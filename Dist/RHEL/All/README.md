RHEL - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for RHEL.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/RHEL/Desktop/README.md) and [notebooks](/Dist/RHEL/Notebook/README.md).

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

Total: 452

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | PRO Z690-A DDR4             | Desktop     | [55f164e414](https://linux-hardware.org/?probe=55f164e414) | Dec 20, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b758a439b8](https://linux-hardware.org/?probe=b758a439b8) | Dec 20, 2023 |
| Dell          | Latitude 5340               | Notebook    | [c9d3b3d7a7](https://linux-hardware.org/?probe=c9d3b3d7a7) | Dec 19, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [c492be4899](https://linux-hardware.org/?probe=c492be4899) | Dec 04, 2023 |
| Dell          | Precision 7530              | Notebook    | [e75b16ca5e](https://linux-hardware.org/?probe=e75b16ca5e) | Dec 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [5c4714ecce](https://linux-hardware.org/?probe=5c4714ecce) | Dec 01, 2023 |
| Lenovo        | ThinkPad L480 20LS0015UK    | Notebook    | [5f786955fc](https://linux-hardware.org/?probe=5f786955fc) | Nov 26, 2023 |
| Dell          | 02C2CP A08                  | Server      | [f7cd1a9252](https://linux-hardware.org/?probe=f7cd1a9252) | Nov 22, 2023 |
| Dell          | 0X8DXD A00                  | Desktop     | [bc58f50ac6](https://linux-hardware.org/?probe=bc58f50ac6) | Nov 22, 2023 |
| Lenovo        | IdeaPad 330S-14IKB U 81F... | Notebook    | [0b06f82d9d](https://linux-hardware.org/?probe=0b06f82d9d) | Nov 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [367bde5a11](https://linux-hardware.org/?probe=367bde5a11) | Nov 03, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [e356c02979](https://linux-hardware.org/?probe=e356c02979) | Oct 30, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [2ed4b6b711](https://linux-hardware.org/?probe=2ed4b6b711) | Oct 24, 2023 |
| Intel         | NUC12SNKi72 M78939-500      | Mini pc     | [1b04f5768f](https://linux-hardware.org/?probe=1b04f5768f) | Oct 24, 2023 |
| Intel         | NUC12SNKi72 M78939-500      | Mini pc     | [eb48924942](https://linux-hardware.org/?probe=eb48924942) | Oct 24, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [79f6aee2c7](https://linux-hardware.org/?probe=79f6aee2c7) | Oct 24, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [1c3bf8f6ef](https://linux-hardware.org/?probe=1c3bf8f6ef) | Oct 19, 2023 |
| System76      | Galago Pro                  | Notebook    | [fbdb665814](https://linux-hardware.org/?probe=fbdb665814) | Oct 03, 2023 |
| Dell          | 03X6X0 A01                  | Server      | [eb082ebcfc](https://linux-hardware.org/?probe=eb082ebcfc) | Oct 03, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| Intel         | NUC12WSBi7 M63355-302       | Mini pc     | [043bac31d2](https://linux-hardware.org/?probe=043bac31d2) | Sep 28, 2023 |
| Dell          | G16 7620                    | Notebook    | [cd30e51d53](https://linux-hardware.org/?probe=cd30e51d53) | Sep 27, 2023 |
| Dell          | Precision 7720              | Notebook    | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f2bb4ee9f0](https://linux-hardware.org/?probe=f2bb4ee9f0) | Sep 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ff1efba80e](https://linux-hardware.org/?probe=ff1efba80e) | Sep 13, 2023 |
| Acer          | Aspire C24-865              | All in one  | [de824a4f4e](https://linux-hardware.org/?probe=de824a4f4e) | Sep 03, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c0af84c629](https://linux-hardware.org/?probe=c0af84c629) | Sep 02, 2023 |
| Lenovo        | ThinkPad T490 20N3S77601    | Notebook    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c190907cc8](https://linux-hardware.org/?probe=c190907cc8) | Aug 29, 2023 |
| HP            | 8955                        | Mini pc     | [b80c4d0245](https://linux-hardware.org/?probe=b80c4d0245) | Aug 28, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5f2a27253a](https://linux-hardware.org/?probe=5f2a27253a) | Aug 21, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5e76f9bfc3](https://linux-hardware.org/?probe=5e76f9bfc3) | Aug 21, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [e5b049be3a](https://linux-hardware.org/?probe=e5b049be3a) | Aug 18, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f88687d2f0](https://linux-hardware.org/?probe=f88687d2f0) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f6892c6532](https://linux-hardware.org/?probe=f6892c6532) | Aug 15, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d5d888506b](https://linux-hardware.org/?probe=d5d888506b) | Aug 10, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [eb99d95702](https://linux-hardware.org/?probe=eb99d95702) | Aug 08, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [de07e937bb](https://linux-hardware.org/?probe=de07e937bb) | Aug 04, 2023 |
| HP            | 0AECh D                     | Desktop     | [b9ea790e39](https://linux-hardware.org/?probe=b9ea790e39) | Jul 24, 2023 |
| HP            | 0AECh D                     | Desktop     | [078f0cd045](https://linux-hardware.org/?probe=078f0cd045) | Jul 24, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [0d8b3d7c32](https://linux-hardware.org/?probe=0d8b3d7c32) | Jun 20, 2023 |
| IBM           | FAB2 Controller Producti... | Server      | [daa3df0f31](https://linux-hardware.org/?probe=daa3df0f31) | Jun 19, 2023 |
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
| ASUSTek       | X550ZA                      | Notebook    | [cc243873e2](https://linux-hardware.org/?probe=cc243873e2) | Mar 26, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [2e55d2163a](https://linux-hardware.org/?probe=2e55d2163a) | Mar 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| Lenovo        | [3633AC1] STC               | Server      | [aef7266e33](https://linux-hardware.org/?probe=aef7266e33) | Mar 20, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [12d8200114](https://linux-hardware.org/?probe=12d8200114) | Mar 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [52e2d79bad](https://linux-hardware.org/?probe=52e2d79bad) | Mar 01, 2023 |
| Getac         | B360                        | Notebook    | [c4bd09adf1](https://linux-hardware.org/?probe=c4bd09adf1) | Mar 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | Notebook    | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [affa3bb9f1](https://linux-hardware.org/?probe=affa3bb9f1) | Feb 19, 2023 |
| Dell          | Precision 7560              | Notebook    | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [2a4e6ab2d4](https://linux-hardware.org/?probe=2a4e6ab2d4) | Feb 07, 2023 |
| Getac         | S410G4                      | Notebook    | [81b80297ab](https://linux-hardware.org/?probe=81b80297ab) | Feb 06, 2023 |
| Getac         | S410G4                      | Notebook    | [1d8e6ad383](https://linux-hardware.org/?probe=1d8e6ad383) | Feb 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [701a355d37](https://linux-hardware.org/?probe=701a355d37) | Feb 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [98f5768c61](https://linux-hardware.org/?probe=98f5768c61) | Jan 22, 2023 |
| Dell          | Latitude 9420               | Notebook    | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [34169c74c5](https://linux-hardware.org/?probe=34169c74c5) | Dec 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [199df541f2](https://linux-hardware.org/?probe=199df541f2) | Dec 21, 2022 |
| MSI           | GE72VR 7RF                  | Notebook    | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9787630f1c](https://linux-hardware.org/?probe=9787630f1c) | Dec 12, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f1ac9526c5](https://linux-hardware.org/?probe=f1ac9526c5) | Dec 08, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [ae85dba67e](https://linux-hardware.org/?probe=ae85dba67e) | Nov 28, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [64fb254a64](https://linux-hardware.org/?probe=64fb254a64) | Nov 17, 2022 |
| Dell          | Latitude E7450              | Notebook    | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [de9e18e6ca](https://linux-hardware.org/?probe=de9e18e6ca) | Nov 14, 2022 |
| Lenovo        | Unknown                     | Convertible | [b4fb099c2f](https://linux-hardware.org/?probe=b4fb099c2f) | Nov 11, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| Dell          | 0RN4PJ A02                  | Server      | [84012f61ff](https://linux-hardware.org/?probe=84012f61ff) | Nov 03, 2022 |
| HP            | 8591                        | Desktop     | [98bde1bd5a](https://linux-hardware.org/?probe=98bde1bd5a) | Nov 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| AZW           | SER V01                     | Mini pc     | [7bb271252d](https://linux-hardware.org/?probe=7bb271252d) | Oct 17, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP            | 340S G7                     | Notebook    | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [8656acec04](https://linux-hardware.org/?probe=8656acec04) | Sep 14, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [23649c49e3](https://linux-hardware.org/?probe=23649c49e3) | Sep 14, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [22131a6ec5](https://linux-hardware.org/?probe=22131a6ec5) | Sep 03, 2022 |
| Acer          | Aspire XC-330               | Desktop     | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Dell          | Precision 7510              | Notebook    | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [3df0bebc37](https://linux-hardware.org/?probe=3df0bebc37) | Aug 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [4776ecdc2a](https://linux-hardware.org/?probe=4776ecdc2a) | Jul 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [71c31086e6](https://linux-hardware.org/?probe=71c31086e6) | Jul 11, 2022 |
| Intel         | H81                         | Desktop     | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [714c212f51](https://linux-hardware.org/?probe=714c212f51) | Jul 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [ab729dc8a5](https://linux-hardware.org/?probe=ab729dc8a5) | Jul 04, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [1cb6aead26](https://linux-hardware.org/?probe=1cb6aead26) | Jul 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | Notebook    | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | ThinkPad T480 20L60034MX    | Notebook    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Unknown       | A06                         | Server      | [aca491bb91](https://linux-hardware.org/?probe=aca491bb91) | Jun 21, 2022 |
| Unknown       | A06                         | Server      | [3bf8edf992](https://linux-hardware.org/?probe=3bf8edf992) | Jun 18, 2022 |
| Supermicro    | X10DRi                      | Server      | [0cf218f7bf](https://linux-hardware.org/?probe=0cf218f7bf) | Jun 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [d77ce7a3f7](https://linux-hardware.org/?probe=d77ce7a3f7) | Jun 13, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [372a1d69d7](https://linux-hardware.org/?probe=372a1d69d7) | May 27, 2022 |
| Dell          | 02K9CR A03                  | Desktop     | [5656d7a0d5](https://linux-hardware.org/?probe=5656d7a0d5) | May 27, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [74525891a0](https://linux-hardware.org/?probe=74525891a0) | May 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f08ef13508](https://linux-hardware.org/?probe=f08ef13508) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Notebook    | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S29D02    | Notebook    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell          | Precision 5550              | Notebook    | [949f4a7658](https://linux-hardware.org/?probe=949f4a7658) | Apr 19, 2022 |
| Lenovo        | 3132 SDK0K17763 WIN 1801... | Desktop     | [a6e43346ba](https://linux-hardware.org/?probe=a6e43346ba) | Apr 16, 2022 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [ddfbf2df5e](https://linux-hardware.org/?probe=ddfbf2df5e) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [5a8ee938ce](https://linux-hardware.org/?probe=5a8ee938ce) | Apr 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7763003308](https://linux-hardware.org/?probe=7763003308) | Mar 31, 2022 |
| Dell          | Precision 7560              | Notebook    | [2abd72978c](https://linux-hardware.org/?probe=2abd72978c) | Mar 29, 2022 |
| Intel         | NUC11DBBi7 M17027-302       | Mini pc     | [e1e4cbbe30](https://linux-hardware.org/?probe=e1e4cbbe30) | Mar 17, 2022 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [0cf67f0201](https://linux-hardware.org/?probe=0cf67f0201) | Mar 06, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [e7843ce1cf](https://linux-hardware.org/?probe=e7843ce1cf) | Mar 05, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [7fd2e4885c](https://linux-hardware.org/?probe=7fd2e4885c) | Mar 05, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [14ea45c4d7](https://linux-hardware.org/?probe=14ea45c4d7) | Mar 03, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [eed6e0f012](https://linux-hardware.org/?probe=eed6e0f012) | Mar 01, 2022 |
| Lenovo        | Z40-70 20366                | Notebook    | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Gigabyte      | B150-HD3-CF                 | Desktop     | [cab21caab7](https://linux-hardware.org/?probe=cab21caab7) | Feb 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [36c52eaf3d](https://linux-hardware.org/?probe=36c52eaf3d) | Feb 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Notebook    | [7b31f4ca0b](https://linux-hardware.org/?probe=7b31f4ca0b) | Feb 05, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b3ef38d0ef](https://linux-hardware.org/?probe=b3ef38d0ef) | Jan 31, 2022 |
| Dell          | Latitude E5570              | Notebook    | [87ec93dcdc](https://linux-hardware.org/?probe=87ec93dcdc) | Jan 31, 2022 |
| Lenovo        | ThinkPad T490 20N3S5DV0S    | Notebook    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [07de603a4a](https://linux-hardware.org/?probe=07de603a4a) | Jan 31, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [a60504e123](https://linux-hardware.org/?probe=a60504e123) | Jan 29, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [335a0c0490](https://linux-hardware.org/?probe=335a0c0490) | Jan 28, 2022 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [5808f89618](https://linux-hardware.org/?probe=5808f89618) | Jan 07, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [e3b3ac9f8b](https://linux-hardware.org/?probe=e3b3ac9f8b) | Jan 01, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [012f2de3d5](https://linux-hardware.org/?probe=012f2de3d5) | Dec 28, 2021 |
| HP            | ProLiant DL380e Gen8        | Server      | [a28b637049](https://linux-hardware.org/?probe=a28b637049) | Dec 28, 2021 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [2e716df6c6](https://linux-hardware.org/?probe=2e716df6c6) | Dec 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Dell          | Precision 3551              | Notebook    | [cbddfb522a](https://linux-hardware.org/?probe=cbddfb522a) | Dec 21, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [ea1413bf9e](https://linux-hardware.org/?probe=ea1413bf9e) | Nov 19, 2021 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | Notebook    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [7052b7628f](https://linux-hardware.org/?probe=7052b7628f) | Nov 18, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0178a25382](https://linux-hardware.org/?probe=0178a25382) | Nov 18, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [f766090339](https://linux-hardware.org/?probe=f766090339) | Nov 16, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ece232f046](https://linux-hardware.org/?probe=ece232f046) | Nov 11, 2021 |
| Lenovo        | ThinkPad P50 20ENS1L000     | Notebook    | [318b5aea2b](https://linux-hardware.org/?probe=318b5aea2b) | Nov 08, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [d3d69e7587](https://linux-hardware.org/?probe=d3d69e7587) | Oct 24, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [59dfcd3b23](https://linux-hardware.org/?probe=59dfcd3b23) | Oct 22, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [07a5b3c465](https://linux-hardware.org/?probe=07a5b3c465) | Oct 16, 2021 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [49d20bd238](https://linux-hardware.org/?probe=49d20bd238) | Oct 12, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [66cd9bb2c9](https://linux-hardware.org/?probe=66cd9bb2c9) | Oct 09, 2021 |
| Lenovo        | ThinkPad P50 20ENS1L000     | Notebook    | [f8443770b9](https://linux-hardware.org/?probe=f8443770b9) | Oct 08, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [63b48dfa23](https://linux-hardware.org/?probe=63b48dfa23) | Oct 07, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | Notebook    | [042f9bec29](https://linux-hardware.org/?probe=042f9bec29) | Oct 06, 2021 |
| HP            | 212B                        | Desktop     | [322371cc6a](https://linux-hardware.org/?probe=322371cc6a) | Oct 04, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [2792a3ef1c](https://linux-hardware.org/?probe=2792a3ef1c) | Oct 03, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [539316ac91](https://linux-hardware.org/?probe=539316ac91) | Sep 30, 2021 |
| Lenovo        | ThinkPad T470 20HES57W00    | Notebook    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [95ae5d0e04](https://linux-hardware.org/?probe=95ae5d0e04) | Sep 29, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [a667466f62](https://linux-hardware.org/?probe=a667466f62) | Sep 17, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [502a6b96a3](https://linux-hardware.org/?probe=502a6b96a3) | Sep 13, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [fc498b8cb0](https://linux-hardware.org/?probe=fc498b8cb0) | Sep 10, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [35fa4b96f4](https://linux-hardware.org/?probe=35fa4b96f4) | Sep 09, 2021 |
| Lenovo        | HR630X                      | Server      | [0627db12df](https://linux-hardware.org/?probe=0627db12df) | Sep 08, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [daadb8ccc0](https://linux-hardware.org/?probe=daadb8ccc0) | Sep 06, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [952dd9f6f5](https://linux-hardware.org/?probe=952dd9f6f5) | Sep 01, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [7bf4b860a8](https://linux-hardware.org/?probe=7bf4b860a8) | Aug 26, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [f7bcc3d753](https://linux-hardware.org/?probe=f7bcc3d753) | Aug 25, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [d62c66d9bd](https://linux-hardware.org/?probe=d62c66d9bd) | Aug 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [1bb9bd9d46](https://linux-hardware.org/?probe=1bb9bd9d46) | Jul 27, 2021 |
| Supermicro    | X10DRi                      | Server      | [6be87ab445](https://linux-hardware.org/?probe=6be87ab445) | Jul 26, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [54f44d70c5](https://linux-hardware.org/?probe=54f44d70c5) | Jul 24, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [9f9cc51cda](https://linux-hardware.org/?probe=9f9cc51cda) | Jul 20, 2021 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [a540fa2f59](https://linux-hardware.org/?probe=a540fa2f59) | Jul 19, 2021 |
| Dell          | Latitude E5510              | Notebook    | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [7e7fbaff11](https://linux-hardware.org/?probe=7e7fbaff11) | Jul 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c4091b8c8c](https://linux-hardware.org/?probe=c4091b8c8c) | Jul 09, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [a03b6b86cc](https://linux-hardware.org/?probe=a03b6b86cc) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [500c95d16b](https://linux-hardware.org/?probe=500c95d16b) | Jul 03, 2021 |
| Dell          | 0MWYPT A02                  | Desktop     | [ab6e7450c3](https://linux-hardware.org/?probe=ab6e7450c3) | Jul 01, 2021 |
| Dell          | Latitude E6430              | Notebook    | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell          | Latitude E6430              | Notebook    | [ed72da5de8](https://linux-hardware.org/?probe=ed72da5de8) | Jun 25, 2021 |
| Dell          | Latitude E6430              | Notebook    | [899e8720e1](https://linux-hardware.org/?probe=899e8720e1) | Jun 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [eccdf8e8c1](https://linux-hardware.org/?probe=eccdf8e8c1) | Jun 20, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a703424a8c](https://linux-hardware.org/?probe=a703424a8c) | Jun 13, 2021 |
| Intel         | DX79SR AAG57199-200         | Desktop     | [380f10f479](https://linux-hardware.org/?probe=380f10f479) | Jun 10, 2021 |
| Dell          | Precision 3541              | Notebook    | [984db774ed](https://linux-hardware.org/?probe=984db774ed) | Jun 08, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| ZTSYSTEMS     | A9DRPF TBD                  | Server      | [1b5977b024](https://linux-hardware.org/?probe=1b5977b024) | Jun 03, 2021 |
| HP            | 1906                        | Desktop     | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| Dell          | 074H08 A00                  | Server      | [b7ac531bf5](https://linux-hardware.org/?probe=b7ac531bf5) | Jun 02, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| ZTSYSTEMS     | A9DRPF TBD                  | Server      | [57e5191283](https://linux-hardware.org/?probe=57e5191283) | Jun 01, 2021 |
| Dell          | 0CNCJW A08                  | Server      | [f90168c69d](https://linux-hardware.org/?probe=f90168c69d) | Jun 01, 2021 |
| Dell          | Latitude E6530              | Notebook    | [2e9b8200a9](https://linux-hardware.org/?probe=2e9b8200a9) | May 29, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [2eebd180f8](https://linux-hardware.org/?probe=2eebd180f8) | May 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c51ae8a5ff](https://linux-hardware.org/?probe=c51ae8a5ff) | May 28, 2021 |
| MiTAC         | HS-9215 R0A                 | Server      | [2f38c3fd0e](https://linux-hardware.org/?probe=2f38c3fd0e) | May 27, 2021 |
| HP            | ProLiant DL180 G6           | Server      | [28b04c3004](https://linux-hardware.org/?probe=28b04c3004) | May 26, 2021 |
| Dell          | 0971VF A01                  | Server      | [9d511d1a0b](https://linux-hardware.org/?probe=9d511d1a0b) | May 26, 2021 |
| Lenovo        | HR630X                      | Server      | [fd087082c0](https://linux-hardware.org/?probe=fd087082c0) | May 26, 2021 |
| HP            | 2129                        | Desktop     | [3991895525](https://linux-hardware.org/?probe=3991895525) | May 23, 2021 |
| MSI           | Z77A-G45                    | Desktop     | [9b11ff6d26](https://linux-hardware.org/?probe=9b11ff6d26) | May 22, 2021 |
| MSI           | Z77A-G45                    | Desktop     | [bd980d04be](https://linux-hardware.org/?probe=bd980d04be) | May 22, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [4a38b848dd](https://linux-hardware.org/?probe=4a38b848dd) | May 19, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [65666a7bec](https://linux-hardware.org/?probe=65666a7bec) | May 17, 2021 |
| HP            | 8054                        | Desktop     | [cf6b804c19](https://linux-hardware.org/?probe=cf6b804c19) | May 13, 2021 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [9cacd1608e](https://linux-hardware.org/?probe=9cacd1608e) | May 08, 2021 |
| Lenovo        | 7D2XCTO1WW                  | Server      | [2175466ea1](https://linux-hardware.org/?probe=2175466ea1) | Apr 25, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [23f12250e5](https://linux-hardware.org/?probe=23f12250e5) | Apr 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | Notebook    | [bf95cd0ce7](https://linux-hardware.org/?probe=bf95cd0ce7) | Apr 20, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [349f951788](https://linux-hardware.org/?probe=349f951788) | Apr 18, 2021 |
| Dell          | Inspiron 3559               | Notebook    | [854655e305](https://linux-hardware.org/?probe=854655e305) | Apr 14, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [f98af88440](https://linux-hardware.org/?probe=f98af88440) | Apr 06, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [4c3dd6a28b](https://linux-hardware.org/?probe=4c3dd6a28b) | Mar 25, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [344f718da0](https://linux-hardware.org/?probe=344f718da0) | Mar 25, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [feedaccb5b](https://linux-hardware.org/?probe=feedaccb5b) | Mar 24, 2021 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [3dce7dc37d](https://linux-hardware.org/?probe=3dce7dc37d) | Mar 20, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [ee5d8875e3](https://linux-hardware.org/?probe=ee5d8875e3) | Mar 11, 2021 |
| Lenovo        | ThinkPad T460 20FMS1VA09    | Notebook    | [5bc6b53ecf](https://linux-hardware.org/?probe=5bc6b53ecf) | Mar 03, 2021 |
| Lenovo        | ThinkPad T460 20FMS1VA09    | Notebook    | [55314e09ff](https://linux-hardware.org/?probe=55314e09ff) | Mar 03, 2021 |
| Lenovo        | ThinkPad W530 2441B32       | Notebook    | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [c6fd48fe3f](https://linux-hardware.org/?probe=c6fd48fe3f) | Feb 28, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [22c97ac8b2](https://linux-hardware.org/?probe=22c97ac8b2) | Feb 27, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [3f081f03fe](https://linux-hardware.org/?probe=3f081f03fe) | Feb 22, 2021 |
| Dell          | Precision 5510              | Notebook    | [2d4aed7f6c](https://linux-hardware.org/?probe=2d4aed7f6c) | Feb 22, 2021 |
| Sony          | VPCEB4L1R                   | Notebook    | [1744d5db17](https://linux-hardware.org/?probe=1744d5db17) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [071f1be343](https://linux-hardware.org/?probe=071f1be343) | Feb 09, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [29d0e20ba4](https://linux-hardware.org/?probe=29d0e20ba4) | Feb 08, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [832d7f19ae](https://linux-hardware.org/?probe=832d7f19ae) | Feb 02, 2021 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | Notebook    | [bdff7fe555](https://linux-hardware.org/?probe=bdff7fe555) | Jan 28, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [98ea3e97e6](https://linux-hardware.org/?probe=98ea3e97e6) | Jan 25, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [2da05b98bf](https://linux-hardware.org/?probe=2da05b98bf) | Jan 25, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [3e0d4ac7c7](https://linux-hardware.org/?probe=3e0d4ac7c7) | Jan 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1a1bbc078f](https://linux-hardware.org/?probe=1a1bbc078f) | Jan 18, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d0ac809f8a](https://linux-hardware.org/?probe=d0ac809f8a) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [038ccd7256](https://linux-hardware.org/?probe=038ccd7256) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [f0441f0a07](https://linux-hardware.org/?probe=f0441f0a07) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [3c396f0b59](https://linux-hardware.org/?probe=3c396f0b59) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [ab4ea06f29](https://linux-hardware.org/?probe=ab4ea06f29) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [e10979867d](https://linux-hardware.org/?probe=e10979867d) | Jan 13, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [d606944d2b](https://linux-hardware.org/?probe=d606944d2b) | Jan 10, 2021 |
| ASRock        | H270 Pro4                   | Desktop     | [3a3b83a6ed](https://linux-hardware.org/?probe=3a3b83a6ed) | Jan 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [e24d02bc67](https://linux-hardware.org/?probe=e24d02bc67) | Jan 05, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [e1e788633e](https://linux-hardware.org/?probe=e1e788633e) | Dec 22, 2020 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [f95e7c46f7](https://linux-hardware.org/?probe=f95e7c46f7) | Dec 14, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [d99f937c68](https://linux-hardware.org/?probe=d99f937c68) | Dec 12, 2020 |
| Dell          | Latitude 5290               | Notebook    | [f69f594914](https://linux-hardware.org/?probe=f69f594914) | Dec 09, 2020 |
| Dell          | Latitude 5290               | Notebook    | [538342789e](https://linux-hardware.org/?probe=538342789e) | Dec 09, 2020 |
| HP            | 1905                        | Desktop     | [6690d08a07](https://linux-hardware.org/?probe=6690d08a07) | Dec 04, 2020 |
| HP            | Pavilion 14                 | Notebook    | [bed5ca82b9](https://linux-hardware.org/?probe=bed5ca82b9) | Dec 03, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | Notebook    | [a70d23cd77](https://linux-hardware.org/?probe=a70d23cd77) | Dec 02, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | Notebook    | [b446c7d5a5](https://linux-hardware.org/?probe=b446c7d5a5) | Dec 02, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | Notebook    | [81c97fb756](https://linux-hardware.org/?probe=81c97fb756) | Dec 02, 2020 |
| Lenovo        | ThinkPad T460 20BUS0QT0A    | Notebook    | [c0487ec734](https://linux-hardware.org/?probe=c0487ec734) | Dec 02, 2020 |
| HP            | ZBook 14u G6                | Notebook    | [84782d875f](https://linux-hardware.org/?probe=84782d875f) | Nov 27, 2020 |
| Dell          | Precision 7510              | Notebook    | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| Dell          | 082WXT A01                  | Desktop     | [8d9240a29c](https://linux-hardware.org/?probe=8d9240a29c) | Nov 19, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [ded8f80f0a](https://linux-hardware.org/?probe=ded8f80f0a) | Nov 18, 2020 |
| Dell          | 082WXT A01                  | Desktop     | [0a2176308f](https://linux-hardware.org/?probe=0a2176308f) | Nov 17, 2020 |
| HP            | 81B4                        | Desktop     | [12ac27dcb5](https://linux-hardware.org/?probe=12ac27dcb5) | Nov 14, 2020 |
| HP            | 81B4                        | Desktop     | [faf7b737fe](https://linux-hardware.org/?probe=faf7b737fe) | Nov 14, 2020 |
| Dell          | Latitude E6420              | Notebook    | [363320d61e](https://linux-hardware.org/?probe=363320d61e) | Nov 11, 2020 |
| Dell          | Latitude E6420              | Notebook    | [8a37aaac86](https://linux-hardware.org/?probe=8a37aaac86) | Nov 11, 2020 |
| MSI           | H310M PRO-VD                | Desktop     | [18c316813f](https://linux-hardware.org/?probe=18c316813f) | Nov 11, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Dell          | Precision 7510              | Notebook    | [432ebce0a4](https://linux-hardware.org/?probe=432ebce0a4) | Nov 03, 2020 |
| HP            | Pavilion 14                 | Notebook    | [d8220245e5](https://linux-hardware.org/?probe=d8220245e5) | Nov 01, 2020 |
| Dell          | Precision 7510              | Notebook    | [a564df5de7](https://linux-hardware.org/?probe=a564df5de7) | Nov 01, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [2dc26a5fbe](https://linux-hardware.org/?probe=2dc26a5fbe) | Oct 29, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [cf0c44ffb8](https://linux-hardware.org/?probe=cf0c44ffb8) | Oct 29, 2020 |
| Lenovo        | ThinkPad T520 42404CG       | Notebook    | [1ca04091de](https://linux-hardware.org/?probe=1ca04091de) | Oct 24, 2020 |
| Lenovo        | ThinkPad T520 42404CG       | Notebook    | [2e3d64e7c5](https://linux-hardware.org/?probe=2e3d64e7c5) | Oct 24, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [f2907d324d](https://linux-hardware.org/?probe=f2907d324d) | Oct 21, 2020 |
| Dell          | Latitude 5300               | Notebook    | [4169f50442](https://linux-hardware.org/?probe=4169f50442) | Oct 18, 2020 |
| Dell          | Latitude 5300               | Notebook    | [4bd822b6e3](https://linux-hardware.org/?probe=4bd822b6e3) | Oct 15, 2020 |
| HP            | 1905                        | Desktop     | [0e53545ff8](https://linux-hardware.org/?probe=0e53545ff8) | Oct 14, 2020 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [7bf945cd18](https://linux-hardware.org/?probe=7bf945cd18) | Oct 13, 2020 |
| HP            | Pavilion 14                 | Notebook    | [b29b04ed35](https://linux-hardware.org/?probe=b29b04ed35) | Oct 08, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [2bc1a5b44a](https://linux-hardware.org/?probe=2bc1a5b44a) | Oct 01, 2020 |
| HP            | 1905                        | Desktop     | [48fd57f60f](https://linux-hardware.org/?probe=48fd57f60f) | Sep 24, 2020 |
| HP            | 1905                        | Desktop     | [0e2d6062d9](https://linux-hardware.org/?probe=0e2d6062d9) | Sep 24, 2020 |
| HP            | 843F                        | Desktop     | [6f9898a049](https://linux-hardware.org/?probe=6f9898a049) | Sep 24, 2020 |
| Lenovo        | ThinkPad P50 20EN0005UK     | Notebook    | [94c1b32081](https://linux-hardware.org/?probe=94c1b32081) | Sep 21, 2020 |
| HP            | 843F                        | Desktop     | [91498f153e](https://linux-hardware.org/?probe=91498f153e) | Sep 18, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | Notebook    | [e3dab03999](https://linux-hardware.org/?probe=e3dab03999) | Sep 01, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [8b995a24c1](https://linux-hardware.org/?probe=8b995a24c1) | Aug 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [97293b7aa0](https://linux-hardware.org/?probe=97293b7aa0) | Aug 04, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | Notebook    | [93b236ab24](https://linux-hardware.org/?probe=93b236ab24) | Aug 01, 2020 |
| ASUSTek       | GL502VMK                    | Notebook    | [7556ef6b87](https://linux-hardware.org/?probe=7556ef6b87) | Jul 22, 2020 |
| HP            | 843F                        | Desktop     | [e0bdf38c8a](https://linux-hardware.org/?probe=e0bdf38c8a) | Jul 16, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU27    | Notebook    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Dell          | Latitude 5300               | Notebook    | [65284e0295](https://linux-hardware.org/?probe=65284e0295) | Jul 04, 2020 |
| Timi          | TM1707                      | Notebook    | [84538e3769](https://linux-hardware.org/?probe=84538e3769) | Jun 30, 2020 |
| Timi          | TM1707                      | Notebook    | [1267830169](https://linux-hardware.org/?probe=1267830169) | Jun 30, 2020 |
| ASUSTek       | GL502VMK                    | Notebook    | [45e4ef6c32](https://linux-hardware.org/?probe=45e4ef6c32) | Jun 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [ce5bce7893](https://linux-hardware.org/?probe=ce5bce7893) | Jun 19, 2020 |
| Dell          | Latitude 5300               | Notebook    | [8ebae81f7c](https://linux-hardware.org/?probe=8ebae81f7c) | Jun 18, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [b9a88cd7cf](https://linux-hardware.org/?probe=b9a88cd7cf) | Jun 13, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [b74e2f66bd](https://linux-hardware.org/?probe=b74e2f66bd) | May 29, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [de063b9994](https://linux-hardware.org/?probe=de063b9994) | May 28, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [9b51817b92](https://linux-hardware.org/?probe=9b51817b92) | May 26, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b97f2eb31f](https://linux-hardware.org/?probe=b97f2eb31f) | May 20, 2020 |
| HP            | 158A                        | Desktop     | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [220c6fdf1c](https://linux-hardware.org/?probe=220c6fdf1c) | May 13, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6237c4cae4](https://linux-hardware.org/?probe=6237c4cae4) | May 10, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [0108b32128](https://linux-hardware.org/?probe=0108b32128) | May 07, 2020 |
| Dell          | G3 3779                     | Notebook    | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Dell          | Precision 5540              | Notebook    | [3c0f6bcf28](https://linux-hardware.org/?probe=3c0f6bcf28) | Apr 29, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [9657b92263](https://linux-hardware.org/?probe=9657b92263) | Apr 14, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0B50... | Notebook    | [ea2a99e61e](https://linux-hardware.org/?probe=ea2a99e61e) | Apr 12, 2020 |
| Gigabyte      | B75-D3V                     | Desktop     | [73b3145cb4](https://linux-hardware.org/?probe=73b3145cb4) | Apr 10, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [8dad315eb5](https://linux-hardware.org/?probe=8dad315eb5) | Apr 07, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [848a63637f](https://linux-hardware.org/?probe=848a63637f) | Apr 01, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [d955389819](https://linux-hardware.org/?probe=d955389819) | Mar 27, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC00    | Notebook    | [c86bb46fad](https://linux-hardware.org/?probe=c86bb46fad) | Mar 26, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC00    | Notebook    | [79d1c623b5](https://linux-hardware.org/?probe=79d1c623b5) | Mar 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [07d54a6a50](https://linux-hardware.org/?probe=07d54a6a50) | Mar 24, 2020 |
| Alienware     | 0VDT73 A00                  | Desktop     | [00cc8f89dc](https://linux-hardware.org/?probe=00cc8f89dc) | Mar 17, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0B50... | Notebook    | [e2eabf79b0](https://linux-hardware.org/?probe=e2eabf79b0) | Mar 03, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [a018f0a4d4](https://linux-hardware.org/?probe=a018f0a4d4) | Feb 27, 2020 |
| Sony          | VPCEB23FM                   | Notebook    | [908bc46e69](https://linux-hardware.org/?probe=908bc46e69) | Feb 27, 2020 |
| Sony          | VPCEB23FM                   | Notebook    | [654cbddfc9](https://linux-hardware.org/?probe=654cbddfc9) | Feb 26, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [e2a3815dd2](https://linux-hardware.org/?probe=e2a3815dd2) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [da0c7d43d0](https://linux-hardware.org/?probe=da0c7d43d0) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [07bde7dae0](https://linux-hardware.org/?probe=07bde7dae0) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [6e7911571a](https://linux-hardware.org/?probe=6e7911571a) | Feb 21, 2020 |
| Dell          | 08D89F A02                  | Server      | [502ac45263](https://linux-hardware.org/?probe=502ac45263) | Feb 21, 2020 |
| Dell          | 08D89F A02                  | Server      | [412539e106](https://linux-hardware.org/?probe=412539e106) | Feb 21, 2020 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | Desktop     | [ce36caf100](https://linux-hardware.org/?probe=ce36caf100) | Feb 18, 2020 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | Desktop     | [13d8453be0](https://linux-hardware.org/?probe=13d8453be0) | Feb 18, 2020 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [48c65f99c6](https://linux-hardware.org/?probe=48c65f99c6) | Feb 17, 2020 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [4e770d86e3](https://linux-hardware.org/?probe=4e770d86e3) | Feb 15, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [0a9570ceaf](https://linux-hardware.org/?probe=0a9570ceaf) | Jan 29, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [2b0d41a249](https://linux-hardware.org/?probe=2b0d41a249) | Jan 29, 2020 |
| Dell          | 0XR1GT A00                  | Desktop     | [319aa86f81](https://linux-hardware.org/?probe=319aa86f81) | Jan 25, 2020 |
| Dell          | 0XR1GT A00                  | Desktop     | [189883a0aa](https://linux-hardware.org/?probe=189883a0aa) | Jan 25, 2020 |
| Lenovo        | ThinkPad T490s 20NX002HU... | Notebook    | [622df7e336](https://linux-hardware.org/?probe=622df7e336) | Jan 24, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [bfacbe4d23](https://linux-hardware.org/?probe=bfacbe4d23) | Jan 18, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [ff60ab76a9](https://linux-hardware.org/?probe=ff60ab76a9) | Jan 15, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [6bffc36e6a](https://linux-hardware.org/?probe=6bffc36e6a) | Jan 06, 2020 |
| ASRock        | H91M-PLUS                   | Desktop     | [c90d6b4c4d](https://linux-hardware.org/?probe=c90d6b4c4d) | Dec 30, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [fff26d5712](https://linux-hardware.org/?probe=fff26d5712) | Dec 21, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [21aeb33209](https://linux-hardware.org/?probe=21aeb33209) | Dec 18, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [199fad181e](https://linux-hardware.org/?probe=199fad181e) | Nov 29, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7b90aa9c1b](https://linux-hardware.org/?probe=7b90aa9c1b) | Nov 21, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1858b15d73](https://linux-hardware.org/?probe=1858b15d73) | Nov 20, 2019 |
| Dell          | 0G919G A00                  | Desktop     | [bdf53b02dc](https://linux-hardware.org/?probe=bdf53b02dc) | Nov 18, 2019 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6a11247e37](https://linux-hardware.org/?probe=6a11247e37) | Nov 11, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| HP            | 250 G4 Notebook PC          | Notebook    | [8dbaf2e95e](https://linux-hardware.org/?probe=8dbaf2e95e) | Nov 07, 2019 |
| HP            | 250 G4 Notebook PC          | Notebook    | [0347166558](https://linux-hardware.org/?probe=0347166558) | Nov 07, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f5adffebe4](https://linux-hardware.org/?probe=f5adffebe4) | Oct 30, 2019 |
| Supermicro    | X7DWN+                      | Desktop     | [505e506351](https://linux-hardware.org/?probe=505e506351) | Oct 26, 2019 |
| Supermicro    | X7DWN+                      | Desktop     | [5ad617d6ad](https://linux-hardware.org/?probe=5ad617d6ad) | Oct 25, 2019 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [2204d80ff6](https://linux-hardware.org/?probe=2204d80ff6) | Oct 22, 2019 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [d1d0246ce6](https://linux-hardware.org/?probe=d1d0246ce6) | Aug 09, 2019 |
| Dell          | Latitude 7390               | Notebook    | [9b0861a491](https://linux-hardware.org/?probe=9b0861a491) | Jul 04, 2019 |
| Dell          | Latitude 7390               | Notebook    | [5090404699](https://linux-hardware.org/?probe=5090404699) | Jul 04, 2019 |
| Lenovo        | ThinkPad L480 20LSS0M100    | Notebook    | [b1b6812c4f](https://linux-hardware.org/?probe=b1b6812c4f) | May 19, 2019 |
| Dell          | 0HHV7N A00                  | Desktop     | [9e55c4bdee](https://linux-hardware.org/?probe=9e55c4bdee) | Apr 05, 2019 |
| HP            | 158A                        | Desktop     | [6924d366ab](https://linux-hardware.org/?probe=6924d366ab) | Jan 09, 2019 |
| Dell          | 05DN3X A00                  | Desktop     | [4be9ce0f72](https://linux-hardware.org/?probe=4be9ce0f72) | Dec 20, 2018 |
| Lenovo        | ThinkPad X131e 3368CTO      | Notebook    | [c3f67b75e2](https://linux-hardware.org/?probe=c3f67b75e2) | Oct 31, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| RHEL 8 | 192       | 63.16%  |
| RHEL 9 | 68        | 22.37%  |
| RHEL 7 | 44        | 14.47%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| RHEL | 301       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64 | 14        | 3.99%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 14        | 3.99%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 12        | 3.42%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 11        | 3.13%   |
| 4.18.0-305.el8.x86_64        | 10        | 2.85%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 10        | 2.85%   |
| 5.14.0-284.30.1.el9_2.x86_64 | 9         | 2.56%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 9         | 2.56%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 9         | 2.56%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 9         | 2.56%   |
| 4.18.0-425.10.1.el8_7.x86_64 | 8         | 2.28%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 8         | 2.28%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 8         | 2.28%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 7         | 1.99%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 7         | 1.99%   |
| 4.18.0-193.el8.x86_64        | 7         | 1.99%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 6         | 1.71%   |
| 4.18.0-425.3.1.el8.x86_64    | 6         | 1.71%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 6         | 1.71%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 6         | 1.71%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 6         | 1.71%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 6         | 1.71%   |
| 3.10.0-1062.12.1.el7.x86_64  | 6         | 1.71%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 5         | 1.42%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 5         | 1.42%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 5         | 1.42%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 5         | 1.42%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 4         | 1.14%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 4         | 1.14%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 4         | 1.14%   |
| 4.18.0-372.9.1.el8.x86_64    | 4         | 1.14%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 4         | 1.14%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 1.14%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 4         | 1.14%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 4         | 1.14%   |
| 4.18.0-147.el8.x86_64        | 4         | 1.14%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 3         | 0.85%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 3         | 0.85%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 3         | 0.85%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 3         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 186       | 61.18%  |
| 5.14.0   | 68        | 22.37%  |
| 3.10.0   | 44        | 14.47%  |
| 5.9.1    | 1         | 0.33%   |
| 5.13.13  | 1         | 0.33%   |
| 5.13.0   | 1         | 0.33%   |
| 5.10.6   | 1         | 0.33%   |
| 4.19.150 | 1         | 0.33%   |
| Unknown  | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 186       | 61.18%  |
| 5.14    | 68        | 22.37%  |
| 3.10    | 44        | 14.47%  |
| 5.13    | 2         | 0.66%   |
| 5.9     | 1         | 0.33%   |
| 5.10    | 1         | 0.33%   |
| 4.19    | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 299       | 99.34%  |
| aarch64 | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 232       | 74.6%   |
| Unknown         | 51        | 16.4%   |
| GNOME Classic   | 14        | 4.5%    |
| KDE5            | 6         | 1.93%   |
| KDE4            | 2         | 0.64%   |
| KDE             | 2         | 0.64%   |
| XFCE            | 1         | 0.32%   |
| MATE            | 1         | 0.32%   |
| GNOME Flashback | 1         | 0.32%   |
| Cinnamon        | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 150       | 48.7%   |
| Wayland | 125       | 40.58%  |
| Unknown | 31        | 10.06%  |
| Tty     | 2         | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 218       | 70.1%   |
| GDM     | 89        | 28.62%  |
| SDDM    | 2         | 0.64%   |
| LightDM | 2         | 0.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 200       | 65.36%  |
| Unknown | 27        | 8.82%   |
| en_GB   | 22        | 7.19%   |
| en_IN   | 8         | 2.61%   |
| pt_BR   | 6         | 1.96%   |
| de_DE   | 5         | 1.63%   |
| ru_RU   | 4         | 1.31%   |
| pl_PL   | 4         | 1.31%   |
| fr_FR   | 4         | 1.31%   |
| es_ES   | 3         | 0.98%   |
| en_NZ   | 3         | 0.98%   |
| nl_NL   | 2         | 0.65%   |
| ja_JP   | 2         | 0.65%   |
| es_AR   | 2         | 0.65%   |
| en_IE   | 2         | 0.65%   |
| cs_CZ   | 2         | 0.65%   |
| sl_SI   | 1         | 0.33%   |
| ko_KR   | 1         | 0.33%   |
| it_IT   | 1         | 0.33%   |
| es_MX   | 1         | 0.33%   |
| es_EC   | 1         | 0.33%   |
| es_CO   | 1         | 0.33%   |
| en_ZA   | 1         | 0.33%   |
| en_DK   | 1         | 0.33%   |
| en_CA   | 1         | 0.33%   |
| de_CH   | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 228       | 74.51%  |
| BIOS | 78        | 25.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 260       | 85.53%  |
| Ext4    | 32        | 10.53%  |
| Unknown | 12        | 3.95%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 179       | 57.56%  |
| GPT     | 110       | 35.37%  |
| MBR     | 22        | 7.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 266       | 87.21%  |
| Yes       | 39        | 12.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 277       | 90.82%  |
| Yes       | 28        | 9.18%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 98        | 32.56%  |
| Dell                    | 65        | 21.59%  |
| Hewlett-Packard         | 37        | 12.29%  |
| ASUSTek Computer        | 31        | 10.3%   |
| Gigabyte Technology     | 14        | 4.65%   |
| MSI                     | 12        | 3.99%   |
| ASRock                  | 7         | 2.33%   |
| Intel                   | 6         | 1.99%   |
| Unknown                 | 5         | 1.66%   |
| Supermicro              | 3         | 1%      |
| Acer                    | 3         | 1%      |
| ZTSYSTEMS               | 2         | 0.66%   |
| Sony                    | 2         | 0.66%   |
| Getac                   | 2         | 0.66%   |
| TUXEDO                  | 1         | 0.33%   |
| Toshiba                 | 1         | 0.33%   |
| Timi                    | 1         | 0.33%   |
| System76                | 1         | 0.33%   |
| Samsung Electronics     | 1         | 0.33%   |
| Razer                   | 1         | 0.33%   |
| Raspberry Pi Foundation | 1         | 0.33%   |
| MiTAC                   | 1         | 0.33%   |
| IBM                     | 1         | 0.33%   |
| Hardkernel              | 1         | 0.33%   |
| CX / Air Computers.     | 1         | 0.33%   |
| AZW                     | 1         | 0.33%   |
| AMI                     | 1         | 0.33%   |
| Alienware               | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge FC630                     | 6         | 1.99%   |
| Unknown                                  | 6         | 1.99%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 4         | 1.33%   |
| Dell PowerEdge R230                      | 4         | 1.33%   |
| ASUS All Series                          | 4         | 1.33%   |
| Supermicro X10DRi                        | 2         | 0.66%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 0.66%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 0.66%   |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 0.66%   |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 0.66%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 2         | 0.66%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 0.66%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 0.66%   |
| Lenovo 7X56CTO1WW HR630X                 | 2         | 0.66%   |
| HP Z620 Workstation                      | 2         | 0.66%   |
| HP EliteBook 8460p                       | 2         | 0.66%   |
| HP EliteBook 2570p                       | 2         | 0.66%   |
| Dell Precision Tower 5810                | 2         | 0.66%   |
| Dell Precision 7560                      | 2         | 0.66%   |
| Dell Precision 7510                      | 2         | 0.66%   |
| Dell PowerEdge R740                      | 2         | 0.66%   |
| Dell PowerEdge R630                      | 2         | 0.66%   |
| Dell OptiPlex 9020                       | 2         | 0.66%   |
| Dell Latitude E6430                      | 2         | 0.66%   |
| Dell Latitude 5300                       | 2         | 0.66%   |
| ZTSYSTEMS Z802                           | 1         | 0.33%   |
| ZTSYSTEMS Z801                           | 1         | 0.33%   |
| TUXEDO N13xWU                            | 1         | 0.33%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.33%   |
| Timi TM1707                              | 1         | 0.33%   |
| System76 Galago Pro                      | 1         | 0.33%   |
| Supermicro X7DW3                         | 1         | 0.33%   |
| Sony VPCEB4L1R                           | 1         | 0.33%   |
| Sony VPCEB23FM                           | 1         | 0.33%   |
| Samsung 730QCJ/730QCR                    | 1         | 0.33%   |
| Razer Blade 15 Mid 2019-Base             | 1         | 0.33%   |
| RPi Raspberry Pi 4 Model B               | 1         | 0.33%   |
| MSI MS-7D54                              | 1         | 0.33%   |
| MSI MS-7D25                              | 1         | 0.33%   |
| MSI MS-7C95                              | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 81        | 26.91%  |
| Dell Precision     | 19        | 6.31%   |
| Dell PowerEdge     | 17        | 5.65%   |
| Dell Latitude      | 14        | 4.65%   |
| HP EliteBook       | 7         | 2.33%   |
| HP ProLiant        | 6         | 1.99%   |
| ASUS ROG           | 6         | 1.99%   |
| ASUS PRIME         | 6         | 1.99%   |
| Unknown            | 6         | 1.99%   |
| Dell Inspiron      | 5         | 1.66%   |
| ASUS All           | 4         | 1.33%   |
| Lenovo ThinkCentre | 3         | 1%      |
| HP ZBook           | 3         | 1%      |
| Dell OptiPlex      | 3         | 1%      |
| ASUS TUF           | 3         | 1%      |
| Supermicro X10DRi  | 2         | 0.66%   |
| Lenovo ThinkSystem | 2         | 0.66%   |
| Lenovo ThinkBook   | 2         | 0.66%   |
| Lenovo 7X56CTO1WW  | 2         | 0.66%   |
| HP Z620            | 2         | 0.66%   |
| HP Z230            | 2         | 0.66%   |
| HP ProBook         | 2         | 0.66%   |
| HP Laptop          | 2         | 0.66%   |
| Dell XPS           | 2         | 0.66%   |
| ASUS VivoBook      | 2         | 0.66%   |
| Acer Aspire        | 2         | 0.66%   |
| ZTSYSTEMS Z802     | 1         | 0.33%   |
| ZTSYSTEMS Z801     | 1         | 0.33%   |
| TUXEDO N13xWU      | 1         | 0.33%   |
| Toshiba Satellite  | 1         | 0.33%   |
| Timi TM1707        | 1         | 0.33%   |
| System76 Galago    | 1         | 0.33%   |
| Supermicro X7DW3   | 1         | 0.33%   |
| Sony VPCEB4L1R     | 1         | 0.33%   |
| Sony VPCEB23FM     | 1         | 0.33%   |
| Samsung 730QCJ     | 1         | 0.33%   |
| Razer Blade        | 1         | 0.33%   |
| RPi Raspberry      | 1         | 0.33%   |
| MSI MS-7D54        | 1         | 0.33%   |
| MSI MS-7D25        | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 51        | 16.94%  |
| 2020 | 44        | 14.62%  |
| 2018 | 39        | 12.96%  |
| 2016 | 25        | 8.31%   |
| 2021 | 24        | 7.97%   |
| 2017 | 21        | 6.98%   |
| 2012 | 20        | 6.64%   |
| 2015 | 19        | 6.31%   |
| 2022 | 14        | 4.65%   |
| 2013 | 11        | 3.65%   |
| 2014 | 9         | 2.99%   |
| 2011 | 8         | 2.66%   |
| 2010 | 8         | 2.66%   |
| 2023 | 6         | 1.99%   |
| 2009 | 2         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 160       | 53.16%  |
| Desktop        | 96        | 31.89%  |
| Server         | 29        | 9.63%   |
| Mini pc        | 8         | 2.66%   |
| Convertible    | 5         | 1.66%   |
| All in one     | 2         | 0.66%   |
| System on chip | 1         | 0.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 267       | 87.83%  |
| Enabled  | 37        | 12.17%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 300       | 99.67%  |
| Yes  | 1         | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 78        | 25.32%  |
| 8.01-16.0       | 60        | 19.48%  |
| 64.01-256.0     | 49        | 15.91%  |
| 4.01-8.0        | 47        | 15.26%  |
| 16.01-24.0      | 41        | 13.31%  |
| 3.01-4.0        | 12        | 3.9%    |
| 24.01-32.0      | 12        | 3.9%    |
| More than 256.0 | 7         | 2.27%   |
| 2.01-3.0        | 1         | 0.32%   |
| Unknown         | 1         | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 108       | 32.34%  |
| 2.01-3.0        | 75        | 22.46%  |
| 3.01-4.0        | 53        | 15.87%  |
| 8.01-16.0       | 48        | 14.37%  |
| 1.01-2.0        | 28        | 8.38%   |
| 16.01-24.0      | 7         | 2.1%    |
| 24.01-32.0      | 6         | 1.8%    |
| 0.51-1.0        | 4         | 1.2%    |
| 32.01-64.0      | 2         | 0.6%    |
| More than 256.0 | 1         | 0.3%    |
| 64.01-256.0     | 1         | 0.3%    |
| Unknown         | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 164       | 52.4%   |
| 2      | 69        | 22.04%  |
| 3      | 36        | 11.5%   |
| 5      | 13        | 4.15%   |
| 4      | 13        | 4.15%   |
| 6      | 4         | 1.28%   |
| 12     | 3         | 0.96%   |
| 0      | 3         | 0.96%   |
| 14     | 2         | 0.64%   |
| 8      | 2         | 0.64%   |
| 7      | 2         | 0.64%   |
| 11     | 1         | 0.32%   |
| 10     | 1         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 240       | 79.21%  |
| Yes       | 63        | 20.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 274       | 90.73%  |
| No        | 28        | 9.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 218       | 72.19%  |
| No        | 84        | 27.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 58.58%  |
| No        | 128       | 41.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 80        | 26.58%  |
| India        | 25        | 8.31%   |
| UK           | 20        | 6.64%   |
| Germany      | 19        | 6.31%   |
| Czechia      | 14        | 4.65%   |
| Canada       | 9         | 2.99%   |
| Brazil       | 8         | 2.66%   |
| Spain        | 7         | 2.33%   |
| Norway       | 7         | 2.33%   |
| France       | 7         | 2.33%   |
| Netherlands  | 6         | 1.99%   |
| Switzerland  | 5         | 1.66%   |
| Poland       | 5         | 1.66%   |
| Italy        | 5         | 1.66%   |
| South Africa | 4         | 1.33%   |
| Russia       | 4         | 1.33%   |
| Mexico       | 4         | 1.33%   |
| Finland      | 4         | 1.33%   |
| New Zealand  | 3         | 1%      |
| Lithuania    | 3         | 1%      |
| Japan        | 3         | 1%      |
| Guatemala    | 3         | 1%      |
| Egypt        | 3         | 1%      |
| Chile        | 3         | 1%      |
| Australia    | 3         | 1%      |
| Argentina    | 3         | 1%      |
| Ukraine      | 2         | 0.66%   |
| Turkey       | 2         | 0.66%   |
| South Korea  | 2         | 0.66%   |
| Singapore    | 2         | 0.66%   |
| Romania      | 2         | 0.66%   |
| Kenya        | 2         | 0.66%   |
| Indonesia    | 2         | 0.66%   |
| Colombia     | 2         | 0.66%   |
| China        | 2         | 0.66%   |
| Austria      | 2         | 0.66%   |
| Turkmenistan | 1         | 0.33%   |
| Sweden       | 1         | 0.33%   |
| Sri Lanka    | 1         | 0.33%   |
| Slovenia     | 1         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Prague           | 11        | 3.47%   |
| Quincy           | 8         | 2.52%   |
| Petersberg       | 6         | 1.89%   |
| Voll             | 4         | 1.26%   |
| Turku            | 3         | 0.95%   |
| San Jose         | 3         | 0.95%   |
| Munich           | 3         | 0.95%   |
| Milan            | 3         | 0.95%   |
| Mexico City      | 3         | 0.95%   |
| Guatemala City   | 3         | 0.95%   |
| Chicago          | 3         | 0.95%   |
| Chennai          | 3         | 0.95%   |
| Bengaluru        | 3         | 0.95%   |
| Wellington       | 2         | 0.63%   |
| Vienna           | 2         | 0.63%   |
| Singapore        | 2         | 0.63%   |
| Santiago         | 2         | 0.63%   |
| Nairobi          | 2         | 0.63%   |
| Montreal         | 2         | 0.63%   |
| Madrid           | 2         | 0.63%   |
| Leeds            | 2         | 0.63%   |
| Kyiv             | 2         | 0.63%   |
| Kongsberg        | 2         | 0.63%   |
| Houston          | 2         | 0.63%   |
| Helsinki         | 2         | 0.63%   |
| Didcot           | 2         | 0.63%   |
| Des Moines       | 2         | 0.63%   |
| Cairo            | 2         | 0.63%   |
| Berlin           | 2         | 0.63%   |
| Bandung          | 2         | 0.63%   |
| Zaragoza         | 1         | 0.32%   |
| Yorktown Heights | 1         | 0.32%   |
| Yongin-si        | 1         | 0.32%   |
| Wroclaw          | 1         | 0.32%   |
| Wildomar         | 1         | 0.32%   |
| Wiesbaden        | 1         | 0.32%   |
| Whiteley         | 1         | 0.32%   |
| Webster          | 1         | 0.32%   |
| Wayne            | 1         | 0.32%   |
| Wake Forest      | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 85        | 143    | 17.97%  |
| Seagate                      | 58        | 115    | 12.26%  |
| WDC                          | 57        | 93     | 12.05%  |
| Toshiba                      | 37        | 50     | 7.82%   |
| SanDisk                      | 27        | 41     | 5.71%   |
| SK hynix                     | 21        | 26     | 4.44%   |
| Kingston                     | 20        | 25     | 4.23%   |
| Intel                        | 20        | 33     | 4.23%   |
| Unknown                      | 16        | 20     | 3.38%   |
| Micron Technology            | 16        | 24     | 3.38%   |
| Crucial                      | 13        | 18     | 2.75%   |
| HGST                         | 9         | 12     | 1.9%    |
| A-DATA Technology            | 7         | 7      | 1.48%   |
| Phison                       | 6         | 10     | 1.27%   |
| Micron/Crucial Technology    | 5         | 7      | 1.06%   |
| KIOXIA                       | 5         | 6      | 1.06%   |
| Dell                         | 5         | 9      | 1.06%   |
| PNY                          | 4         | 5      | 0.85%   |
| Hitachi                      | 4         | 4      | 0.85%   |
| Hewlett-Packard              | 4         | 13     | 0.85%   |
| Gigabyte Technology          | 4         | 5      | 0.85%   |
| China                        | 4         | 4      | 0.85%   |
| Silicon Motion               | 3         | 4      | 0.63%   |
| Lenovo                       | 3         | 3      | 0.63%   |
| Kingston Technology Company  | 3         | 3      | 0.63%   |
| Corsair                      | 3         | 6      | 0.63%   |
| Western Digital              | 2         | 2      | 0.42%   |
| SSSTC                        | 2         | 2      | 0.42%   |
| SABRENT                      | 2         | 2      | 0.42%   |
| Plextor                      | 2         | 2      | 0.42%   |
| KingSpec                     | 2         | 2      | 0.42%   |
| ADATA Technology             | 2         | 2      | 0.42%   |
| XUM                          | 1         | 1      | 0.21%   |
| XPG                          | 1         | 1      | 0.21%   |
| UMIS                         | 1         | 1      | 0.21%   |
| Transcend                    | 1         | 1      | 0.21%   |
| Toshiba America Info Systems | 1         | 1      | 0.21%   |
| Team                         | 1         | 2      | 0.21%   |
| T-FORCE                      | 1         | 2      | 0.21%   |
| SMI                          | 1         | 2      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB                       | 10        | 1.84%   |
| Samsung NVMe SSD Drive 512GB                        | 8         | 1.47%   |
| Toshiba NVMe SSD Drive 256GB                        | 6         | 1.1%    |
| SanDisk NVMe SSD Drive 256GB                        | 6         | 1.1%    |
| Samsung SSD 860 EVO 1TB                             | 6         | 1.1%    |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 6         | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 6         | 1.1%    |
| HGST HTS721010A9E630 1TB                            | 6         | 1.1%    |
| Samsung NVMe SSD Drive 1024GB                       | 5         | 0.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 0.92%   |
| Toshiba MG04ACA100NY 1TB                            | 4         | 0.74%   |
| Samsung SSD 860 EVO 500GB                           | 4         | 0.74%   |
| Samsung NVMe SSD Drive 500GB                        | 4         | 0.74%   |
| Intel NVMe SSD Drive 512GB                          | 4         | 0.74%   |
| Dell MD34xx 26TB                                    | 4         | 0.74%   |
| WDC WD5003ABYZ-011FA0 500GB                         | 3         | 0.55%   |
| Toshiba NVMe SSD Drive 512GB                        | 3         | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3         | 0.55%   |
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3         | 0.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 3         | 0.55%   |
| Samsung SSD 870 EVO 1TB                             | 3         | 0.55%   |
| Samsung NVMe SSD Drive 2TB                          | 3         | 0.55%   |
| Samsung NVMe SSD Drive 1TB                          | 3         | 0.55%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 3         | 0.55%   |
| Micron NVMe SSD Drive 256GB                         | 3         | 0.55%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 0.55%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 0.55%   |
| Crucial CT240BX500SSD1 240GB                        | 3         | 0.55%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2         | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.37%   |
| WDC WD40EFRX-68N32N0 4TB                            | 2         | 0.37%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 2         | 0.37%   |
| WDC WD1003FZEX-00MK2A0 1TB                          | 2         | 0.37%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 2         | 0.37%   |
| Unknown SD/MMC/MS PRO 128GB                         | 2         | 0.37%   |
| Unknown NVMe SSD Drive 256GB                        | 2         | 0.37%   |
| Unknown MMC Card  256GB                             | 2         | 0.37%   |
| Unknown MMC Card  16GB                              | 2         | 0.37%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 114    | 38.67%  |
| WDC                 | 46        | 77     | 30.67%  |
| Toshiba             | 21        | 31     | 14%     |
| HGST                | 9         | 12     | 6%      |
| Hitachi             | 4         | 4      | 2.67%   |
| Dell                | 4         | 8      | 2.67%   |
| Unknown             | 2         | 2      | 1.33%   |
| Hewlett-Packard     | 2         | 9      | 1.33%   |
| SCST_FIO            | 1         | 9      | 0.67%   |
| Samsung Electronics | 1         | 2      | 0.67%   |
| Fantom              | 1         | 1      | 0.67%   |
| DELLBOSS            | 1         | 1      | 0.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 59     | 29.77%  |
| Kingston            | 14        | 18     | 10.69%  |
| Crucial             | 13        | 17     | 9.92%   |
| SanDisk             | 9         | 15     | 6.87%   |
| WDC                 | 8         | 10     | 6.11%   |
| Micron Technology   | 7         | 13     | 5.34%   |
| Intel               | 6         | 10     | 4.58%   |
| A-DATA Technology   | 5         | 5      | 3.82%   |
| SK hynix            | 4         | 8      | 3.05%   |
| PNY                 | 4         | 5      | 3.05%   |
| China               | 4         | 4      | 3.05%   |
| Corsair             | 3         | 6      | 2.29%   |
| Plextor             | 2         | 2      | 1.53%   |
| KingSpec            | 2         | 2      | 1.53%   |
| XUM                 | 1         | 1      | 0.76%   |
| Transcend           | 1         | 1      | 0.76%   |
| Toshiba             | 1         | 1      | 0.76%   |
| Team                | 1         | 2      | 0.76%   |
| Seagate             | 1         | 1      | 0.76%   |
| OCZ                 | 1         | 2      | 0.76%   |
| KINGBANK            | 1         | 1      | 0.76%   |
| Intenso             | 1         | 1      | 0.76%   |
| Hoodisk             | 1         | 1      | 0.76%   |
| Gigabyte Technology | 1         | 1      | 0.76%   |
| Anobit              | 1         | 1      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 169       | 255    | 39.76%  |
| HDD     | 123       | 270    | 28.94%  |
| SSD     | 117       | 187    | 27.53%  |
| MMC     | 10        | 11     | 2.35%   |
| Unknown | 6         | 10     | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 177       | 426    | 46.46%  |
| NVMe | 169       | 253    | 44.36%  |
| SAS  | 25        | 43     | 6.56%   |
| MMC  | 10        | 11     | 2.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 110       | 183    | 42.31%  |
| 0.51-1.0   | 83        | 128    | 31.92%  |
| 1.01-2.0   | 32        | 63     | 12.31%  |
| 3.01-4.0   | 15        | 39     | 5.77%   |
| 4.01-10.0  | 10        | 27     | 3.85%   |
| 20.01-50.0 | 4         | 8      | 1.54%   |
| 2.01-3.0   | 3         | 4      | 1.15%   |
| 10.01-20.0 | 3         | 5      | 1.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 99        | 31.33%  |
| 251-500        | 58        | 18.35%  |
| 501-1000       | 51        | 16.14%  |
| 1001-2000      | 30        | 9.49%   |
| More than 3000 | 26        | 8.23%   |
| Unknown        | 18        | 5.7%    |
| 2001-3000      | 11        | 3.48%   |
| 51-100         | 11        | 3.48%   |
| 1-20           | 7         | 2.22%   |
| 21-50          | 5         | 1.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 83        | 25.15%  |
| 21-50          | 73        | 22.12%  |
| 101-250        | 47        | 14.24%  |
| 51-100         | 47        | 14.24%  |
| 251-500        | 28        | 8.48%   |
| Unknown        | 18        | 5.45%   |
| 1001-2000      | 12        | 3.64%   |
| 501-1000       | 11        | 3.33%   |
| More than 3000 | 6         | 1.82%   |
| 2001-3000      | 5         | 1.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5003ABYZ-011FA0 500GB                    | 1         | 1      | 5.56%   |
| WDC WD50 00LPVX-22V0TT0 500GB                  | 1         | 1      | 5.56%   |
| WDC WD4000FYYZ-01UL1B1 4TB                     | 1         | 3      | 5.56%   |
| WDC WD10EALX-759BA1 1TB                        | 1         | 2      | 5.56%   |
| Transcend TS512GMTS800 512GB SSD               | 1         | 1      | 5.56%   |
| Seagate ST91000640NS 1TB                       | 1         | 2      | 5.56%   |
| Seagate ST6000NM0024-1HT17Z 6TB                | 1         | 2      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 5.56%   |
| Seagate ST1000DM010-2EP102 1TB                 | 1         | 1      | 5.56%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 830 Series 128GB       | 1         | 2      | 5.56%   |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 1         | 1      | 5.56%   |
| Micron Technology M510_2.5 7MM 256GB SSD       | 1         | 1      | 5.56%   |
| Intel SSDSC2BA800G4R 800GB                     | 1         | 2      | 5.56%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 5.56%   |
| Crucial CT1000BX500SSD1 1TB                    | 1         | 1      | 5.56%   |
| A-DATA Technology SU800NS38 256GB SSD          | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 6         | 8      | 33.33%  |
| WDC                       | 4         | 7      | 22.22%  |
| Transcend                 | 1         | 1      | 5.56%   |
| Samsung Electronics       | 1         | 2      | 5.56%   |
| Micron/Crucial Technology | 1         | 1      | 5.56%   |
| Micron Technology         | 1         | 1      | 5.56%   |
| Intel                     | 1         | 2      | 5.56%   |
| Hitachi                   | 1         | 1      | 5.56%   |
| Crucial                   | 1         | 1      | 5.56%   |
| A-DATA Technology         | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 8      | 54.55%  |
| WDC     | 4         | 7      | 36.36%  |
| Hitachi | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 16     | 56.25%  |
| SSD  | 6         | 8      | 37.5%   |
| NVMe | 1         | 1      | 6.25%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 193       | 431    | 59.2%   |
| Works    | 117       | 277    | 35.89%  |
| Malfunc  | 16        | 25     | 4.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 195       | 45.24%  |
| Samsung Electronics            | 55        | 12.76%  |
| AMD                            | 26        | 6.03%   |
| SanDisk                        | 22        | 5.1%    |
| SK hynix                       | 17        | 3.94%   |
| Toshiba America Info Systems   | 16        | 3.71%   |
| Broadcom / LSI                 | 16        | 3.71%   |
| Phison Electronics             | 10        | 2.32%   |
| Micron Technology              | 9         | 2.09%   |
| Kingston Technology Company    | 8         | 1.86%   |
| LSI Logic / Symbios Logic      | 7         | 1.62%   |
| KIOXIA                         | 7         | 1.62%   |
| Micron/Crucial Technology      | 6         | 1.39%   |
| ASMedia Technology             | 6         | 1.39%   |
| ADATA Technology               | 6         | 1.39%   |
| Silicon Motion                 | 5         | 1.16%   |
| Marvell Technology Group       | 4         | 0.93%   |
| Hewlett-Packard                | 4         | 0.93%   |
| Lenovo                         | 3         | 0.7%    |
| Western Digital                | 2         | 0.46%   |
| Biwin Storage Technology       | 2         | 0.46%   |
| Union Memory (Shenzhen)        | 1         | 0.23%   |
| Solid State Storage Technology | 1         | 0.23%   |
| PMC-Sierra                     | 1         | 0.23%   |
| Lite-On Technology             | 1         | 0.23%   |
| HighPoint Technologies         | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 36        | 7.36%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 4.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 3.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 17        | 3.48%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 15        | 3.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13        | 2.66%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 12        | 2.45%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 12        | 2.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 1.84%   |
| Intel SATA Controller [RAID mode]                                              | 9         | 1.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 1.84%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 9         | 1.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 1.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 1.64%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 7         | 1.43%   |
| Intel SSD 660P Series                                                          | 7         | 1.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 1.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 1.43%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 6         | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.23%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 6         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 1.23%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6         | 1.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 1.02%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 5         | 1.02%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 5         | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.02%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                            | 5         | 1.02%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 0.82%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 4         | 0.82%   |
| Phison E12 NVMe Controller                                                     | 4         | 0.82%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 4         | 0.82%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                           | 4         | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 0.82%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 4         | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.82%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 4         | 0.82%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 4         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 185       | 43.12%  |
| NVMe | 169       | 39.39%  |
| RAID | 54        | 12.59%  |
| SAS  | 13        | 3.03%   |
| IDE  | 8         | 1.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 268       | 89.04%  |
| AMD    | 32        | 10.63%  |
| ARM    | 1         | 0.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz      | 11        | 3.65%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 10        | 3.32%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 10        | 3.32%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 6         | 1.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 1.99%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 6         | 1.99%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 5         | 1.66%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz     | 4         | 1.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 1.33%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 4         | 1.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 1.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.33%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz     | 3         | 1%      |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz     | 3         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 1%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 1%      |
| Intel Core i7-7600U CPU @ 2.80GHz       | 3         | 1%      |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 3         | 1%      |
| Intel Core i7-6600U CPU @ 2.60GHz       | 3         | 1%      |
| Intel Core i7-10510U CPU @ 1.80GHz      | 3         | 1%      |
| Intel Core i5-8265U CPU @ 1.60GHz       | 3         | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz       | 3         | 1%      |
| Intel Core i5-5300U CPU @ 2.30GHz       | 3         | 1%      |
| Intel 12th Gen Core i7-12700H           | 3         | 1%      |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 3         | 1%      |
| Intel Xeon Silver 4114 CPU @ 2.20GHz    | 2         | 0.66%   |
| Intel Xeon CPU E5620 @ 2.40GHz          | 2         | 0.66%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz     | 2         | 0.66%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 2         | 0.66%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz     | 2         | 0.66%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz     | 2         | 0.66%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz  | 2         | 0.66%   |
| Intel Core i7-9850H CPU @ 2.60GHz       | 2         | 0.66%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 2         | 0.66%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 2         | 0.66%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.66%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 2         | 0.66%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 2         | 0.66%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 101       | 33.55%  |
| Intel Core i5        | 54        | 17.94%  |
| Intel Xeon           | 50        | 16.61%  |
| Other                | 29        | 9.63%   |
| Intel Core i3        | 15        | 4.98%   |
| AMD Ryzen 9          | 8         | 2.66%   |
| AMD Ryzen 7          | 7         | 2.33%   |
| AMD Ryzen 5          | 7         | 2.33%   |
| Intel Core i9        | 5         | 1.66%   |
| Intel Xeon Silver    | 3         | 1%      |
| Intel Xeon Platinum  | 2         | 0.66%   |
| Intel Xeon Gold      | 2         | 0.66%   |
| Intel Pentium Gold   | 2         | 0.66%   |
| Intel Pentium        | 2         | 0.66%   |
| Intel Celeron        | 2         | 0.66%   |
| AMD Ryzen 7 PRO      | 2         | 0.66%   |
| AMD Ryzen 3          | 2         | 0.66%   |
| AMD EPYC             | 2         | 0.66%   |
| Intel Pentium Silver | 1         | 0.33%   |
| Intel Core 2 Duo     | 1         | 0.33%   |
| AMD FX               | 1         | 0.33%   |
| AMD Athlon X4        | 1         | 0.33%   |
| AMD A4               | 1         | 0.33%   |
| AMD A10              | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 124       | 41.2%   |
| 2      | 55        | 18.27%  |
| 6      | 41        | 13.62%  |
| 8      | 31        | 10.3%   |
| 12     | 16        | 5.32%   |
| 16     | 9         | 2.99%   |
| 10     | 5         | 1.66%   |
| 20     | 4         | 1.33%   |
| 14     | 4         | 1.33%   |
| 24     | 3         | 1%      |
| 48     | 2         | 0.66%   |
| 36     | 2         | 0.66%   |
| 384    | 1         | 0.33%   |
| 96     | 1         | 0.33%   |
| 64     | 1         | 0.33%   |
| 32     | 1         | 0.33%   |
| 1      | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 271       | 90.03%  |
| 2      | 29        | 9.63%   |
| 8      | 1         | 0.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 257       | 84.82%  |
| 1      | 46        | 15.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 293       | 96.7%   |
| Unknown        | 10        | 3.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 38        | 12.54%  |
| Unknown    | 21        | 6.93%   |
| 0x806ea    | 17        | 5.61%   |
| 0x306a9    | 17        | 5.61%   |
| 0x906ea    | 16        | 5.28%   |
| 0x306c3    | 14        | 4.62%   |
| 0xa0652    | 12        | 3.96%   |
| 0x506e3    | 12        | 3.96%   |
| 0x306f2    | 11        | 3.63%   |
| 0x906e9    | 9         | 2.97%   |
| 0x406e3    | 9         | 2.97%   |
| 0x206a7    | 9         | 2.97%   |
| 0x906ed    | 8         | 2.64%   |
| 0x806d1    | 7         | 2.31%   |
| 0x406f1    | 7         | 2.31%   |
| 0x806c1    | 6         | 1.98%   |
| 0x906a3    | 5         | 1.65%   |
| 0x806e9    | 5         | 1.65%   |
| 0x08701021 | 5         | 1.65%   |
| 0xa0671    | 4         | 1.32%   |
| 0x306e4    | 4         | 1.32%   |
| 0x306d4    | 4         | 1.32%   |
| 0x206d7    | 4         | 1.32%   |
| 0x20655    | 4         | 1.32%   |
| 0x40651    | 3         | 0.99%   |
| 0x206c2    | 3         | 0.99%   |
| 0x0a50000c | 3         | 0.99%   |
| 0x08600103 | 3         | 0.99%   |
| 0x08108102 | 3         | 0.99%   |
| 0x906c0    | 2         | 0.66%   |
| 0x90672    | 2         | 0.66%   |
| 0x706e5    | 2         | 0.66%   |
| 0x50654    | 2         | 0.66%   |
| 0x0a20120a | 2         | 0.66%   |
| 0x08701013 | 2         | 0.66%   |
| 0x08600106 | 2         | 0.66%   |
| 0xb0671    | 1         | 0.33%   |
| 0xa0660    | 1         | 0.33%   |
| 0xa0655    | 1         | 0.33%   |
| 0x906eb    | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 98        | 32.45%  |
| Skylake          | 31        | 10.26%  |
| Haswell          | 30        | 9.93%   |
| IvyBridge        | 22        | 7.28%   |
| CometLake        | 15        | 4.97%   |
| Zen 2            | 14        | 4.64%   |
| SandyBridge      | 13        | 4.3%    |
| Icelake          | 13        | 4.3%    |
| Alderlake Hybrid | 12        | 3.97%   |
| Broadwell        | 11        | 3.64%   |
| Westmere         | 8         | 2.65%   |
| TigerLake        | 6         | 1.99%   |
| Unknown          | 6         | 1.99%   |
| Zen 3            | 5         | 1.66%   |
| Zen+             | 4         | 1.32%   |
| Zen              | 3         | 0.99%   |
| Tremont          | 2         | 0.66%   |
| Penryn           | 2         | 0.66%   |
| Excavator        | 2         | 0.66%   |
| Steamroller      | 1         | 0.33%   |
| Sapphire Rapids  | 1         | 0.33%   |
| Piledriver       | 1         | 0.33%   |
| Nehalem          | 1         | 0.33%   |
| Goldmont plus    | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 183       | 50.69%  |
| Nvidia                     | 103       | 28.53%  |
| AMD                        | 42        | 11.63%  |
| Matrox Electronics Systems | 23        | 6.37%   |
| ASPEED Technology          | 10        | 2.77%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 19        | 5.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 19        | 5.19%   |
| Intel UHD Graphics 620                                                      | 18        | 4.92%   |
| Matrox Electronics Systems G200eR2                                          | 13        | 3.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 11        | 3.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 10        | 2.73%   |
| ASPEED Technology ASPEED Graphics Family                                    | 10        | 2.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 9         | 2.46%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 2.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 1.64%   |
| Intel HD Graphics 630                                                       | 6         | 1.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6         | 1.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 1.64%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 6         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 1.37%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 5         | 1.37%   |
| Intel HD Graphics 530                                                       | 5         | 1.37%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 5         | 1.37%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 4         | 1.09%   |
| Matrox Electronics Systems MGA G200EH                                       | 4         | 1.09%   |
| Intel HD Graphics 620                                                       | 4         | 1.09%   |
| Intel HD Graphics 5500                                                      | 4         | 1.09%   |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 1.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 1.09%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 0.82%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                       | 3         | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 0.82%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3         | 0.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 3         | 0.82%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 3         | 0.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 0.82%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3         | 0.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 0.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3         | 0.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 0.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.55%   |
| Nvidia TU117GL [T400 4GB]                                                   | 2         | 0.55%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2         | 0.55%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 128       | 42.11%  |
| 1 x Nvidia              | 58        | 19.08%  |
| Intel + Nvidia          | 38        | 12.5%   |
| 1 x AMD                 | 26        | 8.55%   |
| 1 x Matrox              | 22        | 7.24%   |
| Intel + AMD             | 10        | 3.29%   |
| 1 x ASPEED              | 7         | 2.3%    |
| Other                   | 3         | 0.99%   |
| AMD + Nvidia            | 3         | 0.99%   |
| 2 x Nvidia              | 2         | 0.66%   |
| 2 x AMD                 | 2         | 0.66%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.33%   |
| 2 x Intel               | 1         | 0.33%   |
| Nvidia + Matrox         | 1         | 0.33%   |
| Nvidia + ASPEED         | 1         | 0.33%   |
| AMD + ASPEED            | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 234       | 76.72%  |
| Proprietary | 44        | 14.43%  |
| Unknown     | 27        | 8.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 188       | 61.04%  |
| 1.01-2.0   | 29        | 9.42%   |
| 3.01-4.0   | 22        | 7.14%   |
| 7.01-8.0   | 17        | 5.52%   |
| 0.51-1.0   | 14        | 4.55%   |
| 5.01-6.0   | 12        | 3.9%    |
| 0.01-0.5   | 11        | 3.57%   |
| 2.01-3.0   | 5         | 1.62%   |
| 8.01-16.0  | 5         | 1.62%   |
| 16.01-24.0 | 3         | 0.97%   |
| 4.01-5.0   | 2         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 39        | 11.47%  |
| Samsung Electronics  | 36        | 10.59%  |
| AU Optronics         | 35        | 10.29%  |
| BOE                  | 33        | 9.71%   |
| Chimei Innolux       | 27        | 7.94%   |
| LG Display           | 26        | 7.65%   |
| Lenovo               | 25        | 7.35%   |
| Goldstar             | 18        | 5.29%   |
| Hewlett-Packard      | 16        | 4.71%   |
| Acer                 | 9         | 2.65%   |
| Sharp                | 8         | 2.35%   |
| InfoVision           | 6         | 1.76%   |
| Philips              | 5         | 1.47%   |
| BenQ                 | 5         | 1.47%   |
| AOC                  | 5         | 1.47%   |
| Eizo                 | 4         | 1.18%   |
| Unknown              | 4         | 1.18%   |
| ViewSonic            | 3         | 0.88%   |
| PANDA                | 3         | 0.88%   |
| Gigabyte Technology  | 3         | 0.88%   |
| Ancor Communications | 3         | 0.88%   |
| LGD                  | 2         | 0.59%   |
| Lenovo Group Limited | 2         | 0.59%   |
| Iiyama               | 2         | 0.59%   |
| BOE Technology Group | 2         | 0.59%   |
| Vizio                | 1         | 0.29%   |
| Unknown              | 1         | 0.29%   |
| Sun                  | 1         | 0.29%   |
| STD                  | 1         | 0.29%   |
| Sony                 | 1         | 0.29%   |
| Sceptre Tech         | 1         | 0.29%   |
| Planar               | 1         | 0.29%   |
| Panasonic            | 1         | 0.29%   |
| OUT                  | 1         | 0.29%   |
| Microstep            | 1         | 0.29%   |
| LG Electronics       | 1         | 0.29%   |
| ITE                  | 1         | 0.29%   |
| Insignia             | 1         | 0.29%   |
| Haier                | 1         | 0.29%   |
| EVE                  | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 7         | 1.92%   |
| Dell LCD Monitor DEL0001 1280x1024                                   | 6         | 1.65%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch             | 5         | 1.37%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 5         | 1.37%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 5         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 5         | 1.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 5         | 1.37%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 4         | 1.1%    |
| Unknown                                                              | 4         | 1.1%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3         | 0.82%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch         | 3         | 0.82%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch               | 3         | 0.82%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 3         | 0.82%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 3         | 0.82%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                    | 3         | 0.82%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                | 3         | 0.82%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch       | 3         | 0.82%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 2         | 0.55%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch              | 2         | 0.55%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 2         | 0.55%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch              | 2         | 0.55%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.55%   |
| LGD LCD Monitor 1920x1080                                            | 2         | 0.55%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch          | 2         | 0.55%   |
| Lenovo P27h-20 LEN61E9 2560x1440 609x349mm 27.6-inch                 | 2         | 0.55%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch             | 2         | 0.55%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch           | 2         | 0.55%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 2         | 0.55%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                 | 2         | 0.55%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch           | 2         | 0.55%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch     | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch       | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch        | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 2         | 0.55%   |
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                   | 2         | 0.55%   |
| Vizio E480i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                 | 1         | 0.27%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch        | 1         | 0.27%   |
| ViewSonic VA2419 Series VSC7B32 1920x1080 530x300mm 24.0-inch        | 1         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 163       | 53.44%  |
| 1366x768 (WXGA)    | 26        | 8.52%   |
| 3840x2160 (4K)     | 25        | 8.2%    |
| 2560x1440 (QHD)    | 21        | 6.89%   |
| 1600x900 (HD+)     | 12        | 3.93%   |
| 1920x1200 (WUXGA)  | 8         | 2.62%   |
| 1280x1024 (SXGA)   | 8         | 2.62%   |
| 3440x1440          | 6         | 1.97%   |
| 2560x1080          | 6         | 1.97%   |
| Unknown            | 6         | 1.97%   |
| 3840x1080          | 4         | 1.31%   |
| 1680x1050 (WSXGA+) | 4         | 1.31%   |
| 2560x1600          | 2         | 0.66%   |
| 1440x900 (WXGA+)   | 2         | 0.66%   |
| 9600x2160          | 1         | 0.33%   |
| 7680x2160          | 1         | 0.33%   |
| 7280x2160          | 1         | 0.33%   |
| 6400x2160          | 1         | 0.33%   |
| 5120x1440          | 1         | 0.33%   |
| 3840x1600          | 1         | 0.33%   |
| 3840x1200          | 1         | 0.33%   |
| 2160x1350          | 1         | 0.33%   |
| 2048x1152          | 1         | 0.33%   |
| 1280x800 (WXGA)    | 1         | 0.33%   |
| 1280x768           | 1         | 0.33%   |
| 1280x720 (HD)      | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 57        | 16.91%  |
| 14      | 43        | 12.76%  |
| 13      | 37        | 10.98%  |
| 24      | 32        | 9.5%    |
| 27      | 29        | 8.61%   |
| 23      | 27        | 8.01%   |
| Unknown | 26        | 7.72%   |
| 21      | 18        | 5.34%   |
| 31      | 9         | 2.67%   |
| 34      | 8         | 2.37%   |
| 17      | 7         | 2.08%   |
| 20      | 5         | 1.48%   |
| 12      | 5         | 1.48%   |
| 54      | 4         | 1.19%   |
| 32      | 3         | 0.89%   |
| 16      | 3         | 0.89%   |
| 84      | 2         | 0.59%   |
| 72      | 2         | 0.59%   |
| 47      | 2         | 0.59%   |
| 22      | 2         | 0.59%   |
| 19      | 2         | 0.59%   |
| 18      | 2         | 0.59%   |
| 64      | 1         | 0.3%    |
| 52      | 1         | 0.3%    |
| 49      | 1         | 0.3%    |
| 43      | 1         | 0.3%    |
| 40      | 1         | 0.3%    |
| 39      | 1         | 0.3%    |
| 37      | 1         | 0.3%    |
| 35      | 1         | 0.3%    |
| 33      | 1         | 0.3%    |
| 28      | 1         | 0.3%    |
| 25      | 1         | 0.3%    |
| 11      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 129       | 39.21%  |
| 501-600     | 77        | 23.4%   |
| 401-500     | 27        | 8.21%   |
| Unknown     | 26        | 7.9%    |
| 201-300     | 18        | 5.47%   |
| 601-700     | 15        | 4.56%   |
| 701-800     | 12        | 3.65%   |
| 1001-1500   | 9         | 2.74%   |
| 351-400     | 7         | 2.13%   |
| 801-900     | 4         | 1.22%   |
| 1501-2000   | 4         | 1.22%   |
| 901-1000    | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 216       | 77.98%  |
| 16/10   | 21        | 7.58%   |
| Unknown | 18        | 6.5%    |
| 21/9    | 11        | 3.97%   |
| 5/4     | 8         | 2.89%   |
| 4/3     | 1         | 0.36%   |
| 32/9    | 1         | 0.36%   |
| 3/2     | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 68        | 20.36%  |
| 201-250        | 64        | 19.16%  |
| 101-110        | 56        | 16.77%  |
| 301-350        | 29        | 8.68%   |
| Unknown        | 26        | 7.78%   |
| 351-500        | 21        | 6.29%   |
| 251-300        | 13        | 3.89%   |
| 71-80          | 12        | 3.59%   |
| More than 1000 | 10        | 2.99%   |
| 151-200        | 10        | 2.99%   |
| 501-1000       | 7         | 2.1%    |
| 121-130        | 6         | 1.8%    |
| 61-70          | 5         | 1.5%    |
| 111-120        | 3         | 0.9%    |
| 141-150        | 2         | 0.6%    |
| 51-60          | 1         | 0.3%    |
| 131-140        | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 113       | 34.98%  |
| 51-100        | 95        | 29.41%  |
| 101-120       | 54        | 16.72%  |
| Unknown       | 26        | 8.05%   |
| 161-240       | 21        | 6.5%    |
| 1-50          | 8         | 2.48%   |
| More than 240 | 6         | 1.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 197       | 62.74%  |
| 2     | 65        | 20.7%   |
| 0     | 35        | 11.15%  |
| 3     | 15        | 4.78%   |
| 5     | 1         | 0.32%   |
| 4     | 1         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 230       | 51.22%  |
| Realtek Semiconductor             | 98        | 21.83%  |
| Broadcom                          | 25        | 5.57%   |
| Qualcomm Atheros                  | 19        | 4.23%   |
| Lenovo                            | 19        | 4.23%   |
| Dell                              | 5         | 1.11%   |
| Broadcom Limited                  | 5         | 1.11%   |
| ASIX Electronics                  | 5         | 1.11%   |
| Ralink Technology                 | 4         | 0.89%   |
| MediaTek                          | 4         | 0.89%   |
| Sierra Wireless                   | 3         | 0.67%   |
| Aquantia                          | 3         | 0.67%   |
| Ralink                            | 2         | 0.45%   |
| Marvell Technology Group          | 2         | 0.45%   |
| IBM                               | 2         | 0.45%   |
| Huawei Technologies               | 2         | 0.45%   |
| Ericsson Business Mobile Networks | 2         | 0.45%   |
| DisplayLink                       | 2         | 0.45%   |
| Xiaomi                            | 1         | 0.22%   |
| TP-Link                           | 1         | 0.22%   |
| Tehuti Networks                   | 1         | 0.22%   |
| Samsung Electronics               | 1         | 0.22%   |
| Qualcomm Atheros Communications   | 1         | 0.22%   |
| QLogic                            | 1         | 0.22%   |
| Prolific Technology               | 1         | 0.22%   |
| OPPO Electronics                  | 1         | 0.22%   |
| Microchip Technology              | 1         | 0.22%   |
| Micro Star International          | 1         | 0.22%   |
| Mellanox Technologies             | 1         | 0.22%   |
| Luminary Micro                    | 1         | 0.22%   |
| ICS Advent                        | 1         | 0.22%   |
| Emulex                            | 1         | 0.22%   |
| D-Link                            | 1         | 0.22%   |
| ASUSTek Computer                  | 1         | 0.22%   |
| Arduino SA                        | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 9.87%   |
| Intel Wireless 8265 / 8275                                        | 20        | 3.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 19        | 3.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 3.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 2.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 2.68%   |
| Intel Wi-Fi 6 AX200                                               | 15        | 2.51%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 13        | 2.17%   |
| Intel Ethernet Connection (6) I219-LM                             | 12        | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 2.01%   |
| Intel Wireless 8260                                               | 11        | 1.84%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 1.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 1.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 1.67%   |
| Intel I350 Gigabit Network Connection                             | 10        | 1.67%   |
| Intel Ethernet Controller I225-V                                  | 10        | 1.67%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 9         | 1.51%   |
| Intel Ethernet Connection (10) I219-LM                            | 9         | 1.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8         | 1.34%   |
| Intel I211 Gigabit Network Connection                             | 8         | 1.34%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 1.34%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 8         | 1.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.17%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 7         | 1.17%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1%      |
| Intel Ethernet Connection I217-LM                                 | 6         | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 6         | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 1%      |
| Intel 82574L Gigabit Network Connection                           | 6         | 1%      |
| Intel Wireless-AC 9260                                            | 5         | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.84%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 5         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.67%   |
| Intel Wireless 7265                                               | 4         | 0.67%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.67%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 166       | 72.17%  |
| Realtek Semiconductor             | 19        | 8.26%   |
| Qualcomm Atheros                  | 16        | 6.96%   |
| Broadcom                          | 7         | 3.04%   |
| Ralink Technology                 | 4         | 1.74%   |
| MediaTek                          | 4         | 1.74%   |
| Sierra Wireless                   | 3         | 1.3%    |
| Ralink                            | 2         | 0.87%   |
| Dell                              | 2         | 0.87%   |
| TP-Link                           | 1         | 0.43%   |
| Qualcomm Atheros Communications   | 1         | 0.43%   |
| Micro Star International          | 1         | 0.43%   |
| Ericsson Business Mobile Networks | 1         | 0.43%   |
| D-Link                            | 1         | 0.43%   |
| Broadcom Limited                  | 1         | 0.43%   |
| ASUSTek Computer                  | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                   | 20        | 8.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                            | 19        | 8.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                     | 17        | 7.39%   |
| Intel Wi-Fi 6 AX200                                          | 15        | 6.52%   |
| Intel Comet Lake PCH CNVi WiFi                               | 13        | 5.65%   |
| Intel Cannon Lake PCH CNVi WiFi                              | 12        | 5.22%   |
| Intel Wireless 8260                                          | 11        | 4.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                       | 8         | 3.48%   |
| Intel Wi-Fi 6 AX201                                          | 6         | 2.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                 | 6         | 2.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                             | 6         | 2.61%   |
| Intel Wireless-AC 9260                                       | 5         | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]             | 5         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter             | 4         | 1.74%   |
| Intel Wireless 7265                                          | 4         | 1.74%   |
| Intel Centrino Ultimate-N 6300                               | 4         | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter     | 3         | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter   | 3         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter   | 3         | 1.3%    |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter | 3         | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter              | 2         | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                   | 2         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter              | 2         | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter          | 2         | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                   | 2         | 0.87%   |
| Ralink RT5372 Wireless Adapter                               | 2         | 0.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter   | 2         | 0.87%   |
| Intel Wireless 7260                                          | 2         | 0.87%   |
| Intel Wireless 3165                                          | 2         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                              | 2         | 0.87%   |
| Intel Alder Lake-S PCH CNVi WiFi                             | 2         | 0.87%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                         | 2         | 0.87%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                       | 1         | 0.43%   |
| Sierra Wireless EM7455                                       | 1         | 0.43%   |
| Sierra Wireless EM7421                                       | 1         | 0.43%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem              | 1         | 0.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter     | 1         | 0.43%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                   | 1         | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter              | 1         | 0.43%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter              | 1         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 171       | 51.66%  |
| Realtek Semiconductor    | 89        | 26.89%  |
| Lenovo                   | 19        | 5.74%   |
| Broadcom                 | 19        | 5.74%   |
| ASIX Electronics         | 5         | 1.51%   |
| Qualcomm Atheros         | 4         | 1.21%   |
| Broadcom Limited         | 4         | 1.21%   |
| Dell                     | 3         | 0.91%   |
| Aquantia                 | 3         | 0.91%   |
| Marvell Technology Group | 2         | 0.6%    |
| IBM                      | 2         | 0.6%    |
| DisplayLink              | 2         | 0.6%    |
| Xiaomi                   | 1         | 0.3%    |
| Tehuti Networks          | 1         | 0.3%    |
| QLogic                   | 1         | 0.3%    |
| OPPO Electronics         | 1         | 0.3%    |
| Mellanox Technologies    | 1         | 0.3%    |
| ICS Advent               | 1         | 0.3%    |
| Huawei Technologies      | 1         | 0.3%    |
| Emulex                   | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 59        | 16.34%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 18        | 4.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 16        | 4.43%   |
| Intel Ethernet Connection (6) I219-LM                                          | 12        | 3.32%   |
| Intel Ethernet Connection (7) I219-LM                                          | 11        | 3.05%   |
| Intel Ethernet Connection (4) I219-LM                                          | 11        | 3.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 2.77%   |
| Intel I350 Gigabit Network Connection                                          | 10        | 2.77%   |
| Intel Ethernet Controller I225-V                                               | 10        | 2.77%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 9         | 2.49%   |
| Intel Ethernet Connection (10) I219-LM                                         | 9         | 2.49%   |
| Intel I211 Gigabit Network Connection                                          | 8         | 2.22%   |
| Intel Ethernet Connection (2) I219-LM                                          | 8         | 2.22%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 8         | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                              | 7         | 1.94%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 7         | 1.94%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 1.66%   |
| Intel Ethernet Connection (2) I219-V                                           | 6         | 1.66%   |
| Intel 82574L Gigabit Network Connection                                        | 6         | 1.66%   |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 1.39%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 5         | 1.39%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 1.11%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.11%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 1.11%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 1.11%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 1.11%   |
| Lenovo USB-C to LAN                                                            | 3         | 0.83%   |
| Lenovo ThinkPad Lan                                                            | 3         | 0.83%   |
| Intel Ethernet Controller I225-LM                                              | 3         | 0.83%   |
| Intel Ethernet Connection (5) I219-LM                                          | 3         | 0.83%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.83%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 0.83%   |
| Dell iDRAC Virtual NIC                                                         | 3         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.55%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.55%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.55%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.55%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 2         | 0.55%   |
| Intel Ethernet Controller X550                                                 | 2         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 274       | 54.91%  |
| WiFi     | 218       | 43.69%  |
| Modem    | 7         | 1.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 169       | 53.48%  |
| WiFi     | 146       | 46.2%   |
| Modem    | 1         | 0.32%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 173       | 57.1%   |
| 1     | 83        | 27.39%  |
| 3     | 17        | 5.61%   |
| 4     | 16        | 5.28%   |
| 6     | 7         | 2.31%   |
| 0     | 2         | 0.66%   |
| 132   | 1         | 0.33%   |
| 22    | 1         | 0.33%   |
| 12    | 1         | 0.33%   |
| 8     | 1         | 0.33%   |
| 5     | 1         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 263       | 86.51%  |
| Yes  | 41        | 13.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 133       | 72.68%  |
| Cambridge Silicon Radio         | 10        | 5.46%   |
| Broadcom                        | 9         | 4.92%   |
| Realtek Semiconductor           | 7         | 3.83%   |
| Qualcomm Atheros Communications | 6         | 3.28%   |
| IMC Networks                    | 5         | 2.73%   |
| ASUSTek Computer                | 5         | 2.73%   |
| Foxconn / Hon Hai               | 3         | 1.64%   |
| Ralink                          | 1         | 0.55%   |
| Micro Star International        | 1         | 0.55%   |
| MediaTek                        | 1         | 0.55%   |
| Integrated System Solution      | 1         | 0.55%   |
| Dell                            | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 41        | 22.4%   |
| Intel Bluetooth wireless interface                                                  | 30        | 16.39%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 27        | 14.75%  |
| Intel AX200 Bluetooth                                                               | 14        | 7.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 5.46%   |
| Intel AX210 Bluetooth                                                               | 7         | 3.83%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 2.73%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 2.73%   |
| Intel Bluetooth Device                                                              | 5         | 2.73%   |
| Realtek Bluetooth Radio                                                             | 4         | 2.19%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.19%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.09%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.09%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.09%   |
| ASUS BCM20702A0                                                                     | 2         | 1.09%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.55%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.55%   |
| MediaTek Wireless_Device                                                            | 1         | 0.55%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.55%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.55%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.55%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.55%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.55%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.55%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.55%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.55%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.55%   |
| ASUS Qualcomm Bluetooth 4.1                                                         | 1         | 0.55%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.55%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 230       | 52.51%  |
| Nvidia                                       | 80        | 18.26%  |
| AMD                                          | 42        | 9.59%   |
| Lenovo                                       | 17        | 3.88%   |
| Texas Instruments                            | 7         | 1.6%    |
| Realtek Semiconductor                        | 6         | 1.37%   |
| Plantronics                                  | 6         | 1.37%   |
| JMTek                                        | 5         | 1.14%   |
| GN Netcom                                    | 5         | 1.14%   |
| Creative Labs                                | 4         | 0.91%   |
| Logitech                                     | 3         | 0.68%   |
| Generalplus Technology                       | 3         | 0.68%   |
| Creative Technology                          | 3         | 0.68%   |
| C-Media Electronics                          | 3         | 0.68%   |
| ASUSTek Computer                             | 3         | 0.68%   |
| Corsair                                      | 2         | 0.46%   |
| Blue Microphones                             | 2         | 0.46%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.23%   |
| Tenx Technology                              | 1         | 0.23%   |
| SteelSeries ApS                              | 1         | 0.23%   |
| Sony                                         | 1         | 0.23%   |
| Sennheiser Communications                    | 1         | 0.23%   |
| RODE Microphones                             | 1         | 0.23%   |
| Micro Star International                     | 1         | 0.23%   |
| LG Electronics                               | 1         | 0.23%   |
| Hewlett-Packard                              | 1         | 0.23%   |
| Google                                       | 1         | 0.23%   |
| Giga-Byte Technology                         | 1         | 0.23%   |
| Focusrite-Novation                           | 1         | 0.23%   |
| Dynex                                        | 1         | 0.23%   |
| DSEA A/S                                     | 1         | 0.23%   |
| Dell                                         | 1         | 0.23%   |
| BEHRINGER International                      | 1         | 0.23%   |
| Astro Gaming                                 | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 32        | 6.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 23        | 4.83%   |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 4.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 20        | 4.2%    |
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 3.15%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 2.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 2.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13        | 2.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 11        | 2.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 2.31%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 2.1%    |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 9         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 1.89%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8         | 1.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 1.68%   |
| Nvidia GP104 High Definition Audio Controller                              | 7         | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 1.47%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7         | 1.47%   |
| Texas Instruments PCM2902 Audio Codec                                      | 6         | 1.26%   |
| Realtek Semiconductor USB Audio                                            | 6         | 1.26%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.26%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.26%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 1.26%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.05%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 1.05%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.05%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5         | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.05%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.05%   |
| Plantronics BT600                                                          | 4         | 0.84%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.84%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 4         | 0.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 0.84%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 0.84%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 0.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 42        | 26.25%  |
| Samsung Electronics | 42        | 26.25%  |
| Micron Technology   | 18        | 11.25%  |
| Crucial             | 12        | 7.5%    |
| Kingston            | 11        | 6.88%   |
| Corsair             | 7         | 4.38%   |
| Unknown             | 6         | 3.75%   |
| G.Skill             | 4         | 2.5%    |
| Hewlett-Packard     | 3         | 1.88%   |
| Elpida              | 3         | 1.88%   |
| Transcend           | 2         | 1.25%   |
| Smart               | 2         | 1.25%   |
| GOODRAM             | 2         | 1.25%   |
| Unknown (0x0B5E)    | 1         | 0.63%   |
| Unknown (0x0205)    | 1         | 0.63%   |
| Team                | 1         | 0.63%   |
| Patriot             | 1         | 0.63%   |
| Innodisk            | 1         | 0.63%   |
| Unknown             | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s            | 5         | 2.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 3         | 1.75%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8192MB DIMM DDR4 2666MT/s         | 3         | 1.75%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s           | 3         | 1.75%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 3         | 1.75%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 3         | 1.75%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                    | 2         | 1.17%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 2         | 1.17%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 1.17%   |
| SK hynix RAM HMA82GR7MFR8N-UH 16GB DIMM DDR4 2400MT/s           | 2         | 1.17%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 1.17%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 1.17%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 1.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 1.17%   |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM DDR3 1600MT/s            | 2         | 1.17%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s            | 2         | 1.17%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2400MT/s            | 2         | 1.17%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s         | 2         | 1.17%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s            | 2         | 1.17%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s           | 2         | 1.17%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s          | 2         | 1.17%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s           | 2         | 1.17%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 0.58%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.58%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                       | 1         | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 0.58%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 0.58%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s              | 1         | 0.58%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s                | 1         | 0.58%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s           | 1         | 0.58%   |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s             | 1         | 0.58%   |
| Smart RAM SF564128CJ8NWMNSEG 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.58%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 0.58%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s           | 1         | 0.58%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s            | 1         | 0.58%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 0.58%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s         | 1         | 0.58%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 1         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s         | 1         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 89        | 64.49%  |
| DDR3    | 33        | 23.91%  |
| SDRAM   | 3         | 2.17%   |
| LPDDR4  | 3         | 2.17%   |
| DRAM    | 3         | 2.17%   |
| LPDDR3  | 2         | 1.45%   |
| DDR5    | 2         | 1.45%   |
| LPDDR5  | 1         | 0.72%   |
| DDR2    | 1         | 0.72%   |
| Unknown | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 71        | 52.21%  |
| SODIMM       | 58        | 42.65%  |
| Row Of Chips | 3         | 2.21%   |
| RIMM         | 2         | 1.47%   |
| Chip         | 2         | 1.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 55        | 37.41%  |
| 16384 | 43        | 29.25%  |
| 4096  | 25        | 17.01%  |
| 32768 | 16        | 10.88%  |
| 2048  | 4         | 2.72%   |
| 65536 | 3         | 2.04%   |
| 1024  | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 25        | 17.12%  |
| 2400    | 24        | 16.44%  |
| 1600    | 24        | 16.44%  |
| 2667    | 18        | 12.33%  |
| 2133    | 12        | 8.22%   |
| 3600    | 9         | 6.16%   |
| 1333    | 8         | 5.48%   |
| 2666    | 6         | 4.11%   |
| 2933    | 4         | 2.74%   |
| 6400    | 2         | 1.37%   |
| 3266    | 2         | 1.37%   |
| 1867    | 2         | 1.37%   |
| 1866    | 2         | 1.37%   |
| 4800    | 1         | 0.68%   |
| 3933    | 1         | 0.68%   |
| 2472    | 1         | 0.68%   |
| 2048    | 1         | 0.68%   |
| 1334    | 1         | 0.68%   |
| 1066    | 1         | 0.68%   |
| 800     | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 4         | 36.36%  |
| Seiko Epson        | 3         | 27.27%  |
| Canon              | 3         | 27.27%  |
| Brother Industries | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series         | 1         | 9.09%   |
| Seiko Epson WF-3520 Series         | 1         | 9.09%   |
| Seiko Epson L3210 Series           | 1         | 9.09%   |
| HP LaserJet Professional P 1102w   | 1         | 9.09%   |
| HP ENVY 4500 series                | 1         | 9.09%   |
| HP DeskJet 3700 series             | 1         | 9.09%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 9.09%   |
| Canon PIXMA MG2500 Series          | 1         | 9.09%   |
| Canon E560 series                  | 1         | 9.09%   |
| Canon CanoScan LiDE 300            | 1         | 9.09%   |
| Brother DCP-1610W                  | 1         | 9.09%   |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 50        | 26.18%  |
| IMC Networks                           | 27        | 14.14%  |
| Realtek Semiconductor                  | 15        | 7.85%   |
| Bison Electronics                      | 15        | 7.85%   |
| Microdia                               | 13        | 6.81%   |
| Logitech                               | 11        | 5.76%   |
| Sunplus Innovation Technology          | 9         | 4.71%   |
| Lite-On Technology                     | 5         | 2.62%   |
| Suyin                                  | 4         | 2.09%   |
| Samsung Electronics                    | 4         | 2.09%   |
| Hopewin Electronic Material            | 4         | 2.09%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.09%   |
| Microsoft                              | 3         | 1.57%   |
| Luxvisions Innotech Limited            | 3         | 1.57%   |
| Generalplus Technology                 | 3         | 1.57%   |
| Syntek                                 | 2         | 1.05%   |
| Ruision                                | 2         | 1.05%   |
| Quanta                                 | 2         | 1.05%   |
| Apple                                  | 2         | 1.05%   |
| Acer                                   | 2         | 1.05%   |
| vivo                                   | 1         | 0.52%   |
| Sonix Technology                       | 1         | 0.52%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.52%   |
| Remo Tech                              | 1         | 0.52%   |
| Owon                                   | 1         | 0.52%   |
| LG Electronics                         | 1         | 0.52%   |
| Lenovo                                 | 1         | 0.52%   |
| KYE Systems (Mouse Systems)            | 1         | 0.52%   |
| Jieli Technology                       | 1         | 0.52%   |
| Creative Technology                    | 1         | 0.52%   |
| ARC International                      | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 24        | 12.37%  |
| IMC Networks Integrated Camera                    | 22        | 11.34%  |
| Realtek Integrated_Webcam_HD                      | 9         | 4.64%   |
| Bison Integrated Camera                           | 8         | 4.12%   |
| Sunplus Integrated_Webcam_HD                      | 5         | 2.58%   |
| Microdia Integrated_Webcam_HD                     | 5         | 2.58%   |
| Chicony Integrated Camera (1280x720@30)           | 5         | 2.58%   |
| Chicony HP HD Camera                              | 5         | 2.58%   |
| Bison SunplusIT Integrated Camera                 | 5         | 2.58%   |
| Samsung Galaxy series, misc. (MTP mode)           | 4         | 2.06%   |
| Logitech HD Pro Webcam C920                       | 4         | 2.06%   |
| Lite-On Integrated Camera                         | 4         | 2.06%   |
| Hopewin Electronic Material FULL HD 1080P Webcam  | 4         | 2.06%   |
| Chicony ThinkPad T490 Webcam                      | 4         | 2.06%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 1.55%   |
| Suyin Integrated_Webcam_HD                        | 2         | 1.03%   |
| Ruision UVC Camera                                | 2         | 1.03%   |
| Microdia Webcam                                   | 2         | 1.03%   |
| Microdia Integrated Webcam                        | 2         | 1.03%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 2         | 1.03%   |
| Generalplus GENERAL WEBCAM                        | 2         | 1.03%   |
| Chicony Integrated Camera [ThinkPad]              | 2         | 1.03%   |
| Chicony HP HD Webcam [Fixed]                      | 2         | 1.03%   |
| Bison Integrated IR Camera                        | 2         | 1.03%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                | 2         | 1.03%   |
| vivo V2036                                        | 1         | 0.52%   |
| Syntek Lenovo EasyCamera                          | 1         | 0.52%   |
| Syntek Integrated Camera                          | 1         | 0.52%   |
| Suyin RGBIR Camera                                | 1         | 0.52%   |
| Suyin HP Truevision HD                            | 1         | 0.52%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 1         | 0.52%   |
| Sunplus Integrated Webcam                         | 1         | 0.52%   |
| Sunplus HP HD Webcam [Fixed]                      | 1         | 0.52%   |
| Sunplus FHD Camera Microphone                     | 1         | 0.52%   |
| Sonix USB2.0 HD UVC WebCam                        | 1         | 0.52%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera   | 1         | 0.52%   |
| Remo Tech OBSBOT Tiny 4K                          | 1         | 0.52%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 0.52%   |
| Realtek USB Camera                                | 1         | 0.52%   |
| Realtek NexiGo N960E FHD Webcam                   | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 39        | 59.09%  |
| Validity Sensors           | 18        | 27.27%  |
| Shenzhen Goodix Technology | 5         | 7.58%   |
| Upek                       | 2         | 3.03%   |
| Samsung Electronics        | 1         | 1.52%   |
| Elan Microelectronics      | 1         | 1.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 40.91%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 10.61%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 6.06%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.55%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 4.55%   |
| Validity Sensors VFS491                                                    | 2         | 3.03%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.03%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.03%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.03%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.03%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.52%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.52%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.52%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.52%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.52%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.52%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.52%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.52%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 14        | 50%     |
| Alcor Micro           | 6         | 21.43%  |
| SCM Microsystems      | 2         | 7.14%   |
| Lenovo                | 2         | 7.14%   |
| Yubico.com            | 1         | 3.57%   |
| Upek                  | 1         | 3.57%   |
| OmniKey               | 1         | 3.57%   |
| Gemalto (was Gemplus) | 1         | 3.57%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                              | 6         | 21.43%  |
| Alcor Micro AU9540 Smartcard Reader                        | 6         | 21.43%  |
| Broadcom 58200                                             | 5         | 17.86%  |
| Broadcom BCM5880 Secure Applications Processor             | 3         | 10.71%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 2         | 7.14%   |
| Lenovo Integrated Smart Card Reader                        | 2         | 7.14%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 3.57%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 3.57%   |
| OmniKey CardMan 3121 (HID Technologies)                    | 1         | 3.57%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 1         | 3.57%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 154       | 50.16%  |
| 1     | 101       | 32.9%   |
| 2     | 33        | 10.75%  |
| 3     | 12        | 3.91%   |
| 5     | 5         | 1.63%   |
| 4     | 2         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 66        | 30.14%  |
| Graphics card            | 37        | 16.89%  |
| Unassigned class         | 26        | 11.87%  |
| Communication controller | 25        | 11.42%  |
| Net/wireless             | 16        | 7.31%   |
| Chipcard                 | 16        | 7.31%   |
| Multimedia controller    | 7         | 3.2%    |
| Card reader              | 7         | 3.2%    |
| Net/ethernet             | 6         | 2.74%   |
| Bluetooth                | 4         | 1.83%   |
| Storage/ide              | 2         | 0.91%   |
| Storage                  | 2         | 0.91%   |
| Camera                   | 2         | 0.91%   |
| Storage/raid             | 1         | 0.46%   |
| Sound                    | 1         | 0.46%   |
| Network                  | 1         | 0.46%   |

