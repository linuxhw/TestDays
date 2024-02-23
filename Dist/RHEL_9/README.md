RHEL 9 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for RHEL 9.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/RHEL_9/Desktop/README.md) and [notebooks](/Dist/RHEL_9/Notebook/README.md).

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

Total: 104

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [23c12f49f6](https://linux-hardware.org/?probe=23c12f49f6) | Jan 27, 2024 |
| Dell          | Inspiron N5040              | Notebook    | [7cd09c7dde](https://linux-hardware.org/?probe=7cd09c7dde) | Jan 25, 2024 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [6d4d5ee6c7](https://linux-hardware.org/?probe=6d4d5ee6c7) | Jan 25, 2024 |
| LG Electro... | 15Z95P-GRLGL                | Notebook    | [ce6c983048](https://linux-hardware.org/?probe=ce6c983048) | Jan 24, 2024 |
| LG Electro... | 15Z95P-GRLGL                | Notebook    | [9dcc8bbc45](https://linux-hardware.org/?probe=9dcc8bbc45) | Jan 24, 2024 |
| Dell          | Precision M4800             | Notebook    | [dccdba8512](https://linux-hardware.org/?probe=dccdba8512) | Jan 21, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [cb116dae9c](https://linux-hardware.org/?probe=cb116dae9c) | Jan 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d4e6e0ae3e](https://linux-hardware.org/?probe=d4e6e0ae3e) | Jan 19, 2024 |
| MSI           | Katana GF76 12UC            | Notebook    | [73c3208c03](https://linux-hardware.org/?probe=73c3208c03) | Jan 10, 2024 |
| MSI           | Katana GF76 12UC            | Notebook    | [15db2ea112](https://linux-hardware.org/?probe=15db2ea112) | Jan 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [2bb251ffbb](https://linux-hardware.org/?probe=2bb251ffbb) | Jan 09, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [1abf742848](https://linux-hardware.org/?probe=1abf742848) | Jan 09, 2024 |
| Dell          | Precision 3480              | Notebook    | [e81f3e856b](https://linux-hardware.org/?probe=e81f3e856b) | Jan 03, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [55f164e414](https://linux-hardware.org/?probe=55f164e414) | Dec 20, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b758a439b8](https://linux-hardware.org/?probe=b758a439b8) | Dec 20, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [c492be4899](https://linux-hardware.org/?probe=c492be4899) | Dec 04, 2023 |
| Dell          | Precision 7530              | Notebook    | [e75b16ca5e](https://linux-hardware.org/?probe=e75b16ca5e) | Dec 03, 2023 |
| Lenovo        | ThinkPad L480 20LS0015UK    | Notebook    | [5f786955fc](https://linux-hardware.org/?probe=5f786955fc) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-14IKB U 81F... | Notebook    | [0b06f82d9d](https://linux-hardware.org/?probe=0b06f82d9d) | Nov 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [367bde5a11](https://linux-hardware.org/?probe=367bde5a11) | Nov 03, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [e356c02979](https://linux-hardware.org/?probe=e356c02979) | Oct 30, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [79f6aee2c7](https://linux-hardware.org/?probe=79f6aee2c7) | Oct 24, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [1c3bf8f6ef](https://linux-hardware.org/?probe=1c3bf8f6ef) | Oct 19, 2023 |
| System76      | Galago Pro                  | Notebook    | [fbdb665814](https://linux-hardware.org/?probe=fbdb665814) | Oct 03, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| Intel         | NUC12WSBi7 M63355-302       | Mini pc     | [043bac31d2](https://linux-hardware.org/?probe=043bac31d2) | Sep 28, 2023 |
| Dell          | G16 7620                    | Notebook    | [cd30e51d53](https://linux-hardware.org/?probe=cd30e51d53) | Sep 27, 2023 |
| Dell          | Precision 7720              | Notebook    | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ff1efba80e](https://linux-hardware.org/?probe=ff1efba80e) | Sep 13, 2023 |
| Acer          | Aspire C24-865              | All in one  | [de824a4f4e](https://linux-hardware.org/?probe=de824a4f4e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T490 20N3S77601    | Notebook    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c190907cc8](https://linux-hardware.org/?probe=c190907cc8) | Aug 29, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f88687d2f0](https://linux-hardware.org/?probe=f88687d2f0) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f6892c6532](https://linux-hardware.org/?probe=f6892c6532) | Aug 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [eb99d95702](https://linux-hardware.org/?probe=eb99d95702) | Aug 08, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [de07e937bb](https://linux-hardware.org/?probe=de07e937bb) | Aug 04, 2023 |
| HP            | 0AECh D                     | Desktop     | [b9ea790e39](https://linux-hardware.org/?probe=b9ea790e39) | Jul 24, 2023 |
| HP            | 0AECh D                     | Desktop     | [078f0cd045](https://linux-hardware.org/?probe=078f0cd045) | Jul 24, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [0d8b3d7c32](https://linux-hardware.org/?probe=0d8b3d7c32) | Jun 20, 2023 |
| Lenovo        | STA7B38870 02               | Server      | [80a2f3d367](https://linux-hardware.org/?probe=80a2f3d367) | Jun 18, 2023 |
| Dell          | 07T4MC A02                  | Desktop     | [ad310dd147](https://linux-hardware.org/?probe=ad310dd147) | Jun 09, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [a3a157f327](https://linux-hardware.org/?probe=a3a157f327) | May 21, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2afc4ee693](https://linux-hardware.org/?probe=2afc4ee693) | May 18, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [49ecdacd71](https://linux-hardware.org/?probe=49ecdacd71) | May 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [5938e62d47](https://linux-hardware.org/?probe=5938e62d47) | Apr 17, 2023 |
| Dell          | Precision 7510              | Notebook    | [f68123c20a](https://linux-hardware.org/?probe=f68123c20a) | Apr 13, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [18c5e3c7c3](https://linux-hardware.org/?probe=18c5e3c7c3) | Apr 10, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [de656b2182](https://linux-hardware.org/?probe=de656b2182) | Apr 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0077b88576](https://linux-hardware.org/?probe=0077b88576) | Apr 06, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [68731ac4ec](https://linux-hardware.org/?probe=68731ac4ec) | Mar 31, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [898059efa5](https://linux-hardware.org/?probe=898059efa5) | Mar 28, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [1821e3657a](https://linux-hardware.org/?probe=1821e3657a) | Mar 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | Notebook    | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Dell          | Precision 7560              | Notebook    | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [98f5768c61](https://linux-hardware.org/?probe=98f5768c61) | Jan 22, 2023 |
| Dell          | Latitude 9420               | Notebook    | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| MSI           | GE72VR 7RF                  | Notebook    | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| Dell          | Latitude E7450              | Notebook    | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| Dell          | 0RN4PJ A02                  | Server      | [84012f61ff](https://linux-hardware.org/?probe=84012f61ff) | Nov 03, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP            | 340S G7                     | Notebook    | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Acer          | Aspire XC-330               | Desktop     | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Dell          | Precision 7510              | Notebook    | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [4776ecdc2a](https://linux-hardware.org/?probe=4776ecdc2a) | Jul 15, 2022 |
| Intel         | H81                         | Desktop     | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [ab729dc8a5](https://linux-hardware.org/?probe=ab729dc8a5) | Jul 04, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [1cb6aead26](https://linux-hardware.org/?probe=1cb6aead26) | Jul 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | Notebook    | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Notebook    | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.14.0-284.30.1.el9_2.x86_64 | 9         | 10.84%  |
| 5.14.0-162.6.1.el9_1.x86_64  | 9         | 10.84%  |
| 5.14.0-284.25.1.el9_2.x86_64 | 7         | 8.43%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 6         | 7.23%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 6         | 7.23%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 6         | 7.23%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 5         | 6.02%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 4         | 4.82%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 4         | 4.82%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 4         | 4.82%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 4         | 4.82%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 3         | 3.61%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 3         | 3.61%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 2.41%   |
| 5.14.0-362.18.1.el9_3.x86_64 | 2         | 2.41%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 2.41%   |
| 6.7.1-1.el9.elrepo.x86_64    | 1         | 1.2%    |
| 6.5.2-1.el9.elrepo.x86_64    | 1         | 1.2%    |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 1.2%    |
| 5.14.0-70.17.1.el9_0.aarch64 | 1         | 1.2%    |
| 5.14.0-39.el9.x86_64         | 1         | 1.2%    |
| 5.14.0-284.18.1.el9_2.x86_64 | 1         | 1.2%    |
| 5.14.0-1.7.1.el9.x86_64      | 1         | 1.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 77        | 97.47%  |
| 6.7.1   | 1         | 1.27%   |
| 6.5.2   | 1         | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 77        | 97.47%  |
| 6.7     | 1         | 1.27%   |
| 6.5     | 1         | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 78        | 98.73%  |
| aarch64 | 1         | 1.27%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 72        | 90%     |
| KDE5            | 2         | 2.5%    |
| GNOME Classic   | 2         | 2.5%    |
| XFCE            | 1         | 1.25%   |
| GNOME Flashback | 1         | 1.25%   |
| Cinnamon        | 1         | 1.25%   |
| Unknown         | 1         | 1.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 57        | 72.15%  |
| X11     | 20        | 25.32%  |
| Tty     | 2         | 2.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 47        | 59.49%  |
| GDM     | 31        | 39.24%  |
| SDDM    | 1         | 1.27%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 54        | 68.35%  |
| en_GB | 7         | 8.86%   |
| pt_BR | 4         | 5.06%   |
| en_IN | 3         | 3.8%    |
| en_NZ | 2         | 2.53%   |
| cs_CZ | 2         | 2.53%   |
| ru_RU | 1         | 1.27%   |
| ro_RO | 1         | 1.27%   |
| ja_JP | 1         | 1.27%   |
| es_ES | 1         | 1.27%   |
| en_ZA | 1         | 1.27%   |
| en_CA | 1         | 1.27%   |
| C     | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 71        | 89.87%  |
| BIOS | 8         | 10.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 75        | 94.94%  |
| Ext4 | 4         | 5.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 45        | 56.96%  |
| GPT     | 31        | 39.24%  |
| MBR     | 3         | 3.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 87.34%  |
| Yes       | 10        | 12.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 91.14%  |
| Yes       | 7         | 8.86%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 16        | 20.25%  |
| Lenovo                  | 14        | 17.72%  |
| ASUSTek Computer        | 11        | 13.92%  |
| MSI                     | 9         | 11.39%  |
| Hewlett-Packard         | 7         | 8.86%   |
| Gigabyte Technology     | 6         | 7.59%   |
| Intel                   | 3         | 3.8%    |
| Unknown                 | 3         | 3.8%    |
| ASRock                  | 2         | 2.53%   |
| Acer                    | 2         | 2.53%   |
| System76                | 1         | 1.27%   |
| Samsung Electronics     | 1         | 1.27%   |
| Razer                   | 1         | 1.27%   |
| Raspberry Pi Foundation | 1         | 1.27%   |
| LG Electronics          | 1         | 1.27%   |
| Hardkernel              | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 3         | 3.8%    |
| Gigabyte B550M AORUS PRO-P                  | 2         | 2.53%   |
| System76 Galago Pro                         | 1         | 1.27%   |
| Samsung 730QCJ/730QCR                       | 1         | 1.27%   |
| Razer Blade 15 Mid 2019-Base                | 1         | 1.27%   |
| RPi Raspberry Pi 4 Model B                  | 1         | 1.27%   |
| MSI MS-7D54                                 | 1         | 1.27%   |
| MSI MS-7D25                                 | 1         | 1.27%   |
| MSI MS-7C95                                 | 1         | 1.27%   |
| MSI MS-7B89                                 | 1         | 1.27%   |
| MSI MS-7A71                                 | 1         | 1.27%   |
| MSI Katana GF76 12UC                        | 1         | 1.27%   |
| MSI Katana GF66 12UC                        | 1         | 1.27%   |
| MSI GP75 Leopard 9SD                        | 1         | 1.27%   |
| MSI GE72VR 7RF                              | 1         | 1.27%   |
| LG 15Z95P-GRLGL                             | 1         | 1.27%   |
| Lenovo ThinkSystem SR950 V3                 | 1         | 1.27%   |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US    | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMS1V900 | 1         | 1.27%   |
| Lenovo ThinkPad T490 20N3S77601             | 1         | 1.27%   |
| Lenovo ThinkPad S1 Yoga 12 20DK001YMC       | 1         | 1.27%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS       | 1         | 1.27%   |
| Lenovo ThinkPad L480 20LS0015UK             | 1         | 1.27%   |
| Lenovo ThinkPad L14 Gen 3 21C2S1EE00        | 1         | 1.27%   |
| Lenovo ThinkPad Edge E431 62771L7           | 1         | 1.27%   |
| Lenovo ThinkPad E14 20RA001MMZ              | 1         | 1.27%   |
| Lenovo ThinkBook 14-IIL 20SL                | 1         | 1.27%   |
| Lenovo ThinkBook 13s-IWL 20R9               | 1         | 1.27%   |
| Lenovo IdeaPad 330S-14IKB U 81F4            | 1         | 1.27%   |
| Lenovo IdeaPad 320-15IKB 80XL               | 1         | 1.27%   |
| Intel NUC12WSHi7                            | 1         | 1.27%   |
| Intel H81                                   | 1         | 1.27%   |
| Intel DQ77MK AAG39642-400                   | 1         | 1.27%   |
| HP Z800 Workstation                         | 1         | 1.27%   |
| HP ProLiant ML310e Gen8                     | 1         | 1.27%   |
| HP ProBook 640 G2                           | 1         | 1.27%   |
| HP Laptop 14s-dk0xxx                        | 1         | 1.27%   |
| HP EliteBook 855 G7 Notebook PC             | 1         | 1.27%   |
| HP EliteBook 2570p                          | 1         | 1.27%   |
| HP 340S G7                                  | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 9         | 11.39%  |
| Dell Precision       | 8         | 10.13%  |
| Dell Inspiron        | 3         | 3.8%    |
| ASUS TUF             | 3         | 3.8%    |
| ASUS ROG             | 3         | 3.8%    |
| ASUS PRIME           | 3         | 3.8%    |
| Unknown              | 3         | 3.8%    |
| MSI Katana           | 2         | 2.53%   |
| Lenovo ThinkBook     | 2         | 2.53%   |
| Lenovo IdeaPad       | 2         | 2.53%   |
| HP EliteBook         | 2         | 2.53%   |
| Gigabyte B550M       | 2         | 2.53%   |
| Dell Latitude        | 2         | 2.53%   |
| Acer Aspire          | 2         | 2.53%   |
| System76 Galago      | 1         | 1.27%   |
| Samsung 730QCJ       | 1         | 1.27%   |
| Razer Blade          | 1         | 1.27%   |
| RPi Raspberry        | 1         | 1.27%   |
| MSI MS-7D54          | 1         | 1.27%   |
| MSI MS-7D25          | 1         | 1.27%   |
| MSI MS-7C95          | 1         | 1.27%   |
| MSI MS-7B89          | 1         | 1.27%   |
| MSI MS-7A71          | 1         | 1.27%   |
| MSI GP75             | 1         | 1.27%   |
| MSI GE72VR           | 1         | 1.27%   |
| LG 15Z95P-GRLGL      | 1         | 1.27%   |
| Lenovo ThinkSystem   | 1         | 1.27%   |
| Intel NUC12WSHi7     | 1         | 1.27%   |
| Intel H81            | 1         | 1.27%   |
| Intel DQ77MK         | 1         | 1.27%   |
| HP Z800              | 1         | 1.27%   |
| HP ProLiant          | 1         | 1.27%   |
| HP ProBook           | 1         | 1.27%   |
| HP Laptop            | 1         | 1.27%   |
| HP 340S              | 1         | 1.27%   |
| Hardkernel ODROID-H3 | 1         | 1.27%   |
| Gigabyte X670E       | 1         | 1.27%   |
| Gigabyte MU72-SU0-00 | 1         | 1.27%   |
| Gigabyte H510M       | 1         | 1.27%   |
| Gigabyte AERO        | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 13        | 16.46%  |
| 2022 | 12        | 15.19%  |
| 2019 | 11        | 13.92%  |
| 2020 | 8         | 10.13%  |
| 2023 | 6         | 7.59%   |
| 2018 | 6         | 7.59%   |
| 2017 | 6         | 7.59%   |
| 2015 | 4         | 5.06%   |
| 2016 | 3         | 3.8%    |
| 2014 | 3         | 3.8%    |
| 2013 | 2         | 2.53%   |
| 2012 | 2         | 2.53%   |
| 2010 | 2         | 2.53%   |
| 2011 | 1         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 43        | 54.43%  |
| Desktop        | 30        | 37.97%  |
| Server         | 3         | 3.8%    |
| System on chip | 1         | 1.27%   |
| Mini pc        | 1         | 1.27%   |
| All in one     | 1         | 1.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 67        | 83.75%  |
| Enabled  | 13        | 16.25%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 78        | 98.73%  |
| Yes  | 1         | 1.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 29        | 36.71%  |
| 4.01-8.0        | 16        | 20.25%  |
| 32.01-64.0      | 15        | 18.99%  |
| 64.01-256.0     | 7         | 8.86%   |
| 3.01-4.0        | 5         | 6.33%   |
| 16.01-24.0      | 3         | 3.8%    |
| More than 256.0 | 2         | 2.53%   |
| 24.01-32.0      | 2         | 2.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 29        | 34.52%  |
| 4.01-8.0   | 21        | 25%     |
| 3.01-4.0   | 18        | 21.43%  |
| 8.01-16.0  | 9         | 10.71%  |
| 1.01-2.0   | 6         | 7.14%   |
| 32.01-64.0 | 1         | 1.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 49.38%  |
| 2      | 21        | 25.93%  |
| 3      | 10        | 12.35%  |
| 5      | 4         | 4.94%   |
| 4      | 3         | 3.7%    |
| 14     | 1         | 1.23%   |
| 6      | 1         | 1.23%   |
| 0      | 1         | 1.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 63        | 79.75%  |
| Yes       | 16        | 20.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 86.08%  |
| No        | 11        | 13.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 78.75%  |
| No        | 17        | 21.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 65.43%  |
| No        | 28        | 34.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25        | 31.65%  |
| India        | 8         | 10.13%  |
| UK           | 5         | 6.33%   |
| Canada       | 4         | 5.06%   |
| Brazil       | 4         | 5.06%   |
| Guatemala    | 3         | 3.8%    |
| Turkey       | 2         | 2.53%   |
| Spain        | 2         | 2.53%   |
| Russia       | 2         | 2.53%   |
| New Zealand  | 2         | 2.53%   |
| Italy        | 2         | 2.53%   |
| Czechia      | 2         | 2.53%   |
| Chile        | 2         | 2.53%   |
| Switzerland  | 1         | 1.27%   |
| Sri Lanka    | 1         | 1.27%   |
| South Korea  | 1         | 1.27%   |
| South Africa | 1         | 1.27%   |
| Slovakia     | 1         | 1.27%   |
| Saint Lucia  | 1         | 1.27%   |
| Romania      | 1         | 1.27%   |
| Norway       | 1         | 1.27%   |
| Netherlands  | 1         | 1.27%   |
| Kenya        | 1         | 1.27%   |
| Jordan       | 1         | 1.27%   |
| Japan        | 1         | 1.27%   |
| Indonesia    | 1         | 1.27%   |
| Germany      | 1         | 1.27%   |
| Finland      | 1         | 1.27%   |
| Egypt        | 1         | 1.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Guatemala City      | 3         | 3.66%   |
| Wellington          | 2         | 2.44%   |
| Santiago            | 2         | 2.44%   |
| Zlín               | 1         | 1.22%   |
| Wildomar            | 1         | 1.22%   |
| Whiteley            | 1         | 1.22%   |
| Wake Forest         | 1         | 1.22%   |
| Valencia            | 1         | 1.22%   |
| Valbrembo           | 1         | 1.22%   |
| Tokyo               | 1         | 1.22%   |
| Sutton              | 1         | 1.22%   |
| Stratham            | 1         | 1.22%   |
| Stavropol           | 1         | 1.22%   |
| Skien               | 1         | 1.22%   |
| Sierra Vista        | 1         | 1.22%   |
| Seoul               | 1         | 1.22%   |
| Sao Paulo           | 1         | 1.22%   |
| Sainte-Marie        | 1         | 1.22%   |
| Saint Paul          | 1         | 1.22%   |
| Rio de Janeiro      | 1         | 1.22%   |
| Ribeirao Preto      | 1         | 1.22%   |
| Râmnicu Vâlcea    | 1         | 1.22%   |
| Providence          | 1         | 1.22%   |
| Prairieville        | 1         | 1.22%   |
| Piracicaba          | 1         | 1.22%   |
| Phoenix             | 1         | 1.22%   |
| Pforzheim           | 1         | 1.22%   |
| Parker              | 1         | 1.22%   |
| Oldham              | 1         | 1.22%   |
| Nuenen              | 1         | 1.22%   |
| Newham              | 1         | 1.22%   |
| Newcastle upon Tyne | 1         | 1.22%   |
| New Delhi           | 1         | 1.22%   |
| Nairobi             | 1         | 1.22%   |
| Montgomery          | 1         | 1.22%   |
| Mohegan Lake        | 1         | 1.22%   |
| Milano              | 1         | 1.22%   |
| Mattapoisett        | 1         | 1.22%   |
| Maltepe             | 1         | 1.22%   |
| Liberec             | 1         | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 27        | 32     | 20.3%   |
| WDC                         | 15        | 23     | 11.28%  |
| Seagate                     | 15        | 23     | 11.28%  |
| Sandisk                     | 9         | 13     | 6.77%   |
| Unknown                     | 6         | 9      | 4.51%   |
| Toshiba                     | 5         | 5      | 3.76%   |
| Micron Technology           | 5         | 5      | 3.76%   |
| SK hynix                    | 4         | 4      | 3.01%   |
| Micron/Crucial Technology   | 4         | 6      | 3.01%   |
| KIOXIA                      | 4         | 5      | 3.01%   |
| Kingston                    | 4         | 4      | 3.01%   |
| Intel                       | 4         | 9      | 3.01%   |
| Phison                      | 3         | 3      | 2.26%   |
| HGST                        | 3         | 3      | 2.26%   |
| China                       | 3         | 3      | 2.26%   |
| SABRENT                     | 2         | 2      | 1.5%    |
| Phison Electronics          | 2         | 3      | 1.5%    |
| Kingston Technology Company | 2         | 2      | 1.5%    |
| KingSpec                    | 2         | 2      | 1.5%    |
| Crucial                     | 2         | 3      | 1.5%    |
| ADATA Technology            | 2         | 2      | 1.5%    |
| XUM                         | 1         | 1      | 0.75%   |
| SSSTC                       | 1         | 1      | 0.75%   |
| PNY                         | 1         | 1      | 0.75%   |
| Plextor                     | 1         | 1      | 0.75%   |
| Kingmax                     | 1         | 1      | 0.75%   |
| Hitachi                     | 1         | 1      | 0.75%   |
| Golden                      | 1         | 1      | 0.75%   |
| Gigabyte Technology         | 1         | 1      | 0.75%   |
| Fantom                      | 1         | 1      | 0.75%   |
| A-DATA Technology           | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 5         | 3.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4         | 2.61%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                | 3         | 1.96%   |
| WDC WDBNCE5000PNC 500GB SSD                        | 2         | 1.31%   |
| Unknown MMC Card  256GB                            | 2         | 1.31%   |
| Seagate ST1000DM010-2EP102 1TB                     | 2         | 1.31%   |
| Sandisk WD Blue SN570 500GB                        | 2         | 1.31%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB    | 2         | 1.31%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 2         | 1.31%   |
| Samsung SSD 990 PRO 2TB                            | 2         | 1.31%   |
| Samsung SSD 870 EVO 1TB                            | 2         | 1.31%   |
| SABRENT Disk 500GB                                 | 2         | 1.31%   |
| Phison E16 PCIe4 NVMe Controller 2TB               | 2         | 1.31%   |
| Micron 2400_MTFDKBA512QFM 512GB                    | 2         | 1.31%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                         | 2         | 1.31%   |
| Kingston Company SNV2S250G 250GB                   | 2         | 1.31%   |
| Intel SSD 660P Series 1024GB                       | 2         | 1.31%   |
| HGST HTS721010A9E630 1TB                           | 2         | 1.31%   |
| XUM HX256GSSDSATA3 256GB                           | 1         | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.65%   |
| WDC WDBA3V5000ANC-WRSN 500GB                       | 1         | 0.65%   |
| WDC WD80EFAX-68KNBN0 8TB                           | 1         | 0.65%   |
| WDC WD5000AVDS-63U7B0 500GB                        | 1         | 0.65%   |
| WDC WD5000AVCS-632DY1 500GB                        | 1         | 0.65%   |
| WDC WD50 00LPVX-22V0TT0 500GB                      | 1         | 0.65%   |
| WDC WD40EFRX-68N32N0 4TB                           | 1         | 0.65%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 1         | 0.65%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 1         | 0.65%   |
| WDC WD20EZAZ-00GGJB0 2TB                           | 1         | 0.65%   |
| WDC WD20EARX-008FB0 2TB                            | 1         | 0.65%   |
| WDC WD141KFGX-68FH9N0 14TB                         | 1         | 0.65%   |
| WDC WD140EFGX-68B0GN0 14TB                         | 1         | 0.65%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 0.65%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 0.65%   |
| WDC WD10SPSX-00A6WT0 1TB                           | 1         | 0.65%   |
| WDC WD10JPLX-00MBPT0 1TB                           | 1         | 0.65%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1         | 0.65%   |
| WDC WD10EZEX-00BBHA0 1TB                           | 1         | 0.65%   |
| WDC WD100EFAX-68LHPN0 10TB                         | 1         | 0.65%   |
| Unknown SDU1  64GB                                 | 1         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 23     | 39.47%  |
| WDC     | 12        | 19     | 31.58%  |
| Toshiba | 5         | 5      | 13.16%  |
| HGST    | 3         | 3      | 7.89%   |
| Unknown | 1         | 1      | 2.63%   |
| Hitachi | 1         | 1      | 2.63%   |
| Fantom  | 1         | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 31.43%  |
| WDC                 | 3         | 3      | 8.57%   |
| China               | 3         | 3      | 8.57%   |
| SanDisk             | 2         | 2      | 5.71%   |
| SABRENT             | 2         | 2      | 5.71%   |
| Kingston            | 2         | 2      | 5.71%   |
| KingSpec            | 2         | 2      | 5.71%   |
| Intel               | 2         | 4      | 5.71%   |
| Crucial             | 2         | 2      | 5.71%   |
| XUM                 | 1         | 1      | 2.86%   |
| SK hynix            | 1         | 1      | 2.86%   |
| PNY                 | 1         | 1      | 2.86%   |
| Plextor             | 1         | 1      | 2.86%   |
| Kingmax             | 1         | 1      | 2.86%   |
| Gigabyte Technology | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 54        | 71     | 44.26%  |
| SSD     | 31        | 38     | 25.41%  |
| HDD     | 31        | 53     | 25.41%  |
| MMC     | 4         | 4      | 3.28%   |
| Unknown | 2         | 5      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 54        | 71     | 48.65%  |
| SATA | 47        | 85     | 42.34%  |
| SAS  | 6         | 11     | 5.41%   |
| MMC  | 4         | 4      | 3.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 37     | 42.19%  |
| 0.51-1.0   | 20        | 26     | 31.25%  |
| 1.01-2.0   | 6         | 7      | 9.38%   |
| 4.01-10.0  | 4         | 7      | 6.25%   |
| 3.01-4.0   | 3         | 7      | 4.69%   |
| 2.01-3.0   | 2         | 3      | 3.13%   |
| 10.01-20.0 | 2         | 4      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 30.86%  |
| 251-500        | 18        | 22.22%  |
| 501-1000       | 14        | 17.28%  |
| 1001-2000      | 11        | 13.58%  |
| More than 3000 | 5         | 6.17%   |
| 51-100         | 4         | 4.94%   |
| 21-50          | 3         | 3.7%    |
| Unknown        | 1         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 31        | 38.27%  |
| 21-50          | 21        | 25.93%  |
| 51-100         | 11        | 13.58%  |
| 251-500        | 6         | 7.41%   |
| 101-250        | 6         | 7.41%   |
| More than 3000 | 2         | 2.47%   |
| 1001-2000      | 2         | 2.47%   |
| 2001-3000      | 1         | 1.23%   |
| Unknown        | 1         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD50 00LPVX-22V0TT0 500GB                  | 1         | 1      | 14.29%  |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 14.29%  |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 14.29%  |
| Seagate ST1000DM010-2EP102 1TB                 | 1         | 1      | 14.29%  |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 1         | 1      | 14.29%  |
| Intel SSDSC2BA800G4R 800GB                     | 1         | 2      | 14.29%  |
| Crucial CT1000BX500SSD1 1TB                    | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 3         | 3      | 42.86%  |
| WDC                       | 1         | 1      | 14.29%  |
| Micron/Crucial Technology | 1         | 1      | 14.29%  |
| Intel                     | 1         | 2      | 14.29%  |
| Crucial                   | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 75%     |
| WDC     | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 50%     |
| SSD  | 2         | 3      | 33.33%  |
| NVMe | 1         | 1      | 16.67%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 52        | 105    | 61.18%  |
| Works    | 27        | 58     | 31.76%  |
| Malfunc  | 6         | 8      | 7.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 55        | 44%     |
| Samsung Electronics         | 17        | 13.6%   |
| AMD                         | 12        | 9.6%    |
| SanDisk                     | 8         | 6.4%    |
| Phison Electronics          | 5         | 4%      |
| Micron/Crucial Technology   | 5         | 4%      |
| Micron Technology           | 5         | 4%      |
| KIOXIA                      | 4         | 3.2%    |
| Kingston Technology Company | 4         | 3.2%    |
| SK hynix                    | 3         | 2.4%    |
| ADATA Technology            | 3         | 2.4%    |
| Broadcom / LSI              | 2         | 1.6%    |
| ASMedia Technology          | 2         | 1.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 4.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 4.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.35%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 4.35%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 3.62%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 2.9%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 2.17%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 2.17%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 2.17%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 2.17%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 3         | 2.17%   |
| Intel SSD 660P Series                                                          | 3         | 2.17%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 2.17%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 2.17%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 2.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.17%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 2.17%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.45%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 1.45%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2         | 1.45%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 1.45%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2         | 1.45%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.45%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 2         | 1.45%   |
| Kingston Company NV2 NVMe SSD E21T (DRAM-less)                                 | 2         | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 2         | 1.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.45%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2         | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.45%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 2         | 1.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.45%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.45%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 2         | 1.45%   |
| AMD 600 Series Chipset SATA Controller                                         | 2         | 1.45%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.72%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 55        | 44%     |
| NVMe | 53        | 42.4%   |
| RAID | 15        | 12%     |
| SAS  | 1         | 0.8%    |
| IDE  | 1         | 0.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 65        | 82.28%  |
| AMD    | 13        | 16.46%  |
| ARM    | 1         | 1.27%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 3.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 3.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 2.53%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 2.53%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 2.53%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 2         | 2.53%   |
| Intel 12th Gen Core i9-12900K           | 2         | 2.53%   |
| Intel 12th Gen Core i7-12700H           | 2         | 2.53%   |
| Intel 12th Gen Core i7-1260P            | 2         | 2.53%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 2         | 2.53%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2         | 2.53%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 2.53%   |
| Intel Xeon W-11855M CPU @ 3.20GHz       | 1         | 1.27%   |
| Intel Xeon Silver 4310 CPU @ 2.10GHz    | 1         | 1.27%   |
| Intel Xeon Platinum 8468H               | 1         | 1.27%   |
| Intel Xeon Platinum 8168 CPU @ 2.70GHz  | 1         | 1.27%   |
| Intel Xeon CPU X5570 @ 2.93GHz          | 1         | 1.27%   |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz     | 1         | 1.27%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz     | 1         | 1.27%   |
| Intel Pentium Silver N6005 @ 2.00GHz    | 1         | 1.27%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 1.27%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 1.27%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 1.27%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.27%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.27%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.27%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 1.27%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 1         | 1.27%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.27%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 1         | 1.27%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 1         | 1.27%   |
| Intel Core i5-3470S CPU @ 2.90GHz       | 1         | 1.27%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.27%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 1         | 1.27%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 21        | 26.58%  |
| Intel Core i5        | 16        | 20.25%  |
| Intel Core i7        | 13        | 16.46%  |
| Intel Core i3        | 5         | 6.33%   |
| AMD Ryzen 5          | 5         | 6.33%   |
| Intel Xeon           | 4         | 5.06%   |
| AMD Ryzen 9          | 4         | 5.06%   |
| Intel Xeon Platinum  | 2         | 2.53%   |
| Intel Celeron        | 2         | 2.53%   |
| Intel Xeon Silver    | 1         | 1.27%   |
| Intel Pentium Silver | 1         | 1.27%   |
| Intel Core i9        | 1         | 1.27%   |
| AMD Ryzen 7 PRO      | 1         | 1.27%   |
| AMD Ryzen 7          | 1         | 1.27%   |
| AMD Athlon X4        | 1         | 1.27%   |
| AMD A4               | 1         | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 26        | 32.91%  |
| 2      | 14        | 17.72%  |
| 8      | 11        | 13.92%  |
| 6      | 9         | 11.39%  |
| 12     | 6         | 7.59%   |
| 10     | 4         | 5.06%   |
| 14     | 3         | 3.8%    |
| 16     | 2         | 2.53%   |
| 384    | 1         | 1.27%   |
| 48     | 1         | 1.27%   |
| 24     | 1         | 1.27%   |
| 1      | 1         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 76        | 96.2%   |
| 2      | 2         | 2.53%   |
| 8      | 1         | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 66        | 83.54%  |
| 1      | 13        | 16.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 79        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 16.46%  |
| 0x806ec    | 6         | 7.59%   |
| 0x306a9    | 5         | 6.33%   |
| 0x906a3    | 4         | 5.06%   |
| 0x806d1    | 4         | 5.06%   |
| 0xa0671    | 3         | 3.8%    |
| 0x506e3    | 3         | 3.8%    |
| 0x08701021 | 3         | 3.8%    |
| 0x906ea    | 2         | 2.53%   |
| 0x906e9    | 2         | 2.53%   |
| 0x906c0    | 2         | 2.53%   |
| 0x90672    | 2         | 2.53%   |
| 0x806ea    | 2         | 2.53%   |
| 0x706e5    | 2         | 2.53%   |
| 0x406e3    | 2         | 2.53%   |
| 0x306c3    | 2         | 2.53%   |
| 0x0a20120a | 2         | 2.53%   |
| 0xb0671    | 1         | 1.27%   |
| 0x906ed    | 1         | 1.27%   |
| 0x906a4    | 1         | 1.27%   |
| 0x806f6    | 1         | 1.27%   |
| 0x706a8    | 1         | 1.27%   |
| 0x606a6    | 1         | 1.27%   |
| 0x50654    | 1         | 1.27%   |
| 0x406f1    | 1         | 1.27%   |
| 0x40651    | 1         | 1.27%   |
| 0x306d4    | 1         | 1.27%   |
| 0x20655    | 1         | 1.27%   |
| 0x106a5    | 1         | 1.27%   |
| 0x0a601206 | 1         | 1.27%   |
| 0x0a601203 | 1         | 1.27%   |
| 0x0a50000f | 1         | 1.27%   |
| 0x0a50000c | 1         | 1.27%   |
| 0x08600106 | 1         | 1.27%   |
| 0x08108109 | 1         | 1.27%   |
| 0x06006705 | 1         | 1.27%   |
| 0x0600611a | 1         | 1.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 16        | 20.25%  |
| Alderlake Hybrid | 13        | 16.46%  |
| Icelake          | 10        | 12.66%  |
| Skylake          | 6         | 7.59%   |
| IvyBridge        | 6         | 7.59%   |
| Zen 3            | 4         | 5.06%   |
| Zen 2            | 4         | 5.06%   |
| Haswell          | 3         | 3.8%    |
| Broadwell        | 3         | 3.8%    |
| Unknown          | 3         | 3.8%    |
| Westmere         | 2         | 2.53%   |
| Tremont          | 2         | 2.53%   |
| Excavator        | 2         | 2.53%   |
| Zen+             | 1         | 1.27%   |
| TigerLake        | 1         | 1.27%   |
| Sapphire Rapids  | 1         | 1.27%   |
| Nehalem          | 1         | 1.27%   |
| Goldmont plus    | 1         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 48        | 51.61%  |
| Nvidia                     | 26        | 27.96%  |
| AMD                        | 16        | 17.2%   |
| ASPEED Technology          | 2         | 2.15%   |
| Matrox Electronics Systems | 1         | 1.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                         | 4         | 4.17%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                    | 4         | 4.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]              | 3         | 3.13%   |
| Intel UHD Graphics 620                                       | 3         | 3.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                    | 3         | 3.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]      | 3         | 3.13%   |
| Nvidia TU117GL [T400 4GB]                                    | 2         | 2.08%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                   | 2         | 2.08%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                      | 2         | 2.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                   | 2         | 2.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                         | 2         | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                          | 2         | 2.08%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                    | 2         | 2.08%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                       | 2         | 2.08%   |
| Intel JasperLake [UHD Graphics]                              | 2         | 2.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                       | 2         | 2.08%   |
| Intel HD Graphics 630                                        | 2         | 2.08%   |
| Intel HD Graphics 5500                                       | 2         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller          | 2         | 2.08%   |
| Intel AlderLake-S GT1                                        | 2         | 2.08%   |
| Intel 3rd Gen Core processor Graphics Controller             | 2         | 2.08%   |
| ASPEED Technology ASPEED Graphics Family                     | 2         | 2.08%   |
| AMD Raphael                                                  | 2         | 2.08%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]               | 2         | 2.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series] | 2         | 2.08%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                           | 1         | 1.04%   |
| Nvidia GT218 [GeForce G210]                                  | 1         | 1.04%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                      | 1         | 1.04%   |
| Nvidia GP104GLM [Quadro P3000 Mobile]                        | 1         | 1.04%   |
| Nvidia GP104GL [Quadro P4000]                                | 1         | 1.04%   |
| Nvidia GP104 [GeForce GTX 1070]                              | 1         | 1.04%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                           | 1         | 1.04%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                           | 1         | 1.04%   |
| Nvidia GM206GL [Quadro M2000]                                | 1         | 1.04%   |
| Nvidia GK208B [GeForce GT 730]                               | 1         | 1.04%   |
| Nvidia GK107GLM [Quadro K1100M]                              | 1         | 1.04%   |
| Nvidia GK106 [GeForce GTX 660]                               | 1         | 1.04%   |
| Nvidia GA106 [Geforce RTX 3050]                              | 1         | 1.04%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                           | 1         | 1.04%   |
| Nvidia GA102 [GeForce RTX 3090]                              | 1         | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 43.04%  |
| 1 x Nvidia     | 16        | 20.25%  |
| 1 x AMD        | 10        | 12.66%  |
| Intel + Nvidia | 9         | 11.39%  |
| Intel + AMD    | 3         | 3.8%    |
| 2 x AMD        | 2         | 2.53%   |
| Other          | 1         | 1.27%   |
| 2 x Nvidia     | 1         | 1.27%   |
| 1 x Matrox     | 1         | 1.27%   |
| 1 x ASPEED     | 1         | 1.27%   |
| AMD + ASPEED   | 1         | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 66        | 83.54%  |
| Proprietary | 10        | 12.66%  |
| Unknown     | 3         | 3.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 49.37%  |
| 1.01-2.0   | 8         | 10.13%  |
| 7.01-8.0   | 7         | 8.86%   |
| 3.01-4.0   | 7         | 8.86%   |
| 5.01-6.0   | 5         | 6.33%   |
| 8.01-16.0  | 4         | 5.06%   |
| 0.01-0.5   | 4         | 5.06%   |
| 16.01-24.0 | 3         | 3.8%    |
| 2.01-3.0   | 1         | 1.27%   |
| 0.51-1.0   | 1         | 1.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 12        | 13.19%  |
| BOE                  | 10        | 10.99%  |
| LG Display           | 9         | 9.89%   |
| Dell                 | 9         | 9.89%   |
| Chimei Innolux       | 7         | 7.69%   |
| AU Optronics         | 6         | 6.59%   |
| Acer                 | 5         | 5.49%   |
| Goldstar             | 4         | 4.4%    |
| AOC                  | 3         | 3.3%    |
| Sharp                | 2         | 2.2%    |
| Lenovo               | 2         | 2.2%    |
| Hewlett-Packard      | 2         | 2.2%    |
| Gigabyte Technology  | 2         | 2.2%    |
| CSO                  | 2         | 2.2%    |
| Unknown              | 2         | 2.2%    |
| Vizio                | 1         | 1.1%    |
| Unknown              | 1         | 1.1%    |
| STD                  | 1         | 1.1%    |
| Sony                 | 1         | 1.1%    |
| Philips              | 1         | 1.1%    |
| Panasonic            | 1         | 1.1%    |
| OUT                  | 1         | 1.1%    |
| InfoVision           | 1         | 1.1%    |
| Haier                | 1         | 1.1%    |
| Deco Gear            | 1         | 1.1%    |
| CEX                  | 1         | 1.1%    |
| BOE Technology Group | 1         | 1.1%    |
| BenQ                 | 1         | 1.1%    |
| ASUSTek Computer     | 1         | 1.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                      | 2         | 2.13%   |
| Unknown                                                                 | 2         | 2.13%   |
| Vizio E32-C1 VIZ1004 1920x1080 698x392mm 31.5-inch                      | 1         | 1.06%   |
| Unknown LCD Monitor SAMSUNG                                             | 1         | 1.06%   |
| STD HDMI STD0110 1440x900 420x240mm 19.0-inch                           | 1         | 1.06%   |
| Sony TV SNYD703 1360x768                                                | 1         | 1.06%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch                 | 1         | 1.06%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                 | 1         | 1.06%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch    | 1         | 1.06%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch    | 1         | 1.06%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch    | 1         | 1.06%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 509x286mm 23.0-inch    | 1         | 1.06%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch       | 1         | 1.06%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 520x290mm 23.4-inch       | 1         | 1.06%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch       | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch    | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 950x540mm 43.0-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor S34J55x 7280x2160                       | 1         | 1.06%   |
| Philips PHL 322E1 PHLC20F 1920x1080 698x393mm 31.5-inch                 | 1         | 1.06%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                      | 1         | 1.06%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                         | 1         | 1.06%   |
| LG Display LCD Monitor LGD0753 1920x1080 309x174mm 14.0-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0645 1920x1080 344x194mm 15.5-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0613 1920x1080 309x174mm 14.0-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch             | 1         | 1.06%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch                | 1         | 1.06%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch              | 1         | 1.06%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x290mm 23.1-inch              | 1         | 1.06%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch            | 1         | 1.06%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 519x324mm 24.1-inch            | 1         | 1.06%   |
| Hewlett-Packard LCD Monitor Pavilion32                                  | 1         | 1.06%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 41        | 48.81%  |
| 3840x2160 (4K)     | 10        | 11.9%   |
| 1366x768 (WXGA)    | 9         | 10.71%  |
| 2560x1440 (QHD)    | 7         | 8.33%   |
| 1920x1200 (WUXGA)  | 3         | 3.57%   |
| Unknown            | 3         | 3.57%   |
| 1680x1050 (WSXGA+) | 2         | 2.38%   |
| 1280x1024 (SXGA)   | 2         | 2.38%   |
| 7280x2160          | 1         | 1.19%   |
| 5120x1440          | 1         | 1.19%   |
| 3440x1440          | 1         | 1.19%   |
| 2560x1600          | 1         | 1.19%   |
| 2160x1350          | 1         | 1.19%   |
| 1600x900 (HD+)     | 1         | 1.19%   |
| 1280x768           | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 13        | 14.77%  |
| 15      | 11        | 12.5%   |
| 23      | 9         | 10.23%  |
| 14      | 8         | 9.09%   |
| 27      | 6         | 6.82%   |
| 24      | 5         | 5.68%   |
| 21      | 5         | 5.68%   |
| 17      | 5         | 5.68%   |
| Unknown | 5         | 5.68%   |
| 31      | 4         | 4.55%   |
| 84      | 2         | 2.27%   |
| 72      | 2         | 2.27%   |
| 16      | 2         | 2.27%   |
| 64      | 1         | 1.14%   |
| 54      | 1         | 1.14%   |
| 52      | 1         | 1.14%   |
| 43      | 1         | 1.14%   |
| 35      | 1         | 1.14%   |
| 33      | 1         | 1.14%   |
| 26      | 1         | 1.14%   |
| 20      | 1         | 1.14%   |
| 19      | 1         | 1.14%   |
| 18      | 1         | 1.14%   |
| 12      | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 35.63%  |
| 501-600     | 20        | 22.99%  |
| 401-500     | 7         | 8.05%   |
| 351-400     | 5         | 5.75%   |
| 201-300     | 5         | 5.75%   |
| Unknown     | 5         | 5.75%   |
| 601-700     | 4         | 4.6%    |
| 1501-2000   | 4         | 4.6%    |
| 1001-1500   | 3         | 3.45%   |
| 801-900     | 1         | 1.15%   |
| 701-800     | 1         | 1.15%   |
| 901-1000    | 1         | 1.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 59        | 78.67%  |
| 16/10   | 7         | 9.33%   |
| Unknown | 5         | 6.67%   |
| 5/4     | 2         | 2.67%   |
| 4/3     | 1         | 1.33%   |
| 21/9    | 1         | 1.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 17        | 19.32%  |
| 201-250        | 16        | 18.18%  |
| 101-110        | 11        | 12.5%   |
| More than 1000 | 7         | 7.95%   |
| 301-350        | 7         | 7.95%   |
| 351-500        | 6         | 6.82%   |
| Unknown        | 5         | 5.68%   |
| 71-80          | 4         | 4.55%   |
| 121-130        | 4         | 4.55%   |
| 151-200        | 3         | 3.41%   |
| 251-300        | 2         | 2.27%   |
| 141-150        | 2         | 2.27%   |
| 61-70          | 1         | 1.14%   |
| 131-140        | 1         | 1.14%   |
| 111-120        | 1         | 1.14%   |
| 501-1000       | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 25        | 30.12%  |
| 121-160       | 21        | 25.3%   |
| 101-120       | 19        | 22.89%  |
| 161-240       | 8         | 9.64%   |
| Unknown       | 5         | 6.02%   |
| 1-50          | 3         | 3.61%   |
| More than 240 | 2         | 2.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 56        | 70%     |
| 2     | 15        | 18.75%  |
| 0     | 5         | 6.25%   |
| 3     | 2         | 2.5%    |
| 5     | 1         | 1.25%   |
| 4     | 1         | 1.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 50.88%  |
| Realtek Semiconductor | 39        | 34.21%  |
| Qualcomm Atheros      | 5         | 4.39%   |
| Broadcom              | 4         | 3.51%   |
| Tehuti Networks       | 1         | 0.88%   |
| Ralink Technology     | 1         | 0.88%   |
| MediaTek              | 1         | 0.88%   |
| IBM                   | 1         | 0.88%   |
| DisplayLink           | 1         | 0.88%   |
| Broadcom Limited      | 1         | 0.88%   |
| ASUSTek Computer      | 1         | 0.88%   |
| Aquantia              | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 18        | 12.08%  |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 5.37%   |
| Intel Ethernet Controller I225-V                                       | 8         | 5.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 4.7%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6         | 4.03%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 4.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 3.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 5         | 3.36%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 2.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 2.68%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 2.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1.34%   |
| Intel Wireless 8265 / 8275                                             | 2         | 1.34%   |
| Intel Wireless 8260                                                    | 2         | 1.34%   |
| Intel Wireless 7265                                                    | 2         | 1.34%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 2         | 1.34%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 1.34%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.34%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 1.34%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.34%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.34%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 2         | 1.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 1.34%   |
| Tehuti Networks TN9710P 10GBase-T/NBASE-T Ethernet Adapter             | 1         | 0.67%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.67%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1         | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.67%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.67%   |
| Realtek 802.11n WLAN Adapter                                           | 1         | 0.67%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1         | 0.67%   |
| Intel Wireless 7260                                                    | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 75.38%  |
| Realtek Semiconductor | 7         | 10.77%  |
| Qualcomm Atheros      | 3         | 4.62%   |
| Broadcom              | 2         | 3.08%   |
| Ralink Technology     | 1         | 1.54%   |
| MediaTek              | 1         | 1.54%   |
| Broadcom Limited      | 1         | 1.54%   |
| ASUSTek Computer      | 1         | 1.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]   | 6         | 9.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                            | 6         | 9.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]            | 5         | 7.69%   |
| Intel Wi-Fi 6 AX200                                         | 4         | 6.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                           | 4         | 6.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 2         | 3.08%   |
| Intel Wireless 8265 / 8275                                  | 2         | 3.08%   |
| Intel Wireless 8260                                         | 2         | 3.08%   |
| Intel Wireless 7265                                         | 2         | 3.08%   |
| Intel Raptor Lake PCH CNVi WiFi                             | 2         | 3.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                             | 2         | 3.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                    | 2         | 3.08%   |
| Intel Cannon Lake PCH CNVi WiFi                             | 2         | 3.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                            | 2         | 3.08%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller | 1         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 1         | 1.54%   |
| Realtek RTL8723DE Wireless Network Adapter                  | 1         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter             | 1         | 1.54%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                  | 1         | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter         | 1         | 1.54%   |
| Realtek 802.11n WLAN Adapter                                | 1         | 1.54%   |
| Ralink MT7601U Wireless Adapter                             | 1         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 1         | 1.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                     | 1         | 1.54%   |
| Intel Wireless 7260                                         | 1         | 1.54%   |
| Intel Wireless 3160                                         | 1         | 1.54%   |
| Intel Wi-Fi 6 AX201 160MHz                                  | 1         | 1.54%   |
| Intel Wi-Fi 6 AX201                                         | 1         | 1.54%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]     | 1         | 1.54%   |
| Intel Tiger Lake PCH CNVi WiFi                              | 1         | 1.54%   |
| Intel Raptor Lake-S PCH CNVi WiFi                           | 1         | 1.54%   |
| Intel Centrino Wireless-N 2230                              | 1         | 1.54%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter | 1         | 1.54%   |
| Broadcom BCM4321 802.11b/g/n                                | 1         | 1.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter         | 1         | 1.54%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]         | 1         | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 38        | 48.72%  |
| Intel                 | 31        | 39.74%  |
| Broadcom              | 3         | 3.85%   |
| Qualcomm Atheros      | 2         | 2.56%   |
| Tehuti Networks       | 1         | 1.28%   |
| IBM                   | 1         | 1.28%   |
| DisplayLink           | 1         | 1.28%   |
| Aquantia              | 1         | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 18        | 21.43%  |
| Realtek RTL8125 2.5GbE Controller                                              | 8         | 9.52%   |
| Intel Ethernet Controller I225-V                                               | 8         | 9.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 8.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 5.95%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 3.57%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 2.38%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 2.38%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 2.38%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 2.38%   |
| Tehuti Networks TN9710P 10GBase-T/NBASE-T Ethernet Adapter                     | 1         | 1.19%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 1.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.19%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.19%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1         | 1.19%   |
| Intel Ethernet Controller I226-V                                               | 1         | 1.19%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 1.19%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1         | 1.19%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.19%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.19%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 1.19%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 1.19%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.19%   |
| Intel Ethernet Connection (3) I219-LM                                          | 1         | 1.19%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.19%   |
| Intel Ethernet Connection (23) I219-LM                                         | 1         | 1.19%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.19%   |
| Intel Ethernet Connection (16) I219-V                                          | 1         | 1.19%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.19%   |
| IBM RNDIS/CDC ETHER                                                            | 1         | 1.19%   |
| DisplayLink Dell D3100 Docking Station                                         | 1         | 1.19%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 1.19%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 1         | 1.19%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                               | 1         | 1.19%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1         | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 68        | 51.91%  |
| WiFi     | 63        | 48.09%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 52.44%  |
| Ethernet | 39        | 47.56%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 46        | 57.5%   |
| 1     | 23        | 28.75%  |
| 4     | 5         | 6.25%   |
| 3     | 5         | 6.25%   |
| 0     | 1         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 72.5%   |
| Yes  | 22        | 27.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 74.55%  |
| Realtek Semiconductor           | 3         | 5.45%   |
| Broadcom                        | 3         | 5.45%   |
| Qualcomm Atheros Communications | 2         | 3.64%   |
| Cambridge Silicon Radio         | 2         | 3.64%   |
| MediaTek                        | 1         | 1.82%   |
| Integrated System Solution      | 1         | 1.82%   |
| IMC Networks                    | 1         | 1.82%   |
| ASUSTek Computer                | 1         | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                 | 11        | 20%     |
| Intel AX210 Bluetooth                                 | 6         | 10.91%  |
| Intel Wireless-AC 3168 Bluetooth                      | 5         | 9.09%   |
| Intel Bluetooth Device                                | 5         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 5         | 9.09%   |
| Intel Bluetooth wireless interface                    | 4         | 7.27%   |
| Intel AX200 Bluetooth                                 | 4         | 7.27%   |
| Realtek Bluetooth Radio                               | 2         | 3.64%   |
| Qualcomm Atheros  Bluetooth Device                    | 2         | 3.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2         | 3.64%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 1.82%   |
| MediaTek Wireless_Device                              | 1         | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 1.82%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 1.82%   |
| IMC Networks Bluetooth Radio                          | 1         | 1.82%   |
| Broadcom HP Portable SoftSailing                      | 1         | 1.82%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                  | 1         | 1.82%   |
| Broadcom BCM2045B (BDC-2.1)                           | 1         | 1.82%   |
| ASUS ASUS USB-BT500                                   | 1         | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 62        | 50%     |
| Nvidia                                       | 23        | 18.55%  |
| AMD                                          | 17        | 13.71%  |
| Texas Instruments                            | 5         | 4.03%   |
| Realtek Semiconductor                        | 2         | 1.61%   |
| Creative Labs                                | 2         | 1.61%   |
| ASUSTek Computer                             | 2         | 1.61%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.81%   |
| SteelSeries ApS                              | 1         | 0.81%   |
| Sony                                         | 1         | 0.81%   |
| Micro Star International                     | 1         | 0.81%   |
| Logitech                                     | 1         | 0.81%   |
| LG Electronics                               | 1         | 0.81%   |
| Hewlett-Packard                              | 1         | 0.81%   |
| Corsair                                      | 1         | 0.81%   |
| Blue Microphones                             | 1         | 0.81%   |
| BEHRINGER International                      | 1         | 0.81%   |
| Astro Gaming                                 | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                           | Computers | Percent |
|-------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                                          | 7         | 4.96%   |
| Intel Sunrise Point-LP HD Audio                                                                 | 6         | 4.26%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                         | 6         | 4.26%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 6         | 4.26%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 4         | 2.84%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 4         | 2.84%   |
| Nvidia GA106 High Definition Audio Controller                                                   | 4         | 2.84%   |
| Intel Comet Lake PCH-LP cAVS                                                                    | 4         | 2.84%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 4         | 2.84%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 4         | 2.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 3         | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                                      | 3         | 2.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 3         | 2.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 3         | 2.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 3         | 2.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 3         | 2.13%   |
| Realtek Semiconductor USB Audio                                                                 | 2         | 1.42%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 2         | 1.42%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 2         | 1.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                         | 2         | 1.42%   |
| Intel Raptor Lake-P/U/H cAVS                                                                    | 2         | 1.42%   |
| Intel Jasper Lake HD Audio                                                                      | 2         | 1.42%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.42%   |
| Intel CM238 HD Audio Controller                                                                 | 2         | 1.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                                          | 2         | 1.42%   |
| Intel Broadwell-U Audio Controller                                                              | 2         | 1.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 2         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 2         | 1.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 2         | 1.42%   |
| Intel 200 Series PCH HD Audio                                                                   | 2         | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2         | 1.42%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 2         | 1.42%   |
| ASUSTek Computer USB Audio                                                                      | 2         | 1.42%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 2         | 1.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 2         | 1.42%   |
| AMD Navi 10 HDMI Audio                                                                          | 2         | 1.42%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                | 2         | 1.42%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                  | 1         | 0.71%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                               | 1         | 0.71%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                                                   | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 7         | 20.59%  |
| Samsung Electronics | 5         | 14.71%  |
| Kingston            | 4         | 11.76%  |
| Crucial             | 4         | 11.76%  |
| Micron Technology   | 3         | 8.82%   |
| G.Skill             | 3         | 8.82%   |
| Unknown             | 2         | 5.88%   |
| Corsair             | 2         | 5.88%   |
| Team                | 1         | 2.94%   |
| Smart               | 1         | 2.94%   |
| Hewlett-Packard     | 1         | 2.94%   |
| Elpida              | 1         | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 2         | 5.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1         | 2.7%    |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                    | 1         | 2.7%    |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s          | 1         | 2.7%    |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s        | 1         | 2.7%    |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s        | 1         | 2.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.7%    |
| SK hynix RAM HMCG94MEBRA123N 64GB DIMM DDR5 4800MT/s         | 1         | 2.7%    |
| SK hynix RAM HMCG94MEBRA121N 64GB DIMM DDR5 4800MT/s         | 1         | 2.7%    |
| SK hynix RAM HMCG94MEBRA109N 64GB DIMM DDR5 4800MT/s         | 1         | 2.7%    |
| SK hynix RAM HMAA8GL7CPR4N-VK 64GB DIMM DDR4 2666MT/s        | 1         | 2.7%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 2.7%    |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 2.7%    |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1         | 2.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.7%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 2.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 2.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.7%    |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR2 1867MT/s          | 1         | 2.7%    |
| Samsung RAM K3LK7K7@BM-BGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.7%    |
| Micron RAM Module 8GB Chip LPDDR4                            | 1         | 2.7%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s        | 1         | 2.7%    |
| Micron RAM 18ASF2G72AZ-2G6D1 16GB DIMM DDR4 2667MT/s         | 1         | 2.7%    |
| Kingston RAM X74R9W-MIE 8GB SODIMM DDR4 2933MT/s             | 1         | 2.7%    |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2667MT/s        | 1         | 2.7%    |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s          | 1         | 2.7%    |
| Kingston RAM 9905744-108.A00G 16GB SODIMM DDR4 3200MT/s      | 1         | 2.7%    |
| HP RAM 669237-071 2GB DIMM DDR3 1600MT/s                     | 1         | 2.7%    |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s         | 1         | 2.7%    |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s       | 1         | 2.7%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 1         | 2.7%    |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 1         | 2.7%    |
| Crucial RAM Module 8GB DIMM DDR3 1600MT/s                    | 1         | 2.7%    |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s         | 1         | 2.7%    |
| Crucial RAM CT4G4SFS824A.M8FE 4GB SODIMM DDR4 2400MT/s       | 1         | 2.7%    |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s   | 1         | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 18        | 62.07%  |
| DDR3   | 6         | 20.69%  |
| LPDDR4 | 2         | 6.9%    |
| DDR5   | 2         | 6.9%    |
| LPDDR5 | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 14        | 48.28%  |
| SODIMM       | 12        | 41.38%  |
| Row Of Chips | 2         | 6.9%    |
| Chip         | 1         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 13        | 40.63%  |
| 16384 | 10        | 31.25%  |
| 4096  | 4         | 12.5%   |
| 65536 | 2         | 6.25%   |
| 2048  | 2         | 6.25%   |
| 32768 | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3600    | 5         | 15.63%  |
| 2667    | 5         | 15.63%  |
| 2400    | 4         | 12.5%   |
| 1600    | 4         | 12.5%   |
| 3200    | 3         | 9.38%   |
| 6400    | 2         | 6.25%   |
| 2933    | 2         | 6.25%   |
| 2133    | 2         | 6.25%   |
| 4800    | 1         | 3.13%   |
| 2666    | 1         | 3.13%   |
| 1867    | 1         | 3.13%   |
| 1333    | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 3         | 60%     |
| Hewlett-Packard | 1         | 20%     |
| Canon           | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-4100 Series | 1         | 20%     |
| Seiko Epson WF-3520 Series | 1         | 20%     |
| Seiko Epson L3210 Series   | 1         | 20%     |
| HP DeskJet 3700 series     | 1         | 20%     |
| Canon PIXMA MG2500 Series  | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 17.31%  |
| Microdia                               | 7         | 13.46%  |
| IMC Networks                           | 5         | 9.62%   |
| Sunplus Innovation Technology          | 3         | 5.77%   |
| Realtek Semiconductor                  | 3         | 5.77%   |
| Bison Electronics                      | 3         | 5.77%   |
| Logitech                               | 2         | 3.85%   |
| Lite-On Technology                     | 2         | 3.85%   |
| Apple                                  | 2         | 3.85%   |
| vivo                                   | 1         | 1.92%   |
| Syntek                                 | 1         | 1.92%   |
| Suyin                                  | 1         | 1.92%   |
| Sonix Technology                       | 1         | 1.92%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.92%   |
| Samsung Electronics                    | 1         | 1.92%   |
| Remo Tech                              | 1         | 1.92%   |
| Quanta                                 | 1         | 1.92%   |
| Owon                                   | 1         | 1.92%   |
| Microsoft                              | 1         | 1.92%   |
| Luxvisions Innotech Limited            | 1         | 1.92%   |
| LG Electronics                         | 1         | 1.92%   |
| Generalplus Technology                 | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.92%   |
| Acer                                   | 1         | 1.92%   |
| 8SSC21D67422V1SR3AV5KW1                | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                             | 3         | 5.77%   |
| Sunplus Integrated_Webcam_HD                                          | 2         | 3.85%   |
| Microdia Integrated_Webcam_HD                                         | 2         | 3.85%   |
| IMC Networks Integrated Camera                                        | 2         | 3.85%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                    | 2         | 3.85%   |
| vivo V2036                                                            | 1         | 1.92%   |
| Syntek Integrated Camera                                              | 1         | 1.92%   |
| Suyin Integrated_Webcam_HD                                            | 1         | 1.92%   |
| Sunplus Integrated Camera                                             | 1         | 1.92%   |
| Sonix USB2.0 HD UVC WebCam                                            | 1         | 1.92%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                       | 1         | 1.92%   |
| Samsung Galaxy series, misc. (MTP mode)                               | 1         | 1.92%   |
| Remo Tech OBSBOT Tiny 4K                                              | 1         | 1.92%   |
| Realtek Integrated_Webcam_HD                                          | 1         | 1.92%   |
| Realtek Integrated Webcam_HD                                          | 1         | 1.92%   |
| Realtek Full HD webcam                                                | 1         | 1.92%   |
| Quanta HP TrueVision HD Camera                                        | 1         | 1.92%   |
| Owon USB CAMERA                                                       | 1         | 1.92%   |
| Microsoft LifeCam VX-2000                                             | 1         | 1.92%   |
| Microdia USB 2.0 Camera                                               | 1         | 1.92%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 1.92%   |
| Microdia Integrated_Webcam_FHD                                        | 1         | 1.92%   |
| Microdia Integrated Webcam                                            | 1         | 1.92%   |
| Microdia 1.3 MPixel Integrated Webcam                                 | 1         | 1.92%   |
| Luxvisions Innotech Limited Integrated Camera                         | 1         | 1.92%   |
| Logitech Webcam C250                                                  | 1         | 1.92%   |
| Logitech C922 Pro Stream Webcam                                       | 1         | 1.92%   |
| Lite-On Integrated Camera                                             | 1         | 1.92%   |
| Lite-On HP HD Camera                                                  | 1         | 1.92%   |
| LG LG UltraFine Display Camera                                        | 1         | 1.92%   |
| IMC Networks XHC Camera                                               | 1         | 1.92%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 1         | 1.92%   |
| IMC Networks USB Camera                                               | 1         | 1.92%   |
| Generalplus GENERAL WEBCAM                                            | 1         | 1.92%   |
| Chicony USB2.0 VGA UVC WebCam                                         | 1         | 1.92%   |
| Chicony ThinkPad T490 Webcam                                          | 1         | 1.92%   |
| Chicony LG Camera                                                     | 1         | 1.92%   |
| Chicony HP HD Webcam [Fixed]                                          | 1         | 1.92%   |
| Chicony HP HD Camera                                                  | 1         | 1.92%   |
| Chicony HD Webcam                                                     | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 44.44%  |
| Validity Sensors           | 2         | 22.22%  |
| Shenzhen Goodix Technology | 2         | 22.22%  |
| Samsung Electronics        | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 33.33%  |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 22.22%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 11.11%  |
| Validity Sensors VFS491                                   | 1         | 11.11%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 85.71%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 42.86%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 28.57%  |
| Broadcom 58200                                 | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 51        | 63.75%  |
| 1     | 23        | 28.75%  |
| 2     | 4         | 5%      |
| 4     | 1         | 1.25%   |
| 3     | 1         | 1.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 24.32%  |
| Net/wireless             | 5         | 13.51%  |
| Graphics card            | 5         | 13.51%  |
| Chipcard                 | 4         | 10.81%  |
| Unassigned class         | 3         | 8.11%   |
| Multimedia controller    | 3         | 8.11%   |
| Communication controller | 2         | 5.41%   |
| Storage/ide              | 1         | 2.7%    |
| Net/ethernet             | 1         | 2.7%    |
| Firewire controller      | 1         | 2.7%    |
| Card reader              | 1         | 2.7%    |
| Camera                   | 1         | 2.7%    |
| Bluetooth                | 1         | 2.7%    |

