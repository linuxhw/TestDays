Linux in Sweden - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Sweden/Desktop/README.md) and [notebooks](/Location/Sweden/Notebook/README.md).

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

Total: 2338

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | UX303UB                     | Notebook    | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9d5f38913b](https://linux-hardware.org/?probe=9d5f38913b) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [37a7291916](https://linux-hardware.org/?probe=37a7291916) | Sep 29, 2022 |
| HP            | 18E5                        | Desktop     | [bcc9927d20](https://linux-hardware.org/?probe=bcc9927d20) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [6f9bc0cdba](https://linux-hardware.org/?probe=6f9bc0cdba) | Sep 26, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d65cd8309b](https://linux-hardware.org/?probe=d65cd8309b) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a037b1ec8f](https://linux-hardware.org/?probe=a037b1ec8f) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0290975708](https://linux-hardware.org/?probe=0290975708) | Sep 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [8f29c3dc10](https://linux-hardware.org/?probe=8f29c3dc10) | Sep 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [0d4570c1d6](https://linux-hardware.org/?probe=0d4570c1d6) | Sep 23, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [a68d3f20eb](https://linux-hardware.org/?probe=a68d3f20eb) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [714ca60abf](https://linux-hardware.org/?probe=714ca60abf) | Sep 23, 2022 |
| Lenovo        | Yoga 13sACN 2021 82CY       | Notebook    | [d374a74e0d](https://linux-hardware.org/?probe=d374a74e0d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [5ed0ffde54](https://linux-hardware.org/?probe=5ed0ffde54) | Sep 22, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1bec04d42d](https://linux-hardware.org/?probe=1bec04d42d) | Sep 21, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b35ec1a833](https://linux-hardware.org/?probe=b35ec1a833) | Sep 21, 2022 |
| HP            | Pavilion g7                 | Notebook    | [a5f3f12174](https://linux-hardware.org/?probe=a5f3f12174) | Sep 20, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [af2eb79f4c](https://linux-hardware.org/?probe=af2eb79f4c) | Sep 20, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| HP            | 2B05                        | Desktop     | [c2dcdaa38a](https://linux-hardware.org/?probe=c2dcdaa38a) | Sep 19, 2022 |
| HP            | 2B05                        | Desktop     | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4995ae034f](https://linux-hardware.org/?probe=4995ae034f) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4bf59d7938](https://linux-hardware.org/?probe=4bf59d7938) | Sep 19, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [052bad48c4](https://linux-hardware.org/?probe=052bad48c4) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4aef09c37a](https://linux-hardware.org/?probe=4aef09c37a) | Sep 18, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1d4585c98a](https://linux-hardware.org/?probe=1d4585c98a) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [e85965bc82](https://linux-hardware.org/?probe=e85965bc82) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [0278cf2e45](https://linux-hardware.org/?probe=0278cf2e45) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4c33a54701](https://linux-hardware.org/?probe=4c33a54701) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [52fd47ee14](https://linux-hardware.org/?probe=52fd47ee14) | Sep 15, 2022 |
| Dell          | Latitude 7300               | Notebook    | [9802315270](https://linux-hardware.org/?probe=9802315270) | Sep 14, 2022 |
| Dell          | Latitude 7300               | Notebook    | [5d82c4da95](https://linux-hardware.org/?probe=5d82c4da95) | Sep 14, 2022 |
| HP            | 1497                        | Desktop     | [7d44fed5d5](https://linux-hardware.org/?probe=7d44fed5d5) | Sep 13, 2022 |
| HP            | 1497                        | Desktop     | [3afd83b18b](https://linux-hardware.org/?probe=3afd83b18b) | Sep 13, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | Notebook    | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [bfcf5bab5f](https://linux-hardware.org/?probe=bfcf5bab5f) | Sep 12, 2022 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [5987ef39e4](https://linux-hardware.org/?probe=5987ef39e4) | Sep 11, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f64398226e](https://linux-hardware.org/?probe=f64398226e) | Sep 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8ffb4c23b](https://linux-hardware.org/?probe=c8ffb4c23b) | Sep 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [e77359618c](https://linux-hardware.org/?probe=e77359618c) | Sep 09, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [cf5955c3e1](https://linux-hardware.org/?probe=cf5955c3e1) | Sep 09, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [f6981692e0](https://linux-hardware.org/?probe=f6981692e0) | Sep 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| Rockchip      | Unknown                     | Soc         | [37447111b3](https://linux-hardware.org/?probe=37447111b3) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [308047a7cb](https://linux-hardware.org/?probe=308047a7cb) | Sep 07, 2022 |
| Acer          | 1.0                         | Desktop     | [b81c44ff15](https://linux-hardware.org/?probe=b81c44ff15) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b1edd48233](https://linux-hardware.org/?probe=b1edd48233) | Sep 05, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [a8d726946f](https://linux-hardware.org/?probe=a8d726946f) | Sep 04, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [ed02565650](https://linux-hardware.org/?probe=ed02565650) | Sep 04, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [3f17eeffec](https://linux-hardware.org/?probe=3f17eeffec) | Sep 03, 2022 |
| Dell          | Latitude 7300               | Notebook    | [30994e1857](https://linux-hardware.org/?probe=30994e1857) | Sep 03, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [4080f853b6](https://linux-hardware.org/?probe=4080f853b6) | Sep 03, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d54fe6c0ea](https://linux-hardware.org/?probe=d54fe6c0ea) | Sep 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [47dbe77b54](https://linux-hardware.org/?probe=47dbe77b54) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| Purism        | Librem 14                   | Notebook    | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| HP            | 18E5                        | Desktop     | [e7c5ab6cc4](https://linux-hardware.org/?probe=e7c5ab6cc4) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| HP            | Pavilion 15                 | Notebook    | [19c7cae23c](https://linux-hardware.org/?probe=19c7cae23c) | Aug 31, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [a23b1b0822](https://linux-hardware.org/?probe=a23b1b0822) | Aug 30, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce2bb0938b](https://linux-hardware.org/?probe=ce2bb0938b) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [61b05137a7](https://linux-hardware.org/?probe=61b05137a7) | Aug 26, 2022 |
| ASRock        | X99 WS                      | Desktop     | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| Foxconn       | P35A01                      | Desktop     | [fa220f1ce6](https://linux-hardware.org/?probe=fa220f1ce6) | Aug 25, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [b19844ee21](https://linux-hardware.org/?probe=b19844ee21) | Aug 25, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [6fcc3e058d](https://linux-hardware.org/?probe=6fcc3e058d) | Aug 22, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [d0c0be8be7](https://linux-hardware.org/?probe=d0c0be8be7) | Aug 22, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f269c48ca8](https://linux-hardware.org/?probe=f269c48ca8) | Aug 22, 2022 |
| ASUSTek       | B150M-A                     | Desktop     | [0dac247b92](https://linux-hardware.org/?probe=0dac247b92) | Aug 21, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [a8d4f5e6a0](https://linux-hardware.org/?probe=a8d4f5e6a0) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | Notebook    | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [87fcf5d702](https://linux-hardware.org/?probe=87fcf5d702) | Aug 19, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [0271f9018f](https://linux-hardware.org/?probe=0271f9018f) | Aug 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e2a8c815e](https://linux-hardware.org/?probe=1e2a8c815e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ddc9a7396e](https://linux-hardware.org/?probe=ddc9a7396e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef1cbed5a4](https://linux-hardware.org/?probe=ef1cbed5a4) | Aug 16, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [63d41691ef](https://linux-hardware.org/?probe=63d41691ef) | Aug 15, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [837159c07a](https://linux-hardware.org/?probe=837159c07a) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [6dab67810d](https://linux-hardware.org/?probe=6dab67810d) | Aug 14, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [0b62c9a78f](https://linux-hardware.org/?probe=0b62c9a78f) | Aug 12, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [2487f351d2](https://linux-hardware.org/?probe=2487f351d2) | Aug 12, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [1091d27582](https://linux-hardware.org/?probe=1091d27582) | Aug 11, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [34938e0949](https://linux-hardware.org/?probe=34938e0949) | Aug 11, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [edf947ace6](https://linux-hardware.org/?probe=edf947ace6) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [3fbc687842](https://linux-hardware.org/?probe=3fbc687842) | Aug 08, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [c530c6e2cb](https://linux-hardware.org/?probe=c530c6e2cb) | Aug 08, 2022 |
| HP            | 304Bh                       | Desktop     | [e1e3f301cb](https://linux-hardware.org/?probe=e1e3f301cb) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f91ebc68e8](https://linux-hardware.org/?probe=f91ebc68e8) | Aug 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [b075418a73](https://linux-hardware.org/?probe=b075418a73) | Aug 07, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | Notebook    | [091235281e](https://linux-hardware.org/?probe=091235281e) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [a0f4d75db6](https://linux-hardware.org/?probe=a0f4d75db6) | Aug 06, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | Notebook    | [431684d65c](https://linux-hardware.org/?probe=431684d65c) | Aug 05, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [273c214064](https://linux-hardware.org/?probe=273c214064) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [a2733a0f87](https://linux-hardware.org/?probe=a2733a0f87) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Samsung       | 700G7C                      | Notebook    | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| Dell          | Precision 14 5470           | Notebook    | [089d1a151f](https://linux-hardware.org/?probe=089d1a151f) | Aug 03, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [c52a590c5b](https://linux-hardware.org/?probe=c52a590c5b) | Aug 02, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [64a21844e4](https://linux-hardware.org/?probe=64a21844e4) | Aug 01, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [249d407b66](https://linux-hardware.org/?probe=249d407b66) | Jul 30, 2022 |
| Dell          | 0TP412                      | Desktop     | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [edd98c5418](https://linux-hardware.org/?probe=edd98c5418) | Jul 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3b661517b1](https://linux-hardware.org/?probe=3b661517b1) | Jul 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4fa56bac04](https://linux-hardware.org/?probe=4fa56bac04) | Jul 29, 2022 |
| HP            | 18E7                        | Desktop     | [3d7c1549eb](https://linux-hardware.org/?probe=3d7c1549eb) | Jul 29, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [32c295bae1](https://linux-hardware.org/?probe=32c295bae1) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c3f34f2c91](https://linux-hardware.org/?probe=c3f34f2c91) | Jul 28, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| Acer          | Aspire X1930                | Desktop     | [6a650f512e](https://linux-hardware.org/?probe=6a650f512e) | Jul 27, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [b3df887fe1](https://linux-hardware.org/?probe=b3df887fe1) | Jul 27, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5b4bccdf27](https://linux-hardware.org/?probe=5b4bccdf27) | Jul 27, 2022 |
| ASUSTek       | ZenBook UX325UA             | Notebook    | [587ea51239](https://linux-hardware.org/?probe=587ea51239) | Jul 26, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [960fefaee7](https://linux-hardware.org/?probe=960fefaee7) | Jul 25, 2022 |
| Dell          | Precision 7560              | Notebook    | [2fdcece648](https://linux-hardware.org/?probe=2fdcece648) | Jul 25, 2022 |
| Dell          | Precision 7560              | Notebook    | [02fb353f1e](https://linux-hardware.org/?probe=02fb353f1e) | Jul 25, 2022 |
| Gigabyte      | Z390 M-CF                   | Desktop     | [ae2926d93e](https://linux-hardware.org/?probe=ae2926d93e) | Jul 24, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [e29f39ad9e](https://linux-hardware.org/?probe=e29f39ad9e) | Jul 23, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [65c50de21a](https://linux-hardware.org/?probe=65c50de21a) | Jul 22, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [6dba304ba4](https://linux-hardware.org/?probe=6dba304ba4) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Toshiba       | BLB                         | Notebook    | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | Precision 7760              | Notebook    | [742cb747ef](https://linux-hardware.org/?probe=742cb747ef) | Jul 20, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| Dell          | Precision 3561              | Notebook    | [7dfa6ede1e](https://linux-hardware.org/?probe=7dfa6ede1e) | Jul 18, 2022 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [ba6f405592](https://linux-hardware.org/?probe=ba6f405592) | Jul 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [fb9a47e37f](https://linux-hardware.org/?probe=fb9a47e37f) | Jul 17, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [66fe37549d](https://linux-hardware.org/?probe=66fe37549d) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86ac444b35](https://linux-hardware.org/?probe=86ac444b35) | Jul 15, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9da64b4efa](https://linux-hardware.org/?probe=9da64b4efa) | Jul 14, 2022 |
| Star Labs     | StarBook                    | Notebook    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [235fc9b289](https://linux-hardware.org/?probe=235fc9b289) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [a42efbead1](https://linux-hardware.org/?probe=a42efbead1) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [8d8610ee4f](https://linux-hardware.org/?probe=8d8610ee4f) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [4dba0dc5ab](https://linux-hardware.org/?probe=4dba0dc5ab) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [0e13eaa824](https://linux-hardware.org/?probe=0e13eaa824) | Jul 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [1ac13f76b1](https://linux-hardware.org/?probe=1ac13f76b1) | Jul 10, 2022 |
| Dell          | Precision 5570              | Notebook    | [e4409961fd](https://linux-hardware.org/?probe=e4409961fd) | Jul 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [dcbdde4fdf](https://linux-hardware.org/?probe=dcbdde4fdf) | Jul 06, 2022 |
| Dell          | 0M858N A01                  | Desktop     | [36aca635a8](https://linux-hardware.org/?probe=36aca635a8) | Jul 06, 2022 |
| MSI           | MS-AA71                     | All in one  | [4e7d1d05d6](https://linux-hardware.org/?probe=4e7d1d05d6) | Jul 06, 2022 |
| Dell          | 0GM819                      | Desktop     | [a366983f6a](https://linux-hardware.org/?probe=a366983f6a) | Jul 06, 2022 |
| Dell          | 0GM819                      | Desktop     | [78e233e42f](https://linux-hardware.org/?probe=78e233e42f) | Jul 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [498f4edafb](https://linux-hardware.org/?probe=498f4edafb) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [1264fab131](https://linux-hardware.org/?probe=1264fab131) | Jul 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [fad2fe7297](https://linux-hardware.org/?probe=fad2fe7297) | Jul 04, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [848a8591de](https://linux-hardware.org/?probe=848a8591de) | Jul 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [0cb6549f23](https://linux-hardware.org/?probe=0cb6549f23) | Jun 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0f4c661912](https://linux-hardware.org/?probe=0f4c661912) | Jun 27, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [27343a622f](https://linux-hardware.org/?probe=27343a622f) | Jun 25, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5dd67bc68a](https://linux-hardware.org/?probe=5dd67bc68a) | Jun 25, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [57660d8f0f](https://linux-hardware.org/?probe=57660d8f0f) | Jun 24, 2022 |
| ASUSTek       | N61Vn                       | Notebook    | [72d62f755d](https://linux-hardware.org/?probe=72d62f755d) | Jun 24, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [cfa8a05299](https://linux-hardware.org/?probe=cfa8a05299) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [5188bfb9d3](https://linux-hardware.org/?probe=5188bfb9d3) | Jun 23, 2022 |
| HP            | 2B05                        | Desktop     | [677bb9d569](https://linux-hardware.org/?probe=677bb9d569) | Jun 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [273f19137a](https://linux-hardware.org/?probe=273f19137a) | Jun 21, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [07506542b5](https://linux-hardware.org/?probe=07506542b5) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | Desktop     | [280d4af2d2](https://linux-hardware.org/?probe=280d4af2d2) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | Desktop     | [c90adf6d43](https://linux-hardware.org/?probe=c90adf6d43) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [af5bb55ac5](https://linux-hardware.org/?probe=af5bb55ac5) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| HP            | 2B05                        | Desktop     | [a49ebb4aed](https://linux-hardware.org/?probe=a49ebb4aed) | Jun 19, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [5448ad3e33](https://linux-hardware.org/?probe=5448ad3e33) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [f76be8391b](https://linux-hardware.org/?probe=f76be8391b) | Jun 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [530c081484](https://linux-hardware.org/?probe=530c081484) | Jun 17, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [f75b5004f9](https://linux-hardware.org/?probe=f75b5004f9) | Jun 17, 2022 |
| Gigabyte      | H67M-UD2H-B3                | Desktop     | [1c8dd20713](https://linux-hardware.org/?probe=1c8dd20713) | Jun 16, 2022 |
| Acer          | Aspire TC-230               | Desktop     | [bec506a849](https://linux-hardware.org/?probe=bec506a849) | Jun 16, 2022 |
| Acer          | Predator G3610              | Desktop     | [ff347cdb53](https://linux-hardware.org/?probe=ff347cdb53) | Jun 15, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [fe963bacc6](https://linux-hardware.org/?probe=fe963bacc6) | Jun 14, 2022 |
| congatec      | conga-PA7 A.0               | Mini pc     | [e0c6234f77](https://linux-hardware.org/?probe=e0c6234f77) | Jun 13, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [8153e1c68e](https://linux-hardware.org/?probe=8153e1c68e) | Jun 13, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [12fb5f93c9](https://linux-hardware.org/?probe=12fb5f93c9) | Jun 13, 2022 |
| Dell          | Precision 7520              | Notebook    | [002f7ce017](https://linux-hardware.org/?probe=002f7ce017) | Jun 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [d9cffc5cc6](https://linux-hardware.org/?probe=d9cffc5cc6) | Jun 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63dcba0c57](https://linux-hardware.org/?probe=63dcba0c57) | Jun 10, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [884806d49f](https://linux-hardware.org/?probe=884806d49f) | Jun 09, 2022 |
| Acer          | Aspire 5749Z                | Notebook    | [d7020510e2](https://linux-hardware.org/?probe=d7020510e2) | Jun 08, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [3de14e06c5](https://linux-hardware.org/?probe=3de14e06c5) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [685df41f04](https://linux-hardware.org/?probe=685df41f04) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ba86261552](https://linux-hardware.org/?probe=ba86261552) | Jun 06, 2022 |
| Intel         | NUC11TNBi7 M11895-402       | Mini pc     | [4b972d5b22](https://linux-hardware.org/?probe=4b972d5b22) | Jun 05, 2022 |
| Dell          | Latitude D630               | Notebook    | [fb28805860](https://linux-hardware.org/?probe=fb28805860) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [dc7a83708a](https://linux-hardware.org/?probe=dc7a83708a) | Jun 04, 2022 |
| HP            | ProBook 6450b               | Notebook    | [52467822a6](https://linux-hardware.org/?probe=52467822a6) | Jun 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [b414c22d34](https://linux-hardware.org/?probe=b414c22d34) | Jun 02, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [90b0bc8a37](https://linux-hardware.org/?probe=90b0bc8a37) | Jun 02, 2022 |
| HP            | ProBook 6450b               | Notebook    | [26bce40d20](https://linux-hardware.org/?probe=26bce40d20) | Jun 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [f4906f3799](https://linux-hardware.org/?probe=f4906f3799) | Jun 01, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [860be26e14](https://linux-hardware.org/?probe=860be26e14) | May 29, 2022 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [63747954e9](https://linux-hardware.org/?probe=63747954e9) | May 29, 2022 |
| Lenovo        | ThinkPad W500 4061W8H       | Notebook    | [db9160e089](https://linux-hardware.org/?probe=db9160e089) | May 29, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [bd97a6b3dd](https://linux-hardware.org/?probe=bd97a6b3dd) | May 28, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [b32a949b01](https://linux-hardware.org/?probe=b32a949b01) | May 28, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e64dfe3f6f](https://linux-hardware.org/?probe=e64dfe3f6f) | May 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [8f40318937](https://linux-hardware.org/?probe=8f40318937) | May 27, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c025e27a90](https://linux-hardware.org/?probe=c025e27a90) | May 27, 2022 |
| ASUSTek       | U31Jg                       | Notebook    | [b761173e5e](https://linux-hardware.org/?probe=b761173e5e) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | Notebook    | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [25e4d08ac2](https://linux-hardware.org/?probe=25e4d08ac2) | May 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [2d28231751](https://linux-hardware.org/?probe=2d28231751) | May 25, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c00f6e1b2a](https://linux-hardware.org/?probe=c00f6e1b2a) | May 24, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [683ff3ab1a](https://linux-hardware.org/?probe=683ff3ab1a) | May 24, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [594e42160c](https://linux-hardware.org/?probe=594e42160c) | May 22, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b620a51628](https://linux-hardware.org/?probe=b620a51628) | May 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Gigabyte      | H67N-USB3-B3                | Desktop     | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| HP            | 635                         | Notebook    | [2421582549](https://linux-hardware.org/?probe=2421582549) | May 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f02fa869ff](https://linux-hardware.org/?probe=f02fa869ff) | May 20, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [bdc2dbdba3](https://linux-hardware.org/?probe=bdc2dbdba3) | May 19, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [97e7c3fd74](https://linux-hardware.org/?probe=97e7c3fd74) | May 19, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a1cbc8b911](https://linux-hardware.org/?probe=a1cbc8b911) | May 19, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [736bd1ab68](https://linux-hardware.org/?probe=736bd1ab68) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [6c41f73e8a](https://linux-hardware.org/?probe=6c41f73e8a) | May 18, 2022 |
| HP            | 635                         | Notebook    | [3168b50a90](https://linux-hardware.org/?probe=3168b50a90) | May 18, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [efd77955ef](https://linux-hardware.org/?probe=efd77955ef) | May 15, 2022 |
| MSI           | GS73VR 7RG                  | Notebook    | [3815425b08](https://linux-hardware.org/?probe=3815425b08) | May 15, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [70809098f6](https://linux-hardware.org/?probe=70809098f6) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [7f06d07456](https://linux-hardware.org/?probe=7f06d07456) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [a9c9d7da8d](https://linux-hardware.org/?probe=a9c9d7da8d) | May 14, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [bfcd03ba86](https://linux-hardware.org/?probe=bfcd03ba86) | May 14, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [2152787c64](https://linux-hardware.org/?probe=2152787c64) | May 13, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [235beb3d5f](https://linux-hardware.org/?probe=235beb3d5f) | May 13, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [6f09e11de7](https://linux-hardware.org/?probe=6f09e11de7) | May 12, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [cff8de13ce](https://linux-hardware.org/?probe=cff8de13ce) | May 12, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [ebf71be1f5](https://linux-hardware.org/?probe=ebf71be1f5) | May 12, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [a80ef1636d](https://linux-hardware.org/?probe=a80ef1636d) | May 12, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2342a9d519](https://linux-hardware.org/?probe=2342a9d519) | May 12, 2022 |
| ASUSTek       | A6U                         | Notebook    | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [38bc924977](https://linux-hardware.org/?probe=38bc924977) | May 12, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [9f28ef42a4](https://linux-hardware.org/?probe=9f28ef42a4) | May 11, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [6a69aab6ee](https://linux-hardware.org/?probe=6a69aab6ee) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5b6165bc68](https://linux-hardware.org/?probe=5b6165bc68) | May 10, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [0bec73d852](https://linux-hardware.org/?probe=0bec73d852) | May 10, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [56c5f8cad8](https://linux-hardware.org/?probe=56c5f8cad8) | May 09, 2022 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | Notebook    | [615d6650a0](https://linux-hardware.org/?probe=615d6650a0) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | Notebook    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| Samsung       | 750XDA                      | Notebook    | [466689475e](https://linux-hardware.org/?probe=466689475e) | May 07, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Dell          | Precision M4700             | Notebook    | [81cc8ba45c](https://linux-hardware.org/?probe=81cc8ba45c) | May 06, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [be200c9e57](https://linux-hardware.org/?probe=be200c9e57) | May 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [64eb136705](https://linux-hardware.org/?probe=64eb136705) | May 03, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e2dfdb6af2](https://linux-hardware.org/?probe=e2dfdb6af2) | May 03, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [1bd7f7cd93](https://linux-hardware.org/?probe=1bd7f7cd93) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [1c3645cb67](https://linux-hardware.org/?probe=1c3645cb67) | May 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [f6cc5e2ad5](https://linux-hardware.org/?probe=f6cc5e2ad5) | May 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [adc0bdd7f8](https://linux-hardware.org/?probe=adc0bdd7f8) | May 01, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [e8fee79ec7](https://linux-hardware.org/?probe=e8fee79ec7) | Apr 30, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [995ea9538b](https://linux-hardware.org/?probe=995ea9538b) | Apr 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| ASUSTek       | B150M-A                     | Desktop     | [fa213f6681](https://linux-hardware.org/?probe=fa213f6681) | Apr 28, 2022 |
| Gigabyte      | H67M-UD2H-B3                | Desktop     | [7defbcb7bb](https://linux-hardware.org/?probe=7defbcb7bb) | Apr 28, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | Notebook    | [58076aa8e9](https://linux-hardware.org/?probe=58076aa8e9) | Apr 28, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [37b195945a](https://linux-hardware.org/?probe=37b195945a) | Apr 28, 2022 |
| Dell          | Latitude 7420               | Notebook    | [8e3bcab404](https://linux-hardware.org/?probe=8e3bcab404) | Apr 28, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [11a6c8f173](https://linux-hardware.org/?probe=11a6c8f173) | Apr 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [3b4a331875](https://linux-hardware.org/?probe=3b4a331875) | Apr 26, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | Notebook    | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [8cba4892be](https://linux-hardware.org/?probe=8cba4892be) | Apr 25, 2022 |
| ASUSTek       | UX461UN                     | Convertible | [57bbbf3023](https://linux-hardware.org/?probe=57bbbf3023) | Apr 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c0af99fa7e](https://linux-hardware.org/?probe=c0af99fa7e) | Apr 24, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [6cc8c69a6c](https://linux-hardware.org/?probe=6cc8c69a6c) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS3FX0... | Notebook    | [00d3556f08](https://linux-hardware.org/?probe=00d3556f08) | Apr 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [7988499108](https://linux-hardware.org/?probe=7988499108) | Apr 23, 2022 |
| HP            | 18E9                        | Desktop     | [36ff483a2f](https://linux-hardware.org/?probe=36ff483a2f) | Apr 23, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [cd369fb3e3](https://linux-hardware.org/?probe=cd369fb3e3) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [4548a301f8](https://linux-hardware.org/?probe=4548a301f8) | Apr 22, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [757b005814](https://linux-hardware.org/?probe=757b005814) | Apr 21, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [ca406cf975](https://linux-hardware.org/?probe=ca406cf975) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [32d9d8c8df](https://linux-hardware.org/?probe=32d9d8c8df) | Apr 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [94e43177eb](https://linux-hardware.org/?probe=94e43177eb) | Apr 21, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4c46fa8a5b](https://linux-hardware.org/?probe=4c46fa8a5b) | Apr 19, 2022 |
| ASUSTek       | G551JW                      | Notebook    | [b0d7f099f5](https://linux-hardware.org/?probe=b0d7f099f5) | Apr 18, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | Notebook    | [7855e19861](https://linux-hardware.org/?probe=7855e19861) | Apr 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ce158f41e2](https://linux-hardware.org/?probe=ce158f41e2) | Apr 17, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [5bd64f9988](https://linux-hardware.org/?probe=5bd64f9988) | Apr 17, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| Toshiba       | BLB                         | Notebook    | [903779c2b2](https://linux-hardware.org/?probe=903779c2b2) | Apr 16, 2022 |
| Toshiba       | BLB                         | Notebook    | [1dffc347dd](https://linux-hardware.org/?probe=1dffc347dd) | Apr 16, 2022 |
| MSI           | 990FXA-GD80                 | Desktop     | [391705d3c1](https://linux-hardware.org/?probe=391705d3c1) | Apr 15, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [c42de00504](https://linux-hardware.org/?probe=c42de00504) | Apr 15, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [8994d0ea9f](https://linux-hardware.org/?probe=8994d0ea9f) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | Notebook    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| Dell          | Latitude E7450              | Notebook    | [9af0006104](https://linux-hardware.org/?probe=9af0006104) | Apr 15, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [b2fdf48a7f](https://linux-hardware.org/?probe=b2fdf48a7f) | Apr 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [dba38dc289](https://linux-hardware.org/?probe=dba38dc289) | Apr 13, 2022 |
| HP            | 18E5                        | Desktop     | [3b4f9e8525](https://linux-hardware.org/?probe=3b4f9e8525) | Apr 13, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [ca14d0eb57](https://linux-hardware.org/?probe=ca14d0eb57) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [0056c8d32e](https://linux-hardware.org/?probe=0056c8d32e) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [68aa564b9f](https://linux-hardware.org/?probe=68aa564b9f) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [d9f1aff70a](https://linux-hardware.org/?probe=d9f1aff70a) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [b9b9565fae](https://linux-hardware.org/?probe=b9b9565fae) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | Notebook    | [8fdcef45a9](https://linux-hardware.org/?probe=8fdcef45a9) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ce0316a106](https://linux-hardware.org/?probe=ce0316a106) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [70e4d389af](https://linux-hardware.org/?probe=70e4d389af) | Apr 10, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Maxtang       | FP30 V1.0                   | Desktop     | [2062d8578e](https://linux-hardware.org/?probe=2062d8578e) | Apr 08, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [16fa67b6c1](https://linux-hardware.org/?probe=16fa67b6c1) | Apr 07, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [fca3b357c3](https://linux-hardware.org/?probe=fca3b357c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f4c5281aa9](https://linux-hardware.org/?probe=f4c5281aa9) | Apr 07, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [1c62a4c421](https://linux-hardware.org/?probe=1c62a4c421) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [53e59cf805](https://linux-hardware.org/?probe=53e59cf805) | Apr 06, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [68397184cf](https://linux-hardware.org/?probe=68397184cf) | Apr 06, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [f3bc34e630](https://linux-hardware.org/?probe=f3bc34e630) | Apr 05, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [e3a9cdfd95](https://linux-hardware.org/?probe=e3a9cdfd95) | Apr 05, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [31836fcaa9](https://linux-hardware.org/?probe=31836fcaa9) | Apr 05, 2022 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [4361e01e42](https://linux-hardware.org/?probe=4361e01e42) | Apr 04, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [2af47af588](https://linux-hardware.org/?probe=2af47af588) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [3e01b6fb25](https://linux-hardware.org/?probe=3e01b6fb25) | Apr 03, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [bcff3a3aef](https://linux-hardware.org/?probe=bcff3a3aef) | Apr 03, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [893945236a](https://linux-hardware.org/?probe=893945236a) | Apr 03, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [b3a74c237d](https://linux-hardware.org/?probe=b3a74c237d) | Apr 02, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [01a521b3d1](https://linux-hardware.org/?probe=01a521b3d1) | Apr 02, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2d4957c88f](https://linux-hardware.org/?probe=2d4957c88f) | Apr 02, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [0b247aa185](https://linux-hardware.org/?probe=0b247aa185) | Mar 30, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [137477b9ef](https://linux-hardware.org/?probe=137477b9ef) | Mar 29, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [3a33018680](https://linux-hardware.org/?probe=3a33018680) | Mar 29, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [4ab227f4be](https://linux-hardware.org/?probe=4ab227f4be) | Mar 29, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [e4c1632bc2](https://linux-hardware.org/?probe=e4c1632bc2) | Mar 28, 2022 |
| Dell          | Precision 5540              | Notebook    | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [d5f059e17d](https://linux-hardware.org/?probe=d5f059e17d) | Mar 26, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [f625382909](https://linux-hardware.org/?probe=f625382909) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [e6a885c5df](https://linux-hardware.org/?probe=e6a885c5df) | Mar 26, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e534bb83a](https://linux-hardware.org/?probe=4e534bb83a) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [d08bb2f15b](https://linux-hardware.org/?probe=d08bb2f15b) | Mar 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6af3c57a8a](https://linux-hardware.org/?probe=6af3c57a8a) | Mar 24, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [e0ae9fa252](https://linux-hardware.org/?probe=e0ae9fa252) | Mar 24, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [9f295312dc](https://linux-hardware.org/?probe=9f295312dc) | Mar 21, 2022 |
| Dell          | Latitude 7300               | Notebook    | [751dc53e2b](https://linux-hardware.org/?probe=751dc53e2b) | Mar 20, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [b312650d8d](https://linux-hardware.org/?probe=b312650d8d) | Mar 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [4191a185d4](https://linux-hardware.org/?probe=4191a185d4) | Mar 19, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [f71ac898a8](https://linux-hardware.org/?probe=f71ac898a8) | Mar 19, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [2b46add19f](https://linux-hardware.org/?probe=2b46add19f) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK E546               | Notebook    | [247dd3e47c](https://linux-hardware.org/?probe=247dd3e47c) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | Notebook    | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [21c958ad5f](https://linux-hardware.org/?probe=21c958ad5f) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f9345bd168](https://linux-hardware.org/?probe=f9345bd168) | Mar 12, 2022 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | Desktop     | [e6c507dff4](https://linux-hardware.org/?probe=e6c507dff4) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [84e80f8c56](https://linux-hardware.org/?probe=84e80f8c56) | Mar 12, 2022 |
| ASUSTek       | G11CD-K                     | Desktop     | [f3347643b0](https://linux-hardware.org/?probe=f3347643b0) | Mar 12, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [d7c05bb862](https://linux-hardware.org/?probe=d7c05bb862) | Mar 11, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c4d9b11074](https://linux-hardware.org/?probe=c4d9b11074) | Mar 10, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [8b499a7b72](https://linux-hardware.org/?probe=8b499a7b72) | Mar 08, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3e4ac3a045](https://linux-hardware.org/?probe=3e4ac3a045) | Mar 07, 2022 |
| HP            | ENVY 15                     | Notebook    | [a4f5eedd3c](https://linux-hardware.org/?probe=a4f5eedd3c) | Mar 06, 2022 |
| ASUSTek       | E205SA                      | Notebook    | [4c896c9379](https://linux-hardware.org/?probe=4c896c9379) | Mar 05, 2022 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [db85b45bf6](https://linux-hardware.org/?probe=db85b45bf6) | Mar 05, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [c04f6c7365](https://linux-hardware.org/?probe=c04f6c7365) | Mar 05, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [3ff867b4e2](https://linux-hardware.org/?probe=3ff867b4e2) | Mar 05, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | Notebook    | [af4563cb12](https://linux-hardware.org/?probe=af4563cb12) | Mar 04, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [2efd176b6f](https://linux-hardware.org/?probe=2efd176b6f) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [88a973e27f](https://linux-hardware.org/?probe=88a973e27f) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [d1c5534f6d](https://linux-hardware.org/?probe=d1c5534f6d) | Feb 27, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [2b2338382c](https://linux-hardware.org/?probe=2b2338382c) | Feb 27, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [ff2de5c1da](https://linux-hardware.org/?probe=ff2de5c1da) | Feb 27, 2022 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | Desktop     | [4ae8fd98cc](https://linux-hardware.org/?probe=4ae8fd98cc) | Feb 26, 2022 |
| Sony          | VPCEB36FG                   | Notebook    | [d46f784fbb](https://linux-hardware.org/?probe=d46f784fbb) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [cfd0806662](https://linux-hardware.org/?probe=cfd0806662) | Feb 25, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [1434453fc0](https://linux-hardware.org/?probe=1434453fc0) | Feb 24, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [3bfa40a4c8](https://linux-hardware.org/?probe=3bfa40a4c8) | Feb 24, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [1cc7d4542a](https://linux-hardware.org/?probe=1cc7d4542a) | Feb 23, 2022 |
| Elo Touch ... | Geminilake Continental Z... | Desktop     | [6d9bcef1c7](https://linux-hardware.org/?probe=6d9bcef1c7) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [d31201b74c](https://linux-hardware.org/?probe=d31201b74c) | Feb 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [672f08c769](https://linux-hardware.org/?probe=672f08c769) | Feb 22, 2022 |
| HP            | 86C7                        | All in one  | [efb6906a46](https://linux-hardware.org/?probe=efb6906a46) | Feb 21, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [1c3e6a4af1](https://linux-hardware.org/?probe=1c3e6a4af1) | Feb 21, 2022 |
| Dell          | Precision 3510              | Notebook    | [3956ab645b](https://linux-hardware.org/?probe=3956ab645b) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [d2119e4516](https://linux-hardware.org/?probe=d2119e4516) | Feb 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [129c8a24d9](https://linux-hardware.org/?probe=129c8a24d9) | Feb 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [34117f82de](https://linux-hardware.org/?probe=34117f82de) | Feb 20, 2022 |
| ZEPTO         | ZNOTE                       | Notebook    | [5ff5c2b966](https://linux-hardware.org/?probe=5ff5c2b966) | Feb 20, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [ed1a78c5a6](https://linux-hardware.org/?probe=ed1a78c5a6) | Feb 20, 2022 |
| Dell          | 0P4T42 A01                  | All in one  | [6b8b0ec7f9](https://linux-hardware.org/?probe=6b8b0ec7f9) | Feb 19, 2022 |
| HP            | 3032h                       | Desktop     | [df23e573ba](https://linux-hardware.org/?probe=df23e573ba) | Feb 19, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7b9e4b097d](https://linux-hardware.org/?probe=7b9e4b097d) | Feb 18, 2022 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [b0cf9aa220](https://linux-hardware.org/?probe=b0cf9aa220) | Feb 18, 2022 |
| HP            | Pavilion dv6                | Notebook    | [012e2b5d56](https://linux-hardware.org/?probe=012e2b5d56) | Feb 15, 2022 |
| Dell          | Latitude 5480               | Notebook    | [62ab6cb2c3](https://linux-hardware.org/?probe=62ab6cb2c3) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [cc35d4696d](https://linux-hardware.org/?probe=cc35d4696d) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| HP            | 829A                        | Mini pc     | [dfd0cb667c](https://linux-hardware.org/?probe=dfd0cb667c) | Feb 12, 2022 |
| Dell          | Latitude E6430              | Notebook    | [4b91478aaa](https://linux-hardware.org/?probe=4b91478aaa) | Feb 11, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [0600ea1165](https://linux-hardware.org/?probe=0600ea1165) | Feb 11, 2022 |
| Dell          | Latitude D620               | Notebook    | [dfbcd57dc6](https://linux-hardware.org/?probe=dfbcd57dc6) | Feb 10, 2022 |
| HP            | ENVY 15                     | Notebook    | [91c40a9559](https://linux-hardware.org/?probe=91c40a9559) | Feb 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [8f36d1baac](https://linux-hardware.org/?probe=8f36d1baac) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [accf5c8a43](https://linux-hardware.org/?probe=accf5c8a43) | Feb 08, 2022 |
| Lenovo        | E31-70 80KX                 | Notebook    | [d4fe754aa4](https://linux-hardware.org/?probe=d4fe754aa4) | Feb 07, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [2427f8c1da](https://linux-hardware.org/?probe=2427f8c1da) | Feb 07, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [386053c3ce](https://linux-hardware.org/?probe=386053c3ce) | Feb 07, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [fbea64f951](https://linux-hardware.org/?probe=fbea64f951) | Feb 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [db7f189b71](https://linux-hardware.org/?probe=db7f189b71) | Feb 06, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [70c2ff9419](https://linux-hardware.org/?probe=70c2ff9419) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [3a8c47094b](https://linux-hardware.org/?probe=3a8c47094b) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [ae06eadc57](https://linux-hardware.org/?probe=ae06eadc57) | Feb 05, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cb34c3126d](https://linux-hardware.org/?probe=cb34c3126d) | Feb 05, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a8cc9c8481](https://linux-hardware.org/?probe=a8cc9c8481) | Feb 03, 2022 |
| Packard Be... | IMEDIA S2985                | Desktop     | [661d923ce2](https://linux-hardware.org/?probe=661d923ce2) | Feb 03, 2022 |
| Dell          | 0773VG A01                  | Desktop     | [b1c8ece218](https://linux-hardware.org/?probe=b1c8ece218) | Feb 03, 2022 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [15419beff9](https://linux-hardware.org/?probe=15419beff9) | Feb 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [c51e8a279f](https://linux-hardware.org/?probe=c51e8a279f) | Feb 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [19cb128817](https://linux-hardware.org/?probe=19cb128817) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [108d91c953](https://linux-hardware.org/?probe=108d91c953) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [d866cabd88](https://linux-hardware.org/?probe=d866cabd88) | Feb 02, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [a6321e237c](https://linux-hardware.org/?probe=a6321e237c) | Feb 01, 2022 |
| Acer          | Predator G3610              | Desktop     | [126f12bd14](https://linux-hardware.org/?probe=126f12bd14) | Feb 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [bbe17ee442](https://linux-hardware.org/?probe=bbe17ee442) | Jan 31, 2022 |
| ASUSTek       | GR8                         | Notebook    | [1d8f5be27c](https://linux-hardware.org/?probe=1d8f5be27c) | Jan 30, 2022 |
| Linx          | LAMINALTT8W4G-HBN           | Tablet      | [6350a05df4](https://linux-hardware.org/?probe=6350a05df4) | Jan 29, 2022 |
| Linx          | LAMINALTT8W4G-HBN           | Tablet      | [fa389062e6](https://linux-hardware.org/?probe=fa389062e6) | Jan 29, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [a59b4aa98d](https://linux-hardware.org/?probe=a59b4aa98d) | Jan 29, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [fdf21ecdef](https://linux-hardware.org/?probe=fdf21ecdef) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [b584b0b69a](https://linux-hardware.org/?probe=b584b0b69a) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [1a1b794c06](https://linux-hardware.org/?probe=1a1b794c06) | Jan 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [6b771832b8](https://linux-hardware.org/?probe=6b771832b8) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | Notebook    | [1d8bb5fbe6](https://linux-hardware.org/?probe=1d8bb5fbe6) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | Notebook    | [87aa03d881](https://linux-hardware.org/?probe=87aa03d881) | Jan 27, 2022 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | Desktop     | [a0aecb00c0](https://linux-hardware.org/?probe=a0aecb00c0) | Jan 26, 2022 |
| AAEON         | GENE-BT05 V1.1              | Desktop     | [385d6a7c2e](https://linux-hardware.org/?probe=385d6a7c2e) | Jan 25, 2022 |
| MSI           | B85M-E45                    | Desktop     | [5751d3e736](https://linux-hardware.org/?probe=5751d3e736) | Jan 25, 2022 |
| MSI           | B85M-E45                    | Desktop     | [034f7c3687](https://linux-hardware.org/?probe=034f7c3687) | Jan 25, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [c5c764ccd7](https://linux-hardware.org/?probe=c5c764ccd7) | Jan 24, 2022 |
| Dell          | Latitude E7440              | Notebook    | [74aa958191](https://linux-hardware.org/?probe=74aa958191) | Jan 23, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [e5aea099ea](https://linux-hardware.org/?probe=e5aea099ea) | Jan 23, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [f82cb83a85](https://linux-hardware.org/?probe=f82cb83a85) | Jan 23, 2022 |
| Notebook      | N13xWU                      | Notebook    | [0d615c6812](https://linux-hardware.org/?probe=0d615c6812) | Jan 22, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [2aa2fc8ed9](https://linux-hardware.org/?probe=2aa2fc8ed9) | Jan 22, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [95afa35615](https://linux-hardware.org/?probe=95afa35615) | Jan 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [76ac118b42](https://linux-hardware.org/?probe=76ac118b42) | Jan 20, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [e5b1e0c400](https://linux-hardware.org/?probe=e5b1e0c400) | Jan 20, 2022 |
| Dell          | Inspiron 5721               | Notebook    | [5310b893aa](https://linux-hardware.org/?probe=5310b893aa) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c4103d5c5a](https://linux-hardware.org/?probe=c4103d5c5a) | Jan 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a7cc00f1bb](https://linux-hardware.org/?probe=a7cc00f1bb) | Jan 18, 2022 |
| Dell          | Latitude 7480               | Notebook    | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [2dfe5563ef](https://linux-hardware.org/?probe=2dfe5563ef) | Jan 17, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [35b6de7b5d](https://linux-hardware.org/?probe=35b6de7b5d) | Jan 16, 2022 |
| Dell          | Precision 3561              | Notebook    | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [2e8135c20d](https://linux-hardware.org/?probe=2e8135c20d) | Jan 15, 2022 |
| Intel         | NUC7i7BNB J31145-304        | Mini pc     | [2b7802edc0](https://linux-hardware.org/?probe=2b7802edc0) | Jan 15, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| Lenovo        | ThinkPad X240 20AMS6170H    | Notebook    | [03fc719875](https://linux-hardware.org/?probe=03fc719875) | Jan 14, 2022 |
| Seco          | C40 C                       | Desktop     | [4243badc3f](https://linux-hardware.org/?probe=4243badc3f) | Jan 14, 2022 |
| Dell          | Latitude 5290               | Notebook    | [f1c632a454](https://linux-hardware.org/?probe=f1c632a454) | Jan 12, 2022 |
| MSI           | Z270 GAMING M7              | Desktop     | [4899dd71f5](https://linux-hardware.org/?probe=4899dd71f5) | Jan 12, 2022 |
| MSI           | Z270 GAMING M7              | Desktop     | [9fa194bf62](https://linux-hardware.org/?probe=9fa194bf62) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9856d52b0](https://linux-hardware.org/?probe=d9856d52b0) | Jan 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [8b8a13f3b4](https://linux-hardware.org/?probe=8b8a13f3b4) | Jan 11, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [19857c8f84](https://linux-hardware.org/?probe=19857c8f84) | Jan 11, 2022 |
| ASUSTek       | UX310UQ                     | Notebook    | [a9b40e5f8c](https://linux-hardware.org/?probe=a9b40e5f8c) | Jan 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [0fa4a81a77](https://linux-hardware.org/?probe=0fa4a81a77) | Jan 09, 2022 |
| Sony          | VPCEB3S1E                   | Notebook    | [6f78e2d423](https://linux-hardware.org/?probe=6f78e2d423) | Jan 07, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [42db32249d](https://linux-hardware.org/?probe=42db32249d) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| HP            | EliteBook 1040 G2           | Notebook    | [ca6f52fbeb](https://linux-hardware.org/?probe=ca6f52fbeb) | Jan 06, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [14a4cdc223](https://linux-hardware.org/?probe=14a4cdc223) | Jan 06, 2022 |
| Samsung       | 935XDB                      | Notebook    | [1bb7122515](https://linux-hardware.org/?probe=1bb7122515) | Jan 06, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | Notebook    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Supermicro    | X9DRW                       | Server      | [31684ad7e4](https://linux-hardware.org/?probe=31684ad7e4) | Jan 06, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [649be03cf4](https://linux-hardware.org/?probe=649be03cf4) | Jan 06, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [9ebb75d7a4](https://linux-hardware.org/?probe=9ebb75d7a4) | Jan 06, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [27756cb751](https://linux-hardware.org/?probe=27756cb751) | Jan 05, 2022 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [81efe23b11](https://linux-hardware.org/?probe=81efe23b11) | Jan 04, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [446ac9b29a](https://linux-hardware.org/?probe=446ac9b29a) | Jan 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ef297a39aa](https://linux-hardware.org/?probe=ef297a39aa) | Jan 04, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [492d47c1fa](https://linux-hardware.org/?probe=492d47c1fa) | Jan 04, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [226a67696a](https://linux-hardware.org/?probe=226a67696a) | Jan 03, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [a1905b9b4a](https://linux-hardware.org/?probe=a1905b9b4a) | Jan 03, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| MSI           | H67MA-E45                   | Desktop     | [d15eaff050](https://linux-hardware.org/?probe=d15eaff050) | Jan 01, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [8317742b36](https://linux-hardware.org/?probe=8317742b36) | Jan 01, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4a20cd5429](https://linux-hardware.org/?probe=4a20cd5429) | Jan 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fbc9c7ad1a](https://linux-hardware.org/?probe=fbc9c7ad1a) | Jan 01, 2022 |
| MSI           | MS-7211                     | Desktop     | [f8d1e7a88c](https://linux-hardware.org/?probe=f8d1e7a88c) | Dec 31, 2021 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [7a756782d8](https://linux-hardware.org/?probe=7a756782d8) | Dec 31, 2021 |
| ZEPTO         | ZNOTE                       | Notebook    | [f81a927e9b](https://linux-hardware.org/?probe=f81a927e9b) | Dec 31, 2021 |
| Dell          | Precision 5540              | Notebook    | [ba4fef27b9](https://linux-hardware.org/?probe=ba4fef27b9) | Dec 30, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| Gigabyte      | F2A88XM-DS2P                | Desktop     | [75eea6ae2f](https://linux-hardware.org/?probe=75eea6ae2f) | Dec 30, 2021 |
| Pegatron      | Narra6                      | Desktop     | [da3be9b31b](https://linux-hardware.org/?probe=da3be9b31b) | Dec 29, 2021 |
| MSI           | MS-7211                     | Desktop     | [3524bec1c8](https://linux-hardware.org/?probe=3524bec1c8) | Dec 29, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [02f8579bf3](https://linux-hardware.org/?probe=02f8579bf3) | Dec 29, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [51d4addbb3](https://linux-hardware.org/?probe=51d4addbb3) | Dec 29, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DM... | Notebook    | [e1ba67fc0f](https://linux-hardware.org/?probe=e1ba67fc0f) | Dec 28, 2021 |
| eMachines     | E525                        | Notebook    | [fd80580005](https://linux-hardware.org/?probe=fd80580005) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| Acer          | AOHAPPY                     | Notebook    | [3a8a8f6b8e](https://linux-hardware.org/?probe=3a8a8f6b8e) | Dec 27, 2021 |
| Acer          | Swift SF314-511             | Notebook    | [3a201fd936](https://linux-hardware.org/?probe=3a201fd936) | Dec 27, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [64e387d031](https://linux-hardware.org/?probe=64e387d031) | Dec 27, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [705810cc40](https://linux-hardware.org/?probe=705810cc40) | Dec 25, 2021 |
| eMachines     | E525                        | Notebook    | [fcc3b2a5e3](https://linux-hardware.org/?probe=fcc3b2a5e3) | Dec 25, 2021 |
| eMachines     | E525                        | Notebook    | [e5853e5629](https://linux-hardware.org/?probe=e5853e5629) | Dec 25, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e1713d01a4](https://linux-hardware.org/?probe=e1713d01a4) | Dec 25, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [edad019098](https://linux-hardware.org/?probe=edad019098) | Dec 23, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [0a1cd1d1af](https://linux-hardware.org/?probe=0a1cd1d1af) | Dec 23, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [9dd62bbf73](https://linux-hardware.org/?probe=9dd62bbf73) | Dec 23, 2021 |
| Dell          | 0Y56T3 A00                  | Desktop     | [456cb4ebcc](https://linux-hardware.org/?probe=456cb4ebcc) | Dec 23, 2021 |
| Toshiba       | Satellite L50D-B            | Notebook    | [b5a9d0b1dc](https://linux-hardware.org/?probe=b5a9d0b1dc) | Dec 21, 2021 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [42d4ee98ce](https://linux-hardware.org/?probe=42d4ee98ce) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [c6876b9023](https://linux-hardware.org/?probe=c6876b9023) | Dec 20, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [3fea1de018](https://linux-hardware.org/?probe=3fea1de018) | Dec 20, 2021 |
| eMachines     | E525                        | Notebook    | [bcb03ff38c](https://linux-hardware.org/?probe=bcb03ff38c) | Dec 20, 2021 |
| Acer          | Aspire XC-330               | Desktop     | [1803a4622c](https://linux-hardware.org/?probe=1803a4622c) | Dec 19, 2021 |
| MSI           | Katana GF66 11UE            | Notebook    | [36aea8dc19](https://linux-hardware.org/?probe=36aea8dc19) | Dec 18, 2021 |
| Dell          | Precision 5540              | Notebook    | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| Gigabyte      | F2A88XM-DS2P                | Desktop     | [c18ddabc8d](https://linux-hardware.org/?probe=c18ddabc8d) | Dec 18, 2021 |
| MSI           | Katana GF66 11UE            | Notebook    | [56be528067](https://linux-hardware.org/?probe=56be528067) | Dec 18, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [75b2d1484e](https://linux-hardware.org/?probe=75b2d1484e) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| Acer          | Aspire XC-330               | Desktop     | [61dd8de51b](https://linux-hardware.org/?probe=61dd8de51b) | Dec 16, 2021 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | Notebook    | [38d349f99c](https://linux-hardware.org/?probe=38d349f99c) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [660ce7fc74](https://linux-hardware.org/?probe=660ce7fc74) | Dec 15, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [7d66a9996f](https://linux-hardware.org/?probe=7d66a9996f) | Dec 15, 2021 |
| Dell          | Latitude E6400              | Notebook    | [2936dcb6ab](https://linux-hardware.org/?probe=2936dcb6ab) | Dec 14, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [d4bed6e3e7](https://linux-hardware.org/?probe=d4bed6e3e7) | Dec 14, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [44378ec4a5](https://linux-hardware.org/?probe=44378ec4a5) | Dec 14, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [dff25b4704](https://linux-hardware.org/?probe=dff25b4704) | Dec 11, 2021 |
| Dell          | Latitude E7450              | Notebook    | [f5f9fd93f9](https://linux-hardware.org/?probe=f5f9fd93f9) | Dec 09, 2021 |
| ASUSTek       | CM6650                      | Desktop     | [ef34d60843](https://linux-hardware.org/?probe=ef34d60843) | Dec 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0V400    | Notebook    | [77c3ba8640](https://linux-hardware.org/?probe=77c3ba8640) | Dec 09, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ad04822d41](https://linux-hardware.org/?probe=ad04822d41) | Dec 07, 2021 |
| Dell          | Precision 5560              | Notebook    | [2af841d052](https://linux-hardware.org/?probe=2af841d052) | Dec 07, 2021 |
| Dell          | Precision 5560              | Notebook    | [aeba66f4d6](https://linux-hardware.org/?probe=aeba66f4d6) | Dec 07, 2021 |
| HP            | Pavilion dv6                | Notebook    | [479a9e57d5](https://linux-hardware.org/?probe=479a9e57d5) | Dec 07, 2021 |
| HP            | Pavilion dv6                | Notebook    | [98ad56ddcc](https://linux-hardware.org/?probe=98ad56ddcc) | Dec 07, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [1c3a187ec6](https://linux-hardware.org/?probe=1c3a187ec6) | Dec 07, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [80d04f078e](https://linux-hardware.org/?probe=80d04f078e) | Dec 07, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [9609fb65be](https://linux-hardware.org/?probe=9609fb65be) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [a2e2eceb54](https://linux-hardware.org/?probe=a2e2eceb54) | Dec 05, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [a859413f86](https://linux-hardware.org/?probe=a859413f86) | Dec 05, 2021 |
| Apple         | MacBookPro14,3              | Notebook    | [b08702eb1e](https://linux-hardware.org/?probe=b08702eb1e) | Dec 05, 2021 |
| HUAWEI        | VLT-WX0                     | Notebook    | [3e01a8673d](https://linux-hardware.org/?probe=3e01a8673d) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [fa0051b73b](https://linux-hardware.org/?probe=fa0051b73b) | Dec 02, 2021 |
| Apple         | MacBookPro14,3              | Notebook    | [a7366c8449](https://linux-hardware.org/?probe=a7366c8449) | Dec 02, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [4dce6fbb79](https://linux-hardware.org/?probe=4dce6fbb79) | Dec 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [fa59cc1ea9](https://linux-hardware.org/?probe=fa59cc1ea9) | Dec 01, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [5f2264a472](https://linux-hardware.org/?probe=5f2264a472) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [af8104b01a](https://linux-hardware.org/?probe=af8104b01a) | Nov 30, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [66f2018614](https://linux-hardware.org/?probe=66f2018614) | Nov 30, 2021 |
| Toshiba       | Satellite C50-A-19U         | Notebook    | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Dell          | 03VTJ7 A01                  | All in one  | [fcd0ef9f0e](https://linux-hardware.org/?probe=fcd0ef9f0e) | Nov 29, 2021 |
| Dell          | 03VTJ7 A01                  | All in one  | [5b0f7ffe69](https://linux-hardware.org/?probe=5b0f7ffe69) | Nov 29, 2021 |
| Acer          | Predator PT315-51           | Notebook    | [b37881e828](https://linux-hardware.org/?probe=b37881e828) | Nov 29, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [56f6b7ec0a](https://linux-hardware.org/?probe=56f6b7ec0a) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a74aec830e](https://linux-hardware.org/?probe=a74aec830e) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [af530bb7c7](https://linux-hardware.org/?probe=af530bb7c7) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [19f2a1dd2f](https://linux-hardware.org/?probe=19f2a1dd2f) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [90f2d59148](https://linux-hardware.org/?probe=90f2d59148) | Nov 26, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7ac3b720be](https://linux-hardware.org/?probe=7ac3b720be) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [56f55d6a20](https://linux-hardware.org/?probe=56f55d6a20) | Nov 24, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| HP            | 212B                        | Desktop     | [0377d5dc76](https://linux-hardware.org/?probe=0377d5dc76) | Nov 23, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [ee309c7776](https://linux-hardware.org/?probe=ee309c7776) | Nov 23, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [0f39f8f706](https://linux-hardware.org/?probe=0f39f8f706) | Nov 22, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [9f8a07614e](https://linux-hardware.org/?probe=9f8a07614e) | Nov 21, 2021 |
| ASUSTek       | K53U                        | Notebook    | [12136b1cbd](https://linux-hardware.org/?probe=12136b1cbd) | Nov 20, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [2c0279ade5](https://linux-hardware.org/?probe=2c0279ade5) | Nov 20, 2021 |
| ASUSTek       | K53U                        | Notebook    | [5a5b8c420f](https://linux-hardware.org/?probe=5a5b8c420f) | Nov 20, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [532584c064](https://linux-hardware.org/?probe=532584c064) | Nov 20, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [fcfcf6c49b](https://linux-hardware.org/?probe=fcfcf6c49b) | Nov 20, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [981f4d57e5](https://linux-hardware.org/?probe=981f4d57e5) | Nov 19, 2021 |
| Dell          | Latitude E5570              | Notebook    | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Google        | Edgar                       | Notebook    | [0c4bb072e0](https://linux-hardware.org/?probe=0c4bb072e0) | Nov 16, 2021 |
| HP            | ProBook 6450b               | Notebook    | [943ef75a8b](https://linux-hardware.org/?probe=943ef75a8b) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [cb474c37e6](https://linux-hardware.org/?probe=cb474c37e6) | Nov 15, 2021 |
| Lenovo        | ThinkPad 25 20K70000MX      | Notebook    | [86d3ea8b6a](https://linux-hardware.org/?probe=86d3ea8b6a) | Nov 15, 2021 |
| Google        | Edgar                       | Notebook    | [9cb0616971](https://linux-hardware.org/?probe=9cb0616971) | Nov 15, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dbdeebfe86](https://linux-hardware.org/?probe=dbdeebfe86) | Nov 14, 2021 |
| Acer          | TravelMate Spin B118-R      | Convertible | [7cb747306c](https://linux-hardware.org/?probe=7cb747306c) | Nov 14, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [47982e4a71](https://linux-hardware.org/?probe=47982e4a71) | Nov 14, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [420684393a](https://linux-hardware.org/?probe=420684393a) | Nov 14, 2021 |
| Gigabyte      | Q170TN-T20                  | Desktop     | [28a80f5aa9](https://linux-hardware.org/?probe=28a80f5aa9) | Nov 10, 2021 |
| Gigabyte      | Q170TN-T20                  | Desktop     | [8fce727047](https://linux-hardware.org/?probe=8fce727047) | Nov 10, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | Notebook    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [01629df193](https://linux-hardware.org/?probe=01629df193) | Nov 08, 2021 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [d3f60c7a58](https://linux-hardware.org/?probe=d3f60c7a58) | Nov 06, 2021 |
| ASUSTek       | N550JK                      | Notebook    | [23fd9d7d0d](https://linux-hardware.org/?probe=23fd9d7d0d) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Sony          | VPCCA2S1E                   | Notebook    | [2ce8a8295b](https://linux-hardware.org/?probe=2ce8a8295b) | Nov 05, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| Google        | Grunt                       | Notebook    | [e6c7c07304](https://linux-hardware.org/?probe=e6c7c07304) | Nov 04, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [36b8c3bedd](https://linux-hardware.org/?probe=36b8c3bedd) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480 20L50009MX    | Notebook    | [349faf5242](https://linux-hardware.org/?probe=349faf5242) | Nov 03, 2021 |
| On by NetO... | LT1.1 BRZ                   | Notebook    | [a520593d47](https://linux-hardware.org/?probe=a520593d47) | Nov 02, 2021 |
| On by NetO... | LT1.1 BRZ                   | Notebook    | [f9312f99c7](https://linux-hardware.org/?probe=f9312f99c7) | Nov 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [ae9e2708e9](https://linux-hardware.org/?probe=ae9e2708e9) | Nov 02, 2021 |
| AAEON         | GENE-APL5 V1.0              | Desktop     | [23a62cdb4b](https://linux-hardware.org/?probe=23a62cdb4b) | Nov 02, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1869db225e](https://linux-hardware.org/?probe=1869db225e) | Nov 02, 2021 |
| Gigabyte      | G1.Assassin                 | Desktop     | [40c84c9637](https://linux-hardware.org/?probe=40c84c9637) | Oct 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [82e27c0415](https://linux-hardware.org/?probe=82e27c0415) | Oct 31, 2021 |
| HP            | ZBook 14 G2                 | Notebook    | [ffb40f821b](https://linux-hardware.org/?probe=ffb40f821b) | Oct 30, 2021 |
| MSI           | H87M-G43                    | Desktop     | [aecd71ac63](https://linux-hardware.org/?probe=aecd71ac63) | Oct 30, 2021 |
| Sony          | VGN-CS31S_W                 | Notebook    | [13451dd6c5](https://linux-hardware.org/?probe=13451dd6c5) | Oct 30, 2021 |
| Gigabyte      | Z170-HD3-CF                 | Desktop     | [9c608040d6](https://linux-hardware.org/?probe=9c608040d6) | Oct 30, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [5a5d3a54c3](https://linux-hardware.org/?probe=5a5d3a54c3) | Oct 29, 2021 |
| Dell          | 042P49 A02                  | Desktop     | [e766bcbb62](https://linux-hardware.org/?probe=e766bcbb62) | Oct 29, 2021 |
| HP            | 212B                        | Desktop     | [9d2a807f08](https://linux-hardware.org/?probe=9d2a807f08) | Oct 29, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [4e4391f329](https://linux-hardware.org/?probe=4e4391f329) | Oct 28, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [5d0901fd2c](https://linux-hardware.org/?probe=5d0901fd2c) | Oct 28, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [15d9329bd3](https://linux-hardware.org/?probe=15d9329bd3) | Oct 28, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [e3054d7b1b](https://linux-hardware.org/?probe=e3054d7b1b) | Oct 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5f67b298ab](https://linux-hardware.org/?probe=5f67b298ab) | Oct 27, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [a9c87c6c9c](https://linux-hardware.org/?probe=a9c87c6c9c) | Oct 27, 2021 |
| HP            | 212B                        | Desktop     | [b72e4a7240](https://linux-hardware.org/?probe=b72e4a7240) | Oct 26, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b47e0921b6](https://linux-hardware.org/?probe=b47e0921b6) | Oct 25, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [c518746ece](https://linux-hardware.org/?probe=c518746ece) | Oct 25, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [5f27dd2f45](https://linux-hardware.org/?probe=5f27dd2f45) | Oct 25, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [f6ddc3a2da](https://linux-hardware.org/?probe=f6ddc3a2da) | Oct 24, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [780e40d828](https://linux-hardware.org/?probe=780e40d828) | Oct 23, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e9991e486b](https://linux-hardware.org/?probe=e9991e486b) | Oct 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [470c0932ae](https://linux-hardware.org/?probe=470c0932ae) | Oct 23, 2021 |
| Supermicro    | X10DRU-i+                   | Desktop     | [57ba944640](https://linux-hardware.org/?probe=57ba944640) | Oct 22, 2021 |
| ASUSTek       | Z10PH-D16 Series            | Desktop     | [2591b8710e](https://linux-hardware.org/?probe=2591b8710e) | Oct 22, 2021 |
| Supermicro    | X10DRU-i+                   | Desktop     | [6e64d3ca9b](https://linux-hardware.org/?probe=6e64d3ca9b) | Oct 22, 2021 |
| Supermicro    | X10DRU-i+                   | Desktop     | [082f743459](https://linux-hardware.org/?probe=082f743459) | Oct 22, 2021 |
| ASUSTek       | Z10PH-D16 Series            | Desktop     | [eb31edbd6c](https://linux-hardware.org/?probe=eb31edbd6c) | Oct 22, 2021 |
| ASUSTek       | Z10PH-D16 Series            | Desktop     | [1c2c7bda55](https://linux-hardware.org/?probe=1c2c7bda55) | Oct 22, 2021 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [f11c125224](https://linux-hardware.org/?probe=f11c125224) | Oct 20, 2021 |
| Acer          | Aspire V3-772G              | Notebook    | [10e7ffc71d](https://linux-hardware.org/?probe=10e7ffc71d) | Oct 19, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [a7d8d3cf71](https://linux-hardware.org/?probe=a7d8d3cf71) | Oct 19, 2021 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [1b7f4401be](https://linux-hardware.org/?probe=1b7f4401be) | Oct 17, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d39f2875f9](https://linux-hardware.org/?probe=d39f2875f9) | Oct 17, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [7f36e83485](https://linux-hardware.org/?probe=7f36e83485) | Oct 17, 2021 |
| HP            | 82F1                        | Desktop     | [8aadc7e548](https://linux-hardware.org/?probe=8aadc7e548) | Oct 16, 2021 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [2e44d637e3](https://linux-hardware.org/?probe=2e44d637e3) | Oct 16, 2021 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [6a36c68267](https://linux-hardware.org/?probe=6a36c68267) | Oct 15, 2021 |
| HP            | 86C7                        | All in one  | [57c1da4955](https://linux-hardware.org/?probe=57c1da4955) | Oct 15, 2021 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [a8d60d04b0](https://linux-hardware.org/?probe=a8d60d04b0) | Oct 14, 2021 |
| Dell          | Latitude E5250              | Notebook    | [793091ac6a](https://linux-hardware.org/?probe=793091ac6a) | Oct 14, 2021 |
| Google        | Treeya                      | Notebook    | [82b0964b6d](https://linux-hardware.org/?probe=82b0964b6d) | Oct 14, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [c3cdfe0336](https://linux-hardware.org/?probe=c3cdfe0336) | Oct 14, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [66a9b21300](https://linux-hardware.org/?probe=66a9b21300) | Oct 14, 2021 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [2bf61f2ec6](https://linux-hardware.org/?probe=2bf61f2ec6) | Oct 14, 2021 |
| Google        | Treeya                      | Notebook    | [6c10b9bcb3](https://linux-hardware.org/?probe=6c10b9bcb3) | Oct 14, 2021 |
| Supermicro    | X8DTH                       | Server      | [ad4abe60cd](https://linux-hardware.org/?probe=ad4abe60cd) | Oct 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [331d7231b0](https://linux-hardware.org/?probe=331d7231b0) | Oct 13, 2021 |
| ASUSTek       | TP201SA                     | Notebook    | [504956d2e9](https://linux-hardware.org/?probe=504956d2e9) | Oct 13, 2021 |
| eMachines     | G730                        | Notebook    | [6450ba7397](https://linux-hardware.org/?probe=6450ba7397) | Oct 12, 2021 |
| eMachines     | G730                        | Notebook    | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| MSI           | B150M Night Elf             | Desktop     | [ed3f4e9937](https://linux-hardware.org/?probe=ed3f4e9937) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [31ae42bc51](https://linux-hardware.org/?probe=31ae42bc51) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [5b47e8efcb](https://linux-hardware.org/?probe=5b47e8efcb) | Oct 09, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [9587d6e0dd](https://linux-hardware.org/?probe=9587d6e0dd) | Oct 08, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [7e74deaa8e](https://linux-hardware.org/?probe=7e74deaa8e) | Oct 08, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [73f07430e4](https://linux-hardware.org/?probe=73f07430e4) | Oct 07, 2021 |
| ASUSTek       | X550LB                      | Notebook    | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| Gigabyte      | 970A-UD3                    | Desktop     | [60a820dd34](https://linux-hardware.org/?probe=60a820dd34) | Oct 05, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [28ecb03df2](https://linux-hardware.org/?probe=28ecb03df2) | Oct 05, 2021 |
| Dell          | Latitude 5290               | Notebook    | [e3afd1ef97](https://linux-hardware.org/?probe=e3afd1ef97) | Oct 04, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Dell          | Precision M6800             | Notebook    | [b85ad62146](https://linux-hardware.org/?probe=b85ad62146) | Oct 03, 2021 |
| Dell          | Precision M6800             | Notebook    | [61a932607b](https://linux-hardware.org/?probe=61a932607b) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [46db33820d](https://linux-hardware.org/?probe=46db33820d) | Oct 03, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [133b546e7f](https://linux-hardware.org/?probe=133b546e7f) | Oct 03, 2021 |
| ASRock        | G41M-GS3                    | Desktop     | [b0ae6e12c3](https://linux-hardware.org/?probe=b0ae6e12c3) | Oct 02, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [a1ffad5b6d](https://linux-hardware.org/?probe=a1ffad5b6d) | Oct 02, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [0cb09f59a9](https://linux-hardware.org/?probe=0cb09f59a9) | Oct 01, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [b3f1afc64b](https://linux-hardware.org/?probe=b3f1afc64b) | Oct 01, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [9c3c1f9a85](https://linux-hardware.org/?probe=9c3c1f9a85) | Oct 01, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [6876f0e86d](https://linux-hardware.org/?probe=6876f0e86d) | Sep 29, 2021 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | Notebook    | [4a91c75662](https://linux-hardware.org/?probe=4a91c75662) | Sep 28, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [72c41f4a85](https://linux-hardware.org/?probe=72c41f4a85) | Sep 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [560598d6fb](https://linux-hardware.org/?probe=560598d6fb) | Sep 26, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [bd0f1e95ef](https://linux-hardware.org/?probe=bd0f1e95ef) | Sep 25, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f5c02601d0](https://linux-hardware.org/?probe=f5c02601d0) | Sep 25, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2460060920](https://linux-hardware.org/?probe=2460060920) | Sep 25, 2021 |
| Acer          | WG43M                       | Desktop     | [f269cb6987](https://linux-hardware.org/?probe=f269cb6987) | Sep 25, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [639131ddd5](https://linux-hardware.org/?probe=639131ddd5) | Sep 25, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8617cbbc27](https://linux-hardware.org/?probe=8617cbbc27) | Sep 24, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [f56bf148bf](https://linux-hardware.org/?probe=f56bf148bf) | Sep 24, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [c55708bb3f](https://linux-hardware.org/?probe=c55708bb3f) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [df7ff85482](https://linux-hardware.org/?probe=df7ff85482) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [36c78f1667](https://linux-hardware.org/?probe=36c78f1667) | Sep 23, 2021 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [e001ec9d57](https://linux-hardware.org/?probe=e001ec9d57) | Sep 23, 2021 |
| HP            | Presario CQ62               | Notebook    | [dc91fe3b30](https://linux-hardware.org/?probe=dc91fe3b30) | Sep 22, 2021 |
| AAEON         | GENE-APL5 V1.0              | Desktop     | [7abd7a20df](https://linux-hardware.org/?probe=7abd7a20df) | Sep 21, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [83f3d6df86](https://linux-hardware.org/?probe=83f3d6df86) | Sep 21, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [13d080e9d6](https://linux-hardware.org/?probe=13d080e9d6) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bd2cfcf1ee](https://linux-hardware.org/?probe=bd2cfcf1ee) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [5b337fdb0a](https://linux-hardware.org/?probe=5b337fdb0a) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [b9259e3604](https://linux-hardware.org/?probe=b9259e3604) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [439f4b690a](https://linux-hardware.org/?probe=439f4b690a) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [a9edf67742](https://linux-hardware.org/?probe=a9edf67742) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [9eb1254056](https://linux-hardware.org/?probe=9eb1254056) | Sep 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [7c806aa7c5](https://linux-hardware.org/?probe=7c806aa7c5) | Sep 19, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [3a0e961b45](https://linux-hardware.org/?probe=3a0e961b45) | Sep 18, 2021 |
| Dell          | Latitude E7450              | Notebook    | [f5963dc359](https://linux-hardware.org/?probe=f5963dc359) | Sep 18, 2021 |
| Dell          | Precision 7720              | Notebook    | [80f3d1e3b0](https://linux-hardware.org/?probe=80f3d1e3b0) | Sep 17, 2021 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [8750af4b33](https://linux-hardware.org/?probe=8750af4b33) | Sep 16, 2021 |
| MSI           | B360M BAZOOKA               | Desktop     | [a9fc1d1222](https://linux-hardware.org/?probe=a9fc1d1222) | Sep 16, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [ad597e71b6](https://linux-hardware.org/?probe=ad597e71b6) | Sep 16, 2021 |
| Dell          | Latitude 5290               | Notebook    | [baae3812d5](https://linux-hardware.org/?probe=baae3812d5) | Sep 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [dc1b85b8c9](https://linux-hardware.org/?probe=dc1b85b8c9) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Gigabyte      | H77-D3H                     | Desktop     | [0c9d11ec80](https://linux-hardware.org/?probe=0c9d11ec80) | Sep 14, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [9631d6f9e1](https://linux-hardware.org/?probe=9631d6f9e1) | Sep 14, 2021 |
| HP            | 3032h                       | Desktop     | [3fad749d1a](https://linux-hardware.org/?probe=3fad749d1a) | Sep 12, 2021 |
| Acer          | Swift SF314-511             | Notebook    | [4286a4710c](https://linux-hardware.org/?probe=4286a4710c) | Sep 11, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| ASRock        | HM55-MXM                    | Desktop     | [0d500a3661](https://linux-hardware.org/?probe=0d500a3661) | Sep 11, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [6d3a30d1a7](https://linux-hardware.org/?probe=6d3a30d1a7) | Sep 11, 2021 |
| ASUSTek       | GR8 II-K                    | Desktop     | [fad193ae06](https://linux-hardware.org/?probe=fad193ae06) | Sep 11, 2021 |
| Toshiba       | Satellite L50D-B            | Notebook    | [6eb7be93e9](https://linux-hardware.org/?probe=6eb7be93e9) | Sep 10, 2021 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [c58154679e](https://linux-hardware.org/?probe=c58154679e) | Sep 10, 2021 |
| ASUSTek       | GR8 II-K                    | Desktop     | [417104e2f2](https://linux-hardware.org/?probe=417104e2f2) | Sep 09, 2021 |
| HP            | ProBook 6460b               | Notebook    | [b0f0eaf216](https://linux-hardware.org/?probe=b0f0eaf216) | Sep 09, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [7f29f46363](https://linux-hardware.org/?probe=7f29f46363) | Sep 09, 2021 |
| ASUSTek       | GR8 II-K                    | Desktop     | [9a77062729](https://linux-hardware.org/?probe=9a77062729) | Sep 09, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [04ecb299d9](https://linux-hardware.org/?probe=04ecb299d9) | Sep 08, 2021 |
| HP            | ZBook 17 G3                 | Notebook    | [7e85c2791f](https://linux-hardware.org/?probe=7e85c2791f) | Sep 07, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [d644d366b2](https://linux-hardware.org/?probe=d644d366b2) | Sep 06, 2021 |
| HP            | ProBook 4540s               | Notebook    | [41d764faaf](https://linux-hardware.org/?probe=41d764faaf) | Sep 06, 2021 |
| ASUSTek       | G11CD-K                     | Desktop     | [c4364afff6](https://linux-hardware.org/?probe=c4364afff6) | Sep 05, 2021 |
| PC Special... | N150CU                      | Notebook    | [2fd6f4b53c](https://linux-hardware.org/?probe=2fd6f4b53c) | Sep 05, 2021 |
| HP            | ProBook 6450b               | Notebook    | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [c55d1ba8bf](https://linux-hardware.org/?probe=c55d1ba8bf) | Sep 03, 2021 |
| HP            | 3031h                       | Desktop     | [9fc8c93cd1](https://linux-hardware.org/?probe=9fc8c93cd1) | Sep 01, 2021 |
| Dell          | 0200DY A02                  | Desktop     | [9fd555a4ea](https://linux-hardware.org/?probe=9fd555a4ea) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [d40a00437d](https://linux-hardware.org/?probe=d40a00437d) | Aug 30, 2021 |
| Lenovo        | B51-80 80LM                 | Notebook    | [a81c83bd1c](https://linux-hardware.org/?probe=a81c83bd1c) | Aug 30, 2021 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [f4e788dce6](https://linux-hardware.org/?probe=f4e788dce6) | Aug 30, 2021 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [8f5b776bcb](https://linux-hardware.org/?probe=8f5b776bcb) | Aug 30, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [645425c060](https://linux-hardware.org/?probe=645425c060) | Aug 29, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [78ad2b6854](https://linux-hardware.org/?probe=78ad2b6854) | Aug 27, 2021 |
| Lenovo        | ThinkPad T420s 4174FM9      | Notebook    | [12fd92046e](https://linux-hardware.org/?probe=12fd92046e) | Aug 27, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [8dc5048a39](https://linux-hardware.org/?probe=8dc5048a39) | Aug 26, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [86c5a4a3dd](https://linux-hardware.org/?probe=86c5a4a3dd) | Aug 25, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [01b1cadf52](https://linux-hardware.org/?probe=01b1cadf52) | Aug 25, 2021 |
| Acer          | TravelMate Spin B118-R      | Convertible | [a49c104eda](https://linux-hardware.org/?probe=a49c104eda) | Aug 24, 2021 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [35f6fc9592](https://linux-hardware.org/?probe=35f6fc9592) | Aug 23, 2021 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [32593919a0](https://linux-hardware.org/?probe=32593919a0) | Aug 23, 2021 |
| ASUSTek       | X510UAR                     | Notebook    | [cd238d180b](https://linux-hardware.org/?probe=cd238d180b) | Aug 23, 2021 |
| Toshiba       | Satellite L50D-B            | Notebook    | [1e514cb947](https://linux-hardware.org/?probe=1e514cb947) | Aug 23, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FES0... | Convertible | [4300a083b1](https://linux-hardware.org/?probe=4300a083b1) | Aug 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [7406e49c18](https://linux-hardware.org/?probe=7406e49c18) | Aug 21, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [cdf90072fd](https://linux-hardware.org/?probe=cdf90072fd) | Aug 21, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [f32d5484b5](https://linux-hardware.org/?probe=f32d5484b5) | Aug 20, 2021 |
| ASRock        | G41M-LE                     | Desktop     | [b6d9b74951](https://linux-hardware.org/?probe=b6d9b74951) | Aug 20, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [a8e8ae384a](https://linux-hardware.org/?probe=a8e8ae384a) | Aug 20, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [42ab0a8ca5](https://linux-hardware.org/?probe=42ab0a8ca5) | Aug 20, 2021 |
| Acer          | Aspire X1470                | Desktop     | [79d5cfd4fd](https://linux-hardware.org/?probe=79d5cfd4fd) | Aug 20, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [6d76e9c22e](https://linux-hardware.org/?probe=6d76e9c22e) | Aug 18, 2021 |
| PC Special... | Standard                    | Notebook    | [b7baa43d24](https://linux-hardware.org/?probe=b7baa43d24) | Aug 18, 2021 |
| Gigabyte      | EX58-UD5                    | Desktop     | [9482e2b574](https://linux-hardware.org/?probe=9482e2b574) | Aug 17, 2021 |
| Gigabyte      | EX58-UD5                    | Desktop     | [272f3deca9](https://linux-hardware.org/?probe=272f3deca9) | Aug 17, 2021 |
| MSI           | GP63 Leopard 8RE            | Notebook    | [40a8ec3a95](https://linux-hardware.org/?probe=40a8ec3a95) | Aug 16, 2021 |
| Pegatron      | 2ACF                        | Desktop     | [e26b353478](https://linux-hardware.org/?probe=e26b353478) | Aug 16, 2021 |
| Razer         | Blade                       | Notebook    | [b6bad1f725](https://linux-hardware.org/?probe=b6bad1f725) | Aug 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [77c51b6b7b](https://linux-hardware.org/?probe=77c51b6b7b) | Aug 15, 2021 |
| HP            | Pavilion 17                 | Notebook    | [b628f70687](https://linux-hardware.org/?probe=b628f70687) | Aug 15, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3DK1... | Notebook    | [695ac6427d](https://linux-hardware.org/?probe=695ac6427d) | Aug 15, 2021 |
| ASUSTek       | Z97I-PLUS                   | Desktop     | [347638818a](https://linux-hardware.org/?probe=347638818a) | Aug 15, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [9e8c53410a](https://linux-hardware.org/?probe=9e8c53410a) | Aug 14, 2021 |
| HP            | Compaq nc6320 (EV073AV)     | Notebook    | [bf6050f750](https://linux-hardware.org/?probe=bf6050f750) | Aug 14, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [38abfc60a9](https://linux-hardware.org/?probe=38abfc60a9) | Aug 14, 2021 |
| Lenovo        | 1031 SDK0J40697 WIN 3305... | Desktop     | [a06764af07](https://linux-hardware.org/?probe=a06764af07) | Aug 14, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6775259732](https://linux-hardware.org/?probe=6775259732) | Aug 12, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [adde6ef882](https://linux-hardware.org/?probe=adde6ef882) | Aug 12, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [164bbac83c](https://linux-hardware.org/?probe=164bbac83c) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | Notebook    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [1eba114602](https://linux-hardware.org/?probe=1eba114602) | Aug 11, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [a78580fb6b](https://linux-hardware.org/?probe=a78580fb6b) | Aug 11, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [a31c1f0fda](https://linux-hardware.org/?probe=a31c1f0fda) | Aug 11, 2021 |
| Dell          | Inspiron ME051              | Notebook    | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [c1209f4d40](https://linux-hardware.org/?probe=c1209f4d40) | Aug 09, 2021 |
| Dell          | Precision M4500             | Notebook    | [d7b650fecf](https://linux-hardware.org/?probe=d7b650fecf) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [7bc23070c4](https://linux-hardware.org/?probe=7bc23070c4) | Aug 08, 2021 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [d3e0286f2f](https://linux-hardware.org/?probe=d3e0286f2f) | Aug 08, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [1778263a70](https://linux-hardware.org/?probe=1778263a70) | Aug 08, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [9e08265168](https://linux-hardware.org/?probe=9e08265168) | Aug 08, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5839492cd8](https://linux-hardware.org/?probe=5839492cd8) | Aug 07, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [ffe68561cd](https://linux-hardware.org/?probe=ffe68561cd) | Aug 07, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [b143c1bc24](https://linux-hardware.org/?probe=b143c1bc24) | Aug 07, 2021 |
| Dell          | Latitude E6400              | Notebook    | [dea83da57d](https://linux-hardware.org/?probe=dea83da57d) | Aug 04, 2021 |
| Packard Be... | EasyNote TS11SB             | Notebook    | [aa9468a3de](https://linux-hardware.org/?probe=aa9468a3de) | Aug 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1bcb4e3744](https://linux-hardware.org/?probe=1bcb4e3744) | Aug 03, 2021 |
| Packard Be... | EasyNote TS11SB             | Notebook    | [57fbaedb1e](https://linux-hardware.org/?probe=57fbaedb1e) | Aug 03, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [7c2abb5f03](https://linux-hardware.org/?probe=7c2abb5f03) | Aug 02, 2021 |
| HP            | Pavilion 15                 | Notebook    | [08bd4b9549](https://linux-hardware.org/?probe=08bd4b9549) | Aug 02, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [23399ffe42](https://linux-hardware.org/?probe=23399ffe42) | Jul 30, 2021 |
| AOpen         | D1001 C26361-D1001          | Desktop     | [9d1b679c39](https://linux-hardware.org/?probe=9d1b679c39) | Jul 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [5cacc2c659](https://linux-hardware.org/?probe=5cacc2c659) | Jul 29, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [822adc34c6](https://linux-hardware.org/?probe=822adc34c6) | Jul 28, 2021 |
| MSI           | Z97-G55 SLI                 | Desktop     | [e473068ae1](https://linux-hardware.org/?probe=e473068ae1) | Jul 26, 2021 |
| HP            | ProBook 6460b               | Notebook    | [ad2986d747](https://linux-hardware.org/?probe=ad2986d747) | Jul 26, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [8f6e1f1929](https://linux-hardware.org/?probe=8f6e1f1929) | Jul 25, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [896e1bc2a0](https://linux-hardware.org/?probe=896e1bc2a0) | Jul 25, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [1325b6d6c2](https://linux-hardware.org/?probe=1325b6d6c2) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | Desktop     | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [c992c52bbe](https://linux-hardware.org/?probe=c992c52bbe) | Jul 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [7e6901b321](https://linux-hardware.org/?probe=7e6901b321) | Jul 24, 2021 |
| HP            | EliteBook x360 1020 G2      | Convertible | [bf9a3d1a33](https://linux-hardware.org/?probe=bf9a3d1a33) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [ed51414a9d](https://linux-hardware.org/?probe=ed51414a9d) | Jul 22, 2021 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | Notebook    | [64c8fe4e52](https://linux-hardware.org/?probe=64c8fe4e52) | Jul 20, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a2257b9a18](https://linux-hardware.org/?probe=a2257b9a18) | Jul 19, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [ac79c47d88](https://linux-hardware.org/?probe=ac79c47d88) | Jul 18, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [2e8c9fa212](https://linux-hardware.org/?probe=2e8c9fa212) | Jul 18, 2021 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [35f34b8d3c](https://linux-hardware.org/?probe=35f34b8d3c) | Jul 17, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [715cf27cd7](https://linux-hardware.org/?probe=715cf27cd7) | Jul 17, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [62577e9673](https://linux-hardware.org/?probe=62577e9673) | Jul 13, 2021 |
| HP            | 805B                        | Desktop     | [d6c2730444](https://linux-hardware.org/?probe=d6c2730444) | Jul 12, 2021 |
| Intel Clie... | LAPBC710                    | Notebook    | [49a2ccdeee](https://linux-hardware.org/?probe=49a2ccdeee) | Jul 12, 2021 |
| HP            | Pavilion 15                 | Notebook    | [b4eeb3105e](https://linux-hardware.org/?probe=b4eeb3105e) | Jul 12, 2021 |
| ASUSTek       | M2NBP-VM CSM                | Desktop     | [03f4361376](https://linux-hardware.org/?probe=03f4361376) | Jul 12, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d67f8f6efe](https://linux-hardware.org/?probe=d67f8f6efe) | Jul 11, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f0e5926bb6](https://linux-hardware.org/?probe=f0e5926bb6) | Jul 10, 2021 |
| HP            | Pavilion dv6                | Notebook    | [bb0f20f7a9](https://linux-hardware.org/?probe=bb0f20f7a9) | Jul 10, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5b36935bb4](https://linux-hardware.org/?probe=5b36935bb4) | Jul 10, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a4d952ce54](https://linux-hardware.org/?probe=a4d952ce54) | Jul 10, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [89ed1de959](https://linux-hardware.org/?probe=89ed1de959) | Jul 10, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [8845d0216e](https://linux-hardware.org/?probe=8845d0216e) | Jul 09, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [71e2fb6f8c](https://linux-hardware.org/?probe=71e2fb6f8c) | Jul 09, 2021 |
| HP            | Elite x2 1012 G1            | Notebook    | [4d5cea91ad](https://linux-hardware.org/?probe=4d5cea91ad) | Jul 07, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [505684a737](https://linux-hardware.org/?probe=505684a737) | Jul 07, 2021 |
| JGINYUE       | H97M-VH PLUS V1.0           | Desktop     | [c59567b2c6](https://linux-hardware.org/?probe=c59567b2c6) | Jul 05, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [6fdc284c1a](https://linux-hardware.org/?probe=6fdc284c1a) | Jul 05, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [13f5ecaf06](https://linux-hardware.org/?probe=13f5ecaf06) | Jul 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b20ea1e645](https://linux-hardware.org/?probe=b20ea1e645) | Jul 02, 2021 |
| Gigabyte      | Z68XP-UD3P                  | Desktop     | [a91132f871](https://linux-hardware.org/?probe=a91132f871) | Jul 02, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [43d77edd56](https://linux-hardware.org/?probe=43d77edd56) | Jul 01, 2021 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | Notebook    | [c0ba9a0437](https://linux-hardware.org/?probe=c0ba9a0437) | Jun 30, 2021 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [625c876e08](https://linux-hardware.org/?probe=625c876e08) | Jun 30, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [103c0edcbd](https://linux-hardware.org/?probe=103c0edcbd) | Jun 30, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [aa05cca9b7](https://linux-hardware.org/?probe=aa05cca9b7) | Jun 30, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [5902a639b3](https://linux-hardware.org/?probe=5902a639b3) | Jun 29, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [bd1a38eba3](https://linux-hardware.org/?probe=bd1a38eba3) | Jun 29, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [353a5052a1](https://linux-hardware.org/?probe=353a5052a1) | Jun 29, 2021 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [470151cefe](https://linux-hardware.org/?probe=470151cefe) | Jun 29, 2021 |
| Lenovo        | ThinkPad T460 20FMS06105    | Notebook    | [242cf25827](https://linux-hardware.org/?probe=242cf25827) | Jun 29, 2021 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [259908557b](https://linux-hardware.org/?probe=259908557b) | Jun 28, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [1eae951997](https://linux-hardware.org/?probe=1eae951997) | Jun 28, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [d4dd36702b](https://linux-hardware.org/?probe=d4dd36702b) | Jun 28, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [45df91892a](https://linux-hardware.org/?probe=45df91892a) | Jun 27, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [5fc995dac3](https://linux-hardware.org/?probe=5fc995dac3) | Jun 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [392be37a79](https://linux-hardware.org/?probe=392be37a79) | Jun 25, 2021 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [6995133402](https://linux-hardware.org/?probe=6995133402) | Jun 24, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [b9d0b5be2d](https://linux-hardware.org/?probe=b9d0b5be2d) | Jun 23, 2021 |
| ASUSTek       | ROG Strix G731GW_G731GW     | Notebook    | [85a0c7c512](https://linux-hardware.org/?probe=85a0c7c512) | Jun 23, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [e2b40afe3c](https://linux-hardware.org/?probe=e2b40afe3c) | Jun 23, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [e4ba771332](https://linux-hardware.org/?probe=e4ba771332) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7a6f9e9890](https://linux-hardware.org/?probe=7a6f9e9890) | Jun 22, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [495c04a536](https://linux-hardware.org/?probe=495c04a536) | Jun 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca17e02509](https://linux-hardware.org/?probe=ca17e02509) | Jun 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8ea738199d](https://linux-hardware.org/?probe=8ea738199d) | Jun 22, 2021 |
| HP            | 0A64h                       | Desktop     | [38876167c7](https://linux-hardware.org/?probe=38876167c7) | Jun 21, 2021 |
| HP            | 0A64h                       | Desktop     | [d3e791b0e1](https://linux-hardware.org/?probe=d3e791b0e1) | Jun 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c1abf6c844](https://linux-hardware.org/?probe=c1abf6c844) | Jun 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [aa95a9d75f](https://linux-hardware.org/?probe=aa95a9d75f) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b2a8e0f5a1](https://linux-hardware.org/?probe=b2a8e0f5a1) | Jun 18, 2021 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [7a60f78b32](https://linux-hardware.org/?probe=7a60f78b32) | Jun 17, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP            | EliteBook 725 G3            | Notebook    | [f57f7d1e53](https://linux-hardware.org/?probe=f57f7d1e53) | Jun 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [0e1e07507e](https://linux-hardware.org/?probe=0e1e07507e) | Jun 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [6defc2c42b](https://linux-hardware.org/?probe=6defc2c42b) | Jun 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [03c0890c33](https://linux-hardware.org/?probe=03c0890c33) | Jun 14, 2021 |
| Dell          | Latitude 3350               | Notebook    | [7fe0552d03](https://linux-hardware.org/?probe=7fe0552d03) | Jun 14, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [e6bdb7d91e](https://linux-hardware.org/?probe=e6bdb7d91e) | Jun 13, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [1e841a7eca](https://linux-hardware.org/?probe=1e841a7eca) | Jun 13, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [ead58254b2](https://linux-hardware.org/?probe=ead58254b2) | Jun 12, 2021 |
| ASUSTek       | P5E                         | Desktop     | [975bd773a1](https://linux-hardware.org/?probe=975bd773a1) | Jun 11, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [c9549be0ad](https://linux-hardware.org/?probe=c9549be0ad) | Jun 11, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [293537d794](https://linux-hardware.org/?probe=293537d794) | Jun 11, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [ee40fdc579](https://linux-hardware.org/?probe=ee40fdc579) | Jun 10, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [1fb08e646c](https://linux-hardware.org/?probe=1fb08e646c) | Jun 10, 2021 |
| Apple         | Mac-F2268DAE                | All in one  | [85f2356b7b](https://linux-hardware.org/?probe=85f2356b7b) | Jun 10, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [ce2eb9d95f](https://linux-hardware.org/?probe=ce2eb9d95f) | Jun 09, 2021 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [f7c024788e](https://linux-hardware.org/?probe=f7c024788e) | Jun 09, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [05a2ecf3ec](https://linux-hardware.org/?probe=05a2ecf3ec) | Jun 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [48bda0fbd3](https://linux-hardware.org/?probe=48bda0fbd3) | Jun 09, 2021 |
| Acer          | EG43M                       | Desktop     | [4300da7d4b](https://linux-hardware.org/?probe=4300da7d4b) | Jun 08, 2021 |
| Acer          | EG43M                       | Desktop     | [c160d8848f](https://linux-hardware.org/?probe=c160d8848f) | Jun 08, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [59fb6bb8a1](https://linux-hardware.org/?probe=59fb6bb8a1) | Jun 07, 2021 |
| Lenovo        | ThinkPad X201 4492W36       | Notebook    | [f309552e6e](https://linux-hardware.org/?probe=f309552e6e) | Jun 07, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [e199caf3af](https://linux-hardware.org/?probe=e199caf3af) | Jun 06, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [d449055e57](https://linux-hardware.org/?probe=d449055e57) | Jun 06, 2021 |
| Sony          | VPCCA2S1E                   | Notebook    | [6b20cf032f](https://linux-hardware.org/?probe=6b20cf032f) | Jun 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [117372a8ff](https://linux-hardware.org/?probe=117372a8ff) | Jun 05, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [63985d7619](https://linux-hardware.org/?probe=63985d7619) | Jun 04, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [af3eba9cf0](https://linux-hardware.org/?probe=af3eba9cf0) | Jun 04, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [7bce3059dc](https://linux-hardware.org/?probe=7bce3059dc) | Jun 04, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [6946ffb375](https://linux-hardware.org/?probe=6946ffb375) | Jun 03, 2021 |
| Intel         | NUC7i7BNB J31145-310        | Mini pc     | [14c78a00b9](https://linux-hardware.org/?probe=14c78a00b9) | Jun 02, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [4733f1d376](https://linux-hardware.org/?probe=4733f1d376) | Jun 02, 2021 |
| Dell          | Latitude 9520               | Notebook    | [10a4c770cf](https://linux-hardware.org/?probe=10a4c770cf) | Jun 02, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [d8507e3c64](https://linux-hardware.org/?probe=d8507e3c64) | Jun 01, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [d0d5100ede](https://linux-hardware.org/?probe=d0d5100ede) | Jun 01, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d283998378](https://linux-hardware.org/?probe=d283998378) | Jun 01, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [f7f5736b13](https://linux-hardware.org/?probe=f7f5736b13) | Jun 01, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [9a23df55d8](https://linux-hardware.org/?probe=9a23df55d8) | May 31, 2021 |
| HP            | EliteBook Revolve 810       | Notebook    | [24758ed5b3](https://linux-hardware.org/?probe=24758ed5b3) | May 31, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [9b20a88d5e](https://linux-hardware.org/?probe=9b20a88d5e) | May 31, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [89f6eb0671](https://linux-hardware.org/?probe=89f6eb0671) | May 31, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [9c627ba872](https://linux-hardware.org/?probe=9c627ba872) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cad013a6a5](https://linux-hardware.org/?probe=cad013a6a5) | May 31, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [f2bc4b7196](https://linux-hardware.org/?probe=f2bc4b7196) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [af407b12e2](https://linux-hardware.org/?probe=af407b12e2) | May 29, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [5474165f7b](https://linux-hardware.org/?probe=5474165f7b) | May 27, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [8c36612ff4](https://linux-hardware.org/?probe=8c36612ff4) | May 26, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [5e10971a64](https://linux-hardware.org/?probe=5e10971a64) | May 25, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [046452ba81](https://linux-hardware.org/?probe=046452ba81) | May 25, 2021 |
| Apple         | MacBookPro6,1               | Notebook    | [a0012821b7](https://linux-hardware.org/?probe=a0012821b7) | May 25, 2021 |
| Dell          | Latitude D520               | Notebook    | [7a817a0426](https://linux-hardware.org/?probe=7a817a0426) | May 25, 2021 |
| MSI           | B85M-E45                    | Desktop     | [75e2e357a3](https://linux-hardware.org/?probe=75e2e357a3) | May 25, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [b07793f86c](https://linux-hardware.org/?probe=b07793f86c) | May 25, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Sweden/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 258       | 15.25%  |
| Ubuntu 18.04                 | 131       | 7.74%   |
| Ubuntu 22.04                 | 54        | 3.19%   |
| Pop!_OS 21.04                | 49        | 2.9%    |
| Arch                         | 40        | 2.36%   |
| OpenMandriva 4.2             | 39        | 2.3%    |
| Manjaro                      | 39        | 2.3%    |
| Arch Rolling                 | 38        | 2.25%   |
| KDE neon 20.04               | 36        | 2.13%   |
| Debian 11                    | 36        | 2.13%   |
| OpenMandriva 4.3             | 34        | 2.01%   |
| Pop!_OS 20.04                | 30        | 1.77%   |
| Ubuntu 21.10                 | 29        | 1.71%   |
| Ubuntu 21.04                 | 29        | 1.71%   |
| Pop!_OS 20.10                | 29        | 1.71%   |
| Ubuntu 19.04                 | 27        | 1.6%    |
| Fedora 35                    | 27        | 1.6%    |
| Linux Mint 20.3              | 25        | 1.48%   |
| Fedora 34                    | 25        | 1.48%   |
| Ubuntu 19.10                 | 24        | 1.42%   |
| Fedora 32                    | 23        | 1.36%   |
| openSUSE Tumbleweed-XXXXXXXX | 22        | 1.3%    |
| Zorin 15                     | 21        | 1.24%   |
| Zorin 16                     | 20        | 1.18%   |
| Xubuntu 20.04                | 19        | 1.12%   |
| Ubuntu 20.10                 | 19        | 1.12%   |
| Linux Mint 20.2              | 19        | 1.12%   |
| Linux Mint 20                | 19        | 1.12%   |
| Pop!_OS 22.04                | 18        | 1.06%   |
| Fedora 33                    | 18        | 1.06%   |
| Linux Mint 20.1              | 17        | 1%      |
| ArcoLinux Rolling            | 17        | 1%      |
| Fedora 36                    | 15        | 0.89%   |
| Fedora 31                    | 15        | 0.89%   |
| Pop!_OS 21.10                | 14        | 0.83%   |
| Debian 10                    | 14        | 0.83%   |
| Gentoo 2.6                   | 13        | 0.77%   |
| Ubuntu 18.10                 | 12        | 0.71%   |
| Linux Mint 19.1              | 12        | 0.71%   |
| Gentoo 2.7                   | 12        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 564       | 34.73%  |
| Pop!_OS       | 133       | 8.19%   |
| Fedora        | 123       | 7.57%   |
| Linux Mint    | 108       | 6.65%   |
| OpenMandriva  | 82        | 5.05%   |
| Manjaro       | 80        | 4.93%   |
| Arch          | 77        | 4.74%   |
| Debian        | 64        | 3.94%   |
| Zorin         | 41        | 2.52%   |
| KDE neon      | 41        | 2.52%   |
| Xubuntu       | 36        | 2.22%   |
| Gentoo        | 26        | 1.6%    |
| openSUSE      | 25        | 1.54%   |
| ArcoLinux     | 22        | 1.35%   |
| ROSA          | 20        | 1.23%   |
| Kubuntu       | 19        | 1.17%   |
| CentOS        | 12        | 0.74%   |
| Elementary    | 10        | 0.62%   |
| Clear Linux   | 10        | 0.62%   |
| Ubuntu MATE   | 9         | 0.55%   |
| Endless       | 9         | 0.55%   |
| EndeavourOS   | 9         | 0.55%   |
| Kali          | 8         | 0.49%   |
| Ubuntu Unity  | 7         | 0.43%   |
| Peppermint    | 6         | 0.37%   |
| Solus         | 5         | 0.31%   |
| Lubuntu       | 5         | 0.31%   |
| LMDE          | 5         | 0.31%   |
| Garuda Linux  | 5         | 0.31%   |
| Ubuntu Budgie | 4         | 0.25%   |
| Slackware     | 4         | 0.25%   |
| Parrot        | 4         | 0.25%   |
| MX            | 4         | 0.25%   |
| BlackPanther  | 4         | 0.25%   |
| Alpine        | 4         | 0.25%   |
| Raspbian      | 3         | 0.18%   |
| BunsenLabs    | 3         | 0.18%   |
| Siduction     | 2         | 0.12%   |
| Mageia        | 2         | 0.12%   |
| LinuxFX       | 2         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 39        | 2.13%   |
| 5.4.0-42-generic         | 33        | 1.8%    |
| 5.16.7-desktop-1omv4003  | 33        | 1.8%    |
| 5.4.0-58-generic         | 21        | 1.14%   |
| 5.4.0-48-generic         | 20        | 1.09%   |
| 5.11.0-7620-generic      | 19        | 1.04%   |
| 5.3.0-40-generic         | 17        | 0.93%   |
| 5.13.0-7614-generic      | 17        | 0.93%   |
| 5.4.0-52-generic         | 16        | 0.87%   |
| 5.15.0-46-generic        | 15        | 0.82%   |
| 5.13.0-30-generic        | 15        | 0.82%   |
| 5.4.0-40-generic         | 14        | 0.76%   |
| 5.13.0-39-generic        | 14        | 0.76%   |
| 5.4.0-7634-generic       | 13        | 0.71%   |
| 5.4.0-54-generic         | 12        | 0.65%   |
| 5.4.0-33-generic         | 12        | 0.65%   |
| 5.11.0-37-generic        | 12        | 0.65%   |
| 5.8.0-48-generic         | 11        | 0.6%    |
| 5.4.0-70-generic         | 11        | 0.6%    |
| 5.11.0-7614-generic      | 11        | 0.6%    |
| 5.10.0-8-amd64           | 11        | 0.6%    |
| 5.8.0-43-generic         | 10        | 0.54%   |
| 5.4.0-65-generic         | 10        | 0.54%   |
| 5.4.0-29-generic         | 10        | 0.54%   |
| 5.11.0-41-generic        | 10        | 0.54%   |
| 5.8.0-50-generic         | 9         | 0.49%   |
| 5.4.0-81-generic         | 9         | 0.49%   |
| 5.4.0-67-generic         | 9         | 0.49%   |
| 4.15.0-47-generic        | 9         | 0.49%   |
| 5.8.0-7642-generic       | 8         | 0.44%   |
| 5.8.0-7630-generic       | 8         | 0.44%   |
| 5.4.0-26-generic         | 8         | 0.44%   |
| 5.15.0-41-generic        | 8         | 0.44%   |
| 5.11.0-40-generic        | 8         | 0.44%   |
| 5.11.0-38-generic        | 8         | 0.44%   |
| 5.11.0-27-generic        | 8         | 0.44%   |
| 5.4.0-73-generic         | 7         | 0.38%   |
| 5.4.0-66-generic         | 7         | 0.38%   |
| 5.4.0-56-generic         | 7         | 0.38%   |
| 5.4.0-53-generic         | 7         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 330       | 18.92%  |
| 5.11.0  | 128       | 7.34%   |
| 5.13.0  | 111       | 6.36%   |
| 5.8.0   | 97        | 5.56%   |
| 4.15.0  | 81        | 4.64%   |
| 5.3.0   | 76        | 4.36%   |
| 5.15.0  | 67        | 3.84%   |
| 5.0.0   | 59        | 3.38%   |
| 5.10.0  | 51        | 2.92%   |
| 4.18.0  | 46        | 2.64%   |
| 5.10.14 | 40        | 2.29%   |
| 5.16.7  | 34        | 1.95%   |
| 5.17.5  | 11        | 0.63%   |
| 5.12.4  | 10        | 0.57%   |
| 4.19.0  | 10        | 0.57%   |
| 5.17.1  | 9         | 0.52%   |
| 5.14.0  | 9         | 0.52%   |
| 5.16.0  | 8         | 0.46%   |
| 5.7.0   | 7         | 0.4%    |
| 5.15.7  | 7         | 0.4%    |
| 5.9.0   | 6         | 0.34%   |
| 5.8.1   | 6         | 0.34%   |
| 5.18.0  | 6         | 0.34%   |
| 4.9.20  | 6         | 0.34%   |
| 5.9.8   | 5         | 0.29%   |
| 5.9.14  | 5         | 0.29%   |
| 5.5.8   | 5         | 0.29%   |
| 5.18.14 | 5         | 0.29%   |
| 5.17.15 | 5         | 0.29%   |
| 5.16.15 | 5         | 0.29%   |
| 5.15.5  | 5         | 0.29%   |
| 5.15.15 | 5         | 0.29%   |
| 5.14.11 | 5         | 0.29%   |
| 5.9.16  | 4         | 0.23%   |
| 5.8.11  | 4         | 0.23%   |
| 5.6.0   | 4         | 0.23%   |
| 5.18.10 | 4         | 0.23%   |
| 5.17.9  | 4         | 0.23%   |
| 5.17.4  | 4         | 0.23%   |
| 5.16.2  | 4         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 359       | 20.91%  |
| 5.11    | 157       | 9.14%   |
| 5.10    | 136       | 7.92%   |
| 5.8     | 134       | 7.8%    |
| 5.13    | 131       | 7.63%   |
| 5.15    | 122       | 7.11%   |
| 5.3     | 88        | 5.13%   |
| 4.15    | 81        | 4.72%   |
| 5.16    | 73        | 4.25%   |
| 5.0     | 62        | 3.61%   |
| 4.18    | 53        | 3.09%   |
| 5.17    | 45        | 2.62%   |
| 5.12    | 36        | 2.1%    |
| 5.9     | 33        | 1.92%   |
| 5.18    | 32        | 1.86%   |
| 5.6     | 28        | 1.63%   |
| 5.14    | 26        | 1.51%   |
| 5.7     | 24        | 1.4%    |
| 4.19    | 22        | 1.28%   |
| 4.9     | 16        | 0.93%   |
| 5.5     | 15        | 0.87%   |
| 5.19    | 9         | 0.52%   |
| 5.1     | 7         | 0.41%   |
| 5.2     | 6         | 0.35%   |
| 4.4     | 6         | 0.35%   |
| 4.14    | 3         | 0.17%   |
| 4.1     | 3         | 0.17%   |
| 4.20    | 2         | 0.12%   |
| 4.12    | 2         | 0.12%   |
| 3.10    | 2         | 0.12%   |
| 5       | 1         | 0.06%   |
| 4.16    | 1         | 0.06%   |
| 4.13    | 1         | 0.06%   |
| 3.2     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1520      | 97.56%  |
| i686    | 22        | 1.41%   |
| aarch64 | 9         | 0.58%   |
| armv7l  | 5         | 0.32%   |
| i586    | 1         | 0.06%   |
| armv8l  | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 753       | 45.94%  |
| Unknown         | 257       | 15.68%  |
| KDE5            | 209       | 12.75%  |
| XFCE            | 120       | 7.32%   |
| X-Cinnamon      | 81        | 4.94%   |
| KDE             | 70        | 4.27%   |
| MATE            | 31        | 1.89%   |
| Cinnamon        | 17        | 1.04%   |
| i3              | 12        | 0.73%   |
| KDE4            | 11        | 0.67%   |
| LXQt            | 10        | 0.61%   |
| LXDE            | 10        | 0.61%   |
| Pantheon        | 9         | 0.55%   |
| Budgie          | 8         | 0.49%   |
| Unity           | 7         | 0.43%   |
| Deepin          | 6         | 0.37%   |
| sway            | 4         | 0.24%   |
| Openbox         | 4         | 0.24%   |
| GNOME Classic   | 4         | 0.24%   |
| awesome         | 4         | 0.24%   |
| GNOME Flashback | 3         | 0.18%   |
| qtile           | 2         | 0.12%   |
| DWM             | 2         | 0.12%   |
| xmonad          | 1         | 0.06%   |
| Trinity         | 1         | 0.06%   |
| spectrwm        | 1         | 0.06%   |
| GNOME-Flashback | 1         | 0.06%   |
| bspwm           | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1202      | 75.08%  |
| Wayland     | 206       | 12.87%  |
| Unknown     | 131       | 8.18%   |
| Tty         | 61        | 3.81%   |
| Unspecified | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 937       | 57.77%  |
| SDDM    | 192       | 11.84%  |
| GDM     | 186       | 11.47%  |
| GDM3    | 115       | 7.09%   |
| LightDM | 109       | 6.72%   |
| TDM     | 63        | 3.88%   |
| KDM     | 11        | 0.68%   |
| XDM     | 5         | 0.31%   |
| Ly      | 3         | 0.18%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 728       | 45.41%  |
| sv_SE       | 440       | 27.45%  |
| Unknown     | 223       | 13.91%  |
| en_GB       | 97        | 6.05%   |
| C           | 39        | 2.43%   |
| ru_RU       | 11        | 0.69%   |
| de_DE       | 11        | 0.69%   |
| en_SE       | 7         | 0.44%   |
| en_DK       | 6         | 0.37%   |
| pl_PL       | 5         | 0.31%   |
| fr_FR       | 4         | 0.25%   |
| en_CA       | 3         | 0.19%   |
| bg_BG       | 3         | 0.19%   |
| uk_UA       | 2         | 0.12%   |
| POSIX       | 2         | 0.12%   |
| lt_LT       | 2         | 0.12%   |
| en_IE       | 2         | 0.12%   |
| C.UTF8      | 2         | 0.12%   |
| sv_SE.UTF8  | 1         | 0.06%   |
| sv_FI       | 1         | 0.06%   |
| sma_SE      | 1         | 0.06%   |
| nn_NO       | 1         | 0.06%   |
| nb_NO       | 1         | 0.06%   |
| hu_HU       | 1         | 0.06%   |
| fi_FI       | 1         | 0.06%   |
| es_VE       | 1         | 0.06%   |
| es_ES       | 1         | 0.06%   |
| en_US.utf-8 | 1         | 0.06%   |
| en_IN       | 1         | 0.06%   |
| en_GB.UTF8  | 1         | 0.06%   |
| en_GB.utf-8 | 1         | 0.06%   |
| en_AU       | 1         | 0.06%   |
| en_AG       | 1         | 0.06%   |
| bs_BA       | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 803       | 50.25%  |
| EFI  | 795       | 49.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1232      | 77.1%   |
| Btrfs   | 143       | 8.95%   |
| Overlay | 112       | 7.01%   |
| Unknown | 58        | 3.63%   |
| Xfs     | 24        | 1.5%    |
| Zfs     | 15        | 0.94%   |
| Ext2    | 7         | 0.44%   |
| F2fs    | 3         | 0.19%   |
| Tmpfs   | 2         | 0.13%   |
| XXXXXXX | 1         | 0.06%   |
| Ext3    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 962       | 60.2%   |
| GPT     | 506       | 31.66%  |
| MBR     | 130       | 8.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1376      | 86.65%  |
| Yes       | 212       | 13.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1196      | 75.41%  |
| Yes       | 390       | 24.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 346       | 22.21%  |
| Hewlett-Packard         | 228       | 14.63%  |
| Lenovo                  | 219       | 14.06%  |
| Dell                    | 171       | 10.98%  |
| MSI                     | 114       | 7.32%   |
| Gigabyte Technology     | 108       | 6.93%   |
| Acer                    | 77        | 4.94%   |
| Apple                   | 45        | 2.89%   |
| ASRock                  | 40        | 2.57%   |
| Intel                   | 23        | 1.48%   |
| Toshiba                 | 14        | 0.9%    |
| Sony                    | 14        | 0.9%    |
| Raspberry Pi Foundation | 12        | 0.77%   |
| Packard Bell            | 12        | 0.77%   |
| Fujitsu                 | 12        | 0.77%   |
| Unknown                 | 9         | 0.58%   |
| Supermicro              | 8         | 0.51%   |
| Samsung Electronics     | 8         | 0.51%   |
| Notebook                | 7         | 0.45%   |
| Foxconn                 | 7         | 0.45%   |
| Google                  | 6         | 0.39%   |
| Pegatron                | 5         | 0.32%   |
| AAEON                   | 5         | 0.32%   |
| Microsoft               | 4         | 0.26%   |
| Maxtang                 | 4         | 0.26%   |
| Fujitsu Siemens         | 4         | 0.26%   |
| TUXEDO                  | 3         | 0.19%   |
| HUAWEI                  | 3         | 0.19%   |
| Star Labs               | 2         | 0.13%   |
| Razer                   | 2         | 0.13%   |
| PC Specialist           | 2         | 0.13%   |
| Linx                    | 2         | 0.13%   |
| eMachines               | 2         | 0.13%   |
| AMD                     | 2         | 0.13%   |
| Alienware               | 2         | 0.13%   |
| ZEPTO                   | 1         | 0.06%   |
| YJKC                    | 1         | 0.06%   |
| XDO.AI                  | 1         | 0.06%   |
| Valve                   | 1         | 0.06%   |
| Timi                    | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 21        | 1.35%   |
| Unknown                            | 12        | 0.77%   |
| ASUS ROG STRIX B450-F GAMING       | 10        | 0.64%   |
| MSI MS-7C37                        | 7         | 0.45%   |
| ASUS ROG STRIX X570-F GAMING       | 7         | 0.45%   |
| ASUS PRIME X470-PRO                | 7         | 0.45%   |
| Dell Precision 5540                | 6         | 0.39%   |
| ASUS ROG STRIX B550-F GAMING       | 6         | 0.39%   |
| MSI MS-7C52                        | 5         | 0.32%   |
| MSI MS-7817                        | 5         | 0.32%   |
| Lenovo Yoga C740-14IML 81TC        | 5         | 0.32%   |
| HP Pavilion 15                     | 5         | 0.32%   |
| HP EliteBook Folio 9470m           | 5         | 0.32%   |
| Gigabyte B450M DS3H                | 5         | 0.32%   |
| Dell XPS 13 9310                   | 5         | 0.32%   |
| ASUS Z170 PRO GAMING               | 5         | 0.32%   |
| ASUS PRIME X370-PRO                | 5         | 0.32%   |
| Apple MacBookPro11,3               | 5         | 0.32%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 4         | 0.26%   |
| MSI MS-7C02                        | 4         | 0.26%   |
| Maxtang FP30                       | 4         | 0.26%   |
| Lenovo MIIX 310-10ICR 80SG         | 4         | 0.26%   |
| HP Pavilion dv7                    | 4         | 0.26%   |
| HP EliteBook 840 G2                | 4         | 0.26%   |
| Dell XPS 15 9570                   | 4         | 0.26%   |
| Dell XPS 15 9500                   | 4         | 0.26%   |
| Dell OptiPlex 7010                 | 4         | 0.26%   |
| ASUS SABERTOOTH 990FX R2.0         | 4         | 0.26%   |
| ASUS ROG STRIX B550-I GAMING       | 4         | 0.26%   |
| ASUS ROG STRIX B350-F GAMING       | 4         | 0.26%   |
| ASUS P8Z77-V LX                    | 4         | 0.26%   |
| ASUS M5A97 R2.0                    | 4         | 0.26%   |
| Apple MacBookAir7,2                | 4         | 0.26%   |
| Acer Aspire V3-571                 | 4         | 0.26%   |
| MSI MS-7C91                        | 3         | 0.19%   |
| MSI MS-7C84                        | 3         | 0.19%   |
| MSI MS-7B98                        | 3         | 0.19%   |
| MSI MS-7971                        | 3         | 0.19%   |
| MSI MS-7850                        | 3         | 0.19%   |
| MSI MS-7640                        | 3         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 118       | 7.57%   |
| ASUS ROG              | 69        | 4.43%   |
| HP EliteBook          | 64        | 4.11%   |
| Acer Aspire           | 49        | 3.15%   |
| Dell Latitude         | 48        | 3.08%   |
| Dell Precision        | 44        | 2.82%   |
| ASUS PRIME            | 38        | 2.44%   |
| HP Pavilion           | 34        | 2.18%   |
| Dell XPS              | 34        | 2.18%   |
| HP ProBook            | 27        | 1.73%   |
| HP Compaq             | 27        | 1.73%   |
| Lenovo IdeaPad        | 25        | 1.6%    |
| Dell OptiPlex         | 22        | 1.41%   |
| ASUS All              | 21        | 1.35%   |
| Lenovo Yoga           | 17        | 1.09%   |
| HP ENVY               | 15        | 0.96%   |
| ASUS TUF              | 15        | 0.96%   |
| ASUS VivoBook         | 14        | 0.9%    |
| Toshiba Satellite     | 12        | 0.77%   |
| RPi Raspberry         | 12        | 0.77%   |
| HP ZBook              | 12        | 0.77%   |
| Unknown               | 12        | 0.77%   |
| Lenovo Legion         | 11        | 0.71%   |
| HP Laptop             | 11        | 0.71%   |
| Dell Inspiron         | 11        | 0.71%   |
| ASUS ZenBook          | 10        | 0.64%   |
| Packard Bell EasyNote | 8         | 0.51%   |
| Gigabyte X570         | 8         | 0.51%   |
| ASUS P8Z77-V          | 8         | 0.51%   |
| MSI MS-7C37           | 7         | 0.45%   |
| HP EliteDesk          | 7         | 0.45%   |
| Dell Vostro           | 7         | 0.45%   |
| ASUS SABERTOOTH       | 7         | 0.45%   |
| Acer Swift            | 7         | 0.45%   |
| Acer Predator         | 7         | 0.45%   |
| Gigabyte B450M        | 6         | 0.39%   |
| Apple MacBookPro11    | 6         | 0.39%   |
| MSI MS-7C52           | 5         | 0.32%   |
| MSI MS-7817           | 5         | 0.32%   |
| Lenovo IdeaPadFlex    | 5         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 165       | 10.59%  |
| 2019    | 163       | 10.46%  |
| 2020    | 133       | 8.54%   |
| 2011    | 121       | 7.77%   |
| 2013    | 120       | 7.7%    |
| 2017    | 116       | 7.45%   |
| 2012    | 113       | 7.25%   |
| 2015    | 100       | 6.42%   |
| 2014    | 98        | 6.29%   |
| 2021    | 91        | 5.84%   |
| 2016    | 87        | 5.58%   |
| 2010    | 82        | 5.26%   |
| 2008    | 45        | 2.89%   |
| 2009    | 43        | 2.76%   |
| 2007    | 36        | 2.31%   |
| 2022    | 17        | 1.09%   |
| 2006    | 10        | 0.64%   |
| Unknown | 9         | 0.58%   |
| 2005    | 7         | 0.45%   |
| 2004    | 1         | 0.06%   |
| 2002    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 791       | 50.77%  |
| Desktop        | 650       | 41.72%  |
| Convertible    | 38        | 2.44%   |
| Mini pc        | 28        | 1.8%    |
| All in one     | 14        | 0.9%    |
| System on chip | 13        | 0.83%   |
| Tablet         | 12        | 0.77%   |
| Server         | 10        | 0.64%   |
| Phone          | 2         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1432      | 91.5%   |
| Enabled  | 133       | 8.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1549      | 99.42%  |
| Yes  | 9         | 0.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 379       | 24.02%  |
| 4.01-8.0        | 332       | 21.04%  |
| 8.01-16.0       | 269       | 17.05%  |
| 32.01-64.0      | 231       | 14.64%  |
| 3.01-4.0        | 216       | 13.69%  |
| 64.01-256.0     | 48        | 3.04%   |
| 1.01-2.0        | 48        | 3.04%   |
| 24.01-32.0      | 23        | 1.46%   |
| 2.01-3.0        | 15        | 0.95%   |
| 0.51-1.0        | 14        | 0.89%   |
| More than 256.0 | 2         | 0.13%   |
| 0.01-0.5        | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 577       | 33.55%  |
| 2.01-3.0   | 413       | 24.01%  |
| 4.01-8.0   | 297       | 17.27%  |
| 3.01-4.0   | 216       | 12.56%  |
| 0.51-1.0   | 87        | 5.06%   |
| 8.01-16.0  | 85        | 4.94%   |
| 16.01-24.0 | 21        | 1.22%   |
| 0.01-0.5   | 19        | 1.1%    |
| 24.01-32.0 | 4         | 0.23%   |
| Unknown    | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 939       | 58.43%  |
| 2      | 346       | 21.53%  |
| 3      | 137       | 8.53%   |
| 4      | 83        | 5.16%   |
| 5      | 40        | 2.49%   |
| 6      | 23        | 1.43%   |
| 0      | 16        | 1%      |
| 7      | 14        | 0.87%   |
| 8      | 5         | 0.31%   |
| 10     | 2         | 0.12%   |
| 11     | 1         | 0.06%   |
| 9      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1033      | 65.92%  |
| Yes       | 534       | 34.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1361      | 87.13%  |
| No        | 201       | 12.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1107      | 70.51%  |
| No        | 463       | 29.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 919       | 58.24%  |
| No        | 659       | 41.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 1558      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Stockholm               | 277       | 16.77%  |
| Gothenburg              | 164       | 9.93%   |
| Malmo                   | 79        | 4.78%   |
| Uppsala                 | 51        | 3.09%   |
| Lund                    | 39        | 2.36%   |
| Linköping              | 33        | 2%      |
| Västerås              | 24        | 1.45%   |
| Bromma                  | 24        | 1.45%   |
| Sollentuna              | 23        | 1.39%   |
| Norrköping             | 22        | 1.33%   |
| Vaxjo                   | 19        | 1.15%   |
| Vaestra Froelunda       | 18        | 1.09%   |
| Umeå                   | 18        | 1.09%   |
| Karlstad                | 18        | 1.09%   |
| Haegersten              | 18        | 1.09%   |
| Sundsvall               | 17        | 1.03%   |
| Solna                   | 16        | 0.97%   |
| Huddinge                | 16        | 0.97%   |
| Helsingborg             | 14        | 0.85%   |
| Södertälje            | 12        | 0.73%   |
| Kista                   | 12        | 0.73%   |
| Bandhagen               | 12        | 0.73%   |
| Örebro                 | 11        | 0.67%   |
| Moelndal                | 11        | 0.67%   |
| Halmstad                | 11        | 0.67%   |
| Upplands Vasby          | 10        | 0.61%   |
| Taby                    | 10        | 0.61%   |
| Landskrona              | 10        | 0.61%   |
| Sundbyberg              | 9         | 0.54%   |
| Staffanstorp            | 9         | 0.54%   |
| Spanga                  | 9         | 0.54%   |
| Nyköping               | 9         | 0.54%   |
| Norsborg                | 9         | 0.54%   |
| Gävle                  | 9         | 0.54%   |
| Skövde                 | 8         | 0.48%   |
| Mjoelby                 | 8         | 0.48%   |
| Katrineholm             | 8         | 0.48%   |
| Johanneshov             | 8         | 0.48%   |
| Järfälla Municipality | 8         | 0.48%   |
| Handen                  | 8         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 501       | 816    | 21.49%  |
| WDC                       | 333       | 531    | 14.29%  |
| Seagate                   | 295       | 475    | 12.66%  |
| Kingston                  | 182       | 258    | 7.81%   |
| Intel                     | 134       | 174    | 5.75%   |
| Toshiba                   | 117       | 153    | 5.02%   |
| SanDisk                   | 114       | 148    | 4.89%   |
| Unknown                   | 84        | 110    | 3.6%    |
| Hitachi                   | 76        | 101    | 3.26%   |
| SK hynix                  | 59        | 67     | 2.53%   |
| Crucial                   | 56        | 83     | 2.4%    |
| Micron Technology         | 46        | 59     | 1.97%   |
| HGST                      | 42        | 49     | 1.8%    |
| Apple                     | 23        | 28     | 0.99%   |
| OCZ                       | 21        | 24     | 0.9%    |
| Phison                    | 20        | 24     | 0.86%   |
| Corsair                   | 19        | 26     | 0.82%   |
| LITEON                    | 16        | 21     | 0.69%   |
| A-DATA Technology         | 16        | 16     | 0.69%   |
| Transcend                 | 11        | 12     | 0.47%   |
| KIOXIA                    | 11        | 11     | 0.47%   |
| LITEONIT                  | 10        | 17     | 0.43%   |
| Fujitsu                   | 9         | 13     | 0.39%   |
| Silicon Motion            | 8         | 22     | 0.34%   |
| Intenso                   | 8         | 11     | 0.34%   |
| China                     | 7         | 7      | 0.3%    |
| PNY                       | 6         | 8      | 0.26%   |
| Maxtor                    | 6         | 6      | 0.26%   |
| LaCie                     | 5         | 6      | 0.21%   |
| JMicron Technology        | 5         | 5      | 0.21%   |
| Unknown                   | 5         | 5      | 0.21%   |
| Micron/Crucial Technology | 4         | 6      | 0.17%   |
| Lenovo                    | 4         | 4      | 0.17%   |
| ASMT                      | 4         | 4      | 0.17%   |
| XPG                       | 3         | 3      | 0.13%   |
| ROG                       | 3         | 3      | 0.13%   |
| Lite-On                   | 3         | 3      | 0.13%   |
| Hewlett-Packard           | 3         | 6      | 0.13%   |
| GOODRAM                   | 3         | 4      | 0.13%   |
| ZTE                       | 2         | 2      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB        | 45        | 1.68%   |
| Samsung SSD 850 EVO 500GB        | 35        | 1.3%    |
| Kingston SA400S37120G 120GB SSD  | 27        | 1.01%   |
| Kingston SV300S37A120G 120GB SSD | 26        | 0.97%   |
| Samsung NVMe SSD Drive 500GB     | 25        | 0.93%   |
| Kingston SA400S37240G 240GB SSD  | 25        | 0.93%   |
| Samsung SSD 860 EVO 250GB        | 22        | 0.82%   |
| Samsung SSD 840 EVO 250GB        | 22        | 0.82%   |
| Samsung NVMe SSD Drive 512GB     | 20        | 0.75%   |
| Seagate ST4000DM004-2CV104 4TB   | 19        | 0.71%   |
| Samsung SSD 860 EVO 500GB        | 18        | 0.67%   |
| SanDisk NVMe SSD Drive 1TB       | 16        | 0.6%    |
| Samsung SSD 970 EVO Plus 500GB   | 16        | 0.6%    |
| Samsung NVMe SSD Drive 1TB       | 16        | 0.6%    |
| Kingston SA400S37480G 480GB SSD  | 16        | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB   | 15        | 0.56%   |
| Samsung NVMe SSD Drive 256GB     | 15        | 0.56%   |
| Unknown MMC Card  32GB           | 13        | 0.48%   |
| SanDisk NVMe SSD Drive 512GB     | 13        | 0.48%   |
| Samsung SSD 860 EVO 1TB          | 13        | 0.48%   |
| Samsung NVMe SSD Drive 250GB     | 13        | 0.48%   |
| HGST HTS721010A9E630 1TB         | 13        | 0.48%   |
| WDC WD30EFRX-68EUZN0 3TB         | 12        | 0.45%   |
| Toshiba NVMe SSD Drive 512GB     | 12        | 0.45%   |
| Seagate ST500DM002-1BD142 500GB  | 12        | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB     | 12        | 0.45%   |
| Samsung NVMe SSD Drive 1024GB    | 12        | 0.45%   |
| SK hynix NVMe SSD Drive 512GB    | 11        | 0.41%   |
| Seagate ST4000VN008-2DR166 4TB   | 11        | 0.41%   |
| Intel NVMe SSD Drive 1024GB      | 11        | 0.41%   |
| Unknown MMC Card  16GB           | 10        | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB   | 10        | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB   | 10        | 0.37%   |
| SanDisk NVMe SSD Drive 256GB     | 10        | 0.37%   |
| Samsung SSD 840 EVO 500GB        | 10        | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 9         | 0.34%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 9         | 0.34%   |
| Seagate ST9500325AS 500GB        | 9         | 0.34%   |
| Seagate Expansion Desk 2TB       | 9         | 0.34%   |
| Seagate Expansion 1TB            | 9         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 292       | 464    | 35.44%  |
| WDC                 | 262       | 427    | 31.8%   |
| Hitachi             | 76        | 101    | 9.22%   |
| Toshiba             | 68        | 91     | 8.25%   |
| Samsung Electronics | 45        | 78     | 5.46%   |
| HGST                | 42        | 49     | 5.1%    |
| Unknown             | 9         | 11     | 1.09%   |
| Fujitsu             | 9         | 13     | 1.09%   |
| Apple               | 6         | 6      | 0.73%   |
| Maxtor              | 5         | 5      | 0.61%   |
| Intenso             | 2         | 2      | 0.24%   |
| Hewlett-Packard     | 2         | 4      | 0.24%   |
| USB3.0              | 1         | 1      | 0.12%   |
| SATAFIRM            | 1         | 1      | 0.12%   |
| LaCie               | 1         | 1      | 0.12%   |
| IB                  | 1         | 2      | 0.12%   |
| ASMT                | 1         | 1      | 0.12%   |
| ASMedia             | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 304       | 445    | 33.48%  |
| Kingston            | 141       | 196    | 15.53%  |
| Intel               | 81        | 100    | 8.92%   |
| SanDisk             | 61        | 77     | 6.72%   |
| Crucial             | 54        | 80     | 5.95%   |
| WDC                 | 46        | 63     | 5.07%   |
| Micron Technology   | 34        | 46     | 3.74%   |
| OCZ                 | 21        | 24     | 2.31%   |
| SK hynix            | 19        | 22     | 2.09%   |
| Toshiba             | 16        | 23     | 1.76%   |
| LITEON              | 15        | 20     | 1.65%   |
| Apple               | 15        | 19     | 1.65%   |
| Transcend           | 11        | 12     | 1.21%   |
| Corsair             | 11        | 13     | 1.21%   |
| LITEONIT            | 10        | 17     | 1.1%    |
| A-DATA Technology   | 10        | 10     | 1.1%    |
| China               | 7         | 7      | 0.77%   |
| Intenso             | 6         | 6      | 0.66%   |
| PNY                 | 4         | 6      | 0.44%   |
| ASMT                | 3         | 3      | 0.33%   |
| Verbatim            | 2         | 3      | 0.22%   |
| SPCC                | 2         | 3      | 0.22%   |
| Seagate             | 2         | 4      | 0.22%   |
| Patriot             | 2         | 3      | 0.22%   |
| M4-CT128            | 2         | 2      | 0.22%   |
| GOODRAM             | 2         | 3      | 0.22%   |
| XSTAR               | 1         | 1      | 0.11%   |
| WDC WDS2            | 1         | 1      | 0.11%   |
| WDC WDS1            | 1         | 1      | 0.11%   |
| Unknown             | 1         | 1      | 0.11%   |
| TO Exter            | 1         | 1      | 0.11%   |
| tigo                | 1         | 1      | 0.11%   |
| StoreJet            | 1         | 1      | 0.11%   |
| Star                | 1         | 1      | 0.11%   |
| ROG                 | 1         | 1      | 0.11%   |
| Radeon              | 1         | 1      | 0.11%   |
| OWC                 | 1         | 1      | 0.11%   |
| OCZ-VERTEX3         | 1         | 1      | 0.11%   |
| Netac               | 1         | 1      | 0.11%   |
| MyDigitalSSD        | 1         | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 779       | 1235   | 37.4%   |
| HDD     | 666       | 1258   | 31.97%  |
| NVMe    | 533       | 759    | 25.59%  |
| MMC     | 77        | 93     | 3.7%    |
| Unknown | 28        | 38     | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1159      | 2405   | 62.35%  |
| NVMe | 528       | 751    | 28.4%   |
| SAS  | 95        | 134    | 5.11%   |
| MMC  | 77        | 93     | 4.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 954       | 1559   | 60.65%  |
| 0.51-1.0   | 342       | 504    | 21.74%  |
| 1.01-2.0   | 136       | 200    | 8.65%   |
| 3.01-4.0   | 58        | 101    | 3.69%   |
| 2.01-3.0   | 51        | 81     | 3.24%   |
| 4.01-10.0  | 30        | 45     | 1.91%   |
| 10.01-20.0 | 2         | 3      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 461       | 27.94%  |
| 251-500        | 363       | 22%     |
| 501-1000       | 203       | 12.3%   |
| 1-20           | 141       | 8.55%   |
| 1001-2000      | 128       | 7.76%   |
| More than 3000 | 111       | 6.73%   |
| 51-100         | 80        | 4.85%   |
| Unknown        | 65        | 3.94%   |
| 2001-3000      | 51        | 3.09%   |
| 21-50          | 47        | 2.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 667       | 39.37%  |
| 21-50          | 236       | 13.93%  |
| 101-250        | 214       | 12.63%  |
| 51-100         | 174       | 10.27%  |
| 251-500        | 113       | 6.67%   |
| 501-1000       | 93        | 5.49%   |
| Unknown        | 65        | 3.84%   |
| 1001-2000      | 58        | 3.42%   |
| More than 3000 | 40        | 2.36%   |
| 2001-3000      | 32        | 1.89%   |
| 0              | 2         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 5         | 5      | 4.07%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 2.44%   |
| WDC WD5000AAKX-75U6AA0 500GB                   | 2         | 2      | 1.63%   |
| Seagate ST9500420AS 500GB                      | 2         | 2      | 1.63%   |
| Seagate ST9250410AS 250GB                      | 2         | 3      | 1.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2         | 2      | 1.63%   |
| Samsung Electronics HD501LJ 500GB              | 2         | 2      | 1.63%   |
| Samsung Electronics HD300LJ 304GB              | 2         | 2      | 1.63%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 3      | 1.63%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 1.63%   |
| Crucial CT525MX300SSD1 528GB                   | 2         | 2      | 1.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 0.81%   |
| WDC WD7500AACS-00ZJB0 752GB                    | 1         | 1      | 0.81%   |
| WDC WD740GD-00FLA1 74GB                        | 1         | 1      | 0.81%   |
| WDC WD6400AAKS-22A7B2 640GB                    | 1         | 1      | 0.81%   |
| WDC WD60EFRX-68L0BN1 6TB                       | 1         | 6      | 0.81%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 0.81%   |
| WDC WD5000BPKT-60PK4T0 500GB                   | 1         | 1      | 0.81%   |
| WDC WD5000AZRX-00A8LB0 500GB                   | 1         | 2      | 0.81%   |
| WDC WD5000AAKX-22ERMA0 500GB                   | 1         | 1      | 0.81%   |
| WDC WD5000AAKS-00A7B2 500GB                    | 1         | 1      | 0.81%   |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 2      | 0.81%   |
| WDC WD3200AAKS-75L9A0 320GB                    | 1         | 1      | 0.81%   |
| WDC WD3200AAKS-00B3A0 320GB                    | 1         | 3      | 0.81%   |
| WDC WD30EFRX-68AX9N0 3TB                       | 1         | 1      | 0.81%   |
| WDC WD20EARS-00MVWB0 2TB                       | 1         | 1      | 0.81%   |
| WDC WD15EARS-00Z5B1 1TB                        | 1         | 1      | 0.81%   |
| WDC WD15EADS-00P8B0 1TB                        | 1         | 2      | 0.81%   |
| WDC WD10EZEX-21M2NA0 1TB                       | 1         | 2      | 0.81%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1         | 3      | 0.81%   |
| WDC WD10EFRX-68FYTN0 1TB                       | 1         | 1      | 0.81%   |
| WDC WD10EARS-00MVWB0 1TB                       | 1         | 1      | 0.81%   |
| WDC WD10EALX-009BA0 1TB                        | 1         | 3      | 0.81%   |
| WDC WD10EADS-00M2B0 1TB                        | 1         | 1      | 0.81%   |
| WDC WD10EADS-00L5B1 1TB                        | 1         | 1      | 0.81%   |
| Union Memory UMIS RPJTJ128MED1MWX 128GB        | 1         | 1      | 0.81%   |
| Transcend TS240GMTS420S 240GB SSD              | 1         | 1      | 0.81%   |
| Toshiba MK1633GSG 160GB                        | 1         | 1      | 0.81%   |
| Toshiba HDWD110 1TB                            | 1         | 2      | 0.81%   |
| SK hynix SH920 mSATA 128GB SSD                 | 1         | 1      | 0.81%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 32     | 22.03%  |
| WDC                 | 23        | 41     | 19.49%  |
| Samsung Electronics | 13        | 13     | 11.02%  |
| Intel               | 11        | 13     | 9.32%   |
| Hitachi             | 11        | 13     | 9.32%   |
| HGST                | 5         | 5      | 4.24%   |
| Kingston            | 4         | 4      | 3.39%   |
| OCZ                 | 3         | 5      | 2.54%   |
| Micron Technology   | 3         | 4      | 2.54%   |
| Crucial             | 3         | 3      | 2.54%   |
| Corsair             | 3         | 3      | 2.54%   |
| Toshiba             | 2         | 3      | 1.69%   |
| LITEONIT            | 2         | 2      | 1.69%   |
| Fujitsu             | 2         | 2      | 1.69%   |
| Union Memory        | 1         | 1      | 0.85%   |
| Transcend           | 1         | 1      | 0.85%   |
| SK hynix            | 1         | 1      | 0.85%   |
| SanDisk             | 1         | 1      | 0.85%   |
| PNY                 | 1         | 2      | 0.85%   |
| Hewlett-Packard     | 1         | 1      | 0.85%   |
| Apple               | 1         | 1      | 0.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 32     | 33.33%  |
| WDC                 | 22        | 40     | 28.21%  |
| Hitachi             | 11        | 13     | 14.1%   |
| Samsung Electronics | 8         | 8      | 10.26%  |
| HGST                | 5         | 5      | 6.41%   |
| Toshiba             | 2         | 3      | 2.56%   |
| Fujitsu             | 2         | 2      | 2.56%   |
| Hewlett-Packard     | 1         | 1      | 1.28%   |
| Apple               | 1         | 1      | 1.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 75        | 105    | 66.37%  |
| SSD  | 33        | 41     | 29.2%   |
| NVMe | 5         | 5      | 4.42%   |

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
| Detected | 1037      | 2175   | 61%     |
| Works    | 555       | 1057   | 32.65%  |
| Malfunc  | 108       | 151    | 6.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1008      | 50.07%  |
| AMD                              | 341       | 16.94%  |
| Samsung Electronics              | 239       | 11.87%  |
| SanDisk                          | 80        | 3.97%   |
| Kingston Technology Company      | 44        | 2.19%   |
| SK hynix                         | 39        | 1.94%   |
| Toshiba America Info Systems     | 37        | 1.84%   |
| ASMedia Technology               | 36        | 1.79%   |
| JMicron Technology               | 31        | 1.54%   |
| Phison Electronics               | 30        | 1.49%   |
| Marvell Technology Group         | 26        | 1.29%   |
| Nvidia                           | 17        | 0.84%   |
| Micron Technology                | 13        | 0.65%   |
| KIOXIA                           | 10        | 0.5%    |
| Silicon Motion                   | 9         | 0.45%   |
| ADATA Technology                 | 7         | 0.35%   |
| Silicon Image                    | 6         | 0.3%    |
| Micron/Crucial Technology        | 5         | 0.25%   |
| Lite-On Technology               | 5         | 0.25%   |
| VIA Technologies                 | 4         | 0.2%    |
| Union Memory (Shenzhen)          | 4         | 0.2%    |
| Lenovo                           | 4         | 0.2%    |
| Silicon Integrated Systems [SiS] | 3         | 0.15%   |
| Apple                            | 3         | 0.15%   |
| Solid State Storage Technology   | 2         | 0.1%    |
| Realtek Semiconductor            | 2         | 0.1%    |
| LSI Logic / Symbios Logic        | 2         | 0.1%    |
| Hewlett-Packard                  | 2         | 0.1%    |
| Broadcom / LSI                   | 2         | 0.1%    |
| Seagate Technology               | 1         | 0.05%   |
| Adaptec                          | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 229       | 9.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 137       | 5.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 78        | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 72        | 3.08%   |
| AMD 400 Series Chipset SATA Controller                                         | 59        | 2.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 56        | 2.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 51        | 2.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 46        | 1.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 45        | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 44        | 1.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 44        | 1.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 42        | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 41        | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 35        | 1.5%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 35        | 1.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 32        | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 32        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 31        | 1.33%   |
| Intel SATA Controller [RAID mode]                                              | 30        | 1.28%   |
| Intel SSD 660P Series                                                          | 29        | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 28        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 28        | 1.2%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 27        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 27        | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 26        | 1.11%   |
| Kingston Company A2000 NVMe SSD                                                | 25        | 1.07%   |
| Intel Volume Management Device NVMe RAID Controller                            | 25        | 1.07%   |
| AMD 500 Series Chipset SATA Controller                                         | 25        | 1.07%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 24        | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 0.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 21        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 20        | 0.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 19        | 0.81%   |
| Samsung NVMe SSD Controller 980                                                | 17        | 0.73%   |
| Phison E12 NVMe Controller                                                     | 16        | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                             | 16        | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 16        | 0.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 16        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 16        | 0.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 15        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1147      | 56.89%  |
| NVMe | 536       | 26.59%  |
| IDE  | 206       | 10.22%  |
| RAID | 120       | 5.95%   |
| SAS  | 6         | 0.3%    |
| SCSI | 1         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1147      | 73.62%  |
| AMD      | 396       | 25.42%  |
| ARM      | 14        | 0.9%    |
| QUALCOMM | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 23        | 1.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 22        | 1.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 20        | 1.28%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 16        | 1.03%   |
| Intel Core i5-6600K CPU @ 3.50GHz       | 15        | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 14        | 0.9%    |
| AMD Ryzen 9 3900X 12-Core Processor     | 14        | 0.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 13        | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 12        | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 12        | 0.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 11        | 0.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 11        | 0.71%   |
| Intel Core i5-4690K CPU @ 3.50GHz       | 11        | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 10        | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 10        | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 10        | 0.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 0.64%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 10        | 0.64%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 10        | 0.64%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 9         | 0.58%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 9         | 0.58%   |
| ARM Processor                           | 9         | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 8         | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 8         | 0.51%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 8         | 0.51%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 0.51%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 8         | 0.51%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 8         | 0.51%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 8         | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 8         | 0.51%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 8         | 0.51%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 8         | 0.51%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 8         | 0.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 7         | 0.45%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 7         | 0.45%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 7         | 0.45%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 7         | 0.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 7         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 376       | 24.13%  |
| Intel Core i5           | 376       | 24.13%  |
| AMD Ryzen 5             | 100       | 6.42%   |
| AMD Ryzen 7             | 75        | 4.81%   |
| Other                   | 74        | 4.75%   |
| Intel Core i3           | 68        | 4.36%   |
| Intel Core 2 Duo        | 54        | 3.47%   |
| Intel Celeron           | 49        | 3.15%   |
| Intel Xeon              | 36        | 2.31%   |
| AMD Ryzen 9             | 32        | 2.05%   |
| AMD FX                  | 31        | 1.99%   |
| Intel Pentium           | 28        | 1.8%    |
| Intel Atom              | 23        | 1.48%   |
| AMD Ryzen 3             | 19        | 1.22%   |
| Intel Core 2 Quad       | 15        | 0.96%   |
| Intel Core i9           | 13        | 0.83%   |
| Intel Core 2            | 12        | 0.77%   |
| AMD A8                  | 12        | 0.77%   |
| AMD Ryzen Threadripper  | 11        | 0.71%   |
| AMD A6                  | 10        | 0.64%   |
| Intel Pentium Dual-Core | 9         | 0.58%   |
| Intel Genuine           | 9         | 0.58%   |
| AMD A4                  | 9         | 0.58%   |
| AMD Phenom II X4        | 8         | 0.51%   |
| AMD E1                  | 7         | 0.45%   |
| AMD E                   | 7         | 0.45%   |
| AMD Athlon II X2        | 6         | 0.39%   |
| AMD Athlon 64 X2        | 6         | 0.39%   |
| AMD A10                 | 6         | 0.39%   |
| Intel Pentium Dual      | 5         | 0.32%   |
| ARM BCM                 | 5         | 0.32%   |
| AMD Ryzen Embedded      | 5         | 0.32%   |
| AMD Phenom II X6        | 5         | 0.32%   |
| AMD Ryzen 7 PRO         | 4         | 0.26%   |
| AMD Ryzen 5 PRO         | 4         | 0.26%   |
| Intel Pentium Silver    | 3         | 0.19%   |
| AMD Athlon II X3        | 3         | 0.19%   |
| Intel Pentium M         | 2         | 0.13%   |
| Intel Pentium Gold      | 2         | 0.13%   |
| Intel Core m3           | 2         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 619       | 39.65%  |
| 2       | 531       | 34.02%  |
| 6       | 191       | 12.24%  |
| 8       | 116       | 7.43%   |
| 12      | 29        | 1.86%   |
| 1       | 23        | 1.47%   |
| 16      | 21        | 1.35%   |
| 3       | 15        | 0.96%   |
| 18      | 3         | 0.19%   |
| 14      | 3         | 0.19%   |
| 10      | 3         | 0.19%   |
| 32      | 2         | 0.13%   |
| Unknown | 2         | 0.13%   |
| 64      | 1         | 0.06%   |
| 28      | 1         | 0.06%   |
| 20      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1537      | 98.65%  |
| 2       | 19        | 1.22%   |
| 3       | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1051      | 67.37%  |
| 1       | 507       | 32.5%   |
| Unknown | 2         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1510      | 96.67%  |
| Unknown        | 41        | 2.62%   |
| 32-bit         | 10        | 0.64%   |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 386       | 23.86%  |
| 0x306c3    | 89        | 5.5%    |
| 0x206a7    | 79        | 4.88%   |
| 0x306a9    | 73        | 4.51%   |
| 0x1067a    | 47        | 2.9%    |
| 0x906ea    | 46        | 2.84%   |
| 0x40651    | 45        | 2.78%   |
| 0x906e9    | 38        | 2.35%   |
| 0x806ec    | 38        | 2.35%   |
| 0x506e3    | 37        | 2.29%   |
| 0x806ea    | 36        | 2.22%   |
| 0x406e3    | 36        | 2.22%   |
| 0x306d4    | 32        | 1.98%   |
| 0x806e9    | 31        | 1.92%   |
| 0x806c1    | 30        | 1.85%   |
| 0x08701021 | 30        | 1.85%   |
| 0x20655    | 26        | 1.61%   |
| 0x0800820d | 19        | 1.17%   |
| 0x08701013 | 16        | 0.99%   |
| 0x08108109 | 15        | 0.93%   |
| 0x406c4    | 14        | 0.87%   |
| 0x0810100b | 14        | 0.87%   |
| 0x906ed    | 13        | 0.8%    |
| 0x6fd      | 13        | 0.8%    |
| 0x06000852 | 13        | 0.8%    |
| 0x010000c8 | 13        | 0.8%    |
| 0x106e5    | 12        | 0.74%   |
| 0x0a50000c | 12        | 0.74%   |
| 0x0a201009 | 12        | 0.74%   |
| 0x6f6      | 11        | 0.68%   |
| 0x306f2    | 11        | 0.68%   |
| 0x30678    | 11        | 0.68%   |
| 0x806eb    | 10        | 0.62%   |
| 0x10676    | 10        | 0.62%   |
| 0x06001119 | 10        | 0.62%   |
| 0xa0652    | 9         | 0.56%   |
| 0x08600106 | 9         | 0.56%   |
| 0x08001138 | 9         | 0.56%   |
| 0x0700010f | 9         | 0.56%   |
| 0x6fb      | 8         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 280       | 17.96%  |
| Haswell          | 179       | 11.48%  |
| SandyBridge      | 113       | 7.25%   |
| Skylake          | 98        | 6.29%   |
| IvyBridge        | 96        | 6.16%   |
| Zen 2            | 84        | 5.39%   |
| Penryn           | 66        | 4.23%   |
| Zen+             | 60        | 3.85%   |
| Zen 3            | 47        | 3.01%   |
| Zen              | 46        | 2.95%   |
| Westmere         | 44        | 2.82%   |
| Broadwell        | 44        | 2.82%   |
| Core             | 43        | 2.76%   |
| Silvermont       | 42        | 2.69%   |
| TigerLake        | 40        | 2.57%   |
| Unknown          | 38        | 2.44%   |
| K10              | 36        | 2.31%   |
| Piledriver       | 32        | 2.05%   |
| CometLake        | 24        | 1.54%   |
| Nehalem          | 18        | 1.15%   |
| Goldmont plus    | 14        | 0.9%    |
| Excavator        | 13        | 0.83%   |
| K8 Hammer        | 12        | 0.77%   |
| K10 Llano        | 10        | 0.64%   |
| Jaguar           | 10        | 0.64%   |
| IceLake          | 10        | 0.64%   |
| Bulldozer        | 10        | 0.64%   |
| Bobcat           | 9         | 0.58%   |
| Alderlake Hybrid | 8         | 0.51%   |
| Goldmont         | 7         | 0.45%   |
| Puma             | 6         | 0.38%   |
| Bonnell          | 6         | 0.38%   |
| P6               | 4         | 0.26%   |
| NetBurst         | 3         | 0.19%   |
| Steamroller      | 2         | 0.13%   |
| K8 & K10 hybrid  | 2         | 0.13%   |
| Tremont          | 1         | 0.06%   |
| K6               | 1         | 0.06%   |
| Geode            | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 798       | 44.06%  |
| Nvidia                           | 592       | 32.69%  |
| AMD                              | 404       | 22.31%  |
| Matrox Electronics Systems       | 7         | 0.39%   |
| ASPEED Technology                | 7         | 0.39%   |
| Silicon Integrated Systems [SiS] | 3         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 74        | 3.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 52        | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 50        | 2.67%   |
| Intel UHD Graphics 620                                                                   | 41        | 2.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 39        | 2.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 2.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 38        | 2.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 36        | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 36        | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 33        | 1.76%   |
| Intel HD Graphics 620                                                                    | 29        | 1.55%   |
| Intel HD Graphics 5500                                                                   | 29        | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 26        | 1.39%   |
| Intel HD Graphics 630                                                                    | 26        | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 24        | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 24        | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 1.12%   |
| AMD Renoir                                                                               | 21        | 1.12%   |
| AMD Cezanne                                                                              | 21        | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 20        | 1.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 1.07%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 19        | 1.01%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 19        | 1.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 0.91%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 16        | 0.85%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 16        | 0.85%   |
| Intel HD Graphics 530                                                                    | 15        | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 14        | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 14        | 0.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 13        | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 13        | 0.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 13        | 0.69%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 13        | 0.69%   |
| AMD Lucienne                                                                             | 13        | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 0.64%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 12        | 0.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 564       | 35.9%   |
| 1 x Nvidia               | 383       | 24.38%  |
| 1 x AMD                  | 329       | 20.94%  |
| Intel + Nvidia           | 181       | 11.52%  |
| Intel + AMD              | 29        | 1.85%   |
| 2 x AMD                  | 26        | 1.65%   |
| AMD + Nvidia             | 21        | 1.34%   |
| Other                    | 15        | 0.95%   |
| 1 x ASPEED               | 7         | 0.45%   |
| 1 x Matrox               | 5         | 0.32%   |
| 2 x Nvidia               | 4         | 0.25%   |
| 1 x SiS                  | 3         | 0.19%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.06%   |
| Nvidia + Matrox          | 1         | 0.06%   |
| Intel + 2 x Nvidia       | 1         | 0.06%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1157      | 73.14%  |
| Proprietary | 355       | 22.44%  |
| Unknown     | 70        | 4.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 820       | 51.19%  |
| 1.01-2.0   | 190       | 11.86%  |
| 0.01-0.5   | 163       | 10.17%  |
| 0.51-1.0   | 113       | 7.05%   |
| 3.01-4.0   | 111       | 6.93%   |
| 7.01-8.0   | 102       | 6.37%   |
| 5.01-6.0   | 53        | 3.31%   |
| 8.01-16.0  | 27        | 1.69%   |
| 2.01-3.0   | 20        | 1.25%   |
| 16.01-24.0 | 3         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 220       | 12.44%  |
| Samsung Electronics     | 212       | 11.99%  |
| LG Display              | 131       | 7.41%   |
| Chimei Innolux          | 123       | 6.96%   |
| Dell                    | 103       | 5.83%   |
| BenQ                    | 96        | 5.43%   |
| Philips                 | 86        | 4.86%   |
| Ancor Communications    | 82        | 4.64%   |
| AOC                     | 73        | 4.13%   |
| Hewlett-Packard         | 72        | 4.07%   |
| BOE                     | 71        | 4.02%   |
| Acer                    | 61        | 3.45%   |
| Sharp                   | 46        | 2.6%    |
| Goldstar                | 43        | 2.43%   |
| Lenovo                  | 36        | 2.04%   |
| Apple                   | 36        | 2.04%   |
| ASUSTek Computer        | 28        | 1.58%   |
| Eizo                    | 19        | 1.07%   |
| Chi Mei Optoelectronics | 19        | 1.07%   |
| LG Philips              | 16        | 0.9%    |
| InfoVision              | 15        | 0.85%   |
| Vestel Elektronik       | 12        | 0.68%   |
| Sony                    | 12        | 0.68%   |
| Unknown                 | 11        | 0.62%   |
| MSI                     | 11        | 0.62%   |
| Panasonic               | 9         | 0.51%   |
| LG Electronics          | 9         | 0.51%   |
| CSO                     | 8         | 0.45%   |
| ViewSonic               | 7         | 0.4%    |
| PANDA                   | 6         | 0.34%   |
| Toshiba                 | 5         | 0.28%   |
| Fujitsu Siemens         | 5         | 0.28%   |
| BOE Technology Group    | 5         | 0.28%   |
| VOXICON                 | 4         | 0.23%   |
| Quanta Display          | 4         | 0.23%   |
| OEM                     | 4         | 0.23%   |
| Microstep               | 4         | 0.23%   |
| LGD                     | 4         | 0.23%   |
| AUS                     | 4         | 0.23%   |
| Packard Bell            | 3         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 12        | 0.65%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 11        | 0.59%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8         | 0.43%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 8         | 0.43%   |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                  | 8         | 0.43%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 8         | 0.43%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 7         | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.38%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 7         | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 0.38%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 7         | 0.38%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                  | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 6         | 0.32%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 6         | 0.32%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 5         | 0.27%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch            | 5         | 0.27%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 5         | 0.27%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 5         | 0.27%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 5         | 0.27%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 5         | 0.27%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 5         | 0.27%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 5         | 0.27%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 5         | 0.27%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 4         | 0.22%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 4         | 0.22%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 4         | 0.22%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 4         | 0.22%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                       | 4         | 0.22%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 4         | 0.22%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.22%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch          | 4         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 4         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 4         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 4         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 758       | 44.43%  |
| 1366x768 (WXGA)    | 204       | 11.96%  |
| 2560x1440 (QHD)    | 139       | 8.15%   |
| 3840x2160 (4K)     | 135       | 7.91%   |
| 1680x1050 (WSXGA+) | 65        | 3.81%   |
| 1920x1200 (WUXGA)  | 55        | 3.22%   |
| 3440x1440          | 40        | 2.34%   |
| 1600x900 (HD+)     | 38        | 2.23%   |
| 1280x1024 (SXGA)   | 36        | 2.11%   |
| 1280x800 (WXGA)    | 35        | 2.05%   |
| Unknown            | 34        | 1.99%   |
| 1440x900 (WXGA+)   | 24        | 1.41%   |
| 3840x1080          | 17        | 1%      |
| 2560x1600          | 16        | 0.94%   |
| 3840x2400          | 13        | 0.76%   |
| 2880x1800          | 13        | 0.76%   |
| 1024x768 (XGA)     | 11        | 0.64%   |
| 1360x768           | 9         | 0.53%   |
| 1920x540           | 7         | 0.41%   |
| 1280x720 (HD)      | 7         | 0.41%   |
| 1024x600           | 5         | 0.29%   |
| 3200x1800 (QHD+)   | 4         | 0.23%   |
| 2560x1080          | 4         | 0.23%   |
| 6400x2160          | 3         | 0.18%   |
| 5760x1080          | 3         | 0.18%   |
| 2736x1824          | 3         | 0.18%   |
| 2288x1287          | 3         | 0.18%   |
| 5760x2160          | 2         | 0.12%   |
| 3840x1600          | 2         | 0.12%   |
| 3840x1200          | 2         | 0.12%   |
| 3200x1200          | 2         | 0.12%   |
| 2160x1440          | 2         | 0.12%   |
| 800x1280           | 1         | 0.06%   |
| 7280x2160          | 1         | 0.06%   |
| 5520x2160          | 1         | 0.06%   |
| 4864x1080          | 1         | 0.06%   |
| 4480x1440          | 1         | 0.06%   |
| 4240x1440          | 1         | 0.06%   |
| 3600x1080          | 1         | 0.06%   |
| 3360x1080          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 329       | 18.67%  |
| 24      | 191       | 10.84%  |
| 27      | 187       | 10.61%  |
| 13      | 185       | 10.5%   |
| Unknown | 130       | 7.38%   |
| 14      | 124       | 7.04%   |
| 23      | 119       | 6.75%   |
| 17      | 70        | 3.97%   |
| 12      | 49        | 2.78%   |
| 22      | 48        | 2.72%   |
| 21      | 45        | 2.55%   |
| 31      | 39        | 2.21%   |
| 34      | 37        | 2.1%    |
| 19      | 36        | 2.04%   |
| 84      | 24        | 1.36%   |
| 11      | 22        | 1.25%   |
| 32      | 16        | 0.91%   |
| 20      | 10        | 0.57%   |
| 72      | 9         | 0.51%   |
| 54      | 9         | 0.51%   |
| 25      | 8         | 0.45%   |
| 65      | 6         | 0.34%   |
| 42      | 6         | 0.34%   |
| 18      | 6         | 0.34%   |
| 35      | 5         | 0.28%   |
| 29      | 5         | 0.28%   |
| 16      | 5         | 0.28%   |
| 10      | 5         | 0.28%   |
| 49      | 4         | 0.23%   |
| 39      | 4         | 0.23%   |
| 50      | 3         | 0.17%   |
| 48      | 3         | 0.17%   |
| 46      | 3         | 0.17%   |
| 37      | 3         | 0.17%   |
| 55      | 2         | 0.11%   |
| 47      | 2         | 0.11%   |
| 33      | 2         | 0.11%   |
| 26      | 2         | 0.11%   |
| 142     | 1         | 0.06%   |
| 75      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 545       | 31.65%  |
| 501-600        | 454       | 26.36%  |
| 201-300        | 172       | 9.99%   |
| Unknown        | 130       | 7.55%   |
| 401-500        | 119       | 6.91%   |
| 351-400        | 96        | 5.57%   |
| 601-700        | 61        | 3.54%   |
| 701-800        | 55        | 3.19%   |
| 1501-2000      | 35        | 2.03%   |
| 1001-1500      | 34        | 1.97%   |
| 801-900        | 12        | 0.7%    |
| 901-1000       | 8         | 0.46%   |
| More than 2000 | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1113      | 70.31%  |
| 16/10   | 232       | 14.66%  |
| Unknown | 121       | 7.64%   |
| 21/9    | 44        | 2.78%   |
| 5/4     | 37        | 2.34%   |
| 4/3     | 14        | 0.88%   |
| 3/2     | 13        | 0.82%   |
| 32/9    | 6         | 0.38%   |
| 1.00    | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |
| 0.45    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 327       | 18.9%   |
| 201-250        | 300       | 17.34%  |
| 81-90          | 227       | 13.12%  |
| 301-350        | 189       | 10.92%  |
| Unknown        | 130       | 7.51%   |
| 351-500        | 101       | 5.84%   |
| 71-80          | 81        | 4.68%   |
| 251-300        | 76        | 4.39%   |
| More than 1000 | 59        | 3.41%   |
| 151-200        | 55        | 3.18%   |
| 121-130        | 54        | 3.12%   |
| 61-70          | 47        | 2.72%   |
| 501-1000       | 26        | 1.5%    |
| 51-60          | 22        | 1.27%   |
| 141-150        | 13        | 0.75%   |
| 131-140        | 9         | 0.52%   |
| 41-50          | 5         | 0.29%   |
| 111-120        | 5         | 0.29%   |
| 91-100         | 4         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 552       | 32.9%   |
| 121-160       | 426       | 25.39%  |
| 101-120       | 351       | 20.92%  |
| Unknown       | 130       | 7.75%   |
| 161-240       | 115       | 6.85%   |
| More than 240 | 58        | 3.46%   |
| 1-50          | 46        | 2.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1185      | 74.02%  |
| 2     | 298       | 18.61%  |
| 0     | 82        | 5.12%   |
| 3     | 32        | 2%      |
| 4     | 4         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 880       | 39.3%   |
| Realtek Semiconductor                  | 668       | 29.83%  |
| Qualcomm Atheros                       | 229       | 10.23%  |
| Broadcom                               | 138       | 6.16%   |
| Broadcom Limited                       | 33        | 1.47%   |
| Marvell Technology Group               | 25        | 1.12%   |
| Ralink                                 | 19        | 0.85%   |
| MediaTek                               | 17        | 0.76%   |
| Hewlett-Packard                        | 15        | 0.67%   |
| Nvidia                                 | 13        | 0.58%   |
| D-Link System                          | 13        | 0.58%   |
| NetGear                                | 11        | 0.49%   |
| Lenovo                                 | 11        | 0.49%   |
| Dell                                   | 11        | 0.49%   |
| D-Link                                 | 11        | 0.49%   |
| ASIX Electronics                       | 11        | 0.49%   |
| Ralink Technology                      | 10        | 0.45%   |
| Microsoft                              | 10        | 0.45%   |
| ASUSTek Computer                       | 10        | 0.45%   |
| TP-Link                                | 9         | 0.4%    |
| Huawei Technologies                    | 9         | 0.4%    |
| Sierra Wireless                        | 8         | 0.36%   |
| Ericsson Business Mobile Networks      | 6         | 0.27%   |
| DisplayLink                            | 6         | 0.27%   |
| Qualcomm Atheros Communications        | 5         | 0.22%   |
| Qualcomm                               | 4         | 0.18%   |
| FIBOCOM                                | 4         | 0.18%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.13%   |
| Samsung Electronics                    | 3         | 0.13%   |
| Belkin Components                      | 3         | 0.13%   |
| Aquantia                               | 3         | 0.13%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.09%   |
| Standard Microsystems                  | 2         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.09%   |
| Microchip Technology                   | 2         | 0.09%   |
| ICS Advent                             | 2         | 0.09%   |
| Dresden Elektronik                     | 2         | 0.09%   |
| Xiaomi                                 | 1         | 0.04%   |
| Wilocity                               | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 489       | 18.25%  |
| Intel I211 Gigabit Network Connection                             | 84        | 3.13%   |
| Intel Wi-Fi 6 AX200                                               | 72        | 2.69%   |
| Intel Wireless 8265 / 8275                                        | 68        | 2.54%   |
| Intel Wireless 7260                                               | 59        | 2.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 57        | 2.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47        | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 46        | 1.72%   |
| Intel Wireless 8260                                               | 43        | 1.6%    |
| Intel Ethernet Connection (2) I219-V                              | 40        | 1.49%   |
| Intel Wireless 7265                                               | 37        | 1.38%   |
| Intel Wi-Fi 6 AX201                                               | 34        | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 30        | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28        | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 28        | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 26        | 0.97%   |
| Intel Ethernet Connection I217-LM                                 | 26        | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 25        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 24        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 24        | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 23        | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 21        | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 21        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 20        | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 20        | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 19        | 0.71%   |
| Intel Ethernet Connection (4) I219-V                              | 19        | 0.71%   |
| Intel Ethernet Connection (2) I218-V                              | 19        | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 18        | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 17        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 17        | 0.63%   |
| Intel Wireless-AC 9260                                            | 17        | 0.63%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 16        | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 15        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 15        | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 611       | 52.31%  |
| Qualcomm Atheros                  | 172       | 14.73%  |
| Realtek Semiconductor             | 134       | 11.47%  |
| Broadcom                          | 92        | 7.88%   |
| Ralink                            | 19        | 1.63%   |
| MediaTek                          | 17        | 1.46%   |
| Broadcom Limited                  | 16        | 1.37%   |
| NetGear                           | 11        | 0.94%   |
| Ralink Technology                 | 10        | 0.86%   |
| D-Link                            | 10        | 0.86%   |
| ASUSTek Computer                  | 10        | 0.86%   |
| D-Link System                     | 9         | 0.77%   |
| Sierra Wireless                   | 8         | 0.68%   |
| TP-Link                           | 6         | 0.51%   |
| Microsoft                         | 6         | 0.51%   |
| Qualcomm Atheros Communications   | 5         | 0.43%   |
| Dell                              | 5         | 0.43%   |
| Marvell Technology Group          | 4         | 0.34%   |
| Hewlett-Packard                   | 4         | 0.34%   |
| FIBOCOM                           | 4         | 0.34%   |
| Belkin Components                 | 3         | 0.26%   |
| Qualcomm                          | 2         | 0.17%   |
| Ericsson Business Mobile Networks | 2         | 0.17%   |
| Wilocity                          | 1         | 0.09%   |
| Wacom                             | 1         | 0.09%   |
| Sitecom Europe                    | 1         | 0.09%   |
| Micro Star International          | 1         | 0.09%   |
| Linksys                           | 1         | 0.09%   |
| IMC Networks                      | 1         | 0.09%   |
| Edimax Technology                 | 1         | 0.09%   |
| Chu Yuen Enterprise               | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 72        | 6.14%   |
| Intel Wireless 8265 / 8275                                     | 68        | 5.8%    |
| Intel Wireless 7260                                            | 59        | 5.03%   |
| Intel Wireless 8260                                            | 43        | 3.67%   |
| Intel Wireless 7265                                            | 37        | 3.15%   |
| Intel Wi-Fi 6 AX201                                            | 34        | 2.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 30        | 2.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 28        | 2.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 26        | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 25        | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 24        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 23        | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 22        | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 21        | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 20        | 1.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 20        | 1.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 18        | 1.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 17        | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 17        | 1.45%   |
| Intel Wireless-AC 9260                                         | 17        | 1.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 16        | 1.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 1.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 15        | 1.28%   |
| Intel Wireless 3160                                            | 14        | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 14        | 1.19%   |
| Intel Centrino Advanced-N 6200                                 | 14        | 1.19%   |
| Intel Wireless 3165                                            | 13        | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 12        | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 12        | 1.02%   |
| Intel Centrino Advanced-N 6235                                 | 12        | 1.02%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 12        | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 10        | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 9         | 0.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 9         | 0.77%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 9         | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 9         | 0.77%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8         | 0.68%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 7         | 0.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 7         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 618       | 43.1%   |
| Intel                                  | 536       | 37.38%  |
| Qualcomm Atheros                       | 85        | 5.93%   |
| Broadcom                               | 64        | 4.46%   |
| Marvell Technology Group               | 21        | 1.46%   |
| Broadcom Limited                       | 18        | 1.26%   |
| Nvidia                                 | 13        | 0.91%   |
| ASIX Electronics                       | 11        | 0.77%   |
| Lenovo                                 | 10        | 0.7%    |
| Huawei Technologies                    | 7         | 0.49%   |
| DisplayLink                            | 6         | 0.42%   |
| Hewlett-Packard                        | 5         | 0.35%   |
| Microsoft                              | 4         | 0.28%   |
| D-Link System                          | 4         | 0.28%   |
| TP-Link                                | 3         | 0.21%   |
| Samsung Electronics                    | 3         | 0.21%   |
| Aquantia                               | 3         | 0.21%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.14%   |
| Standard Microsystems                  | 2         | 0.14%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.14%   |
| Qualcomm                               | 2         | 0.14%   |
| Microchip Technology                   | 2         | 0.14%   |
| ICS Advent                             | 2         | 0.14%   |
| Xiaomi                                 | 1         | 0.07%   |
| VIA Technologies                       | 1         | 0.07%   |
| Unknown                                | 1         | 0.07%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.07%   |
| JMicron Technology                     | 1         | 0.07%   |
| Gemtek                                 | 1         | 0.07%   |
| D-Link                                 | 1         | 0.07%   |
| Apple                                  | 1         | 0.07%   |
| 3Com                                   | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 489       | 33.31%  |
| Intel I211 Gigabit Network Connection                             | 84        | 5.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 57        | 3.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47        | 3.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 46        | 3.13%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 2.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28        | 1.91%   |
| Intel Ethernet Connection I217-LM                                 | 26        | 1.77%   |
| Intel Ethernet Connection (7) I219-V                              | 24        | 1.63%   |
| Intel 82579V Gigabit Network Connection                           | 21        | 1.43%   |
| Intel Ethernet Controller I225-V                                  | 19        | 1.29%   |
| Intel Ethernet Connection (4) I219-V                              | 19        | 1.29%   |
| Intel Ethernet Connection (2) I218-V                              | 19        | 1.29%   |
| Intel Ethernet Connection I218-LM                                 | 18        | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 1.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 1.02%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 1.02%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.95%   |
| Intel Ethernet Connection I219-V                                  | 13        | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 13        | 0.89%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 13        | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11        | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.75%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 10        | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.61%   |
| Intel Ethernet Connection (6) I219-LM                             | 9         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                             | 7         | 0.48%   |
| Intel 82566MM Gigabit Network Connection                          | 7         | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 0.41%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1357      | 54.21%  |
| WiFi     | 1107      | 44.23%  |
| Modem    | 32        | 1.28%   |
| Unknown  | 7         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 833       | 51.48%  |
| Ethernet | 783       | 48.39%  |
| Unknown  | 2         | 0.12%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 809       | 51.79%  |
| 1     | 664       | 42.51%  |
| 3     | 41        | 2.62%   |
| 0     | 33        | 2.11%   |
| 4     | 8         | 0.51%   |
| 5     | 5         | 0.32%   |
| 9     | 1         | 0.06%   |
| 6     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1523      | 97.32%  |
| Yes  | 42        | 2.68%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 482       | 51.88%  |
| Realtek Semiconductor           | 56        | 6.03%   |
| Qualcomm Atheros Communications | 56        | 6.03%   |
| ASUSTek Computer                | 53        | 5.71%   |
| Cambridge Silicon Radio         | 49        | 5.27%   |
| Broadcom                        | 40        | 4.31%   |
| Apple                           | 40        | 4.31%   |
| IMC Networks                    | 38        | 4.09%   |
| Lite-On Technology              | 26        | 2.8%    |
| Foxconn / Hon Hai               | 25        | 2.69%   |
| Hewlett-Packard                 | 16        | 1.72%   |
| Dell                            | 15        | 1.61%   |
| Ralink                          | 7         | 0.75%   |
| Toshiba                         | 4         | 0.43%   |
| Marvell Semiconductor           | 4         | 0.43%   |
| MediaTek                        | 3         | 0.32%   |
| Realtek                         | 2         | 0.22%   |
| Ralink Technology               | 2         | 0.22%   |
| Micro Star International        | 2         | 0.22%   |
| HTC (High Tech Computer)        | 2         | 0.22%   |
| Chicony Electronics             | 2         | 0.22%   |
| USI                             | 1         | 0.11%   |
| Fujitsu                         | 1         | 0.11%   |
| Creative Technology             | 1         | 0.11%   |
| Alps Electric                   | 1         | 0.11%   |
| Unknown                         | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 218       | 23.37%  |
| Intel AX201 Bluetooth                               | 72        | 7.72%   |
| Intel AX200 Bluetooth                               | 69        | 7.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 50        | 5.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 49        | 5.25%   |
| Realtek Bluetooth Radio                             | 38        | 4.07%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 24        | 2.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 20        | 2.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 2.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 1.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 1.61%   |
| Apple Bluetooth Host Controller                     | 15        | 1.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 1.5%    |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 1.5%    |
| Qualcomm Atheros  Bluetooth Device                  | 13        | 1.39%   |
| IMC Networks Bluetooth Radio                        | 13        | 1.39%   |
| Intel AX210 Bluetooth                               | 12        | 1.29%   |
| IMC Networks Bluetooth Device                       | 12        | 1.29%   |
| Apple Bluetooth USB Host Controller                 | 12        | 1.29%   |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 1.18%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 1.18%   |
| Lite-On Bluetooth Device                            | 9         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.86%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 8         | 0.86%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.75%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.64%   |
| ASUS Bluetooth Radio                                | 6         | 0.64%   |
| ASUS ASUS USB-BT500                                 | 6         | 0.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.54%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.54%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.43%   |
| Intel Bluetooth Device                              | 4         | 0.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.43%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.43%   |
| Broadcom HP Portable SoftSailing                    | 4         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1083      | 46.74%  |
| AMD                                             | 476       | 20.54%  |
| Nvidia                                          | 440       | 18.99%  |
| C-Media Electronics                             | 44        | 1.9%    |
| Logitech                                        | 27        | 1.17%   |
| Kingston Technology                             | 16        | 0.69%   |
| Creative Labs                                   | 16        | 0.69%   |
| Realtek Semiconductor                           | 13        | 0.56%   |
| Plantronics                                     | 13        | 0.56%   |
| Texas Instruments                               | 12        | 0.52%   |
| Focusrite-Novation                              | 11        | 0.47%   |
| Creative Technology                             | 10        | 0.43%   |
| SteelSeries ApS                                 | 9         | 0.39%   |
| Lenovo                                          | 9         | 0.39%   |
| Razer USA                                       | 8         | 0.35%   |
| Corsair                                         | 8         | 0.35%   |
| SAVITECH                                        | 7         | 0.3%    |
| RODE Microphones                                | 7         | 0.3%    |
| GN Netcom                                       | 5         | 0.22%   |
| Yamaha                                          | 4         | 0.17%   |
| Micro Star International                        | 4         | 0.17%   |
| GYROCOM C&C                                     | 4         | 0.17%   |
| Blue Microphones                                | 4         | 0.17%   |
| ASUSTek Computer                                | 4         | 0.17%   |
| VIA Technologies                                | 3         | 0.13%   |
| Silicon Integrated Systems [SiS]                | 3         | 0.13%   |
| Samson Technologies                             | 3         | 0.13%   |
| PreSonus Audio Electronics                      | 3         | 0.13%   |
| JMTek                                           | 3         | 0.13%   |
| Valve Software                                  | 2         | 0.09%   |
| Sennheiser Communications                       | 2         | 0.09%   |
| Schiit Audio                                    | 2         | 0.09%   |
| Samsung Electronics                             | 2         | 0.09%   |
| RME                                             | 2         | 0.09%   |
| M-Audio                                         | 2         | 0.09%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.09%   |
| Hewlett-Packard                                 | 2         | 0.09%   |
| Generalplus Technology                          | 2         | 0.09%   |
| DSEA A/S                                        | 2         | 0.09%   |
| BEHRINGER International                         | 2         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 122       | 4.48%   |
| AMD Family 17h/19h HD Audio Controller                                     | 104       | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 100       | 3.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 99        | 3.64%   |
| AMD Starship/Matisse HD Audio Controller                                   | 85        | 3.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 83        | 3.05%   |
| Intel Cannon Lake PCH cAVS                                                 | 72        | 2.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 70        | 2.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 55        | 2.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 53        | 1.95%   |
| Intel Haswell-ULT HD Audio Controller                                      | 52        | 1.91%   |
| Intel 8 Series HD Audio Controller                                         | 52        | 1.91%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 51        | 1.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 49        | 1.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 48        | 1.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 42        | 1.54%   |
| AMD FCH Azalia Controller                                                  | 42        | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 40        | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 40        | 1.47%   |
| Nvidia GP106 High Definition Audio Controller                              | 39        | 1.43%   |
| Intel 200 Series PCH HD Audio                                              | 39        | 1.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 37        | 1.36%   |
| Intel Broadwell-U Audio Controller                                         | 37        | 1.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 37        | 1.36%   |
| Nvidia GP104 High Definition Audio Controller                              | 34        | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 34        | 1.25%   |
| Nvidia TU106 High Definition Audio Controller                              | 31        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 27        | 0.99%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 27        | 0.99%   |
| Nvidia GM204 High Definition Audio Controller                              | 25        | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 25        | 0.92%   |
| Intel CM238 HD Audio Controller                                            | 25        | 0.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 25        | 0.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 24        | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                               | 23        | 0.84%   |
| Nvidia High Definition Audio Controller                                    | 22        | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 22        | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 22        | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                   | 22        | 0.81%   |
| AMD Navi 10 HDMI Audio                                                     | 21        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 191       | 21.7%   |
| SK hynix                     | 153       | 17.39%  |
| Corsair                      | 128       | 14.55%  |
| Kingston                     | 107       | 12.16%  |
| Micron Technology            | 84        | 9.55%   |
| Unknown                      | 75        | 8.52%   |
| Crucial                      | 45        | 5.11%   |
| G.Skill                      | 27        | 3.07%   |
| Ramaxel Technology           | 11        | 1.25%   |
| Elpida                       | 10        | 1.14%   |
| A-DATA Technology            | 10        | 1.14%   |
| Unknown (ABCD)               | 7         | 0.8%    |
| Nanya Technology             | 7         | 0.8%    |
| Unknown                      | 3         | 0.34%   |
| Transcend                    | 2         | 0.23%   |
| Team                         | 2         | 0.23%   |
| Qimonda                      | 2         | 0.23%   |
| Patriot                      | 2         | 0.23%   |
| G-Alantic                    | 2         | 0.23%   |
| Avant                        | 2         | 0.23%   |
| Unknown (AB)                 | 1         | 0.11%   |
| Unknown (836D)               | 1         | 0.11%   |
| SHARETRONIC                  | 1         | 0.11%   |
| Patriot Memory (PDP Systems) | 1         | 0.11%   |
| Netlist                      | 1         | 0.11%   |
| GSkill                       | 1         | 0.11%   |
| GOODRAM                      | 1         | 0.11%   |
| ASint Technology             | 1         | 0.11%   |
| Apacer                       | 1         | 0.11%   |
| Ankowall                     | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s           | 18        | 1.9%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s           | 10        | 1.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 8         | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 8         | 0.84%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 8         | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 6         | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 6         | 0.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s           | 6         | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s           | 6         | 0.63%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 6         | 0.63%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s           | 6         | 0.63%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                    | 5         | 0.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 5         | 0.53%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 5         | 0.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s       | 5         | 0.53%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 5         | 0.53%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s               | 5         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 4         | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s | 4         | 0.42%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s          | 4         | 0.42%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 4         | 0.42%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 4         | 0.42%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s           | 4         | 0.42%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s           | 4         | 0.42%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 4         | 0.42%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s          | 4         | 0.42%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s           | 4         | 0.42%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s        | 4         | 0.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 4         | 0.42%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s             | 4         | 0.42%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s       | 4         | 0.42%   |
| Corsair RAM CMK8GX4M2A2666C16 4096MB DIMM DDR4 2747MT/s         | 4         | 0.42%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s          | 4         | 0.42%   |
| Corsair RAM CMK16GX4M2Z3600C18 8GB DIMM DDR4 3600MT/s           | 4         | 0.42%   |
| Corsair RAM CMK16GX4M2Z3200C16 8192MB DIMM DDR4 3200MT/s        | 4         | 0.42%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s           | 4         | 0.42%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                         | 3         | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                     | 3         | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR2                              | 3         | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR3                           | 3         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 380       | 47.8%   |
| DDR3    | 267       | 33.58%  |
| LPDDR4  | 40        | 5.03%   |
| DDR2    | 33        | 4.15%   |
| LPDDR3  | 24        | 3.02%   |
| SDRAM   | 21        | 2.64%   |
| Unknown | 15        | 1.89%   |
| DDR     | 9         | 1.13%   |
| DRAM    | 3         | 0.38%   |
| DDR5    | 3         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 419       | 52.84%  |
| DIMM         | 305       | 38.46%  |
| Row Of Chips | 55        | 6.94%   |
| Chip         | 10        | 1.26%   |
| Unknown      | 3         | 0.38%   |
| FB-DIMM      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 326       | 38.31%  |
| 4096    | 213       | 25.03%  |
| 16384   | 147       | 17.27%  |
| 2048    | 115       | 13.51%  |
| 1024    | 26        | 3.06%   |
| 32768   | 18        | 2.12%   |
| 512     | 5         | 0.59%   |
| Unknown | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 168       | 19.79%  |
| 2667    | 105       | 12.37%  |
| 3200    | 93        | 10.95%  |
| 2400    | 65        | 7.66%   |
| 2133    | 61        | 7.18%   |
| 1333    | 47        | 5.54%   |
| 3600    | 41        | 4.83%   |
| 667     | 26        | 3.06%   |
| 1334    | 24        | 2.83%   |
| 4267    | 21        | 2.47%   |
| 1867    | 19        | 2.24%   |
| 3466    | 17        | 2%      |
| Unknown | 17        | 2%      |
| 800     | 16        | 1.88%   |
| 3400    | 10        | 1.18%   |
| 3000    | 9         | 1.06%   |
| 1067    | 9         | 1.06%   |
| 1066    | 9         | 1.06%   |
| 4266    | 8         | 0.94%   |
| 3266    | 7         | 0.82%   |
| 2666    | 7         | 0.82%   |
| 1800    | 6         | 0.71%   |
| 3733    | 5         | 0.59%   |
| 1866    | 5         | 0.59%   |
| 4800    | 4         | 0.47%   |
| 4199    | 4         | 0.47%   |
| 3800    | 4         | 0.47%   |
| 2933    | 4         | 0.47%   |
| 2747    | 4         | 0.47%   |
| 8400    | 3         | 0.35%   |
| 49926   | 2         | 0.24%   |
| 3151    | 2         | 0.24%   |
| 3100    | 2         | 0.24%   |
| 2048    | 2         | 0.24%   |
| 2000    | 2         | 0.24%   |
| 975     | 2         | 0.24%   |
| 6400    | 1         | 0.12%   |
| 4333    | 1         | 0.12%   |
| 3866    | 1         | 0.12%   |
| 3666    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 37.5%   |
| Samsung Electronics | 5         | 20.83%  |
| Brother Industries  | 5         | 20.83%  |
| Canon               | 3         | 12.5%   |
| Seiko Epson         | 1         | 4.17%   |
| Oki Data            | 1         | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 2         | 8.33%   |
| HP LaserJet 1020                     | 2         | 8.33%   |
| Seiko Epson XP-4100 Series           | 1         | 4.17%   |
| Samsung SCX-3200 Series              | 1         | 4.17%   |
| Samsung M2070 Series                 | 1         | 4.17%   |
| Samsung Color Laser Printer          | 1         | 4.17%   |
| Oki Data USB Device                  | 1         | 4.17%   |
| HP OfficeJet Pro 8730                | 1         | 4.17%   |
| HP OfficeJet G55                     | 1         | 4.17%   |
| HP LaserJet P2035                    | 1         | 4.17%   |
| HP ENVY 4520 series                  | 1         | 4.17%   |
| HP DeskJet 5650c                     | 1         | 4.17%   |
| HP Deskjet 3050 J610 series          | 1         | 4.17%   |
| HP DeskJet 2130 series               | 1         | 4.17%   |
| Canon LiDE 300                       | 1         | 4.17%   |
| Canon LBP7010C/7018C                 | 1         | 4.17%   |
| Canon LBP6200                        | 1         | 4.17%   |
| Brother QL-500 label printer         | 1         | 4.17%   |
| Brother HL-2270DW Laser Printer      | 1         | 4.17%   |
| Brother HL-2130 series               | 1         | 4.17%   |
| Brother DCP-7055W                    | 1         | 4.17%   |
| Brother DCP-7040                     | 1         | 4.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 83.33%  |
| Hewlett-Packard | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP ScanJet 2200c                       | 1         | 16.67%  |
| Canon CanoScan LiDE 700F               | 1         | 16.67%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 16.67%  |
| Canon CanoScan LiDE 210                | 1         | 16.67%  |
| Canon CanoScan LiDE 120                | 1         | 16.67%  |
| Canon CanoScan LiDE 100                | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 206       | 24.35%  |
| Microdia                               | 86        | 10.17%  |
| IMC Networks                           | 68        | 8.04%   |
| Logitech                               | 66        | 7.8%    |
| Acer                                   | 64        | 7.57%   |
| Realtek Semiconductor                  | 54        | 6.38%   |
| Sunplus Innovation Technology          | 41        | 4.85%   |
| Cheng Uei Precision Industry (Foxlink) | 34        | 4.02%   |
| Apple                                  | 32        | 3.78%   |
| Lite-On Technology                     | 28        | 3.31%   |
| Quanta                                 | 26        | 3.07%   |
| Syntek                                 | 20        | 2.36%   |
| Suyin                                  | 19        | 2.25%   |
| Samsung Electronics                    | 11        | 1.3%    |
| Ricoh                                  | 10        | 1.18%   |
| Microsoft                              | 8         | 0.95%   |
| Lenovo                                 | 8         | 0.95%   |
| ALi                                    | 6         | 0.71%   |
| Alcor Micro                            | 6         | 0.71%   |
| Luxvisions Innotech Limited            | 5         | 0.59%   |
| Creative Technology                    | 5         | 0.59%   |
| Z-Star Microelectronics                | 4         | 0.47%   |
| Silicon Motion                         | 4         | 0.47%   |
| Primax Electronics                     | 4         | 0.47%   |
| Unknown                                | 3         | 0.35%   |
| Generalplus Technology                 | 3         | 0.35%   |
| Trust                                  | 2         | 0.24%   |
| Sunplus Technology                     | 2         | 0.24%   |
| Importek                               | 2         | 0.24%   |
| DigiTech                               | 2         | 0.24%   |
| ARC International                      | 2         | 0.24%   |
| Valve Software                         | 1         | 0.12%   |
| SunplusIT                              | 1         | 0.12%   |
| Sony                                   | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| Philips (or NXP)                       | 1         | 0.12%   |
| Novatek Microelectronics               | 1         | 0.12%   |
| Linux Foundation                       | 1         | 0.12%   |
| LG Electronics                         | 1         | 0.12%   |
| Intel                                  | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 44        | 5.13%   |
| Microdia Integrated_Webcam_HD                                            | 40        | 4.67%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 23        | 2.68%   |
| IMC Networks Integrated Camera                                           | 21        | 2.45%   |
| Chicony HD Webcam                                                        | 20        | 2.33%   |
| Realtek Integrated_Webcam_HD                                             | 19        | 2.22%   |
| Acer Integrated Camera                                                   | 17        | 1.98%   |
| Syntek Integrated Camera                                                 | 14        | 1.63%   |
| Logitech Webcam C270                                                     | 13        | 1.52%   |
| Chicony HP HD Camera                                                     | 13        | 1.52%   |
| Apple iPhone5/5C/5S/6                                                    | 12        | 1.4%    |
| Acer Lenovo EasyCamera                                                   | 12        | 1.4%    |
| Sunplus HD WebCam                                                        | 11        | 1.28%   |
| Samsung Galaxy A5 (MTP)                                                  | 11        | 1.28%   |
| Logitech HD Pro Webcam C920                                              | 11        | 1.28%   |
| Logitech C922 Pro Stream Webcam                                          | 10        | 1.17%   |
| Sunplus Integrated_Webcam_HD                                             | 9         | 1.05%   |
| Lite-On HP HD Webcam                                                     | 9         | 1.05%   |
| Lite-On HP HD Camera                                                     | 9         | 1.05%   |
| Quanta HP HD Camera                                                      | 8         | 0.93%   |
| Chicony HP HD Webcam                                                     | 8         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 8         | 0.93%   |
| Apple Built-in iSight                                                    | 8         | 0.93%   |
| Acer SunplusIT Integrated Camera                                         | 8         | 0.93%   |
| Realtek USB Camera                                                       | 7         | 0.82%   |
| Lite-On Integrated Camera                                                | 7         | 0.82%   |
| Chicony HP Wide Vision HD Camera                                         | 7         | 0.82%   |
| Chicony HP Truevision HD                                                 | 7         | 0.82%   |
| Chicony HP HD Webcam [Fixed]                                             | 7         | 0.82%   |
| Acer EasyCamera                                                          | 7         | 0.82%   |
| Syntek Lenovo EasyCamera                                                 | 6         | 0.7%    |
| Chicony USB2.0 HD UVC WebCam                                             | 6         | 0.7%    |
| Chicony USB2.0 Camera                                                    | 6         | 0.7%    |
| Chicony HD User Facing                                                   | 6         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 6         | 0.7%    |
| Realtek USB2.0 VGA UVC WebCam                                            | 5         | 0.58%   |
| Realtek USB2.0 HD UVC WebCam                                             | 5         | 0.58%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 5         | 0.58%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 5         | 0.58%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 5         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 97        | 44.91%  |
| Synaptics                  | 54        | 25%     |
| Shenzhen Goodix Technology | 24        | 11.11%  |
| AuthenTec                  | 11        | 5.09%   |
| Upek                       | 10        | 4.63%   |
| Elan Microelectronics      | 10        | 4.63%   |
| STMicroelectronics         | 6         | 2.78%   |
| LighTuning Technology      | 4         | 1.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 15.28%  |
| Unknown                                                                    | 16        | 7.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 6.02%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 6.02%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 4.17%   |
| Validity Sensors VFS491                                                    | 8         | 3.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 3.7%    |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 3.7%    |
| Elan ELAN:Fingerprint                                                      | 8         | 3.7%    |
| Validity Sensors Synaptics WBDI                                            | 7         | 3.24%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.78%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 2.78%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.78%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.31%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 2.31%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.31%   |
| AuthenTec AES2810                                                          | 5         | 2.31%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 2.31%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.85%   |
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 1.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.39%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.39%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.39%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.93%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.93%   |
| Synaptics  WBDI                                                            | 2         | 0.93%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.93%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.93%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.93%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.46%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.46%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.46%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.46%   |
| Synaptics WBDI Device                                                      | 1         | 0.46%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.46%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.46%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.46%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.46%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 49        | 44.55%  |
| Alcor Micro           | 41        | 37.27%  |
| O2 Micro              | 8         | 7.27%   |
| Upek                  | 4         | 3.64%   |
| Lenovo                | 4         | 3.64%   |
| Yubico.com            | 1         | 0.91%   |
| Hewlett-Packard       | 1         | 0.91%   |
| Gemalto (was Gemplus) | 1         | 0.91%   |
| Cherry                | 1         | 0.91%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 39        | 35.45%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 15.45%  |
| Broadcom 58200                                                               | 12        | 10.91%  |
| Broadcom 5880                                                                | 11        | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 7.27%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 6.36%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.64%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 3.64%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.82%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.91%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.91%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.91%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.91%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.91%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.91%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1061      | 66.52%  |
| 1     | 415       | 26.02%  |
| 2     | 100       | 6.27%   |
| 3     | 13        | 0.82%   |
| 4     | 5         | 0.31%   |
| 7     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 215       | 32.72%  |
| Graphics card            | 117       | 17.81%  |
| Chipcard                 | 97        | 14.76%  |
| Net/wireless             | 56        | 8.52%   |
| Multimedia controller    | 37        | 5.63%   |
| Communication controller | 35        | 5.33%   |
| Unassigned class         | 22        | 3.35%   |
| Camera                   | 18        | 2.74%   |
| Bluetooth                | 18        | 2.74%   |
| Sound                    | 13        | 1.98%   |
| Card reader              | 10        | 1.52%   |
| Net/ethernet             | 5         | 0.76%   |
| Storage                  | 2         | 0.3%    |
| Network                  | 2         | 0.3%    |
| Modem                    | 2         | 0.3%    |
| Flash memory             | 2         | 0.3%    |
| Storage/raid             | 1         | 0.15%   |
| Storage/nvme             | 1         | 0.15%   |
| Storage/ide              | 1         | 0.15%   |
| Storage/ata              | 1         | 0.15%   |
| Firewire controller      | 1         | 0.15%   |
| Dvb card                 | 1         | 0.15%   |

