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

Total: 302

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 30       | 14.42%  |
| Debian 11                    | 15       | 7.21%   |
| Ubuntu 22.04                 | 10       | 4.81%   |
| Ubuntu 18.04                 | 9        | 4.33%   |
| Zorin 16                     | 8        | 3.85%   |
| OpenMandriva 4.3             | 8        | 3.85%   |
| OpenMandriva 23.03           | 7        | 3.37%   |
| OpenMandriva 4.2             | 6        | 2.88%   |
| Pop!_OS 22.04                | 5        | 2.4%    |
| Pop!_OS 20.04                | 5        | 2.4%    |
| OpenMandriva 4.50            | 5        | 2.4%    |
| ArcoLinux Rolling            | 5        | 2.4%    |
| Ubuntu 19.04                 | 4        | 1.92%   |
| OpenMandriva 23.08           | 4        | 1.92%   |
| OpenMandriva 23.01           | 4        | 1.92%   |
| Xubuntu 18.04                | 3        | 1.44%   |
| Linux Mint 19.3              | 3        | 1.44%   |
| Fedora 37                    | 3        | 1.44%   |
| Fedora 33                    | 3        | 1.44%   |
| Zorin 15                     | 2        | 0.96%   |
| Ubuntu 23.04                 | 2        | 0.96%   |
| Ubuntu 19.10                 | 2        | 0.96%   |
| Pop!_OS 21.04                | 2        | 0.96%   |
| Pop!_OS 20.10                | 2        | 0.96%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 0.96%   |
| OpenMandriva 23.07           | 2        | 0.96%   |
| Manjaro 21.2.6               | 2        | 0.96%   |
| Linux Mint 20.3              | 2        | 0.96%   |
| KDE neon 22.04               | 2        | 0.96%   |
| KDE neon 20.04               | 2        | 0.96%   |
| Fedora 39                    | 2        | 0.96%   |
| Fedora 34                    | 2        | 0.96%   |
| Debian 12                    | 2        | 0.96%   |
| Arch                         | 2        | 0.96%   |
| Ubuntu MATE 20.04            | 1        | 0.48%   |
| Ubuntu 22.10                 | 1        | 0.48%   |
| Ubuntu 21.10                 | 1        | 0.48%   |
| Ubuntu 21.04                 | 1        | 0.48%   |
| Ubuntu 20.10                 | 1        | 0.48%   |
| SteamOS 3.4                  | 1        | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 58       | 29.44%  |
| OpenMandriva | 33       | 16.75%  |
| Debian       | 18       | 9.14%   |
| Pop!_OS      | 13       | 6.6%    |
| Fedora       | 11       | 5.58%   |
| Zorin        | 10       | 5.08%   |
| Linux Mint   | 10       | 5.08%   |
| Manjaro      | 5        | 2.54%   |
| ArcoLinux    | 5        | 2.54%   |
| KDE neon     | 4        | 2.03%   |
| Xubuntu      | 3        | 1.52%   |
| Lubuntu      | 3        | 1.52%   |
| Endless      | 3        | 1.52%   |
| Elementary   | 3        | 1.52%   |
| Arch         | 3        | 1.52%   |
| openSUSE     | 2        | 1.02%   |
| Kubuntu      | 2        | 1.02%   |
| Kali         | 2        | 1.02%   |
| EndeavourOS  | 2        | 1.02%   |
| Ubuntu MATE  | 1        | 0.51%   |
| SteamOS      | 1        | 0.51%   |
| ROSA         | 1        | 0.51%   |
| Linux Lite   | 1        | 0.51%   |
| Gentoo       | 1        | 0.51%   |
| ChimeraOS    | 1        | 0.51%   |
| CentOS       | 1        | 0.51%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.2.6-desktop-1omv2390        | 8        | 3.4%    |
| 5.10.14-desktop-1omv4002      | 6        | 2.55%   |
| 5.4.0-58-generic              | 5        | 2.13%   |
| 5.16.7-desktop-1omv4003       | 5        | 2.13%   |
| 5.13.19-6-pve                 | 5        | 2.13%   |
| 6.4.11-desktop-1omv2390       | 4        | 1.7%    |
| 5.4.0-42-generic              | 4        | 1.7%    |
| 5.15.108-1-pve                | 4        | 1.7%    |
| 5.4.0-40-generic              | 3        | 1.28%   |
| 5.3.0-53-generic              | 3        | 1.28%   |
| 5.3.0-46-generic              | 3        | 1.28%   |
| 5.16.3-desktop-2omv4050       | 3        | 1.28%   |
| 5.15.126-1-pve                | 3        | 1.28%   |
| 5.15.0-52-generic             | 3        | 1.28%   |
| 5.11.0-27-generic             | 3        | 1.28%   |
| 6.6.7-200.fc39.x86_64         | 2        | 0.85%   |
| 6.3.5-desktop-3omv2390        | 2        | 0.85%   |
| 6.2.6-76060206-generic        | 2        | 0.85%   |
| 6.0.12-76060006-generic       | 2        | 0.85%   |
| 5.8.0-53-generic              | 2        | 0.85%   |
| 5.8.0-44-generic              | 2        | 0.85%   |
| 5.8.0-41-generic              | 2        | 0.85%   |
| 5.4.0-77-generic              | 2        | 0.85%   |
| 5.4.0-7634-generic            | 2        | 0.85%   |
| 5.4.0-48-generic              | 2        | 0.85%   |
| 5.4.0-37-generic              | 2        | 0.85%   |
| 5.4.0-29-generic              | 2        | 0.85%   |
| 5.19.0-46-generic             | 2        | 0.85%   |
| 5.19.0-32-generic             | 2        | 0.85%   |
| 5.15.35-3-pve                 | 2        | 0.85%   |
| 5.15.0-58-generic             | 2        | 0.85%   |
| 5.15.0-39-generic             | 2        | 0.85%   |
| 5.12.7-desktop-clang-1omv4003 | 2        | 0.85%   |
| 5.12.4-desktop-1omv4050       | 2        | 0.85%   |
| 5.12.15-300.fc34.x86_64       | 2        | 0.85%   |
| 5.11.0-41-generic             | 2        | 0.85%   |
| 5.11.0-35-generic             | 2        | 0.85%   |
| 5.11.0-34-generic             | 2        | 0.85%   |
| 5.0.0-27-generic              | 2        | 0.85%   |
| 6.5.7-arch1-1                 | 1        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 33       | 14.93%  |
| 5.15.0   | 15       | 6.79%   |
| 5.11.0   | 12       | 5.43%   |
| 5.8.0    | 11       | 4.98%   |
| 6.2.6    | 10       | 4.52%   |
| 5.3.0    | 8        | 3.62%   |
| 5.19.0   | 7        | 3.17%   |
| 5.0.0    | 7        | 3.17%   |
| 5.10.14  | 6        | 2.71%   |
| 4.15.0   | 6        | 2.71%   |
| 5.16.7   | 5        | 2.26%   |
| 5.13.19  | 5        | 2.26%   |
| 5.13.0   | 5        | 2.26%   |
| 6.4.11   | 4        | 1.81%   |
| 6.2.0    | 4        | 1.81%   |
| 5.15.108 | 4        | 1.81%   |
| 5.16.3   | 3        | 1.36%   |
| 5.15.126 | 3        | 1.36%   |
| 6.6.7    | 2        | 0.9%    |
| 6.5.6    | 2        | 0.9%    |
| 6.3.5    | 2        | 0.9%    |
| 6.2.16   | 2        | 0.9%    |
| 6.1.0    | 2        | 0.9%    |
| 6.0.12   | 2        | 0.9%    |
| 5.18.0   | 2        | 0.9%    |
| 5.17.1   | 2        | 0.9%    |
| 5.15.35  | 2        | 0.9%    |
| 5.12.7   | 2        | 0.9%    |
| 5.12.4   | 2        | 0.9%    |
| 5.12.15  | 2        | 0.9%    |
| 5.10.0   | 2        | 0.9%    |
| 4.18.0   | 2        | 0.9%    |
| 6.5.7    | 1        | 0.45%   |
| 6.5.5    | 1        | 0.45%   |
| 6.4.4    | 1        | 0.45%   |
| 6.4.15   | 1        | 0.45%   |
| 6.4.12   | 1        | 0.45%   |
| 6.4.10   | 1        | 0.45%   |
| 6.3.9    | 1        | 0.45%   |
| 6.3.8    | 1        | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 33       | 15.35%  |
| 5.15    | 30       | 13.95%  |
| 6.2     | 18       | 8.37%   |
| 5.11    | 13       | 6.05%   |
| 5.8     | 11       | 5.12%   |
| 5.16    | 11       | 5.12%   |
| 5.13    | 11       | 5.12%   |
| 5.19    | 9        | 4.19%   |
| 5.10    | 9        | 4.19%   |
| 5.3     | 8        | 3.72%   |
| 6.4     | 7        | 3.26%   |
| 5.0     | 7        | 3.26%   |
| 6.3     | 6        | 2.79%   |
| 5.12    | 6        | 2.79%   |
| 4.15    | 6        | 2.79%   |
| 6.0     | 5        | 2.33%   |
| 6.1     | 4        | 1.86%   |
| 5.18    | 4        | 1.86%   |
| 6.5     | 3        | 1.4%    |
| 5.9     | 3        | 1.4%    |
| 5.17    | 3        | 1.4%    |
| 5.14    | 3        | 1.4%    |
| 6.6     | 2        | 0.93%   |
| 4.18    | 2        | 0.93%   |
| 4.9     | 1        | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 187      | 98.94%  |
| i686   | 2        | 1.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| GNOME        | 82       | 41.41%  |
| KDE5         | 46       | 23.23%  |
| XFCE         | 18       | 9.09%   |
| Unknown      | 15       | 7.58%   |
| Openbox      | 9        | 4.55%   |
| X-Cinnamon   | 8        | 4.04%   |
| MATE         | 6        | 3.03%   |
| LXQt         | 4        | 2.02%   |
| Pantheon     | 3        | 1.52%   |
| KDE          | 3        | 1.52%   |
| LXDE         | 1        | 0.51%   |
| herbstluftwm | 1        | 0.51%   |
| Cinnamon     | 1        | 0.51%   |
| bspwm        | 1        | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 153      | 78.06%  |
| Wayland | 24       | 12.24%  |
| Tty     | 12       | 6.12%   |
| Unknown | 7        | 3.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 90       | 46.39%  |
| SDDM    | 47       | 24.23%  |
| LightDM | 24       | 12.37%  |
| GDM3    | 17       | 8.76%   |
| GDM     | 12       | 6.19%   |
| TDM     | 3        | 1.55%   |
| LXDM    | 1        | 0.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 147      | 76.17%  |
| en_GB   | 15       | 7.77%   |
| Unknown | 10       | 5.18%   |
| en_SG   | 9        | 4.66%   |
| en_AU   | 3        | 1.55%   |
| zh_CN   | 2        | 1.04%   |
| de_DE   | 2        | 1.04%   |
| zh_SG   | 1        | 0.52%   |
| ms_MY   | 1        | 0.52%   |
| en_MY   | 1        | 0.52%   |
| en_HK   | 1        | 0.52%   |
| C       | 1        | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 117      | 60.31%  |
| EFI  | 77       | 39.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 131      | 67.53%  |
| Btrfs   | 20       | 10.31%  |
| Overlay | 19       | 9.79%   |
| Zfs     | 10       | 5.15%   |
| Tmpfs   | 5        | 2.58%   |
| Unknown | 4        | 2.06%   |
| Xfs     | 3        | 1.55%   |
| Ext3    | 1        | 0.52%   |
| Ext2    | 1        | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 89       | 46.35%  |
| GPT     | 75       | 39.06%  |
| MBR     | 28       | 14.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 143      | 72.59%  |
| Yes       | 54       | 27.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 61.14%  |
| Yes       | 75       | 38.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 41       | 21.69%  |
| ASUSTek Computer    | 40       | 21.16%  |
| MSI                 | 22       | 11.64%  |
| Dell                | 21       | 11.11%  |
| Intel               | 17       | 8.99%   |
| Hewlett-Packard     | 9        | 4.76%   |
| Lenovo              | 8        | 4.23%   |
| ASRock              | 8        | 4.23%   |
| Acer                | 7        | 3.7%    |
| Biostar             | 5        | 2.65%   |
| ECS                 | 3        | 1.59%   |
| Unknown             | 2        | 1.06%   |
| Vorke               | 1        | 0.53%   |
| Shuttle             | 1        | 0.53%   |
| Seco                | 1        | 0.53%   |
| ONDA                | 1        | 0.53%   |
| ASRockRack          | 1        | 0.53%   |
| AMI                 | 1        | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Intel DH61WW AAG23116-204           | 8        | 4.23%   |
| ASUS All Series                     | 8        | 4.23%   |
| Gigabyte Z77M-D3H                   | 6        | 3.17%   |
| Gigabyte B85M-D3H                   | 6        | 3.17%   |
| MSI MS-7C52                         | 5        | 2.65%   |
| MSI MS-7817                         | 3        | 1.59%   |
| Intel DH61WW AAG23116-300           | 3        | 1.59%   |
| Gigabyte B450M S2H                  | 3        | 1.59%   |
| Dell OptiPlex 755                   | 3        | 1.59%   |
| MSI MS-7C81                         | 2        | 1.06%   |
| MSI MS-7B89                         | 2        | 1.06%   |
| Intel MAHOBAY                       | 2        | 1.06%   |
| Gigabyte X570 UD                    | 2        | 1.06%   |
| Gigabyte B550 AORUS PRO V2          | 2        | 1.06%   |
| Dell XPS 8940                       | 2        | 1.06%   |
| Dell OptiPlex 990                   | 2        | 1.06%   |
| Dell OptiPlex 7010                  | 2        | 1.06%   |
| Biostar G41D3C                      | 2        | 1.06%   |
| ASUS ROG STRIX X670E-E GAMING WIFI  | 2        | 1.06%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI     | 2        | 1.06%   |
| ASUS P8Z77-V LX                     | 2        | 1.06%   |
| ASRock B550 Pro4                    | 2        | 1.06%   |
| Unknown                             | 2        | 1.06%   |
| Vorke V1 Plus                       | 1        | 0.53%   |
| Shuttle DH170                       | 1        | 0.53%   |
| Seco C40                            | 1        | 0.53%   |
| ONDA H110-MINI V3.00                | 1        | 0.53%   |
| MSI MS-7D99                         | 1        | 0.53%   |
| MSI MS-7D46                         | 1        | 0.53%   |
| MSI MS-7D42                         | 1        | 0.53%   |
| MSI MS-7C37                         | 1        | 0.53%   |
| MSI MS-7C02                         | 1        | 0.53%   |
| MSI MS-7A39                         | 1        | 0.53%   |
| MSI MS-7979                         | 1        | 0.53%   |
| MSI MS-7916                         | 1        | 0.53%   |
| MSI MS-7693                         | 1        | 0.53%   |
| MSI MS-7388                         | 1        | 0.53%   |
| Lenovo ThinkStation S10 6483CTO     | 1        | 0.53%   |
| Lenovo ThinkStation P620 30E0S0E000 | 1        | 0.53%   |
| Lenovo ThinkStation P500 30A6S1B50X | 1        | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 12       | 6.35%   |
| Intel DH61WW        | 11       | 5.82%   |
| ASUS All            | 8        | 4.23%   |
| Gigabyte Z77M-D3H   | 6        | 3.17%   |
| Gigabyte B85M-D3H   | 6        | 3.17%   |
| MSI MS-7C52         | 5        | 2.65%   |
| Lenovo ThinkCentre  | 4        | 2.12%   |
| HP Compaq           | 4        | 2.12%   |
| Gigabyte X570       | 4        | 2.12%   |
| Gigabyte B450M      | 4        | 2.12%   |
| Dell Precision      | 4        | 2.12%   |
| ASUS ROG            | 4        | 2.12%   |
| ASUS PRIME          | 4        | 2.12%   |
| Acer Veriton        | 4        | 2.12%   |
| MSI MS-7817         | 3        | 1.59%   |
| Lenovo ThinkStation | 3        | 1.59%   |
| Dell Inspiron       | 3        | 1.59%   |
| ASUS TUF            | 3        | 1.59%   |
| ASUS P8B75-M        | 3        | 1.59%   |
| Acer Aspire         | 3        | 1.59%   |
| MSI MS-7C81         | 2        | 1.06%   |
| MSI MS-7B89         | 2        | 1.06%   |
| Intel MAHOBAY       | 2        | 1.06%   |
| Gigabyte B550       | 2        | 1.06%   |
| Dell XPS            | 2        | 1.06%   |
| Biostar G41D3C      | 2        | 1.06%   |
| ASUS Pro            | 2        | 1.06%   |
| ASUS P8Z77-V        | 2        | 1.06%   |
| ASRock B550         | 2        | 1.06%   |
| Unknown             | 2        | 1.06%   |
| Vorke V1            | 1        | 0.53%   |
| Shuttle DH170       | 1        | 0.53%   |
| Seco C40            | 1        | 0.53%   |
| ONDA H110-MINI      | 1        | 0.53%   |
| MSI MS-7D99         | 1        | 0.53%   |
| MSI MS-7D46         | 1        | 0.53%   |
| MSI MS-7D42         | 1        | 0.53%   |
| MSI MS-7C37         | 1        | 0.53%   |
| MSI MS-7C02         | 1        | 0.53%   |
| MSI MS-7A39         | 1        | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 29       | 15.34%  |
| 2018 | 20       | 10.58%  |
| 2013 | 17       | 8.99%   |
| 2011 | 15       | 7.94%   |
| 2019 | 13       | 6.88%   |
| 2020 | 11       | 5.82%   |
| 2015 | 11       | 5.82%   |
| 2008 | 11       | 5.82%   |
| 2022 | 10       | 5.29%   |
| 2021 | 10       | 5.29%   |
| 2017 | 10       | 5.29%   |
| 2007 | 9        | 4.76%   |
| 2014 | 7        | 3.7%    |
| 2010 | 7        | 3.7%    |
| 2009 | 6        | 3.17%   |
| 2023 | 1        | 0.53%   |
| 2016 | 1        | 0.53%   |
| 2006 | 1        | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 189      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 182      | 96.3%   |
| Enabled  | 7        | 3.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 189      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 56       | 29.02%  |
| 4.01-8.0    | 35       | 18.13%  |
| 8.01-16.0   | 31       | 16.06%  |
| 3.01-4.0    | 23       | 11.92%  |
| 32.01-64.0  | 20       | 10.36%  |
| 64.01-256.0 | 13       | 6.74%   |
| 1.01-2.0    | 8        | 4.15%   |
| 24.01-32.0  | 5        | 2.59%   |
| 2.01-3.0    | 2        | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 64       | 29.36%  |
| 2.01-3.0    | 61       | 27.98%  |
| 3.01-4.0    | 33       | 15.14%  |
| 4.01-8.0    | 17       | 7.8%    |
| 0.51-1.0    | 14       | 6.42%   |
| 8.01-16.0   | 10       | 4.59%   |
| 32.01-64.0  | 5        | 2.29%   |
| 24.01-32.0  | 4        | 1.83%   |
| 16.01-24.0  | 4        | 1.83%   |
| 64.01-256.0 | 3        | 1.38%   |
| 0.01-0.5    | 3        | 1.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 65       | 32.5%   |
| 2      | 56       | 28%     |
| 3      | 30       | 15%     |
| 4      | 20       | 10%     |
| 5      | 9        | 4.5%    |
| 7      | 8        | 4%      |
| 6      | 5        | 2.5%    |
| 8      | 4        | 2%      |
| 11     | 1        | 0.5%    |
| 10     | 1        | 0.5%    |
| 9      | 1        | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 132      | 69.11%  |
| Yes       | 59       | 30.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 174      | 92.06%  |
| No        | 15       | 7.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 116      | 60.1%   |
| No        | 77       | 39.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 67.54%  |
| Yes       | 62       | 32.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Malaysia | 189      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Kuala Lumpur           | 81       | 39.13%  |
| Petaling Jaya          | 19       | 9.18%   |
| George Town            | 11       | 5.31%   |
| Seremban               | 6        | 2.9%    |
| Kuching                | 6        | 2.9%    |
| Kota Kinabalu          | 6        | 2.9%    |
| Shah Alam              | 5        | 2.42%   |
| Kajang                 | 5        | 2.42%   |
| Subang Jaya            | 4        | 1.93%   |
| Malacca                | 4        | 1.93%   |
| Johor Bahru            | 4        | 1.93%   |
| Butterworth            | 4        | 1.93%   |
| Sungai Buloh           | 3        | 1.45%   |
| Puchong Batu Dua Belas | 3        | 1.45%   |
| Kulim                  | 3        | 1.45%   |
| Kota Bharu             | 3        | 1.45%   |
| Ipoh                   | 3        | 1.45%   |
| Cheras                 | 3        | 1.45%   |
| Bayan Lepas            | 3        | 1.45%   |
| Tawau                  | 2        | 0.97%   |
| Labuan                 | 2        | 0.97%   |
| Bukit Mertajam         | 2        | 0.97%   |
| Ampang                 | 2        | 0.97%   |
| Alor Star              | 2        | 0.97%   |
| Taman Senai            | 1        | 0.48%   |
| Taiping                | 1        | 0.48%   |
| Sungai Petani          | 1        | 0.48%   |
| Seri Kembangan         | 1        | 0.48%   |
| Semenyih               | 1        | 0.48%   |
| Rawang                 | 1        | 0.48%   |
| Putrajaya              | 1        | 0.48%   |
| Penampang              | 1        | 0.48%   |
| Padang Serai           | 1        | 0.48%   |
| Muar town              | 1        | 0.48%   |
| Marabu                 | 1        | 0.48%   |
| Long Seridan           | 1        | 0.48%   |
| Kulai                  | 1        | 0.48%   |
| Kuantan                | 1        | 0.48%   |
| Klang                  | 1        | 0.48%   |
| Cukai                  | 1        | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 87       | 174    | 22.77%  |
| WDC                         | 79       | 154    | 20.68%  |
| Kingston                    | 38       | 67     | 9.95%   |
| Samsung Electronics         | 24       | 39     | 6.28%   |
| Toshiba                     | 16       | 18     | 4.19%   |
| PNY                         | 13       | 41     | 3.4%    |
| A-DATA Technology           | 13       | 24     | 3.4%    |
| Crucial                     | 10       | 16     | 2.62%   |
| Sandisk                     | 7        | 11     | 1.83%   |
| Intel                       | 7        | 11     | 1.83%   |
| Unknown                     | 6        | 7      | 1.57%   |
| Corsair                     | 6        | 17     | 1.57%   |
| Apacer                      | 6        | 11     | 1.57%   |
| Micron Technology           | 4        | 8      | 1.05%   |
| Silicon Motion              | 3        | 4      | 0.79%   |
| Phison Electronics          | 3        | 3      | 0.79%   |
| Phison                      | 3        | 4      | 0.79%   |
| KIOXIA-EXCERIA              | 3        | 5      | 0.79%   |
| Hitachi                     | 3        | 3      | 0.79%   |
| HGST                        | 3        | 3      | 0.79%   |
| Gigabyte Technology         | 3        | 3      | 0.79%   |
| China                       | 3        | 3      | 0.79%   |
| XPG                         | 2        | 3      | 0.52%   |
| Transcend                   | 2        | 3      | 0.52%   |
| TO Exter                    | 2        | 4      | 0.52%   |
| SPCC                        | 2        | 2      | 0.52%   |
| Plextor                     | 2        | 2      | 0.52%   |
| OCZ                         | 2        | 7      | 0.52%   |
| Kingston Technology Company | 2        | 2      | 0.52%   |
| Hewlett-Packard             | 2        | 2      | 0.52%   |
| GAMER                       | 2        | 2      | 0.52%   |
| External                    | 2        | 2      | 0.52%   |
| ADATA Technology            | 2        | 2      | 0.52%   |
| Verbatim                    | 1        | 1      | 0.26%   |
| sk600                       | 1        | 1      | 0.26%   |
| SK hynix                    | 1        | 1      | 0.26%   |
| SATAFIRM                    | 1        | 1      | 0.26%   |
| Realtek                     | 1        | 1      | 0.26%   |
| Pioneer                     | 1        | 1      | 0.26%   |
| Micron/Crucial Technology   | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD    | 13       | 2.86%   |
| Seagate ST2000DM008-2UB102 2TB     | 11       | 2.42%   |
| Seagate ST3500414CS 500GB          | 9        | 1.98%   |
| Seagate ST1000DM010-2EP102 1TB     | 8        | 1.76%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 7        | 1.54%   |
| WDC WD2500AAKX-753CA1 250GB        | 7        | 1.54%   |
| PNY 1TB SATA SSD                   | 6        | 1.32%   |
| Corsair Force MP510 240GB          | 6        | 1.32%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 5        | 1.1%    |
| WDC WD20EZRX-00D8PB0 2TB           | 5        | 1.1%    |
| Seagate ST500DM002-1BD142 500GB    | 5        | 1.1%    |
| Seagate ST380815AS 80GB            | 5        | 1.1%    |
| Samsung HD103SJ 1TB                | 5        | 1.1%    |
| A-DATA SX8200PNP 256GB             | 5        | 1.1%    |
| Toshiba MQ01ABD100 1TB             | 4        | 0.88%   |
| Seagate ST500DM002-1BC142 500GB    | 4        | 0.88%   |
| Seagate ST3160815AS 160GB          | 4        | 0.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4        | 0.88%   |
| Kingston SA400S37480G 480GB SSD    | 4        | 0.88%   |
| A-DATA SU650 120GB SSD             | 4        | 0.88%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 3        | 0.66%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 3        | 0.66%   |
| WDC WD3200AAKS-00SBA0 320GB        | 3        | 0.66%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 3        | 0.66%   |
| WDC WD10EZEX-22MFCA0 1TB           | 3        | 0.66%   |
| Seagate ST3320418AS 320GB          | 3        | 0.66%   |
| Seagate ST2000DM006-2DM164 2TB     | 3        | 0.66%   |
| Seagate ST1000DM003-1ER162 1TB     | 3        | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB     | 3        | 0.66%   |
| PNY CS900 1TB SSD                  | 3        | 0.66%   |
| PNY CS900 120GB SSD                | 3        | 0.66%   |
| Kingston SV300S37A120G 120GB SSD   | 3        | 0.66%   |
| Kingston SEDC500R1920G 2TB SSD     | 3        | 0.66%   |
| Kingston SA400S37120G 120GB SSD    | 3        | 0.66%   |
| Kingston NVMe SSD Drive 500GB      | 3        | 0.66%   |
| Crucial CT500MX500SSD1 500GB       | 3        | 0.66%   |
| XPG NVMe SSD Drive 512GB           | 2        | 0.44%   |
| WDC WD800JD-22MSA1 80GB            | 2        | 0.44%   |
| WDC WD5000AAKX-001CA0 500GB        | 2        | 0.44%   |
| WDC WD5000AADS-00S9B0 500GB        | 2        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 86       | 173    | 42.57%  |
| WDC                 | 76       | 151    | 37.62%  |
| Toshiba             | 16       | 18     | 7.92%   |
| Samsung Electronics | 9        | 13     | 4.46%   |
| Hitachi             | 3        | 3      | 1.49%   |
| HGST                | 3        | 3      | 1.49%   |
| Unknown             | 2        | 2      | 0.99%   |
| TO Exter            | 2        | 4      | 0.99%   |
| External            | 2        | 2      | 0.99%   |
| Maxtor              | 1        | 4      | 0.5%    |
| JMicron Technology  | 1        | 1      | 0.5%    |
| Hewlett-Packard     | 1        | 1      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 33       | 51     | 27.73%  |
| PNY                 | 12       | 40     | 10.08%  |
| Crucial             | 10       | 16     | 8.4%    |
| Samsung Electronics | 9        | 14     | 7.56%   |
| Apacer              | 6        | 11     | 5.04%   |
| A-DATA Technology   | 6        | 6      | 5.04%   |
| SanDisk             | 5        | 8      | 4.2%    |
| Intel               | 5        | 8      | 4.2%    |
| China               | 3        | 3      | 2.52%   |
| WDC                 | 2        | 2      | 1.68%   |
| Transcend           | 2        | 3      | 1.68%   |
| SPCC                | 2        | 2      | 1.68%   |
| Plextor             | 2        | 2      | 1.68%   |
| OCZ                 | 2        | 7      | 1.68%   |
| Micron Technology   | 2        | 6      | 1.68%   |
| KIOXIA-EXCERIA      | 2        | 4      | 1.68%   |
| Verbatim            | 1        | 1      | 0.84%   |
| sk600               | 1        | 1      | 0.84%   |
| SK hynix            | 1        | 1      | 0.84%   |
| Seagate             | 1        | 1      | 0.84%   |
| SATAFIRM            | 1        | 1      | 0.84%   |
| Pioneer             | 1        | 1      | 0.84%   |
| MAXSUN              | 1        | 1      | 0.84%   |
| LITEON              | 1        | 1      | 0.84%   |
| KimMiDi             | 1        | 1      | 0.84%   |
| Hikvision           | 1        | 2      | 0.84%   |
| Hewlett-Packard     | 1        | 1      | 0.84%   |
| GAMER               | 1        | 1      | 0.84%   |
| FORESEE             | 1        | 1      | 0.84%   |
| Colorful            | 1        | 1      | 0.84%   |
| ASMT                | 1        | 2      | 0.84%   |
| AGI                 | 1        | 1      | 0.84%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 150      | 375    | 49.67%  |
| SSD     | 98       | 201    | 32.45%  |
| NVMe    | 46       | 97     | 15.23%  |
| Unknown | 6        | 8      | 1.99%   |
| MMC     | 2        | 2      | 0.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 176      | 563    | 73.64%  |
| NVMe | 46       | 96     | 19.25%  |
| SAS  | 15       | 22     | 6.28%   |
| MMC  | 2        | 2      | 0.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 136      | 281    | 51.32%  |
| 0.51-1.0   | 79       | 168    | 29.81%  |
| 1.01-2.0   | 37       | 102    | 13.96%  |
| 3.01-4.0   | 7        | 16     | 2.64%   |
| 2.01-3.0   | 3        | 4      | 1.13%   |
| 4.01-10.0  | 3        | 5      | 1.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 51       | 25.25%  |
| 501-1000       | 32       | 15.84%  |
| 251-500        | 30       | 14.85%  |
| 1001-2000      | 20       | 9.9%    |
| 1-20           | 15       | 7.43%   |
| 51-100         | 15       | 7.43%   |
| More than 3000 | 13       | 6.44%   |
| Unknown        | 10       | 4.95%   |
| 21-50          | 9        | 4.46%   |
| 2001-3000      | 7        | 3.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 86       | 40.38%  |
| 21-50          | 26       | 12.21%  |
| 51-100         | 24       | 11.27%  |
| 101-250        | 21       | 9.86%   |
| 251-500        | 15       | 7.04%   |
| 1001-2000      | 11       | 5.16%   |
| 501-1000       | 11       | 5.16%   |
| Unknown        | 10       | 4.69%   |
| More than 3000 | 7        | 3.29%   |
| 2001-3000      | 2        | 0.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB       | 7        | 7      | 25.93%  |
| Seagate ST3500414CS 500GB          | 2        | 3      | 7.41%   |
| WDC WD800AAJS-00PSA0 80GB          | 1        | 1      | 3.7%    |
| WDC WD5000AAKX-753CA1 500GB        | 1        | 1      | 3.7%    |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 1      | 3.7%    |
| WDC WD5000AADS-00S9B0 500GB        | 1        | 1      | 3.7%    |
| WDC WD10EZEX-60WN4A0 1TB           | 1        | 1      | 3.7%    |
| Toshiba MQ01ABD100 1TB             | 1        | 1      | 3.7%    |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 3.7%    |
| Seagate ST380211AS 80GB            | 1        | 1      | 3.7%    |
| Seagate ST3320620A 320GB           | 1        | 1      | 3.7%    |
| Seagate ST31000322CS 1TB           | 1        | 1      | 3.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 3.7%    |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 3.7%    |
| Samsung Electronics HM160HI 160GB  | 1        | 1      | 3.7%    |
| Kingston SV300S37A120G 120GB SSD   | 1        | 1      | 3.7%    |
| Intel SSDSCKKW120H6 120GB          | 1        | 1      | 3.7%    |
| Hitachi HDS721680PLA380 80GB       | 1        | 1      | 3.7%    |
| Hitachi HDS721050CLA362 500GB      | 1        | 1      | 3.7%    |
| Hewlett-Packard SSD S700 120GB     | 1        | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 46.15%  |
| Seagate             | 7        | 9      | 26.92%  |
| Hitachi             | 2        | 2      | 7.69%   |
| Toshiba             | 1        | 1      | 3.85%   |
| Samsung Electronics | 1        | 1      | 3.85%   |
| Kingston            | 1        | 1      | 3.85%   |
| Intel               | 1        | 1      | 3.85%   |
| Hewlett-Packard     | 1        | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 52.17%  |
| Seagate             | 7        | 9      | 30.43%  |
| Hitachi             | 2        | 2      | 8.7%    |
| Toshiba             | 1        | 1      | 4.35%   |
| Samsung Electronics | 1        | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 25     | 88.46%  |
| SSD  | 3        | 3      | 11.54%  |

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
| Detected | 106      | 347    | 48.62%  |
| Works    | 86       | 308    | 39.45%  |
| Malfunc  | 26       | 28     | 11.93%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 137      | 52.09%  |
| AMD                         | 47       | 17.87%  |
| Phison Electronics          | 16       | 6.08%   |
| ASMedia Technology          | 10       | 3.8%    |
| Kingston Technology Company | 9        | 3.42%   |
| ADATA Technology            | 9        | 3.42%   |
| Samsung Electronics         | 8        | 3.04%   |
| Silicon Motion              | 4        | 1.52%   |
| Nvidia                      | 4        | 1.52%   |
| Marvell Technology Group    | 4        | 1.52%   |
| JMicron Technology          | 4        | 1.52%   |
| SanDisk                     | 3        | 1.14%   |
| Micron Technology           | 2        | 0.76%   |
| Broadcom / LSI              | 2        | 0.76%   |
| Silicon Image               | 1        | 0.38%   |
| Micron/Crucial Technology   | 1        | 0.38%   |
| Lite-On IT Corp. / Plextor  | 1        | 0.38%   |
| KIOXIA                      | 1        | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33       | 9.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 20       | 5.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 18       | 5.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 11       | 3.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10       | 2.92%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 10       | 2.92%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 10       | 2.92%   |
| AMD 400 Series Chipset SATA Controller                                         | 10       | 2.92%   |
| Intel SATA Controller [RAID mode]                                              | 9        | 2.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 9        | 2.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 9        | 2.62%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 9        | 2.62%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 7        | 2.04%   |
| Phison E12 NVMe Controller                                                     | 7        | 2.04%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 7        | 2.04%   |
| AMD FCH SATA Controller D                                                      | 6        | 1.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 1.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 1.46%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5        | 1.46%   |
| Intel 82Q35 Express PT IDER Controller                                         | 5        | 1.46%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 5        | 1.46%   |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 1.46%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4        | 1.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 4        | 1.17%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 4        | 1.17%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3        | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 0.87%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3        | 0.87%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3        | 0.87%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 3        | 0.87%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 3        | 0.87%   |
| ASMedia 1064 SATA Controller                                                   | 3        | 0.87%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 0.58%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 0.58%   |
| Nvidia MCP61 SATA Controller                                                   | 2        | 0.58%   |
| Nvidia MCP61 IDE                                                               | 2        | 0.58%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                         | 2        | 0.58%   |
| Kingston Company DC1000B NVMe SSD E12DC                                        | 2        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 143      | 55.86%  |
| IDE  | 48       | 18.75%  |
| NVMe | 46       | 17.97%  |
| RAID | 17       | 6.64%   |
| SAS  | 2        | 0.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 139      | 73.54%  |
| AMD    | 50       | 26.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium CPU G620 @ 2.60GHz            | 9        | 4.74%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 8        | 4.21%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 5        | 2.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 2.11%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 2.11%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 2.11%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 2.11%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 4        | 2.11%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4        | 2.11%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 2.11%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 2.11%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 3        | 1.58%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 1.58%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 1.58%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 1.58%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 1.58%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1.58%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 2        | 1.05%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 1.05%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 1.05%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.05%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.05%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.05%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2        | 1.05%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.05%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.05%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.05%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 2        | 1.05%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.05%   |
| Intel 12th Gen Core i5-12400F               | 2        | 1.05%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.05%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 2        | 1.05%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 2        | 1.05%   |
| AMD Ryzen 5 5600 6-Core Processor           | 2        | 1.05%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.05%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.05%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 2        | 1.05%   |
| Intel Xeon CPU E5-2699 v3 @ 2.30GHz         | 1        | 0.53%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz         | 1        | 0.53%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz          | 1        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 38       | 20%     |
| Intel Core i3           | 25       | 13.16%  |
| AMD Ryzen 5             | 18       | 9.47%   |
| Intel Pentium           | 16       | 8.42%   |
| Intel Core i7           | 15       | 7.89%   |
| Intel Core 2 Duo        | 12       | 6.32%   |
| Other                   | 10       | 5.26%   |
| Intel Xeon              | 9        | 4.74%   |
| AMD Ryzen 9             | 7        | 3.68%   |
| Intel Core 2 Quad       | 6        | 3.16%   |
| AMD Ryzen 7             | 5        | 2.63%   |
| AMD Ryzen 3             | 4        | 2.11%   |
| Intel Pentium Dual-Core | 3        | 1.58%   |
| AMD Ryzen Threadripper  | 3        | 1.58%   |
| Intel Celeron           | 2        | 1.05%   |
| Intel Atom              | 2        | 1.05%   |
| AMD FX                  | 2        | 1.05%   |
| AMD Athlon 64 X2        | 2        | 1.05%   |
| AMD A10                 | 2        | 1.05%   |
| Intel Pentium Dual      | 1        | 0.53%   |
| Intel Core i9           | 1        | 0.53%   |
| AMD Ryzen Embedded      | 1        | 0.53%   |
| AMD Phenom II X6        | 1        | 0.53%   |
| AMD Phenom II X4        | 1        | 0.53%   |
| AMD EPYC                | 1        | 0.53%   |
| AMD Athlon X2           | 1        | 0.53%   |
| AMD Athlon              | 1        | 0.53%   |
| AMD A6                  | 1        | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 72       | 37.89%  |
| 2      | 62       | 32.63%  |
| 6      | 29       | 15.26%  |
| 16     | 9        | 4.74%   |
| 8      | 7        | 3.68%   |
| 12     | 5        | 2.63%   |
| 10     | 2        | 1.05%   |
| 36     | 1        | 0.53%   |
| 32     | 1        | 0.53%   |
| 28     | 1        | 0.53%   |
| 3      | 1        | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 187      | 98.94%  |
| 2      | 2        | 1.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 95       | 50%     |
| 1      | 95       | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 189      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 55       | 27.78%  |
| 0x306c3    | 23       | 11.62%  |
| 0x206a7    | 15       | 7.58%   |
| 0x306a9    | 13       | 6.57%   |
| 0x1067a    | 12       | 6.06%   |
| 0x506e3    | 6        | 3.03%   |
| 0x08108109 | 6        | 3.03%   |
| 0x90672    | 5        | 2.53%   |
| 0x08701021 | 5        | 2.53%   |
| 0x6fb      | 4        | 2.02%   |
| 0x906ea    | 3        | 1.52%   |
| 0x6fd      | 3        | 1.52%   |
| 0x0a601203 | 3        | 1.52%   |
| 0x0a20120a | 3        | 1.52%   |
| 0xa0671    | 2        | 1.01%   |
| 0xa0655    | 2        | 1.01%   |
| 0xa0653    | 2        | 1.01%   |
| 0x906e9    | 2        | 1.01%   |
| 0x10676    | 2        | 1.01%   |
| 0x0830104d | 2        | 1.01%   |
| 0x906eb    | 1        | 0.51%   |
| 0x506f1    | 1        | 0.51%   |
| 0x506c9    | 1        | 0.51%   |
| 0x406f1    | 1        | 0.51%   |
| 0x406c4    | 1        | 0.51%   |
| 0x406c3    | 1        | 0.51%   |
| 0x306f2    | 1        | 0.51%   |
| 0x206d7    | 1        | 0.51%   |
| 0x20652    | 1        | 0.51%   |
| 0x106a5    | 1        | 0.51%   |
| 0x0a601206 | 1        | 0.51%   |
| 0x0a50000d | 1        | 0.51%   |
| 0x0a50000b | 1        | 0.51%   |
| 0x0a201025 | 1        | 0.51%   |
| 0x0a201016 | 1        | 0.51%   |
| 0x0a201009 | 1        | 0.51%   |
| 0x0a008203 | 1        | 0.51%   |
| 0x08701013 | 1        | 0.51%   |
| 0x08301039 | 1        | 0.51%   |
| 0x0810100b | 1        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 29       | 15.34%  |
| IvyBridge        | 26       | 13.76%  |
| SandyBridge      | 19       | 10.05%  |
| Penryn           | 16       | 8.47%   |
| Zen 3            | 11       | 5.82%   |
| Zen+             | 9        | 4.76%   |
| Zen 2            | 9        | 4.76%   |
| KabyLake         | 9        | 4.76%   |
| Unknown          | 9        | 4.76%   |
| Skylake          | 8        | 4.23%   |
| Core             | 8        | 4.23%   |
| Zen              | 6        | 3.17%   |
| CometLake        | 6        | 3.17%   |
| Alderlake Hybrid | 5        | 2.65%   |
| K10              | 3        | 1.59%   |
| Westmere         | 2        | 1.06%   |
| Silvermont       | 2        | 1.06%   |
| Piledriver       | 2        | 1.06%   |
| K8 Hammer        | 2        | 1.06%   |
| Goldmont         | 2        | 1.06%   |
| Steamroller      | 1        | 0.53%   |
| Nehalem          | 1        | 0.53%   |
| K10 Llano        | 1        | 0.53%   |
| Icelake          | 1        | 0.53%   |
| Excavator        | 1        | 0.53%   |
| Broadwell        | 1        | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 81       | 39.51%  |
| Intel             | 69       | 33.66%  |
| AMD               | 52       | 25.37%  |
| ASPEED Technology | 3        | 1.46%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 17       | 8.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 5.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9        | 4.31%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 7        | 3.35%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 6        | 2.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 2.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6        | 2.87%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 5        | 2.39%   |
| Intel HD Graphics 530                                                                    | 5        | 2.39%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5        | 2.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 2.39%   |
| AMD Raphael                                                                              | 4        | 1.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3        | 1.44%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 3        | 1.44%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3        | 1.44%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3        | 1.44%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3        | 1.44%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 1.44%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 3        | 1.44%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 3        | 1.44%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 1.44%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3        | 1.44%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 3        | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 1.44%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 1.44%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 0.96%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 2        | 0.96%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 2        | 0.96%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 2        | 0.96%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2        | 0.96%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 0.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.96%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 0.96%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 0.96%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 0.96%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 0.96%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 0.96%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2        | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 72       | 38.1%   |
| 1 x Intel            | 59       | 31.22%  |
| 1 x AMD              | 46       | 24.34%  |
| Nvidia + ASPEED      | 3        | 1.59%   |
| AMD + Nvidia         | 3        | 1.59%   |
| Intel + Nvidia       | 2        | 1.06%   |
| Other                | 1        | 0.53%   |
| 2 x AMD + 3 x Nvidia | 1        | 0.53%   |
| 2 x AMD              | 1        | 0.53%   |
| Intel + AMD          | 1        | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 143      | 73.33%  |
| Proprietary | 40       | 20.51%  |
| Unknown     | 12       | 6.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 88       | 45.36%  |
| 1.01-2.0   | 31       | 15.98%  |
| 0.51-1.0   | 24       | 12.37%  |
| 7.01-8.0   | 16       | 8.25%   |
| 3.01-4.0   | 11       | 5.67%   |
| 0.01-0.5   | 11       | 5.67%   |
| 5.01-6.0   | 6        | 3.09%   |
| 8.01-16.0  | 4        | 2.06%   |
| 2.01-3.0   | 2        | 1.03%   |
| 32.01-64.0 | 1        | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 38       | 19.9%   |
| Acer                 | 21       | 10.99%  |
| Samsung Electronics  | 19       | 9.95%   |
| Goldstar             | 18       | 9.42%   |
| BenQ                 | 16       | 8.38%   |
| Hewlett-Packard      | 15       | 7.85%   |
| AOC                  | 14       | 7.33%   |
| Philips              | 8        | 4.19%   |
| ViewSonic            | 7        | 3.66%   |
| Lenovo               | 5        | 2.62%   |
| Sharp                | 3        | 1.57%   |
| ASUSTek Computer     | 3        | 1.57%   |
| Toshiba              | 2        | 1.05%   |
| Panasonic            | 2        | 1.05%   |
| LG Electronics       | 2        | 1.05%   |
| Denver               | 2        | 1.05%   |
| Unknown              | 2        | 1.05%   |
| Unknown              | 1        | 0.52%   |
| NCS                  | 1        | 0.52%   |
| MSI                  | 1        | 0.52%   |
| MSG                  | 1        | 0.52%   |
| Mi                   | 1        | 0.52%   |
| HUYINIUDA            | 1        | 0.52%   |
| GAOMON               | 1        | 0.52%   |
| Fujitsu Siemens      | 1        | 0.52%   |
| Envision Peripherals | 1        | 0.52%   |
| Eizo                 | 1        | 0.52%   |
| Dinner               | 1        | 0.52%   |
| CVT                  | 1        | 0.52%   |
| AOpen                | 1        | 0.52%   |
| AGO                  | 1        | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 7        | 3.45%   |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                  | 6        | 2.96%   |
| Dell E2720HS DELA15E 1920x1080 600x340mm 27.2-inch                | 4        | 1.97%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 3        | 1.48%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                | 3        | 1.48%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch               | 3        | 1.48%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch           | 3        | 1.48%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                 | 3        | 1.48%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                 | 3        | 1.48%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch | 2        | 0.99%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch  | 2        | 0.99%   |
| Hewlett-Packard LCD Monitor P221                                  | 2        | 0.99%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch           | 2        | 0.99%   |
| Dell LCD Monitor E2720HS 1920x1080                                | 2        | 0.99%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                 | 2        | 0.99%   |
| BenQ LCD Monitor GW2270 1920x1080                                 | 2        | 0.99%   |
| ASUSTek Computer XG32VQR AUS32B2 2560x1440 697x393mm 31.5-inch    | 2        | 0.99%   |
| AOC LCD Monitor 936W 1366x768                                     | 2        | 0.99%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                     | 2        | 0.99%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                   | 2        | 0.99%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                    | 2        | 0.99%   |
| Acer V193HQL ACR027C 1366x768 410x230mm 18.5-inch                 | 2        | 0.99%   |
| Unknown                                                           | 2        | 0.99%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch     | 1        | 0.49%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch         | 1        | 0.49%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch         | 1        | 0.49%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch     | 1        | 0.49%   |
| ViewSonic VA2732-FHD VSC0D3A 1920x1080 598x336mm 27.0-inch        | 1        | 0.49%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch        | 1        | 0.49%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch      | 1        | 0.49%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                             | 1        | 0.49%   |
| Toshiba TV TSB0113 1920x1080 1220x680mm 55.0-inch                 | 1        | 0.49%   |
| Toshiba Crystal View LCD0001 1920x1080 408x255mm 18.9-inch        | 1        | 0.49%   |
| Sharp LCD SHP10C9 1920x540                                        | 1        | 0.49%   |
| Sharp LCD SHP10A2 1360x768                                        | 1        | 0.49%   |
| Sharp LC-22LE420M SHP2242 1920x1080 477x268mm 21.5-inch           | 1        | 0.49%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch | 1        | 0.49%   |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch  | 1        | 0.49%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch | 1        | 0.49%   |
| Samsung Electronics S24C350 SAM0A3C 1920x1080 521x293mm 23.5-inch | 1        | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 81       | 42.86%  |
| 1366x768 (WXGA)    | 20       | 10.58%  |
| 3840x2160 (4K)     | 17       | 8.99%   |
| 1600x900 (HD+)     | 15       | 7.94%   |
| 2560x1440 (QHD)    | 9        | 4.76%   |
| 1440x900 (WXGA+)   | 7        | 3.7%    |
| 2560x1080          | 6        | 3.17%   |
| 1680x1050 (WSXGA+) | 6        | 3.17%   |
| 1360x768           | 5        | 2.65%   |
| Unknown            | 5        | 2.65%   |
| 1280x1024 (SXGA)   | 3        | 1.59%   |
| 5760x1080          | 2        | 1.06%   |
| 1920x1200 (WUXGA)  | 2        | 1.06%   |
| 1600x1200          | 2        | 1.06%   |
| 5440x1080          | 1        | 0.53%   |
| 5120x1440          | 1        | 0.53%   |
| 3840x1080          | 1        | 0.53%   |
| 3440x1440          | 1        | 0.53%   |
| 3120x1600          | 1        | 0.53%   |
| 1920x540           | 1        | 0.53%   |
| 1280x960           | 1        | 0.53%   |
| 1280x720 (HD)      | 1        | 0.53%   |
| 1024x768 (XGA)     | 1        | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 24       | 12.63%  |
| 23      | 23       | 12.11%  |
| 21      | 21       | 11.05%  |
| 18      | 21       | 11.05%  |
| Unknown | 18       | 9.47%   |
| 27      | 17       | 8.95%   |
| 19      | 14       | 7.37%   |
| 20      | 13       | 6.84%   |
| 31      | 10       | 5.26%   |
| 22      | 7        | 3.68%   |
| 34      | 5        | 2.63%   |
| 32      | 3        | 1.58%   |
| 17      | 3        | 1.58%   |
| 84      | 2        | 1.05%   |
| 15      | 2        | 1.05%   |
| 12      | 2        | 1.05%   |
| 55      | 1        | 0.53%   |
| 49      | 1        | 0.53%   |
| 39      | 1        | 0.53%   |
| 28      | 1        | 0.53%   |
| 25      | 1        | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 74       | 39.57%  |
| 501-600     | 60       | 32.09%  |
| Unknown     | 18       | 9.63%   |
| 601-700     | 13       | 6.95%   |
| 701-800     | 8        | 4.28%   |
| 301-350     | 5        | 2.67%   |
| 351-400     | 2        | 1.07%   |
| 201-300     | 2        | 1.07%   |
| 1501-2000   | 2        | 1.07%   |
| 1001-1500   | 2        | 1.07%   |
| 801-900     | 1        | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 129      | 71.27%  |
| 16/10   | 18       | 9.94%   |
| Unknown | 16       | 8.84%   |
| 21/9    | 6        | 3.31%   |
| 5/4     | 5        | 2.76%   |
| 4/3     | 5        | 2.76%   |
| 32/9    | 2        | 1.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 65       | 34.76%  |
| 151-200        | 33       | 17.65%  |
| 141-150        | 22       | 11.76%  |
| 351-500        | 18       | 9.63%   |
| Unknown        | 18       | 9.63%   |
| 301-350        | 17       | 9.09%   |
| 251-300        | 5        | 2.67%   |
| More than 1000 | 3        | 1.6%    |
| 71-80          | 2        | 1.07%   |
| 101-110        | 2        | 1.07%   |
| 501-1000       | 2        | 1.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 125      | 69.06%  |
| 101-120 | 26       | 14.36%  |
| Unknown | 18       | 9.94%   |
| 121-160 | 6        | 3.31%   |
| 1-50    | 3        | 1.66%   |
| 161-240 | 3        | 1.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 155      | 81.15%  |
| 2     | 18       | 9.42%   |
| 0     | 16       | 8.38%   |
| 3     | 2        | 1.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 105      | 33.87%  |
| Intel                             | 84       | 27.1%   |
| Qualcomm Atheros                  | 26       | 8.39%   |
| TP-Link                           | 21       | 6.77%   |
| Ralink Technology                 | 14       | 4.52%   |
| D-Link                            | 10       | 3.23%   |
| Broadcom                          | 10       | 3.23%   |
| Qualcomm Atheros Communications   | 9        | 2.9%    |
| Xiaomi                            | 6        | 1.94%   |
| Nvidia                            | 3        | 0.97%   |
| Samsung Electronics               | 2        | 0.65%   |
| OPPO Electronics                  | 2        | 0.65%   |
| MediaTek                          | 2        | 0.65%   |
| Broadcom Limited                  | 2        | 0.65%   |
| Aquantia                          | 2        | 0.65%   |
| Tehuti Networks                   | 1        | 0.32%   |
| T & A Mobile Phones               | 1        | 0.32%   |
| Sundance Technology Inc / IC Plus | 1        | 0.32%   |
| Ralink                            | 1        | 0.32%   |
| Qualcomm                          | 1        | 0.32%   |
| Mercucys                          | 1        | 0.32%   |
| Mellanox Technologies             | 1        | 0.32%   |
| InterBiometrics                   | 1        | 0.32%   |
| D-Link System                     | 1        | 0.32%   |
| Apple                             | 1        | 0.32%   |
| American Megatrends               | 1        | 0.32%   |
| AboCom Systems                    | 1        | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 75       | 21.43%  |
| Realtek RTL8125 2.5GbE Controller                                                    | 12       | 3.43%   |
| TP-Link Archer T4U ver.3                                                             | 9        | 2.57%   |
| Intel 82579V Gigabit Network Connection                                              | 9        | 2.57%   |
| Realtek 802.11ac NIC                                                                 | 7        | 2%      |
| Ralink MT7601U Wireless Adapter                                                      | 7        | 2%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 7        | 2%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 6        | 1.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 6        | 1.71%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 6        | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 6        | 1.71%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6        | 1.71%   |
| Intel I211 Gigabit Network Connection                                                | 5        | 1.43%   |
| Intel Ethernet Controller I225-V                                                     | 5        | 1.43%   |
| Intel Ethernet Connection (11) I219-V                                                | 5        | 1.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                                 | 5        | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                       | 4        | 1.14%   |
| TP-Link 802.11n NIC                                                                  | 4        | 1.14%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 4        | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4        | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 4        | 1.14%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 4        | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 4        | 1.14%   |
| Intel Ethernet Connection I217-LM                                                    | 4        | 1.14%   |
| Intel Ethernet Connection (7) I219-V                                                 | 4        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 1.14%   |
| Intel 82567LM-3 Gigabit Network Connection                                           | 4        | 1.14%   |
| Intel 82566DM-2 Gigabit Network Connection                                           | 4        | 1.14%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 3        | 0.86%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3        | 0.86%   |
| Intel Ethernet Controller X550                                                       | 3        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                                                 | 3        | 0.86%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                         | 3        | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                 | 2        | 0.57%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                | 2        | 0.57%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2        | 0.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 2        | 0.57%   |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 27       | 21.09%  |
| Intel                           | 23       | 17.97%  |
| TP-Link                         | 21       | 16.41%  |
| Ralink Technology               | 14       | 10.94%  |
| Qualcomm Atheros                | 11       | 8.59%   |
| D-Link                          | 10       | 7.81%   |
| Qualcomm Atheros Communications | 9        | 7.03%   |
| Broadcom                        | 6        | 4.69%   |
| MediaTek                        | 2        | 1.56%   |
| Ralink                          | 1        | 0.78%   |
| Mercucys                        | 1        | 0.78%   |
| D-Link System                   | 1        | 0.78%   |
| Broadcom Limited                | 1        | 0.78%   |
| AboCom Systems                  | 1        | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| TP-Link Archer T4U ver.3                                                             | 9        | 6.92%   |
| Realtek 802.11ac NIC                                                                 | 7        | 5.38%   |
| Ralink MT7601U Wireless Adapter                                                      | 7        | 5.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 6        | 4.62%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 6        | 4.62%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 6        | 4.62%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6        | 4.62%   |
| TP-Link 802.11n NIC                                                                  | 4        | 3.08%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 4        | 3.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4        | 3.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 4        | 3.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 4        | 3.08%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 4        | 3.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 3        | 2.31%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3        | 2.31%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                         | 3        | 2.31%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                | 2        | 1.54%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                           | 2        | 1.54%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 1.54%   |
| Ralink RT5370 Wireless Adapter                                                       | 2        | 1.54%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 2        | 1.54%   |
| Intel Wireless 3165                                                                  | 2        | 1.54%   |
| Intel Wi-Fi 6 AX200                                                                  | 2        | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 2        | 1.54%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 2        | 1.54%   |
| Intel 700 Series Chipset Family Wi-Fi                                                | 2        | 1.54%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1        | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.77%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1        | 0.77%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                            | 1        | 0.77%   |
| Ralink RT5572 Wireless Adapter                                                       | 1        | 0.77%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                          | 1        | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 1        | 0.77%   |
| Mercucys 802.11n NIC                                                                 | 1        | 0.77%   |
| MediaTek WiFi                                                                        | 1        | 0.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 1        | 0.77%   |
| Intel Wireless-AC 9260                                                               | 1        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 92       | 45.1%   |
| Intel                             | 71       | 34.8%   |
| Qualcomm Atheros                  | 15       | 7.35%   |
| Xiaomi                            | 6        | 2.94%   |
| Broadcom                          | 4        | 1.96%   |
| Nvidia                            | 3        | 1.47%   |
| OPPO Electronics                  | 2        | 0.98%   |
| Aquantia                          | 2        | 0.98%   |
| Tehuti Networks                   | 1        | 0.49%   |
| T & A Mobile Phones               | 1        | 0.49%   |
| Sundance Technology Inc / IC Plus | 1        | 0.49%   |
| Samsung Electronics               | 1        | 0.49%   |
| Qualcomm                          | 1        | 0.49%   |
| Mellanox Technologies             | 1        | 0.49%   |
| Broadcom Limited                  | 1        | 0.49%   |
| Apple                             | 1        | 0.49%   |
| American Megatrends               | 1        | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 75       | 34.4%   |
| Realtek RTL8125 2.5GbE Controller                                          | 12       | 5.5%    |
| Intel 82579V Gigabit Network Connection                                    | 9        | 4.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 7        | 3.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6        | 2.75%   |
| Intel I211 Gigabit Network Connection                                      | 5        | 2.29%   |
| Intel Ethernet Controller I225-V                                           | 5        | 2.29%   |
| Intel Ethernet Connection (11) I219-V                                      | 5        | 2.29%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                       | 5        | 2.29%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 4        | 1.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 4        | 1.83%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 1.83%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 1.83%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4        | 1.83%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4        | 1.83%   |
| Intel Ethernet Controller X550                                             | 3        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 1.38%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2        | 0.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 0.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 2        | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 2        | 0.92%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2        | 0.92%   |
| OPPO SM8350-IDP _SN:27BAACC8                                               | 2        | 0.92%   |
| Intel I350 Gigabit Fiber Network Connection                                | 2        | 0.92%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 0.92%   |
| Intel Ethernet Connection I217-V                                           | 2        | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 0.92%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 0.92%   |
| Intel Ethernet 10G 2P X520 Adapter                                         | 2        | 0.92%   |
| Intel 82583V Gigabit Network Connection                                    | 2        | 0.92%   |
| Intel 82562V-2 10/100 Network Connection                                   | 2        | 0.92%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 0.92%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 0.92%   |
| Tehuti Networks TN9310 10GbE SFP+ Ethernet Adapter                         | 1        | 0.46%   |
| T & A Mobile Phones TCL 20E                                                | 1        | 0.46%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                                      | 1        | 0.46%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 0.46%   |
| Qualcomm CAPE-MTP _SN:14677F87                                             | 1        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 174      | 59.59%  |
| WiFi     | 116      | 39.73%  |
| Modem    | 2        | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 113      | 58.85%  |
| WiFi     | 79       | 41.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 109      | 57.07%  |
| 2     | 48       | 25.13%  |
| 0     | 14       | 7.33%   |
| 3     | 11       | 5.76%   |
| 4     | 3        | 1.57%   |
| 5     | 2        | 1.05%   |
| 11    | 1        | 0.52%   |
| 9     | 1        | 0.52%   |
| 8     | 1        | 0.52%   |
| 6     | 1        | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 147      | 75.38%  |
| Yes  | 48       | 24.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 23       | 36.51%  |
| Cambridge Silicon Radio | 23       | 36.51%  |
| Realtek Semiconductor   | 4        | 6.35%   |
| TP-Link                 | 3        | 4.76%   |
| IMC Networks            | 2        | 3.17%   |
| D-Link                  | 2        | 3.17%   |
| Broadcom                | 2        | 3.17%   |
| Apple                   | 2        | 3.17%   |
| MediaTek                | 1        | 1.59%   |
| Foxconn / Hon Hai       | 1        | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23       | 36.51%  |
| Intel Bluetooth Device                              | 8        | 12.7%   |
| Intel Bluetooth wireless interface                  | 6        | 9.52%   |
| Realtek Bluetooth Radio                             | 4        | 6.35%   |
| Intel AX210 Bluetooth                               | 4        | 6.35%   |
| TP-Link UB500 Adapter                               | 3        | 4.76%   |
| Intel AX200 Bluetooth                               | 3        | 4.76%   |
| D-Link DBT-122 Bluetooth adapter                    | 2        | 3.17%   |
| Apple Bluetooth USB Host Controller                 | 2        | 3.17%   |
| MediaTek Wireless_Device                            | 1        | 1.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.59%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 1.59%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.59%   |
| IMC Networks Bluetooth Device                       | 1        | 1.59%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1        | 1.59%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.59%   |
| Broadcom BCM20702A0                                 | 1        | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 130      | 40.5%   |
| Nvidia                      | 80       | 24.92%  |
| AMD                         | 68       | 21.18%  |
| Logitech                    | 7        | 2.18%   |
| C-Media Electronics         | 6        | 1.87%   |
| ASUSTek Computer            | 5        | 1.56%   |
| JMTek                       | 4        | 1.25%   |
| Texas Instruments           | 3        | 0.93%   |
| Yamaha                      | 1        | 0.31%   |
| XMOS                        | 1        | 0.31%   |
| Tenx Technology             | 1        | 0.31%   |
| SteelSeries ApS             | 1        | 0.31%   |
| Setek Elektronik            | 1        | 0.31%   |
| RODE Microphones            | 1        | 0.31%   |
| Razer USA                   | 1        | 0.31%   |
| GYROCOM C&C                 | 1        | 0.31%   |
| GN Netcom                   | 1        | 0.31%   |
| Generalplus Technology      | 1        | 0.31%   |
| FiiO Electronics Technology | 1        | 0.31%   |
| DCMT Technology             | 1        | 0.31%   |
| Creative Technology         | 1        | 0.31%   |
| Creative Labs               | 1        | 0.31%   |
| Cooler Master               | 1        | 0.31%   |
| BR23                        | 1        | 0.31%   |
| Barco Display Systems       | 1        | 0.31%   |
| Anlya.cn                    | 1        | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 20       | 5.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 20       | 5.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 19       | 5.31%   |
| AMD Starship/Matisse HD Audio Controller                                          | 16       | 4.47%   |
| Nvidia GF108 High Definition Audio Controller                                     | 14       | 3.91%   |
| AMD Family 17h/19h HD Audio Controller                                            | 14       | 3.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12       | 3.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10       | 2.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 10       | 2.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9        | 2.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 8        | 2.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 8        | 2.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7        | 1.96%   |
| Nvidia GA106 High Definition Audio Controller                                     | 6        | 1.68%   |
| Nvidia TU106 High Definition Audio Controller                                     | 5        | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                        | 5        | 1.4%    |
| Intel Alder Lake-S HD Audio Controller                                            | 5        | 1.4%    |
| ASUSTek Computer USB Audio                                                        | 5        | 1.4%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 5        | 1.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 1.4%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5        | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4        | 1.12%   |
| Nvidia GM204 High Definition Audio Controller                                     | 4        | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 1.12%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 1.12%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4        | 1.12%   |
| Logitech H600 [Wireless Headset]                                                  | 4        | 1.12%   |
| JMTek USB PnP Audio Device                                                        | 4        | 1.12%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 1.12%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4        | 1.12%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 4        | 1.12%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3        | 0.84%   |
| Nvidia High Definition Audio Controller                                           | 3        | 0.84%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 0.84%   |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 0.84%   |
| Nvidia GA102 High Definition Audio Controller                                     | 3        | 0.84%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.84%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 3        | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 38       | 33.63%  |
| Corsair             | 21       | 18.58%  |
| Unknown             | 11       | 9.73%   |
| SK hynix            | 8        | 7.08%   |
| Samsung Electronics | 6        | 5.31%   |
| Kingmax             | 4        | 3.54%   |
| Micron Technology   | 3        | 2.65%   |
| Team                | 2        | 1.77%   |
| Ramaxel Technology  | 2        | 1.77%   |
| PNY                 | 2        | 1.77%   |
| Kimtigo             | 2        | 1.77%   |
| G.Skill             | 2        | 1.77%   |
| A-DATA Technology   | 2        | 1.77%   |
| Unknown (ABCD)      | 1        | 0.88%   |
| Silicon Power       | 1        | 0.88%   |
| SemsoTai            | 1        | 0.88%   |
| Patriot Memory      | 1        | 0.88%   |
| MAXSUN              | 1        | 0.88%   |
| Lexar               | 1        | 0.88%   |
| Kinlstuo            | 1        | 0.88%   |
| Crucial             | 1        | 0.88%   |
| Apacer              | 1        | 0.88%   |
| Unknown             | 1        | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s            | 6        | 4.8%    |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 5        | 4%      |
| Unknown RAM Module 2GB DIMM SDRAM                              | 4        | 3.2%    |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s         | 4        | 3.2%    |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 3        | 2.4%    |
| Kingmax RAM FLFE85F-C8KL9 2GB DIMM DDR3 1333MT/s               | 3        | 2.4%    |
| Unknown RAM Module 4GB DIMM SDRAM                              | 2        | 1.6%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 1.6%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 2        | 1.6%    |
| Kingston RAM KF552C36-16 16GB DIMM 5200MT/s                    | 2        | 1.6%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 2        | 1.6%    |
| Kingston RAM 99U5471-050.A00LF 8GB DIMM DDR3 1600MT/s          | 2        | 1.6%    |
| Kingmax RAM FLFE85F-C8KM9 2GB DIMM DDR3 1333MT/s               | 2        | 1.6%    |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                 | 2        | 1.6%    |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 2        | 1.6%    |
| Unknown RAM Module 8GB DIMM 667MT/s                            | 1        | 0.8%    |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s                   | 1        | 0.8%    |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                      | 1        | 0.8%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.8%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 0.8%    |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.8%    |
| Unknown RAM Module 2GB DIMM 667MT/s                            | 1        | 0.8%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.8%    |
| Team RAM TEAMGROUP-UD4-3000 8192MB DIMM DDR4 3200MT/s          | 1        | 0.8%    |
| Team RAM Elite-800 2GB DIMM SDRAM 2048MT/s                     | 1        | 0.8%    |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                  | 1        | 0.8%    |
| SK hynix RAM HYMP112F72CP8N3-Y5 1024MB FB-DIMM DDR2 667MT/s    | 1        | 0.8%    |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.8%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s           | 1        | 0.8%    |
| SK hynix RAM HMA84GR7CJR4N-XN 32GB DIMM DDR4 3200MT/s          | 1        | 0.8%    |
| SK hynix RAM HMA82GR7CJR4N-VK 16384MB DIMM DDR4 2666MT/s       | 1        | 0.8%    |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s           | 1        | 0.8%    |
| Silicon Power RAM DBLT2GN568S 2GB DIMM DDR3 1333MT/s           | 1        | 0.8%    |
| SemsoTai RAM Module 8GB DIMM DDR4 2667MT/s                     | 1        | 0.8%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 1        | 0.8%    |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s           | 1        | 0.8%    |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s           | 1        | 0.8%    |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 0.8%    |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.8%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 42       | 39.62%  |
| DDR3    | 37       | 34.91%  |
| SDRAM   | 13       | 12.26%  |
| DDR2    | 5        | 4.72%   |
| DDR5    | 4        | 3.77%   |
| Unknown | 3        | 2.83%   |
| LPDDR4  | 1        | 0.94%   |
| DRAM    | 1        | 0.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 100      | 95.24%  |
| SODIMM  | 4        | 3.81%   |
| FB-DIMM | 1        | 0.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 47       | 43.12%  |
| 2048  | 18       | 16.51%  |
| 4096  | 16       | 14.68%  |
| 32768 | 14       | 12.84%  |
| 16384 | 13       | 11.93%  |
| 1024  | 1        | 0.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 30       | 26.79%  |
| 3200    | 16       | 14.29%  |
| 1333    | 7        | 6.25%   |
| 2667    | 6        | 5.36%   |
| 2400    | 5        | 4.46%   |
| 667     | 5        | 4.46%   |
| Unknown | 5        | 4.46%   |
| 3600    | 4        | 3.57%   |
| 800     | 4        | 3.57%   |
| 5200    | 3        | 2.68%   |
| 3933    | 3        | 2.68%   |
| 3733    | 3        | 2.68%   |
| 2133    | 3        | 2.68%   |
| 1800    | 3        | 2.68%   |
| 1867    | 2        | 1.79%   |
| 1866    | 2        | 1.79%   |
| 1066    | 2        | 1.79%   |
| 4800    | 1        | 0.89%   |
| 3666    | 1        | 0.89%   |
| 3534    | 1        | 0.89%   |
| 3466    | 1        | 0.89%   |
| 3000    | 1        | 0.89%   |
| 2933    | 1        | 0.89%   |
| 2666    | 1        | 0.89%   |
| 2048    | 1        | 0.89%   |
| 1067    | 1        | 0.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 30%     |
| Hewlett-Packard     | 2        | 20%     |
| Brother Industries  | 2        | 20%     |
| Seiko Epson         | 1        | 10%     |
| Prolific Technology | 1        | 10%     |
| Canon               | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung SCX-3400 Series       | 3        | 30%     |
| Seiko Epson L310 Series       | 1        | 10%     |
| Prolific PL2305 Parallel Port | 1        | 10%     |
| HP Ink Tank 110 series        | 1        | 10%     |
| HP DeskJet F4200 series       | 1        | 10%     |
| Canon E410 series             | 1        | 10%     |
| Brother DCP-J105              | 1        | 10%     |
| Brother DCP-1610W             | 1        | 10%     |

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
| Logitech                      | 11       | 40.74%  |
| Generalplus Technology        | 3        | 11.11%  |
| YGTek                         | 2        | 7.41%   |
| Microdia                      | 2        | 7.41%   |
| Apple                         | 2        | 7.41%   |
| WCM_USB                       | 1        | 3.7%    |
| Sunplus Innovation Technology | 1        | 3.7%    |
| Realtek Semiconductor         | 1        | 3.7%    |
| Lenovo                        | 1        | 3.7%    |
| Jieli Technology              | 1        | 3.7%    |
| Genesys Logic                 | 1        | 3.7%    |
| ARC International             | 1        | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 3        | 11.11%  |
| YGTek Webcam                             | 2        | 7.41%   |
| Microdia USB Camera                      | 2        | 7.41%   |
| Logitech Webcam C170                     | 2        | 7.41%   |
| Generalplus 808 Camera #9 (web-cam mode) | 2        | 7.41%   |
| Apple iPhone 5/5C/5S/6/SE                | 2        | 7.41%   |
| WCM_USB WEB CAM                          | 1        | 3.7%    |
| Sunplus WEBCAM ESSENTIELB W1             | 1        | 3.7%    |
| Realtek HP High Definition 1MP Webcam    | 1        | 3.7%    |
| Logitech Webcam C310                     | 1        | 3.7%    |
| Logitech Webcam C250                     | 1        | 3.7%    |
| Logitech Webcam B500                     | 1        | 3.7%    |
| Logitech HD Webcam C510                  | 1        | 3.7%    |
| Logitech HD Pro Webcam C920              | 1        | 3.7%    |
| Logitech C920 PRO HD Webcam              | 1        | 3.7%    |
| Lenovo FHD Webcam                        | 1        | 3.7%    |
| Jieli USB PHY 2.0                        | 1        | 3.7%    |
| Genesys Logic Camera                     | 1        | 3.7%    |
| Generalplus GENERAL WEBCAM               | 1        | 3.7%    |
| ARC International Camera                 | 1        | 3.7%    |

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
| 0     | 156      | 79.59%  |
| 1     | 37       | 18.88%  |
| 6     | 1        | 0.51%   |
| 3     | 1        | 0.51%   |
| 2     | 1        | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 18       | 42.86%  |
| Net/wireless             | 13       | 30.95%  |
| Communication controller | 4        | 9.52%   |
| Unassigned class         | 3        | 7.14%   |
| Sound                    | 2        | 4.76%   |
| Storage/ide              | 1        | 2.38%   |
| Network                  | 1        | 2.38%   |

