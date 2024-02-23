Linux in Romania - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Romania.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Romania/Desktop/README.md) and [notebooks](/Location/Romania/Notebook/README.md).

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

Total: 2976

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Strix G634JZ_G634JZ     | Notebook    | [4b8399084a](https://linux-hardware.org/?probe=4b8399084a) | Feb 01, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [f0bd42b414](https://linux-hardware.org/?probe=f0bd42b414) | Feb 01, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [84c37d0192](https://linux-hardware.org/?probe=84c37d0192) | Feb 01, 2024 |
| HP            | Elite x2 1012 G1            | Notebook    | [44bbb3b748](https://linux-hardware.org/?probe=44bbb3b748) | Jan 31, 2024 |
| ASUSTek       | B85M-K                      | Desktop     | [3058093889](https://linux-hardware.org/?probe=3058093889) | Jan 31, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [16922386a7](https://linux-hardware.org/?probe=16922386a7) | Jan 31, 2024 |
| HP            | 1495                        | Desktop     | [a2017adb28](https://linux-hardware.org/?probe=a2017adb28) | Jan 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [028ce3b254](https://linux-hardware.org/?probe=028ce3b254) | Jan 29, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [91fddd3173](https://linux-hardware.org/?probe=91fddd3173) | Jan 28, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [f05cba633f](https://linux-hardware.org/?probe=f05cba633f) | Jan 28, 2024 |
| Gateway       | DS10G                       | Desktop     | [869339de12](https://linux-hardware.org/?probe=869339de12) | Jan 28, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0937d9ebea](https://linux-hardware.org/?probe=0937d9ebea) | Jan 27, 2024 |
| ASUSTek       | N551JX                      | Notebook    | [6a0be842aa](https://linux-hardware.org/?probe=6a0be842aa) | Jan 27, 2024 |
| Dell          | Inspiron N5040              | Notebook    | [7cd09c7dde](https://linux-hardware.org/?probe=7cd09c7dde) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [81338699ce](https://linux-hardware.org/?probe=81338699ce) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [9f021a2102](https://linux-hardware.org/?probe=9f021a2102) | Jan 25, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [d94fb0b47b](https://linux-hardware.org/?probe=d94fb0b47b) | Jan 24, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [4b9301ae7f](https://linux-hardware.org/?probe=4b9301ae7f) | Jan 24, 2024 |
| Acer          | Aspire A315-35              | Notebook    | [40bb0f1f4d](https://linux-hardware.org/?probe=40bb0f1f4d) | Jan 24, 2024 |
| Alienware     | 07W25T A01                  | Desktop     | [538d2e2b5f](https://linux-hardware.org/?probe=538d2e2b5f) | Jan 24, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME E... | Desktop     | [299dd0311b](https://linux-hardware.org/?probe=299dd0311b) | Jan 24, 2024 |
| Dell          | Inspiron N5040              | Notebook    | [79bca2224b](https://linux-hardware.org/?probe=79bca2224b) | Jan 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [318e16ffb6](https://linux-hardware.org/?probe=318e16ffb6) | Jan 22, 2024 |
| Alienware     | 07W25T A01                  | Desktop     | [2a7a6fd405](https://linux-hardware.org/?probe=2a7a6fd405) | Jan 22, 2024 |
| AZW           | GTR V21                     | Desktop     | [dbc8e08754](https://linux-hardware.org/?probe=dbc8e08754) | Jan 21, 2024 |
| Acer          | Aspire SW3-016              | Notebook    | [01ee7724e0](https://linux-hardware.org/?probe=01ee7724e0) | Jan 21, 2024 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [41c285445b](https://linux-hardware.org/?probe=41c285445b) | Jan 21, 2024 |
| Acer          | Aspire A315-35              | Notebook    | [baff1b7c03](https://linux-hardware.org/?probe=baff1b7c03) | Jan 20, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [97f56eac35](https://linux-hardware.org/?probe=97f56eac35) | Jan 19, 2024 |
| Acer          | Aspire A315-35              | Notebook    | [dafaf99dd0](https://linux-hardware.org/?probe=dafaf99dd0) | Jan 19, 2024 |
| Dell          | Latitude E6230              | Notebook    | [421a0c04cf](https://linux-hardware.org/?probe=421a0c04cf) | Jan 19, 2024 |
| Dell          | Latitude E6230              | Notebook    | [c5602b88c7](https://linux-hardware.org/?probe=c5602b88c7) | Jan 18, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [f830d5e5f7](https://linux-hardware.org/?probe=f830d5e5f7) | Jan 18, 2024 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [ca16a763c8](https://linux-hardware.org/?probe=ca16a763c8) | Jan 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [5ea527f9cc](https://linux-hardware.org/?probe=5ea527f9cc) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [3c8a40dcc2](https://linux-hardware.org/?probe=3c8a40dcc2) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [4a57c65ec3](https://linux-hardware.org/?probe=4a57c65ec3) | Jan 15, 2024 |
| ASRock        | X470 Taichi                 | Desktop     | [85ada6019c](https://linux-hardware.org/?probe=85ada6019c) | Jan 15, 2024 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [268e37f04e](https://linux-hardware.org/?probe=268e37f04e) | Jan 14, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [1ece67bdd1](https://linux-hardware.org/?probe=1ece67bdd1) | Jan 12, 2024 |
| Lenovo        | ThinkPad T440 20B7S1WJ00    | Notebook    | [215c45abef](https://linux-hardware.org/?probe=215c45abef) | Jan 11, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a8ddb87bfe](https://linux-hardware.org/?probe=a8ddb87bfe) | Jan 11, 2024 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [9960b657ec](https://linux-hardware.org/?probe=9960b657ec) | Jan 11, 2024 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [d1041fde50](https://linux-hardware.org/?probe=d1041fde50) | Jan 11, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [a4897703b1](https://linux-hardware.org/?probe=a4897703b1) | Jan 10, 2024 |
| Dell          | 072T6D A05                  | Server      | [081a7baae9](https://linux-hardware.org/?probe=081a7baae9) | Jan 10, 2024 |
| ASUSTek       | G10DK                       | Desktop     | [7339bf1ed8](https://linux-hardware.org/?probe=7339bf1ed8) | Jan 09, 2024 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [931f2e4a0e](https://linux-hardware.org/?probe=931f2e4a0e) | Jan 08, 2024 |
| Complet       | MY8315XX                    | Notebook    | [cb08af3409](https://linux-hardware.org/?probe=cb08af3409) | Jan 07, 2024 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [61066d4150](https://linux-hardware.org/?probe=61066d4150) | Jan 07, 2024 |
| Lenovo        | ThinkPad T480s 20L8S0R30... | Notebook    | [9cfe296019](https://linux-hardware.org/?probe=9cfe296019) | Jan 07, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [1db7814b85](https://linux-hardware.org/?probe=1db7814b85) | Jan 07, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7f25d85205](https://linux-hardware.org/?probe=7f25d85205) | Jan 07, 2024 |
| Sony          | SVF1521H1EW                 | Notebook    | [1939183179](https://linux-hardware.org/?probe=1939183179) | Jan 07, 2024 |
| Sony          | SVF1521H1EW                 | Notebook    | [f73763fd0c](https://linux-hardware.org/?probe=f73763fd0c) | Jan 06, 2024 |
| Lenovo        | ThinkPad T410 2518FMG       | Notebook    | [d2e50fca98](https://linux-hardware.org/?probe=d2e50fca98) | Jan 03, 2024 |
| Lenovo        | ThinkPad T410 2518FMG       | Notebook    | [e1d4b75f1c](https://linux-hardware.org/?probe=e1d4b75f1c) | Jan 03, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [d99098989d](https://linux-hardware.org/?probe=d99098989d) | Jan 03, 2024 |
| Gigabyte      | MH610AT-SI                  | Desktop     | [1b75d28eb3](https://linux-hardware.org/?probe=1b75d28eb3) | Jan 03, 2024 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [9711c69823](https://linux-hardware.org/?probe=9711c69823) | Jan 02, 2024 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [018238aa79](https://linux-hardware.org/?probe=018238aa79) | Jan 01, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [28ad8513b4](https://linux-hardware.org/?probe=28ad8513b4) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8f3ab867ea](https://linux-hardware.org/?probe=8f3ab867ea) | Dec 30, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [29e0740b9d](https://linux-hardware.org/?probe=29e0740b9d) | Dec 29, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e260b20e5d](https://linux-hardware.org/?probe=e260b20e5d) | Dec 28, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [050f6ca09e](https://linux-hardware.org/?probe=050f6ca09e) | Dec 28, 2023 |
| Lenovo        | No DPK                      | All in one  | [e47b692f60](https://linux-hardware.org/?probe=e47b692f60) | Dec 28, 2023 |
| Lenovo        | No DPK                      | All in one  | [961bd36b3d](https://linux-hardware.org/?probe=961bd36b3d) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [58080b01c8](https://linux-hardware.org/?probe=58080b01c8) | Dec 27, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [fcda025864](https://linux-hardware.org/?probe=fcda025864) | Dec 26, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [a3c4869087](https://linux-hardware.org/?probe=a3c4869087) | Dec 24, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [e53cfaf52c](https://linux-hardware.org/?probe=e53cfaf52c) | Dec 24, 2023 |
| Acer          | Aspire 5742Z                | Notebook    | [ddf1553f4b](https://linux-hardware.org/?probe=ddf1553f4b) | Dec 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [6406b552c4](https://linux-hardware.org/?probe=6406b552c4) | Dec 23, 2023 |
| Allview       | Allbook I/1                 | Notebook    | [960dfde4cd](https://linux-hardware.org/?probe=960dfde4cd) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [9e521ad3e9](https://linux-hardware.org/?probe=9e521ad3e9) | Dec 22, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [52af26d8a1](https://linux-hardware.org/?probe=52af26d8a1) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [64ec373e84](https://linux-hardware.org/?probe=64ec373e84) | Dec 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [aa11af3235](https://linux-hardware.org/?probe=aa11af3235) | Dec 20, 2023 |
| MSI           | B85-G43                     | Desktop     | [2c855d2376](https://linux-hardware.org/?probe=2c855d2376) | Dec 19, 2023 |
| Lenovo        | Legion 5 15IMH6 82NL        | Notebook    | [e54630a5d8](https://linux-hardware.org/?probe=e54630a5d8) | Dec 18, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [baf5b47a47](https://linux-hardware.org/?probe=baf5b47a47) | Dec 18, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [6d81343411](https://linux-hardware.org/?probe=6d81343411) | Dec 18, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [f93e198dd4](https://linux-hardware.org/?probe=f93e198dd4) | Dec 18, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [a6ae535887](https://linux-hardware.org/?probe=a6ae535887) | Dec 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS19500     | Notebook    | [7067fb02ed](https://linux-hardware.org/?probe=7067fb02ed) | Dec 18, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [8507460974](https://linux-hardware.org/?probe=8507460974) | Dec 18, 2023 |
| PC Special... | MP 17 Recoil Master         | Notebook    | [f199dc6e36](https://linux-hardware.org/?probe=f199dc6e36) | Dec 17, 2023 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [ac7985ff69](https://linux-hardware.org/?probe=ac7985ff69) | Dec 17, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [47747d42ef](https://linux-hardware.org/?probe=47747d42ef) | Dec 17, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6920e9d7c2](https://linux-hardware.org/?probe=6920e9d7c2) | Dec 17, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [9c68457da9](https://linux-hardware.org/?probe=9c68457da9) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [6d72d7366b](https://linux-hardware.org/?probe=6d72d7366b) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [d8a98a209a](https://linux-hardware.org/?probe=d8a98a209a) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c839de638b](https://linux-hardware.org/?probe=c839de638b) | Dec 15, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [f7b0d4b746](https://linux-hardware.org/?probe=f7b0d4b746) | Dec 14, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [cdde8c0b3f](https://linux-hardware.org/?probe=cdde8c0b3f) | Dec 13, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [0ffc45c096](https://linux-hardware.org/?probe=0ffc45c096) | Dec 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [230f41f6b5](https://linux-hardware.org/?probe=230f41f6b5) | Dec 12, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [0ad101e0f2](https://linux-hardware.org/?probe=0ad101e0f2) | Dec 12, 2023 |
| HP            | Presario CQ58               | Notebook    | [b23d694ab4](https://linux-hardware.org/?probe=b23d694ab4) | Dec 11, 2023 |
| Dell          | Precision 5530              | Notebook    | [eee9114e4b](https://linux-hardware.org/?probe=eee9114e4b) | Dec 10, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [48fffc72b6](https://linux-hardware.org/?probe=48fffc72b6) | Dec 10, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [4c20f6a826](https://linux-hardware.org/?probe=4c20f6a826) | Dec 10, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [e2c932c285](https://linux-hardware.org/?probe=e2c932c285) | Dec 09, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [baa82e571f](https://linux-hardware.org/?probe=baa82e571f) | Dec 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [551b412a34](https://linux-hardware.org/?probe=551b412a34) | Dec 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [587ff35c26](https://linux-hardware.org/?probe=587ff35c26) | Dec 08, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [0257ed619f](https://linux-hardware.org/?probe=0257ed619f) | Dec 08, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [5775bf1613](https://linux-hardware.org/?probe=5775bf1613) | Dec 08, 2023 |
| Dell          | 0GM819                      | Desktop     | [5c9ffb0977](https://linux-hardware.org/?probe=5c9ffb0977) | Dec 07, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [5f96473345](https://linux-hardware.org/?probe=5f96473345) | Dec 07, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [ba354037ff](https://linux-hardware.org/?probe=ba354037ff) | Dec 07, 2023 |
| Acer          | TravelMate P645-S           | Notebook    | [e44f06b326](https://linux-hardware.org/?probe=e44f06b326) | Dec 07, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [46bc5ee727](https://linux-hardware.org/?probe=46bc5ee727) | Dec 06, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [ad97d6f3c6](https://linux-hardware.org/?probe=ad97d6f3c6) | Dec 05, 2023 |
| HP            | 550                         | Notebook    | [a3dc2d4062](https://linux-hardware.org/?probe=a3dc2d4062) | Dec 05, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [93675534e1](https://linux-hardware.org/?probe=93675534e1) | Dec 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [8463f6c28f](https://linux-hardware.org/?probe=8463f6c28f) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [f8a528e1d6](https://linux-hardware.org/?probe=f8a528e1d6) | Dec 03, 2023 |
| Acer          | Aspire 8951G                | Notebook    | [f98b449dba](https://linux-hardware.org/?probe=f98b449dba) | Dec 03, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [20a5a6a137](https://linux-hardware.org/?probe=20a5a6a137) | Dec 03, 2023 |
| HP            | 8299                        | Desktop     | [fb5b226159](https://linux-hardware.org/?probe=fb5b226159) | Dec 02, 2023 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | Notebook    | [49c0a7990e](https://linux-hardware.org/?probe=49c0a7990e) | Dec 01, 2023 |
| HP            | 843B                        | Desktop     | [5a69492f49](https://linux-hardware.org/?probe=5a69492f49) | Nov 30, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [10c0db94d1](https://linux-hardware.org/?probe=10c0db94d1) | Nov 29, 2023 |
| Dell          | Inspiron N5030              | Notebook    | [cf3da3211d](https://linux-hardware.org/?probe=cf3da3211d) | Nov 28, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [60c7835d8c](https://linux-hardware.org/?probe=60c7835d8c) | Nov 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [5fabcb33c4](https://linux-hardware.org/?probe=5fabcb33c4) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [0ddcbc9eb9](https://linux-hardware.org/?probe=0ddcbc9eb9) | Nov 27, 2023 |
| Lenovo        | 15ARE05 81W4                | Notebook    | [c3763733da](https://linux-hardware.org/?probe=c3763733da) | Nov 27, 2023 |
| Lenovo        | 15ARE05 81W4                | Notebook    | [4fa9ab8a76](https://linux-hardware.org/?probe=4fa9ab8a76) | Nov 27, 2023 |
| Dell          | 0YP806 A01                  | Desktop     | [078d014e70](https://linux-hardware.org/?probe=078d014e70) | Nov 26, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [6dcba67a12](https://linux-hardware.org/?probe=6dcba67a12) | Nov 26, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [c887e86fe4](https://linux-hardware.org/?probe=c887e86fe4) | Nov 25, 2023 |
| Dell          | Latitude 7400               | Notebook    | [86a9de8212](https://linux-hardware.org/?probe=86a9de8212) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [7478563980](https://linux-hardware.org/?probe=7478563980) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a8b99ab7f3](https://linux-hardware.org/?probe=a8b99ab7f3) | Nov 23, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [6115c9c76e](https://linux-hardware.org/?probe=6115c9c76e) | Nov 23, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [d71110004d](https://linux-hardware.org/?probe=d71110004d) | Nov 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [0454a567a0](https://linux-hardware.org/?probe=0454a567a0) | Nov 21, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [2995eb87c1](https://linux-hardware.org/?probe=2995eb87c1) | Nov 21, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [78dac027a1](https://linux-hardware.org/?probe=78dac027a1) | Nov 19, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [cc9d93b28f](https://linux-hardware.org/?probe=cc9d93b28f) | Nov 19, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [f5c9812962](https://linux-hardware.org/?probe=f5c9812962) | Nov 19, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [6e4144386d](https://linux-hardware.org/?probe=6e4144386d) | Nov 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [55df37c5d0](https://linux-hardware.org/?probe=55df37c5d0) | Nov 17, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [4cb5f6eae9](https://linux-hardware.org/?probe=4cb5f6eae9) | Nov 17, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [753bf22a5f](https://linux-hardware.org/?probe=753bf22a5f) | Nov 17, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [391e71ffae](https://linux-hardware.org/?probe=391e71ffae) | Nov 17, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [49ea9a3b35](https://linux-hardware.org/?probe=49ea9a3b35) | Nov 15, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [ffc320e32c](https://linux-hardware.org/?probe=ffc320e32c) | Nov 15, 2023 |
| Dell          | Latitude 5521               | Notebook    | [2cd2e72764](https://linux-hardware.org/?probe=2cd2e72764) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [adaf0ff475](https://linux-hardware.org/?probe=adaf0ff475) | Nov 15, 2023 |
| Lenovo        | IdeaPad Slim 5 14IAH8 83... | Notebook    | [e33ce14e30](https://linux-hardware.org/?probe=e33ce14e30) | Nov 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [da50e3550f](https://linux-hardware.org/?probe=da50e3550f) | Nov 14, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [e8803a2d63](https://linux-hardware.org/?probe=e8803a2d63) | Nov 13, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [b7788fefa0](https://linux-hardware.org/?probe=b7788fefa0) | Nov 13, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [de08a9140e](https://linux-hardware.org/?probe=de08a9140e) | Nov 12, 2023 |
| Allview       | Allbook I/1                 | Notebook    | [2da284e5a6](https://linux-hardware.org/?probe=2da284e5a6) | Nov 11, 2023 |
| Jumper        | EZbook                      | Notebook    | [f7f10f7817](https://linux-hardware.org/?probe=f7f10f7817) | Nov 11, 2023 |
| Allview       | Allbook I/1                 | Notebook    | [4ea9038785](https://linux-hardware.org/?probe=4ea9038785) | Nov 10, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [0fcd993247](https://linux-hardware.org/?probe=0fcd993247) | Nov 10, 2023 |
| MSI           | X299 RAIDER                 | Desktop     | [3f714787ff](https://linux-hardware.org/?probe=3f714787ff) | Nov 09, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [ea4a2b9084](https://linux-hardware.org/?probe=ea4a2b9084) | Nov 07, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [0d04acd22d](https://linux-hardware.org/?probe=0d04acd22d) | Nov 07, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [61fdbe9ec2](https://linux-hardware.org/?probe=61fdbe9ec2) | Nov 07, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [b64eb3798d](https://linux-hardware.org/?probe=b64eb3798d) | Nov 07, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [982bf3ea4c](https://linux-hardware.org/?probe=982bf3ea4c) | Nov 07, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [b8f226f7f0](https://linux-hardware.org/?probe=b8f226f7f0) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [ce00056643](https://linux-hardware.org/?probe=ce00056643) | Nov 07, 2023 |
| ASUSTek       | P30AD                       | Desktop     | [63322c386f](https://linux-hardware.org/?probe=63322c386f) | Nov 05, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [f8a30d78d3](https://linux-hardware.org/?probe=f8a30d78d3) | Nov 04, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [1e3cdf0bf2](https://linux-hardware.org/?probe=1e3cdf0bf2) | Nov 04, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [48103e7e91](https://linux-hardware.org/?probe=48103e7e91) | Nov 03, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [b0d77e36b1](https://linux-hardware.org/?probe=b0d77e36b1) | Nov 03, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [0af35bd53b](https://linux-hardware.org/?probe=0af35bd53b) | Nov 02, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [32a001fb07](https://linux-hardware.org/?probe=32a001fb07) | Nov 02, 2023 |
| Dell          | Latitude 7370               | Notebook    | [b16724db59](https://linux-hardware.org/?probe=b16724db59) | Nov 01, 2023 |
| Google        | Akemi                       | Notebook    | [75082d5cf9](https://linux-hardware.org/?probe=75082d5cf9) | Nov 01, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [d4630a5c8b](https://linux-hardware.org/?probe=d4630a5c8b) | Nov 01, 2023 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [64a6524677](https://linux-hardware.org/?probe=64a6524677) | Oct 31, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [c26ec81fab](https://linux-hardware.org/?probe=c26ec81fab) | Oct 31, 2023 |
| Intel         | X99                         | Desktop     | [426c412f62](https://linux-hardware.org/?probe=426c412f62) | Oct 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [941ca289ce](https://linux-hardware.org/?probe=941ca289ce) | Oct 30, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [4d9e5a7157](https://linux-hardware.org/?probe=4d9e5a7157) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9f0452aba6](https://linux-hardware.org/?probe=9f0452aba6) | Oct 29, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [01e0620386](https://linux-hardware.org/?probe=01e0620386) | Oct 29, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [8e871997f7](https://linux-hardware.org/?probe=8e871997f7) | Oct 29, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [f8e77bd53a](https://linux-hardware.org/?probe=f8e77bd53a) | Oct 28, 2023 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [a4bed1729d](https://linux-hardware.org/?probe=a4bed1729d) | Oct 28, 2023 |
| ASUSTek       | V241FA                      | All in one  | [92f8ffc191](https://linux-hardware.org/?probe=92f8ffc191) | Oct 27, 2023 |
| Intel         | DX79TO AAG28805-401         | Desktop     | [75e8f73b6a](https://linux-hardware.org/?probe=75e8f73b6a) | Oct 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e622e81e16](https://linux-hardware.org/?probe=e622e81e16) | Oct 24, 2023 |
| Lenovo        | ThinkPad T480 20L6S5FF0S    | Notebook    | [4a4fe99b2d](https://linux-hardware.org/?probe=4a4fe99b2d) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f45a5143fc](https://linux-hardware.org/?probe=f45a5143fc) | Oct 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [a7a49e3d3f](https://linux-hardware.org/?probe=a7a49e3d3f) | Oct 23, 2023 |
| ASUSTek       | ZenBook UX534FTC            | Notebook    | [a268a7a10e](https://linux-hardware.org/?probe=a268a7a10e) | Oct 22, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [ee15c1dbea](https://linux-hardware.org/?probe=ee15c1dbea) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [77fb62615e](https://linux-hardware.org/?probe=77fb62615e) | Oct 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [43f9375597](https://linux-hardware.org/?probe=43f9375597) | Oct 21, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [75f2f0b411](https://linux-hardware.org/?probe=75f2f0b411) | Oct 21, 2023 |
| HP            | 3397                        | Desktop     | [d826d02943](https://linux-hardware.org/?probe=d826d02943) | Oct 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [de8a8232ba](https://linux-hardware.org/?probe=de8a8232ba) | Oct 19, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [0f5885bc27](https://linux-hardware.org/?probe=0f5885bc27) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9f9777f778](https://linux-hardware.org/?probe=9f9777f778) | Oct 17, 2023 |
| Lenovo        | 15ARE05 81W4                | Notebook    | [dcb09acd04](https://linux-hardware.org/?probe=dcb09acd04) | Oct 17, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [c430358d6a](https://linux-hardware.org/?probe=c430358d6a) | Oct 17, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [b96d2e0be9](https://linux-hardware.org/?probe=b96d2e0be9) | Oct 16, 2023 |
| HP            | 2000                        | Notebook    | [c2669ff6cb](https://linux-hardware.org/?probe=c2669ff6cb) | Oct 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [471a6f3119](https://linux-hardware.org/?probe=471a6f3119) | Oct 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [f16973062f](https://linux-hardware.org/?probe=f16973062f) | Oct 15, 2023 |
| Dell          | 0V52N7 A00                  | Server      | [757c40f561](https://linux-hardware.org/?probe=757c40f561) | Oct 15, 2023 |
| Dell          | 0V52N7 A00                  | Server      | [8b00ca5242](https://linux-hardware.org/?probe=8b00ca5242) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [66a5a05425](https://linux-hardware.org/?probe=66a5a05425) | Oct 15, 2023 |
| Toshiba       | Satellite CL10-C-102        | Notebook    | [cdaab4e230](https://linux-hardware.org/?probe=cdaab4e230) | Oct 15, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [d2e0e9fc07](https://linux-hardware.org/?probe=d2e0e9fc07) | Oct 14, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [551ff39482](https://linux-hardware.org/?probe=551ff39482) | Oct 14, 2023 |
| Lenovo        | 3112 SDK0J40697 WIN 3305... | All in one  | [dec3f47001](https://linux-hardware.org/?probe=dec3f47001) | Oct 14, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [ca520343c8](https://linux-hardware.org/?probe=ca520343c8) | Oct 13, 2023 |
| Lenovo        | 15ARE05 81W4                | Notebook    | [c0066cda83](https://linux-hardware.org/?probe=c0066cda83) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [662b033cee](https://linux-hardware.org/?probe=662b033cee) | Oct 12, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [3069c746fd](https://linux-hardware.org/?probe=3069c746fd) | Oct 12, 2023 |
| HP            | 8437                        | Desktop     | [ac8d6773a3](https://linux-hardware.org/?probe=ac8d6773a3) | Oct 11, 2023 |
| libre-comp... | aml-s905x-cc                | Soc         | [13dd011d9b](https://linux-hardware.org/?probe=13dd011d9b) | Oct 10, 2023 |
| BESSTAR Te... | X400                        | Notebook    | [c955c44ef3](https://linux-hardware.org/?probe=c955c44ef3) | Oct 10, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [cb78c82e7a](https://linux-hardware.org/?probe=cb78c82e7a) | Oct 09, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [fa47449843](https://linux-hardware.org/?probe=fa47449843) | Oct 08, 2023 |
| HP            | 0A58h                       | Desktop     | [f55b84ff65](https://linux-hardware.org/?probe=f55b84ff65) | Oct 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5324f47bcf](https://linux-hardware.org/?probe=5324f47bcf) | Oct 07, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [cad844c720](https://linux-hardware.org/?probe=cad844c720) | Oct 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [60d5b8f4c0](https://linux-hardware.org/?probe=60d5b8f4c0) | Oct 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [99f8282319](https://linux-hardware.org/?probe=99f8282319) | Oct 06, 2023 |
| HP            | ProBook 6450b               | Notebook    | [f597cfe9d1](https://linux-hardware.org/?probe=f597cfe9d1) | Oct 05, 2023 |
| Google        | Magpie                      | Notebook    | [91fa583b13](https://linux-hardware.org/?probe=91fa583b13) | Oct 05, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [02ff66cc0c](https://linux-hardware.org/?probe=02ff66cc0c) | Oct 05, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [555d578f86](https://linux-hardware.org/?probe=555d578f86) | Oct 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [504010f96c](https://linux-hardware.org/?probe=504010f96c) | Oct 04, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [96c62ad87e](https://linux-hardware.org/?probe=96c62ad87e) | Oct 03, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [b6a9eaaec5](https://linux-hardware.org/?probe=b6a9eaaec5) | Oct 03, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [6bc4edfef5](https://linux-hardware.org/?probe=6bc4edfef5) | Oct 02, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [a9b3098036](https://linux-hardware.org/?probe=a9b3098036) | Oct 02, 2023 |
| Google        | Magpie                      | Notebook    | [32a7bba307](https://linux-hardware.org/?probe=32a7bba307) | Oct 01, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Toshiba       | Satellite C850-D4K          | Notebook    | [47d93b3030](https://linux-hardware.org/?probe=47d93b3030) | Oct 01, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [c8a525522f](https://linux-hardware.org/?probe=c8a525522f) | Sep 30, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [eab41d0848](https://linux-hardware.org/?probe=eab41d0848) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [9a749a1c41](https://linux-hardware.org/?probe=9a749a1c41) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [452cd2622a](https://linux-hardware.org/?probe=452cd2622a) | Sep 30, 2023 |
| WesternDig... | BBC 0001                    | Desktop     | [b31e10d01b](https://linux-hardware.org/?probe=b31e10d01b) | Sep 29, 2023 |
| WesternDig... | BBC 0001                    | Desktop     | [ba340393f7](https://linux-hardware.org/?probe=ba340393f7) | Sep 29, 2023 |
| HP            | 1496                        | Desktop     | [3867e7af58](https://linux-hardware.org/?probe=3867e7af58) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb4cde69b8](https://linux-hardware.org/?probe=fb4cde69b8) | Sep 28, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [7ab6fc6901](https://linux-hardware.org/?probe=7ab6fc6901) | Sep 27, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [d59518d612](https://linux-hardware.org/?probe=d59518d612) | Sep 25, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [a1e01ab80d](https://linux-hardware.org/?probe=a1e01ab80d) | Sep 25, 2023 |
| AZW           | GTR V01                     | Mini pc     | [9ea546d36c](https://linux-hardware.org/?probe=9ea546d36c) | Sep 22, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [65e95a03e9](https://linux-hardware.org/?probe=65e95a03e9) | Sep 22, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [34857762c0](https://linux-hardware.org/?probe=34857762c0) | Sep 21, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [45f00aaf92](https://linux-hardware.org/?probe=45f00aaf92) | Sep 21, 2023 |
| Dell          | Latitude 5420               | Notebook    | [c40b9df526](https://linux-hardware.org/?probe=c40b9df526) | Sep 21, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9caba9ee44](https://linux-hardware.org/?probe=9caba9ee44) | Sep 21, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [07431109a7](https://linux-hardware.org/?probe=07431109a7) | Sep 21, 2023 |
| ASUSTek       | B150M-C D3                  | Desktop     | [179a66ec43](https://linux-hardware.org/?probe=179a66ec43) | Sep 19, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [6ed76f72d7](https://linux-hardware.org/?probe=6ed76f72d7) | Sep 19, 2023 |
| HP            | 158B                        | Desktop     | [f8385c7d22](https://linux-hardware.org/?probe=f8385c7d22) | Sep 18, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [afbaf99497](https://linux-hardware.org/?probe=afbaf99497) | Sep 16, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [effa0104c0](https://linux-hardware.org/?probe=effa0104c0) | Sep 16, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [72ec01815f](https://linux-hardware.org/?probe=72ec01815f) | Sep 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [365a5e674f](https://linux-hardware.org/?probe=365a5e674f) | Sep 15, 2023 |
| HP            | 158B                        | Desktop     | [986f0c6ba1](https://linux-hardware.org/?probe=986f0c6ba1) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [eaa723190d](https://linux-hardware.org/?probe=eaa723190d) | Sep 15, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [356d6d3e13](https://linux-hardware.org/?probe=356d6d3e13) | Sep 15, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [7ae470ffa8](https://linux-hardware.org/?probe=7ae470ffa8) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [d27fa5404b](https://linux-hardware.org/?probe=d27fa5404b) | Sep 14, 2023 |
| HP            | 339A                        | Desktop     | [1b8a467d98](https://linux-hardware.org/?probe=1b8a467d98) | Sep 13, 2023 |
| Lenovo        | 3717 NO DPK                 | Desktop     | [13870a17b4](https://linux-hardware.org/?probe=13870a17b4) | Sep 13, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [ba05e7b3a7](https://linux-hardware.org/?probe=ba05e7b3a7) | Sep 12, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [78a9c8ba47](https://linux-hardware.org/?probe=78a9c8ba47) | Sep 12, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [a8f64806fe](https://linux-hardware.org/?probe=a8f64806fe) | Sep 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e1b135961f](https://linux-hardware.org/?probe=e1b135961f) | Sep 12, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [b1b59ca70c](https://linux-hardware.org/?probe=b1b59ca70c) | Sep 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1275709f08](https://linux-hardware.org/?probe=1275709f08) | Sep 09, 2023 |
| Acer          | EQ45LM                      | Desktop     | [015ea66c32](https://linux-hardware.org/?probe=015ea66c32) | Sep 09, 2023 |
| Acer          | EQ45LM                      | Desktop     | [22af76a0b6](https://linux-hardware.org/?probe=22af76a0b6) | Sep 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7263435dde](https://linux-hardware.org/?probe=7263435dde) | Sep 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [f66ec50e55](https://linux-hardware.org/?probe=f66ec50e55) | Sep 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [9a31047350](https://linux-hardware.org/?probe=9a31047350) | Sep 05, 2023 |
| Acer          | Nitro AN515-41              | Notebook    | [8d55fa5be4](https://linux-hardware.org/?probe=8d55fa5be4) | Sep 03, 2023 |
| HP            | 15                          | Notebook    | [db9d960b39](https://linux-hardware.org/?probe=db9d960b39) | Sep 03, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [66df65e0f0](https://linux-hardware.org/?probe=66df65e0f0) | Sep 02, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [d3c3b72e39](https://linux-hardware.org/?probe=d3c3b72e39) | Sep 01, 2023 |
| Acer          | TMP645-M                    | Notebook    | [17838ce9b0](https://linux-hardware.org/?probe=17838ce9b0) | Aug 30, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [ca4dd5a11e](https://linux-hardware.org/?probe=ca4dd5a11e) | Aug 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d036282290](https://linux-hardware.org/?probe=d036282290) | Aug 29, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [b866599fbc](https://linux-hardware.org/?probe=b866599fbc) | Aug 29, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [90b8d2cb66](https://linux-hardware.org/?probe=90b8d2cb66) | Aug 28, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [a8a97f9555](https://linux-hardware.org/?probe=a8a97f9555) | Aug 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8169effdbe](https://linux-hardware.org/?probe=8169effdbe) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [dd4626de1b](https://linux-hardware.org/?probe=dd4626de1b) | Aug 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [78a62eeefe](https://linux-hardware.org/?probe=78a62eeefe) | Aug 26, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [db9336b4db](https://linux-hardware.org/?probe=db9336b4db) | Aug 26, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [7aca2d97c0](https://linux-hardware.org/?probe=7aca2d97c0) | Aug 25, 2023 |
| Acer          | EQ45LM                      | Desktop     | [aa8ea529f7](https://linux-hardware.org/?probe=aa8ea529f7) | Aug 24, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [05eae6c877](https://linux-hardware.org/?probe=05eae6c877) | Aug 22, 2023 |
| ASRock        | 890GX Pro3                  | Desktop     | [c36b43c52a](https://linux-hardware.org/?probe=c36b43c52a) | Aug 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b3f1d927a1](https://linux-hardware.org/?probe=b3f1d927a1) | Aug 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d7b6d2a997](https://linux-hardware.org/?probe=d7b6d2a997) | Aug 21, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d7805c8232](https://linux-hardware.org/?probe=d7805c8232) | Aug 19, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [8946b925ea](https://linux-hardware.org/?probe=8946b925ea) | Aug 18, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [8478931432](https://linux-hardware.org/?probe=8478931432) | Aug 17, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [3fa65d407a](https://linux-hardware.org/?probe=3fa65d407a) | Aug 17, 2023 |
| HP            | Compaq 6710b (FG040EC#AB... | Notebook    | [a0cd8c1b40](https://linux-hardware.org/?probe=a0cd8c1b40) | Aug 16, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [8bc67959d1](https://linux-hardware.org/?probe=8bc67959d1) | Aug 16, 2023 |
| ASUSTek       | GL552JX                     | Notebook    | [9594a231bd](https://linux-hardware.org/?probe=9594a231bd) | Aug 16, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [f0d90b715d](https://linux-hardware.org/?probe=f0d90b715d) | Aug 15, 2023 |
| Gigabyte      | Z270M-D3H-CF                | Desktop     | [74d96ec17a](https://linux-hardware.org/?probe=74d96ec17a) | Aug 15, 2023 |
| Gigabyte      | Z270M-D3H-CF                | Desktop     | [8e4f3bf14e](https://linux-hardware.org/?probe=8e4f3bf14e) | Aug 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [18d3d9a7c1](https://linux-hardware.org/?probe=18d3d9a7c1) | Aug 14, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [f0f6b13bf3](https://linux-hardware.org/?probe=f0f6b13bf3) | Aug 13, 2023 |
| Allview       | Allbook H                   | Notebook    | [1a8e5e7f8f](https://linux-hardware.org/?probe=1a8e5e7f8f) | Aug 13, 2023 |
| Intel         | NUC7i5BNB J31144-303        | Mini pc     | [144f77980e](https://linux-hardware.org/?probe=144f77980e) | Aug 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [7fd3205fde](https://linux-hardware.org/?probe=7fd3205fde) | Aug 11, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [ce593ff6c7](https://linux-hardware.org/?probe=ce593ff6c7) | Aug 07, 2023 |
| Acer          | AO756                       | Notebook    | [60475c9d52](https://linux-hardware.org/?probe=60475c9d52) | Aug 06, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| WEIGO         | CDA-141AU                   | Notebook    | [35c705bd70](https://linux-hardware.org/?probe=35c705bd70) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [66d6565a06](https://linux-hardware.org/?probe=66d6565a06) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [70aa79986f](https://linux-hardware.org/?probe=70aa79986f) | Aug 05, 2023 |
| Acer          | EQ45LM                      | Desktop     | [b9be16315e](https://linux-hardware.org/?probe=b9be16315e) | Aug 05, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [cc0ea700cc](https://linux-hardware.org/?probe=cc0ea700cc) | Aug 04, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a7b2a3fcc](https://linux-hardware.org/?probe=0a7b2a3fcc) | Aug 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [9171e8e6b9](https://linux-hardware.org/?probe=9171e8e6b9) | Aug 03, 2023 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [c279d0ba16](https://linux-hardware.org/?probe=c279d0ba16) | Aug 02, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [8de1f944a7](https://linux-hardware.org/?probe=8de1f944a7) | Jul 30, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | Desktop     | [9cc0db1a3d](https://linux-hardware.org/?probe=9cc0db1a3d) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [d1bf55b135](https://linux-hardware.org/?probe=d1bf55b135) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ea8a893b11](https://linux-hardware.org/?probe=ea8a893b11) | Jul 29, 2023 |
| Lenovo        | ThinkPad W541 20EFS00N00    | Notebook    | [c9f80b56fc](https://linux-hardware.org/?probe=c9f80b56fc) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [9f04167710](https://linux-hardware.org/?probe=9f04167710) | Jul 27, 2023 |
| Acer          | EQ45LM                      | Desktop     | [29e2f587cd](https://linux-hardware.org/?probe=29e2f587cd) | Jul 26, 2023 |
| Acer          | EQ45LM                      | Desktop     | [37f6c76c11](https://linux-hardware.org/?probe=37f6c76c11) | Jul 25, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [798cadd754](https://linux-hardware.org/?probe=798cadd754) | Jul 25, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | Desktop     | [6417b2e0e3](https://linux-hardware.org/?probe=6417b2e0e3) | Jul 24, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [e9a58d14e7](https://linux-hardware.org/?probe=e9a58d14e7) | Jul 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [93857a3b66](https://linux-hardware.org/?probe=93857a3b66) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [dac4434339](https://linux-hardware.org/?probe=dac4434339) | Jul 18, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [3dfd41fda9](https://linux-hardware.org/?probe=3dfd41fda9) | Jul 17, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [c5bee4d8fe](https://linux-hardware.org/?probe=c5bee4d8fe) | Jul 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3057a60e0f](https://linux-hardware.org/?probe=3057a60e0f) | Jul 17, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [501969ed00](https://linux-hardware.org/?probe=501969ed00) | Jul 15, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [85d4919b9c](https://linux-hardware.org/?probe=85d4919b9c) | Jul 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [052b5c1741](https://linux-hardware.org/?probe=052b5c1741) | Jul 12, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [9fc68063e3](https://linux-hardware.org/?probe=9fc68063e3) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [f35543549c](https://linux-hardware.org/?probe=f35543549c) | Jul 11, 2023 |
| Unknown       | HP Chromebook 14            | Notebook    | [63b183aa51](https://linux-hardware.org/?probe=63b183aa51) | Jul 11, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [0ae95a7985](https://linux-hardware.org/?probe=0ae95a7985) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [3cad86057a](https://linux-hardware.org/?probe=3cad86057a) | Jul 09, 2023 |
| Acer          | EQ45LM                      | Desktop     | [3cafc83ffb](https://linux-hardware.org/?probe=3cafc83ffb) | Jul 08, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [a29509646a](https://linux-hardware.org/?probe=a29509646a) | Jul 08, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [952e97925b](https://linux-hardware.org/?probe=952e97925b) | Jul 08, 2023 |
| Dell          | Latitude 3500               | Notebook    | [38a0d6b099](https://linux-hardware.org/?probe=38a0d6b099) | Jul 08, 2023 |
| Dell          | Studio 1749                 | Notebook    | [fe1e5d7b8f](https://linux-hardware.org/?probe=fe1e5d7b8f) | Jul 05, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [79d631563a](https://linux-hardware.org/?probe=79d631563a) | Jul 01, 2023 |
| Acer          | EQ45LM                      | Desktop     | [30781f8f1b](https://linux-hardware.org/?probe=30781f8f1b) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8862b2d8db](https://linux-hardware.org/?probe=8862b2d8db) | Jun 25, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [dc2aebbc48](https://linux-hardware.org/?probe=dc2aebbc48) | Jun 24, 2023 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | Notebook    | [a74b5c2880](https://linux-hardware.org/?probe=a74b5c2880) | Jun 24, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [f0ab10725e](https://linux-hardware.org/?probe=f0ab10725e) | Jun 23, 2023 |
| Acer          | Aspire A315-58G             | Notebook    | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Acer          | Swift SF314-52G             | Notebook    | [4eab971a60](https://linux-hardware.org/?probe=4eab971a60) | Jun 21, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [530f6272c9](https://linux-hardware.org/?probe=530f6272c9) | Jun 20, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [928b30815b](https://linux-hardware.org/?probe=928b30815b) | Jun 18, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [c6a929a9ec](https://linux-hardware.org/?probe=c6a929a9ec) | Jun 17, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [d72b8e616f](https://linux-hardware.org/?probe=d72b8e616f) | Jun 17, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [0ef00ccccc](https://linux-hardware.org/?probe=0ef00ccccc) | Jun 16, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [f1f16d8add](https://linux-hardware.org/?probe=f1f16d8add) | Jun 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [2346d706e3](https://linux-hardware.org/?probe=2346d706e3) | Jun 15, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [7747deeb57](https://linux-hardware.org/?probe=7747deeb57) | Jun 15, 2023 |
| HP            | 81B3                        | Desktop     | [9ba98d3c27](https://linux-hardware.org/?probe=9ba98d3c27) | Jun 14, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [1c62ecb77d](https://linux-hardware.org/?probe=1c62ecb77d) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e073b99b63](https://linux-hardware.org/?probe=e073b99b63) | Jun 13, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [e722fda49e](https://linux-hardware.org/?probe=e722fda49e) | Jun 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [0f5b161a60](https://linux-hardware.org/?probe=0f5b161a60) | Jun 13, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [9e763f2e63](https://linux-hardware.org/?probe=9e763f2e63) | Jun 12, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [d567ae409c](https://linux-hardware.org/?probe=d567ae409c) | Jun 12, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [b6a626c812](https://linux-hardware.org/?probe=b6a626c812) | Jun 10, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [b9eb9677f5](https://linux-hardware.org/?probe=b9eb9677f5) | Jun 10, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [fadb7a6aa8](https://linux-hardware.org/?probe=fadb7a6aa8) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b7ab29fbb5](https://linux-hardware.org/?probe=b7ab29fbb5) | Jun 06, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [05530e670e](https://linux-hardware.org/?probe=05530e670e) | Jun 06, 2023 |
| Acer          | EQ45LM                      | Desktop     | [73f7a3078f](https://linux-hardware.org/?probe=73f7a3078f) | Jun 06, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ea07821e39](https://linux-hardware.org/?probe=ea07821e39) | Jun 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [1285aacf1b](https://linux-hardware.org/?probe=1285aacf1b) | Jun 04, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [7cd25ddbda](https://linux-hardware.org/?probe=7cd25ddbda) | Jun 04, 2023 |
| ASUSTek       | Zenbook UM5401RA_RM5401R... | Notebook    | [763a52f3e8](https://linux-hardware.org/?probe=763a52f3e8) | Jun 03, 2023 |
| HP            | ENVY 17                     | Notebook    | [79fd438f05](https://linux-hardware.org/?probe=79fd438f05) | Jun 03, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [055866f703](https://linux-hardware.org/?probe=055866f703) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [dc0e29f0bb](https://linux-hardware.org/?probe=dc0e29f0bb) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [693005f5b4](https://linux-hardware.org/?probe=693005f5b4) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [1f18cef2df](https://linux-hardware.org/?probe=1f18cef2df) | Jun 01, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [7ae3edd73e](https://linux-hardware.org/?probe=7ae3edd73e) | Jun 01, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [f93dd394e8](https://linux-hardware.org/?probe=f93dd394e8) | May 31, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [6bec5a03df](https://linux-hardware.org/?probe=6bec5a03df) | May 30, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [3ecf79af69](https://linux-hardware.org/?probe=3ecf79af69) | May 29, 2023 |
| Dell          | Latitude E6440              | Notebook    | [821e3e3246](https://linux-hardware.org/?probe=821e3e3246) | May 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [acee298918](https://linux-hardware.org/?probe=acee298918) | May 26, 2023 |
| Acer          | EQ45LM                      | Desktop     | [a49c4c8438](https://linux-hardware.org/?probe=a49c4c8438) | May 26, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [c8c9f63237](https://linux-hardware.org/?probe=c8c9f63237) | May 25, 2023 |
| Dell          | G15 5510                    | Notebook    | [325fcf6e78](https://linux-hardware.org/?probe=325fcf6e78) | May 25, 2023 |
| HP            | ProBook 6440b               | Notebook    | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [7a892801c0](https://linux-hardware.org/?probe=7a892801c0) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [61b85cdced](https://linux-hardware.org/?probe=61b85cdced) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [b167237d46](https://linux-hardware.org/?probe=b167237d46) | May 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [117db8031d](https://linux-hardware.org/?probe=117db8031d) | May 24, 2023 |
| Dell          | Precision 7540              | Notebook    | [65605ee5e8](https://linux-hardware.org/?probe=65605ee5e8) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [a1e2fa6222](https://linux-hardware.org/?probe=a1e2fa6222) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [cb3e4d2c2b](https://linux-hardware.org/?probe=cb3e4d2c2b) | May 24, 2023 |
| Allview       | Allbook H                   | Notebook    | [8b0c0a3436](https://linux-hardware.org/?probe=8b0c0a3436) | May 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [64ceddcdd4](https://linux-hardware.org/?probe=64ceddcdd4) | May 24, 2023 |
| Dell          | G15 5510                    | Notebook    | [730985e467](https://linux-hardware.org/?probe=730985e467) | May 24, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [319f4883aa](https://linux-hardware.org/?probe=319f4883aa) | May 22, 2023 |
| HP            | 805D                        | Desktop     | [2ac4992bcd](https://linux-hardware.org/?probe=2ac4992bcd) | May 22, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [5309c41b94](https://linux-hardware.org/?probe=5309c41b94) | May 21, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b8ed6a8b77](https://linux-hardware.org/?probe=b8ed6a8b77) | May 18, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ceeff309eb](https://linux-hardware.org/?probe=ceeff309eb) | May 18, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [00685614c4](https://linux-hardware.org/?probe=00685614c4) | May 16, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [fc6d34934a](https://linux-hardware.org/?probe=fc6d34934a) | May 14, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [cbd408a1a6](https://linux-hardware.org/?probe=cbd408a1a6) | May 13, 2023 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [f1884eebc6](https://linux-hardware.org/?probe=f1884eebc6) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| Acer          | Extensa 5220                | Notebook    | [935b52f12c](https://linux-hardware.org/?probe=935b52f12c) | May 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [af96be2497](https://linux-hardware.org/?probe=af96be2497) | May 11, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [5921d78ceb](https://linux-hardware.org/?probe=5921d78ceb) | May 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5f4146c326](https://linux-hardware.org/?probe=5f4146c326) | May 10, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [8f9a64c245](https://linux-hardware.org/?probe=8f9a64c245) | May 08, 2023 |
| Dell          | Inspiron 11-3162            | Notebook    | [62813124bb](https://linux-hardware.org/?probe=62813124bb) | May 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [a312f0545f](https://linux-hardware.org/?probe=a312f0545f) | May 07, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [2a321db63e](https://linux-hardware.org/?probe=2a321db63e) | May 07, 2023 |
| Dell          | 0YXT71 A03                  | Desktop     | [b8281f77a3](https://linux-hardware.org/?probe=b8281f77a3) | May 07, 2023 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [f86e67c005](https://linux-hardware.org/?probe=f86e67c005) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [85648a82df](https://linux-hardware.org/?probe=85648a82df) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d905babc43](https://linux-hardware.org/?probe=d905babc43) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [bb7835495e](https://linux-hardware.org/?probe=bb7835495e) | May 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [af9c3172bc](https://linux-hardware.org/?probe=af9c3172bc) | May 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [862ef64565](https://linux-hardware.org/?probe=862ef64565) | May 05, 2023 |
| MSI           | GP75 Leopard 9SE            | Notebook    | [425ecbf896](https://linux-hardware.org/?probe=425ecbf896) | May 04, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [7a04e30859](https://linux-hardware.org/?probe=7a04e30859) | May 03, 2023 |
| HP            | Notebook                    | Notebook    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [7c56fae21c](https://linux-hardware.org/?probe=7c56fae21c) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3b04b16c3e](https://linux-hardware.org/?probe=3b04b16c3e) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1234a4cf5a](https://linux-hardware.org/?probe=1234a4cf5a) | May 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e055c16455](https://linux-hardware.org/?probe=e055c16455) | May 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5101f4e19d](https://linux-hardware.org/?probe=5101f4e19d) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [2a4cf994ac](https://linux-hardware.org/?probe=2a4cf994ac) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ed2a323b49](https://linux-hardware.org/?probe=ed2a323b49) | May 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [4607549f5a](https://linux-hardware.org/?probe=4607549f5a) | May 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [754b22a59c](https://linux-hardware.org/?probe=754b22a59c) | May 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d1b974c33a](https://linux-hardware.org/?probe=d1b974c33a) | May 01, 2023 |
| Lenovo        | 36DB No DPK                 | All in one  | [01458c55a9](https://linux-hardware.org/?probe=01458c55a9) | Apr 28, 2023 |
| Lenovo        | 36DB No DPK                 | All in one  | [df53e54c69](https://linux-hardware.org/?probe=df53e54c69) | Apr 28, 2023 |
| Acer          | Aspire 5110                 | Notebook    | [b43b059257](https://linux-hardware.org/?probe=b43b059257) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2beb48be05](https://linux-hardware.org/?probe=2beb48be05) | Apr 27, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [f58ab8b9c4](https://linux-hardware.org/?probe=f58ab8b9c4) | Apr 27, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| ASUSTek       | K53SM                       | Notebook    | [92ac292547](https://linux-hardware.org/?probe=92ac292547) | Apr 24, 2023 |
| Acer          | Aspire V5-122P              | Notebook    | [baf567c71f](https://linux-hardware.org/?probe=baf567c71f) | Apr 23, 2023 |
| Samsung       | 730QDA                      | Convertible | [a6fef02901](https://linux-hardware.org/?probe=a6fef02901) | Apr 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [481c5a9169](https://linux-hardware.org/?probe=481c5a9169) | Apr 23, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [6e52b3ea77](https://linux-hardware.org/?probe=6e52b3ea77) | Apr 22, 2023 |
| Allview       | Allbook J                   | Notebook    | [96a3d7d3ef](https://linux-hardware.org/?probe=96a3d7d3ef) | Apr 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [1127dfa79c](https://linux-hardware.org/?probe=1127dfa79c) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [3f01c5df6e](https://linux-hardware.org/?probe=3f01c5df6e) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [a5ef39681b](https://linux-hardware.org/?probe=a5ef39681b) | Apr 21, 2023 |
| Allview       | Allbook J                   | Notebook    | [4ff8627338](https://linux-hardware.org/?probe=4ff8627338) | Apr 18, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c7ca0e9fd1](https://linux-hardware.org/?probe=c7ca0e9fd1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [0c4578a674](https://linux-hardware.org/?probe=0c4578a674) | Apr 14, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [356ff49c7c](https://linux-hardware.org/?probe=356ff49c7c) | Apr 13, 2023 |
| HP            | 1495                        | Desktop     | [569a6f28f4](https://linux-hardware.org/?probe=569a6f28f4) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [da4c241466](https://linux-hardware.org/?probe=da4c241466) | Apr 10, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [5244868737](https://linux-hardware.org/?probe=5244868737) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | Notebook    | [ae8c333d72](https://linux-hardware.org/?probe=ae8c333d72) | Apr 07, 2023 |
| ASUSTek       | X55U                        | Notebook    | [0abf7df439](https://linux-hardware.org/?probe=0abf7df439) | Apr 06, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [6b554016fe](https://linux-hardware.org/?probe=6b554016fe) | Apr 03, 2023 |
| ASUSTek       | J1900I-C                    | Desktop     | [0fbd47b12e](https://linux-hardware.org/?probe=0fbd47b12e) | Apr 02, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [90796fbad9](https://linux-hardware.org/?probe=90796fbad9) | Mar 31, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [5d5862d22a](https://linux-hardware.org/?probe=5d5862d22a) | Mar 31, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [5be11a9a6e](https://linux-hardware.org/?probe=5be11a9a6e) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [bfa850ddad](https://linux-hardware.org/?probe=bfa850ddad) | Mar 29, 2023 |
| HP            | 3047h                       | Desktop     | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [577947c9d3](https://linux-hardware.org/?probe=577947c9d3) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [08e7388619](https://linux-hardware.org/?probe=08e7388619) | Mar 27, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [bef27b5a10](https://linux-hardware.org/?probe=bef27b5a10) | Mar 26, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [daac2899b2](https://linux-hardware.org/?probe=daac2899b2) | Mar 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [84af25ca8c](https://linux-hardware.org/?probe=84af25ca8c) | Mar 26, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [f99591fe95](https://linux-hardware.org/?probe=f99591fe95) | Mar 26, 2023 |
| Acer          | V5-131                      | Notebook    | [f35bd55401](https://linux-hardware.org/?probe=f35bd55401) | Mar 26, 2023 |
| Acer          | TravelMate 5744             | Notebook    | [3ad8bf7639](https://linux-hardware.org/?probe=3ad8bf7639) | Mar 22, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [c5b2997e80](https://linux-hardware.org/?probe=c5b2997e80) | Mar 21, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [4a4c44f0dd](https://linux-hardware.org/?probe=4a4c44f0dd) | Mar 18, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ceb794a09f](https://linux-hardware.org/?probe=ceb794a09f) | Mar 17, 2023 |
| ASUSTek       | P9X79 WS                    | Desktop     | [29e03bb7ce](https://linux-hardware.org/?probe=29e03bb7ce) | Mar 17, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| HP            | ZBook 15                    | Notebook    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [8912f590e3](https://linux-hardware.org/?probe=8912f590e3) | Mar 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [d56d3939f9](https://linux-hardware.org/?probe=d56d3939f9) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [abebd8a5c2](https://linux-hardware.org/?probe=abebd8a5c2) | Mar 11, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | Notebook    | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a3a158ccf2](https://linux-hardware.org/?probe=a3a158ccf2) | Mar 08, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [72d0284bdd](https://linux-hardware.org/?probe=72d0284bdd) | Mar 05, 2023 |
| HP            | Compaq 6735b                | Notebook    | [8c664182a2](https://linux-hardware.org/?probe=8c664182a2) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [9fba7bceb7](https://linux-hardware.org/?probe=9fba7bceb7) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2dea6717ae](https://linux-hardware.org/?probe=2dea6717ae) | Mar 02, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| ASUSTek       | FX503VD                     | Notebook    | [46954919f7](https://linux-hardware.org/?probe=46954919f7) | Feb 27, 2023 |
| ASUSTek       | FX503VD                     | Notebook    | [60e1742e7e](https://linux-hardware.org/?probe=60e1742e7e) | Feb 27, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [ea8bb4c0e4](https://linux-hardware.org/?probe=ea8bb4c0e4) | Feb 27, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [edf748dbbb](https://linux-hardware.org/?probe=edf748dbbb) | Feb 26, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [22cf774ac0](https://linux-hardware.org/?probe=22cf774ac0) | Feb 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [46aedb5579](https://linux-hardware.org/?probe=46aedb5579) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | Notebook    | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [0f251d6bbf](https://linux-hardware.org/?probe=0f251d6bbf) | Feb 23, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [bf6718f1d0](https://linux-hardware.org/?probe=bf6718f1d0) | Feb 22, 2023 |
| Dell          | Latitude 5580               | Notebook    | [91567566be](https://linux-hardware.org/?probe=91567566be) | Feb 21, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [e8963c4e59](https://linux-hardware.org/?probe=e8963c4e59) | Feb 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [c205da78c9](https://linux-hardware.org/?probe=c205da78c9) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [8942075e7b](https://linux-hardware.org/?probe=8942075e7b) | Feb 18, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [dc294f018e](https://linux-hardware.org/?probe=dc294f018e) | Feb 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [e614d24613](https://linux-hardware.org/?probe=e614d24613) | Feb 17, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [f36e84dcaf](https://linux-hardware.org/?probe=f36e84dcaf) | Feb 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [684445aeab](https://linux-hardware.org/?probe=684445aeab) | Feb 16, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| HP            | 0AA8h                       | Desktop     | [e7bbc5903b](https://linux-hardware.org/?probe=e7bbc5903b) | Feb 15, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [6047c68386](https://linux-hardware.org/?probe=6047c68386) | Feb 11, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [199c8805ee](https://linux-hardware.org/?probe=199c8805ee) | Feb 10, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [1360d3227f](https://linux-hardware.org/?probe=1360d3227f) | Feb 10, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [fa2a1dba2d](https://linux-hardware.org/?probe=fa2a1dba2d) | Feb 09, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [e7b8536ad4](https://linux-hardware.org/?probe=e7b8536ad4) | Feb 09, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [a2729c9880](https://linux-hardware.org/?probe=a2729c9880) | Feb 08, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [6161d6b31d](https://linux-hardware.org/?probe=6161d6b31d) | Feb 08, 2023 |
| HP            | 1494                        | Desktop     | [ba7c61bf23](https://linux-hardware.org/?probe=ba7c61bf23) | Feb 07, 2023 |
| HP            | 1494                        | Desktop     | [a582a0d6c7](https://linux-hardware.org/?probe=a582a0d6c7) | Feb 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0c14eb04ce](https://linux-hardware.org/?probe=0c14eb04ce) | Feb 06, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [2f47f8d73d](https://linux-hardware.org/?probe=2f47f8d73d) | Feb 05, 2023 |
| Toshiba       | Satellite C55-A-168         | Notebook    | [e92c2babc4](https://linux-hardware.org/?probe=e92c2babc4) | Feb 05, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [c4c5c0888a](https://linux-hardware.org/?probe=c4c5c0888a) | Feb 04, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [4ed27fe851](https://linux-hardware.org/?probe=4ed27fe851) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [a2ff80e7dd](https://linux-hardware.org/?probe=a2ff80e7dd) | Feb 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [2791787281](https://linux-hardware.org/?probe=2791787281) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [e2ad5b033f](https://linux-hardware.org/?probe=e2ad5b033f) | Jan 31, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [6c3dd54582](https://linux-hardware.org/?probe=6c3dd54582) | Jan 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| ASRock        | J4125M                      | Desktop     | [535c1b6821](https://linux-hardware.org/?probe=535c1b6821) | Jan 30, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [da2056876e](https://linux-hardware.org/?probe=da2056876e) | Jan 29, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [b7377ee894](https://linux-hardware.org/?probe=b7377ee894) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [b8891cfc9b](https://linux-hardware.org/?probe=b8891cfc9b) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [fb0a23c0e6](https://linux-hardware.org/?probe=fb0a23c0e6) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [24b6a47ebb](https://linux-hardware.org/?probe=24b6a47ebb) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [5d58c53672](https://linux-hardware.org/?probe=5d58c53672) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [b352f0af44](https://linux-hardware.org/?probe=b352f0af44) | Jan 27, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3e65f42529](https://linux-hardware.org/?probe=3e65f42529) | Jan 26, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [e030231e2c](https://linux-hardware.org/?probe=e030231e2c) | Jan 25, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [5f584c387e](https://linux-hardware.org/?probe=5f584c387e) | Jan 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [5b2fd24ed7](https://linux-hardware.org/?probe=5b2fd24ed7) | Jan 24, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [ac4fa9fd5f](https://linux-hardware.org/?probe=ac4fa9fd5f) | Jan 23, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [36d99ec94e](https://linux-hardware.org/?probe=36d99ec94e) | Jan 22, 2023 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [cd23d81f65](https://linux-hardware.org/?probe=cd23d81f65) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [adbc469f95](https://linux-hardware.org/?probe=adbc469f95) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [9249ff32b3](https://linux-hardware.org/?probe=9249ff32b3) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [a7ba34fed5](https://linux-hardware.org/?probe=a7ba34fed5) | Jan 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [de713cedce](https://linux-hardware.org/?probe=de713cedce) | Jan 21, 2023 |
| Acer          | V5WE2                       | Notebook    | [021281441e](https://linux-hardware.org/?probe=021281441e) | Jan 20, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [be320f363d](https://linux-hardware.org/?probe=be320f363d) | Jan 19, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [e3d0558aee](https://linux-hardware.org/?probe=e3d0558aee) | Jan 19, 2023 |
| Dell          | Precision M6600             | Notebook    | [478f51f2be](https://linux-hardware.org/?probe=478f51f2be) | Jan 17, 2023 |
| MSI           | 970A-G43                    | Desktop     | [086e04b65f](https://linux-hardware.org/?probe=086e04b65f) | Jan 17, 2023 |
| Dell          | Precision M6600             | Notebook    | [7511681884](https://linux-hardware.org/?probe=7511681884) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [bf8115e391](https://linux-hardware.org/?probe=bf8115e391) | Jan 15, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [25cf332260](https://linux-hardware.org/?probe=25cf332260) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3f12fad87c](https://linux-hardware.org/?probe=3f12fad87c) | Jan 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6584beb723](https://linux-hardware.org/?probe=6584beb723) | Jan 15, 2023 |
| Gigabyte      | H67M-D2-B3                  | Desktop     | [6a4e71bb84](https://linux-hardware.org/?probe=6a4e71bb84) | Jan 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [020abf67f6](https://linux-hardware.org/?probe=020abf67f6) | Jan 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [f32463429a](https://linux-hardware.org/?probe=f32463429a) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [6f39a15710](https://linux-hardware.org/?probe=6f39a15710) | Jan 13, 2023 |
| ASUSTek       | X406UAR                     | Notebook    | [68da6f6220](https://linux-hardware.org/?probe=68da6f6220) | Jan 13, 2023 |
| ASUSTek       | J1900I-C                    | Desktop     | [f12439ce42](https://linux-hardware.org/?probe=f12439ce42) | Jan 13, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [0eb36758be](https://linux-hardware.org/?probe=0eb36758be) | Jan 13, 2023 |
| HP            | 21F5                        | Desktop     | [141aa3faa6](https://linux-hardware.org/?probe=141aa3faa6) | Jan 12, 2023 |
| ASUSTek       | X406UAR                     | Notebook    | [729e2e0d41](https://linux-hardware.org/?probe=729e2e0d41) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [de94c3e313](https://linux-hardware.org/?probe=de94c3e313) | Jan 12, 2023 |
| ASUSTek       | PN50                        | Mini pc     | [564c992a69](https://linux-hardware.org/?probe=564c992a69) | Jan 11, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [9a698e2879](https://linux-hardware.org/?probe=9a698e2879) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| Acer          | TMP645-M                    | Notebook    | [8e0b2f5e90](https://linux-hardware.org/?probe=8e0b2f5e90) | Jan 10, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [afe262fc54](https://linux-hardware.org/?probe=afe262fc54) | Jan 09, 2023 |
| ASUSTek       | K50IE                       | Notebook    | [4fdb15502c](https://linux-hardware.org/?probe=4fdb15502c) | Jan 09, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | Notebook    | [fc35d7e62b](https://linux-hardware.org/?probe=fc35d7e62b) | Jan 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [69cda32447](https://linux-hardware.org/?probe=69cda32447) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [c4ae03416f](https://linux-hardware.org/?probe=c4ae03416f) | Jan 07, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [cc98c43ea0](https://linux-hardware.org/?probe=cc98c43ea0) | Jan 07, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [9320df061f](https://linux-hardware.org/?probe=9320df061f) | Jan 06, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Neousys Te... | POC-200 Series              | Notebook    | [7c37ff8631](https://linux-hardware.org/?probe=7c37ff8631) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| ASRock        | FM2A88M-HD+ R3.0            | Desktop     | [acbd8114d2](https://linux-hardware.org/?probe=acbd8114d2) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [3fb1b015e3](https://linux-hardware.org/?probe=3fb1b015e3) | Jan 02, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [cdb2bf4725](https://linux-hardware.org/?probe=cdb2bf4725) | Jan 02, 2023 |
| MSI           | PRO B660M-E DDR4            | Desktop     | [6ae9b30e34](https://linux-hardware.org/?probe=6ae9b30e34) | Jan 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [8db34630c3](https://linux-hardware.org/?probe=8db34630c3) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1ff4c4bf09](https://linux-hardware.org/?probe=1ff4c4bf09) | Dec 28, 2022 |
| Lenovo        | No DPK                      | Desktop     | [944f84567a](https://linux-hardware.org/?probe=944f84567a) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [57a42cabf6](https://linux-hardware.org/?probe=57a42cabf6) | Dec 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [9a6b000b23](https://linux-hardware.org/?probe=9a6b000b23) | Dec 23, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [2892951c9c](https://linux-hardware.org/?probe=2892951c9c) | Dec 23, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [81f7e4d804](https://linux-hardware.org/?probe=81f7e4d804) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [ddc35a5b0d](https://linux-hardware.org/?probe=ddc35a5b0d) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | Notebook    | [6306be2273](https://linux-hardware.org/?probe=6306be2273) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | Notebook    | [cf8576151f](https://linux-hardware.org/?probe=cf8576151f) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| HP            | 89E8 0100                   | All in one  | [0e9567b0a5](https://linux-hardware.org/?probe=0e9567b0a5) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [d27a2a4e0f](https://linux-hardware.org/?probe=d27a2a4e0f) | Dec 20, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [30aec905c0](https://linux-hardware.org/?probe=30aec905c0) | Dec 19, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [20544e55bb](https://linux-hardware.org/?probe=20544e55bb) | Dec 14, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d087536cbf](https://linux-hardware.org/?probe=d087536cbf) | Dec 14, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [20c4b98c2c](https://linux-hardware.org/?probe=20c4b98c2c) | Dec 14, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| MSI           | MS-B1591                    | Desktop     | [33cb107fb9](https://linux-hardware.org/?probe=33cb107fb9) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [a1f1288337](https://linux-hardware.org/?probe=a1f1288337) | Dec 13, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [d1b0bc1c03](https://linux-hardware.org/?probe=d1b0bc1c03) | Dec 12, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [05c7382806](https://linux-hardware.org/?probe=05c7382806) | Dec 11, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [97691e3dca](https://linux-hardware.org/?probe=97691e3dca) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a7a3ccf712](https://linux-hardware.org/?probe=a7a3ccf712) | Dec 11, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [32e7431c24](https://linux-hardware.org/?probe=32e7431c24) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [83b02f1ffb](https://linux-hardware.org/?probe=83b02f1ffb) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ec32b72261](https://linux-hardware.org/?probe=ec32b72261) | Dec 09, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [e7495f12e4](https://linux-hardware.org/?probe=e7495f12e4) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea7638c0f9](https://linux-hardware.org/?probe=ea7638c0f9) | Dec 07, 2022 |
| ASRock        | N68-GE3 UCC                 | Desktop     | [fd65cfedda](https://linux-hardware.org/?probe=fd65cfedda) | Dec 07, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [10f8aab734](https://linux-hardware.org/?probe=10f8aab734) | Dec 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a35bac4078](https://linux-hardware.org/?probe=a35bac4078) | Dec 06, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [2f693620e1](https://linux-hardware.org/?probe=2f693620e1) | Dec 06, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [586b9fe0a6](https://linux-hardware.org/?probe=586b9fe0a6) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b387887bb6](https://linux-hardware.org/?probe=b387887bb6) | Dec 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [d5ada57985](https://linux-hardware.org/?probe=d5ada57985) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3d64de28f5](https://linux-hardware.org/?probe=3d64de28f5) | Dec 01, 2022 |
| MSI           | G41M-S03                    | Desktop     | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | Notebook    | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1FR0... | Notebook    | [517347d2cf](https://linux-hardware.org/?probe=517347d2cf) | Nov 30, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b7a1fc62d1](https://linux-hardware.org/?probe=b7a1fc62d1) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [972f6f4355](https://linux-hardware.org/?probe=972f6f4355) | Nov 28, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [5b2f9bfd5c](https://linux-hardware.org/?probe=5b2f9bfd5c) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a39632439e](https://linux-hardware.org/?probe=a39632439e) | Nov 27, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [16679f50e3](https://linux-hardware.org/?probe=16679f50e3) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a178e673c3](https://linux-hardware.org/?probe=a178e673c3) | Nov 26, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [c1d5a26691](https://linux-hardware.org/?probe=c1d5a26691) | Nov 26, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a41bb9177a](https://linux-hardware.org/?probe=a41bb9177a) | Nov 23, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6c797b4554](https://linux-hardware.org/?probe=6c797b4554) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [b8379d261b](https://linux-hardware.org/?probe=b8379d261b) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Dell          | Latitude E6410              | Notebook    | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [75af06e026](https://linux-hardware.org/?probe=75af06e026) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c5ec7b9dcc](https://linux-hardware.org/?probe=c5ec7b9dcc) | Nov 20, 2022 |
| Lenovo        | V15 G1 IML 82NB             | Notebook    | [a120cac88b](https://linux-hardware.org/?probe=a120cac88b) | Nov 18, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2089ec3efb](https://linux-hardware.org/?probe=2089ec3efb) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | Desktop     | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Allview       | Allbook H                   | Notebook    | [4de72c8cba](https://linux-hardware.org/?probe=4de72c8cba) | Nov 17, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| HP            | 843B                        | Desktop     | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [30916d8420](https://linux-hardware.org/?probe=30916d8420) | Nov 16, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [61bcea3891](https://linux-hardware.org/?probe=61bcea3891) | Nov 13, 2022 |
| Alienware     | Area-51m                    | Notebook    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| Dell          | Latitude E7270              | Notebook    | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e80d2221f5](https://linux-hardware.org/?probe=e80d2221f5) | Nov 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [8384350121](https://linux-hardware.org/?probe=8384350121) | Nov 08, 2022 |
| Acer          | Aspire A314-35              | Notebook    | [14751e1ae3](https://linux-hardware.org/?probe=14751e1ae3) | Nov 08, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [7dc3ed5f76](https://linux-hardware.org/?probe=7dc3ed5f76) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81A8     | Notebook    | [85efda7536](https://linux-hardware.org/?probe=85efda7536) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [f9238c2035](https://linux-hardware.org/?probe=f9238c2035) | Oct 28, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [9e8ec19352](https://linux-hardware.org/?probe=9e8ec19352) | Oct 26, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [7274eca48b](https://linux-hardware.org/?probe=7274eca48b) | Oct 23, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [84941aaa84](https://linux-hardware.org/?probe=84941aaa84) | Oct 14, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [a6a5cdbf04](https://linux-hardware.org/?probe=a6a5cdbf04) | Oct 13, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [478ba58d34](https://linux-hardware.org/?probe=478ba58d34) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| ASUSTek       | V222GAR                     | All in one  | [e7e07dca5c](https://linux-hardware.org/?probe=e7e07dca5c) | Oct 12, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [79236a7a89](https://linux-hardware.org/?probe=79236a7a89) | Oct 11, 2022 |
| Medion        | Akoya E6239                 | Notebook    | [46ce690b32](https://linux-hardware.org/?probe=46ce690b32) | Oct 10, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [abc991002e](https://linux-hardware.org/?probe=abc991002e) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8694ed82a6](https://linux-hardware.org/?probe=8694ed82a6) | Oct 09, 2022 |
| Dell          | Latitude E6410              | Notebook    | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| HP            | 2AED                        | All in one  | [9092720ed6](https://linux-hardware.org/?probe=9092720ed6) | Oct 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9474bd3b9](https://linux-hardware.org/?probe=d9474bd3b9) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [cf4537f9cb](https://linux-hardware.org/?probe=cf4537f9cb) | Oct 02, 2022 |
| Medion        | Akoya P2214T                | Notebook    | [428205d2a5](https://linux-hardware.org/?probe=428205d2a5) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [3e92ba3812](https://linux-hardware.org/?probe=3e92ba3812) | Sep 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [96c4c8ba02](https://linux-hardware.org/?probe=96c4c8ba02) | Sep 28, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [11f99758e6](https://linux-hardware.org/?probe=11f99758e6) | Sep 28, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | Notebook    | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [deed57ec88](https://linux-hardware.org/?probe=deed57ec88) | Sep 23, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [38e1cc9153](https://linux-hardware.org/?probe=38e1cc9153) | Sep 22, 2022 |
| Fusion5       | S14                         | Notebook    | [9b3e06c4e4](https://linux-hardware.org/?probe=9b3e06c4e4) | Sep 22, 2022 |
| Acer          | Aspire 5750Z                | Notebook    | [b673d5cfe9](https://linux-hardware.org/?probe=b673d5cfe9) | Sep 22, 2022 |
| Dell          | Precision 3561              | Notebook    | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [aba8915769](https://linux-hardware.org/?probe=aba8915769) | Sep 19, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [d52ac897f4](https://linux-hardware.org/?probe=d52ac897f4) | Sep 15, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [39f83f7692](https://linux-hardware.org/?probe=39f83f7692) | Sep 13, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2af6edb7a0](https://linux-hardware.org/?probe=2af6edb7a0) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [43311add57](https://linux-hardware.org/?probe=43311add57) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c13cd2c2ac](https://linux-hardware.org/?probe=c13cd2c2ac) | Sep 09, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [3474424d64](https://linux-hardware.org/?probe=3474424d64) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [a2962588fa](https://linux-hardware.org/?probe=a2962588fa) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e47c8e6967](https://linux-hardware.org/?probe=e47c8e6967) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [3f805d59b5](https://linux-hardware.org/?probe=3f805d59b5) | Sep 04, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [dcf7869cf6](https://linux-hardware.org/?probe=dcf7869cf6) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [c129f7c9b1](https://linux-hardware.org/?probe=c129f7c9b1) | Aug 29, 2022 |
| Dell          | Latitude E7470              | Notebook    | [568c9bfd40](https://linux-hardware.org/?probe=568c9bfd40) | Aug 28, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [4c16a58579](https://linux-hardware.org/?probe=4c16a58579) | Aug 28, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [fbf3d4a87a](https://linux-hardware.org/?probe=fbf3d4a87a) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [8b85141416](https://linux-hardware.org/?probe=8b85141416) | Aug 26, 2022 |
| Complet       | MY8312                      | Notebook    | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [09feb7053d](https://linux-hardware.org/?probe=09feb7053d) | Aug 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [69281b6cc3](https://linux-hardware.org/?probe=69281b6cc3) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [2af48f00ac](https://linux-hardware.org/?probe=2af48f00ac) | Aug 22, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [0910ca3887](https://linux-hardware.org/?probe=0910ca3887) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| Dell          | Latitude 7410               | Notebook    | [ae90ce90ed](https://linux-hardware.org/?probe=ae90ce90ed) | Aug 22, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [5cbe471be8](https://linux-hardware.org/?probe=5cbe471be8) | Aug 19, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | Notebook    | [1a0800fc4a](https://linux-hardware.org/?probe=1a0800fc4a) | Aug 19, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [4b585d8c34](https://linux-hardware.org/?probe=4b585d8c34) | Aug 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [f45a97ca40](https://linux-hardware.org/?probe=f45a97ca40) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [ca6a3b3fba](https://linux-hardware.org/?probe=ca6a3b3fba) | Aug 12, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [cdee8ca864](https://linux-hardware.org/?probe=cdee8ca864) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [eb79423b1d](https://linux-hardware.org/?probe=eb79423b1d) | Aug 12, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [86523f9a5f](https://linux-hardware.org/?probe=86523f9a5f) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [6826a8d40d](https://linux-hardware.org/?probe=6826a8d40d) | Aug 08, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [83626d765b](https://linux-hardware.org/?probe=83626d765b) | Aug 08, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [94d50a1c56](https://linux-hardware.org/?probe=94d50a1c56) | Aug 08, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1fe8a14d3b](https://linux-hardware.org/?probe=1fe8a14d3b) | Aug 06, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Unknown       | 1.0                         | Desktop     | [4394243123](https://linux-hardware.org/?probe=4394243123) | Aug 05, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | Notebook    | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| Unknown       | 1.0                         | Desktop     | [545d9cf73c](https://linux-hardware.org/?probe=545d9cf73c) | Aug 04, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [fbe4f4d2ce](https://linux-hardware.org/?probe=fbe4f4d2ce) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [eeccdc2b7f](https://linux-hardware.org/?probe=eeccdc2b7f) | Aug 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e6bfde2a29](https://linux-hardware.org/?probe=e6bfde2a29) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8b3fd99e18](https://linux-hardware.org/?probe=8b3fd99e18) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4ee4fc0689](https://linux-hardware.org/?probe=4ee4fc0689) | Jul 26, 2022 |
| HP            | 8704                        | Desktop     | [eaa4bc0059](https://linux-hardware.org/?probe=eaa4bc0059) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | Notebook    | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [892229b650](https://linux-hardware.org/?probe=892229b650) | Jul 21, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [9a5f11c4b9](https://linux-hardware.org/?probe=9a5f11c4b9) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Acer          | Aspire SW3-016              | Notebook    | [c48cdf5576](https://linux-hardware.org/?probe=c48cdf5576) | Jul 17, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [84cd652e24](https://linux-hardware.org/?probe=84cd652e24) | Jul 16, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [55efce6cdc](https://linux-hardware.org/?probe=55efce6cdc) | Jul 13, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [be909dd3b4](https://linux-hardware.org/?probe=be909dd3b4) | Jul 12, 2022 |
| HP            | 355 G2                      | Notebook    | [55239c5062](https://linux-hardware.org/?probe=55239c5062) | Jul 11, 2022 |
| HP            | 355 G2                      | Notebook    | [9b5e64b838](https://linux-hardware.org/?probe=9b5e64b838) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| HP            | 250 G4                      | Notebook    | [33dcd9203d](https://linux-hardware.org/?probe=33dcd9203d) | Jul 09, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [99172a6e6f](https://linux-hardware.org/?probe=99172a6e6f) | Jul 08, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [cb302e010e](https://linux-hardware.org/?probe=cb302e010e) | Jul 08, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [f991c1fba8](https://linux-hardware.org/?probe=f991c1fba8) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | Desktop     | [a5f338ae1a](https://linux-hardware.org/?probe=a5f338ae1a) | Jul 07, 2022 |
| HP            | ProBook 4310s               | Notebook    | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [32463f298d](https://linux-hardware.org/?probe=32463f298d) | Jul 05, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [457aa90e64](https://linux-hardware.org/?probe=457aa90e64) | Jul 02, 2022 |
| Dell          | Latitude 5521               | Notebook    | [2fda374f06](https://linux-hardware.org/?probe=2fda374f06) | Jun 24, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [eeac425783](https://linux-hardware.org/?probe=eeac425783) | Jun 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [70d6947d54](https://linux-hardware.org/?probe=70d6947d54) | Jun 16, 2022 |
| HP            | 1790                        | Desktop     | [341a6c4c70](https://linux-hardware.org/?probe=341a6c4c70) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [1e88796016](https://linux-hardware.org/?probe=1e88796016) | Jun 15, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4b2037715f](https://linux-hardware.org/?probe=4b2037715f) | Jun 15, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Dell          | Latitude E6440              | Notebook    | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a144e0b75e](https://linux-hardware.org/?probe=a144e0b75e) | Jun 08, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [992f232db5](https://linux-hardware.org/?probe=992f232db5) | Jun 08, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [ef5b8100ce](https://linux-hardware.org/?probe=ef5b8100ce) | Jun 07, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Prestigio     | PSB141C04CGP                | Notebook    | [4fa2ee47c0](https://linux-hardware.org/?probe=4fa2ee47c0) | Jun 01, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [083e3a354a](https://linux-hardware.org/?probe=083e3a354a) | May 29, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [83209051cb](https://linux-hardware.org/?probe=83209051cb) | May 29, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [74c64ebe72](https://linux-hardware.org/?probe=74c64ebe72) | May 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [3115570400](https://linux-hardware.org/?probe=3115570400) | May 24, 2022 |
| Allview       | Allbook H                   | Notebook    | [9ea4897c6b](https://linux-hardware.org/?probe=9ea4897c6b) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b01633e1ae](https://linux-hardware.org/?probe=b01633e1ae) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [815dbb114b](https://linux-hardware.org/?probe=815dbb114b) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9a6c29a243](https://linux-hardware.org/?probe=9a6c29a243) | May 21, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [949f8f3e50](https://linux-hardware.org/?probe=949f8f3e50) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [4d2d33c41c](https://linux-hardware.org/?probe=4d2d33c41c) | May 20, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| Lenovo        | ThinkPad P53 20QNS01900     | Notebook    | [158f212b30](https://linux-hardware.org/?probe=158f212b30) | May 13, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [550824d592](https://linux-hardware.org/?probe=550824d592) | May 12, 2022 |
| HP            | 0AA8h                       | Desktop     | [7d29587a1a](https://linux-hardware.org/?probe=7d29587a1a) | May 11, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [324d1abe3b](https://linux-hardware.org/?probe=324d1abe3b) | May 08, 2022 |
| HP            | ProBook 4520s               | Notebook    | [06e044a425](https://linux-hardware.org/?probe=06e044a425) | May 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [52c2a321a4](https://linux-hardware.org/?probe=52c2a321a4) | May 07, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [9fe037820e](https://linux-hardware.org/?probe=9fe037820e) | May 05, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [7a6aa0c236](https://linux-hardware.org/?probe=7a6aa0c236) | May 03, 2022 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [713358f855](https://linux-hardware.org/?probe=713358f855) | May 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [a8e967a378](https://linux-hardware.org/?probe=a8e967a378) | May 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6537fb670a](https://linux-hardware.org/?probe=6537fb670a) | May 01, 2022 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| HP            | ProBook 4520s               | Notebook    | [60eab2c6c5](https://linux-hardware.org/?probe=60eab2c6c5) | Apr 30, 2022 |
| Pegatron      | Spring Peak                 | Notebook    | [66a1692171](https://linux-hardware.org/?probe=66a1692171) | Apr 30, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [efcd6be006](https://linux-hardware.org/?probe=efcd6be006) | Apr 27, 2022 |
| Dell          | Latitude E4310              | Notebook    | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [afe44fa080](https://linux-hardware.org/?probe=afe44fa080) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8ece944a7b](https://linux-hardware.org/?probe=8ece944a7b) | Apr 27, 2022 |
| Dell          | Latitude E6520              | Notebook    | [1ca407a69f](https://linux-hardware.org/?probe=1ca407a69f) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bcc0c7612d](https://linux-hardware.org/?probe=bcc0c7612d) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1EH0... | Notebook    | [fae5ee6551](https://linux-hardware.org/?probe=fae5ee6551) | Apr 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [c7dfc69b32](https://linux-hardware.org/?probe=c7dfc69b32) | Apr 26, 2022 |
| HP            | ProBook 4520s               | Notebook    | [1621eddc70](https://linux-hardware.org/?probe=1621eddc70) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [41276f12db](https://linux-hardware.org/?probe=41276f12db) | Apr 23, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | Notebook    | [55733b5ae3](https://linux-hardware.org/?probe=55733b5ae3) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [a551ef1ec7](https://linux-hardware.org/?probe=a551ef1ec7) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [fd6718859d](https://linux-hardware.org/?probe=fd6718859d) | Apr 23, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [2518b6daad](https://linux-hardware.org/?probe=2518b6daad) | Apr 22, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [17d51c502f](https://linux-hardware.org/?probe=17d51c502f) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a3a204ed56](https://linux-hardware.org/?probe=a3a204ed56) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4521315d14](https://linux-hardware.org/?probe=4521315d14) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [fff2447e5a](https://linux-hardware.org/?probe=fff2447e5a) | Apr 21, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | Notebook    | [de746c72d1](https://linux-hardware.org/?probe=de746c72d1) | Apr 20, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [5d95841f54](https://linux-hardware.org/?probe=5d95841f54) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | Notebook    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Romania/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 212       | 9.67%   |
| Ubuntu 22.04                 | 111       | 5.06%   |
| Ubuntu 18.04                 | 107       | 4.88%   |
| BlackPanther 18.1            | 62        | 2.83%   |
| OpenMandriva 4.3             | 51        | 2.33%   |
| OpenMandriva 4.2             | 45        | 2.05%   |
| Arch Rolling                 | 38        | 1.73%   |
| Manjaro                      | 36        | 1.64%   |
| Zorin 16                     | 31        | 1.41%   |
| Debian 11                    | 30        | 1.37%   |
| ArcoLinux Rolling            | 29        | 1.32%   |
| Arch                         | 28        | 1.28%   |
| ROSA R10                     | 27        | 1.23%   |
| Pop!_OS 22.04                | 24        | 1.09%   |
| KDE neon 20.04               | 24        | 1.09%   |
| Pop!_OS 21.04                | 23        | 1.05%   |
| Linux Mint 21.1              | 22        | 1%      |
| Fedora 39                    | 21        | 0.96%   |
| Ubuntu 21.10                 | 20        | 0.91%   |
| Pop!_OS 20.04                | 20        | 0.91%   |
| openSUSE Tumbleweed-XXXXXXXX | 20        | 0.91%   |
| Endless 3.7.8                | 20        | 0.91%   |
| Debian 12                    | 20        | 0.91%   |
| Zorin 15                     | 19        | 0.87%   |
| Fedora 35                    | 19        | 0.87%   |
| Ubuntu 23.04                 | 18        | 0.82%   |
| Ubuntu 20.10                 | 18        | 0.82%   |
| Fedora 38                    | 18        | 0.82%   |
| Endless 3.9.5                | 18        | 0.82%   |
| Endless 3.9.1                | 18        | 0.82%   |
| Ubuntu 19.10                 | 17        | 0.78%   |
| OpenMandriva 23.01           | 17        | 0.78%   |
| Linux Mint 21.2              | 17        | 0.78%   |
| Ubuntu 21.04                 | 16        | 0.73%   |
| Linux Mint 20.3              | 16        | 0.73%   |
| Ubuntu 19.04                 | 15        | 0.68%   |
| Pop!_OS 20.10                | 15        | 0.68%   |
| Linux Mint 20.2              | 15        | 0.68%   |
| Fedora 34                    | 15        | 0.68%   |
| Endless 3.8.6                | 15        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 546       | 26.94%  |
| Endless       | 253       | 12.48%  |
| OpenMandriva  | 167       | 8.24%   |
| Fedora        | 126       | 6.22%   |
| Linux Mint    | 123       | 6.07%   |
| Pop!_OS       | 90        | 4.44%   |
| Debian        | 68        | 3.35%   |
| ROSA          | 67        | 3.31%   |
| Manjaro       | 66        | 3.26%   |
| Arch          | 65        | 3.21%   |
| BlackPanther  | 64        | 3.16%   |
| Zorin         | 57        | 2.81%   |
| KDE neon      | 33        | 1.63%   |
| ArcoLinux     | 32        | 1.58%   |
| Kubuntu       | 26        | 1.28%   |
| Xubuntu       | 25        | 1.23%   |
| openSUSE      | 25        | 1.23%   |
| Kali          | 16        | 0.79%   |
| Ubuntu Unity  | 14        | 0.69%   |
| Clear Linux   | 14        | 0.69%   |
| Gentoo        | 11        | 0.54%   |
| Elementary    | 11        | 0.54%   |
| Ubuntu MATE   | 10        | 0.49%   |
| SteamOS       | 9         | 0.44%   |
| EndeavourOS   | 9         | 0.44%   |
| MX            | 8         | 0.39%   |
| Peppermint    | 7         | 0.35%   |
| Garuda Linux  | 7         | 0.35%   |
| Nobara        | 6         | 0.3%    |
| Lubuntu       | 6         | 0.3%    |
| LMDE          | 6         | 0.3%    |
| Linux Lite    | 6         | 0.3%    |
| Xero          | 4         | 0.2%    |
| Ubuntu Budgie | 4         | 0.2%    |
| Raspbian      | 4         | 0.2%    |
| CentOS        | 4         | 0.2%    |
| Artix         | 4         | 0.2%    |
| Solus         | 3         | 0.15%   |
| RHEL          | 3         | 0.15%   |
| Ubuntu Studio | 2         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-14-generic                | 70        | 3.03%   |
| 5.4.0-42-generic                | 50        | 2.16%   |
| 4.18.16-desktop-1bP             | 47        | 2.03%   |
| 5.10.14-desktop-1omv4002        | 44        | 1.9%    |
| 5.16.7-desktop-1omv4003         | 43        | 1.86%   |
| 5.4.0-19-generic                | 32        | 1.38%   |
| 5.3.0-28-generic                | 26        | 1.12%   |
| 5.11.0-35-generic               | 19        | 0.82%   |
| 5.3.0-23-generic                | 18        | 0.78%   |
| 6.1.1-desktop-1omv2290          | 17        | 0.73%   |
| 4.18.0-15-generic               | 17        | 0.73%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 16        | 0.69%   |
| 5.6.14-desktop-2bP              | 15        | 0.65%   |
| 5.0.0-25-generic                | 15        | 0.65%   |
| 6.2.6-desktop-1omv2390          | 14        | 0.61%   |
| 5.4.0-40-generic                | 14        | 0.61%   |
| 5.15.0-58-generic               | 14        | 0.61%   |
| 5.3.0-46-generic                | 13        | 0.56%   |
| 5.0.0-20-generic                | 12        | 0.52%   |
| 6.2.0-36-generic                | 11        | 0.48%   |
| 5.4.0-52-generic                | 11        | 0.48%   |
| 5.4.0-29-generic                | 11        | 0.48%   |
| 5.4.0-26-generic                | 11        | 0.48%   |
| 5.3.0-19-generic                | 11        | 0.48%   |
| 5.15.0-52-generic               | 11        | 0.48%   |
| 6.4.11-desktop-1omv2390         | 10        | 0.43%   |
| 5.4.0-56-generic                | 10        | 0.43%   |
| 5.4.0-54-generic                | 10        | 0.43%   |
| 5.15.0-56-generic               | 10        | 0.43%   |
| 5.13.0-28-generic               | 10        | 0.43%   |
| 5.11.0-7620-generic             | 10        | 0.43%   |
| 5.11.0-43-generic               | 10        | 0.43%   |
| 5.0.0-37-generic                | 10        | 0.43%   |
| 4.15.0-15-generic               | 10        | 0.43%   |
| 5.8.0-50-generic                | 9         | 0.39%   |
| 5.4.0-7634-generic              | 9         | 0.39%   |
| 5.4.0-74-generic                | 9         | 0.39%   |
| 5.4.0-66-generic                | 9         | 0.39%   |
| 5.4.0-47-generic                | 9         | 0.39%   |
| 5.4.0-37-generic                | 9         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 309       | 13.9%   |
| 5.15.0  | 155       | 6.97%   |
| 5.8.0   | 151       | 6.79%   |
| 5.3.0   | 117       | 5.26%   |
| 5.11.0  | 102       | 4.59%   |
| 4.15.0  | 97        | 4.36%   |
| 5.0.0   | 80        | 3.6%    |
| 5.13.0  | 68        | 3.06%   |
| 6.2.0   | 55        | 2.47%   |
| 4.18.0  | 54        | 2.43%   |
| 5.19.0  | 51        | 2.29%   |
| 4.18.16 | 47        | 2.11%   |
| 5.10.14 | 45        | 2.02%   |
| 5.16.7  | 43        | 1.93%   |
| 5.10.0  | 39        | 1.75%   |
| 6.5.0   | 28        | 1.26%   |
| 6.1.0   | 26        | 1.17%   |
| 6.1.1   | 20        | 0.9%    |
| 6.2.6   | 19        | 0.85%   |
| 4.9.60  | 18        | 0.81%   |
| 5.6.14  | 16        | 0.72%   |
| 4.9.20  | 15        | 0.67%   |
| 6.4.11  | 13        | 0.58%   |
| 6.6.2   | 11        | 0.49%   |
| 6.5.5   | 11        | 0.49%   |
| 6.3.5   | 11        | 0.49%   |
| 4.19.0  | 11        | 0.49%   |
| 6.1.12  | 10        | 0.45%   |
| 4.13.0  | 10        | 0.45%   |
| 5.16.13 | 9         | 0.4%    |
| 4.9.76  | 8         | 0.36%   |
| 6.5.9   | 7         | 0.31%   |
| 6.5.6   | 7         | 0.31%   |
| 6.5.11  | 7         | 0.31%   |
| 6.0.11  | 7         | 0.31%   |
| 5.8.18  | 7         | 0.31%   |
| 6.0.0   | 6         | 0.27%   |
| 5.18.10 | 6         | 0.27%   |
| 5.17.0  | 6         | 0.27%   |
| 5.14.0  | 6         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 331       | 15.07%  |
| 5.15    | 202       | 9.2%    |
| 5.8     | 178       | 8.11%   |
| 5.3     | 127       | 5.78%   |
| 5.11    | 116       | 5.28%   |
| 5.10    | 107       | 4.87%   |
| 4.18    | 103       | 4.69%   |
| 4.15    | 97        | 4.42%   |
| 6.2     | 89        | 4.05%   |
| 5.0     | 85        | 3.87%   |
| 6.1     | 81        | 3.69%   |
| 5.16    | 76        | 3.46%   |
| 5.13    | 75        | 3.42%   |
| 5.19    | 70        | 3.19%   |
| 6.5     | 69        | 3.14%   |
| 4.9     | 50        | 2.28%   |
| 6.6     | 41        | 1.87%   |
| 6.0     | 36        | 1.64%   |
| 5.6     | 30        | 1.37%   |
| 6.4     | 28        | 1.28%   |
| 5.18    | 26        | 1.18%   |
| 6.3     | 23        | 1.05%   |
| 5.9     | 22        | 1%      |
| 5.17    | 22        | 1%      |
| 5.14    | 21        | 0.96%   |
| 5.12    | 18        | 0.82%   |
| 4.19    | 14        | 0.64%   |
| 5.7     | 10        | 0.46%   |
| 4.13    | 10        | 0.46%   |
| 4.1     | 8         | 0.36%   |
| 5.5     | 7         | 0.32%   |
| 5.2     | 5         | 0.23%   |
| 6.7     | 4         | 0.18%   |
| 5.1     | 4         | 0.18%   |
| 4.8     | 3         | 0.14%   |
| 4.12    | 2         | 0.09%   |
| 4.4     | 1         | 0.05%   |
| 4.17    | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.14    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1904      | 97.74%  |
| i686    | 34        | 1.75%   |
| armv7l  | 5         | 0.26%   |
| aarch64 | 5         | 0.26%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 946       | 46.51%  |
| KDE5             | 401       | 19.71%  |
| Unknown          | 233       | 11.46%  |
| XFCE             | 123       | 6.05%   |
| X-Cinnamon       | 95        | 4.67%   |
| KDE4             | 44        | 2.16%   |
| KDE              | 39        | 1.92%   |
| MATE             | 29        | 1.43%   |
| LXQt             | 21        | 1.03%   |
| Cinnamon         | 15        | 0.74%   |
| Unity            | 14        | 0.69%   |
| LXDE             | 14        | 0.69%   |
| i3               | 10        | 0.49%   |
| Pantheon         | 9         | 0.44%   |
| Budgie           | 5         | 0.25%   |
| sway             | 4         | 0.2%    |
| Hyprland         | 4         | 0.2%    |
| Openbox          | 3         | 0.15%   |
| GNOME Classic    | 3         | 0.15%   |
| Endless:GNOME    | 3         | 0.15%   |
| Deepin           | 3         | 0.15%   |
| xmonad           | 2         | 0.1%    |
| GNOME Flashback  | 2         | 0.1%    |
| awesome          | 2         | 0.1%    |
| ubuntu           | 1         | 0.05%   |
| sussy_bspwm      | 1         | 0.05%   |
| qtile            | 1         | 0.05%   |
| lightdm-xsession | 1         | 0.05%   |
| jwm              | 1         | 0.05%   |
| GNUstep          | 1         | 0.05%   |
| GNOME-Flashback  | 1         | 0.05%   |
| Enlightenment    | 1         | 0.05%   |
| dusk             | 1         | 0.05%   |
| bspwm            | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1490      | 74.5%   |
| Wayland     | 325       | 16.25%  |
| Unknown     | 152       | 7.6%    |
| Tty         | 32        | 1.6%    |
| Unspecified | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1040      | 51.16%  |
| SDDM    | 360       | 17.71%  |
| GDM3    | 198       | 9.74%   |
| GDM     | 190       | 9.35%   |
| LightDM | 150       | 7.38%   |
| KDM     | 44        | 2.16%   |
| TDM     | 41        | 2.02%   |
| XDM     | 4         | 0.2%    |
| SLiM    | 3         | 0.15%   |
| Ly      | 1         | 0.05%   |
| LXDM    | 1         | 0.05%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1212      | 60.54%  |
| ro_RO       | 334       | 16.68%  |
| Unknown     | 313       | 15.63%  |
| en_GB       | 42        | 2.1%    |
| C           | 33        | 1.65%   |
| hu_HU       | 17        | 0.85%   |
| it_IT       | 11        | 0.55%   |
| fr_FR       | 8         | 0.4%    |
| es_ES       | 7         | 0.35%   |
| de_DE       | 5         | 0.25%   |
| en_IL       | 3         | 0.15%   |
| ru_RU       | 2         | 0.1%    |
| en_IN       | 2         | 0.1%    |
| en_AG       | 2         | 0.1%    |
| uk_UA       | 1         | 0.05%   |
| nl_NL       | 1         | 0.05%   |
| fr_CH       | 1         | 0.05%   |
| es_MX       | 1         | 0.05%   |
| en_US.UTF8  | 1         | 0.05%   |
| en_US.UTF.8 | 1         | 0.05%   |
| en_US.utf-8 | 1         | 0.05%   |
| en_DE       | 1         | 0.05%   |
| en_CA       | 1         | 0.05%   |
| en_001      | 1         | 0.05%   |
| C.UTF8      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1033      | 51.91%  |
| BIOS | 957       | 48.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1410      | 70.46%  |
| Overlay | 195       | 9.75%   |
| Btrfs   | 160       | 8%      |
| Unknown | 154       | 7.7%    |
| Tmpfs   | 47        | 2.35%   |
| Xfs     | 20        | 1%      |
| Zfs     | 7         | 0.35%   |
| F2fs    | 3         | 0.15%   |
| Ext2    | 3         | 0.15%   |
| Jfs     | 1         | 0.05%   |
| Ext3    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1066      | 53.62%  |
| GPT     | 658       | 33.1%   |
| MBR     | 264       | 13.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1713      | 86.38%  |
| Yes       | 270       | 13.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1444      | 72.82%  |
| Yes       | 539       | 27.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 505       | 25.95%  |
| Lenovo                  | 314       | 16.14%  |
| Hewlett-Packard         | 235       | 12.08%  |
| Dell                    | 219       | 11.25%  |
| Acer                    | 147       | 7.55%   |
| Gigabyte Technology     | 139       | 7.14%   |
| MSI                     | 84        | 4.32%   |
| ASRock                  | 49        | 2.52%   |
| Toshiba                 | 27        | 1.39%   |
| Intel                   | 18        | 0.92%   |
| Fujitsu Siemens         | 14        | 0.72%   |
| Fujitsu                 | 14        | 0.72%   |
| Apple                   | 14        | 0.72%   |
| Complet                 | 13        | 0.67%   |
| Sony                    | 11        | 0.57%   |
| Unknown                 | 11        | 0.57%   |
| HUAWEI                  | 10        | 0.51%   |
| Medion                  | 9         | 0.46%   |
| Allview                 | 9         | 0.46%   |
| Valve                   | 8         | 0.41%   |
| Raspberry Pi Foundation | 8         | 0.41%   |
| Samsung Electronics     | 7         | 0.36%   |
| Pegatron                | 6         | 0.31%   |
| Foxconn                 | 6         | 0.31%   |
| Chuwi                   | 5         | 0.26%   |
| Packard Bell            | 4         | 0.21%   |
| Alienware               | 4         | 0.21%   |
| AZW                     | 3         | 0.15%   |
| WesternDigital          | 2         | 0.1%    |
| TUXEDO                  | 2         | 0.1%    |
| Timi                    | 2         | 0.1%    |
| Supermicro              | 2         | 0.1%    |
| IBM                     | 2         | 0.1%    |
| Google                  | 2         | 0.1%    |
| BESSTAR Tech            | 2         | 0.1%    |
| AMI                     | 2         | 0.1%    |
| ZOTAC                   | 1         | 0.05%   |
| WEIGO                   | 1         | 0.05%   |
| Visual Fan              | 1         | 0.05%   |
| VALE                    | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS X541NA                                | 17        | 0.87%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 17        | 0.87%   |
| ASUS All Series                            | 17        | 0.87%   |
| Unknown                                    | 14        | 0.72%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA     | 10        | 0.51%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 10        | 0.51%   |
| Acer Veriton L670G                         | 10        | 0.51%   |
| Valve Jupiter                              | 8         | 0.41%   |
| Gigabyte B450M DS3H                        | 7         | 0.36%   |
| Dell XPS 15 9530                           | 7         | 0.36%   |
| Complet MY8312                             | 7         | 0.36%   |
| ASUS X541UVK                               | 7         | 0.36%   |
| ASUS X541UAK                               | 7         | 0.36%   |
| ASUS X406UAR                               | 7         | 0.36%   |
| Lenovo Legion Y530-15ICH 81FV              | 6         | 0.31%   |
| ASUS VivoBook_ASUSLaptop X509FB_X509FB     | 6         | 0.31%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_A540MA | 6         | 0.31%   |
| ASUS PRIME A320M-K                         | 6         | 0.31%   |
| Lenovo V330-15IKB 81AX                     | 5         | 0.26%   |
| HP Notebook                                | 5         | 0.26%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 5         | 0.26%   |
| ASUS VivoBook_ASUSLaptop X509DAP_M509DA    | 5         | 0.26%   |
| ASUS VivoBook_ASUS Laptop X505ZA_A505ZA    | 5         | 0.26%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 5         | 0.26%   |
| ASUS GL552JX                               | 5         | 0.26%   |
| Allview Allbook H                          | 5         | 0.26%   |
| Acer Aspire A315-21G                       | 5         | 0.26%   |
| MSI MS-7996                                | 4         | 0.21%   |
| MSI MS-7721                                | 4         | 0.21%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 4         | 0.21%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 4         | 0.21%   |
| Lenovo G510 20238                          | 4         | 0.21%   |
| Gigabyte X470 AORUS ULTRA GAMING           | 4         | 0.21%   |
| Dell OptiPlex 7010                         | 4         | 0.21%   |
| Dell Latitude E6410                        | 4         | 0.21%   |
| Dell Inspiron 5558                         | 4         | 0.21%   |
| Dell Inspiron 1545                         | 4         | 0.21%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.21%   |
| ASUS X542UAR                               | 4         | 0.21%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA     | 4         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUS VivoBook           | 133       | 6.83%   |
| Acer Aspire             | 94        | 4.83%   |
| Lenovo ThinkPad         | 92        | 4.73%   |
| Lenovo IdeaPad          | 92        | 4.73%   |
| Dell Latitude           | 60        | 3.08%   |
| Dell Inspiron           | 55        | 2.83%   |
| HP Compaq               | 40        | 2.06%   |
| ASUS ROG                | 36        | 1.85%   |
| ASUS PRIME              | 35        | 1.8%    |
| HP EliteBook            | 33        | 1.7%    |
| Dell OptiPlex           | 32        | 1.64%   |
| HP ProBook              | 31        | 1.59%   |
| Lenovo Legion           | 29        | 1.49%   |
| Toshiba Satellite       | 26        | 1.34%   |
| HP Pavilion             | 26        | 1.34%   |
| ASUS ASUS               | 23        | 1.18%   |
| Lenovo ThinkCentre      | 21        | 1.08%   |
| Dell XPS                | 21        | 1.08%   |
| HP Laptop               | 19        | 0.98%   |
| ASUS TUF                | 18        | 0.92%   |
| ASUS X541NA             | 17        | 0.87%   |
| ASUS All                | 17        | 0.87%   |
| ASUS ZenBook            | 15        | 0.77%   |
| Acer Veriton            | 15        | 0.77%   |
| Dell Vostro             | 14        | 0.72%   |
| Unknown                 | 14        | 0.72%   |
| Dell Precision          | 13        | 0.67%   |
| Lenovo Yoga             | 11        | 0.57%   |
| HP 250                  | 11        | 0.57%   |
| Lenovo ThinkBook        | 10        | 0.51%   |
| Gigabyte B450M          | 9         | 0.46%   |
| Fujitsu Siemens ESPRIMO | 9         | 0.46%   |
| Allview Allbook         | 9         | 0.46%   |
| Acer Nitro              | 9         | 0.46%   |
| Valve Jupiter           | 8         | 0.41%   |
| RPi Raspberry           | 8         | 0.41%   |
| Dell PowerEdge          | 8         | 0.41%   |
| HP ZBook                | 7         | 0.36%   |
| HP OMEN                 | 7         | 0.36%   |
| Gigabyte X570           | 7         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 234       | 12.02%  |
| 2018    | 212       | 10.89%  |
| 2020    | 167       | 8.58%   |
| 2017    | 160       | 8.22%   |
| 2021    | 132       | 6.78%   |
| 2015    | 124       | 6.37%   |
| 2013    | 122       | 6.27%   |
| 2012    | 106       | 5.45%   |
| 2011    | 104       | 5.34%   |
| 2014    | 100       | 5.14%   |
| 2010    | 86        | 4.42%   |
| 2008    | 80        | 4.11%   |
| 2016    | 76        | 3.91%   |
| 2022    | 63        | 3.24%   |
| 2009    | 59        | 3.03%   |
| 2007    | 59        | 3.03%   |
| 2023    | 27        | 1.39%   |
| 2006    | 19        | 0.98%   |
| Unknown | 9         | 0.46%   |
| 2005    | 5         | 0.26%   |
| 2004    | 2         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1261      | 64.8%   |
| Desktop        | 595       | 30.58%  |
| All in one     | 25        | 1.28%   |
| Convertible    | 18        | 0.92%   |
| Mini pc        | 18        | 0.92%   |
| Tablet         | 10        | 0.51%   |
| Server         | 10        | 0.51%   |
| System on chip | 9         | 0.46%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1858      | 94.84%  |
| Enabled  | 101       | 5.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1944      | 99.9%   |
| Yes  | 2         | 0.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 501       | 25.25%  |
| 4.01-8.0        | 467       | 23.54%  |
| 8.01-16.0       | 352       | 17.74%  |
| 16.01-24.0      | 323       | 16.28%  |
| 32.01-64.0      | 155       | 7.81%   |
| 1.01-2.0        | 78        | 3.93%   |
| 64.01-256.0     | 49        | 2.47%   |
| 24.01-32.0      | 24        | 1.21%   |
| 2.01-3.0        | 18        | 0.91%   |
| 0.51-1.0        | 15        | 0.76%   |
| More than 256.0 | 2         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 786       | 36.12%  |
| 2.01-3.0    | 559       | 25.69%  |
| 3.01-4.0    | 260       | 11.95%  |
| 4.01-8.0    | 233       | 10.71%  |
| 0.51-1.0    | 202       | 9.28%   |
| 8.01-16.0   | 78        | 3.58%   |
| 0.01-0.5    | 45        | 2.07%   |
| 16.01-24.0  | 6         | 0.28%   |
| 32.01-64.0  | 3         | 0.14%   |
| 24.01-32.0  | 2         | 0.09%   |
| 64.01-256.0 | 2         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1293      | 64.46%  |
| 2      | 458       | 22.83%  |
| 3      | 132       | 6.58%   |
| 4      | 56        | 2.79%   |
| 5      | 28        | 1.4%    |
| 0      | 15        | 0.75%   |
| 6      | 8         | 0.4%    |
| 9      | 4         | 0.2%    |
| 7      | 4         | 0.2%    |
| 8      | 3         | 0.15%   |
| 24     | 1         | 0.05%   |
| 15     | 1         | 0.05%   |
| 14     | 1         | 0.05%   |
| 11     | 1         | 0.05%   |
| 10     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1229      | 62.67%  |
| Yes       | 732       | 37.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1612      | 82.67%  |
| No        | 338       | 17.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1508      | 77.02%  |
| No        | 450       | 22.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1230      | 62.34%  |
| No        | 743       | 37.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Romania | 1946      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Bucharest             | 624       | 30.17%  |
| Cluj-Napoca           | 135       | 6.53%   |
| Iasi                  | 96        | 4.64%   |
| Timișoara            | 79        | 3.82%   |
| Brasov                | 61        | 2.95%   |
| Târgu Mureş         | 60        | 2.9%    |
| Ploieşti             | 51        | 2.47%   |
| Sibiu                 | 41        | 1.98%   |
| Constanța            | 41        | 1.98%   |
| Oradea                | 34        | 1.64%   |
| Arad                  | 32        | 1.55%   |
| Piteşti              | 31        | 1.5%    |
| Baia Mare             | 27        | 1.31%   |
| Craiova               | 26        | 1.26%   |
| Galati                | 23        | 1.11%   |
| Popesti-Leordeni      | 21        | 1.02%   |
| Zalău                | 19        | 0.92%   |
| Râmnicu Vâlcea      | 19        | 0.92%   |
| Voluntari             | 18        | 0.87%   |
| Bacau                 | 18        | 0.87%   |
| Miercurea-Ciuc        | 16        | 0.77%   |
| Botosani              | 16        | 0.77%   |
| Targoviste            | 15        | 0.73%   |
| Satu Mare             | 15        | 0.73%   |
| Piatra Neamţ         | 14        | 0.68%   |
| Floresti              | 13        | 0.63%   |
| Reşiţa              | 12        | 0.58%   |
| Tulcea                | 11        | 0.53%   |
| Focşani              | 11        | 0.53%   |
| Deva                  | 11        | 0.53%   |
| Buzau                 | 11        | 0.53%   |
| Braila                | 11        | 0.53%   |
| Alba Iulia            | 11        | 0.53%   |
| Drobeta-Turnu Severin | 10        | 0.48%   |
| Târgu Jiu            | 9         | 0.44%   |
| Suceava               | 9         | 0.44%   |
| Mediaş               | 9         | 0.44%   |
| Sfantu Gheorghe       | 8         | 0.39%   |
| Roman                 | 8         | 0.39%   |
| Mangalia              | 8         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 402       | 589    | 14.53%  |
| Seagate                     | 396       | 617    | 14.31%  |
| Samsung Electronics         | 374       | 521    | 13.52%  |
| Kingston                    | 319       | 435    | 11.53%  |
| Toshiba                     | 180       | 227    | 6.51%   |
| SanDisk                     | 110       | 137    | 3.98%   |
| Unknown                     | 106       | 136    | 3.83%   |
| A-DATA Technology           | 102       | 127    | 3.69%   |
| Intel                       | 92        | 116    | 3.32%   |
| SK hynix                    | 83        | 111    | 3%      |
| Hitachi                     | 69        | 89     | 2.49%   |
| HGST                        | 63        | 82     | 2.28%   |
| Micron Technology           | 55        | 72     | 1.99%   |
| Crucial                     | 42        | 54     | 1.52%   |
| Patriot                     | 22        | 26     | 0.8%    |
| Kingston Technology Company | 20        | 22     | 0.72%   |
| Maxtor                      | 18        | 25     | 0.65%   |
| KIOXIA                      | 17        | 17     | 0.61%   |
| Hewlett-Packard             | 17        | 20     | 0.61%   |
| SPCC                        | 16        | 20     | 0.58%   |
| Phison                      | 16        | 19     | 0.58%   |
| XPG                         | 11        | 15     | 0.4%    |
| OCZ                         | 11        | 21     | 0.4%    |
| Gigabyte Technology         | 10        | 14     | 0.36%   |
| Transcend                   | 9         | 11     | 0.33%   |
| Silicon Motion              | 9         | 11     | 0.33%   |
| Phison Electronics          | 9         | 10     | 0.33%   |
| Netac                       | 9         | 11     | 0.33%   |
| FORESEE                     | 9         | 10     | 0.33%   |
| Corsair                     | 9         | 17     | 0.33%   |
| Realtek Semiconductor       | 8         | 9      | 0.29%   |
| Kingmax                     | 8         | 9      | 0.29%   |
| Fujitsu                     | 8         | 9      | 0.29%   |
| GOODRAM                     | 7         | 7      | 0.25%   |
| China                       | 7         | 7      | 0.25%   |
| Apple                       | 7         | 10     | 0.25%   |
| ADATA Technology            | 7         | 8      | 0.25%   |
| Team                        | 6         | 6      | 0.22%   |
| Plextor                     | 6         | 7      | 0.22%   |
| ASMT                        | 6         | 6      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 73        | 2.45%   |
| Seagate ST1000LM035-1RK172 1TB                     | 47        | 1.58%   |
| Toshiba MQ01ABF050 500GB                           | 46        | 1.54%   |
| Kingston SA400S37480G 480GB SSD                    | 37        | 1.24%   |
| Seagate ST500LT012-1DG142 500GB                    | 32        | 1.07%   |
| Kingston SA400S37120G 120GB SSD                    | 32        | 1.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 28        | 0.94%   |
| Seagate ST1000DM010-2EP102 1TB                     | 26        | 0.87%   |
| Kingston SV300S37A120G 120GB SSD                   | 25        | 0.84%   |
| Unknown MMC Card  32GB                             | 23        | 0.77%   |
| Toshiba MQ04ABF100 1TB                             | 22        | 0.74%   |
| Samsung NVMe SSD Drive 512GB                       | 21        | 0.7%    |
| HGST HTS721010A9E630 1TB                           | 21        | 0.7%    |
| Samsung SSD 860 EVO 500GB                          | 20        | 0.67%   |
| Samsung SSD 850 EVO 250GB                          | 20        | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 18        | 0.6%    |
| SanDisk NVMe SSD Drive 256GB                       | 18        | 0.6%    |
| A-DATA SU650 240GB SSD                             | 18        | 0.6%    |
| SanDisk NVMe SSD Drive 512GB                       | 17        | 0.57%   |
| Toshiba MQ01ABD100 1TB                             | 16        | 0.54%   |
| Seagate ST500DM002-1BD142 500GB                    | 16        | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 16        | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 15        | 0.5%    |
| Kingston SV300S37A240G 240GB SSD                   | 15        | 0.5%    |
| Seagate Expansion 1TB                              | 14        | 0.47%   |
| Kingston SUV400S37120G 120GB SSD                   | 13        | 0.44%   |
| SK hynix NVMe SSD Drive 512GB                      | 12        | 0.4%    |
| Samsung SSD 860 EVO 250GB                          | 12        | 0.4%    |
| Patriot Burst 120GB SSD                            | 12        | 0.4%    |
| Intel NVMe SSD Drive 512GB                         | 12        | 0.4%    |
| Toshiba DT01ACA050 500GB                           | 11        | 0.37%   |
| SK hynix HFS256G39TND-N210A 256GB SSD              | 11        | 0.37%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 11        | 0.37%   |
| HGST HTS545050A7E680 500GB                         | 11        | 0.37%   |
| WDC WD1600AAJS-22L7A0 160GB                        | 10        | 0.34%   |
| Unknown MMC Card  64GB                             | 10        | 0.34%   |
| Unknown MMC Card  128GB                            | 10        | 0.34%   |
| Seagate ST2000DM008-2FR102 2TB                     | 10        | 0.34%   |
| HGST HTS541010A9E680 1TB                           | 10        | 0.34%   |
| A-DATA SU630 240GB SSD                             | 10        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 390       | 607    | 35.58%  |
| WDC                 | 333       | 503    | 30.38%  |
| Toshiba             | 152       | 192    | 13.87%  |
| Hitachi             | 69        | 89     | 6.3%    |
| HGST                | 63        | 82     | 5.75%   |
| Samsung Electronics | 35        | 43     | 3.19%   |
| Maxtor              | 17        | 24     | 1.55%   |
| Unknown             | 9         | 10     | 0.82%   |
| Fujitsu             | 8         | 9      | 0.73%   |
| TO Exter            | 3         | 6      | 0.27%   |
| Apple               | 3         | 4      | 0.27%   |
| LaCie               | 2         | 8      | 0.18%   |
| IBM/Hitachi         | 2         | 2      | 0.18%   |
| Hewlett-Packard     | 2         | 3      | 0.18%   |
| ASMT                | 2         | 2      | 0.18%   |
| XrayDisk            | 1         | 1      | 0.09%   |
| Intenso             | 1         | 1      | 0.09%   |
| HGST HTS            | 1         | 1      | 0.09%   |
| External            | 1         | 1      | 0.09%   |
| ExcelStor           | 1         | 1      | 0.09%   |
| ASMT109x            | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 277       | 371    | 30.47%  |
| Samsung Electronics | 151       | 207    | 16.61%  |
| A-DATA Technology   | 93        | 118    | 10.23%  |
| SanDisk             | 44        | 59     | 4.84%   |
| Crucial             | 37        | 49     | 4.07%   |
| WDC                 | 30        | 34     | 3.3%    |
| Intel               | 30        | 33     | 3.3%    |
| SK hynix            | 26        | 36     | 2.86%   |
| Patriot             | 21        | 25     | 2.31%   |
| Micron Technology   | 21        | 25     | 2.31%   |
| SPCC                | 16        | 20     | 1.76%   |
| Hewlett-Packard     | 12        | 13     | 1.32%   |
| OCZ                 | 11        | 21     | 1.21%   |
| Toshiba             | 10        | 11     | 1.1%    |
| Netac               | 9         | 11     | 0.99%   |
| Gigabyte Technology | 9         | 13     | 0.99%   |
| FORESEE             | 9         | 10     | 0.99%   |
| Transcend           | 8         | 10     | 0.88%   |
| Kingmax             | 8         | 9      | 0.88%   |
| GOODRAM             | 7         | 7      | 0.77%   |
| Corsair             | 7         | 14     | 0.77%   |
| China               | 7         | 7      | 0.77%   |
| Team                | 6         | 6      | 0.66%   |
| Verbatim            | 4         | 6      | 0.44%   |
| Emtec               | 4         | 4      | 0.44%   |
| ASMT                | 4         | 4      | 0.44%   |
| Apacer              | 4         | 5      | 0.44%   |
| PNY                 | 3         | 4      | 0.33%   |
| LITEON              | 3         | 3      | 0.33%   |
| Teclast             | 2         | 2      | 0.22%   |
| Seagate             | 2         | 2      | 0.22%   |
| MicroFrom           | 2         | 2      | 0.22%   |
| LITEONIT            | 2         | 2      | 0.22%   |
| Lite-On             | 2         | 2      | 0.22%   |
| Intenso             | 2         | 2      | 0.22%   |
| Apple               | 2         | 3      | 0.22%   |
| Wibtek              | 1         | 1      | 0.11%   |
| W800S               | 1         | 1      | 0.11%   |
| Unknown             | 1         | 1      | 0.11%   |
| sobetter            | 1         | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 948       | 1590   | 38.13%  |
| SSD     | 807       | 1179   | 32.46%  |
| NVMe    | 625       | 880    | 25.14%  |
| MMC     | 89        | 115    | 3.58%   |
| Unknown | 17        | 22     | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1416      | 2660   | 63.84%  |
| NVMe | 624       | 879    | 28.13%  |
| SAS  | 89        | 132    | 4.01%   |
| MMC  | 89        | 115    | 4.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1102      | 1751   | 62.65%  |
| 0.51-1.0   | 493       | 686    | 28.03%  |
| 1.01-2.0   | 98        | 155    | 5.57%   |
| 3.01-4.0   | 26        | 49     | 1.48%   |
| 4.01-10.0  | 20        | 67     | 1.14%   |
| 2.01-3.0   | 17        | 55     | 0.97%   |
| 10.01-20.0 | 3         | 6      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 575       | 27.68%  |
| 251-500        | 442       | 21.28%  |
| 501-1000       | 334       | 16.08%  |
| 1-20           | 192       | 9.24%   |
| 51-100         | 141       | 6.79%   |
| 1001-2000      | 118       | 5.68%   |
| 21-50          | 87        | 4.19%   |
| Unknown        | 81        | 3.9%    |
| More than 3000 | 55        | 2.65%   |
| 2001-3000      | 52        | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 841       | 39.24%  |
| 21-50          | 432       | 20.16%  |
| 101-250        | 234       | 10.92%  |
| 51-100         | 222       | 10.36%  |
| 251-500        | 134       | 6.25%   |
| 501-1000       | 109       | 5.09%   |
| Unknown        | 81        | 3.78%   |
| 1001-2000      | 59        | 2.75%   |
| More than 3000 | 20        | 0.93%   |
| 2001-3000      | 11        | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Hitachi HTS725032A7E630 320GB        | 7         | 7      | 3.11%   |
| HGST HTS541010A9E680 1TB             | 5         | 5      | 2.22%   |
| HGST HTS545050A7E680 500GB           | 4         | 4      | 1.78%   |
| WDC WD5000AAKX-001CA0 500GB          | 3         | 3      | 1.33%   |
| WDC WD3200AAJS-60Z0A0 320GB          | 3         | 6      | 1.33%   |
| Seagate ST9500420AS 500GB            | 3         | 3      | 1.33%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 3      | 1.33%   |
| Seagate ST3500312CS 500GB            | 3         | 3      | 1.33%   |
| Maxtor STM3250310AS 250GB            | 3         | 4      | 1.33%   |
| HGST HTS725050A7E630 500GB           | 3         | 4      | 1.33%   |
| WDC WD5000AADS-00S9B0 500GB          | 2         | 2      | 0.89%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2         | 2      | 0.89%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB | 2         | 2      | 0.89%   |
| Toshiba MQ01ABF050 500GB             | 2         | 2      | 0.89%   |
| Seagate STM3250318AS 250GB           | 2         | 3      | 0.89%   |
| Seagate ST95005620AS 500GB           | 2         | 5      | 0.89%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 0.89%   |
| Seagate ST9160821AS 160GB            | 2         | 2      | 0.89%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 3      | 0.89%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 2      | 0.89%   |
| Seagate ST3500320AS 500GB            | 2         | 3      | 0.89%   |
| Seagate ST3250318AS 250GB            | 2         | 3      | 0.89%   |
| Seagate ST1000LX015-1U7172 1TB       | 2         | 2      | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 2      | 0.89%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 3      | 0.89%   |
| OCZ ARC100 240GB SSD                 | 2         | 2      | 0.89%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 2      | 0.89%   |
| Hitachi HTS725032A9A364 320GB        | 2         | 3      | 0.89%   |
| Hitachi HTS545016B9A300 160GB        | 2         | 2      | 0.89%   |
| Hitachi HDS721616PLA380 160GB        | 2         | 2      | 0.89%   |
| Apacer 16GB SATA Flash Drive SSD     | 2         | 3      | 0.89%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 1      | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 1      | 0.44%   |
| WDC WD7500BPVT-60HXZT3 752GB         | 1         | 2      | 0.44%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 1      | 0.44%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1      | 0.44%   |
| WDC WD5000BPKT-60PK4T0 500GB         | 1         | 2      | 0.44%   |
| WDC WD5000BEVT-60A0RT0 500GB         | 1         | 1      | 0.44%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1         | 1      | 0.44%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 1      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 69     | 25%     |
| WDC                 | 51        | 77     | 23.61%  |
| Hitachi             | 24        | 28     | 11.11%  |
| Samsung Electronics | 16        | 18     | 7.41%   |
| HGST                | 15        | 16     | 6.94%   |
| Toshiba             | 11        | 12     | 5.09%   |
| Maxtor              | 7         | 9      | 3.24%   |
| Kingston            | 7         | 9      | 3.24%   |
| SK hynix            | 6         | 6      | 2.78%   |
| Intel               | 4         | 4      | 1.85%   |
| Hewlett-Packard     | 3         | 3      | 1.39%   |
| Fujitsu             | 3         | 3      | 1.39%   |
| Patriot             | 2         | 2      | 0.93%   |
| OCZ                 | 2         | 2      | 0.93%   |
| Apacer              | 2         | 3      | 0.93%   |
| A-DATA Technology   | 2         | 2      | 0.93%   |
| Teclast             | 1         | 1      | 0.46%   |
| SanDisk             | 1         | 1      | 0.46%   |
| Plextor             | 1         | 1      | 0.46%   |
| Micron Technology   | 1         | 1      | 0.46%   |
| LITEONIT            | 1         | 1      | 0.46%   |
| Crucial             | 1         | 1      | 0.46%   |
| Corsair             | 1         | 7      | 0.46%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 69     | 31.21%  |
| WDC                 | 47        | 73     | 27.17%  |
| Hitachi             | 24        | 28     | 13.87%  |
| HGST                | 15        | 16     | 8.67%   |
| Samsung Electronics | 12        | 14     | 6.94%   |
| Toshiba             | 11        | 12     | 6.36%   |
| Maxtor              | 7         | 9      | 4.05%   |
| Fujitsu             | 3         | 3      | 1.73%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 161       | 224    | 78.92%  |
| SSD  | 41        | 50     | 20.1%   |
| NVMe | 2         | 2      | 0.98%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60KA9T0 320GB | 1         | 1      | 33.33%  |
| WDC WD2500BEVS-22UST0 250GB  | 1         | 1      | 33.33%  |
| Seagate ST3160215A 160GB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1213      | 2228   | 56.79%  |
| Works    | 725       | 1279   | 33.94%  |
| Malfunc  | 195       | 276    | 9.13%   |
| Failed   | 3         | 3      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1400      | 57.24%  |
| AMD                              | 320       | 13.08%  |
| Samsung Electronics              | 212       | 8.67%   |
| SanDisk                          | 107       | 4.37%   |
| Kingston Technology Company      | 68        | 2.78%   |
| SK hynix                         | 56        | 2.29%   |
| Micron Technology                | 34        | 1.39%   |
| ASMedia Technology               | 28        | 1.14%   |
| Phison Electronics               | 25        | 1.02%   |
| ADATA Technology                 | 25        | 1.02%   |
| Toshiba America Info Systems     | 19        | 0.78%   |
| KIOXIA                           | 19        | 0.78%   |
| Nvidia                           | 17        | 0.7%    |
| Marvell Technology Group         | 17        | 0.7%    |
| Realtek Semiconductor            | 15        | 0.61%   |
| JMicron Technology               | 15        | 0.61%   |
| Silicon Motion                   | 14        | 0.57%   |
| Micron/Crucial Technology        | 8         | 0.33%   |
| Lite-On Technology               | 6         | 0.25%   |
| Broadcom / LSI                   | 6         | 0.25%   |
| VIA Technologies                 | 5         | 0.2%    |
| Silicon Integrated Systems [SiS] | 5         | 0.2%    |
| Solidigm                         | 4         | 0.16%   |
| Silicon Image                    | 4         | 0.16%   |
| LSI Logic / Symbios Logic        | 4         | 0.16%   |
| Union Memory (Shenzhen)          | 2         | 0.08%   |
| Solid State Storage Technology   | 2         | 0.08%   |
| Seagate Technology               | 2         | 0.08%   |
| Lenovo                           | 2         | 0.08%   |
| Hewlett-Packard                  | 2         | 0.08%   |
| Integrated Technology Express    | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 225       | 8.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 121       | 4.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 96        | 3.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 92        | 3.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 92        | 3.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 72        | 2.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 70        | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 56        | 2%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 51        | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 51        | 1.82%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 50        | 1.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 45        | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 41        | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 39        | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                         | 39        | 1.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 38        | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 38        | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 35        | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 35        | 1.25%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 31        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 31        | 1.11%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 30        | 1.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 30        | 1.07%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 29        | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 29        | 1.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 29        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 29        | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 29        | 1.04%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 28        | 1%      |
| Intel SSD 660P Series                                                          | 27        | 0.97%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 26        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 26        | 0.93%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 25        | 0.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 24        | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 24        | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 24        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 24        | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 23        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 23        | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                            | 22        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1428      | 56.89%  |
| NVMe | 633       | 25.22%  |
| IDE  | 243       | 9.68%   |
| RAID | 198       | 7.89%   |
| SAS  | 8         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1516      | 77.9%   |
| AMD    | 420       | 21.58%  |
| ARM    | 10        | 0.51%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 43        | 2.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 1.54%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 28        | 1.44%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 26        | 1.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 22        | 1.13%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 19        | 0.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 0.92%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 0.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 17        | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 16        | 0.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 0.82%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 15        | 0.77%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 15        | 0.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 0.72%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.67%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 12        | 0.62%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 12        | 0.62%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 12        | 0.62%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 12        | 0.62%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 11        | 0.56%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 10        | 0.51%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 10        | 0.51%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 10        | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.51%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 10        | 0.51%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 10        | 0.51%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 0.51%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.51%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 0.51%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 9         | 0.46%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 9         | 0.46%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 9         | 0.46%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.41%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 8         | 0.41%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 8         | 0.41%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.41%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 8         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 364       | 18.69%  |
| Intel Core i7           | 362       | 18.58%  |
| Intel Core i3           | 197       | 10.11%  |
| Intel Celeron           | 156       | 8.01%   |
| Other                   | 135       | 6.93%   |
| AMD Ryzen 5             | 103       | 5.29%   |
| Intel Core 2 Duo        | 93        | 4.77%   |
| AMD Ryzen 7             | 92        | 4.72%   |
| Intel Pentium           | 61        | 3.13%   |
| AMD Ryzen 3             | 34        | 1.75%   |
| Intel Xeon              | 30        | 1.54%   |
| AMD Ryzen 9             | 30        | 1.54%   |
| Intel Atom              | 28        | 1.44%   |
| Intel Pentium Dual-Core | 22        | 1.13%   |
| Intel Core 2 Quad       | 18        | 0.92%   |
| AMD A4                  | 18        | 0.92%   |
| Intel Core i9           | 16        | 0.82%   |
| AMD FX                  | 16        | 0.82%   |
| Intel Core 2            | 14        | 0.72%   |
| AMD A8                  | 13        | 0.67%   |
| Intel Genuine           | 11        | 0.56%   |
| Intel Pentium Dual      | 9         | 0.46%   |
| AMD Ryzen 7 PRO         | 8         | 0.41%   |
| AMD Phenom II X4        | 8         | 0.41%   |
| AMD E                   | 7         | 0.36%   |
| AMD Ryzen Threadripper  | 6         | 0.31%   |
| AMD Athlon              | 6         | 0.31%   |
| AMD A6                  | 6         | 0.31%   |
| Intel Pentium Silver    | 5         | 0.26%   |
| AMD E2                  | 5         | 0.26%   |
| Intel Celeron M         | 4         | 0.21%   |
| ARM BCM                 | 4         | 0.21%   |
| AMD Sempron             | 4         | 0.21%   |
| AMD Athlon II X4        | 4         | 0.21%   |
| AMD A10                 | 4         | 0.21%   |
| AMD Turion 64 X2 Mobile | 3         | 0.15%   |
| AMD Athlon II X3        | 3         | 0.15%   |
| AMD Athlon 64 X2        | 3         | 0.15%   |
| Intel Pentium Gold      | 2         | 0.1%    |
| Intel Pentium D         | 2         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 834       | 42.84%  |
| 4       | 674       | 34.62%  |
| 6       | 160       | 8.22%   |
| 8       | 147       | 7.55%   |
| 1       | 42        | 2.16%   |
| 12      | 26        | 1.34%   |
| 10      | 18        | 0.92%   |
| 16      | 11        | 0.56%   |
| 14      | 10        | 0.51%   |
| 3       | 10        | 0.51%   |
| 24      | 5         | 0.26%   |
| 32      | 4         | 0.21%   |
| 64      | 1         | 0.05%   |
| 36      | 1         | 0.05%   |
| 28      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |
| 18      | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1929      | 99.13%  |
| 2       | 16        | 0.82%   |
| Unknown | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1269      | 65.18%  |
| 1       | 675       | 34.67%  |
| 4       | 2         | 0.1%    |
| Unknown | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1850      | 94.73%  |
| Unknown        | 89        | 4.56%   |
| 32-bit         | 14        | 0.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 518       | 25.66%  |
| 0x206a7    | 90        | 4.46%   |
| 0x306c3    | 89        | 4.41%   |
| 0x306a9    | 83        | 4.11%   |
| 0x1067a    | 63        | 3.12%   |
| 0x806ea    | 61        | 3.02%   |
| 0x906ea    | 57        | 2.82%   |
| 0x806ec    | 56        | 2.77%   |
| 0x706a1    | 51        | 2.53%   |
| 0x906e9    | 45        | 2.23%   |
| 0x40651    | 39        | 1.93%   |
| 0x806c1    | 35        | 1.73%   |
| 0x506e3    | 35        | 1.73%   |
| 0x506c9    | 34        | 1.68%   |
| 0x806e9    | 33        | 1.63%   |
| 0x20655    | 32        | 1.58%   |
| 0x306d4    | 29        | 1.44%   |
| 0x0a50000c | 26        | 1.29%   |
| 0x10676    | 25        | 1.24%   |
| 0x806eb    | 24        | 1.19%   |
| 0x406e3    | 24        | 1.19%   |
| 0x08108109 | 23        | 1.14%   |
| 0x6fd      | 20        | 0.99%   |
| 0x010000c8 | 20        | 0.99%   |
| 0x706e5    | 19        | 0.94%   |
| 0x406c4    | 19        | 0.94%   |
| 0x08108102 | 18        | 0.89%   |
| 0x08600106 | 16        | 0.79%   |
| 0x08701021 | 14        | 0.69%   |
| 0xa0652    | 13        | 0.64%   |
| 0x08600104 | 13        | 0.64%   |
| 0x0810100b | 13        | 0.64%   |
| 0x906ed    | 12        | 0.59%   |
| 0x6fb      | 12        | 0.59%   |
| 0x06001119 | 12        | 0.59%   |
| 0x706a8    | 11        | 0.54%   |
| 0x406c3    | 11        | 0.54%   |
| 0x806d1    | 10        | 0.5%    |
| 0x08701013 | 10        | 0.5%    |
| 0x0800820d | 10        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 374       | 19.16%  |
| Haswell          | 177       | 9.07%   |
| SandyBridge      | 114       | 5.84%   |
| Penryn           | 107       | 5.48%   |
| IvyBridge        | 105       | 5.38%   |
| Skylake          | 84        | 4.3%    |
| Zen 2            | 78        | 4%      |
| Unknown          | 76        | 3.89%   |
| Goldmont plus    | 72        | 3.69%   |
| Zen+             | 67        | 3.43%   |
| Core             | 64        | 3.28%   |
| Zen 3            | 61        | 3.13%   |
| Westmere         | 59        | 3.02%   |
| Silvermont       | 53        | 2.72%   |
| TigerLake        | 50        | 2.56%   |
| Broadwell        | 45        | 2.31%   |
| Zen              | 42        | 2.15%   |
| Goldmont         | 41        | 2.1%    |
| IceLake          | 37        | 1.9%    |
| CometLake        | 37        | 1.9%    |
| Alderlake Hybrid | 35        | 1.79%   |
| K10              | 30        | 1.54%   |
| Piledriver       | 29        | 1.49%   |
| Excavator        | 21        | 1.08%   |
| K8 Hammer        | 14        | 0.72%   |
| P6               | 12        | 0.61%   |
| Nehalem          | 12        | 0.61%   |
| Bonnell          | 11        | 0.56%   |
| Bobcat           | 9         | 0.46%   |
| Puma             | 8         | 0.41%   |
| NetBurst         | 6         | 0.31%   |
| Tremont          | 5         | 0.26%   |
| K10 Llano        | 5         | 0.26%   |
| K8 & K10 hybrid  | 4         | 0.2%    |
| Jaguar           | 4         | 0.2%    |
| Steamroller      | 3         | 0.15%   |
| Bulldozer        | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1226      | 51.21%  |
| Nvidia                           | 656       | 27.4%   |
| AMD                              | 495       | 20.68%  |
| Matrox Electronics Systems       | 7         | 0.29%   |
| Silicon Integrated Systems [SiS] | 5         | 0.21%   |
| ASPEED Technology                | 4         | 0.17%   |
| VIA Technologies                 | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 86        | 3.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 69        | 2.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 66        | 2.69%   |
| Intel UHD Graphics 620                                                                   | 64        | 2.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 61        | 2.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 54        | 2.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 50        | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 49        | 1.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 48        | 1.95%   |
| Intel HD Graphics 620                                                                    | 45        | 1.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 43        | 1.75%   |
| Intel HD Graphics 630                                                                    | 40        | 1.63%   |
| Intel HD Graphics 5500                                                                   | 40        | 1.63%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 38        | 1.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 37        | 1.51%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 36        | 1.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 35        | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 1.42%   |
| Intel HD Graphics 530                                                                    | 34        | 1.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 30        | 1.22%   |
| Intel HD Graphics 500                                                                    | 30        | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 27        | 1.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 1.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 25        | 1.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 25        | 1.02%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 24        | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 23        | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 22        | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 0.85%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 18        | 0.73%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 18        | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 0.69%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 0.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 16        | 0.65%   |
| Nvidia GP108M [GeForce MX150]                                                            | 15        | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.61%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 15        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 812       | 41.58%  |
| 1 x AMD        | 356       | 18.23%  |
| Intel + Nvidia | 329       | 16.85%  |
| 1 x Nvidia     | 277       | 14.18%  |
| Intel + AMD    | 62        | 3.17%   |
| AMD + Nvidia   | 49        | 2.51%   |
| 2 x AMD        | 27        | 1.38%   |
| 2 x Intel      | 12        | 0.61%   |
| Other          | 10        | 0.51%   |
| 1 x Matrox     | 7         | 0.36%   |
| 1 x SiS        | 5         | 0.26%   |
| 1 x ASPEED     | 3         | 0.15%   |
| 2 x Nvidia     | 2         | 0.1%    |
| 1 x VIA        | 1         | 0.05%   |
| AMD + ASPEED   | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1536      | 77.97%  |
| Proprietary | 377       | 19.14%  |
| Unknown     | 57        | 2.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1134      | 56.39%  |
| 1.01-2.0   | 263       | 13.08%  |
| 0.01-0.5   | 212       | 10.54%  |
| 3.01-4.0   | 138       | 6.86%   |
| 0.51-1.0   | 124       | 6.17%   |
| 7.01-8.0   | 64        | 3.18%   |
| 5.01-6.0   | 42        | 2.09%   |
| 8.01-16.0  | 16        | 0.8%    |
| 2.01-3.0   | 12        | 0.6%    |
| 16.01-24.0 | 5         | 0.25%   |
| 0          | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 255       | 12.34%  |
| Samsung Electronics     | 251       | 12.14%  |
| Chimei Innolux          | 231       | 11.18%  |
| BOE                     | 228       | 11.03%  |
| LG Display              | 193       | 9.34%   |
| Dell                    | 150       | 7.26%   |
| Goldstar                | 103       | 4.98%   |
| Philips                 | 75        | 3.63%   |
| PANDA                   | 51        | 2.47%   |
| BenQ                    | 46        | 2.23%   |
| Lenovo                  | 42        | 2.03%   |
| Chi Mei Optoelectronics | 38        | 1.84%   |
| Hewlett-Packard         | 36        | 1.74%   |
| Acer                    | 35        | 1.69%   |
| AOC                     | 34        | 1.64%   |
| Sharp                   | 32        | 1.55%   |
| Ancor Communications    | 32        | 1.55%   |
| Fujitsu Siemens         | 21        | 1.02%   |
| ASUSTek Computer        | 18        | 0.87%   |
| LG Philips              | 15        | 0.73%   |
| LG Electronics          | 12        | 0.58%   |
| Eizo                    | 11        | 0.53%   |
| Unknown                 | 10        | 0.48%   |
| Sony                    | 10        | 0.48%   |
| CSO                     | 10        | 0.48%   |
| Apple                   | 10        | 0.48%   |
| InfoVision              | 8         | 0.39%   |
| Vestel Elektronik       | 7         | 0.34%   |
| KTC                     | 7         | 0.34%   |
| Lenovo Group Limited    | 6         | 0.29%   |
| ViewSonic               | 5         | 0.24%   |
| Toshiba                 | 5         | 0.24%   |
| Panasonic               | 5         | 0.24%   |
| Valve                   | 4         | 0.19%   |
| LGD                     | 4         | 0.19%   |
| InnoLux Display         | 4         | 0.19%   |
| Iiyama                  | 4         | 0.19%   |
| HannStar                | 4         | 0.19%   |
| CPT                     | 4         | 0.19%   |
| Belinea                 | 3         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 27        | 1.27%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 26        | 1.22%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 22        | 1.04%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.99%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 0.8%    |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 15        | 0.71%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 12        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 11        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.52%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 11        | 0.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 10        | 0.47%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 10        | 0.47%   |
| Goldstar E2250 GSM578D 1920x1080 477x268mm 21.5-inch                     | 10        | 0.47%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 9         | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 9         | 0.42%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 8         | 0.38%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 8         | 0.38%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 8         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 8         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 8         | 0.38%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 8         | 0.38%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch     | 7         | 0.33%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                  | 7         | 0.33%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 7         | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.33%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 7         | 0.33%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 7         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch    | 6         | 0.28%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 6         | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 6         | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 6         | 0.28%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 6         | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.28%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 6         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 928       | 46.8%   |
| 1366x768 (WXGA)    | 413       | 20.83%  |
| 3840x2160 (4K)     | 88        | 4.44%   |
| 1280x1024 (SXGA)   | 78        | 3.93%   |
| 2560x1440 (QHD)    | 70        | 3.53%   |
| 1600x900 (HD+)     | 60        | 3.03%   |
| 1680x1050 (WSXGA+) | 50        | 2.52%   |
| 1920x1200 (WUXGA)  | 43        | 2.17%   |
| 1280x800 (WXGA)    | 42        | 2.12%   |
| 1440x900 (WXGA+)   | 28        | 1.41%   |
| Unknown            | 21        | 1.06%   |
| 1360x768           | 16        | 0.81%   |
| 2560x1600          | 15        | 0.76%   |
| 3440x1440          | 14        | 0.71%   |
| 2880x1800          | 14        | 0.71%   |
| 2560x1080          | 14        | 0.71%   |
| 3200x1800 (QHD+)   | 11        | 0.55%   |
| 1024x600           | 8         | 0.4%    |
| 800x1280           | 7         | 0.35%   |
| 3840x1080          | 7         | 0.35%   |
| 2160x1440          | 7         | 0.35%   |
| 1024x768 (XGA)     | 7         | 0.35%   |
| 3840x2400          | 3         | 0.15%   |
| 1600x1200          | 3         | 0.15%   |
| 5760x2160          | 2         | 0.1%    |
| 5120x1440          | 2         | 0.1%    |
| 3840x1600          | 2         | 0.1%    |
| 3200x2000          | 2         | 0.1%    |
| 1920x540           | 2         | 0.1%    |
| 1400x1050          | 2         | 0.1%    |
| 1280x720 (HD)      | 2         | 0.1%    |
| 800x600            | 1         | 0.05%   |
| 7680x1440          | 1         | 0.05%   |
| 6400x1440          | 1         | 0.05%   |
| 6000x1440          | 1         | 0.05%   |
| 4960x1080          | 1         | 0.05%   |
| 3926x1440          | 1         | 0.05%   |
| 3840x2524          | 1         | 0.05%   |
| 3600x1200          | 1         | 0.05%   |
| 3360x1080          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 766       | 37.4%   |
| 24      | 141       | 6.88%   |
| 14      | 141       | 6.88%   |
| 13      | 137       | 6.69%   |
| 17      | 124       | 6.05%   |
| 21      | 116       | 5.66%   |
| 27      | 104       | 5.08%   |
| 23      | 103       | 5.03%   |
| Unknown | 78        | 3.81%   |
| 19      | 55        | 2.69%   |
| 22      | 35        | 1.71%   |
| 18      | 29        | 1.42%   |
| 31      | 27        | 1.32%   |
| 34      | 25        | 1.22%   |
| 16      | 22        | 1.07%   |
| 12      | 20        | 0.98%   |
| 84      | 17        | 0.83%   |
| 20      | 13        | 0.63%   |
| 54      | 11        | 0.54%   |
| 11      | 10        | 0.49%   |
| 10      | 9         | 0.44%   |
| 40      | 8         | 0.39%   |
| 32      | 8         | 0.39%   |
| 72      | 6         | 0.29%   |
| 65      | 6         | 0.29%   |
| 26      | 5         | 0.24%   |
| 7       | 4         | 0.2%    |
| 28      | 3         | 0.15%   |
| 25      | 3         | 0.15%   |
| 3       | 3         | 0.15%   |
| 52      | 2         | 0.1%    |
| 46      | 2         | 0.1%    |
| 43      | 2         | 0.1%    |
| 42      | 2         | 0.1%    |
| 37      | 2         | 0.1%    |
| 29      | 2         | 0.1%    |
| 8       | 2         | 0.1%    |
| 142     | 1         | 0.05%   |
| 86      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1012      | 49.93%  |
| 501-600        | 328       | 16.18%  |
| 401-500        | 203       | 10.01%  |
| 351-400        | 162       | 7.99%   |
| 201-300        | 98        | 4.83%   |
| Unknown        | 78        | 3.85%   |
| 601-700        | 41        | 2.02%   |
| 701-800        | 33        | 1.63%   |
| 1001-1500      | 25        | 1.23%   |
| 1501-2000      | 23        | 1.13%   |
| 801-900        | 10        | 0.49%   |
| 1-100          | 7         | 0.35%   |
| 901-1000       | 4         | 0.2%    |
| 101-200        | 2         | 0.1%    |
| More than 2000 | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1492      | 78.82%  |
| 16/10   | 193       | 10.2%   |
| 5/4     | 69        | 3.65%   |
| Unknown | 67        | 3.54%   |
| 21/9    | 28        | 1.48%   |
| 4/3     | 15        | 0.79%   |
| 3/2     | 14        | 0.74%   |
| 6/5     | 8         | 0.42%   |
| 0.67    | 4         | 0.21%   |
| 32/9    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 767       | 37.67%  |
| 201-250        | 319       | 15.67%  |
| 81-90          | 230       | 11.3%   |
| 301-350        | 108       | 5.3%    |
| 151-200        | 98        | 4.81%   |
| 121-130        | 91        | 4.47%   |
| Unknown        | 78        | 3.83%   |
| 351-500        | 62        | 3.05%   |
| 251-300        | 49        | 2.41%   |
| 141-150        | 48        | 2.36%   |
| More than 1000 | 46        | 2.26%   |
| 71-80          | 45        | 2.21%   |
| 61-70          | 18        | 0.88%   |
| 111-120        | 17        | 0.83%   |
| 501-1000       | 17        | 0.83%   |
| 51-60          | 10        | 0.49%   |
| 131-140        | 10        | 0.49%   |
| 41-50          | 9         | 0.44%   |
| 1-40           | 9         | 0.44%   |
| 91-100         | 5         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 618       | 30.75%  |
| 101-120       | 577       | 28.71%  |
| 51-100        | 563       | 28.01%  |
| 161-240       | 93        | 4.63%   |
| Unknown       | 78        | 3.88%   |
| More than 240 | 44        | 2.19%   |
| 1-50          | 37        | 1.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1659      | 83.45%  |
| 2     | 227       | 11.42%  |
| 0     | 73        | 3.67%   |
| 3     | 27        | 1.36%   |
| 4     | 2         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1120      | 39.01%  |
| Intel                             | 853       | 29.71%  |
| Qualcomm Atheros                  | 328       | 11.42%  |
| Broadcom                          | 150       | 5.22%   |
| MediaTek                          | 72        | 2.51%   |
| TP-Link                           | 62        | 2.16%   |
| Broadcom Limited                  | 31        | 1.08%   |
| Ralink                            | 24        | 0.84%   |
| Ralink Technology                 | 23        | 0.8%    |
| Marvell Technology Group          | 23        | 0.8%    |
| Nvidia                            | 14        | 0.49%   |
| ASUSTek Computer                  | 14        | 0.49%   |
| Huawei Technologies               | 13        | 0.45%   |
| ASIX Electronics                  | 12        | 0.42%   |
| Samsung Electronics               | 11        | 0.38%   |
| D-Link                            | 10        | 0.35%   |
| Xiaomi                            | 9         | 0.31%   |
| Ericsson Business Mobile Networks | 7         | 0.24%   |
| Aquantia                          | 7         | 0.24%   |
| Qualcomm Atheros Communications   | 6         | 0.21%   |
| Hewlett-Packard                   | 6         | 0.21%   |
| ZTE WCDMA Technologies MSM        | 5         | 0.17%   |
| Microsoft                         | 5         | 0.17%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.14%   |
| Lenovo                            | 4         | 0.14%   |
| JMicron Technology                | 4         | 0.14%   |
| Google                            | 4         | 0.14%   |
| Edimax Technology                 | 4         | 0.14%   |
| VIA Technologies                  | 3         | 0.1%    |
| Sierra Wireless                   | 3         | 0.1%    |
| Tenda                             | 2         | 0.07%   |
| Standard Microsystems             | 2         | 0.07%   |
| Qualcomm                          | 2         | 0.07%   |
| IMC Networks                      | 2         | 0.07%   |
| Giga-Byte Technology              | 2         | 0.07%   |
| Fibocom                           | 2         | 0.07%   |
| DisplayLink                       | 2         | 0.07%   |
| Dell                              | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| Belkin Components                 | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 718       | 21.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 136       | 4.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 89        | 2.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 81        | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 69        | 2.06%   |
| Intel Wi-Fi 6 AX200                                                    | 67        | 2%      |
| Intel Wireless 8265 / 8275                                             | 65        | 1.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 57        | 1.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 55        | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 48        | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 42        | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 42        | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 41        | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 40        | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                      | 37        | 1.1%    |
| Intel Wi-Fi 6 AX201                                                    | 36        | 1.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 36        | 1.07%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 33        | 0.98%   |
| Intel I211 Gigabit Network Connection                                  | 33        | 0.98%   |
| Intel Wireless 7260                                                    | 32        | 0.95%   |
| Intel Ethernet Connection I217-LM                                      | 31        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 30        | 0.89%   |
| Intel Wireless 7265                                                    | 30        | 0.89%   |
| Intel Ethernet Connection (2) I219-V                                   | 25        | 0.75%   |
| Intel Wireless 8260                                                    | 24        | 0.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 23        | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 23        | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 23        | 0.69%   |
| Intel Wireless 3165                                                    | 22        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 21        | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 20        | 0.6%    |
| Intel Wireless 3160                                                    | 20        | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 20        | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 20        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 19        | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                          | 19        | 0.57%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 17        | 0.51%   |
| Intel 82577LM Gigabit Network Connection                               | 17        | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 16        | 0.48%   |
| Intel Centrino Advanced-N 6200                                         | 16        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 632       | 39.92%  |
| Realtek Semiconductor             | 344       | 21.73%  |
| Qualcomm Atheros                  | 267       | 16.87%  |
| Broadcom                          | 97        | 6.13%   |
| MediaTek                          | 64        | 4.04%   |
| TP-Link                           | 52        | 3.28%   |
| Ralink                            | 24        | 1.52%   |
| Ralink Technology                 | 23        | 1.45%   |
| Broadcom Limited                  | 16        | 1.01%   |
| ASUSTek Computer                  | 14        | 0.88%   |
| D-Link                            | 10        | 0.63%   |
| Qualcomm Atheros Communications   | 6         | 0.38%   |
| Microsoft                         | 5         | 0.32%   |
| Ericsson Business Mobile Networks | 4         | 0.25%   |
| Edimax Technology                 | 4         | 0.25%   |
| Sierra Wireless                   | 3         | 0.19%   |
| Tenda                             | 2         | 0.13%   |
| IMC Networks                      | 2         | 0.13%   |
| Fibocom                           | 2         | 0.13%   |
| Belkin Components                 | 2         | 0.13%   |
| Sitecom Europe                    | 1         | 0.06%   |
| Qualcomm                          | 1         | 0.06%   |
| Qcom                              | 1         | 0.06%   |
| NetGear                           | 1         | 0.06%   |
| Micro Star International          | 1         | 0.06%   |
| Mercucys                          | 1         | 0.06%   |
| Linksys                           | 1         | 0.06%   |
| D-Link System                     | 1         | 0.06%   |
| Belkin                            | 1         | 0.06%   |
| Accton Technology                 | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 89        | 5.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 81        | 5.09%   |
| Intel Wi-Fi 6 AX200                                                     | 67        | 4.21%   |
| Intel Wireless 8265 / 8275                                              | 65        | 4.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 57        | 3.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 55        | 3.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 48        | 3.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 42        | 2.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 42        | 2.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 40        | 2.51%   |
| Intel Wi-Fi 6 AX201                                                     | 36        | 2.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 2.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 33        | 2.07%   |
| Intel Wireless 7260                                                     | 32        | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 30        | 1.89%   |
| Intel Wireless 7265                                                     | 30        | 1.89%   |
| Intel Wireless 8260                                                     | 24        | 1.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 23        | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 23        | 1.45%   |
| Intel Wireless 3165                                                     | 22        | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 21        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 1.26%   |
| Intel Wireless 3160                                                     | 20        | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 20        | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 20        | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                           | 19        | 1.19%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 17        | 1.07%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 1.01%   |
| Intel Centrino Advanced-N 6200                                          | 16        | 1.01%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 15        | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 0.82%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 0.69%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 10        | 0.63%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 10        | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.63%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 10        | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 10        | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 0.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 950       | 55.85%  |
| Intel                                  | 425       | 24.99%  |
| Qualcomm Atheros                       | 95        | 5.58%   |
| Broadcom                               | 77        | 4.53%   |
| Marvell Technology Group               | 23        | 1.35%   |
| Broadcom Limited                       | 15        | 0.88%   |
| Nvidia                                 | 14        | 0.82%   |
| ASIX Electronics                       | 12        | 0.71%   |
| Samsung Electronics                    | 11        | 0.65%   |
| TP-Link                                | 10        | 0.59%   |
| Huawei Technologies                    | 10        | 0.59%   |
| Xiaomi                                 | 9         | 0.53%   |
| MediaTek                               | 7         | 0.41%   |
| Aquantia                               | 7         | 0.41%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.24%   |
| Lenovo                                 | 4         | 0.24%   |
| JMicron Technology                     | 4         | 0.24%   |
| Google                                 | 4         | 0.24%   |
| VIA Technologies                       | 3         | 0.18%   |
| Standard Microsystems                  | 2         | 0.12%   |
| Giga-Byte Technology                   | 2         | 0.12%   |
| DisplayLink                            | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Qualcomm                               | 1         | 0.06%   |
| QNAP System                            | 1         | 0.06%   |
| QLogic                                 | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| HMD Global                             | 1         | 0.06%   |
| Hewlett-Packard                        | 1         | 0.06%   |
| Dell                                   | 1         | 0.06%   |
| D-Link System                          | 1         | 0.06%   |
| 3Com                                   | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 718       | 41.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 136       | 7.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 69        | 3.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 41        | 2.36%   |
| Realtek RTL8125 2.5GbE Controller                                      | 37        | 2.13%   |
| Intel I211 Gigabit Network Connection                                  | 33        | 1.9%    |
| Intel Ethernet Connection I217-LM                                      | 31        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                                   | 25        | 1.44%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 23        | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 19        | 1.1%    |
| Intel 82577LM Gigabit Network Connection                               | 17        | 0.98%   |
| Intel Ethernet Connection (7) I219-V                                   | 14        | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 14        | 0.81%   |
| Intel Ethernet Connection I217-V                                       | 13        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                  | 13        | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 12        | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                          | 12        | 0.69%   |
| Intel Ethernet Controller I225-V                                       | 11        | 0.63%   |
| Intel Ethernet Connection I218-LM                                      | 11        | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                  | 11        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                                  | 10        | 0.58%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 9         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 9         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 9         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 9         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 9         | 0.52%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                                   | 9         | 0.52%   |
| Intel 82579V Gigabit Network Connection                                | 9         | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 9         | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 8         | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 8         | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 8         | 0.46%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 8         | 0.46%   |
| Nvidia MCP61 Ethernet                                                  | 7         | 0.4%    |
| MediaTek File-CD Gadget                                                | 7         | 0.4%    |
| Intel I210 Gigabit Network Connection                                  | 7         | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 0.4%    |
| Intel 82574L Gigabit Network Connection                                | 7         | 0.4%    |
| Intel 82567LM Gigabit Network Connection                               | 7         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1611      | 51.26%  |
| WiFi     | 1505      | 47.88%  |
| Modem    | 22        | 0.7%    |
| Unknown  | 5         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1189      | 58.77%  |
| Ethernet | 833       | 41.18%  |
| Unknown  | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1046      | 53.64%  |
| 1     | 819       | 42%     |
| 0     | 40        | 2.05%   |
| 3     | 36        | 1.85%   |
| 4     | 7         | 0.36%   |
| 8     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1636      | 82.29%  |
| Yes  | 352       | 17.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 509       | 41.15%  |
| IMC Networks                    | 174       | 14.07%  |
| Realtek Semiconductor           | 156       | 12.61%  |
| Qualcomm Atheros Communications | 83        | 6.71%   |
| Lite-On Technology              | 65        | 5.25%   |
| Broadcom                        | 42        | 3.4%    |
| Cambridge Silicon Radio         | 38        | 3.07%   |
| Foxconn / Hon Hai               | 34        | 2.75%   |
| ASUSTek Computer                | 31        | 2.51%   |
| Dell                            | 20        | 1.62%   |
| Hewlett-Packard                 | 16        | 1.29%   |
| Toshiba                         | 14        | 1.13%   |
| Apple                           | 12        | 0.97%   |
| Ralink                          | 9         | 0.73%   |
| MediaTek                        | 9         | 0.73%   |
| Realtek                         | 4         | 0.32%   |
| Alps Electric                   | 3         | 0.24%   |
| USI                             | 2         | 0.16%   |
| SINO WEALTH                     | 2         | 0.16%   |
| Integrated System Solution      | 2         | 0.16%   |
| Chicony Electronics             | 2         | 0.16%   |
| TP-Link                         | 1         | 0.08%   |
| Ralink Technology               | 1         | 0.08%   |
| Opticis                         | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| Foxconn International           | 1         | 0.08%   |
| Edimax Technology               | 1         | 0.08%   |
| Conwise Technology              | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |
| Askey Computer                  | 1         | 0.08%   |
| Accel Semiconductor             | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 198       | 16.01%  |
| Realtek Bluetooth Radio                             | 110       | 8.89%   |
| IMC Networks Bluetooth Radio                        | 99        | 8%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 93        | 7.52%   |
| Intel AX201 Bluetooth                               | 90        | 7.28%   |
| Intel AX200 Bluetooth                               | 67        | 5.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 47        | 3.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 38        | 3.07%   |
| IMC Networks Bluetooth Device                       | 34        | 2.75%   |
| IMC Networks Wireless_Device                        | 33        | 2.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 27        | 2.18%   |
| Realtek  Bluetooth 4.2 Adapter                      | 25        | 2.02%   |
| Intel Bluetooth Device                              | 22        | 1.78%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 19        | 1.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 14        | 1.13%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 13        | 1.05%   |
| Lite-On Bluetooth Device                            | 12        | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 10        | 0.81%   |
| Intel AX210 Bluetooth                               | 10        | 0.81%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.73%   |
| MediaTek Wireless_Device                            | 9         | 0.73%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.73%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 0.73%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.73%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.73%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 0.65%   |
| ASUS ASUS USB-BT500                                 | 8         | 0.65%   |
| Toshiba Bluetooth Device                            | 7         | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 7         | 0.57%   |
| Lite-On Wireless_Device                             | 7         | 0.57%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.57%   |
| Broadcom BCM2045A0                                  | 7         | 0.57%   |
| Apple Bluetooth Host Controller                     | 6         | 0.49%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.4%    |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.4%    |
| Foxconn / Hon Hai BCM20702A0                        | 5         | 0.4%    |
| Dell Wireless 365 Bluetooth                         | 5         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1466      | 56.76%  |
| AMD                                          | 475       | 18.39%  |
| Nvidia                                       | 421       | 16.3%   |
| C-Media Electronics                          | 40        | 1.55%   |
| Creative Labs                                | 23        | 0.89%   |
| Logitech                                     | 15        | 0.58%   |
| GN Netcom                                    | 11        | 0.43%   |
| ASUSTek Computer                             | 10        | 0.39%   |
| Creative Technology                          | 9         | 0.35%   |
| Trust                                        | 7         | 0.27%   |
| Realtek Semiconductor                        | 7         | 0.27%   |
| Texas Instruments                            | 6         | 0.23%   |
| Lenovo                                       | 6         | 0.23%   |
| Kingston Technology                          | 6         | 0.23%   |
| Silicon Integrated Systems [SiS]             | 5         | 0.19%   |
| Giga-Byte Technology                         | 5         | 0.19%   |
| XMOS                                         | 4         | 0.15%   |
| Sennheiser Communications                    | 4         | 0.15%   |
| Razer USA                                    | 4         | 0.15%   |
| Plantronics                                  | 4         | 0.15%   |
| Generalplus Technology                       | 4         | 0.15%   |
| VIA Technologies                             | 3         | 0.12%   |
| Tenx Technology                              | 3         | 0.12%   |
| DSEA A/S                                     | 3         | 0.12%   |
| Dell                                         | 3         | 0.12%   |
| KTMicro                                      | 2         | 0.08%   |
| JMTek                                        | 2         | 0.08%   |
| GYROCOM C&C                                  | 2         | 0.08%   |
| Focusrite-Novation                           | 2         | 0.08%   |
| Edifier Technology                           | 2         | 0.08%   |
| Corsair                                      | 2         | 0.08%   |
| Audio-Technica                               | 2         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| Unknown                                      | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.04%   |
| TEAC                                         | 1         | 0.04%   |
| Studiologic                                  | 1         | 0.04%   |
| Sony                                         | 1         | 0.04%   |
| Samsung Electronics                          | 1         | 0.04%   |
| Samson Technologies                          | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 194       | 6.32%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 150       | 4.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 105       | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 104       | 3.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 103       | 3.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 83        | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 83        | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 78        | 2.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 74        | 2.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 71        | 2.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 65        | 2.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 62        | 2.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 57        | 1.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 56        | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 56        | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 54        | 1.76%   |
| Intel 8 Series HD Audio Controller                                                                | 53        | 1.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 50        | 1.63%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 50        | 1.63%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 49        | 1.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 43        | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 41        | 1.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 41        | 1.34%   |
| Intel Broadwell-U Audio Controller                                                                | 41        | 1.34%   |
| AMD FCH Azalia Controller                                                                         | 40        | 1.3%    |
| Intel 200 Series PCH HD Audio                                                                     | 38        | 1.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 37        | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 36        | 1.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 36        | 1.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 33        | 1.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 31        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 30        | 0.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 30        | 0.98%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 27        | 0.88%   |
| Intel Comet Lake PCH cAVS                                                                         | 26        | 0.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 25        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 24        | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 23        | 0.75%   |
| Nvidia High Definition Audio Controller                                                           | 23        | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 23        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 277       | 24.3%   |
| SK hynix                     | 197       | 17.28%  |
| Kingston                     | 170       | 14.91%  |
| Micron Technology            | 109       | 9.56%   |
| Unknown                      | 90        | 7.89%   |
| Corsair                      | 79        | 6.93%   |
| Crucial                      | 33        | 2.89%   |
| Ramaxel Technology           | 29        | 2.54%   |
| A-DATA Technology            | 28        | 2.46%   |
| Nanya Technology             | 22        | 1.93%   |
| Elpida                       | 20        | 1.75%   |
| G.Skill                      | 17        | 1.49%   |
| Unknown (ABCD)               | 12        | 1.05%   |
| Kingmax                      | 12        | 1.05%   |
| Unknown                      | 6         | 0.53%   |
| Patriot                      | 4         | 0.35%   |
| Apacer                       | 4         | 0.35%   |
| Qimonda                      | 3         | 0.26%   |
| GOODRAM                      | 3         | 0.26%   |
| Transcend                    | 2         | 0.18%   |
| Silicon Power                | 2         | 0.18%   |
| Kingmax Semiconductor        | 2         | 0.18%   |
| Golden Empire                | 2         | 0.18%   |
| Unknown (7F7F7F94FFFFFFFF)   | 1         | 0.09%   |
| Unknown (0x9801)             | 1         | 0.09%   |
| Unknown (0x7FDA000000000000) | 1         | 0.09%   |
| Unknown (0B45)               | 1         | 0.09%   |
| Team                         | 1         | 0.09%   |
| TakeMS                       | 1         | 0.09%   |
| SK_Hynix                     | 1         | 0.09%   |
| SHARETRONIC                  | 1         | 0.09%   |
| S                            | 1         | 0.09%   |
| KingFast                     | 1         | 0.09%   |
| Infineon                     | 1         | 0.09%   |
| H                            | 1         | 0.09%   |
| Exceleram                    | 1         | 0.09%   |
| Avant                        | 1         | 0.09%   |
| Atermiter                    | 1         | 0.09%   |
| ASint Technology             | 1         | 0.09%   |
| AMD                          | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 17        | 1.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 11        | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 11        | 0.88%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 11        | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 0.88%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 10        | 0.8%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 10        | 0.8%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 10        | 0.8%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 10        | 0.8%    |
| Samsung RAM M4 70T5663RZ3-CE6 2GB SODIMM DDR2 667MT/s               | 10        | 0.8%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 9         | 0.72%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 8         | 0.64%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                 | 8         | 0.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 7         | 0.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 7         | 0.56%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 7         | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 7         | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 7         | 0.56%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                              | 6         | 0.48%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 6         | 0.48%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 6         | 0.48%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 6         | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 6         | 0.48%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s                   | 6         | 0.48%   |
| Unknown                                                             | 6         | 0.48%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 5         | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 5         | 0.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 5         | 0.4%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 0.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 0.4%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s                 | 5         | 0.4%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 5         | 0.4%    |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s           | 5         | 0.4%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 4         | 0.32%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 4         | 0.32%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 0.32%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 4         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 457       | 47.06%  |
| DDR3    | 313       | 32.23%  |
| DDR2    | 68        | 7%      |
| SDRAM   | 32        | 3.3%    |
| LPDDR4  | 25        | 2.57%   |
| Unknown | 23        | 2.37%   |
| DDR5    | 18        | 1.85%   |
| LPDDR3  | 17        | 1.75%   |
| LPDDR5  | 12        | 1.24%   |
| DDR     | 4         | 0.41%   |
| DRAM    | 2         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 594       | 61.94%  |
| DIMM         | 307       | 32.01%  |
| Row Of Chips | 51        | 5.32%   |
| Chip         | 5         | 0.52%   |
| RIMM         | 1         | 0.1%    |
| FB-DIMM      | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 387       | 36.68%  |
| 4096  | 301       | 28.53%  |
| 16384 | 153       | 14.5%   |
| 2048  | 131       | 12.42%  |
| 1024  | 54        | 5.12%   |
| 32768 | 23        | 2.18%   |
| 512   | 6         | 0.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 202       | 18.74%  |
| 3200    | 166       | 15.4%   |
| 2667    | 150       | 13.91%  |
| 2400    | 94        | 8.72%   |
| 1333    | 62        | 5.75%   |
| 2133    | 44        | 4.08%   |
| 1334    | 42        | 3.9%    |
| 667     | 40        | 3.71%   |
| 800     | 32        | 2.97%   |
| 3600    | 21        | 1.95%   |
| Unknown | 20        | 1.86%   |
| 3266    | 18        | 1.67%   |
| 6400    | 12        | 1.11%   |
| 1867    | 11        | 1.02%   |
| 1067    | 11        | 1.02%   |
| 3000    | 10        | 0.93%   |
| 2666    | 10        | 0.93%   |
| 975     | 9         | 0.83%   |
| 4800    | 8         | 0.74%   |
| 4267    | 8         | 0.74%   |
| 3733    | 8         | 0.74%   |
| 1866    | 7         | 0.65%   |
| 1066    | 7         | 0.65%   |
| 3400    | 6         | 0.56%   |
| 2933    | 6         | 0.56%   |
| 533     | 6         | 0.56%   |
| 4199    | 5         | 0.46%   |
| 2048    | 5         | 0.46%   |
| 6000    | 4         | 0.37%   |
| 4266    | 4         | 0.37%   |
| 1800    | 4         | 0.37%   |
| 3866    | 3         | 0.28%   |
| 3800    | 3         | 0.28%   |
| 3500    | 3         | 0.28%   |
| 400     | 3         | 0.28%   |
| 5600    | 2         | 0.19%   |
| 3466    | 2         | 0.19%   |
| 3333    | 2         | 0.19%   |
| 3066    | 2         | 0.19%   |
| 2800    | 2         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 24.07%  |
| Canon                 | 10        | 18.52%  |
| Samsung Electronics   | 9         | 16.67%  |
| Brother Industries    | 8         | 14.81%  |
| Seiko Epson           | 7         | 12.96%  |
| Xerox                 | 2         | 3.7%    |
| Lexmark International | 2         | 3.7%    |
| Zebra                 | 1         | 1.85%   |
| QinHeng Electronics   | 1         | 1.85%   |
| ATEN International    | 1         | 1.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Samsung M2070 Series                          | 3         | 5.56%   |
| Seiko Epson L3150 Series                      | 2         | 3.7%    |
| Seiko Epson L3110 Series                      | 2         | 3.7%    |
| Samsung Composite Device                      | 2         | 3.7%    |
| Lexmark International InkJet Color Printer    | 2         | 3.7%    |
| HP DeskJet 2130 series                        | 2         | 3.7%    |
| Canon MF4010 series                           | 2         | 3.7%    |
| Brother HL-1110 series                        | 2         | 3.7%    |
| Zebra GK420t Label Printer                    | 1         | 1.85%   |
| Xerox Phaser 6130N                            | 1         | 1.85%   |
| Xerox Phaser 3020                             | 1         | 1.85%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.85%   |
| Seiko Epson L6160 Series                      | 1         | 1.85%   |
| Seiko Epson ET-2600 Series                    | 1         | 1.85%   |
| Samsung ML-216x Series Laser Printer          | 1         | 1.85%   |
| Samsung M267x 287x Series                     | 1         | 1.85%   |
| Samsung M2020 Series                          | 1         | 1.85%   |
| Samsung CLP-310 Color Laser Printer           | 1         | 1.85%   |
| QinHeng CH340S                                | 1         | 1.85%   |
| HP LaserJet 3050                              | 1         | 1.85%   |
| HP LaserJet 1022                              | 1         | 1.85%   |
| HP LaserJet 1018                              | 1         | 1.85%   |
| HP Laser 107a                                 | 1         | 1.85%   |
| HP HP LaserJet M14-M17                        | 1         | 1.85%   |
| HP Deskjet F4500 series                       | 1         | 1.85%   |
| HP DeskJet F2492 All-in-One                   | 1         | 1.85%   |
| HP Deskjet 3050A                              | 1         | 1.85%   |
| HP DeskJet 2700 series                        | 1         | 1.85%   |
| HP DeskJet 2300 series                        | 1         | 1.85%   |
| HP Deskjet 2050 J510                          | 1         | 1.85%   |
| Canon PIXMA MP280                             | 1         | 1.85%   |
| Canon PIXMA MP250                             | 1         | 1.85%   |
| Canon MF4320-4350                             | 1         | 1.85%   |
| Canon MF3200 series                           | 1         | 1.85%   |
| Canon MF3110                                  | 1         | 1.85%   |
| Canon LBP2900                                 | 1         | 1.85%   |
| Canon iP7200 series                           | 1         | 1.85%   |
| Canon CanoScan LiDE 300                       | 1         | 1.85%   |
| Brother MFC-7420                              | 1         | 1.85%   |
| Brother HL-5380DN series                      | 1         | 1.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 100 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 278       | 21.98%  |
| Chicony Electronics                    | 255       | 20.16%  |
| Realtek Semiconductor                  | 107       | 8.46%   |
| Microdia                               | 93        | 7.35%   |
| Quanta                                 | 63        | 4.98%   |
| Sunplus Innovation Technology          | 62        | 4.9%    |
| Bison Electronics                      | 57        | 4.51%   |
| Syntek                                 | 35        | 2.77%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 2.45%   |
| Alcor Micro                            | 28        | 2.21%   |
| Acer                                   | 28        | 2.21%   |
| Lite-On Technology                     | 27        | 2.13%   |
| Logitech                               | 25        | 1.98%   |
| Sonix Technology                       | 23        | 1.82%   |
| Suyin                                  | 22        | 1.74%   |
| Luxvisions Innotech Limited            | 13        | 1.03%   |
| Apple                                  | 13        | 1.03%   |
| Samsung Electronics                    | 11        | 0.87%   |
| Microsoft                              | 11        | 0.87%   |
| Ricoh                                  | 10        | 0.79%   |
| Z-Star Microelectronics                | 7         | 0.55%   |
| Silicon Motion                         | 7         | 0.55%   |
| ShineTech                              | 6         | 0.47%   |
| OmniVision Technologies                | 5         | 0.4%    |
| ALi                                    | 4         | 0.32%   |
| Primax Electronics                     | 3         | 0.24%   |
| Lenovo                                 | 3         | 0.24%   |
| GEMBIRD                                | 3         | 0.24%   |
| Cubeternet                             | 3         | 0.24%   |
| Sunplus Technology                     | 2         | 0.16%   |
| Jieli Technology                       | 2         | 0.16%   |
| Importek                               | 2         | 0.16%   |
| Genesys Logic                          | 2         | 0.16%   |
| Aveo Technology                        | 2         | 0.16%   |
| Arkmicro Technologies                  | 2         | 0.16%   |
| Y Media                                | 1         | 0.08%   |
| WaveRider Communications               | 1         | 0.08%   |
| Unknown                                | 1         | 0.08%   |
| Trust                                  | 1         | 0.08%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam      | 112       | 8.83%   |
| IMC Networks USB2.0 HD UVC WebCam       | 88        | 6.94%   |
| Chicony Integrated Camera               | 56        | 4.42%   |
| Realtek Integrated_Webcam_HD            | 38        | 3%      |
| IMC Networks Integrated Camera          | 37        | 2.92%   |
| Microdia Integrated_Webcam_HD           | 28        | 2.21%   |
| Chicony HD WebCam                       | 23        | 1.81%   |
| Bison Integrated Camera                 | 22        | 1.74%   |
| Syntek Integrated Camera                | 20        | 1.58%   |
| Realtek USB Camera                      | 19        | 1.5%    |
| Chicony USB2.0 VGA UVC WebCam           | 19        | 1.5%    |
| Sonix USB2.0 HD UVC WebCam              | 18        | 1.42%   |
| Chicony USB2.0 HD UVC WebCam            | 16        | 1.26%   |
| Sunplus HD WebCam                       | 13        | 1.03%   |
| Quanta VGA WebCam                       | 12        | 0.95%   |
| Samsung Galaxy series, misc. (MTP mode) | 11        | 0.87%   |
| Chicony TOSHIBA Web Camera - HD         | 11        | 0.87%   |
| Bison Lenovo EasyCamera                 | 11        | 0.87%   |
| Lite-On Integrated Camera               | 10        | 0.79%   |
| Chicony EasyCamera                      | 10        | 0.79%   |
| Acer SunplusIT Integrated Camera        | 10        | 0.79%   |
| Chicony VGA Webcam                      | 9         | 0.71%   |
| Chicony HP Webcam                       | 9         | 0.71%   |
| Alcor Micro USB 2.0 PC Camera           | 9         | 0.71%   |
| Alcor Micro USB 2.0 Camera              | 9         | 0.71%   |
| Realtek USB2.0 HD UVC WebCam            | 8         | 0.63%   |
| Quanta ACER HD User Facing              | 8         | 0.63%   |
| Microsoft LifeCam HD-3000               | 8         | 0.63%   |
| Microdia Integrated Webcam              | 8         | 0.63%   |
| Microdia Camera                         | 8         | 0.63%   |
| Syntek Lenovo EasyCamera                | 7         | 0.55%   |
| Syntek EasyCamera                       | 7         | 0.55%   |
| Sunplus Integrated_Webcam_HD            | 7         | 0.55%   |
| Realtek USB2.0 VGA UVC WebCam           | 7         | 0.55%   |
| Realtek Integrated Webcam               | 7         | 0.55%   |
| IMC Networks USB2.0 UVC HD Webcam       | 7         | 0.55%   |
| Bison EasyCamera                        | 7         | 0.55%   |
| Sunplus ASUS Webcam                     | 6         | 0.47%   |
| ShineTech USB2.0 HD UVC WebCam          | 6         | 0.47%   |
| Realtek Lenovo EasyCamera               | 6         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 59        | 31.22%  |
| Synaptics                          | 51        | 26.98%  |
| Shenzhen Goodix Technology         | 23        | 12.17%  |
| Elan Microelectronics              | 16        | 8.47%   |
| Upek                               | 12        | 6.35%   |
| LighTuning Technology              | 11        | 5.82%   |
| AuthenTec                          | 11        | 5.82%   |
| Focal-systems.Corp                 | 2         | 1.06%   |
| STMicroelectronics                 | 1         | 0.53%   |
| Samsung Electronics                | 1         | 0.53%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.53%   |
| GDMicroelectronics                 | 1         | 0.53%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 7.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 15        | 7.94%   |
| Shenzhen Goodix  Fingerprint Device                                        | 15        | 7.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 5.82%   |
| Synaptics  WBDI                                                            | 11        | 5.82%   |
| Elan ELAN:Fingerprint                                                      | 10        | 5.29%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 3.7%    |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 3.7%    |
| AuthenTec AES2810                                                          | 7         | 3.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 3.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.17%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 3.17%   |
| Elan ELAN:ARM-M4                                                           | 6         | 3.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.65%   |
| Validity Sensors VFS491                                                    | 4         | 2.12%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 2.12%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.59%   |
| Synaptics WBDI                                                             | 3         | 1.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.59%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.59%   |
| LighTuning Fingerprint Reader                                              | 3         | 1.59%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.06%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.06%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.06%   |
| LighTuning Fingerprint Sensor                                              | 2         | 1.06%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 2         | 1.06%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.06%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.06%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.53%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.53%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.53%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.53%   |
| Synaptics UWP WBDI                                                         | 1         | 0.53%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.53%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.53%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.53%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 44        | 54.32%  |
| Alcor Micro               | 19        | 23.46%  |
| Upek                      | 5         | 6.17%   |
| Lenovo                    | 5         | 6.17%   |
| O2 Micro                  | 4         | 4.94%   |
| Gemalto (was Gemplus)     | 1         | 1.23%   |
| Fujitsu Siemens Computers | 1         | 1.23%   |
| Chicony Electronics       | 1         | 1.23%   |
| Aladdin Knowledge Systems | 1         | 1.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 23.46%  |
| Broadcom 58200                                                               | 14        | 17.28%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 13.58%  |
| Broadcom 5880                                                                | 11        | 13.58%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 9.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 6.17%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 6.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 4.94%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.23%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 1.23%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.23%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1421      | 71.7%   |
| 1     | 457       | 23.06%  |
| 2     | 93        | 4.69%   |
| 3     | 9         | 0.45%   |
| 10    | 1         | 0.05%   |
| 4     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 188       | 28.31%  |
| Graphics card            | 151       | 22.74%  |
| Net/wireless             | 87        | 13.1%   |
| Chipcard                 | 73        | 10.99%  |
| Multimedia controller    | 41        | 6.17%   |
| Camera                   | 24        | 3.61%   |
| Communication controller | 23        | 3.46%   |
| Bluetooth                | 17        | 2.56%   |
| Storage                  | 16        | 2.41%   |
| Card reader              | 9         | 1.36%   |
| Sound                    | 8         | 1.2%    |
| Unassigned class         | 7         | 1.05%   |
| Net/ethernet             | 5         | 0.75%   |
| Network                  | 3         | 0.45%   |
| Modem                    | 3         | 0.45%   |
| Storage/ide              | 2         | 0.3%    |
| Flash memory             | 2         | 0.3%    |
| Unclassified device      | 1         | 0.15%   |
| Storage/raid             | 1         | 0.15%   |
| Storage/nvme             | 1         | 0.15%   |
| Firewire controller      | 1         | 0.15%   |
| Dvb card                 | 1         | 0.15%   |

