Linux in Brazil - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Brazil/Desktop/README.md) and [notebooks](/Location/Brazil/Notebook/README.md).

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

Total: 15512

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion 11 x360 PC         | Notebook    | [a1271c4465](https://linux-hardware.org/?probe=a1271c4465) | May 07, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [1140eb8bbd](https://linux-hardware.org/?probe=1140eb8bbd) | May 07, 2022 |
| Positivo      | POS-MI945AA                 | Desktop     | [dffab0e390](https://linux-hardware.org/?probe=dffab0e390) | May 07, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [5790e8a0cb](https://linux-hardware.org/?probe=5790e8a0cb) | May 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [39beda4841](https://linux-hardware.org/?probe=39beda4841) | May 07, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [3ded76a717](https://linux-hardware.org/?probe=3ded76a717) | May 07, 2022 |
| HP            | ProBook 645 G1              | Notebook    | [c8bd8caf2f](https://linux-hardware.org/?probe=c8bd8caf2f) | May 07, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [632a2af548](https://linux-hardware.org/?probe=632a2af548) | May 07, 2022 |
| Samsung       | 550XDA                      | Notebook    | [a616d83a41](https://linux-hardware.org/?probe=a616d83a41) | May 07, 2022 |
| MSI           | 880GMA-E35                  | Desktop     | [a2998f652e](https://linux-hardware.org/?probe=a2998f652e) | May 07, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Positivo      | POS-PIH81DI                 | Desktop     | [f7b64e05f8](https://linux-hardware.org/?probe=f7b64e05f8) | May 06, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [6a3cbcae26](https://linux-hardware.org/?probe=6a3cbcae26) | May 06, 2022 |
| MSI           | 880GMA-E35                  | Desktop     | [862de68566](https://linux-hardware.org/?probe=862de68566) | May 06, 2022 |
| Gateway       | NV55C                       | Notebook    | [2cbbfa9c42](https://linux-hardware.org/?probe=2cbbfa9c42) | May 06, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f298dfd02a](https://linux-hardware.org/?probe=f298dfd02a) | May 06, 2022 |
| Intel         | H55                         | Desktop     | [138637d12c](https://linux-hardware.org/?probe=138637d12c) | May 06, 2022 |
| MSI           | B550M PRO-DASH              | Desktop     | [585987ecf7](https://linux-hardware.org/?probe=585987ecf7) | May 06, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [e2b06a4a28](https://linux-hardware.org/?probe=e2b06a4a28) | May 05, 2022 |
| Positivo      | POS-PARS760GCD              | Desktop     | [dfc00dfd71](https://linux-hardware.org/?probe=dfc00dfd71) | May 05, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [ddc4d88d20](https://linux-hardware.org/?probe=ddc4d88d20) | May 05, 2022 |
| Intel         | H61                         | Desktop     | [ef0e75557e](https://linux-hardware.org/?probe=ef0e75557e) | May 05, 2022 |
| Philco        | 10D                         | Notebook    | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | Notebook    | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [9d466643e0](https://linux-hardware.org/?probe=9d466643e0) | May 05, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [f03b0f28ef](https://linux-hardware.org/?probe=f03b0f28ef) | May 05, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [af3af97b7d](https://linux-hardware.org/?probe=af3af97b7d) | May 05, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [8ca57528af](https://linux-hardware.org/?probe=8ca57528af) | May 04, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [3bc61ca207](https://linux-hardware.org/?probe=3bc61ca207) | May 04, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [8d41e2310f](https://linux-hardware.org/?probe=8d41e2310f) | May 04, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [f1e24327ba](https://linux-hardware.org/?probe=f1e24327ba) | May 04, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [1cd8020334](https://linux-hardware.org/?probe=1cd8020334) | May 04, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [3c081a7012](https://linux-hardware.org/?probe=3c081a7012) | May 04, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [3cab561b32](https://linux-hardware.org/?probe=3cab561b32) | May 04, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [2b5958e2dd](https://linux-hardware.org/?probe=2b5958e2dd) | May 04, 2022 |
| Samsung       | 740U3M                      | Convertible | [4ba9324ca5](https://linux-hardware.org/?probe=4ba9324ca5) | May 04, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [f5e954ea5e](https://linux-hardware.org/?probe=f5e954ea5e) | May 04, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N70... | Notebook    | [9da4b1ddc5](https://linux-hardware.org/?probe=9da4b1ddc5) | May 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [2136362d58](https://linux-hardware.org/?probe=2136362d58) | May 03, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [1d4b493814](https://linux-hardware.org/?probe=1d4b493814) | May 03, 2022 |
| Lenovo        | SDK0E50515 STD              | Desktop     | [9a67a9ecfe](https://linux-hardware.org/?probe=9a67a9ecfe) | May 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [f9db97e5d3](https://linux-hardware.org/?probe=f9db97e5d3) | May 03, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [61f313c65a](https://linux-hardware.org/?probe=61f313c65a) | May 03, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [bd62b32976](https://linux-hardware.org/?probe=bd62b32976) | May 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4516542417](https://linux-hardware.org/?probe=4516542417) | May 03, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [489d69a9ee](https://linux-hardware.org/?probe=489d69a9ee) | May 03, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [fd6a65f99a](https://linux-hardware.org/?probe=fd6a65f99a) | May 03, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [914e422e76](https://linux-hardware.org/?probe=914e422e76) | May 03, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [f2de7ca21b](https://linux-hardware.org/?probe=f2de7ca21b) | May 03, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [46a54445e0](https://linux-hardware.org/?probe=46a54445e0) | May 03, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [f749343aee](https://linux-hardware.org/?probe=f749343aee) | May 03, 2022 |
| HP            | Pavilion dv6                | Notebook    | [7587fe8761](https://linux-hardware.org/?probe=7587fe8761) | May 03, 2022 |
| HP            | Pavilion dv6                | Notebook    | [bf79099573](https://linux-hardware.org/?probe=bf79099573) | May 03, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [ab72c3ae3f](https://linux-hardware.org/?probe=ab72c3ae3f) | May 03, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [c47758f125](https://linux-hardware.org/?probe=c47758f125) | May 03, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [ba926f40d8](https://linux-hardware.org/?probe=ba926f40d8) | May 02, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [2b340d6955](https://linux-hardware.org/?probe=2b340d6955) | May 02, 2022 |
| JINGSHA       | Unknown                     | Desktop     | [94dd890d71](https://linux-hardware.org/?probe=94dd890d71) | May 02, 2022 |
| Avell High... | B.ON                        | Notebook    | [5de402efe5](https://linux-hardware.org/?probe=5de402efe5) | May 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [78de3c2817](https://linux-hardware.org/?probe=78de3c2817) | May 02, 2022 |
| Intel         | H61M-DS2                    | Desktop     | [78f738c029](https://linux-hardware.org/?probe=78f738c029) | May 02, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [f571b0dc6f](https://linux-hardware.org/?probe=f571b0dc6f) | May 02, 2022 |
| Intel         | H61M-DS2                    | Desktop     | [10c3d8c8a0](https://linux-hardware.org/?probe=10c3d8c8a0) | May 02, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [88080c45b1](https://linux-hardware.org/?probe=88080c45b1) | May 02, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [8fbdd05b2a](https://linux-hardware.org/?probe=8fbdd05b2a) | May 02, 2022 |
| Toshiba       | Satellite M55               | Notebook    | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [72f6ebfc11](https://linux-hardware.org/?probe=72f6ebfc11) | May 01, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [0205c9da07](https://linux-hardware.org/?probe=0205c9da07) | May 01, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [5ad527dcd2](https://linux-hardware.org/?probe=5ad527dcd2) | May 01, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [85d403928b](https://linux-hardware.org/?probe=85d403928b) | May 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [414334d8e3](https://linux-hardware.org/?probe=414334d8e3) | May 01, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [cb532b211e](https://linux-hardware.org/?probe=cb532b211e) | May 01, 2022 |
| LG Electro... | P430-G.BC41P1               | Notebook    | [527905ca3b](https://linux-hardware.org/?probe=527905ca3b) | May 01, 2022 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [53f6946eba](https://linux-hardware.org/?probe=53f6946eba) | May 01, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [6d0ad0b8f2](https://linux-hardware.org/?probe=6d0ad0b8f2) | May 01, 2022 |
| Acer          | F5-573                      | Notebook    | [47c8b0dd51](https://linux-hardware.org/?probe=47c8b0dd51) | May 01, 2022 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [a9a49f094d](https://linux-hardware.org/?probe=a9a49f094d) | May 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [e91d9c480d](https://linux-hardware.org/?probe=e91d9c480d) | May 01, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [52c4caf797](https://linux-hardware.org/?probe=52c4caf797) | May 01, 2022 |
| Positivo      | POS-EIH110EA                | Desktop     | [d0a20e98ac](https://linux-hardware.org/?probe=d0a20e98ac) | May 01, 2022 |
| Acer          | Aspire 5741                 | Notebook    | [f82c315ff4](https://linux-hardware.org/?probe=f82c315ff4) | May 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [34df7ab926](https://linux-hardware.org/?probe=34df7ab926) | May 01, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [31fdda39b1](https://linux-hardware.org/?probe=31fdda39b1) | May 01, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [534476ac99](https://linux-hardware.org/?probe=534476ac99) | Apr 30, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [5a3254d19c](https://linux-hardware.org/?probe=5a3254d19c) | Apr 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [589f58c857](https://linux-hardware.org/?probe=589f58c857) | Apr 30, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [3782e39a43](https://linux-hardware.org/?probe=3782e39a43) | Apr 30, 2022 |
| Positivo      | POS-ECIG41BSA               | Desktop     | [b622f7f43f](https://linux-hardware.org/?probe=b622f7f43f) | Apr 30, 2022 |
| Acer          | V5-171                      | Notebook    | [a07ba20ff0](https://linux-hardware.org/?probe=a07ba20ff0) | Apr 30, 2022 |
| Dell          | System XPS L502X            | Notebook    | [77e1846d8d](https://linux-hardware.org/?probe=77e1846d8d) | Apr 30, 2022 |
| Itautec       | Infoway w7535               | Notebook    | [ac87d9e508](https://linux-hardware.org/?probe=ac87d9e508) | Apr 30, 2022 |
| Positivo      | S14CT01                     | Notebook    | [7260e4f199](https://linux-hardware.org/?probe=7260e4f199) | Apr 30, 2022 |
| Lenovo        | G40-70 80GA                 | Notebook    | [fcd20cb250](https://linux-hardware.org/?probe=fcd20cb250) | Apr 30, 2022 |
| Positivo      | S14CT01                     | Notebook    | [dec0b170c2](https://linux-hardware.org/?probe=dec0b170c2) | Apr 30, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [8074a86bc7](https://linux-hardware.org/?probe=8074a86bc7) | Apr 30, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [6afc1a0af8](https://linux-hardware.org/?probe=6afc1a0af8) | Apr 30, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [89def966af](https://linux-hardware.org/?probe=89def966af) | Apr 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [627cbf0981](https://linux-hardware.org/?probe=627cbf0981) | Apr 30, 2022 |
| JINGSHA       | Unknown                     | Desktop     | [e1b9c4eab0](https://linux-hardware.org/?probe=e1b9c4eab0) | Apr 30, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [70efbbb6c7](https://linux-hardware.org/?probe=70efbbb6c7) | Apr 30, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | Desktop     | [2f215a330a](https://linux-hardware.org/?probe=2f215a330a) | Apr 30, 2022 |
| Philco        | 14I                         | Notebook    | [03bb0fdeef](https://linux-hardware.org/?probe=03bb0fdeef) | Apr 30, 2022 |
| Acer          | V5-171                      | Notebook    | [8500a1c376](https://linux-hardware.org/?probe=8500a1c376) | Apr 30, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [e1369b0428](https://linux-hardware.org/?probe=e1369b0428) | Apr 29, 2022 |
| Avell High... | B.ON                        | Notebook    | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| Unknown       | Intel X79                   | Desktop     | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | Desktop     | [a5743a1922](https://linux-hardware.org/?probe=a5743a1922) | Apr 29, 2022 |
| PCWare        | IPX4105G Pro                | Desktop     | [073d789fc4](https://linux-hardware.org/?probe=073d789fc4) | Apr 29, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [6a5bc03a3a](https://linux-hardware.org/?probe=6a5bc03a3a) | Apr 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [eecc63a9af](https://linux-hardware.org/?probe=eecc63a9af) | Apr 29, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [15a2c261da](https://linux-hardware.org/?probe=15a2c261da) | Apr 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [a5d8e73a23](https://linux-hardware.org/?probe=a5d8e73a23) | Apr 28, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [be4ab0fd27](https://linux-hardware.org/?probe=be4ab0fd27) | Apr 28, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [4ff968ef61](https://linux-hardware.org/?probe=4ff968ef61) | Apr 28, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [ca65be05f0](https://linux-hardware.org/?probe=ca65be05f0) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [995f77010e](https://linux-hardware.org/?probe=995f77010e) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [e2293170b3](https://linux-hardware.org/?probe=e2293170b3) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [8105c6bf09](https://linux-hardware.org/?probe=8105c6bf09) | Apr 28, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [11b568f82d](https://linux-hardware.org/?probe=11b568f82d) | Apr 28, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [7867dbccf7](https://linux-hardware.org/?probe=7867dbccf7) | Apr 28, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [0b88a7422d](https://linux-hardware.org/?probe=0b88a7422d) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [a63dc69025](https://linux-hardware.org/?probe=a63dc69025) | Apr 28, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [39efe61675](https://linux-hardware.org/?probe=39efe61675) | Apr 28, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [56d52ea265](https://linux-hardware.org/?probe=56d52ea265) | Apr 28, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f5a5a69887](https://linux-hardware.org/?probe=f5a5a69887) | Apr 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [49396d0706](https://linux-hardware.org/?probe=49396d0706) | Apr 28, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [740919a383](https://linux-hardware.org/?probe=740919a383) | Apr 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [695d362d8f](https://linux-hardware.org/?probe=695d362d8f) | Apr 27, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d394f4e0d9](https://linux-hardware.org/?probe=d394f4e0d9) | Apr 27, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [c82cd4f476](https://linux-hardware.org/?probe=c82cd4f476) | Apr 27, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [7c99d7d4c5](https://linux-hardware.org/?probe=7c99d7d4c5) | Apr 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [e77a313003](https://linux-hardware.org/?probe=e77a313003) | Apr 27, 2022 |
| Lenovo        | ThinkPad T480 20L6SJN400    | Notebook    | [294a5ef80c](https://linux-hardware.org/?probe=294a5ef80c) | Apr 27, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [718c932097](https://linux-hardware.org/?probe=718c932097) | Apr 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [b7ac79ff8f](https://linux-hardware.org/?probe=b7ac79ff8f) | Apr 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [593ee8ccf3](https://linux-hardware.org/?probe=593ee8ccf3) | Apr 27, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [8f10e59515](https://linux-hardware.org/?probe=8f10e59515) | Apr 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9e7c77d251](https://linux-hardware.org/?probe=9e7c77d251) | Apr 27, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [a49e25f2b8](https://linux-hardware.org/?probe=a49e25f2b8) | Apr 27, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [8dafe7350b](https://linux-hardware.org/?probe=8dafe7350b) | Apr 27, 2022 |
| Positivo      | S14SL01                     | Notebook    | [f8bdbe707d](https://linux-hardware.org/?probe=f8bdbe707d) | Apr 27, 2022 |
| Dell          | Latitude 5410               | Notebook    | [1a67b58656](https://linux-hardware.org/?probe=1a67b58656) | Apr 27, 2022 |
| MSI           | Z97-G45 GAMING              | Desktop     | [6660cb5133](https://linux-hardware.org/?probe=6660cb5133) | Apr 27, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [f3c9dd19da](https://linux-hardware.org/?probe=f3c9dd19da) | Apr 26, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [bca722d45d](https://linux-hardware.org/?probe=bca722d45d) | Apr 26, 2022 |
| Itautec       | NT 2030                     | Desktop     | [ce556d6808](https://linux-hardware.org/?probe=ce556d6808) | Apr 26, 2022 |
| Google        | Relm                        | Notebook    | [edd0a8864b](https://linux-hardware.org/?probe=edd0a8864b) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d4b7580074](https://linux-hardware.org/?probe=d4b7580074) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d994ff2a13](https://linux-hardware.org/?probe=d994ff2a13) | Apr 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [c9b8a75b0a](https://linux-hardware.org/?probe=c9b8a75b0a) | Apr 26, 2022 |
| MSI           | MS-6701                     | Desktop     | [8853d92523](https://linux-hardware.org/?probe=8853d92523) | Apr 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [64cd863479](https://linux-hardware.org/?probe=64cd863479) | Apr 26, 2022 |
| MSI           | MS-6701                     | Desktop     | [0bde2af604](https://linux-hardware.org/?probe=0bde2af604) | Apr 26, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [a42b1cda2c](https://linux-hardware.org/?probe=a42b1cda2c) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [128cdc0a61](https://linux-hardware.org/?probe=128cdc0a61) | Apr 26, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [0adfe1cfb9](https://linux-hardware.org/?probe=0adfe1cfb9) | Apr 25, 2022 |
| Toshiba       | Satellite S55-C             | Notebook    | [05afb55e10](https://linux-hardware.org/?probe=05afb55e10) | Apr 25, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [f99a1a0591](https://linux-hardware.org/?probe=f99a1a0591) | Apr 25, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [89debf3e0e](https://linux-hardware.org/?probe=89debf3e0e) | Apr 25, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [47a349b8db](https://linux-hardware.org/?probe=47a349b8db) | Apr 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [8f76034215](https://linux-hardware.org/?probe=8f76034215) | Apr 25, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [319cbc94dd](https://linux-hardware.org/?probe=319cbc94dd) | Apr 25, 2022 |
| Sony          | SVS13A25PBS                 | Notebook    | [c1be74b619](https://linux-hardware.org/?probe=c1be74b619) | Apr 25, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [7b82407cba](https://linux-hardware.org/?probe=7b82407cba) | Apr 25, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [06ecfd2026](https://linux-hardware.org/?probe=06ecfd2026) | Apr 25, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [7423afe5a1](https://linux-hardware.org/?probe=7423afe5a1) | Apr 25, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [6a67f6de58](https://linux-hardware.org/?probe=6a67f6de58) | Apr 25, 2022 |
| Supermicro    | X7DWT                       | Desktop     | [d7d46c682c](https://linux-hardware.org/?probe=d7d46c682c) | Apr 25, 2022 |
| Supermicro    | X7DWT                       | Desktop     | [4570a2caf7](https://linux-hardware.org/?probe=4570a2caf7) | Apr 25, 2022 |
| Google        | Bobba                       | Notebook    | [008afa9913](https://linux-hardware.org/?probe=008afa9913) | Apr 25, 2022 |
| Sony          | VPCEH25FM                   | Notebook    | [bceedddb01](https://linux-hardware.org/?probe=bceedddb01) | Apr 24, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [b0a2546f9f](https://linux-hardware.org/?probe=b0a2546f9f) | Apr 24, 2022 |
| Positivo      | POS-EIBTDB                  | Desktop     | [2b6822eb50](https://linux-hardware.org/?probe=2b6822eb50) | Apr 24, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [4d499dd1d3](https://linux-hardware.org/?probe=4d499dd1d3) | Apr 24, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| Biostar       | NM70I-1017U                 | Desktop     | [c27061c8f4](https://linux-hardware.org/?probe=c27061c8f4) | Apr 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [c9c576f90b](https://linux-hardware.org/?probe=c9c576f90b) | Apr 24, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [20d9884cb6](https://linux-hardware.org/?probe=20d9884cb6) | Apr 24, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [dac092d7bc](https://linux-hardware.org/?probe=dac092d7bc) | Apr 24, 2022 |
| Avell High... | C65 MOB                     | Notebook    | [b8e185c194](https://linux-hardware.org/?probe=b8e185c194) | Apr 24, 2022 |
| MSI           | H81M-E33                    | Desktop     | [a56e939c9f](https://linux-hardware.org/?probe=a56e939c9f) | Apr 23, 2022 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [4f5bd4cb03](https://linux-hardware.org/?probe=4f5bd4cb03) | Apr 23, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [d5918f0d93](https://linux-hardware.org/?probe=d5918f0d93) | Apr 23, 2022 |
| Google        | Bobba                       | Notebook    | [a5c612d7ec](https://linux-hardware.org/?probe=a5c612d7ec) | Apr 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3e3f727deb](https://linux-hardware.org/?probe=3e3f727deb) | Apr 23, 2022 |
| Pegatron      | IPMH61P1                    | Desktop     | [73ac7e5e3e](https://linux-hardware.org/?probe=73ac7e5e3e) | Apr 23, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [e4d563d75b](https://linux-hardware.org/?probe=e4d563d75b) | Apr 23, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [8d16b89bdb](https://linux-hardware.org/?probe=8d16b89bdb) | Apr 23, 2022 |
| MSI           | G41M-S01                    | Desktop     | [cd81f73a4d](https://linux-hardware.org/?probe=cd81f73a4d) | Apr 23, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [6e05fa6a88](https://linux-hardware.org/?probe=6e05fa6a88) | Apr 23, 2022 |
| Intel         | H81                         | Desktop     | [9720e797c4](https://linux-hardware.org/?probe=9720e797c4) | Apr 23, 2022 |
| Intel         | H81                         | Desktop     | [2c89989829](https://linux-hardware.org/?probe=2c89989829) | Apr 23, 2022 |
| Gateway       | NE570                       | Notebook    | [1cb22c0c86](https://linux-hardware.org/?probe=1cb22c0c86) | Apr 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [f45406567e](https://linux-hardware.org/?probe=f45406567e) | Apr 23, 2022 |
| Lenovo        | ThinkPad P50 20EQS64N1N     | Notebook    | [c3d792a237](https://linux-hardware.org/?probe=c3d792a237) | Apr 23, 2022 |
| Pegatron      | IPMH61P1                    | Desktop     | [26a1791ea4](https://linux-hardware.org/?probe=26a1791ea4) | Apr 22, 2022 |
| Google        | Bobba                       | Notebook    | [5ad66cbf53](https://linux-hardware.org/?probe=5ad66cbf53) | Apr 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [e97ab3fc6c](https://linux-hardware.org/?probe=e97ab3fc6c) | Apr 22, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [9eeb0ced39](https://linux-hardware.org/?probe=9eeb0ced39) | Apr 22, 2022 |
| Samsung       | 550XDA                      | Notebook    | [379e724ba3](https://linux-hardware.org/?probe=379e724ba3) | Apr 22, 2022 |
| ASUSTek       | P7H55-M BR                  | Desktop     | [e3c7a6ade9](https://linux-hardware.org/?probe=e3c7a6ade9) | Apr 22, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [f3e50d22aa](https://linux-hardware.org/?probe=f3e50d22aa) | Apr 22, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [36b0510bae](https://linux-hardware.org/?probe=36b0510bae) | Apr 22, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [d90f38b2ad](https://linux-hardware.org/?probe=d90f38b2ad) | Apr 22, 2022 |
| Samsung       | 550XDA                      | Notebook    | [a3011752e2](https://linux-hardware.org/?probe=a3011752e2) | Apr 22, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [c4cfcaf69e](https://linux-hardware.org/?probe=c4cfcaf69e) | Apr 22, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [b5dbaddd84](https://linux-hardware.org/?probe=b5dbaddd84) | Apr 22, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [f5f36d1c44](https://linux-hardware.org/?probe=f5f36d1c44) | Apr 22, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0150424029](https://linux-hardware.org/?probe=0150424029) | Apr 22, 2022 |
| Dell          | 073MMW A03                  | Desktop     | [f3ecf74145](https://linux-hardware.org/?probe=f3ecf74145) | Apr 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [83c11db3f8](https://linux-hardware.org/?probe=83c11db3f8) | Apr 22, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [05dfaaa5c7](https://linux-hardware.org/?probe=05dfaaa5c7) | Apr 21, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [6a3938aa9c](https://linux-hardware.org/?probe=6a3938aa9c) | Apr 21, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [db446247f1](https://linux-hardware.org/?probe=db446247f1) | Apr 21, 2022 |
| Intel         | X99                         | Desktop     | [f7410bb2fd](https://linux-hardware.org/?probe=f7410bb2fd) | Apr 21, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [b5f1325640](https://linux-hardware.org/?probe=b5f1325640) | Apr 21, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [f68123a23d](https://linux-hardware.org/?probe=f68123a23d) | Apr 21, 2022 |
| Acer          | Aspire 1410                 | Notebook    | [703c2ec84a](https://linux-hardware.org/?probe=703c2ec84a) | Apr 21, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [49bb0bd1ff](https://linux-hardware.org/?probe=49bb0bd1ff) | Apr 21, 2022 |
| Positivo      | W940TU                      | Notebook    | [4d03effd28](https://linux-hardware.org/?probe=4d03effd28) | Apr 20, 2022 |
| Positivo      | W940TU                      | Notebook    | [971493b883](https://linux-hardware.org/?probe=971493b883) | Apr 20, 2022 |
| Philco        | Unknown                     | Notebook    | [16719246ff](https://linux-hardware.org/?probe=16719246ff) | Apr 20, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c568c44d81](https://linux-hardware.org/?probe=c568c44d81) | Apr 20, 2022 |
| Samsung       | 550XDA                      | Notebook    | [66cb0691e0](https://linux-hardware.org/?probe=66cb0691e0) | Apr 20, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [5cb77cb68e](https://linux-hardware.org/?probe=5cb77cb68e) | Apr 20, 2022 |
| HP            | Pavilion dv6                | Notebook    | [8a3a510921](https://linux-hardware.org/?probe=8a3a510921) | Apr 20, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [5593faa826](https://linux-hardware.org/?probe=5593faa826) | Apr 20, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [5549666ce7](https://linux-hardware.org/?probe=5549666ce7) | Apr 20, 2022 |
| Intel         | W7650                       | Notebook    | [edb281c81e](https://linux-hardware.org/?probe=edb281c81e) | Apr 20, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [05daf3f64b](https://linux-hardware.org/?probe=05daf3f64b) | Apr 20, 2022 |
| Intel         | W7650                       | Notebook    | [cdf0885f07](https://linux-hardware.org/?probe=cdf0885f07) | Apr 20, 2022 |
| Positivo      | Q464C                       | Notebook    | [b68073fbe4](https://linux-hardware.org/?probe=b68073fbe4) | Apr 20, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d126b742fe](https://linux-hardware.org/?probe=d126b742fe) | Apr 20, 2022 |
| Positivo      | Q464C                       | Notebook    | [31c6ba5157](https://linux-hardware.org/?probe=31c6ba5157) | Apr 20, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [888cf862fc](https://linux-hardware.org/?probe=888cf862fc) | Apr 20, 2022 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [0aa2639b59](https://linux-hardware.org/?probe=0aa2639b59) | Apr 20, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [288c8e99b2](https://linux-hardware.org/?probe=288c8e99b2) | Apr 20, 2022 |
| Acer          | Aspire E5-574               | Notebook    | [6f1f7031bb](https://linux-hardware.org/?probe=6f1f7031bb) | Apr 19, 2022 |
| HP            | Pavilion Laptop 14-bk0xx    | Notebook    | [61ebff551a](https://linux-hardware.org/?probe=61ebff551a) | Apr 19, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [4b9d2c67fe](https://linux-hardware.org/?probe=4b9d2c67fe) | Apr 19, 2022 |
| Dell          | Latitude 3410               | Notebook    | [d932874d9c](https://linux-hardware.org/?probe=d932874d9c) | Apr 19, 2022 |
| Positivo      | N1250                       | Notebook    | [c2dfeaab53](https://linux-hardware.org/?probe=c2dfeaab53) | Apr 19, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [0f924d06d6](https://linux-hardware.org/?probe=0f924d06d6) | Apr 19, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [3654d1f0fa](https://linux-hardware.org/?probe=3654d1f0fa) | Apr 19, 2022 |
| Samsung       | 370E4K                      | Notebook    | [b3d7575f01](https://linux-hardware.org/?probe=b3d7575f01) | Apr 18, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [746e2ea0d2](https://linux-hardware.org/?probe=746e2ea0d2) | Apr 18, 2022 |
| MSI           | Boston                      | Desktop     | [ee1d487c1e](https://linux-hardware.org/?probe=ee1d487c1e) | Apr 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [b903351314](https://linux-hardware.org/?probe=b903351314) | Apr 18, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [e9f6594677](https://linux-hardware.org/?probe=e9f6594677) | Apr 18, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [d6b72a0160](https://linux-hardware.org/?probe=d6b72a0160) | Apr 18, 2022 |
| Avell High... | B.ON                        | Notebook    | [6f37e0aabc](https://linux-hardware.org/?probe=6f37e0aabc) | Apr 18, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [1b3267b605](https://linux-hardware.org/?probe=1b3267b605) | Apr 18, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N70... | Notebook    | [db5f56be25](https://linux-hardware.org/?probe=db5f56be25) | Apr 18, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [f7888cc252](https://linux-hardware.org/?probe=f7888cc252) | Apr 18, 2022 |
| Gigabyte      | G41MT-ES2L                  | Desktop     | [fbeec44852](https://linux-hardware.org/?probe=fbeec44852) | Apr 18, 2022 |
| Intel         | Unknown                     | Desktop     | [b734cf3221](https://linux-hardware.org/?probe=b734cf3221) | Apr 17, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [e2462a2328](https://linux-hardware.org/?probe=e2462a2328) | Apr 17, 2022 |
| Positivo      | Mobile                      | Notebook    | [0cfa1a5e22](https://linux-hardware.org/?probe=0cfa1a5e22) | Apr 17, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [6bdbd5de5d](https://linux-hardware.org/?probe=6bdbd5de5d) | Apr 17, 2022 |
| Gateway       | NE570                       | Notebook    | [d4b1bdce70](https://linux-hardware.org/?probe=d4b1bdce70) | Apr 17, 2022 |
| Gigabyte      | 970A-UD3                    | Desktop     | [7128f5f2b4](https://linux-hardware.org/?probe=7128f5f2b4) | Apr 17, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [4def2a51dc](https://linux-hardware.org/?probe=4def2a51dc) | Apr 17, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [8f8f3b74e6](https://linux-hardware.org/?probe=8f8f3b74e6) | Apr 16, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [28c58e21e0](https://linux-hardware.org/?probe=28c58e21e0) | Apr 16, 2022 |
| MSI           | MS-7438 100                 | Desktop     | [bac261ba9a](https://linux-hardware.org/?probe=bac261ba9a) | Apr 16, 2022 |
| Positivo      | H14BU08                     | Notebook    | [43d44df3d2](https://linux-hardware.org/?probe=43d44df3d2) | Apr 16, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [7a3fa3e4a4](https://linux-hardware.org/?probe=7a3fa3e4a4) | Apr 16, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [dfd89c6a60](https://linux-hardware.org/?probe=dfd89c6a60) | Apr 16, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [5f7dafa5b9](https://linux-hardware.org/?probe=5f7dafa5b9) | Apr 16, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [e9e45e7f91](https://linux-hardware.org/?probe=e9e45e7f91) | Apr 16, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [e51d0544a1](https://linux-hardware.org/?probe=e51d0544a1) | Apr 16, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7e44758885](https://linux-hardware.org/?probe=7e44758885) | Apr 16, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b07e7e9974](https://linux-hardware.org/?probe=b07e7e9974) | Apr 16, 2022 |
| Positivo B... | VJC141F11X-B0111L           | Notebook    | [5ea499eca7](https://linux-hardware.org/?probe=5ea499eca7) | Apr 16, 2022 |
| Unknown       | Unknown                     | Soc         | [478b3488e7](https://linux-hardware.org/?probe=478b3488e7) | Apr 16, 2022 |
| Dell          | 0VHXCD A03                  | Desktop     | [290987223e](https://linux-hardware.org/?probe=290987223e) | Apr 16, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [27d5f97167](https://linux-hardware.org/?probe=27d5f97167) | Apr 16, 2022 |
| HP            | Pavilion dv6                | Notebook    | [639a7422d8](https://linux-hardware.org/?probe=639a7422d8) | Apr 16, 2022 |
| Positivo      | C464C                       | Convertible | [c4bf224f57](https://linux-hardware.org/?probe=c4bf224f57) | Apr 15, 2022 |
| Compaq        | Presario CQ-29              | Notebook    | [4c37a60084](https://linux-hardware.org/?probe=4c37a60084) | Apr 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [3b30ef3d55](https://linux-hardware.org/?probe=3b30ef3d55) | Apr 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | Desktop     | [0a8d0e5302](https://linux-hardware.org/?probe=0a8d0e5302) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [5302420f94](https://linux-hardware.org/?probe=5302420f94) | Apr 15, 2022 |
| Dell          | Latitude 5420               | Notebook    | [7b97392ed4](https://linux-hardware.org/?probe=7b97392ed4) | Apr 15, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [0646755403](https://linux-hardware.org/?probe=0646755403) | Apr 15, 2022 |
| Dell          | Latitude 5420               | Notebook    | [7ef3e515d9](https://linux-hardware.org/?probe=7ef3e515d9) | Apr 15, 2022 |
| Dell          | Inspiron 3481               | Notebook    | [69d336ac59](https://linux-hardware.org/?probe=69d336ac59) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [3e2989ae49](https://linux-hardware.org/?probe=3e2989ae49) | Apr 15, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [172be13d6d](https://linux-hardware.org/?probe=172be13d6d) | Apr 15, 2022 |
| GALAX         | A320M G10g                  | Desktop     | [958fc1bf94](https://linux-hardware.org/?probe=958fc1bf94) | Apr 14, 2022 |
| Itautec       | ST 4262 ST-4262 Padrao 0... | Desktop     | [1dd8e2f31b](https://linux-hardware.org/?probe=1dd8e2f31b) | Apr 14, 2022 |
| Dell          | XPS L322X                   | Notebook    | [eee5065a27](https://linux-hardware.org/?probe=eee5065a27) | Apr 14, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [dd5d897f4c](https://linux-hardware.org/?probe=dd5d897f4c) | Apr 14, 2022 |
| Dell          | 0YR541 A01                  | Desktop     | [f206c3667e](https://linux-hardware.org/?probe=f206c3667e) | Apr 14, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [d29ff8a54e](https://linux-hardware.org/?probe=d29ff8a54e) | Apr 14, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [8c6aae59db](https://linux-hardware.org/?probe=8c6aae59db) | Apr 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [83dda83cdf](https://linux-hardware.org/?probe=83dda83cdf) | Apr 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [92eaa72b3c](https://linux-hardware.org/?probe=92eaa72b3c) | Apr 14, 2022 |
| HP            | G42                         | Notebook    | [e717533860](https://linux-hardware.org/?probe=e717533860) | Apr 14, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [a7f25c6027](https://linux-hardware.org/?probe=a7f25c6027) | Apr 14, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [f8f13d5514](https://linux-hardware.org/?probe=f8f13d5514) | Apr 14, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [3752ecab33](https://linux-hardware.org/?probe=3752ecab33) | Apr 14, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a8061e68ff](https://linux-hardware.org/?probe=a8061e68ff) | Apr 14, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [417d3ab696](https://linux-hardware.org/?probe=417d3ab696) | Apr 14, 2022 |
| Gateway       | NE570                       | Notebook    | [3635e5c663](https://linux-hardware.org/?probe=3635e5c663) | Apr 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a5c9b7fc78](https://linux-hardware.org/?probe=a5c9b7fc78) | Apr 14, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [af418a6f28](https://linux-hardware.org/?probe=af418a6f28) | Apr 13, 2022 |
| Dell          | Inspiron 7560               | Notebook    | [1bb75ffe05](https://linux-hardware.org/?probe=1bb75ffe05) | Apr 13, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [645c74ef90](https://linux-hardware.org/?probe=645c74ef90) | Apr 13, 2022 |
| Megaware      | MW-G31T-M7                  | Desktop     | [3ac4860cb3](https://linux-hardware.org/?probe=3ac4860cb3) | Apr 13, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [4aeb8de6f6](https://linux-hardware.org/?probe=4aeb8de6f6) | Apr 13, 2022 |
| Lenovo        | BS145-15IIL 82HB            | Notebook    | [e595769424](https://linux-hardware.org/?probe=e595769424) | Apr 13, 2022 |
| Toshiba       | Satellite U845W             | Notebook    | [c8b77c70a6](https://linux-hardware.org/?probe=c8b77c70a6) | Apr 13, 2022 |
| Megaware      | MW-G31T-M7                  | Desktop     | [ce643cbdcd](https://linux-hardware.org/?probe=ce643cbdcd) | Apr 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [33cce38b5e](https://linux-hardware.org/?probe=33cce38b5e) | Apr 13, 2022 |
| Multilaser    | M11W                        | Notebook    | [4be432c77a](https://linux-hardware.org/?probe=4be432c77a) | Apr 13, 2022 |
| Avell High... | B.ON                        | Notebook    | [0e81f76e2b](https://linux-hardware.org/?probe=0e81f76e2b) | Apr 13, 2022 |
| Gateway       | NE570                       | Notebook    | [068d4c39f2](https://linux-hardware.org/?probe=068d4c39f2) | Apr 13, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [abebd4506d](https://linux-hardware.org/?probe=abebd4506d) | Apr 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [fad4436356](https://linux-hardware.org/?probe=fad4436356) | Apr 13, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [9fa510fc02](https://linux-hardware.org/?probe=9fa510fc02) | Apr 13, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d42dc1919c](https://linux-hardware.org/?probe=d42dc1919c) | Apr 13, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [080cbf45eb](https://linux-hardware.org/?probe=080cbf45eb) | Apr 13, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [85062520f7](https://linux-hardware.org/?probe=85062520f7) | Apr 13, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [e79417a89e](https://linux-hardware.org/?probe=e79417a89e) | Apr 13, 2022 |
| Positivo      | Mobile                      | Notebook    | [1bd294322c](https://linux-hardware.org/?probe=1bd294322c) | Apr 12, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [1ca06f94c7](https://linux-hardware.org/?probe=1ca06f94c7) | Apr 12, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [24545103f4](https://linux-hardware.org/?probe=24545103f4) | Apr 12, 2022 |
| ASUSTek       | SABERTOOTH 990FX R3.0       | Desktop     | [4f5a780267](https://linux-hardware.org/?probe=4f5a780267) | Apr 12, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [0e748100fa](https://linux-hardware.org/?probe=0e748100fa) | Apr 12, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [73bb0eeab0](https://linux-hardware.org/?probe=73bb0eeab0) | Apr 12, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [506a9d5a07](https://linux-hardware.org/?probe=506a9d5a07) | Apr 12, 2022 |
| ASUSTek       | X451CA                      | Notebook    | [865aec543f](https://linux-hardware.org/?probe=865aec543f) | Apr 12, 2022 |
| Toshiba       | STI 010433                  | Desktop     | [9eb114e523](https://linux-hardware.org/?probe=9eb114e523) | Apr 12, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [f4cb39e804](https://linux-hardware.org/?probe=f4cb39e804) | Apr 12, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [80c51dad27](https://linux-hardware.org/?probe=80c51dad27) | Apr 12, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [8879fa758a](https://linux-hardware.org/?probe=8879fa758a) | Apr 11, 2022 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [e2452fa831](https://linux-hardware.org/?probe=e2452fa831) | Apr 11, 2022 |
| Intel         | W7650                       | Notebook    | [4bd778e810](https://linux-hardware.org/?probe=4bd778e810) | Apr 11, 2022 |
| Dell          | Latitude 5420               | Notebook    | [8f23343086](https://linux-hardware.org/?probe=8f23343086) | Apr 11, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [4f13d38f2e](https://linux-hardware.org/?probe=4f13d38f2e) | Apr 11, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [0a89a1b47b](https://linux-hardware.org/?probe=0a89a1b47b) | Apr 11, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [6748a96716](https://linux-hardware.org/?probe=6748a96716) | Apr 11, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [4f465b1b2d](https://linux-hardware.org/?probe=4f465b1b2d) | Apr 11, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5738641fc9](https://linux-hardware.org/?probe=5738641fc9) | Apr 11, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [e6adfda5ec](https://linux-hardware.org/?probe=e6adfda5ec) | Apr 11, 2022 |
| Intel         | W7650                       | Notebook    | [7c970783e1](https://linux-hardware.org/?probe=7c970783e1) | Apr 11, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | Desktop     | [a751b63d6b](https://linux-hardware.org/?probe=a751b63d6b) | Apr 11, 2022 |
| Dell          | Latitude E5400              | Notebook    | [0ac76c891f](https://linux-hardware.org/?probe=0ac76c891f) | Apr 11, 2022 |
| Positivo      | POS-MI945AA                 | Desktop     | [581272b7c1](https://linux-hardware.org/?probe=581272b7c1) | Apr 11, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [266d7d3a62](https://linux-hardware.org/?probe=266d7d3a62) | Apr 11, 2022 |
| Itautec       | ST 4265                     | Desktop     | [b2facb728e](https://linux-hardware.org/?probe=b2facb728e) | Apr 10, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [5c2b30a7e1](https://linux-hardware.org/?probe=5c2b30a7e1) | Apr 10, 2022 |
| Pegatron      | IPMH61P1                    | Desktop     | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | Desktop     | [f394924315](https://linux-hardware.org/?probe=f394924315) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | Desktop     | [9edb3bbc43](https://linux-hardware.org/?probe=9edb3bbc43) | Apr 10, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [50f8111e57](https://linux-hardware.org/?probe=50f8111e57) | Apr 10, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [218db09adf](https://linux-hardware.org/?probe=218db09adf) | Apr 10, 2022 |
| ASRock        | G31M-S                      | Desktop     | [e02bbd85b4](https://linux-hardware.org/?probe=e02bbd85b4) | Apr 10, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [058f6a25dd](https://linux-hardware.org/?probe=058f6a25dd) | Apr 10, 2022 |
| LG Electro... | U460-G.BG51P1               | Notebook    | [33afe2c679](https://linux-hardware.org/?probe=33afe2c679) | Apr 10, 2022 |
| Unknown       | Amlogic Meson GXL (S905X... | Soc         | [65d6ffe591](https://linux-hardware.org/?probe=65d6ffe591) | Apr 09, 2022 |
| Unknown       | TIGD-CI4                    | Desktop     | [266aef8b2e](https://linux-hardware.org/?probe=266aef8b2e) | Apr 09, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [7b3a49ec3c](https://linux-hardware.org/?probe=7b3a49ec3c) | Apr 09, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [3ffa339c32](https://linux-hardware.org/?probe=3ffa339c32) | Apr 09, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [8a07adc0f8](https://linux-hardware.org/?probe=8a07adc0f8) | Apr 09, 2022 |
| Positivo      | N1250                       | Notebook    | [c64a47d6fc](https://linux-hardware.org/?probe=c64a47d6fc) | Apr 09, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [9dbe75c090](https://linux-hardware.org/?probe=9dbe75c090) | Apr 09, 2022 |
| HP            | G42                         | Notebook    | [32fad98d60](https://linux-hardware.org/?probe=32fad98d60) | Apr 09, 2022 |
| Positivo      | S14CT01                     | Notebook    | [a98fcbb9f2](https://linux-hardware.org/?probe=a98fcbb9f2) | Apr 08, 2022 |
| LG Electro... | S430-G.BC33P1               | Notebook    | [95f8d514d6](https://linux-hardware.org/?probe=95f8d514d6) | Apr 08, 2022 |
| Intel         | H81                         | Desktop     | [ffcfab5f12](https://linux-hardware.org/?probe=ffcfab5f12) | Apr 08, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [e26d163f72](https://linux-hardware.org/?probe=e26d163f72) | Apr 08, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [d9c54563b1](https://linux-hardware.org/?probe=d9c54563b1) | Apr 08, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [cdc96ed221](https://linux-hardware.org/?probe=cdc96ed221) | Apr 08, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | Notebook    | [ca8d7c1137](https://linux-hardware.org/?probe=ca8d7c1137) | Apr 08, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| Intel         | Unknown                     | Desktop     | [28f0edef8f](https://linux-hardware.org/?probe=28f0edef8f) | Apr 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [cd93e2fd82](https://linux-hardware.org/?probe=cd93e2fd82) | Apr 08, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | Desktop     | [fe36e7827a](https://linux-hardware.org/?probe=fe36e7827a) | Apr 08, 2022 |
| Positivo      | NB50TH                      | Notebook    | [8b6dbaa2a6](https://linux-hardware.org/?probe=8b6dbaa2a6) | Apr 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [b107483192](https://linux-hardware.org/?probe=b107483192) | Apr 07, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| HP            | ProBook 445 G7 Notebook ... | Notebook    | [0d15f8a702](https://linux-hardware.org/?probe=0d15f8a702) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [a78f13de9e](https://linux-hardware.org/?probe=a78f13de9e) | Apr 07, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [3c17fb0db4](https://linux-hardware.org/?probe=3c17fb0db4) | Apr 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [54bc7d6864](https://linux-hardware.org/?probe=54bc7d6864) | Apr 07, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [f29ab972e7](https://linux-hardware.org/?probe=f29ab972e7) | Apr 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [297454c537](https://linux-hardware.org/?probe=297454c537) | Apr 07, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [d98ca9a688](https://linux-hardware.org/?probe=d98ca9a688) | Apr 07, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [9a64c993f5](https://linux-hardware.org/?probe=9a64c993f5) | Apr 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [0f8f2d9229](https://linux-hardware.org/?probe=0f8f2d9229) | Apr 07, 2022 |
| Lenovo        | ThinkPad E490 20N9001MBR    | Notebook    | [1b041100a3](https://linux-hardware.org/?probe=1b041100a3) | Apr 07, 2022 |
| Positivo      | S14SL01                     | Notebook    | [092f7c7d2b](https://linux-hardware.org/?probe=092f7c7d2b) | Apr 07, 2022 |
| Intel         | X99                         | Desktop     | [4b1591958f](https://linux-hardware.org/?probe=4b1591958f) | Apr 06, 2022 |
| Acer          | Aspire XC-605               | Desktop     | [201896f70b](https://linux-hardware.org/?probe=201896f70b) | Apr 06, 2022 |
| Intel         | Shark Bay Client platfor... | Notebook    | [8b1a97afe3](https://linux-hardware.org/?probe=8b1a97afe3) | Apr 06, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Notebook    | [a6c37e7ee4](https://linux-hardware.org/?probe=a6c37e7ee4) | Apr 06, 2022 |
| Positivo      | Mobile                      | Notebook    | [024848f840](https://linux-hardware.org/?probe=024848f840) | Apr 06, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | Notebook    | [7ba2d85c09](https://linux-hardware.org/?probe=7ba2d85c09) | Apr 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [3719a80289](https://linux-hardware.org/?probe=3719a80289) | Apr 06, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [8c8679b57b](https://linux-hardware.org/?probe=8c8679b57b) | Apr 06, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [0887c85f98](https://linux-hardware.org/?probe=0887c85f98) | Apr 06, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [6caf8b778d](https://linux-hardware.org/?probe=6caf8b778d) | Apr 06, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [520cbf0afa](https://linux-hardware.org/?probe=520cbf0afa) | Apr 06, 2022 |
| ASRock        | FM2A78M-ITX+                | Desktop     | [63799d0adb](https://linux-hardware.org/?probe=63799d0adb) | Apr 06, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [d430c4bae4](https://linux-hardware.org/?probe=d430c4bae4) | Apr 06, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [652cd5fc07](https://linux-hardware.org/?probe=652cd5fc07) | Apr 06, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [1f6514f558](https://linux-hardware.org/?probe=1f6514f558) | Apr 06, 2022 |
| HP            | 3047h                       | Desktop     | [6766d428ef](https://linux-hardware.org/?probe=6766d428ef) | Apr 05, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [adf960d914](https://linux-hardware.org/?probe=adf960d914) | Apr 05, 2022 |
| ASUSTek       | 1015PE                      | Notebook    | [0643abbf5b](https://linux-hardware.org/?probe=0643abbf5b) | Apr 05, 2022 |
| Multilaser    | PC121                       | Notebook    | [f93e89718f](https://linux-hardware.org/?probe=f93e89718f) | Apr 05, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [a5e25a491a](https://linux-hardware.org/?probe=a5e25a491a) | Apr 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f31a359956](https://linux-hardware.org/?probe=f31a359956) | Apr 05, 2022 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [ac27863283](https://linux-hardware.org/?probe=ac27863283) | Apr 05, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [e007605c2c](https://linux-hardware.org/?probe=e007605c2c) | Apr 05, 2022 |
| ASUSTek       | GL502VT                     | Notebook    | [7f0692eb54](https://linux-hardware.org/?probe=7f0692eb54) | Apr 05, 2022 |
| Multilaser    | PC121                       | Notebook    | [31f2c02434](https://linux-hardware.org/?probe=31f2c02434) | Apr 05, 2022 |
| Intel         | H61                         | Desktop     | [d378493561](https://linux-hardware.org/?probe=d378493561) | Apr 05, 2022 |
| Dell          | 02YRK5 A03                  | Desktop     | [8f30fb0a3f](https://linux-hardware.org/?probe=8f30fb0a3f) | Apr 04, 2022 |
| Dell          | 02YRK5 A03                  | Desktop     | [4014bf184c](https://linux-hardware.org/?probe=4014bf184c) | Apr 04, 2022 |
| Philco        | 14H                         | Notebook    | [4408057803](https://linux-hardware.org/?probe=4408057803) | Apr 04, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [eb69a7978b](https://linux-hardware.org/?probe=eb69a7978b) | Apr 04, 2022 |
| Gigabyte      | H55M-S2HP                   | Desktop     | [5079856030](https://linux-hardware.org/?probe=5079856030) | Apr 04, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [126fa9fa52](https://linux-hardware.org/?probe=126fa9fa52) | Apr 04, 2022 |
| Dell          | Inspiron 5448               | Notebook    | [b8e5b302de](https://linux-hardware.org/?probe=b8e5b302de) | Apr 04, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [9ca082be16](https://linux-hardware.org/?probe=9ca082be16) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [4fdc33f1a2](https://linux-hardware.org/?probe=4fdc33f1a2) | Apr 04, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [d479e2ae4a](https://linux-hardware.org/?probe=d479e2ae4a) | Apr 04, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [08491e74ef](https://linux-hardware.org/?probe=08491e74ef) | Apr 04, 2022 |
| HP            | 1998                        | Desktop     | [d30791d695](https://linux-hardware.org/?probe=d30791d695) | Apr 04, 2022 |
| HP            | 1998                        | Desktop     | [74f1744dce](https://linux-hardware.org/?probe=74f1744dce) | Apr 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [93c2d9ec80](https://linux-hardware.org/?probe=93c2d9ec80) | Apr 03, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ecdd532a2c](https://linux-hardware.org/?probe=ecdd532a2c) | Apr 03, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [ab77f43b05](https://linux-hardware.org/?probe=ab77f43b05) | Apr 03, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [2f79554fe5](https://linux-hardware.org/?probe=2f79554fe5) | Apr 03, 2022 |
| HP            | Pavilion dm1                | Notebook    | [6b26166587](https://linux-hardware.org/?probe=6b26166587) | Apr 03, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [40077b3761](https://linux-hardware.org/?probe=40077b3761) | Apr 03, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [2911dea3f0](https://linux-hardware.org/?probe=2911dea3f0) | Apr 02, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [312811bfc3](https://linux-hardware.org/?probe=312811bfc3) | Apr 02, 2022 |
| Positivo      | S14CT01                     | Notebook    | [93170d0c1b](https://linux-hardware.org/?probe=93170d0c1b) | Apr 02, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [a4c9ba22ca](https://linux-hardware.org/?probe=a4c9ba22ca) | Apr 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [63408907f1](https://linux-hardware.org/?probe=63408907f1) | Apr 02, 2022 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [a8425c2df8](https://linux-hardware.org/?probe=a8425c2df8) | Apr 02, 2022 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [6655399773](https://linux-hardware.org/?probe=6655399773) | Apr 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [37394c9815](https://linux-hardware.org/?probe=37394c9815) | Apr 02, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [eedbf6a10e](https://linux-hardware.org/?probe=eedbf6a10e) | Apr 02, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [42038ab400](https://linux-hardware.org/?probe=42038ab400) | Apr 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [c85f37714f](https://linux-hardware.org/?probe=c85f37714f) | Apr 02, 2022 |
| Dell          | Inspiron 5481               | Convertible | [e364cee660](https://linux-hardware.org/?probe=e364cee660) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | Desktop     | [5d3d268c96](https://linux-hardware.org/?probe=5d3d268c96) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | Desktop     | [3dac9f017e](https://linux-hardware.org/?probe=3dac9f017e) | Apr 02, 2022 |
| Dell          | Inspiron 5481               | Convertible | [69c13d70e3](https://linux-hardware.org/?probe=69c13d70e3) | Apr 02, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [039209129c](https://linux-hardware.org/?probe=039209129c) | Apr 02, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [ba7a9c106a](https://linux-hardware.org/?probe=ba7a9c106a) | Apr 02, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [45b26abf42](https://linux-hardware.org/?probe=45b26abf42) | Apr 02, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [a8331ec187](https://linux-hardware.org/?probe=a8331ec187) | Apr 02, 2022 |
| Toshiba       | STI 010433                  | Desktop     | [daa5ae86bc](https://linux-hardware.org/?probe=daa5ae86bc) | Apr 01, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [c6f1665499](https://linux-hardware.org/?probe=c6f1665499) | Apr 01, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [53c0c6467d](https://linux-hardware.org/?probe=53c0c6467d) | Apr 01, 2022 |
| Itautec       | SM 3330 SM-3330 Padrao 0... | Desktop     | [47e5e82b88](https://linux-hardware.org/?probe=47e5e82b88) | Apr 01, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [9173259aed](https://linux-hardware.org/?probe=9173259aed) | Apr 01, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [ca7d796269](https://linux-hardware.org/?probe=ca7d796269) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [eba4514371](https://linux-hardware.org/?probe=eba4514371) | Apr 01, 2022 |
| HP            | G42                         | Notebook    | [4768d00265](https://linux-hardware.org/?probe=4768d00265) | Apr 01, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [47059c6626](https://linux-hardware.org/?probe=47059c6626) | Apr 01, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [b6da5f9629](https://linux-hardware.org/?probe=b6da5f9629) | Apr 01, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [b39bf0ec05](https://linux-hardware.org/?probe=b39bf0ec05) | Apr 01, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [6a7bc096c0](https://linux-hardware.org/?probe=6a7bc096c0) | Apr 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [0b849ce682](https://linux-hardware.org/?probe=0b849ce682) | Apr 01, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [c7cd058399](https://linux-hardware.org/?probe=c7cd058399) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [606eb17f56](https://linux-hardware.org/?probe=606eb17f56) | Apr 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [11731e6ece](https://linux-hardware.org/?probe=11731e6ece) | Apr 01, 2022 |
| Multilaser    | PC13X                       | Notebook    | [d62e1676c3](https://linux-hardware.org/?probe=d62e1676c3) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [6b0cd44dbb](https://linux-hardware.org/?probe=6b0cd44dbb) | Apr 01, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [9e095642f0](https://linux-hardware.org/?probe=9e095642f0) | Apr 01, 2022 |
| HP            | 1998                        | Desktop     | [23ca5d6703](https://linux-hardware.org/?probe=23ca5d6703) | Apr 01, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [21a9f5c811](https://linux-hardware.org/?probe=21a9f5c811) | Apr 01, 2022 |
| ASUSTek       | X102BA                      | Notebook    | [78ecf202d2](https://linux-hardware.org/?probe=78ecf202d2) | Apr 01, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [61a7788bfa](https://linux-hardware.org/?probe=61a7788bfa) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4dccfefe8a](https://linux-hardware.org/?probe=4dccfefe8a) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c226f684e8](https://linux-hardware.org/?probe=c226f684e8) | Mar 31, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [a4ad860e3d](https://linux-hardware.org/?probe=a4ad860e3d) | Mar 31, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [a8c1be0abd](https://linux-hardware.org/?probe=a8c1be0abd) | Mar 31, 2022 |
| Positivo      | POS-PIG41BO                 | Desktop     | [865f71148c](https://linux-hardware.org/?probe=865f71148c) | Mar 31, 2022 |
| Avell High... | B.ON                        | Notebook    | [d2628705e8](https://linux-hardware.org/?probe=d2628705e8) | Mar 31, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [2ce0540229](https://linux-hardware.org/?probe=2ce0540229) | Mar 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [2c37064716](https://linux-hardware.org/?probe=2c37064716) | Mar 31, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [f43d64639e](https://linux-hardware.org/?probe=f43d64639e) | Mar 31, 2022 |
| Multilaser    | PC13X                       | Notebook    | [e0e93fcf81](https://linux-hardware.org/?probe=e0e93fcf81) | Mar 30, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [c2daebfd60](https://linux-hardware.org/?probe=c2daebfd60) | Mar 30, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [d01eb61b5a](https://linux-hardware.org/?probe=d01eb61b5a) | Mar 30, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [47c1543863](https://linux-hardware.org/?probe=47c1543863) | Mar 30, 2022 |
| Pegatron      | SM 3322                     | Desktop     | [5f56bb615a](https://linux-hardware.org/?probe=5f56bb615a) | Mar 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [29096b57ad](https://linux-hardware.org/?probe=29096b57ad) | Mar 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f46afcf627](https://linux-hardware.org/?probe=f46afcf627) | Mar 30, 2022 |
| Samsung       | 530XBB                      | Notebook    | [cf7f06b3fe](https://linux-hardware.org/?probe=cf7f06b3fe) | Mar 30, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [b61b3e31e7](https://linux-hardware.org/?probe=b61b3e31e7) | Mar 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [323f2d9a1c](https://linux-hardware.org/?probe=323f2d9a1c) | Mar 30, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [af894bb443](https://linux-hardware.org/?probe=af894bb443) | Mar 30, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [9fde02b49a](https://linux-hardware.org/?probe=9fde02b49a) | Mar 30, 2022 |
| Philco        | 14I                         | Notebook    | [f49a55854c](https://linux-hardware.org/?probe=f49a55854c) | Mar 30, 2022 |
| Dell          | 0FR6WH A01                  | Desktop     | [3ebf09bc41](https://linux-hardware.org/?probe=3ebf09bc41) | Mar 30, 2022 |
| Avell High... | B.ON                        | Notebook    | [697fc1d4ec](https://linux-hardware.org/?probe=697fc1d4ec) | Mar 29, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [519c65be70](https://linux-hardware.org/?probe=519c65be70) | Mar 29, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [f21f3af1ca](https://linux-hardware.org/?probe=f21f3af1ca) | Mar 29, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [cc40a0b5fc](https://linux-hardware.org/?probe=cc40a0b5fc) | Mar 29, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [4601e5231f](https://linux-hardware.org/?probe=4601e5231f) | Mar 29, 2022 |
| Multilaser    | PC112                       | Convertible | [d272117426](https://linux-hardware.org/?probe=d272117426) | Mar 28, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [36681f4a2f](https://linux-hardware.org/?probe=36681f4a2f) | Mar 28, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [2c06de39ad](https://linux-hardware.org/?probe=2c06de39ad) | Mar 28, 2022 |
| HP            | Pavilion g4                 | Notebook    | [5f8c09baeb](https://linux-hardware.org/?probe=5f8c09baeb) | Mar 28, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [23eba220fc](https://linux-hardware.org/?probe=23eba220fc) | Mar 28, 2022 |
| Positivo      | Q464C                       | Notebook    | [16e296228a](https://linux-hardware.org/?probe=16e296228a) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [a50c8cdd0d](https://linux-hardware.org/?probe=a50c8cdd0d) | Mar 28, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [94a20fae0d](https://linux-hardware.org/?probe=94a20fae0d) | Mar 28, 2022 |
| Intel         | W7650                       | Notebook    | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [5f779f4af0](https://linux-hardware.org/?probe=5f779f4af0) | Mar 27, 2022 |
| Multilaser    | PC13X_DS                    | Notebook    | [7f7481d038](https://linux-hardware.org/?probe=7f7481d038) | Mar 27, 2022 |
| Acer          | V5-171                      | Notebook    | [e1a668bda2](https://linux-hardware.org/?probe=e1a668bda2) | Mar 27, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [1c9b405e1b](https://linux-hardware.org/?probe=1c9b405e1b) | Mar 27, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [44913af0e4](https://linux-hardware.org/?probe=44913af0e4) | Mar 27, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [94cfb244c9](https://linux-hardware.org/?probe=94cfb244c9) | Mar 27, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [b596ec9c95](https://linux-hardware.org/?probe=b596ec9c95) | Mar 27, 2022 |
| Toshiba       | Satellite A135              | Notebook    | [cf23c9bdb5](https://linux-hardware.org/?probe=cf23c9bdb5) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [f457ad3a65](https://linux-hardware.org/?probe=f457ad3a65) | Mar 27, 2022 |
| Dell          | Latitude 3410               | Notebook    | [503bb0a712](https://linux-hardware.org/?probe=503bb0a712) | Mar 27, 2022 |
| Dell          | Latitude 3410               | Notebook    | [5590356e12](https://linux-hardware.org/?probe=5590356e12) | Mar 27, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [b4864a1611](https://linux-hardware.org/?probe=b4864a1611) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [51c0f63296](https://linux-hardware.org/?probe=51c0f63296) | Mar 27, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [e269e3b44e](https://linux-hardware.org/?probe=e269e3b44e) | Mar 27, 2022 |
| Dell          | Latitude E6430              | Notebook    | [1e9495c4f6](https://linux-hardware.org/?probe=1e9495c4f6) | Mar 27, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [73be67de2c](https://linux-hardware.org/?probe=73be67de2c) | Mar 27, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [710ec26531](https://linux-hardware.org/?probe=710ec26531) | Mar 27, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [17724c0c21](https://linux-hardware.org/?probe=17724c0c21) | Mar 27, 2022 |
| Positivo      | Q232A                       | Notebook    | [fe29ba6b10](https://linux-hardware.org/?probe=fe29ba6b10) | Mar 27, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3839ca9677](https://linux-hardware.org/?probe=3839ca9677) | Mar 27, 2022 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [4d07e31cee](https://linux-hardware.org/?probe=4d07e31cee) | Mar 27, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [06ef38ab3e](https://linux-hardware.org/?probe=06ef38ab3e) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [d4655e802a](https://linux-hardware.org/?probe=d4655e802a) | Mar 26, 2022 |
| Multilaser    | PC112                       | Convertible | [2653b74103](https://linux-hardware.org/?probe=2653b74103) | Mar 26, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [081389ed06](https://linux-hardware.org/?probe=081389ed06) | Mar 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d23f0ea2dc](https://linux-hardware.org/?probe=d23f0ea2dc) | Mar 26, 2022 |
| ASUSTek       | P8H61-M LE/BR               | Desktop     | [732876bdd8](https://linux-hardware.org/?probe=732876bdd8) | Mar 26, 2022 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [c8acfed97a](https://linux-hardware.org/?probe=c8acfed97a) | Mar 26, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [5861c8e75a](https://linux-hardware.org/?probe=5861c8e75a) | Mar 26, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [b78f0137ba](https://linux-hardware.org/?probe=b78f0137ba) | Mar 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [a7d9a4a0de](https://linux-hardware.org/?probe=a7d9a4a0de) | Mar 26, 2022 |
| Positivo      | Q432A                       | Convertible | [754afa9c8c](https://linux-hardware.org/?probe=754afa9c8c) | Mar 25, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [ca93a32a4b](https://linux-hardware.org/?probe=ca93a32a4b) | Mar 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c4986f3f81](https://linux-hardware.org/?probe=c4986f3f81) | Mar 25, 2022 |
| Alienware     | m15 R6                      | Notebook    | [5505410995](https://linux-hardware.org/?probe=5505410995) | Mar 25, 2022 |
| Dell          | Vostro 7590                 | Notebook    | [1a15d49b97](https://linux-hardware.org/?probe=1a15d49b97) | Mar 25, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [d1e5c0bc9f](https://linux-hardware.org/?probe=d1e5c0bc9f) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [1ab1216e5b](https://linux-hardware.org/?probe=1ab1216e5b) | Mar 25, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [b47655a721](https://linux-hardware.org/?probe=b47655a721) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [29d034d804](https://linux-hardware.org/?probe=29d034d804) | Mar 25, 2022 |
| Sony          | VGN-FW180D                  | Notebook    | [9bbcb3d0ac](https://linux-hardware.org/?probe=9bbcb3d0ac) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [ca13a081ff](https://linux-hardware.org/?probe=ca13a081ff) | Mar 25, 2022 |
| Samsung       | 550XDA                      | Notebook    | [3b0cca4251](https://linux-hardware.org/?probe=3b0cca4251) | Mar 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f32a9d892c](https://linux-hardware.org/?probe=f32a9d892c) | Mar 25, 2022 |
| Login Info... | LOG-H110M-G3                | Desktop     | [30a691b952](https://linux-hardware.org/?probe=30a691b952) | Mar 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [7ebb094ad8](https://linux-hardware.org/?probe=7ebb094ad8) | Mar 25, 2022 |
| Avell High... | B.ON                        | Notebook    | [19b689aa12](https://linux-hardware.org/?probe=19b689aa12) | Mar 25, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [19cb24e20c](https://linux-hardware.org/?probe=19cb24e20c) | Mar 25, 2022 |
| Dell          | Latitude 7380               | Notebook    | [d3302e2138](https://linux-hardware.org/?probe=d3302e2138) | Mar 24, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [1017a921d7](https://linux-hardware.org/?probe=1017a921d7) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [e22336384e](https://linux-hardware.org/?probe=e22336384e) | Mar 24, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [7c506671a1](https://linux-hardware.org/?probe=7c506671a1) | Mar 24, 2022 |
| HP            | ProBook 6465b               | Notebook    | [2e1792442b](https://linux-hardware.org/?probe=2e1792442b) | Mar 24, 2022 |
| HP            | ProBook 6465b               | Notebook    | [51a296abf8](https://linux-hardware.org/?probe=51a296abf8) | Mar 24, 2022 |
| Lenovo        | V15 G2 ITL 82ME             | Notebook    | [f89824dbc7](https://linux-hardware.org/?probe=f89824dbc7) | Mar 24, 2022 |
| Positivo      | Q432A                       | Convertible | [afbf6af7f9](https://linux-hardware.org/?probe=afbf6af7f9) | Mar 24, 2022 |
| Positivo      | Q432A                       | Convertible | [883395b0e7](https://linux-hardware.org/?probe=883395b0e7) | Mar 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [b5fff905c8](https://linux-hardware.org/?probe=b5fff905c8) | Mar 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9612c1e4bd](https://linux-hardware.org/?probe=9612c1e4bd) | Mar 24, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [930cc740b2](https://linux-hardware.org/?probe=930cc740b2) | Mar 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [08c4b3b7a5](https://linux-hardware.org/?probe=08c4b3b7a5) | Mar 24, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [bc18447c4b](https://linux-hardware.org/?probe=bc18447c4b) | Mar 24, 2022 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [17a0a5394e](https://linux-hardware.org/?probe=17a0a5394e) | Mar 24, 2022 |
| HP            | Pavilion g4                 | Notebook    | [bbb464378e](https://linux-hardware.org/?probe=bbb464378e) | Mar 23, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ef1af7bbae](https://linux-hardware.org/?probe=ef1af7bbae) | Mar 23, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [af80d44a27](https://linux-hardware.org/?probe=af80d44a27) | Mar 23, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [687fcb0605](https://linux-hardware.org/?probe=687fcb0605) | Mar 23, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [31b072eae1](https://linux-hardware.org/?probe=31b072eae1) | Mar 23, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [82934a5fbf](https://linux-hardware.org/?probe=82934a5fbf) | Mar 23, 2022 |
| Positivo      | H14BT58                     | Notebook    | [3380c2e20d](https://linux-hardware.org/?probe=3380c2e20d) | Mar 23, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [4e75dbe2d2](https://linux-hardware.org/?probe=4e75dbe2d2) | Mar 23, 2022 |
| Dell          | 0D883F A06                  | Desktop     | [7966cb4145](https://linux-hardware.org/?probe=7966cb4145) | Mar 23, 2022 |
| MSI           | 2A9C                        | Desktop     | [5789a9614f](https://linux-hardware.org/?probe=5789a9614f) | Mar 23, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [ef32f1be04](https://linux-hardware.org/?probe=ef32f1be04) | Mar 23, 2022 |
| Positivo      | C14CU51                     | Notebook    | [1ca3c10e9b](https://linux-hardware.org/?probe=1ca3c10e9b) | Mar 23, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [1bce4dc771](https://linux-hardware.org/?probe=1bce4dc771) | Mar 22, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [4d97559516](https://linux-hardware.org/?probe=4d97559516) | Mar 22, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [d2733b3c95](https://linux-hardware.org/?probe=d2733b3c95) | Mar 22, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [edaf75da5f](https://linux-hardware.org/?probe=edaf75da5f) | Mar 22, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [e3d131ff9a](https://linux-hardware.org/?probe=e3d131ff9a) | Mar 22, 2022 |
| Avell High... | B.ON                        | Notebook    | [28dd4cfea0](https://linux-hardware.org/?probe=28dd4cfea0) | Mar 22, 2022 |
| Digiboard     | MPxx                        | Desktop     | [b3bb9ff288](https://linux-hardware.org/?probe=b3bb9ff288) | Mar 22, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7561e02794](https://linux-hardware.org/?probe=7561e02794) | Mar 22, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [b4511f91a2](https://linux-hardware.org/?probe=b4511f91a2) | Mar 22, 2022 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [94393a4d0a](https://linux-hardware.org/?probe=94393a4d0a) | Mar 22, 2022 |
| Dell          | Latitude 3410               | Notebook    | [d81534df3a](https://linux-hardware.org/?probe=d81534df3a) | Mar 22, 2022 |
| Sony          | VPCEH10EB                   | Notebook    | [921d432c3c](https://linux-hardware.org/?probe=921d432c3c) | Mar 22, 2022 |
| Dell          | Inspiron 5437               | Notebook    | [3b5a987609](https://linux-hardware.org/?probe=3b5a987609) | Mar 22, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [de3d4db2c5](https://linux-hardware.org/?probe=de3d4db2c5) | Mar 22, 2022 |
| LG Electro... | R480-L.B211P1               | Notebook    | [0ab46e5aba](https://linux-hardware.org/?probe=0ab46e5aba) | Mar 22, 2022 |
| Dell          | Inspiron 5423               | Notebook    | [ea335b5e3b](https://linux-hardware.org/?probe=ea335b5e3b) | Mar 21, 2022 |
| ASUSTek       | K40IJ                       | Notebook    | [dbc0e61f47](https://linux-hardware.org/?probe=dbc0e61f47) | Mar 21, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [6b216c3e7c](https://linux-hardware.org/?probe=6b216c3e7c) | Mar 21, 2022 |
| Dell          | Latitude 3410               | Notebook    | [6d78749bd6](https://linux-hardware.org/?probe=6d78749bd6) | Mar 21, 2022 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [fcf20188d2](https://linux-hardware.org/?probe=fcf20188d2) | Mar 21, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [0626cf6142](https://linux-hardware.org/?probe=0626cf6142) | Mar 21, 2022 |
| Positivo      | POS-EIH61CR POSITIVO        | Desktop     | [b789768b64](https://linux-hardware.org/?probe=b789768b64) | Mar 21, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [b2fd45aebb](https://linux-hardware.org/?probe=b2fd45aebb) | Mar 21, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [c004cff4ed](https://linux-hardware.org/?probe=c004cff4ed) | Mar 21, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [aaf1f9eb09](https://linux-hardware.org/?probe=aaf1f9eb09) | Mar 20, 2022 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [26c6fa4da4](https://linux-hardware.org/?probe=26c6fa4da4) | Mar 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [50348e45ec](https://linux-hardware.org/?probe=50348e45ec) | Mar 20, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [b5abf934a3](https://linux-hardware.org/?probe=b5abf934a3) | Mar 20, 2022 |
| MSI           | B250M PRO-VH                | Desktop     | [d3885311bc](https://linux-hardware.org/?probe=d3885311bc) | Mar 20, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [ef43a1dac3](https://linux-hardware.org/?probe=ef43a1dac3) | Mar 20, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [3617d07720](https://linux-hardware.org/?probe=3617d07720) | Mar 20, 2022 |
| Biostar       | B460GTQ                     | Desktop     | [7c912f57c6](https://linux-hardware.org/?probe=7c912f57c6) | Mar 20, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [519b33398d](https://linux-hardware.org/?probe=519b33398d) | Mar 20, 2022 |
| Dell          | Inspiron 5481               | Convertible | [7292765d92](https://linux-hardware.org/?probe=7292765d92) | Mar 20, 2022 |
| Samsung       | 550XDA                      | Notebook    | [a5d8eebb8c](https://linux-hardware.org/?probe=a5d8eebb8c) | Mar 20, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [f3e67de15e](https://linux-hardware.org/?probe=f3e67de15e) | Mar 20, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [78676e017b](https://linux-hardware.org/?probe=78676e017b) | Mar 19, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [ada99ba65e](https://linux-hardware.org/?probe=ada99ba65e) | Mar 19, 2022 |
| Compal        | NCL60/61                    | Notebook    | [39c9e97e85](https://linux-hardware.org/?probe=39c9e97e85) | Mar 19, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [9719c4cdeb](https://linux-hardware.org/?probe=9719c4cdeb) | Mar 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [be18e33911](https://linux-hardware.org/?probe=be18e33911) | Mar 19, 2022 |
| Dell          | 0VRWRC A01                  | Desktop     | [48a73bd70f](https://linux-hardware.org/?probe=48a73bd70f) | Mar 19, 2022 |
| Dell          | 0VRWRC A01                  | Desktop     | [bcced0a8f2](https://linux-hardware.org/?probe=bcced0a8f2) | Mar 19, 2022 |
| ECS           | A990FXM-A                   | Desktop     | [32deb5b6a1](https://linux-hardware.org/?probe=32deb5b6a1) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | Notebook    | [8366f92538](https://linux-hardware.org/?probe=8366f92538) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | Notebook    | [8f96005683](https://linux-hardware.org/?probe=8f96005683) | Mar 19, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [4d11bb964b](https://linux-hardware.org/?probe=4d11bb964b) | Mar 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [3693169add](https://linux-hardware.org/?probe=3693169add) | Mar 19, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [7970a8e8d2](https://linux-hardware.org/?probe=7970a8e8d2) | Mar 19, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [6c60e6d6af](https://linux-hardware.org/?probe=6c60e6d6af) | Mar 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [e7534ca823](https://linux-hardware.org/?probe=e7534ca823) | Mar 19, 2022 |
| Positivo      | Mobile                      | Notebook    | [a1eb18d712](https://linux-hardware.org/?probe=a1eb18d712) | Mar 18, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [7ab3aba611](https://linux-hardware.org/?probe=7ab3aba611) | Mar 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [3f17145276](https://linux-hardware.org/?probe=3f17145276) | Mar 18, 2022 |
| Philco        | 14I                         | Notebook    | [ceefb7fc2f](https://linux-hardware.org/?probe=ceefb7fc2f) | Mar 18, 2022 |
| Itautec       | Infoway w7535               | Notebook    | [e963149321](https://linux-hardware.org/?probe=e963149321) | Mar 18, 2022 |
| Biostar       | N68S3B                      | Desktop     | [736799fe08](https://linux-hardware.org/?probe=736799fe08) | Mar 18, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7cafe0766c](https://linux-hardware.org/?probe=7cafe0766c) | Mar 18, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [6f4835e78d](https://linux-hardware.org/?probe=6f4835e78d) | Mar 18, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [9dc0d76053](https://linux-hardware.org/?probe=9dc0d76053) | Mar 17, 2022 |
| MSI           | J1900I                      | Desktop     | [991f20b3b8](https://linux-hardware.org/?probe=991f20b3b8) | Mar 17, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [a56fb721dd](https://linux-hardware.org/?probe=a56fb721dd) | Mar 17, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [c41639222f](https://linux-hardware.org/?probe=c41639222f) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [47a984d336](https://linux-hardware.org/?probe=47a984d336) | Mar 17, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [24b9866304](https://linux-hardware.org/?probe=24b9866304) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | Notebook    | [75909ee2fc](https://linux-hardware.org/?probe=75909ee2fc) | Mar 17, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [be2d436df6](https://linux-hardware.org/?probe=be2d436df6) | Mar 17, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [9ebb2a429f](https://linux-hardware.org/?probe=9ebb2a429f) | Mar 17, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cb5c244ae1](https://linux-hardware.org/?probe=cb5c244ae1) | Mar 17, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [15a04898a4](https://linux-hardware.org/?probe=15a04898a4) | Mar 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aaee68ff4](https://linux-hardware.org/?probe=1aaee68ff4) | Mar 16, 2022 |
| HP            | 83E2                        | Desktop     | [d39e85ed10](https://linux-hardware.org/?probe=d39e85ed10) | Mar 16, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [05d071af74](https://linux-hardware.org/?probe=05d071af74) | Mar 16, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [83d37bb724](https://linux-hardware.org/?probe=83d37bb724) | Mar 16, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [bd035566a4](https://linux-hardware.org/?probe=bd035566a4) | Mar 16, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [e5d7cda06b](https://linux-hardware.org/?probe=e5d7cda06b) | Mar 16, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [3e1b96fe9f](https://linux-hardware.org/?probe=3e1b96fe9f) | Mar 16, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [09340e0b12](https://linux-hardware.org/?probe=09340e0b12) | Mar 16, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [be15e65580](https://linux-hardware.org/?probe=be15e65580) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [62038e09e8](https://linux-hardware.org/?probe=62038e09e8) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [cbebb0b476](https://linux-hardware.org/?probe=cbebb0b476) | Mar 15, 2022 |
| Intel         | powered classmate PC        | Notebook    | [6938945c70](https://linux-hardware.org/?probe=6938945c70) | Mar 15, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [220c4f69b0](https://linux-hardware.org/?probe=220c4f69b0) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| Positivo      | POS-PIH77CM POSITIVO        | Desktop     | [8420ad7ef2](https://linux-hardware.org/?probe=8420ad7ef2) | Mar 14, 2022 |
| Lenovo        | ThinkPad R61 7733B46        | Notebook    | [d2220c6c2e](https://linux-hardware.org/?probe=d2220c6c2e) | Mar 14, 2022 |
| Dell          | G3 3500                     | Notebook    | [7c50a4be17](https://linux-hardware.org/?probe=7c50a4be17) | Mar 14, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [ebeea29eda](https://linux-hardware.org/?probe=ebeea29eda) | Mar 14, 2022 |
| Dell          | 08YDFF A01                  | Desktop     | [322d01a111](https://linux-hardware.org/?probe=322d01a111) | Mar 14, 2022 |
| HP            | ProBook 6465b               | Notebook    | [95ecc6cdbd](https://linux-hardware.org/?probe=95ecc6cdbd) | Mar 14, 2022 |
| Dell          | G3 3500                     | Notebook    | [65879fdfa3](https://linux-hardware.org/?probe=65879fdfa3) | Mar 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [2e828331f3](https://linux-hardware.org/?probe=2e828331f3) | Mar 14, 2022 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [38f9d1058f](https://linux-hardware.org/?probe=38f9d1058f) | Mar 14, 2022 |
| Positivo      | C14RV01                     | Notebook    | [c3bea5a62d](https://linux-hardware.org/?probe=c3bea5a62d) | Mar 14, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [9636a8d68a](https://linux-hardware.org/?probe=9636a8d68a) | Mar 14, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7b964bbd1f](https://linux-hardware.org/?probe=7b964bbd1f) | Mar 14, 2022 |
| Positivo      | Q232A                       | Notebook    | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| Positivo      | N1250                       | Notebook    | [e0ac8b69f1](https://linux-hardware.org/?probe=e0ac8b69f1) | Mar 13, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [824c5eb97d](https://linux-hardware.org/?probe=824c5eb97d) | Mar 13, 2022 |
| Intel         | DH61WW AAG23116-303         | Desktop     | [8cc21d5508](https://linux-hardware.org/?probe=8cc21d5508) | Mar 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [6b62eaea48](https://linux-hardware.org/?probe=6b62eaea48) | Mar 13, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [e86cb3194d](https://linux-hardware.org/?probe=e86cb3194d) | Mar 13, 2022 |
| Visum         | A6VMX 0A                    | Desktop     | [82a79d1b3c](https://linux-hardware.org/?probe=82a79d1b3c) | Mar 13, 2022 |
| HP            | Pavilion g4                 | Notebook    | [97be773922](https://linux-hardware.org/?probe=97be773922) | Mar 12, 2022 |
| HP            | Pavilion g4                 | Notebook    | [4ec085dcd5](https://linux-hardware.org/?probe=4ec085dcd5) | Mar 12, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [9391de1a74](https://linux-hardware.org/?probe=9391de1a74) | Mar 12, 2022 |
| Positivo      | S14CT01                     | Notebook    | [198fc329a3](https://linux-hardware.org/?probe=198fc329a3) | Mar 12, 2022 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [f8ef0e1c18](https://linux-hardware.org/?probe=f8ef0e1c18) | Mar 12, 2022 |
| Avell High... | B.ON                        | Notebook    | [3632f15fda](https://linux-hardware.org/?probe=3632f15fda) | Mar 12, 2022 |
| Dell          | Inspiron N4030              | Notebook    | [7828723d3d](https://linux-hardware.org/?probe=7828723d3d) | Mar 12, 2022 |
| Dell          | Inspiron N4030              | Notebook    | [22c9e04b22](https://linux-hardware.org/?probe=22c9e04b22) | Mar 12, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [30f82f9c0a](https://linux-hardware.org/?probe=30f82f9c0a) | Mar 12, 2022 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [ebf747ad50](https://linux-hardware.org/?probe=ebf747ad50) | Mar 12, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [40de48af24](https://linux-hardware.org/?probe=40de48af24) | Mar 12, 2022 |
| Philco        | 10D                         | Notebook    | [c983be3bb0](https://linux-hardware.org/?probe=c983be3bb0) | Mar 11, 2022 |
| Lenovo        | 3130 SDK0J40700 WIN 3258... | Mini pc     | [8df8132490](https://linux-hardware.org/?probe=8df8132490) | Mar 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [a6ec683476](https://linux-hardware.org/?probe=a6ec683476) | Mar 11, 2022 |
| HP            | 1000                        | Notebook    | [c43fd3bfa5](https://linux-hardware.org/?probe=c43fd3bfa5) | Mar 11, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [e5242e79bd](https://linux-hardware.org/?probe=e5242e79bd) | Mar 11, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [734698831b](https://linux-hardware.org/?probe=734698831b) | Mar 11, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [a3f9e83752](https://linux-hardware.org/?probe=a3f9e83752) | Mar 11, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [036df95c28](https://linux-hardware.org/?probe=036df95c28) | Mar 11, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [8248b17f01](https://linux-hardware.org/?probe=8248b17f01) | Mar 11, 2022 |
| ASUSTek       | X451CAP                     | Notebook    | [9a92c2571b](https://linux-hardware.org/?probe=9a92c2571b) | Mar 11, 2022 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [f3a97cad04](https://linux-hardware.org/?probe=f3a97cad04) | Mar 11, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [22452f39c2](https://linux-hardware.org/?probe=22452f39c2) | Mar 11, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [9de4c6210f](https://linux-hardware.org/?probe=9de4c6210f) | Mar 11, 2022 |
| Intel         | H61                         | Desktop     | [8ce8958b88](https://linux-hardware.org/?probe=8ce8958b88) | Mar 10, 2022 |
| Megaware      | MW-H61M-2H                  | Desktop     | [ceb5a251e7](https://linux-hardware.org/?probe=ceb5a251e7) | Mar 10, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [cca64bfd46](https://linux-hardware.org/?probe=cca64bfd46) | Mar 10, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ef2e2e6872](https://linux-hardware.org/?probe=ef2e2e6872) | Mar 10, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [2e4bdb96fa](https://linux-hardware.org/?probe=2e4bdb96fa) | Mar 10, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [d20ef03d37](https://linux-hardware.org/?probe=d20ef03d37) | Mar 10, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [674a4fbede](https://linux-hardware.org/?probe=674a4fbede) | Mar 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7b7cf41624](https://linux-hardware.org/?probe=7b7cf41624) | Mar 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [418dc14fe7](https://linux-hardware.org/?probe=418dc14fe7) | Mar 10, 2022 |
| Intel         | H61                         | Desktop     | [cb91470ea7](https://linux-hardware.org/?probe=cb91470ea7) | Mar 10, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [282f0e1f65](https://linux-hardware.org/?probe=282f0e1f65) | Mar 10, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [dbc222289c](https://linux-hardware.org/?probe=dbc222289c) | Mar 10, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [7280c9c630](https://linux-hardware.org/?probe=7280c9c630) | Mar 10, 2022 |
| ONDA          | A68V+                       | Desktop     | [2c4c04ae22](https://linux-hardware.org/?probe=2c4c04ae22) | Mar 10, 2022 |
| Positivo      | S14CT01                     | Notebook    | [89ff3431e1](https://linux-hardware.org/?probe=89ff3431e1) | Mar 09, 2022 |
| Sony          | VJF153                      | Notebook    | [5aa5f532b7](https://linux-hardware.org/?probe=5aa5f532b7) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [490da26167](https://linux-hardware.org/?probe=490da26167) | Mar 09, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [84bc5f3382](https://linux-hardware.org/?probe=84bc5f3382) | Mar 09, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [849f4141ce](https://linux-hardware.org/?probe=849f4141ce) | Mar 09, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [49503537f5](https://linux-hardware.org/?probe=49503537f5) | Mar 09, 2022 |
| Positivo      | CHT12CP                     | Notebook    | [fa7f40245b](https://linux-hardware.org/?probe=fa7f40245b) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [17f7f8858f](https://linux-hardware.org/?probe=17f7f8858f) | Mar 09, 2022 |
| Dell          | Latitude 5420               | Notebook    | [81bcf5ce9c](https://linux-hardware.org/?probe=81bcf5ce9c) | Mar 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a5c7569f3c](https://linux-hardware.org/?probe=a5c7569f3c) | Mar 09, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [78d900b185](https://linux-hardware.org/?probe=78d900b185) | Mar 09, 2022 |
| Acer          | Predator G3-572             | Notebook    | [56f568ccef](https://linux-hardware.org/?probe=56f568ccef) | Mar 08, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [e1e3698dbc](https://linux-hardware.org/?probe=e1e3698dbc) | Mar 08, 2022 |
| Samsung       | 550XDA                      | Notebook    | [cca05024ce](https://linux-hardware.org/?probe=cca05024ce) | Mar 08, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [c7025ac75e](https://linux-hardware.org/?probe=c7025ac75e) | Mar 08, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [25951f4351](https://linux-hardware.org/?probe=25951f4351) | Mar 08, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [16f5e2d856](https://linux-hardware.org/?probe=16f5e2d856) | Mar 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f118a17b6e](https://linux-hardware.org/?probe=f118a17b6e) | Mar 08, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [1e28e34bca](https://linux-hardware.org/?probe=1e28e34bca) | Mar 08, 2022 |
| System76      | Lemur Pro                   | Notebook    | [69ce23b9f3](https://linux-hardware.org/?probe=69ce23b9f3) | Mar 07, 2022 |
| ASUSTek       | M2N-SLI                     | Desktop     | [675f15b6db](https://linux-hardware.org/?probe=675f15b6db) | Mar 07, 2022 |
| Acer          | Predator G3-572             | Notebook    | [156e7734be](https://linux-hardware.org/?probe=156e7734be) | Mar 07, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [88c5f71c1d](https://linux-hardware.org/?probe=88c5f71c1d) | Mar 07, 2022 |
| Intel         | H61                         | Desktop     | [5198074ef6](https://linux-hardware.org/?probe=5198074ef6) | Mar 07, 2022 |
| Sony          | SVE15111EBS                 | Notebook    | [5e2a00d875](https://linux-hardware.org/?probe=5e2a00d875) | Mar 07, 2022 |
| HP            | G42                         | Notebook    | [a6ea4c70b4](https://linux-hardware.org/?probe=a6ea4c70b4) | Mar 07, 2022 |
| Samsung       | 767XCL                      | Notebook    | [7685cdcfb9](https://linux-hardware.org/?probe=7685cdcfb9) | Mar 07, 2022 |
| HP            | G42                         | Notebook    | [77c16390cc](https://linux-hardware.org/?probe=77c16390cc) | Mar 07, 2022 |
| Sony          | SVE15111EBS                 | Notebook    | [49294d3345](https://linux-hardware.org/?probe=49294d3345) | Mar 06, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [852b569ef5](https://linux-hardware.org/?probe=852b569ef5) | Mar 06, 2022 |
| Avell High... | 1513                        | Notebook    | [c2a1be9b32](https://linux-hardware.org/?probe=c2a1be9b32) | Mar 06, 2022 |
| Sony          | SVE15111EBS                 | Notebook    | [f6c420fad1](https://linux-hardware.org/?probe=f6c420fad1) | Mar 06, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [2bf4890b1b](https://linux-hardware.org/?probe=2bf4890b1b) | Mar 06, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [45abb29457](https://linux-hardware.org/?probe=45abb29457) | Mar 06, 2022 |
| Sony          | SVE15111EBS                 | Notebook    | [2a9bee0a38](https://linux-hardware.org/?probe=2a9bee0a38) | Mar 06, 2022 |
| Acer          | Aspire 4745Z                | Notebook    | [a3021ea674](https://linux-hardware.org/?probe=a3021ea674) | Mar 06, 2022 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [060ea89f97](https://linux-hardware.org/?probe=060ea89f97) | Mar 06, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [632b62bd7c](https://linux-hardware.org/?probe=632b62bd7c) | Mar 06, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [d7c3e61995](https://linux-hardware.org/?probe=d7c3e61995) | Mar 06, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [d419223147](https://linux-hardware.org/?probe=d419223147) | Mar 06, 2022 |
| Positivo      | C14RV01                     | Notebook    | [2ac19f368f](https://linux-hardware.org/?probe=2ac19f368f) | Mar 06, 2022 |
| Dell          | Inspiron 5437               | Notebook    | [6b892c83ff](https://linux-hardware.org/?probe=6b892c83ff) | Mar 06, 2022 |
| Samsung       | 767XCL                      | Notebook    | [e01c76fd80](https://linux-hardware.org/?probe=e01c76fd80) | Mar 06, 2022 |
| Samsung       | 767XCL                      | Notebook    | [a45c6cfda9](https://linux-hardware.org/?probe=a45c6cfda9) | Mar 05, 2022 |
| Acer          | Aspire 5733                 | Notebook    | [79a1d21f1e](https://linux-hardware.org/?probe=79a1d21f1e) | Mar 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [54a840498f](https://linux-hardware.org/?probe=54a840498f) | Mar 05, 2022 |
| Positivo B... | VJC141F11X-B0111L           | Notebook    | [5699a5d3e2](https://linux-hardware.org/?probe=5699a5d3e2) | Mar 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [14fc889e5f](https://linux-hardware.org/?probe=14fc889e5f) | Mar 05, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [97eedd34f4](https://linux-hardware.org/?probe=97eedd34f4) | Mar 05, 2022 |
| Dell          | Inspiron N4030              | Notebook    | [ac4c492fcf](https://linux-hardware.org/?probe=ac4c492fcf) | Mar 05, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [7fd2e4885c](https://linux-hardware.org/?probe=7fd2e4885c) | Mar 05, 2022 |
| Dell          | Inspiron N4030              | Notebook    | [e5e17e5138](https://linux-hardware.org/?probe=e5e17e5138) | Mar 05, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [a578472a20](https://linux-hardware.org/?probe=a578472a20) | Mar 05, 2022 |
| Avell High... | A40 LIV                     | Notebook    | [6056996dfb](https://linux-hardware.org/?probe=6056996dfb) | Mar 05, 2022 |
| Positivo      | Q232A                       | Notebook    | [0244ef1064](https://linux-hardware.org/?probe=0244ef1064) | Mar 05, 2022 |
| Positivo      | Q232A                       | Notebook    | [1f2ae579f6](https://linux-hardware.org/?probe=1f2ae579f6) | Mar 05, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [5119ee3a39](https://linux-hardware.org/?probe=5119ee3a39) | Mar 05, 2022 |
| Samsung       | 767XCL                      | Notebook    | [fddef2f8df](https://linux-hardware.org/?probe=fddef2f8df) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Intel         | DG31PR AAE58249-302         | Desktop     | [fb8b615012](https://linux-hardware.org/?probe=fb8b615012) | Mar 04, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [be345eb07f](https://linux-hardware.org/?probe=be345eb07f) | Mar 04, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [779a3314fd](https://linux-hardware.org/?probe=779a3314fd) | Mar 04, 2022 |
| Positivo B... | VJFE52F11X-XXXXXX           | Notebook    | [d40ec33f5e](https://linux-hardware.org/?probe=d40ec33f5e) | Mar 04, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [ac36138ae4](https://linux-hardware.org/?probe=ac36138ae4) | Mar 04, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [7557a0afed](https://linux-hardware.org/?probe=7557a0afed) | Mar 03, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [5597750b89](https://linux-hardware.org/?probe=5597750b89) | Mar 03, 2022 |
| Acer          | V5-171                      | Notebook    | [8c620eae72](https://linux-hardware.org/?probe=8c620eae72) | Mar 03, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [77e4345afe](https://linux-hardware.org/?probe=77e4345afe) | Mar 03, 2022 |
| KLLISRE       | B75 V1.1                    | Desktop     | [f29cfed3d4](https://linux-hardware.org/?probe=f29cfed3d4) | Mar 03, 2022 |
| Intel         | H61                         | Desktop     | [86f2038ab2](https://linux-hardware.org/?probe=86f2038ab2) | Mar 03, 2022 |
| Sony          | VPCCW2UFX                   | Notebook    | [47587383d1](https://linux-hardware.org/?probe=47587383d1) | Mar 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [72a9d60f1b](https://linux-hardware.org/?probe=72a9d60f1b) | Mar 03, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [09b1cd7548](https://linux-hardware.org/?probe=09b1cd7548) | Mar 03, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [f87b97e105](https://linux-hardware.org/?probe=f87b97e105) | Mar 03, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [0875be36f0](https://linux-hardware.org/?probe=0875be36f0) | Mar 03, 2022 |
| Intel         | DG31PR AAE58249-302         | Desktop     | [71344b6640](https://linux-hardware.org/?probe=71344b6640) | Mar 03, 2022 |
| OEM           | I42IL1                      | Notebook    | [0920ee7ed1](https://linux-hardware.org/?probe=0920ee7ed1) | Mar 03, 2022 |
| MSI           | MS-7255 V2.0                | Desktop     | [5874b1887d](https://linux-hardware.org/?probe=5874b1887d) | Mar 03, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [1da1f4ab04](https://linux-hardware.org/?probe=1da1f4ab04) | Mar 03, 2022 |
| ECS           | A785GM-AD3                  | Desktop     | [43c3e7c4a0](https://linux-hardware.org/?probe=43c3e7c4a0) | Mar 02, 2022 |
| Positivo      | POS-RIQ370ED                | Desktop     | [0fa80fe8c0](https://linux-hardware.org/?probe=0fa80fe8c0) | Mar 02, 2022 |
| Positivo      | H14BT58                     | Notebook    | [5bcf783e8d](https://linux-hardware.org/?probe=5bcf783e8d) | Mar 02, 2022 |
| Positivo      | S14SL01                     | Notebook    | [7cea537f9c](https://linux-hardware.org/?probe=7cea537f9c) | Mar 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [35507d8b67](https://linux-hardware.org/?probe=35507d8b67) | Mar 02, 2022 |
| Positivo      | S14SL01                     | Notebook    | [066bae4a89](https://linux-hardware.org/?probe=066bae4a89) | Mar 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [9444d52862](https://linux-hardware.org/?probe=9444d52862) | Mar 02, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [476396ef7c](https://linux-hardware.org/?probe=476396ef7c) | Mar 02, 2022 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [7fb5d56fdd](https://linux-hardware.org/?probe=7fb5d56fdd) | Mar 02, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [fd7ddf8a96](https://linux-hardware.org/?probe=fd7ddf8a96) | Mar 01, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [8c1bcab1d9](https://linux-hardware.org/?probe=8c1bcab1d9) | Mar 01, 2022 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [0a32bd76ae](https://linux-hardware.org/?probe=0a32bd76ae) | Mar 01, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [6a159a891a](https://linux-hardware.org/?probe=6a159a891a) | Mar 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ecd28158cc](https://linux-hardware.org/?probe=ecd28158cc) | Mar 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2d76cb0d68](https://linux-hardware.org/?probe=2d76cb0d68) | Mar 01, 2022 |
| Samsung       | 370E4K                      | Notebook    | [2aaabbb5c7](https://linux-hardware.org/?probe=2aaabbb5c7) | Mar 01, 2022 |
| Philco        | O E M                       | Notebook    | [47cc99022d](https://linux-hardware.org/?probe=47cc99022d) | Mar 01, 2022 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | Desktop     | [4448b7c526](https://linux-hardware.org/?probe=4448b7c526) | Mar 01, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [f38fb6bf3f](https://linux-hardware.org/?probe=f38fb6bf3f) | Feb 28, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [38a96041fa](https://linux-hardware.org/?probe=38a96041fa) | Feb 28, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [c43798eb21](https://linux-hardware.org/?probe=c43798eb21) | Feb 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [f0c13794e9](https://linux-hardware.org/?probe=f0c13794e9) | Feb 28, 2022 |
| Toshiba       | Satellite S55-C             | Notebook    | [e194d9993d](https://linux-hardware.org/?probe=e194d9993d) | Feb 28, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [122a25202d](https://linux-hardware.org/?probe=122a25202d) | Feb 28, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [846c33b65f](https://linux-hardware.org/?probe=846c33b65f) | Feb 28, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [21165232d6](https://linux-hardware.org/?probe=21165232d6) | Feb 28, 2022 |
| Intel         | H55                         | Desktop     | [2f52a73f85](https://linux-hardware.org/?probe=2f52a73f85) | Feb 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [cc638e722f](https://linux-hardware.org/?probe=cc638e722f) | Feb 27, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [fb656318f6](https://linux-hardware.org/?probe=fb656318f6) | Feb 27, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [7cc9909959](https://linux-hardware.org/?probe=7cc9909959) | Feb 27, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [6d4bc4aec1](https://linux-hardware.org/?probe=6d4bc4aec1) | Feb 27, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [c607041591](https://linux-hardware.org/?probe=c607041591) | Feb 27, 2022 |
| Positivo      | C14CU41TV                   | Notebook    | [7cabe0e07c](https://linux-hardware.org/?probe=7cabe0e07c) | Feb 27, 2022 |
| Digiboard     | MPxx                        | Desktop     | [9ad44a5962](https://linux-hardware.org/?probe=9ad44a5962) | Feb 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [e65c4dc3c7](https://linux-hardware.org/?probe=e65c4dc3c7) | Feb 26, 2022 |
| ASUSTek       | X451CAP                     | Notebook    | [733cc22d43](https://linux-hardware.org/?probe=733cc22d43) | Feb 26, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [787d7a32b7](https://linux-hardware.org/?probe=787d7a32b7) | Feb 26, 2022 |
| Samsung       | 550XDA                      | Notebook    | [460d65857c](https://linux-hardware.org/?probe=460d65857c) | Feb 26, 2022 |
| Samsung       | 550XDA                      | Notebook    | [a41870c5b7](https://linux-hardware.org/?probe=a41870c5b7) | Feb 26, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f5ae3c9897](https://linux-hardware.org/?probe=f5ae3c9897) | Feb 26, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [72dc373199](https://linux-hardware.org/?probe=72dc373199) | Feb 26, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [d55cc6eae3](https://linux-hardware.org/?probe=d55cc6eae3) | Feb 26, 2022 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [567a2d4073](https://linux-hardware.org/?probe=567a2d4073) | Feb 26, 2022 |
| HP            | Pavilion g4                 | Notebook    | [0e40990ec2](https://linux-hardware.org/?probe=0e40990ec2) | Feb 26, 2022 |
| Positivo B... | VJFE52F11X-B1111S           | Notebook    | [893011f788](https://linux-hardware.org/?probe=893011f788) | Feb 26, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [dfea927361](https://linux-hardware.org/?probe=dfea927361) | Feb 26, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [72d6263861](https://linux-hardware.org/?probe=72d6263861) | Feb 26, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [17586d38de](https://linux-hardware.org/?probe=17586d38de) | Feb 26, 2022 |
| Biostar       | NM70I-1017U                 | Desktop     | [f35ed03897](https://linux-hardware.org/?probe=f35ed03897) | Feb 25, 2022 |
| Dell          | Inspiron 5448               | Notebook    | [2458e07e0d](https://linux-hardware.org/?probe=2458e07e0d) | Feb 25, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [ac581c6a60](https://linux-hardware.org/?probe=ac581c6a60) | Feb 25, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| Dell          | 0KRXWM A02                  | Desktop     | [01a5ebd96b](https://linux-hardware.org/?probe=01a5ebd96b) | Feb 25, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [9e276a3e5b](https://linux-hardware.org/?probe=9e276a3e5b) | Feb 25, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [6754afe86b](https://linux-hardware.org/?probe=6754afe86b) | Feb 25, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [8340571f28](https://linux-hardware.org/?probe=8340571f28) | Feb 25, 2022 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [7e14c1aa3b](https://linux-hardware.org/?probe=7e14c1aa3b) | Feb 25, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [903ce0415a](https://linux-hardware.org/?probe=903ce0415a) | Feb 25, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [c55ba8cab2](https://linux-hardware.org/?probe=c55ba8cab2) | Feb 25, 2022 |
| Positivo      | POS-AG31AP                  | Desktop     | [87841e3821](https://linux-hardware.org/?probe=87841e3821) | Feb 24, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [ba023e3489](https://linux-hardware.org/?probe=ba023e3489) | Feb 24, 2022 |
| Positivo      | POS-AG31AP                  | Desktop     | [0e4ed2b710](https://linux-hardware.org/?probe=0e4ed2b710) | Feb 24, 2022 |
| LG Electro... | 22V240 FAB3                 | All in one  | [23b20c26f2](https://linux-hardware.org/?probe=23b20c26f2) | Feb 24, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [d02db54216](https://linux-hardware.org/?probe=d02db54216) | Feb 24, 2022 |
| LG Electro... | S425-G.BC31P1               | Notebook    | [d08e9c2b6c](https://linux-hardware.org/?probe=d08e9c2b6c) | Feb 24, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [b94d0c6e20](https://linux-hardware.org/?probe=b94d0c6e20) | Feb 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [cbdc973c33](https://linux-hardware.org/?probe=cbdc973c33) | Feb 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [b1354ad7df](https://linux-hardware.org/?probe=b1354ad7df) | Feb 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [7f2fc1617a](https://linux-hardware.org/?probe=7f2fc1617a) | Feb 24, 2022 |
| Samsung       | 530XBB                      | Notebook    | [88ec5ad0c4](https://linux-hardware.org/?probe=88ec5ad0c4) | Feb 24, 2022 |
| HP            | Pavilion dv4 2055br         | Notebook    | [11dee71ccf](https://linux-hardware.org/?probe=11dee71ccf) | Feb 24, 2022 |
| HP            | Pavilion dm1                | Notebook    | [cc944526a3](https://linux-hardware.org/?probe=cc944526a3) | Feb 24, 2022 |
| HP            | Pavilion dm1                | Notebook    | [6553871bc1](https://linux-hardware.org/?probe=6553871bc1) | Feb 24, 2022 |
| Toshiba       | IS 1412                     | Notebook    | [3621d1064d](https://linux-hardware.org/?probe=3621d1064d) | Feb 24, 2022 |
| Intel         | S1200SP H57533-210          | Server      | [7c1fa00b21](https://linux-hardware.org/?probe=7c1fa00b21) | Feb 23, 2022 |
| Positivo      | POS-AG31AP                  | Desktop     | [bb3146467c](https://linux-hardware.org/?probe=bb3146467c) | Feb 23, 2022 |
| Positivo      | POS-AG31AP                  | Desktop     | [cbca5bf3a8](https://linux-hardware.org/?probe=cbca5bf3a8) | Feb 23, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [2f53cef399](https://linux-hardware.org/?probe=2f53cef399) | Feb 23, 2022 |
| Intel         | H55                         | Desktop     | [39bf688b34](https://linux-hardware.org/?probe=39bf688b34) | Feb 23, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [da3e382cd2](https://linux-hardware.org/?probe=da3e382cd2) | Feb 23, 2022 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [7cd7c3a4ab](https://linux-hardware.org/?probe=7cd7c3a4ab) | Feb 23, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [4ad321a25c](https://linux-hardware.org/?probe=4ad321a25c) | Feb 23, 2022 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [b460bc4c34](https://linux-hardware.org/?probe=b460bc4c34) | Feb 23, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [19a31feaf4](https://linux-hardware.org/?probe=19a31feaf4) | Feb 22, 2022 |
| Lenovo        | ThinkCentre M90p 5485AG8    | Desktop     | [413a69681a](https://linux-hardware.org/?probe=413a69681a) | Feb 22, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [34efccbe97](https://linux-hardware.org/?probe=34efccbe97) | Feb 22, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [91c3328a21](https://linux-hardware.org/?probe=91c3328a21) | Feb 22, 2022 |
| Acer          | V5-171                      | Notebook    | [2ef877834d](https://linux-hardware.org/?probe=2ef877834d) | Feb 22, 2022 |
| Dell          | Latitude 3420               | Notebook    | [fb586744c3](https://linux-hardware.org/?probe=fb586744c3) | Feb 22, 2022 |
| LG Electro... | R410-L.D211P1               | Notebook    | [db073c90fd](https://linux-hardware.org/?probe=db073c90fd) | Feb 22, 2022 |
| Positivo      | Mobile                      | Notebook    | [5192d94c20](https://linux-hardware.org/?probe=5192d94c20) | Feb 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [c4ba00804b](https://linux-hardware.org/?probe=c4ba00804b) | Feb 22, 2022 |
| Dell          | 057XR4 A00                  | All in one  | [6d6980bc69](https://linux-hardware.org/?probe=6d6980bc69) | Feb 21, 2022 |
| Lenovo        | ThinkPad T420 4180LVP       | Notebook    | [f044c1a44d](https://linux-hardware.org/?probe=f044c1a44d) | Feb 21, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [750e864bf2](https://linux-hardware.org/?probe=750e864bf2) | Feb 21, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [c84d38d52f](https://linux-hardware.org/?probe=c84d38d52f) | Feb 21, 2022 |
| Unknown       | PCWARE APMCP68              | Desktop     | [4a123c183a](https://linux-hardware.org/?probe=4a123c183a) | Feb 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [d8c0892058](https://linux-hardware.org/?probe=d8c0892058) | Feb 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [fa1b42a476](https://linux-hardware.org/?probe=fa1b42a476) | Feb 21, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [c671dad477](https://linux-hardware.org/?probe=c671dad477) | Feb 21, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [6e37f69275](https://linux-hardware.org/?probe=6e37f69275) | Feb 21, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [5031241166](https://linux-hardware.org/?probe=5031241166) | Feb 21, 2022 |
| Positivo      | Smash                       | Notebook    | [68fd957c2e](https://linux-hardware.org/?probe=68fd957c2e) | Feb 21, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [1a5f1021df](https://linux-hardware.org/?probe=1a5f1021df) | Feb 21, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [d6b6cbe6c9](https://linux-hardware.org/?probe=d6b6cbe6c9) | Feb 21, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [5431dfb2ef](https://linux-hardware.org/?probe=5431dfb2ef) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [9264e93f98](https://linux-hardware.org/?probe=9264e93f98) | Feb 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [558ef9e9d4](https://linux-hardware.org/?probe=558ef9e9d4) | Feb 20, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [388a17923c](https://linux-hardware.org/?probe=388a17923c) | Feb 20, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [b9e6d11567](https://linux-hardware.org/?probe=b9e6d11567) | Feb 20, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [5d16d8202f](https://linux-hardware.org/?probe=5d16d8202f) | Feb 20, 2022 |
| Multilaser    | PC130                       | Notebook    | [4a49294d21](https://linux-hardware.org/?probe=4a49294d21) | Feb 20, 2022 |
| Multilaser    | PC130                       | Notebook    | [4681b7ae9e](https://linux-hardware.org/?probe=4681b7ae9e) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [65c44b63d6](https://linux-hardware.org/?probe=65c44b63d6) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [d8c4226f82](https://linux-hardware.org/?probe=d8c4226f82) | Feb 20, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [e844adcca1](https://linux-hardware.org/?probe=e844adcca1) | Feb 20, 2022 |
| HP            | Pavilion dv4 2055br         | Notebook    | [726c38b448](https://linux-hardware.org/?probe=726c38b448) | Feb 20, 2022 |
| Dell          | 07N90W A02                  | Desktop     | [caa8d90509](https://linux-hardware.org/?probe=caa8d90509) | Feb 20, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [642e1f0705](https://linux-hardware.org/?probe=642e1f0705) | Feb 20, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [8c976c5259](https://linux-hardware.org/?probe=8c976c5259) | Feb 20, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [198452fc15](https://linux-hardware.org/?probe=198452fc15) | Feb 20, 2022 |
| Digitron      | G31T-M7                     | Desktop     | [8c83de382a](https://linux-hardware.org/?probe=8c83de382a) | Feb 19, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [8a64c8dde8](https://linux-hardware.org/?probe=8a64c8dde8) | Feb 19, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [5d973743c8](https://linux-hardware.org/?probe=5d973743c8) | Feb 19, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [c73dc0aa9f](https://linux-hardware.org/?probe=c73dc0aa9f) | Feb 19, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [f1f8a3c656](https://linux-hardware.org/?probe=f1f8a3c656) | Feb 19, 2022 |
| LG Electro... | U460-G.BG51P1               | Notebook    | [493da7c326](https://linux-hardware.org/?probe=493da7c326) | Feb 19, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [00427ca464](https://linux-hardware.org/?probe=00427ca464) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [86af1dc736](https://linux-hardware.org/?probe=86af1dc736) | Feb 19, 2022 |
| Acer          | Aspire 4738                 | Notebook    | [f4b2c409f4](https://linux-hardware.org/?probe=f4b2c409f4) | Feb 19, 2022 |
| Positivo      | CHT14B                      | Notebook    | [c2f39e4414](https://linux-hardware.org/?probe=c2f39e4414) | Feb 19, 2022 |
| Positivo      | CHT14B                      | Notebook    | [674256dc2a](https://linux-hardware.org/?probe=674256dc2a) | Feb 19, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [0b554c2d97](https://linux-hardware.org/?probe=0b554c2d97) | Feb 19, 2022 |
| Positivo      | S14CT01                     | Notebook    | [eac3e2cb5d](https://linux-hardware.org/?probe=eac3e2cb5d) | Feb 19, 2022 |
| Lenovo        | ThinkPad T440 20B7008ABR    | Notebook    | [b690de8548](https://linux-hardware.org/?probe=b690de8548) | Feb 19, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [cce1f45d54](https://linux-hardware.org/?probe=cce1f45d54) | Feb 19, 2022 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [546d09f207](https://linux-hardware.org/?probe=546d09f207) | Feb 19, 2022 |
| Lenovo        | Yoga 500-14IBD 80NE         | Notebook    | [8b199e2a77](https://linux-hardware.org/?probe=8b199e2a77) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ef345f036b](https://linux-hardware.org/?probe=ef345f036b) | Feb 19, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [700b7ea8e8](https://linux-hardware.org/?probe=700b7ea8e8) | Feb 18, 2022 |
| Avell High... | B.ON                        | Notebook    | [9ef94d96d1](https://linux-hardware.org/?probe=9ef94d96d1) | Feb 18, 2022 |
| Acer          | Aspire 5741Z                | Notebook    | [93f3b53e77](https://linux-hardware.org/?probe=93f3b53e77) | Feb 18, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [59a321d574](https://linux-hardware.org/?probe=59a321d574) | Feb 18, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [c2df5bb692](https://linux-hardware.org/?probe=c2df5bb692) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [e0837f8e22](https://linux-hardware.org/?probe=e0837f8e22) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440 20B7003LBR    | Notebook    | [74fa6de20d](https://linux-hardware.org/?probe=74fa6de20d) | Feb 18, 2022 |
| Compaq        | Presario CQ-17              | Notebook    | [02d0a5926f](https://linux-hardware.org/?probe=02d0a5926f) | Feb 18, 2022 |
| Avell High... | B.ON                        | Notebook    | [3b3e1a7730](https://linux-hardware.org/?probe=3b3e1a7730) | Feb 18, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [d0372ba4af](https://linux-hardware.org/?probe=d0372ba4af) | Feb 18, 2022 |
| ATI           | BONEFISH                    | Notebook    | [caa7c41c75](https://linux-hardware.org/?probe=caa7c41c75) | Feb 17, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [b1ab92368d](https://linux-hardware.org/?probe=b1ab92368d) | Feb 17, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [4a66255bed](https://linux-hardware.org/?probe=4a66255bed) | Feb 17, 2022 |
| Avell High... | B.ON                        | Notebook    | [26b25d67d6](https://linux-hardware.org/?probe=26b25d67d6) | Feb 17, 2022 |
| Intel         | DH55PJ AAE93812-302         | Desktop     | [491016ec7c](https://linux-hardware.org/?probe=491016ec7c) | Feb 16, 2022 |
| HP            | 2B2F MVB,A                  | All in one  | [06be58f9b6](https://linux-hardware.org/?probe=06be58f9b6) | Feb 16, 2022 |
| HP            | 3048h                       | Desktop     | [6f448e856a](https://linux-hardware.org/?probe=6f448e856a) | Feb 16, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [311429d9ef](https://linux-hardware.org/?probe=311429d9ef) | Feb 16, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e03bf2b8a8](https://linux-hardware.org/?probe=e03bf2b8a8) | Feb 16, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [21d0529167](https://linux-hardware.org/?probe=21d0529167) | Feb 16, 2022 |
| Intel         | H55                         | Desktop     | [b890b6f13e](https://linux-hardware.org/?probe=b890b6f13e) | Feb 16, 2022 |
| Huanan        | X79-ZD3 V2.3                | Desktop     | [c20523ee1f](https://linux-hardware.org/?probe=c20523ee1f) | Feb 15, 2022 |
| Dell          | Inspiron 5468               | Notebook    | [06eaa64926](https://linux-hardware.org/?probe=06eaa64926) | Feb 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [f84382df07](https://linux-hardware.org/?probe=f84382df07) | Feb 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [32b28f79c9](https://linux-hardware.org/?probe=32b28f79c9) | Feb 15, 2022 |
| Centrium      | C2014-H81H3-M4              | Desktop     | [6b0be9c067](https://linux-hardware.org/?probe=6b0be9c067) | Feb 15, 2022 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [b36ee90ac0](https://linux-hardware.org/?probe=b36ee90ac0) | Feb 15, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [2504c5ff16](https://linux-hardware.org/?probe=2504c5ff16) | Feb 15, 2022 |
| Intel         | W7650                       | Notebook    | [16cb290b88](https://linux-hardware.org/?probe=16cb290b88) | Feb 15, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [19c20b4b30](https://linux-hardware.org/?probe=19c20b4b30) | Feb 15, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [e202260efb](https://linux-hardware.org/?probe=e202260efb) | Feb 14, 2022 |
| Avell High... | B.ON                        | Notebook    | [736bab4e42](https://linux-hardware.org/?probe=736bab4e42) | Feb 14, 2022 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | Notebook    | [dfe8d18c8d](https://linux-hardware.org/?probe=dfe8d18c8d) | Feb 14, 2022 |
| Positivo      | CHT12CP                     | Notebook    | [d0d94ff35a](https://linux-hardware.org/?probe=d0d94ff35a) | Feb 14, 2022 |
| System76      | Galago Pro                  | Notebook    | [6ecd530026](https://linux-hardware.org/?probe=6ecd530026) | Feb 14, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [6846e14550](https://linux-hardware.org/?probe=6846e14550) | Feb 14, 2022 |
| Acer          | V5-171                      | Notebook    | [0200220f80](https://linux-hardware.org/?probe=0200220f80) | Feb 14, 2022 |
| Philco        | 10D                         | Desktop     | [2efb7555a1](https://linux-hardware.org/?probe=2efb7555a1) | Feb 14, 2022 |
| System76      | Galago Pro                  | Notebook    | [b3b3e5cfa0](https://linux-hardware.org/?probe=b3b3e5cfa0) | Feb 14, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | Notebook    | [aa3ec329c6](https://linux-hardware.org/?probe=aa3ec329c6) | Feb 14, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [3db88da0ec](https://linux-hardware.org/?probe=3db88da0ec) | Feb 13, 2022 |
| Positivo      | POS-PIH81DI                 | Desktop     | [64c37730f6](https://linux-hardware.org/?probe=64c37730f6) | Feb 13, 2022 |
| Sony          | VGN-Z550N                   | Notebook    | [2ea7027f87](https://linux-hardware.org/?probe=2ea7027f87) | Feb 13, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [f2968206ac](https://linux-hardware.org/?probe=f2968206ac) | Feb 13, 2022 |
| Dell          | Latitude E7440              | Notebook    | [a43b6273dd](https://linux-hardware.org/?probe=a43b6273dd) | Feb 13, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [d7da9b2ff3](https://linux-hardware.org/?probe=d7da9b2ff3) | Feb 13, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [0303c5a132](https://linux-hardware.org/?probe=0303c5a132) | Feb 13, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [2a2ca89607](https://linux-hardware.org/?probe=2a2ca89607) | Feb 13, 2022 |
| Dell          | Latitude E5450              | Notebook    | [09fa63b2aa](https://linux-hardware.org/?probe=09fa63b2aa) | Feb 13, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [de30d6bb15](https://linux-hardware.org/?probe=de30d6bb15) | Feb 13, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [1f5dd04a09](https://linux-hardware.org/?probe=1f5dd04a09) | Feb 13, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [2e9d58f492](https://linux-hardware.org/?probe=2e9d58f492) | Feb 13, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [dd5c587aaa](https://linux-hardware.org/?probe=dd5c587aaa) | Feb 13, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80W2      | Notebook    | [045c989217](https://linux-hardware.org/?probe=045c989217) | Feb 13, 2022 |
| ASUSTek       | K84C                        | Notebook    | [4ca657e962](https://linux-hardware.org/?probe=4ca657e962) | Feb 12, 2022 |
| Dell          | Latitude 5490               | Notebook    | [4de050de9d](https://linux-hardware.org/?probe=4de050de9d) | Feb 12, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [295d9daf15](https://linux-hardware.org/?probe=295d9daf15) | Feb 12, 2022 |
| Dell          | 0DT097 A00                  | Server      | [ca96304cac](https://linux-hardware.org/?probe=ca96304cac) | Feb 12, 2022 |
| ECS           | A785GM-AD3                  | Desktop     | [b6459dbb39](https://linux-hardware.org/?probe=b6459dbb39) | Feb 12, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [efb0663602](https://linux-hardware.org/?probe=efb0663602) | Feb 12, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [a9271fbd9f](https://linux-hardware.org/?probe=a9271fbd9f) | Feb 12, 2022 |
| ASUSTek       | P8Z77-M                     | Desktop     | [2662081a67](https://linux-hardware.org/?probe=2662081a67) | Feb 12, 2022 |
| Positivo      | N4340                       | Notebook    | [45302cfd33](https://linux-hardware.org/?probe=45302cfd33) | Feb 12, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [037faea8f6](https://linux-hardware.org/?probe=037faea8f6) | Feb 12, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [5124a5816c](https://linux-hardware.org/?probe=5124a5816c) | Feb 12, 2022 |
| Samsung       | 530XBB                      | Notebook    | [4da9be49c4](https://linux-hardware.org/?probe=4da9be49c4) | Feb 12, 2022 |
| ASUSTek       | K84C                        | Notebook    | [338aea772f](https://linux-hardware.org/?probe=338aea772f) | Feb 11, 2022 |
| Positivo      | POS-EAA75DE                 | Desktop     | [1b14cace5c](https://linux-hardware.org/?probe=1b14cace5c) | Feb 11, 2022 |
| Philco        | 10D                         | Notebook    | [562bb178d4](https://linux-hardware.org/?probe=562bb178d4) | Feb 11, 2022 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [ff7b84fe78](https://linux-hardware.org/?probe=ff7b84fe78) | Feb 11, 2022 |
| Dell          | 0K240Y A04                  | Desktop     | [4342c15fb0](https://linux-hardware.org/?probe=4342c15fb0) | Feb 11, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [98a3f252a8](https://linux-hardware.org/?probe=98a3f252a8) | Feb 11, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [81fb0bce4d](https://linux-hardware.org/?probe=81fb0bce4d) | Feb 11, 2022 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [0caedcc26b](https://linux-hardware.org/?probe=0caedcc26b) | Feb 11, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [dbacdb1c14](https://linux-hardware.org/?probe=dbacdb1c14) | Feb 11, 2022 |
| ASUSTek       | X102BA                      | Notebook    | [401e015fff](https://linux-hardware.org/?probe=401e015fff) | Feb 11, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [2885a7e3ed](https://linux-hardware.org/?probe=2885a7e3ed) | Feb 11, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [f886f43d19](https://linux-hardware.org/?probe=f886f43d19) | Feb 11, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [d6a821dc5b](https://linux-hardware.org/?probe=d6a821dc5b) | Feb 11, 2022 |
| Intel         | H61                         | Desktop     | [e06357425a](https://linux-hardware.org/?probe=e06357425a) | Feb 11, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | Notebook    | [c400d6b3f2](https://linux-hardware.org/?probe=c400d6b3f2) | Feb 11, 2022 |
| PCWare        | IPMH61R3 8MB                | Desktop     | [58a0a81447](https://linux-hardware.org/?probe=58a0a81447) | Feb 11, 2022 |
| Digibras      | CL341                       | Notebook    | [f3b678924d](https://linux-hardware.org/?probe=f3b678924d) | Feb 11, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [c155b2bd06](https://linux-hardware.org/?probe=c155b2bd06) | Feb 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [bd8513dc66](https://linux-hardware.org/?probe=bd8513dc66) | Feb 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6a4a06344a](https://linux-hardware.org/?probe=6a4a06344a) | Feb 10, 2022 |
| HP            | 829A                        | Mini pc     | [67a56e0954](https://linux-hardware.org/?probe=67a56e0954) | Feb 10, 2022 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [5b9ae01006](https://linux-hardware.org/?probe=5b9ae01006) | Feb 10, 2022 |
| ASUSTek       | Z450UAK                     | Notebook    | [d619483cc3](https://linux-hardware.org/?probe=d619483cc3) | Feb 10, 2022 |
| Sony          | VGN-Z550N                   | Notebook    | [92a2b7000d](https://linux-hardware.org/?probe=92a2b7000d) | Feb 10, 2022 |
| Sony          | VGN-Z550N                   | Notebook    | [9d1ed43ea9](https://linux-hardware.org/?probe=9d1ed43ea9) | Feb 10, 2022 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [1b903af2df](https://linux-hardware.org/?probe=1b903af2df) | Feb 10, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [b53861af9b](https://linux-hardware.org/?probe=b53861af9b) | Feb 09, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [62d5812547](https://linux-hardware.org/?probe=62d5812547) | Feb 09, 2022 |
| Avell High... | B.ON                        | Notebook    | [299d30a86c](https://linux-hardware.org/?probe=299d30a86c) | Feb 09, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [dfb7099c69](https://linux-hardware.org/?probe=dfb7099c69) | Feb 09, 2022 |
| Intel         | DH55HC AAE70933-502         | Desktop     | [daabbb468a](https://linux-hardware.org/?probe=daabbb468a) | Feb 09, 2022 |
| Gigabyte      | H310M M.2                   | Desktop     | [41502e29af](https://linux-hardware.org/?probe=41502e29af) | Feb 09, 2022 |
| Positivo B... | VJFE52F11X-B1111S           | Notebook    | [75e404cde1](https://linux-hardware.org/?probe=75e404cde1) | Feb 09, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [3f2bbe863b](https://linux-hardware.org/?probe=3f2bbe863b) | Feb 09, 2022 |
| Lenovo        | IdeaPad G485 QAWGE          | Notebook    | [6e92f61334](https://linux-hardware.org/?probe=6e92f61334) | Feb 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [6e83303f73](https://linux-hardware.org/?probe=6e83303f73) | Feb 09, 2022 |
| Samsung       | 530XBB                      | Notebook    | [dd0298264f](https://linux-hardware.org/?probe=dd0298264f) | Feb 09, 2022 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [48e68c86d6](https://linux-hardware.org/?probe=48e68c86d6) | Feb 09, 2022 |
| Dell          | XPS L421X                   | Notebook    | [f84aa1d978](https://linux-hardware.org/?probe=f84aa1d978) | Feb 09, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [6140bf02fa](https://linux-hardware.org/?probe=6140bf02fa) | Feb 09, 2022 |
| Positivo      | POS-EINM70CS POSITIVO       | Desktop     | [28b687e587](https://linux-hardware.org/?probe=28b687e587) | Feb 09, 2022 |
| Dell          | XPS L421X                   | Notebook    | [e869731d45](https://linux-hardware.org/?probe=e869731d45) | Feb 09, 2022 |
| Compaq        | TL009                       | All in one  | [f97345c4f4](https://linux-hardware.org/?probe=f97345c4f4) | Feb 09, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [0d09c987ef](https://linux-hardware.org/?probe=0d09c987ef) | Feb 09, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [3dffdcc5d3](https://linux-hardware.org/?probe=3dffdcc5d3) | Feb 09, 2022 |
| Razer         | Blade                       | Notebook    | [688d6b74bc](https://linux-hardware.org/?probe=688d6b74bc) | Feb 09, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [b6402a0817](https://linux-hardware.org/?probe=b6402a0817) | Feb 09, 2022 |
| Kennex        | POS-PIG41BA                 | Desktop     | [54cfa11e20](https://linux-hardware.org/?probe=54cfa11e20) | Feb 09, 2022 |
| SUPoX COMP... | B250A-BTC PRO               | Desktop     | [780b5cb42e](https://linux-hardware.org/?probe=780b5cb42e) | Feb 09, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [1dac9367c9](https://linux-hardware.org/?probe=1dac9367c9) | Feb 08, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [9f8ac3fe7f](https://linux-hardware.org/?probe=9f8ac3fe7f) | Feb 08, 2022 |
| Positivo      | N600                        | Notebook    | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Intel         | H61                         | Desktop     | [71ed0d632b](https://linux-hardware.org/?probe=71ed0d632b) | Feb 08, 2022 |
| Positivo      | N600                        | Notebook    | [1591046f31](https://linux-hardware.org/?probe=1591046f31) | Feb 08, 2022 |
| PCChips       | A51G                        | Desktop     | [c3b2b7a8a3](https://linux-hardware.org/?probe=c3b2b7a8a3) | Feb 08, 2022 |
| Dell          | 0KWVT8 A02                  | Desktop     | [d48b27d912](https://linux-hardware.org/?probe=d48b27d912) | Feb 08, 2022 |
| PCChips       | A51G                        | Desktop     | [7f3ae0e392](https://linux-hardware.org/?probe=7f3ae0e392) | Feb 08, 2022 |
| Supermicro    | X9DAi                       | Desktop     | [ea3cbb18b7](https://linux-hardware.org/?probe=ea3cbb18b7) | Feb 08, 2022 |
| Supermicro    | X9DAi                       | Desktop     | [f4ce79a016](https://linux-hardware.org/?probe=f4ce79a016) | Feb 08, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [74eb28f4a3](https://linux-hardware.org/?probe=74eb28f4a3) | Feb 08, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [c5f7e8a1d6](https://linux-hardware.org/?probe=c5f7e8a1d6) | Feb 08, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [9aa6cb1e41](https://linux-hardware.org/?probe=9aa6cb1e41) | Feb 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [4b3eedcd91](https://linux-hardware.org/?probe=4b3eedcd91) | Feb 08, 2022 |
| Samsung       | 550XDA                      | Notebook    | [ec92003cdd](https://linux-hardware.org/?probe=ec92003cdd) | Feb 08, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [6bb9884c12](https://linux-hardware.org/?probe=6bb9884c12) | Feb 08, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [d08f0c4b79](https://linux-hardware.org/?probe=d08f0c4b79) | Feb 08, 2022 |
| Digiboard     | NM70-TI                     | Desktop     | [94fb04410f](https://linux-hardware.org/?probe=94fb04410f) | Feb 08, 2022 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [36b7150c17](https://linux-hardware.org/?probe=36b7150c17) | Feb 08, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [5195720c69](https://linux-hardware.org/?probe=5195720c69) | Feb 08, 2022 |
| Dell          | Inspiron 5481               | Convertible | [1f266a5183](https://linux-hardware.org/?probe=1f266a5183) | Feb 08, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [08bf40800a](https://linux-hardware.org/?probe=08bf40800a) | Feb 08, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [cdab54c6de](https://linux-hardware.org/?probe=cdab54c6de) | Feb 07, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [9d53729c91](https://linux-hardware.org/?probe=9d53729c91) | Feb 07, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [4ceccc2e76](https://linux-hardware.org/?probe=4ceccc2e76) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| HP            | 859C                        | Desktop     | [e984dd6733](https://linux-hardware.org/?probe=e984dd6733) | Feb 07, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [733ee79a8f](https://linux-hardware.org/?probe=733ee79a8f) | Feb 07, 2022 |
| ASRock        | 970A-G                      | Desktop     | [de12500bf9](https://linux-hardware.org/?probe=de12500bf9) | Feb 07, 2022 |
| Gateway       | NV55C                       | Notebook    | [27fd1ff7f1](https://linux-hardware.org/?probe=27fd1ff7f1) | Feb 07, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c8c77fd622](https://linux-hardware.org/?probe=c8c77fd622) | Feb 07, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [38aadf36ea](https://linux-hardware.org/?probe=38aadf36ea) | Feb 07, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [a6b95e1220](https://linux-hardware.org/?probe=a6b95e1220) | Feb 07, 2022 |
| Biostar       | H81A                        | Desktop     | [e045b16856](https://linux-hardware.org/?probe=e045b16856) | Feb 07, 2022 |
| ASUSTek       | TUF GAMING B460M-PLUS       | Desktop     | [cec6148a23](https://linux-hardware.org/?probe=cec6148a23) | Feb 07, 2022 |
| Lenovo        | ThinkPad E490 20N9A02FBR    | Notebook    | [f7c6505e86](https://linux-hardware.org/?probe=f7c6505e86) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [09e661535f](https://linux-hardware.org/?probe=09e661535f) | Feb 07, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [37a64d4872](https://linux-hardware.org/?probe=37a64d4872) | Feb 06, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [824af874a4](https://linux-hardware.org/?probe=824af874a4) | Feb 06, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [dd6e3f3a64](https://linux-hardware.org/?probe=dd6e3f3a64) | Feb 06, 2022 |
| Positivo      | C14CU51                     | Notebook    | [c3d5c7e4a7](https://linux-hardware.org/?probe=c3d5c7e4a7) | Feb 06, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [74ebb0645d](https://linux-hardware.org/?probe=74ebb0645d) | Feb 06, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [d6f8f41bc5](https://linux-hardware.org/?probe=d6f8f41bc5) | Feb 06, 2022 |
| Samsung       | 550XDA                      | Notebook    | [9c9b8d6672](https://linux-hardware.org/?probe=9c9b8d6672) | Feb 06, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [9ac652a7bf](https://linux-hardware.org/?probe=9ac652a7bf) | Feb 06, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [7030f02dfa](https://linux-hardware.org/?probe=7030f02dfa) | Feb 06, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [1f5badca6e](https://linux-hardware.org/?probe=1f5badca6e) | Feb 06, 2022 |
| ASUSTek       | K42F                        | Notebook    | [8bab320535](https://linux-hardware.org/?probe=8bab320535) | Feb 06, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [345a864747](https://linux-hardware.org/?probe=345a864747) | Feb 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a41632fc91](https://linux-hardware.org/?probe=a41632fc91) | Feb 05, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a07e2de32a](https://linux-hardware.org/?probe=a07e2de32a) | Feb 05, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [bf8d058c93](https://linux-hardware.org/?probe=bf8d058c93) | Feb 05, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [e3bbffb77b](https://linux-hardware.org/?probe=e3bbffb77b) | Feb 05, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [f4319bd379](https://linux-hardware.org/?probe=f4319bd379) | Feb 05, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [6c5369cb37](https://linux-hardware.org/?probe=6c5369cb37) | Feb 05, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [79e02b1ade](https://linux-hardware.org/?probe=79e02b1ade) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [8aab9e3d48](https://linux-hardware.org/?probe=8aab9e3d48) | Feb 05, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [36c52eaf3d](https://linux-hardware.org/?probe=36c52eaf3d) | Feb 05, 2022 |
| Samsung       | 530XBB                      | Notebook    | [ccc2c811de](https://linux-hardware.org/?probe=ccc2c811de) | Feb 05, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [10c9ca0b26](https://linux-hardware.org/?probe=10c9ca0b26) | Feb 05, 2022 |
| Itautec       | Infoway w7730               | Notebook    | [c3d571b041](https://linux-hardware.org/?probe=c3d571b041) | Feb 05, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [802fcebea6](https://linux-hardware.org/?probe=802fcebea6) | Feb 04, 2022 |
| HP            | Pavilion dm1                | Notebook    | [4b0fcd3df5](https://linux-hardware.org/?probe=4b0fcd3df5) | Feb 04, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [37c0fc9564](https://linux-hardware.org/?probe=37c0fc9564) | Feb 04, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [417bb2f526](https://linux-hardware.org/?probe=417bb2f526) | Feb 04, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [cab5335d99](https://linux-hardware.org/?probe=cab5335d99) | Feb 04, 2022 |
| Positivo      | Mobile                      | Notebook    | [762406b308](https://linux-hardware.org/?probe=762406b308) | Feb 04, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [9a2365cd5c](https://linux-hardware.org/?probe=9a2365cd5c) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [1f4e97ac28](https://linux-hardware.org/?probe=1f4e97ac28) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [e799f33b3f](https://linux-hardware.org/?probe=e799f33b3f) | Feb 04, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [9b5cf9015f](https://linux-hardware.org/?probe=9b5cf9015f) | Feb 04, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [dad82452b2](https://linux-hardware.org/?probe=dad82452b2) | Feb 03, 2022 |
| Dell          | Latitude 5420               | Notebook    | [bbf52a52c3](https://linux-hardware.org/?probe=bbf52a52c3) | Feb 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [a720c94820](https://linux-hardware.org/?probe=a720c94820) | Feb 03, 2022 |
| Dell          | Latitude 5420               | Notebook    | [29b1f9a6d4](https://linux-hardware.org/?probe=29b1f9a6d4) | Feb 03, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [fc543d0d57](https://linux-hardware.org/?probe=fc543d0d57) | Feb 03, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [4524a07e84](https://linux-hardware.org/?probe=4524a07e84) | Feb 03, 2022 |
| Biostar       | H510MH                      | Desktop     | [2058cb6d56](https://linux-hardware.org/?probe=2058cb6d56) | Feb 03, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9da6b947f5](https://linux-hardware.org/?probe=9da6b947f5) | Feb 03, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [ebc65d68d9](https://linux-hardware.org/?probe=ebc65d68d9) | Feb 03, 2022 |
| ASRock        | FM2A68M-HD+ R2.0            | Desktop     | [2f5f68141f](https://linux-hardware.org/?probe=2f5f68141f) | Feb 03, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [f260feda72](https://linux-hardware.org/?probe=f260feda72) | Feb 03, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [08ea66be77](https://linux-hardware.org/?probe=08ea66be77) | Feb 03, 2022 |
| ASRock        | FM2A68M-HD+ R2.0            | Desktop     | [d0ba3786b2](https://linux-hardware.org/?probe=d0ba3786b2) | Feb 03, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [1add69d20a](https://linux-hardware.org/?probe=1add69d20a) | Feb 03, 2022 |
| Dell          | 0XCR8D A01                  | Desktop     | [a68034b1e8](https://linux-hardware.org/?probe=a68034b1e8) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [67e8645c04](https://linux-hardware.org/?probe=67e8645c04) | Feb 03, 2022 |
| Multilaser    | PC024                       | Tablet      | [9ad6a77447](https://linux-hardware.org/?probe=9ad6a77447) | Feb 03, 2022 |
| Multilaser    | PC024                       | Tablet      | [bd6cbc4c5e](https://linux-hardware.org/?probe=bd6cbc4c5e) | Feb 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [39dcd3854f](https://linux-hardware.org/?probe=39dcd3854f) | Feb 03, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [1762291c98](https://linux-hardware.org/?probe=1762291c98) | Feb 02, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [a7b8841235](https://linux-hardware.org/?probe=a7b8841235) | Feb 02, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [f8f690a2b4](https://linux-hardware.org/?probe=f8f690a2b4) | Feb 02, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [1fc021cf65](https://linux-hardware.org/?probe=1fc021cf65) | Feb 02, 2022 |
| LG Electro... | S425-G.BC31P1               | Notebook    | [fa414c50c0](https://linux-hardware.org/?probe=fa414c50c0) | Feb 02, 2022 |
| Intel         | W7650                       | Notebook    | [930e8f9b6a](https://linux-hardware.org/?probe=930e8f9b6a) | Feb 02, 2022 |
| Intel         | W7650                       | Notebook    | [5ea44e43ef](https://linux-hardware.org/?probe=5ea44e43ef) | Feb 02, 2022 |
| Sony          | SVS13A25PBS                 | Notebook    | [9072890c1d](https://linux-hardware.org/?probe=9072890c1d) | Feb 02, 2022 |
| Sony          | SVS13A25PBS                 | Notebook    | [894e40654e](https://linux-hardware.org/?probe=894e40654e) | Feb 02, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [6ad31c02f7](https://linux-hardware.org/?probe=6ad31c02f7) | Feb 02, 2022 |
| Dell          | Inspiron 5423               | Notebook    | [087f6b0b86](https://linux-hardware.org/?probe=087f6b0b86) | Feb 02, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [285fd7e214](https://linux-hardware.org/?probe=285fd7e214) | Feb 02, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS_BR     | Desktop     | [554e7f33b4](https://linux-hardware.org/?probe=554e7f33b4) | Feb 02, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [9d8d2dafa1](https://linux-hardware.org/?probe=9d8d2dafa1) | Feb 02, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [14d778971f](https://linux-hardware.org/?probe=14d778971f) | Feb 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [466673ab1c](https://linux-hardware.org/?probe=466673ab1c) | Feb 02, 2022 |
| Dell          | 0Y1861 A00                  | Desktop     | [cb60a2e337](https://linux-hardware.org/?probe=cb60a2e337) | Feb 02, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [f12174ddb8](https://linux-hardware.org/?probe=f12174ddb8) | Feb 02, 2022 |
| ASRock        | A320M-HD R4.0               | Desktop     | [f2dfa50076](https://linux-hardware.org/?probe=f2dfa50076) | Feb 02, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [874f163f65](https://linux-hardware.org/?probe=874f163f65) | Feb 02, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [154ca59694](https://linux-hardware.org/?probe=154ca59694) | Feb 01, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [7b278e62d8](https://linux-hardware.org/?probe=7b278e62d8) | Feb 01, 2022 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [5cc8e8f8d3](https://linux-hardware.org/?probe=5cc8e8f8d3) | Feb 01, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [ac0fd77d33](https://linux-hardware.org/?probe=ac0fd77d33) | Feb 01, 2022 |
| HP            | ProBook 6465b               | Notebook    | [aca95b9f2d](https://linux-hardware.org/?probe=aca95b9f2d) | Feb 01, 2022 |
| Avell High... | B.ON                        | Notebook    | [845b25e77d](https://linux-hardware.org/?probe=845b25e77d) | Feb 01, 2022 |
| Dell          | 0Y1861 A00                  | Desktop     | [1a05a6ca0e](https://linux-hardware.org/?probe=1a05a6ca0e) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d3a9e62b95](https://linux-hardware.org/?probe=d3a9e62b95) | Feb 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS_BR     | Desktop     | [38e6b543ca](https://linux-hardware.org/?probe=38e6b543ca) | Feb 01, 2022 |
| Digiboard     | MPxx                        | Desktop     | [1ea5e5205c](https://linux-hardware.org/?probe=1ea5e5205c) | Feb 01, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| ASUSTek       | N53Ta                       | Notebook    | [7b343f4dfd](https://linux-hardware.org/?probe=7b343f4dfd) | Feb 01, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [93038a58a7](https://linux-hardware.org/?probe=93038a58a7) | Feb 01, 2022 |
| Lenovo        | ThinkPad Edge 05782GP       | Notebook    | [fc49fcb2f6](https://linux-hardware.org/?probe=fc49fcb2f6) | Jan 31, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [4ea07fe50a](https://linux-hardware.org/?probe=4ea07fe50a) | Jan 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [829c0b88a2](https://linux-hardware.org/?probe=829c0b88a2) | Jan 31, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [07de603a4a](https://linux-hardware.org/?probe=07de603a4a) | Jan 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [54b9aa9f99](https://linux-hardware.org/?probe=54b9aa9f99) | Jan 31, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [d60beb8456](https://linux-hardware.org/?probe=d60beb8456) | Jan 31, 2022 |
| Itautec       | Infoway a7420               | Notebook    | [b58a27017b](https://linux-hardware.org/?probe=b58a27017b) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | Notebook    | [cf01ca64c3](https://linux-hardware.org/?probe=cf01ca64c3) | Jan 31, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [b08c9147e6](https://linux-hardware.org/?probe=b08c9147e6) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | Notebook    | [17015b4fbe](https://linux-hardware.org/?probe=17015b4fbe) | Jan 30, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [7cf619e5e4](https://linux-hardware.org/?probe=7cf619e5e4) | Jan 30, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [c342bd0bba](https://linux-hardware.org/?probe=c342bd0bba) | Jan 30, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [d38f4418f9](https://linux-hardware.org/?probe=d38f4418f9) | Jan 30, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS_BR     | Desktop     | [dc652a6ac4](https://linux-hardware.org/?probe=dc652a6ac4) | Jan 30, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [f1987d67dc](https://linux-hardware.org/?probe=f1987d67dc) | Jan 30, 2022 |
| Intel         | H81                         | Desktop     | [c1763fe2cf](https://linux-hardware.org/?probe=c1763fe2cf) | Jan 29, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [094fd8e853](https://linux-hardware.org/?probe=094fd8e853) | Jan 29, 2022 |
| Positivo      | H14BT58                     | Notebook    | [1469696155](https://linux-hardware.org/?probe=1469696155) | Jan 29, 2022 |
| ECS           | G31T-M                      | Desktop     | [3820396d91](https://linux-hardware.org/?probe=3820396d91) | Jan 29, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [313d4824d2](https://linux-hardware.org/?probe=313d4824d2) | Jan 29, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [8840e8dbd1](https://linux-hardware.org/?probe=8840e8dbd1) | Jan 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [ea20e32cbd](https://linux-hardware.org/?probe=ea20e32cbd) | Jan 29, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4a98af8b6c](https://linux-hardware.org/?probe=4a98af8b6c) | Jan 29, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [37a1f0912e](https://linux-hardware.org/?probe=37a1f0912e) | Jan 29, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [a3f76dfb23](https://linux-hardware.org/?probe=a3f76dfb23) | Jan 29, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [fc189e6c81](https://linux-hardware.org/?probe=fc189e6c81) | Jan 29, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [e0b0cbe190](https://linux-hardware.org/?probe=e0b0cbe190) | Jan 29, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [cf0c5309ad](https://linux-hardware.org/?probe=cf0c5309ad) | Jan 29, 2022 |
| Toshiba       | Satellite S55-C             | Notebook    | [467509424b](https://linux-hardware.org/?probe=467509424b) | Jan 28, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [95423d6649](https://linux-hardware.org/?probe=95423d6649) | Jan 28, 2022 |
| Positivo      | Mobile                      | Notebook    | [c461425f95](https://linux-hardware.org/?probe=c461425f95) | Jan 28, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [f35d941d2a](https://linux-hardware.org/?probe=f35d941d2a) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| Dell          | Inspiron 7560               | Notebook    | [ce1c4e39c2](https://linux-hardware.org/?probe=ce1c4e39c2) | Jan 28, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [6e72e70430](https://linux-hardware.org/?probe=6e72e70430) | Jan 28, 2022 |
| Acer          | Nitro AN515-53              | Notebook    | [dfcbe10351](https://linux-hardware.org/?probe=dfcbe10351) | Jan 28, 2022 |
| Dell          | Inspiron 15 3515            | Notebook    | [22a2219833](https://linux-hardware.org/?probe=22a2219833) | Jan 27, 2022 |
| Intel         | H61                         | Desktop     | [c2f4b3c4d8](https://linux-hardware.org/?probe=c2f4b3c4d8) | Jan 27, 2022 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [622d718c89](https://linux-hardware.org/?probe=622d718c89) | Jan 27, 2022 |
| Positivo      | S14BW01                     | Notebook    | [b406634127](https://linux-hardware.org/?probe=b406634127) | Jan 27, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [f741575389](https://linux-hardware.org/?probe=f741575389) | Jan 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [a952a9ecbb](https://linux-hardware.org/?probe=a952a9ecbb) | Jan 27, 2022 |
| Sony          | SVE14A15FBP                 | Notebook    | [df5205f4d5](https://linux-hardware.org/?probe=df5205f4d5) | Jan 27, 2022 |
| ASUSTek       | TUF GAMING A520M-PLUS II    | Desktop     | [ad887e6da9](https://linux-hardware.org/?probe=ad887e6da9) | Jan 27, 2022 |
| ASRock        | H61M-HG4                    | Desktop     | [442847292d](https://linux-hardware.org/?probe=442847292d) | Jan 27, 2022 |
| Positivo      | Harrison                    | Notebook    | [320f20f33d](https://linux-hardware.org/?probe=320f20f33d) | Jan 27, 2022 |
| Alienware     | x15 R1                      | Notebook    | [4d82c0e97f](https://linux-hardware.org/?probe=4d82c0e97f) | Jan 26, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [82ee6777f1](https://linux-hardware.org/?probe=82ee6777f1) | Jan 26, 2022 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [ef86245dd3](https://linux-hardware.org/?probe=ef86245dd3) | Jan 26, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [d3df4ed8e6](https://linux-hardware.org/?probe=d3df4ed8e6) | Jan 26, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [8a951a4419](https://linux-hardware.org/?probe=8a951a4419) | Jan 26, 2022 |
| ASRock        | ION3D-HT                    | Desktop     | [dc36b83c20](https://linux-hardware.org/?probe=dc36b83c20) | Jan 26, 2022 |
| ASRock        | G31M-S                      | Desktop     | [e579ce1757](https://linux-hardware.org/?probe=e579ce1757) | Jan 26, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [a23be61a14](https://linux-hardware.org/?probe=a23be61a14) | Jan 26, 2022 |
| Acer          | Aspire E5-574G              | Notebook    | [0dab243a9d](https://linux-hardware.org/?probe=0dab243a9d) | Jan 26, 2022 |
| Acer          | Aspire E5-574G              | Notebook    | [eedcd1e054](https://linux-hardware.org/?probe=eedcd1e054) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [3e03426280](https://linux-hardware.org/?probe=3e03426280) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [4a3755734e](https://linux-hardware.org/?probe=4a3755734e) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [4283316d8a](https://linux-hardware.org/?probe=4283316d8a) | Jan 26, 2022 |
| GALAX         | B365M G10b                  | Desktop     | [bd83b31919](https://linux-hardware.org/?probe=bd83b31919) | Jan 26, 2022 |
| Acer          | Aspire 4741                 | Notebook    | [bb695da9c9](https://linux-hardware.org/?probe=bb695da9c9) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [2c70e74055](https://linux-hardware.org/?probe=2c70e74055) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [6a692a4e11](https://linux-hardware.org/?probe=6a692a4e11) | Jan 26, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [57a443437c](https://linux-hardware.org/?probe=57a443437c) | Jan 26, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [52bad055e2](https://linux-hardware.org/?probe=52bad055e2) | Jan 26, 2022 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [934887404f](https://linux-hardware.org/?probe=934887404f) | Jan 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [8f09e74061](https://linux-hardware.org/?probe=8f09e74061) | Jan 26, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [75f4b47111](https://linux-hardware.org/?probe=75f4b47111) | Jan 26, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [e9f06efa7a](https://linux-hardware.org/?probe=e9f06efa7a) | Jan 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [041c78217d](https://linux-hardware.org/?probe=041c78217d) | Jan 26, 2022 |
| Sony          | SVS13125PBB                 | Notebook    | [ad2c655a36](https://linux-hardware.org/?probe=ad2c655a36) | Jan 25, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [1816cd81d3](https://linux-hardware.org/?probe=1816cd81d3) | Jan 25, 2022 |
| HP            | G42                         | Notebook    | [3d3f5f2d07](https://linux-hardware.org/?probe=3d3f5f2d07) | Jan 25, 2022 |
| Compal        | Unknown                     | Notebook    | [d1d374e6df](https://linux-hardware.org/?probe=d1d374e6df) | Jan 25, 2022 |
| Dell          | G3 3500                     | Notebook    | [57dd97e7c8](https://linux-hardware.org/?probe=57dd97e7c8) | Jan 25, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [df150bfd87](https://linux-hardware.org/?probe=df150bfd87) | Jan 25, 2022 |
| Itautec       | Infoway N8755               | Notebook    | [34a8012b59](https://linux-hardware.org/?probe=34a8012b59) | Jan 25, 2022 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [768e6d18dd](https://linux-hardware.org/?probe=768e6d18dd) | Jan 25, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [e0eb175311](https://linux-hardware.org/?probe=e0eb175311) | Jan 25, 2022 |
| Positivo      | Mobile                      | Notebook    | [9b53719e46](https://linux-hardware.org/?probe=9b53719e46) | Jan 25, 2022 |
| Dell          | 07N90W A02                  | Desktop     | [e31441d515](https://linux-hardware.org/?probe=e31441d515) | Jan 25, 2022 |
| Positivo      | Mobile                      | Notebook    | [b5e6002477](https://linux-hardware.org/?probe=b5e6002477) | Jan 25, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [184ff94e21](https://linux-hardware.org/?probe=184ff94e21) | Jan 25, 2022 |
| Dell          | Latitude 5420               | Notebook    | [3aad8f46c6](https://linux-hardware.org/?probe=3aad8f46c6) | Jan 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [032ee6d6c0](https://linux-hardware.org/?probe=032ee6d6c0) | Jan 24, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [9ea2007217](https://linux-hardware.org/?probe=9ea2007217) | Jan 24, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [dd33a742c9](https://linux-hardware.org/?probe=dd33a742c9) | Jan 24, 2022 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [8cf26e383a](https://linux-hardware.org/?probe=8cf26e383a) | Jan 24, 2022 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [d753eb21e8](https://linux-hardware.org/?probe=d753eb21e8) | Jan 24, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [9a38c32175](https://linux-hardware.org/?probe=9a38c32175) | Jan 24, 2022 |
| Intel         | H61                         | Desktop     | [a673457fc6](https://linux-hardware.org/?probe=a673457fc6) | Jan 23, 2022 |
| Intel         | H61                         | Desktop     | [aa29a62d0d](https://linux-hardware.org/?probe=aa29a62d0d) | Jan 23, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [8a843419b7](https://linux-hardware.org/?probe=8a843419b7) | Jan 23, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | Desktop     | [d9cbf7e314](https://linux-hardware.org/?probe=d9cbf7e314) | Jan 23, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9164aa7783](https://linux-hardware.org/?probe=9164aa7783) | Jan 23, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [215b5c3802](https://linux-hardware.org/?probe=215b5c3802) | Jan 23, 2022 |
| Positivo      | Q464C                       | Notebook    | [c5fa0e3561](https://linux-hardware.org/?probe=c5fa0e3561) | Jan 23, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [a74c254bb3](https://linux-hardware.org/?probe=a74c254bb3) | Jan 23, 2022 |
| ASUSTek       | TUF GAMING A520M-PLUS II    | Desktop     | [f950d7e322](https://linux-hardware.org/?probe=f950d7e322) | Jan 23, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [9597313782](https://linux-hardware.org/?probe=9597313782) | Jan 23, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [310b719b15](https://linux-hardware.org/?probe=310b719b15) | Jan 23, 2022 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [f6a03580c7](https://linux-hardware.org/?probe=f6a03580c7) | Jan 22, 2022 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [6ff572331c](https://linux-hardware.org/?probe=6ff572331c) | Jan 22, 2022 |
| Dell          | Vostro 1014                 | Notebook    | [16809ca9dd](https://linux-hardware.org/?probe=16809ca9dd) | Jan 22, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [5eb9b9e574](https://linux-hardware.org/?probe=5eb9b9e574) | Jan 22, 2022 |
| MSI           | Z77A-G45                    | Desktop     | [a397ea4233](https://linux-hardware.org/?probe=a397ea4233) | Jan 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [1c15058d91](https://linux-hardware.org/?probe=1c15058d91) | Jan 22, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5cb8ff854b](https://linux-hardware.org/?probe=5cb8ff854b) | Jan 21, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [44abfe4d29](https://linux-hardware.org/?probe=44abfe4d29) | Jan 21, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [4a721e7678](https://linux-hardware.org/?probe=4a721e7678) | Jan 21, 2022 |
| Dell          | Latitude 3420               | Notebook    | [2882c1a5d4](https://linux-hardware.org/?probe=2882c1a5d4) | Jan 21, 2022 |
| Sony          | SVS13125PBB                 | Notebook    | [6f5c214fe0](https://linux-hardware.org/?probe=6f5c214fe0) | Jan 21, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [e9a3d35409](https://linux-hardware.org/?probe=e9a3d35409) | Jan 21, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [b7b49a4994](https://linux-hardware.org/?probe=b7b49a4994) | Jan 21, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [164b959848](https://linux-hardware.org/?probe=164b959848) | Jan 21, 2022 |
| Philco        | 14I                         | Notebook    | [5006ca52e2](https://linux-hardware.org/?probe=5006ca52e2) | Jan 21, 2022 |
| Dell          | 019KMN A03                  | All in one  | [0b0f9a42cd](https://linux-hardware.org/?probe=0b0f9a42cd) | Jan 21, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [11de4173b1](https://linux-hardware.org/?probe=11de4173b1) | Jan 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [6d6c1565b7](https://linux-hardware.org/?probe=6d6c1565b7) | Jan 21, 2022 |
| Positivo      | ES10IS2                     | Notebook    | [c4980689e4](https://linux-hardware.org/?probe=c4980689e4) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f5e870f95b](https://linux-hardware.org/?probe=f5e870f95b) | Jan 21, 2022 |
| Sony          | VPCYB15AB                   | Notebook    | [1d7c8aa76a](https://linux-hardware.org/?probe=1d7c8aa76a) | Jan 21, 2022 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [56c6a8b68d](https://linux-hardware.org/?probe=56c6a8b68d) | Jan 21, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [03a8c77758](https://linux-hardware.org/?probe=03a8c77758) | Jan 20, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [df698a1427](https://linux-hardware.org/?probe=df698a1427) | Jan 20, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [1ab15ca104](https://linux-hardware.org/?probe=1ab15ca104) | Jan 20, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [c1b18abd63](https://linux-hardware.org/?probe=c1b18abd63) | Jan 20, 2022 |
| Lenovo        | B490 37722QP                | Notebook    | [6b32b6b8ef](https://linux-hardware.org/?probe=6b32b6b8ef) | Jan 20, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [14d9303d1d](https://linux-hardware.org/?probe=14d9303d1d) | Jan 20, 2022 |
| Samsung       | 930QDB                      | Convertible | [e498435120](https://linux-hardware.org/?probe=e498435120) | Jan 20, 2022 |
| Multilaser    | UB32X                       | Notebook    | [bd6f4152df](https://linux-hardware.org/?probe=bd6f4152df) | Jan 20, 2022 |
| Toshiba       | STI 014348                  | Desktop     | [91c7d3cbf1](https://linux-hardware.org/?probe=91c7d3cbf1) | Jan 20, 2022 |
| Dell          | Latitude E6330              | Notebook    | [c7b076f945](https://linux-hardware.org/?probe=c7b076f945) | Jan 20, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [f6598e8ab2](https://linux-hardware.org/?probe=f6598e8ab2) | Jan 20, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [d6927e8d81](https://linux-hardware.org/?probe=d6927e8d81) | Jan 20, 2022 |
| MSI           | H61M-P31                    | Desktop     | [495cb0d09b](https://linux-hardware.org/?probe=495cb0d09b) | Jan 20, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [6a311bab4a](https://linux-hardware.org/?probe=6a311bab4a) | Jan 19, 2022 |
| Positivo      | H14BU08                     | Notebook    | [8fb0d7e730](https://linux-hardware.org/?probe=8fb0d7e730) | Jan 19, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [0779d5bf00](https://linux-hardware.org/?probe=0779d5bf00) | Jan 19, 2022 |
| Dell          | 0KV62T A02                  | Desktop     | [f315491f5a](https://linux-hardware.org/?probe=f315491f5a) | Jan 19, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [fbcf7fffa8](https://linux-hardware.org/?probe=fbcf7fffa8) | Jan 19, 2022 |
| Samsung       | 550XDA                      | Notebook    | [cf44d057a0](https://linux-hardware.org/?probe=cf44d057a0) | Jan 19, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [11d9077e60](https://linux-hardware.org/?probe=11d9077e60) | Jan 19, 2022 |
| Samsung       | 930QDB                      | Convertible | [0ed7b7e65d](https://linux-hardware.org/?probe=0ed7b7e65d) | Jan 19, 2022 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [0fe0867d33](https://linux-hardware.org/?probe=0fe0867d33) | Jan 18, 2022 |
| Lenovo        | B490 37722QP                | Notebook    | [3113fb2078](https://linux-hardware.org/?probe=3113fb2078) | Jan 18, 2022 |
| ASUSTek       | N46VM                       | Notebook    | [0a88f88571](https://linux-hardware.org/?probe=0a88f88571) | Jan 18, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [b6d4b36704](https://linux-hardware.org/?probe=b6d4b36704) | Jan 18, 2022 |
| Positivo      | S14SL01                     | Notebook    | [01a64fab08](https://linux-hardware.org/?probe=01a64fab08) | Jan 18, 2022 |
| ASUSTek       | N46VM                       | Notebook    | [4d85d5ff13](https://linux-hardware.org/?probe=4d85d5ff13) | Jan 18, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [839a67f960](https://linux-hardware.org/?probe=839a67f960) | Jan 18, 2022 |
| HP            | 1489                        | All in one  | [f321eccadc](https://linux-hardware.org/?probe=f321eccadc) | Jan 18, 2022 |
| Positivo      | Mobile                      | Notebook    | [5f360ec080](https://linux-hardware.org/?probe=5f360ec080) | Jan 18, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [719d452709](https://linux-hardware.org/?probe=719d452709) | Jan 18, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [1f699a9a4d](https://linux-hardware.org/?probe=1f699a9a4d) | Jan 17, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [88d5bd947a](https://linux-hardware.org/?probe=88d5bd947a) | Jan 17, 2022 |
| HP            | 2B2F MVB,A                  | All in one  | [f6f22d94e8](https://linux-hardware.org/?probe=f6f22d94e8) | Jan 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [92d72ff4a1](https://linux-hardware.org/?probe=92d72ff4a1) | Jan 17, 2022 |
| LG Electro... | U460-G.BK51P1               | Notebook    | [de3d27183a](https://linux-hardware.org/?probe=de3d27183a) | Jan 17, 2022 |
| Unknown       | X79                         | Desktop     | [b3d66e7462](https://linux-hardware.org/?probe=b3d66e7462) | Jan 17, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [9bad24f3d9](https://linux-hardware.org/?probe=9bad24f3d9) | Jan 17, 2022 |
| Compal        | NBLBX                       | Notebook    | [87344a7bf7](https://linux-hardware.org/?probe=87344a7bf7) | Jan 16, 2022 |
| Toshiba       | STI 010433                  | Desktop     | [55f81b7b7c](https://linux-hardware.org/?probe=55f81b7b7c) | Jan 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [e68efc018a](https://linux-hardware.org/?probe=e68efc018a) | Jan 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [940b702411](https://linux-hardware.org/?probe=940b702411) | Jan 16, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [5145582e04](https://linux-hardware.org/?probe=5145582e04) | Jan 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7a5ba5f560](https://linux-hardware.org/?probe=7a5ba5f560) | Jan 16, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [07f1a949ab](https://linux-hardware.org/?probe=07f1a949ab) | Jan 16, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [b3a3cf01c7](https://linux-hardware.org/?probe=b3a3cf01c7) | Jan 16, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [4bcdec655f](https://linux-hardware.org/?probe=4bcdec655f) | Jan 16, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [30c9fe2f5f](https://linux-hardware.org/?probe=30c9fe2f5f) | Jan 16, 2022 |
| Lenovo        | ThinkPad T420 4180AG3       | Notebook    | [2c3cd27ad2](https://linux-hardware.org/?probe=2c3cd27ad2) | Jan 16, 2022 |
| Samsung       | 550XDA                      | Notebook    | [14e342e56d](https://linux-hardware.org/?probe=14e342e56d) | Jan 16, 2022 |
| Samsung       | 550XDA                      | Notebook    | [6c0b2cc195](https://linux-hardware.org/?probe=6c0b2cc195) | Jan 16, 2022 |
| HP            | 8266                        | Desktop     | [c2cbb29774](https://linux-hardware.org/?probe=c2cbb29774) | Jan 15, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [1e97f26a27](https://linux-hardware.org/?probe=1e97f26a27) | Jan 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [5ede90aefe](https://linux-hardware.org/?probe=5ede90aefe) | Jan 15, 2022 |
| AZW           | GK mini                     | Mini pc     | [7fb0a9b2e9](https://linux-hardware.org/?probe=7fb0a9b2e9) | Jan 15, 2022 |
| Dell          | Inspiron 1420               | Notebook    | [35d076d3df](https://linux-hardware.org/?probe=35d076d3df) | Jan 15, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [8e0e9f89bd](https://linux-hardware.org/?probe=8e0e9f89bd) | Jan 15, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [891e984a74](https://linux-hardware.org/?probe=891e984a74) | Jan 15, 2022 |
| Multilaser    | UB32X                       | Notebook    | [f65b37d922](https://linux-hardware.org/?probe=f65b37d922) | Jan 15, 2022 |
| Positivo      | C464C                       | Convertible | [cbc3e3ed97](https://linux-hardware.org/?probe=cbc3e3ed97) | Jan 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [a76b9e67bb](https://linux-hardware.org/?probe=a76b9e67bb) | Jan 14, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [daa65dc7ef](https://linux-hardware.org/?probe=daa65dc7ef) | Jan 14, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [eafa397038](https://linux-hardware.org/?probe=eafa397038) | Jan 14, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [c52da73717](https://linux-hardware.org/?probe=c52da73717) | Jan 14, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [3ea50d80ec](https://linux-hardware.org/?probe=3ea50d80ec) | Jan 14, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2d1fa4cb30](https://linux-hardware.org/?probe=2d1fa4cb30) | Jan 14, 2022 |
| LG Electro... | R580-G.BP21P1               | Notebook    | [925fe25a7c](https://linux-hardware.org/?probe=925fe25a7c) | Jan 13, 2022 |
| Unknown       | X99-GT                      | Desktop     | [4562aa0142](https://linux-hardware.org/?probe=4562aa0142) | Jan 13, 2022 |
| HP            | 240 G6 Notebook PC          | Notebook    | [792a79c2fb](https://linux-hardware.org/?probe=792a79c2fb) | Jan 13, 2022 |
| Dell          | Latitude 5420               | Notebook    | [ab13df4cd4](https://linux-hardware.org/?probe=ab13df4cd4) | Jan 13, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [d9ee3ea8d1](https://linux-hardware.org/?probe=d9ee3ea8d1) | Jan 13, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [311d594372](https://linux-hardware.org/?probe=311d594372) | Jan 13, 2022 |
| Lenovo        | G40-70 80GA                 | Notebook    | [6321546415](https://linux-hardware.org/?probe=6321546415) | Jan 12, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [f598674489](https://linux-hardware.org/?probe=f598674489) | Jan 12, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [2a29726d59](https://linux-hardware.org/?probe=2a29726d59) | Jan 12, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [b04bda9800](https://linux-hardware.org/?probe=b04bda9800) | Jan 12, 2022 |
| Positivo      | POS-MIG31AG                 | Desktop     | [bd893c6368](https://linux-hardware.org/?probe=bd893c6368) | Jan 12, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [b4c83278e2](https://linux-hardware.org/?probe=b4c83278e2) | Jan 12, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [acd1da8f35](https://linux-hardware.org/?probe=acd1da8f35) | Jan 12, 2022 |
| Compal        | NCL60/61                    | Notebook    | [3f71d0d088](https://linux-hardware.org/?probe=3f71d0d088) | Jan 12, 2022 |
| Positivo      | POS-PIH81DI                 | Desktop     | [0bbfacaaea](https://linux-hardware.org/?probe=0bbfacaaea) | Jan 11, 2022 |
| ASUSTek       | Z550SA                      | Notebook    | [322fa160ae](https://linux-hardware.org/?probe=322fa160ae) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [6b764029b7](https://linux-hardware.org/?probe=6b764029b7) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [60f264617e](https://linux-hardware.org/?probe=60f264617e) | Jan 11, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [7411a4cc5e](https://linux-hardware.org/?probe=7411a4cc5e) | Jan 11, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [5ed8f41517](https://linux-hardware.org/?probe=5ed8f41517) | Jan 11, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [f67eed490e](https://linux-hardware.org/?probe=f67eed490e) | Jan 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [34acf9099a](https://linux-hardware.org/?probe=34acf9099a) | Jan 11, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [52197b0dea](https://linux-hardware.org/?probe=52197b0dea) | Jan 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [76cb68e427](https://linux-hardware.org/?probe=76cb68e427) | Jan 11, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [12077557be](https://linux-hardware.org/?probe=12077557be) | Jan 11, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [73dbecedf2](https://linux-hardware.org/?probe=73dbecedf2) | Jan 11, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [20cc8ef2ea](https://linux-hardware.org/?probe=20cc8ef2ea) | Jan 11, 2022 |
| Dell          | Vostro 1520                 | Notebook    | [2278a225cd](https://linux-hardware.org/?probe=2278a225cd) | Jan 11, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [ea55ac1aab](https://linux-hardware.org/?probe=ea55ac1aab) | Jan 11, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [2a06c33573](https://linux-hardware.org/?probe=2a06c33573) | Jan 11, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [c9765c772f](https://linux-hardware.org/?probe=c9765c772f) | Jan 11, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [252df76aa8](https://linux-hardware.org/?probe=252df76aa8) | Jan 10, 2022 |
| Positivo      | N600                        | Notebook    | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [33159068d9](https://linux-hardware.org/?probe=33159068d9) | Jan 10, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [dfa3a6df3f](https://linux-hardware.org/?probe=dfa3a6df3f) | Jan 10, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [c7ec6cce32](https://linux-hardware.org/?probe=c7ec6cce32) | Jan 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [dcf0799dd1](https://linux-hardware.org/?probe=dcf0799dd1) | Jan 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [fb3838c0db](https://linux-hardware.org/?probe=fb3838c0db) | Jan 10, 2022 |
| Lenovo        | B490 37722LP                | Notebook    | [c36fa4c158](https://linux-hardware.org/?probe=c36fa4c158) | Jan 10, 2022 |
| Multilaser    | PC112                       | Convertible | [688f006263](https://linux-hardware.org/?probe=688f006263) | Jan 10, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [936bd6bf44](https://linux-hardware.org/?probe=936bd6bf44) | Jan 10, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [9fdbf19ebf](https://linux-hardware.org/?probe=9fdbf19ebf) | Jan 09, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [609662084d](https://linux-hardware.org/?probe=609662084d) | Jan 09, 2022 |
| ASRock        | G31M-S                      | Desktop     | [1006244941](https://linux-hardware.org/?probe=1006244941) | Jan 09, 2022 |
| Dell          | 05CNYF A01                  | Desktop     | [c197ba435d](https://linux-hardware.org/?probe=c197ba435d) | Jan 09, 2022 |
| Dell          | Inspiron 7560               | Notebook    | [18daf15e61](https://linux-hardware.org/?probe=18daf15e61) | Jan 09, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [9fefdda545](https://linux-hardware.org/?probe=9fefdda545) | Jan 09, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [6b6c84515a](https://linux-hardware.org/?probe=6b6c84515a) | Jan 09, 2022 |
| Dell          | Latitude E5400              | Notebook    | [4f72d3dae0](https://linux-hardware.org/?probe=4f72d3dae0) | Jan 09, 2022 |
| Phitronics    | P33G                        | Desktop     | [d21245c1ea](https://linux-hardware.org/?probe=d21245c1ea) | Jan 09, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [b2e4fe050c](https://linux-hardware.org/?probe=b2e4fe050c) | Jan 09, 2022 |
| HP            | ProBook 6450b               | Notebook    | [cf1a585619](https://linux-hardware.org/?probe=cf1a585619) | Jan 09, 2022 |
| Dell          | Inspiron 5557               | Notebook    | [fb29216e68](https://linux-hardware.org/?probe=fb29216e68) | Jan 09, 2022 |
| ASRock        | G31M-S                      | Desktop     | [b33a983889](https://linux-hardware.org/?probe=b33a983889) | Jan 08, 2022 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [5602ba99c2](https://linux-hardware.org/?probe=5602ba99c2) | Jan 08, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [ceb31a41b4](https://linux-hardware.org/?probe=ceb31a41b4) | Jan 08, 2022 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [82aa762a97](https://linux-hardware.org/?probe=82aa762a97) | Jan 08, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [feff8775da](https://linux-hardware.org/?probe=feff8775da) | Jan 08, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [4d2a0c8d41](https://linux-hardware.org/?probe=4d2a0c8d41) | Jan 08, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [91c54ce00a](https://linux-hardware.org/?probe=91c54ce00a) | Jan 08, 2022 |
| Dell          | Inspiron 7560               | Notebook    | [a17707c45d](https://linux-hardware.org/?probe=a17707c45d) | Jan 08, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [86efdd34c0](https://linux-hardware.org/?probe=86efdd34c0) | Jan 08, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [6c9118e320](https://linux-hardware.org/?probe=6c9118e320) | Jan 08, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [103f52795a](https://linux-hardware.org/?probe=103f52795a) | Jan 08, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [c87cec55bd](https://linux-hardware.org/?probe=c87cec55bd) | Jan 07, 2022 |
| HP            | Compaq 6910p (GX316UC#AB... | Notebook    | [0ffa23c15e](https://linux-hardware.org/?probe=0ffa23c15e) | Jan 07, 2022 |
| Intel         | H61                         | Desktop     | [aceeadad0e](https://linux-hardware.org/?probe=aceeadad0e) | Jan 07, 2022 |
| HP            | 240 G6 Notebook PC          | Notebook    | [079d91dda3](https://linux-hardware.org/?probe=079d91dda3) | Jan 07, 2022 |
| MSI           | MS-B0961                    | All in one  | [3136ced425](https://linux-hardware.org/?probe=3136ced425) | Jan 07, 2022 |
| Dell          | Inspiron One 2320           | All in one  | [6008fda2ad](https://linux-hardware.org/?probe=6008fda2ad) | Jan 07, 2022 |
| Dell          | Latitude 5420               | Notebook    | [ab3973e74b](https://linux-hardware.org/?probe=ab3973e74b) | Jan 07, 2022 |
| Dell          | Latitude 5420               | Notebook    | [517adf10a8](https://linux-hardware.org/?probe=517adf10a8) | Jan 06, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [d22f32f071](https://linux-hardware.org/?probe=d22f32f071) | Jan 06, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [bb252bbd37](https://linux-hardware.org/?probe=bb252bbd37) | Jan 06, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [610072e219](https://linux-hardware.org/?probe=610072e219) | Jan 06, 2022 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [2cb2bbbfc6](https://linux-hardware.org/?probe=2cb2bbbfc6) | Jan 06, 2022 |
| Positivo      | POS-PQ45AU                  | Desktop     | [9293dfdb4d](https://linux-hardware.org/?probe=9293dfdb4d) | Jan 06, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [179cf54d82](https://linux-hardware.org/?probe=179cf54d82) | Jan 06, 2022 |
| AMD           | A88K                        | Desktop     | [9c664dd81f](https://linux-hardware.org/?probe=9c664dd81f) | Jan 05, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [5222b66726](https://linux-hardware.org/?probe=5222b66726) | Jan 05, 2022 |
| Samsung       | 550XDA                      | Notebook    | [1bdf544285](https://linux-hardware.org/?probe=1bdf544285) | Jan 05, 2022 |
| Lenovo        | Y720-15IKB 81CQ             | Notebook    | [13cbd87036](https://linux-hardware.org/?probe=13cbd87036) | Jan 05, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [8355b9f07c](https://linux-hardware.org/?probe=8355b9f07c) | Jan 05, 2022 |
| ASUSTek       | B85-A R2.0                  | Desktop     | [de3800071c](https://linux-hardware.org/?probe=de3800071c) | Jan 05, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [75a92c6550](https://linux-hardware.org/?probe=75a92c6550) | Jan 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bcc46e9fcb](https://linux-hardware.org/?probe=bcc46e9fcb) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B460M-PLUS       | Desktop     | [1ad802006b](https://linux-hardware.org/?probe=1ad802006b) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B460M-PLUS       | Desktop     | [32d0fda197](https://linux-hardware.org/?probe=32d0fda197) | Jan 05, 2022 |
| HP            | ProBook 4430s               | Notebook    | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| Dell          | Inspiron One 2320           | All in one  | [5ad8eee194](https://linux-hardware.org/?probe=5ad8eee194) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [b6c0836e89](https://linux-hardware.org/?probe=b6c0836e89) | Jan 04, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [d15eb36c4f](https://linux-hardware.org/?probe=d15eb36c4f) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [61978f9418](https://linux-hardware.org/?probe=61978f9418) | Jan 04, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [c66b09770b](https://linux-hardware.org/?probe=c66b09770b) | Jan 04, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [e41a208158](https://linux-hardware.org/?probe=e41a208158) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | Notebook    | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Positivo      | POS-PIH81DI                 | Desktop     | [c2f06752f5](https://linux-hardware.org/?probe=c2f06752f5) | Jan 04, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [c8aafbbc8d](https://linux-hardware.org/?probe=c8aafbbc8d) | Jan 04, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [3cae008c9d](https://linux-hardware.org/?probe=3cae008c9d) | Jan 04, 2022 |
| Dell          | 0KWVT8 A02                  | Desktop     | [fe5ca696c8](https://linux-hardware.org/?probe=fe5ca696c8) | Jan 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [9d4bddea4d](https://linux-hardware.org/?probe=9d4bddea4d) | Jan 03, 2022 |
| Intel         | H55                         | Desktop     | [aa361d5399](https://linux-hardware.org/?probe=aa361d5399) | Jan 03, 2022 |
| HP            | 1495                        | Desktop     | [6298747a55](https://linux-hardware.org/?probe=6298747a55) | Jan 03, 2022 |
| Samsung       | 750XBE/730XBE               | Notebook    | [5608016bcb](https://linux-hardware.org/?probe=5608016bcb) | Jan 03, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [bb57e8f3b9](https://linux-hardware.org/?probe=bb57e8f3b9) | Jan 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [b0877f3054](https://linux-hardware.org/?probe=b0877f3054) | Jan 03, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [8bec3c5b12](https://linux-hardware.org/?probe=8bec3c5b12) | Jan 03, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [282277fa58](https://linux-hardware.org/?probe=282277fa58) | Jan 02, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [b4049969e7](https://linux-hardware.org/?probe=b4049969e7) | Jan 02, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [47887a95e0](https://linux-hardware.org/?probe=47887a95e0) | Jan 02, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [c5e569b5c7](https://linux-hardware.org/?probe=c5e569b5c7) | Jan 02, 2022 |
| Positivo      | Q464C                       | Notebook    | [6b04ee9d48](https://linux-hardware.org/?probe=6b04ee9d48) | Jan 02, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [4b12ee93be](https://linux-hardware.org/?probe=4b12ee93be) | Jan 02, 2022 |
| HP            | Compaq Presario CQ43        | Notebook    | [af69f165f8](https://linux-hardware.org/?probe=af69f165f8) | Jan 02, 2022 |
| HP            | Compaq Presario CQ43        | Notebook    | [6e0b499d88](https://linux-hardware.org/?probe=6e0b499d88) | Jan 02, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [3d96bb9bc2](https://linux-hardware.org/?probe=3d96bb9bc2) | Jan 02, 2022 |
| Dell          | Inspiron 1428               | Notebook    | [29a20cfbd9](https://linux-hardware.org/?probe=29a20cfbd9) | Jan 02, 2022 |
| ASRock        | B75M-DGS R2.0               | Desktop     | [6a0f1a65c1](https://linux-hardware.org/?probe=6a0f1a65c1) | Jan 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [d70ae1191d](https://linux-hardware.org/?probe=d70ae1191d) | Jan 02, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [355b4fcf61](https://linux-hardware.org/?probe=355b4fcf61) | Jan 02, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [ffd9717d80](https://linux-hardware.org/?probe=ffd9717d80) | Jan 02, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [be76922082](https://linux-hardware.org/?probe=be76922082) | Jan 02, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [f6393f5788](https://linux-hardware.org/?probe=f6393f5788) | Jan 01, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [e0415c1970](https://linux-hardware.org/?probe=e0415c1970) | Jan 01, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d7774870db](https://linux-hardware.org/?probe=d7774870db) | Jan 01, 2022 |
| Dell          | Inspiron 5480               | Notebook    | [cf92148eac](https://linux-hardware.org/?probe=cf92148eac) | Jan 01, 2022 |
| HP            | G60                         | Notebook    | [08350a2b75](https://linux-hardware.org/?probe=08350a2b75) | Jan 01, 2022 |
| Toshiba       | AS 1301                     | Notebook    | [8617f80de9](https://linux-hardware.org/?probe=8617f80de9) | Jan 01, 2022 |
| Dell          | Inspiron 7560               | Notebook    | [1521c2f202](https://linux-hardware.org/?probe=1521c2f202) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [74de092c5f](https://linux-hardware.org/?probe=74de092c5f) | Jan 01, 2022 |
| Positivo      | SW6H                        | Notebook    | [a7566e6187](https://linux-hardware.org/?probe=a7566e6187) | Jan 01, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [3ebf180dc4](https://linux-hardware.org/?probe=3ebf180dc4) | Jan 01, 2022 |
| Dell          | Inspiron 7560               | Notebook    | [1b7b408372](https://linux-hardware.org/?probe=1b7b408372) | Dec 31, 2021 |
| Dell          | Inspiron 7560               | Notebook    | [18fb6b8c3d](https://linux-hardware.org/?probe=18fb6b8c3d) | Dec 31, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [0a7a64e88d](https://linux-hardware.org/?probe=0a7a64e88d) | Dec 31, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [0bfa74fa9f](https://linux-hardware.org/?probe=0bfa74fa9f) | Dec 31, 2021 |
| Dell          | Latitude E6230              | Notebook    | [fd4e9c6d43](https://linux-hardware.org/?probe=fd4e9c6d43) | Dec 31, 2021 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [2ddd424f94](https://linux-hardware.org/?probe=2ddd424f94) | Dec 31, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [65aab50b2c](https://linux-hardware.org/?probe=65aab50b2c) | Dec 31, 2021 |
| Dell          | Inspiron 5458on             | Notebook    | [265cd0c910](https://linux-hardware.org/?probe=265cd0c910) | Dec 31, 2021 |
| Intel         | H61                         | Desktop     | [9743103ac6](https://linux-hardware.org/?probe=9743103ac6) | Dec 31, 2021 |
| Samsung       | 270E5G/270E5U               | Notebook    | [0f92fab3db](https://linux-hardware.org/?probe=0f92fab3db) | Dec 31, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [d7b37cd814](https://linux-hardware.org/?probe=d7b37cd814) | Dec 31, 2021 |
| Dell          | Inspiron 5447               | Notebook    | [0012b60e04](https://linux-hardware.org/?probe=0012b60e04) | Dec 31, 2021 |
| Dell          | Inspiron 5447               | Notebook    | [ee494391f7](https://linux-hardware.org/?probe=ee494391f7) | Dec 31, 2021 |
| Samsung       | 550XDA                      | Notebook    | [8f01f7ab00](https://linux-hardware.org/?probe=8f01f7ab00) | Dec 30, 2021 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [f73a2b3505](https://linux-hardware.org/?probe=f73a2b3505) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [17548c6fc7](https://linux-hardware.org/?probe=17548c6fc7) | Dec 30, 2021 |
| HP            | Unknown                     | Notebook    | [e1eb3d8838](https://linux-hardware.org/?probe=e1eb3d8838) | Dec 30, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | Notebook    | [c076e4939e](https://linux-hardware.org/?probe=c076e4939e) | Dec 30, 2021 |
| Samsung       | 930QDB                      | Convertible | [10ba767052](https://linux-hardware.org/?probe=10ba767052) | Dec 30, 2021 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [e4d3f29412](https://linux-hardware.org/?probe=e4d3f29412) | Dec 30, 2021 |
| Intel         | H61                         | Desktop     | [e2b49aa759](https://linux-hardware.org/?probe=e2b49aa759) | Dec 30, 2021 |
| Dell          | 01XK1W A00                  | Desktop     | [5407438c6e](https://linux-hardware.org/?probe=5407438c6e) | Dec 30, 2021 |
| Dell          | 01XK1W A00                  | Desktop     | [0b80d9da29](https://linux-hardware.org/?probe=0b80d9da29) | Dec 30, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [deb4e10a41](https://linux-hardware.org/?probe=deb4e10a41) | Dec 29, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3e4ab4e082](https://linux-hardware.org/?probe=3e4ab4e082) | Dec 29, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [b699cbc873](https://linux-hardware.org/?probe=b699cbc873) | Dec 29, 2021 |
| Positivo      | POS-EINM70CS POSITIVO       | Desktop     | [a4a22cd651](https://linux-hardware.org/?probe=a4a22cd651) | Dec 29, 2021 |
| Pegatron      | IPMIP-GS                    | Desktop     | [0fe3445de4](https://linux-hardware.org/?probe=0fe3445de4) | Dec 29, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [03802bfda7](https://linux-hardware.org/?probe=03802bfda7) | Dec 29, 2021 |
| Dell          | Latitude 5420               | Notebook    | [42e63fd746](https://linux-hardware.org/?probe=42e63fd746) | Dec 29, 2021 |
| Dell          | Latitude 5420               | Notebook    | [ae4bf2544b](https://linux-hardware.org/?probe=ae4bf2544b) | Dec 29, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [0ba9ee7a74](https://linux-hardware.org/?probe=0ba9ee7a74) | Dec 29, 2021 |
| Dell          | Inspiron 5490               | Notebook    | [863f8366a7](https://linux-hardware.org/?probe=863f8366a7) | Dec 29, 2021 |
| Dell          | Inspiron 5490               | Notebook    | [6214557268](https://linux-hardware.org/?probe=6214557268) | Dec 29, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [93ddeaab25](https://linux-hardware.org/?probe=93ddeaab25) | Dec 29, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [18a966b290](https://linux-hardware.org/?probe=18a966b290) | Dec 29, 2021 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [7c247b0c9f](https://linux-hardware.org/?probe=7c247b0c9f) | Dec 29, 2021 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [9a7cac43e9](https://linux-hardware.org/?probe=9a7cac43e9) | Dec 28, 2021 |
| Acer          | Aspire A315-54K             | Notebook    | [b662c9c046](https://linux-hardware.org/?probe=b662c9c046) | Dec 28, 2021 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [5cff8b82d5](https://linux-hardware.org/?probe=5cff8b82d5) | Dec 28, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [cdb6614961](https://linux-hardware.org/?probe=cdb6614961) | Dec 28, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [95b7ad1e07](https://linux-hardware.org/?probe=95b7ad1e07) | Dec 28, 2021 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [aa4ac7f9c8](https://linux-hardware.org/?probe=aa4ac7f9c8) | Dec 28, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [af582ea780](https://linux-hardware.org/?probe=af582ea780) | Dec 28, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [86223c6744](https://linux-hardware.org/?probe=86223c6744) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [be839fd24d](https://linux-hardware.org/?probe=be839fd24d) | Dec 28, 2021 |
| Dell          | Inspiron 7560               | Notebook    | [5ad630b5e5](https://linux-hardware.org/?probe=5ad630b5e5) | Dec 28, 2021 |
| Positivo      | POS-PARS760GCD POSITIVO     | Desktop     | [4a81b51d58](https://linux-hardware.org/?probe=4a81b51d58) | Dec 28, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [7ae1568f36](https://linux-hardware.org/?probe=7ae1568f36) | Dec 27, 2021 |
| Dell          | Inspiron 5537               | Notebook    | [f4878864ec](https://linux-hardware.org/?probe=f4878864ec) | Dec 27, 2021 |
| Avell High... | A70 MOB                     | Notebook    | [dac7555e81](https://linux-hardware.org/?probe=dac7555e81) | Dec 27, 2021 |
| Wistron       | ProLiant ML110 G5           | Server      | [c3bd5cbae8](https://linux-hardware.org/?probe=c3bd5cbae8) | Dec 27, 2021 |
| ASUSTek       | X45U                        | Notebook    | [55d2da3313](https://linux-hardware.org/?probe=55d2da3313) | Dec 27, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [eaee471d35](https://linux-hardware.org/?probe=eaee471d35) | Dec 27, 2021 |
| Wistron       | ProLiant ML110 G5           | Server      | [8526295a2f](https://linux-hardware.org/?probe=8526295a2f) | Dec 27, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d0059fcd5a](https://linux-hardware.org/?probe=d0059fcd5a) | Dec 27, 2021 |
| Sony          | SVT11125CBS                 | Notebook    | [961f242a60](https://linux-hardware.org/?probe=961f242a60) | Dec 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [bc09325848](https://linux-hardware.org/?probe=bc09325848) | Dec 27, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [8262ba8f4a](https://linux-hardware.org/?probe=8262ba8f4a) | Dec 27, 2021 |
| ASUSTek       | P8H61-M LE/BR               | Desktop     | [01c5633412](https://linux-hardware.org/?probe=01c5633412) | Dec 27, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [5e78de369f](https://linux-hardware.org/?probe=5e78de369f) | Dec 27, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [8cf9037edf](https://linux-hardware.org/?probe=8cf9037edf) | Dec 27, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [e3c3ae36a2](https://linux-hardware.org/?probe=e3c3ae36a2) | Dec 27, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [adcf14bf31](https://linux-hardware.org/?probe=adcf14bf31) | Dec 27, 2021 |
| Positivo      | V142N_4G                    | Notebook    | [fb167e6518](https://linux-hardware.org/?probe=fb167e6518) | Dec 27, 2021 |
| OEM           | I38II                       | Notebook    | [52bc5190dd](https://linux-hardware.org/?probe=52bc5190dd) | Dec 27, 2021 |
| Positivo      | POS-MIH61CF                 | Desktop     | [a8fd13db4c](https://linux-hardware.org/?probe=a8fd13db4c) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [d0bf339bdf](https://linux-hardware.org/?probe=d0bf339bdf) | Dec 26, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [135d34c579](https://linux-hardware.org/?probe=135d34c579) | Dec 26, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [84b16824bd](https://linux-hardware.org/?probe=84b16824bd) | Dec 26, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [9f25d765b2](https://linux-hardware.org/?probe=9f25d765b2) | Dec 26, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [661d4c5b99](https://linux-hardware.org/?probe=661d4c5b99) | Dec 26, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [42837842b9](https://linux-hardware.org/?probe=42837842b9) | Dec 26, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9a6b436bcb](https://linux-hardware.org/?probe=9a6b436bcb) | Dec 26, 2021 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [28aad352f5](https://linux-hardware.org/?probe=28aad352f5) | Dec 26, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [06de3a03ad](https://linux-hardware.org/?probe=06de3a03ad) | Dec 26, 2021 |
| HP            | Compaq Presario CQ43        | Notebook    | [19fc1f14de](https://linux-hardware.org/?probe=19fc1f14de) | Dec 26, 2021 |
| Acer          | Aspire M5-481T              | Notebook    | [2515a869a5](https://linux-hardware.org/?probe=2515a869a5) | Dec 26, 2021 |
| Dell          | 0W1MP6 A07                  | Server      | [d95ea030ff](https://linux-hardware.org/?probe=d95ea030ff) | Dec 26, 2021 |
| Acer          | Aspire M5-481T              | Notebook    | [1ef9b940b2](https://linux-hardware.org/?probe=1ef9b940b2) | Dec 26, 2021 |
| Dell          | 0W1MP6 A07                  | Server      | [295b978781](https://linux-hardware.org/?probe=295b978781) | Dec 26, 2021 |
| MSI           | H97M-G43                    | Desktop     | [9befbf0087](https://linux-hardware.org/?probe=9befbf0087) | Dec 25, 2021 |
| Acer          | Aspire A315-42G             | Notebook    | [453f75585c](https://linux-hardware.org/?probe=453f75585c) | Dec 25, 2021 |
| Biostar       | G31-M7 TE                   | Desktop     | [abb80ccd85](https://linux-hardware.org/?probe=abb80ccd85) | Dec 25, 2021 |
| ASUSTek       | M2N-E                       | Desktop     | [3a08145f4b](https://linux-hardware.org/?probe=3a08145f4b) | Dec 24, 2021 |
| Dell          | 057XR4 A00                  | All in one  | [c266e20519](https://linux-hardware.org/?probe=c266e20519) | Dec 24, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [74de11b348](https://linux-hardware.org/?probe=74de11b348) | Dec 24, 2021 |
| Positivo      | POS-MIH61CF                 | Desktop     | [f10e90bd72](https://linux-hardware.org/?probe=f10e90bd72) | Dec 24, 2021 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [d76ed454c1](https://linux-hardware.org/?probe=d76ed454c1) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| 16216-BM-2... | Z97M GAMING 14655-BV-171... | Desktop     | [c432df16c9](https://linux-hardware.org/?probe=c432df16c9) | Dec 24, 2021 |
| Lenovo        | V470 439627U                | Notebook    | [7c44d560dc](https://linux-hardware.org/?probe=7c44d560dc) | Dec 24, 2021 |
| HP            | Compaq Presario CQ43        | Notebook    | [8a9469ae9b](https://linux-hardware.org/?probe=8a9469ae9b) | Dec 24, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [6eec25d058](https://linux-hardware.org/?probe=6eec25d058) | Dec 24, 2021 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [f1e535b5ba](https://linux-hardware.org/?probe=f1e535b5ba) | Dec 24, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [bef8e4334a](https://linux-hardware.org/?probe=bef8e4334a) | Dec 23, 2021 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [f6beaa3bcc](https://linux-hardware.org/?probe=f6beaa3bcc) | Dec 23, 2021 |
| Megaware      | G41T-M7                     | Desktop     | [0962b3b7b4](https://linux-hardware.org/?probe=0962b3b7b4) | Dec 23, 2021 |
| Dell          | System Vostro 3450          | Notebook    | [9499015c46](https://linux-hardware.org/?probe=9499015c46) | Dec 23, 2021 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [5afa9a7018](https://linux-hardware.org/?probe=5afa9a7018) | Dec 23, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [0ac81fb221](https://linux-hardware.org/?probe=0ac81fb221) | Dec 23, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [3a101db74b](https://linux-hardware.org/?probe=3a101db74b) | Dec 23, 2021 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [c1c7140811](https://linux-hardware.org/?probe=c1c7140811) | Dec 23, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [40e8ac4ece](https://linux-hardware.org/?probe=40e8ac4ece) | Dec 23, 2021 |
| Lenovo        | V470 439627U                | Notebook    | [71387b4f47](https://linux-hardware.org/?probe=71387b4f47) | Dec 23, 2021 |
| Positivo      | CHT14B                      | Notebook    | [ae9f7801cf](https://linux-hardware.org/?probe=ae9f7801cf) | Dec 23, 2021 |
| Positivo      | CHT14B                      | Notebook    | [3efc353498](https://linux-hardware.org/?probe=3efc353498) | Dec 23, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [197e469eb4](https://linux-hardware.org/?probe=197e469eb4) | Dec 23, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3c497749b6](https://linux-hardware.org/?probe=3c497749b6) | Dec 23, 2021 |
| Dell          | Vostro 3480                 | Notebook    | [99e4c4339b](https://linux-hardware.org/?probe=99e4c4339b) | Dec 22, 2021 |
| Dell          | Inspiron 5447               | Notebook    | [83331a9c7c](https://linux-hardware.org/?probe=83331a9c7c) | Dec 22, 2021 |
| Lenovo        | ThinkPad E14 20RBS3LV00     | Notebook    | [c3ff7fe60b](https://linux-hardware.org/?probe=c3ff7fe60b) | Dec 22, 2021 |
| Lenovo        | ThinkPad E14 20RBS3LV00     | Notebook    | [4a65927165](https://linux-hardware.org/?probe=4a65927165) | Dec 22, 2021 |
| Dell          | Inspiron 5547               | Notebook    | [605e3df140](https://linux-hardware.org/?probe=605e3df140) | Dec 22, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [ac5f615cbd](https://linux-hardware.org/?probe=ac5f615cbd) | Dec 22, 2021 |
| ASRock        | AM1B-MH                     | Desktop     | [7f05b603cc](https://linux-hardware.org/?probe=7f05b603cc) | Dec 22, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [146165d8d1](https://linux-hardware.org/?probe=146165d8d1) | Dec 22, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [c44547da71](https://linux-hardware.org/?probe=c44547da71) | Dec 22, 2021 |
| OEM           | B14HM21                     | Notebook    | [8b8a787f86](https://linux-hardware.org/?probe=8b8a787f86) | Dec 22, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [842eae5b1d](https://linux-hardware.org/?probe=842eae5b1d) | Dec 22, 2021 |
| Biostar       | A68N-5600E                  | Desktop     | [9ed7856f41](https://linux-hardware.org/?probe=9ed7856f41) | Dec 22, 2021 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [86396d9983](https://linux-hardware.org/?probe=86396d9983) | Dec 22, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [985fc37716](https://linux-hardware.org/?probe=985fc37716) | Dec 22, 2021 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [fb84715d28](https://linux-hardware.org/?probe=fb84715d28) | Dec 22, 2021 |
| Gigabyte      | H270M-Gaming3-CF            | Desktop     | [bf6a8005bc](https://linux-hardware.org/?probe=bf6a8005bc) | Dec 22, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [6c55617f07](https://linux-hardware.org/?probe=6c55617f07) | Dec 22, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [351cfa4f12](https://linux-hardware.org/?probe=351cfa4f12) | Dec 22, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [5994dbd498](https://linux-hardware.org/?probe=5994dbd498) | Dec 21, 2021 |
| HP            | Compaq Mini 311-1100        | Notebook    | [d1aaa6b464](https://linux-hardware.org/?probe=d1aaa6b464) | Dec 21, 2021 |
| ASUSTek       | X55U                        | Notebook    | [6c10bfc423](https://linux-hardware.org/?probe=6c10bfc423) | Dec 21, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [5f47284626](https://linux-hardware.org/?probe=5f47284626) | Dec 21, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [6c17de2a03](https://linux-hardware.org/?probe=6c17de2a03) | Dec 21, 2021 |
| Apple         | MacBookPro4,1               | Notebook    | [855e5ba65d](https://linux-hardware.org/?probe=855e5ba65d) | Dec 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9775119696](https://linux-hardware.org/?probe=9775119696) | Dec 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [148afb76d9](https://linux-hardware.org/?probe=148afb76d9) | Dec 21, 2021 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [4ef2bfbf6d](https://linux-hardware.org/?probe=4ef2bfbf6d) | Dec 21, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [b2108dd133](https://linux-hardware.org/?probe=b2108dd133) | Dec 21, 2021 |
| HP            | G42                         | Notebook    | [9253a8caf5](https://linux-hardware.org/?probe=9253a8caf5) | Dec 20, 2021 |
| ASUSTek       | P8H61-M LE/BR               | Desktop     | [133dc63868](https://linux-hardware.org/?probe=133dc63868) | Dec 20, 2021 |
| Itautec       | AL 2022 AL 2022 Padrao 0... | All in one  | [9defc41ed2](https://linux-hardware.org/?probe=9defc41ed2) | Dec 20, 2021 |
| Gigabyte      | H55M-S2HP                   | Desktop     | [24bb32f99c](https://linux-hardware.org/?probe=24bb32f99c) | Dec 20, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [32b9121efc](https://linux-hardware.org/?probe=32b9121efc) | Dec 20, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [44d2768522](https://linux-hardware.org/?probe=44d2768522) | Dec 20, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| Intel         | B75                         | Desktop     | [9178fa9053](https://linux-hardware.org/?probe=9178fa9053) | Dec 19, 2021 |
| Digibras      | NH4CU03                     | Notebook    | [517425552d](https://linux-hardware.org/?probe=517425552d) | Dec 19, 2021 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [a15986fe04](https://linux-hardware.org/?probe=a15986fe04) | Dec 19, 2021 |
| Dell          | Inspiron N4050              | Notebook    | [069b0b5d94](https://linux-hardware.org/?probe=069b0b5d94) | Dec 19, 2021 |
| Acer          | Unknown                     | Notebook    | [21b566f81d](https://linux-hardware.org/?probe=21b566f81d) | Dec 19, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [fbd0755545](https://linux-hardware.org/?probe=fbd0755545) | Dec 19, 2021 |
| MSI           | GT80 2QC                    | Notebook    | [68b70c6ff9](https://linux-hardware.org/?probe=68b70c6ff9) | Dec 19, 2021 |
| HP            | Compaq Presario CQ43        | Notebook    | [95d53051a2](https://linux-hardware.org/?probe=95d53051a2) | Dec 19, 2021 |
| HP            | Compaq Presario CQ43        | Notebook    | [7841090d93](https://linux-hardware.org/?probe=7841090d93) | Dec 18, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [44b1bbbb9c](https://linux-hardware.org/?probe=44b1bbbb9c) | Dec 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [de9ccde374](https://linux-hardware.org/?probe=de9ccde374) | Dec 18, 2021 |
| Acer          | Nitro AN515-53              | Notebook    | [a9affc8e28](https://linux-hardware.org/?probe=a9affc8e28) | Dec 18, 2021 |
| Dell          | Inspiron 5490               | Notebook    | [861cccd79f](https://linux-hardware.org/?probe=861cccd79f) | Dec 18, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [2fe6c83103](https://linux-hardware.org/?probe=2fe6c83103) | Dec 18, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [0b0904b925](https://linux-hardware.org/?probe=0b0904b925) | Dec 18, 2021 |
| Samsung       | 550XDA                      | Notebook    | [6b3fd04b47](https://linux-hardware.org/?probe=6b3fd04b47) | Dec 18, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [3854ed74f2](https://linux-hardware.org/?probe=3854ed74f2) | Dec 17, 2021 |
| ASRock        | H61M-VG3                    | Desktop     | [392a957541](https://linux-hardware.org/?probe=392a957541) | Dec 17, 2021 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [f568afeb8c](https://linux-hardware.org/?probe=f568afeb8c) | Dec 17, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [57431951a3](https://linux-hardware.org/?probe=57431951a3) | Dec 17, 2021 |
| Acer          | V5-171                      | Notebook    | [2058672bcf](https://linux-hardware.org/?probe=2058672bcf) | Dec 17, 2021 |
| Intel         | X99 V1.0                    | Desktop     | [49bca842a4](https://linux-hardware.org/?probe=49bca842a4) | Dec 17, 2021 |
| Intel         | B75                         | Desktop     | [95258dab55](https://linux-hardware.org/?probe=95258dab55) | Dec 17, 2021 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [882c4d6758](https://linux-hardware.org/?probe=882c4d6758) | Dec 17, 2021 |
| Positivo      | C14CR21TV                   | Notebook    | [e9cbfcb4b8](https://linux-hardware.org/?probe=e9cbfcb4b8) | Dec 17, 2021 |
| HP            | Pavilion 14                 | Notebook    | [be9e6368e4](https://linux-hardware.org/?probe=be9e6368e4) | Dec 17, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [c21343c233](https://linux-hardware.org/?probe=c21343c233) | Dec 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d3de4858ff](https://linux-hardware.org/?probe=d3de4858ff) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | Notebook    | [58eb588f8b](https://linux-hardware.org/?probe=58eb588f8b) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | Notebook    | [84cabc70f7](https://linux-hardware.org/?probe=84cabc70f7) | Dec 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ecf858d3fa](https://linux-hardware.org/?probe=ecf858d3fa) | Dec 16, 2021 |
| Lenovo        | Legion 5 15IMH05H 82CF      | Notebook    | [7ca51b2384](https://linux-hardware.org/?probe=7ca51b2384) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [eab6a0aed6](https://linux-hardware.org/?probe=eab6a0aed6) | Dec 16, 2021 |
| Positivo      | S14BW01                     | Notebook    | [94de31910c](https://linux-hardware.org/?probe=94de31910c) | Dec 16, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [e5268abe79](https://linux-hardware.org/?probe=e5268abe79) | Dec 16, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| Acer          | Aspire 5750Z                | Notebook    | [6a4339303f](https://linux-hardware.org/?probe=6a4339303f) | Dec 15, 2021 |
| Dell          | 0290HC A00                  | All in one  | [3f067e729f](https://linux-hardware.org/?probe=3f067e729f) | Dec 15, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [061faf00df](https://linux-hardware.org/?probe=061faf00df) | Dec 15, 2021 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [7d281d21d7](https://linux-hardware.org/?probe=7d281d21d7) | Dec 15, 2021 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [2480e6d750](https://linux-hardware.org/?probe=2480e6d750) | Dec 15, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [c76d68c4fd](https://linux-hardware.org/?probe=c76d68c4fd) | Dec 15, 2021 |
| ASUSTek       | K43U                        | Notebook    | [d7df2cd94e](https://linux-hardware.org/?probe=d7df2cd94e) | Dec 15, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [e57dc7794c](https://linux-hardware.org/?probe=e57dc7794c) | Dec 15, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [2cc6e5b35b](https://linux-hardware.org/?probe=2cc6e5b35b) | Dec 15, 2021 |
| Unknown       | Unknown                     | Notebook    | [9e4b4af367](https://linux-hardware.org/?probe=9e4b4af367) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [bcdd9529a6](https://linux-hardware.org/?probe=bcdd9529a6) | Dec 15, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [885ea098ef](https://linux-hardware.org/?probe=885ea098ef) | Dec 15, 2021 |
| Acer          | Nitro AN517-51              | Notebook    | [214ea4e512](https://linux-hardware.org/?probe=214ea4e512) | Dec 15, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [bd9653afdd](https://linux-hardware.org/?probe=bd9653afdd) | Dec 15, 2021 |
| Dell          | Vostro 3583                 | Notebook    | [ce55356c09](https://linux-hardware.org/?probe=ce55356c09) | Dec 15, 2021 |
| Positivo      | W942SW_SW1                  | Notebook    | [8022ee0ceb](https://linux-hardware.org/?probe=8022ee0ceb) | Dec 14, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [4a44000cf0](https://linux-hardware.org/?probe=4a44000cf0) | Dec 14, 2021 |
| Positivo      | POS-MIH61CF                 | Desktop     | [20ecdbd153](https://linux-hardware.org/?probe=20ecdbd153) | Dec 14, 2021 |
| Acer          | Nitro AN517-51              | Notebook    | [9002ea7794](https://linux-hardware.org/?probe=9002ea7794) | Dec 14, 2021 |
| Login Info... | LOG-H81H3-M4                | Desktop     | [08da3d865e](https://linux-hardware.org/?probe=08da3d865e) | Dec 14, 2021 |
| Login Info... | LOG-H81H3-M4                | Desktop     | [3a3571dba2](https://linux-hardware.org/?probe=3a3571dba2) | Dec 14, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [67ee599ec8](https://linux-hardware.org/?probe=67ee599ec8) | Dec 14, 2021 |
| Intel         | H55                         | Desktop     | [7debbb77f2](https://linux-hardware.org/?probe=7debbb77f2) | Dec 14, 2021 |
| Pegatron      | IPMH61P1                    | Desktop     | [1ba6ea2ee9](https://linux-hardware.org/?probe=1ba6ea2ee9) | Dec 14, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [dd29feeb10](https://linux-hardware.org/?probe=dd29feeb10) | Dec 14, 2021 |
| Digibras      | NH4CU03                     | Notebook    | [97b0f21219](https://linux-hardware.org/?probe=97b0f21219) | Dec 14, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [60710b379b](https://linux-hardware.org/?probe=60710b379b) | Dec 13, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [9e321117dd](https://linux-hardware.org/?probe=9e321117dd) | Dec 13, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [44d2be94f6](https://linux-hardware.org/?probe=44d2be94f6) | Dec 13, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [16af5a00db](https://linux-hardware.org/?probe=16af5a00db) | Dec 13, 2021 |
| ECS           | G41T-M7                     | Desktop     | [5a8641a9aa](https://linux-hardware.org/?probe=5a8641a9aa) | Dec 13, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [ef791632cf](https://linux-hardware.org/?probe=ef791632cf) | Dec 13, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [2074bdb7a5](https://linux-hardware.org/?probe=2074bdb7a5) | Dec 13, 2021 |
| Intel         | B75                         | Desktop     | [652828f7b9](https://linux-hardware.org/?probe=652828f7b9) | Dec 13, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [2259c467c8](https://linux-hardware.org/?probe=2259c467c8) | Dec 13, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [770a0db869](https://linux-hardware.org/?probe=770a0db869) | Dec 13, 2021 |
| Digibras      | NH4CU03                     | Notebook    | [5ffb383677](https://linux-hardware.org/?probe=5ffb383677) | Dec 13, 2021 |
| Sony          | VPCYB15AB                   | Notebook    | [780ef18db3](https://linux-hardware.org/?probe=780ef18db3) | Dec 13, 2021 |
| Avell High... | A70 LIV                     | Notebook    | [3930fc87b1](https://linux-hardware.org/?probe=3930fc87b1) | Dec 12, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [499d539995](https://linux-hardware.org/?probe=499d539995) | Dec 12, 2021 |
| Dell          | 0HJ781                      | Desktop     | [acac78cc8a](https://linux-hardware.org/?probe=acac78cc8a) | Dec 12, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [1ee5ab4347](https://linux-hardware.org/?probe=1ee5ab4347) | Dec 12, 2021 |
| MSI           | Katana GF66 11UC            | Notebook    | [4160ab78a5](https://linux-hardware.org/?probe=4160ab78a5) | Dec 12, 2021 |
| ASRock        | N68-S3 FX                   | Desktop     | [3cbe6d3002](https://linux-hardware.org/?probe=3cbe6d3002) | Dec 12, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [d9958d2f46](https://linux-hardware.org/?probe=d9958d2f46) | Dec 12, 2021 |
| Positivo      | CHT14B                      | Notebook    | [6ebdfd7b1f](https://linux-hardware.org/?probe=6ebdfd7b1f) | Dec 12, 2021 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [1c751e7ed7](https://linux-hardware.org/?probe=1c751e7ed7) | Dec 12, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [f5ae8cd0ac](https://linux-hardware.org/?probe=f5ae8cd0ac) | Dec 12, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [411bdbd3ed](https://linux-hardware.org/?probe=411bdbd3ed) | Dec 12, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [a46fba1154](https://linux-hardware.org/?probe=a46fba1154) | Dec 12, 2021 |
| Positivo      | POS-MI945AA                 | Desktop     | [d41df45a2d](https://linux-hardware.org/?probe=d41df45a2d) | Dec 11, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [e1ad26f0df](https://linux-hardware.org/?probe=e1ad26f0df) | Dec 11, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [52573eec91](https://linux-hardware.org/?probe=52573eec91) | Dec 11, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [b18adbf17f](https://linux-hardware.org/?probe=b18adbf17f) | Dec 11, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [ffd4903a50](https://linux-hardware.org/?probe=ffd4903a50) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [7d7873b658](https://linux-hardware.org/?probe=7d7873b658) | Dec 11, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [8fa258429d](https://linux-hardware.org/?probe=8fa258429d) | Dec 11, 2021 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [3c1c997421](https://linux-hardware.org/?probe=3c1c997421) | Dec 11, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [1acc5eb194](https://linux-hardware.org/?probe=1acc5eb194) | Dec 10, 2021 |
| Acer          | Aspire A514-53              | Notebook    | [eb51cb66cb](https://linux-hardware.org/?probe=eb51cb66cb) | Dec 10, 2021 |
| ASUSTek       | EX-B150M-V3                 | Desktop     | [b999617124](https://linux-hardware.org/?probe=b999617124) | Dec 10, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [1c9ca21f4e](https://linux-hardware.org/?probe=1c9ca21f4e) | Dec 10, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [e80b991fb4](https://linux-hardware.org/?probe=e80b991fb4) | Dec 10, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [ed02327600](https://linux-hardware.org/?probe=ed02327600) | Dec 10, 2021 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [939be3ba51](https://linux-hardware.org/?probe=939be3ba51) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [176194b06f](https://linux-hardware.org/?probe=176194b06f) | Dec 10, 2021 |
| OEM           | I38II                       | Notebook    | [b4db17dc1d](https://linux-hardware.org/?probe=b4db17dc1d) | Dec 10, 2021 |
| Huanan        | X79 V2.3 249PC              | Desktop     | [486dfd146e](https://linux-hardware.org/?probe=486dfd146e) | Dec 10, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [862ca9280c](https://linux-hardware.org/?probe=862ca9280c) | Dec 10, 2021 |
| Acer          | Aspire A514-53              | Notebook    | [90975ac5a8](https://linux-hardware.org/?probe=90975ac5a8) | Dec 09, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c081123078](https://linux-hardware.org/?probe=c081123078) | Dec 09, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [17d73377a6](https://linux-hardware.org/?probe=17d73377a6) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [33d0a5b33b](https://linux-hardware.org/?probe=33d0a5b33b) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [1c34027340](https://linux-hardware.org/?probe=1c34027340) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [0e19f8e2ae](https://linux-hardware.org/?probe=0e19f8e2ae) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [a37d2cc42f](https://linux-hardware.org/?probe=a37d2cc42f) | Dec 09, 2021 |
| LG Electro... | A410-G.BC49P1               | Notebook    | [5f952dc625](https://linux-hardware.org/?probe=5f952dc625) | Dec 09, 2021 |
| Dell          | Inspiron 7472               | Notebook    | [64b7b3a797](https://linux-hardware.org/?probe=64b7b3a797) | Dec 09, 2021 |
| Gigabyte      | Z370M AORUS Gaming-CF       | Desktop     | [1a64f6d9ca](https://linux-hardware.org/?probe=1a64f6d9ca) | Dec 09, 2021 |
| Unknown       | MT6771V/CT (DT)             | Soc         | [8fc4d20686](https://linux-hardware.org/?probe=8fc4d20686) | Dec 09, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [d32c954439](https://linux-hardware.org/?probe=d32c954439) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [24da5b4ebe](https://linux-hardware.org/?probe=24da5b4ebe) | Dec 08, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [eff62b036a](https://linux-hardware.org/?probe=eff62b036a) | Dec 08, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [ccc253bb9a](https://linux-hardware.org/?probe=ccc253bb9a) | Dec 08, 2021 |
| Intel         | H55                         | Desktop     | [ee970ff7cd](https://linux-hardware.org/?probe=ee970ff7cd) | Dec 08, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [9312862519](https://linux-hardware.org/?probe=9312862519) | Dec 08, 2021 |
| Acer          | Spin SP315-51               | Convertible | [b0024d427d](https://linux-hardware.org/?probe=b0024d427d) | Dec 08, 2021 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [b8c7e334d0](https://linux-hardware.org/?probe=b8c7e334d0) | Dec 08, 2021 |
| Dell          | Vostro 3583                 | Notebook    | [5c12c4090b](https://linux-hardware.org/?probe=5c12c4090b) | Dec 08, 2021 |
| HP            | Unknown                     | Notebook    | [33ca2db025](https://linux-hardware.org/?probe=33ca2db025) | Dec 07, 2021 |
| Positivo      | POS-EINM70CS POSITIVO       | Desktop     | [692ab16355](https://linux-hardware.org/?probe=692ab16355) | Dec 07, 2021 |
| Dell          | Vostro 5481                 | Notebook    | [aff3262599](https://linux-hardware.org/?probe=aff3262599) | Dec 07, 2021 |
| Avell High... | B.ON                        | Notebook    | [5bfb9e677a](https://linux-hardware.org/?probe=5bfb9e677a) | Dec 07, 2021 |
| Avell High... | B.ON                        | Notebook    | [d2b832ea0a](https://linux-hardware.org/?probe=d2b832ea0a) | Dec 07, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [9fa66d6287](https://linux-hardware.org/?probe=9fa66d6287) | Dec 07, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [4bc9eb7cea](https://linux-hardware.org/?probe=4bc9eb7cea) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [ad406a6f63](https://linux-hardware.org/?probe=ad406a6f63) | Dec 07, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [d4b308c0c8](https://linux-hardware.org/?probe=d4b308c0c8) | Dec 07, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [5c46f5e832](https://linux-hardware.org/?probe=5c46f5e832) | Dec 07, 2021 |
| Intel         | HuronRiver Platform         | Notebook    | [95d3387e6c](https://linux-hardware.org/?probe=95d3387e6c) | Dec 07, 2021 |
| OEM           | B75                         | Desktop     | [d6a1e29a32](https://linux-hardware.org/?probe=d6a1e29a32) | Dec 07, 2021 |
| Samsung       | 550XDA                      | Notebook    | [948f6de494](https://linux-hardware.org/?probe=948f6de494) | Dec 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [1b7cc00c10](https://linux-hardware.org/?probe=1b7cc00c10) | Dec 07, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [7fe252c0cd](https://linux-hardware.org/?probe=7fe252c0cd) | Dec 07, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [88d9ee29b4](https://linux-hardware.org/?probe=88d9ee29b4) | Dec 07, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [7cb1ebd6c9](https://linux-hardware.org/?probe=7cb1ebd6c9) | Dec 07, 2021 |
| Dell          | Latitude 3420               | Notebook    | [4885c88ddc](https://linux-hardware.org/?probe=4885c88ddc) | Dec 06, 2021 |
| Positivo      | J14AL11                     | Notebook    | [2e5fd22945](https://linux-hardware.org/?probe=2e5fd22945) | Dec 06, 2021 |
| Unknown       | Unknown                     | Tablet      | [8bc0024182](https://linux-hardware.org/?probe=8bc0024182) | Dec 06, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [543f25da6d](https://linux-hardware.org/?probe=543f25da6d) | Dec 06, 2021 |
| Unknown       | Phitronics PN73PVS-M        | Desktop     | [f64b92d5b2](https://linux-hardware.org/?probe=f64b92d5b2) | Dec 06, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [1493fa959b](https://linux-hardware.org/?probe=1493fa959b) | Dec 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [059c42fd1a](https://linux-hardware.org/?probe=059c42fd1a) | Dec 06, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [9df7d7ad8f](https://linux-hardware.org/?probe=9df7d7ad8f) | Dec 06, 2021 |
| Acer          | Aspire E1-421               | Notebook    | [a7c18d534d](https://linux-hardware.org/?probe=a7c18d534d) | Dec 06, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [7763d72707](https://linux-hardware.org/?probe=7763d72707) | Dec 06, 2021 |
| Toshiba       | IS-1253                     | Notebook    | [0b8914d4c8](https://linux-hardware.org/?probe=0b8914d4c8) | Dec 06, 2021 |
| Dell          | Inspiron 5482               | Convertible | [03eafd14da](https://linux-hardware.org/?probe=03eafd14da) | Dec 05, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [1d0798ca73](https://linux-hardware.org/?probe=1d0798ca73) | Dec 05, 2021 |
| Dell          | Inspiron 5482               | Convertible | [c1bb3c51d7](https://linux-hardware.org/?probe=c1bb3c51d7) | Dec 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ed493cd76f](https://linux-hardware.org/?probe=ed493cd76f) | Dec 05, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a838b63586](https://linux-hardware.org/?probe=a838b63586) | Dec 05, 2021 |
| INTELBRAS     | IE-G41T-M7                  | Desktop     | [ff7f8750ea](https://linux-hardware.org/?probe=ff7f8750ea) | Dec 05, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [bf5b172c0f](https://linux-hardware.org/?probe=bf5b172c0f) | Dec 05, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [a3524e5c56](https://linux-hardware.org/?probe=a3524e5c56) | Dec 05, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [f4b7b56b1b](https://linux-hardware.org/?probe=f4b7b56b1b) | Dec 05, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [81a9718a11](https://linux-hardware.org/?probe=81a9718a11) | Dec 05, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [2c23cbe8d1](https://linux-hardware.org/?probe=2c23cbe8d1) | Dec 05, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [b4382c3b38](https://linux-hardware.org/?probe=b4382c3b38) | Dec 04, 2021 |
| Positivo      | NB50TH                      | Notebook    | [705bae2d39](https://linux-hardware.org/?probe=705bae2d39) | Dec 04, 2021 |
| Acer          | Aspire A514-54G             | Notebook    | [ff52dd520c](https://linux-hardware.org/?probe=ff52dd520c) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [a3209e0ed1](https://linux-hardware.org/?probe=a3209e0ed1) | Dec 04, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Avell High... | B.ON                        | Notebook    | [91a81934ed](https://linux-hardware.org/?probe=91a81934ed) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [bc211e09fd](https://linux-hardware.org/?probe=bc211e09fd) | Dec 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [2b7412b23b](https://linux-hardware.org/?probe=2b7412b23b) | Dec 04, 2021 |
| Intel         | B75                         | Desktop     | [42982cfe94](https://linux-hardware.org/?probe=42982cfe94) | Dec 04, 2021 |
| Dell          | Inspiron 5490               | Notebook    | [21da3b7e37](https://linux-hardware.org/?probe=21da3b7e37) | Dec 03, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [58020d3b39](https://linux-hardware.org/?probe=58020d3b39) | Dec 03, 2021 |
| Intel         | B75                         | Desktop     | [c76a831e54](https://linux-hardware.org/?probe=c76a831e54) | Dec 03, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [e9247c2fb2](https://linux-hardware.org/?probe=e9247c2fb2) | Dec 03, 2021 |
| Sony          | SVE14A15FBP                 | Notebook    | [4a5895c643](https://linux-hardware.org/?probe=4a5895c643) | Dec 03, 2021 |
| Pegatron      | 2AD2A                       | Desktop     | [62775fc64d](https://linux-hardware.org/?probe=62775fc64d) | Dec 03, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [29ff3edb05](https://linux-hardware.org/?probe=29ff3edb05) | Dec 03, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [313d4d0bd8](https://linux-hardware.org/?probe=313d4d0bd8) | Dec 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [59795a80ef](https://linux-hardware.org/?probe=59795a80ef) | Dec 03, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [4012763f85](https://linux-hardware.org/?probe=4012763f85) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [088fab187c](https://linux-hardware.org/?probe=088fab187c) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [2f6f3b14de](https://linux-hardware.org/?probe=2f6f3b14de) | Dec 03, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [bbdfd3b78e](https://linux-hardware.org/?probe=bbdfd3b78e) | Dec 02, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [945995abf6](https://linux-hardware.org/?probe=945995abf6) | Dec 02, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [35a82530fb](https://linux-hardware.org/?probe=35a82530fb) | Dec 02, 2021 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [ca1727f54a](https://linux-hardware.org/?probe=ca1727f54a) | Dec 02, 2021 |
| Positivo      | H14BT58                     | Notebook    | [7e692b3a7a](https://linux-hardware.org/?probe=7e692b3a7a) | Dec 02, 2021 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [c82a34a915](https://linux-hardware.org/?probe=c82a34a915) | Dec 02, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [a824747d21](https://linux-hardware.org/?probe=a824747d21) | Dec 02, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [6491dbee12](https://linux-hardware.org/?probe=6491dbee12) | Dec 02, 2021 |
| Dell          | Inspiron N4050              | Notebook    | [46f1d21cbc](https://linux-hardware.org/?probe=46f1d21cbc) | Dec 02, 2021 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [6432830846](https://linux-hardware.org/?probe=6432830846) | Dec 02, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [3d6f1cb094](https://linux-hardware.org/?probe=3d6f1cb094) | Dec 02, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [5c74762b22](https://linux-hardware.org/?probe=5c74762b22) | Dec 02, 2021 |
| Dell          | 0D8312 A00                  | Desktop     | [806ae8b9e6](https://linux-hardware.org/?probe=806ae8b9e6) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [4f46a6c92a](https://linux-hardware.org/?probe=4f46a6c92a) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [1521941a87](https://linux-hardware.org/?probe=1521941a87) | Dec 02, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [4a21fcd64f](https://linux-hardware.org/?probe=4a21fcd64f) | Dec 02, 2021 |
| Philco        | 14F                         | Notebook    | [ab69e64295](https://linux-hardware.org/?probe=ab69e64295) | Dec 02, 2021 |
| Avell High... | B.ON                        | Notebook    | [a7513f22ee](https://linux-hardware.org/?probe=a7513f22ee) | Dec 02, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [9bbfd01bca](https://linux-hardware.org/?probe=9bbfd01bca) | Dec 01, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [18d91295e1](https://linux-hardware.org/?probe=18d91295e1) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [6807edf501](https://linux-hardware.org/?probe=6807edf501) | Dec 01, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3027af9a0e](https://linux-hardware.org/?probe=3027af9a0e) | Dec 01, 2021 |
| ASRock        | H310M-HG4                   | Desktop     | [8668ab4a0b](https://linux-hardware.org/?probe=8668ab4a0b) | Dec 01, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [6522739036](https://linux-hardware.org/?probe=6522739036) | Dec 01, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [3438f86ded](https://linux-hardware.org/?probe=3438f86ded) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [500f9c8851](https://linux-hardware.org/?probe=500f9c8851) | Dec 01, 2021 |
| Biostar       | H310MHC2                    | Desktop     | [1a5c78c192](https://linux-hardware.org/?probe=1a5c78c192) | Dec 01, 2021 |
| Biostar       | H310MHC2                    | Desktop     | [9671ad8fd0](https://linux-hardware.org/?probe=9671ad8fd0) | Dec 01, 2021 |
| Samsung       | 550XDA                      | Notebook    | [30c24b17f4](https://linux-hardware.org/?probe=30c24b17f4) | Dec 01, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [960a8d5f25](https://linux-hardware.org/?probe=960a8d5f25) | Dec 01, 2021 |
| Toshiba       | STI 007467                  | Desktop     | [ac036e6dd5](https://linux-hardware.org/?probe=ac036e6dd5) | Nov 30, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [7fe28eead2](https://linux-hardware.org/?probe=7fe28eead2) | Nov 30, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [991967c2ff](https://linux-hardware.org/?probe=991967c2ff) | Nov 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [74ce8e4fbe](https://linux-hardware.org/?probe=74ce8e4fbe) | Nov 30, 2021 |
| Dell          | 072J5G A00                  | Server      | [2cb0bf19f0](https://linux-hardware.org/?probe=2cb0bf19f0) | Nov 30, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [0a6feb58e7](https://linux-hardware.org/?probe=0a6feb58e7) | Nov 30, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [1b4de261b3](https://linux-hardware.org/?probe=1b4de261b3) | Nov 30, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [3da13c5e1b](https://linux-hardware.org/?probe=3da13c5e1b) | Nov 30, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [7edf9fe1b5](https://linux-hardware.org/?probe=7edf9fe1b5) | Nov 30, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [e62e98d46d](https://linux-hardware.org/?probe=e62e98d46d) | Nov 30, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [6ee6a2bc49](https://linux-hardware.org/?probe=6ee6a2bc49) | Nov 30, 2021 |
| Intel         | H61                         | Desktop     | [9191bc7b9c](https://linux-hardware.org/?probe=9191bc7b9c) | Nov 30, 2021 |
| Acer          | Nitro AN517-51              | Notebook    | [e7af37db76](https://linux-hardware.org/?probe=e7af37db76) | Nov 30, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ecc61836da](https://linux-hardware.org/?probe=ecc61836da) | Nov 30, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [59da226d80](https://linux-hardware.org/?probe=59da226d80) | Nov 30, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [7532ace96c](https://linux-hardware.org/?probe=7532ace96c) | Nov 29, 2021 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [12d13db993](https://linux-hardware.org/?probe=12d13db993) | Nov 29, 2021 |
| Dell          | G5 5590                     | Notebook    | [e569e56450](https://linux-hardware.org/?probe=e569e56450) | Nov 29, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [dcd5217827](https://linux-hardware.org/?probe=dcd5217827) | Nov 29, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [677782bf59](https://linux-hardware.org/?probe=677782bf59) | Nov 29, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [26cba9b931](https://linux-hardware.org/?probe=26cba9b931) | Nov 29, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [a716e055d8](https://linux-hardware.org/?probe=a716e055d8) | Nov 29, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [3a2bf12582](https://linux-hardware.org/?probe=3a2bf12582) | Nov 29, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [10754c360e](https://linux-hardware.org/?probe=10754c360e) | Nov 29, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [71e47d66a9](https://linux-hardware.org/?probe=71e47d66a9) | Nov 28, 2021 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [7e68f244db](https://linux-hardware.org/?probe=7e68f244db) | Nov 28, 2021 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [44a2f22839](https://linux-hardware.org/?probe=44a2f22839) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [7add4c45f0](https://linux-hardware.org/?probe=7add4c45f0) | Nov 28, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [aa9b2c7788](https://linux-hardware.org/?probe=aa9b2c7788) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [c3ac874c98](https://linux-hardware.org/?probe=c3ac874c98) | Nov 28, 2021 |
| Huanan        | X79 249PC V2.2              | Desktop     | [9fa5442062](https://linux-hardware.org/?probe=9fa5442062) | Nov 28, 2021 |
| LG Electro... | 22V240 FAB3                 | All in one  | [07bc131da8](https://linux-hardware.org/?probe=07bc131da8) | Nov 28, 2021 |
| Acer          | Aspire 5050                 | Notebook    | [22057607c1](https://linux-hardware.org/?probe=22057607c1) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [cd296f933b](https://linux-hardware.org/?probe=cd296f933b) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [44c0cf428f](https://linux-hardware.org/?probe=44c0cf428f) | Nov 28, 2021 |
| Philco        | OEM                         | Notebook    | [3d13f6a539](https://linux-hardware.org/?probe=3d13f6a539) | Nov 28, 2021 |
| Dell          | Inspiron 5447               | Notebook    | [bbdd9f0b69](https://linux-hardware.org/?probe=bbdd9f0b69) | Nov 28, 2021 |
| Acer          | Aspire 5050                 | Notebook    | [7935d8067b](https://linux-hardware.org/?probe=7935d8067b) | Nov 28, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [9993e59d59](https://linux-hardware.org/?probe=9993e59d59) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [02b7a680cd](https://linux-hardware.org/?probe=02b7a680cd) | Nov 28, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [5d5d624d8c](https://linux-hardware.org/?probe=5d5d624d8c) | Nov 27, 2021 |
| Dell          | Inspiron 5421               | Notebook    | [2bf059f608](https://linux-hardware.org/?probe=2bf059f608) | Nov 27, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b63d468197](https://linux-hardware.org/?probe=b63d468197) | Nov 27, 2021 |
| Login Info... | LOG-MB47II7                 | Notebook    | [1c2d866625](https://linux-hardware.org/?probe=1c2d866625) | Nov 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [69b74ce687](https://linux-hardware.org/?probe=69b74ce687) | Nov 27, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [942114b7ed](https://linux-hardware.org/?probe=942114b7ed) | Nov 27, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [08c282da3a](https://linux-hardware.org/?probe=08c282da3a) | Nov 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [16be623c84](https://linux-hardware.org/?probe=16be623c84) | Nov 27, 2021 |
| ASRock        | H77M                        | Desktop     | [c606652163](https://linux-hardware.org/?probe=c606652163) | Nov 27, 2021 |
| Dell          | Inspiron 7559               | Notebook    | [e2b7b798a8](https://linux-hardware.org/?probe=e2b7b798a8) | Nov 27, 2021 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [c23e7e890b](https://linux-hardware.org/?probe=c23e7e890b) | Nov 27, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [1e4799819e](https://linux-hardware.org/?probe=1e4799819e) | Nov 26, 2021 |
| PCWare        | IPMH61R3                    | Desktop     | [9d69282e7a](https://linux-hardware.org/?probe=9d69282e7a) | Nov 26, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [8a5475fd42](https://linux-hardware.org/?probe=8a5475fd42) | Nov 26, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [8c0a3a65ba](https://linux-hardware.org/?probe=8c0a3a65ba) | Nov 26, 2021 |
| LG Electro... | Z430-G.BE41P1               | Notebook    | [d2a91c1633](https://linux-hardware.org/?probe=d2a91c1633) | Nov 26, 2021 |
| LG Electro... | Z430-G.BE41P1               | Notebook    | [10770dac94](https://linux-hardware.org/?probe=10770dac94) | Nov 26, 2021 |
| ASRock        | H110M-HG4                   | Desktop     | [7a9a5a1f00](https://linux-hardware.org/?probe=7a9a5a1f00) | Nov 26, 2021 |
| Positivo      | Mobile                      | Notebook    | [f67e7cf244](https://linux-hardware.org/?probe=f67e7cf244) | Nov 25, 2021 |
| Avell High... | B.ON                        | Notebook    | [5fd318217e](https://linux-hardware.org/?probe=5fd318217e) | Nov 25, 2021 |
| Positivo      | Mobile                      | Notebook    | [aa89357d9f](https://linux-hardware.org/?probe=aa89357d9f) | Nov 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [9048aa2348](https://linux-hardware.org/?probe=9048aa2348) | Nov 25, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [1ec79ee5e6](https://linux-hardware.org/?probe=1ec79ee5e6) | Nov 25, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [cd408c48d0](https://linux-hardware.org/?probe=cd408c48d0) | Nov 25, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [3c089ce814](https://linux-hardware.org/?probe=3c089ce814) | Nov 25, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [a10a19ecfb](https://linux-hardware.org/?probe=a10a19ecfb) | Nov 25, 2021 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [df371e2ae6](https://linux-hardware.org/?probe=df371e2ae6) | Nov 25, 2021 |
| Dell          | Inspiron 5537               | Notebook    | [be435b0de0](https://linux-hardware.org/?probe=be435b0de0) | Nov 25, 2021 |
| Dell          | Inspiron 5537               | Notebook    | [d09709c348](https://linux-hardware.org/?probe=d09709c348) | Nov 25, 2021 |
| HP            | ProBook 6460b               | Notebook    | [a072a6246d](https://linux-hardware.org/?probe=a072a6246d) | Nov 25, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [4766af9ef7](https://linux-hardware.org/?probe=4766af9ef7) | Nov 25, 2021 |
| Multilaser    | PC024                       | Notebook    | [7979d1f6b5](https://linux-hardware.org/?probe=7979d1f6b5) | Nov 25, 2021 |
| LG Electro... | S425-L.BC24P1               | Notebook    | [6d6d4fca9b](https://linux-hardware.org/?probe=6d6d4fca9b) | Nov 24, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [7cb7c080e6](https://linux-hardware.org/?probe=7cb7c080e6) | Nov 24, 2021 |
| HP            | 1998                        | Desktop     | [96a848eddc](https://linux-hardware.org/?probe=96a848eddc) | Nov 24, 2021 |
| Toshiba       | STI NA 1401                 | Notebook    | [e2440e4557](https://linux-hardware.org/?probe=e2440e4557) | Nov 24, 2021 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [64e0d3193c](https://linux-hardware.org/?probe=64e0d3193c) | Nov 24, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [35daf15c62](https://linux-hardware.org/?probe=35daf15c62) | Nov 24, 2021 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [4c71ba1902](https://linux-hardware.org/?probe=4c71ba1902) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b6bfa4b827](https://linux-hardware.org/?probe=b6bfa4b827) | Nov 24, 2021 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d5f31eb76e](https://linux-hardware.org/?probe=d5f31eb76e) | Nov 24, 2021 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d61128f6f4](https://linux-hardware.org/?probe=d61128f6f4) | Nov 24, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [9dcd5129ea](https://linux-hardware.org/?probe=9dcd5129ea) | Nov 24, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [d4bfc15ece](https://linux-hardware.org/?probe=d4bfc15ece) | Nov 24, 2021 |
| Samsung       | RV419                       | Notebook    | [61ed787e01](https://linux-hardware.org/?probe=61ed787e01) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [670534d1c1](https://linux-hardware.org/?probe=670534d1c1) | Nov 24, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [ba05aeb5fe](https://linux-hardware.org/?probe=ba05aeb5fe) | Nov 23, 2021 |
| Toshiba       | STI 012887                  | Desktop     | [f021a9f7a7](https://linux-hardware.org/?probe=f021a9f7a7) | Nov 23, 2021 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [1e54dd310c](https://linux-hardware.org/?probe=1e54dd310c) | Nov 23, 2021 |
| HP            | ENVY 17                     | Notebook    | [55408e2f19](https://linux-hardware.org/?probe=55408e2f19) | Nov 23, 2021 |
| Acer          | Aspire 5338                 | Notebook    | [db097f4f70](https://linux-hardware.org/?probe=db097f4f70) | Nov 23, 2021 |
| Dell          | Inspiron 11-3168            | Notebook    | [b7b3b8ef38](https://linux-hardware.org/?probe=b7b3b8ef38) | Nov 23, 2021 |
| Dell          | Vostro 1510                 | Notebook    | [3eb9def4af](https://linux-hardware.org/?probe=3eb9def4af) | Nov 23, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [9fd987e7d8](https://linux-hardware.org/?probe=9fd987e7d8) | Nov 23, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [b4fb255866](https://linux-hardware.org/?probe=b4fb255866) | Nov 23, 2021 |
| Dell          | Inspiron 7560               | Notebook    | [8a73006911](https://linux-hardware.org/?probe=8a73006911) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | Notebook    | [d29d6c2f61](https://linux-hardware.org/?probe=d29d6c2f61) | Nov 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [57364e93b2](https://linux-hardware.org/?probe=57364e93b2) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | Notebook    | [6e361a8715](https://linux-hardware.org/?probe=6e361a8715) | Nov 23, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [457a2ff293](https://linux-hardware.org/?probe=457a2ff293) | Nov 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ef65932064](https://linux-hardware.org/?probe=ef65932064) | Nov 23, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [9d5c38a0f0](https://linux-hardware.org/?probe=9d5c38a0f0) | Nov 22, 2021 |
| MSI           | H97M-G43                    | Desktop     | [72386930d0](https://linux-hardware.org/?probe=72386930d0) | Nov 22, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [0188a0770d](https://linux-hardware.org/?probe=0188a0770d) | Nov 22, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [1c1aa18fb7](https://linux-hardware.org/?probe=1c1aa18fb7) | Nov 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [ebc991da95](https://linux-hardware.org/?probe=ebc991da95) | Nov 22, 2021 |
| Sony          | VGN-FZ480E                  | Notebook    | [18898ae0ab](https://linux-hardware.org/?probe=18898ae0ab) | Nov 21, 2021 |
| Daten Tecn... | DQ77PRO                     | Desktop     | [43a566e5c5](https://linux-hardware.org/?probe=43a566e5c5) | Nov 21, 2021 |
| MEGA          | G41T-M7 LGT                 | Desktop     | [7238b4cd22](https://linux-hardware.org/?probe=7238b4cd22) | Nov 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [423bdd7d74](https://linux-hardware.org/?probe=423bdd7d74) | Nov 21, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [bb0a461d82](https://linux-hardware.org/?probe=bb0a461d82) | Nov 21, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [500749d948](https://linux-hardware.org/?probe=500749d948) | Nov 21, 2021 |
| ASUSTek       | K43E                        | Notebook    | [5d93c9b5e1](https://linux-hardware.org/?probe=5d93c9b5e1) | Nov 20, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [09039121c2](https://linux-hardware.org/?probe=09039121c2) | Nov 20, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [53054c8f7a](https://linux-hardware.org/?probe=53054c8f7a) | Nov 20, 2021 |
| Positivo      | POS-EINM70CS POSITIVO       | Desktop     | [54ef64d5fd](https://linux-hardware.org/?probe=54ef64d5fd) | Nov 20, 2021 |
| Megaware      | MW-H61H2-M2                 | Desktop     | [5c6dcdd573](https://linux-hardware.org/?probe=5c6dcdd573) | Nov 20, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [c5dc9a3bde](https://linux-hardware.org/?probe=c5dc9a3bde) | Nov 20, 2021 |
| Toshiba       | IS 1462B                    | Notebook    | [682a8f788c](https://linux-hardware.org/?probe=682a8f788c) | Nov 20, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [9a5752b5a6](https://linux-hardware.org/?probe=9a5752b5a6) | Nov 19, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [1717b35b87](https://linux-hardware.org/?probe=1717b35b87) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [31cebd4e96](https://linux-hardware.org/?probe=31cebd4e96) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [0be43eb710](https://linux-hardware.org/?probe=0be43eb710) | Nov 19, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9462d546b4](https://linux-hardware.org/?probe=9462d546b4) | Nov 19, 2021 |
| Positivo      | C14CR21                     | Notebook    | [a771171160](https://linux-hardware.org/?probe=a771171160) | Nov 19, 2021 |
| Acer          | Aspire 4745                 | Notebook    | [9edc4a1dd4](https://linux-hardware.org/?probe=9edc4a1dd4) | Nov 19, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [495017ce96](https://linux-hardware.org/?probe=495017ce96) | Nov 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [c33849e45a](https://linux-hardware.org/?probe=c33849e45a) | Nov 19, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [96d8266022](https://linux-hardware.org/?probe=96d8266022) | Nov 19, 2021 |
| ASUSTek       | P5VD2-MX SE                 | Desktop     | [bf34c9fbca](https://linux-hardware.org/?probe=bf34c9fbca) | Nov 19, 2021 |
| HP            | Compaq Presario CQ50        | Notebook    | [75700ea22a](https://linux-hardware.org/?probe=75700ea22a) | Nov 19, 2021 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [1e36050d80](https://linux-hardware.org/?probe=1e36050d80) | Nov 18, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [4383599975](https://linux-hardware.org/?probe=4383599975) | Nov 18, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [34aff3ab72](https://linux-hardware.org/?probe=34aff3ab72) | Nov 18, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [e8a4c6e52b](https://linux-hardware.org/?probe=e8a4c6e52b) | Nov 18, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [ac573c69d3](https://linux-hardware.org/?probe=ac573c69d3) | Nov 18, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [8bc6042d3f](https://linux-hardware.org/?probe=8bc6042d3f) | Nov 17, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [d850875f62](https://linux-hardware.org/?probe=d850875f62) | Nov 17, 2021 |
| SZMZ          | X99M-G2                     | Desktop     | [14cf409f74](https://linux-hardware.org/?probe=14cf409f74) | Nov 17, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [e4919b1254](https://linux-hardware.org/?probe=e4919b1254) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | Notebook    | [585419cd38](https://linux-hardware.org/?probe=585419cd38) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | Notebook    | [9dff5423c9](https://linux-hardware.org/?probe=9dff5423c9) | Nov 17, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [30520d2f19](https://linux-hardware.org/?probe=30520d2f19) | Nov 17, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [d71fa6378d](https://linux-hardware.org/?probe=d71fa6378d) | Nov 17, 2021 |
| Positivo      | Mobile                      | Notebook    | [9b83c09ad3](https://linux-hardware.org/?probe=9b83c09ad3) | Nov 17, 2021 |
| MSI           | Boston                      | Desktop     | [6e0d850a8e](https://linux-hardware.org/?probe=6e0d850a8e) | Nov 17, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [dc16c3ef7d](https://linux-hardware.org/?probe=dc16c3ef7d) | Nov 17, 2021 |
| Samsung       | 550XDA                      | Notebook    | [607bff4b5f](https://linux-hardware.org/?probe=607bff4b5f) | Nov 17, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [217880cca8](https://linux-hardware.org/?probe=217880cca8) | Nov 17, 2021 |
| Dell          | Inspiron 7560               | Notebook    | [84b417f9d3](https://linux-hardware.org/?probe=84b417f9d3) | Nov 17, 2021 |
| Dell          | 0GXM1W A02                  | Desktop     | [0631623e1e](https://linux-hardware.org/?probe=0631623e1e) | Nov 17, 2021 |
| Lenovo        | ThinkPad E14 20RBS2D100     | Notebook    | [f3a3d2668d](https://linux-hardware.org/?probe=f3a3d2668d) | Nov 17, 2021 |
| HP            | 0A58h                       | Desktop     | [caecb0c75f](https://linux-hardware.org/?probe=caecb0c75f) | Nov 17, 2021 |
| Gigabyte      | VM900M                      | Desktop     | [80536ac6e5](https://linux-hardware.org/?probe=80536ac6e5) | Nov 16, 2021 |
| Gigabyte      | VM900M                      | Desktop     | [7cd9a0a1ca](https://linux-hardware.org/?probe=7cd9a0a1ca) | Nov 16, 2021 |
| Lenovo        | ThinkPad E14 20RBS2D100     | Notebook    | [e0a279ef7e](https://linux-hardware.org/?probe=e0a279ef7e) | Nov 16, 2021 |
| Acer          | Aspire E1-421               | Notebook    | [52cc14391a](https://linux-hardware.org/?probe=52cc14391a) | Nov 16, 2021 |
| Positivo      | POS-PIQ67CG POSITIVO        | Desktop     | [bcec39d0de](https://linux-hardware.org/?probe=bcec39d0de) | Nov 16, 2021 |
| ASUSTek       | K43E                        | Notebook    | [ce875ce67c](https://linux-hardware.org/?probe=ce875ce67c) | Nov 16, 2021 |
| Lenovo        | IdeaPad Z460 0913           | Notebook    | [0bb3eea006](https://linux-hardware.org/?probe=0bb3eea006) | Nov 16, 2021 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [ce6fcda189](https://linux-hardware.org/?probe=ce6fcda189) | Nov 16, 2021 |
| ASUSTek       | K43E                        | Notebook    | [bd2dad5f8e](https://linux-hardware.org/?probe=bd2dad5f8e) | Nov 16, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [223642cd17](https://linux-hardware.org/?probe=223642cd17) | Nov 16, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [8a16729060](https://linux-hardware.org/?probe=8a16729060) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [dbaa27643e](https://linux-hardware.org/?probe=dbaa27643e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [aad4a92e0e](https://linux-hardware.org/?probe=aad4a92e0e) | Nov 16, 2021 |
| LG Electro... | X140-G.BG12P1               | Notebook    | [337924a30c](https://linux-hardware.org/?probe=337924a30c) | Nov 16, 2021 |
| LG Electro... | X140-G.BG12P1               | Notebook    | [abe339e912](https://linux-hardware.org/?probe=abe339e912) | Nov 16, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [c5764c10dc](https://linux-hardware.org/?probe=c5764c10dc) | Nov 16, 2021 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [203c43fc12](https://linux-hardware.org/?probe=203c43fc12) | Nov 15, 2021 |
| Positivo      | POS-PIQ67CG POSITIVO        | Desktop     | [8f7dd03e2d](https://linux-hardware.org/?probe=8f7dd03e2d) | Nov 15, 2021 |
| ASUSTek       | X751LJ                      | Notebook    | [79030e87e9](https://linux-hardware.org/?probe=79030e87e9) | Nov 15, 2021 |
| ASUSTek       | M2N-E                       | Desktop     | [8da42387a5](https://linux-hardware.org/?probe=8da42387a5) | Nov 15, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [b6630ba66c](https://linux-hardware.org/?probe=b6630ba66c) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [74ce7d98c6](https://linux-hardware.org/?probe=74ce7d98c6) | Nov 15, 2021 |
| MSI           | MS-7529                     | Desktop     | [d6f55ff177](https://linux-hardware.org/?probe=d6f55ff177) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [180bbba91c](https://linux-hardware.org/?probe=180bbba91c) | Nov 15, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [f998266e76](https://linux-hardware.org/?probe=f998266e76) | Nov 15, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [3028a32b5d](https://linux-hardware.org/?probe=3028a32b5d) | Nov 15, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [ca5c253749](https://linux-hardware.org/?probe=ca5c253749) | Nov 14, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [0d585eb1d9](https://linux-hardware.org/?probe=0d585eb1d9) | Nov 14, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b0f479b5b3](https://linux-hardware.org/?probe=b0f479b5b3) | Nov 14, 2021 |
| ASRock        | Z590M Phantom Gaming 4      | Desktop     | [f5df2fd431](https://linux-hardware.org/?probe=f5df2fd431) | Nov 14, 2021 |
| Lenovo        | G470 20078                  | Notebook    | [cd92d6030e](https://linux-hardware.org/?probe=cd92d6030e) | Nov 14, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [328668f616](https://linux-hardware.org/?probe=328668f616) | Nov 14, 2021 |
| Dell          | 0VRWRC A01                  | Desktop     | [e202cef308](https://linux-hardware.org/?probe=e202cef308) | Nov 14, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [29d6ad8b6f](https://linux-hardware.org/?probe=29d6ad8b6f) | Nov 14, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [832b5007b0](https://linux-hardware.org/?probe=832b5007b0) | Nov 14, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [3a6a636384](https://linux-hardware.org/?probe=3a6a636384) | Nov 14, 2021 |
| OEM           | I38II                       | Notebook    | [0b2d349414](https://linux-hardware.org/?probe=0b2d349414) | Nov 14, 2021 |
| Positivo      | H14SU08                     | Notebook    | [5e9259bbd3](https://linux-hardware.org/?probe=5e9259bbd3) | Nov 14, 2021 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ffbf11ec7f](https://linux-hardware.org/?probe=ffbf11ec7f) | Nov 14, 2021 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [8968b7142d](https://linux-hardware.org/?probe=8968b7142d) | Nov 14, 2021 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [bb0216f047](https://linux-hardware.org/?probe=bb0216f047) | Nov 13, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ed343e426b](https://linux-hardware.org/?probe=ed343e426b) | Nov 13, 2021 |
| Login Info... | LOG-MB47II7                 | Notebook    | [4a568a9bdf](https://linux-hardware.org/?probe=4a568a9bdf) | Nov 13, 2021 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [3eaabe505d](https://linux-hardware.org/?probe=3eaabe505d) | Nov 13, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [cfd9893fd8](https://linux-hardware.org/?probe=cfd9893fd8) | Nov 13, 2021 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [8f763c3644](https://linux-hardware.org/?probe=8f763c3644) | Nov 13, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [06699211b6](https://linux-hardware.org/?probe=06699211b6) | Nov 13, 2021 |
| HP            | ProLiant DL360 G5           | Server      | [59421fdcd1](https://linux-hardware.org/?probe=59421fdcd1) | Nov 13, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [7f5b5d0c7a](https://linux-hardware.org/?probe=7f5b5d0c7a) | Nov 13, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [0e2bb34878](https://linux-hardware.org/?probe=0e2bb34878) | Nov 13, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [e9840b2a27](https://linux-hardware.org/?probe=e9840b2a27) | Nov 13, 2021 |
| SUPoX COMP... | B250A-BTC PRO               | Desktop     | [523a272559](https://linux-hardware.org/?probe=523a272559) | Nov 13, 2021 |
| Positivo      | V142N_4G                    | Notebook    | [6afdf02b96](https://linux-hardware.org/?probe=6afdf02b96) | Nov 13, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [2a98c5ad7b](https://linux-hardware.org/?probe=2a98c5ad7b) | Nov 13, 2021 |
| Samsung       | 550XDA                      | Notebook    | [69fe372895](https://linux-hardware.org/?probe=69fe372895) | Nov 12, 2021 |
| Samsung       | 550XDA                      | Notebook    | [61a4dbe6b6](https://linux-hardware.org/?probe=61a4dbe6b6) | Nov 12, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [7d4b51e485](https://linux-hardware.org/?probe=7d4b51e485) | Nov 12, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [3bbda8b194](https://linux-hardware.org/?probe=3bbda8b194) | Nov 12, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [5a9d6ba46e](https://linux-hardware.org/?probe=5a9d6ba46e) | Nov 12, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [4280461eea](https://linux-hardware.org/?probe=4280461eea) | Nov 12, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [e8879e98df](https://linux-hardware.org/?probe=e8879e98df) | Nov 12, 2021 |
| Pegatron      | 2AD2A                       | Desktop     | [5e251eb093](https://linux-hardware.org/?probe=5e251eb093) | Nov 12, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [0844d91e6b](https://linux-hardware.org/?probe=0844d91e6b) | Nov 12, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [de57dceaea](https://linux-hardware.org/?probe=de57dceaea) | Nov 12, 2021 |
| Samsung       | 370E4K                      | Notebook    | [f076dae1f9](https://linux-hardware.org/?probe=f076dae1f9) | Nov 12, 2021 |
| Intel         | H61                         | Desktop     | [dfd13362dc](https://linux-hardware.org/?probe=dfd13362dc) | Nov 12, 2021 |
| Dell          | 0F428D A00                  | Desktop     | [b676f351e0](https://linux-hardware.org/?probe=b676f351e0) | Nov 12, 2021 |
| Dell          | G5 5590                     | Notebook    | [5965461af0](https://linux-hardware.org/?probe=5965461af0) | Nov 12, 2021 |
| Dell          | G5 5590                     | Notebook    | [42c0049b50](https://linux-hardware.org/?probe=42c0049b50) | Nov 12, 2021 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [f806b413c5](https://linux-hardware.org/?probe=f806b413c5) | Nov 11, 2021 |
| Dell          | Latitude 3420               | Notebook    | [d58aa8a60c](https://linux-hardware.org/?probe=d58aa8a60c) | Nov 11, 2021 |
| Positivo      | POS-PQ45AU                  | Desktop     | [65766d4a35](https://linux-hardware.org/?probe=65766d4a35) | Nov 11, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [db067048aa](https://linux-hardware.org/?probe=db067048aa) | Nov 11, 2021 |
| Positivo      | POS-PQ45AU                  | Desktop     | [2118b60781](https://linux-hardware.org/?probe=2118b60781) | Nov 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [ae7c7124b8](https://linux-hardware.org/?probe=ae7c7124b8) | Nov 11, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [665fa7f7f2](https://linux-hardware.org/?probe=665fa7f7f2) | Nov 11, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [b0556699a5](https://linux-hardware.org/?probe=b0556699a5) | Nov 11, 2021 |
| MSI           | MS-7276                     | Desktop     | [c3450557eb](https://linux-hardware.org/?probe=c3450557eb) | Nov 11, 2021 |
| Samsung       | 370E4K                      | Notebook    | [a296e36d75](https://linux-hardware.org/?probe=a296e36d75) | Nov 11, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [0d059f1720](https://linux-hardware.org/?probe=0d059f1720) | Nov 11, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [d43bbede7b](https://linux-hardware.org/?probe=d43bbede7b) | Nov 11, 2021 |
| Dell          | G3 3579                     | Notebook    | [de2e21fc7d](https://linux-hardware.org/?probe=de2e21fc7d) | Nov 11, 2021 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [7b125e4ba6](https://linux-hardware.org/?probe=7b125e4ba6) | Nov 11, 2021 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [b11f112034](https://linux-hardware.org/?probe=b11f112034) | Nov 11, 2021 |
| Toshiba       | NA 1402                     | Notebook    | [a32237ae56](https://linux-hardware.org/?probe=a32237ae56) | Nov 11, 2021 |
| INTELBRAS     | IE-G31TM7                   | Desktop     | [1b854398a1](https://linux-hardware.org/?probe=1b854398a1) | Nov 11, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [694ece3b3f](https://linux-hardware.org/?probe=694ece3b3f) | Nov 11, 2021 |
| Dell          | Vostro 3480                 | Notebook    | [25a0c10009](https://linux-hardware.org/?probe=25a0c10009) | Nov 11, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [2bea44827f](https://linux-hardware.org/?probe=2bea44827f) | Nov 11, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [f5eba44619](https://linux-hardware.org/?probe=f5eba44619) | Nov 11, 2021 |
| Dell          | Vostro 3480                 | Notebook    | [a4167ceb73](https://linux-hardware.org/?probe=a4167ceb73) | Nov 11, 2021 |
| Intel         | H55                         | Desktop     | [7fc34476de](https://linux-hardware.org/?probe=7fc34476de) | Nov 10, 2021 |
| Intel         | H55                         | Desktop     | [0364a82ed9](https://linux-hardware.org/?probe=0364a82ed9) | Nov 10, 2021 |
| HP            | Pavilion 14                 | Notebook    | [1ed6c4bf90](https://linux-hardware.org/?probe=1ed6c4bf90) | Nov 10, 2021 |
| HP            | Pavilion 14                 | Notebook    | [4772b8de9b](https://linux-hardware.org/?probe=4772b8de9b) | Nov 10, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [5842108f8f](https://linux-hardware.org/?probe=5842108f8f) | Nov 10, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [3fad218eef](https://linux-hardware.org/?probe=3fad218eef) | Nov 10, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [d0f30ab5d2](https://linux-hardware.org/?probe=d0f30ab5d2) | Nov 10, 2021 |
| Acer          | AOD257                      | Notebook    | [f9faa5980e](https://linux-hardware.org/?probe=f9faa5980e) | Nov 10, 2021 |
| Acer          | AOD257                      | Notebook    | [3ecb22f1c0](https://linux-hardware.org/?probe=3ecb22f1c0) | Nov 10, 2021 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [544e219f00](https://linux-hardware.org/?probe=544e219f00) | Nov 10, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [d3b67380f0](https://linux-hardware.org/?probe=d3b67380f0) | Nov 10, 2021 |
| Toshiba       | STI NA 1401                 | Notebook    | [f1d5056f39](https://linux-hardware.org/?probe=f1d5056f39) | Nov 10, 2021 |
| ECS           | G41T-R3                     | Desktop     | [13f3059141](https://linux-hardware.org/?probe=13f3059141) | Nov 10, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [9a8f9d0864](https://linux-hardware.org/?probe=9a8f9d0864) | Nov 10, 2021 |
| Centrium      | C2018-H310CH5-M2            | Desktop     | [fef88de583](https://linux-hardware.org/?probe=fef88de583) | Nov 10, 2021 |
| Samsung       | 370E4K                      | Notebook    | [0e84b827bd](https://linux-hardware.org/?probe=0e84b827bd) | Nov 10, 2021 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [4427467cb5](https://linux-hardware.org/?probe=4427467cb5) | Nov 10, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [580bcd40a3](https://linux-hardware.org/?probe=580bcd40a3) | Nov 10, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [44cbd7d741](https://linux-hardware.org/?probe=44cbd7d741) | Nov 10, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [763f863266](https://linux-hardware.org/?probe=763f863266) | Nov 09, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [98e7d0e41c](https://linux-hardware.org/?probe=98e7d0e41c) | Nov 09, 2021 |
| Samsung       | 550XBE/350XBE               | Notebook    | [0597be3c31](https://linux-hardware.org/?probe=0597be3c31) | Nov 09, 2021 |
| Samsung       | 550XBE/350XBE               | Notebook    | [3dcebc581d](https://linux-hardware.org/?probe=3dcebc581d) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [bc08546f3f](https://linux-hardware.org/?probe=bc08546f3f) | Nov 09, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [32ffc2e9a5](https://linux-hardware.org/?probe=32ffc2e9a5) | Nov 09, 2021 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [ac46929783](https://linux-hardware.org/?probe=ac46929783) | Nov 09, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [6d46de50cb](https://linux-hardware.org/?probe=6d46de50cb) | Nov 09, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [5b51071e3f](https://linux-hardware.org/?probe=5b51071e3f) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [325cc5e53a](https://linux-hardware.org/?probe=325cc5e53a) | Nov 09, 2021 |
| Centrium      | C2018-H310CH5-M2            | Desktop     | [c06bb3991d](https://linux-hardware.org/?probe=c06bb3991d) | Nov 09, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [bf353c530a](https://linux-hardware.org/?probe=bf353c530a) | Nov 09, 2021 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | Notebook    | [fc450330af](https://linux-hardware.org/?probe=fc450330af) | Nov 09, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [2458e67cf5](https://linux-hardware.org/?probe=2458e67cf5) | Nov 09, 2021 |
| Samsung       | R430/R480/R440              | Notebook    | [04996a81f4](https://linux-hardware.org/?probe=04996a81f4) | Nov 08, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [4abd5bf630](https://linux-hardware.org/?probe=4abd5bf630) | Nov 08, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [49de67bc9e](https://linux-hardware.org/?probe=49de67bc9e) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [886c08185e](https://linux-hardware.org/?probe=886c08185e) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e141b2d36a](https://linux-hardware.org/?probe=e141b2d36a) | Nov 08, 2021 |
| HP            | Pavilion dv7                | Notebook    | [a19e73fd27](https://linux-hardware.org/?probe=a19e73fd27) | Nov 08, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [76d6e63da5](https://linux-hardware.org/?probe=76d6e63da5) | Nov 07, 2021 |
| ASUSTek       | K42F                        | Notebook    | [a0fc0b335f](https://linux-hardware.org/?probe=a0fc0b335f) | Nov 07, 2021 |
| Dell          | Inspiron 5490               | Notebook    | [abf9aa4a6c](https://linux-hardware.org/?probe=abf9aa4a6c) | Nov 07, 2021 |
| ABIT          | AX78                        | Desktop     | [3d56ae3738](https://linux-hardware.org/?probe=3d56ae3738) | Nov 06, 2021 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [4b98da95b0](https://linux-hardware.org/?probe=4b98da95b0) | Nov 06, 2021 |
| Positivo      | Mobile                      | Notebook    | [17b00479c7](https://linux-hardware.org/?probe=17b00479c7) | Nov 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [e6e813115f](https://linux-hardware.org/?probe=e6e813115f) | Nov 06, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [ec20c8a0b6](https://linux-hardware.org/?probe=ec20c8a0b6) | Nov 06, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [9c14e4d461](https://linux-hardware.org/?probe=9c14e4d461) | Nov 06, 2021 |
| Positivo      | W942SW_SW1                  | Notebook    | [3a8406ec90](https://linux-hardware.org/?probe=3a8406ec90) | Nov 06, 2021 |
| Lenovo        | G50-80 80R0                 | Notebook    | [a24e6b4e38](https://linux-hardware.org/?probe=a24e6b4e38) | Nov 06, 2021 |
| Lenovo        | G50-80 80R0                 | Notebook    | [94d7421e0c](https://linux-hardware.org/?probe=94d7421e0c) | Nov 06, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [effc5cc35d](https://linux-hardware.org/?probe=effc5cc35d) | Nov 06, 2021 |
| Dell          | G3 3590                     | Notebook    | [aa237dfc61](https://linux-hardware.org/?probe=aa237dfc61) | Nov 06, 2021 |
| Acer          | Aspire XXXX                 | Notebook    | [2e486fd092](https://linux-hardware.org/?probe=2e486fd092) | Nov 05, 2021 |
| Avell High... | A70 LIV                     | Notebook    | [b4d7b0e021](https://linux-hardware.org/?probe=b4d7b0e021) | Nov 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [348e52abbd](https://linux-hardware.org/?probe=348e52abbd) | Nov 05, 2021 |
| Huanan        | X99-BD4 V1.3                | Desktop     | [8e6aa7adcd](https://linux-hardware.org/?probe=8e6aa7adcd) | Nov 05, 2021 |
| Dell          | Inspiron 5547               | Notebook    | [6ebd71080f](https://linux-hardware.org/?probe=6ebd71080f) | Nov 04, 2021 |
| Dell          | Inspiron 5547               | Notebook    | [df08a534fa](https://linux-hardware.org/?probe=df08a534fa) | Nov 04, 2021 |
| HP            | Pavilion dv4                | Notebook    | [d37c348339](https://linux-hardware.org/?probe=d37c348339) | Nov 04, 2021 |
| ASRock        | H310CM-HG4                  | Desktop     | [89e6c09611](https://linux-hardware.org/?probe=89e6c09611) | Nov 04, 2021 |
| ASRock        | H310CM-HG4                  | Desktop     | [a66f4a5024](https://linux-hardware.org/?probe=a66f4a5024) | Nov 04, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [6b5f820af1](https://linux-hardware.org/?probe=6b5f820af1) | Nov 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [3e926045ee](https://linux-hardware.org/?probe=3e926045ee) | Nov 04, 2021 |
| Toshiba       | IS 1462B                    | Notebook    | [a5538db795](https://linux-hardware.org/?probe=a5538db795) | Nov 04, 2021 |
| Intel         | H61                         | Desktop     | [51f383b050](https://linux-hardware.org/?probe=51f383b050) | Nov 04, 2021 |
| Positivo      | Mobile                      | Notebook    | [36163a2c6c](https://linux-hardware.org/?probe=36163a2c6c) | Nov 04, 2021 |
| Intel         | H61                         | Desktop     | [062b4c247d](https://linux-hardware.org/?probe=062b4c247d) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [d7a405763d](https://linux-hardware.org/?probe=d7a405763d) | Nov 04, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [8724bc9bbf](https://linux-hardware.org/?probe=8724bc9bbf) | Nov 04, 2021 |
| Acer          | Aspire A514-54G             | Notebook    | [8908b4165a](https://linux-hardware.org/?probe=8908b4165a) | Nov 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [661a73d3c5](https://linux-hardware.org/?probe=661a73d3c5) | Nov 03, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [d6b72b3f64](https://linux-hardware.org/?probe=d6b72b3f64) | Nov 03, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [afcbc89406](https://linux-hardware.org/?probe=afcbc89406) | Nov 03, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [b5cdc4a164](https://linux-hardware.org/?probe=b5cdc4a164) | Nov 03, 2021 |
| LG Electro... | 22V280 FAB1                 | All in one  | [f57c7bbe97](https://linux-hardware.org/?probe=f57c7bbe97) | Nov 03, 2021 |
| Sony          | VGN-FZ480E                  | Notebook    | [715e1bfcd5](https://linux-hardware.org/?probe=715e1bfcd5) | Nov 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [2d26d5b578](https://linux-hardware.org/?probe=2d26d5b578) | Nov 02, 2021 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [3215c2037d](https://linux-hardware.org/?probe=3215c2037d) | Nov 02, 2021 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [e58e6144bf](https://linux-hardware.org/?probe=e58e6144bf) | Nov 02, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [8326fcc8b9](https://linux-hardware.org/?probe=8326fcc8b9) | Nov 02, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [f7096b9069](https://linux-hardware.org/?probe=f7096b9069) | Nov 02, 2021 |
| Intel         | H61                         | Desktop     | [c3f5ace673](https://linux-hardware.org/?probe=c3f5ace673) | Nov 02, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1a8d172b1a](https://linux-hardware.org/?probe=1a8d172b1a) | Nov 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1b665c64fd](https://linux-hardware.org/?probe=1b665c64fd) | Nov 02, 2021 |
| Positivo      | C464C                       | Convertible | [9e96f56fdb](https://linux-hardware.org/?probe=9e96f56fdb) | Nov 02, 2021 |
| ECS           | A880GM-M6                   | Desktop     | [379db33055](https://linux-hardware.org/?probe=379db33055) | Nov 02, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [b15e80cab7](https://linux-hardware.org/?probe=b15e80cab7) | Nov 01, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [754d944557](https://linux-hardware.org/?probe=754d944557) | Nov 01, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [8c7226d96a](https://linux-hardware.org/?probe=8c7226d96a) | Nov 01, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [f7fa163f1f](https://linux-hardware.org/?probe=f7fa163f1f) | Nov 01, 2021 |
| Dell          | Latitude E6430              | Notebook    | [d35b1ab829](https://linux-hardware.org/?probe=d35b1ab829) | Nov 01, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [9bb9999a3a](https://linux-hardware.org/?probe=9bb9999a3a) | Nov 01, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [2d4b614d02](https://linux-hardware.org/?probe=2d4b614d02) | Nov 01, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [4faa88a423](https://linux-hardware.org/?probe=4faa88a423) | Nov 01, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [1cc5699354](https://linux-hardware.org/?probe=1cc5699354) | Nov 01, 2021 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [14e8c3fcb9](https://linux-hardware.org/?probe=14e8c3fcb9) | Nov 01, 2021 |
| ASRock        | H110M-HG4                   | Desktop     | [763eb51f47](https://linux-hardware.org/?probe=763eb51f47) | Nov 01, 2021 |
| HOUTER        | IPMH61R1                    | Desktop     | [ca910cfd3d](https://linux-hardware.org/?probe=ca910cfd3d) | Nov 01, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [807a8b23ce](https://linux-hardware.org/?probe=807a8b23ce) | Nov 01, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [8182230d1d](https://linux-hardware.org/?probe=8182230d1d) | Nov 01, 2021 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [c9e815f4f5](https://linux-hardware.org/?probe=c9e815f4f5) | Nov 01, 2021 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [42cd4d28bd](https://linux-hardware.org/?probe=42cd4d28bd) | Nov 01, 2021 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [24974be67e](https://linux-hardware.org/?probe=24974be67e) | Oct 31, 2021 |
| Standard      | AHV                         | Notebook    | [a960753588](https://linux-hardware.org/?probe=a960753588) | Oct 31, 2021 |
| Standard      | AHV                         | Notebook    | [1478edca39](https://linux-hardware.org/?probe=1478edca39) | Oct 31, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [491d1a96cc](https://linux-hardware.org/?probe=491d1a96cc) | Oct 31, 2021 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [324f6e5fad](https://linux-hardware.org/?probe=324f6e5fad) | Oct 31, 2021 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [a6574237d6](https://linux-hardware.org/?probe=a6574237d6) | Oct 31, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [0f2394b49d](https://linux-hardware.org/?probe=0f2394b49d) | Oct 31, 2021 |
| LG Electro... | 22V240 FAB3                 | All in one  | [314abb1ff1](https://linux-hardware.org/?probe=314abb1ff1) | Oct 31, 2021 |
| Toshiba       | IS 1412                     | Notebook    | [c0faa178a2](https://linux-hardware.org/?probe=c0faa178a2) | Oct 31, 2021 |
| Intel         | B75 V124                    | Desktop     | [c2d53c8118](https://linux-hardware.org/?probe=c2d53c8118) | Oct 31, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [3e3fea2e0f](https://linux-hardware.org/?probe=3e3fea2e0f) | Oct 30, 2021 |
| Dell          | Inspiron 5421               | Notebook    | [d70e2b74d0](https://linux-hardware.org/?probe=d70e2b74d0) | Oct 30, 2021 |
| Dell          | Inspiron 5421               | Notebook    | [d4d3ebf711](https://linux-hardware.org/?probe=d4d3ebf711) | Oct 30, 2021 |
| Samsung       | 270E5G/270E5U               | Notebook    | [31ae4d8fda](https://linux-hardware.org/?probe=31ae4d8fda) | Oct 30, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [5434b808b5](https://linux-hardware.org/?probe=5434b808b5) | Oct 30, 2021 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [9bd1a96f2e](https://linux-hardware.org/?probe=9bd1a96f2e) | Oct 30, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [bc9dc107d1](https://linux-hardware.org/?probe=bc9dc107d1) | Oct 30, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [24fe21040d](https://linux-hardware.org/?probe=24fe21040d) | Oct 30, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [bb6de8b3e0](https://linux-hardware.org/?probe=bb6de8b3e0) | Oct 30, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [8bd0954be7](https://linux-hardware.org/?probe=8bd0954be7) | Oct 30, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [3914304341](https://linux-hardware.org/?probe=3914304341) | Oct 30, 2021 |
| Multilaser    | PC112                       | Convertible | [aa88177e76](https://linux-hardware.org/?probe=aa88177e76) | Oct 30, 2021 |
| Lenovo        | G480 20149                  | Notebook    | [ee0a6fc9ca](https://linux-hardware.org/?probe=ee0a6fc9ca) | Oct 30, 2021 |
| Sony          | SVF15213CBB                 | Notebook    | [1d79ed8874](https://linux-hardware.org/?probe=1d79ed8874) | Oct 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [eecc1408e7](https://linux-hardware.org/?probe=eecc1408e7) | Oct 29, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [f2d60e0b6a](https://linux-hardware.org/?probe=f2d60e0b6a) | Oct 29, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [388caf40fe](https://linux-hardware.org/?probe=388caf40fe) | Oct 29, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [798a613fa7](https://linux-hardware.org/?probe=798a613fa7) | Oct 29, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [88286c36e9](https://linux-hardware.org/?probe=88286c36e9) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [6b471bc42d](https://linux-hardware.org/?probe=6b471bc42d) | Oct 29, 2021 |
| Dell          | Latitude 7420               | Notebook    | [20266b5994](https://linux-hardware.org/?probe=20266b5994) | Oct 29, 2021 |
| ASUSTek       | M2N-SLI                     | Desktop     | [c31d447213](https://linux-hardware.org/?probe=c31d447213) | Oct 29, 2021 |
| Dell          | System XPS L502X            | Notebook    | [8f052d2acb](https://linux-hardware.org/?probe=8f052d2acb) | Oct 29, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [1be6c8dc87](https://linux-hardware.org/?probe=1be6c8dc87) | Oct 29, 2021 |
| Intel         | H61                         | Desktop     | [89c4e2a423](https://linux-hardware.org/?probe=89c4e2a423) | Oct 29, 2021 |
| Digitron      | G31T-M7                     | Desktop     | [8e02bb30bc](https://linux-hardware.org/?probe=8e02bb30bc) | Oct 29, 2021 |
| Unknown       | Phitronics G41-M3           | Desktop     | [16c678627e](https://linux-hardware.org/?probe=16c678627e) | Oct 29, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [7463facb20](https://linux-hardware.org/?probe=7463facb20) | Oct 29, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [270d4c1d21](https://linux-hardware.org/?probe=270d4c1d21) | Oct 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [f1941a09e5](https://linux-hardware.org/?probe=f1941a09e5) | Oct 28, 2021 |
| Toshiba       | STI NA 1401                 | Notebook    | [c8075f4483](https://linux-hardware.org/?probe=c8075f4483) | Oct 28, 2021 |
| Dell          | Vostro 14-5480              | Notebook    | [5d323af087](https://linux-hardware.org/?probe=5d323af087) | Oct 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [31c9d5b545](https://linux-hardware.org/?probe=31c9d5b545) | Oct 28, 2021 |
| Dell          | Vostro 14-5480              | Notebook    | [e2c5f1bdea](https://linux-hardware.org/?probe=e2c5f1bdea) | Oct 28, 2021 |
| HP            | 3047h                       | Desktop     | [eedab3769c](https://linux-hardware.org/?probe=eedab3769c) | Oct 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [89afa44bcf](https://linux-hardware.org/?probe=89afa44bcf) | Oct 28, 2021 |
| Unknown       | Phitronics H55-M            | Desktop     | [df6d3817cb](https://linux-hardware.org/?probe=df6d3817cb) | Oct 28, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [d10e4364a0](https://linux-hardware.org/?probe=d10e4364a0) | Oct 27, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [27d2383b87](https://linux-hardware.org/?probe=27d2383b87) | Oct 27, 2021 |
| BESSTAR Te... | X400                        | Notebook    | [9cfc0bb300](https://linux-hardware.org/?probe=9cfc0bb300) | Oct 27, 2021 |
| Dell          | 05CNYF A01                  | Desktop     | [95530db3a8](https://linux-hardware.org/?probe=95530db3a8) | Oct 27, 2021 |
| DIGIBOARD     | G41M-S                      | Desktop     | [4ec5cdcbd1](https://linux-hardware.org/?probe=4ec5cdcbd1) | Oct 27, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| Intel         | H55                         | Desktop     | [b32e64a698](https://linux-hardware.org/?probe=b32e64a698) | Oct 27, 2021 |
| Pegatron      | 2A99                        | Desktop     | [29fd6eae29](https://linux-hardware.org/?probe=29fd6eae29) | Oct 27, 2021 |
| Dell          | Vostro 3400                 | Notebook    | [608e1f800d](https://linux-hardware.org/?probe=608e1f800d) | Oct 27, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [f3400508fb](https://linux-hardware.org/?probe=f3400508fb) | Oct 27, 2021 |
| Lenovo        | ThinkPad T480 20L6SCWK00    | Notebook    | [feb7f2a285](https://linux-hardware.org/?probe=feb7f2a285) | Oct 27, 2021 |
| Sony          | VGN-FZ480E                  | Notebook    | [2af35086e4](https://linux-hardware.org/?probe=2af35086e4) | Oct 27, 2021 |
| ASRock        | B360M Performance           | Desktop     | [2ff008a28d](https://linux-hardware.org/?probe=2ff008a28d) | Oct 26, 2021 |
| Sony          | VGN-FZ480E                  | Notebook    | [83564443b9](https://linux-hardware.org/?probe=83564443b9) | Oct 26, 2021 |
| MSI           | A320M GAMING PRO            | Desktop     | [599dfb26a8](https://linux-hardware.org/?probe=599dfb26a8) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [2ab4ca2f07](https://linux-hardware.org/?probe=2ab4ca2f07) | Oct 26, 2021 |
| Intel         | H55                         | Desktop     | [1b80ff1b5a](https://linux-hardware.org/?probe=1b80ff1b5a) | Oct 26, 2021 |
| Dell          | 0D441T A01                  | Desktop     | [51d64c0798](https://linux-hardware.org/?probe=51d64c0798) | Oct 26, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [e348a818bd](https://linux-hardware.org/?probe=e348a818bd) | Oct 26, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [ac77c040ba](https://linux-hardware.org/?probe=ac77c040ba) | Oct 26, 2021 |
| Dell          | Inspiron 5537               | Notebook    | [e2d02f71bc](https://linux-hardware.org/?probe=e2d02f71bc) | Oct 26, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [c01fa4b013](https://linux-hardware.org/?probe=c01fa4b013) | Oct 26, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0dfe108c69](https://linux-hardware.org/?probe=0dfe108c69) | Oct 26, 2021 |
| HP            | Unknown                     | Notebook    | [f31ac36b11](https://linux-hardware.org/?probe=f31ac36b11) | Oct 25, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [df7b7986f5](https://linux-hardware.org/?probe=df7b7986f5) | Oct 25, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [d9e192761c](https://linux-hardware.org/?probe=d9e192761c) | Oct 25, 2021 |
| Acer          | AO722                       | Notebook    | [832ca83fcd](https://linux-hardware.org/?probe=832ca83fcd) | Oct 25, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [428aa9470f](https://linux-hardware.org/?probe=428aa9470f) | Oct 25, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | Notebook    | [d3720f9145](https://linux-hardware.org/?probe=d3720f9145) | Oct 25, 2021 |
| Dell          | Latitude 3420               | Notebook    | [e330d77b1f](https://linux-hardware.org/?probe=e330d77b1f) | Oct 25, 2021 |
| HP            | Pavilion 14                 | Notebook    | [e12e55583d](https://linux-hardware.org/?probe=e12e55583d) | Oct 25, 2021 |
| ASUSTek       | X555LF                      | Notebook    | [984c7c6778](https://linux-hardware.org/?probe=984c7c6778) | Oct 25, 2021 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [a1cf5282ba](https://linux-hardware.org/?probe=a1cf5282ba) | Oct 25, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [39348a932e](https://linux-hardware.org/?probe=39348a932e) | Oct 25, 2021 |
| Dell          | System XPS L502X            | Notebook    | [3397631304](https://linux-hardware.org/?probe=3397631304) | Oct 25, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [5b06944051](https://linux-hardware.org/?probe=5b06944051) | Oct 25, 2021 |
| Compaq        | Presario CQ-25              | Notebook    | [ff46dc73d4](https://linux-hardware.org/?probe=ff46dc73d4) | Oct 25, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [bcc833ac3c](https://linux-hardware.org/?probe=bcc833ac3c) | Oct 25, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [6ad3cf44dc](https://linux-hardware.org/?probe=6ad3cf44dc) | Oct 24, 2021 |
| Positivo      | C14CR21                     | Notebook    | [9f3a43bc94](https://linux-hardware.org/?probe=9f3a43bc94) | Oct 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [8e4a94423a](https://linux-hardware.org/?probe=8e4a94423a) | Oct 24, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [1e8a2612aa](https://linux-hardware.org/?probe=1e8a2612aa) | Oct 24, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [f901b7640e](https://linux-hardware.org/?probe=f901b7640e) | Oct 24, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [fdbf1831d8](https://linux-hardware.org/?probe=fdbf1831d8) | Oct 24, 2021 |
| Intel         | X79 V1.x                    | Desktop     | [0a06d56c4d](https://linux-hardware.org/?probe=0a06d56c4d) | Oct 24, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [a81bf18dd8](https://linux-hardware.org/?probe=a81bf18dd8) | Oct 24, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [217767cb69](https://linux-hardware.org/?probe=217767cb69) | Oct 23, 2021 |
| Acer          | Acadia V1.42                | Notebook    | [01122f69f4](https://linux-hardware.org/?probe=01122f69f4) | Oct 23, 2021 |
| Dell          | Latitude 3420               | Notebook    | [ed2568dfa1](https://linux-hardware.org/?probe=ed2568dfa1) | Oct 23, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [09f6196e70](https://linux-hardware.org/?probe=09f6196e70) | Oct 23, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [557421f62e](https://linux-hardware.org/?probe=557421f62e) | Oct 23, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [f5703d2f8f](https://linux-hardware.org/?probe=f5703d2f8f) | Oct 23, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [af65c254d8](https://linux-hardware.org/?probe=af65c254d8) | Oct 23, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [48db1afdd3](https://linux-hardware.org/?probe=48db1afdd3) | Oct 23, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6f89504680](https://linux-hardware.org/?probe=6f89504680) | Oct 23, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [80a124f9cd](https://linux-hardware.org/?probe=80a124f9cd) | Oct 23, 2021 |
| HP            | Pavilion dv4-1120br         | Notebook    | [10e4cb83a8](https://linux-hardware.org/?probe=10e4cb83a8) | Oct 23, 2021 |
| Dell          | Latitude 3400               | Notebook    | [7f519c2721](https://linux-hardware.org/?probe=7f519c2721) | Oct 23, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8d8e23af16](https://linux-hardware.org/?probe=8d8e23af16) | Oct 23, 2021 |
| Acer          | Acadia V1.42                | Notebook    | [11b24034fc](https://linux-hardware.org/?probe=11b24034fc) | Oct 23, 2021 |
| Acer          | Nitro AN517-51              | Notebook    | [271c2188cb](https://linux-hardware.org/?probe=271c2188cb) | Oct 23, 2021 |
| Dell          | Inspiron 3437               | Notebook    | [5c433f99b1](https://linux-hardware.org/?probe=5c433f99b1) | Oct 22, 2021 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [040d7f611e](https://linux-hardware.org/?probe=040d7f611e) | Oct 22, 2021 |
| Positivo      | S14BW01                     | Notebook    | [6b146fc86e](https://linux-hardware.org/?probe=6b146fc86e) | Oct 22, 2021 |
| Dell          | Inspiron N4050              | Notebook    | [970402d06d](https://linux-hardware.org/?probe=970402d06d) | Oct 22, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [f06d6b9f20](https://linux-hardware.org/?probe=f06d6b9f20) | Oct 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0ec4e1e668](https://linux-hardware.org/?probe=0ec4e1e668) | Oct 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [88f5592418](https://linux-hardware.org/?probe=88f5592418) | Oct 22, 2021 |
| HP            | Pavilion g4                 | Notebook    | [3b86797a83](https://linux-hardware.org/?probe=3b86797a83) | Oct 22, 2021 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [967d1d28ce](https://linux-hardware.org/?probe=967d1d28ce) | Oct 22, 2021 |
| MSI           | G41M-S01                    | Desktop     | [7abf5c3ae6](https://linux-hardware.org/?probe=7abf5c3ae6) | Oct 22, 2021 |
| Dell          | Inspiron N4050              | Notebook    | [85a514f622](https://linux-hardware.org/?probe=85a514f622) | Oct 22, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [0278eaa13a](https://linux-hardware.org/?probe=0278eaa13a) | Oct 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [19f7ba4a63](https://linux-hardware.org/?probe=19f7ba4a63) | Oct 22, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [0be91c158b](https://linux-hardware.org/?probe=0be91c158b) | Oct 22, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [8cc27e0d4e](https://linux-hardware.org/?probe=8cc27e0d4e) | Oct 21, 2021 |
| MSI           | G41M-S01                    | Desktop     | [34e44b9df8](https://linux-hardware.org/?probe=34e44b9df8) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [703d0f2090](https://linux-hardware.org/?probe=703d0f2090) | Oct 21, 2021 |
| Intel         | H61                         | Desktop     | [2e8854724e](https://linux-hardware.org/?probe=2e8854724e) | Oct 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [3fe556cde3](https://linux-hardware.org/?probe=3fe556cde3) | Oct 21, 2021 |
| DIGIBOARD     | G41M-S                      | Desktop     | [bb3db7dba8](https://linux-hardware.org/?probe=bb3db7dba8) | Oct 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [0413ebb72c](https://linux-hardware.org/?probe=0413ebb72c) | Oct 21, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [1ef866386c](https://linux-hardware.org/?probe=1ef866386c) | Oct 21, 2021 |
| HP            | Pavilion dm1                | Notebook    | [1408d15ece](https://linux-hardware.org/?probe=1408d15ece) | Oct 21, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [5153e99cce](https://linux-hardware.org/?probe=5153e99cce) | Oct 21, 2021 |
| Samsung       | 900X5T                      | Notebook    | [4f39e11826](https://linux-hardware.org/?probe=4f39e11826) | Oct 21, 2021 |
| Samsung       | 900X5T                      | Notebook    | [3e27247540](https://linux-hardware.org/?probe=3e27247540) | Oct 21, 2021 |
| Lenovo        | G470 20078                  | Notebook    | [394cdd726f](https://linux-hardware.org/?probe=394cdd726f) | Oct 21, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [cd748cc7d4](https://linux-hardware.org/?probe=cd748cc7d4) | Oct 20, 2021 |
| Lenovo        | G470 20078                  | Notebook    | [3ad2e537e7](https://linux-hardware.org/?probe=3ad2e537e7) | Oct 20, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [25cfcf0ca1](https://linux-hardware.org/?probe=25cfcf0ca1) | Oct 20, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [c008aa97e0](https://linux-hardware.org/?probe=c008aa97e0) | Oct 20, 2021 |
| Unknown       | Phitronics G41-M3           | Desktop     | [a6ccedb5bd](https://linux-hardware.org/?probe=a6ccedb5bd) | Oct 20, 2021 |
| Unknown       | Phitronics G41-M3           | Desktop     | [fbe886aee7](https://linux-hardware.org/?probe=fbe886aee7) | Oct 20, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [e00a2deae3](https://linux-hardware.org/?probe=e00a2deae3) | Oct 20, 2021 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [2c6cfc5b5a](https://linux-hardware.org/?probe=2c6cfc5b5a) | Oct 20, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [b66eb36016](https://linux-hardware.org/?probe=b66eb36016) | Oct 20, 2021 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [632f3122a2](https://linux-hardware.org/?probe=632f3122a2) | Oct 20, 2021 |
| Lenovo        | IdeaPad Flex14 20308        | Notebook    | [33d071cbec](https://linux-hardware.org/?probe=33d071cbec) | Oct 20, 2021 |
| Dell          | Inspiron 5481               | Notebook    | [beb9349c6e](https://linux-hardware.org/?probe=beb9349c6e) | Oct 20, 2021 |
| Intel         | W7650                       | Notebook    | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [17baa8dc0e](https://linux-hardware.org/?probe=17baa8dc0e) | Oct 19, 2021 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [03b2c2e1af](https://linux-hardware.org/?probe=03b2c2e1af) | Oct 19, 2021 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [bc7ed68945](https://linux-hardware.org/?probe=bc7ed68945) | Oct 19, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [f1f5f6bf59](https://linux-hardware.org/?probe=f1f5f6bf59) | Oct 19, 2021 |
| Digiboard     | MPxx                        | Desktop     | [138c2ef6fb](https://linux-hardware.org/?probe=138c2ef6fb) | Oct 19, 2021 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [3475f6407e](https://linux-hardware.org/?probe=3475f6407e) | Oct 19, 2021 |
| MSI           | H97M-G43                    | Desktop     | [035fce3bfc](https://linux-hardware.org/?probe=035fce3bfc) | Oct 19, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [a174c1781d](https://linux-hardware.org/?probe=a174c1781d) | Oct 19, 2021 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [310f5898f3](https://linux-hardware.org/?probe=310f5898f3) | Oct 18, 2021 |
| Toshiba       | STI NA 1401                 | Notebook    | [6e93fdc0c9](https://linux-hardware.org/?probe=6e93fdc0c9) | Oct 18, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [a4bb8bffd7](https://linux-hardware.org/?probe=a4bb8bffd7) | Oct 18, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3aa7fc8e09](https://linux-hardware.org/?probe=3aa7fc8e09) | Oct 18, 2021 |
| Login Info... | LOG-MB47II7                 | Notebook    | [b277a4e2db](https://linux-hardware.org/?probe=b277a4e2db) | Oct 18, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [eff4abf74e](https://linux-hardware.org/?probe=eff4abf74e) | Oct 18, 2021 |
| Lenovo        | ThinkPad E490 20N9001FBR    | Notebook    | [7c1d310221](https://linux-hardware.org/?probe=7c1d310221) | Oct 18, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [374e69046b](https://linux-hardware.org/?probe=374e69046b) | Oct 18, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [f2a60e237e](https://linux-hardware.org/?probe=f2a60e237e) | Oct 18, 2021 |
| Positivo      | C14CR21                     | Notebook    | [ef9930e6f9](https://linux-hardware.org/?probe=ef9930e6f9) | Oct 17, 2021 |
| Biostar       | A320MH                      | Desktop     | [3141b2e460](https://linux-hardware.org/?probe=3141b2e460) | Oct 17, 2021 |
| Positivo      | C14CR21                     | Notebook    | [942958ab88](https://linux-hardware.org/?probe=942958ab88) | Oct 17, 2021 |
| ASRock        | N68-S3 FX                   | Desktop     | [090662dcd6](https://linux-hardware.org/?probe=090662dcd6) | Oct 17, 2021 |
| Intel         | H55                         | Desktop     | [919e9c3fcf](https://linux-hardware.org/?probe=919e9c3fcf) | Oct 17, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [66d1015de7](https://linux-hardware.org/?probe=66d1015de7) | Oct 17, 2021 |
| Dell          | G3 3579                     | Notebook    | [28d725057f](https://linux-hardware.org/?probe=28d725057f) | Oct 17, 2021 |
| Dell          | G3 3579                     | Notebook    | [a81715d288](https://linux-hardware.org/?probe=a81715d288) | Oct 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [383e24fcf5](https://linux-hardware.org/?probe=383e24fcf5) | Oct 17, 2021 |
| Positivo      | POS-EIB75CO POSITIVO        | Desktop     | [73e914eac2](https://linux-hardware.org/?probe=73e914eac2) | Oct 17, 2021 |
| ECS           | G41T-M7                     | Desktop     | [2ea8e79aa2](https://linux-hardware.org/?probe=2ea8e79aa2) | Oct 17, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [baebf9648a](https://linux-hardware.org/?probe=baebf9648a) | Oct 17, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [a306e628c3](https://linux-hardware.org/?probe=a306e628c3) | Oct 17, 2021 |
| ECS           | G41T-M7                     | Desktop     | [87f5a1e02f](https://linux-hardware.org/?probe=87f5a1e02f) | Oct 17, 2021 |
| Samsung       | 370E4K                      | Notebook    | [e96252931e](https://linux-hardware.org/?probe=e96252931e) | Oct 17, 2021 |
| Biostar       | A55MLC2                     | Desktop     | [1410ad4172](https://linux-hardware.org/?probe=1410ad4172) | Oct 17, 2021 |
| 16216-BM-2... | Z97M GAMING 14655-BV-171... | Desktop     | [d6e1b47b17](https://linux-hardware.org/?probe=d6e1b47b17) | Oct 16, 2021 |
| Samsung       | 550XDA                      | Notebook    | [b4026018fe](https://linux-hardware.org/?probe=b4026018fe) | Oct 16, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [29575a20e2](https://linux-hardware.org/?probe=29575a20e2) | Oct 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [397c4c2aca](https://linux-hardware.org/?probe=397c4c2aca) | Oct 16, 2021 |
| LG Electro... | A550-C.BE55P1               | Notebook    | [cac46f39f4](https://linux-hardware.org/?probe=cac46f39f4) | Oct 16, 2021 |
| Foxconn       | TPS01                       | Desktop     | [a967246bfb](https://linux-hardware.org/?probe=a967246bfb) | Oct 16, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [ec55317836](https://linux-hardware.org/?probe=ec55317836) | Oct 16, 2021 |
| Positivo      | C14CR21                     | Notebook    | [07aaf675fd](https://linux-hardware.org/?probe=07aaf675fd) | Oct 16, 2021 |
| Unknown       | Unknown                     | Notebook    | [3233e1293c](https://linux-hardware.org/?probe=3233e1293c) | Oct 15, 2021 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [044227e4ba](https://linux-hardware.org/?probe=044227e4ba) | Oct 15, 2021 |
| ASRock        | H110M-HG4                   | Desktop     | [8b488cbe13](https://linux-hardware.org/?probe=8b488cbe13) | Oct 15, 2021 |
| ASUSTek       | Z550SA                      | Notebook    | [9728ec8a83](https://linux-hardware.org/?probe=9728ec8a83) | Oct 15, 2021 |
| Acer          | Nitro AN517-51              | Notebook    | [a6d2f51c46](https://linux-hardware.org/?probe=a6d2f51c46) | Oct 15, 2021 |
| OEM           | I41SI                       | Notebook    | [814ebd5dd1](https://linux-hardware.org/?probe=814ebd5dd1) | Oct 15, 2021 |
| LG Electro... | U460-G.BG31P1               | Notebook    | [082c923ad8](https://linux-hardware.org/?probe=082c923ad8) | Oct 15, 2021 |
| LG Electro... | U460-G.BG31P1               | Notebook    | [a2979e1c5f](https://linux-hardware.org/?probe=a2979e1c5f) | Oct 15, 2021 |
| Positivo      | S14SL01                     | Notebook    | [5d92191da4](https://linux-hardware.org/?probe=5d92191da4) | Oct 15, 2021 |
| Gigabyte      | H310M H                     | Desktop     | [71ec24f0bb](https://linux-hardware.org/?probe=71ec24f0bb) | Oct 15, 2021 |
| Philco        | DTC-A55                     | Desktop     | [180d616afd](https://linux-hardware.org/?probe=180d616afd) | Oct 15, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [39495897d7](https://linux-hardware.org/?probe=39495897d7) | Oct 15, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [b41a6353ea](https://linux-hardware.org/?probe=b41a6353ea) | Oct 15, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [eec2fcfa3b](https://linux-hardware.org/?probe=eec2fcfa3b) | Oct 15, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [3c24201057](https://linux-hardware.org/?probe=3c24201057) | Oct 15, 2021 |
| DIGIBOARD     | G41M-S                      | Desktop     | [4bba0c24db](https://linux-hardware.org/?probe=4bba0c24db) | Oct 14, 2021 |
| HP            | 09E8h                       | Desktop     | [7faca26f13](https://linux-hardware.org/?probe=7faca26f13) | Oct 14, 2021 |
| HP            | 09E8h                       | Desktop     | [5013f5686b](https://linux-hardware.org/?probe=5013f5686b) | Oct 14, 2021 |
| Lenovo        | 3000 IPM31                  | Desktop     | [10c008ff82](https://linux-hardware.org/?probe=10c008ff82) | Oct 14, 2021 |
| Lenovo        | ThinkPad E490 20N9CTO1WW    | Notebook    | [69243ba50f](https://linux-hardware.org/?probe=69243ba50f) | Oct 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [f8f343d12b](https://linux-hardware.org/?probe=f8f343d12b) | Oct 14, 2021 |
| Dell          | G3 3590                     | Notebook    | [3165d77a8e](https://linux-hardware.org/?probe=3165d77a8e) | Oct 14, 2021 |
| Positivo      | Smash3                      | Notebook    | [3c9fe4acb8](https://linux-hardware.org/?probe=3c9fe4acb8) | Oct 14, 2021 |
| Positivo      | Smash3                      | Notebook    | [ab60c4e746](https://linux-hardware.org/?probe=ab60c4e746) | Oct 14, 2021 |
| Huanan        | X99-TF V2.0                 | Desktop     | [f7a082bf52](https://linux-hardware.org/?probe=f7a082bf52) | Oct 14, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [a58944640b](https://linux-hardware.org/?probe=a58944640b) | Oct 14, 2021 |
| Intel         | H61                         | Desktop     | [3f8d650142](https://linux-hardware.org/?probe=3f8d650142) | Oct 14, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [a4834f8957](https://linux-hardware.org/?probe=a4834f8957) | Oct 13, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [0175c5181a](https://linux-hardware.org/?probe=0175c5181a) | Oct 13, 2021 |
| HP            | ProBook 445 G7 Notebook ... | Notebook    | [83045a6763](https://linux-hardware.org/?probe=83045a6763) | Oct 13, 2021 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [8ada30dc90](https://linux-hardware.org/?probe=8ada30dc90) | Oct 13, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [4121b728e7](https://linux-hardware.org/?probe=4121b728e7) | Oct 13, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [125473d905](https://linux-hardware.org/?probe=125473d905) | Oct 13, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [eeb6c7bd08](https://linux-hardware.org/?probe=eeb6c7bd08) | Oct 13, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [77065a0cd8](https://linux-hardware.org/?probe=77065a0cd8) | Oct 13, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [b241b611f1](https://linux-hardware.org/?probe=b241b611f1) | Oct 13, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [85be06c49d](https://linux-hardware.org/?probe=85be06c49d) | Oct 13, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [a8e5248d3d](https://linux-hardware.org/?probe=a8e5248d3d) | Oct 13, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [dc154fe7c0](https://linux-hardware.org/?probe=dc154fe7c0) | Oct 13, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [589e47b071](https://linux-hardware.org/?probe=589e47b071) | Oct 13, 2021 |
| Positivo      | S14BW01                     | Notebook    | [0f03880266](https://linux-hardware.org/?probe=0f03880266) | Oct 13, 2021 |
| PCWare        | IPX1800E2                   | Desktop     | [509f6b0c67](https://linux-hardware.org/?probe=509f6b0c67) | Oct 13, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [82498fffc2](https://linux-hardware.org/?probe=82498fffc2) | Oct 12, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [60eb0f3782](https://linux-hardware.org/?probe=60eb0f3782) | Oct 12, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [60b294879d](https://linux-hardware.org/?probe=60b294879d) | Oct 12, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [5caa8b5a71](https://linux-hardware.org/?probe=5caa8b5a71) | Oct 12, 2021 |
| MSI           | MS-7267                     | Desktop     | [3d1ee9b7d7](https://linux-hardware.org/?probe=3d1ee9b7d7) | Oct 12, 2021 |
| MSI           | MS-7267                     | Desktop     | [48649b4ed6](https://linux-hardware.org/?probe=48649b4ed6) | Oct 12, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [0a00ed81de](https://linux-hardware.org/?probe=0a00ed81de) | Oct 12, 2021 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [ab28d0c9d9](https://linux-hardware.org/?probe=ab28d0c9d9) | Oct 12, 2021 |
| Acer          | Aspire A315-42G             | Notebook    | [5b667bff5d](https://linux-hardware.org/?probe=5b667bff5d) | Oct 12, 2021 |
| MSI           | H97M-G43                    | Desktop     | [1bff3500a0](https://linux-hardware.org/?probe=1bff3500a0) | Oct 12, 2021 |
| MSI           | H97M-G43                    | Desktop     | [ccfb78add4](https://linux-hardware.org/?probe=ccfb78add4) | Oct 12, 2021 |
| HP            | Pavilion dv2000 (RP408UA... | Notebook    | [31a42ed2b6](https://linux-hardware.org/?probe=31a42ed2b6) | Oct 12, 2021 |
| Avell High... | A60 MUV                     | Notebook    | [e6b31a5408](https://linux-hardware.org/?probe=e6b31a5408) | Oct 12, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [6476999787](https://linux-hardware.org/?probe=6476999787) | Oct 12, 2021 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [cf61a35aa1](https://linux-hardware.org/?probe=cf61a35aa1) | Oct 12, 2021 |
| ASUSTek       | Z550MA                      | Notebook    | [dc911b6ef4](https://linux-hardware.org/?probe=dc911b6ef4) | Oct 12, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [edd8f01f22](https://linux-hardware.org/?probe=edd8f01f22) | Oct 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fe78f0e87c](https://linux-hardware.org/?probe=fe78f0e87c) | Oct 12, 2021 |
| Dell          | G3 3590                     | Notebook    | [4c5db870d5](https://linux-hardware.org/?probe=4c5db870d5) | Oct 12, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [61a2a7f494](https://linux-hardware.org/?probe=61a2a7f494) | Oct 12, 2021 |
| Unknown       | GSUO H61V10C                | Desktop     | [c3a23ae9fb](https://linux-hardware.org/?probe=c3a23ae9fb) | Oct 12, 2021 |
| Unknown       | GSUO H61V10C                | Desktop     | [55fe5f3dd1](https://linux-hardware.org/?probe=55fe5f3dd1) | Oct 12, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9dc8d76ce0](https://linux-hardware.org/?probe=9dc8d76ce0) | Oct 12, 2021 |
| Dell          | Inspiron One 2320           | All in one  | [81048aabf5](https://linux-hardware.org/?probe=81048aabf5) | Oct 11, 2021 |
| Positivo      | S14BW01                     | Notebook    | [0a725f31b4](https://linux-hardware.org/?probe=0a725f31b4) | Oct 11, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [5dd4cb8920](https://linux-hardware.org/?probe=5dd4cb8920) | Oct 11, 2021 |
| ASUSTek       | X510UR                      | Notebook    | [40a5b25871](https://linux-hardware.org/?probe=40a5b25871) | Oct 11, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [c471d24818](https://linux-hardware.org/?probe=c471d24818) | Oct 11, 2021 |
| Samsung       | 550XBE/350XBE               | Notebook    | [34b3be8c54](https://linux-hardware.org/?probe=34b3be8c54) | Oct 11, 2021 |
| PCChips       | P49G                        | Desktop     | [381061a980](https://linux-hardware.org/?probe=381061a980) | Oct 11, 2021 |
| Unknown       | Phitronics G41-M3           | Desktop     | [2b94f6fcca](https://linux-hardware.org/?probe=2b94f6fcca) | Oct 11, 2021 |
| ASUSTek       | X451CAP                     | Notebook    | [3312d93006](https://linux-hardware.org/?probe=3312d93006) | Oct 11, 2021 |
| Dell          | 0CKCXH A03                  | Desktop     | [5af30a5690](https://linux-hardware.org/?probe=5af30a5690) | Oct 11, 2021 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [a9760c8b4a](https://linux-hardware.org/?probe=a9760c8b4a) | Oct 11, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [e6eee85025](https://linux-hardware.org/?probe=e6eee85025) | Oct 11, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [61e272a119](https://linux-hardware.org/?probe=61e272a119) | Oct 10, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [f5147cd609](https://linux-hardware.org/?probe=f5147cd609) | Oct 10, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [5070a2bdc7](https://linux-hardware.org/?probe=5070a2bdc7) | Oct 10, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [661aa3980f](https://linux-hardware.org/?probe=661aa3980f) | Oct 10, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [d68a1a657f](https://linux-hardware.org/?probe=d68a1a657f) | Oct 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [5b4efb9e18](https://linux-hardware.org/?probe=5b4efb9e18) | Oct 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [3abe7cda22](https://linux-hardware.org/?probe=3abe7cda22) | Oct 10, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [11f6b37f01](https://linux-hardware.org/?probe=11f6b37f01) | Oct 10, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [c0ae5669be](https://linux-hardware.org/?probe=c0ae5669be) | Oct 10, 2021 |
| Intel         | DG35EC AAE29266-202         | Desktop     | [d61f31abf0](https://linux-hardware.org/?probe=d61f31abf0) | Oct 10, 2021 |
| Intel         | DG35EC AAE29266-202         | Desktop     | [24fa8f8f31](https://linux-hardware.org/?probe=24fa8f8f31) | Oct 10, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [3c7018cbdf](https://linux-hardware.org/?probe=3c7018cbdf) | Oct 10, 2021 |
| Digibras      | NH4CU53                     | Notebook    | [2d576fc462](https://linux-hardware.org/?probe=2d576fc462) | Oct 10, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c97f94ce2f](https://linux-hardware.org/?probe=c97f94ce2f) | Oct 10, 2021 |
| Intel         | H61                         | Desktop     | [38f7084dac](https://linux-hardware.org/?probe=38f7084dac) | Oct 10, 2021 |
| HP            | Pavilion g4                 | Notebook    | [ec01cc8010](https://linux-hardware.org/?probe=ec01cc8010) | Oct 10, 2021 |
| Dell          | Inspiron 5447               | Notebook    | [689944cbda](https://linux-hardware.org/?probe=689944cbda) | Oct 10, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [ce0b4be791](https://linux-hardware.org/?probe=ce0b4be791) | Oct 10, 2021 |
| Acer          | Aspire ES1-411              | Notebook    | [04643df6f1](https://linux-hardware.org/?probe=04643df6f1) | Oct 10, 2021 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [393852d904](https://linux-hardware.org/?probe=393852d904) | Oct 10, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [47d670e622](https://linux-hardware.org/?probe=47d670e622) | Oct 10, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [5bba08307b](https://linux-hardware.org/?probe=5bba08307b) | Oct 10, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [724dad5f41](https://linux-hardware.org/?probe=724dad5f41) | Oct 09, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [c361beb898](https://linux-hardware.org/?probe=c361beb898) | Oct 09, 2021 |
| Toshiba       | Satellite C655              | Notebook    | [39f61ad9fd](https://linux-hardware.org/?probe=39f61ad9fd) | Oct 09, 2021 |
| HP            | TouchSmart tm2              | Notebook    | [4a04d297c6](https://linux-hardware.org/?probe=4a04d297c6) | Oct 09, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [56e9375e76](https://linux-hardware.org/?probe=56e9375e76) | Oct 09, 2021 |
| Sony          | SVT13115FBS                 | Notebook    | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [f15efc966d](https://linux-hardware.org/?probe=f15efc966d) | Oct 08, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [ecfcf772fb](https://linux-hardware.org/?probe=ecfcf772fb) | Oct 08, 2021 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [2bc0b62213](https://linux-hardware.org/?probe=2bc0b62213) | Oct 08, 2021 |
| MSI           | G41M-S01                    | Desktop     | [88647490e2](https://linux-hardware.org/?probe=88647490e2) | Oct 08, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [8f26f50fbc](https://linux-hardware.org/?probe=8f26f50fbc) | Oct 08, 2021 |
| Dell          | G3 3500                     | Notebook    | [b4e985bcba](https://linux-hardware.org/?probe=b4e985bcba) | Oct 08, 2021 |
| Multilaser    | UB32X                       | Notebook    | [e5e22df913](https://linux-hardware.org/?probe=e5e22df913) | Oct 08, 2021 |
| OEM           | Unknown                     | Notebook    | [81ab5eba46](https://linux-hardware.org/?probe=81ab5eba46) | Oct 08, 2021 |
| Sony          | VPCEA20FB                   | Notebook    | [de4d94232e](https://linux-hardware.org/?probe=de4d94232e) | Oct 07, 2021 |
| Sony          | VPCEA20FB                   | Notebook    | [52e6abba3c](https://linux-hardware.org/?probe=52e6abba3c) | Oct 07, 2021 |
| ASUSTek       | X751LJ                      | Notebook    | [08ba22fc67](https://linux-hardware.org/?probe=08ba22fc67) | Oct 07, 2021 |
| OEM           | Unknown                     | Notebook    | [d7843090fc](https://linux-hardware.org/?probe=d7843090fc) | Oct 07, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [639ef19ce2](https://linux-hardware.org/?probe=639ef19ce2) | Oct 07, 2021 |
| Lenovo        | B320-14IKB 81CC             | Notebook    | [d2b36ea612](https://linux-hardware.org/?probe=d2b36ea612) | Oct 07, 2021 |
| Dell          | Inspiron 7560               | Notebook    | [f04c214239](https://linux-hardware.org/?probe=f04c214239) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9ed170f601](https://linux-hardware.org/?probe=9ed170f601) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [97f69ae3fa](https://linux-hardware.org/?probe=97f69ae3fa) | Oct 07, 2021 |
| Philco        | 14I                         | Notebook    | [0080a4ef97](https://linux-hardware.org/?probe=0080a4ef97) | Oct 07, 2021 |
| Philco        | 14I                         | Notebook    | [ff6fc89ff5](https://linux-hardware.org/?probe=ff6fc89ff5) | Oct 07, 2021 |
| Intel         | DG31PR AAE58249-301         | Desktop     | [231505c0b0](https://linux-hardware.org/?probe=231505c0b0) | Oct 07, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [a0d197c569](https://linux-hardware.org/?probe=a0d197c569) | Oct 07, 2021 |
| ASRock        | N68-S3 FX                   | Desktop     | [7a993d28fd](https://linux-hardware.org/?probe=7a993d28fd) | Oct 07, 2021 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [86873ad187](https://linux-hardware.org/?probe=86873ad187) | Oct 07, 2021 |
| Acer          | Aspire ES1-533              | Notebook    | [a1a36f11f4](https://linux-hardware.org/?probe=a1a36f11f4) | Oct 07, 2021 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [a10f9aa345](https://linux-hardware.org/?probe=a10f9aa345) | Oct 07, 2021 |
| MSI           | Z270 SLI PLUS               | Desktop     | [b35b4de93f](https://linux-hardware.org/?probe=b35b4de93f) | Oct 06, 2021 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [9cc567f48b](https://linux-hardware.org/?probe=9cc567f48b) | Oct 06, 2021 |
| Positivo      | POS-ECIG41BSA               | Desktop     | [978a5e9bce](https://linux-hardware.org/?probe=978a5e9bce) | Oct 06, 2021 |
| Intel         | H61                         | Desktop     | [8ec0d8b02a](https://linux-hardware.org/?probe=8ec0d8b02a) | Oct 06, 2021 |
| Dell          | Latitude 5400               | Notebook    | [53a7573a6f](https://linux-hardware.org/?probe=53a7573a6f) | Oct 06, 2021 |
| ASUSTek       | ZenBook Q326FA_Q326FA       | Convertible | [71fb7c2c92](https://linux-hardware.org/?probe=71fb7c2c92) | Oct 06, 2021 |
| ASUSTek       | ZenBook Q326FA_Q326FA       | Convertible | [f5dd67ff4c](https://linux-hardware.org/?probe=f5dd67ff4c) | Oct 06, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [eb4d94004c](https://linux-hardware.org/?probe=eb4d94004c) | Oct 06, 2021 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [4c9743cdd1](https://linux-hardware.org/?probe=4c9743cdd1) | Oct 06, 2021 |
| Sony          | VPCEH40EB                   | Notebook    | [aa24653464](https://linux-hardware.org/?probe=aa24653464) | Oct 06, 2021 |
| Sony          | VPCEH40EB                   | Notebook    | [ea7ca4b810](https://linux-hardware.org/?probe=ea7ca4b810) | Oct 06, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [d5dbcb7130](https://linux-hardware.org/?probe=d5dbcb7130) | Oct 06, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [4ca9b7c23a](https://linux-hardware.org/?probe=4ca9b7c23a) | Oct 06, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d4931747ca](https://linux-hardware.org/?probe=d4931747ca) | Oct 05, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [e9b9d62598](https://linux-hardware.org/?probe=e9b9d62598) | Oct 05, 2021 |
| Intel         | DH61SA AAG38870-300         | Desktop     | [43e3fccc3d](https://linux-hardware.org/?probe=43e3fccc3d) | Oct 05, 2021 |
| Dell          | Inspiron 5537               | Notebook    | [edd8cf99a2](https://linux-hardware.org/?probe=edd8cf99a2) | Oct 05, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [717531e025](https://linux-hardware.org/?probe=717531e025) | Oct 05, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [a1ffed0a4e](https://linux-hardware.org/?probe=a1ffed0a4e) | Oct 04, 2021 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [459d0f2e53](https://linux-hardware.org/?probe=459d0f2e53) | Oct 04, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [3ab27b741e](https://linux-hardware.org/?probe=3ab27b741e) | Oct 04, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [21d49c2826](https://linux-hardware.org/?probe=21d49c2826) | Oct 04, 2021 |
| MITSUSHIBA    | Intel NUC I3 BP-011F / B... | Mini pc     | [401691db3b](https://linux-hardware.org/?probe=401691db3b) | Oct 04, 2021 |
| MITSUSHIBA    | Intel NUC I3 BP-011F / B... | Mini pc     | [565165373d](https://linux-hardware.org/?probe=565165373d) | Oct 04, 2021 |
| Dell          | 053CWD A00                  | Desktop     | [2c4113a15a](https://linux-hardware.org/?probe=2c4113a15a) | Oct 04, 2021 |
| Dell          | 053CWD A00                  | Desktop     | [0d70c08e7a](https://linux-hardware.org/?probe=0d70c08e7a) | Oct 04, 2021 |
| IBM           | MSI-9151 Boards             | Desktop     | [0511aeeac6](https://linux-hardware.org/?probe=0511aeeac6) | Oct 04, 2021 |
| IBM           | MSI-9151 Boards             | Desktop     | [ad44652156](https://linux-hardware.org/?probe=ad44652156) | Oct 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [be6cf2d704](https://linux-hardware.org/?probe=be6cf2d704) | Oct 04, 2021 |
| Intel         | NUC6i3SYB H81132-503        | Mini pc     | [38571fcfb9](https://linux-hardware.org/?probe=38571fcfb9) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [9622936906](https://linux-hardware.org/?probe=9622936906) | Oct 04, 2021 |
| Dell          | Inspiron 5537               | Notebook    | [dc1d70608c](https://linux-hardware.org/?probe=dc1d70608c) | Oct 04, 2021 |
| ASRock        | H110M-HDS R3.0              | Desktop     | [74b79eaf21](https://linux-hardware.org/?probe=74b79eaf21) | Oct 03, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [cdb8dd9b53](https://linux-hardware.org/?probe=cdb8dd9b53) | Oct 03, 2021 |
| Intel         | X99 V1.x                    | Desktop     | [d5bb69920a](https://linux-hardware.org/?probe=d5bb69920a) | Oct 03, 2021 |
| HP            | 240 G1                      | Notebook    | [9aba4f2689](https://linux-hardware.org/?probe=9aba4f2689) | Oct 03, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [e8fd995776](https://linux-hardware.org/?probe=e8fd995776) | Oct 03, 2021 |
| Sony          | VPCEH10EB                   | Notebook    | [c75fe465b1](https://linux-hardware.org/?probe=c75fe465b1) | Oct 03, 2021 |
| Gigabyte      | H510M H                     | Desktop     | [991a31ce5a](https://linux-hardware.org/?probe=991a31ce5a) | Oct 02, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [f6aeb86bde](https://linux-hardware.org/?probe=f6aeb86bde) | Oct 02, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [3047b3ec7c](https://linux-hardware.org/?probe=3047b3ec7c) | Oct 02, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [8169f29a6a](https://linux-hardware.org/?probe=8169f29a6a) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [9923b250ea](https://linux-hardware.org/?probe=9923b250ea) | Oct 02, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [e44e6c5a44](https://linux-hardware.org/?probe=e44e6c5a44) | Oct 02, 2021 |
| Lenovo        | Unknown                     | Notebook    | [56e7fa3c9b](https://linux-hardware.org/?probe=56e7fa3c9b) | Oct 02, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [db26b44773](https://linux-hardware.org/?probe=db26b44773) | Oct 02, 2021 |
| Intel         | DG35EC AAE29266-202         | Desktop     | [74d233db8b](https://linux-hardware.org/?probe=74d233db8b) | Oct 02, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [3be52ed98f](https://linux-hardware.org/?probe=3be52ed98f) | Oct 02, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [ffb9699d7a](https://linux-hardware.org/?probe=ffb9699d7a) | Oct 02, 2021 |
| Intel         | DG35EC AAE29266-202         | Desktop     | [f29471dfd6](https://linux-hardware.org/?probe=f29471dfd6) | Oct 01, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [c2fda06302](https://linux-hardware.org/?probe=c2fda06302) | Oct 01, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [c79d1def32](https://linux-hardware.org/?probe=c79d1def32) | Oct 01, 2021 |
| Samsung       | 550XDA                      | Notebook    | [03b0767f75](https://linux-hardware.org/?probe=03b0767f75) | Oct 01, 2021 |
| Acer          | Aspire ES1-431              | Notebook    | [e8ca351107](https://linux-hardware.org/?probe=e8ca351107) | Oct 01, 2021 |
| Acer          | Aspire ES1-431              | Notebook    | [6e3f9142f0](https://linux-hardware.org/?probe=6e3f9142f0) | Oct 01, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [f5565dfb2a](https://linux-hardware.org/?probe=f5565dfb2a) | Oct 01, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [10d8a84245](https://linux-hardware.org/?probe=10d8a84245) | Oct 01, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [090eee57b7](https://linux-hardware.org/?probe=090eee57b7) | Oct 01, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [2968458879](https://linux-hardware.org/?probe=2968458879) | Oct 01, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a0cb946b8a](https://linux-hardware.org/?probe=a0cb946b8a) | Oct 01, 2021 |
| MSI           | G41M-P33 Combo              | Desktop     | [ec8e63e96e](https://linux-hardware.org/?probe=ec8e63e96e) | Oct 01, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2e10a8baf0](https://linux-hardware.org/?probe=2e10a8baf0) | Sep 30, 2021 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [29ae8992b5](https://linux-hardware.org/?probe=29ae8992b5) | Sep 30, 2021 |
| Unknown       | PCWARE APMCP68              | Desktop     | [53439ed943](https://linux-hardware.org/?probe=53439ed943) | Sep 30, 2021 |
| Unknown       | PCWARE APMCP68              | Desktop     | [d17d7c6e6f](https://linux-hardware.org/?probe=d17d7c6e6f) | Sep 30, 2021 |
| Positivo      | Mobile                      | Notebook    | [9e098ffe5e](https://linux-hardware.org/?probe=9e098ffe5e) | Sep 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [819ee8affd](https://linux-hardware.org/?probe=819ee8affd) | Sep 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4328d7510a](https://linux-hardware.org/?probe=4328d7510a) | Sep 30, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [a9d145291f](https://linux-hardware.org/?probe=a9d145291f) | Sep 30, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [cb940b924d](https://linux-hardware.org/?probe=cb940b924d) | Sep 30, 2021 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [1abb7a2b2a](https://linux-hardware.org/?probe=1abb7a2b2a) | Sep 30, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [60fe11ee00](https://linux-hardware.org/?probe=60fe11ee00) | Sep 30, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [964476869c](https://linux-hardware.org/?probe=964476869c) | Sep 30, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [2fe59d03eb](https://linux-hardware.org/?probe=2fe59d03eb) | Sep 30, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b8b2183bc1](https://linux-hardware.org/?probe=b8b2183bc1) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [359171629f](https://linux-hardware.org/?probe=359171629f) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [4e125287e4](https://linux-hardware.org/?probe=4e125287e4) | Sep 30, 2021 |
| Positivo      | Mobile                      | Notebook    | [fb85092913](https://linux-hardware.org/?probe=fb85092913) | Sep 30, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [9b5b92afef](https://linux-hardware.org/?probe=9b5b92afef) | Sep 30, 2021 |
| Positivo      | Mobile                      | Notebook    | [e45a4b5186](https://linux-hardware.org/?probe=e45a4b5186) | Sep 30, 2021 |
| OEM           | Unknown                     | Desktop     | [a6d82457d0](https://linux-hardware.org/?probe=a6d82457d0) | Sep 30, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [d0c34db7d4](https://linux-hardware.org/?probe=d0c34db7d4) | Sep 29, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [a47ae6e7b0](https://linux-hardware.org/?probe=a47ae6e7b0) | Sep 29, 2021 |
| Samsung       | 270E5G/270E5U               | Notebook    | [5b9a273adf](https://linux-hardware.org/?probe=5b9a273adf) | Sep 29, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [949ac66eff](https://linux-hardware.org/?probe=949ac66eff) | Sep 29, 2021 |
| Positivo      | Smash3                      | Notebook    | [fe185c2e3f](https://linux-hardware.org/?probe=fe185c2e3f) | Sep 29, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [6c15236ba3](https://linux-hardware.org/?probe=6c15236ba3) | Sep 29, 2021 |
| Lenovo        | B320-14IKB 81CC             | Notebook    | [a460edd4e8](https://linux-hardware.org/?probe=a460edd4e8) | Sep 29, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [f7a5bd6c04](https://linux-hardware.org/?probe=f7a5bd6c04) | Sep 29, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [f3e306d3de](https://linux-hardware.org/?probe=f3e306d3de) | Sep 29, 2021 |
| ASRock        | N68-S3 FX                   | Desktop     | [7928afa92c](https://linux-hardware.org/?probe=7928afa92c) | Sep 28, 2021 |
| HP            | 1998                        | Desktop     | [bb31e60922](https://linux-hardware.org/?probe=bb31e60922) | Sep 28, 2021 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [17a839112e](https://linux-hardware.org/?probe=17a839112e) | Sep 28, 2021 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [bde64491bc](https://linux-hardware.org/?probe=bde64491bc) | Sep 28, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ec5453ee8c](https://linux-hardware.org/?probe=ec5453ee8c) | Sep 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [c81def3b2e](https://linux-hardware.org/?probe=c81def3b2e) | Sep 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [50601caf44](https://linux-hardware.org/?probe=50601caf44) | Sep 28, 2021 |
| Digiboard     | MPxx                        | Desktop     | [bad4baa7aa](https://linux-hardware.org/?probe=bad4baa7aa) | Sep 28, 2021 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [062fa178c0](https://linux-hardware.org/?probe=062fa178c0) | Sep 28, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [a9e4f4822e](https://linux-hardware.org/?probe=a9e4f4822e) | Sep 28, 2021 |
| Positivo      | Mobile                      | Notebook    | [960cbb831a](https://linux-hardware.org/?probe=960cbb831a) | Sep 28, 2021 |
| Acer          | Aspire A315-56              | Notebook    | [3fc47b2c92](https://linux-hardware.org/?probe=3fc47b2c92) | Sep 27, 2021 |
| Positivo      | S14BW01                     | Notebook    | [6a9cecbb0e](https://linux-hardware.org/?probe=6a9cecbb0e) | Sep 27, 2021 |
| Acer          | Aspire E1-471               | Notebook    | [dc9d130047](https://linux-hardware.org/?probe=dc9d130047) | Sep 27, 2021 |
| ASRock        | A55M-HVS                    | Desktop     | [3061a2007b](https://linux-hardware.org/?probe=3061a2007b) | Sep 27, 2021 |
| PCWare        | IPMH61R2                    | Desktop     | [62d2476431](https://linux-hardware.org/?probe=62d2476431) | Sep 27, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [66a2255f4a](https://linux-hardware.org/?probe=66a2255f4a) | Sep 27, 2021 |
| Acer          | Aspire 4553                 | Notebook    | [70acc3adae](https://linux-hardware.org/?probe=70acc3adae) | Sep 27, 2021 |
| Digibras      | NH4CU53                     | Notebook    | [f0615abf72](https://linux-hardware.org/?probe=f0615abf72) | Sep 27, 2021 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [cf3c570b7a](https://linux-hardware.org/?probe=cf3c570b7a) | Sep 27, 2021 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [ee4f0f6f02](https://linux-hardware.org/?probe=ee4f0f6f02) | Sep 27, 2021 |
| HP            | Pavilion g4                 | Notebook    | [bb0793d3ab](https://linux-hardware.org/?probe=bb0793d3ab) | Sep 27, 2021 |
| HP            | Pavilion g4                 | Notebook    | [029c21cd2d](https://linux-hardware.org/?probe=029c21cd2d) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | Notebook    | [721c266b6b](https://linux-hardware.org/?probe=721c266b6b) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | Notebook    | [00d9651c96](https://linux-hardware.org/?probe=00d9651c96) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [f290c9b80f](https://linux-hardware.org/?probe=f290c9b80f) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [82bd2ec7eb](https://linux-hardware.org/?probe=82bd2ec7eb) | Sep 27, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [630184b246](https://linux-hardware.org/?probe=630184b246) | Sep 27, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [2d74e1dee2](https://linux-hardware.org/?probe=2d74e1dee2) | Sep 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [e604f9120c](https://linux-hardware.org/?probe=e604f9120c) | Sep 27, 2021 |
| Positivo      | W940TU                      | Notebook    | [0153e89101](https://linux-hardware.org/?probe=0153e89101) | Sep 27, 2021 |
| Positivo      | EC10IS1                     | Notebook    | [3e75f71b33](https://linux-hardware.org/?probe=3e75f71b33) | Sep 26, 2021 |
| Gateway       | NE56R                       | Notebook    | [09c06599e4](https://linux-hardware.org/?probe=09c06599e4) | Sep 26, 2021 |
| Gigabyte      | H310M H                     | Desktop     | [edc70d4571](https://linux-hardware.org/?probe=edc70d4571) | Sep 26, 2021 |
| Positivo      | W940TU                      | Notebook    | [fc44f175b0](https://linux-hardware.org/?probe=fc44f175b0) | Sep 26, 2021 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [1c65589814](https://linux-hardware.org/?probe=1c65589814) | Sep 26, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [6786f73aaa](https://linux-hardware.org/?probe=6786f73aaa) | Sep 26, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [931dcd2f32](https://linux-hardware.org/?probe=931dcd2f32) | Sep 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [faf2457b94](https://linux-hardware.org/?probe=faf2457b94) | Sep 26, 2021 |
| LG Electro... | X140-G.BG12P1               | Notebook    | [626d49a6a9](https://linux-hardware.org/?probe=626d49a6a9) | Sep 26, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [67c627caba](https://linux-hardware.org/?probe=67c627caba) | Sep 26, 2021 |
| Lenovo        | Legion 5 15IMH05H 82CF      | Notebook    | [8c5d298498](https://linux-hardware.org/?probe=8c5d298498) | Sep 26, 2021 |
| Lenovo        | ThinkPad X200 2024A16       | Notebook    | [36fb1f3891](https://linux-hardware.org/?probe=36fb1f3891) | Sep 26, 2021 |
| Unknown       | Intel X79                   | Desktop     | [10b8dbc9a7](https://linux-hardware.org/?probe=10b8dbc9a7) | Sep 26, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [65f21b6089](https://linux-hardware.org/?probe=65f21b6089) | Sep 26, 2021 |
| HP            | Pavilion 14                 | Notebook    | [2ab5781fef](https://linux-hardware.org/?probe=2ab5781fef) | Sep 25, 2021 |
| HP            | 0AA8h                       | Desktop     | [496b6b24f2](https://linux-hardware.org/?probe=496b6b24f2) | Sep 25, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [530c4bb80d](https://linux-hardware.org/?probe=530c4bb80d) | Sep 25, 2021 |
| HP            | ProBook 6465b               | Notebook    | [dbff45c387](https://linux-hardware.org/?probe=dbff45c387) | Sep 25, 2021 |
| ECS           | A55F-M4                     | Desktop     | [627bf10798](https://linux-hardware.org/?probe=627bf10798) | Sep 25, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [b484f4f0cc](https://linux-hardware.org/?probe=b484f4f0cc) | Sep 25, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [a48ffce26d](https://linux-hardware.org/?probe=a48ffce26d) | Sep 25, 2021 |
| Dell          | Latitude E6430              | Notebook    | [cf0b1842b5](https://linux-hardware.org/?probe=cf0b1842b5) | Sep 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5dc4b1b49b](https://linux-hardware.org/?probe=5dc4b1b49b) | Sep 25, 2021 |
| Biostar       | G41D3C                      | Desktop     | [c3f6f00677](https://linux-hardware.org/?probe=c3f6f00677) | Sep 25, 2021 |
| ASRock        | A55M-HVS                    | Desktop     | [4748ccb729](https://linux-hardware.org/?probe=4748ccb729) | Sep 25, 2021 |
| Gateway       | NE56R                       | Notebook    | [ae70cb194b](https://linux-hardware.org/?probe=ae70cb194b) | Sep 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [0a60104e53](https://linux-hardware.org/?probe=0a60104e53) | Sep 25, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [cb8cc4304e](https://linux-hardware.org/?probe=cb8cc4304e) | Sep 25, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dd082afe88](https://linux-hardware.org/?probe=dd082afe88) | Sep 24, 2021 |
| Gigabyte      | H310M H                     | Desktop     | [4f3e69507b](https://linux-hardware.org/?probe=4f3e69507b) | Sep 24, 2021 |
| Positivo      | Smash3                      | Notebook    | [ee8284c509](https://linux-hardware.org/?probe=ee8284c509) | Sep 24, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [2f771e8271](https://linux-hardware.org/?probe=2f771e8271) | Sep 24, 2021 |
| Lenovo        | G40-70 80GA                 | Notebook    | [f2f6396a3c](https://linux-hardware.org/?probe=f2f6396a3c) | Sep 24, 2021 |
| LG Electro... | X140-G.BG12P1               | Notebook    | [d5bb2a15f6](https://linux-hardware.org/?probe=d5bb2a15f6) | Sep 24, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [0a2987d902](https://linux-hardware.org/?probe=0a2987d902) | Sep 24, 2021 |
| Dell          | Inspiron 3584               | Notebook    | [4f8cf87cd0](https://linux-hardware.org/?probe=4f8cf87cd0) | Sep 24, 2021 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [9973a9c2a2](https://linux-hardware.org/?probe=9973a9c2a2) | Sep 24, 2021 |
| Avell High... | B.ON                        | Notebook    | [45c4ec81ea](https://linux-hardware.org/?probe=45c4ec81ea) | Sep 24, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [a086c8516d](https://linux-hardware.org/?probe=a086c8516d) | Sep 24, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [9e6acff67b](https://linux-hardware.org/?probe=9e6acff67b) | Sep 24, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [b7498ef12c](https://linux-hardware.org/?probe=b7498ef12c) | Sep 24, 2021 |
| Positivo      | Smash3                      | Notebook    | [9789e38ff6](https://linux-hardware.org/?probe=9789e38ff6) | Sep 23, 2021 |
| ASRock        | A55M-HVS                    | Desktop     | [a367ec462a](https://linux-hardware.org/?probe=a367ec462a) | Sep 23, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [1f03dc33de](https://linux-hardware.org/?probe=1f03dc33de) | Sep 23, 2021 |
| Philco        | 14F                         | Notebook    | [093b9632e8](https://linux-hardware.org/?probe=093b9632e8) | Sep 23, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [cb23f25d7f](https://linux-hardware.org/?probe=cb23f25d7f) | Sep 23, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [e75373a634](https://linux-hardware.org/?probe=e75373a634) | Sep 23, 2021 |
| ASRock        | 760GM-HD                    | Desktop     | [3e95020892](https://linux-hardware.org/?probe=3e95020892) | Sep 23, 2021 |
| Supermicro    | X7DB8                       | Desktop     | [f235adfa2d](https://linux-hardware.org/?probe=f235adfa2d) | Sep 23, 2021 |
| Dell          | System Inspiron N4120       | Notebook    | [5da38a8b5e](https://linux-hardware.org/?probe=5da38a8b5e) | Sep 23, 2021 |
| ASRock        | 760GM-HD                    | Desktop     | [f43227bf66](https://linux-hardware.org/?probe=f43227bf66) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [74410f0d0c](https://linux-hardware.org/?probe=74410f0d0c) | Sep 23, 2021 |
| ASUSTek       | P8H67-V                     | Desktop     | [ddb22c91d8](https://linux-hardware.org/?probe=ddb22c91d8) | Sep 23, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [abdedf857f](https://linux-hardware.org/?probe=abdedf857f) | Sep 23, 2021 |
| Positivo      | NB50TH 11144919             | Notebook    | [25c060dd59](https://linux-hardware.org/?probe=25c060dd59) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ad81766325](https://linux-hardware.org/?probe=ad81766325) | Sep 23, 2021 |
| Biostar       | A960D+V3                    | Desktop     | [016f8366d2](https://linux-hardware.org/?probe=016f8366d2) | Sep 22, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [1473ddbea8](https://linux-hardware.org/?probe=1473ddbea8) | Sep 22, 2021 |
| Lenovo        | ThinkPad T480 20L6SCWK00    | Notebook    | [d8f862995c](https://linux-hardware.org/?probe=d8f862995c) | Sep 22, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [706bf9f278](https://linux-hardware.org/?probe=706bf9f278) | Sep 22, 2021 |
| Dell          | Inspiron 6000               | Notebook    | [f48bad44cd](https://linux-hardware.org/?probe=f48bad44cd) | Sep 22, 2021 |
| Dell          | Inspiron 6000               | Notebook    | [9b3cde9b5f](https://linux-hardware.org/?probe=9b3cde9b5f) | Sep 22, 2021 |
| Positivo      | NB50TH 11144919             | Notebook    | [8aea8bce96](https://linux-hardware.org/?probe=8aea8bce96) | Sep 22, 2021 |
| ASRock        | A55M-HVS                    | Desktop     | [f0081639fb](https://linux-hardware.org/?probe=f0081639fb) | Sep 22, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [86fcd8882b](https://linux-hardware.org/?probe=86fcd8882b) | Sep 22, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [2c3343049c](https://linux-hardware.org/?probe=2c3343049c) | Sep 22, 2021 |
| Dell          | G5 5590                     | Notebook    | [90e0f568ef](https://linux-hardware.org/?probe=90e0f568ef) | Sep 22, 2021 |
| Dell          | G5 5590                     | Notebook    | [484c36584c](https://linux-hardware.org/?probe=484c36584c) | Sep 22, 2021 |
| Toshiba       | IS 1442                     | Notebook    | [26b3724f40](https://linux-hardware.org/?probe=26b3724f40) | Sep 22, 2021 |
| ASUSTek       | X510UR                      | Notebook    | [fb80dd8209](https://linux-hardware.org/?probe=fb80dd8209) | Sep 22, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [9662887c26](https://linux-hardware.org/?probe=9662887c26) | Sep 22, 2021 |
| Intel         | D33217GKE G76540-202        | Desktop     | [dfc89bbcfb](https://linux-hardware.org/?probe=dfc89bbcfb) | Sep 22, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [effa7b0365](https://linux-hardware.org/?probe=effa7b0365) | Sep 22, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [e886fe36b0](https://linux-hardware.org/?probe=e886fe36b0) | Sep 22, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [04f654bbf6](https://linux-hardware.org/?probe=04f654bbf6) | Sep 22, 2021 |
| HP            | ProBook 445 G7 Notebook ... | Notebook    | [c9a187f9b5](https://linux-hardware.org/?probe=c9a187f9b5) | Sep 22, 2021 |
| ASRock        | B560M-HDV                   | Desktop     | [d3e3f32b10](https://linux-hardware.org/?probe=d3e3f32b10) | Sep 22, 2021 |
| Samsung       | RV415                       | Notebook    | [9fbf78d306](https://linux-hardware.org/?probe=9fbf78d306) | Sep 21, 2021 |
| Lenovo        | G40-70 80GA                 | Notebook    | [8ba031b32f](https://linux-hardware.org/?probe=8ba031b32f) | Sep 21, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [984abecd8d](https://linux-hardware.org/?probe=984abecd8d) | Sep 21, 2021 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [f18ba9c670](https://linux-hardware.org/?probe=f18ba9c670) | Sep 21, 2021 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [a5dea4108e](https://linux-hardware.org/?probe=a5dea4108e) | Sep 21, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [a08d8ecd94](https://linux-hardware.org/?probe=a08d8ecd94) | Sep 21, 2021 |
| VS Company    | G31T-M                      | Desktop     | [ed8bb8c0d1](https://linux-hardware.org/?probe=ed8bb8c0d1) | Sep 21, 2021 |
| Acer          | Aspire A315-54              | Notebook    | [f06a523887](https://linux-hardware.org/?probe=f06a523887) | Sep 21, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3ef59689e6](https://linux-hardware.org/?probe=3ef59689e6) | Sep 21, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [cc973ea077](https://linux-hardware.org/?probe=cc973ea077) | Sep 21, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [be7dfbdb8e](https://linux-hardware.org/?probe=be7dfbdb8e) | Sep 21, 2021 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [3d75b079f5](https://linux-hardware.org/?probe=3d75b079f5) | Sep 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [91055c07be](https://linux-hardware.org/?probe=91055c07be) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [ae16407ef3](https://linux-hardware.org/?probe=ae16407ef3) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [9d2e1404e3](https://linux-hardware.org/?probe=9d2e1404e3) | Sep 20, 2021 |
| Unknown       | G31T-M7                     | Desktop     | [7dcab46660](https://linux-hardware.org/?probe=7dcab46660) | Sep 20, 2021 |
| Dell          | Inspiron 5537               | Notebook    | [e118644949](https://linux-hardware.org/?probe=e118644949) | Sep 20, 2021 |
| Dell          | Inspiron 5537               | Notebook    | [e713d93c95](https://linux-hardware.org/?probe=e713d93c95) | Sep 20, 2021 |
| Gigabyte      | A520M S2H                   | Desktop     | [aa80372d13](https://linux-hardware.org/?probe=aa80372d13) | Sep 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [2380a0486d](https://linux-hardware.org/?probe=2380a0486d) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c05636068f](https://linux-hardware.org/?probe=c05636068f) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [1a012b3021](https://linux-hardware.org/?probe=1a012b3021) | Sep 20, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [fb681f1d38](https://linux-hardware.org/?probe=fb681f1d38) | Sep 20, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [aa89265aaf](https://linux-hardware.org/?probe=aa89265aaf) | Sep 20, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [c586c22b15](https://linux-hardware.org/?probe=c586c22b15) | Sep 20, 2021 |
| Huanan        | X79-ZD3                     | Desktop     | [b1b17838a5](https://linux-hardware.org/?probe=b1b17838a5) | Sep 20, 2021 |
| ASRock        | Z390M Pro4                  | Desktop     | [a0536638b2](https://linux-hardware.org/?probe=a0536638b2) | Sep 20, 2021 |
| HP            | Pavilion dv6                | Notebook    | [05a48a70a1](https://linux-hardware.org/?probe=05a48a70a1) | Sep 19, 2021 |
| Positivo      | S14CT01                     | Notebook    | [0d1ab84e09](https://linux-hardware.org/?probe=0d1ab84e09) | Sep 19, 2021 |
| Intel         | DG41WV AAE90316-102         | Desktop     | [c6bfde4b60](https://linux-hardware.org/?probe=c6bfde4b60) | Sep 19, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [37f34b16c5](https://linux-hardware.org/?probe=37f34b16c5) | Sep 19, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [92c40f2b14](https://linux-hardware.org/?probe=92c40f2b14) | Sep 19, 2021 |
| Intel         | H61                         | Desktop     | [f28c2f500f](https://linux-hardware.org/?probe=f28c2f500f) | Sep 19, 2021 |
| Intel         | H61                         | Desktop     | [d92009bca8](https://linux-hardware.org/?probe=d92009bca8) | Sep 19, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [25fd382b32](https://linux-hardware.org/?probe=25fd382b32) | Sep 19, 2021 |
| ASRock        | B75 Pro3                    | Desktop     | [3dde09d211](https://linux-hardware.org/?probe=3dde09d211) | Sep 18, 2021 |
| Notebook      | W65_W67RN,RC1,RCY           | Notebook    | [c3f2419a83](https://linux-hardware.org/?probe=c3f2419a83) | Sep 18, 2021 |
| Notebook      | W65_W67RN,RC1,RCY           | Notebook    | [63dde78ef0](https://linux-hardware.org/?probe=63dde78ef0) | Sep 18, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [2cae5a1f25](https://linux-hardware.org/?probe=2cae5a1f25) | Sep 18, 2021 |
| Dell          | 0VRWRC A01                  | Desktop     | [c2a88904db](https://linux-hardware.org/?probe=c2a88904db) | Sep 18, 2021 |
| Dell          | 0VRWRC A01                  | Desktop     | [3a21f72544](https://linux-hardware.org/?probe=3a21f72544) | Sep 18, 2021 |
| HP            | G42                         | Notebook    | [0e9914c9cc](https://linux-hardware.org/?probe=0e9914c9cc) | Sep 18, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [64d57a64a0](https://linux-hardware.org/?probe=64d57a64a0) | Sep 18, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [e44f6e672e](https://linux-hardware.org/?probe=e44f6e672e) | Sep 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e8f361170f](https://linux-hardware.org/?probe=e8f361170f) | Sep 18, 2021 |
| Acer          | AO725                       | Notebook    | [8b4adc738c](https://linux-hardware.org/?probe=8b4adc738c) | Sep 18, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [44902b132d](https://linux-hardware.org/?probe=44902b132d) | Sep 18, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [131a09c44c](https://linux-hardware.org/?probe=131a09c44c) | Sep 18, 2021 |
| Dell          | Latitude 3490               | Notebook    | [bf645d2394](https://linux-hardware.org/?probe=bf645d2394) | Sep 17, 2021 |
| Biostar       | X370GT7                     | Desktop     | [3604b6236d](https://linux-hardware.org/?probe=3604b6236d) | Sep 17, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [2f62c6c1d4](https://linux-hardware.org/?probe=2f62c6c1d4) | Sep 17, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [69e45df388](https://linux-hardware.org/?probe=69e45df388) | Sep 17, 2021 |
| Lenovo        | G460 0677                   | Notebook    | [6f23b54ef5](https://linux-hardware.org/?probe=6f23b54ef5) | Sep 17, 2021 |
| Positivo      | Mobile                      | Notebook    | [6f701d72fd](https://linux-hardware.org/?probe=6f701d72fd) | Sep 17, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [fb99d0767d](https://linux-hardware.org/?probe=fb99d0767d) | Sep 17, 2021 |
| Dell          | Inspiron 5482               | Convertible | [c52711ab47](https://linux-hardware.org/?probe=c52711ab47) | Sep 16, 2021 |
| Acer          | Aspire V3-572G              | Notebook    | [addf12cb05](https://linux-hardware.org/?probe=addf12cb05) | Sep 16, 2021 |
| Unknown       | G31T-M7                     | Desktop     | [54c45c2abb](https://linux-hardware.org/?probe=54c45c2abb) | Sep 16, 2021 |
| Unknown       | Unknown                     | Notebook    | [d7b86e803f](https://linux-hardware.org/?probe=d7b86e803f) | Sep 16, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [94284ba5b0](https://linux-hardware.org/?probe=94284ba5b0) | Sep 16, 2021 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [1982fe12c4](https://linux-hardware.org/?probe=1982fe12c4) | Sep 16, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [1141e79a29](https://linux-hardware.org/?probe=1141e79a29) | Sep 16, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [670c2b0df7](https://linux-hardware.org/?probe=670c2b0df7) | Sep 16, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [134631220f](https://linux-hardware.org/?probe=134631220f) | Sep 16, 2021 |
| Acer          | Predator PH315-52           | Notebook    | [30772ab737](https://linux-hardware.org/?probe=30772ab737) | Sep 16, 2021 |
| Acer          | Predator PH315-52           | Notebook    | [7fd7b5116f](https://linux-hardware.org/?probe=7fd7b5116f) | Sep 16, 2021 |
| Acer          | AZ1100                      | All in one  | [6a428a166a](https://linux-hardware.org/?probe=6a428a166a) | Sep 16, 2021 |
| Acer          | AZ1100                      | All in one  | [e4f070935b](https://linux-hardware.org/?probe=e4f070935b) | Sep 16, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [226f916086](https://linux-hardware.org/?probe=226f916086) | Sep 15, 2021 |
| Samsung       | 700Z3C/700Z5C               | Notebook    | [8307888e2a](https://linux-hardware.org/?probe=8307888e2a) | Sep 15, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [28e7ace40d](https://linux-hardware.org/?probe=28e7ace40d) | Sep 15, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [ddb041ded0](https://linux-hardware.org/?probe=ddb041ded0) | Sep 15, 2021 |
| Dell          | Inspiron 3437               | Notebook    | [67069e48f0](https://linux-hardware.org/?probe=67069e48f0) | Sep 15, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [8cdc0019ed](https://linux-hardware.org/?probe=8cdc0019ed) | Sep 15, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [5f66fcc8d7](https://linux-hardware.org/?probe=5f66fcc8d7) | Sep 15, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [6a3592ad63](https://linux-hardware.org/?probe=6a3592ad63) | Sep 15, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [a9335318aa](https://linux-hardware.org/?probe=a9335318aa) | Sep 15, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [571644e06b](https://linux-hardware.org/?probe=571644e06b) | Sep 14, 2021 |
| Lenovo        | ThinkPad T450s 20BWZ0CKU... | Notebook    | [a9e206d41b](https://linux-hardware.org/?probe=a9e206d41b) | Sep 14, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [21e3d9bccb](https://linux-hardware.org/?probe=21e3d9bccb) | Sep 14, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [7deb832fbd](https://linux-hardware.org/?probe=7deb832fbd) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [785f6c0a11](https://linux-hardware.org/?probe=785f6c0a11) | Sep 14, 2021 |
| HOUTER        | IPMH61R1                    | Desktop     | [47deb6e1fb](https://linux-hardware.org/?probe=47deb6e1fb) | Sep 14, 2021 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [b057a2965d](https://linux-hardware.org/?probe=b057a2965d) | Sep 14, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [7e486cd179](https://linux-hardware.org/?probe=7e486cd179) | Sep 14, 2021 |
| Dell          | Latitude 3400               | Notebook    | [bfc68e0d9b](https://linux-hardware.org/?probe=bfc68e0d9b) | Sep 14, 2021 |
| Acer          | Aspire S3                   | Notebook    | [1c1964dc70](https://linux-hardware.org/?probe=1c1964dc70) | Sep 14, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [4fece13da7](https://linux-hardware.org/?probe=4fece13da7) | Sep 14, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [55bc3a893f](https://linux-hardware.org/?probe=55bc3a893f) | Sep 14, 2021 |
| Positivo      | POS-PIQ77CL                 | Desktop     | [87ec217aed](https://linux-hardware.org/?probe=87ec217aed) | Sep 14, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [aa7d7cfdf6](https://linux-hardware.org/?probe=aa7d7cfdf6) | Sep 13, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [8f215120c2](https://linux-hardware.org/?probe=8f215120c2) | Sep 13, 2021 |
| Dell          | 0VRWRC A01                  | Desktop     | [a14cd2accb](https://linux-hardware.org/?probe=a14cd2accb) | Sep 13, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [f6865a8228](https://linux-hardware.org/?probe=f6865a8228) | Sep 13, 2021 |
| Dell          | 0VRWRC A01                  | Desktop     | [442dd66231](https://linux-hardware.org/?probe=442dd66231) | Sep 13, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [d27165285a](https://linux-hardware.org/?probe=d27165285a) | Sep 13, 2021 |
| Lenovo        | BS145-15IIL 82HB            | Notebook    | [c731e4ee9d](https://linux-hardware.org/?probe=c731e4ee9d) | Sep 13, 2021 |
| Lenovo        | BS145-15IIL 82HB            | Notebook    | [267d8551a9](https://linux-hardware.org/?probe=267d8551a9) | Sep 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7e31c12fab](https://linux-hardware.org/?probe=7e31c12fab) | Sep 13, 2021 |
| Qbex          | UDPAIOQBEX01                | Notebook    | [34c385cfe4](https://linux-hardware.org/?probe=34c385cfe4) | Sep 13, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [9eec34a3f2](https://linux-hardware.org/?probe=9eec34a3f2) | Sep 13, 2021 |
| Lenovo        | ThinkPad E14 20RB0028BR     | Notebook    | [8b1b3a98ba](https://linux-hardware.org/?probe=8b1b3a98ba) | Sep 12, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [271309ac53](https://linux-hardware.org/?probe=271309ac53) | Sep 12, 2021 |
| Gateway       | NE56R                       | Notebook    | [1cf7429528](https://linux-hardware.org/?probe=1cf7429528) | Sep 12, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [bc80b42442](https://linux-hardware.org/?probe=bc80b42442) | Sep 12, 2021 |
| Dell          | Inspiron 5448               | Notebook    | [2a2625d85f](https://linux-hardware.org/?probe=2a2625d85f) | Sep 11, 2021 |
| Gigabyte      | A520M S2H                   | Desktop     | [d8a1bf8786](https://linux-hardware.org/?probe=d8a1bf8786) | Sep 11, 2021 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [5f2cc29efc](https://linux-hardware.org/?probe=5f2cc29efc) | Sep 11, 2021 |
| Intel         | DG41RQ AAE54511-201         | Desktop     | [14957a27ad](https://linux-hardware.org/?probe=14957a27ad) | Sep 11, 2021 |
| Intel         | DG41RQ AAE54511-201         | Desktop     | [f525bfb156](https://linux-hardware.org/?probe=f525bfb156) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1465a2e9d6](https://linux-hardware.org/?probe=1465a2e9d6) | Sep 11, 2021 |
| ASUSTek       | Z550MA                      | Notebook    | [4786139b6b](https://linux-hardware.org/?probe=4786139b6b) | Sep 11, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [9d79dbb85f](https://linux-hardware.org/?probe=9d79dbb85f) | Sep 11, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [72680b877a](https://linux-hardware.org/?probe=72680b877a) | Sep 11, 2021 |
| ASUSTek       | ROG STRIX B460-H GAMING     | Desktop     | [f231e22b8e](https://linux-hardware.org/?probe=f231e22b8e) | Sep 11, 2021 |
| Digibras      | NH4CU53                     | Notebook    | [5f2f500f7a](https://linux-hardware.org/?probe=5f2f500f7a) | Sep 10, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [dd09fcf11e](https://linux-hardware.org/?probe=dd09fcf11e) | Sep 10, 2021 |
| Intel         | H61                         | Desktop     | [0010dbcb5e](https://linux-hardware.org/?probe=0010dbcb5e) | Sep 10, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [c5715787c9](https://linux-hardware.org/?probe=c5715787c9) | Sep 10, 2021 |
| ASUSTek       | X45U                        | Notebook    | [ebb2079624](https://linux-hardware.org/?probe=ebb2079624) | Sep 10, 2021 |
| HP            | 872E                        | Mini pc     | [137e91b812](https://linux-hardware.org/?probe=137e91b812) | Sep 10, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [dc65befff1](https://linux-hardware.org/?probe=dc65befff1) | Sep 10, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [46dcdb6184](https://linux-hardware.org/?probe=46dcdb6184) | Sep 10, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [e5b03fa6d6](https://linux-hardware.org/?probe=e5b03fa6d6) | Sep 10, 2021 |
| Dell          | 0F428D A00                  | Desktop     | [c1a8da1f2a](https://linux-hardware.org/?probe=c1a8da1f2a) | Sep 10, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [0c8b9d0704](https://linux-hardware.org/?probe=0c8b9d0704) | Sep 10, 2021 |
| Positivo      | C14RV01                     | Notebook    | [fc6fa07b38](https://linux-hardware.org/?probe=fc6fa07b38) | Sep 10, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [6c52ffbc68](https://linux-hardware.org/?probe=6c52ffbc68) | Sep 10, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [dd8d58ee6a](https://linux-hardware.org/?probe=dd8d58ee6a) | Sep 10, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [4a85971cce](https://linux-hardware.org/?probe=4a85971cce) | Sep 09, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [797c4816b1](https://linux-hardware.org/?probe=797c4816b1) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [3ea6af2159](https://linux-hardware.org/?probe=3ea6af2159) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [981856c740](https://linux-hardware.org/?probe=981856c740) | Sep 09, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [8dfaed35a4](https://linux-hardware.org/?probe=8dfaed35a4) | Sep 09, 2021 |
| ASUSTek       | K84C                        | Notebook    | [6a6f283e0f](https://linux-hardware.org/?probe=6a6f283e0f) | Sep 09, 2021 |
| Itautec       | Infoway a7420               | Notebook    | [282046f0c0](https://linux-hardware.org/?probe=282046f0c0) | Sep 09, 2021 |
| Dell          | Inspiron 7348               | Notebook    | [d0d5054fe1](https://linux-hardware.org/?probe=d0d5054fe1) | Sep 09, 2021 |
| Gigabyte      | Z170M-D3H DDR3-CF           | Desktop     | [e81b4b3e42](https://linux-hardware.org/?probe=e81b4b3e42) | Sep 09, 2021 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [844d7b2492](https://linux-hardware.org/?probe=844d7b2492) | Sep 09, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [7add887914](https://linux-hardware.org/?probe=7add887914) | Sep 08, 2021 |
| Dell          | 0X9680                      | Desktop     | [e59ed269a8](https://linux-hardware.org/?probe=e59ed269a8) | Sep 08, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [8944573827](https://linux-hardware.org/?probe=8944573827) | Sep 08, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [527f58e3a8](https://linux-hardware.org/?probe=527f58e3a8) | Sep 08, 2021 |
| HP            | Pavilion dv4-1120br         | Notebook    | [07bd9042be](https://linux-hardware.org/?probe=07bd9042be) | Sep 08, 2021 |
| ASRock        | N68-S3 FX                   | Desktop     | [6cd6e2e46b](https://linux-hardware.org/?probe=6cd6e2e46b) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion dv4-1120br         | Notebook    | [e56dba587b](https://linux-hardware.org/?probe=e56dba587b) | Sep 08, 2021 |
| HP            | G42                         | Notebook    | [bd7069bf8d](https://linux-hardware.org/?probe=bd7069bf8d) | Sep 07, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [6eb800a8c2](https://linux-hardware.org/?probe=6eb800a8c2) | Sep 07, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [62020026f9](https://linux-hardware.org/?probe=62020026f9) | Sep 07, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [550876baee](https://linux-hardware.org/?probe=550876baee) | Sep 07, 2021 |
| Acer          | V5-171                      | Notebook    | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [ff1e6a6f98](https://linux-hardware.org/?probe=ff1e6a6f98) | Sep 07, 2021 |
| Positivo      | POS-EINM70CS POSITIVO       | Desktop     | [e9b6332a1f](https://linux-hardware.org/?probe=e9b6332a1f) | Sep 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [1b6daffa3e](https://linux-hardware.org/?probe=1b6daffa3e) | Sep 07, 2021 |
| Positivo      | MOBILE                      | Notebook    | [dbef32639d](https://linux-hardware.org/?probe=dbef32639d) | Sep 07, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [9bab4b76ff](https://linux-hardware.org/?probe=9bab4b76ff) | Sep 07, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [305d566f57](https://linux-hardware.org/?probe=305d566f57) | Sep 07, 2021 |
| LG Electro... | S425-L.BC24P1               | Notebook    | [f3a726fe5e](https://linux-hardware.org/?probe=f3a726fe5e) | Sep 06, 2021 |
| ASRock        | AM1B-ITX                    | Desktop     | [e4df21ea0c](https://linux-hardware.org/?probe=e4df21ea0c) | Sep 06, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [6d486e0e31](https://linux-hardware.org/?probe=6d486e0e31) | Sep 06, 2021 |
| Positivo      | MOBILE                      | Notebook    | [a309a16af9](https://linux-hardware.org/?probe=a309a16af9) | Sep 06, 2021 |
| Samsung       | 550XBE/350XBE               | Notebook    | [b6ebf59cfa](https://linux-hardware.org/?probe=b6ebf59cfa) | Sep 06, 2021 |
| Positivo      | POS-EIH61CE SIM             | Desktop     | [fa2919c4c1](https://linux-hardware.org/?probe=fa2919c4c1) | Sep 06, 2021 |
| Unknown       | Phitronics G41-M3           | Desktop     | [56357dd4af](https://linux-hardware.org/?probe=56357dd4af) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [694b8d27de](https://linux-hardware.org/?probe=694b8d27de) | Sep 06, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [b6e28c84c8](https://linux-hardware.org/?probe=b6e28c84c8) | Sep 06, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [889fd56c8b](https://linux-hardware.org/?probe=889fd56c8b) | Sep 05, 2021 |
| Dell          | Inspiron N4050              | Notebook    | [486c5704ac](https://linux-hardware.org/?probe=486c5704ac) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | Notebook    | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Lenovo        | ThinkPad P50 20EQS64N1N     | Notebook    | [51637c3908](https://linux-hardware.org/?probe=51637c3908) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [e4b4aa030b](https://linux-hardware.org/?probe=e4b4aa030b) | Sep 05, 2021 |
| Acer          | Aspire 6935                 | Notebook    | [6380b270a4](https://linux-hardware.org/?probe=6380b270a4) | Sep 05, 2021 |
| Dell          | System Vostro 3460          | Notebook    | [e725d75229](https://linux-hardware.org/?probe=e725d75229) | Sep 05, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [422c5c70dc](https://linux-hardware.org/?probe=422c5c70dc) | Sep 05, 2021 |
| PCWare        | CAPE7 847                   | Desktop     | [0304b8445b](https://linux-hardware.org/?probe=0304b8445b) | Sep 05, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [20f947223f](https://linux-hardware.org/?probe=20f947223f) | Sep 05, 2021 |
| ASUSTek       | P5P41C                      | Desktop     | [e68f372c7b](https://linux-hardware.org/?probe=e68f372c7b) | Sep 05, 2021 |
| ASUSTek       | K8N                         | Desktop     | [224c8289b1](https://linux-hardware.org/?probe=224c8289b1) | Sep 05, 2021 |
| Acer          | Aspire 4736Z                | Notebook    | [4e468942bb](https://linux-hardware.org/?probe=4e468942bb) | Sep 05, 2021 |
| Acer          | Aspire 4736Z                | Notebook    | [fdc2390413](https://linux-hardware.org/?probe=fdc2390413) | Sep 05, 2021 |
| Dell          | Inspiron N4050              | Notebook    | [b86818b509](https://linux-hardware.org/?probe=b86818b509) | Sep 05, 2021 |
| PCWare        | IPMH61R1                    | Desktop     | [f18e73b554](https://linux-hardware.org/?probe=f18e73b554) | Sep 05, 2021 |
| Intel         | SharkBay Platform           | Notebook    | [a19a4b3125](https://linux-hardware.org/?probe=a19a4b3125) | Sep 05, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [e0579175c3](https://linux-hardware.org/?probe=e0579175c3) | Sep 05, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [340d7d28d0](https://linux-hardware.org/?probe=340d7d28d0) | Sep 05, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [a1dd62b9c8](https://linux-hardware.org/?probe=a1dd62b9c8) | Sep 04, 2021 |
| Dell          | Latitude 3490               | Notebook    | [304e16b939](https://linux-hardware.org/?probe=304e16b939) | Sep 04, 2021 |
| Dell          | Latitude 3490               | Notebook    | [edc14d7a25](https://linux-hardware.org/?probe=edc14d7a25) | Sep 04, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [e32db7a4ce](https://linux-hardware.org/?probe=e32db7a4ce) | Sep 04, 2021 |
| Positivo      | MOBILE                      | Notebook    | [6d447067b0](https://linux-hardware.org/?probe=6d447067b0) | Sep 04, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [5fa8f9c97d](https://linux-hardware.org/?probe=5fa8f9c97d) | Sep 04, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [107f6fe7d8](https://linux-hardware.org/?probe=107f6fe7d8) | Sep 04, 2021 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [73b5c289e2](https://linux-hardware.org/?probe=73b5c289e2) | Sep 04, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [a2b6653813](https://linux-hardware.org/?probe=a2b6653813) | Sep 04, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [01078048fe](https://linux-hardware.org/?probe=01078048fe) | Sep 04, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [1503acee14](https://linux-hardware.org/?probe=1503acee14) | Sep 04, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [328451404d](https://linux-hardware.org/?probe=328451404d) | Sep 04, 2021 |
| Lenovo        | IdeaPad G485 QAWGE          | Notebook    | [e4e83ad591](https://linux-hardware.org/?probe=e4e83ad591) | Sep 04, 2021 |
| HP            | G42                         | Notebook    | [cace650582](https://linux-hardware.org/?probe=cace650582) | Sep 03, 2021 |
| Positivo      | S14CT01                     | Notebook    | [f766cef59e](https://linux-hardware.org/?probe=f766cef59e) | Sep 03, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [c080ec772f](https://linux-hardware.org/?probe=c080ec772f) | Sep 03, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [0d9d760140](https://linux-hardware.org/?probe=0d9d760140) | Sep 03, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [638ad20012](https://linux-hardware.org/?probe=638ad20012) | Sep 03, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [556461d567](https://linux-hardware.org/?probe=556461d567) | Sep 03, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [ba8a47c4f2](https://linux-hardware.org/?probe=ba8a47c4f2) | Sep 03, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [cf87648c88](https://linux-hardware.org/?probe=cf87648c88) | Sep 03, 2021 |
| HP            | Pavilion g4                 | Notebook    | [383792988a](https://linux-hardware.org/?probe=383792988a) | Sep 02, 2021 |
| Lenovo        | SDK0E50510 WIN 262508077... | Desktop     | [69e28c4c65](https://linux-hardware.org/?probe=69e28c4c65) | Sep 02, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [f769c7b8bb](https://linux-hardware.org/?probe=f769c7b8bb) | Sep 02, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [71929d46ed](https://linux-hardware.org/?probe=71929d46ed) | Sep 02, 2021 |
| Foxconn       | M61PMV FAB                  | Desktop     | [9a3fc925aa](https://linux-hardware.org/?probe=9a3fc925aa) | Sep 02, 2021 |
| Foxconn       | M61PMV FAB                  | Desktop     | [880a64fe95](https://linux-hardware.org/?probe=880a64fe95) | Sep 02, 2021 |
| Toshiba       | Satellite C655              | Notebook    | [1a24fad6d9](https://linux-hardware.org/?probe=1a24fad6d9) | Sep 02, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [7a7454a9ae](https://linux-hardware.org/?probe=7a7454a9ae) | Sep 02, 2021 |
| Acer          | Unknown                     | Notebook    | [e05afa34e0](https://linux-hardware.org/?probe=e05afa34e0) | Sep 02, 2021 |
| Toshiba       | IS 1412                     | Notebook    | [ae90a1e459](https://linux-hardware.org/?probe=ae90a1e459) | Sep 02, 2021 |
| HP            | Pavilion 14                 | Notebook    | [351766240c](https://linux-hardware.org/?probe=351766240c) | Sep 02, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [724ad5d6a2](https://linux-hardware.org/?probe=724ad5d6a2) | Sep 02, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [ac85e51b51](https://linux-hardware.org/?probe=ac85e51b51) | Sep 02, 2021 |
| Positivo      | C41TB                       | Notebook    | [d100e19cde](https://linux-hardware.org/?probe=d100e19cde) | Sep 01, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2bcede7edc](https://linux-hardware.org/?probe=2bcede7edc) | Sep 01, 2021 |
| Positivo      | C41TB                       | Notebook    | [e904092d0d](https://linux-hardware.org/?probe=e904092d0d) | Sep 01, 2021 |
| IBM           | System Planar Card SIT      | Desktop     | [a6fae29097](https://linux-hardware.org/?probe=a6fae29097) | Sep 01, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [46a61ffaa2](https://linux-hardware.org/?probe=46a61ffaa2) | Aug 31, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [85fa26ea9e](https://linux-hardware.org/?probe=85fa26ea9e) | Aug 31, 2021 |
| PCWare        | IPMH61R1                    | Desktop     | [2479b1480b](https://linux-hardware.org/?probe=2479b1480b) | Aug 31, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 1455      | 14.23%  |
| Ubuntu 18.04      | 1029      | 10.07%  |
| OpenMandriva 4.2  | 326       | 3.19%   |
| Pop!_OS 20.04     | 313       | 3.06%   |
| Linux Mint 20     | 312       | 3.05%   |
| Linux Mint 19.3   | 277       | 2.71%   |
| Linux Mint 19.1   | 234       | 2.29%   |
| Ubuntu 19.04      | 218       | 2.13%   |
| Linux Mint 20.1   | 195       | 1.91%   |
| KDE neon 20.04    | 180       | 1.76%   |
| Ubuntu 19.10      | 173       | 1.69%   |
| Linux Mint 20.2   | 166       | 1.62%   |
| Arch              | 161       | 1.57%   |
| Debian 10         | 153       | 1.5%    |
| Zorin 15          | 143       | 1.4%    |
| Manjaro           | 135       | 1.32%   |
| Pop!_OS 21.04     | 127       | 1.24%   |
| Pop!_OS 20.10     | 126       | 1.23%   |
| Fedora 34         | 118       | 1.15%   |
| Xubuntu 20.04     | 113       | 1.11%   |
| OpenMandriva 4.3  | 113       | 1.11%   |
| Fedora 32         | 112       | 1.1%    |
| Pop!_OS 21.10     | 107       | 1.05%   |
| Fedora 33         | 105       | 1.03%   |
| Fedora 35         | 103       | 1.01%   |
| Ubuntu 16.04      | 101       | 0.99%   |
| Linux Mint 19.2   | 101       | 0.99%   |
| Kubuntu 20.04     | 101       | 0.99%   |
| Linux Mint 20.3   | 99        | 0.97%   |
| Ubuntu 20.10      | 98        | 0.96%   |
| Zorin 16          | 95        | 0.93%   |
| Ubuntu MATE 20.04 | 93        | 0.91%   |
| Debian 11         | 92        | 0.9%    |
| Ubuntu 18.10      | 83        | 0.81%   |
| Endless 3.7.8     | 77        | 0.75%   |
| Arch Rolling      | 76        | 0.74%   |
| Ubuntu 21.10      | 75        | 0.73%   |
| Endless 3.9.5     | 72        | 0.7%    |
| Xubuntu 18.04     | 71        | 0.69%   |
| Ubuntu 21.04      | 66        | 0.65%   |
| Fedora 31         | 59        | 0.58%   |
| Endless 3.9.1     | 55        | 0.54%   |
| Endless 3.8.6     | 55        | 0.54%   |
| Endless 3.8.7     | 53        | 0.52%   |
| Endless 3.9.4     | 48        | 0.47%   |
| Endless 3.8.4     | 48        | 0.47%   |
| Endless 3.7.4     | 46        | 0.45%   |
| Endless 3.9.3     | 45        | 0.44%   |
| LMDE 4            | 42        | 0.41%   |
| Debian Testing    | 42        | 0.41%   |
| Debian 9          | 41        | 0.4%    |
| Manjaro 20.0.3    | 39        | 0.38%   |
| Lubuntu 20.04     | 38        | 0.37%   |
| Endless 3.8.3     | 38        | 0.37%   |
| Fedora 30         | 37        | 0.36%   |
| Linux Mint 19     | 36        | 0.35%   |
| ROSA R10          | 34        | 0.33%   |
| KDE neon 18.04    | 33        | 0.32%   |
| Endless 3.8.5     | 33        | 0.32%   |
| Endless 3.8.0     | 33        | 0.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3248      | 33.04%  |
| Linux Mint    | 1375      | 13.99%  |
| Endless       | 927       | 9.43%   |
| Pop!_OS       | 663       | 6.74%   |
| Fedora        | 511       | 5.2%    |
| OpenMandriva  | 467       | 4.75%   |
| Debian        | 326       | 3.32%   |
| Manjaro       | 294       | 2.99%   |
| Zorin         | 247       | 2.51%   |
| Arch          | 228       | 2.32%   |
| KDE neon      | 210       | 2.14%   |
| Xubuntu       | 201       | 2.04%   |
| Kubuntu       | 166       | 1.69%   |
| Ubuntu MATE   | 121       | 1.23%   |
| ROSA          | 111       | 1.13%   |
| Lubuntu       | 89        | 0.91%   |
| openSUSE      | 75        | 0.76%   |
| Elementary    | 67        | 0.68%   |
| LMDE          | 48        | 0.49%   |
| Deepin        | 45        | 0.46%   |
| LinuxFX       | 38        | 0.39%   |
| Kali          | 38        | 0.39%   |
| Ubuntu Budgie | 33        | 0.34%   |
| BlackPanther  | 30        | 0.31%   |
| ArcoLinux     | 30        | 0.31%   |
| Clear Linux   | 29        | 0.3%    |
| CentOS        | 26        | 0.26%   |
| Peppermint    | 14        | 0.14%   |
| EndeavourOS   | 13        | 0.13%   |
| Gentoo        | 12        | 0.12%   |
| BigLinux      | 12        | 0.12%   |
| Solus         | 11        | 0.11%   |
| Parrot        | 11        | 0.11%   |
| Reborn OS     | 10        | 0.1%    |
| MX            | 10        | 0.1%    |
| Void Linux    | 7         | 0.07%   |
| Slackware     | 6         | 0.06%   |
| Garuda Linux  | 6         | 0.06%   |
| Devuan        | 5         | 0.05%   |
| PCLinuxOS     | 4         | 0.04%   |
| Mageia        | 4         | 0.04%   |
| RHEL          | 3         | 0.03%   |
| PostmarketOS  | 3         | 0.03%   |
| Oracle Linux  | 3         | 0.03%   |
| GNOME OS      | 3         | 0.03%   |
| Chrome OS     | 3         | 0.03%   |
| BunsenLabs    | 3         | 0.03%   |
| Artix         | 3         | 0.03%   |
| UbuntuDDE     | 2         | 0.02%   |
| Sparky        | 2         | 0.02%   |
| Raspbian      | 2         | 0.02%   |
| Makulu        | 2         | 0.02%   |
| Linux Lite    | 2         | 0.02%   |
| Funtoo        | 2         | 0.02%   |
| E-On          | 2         | 0.02%   |
| BlackArch     | 2         | 0.02%   |
| Alpine        | 2         | 0.02%   |
| Xero          | 1         | 0.01%   |
| Septor        | 1         | 0.01%   |
| Salient OS    | 1         | 0.01%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 708       | 6.38%   |
| 5.10.14-desktop-1omv4002 | 316       | 2.85%   |
| 5.8.0-14-generic         | 278       | 2.5%    |
| 4.15.0-46-generic        | 156       | 1.41%   |
| 5.3.0-28-generic         | 145       | 1.31%   |
| 5.4.0-48-generic         | 138       | 1.24%   |
| 5.4.0-19-generic         | 137       | 1.23%   |
| 5.4.0-7634-generic       | 124       | 1.12%   |
| 5.4.0-40-generic         | 113       | 1.02%   |
| 5.16.7-desktop-1omv4003  | 113       | 1.02%   |
| 5.4.0-58-generic         | 108       | 0.97%   |
| 5.4.0-52-generic         | 105       | 0.95%   |
| 5.4.0-26-generic         | 104       | 0.94%   |
| 5.4.0-47-generic         | 97        | 0.87%   |
| 4.18.0-15-generic        | 97        | 0.87%   |
| 5.3.0-40-generic         | 88        | 0.79%   |
| 5.3.0-46-generic         | 79        | 0.71%   |
| 5.11.0-7620-generic      | 78        | 0.7%    |
| 5.0.0-32-generic         | 77        | 0.69%   |
| 5.0.0-37-generic         | 73        | 0.66%   |
| 4.15.0-20-generic        | 72        | 0.65%   |
| 5.4.0-70-generic         | 70        | 0.63%   |
| 5.4.0-72-generic         | 67        | 0.6%    |
| 5.4.0-80-generic         | 64        | 0.58%   |
| 5.4.0-65-generic         | 64        | 0.58%   |
| 5.3.0-23-generic         | 63        | 0.57%   |
| 5.4.0-37-generic         | 62        | 0.56%   |
| 5.4.0-29-generic         | 62        | 0.56%   |
| 4.18.0-16-generic        | 62        | 0.56%   |
| 5.4.0-39-generic         | 60        | 0.54%   |
| 5.11.0-37-generic        | 60        | 0.54%   |
| 5.0.0-25-generic         | 60        | 0.54%   |
| 5.8.0-7630-generic       | 59        | 0.53%   |
| 5.3.0-19-generic         | 58        | 0.52%   |
| 5.11.0-27-generic        | 58        | 0.52%   |
| 5.4.0-54-generic         | 57        | 0.51%   |
| 5.3.0-51-generic         | 57        | 0.51%   |
| 5.11.0-35-generic        | 56        | 0.5%    |
| 4.15.0-47-generic        | 56        | 0.5%    |
| 5.3.0-53-generic         | 55        | 0.5%    |
| 5.0.0-13-generic         | 55        | 0.5%    |
| 5.4.0-74-generic         | 54        | 0.49%   |
| 5.4.0-45-generic         | 54        | 0.49%   |
| 4.18.0-17-generic        | 54        | 0.49%   |
| 5.4.0-66-generic         | 53        | 0.48%   |
| 5.13.0-30-generic        | 53        | 0.48%   |
| 5.4.0-33-generic         | 51        | 0.46%   |
| 5.8.0-50-generic         | 50        | 0.45%   |
| 5.8.0-43-generic         | 50        | 0.45%   |
| 4.15.0-54-generic        | 50        | 0.45%   |
| 5.4.0-73-generic         | 48        | 0.43%   |
| 5.0.0-23-generic         | 48        | 0.43%   |
| 4.18.0-25-generic        | 48        | 0.43%   |
| 5.4.0-7642-generic       | 47        | 0.42%   |
| 5.8.0-44-generic         | 46        | 0.41%   |
| 5.4.0-91-generic         | 46        | 0.41%   |
| 5.13.0-39-generic        | 46        | 0.41%   |
| 5.8.0-7642-generic       | 45        | 0.41%   |
| 5.4.0-56-generic         | 45        | 0.41%   |
| 5.3.0-42-generic         | 43        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 2847      | 27.32%  |
| 4.15.0  | 929       | 8.91%   |
| 5.8.0   | 858       | 8.23%   |
| 5.3.0   | 798       | 7.66%   |
| 5.11.0  | 640       | 6.14%   |
| 5.0.0   | 558       | 5.35%   |
| 4.18.0  | 413       | 3.96%   |
| 5.13.0  | 363       | 3.48%   |
| 5.10.14 | 318       | 3.05%   |
| 4.19.0  | 181       | 1.74%   |
| 5.10.0  | 126       | 1.21%   |
| 5.16.7  | 113       | 1.08%   |
| 5.7.9   | 47        | 0.45%   |
| 4.4.0   | 43        | 0.41%   |
| 5.15.0  | 42        | 0.4%    |
| 5.16.11 | 40        | 0.38%   |
| 4.9.0   | 37        | 0.36%   |
| 5.15.5  | 31        | 0.3%    |
| 5.7.0   | 30        | 0.29%   |
| 5.15.15 | 30        | 0.29%   |
| 5.9.16  | 29        | 0.28%   |
| 4.9.60  | 27        | 0.26%   |
| 5.6.19  | 26        | 0.25%   |
| 5.3.18  | 25        | 0.24%   |
| 4.18.16 | 25        | 0.24%   |
| 5.7.10  | 22        | 0.21%   |
| 5.16.15 | 22        | 0.21%   |
| 5.13.19 | 22        | 0.21%   |
| 5.14.0  | 21        | 0.2%    |
| 5.11.12 | 21        | 0.2%    |
| 5.15.8  | 20        | 0.19%   |
| 5.12.4  | 20        | 0.19%   |
| 5.9.11  | 19        | 0.18%   |
| 5.6.15  | 19        | 0.18%   |
| 4.9.20  | 18        | 0.17%   |
| 5.8.18  | 16        | 0.15%   |
| 5.15.11 | 16        | 0.15%   |
| 5.13.13 | 16        | 0.15%   |
| 5.16.19 | 15        | 0.14%   |
| 5.6.0   | 14        | 0.13%   |
| 5.9.0   | 13        | 0.12%   |
| 5.8.15  | 13        | 0.12%   |
| 5.6.14  | 13        | 0.12%   |
| 5.3.7   | 13        | 0.12%   |
| 5.12.13 | 13        | 0.12%   |
| 5.9.1   | 12        | 0.12%   |
| 5.4.52  | 12        | 0.12%   |
| 5.12.9  | 12        | 0.12%   |
| 4.13.0  | 12        | 0.12%   |
| 5.8.16  | 11        | 0.11%   |
| 5.8.10  | 11        | 0.11%   |
| 5.7.8   | 11        | 0.11%   |
| 5.7.7   | 11        | 0.11%   |
| 5.6.6   | 11        | 0.11%   |
| 5.4.50  | 11        | 0.11%   |
| 5.16.18 | 11        | 0.11%   |
| 5.16.0  | 11        | 0.11%   |
| 5.15.23 | 11        | 0.11%   |
| 5.14.14 | 11        | 0.11%   |
| 5.14.10 | 11        | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 2969      | 28.82%  |
| 5.8     | 974       | 9.46%   |
| 4.15    | 929       | 9.02%   |
| 5.3     | 868       | 8.43%   |
| 5.11    | 732       | 7.11%   |
| 5.10    | 617       | 5.99%   |
| 5.0     | 600       | 5.82%   |
| 5.13    | 453       | 4.4%    |
| 4.18    | 446       | 4.33%   |
| 5.16    | 269       | 2.61%   |
| 5.15    | 221       | 2.15%   |
| 4.19    | 216       | 2.1%    |
| 5.7     | 173       | 1.68%   |
| 5.6     | 126       | 1.22%   |
| 5.9     | 113       | 1.1%    |
| 5.12    | 112       | 1.09%   |
| 5.14    | 103       | 1%      |
| 4.9     | 102       | 0.99%   |
| 5.5     | 50        | 0.49%   |
| 4.4     | 48        | 0.47%   |
| 5.1     | 40        | 0.39%   |
| 5.17    | 39        | 0.38%   |
| 5.2     | 29        | 0.28%   |
| 3.10    | 14        | 0.14%   |
| 4.13    | 13        | 0.13%   |
| 4.1     | 11        | 0.11%   |
| 4.20    | 10        | 0.1%    |
| 4.10    | 7         | 0.07%   |
| 4.12    | 6         | 0.06%   |
| 4.14    | 5         | 0.05%   |
| 4.8     | 3         | 0.03%   |
| 4.17    | 2         | 0.02%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 9167      | 96.83%  |
| i686    | 281       | 2.97%   |
| aarch64 | 12        | 0.13%   |
| armv7l  | 7         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 4469      | 45.31%  |
| Unknown                  | 1755      | 17.79%  |
| KDE5                     | 940       | 9.53%   |
| X-Cinnamon               | 759       | 7.7%    |
| XFCE                     | 635       | 6.44%   |
| KDE                      | 311       | 3.15%   |
| MATE                     | 295       | 2.99%   |
| Cinnamon                 | 204       | 2.07%   |
| Unity                    | 76        | 0.77%   |
| LXQt                     | 76        | 0.77%   |
| KDE4                     | 66        | 0.67%   |
| Pantheon                 | 55        | 0.56%   |
| Deepin                   | 54        | 0.55%   |
| Budgie                   | 51        | 0.52%   |
| LXDE                     | 46        | 0.47%   |
| i3                       | 24        | 0.24%   |
| GNOME Flashback          | 13        | 0.13%   |
| GNOME Classic            | 11        | 0.11%   |
| awesome                  | 7         | 0.07%   |
| openbox                  | 4         | 0.04%   |
| Enlightenment            | 4         | 0.04%   |
| sway                     | 2         | 0.02%   |
| xmonad                   | 1         | 0.01%   |
| Trinity                  | 1         | 0.01%   |
| qtile                    | 1         | 0.01%   |
| bspwm                    | 1         | 0.01%   |
| 03WindowMaker            | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 8070      | 83.56%  |
| Unknown | 857       | 8.87%   |
| Wayland | 671       | 6.95%   |
| Tty     | 58        | 0.6%    |
| Web     | 2         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6602      | 67.88%  |
| GDM     | 1038      | 10.67%  |
| SDDM    | 899       | 9.24%   |
| TDM     | 526       | 5.41%   |
| LightDM | 351       | 3.61%   |
| GDM3    | 229       | 2.35%   |
| KDM     | 66        | 0.68%   |
| XDM     | 6         | 0.06%   |
| SLiM    | 4         | 0.04%   |
| LXDM    | 3         | 0.03%   |
| MDM     | 2         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pt_BR       | 6250      | 64.61%  |
| Unknown     | 1681      | 17.38%  |
| en_US       | 1501      | 15.52%  |
| C           | 131       | 1.35%   |
| en_GB       | 35        | 0.36%   |
| pt_PT       | 30        | 0.31%   |
| es_ES       | 13        | 0.13%   |
| en_CA       | 6         | 0.06%   |
| de_DE       | 5         | 0.05%   |
| fr_FR       | 4         | 0.04%   |
| POSIX       | 3         | 0.03%   |
| es_MX       | 2         | 0.02%   |
| ru_RU       | 1         | 0.01%   |
| pt_BR.UTF8  | 1         | 0.01%   |
| ja_JP       | 1         | 0.01%   |
| it_IT       | 1         | 0.01%   |
| es_CL       | 1         | 0.01%   |
| es_AR       | 1         | 0.01%   |
| eo          | 1         | 0.01%   |
| en_US.utf-8 | 1         | 0.01%   |
| en_US.UFT-8 | 1         | 0.01%   |
| en_IN       | 1         | 0.01%   |
| em_US       | 1         | 0.01%   |
| C.UTF8      | 1         | 0.01%   |
| ar_EG       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 5559      | 57.55%  |
| EFI  | 4101      | 42.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 7735      | 80.16%  |
| Unknown | 680       | 7.05%   |
| Overlay | 617       | 6.39%   |
| Btrfs   | 454       | 4.7%    |
| Xfs     | 68        | 0.7%    |
| Zfs     | 31        | 0.32%   |
| Tmpfs   | 20        | 0.21%   |
| Ext3    | 17        | 0.18%   |
| Ext2    | 16        | 0.17%   |
| F2fs    | 9         | 0.09%   |
| Aufs    | 3         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6847      | 70.97%  |
| GPT     | 1776      | 18.41%  |
| MBR     | 1025      | 10.62%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 8573      | 89.4%   |
| Yes       | 1016      | 10.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7090      | 73.84%  |
| Yes       | 2512      | 26.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1543      | 16.31%  |
| ASUSTek Computer        | 1242      | 13.13%  |
| Acer                    | 1174      | 12.41%  |
| Lenovo                  | 789       | 8.34%   |
| Gigabyte Technology     | 632       | 6.68%   |
| Positivo                | 556       | 5.88%   |
| Hewlett-Packard         | 536       | 5.67%   |
| Samsung Electronics     | 468       | 4.95%   |
| ASRock                  | 316       | 3.34%   |
| Intel                   | 315       | 3.33%   |
| Unknown                 | 192       | 2.03%   |
| MSI                     | 165       | 1.74%   |
| Sony                    | 130       | 1.37%   |
| LG Electronics          | 101       | 1.07%   |
| Semp Toshiba            | 96        | 1.01%   |
| Itautec                 | 96        | 1.01%   |
| Apple                   | 93        | 0.98%   |
| PCWare                  | 87        | 0.92%   |
| Biostar                 | 66        | 0.7%    |
| Pegatron                | 58        | 0.61%   |
| Digibras                | 58        | 0.61%   |
| ECS                     | 52        | 0.55%   |
| Avell High Performance  | 52        | 0.55%   |
| OEM                     | 41        | 0.43%   |
| Philco                  | 40        | 0.42%   |
| Multilaser              | 36        | 0.38%   |
| Toshiba                 | 32        | 0.34%   |
| Megaware                | 27        | 0.29%   |
| Positivo Bahia - VAIO   | 25        | 0.26%   |
| Compaq                  | 25        | 0.26%   |
| Notebook                | 22        | 0.23%   |
| Huanan                  | 21        | 0.22%   |
| Foxconn                 | 20        | 0.21%   |
| Compal                  | 17        | 0.18%   |
| Login Informatica       | 16        | 0.17%   |
| Gateway                 | 16        | 0.17%   |
| Qbex                    | 14        | 0.15%   |
| Supermicro              | 13        | 0.14%   |
| Google                  | 13        | 0.14%   |
| Clevo                   | 12        | 0.13%   |
| CCE                     | 11        | 0.12%   |
| Raspberry Pi Foundation | 10        | 0.11%   |
| PCChips                 | 9         | 0.1%    |
| eMachines               | 9         | 0.1%    |
| Quanta                  | 8         | 0.08%   |
| Digiboard               | 8         | 0.08%   |
| Daten Tecnologia        | 8         | 0.08%   |
| AMD                     | 8         | 0.08%   |
| VS Company              | 7         | 0.07%   |
| Microsoft               | 7         | 0.07%   |
| Digitron                | 7         | 0.07%   |
| Alienware               | 7         | 0.07%   |
| INTELBRAS               | 6         | 0.06%   |
| AMI                     | 6         | 0.06%   |
| Standard                | 5         | 0.05%   |
| Phitronics              | 5         | 0.05%   |
| LNV                     | 5         | 0.05%   |
| IBM                     | 5         | 0.05%   |
| Centrium                | 5         | 0.05%   |
| Timi                    | 4         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 232       | 2.45%   |
| Acer Nitro AN515-54                         | 129       | 1.36%   |
| ASUS All Series                             | 117       | 1.24%   |
| Positivo MOBILE                             | 114       | 1.2%    |
| Acer Aspire A315-53                         | 64        | 0.68%   |
| Samsung 340XAA/350XAA/550XAA                | 58        | 0.61%   |
| Intel H61                                   | 51        | 0.54%   |
| Dell Inspiron 3583                          | 51        | 0.54%   |
| Acer Nitro AN517-51                         | 50        | 0.53%   |
| Acer Aspire A315-34                         | 50        | 0.53%   |
| Acer Nitro AN515-44                         | 49        | 0.52%   |
| Dell Inspiron 5566                          | 48        | 0.51%   |
| ASUS PRIME B450M-GAMING/BR                  | 48        | 0.51%   |
| Lenovo IdeaPad S145-15API 81V7              | 47        | 0.5%    |
| Lenovo IdeaPad 330-15IKB 81FE               | 47        | 0.5%    |
| Acer Nitro AN515-43                         | 44        | 0.47%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 43        | 0.45%   |
| ASRock A320M-HD                             | 43        | 0.45%   |
| Dell Inspiron 15-3567                       | 42        | 0.44%   |
| Acer Aspire A515-51                         | 42        | 0.44%   |
| ASUS PRIME A320M-K/BR                       | 40        | 0.42%   |
| Semp Toshiba STI                            | 39        | 0.41%   |
| Itautec Infoway                             | 39        | 0.41%   |
| ASUS M5A78L-M LX/BR                         | 39        | 0.41%   |
| HP G42                                      | 38        | 0.4%    |
| Acer Nitro AN515-52                         | 35        | 0.37%   |
| Dell Inspiron 3421                          | 34        | 0.36%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 32        | 0.34%   |
| Gigabyte H61M-S1                            | 31        | 0.33%   |
| Positivo S14CT01                            | 30        | 0.32%   |
| Dell Inspiron N4050                         | 30        | 0.32%   |
| Dell Inspiron 3442                          | 30        | 0.32%   |
| Intel H55                                   | 29        | 0.31%   |
| HP Pavilion g4                              | 29        | 0.31%   |
| Gigabyte A320M-S2H                          | 29        | 0.31%   |
| Dell Inspiron 7520                          | 29        | 0.31%   |
| Samsung 300E5M/300E5L                       | 28        | 0.3%    |
| Gigabyte B75M-D3H                           | 28        | 0.3%    |
| Dell Inspiron 1545                          | 28        | 0.3%    |
| ASUS M5A78L-M PLUS/USB3                     | 28        | 0.3%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 27        | 0.29%   |
| ASUS P8H61-M LX3 R2.0                       | 27        | 0.29%   |
| Acer Aspire E1-571                          | 27        | 0.29%   |
| Dell Inspiron 5437                          | 26        | 0.27%   |
| ASRock N68-S3 FX                            | 26        | 0.27%   |
| Digibras NH4CU53                            | 25        | 0.26%   |
| Digibras NH4CU03                            | 25        | 0.26%   |
| Acer Aspire E5-571                          | 25        | 0.26%   |
| Dell Inspiron 5458                          | 24        | 0.25%   |
| Dell Inspiron 1525                          | 24        | 0.25%   |
| Dell G3 3590                                | 24        | 0.25%   |
| Acer Aspire A515-54G                        | 24        | 0.25%   |
| Dell Inspiron 5423                          | 23        | 0.24%   |
| Dell Inspiron 15 7000 Gaming                | 23        | 0.24%   |
| Acer Nitro AN515-51                         | 23        | 0.24%   |
| Acer Aspire A515-51G                        | 23        | 0.24%   |
| Dell Inspiron 5557                          | 22        | 0.23%   |
| ASUS H61M-A/BR                              | 22        | 0.23%   |
| Dell Inspiron 7560                          | 21        | 0.22%   |
| Dell Inspiron 5537                          | 21        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 925       | 9.78%   |
| Acer Aspire            | 756       | 7.99%   |
| Lenovo IdeaPad         | 374       | 3.95%   |
| Acer Nitro             | 334       | 3.53%   |
| Unknown                | 232       | 2.45%   |
| Dell Vostro            | 182       | 1.92%   |
| ASUS PRIME             | 180       | 1.9%    |
| HP Pavilion            | 173       | 1.83%   |
| Lenovo ThinkPad        | 166       | 1.75%   |
| Dell Latitude          | 133       | 1.41%   |
| Dell OptiPlex          | 130       | 1.37%   |
| ASUS All               | 117       | 1.24%   |
| Positivo Mobile        | 114       | 1.2%    |
| ASUS M5A78L-M          | 101       | 1.07%   |
| Itautec Infoway        | 93        | 0.98%   |
| HP Compaq              | 80        | 0.85%   |
| ASUS P8H61-M           | 67        | 0.71%   |
| ASUS TUF               | 60        | 0.63%   |
| Samsung 340XAA         | 58        | 0.61%   |
| Dell XPS               | 57        | 0.6%    |
| ASUS VivoBook          | 54        | 0.57%   |
| Intel H61              | 53        | 0.56%   |
| Semp Toshiba STI       | 47        | 0.5%    |
| Lenovo ThinkCentre     | 45        | 0.48%   |
| Dell G3                | 44        | 0.47%   |
| ASRock A320M-HD        | 44        | 0.47%   |
| HP ProBook             | 38        | 0.4%    |
| HP G42                 | 38        | 0.4%    |
| ASUS ROG               | 38        | 0.4%    |
| Samsung RV411          | 37        | 0.39%   |
| Intel H55              | 33        | 0.35%   |
| HP EliteBook           | 31        | 0.33%   |
| Gigabyte H61M-S1       | 31        | 0.33%   |
| Positivo S14CT01       | 30        | 0.32%   |
| Gigabyte A320M-S2H     | 29        | 0.31%   |
| Samsung 300E5M         | 28        | 0.3%    |
| Gigabyte B75M-D3H      | 28        | 0.3%    |
| Toshiba Satellite      | 27        | 0.29%   |
| Semp Toshiba IS        | 27        | 0.29%   |
| ASRock N68-S3          | 27        | 0.29%   |
| Gigabyte B450M         | 26        | 0.27%   |
| Acer Predator          | 26        | 0.27%   |
| Gigabyte GA-78LMT-USB3 | 25        | 0.26%   |
| Digibras NH4CU53       | 25        | 0.26%   |
| Digibras NH4CU03       | 25        | 0.26%   |
| Compaq Presario        | 23        | 0.24%   |
| Samsung RV415          | 22        | 0.23%   |
| Lenovo Yoga            | 22        | 0.23%   |
| HP EliteDesk           | 22        | 0.23%   |
| ASUS P5G41T-M          | 22        | 0.23%   |
| ASUS H61M-A            | 22        | 0.23%   |
| Dell Precision         | 21        | 0.22%   |
| Samsung 370E4K         | 20        | 0.21%   |
| Samsung 300E5EV        | 20        | 0.21%   |
| Samsung 270E5J         | 20        | 0.21%   |
| Positivo H14BT58       | 20        | 0.21%   |
| ASRock B450M           | 20        | 0.21%   |
| Samsung 300E4C         | 19        | 0.2%    |
| Positivo Q232A         | 19        | 0.2%    |
| HP ENVY                | 19        | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1036      | 10.95%  |
| 2012    | 1007      | 10.64%  |
| 2011    | 956       | 10.1%   |
| 2018    | 934       | 9.87%   |
| 2017    | 760       | 8.03%   |
| 2013    | 746       | 7.89%   |
| 2010    | 650       | 6.87%   |
| 2016    | 596       | 6.3%    |
| 2014    | 546       | 5.77%   |
| 2009    | 429       | 4.53%   |
| 2015    | 425       | 4.49%   |
| 2008    | 417       | 4.41%   |
| 2020    | 391       | 4.13%   |
| 2007    | 258       | 2.73%   |
| 2021    | 153       | 1.62%   |
| 2006    | 77        | 0.81%   |
| Unknown | 42        | 0.44%   |
| 2005    | 26        | 0.27%   |
| 2004    | 9         | 0.1%    |
| 2022    | 2         | 0.02%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 5655      | 59.77%  |
| Desktop        | 3572      | 37.75%  |
| All in one     | 74        | 0.78%   |
| Convertible    | 64        | 0.68%   |
| Mini pc        | 31        | 0.33%   |
| Server         | 30        | 0.32%   |
| Tablet         | 18        | 0.19%   |
| System on chip | 16        | 0.17%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 8503      | 89.45%  |
| Enabled  | 1003      | 10.55%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9446      | 99.84%  |
| Yes  | 15        | 0.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 2653      | 27.62%  |
| 4.01-8.0        | 2550      | 26.54%  |
| 8.01-16.0       | 1678      | 17.47%  |
| 16.01-24.0      | 1377      | 14.33%  |
| 1.01-2.0        | 703       | 7.32%   |
| 32.01-64.0      | 241       | 2.51%   |
| 2.01-3.0        | 224       | 2.33%   |
| 24.01-32.0      | 67        | 0.7%    |
| 64.01-256.0     | 56        | 0.58%   |
| 0.51-1.0        | 49        | 0.51%   |
| More than 256.0 | 5         | 0.05%   |
| 0.01-0.5        | 2         | 0.02%   |
| Unknown         | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 3981      | 38.2%   |
| 2.01-3.0    | 2825      | 27.11%  |
| 3.01-4.0    | 1261      | 12.1%   |
| 4.01-8.0    | 1144      | 10.98%  |
| 0.51-1.0    | 868       | 8.33%   |
| 8.01-16.0   | 213       | 2.04%   |
| 0.01-0.5    | 98        | 0.94%   |
| 16.01-24.0  | 18        | 0.17%   |
| Unknown     | 5         | 0.05%   |
| 24.01-32.0  | 4         | 0.04%   |
| 32.01-64.0  | 3         | 0.03%   |
| 64.01-256.0 | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6050      | 62.54%  |
| 2       | 2673      | 27.63%  |
| 3       | 539       | 5.57%   |
| 4       | 205       | 2.12%   |
| 0       | 86        | 0.89%   |
| 5       | 62        | 0.64%   |
| 6       | 37        | 0.38%   |
| 7       | 7         | 0.07%   |
| 8       | 6         | 0.06%   |
| 9       | 5         | 0.05%   |
| 18      | 1         | 0.01%   |
| 15      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5670      | 59.5%   |
| Yes       | 3859      | 40.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8797      | 92.86%  |
| No        | 676       | 7.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6918      | 72.67%  |
| No        | 2602      | 27.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4869      | 51.04%  |
| Yes       | 4671      | 48.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 9461      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 1090      | 10.94%  |
| Rio de Janeiro            | 563       | 5.65%   |
| Curitiba                  | 286       | 2.87%   |
| Belo Horizonte            | 285       | 2.86%   |
| BrasГ­lia               | 229       | 2.3%    |
| Porto Alegre              | 225       | 2.26%   |
| Fortaleza                 | 195       | 1.96%   |
| Campinas                  | 152       | 1.53%   |
| Salvador                  | 139       | 1.39%   |
| Recife                    | 135       | 1.35%   |
| Osasco                    | 91        | 0.91%   |
| GoiГўnia                | 89        | 0.89%   |
| Natal                     | 82        | 0.82%   |
| BrasÃ­lia               | 80        | 0.8%    |
| Guarulhos                 | 79        | 0.79%   |
| Manaus                    | 77        | 0.77%   |
| FlorianГіpolis          | 76        | 0.76%   |
| Santo AndrГ©            | 74        | 0.74%   |
| Campo Grande              | 66        | 0.66%   |
| Sorocaba                  | 63        | 0.63%   |
| Joinville                 | 61        | 0.61%   |
| Teresina                  | 58        | 0.58%   |
| VitГіria                | 53        | 0.53%   |
| SГЈo JosГ© dos Campos | 53        | 0.53%   |
| JundiaГ­                | 53        | 0.53%   |
| NiterГіi                | 50        | 0.5%    |
| Juiz de Fora              | 49        | 0.49%   |
| Londrina                  | 48        | 0.48%   |
| Aracaju                   | 48        | 0.48%   |
| BelГ©m                  | 45        | 0.45%   |
| SГЈo LuГ­s            | 44        | 0.44%   |
| Blumenau                  | 44        | 0.44%   |
| UberlГўndia             | 43        | 0.43%   |
| JoГЈo Pessoa            | 42        | 0.42%   |
| Duque de Caxias           | 42        | 0.42%   |
| Sao Jose                  | 41        | 0.41%   |
| MaringГЎ                | 39        | 0.39%   |
| Sao Goncalo               | 38        | 0.38%   |
| Canoas                    | 37        | 0.37%   |
| Santos                    | 36        | 0.36%   |
| SГЈo Carlos             | 35        | 0.35%   |
| SГЈo Bernardo do Campo  | 35        | 0.35%   |
| Santo AndrÃ©            | 34        | 0.34%   |
| FlorianÃ³polis          | 34        | 0.34%   |
| Taubate                   | 31        | 0.31%   |
| GoiÃ¢nia                | 31        | 0.31%   |
| Vila Velha                | 30        | 0.3%    |
| RibeirГЈo Preto         | 30        | 0.3%    |
| Porto Velho               | 30        | 0.3%    |
| Bauru                     | 30        | 0.3%    |
| MaceiГі                 | 29        | 0.29%   |
| Contagem                  | 29        | 0.29%   |
| Campina Grande            | 29        | 0.29%   |
| Praia Grande              | 28        | 0.28%   |
| Americana                 | 28        | 0.28%   |
| Sao Vicente               | 27        | 0.27%   |
| Presidente Prudente       | 27        | 0.27%   |
| Palmas                    | 26        | 0.26%   |
| BelÃ©m                  | 26        | 0.26%   |
| Araraquara                | 26        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 2791      | 3563   | 21.64%  |
| Seagate                        | 2658      | 3708   | 20.61%  |
| Samsung Electronics            | 1349      | 1851   | 10.46%  |
| Kingston                       | 1294      | 1684   | 10.03%  |
| Toshiba                        | 796       | 932    | 6.17%   |
| Sandisk                        | 660       | 893    | 5.12%   |
| Unknown                        | 389       | 536    | 3.02%   |
| Hitachi                        | 325       | 404    | 2.52%   |
| A-DATA Technology              | 320       | 399    | 2.48%   |
| Intel                          | 280       | 338    | 2.17%   |
| Crucial                        | 218       | 279    | 1.69%   |
| China                          | 211       | 247    | 1.64%   |
| Silicon Motion                 | 110       | 139    | 0.85%   |
| HGST                           | 110       | 131    | 0.85%   |
| MAXTOR                         | 109       | 134    | 0.85%   |
| LITEON                         | 102       | 116    | 0.79%   |
| SK Hynix                       | 92        | 125    | 0.71%   |
| ADATA Technology               | 91        | 113    | 0.71%   |
| Lexar                          | 67        | 77     | 0.52%   |
| KingSpec                       | 62        | 71     | 0.48%   |
| Corsair                        | 53        | 63     | 0.41%   |
| Phison                         | 49        | 71     | 0.38%   |
| Realtek Semiconductor          | 48        | 59     | 0.37%   |
| XPG                            | 45        | 58     | 0.35%   |
| Fujitsu                        | 45        | 55     | 0.35%   |
| JMicron                        | 43        | 52     | 0.33%   |
| Hewlett-Packard                | 35        | 44     | 0.27%   |
| Apple                          | 33        | 49     | 0.26%   |
| PNY                            | 30        | 37     | 0.23%   |
| Gigabyte Technology            | 26        | 36     | 0.2%    |
| SMART                          | 25        | 27     | 0.19%   |
| Patriot                        | 25        | 31     | 0.19%   |
| KingDian                       | 24        | 31     | 0.19%   |
| Netac                          | 22        | 30     | 0.17%   |
| Solid State Storage Technology | 20        | 25     | 0.16%   |
| SSSTC                          | 19        | 19     | 0.15%   |
| XrayDisk                       | 15        | 17     | 0.12%   |
| OCZ                            | 14        | 14     | 0.11%   |
| Micron/Crucial Technology      | 14        | 18     | 0.11%   |
| Unknown                        | 14        | 14     | 0.11%   |
| Micron Technology              | 13        | 15     | 0.1%    |
| KIOXIA                         | 13        | 16     | 0.1%    |
| LITEONIT                       | 12        | 17     | 0.09%   |
| Solid State Storage            | 11        | 11     | 0.09%   |
| Lite-On                        | 11        | 12     | 0.09%   |
| BHT                            | 10        | 13     | 0.08%   |
| ExcelStor                      | 9         | 10     | 0.07%   |
| PLEXTOR                        | 7         | 8      | 0.05%   |
| HS-SSD-C100                    | 6         | 10     | 0.05%   |
| Team                           | 5         | 7      | 0.04%   |
| Pichau                         | 5         | 5      | 0.04%   |
| AFOX                           | 5         | 7      | 0.04%   |
| Zheino                         | 4         | 7      | 0.03%   |
| Vaseky                         | 4         | 4      | 0.03%   |
| Union Memory                   | 4         | 5      | 0.03%   |
| Transcend                      | 4         | 4      | 0.03%   |
| SPCC                           | 4         | 7      | 0.03%   |
| RZX                            | 4         | 5      | 0.03%   |
| Lenovo                         | 4         | 5      | 0.03%   |
| KINGBANK                       | 4         | 6      | 0.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 445       | 3.24%   |
| WDC WD10SPZX-21Z10T0 1TB            | 440       | 3.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 267       | 1.95%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 242       | 1.76%   |
| Kingston SA400S37120G 120GB SSD     | 241       | 1.76%   |
| Kingston SA400S37480G 480GB SSD     | 205       | 1.49%   |
| Seagate ST500DM002-1BD142 500GB     | 204       | 1.49%   |
| Seagate ST1000DM010-2EP102 1TB      | 166       | 1.21%   |
| Toshiba MQ01ABD100 1TB              | 123       | 0.9%    |
| SanDisk SSD PLUS 240GB              | 118       | 0.86%   |
| Kingston SV300S37A120G 120GB SSD    | 115       | 0.84%   |
| Unknown MMC Card  32GB              | 109       | 0.79%   |
| WDC WD10SPZX-24Z10 1TB              | 108       | 0.79%   |
| Samsung HD322HJ 320GB               | 103       | 0.75%   |
| Intel NVMe SSD Drive 512GB          | 100       | 0.73%   |
| Seagate Expansion+ 2TB              | 94        | 0.68%   |
| Seagate ST1000LM035-1RK172 1TB      | 93        | 0.68%   |
| Samsung HM321HI 320GB               | 89        | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 88        | 0.64%   |
| SanDisk SSD PLUS 120GB              | 87        | 0.63%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 87        | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB            | 86        | 0.63%   |
| Samsung HD161HJ 160GB               | 86        | 0.63%   |
| Samsung HD502HI 500GB               | 80        | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB      | 79        | 0.58%   |
| Samsung HD502HJ 500GB               | 78        | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB      | 76        | 0.55%   |
| Seagate ST9500325AS 500GB           | 75        | 0.55%   |
| SanDisk SDSSDA240G 240GB            | 73        | 0.53%   |
| WDC WD10SPZX-75Z10T2 1TB            | 72        | 0.52%   |
| Crucial CT240BX500SSD1 240GB        | 70        | 0.51%   |
| WDC WD5000AAKX-003CA0 500GB         | 68        | 0.5%    |
| Intel NVMe SSD Drive 128GB          | 68        | 0.5%    |
| Seagate ST3500418AS 500GB           | 64        | 0.47%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 62        | 0.45%   |
| WDC WD10EARS-00Y5B1 1TB             | 61        | 0.44%   |
| Toshiba MQ01ABF050 500GB            | 61        | 0.44%   |
| Toshiba MQ04ABF100 1TB              | 59        | 0.43%   |
| WDC WD10JPVX-75JC3T0 1TB            | 57        | 0.42%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 55        | 0.4%    |
| SanDisk SDSSDA120G 120GB            | 55        | 0.4%    |
| Sandisk NVMe SSD Drive 512GB        | 55        | 0.4%    |
| SanDisk SSD PLUS 480GB              | 53        | 0.39%   |
| Kingston SV300S37A240G 240GB SSD    | 52        | 0.38%   |
| Seagate ST3500312CS 500GB           | 51        | 0.37%   |
| Toshiba MQ01ABD050 500GB            | 50        | 0.36%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 49        | 0.36%   |
| WDC WD10EZEX-00BN5A0 1TB            | 49        | 0.36%   |
| Toshiba DT01ACA050 500GB            | 48        | 0.35%   |
| Seagate ST2000LM007-1R8174 2TB      | 48        | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB      | 47        | 0.34%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 46        | 0.34%   |
| Seagate ST500LT012-9WS142 500GB     | 46        | 0.34%   |
| Seagate ST31000524AS 1TB            | 45        | 0.33%   |
| Kingston SUV400S37240G 240GB SSD    | 45        | 0.33%   |
| ADATA NVMe SSD Drive 256GB          | 44        | 0.32%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 43        | 0.31%   |
| WDC WD10EZEX-00WN4A0 1TB            | 43        | 0.31%   |
| Toshiba HDWD110 1TB                 | 43        | 0.31%   |
| WDC WD10JPCX-24UE4T0 1TB            | 42        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2648      | 3684   | 35.16%  |
| WDC                 | 2515      | 3122   | 33.39%  |
| Samsung Electronics | 959       | 1244   | 12.73%  |
| Toshiba             | 753       | 884    | 10%     |
| Hitachi             | 325       | 404    | 4.31%   |
| HGST                | 110       | 131    | 1.46%   |
| MAXTOR              | 102       | 126    | 1.35%   |
| Fujitsu             | 44        | 53     | 0.58%   |
| Unknown             | 22        | 24     | 0.29%   |
| Apple               | 15        | 26     | 0.2%    |
| Hewlett-Packard     | 12        | 15     | 0.16%   |
| ExcelStor           | 9         | 10     | 0.12%   |
| JMicron             | 4         | 5      | 0.05%   |
| ASMT                | 2         | 2      | 0.03%   |
| USB3.0              | 1         | 1      | 0.01%   |
| sage                | 1         | 1      | 0.01%   |
| SABRENT             | 1         | 1      | 0.01%   |
| MDT                 | 1         | 1      | 0.01%   |
| Maxtor 6            | 1         | 1      | 0.01%   |
| Lenovo              | 1         | 1      | 0.01%   |
| Intenso             | 1         | 1      | 0.01%   |
| IBM/Hitachi         | 1         | 2      | 0.01%   |
| IBM                 | 1         | 3      | 0.01%   |
| FEASSO              | 1         | 2      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| China               | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1262      | 1629   | 33.47%  |
| SanDisk             | 524       | 738    | 13.9%   |
| WDC                 | 294       | 371    | 7.8%    |
| Samsung Electronics | 285       | 439    | 7.56%   |
| A-DATA Technology   | 226       | 276    | 5.99%   |
| China               | 210       | 246    | 5.57%   |
| Crucial             | 209       | 266    | 5.54%   |
| LITEON              | 90        | 103    | 2.39%   |
| Lexar               | 67        | 77     | 1.78%   |
| KingSpec            | 61        | 70     | 1.62%   |
| Intel               | 43        | 58     | 1.14%   |
| Corsair             | 43        | 51     | 1.14%   |
| JMicron             | 34        | 42     | 0.9%    |
| PNY                 | 29        | 36     | 0.77%   |
| SMART               | 25        | 27     | 0.66%   |
| Patriot             | 23        | 28     | 0.61%   |
| KingDian            | 23        | 30     | 0.61%   |
| Gigabyte Technology | 23        | 32     | 0.61%   |
| Unknown             | 21        | 24     | 0.56%   |
| Netac               | 20        | 27     | 0.53%   |
| Apple               | 18        | 21     | 0.48%   |
| SK Hynix            | 17        | 21     | 0.45%   |
| Hewlett-Packard     | 16        | 20     | 0.42%   |
| Toshiba             | 15        | 18     | 0.4%    |
| OCZ                 | 14        | 14     | 0.37%   |
| LITEONIT            | 12        | 17     | 0.32%   |
| Seagate             | 11        | 14     | 0.29%   |
| Unknown             | 11        | 11     | 0.29%   |
| BHT                 | 10        | 13     | 0.27%   |
| Micron Technology   | 9         | 11     | 0.24%   |
| PLEXTOR             | 7         | 8      | 0.19%   |
| MAXTOR              | 7         | 8      | 0.19%   |
| XrayDisk            | 5         | 6      | 0.13%   |
| Team                | 5         | 7      | 0.13%   |
| Pichau              | 5         | 5      | 0.13%   |
| Transcend           | 4         | 4      | 0.11%   |
| RZX                 | 4         | 5      | 0.11%   |
| KINGBANK            | 4         | 6      | 0.11%   |
| Colorful            | 4         | 4      | 0.11%   |
| Apacer              | 4         | 4      | 0.11%   |
| Zheino              | 3         | 6      | 0.08%   |
| Vaseky              | 3         | 3      | 0.08%   |
| TSA                 | 3         | 3      | 0.08%   |
| TO Exter            | 3         | 4      | 0.08%   |
| SuperSSpeed         | 3         | 4      | 0.08%   |
| NGFF                | 3         | 3      | 0.08%   |
| Mushkin             | 3         | 4      | 0.08%   |
| HS-SSD-C100         | 3         | 3      | 0.08%   |
| WDC WDS2            | 2         | 2      | 0.05%   |
| SPCC                | 2         | 4      | 0.05%   |
| Ramsta              | 2         | 2      | 0.05%   |
| MGS                 | 2         | 3      | 0.05%   |
| GLOWAY              | 2         | 2      | 0.05%   |
| External            | 2         | 2      | 0.05%   |
| Dell                | 2         | 2      | 0.05%   |
| BIWIN               | 2         | 2      | 0.05%   |
| AFOX                | 2         | 3      | 0.05%   |
| Wintec              | 1         | 1      | 0.03%   |
| WDC WDS             | 1         | 1      | 0.03%   |
| WANGCHU             | 1         | 1      | 0.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 6713      | 9746   | 57.03%  |
| SSD     | 3428      | 4878   | 29.12%  |
| NVMe    | 1257      | 1648   | 10.68%  |
| MMC     | 284       | 415    | 2.41%   |
| Unknown | 89        | 120    | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 8539      | 14378  | 82.51%  |
| NVMe | 1257      | 1647   | 12.15%  |
| MMC  | 284       | 415    | 2.74%   |
| SAS  | 269       | 367    | 2.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 6451      | 9671   | 63.51%  |
| 0.51-1.0   | 3095      | 4046   | 30.47%  |
| 1.01-2.0   | 450       | 648    | 4.43%   |
| 2.01-3.0   | 73        | 106    | 0.72%   |
| 3.01-4.0   | 64        | 107    | 0.63%   |
| 4.01-10.0  | 20        | 40     | 0.2%    |
| 10.01-20.0 | 4         | 6      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2755      | 27.7%   |
| 251-500        | 2479      | 24.92%  |
| 501-1000       | 1697      | 17.06%  |
| 51-100         | 689       | 6.93%   |
| 1001-2000      | 666       | 6.7%    |
| 1-20           | 663       | 6.67%   |
| 21-50          | 479       | 4.82%   |
| 2001-3000      | 194       | 1.95%   |
| Unknown        | 169       | 1.7%    |
| More than 3000 | 156       | 1.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3959      | 38.58%  |
| 21-50          | 2209      | 21.52%  |
| 101-250        | 1276      | 12.43%  |
| 51-100         | 1237      | 12.05%  |
| 251-500        | 664       | 6.47%   |
| 501-1000       | 461       | 4.49%   |
| 1001-2000      | 193       | 1.88%   |
| Unknown        | 169       | 1.65%   |
| 2001-3000      | 54        | 0.53%   |
| More than 3000 | 41        | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB      | 32        | 34     | 3.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 30        | 32     | 3.26%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 22        | 23     | 2.39%   |
| WDC WD5000AAKX-003CA0 500GB          | 21        | 21     | 2.29%   |
| Seagate ST9500325AS 500GB            | 20        | 22     | 2.18%   |
| Samsung Electronics HD322HJ 320GB    | 16        | 16     | 1.74%   |
| Samsung Electronics HD161HJ 160GB    | 15        | 16     | 1.63%   |
| Samsung Electronics HD502HI 500GB    | 14        | 16     | 1.52%   |
| Samsung Electronics HD502HJ 500GB    | 11        | 11     | 1.2%    |
| WDC WD10EARS-00Y5B1 1TB              | 10        | 11     | 1.09%   |
| Seagate ST9320325AS 320GB            | 10        | 10     | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB       | 10        | 10     | 1.09%   |
| Kingston SV300S37A120G 120GB SSD     | 10        | 10     | 1.09%   |
| Toshiba MQ01ABD100 1TB               | 9         | 9      | 0.98%   |
| Toshiba MQ01ABD050 500GB             | 9         | 9      | 0.98%   |
| Seagate ST3500418AS 500GB            | 9         | 15     | 0.98%   |
| MAXTOR STM3160215AS 160GB            | 9         | 10     | 0.98%   |
| Seagate ST1000DM010-2EP102 1TB       | 8         | 11     | 0.87%   |
| Samsung Electronics HD103SJ 1TB      | 8         | 10     | 0.87%   |
| Samsung Electronics HD080HJ 80GB     | 8         | 10     | 0.87%   |
| WDC WD3200AAJS-00L7A0 320GB          | 7         | 7      | 0.76%   |
| Toshiba MQ02ABD100H 1TB              | 7         | 11     | 0.76%   |
| Seagate ST3320418AS 320GB            | 7         | 11     | 0.76%   |
| Samsung Electronics HM321HI 320GB    | 7         | 7      | 0.76%   |
| Samsung Electronics HD250HJ 250GB    | 7         | 8      | 0.76%   |
| Kingston SA400S37120G 120GB SSD      | 7         | 11     | 0.76%   |
| WDC WD5000AAKX-00U6AA0 500GB         | 6         | 7      | 0.65%   |
| Toshiba MQ01ABF050 500GB             | 6         | 6      | 0.65%   |
| Toshiba MQ01ABD032 320GB             | 6         | 7      | 0.65%   |
| Seagate ST2000DM001-1CH164 2TB       | 6         | 7      | 0.65%   |
| Seagate ST1500DL003-9VT16L 1TB       | 6         | 6      | 0.65%   |
| Seagate ST1000DM003-9YN162 1TB       | 6         | 6      | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB       | 6         | 7      | 0.65%   |
| Samsung Electronics HM160HI 160GB    | 6         | 6      | 0.65%   |
| Kingston SA400S37480G 480GB SSD      | 6         | 7      | 0.65%   |
| Kingston SA400S37240G 240GB SSD      | 6         | 6      | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 5         | 5      | 0.54%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 5         | 6      | 0.54%   |
| WDC WD5000AAKX-083CA1 500GB          | 5         | 5      | 0.54%   |
| WDC WD10JPCX-24UE4T0 1TB             | 5         | 7      | 0.54%   |
| Toshiba DT01ACA050 500GB             | 5         | 5      | 0.54%   |
| Seagate ST500LT012-9WS142 500GB      | 5         | 7      | 0.54%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 6      | 0.54%   |
| Seagate ST31000528AS 1TB             | 5         | 8      | 0.54%   |
| SanDisk SSD PLUS 240GB               | 5         | 5      | 0.54%   |
| Samsung Electronics HD103SI 1TB      | 5         | 5      | 0.54%   |
| Hitachi HTS547550A9E384 500GB        | 5         | 5      | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB             | 4         | 4      | 0.44%   |
| Seagate ST9500423AS 500GB            | 4         | 4      | 0.44%   |
| Seagate ST4000DM000-1F2168 4TB       | 4         | 4      | 0.44%   |
| Seagate ST3500413AS 500GB            | 4         | 5      | 0.44%   |
| Seagate ST3500312CS 500GB            | 4         | 4      | 0.44%   |
| Seagate ST3250318AS 250GB            | 4         | 4      | 0.44%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 4      | 0.44%   |
| Seagate ST3160318AS 160GB            | 4         | 4      | 0.44%   |
| Seagate ST31000524AS 1TB             | 4         | 4      | 0.44%   |
| Samsung Electronics SP0842N 80GB     | 4         | 4      | 0.44%   |
| Samsung Electronics HN-M500MBB 500GB | 4         | 6      | 0.44%   |
| Samsung Electronics HD753LJ 752GB    | 4         | 4      | 0.44%   |
| Samsung Electronics HD161GJ 160GB    | 4         | 4      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 298       | 354    | 33.9%   |
| WDC                 | 195       | 217    | 22.18%  |
| Samsung Electronics | 141       | 172    | 16.04%  |
| Toshiba             | 81        | 90     | 9.22%   |
| Hitachi             | 45        | 47     | 5.12%   |
| Kingston            | 36        | 44     | 4.1%    |
| MAXTOR              | 18        | 19     | 2.05%   |
| SanDisk             | 14        | 14     | 1.59%   |
| A-DATA Technology   | 7         | 7      | 0.8%    |
| Intel               | 6         | 6      | 0.68%   |
| Fujitsu             | 5         | 6      | 0.57%   |
| China               | 4         | 4      | 0.46%   |
| XPG                 | 3         | 3      | 0.34%   |
| OCZ                 | 3         | 3      | 0.34%   |
| Crucial             | 3         | 3      | 0.34%   |
| Apple               | 3         | 3      | 0.34%   |
| PNY                 | 2         | 2      | 0.23%   |
| LITEON              | 2         | 2      | 0.23%   |
| HGST                | 2         | 2      | 0.23%   |
| Corsair             | 2         | 2      | 0.23%   |
| QIANGHE             | 1         | 1      | 0.11%   |
| PLEXTOR             | 1         | 1      | 0.11%   |
| OCZ-VERTEX3         | 1         | 1      | 0.11%   |
| Micron Technology   | 1         | 1      | 0.11%   |
| LITEONIT            | 1         | 2      | 0.11%   |
| Hewlett-Packard     | 1         | 1      | 0.11%   |
| FEASSO              | 1         | 2      | 0.11%   |
| ExcelStor           | 1         | 2      | 0.11%   |
| Unknown             | 1         | 1      | 0.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 298       | 354    | 38.3%   |
| WDC                 | 186       | 208    | 23.91%  |
| Samsung Electronics | 139       | 170    | 17.87%  |
| Toshiba             | 80        | 89     | 10.28%  |
| Hitachi             | 45        | 47     | 5.78%   |
| MAXTOR              | 18        | 19     | 2.31%   |
| Fujitsu             | 5         | 6      | 0.64%   |
| HGST                | 2         | 2      | 0.26%   |
| Apple               | 2         | 2      | 0.26%   |
| Hewlett-Packard     | 1         | 1      | 0.13%   |
| FEASSO              | 1         | 2      | 0.13%   |
| ExcelStor           | 1         | 2      | 0.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 715       | 902    | 87.73%  |
| SSD  | 90        | 100    | 11.04%  |
| NVMe | 10        | 10     | 1.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 5%      |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 5%      |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 5%      |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 5%      |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 5%      |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 5%      |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 5%      |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 5%      |
| Seagate ST31000340NS 1TB                         | 1         | 1      | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 5%      |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 5%      |
| Samsung Electronics HM321HI 320GB                | 1         | 1      | 5%      |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 5%      |
| Samsung Electronics HM250HI 250GB                | 1         | 1      | 5%      |
| Samsung Electronics HD502HJ 500GB                | 1         | 3      | 5%      |
| Samsung Electronics HD322GJ 320GB                | 1         | 1      | 5%      |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 5%      |
| Samsung Electronics HD080HJ 80GB                 | 1         | 1      | 5%      |
| MAXTOR STM380215AS 80GB                          | 1         | 1      | 5%      |
| Hitachi HDS721050DLE630 500GB                    | 1         | 1      | 5%      |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 10     | 40%     |
| Seagate             | 5         | 5      | 25%     |
| WDC                 | 3         | 3      | 15%     |
| Toshiba             | 2         | 2      | 10%     |
| MAXTOR              | 1         | 1      | 5%      |
| Hitachi             | 1         | 1      | 5%      |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 6926      | 12227  | 69.39%  |
| Works    | 2242      | 3546   | 22.46%  |
| Malfunc  | 793       | 1012   | 7.95%   |
| Failed   | 20        | 22     | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7294      | 69.62%  |
| AMD                              | 1475      | 14.08%  |
| Nvidia                           | 228       | 2.18%   |
| ADATA Technology                 | 217       | 2.07%   |
| Sandisk                          | 168       | 1.6%    |
| Samsung Electronics              | 150       | 1.43%   |
| Silicon Motion                   | 124       | 1.18%   |
| Silicon Integrated Systems [SiS] | 96        | 0.92%   |
| Realtek Semiconductor            | 73        | 0.7%    |
| Marvell Technology Group         | 72        | 0.69%   |
| SK Hynix                         | 70        | 0.67%   |
| JMicron Technology               | 69        | 0.66%   |
| VIA Technologies                 | 66        | 0.63%   |
| Solid State Storage Technology   | 65        | 0.62%   |
| Phison Electronics               | 61        | 0.58%   |
| ASMedia Technology               | 55        | 0.52%   |
| Kingston Technology Company      | 40        | 0.38%   |
| Micron/Crucial Technology        | 25        | 0.24%   |
| Toshiba America Info Systems     | 22        | 0.21%   |
| Lite-On Technology               | 22        | 0.21%   |
| LSI Logic / Symbios Logic        | 15        | 0.14%   |
| KIOXIA                           | 14        | 0.13%   |
| Broadcom / LSI                   | 10        | 0.1%    |
| Union Memory (Shenzhen)          | 6         | 0.06%   |
| Silicon Image                    | 5         | 0.05%   |
| Seagate Technology               | 5         | 0.05%   |
| OCZ Technology Group             | 4         | 0.04%   |
| Micron Technology                | 4         | 0.04%   |
| Adaptec                          | 4         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.03%   |
| Hewlett-Packard                  | 3         | 0.03%   |
| Lenovo                           | 2         | 0.02%   |
| Dell                             | 2         | 0.02%   |
| Beijing Starblaze Technology     | 2         | 0.02%   |
| Apple                            | 2         | 0.02%   |
| Shenzhen Longsys Electronics     | 1         | 0.01%   |
| Promise Technology               | 1         | 0.01%   |
| Broadcom                         | 1         | 0.01%   |
| Biwin Storage Technology         | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 873       | 6.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 821       | 6.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 693       | 5.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 556       | 4.29%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 511       | 3.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 402       | 3.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 396       | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 331       | 2.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 317       | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 306       | 2.36%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 275       | 2.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 264       | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 258       | 1.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 257       | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 213       | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 205       | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 199       | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 199       | 1.53%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 198       | 1.53%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 179       | 1.38%   |
| AMD FCH SATA Controller D                                                               | 177       | 1.36%   |
| ADATA Non-Volatile memory controller                                                    | 165       | 1.27%   |
| Nvidia MCP61 SATA Controller                                                            | 162       | 1.25%   |
| AMD 400 Series Chipset SATA Controller                                                  | 162       | 1.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 139       | 1.07%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 137       | 1.06%   |
| Nvidia MCP61 IDE                                                                        | 132       | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 131       | 1.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 124       | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 124       | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 115       | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 114       | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 114       | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 112       | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 106       | 0.82%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 105       | 0.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 103       | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 101       | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 99        | 0.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 98        | 0.76%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 95        | 0.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 95        | 0.73%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 77        | 0.59%   |
| Intel SATA Controller [RAID mode]                                                       | 73        | 0.56%   |
| AMD 300 Series Chipset SATA Controller                                                  | 71        | 0.55%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 67        | 0.52%   |
| Solid State Storage Non-Volatile memory controller                                      | 65        | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 64        | 0.49%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 62        | 0.48%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 57        | 0.44%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 56        | 0.43%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 56        | 0.43%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 55        | 0.42%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 53        | 0.41%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 52        | 0.4%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 46        | 0.35%   |
| AMD FCH IDE Controller                                                                  | 46        | 0.35%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 45        | 0.35%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 45        | 0.35%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 42        | 0.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 7096      | 64.17%  |
| IDE  | 2022      | 18.29%  |
| NVMe | 1271      | 11.49%  |
| RAID | 653       | 5.91%   |
| SCSI | 11        | 0.1%    |
| SAS  | 5         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 7742      | 81.83%  |
| AMD          | 1694      | 17.91%  |
| ARM          | 19        | 0.2%    |
| CentaurHauls | 5         | 0.05%   |
| Unknown      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 203       | 2.14%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 153       | 1.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 127       | 1.34%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 121       | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 111       | 1.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 108       | 1.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 108       | 1.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 107       | 1.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 102       | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 99        | 1.04%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 90        | 0.95%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 81        | 0.85%   |
| AMD FX-6300 Six-Core Processor                | 81        | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 76        | 0.8%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 75        | 0.79%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 74        | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 72        | 0.76%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 72        | 0.76%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 71        | 0.75%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 71        | 0.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 70        | 0.74%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 68        | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 65        | 0.69%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 65        | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 63        | 0.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 60        | 0.63%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 60        | 0.63%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 60        | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 59        | 0.62%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 57        | 0.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 57        | 0.6%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 56        | 0.59%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 54        | 0.57%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 53        | 0.56%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 52        | 0.55%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 52        | 0.55%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 52        | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 51        | 0.54%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 50        | 0.53%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 48        | 0.51%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 48        | 0.51%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 47        | 0.5%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 47        | 0.5%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 46        | 0.49%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 45        | 0.47%   |
| Intel Celeron CPU J1800 @ 2.41GHz             | 45        | 0.47%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 45        | 0.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 44        | 0.46%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 43        | 0.45%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 43        | 0.45%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 42        | 0.44%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 42        | 0.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 42        | 0.44%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 41        | 0.43%   |
| AMD Ryzen 5 3600 6-Core Processor             | 41        | 0.43%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 40        | 0.42%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 39        | 0.41%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 38        | 0.4%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 38        | 0.4%    |
| Intel Core i3-6100U CPU @ 2.30GHz             | 38        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2383      | 25.13%  |
| Intel Core i7                  | 1571      | 16.57%  |
| Intel Core i3                  | 1318      | 13.9%   |
| Intel Celeron                  | 633       | 6.68%   |
| Intel Core 2 Duo               | 436       | 4.6%    |
| AMD Ryzen 5                    | 378       | 3.99%   |
| Intel Pentium Dual-Core        | 286       | 3.02%   |
| Intel Atom                     | 235       | 2.48%   |
| AMD FX                         | 224       | 2.36%   |
| Intel Pentium                  | 223       | 2.35%   |
| AMD Ryzen 7                    | 205       | 2.16%   |
| Intel Xeon                     | 162       | 1.71%   |
| Intel Pentium Dual             | 130       | 1.37%   |
| Other                          | 124       | 1.31%   |
| AMD Ryzen 3                    | 87        | 0.92%   |
| Intel Core 2 Quad              | 83        | 0.88%   |
| AMD Phenom II X4               | 66        | 0.7%    |
| AMD Athlon II X2               | 62        | 0.65%   |
| AMD E                          | 52        | 0.55%   |
| AMD A4                         | 52        | 0.55%   |
| AMD A10                        | 51        | 0.54%   |
| Intel Core 2                   | 47        | 0.5%    |
| AMD Athlon 64 X2               | 43        | 0.45%   |
| AMD C-60                       | 39        | 0.41%   |
| AMD A6                         | 39        | 0.41%   |
| AMD A8                         | 38        | 0.4%    |
| Intel Genuine                  | 35        | 0.37%   |
| AMD Athlon                     | 35        | 0.37%   |
| AMD Sempron                    | 31        | 0.33%   |
| AMD E1                         | 30        | 0.32%   |
| Intel Pentium 4                | 27        | 0.28%   |
| AMD C-70                       | 24        | 0.25%   |
| AMD Phenom II X6               | 22        | 0.23%   |
| AMD Ryzen 9                    | 21        | 0.22%   |
| Intel Pentium Gold             | 16        | 0.17%   |
| AMD Athlon II X4               | 16        | 0.17%   |
| AMD C-50                       | 15        | 0.16%   |
| Intel Core i9                  | 14        | 0.15%   |
| Intel Celeron Dual-Core        | 14        | 0.15%   |
| AMD Phenom II X2               | 14        | 0.15%   |
| AMD Phenom                     | 13        | 0.14%   |
| Intel Pentium D                | 12        | 0.13%   |
| Intel Celeron M                | 12        | 0.13%   |
| AMD Mobile Sempron             | 12        | 0.13%   |
| AMD Athlon II X3               | 12        | 0.13%   |
| AMD Athlon II                  | 10        | 0.11%   |
| AMD A12                        | 9         | 0.09%   |
| AMD Ryzen 3 PRO                | 7         | 0.07%   |
| AMD E2                         | 6         | 0.06%   |
| CentaurHauls VIA C7            | 5         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 5         | 0.05%   |
| AMD Turion II                  | 5         | 0.05%   |
| AMD Turion 64 Mobile           | 5         | 0.05%   |
| AMD Ryzen 5 PRO                | 5         | 0.05%   |
| AMD Phenom II X3               | 5         | 0.05%   |
| Intel Pentium M                | 4         | 0.04%   |
| AMD Turion 64 X2 Mobile        | 4         | 0.04%   |
| AMD Ryzen 7 PRO                | 4         | 0.04%   |
| AMD Phenom II                  | 4         | 0.04%   |
| AMD Athlon X4                  | 4         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5221      | 55.07%  |
| 4       | 2978      | 31.41%  |
| 6       | 578       | 6.1%    |
| 1       | 287       | 3.03%   |
| 8       | 223       | 2.35%   |
| 3       | 119       | 1.26%   |
| 12      | 31        | 0.33%   |
| Unknown | 15        | 0.16%   |
| 16      | 10        | 0.11%   |
| 20      | 6         | 0.06%   |
| 10      | 5         | 0.05%   |
| 24      | 2         | 0.02%   |
| 14      | 2         | 0.02%   |
| 32      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 9425      | 99.61%  |
| 2       | 34        | 0.36%   |
| Unknown | 2         | 0.02%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6016      | 63.53%  |
| 1       | 3439      | 36.31%  |
| Unknown | 15        | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 8881      | 93.27%  |
| Unknown        | 536       | 5.63%   |
| 32-bit         | 58        | 0.61%   |
| 64-bit         | 47        | 0.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1587      | 16.28%  |
| 0x306a9    | 846       | 8.68%   |
| 0x206a7    | 824       | 8.45%   |
| 0x1067a    | 558       | 5.72%   |
| 0x906ea    | 372       | 3.82%   |
| 0x806e9    | 344       | 3.53%   |
| 0x20655    | 313       | 3.21%   |
| 0x306c3    | 312       | 3.2%    |
| 0x40651    | 291       | 2.99%   |
| 0x806ec    | 287       | 2.94%   |
| 0x406e3    | 248       | 2.54%   |
| 0x306d4    | 243       | 2.49%   |
| 0x806ea    | 227       | 2.33%   |
| 0x6fd      | 218       | 2.24%   |
| 0x906e9    | 189       | 1.94%   |
| 0x06000852 | 140       | 1.44%   |
| 0x406c4    | 139       | 1.43%   |
| 0x010000c8 | 121       | 1.24%   |
| 0x08108109 | 115       | 1.18%   |
| 0x30678    | 114       | 1.17%   |
| 0x05000119 | 89        | 0.91%   |
| 0x20652    | 81        | 0.83%   |
| 0x906ed    | 79        | 0.81%   |
| 0x806c1    | 78        | 0.8%    |
| 0x08108102 | 71        | 0.73%   |
| 0x10676    | 69        | 0.71%   |
| 0x0800820d | 64        | 0.66%   |
| 0x506e3    | 63        | 0.65%   |
| 0x706a1    | 62        | 0.64%   |
| 0x6fb      | 61        | 0.63%   |
| 0x08701021 | 60        | 0.62%   |
| 0x106ca    | 54        | 0.55%   |
| 0x08600103 | 51        | 0.52%   |
| 0x806eb    | 47        | 0.48%   |
| 0x10661    | 45        | 0.46%   |
| 0x706e5    | 44        | 0.45%   |
| 0x0810100b | 43        | 0.44%   |
| 0x08701013 | 42        | 0.43%   |
| 0x106e5    | 41        | 0.42%   |
| 0x406c3    | 40        | 0.41%   |
| 0x06001119 | 39        | 0.4%    |
| 0x08101016 | 37        | 0.38%   |
| 0x0600611a | 36        | 0.37%   |
| 0x03000027 | 34        | 0.35%   |
| 0x706a8    | 33        | 0.34%   |
| 0x506c9    | 32        | 0.33%   |
| 0x05000029 | 32        | 0.33%   |
| 0x306f2    | 29        | 0.3%    |
| 0x010000db | 29        | 0.3%    |
| 0xa0652    | 28        | 0.29%   |
| 0x30661    | 28        | 0.29%   |
| 0x08001138 | 28        | 0.29%   |
| 0x0700010f | 28        | 0.29%   |
| 0x06003106 | 28        | 0.29%   |
| 0x306e4    | 25        | 0.26%   |
| 0x906eb    | 24        | 0.25%   |
| 0x6f6      | 24        | 0.25%   |
| 0x6f2      | 23        | 0.24%   |
| 0xa0653    | 22        | 0.23%   |
| 0x0600063e | 22        | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 1826      | 19.29%  |
| IvyBridge       | 1008      | 10.65%  |
| SandyBridge     | 964       | 10.18%  |
| Haswell         | 732       | 7.73%   |
| Penryn          | 714       | 7.54%   |
| Westmere        | 456       | 4.82%   |
| Core            | 417       | 4.4%    |
| Silvermont      | 363       | 3.83%   |
| Skylake         | 362       | 3.82%   |
| Zen+            | 315       | 3.33%   |
| Broadwell       | 281       | 2.97%   |
| K10             | 261       | 2.76%   |
| Piledriver      | 236       | 2.49%   |
| Zen             | 195       | 2.06%   |
| Zen 2           | 178       | 1.88%   |
| Bobcat          | 151       | 1.59%   |
| Goldmont plus   | 103       | 1.09%   |
| Bonnell         | 102       | 1.08%   |
| TigerLake       | 96        | 1.01%   |
| K8 Hammer       | 94        | 0.99%   |
| CometLake       | 92        | 0.97%   |
| Nehalem         | 61        | 0.64%   |
| Excavator       | 58        | 0.61%   |
| IceLake         | 56        | 0.59%   |
| NetBurst        | 47        | 0.5%    |
| K10 Llano       | 42        | 0.44%   |
| Unknown         | 40        | 0.42%   |
| Goldmont        | 37        | 0.39%   |
| Jaguar          | 36        | 0.38%   |
| Bulldozer       | 36        | 0.38%   |
| Steamroller     | 35        | 0.37%   |
| Zen 3           | 33        | 0.35%   |
| P6              | 24        | 0.25%   |
| K8 & K10 hybrid | 9         | 0.1%    |
| Puma            | 7         | 0.07%   |
| K6              | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6426      | 56.62%  |
| Nvidia                           | 2817      | 24.82%  |
| AMD                              | 1930      | 17%     |
| Silicon Integrated Systems [SiS] | 93        | 0.82%   |
| VIA Technologies                 | 50        | 0.44%   |
| Matrox Electronics Systems       | 20        | 0.18%   |
| ASPEED Technology                | 6         | 0.05%   |
| Silicon Motion                   | 4         | 0.04%   |
| ATI Technologies                 | 3         | 0.03%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 797       | 6.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 612       | 5.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 395       | 3.4%    |
| Intel HD Graphics 620                                                                    | 386       | 3.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 345       | 2.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 332       | 2.85%   |
| Intel HD Graphics 5500                                                                   | 258       | 2.22%   |
| Intel UHD Graphics 620                                                                   | 249       | 2.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 248       | 2.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 247       | 2.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 244       | 2.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 218       | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 213       | 1.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 204       | 1.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 193       | 1.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 150       | 1.29%   |
| Intel HD Graphics 630                                                                    | 149       | 1.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 145       | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 144       | 1.24%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 141       | 1.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 137       | 1.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 132       | 1.13%   |
| Nvidia GT218 [GeForce 210]                                                               | 127       | 1.09%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 124       | 1.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 119       | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 119       | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 103       | 0.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 90        | 0.77%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 87        | 0.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 86        | 0.74%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 86        | 0.74%   |
| Nvidia GP108M [GeForce MX150]                                                            | 84        | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 83        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 81        | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 74        | 0.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 69        | 0.59%   |
| Nvidia GM108M [GeForce MX110]                                                            | 66        | 0.57%   |
| AMD RS780L [Radeon 3000]                                                                 | 66        | 0.57%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 64        | 0.55%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 64        | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 63        | 0.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 61        | 0.52%   |
| AMD Renoir                                                                               | 60        | 0.52%   |
| Nvidia TU117M                                                                            | 59        | 0.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 59        | 0.51%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 58        | 0.5%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 56        | 0.48%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 56        | 0.48%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 51        | 0.44%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 50        | 0.43%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 47        | 0.4%    |
| Nvidia GP108M [GeForce MX250]                                                            | 46        | 0.4%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 46        | 0.4%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 43        | 0.37%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 42        | 0.36%   |
| Intel HD Graphics 530                                                                    | 42        | 0.36%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 41        | 0.35%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 40        | 0.34%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 39        | 0.34%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 38        | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 4690      | 49.31%  |
| 1 x AMD                 | 1377      | 14.48%  |
| 1 x Nvidia              | 1356      | 14.26%  |
| Intel + Nvidia          | 1324      | 13.92%  |
| Intel + AMD             | 353       | 3.71%   |
| AMD + Nvidia            | 111       | 1.17%   |
| 1 x SiS                 | 93        | 0.98%   |
| 2 x AMD                 | 90        | 0.95%   |
| 1 x VIA                 | 49        | 0.52%   |
| Other                   | 22        | 0.23%   |
| 1 x Matrox              | 20        | 0.21%   |
| 2 x Nvidia              | 13        | 0.14%   |
| 1 x ASPEED              | 5         | 0.05%   |
| Intel + Silicon Motion  | 2         | 0.02%   |
| 1 x Silicon Motion      | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| Nvidia + Silicon Motion | 1         | 0.01%   |
| Nvidia + ASPEED         | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 7524      | 78.68%  |
| Proprietary | 1672      | 17.48%  |
| Unknown     | 367       | 3.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5640      | 58.28%  |
| 1.01-2.0   | 1491      | 15.41%  |
| 0.01-0.5   | 871       | 9%      |
| 0.51-1.0   | 697       | 7.2%    |
| 3.01-4.0   | 633       | 6.54%   |
| 5.01-6.0   | 149       | 1.54%   |
| 7.01-8.0   | 132       | 1.36%   |
| 2.01-3.0   | 52        | 0.54%   |
| 8.01-16.0  | 10        | 0.1%    |
| 4.01-5.0   | 2         | 0.02%   |
| 16.01-24.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1517      | 14.92%  |
| Goldstar                | 1305      | 12.84%  |
| AU Optronics            | 1277      | 12.56%  |
| BOE                     | 1157      | 11.38%  |
| LG Display              | 944       | 9.29%   |
| Chimei Innolux          | 931       | 9.16%   |
| AOC                     | 664       | 6.53%   |
| Dell                    | 423       | 4.16%   |
| Philips                 | 257       | 2.53%   |
| Acer                    | 150       | 1.48%   |
| LG Electronics          | 135       | 1.33%   |
| Chi Mei Optoelectronics | 124       | 1.22%   |
| Hewlett-Packard         | 100       | 0.98%   |
| InfoVision              | 98        | 0.96%   |
| Lenovo                  | 90        | 0.89%   |
| Apple                   | 80        | 0.79%   |
| PANDA                   | 77        | 0.76%   |
| Sony                    | 69        | 0.68%   |
| BenQ                    | 60        | 0.59%   |
| Unknown                 | 50        | 0.49%   |
| HannStar                | 42        | 0.41%   |
| CPT                     | 42        | 0.41%   |
| RTK                     | 35        | 0.34%   |
| Positivo                | 34        | 0.33%   |
| LG Philips              | 32        | 0.31%   |
| Panasonic               | 27        | 0.27%   |
| InnoLux Display         | 25        | 0.25%   |
| Ancor Communications    | 23        | 0.23%   |
| ASUSTek Computer        | 19        | 0.19%   |
| Sharp                   | 18        | 0.18%   |
| Toshiba                 | 16        | 0.16%   |
| NCS                     | 16        | 0.16%   |
| MTD                     | 16        | 0.16%   |
| GDH                     | 15        | 0.15%   |
| SLD                     | 14        | 0.14%   |
| Daewoo                  | 12        | 0.12%   |
| AGO                     | 12        | 0.12%   |
| TXD                     | 11        | 0.11%   |
| HB@                     | 11        | 0.11%   |
| Envision                | 11        | 0.11%   |
| STA                     | 10        | 0.1%    |
| SKY                     | 10        | 0.1%    |
| MStar                   | 10        | 0.1%    |
| KDC                     | 10        | 0.1%    |
| VIE                     | 9         | 0.09%   |
| MSI                     | 9         | 0.09%   |
| Unknown (XXX)           | 8         | 0.08%   |
| PZG                     | 7         | 0.07%   |
| JRY                     | 7         | 0.07%   |
| ___                     | 6         | 0.06%   |
| Quanta Display          | 6         | 0.06%   |
| Proview                 | 6         | 0.06%   |
| CVT                     | 6         | 0.06%   |
| LGD                     | 5         | 0.05%   |
| ITE                     | 5         | 0.05%   |
| Envision Peripherals    | 5         | 0.05%   |
| Semp Toshiba            | 4         | 0.04%   |
| Seiko/Epson             | 4         | 0.04%   |
| Philco                  | 4         | 0.04%   |
| Wacom                   | 3         | 0.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch          | 148       | 1.42%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 105       | 1.01%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 101       | 0.97%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 92        | 0.88%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 89        | 0.85%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 88        | 0.84%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 86        | 0.82%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 82        | 0.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 79        | 0.76%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 73        | 0.7%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 71        | 0.68%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 66        | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 64        | 0.61%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 59        | 0.56%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 56        | 0.54%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 55        | 0.53%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 52        | 0.5%    |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 50        | 0.48%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 49        | 0.47%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 49        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 49        | 0.47%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 49        | 0.47%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 48        | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 47        | 0.45%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 47        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 45        | 0.43%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch          | 43        | 0.41%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 42        | 0.4%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 41        | 0.39%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 41        | 0.39%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 40        | 0.38%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 39        | 0.37%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 38        | 0.36%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 37        | 0.35%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch          | 36        | 0.34%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 36        | 0.34%   |
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                    | 34        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 33        | 0.32%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 32        | 0.31%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 32        | 0.31%   |
| BOE LCD Monitor BOE0839 1920x1080 382x215mm 17.3-inch                | 32        | 0.31%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 32        | 0.31%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch        | 32        | 0.31%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch        | 32        | 0.31%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 31        | 0.3%    |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch    | 31        | 0.3%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 31        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 31        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch      | 31        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 31        | 0.3%    |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 31        | 0.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 31        | 0.3%    |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 30        | 0.29%   |
| BOE LCD Monitor BOE05F0 1366x768 309x173mm 13.9-inch                 | 30        | 0.29%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch          | 29        | 0.28%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                  | 29        | 0.28%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                  | 29        | 0.28%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch               | 29        | 0.28%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch        | 29        | 0.28%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 28        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4087      | 41.19%  |
| 1920x1080 (FHD)    | 3026      | 30.5%   |
| 1600x900 (HD+)     | 432       | 4.35%   |
| 1440x900 (WXGA+)   | 341       | 3.44%   |
| 2560x1080          | 304       | 3.06%   |
| 1280x1024 (SXGA)   | 281       | 2.83%   |
| 1360x768           | 272       | 2.74%   |
| 1280x800 (WXGA)    | 257       | 2.59%   |
| 3840x2160 (4K)     | 203       | 2.05%   |
| 1680x1050 (WSXGA+) | 157       | 1.58%   |
| 1024x768 (XGA)     | 106       | 1.07%   |
| Unknown            | 89        | 0.9%    |
| 2560x1440 (QHD)    | 65        | 0.66%   |
| 1920x1200 (WUXGA)  | 46        | 0.46%   |
| 1280x720 (HD)      | 40        | 0.4%    |
| 1024x600           | 37        | 0.37%   |
| 1920x540           | 24        | 0.24%   |
| 3840x1080          | 22        | 0.22%   |
| 2288x1287          | 15        | 0.15%   |
| 3440x1440          | 9         | 0.09%   |
| 1152x864           | 9         | 0.09%   |
| 2560x1600          | 6         | 0.06%   |
| 4480x1080          | 5         | 0.05%   |
| 3286x1080          | 5         | 0.05%   |
| 1600x1200          | 5         | 0.05%   |
| 5760x1080          | 4         | 0.04%   |
| 3360x1080          | 4         | 0.04%   |
| 3200x1080          | 4         | 0.04%   |
| 2736x1824          | 4         | 0.04%   |
| 1280x960           | 4         | 0.04%   |
| 3200x1800 (QHD+)   | 3         | 0.03%   |
| 2732x768           | 3         | 0.03%   |
| 6400x1080          | 2         | 0.02%   |
| 3840x2400          | 2         | 0.02%   |
| 3600x1080          | 2         | 0.02%   |
| 3520x1080          | 2         | 0.02%   |
| 3360x1050          | 2         | 0.02%   |
| 2880x1800          | 2         | 0.02%   |
| 2800x900           | 2         | 0.02%   |
| 2720x1024          | 2         | 0.02%   |
| 2646x768           | 2         | 0.02%   |
| 2646x1024          | 2         | 0.02%   |
| 640x480            | 1         | 0.01%   |
| 6400x2160          | 1         | 0.01%   |
| 5760x2160          | 1         | 0.01%   |
| 5440x1080          | 1         | 0.01%   |
| 5120x1440          | 1         | 0.01%   |
| 5120x1080          | 1         | 0.01%   |
| 4160x1080          | 1         | 0.01%   |
| 3640x1920          | 1         | 0.01%   |
| 3360x1200          | 1         | 0.01%   |
| 3280x1080          | 1         | 0.01%   |
| 3200x900           | 1         | 0.01%   |
| 2966x900           | 1         | 0.01%   |
| 2960x900           | 1         | 0.01%   |
| 2944x1080          | 1         | 0.01%   |
| 2880x900           | 1         | 0.01%   |
| 2726x768           | 1         | 0.01%   |
| 2646x800           | 1         | 0.01%   |
| 2640x800           | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3021      | 29.59%  |
| 14      | 1263      | 12.37%  |
| 13      | 1101      | 10.79%  |
| 18      | 681       | 6.67%   |
| 21      | 623       | 6.1%    |
| 23      | 586       | 5.74%   |
| Unknown | 441       | 4.32%   |
| 17      | 440       | 4.31%   |
| 24      | 281       | 2.75%   |
| 34      | 260       | 2.55%   |
| 20      | 256       | 2.51%   |
| 19      | 237       | 2.32%   |
| 27      | 201       | 1.97%   |
| 22      | 99        | 0.97%   |
| 31      | 97        | 0.95%   |
| 11      | 97        | 0.95%   |
| 12      | 62        | 0.61%   |
| 40      | 58        | 0.57%   |
| 32      | 56        | 0.55%   |
| 72      | 46        | 0.45%   |
| 10      | 45        | 0.44%   |
| 84      | 35        | 0.34%   |
| 28      | 35        | 0.34%   |
| 54      | 32        | 0.31%   |
| 16      | 30        | 0.29%   |
| 26      | 27        | 0.26%   |
| 47      | 14        | 0.14%   |
| 52      | 13        | 0.13%   |
| 46      | 12        | 0.12%   |
| 48      | 7         | 0.07%   |
| 37      | 7         | 0.07%   |
| 142     | 6         | 0.06%   |
| 39      | 5         | 0.05%   |
| 25      | 5         | 0.05%   |
| 65      | 4         | 0.04%   |
| 41      | 4         | 0.04%   |
| 50      | 3         | 0.03%   |
| 43      | 3         | 0.03%   |
| 55      | 2         | 0.02%   |
| 42      | 2         | 0.02%   |
| 29      | 2         | 0.02%   |
| 75      | 1         | 0.01%   |
| 74      | 1         | 0.01%   |
| 64      | 1         | 0.01%   |
| 60      | 1         | 0.01%   |
| 57      | 1         | 0.01%   |
| 49      | 1         | 0.01%   |
| 38      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |
| 30      | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 5304      | 52.74%  |
| 401-500        | 1799      | 17.89%  |
| 501-600        | 1021      | 10.15%  |
| Unknown        | 441       | 4.39%   |
| 201-300        | 384       | 3.82%   |
| 351-400        | 375       | 3.73%   |
| 701-800        | 316       | 3.14%   |
| 601-700        | 158       | 1.57%   |
| 1001-1500      | 90        | 0.89%   |
| 1501-2000      | 83        | 0.83%   |
| 801-900        | 71        | 0.71%   |
| 901-1000       | 9         | 0.09%   |
| More than 2000 | 6         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 7336      | 79.33%  |
| 16/10   | 758       | 8.2%    |
| Unknown | 386       | 4.17%   |
| 21/9    | 283       | 3.06%   |
| 5/4     | 278       | 3.01%   |
| 4/3     | 154       | 1.67%   |
| 3/2     | 45        | 0.49%   |
| 1.00    | 6         | 0.06%   |
| 6/5     | 1         | 0.01%   |
| 32/9    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2985      | 29.39%  |
| 81-90          | 2220      | 21.86%  |
| 201-250        | 1339      | 13.19%  |
| 141-150        | 831       | 8.18%   |
| 151-200        | 723       | 7.12%   |
| Unknown        | 441       | 4.34%   |
| 351-500        | 423       | 4.17%   |
| 301-350        | 207       | 2.04%   |
| More than 1000 | 152       | 1.5%    |
| 71-80          | 146       | 1.44%   |
| 121-130        | 119       | 1.17%   |
| 501-1000       | 108       | 1.06%   |
| 251-300        | 107       | 1.05%   |
| 131-140        | 104       | 1.02%   |
| 51-60          | 97        | 0.96%   |
| 41-50          | 45        | 0.44%   |
| 91-100         | 41        | 0.4%    |
| 111-120        | 34        | 0.33%   |
| 61-70          | 33        | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 4219      | 42.77%  |
| 51-100        | 3231      | 32.76%  |
| 121-160       | 1609      | 16.31%  |
| Unknown       | 442       | 4.48%   |
| 1-50          | 230       | 2.33%   |
| 161-240       | 113       | 1.15%   |
| More than 240 | 20        | 0.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 7713      | 79.91%  |
| 2     | 1465      | 15.18%  |
| 0     | 403       | 4.18%   |
| 3     | 69        | 0.71%   |
| 4     | 2         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 6715      | 44.48%  |
| Qualcomm Atheros                      | 3113      | 20.62%  |
| Intel                                 | 2415      | 16%     |
| Broadcom                              | 720       | 4.77%   |
| Ralink Technology                     | 354       | 2.35%   |
| Marvell Technology Group              | 201       | 1.33%   |
| Nvidia                                | 188       | 1.25%   |
| Ralink                                | 183       | 1.21%   |
| JMicron Technology                    | 173       | 1.15%   |
| Broadcom Limited                      | 158       | 1.05%   |
| TP-Link                               | 137       | 0.91%   |
| Qualcomm Atheros Communications       | 109       | 0.72%   |
| Silicon Integrated Systems [SiS]      | 94        | 0.62%   |
| Samsung Electronics                   | 83        | 0.55%   |
| VIA Technologies                      | 62        | 0.41%   |
| D-Link                                | 62        | 0.41%   |
| Motorola PCS                          | 37        | 0.25%   |
| Xiaomi                                | 34        | 0.23%   |
| Microsoft                             | 33        | 0.22%   |
| D-Link System                         | 33        | 0.22%   |
| ASIX Electronics                      | 23        | 0.15%   |
| ICS Advent                            | 14        | 0.09%   |
| Motorola                              | 12        | 0.08%   |
| MediaTek                              | 11        | 0.07%   |
| DisplayLink                           | 8         | 0.05%   |
| LG Electronics                        | 6         | 0.04%   |
| Dell                                  | 6         | 0.04%   |
| Mercucys                              | 5         | 0.03%   |
| Huawei Technologies                   | 5         | 0.03%   |
| Edimax Technology                     | 5         | 0.03%   |
| ASUSTek Computer                      | 5         | 0.03%   |
| 3Com                                  | 5         | 0.03%   |
| Qualcomm                              | 4         | 0.03%   |
| Lenovo                                | 4         | 0.03%   |
| Attansic Technology                   | 4         | 0.03%   |
| Arduino SA                            | 4         | 0.03%   |
| AMD                                   | 4         | 0.03%   |
| Accton Technology                     | 4         | 0.03%   |
| Sundance Technology Inc / IC Plus     | 3         | 0.02%   |
| Microchip Technology                  | 3         | 0.02%   |
| Hangzhou Silan Microelectronics       | 3         | 0.02%   |
| Ericsson Business Mobile Networks     | 3         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.02%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.01%   |
| Sierra Wireless                       | 2         | 0.01%   |
| Philips (or NXP)                      | 2         | 0.01%   |
| OPPO Electronics                      | 2         | 0.01%   |
| NetGear                               | 2         | 0.01%   |
| Micro Star International              | 2         | 0.01%   |
| Linksys                               | 2         | 0.01%   |
| IMC Networks                          | 2         | 0.01%   |
| Apple                                 | 2         | 0.01%   |
| Xilinx                                | 1         | 0.01%   |
| Unknown                               | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |
| T & A Mobile Phones                   | 1         | 0.01%   |
| Spreadtrum Communications             | 1         | 0.01%   |
| SK Hynix                              | 1         | 0.01%   |
| SILICON Laboratories                  | 1         | 0.01%   |
| Sagem                                 | 1         | 0.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 4464      | 27.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1512      | 9.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 725       | 4.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 613       | 3.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 564       | 3.42%   |
| Intel Wi-Fi 6 AX200                                                     | 296       | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 272       | 1.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 270       | 1.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 263       | 1.6%    |
| Ralink MT7601U Wireless Adapter                                         | 197       | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 188       | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 148       | 0.9%    |
| Nvidia MCP61 Ethernet                                                   | 142       | 0.86%   |
| Intel Wireless 7265                                                     | 139       | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 138       | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 127       | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 124       | 0.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 121       | 0.73%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 103       | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 100       | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 98        | 0.59%   |
| Qualcomm Atheros AR9271 802.11n                                         | 98        | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 94        | 0.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 92        | 0.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 87        | 0.53%   |
| Intel Wi-Fi 6 AX201                                                     | 87        | 0.53%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 83        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 83        | 0.5%    |
| Intel Wireless 3165                                                     | 81        | 0.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 80        | 0.49%   |
| Intel Wireless 7260                                                     | 80        | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 80        | 0.49%   |
| Intel Ethernet Connection (2) I219-V                                    | 76        | 0.46%   |
| Ralink RT5370 Wireless Adapter                                          | 74        | 0.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 70        | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 69        | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 68        | 0.41%   |
| Intel Wireless 3160                                                     | 67        | 0.41%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 67        | 0.41%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 66        | 0.4%    |
| Intel I211 Gigabit Network Connection                                   | 66        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                           | 62        | 0.38%   |
| Intel Ethernet Connection (7) I219-V                                    | 62        | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 61        | 0.37%   |
| Intel 82579V Gigabit Network Connection                                 | 61        | 0.37%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 59        | 0.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 57        | 0.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 55        | 0.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 55        | 0.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 55        | 0.33%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 52        | 0.32%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 52        | 0.32%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                     | 52        | 0.32%   |
| Intel Centrino Advanced-N 6235                                          | 50        | 0.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 49        | 0.3%    |
| VIA VT6102/VT6103 [Rhine-II]                                            | 46        | 0.28%   |
| Intel Wireless 8265 / 8275                                              | 46        | 0.28%   |
| Intel Ethernet Connection I217-LM                                       | 46        | 0.28%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                              | 45        | 0.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 45        | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 2714      | 37.79%  |
| Intel                                 | 1829      | 25.47%  |
| Realtek Semiconductor                 | 1162      | 16.18%  |
| Broadcom                              | 452       | 6.29%   |
| Ralink Technology                     | 354       | 4.93%   |
| Ralink                                | 183       | 2.55%   |
| TP-Link                               | 126       | 1.75%   |
| Qualcomm Atheros Communications       | 109       | 1.52%   |
| Broadcom Limited                      | 89        | 1.24%   |
| D-Link                                | 62        | 0.86%   |
| Microsoft                             | 33        | 0.46%   |
| D-Link System                         | 22        | 0.31%   |
| Marvell Technology Group              | 6         | 0.08%   |
| Mercucys                              | 5         | 0.07%   |
| MEDIATEK                              | 5         | 0.07%   |
| Edimax Technology                     | 5         | 0.07%   |
| Dell                                  | 3         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.04%   |
| Sierra Wireless                       | 2         | 0.03%   |
| Philips (or NXP)                      | 2         | 0.03%   |
| NetGear                               | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| Linksys                               | 2         | 0.03%   |
| IMC Networks                          | 2         | 0.03%   |
| Accton Technology                     | 2         | 0.03%   |
| Texas Instruments                     | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |
| Encore Electronics                    | 1         | 0.01%   |
| ASUSTek Computer                      | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 725       | 10.03%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 613       | 8.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 564       | 7.8%    |
| Intel Wi-Fi 6 AX200                                                     | 296       | 4.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 272       | 3.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 270       | 3.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 263       | 3.64%   |
| Ralink MT7601U Wireless Adapter                                         | 197       | 2.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 188       | 2.6%    |
| Intel Wireless 7265                                                     | 139       | 1.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 138       | 1.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 124       | 1.72%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 103       | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 100       | 1.38%   |
| Qualcomm Atheros AR9271 802.11n                                         | 98        | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 94        | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 92        | 1.27%   |
| Intel Wi-Fi 6 AX201                                                     | 87        | 1.2%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 83        | 1.15%   |
| Intel Wireless 3165                                                     | 81        | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 80        | 1.11%   |
| Intel Wireless 7260                                                     | 80        | 1.11%   |
| Ralink RT5370 Wireless Adapter                                          | 74        | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 70        | 0.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 68        | 0.94%   |
| Intel Wireless 3160                                                     | 67        | 0.93%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 67        | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 59        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 57        | 0.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 55        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 55        | 0.76%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 52        | 0.72%   |
| Intel Centrino Advanced-N 6235                                          | 50        | 0.69%   |
| Intel Wireless 8265 / 8275                                              | 46        | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 45        | 0.62%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 45        | 0.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 44        | 0.61%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 43        | 0.59%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 40        | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 38        | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 37        | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 35        | 0.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 35        | 0.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 35        | 0.48%   |
| Broadcom BCM43142 802.11b/g/n                                           | 35        | 0.48%   |
| Intel WiFi Link 5100                                                    | 34        | 0.47%   |
| Realtek 802.11ac NIC                                                    | 33        | 0.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 33        | 0.46%   |
| Intel Wireless-AC 9260                                                  | 33        | 0.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 30        | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 29        | 0.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 29        | 0.4%    |
| Intel Wireless 8260                                                     | 29        | 0.4%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 28        | 0.39%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 28        | 0.39%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 28        | 0.39%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 26        | 0.36%   |
| Intel Centrino Advanced-N 6200                                          | 26        | 0.36%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 25        | 0.35%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 22        | 0.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 6225      | 68.47%  |
| Intel                             | 864       | 9.5%    |
| Qualcomm Atheros                  | 615       | 6.76%   |
| Broadcom                          | 332       | 3.65%   |
| Marvell Technology Group          | 195       | 2.14%   |
| Nvidia                            | 187       | 2.06%   |
| JMicron Technology                | 173       | 1.9%    |
| Silicon Integrated Systems [SiS]  | 94        | 1.03%   |
| Samsung Electronics               | 82        | 0.9%    |
| Broadcom Limited                  | 75        | 0.82%   |
| VIA Technologies                  | 61        | 0.67%   |
| Xiaomi                            | 34        | 0.37%   |
| Motorola PCS                      | 29        | 0.32%   |
| ASIX Electronics                  | 23        | 0.25%   |
| ICS Advent                        | 14        | 0.15%   |
| TP-Link                           | 11        | 0.12%   |
| D-Link System                     | 11        | 0.12%   |
| DisplayLink                       | 8         | 0.09%   |
| MediaTek                          | 5         | 0.05%   |
| 3Com                              | 5         | 0.05%   |
| Qualcomm                          | 4         | 0.04%   |
| LG Electronics                    | 4         | 0.04%   |
| Lenovo                            | 4         | 0.04%   |
| Attansic Technology               | 4         | 0.04%   |
| ASUSTek Computer                  | 4         | 0.04%   |
| Sundance Technology Inc / IC Plus | 3         | 0.03%   |
| Hangzhou Silan Microelectronics   | 3         | 0.03%   |
| OPPO Electronics                  | 2         | 0.02%   |
| Microchip Technology              | 2         | 0.02%   |
| Huawei Technologies               | 2         | 0.02%   |
| Apple                             | 2         | 0.02%   |
| Accton Technology                 | 2         | 0.02%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.01%   |
| T & A Mobile Phones               | 1         | 0.01%   |
| Spreadtrum Communications         | 1         | 0.01%   |
| SK Hynix                          | 1         | 0.01%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.01%   |
| NetXen Incorporated               | 1         | 0.01%   |
| Netchip Technology                | 1         | 0.01%   |
| MosChip Semiconductor             | 1         | 0.01%   |
| IBM                               | 1         | 0.01%   |
| Chelsio Communications            | 1         | 0.01%   |
| Aquantia                          | 1         | 0.01%   |
| AMD                               | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 4464      | 48.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1512      | 16.46%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 148       | 1.61%   |
| Nvidia MCP61 Ethernet                                                          | 142       | 1.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 127       | 1.38%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 121       | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 98        | 1.07%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 87        | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 83        | 0.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 80        | 0.87%   |
| Intel Ethernet Connection (2) I219-V                                           | 76        | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 69        | 0.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 66        | 0.72%   |
| Intel I211 Gigabit Network Connection                                          | 66        | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 62        | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                           | 62        | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 61        | 0.66%   |
| Intel 82579V Gigabit Network Connection                                        | 61        | 0.66%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 55        | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 52        | 0.57%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 52        | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 49        | 0.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 46        | 0.5%    |
| Intel Ethernet Connection I217-LM                                              | 46        | 0.5%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 45        | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 42        | 0.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 36        | 0.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 35        | 0.38%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 35        | 0.38%   |
| Realtek RTL8125 2.5GbE Controller                                              | 32        | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 30        | 0.33%   |
| Motorola PCS moto g(30)                                                        | 29        | 0.32%   |
| Intel 82578DC Gigabit Network Connection                                       | 29        | 0.32%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 29        | 0.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 28        | 0.3%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 28        | 0.3%    |
| Intel Ethernet Connection (2) I218-V                                           | 27        | 0.29%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 27        | 0.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 25        | 0.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 24        | 0.26%   |
| Intel Ethernet Connection (4) I219-LM                                          | 24        | 0.26%   |
| Intel Ethernet Connection I217-V                                               | 23        | 0.25%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 21        | 0.23%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 21        | 0.23%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 20        | 0.22%   |
| Intel Ethernet Connection I219-LM                                              | 20        | 0.22%   |
| Intel 82578DM Gigabit Network Connection                                       | 20        | 0.22%   |
| Intel 82577LM Gigabit Network Connection                                       | 20        | 0.22%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 19        | 0.21%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 19        | 0.21%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 18        | 0.2%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 17        | 0.19%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 0.19%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 17        | 0.19%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 16        | 0.17%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 15        | 0.16%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 14        | 0.15%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 14        | 0.15%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 13        | 0.14%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 13        | 0.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 8789      | 55.72%  |
| WiFi     | 6917      | 43.85%  |
| Modem    | 48        | 0.3%    |
| Unknown  | 20        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6274      | 50.48%  |
| WiFi     | 6149      | 49.48%  |
| Unknown  | 5         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 5596      | 58.95%  |
| 1     | 3558      | 37.48%  |
| 0     | 259       | 2.73%   |
| 3     | 59        | 0.62%   |
| 4     | 14        | 0.15%   |
| 10    | 3         | 0.03%   |
| 8     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8115      | 83.97%  |
| Yes  | 1549      | 16.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1519      | 32.35%  |
| Qualcomm Atheros Communications | 1282      | 27.3%   |
| Lite-On Technology              | 563       | 11.99%  |
| Cambridge Silicon Radio         | 388       | 8.26%   |
| Broadcom                        | 197       | 4.2%    |
| Realtek Semiconductor           | 153       | 3.26%   |
| Foxconn / Hon Hai               | 104       | 2.21%   |
| Apple                           | 95        | 2.02%   |
| IMC Networks                    | 90        | 1.92%   |
| Dell                            | 66        | 1.41%   |
| Ralink                          | 44        | 0.94%   |
| Hewlett-Packard                 | 42        | 0.89%   |
| Unknown                         | 40        | 0.85%   |
| Qcom                            | 22        | 0.47%   |
| ASUSTek Computer                | 19        | 0.4%    |
| Ralink Technology               | 16        | 0.34%   |
| Alps Electric                   | 12        | 0.26%   |
| Foxconn International           | 11        | 0.23%   |
| Integrated System Solution      | 8         | 0.17%   |
| Askey Computer                  | 7         | 0.15%   |
| Toshiba                         | 4         | 0.09%   |
| Micro Star International        | 4         | 0.09%   |
| Conwise Technology              | 3         | 0.06%   |
| Marvell Semiconductor           | 2         | 0.04%   |
| Syntek                          | 1         | 0.02%   |
| Motorola PCS                    | 1         | 0.02%   |
| MediaTek                        | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 716       | 15.24%  |
| Intel Bluetooth wireless interface                                                  | 549       | 11.69%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 388       | 8.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 374       | 7.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 335       | 7.13%   |
| Intel AX200 Bluetooth                                                               | 288       | 6.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 199       | 4.24%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 135       | 2.87%   |
| Realtek Bluetooth Radio                                                             | 120       | 2.55%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 117       | 2.49%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 101       | 2.15%   |
| Intel AX201 Bluetooth                                                               | 91        | 1.94%   |
| Lite-On Bluetooth Device                                                            | 81        | 1.72%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 73        | 1.55%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 73        | 1.55%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 56        | 1.19%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 52        | 1.11%   |
| Intel Bluetooth Device                                                              | 51        | 1.09%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 51        | 1.09%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 51        | 1.09%   |
| Ralink RT3290 Bluetooth                                                             | 44        | 0.94%   |
| Unknown Bluetooth Device                                                            | 40        | 0.85%   |
| Apple Bluetooth Host Controller                                                     | 37        | 0.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 31        | 0.66%   |
| IMC Networks Bluetooth Radio                                                        | 30        | 0.64%   |
| Dell Wireless 365 Bluetooth                                                         | 29        | 0.62%   |
| IMC Networks Bluetooth Device                                                       | 28        | 0.6%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 28        | 0.6%    |
| Apple Bluetooth USB Host Controller                                                 | 27        | 0.57%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 26        | 0.55%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 24        | 0.51%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 20        | 0.43%   |
| Lite-On Atheros Bluetooth                                                           | 19        | 0.4%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 16        | 0.34%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 15        | 0.32%   |
| Realtek RTL8723A Bluetooth                                                          | 14        | 0.3%    |
| Qcom Broadcom Bluetooth USB                                                         | 14        | 0.3%    |
| Dell DW375 Bluetooth Module                                                         | 14        | 0.3%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 14        | 0.3%    |
| Apple Bluetooth HCI                                                                 | 14        | 0.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 13        | 0.28%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 13        | 0.28%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 13        | 0.28%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 13        | 0.28%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 12        | 0.26%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 11        | 0.23%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 11        | 0.23%   |
| IMC Networks Bluetooth                                                              | 10        | 0.21%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 9         | 0.19%   |
| Qcom Bluetooth USB                                                                  | 8         | 0.17%   |
| Dell Wireless 355 Bluetooth                                                         | 8         | 0.17%   |
| Broadcom BCM20702A0                                                                 | 8         | 0.17%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 8         | 0.17%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 0.15%   |
| Intel AX210 Bluetooth                                                               | 7         | 0.15%   |
| Broadcom BCM2045 Bluetooth                                                          | 7         | 0.15%   |
| Askey Bluetooth Device                                                              | 7         | 0.15%   |
| Broadcom HP Portable SoftSailing                                                    | 6         | 0.13%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 0.11%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 5         | 0.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 7361      | 61.22%  |
| Nvidia                                          | 1871      | 15.56%  |
| AMD                                             | 1858      | 15.45%  |
| C-Media Electronics                             | 193       | 1.61%   |
| Silicon Integrated Systems [SiS]                | 95        | 0.79%   |
| Generalplus Technology                          | 89        | 0.74%   |
| VIA Technologies                                | 68        | 0.57%   |
| Logitech                                        | 65        | 0.54%   |
| JMTek                                           | 52        | 0.43%   |
| Kingston Technology                             | 33        | 0.27%   |
| Creative Labs                                   | 30        | 0.25%   |
| Texas Instruments                               | 25        | 0.21%   |
| Corsair                                         | 24        | 0.2%    |
| Plantronics                                     | 18        | 0.15%   |
| Microsoft                                       | 18        | 0.15%   |
| Licensed by Sony Computer Entertainment America | 15        | 0.12%   |
| Tenx Technology                                 | 12        | 0.1%    |
| Razer USA                                       | 12        | 0.1%    |
| GN Netcom                                       | 12        | 0.1%    |
| BEHRINGER International                         | 12        | 0.1%    |
| Sony                                            | 9         | 0.07%   |
| Realtek Semiconductor                           | 8         | 0.07%   |
| Focusrite-Novation                              | 8         | 0.07%   |
| Dell                                            | 8         | 0.07%   |
| SteelSeries ApS                                 | 6         | 0.05%   |
| M-Audio                                         | 6         | 0.05%   |
| Fry's Electronics                               | 6         | 0.05%   |
| Philips (or NXP)                                | 5         | 0.04%   |
| JBL                                             | 5         | 0.04%   |
| BY EDIFIER                                      | 5         | 0.04%   |
| Turtle Beach                                    | 4         | 0.03%   |
| Tdlasunnic                                      | 4         | 0.03%   |
| Samsung Electronics                             | 4         | 0.03%   |
| Lenovo                                          | 4         | 0.03%   |
| Goldvish                                        | 4         | 0.03%   |
| Creative Technology                             | 4         | 0.03%   |
| Cirrus Logic                                    | 4         | 0.03%   |
| UCQ01000                                        | 3         | 0.02%   |
| FIFINE Microphones                              | 3         | 0.02%   |
| Elite Silicon                                   | 3         | 0.02%   |
| ATI Technologies                                | 3         | 0.02%   |
| Astro Gaming                                    | 3         | 0.02%   |
| Syntek                                          | 2         | 0.02%   |
| SOMIC Industrial                                | 2         | 0.02%   |
| Samson Technologies                             | 2         | 0.02%   |
| QinHeng Electronics                             | 2         | 0.02%   |
| Meizu                                           | 2         | 0.02%   |
| LG Electronics                                  | 2         | 0.02%   |
| EDIFIER Technology                              | 2         | 0.02%   |
| Casio Computer                                  | 2         | 0.02%   |
| BR25                                            | 2         | 0.02%   |
| Barco Display Systems                           | 2         | 0.02%   |
| Winbond Electronics                             | 1         | 0.01%   |
| USB-MIC                                         | 1         | 0.01%   |
| Unknown                                         | 1         | 0.01%   |
| Trident Microsystems                            | 1         | 0.01%   |
| Shenzhen Rapoo Technology                       | 1         | 0.01%   |
| SHARKOON Technologies                           | 1         | 0.01%   |
| Sennheiser Communications                       | 1         | 0.01%   |
| Roland                                          | 1         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 978       | 7.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 947       | 6.78%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 944       | 6.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 594       | 4.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 482       | 3.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 472       | 3.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 464       | 3.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 408       | 2.92%   |
| Intel 8 Series HD Audio Controller                                                                | 332       | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 328       | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 324       | 2.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 292       | 2.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 288       | 2.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 273       | 1.96%   |
| Intel Broadwell-U Audio Controller                                                                | 271       | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 270       | 1.93%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 263       | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 247       | 1.77%   |
| AMD FCH Azalia Controller                                                                         | 222       | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 215       | 1.54%   |
| Nvidia High Definition Audio Controller                                                           | 203       | 1.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 178       | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 166       | 1.19%   |
| Nvidia MCP61 High Definition Audio                                                                | 156       | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 152       | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 150       | 1.07%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 150       | 1.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 147       | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 142       | 1.02%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 140       | 1%      |
| AMD Wrestler HDMI Audio                                                                           | 136       | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 121       | 0.87%   |
| Intel 200 Series PCH HD Audio                                                                     | 116       | 0.83%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 116       | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 103       | 0.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 95        | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 94        | 0.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 93        | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 89        | 0.64%   |
| Generalplus Technology Usb Audio Device                                                           | 89        | 0.64%   |
| Intel CM238 HD Audio Controller                                                                   | 88        | 0.63%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 87        | 0.62%   |
| AMD Kabini HDMI/DP Audio                                                                          | 81        | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 76        | 0.54%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 75        | 0.54%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 67        | 0.48%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 56        | 0.4%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 52        | 0.37%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 50        | 0.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 50        | 0.36%   |
| Intel Comet Lake PCH cAVS                                                                         | 45        | 0.32%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 44        | 0.32%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 44        | 0.32%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 44        | 0.32%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 43        | 0.31%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 43        | 0.31%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 42        | 0.3%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 41        | 0.29%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 40        | 0.29%   |
| C-Media Electronics CM108 Audio Controller                                                        | 39        | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 685       | 18.64%  |
| Kingston            | 616       | 16.76%  |
| Smart               | 470       | 12.79%  |
| Samsung Electronics | 355       | 9.66%   |
| SK Hynix            | 253       | 6.88%   |
| A-DATA Technology   | 190       | 5.17%   |
| Corsair             | 185       | 5.03%   |
| Teikon              | 134       | 3.65%   |
| Crucial             | 128       | 3.48%   |
| Micron Technology   | 118       | 3.21%   |
| Smart Brazil        | 84        | 2.29%   |
| High Bridge         | 49        | 1.33%   |
| Elpida              | 41        | 1.12%   |
| Multilaser          | 35        | 0.95%   |
| G.Skill             | 29        | 0.79%   |
| Team                | 28        | 0.76%   |
| Apacer              | 25        | 0.68%   |
| Patriot             | 17        | 0.46%   |
| Nanya Technology    | 17        | 0.46%   |
| Unknown             | 16        | 0.44%   |
| Unknown (ABCD)      | 14        | 0.38%   |
| Avant               | 11        | 0.3%    |
| Ramaxel Technology  | 10        | 0.27%   |
| Kllisre             | 9         | 0.24%   |
| HT Micron           | 9         | 0.24%   |
| Smart Modular       | 8         | 0.22%   |
| RZX                 | 8         | 0.22%   |
| atermiter           | 8         | 0.22%   |
| Kreton              | 7         | 0.19%   |
| HBS                 | 7         | 0.19%   |
| CSX                 | 7         | 0.19%   |
| GEIL                | 6         | 0.16%   |
| Carry               | 6         | 0.16%   |
| Positivo            | 5         | 0.14%   |
| Kingmax             | 5         | 0.14%   |
| Unknown (82B5)      | 4         | 0.11%   |
| Puskill             | 4         | 0.11%   |
| Unknown (898F)      | 3         | 0.08%   |
| Silicon Power       | 3         | 0.08%   |
| Qbex                | 3         | 0.08%   |
| MemoWise            | 3         | 0.08%   |
| Hewlett-Packard     | 3         | 0.08%   |
| Goldkey             | 3         | 0.08%   |
| Gloway              | 3         | 0.08%   |
| AMD                 | 3         | 0.08%   |
| Walton Chaintech    | 2         | 0.05%   |
| Unknown (0x0194)    | 2         | 0.05%   |
| Transcend           | 2         | 0.05%   |
| Super Talent        | 2         | 0.05%   |
| SanDisk             | 2         | 0.05%   |
| Qimonda             | 2         | 0.05%   |
| pqi                 | 2         | 0.05%   |
| Lexar               | 2         | 0.05%   |
| Golden Empire       | 2         | 0.05%   |
| Catalyst            | 2         | 0.05%   |
| Apogee              | 2         | 0.05%   |
| ZIFEI               | 1         | 0.03%   |
| Veineda             | 1         | 0.03%   |
| Uroad               | 1         | 0.03%   |
| Unknown (8A02)      | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 66        | 1.63%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                   | 41        | 1.02%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 40        | 0.99%   |
| Smart RAM SH564568FH8NZPHSCR 2048MB SODIMM DDR3 1333MT/s            | 38        | 0.94%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 38        | 0.94%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s            | 31        | 0.77%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                        | 30        | 0.74%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s               | 30        | 0.74%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s               | 29        | 0.72%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 28        | 0.69%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s               | 26        | 0.64%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 26        | 0.64%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 26        | 0.64%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                 | 26        | 0.64%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 25        | 0.62%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 23        | 0.57%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s            | 23        | 0.57%   |
| Smart RAM SH564128FJ8NZRNSDG 4096MB SODIMM DDR3 1600MT/s            | 22        | 0.54%   |
| Smart RAM SH564128FJ8NWRNSQR 4096MB SODIMM DDR3 1600MT/s            | 21        | 0.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 20        | 0.5%    |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 20        | 0.5%    |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s              | 20        | 0.5%    |
| Teikon RAM TMA81GS6AFR8N-UHSC 8192MB SODIMM DDR4 2400MT/s           | 18        | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 18        | 0.45%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 17        | 0.42%   |
| Unknown                                                             | 16        | 0.4%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                         | 15        | 0.37%   |
| Smart RAM SH564568FH8NZPHSCG 2048MB SODIMM DDR3 1333MT/s            | 15        | 0.37%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s               | 15        | 0.37%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 15        | 0.37%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s                        | 15        | 0.37%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 14        | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 14        | 0.35%   |
| Smart RAM SH564568FH8NWPHSFG 2048MB SODIMM DDR3 1333MT/s            | 14        | 0.35%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s                | 14        | 0.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 14        | 0.35%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s                 | 14        | 0.35%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 13        | 0.32%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s               | 13        | 0.32%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s                | 13        | 0.32%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                              | 12        | 0.3%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 12        | 0.3%    |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s               | 12        | 0.3%    |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                | 12        | 0.3%    |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s             | 12        | 0.3%    |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s          | 12        | 0.3%    |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 11        | 0.27%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 11        | 0.27%   |
| Unknown RAM Module 4096MB DIMM SDRAM                                | 11        | 0.27%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 11        | 0.27%   |
| Unknown RAM Module 2048MB DIMM DDR2                                 | 11        | 0.27%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s            | 11        | 0.27%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s         | 11        | 0.27%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s                | 11        | 0.27%   |
| A-DATA RAM AM1P26KC4U1-BACS 4GB SODIMM DDR4 2667MT/s                | 11        | 0.27%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                        | 10        | 0.25%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                             | 10        | 0.25%   |
| Unknown RAM Module 2GB DIMM DDR2                                    | 10        | 0.25%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s                 | 10        | 0.25%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s          | 10        | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 1397      | 44.41%  |
| DDR4         | 1099      | 34.93%  |
| DDR2         | 229       | 7.28%   |
| Unknown      | 162       | 5.15%   |
| SDRAM        | 138       | 4.39%   |
| LPDDR4       | 40        | 1.27%   |
| DDR          | 40        | 1.27%   |
| LPDDR3       | 24        | 0.76%   |
| DRAM         | 15        | 0.48%   |
| RAM          | 1         | 0.03%   |
| DDR2 FB-DIMM | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1682      | 54.07%  |
| DIMM         | 1362      | 43.78%  |
| Row Of Chips | 53        | 1.7%    |
| Unknown      | 8         | 0.26%   |
| RIMM         | 2         | 0.06%   |
| FB-DIMM      | 2         | 0.06%   |
| Chip         | 2         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1351      | 38.16%  |
| 8192  | 962       | 27.18%  |
| 2048  | 772       | 21.81%  |
| 16384 | 264       | 7.46%   |
| 1024  | 133       | 3.76%   |
| 32768 | 41        | 1.16%   |
| 512   | 14        | 0.4%    |
| 256   | 2         | 0.06%   |
| 16    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 743       | 21.23%  |
| 1333    | 505       | 14.43%  |
| 2667    | 450       | 12.86%  |
| 2400    | 338       | 9.66%   |
| Unknown | 186       | 5.31%   |
| 1334    | 175       | 5%      |
| 800     | 138       | 3.94%   |
| 2133    | 118       | 3.37%   |
| 3200    | 113       | 3.23%   |
| 667     | 113       | 3.23%   |
| 2933    | 56        | 1.6%    |
| 1067    | 49        | 1.4%    |
| 1066    | 48        | 1.37%   |
| 3600    | 42        | 1.2%    |
| 3000    | 41        | 1.17%   |
| 1867    | 41        | 1.17%   |
| 4199    | 31        | 0.89%   |
| 3466    | 29        | 0.83%   |
| 1866    | 29        | 0.83%   |
| 533     | 28        | 0.8%    |
| 2666    | 24        | 0.69%   |
| 2800    | 23        | 0.66%   |
| 4267    | 18        | 0.51%   |
| 2048    | 17        | 0.49%   |
| 975     | 16        | 0.46%   |
| 3151    | 14        | 0.4%    |
| 400     | 13        | 0.37%   |
| 3733    | 11        | 0.31%   |
| 333     | 11        | 0.31%   |
| 3266    | 10        | 0.29%   |
| 3334    | 7         | 0.2%    |
| 3333    | 5         | 0.14%   |
| 1200    | 5         | 0.14%   |
| 3533    | 3         | 0.09%   |
| 3400    | 3         | 0.09%   |
| 2132    | 3         | 0.09%   |
| 1400    | 3         | 0.09%   |
| 49926   | 2         | 0.06%   |
| 5354    | 2         | 0.06%   |
| 3100    | 2         | 0.06%   |
| 3066    | 2         | 0.06%   |
| 2733    | 2         | 0.06%   |
| 1639    | 2         | 0.06%   |
| 1332    | 2         | 0.06%   |
| 133     | 2         | 0.06%   |
| 65535   | 1         | 0.03%   |
| 52217   | 1         | 0.03%   |
| 41632   | 1         | 0.03%   |
| 4133    | 1         | 0.03%   |
| 4000    | 1         | 0.03%   |
| 3800    | 1         | 0.03%   |
| 3500    | 1         | 0.03%   |
| 3067    | 1         | 0.03%   |
| 3007    | 1         | 0.03%   |
| 2866    | 1         | 0.03%   |
| 2747    | 1         | 0.03%   |
| 2267    | 1         | 0.03%   |
| 2200    | 1         | 0.03%   |
| 2134    | 1         | 0.03%   |
| 1776    | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 98        | 45.37%  |
| Seiko Epson           | 55        | 25.46%  |
| Samsung Electronics   | 20        | 9.26%   |
| Brother Industries    | 16        | 7.41%   |
| Canon                 | 15        | 6.94%   |
| QinHeng Electronics   | 2         | 0.93%   |
| Lexmark International | 2         | 0.93%   |
| Apple                 | 2         | 0.93%   |
| Xerox                 | 1         | 0.46%   |
| Ricoh                 | 1         | 0.46%   |
| Prolific Technology   | 1         | 0.46%   |
| Oki Data              | 1         | 0.46%   |
| MIIIW                 | 1         | 0.46%   |
| ARGOX                 | 1         | 0.46%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                   | 11        | 5.09%   |
| Seiko Epson L395 Series                      | 9         | 4.17%   |
| HP DeskJet 2130 series                       | 8         | 3.7%    |
| HP Deskjet 3050 J610 series                  | 7         | 3.24%   |
| HP Deskjet 2540 series                       | 7         | 3.24%   |
| Seiko Epson L365 Series                      | 6         | 2.78%   |
| Seiko Epson L355 Series                      | 6         | 2.78%   |
| HP Ink Tank Wireless 410 series              | 6         | 2.78%   |
| Samsung SCX-4200 series                      | 5         | 2.31%   |
| HP LaserJet Professional P1102w              | 5         | 2.31%   |
| HP LaserJet 1020                             | 5         | 2.31%   |
| HP DeskJet F4100 Printer series              | 5         | 2.31%   |
| Samsung M2070 Series                         | 4         | 1.85%   |
| HP LaserJet P1005                            | 4         | 1.85%   |
| HP DeskJet F4200 series                      | 4         | 1.85%   |
| HP DeskJet 3630 series                       | 4         | 1.85%   |
| HP DeskJet 2600 series                       | 4         | 1.85%   |
| Canon G3010 series                           | 4         | 1.85%   |
| Seiko Epson L210 Series                      | 3         | 1.39%   |
| Samsung M2020 Series                         | 3         | 1.39%   |
| HP Deskjet F4400 series                      | 3         | 1.39%   |
| HP DeskJet 2700 series                       | 3         | 1.39%   |
| HP Deskjet 2050 J510                         | 3         | 1.39%   |
| Brother HL-1200 series                       | 3         | 1.39%   |
| Seiko Epson XP-243 245 247 Series            | 2         | 0.93%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 2         | 0.93%   |
| Seiko Epson L4150 Series                     | 2         | 0.93%   |
| Seiko Epson L375 Series                      | 2         | 0.93%   |
| Seiko Epson ET-3750 Series                   | 2         | 0.93%   |
| Samsung SCX-3200 Series                      | 2         | 0.93%   |
| QinHeng CH340S                               | 2         | 0.93%   |
| HP Printing Support                          | 2         | 0.93%   |
| HP LaserJet 1018                             | 2         | 0.93%   |
| HP DeskJet D1360                             | 2         | 0.93%   |
| HP Deskjet 4620 series                       | 2         | 0.93%   |
| HP DeskJet 2300 series                       | 2         | 0.93%   |
| Canon PIXMA MG3000 series                    | 2         | 0.93%   |
| Brother HL-1210W series                      | 2         | 0.93%   |
| Brother DCP-7055 scanner/printer             | 2         | 0.93%   |
| Apple Gamesir-G3s 2.10                       | 2         | 0.93%   |
| Xerox Phaser 3040                            | 1         | 0.46%   |
| Seiko Epson XP-235 Series                    | 1         | 0.46%   |
| Seiko Epson XP-211 214 216 Series            | 1         | 0.46%   |
| Seiko Epson Printer                          | 1         | 0.46%   |
| Seiko Epson L805 Series                      | 1         | 0.46%   |
| Seiko Epson L380 Series                      | 1         | 0.46%   |
| Seiko Epson L3110 Series                     | 1         | 0.46%   |
| Seiko Epson L222 Series                      | 1         | 0.46%   |
| Seiko Epson L1300 Series                     | 1         | 0.46%   |
| Seiko Epson L120 Series                      | 1         | 0.46%   |
| Seiko Epson Epson Stylus T25 Series          | 1         | 0.46%   |
| Samsung SCX-4623 Series                      | 1         | 0.46%   |
| Samsung SCX-4600 Series                      | 1         | 0.46%   |
| Samsung SCX-3400 Series                      | 1         | 0.46%   |
| Samsung ML-216x Series Laser Printer         | 1         | 0.46%   |
| Samsung ML-1865W Series                      | 1         | 0.46%   |
| Samsung M332x 382x 402x Series               | 1         | 0.46%   |
| Ricoh Printing Support                       | 1         | 0.46%   |
| Prolific PL2305 Parallel Port                | 1         | 0.46%   |
| Oki Data USB Device                          | 1         | 0.46%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 8         | 42.11%  |
| Canon           | 8         | 42.11%  |
| Seiko Epson     | 2         | 10.53%  |
| Mustek Systems  | 1         | 5.26%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP ScanJet 2400c                                        | 5         | 26.32%  |
| Canon CanoScan LIDE 25                                  | 4         | 21.05%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 5.26%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 5.26%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 5.26%   |
| HP ScanJet G4050                                        | 1         | 5.26%   |
| HP ScanJet 3800c                                        | 1         | 5.26%   |
| HP Scanjet 200                                          | 1         | 5.26%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5.26%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 5.26%   |
| Canon CanoScan LiDE 210                                 | 1         | 5.26%   |
| Canon CanoScan LiDE 110                                 | 1         | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1174      | 20.25%  |
| Microdia                               | 638       | 11%     |
| Realtek Semiconductor                  | 537       | 9.26%   |
| Quanta                                 | 495       | 8.54%   |
| Silicon Motion                         | 434       | 7.49%   |
| Sunplus Innovation Technology          | 413       | 7.12%   |
| Acer                                   | 389       | 6.71%   |
| Suyin                                  | 236       | 4.07%   |
| IMC Networks                           | 217       | 3.74%   |
| Logitech                               | 200       | 3.45%   |
| Syntek                                 | 166       | 2.86%   |
| Alcor Micro                            | 117       | 2.02%   |
| Apple                                  | 85        | 1.47%   |
| Samsung Electronics                    | 75        | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) | 68        | 1.17%   |
| Z-Star Microelectronics                | 49        | 0.85%   |
| Generalplus Technology                 | 46        | 0.79%   |
| Microsoft                              | 43        | 0.74%   |
| Ricoh                                  | 42        | 0.72%   |
| ALi                                    | 39        | 0.67%   |
| Unknown                                | 24        | 0.41%   |
| Importek                               | 22        | 0.38%   |
| Aveo Technology                        | 22        | 0.38%   |
| Lite-On Technology                     | 20        | 0.34%   |
| OmniVision Technologies                | 19        | 0.33%   |
| GEMBIRD                                | 19        | 0.33%   |
| Pixart Imaging                         | 17        | 0.29%   |
| LG Electronics                         | 17        | 0.29%   |
| Cubeternet                             | 13        | 0.22%   |
| Lenovo                                 | 12        | 0.21%   |
| Genesys Logic                          | 10        | 0.17%   |
| Sunplus Technology                     | 9         | 0.16%   |
| Jieli Technology                       | 9         | 0.16%   |
| Intel                                  | 9         | 0.16%   |
| Camera                                 | 8         | 0.14%   |
| MacroSilicon                           | 7         | 0.12%   |
| Arkmicro Technologies                  | 7         | 0.12%   |
| KYE Systems (Mouse Systems)            | 6         | 0.1%    |
| Image Processor                        | 5         | 0.09%   |
| Hewlett-Packard                        | 5         | 0.09%   |
| DigiTech                               | 5         | 0.09%   |
| USB Camera                             | 4         | 0.07%   |
| Philips (or NXP)                       | 4         | 0.07%   |
| JMicron Technology                     | 4         | 0.07%   |
| GenesysLogic Technology                | 4         | 0.07%   |
| Foxconn / Hon Hai                      | 4         | 0.07%   |
| SunplusIT                              | 3         | 0.05%   |
| Primax Electronics                     | 3         | 0.05%   |
| Fitipower Integrated Technology        | 3         | 0.05%   |
| A4Tech                                 | 3         | 0.05%   |
| YGTek                                  | 2         | 0.03%   |
| Y Media                                | 2         | 0.03%   |
| Xiongmai                               | 2         | 0.03%   |
| WCM_USB                                | 2         | 0.03%   |
| Sonix Technology                       | 2         | 0.03%   |
| Huawei Technologies                    | 2         | 0.03%   |
| Denron                                 | 2         | 0.03%   |
| Creative Technology                    | 2         | 0.03%   |
| CQG-5693-201019                        | 2         | 0.03%   |
| Asuscom Network                        | 2         | 0.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD              | 221       | 3.81%   |
| Chicony HD WebCam                         | 214       | 3.69%   |
| Microdia Integrated_Webcam_HD             | 209       | 3.6%    |
| Quanta HD User Facing                     | 198       | 3.41%   |
| Chicony HD User Facing                    | 181       | 3.12%   |
| Sunplus Integrated_Webcam_HD              | 170       | 2.93%   |
| Quanta VGA WebCam                         | 161       | 2.77%   |
| Silicon Motion Web Camera                 | 152       | 2.62%   |
| Chicony VGA WebCam                        | 120       | 2.07%   |
| Chicony Integrated Camera                 | 107       | 1.84%   |
| Realtek Integrated Webcam                 | 91        | 1.57%   |
| Quanta HD Webcam                          | 88        | 1.52%   |
| Syntek Integrated Camera                  | 85        | 1.46%   |
| Sunplus HD WebCam                         | 85        | 1.46%   |
| Logitech Webcam C270                      | 83        | 1.43%   |
| Microdia Laptop_Integrated_Webcam_HD      | 80        | 1.38%   |
| Chicony USB 2.0 Camera                    | 76        | 1.31%   |
| Samsung Galaxy A5 (MTP)                   | 74        | 1.27%   |
| Alcor Micro USB 2.0 Camera                | 72        | 1.24%   |
| Acer BisonCam, NB Pro                     | 64        | 1.1%    |
| Acer EasyCamera                           | 60        | 1.03%   |
| Acer Lenovo EasyCamera                    | 55        | 0.95%   |
| Realtek USB Camera                        | 53        | 0.91%   |
| Microdia Dell Laptop Integrated Webcam HD | 49        | 0.84%   |
| Logitech HD Pro Webcam C920               | 43        | 0.74%   |
| Silicon Motion WebCam SC-10HDD12636N      | 42        | 0.72%   |
| Microdia Integrated Webcam HD             | 40        | 0.69%   |
| Acer VGA WebCam                           | 38        | 0.65%   |
| Silicon Motion WebCam SCB-1100N           | 37        | 0.64%   |
| Realtek HD WebCam                         | 37        | 0.64%   |
| Chicony EasyCamera                        | 37        | 0.64%   |
| IMC Networks Integrated Camera            | 35        | 0.6%    |
| Silicon Motion WebCam SC-13HDL11939N      | 33        | 0.57%   |
| Acer Integrated Camera                    | 33        | 0.57%   |
| Syntek EasyCamera                         | 32        | 0.55%   |
| Generalplus GENERAL WEBCAM                | 32        | 0.55%   |
| Acer HD Webcam                            | 32        | 0.55%   |
| Suyin Integrated_Webcam_HD                | 30        | 0.52%   |
| Silicon Motion WebCam SCB-0385N           | 30        | 0.52%   |
| Chicony Lenovo EasyCamera                 | 30        | 0.52%   |
| Silicon Motion WebCam SC-0311139N         | 28        | 0.48%   |
| Microdia Sonix USB 2.0 Camera             | 28        | 0.48%   |
| Microdia Integrated Webcam                | 28        | 0.48%   |
| IMC Networks USB2.0 HD UVC WebCam         | 28        | 0.48%   |
| Realtek EasyCamera                        | 27        | 0.47%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 27        | 0.47%   |
| Chicony USB2.0 VGA UVC WebCam             | 26        | 0.45%   |
| Chicony USB2.0 HD UVC WebCam              | 26        | 0.45%   |
| Chicony HP TrueVision HD                  | 26        | 0.45%   |
| Chicony HD WebCam (Acer)                  | 26        | 0.45%   |
| Suyin HP Webcam-101                       | 25        | 0.43%   |
| Apple FaceTime HD Camera                  | 25        | 0.43%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 23        | 0.4%    |
| Silicon Motion ATIV VGA Camera            | 23        | 0.4%    |
| Chicony USB2.0 Camera                     | 23        | 0.4%    |
| Chicony Integrated Camera (1280x720@30)   | 23        | 0.4%    |
| Apple iPhone 5/5C/5S/6/SE                 | 23        | 0.4%    |
| Sunplus Integrated Webcam                 | 21        | 0.36%   |
| IMC Networks EasyCamera                   | 21        | 0.36%   |
| Apple Built-in iSight                     | 21        | 0.36%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 237       | 47.88%  |
| Synaptics                  | 62        | 12.53%  |
| Upek                       | 49        | 9.9%    |
| Shenzhen Goodix Technology | 46        | 9.29%   |
| AuthenTec                  | 45        | 9.09%   |
| LighTuning Technology      | 26        | 5.25%   |
| Samsung Electronics        | 15        | 3.03%   |
| Elan Microelectronics      | 7         | 1.41%   |
| STMicroelectronics         | 3         | 0.61%   |
| Dell                       | 2         | 0.4%    |
| Futronic Technology        | 1         | 0.2%    |
| Focal-systems.Corp         | 1         | 0.2%    |
| DigitalPersona             | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 83        | 16.77%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 41        | 8.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 33        | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 25        | 5.05%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 4.65%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 4.24%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 21        | 4.24%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 20        | 4.04%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 4.04%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 17        | 3.43%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 15        | 3.03%   |
| Synaptics  WBDI                                                            | 15        | 3.03%   |
| Samsung Fingerprint Device                                                 | 15        | 3.03%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 2.42%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.42%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 2.02%   |
| Validity Sensors VFS491                                                    | 9         | 1.82%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 1.62%   |
| AuthenTec AES2810                                                          | 8         | 1.62%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 7         | 1.41%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 1.41%   |
| Elan ELAN:Fingerprint                                                      | 7         | 1.41%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.41%   |
| Unknown                                                                    | 7         | 1.41%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.21%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.21%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.01%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 0.81%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.61%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.61%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.61%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.4%    |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 2         | 0.4%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.2%    |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.2%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.2%    |
| Upek TouchStrip Fingerprint Sensor                                         | 1         | 0.2%    |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.2%    |
| Futronic FS81 Fingerprint Scanner Module                                   | 1         | 0.2%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.2%    |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.2%    |
| AuthenTec AES1600                                                          | 1         | 0.2%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 65        | 42.21%  |
| Alcor Micro                       | 24        | 15.58%  |
| Lenovo                            | 11        | 7.14%   |
| Giesecke & Devrient               | 11        | 7.14%   |
| Gemalto (was Gemplus)             | 11        | 7.14%   |
| Upek                              | 8         | 5.19%   |
| Watchdata                         | 5         | 3.25%   |
| Aladdin Knowledge Systems         | 5         | 3.25%   |
| SCM Microsystems                  | 3         | 1.95%   |
| OmniKey                           | 3         | 1.95%   |
| Chicony Electronics               | 3         | 1.95%   |
| O2 Micro                          | 2         | 1.3%    |
| VASCO Data Security International | 1         | 0.65%   |
| Realtek Semiconductor             | 1         | 0.65%   |
| Advanced Card Systems             | 1         | 0.65%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 15.58%  |
| Broadcom BCM5880 Secure Applications Processor                               | 19        | 12.34%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 10.39%  |
| Broadcom 5880                                                                | 16        | 10.39%  |
| Broadcom 58200                                                               | 14        | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 7.14%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 10        | 6.49%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 5.19%   |
| Giesecke & Devrient StarSign CUT                                             | 6         | 3.9%    |
| Watchdata USB Key                                                            | 5         | 3.25%   |
| Giesecke & Devrient StarSign CUT S                                           | 5         | 3.25%   |
| Aladdin Knowledge Systems Token JC                                           | 5         | 3.25%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 1.95%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 1.3%    |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.3%    |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.65%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.65%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.65%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.65%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.65%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 0.65%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.65%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.65%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 7748      | 80.69%  |
| 1     | 1631      | 16.99%  |
| 2     | 184       | 1.92%   |
| 3     | 24        | 0.25%   |
| 4     | 11        | 0.11%   |
| 7     | 2         | 0.02%   |
| 8     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 603       | 29.33%  |
| Fingerprint reader       | 491       | 23.88%  |
| Net/wireless             | 257       | 12.5%   |
| Multimedia controller    | 153       | 7.44%   |
| Chipcard                 | 133       | 6.47%   |
| Communication controller | 82        | 3.99%   |
| Bluetooth                | 70        | 3.4%    |
| Camera                   | 56        | 2.72%   |
| Unassigned class         | 44        | 2.14%   |
| Sound                    | 42        | 2.04%   |
| Storage                  | 32        | 1.56%   |
| Net/ethernet             | 23        | 1.12%   |
| Modem                    | 22        | 1.07%   |
| Flash memory             | 19        | 0.92%   |
| Card reader              | 9         | 0.44%   |
| Network                  | 5         | 0.24%   |
| Firewire controller      | 5         | 0.24%   |
| Storage/ide              | 4         | 0.19%   |
| Storage/raid             | 3         | 0.15%   |
| Video                    | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

