Linux in Malaysia - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Malaysia.

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

Total: 342

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte   | H410M S2 V2                 | [a1fbe8858b](https://linux-hardware.org/?probe=a1fbe8858b) | Apr 26, 2024 |
| Dell       | 04Y8V0 A02                  | [069de8abaf](https://linux-hardware.org/?probe=069de8abaf) | Apr 24, 2024 |
| Gigabyte   | X570 UD                     | [5240449916](https://linux-hardware.org/?probe=5240449916) | Apr 18, 2024 |
| ASRock     | B550 Pro4                   | [f906fa4f7c](https://linux-hardware.org/?probe=f906fa4f7c) | Apr 18, 2024 |
| Unknown    | Unknown                     | [9be7b4bfdc](https://linux-hardware.org/?probe=9be7b4bfdc) | Apr 17, 2024 |
| ECS        | G31T-M7                     | [fa7e63c25c](https://linux-hardware.org/?probe=fa7e63c25c) | Apr 17, 2024 |
| Dell       | 06D7TR A02                  | [8b107755d6](https://linux-hardware.org/?probe=8b107755d6) | Apr 17, 2024 |
| Gigabyte   | B85M-D3H                    | [0428aaf36d](https://linux-hardware.org/?probe=0428aaf36d) | Apr 15, 2024 |
| ASUSTek    | CROSSHAIR VI HERO           | [8f232e4e6c](https://linux-hardware.org/?probe=8f232e4e6c) | Apr 11, 2024 |
| HP         | 18E7                        | [467ac72efe](https://linux-hardware.org/?probe=467ac72efe) | Apr 07, 2024 |
| ECS        | G31T-M7                     | [ce42a0a99a](https://linux-hardware.org/?probe=ce42a0a99a) | Apr 01, 2024 |
| MSI        | MS-7388                     | [7ece0030bf](https://linux-hardware.org/?probe=7ece0030bf) | Mar 30, 2024 |
| Dell       | 04Y8V0 A02                  | [f6d71cfa9f](https://linux-hardware.org/?probe=f6d71cfa9f) | Mar 30, 2024 |
| Gigabyte   | X570 UD                     | [539238d399](https://linux-hardware.org/?probe=539238d399) | Mar 29, 2024 |
| ASRock     | B550 Pro4                   | [9144eb7fe4](https://linux-hardware.org/?probe=9144eb7fe4) | Mar 29, 2024 |
| Gigabyte   | B550 AORUS PRO V2           | [d84d712a77](https://linux-hardware.org/?probe=d84d712a77) | Mar 29, 2024 |
| Acer       | Aspire TC-1660 V:1.1        | [c0dfdce31b](https://linux-hardware.org/?probe=c0dfdce31b) | Mar 21, 2024 |
| MSI        | A520M-A PRO                 | [8ff1245537](https://linux-hardware.org/?probe=8ff1245537) | Mar 19, 2024 |
| ASUSTek    | TUF Gaming B550M-PLUS       | [a19c2ddfef](https://linux-hardware.org/?probe=a19c2ddfef) | Mar 14, 2024 |
| Dell       | 06D7TR A02                  | [e92342cc9d](https://linux-hardware.org/?probe=e92342cc9d) | Mar 06, 2024 |
| Gigabyte   | H110M-DS2-CF                | [363dfceefd](https://linux-hardware.org/?probe=363dfceefd) | Mar 06, 2024 |
| MSI        | X470 GAMING PLUS MAX        | [d746e0ee2c](https://linux-hardware.org/?probe=d746e0ee2c) | Mar 05, 2024 |
| MSI        | Z97 GAMING 7                | [be7cf8b3fc](https://linux-hardware.org/?probe=be7cf8b3fc) | Mar 01, 2024 |
| MSI        | MS-7388                     | [2429edf24b](https://linux-hardware.org/?probe=2429edf24b) | Feb 24, 2024 |
| MSI        | A520M-A PRO                 | [4958d63fb4](https://linux-hardware.org/?probe=4958d63fb4) | Feb 20, 2024 |
| ASUSTek    | PRIME B760M-A WIFI D4       | [68ae08681c](https://linux-hardware.org/?probe=68ae08681c) | Feb 18, 2024 |
| Unknown    | Unknown                     | [89d1e82e1f](https://linux-hardware.org/?probe=89d1e82e1f) | Feb 16, 2024 |
| ASUSTek    | TUF B450M-PLUS GAMING       | [1bbac9a561](https://linux-hardware.org/?probe=1bbac9a561) | Feb 06, 2024 |
| ASUSTek    | TUF B450M-PLUS GAMING       | [c737ef78e9](https://linux-hardware.org/?probe=c737ef78e9) | Jan 30, 2024 |
| AZW        | MINI S 10                   | [a209f8ae32](https://linux-hardware.org/?probe=a209f8ae32) | Jan 30, 2024 |
| ASRock     | X370 Professional Gaming    | [ddff1295a4](https://linux-hardware.org/?probe=ddff1295a4) | Jan 30, 2024 |
| Dell       | 0W0CHX A00                  | [e57642d0d4](https://linux-hardware.org/?probe=e57642d0d4) | Jan 28, 2024 |
| Machenike  | ARB19                       | [3002916884](https://linux-hardware.org/?probe=3002916884) | Jan 28, 2024 |
| Machenike  | ARB19                       | [4f289b9a02](https://linux-hardware.org/?probe=4f289b9a02) | Jan 28, 2024 |
| Dell       | 0427JK A00                  | [7f8cfea83b](https://linux-hardware.org/?probe=7f8cfea83b) | Jan 20, 2024 |
| MSI        | MS-7388                     | [e151be731a](https://linux-hardware.org/?probe=e151be731a) | Jan 20, 2024 |
| Dell       | 04Y8V0 A02                  | [c7ac75fb19](https://linux-hardware.org/?probe=c7ac75fb19) | Jan 20, 2024 |
| Gigabyte   | A520M K V2                  | [65409c0132](https://linux-hardware.org/?probe=65409c0132) | Jan 19, 2024 |
| HP         | 2B2C                        | [6e5219edb5](https://linux-hardware.org/?probe=6e5219edb5) | Jan 11, 2024 |
| HP         | 2B2C                        | [5ac47f9e43](https://linux-hardware.org/?probe=5ac47f9e43) | Jan 04, 2024 |
| MSI        | MS-7388                     | [efab378a60](https://linux-hardware.org/?probe=efab378a60) | Dec 24, 2023 |
| Dell       | 04Y8V0 A02                  | [1c3e40ac13](https://linux-hardware.org/?probe=1c3e40ac13) | Dec 23, 2023 |
| MSI        | MS-7388                     | [5027d4b8ed](https://linux-hardware.org/?probe=5027d4b8ed) | Dec 23, 2023 |
| HP         | 2129                        | [3a95965680](https://linux-hardware.org/?probe=3a95965680) | Dec 13, 2023 |
| Intel      | H61                         | [97a16fcd1b](https://linux-hardware.org/?probe=97a16fcd1b) | Nov 27, 2023 |
| Gigabyte   | H410M S2 V2                 | [c6955988fb](https://linux-hardware.org/?probe=c6955988fb) | Nov 25, 2023 |
| Lenovo     | 30C7 SDK0K13468 WIN 3273... | [27b54b9945](https://linux-hardware.org/?probe=27b54b9945) | Nov 19, 2023 |
| ASRock     | B550 Pro4                   | [1063cc1572](https://linux-hardware.org/?probe=1063cc1572) | Nov 15, 2023 |
| ASRock     | B550 Pro4                   | [8ee2dc1361](https://linux-hardware.org/?probe=8ee2dc1361) | Nov 15, 2023 |
| ASUSTek    | ROG STRIX X670E-E GAMING... | [6ff4b2ddd5](https://linux-hardware.org/?probe=6ff4b2ddd5) | Nov 15, 2023 |
| Gigabyte   | B550 AORUS PRO V2           | [e8e0ef7485](https://linux-hardware.org/?probe=e8e0ef7485) | Nov 15, 2023 |
| Unknown    | Unknown                     | [49baeb0911](https://linux-hardware.org/?probe=49baeb0911) | Oct 25, 2023 |
| Unknown    | Unknown                     | [03fbe0b1a4](https://linux-hardware.org/?probe=03fbe0b1a4) | Oct 24, 2023 |
| ECS        | G31T-M7                     | [297db99cc3](https://linux-hardware.org/?probe=297db99cc3) | Oct 20, 2023 |
| ASRock     | B550 Pro4                   | [0d55c2a6af](https://linux-hardware.org/?probe=0d55c2a6af) | Oct 20, 2023 |
| Gigabyte   | X670 AORUS ELITE AX         | [67365133d9](https://linux-hardware.org/?probe=67365133d9) | Oct 17, 2023 |
| ASUSTek    | PRIME B560M-K               | [954eecec42](https://linux-hardware.org/?probe=954eecec42) | Oct 09, 2023 |
| ASUSTek    | ROG STRIX X670E-E GAMING... | [5295ac09d9](https://linux-hardware.org/?probe=5295ac09d9) | Oct 06, 2023 |
| ASUSTek    | PRIME B560M-K               | [ee02fff8df](https://linux-hardware.org/?probe=ee02fff8df) | Sep 28, 2023 |
| Gigabyte   | B550 AORUS PRO V2           | [273b056209](https://linux-hardware.org/?probe=273b056209) | Sep 25, 2023 |
| MSI        | MS-7388                     | [f5ee235af0](https://linux-hardware.org/?probe=f5ee235af0) | Sep 23, 2023 |
| ASRock     | B550 Pro4                   | [af2217289d](https://linux-hardware.org/?probe=af2217289d) | Sep 19, 2023 |
| ASUSTek    | M5A78L-M LX V2              | [92b5ca6639](https://linux-hardware.org/?probe=92b5ca6639) | Sep 03, 2023 |
| ASUSTek    | PRIME B760M-A WIFI D4       | [f2eccf0aa8](https://linux-hardware.org/?probe=f2eccf0aa8) | Sep 02, 2023 |
| ASRock     | A620M-HDV/M.2+              | [674da4ba95](https://linux-hardware.org/?probe=674da4ba95) | Sep 02, 2023 |
| Gigabyte   | B85M-D3H                    | [4660dc9f99](https://linux-hardware.org/?probe=4660dc9f99) | Sep 01, 2023 |
| ECS        | G31T-M7                     | [f095887170](https://linux-hardware.org/?probe=f095887170) | Aug 28, 2023 |
| MSI        | MS-7388                     | [42530086f2](https://linux-hardware.org/?probe=42530086f2) | Aug 27, 2023 |
| Dell       | 04Y8V0 A02                  | [629b07f8bc](https://linux-hardware.org/?probe=629b07f8bc) | Aug 27, 2023 |
| MSI        | MS-7388                     | [5c1e4b0c2b](https://linux-hardware.org/?probe=5c1e4b0c2b) | Aug 25, 2023 |
| Intel      | X99                         | [785fcd2a1d](https://linux-hardware.org/?probe=785fcd2a1d) | Aug 21, 2023 |
| Intel      | X99                         | [b54ecfbbc3](https://linux-hardware.org/?probe=b54ecfbbc3) | Aug 21, 2023 |
| MSI        | PRO B760M-A WIFI DDR4       | [109c0dbb17](https://linux-hardware.org/?probe=109c0dbb17) | Aug 20, 2023 |
| Acer       | Veriton M2611G v1.0         | [1527c20b46](https://linux-hardware.org/?probe=1527c20b46) | Aug 19, 2023 |
| ECS        | G31T-M7                     | [2d35b5e140](https://linux-hardware.org/?probe=2d35b5e140) | Aug 14, 2023 |
| Gigabyte   | H410M S2 V2                 | [d4c5a12d06](https://linux-hardware.org/?probe=d4c5a12d06) | Aug 10, 2023 |
| Dell       | 0WR7PY A03                  | [becf318878](https://linux-hardware.org/?probe=becf318878) | Aug 07, 2023 |
| Gigabyte   | G31M-S2C                    | [9cda5ca576](https://linux-hardware.org/?probe=9cda5ca576) | Aug 05, 2023 |
| ASUSTek    | P5G41T-M LX3                | [f82f03bf86](https://linux-hardware.org/?probe=f82f03bf86) | Aug 04, 2023 |
| ASUSTek    | P5G41T-M LX3                | [356e8a0637](https://linux-hardware.org/?probe=356e8a0637) | Jul 28, 2023 |
| Gigabyte   | B450M S2H                   | [f2f1f87d0c](https://linux-hardware.org/?probe=f2f1f87d0c) | Jul 23, 2023 |
| Lenovo     | MAHOBAY NOK                 | [9b6d9b3e96](https://linux-hardware.org/?probe=9b6d9b3e96) | Jul 21, 2023 |
| MSI        | PRO B660M-E DDR4            | [62aa29ec8e](https://linux-hardware.org/?probe=62aa29ec8e) | Jul 19, 2023 |
| MSI        | Z97 GAMING 7                | [28c6cd48b8](https://linux-hardware.org/?probe=28c6cd48b8) | Jul 16, 2023 |
| MSI        | Z97 GAMING 7                | [9ef499d31f](https://linux-hardware.org/?probe=9ef499d31f) | Jul 16, 2023 |
| Acer       | Veriton X6610G              | [e1189e3406](https://linux-hardware.org/?probe=e1189e3406) | Jul 13, 2023 |
| ASRockRack | ROMED8QM-2T                 | [a4fe5ea9c9](https://linux-hardware.org/?probe=a4fe5ea9c9) | Jul 13, 2023 |
| ASUSTek    | P5G41T-M LX3                | [8287d6e8e3](https://linux-hardware.org/?probe=8287d6e8e3) | Jul 04, 2023 |
| Gigabyte   | A320M-S2H V2-CF             | [18b6484d81](https://linux-hardware.org/?probe=18b6484d81) | Jul 01, 2023 |
| MSI        | A320M PRO-VH                | [1a84c61bd4](https://linux-hardware.org/?probe=1a84c61bd4) | Jun 27, 2023 |
| HP         | 2B2C                        | [a8ec805431](https://linux-hardware.org/?probe=a8ec805431) | Jun 27, 2023 |
| Gigabyte   | B550 AORUS PRO V2           | [1143a7eebc](https://linux-hardware.org/?probe=1143a7eebc) | Jun 27, 2023 |
| HP         | 2B2C                        | [3b82186362](https://linux-hardware.org/?probe=3b82186362) | Jun 26, 2023 |
| Intel      | DH61WW AAG23116-204         | [4269ca2c0b](https://linux-hardware.org/?probe=4269ca2c0b) | Jun 25, 2023 |
| HP         | 2B2C                        | [4303d28839](https://linux-hardware.org/?probe=4303d28839) | Jun 22, 2023 |
| Gigabyte   | A320M-S2H V2-CF             | [1623fa6455](https://linux-hardware.org/?probe=1623fa6455) | Jun 11, 2023 |
| MSI        | MS-7388                     | [6d3a406400](https://linux-hardware.org/?probe=6d3a406400) | Jun 10, 2023 |
| MSI        | MS-7388                     | [fc12ac6b90](https://linux-hardware.org/?probe=fc12ac6b90) | Jun 02, 2023 |
| ASUSTek    | H81M-K                      | [f65eac842b](https://linux-hardware.org/?probe=f65eac842b) | May 23, 2023 |
| Gigabyte   | H410M S2 V2                 | [9d2439e8d7](https://linux-hardware.org/?probe=9d2439e8d7) | May 18, 2023 |
| Gigabyte   | B450 AORUS ELITE            | [7957c81218](https://linux-hardware.org/?probe=7957c81218) | May 17, 2023 |
| Gigabyte   | B450 AORUS ELITE            | [1aedc7da48](https://linux-hardware.org/?probe=1aedc7da48) | May 17, 2023 |
| MSI        | MS-7388                     | [948e1d2358](https://linux-hardware.org/?probe=948e1d2358) | May 03, 2023 |
| MSI        | MS-7388                     | [ec819aca80](https://linux-hardware.org/?probe=ec819aca80) | May 01, 2023 |
| Gigabyte   | Z77M-D3H                    | [6da1ddcef5](https://linux-hardware.org/?probe=6da1ddcef5) | May 01, 2023 |
| Gigabyte   | Z77M-D3H                    | [a3d2b3dcd3](https://linux-hardware.org/?probe=a3d2b3dcd3) | Apr 30, 2023 |
| Gigabyte   | Z77M-D3H                    | [915147a191](https://linux-hardware.org/?probe=915147a191) | Apr 25, 2023 |
| Gigabyte   | Z77M-D3H                    | [92a968e58d](https://linux-hardware.org/?probe=92a968e58d) | Apr 25, 2023 |
| Dell       | 0F373D A00                  | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Acer       | Aspire XC-710 V:1.1         | [a09ea158cc](https://linux-hardware.org/?probe=a09ea158cc) | Apr 20, 2023 |
| ASRock     | B550 Pro4                   | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| MSI        | MS-7388                     | [4efa2b04da](https://linux-hardware.org/?probe=4efa2b04da) | Apr 14, 2023 |
| Gigabyte   | B550 AORUS PRO V2           | [f4cbe67033](https://linux-hardware.org/?probe=f4cbe67033) | Apr 14, 2023 |
| Gigabyte   | Z77M-D3H                    | [ffdcd55e2e](https://linux-hardware.org/?probe=ffdcd55e2e) | Apr 13, 2023 |
| MSI        | MS-7388                     | [d7f892b3e2](https://linux-hardware.org/?probe=d7f892b3e2) | Apr 12, 2023 |
| Gigabyte   | Z77M-D3H                    | [d76bd92923](https://linux-hardware.org/?probe=d76bd92923) | Apr 07, 2023 |
| MSI        | B450M-A PRO MAX             | [54789b15f3](https://linux-hardware.org/?probe=54789b15f3) | Mar 29, 2023 |
| ASUSTek    | Pro WS WRX80E-SAGE SE WI... | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| Biostar    | G41D3+                      | [ebb9a17568](https://linux-hardware.org/?probe=ebb9a17568) | Mar 23, 2023 |
| Gigabyte   | GA-890GPA-UD3H              | [b54b641b36](https://linux-hardware.org/?probe=b54b641b36) | Mar 14, 2023 |
| ASUSTek    | Pro WS WRX80E-SAGE SE WI... | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek    | Pro WS WRX80E-SAGE SE WI... | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte   | X570 UD                     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| Dell       | 084J0R A00                  | [dcde5e81ed](https://linux-hardware.org/?probe=dcde5e81ed) | Mar 04, 2023 |
| Intel      | DH61WW AAG23116-204         | [c9b32e7136](https://linux-hardware.org/?probe=c9b32e7136) | Mar 03, 2023 |
| Unknown    | J3160-4L                    | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| MSI        | A320M GRENADE               | [1a5ffd0fc4](https://linux-hardware.org/?probe=1a5ffd0fc4) | Mar 01, 2023 |
| Gigabyte   | H370 AORUS GAMING 3-CF      | [59d082bd5f](https://linux-hardware.org/?probe=59d082bd5f) | Feb 26, 2023 |
| Gigabyte   | B550 AORUS PRO V2           | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRock     | B550 Pro4                   | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| ASUSTek    | B85M-G                      | [c803a7f9e8](https://linux-hardware.org/?probe=c803a7f9e8) | Feb 15, 2023 |
| ASUSTek    | B85M-G                      | [3a660768c0](https://linux-hardware.org/?probe=3a660768c0) | Feb 15, 2023 |
| Dell       | 0MGK50 A02                  | [43bd1ca5e1](https://linux-hardware.org/?probe=43bd1ca5e1) | Feb 15, 2023 |
| Gigabyte   | B550 AORUS PRO V2           | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek    | Pro WS WRX80E-SAGE SE WI... | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASUSTek    | Pro WS WRX80E-SAGE SE WI... | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| Gigabyte   | X570 UD                     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| MSI        | 970A-G46                    | [6012e644eb](https://linux-hardware.org/?probe=6012e644eb) | Feb 13, 2023 |
| HP         | 18E4                        | [55972b87dd](https://linux-hardware.org/?probe=55972b87dd) | Feb 11, 2023 |
| Gigabyte   | B560M AORUS ELITE           | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| Gigabyte   | B85M-D3H                    | [903e8715e4](https://linux-hardware.org/?probe=903e8715e4) | Feb 03, 2023 |
| Gigabyte   | B85M-D3H                    | [6013489300](https://linux-hardware.org/?probe=6013489300) | Feb 03, 2023 |
| Gigabyte   | GA-890GPA-UD3H              | [e660f922a4](https://linux-hardware.org/?probe=e660f922a4) | Jan 27, 2023 |
| ASUSTek    | H81M-K                      | [cb932accdb](https://linux-hardware.org/?probe=cb932accdb) | Jan 24, 2023 |
| HP         | 2B2C                        | [1a74d92aaf](https://linux-hardware.org/?probe=1a74d92aaf) | Jan 08, 2023 |
| ASRock     | A320M-DVS R4.0              | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| Gigabyte   | B85M-D3H                    | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
| HP         | 2B2C                        | [91862a2497](https://linux-hardware.org/?probe=91862a2497) | Nov 19, 2022 |
| HP         | 2B2C                        | [2eb8311f18](https://linux-hardware.org/?probe=2eb8311f18) | Nov 16, 2022 |
| MSI        | MPG X570 GAMING EDGE WIF... | [1fef4a8aa5](https://linux-hardware.org/?probe=1fef4a8aa5) | Nov 13, 2022 |
| MSI        | B450M-A PRO MAX             | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| Gigabyte   | X570 UD                     | [29641e8b7c](https://linux-hardware.org/?probe=29641e8b7c) | Nov 09, 2022 |
| ASUSTek    | P7H55-M LE                  | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| ASUSTek    | P7H55-M LE                  | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Seco       | C40 C                       | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| Gigabyte   | AX370M-Gaming 3-CF          | [abe170cf19](https://linux-hardware.org/?probe=abe170cf19) | Oct 27, 2022 |
| HP         | 2B2C                        | [df8a8ec9bc](https://linux-hardware.org/?probe=df8a8ec9bc) | Sep 29, 2022 |
| HP         | 18E7                        | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| ASUSTek    | ProArt Z690-CREATOR WIFI    | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| Intel      | DH61WW AAG23116-204         | [3310a4c592](https://linux-hardware.org/?probe=3310a4c592) | Sep 02, 2022 |
| Vorke      | V1 Plus                     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI        | B450M MORTAR MAX            | [25e7e97937](https://linux-hardware.org/?probe=25e7e97937) | Aug 29, 2022 |
| MSI        | B450M MORTAR MAX            | [9b0e2c480f](https://linux-hardware.org/?probe=9b0e2c480f) | Aug 28, 2022 |
| Dell       | 0PU052                      | [2bffd37724](https://linux-hardware.org/?probe=2bffd37724) | Aug 24, 2022 |
| ASUSTek    | P5G41T-M LX3                | [0aefa0613d](https://linux-hardware.org/?probe=0aefa0613d) | Aug 15, 2022 |
| ASUSTek    | P5G41T-M LX3                | [d000ce4d8c](https://linux-hardware.org/?probe=d000ce4d8c) | Aug 15, 2022 |
| Intel      | DH61WW AAG23116-204         | [30715e2f04](https://linux-hardware.org/?probe=30715e2f04) | Aug 01, 2022 |
| Lenovo     | ThinkCentre M58 7359DHJ     | [46c2c1db62](https://linux-hardware.org/?probe=46c2c1db62) | Jul 26, 2022 |
| ONDA       | H110-MINI V3.00 Ver:3.00    | [62b2a7897b](https://linux-hardware.org/?probe=62b2a7897b) | Jul 24, 2022 |
| Gigabyte   | Z390 GAMING X-CF            | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| Gigabyte   | X570 AORUS MASTER           | [aa2a721361](https://linux-hardware.org/?probe=aa2a721361) | Jul 15, 2022 |
| Gigabyte   | B450M S2H                   | [0287348f80](https://linux-hardware.org/?probe=0287348f80) | Jul 12, 2022 |
| Intel      | MAHOBAY                     | [39c0379cee](https://linux-hardware.org/?probe=39c0379cee) | Jul 04, 2022 |
| Gigabyte   | H470 HD3                    | [4857a7b7bf](https://linux-hardware.org/?probe=4857a7b7bf) | Jun 30, 2022 |
| ASUSTek    | ROG Maximus Z690 HERO       | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI        | MAG B660M MORTAR WIFI DD... | [c5a5b25674](https://linux-hardware.org/?probe=c5a5b25674) | Jun 28, 2022 |
| Intel      | MAHOBAY                     | [c292904665](https://linux-hardware.org/?probe=c292904665) | Jun 24, 2022 |
| ASUSTek    | CROSSHAIR VI HERO           | [2a4d1c8a0b](https://linux-hardware.org/?probe=2a4d1c8a0b) | Jun 19, 2022 |
| Lenovo     | 102F SDK0E50510 WIN 2625... | [35c05116d1](https://linux-hardware.org/?probe=35c05116d1) | Jun 16, 2022 |
| ASUSTek    | TUF Gaming B660M-PLUS WI... | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| ASUSTek    | TUF Gaming B660M-PLUS WI... | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| ASUSTek    | TUF Gaming B660M-PLUS WI... | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek    | TUF Gaming B660M-PLUS WI... | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| Gigabyte   | X570 AORUS ELITE WIFI       | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| ASUSTek    | P5G41T-M LX3                | [43adb86887](https://linux-hardware.org/?probe=43adb86887) | Apr 25, 2022 |
| ASUSTek    | P5G41T-M LX3                | [ba9b8d5ac1](https://linux-hardware.org/?probe=ba9b8d5ac1) | Apr 25, 2022 |
| ECS        | Iris8                       | [1cff4313c1](https://linux-hardware.org/?probe=1cff4313c1) | Apr 23, 2022 |
| HP         | 2B2C                        | [195e5473e9](https://linux-hardware.org/?probe=195e5473e9) | Apr 20, 2022 |
| HP         | 2B2C                        | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| ASUSTek    | B85M-G                      | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| ASUSTek    | B85M-G                      | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte   | H470 HD3                    | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| Intel      | DH61WW AAG23116-204         | [7ec10d98e3](https://linux-hardware.org/?probe=7ec10d98e3) | Apr 03, 2022 |
| Lenovo     | 30D9 NOK                    | [c378cd6fd3](https://linux-hardware.org/?probe=c378cd6fd3) | Mar 27, 2022 |
| Intel      | DH61WW AAG23116-204         | [a1c0612337](https://linux-hardware.org/?probe=a1c0612337) | Mar 17, 2022 |
| ASUSTek    | P8B75-M LX                  | [d52d9feb9e](https://linux-hardware.org/?probe=d52d9feb9e) | Mar 09, 2022 |
| ASUSTek    | P8B75-M LX                  | [8d3f72c54f](https://linux-hardware.org/?probe=8d3f72c54f) | Mar 03, 2022 |
| Biostar    | G41D3+                      | [62ba30cf71](https://linux-hardware.org/?probe=62ba30cf71) | Mar 02, 2022 |
| Dell       | 0D441T A03                  | [bbedea92ea](https://linux-hardware.org/?probe=bbedea92ea) | Mar 01, 2022 |
| Dell       | 0D441T A03                  | [297c168632](https://linux-hardware.org/?probe=297c168632) | Mar 01, 2022 |
| Shuttle    | FH170                       | [768e13fd34](https://linux-hardware.org/?probe=768e13fd34) | Feb 25, 2022 |
| ASUSTek    | H110M-D                     | [1dec2ddfad](https://linux-hardware.org/?probe=1dec2ddfad) | Feb 19, 2022 |
| MSI        | B450 TOMAHAWK               | [6b15f755b0](https://linux-hardware.org/?probe=6b15f755b0) | Jan 12, 2022 |
| Gigabyte   | H470 HD3                    | [ff2f0db3fe](https://linux-hardware.org/?probe=ff2f0db3fe) | Jan 09, 2022 |
| Lenovo     | ThinkStation S10 6483CTO    | [0d867912a7](https://linux-hardware.org/?probe=0d867912a7) | Jan 01, 2022 |
| ECS        | H61H2-M12                   | [c8ca1c8cc8](https://linux-hardware.org/?probe=c8ca1c8cc8) | Dec 24, 2021 |
| MSI        | MAG B460 TOMAHAWK           | [c748f77108](https://linux-hardware.org/?probe=c748f77108) | Dec 12, 2021 |
| HP         | 2B44                        | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| ASUSTek    | TUF Gaming B550-PLUS        | [5c4ae3bd8c](https://linux-hardware.org/?probe=5c4ae3bd8c) | Nov 30, 2021 |
| ECS        | H61H2-M12                   | [c731d25471](https://linux-hardware.org/?probe=c731d25471) | Nov 30, 2021 |
| Dell       | 048DY8 A01                  | [6e5e669c60](https://linux-hardware.org/?probe=6e5e669c60) | Nov 25, 2021 |
| ECS        | H61H2-M12                   | [b5393ad660](https://linux-hardware.org/?probe=b5393ad660) | Nov 12, 2021 |
| ASUSTek    | M2N32-SLI DELUXE            | [87fff05f0f](https://linux-hardware.org/?probe=87fff05f0f) | Nov 03, 2021 |
| Intel      | B75                         | [fef715f491](https://linux-hardware.org/?probe=fef715f491) | Oct 23, 2021 |
| Gigabyte   | H370M D3H-CF                | [8fee3106f7](https://linux-hardware.org/?probe=8fee3106f7) | Oct 12, 2021 |
| Gigabyte   | H370M D3H-CF                | [f79000e059](https://linux-hardware.org/?probe=f79000e059) | Oct 12, 2021 |
| Biostar    | G41D3C                      | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Biostar    | G41D3C                      | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| Gigabyte   | B85M-D3H                    | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| Lenovo     | MAHOBAY NOK                 | [c2533e9d48](https://linux-hardware.org/?probe=c2533e9d48) | Sep 11, 2021 |
| MSI        | H81M-P33                    | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| Biostar    | G41D3C                      | [8137e09a97](https://linux-hardware.org/?probe=8137e09a97) | Sep 08, 2021 |
| Biostar    | G41D3C                      | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| Gigabyte   | B85M-D3H                    | [5377e486bc](https://linux-hardware.org/?probe=5377e486bc) | Sep 03, 2021 |
| MSI        | MAG B460 TOMAHAWK           | [a61ee6d83a](https://linux-hardware.org/?probe=a61ee6d83a) | Sep 01, 2021 |
| Biostar    | G41D3C                      | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar    | G41D3C                      | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| MSI        | MAG B460 TOMAHAWK           | [a1ec21ae3f](https://linux-hardware.org/?probe=a1ec21ae3f) | Aug 29, 2021 |
| ASRock     | H81M-VG4 R2.0               | [cac6720bff](https://linux-hardware.org/?probe=cac6720bff) | Aug 29, 2021 |
| Gigabyte   | B450M S2H V2                | [777faedb05](https://linux-hardware.org/?probe=777faedb05) | Aug 27, 2021 |
| Gigabyte   | B85M-D3H                    | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte   | B85M-D3H                    | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Gigabyte   | B450M S2H V2                | [9e8fa8f32d](https://linux-hardware.org/?probe=9e8fa8f32d) | Aug 23, 2021 |
| Lenovo     | 1046 SDK0T08861 WIN 3305... | [de1fa2ccc0](https://linux-hardware.org/?probe=de1fa2ccc0) | Aug 20, 2021 |
| Intel      | DH61WW AAG23116-204         | [89188fe3ca](https://linux-hardware.org/?probe=89188fe3ca) | Aug 08, 2021 |
| Gigabyte   | B85M-D3H                    | [3e56e95f2f](https://linux-hardware.org/?probe=3e56e95f2f) | Aug 05, 2021 |
| ASUSTek    | P8Z77-V LX                  | [36562061d6](https://linux-hardware.org/?probe=36562061d6) | Jul 30, 2021 |
| ASUSTek    | P8B75-M LE                  | [e71a7fc65b](https://linux-hardware.org/?probe=e71a7fc65b) | Jul 23, 2021 |
| Dell       | 0427JK A00                  | [3e66028cf8](https://linux-hardware.org/?probe=3e66028cf8) | Jul 22, 2021 |
| ASUSTek    | P8B75-M                     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek    | P8B75-M                     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| ASUSTek    | PRIME H310M-D R2.0          | [5a349c4952](https://linux-hardware.org/?probe=5a349c4952) | Jul 19, 2021 |
| Intel      | DH61WW AAG23116-204         | [275304e806](https://linux-hardware.org/?probe=275304e806) | Jul 19, 2021 |
| Intel      | DH61WW AAG23116-204         | [99df792e3b](https://linux-hardware.org/?probe=99df792e3b) | Jul 18, 2021 |
| Gigabyte   | M61PME-S2P                  | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| Intel      | DH61WW AAG23116-204         | [2495cf9be5](https://linux-hardware.org/?probe=2495cf9be5) | Jul 12, 2021 |
| Gigabyte   | B85M-D3H                    | [b551baea7d](https://linux-hardware.org/?probe=b551baea7d) | Jul 11, 2021 |
| Dell       | 0427JK A00                  | [82c73cf6be](https://linux-hardware.org/?probe=82c73cf6be) | Jul 09, 2021 |
| MSI        | B450M MORTAR                | [e8965c736d](https://linux-hardware.org/?probe=e8965c736d) | Jul 05, 2021 |
| Intel      | DH61WW AAG23116-204         | [a5a80d3f13](https://linux-hardware.org/?probe=a5a80d3f13) | Jun 24, 2021 |
| Dell       | 0427JK A00                  | [d9270ab2c1](https://linux-hardware.org/?probe=d9270ab2c1) | Jun 23, 2021 |
| MSI        | B450M MORTAR                | [0183eeb644](https://linux-hardware.org/?probe=0183eeb644) | Jun 12, 2021 |
| MSI        | H81M-P33                    | [69a8b43e74](https://linux-hardware.org/?probe=69a8b43e74) | Jun 02, 2021 |
| MSI        | H81M-P33                    | [a67e6bcfce](https://linux-hardware.org/?probe=a67e6bcfce) | Jun 02, 2021 |
| Gigabyte   | AB350M-Gaming 3-CF          | [00658a23ab](https://linux-hardware.org/?probe=00658a23ab) | May 27, 2021 |
| ASUSTek    | H97M-E                      | [5f39051050](https://linux-hardware.org/?probe=5f39051050) | May 26, 2021 |
| Gigabyte   | B450M S2H                   | [4c5c7570f6](https://linux-hardware.org/?probe=4c5c7570f6) | May 25, 2021 |
| ASUSTek    | P8Z68-V PRO                 | [2b0de1ba10](https://linux-hardware.org/?probe=2b0de1ba10) | May 21, 2021 |
| ASUSTek    | GRYPHON Z87                 | [0cd0f0c51f](https://linux-hardware.org/?probe=0cd0f0c51f) | May 13, 2021 |
| HP         | 0AA8h                       | [5f350b471f](https://linux-hardware.org/?probe=5f350b471f) | Apr 29, 2021 |
| Gigabyte   | Z97X-Gaming G1              | [07efcf431f](https://linux-hardware.org/?probe=07efcf431f) | Apr 14, 2021 |
| Gigabyte   | Z97X-Gaming G1              | [9f265d798d](https://linux-hardware.org/?probe=9f265d798d) | Apr 14, 2021 |
| AMI        | Cherry Trail Tablet         | [87041c97fb](https://linux-hardware.org/?probe=87041c97fb) | Apr 14, 2021 |
| ASUSTek    | P5QPL-VM EPU                | [6d3642385e](https://linux-hardware.org/?probe=6d3642385e) | Apr 11, 2021 |
| ASUSTek    | P5QPL-VM EPU                | [fc405347a5](https://linux-hardware.org/?probe=fc405347a5) | Mar 12, 2021 |
| ASUSTek    | H110M-D                     | [19e3cff2be](https://linux-hardware.org/?probe=19e3cff2be) | Feb 27, 2021 |
| Gigabyte   | A320M-S2H V2-CF             | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| Acer       | MCP73VE NVIDIA MCP73        | [b50872caf4](https://linux-hardware.org/?probe=b50872caf4) | Feb 07, 2021 |
| MSI        | A320M-A PRO MAX             | [7daa68908c](https://linux-hardware.org/?probe=7daa68908c) | Feb 06, 2021 |
| Acer       | MCP73VE NVIDIA MCP73        | [acb369859f](https://linux-hardware.org/?probe=acb369859f) | Feb 06, 2021 |
| Acer       | Veriton X6630G V:1.0        | [d6126d9f25](https://linux-hardware.org/?probe=d6126d9f25) | Jan 27, 2021 |
| Acer       | Veriton X6630G V:1.0        | [9e5a28d45d](https://linux-hardware.org/?probe=9e5a28d45d) | Jan 27, 2021 |
| Dell       | 0WR7PY A01                  | [9b13ab689f](https://linux-hardware.org/?probe=9b13ab689f) | Jan 24, 2021 |
| Dell       | 0WMJ54 A01                  | [dd87c824a0](https://linux-hardware.org/?probe=dd87c824a0) | Jan 18, 2021 |
| ASUSTek    | P8Z77-V LX                  | [9e291d5782](https://linux-hardware.org/?probe=9e291d5782) | Jan 12, 2021 |
| Intel      | DH77KC AAG39641-400         | [f3c691cbf8](https://linux-hardware.org/?probe=f3c691cbf8) | Jan 01, 2021 |
| MSI        | H81M-P33                    | [e8d73a49e5](https://linux-hardware.org/?probe=e8d73a49e5) | Dec 30, 2020 |
| Intel      | DH61WW AAG23116-300         | [7e473c8d12](https://linux-hardware.org/?probe=7e473c8d12) | Dec 24, 2020 |
| Intel      | DH61WW AAG23116-300         | [645dfe5a80](https://linux-hardware.org/?probe=645dfe5a80) | Dec 23, 2020 |
| Dell       | 0PU052                      | [520a4ef3d0](https://linux-hardware.org/?probe=520a4ef3d0) | Dec 23, 2020 |
| Biostar    | A320MH                      | [a6b1134a37](https://linux-hardware.org/?probe=a6b1134a37) | Dec 18, 2020 |
| Gigabyte   | F2A88XM-HD3P                | [a0b90b128d](https://linux-hardware.org/?probe=a0b90b128d) | Dec 16, 2020 |
| Gigabyte   | H77M-D3H                    | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte   | H77M-D3H                    | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| Intel      | DH61WW AAG23116-300         | [414fc579a1](https://linux-hardware.org/?probe=414fc579a1) | Dec 02, 2020 |
| Intel      | DH61WW AAG23116-300         | [cf6242caca](https://linux-hardware.org/?probe=cf6242caca) | Dec 02, 2020 |
| Intel      | DH61WW AAG23116-300         | [afbf8ce7bc](https://linux-hardware.org/?probe=afbf8ce7bc) | Dec 01, 2020 |
| ASRock     | G41C-GS                     | [c323f09a39](https://linux-hardware.org/?probe=c323f09a39) | Nov 17, 2020 |
| Gigabyte   | Z490 VISION D               | [af58d1579d](https://linux-hardware.org/?probe=af58d1579d) | Nov 09, 2020 |
| ASUSTek    | B85M-G                      | [5021546be8](https://linux-hardware.org/?probe=5021546be8) | Oct 30, 2020 |
| ASUSTek    | PRIME B350-PLUS             | [b6aa803efb](https://linux-hardware.org/?probe=b6aa803efb) | Oct 21, 2020 |
| ASUSTek    | PRIME B350-PLUS             | [02a2657831](https://linux-hardware.org/?probe=02a2657831) | Oct 20, 2020 |
| Dell       | 09WH54 A00                  | [5c8d0c0991](https://linux-hardware.org/?probe=5c8d0c0991) | Oct 15, 2020 |
| Dell       | 06D7TR A02                  | [1fff522fa1](https://linux-hardware.org/?probe=1fff522fa1) | Oct 13, 2020 |
| Dell       | 09WH54 A00                  | [e8e5a3c2ac](https://linux-hardware.org/?probe=e8e5a3c2ac) | Oct 12, 2020 |
| Dell       | 0RW203                      | [594ab9e6d3](https://linux-hardware.org/?probe=594ab9e6d3) | Sep 02, 2020 |
| Gigabyte   | B450M S2H                   | [0930a62ca5](https://linux-hardware.org/?probe=0930a62ca5) | Aug 21, 2020 |
| ASUSTek    | Z170 PRO GAMING             | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| ASUSTek    | H110M-D                     | [bc44361c47](https://linux-hardware.org/?probe=bc44361c47) | Aug 02, 2020 |
| ASUSTek    | H110M-D                     | [e8cc620228](https://linux-hardware.org/?probe=e8cc620228) | Aug 02, 2020 |
| Gigabyte   | B85M-D3H                    | [3f99c1674c](https://linux-hardware.org/?probe=3f99c1674c) | Jul 30, 2020 |
| Dell       | 0D6H9T A00                  | [dbbc5219fd](https://linux-hardware.org/?probe=dbbc5219fd) | Jul 27, 2020 |
| Gigabyte   | B85M-D3H                    | [2bfaffc9c5](https://linux-hardware.org/?probe=2bfaffc9c5) | Jul 21, 2020 |
| Gigabyte   | H61M-S2P-R3                 | [7b83e5785f](https://linux-hardware.org/?probe=7b83e5785f) | Jul 19, 2020 |
| Gigabyte   | B85M-D3H                    | [ab9fa86313](https://linux-hardware.org/?probe=ab9fa86313) | Jul 16, 2020 |
| Gigabyte   | GA-890GPA-UD3H              | [7d9a43933e](https://linux-hardware.org/?probe=7d9a43933e) | Jul 14, 2020 |
| Biostar    | H81MHV3                     | [48cdbb3d36](https://linux-hardware.org/?probe=48cdbb3d36) | Jul 11, 2020 |
| Biostar    | H81MHV3                     | [a97a2e14e2](https://linux-hardware.org/?probe=a97a2e14e2) | Jul 06, 2020 |
| Gigabyte   | B85M-D3H                    | [5d32eb1d75](https://linux-hardware.org/?probe=5d32eb1d75) | Jun 30, 2020 |
| Acer       | Aspire XC600 v1.0           | [99ff555015](https://linux-hardware.org/?probe=99ff555015) | Jun 21, 2020 |
| Gigabyte   | GA-890GPA-UD3H              | [05556ef252](https://linux-hardware.org/?probe=05556ef252) | Jun 19, 2020 |
| Acer       | Aspire XC600 v1.0           | [eac1260628](https://linux-hardware.org/?probe=eac1260628) | Jun 17, 2020 |
| ASRock     | Z77 Extreme4                | [ba4a677fab](https://linux-hardware.org/?probe=ba4a677fab) | Jun 10, 2020 |
| MSI        | A320M-A PRO MAX             | [11c6b72a1b](https://linux-hardware.org/?probe=11c6b72a1b) | Jun 03, 2020 |
| MSI        | A320M-A PRO MAX             | [ecf8e72f94](https://linux-hardware.org/?probe=ecf8e72f94) | May 31, 2020 |
| ASRock     | Z77 Extreme4                | [865933043f](https://linux-hardware.org/?probe=865933043f) | May 26, 2020 |
| Acer       | EQ45M                       | [a682473a39](https://linux-hardware.org/?probe=a682473a39) | May 23, 2020 |
| Gigabyte   | B85M-D3H                    | [d2113ac640](https://linux-hardware.org/?probe=d2113ac640) | May 21, 2020 |
| Dell       | 0PU052                      | [40ab4a84b5](https://linux-hardware.org/?probe=40ab4a84b5) | May 18, 2020 |
| Gigabyte   | B85M-D3H                    | [8156a3eef6](https://linux-hardware.org/?probe=8156a3eef6) | May 11, 2020 |
| Dell       | 0RY007                      | [4d44e2723d](https://linux-hardware.org/?probe=4d44e2723d) | May 04, 2020 |
| Acer       | EQ45M                       | [03e154e2dc](https://linux-hardware.org/?probe=03e154e2dc) | Apr 21, 2020 |
| Dell       | 0C3YXR A01                  | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| ASUSTek    | TUF B360-PLUS GAMING        | [0444963962](https://linux-hardware.org/?probe=0444963962) | Apr 12, 2020 |
| MSI        | B150M Night Elf             | [01013b611d](https://linux-hardware.org/?probe=01013b611d) | Apr 11, 2020 |
| Gigabyte   | H61M-S2P-R3                 | [1211d7770c](https://linux-hardware.org/?probe=1211d7770c) | Mar 15, 2020 |
| ASUSTek    | P6T SE                      | [05737b4c23](https://linux-hardware.org/?probe=05737b4c23) | Feb 11, 2020 |
| HP         | 3647h                       | [06df72e240](https://linux-hardware.org/?probe=06df72e240) | Feb 08, 2020 |
| ASUSTek    | P8Z77-M                     | [9247337003](https://linux-hardware.org/?probe=9247337003) | Jan 20, 2020 |
| ASUSTek    | P6T SE                      | [02d013ad00](https://linux-hardware.org/?probe=02d013ad00) | Dec 20, 2019 |
| ASUSTek    | P6T SE                      | [9e78c03471](https://linux-hardware.org/?probe=9e78c03471) | Nov 17, 2019 |
| ASUSTek    | F1A55-M LX PLUS             | [875f14ed53](https://linux-hardware.org/?probe=875f14ed53) | Nov 13, 2019 |
| ASUSTek    | P6T SE                      | [7ce70fa206](https://linux-hardware.org/?probe=7ce70fa206) | Oct 25, 2019 |
| ASUSTek    | P5QPL-AM                    | [b37e090603](https://linux-hardware.org/?probe=b37e090603) | Oct 06, 2019 |
| HP         | 0AA8h                       | [a60543a450](https://linux-hardware.org/?probe=a60543a450) | Sep 07, 2019 |
| Dell       | 0RY007                      | [576ec7dcd0](https://linux-hardware.org/?probe=576ec7dcd0) | Aug 22, 2019 |
| ASUSTek    | Maximus VII RANGER          | [d9d789a4f2](https://linux-hardware.org/?probe=d9d789a4f2) | Aug 21, 2019 |
| ASUSTek    | P6T SE                      | [a91c21a426](https://linux-hardware.org/?probe=a91c21a426) | Aug 02, 2019 |
| ASUSTek    | H81M-C                      | [38a96dff85](https://linux-hardware.org/?probe=38a96dff85) | Jul 02, 2019 |
| ASUSTek    | ROG STRIX Z370-F GAMING     | [62b0b05a66](https://linux-hardware.org/?probe=62b0b05a66) | Jul 01, 2019 |
| ASRock     | X79 Extreme9                | [c96c05c47b](https://linux-hardware.org/?probe=c96c05c47b) | Nov 30, 2018 |
| HP         | 2820h                       | [1f42af0283](https://linux-hardware.org/?probe=1f42af0283) | Dec 17, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 30       | 12.93%  |
| Debian 11                    | 18       | 7.76%   |
| Ubuntu 22.04                 | 13       | 5.6%    |
| Ubuntu 18.04                 | 9        | 3.88%   |
| Zorin 16                     | 8        | 3.45%   |
| OpenMandriva 4.3             | 8        | 3.45%   |
| OpenMandriva 23.03           | 7        | 3.02%   |
| ArcoLinux Rolling            | 7        | 3.02%   |
| Pop!_OS 22.04                | 6        | 2.59%   |
| OpenMandriva 4.2             | 6        | 2.59%   |
| Pop!_OS 20.04                | 5        | 2.16%   |
| OpenMandriva 4.50            | 5        | 2.16%   |
| Ubuntu 19.04                 | 4        | 1.72%   |
| OpenMandriva 23.08           | 4        | 1.72%   |
| OpenMandriva 23.01           | 4        | 1.72%   |
| Xubuntu 18.04                | 3        | 1.29%   |
| Linux Mint 19.3              | 3        | 1.29%   |
| Fedora 39                    | 3        | 1.29%   |
| Fedora 37                    | 3        | 1.29%   |
| Fedora 33                    | 3        | 1.29%   |
| Zorin 15                     | 2        | 0.86%   |
| Ubuntu 23.10                 | 2        | 0.86%   |
| Ubuntu 23.04                 | 2        | 0.86%   |
| Ubuntu 19.10                 | 2        | 0.86%   |
| Pop!_OS 21.04                | 2        | 0.86%   |
| Pop!_OS 20.10                | 2        | 0.86%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 0.86%   |
| OpenMandriva 23.07           | 2        | 0.86%   |
| Manjaro 21.2.6               | 2        | 0.86%   |
| Linux Mint 20.3              | 2        | 0.86%   |
| KDE neon 22.04               | 2        | 0.86%   |
| KDE neon 20.04               | 2        | 0.86%   |
| Fedora 40                    | 2        | 0.86%   |
| Fedora 34                    | 2        | 0.86%   |
| Debian 12                    | 2        | 0.86%   |
| Arch                         | 2        | 0.86%   |
| Zorin 17                     | 1        | 0.43%   |
| Ubuntu Unity 22.04           | 1        | 0.43%   |
| Ubuntu MATE 20.04            | 1        | 0.43%   |
| Ubuntu 22.10                 | 1        | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 62       | 28.57%  |
| OpenMandriva | 34       | 15.67%  |
| Debian       | 21       | 9.68%   |
| Pop!_OS      | 14       | 6.45%   |
| Fedora       | 12       | 5.53%   |
| Zorin        | 10       | 4.61%   |
| Linux Mint   | 10       | 4.61%   |
| ArcoLinux    | 7        | 3.23%   |
| Manjaro      | 5        | 2.3%    |
| Lubuntu      | 4        | 1.84%   |
| KDE neon     | 4        | 1.84%   |
| Elementary   | 4        | 1.84%   |
| Xubuntu      | 3        | 1.38%   |
| openSUSE     | 3        | 1.38%   |
| Endless      | 3        | 1.38%   |
| Arch         | 3        | 1.38%   |
| ROSA         | 2        | 0.92%   |
| Kubuntu      | 2        | 0.92%   |
| Kali         | 2        | 0.92%   |
| EndeavourOS  | 2        | 0.92%   |
| Ubuntu Unity | 1        | 0.46%   |
| Ubuntu MATE  | 1        | 0.46%   |
| SteamOS      | 1        | 0.46%   |
| Rocky Linux  | 1        | 0.46%   |
| Parrot       | 1        | 0.46%   |
| Mageia       | 1        | 0.46%   |
| Linux Lite   | 1        | 0.46%   |
| Gentoo       | 1        | 0.46%   |
| ChimeraOS    | 1        | 0.46%   |
| CentOS       | 1        | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.2.6-desktop-1omv2390        | 8        | 2.95%   |
| 5.10.14-desktop-1omv4002      | 6        | 2.21%   |
| 5.4.0-58-generic              | 5        | 1.85%   |
| 5.16.7-desktop-1omv4003       | 5        | 1.85%   |
| 5.13.19-6-pve                 | 5        | 1.85%   |
| 6.4.11-desktop-1omv2390       | 4        | 1.48%   |
| 5.4.0-42-generic              | 4        | 1.48%   |
| 5.15.126-1-pve                | 4        | 1.48%   |
| 5.15.108-1-pve                | 4        | 1.48%   |
| 6.5.0-27-generic              | 3        | 1.11%   |
| 6.5.0-14-generic              | 3        | 1.11%   |
| 5.4.0-40-generic              | 3        | 1.11%   |
| 5.3.0-53-generic              | 3        | 1.11%   |
| 5.3.0-46-generic              | 3        | 1.11%   |
| 5.16.3-desktop-2omv4050       | 3        | 1.11%   |
| 5.15.0-52-generic             | 3        | 1.11%   |
| 5.11.0-27-generic             | 3        | 1.11%   |
| 6.8.2-300.fc40.x86_64         | 2        | 0.74%   |
| 6.6.7-200.fc39.x86_64         | 2        | 0.74%   |
| 6.6.11-200.fc39.x86_64        | 2        | 0.74%   |
| 6.5.0-15-generic              | 2        | 0.74%   |
| 6.3.5-desktop-3omv2390        | 2        | 0.74%   |
| 6.2.6-76060206-generic        | 2        | 0.74%   |
| 6.0.12-76060006-generic       | 2        | 0.74%   |
| 5.8.0-53-generic              | 2        | 0.74%   |
| 5.8.0-44-generic              | 2        | 0.74%   |
| 5.8.0-41-generic              | 2        | 0.74%   |
| 5.4.0-77-generic              | 2        | 0.74%   |
| 5.4.0-7634-generic            | 2        | 0.74%   |
| 5.4.0-48-generic              | 2        | 0.74%   |
| 5.4.0-37-generic              | 2        | 0.74%   |
| 5.4.0-29-generic              | 2        | 0.74%   |
| 5.19.0-46-generic             | 2        | 0.74%   |
| 5.19.0-32-generic             | 2        | 0.74%   |
| 5.15.35-3-pve                 | 2        | 0.74%   |
| 5.15.143-1-pve                | 2        | 0.74%   |
| 5.15.0-58-generic             | 2        | 0.74%   |
| 5.15.0-39-generic             | 2        | 0.74%   |
| 5.12.7-desktop-clang-1omv4003 | 2        | 0.74%   |
| 5.12.4-desktop-1omv4050       | 2        | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 33       | 12.99%  |
| 5.15.0   | 15       | 5.91%   |
| 5.11.0   | 12       | 4.72%   |
| 5.8.0    | 11       | 4.33%   |
| 6.5.0    | 10       | 3.94%   |
| 6.2.6    | 10       | 3.94%   |
| 5.3.0    | 8        | 3.15%   |
| 5.19.0   | 7        | 2.76%   |
| 5.0.0    | 7        | 2.76%   |
| 5.10.14  | 6        | 2.36%   |
| 4.15.0   | 6        | 2.36%   |
| 5.16.7   | 5        | 1.97%   |
| 5.13.19  | 5        | 1.97%   |
| 5.13.0   | 5        | 1.97%   |
| 6.4.11   | 4        | 1.57%   |
| 6.2.0    | 4        | 1.57%   |
| 5.15.126 | 4        | 1.57%   |
| 5.15.108 | 4        | 1.57%   |
| 6.8.2    | 3        | 1.18%   |
| 6.6.11   | 3        | 1.18%   |
| 6.5.6    | 3        | 1.18%   |
| 5.16.3   | 3        | 1.18%   |
| 6.6.7    | 2        | 0.79%   |
| 6.3.5    | 2        | 0.79%   |
| 6.2.16   | 2        | 0.79%   |
| 6.1.0    | 2        | 0.79%   |
| 6.0.12   | 2        | 0.79%   |
| 5.18.0   | 2        | 0.79%   |
| 5.17.1   | 2        | 0.79%   |
| 5.15.35  | 2        | 0.79%   |
| 5.15.143 | 2        | 0.79%   |
| 5.12.7   | 2        | 0.79%   |
| 5.12.4   | 2        | 0.79%   |
| 5.12.15  | 2        | 0.79%   |
| 5.10.0   | 2        | 0.79%   |
| 4.18.0   | 2        | 0.79%   |
| 6.8.7    | 1        | 0.39%   |
| 6.8.0    | 1        | 0.39%   |
| 6.7.8    | 1        | 0.39%   |
| 6.7.5    | 1        | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 33       | 13.58%  |
| 5.15    | 33       | 13.58%  |
| 6.2     | 18       | 7.41%   |
| 6.5     | 14       | 5.76%   |
| 5.11    | 13       | 5.35%   |
| 5.8     | 11       | 4.53%   |
| 5.16    | 11       | 4.53%   |
| 5.13    | 11       | 4.53%   |
| 5.19    | 9        | 3.7%    |
| 5.10    | 9        | 3.7%    |
| 6.6     | 8        | 3.29%   |
| 5.3     | 8        | 3.29%   |
| 6.4     | 7        | 2.88%   |
| 5.0     | 7        | 2.88%   |
| 6.3     | 6        | 2.47%   |
| 5.12    | 6        | 2.47%   |
| 4.15    | 6        | 2.47%   |
| 6.0     | 5        | 2.06%   |
| 6.8     | 4        | 1.65%   |
| 6.1     | 4        | 1.65%   |
| 5.18    | 4        | 1.65%   |
| 5.14    | 4        | 1.65%   |
| 6.7     | 3        | 1.23%   |
| 5.9     | 3        | 1.23%   |
| 5.17    | 3        | 1.23%   |
| 4.18    | 2        | 0.82%   |
| 4.9     | 1        | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 205      | 99.03%  |
| i686   | 2        | 0.97%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| GNOME        | 87       | 39.37%  |
| KDE5         | 49       | 22.17%  |
| XFCE         | 23       | 10.41%  |
| Unknown      | 17       | 7.69%   |
| Openbox      | 9        | 4.07%   |
| X-Cinnamon   | 8        | 3.62%   |
| MATE         | 7        | 3.17%   |
| LXQt         | 5        | 2.26%   |
| Pantheon     | 4        | 1.81%   |
| KDE          | 3        | 1.36%   |
| KDE6         | 2        | 0.9%    |
| wayfire      | 1        | 0.45%   |
| Unity        | 1        | 0.45%   |
| LXDE         | 1        | 0.45%   |
| KDE4         | 1        | 0.45%   |
| herbstluftwm | 1        | 0.45%   |
| Cinnamon     | 1        | 0.45%   |
| bspwm        | 1        | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 163      | 74.43%  |
| Wayland | 33       | 15.07%  |
| Tty     | 16       | 7.31%   |
| Unknown | 7        | 3.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 95       | 44.39%  |
| SDDM    | 51       | 23.83%  |
| LightDM | 29       | 13.55%  |
| GDM3    | 22       | 10.28%  |
| GDM     | 13       | 6.07%   |
| TDM     | 3        | 1.4%    |
| LXDM    | 1        | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 161      | 75.23%  |
| en_GB   | 16       | 7.48%   |
| en_SG   | 11       | 5.14%   |
| Unknown | 10       | 4.67%   |
| zh_CN   | 3        | 1.4%    |
| en_AU   | 3        | 1.4%    |
| en_MY   | 2        | 0.93%   |
| en_HK   | 2        | 0.93%   |
| de_DE   | 2        | 0.93%   |
| C       | 2        | 0.93%   |
| zh_SG   | 1        | 0.47%   |
| ms_MY   | 1        | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 125      | 58.41%  |
| EFI  | 89       | 41.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 136      | 63.26%  |
| Btrfs   | 26       | 12.09%  |
| Overlay | 21       | 9.77%   |
| Tmpfs   | 11       | 5.12%   |
| Zfs     | 10       | 4.65%   |
| Xfs     | 5        | 2.33%   |
| Unknown | 4        | 1.86%   |
| Ext3    | 1        | 0.47%   |
| Ext2    | 1        | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 94       | 44.34%  |
| GPT     | 90       | 42.45%  |
| MBR     | 28       | 13.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 157      | 72.35%  |
| Yes       | 60       | 27.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 132      | 61.97%  |
| Yes       | 81       | 38.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 45       | 21.74%  |
| ASUSTek Computer    | 43       | 20.77%  |
| MSI                 | 24       | 11.59%  |
| Dell                | 22       | 10.63%  |
| Intel               | 17       | 8.21%   |
| Hewlett-Packard     | 10       | 4.83%   |
| ASRock              | 10       | 4.83%   |
| Lenovo              | 8        | 3.86%   |
| Acer                | 8        | 3.86%   |
| Biostar             | 5        | 2.42%   |
| Unknown             | 4        | 1.93%   |
| ECS                 | 3        | 1.45%   |
| Vorke               | 1        | 0.48%   |
| Shuttle             | 1        | 0.48%   |
| Seco                | 1        | 0.48%   |
| ONDA                | 1        | 0.48%   |
| Machenike           | 1        | 0.48%   |
| AZW                 | 1        | 0.48%   |
| ASRockRack          | 1        | 0.48%   |
| AMI                 | 1        | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Intel DH61WW AAG23116-204          | 8        | 3.86%   |
| ASUS All Series                    | 8        | 3.86%   |
| Gigabyte Z77M-D3H                  | 6        | 2.9%    |
| Gigabyte B85M-D3H                  | 6        | 2.9%    |
| MSI MS-7C52                        | 5        | 2.42%   |
| Gigabyte X570 UD                   | 4        | 1.93%   |
| Unknown                            | 4        | 1.93%   |
| MSI MS-7817                        | 3        | 1.45%   |
| Intel DH61WW AAG23116-300          | 3        | 1.45%   |
| Gigabyte B450M S2H                 | 3        | 1.45%   |
| Dell OptiPlex 755                  | 3        | 1.45%   |
| ASRock B550 Pro4                   | 3        | 1.45%   |
| MSI MS-7C81                        | 2        | 0.97%   |
| MSI MS-7B89                        | 2        | 0.97%   |
| Intel MAHOBAY                      | 2        | 0.97%   |
| Gigabyte B550 AORUS PRO V2         | 2        | 0.97%   |
| Dell XPS 8940                      | 2        | 0.97%   |
| Dell OptiPlex 990                  | 2        | 0.97%   |
| Dell OptiPlex 7010                 | 2        | 0.97%   |
| Biostar G41D3C                     | 2        | 0.97%   |
| ASUS ROG STRIX X670E-E GAMING WIFI | 2        | 0.97%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI    | 2        | 0.97%   |
| ASUS P8Z77-V LX                    | 2        | 0.97%   |
| ASUS CROSSHAIR VI HERO             | 2        | 0.97%   |
| Vorke V1 Plus                      | 1        | 0.48%   |
| Shuttle DH170                      | 1        | 0.48%   |
| Seco C40                           | 1        | 0.48%   |
| ONDA H110-MINI V3.00               | 1        | 0.48%   |
| MSI MS-7D99                        | 1        | 0.48%   |
| MSI MS-7D46                        | 1        | 0.48%   |
| MSI MS-7D42                        | 1        | 0.48%   |
| MSI MS-7C96                        | 1        | 0.48%   |
| MSI MS-7C37                        | 1        | 0.48%   |
| MSI MS-7C02                        | 1        | 0.48%   |
| MSI MS-7B79                        | 1        | 0.48%   |
| MSI MS-7A39                        | 1        | 0.48%   |
| MSI MS-7979                        | 1        | 0.48%   |
| MSI MS-7916                        | 1        | 0.48%   |
| MSI MS-7693                        | 1        | 0.48%   |
| MSI MS-7388                        | 1        | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 13       | 6.28%   |
| Intel DH61WW        | 11       | 5.31%   |
| ASUS All            | 8        | 3.86%   |
| Gigabyte Z77M-D3H   | 6        | 2.9%    |
| Gigabyte X570       | 6        | 2.9%    |
| Gigabyte B85M-D3H   | 6        | 2.9%    |
| MSI MS-7C52         | 5        | 2.42%   |
| ASUS TUF            | 5        | 2.42%   |
| Lenovo ThinkCentre  | 4        | 1.93%   |
| HP Compaq           | 4        | 1.93%   |
| Gigabyte B450M      | 4        | 1.93%   |
| Dell Precision      | 4        | 1.93%   |
| ASUS ROG            | 4        | 1.93%   |
| ASUS PRIME          | 4        | 1.93%   |
| Acer Veriton        | 4        | 1.93%   |
| Acer Aspire         | 4        | 1.93%   |
| Unknown             | 4        | 1.93%   |
| MSI MS-7817         | 3        | 1.45%   |
| Lenovo ThinkStation | 3        | 1.45%   |
| Dell Inspiron       | 3        | 1.45%   |
| ASUS P8B75-M        | 3        | 1.45%   |
| ASRock B550         | 3        | 1.45%   |
| MSI MS-7C81         | 2        | 0.97%   |
| MSI MS-7B89         | 2        | 0.97%   |
| Intel MAHOBAY       | 2        | 0.97%   |
| HP ProDesk          | 2        | 0.97%   |
| Gigabyte B550       | 2        | 0.97%   |
| Dell XPS            | 2        | 0.97%   |
| Biostar G41D3C      | 2        | 0.97%   |
| ASUS Pro            | 2        | 0.97%   |
| ASUS P8Z77-V        | 2        | 0.97%   |
| ASUS CROSSHAIR      | 2        | 0.97%   |
| Vorke V1            | 1        | 0.48%   |
| Shuttle DH170       | 1        | 0.48%   |
| Seco C40            | 1        | 0.48%   |
| ONDA H110-MINI      | 1        | 0.48%   |
| MSI MS-7D99         | 1        | 0.48%   |
| MSI MS-7D46         | 1        | 0.48%   |
| MSI MS-7D42         | 1        | 0.48%   |
| MSI MS-7C96         | 1        | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 29       | 14.01%  |
| 2018    | 20       | 9.66%   |
| 2013    | 18       | 8.7%    |
| 2019    | 16       | 7.73%   |
| 2011    | 15       | 7.25%   |
| 2022    | 13       | 6.28%   |
| 2020    | 13       | 6.28%   |
| 2017    | 12       | 5.8%    |
| 2015    | 12       | 5.8%    |
| 2021    | 11       | 5.31%   |
| 2008    | 11       | 5.31%   |
| 2007    | 9        | 4.35%   |
| 2014    | 7        | 3.38%   |
| 2010    | 7        | 3.38%   |
| 2009    | 6        | 2.9%    |
| 2023    | 4        | 1.93%   |
| 2016    | 2        | 0.97%   |
| 2006    | 1        | 0.48%   |
| Unknown | 1        | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 207      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 200      | 96.62%  |
| Enabled  | 7        | 3.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 207      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 61       | 28.5%   |
| 4.01-8.0    | 36       | 16.82%  |
| 8.01-16.0   | 35       | 16.36%  |
| 3.01-4.0    | 23       | 10.75%  |
| 32.01-64.0  | 22       | 10.28%  |
| 64.01-256.0 | 19       | 8.88%   |
| 24.01-32.0  | 8        | 3.74%   |
| 1.01-2.0    | 8        | 3.74%   |
| 2.01-3.0    | 2        | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 70       | 28.69%  |
| 2.01-3.0    | 63       | 25.82%  |
| 3.01-4.0    | 35       | 14.34%  |
| 4.01-8.0    | 23       | 9.43%   |
| 8.01-16.0   | 15       | 6.15%   |
| 0.51-1.0    | 15       | 6.15%   |
| 32.01-64.0  | 7        | 2.87%   |
| 16.01-24.0  | 6        | 2.46%   |
| 24.01-32.0  | 4        | 1.64%   |
| 64.01-256.0 | 3        | 1.23%   |
| 0.01-0.5    | 3        | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 72       | 32.58%  |
| 2      | 62       | 28.05%  |
| 3      | 33       | 14.93%  |
| 4      | 20       | 9.05%   |
| 7      | 9        | 4.07%   |
| 5      | 9        | 4.07%   |
| 8      | 6        | 2.71%   |
| 6      | 5        | 2.26%   |
| 11     | 2        | 0.9%    |
| 10     | 2        | 0.9%    |
| 9      | 1        | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 145      | 69.38%  |
| Yes       | 64       | 30.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 192      | 92.75%  |
| No        | 15       | 7.25%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 124      | 58.22%  |
| No        | 89       | 41.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 139      | 66.19%  |
| Yes       | 71       | 33.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Malaysia | 207      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Kuala Lumpur           | 96       | 41.74%  |
| Petaling Jaya          | 19       | 8.26%   |
| George Town            | 13       | 5.65%   |
| Seremban               | 8        | 3.48%   |
| Kota Kinabalu          | 8        | 3.48%   |
| Kuching                | 6        | 2.61%   |
| Kajang                 | 6        | 2.61%   |
| Shah Alam              | 5        | 2.17%   |
| Subang Jaya            | 4        | 1.74%   |
| Malacca                | 4        | 1.74%   |
| Johor Bahru            | 4        | 1.74%   |
| Butterworth            | 4        | 1.74%   |
| Sungai Buloh           | 3        | 1.3%    |
| Puchong Batu Dua Belas | 3        | 1.3%    |
| Kulim                  | 3        | 1.3%    |
| Kota Bharu             | 3        | 1.3%    |
| Ipoh                   | 3        | 1.3%    |
| Cheras                 | 3        | 1.3%    |
| Bayan Lepas            | 3        | 1.3%    |
| Tawau                  | 2        | 0.87%   |
| Seri Kembangan         | 2        | 0.87%   |
| Labuan                 | 2        | 0.87%   |
| Bukit Mertajam         | 2        | 0.87%   |
| Ampang                 | 2        | 0.87%   |
| Alor Star              | 2        | 0.87%   |
| Taman Senai            | 1        | 0.43%   |
| Taiping                | 1        | 0.43%   |
| Sungai Petani          | 1        | 0.43%   |
| Semenyih               | 1        | 0.43%   |
| Rawang                 | 1        | 0.43%   |
| Putrajaya              | 1        | 0.43%   |
| Penampang              | 1        | 0.43%   |
| Padang Serai           | 1        | 0.43%   |
| Muar town              | 1        | 0.43%   |
| Marabu                 | 1        | 0.43%   |
| Long Seridan           | 1        | 0.43%   |
| Kulai                  | 1        | 0.43%   |
| Kuantan                | 1        | 0.43%   |
| Klang                  | 1        | 0.43%   |
| Cukai                  | 1        | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 93       | 195    | 21.78%  |
| WDC                         | 82       | 164    | 19.2%   |
| Kingston                    | 42       | 91     | 9.84%   |
| Samsung Electronics         | 27       | 45     | 6.32%   |
| Toshiba                     | 20       | 28     | 4.68%   |
| PNY                         | 16       | 51     | 3.75%   |
| A-DATA Technology           | 14       | 27     | 3.28%   |
| SanDisk                     | 11       | 16     | 2.58%   |
| Crucial                     | 11       | 20     | 2.58%   |
| Intel                       | 8        | 13     | 1.87%   |
| Apacer                      | 7        | 12     | 1.64%   |
| Unknown                     | 6        | 8      | 1.41%   |
| Corsair                     | 6        | 17     | 1.41%   |
| Phison Electronics          | 5        | 5      | 1.17%   |
| Micron Technology           | 5        | 10     | 1.17%   |
| Silicon Motion              | 4        | 8      | 0.94%   |
| Hitachi                     | 4        | 4      | 0.94%   |
| HGST                        | 4        | 4      | 0.94%   |
| China                       | 4        | 4      | 0.94%   |
| TO Exter                    | 3        | 5      | 0.7%    |
| Phison                      | 3        | 4      | 0.7%    |
| KIOXIA-EXCERIA              | 3        | 5      | 0.7%    |
| Gigabyte Technology         | 3        | 3      | 0.7%    |
| XPG                         | 2        | 3      | 0.47%   |
| Verbatim                    | 2        | 3      | 0.47%   |
| Transcend                   | 2        | 3      | 0.47%   |
| SPCC                        | 2        | 2      | 0.47%   |
| SK hynix                    | 2        | 2      | 0.47%   |
| Plextor                     | 2        | 2      | 0.47%   |
| OCZ                         | 2        | 7      | 0.47%   |
| Kingston Technology Company | 2        | 2      | 0.47%   |
| Hewlett-Packard             | 2        | 2      | 0.47%   |
| GAMER                       | 2        | 2      | 0.47%   |
| External                    | 2        | 2      | 0.47%   |
| AGI                         | 2        | 2      | 0.47%   |
| ADATA Technology            | 2        | 2      | 0.47%   |
| sk600                       | 1        | 1      | 0.23%   |
| SATAFIRM                    | 1        | 1      | 0.23%   |
| Realtek Semiconductor       | 1        | 1      | 0.23%   |
| Realtek                     | 1        | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seagate ST2000DM008-2UB102 2TB          | 13       | 2.55%   |
| Kingston SA400S37240G 240GB SSD         | 13       | 2.55%   |
| Seagate ST3500414CS 500GB               | 9        | 1.77%   |
| PNY 1TB SATA SSD                        | 9        | 1.77%   |
| Seagate ST1000DM010-2EP102 1TB          | 8        | 1.57%   |
| WDC WD5000AAKX-75U6AA0 500GB            | 7        | 1.38%   |
| WDC WD2500AAKX-753CA1 250GB             | 7        | 1.38%   |
| Samsung HD103SJ 1TB                     | 6        | 1.18%   |
| Kingston SEDC500R1920G 2TB SSD          | 6        | 1.18%   |
| Corsair Force MP510 240GB               | 6        | 1.18%   |
| A-DATA SX8200PNP 256GB                  | 6        | 1.18%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 5        | 0.98%   |
| WDC WD20EZRX-00D8PB0 2TB                | 5        | 0.98%   |
| Seagate ST500DM002-1BD142 500GB         | 5        | 0.98%   |
| Seagate ST380815AS 80GB                 | 5        | 0.98%   |
| PNY CS900 1TB SSD                       | 5        | 0.98%   |
| Kingston SEDC1000BM8960G 960GB          | 5        | 0.98%   |
| Toshiba MQ01ABD100 1TB                  | 4        | 0.79%   |
| Seagate ST500DM002-1BC142 500GB         | 4        | 0.79%   |
| Seagate ST3160815AS 160GB               | 4        | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4        | 0.79%   |
| Kingston SA400S37480G 480GB SSD         | 4        | 0.79%   |
| A-DATA SU650 120GB SSD                  | 4        | 0.79%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 3        | 0.59%   |
| WDC WD5000AAKX-08U6AA0 500GB            | 3        | 0.59%   |
| WDC WD3200AAKS-00SBA0 320GB             | 3        | 0.59%   |
| WDC WD20EZAZ-00GGJB0 2TB                | 3        | 0.59%   |
| WDC WD10EZEX-22MFCA0 1TB                | 3        | 0.59%   |
| TO Exter nal USB 3.0 500GB              | 3        | 0.59%   |
| Seagate ST3320418AS 320GB               | 3        | 0.59%   |
| Seagate ST2000DM006-2DM164 2TB          | 3        | 0.59%   |
| Seagate ST1000DM003-1ER162 1TB          | 3        | 0.59%   |
| Seagate ST1000DM003-1CH162 1TB          | 3        | 0.59%   |
| PNY CS900 120GB SSD                     | 3        | 0.59%   |
| Phison PS5013 E13 NVMe Controller 512GB | 3        | 0.59%   |
| Kingston SV300S37A120G 120GB SSD        | 3        | 0.59%   |
| Kingston SA400S37120G 120GB SSD         | 3        | 0.59%   |
| Kingston NVMe SSD Drive 500GB           | 3        | 0.59%   |
| Crucial CT500MX500SSD1 500GB            | 3        | 0.59%   |
| XPG NVMe SSD Drive 512GB                | 2        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 92       | 194    | 42.59%  |
| WDC                 | 78       | 160    | 36.11%  |
| Toshiba             | 20       | 28     | 9.26%   |
| Samsung Electronics | 10       | 14     | 4.63%   |
| Hitachi             | 4        | 4      | 1.85%   |
| HGST                | 4        | 4      | 1.85%   |
| TO Exter            | 3        | 5      | 1.39%   |
| Unknown             | 2        | 2      | 0.93%   |
| Maxtor              | 1        | 4      | 0.46%   |
| JMicron Technology  | 1        | 1      | 0.46%   |
| Hewlett-Packard     | 1        | 1      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 36       | 64     | 26.28%  |
| PNY                 | 15       | 50     | 10.95%  |
| Crucial             | 11       | 20     | 8.03%   |
| Samsung Electronics | 10       | 18     | 7.3%    |
| Apacer              | 7        | 12     | 5.11%   |
| SanDisk             | 6        | 9      | 4.38%   |
| Intel               | 6        | 10     | 4.38%   |
| A-DATA Technology   | 6        | 7      | 4.38%   |
| China               | 4        | 4      | 2.92%   |
| WDC                 | 3        | 3      | 2.19%   |
| Verbatim            | 2        | 3      | 1.46%   |
| Transcend           | 2        | 3      | 1.46%   |
| SPCC                | 2        | 2      | 1.46%   |
| Plextor             | 2        | 2      | 1.46%   |
| OCZ                 | 2        | 7      | 1.46%   |
| Micron Technology   | 2        | 6      | 1.46%   |
| KIOXIA-EXCERIA      | 2        | 4      | 1.46%   |
| External            | 2        | 2      | 1.46%   |
| AGI                 | 2        | 2      | 1.46%   |
| sk600               | 1        | 1      | 0.73%   |
| SK hynix            | 1        | 1      | 0.73%   |
| Seagate             | 1        | 1      | 0.73%   |
| SATAFIRM            | 1        | 1      | 0.73%   |
| Pioneer             | 1        | 1      | 0.73%   |
| MAXSUN              | 1        | 1      | 0.73%   |
| LITEON              | 1        | 1      | 0.73%   |
| KingSpec            | 1        | 1      | 0.73%   |
| KimMiDi             | 1        | 1      | 0.73%   |
| Hikvision           | 1        | 2      | 0.73%   |
| Hewlett-Packard     | 1        | 1      | 0.73%   |
| GAMER               | 1        | 1      | 0.73%   |
| FORESEE             | 1        | 1      | 0.73%   |
| Colorful            | 1        | 1      | 0.73%   |
| ASMT                | 1        | 2      | 0.73%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 160      | 417    | 47.76%  |
| SSD     | 107      | 245    | 31.94%  |
| NVMe    | 60       | 126    | 17.91%  |
| Unknown | 6        | 9      | 1.79%   |
| MMC     | 2        | 2      | 0.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 190      | 648    | 70.9%   |
| NVMe | 60       | 125    | 22.39%  |
| SAS  | 16       | 24     | 5.97%   |
| MMC  | 2        | 2      | 0.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 143      | 306    | 49.48%  |
| 0.51-1.0   | 83       | 182    | 28.72%  |
| 1.01-2.0   | 42       | 124    | 14.53%  |
| 3.01-4.0   | 10       | 20     | 3.46%   |
| 4.01-10.0  | 5        | 12     | 1.73%   |
| 2.01-3.0   | 4        | 6      | 1.38%   |
| 10.01-20.0 | 2        | 12     | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 52       | 23.21%  |
| 501-1000       | 39       | 17.41%  |
| 251-500        | 33       | 14.73%  |
| 1001-2000      | 23       | 10.27%  |
| More than 3000 | 18       | 8.04%   |
| 1-20           | 18       | 8.04%   |
| 51-100         | 15       | 6.7%    |
| Unknown        | 10       | 4.46%   |
| 21-50          | 9        | 4.02%   |
| 2001-3000      | 7        | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 92       | 38.82%  |
| 21-50          | 29       | 12.24%  |
| 101-250        | 27       | 11.39%  |
| 51-100         | 26       | 10.97%  |
| 251-500        | 16       | 6.75%   |
| 501-1000       | 14       | 5.91%   |
| 1001-2000      | 11       | 4.64%   |
| Unknown        | 10       | 4.22%   |
| More than 3000 | 9        | 3.8%    |
| 2001-3000      | 3        | 1.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB       | 7        | 7      | 23.33%  |
| Seagate ST3500414CS 500GB          | 2        | 3      | 6.67%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 2      | 6.67%   |
| WDC WD800AAJS-00PSA0 80GB          | 1        | 1      | 3.33%   |
| WDC WD5000AAKX-753CA1 500GB        | 1        | 1      | 3.33%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 1      | 3.33%   |
| WDC WD5000AADS-00S9B0 500GB        | 1        | 1      | 3.33%   |
| WDC WD10EZEX-60WN4A0 1TB           | 1        | 1      | 3.33%   |
| Toshiba MQ01ABD100 1TB             | 1        | 1      | 3.33%   |
| Toshiba DT01ACA100 1TB             | 1        | 1      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 3.33%   |
| Seagate ST380211AS 80GB            | 1        | 1      | 3.33%   |
| Seagate ST3320620A 320GB           | 1        | 1      | 3.33%   |
| Seagate ST31000524AS 1TB           | 1        | 1      | 3.33%   |
| Seagate ST31000322CS 1TB           | 1        | 1      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 3.33%   |
| Samsung Electronics HM160HI 160GB  | 1        | 1      | 3.33%   |
| Kingston SV300S37A120G 120GB SSD   | 1        | 1      | 3.33%   |
| Intel SSDSCKKW120H6 120GB          | 1        | 1      | 3.33%   |
| Hitachi HDS721680PLA380 80GB       | 1        | 1      | 3.33%   |
| Hitachi HDS721050CLA362 500GB      | 1        | 1      | 3.33%   |
| Hewlett-Packard SSD S700 120GB     | 1        | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 41.38%  |
| Seagate             | 9        | 11     | 31.03%  |
| Toshiba             | 2        | 2      | 6.9%    |
| Hitachi             | 2        | 2      | 6.9%    |
| Samsung Electronics | 1        | 1      | 3.45%   |
| Kingston            | 1        | 1      | 3.45%   |
| Intel               | 1        | 1      | 3.45%   |
| Hewlett-Packard     | 1        | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 46.15%  |
| Seagate             | 9        | 11     | 34.62%  |
| Toshiba             | 2        | 2      | 7.69%   |
| Hitachi             | 2        | 2      | 7.69%   |
| Samsung Electronics | 1        | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 28     | 89.66%  |
| SSD  | 3        | 3      | 10.34%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 117      | 399    | 48.75%  |
| Works    | 94       | 369    | 39.17%  |
| Malfunc  | 29       | 31     | 12.08%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 143      | 47.99%  |
| AMD                         | 57       | 19.13%  |
| Phison Electronics          | 18       | 6.04%   |
| Kingston Technology Company | 13       | 4.36%   |
| ASMedia Technology          | 11       | 3.69%   |
| ADATA Technology            | 10       | 3.36%   |
| Samsung Electronics         | 9        | 3.02%   |
| Sandisk                     | 6        | 2.01%   |
| Silicon Motion              | 5        | 1.68%   |
| Nvidia                      | 4        | 1.34%   |
| Marvell Technology Group    | 4        | 1.34%   |
| JMicron Technology          | 4        | 1.34%   |
| Micron Technology           | 3        | 1.01%   |
| Broadcom / LSI              | 3        | 1.01%   |
| SK hynix                    | 1        | 0.34%   |
| Silicon Image               | 1        | 0.34%   |
| Realtek Semiconductor       | 1        | 0.34%   |
| Micron/Crucial Technology   | 1        | 0.34%   |
| MAXIO Technology (Hangzhou) | 1        | 0.34%   |
| LSI Logic / Symbios Logic   | 1        | 0.34%   |
| Lite-On IT Corp. / Plextor  | 1        | 0.34%   |
| KIOXIA                      | 1        | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 35       | 9.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 21       | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 18       | 4.7%    |
| AMD 400 Series Chipset SATA Controller                                         | 12       | 3.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11       | 2.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 11       | 2.87%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10       | 2.61%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 10       | 2.61%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 10       | 2.61%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 10       | 2.61%   |
| Intel SATA Controller [RAID mode]                                              | 9        | 2.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 9        | 2.35%   |
| AMD 500 Series Chipset SATA Controller                                         | 9        | 2.35%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 8        | 2.09%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 8        | 2.09%   |
| Phison E12 NVMe Controller                                                     | 7        | 1.83%   |
| AMD FCH SATA Controller D                                                      | 6        | 1.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 1.31%   |
| Kingston Company DC1000B NVMe SSD E12DC                                        | 5        | 1.31%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 1.31%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5        | 1.31%   |
| Intel 82Q35 Express PT IDER Controller                                         | 5        | 1.31%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 5        | 1.31%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4        | 1.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4        | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 1.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 4        | 1.04%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 4        | 1.04%   |
| AMD X370 Series Chipset SATA Controller                                        | 4        | 1.04%   |
| AMD 600 Series Chipset SATA Controller                                         | 4        | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 0.78%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 0.78%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3        | 0.78%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 3        | 0.78%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 3        | 0.78%   |
| ASMedia ASM1064 Serial ATA Controller                                          | 3        | 0.78%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 0.78%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.52%   |
| Nvidia MCP61 SATA Controller                                                   | 2        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 159      | 55.02%  |
| NVMe | 60       | 20.76%  |
| IDE  | 49       | 16.96%  |
| RAID | 17       | 5.88%   |
| SAS  | 4        | 1.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 146      | 70.53%  |
| AMD    | 61       | 29.47%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium CPU G620 @ 2.60GHz            | 9        | 4.31%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 8        | 3.83%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 7        | 3.35%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 5        | 2.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 1.91%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 1.91%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1.91%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 4        | 1.91%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 1.91%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 1.91%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 1.91%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 3        | 1.44%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 1.44%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 1.44%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 1.44%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 1.44%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.44%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 2        | 0.96%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 0.96%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.96%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.96%   |
| Intel Core i5-4670 CPU @ 3.40GHz            | 2        | 0.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.96%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 0.96%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 0.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.96%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 2        | 0.96%   |
| Intel 12th Gen Core i7-12700                | 2        | 0.96%   |
| Intel 12th Gen Core i5-12400F               | 2        | 0.96%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 0.96%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 2        | 0.96%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 0.96%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 2        | 0.96%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 0.96%   |
| AMD Ryzen 5 5600 6-Core Processor           | 2        | 0.96%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 0.96%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 40       | 19.14%  |
| Intel Core i3           | 27       | 12.92%  |
| AMD Ryzen 5             | 19       | 9.09%   |
| Intel Pentium           | 16       | 7.66%   |
| Intel Core i7           | 15       | 7.18%   |
| Intel Core 2 Duo        | 13       | 6.22%   |
| Other                   | 11       | 5.26%   |
| AMD Ryzen 7             | 11       | 5.26%   |
| AMD Ryzen 9             | 10       | 4.78%   |
| Intel Xeon              | 9        | 4.31%   |
| Intel Core 2 Quad       | 6        | 2.87%   |
| AMD Ryzen 3             | 5        | 2.39%   |
| Intel Pentium Dual-Core | 3        | 1.44%   |
| Intel Celeron           | 3        | 1.44%   |
| AMD Ryzen Threadripper  | 3        | 1.44%   |
| Intel Atom              | 2        | 0.96%   |
| AMD FX                  | 2        | 0.96%   |
| AMD Athlon 64 X2        | 2        | 0.96%   |
| AMD A10                 | 2        | 0.96%   |
| Intel Pentium Dual      | 1        | 0.48%   |
| Intel Core i9           | 1        | 0.48%   |
| AMD Ryzen Embedded      | 1        | 0.48%   |
| AMD Ryzen 5 PRO         | 1        | 0.48%   |
| AMD Phenom II X6        | 1        | 0.48%   |
| AMD Phenom II X4        | 1        | 0.48%   |
| AMD EPYC                | 1        | 0.48%   |
| AMD Athlon X2           | 1        | 0.48%   |
| AMD Athlon              | 1        | 0.48%   |
| AMD A6                  | 1        | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 78       | 37.32%  |
| 2      | 64       | 30.62%  |
| 6      | 31       | 14.83%  |
| 8      | 13       | 6.22%   |
| 16     | 12       | 5.74%   |
| 12     | 5        | 2.39%   |
| 10     | 2        | 0.96%   |
| 36     | 1        | 0.48%   |
| 32     | 1        | 0.48%   |
| 28     | 1        | 0.48%   |
| 3      | 1        | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 205      | 99.03%  |
| 2      | 2        | 0.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 108      | 51.67%  |
| 1      | 101      | 48.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 207      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 73       | 32.74%  |
| 0x306c3    | 23       | 10.31%  |
| 0x206a7    | 15       | 6.73%   |
| 0x306a9    | 13       | 5.83%   |
| 0x1067a    | 12       | 5.38%   |
| 0x506e3    | 6        | 2.69%   |
| 0x08108109 | 6        | 2.69%   |
| 0x90672    | 5        | 2.24%   |
| 0x08701021 | 5        | 2.24%   |
| 0x6fb      | 4        | 1.79%   |
| 0x906ea    | 3        | 1.35%   |
| 0x6fd      | 3        | 1.35%   |
| 0x0a601203 | 3        | 1.35%   |
| 0x0a20120a | 3        | 1.35%   |
| 0xa0671    | 2        | 0.9%    |
| 0xa0655    | 2        | 0.9%    |
| 0xa0653    | 2        | 0.9%    |
| 0x906e9    | 2        | 0.9%    |
| 0x10676    | 2        | 0.9%    |
| 0x0a201025 | 2        | 0.9%    |
| 0x0830104d | 2        | 0.9%    |
| 0x0800820d | 2        | 0.9%    |
| 0x906eb    | 1        | 0.45%   |
| 0x506f1    | 1        | 0.45%   |
| 0x506c9    | 1        | 0.45%   |
| 0x406f1    | 1        | 0.45%   |
| 0x406c4    | 1        | 0.45%   |
| 0x406c3    | 1        | 0.45%   |
| 0x306f2    | 1        | 0.45%   |
| 0x206d7    | 1        | 0.45%   |
| 0x20652    | 1        | 0.45%   |
| 0x106a5    | 1        | 0.45%   |
| 0x0a601206 | 1        | 0.45%   |
| 0x0a50000f | 1        | 0.45%   |
| 0x0a50000d | 1        | 0.45%   |
| 0x0a50000b | 1        | 0.45%   |
| 0x0a404102 | 1        | 0.45%   |
| 0x0a20120e | 1        | 0.45%   |
| 0x0a201016 | 1        | 0.45%   |
| 0x0a201009 | 1        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 30       | 14.42%  |
| IvyBridge        | 26       | 12.5%   |
| SandyBridge      | 19       | 9.13%   |
| Penryn           | 17       | 8.17%   |
| Zen 3            | 16       | 7.69%   |
| Zen 2            | 12       | 5.77%   |
| Unknown          | 11       | 5.29%   |
| Zen+             | 10       | 4.81%   |
| Skylake          | 10       | 4.81%   |
| KabyLake         | 9        | 4.33%   |
| Zen              | 8        | 3.85%   |
| Core             | 8        | 3.85%   |
| CometLake        | 7        | 3.37%   |
| Alderlake Hybrid | 5        | 2.4%    |
| K10              | 3        | 1.44%   |
| Westmere         | 2        | 0.96%   |
| Silvermont       | 2        | 0.96%   |
| Piledriver       | 2        | 0.96%   |
| K8 Hammer        | 2        | 0.96%   |
| Goldmont         | 2        | 0.96%   |
| Steamroller      | 1        | 0.48%   |
| Nehalem          | 1        | 0.48%   |
| K10 Llano        | 1        | 0.48%   |
| Icelake          | 1        | 0.48%   |
| Gracemont        | 1        | 0.48%   |
| Excavator        | 1        | 0.48%   |
| Broadwell        | 1        | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 88       | 39.29%  |
| Intel             | 74       | 33.04%  |
| AMD               | 59       | 26.34%  |
| ASPEED Technology | 3        | 1.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 17       | 7.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13       | 5.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10       | 4.35%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 8        | 3.48%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 7        | 3.04%   |
| Intel HD Graphics 530                                                                    | 6        | 2.61%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 2.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6        | 2.61%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 5        | 2.17%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5        | 2.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 2.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5        | 2.17%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4        | 1.74%   |
| AMD Raphael                                                                              | 4        | 1.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3        | 1.3%    |
| Nvidia GM206 [GeForce GTX 950]                                                           | 3        | 1.3%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3        | 1.3%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3        | 1.3%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 1.3%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 3        | 1.3%    |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 3        | 1.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 1.3%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 3        | 1.3%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 1.3%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 3        | 1.3%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 3        | 1.3%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 1.3%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2        | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 0.87%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 2        | 0.87%   |
| Nvidia GT218 [GeForce G210]                                                              | 2        | 0.87%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2        | 0.87%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 2        | 0.87%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2        | 0.87%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.87%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 0.87%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 0.87%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 80       | 38.28%  |
| 1 x Intel            | 63       | 30.14%  |
| 1 x AMD              | 53       | 25.36%  |
| Nvidia + ASPEED      | 3        | 1.44%   |
| Intel + Nvidia       | 3        | 1.44%   |
| AMD + Nvidia         | 3        | 1.44%   |
| Other                | 1        | 0.48%   |
| 2 x AMD + 3 x Nvidia | 1        | 0.48%   |
| 2 x AMD              | 1        | 0.48%   |
| Intel + AMD          | 1        | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 159      | 74.3%   |
| Proprietary | 41       | 19.16%  |
| Unknown     | 14       | 6.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 99       | 45.62%  |
| 1.01-2.0   | 33       | 15.21%  |
| 0.51-1.0   | 25       | 11.52%  |
| 7.01-8.0   | 18       | 8.29%   |
| 0.01-0.5   | 14       | 6.45%   |
| 3.01-4.0   | 12       | 5.53%   |
| 5.01-6.0   | 6        | 2.76%   |
| 8.01-16.0  | 6        | 2.76%   |
| 2.01-3.0   | 3        | 1.38%   |
| 32.01-64.0 | 1        | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 40       | 19.05%  |
| Acer                 | 22       | 10.48%  |
| Samsung Electronics  | 20       | 9.52%   |
| Goldstar             | 19       | 9.05%   |
| BenQ                 | 19       | 9.05%   |
| Hewlett-Packard      | 16       | 7.62%   |
| AOC                  | 15       | 7.14%   |
| Philips              | 8        | 3.81%   |
| ViewSonic            | 7        | 3.33%   |
| Lenovo               | 6        | 2.86%   |
| ASUSTek Computer     | 5        | 2.38%   |
| Sharp                | 4        | 1.9%    |
| Denver               | 3        | 1.43%   |
| Toshiba              | 2        | 0.95%   |
| Panasonic            | 2        | 0.95%   |
| MSI                  | 2        | 0.95%   |
| LG Electronics       | 2        | 0.95%   |
| Unknown              | 2        | 0.95%   |
| Unknown              | 1        | 0.48%   |
| NCS                  | 1        | 0.48%   |
| MSG                  | 1        | 0.48%   |
| Mi                   | 1        | 0.48%   |
| Lenovo Group Limited | 1        | 0.48%   |
| IPS                  | 1        | 0.48%   |
| HUYINIUDA            | 1        | 0.48%   |
| GAOMON               | 1        | 0.48%   |
| Fujitsu Siemens      | 1        | 0.48%   |
| Envision Peripherals | 1        | 0.48%   |
| Eizo                 | 1        | 0.48%   |
| Dinner               | 1        | 0.48%   |
| CVT                  | 1        | 0.48%   |
| CMT                  | 1        | 0.48%   |
| AOpen                | 1        | 0.48%   |
| AGO                  | 1        | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 8        | 3.51%   |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                  | 6        | 2.63%   |
| Dell E2720HS DELA15E 1920x1080 598x336mm 27.0-inch                | 4        | 1.75%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                 | 4        | 1.75%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch | 3        | 1.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 3        | 1.32%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                | 3        | 1.32%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch               | 3        | 1.32%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch           | 3        | 1.32%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                 | 3        | 1.32%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch  | 2        | 0.88%   |
| Hewlett-Packard LCD Monitor P221                                  | 2        | 0.88%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch           | 2        | 0.88%   |
| Denver LM27-E230C LHCFFFF 1920x1080 598x336mm 27.0-inch           | 2        | 0.88%   |
| Dell LCD Monitor E2720HS 1920x1080                                | 2        | 0.88%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                 | 2        | 0.88%   |
| BenQ LCD Monitor GW2270 1920x1080                                 | 2        | 0.88%   |
| ASUSTek Computer XG32VQR AUS32B2 2560x1440 697x393mm 31.5-inch    | 2        | 0.88%   |
| AOC LCD Monitor 936W 1366x768                                     | 2        | 0.88%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                     | 2        | 0.88%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                   | 2        | 0.88%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                    | 2        | 0.88%   |
| Acer XV240Y P ACR0734 1920x1080 527x296mm 23.8-inch               | 2        | 0.88%   |
| Acer V193HQL ACR027C 1366x768 410x230mm 18.5-inch                 | 2        | 0.88%   |
| Unknown                                                           | 2        | 0.88%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch     | 1        | 0.44%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch         | 1        | 0.44%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch         | 1        | 0.44%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch     | 1        | 0.44%   |
| ViewSonic VA2732-FHD VSC0D3A 1920x1080 598x336mm 27.0-inch        | 1        | 0.44%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch        | 1        | 0.44%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch      | 1        | 0.44%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                             | 1        | 0.44%   |
| Toshiba TV TSB0113 1920x1080 1220x680mm 55.0-inch                 | 1        | 0.44%   |
| Toshiba Crystal View LCD0001 1920x1080 408x255mm 18.9-inch        | 1        | 0.44%   |
| Sharp LCD SHP10C9 1920x540                                        | 1        | 0.44%   |
| Sharp LCD SHP10A2 1360x768                                        | 1        | 0.44%   |
| Sharp LC-22LE420M SHP2242 1920x1080 477x268mm 21.5-inch           | 1        | 0.44%   |
| Sharp HDMI SHP10A1 1360x768 700x390mm 31.5-inch                   | 1        | 0.44%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch | 1        | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 91       | 43.54%  |
| 3840x2160 (4K)     | 20       | 9.57%   |
| 1366x768 (WXGA)    | 20       | 9.57%   |
| 1600x900 (HD+)     | 16       | 7.66%   |
| 2560x1440 (QHD)    | 11       | 5.26%   |
| 1440x900 (WXGA+)   | 8        | 3.83%   |
| 2560x1080          | 6        | 2.87%   |
| 1680x1050 (WSXGA+) | 6        | 2.87%   |
| 1360x768           | 6        | 2.87%   |
| Unknown            | 5        | 2.39%   |
| 1920x1200 (WUXGA)  | 3        | 1.44%   |
| 1280x1024 (SXGA)   | 3        | 1.44%   |
| 5760x1080          | 2        | 0.96%   |
| 3440x1440          | 2        | 0.96%   |
| 1600x1200          | 2        | 0.96%   |
| 5440x1080          | 1        | 0.48%   |
| 5120x1440          | 1        | 0.48%   |
| 3840x1080          | 1        | 0.48%   |
| 3120x1600          | 1        | 0.48%   |
| 1920x540           | 1        | 0.48%   |
| 1280x960           | 1        | 0.48%   |
| 1280x720 (HD)      | 1        | 0.48%   |
| 1024x768 (XGA)     | 1        | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 28       | 13.27%  |
| 23      | 25       | 11.85%  |
| 21      | 25       | 11.85%  |
| 18      | 21       | 9.95%   |
| 27      | 20       | 9.48%   |
| Unknown | 19       | 9%      |
| 19      | 15       | 7.11%   |
| 20      | 14       | 6.64%   |
| 31      | 11       | 5.21%   |
| 22      | 8        | 3.79%   |
| 34      | 6        | 2.84%   |
| 32      | 4        | 1.9%    |
| 17      | 3        | 1.42%   |
| 84      | 2        | 0.95%   |
| 49      | 2        | 0.95%   |
| 12      | 2        | 0.95%   |
| 55      | 1        | 0.47%   |
| 39      | 1        | 0.47%   |
| 28      | 1        | 0.47%   |
| 26      | 1        | 0.47%   |
| 25      | 1        | 0.47%   |
| 15      | 1        | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 80       | 38.83%  |
| 501-600     | 69       | 33.5%   |
| Unknown     | 19       | 9.22%   |
| 601-700     | 14       | 6.8%    |
| 701-800     | 10       | 4.85%   |
| 301-350     | 4        | 1.94%   |
| 1001-1500   | 3        | 1.46%   |
| 351-400     | 2        | 0.97%   |
| 201-300     | 2        | 0.97%   |
| 1501-2000   | 2        | 0.97%   |
| 801-900     | 1        | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 142      | 70.65%  |
| 16/10   | 22       | 10.95%  |
| Unknown | 17       | 8.46%   |
| 21/9    | 7        | 3.48%   |
| 5/4     | 5        | 2.49%   |
| 4/3     | 5        | 2.49%   |
| 32/9    | 3        | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 73       | 35.27%  |
| 151-200        | 36       | 17.39%  |
| 141-150        | 22       | 10.63%  |
| 351-500        | 21       | 10.14%  |
| 301-350        | 20       | 9.66%   |
| Unknown        | 19       | 9.18%   |
| 251-300        | 7        | 3.38%   |
| More than 1000 | 3        | 1.45%   |
| 501-1000       | 3        | 1.45%   |
| 71-80          | 2        | 0.97%   |
| 101-110        | 1        | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 134      | 67.68%  |
| 101-120 | 32       | 16.16%  |
| Unknown | 19       | 9.6%    |
| 121-160 | 6        | 3.03%   |
| 1-50    | 4        | 2.02%   |
| 161-240 | 3        | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 166      | 78.3%   |
| 2     | 24       | 11.32%  |
| 0     | 20       | 9.43%   |
| 3     | 2        | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 119      | 34.39%  |
| Intel                             | 98       | 28.32%  |
| Qualcomm Atheros                  | 26       | 7.51%   |
| TP-Link                           | 22       | 6.36%   |
| Ralink Technology                 | 15       | 4.34%   |
| Broadcom                          | 11       | 3.18%   |
| D-Link                            | 10       | 2.89%   |
| Qualcomm Atheros Communications   | 9        | 2.6%    |
| Xiaomi                            | 6        | 1.73%   |
| Samsung Electronics               | 3        | 0.87%   |
| OPPO Electronics                  | 3        | 0.87%   |
| Nvidia                            | 3        | 0.87%   |
| Broadcom Limited                  | 3        | 0.87%   |
| Aquantia                          | 3        | 0.87%   |
| MediaTek                          | 2        | 0.58%   |
| Tehuti Networks                   | 1        | 0.29%   |
| T & A Mobile Phones               | 1        | 0.29%   |
| Sundance Technology Inc / IC Plus | 1        | 0.29%   |
| Ralink                            | 1        | 0.29%   |
| Qualcomm                          | 1        | 0.29%   |
| Mercucys                          | 1        | 0.29%   |
| Mellanox Technologies             | 1        | 0.29%   |
| InterBiometrics                   | 1        | 0.29%   |
| ICS Advent                        | 1        | 0.29%   |
| D-Link System                     | 1        | 0.29%   |
| Apple                             | 1        | 0.29%   |
| American Megatrends               | 1        | 0.29%   |
| AboCom Systems                    | 1        | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller               | 86       | 22.05%  |
| Realtek RTL8125 2.5GbE Controller                                                    | 14       | 3.59%   |
| TP-Link Archer T4U ver.3                                                             | 9        | 2.31%   |
| Intel 82579V Gigabit Network Connection                                              | 9        | 2.31%   |
| Realtek 802.11ac NIC                                                                 | 8        | 2.05%   |
| Ralink MT7601U Wireless Adapter                                                      | 8        | 2.05%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                                 | 8        | 2.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 7        | 1.79%   |
| Intel I211 Gigabit Network Connection                                                | 7        | 1.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 6        | 1.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 6        | 1.54%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 6        | 1.54%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 6        | 1.54%   |
| Intel Ethernet Controller I225-V                                                     | 6        | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 6        | 1.54%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6        | 1.54%   |
| TP-Link 802.11n NIC                                                                  | 5        | 1.28%   |
| Intel Ethernet Connection I217-LM                                                    | 5        | 1.28%   |
| Intel Ethernet Connection (11) I219-V                                                | 5        | 1.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                       | 4        | 1.03%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 4        | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4        | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 4        | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 4        | 1.03%   |
| Intel Wi-Fi 6 AX200                                                                  | 4        | 1.03%   |
| Intel Ethernet Connection (7) I219-V                                                 | 4        | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 1.03%   |
| Intel 82567LM-3 Gigabit Network Connection                                           | 4        | 1.03%   |
| Intel 82566DM-2 Gigabit Network Connection                                           | 4        | 1.03%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                         | 4        | 1.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 3        | 0.77%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 3        | 0.77%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3        | 0.77%   |
| Intel Ethernet Controller X550                                                       | 3        | 0.77%   |
| Intel Ethernet Connection (2) I219-V                                                 | 3        | 0.77%   |
| Intel Ethernet 10G 2P X520 Adapter                                                   | 3        | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                 | 2        | 0.51%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 2        | 0.51%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 30       | 21.74%  |
| Realtek Semiconductor           | 27       | 19.57%  |
| TP-Link                         | 22       | 15.94%  |
| Ralink Technology               | 15       | 10.87%  |
| Qualcomm Atheros                | 11       | 7.97%   |
| D-Link                          | 10       | 7.25%   |
| Qualcomm Atheros Communications | 9        | 6.52%   |
| Broadcom                        | 7        | 5.07%   |
| MediaTek                        | 2        | 1.45%   |
| Ralink                          | 1        | 0.72%   |
| Mercucys                        | 1        | 0.72%   |
| D-Link System                   | 1        | 0.72%   |
| Broadcom Limited                | 1        | 0.72%   |
| AboCom Systems                  | 1        | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| TP-Link Archer T4U ver.3                                                             | 9        | 6.38%   |
| Realtek 802.11ac NIC                                                                 | 8        | 5.67%   |
| Ralink MT7601U Wireless Adapter                                                      | 8        | 5.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 6        | 4.26%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 6        | 4.26%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 6        | 4.26%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 6        | 4.26%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6        | 4.26%   |
| TP-Link 802.11n NIC                                                                  | 5        | 3.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 4        | 2.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4        | 2.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 4        | 2.84%   |
| Intel Wi-Fi 6 AX200                                                                  | 4        | 2.84%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 2.84%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                         | 4        | 2.84%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 3        | 2.13%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3        | 2.13%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 2        | 1.42%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2        | 1.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 1.42%   |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 1.42%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 2        | 1.42%   |
| Intel Wireless 3165                                                                  | 2        | 1.42%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                    | 2        | 1.42%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 2        | 1.42%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 2        | 1.42%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1        | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 0.71%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                            | 1        | 0.71%   |
| Ralink RT5572 Wireless Adapter                                                       | 1        | 0.71%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                          | 1        | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 1        | 0.71%   |
| Mercucys 802.11n NIC                                                                 | 1        | 0.71%   |
| MediaTek WiFi                                                                        | 1        | 0.71%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 1        | 0.71%   |
| Intel Wireless 8260                                                                  | 1        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 106      | 45.69%  |
| Intel                             | 79       | 34.05%  |
| Qualcomm Atheros                  | 15       | 6.47%   |
| Xiaomi                            | 6        | 2.59%   |
| Broadcom                          | 4        | 1.72%   |
| Samsung Electronics               | 3        | 1.29%   |
| OPPO Electronics                  | 3        | 1.29%   |
| Nvidia                            | 3        | 1.29%   |
| Aquantia                          | 3        | 1.29%   |
| Broadcom Limited                  | 2        | 0.86%   |
| Tehuti Networks                   | 1        | 0.43%   |
| T & A Mobile Phones               | 1        | 0.43%   |
| Sundance Technology Inc / IC Plus | 1        | 0.43%   |
| Qualcomm                          | 1        | 0.43%   |
| Mellanox Technologies             | 1        | 0.43%   |
| ICS Advent                        | 1        | 0.43%   |
| Apple                             | 1        | 0.43%   |
| American Megatrends               | 1        | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 86       | 34.68%  |
| Realtek RTL8125 2.5GbE Controller                                          | 14       | 5.65%   |
| Intel 82579V Gigabit Network Connection                                    | 9        | 3.63%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                       | 8        | 3.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 7        | 2.82%   |
| Intel I211 Gigabit Network Connection                                      | 7        | 2.82%   |
| Intel Ethernet Controller I225-V                                           | 6        | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6        | 2.42%   |
| Intel Ethernet Connection I217-LM                                          | 5        | 2.02%   |
| Intel Ethernet Connection (11) I219-V                                      | 5        | 2.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 4        | 1.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 4        | 1.61%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 1.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 1.61%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 1.61%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 3        | 1.21%   |
| Intel Ethernet Controller X550                                             | 3        | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 1.21%   |
| Intel Ethernet 10G 2P X520 Adapter                                         | 3        | 1.21%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2        | 0.81%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 2        | 0.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 2        | 0.81%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2        | 0.81%   |
| OPPO SM8350-MTP _SN:9338D66C                                               | 2        | 0.81%   |
| Intel I350 Gigabit Fiber Network Connection                                | 2        | 0.81%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 0.81%   |
| Intel Ethernet Connection I217-V                                           | 2        | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 0.81%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 0.81%   |
| Intel 82583V Gigabit Network Connection                                    | 2        | 0.81%   |
| Intel 82562V-2 10/100 Network Connection                                   | 2        | 0.81%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 0.81%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 0.81%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express            | 2        | 0.81%   |
| Tehuti Networks TN9310 10GbE SFP+ Ethernet Adapter                         | 1        | 0.4%    |
| T & A Mobile Phones TCL 20E                                                | 1        | 0.4%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 192      | 60.57%  |
| WiFi     | 124      | 39.12%  |
| Modem    | 1        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 125      | 58.96%  |
| WiFi     | 87       | 41.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 54.5%   |
| 2     | 57       | 27.01%  |
| 3     | 15       | 7.11%   |
| 0     | 14       | 6.64%   |
| 5     | 3        | 1.42%   |
| 4     | 3        | 1.42%   |
| 11    | 1        | 0.47%   |
| 9     | 1        | 0.47%   |
| 8     | 1        | 0.47%   |
| 6     | 1        | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 156      | 72.9%   |
| Yes  | 58       | 27.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 30       | 40.54%  |
| Cambridge Silicon Radio | 23       | 31.08%  |
| Realtek Semiconductor   | 7        | 9.46%   |
| TP-Link                 | 4        | 5.41%   |
| IMC Networks            | 2        | 2.7%    |
| D-Link                  | 2        | 2.7%    |
| Broadcom                | 2        | 2.7%    |
| Apple                   | 2        | 2.7%    |
| MediaTek                | 1        | 1.35%   |
| Foxconn / Hon Hai       | 1        | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23       | 31.08%  |
| Intel AX201 Bluetooth                               | 10       | 13.51%  |
| Realtek Bluetooth Radio                             | 7        | 9.46%   |
| Intel Bluetooth wireless interface                  | 5        | 6.76%   |
| Intel AX210 Bluetooth                               | 5        | 6.76%   |
| Intel AX200 Bluetooth                               | 5        | 6.76%   |
| TP-Link UB500 Adapter                               | 4        | 5.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 2.7%    |
| D-Link DBT-122 Bluetooth adapter                    | 2        | 2.7%    |
| Apple Bluetooth Host Controller                     | 2        | 2.7%    |
| MediaTek Wireless_Device                            | 1        | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.35%   |
| Intel Bluetooth Device                              | 1        | 1.35%   |
| Intel AX211 Bluetooth                               | 1        | 1.35%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.35%   |
| IMC Networks Bluetooth Device                       | 1        | 1.35%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1        | 1.35%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.35%   |
| Broadcom BCM20702A0                                 | 1        | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 137      | 39.14%  |
| Nvidia                                       | 87       | 24.86%  |
| AMD                                          | 79       | 22.57%  |
| Logitech                                     | 7        | 2%      |
| C-Media Electronics                          | 6        | 1.71%   |
| ASUSTek Computer                             | 6        | 1.71%   |
| JMTek                                        | 5        | 1.43%   |
| Texas Instruments                            | 3        | 0.86%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.29%   |
| Yamaha                                       | 1        | 0.29%   |
| XMOS                                         | 1        | 0.29%   |
| TX                                           | 1        | 0.29%   |
| Tenx Technology                              | 1        | 0.29%   |
| SteelSeries ApS                              | 1        | 0.29%   |
| Setek Elektronik                             | 1        | 0.29%   |
| RODE Microphones                             | 1        | 0.29%   |
| Realtek Semiconductor                        | 1        | 0.29%   |
| Razer USA                                    | 1        | 0.29%   |
| GYROCOM C&C                                  | 1        | 0.29%   |
| GN Netcom                                    | 1        | 0.29%   |
| Generalplus Technology                       | 1        | 0.29%   |
| FiiO Electronics Technology                  | 1        | 0.29%   |
| DCMT Technology                              | 1        | 0.29%   |
| Creative Technology                          | 1        | 0.29%   |
| Creative Labs                                | 1        | 0.29%   |
| Cooler Master                                | 1        | 0.29%   |
| BR25                                         | 1        | 0.29%   |
| Barco Display Systems                        | 1        | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 21       | 5.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 20       | 5.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 20       | 5.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 20       | 5.03%   |
| AMD Family 17h/19h HD Audio Controller                                            | 18       | 4.52%   |
| Nvidia GF108 High Definition Audio Controller                                     | 14       | 3.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14       | 3.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 11       | 2.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 11       | 2.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 10       | 2.51%   |
| Nvidia GA106 High Definition Audio Controller                                     | 9        | 2.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 9        | 2.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8        | 2.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 8        | 2.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 7        | 1.76%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 6        | 1.51%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 6        | 1.51%   |
| Nvidia TU106 High Definition Audio Controller                                     | 5        | 1.26%   |
| JMTek USB PnP Audio Device                                                        | 5        | 1.26%   |
| Intel Cannon Lake PCH cAVS                                                        | 5        | 1.26%   |
| Intel Alder Lake-S HD Audio Controller                                            | 5        | 1.26%   |
| ASUSTek Computer USB Audio                                                        | 5        | 1.26%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 5        | 1.26%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5        | 1.26%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 1.01%   |
| Nvidia High Definition Audio Controller                                           | 4        | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4        | 1.01%   |
| Nvidia GM204 High Definition Audio Controller                                     | 4        | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 1.01%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4        | 1.01%   |
| Logitech H600 [Wireless Headset]                                                  | 4        | 1.01%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 1.01%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 1.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4        | 1.01%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 4        | 1.01%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3        | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 0.75%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 0.75%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 42       | 33.33%  |
| Corsair             | 24       | 19.05%  |
| Unknown             | 11       | 8.73%   |
| SK hynix            | 9        | 7.14%   |
| Samsung Electronics | 7        | 5.56%   |
| Micron Technology   | 4        | 3.17%   |
| Kingmax             | 4        | 3.17%   |
| PNY                 | 3        | 2.38%   |
| A-DATA Technology   | 3        | 2.38%   |
| Team                | 2        | 1.59%   |
| Ramaxel Technology  | 2        | 1.59%   |
| Kimtigo             | 2        | 1.59%   |
| G.Skill             | 2        | 1.59%   |
| Unknown             | 2        | 1.59%   |
| Unknown (ABCD)      | 1        | 0.79%   |
| Silicon Power       | 1        | 0.79%   |
| SemsoTai            | 1        | 0.79%   |
| Patriot Memory      | 1        | 0.79%   |
| MAXSUN              | 1        | 0.79%   |
| Lexar               | 1        | 0.79%   |
| Kinlstuo            | 1        | 0.79%   |
| Crucial             | 1        | 0.79%   |
| Apacer              | 1        | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s          | 6        | 4.29%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3600MT/s       | 6        | 4.29%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s        | 5        | 3.57%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 4        | 2.86%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s        | 4        | 2.86%   |
| Kingmax RAM FLFE85F-C8KL9 2GB DIMM DDR3 1333MT/s             | 3        | 2.14%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 2        | 1.43%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 2        | 1.43%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s          | 2        | 1.43%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s          | 2        | 1.43%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s         | 2        | 1.43%   |
| Kingston RAM KF552C36-16 16GB DIMM DDR5 5200MT/s             | 2        | 1.43%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s        | 2        | 1.43%   |
| Kingston RAM 99U5471-050.A00LF 8GB DIMM DDR3 1600MT/s        | 2        | 1.43%   |
| Kingmax RAM FLFE85F-C8KM9 2048MB DIMM 1333MT/s               | 2        | 1.43%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s               | 2        | 1.43%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                  | 2        | 1.43%   |
| Unknown                                                      | 2        | 1.43%   |
| Unknown RAM Module 8GB DIMM 667MT/s                          | 1        | 0.71%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s                 | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                    | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM 667MT/s                          | 1        | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 0.71%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s           | 1        | 0.71%   |
| Team RAM Elite-800 2GB DIMM SDRAM 2048MT/s                   | 1        | 0.71%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                | 1        | 0.71%   |
| SK hynix RAM HYMP112F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s  | 1        | 0.71%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s         | 1        | 0.71%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.71%   |
| SK hynix RAM HMA84GR7CJR4N-XN 32GB DIMM DDR4 3200MT/s        | 1        | 0.71%   |
| SK hynix RAM HMA82GR7CJR4N-VK 16384MB DIMM DDR4 2666MT/s     | 1        | 0.71%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1        | 0.71%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s         | 1        | 0.71%   |
| Silicon Power RAM DBLT2GN568S 2GB DIMM DDR3 1333MT/s         | 1        | 0.71%   |
| SemsoTai RAM Module 8GB DIMM DDR4 2667MT/s                   | 1        | 0.71%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1        | 0.71%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s     | 1        | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 52       | 43.7%   |
| DDR3    | 37       | 31.09%  |
| SDRAM   | 15       | 12.61%  |
| DDR5    | 5        | 4.2%    |
| DDR2    | 5        | 4.2%    |
| Unknown | 3        | 2.52%   |
| LPDDR4  | 1        | 0.84%   |
| DRAM    | 1        | 0.84%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 110      | 94.02%  |
| SODIMM  | 6        | 5.13%   |
| FB-DIMM | 1        | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 53       | 43.44%  |
| 2048  | 18       | 14.75%  |
| 32768 | 17       | 13.93%  |
| 16384 | 17       | 13.93%  |
| 4096  | 16       | 13.11%  |
| 1024  | 1        | 0.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 31       | 24.8%   |
| 3200    | 14       | 11.2%   |
| 3600    | 11       | 8.8%    |
| 2400    | 8        | 6.4%    |
| 1333    | 7        | 5.6%    |
| 2667    | 6        | 4.8%    |
| 667     | 5        | 4%      |
| Unknown | 5        | 4%      |
| 3933    | 4        | 3.2%    |
| 800     | 4        | 3.2%    |
| 5200    | 3        | 2.4%    |
| 3733    | 3        | 2.4%    |
| 2133    | 3        | 2.4%    |
| 1800    | 3        | 2.4%    |
| 4800    | 2        | 1.6%    |
| 2666    | 2        | 1.6%    |
| 1867    | 2        | 1.6%    |
| 1866    | 2        | 1.6%    |
| 1066    | 2        | 1.6%    |
| 3666    | 1        | 0.8%    |
| 3534    | 1        | 0.8%    |
| 3466    | 1        | 0.8%    |
| 3400    | 1        | 0.8%    |
| 3000    | 1        | 0.8%    |
| 2933    | 1        | 0.8%    |
| 2048    | 1        | 0.8%    |
| 1067    | 1        | 0.8%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 27.27%  |
| Brother Industries  | 3        | 27.27%  |
| Hewlett-Packard     | 2        | 18.18%  |
| Seiko Epson         | 1        | 9.09%   |
| Prolific Technology | 1        | 9.09%   |
| Canon               | 1        | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung SCX-3400 Series       | 3        | 27.27%  |
| Seiko Epson L312 Series       | 1        | 9.09%   |
| Prolific PL2305 Parallel Port | 1        | 9.09%   |
| HP Ink Tank 110 series        | 1        | 9.09%   |
| HP DeskJet F4200 series       | 1        | 9.09%   |
| Canon E410 series             | 1        | 9.09%   |
| Brother MFC-1910W             | 1        | 9.09%   |
| Brother DCP-J105              | 1        | 9.09%   |
| Brother DCP-1610W             | 1        | 9.09%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 12       | 40%     |
| Microdia                      | 3        | 10%     |
| Generalplus Technology        | 3        | 10%     |
| YGTek                         | 2        | 6.67%   |
| Genesys Logic                 | 2        | 6.67%   |
| Apple                         | 2        | 6.67%   |
| WCM_USB                       | 1        | 3.33%   |
| Sunplus Innovation Technology | 1        | 3.33%   |
| Realtek Semiconductor         | 1        | 3.33%   |
| Lenovo                        | 1        | 3.33%   |
| Jieli Technology              | 1        | 3.33%   |
| ARC International             | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 4        | 13.33%  |
| YGTek Webcam                          | 2        | 6.67%   |
| Microdia USB 2.0 Camera               | 2        | 6.67%   |
| Logitech Webcam C170                  | 2        | 6.67%   |
| Genesys Logic Camera                  | 2        | 6.67%   |
| Generalplus 808 Camera                | 2        | 6.67%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X       | 2        | 6.67%   |
| WCM_USB WEB CAM                       | 1        | 3.33%   |
| Sunplus Full HD webcam                | 1        | 3.33%   |
| Realtek HP High Definition 1MP Webcam | 1        | 3.33%   |
| Microdia Camera                       | 1        | 3.33%   |
| Logitech Webcam C310                  | 1        | 3.33%   |
| Logitech Webcam C250                  | 1        | 3.33%   |
| Logitech Webcam B500                  | 1        | 3.33%   |
| Logitech HD Webcam C510               | 1        | 3.33%   |
| Logitech HD Pro Webcam C920           | 1        | 3.33%   |
| Logitech C920 PRO HD Webcam           | 1        | 3.33%   |
| Lenovo FHD Webcam                     | 1        | 3.33%   |
| Jieli USB PHY 2.0                     | 1        | 3.33%   |
| Generalplus CAMERA - UVC              | 1        | 3.33%   |
| ARC International Camera              | 1        | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 173      | 79.72%  |
| 1     | 41       | 18.89%  |
| 6     | 1        | 0.46%   |
| 3     | 1        | 0.46%   |
| 2     | 1        | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 22       | 47.83%  |
| Net/wireless             | 13       | 28.26%  |
| Communication controller | 4        | 8.7%    |
| Unassigned class         | 3        | 6.52%   |
| Sound                    | 2        | 4.35%   |
| Storage/ide              | 1        | 2.17%   |
| Network                  | 1        | 2.17%   |

