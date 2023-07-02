Linux in Russia - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Russia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Russia/Desktop/README.md) and [notebooks](/Location/Russia/Notebook/README.md).

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

Total: 39507

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Chuwi         | Hi10 pro tablet             | Tablet      | [ac39cc2f2a](https://linux-hardware.org/?probe=ac39cc2f2a) | Jul 01, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [c43e65f1ae](https://linux-hardware.org/?probe=c43e65f1ae) | Jun 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [b5d1a7e115](https://linux-hardware.org/?probe=b5d1a7e115) | Jun 30, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [434ba90999](https://linux-hardware.org/?probe=434ba90999) | Jun 30, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [0eb501cde5](https://linux-hardware.org/?probe=0eb501cde5) | Jun 30, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [b2d81d6e67](https://linux-hardware.org/?probe=b2d81d6e67) | Jun 30, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [8bfe14749f](https://linux-hardware.org/?probe=8bfe14749f) | Jun 30, 2023 |
| Gigabyte      | G33M-S2L                    | Desktop     | [99ffcc407b](https://linux-hardware.org/?probe=99ffcc407b) | Jun 30, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [befac7b8de](https://linux-hardware.org/?probe=befac7b8de) | Jun 30, 2023 |
| Supermicro    | X8DTU                       | Server      | [4ff2cd1bcf](https://linux-hardware.org/?probe=4ff2cd1bcf) | Jun 30, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [661dc06ef7](https://linux-hardware.org/?probe=661dc06ef7) | Jun 30, 2023 |
| Lenovo        | ThinkPad E490 20N80017RT    | Notebook    | [a2a1011725](https://linux-hardware.org/?probe=a2a1011725) | Jun 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [2fe05dff41](https://linux-hardware.org/?probe=2fe05dff41) | Jun 30, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [5e11bea093](https://linux-hardware.org/?probe=5e11bea093) | Jun 30, 2023 |
| Timi          | Xiaomi Book Air 13 2022     | Convertible | [2d7ee2c4a8](https://linux-hardware.org/?probe=2d7ee2c4a8) | Jun 30, 2023 |
| Chuwi         | CoreBook XPro               | Notebook    | [501d899938](https://linux-hardware.org/?probe=501d899938) | Jun 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [5199efd89e](https://linux-hardware.org/?probe=5199efd89e) | Jun 30, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0272953855](https://linux-hardware.org/?probe=0272953855) | Jun 30, 2023 |
| Supermicro    | X8DTU                       | Server      | [a1fa5d4047](https://linux-hardware.org/?probe=a1fa5d4047) | Jun 30, 2023 |
| Supermicro    | X8DTU                       | Server      | [f62d2cd7ee](https://linux-hardware.org/?probe=f62d2cd7ee) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [05cb990f84](https://linux-hardware.org/?probe=05cb990f84) | Jun 30, 2023 |
| Supermicro    | X9DRW                       | Desktop     | [cb955d7a58](https://linux-hardware.org/?probe=cb955d7a58) | Jun 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [9fc143ab80](https://linux-hardware.org/?probe=9fc143ab80) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [4677625b04](https://linux-hardware.org/?probe=4677625b04) | Jun 30, 2023 |
| ASRock        | G31M-GS                     | Desktop     | [3bd67e0f9f](https://linux-hardware.org/?probe=3bd67e0f9f) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [5dd37cbc97](https://linux-hardware.org/?probe=5dd37cbc97) | Jun 30, 2023 |
| ASUSTek       | ME176C                      | Notebook    | [2f2e7076e1](https://linux-hardware.org/?probe=2f2e7076e1) | Jun 30, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [9a9ca045af](https://linux-hardware.org/?probe=9a9ca045af) | Jun 30, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [a366d05b2b](https://linux-hardware.org/?probe=a366d05b2b) | Jun 30, 2023 |
| ASUSTek       | K52F                        | Notebook    | [98e9b448c7](https://linux-hardware.org/?probe=98e9b448c7) | Jun 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [b98433fa84](https://linux-hardware.org/?probe=b98433fa84) | Jun 29, 2023 |
| Dell          | Studio 1558                 | Notebook    | [66e76ea87d](https://linux-hardware.org/?probe=66e76ea87d) | Jun 29, 2023 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [bce7d100cf](https://linux-hardware.org/?probe=bce7d100cf) | Jun 29, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f3cb4dc749](https://linux-hardware.org/?probe=f3cb4dc749) | Jun 29, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [6a95d2096d](https://linux-hardware.org/?probe=6a95d2096d) | Jun 29, 2023 |
| Acer          | Aspire E5-531G              | Notebook    | [a6eaac367e](https://linux-hardware.org/?probe=a6eaac367e) | Jun 29, 2023 |
| MSI           | MS-7267 100                 | Desktop     | [3a014aae8a](https://linux-hardware.org/?probe=3a014aae8a) | Jun 29, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [9979e7a733](https://linux-hardware.org/?probe=9979e7a733) | Jun 29, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [057b246898](https://linux-hardware.org/?probe=057b246898) | Jun 29, 2023 |
| Supermicro    | X8DTU                       | Server      | [1f006cb678](https://linux-hardware.org/?probe=1f006cb678) | Jun 29, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [e12c71fb39](https://linux-hardware.org/?probe=e12c71fb39) | Jun 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [1c349accca](https://linux-hardware.org/?probe=1c349accca) | Jun 29, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [9d4c4f5506](https://linux-hardware.org/?probe=9d4c4f5506) | Jun 29, 2023 |
| Acer          | Aspire TC-705               | Desktop     | [326f873ac3](https://linux-hardware.org/?probe=326f873ac3) | Jun 29, 2023 |
| eMachines     | eME728                      | Notebook    | [37dc0ef617](https://linux-hardware.org/?probe=37dc0ef617) | Jun 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [076e14da35](https://linux-hardware.org/?probe=076e14da35) | Jun 29, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [61930889dc](https://linux-hardware.org/?probe=61930889dc) | Jun 29, 2023 |
| Biostar       | H510MHP                     | Desktop     | [7ddeb5c281](https://linux-hardware.org/?probe=7ddeb5c281) | Jun 29, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [f40af0020a](https://linux-hardware.org/?probe=f40af0020a) | Jun 29, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [305a3e3c1a](https://linux-hardware.org/?probe=305a3e3c1a) | Jun 29, 2023 |
| HP            | Pavilion g6                 | Notebook    | [b16b0ced2f](https://linux-hardware.org/?probe=b16b0ced2f) | Jun 28, 2023 |
| HP            | Notebook                    | Notebook    | [d5ab0810e6](https://linux-hardware.org/?probe=d5ab0810e6) | Jun 28, 2023 |
| HP            | Notebook                    | Notebook    | [2b5ac7b339](https://linux-hardware.org/?probe=2b5ac7b339) | Jun 28, 2023 |
| ASUSTek       | M2A-VM                      | Desktop     | [d25910c419](https://linux-hardware.org/?probe=d25910c419) | Jun 28, 2023 |
| Gigabyte      | MRHM3AP                     | Desktop     | [2d91c7c05a](https://linux-hardware.org/?probe=2d91c7c05a) | Jun 28, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [6197072395](https://linux-hardware.org/?probe=6197072395) | Jun 28, 2023 |
| Intel         | DG965SS AAD41678-304        | Desktop     | [696cd9ce01](https://linux-hardware.org/?probe=696cd9ce01) | Jun 28, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [978c7d9a50](https://linux-hardware.org/?probe=978c7d9a50) | Jun 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [0ea4bcb3df](https://linux-hardware.org/?probe=0ea4bcb3df) | Jun 28, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [69f1784c40](https://linux-hardware.org/?probe=69f1784c40) | Jun 28, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [2545527872](https://linux-hardware.org/?probe=2545527872) | Jun 28, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [9a96d38f8a](https://linux-hardware.org/?probe=9a96d38f8a) | Jun 28, 2023 |
| Huanan        | X99-BD4 V1.31               | Desktop     | [fcd9a6b1e2](https://linux-hardware.org/?probe=fcd9a6b1e2) | Jun 28, 2023 |
| Aquarius      | NS585                       | Notebook    | [52a07593c9](https://linux-hardware.org/?probe=52a07593c9) | Jun 28, 2023 |
| Aquarius      | NS585                       | Notebook    | [b2f86e98f9](https://linux-hardware.org/?probe=b2f86e98f9) | Jun 28, 2023 |
| Supermicro    | H11SSL-i                    | Server      | [2713ca5a34](https://linux-hardware.org/?probe=2713ca5a34) | Jun 28, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | Notebook    | [5ea6336cb5](https://linux-hardware.org/?probe=5ea6336cb5) | Jun 28, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [36f9eb51e6](https://linux-hardware.org/?probe=36f9eb51e6) | Jun 28, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [6a2c4254e7](https://linux-hardware.org/?probe=6a2c4254e7) | Jun 28, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | Notebook    | [1d6bf708ce](https://linux-hardware.org/?probe=1d6bf708ce) | Jun 28, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [ab4772fd2e](https://linux-hardware.org/?probe=ab4772fd2e) | Jun 28, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [bc9d733b89](https://linux-hardware.org/?probe=bc9d733b89) | Jun 27, 2023 |
| Gigabyte      | MRHM3AP                     | Desktop     | [7007bb2db5](https://linux-hardware.org/?probe=7007bb2db5) | Jun 27, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [7de1b2a03f](https://linux-hardware.org/?probe=7de1b2a03f) | Jun 27, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [b96f0a3b19](https://linux-hardware.org/?probe=b96f0a3b19) | Jun 27, 2023 |
| MSI           | GL65 Leopard 10SCSR         | Notebook    | [165a76b787](https://linux-hardware.org/?probe=165a76b787) | Jun 27, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [65794907cc](https://linux-hardware.org/?probe=65794907cc) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2ed9f4248c](https://linux-hardware.org/?probe=2ed9f4248c) | Jun 27, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [a0c358b2b3](https://linux-hardware.org/?probe=a0c358b2b3) | Jun 27, 2023 |
| Acer          | Aspire Z1811                | All in one  | [0115283b1c](https://linux-hardware.org/?probe=0115283b1c) | Jun 27, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [a2dbae939a](https://linux-hardware.org/?probe=a2dbae939a) | Jun 27, 2023 |
| Acer          | Extensa 2519                | Notebook    | [1a8a4ee11e](https://linux-hardware.org/?probe=1a8a4ee11e) | Jun 27, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [d7e51d1ddb](https://linux-hardware.org/?probe=d7e51d1ddb) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [5336cd4400](https://linux-hardware.org/?probe=5336cd4400) | Jun 27, 2023 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [1f7adfe250](https://linux-hardware.org/?probe=1f7adfe250) | Jun 27, 2023 |
| Supermicro    | H11SSL-i                    | Server      | [15e179f857](https://linux-hardware.org/?probe=15e179f857) | Jun 27, 2023 |
| Lenovo        | ThinkPad SL410 2842RN9      | Notebook    | [37157ab2f7](https://linux-hardware.org/?probe=37157ab2f7) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [dc32791d25](https://linux-hardware.org/?probe=dc32791d25) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [adf7a275be](https://linux-hardware.org/?probe=adf7a275be) | Jun 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| ASUSTek       | P5P41D                      | Desktop     | [cd85f8d99e](https://linux-hardware.org/?probe=cd85f8d99e) | Jun 27, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [ec28913b4e](https://linux-hardware.org/?probe=ec28913b4e) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b21d5b2e0a](https://linux-hardware.org/?probe=b21d5b2e0a) | Jun 26, 2023 |
| 3Logic Gro... | APM Graviton A15i-K2        | Notebook    | [6371ce9a45](https://linux-hardware.org/?probe=6371ce9a45) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [cde6a94b92](https://linux-hardware.org/?probe=cde6a94b92) | Jun 26, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [7b60ea1445](https://linux-hardware.org/?probe=7b60ea1445) | Jun 26, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [674acd96a8](https://linux-hardware.org/?probe=674acd96a8) | Jun 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [91bb626fa8](https://linux-hardware.org/?probe=91bb626fa8) | Jun 26, 2023 |
| Lenovo        | G780 20138                  | Notebook    | [41cdbe05fe](https://linux-hardware.org/?probe=41cdbe05fe) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [25af22ec30](https://linux-hardware.org/?probe=25af22ec30) | Jun 26, 2023 |
| Pegatron      | 2A99h                       | Desktop     | [86b2544e47](https://linux-hardware.org/?probe=86b2544e47) | Jun 26, 2023 |
| Pegatron      | 2A99h                       | Desktop     | [e3716dffd6](https://linux-hardware.org/?probe=e3716dffd6) | Jun 26, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [929fce049c](https://linux-hardware.org/?probe=929fce049c) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [8e957a70f0](https://linux-hardware.org/?probe=8e957a70f0) | Jun 26, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [2e9bc10188](https://linux-hardware.org/?probe=2e9bc10188) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [bb09ae1f8d](https://linux-hardware.org/?probe=bb09ae1f8d) | Jun 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [9c8513ff31](https://linux-hardware.org/?probe=9c8513ff31) | Jun 25, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [eb68fc38b0](https://linux-hardware.org/?probe=eb68fc38b0) | Jun 25, 2023 |
| HASEE Comp... | PB50_70DFx,DDx              | Notebook    | [3690bcb661](https://linux-hardware.org/?probe=3690bcb661) | Jun 25, 2023 |
| ASUSTek       | P5P41D                      | Desktop     | [aaf9376be5](https://linux-hardware.org/?probe=aaf9376be5) | Jun 25, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [6a01ca36af](https://linux-hardware.org/?probe=6a01ca36af) | Jun 25, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [b5996a0d85](https://linux-hardware.org/?probe=b5996a0d85) | Jun 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [cee2bb11dc](https://linux-hardware.org/?probe=cee2bb11dc) | Jun 25, 2023 |
| ASUSTek       | M51Vr                       | Notebook    | [16404e70f6](https://linux-hardware.org/?probe=16404e70f6) | Jun 25, 2023 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [a5d8941505](https://linux-hardware.org/?probe=a5d8941505) | Jun 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [f40cb826de](https://linux-hardware.org/?probe=f40cb826de) | Jun 25, 2023 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [6398806c80](https://linux-hardware.org/?probe=6398806c80) | Jun 25, 2023 |
| Haier         | i1510SD                     | Notebook    | [f464f11210](https://linux-hardware.org/?probe=f464f11210) | Jun 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [3a045583a7](https://linux-hardware.org/?probe=3a045583a7) | Jun 25, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [3f74c8ae6f](https://linux-hardware.org/?probe=3f74c8ae6f) | Jun 25, 2023 |
| Acer          | Aspire A517-51              | Notebook    | [7f4ad14efb](https://linux-hardware.org/?probe=7f4ad14efb) | Jun 25, 2023 |
| Lenovo        | G580                        | Notebook    | [daa41583f5](https://linux-hardware.org/?probe=daa41583f5) | Jun 25, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [0a3cfef2ce](https://linux-hardware.org/?probe=0a3cfef2ce) | Jun 25, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [02db87eec4](https://linux-hardware.org/?probe=02db87eec4) | Jun 25, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | Desktop     | [9f48465b75](https://linux-hardware.org/?probe=9f48465b75) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [39719594b9](https://linux-hardware.org/?probe=39719594b9) | Jun 24, 2023 |
| eMachines     | E725                        | Notebook    | [91c6056aff](https://linux-hardware.org/?probe=91c6056aff) | Jun 24, 2023 |
| Dell          | Inspiron 1720               | Notebook    | [60c2ef3b92](https://linux-hardware.org/?probe=60c2ef3b92) | Jun 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [a8420bc87d](https://linux-hardware.org/?probe=a8420bc87d) | Jun 24, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [3910260d34](https://linux-hardware.org/?probe=3910260d34) | Jun 24, 2023 |
| Unknown       | 2288H V5                    | Server      | [309e947b4d](https://linux-hardware.org/?probe=309e947b4d) | Jun 24, 2023 |
| ASUSTek       | V241DA                      | All in one  | [ad4578a321](https://linux-hardware.org/?probe=ad4578a321) | Jun 24, 2023 |
| Toshiba       | Satellite U300              | Notebook    | [2abf629721](https://linux-hardware.org/?probe=2abf629721) | Jun 24, 2023 |
| MSI           | 760GM-P21                   | Desktop     | [a6ab8ab499](https://linux-hardware.org/?probe=a6ab8ab499) | Jun 24, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [6da517e892](https://linux-hardware.org/?probe=6da517e892) | Jun 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [e44e80fc33](https://linux-hardware.org/?probe=e44e80fc33) | Jun 23, 2023 |
| Irbis         | NB131                       | Convertible | [9898b376fe](https://linux-hardware.org/?probe=9898b376fe) | Jun 23, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [d4f7477589](https://linux-hardware.org/?probe=d4f7477589) | Jun 23, 2023 |
| Supermicro    | X8DTU                       | Server      | [d84b50b0ed](https://linux-hardware.org/?probe=d84b50b0ed) | Jun 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6bc214e79](https://linux-hardware.org/?probe=b6bc214e79) | Jun 23, 2023 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [9ed9153958](https://linux-hardware.org/?probe=9ed9153958) | Jun 23, 2023 |
| HP            | 530 Notebook PC(KP479AA#... | Notebook    | [0c639de47d](https://linux-hardware.org/?probe=0c639de47d) | Jun 23, 2023 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [d6e01ed04d](https://linux-hardware.org/?probe=d6e01ed04d) | Jun 23, 2023 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [ec3da2f6be](https://linux-hardware.org/?probe=ec3da2f6be) | Jun 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [bb559685e3](https://linux-hardware.org/?probe=bb559685e3) | Jun 23, 2023 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [167de0618f](https://linux-hardware.org/?probe=167de0618f) | Jun 23, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [610b99a65b](https://linux-hardware.org/?probe=610b99a65b) | Jun 23, 2023 |
| ASUSTek       | V241DA                      | All in one  | [c33937f37b](https://linux-hardware.org/?probe=c33937f37b) | Jun 23, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d2e49b65bc](https://linux-hardware.org/?probe=d2e49b65bc) | Jun 23, 2023 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [12fb789329](https://linux-hardware.org/?probe=12fb789329) | Jun 23, 2023 |
| Sony          | VAIO                        | All in one  | [8eda132a31](https://linux-hardware.org/?probe=8eda132a31) | Jun 22, 2023 |
| Lenovo        | Legion Y540-15IRH Laptop... | Notebook    | [3f7008d282](https://linux-hardware.org/?probe=3f7008d282) | Jun 22, 2023 |
| Supermicro    | X8DTU                       | Server      | [d8d978bd73](https://linux-hardware.org/?probe=d8d978bd73) | Jun 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [cac503031c](https://linux-hardware.org/?probe=cac503031c) | Jun 22, 2023 |
| Supermicro    | X9DRW                       | Desktop     | [3b2f007f67](https://linux-hardware.org/?probe=3b2f007f67) | Jun 22, 2023 |
| ASRock        | N68-GS4 FX                  | Desktop     | [c665b54f21](https://linux-hardware.org/?probe=c665b54f21) | Jun 22, 2023 |
| iRU           | J231                        | All in one  | [3002ce753a](https://linux-hardware.org/?probe=3002ce753a) | Jun 22, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [52bcb712ec](https://linux-hardware.org/?probe=52bcb712ec) | Jun 22, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [e8e25f684e](https://linux-hardware.org/?probe=e8e25f684e) | Jun 22, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [db93ddfd03](https://linux-hardware.org/?probe=db93ddfd03) | Jun 22, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [3c27e4a91d](https://linux-hardware.org/?probe=3c27e4a91d) | Jun 22, 2023 |
| HP            | 3048h                       | Desktop     | [e4353bb3d2](https://linux-hardware.org/?probe=e4353bb3d2) | Jun 22, 2023 |
| Supermicro    | X10SRi-F                    | Server      | [3737f3d817](https://linux-hardware.org/?probe=3737f3d817) | Jun 22, 2023 |
| Supermicro    | X10SRi-FB                   | Server      | [b4b0d51700](https://linux-hardware.org/?probe=b4b0d51700) | Jun 22, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [744a4b8498](https://linux-hardware.org/?probe=744a4b8498) | Jun 22, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [f46c865218](https://linux-hardware.org/?probe=f46c865218) | Jun 22, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [5d9a09395c](https://linux-hardware.org/?probe=5d9a09395c) | Jun 22, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [17fb06c810](https://linux-hardware.org/?probe=17fb06c810) | Jun 21, 2023 |
| HP            | ProLiant ML150 G5           | Desktop     | [9106155d17](https://linux-hardware.org/?probe=9106155d17) | Jun 21, 2023 |
| Intel         | D34010WYK H14771-302        | Desktop     | [acda87fcd6](https://linux-hardware.org/?probe=acda87fcd6) | Jun 21, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [dd05dd9f39](https://linux-hardware.org/?probe=dd05dd9f39) | Jun 21, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [a9dc241d86](https://linux-hardware.org/?probe=a9dc241d86) | Jun 21, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [f1fab285fe](https://linux-hardware.org/?probe=f1fab285fe) | Jun 21, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [8cf892e60d](https://linux-hardware.org/?probe=8cf892e60d) | Jun 21, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [03b14ba782](https://linux-hardware.org/?probe=03b14ba782) | Jun 21, 2023 |
| Supermicro    | X9DRW                       | Server      | [6d1f71111e](https://linux-hardware.org/?probe=6d1f71111e) | Jun 21, 2023 |
| Supermicro    | X9DRW                       | Server      | [c2eae10d12](https://linux-hardware.org/?probe=c2eae10d12) | Jun 21, 2023 |
| Supermicro    | X9DRW                       | Server      | [9a25e9e1fb](https://linux-hardware.org/?probe=9a25e9e1fb) | Jun 21, 2023 |
| Supermicro    | X9DRW                       | Server      | [336efb6e27](https://linux-hardware.org/?probe=336efb6e27) | Jun 21, 2023 |
| iRU           | LPGR.469559.010             | All in one  | [de31116bbc](https://linux-hardware.org/?probe=de31116bbc) | Jun 21, 2023 |
| Dell          | 08GXHX A06                  | Server      | [477b8a89fb](https://linux-hardware.org/?probe=477b8a89fb) | Jun 21, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [f4894017da](https://linux-hardware.org/?probe=f4894017da) | Jun 21, 2023 |
| Packard Be... | EasyNote TE69CX             | Notebook    | [d72fa50a56](https://linux-hardware.org/?probe=d72fa50a56) | Jun 21, 2023 |
| HP            | Unknown                     | Notebook    | [f7a4bc57b0](https://linux-hardware.org/?probe=f7a4bc57b0) | Jun 21, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [f92fdecc78](https://linux-hardware.org/?probe=f92fdecc78) | Jun 21, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [03450fe3f0](https://linux-hardware.org/?probe=03450fe3f0) | Jun 21, 2023 |
| Lenovo        | 3123 SDK0J40697 WIN 3305... | All in one  | [415c08bfe4](https://linux-hardware.org/?probe=415c08bfe4) | Jun 21, 2023 |
| Quanta        | TWH                         | Notebook    | [5d04c17be4](https://linux-hardware.org/?probe=5d04c17be4) | Jun 21, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [9f5f612aa7](https://linux-hardware.org/?probe=9f5f612aa7) | Jun 21, 2023 |
| Intel Clie... | LAPBC710                    | Notebook    | [6c97bec6f0](https://linux-hardware.org/?probe=6c97bec6f0) | Jun 21, 2023 |
| Huanan        | B660-D4 V1.0                | Desktop     | [b28fa98f7e](https://linux-hardware.org/?probe=b28fa98f7e) | Jun 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [dc5a63aacc](https://linux-hardware.org/?probe=dc5a63aacc) | Jun 20, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [b34b0bc6e5](https://linux-hardware.org/?probe=b34b0bc6e5) | Jun 20, 2023 |
| Lenovo        | K14 Gen 1 21CSS16E00        | Notebook    | [d60f0418a5](https://linux-hardware.org/?probe=d60f0418a5) | Jun 20, 2023 |
| Dell          | 0WWR83 A05                  | Server      | [f1bf1f7e68](https://linux-hardware.org/?probe=f1bf1f7e68) | Jun 20, 2023 |
| Dell          | 0WWR83 A05                  | Server      | [d1f4b49c8e](https://linux-hardware.org/?probe=d1f4b49c8e) | Jun 20, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [2e2c8b4c64](https://linux-hardware.org/?probe=2e2c8b4c64) | Jun 20, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [07f19ac996](https://linux-hardware.org/?probe=07f19ac996) | Jun 20, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [1dee87098f](https://linux-hardware.org/?probe=1dee87098f) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [1742a525de](https://linux-hardware.org/?probe=1742a525de) | Jun 20, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [9fd3502acf](https://linux-hardware.org/?probe=9fd3502acf) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [cfc9cd338e](https://linux-hardware.org/?probe=cfc9cd338e) | Jun 20, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [8e171dc32b](https://linux-hardware.org/?probe=8e171dc32b) | Jun 20, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [11edb8696f](https://linux-hardware.org/?probe=11edb8696f) | Jun 20, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [2df6a58651](https://linux-hardware.org/?probe=2df6a58651) | Jun 20, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [9b75bc9f7e](https://linux-hardware.org/?probe=9b75bc9f7e) | Jun 20, 2023 |
| Lenovo        | 3130 NOK                    | Mini pc     | [4d78f4e3ca](https://linux-hardware.org/?probe=4d78f4e3ca) | Jun 20, 2023 |
| ASUSTek       | 1011CX                      | Notebook    | [0fa6b0b3dc](https://linux-hardware.org/?probe=0fa6b0b3dc) | Jun 19, 2023 |
| Aquarius      | AQX300M                     | Desktop     | [e0052dddf2](https://linux-hardware.org/?probe=e0052dddf2) | Jun 19, 2023 |
| Aquarius      | AQX300M                     | Desktop     | [c94b718636](https://linux-hardware.org/?probe=c94b718636) | Jun 19, 2023 |
| MSI           | B450M PRO-VDH               | Desktop     | [ed8ee7af2c](https://linux-hardware.org/?probe=ed8ee7af2c) | Jun 19, 2023 |
| Supermicro    | X8DTU                       | Server      | [b5c48fea7a](https://linux-hardware.org/?probe=b5c48fea7a) | Jun 19, 2023 |
| Supermicro    | X8DTU                       | Server      | [9c84dae093](https://linux-hardware.org/?probe=9c84dae093) | Jun 19, 2023 |
| Supermicro    | X8DTU                       | Server      | [7be4e075bb](https://linux-hardware.org/?probe=7be4e075bb) | Jun 19, 2023 |
| Biostar       | H610MH                      | Desktop     | [ba1951d1fa](https://linux-hardware.org/?probe=ba1951d1fa) | Jun 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3eab70981f](https://linux-hardware.org/?probe=3eab70981f) | Jun 19, 2023 |
| Acer          | Extensa 5630                | Notebook    | [b3abbec1ca](https://linux-hardware.org/?probe=b3abbec1ca) | Jun 19, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [4c2f50a608](https://linux-hardware.org/?probe=4c2f50a608) | Jun 19, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [41eb54fba2](https://linux-hardware.org/?probe=41eb54fba2) | Jun 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [2ac629a3ac](https://linux-hardware.org/?probe=2ac629a3ac) | Jun 19, 2023 |
| MSI           | GT70 2OC/2OD                | Notebook    | [adee2af879](https://linux-hardware.org/?probe=adee2af879) | Jun 19, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [0d56b62a99](https://linux-hardware.org/?probe=0d56b62a99) | Jun 19, 2023 |
| ASUSTek       | V221IC                      | All in one  | [c54f07785e](https://linux-hardware.org/?probe=c54f07785e) | Jun 18, 2023 |
| ASUSTek       | X200LA                      | Notebook    | [28ba5d9a3a](https://linux-hardware.org/?probe=28ba5d9a3a) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [924b6e8d54](https://linux-hardware.org/?probe=924b6e8d54) | Jun 18, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0c4198042a](https://linux-hardware.org/?probe=0c4198042a) | Jun 18, 2023 |
| AZW           | U59                         | Desktop     | [6f1191e5e2](https://linux-hardware.org/?probe=6f1191e5e2) | Jun 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [f3cbbb121e](https://linux-hardware.org/?probe=f3cbbb121e) | Jun 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [c867520de1](https://linux-hardware.org/?probe=c867520de1) | Jun 18, 2023 |
| ASUSTek       | X200LA                      | Notebook    | [5aca48b9ca](https://linux-hardware.org/?probe=5aca48b9ca) | Jun 18, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [4be686b049](https://linux-hardware.org/?probe=4be686b049) | Jun 18, 2023 |
| Aquarius      | NS483                       | Notebook    | [dd5daf7f12](https://linux-hardware.org/?probe=dd5daf7f12) | Jun 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [bc9f4e0f09](https://linux-hardware.org/?probe=bc9f4e0f09) | Jun 18, 2023 |
| MSI           | B75A-G43                    | Desktop     | [d2399f16bd](https://linux-hardware.org/?probe=d2399f16bd) | Jun 18, 2023 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [fac7a3587a](https://linux-hardware.org/?probe=fac7a3587a) | Jun 18, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [e4eb86f394](https://linux-hardware.org/?probe=e4eb86f394) | Jun 18, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [c3b7f0c23e](https://linux-hardware.org/?probe=c3b7f0c23e) | Jun 18, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [a161ef52b4](https://linux-hardware.org/?probe=a161ef52b4) | Jun 18, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [6b85997420](https://linux-hardware.org/?probe=6b85997420) | Jun 17, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [bb3ad00508](https://linux-hardware.org/?probe=bb3ad00508) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [ae4661e26f](https://linux-hardware.org/?probe=ae4661e26f) | Jun 17, 2023 |
| MSI           | GX60 1AC                    | Notebook    | [64c48d22a7](https://linux-hardware.org/?probe=64c48d22a7) | Jun 17, 2023 |
| ASUSTek       | M2A-VM                      | Desktop     | [0d1a4c9975](https://linux-hardware.org/?probe=0d1a4c9975) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [2791b66594](https://linux-hardware.org/?probe=2791b66594) | Jun 17, 2023 |
| Lenovo        | H420                        | Desktop     | [c8d4d2fe1b](https://linux-hardware.org/?probe=c8d4d2fe1b) | Jun 17, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [da28ef1e25](https://linux-hardware.org/?probe=da28ef1e25) | Jun 17, 2023 |
| ASRock        | N68-GS4 FX                  | Desktop     | [10376b9b47](https://linux-hardware.org/?probe=10376b9b47) | Jun 17, 2023 |
| HP            | 630                         | Notebook    | [493010a411](https://linux-hardware.org/?probe=493010a411) | Jun 16, 2023 |
| Huanan        | X99-ZD4 V2.0                | Desktop     | [be1f0f151e](https://linux-hardware.org/?probe=be1f0f151e) | Jun 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7e699d65f7](https://linux-hardware.org/?probe=7e699d65f7) | Jun 16, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [e2531ea6c8](https://linux-hardware.org/?probe=e2531ea6c8) | Jun 16, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [6a93f8d5d8](https://linux-hardware.org/?probe=6a93f8d5d8) | Jun 16, 2023 |
| iRU           | AraT                        | Desktop     | [3720460510](https://linux-hardware.org/?probe=3720460510) | Jun 16, 2023 |
| NCR           | Estoril                     | Desktop     | [d29339575f](https://linux-hardware.org/?probe=d29339575f) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [896d66d33f](https://linux-hardware.org/?probe=896d66d33f) | Jun 16, 2023 |
| Dell          | Latitude 3420               | Notebook    | [a0074970bf](https://linux-hardware.org/?probe=a0074970bf) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [b26c331bfc](https://linux-hardware.org/?probe=b26c331bfc) | Jun 16, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | Notebook    | [06ce0448f5](https://linux-hardware.org/?probe=06ce0448f5) | Jun 16, 2023 |
| ASUSTek       | P5QL-CM                     | Desktop     | [13f819c2d6](https://linux-hardware.org/?probe=13f819c2d6) | Jun 16, 2023 |
| WeiBu         | OEM                         | Notebook    | [349908e6d0](https://linux-hardware.org/?probe=349908e6d0) | Jun 16, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [1e46ee1872](https://linux-hardware.org/?probe=1e46ee1872) | Jun 16, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | Desktop     | [9994571651](https://linux-hardware.org/?probe=9994571651) | Jun 15, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [baa9231329](https://linux-hardware.org/?probe=baa9231329) | Jun 15, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [39b295867e](https://linux-hardware.org/?probe=39b295867e) | Jun 15, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [f3a2b5f30f](https://linux-hardware.org/?probe=f3a2b5f30f) | Jun 15, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [02e4016a2f](https://linux-hardware.org/?probe=02e4016a2f) | Jun 15, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [1360220387](https://linux-hardware.org/?probe=1360220387) | Jun 15, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [5ce34d4e94](https://linux-hardware.org/?probe=5ce34d4e94) | Jun 15, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [92482439de](https://linux-hardware.org/?probe=92482439de) | Jun 15, 2023 |
| HP            | ENVY Notebook               | Notebook    | [ee7a2ae915](https://linux-hardware.org/?probe=ee7a2ae915) | Jun 15, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [91787f8dfb](https://linux-hardware.org/?probe=91787f8dfb) | Jun 15, 2023 |
| HP            | ENVY Notebook               | Notebook    | [29828fefe2](https://linux-hardware.org/?probe=29828fefe2) | Jun 15, 2023 |
| Gigabyte      | MX33-BS0-00 00010001        | Server      | [f49cc2ef1e](https://linux-hardware.org/?probe=f49cc2ef1e) | Jun 15, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [5ec4b74af2](https://linux-hardware.org/?probe=5ec4b74af2) | Jun 15, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8649d41483](https://linux-hardware.org/?probe=8649d41483) | Jun 15, 2023 |
| Unknown       | EZpad                       | Tablet      | [c45fd9bb4e](https://linux-hardware.org/?probe=c45fd9bb4e) | Jun 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [49cfb3fdda](https://linux-hardware.org/?probe=49cfb3fdda) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [3a944bbbd5](https://linux-hardware.org/?probe=3a944bbbd5) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [377af23ae8](https://linux-hardware.org/?probe=377af23ae8) | Jun 15, 2023 |
| HP            | 895F                        | All in one  | [1f8ae4f41b](https://linux-hardware.org/?probe=1f8ae4f41b) | Jun 15, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [a708d51992](https://linux-hardware.org/?probe=a708d51992) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [581aba0aa2](https://linux-hardware.org/?probe=581aba0aa2) | Jun 15, 2023 |
| HP            | 895F                        | All in one  | [998f1d4e21](https://linux-hardware.org/?probe=998f1d4e21) | Jun 15, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [ff2a2aeca0](https://linux-hardware.org/?probe=ff2a2aeca0) | Jun 15, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [fe83d43137](https://linux-hardware.org/?probe=fe83d43137) | Jun 15, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [8515730b56](https://linux-hardware.org/?probe=8515730b56) | Jun 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [dcf3ae5611](https://linux-hardware.org/?probe=dcf3ae5611) | Jun 15, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [a796ed0ed7](https://linux-hardware.org/?probe=a796ed0ed7) | Jun 14, 2023 |
| Gigabyte      | P55-USB3                    | Desktop     | [eb497abe93](https://linux-hardware.org/?probe=eb497abe93) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [eba8248dae](https://linux-hardware.org/?probe=eba8248dae) | Jun 14, 2023 |
| Acer          | Aspire S3-391               | Notebook    | [0547c7bf3a](https://linux-hardware.org/?probe=0547c7bf3a) | Jun 14, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [b980e4f162](https://linux-hardware.org/?probe=b980e4f162) | Jun 14, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [dcfab5627c](https://linux-hardware.org/?probe=dcfab5627c) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [6ef7b87ef5](https://linux-hardware.org/?probe=6ef7b87ef5) | Jun 14, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [b972bb9890](https://linux-hardware.org/?probe=b972bb9890) | Jun 14, 2023 |
| MSI           | Katana GF66 12UE            | Notebook    | [49026cdaf3](https://linux-hardware.org/?probe=49026cdaf3) | Jun 14, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [6e0ca764b5](https://linux-hardware.org/?probe=6e0ca764b5) | Jun 14, 2023 |
| Intel         | M50CYP2SBSTD K42381-351     | Server      | [b1b7037d4f](https://linux-hardware.org/?probe=b1b7037d4f) | Jun 14, 2023 |
| Toshiba       | Satellite L30               | Notebook    | [0b240892de](https://linux-hardware.org/?probe=0b240892de) | Jun 14, 2023 |
| Lenovo        | 7X06CTO1WW                  | Server      | [dc3ea6dbb8](https://linux-hardware.org/?probe=dc3ea6dbb8) | Jun 14, 2023 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [bb75cfba76](https://linux-hardware.org/?probe=bb75cfba76) | Jun 14, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [2a3c6cf0ab](https://linux-hardware.org/?probe=2a3c6cf0ab) | Jun 14, 2023 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [d7e7c84a43](https://linux-hardware.org/?probe=d7e7c84a43) | Jun 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [5659761c9c](https://linux-hardware.org/?probe=5659761c9c) | Jun 14, 2023 |
| Supermicro    | H11SSL-i                    | Server      | [1910e1e8de](https://linux-hardware.org/?probe=1910e1e8de) | Jun 14, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [57b3c23d43](https://linux-hardware.org/?probe=57b3c23d43) | Jun 14, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [493866d0e6](https://linux-hardware.org/?probe=493866d0e6) | Jun 14, 2023 |
| Lenovo        | 3135 NOK                    | Mini pc     | [77687d0577](https://linux-hardware.org/?probe=77687d0577) | Jun 14, 2023 |
| Irbis         | NB123                       | Notebook    | [f6dae4c3c4](https://linux-hardware.org/?probe=f6dae4c3c4) | Jun 14, 2023 |
| Supermicro    | X8DT6                       | Server      | [2aed9ad5fa](https://linux-hardware.org/?probe=2aed9ad5fa) | Jun 14, 2023 |
| Unknown       | Beelink GT-King Pro         | Soc         | [766d906989](https://linux-hardware.org/?probe=766d906989) | Jun 13, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [deeef80345](https://linux-hardware.org/?probe=deeef80345) | Jun 13, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [337e4a106e](https://linux-hardware.org/?probe=337e4a106e) | Jun 13, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [0834ca7236](https://linux-hardware.org/?probe=0834ca7236) | Jun 13, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [06c6c417c9](https://linux-hardware.org/?probe=06c6c417c9) | Jun 13, 2023 |
| ECS           | G31T-M9                     | Desktop     | [ba2a738c96](https://linux-hardware.org/?probe=ba2a738c96) | Jun 13, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [456a49b146](https://linux-hardware.org/?probe=456a49b146) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [ee5c72c283](https://linux-hardware.org/?probe=ee5c72c283) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [db48a7b38d](https://linux-hardware.org/?probe=db48a7b38d) | Jun 13, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [680fe3ebbf](https://linux-hardware.org/?probe=680fe3ebbf) | Jun 13, 2023 |
| HUAWEI        | HKF-WXX                     | Notebook    | [ad88913ce4](https://linux-hardware.org/?probe=ad88913ce4) | Jun 13, 2023 |
| Dell          | 500                         | Notebook    | [b220c5553e](https://linux-hardware.org/?probe=b220c5553e) | Jun 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4a879a147e](https://linux-hardware.org/?probe=4a879a147e) | Jun 12, 2023 |
| MSI           | A68HM-P33 V2                | Desktop     | [23097e912c](https://linux-hardware.org/?probe=23097e912c) | Jun 12, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [dcae82c86f](https://linux-hardware.org/?probe=dcae82c86f) | Jun 12, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b5b264d1e8](https://linux-hardware.org/?probe=b5b264d1e8) | Jun 12, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [887dced95a](https://linux-hardware.org/?probe=887dced95a) | Jun 12, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [0dfc0118d2](https://linux-hardware.org/?probe=0dfc0118d2) | Jun 12, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [3e121c01dd](https://linux-hardware.org/?probe=3e121c01dd) | Jun 12, 2023 |
| Acer          | Extensa 5220                | Notebook    | [3f547b15a3](https://linux-hardware.org/?probe=3f547b15a3) | Jun 12, 2023 |
| ASUSTek       | Zenbook UP6502ZD_Q539ZD     | Convertible | [e2cd0602f8](https://linux-hardware.org/?probe=e2cd0602f8) | Jun 12, 2023 |
| ASUSTek       | X551CAP                     | Notebook    | [4076a43510](https://linux-hardware.org/?probe=4076a43510) | Jun 12, 2023 |
| Gigabyte      | P55-USB3                    | Desktop     | [33915148d2](https://linux-hardware.org/?probe=33915148d2) | Jun 11, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [f1614bb08f](https://linux-hardware.org/?probe=f1614bb08f) | Jun 11, 2023 |
| Lenovo        | IdeaPad S10-2 20027         | Notebook    | [cd1619a50d](https://linux-hardware.org/?probe=cd1619a50d) | Jun 11, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [2a5625ca4c](https://linux-hardware.org/?probe=2a5625ca4c) | Jun 11, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [238dbf7ebb](https://linux-hardware.org/?probe=238dbf7ebb) | Jun 11, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [4ecff82426](https://linux-hardware.org/?probe=4ecff82426) | Jun 11, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [334034fb3d](https://linux-hardware.org/?probe=334034fb3d) | Jun 11, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [77cb4dfd02](https://linux-hardware.org/?probe=77cb4dfd02) | Jun 11, 2023 |
| Samsung       | P29/28/26                   | Notebook    | [d7e9b6f2f3](https://linux-hardware.org/?probe=d7e9b6f2f3) | Jun 11, 2023 |
| ASUSTek       | M4N68T V2                   | Desktop     | [4be2f626a3](https://linux-hardware.org/?probe=4be2f626a3) | Jun 11, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [d28c61c2a7](https://linux-hardware.org/?probe=d28c61c2a7) | Jun 11, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0aeb6a400a](https://linux-hardware.org/?probe=0aeb6a400a) | Jun 11, 2023 |
| ASUSTek       | ZenBook UX334FAC_UX334FA    | Notebook    | [ba762c6d80](https://linux-hardware.org/?probe=ba762c6d80) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [8b88702b69](https://linux-hardware.org/?probe=8b88702b69) | Jun 11, 2023 |
| HP            | ProBook 470 G0              | Notebook    | [d3fdf73c3e](https://linux-hardware.org/?probe=d3fdf73c3e) | Jun 10, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [af18d05812](https://linux-hardware.org/?probe=af18d05812) | Jun 10, 2023 |
| Acer          | Aspire A517-51              | Notebook    | [01cfb1c93f](https://linux-hardware.org/?probe=01cfb1c93f) | Jun 10, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [d592b19e9b](https://linux-hardware.org/?probe=d592b19e9b) | Jun 10, 2023 |
| Samsung       | P29/28/26                   | Notebook    | [6040d56961](https://linux-hardware.org/?probe=6040d56961) | Jun 10, 2023 |
| Gigabyte      | 8I865GVMK-775               | Desktop     | [3d90d76b7b](https://linux-hardware.org/?probe=3d90d76b7b) | Jun 10, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [dfba5357ee](https://linux-hardware.org/?probe=dfba5357ee) | Jun 10, 2023 |
| WeiBu         | OEM                         | Notebook    | [49bd40f956](https://linux-hardware.org/?probe=49bd40f956) | Jun 10, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [61c1703e67](https://linux-hardware.org/?probe=61c1703e67) | Jun 10, 2023 |
| Huanan        | X99 F8D V2.2                | Desktop     | [1eeaac2701](https://linux-hardware.org/?probe=1eeaac2701) | Jun 10, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | Desktop     | [88955e82f2](https://linux-hardware.org/?probe=88955e82f2) | Jun 10, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [321ad38786](https://linux-hardware.org/?probe=321ad38786) | Jun 10, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [82adaa06b7](https://linux-hardware.org/?probe=82adaa06b7) | Jun 10, 2023 |
| ASRock        | H610M-ITX/ac                | Desktop     | [80002221f5](https://linux-hardware.org/?probe=80002221f5) | Jun 10, 2023 |
| TYAN Compu... | S7010                       | Server      | [a8b96e89f2](https://linux-hardware.org/?probe=a8b96e89f2) | Jun 10, 2023 |
| MACHENIKE     | F117-7P                     | Notebook    | [78ad896b83](https://linux-hardware.org/?probe=78ad896b83) | Jun 10, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [16b496c21d](https://linux-hardware.org/?probe=16b496c21d) | Jun 10, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [2b4f40f41b](https://linux-hardware.org/?probe=2b4f40f41b) | Jun 09, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [62d37454d3](https://linux-hardware.org/?probe=62d37454d3) | Jun 09, 2023 |
| Dell          | Latitude 5480               | Notebook    | [5b3fb0b4f8](https://linux-hardware.org/?probe=5b3fb0b4f8) | Jun 09, 2023 |
| ECS           | G31T-M9                     | Desktop     | [d8ca98b733](https://linux-hardware.org/?probe=d8ca98b733) | Jun 09, 2023 |
| IBM           | 00J6244 08                  | Server      | [1543d47492](https://linux-hardware.org/?probe=1543d47492) | Jun 09, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [69227c0908](https://linux-hardware.org/?probe=69227c0908) | Jun 09, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [8a9223ce9f](https://linux-hardware.org/?probe=8a9223ce9f) | Jun 09, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [fb883c82bc](https://linux-hardware.org/?probe=fb883c82bc) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b2c39972c2](https://linux-hardware.org/?probe=b2c39972c2) | Jun 09, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [e54b5ce7da](https://linux-hardware.org/?probe=e54b5ce7da) | Jun 09, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [aa0b439e8d](https://linux-hardware.org/?probe=aa0b439e8d) | Jun 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [e246e70bb6](https://linux-hardware.org/?probe=e246e70bb6) | Jun 09, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [c14dcffa32](https://linux-hardware.org/?probe=c14dcffa32) | Jun 08, 2023 |
| Supermicro    | X10DRG-Q                    | Desktop     | [c03c5ea1b9](https://linux-hardware.org/?probe=c03c5ea1b9) | Jun 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [092cd038fc](https://linux-hardware.org/?probe=092cd038fc) | Jun 08, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [20092d99e6](https://linux-hardware.org/?probe=20092d99e6) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [8c9992144c](https://linux-hardware.org/?probe=8c9992144c) | Jun 08, 2023 |
| Dell          | 08GXHX A06                  | Server      | [e4ef5b4ff9](https://linux-hardware.org/?probe=e4ef5b4ff9) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [afa1204a2d](https://linux-hardware.org/?probe=afa1204a2d) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [71e863c1a8](https://linux-hardware.org/?probe=71e863c1a8) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [5033e3aef3](https://linux-hardware.org/?probe=5033e3aef3) | Jun 08, 2023 |
| Supermicro    | X9DRW                       | Server      | [0f8167210a](https://linux-hardware.org/?probe=0f8167210a) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [ab8024c378](https://linux-hardware.org/?probe=ab8024c378) | Jun 08, 2023 |
| Supermicro    | X9DRW                       | Server      | [6845342901](https://linux-hardware.org/?probe=6845342901) | Jun 08, 2023 |
| Supermicro    | X10DRU-i+                   | Server      | [a94d257f7f](https://linux-hardware.org/?probe=a94d257f7f) | Jun 08, 2023 |
| Supermicro    | X8DTL                       | Server      | [b261675cb7](https://linux-hardware.org/?probe=b261675cb7) | Jun 08, 2023 |
| Supermicro    | X8DTU                       | Server      | [605dfce92c](https://linux-hardware.org/?probe=605dfce92c) | Jun 08, 2023 |
| Lenovo        | Unknown                     | Notebook    | [1842b75de0](https://linux-hardware.org/?probe=1842b75de0) | Jun 08, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [dcd4a1ad41](https://linux-hardware.org/?probe=dcd4a1ad41) | Jun 08, 2023 |
| Biostar       | H610MH                      | Desktop     | [a2c82f65b6](https://linux-hardware.org/?probe=a2c82f65b6) | Jun 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [13b0e73872](https://linux-hardware.org/?probe=13b0e73872) | Jun 08, 2023 |
| HJS           | OPSH110D4                   | Desktop     | [bfb0ead991](https://linux-hardware.org/?probe=bfb0ead991) | Jun 08, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [fa22309a62](https://linux-hardware.org/?probe=fa22309a62) | Jun 08, 2023 |
| Biostar       | H610MH                      | Desktop     | [2cd4e157d4](https://linux-hardware.org/?probe=2cd4e157d4) | Jun 08, 2023 |
| INFERIT       | Silver                      | Notebook    | [f6b3fc6762](https://linux-hardware.org/?probe=f6b3fc6762) | Jun 08, 2023 |
| Unknown       | Unknown                     | Tablet      | [072c85039e](https://linux-hardware.org/?probe=072c85039e) | Jun 08, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [86dfe28c7a](https://linux-hardware.org/?probe=86dfe28c7a) | Jun 08, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [87b5fd28c2](https://linux-hardware.org/?probe=87b5fd28c2) | Jun 08, 2023 |
| HP            | 895F                        | All in one  | [355d6e856c](https://linux-hardware.org/?probe=355d6e856c) | Jun 08, 2023 |
| MSI           | GE60 2PL                    | Notebook    | [e1d118e2d2](https://linux-hardware.org/?probe=e1d118e2d2) | Jun 08, 2023 |
| HP            | G62                         | Notebook    | [fb9522ceac](https://linux-hardware.org/?probe=fb9522ceac) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [302bb0628a](https://linux-hardware.org/?probe=302bb0628a) | Jun 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [292625f2da](https://linux-hardware.org/?probe=292625f2da) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | Notebook    | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [102b3706f4](https://linux-hardware.org/?probe=102b3706f4) | Jun 08, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [aaf59358b7](https://linux-hardware.org/?probe=aaf59358b7) | Jun 07, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [45cc99775f](https://linux-hardware.org/?probe=45cc99775f) | Jun 07, 2023 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [5f0e8ab63a](https://linux-hardware.org/?probe=5f0e8ab63a) | Jun 07, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [b4eb1cdd06](https://linux-hardware.org/?probe=b4eb1cdd06) | Jun 07, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [b2c6247a0e](https://linux-hardware.org/?probe=b2c6247a0e) | Jun 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [369f5d3044](https://linux-hardware.org/?probe=369f5d3044) | Jun 07, 2023 |
| Machcreato... | 14                          | Notebook    | [d889b02b13](https://linux-hardware.org/?probe=d889b02b13) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [6d434209eb](https://linux-hardware.org/?probe=6d434209eb) | Jun 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [96256dca48](https://linux-hardware.org/?probe=96256dca48) | Jun 07, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [5ca7ad5fb0](https://linux-hardware.org/?probe=5ca7ad5fb0) | Jun 07, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [4c56663011](https://linux-hardware.org/?probe=4c56663011) | Jun 07, 2023 |
| Kraftway      | KWH510                      | Desktop     | [3a5ccb373b](https://linux-hardware.org/?probe=3a5ccb373b) | Jun 07, 2023 |
| Supermicro    | H12SSW-NT                   | Server      | [5950749033](https://linux-hardware.org/?probe=5950749033) | Jun 07, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [6e2a67c010](https://linux-hardware.org/?probe=6e2a67c010) | Jun 07, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [2e0b21f8d4](https://linux-hardware.org/?probe=2e0b21f8d4) | Jun 07, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [db91b1b71c](https://linux-hardware.org/?probe=db91b1b71c) | Jun 07, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [468f6fe603](https://linux-hardware.org/?probe=468f6fe603) | Jun 06, 2023 |
| Acer          | AOD257                      | Notebook    | [1b75b86659](https://linux-hardware.org/?probe=1b75b86659) | Jun 06, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [d2c05f91c4](https://linux-hardware.org/?probe=d2c05f91c4) | Jun 06, 2023 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [c2f52c637b](https://linux-hardware.org/?probe=c2f52c637b) | Jun 06, 2023 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [d6f404ae63](https://linux-hardware.org/?probe=d6f404ae63) | Jun 06, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [2ff7b71aed](https://linux-hardware.org/?probe=2ff7b71aed) | Jun 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [443550d99f](https://linux-hardware.org/?probe=443550d99f) | Jun 06, 2023 |
| Machcreato... | 14                          | Notebook    | [f0a27a9f97](https://linux-hardware.org/?probe=f0a27a9f97) | Jun 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d75a894e8c](https://linux-hardware.org/?probe=d75a894e8c) | Jun 06, 2023 |
| Intel         | E5 V1.0                     | Desktop     | [077c08c2dc](https://linux-hardware.org/?probe=077c08c2dc) | Jun 06, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [10ecbb2117](https://linux-hardware.org/?probe=10ecbb2117) | Jun 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [be9987ca28](https://linux-hardware.org/?probe=be9987ca28) | Jun 06, 2023 |
| Dell          | G5 5587                     | Notebook    | [909f234c06](https://linux-hardware.org/?probe=909f234c06) | Jun 06, 2023 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [83988ad739](https://linux-hardware.org/?probe=83988ad739) | Jun 06, 2023 |
| Lenovo        | G70-70 80HW                 | Notebook    | [0d46480e90](https://linux-hardware.org/?probe=0d46480e90) | Jun 06, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [60bf4b0442](https://linux-hardware.org/?probe=60bf4b0442) | Jun 05, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [d55fa44834](https://linux-hardware.org/?probe=d55fa44834) | Jun 05, 2023 |
| realme        | CloudProXXXX                | Notebook    | [22cced9066](https://linux-hardware.org/?probe=22cced9066) | Jun 05, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [5a66eed08e](https://linux-hardware.org/?probe=5a66eed08e) | Jun 05, 2023 |
| Unknown       | X79                         | Desktop     | [8c1de0f494](https://linux-hardware.org/?probe=8c1de0f494) | Jun 05, 2023 |
| ECS           | G31T-M9                     | Desktop     | [8bb444bdd6](https://linux-hardware.org/?probe=8bb444bdd6) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Lenovo        | 3123 SDK0J40697 WIN 3305... | All in one  | [b5b1c0dd60](https://linux-hardware.org/?probe=b5b1c0dd60) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [2ec944c5d0](https://linux-hardware.org/?probe=2ec944c5d0) | Jun 05, 2023 |
| Aquarius      | NS585                       | Notebook    | [b3f11e4a53](https://linux-hardware.org/?probe=b3f11e4a53) | Jun 05, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [8896a460d4](https://linux-hardware.org/?probe=8896a460d4) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [d392dff6bb](https://linux-hardware.org/?probe=d392dff6bb) | Jun 05, 2023 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [72702690e5](https://linux-hardware.org/?probe=72702690e5) | Jun 05, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [3ed00534ed](https://linux-hardware.org/?probe=3ed00534ed) | Jun 05, 2023 |
| ECS           | G31T-M9                     | Desktop     | [630360ab38](https://linux-hardware.org/?probe=630360ab38) | Jun 05, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [2e429d02d1](https://linux-hardware.org/?probe=2e429d02d1) | Jun 05, 2023 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [1f07862108](https://linux-hardware.org/?probe=1f07862108) | Jun 05, 2023 |
| HP            | Mini 210-1000               | Notebook    | [96f41af422](https://linux-hardware.org/?probe=96f41af422) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [991c5472ac](https://linux-hardware.org/?probe=991c5472ac) | Jun 05, 2023 |
| ASUSTek       | SABERTOOTH 55i              | Desktop     | [c208cb2024](https://linux-hardware.org/?probe=c208cb2024) | Jun 05, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [ac55415914](https://linux-hardware.org/?probe=ac55415914) | Jun 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d7ae224bea](https://linux-hardware.org/?probe=d7ae224bea) | Jun 04, 2023 |
| Samsung       | N102                        | Notebook    | [c3e402b50d](https://linux-hardware.org/?probe=c3e402b50d) | Jun 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [944c353c44](https://linux-hardware.org/?probe=944c353c44) | Jun 04, 2023 |
| Intel         | S1200RP_SE G62252-408       | Server      | [887b53c07e](https://linux-hardware.org/?probe=887b53c07e) | Jun 04, 2023 |
| Intel         | S1200RP_SE G62252-408       | Server      | [267a861f0d](https://linux-hardware.org/?probe=267a861f0d) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [dfb8881ffe](https://linux-hardware.org/?probe=dfb8881ffe) | Jun 04, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [aa5ed8cbc0](https://linux-hardware.org/?probe=aa5ed8cbc0) | Jun 04, 2023 |
| ASRock        | G31M-GS                     | Desktop     | [558dec9114](https://linux-hardware.org/?probe=558dec9114) | Jun 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [4192000802](https://linux-hardware.org/?probe=4192000802) | Jun 04, 2023 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [a0f9cde008](https://linux-hardware.org/?probe=a0f9cde008) | Jun 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [168fa7f541](https://linux-hardware.org/?probe=168fa7f541) | Jun 04, 2023 |
| Acer          | Spin SP111-32N              | Convertible | [e27deb35b8](https://linux-hardware.org/?probe=e27deb35b8) | Jun 03, 2023 |
| Acer          | Spin SP111-32N              | Convertible | [60f94ec7f1](https://linux-hardware.org/?probe=60f94ec7f1) | Jun 03, 2023 |
| Lenovo        | V560                        | Notebook    | [b2564e07cc](https://linux-hardware.org/?probe=b2564e07cc) | Jun 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [fdfee4fc99](https://linux-hardware.org/?probe=fdfee4fc99) | Jun 03, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [640faccae0](https://linux-hardware.org/?probe=640faccae0) | Jun 03, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [b5d7957b55](https://linux-hardware.org/?probe=b5d7957b55) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [5d6b08920f](https://linux-hardware.org/?probe=5d6b08920f) | Jun 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [cf26028872](https://linux-hardware.org/?probe=cf26028872) | Jun 03, 2023 |
| Acer          | Aspire S3                   | Notebook    | [23c1a32b88](https://linux-hardware.org/?probe=23c1a32b88) | Jun 03, 2023 |
| Samsung       | N102                        | Notebook    | [b21ddf3fea](https://linux-hardware.org/?probe=b21ddf3fea) | Jun 03, 2023 |
| ECS           | G31T-M                      | Desktop     | [55d38b75c7](https://linux-hardware.org/?probe=55d38b75c7) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [5387bcbf7d](https://linux-hardware.org/?probe=5387bcbf7d) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [881df8f45c](https://linux-hardware.org/?probe=881df8f45c) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [0dd3be3300](https://linux-hardware.org/?probe=0dd3be3300) | Jun 03, 2023 |
| ASUSTek       | PRIME A520M-A               | Desktop     | [7dac003c12](https://linux-hardware.org/?probe=7dac003c12) | Jun 03, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [88c3440ff2](https://linux-hardware.org/?probe=88c3440ff2) | Jun 03, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [3160e89723](https://linux-hardware.org/?probe=3160e89723) | Jun 03, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [1c7cc37995](https://linux-hardware.org/?probe=1c7cc37995) | Jun 03, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [088518df2b](https://linux-hardware.org/?probe=088518df2b) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [11e04db670](https://linux-hardware.org/?probe=11e04db670) | Jun 02, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [532dea434a](https://linux-hardware.org/?probe=532dea434a) | Jun 02, 2023 |
| HP            | ENVY Notebook               | Notebook    | [e7f4c63499](https://linux-hardware.org/?probe=e7f4c63499) | Jun 02, 2023 |
| DEXP          | Aquilon C15                 | Notebook    | [763c923576](https://linux-hardware.org/?probe=763c923576) | Jun 02, 2023 |
| IBM           | 00J6244 08                  | Server      | [81b4c3fd14](https://linux-hardware.org/?probe=81b4c3fd14) | Jun 02, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [964377db0b](https://linux-hardware.org/?probe=964377db0b) | Jun 02, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [df3c87a033](https://linux-hardware.org/?probe=df3c87a033) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [853bd25ca5](https://linux-hardware.org/?probe=853bd25ca5) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [3a9fb692f1](https://linux-hardware.org/?probe=3a9fb692f1) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [9b549fe65a](https://linux-hardware.org/?probe=9b549fe65a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [db685837d0](https://linux-hardware.org/?probe=db685837d0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [968b38e0b9](https://linux-hardware.org/?probe=968b38e0b9) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [c9a04d8da0](https://linux-hardware.org/?probe=c9a04d8da0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [238931757a](https://linux-hardware.org/?probe=238931757a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [e190e991a6](https://linux-hardware.org/?probe=e190e991a6) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0816e77499](https://linux-hardware.org/?probe=0816e77499) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [ff143ac918](https://linux-hardware.org/?probe=ff143ac918) | Jun 02, 2023 |
| Aquarius      | NS585                       | Notebook    | [6f93385917](https://linux-hardware.org/?probe=6f93385917) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| Zvezda        | Arctur test_serv            | Server      | [f728993499](https://linux-hardware.org/?probe=f728993499) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [05a99cf128](https://linux-hardware.org/?probe=05a99cf128) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| Aquarius      | NS585                       | Notebook    | [091267ec3a](https://linux-hardware.org/?probe=091267ec3a) | Jun 02, 2023 |
| Aquarius      | NS585                       | Notebook    | [7534819f94](https://linux-hardware.org/?probe=7534819f94) | Jun 02, 2023 |
| Lenovo        | S40-70 80GQ                 | Notebook    | [9a3fbc7388](https://linux-hardware.org/?probe=9a3fbc7388) | Jun 02, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [3feb5e9cb5](https://linux-hardware.org/?probe=3feb5e9cb5) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [81ec1cc134](https://linux-hardware.org/?probe=81ec1cc134) | Jun 01, 2023 |
| ASRock        | Z77M                        | Desktop     | [eae1adee21](https://linux-hardware.org/?probe=eae1adee21) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f3b666f725](https://linux-hardware.org/?probe=f3b666f725) | Jun 01, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [308b943182](https://linux-hardware.org/?probe=308b943182) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1cf7ec0aa5](https://linux-hardware.org/?probe=1cf7ec0aa5) | Jun 01, 2023 |
| ASRock        | J3455M                      | Desktop     | [ca1db2cfb9](https://linux-hardware.org/?probe=ca1db2cfb9) | Jun 01, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [38a0e17081](https://linux-hardware.org/?probe=38a0e17081) | Jun 01, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [09b2200a7f](https://linux-hardware.org/?probe=09b2200a7f) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [7f9d81bd57](https://linux-hardware.org/?probe=7f9d81bd57) | Jun 01, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [1708ebae47](https://linux-hardware.org/?probe=1708ebae47) | Jun 01, 2023 |
| Aquarius      | NS585                       | Notebook    | [ffa7425b95](https://linux-hardware.org/?probe=ffa7425b95) | Jun 01, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [b92d2128ad](https://linux-hardware.org/?probe=b92d2128ad) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Aquarius      | NS585                       | Notebook    | [fafcbbe90e](https://linux-hardware.org/?probe=fafcbbe90e) | Jun 01, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [1bd92e67d7](https://linux-hardware.org/?probe=1bd92e67d7) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9afffc17a1](https://linux-hardware.org/?probe=9afffc17a1) | Jun 01, 2023 |
| Samsung       | 750QFG                      | Convertible | [7720d51647](https://linux-hardware.org/?probe=7720d51647) | Jun 01, 2023 |
| Dell          | Latitude 5490               | Notebook    | [34dde30b90](https://linux-hardware.org/?probe=34dde30b90) | Jun 01, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [31e0f624be](https://linux-hardware.org/?probe=31e0f624be) | Jun 01, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [d75bfc397f](https://linux-hardware.org/?probe=d75bfc397f) | Jun 01, 2023 |
| Gigabyte      | EP45T-DS3                   | Desktop     | [0dd3baa28d](https://linux-hardware.org/?probe=0dd3baa28d) | Jun 01, 2023 |
| Timi          | TM1801                      | Notebook    | [aa1db210df](https://linux-hardware.org/?probe=aa1db210df) | Jun 01, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [d94ba8fb27](https://linux-hardware.org/?probe=d94ba8fb27) | Jun 01, 2023 |
| Lenovo        | K14 Gen 1 21CSS16E00        | Notebook    | [9c95ad4263](https://linux-hardware.org/?probe=9c95ad4263) | May 31, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [ba0b4e2430](https://linux-hardware.org/?probe=ba0b4e2430) | May 31, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [3058ac9018](https://linux-hardware.org/?probe=3058ac9018) | May 31, 2023 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [6a2cd16e95](https://linux-hardware.org/?probe=6a2cd16e95) | May 31, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [483bf9a882](https://linux-hardware.org/?probe=483bf9a882) | May 31, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [717c7884c8](https://linux-hardware.org/?probe=717c7884c8) | May 31, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [d68236f41d](https://linux-hardware.org/?probe=d68236f41d) | May 31, 2023 |
| ASRock        | A320D4-P1                   | Desktop     | [195945844b](https://linux-hardware.org/?probe=195945844b) | May 31, 2023 |
| ECS           | G31T-M9                     | Desktop     | [f227323587](https://linux-hardware.org/?probe=f227323587) | May 31, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6bcba3e54d](https://linux-hardware.org/?probe=6bcba3e54d) | May 31, 2023 |
| AMD           | AOPW-PLUS                   | Server      | [9e0f4d41e2](https://linux-hardware.org/?probe=9e0f4d41e2) | May 31, 2023 |
| Dell          | Latitude 5411               | Notebook    | [8583aa2091](https://linux-hardware.org/?probe=8583aa2091) | May 31, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [384ebf87a3](https://linux-hardware.org/?probe=384ebf87a3) | May 31, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [ebc3d97429](https://linux-hardware.org/?probe=ebc3d97429) | May 30, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [97382e45f8](https://linux-hardware.org/?probe=97382e45f8) | May 30, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [3222c41173](https://linux-hardware.org/?probe=3222c41173) | May 30, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d20ebd68c0](https://linux-hardware.org/?probe=d20ebd68c0) | May 30, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [85a2504037](https://linux-hardware.org/?probe=85a2504037) | May 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4833d37ec3](https://linux-hardware.org/?probe=4833d37ec3) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [c56271ea6a](https://linux-hardware.org/?probe=c56271ea6a) | May 30, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [ca4e5a8f82](https://linux-hardware.org/?probe=ca4e5a8f82) | May 30, 2023 |
| Biostar       | H610MH                      | Desktop     | [708df29fd6](https://linux-hardware.org/?probe=708df29fd6) | May 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [7ab8c72481](https://linux-hardware.org/?probe=7ab8c72481) | May 30, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [c23ef58095](https://linux-hardware.org/?probe=c23ef58095) | May 30, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [676d83919f](https://linux-hardware.org/?probe=676d83919f) | May 30, 2023 |
| IBM           | 00J6244 08                  | Server      | [cee2891b60](https://linux-hardware.org/?probe=cee2891b60) | May 30, 2023 |
| ICL           | RAYbook Si1407              | Notebook    | [5956bb96ff](https://linux-hardware.org/?probe=5956bb96ff) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a0ffb7fd40](https://linux-hardware.org/?probe=a0ffb7fd40) | May 30, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [446d026ac1](https://linux-hardware.org/?probe=446d026ac1) | May 30, 2023 |
| Supermicro    | X9DR3-F                     | Server      | [afcfc0fdf3](https://linux-hardware.org/?probe=afcfc0fdf3) | May 30, 2023 |
| Gigabyte      | B560M D3H                   | Desktop     | [8579e0281a](https://linux-hardware.org/?probe=8579e0281a) | May 30, 2023 |
| MSI           | MS-ACD31                    | All in one  | [d958890b05](https://linux-hardware.org/?probe=d958890b05) | May 30, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [3722c76b10](https://linux-hardware.org/?probe=3722c76b10) | May 30, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [4843789a62](https://linux-hardware.org/?probe=4843789a62) | May 30, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [9da720226e](https://linux-hardware.org/?probe=9da720226e) | May 30, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [611b47056d](https://linux-hardware.org/?probe=611b47056d) | May 30, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [dacfbfd038](https://linux-hardware.org/?probe=dacfbfd038) | May 30, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8e0413af72](https://linux-hardware.org/?probe=8e0413af72) | May 30, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [c0e9edd453](https://linux-hardware.org/?probe=c0e9edd453) | May 30, 2023 |
| MSI           | GE60 2PC                    | Notebook    | [48c124853f](https://linux-hardware.org/?probe=48c124853f) | May 30, 2023 |
| ASUSTek       | X550WA                      | Notebook    | [864236b0c9](https://linux-hardware.org/?probe=864236b0c9) | May 29, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [2ef322a58d](https://linux-hardware.org/?probe=2ef322a58d) | May 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [3933dfe4f0](https://linux-hardware.org/?probe=3933dfe4f0) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [80c2e03e4e](https://linux-hardware.org/?probe=80c2e03e4e) | May 29, 2023 |
| Huanan        | X99 F8D V2.2                | Desktop     | [b4e407cdb0](https://linux-hardware.org/?probe=b4e407cdb0) | May 29, 2023 |
| ECS           | G31T-M9                     | Desktop     | [8f4cd5b132](https://linux-hardware.org/?probe=8f4cd5b132) | May 29, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [a786eb985d](https://linux-hardware.org/?probe=a786eb985d) | May 29, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [a1f825f4e5](https://linux-hardware.org/?probe=a1f825f4e5) | May 29, 2023 |
| Intel         | NUC7JYB J67970-403          | Mini pc     | [8af314920e](https://linux-hardware.org/?probe=8af314920e) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ffe8469edc](https://linux-hardware.org/?probe=ffe8469edc) | May 29, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [8f51b4170e](https://linux-hardware.org/?probe=8f51b4170e) | May 29, 2023 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [9b21df1d8e](https://linux-hardware.org/?probe=9b21df1d8e) | May 29, 2023 |
| Supermicro    | H12SSW-NT                   | Server      | [f8a6482d0e](https://linux-hardware.org/?probe=f8a6482d0e) | May 29, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [35d14ed328](https://linux-hardware.org/?probe=35d14ed328) | May 29, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [36a3563566](https://linux-hardware.org/?probe=36a3563566) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [e9f274ad89](https://linux-hardware.org/?probe=e9f274ad89) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [62a5559050](https://linux-hardware.org/?probe=62a5559050) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [a9c147d701](https://linux-hardware.org/?probe=a9c147d701) | May 29, 2023 |
| ICL-KME CS    | RAYbook                     | Notebook    | [9e976ffc1a](https://linux-hardware.org/?probe=9e976ffc1a) | May 29, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [4b53ed4ede](https://linux-hardware.org/?probe=4b53ed4ede) | May 29, 2023 |
| MSI           | 770-C45                     | Desktop     | [dae0d25fcc](https://linux-hardware.org/?probe=dae0d25fcc) | May 29, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [b7be0bf5ad](https://linux-hardware.org/?probe=b7be0bf5ad) | May 29, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [e57b9850f8](https://linux-hardware.org/?probe=e57b9850f8) | May 28, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [d3afe375cf](https://linux-hardware.org/?probe=d3afe375cf) | May 28, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [0c7bfc7977](https://linux-hardware.org/?probe=0c7bfc7977) | May 28, 2023 |
| iRU           | J231                        | All in one  | [fdc7f7219d](https://linux-hardware.org/?probe=fdc7f7219d) | May 28, 2023 |
| Unknown       | X79                         | Desktop     | [cfda28fe65](https://linux-hardware.org/?probe=cfda28fe65) | May 28, 2023 |
| ASUSTek       | PN52                        | Mini pc     | [6f81612c62](https://linux-hardware.org/?probe=6f81612c62) | May 28, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [fa3f4694ba](https://linux-hardware.org/?probe=fa3f4694ba) | May 28, 2023 |
| ASUSTek       | PN52                        | Mini pc     | [444239084c](https://linux-hardware.org/?probe=444239084c) | May 28, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [849ff29f29](https://linux-hardware.org/?probe=849ff29f29) | May 28, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [45a2eb8526](https://linux-hardware.org/?probe=45a2eb8526) | May 28, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [773f0d5242](https://linux-hardware.org/?probe=773f0d5242) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [86876e9715](https://linux-hardware.org/?probe=86876e9715) | May 28, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | Notebook    | [8283b1247f](https://linux-hardware.org/?probe=8283b1247f) | May 28, 2023 |
| LTD Delovo... | EVE 14 C414                 | Notebook    | [d52f6c1303](https://linux-hardware.org/?probe=d52f6c1303) | May 28, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [39f6ad44fe](https://linux-hardware.org/?probe=39f6ad44fe) | May 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [b294c91e3a](https://linux-hardware.org/?probe=b294c91e3a) | May 28, 2023 |
| Lenovo        | IdeaPad Z570 1024CPU        | Notebook    | [eb1c70f7af](https://linux-hardware.org/?probe=eb1c70f7af) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | Notebook    | [fb534d212e](https://linux-hardware.org/?probe=fb534d212e) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | Notebook    | [6b753016ff](https://linux-hardware.org/?probe=6b753016ff) | May 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [447bbfbd40](https://linux-hardware.org/?probe=447bbfbd40) | May 27, 2023 |
| ASUSTek       | ROG Strix G634JY_G634JY     | Notebook    | [026cf06ce5](https://linux-hardware.org/?probe=026cf06ce5) | May 27, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [c6309fc374](https://linux-hardware.org/?probe=c6309fc374) | May 27, 2023 |
| AZW           | MINI S                      | Desktop     | [55c17a6700](https://linux-hardware.org/?probe=55c17a6700) | May 27, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [1f8b536f4f](https://linux-hardware.org/?probe=1f8b536f4f) | May 27, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [bfc89878ce](https://linux-hardware.org/?probe=bfc89878ce) | May 27, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [e43931a1af](https://linux-hardware.org/?probe=e43931a1af) | May 27, 2023 |
| Huanan        | X79 249PC V2.2              | Desktop     | [0723379042](https://linux-hardware.org/?probe=0723379042) | May 27, 2023 |
| Huanan        | X79 249PC V2.2              | Desktop     | [ef1a056412](https://linux-hardware.org/?probe=ef1a056412) | May 27, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [7fce8e04b2](https://linux-hardware.org/?probe=7fce8e04b2) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [bcdfc5a2bf](https://linux-hardware.org/?probe=bcdfc5a2bf) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [68cb8bdf49](https://linux-hardware.org/?probe=68cb8bdf49) | May 27, 2023 |
| Aquarius      | NS585                       | Notebook    | [a87c8d46b6](https://linux-hardware.org/?probe=a87c8d46b6) | May 27, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [ff2e86c530](https://linux-hardware.org/?probe=ff2e86c530) | May 27, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [f1bfd18361](https://linux-hardware.org/?probe=f1bfd18361) | May 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [985e20f0ad](https://linux-hardware.org/?probe=985e20f0ad) | May 27, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [8fdbd504af](https://linux-hardware.org/?probe=8fdbd504af) | May 27, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [95231653d0](https://linux-hardware.org/?probe=95231653d0) | May 26, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [4662e37743](https://linux-hardware.org/?probe=4662e37743) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [92836191e9](https://linux-hardware.org/?probe=92836191e9) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [0d449702e3](https://linux-hardware.org/?probe=0d449702e3) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [a5fbe0c1ba](https://linux-hardware.org/?probe=a5fbe0c1ba) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [f9fd99a8b7](https://linux-hardware.org/?probe=f9fd99a8b7) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [6c87853f8c](https://linux-hardware.org/?probe=6c87853f8c) | May 26, 2023 |
| Samsung       | N130                        | Notebook    | [bd37239d10](https://linux-hardware.org/?probe=bd37239d10) | May 26, 2023 |
| Timi          | TM1701                      | Notebook    | [94105aa58f](https://linux-hardware.org/?probe=94105aa58f) | May 26, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [138348e6eb](https://linux-hardware.org/?probe=138348e6eb) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [388eed2f8e](https://linux-hardware.org/?probe=388eed2f8e) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [1bc02afebc](https://linux-hardware.org/?probe=1bc02afebc) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [485617123a](https://linux-hardware.org/?probe=485617123a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [d1933e40f4](https://linux-hardware.org/?probe=d1933e40f4) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [db84f366d0](https://linux-hardware.org/?probe=db84f366d0) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [4d7f19ec5b](https://linux-hardware.org/?probe=4d7f19ec5b) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [adb7acad13](https://linux-hardware.org/?probe=adb7acad13) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [897503110a](https://linux-hardware.org/?probe=897503110a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [7ddbfedd32](https://linux-hardware.org/?probe=7ddbfedd32) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [96202d100a](https://linux-hardware.org/?probe=96202d100a) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [faa830a26c](https://linux-hardware.org/?probe=faa830a26c) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [03d0e0d8d7](https://linux-hardware.org/?probe=03d0e0d8d7) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f76e433d68](https://linux-hardware.org/?probe=f76e433d68) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [610a5f2bb3](https://linux-hardware.org/?probe=610a5f2bb3) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f10a5bd0f9](https://linux-hardware.org/?probe=f10a5bd0f9) | May 26, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [4945ea3fba](https://linux-hardware.org/?probe=4945ea3fba) | May 26, 2023 |
| eMachines     | eME644G                     | Notebook    | [cde4d7b461](https://linux-hardware.org/?probe=cde4d7b461) | May 26, 2023 |
| eMachines     | E725                        | Notebook    | [a4be8012a8](https://linux-hardware.org/?probe=a4be8012a8) | May 26, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [d3ac4866d3](https://linux-hardware.org/?probe=d3ac4866d3) | May 26, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [67b6a5e731](https://linux-hardware.org/?probe=67b6a5e731) | May 26, 2023 |
| ASUSTek       | G50VT                       | Notebook    | [6e4a2588b1](https://linux-hardware.org/?probe=6e4a2588b1) | May 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [7a40f97a17](https://linux-hardware.org/?probe=7a40f97a17) | May 26, 2023 |
| Acer          | Aspire V3-551               | Notebook    | [9d609ccd4a](https://linux-hardware.org/?probe=9d609ccd4a) | May 26, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [925318e521](https://linux-hardware.org/?probe=925318e521) | May 26, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [cd4b2a2c6e](https://linux-hardware.org/?probe=cd4b2a2c6e) | May 26, 2023 |
| HP            | 83F0                        | Desktop     | [77cfad8631](https://linux-hardware.org/?probe=77cfad8631) | May 26, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [9683a94030](https://linux-hardware.org/?probe=9683a94030) | May 26, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [e34e6ab643](https://linux-hardware.org/?probe=e34e6ab643) | May 26, 2023 |
| Intel Clie... | LAPBC710                    | Notebook    | [7ed6d7079c](https://linux-hardware.org/?probe=7ed6d7079c) | May 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [b63a3cbd7b](https://linux-hardware.org/?probe=b63a3cbd7b) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [3db7516231](https://linux-hardware.org/?probe=3db7516231) | May 25, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [f9111f71f7](https://linux-hardware.org/?probe=f9111f71f7) | May 25, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [7b19816353](https://linux-hardware.org/?probe=7b19816353) | May 25, 2023 |
| HP            | ProBook 4535s               | Notebook    | [bf141ba124](https://linux-hardware.org/?probe=bf141ba124) | May 25, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [b9af05a16f](https://linux-hardware.org/?probe=b9af05a16f) | May 25, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [387793dfb2](https://linux-hardware.org/?probe=387793dfb2) | May 25, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [142c9c4384](https://linux-hardware.org/?probe=142c9c4384) | May 25, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [5311e723a0](https://linux-hardware.org/?probe=5311e723a0) | May 25, 2023 |
| Gigabyte      | E350N WIN8                  | Desktop     | [3d858aac61](https://linux-hardware.org/?probe=3d858aac61) | May 25, 2023 |
| eMachines     | eME644G                     | Notebook    | [bc740da95e](https://linux-hardware.org/?probe=bc740da95e) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [7b4b86c1ea](https://linux-hardware.org/?probe=7b4b86c1ea) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [15c2f741bf](https://linux-hardware.org/?probe=15c2f741bf) | May 25, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [4670302b3a](https://linux-hardware.org/?probe=4670302b3a) | May 25, 2023 |
| Aquarius      | NS685U R11                  | Notebook    | [8e0050a63d](https://linux-hardware.org/?probe=8e0050a63d) | May 25, 2023 |
| Aquarius      | NS685U R11                  | Notebook    | [17191f57d3](https://linux-hardware.org/?probe=17191f57d3) | May 25, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [41f9a8d4b1](https://linux-hardware.org/?probe=41f9a8d4b1) | May 25, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [51dbf3c463](https://linux-hardware.org/?probe=51dbf3c463) | May 25, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [a5f7973a09](https://linux-hardware.org/?probe=a5f7973a09) | May 25, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [99bcbfbb2a](https://linux-hardware.org/?probe=99bcbfbb2a) | May 25, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a98cdfee26](https://linux-hardware.org/?probe=a98cdfee26) | May 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [82a0d45251](https://linux-hardware.org/?probe=82a0d45251) | May 25, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [00a5e48ef4](https://linux-hardware.org/?probe=00a5e48ef4) | May 25, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [589639a63f](https://linux-hardware.org/?probe=589639a63f) | May 25, 2023 |
| Timi          | TM1701                      | Notebook    | [c883337466](https://linux-hardware.org/?probe=c883337466) | May 24, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [c6cc5e2a20](https://linux-hardware.org/?probe=c6cc5e2a20) | May 24, 2023 |
| Gigabyte      | GA-E240N                    | Desktop     | [f538fa3add](https://linux-hardware.org/?probe=f538fa3add) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [fb5edbbd6b](https://linux-hardware.org/?probe=fb5edbbd6b) | May 24, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [fe046d6420](https://linux-hardware.org/?probe=fe046d6420) | May 24, 2023 |
| Gigabyte      | GA-770T-USB3                | Desktop     | [60e294f0e6](https://linux-hardware.org/?probe=60e294f0e6) | May 24, 2023 |
| Acer          | Extensa 5630                | Notebook    | [00e8bb4d6a](https://linux-hardware.org/?probe=00e8bb4d6a) | May 24, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [9486b7ca4f](https://linux-hardware.org/?probe=9486b7ca4f) | May 24, 2023 |
| Samsung       | R710                        | Notebook    | [a2c199b3cd](https://linux-hardware.org/?probe=a2c199b3cd) | May 24, 2023 |
| Packard Be... | DOT S                       | Notebook    | [a49bbc7aa2](https://linux-hardware.org/?probe=a49bbc7aa2) | May 24, 2023 |
| ASUSTek       | E35M1-M                     | Desktop     | [c62d813dd9](https://linux-hardware.org/?probe=c62d813dd9) | May 24, 2023 |
| DEXP          | Aquilon C14                 | Notebook    | [357a7caaf8](https://linux-hardware.org/?probe=357a7caaf8) | May 24, 2023 |
| DEXP          | Aquilon C14                 | Notebook    | [cd3dc35687](https://linux-hardware.org/?probe=cd3dc35687) | May 24, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [3898315bde](https://linux-hardware.org/?probe=3898315bde) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [a03284052b](https://linux-hardware.org/?probe=a03284052b) | May 24, 2023 |
| ASUSTek       | UL30A                       | Notebook    | [d7ab3b0ed3](https://linux-hardware.org/?probe=d7ab3b0ed3) | May 24, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [1e1fb2110f](https://linux-hardware.org/?probe=1e1fb2110f) | May 24, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [0854b7f24a](https://linux-hardware.org/?probe=0854b7f24a) | May 24, 2023 |
| Gigabyte      | 8I945GZME-RH                | Desktop     | [3b4c63eddb](https://linux-hardware.org/?probe=3b4c63eddb) | May 24, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [dd1104fc5a](https://linux-hardware.org/?probe=dd1104fc5a) | May 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [192358f396](https://linux-hardware.org/?probe=192358f396) | May 23, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [e147bb9d5e](https://linux-hardware.org/?probe=e147bb9d5e) | May 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [6680332a54](https://linux-hardware.org/?probe=6680332a54) | May 23, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [17f5577d63](https://linux-hardware.org/?probe=17f5577d63) | May 23, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [49bd7863b7](https://linux-hardware.org/?probe=49bd7863b7) | May 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4f9c9295d4](https://linux-hardware.org/?probe=4f9c9295d4) | May 23, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [39ff25bc94](https://linux-hardware.org/?probe=39ff25bc94) | May 23, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [d06b734926](https://linux-hardware.org/?probe=d06b734926) | May 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [3ee24557f7](https://linux-hardware.org/?probe=3ee24557f7) | May 23, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [95301f4dea](https://linux-hardware.org/?probe=95301f4dea) | May 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [a410c18f8c](https://linux-hardware.org/?probe=a410c18f8c) | May 23, 2023 |
| MSI           | MAG B560M BAZOOKA           | Desktop     | [712c1eecdb](https://linux-hardware.org/?probe=712c1eecdb) | May 23, 2023 |
| ASUSTek       | ET2321I                     | Notebook    | [829fe9b078](https://linux-hardware.org/?probe=829fe9b078) | May 23, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [4d067a1511](https://linux-hardware.org/?probe=4d067a1511) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [374ccaecd9](https://linux-hardware.org/?probe=374ccaecd9) | May 22, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [702a597b36](https://linux-hardware.org/?probe=702a597b36) | May 22, 2023 |
| MSI           | MS-7A66                     | Desktop     | [9be9117e62](https://linux-hardware.org/?probe=9be9117e62) | May 22, 2023 |
| MSI           | 770-C45                     | Desktop     | [98672fa54c](https://linux-hardware.org/?probe=98672fa54c) | May 22, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [6ca579ee78](https://linux-hardware.org/?probe=6ca579ee78) | May 22, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [91ad90fd67](https://linux-hardware.org/?probe=91ad90fd67) | May 22, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [00b64b43b5](https://linux-hardware.org/?probe=00b64b43b5) | May 22, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [91aa0c376a](https://linux-hardware.org/?probe=91aa0c376a) | May 22, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [98f94bccb6](https://linux-hardware.org/?probe=98f94bccb6) | May 22, 2023 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [71fc64d684](https://linux-hardware.org/?probe=71fc64d684) | May 22, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [3ad250d762](https://linux-hardware.org/?probe=3ad250d762) | May 22, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [5dd26df23e](https://linux-hardware.org/?probe=5dd26df23e) | May 22, 2023 |
| ASUSTek       | Z97-C                       | Desktop     | [e308a2d977](https://linux-hardware.org/?probe=e308a2d977) | May 22, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [179e48239b](https://linux-hardware.org/?probe=179e48239b) | May 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [0a03a5a40a](https://linux-hardware.org/?probe=0a03a5a40a) | May 22, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [8226c82b49](https://linux-hardware.org/?probe=8226c82b49) | May 21, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [6a8e6201be](https://linux-hardware.org/?probe=6a8e6201be) | May 21, 2023 |
| Lenovo        | Unknown                     | Notebook    | [1288108e10](https://linux-hardware.org/?probe=1288108e10) | May 21, 2023 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [f573a9cfae](https://linux-hardware.org/?probe=f573a9cfae) | May 21, 2023 |
| Unknown       | X133                        | Notebook    | [52cd0be8f5](https://linux-hardware.org/?probe=52cd0be8f5) | May 21, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [1e231f6e75](https://linux-hardware.org/?probe=1e231f6e75) | May 21, 2023 |
| Unknown       | Unknown                     | Soc         | [d40c7d6729](https://linux-hardware.org/?probe=d40c7d6729) | May 21, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [7f15c1b9e3](https://linux-hardware.org/?probe=7f15c1b9e3) | May 21, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [bc16fc021e](https://linux-hardware.org/?probe=bc16fc021e) | May 21, 2023 |
| ASRock        | Q1900M                      | Desktop     | [0290a65c70](https://linux-hardware.org/?probe=0290a65c70) | May 21, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [279141fa2a](https://linux-hardware.org/?probe=279141fa2a) | May 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [47ab72fc6c](https://linux-hardware.org/?probe=47ab72fc6c) | May 20, 2023 |
| HASEE Comp... | V1x0PNPx                    | Notebook    | [ce5f16dcfe](https://linux-hardware.org/?probe=ce5f16dcfe) | May 20, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [166b73ef05](https://linux-hardware.org/?probe=166b73ef05) | May 20, 2023 |
| GX55          | Standard                    | Mini pc     | [c30cac8dda](https://linux-hardware.org/?probe=c30cac8dda) | May 20, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [ebe8b24fd2](https://linux-hardware.org/?probe=ebe8b24fd2) | May 20, 2023 |
| Lenovo        | 3714 NOK                    | Desktop     | [0da1ff78c6](https://linux-hardware.org/?probe=0da1ff78c6) | May 20, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [919ed7f9e1](https://linux-hardware.org/?probe=919ed7f9e1) | May 20, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [d2ddb09cc1](https://linux-hardware.org/?probe=d2ddb09cc1) | May 20, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c43eef4a3a](https://linux-hardware.org/?probe=c43eef4a3a) | May 20, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [927345991a](https://linux-hardware.org/?probe=927345991a) | May 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ac3d3ea87c](https://linux-hardware.org/?probe=ac3d3ea87c) | May 19, 2023 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [ab569c8de9](https://linux-hardware.org/?probe=ab569c8de9) | May 19, 2023 |
| Supermicro    | X5DPA                       | Desktop     | [0823a08bd8](https://linux-hardware.org/?probe=0823a08bd8) | May 19, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [a51baad28a](https://linux-hardware.org/?probe=a51baad28a) | May 19, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2402CBA... | Notebook    | [13d783ec86](https://linux-hardware.org/?probe=13d783ec86) | May 19, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [09cc939f04](https://linux-hardware.org/?probe=09cc939f04) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [7d600a9c24](https://linux-hardware.org/?probe=7d600a9c24) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [0f034f50a0](https://linux-hardware.org/?probe=0f034f50a0) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [cdb86f0326](https://linux-hardware.org/?probe=cdb86f0326) | May 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [39fa0ce7e9](https://linux-hardware.org/?probe=39fa0ce7e9) | May 19, 2023 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [e1901ac344](https://linux-hardware.org/?probe=e1901ac344) | May 19, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [8c80042f1e](https://linux-hardware.org/?probe=8c80042f1e) | May 19, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [d5ffcf1bec](https://linux-hardware.org/?probe=d5ffcf1bec) | May 19, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [12da248164](https://linux-hardware.org/?probe=12da248164) | May 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [d51c5680e8](https://linux-hardware.org/?probe=d51c5680e8) | May 19, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [52dbfc4c5a](https://linux-hardware.org/?probe=52dbfc4c5a) | May 19, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [e7949de034](https://linux-hardware.org/?probe=e7949de034) | May 19, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c1f8fc5eed](https://linux-hardware.org/?probe=c1f8fc5eed) | May 19, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [7f35aa414f](https://linux-hardware.org/?probe=7f35aa414f) | May 18, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [08df098150](https://linux-hardware.org/?probe=08df098150) | May 18, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [763654d8fc](https://linux-hardware.org/?probe=763654d8fc) | May 18, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [0517273b27](https://linux-hardware.org/?probe=0517273b27) | May 18, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [137d8d57ee](https://linux-hardware.org/?probe=137d8d57ee) | May 18, 2023 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [276b10e762](https://linux-hardware.org/?probe=276b10e762) | May 18, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [286c28d090](https://linux-hardware.org/?probe=286c28d090) | May 18, 2023 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a6bcd864f3](https://linux-hardware.org/?probe=a6bcd864f3) | May 18, 2023 |
| Aquarius      | NS585                       | Notebook    | [dc2b351b40](https://linux-hardware.org/?probe=dc2b351b40) | May 18, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [6c9d197b74](https://linux-hardware.org/?probe=6c9d197b74) | May 18, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [c5f452ea28](https://linux-hardware.org/?probe=c5f452ea28) | May 18, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [fdb0fb3d9c](https://linux-hardware.org/?probe=fdb0fb3d9c) | May 18, 2023 |
| HONOR         | HLYL-WXX9                   | Notebook    | [01a49c336d](https://linux-hardware.org/?probe=01a49c336d) | May 18, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [05c4685974](https://linux-hardware.org/?probe=05c4685974) | May 18, 2023 |
| MTR           | DP1000T-B V2.0              | All in one  | [f607fe37d0](https://linux-hardware.org/?probe=f607fe37d0) | May 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [4551c437bf](https://linux-hardware.org/?probe=4551c437bf) | May 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [a1cb84300e](https://linux-hardware.org/?probe=a1cb84300e) | May 18, 2023 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [4651c937d1](https://linux-hardware.org/?probe=4651c937d1) | May 18, 2023 |
| OEM           | X79G                        | Desktop     | [08ece3d402](https://linux-hardware.org/?probe=08ece3d402) | May 18, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [86b17fb9ff](https://linux-hardware.org/?probe=86b17fb9ff) | May 17, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [a776d86dad](https://linux-hardware.org/?probe=a776d86dad) | May 17, 2023 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [adc188c60b](https://linux-hardware.org/?probe=adc188c60b) | May 17, 2023 |
| Unknown       | NF-CK804                    | Desktop     | [754a676bd7](https://linux-hardware.org/?probe=754a676bd7) | May 17, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [6688a22b2b](https://linux-hardware.org/?probe=6688a22b2b) | May 17, 2023 |
| MSI           | B85-G43                     | Desktop     | [fbf5ca53e9](https://linux-hardware.org/?probe=fbf5ca53e9) | May 17, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [f93ee0d717](https://linux-hardware.org/?probe=f93ee0d717) | May 17, 2023 |
| Aquarius      | NS685U R11                  | Notebook    | [23e33588a8](https://linux-hardware.org/?probe=23e33588a8) | May 17, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [dce4e8be7c](https://linux-hardware.org/?probe=dce4e8be7c) | May 17, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [94ee6e64c4](https://linux-hardware.org/?probe=94ee6e64c4) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [2df1a28c50](https://linux-hardware.org/?probe=2df1a28c50) | May 17, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [1455e60d54](https://linux-hardware.org/?probe=1455e60d54) | May 17, 2023 |
| Supermicro    | H12DSi-N6                   | Server      | [bb6cdf1807](https://linux-hardware.org/?probe=bb6cdf1807) | May 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [b9410e67b1](https://linux-hardware.org/?probe=b9410e67b1) | May 17, 2023 |
| HP            | 1589                        | Desktop     | [2eb60ba617](https://linux-hardware.org/?probe=2eb60ba617) | May 17, 2023 |
| Acer          | Veriton N4680G              | Desktop     | [c1fc339cf0](https://linux-hardware.org/?probe=c1fc339cf0) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAA... | Notebook    | [5e4e802b87](https://linux-hardware.org/?probe=5e4e802b87) | May 17, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [e0fb89fec8](https://linux-hardware.org/?probe=e0fb89fec8) | May 17, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [e571fb4d7d](https://linux-hardware.org/?probe=e571fb4d7d) | May 17, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | Notebook    | [429d4451c9](https://linux-hardware.org/?probe=429d4451c9) | May 16, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [3776285fc1](https://linux-hardware.org/?probe=3776285fc1) | May 16, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [03316a0819](https://linux-hardware.org/?probe=03316a0819) | May 16, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [930e5f69ed](https://linux-hardware.org/?probe=930e5f69ed) | May 16, 2023 |
| Maxtang       | FP650 V1.0                  | Desktop     | [8f1eba846a](https://linux-hardware.org/?probe=8f1eba846a) | May 16, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [81366d4eb1](https://linux-hardware.org/?probe=81366d4eb1) | May 16, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [1bfbf34771](https://linux-hardware.org/?probe=1bfbf34771) | May 16, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [ee17ca6aa8](https://linux-hardware.org/?probe=ee17ca6aa8) | May 16, 2023 |
| ASUSTek       | K53TA                       | Notebook    | [9700522405](https://linux-hardware.org/?probe=9700522405) | May 16, 2023 |
| HP            | ENVY dv6                    | Notebook    | [2490803f28](https://linux-hardware.org/?probe=2490803f28) | May 16, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d9cac69c4c](https://linux-hardware.org/?probe=d9cac69c4c) | May 16, 2023 |
| Digma         | EVE 11 C422 ES1068EW        | Notebook    | [21255b70aa](https://linux-hardware.org/?probe=21255b70aa) | May 16, 2023 |
| Acer          | AOD257                      | Notebook    | [421fde4e9b](https://linux-hardware.org/?probe=421fde4e9b) | May 16, 2023 |
| Samsung       | R780                        | Notebook    | [5862ae2996](https://linux-hardware.org/?probe=5862ae2996) | May 16, 2023 |
| Samsung       | R780                        | Notebook    | [1fc01590bb](https://linux-hardware.org/?probe=1fc01590bb) | May 16, 2023 |
| ASUSTek       | H170-PRO/USB                | Desktop     | [2cefbf1505](https://linux-hardware.org/?probe=2cefbf1505) | May 16, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [7dca952cb0](https://linux-hardware.org/?probe=7dca952cb0) | May 16, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9505c6130c](https://linux-hardware.org/?probe=9505c6130c) | May 16, 2023 |
| Lenovo        | 3145 No DPK                 | All in one  | [4fac5ac06a](https://linux-hardware.org/?probe=4fac5ac06a) | May 16, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [cce2c46f1e](https://linux-hardware.org/?probe=cce2c46f1e) | May 16, 2023 |
| iRU           | A231                        | Desktop     | [0b35bba039](https://linux-hardware.org/?probe=0b35bba039) | May 16, 2023 |
| ASUSTek       | K53TA                       | Notebook    | [57a36429fe](https://linux-hardware.org/?probe=57a36429fe) | May 15, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6586d8eaed](https://linux-hardware.org/?probe=6586d8eaed) | May 15, 2023 |
| Acer          | Aspire TC-705               | Desktop     | [781430f6f0](https://linux-hardware.org/?probe=781430f6f0) | May 15, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2b6c863711](https://linux-hardware.org/?probe=2b6c863711) | May 15, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [eee39f2f10](https://linux-hardware.org/?probe=eee39f2f10) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2ffc331e90](https://linux-hardware.org/?probe=2ffc331e90) | May 15, 2023 |
| Samsung       | R428/P428                   | Notebook    | [1d93335f58](https://linux-hardware.org/?probe=1d93335f58) | May 15, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [ec59045a15](https://linux-hardware.org/?probe=ec59045a15) | May 15, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [acd8d0441a](https://linux-hardware.org/?probe=acd8d0441a) | May 15, 2023 |
| Gigabyte      | B760 AORUS ELITE AX         | Desktop     | [b1ab3ebdd4](https://linux-hardware.org/?probe=b1ab3ebdd4) | May 15, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [6de826cbe5](https://linux-hardware.org/?probe=6de826cbe5) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f8f9a6dc69](https://linux-hardware.org/?probe=f8f9a6dc69) | May 15, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [36cb64f82a](https://linux-hardware.org/?probe=36cb64f82a) | May 15, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [8da2dc07ec](https://linux-hardware.org/?probe=8da2dc07ec) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7661V3L        | Notebook    | [5714171d2a](https://linux-hardware.org/?probe=5714171d2a) | May 14, 2023 |
| iRU           | A231                        | Desktop     | [8c941b1457](https://linux-hardware.org/?probe=8c941b1457) | May 14, 2023 |
| Acer          | Aspire V5-552G              | Notebook    | [4384294484](https://linux-hardware.org/?probe=4384294484) | May 14, 2023 |
| AZW           | MINI S                      | Desktop     | [72c9908514](https://linux-hardware.org/?probe=72c9908514) | May 14, 2023 |
| AZW           | MINI S                      | Desktop     | [788d932e58](https://linux-hardware.org/?probe=788d932e58) | May 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bd390995e3](https://linux-hardware.org/?probe=bd390995e3) | May 14, 2023 |
| HP            | ProBook 6560b               | Notebook    | [e8f24791d1](https://linux-hardware.org/?probe=e8f24791d1) | May 14, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [4272bb4341](https://linux-hardware.org/?probe=4272bb4341) | May 14, 2023 |
| Acer          | TravelMate B113             | Notebook    | [b6a4ef5336](https://linux-hardware.org/?probe=b6a4ef5336) | May 14, 2023 |
| Acer          | TravelMate B113             | Notebook    | [c2e9fe6581](https://linux-hardware.org/?probe=c2e9fe6581) | May 14, 2023 |
| MSI           | GL62 6QF                    | Notebook    | [6ae5c650f3](https://linux-hardware.org/?probe=6ae5c650f3) | May 14, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [08e2dca3fe](https://linux-hardware.org/?probe=08e2dca3fe) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [72eaf980ad](https://linux-hardware.org/?probe=72eaf980ad) | May 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [077df36551](https://linux-hardware.org/?probe=077df36551) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [ba47df6545](https://linux-hardware.org/?probe=ba47df6545) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [0b6c34eefa](https://linux-hardware.org/?probe=0b6c34eefa) | May 14, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [675fc0ce85](https://linux-hardware.org/?probe=675fc0ce85) | May 14, 2023 |
| Irbis         | NB64                        | Notebook    | [a3dc2d6133](https://linux-hardware.org/?probe=a3dc2d6133) | May 13, 2023 |
| Irbis         | NB64                        | Notebook    | [369617cbf6](https://linux-hardware.org/?probe=369617cbf6) | May 13, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [10ee4f50b6](https://linux-hardware.org/?probe=10ee4f50b6) | May 13, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [7e178a2a32](https://linux-hardware.org/?probe=7e178a2a32) | May 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cd0c59d678](https://linux-hardware.org/?probe=cd0c59d678) | May 13, 2023 |
| Lenovo        | ThinkCentre M71e 3176RV9    | Desktop     | [1f47569d44](https://linux-hardware.org/?probe=1f47569d44) | May 13, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [12b97cd9b6](https://linux-hardware.org/?probe=12b97cd9b6) | May 13, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [3d4b4e176a](https://linux-hardware.org/?probe=3d4b4e176a) | May 13, 2023 |
| OEM           | X99-Turbo                   | Desktop     | [31cc62203f](https://linux-hardware.org/?probe=31cc62203f) | May 13, 2023 |
| ECS           | IC55H-A                     | Desktop     | [82ad3504a9](https://linux-hardware.org/?probe=82ad3504a9) | May 13, 2023 |
| Samsung       | R425/R525                   | Notebook    | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| ASUSTek       | P5B                         | Desktop     | [ef0459f224](https://linux-hardware.org/?probe=ef0459f224) | May 13, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [efab80e399](https://linux-hardware.org/?probe=efab80e399) | May 13, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a86469b33f](https://linux-hardware.org/?probe=a86469b33f) | May 12, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [af60056caa](https://linux-hardware.org/?probe=af60056caa) | May 12, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b1b041ac47](https://linux-hardware.org/?probe=b1b041ac47) | May 12, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [de18c72638](https://linux-hardware.org/?probe=de18c72638) | May 12, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [29e584b980](https://linux-hardware.org/?probe=29e584b980) | May 12, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [22673e3f0c](https://linux-hardware.org/?probe=22673e3f0c) | May 12, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [2941682016](https://linux-hardware.org/?probe=2941682016) | May 12, 2023 |
| ASUSTek       | M51Sn                       | Notebook    | [94a426384a](https://linux-hardware.org/?probe=94a426384a) | May 12, 2023 |
| HP            | 8374 1100                   | All in one  | [2e31c0e1d5](https://linux-hardware.org/?probe=2e31c0e1d5) | May 12, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | Notebook    | [2a93dcb797](https://linux-hardware.org/?probe=2a93dcb797) | May 12, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [ceea346358](https://linux-hardware.org/?probe=ceea346358) | May 12, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [16782746d8](https://linux-hardware.org/?probe=16782746d8) | May 12, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [5afcbcef75](https://linux-hardware.org/?probe=5afcbcef75) | May 12, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [0959f95f56](https://linux-hardware.org/?probe=0959f95f56) | May 12, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [b502077711](https://linux-hardware.org/?probe=b502077711) | May 12, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [ab733d41de](https://linux-hardware.org/?probe=ab733d41de) | May 12, 2023 |
| Acer          | RS880M05                    | Desktop     | [5952c105f6](https://linux-hardware.org/?probe=5952c105f6) | May 12, 2023 |
| MSI           | 770-C45                     | Desktop     | [a2b983590a](https://linux-hardware.org/?probe=a2b983590a) | May 12, 2023 |
| MSI           | 770-C45                     | Desktop     | [6f2e35faa1](https://linux-hardware.org/?probe=6f2e35faa1) | May 12, 2023 |
| Digma         | Pro Magnus M DN16R7-ADXW... | Notebook    | [4e4a1278e9](https://linux-hardware.org/?probe=4e4a1278e9) | May 12, 2023 |
| HUAWEI        | NbDE-WXX9                   | Notebook    | [77da4c15ba](https://linux-hardware.org/?probe=77da4c15ba) | May 12, 2023 |
| Rombica       | myBook Zenith               | Notebook    | [f7438f1448](https://linux-hardware.org/?probe=f7438f1448) | May 11, 2023 |
| Notebook      | W250EGQ / W270EGQ           | Notebook    | [7259a9f7fb](https://linux-hardware.org/?probe=7259a9f7fb) | May 11, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [68e25fe72f](https://linux-hardware.org/?probe=68e25fe72f) | May 11, 2023 |
| Huanan        | X99-F8 Gaming 2021          | Desktop     | [fb4cf864f2](https://linux-hardware.org/?probe=fb4cf864f2) | May 11, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [847d86e573](https://linux-hardware.org/?probe=847d86e573) | May 11, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [11e89ebe3c](https://linux-hardware.org/?probe=11e89ebe3c) | May 11, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [dea48fc3fa](https://linux-hardware.org/?probe=dea48fc3fa) | May 11, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [3fb4df889e](https://linux-hardware.org/?probe=3fb4df889e) | May 11, 2023 |
| Gigabyte      | Z270N-Gaming 5              | Desktop     | [c056fdd9a8](https://linux-hardware.org/?probe=c056fdd9a8) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [b3342e7343](https://linux-hardware.org/?probe=b3342e7343) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [f0fbd1eda9](https://linux-hardware.org/?probe=f0fbd1eda9) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [096f897a80](https://linux-hardware.org/?probe=096f897a80) | May 11, 2023 |
| Clevo         | W210CUQ                     | Notebook    | [73f12c473d](https://linux-hardware.org/?probe=73f12c473d) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [7a1acf3851](https://linux-hardware.org/?probe=7a1acf3851) | May 11, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [3c0893a822](https://linux-hardware.org/?probe=3c0893a822) | May 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [39f23657d8](https://linux-hardware.org/?probe=39f23657d8) | May 11, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [3fee2052a6](https://linux-hardware.org/?probe=3fee2052a6) | May 11, 2023 |
| Supermicro    | H11SSL-i                    | Server      | [b68071ee84](https://linux-hardware.org/?probe=b68071ee84) | May 11, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [3eebb3f19d](https://linux-hardware.org/?probe=3eebb3f19d) | May 11, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [b266312b1e](https://linux-hardware.org/?probe=b266312b1e) | May 11, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [848dc775e0](https://linux-hardware.org/?probe=848dc775e0) | May 11, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [72aed73d34](https://linux-hardware.org/?probe=72aed73d34) | May 11, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [8726271588](https://linux-hardware.org/?probe=8726271588) | May 11, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [ac70f06ddc](https://linux-hardware.org/?probe=ac70f06ddc) | May 11, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [cf7aa805b4](https://linux-hardware.org/?probe=cf7aa805b4) | May 11, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [ceff5a622d](https://linux-hardware.org/?probe=ceff5a622d) | May 11, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [54b185860a](https://linux-hardware.org/?probe=54b185860a) | May 10, 2023 |
| Digma         | EVE 11 C422 ES1068EW        | Notebook    | [6c6b40d9de](https://linux-hardware.org/?probe=6c6b40d9de) | May 10, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [8376015b15](https://linux-hardware.org/?probe=8376015b15) | May 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [e07b012f6b](https://linux-hardware.org/?probe=e07b012f6b) | May 10, 2023 |
| ECS           | G31T-M9                     | Desktop     | [25fd5432f0](https://linux-hardware.org/?probe=25fd5432f0) | May 10, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [e391a674fa](https://linux-hardware.org/?probe=e391a674fa) | May 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [c3902a3649](https://linux-hardware.org/?probe=c3902a3649) | May 10, 2023 |
| HP            | 339A                        | Desktop     | [f5a7934b67](https://linux-hardware.org/?probe=f5a7934b67) | May 10, 2023 |
| Supermicro    | X9DRW                       | Server      | [a36aa5e1ee](https://linux-hardware.org/?probe=a36aa5e1ee) | May 10, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [7b956abe69](https://linux-hardware.org/?probe=7b956abe69) | May 10, 2023 |
| Irbis         | NB143                       | Notebook    | [b4dd25345a](https://linux-hardware.org/?probe=b4dd25345a) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [ce24dc022b](https://linux-hardware.org/?probe=ce24dc022b) | May 10, 2023 |
| ASUSTek       | P8Z68-M PRO                 | Desktop     | [37b88384a5](https://linux-hardware.org/?probe=37b88384a5) | May 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [1285d2af93](https://linux-hardware.org/?probe=1285d2af93) | May 10, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [928216a0a5](https://linux-hardware.org/?probe=928216a0a5) | May 10, 2023 |
| Supermicro    | X8DTU                       | Server      | [c3f047a095](https://linux-hardware.org/?probe=c3f047a095) | May 10, 2023 |
| Supermicro    | X8DTU                       | Server      | [5898cc1b65](https://linux-hardware.org/?probe=5898cc1b65) | May 10, 2023 |
| Intel         | X58M                        | Desktop     | [666b002908](https://linux-hardware.org/?probe=666b002908) | May 10, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6dab6243c2](https://linux-hardware.org/?probe=6dab6243c2) | May 10, 2023 |
| MSI           | GP60 2OD                    | Notebook    | [910b0f9647](https://linux-hardware.org/?probe=910b0f9647) | May 10, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [aa5ebc6727](https://linux-hardware.org/?probe=aa5ebc6727) | May 10, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [e61f99e96e](https://linux-hardware.org/?probe=e61f99e96e) | May 10, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [ab5b69b742](https://linux-hardware.org/?probe=ab5b69b742) | May 10, 2023 |
| Lenovo        | RD450X                      | Server      | [6fca1885fc](https://linux-hardware.org/?probe=6fca1885fc) | May 10, 2023 |
| Lenovo        | RD450X                      | Server      | [5cd314b0af](https://linux-hardware.org/?probe=5cd314b0af) | May 10, 2023 |
| Packard Be... | DOT S                       | Notebook    | [1ca8df486d](https://linux-hardware.org/?probe=1ca8df486d) | May 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [21471afcae](https://linux-hardware.org/?probe=21471afcae) | May 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [4a0ccb88d2](https://linux-hardware.org/?probe=4a0ccb88d2) | May 09, 2023 |
| Clevo         | W210CUQ                     | Notebook    | [afd0fd091b](https://linux-hardware.org/?probe=afd0fd091b) | May 09, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [3ad22447bb](https://linux-hardware.org/?probe=3ad22447bb) | May 09, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [d95065a8fa](https://linux-hardware.org/?probe=d95065a8fa) | May 09, 2023 |
| Acer          | Aspire 5100                 | Notebook    | [d12cffdc1d](https://linux-hardware.org/?probe=d12cffdc1d) | May 09, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [7f25dc4e18](https://linux-hardware.org/?probe=7f25dc4e18) | May 09, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [12c2931180](https://linux-hardware.org/?probe=12c2931180) | May 09, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [27ec66031a](https://linux-hardware.org/?probe=27ec66031a) | May 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [1324443418](https://linux-hardware.org/?probe=1324443418) | May 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [49ad1e2075](https://linux-hardware.org/?probe=49ad1e2075) | May 09, 2023 |
| ASRock        | H67DE3/SI                   | Desktop     | [13b1131bef](https://linux-hardware.org/?probe=13b1131bef) | May 08, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [de7d5668d5](https://linux-hardware.org/?probe=de7d5668d5) | May 08, 2023 |
| ASUSTek       | M3N WS                      | Desktop     | [fb7920c5f9](https://linux-hardware.org/?probe=fb7920c5f9) | May 08, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | Notebook    | [f63a54bf5f](https://linux-hardware.org/?probe=f63a54bf5f) | May 08, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1d61e5da8b](https://linux-hardware.org/?probe=1d61e5da8b) | May 08, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [5c8c1872e4](https://linux-hardware.org/?probe=5c8c1872e4) | May 08, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [5e78ff90cc](https://linux-hardware.org/?probe=5e78ff90cc) | May 08, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [8394909745](https://linux-hardware.org/?probe=8394909745) | May 08, 2023 |
| Acer          | Aspire ES1-132              | Notebook    | [10a13dcd68](https://linux-hardware.org/?probe=10a13dcd68) | May 08, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [f64f988a79](https://linux-hardware.org/?probe=f64f988a79) | May 08, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [47f5fe62aa](https://linux-hardware.org/?probe=47f5fe62aa) | May 08, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e6ead6e953](https://linux-hardware.org/?probe=e6ead6e953) | May 08, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [e3dc27eee1](https://linux-hardware.org/?probe=e3dc27eee1) | May 08, 2023 |
| Samsung       | 300V3A/300V4A/300V5A        | Notebook    | [bb84771a09](https://linux-hardware.org/?probe=bb84771a09) | May 08, 2023 |
| Dell          | Inspiron N5050              | Notebook    | [577e5fe375](https://linux-hardware.org/?probe=577e5fe375) | May 08, 2023 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [9a420c42de](https://linux-hardware.org/?probe=9a420c42de) | May 07, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f045323c99](https://linux-hardware.org/?probe=f045323c99) | May 07, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a13212b8b7](https://linux-hardware.org/?probe=a13212b8b7) | May 07, 2023 |
| Lenovo        | V580c 20160                 | Notebook    | [8efa05ada7](https://linux-hardware.org/?probe=8efa05ada7) | May 07, 2023 |
| Sony          | VPCZ23Q9R                   | Notebook    | [38c78ad6b1](https://linux-hardware.org/?probe=38c78ad6b1) | May 07, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [a241837604](https://linux-hardware.org/?probe=a241837604) | May 07, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ROSA R11           | 3118      | 10.68%  |
| ROSA R10           | 3116      | 10.68%  |
| ROSA R8.1          | 2217      | 7.6%    |
| ROSA R8            | 1995      | 6.84%   |
| ROSA R9            | 1814      | 6.22%   |
| ROSA 12.2          | 1749      | 5.99%   |
| ROSA R11.1         | 1694      | 5.8%    |
| Debian 11          | 1002      | 3.43%   |
| Ubuntu 20.04       | 891       | 3.05%   |
| ROSA 12.3          | 818       | 2.8%    |
| Ubuntu 18.04       | 485       | 1.66%   |
| OpenMandriva 4.2   | 402       | 1.38%   |
| ROSA 12.4          | 400       | 1.37%   |
| Ubuntu 22.04       | 392       | 1.34%   |
| OpenMandriva 4.3   | 284       | 0.97%   |
| ROSA 12.1          | 271       | 0.93%   |
| Arch Rolling       | 256       | 0.88%   |
| KDE neon 20.04     | 199       | 0.68%   |
| Arch               | 175       | 0.6%    |
| Debian 10          | 174       | 0.6%    |
| Kometa P10         | 165       | 0.57%   |
| ROSA 12            | 158       | 0.54%   |
| Manjaro            | 158       | 0.54%   |
| Debian 12          | 152       | 0.52%   |
| Fedora 36          | 150       | 0.51%   |
| Fedora 37          | 144       | 0.49%   |
| Linux Mint 20.3    | 135       | 0.46%   |
| Linux Mint 19.3    | 133       | 0.46%   |
| Xubuntu 20.04      | 126       | 0.43%   |
| OpenMandriva 23.01 | 119       | 0.41%   |
| Kubuntu 20.04      | 118       | 0.4%    |
| Linux Mint 18.3    | 112       | 0.38%   |
| Fedora 35          | 112       | 0.38%   |
| OpenMandriva 23.03 | 110       | 0.38%   |
| Linux Mint 20.1    | 108       | 0.37%   |
| Linux Mint 19.1    | 105       | 0.36%   |
| ALT Linux 10.1     | 103       | 0.35%   |
| Red OS 7.3.1       | 100       | 0.34%   |
| Red OS 7.3.2       | 97        | 0.33%   |
| Linux Mint 20      | 96        | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| ROSA          | 14907     | 57.62%  |
| Ubuntu        | 2210      | 8.54%   |
| Debian        | 1366      | 5.28%   |
| Linux Mint    | 1074      | 4.15%   |
| OpenMandriva  | 970       | 3.75%   |
| Fedora        | 714       | 2.76%   |
| Manjaro       | 599       | 2.32%   |
| ALT Linux     | 527       | 2.04%   |
| Arch          | 414       | 1.6%    |
| Endless       | 286       | 1.11%   |
| Red OS        | 282       | 1.09%   |
| Kubuntu       | 263       | 1.02%   |
| KDE neon      | 260       | 1.01%   |
| Xubuntu       | 257       | 0.99%   |
| RED           | 168       | 0.65%   |
| Pop!_OS       | 154       | 0.6%    |
| Gentoo        | 131       | 0.51%   |
| openSUSE      | 96        | 0.37%   |
| Elementary    | 87        | 0.34%   |
| Kali          | 84        | 0.32%   |
| Ubuntu MATE   | 65        | 0.25%   |
| Clear Linux   | 63        | 0.24%   |
| CentOS        | 63        | 0.24%   |
| Lubuntu       | 62        | 0.24%   |
| LMDE          | 61        | 0.24%   |
| Zorin         | 60        | 0.23%   |
| Ubuntu Unity  | 50        | 0.19%   |
| ArcoLinux     | 46        | 0.18%   |
| RELS          | 44        | 0.17%   |
| Cyber Infra   | 38        | 0.15%   |
| Astra Linux   | 28        | 0.11%   |
| EndeavourOS   | 27        | 0.1%    |
| SteamOS       | 25        | 0.1%    |
| Artix         | 23        | 0.09%   |
| MX            | 22        | 0.09%   |
| Parrot        | 18        | 0.07%   |
| Ubuntu Budgie | 16        | 0.06%   |
| RELD          | 15        | 0.06%   |
| Calculate     | 15        | 0.06%   |
| Void Linux    | 13        | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.10.74-generic-2rosa2021.1-x86_64  | 1493      | 4.76%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 1358      | 4.33%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 1352      | 4.31%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 1280      | 4.08%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 761       | 2.43%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 619       | 1.97%   |
| 5.10.0-7-amd64                      | 583       | 1.86%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 558       | 1.78%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 545       | 1.74%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 476       | 1.52%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 395       | 1.26%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 391       | 1.25%   |
| 5.10.14-desktop-1omv4002            | 387       | 1.23%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 377       | 1.2%    |
| 4.15.0-desktop-68.5rosa-x86_64      | 369       | 1.18%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 363       | 1.16%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 353       | 1.13%   |
| 4.15.0-desktop-45.1rosa-i586        | 348       | 1.11%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 326       | 1.04%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 322       | 1.03%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 319       | 1.02%   |
| 5.4.32-generic-2rosa-x86_64         | 316       | 1.01%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 307       | 0.98%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 297       | 0.95%   |
| 5.4.83-generic-2rosa-x86_64         | 291       | 0.93%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 278       | 0.89%   |
| 5.16.7-desktop-1omv4003             | 261       | 0.83%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 251       | 0.8%    |
| 4.15.0-desktop-94.1rosa-x86_64      | 251       | 0.8%    |
| 5.15.79-generic-1rosa2021.1-x86_64  | 238       | 0.76%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 220       | 0.7%    |
| 4.1.25-nrj-desktop-1rosa-i586       | 204       | 0.65%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 192       | 0.61%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 167       | 0.53%   |
| 5.10.0-2-amd64                      | 149       | 0.47%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 143       | 0.46%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 143       | 0.46%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 138       | 0.44%   |
| 5.4.0-42-generic                    | 126       | 0.4%    |
| 4.1.38-nrj-desktop-1rosa-x86_64     | 124       | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 3992      | 13.13%  |
| 4.9.60   | 1751      | 5.76%   |
| 4.9.20   | 1642      | 5.4%    |
| 5.10.74  | 1542      | 5.07%   |
| 5.4.0    | 1340      | 4.41%   |
| 4.1.34   | 1057      | 3.48%   |
| 5.10.0   | 1047      | 3.44%   |
| 4.1.38   | 841       | 2.77%   |
| 4.9.9    | 792       | 2.6%    |
| 4.9.124  | 765       | 2.52%   |
| 4.1.25   | 763       | 2.51%   |
| 5.15.0   | 718       | 2.36%   |
| 4.9.76   | 494       | 1.62%   |
| 4.9.41   | 493       | 1.62%   |
| 4.9.155  | 479       | 1.58%   |
| 5.4.32   | 433       | 1.42%   |
| 5.3.0    | 400       | 1.32%   |
| 5.10.14  | 391       | 1.29%   |
| 5.4.83   | 379       | 1.25%   |
| 5.8.0    | 376       | 1.24%   |
| 5.11.0   | 356       | 1.17%   |
| 6.1.20   | 337       | 1.11%   |
| 5.10.118 | 335       | 1.1%    |
| 5.15.75  | 320       | 1.05%   |
| 5.13.0   | 308       | 1.01%   |
| 5.0.0    | 296       | 0.97%   |
| 5.16.7   | 264       | 0.87%   |
| 4.9.95   | 251       | 0.83%   |
| 5.15.79  | 242       | 0.8%    |
| 5.19.0   | 232       | 0.76%   |
| 4.18.0   | 192       | 0.63%   |
| 6.1.0    | 190       | 0.62%   |
| 4.9.111  | 187       | 0.61%   |
| 4.19.0   | 158       | 0.52%   |
| 4.13.0   | 145       | 0.48%   |
| 4.9.87   | 142       | 0.47%   |
| 5.10.71  | 139       | 0.46%   |
| 3.10.0   | 129       | 0.42%   |
| 6.2.6    | 127       | 0.42%   |
| 6.1.1    | 121       | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 6233      | 21.84%  |
| 4.15    | 4030      | 14.12%  |
| 5.10    | 4003      | 14.03%  |
| 4.1     | 2601      | 9.12%   |
| 5.4     | 2496      | 8.75%   |
| 5.15    | 2034      | 7.13%   |
| 6.1     | 850       | 2.98%   |
| 5.11    | 514       | 1.8%    |
| 5.8     | 499       | 1.75%   |
| 5.3     | 496       | 1.74%   |
| 5.16    | 417       | 1.46%   |
| 5.13    | 407       | 1.43%   |
| 5.19    | 344       | 1.21%   |
| 5.0     | 325       | 1.14%   |
| 6.2     | 301       | 1.05%   |
| 6.0     | 272       | 0.95%   |
| 5.18    | 254       | 0.89%   |
| 4.19    | 248       | 0.87%   |
| 5.17    | 224       | 0.79%   |
| 4.18    | 218       | 0.76%   |
| 4.13    | 175       | 0.61%   |
| 5.14    | 174       | 0.61%   |
| 5.6     | 157       | 0.55%   |
| 5.9     | 137       | 0.48%   |
| 3.10    | 132       | 0.46%   |
| 4.4     | 109       | 0.38%   |
| 5.12    | 99        | 0.35%   |
| 5.7     | 93        | 0.33%   |
| 6.3     | 82        | 0.29%   |
| 4.8     | 77        | 0.27%   |
| 4.16    | 76        | 0.27%   |
| 5.5     | 71        | 0.25%   |
| 4.10    | 59        | 0.21%   |
| 4.14    | 50        | 0.18%   |
| 3.14    | 43        | 0.15%   |
| 5.2     | 40        | 0.14%   |
| 4.12    | 30        | 0.11%   |
| 4.17    | 27        | 0.09%   |
| 4.11    | 24        | 0.08%   |
| 5.1     | 18        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 21979     | 86.44%  |
| i686        | 3359      | 13.21%  |
| aarch64     | 57        | 0.22%   |
| armv7l      | 15        | 0.06%   |
| armv6l      | 5         | 0.02%   |
| e2k         | 4         | 0.02%   |
| armv8l      | 3         | 0.01%   |
| ppc64       | 1         | 0.004%  |
| ppc         | 1         | 0.004%  |
| mips        | 1         | 0.004%  |
| loongarch64 | 1         | 0.004%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| KDE4               | 9050      | 33.62%  |
| KDE5               | 7070      | 26.26%  |
| GNOME              | 4401      | 16.35%  |
| Unknown            | 2172      | 8.07%   |
| XFCE               | 939       | 3.49%   |
| LXQt               | 793       | 2.95%   |
| MATE               | 792       | 2.94%   |
| X-Cinnamon         | 491       | 1.82%   |
| Cinnamon           | 469       | 1.74%   |
| KDE                | 314       | 1.17%   |
| Pantheon           | 82        | 0.3%    |
| LXDE               | 57        | 0.21%   |
| Unity              | 50        | 0.19%   |
| i3                 | 49        | 0.18%   |
| Budgie             | 37        | 0.14%   |
| GNOME Flashback    | 26        | 0.1%    |
| Deepin             | 18        | 0.07%   |
| sway               | 15        | 0.06%   |
| fly                | 15        | 0.06%   |
| GNOME Classic      | 10        | 0.04%   |
| awesome            | 10        | 0.04%   |
| openbox            | 9         | 0.03%   |
| icewm              | 7         | 0.03%   |
| DWM                | 7         | 0.03%   |
| bspwm              | 7         | 0.03%   |
| Hyprland           | 5         | 0.02%   |
| xmonad             | 4         | 0.01%   |
| Trinity            | 4         | 0.01%   |
| lightdm-xsession   | 4         | 0.01%   |
| fluxbox            | 3         | 0.01%   |
| X-Generic          | 1         | 0.004%  |
| steamos            | 1         | 0.004%  |
| qtile              | 1         | 0.004%  |
| pantheon-non-gnome | 1         | 0.004%  |
| none+i3            | 1         | 0.004%  |
| Lumina             | 1         | 0.004%  |
| Lubuntu            | 1         | 0.004%  |
| i3-with-shmlog     | 1         | 0.004%  |
| fvwm2              | 1         | 0.004%  |
| Enlightenment      | 1         | 0.004%  |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 20346     | 78.59%  |
| Wayland | 3847      | 14.86%  |
| Unknown | 1396      | 5.39%   |
| Tty     | 299       | 1.15%   |
| Web     | 1         | 0.004%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDM     | 9112      | 33.97%  |
| SDDM    | 7192      | 26.81%  |
| Unknown | 4647      | 17.32%  |
| GDM     | 3120      | 11.63%  |
| LightDM | 1180      | 4.4%    |
| TDM     | 798       | 2.97%   |
| GDM3    | 652       | 2.43%   |
| MDM     | 43        | 0.16%   |
| XDM     | 28        | 0.1%    |
| SLiM    | 17        | 0.06%   |
| FLY-DM  | 11        | 0.04%   |
| LXDM    | 10        | 0.04%   |
| Ly      | 6         | 0.02%   |
| NODM    | 4         | 0.01%   |
| GREETD  | 4         | 0.01%   |
| WDM     | 1         | 0.004%  |
| LDM     | 1         | 0.004%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 12404     | 47.37%  |
| ru_RU       | 10941     | 41.78%  |
| en_US       | 2436      | 9.3%    |
| C           | 169       | 0.65%   |
| en_GB       | 85        | 0.32%   |
| ru_RU.UTF_8 | 30        | 0.11%   |
| ru_UA       | 18        | 0.07%   |
| C.UTF8      | 15        | 0.06%   |
| POSIX       | 13        | 0.05%   |
| ru_RU.UTF8  | 9         | 0.03%   |
| de_DE       | 7         | 0.03%   |
| cv_RU       | 7         | 0.03%   |
| zh_CN       | 6         | 0.02%   |
| en_DK       | 5         | 0.02%   |
| en_AG       | 5         | 0.02%   |
| ba_RU       | 5         | 0.02%   |
| en_CA       | 4         | 0.02%   |
| uk_UA       | 3         | 0.01%   |
| tt_RU       | 3         | 0.01%   |
| fr_FR       | 3         | 0.01%   |
| es_ES       | 3         | 0.01%   |
| tr_TR       | 2         | 0.01%   |
| myv_RU      | 2         | 0.01%   |
| it_IT       | 2         | 0.01%   |
| pt_BR       | 1         | 0.004%  |
| ja_JP       | 1         | 0.004%  |
| en_RU       | 1         | 0.004%  |
| en_NZ       | 1         | 0.004%  |
| en_IL       | 1         | 0.004%  |
| en_GB.utf-8 | 1         | 0.004%  |
| en_AU       | 1         | 0.004%  |
| en-US       | 1         | 0.004%  |
| ce_RU       | 1         | 0.004%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 16274     | 63.3%   |
| EFI  | 9437      | 36.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 15321     | 57.55%  |
| Unknown  | 7580      | 28.47%  |
| Overlay  | 1806      | 6.78%   |
| Btrfs    | 1375      | 5.17%   |
| Xfs      | 212       | 0.8%    |
| Zfs      | 81        | 0.3%    |
| Ext3     | 68        | 0.26%   |
| Tmpfs    | 45        | 0.17%   |
| Ext2     | 41        | 0.15%   |
| F2fs     | 39        | 0.15%   |
| Aufs     | 22        | 0.08%   |
| Reiserfs | 8         | 0.03%   |
| XXXXXXX  | 5         | 0.02%   |
| Rootfs   | 5         | 0.02%   |
| Jfs      | 5         | 0.02%   |
| SAMSUNG  | 3         | 0.01%   |
| XXXXX    | 2         | 0.01%   |
| Ufs      | 1         | 0.004%  |
| Exfat    | 1         | 0.004%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 10823     | 40.65%  |
| GPT     | 8866      | 33.3%   |
| Unknown | 6935      | 26.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22332     | 85.9%   |
| Yes       | 3666      | 14.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 17819     | 67.91%  |
| Yes       | 8420      | 32.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 6446      | 25.63%  |
| Gigabyte Technology | 2991      | 11.89%  |
| Lenovo              | 2454      | 9.76%   |
| Hewlett-Packard     | 2040      | 8.11%   |
| Acer                | 1863      | 7.41%   |
| MSI                 | 1611      | 6.41%   |
| ASRock              | 1315      | 5.23%   |
| Dell                | 977       | 3.89%   |
| Samsung Electronics | 665       | 2.64%   |
| Intel               | 478       | 1.9%    |
| Unknown             | 316       | 1.26%   |
| Toshiba             | 295       | 1.17%   |
| Sony                | 279       | 1.11%   |
| ECS                 | 272       | 1.08%   |
| HUAWEI              | 218       | 0.87%   |
| Packard Bell        | 184       | 0.73%   |
| Supermicro          | 180       | 0.72%   |
| Apple               | 150       | 0.6%    |
| Pegatron            | 149       | 0.59%   |
| Biostar             | 132       | 0.52%   |
| Foxconn             | 125       | 0.5%    |
| eMachines           | 124       | 0.49%   |
| Clevo               | 106       | 0.42%   |
| Aquarius            | 102       | 0.41%   |
| Timi                | 94        | 0.37%   |
| Huanan              | 86        | 0.34%   |
| Notebook            | 75        | 0.3%    |
| Digma               | 62        | 0.25%   |
| Fujitsu             | 59        | 0.23%   |
| Fujitsu Siemens     | 57        | 0.23%   |
| HONOR               | 51        | 0.2%    |
| Irbis               | 49        | 0.19%   |
| Quanta              | 42        | 0.17%   |
| DNS                 | 40        | 0.16%   |
| ICL                 | 39        | 0.16%   |
| 3Logic Group        | 39        | 0.16%   |
| Prestigio           | 37        | 0.15%   |
| DEPO Computers      | 36        | 0.14%   |
| AMI                 | 34        | 0.14%   |
| DEXP                | 33        | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 411       | 1.63%   |
| ASUS All Series                  | 382       | 1.52%   |
| HP Pavilion g6                   | 125       | 0.5%    |
| HP Pavilion dv6                  | 80        | 0.32%   |
| HP Notebook                      | 80        | 0.32%   |
| HP Laptop 15-bw0xx               | 76        | 0.3%    |
| MSI MS-7996                      | 72        | 0.29%   |
| Gigabyte 970A-DS3P               | 72        | 0.29%   |
| MSI MS-7817                      | 70        | 0.28%   |
| ASUS M5A78L-M LX3                | 68        | 0.27%   |
| ASUS H110M-R                     | 60        | 0.24%   |
| Acer Aspire V3-571G              | 60        | 0.24%   |
| ASUS P8H61-M LX3 R2.0            | 59        | 0.23%   |
| ASUS S20 K29                     | 55        | 0.22%   |
| Lenovo G570 20079                | 53        | 0.21%   |
| Supermicro Super Server          | 50        | 0.2%    |
| Aquarius NS585                   | 50        | 0.2%    |
| Intel SKYBAY                     | 49        | 0.19%   |
| ASUS P5K                         | 49        | 0.19%   |
| Lenovo B570e HuronRiver Platform | 47        | 0.19%   |
| ASUS M5A97 R2.0                  | 47        | 0.19%   |
| MSI MS-7529                      | 46        | 0.18%   |
| Gigabyte H61M-S1                 | 46        | 0.18%   |
| ASRock G31M-S                    | 46        | 0.18%   |
| Gigabyte G31M-ES2L               | 44        | 0.17%   |
| Lenovo B590 20206                | 43        | 0.17%   |
| ASUS P5KPL-AM                    | 43        | 0.17%   |
| ASUS P5G41T-M LX2/GB             | 43        | 0.17%   |
| HP Pavilion dv7                  | 42        | 0.17%   |
| MSI MS-7592                      | 41        | 0.16%   |
| ASUS PRIME A320M-K               | 41        | 0.16%   |
| Gigabyte H61M-S2PV               | 40        | 0.16%   |
| ASRock N68C-S UCC                | 40        | 0.16%   |
| Packard Bell EasyNote TE11HC     | 39        | 0.16%   |
| HP Pavilion 15                   | 39        | 0.16%   |
| ASUS M5A78L-M/USB3               | 39        | 0.16%   |
| Lenovo B590 20208                | 38        | 0.15%   |
| ASUS M5A97 LE R2.0               | 37        | 0.15%   |
| Lenovo G50-45 80E3               | 36        | 0.14%   |
| ECS G31T-M9                      | 36        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1267      | 5.04%   |
| Lenovo IdeaPad        | 649       | 2.58%   |
| HP Pavilion           | 526       | 2.09%   |
| Lenovo ThinkPad       | 480       | 1.91%   |
| Dell Inspiron         | 435       | 1.73%   |
| ASUS PRIME            | 427       | 1.7%    |
| Unknown               | 411       | 1.63%   |
| ASUS All              | 382       | 1.52%   |
| ASUS VivoBook         | 308       | 1.22%   |
| HP Laptop             | 295       | 1.17%   |
| Toshiba Satellite     | 274       | 1.09%   |
| HP ProBook            | 264       | 1.05%   |
| ASUS P8H61-M          | 191       | 0.76%   |
| ASUS M5A78L-M         | 179       | 0.71%   |
| Dell Latitude         | 174       | 0.69%   |
| HP Compaq             | 170       | 0.68%   |
| Acer Extensa          | 156       | 0.62%   |
| Packard Bell EasyNote | 153       | 0.61%   |
| ASUS P5KPL-AM         | 127       | 0.51%   |
| ASUS ROG              | 126       | 0.5%    |
| Dell Vostro           | 125       | 0.5%    |
| ASUS TUF              | 117       | 0.47%   |
| ASUS M5A97            | 114       | 0.45%   |
| ASUS P5G41T-M         | 109       | 0.43%   |
| ASUS P5K              | 100       | 0.4%    |
| HP EliteBook          | 93        | 0.37%   |
| Acer TravelMate       | 90        | 0.36%   |
| ASUS P8Z77-V          | 87        | 0.35%   |
| Lenovo B590           | 81        | 0.32%   |
| HP Notebook           | 81        | 0.32%   |
| Lenovo ThinkCentre    | 78        | 0.31%   |
| Lenovo G580           | 78        | 0.31%   |
| Gigabyte B450M        | 74        | 0.29%   |
| Gigabyte 970A-DS3P    | 73        | 0.29%   |
| Dell OptiPlex         | 73        | 0.29%   |
| ASUS P5Q              | 73        | 0.29%   |
| MSI MS-7996           | 72        | 0.29%   |
| Lenovo ThinkBook      | 72        | 0.29%   |
| HP ENVY               | 72        | 0.29%   |
| MSI MS-7817           | 70        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 3057      | 12.16%  |
| 2011    | 2594      | 10.32%  |
| 2010    | 1990      | 7.91%   |
| 2013    | 1770      | 7.04%   |
| 2009    | 1692      | 6.73%   |
| 2018    | 1685      | 6.7%    |
| 2008    | 1393      | 5.54%   |
| 2019    | 1382      | 5.5%    |
| 2020    | 1238      | 4.92%   |
| 2017    | 1199      | 4.77%   |
| 2007    | 1195      | 4.75%   |
| 2021    | 1102      | 4.38%   |
| 2014    | 1102      | 4.38%   |
| 2016    | 1073      | 4.27%   |
| 2015    | 988       | 3.93%   |
| 2006    | 684       | 2.72%   |
| 2022    | 510       | 2.03%   |
| 2005    | 251       | 1%      |
| Unknown | 86        | 0.34%   |
| 2004    | 80        | 0.32%   |
| 2003    | 44        | 0.17%   |
| 2023    | 18        | 0.07%   |
| 2002    | 8         | 0.03%   |
| 2001    | 5         | 0.02%   |
| 2000    | 1         | 0.004%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 12058     | 47.95%  |
| Notebook       | 11977     | 47.63%  |
| All in one     | 341       | 1.36%   |
| Server         | 284       | 1.13%   |
| Mini pc        | 197       | 0.78%   |
| Convertible    | 118       | 0.47%   |
| Tablet         | 101       | 0.4%    |
| System on chip | 62        | 0.25%   |
| Phone          | 6         | 0.02%   |
| Stick pc       | 2         | 0.01%   |
| Firewall       | 1         | 0.004%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 24531     | 97.27%  |
| Enabled  | 689       | 2.73%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25129     | 99.93%  |
| Yes  | 18        | 0.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 6861      | 26.39%  |
| 4.01-8.0        | 5547      | 21.34%  |
| 8.01-16.0       | 4589      | 17.65%  |
| 16.01-24.0      | 2977      | 11.45%  |
| 1.01-2.0        | 2570      | 9.89%   |
| 2.01-3.0        | 1461      | 5.62%   |
| 32.01-64.0      | 960       | 3.69%   |
| 0.51-1.0        | 434       | 1.67%   |
| 64.01-256.0     | 292       | 1.12%   |
| 24.01-32.0      | 212       | 0.82%   |
| More than 256.0 | 53        | 0.2%    |
| 0.01-0.5        | 34        | 0.13%   |
| Unknown         | 7         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 10878     | 38.27%  |
| 0.51-1.0        | 8841      | 31.11%  |
| 2.01-3.0        | 3955      | 13.92%  |
| 4.01-8.0        | 1771      | 6.23%   |
| 3.01-4.0        | 1670      | 5.88%   |
| 0.01-0.5        | 634       | 2.23%   |
| 8.01-16.0       | 481       | 1.69%   |
| 16.01-24.0      | 77        | 0.27%   |
| Unknown         | 35        | 0.12%   |
| 32.01-64.0      | 32        | 0.11%   |
| 24.01-32.0      | 29        | 0.1%    |
| 64.01-256.0     | 14        | 0.05%   |
| More than 256.0 | 5         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 16492     | 62.79%  |
| 2       | 6173      | 23.5%   |
| 3       | 2017      | 7.68%   |
| 4       | 802       | 3.05%   |
| 5       | 337       | 1.28%   |
| 0       | 196       | 0.75%   |
| 6       | 110       | 0.42%   |
| 7       | 45        | 0.17%   |
| 8       | 38        | 0.14%   |
| 9       | 13        | 0.05%   |
| Unknown | 9         | 0.03%   |
| 10      | 8         | 0.03%   |
| 11      | 6         | 0.02%   |
| 28      | 3         | 0.01%   |
| 17      | 3         | 0.01%   |
| 16      | 2         | 0.01%   |
| 12      | 2         | 0.01%   |
| 209     | 1         | 0.004%  |
| 27      | 1         | 0.004%  |
| 25      | 1         | 0.004%  |
| 24      | 1         | 0.004%  |
| 21      | 1         | 0.004%  |
| 19      | 1         | 0.004%  |
| 18      | 1         | 0.004%  |
| 15      | 1         | 0.004%  |
| 13      | 1         | 0.004%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 13906     | 54.32%  |
| Yes       | 11694     | 45.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23130     | 91.88%  |
| No        | 2043      | 8.12%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15361     | 60.54%  |
| No        | 10014     | 39.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 14712     | 57.69%  |
| Yes       | 10788     | 42.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 25147     | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Moscow           | 5162      | 19.17%  |
| St Petersburg    | 2159      | 8.02%   |
| Voronezh         | 1183      | 4.39%   |
| Novosibirsk      | 806       | 2.99%   |
| Pecherskoye      | 765       | 2.84%   |
| Krasnodar        | 692       | 2.57%   |
| Yekaterinburg    | 687       | 2.55%   |
| Nizhniy Novgorod | 517       | 1.92%   |
| Samara           | 501       | 1.86%   |
| Perm             | 444       | 1.65%   |
| Rostov-on-Don    | 441       | 1.64%   |
| Chelyabinsk      | 411       | 1.53%   |
| Krasnoyarsk      | 317       | 1.18%   |
| Kazan’         | 292       | 1.08%   |
| Saratov          | 291       | 1.08%   |
| Ufa              | 264       | 0.98%   |
| Omsk             | 262       | 0.97%   |
| Volgograd        | 235       | 0.87%   |
| Tyumen           | 216       | 0.8%    |
| Khabarovsk       | 216       | 0.8%    |
| Vladivostok      | 214       | 0.79%   |
| Barnaul          | 209       | 0.78%   |
| Irkutsk          | 200       | 0.74%   |
| Stavropol        | 199       | 0.74%   |
| Yaroslavl        | 164       | 0.61%   |
| Kaliningrad      | 157       | 0.58%   |
| Ulyanovsk        | 155       | 0.58%   |
| Tomsk            | 152       | 0.56%   |
| Kemerovo         | 150       | 0.56%   |
| Tula             | 147       | 0.55%   |
| Belgorod         | 147       | 0.55%   |
| Orenburg         | 143       | 0.53%   |
| Ryazan           | 136       | 0.51%   |
| Kirov            | 136       | 0.51%   |
| Bryansk          | 132       | 0.49%   |
| Novokuznetsk     | 127       | 0.47%   |
| Surgut           | 125       | 0.46%   |
| Izhevsk          | 124       | 0.46%   |
| Tolyatti         | 121       | 0.45%   |
| Penza            | 117       | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7608      | 12340  | 21.08%  |
| Seagate             | 7283      | 11207  | 20.18%  |
| Samsung Electronics | 3240      | 4784   | 8.98%   |
| Toshiba             | 2868      | 4044   | 7.95%   |
| Hitachi             | 2043      | 2785   | 5.66%   |
| Kingston            | 1860      | 2461   | 5.15%   |
| Unknown             | 851       | 1128   | 2.36%   |
| HGST                | 785       | 1184   | 2.17%   |
| SanDisk             | 757       | 1013   | 2.1%    |
| Intel               | 639       | 984    | 1.77%   |
| A-DATA Technology   | 637       | 952    | 1.76%   |
| China               | 578       | 786    | 1.6%    |
| Crucial             | 455       | 598    | 1.26%   |
| SPCC                | 451       | 590    | 1.25%   |
| SK hynix            | 444       | 563    | 1.23%   |
| OCZ                 | 330       | 419    | 0.91%   |
| Apacer              | 318       | 407    | 0.88%   |
| Plextor             | 287       | 416    | 0.8%    |
| Maxtor              | 284       | 359    | 0.79%   |
| Micron Technology   | 224       | 325    | 0.62%   |
| Smartbuy            | 223       | 286    | 0.62%   |
| Fujitsu             | 196       | 247    | 0.54%   |
| Transcend           | 190       | 239    | 0.53%   |
| KingSpec            | 178       | 222    | 0.49%   |
| AMD                 | 172       | 214    | 0.48%   |
| Patriot             | 171       | 216    | 0.47%   |
| HUAWEI              | 161       | 196    | 0.45%   |
| Netac               | 150       | 246    | 0.42%   |
| Silicon Motion      | 146       | 179    | 0.4%    |
| GOODRAM             | 120       | 159    | 0.33%   |
| Phison              | 116       | 132    | 0.32%   |
| KIOXIA              | 116       | 144    | 0.32%   |
| Corsair             | 113       | 161    | 0.31%   |
| Gigabyte Technology | 96        | 115    | 0.27%   |
| Unknown             | 88        | 97     | 0.24%   |
| KingDian            | 77        | 117    | 0.21%   |
| JMicron Technology  | 72        | 76     | 0.2%    |
| Apple               | 69        | 90     | 0.19%   |
| XPG                 | 62        | 80     | 0.17%   |
| XrayDisk            | 61        | 79     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB    | 413       | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 302       | 0.76%   |
| Seagate ST500LT012-1DG142 500GB    | 296       | 0.75%   |
| Toshiba DT01ACA050 500GB           | 292       | 0.74%   |
| Toshiba MQ01ABF050 500GB           | 291       | 0.74%   |
| Kingston SA400S37240G 240GB SSD    | 270       | 0.68%   |
| Seagate ST1000DM010-2EP102 1TB     | 266       | 0.67%   |
| Seagate ST3500418AS 500GB          | 258       | 0.65%   |
| Toshiba HDWD110 1TB                | 256       | 0.65%   |
| Kingston SA400S37120G 120GB SSD    | 256       | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB           | 234       | 0.59%   |
| Seagate ST9500325AS 500GB          | 234       | 0.59%   |
| Kingston SV300S37A120G 120GB SSD   | 219       | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 214       | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB     | 209       | 0.53%   |
| Toshiba DT01ACA100 1TB             | 208       | 0.53%   |
| Samsung SSD 860 EVO 250GB          | 206       | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB     | 203       | 0.51%   |
| Seagate ST9320325AS 320GB          | 185       | 0.47%   |
| HGST HTS545050A7E680 500GB         | 179       | 0.45%   |
| WDC WDS120G2G0A-00JH30 128GB SSD   | 162       | 0.41%   |
| Toshiba MQ01ABD100 1TB             | 152       | 0.38%   |
| WDC WD5000AAKX-001CA0 500GB        | 140       | 0.35%   |
| Seagate ST3250410AS 250GB          | 139       | 0.35%   |
| Samsung SSD 860 EVO 500GB          | 133       | 0.34%   |
| Seagate ST380011A 80GB             | 131       | 0.33%   |
| Seagate ST380815AS 80GB            | 129       | 0.33%   |
| Seagate ST31000528AS 1TB           | 125       | 0.32%   |
| Toshiba MQ04ABF100 1TB             | 124       | 0.31%   |
| Seagate ST31000524AS 1TB           | 124       | 0.31%   |
| Hitachi HTS543232A7A384 320GB      | 124       | 0.31%   |
| Seagate ST1000DM003-1ER162 1TB     | 123       | 0.31%   |
| Seagate ST500LT012-9WS142 500GB    | 122       | 0.31%   |
| SPCC Solid State Disk 120GB        | 120       | 0.3%    |
| Seagate ST3160815AS 160GB          | 120       | 0.3%    |
| Seagate ST9250315AS 250GB          | 119       | 0.3%    |
| Hitachi HDS721050CLA362 500GB      | 119       | 0.3%    |
| HGST HTS545050A7E380 500GB         | 119       | 0.3%    |
| HGST HTS721010A9E630 1TB           | 118       | 0.3%    |
| Seagate ST3250310AS 250GB          | 116       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7253      | 11140  | 34.23%  |
| WDC                 | 6805      | 10785  | 32.12%  |
| Toshiba             | 2634      | 3695   | 12.43%  |
| Hitachi             | 2043      | 2785   | 9.64%   |
| Samsung Electronics | 1003      | 1391   | 4.73%   |
| HGST                | 785       | 1184   | 3.7%    |
| Maxtor              | 282       | 357    | 1.33%   |
| Fujitsu             | 194       | 245    | 0.92%   |
| Unknown             | 56        | 77     | 0.26%   |
| Apple               | 23        | 30     | 0.11%   |
| IBM/Hitachi         | 18        | 21     | 0.08%   |
| Hewlett-Packard     | 14        | 40     | 0.07%   |
| USB3.0              | 5         | 5      | 0.02%   |
| IBM                 | 5         | 5      | 0.02%   |
| PHD 3.0             | 4         | 4      | 0.02%   |
| Lenovo              | 4         | 35     | 0.02%   |
| HGST HTS            | 4         | 4      | 0.02%   |
| ASMT                | 4         | 15     | 0.02%   |
| ASMedia             | 4         | 5      | 0.02%   |
| WD MediaMax         | 3         | 4      | 0.01%   |
| Quantum             | 3         | 3      | 0.01%   |
| KESU                | 3         | 3      | 0.01%   |
| CLOVER              | 3         | 3      | 0.01%   |
| Unknown             | 3         | 3      | 0.01%   |
| Synology            | 2         | 3      | 0.01%   |
| SCST_BIO            | 2         | 6      | 0.01%   |
| MARSHAL             | 2         | 2      | 0.01%   |
| LIO-ORG             | 2         | 2      | 0.01%   |
| HPE                 | 2         | 2      | 0.01%   |
| ExcelStor           | 2         | 2      | 0.01%   |
| ASMT106x            | 2         | 3      | 0.01%   |
| ZALMAN              | 1         | 1      | 0.005%  |
| VSTORAGE            | 1         | 1      | 0.005%  |
| USB 3.0             | 1         | 1      | 0.005%  |
| StoreJet            | 1         | 1      | 0.005%  |
| SILICONMOTION       | 1         | 1      | 0.005%  |
| Silicon             | 1         | 1      | 0.005%  |
| SAGE                | 1         | 1      | 0.005%  |
| QNAP                | 1         | 2      | 0.005%  |
| Pioneer             | 1         | 1      | 0.005%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1573      | 2078   | 15.75%  |
| Samsung Electronics | 1280      | 1880   | 12.82%  |
| WDC                 | 760       | 981    | 7.61%   |
| China               | 574       | 782    | 5.75%   |
| A-DATA Technology   | 533       | 792    | 5.34%   |
| SanDisk             | 478       | 666    | 4.79%   |
| Crucial             | 439       | 576    | 4.4%    |
| SPCC                | 428       | 561    | 4.29%   |
| Intel               | 337       | 565    | 3.38%   |
| OCZ                 | 329       | 418    | 3.29%   |
| Plextor             | 269       | 376    | 2.69%   |
| Apacer              | 266       | 342    | 2.66%   |
| Smartbuy            | 211       | 272    | 2.11%   |
| Transcend           | 178       | 219    | 1.78%   |
| KingSpec            | 177       | 221    | 1.77%   |
| Patriot             | 161       | 205    | 1.61%   |
| Toshiba             | 157       | 214    | 1.57%   |
| AMD                 | 156       | 189    | 1.56%   |
| Netac               | 117       | 203    | 1.17%   |
| GOODRAM             | 115       | 154    | 1.15%   |
| Corsair             | 106       | 150    | 1.06%   |
| Micron Technology   | 101       | 159    | 1.01%   |
| SK hynix            | 89        | 109    | 0.89%   |
| KingDian            | 76        | 116    | 0.76%   |
| Gigabyte Technology | 62        | 70     | 0.62%   |
| XrayDisk            | 49        | 64     | 0.49%   |
| Kingmax             | 47        | 86     | 0.47%   |
| Foxline             | 43        | 51     | 0.43%   |
| Unknown             | 42        | 47     | 0.42%   |
| Apple               | 36        | 43     | 0.36%   |
| LITEON              | 34        | 42     | 0.34%   |
| Hewlett-Packard     | 30        | 44     | 0.3%    |
| LITEONIT            | 29        | 48     | 0.29%   |
| AXIOMTEK            | 28        | 30     | 0.28%   |
| Qumo                | 27        | 35     | 0.27%   |
| Londisk             | 26        | 30     | 0.26%   |
| KingFast            | 24        | 30     | 0.24%   |
| TO Exter            | 23        | 27     | 0.23%   |
| Team                | 23        | 27     | 0.23%   |
| Zheino              | 21        | 28     | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 17899     | 31882  | 56.41%  |
| SSD     | 8790      | 13629  | 27.7%   |
| NVMe    | 3787      | 5317   | 11.93%  |
| MMC     | 832       | 1122   | 2.62%   |
| Unknown | 425       | 692    | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22074     | 44992  | 80.39%  |
| NVMe | 3751      | 5258   | 13.66%  |
| MMC  | 832       | 1122   | 3.03%   |
| SAS  | 803       | 1270   | 2.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 18492     | 31413  | 68.56%  |
| 0.51-1.0        | 6629      | 10758  | 24.58%  |
| 1.01-2.0        | 1198      | 2076   | 4.44%   |
| 2.01-3.0        | 262       | 461    | 0.97%   |
| 3.01-4.0        | 219       | 392    | 0.81%   |
| 4.01-10.0       | 136       | 331    | 0.5%    |
| 10.01-20.0      | 25        | 69     | 0.09%   |
| More than 100.0 | 7         | 8      | 0.03%   |
| 0               | 2         | 2      | 0.01%   |
| 20.01-50.0      | 1         | 1      | 0.004%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 7575      | 27.17%  |
| 251-500        | 5972      | 21.42%  |
| 501-1000       | 3245      | 11.64%  |
| 1-20           | 2997      | 10.75%  |
| 51-100         | 2652      | 9.51%   |
| 21-50          | 1801      | 6.46%   |
| 1001-2000      | 1553      | 5.57%   |
| Unknown        | 1129      | 4.05%   |
| 2001-3000      | 494       | 1.77%   |
| More than 3000 | 462       | 1.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 15409     | 54.59%  |
| 21-50          | 3418      | 12.11%  |
| 101-250        | 2453      | 8.69%   |
| 51-100         | 2215      | 7.85%   |
| 251-500        | 1651      | 5.85%   |
| Unknown        | 1129      | 4%      |
| 501-1000       | 1066      | 3.78%   |
| 1001-2000      | 548       | 1.94%   |
| More than 3000 | 185       | 0.66%   |
| 2001-3000      | 151       | 0.53%   |
| 0              | 2         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 160       | 214    | 1.81%   |
| Seagate ST500DM002-1BD142 500GB    | 159       | 200    | 1.8%    |
| Seagate ST3500418AS 500GB          | 113       | 145    | 1.28%   |
| Seagate ST500LT012-9WS142 500GB    | 110       | 130    | 1.25%   |
| Seagate ST9320325AS 320GB          | 100       | 126    | 1.13%   |
| Seagate ST3250410AS 250GB          | 92        | 117    | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 86        | 103    | 0.98%   |
| Seagate ST9250315AS 250GB          | 84        | 103    | 0.95%   |
| Seagate ST500LT012-1DG142 500GB    | 82        | 100    | 0.93%   |
| HGST HTS545050A7E680 500GB         | 79        | 117    | 0.9%    |
| WDC WD5000AAKX-001CA0 500GB        | 69        | 87     | 0.78%   |
| Seagate ST3250310AS 250GB          | 68        | 112    | 0.77%   |
| Seagate ST320LT020-9YG142 320GB    | 63        | 90     | 0.71%   |
| Seagate ST3320613AS 320GB          | 62        | 83     | 0.7%    |
| Seagate ST31000528AS 1TB           | 58        | 68     | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB     | 58        | 89     | 0.66%   |
| Seagate ST1000DM003-9YN162 1TB     | 55        | 65     | 0.62%   |
| HGST HTS545050A7E380 500GB         | 53        | 84     | 0.6%    |
| Hitachi HTS543232A7A384 320GB      | 48        | 54     | 0.54%   |
| Hitachi HDS721050CLA362 500GB      | 48        | 57     | 0.54%   |
| Hitachi HTS545025B9A300 250GB      | 47        | 58     | 0.53%   |
| WDC WD5000AADS-00S9B0 500GB        | 46        | 53     | 0.52%   |
| Seagate ST380011A 80GB             | 45        | 48     | 0.51%   |
| Seagate ST250DM000-1BD141 250GB    | 45        | 60     | 0.51%   |
| Seagate ST31000524AS 1TB           | 44        | 57     | 0.5%    |
| Seagate ST3160815AS 160GB          | 43        | 54     | 0.49%   |
| Seagate ST320LT012-9WS14C 320GB    | 42        | 56     | 0.48%   |
| WDC WD3200AAJS-00L7A0 320GB        | 40        | 45     | 0.45%   |
| Seagate ST3250318AS 250GB          | 40        | 51     | 0.45%   |
| Kingston SV300S37A120G 120GB SSD   | 40        | 41     | 0.45%   |
| Hitachi HTS541612J9SA00 120GB      | 39        | 51     | 0.44%   |
| Hitachi HDS721010CLA332 1TB        | 39        | 46     | 0.44%   |
| Hitachi HTS547550A9E384 500GB      | 38        | 53     | 0.43%   |
| Hitachi HDS721616PLA380 160GB      | 38        | 52     | 0.43%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 37        | 58     | 0.42%   |
| WDC WD10EARS-00Y5B1 1TB            | 37        | 61     | 0.42%   |
| Toshiba MQ01ABF050 500GB           | 37        | 50     | 0.42%   |
| Toshiba MQ01ABD050 500GB           | 37        | 44     | 0.42%   |
| Seagate ST380815AS 80GB            | 36        | 48     | 0.41%   |
| Seagate ST3160811AS 160GB          | 36        | 52     | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2897      | 4013   | 34.43%  |
| WDC                 | 2075      | 2885   | 24.66%  |
| Hitachi             | 1002      | 1315   | 11.91%  |
| Toshiba             | 616       | 806    | 7.32%   |
| Samsung Electronics | 528       | 717    | 6.28%   |
| HGST                | 218       | 322    | 2.59%   |
| Maxtor              | 164       | 195    | 1.95%   |
| Kingston            | 149       | 171    | 1.77%   |
| OCZ                 | 69        | 87     | 0.82%   |
| SanDisk             | 64        | 78     | 0.76%   |
| Intel               | 59        | 85     | 0.7%    |
| A-DATA Technology   | 55        | 77     | 0.65%   |
| Fujitsu             | 54        | 71     | 0.64%   |
| SPCC                | 50        | 58     | 0.59%   |
| Corsair             | 37        | 52     | 0.44%   |
| China               | 29        | 37     | 0.34%   |
| SK hynix            | 28        | 38     | 0.33%   |
| KingSpec            | 28        | 32     | 0.33%   |
| Kingmax             | 27        | 48     | 0.32%   |
| Plextor             | 21        | 34     | 0.25%   |
| Crucial             | 21        | 34     | 0.25%   |
| AMD                 | 19        | 24     | 0.23%   |
| IBM/Hitachi         | 16        | 19     | 0.19%   |
| Netac               | 12        | 13     | 0.14%   |
| LITEON              | 12        | 14     | 0.14%   |
| Micron Technology   | 11        | 19     | 0.13%   |
| LITEONIT            | 10        | 16     | 0.12%   |
| Unknown             | 10        | 12     | 0.12%   |
| OCZ-VERTEX3         | 8         | 13     | 0.1%    |
| Transcend           | 7         | 7      | 0.08%   |
| KingDian            | 7         | 11     | 0.08%   |
| Neo                 | 6         | 12     | 0.07%   |
| Smartbuy            | 5         | 6      | 0.06%   |
| Apple               | 5         | 6      | 0.06%   |
| Apacer              | 5         | 5      | 0.06%   |
| SSSTC               | 4         | 5      | 0.05%   |
| XrayDisk            | 3         | 5      | 0.04%   |
| XPG                 | 3         | 6      | 0.04%   |
| Team                | 3         | 3      | 0.04%   |
| Silicon Motion      | 3         | 4      | 0.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2896      | 4010   | 38.74%  |
| WDC                 | 2017      | 2803   | 26.98%  |
| Hitachi             | 1002      | 1315   | 13.4%   |
| Toshiba             | 609       | 799    | 8.15%   |
| Samsung Electronics | 480       | 658    | 6.42%   |
| HGST                | 218       | 322    | 2.92%   |
| Maxtor              | 164       | 195    | 2.19%   |
| Fujitsu             | 54        | 71     | 0.72%   |
| IBM/Hitachi         | 16        | 19     | 0.21%   |
| IBM                 | 3         | 3      | 0.04%   |
| Hewlett-Packard     | 3         | 4      | 0.04%   |
| Quantum             | 2         | 2      | 0.03%   |
| MARSHAL             | 2         | 2      | 0.03%   |
| HGST HTS            | 2         | 2      | 0.03%   |
| ASMT                | 2         | 4      | 0.03%   |
| Apple               | 2         | 3      | 0.03%   |
| WD MediaMax         | 1         | 1      | 0.01%   |
| ExcelStor           | 1         | 1      | 0.01%   |
| ASMedia             | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6860      | 10216  | 88.06%  |
| SSD  | 881       | 1157   | 11.31%  |
| NVMe | 49        | 70     | 0.63%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST31000528AS 1TB           | 7         | 9      | 2.49%   |
| Seagate ST31000524AS 1TB           | 7         | 9      | 2.49%   |
| Hitachi HDS721010DLE630 1TB        | 6         | 7      | 2.14%   |
| Seagate ST9500325AS 500GB          | 5         | 5      | 1.78%   |
| Seagate ST3500418AS 500GB          | 5         | 6      | 1.78%   |
| Seagate ST3500412AS 500GB          | 5         | 6      | 1.78%   |
| Samsung Electronics HM321HI 320GB  | 5         | 7      | 1.78%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 4         | 5      | 1.42%   |
| Seagate ST9320325AS 320GB          | 4         | 5      | 1.42%   |
| HGST HTS721010A9E630 1TB           | 4         | 5      | 1.42%   |
| HGST HTS545050A7E680 500GB         | 4         | 4      | 1.42%   |
| HGST HTS545050A7E380 500GB         | 4         | 4      | 1.42%   |
| WDC WD1600BEVS-22RST0 160GB        | 3         | 4      | 1.07%   |
| Toshiba MQ01ABD050 500GB           | 3         | 3      | 1.07%   |
| Toshiba MK6465GSX 640GB            | 3         | 3      | 1.07%   |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 1.07%   |
| Seagate ST31000333AS 1TB           | 3         | 3      | 1.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 1.07%   |
| Samsung Electronics SP0411N 40GB   | 3         | 4      | 1.07%   |
| Maxtor 6Y080L0 82GB                | 3         | 3      | 1.07%   |
| Hitachi HTS547550A9E384 500GB      | 3         | 3      | 1.07%   |
| Hitachi HDS721010CLA332 1TB        | 3         | 3      | 1.07%   |
| WDC WD5000AAKS-00V1A0 500GB        | 2         | 2      | 0.71%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 2         | 2      | 0.71%   |
| WDC WD3200AAJS-00L7A0 320GB        | 2         | 2      | 0.71%   |
| WDC WD20EARS-00MVWB0 2TB           | 2         | 2      | 0.71%   |
| WDC WD15EARS-00MVWB0 1TB           | 2         | 4      | 0.71%   |
| Toshiba MK3259GSXP 320GB           | 2         | 2      | 0.71%   |
| Seagate STM3500418AS 500GB         | 2         | 2      | 0.71%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 0.71%   |
| Seagate ST500DM005 HD502HJ 500GB   | 2         | 3      | 0.71%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 2      | 0.71%   |
| Seagate ST500DM002-1BC142 500GB    | 2         | 2      | 0.71%   |
| Seagate ST3750528AS 752GB          | 2         | 2      | 0.71%   |
| Seagate ST3320613AS 320GB          | 2         | 3      | 0.71%   |
| Seagate ST3250318AS 250GB          | 2         | 2      | 0.71%   |
| Seagate ST32000542AS 2TB           | 2         | 4      | 0.71%   |
| Seagate ST3160318AS 160GB          | 2         | 2      | 0.71%   |
| Seagate ST250DM000-1BD141 250GB    | 2         | 2      | 0.71%   |
| Samsung Electronics HM160HI 160GB  | 2         | 2      | 0.71%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 84        | 101    | 30.11%  |
| WDC                 | 75        | 92     | 26.88%  |
| Samsung Electronics | 36        | 39     | 12.9%   |
| Hitachi             | 27        | 30     | 9.68%   |
| Toshiba             | 23        | 25     | 8.24%   |
| HGST                | 16        | 18     | 5.73%   |
| Maxtor              | 7         | 7      | 2.51%   |
| Transcend           | 1         | 1      | 0.36%   |
| OCZ                 | 1         | 1      | 0.36%   |
| Intel               | 1         | 1      | 0.36%   |
| IBM-ESXS            | 1         | 2      | 0.36%   |
| Hewlett-Packard     | 1         | 1      | 0.36%   |
| GOODRAM             | 1         | 1      | 0.36%   |
| Fujitsu             | 1         | 1      | 0.36%   |
| Crucial             | 1         | 1      | 0.36%   |
| Corsair             | 1         | 1      | 0.36%   |
| Apple               | 1         | 2      | 0.36%   |
| A-DATA Technology   | 1         | 1      | 0.36%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 16327     | 31276  | 55.39%  |
| Malfunc  | 7574      | 11443  | 25.7%   |
| Detected | 5297      | 9597   | 17.97%  |
| Failed   | 275       | 325    | 0.93%   |
| Limited  | 1         | 1      | 0.003%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 17307     | 58.31%  |
| AMD                              | 5434      | 18.31%  |
| Samsung Electronics              | 1116      | 3.76%   |
| Nvidia                           | 915       | 3.08%   |
| JMicron Technology               | 826       | 2.78%   |
| Sandisk                          | 471       | 1.59%   |
| Marvell Technology Group         | 447       | 1.51%   |
| ASMedia Technology               | 409       | 1.38%   |
| SK hynix                         | 339       | 1.14%   |
| Kingston Technology Company      | 325       | 1.09%   |
| Phison Electronics               | 296       | 1%      |
| Silicon Motion                   | 245       | 0.83%   |
| VIA Technologies                 | 226       | 0.76%   |
| Micron Technology                | 132       | 0.44%   |
| KIOXIA                           | 128       | 0.43%   |
| Toshiba America Info Systems     | 116       | 0.39%   |
| ADATA Technology                 | 116       | 0.39%   |
| Silicon Integrated Systems [SiS] | 115       | 0.39%   |
| Realtek Semiconductor            | 94        | 0.32%   |
| Union Memory (Shenzhen)          | 67        | 0.23%   |
| LSI Logic / Symbios Logic        | 55        | 0.19%   |
| Solid State Storage Technology   | 49        | 0.17%   |
| Broadcom / LSI                   | 49        | 0.17%   |
| Silicon Image                    | 39        | 0.13%   |
| INNOGRIT                         | 39        | 0.13%   |
| Lite-On Technology               | 37        | 0.12%   |
| MAXIO Technology (Hangzhou)      | 31        | 0.1%    |
| Integrated Technology Express    | 31        | 0.1%    |
| Adaptec                          | 31        | 0.1%    |
| Shenzhen Longsys Electronics     | 28        | 0.09%   |
| Micron/Crucial Technology        | 28        | 0.09%   |
| Netac Technology                 | 27        | 0.09%   |
| Hewlett-Packard                  | 27        | 0.09%   |
| Yangtze Memory Technologies      | 9         | 0.03%   |
| Apple                            | 8         | 0.03%   |
| Lenovo                           | 6         | 0.02%   |
| ULi Electronics                  | 5         | 0.02%   |
| Seagate Technology               | 5         | 0.02%   |
| O2 Micro                         | 5         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 5         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 2841      | 7.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1482      | 3.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1413      | 3.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1195      | 3.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1190      | 3.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1068      | 2.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 996       | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 961       | 2.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 823       | 2.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 741       | 1.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 662       | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 646       | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 611       | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 610       | 1.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 559       | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 534       | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 519       | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 486       | 1.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 478       | 1.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 474       | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 468       | 1.25%   |
| Nvidia MCP61 SATA Controller                                                            | 405       | 1.08%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 391       | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 391       | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 390       | 1.04%   |
| Nvidia MCP61 IDE                                                                        | 378       | 1.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 341       | 0.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 337       | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 316       | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 314       | 0.84%   |
| Samsung NVMe SSD Controller 980                                                         | 306       | 0.82%   |
| JMicron JMB368 IDE controller                                                           | 305       | 0.81%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 298       | 0.8%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 296       | 0.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 288       | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 270       | 0.72%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 268       | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 262       | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 244       | 0.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 234       | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 18175     | 59.54%  |
| IDE  | 7580      | 24.83%  |
| NVMe | 3783      | 12.39%  |
| RAID | 891       | 2.92%   |
| SAS  | 78        | 0.26%   |
| SCSI | 20        | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 18356     | 72.99%  |
| AMD          | 6697      | 26.63%  |
| ARM          | 65        | 0.26%   |
| CentaurHauls | 9         | 0.04%   |
| QUALCOMM     | 6         | 0.02%   |
| Unknown      | 5         | 0.02%   |
| HiSilicon    | 4         | 0.02%   |
| PowerMac7,2  | 1         | 0.004%  |
| PowerBook5,6 | 1         | 0.004%  |
| MIPS         | 1         | 0.004%  |
| MBE8C-PC     | 1         | 0.004%  |
| Loongson     | 1         | 0.004%  |
| Elbrus-MCST  | 1         | 0.004%  |
| E8C/EATX     | 1         | 0.004%  |
| E8C-SWTX     | 1         | 0.004%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 168       | 0.66%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 168       | 0.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 154       | 0.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 154       | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 153       | 0.6%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 151       | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 143       | 0.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 130       | 0.51%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 123       | 0.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 123       | 0.49%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 121       | 0.48%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 121       | 0.48%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 117       | 0.46%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 116       | 0.46%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 116       | 0.46%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 115       | 0.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 114       | 0.45%   |
| Intel Pentium 4 CPU 3.00GHz                   | 113       | 0.45%   |
| AMD Ryzen 5 3600 6-Core Processor             | 111       | 0.44%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 110       | 0.43%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 110       | 0.43%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 108       | 0.43%   |
| AMD FX-6300 Six-Core Processor                | 107       | 0.42%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 106       | 0.42%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 106       | 0.42%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 103       | 0.41%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 103       | 0.41%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 102       | 0.4%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 100       | 0.39%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 97        | 0.38%   |
| AMD Athlon II X2 250 Processor                | 95        | 0.38%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 92        | 0.36%   |
| AMD FX-8350 Eight-Core Processor              | 92        | 0.36%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 91        | 0.36%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 91        | 0.36%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 90        | 0.36%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 89        | 0.35%   |
| AMD E-450 APU with Radeon HD Graphics         | 88        | 0.35%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 87        | 0.34%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 86        | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 4112      | 16.26%  |
| Intel Core i3           | 2893      | 11.44%  |
| Intel Core i7           | 1876      | 7.42%   |
| Intel Celeron           | 1742      | 6.89%   |
| Intel Pentium           | 1586      | 6.27%   |
| Intel Core 2 Duo        | 1410      | 5.58%   |
| AMD Ryzen 5             | 1087      | 4.3%    |
| Intel Atom              | 921       | 3.64%   |
| Other                   | 785       | 3.1%    |
| Intel Xeon              | 737       | 2.92%   |
| AMD FX                  | 637       | 2.52%   |
| Intel Pentium Dual-Core | 601       | 2.38%   |
| AMD Ryzen 7             | 481       | 1.9%    |
| AMD Athlon 64 X2        | 438       | 1.73%   |
| Intel Core 2 Quad       | 354       | 1.4%    |
| AMD Athlon II X2        | 331       | 1.31%   |
| AMD A6                  | 329       | 1.3%    |
| AMD Ryzen 3             | 312       | 1.23%   |
| AMD A8                  | 273       | 1.08%   |
| AMD A4                  | 270       | 1.07%   |
| AMD A10                 | 263       | 1.04%   |
| Intel Pentium 4         | 259       | 1.02%   |
| Intel Pentium Dual      | 244       | 0.97%   |
| Intel Core 2            | 233       | 0.92%   |
| AMD Phenom II X4        | 207       | 0.82%   |
| AMD E                   | 170       | 0.67%   |
| AMD Athlon II X4        | 152       | 0.6%    |
| Intel Genuine           | 144       | 0.57%   |
| AMD E1                  | 129       | 0.51%   |
| AMD Athlon              | 121       | 0.48%   |
| AMD E2                  | 120       | 0.47%   |
| AMD Athlon II X3        | 119       | 0.47%   |
| Intel Pentium D         | 108       | 0.43%   |
| Intel Pentium Gold      | 101       | 0.4%    |
| AMD Phenom              | 100       | 0.4%    |
| Intel Pentium Silver    | 97        | 0.38%   |
| AMD Ryzen 9             | 93        | 0.37%   |
| AMD Athlon 64           | 92        | 0.36%   |
| AMD Phenom II X6        | 83        | 0.33%   |
| Intel Celeron M         | 78        | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 12546     | 49.09%  |
| 4       | 7132      | 27.91%  |
| 6       | 1741      | 6.81%   |
| 1       | 1369      | 5.36%   |
| Unknown | 1106      | 4.33%   |
| 8       | 855       | 3.35%   |
| 3       | 337       | 1.32%   |
| 12      | 168       | 0.66%   |
| 16      | 74        | 0.29%   |
| 10      | 70        | 0.27%   |
| 24      | 47        | 0.18%   |
| 14      | 32        | 0.13%   |
| 20      | 19        | 0.07%   |
| 32      | 18        | 0.07%   |
| 28      | 14        | 0.05%   |
| 18      | 5         | 0.02%   |
| 96      | 4         | 0.02%   |
| 40      | 4         | 0.02%   |
| 36      | 3         | 0.01%   |
| 56      | 2         | 0.01%   |
| 48      | 2         | 0.01%   |
| 192     | 1         | 0.004%  |
| 128     | 1         | 0.004%  |
| 80      | 1         | 0.004%  |
| 72      | 1         | 0.004%  |
| 22      | 1         | 0.004%  |
| 15      | 1         | 0.004%  |
| 5       | 1         | 0.004%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 24857     | 98.78%  |
| 2       | 257       | 1.02%   |
| Unknown | 38        | 0.15%   |
| 4       | 8         | 0.03%   |
| 3       | 2         | 0.01%   |
| 8       | 1         | 0.004%  |
| 0       | 1         | 0.004%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 12254     | 47.99%  |
| 2       | 12172     | 47.66%  |
| Unknown | 1106      | 4.33%   |
| 8       | 2         | 0.01%   |
| 6       | 2         | 0.01%   |
| 4       | 1         | 0.004%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 24360     | 96.74%  |
| 32-bit         | 567       | 2.25%   |
| Unknown        | 239       | 0.95%   |
| 64-bit         | 16        | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2771      | 10.74%  |
| 0x206a7    | 2290      | 8.88%   |
| 0x306a9    | 1941      | 7.52%   |
| 0x1067a    | 1534      | 5.95%   |
| 0x306c3    | 1101      | 4.27%   |
| 0x010000c8 | 638       | 2.47%   |
| 0x6fd      | 619       | 2.4%    |
| 0x20655    | 574       | 2.22%   |
| 0x906ea    | 538       | 2.09%   |
| 0x506e3    | 476       | 1.84%   |
| 0x10676    | 436       | 1.69%   |
| 0x906e9    | 407       | 1.58%   |
| 0x06001119 | 400       | 1.55%   |
| 0x106ca    | 376       | 1.46%   |
| 0x30678    | 342       | 1.33%   |
| 0x806ec    | 338       | 1.31%   |
| 0x40651    | 321       | 1.24%   |
| 0x806ea    | 315       | 1.22%   |
| 0x08108109 | 290       | 1.12%   |
| 0x6fb      | 283       | 1.1%    |
| 0x406c4    | 265       | 1.03%   |
| 0x406e3    | 259       | 1%      |
| 0x806e9    | 257       | 1%      |
| 0x806c1    | 256       | 0.99%   |
| 0x06000852 | 234       | 0.91%   |
| 0xa0653    | 232       | 0.9%    |
| 0x20652    | 223       | 0.86%   |
| 0x03000027 | 216       | 0.84%   |
| 0x306d4    | 192       | 0.74%   |
| 0x05000119 | 189       | 0.73%   |
| 0x0800820d | 178       | 0.69%   |
| 0x08701021 | 171       | 0.66%   |
| 0x0600084f | 171       | 0.66%   |
| 0x0a50000c | 163       | 0.63%   |
| 0x6f6      | 161       | 0.62%   |
| 0x07030105 | 160       | 0.62%   |
| 0x506c9    | 159       | 0.62%   |
| 0x906eb    | 155       | 0.6%    |
| 0x30661    | 153       | 0.59%   |
| 0x106e5    | 153       | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 2513      | 9.94%   |
| KabyLake         | 2459      | 9.72%   |
| IvyBridge        | 2154      | 8.52%   |
| Penryn           | 2021      | 7.99%   |
| Haswell          | 1637      | 6.47%   |
| Core             | 1457      | 5.76%   |
| K10              | 1248      | 4.93%   |
| Piledriver       | 936       | 3.7%    |
| Westmere         | 897       | 3.55%   |
| Skylake          | 886       | 3.5%    |
| Silvermont       | 840       | 3.32%   |
| Zen+             | 667       | 2.64%   |
| K8 Hammer        | 663       | 2.62%   |
| Bonnell          | 645       | 2.55%   |
| Unknown          | 616       | 2.44%   |
| Zen 2            | 565       | 2.23%   |
| NetBurst         | 485       | 1.92%   |
| CometLake        | 417       | 1.65%   |
| Zen              | 413       | 1.63%   |
| Zen 3            | 357       | 1.41%   |
| Excavator        | 353       | 1.4%    |
| TigerLake        | 325       | 1.29%   |
| Bobcat           | 291       | 1.15%   |
| Goldmont plus    | 274       | 1.08%   |
| Broadwell        | 269       | 1.06%   |
| K10 Llano        | 244       | 0.96%   |
| Nehalem          | 217       | 0.86%   |
| Puma             | 209       | 0.83%   |
| Goldmont         | 193       | 0.76%   |
| P6               | 191       | 0.76%   |
| IceLake          | 189       | 0.75%   |
| Bulldozer        | 144       | 0.57%   |
| Alderlake Hybrid | 133       | 0.53%   |
| Steamroller      | 129       | 0.51%   |
| Jaguar           | 123       | 0.49%   |
| K8 & K10 hybrid  | 71        | 0.28%   |
| Tremont          | 47        | 0.19%   |
| K6               | 11        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 11902     | 40.56%  |
| Nvidia                                       | 9673      | 32.97%  |
| AMD                                          | 7391      | 25.19%  |
| ASPEED Technology                            | 144       | 0.49%   |
| Matrox Electronics Systems                   | 142       | 0.48%   |
| Silicon Integrated Systems [SiS]             | 36        | 0.12%   |
| VIA Technologies                             | 27        | 0.09%   |
| ATI Technologies                             | 10        | 0.03%   |
| Huawei Technologies                          | 8         | 0.03%   |
| Zhaoxin                                      | 3         | 0.01%   |
| S3 Graphics                                  | 3         | 0.01%   |
| Silicon Motion                               | 2         | 0.01%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.003%  |
| Loongson Technology                          | 1         | 0.003%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1667      | 5.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1136      | 3.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 445       | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 428       | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 408       | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 407       | 1.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 390       | 1.26%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 360       | 1.16%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 359       | 1.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 354       | 1.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 333       | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 318       | 1.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 318       | 1.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 300       | 0.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 279       | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 275       | 0.89%   |
| AMD Renoir                                                                               | 275       | 0.89%   |
| Intel UHD Graphics 620                                                                   | 270       | 0.87%   |
| Intel HD Graphics 620                                                                    | 267       | 0.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 260       | 0.84%   |
| Nvidia GT218 [GeForce 210]                                                               | 258       | 0.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 256       | 0.83%   |
| Intel HD Graphics 630                                                                    | 247       | 0.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 242       | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 242       | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 242       | 0.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 242       | 0.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 238       | 0.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 223       | 0.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 222       | 0.72%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 222       | 0.72%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 221       | 0.71%   |
| Intel HD Graphics 530                                                                    | 219       | 0.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 218       | 0.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 215       | 0.69%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 212       | 0.68%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 193       | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 192       | 0.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 190       | 0.61%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 182       | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| 1 x Intel                     | 8153      | 32.01%  |
| 1 x Nvidia                    | 6486      | 25.46%  |
| 1 x AMD                       | 5645      | 22.16%  |
| Intel + Nvidia                | 2902      | 11.39%  |
| 2 x AMD                       | 886       | 3.48%   |
| Intel + AMD                   | 638       | 2.5%    |
| AMD + Nvidia                  | 235       | 0.92%   |
| 1 x Matrox                    | 131       | 0.51%   |
| 1 x ASPEED                    | 127       | 0.5%    |
| Other                         | 93        | 0.37%   |
| 2 x Nvidia                    | 36        | 0.14%   |
| 1 x SiS                       | 36        | 0.14%   |
| 1 x VIA                       | 27        | 0.11%   |
| 2 x Intel                     | 17        | 0.07%   |
| Nvidia + Matrox               | 11        | 0.04%   |
| Nvidia + ASPEED               | 8         | 0.03%   |
| 1 x Huawei Technologies       | 8         | 0.03%   |
| AMD + ASPEED                  | 6         | 0.02%   |
| 3 x AMD                       | 4         | 0.02%   |
| 3 x Nvidia                    | 3         | 0.01%   |
| 1 x Zhaoxin                   | 2         | 0.01%   |
| 1 x Silicon Motion            | 2         | 0.01%   |
| 1 x S3 Graphics               | 2         | 0.01%   |
| Intel + 2 x Nvidia            | 2         | 0.01%   |
| Intel + 2 x AMD               | 2         | 0.01%   |
| 3 x Nvidia + 1 x ASPEED       | 1         | 0.004%  |
| 2 x Nvidia + 1 x ASPEED       | 1         | 0.004%  |
| 2 x AMD + 1 x Nvidia          | 1         | 0.004%  |
| 1 x XGI                       | 1         | 0.004%  |
| Nvidia + Zhaoxin              | 1         | 0.004%  |
| 1 x Loongson Technology       | 1         | 0.004%  |
| Intel + SiS + 1 x S3 Graphics | 1         | 0.004%  |
| Intel + ASPEED                | 1         | 0.004%  |
| Intel + AMD + 4 x Nvidia      | 1         | 0.004%  |
| AMD + 2 x Nvidia              | 1         | 0.004%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 20328     | 78.02%  |
| Proprietary | 3556      | 13.65%  |
| Unknown     | 2172      | 8.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8755      | 33.13%  |
| 1.01-2.0   | 6009      | 22.74%  |
| 0.01-0.5   | 5432      | 20.56%  |
| 0.51-1.0   | 3423      | 12.95%  |
| 3.01-4.0   | 1735      | 6.57%   |
| 7.01-8.0   | 461       | 1.74%   |
| 5.01-6.0   | 302       | 1.14%   |
| 2.01-3.0   | 185       | 0.7%    |
| 8.01-16.0  | 104       | 0.39%   |
| 16.01-24.0 | 13        | 0.05%   |
| 4.01-5.0   | 6         | 0.02%   |
| 24.01-32.0 | 1         | 0.004%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 4449      | 18.22%  |
| AU Optronics            | 2578      | 10.56%  |
| LG Display              | 1881      | 7.7%    |
| Goldstar                | 1754      | 7.18%   |
| BOE                     | 1508      | 6.18%   |
| Chimei Innolux          | 1456      | 5.96%   |
| Acer                    | 1404      | 5.75%   |
| BenQ                    | 1105      | 4.53%   |
| Philips                 | 873       | 3.58%   |
| Chi Mei Optoelectronics | 817       | 3.35%   |
| Dell                    | 652       | 2.67%   |
| AOC                     | 623       | 2.55%   |
| ViewSonic               | 615       | 2.52%   |
| Ancor Communications    | 428       | 1.75%   |
| Hewlett-Packard         | 417       | 1.71%   |
| Lenovo                  | 338       | 1.38%   |
| NEC Computers           | 298       | 1.22%   |
| LG Philips              | 228       | 0.93%   |
| HannStar                | 203       | 0.83%   |
| Iiyama                  | 194       | 0.79%   |
| Sony                    | 184       | 0.75%   |
| PANDA                   | 162       | 0.66%   |
| Apple                   | 136       | 0.56%   |
| InfoVision              | 125       | 0.51%   |
| CPT                     | 117       | 0.48%   |
| Sharp                   | 116       | 0.48%   |
| ASUSTek Computer        | 100       | 0.41%   |
| Unknown                 | 91        | 0.37%   |
| Envision Peripherals    | 65        | 0.27%   |
| LG Electronics          | 64        | 0.26%   |
| Plain Tree Systems      | 58        | 0.24%   |
| Toshiba                 | 54        | 0.22%   |
| HHT                     | 48        | 0.2%    |
| Packard Bell            | 43        | 0.18%   |
| Mi                      | 40        | 0.16%   |
| MSI                     | 38        | 0.16%   |
| CSO                     | 38        | 0.16%   |
| ___                     | 35        | 0.14%   |
| TMX                     | 32        | 0.13%   |
| InnoLux Display         | 32        | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 233       | 0.93%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 202       | 0.81%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 176       | 0.71%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 158       | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 156       | 0.62%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 108       | 0.43%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 103       | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 101       | 0.4%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 94        | 0.38%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 93        | 0.37%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 92        | 0.37%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch     | 88        | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 87        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 86        | 0.34%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 78        | 0.31%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 77        | 0.31%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 74        | 0.3%    |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 74        | 0.3%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 74        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 73        | 0.29%   |
| Acer AL1716 ACRAD46 1280x1024 338x270mm 17.0-inch                        | 73        | 0.29%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch     | 71        | 0.28%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 69        | 0.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 67        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 67        | 0.27%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 65        | 0.26%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 65        | 0.26%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 64        | 0.26%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 61        | 0.24%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 61        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 61        | 0.24%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 60        | 0.24%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 60        | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 56        | 0.22%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 56        | 0.22%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 54        | 0.22%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 53        | 0.21%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 51        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 50        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 50        | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 9052      | 37.9%   |
| 1366x768 (WXGA)    | 5423      | 22.7%   |
| 1280x1024 (SXGA)   | 2452      | 10.27%  |
| 1600x900 (HD+)     | 1209      | 5.06%   |
| 1280x800 (WXGA)    | 794       | 3.32%   |
| 1440x900 (WXGA+)   | 760       | 3.18%   |
| 1680x1050 (WSXGA+) | 741       | 3.1%    |
| 3840x2160 (4K)     | 611       | 2.56%   |
| 2560x1440 (QHD)    | 594       | 2.49%   |
| 1024x600           | 390       | 1.63%   |
| 1920x1200 (WUXGA)  | 350       | 1.47%   |
| 1360x768           | 220       | 0.92%   |
| 1024x768 (XGA)     | 202       | 0.85%   |
| 2560x1080          | 136       | 0.57%   |
| Unknown            | 102       | 0.43%   |
| 1600x1200          | 100       | 0.42%   |
| 3440x1440          | 81        | 0.34%   |
| 2560x1600          | 76        | 0.32%   |
| 2160x1440          | 64        | 0.27%   |
| 1280x720 (HD)      | 57        | 0.24%   |
| 1920x540           | 39        | 0.16%   |
| 1400x1050          | 37        | 0.15%   |
| 2288x1287          | 36        | 0.15%   |
| 2880x1800          | 35        | 0.15%   |
| 3840x1080          | 28        | 0.12%   |
| 800x1280           | 25        | 0.1%    |
| 3200x2000          | 18        | 0.08%   |
| 1152x864           | 15        | 0.06%   |
| 2048x1536          | 14        | 0.06%   |
| 1680x945           | 14        | 0.06%   |
| 1280x960           | 14        | 0.06%   |
| 2520x1680          | 13        | 0.05%   |
| 3000x2000          | 12        | 0.05%   |
| 2048x1152          | 11        | 0.05%   |
| 4480x1440          | 9         | 0.04%   |
| 3840x2400          | 8         | 0.03%   |
| 1920x1440          | 8         | 0.03%   |
| 3200x1800 (QHD+)   | 7         | 0.03%   |
| 5760x2160          | 6         | 0.03%   |
| 3200x1080          | 6         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 7178      | 29.35%  |
| 17      | 2221      | 9.08%   |
| 21      | 2091      | 8.55%   |
| 23      | 1819      | 7.44%   |
| 19      | 1741      | 7.12%   |
| 24      | 1480      | 6.05%   |
| 13      | 1084      | 4.43%   |
| 14      | 1026      | 4.19%   |
| 27      | 969       | 3.96%   |
| 18      | 734       | 3%      |
| 20      | 594       | 2.43%   |
| Unknown | 543       | 2.22%   |
| 22      | 434       | 1.77%   |
| 10      | 407       | 1.66%   |
| 11      | 278       | 1.14%   |
| 12      | 245       | 1%      |
| 31      | 229       | 0.94%   |
| 34      | 179       | 0.73%   |
| 16      | 166       | 0.68%   |
| 40      | 144       | 0.59%   |
| 32      | 110       | 0.45%   |
| 54      | 106       | 0.43%   |
| 72      | 105       | 0.43%   |
| 26      | 71        | 0.29%   |
| 52      | 65        | 0.27%   |
| 25      | 50        | 0.2%    |
| 84      | 46        | 0.19%   |
| 42      | 33        | 0.13%   |
| 48      | 32        | 0.13%   |
| 46      | 32        | 0.13%   |
| 142     | 24        | 0.1%    |
| 28      | 23        | 0.09%   |
| 8       | 23        | 0.09%   |
| 7       | 19        | 0.08%   |
| 43      | 18        | 0.07%   |
| 33      | 14        | 0.06%   |
| 65      | 13        | 0.05%   |
| 29      | 13        | 0.05%   |
| 37      | 11        | 0.04%   |
| 50      | 9         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 9743      | 40.27%  |
| 401-500        | 4373      | 18.07%  |
| 501-600        | 4140      | 17.11%  |
| 351-400        | 2474      | 10.23%  |
| 201-300        | 1549      | 6.4%    |
| Unknown        | 543       | 2.24%   |
| 601-700        | 317       | 1.31%   |
| 701-800        | 307       | 1.27%   |
| 1001-1500      | 293       | 1.21%   |
| 1501-2000      | 157       | 0.65%   |
| 801-900        | 118       | 0.49%   |
| 901-1000       | 103       | 0.43%   |
| More than 2000 | 30        | 0.12%   |
| 1-100          | 24        | 0.1%    |
| 101-200        | 23        | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 16632     | 71.66%  |
| 16/10   | 2739      | 11.8%   |
| 5/4     | 2315      | 9.98%   |
| 4/3     | 554       | 2.39%   |
| Unknown | 386       | 1.66%   |
| 21/9    | 242       | 1.04%   |
| 3/2     | 230       | 0.99%   |
| 6/5     | 49        | 0.21%   |
| 1.00    | 24        | 0.1%    |
| 0.67    | 19        | 0.08%   |
| 32/9    | 9         | 0.04%   |
| 3.73    | 2         | 0.01%   |
| 0.62    | 2         | 0.01%   |
| 2.00    | 1         | 0.004%  |
| 1.96    | 1         | 0.004%  |
| 0.80    | 1         | 0.004%  |
| 0.56    | 1         | 0.004%  |
| 0.45    | 1         | 0.004%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7079      | 29.13%  |
| 201-250        | 4930      | 20.29%  |
| 151-200        | 2896      | 11.92%  |
| 141-150        | 1738      | 7.15%   |
| 81-90          | 1601      | 6.59%   |
| 301-350        | 1037      | 4.27%   |
| 121-130        | 866       | 3.56%   |
| 351-500        | 550       | 2.26%   |
| Unknown        | 543       | 2.23%   |
| 71-80          | 507       | 2.09%   |
| More than 1000 | 434       | 1.79%   |
| 251-300        | 421       | 1.73%   |
| 41-50          | 410       | 1.69%   |
| 51-60          | 278       | 1.14%   |
| 501-1000       | 270       | 1.11%   |
| 131-140        | 217       | 0.89%   |
| 61-70          | 199       | 0.82%   |
| 111-120        | 182       | 0.75%   |
| 91-100         | 98        | 0.4%    |
| 1-40           | 47        | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 10237     | 43.1%   |
| 101-120       | 7745      | 32.61%  |
| 121-160       | 3970      | 16.71%  |
| 161-240       | 604       | 2.54%   |
| Unknown       | 543       | 2.29%   |
| 1-50          | 500       | 2.1%    |
| More than 240 | 154       | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 21672     | 84.5%   |
| 2     | 2046      | 7.98%   |
| 0     | 1810      | 7.06%   |
| 3     | 115       | 0.45%   |
| 4     | 4         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 16114     | 43.35%  |
| Qualcomm Atheros                  | 6368      | 17.13%  |
| Intel                             | 5999      | 16.14%  |
| Broadcom                          | 2086      | 5.61%   |
| Nvidia                            | 750       | 2.02%   |
| Marvell Technology Group          | 713       | 1.92%   |
| Ralink                            | 564       | 1.52%   |
| Broadcom Limited                  | 546       | 1.47%   |
| Huawei Technologies               | 491       | 1.32%   |
| Ralink Technology                 | 488       | 1.31%   |
| TP-Link                           | 327       | 0.88%   |
| MediaTek                          | 297       | 0.8%    |
| VIA Technologies                  | 194       | 0.52%   |
| Xiaomi                            | 168       | 0.45%   |
| D-Link                            | 166       | 0.45%   |
| D-Link System                     | 158       | 0.43%   |
| ASUSTek Computer                  | 141       | 0.38%   |
| JMicron Technology                | 125       | 0.34%   |
| Qualcomm Atheros Communications   | 124       | 0.33%   |
| Attansic Technology               | 109       | 0.29%   |
| ZTE WCDMA Technologies MSM        | 105       | 0.28%   |
| Samsung Electronics               | 98        | 0.26%   |
| Silicon Integrated Systems [SiS]  | 78        | 0.21%   |
| Qualcomm                          | 58        | 0.16%   |
| ASIX Electronics                  | 54        | 0.15%   |
| Mellanox Technologies             | 49        | 0.13%   |
| Sundance Technology Inc / IC Plus | 37        | 0.1%    |
| Gemtek                            | 35        | 0.09%   |
| 3Com                              | 33        | 0.09%   |
| Sierra Wireless                   | 27        | 0.07%   |
| Microsoft                         | 27        | 0.07%   |
| IBM                               | 27        | 0.07%   |
| Hewlett-Packard                   | 26        | 0.07%   |
| Ericsson Business Mobile Networks | 25        | 0.07%   |
| Vimtron Electronics               | 23        | 0.06%   |
| HTC (High Tech Computer)          | 23        | 0.06%   |
| NetGear                           | 22        | 0.06%   |
| Mercucys                          | 22        | 0.06%   |
| Lenovo                            | 22        | 0.06%   |
| OPPO Electronics                  | 20        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 11828     | 28.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2141      | 5.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1466      | 3.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 896       | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 645       | 1.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 577       | 1.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 538       | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 522       | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 478       | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 434       | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 426       | 1.02%   |
| Nvidia MCP61 Ethernet                                                   | 361       | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 354       | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 351       | 0.84%   |
| Intel Wi-Fi 6 AX200                                                     | 325       | 0.78%   |
| Ralink MT7601U Wireless Adapter                                         | 307       | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                           | 305       | 0.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 275       | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 258       | 0.62%   |
| Intel Wi-Fi 6 AX201                                                     | 258       | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 254       | 0.61%   |
| Intel Wireless 8265 / 8275                                              | 249       | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 243       | 0.58%   |
| Intel Wireless 7265                                                     | 243       | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 239       | 0.57%   |
| Huawei Modem/Networkcard                                                | 237       | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                    | 233       | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 230       | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 218       | 0.52%   |
| Intel Wireless 3165                                                     | 217       | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 209       | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 209       | 0.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 206       | 0.49%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 202       | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                       | 198       | 0.48%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 197       | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 196       | 0.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 196       | 0.47%   |
| Intel I211 Gigabit Network Connection                                   | 193       | 0.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 191       | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 4636      | 29.18%  |
| Intel                           | 4241      | 26.69%  |
| Realtek Semiconductor           | 3036      | 19.11%  |
| Broadcom                        | 1437      | 9.04%   |
| Ralink                          | 564       | 3.55%   |
| Ralink Technology               | 488       | 3.07%   |
| TP-Link                         | 288       | 1.81%   |
| Broadcom Limited                | 275       | 1.73%   |
| MediaTek                        | 212       | 1.33%   |
| D-Link                          | 144       | 0.91%   |
| ASUSTek Computer                | 130       | 0.82%   |
| Qualcomm Atheros Communications | 124       | 0.78%   |
| D-Link System                   | 69        | 0.43%   |
| Sierra Wireless                 | 27        | 0.17%   |
| Microsoft                       | 27        | 0.17%   |
| Mercucys                        | 22        | 0.14%   |
| NetGear                         | 21        | 0.13%   |
| Qualcomm                        | 20        | 0.13%   |
| IMC Networks                    | 16        | 0.1%    |
| ZyXEL Communications            | 15        | 0.09%   |
| Realtek                         | 12        | 0.08%   |
| Fibocom                         | 12        | 0.08%   |
| Xiaomi                          | 10        | 0.06%   |
| Dell                            | 10        | 0.06%   |
| Micro Star International        | 7         | 0.04%   |
| Marvell Technology Group        | 5         | 0.03%   |
| Edimax Technology               | 5         | 0.03%   |
| ZyDAS                           | 3         | 0.02%   |
| VIA Technologies                | 3         | 0.02%   |
| Texas Instruments               | 3         | 0.02%   |
| Linksys                         | 3         | 0.02%   |
| Hewlett-Packard                 | 3         | 0.02%   |
| Wacom                           | 2         | 0.01%   |
| TRENDnet                        | 2         | 0.01%   |
| Fujitsu Siemens Computers       | 2         | 0.01%   |
| ASUSTek Computer (wrong ID)     | 2         | 0.01%   |
| Z-Com                           | 1         | 0.01%   |
| Wilocity                        | 1         | 0.01%   |
| Quectel Wireless Solutions      | 1         | 0.01%   |
| Qcom                            | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1466      | 9.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 896       | 5.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 645       | 4.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 577       | 3.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 522       | 3.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 434       | 2.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 426       | 2.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 354       | 2.21%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 351       | 2.19%   |
| Intel Wi-Fi 6 AX200                                                     | 325       | 2.03%   |
| Ralink MT7601U Wireless Adapter                                         | 307       | 1.92%   |
| Broadcom BCM43142 802.11b/g/n                                           | 305       | 1.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 275       | 1.72%   |
| Intel Wi-Fi 6 AX201                                                     | 258       | 1.61%   |
| Intel Wireless 8265 / 8275                                              | 249       | 1.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 243       | 1.52%   |
| Intel Wireless 7265                                                     | 243       | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 218       | 1.36%   |
| Intel Wireless 3165                                                     | 217       | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 209       | 1.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 197       | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 196       | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 191       | 1.19%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 187       | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 180       | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 157       | 0.98%   |
| Intel WiFi Link 5100                                                    | 156       | 0.97%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 144       | 0.9%    |
| Intel Wireless 7260                                                     | 143       | 0.89%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 141       | 0.88%   |
| Intel Centrino Wireless-N 130                                           | 127       | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 125       | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 124       | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 124       | 0.77%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 122       | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 118       | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 117       | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 109       | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                         | 102       | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 101       | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 14967     | 60.91%  |
| Intel                                  | 2756      | 11.22%  |
| Qualcomm Atheros                       | 2527      | 10.28%  |
| Broadcom                               | 844       | 3.43%   |
| Nvidia                                 | 749       | 3.05%   |
| Marvell Technology Group               | 708       | 2.88%   |
| Broadcom Limited                       | 281       | 1.14%   |
| VIA Technologies                       | 189       | 0.77%   |
| Huawei Technologies                    | 162       | 0.66%   |
| Xiaomi                                 | 158       | 0.64%   |
| JMicron Technology                     | 125       | 0.51%   |
| Attansic Technology                    | 109       | 0.44%   |
| D-Link System                          | 90        | 0.37%   |
| MediaTek                               | 82        | 0.33%   |
| Samsung Electronics                    | 81        | 0.33%   |
| Silicon Integrated Systems [SiS]       | 77        | 0.31%   |
| ASIX Electronics                       | 54        | 0.22%   |
| TP-Link                                | 40        | 0.16%   |
| Qualcomm                               | 38        | 0.15%   |
| Sundance Technology Inc / IC Plus      | 37        | 0.15%   |
| Mellanox Technologies                  | 37        | 0.15%   |
| Gemtek                                 | 34        | 0.14%   |
| 3Com                                   | 33        | 0.13%   |
| IBM                                    | 27        | 0.11%   |
| Vimtron Electronics                    | 23        | 0.09%   |
| HTC (High Tech Computer)               | 23        | 0.09%   |
| Lenovo                                 | 22        | 0.09%   |
| D-Link                                 | 22        | 0.09%   |
| OPPO Electronics                       | 20        | 0.08%   |
| ZTE WCDMA Technologies MSM             | 18        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 15        | 0.06%   |
| Aquantia                               | 15        | 0.06%   |
| Spreadtrum Communications              | 14        | 0.06%   |
| HMD Global                             | 14        | 0.06%   |
| T & A Mobile Phones                    | 12        | 0.05%   |
| GCT Semiconductor                      | 12        | 0.05%   |
| ASUSTek Computer                       | 12        | 0.05%   |
| ICS Advent                             | 11        | 0.04%   |
| Apple                                  | 11        | 0.04%   |
| Microchip Technology                   | 10        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11828     | 47.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2141      | 8.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 538       | 2.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 478       | 1.91%   |
| Nvidia MCP61 Ethernet                                             | 361       | 1.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 258       | 1.03%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 254       | 1.02%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 239       | 0.96%   |
| Intel Ethernet Connection (2) I219-V                              | 233       | 0.93%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 230       | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 209       | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 206       | 0.82%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 202       | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 198       | 0.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 196       | 0.78%   |
| Intel I211 Gigabit Network Connection                             | 193       | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 190       | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 176       | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 133       | 0.53%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 128       | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 125       | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 123       | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 122       | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 121       | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 120       | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 110       | 0.44%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 109       | 0.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 105       | 0.42%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 102       | 0.41%   |
| Intel I210 Gigabit Network Connection                             | 95        | 0.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 91        | 0.36%   |
| Intel Ethernet Connection (14) I219-V                             | 91        | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 90        | 0.36%   |
| Intel 82574L Gigabit Network Connection                           | 90        | 0.36%   |
| Intel Ethernet Controller I225-V                                  | 89        | 0.36%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 87        | 0.35%   |
| Huawei LLD-L21                                                    | 86        | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 85        | 0.34%   |
| Nvidia MCP77 Ethernet                                             | 83        | 0.33%   |
| Intel Ethernet Connection I217-V                                  | 82        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 23089     | 59.04%  |
| WiFi     | 15358     | 39.27%  |
| Modem    | 620       | 1.59%   |
| Unknown  | 43        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 13402     | 52.91%  |
| WiFi     | 11881     | 46.9%   |
| Modem    | 46        | 0.18%   |
| Unknown  | 3         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 12505     | 49.5%   |
| 1     | 11876     | 47.01%  |
| 0     | 507       | 2.01%   |
| 3     | 217       | 0.86%   |
| 4     | 88        | 0.35%   |
| 6     | 38        | 0.15%   |
| 8     | 13        | 0.05%   |
| 5     | 5         | 0.02%   |
| 7     | 4         | 0.02%   |
| 12    | 3         | 0.01%   |
| 11    | 2         | 0.01%   |
| 33    | 1         | 0.004%  |
| 20    | 1         | 0.004%  |
| 14    | 1         | 0.004%  |
| 13    | 1         | 0.004%  |
| 10    | 1         | 0.004%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 24783     | 98.13%  |
| Yes  | 471       | 1.87%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3064      | 28.07%  |
| Realtek Semiconductor           | 1319      | 12.08%  |
| Qualcomm Atheros Communications | 1282      | 11.74%  |
| Cambridge Silicon Radio         | 881       | 8.07%   |
| IMC Networks                    | 760       | 6.96%   |
| Broadcom                        | 712       | 6.52%   |
| Lite-On Technology              | 651       | 5.96%   |
| Foxconn / Hon Hai               | 556       | 5.09%   |
| ASUSTek Computer                | 334       | 3.06%   |
| Ralink                          | 197       | 1.8%    |
| Toshiba                         | 152       | 1.39%   |
| Foxconn International           | 151       | 1.38%   |
| Apple                           | 148       | 1.36%   |
| Realtek                         | 137       | 1.26%   |
| Hewlett-Packard                 | 128       | 1.17%   |
| Dell                            | 111       | 1.02%   |
| Alps Electric                   | 65        | 0.6%    |
| MediaTek                        | 47        | 0.43%   |
| Ralink Technology               | 38        | 0.35%   |
| Integrated System Solution      | 31        | 0.28%   |
| Opticis                         | 23        | 0.21%   |
| Chicony Electronics             | 23        | 0.21%   |
| TP-Link                         | 18        | 0.16%   |
| Micro Star International        | 13        | 0.12%   |
| USI                             | 10        | 0.09%   |
| ISSC                            | 10        | 0.09%   |
| Conwise Technology              | 9         | 0.08%   |
| Askey Computer                  | 7         | 0.06%   |
| Taiyo Yuden                     | 5         | 0.05%   |
| Roper                           | 5         | 0.05%   |
| Qcom                            | 5         | 0.05%   |
| Logitech                        | 4         | 0.04%   |
| HTC (High Tech Computer)        | 4         | 0.04%   |
| D-Link System                   | 4         | 0.04%   |
| Marvell Semiconductor           | 3         | 0.03%   |
| Samsung Electronics             | 2         | 0.02%   |
| Actions                         | 2         | 0.02%   |
| TRENDnet                        | 1         | 0.01%   |
| Syntek                          | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 1011      | 9.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 881       | 8.06%   |
| Realtek Bluetooth Radio                                                             | 774       | 7.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 560       | 5.13%   |
| Intel AX201 Bluetooth                                                               | 483       | 4.42%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 401       | 3.67%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 379       | 3.47%   |
| Intel AX200 Bluetooth                                                               | 321       | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 312       | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 263       | 2.41%   |
| IMC Networks Bluetooth Radio                                                        | 235       | 2.15%   |
| Ralink RT3290 Bluetooth                                                             | 197       | 1.8%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 190       | 1.74%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 186       | 1.7%    |
| IMC Networks Bluetooth Device                                                       | 181       | 1.66%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 165       | 1.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 162       | 1.48%   |
| Lite-On Bluetooth Device                                                            | 161       | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 153       | 1.4%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 152       | 1.39%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 149       | 1.36%   |
| Realtek Bluetooth Radio                                                             | 137       | 1.25%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 135       | 1.24%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 107       | 0.98%   |
| Realtek RTL8723B Bluetooth                                                          | 105       | 0.96%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 105       | 0.96%   |
| Broadcom BCM2045 Bluetooth                                                          | 99        | 0.91%   |
| Intel AX210 Bluetooth                                                               | 78        | 0.71%   |
| Qualcomm Atheros Bluetooth                                                          | 73        | 0.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 73        | 0.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 72        | 0.66%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 70        | 0.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 65        | 0.59%   |
| IMC Networks Wireless_Device                                                        | 63        | 0.58%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 62        | 0.57%   |
| Broadcom HP Portable Valentine                                                      | 62        | 0.57%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 62        | 0.57%   |
| Apple Bluetooth USB Host Controller                                                 | 59        | 0.54%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 58        | 0.53%   |
| Toshiba Integrated Bluetooth HCI                                                    | 57        | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 17253     | 51.04%  |
| AMD                                  | 7747      | 22.92%  |
| Nvidia                               | 6440      | 19.05%  |
| C-Media Electronics                  | 606       | 1.79%   |
| Creative Labs                        | 323       | 0.96%   |
| VIA Technologies                     | 134       | 0.4%    |
| Silicon Integrated Systems [SiS]     | 113       | 0.33%   |
| Creative Technology                  | 111       | 0.33%   |
| Logitech                             | 101       | 0.3%    |
| JMTek                                | 90        | 0.27%   |
| Texas Instruments                    | 65        | 0.19%   |
| Generalplus Technology               | 61        | 0.18%   |
| ASUSTek Computer                     | 35        | 0.1%    |
| Plantronics                          | 29        | 0.09%   |
| Kingston Technology                  | 27        | 0.08%   |
| Lenovo                               | 26        | 0.08%   |
| Realtek Semiconductor                | 25        | 0.07%   |
| GN Netcom                            | 21        | 0.06%   |
| Yamaha                               | 20        | 0.06%   |
| Razer USA                            | 19        | 0.06%   |
| Sony                                 | 18        | 0.05%   |
| A4Tech                               | 17        | 0.05%   |
| Samson Technologies                  | 15        | 0.04%   |
| SteelSeries ApS                      | 14        | 0.04%   |
| KTMicro                              | 13        | 0.04%   |
| Pixart Imaging                       | 12        | 0.04%   |
| M-Audio                              | 12        | 0.04%   |
| Focusrite-Novation                   | 12        | 0.04%   |
| XMOS                                 | 11        | 0.03%   |
| Sennheiser Communications            | 11        | 0.03%   |
| Ensoniq                              | 10        | 0.03%   |
| Thesycon Systemsoftware & Consulting | 9         | 0.03%   |
| Nordic Semiconductor ASA             | 9         | 0.03%   |
| Microsoft                            | 9         | 0.03%   |
| Micro Star International             | 9         | 0.03%   |
| Conexant Systems                     | 9         | 0.03%   |
| BEHRINGER International              | 9         | 0.03%   |
| GYROCOM C&C                          | 8         | 0.02%   |
| SAVITECH                             | 7         | 0.02%   |
| Promethean Limited                   | 7         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2238      | 5.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2191      | 5.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2180      | 5.54%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2023      | 5.14%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1351      | 3.43%   |
| AMD FCH Azalia Controller                                                                         | 1218      | 3.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1050      | 2.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 968       | 2.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 914       | 2.32%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 910       | 2.31%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 801       | 2.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 666       | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 663       | 1.68%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 621       | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 598       | 1.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 583       | 1.48%   |
| Nvidia High Definition Audio Controller                                                           | 579       | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 529       | 1.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 521       | 1.32%   |
| Intel 200 Series PCH HD Audio                                                                     | 495       | 1.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 494       | 1.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 462       | 1.17%   |
| AMD Kabini HDMI/DP Audio                                                                          | 428       | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 405       | 1.03%   |
| Nvidia MCP61 High Definition Audio                                                                | 391       | 0.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 382       | 0.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 356       | 0.9%    |
| Intel 8 Series HD Audio Controller                                                                | 356       | 0.9%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 351       | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 348       | 0.88%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 338       | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 332       | 0.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 325       | 0.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 311       | 0.79%   |
| AMD Trinity HDMI Audio Controller                                                                 | 310       | 0.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 305       | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 282       | 0.72%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 274       | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 273       | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 268       | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 6297      | 25.31%  |
| Samsung Electronics          | 3815      | 15.33%  |
| Kingston                     | 3743      | 15.04%  |
| SK hynix                     | 2954      | 11.87%  |
| Crucial                      | 1332      | 5.35%   |
| Micron Technology            | 1298      | 5.22%   |
| Corsair                      | 571       | 2.29%   |
| Elpida                       | 522       | 2.1%    |
| Nanya Technology             | 474       | 1.9%    |
| AMD                          | 471       | 1.89%   |
| A-DATA Technology            | 466       | 1.87%   |
| Patriot                      | 421       | 1.69%   |
| Ramaxel Technology           | 414       | 1.66%   |
| Unknown (ABCD)               | 144       | 0.58%   |
| Goodram                      | 140       | 0.56%   |
| Goldkey                      | 134       | 0.54%   |
| ASint Technology             | 128       | 0.51%   |
| Apacer                       | 112       | 0.45%   |
| Foxline                      | 111       | 0.45%   |
| G.Skill                      | 93        | 0.37%   |
| Unknown                      | 90        | 0.36%   |
| 48spaces                     | 82        | 0.33%   |
| Qumo                         | 81        | 0.33%   |
| Transcend                    | 80        | 0.32%   |
| Kingmax                      | 74        | 0.3%    |
| Silicon Power                | 64        | 0.26%   |
| Kllisre                      | 64        | 0.26%   |
| SHARETRONIC                  | 56        | 0.23%   |
| Unifosa                      | 54        | 0.22%   |
| Qimonda                      | 41        | 0.16%   |
| ACPI Digital                 | 34        | 0.14%   |
| KETECH                       | 31        | 0.12%   |
| Atermiter                    | 30        | 0.12%   |
| GeIL                         | 29        | 0.12%   |
| Hikvision                    | 25        | 0.1%    |
| Team                         | 23        | 0.09%   |
| Toshiba                      | 21        | 0.08%   |
| Ramos Technology             | 19        | 0.08%   |
| Patriot Memory (PDP Systems) | 14        | 0.06%   |
| Kingmax Semiconductor        | 13        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 291       | 1.04%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 271       | 0.97%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 264       | 0.95%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 227       | 0.81%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 224       | 0.8%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 213       | 0.76%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 206       | 0.74%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                      | 186       | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 164       | 0.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 159       | 0.57%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 145       | 0.52%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 142       | 0.51%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 137       | 0.49%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 137       | 0.49%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 135       | 0.48%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 130       | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 128       | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 122       | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 121       | 0.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 114       | 0.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 113       | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 112       | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 111       | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 109       | 0.39%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 106       | 0.38%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 105       | 0.38%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 101       | 0.36%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 97        | 0.35%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 96        | 0.34%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 94        | 0.34%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 93        | 0.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 92        | 0.33%   |
| Unknown                                                          | 90        | 0.32%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 89        | 0.32%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 86        | 0.31%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                           | 86        | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 85        | 0.3%    |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 83        | 0.3%    |
| Unknown RAM Module 512MB DIMM SDRAM                              | 82        | 0.29%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 81        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 9202      | 42.23%  |
| DDR4    | 5492      | 25.21%  |
| DDR2    | 2397      | 11%     |
| Unknown | 2120      | 9.73%   |
| SDRAM   | 1501      | 6.89%   |
| DDR     | 423       | 1.94%   |
| LPDDR4  | 356       | 1.63%   |
| DRAM    | 116       | 0.53%   |
| LPDDR3  | 109       | 0.5%    |
| DDR5    | 47        | 0.22%   |
| LPDDR5  | 24        | 0.11%   |
| SRAM    | 1         | 0.005%  |
| EEPROM  | 1         | 0.005%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 10754     | 50.07%  |
| SODIMM       | 10191     | 47.44%  |
| Row Of Chips | 483       | 2.25%   |
| Chip         | 27        | 0.13%   |
| FB-DIMM      | 16        | 0.07%   |
| Unknown      | 8         | 0.04%   |
| RIMM         | 1         | 0.005%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 8219      | 33.04%  |
| 2048    | 6518      | 26.21%  |
| 8192    | 5291      | 21.27%  |
| 1024    | 2722      | 10.94%  |
| 16384   | 1170      | 4.7%    |
| 512     | 549       | 2.21%   |
| 32768   | 246       | 0.99%   |
| 256     | 104       | 0.42%   |
| 65536   | 27        | 0.11%   |
| 1536    | 10        | 0.04%   |
| 32      | 5         | 0.02%   |
| Unknown | 5         | 0.02%   |
| 128     | 2         | 0.01%   |
| 16      | 2         | 0.01%   |
| 258496  | 1         | 0.004%  |
| 129408  | 1         | 0.004%  |
| 1       | 1         | 0.004%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 5405      | 22.61%  |
| 1333    | 2761      | 11.55%  |
| 2667    | 1848      | 7.73%   |
| Unknown | 1635      | 6.84%   |
| 800     | 1542      | 6.45%   |
| 3200    | 1420      | 5.94%   |
| 667     | 1393      | 5.83%   |
| 1334    | 1376      | 5.76%   |
| 2400    | 1253      | 5.24%   |
| 2133    | 704       | 2.95%   |
| 1066    | 327       | 1.37%   |
| 1067    | 322       | 1.35%   |
| 1867    | 305       | 1.28%   |
| 400     | 305       | 1.28%   |
| 533     | 290       | 1.21%   |
| 4199    | 284       | 1.19%   |
| 1866    | 251       | 1.05%   |
| 3600    | 237       | 0.99%   |
| 3266    | 218       | 0.91%   |
| 333     | 181       | 0.76%   |
| 2933    | 170       | 0.71%   |
| 2666    | 139       | 0.58%   |
| 3400    | 128       | 0.54%   |
| 2048    | 123       | 0.51%   |
| 1800    | 82        | 0.34%   |
| 3466    | 74        | 0.31%   |
| 3000    | 68        | 0.28%   |
| 975     | 65        | 0.27%   |
| 266     | 62        | 0.26%   |
| 2800    | 56        | 0.23%   |
| 4267    | 50        | 0.21%   |
| 3733    | 46        | 0.19%   |
| 2866    | 42        | 0.18%   |
| 3333    | 41        | 0.17%   |
| 4800    | 35        | 0.15%   |
| 1648    | 34        | 0.14%   |
| 66      | 33        | 0.14%   |
| 1639    | 32        | 0.13%   |
| 2134    | 30        | 0.13%   |
| 2000    | 29        | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 359       | 28.74%  |
| Canon                           | 263       | 21.06%  |
| Samsung Electronics             | 208       | 16.65%  |
| Seiko Epson                     | 114       | 9.13%   |
| Brother Industries              | 89        | 7.13%   |
| Xerox                           | 47        | 3.76%   |
| Pantum                          | 38        | 3.04%   |
| Panasonic (Matsushita)          | 37        | 2.96%   |
| Kyocera                         | 24        | 1.92%   |
| Ricoh                           | 21        | 1.68%   |
| QinHeng Electronics             | 13        | 1.04%   |
| Prolific Technology             | 7         | 0.56%   |
| NXP Semiconductors              | 3         | 0.24%   |
| Lexmark International           | 3         | 0.24%   |
| Xiaomi                          | 2         | 0.16%   |
| TSC Auto ID Technology          | 2         | 0.16%   |
| STMicroelectronics              | 2         | 0.16%   |
| Konica Minolta                  | 2         | 0.16%   |
| Datamax-O'Neil                  | 2         | 0.16%   |
| cab Produkttechnik GmbH & Co KG | 2         | 0.16%   |
| Apple                           | 2         | 0.16%   |
| Sharp                           | 1         | 0.08%   |
| Samsung Info. Systems America   | 1         | 0.08%   |
| Oki Data                        | 1         | 0.08%   |
| NCR                             | 1         | 0.08%   |
| KODAK                           | 1         | 0.08%   |
| iDPRT                           | 1         | 0.08%   |
| GODEX INTERNATIONAL             | 1         | 0.08%   |
| Fuji Xerox                      | 1         | 0.08%   |
| Custom Engineering SPA          | 1         | 0.08%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP LaserJet 1020                      | 38        | 3.02%   |
| Samsung SCX-4200 series               | 34        | 2.7%    |
| HP LaserJet 1018                      | 31        | 2.47%   |
| HP LaserJet P1102                     | 30        | 2.39%   |
| Canon LBP2900                         | 30        | 2.39%   |
| Panasonic (Matsushita) KX-MB1500RU    | 24        | 1.91%   |
| Samsung SCX-3400 Series               | 22        | 1.75%   |
| HP LaserJet 1010                      | 20        | 1.59%   |
| HP LaserJet P1005                     | 19        | 1.51%   |
| Samsung SCX-3200 Series               | 18        | 1.43%   |
| Seiko Epson Printer                   | 17        | 1.35%   |
| Canon MF4010 series                   | 16        | 1.27%   |
| Canon MF3010                          | 15        | 1.19%   |
| Seiko Epson USB2.0 Printer (Hi-speed) | 14        | 1.11%   |
| Samsung M2070 Series                  | 14        | 1.11%   |
| HP LaserJet 1320                      | 14        | 1.11%   |
| HP LaserJet 1200                      | 14        | 1.11%   |
| Canon MF4410                          | 14        | 1.11%   |
| Brother HL-1110 series                | 14        | 1.11%   |
| QinHeng CH340S                        | 13        | 1.03%   |
| Pantum P2200 series                   | 13        | 1.03%   |
| Samsung ML-1640 Series Laser Printer  | 12        | 0.95%   |
| Samsung ML-1210 Printer               | 12        | 0.95%   |
| Canon PIXMA MG2500 Series             | 12        | 0.95%   |
| Canon LBP3010/LBP3018/LBP3050         | 12        | 0.95%   |
| Seiko Epson L210 Series               | 11        | 0.88%   |
| HP LaserJet 1022                      | 11        | 0.88%   |
| HP DeskJet 2130 series                | 11        | 0.88%   |
| Canon LBP6000                         | 11        | 0.88%   |
| Samsung ML-2010P Mono Laser Printer   | 10        | 0.8%    |
| Samsung M2020 Series                  | 10        | 0.8%    |
| Pantum M6500 series                   | 10        | 0.8%    |
| HP LaserJet 1300                      | 10        | 0.8%    |
| Canon LaserShot LBP-1120 Printer      | 10        | 0.8%    |
| Brother HL-2030 Laser Printer         | 10        | 0.8%    |
| Samsung SCX-4100 Scanner              | 9         | 0.72%   |
| Canon LBP810                          | 9         | 0.72%   |
| Canon LBP6020                         | 9         | 0.72%   |
| Xerox WorkCentre 3119 Series          | 8         | 0.64%   |
| Xerox Phaser 3140 and 3155            | 8         | 0.64%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 116       | 36.14%  |
| Seiko Epson                 | 83        | 25.86%  |
| Hewlett-Packard             | 56        | 17.45%  |
| Mustek Systems              | 33        | 10.28%  |
| Acer Peripherals (now BenQ) | 13        | 4.05%   |
| Ultima Electronics          | 12        | 3.74%   |
| KYE Systems (Mouse Systems) | 5         | 1.56%   |
| Avision                     | 2         | 0.62%   |
| Canon Electronics           | 1         | 0.31%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                                                | 20        | 6.21%   |
| Canon CanoScan LiDE 110                                                               | 20        | 6.21%   |
| HP ScanJet 2400c                                                                      | 19        | 5.9%    |
| Canon CanoScan LiDE 120                                                               | 18        | 5.59%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 13        | 4.04%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 11        | 3.42%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 11        | 3.42%   |
| Canon CanoScan LiDE 210                                                               | 11        | 3.42%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 10        | 3.11%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 10        | 3.11%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 10        | 3.11%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 9         | 2.8%    |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 7         | 2.17%   |
| Mustek Systems SNAPSCAN e22                                                           | 7         | 2.17%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 6         | 1.86%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 6         | 1.86%   |
| Canon CanoScan LiDE 60                                                                | 6         | 1.86%   |
| Canon CanoScan LiDE 220                                                               | 6         | 1.86%   |
| Canon CanoScan LiDE 100                                                               | 6         | 1.86%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 4         | 1.24%   |
| HP ScanJet 3800c                                                                      | 4         | 1.24%   |
| Canon CanoScan LiDE 70                                                                | 4         | 1.24%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 4         | 1.24%   |
| Seiko Epson Perfection 660                                                            | 3         | 0.93%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 3         | 0.93%   |
| HP ScanJet 3970c                                                                      | 3         | 0.93%   |
| HP ScanJet 3770                                                                       | 3         | 0.93%   |
| HP Scanjet 200                                                                        | 3         | 0.93%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 3         | 0.93%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 3         | 0.93%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 3         | 0.93%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 2         | 0.62%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 2         | 0.62%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 2         | 0.62%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 2         | 0.62%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 2         | 0.62%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 2         | 0.62%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 2         | 0.62%   |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 0.62%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4                                          | 2         | 0.62%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2815      | 20.97%  |
| IMC Networks                           | 1317      | 9.81%   |
| Logitech                               | 856       | 6.38%   |
| Realtek Semiconductor                  | 810       | 6.03%   |
| Microdia                               | 744       | 5.54%   |
| Suyin                                  | 665       | 4.95%   |
| Z-Star Microelectronics                | 580       | 4.32%   |
| Acer                                   | 577       | 4.3%    |
| Sunplus Innovation Technology          | 531       | 3.95%   |
| Bison Electronics                      | 477       | 3.55%   |
| Quanta                                 | 462       | 3.44%   |
| Silicon Motion                         | 421       | 3.14%   |
| Cheng Uei Precision Industry (Foxlink) | 410       | 3.05%   |
| Alcor Micro                            | 392       | 2.92%   |
| Syntek                                 | 354       | 2.64%   |
| Apple                                  | 164       | 1.22%   |
| Lite-On Technology                     | 132       | 0.98%   |
| Microsoft                              | 128       | 0.95%   |
| Ricoh                                  | 124       | 0.92%   |
| ALi                                    | 107       | 0.8%    |
| Luxvisions Innotech Limited            | 105       | 0.78%   |
| KYE Systems (Mouse Systems)            | 100       | 0.74%   |
| GEMBIRD                                | 82        | 0.61%   |
| DigiTech                               | 82        | 0.61%   |
| Arkmicro Technologies                  | 75        | 0.56%   |
| Aveo Technology                        | 64        | 0.48%   |
| Samsung Electronics                    | 59        | 0.44%   |
| Pixart Imaging                         | 59        | 0.44%   |
| Cubeternet                             | 55        | 0.41%   |
| SunplusIT                              | 47        | 0.35%   |
| Sonix Technology                       | 46        | 0.34%   |
| Creative Technology                    | 45        | 0.34%   |
| Lenovo                                 | 41        | 0.31%   |
| Primax Electronics                     | 33        | 0.25%   |
| USB Camera                             | 29        | 0.22%   |
| Genesys Logic                          | 26        | 0.19%   |
| Importek                               | 24        | 0.18%   |
| A4Tech                                 | 24        | 0.18%   |
| Y Media                                | 22        | 0.16%   |
| Sunplus Technology                     | 20        | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Logitech Webcam C270                     | 305       | 2.27%   |
| Chicony HD Webcam                        | 293       | 2.18%   |
| Chicony Integrated Camera                | 275       | 2.04%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 249       | 1.85%   |
| Chicony Lenovo EasyCamera                | 221       | 1.64%   |
| IMC Networks USB2.0 HD UVC WebCam        | 203       | 1.51%   |
| Z-Star Venus USB2.0 Camera               | 173       | 1.29%   |
| Microdia Integrated_Webcam_HD            | 156       | 1.16%   |
| Sunplus HD WebCam                        | 152       | 1.13%   |
| IMC Networks Integrated Camera           | 149       | 1.11%   |
| Chicony USB2.0 HD UVC WebCam             | 142       | 1.06%   |
| IMC Networks UVC VGA Webcam              | 140       | 1.04%   |
| Acer Lenovo Integrated Webcam            | 136       | 1.01%   |
| Chicony USB 2.0 camera                   | 128       | 0.95%   |
| Realtek Integrated_Webcam_HD             | 123       | 0.91%   |
| Z-Star A4 TECH USB2.0 PC Camera J        | 117       | 0.87%   |
| Microdia Camera                          | 117       | 0.87%   |
| Syntek Integrated Camera                 | 111       | 0.82%   |
| Quanta VGA WebCam                        | 107       | 0.8%    |
| Chicony HP Webcam                        | 107       | 0.8%    |
| Alcor Micro USB 2.0 Camera               | 105       | 0.78%   |
| Chicony VGA Webcam                       | 102       | 0.76%   |
| Acer BisonCam, NB Pro                    | 102       | 0.76%   |
| Realtek Lenovo EasyCamera                | 98        | 0.73%   |
| Realtek USB Camera                       | 96        | 0.71%   |
| Chicony USB2.0 VGA UVC WebCam            | 92        | 0.68%   |
| Alcor Micro Asus Integrated Webcam       | 88        | 0.65%   |
| IMC Networks HD Camera                   | 86        | 0.64%   |
| Silicon Motion WebCam SC-0311139N        | 85        | 0.63%   |
| Acer Integrated Camera                   | 84        | 0.62%   |
| Z-Star A4 TECH USB2.0 PC Camera E        | 81        | 0.6%    |
| Syntek Lenovo EasyCamera                 | 80        | 0.59%   |
| IMC Networks Integrated Webcam           | 80        | 0.59%   |
| Bison Lenovo EasyCamera                  | 78        | 0.58%   |
| Sunplus Integrated_Webcam_HD             | 77        | 0.57%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 77        | 0.57%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 76        | 0.56%   |
| Chicony HP Truevision HD                 | 76        | 0.56%   |
| DigiTech USB 2.0 PC Camera               | 74        | 0.55%   |
| Bison Lenovo Integrated Webcam           | 73        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 446       | 30.97%  |
| Shenzhen Goodix Technology         | 274       | 19.03%  |
| Synaptics                          | 217       | 15.07%  |
| AuthenTec                          | 135       | 9.38%   |
| Upek                               | 111       | 7.71%   |
| LighTuning Technology              | 100       | 6.94%   |
| Elan Microelectronics              | 97        | 6.74%   |
| STMicroelectronics                 | 37        | 2.57%   |
| Focal-systems.Corp                 | 11        | 0.76%   |
| Realtek USB2.0 Finger Print Bridge | 9         | 0.63%   |
| Microsoft                          | 2         | 0.14%   |
| Samsung Electronics                | 1         | 0.07%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 218       | 15.14%  |
| Validity Sensors Fingerprint scanner                                       | 101       | 7.01%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 93        | 6.46%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 89        | 6.18%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 75        | 5.21%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 63        | 4.38%   |
| Elan ELAN:Fingerprint                                                      | 62        | 4.31%   |
| Shenzhen Goodix Fingerprint Reader                                         | 49        | 3.4%    |
| LighTuning Fingerprint Reader                                              | 45        | 3.13%   |
| AuthenTec AES1600                                                          | 42        | 2.92%   |
| STMicroelectronics Fingerprint Reader                                      | 37        | 2.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 34        | 2.36%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 33        | 2.29%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 32        | 2.22%   |
| Elan ELAN:ARM-M4                                                           | 31        | 2.15%   |
| AuthenTec AES2810                                                          | 28        | 1.94%   |
| Validity Sensors VFS491                                                    | 27        | 1.88%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 26        | 1.81%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 24        | 1.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 22        | 1.53%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 1.39%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 20        | 1.39%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 19        | 1.32%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 19        | 1.32%   |
| Upek TCS5B Fingerprint sensor                                              | 18        | 1.25%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 18        | 1.25%   |
| Synaptics  WBDI                                                            | 17        | 1.18%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 1.18%   |
| Validity Sensors Synaptics WBDI                                            | 15        | 1.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 15        | 1.04%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 0.83%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 12        | 0.83%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 0.76%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 11        | 0.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 0.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 0.63%   |
| Synaptics UWP WBDI Device                                                  | 9         | 0.63%   |
| Synaptics UWP WBDI                                                         | 9         | 0.63%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 9         | 0.63%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 8         | 0.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 105       | 32.41%  |
| Broadcom                   | 88        | 27.16%  |
| Upek                       | 26        | 8.02%   |
| O2 Micro                   | 21        | 6.48%   |
| Aktiv                      | 18        | 5.56%   |
| Lenovo                     | 16        | 4.94%   |
| Aladdin Knowledge Systems  | 15        | 4.63%   |
| Aladdin R.D.               | 9         | 2.78%   |
| Advanced Card Systems      | 7         | 2.16%   |
| Yubico.com                 | 6         | 1.85%   |
| Gemalto (was Gemplus)      | 5         | 1.54%   |
| Athena Smartcard Solutions | 4         | 1.23%   |
| OmniKey                    | 1         | 0.31%   |
| NXP Semiconductors         | 1         | 0.31%   |
| Microchip Technology       | 1         | 0.31%   |
| Castles Technology         | 1         | 0.31%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 100       | 30.86%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 10.49%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 8.02%   |
| Broadcom 58200                                                               | 20        | 6.17%   |
| Broadcom 5880                                                                | 19        | 5.86%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 5.56%   |
| Aktiv Rutoken lite                                                           | 18        | 5.56%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 4.94%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 4.63%   |
| Aladdin Knowledge Systems Token JC                                           | 15        | 4.63%   |
| Aladdin R.D. JaCarta                                                         | 8         | 2.47%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 6         | 1.85%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 4         | 1.23%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.23%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.93%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.93%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.62%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.62%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 2         | 0.62%   |
| OmniKey Smart Card Reader USB                                                | 1         | 0.31%   |
| NXP Semiconductors PN7462au CCID                                             | 1         | 0.31%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.31%   |
| Castles Technology EZCCID Smart Card Reader                                  | 1         | 0.31%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.31%   |
| Aladdin R.D. Smart card reader JCR721                                        | 1         | 0.31%   |
| Advanced Card Systems Token USB 64K                                          | 1         | 0.31%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.31%   |
| Advanced Card Systems ACR3901U                                               | 1         | 0.31%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 19222     | 74.04%  |
| 1     | 5485      | 21.13%  |
| 2     | 953       | 3.67%   |
| 3     | 191       | 0.74%   |
| 4     | 80        | 0.31%   |
| 5     | 18        | 0.07%   |
| 6     | 8         | 0.03%   |
| 7     | 3         | 0.01%   |
| 9     | 1         | 0.004%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3423      | 44.43%  |
| Fingerprint reader       | 1435      | 18.62%  |
| Net/wireless             | 727       | 9.44%   |
| Communication controller | 384       | 4.98%   |
| Multimedia controller    | 358       | 4.65%   |
| Bluetooth                | 282       | 3.66%   |
| Chipcard                 | 276       | 3.58%   |
| Unassigned class         | 215       | 2.79%   |
| Camera                   | 174       | 2.26%   |
| Sound                    | 89        | 1.16%   |
| Storage                  | 70        | 0.91%   |
| Flash memory             | 63        | 0.82%   |
| Net/ethernet             | 48        | 0.62%   |
| Modem                    | 30        | 0.39%   |
| Network                  | 29        | 0.38%   |
| Card reader              | 29        | 0.38%   |
| Dvb card                 | 21        | 0.27%   |
| Storage/raid             | 17        | 0.22%   |
| Storage/ide              | 10        | 0.13%   |
| Firewire controller      | 9         | 0.12%   |
| Storage/ata              | 7         | 0.09%   |
| Tv card                  | 5         | 0.06%   |
| Unclassified device      | 2         | 0.03%   |
| Wireless                 | 1         | 0.01%   |
| Video                    | 1         | 0.01%   |

