Ubuntu 23.04 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_23.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_23.04/Notebook/README.md).

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

Total: 921

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [2ee9ffdaa0](https://linux-hardware.org/?probe=2ee9ffdaa0) | Jun 30, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [6ab7575bed](https://linux-hardware.org/?probe=6ab7575bed) | Jun 30, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [fa055ceb7c](https://linux-hardware.org/?probe=fa055ceb7c) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [d42cdc8551](https://linux-hardware.org/?probe=d42cdc8551) | Jun 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [b5d1a7e115](https://linux-hardware.org/?probe=b5d1a7e115) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [951adb91cd](https://linux-hardware.org/?probe=951adb91cd) | Jun 30, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [99a03772fb](https://linux-hardware.org/?probe=99a03772fb) | Jun 30, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [ffcfef2edb](https://linux-hardware.org/?probe=ffcfef2edb) | Jun 30, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [2012cd2c37](https://linux-hardware.org/?probe=2012cd2c37) | Jun 30, 2023 |
| Timi          | Xiaomi Book Air 13 2022     | Convertible | [2d7ee2c4a8](https://linux-hardware.org/?probe=2d7ee2c4a8) | Jun 30, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [22a896d74b](https://linux-hardware.org/?probe=22a896d74b) | Jun 30, 2023 |
| Dell          | Latitude 5440               | Notebook    | [7868400967](https://linux-hardware.org/?probe=7868400967) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1e4c2cf905](https://linux-hardware.org/?probe=1e4c2cf905) | Jun 30, 2023 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [35871c9acc](https://linux-hardware.org/?probe=35871c9acc) | Jun 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [b98433fa84](https://linux-hardware.org/?probe=b98433fa84) | Jun 29, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [42624c8bb1](https://linux-hardware.org/?probe=42624c8bb1) | Jun 29, 2023 |
| Acer          | NC-A515-51G-59DM            | Notebook    | [a521f2cc60](https://linux-hardware.org/?probe=a521f2cc60) | Jun 29, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [1caca06d89](https://linux-hardware.org/?probe=1caca06d89) | Jun 29, 2023 |
| Acer          | Aspire XC-840               | Desktop     | [76c750aae4](https://linux-hardware.org/?probe=76c750aae4) | Jun 29, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [952909bc80](https://linux-hardware.org/?probe=952909bc80) | Jun 29, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [61930889dc](https://linux-hardware.org/?probe=61930889dc) | Jun 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [d358089f32](https://linux-hardware.org/?probe=d358089f32) | Jun 29, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [f1a1aa76e2](https://linux-hardware.org/?probe=f1a1aa76e2) | Jun 29, 2023 |
| Sony          | SVE17137CXB                 | Notebook    | [ed6f82dc16](https://linux-hardware.org/?probe=ed6f82dc16) | Jun 29, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [a41ff8c573](https://linux-hardware.org/?probe=a41ff8c573) | Jun 29, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [6147d58cdf](https://linux-hardware.org/?probe=6147d58cdf) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | Notebook    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [3c4acbf380](https://linux-hardware.org/?probe=3c4acbf380) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ff560998d8](https://linux-hardware.org/?probe=ff560998d8) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7017964456](https://linux-hardware.org/?probe=7017964456) | Jun 28, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [506c909e37](https://linux-hardware.org/?probe=506c909e37) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [8ae62960d8](https://linux-hardware.org/?probe=8ae62960d8) | Jun 28, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ad91997e3e](https://linux-hardware.org/?probe=ad91997e3e) | Jun 28, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [b30ff15571](https://linux-hardware.org/?probe=b30ff15571) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [e2ea94e083](https://linux-hardware.org/?probe=e2ea94e083) | Jun 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [90a10ed8ed](https://linux-hardware.org/?probe=90a10ed8ed) | Jun 28, 2023 |
| Acer          | Aspire Z3-705               | All in one  | [058c58505d](https://linux-hardware.org/?probe=058c58505d) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [4e40b350ca](https://linux-hardware.org/?probe=4e40b350ca) | Jun 28, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | Notebook    | [1d6bf708ce](https://linux-hardware.org/?probe=1d6bf708ce) | Jun 28, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [177c923e5a](https://linux-hardware.org/?probe=177c923e5a) | Jun 27, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [8ef6f6f24a](https://linux-hardware.org/?probe=8ef6f6f24a) | Jun 27, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [d4c9f8de35](https://linux-hardware.org/?probe=d4c9f8de35) | Jun 27, 2023 |
| HP            | ENVY 15                     | Notebook    | [0d46d829d2](https://linux-hardware.org/?probe=0d46d829d2) | Jun 27, 2023 |
| HP            | ENVY 15                     | Notebook    | [189cf01c37](https://linux-hardware.org/?probe=189cf01c37) | Jun 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7497c404d4](https://linux-hardware.org/?probe=7497c404d4) | Jun 27, 2023 |
| Daten Tecn... | ESTELAR                     | Notebook    | [0052df6a90](https://linux-hardware.org/?probe=0052df6a90) | Jun 27, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [742d015edb](https://linux-hardware.org/?probe=742d015edb) | Jun 26, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [6c659f8e1f](https://linux-hardware.org/?probe=6c659f8e1f) | Jun 26, 2023 |
| Daten Tecn... | ESTELAR                     | Notebook    | [d5f99bced6](https://linux-hardware.org/?probe=d5f99bced6) | Jun 26, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [076507dc77](https://linux-hardware.org/?probe=076507dc77) | Jun 26, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [2e9bc10188](https://linux-hardware.org/?probe=2e9bc10188) | Jun 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [544c014552](https://linux-hardware.org/?probe=544c014552) | Jun 26, 2023 |
| Gateway       | NV57H                       | Notebook    | [a49db45595](https://linux-hardware.org/?probe=a49db45595) | Jun 26, 2023 |
| Gateway       | NV57H                       | Notebook    | [ee84597590](https://linux-hardware.org/?probe=ee84597590) | Jun 26, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | Notebook    | [70a6547925](https://linux-hardware.org/?probe=70a6547925) | Jun 26, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [77e0f0541a](https://linux-hardware.org/?probe=77e0f0541a) | Jun 26, 2023 |
| Star Labs     | LabTop                      | Notebook    | [87a0d9dc09](https://linux-hardware.org/?probe=87a0d9dc09) | Jun 26, 2023 |
| Acer          | TravelMate 6493             | Notebook    | [490906b996](https://linux-hardware.org/?probe=490906b996) | Jun 25, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [3ec1b71f5c](https://linux-hardware.org/?probe=3ec1b71f5c) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [286826f3b2](https://linux-hardware.org/?probe=286826f3b2) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [b15f68a294](https://linux-hardware.org/?probe=b15f68a294) | Jun 25, 2023 |
| Intel         | H61                         | Desktop     | [8af1bf1ada](https://linux-hardware.org/?probe=8af1bf1ada) | Jun 25, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [9a87719748](https://linux-hardware.org/?probe=9a87719748) | Jun 25, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3505659de8](https://linux-hardware.org/?probe=3505659de8) | Jun 25, 2023 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [9f1f9757a2](https://linux-hardware.org/?probe=9f1f9757a2) | Jun 25, 2023 |
| Dell          | 07N90W A01                  | Desktop     | [67a12e071e](https://linux-hardware.org/?probe=67a12e071e) | Jun 25, 2023 |
| ASRock        | X570 Extreme4               | Desktop     | [0ab63facb3](https://linux-hardware.org/?probe=0ab63facb3) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [223911e8f0](https://linux-hardware.org/?probe=223911e8f0) | Jun 25, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | Notebook    | [1809b4709e](https://linux-hardware.org/?probe=1809b4709e) | Jun 25, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [2e20ab8996](https://linux-hardware.org/?probe=2e20ab8996) | Jun 25, 2023 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [94afcaf73d](https://linux-hardware.org/?probe=94afcaf73d) | Jun 25, 2023 |
| HP            | 805D                        | Desktop     | [d55246de23](https://linux-hardware.org/?probe=d55246de23) | Jun 24, 2023 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [7d8f0212e9](https://linux-hardware.org/?probe=7d8f0212e9) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [ade3806ebb](https://linux-hardware.org/?probe=ade3806ebb) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [8a22a7fba4](https://linux-hardware.org/?probe=8a22a7fba4) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [b82cc440a0](https://linux-hardware.org/?probe=b82cc440a0) | Jun 24, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [cc2b3ff1ad](https://linux-hardware.org/?probe=cc2b3ff1ad) | Jun 24, 2023 |
| Dell          | G5 5590                     | Notebook    | [6d6974b0eb](https://linux-hardware.org/?probe=6d6974b0eb) | Jun 24, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1a8f2401f1](https://linux-hardware.org/?probe=1a8f2401f1) | Jun 24, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [ed70d540cd](https://linux-hardware.org/?probe=ed70d540cd) | Jun 24, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [dd17969875](https://linux-hardware.org/?probe=dd17969875) | Jun 24, 2023 |
| System76      | Desktop leox5               | Desktop     | [210eb3f1e8](https://linux-hardware.org/?probe=210eb3f1e8) | Jun 24, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [45575cf0cc](https://linux-hardware.org/?probe=45575cf0cc) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [e3d196b0b5](https://linux-hardware.org/?probe=e3d196b0b5) | Jun 24, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [77d2d05995](https://linux-hardware.org/?probe=77d2d05995) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [e5b4e8d2d4](https://linux-hardware.org/?probe=e5b4e8d2d4) | Jun 24, 2023 |
| MSI           | H270-A PRO                  | Desktop     | [169bbe5f04](https://linux-hardware.org/?probe=169bbe5f04) | Jun 23, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a9079161b0](https://linux-hardware.org/?probe=a9079161b0) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ac715f3941](https://linux-hardware.org/?probe=ac715f3941) | Jun 23, 2023 |
| HP            | ENVY 15                     | Notebook    | [3918cca1e5](https://linux-hardware.org/?probe=3918cca1e5) | Jun 23, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [7b33fc2cb8](https://linux-hardware.org/?probe=7b33fc2cb8) | Jun 23, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [23ea485e5e](https://linux-hardware.org/?probe=23ea485e5e) | Jun 22, 2023 |
| MSI           | 760GM -E51                  | Desktop     | [3f0c7f7d21](https://linux-hardware.org/?probe=3f0c7f7d21) | Jun 22, 2023 |
| Acer          | Swift SFE16-42              | Notebook    | [9afa4fb174](https://linux-hardware.org/?probe=9afa4fb174) | Jun 22, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [44050251e9](https://linux-hardware.org/?probe=44050251e9) | Jun 22, 2023 |
| ASUSTek       | PRIME Z790M-PLUS            | Desktop     | [ea7090722f](https://linux-hardware.org/?probe=ea7090722f) | Jun 22, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [67f3cd78e2](https://linux-hardware.org/?probe=67f3cd78e2) | Jun 22, 2023 |
| Positivo      | Mobile                      | Notebook    | [f9a55866f0](https://linux-hardware.org/?probe=f9a55866f0) | Jun 22, 2023 |
| Positivo      | Mobile                      | Notebook    | [25df2e5abc](https://linux-hardware.org/?probe=25df2e5abc) | Jun 22, 2023 |
| Dell          | 0YXG0N A00                  | Desktop     | [546af4a5d6](https://linux-hardware.org/?probe=546af4a5d6) | Jun 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [0fb6c61a2b](https://linux-hardware.org/?probe=0fb6c61a2b) | Jun 21, 2023 |
| Acer          | Aspire A515-53G             | Notebook    | [430cfefc6a](https://linux-hardware.org/?probe=430cfefc6a) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [f96a1a3552](https://linux-hardware.org/?probe=f96a1a3552) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [52c4c32098](https://linux-hardware.org/?probe=52c4c32098) | Jun 21, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [53ef3811fc](https://linux-hardware.org/?probe=53ef3811fc) | Jun 21, 2023 |
| HP            | 339A                        | Desktop     | [420903b9cc](https://linux-hardware.org/?probe=420903b9cc) | Jun 21, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [7a29f3d086](https://linux-hardware.org/?probe=7a29f3d086) | Jun 20, 2023 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [881e4f3437](https://linux-hardware.org/?probe=881e4f3437) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [7a4754357e](https://linux-hardware.org/?probe=7a4754357e) | Jun 20, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [6840ce5f21](https://linux-hardware.org/?probe=6840ce5f21) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [513165d4f6](https://linux-hardware.org/?probe=513165d4f6) | Jun 20, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [b51dda105a](https://linux-hardware.org/?probe=b51dda105a) | Jun 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [bff08fbf94](https://linux-hardware.org/?probe=bff08fbf94) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [15e75e17fc](https://linux-hardware.org/?probe=15e75e17fc) | Jun 20, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [226b3173fe](https://linux-hardware.org/?probe=226b3173fe) | Jun 20, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [97fb6e5a1b](https://linux-hardware.org/?probe=97fb6e5a1b) | Jun 20, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [05b8720dce](https://linux-hardware.org/?probe=05b8720dce) | Jun 19, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [6dea148dd7](https://linux-hardware.org/?probe=6dea148dd7) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [91f85b5bb5](https://linux-hardware.org/?probe=91f85b5bb5) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [93f576698e](https://linux-hardware.org/?probe=93f576698e) | Jun 19, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [8031890e56](https://linux-hardware.org/?probe=8031890e56) | Jun 19, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [067eeb10e5](https://linux-hardware.org/?probe=067eeb10e5) | Jun 19, 2023 |
| Otazak        | iPC45                       | Convertible | [5448e32422](https://linux-hardware.org/?probe=5448e32422) | Jun 19, 2023 |
| HP            | Notebook                    | Notebook    | [6df5e3f6ff](https://linux-hardware.org/?probe=6df5e3f6ff) | Jun 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [948225d98e](https://linux-hardware.org/?probe=948225d98e) | Jun 18, 2023 |
| Toshiba       | Satellite-L845              | Notebook    | [cfe5a81354](https://linux-hardware.org/?probe=cfe5a81354) | Jun 18, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [a4bea0f3e3](https://linux-hardware.org/?probe=a4bea0f3e3) | Jun 18, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [8bf2dd01d7](https://linux-hardware.org/?probe=8bf2dd01d7) | Jun 18, 2023 |
| Panasonic     | CF-54-2                     | Notebook    | [48b7e4f212](https://linux-hardware.org/?probe=48b7e4f212) | Jun 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [c867520de1](https://linux-hardware.org/?probe=c867520de1) | Jun 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [159b20029e](https://linux-hardware.org/?probe=159b20029e) | Jun 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [bc9f4e0f09](https://linux-hardware.org/?probe=bc9f4e0f09) | Jun 18, 2023 |
| HP            | Pavilion dv6                | Notebook    | [f47b055767](https://linux-hardware.org/?probe=f47b055767) | Jun 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [8f32e75d6e](https://linux-hardware.org/?probe=8f32e75d6e) | Jun 18, 2023 |
| Intel         | NUC13SBBi9 M58736-302       | Mini pc     | [66ef514141](https://linux-hardware.org/?probe=66ef514141) | Jun 17, 2023 |
| HP            | 84FD                        | Desktop     | [968b4e287f](https://linux-hardware.org/?probe=968b4e287f) | Jun 17, 2023 |
| HP            | 84FD                        | Desktop     | [1711c65b62](https://linux-hardware.org/?probe=1711c65b62) | Jun 17, 2023 |
| Medion        | S15449                      | Notebook    | [9ee17b411b](https://linux-hardware.org/?probe=9ee17b411b) | Jun 17, 2023 |
| Dell          | 0P301D A00                  | Desktop     | [91bec0952f](https://linux-hardware.org/?probe=91bec0952f) | Jun 17, 2023 |
| HP            | 2B3B                        | All in one  | [5e96206d26](https://linux-hardware.org/?probe=5e96206d26) | Jun 17, 2023 |
| HP            | ENVY 15                     | Notebook    | [10a4cb8865](https://linux-hardware.org/?probe=10a4cb8865) | Jun 17, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [0ef00ccccc](https://linux-hardware.org/?probe=0ef00ccccc) | Jun 16, 2023 |
| Toshiba       | Satellite C870-199          | Notebook    | [cc18b4ff53](https://linux-hardware.org/?probe=cc18b4ff53) | Jun 16, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [2734ce8c5d](https://linux-hardware.org/?probe=2734ce8c5d) | Jun 16, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [cd928f7cc4](https://linux-hardware.org/?probe=cd928f7cc4) | Jun 16, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [3204bd2215](https://linux-hardware.org/?probe=3204bd2215) | Jun 16, 2023 |
| Supermicro    | X10DRi                      | Server      | [2adac716cd](https://linux-hardware.org/?probe=2adac716cd) | Jun 16, 2023 |
| HP            | 1496                        | Desktop     | [ccc9943e2d](https://linux-hardware.org/?probe=ccc9943e2d) | Jun 16, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [3b94657fa0](https://linux-hardware.org/?probe=3b94657fa0) | Jun 16, 2023 |
| Unknown       | G41 Series                  | Desktop     | [07122155fa](https://linux-hardware.org/?probe=07122155fa) | Jun 15, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [eeb1bdc4d1](https://linux-hardware.org/?probe=eeb1bdc4d1) | Jun 15, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [3ba89fb405](https://linux-hardware.org/?probe=3ba89fb405) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [fe65868ffe](https://linux-hardware.org/?probe=fe65868ffe) | Jun 15, 2023 |
| ASUSTek       | Rev                         | Desktop     | [6c5d91db68](https://linux-hardware.org/?probe=6c5d91db68) | Jun 15, 2023 |
| Dell          | Inspiron 14 7435 2-in-1     | Convertible | [b6b86a1205](https://linux-hardware.org/?probe=b6b86a1205) | Jun 15, 2023 |
| MSI           | Stealth GS77 12UE           | Notebook    | [48df655e45](https://linux-hardware.org/?probe=48df655e45) | Jun 15, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [7df89b77f2](https://linux-hardware.org/?probe=7df89b77f2) | Jun 15, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2e1608028d](https://linux-hardware.org/?probe=2e1608028d) | Jun 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [dcfab5627c](https://linux-hardware.org/?probe=dcfab5627c) | Jun 14, 2023 |
| Unknown       | G41T-M7                     | Desktop     | [18a63d3a27](https://linux-hardware.org/?probe=18a63d3a27) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [e9aeb26aeb](https://linux-hardware.org/?probe=e9aeb26aeb) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [f675b70f23](https://linux-hardware.org/?probe=f675b70f23) | Jun 14, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [5cbee4094a](https://linux-hardware.org/?probe=5cbee4094a) | Jun 14, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [9a8a71741e](https://linux-hardware.org/?probe=9a8a71741e) | Jun 14, 2023 |
| Sony          | SVS1312J3EW                 | Notebook    | [6668ed0dbe](https://linux-hardware.org/?probe=6668ed0dbe) | Jun 14, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [a5cbd2e848](https://linux-hardware.org/?probe=a5cbd2e848) | Jun 14, 2023 |
| PC Special... | P65_P67RGRERA               | Notebook    | [49773a4767](https://linux-hardware.org/?probe=49773a4767) | Jun 14, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [143672bf6c](https://linux-hardware.org/?probe=143672bf6c) | Jun 14, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [b3b70ef13b](https://linux-hardware.org/?probe=b3b70ef13b) | Jun 14, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [9f26d41d53](https://linux-hardware.org/?probe=9f26d41d53) | Jun 14, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [20f84530c7](https://linux-hardware.org/?probe=20f84530c7) | Jun 14, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [d0187875be](https://linux-hardware.org/?probe=d0187875be) | Jun 13, 2023 |
| Medion        | Z370H4-EM                   | Desktop     | [e2df546273](https://linux-hardware.org/?probe=e2df546273) | Jun 13, 2023 |
| Medion        | Z370H4-EM                   | Desktop     | [bcfcd0b59d](https://linux-hardware.org/?probe=bcfcd0b59d) | Jun 13, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [1ede32fb28](https://linux-hardware.org/?probe=1ede32fb28) | Jun 13, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [0834ca7236](https://linux-hardware.org/?probe=0834ca7236) | Jun 13, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a22e7ac3ea](https://linux-hardware.org/?probe=a22e7ac3ea) | Jun 13, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [3ddafcad45](https://linux-hardware.org/?probe=3ddafcad45) | Jun 13, 2023 |
| Alienware     | m15 R7                      | Notebook    | [c4a2634a83](https://linux-hardware.org/?probe=c4a2634a83) | Jun 13, 2023 |
| Alienware     | m15 R7                      | Notebook    | [7b53840b8b](https://linux-hardware.org/?probe=7b53840b8b) | Jun 13, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [b303846ade](https://linux-hardware.org/?probe=b303846ade) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M58 7360PL9     | Desktop     | [da837e8612](https://linux-hardware.org/?probe=da837e8612) | Jun 13, 2023 |
| Toshiba       | Satellite P755              | Notebook    | [3b0c830987](https://linux-hardware.org/?probe=3b0c830987) | Jun 13, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0579a4f6f3](https://linux-hardware.org/?probe=0579a4f6f3) | Jun 13, 2023 |
| Dell          | Latitude E7250              | Notebook    | [cc9fc2bace](https://linux-hardware.org/?probe=cc9fc2bace) | Jun 13, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [794030a707](https://linux-hardware.org/?probe=794030a707) | Jun 12, 2023 |
| Dell          | 500                         | Notebook    | [b220c5553e](https://linux-hardware.org/?probe=b220c5553e) | Jun 12, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [aabb8192ee](https://linux-hardware.org/?probe=aabb8192ee) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b31d9c8e55](https://linux-hardware.org/?probe=b31d9c8e55) | Jun 12, 2023 |
| MSI           | B250M MORTAR ARCTIC         | Desktop     | [5e0e6586b7](https://linux-hardware.org/?probe=5e0e6586b7) | Jun 11, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [235239b42b](https://linux-hardware.org/?probe=235239b42b) | Jun 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [d2c4574d58](https://linux-hardware.org/?probe=d2c4574d58) | Jun 11, 2023 |
| Entroware     | Poseidon                    | Desktop     | [506bfb1a08](https://linux-hardware.org/?probe=506bfb1a08) | Jun 11, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [da1f33a87b](https://linux-hardware.org/?probe=da1f33a87b) | Jun 11, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 3 ... | Convertible | [786dd354ed](https://linux-hardware.org/?probe=786dd354ed) | Jun 11, 2023 |
| Dell          | Latitude 7480               | Notebook    | [03b8f5a162](https://linux-hardware.org/?probe=03b8f5a162) | Jun 11, 2023 |
| Dell          | Precision 5570              | Notebook    | [32975fdf08](https://linux-hardware.org/?probe=32975fdf08) | Jun 11, 2023 |
| ASUSTek       | GX501VIK                    | Notebook    | [e54a895262](https://linux-hardware.org/?probe=e54a895262) | Jun 11, 2023 |
| Intel         | DP45SG AAE27733-404         | Desktop     | [7abba8629e](https://linux-hardware.org/?probe=7abba8629e) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | Desktop     | [afaced265f](https://linux-hardware.org/?probe=afaced265f) | Jun 10, 2023 |
| HP            | 81B4                        | Desktop     | [2d7748536f](https://linux-hardware.org/?probe=2d7748536f) | Jun 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | Notebook    | [3d3375df75](https://linux-hardware.org/?probe=3d3375df75) | Jun 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [65a47406b0](https://linux-hardware.org/?probe=65a47406b0) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0XV0... | Notebook    | [b2f7d876c7](https://linux-hardware.org/?probe=b2f7d876c7) | Jun 10, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [63c110632a](https://linux-hardware.org/?probe=63c110632a) | Jun 10, 2023 |
| MSI           | Prestige 13Evo A13M         | Notebook    | [3feb3bce01](https://linux-hardware.org/?probe=3feb3bce01) | Jun 10, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [4b6aa9a912](https://linux-hardware.org/?probe=4b6aa9a912) | Jun 10, 2023 |
| Dell          | Latitude E5500              | Notebook    | [41ad12c465](https://linux-hardware.org/?probe=41ad12c465) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [246facab73](https://linux-hardware.org/?probe=246facab73) | Jun 10, 2023 |
| Sony          | VPCF120FD                   | Notebook    | [47f02bd498](https://linux-hardware.org/?probe=47f02bd498) | Jun 10, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [672a491915](https://linux-hardware.org/?probe=672a491915) | Jun 09, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [233dac6c68](https://linux-hardware.org/?probe=233dac6c68) | Jun 09, 2023 |
| Lenovo        | 3172 SDK0J40697 WIN 3305... | Mini pc     | [7f437dc929](https://linux-hardware.org/?probe=7f437dc929) | Jun 09, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [5ad9f9e0bf](https://linux-hardware.org/?probe=5ad9f9e0bf) | Jun 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [4f69ba649a](https://linux-hardware.org/?probe=4f69ba649a) | Jun 09, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c9f26e18c2](https://linux-hardware.org/?probe=c9f26e18c2) | Jun 09, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [c7ced127f8](https://linux-hardware.org/?probe=c7ced127f8) | Jun 09, 2023 |
| Dell          | Inspiron 15-5568            | Notebook    | [19b686b7d7](https://linux-hardware.org/?probe=19b686b7d7) | Jun 09, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [09ba95bf3b](https://linux-hardware.org/?probe=09ba95bf3b) | Jun 08, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| ASUSTek       | X455LA                      | Notebook    | [583596672d](https://linux-hardware.org/?probe=583596672d) | Jun 08, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [8fa2e2acc9](https://linux-hardware.org/?probe=8fa2e2acc9) | Jun 08, 2023 |
| AZW           | Green G4 10                 | Desktop     | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [b161b2177a](https://linux-hardware.org/?probe=b161b2177a) | Jun 08, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [92645b42ac](https://linux-hardware.org/?probe=92645b42ac) | Jun 08, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [5bec216150](https://linux-hardware.org/?probe=5bec216150) | Jun 08, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [7fa12c3607](https://linux-hardware.org/?probe=7fa12c3607) | Jun 08, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [c44abee9e7](https://linux-hardware.org/?probe=c44abee9e7) | Jun 08, 2023 |
| Gigabyte      | P2542                       | Notebook    | [12a2415432](https://linux-hardware.org/?probe=12a2415432) | Jun 08, 2023 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| MSI           | A88XM-E35                   | Desktop     | [efe1285363](https://linux-hardware.org/?probe=efe1285363) | Jun 07, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [ea8584cbda](https://linux-hardware.org/?probe=ea8584cbda) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [76ca69b8cc](https://linux-hardware.org/?probe=76ca69b8cc) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [3932ac5190](https://linux-hardware.org/?probe=3932ac5190) | Jun 07, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [9ea0a82205](https://linux-hardware.org/?probe=9ea0a82205) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ff2ebbb0ae](https://linux-hardware.org/?probe=ff2ebbb0ae) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | Notebook    | [265c19be27](https://linux-hardware.org/?probe=265c19be27) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [b0435761df](https://linux-hardware.org/?probe=b0435761df) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [a76212cc40](https://linux-hardware.org/?probe=a76212cc40) | Jun 07, 2023 |
| Dell          | 0R6PCT A01                  | Desktop     | [e1623fbc8e](https://linux-hardware.org/?probe=e1623fbc8e) | Jun 07, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [9d0aa12b81](https://linux-hardware.org/?probe=9d0aa12b81) | Jun 06, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e56988bf8e](https://linux-hardware.org/?probe=e56988bf8e) | Jun 06, 2023 |
| Dell          | Latitude 7480               | Notebook    | [61c800a3b4](https://linux-hardware.org/?probe=61c800a3b4) | Jun 06, 2023 |
| Notebook      | P65xHP                      | Notebook    | [bf35e218d7](https://linux-hardware.org/?probe=bf35e218d7) | Jun 06, 2023 |
| Dell          | 0RY007                      | Desktop     | [49c7cbbfde](https://linux-hardware.org/?probe=49c7cbbfde) | Jun 06, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [fe852e8a1d](https://linux-hardware.org/?probe=fe852e8a1d) | Jun 06, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [262ee566e1](https://linux-hardware.org/?probe=262ee566e1) | Jun 06, 2023 |
| Pegatron      | H81-M1                      | Desktop     | [2641e6773e](https://linux-hardware.org/?probe=2641e6773e) | Jun 05, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [0763f751ac](https://linux-hardware.org/?probe=0763f751ac) | Jun 05, 2023 |
| Notebook      | P65xHP                      | Notebook    | [51834b893c](https://linux-hardware.org/?probe=51834b893c) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [1c99e1316c](https://linux-hardware.org/?probe=1c99e1316c) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [60fb09bf5e](https://linux-hardware.org/?probe=60fb09bf5e) | Jun 05, 2023 |
| MECER         | MW10Q17                     | Tablet      | [36fd3d704b](https://linux-hardware.org/?probe=36fd3d704b) | Jun 05, 2023 |
| MECER         | MW10Q17                     | Tablet      | [3cdab95833](https://linux-hardware.org/?probe=3cdab95833) | Jun 05, 2023 |
| Unknown       | Unknown                     | Tablet      | [33c4d481d9](https://linux-hardware.org/?probe=33c4d481d9) | Jun 05, 2023 |
| MSI           | B250 GAMING PRO CARBON      | Desktop     | [32da3735d9](https://linux-hardware.org/?probe=32da3735d9) | Jun 05, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [a2c31cdc69](https://linux-hardware.org/?probe=a2c31cdc69) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-V                | Desktop     | [d0fd3fd90a](https://linux-hardware.org/?probe=d0fd3fd90a) | Jun 04, 2023 |
| ASUSTek       | PRIME Z590-V                | Desktop     | [bc93ac1588](https://linux-hardware.org/?probe=bc93ac1588) | Jun 04, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [d4bc6d6c8c](https://linux-hardware.org/?probe=d4bc6d6c8c) | Jun 04, 2023 |
| Sony          | VPCEH2H4E                   | Notebook    | [793e883d0c](https://linux-hardware.org/?probe=793e883d0c) | Jun 04, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [5c1f2cc0d3](https://linux-hardware.org/?probe=5c1f2cc0d3) | Jun 04, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5b7a78b32e](https://linux-hardware.org/?probe=5b7a78b32e) | Jun 04, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [969354604a](https://linux-hardware.org/?probe=969354604a) | Jun 04, 2023 |
| Dell          | Latitude E5520              | Notebook    | [7e2d1fdd22](https://linux-hardware.org/?probe=7e2d1fdd22) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [f39742476c](https://linux-hardware.org/?probe=f39742476c) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [efa49bf468](https://linux-hardware.org/?probe=efa49bf468) | Jun 04, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f472cba5a6](https://linux-hardware.org/?probe=f472cba5a6) | Jun 04, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [b9fd75507c](https://linux-hardware.org/?probe=b9fd75507c) | Jun 04, 2023 |
| Dell          | Latitude E5510              | Notebook    | [353a2174af](https://linux-hardware.org/?probe=353a2174af) | Jun 04, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [82542c4daa](https://linux-hardware.org/?probe=82542c4daa) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [0c8afa948b](https://linux-hardware.org/?probe=0c8afa948b) | Jun 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [6d8d7f6384](https://linux-hardware.org/?probe=6d8d7f6384) | Jun 04, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | Notebook    | [4f62d33d84](https://linux-hardware.org/?probe=4f62d33d84) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [aaed1b39af](https://linux-hardware.org/?probe=aaed1b39af) | Jun 03, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [8b790b76a6](https://linux-hardware.org/?probe=8b790b76a6) | Jun 03, 2023 |
| ASUSTek       | K52Je                       | Notebook    | [0190eef08c](https://linux-hardware.org/?probe=0190eef08c) | Jun 03, 2023 |
| Intel         | X99 V102                    | Desktop     | [ed5a67e8a5](https://linux-hardware.org/?probe=ed5a67e8a5) | Jun 03, 2023 |
| MSI           | H97M-G43                    | Desktop     | [6bd1b61977](https://linux-hardware.org/?probe=6bd1b61977) | Jun 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [8d783c6b00](https://linux-hardware.org/?probe=8d783c6b00) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [069b512b91](https://linux-hardware.org/?probe=069b512b91) | Jun 03, 2023 |
| Lenovo        | ThinkPad T420 4236WQD       | Notebook    | [69a63f31e1](https://linux-hardware.org/?probe=69a63f31e1) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [51868dd3c8](https://linux-hardware.org/?probe=51868dd3c8) | Jun 03, 2023 |
| HP            | ENVY 17                     | Notebook    | [79fd438f05](https://linux-hardware.org/?probe=79fd438f05) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [44571410f0](https://linux-hardware.org/?probe=44571410f0) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [d54d77b051](https://linux-hardware.org/?probe=d54d77b051) | Jun 03, 2023 |
| HP            | 3047h                       | Desktop     | [1825675e99](https://linux-hardware.org/?probe=1825675e99) | Jun 03, 2023 |
| MSI           | B250 GAMING PRO CARBON      | Desktop     | [ef7acf6baa](https://linux-hardware.org/?probe=ef7acf6baa) | Jun 03, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [93bdbbdafb](https://linux-hardware.org/?probe=93bdbbdafb) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [4e17d7c6e8](https://linux-hardware.org/?probe=4e17d7c6e8) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [965de576c7](https://linux-hardware.org/?probe=965de576c7) | Jun 03, 2023 |
| Dell          | Latitude 5491               | Notebook    | [6a8a7e6188](https://linux-hardware.org/?probe=6a8a7e6188) | Jun 03, 2023 |
| Dell          | 0RY007                      | Desktop     | [f3028ff55d](https://linux-hardware.org/?probe=f3028ff55d) | Jun 02, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [160d4525c6](https://linux-hardware.org/?probe=160d4525c6) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [fa4bd41f4b](https://linux-hardware.org/?probe=fa4bd41f4b) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [959b76650d](https://linux-hardware.org/?probe=959b76650d) | Jun 02, 2023 |
| Samsung       | 730QED                      | Convertible | [f447d7526c](https://linux-hardware.org/?probe=f447d7526c) | Jun 02, 2023 |
| Samsung       | 730QED                      | Convertible | [ca8f4d1ff7](https://linux-hardware.org/?probe=ca8f4d1ff7) | Jun 02, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [a080a07f52](https://linux-hardware.org/?probe=a080a07f52) | Jun 02, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [e94cab5008](https://linux-hardware.org/?probe=e94cab5008) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [1aea71b6c0](https://linux-hardware.org/?probe=1aea71b6c0) | Jun 02, 2023 |
| Unknown       | Unknown                     | Notebook    | [655398fc94](https://linux-hardware.org/?probe=655398fc94) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [1bdb74a8ba](https://linux-hardware.org/?probe=1bdb74a8ba) | Jun 02, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [8aab7c6536](https://linux-hardware.org/?probe=8aab7c6536) | Jun 01, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [e2d37b2d66](https://linux-hardware.org/?probe=e2d37b2d66) | Jun 01, 2023 |
| HP            | ProBook 6450b               | Notebook    | [d3d4e45f9d](https://linux-hardware.org/?probe=d3d4e45f9d) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [f66667b7fb](https://linux-hardware.org/?probe=f66667b7fb) | Jun 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [6d7803788d](https://linux-hardware.org/?probe=6d7803788d) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [8a69d6c123](https://linux-hardware.org/?probe=8a69d6c123) | Jun 01, 2023 |
| HP            | 83E2                        | Desktop     | [eaf5f90360](https://linux-hardware.org/?probe=eaf5f90360) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [ecfe7565f4](https://linux-hardware.org/?probe=ecfe7565f4) | Jun 01, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [e822eb4072](https://linux-hardware.org/?probe=e822eb4072) | Jun 01, 2023 |
| ASUSTek       | K53SK                       | Notebook    | [9b376cdd45](https://linux-hardware.org/?probe=9b376cdd45) | Jun 01, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [3fb05bfb0b](https://linux-hardware.org/?probe=3fb05bfb0b) | May 31, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3b9639141c](https://linux-hardware.org/?probe=3b9639141c) | May 31, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [560680687c](https://linux-hardware.org/?probe=560680687c) | May 31, 2023 |
| Dell          | 0RY007                      | Desktop     | [b726df555b](https://linux-hardware.org/?probe=b726df555b) | May 31, 2023 |
| Dell          | 0RY007                      | Desktop     | [32e931c79b](https://linux-hardware.org/?probe=32e931c79b) | May 31, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | Notebook    | [239faf8c55](https://linux-hardware.org/?probe=239faf8c55) | May 31, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [8630cfad52](https://linux-hardware.org/?probe=8630cfad52) | May 31, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [953ee1ef05](https://linux-hardware.org/?probe=953ee1ef05) | May 31, 2023 |
| Gigabyte      | X99-UD7 WIFI-CF             | Desktop     | [955e65b76f](https://linux-hardware.org/?probe=955e65b76f) | May 31, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [7c031081c5](https://linux-hardware.org/?probe=7c031081c5) | May 31, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [e45b1707bd](https://linux-hardware.org/?probe=e45b1707bd) | May 31, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [a8c97baf10](https://linux-hardware.org/?probe=a8c97baf10) | May 31, 2023 |
| ASUSTek       | ROG Strix G513RS_G513RS     | Notebook    | [69b1782cce](https://linux-hardware.org/?probe=69b1782cce) | May 31, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [0626de1b2a](https://linux-hardware.org/?probe=0626de1b2a) | May 31, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [2703e7856e](https://linux-hardware.org/?probe=2703e7856e) | May 30, 2023 |
| ASUSTek       | K53SK                       | Notebook    | [bfd926c8da](https://linux-hardware.org/?probe=bfd926c8da) | May 30, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [cdc6168586](https://linux-hardware.org/?probe=cdc6168586) | May 30, 2023 |
| Gigabyte      | P2542                       | Notebook    | [b1064cae7a](https://linux-hardware.org/?probe=b1064cae7a) | May 30, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [b79113b0b5](https://linux-hardware.org/?probe=b79113b0b5) | May 30, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [45e5adbb22](https://linux-hardware.org/?probe=45e5adbb22) | May 30, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e51e0ef0da](https://linux-hardware.org/?probe=e51e0ef0da) | May 30, 2023 |
| Gigabyte      | P2542                       | Notebook    | [7cded000f2](https://linux-hardware.org/?probe=7cded000f2) | May 30, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [0c3b8da8d5](https://linux-hardware.org/?probe=0c3b8da8d5) | May 30, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [dfe30c4e4a](https://linux-hardware.org/?probe=dfe30c4e4a) | May 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [8002face48](https://linux-hardware.org/?probe=8002face48) | May 30, 2023 |
| Intel         | DH61BF AAG81311-102         | Desktop     | [22123492ab](https://linux-hardware.org/?probe=22123492ab) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [cddd43859b](https://linux-hardware.org/?probe=cddd43859b) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [46f455ce35](https://linux-hardware.org/?probe=46f455ce35) | May 30, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [67c96085bf](https://linux-hardware.org/?probe=67c96085bf) | May 30, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [1e0fbe86da](https://linux-hardware.org/?probe=1e0fbe86da) | May 29, 2023 |
| Alienware     | x15 R1                      | Notebook    | [19e9b8e338](https://linux-hardware.org/?probe=19e9b8e338) | May 29, 2023 |
| ASUSTek       | ROG STRIX Z790-H GAMING ... | Desktop     | [11432ddeb6](https://linux-hardware.org/?probe=11432ddeb6) | May 29, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [312b05f0a4](https://linux-hardware.org/?probe=312b05f0a4) | May 29, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [e57b9850f8](https://linux-hardware.org/?probe=e57b9850f8) | May 28, 2023 |
| ALLDOCUBE     | i1405C                      | Notebook    | [7e4475ef13](https://linux-hardware.org/?probe=7e4475ef13) | May 28, 2023 |
| HP            | ProBook x360 435 G7         | Convertible | [8d113fecb4](https://linux-hardware.org/?probe=8d113fecb4) | May 28, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c2408a1885](https://linux-hardware.org/?probe=c2408a1885) | May 28, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [34d96aa1df](https://linux-hardware.org/?probe=34d96aa1df) | May 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [c7afdbbd76](https://linux-hardware.org/?probe=c7afdbbd76) | May 28, 2023 |
| AVITA         | NE14A2                      | Notebook    | [89c5edafbc](https://linux-hardware.org/?probe=89c5edafbc) | May 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | Notebook    | [618a907425](https://linux-hardware.org/?probe=618a907425) | May 27, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [2fadb86df4](https://linux-hardware.org/?probe=2fadb86df4) | May 27, 2023 |
| Dell          | Latitude 5440               | Notebook    | [9ed4f0e7ac](https://linux-hardware.org/?probe=9ed4f0e7ac) | May 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [c7566d1ab9](https://linux-hardware.org/?probe=c7566d1ab9) | May 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [5327e82af6](https://linux-hardware.org/?probe=5327e82af6) | May 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [57b9304725](https://linux-hardware.org/?probe=57b9304725) | May 27, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [18a13174aa](https://linux-hardware.org/?probe=18a13174aa) | May 27, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [7fce8e04b2](https://linux-hardware.org/?probe=7fce8e04b2) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [7e895c167b](https://linux-hardware.org/?probe=7e895c167b) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [526503fef7](https://linux-hardware.org/?probe=526503fef7) | May 27, 2023 |
| Dell          | Latitude 7480               | Notebook    | [2c74ec8198](https://linux-hardware.org/?probe=2c74ec8198) | May 27, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [3058a75499](https://linux-hardware.org/?probe=3058a75499) | May 26, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [433b367e58](https://linux-hardware.org/?probe=433b367e58) | May 26, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [ac85063e46](https://linux-hardware.org/?probe=ac85063e46) | May 26, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [b8bb801b93](https://linux-hardware.org/?probe=b8bb801b93) | May 26, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [a8c4cf6158](https://linux-hardware.org/?probe=a8c4cf6158) | May 26, 2023 |
| AAEON         | UP-CHCR1 V0.4               | Desktop     | [b77201e825](https://linux-hardware.org/?probe=b77201e825) | May 26, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [4572d76da5](https://linux-hardware.org/?probe=4572d76da5) | May 26, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [9683a94030](https://linux-hardware.org/?probe=9683a94030) | May 26, 2023 |
| HP            | 2B3B                        | All in one  | [7819836b92](https://linux-hardware.org/?probe=7819836b92) | May 26, 2023 |
| Acer          | Predator PT316-51s          | Notebook    | [0242988287](https://linux-hardware.org/?probe=0242988287) | May 26, 2023 |
| Dell          | 0RY007                      | Desktop     | [6fb4081584](https://linux-hardware.org/?probe=6fb4081584) | May 25, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [f9567774d9](https://linux-hardware.org/?probe=f9567774d9) | May 25, 2023 |
| HP            | ENVY Laptop 13-ah0503na     | Notebook    | [cdf2d7b4b4](https://linux-hardware.org/?probe=cdf2d7b4b4) | May 25, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [0316f8d274](https://linux-hardware.org/?probe=0316f8d274) | May 25, 2023 |
| Lenovo        | ThinkPad T580 20LAS62M07    | Notebook    | [48ad025649](https://linux-hardware.org/?probe=48ad025649) | May 25, 2023 |
| Google        | Akali 360                   | Notebook    | [2a4bbc5d81](https://linux-hardware.org/?probe=2a4bbc5d81) | May 25, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [e55e554596](https://linux-hardware.org/?probe=e55e554596) | May 25, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [53cbfa6255](https://linux-hardware.org/?probe=53cbfa6255) | May 25, 2023 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [55790e804a](https://linux-hardware.org/?probe=55790e804a) | May 25, 2023 |
| Toshiba       | Satellite Pro C650          | Notebook    | [50fc04b16c](https://linux-hardware.org/?probe=50fc04b16c) | May 25, 2023 |
| Mediacom      | SMARTBOOK ONE               | Notebook    | [ad010a6b3e](https://linux-hardware.org/?probe=ad010a6b3e) | May 25, 2023 |
| Dell          | 03KWTV A02                  | Desktop     | [60ade2d50f](https://linux-hardware.org/?probe=60ade2d50f) | May 25, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [b291f783a2](https://linux-hardware.org/?probe=b291f783a2) | May 25, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [a7274d19af](https://linux-hardware.org/?probe=a7274d19af) | May 24, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [7a892801c0](https://linux-hardware.org/?probe=7a892801c0) | May 24, 2023 |
| Dell          | Latitude 7390               | Notebook    | [999bb94a31](https://linux-hardware.org/?probe=999bb94a31) | May 24, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [a2a31dbbee](https://linux-hardware.org/?probe=a2a31dbbee) | May 24, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [9486b7ca4f](https://linux-hardware.org/?probe=9486b7ca4f) | May 24, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [810c2ac411](https://linux-hardware.org/?probe=810c2ac411) | May 24, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [4c512786cc](https://linux-hardware.org/?probe=4c512786cc) | May 24, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [da0b980bc3](https://linux-hardware.org/?probe=da0b980bc3) | May 24, 2023 |
| Allview       | Allbook H                   | Notebook    | [8b0c0a3436](https://linux-hardware.org/?probe=8b0c0a3436) | May 24, 2023 |
| Dell          | Precision 3571              | Notebook    | [3806fcdb9c](https://linux-hardware.org/?probe=3806fcdb9c) | May 24, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | Notebook    | [306ecade71](https://linux-hardware.org/?probe=306ecade71) | May 24, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [c9eaabeb95](https://linux-hardware.org/?probe=c9eaabeb95) | May 24, 2023 |
| HP            | Pavilion dv5                | Notebook    | [2906e3ff3b](https://linux-hardware.org/?probe=2906e3ff3b) | May 24, 2023 |
| HP            | 15                          | Notebook    | [b62229cac1](https://linux-hardware.org/?probe=b62229cac1) | May 24, 2023 |
| ASUSTek       | Z87-DELUXE/DUAL             | Desktop     | [0f0c4f64ce](https://linux-hardware.org/?probe=0f0c4f64ce) | May 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ed936908c9](https://linux-hardware.org/?probe=ed936908c9) | May 23, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [4c3c861f80](https://linux-hardware.org/?probe=4c3c861f80) | May 23, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | Notebook    | [77f092da32](https://linux-hardware.org/?probe=77f092da32) | May 23, 2023 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [a36e076c17](https://linux-hardware.org/?probe=a36e076c17) | May 23, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3cb0dd251d](https://linux-hardware.org/?probe=3cb0dd251d) | May 23, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [a92437f5aa](https://linux-hardware.org/?probe=a92437f5aa) | May 23, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [674b64f381](https://linux-hardware.org/?probe=674b64f381) | May 23, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [73d0ff64b6](https://linux-hardware.org/?probe=73d0ff64b6) | May 23, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [3740264eb0](https://linux-hardware.org/?probe=3740264eb0) | May 23, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [431f2db1fc](https://linux-hardware.org/?probe=431f2db1fc) | May 23, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [241bd90f1f](https://linux-hardware.org/?probe=241bd90f1f) | May 23, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [fe7d1e1f90](https://linux-hardware.org/?probe=fe7d1e1f90) | May 22, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [2afda2396c](https://linux-hardware.org/?probe=2afda2396c) | May 22, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [702a597b36](https://linux-hardware.org/?probe=702a597b36) | May 22, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [8b3acda484](https://linux-hardware.org/?probe=8b3acda484) | May 22, 2023 |
| Acer          | Swift SF514-56T             | Notebook    | [81a0e002b7](https://linux-hardware.org/?probe=81a0e002b7) | May 22, 2023 |
| Dell          | Latitude 3420               | Notebook    | [d598f2634f](https://linux-hardware.org/?probe=d598f2634f) | May 22, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [76bd19169a](https://linux-hardware.org/?probe=76bd19169a) | May 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS1GQ00    | Notebook    | [1ea9bac322](https://linux-hardware.org/?probe=1ea9bac322) | May 22, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 80XB     | Convertible | [f783691b47](https://linux-hardware.org/?probe=f783691b47) | May 22, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [11c329d15a](https://linux-hardware.org/?probe=11c329d15a) | May 22, 2023 |
| Dell          | Inspiron 7590 2n1           | Convertible | [15f4105418](https://linux-hardware.org/?probe=15f4105418) | May 22, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [4051f4b27d](https://linux-hardware.org/?probe=4051f4b27d) | May 22, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [e3ea42dd02](https://linux-hardware.org/?probe=e3ea42dd02) | May 22, 2023 |
| Unknown       | DT138IB                     | Desktop     | [130e17f9e3](https://linux-hardware.org/?probe=130e17f9e3) | May 21, 2023 |
| Acer          | TravelMate Spin P414RN-4... | Convertible | [cb8bc926b8](https://linux-hardware.org/?probe=cb8bc926b8) | May 21, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [55a289b426](https://linux-hardware.org/?probe=55a289b426) | May 21, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [d29f7a36f9](https://linux-hardware.org/?probe=d29f7a36f9) | May 21, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [f511a54601](https://linux-hardware.org/?probe=f511a54601) | May 21, 2023 |
| Dell          | Latitude E6530              | Notebook    | [7c04efc558](https://linux-hardware.org/?probe=7c04efc558) | May 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [4a68db15c2](https://linux-hardware.org/?probe=4a68db15c2) | May 21, 2023 |
| ASUSTek       | ROG Flow X13 GV302XI_GV3... | Convertible | [5d4070956a](https://linux-hardware.org/?probe=5d4070956a) | May 21, 2023 |
| HP            | 2B3B                        | All in one  | [2ed92e9c21](https://linux-hardware.org/?probe=2ed92e9c21) | May 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [596f37cc9d](https://linux-hardware.org/?probe=596f37cc9d) | May 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8952bab351](https://linux-hardware.org/?probe=8952bab351) | May 21, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [88cf891056](https://linux-hardware.org/?probe=88cf891056) | May 21, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [ab706a91d4](https://linux-hardware.org/?probe=ab706a91d4) | May 20, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [166b73ef05](https://linux-hardware.org/?probe=166b73ef05) | May 20, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [d549fb62db](https://linux-hardware.org/?probe=d549fb62db) | May 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c242460e72](https://linux-hardware.org/?probe=c242460e72) | May 20, 2023 |
| HP            | 8055                        | Desktop     | [ddfca600c1](https://linux-hardware.org/?probe=ddfca600c1) | May 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [17ac43247a](https://linux-hardware.org/?probe=17ac43247a) | May 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [c7157cc723](https://linux-hardware.org/?probe=c7157cc723) | May 20, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [c6ce2f365a](https://linux-hardware.org/?probe=c6ce2f365a) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [de162ff16c](https://linux-hardware.org/?probe=de162ff16c) | May 20, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [5da7add39a](https://linux-hardware.org/?probe=5da7add39a) | May 20, 2023 |
| HP            | 8055                        | Desktop     | [d7b466e881](https://linux-hardware.org/?probe=d7b466e881) | May 20, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [105fb43fc1](https://linux-hardware.org/?probe=105fb43fc1) | May 20, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [42ab4c7e67](https://linux-hardware.org/?probe=42ab4c7e67) | May 20, 2023 |
| AZW           | SER V01                     | Mini pc     | [e0c2283aa1](https://linux-hardware.org/?probe=e0c2283aa1) | May 20, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [b60db9bc14](https://linux-hardware.org/?probe=b60db9bc14) | May 20, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [e168b46b94](https://linux-hardware.org/?probe=e168b46b94) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9f1830f264](https://linux-hardware.org/?probe=9f1830f264) | May 19, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [061e1e2aec](https://linux-hardware.org/?probe=061e1e2aec) | May 19, 2023 |
| ASUSTek       | PRIME B650M-A II            | Desktop     | [183b85c77c](https://linux-hardware.org/?probe=183b85c77c) | May 19, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [9dbbfc6c8e](https://linux-hardware.org/?probe=9dbbfc6c8e) | May 19, 2023 |
| Gigabyte      | H67A-D3H-B3                 | Desktop     | [606bb335e6](https://linux-hardware.org/?probe=606bb335e6) | May 19, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [f79cecb83e](https://linux-hardware.org/?probe=f79cecb83e) | May 19, 2023 |
| MSI           | VR601                       | Notebook    | [7f9381407d](https://linux-hardware.org/?probe=7f9381407d) | May 19, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [e4b87f1e56](https://linux-hardware.org/?probe=e4b87f1e56) | May 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [5bac34a5f5](https://linux-hardware.org/?probe=5bac34a5f5) | May 19, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [a8bb37c78e](https://linux-hardware.org/?probe=a8bb37c78e) | May 19, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [9475bc847b](https://linux-hardware.org/?probe=9475bc847b) | May 19, 2023 |
| MSI           | MS-B9311                    | Desktop     | [3cfc1fbb83](https://linux-hardware.org/?probe=3cfc1fbb83) | May 19, 2023 |
| HP            | Pavilion dv6                | Notebook    | [4fb1281981](https://linux-hardware.org/?probe=4fb1281981) | May 18, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d8d391a609](https://linux-hardware.org/?probe=d8d391a609) | May 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [7af74c5864](https://linux-hardware.org/?probe=7af74c5864) | May 18, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [87418d1634](https://linux-hardware.org/?probe=87418d1634) | May 18, 2023 |
| Acer          | TravelMate Spin P414RN-4... | Convertible | [69d4abb6e4](https://linux-hardware.org/?probe=69d4abb6e4) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [161776168b](https://linux-hardware.org/?probe=161776168b) | May 18, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [c3626b71ae](https://linux-hardware.org/?probe=c3626b71ae) | May 18, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [52ee676c29](https://linux-hardware.org/?probe=52ee676c29) | May 18, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | Notebook    | [e17fc662cc](https://linux-hardware.org/?probe=e17fc662cc) | May 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [b5d454d4ec](https://linux-hardware.org/?probe=b5d454d4ec) | May 18, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | Notebook    | [d1569df0f6](https://linux-hardware.org/?probe=d1569df0f6) | May 18, 2023 |
| Gateway       | DS10G                       | Desktop     | [556a92e56a](https://linux-hardware.org/?probe=556a92e56a) | May 18, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [9d66e80652](https://linux-hardware.org/?probe=9d66e80652) | May 18, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [1923d74fbc](https://linux-hardware.org/?probe=1923d74fbc) | May 18, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [59902928be](https://linux-hardware.org/?probe=59902928be) | May 18, 2023 |
| Dell          | Precision 5570              | Notebook    | [c9e52e6e8c](https://linux-hardware.org/?probe=c9e52e6e8c) | May 18, 2023 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [41971afc9c](https://linux-hardware.org/?probe=41971afc9c) | May 17, 2023 |
| HP            | ProBook x360 435 G7         | Convertible | [073a6b791a](https://linux-hardware.org/?probe=073a6b791a) | May 17, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [07a430eb2b](https://linux-hardware.org/?probe=07a430eb2b) | May 17, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3c3f22e8c7](https://linux-hardware.org/?probe=3c3f22e8c7) | May 17, 2023 |
| Dell          | 0M3F6C A01                  | Desktop     | [d0fc9b65d0](https://linux-hardware.org/?probe=d0fc9b65d0) | May 17, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [89e05e4477](https://linux-hardware.org/?probe=89e05e4477) | May 17, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [74b2c2122c](https://linux-hardware.org/?probe=74b2c2122c) | May 17, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e6064ac95c](https://linux-hardware.org/?probe=e6064ac95c) | May 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [478f988430](https://linux-hardware.org/?probe=478f988430) | May 16, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [f7c208d0f0](https://linux-hardware.org/?probe=f7c208d0f0) | May 16, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [212936564d](https://linux-hardware.org/?probe=212936564d) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [5553ae2ec9](https://linux-hardware.org/?probe=5553ae2ec9) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [f297fbda85](https://linux-hardware.org/?probe=f297fbda85) | May 16, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [9ea7971a18](https://linux-hardware.org/?probe=9ea7971a18) | May 16, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | Notebook    | [58b895e713](https://linux-hardware.org/?probe=58b895e713) | May 16, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [df01be5efd](https://linux-hardware.org/?probe=df01be5efd) | May 16, 2023 |
| Dell          | 0WXD1Y A01                  | Server      | [9d5a4b579e](https://linux-hardware.org/?probe=9d5a4b579e) | May 16, 2023 |
| Intel         | H61                         | Desktop     | [c54c89a4b1](https://linux-hardware.org/?probe=c54c89a4b1) | May 16, 2023 |
| MSI           | 3664h                       | Desktop     | [b45eee9c3a](https://linux-hardware.org/?probe=b45eee9c3a) | May 16, 2023 |
| HP            | 8055                        | Desktop     | [639cc3308f](https://linux-hardware.org/?probe=639cc3308f) | May 16, 2023 |
| HP            | 8055                        | Desktop     | [15c8401c45](https://linux-hardware.org/?probe=15c8401c45) | May 16, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [82db8cdf8a](https://linux-hardware.org/?probe=82db8cdf8a) | May 15, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ba609eb1e6](https://linux-hardware.org/?probe=ba609eb1e6) | May 15, 2023 |
| HP            | 3397                        | Desktop     | [3cfe6e2812](https://linux-hardware.org/?probe=3cfe6e2812) | May 15, 2023 |
| Dell          | 0KV3RP A00                  | Desktop     | [d324b5e64d](https://linux-hardware.org/?probe=d324b5e64d) | May 15, 2023 |
| Intel         | DX79SI AAG28808-600         | Desktop     | [d222ee2f89](https://linux-hardware.org/?probe=d222ee2f89) | May 14, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [9cda219db5](https://linux-hardware.org/?probe=9cda219db5) | May 14, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [656e811dfb](https://linux-hardware.org/?probe=656e811dfb) | May 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [a2c1fd19aa](https://linux-hardware.org/?probe=a2c1fd19aa) | May 14, 2023 |
| Lenovo        | NOK                         | Desktop     | [9c6f0bae8f](https://linux-hardware.org/?probe=9c6f0bae8f) | May 14, 2023 |
| Acer          | Aspire A717-72G             | Notebook    | [1ab0673015](https://linux-hardware.org/?probe=1ab0673015) | May 14, 2023 |
| Acer          | Aspire A717-72G             | Notebook    | [62a46acc18](https://linux-hardware.org/?probe=62a46acc18) | May 14, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b08b887e1a](https://linux-hardware.org/?probe=b08b887e1a) | May 14, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [423359d677](https://linux-hardware.org/?probe=423359d677) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [020d4612bd](https://linux-hardware.org/?probe=020d4612bd) | May 14, 2023 |
| HP            | Notebook                    | Notebook    | [decd46d3ed](https://linux-hardware.org/?probe=decd46d3ed) | May 14, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [66ae15a360](https://linux-hardware.org/?probe=66ae15a360) | May 14, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [274fbdb43e](https://linux-hardware.org/?probe=274fbdb43e) | May 14, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [821d79dc3f](https://linux-hardware.org/?probe=821d79dc3f) | May 14, 2023 |
| Gigabyte      | 970A-DS3                    | Desktop     | [97ef085eca](https://linux-hardware.org/?probe=97ef085eca) | May 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [07bf228811](https://linux-hardware.org/?probe=07bf228811) | May 14, 2023 |
| MSI           | GS75 Stealth 10SFS          | Notebook    | [a2116b61ea](https://linux-hardware.org/?probe=a2116b61ea) | May 14, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [803f9dba3c](https://linux-hardware.org/?probe=803f9dba3c) | May 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [09eb36df64](https://linux-hardware.org/?probe=09eb36df64) | May 13, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [d06731c12e](https://linux-hardware.org/?probe=d06731c12e) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [5768cd981e](https://linux-hardware.org/?probe=5768cd981e) | May 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a8c81eafb0](https://linux-hardware.org/?probe=a8c81eafb0) | May 13, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [bfff1b604f](https://linux-hardware.org/?probe=bfff1b604f) | May 13, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [4491067060](https://linux-hardware.org/?probe=4491067060) | May 13, 2023 |
| Dell          | 0D883F A05                  | Desktop     | [99e782e805](https://linux-hardware.org/?probe=99e782e805) | May 13, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [66bff684b7](https://linux-hardware.org/?probe=66bff684b7) | May 13, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [6d362f8c74](https://linux-hardware.org/?probe=6d362f8c74) | May 13, 2023 |
| HP            | 2B3B                        | All in one  | [4785289345](https://linux-hardware.org/?probe=4785289345) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [14eae60f4f](https://linux-hardware.org/?probe=14eae60f4f) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [7ac717a41d](https://linux-hardware.org/?probe=7ac717a41d) | May 13, 2023 |
| Samsung       | 960XFH                      | Notebook    | [6d6b4a9c5e](https://linux-hardware.org/?probe=6d6b4a9c5e) | May 12, 2023 |
| Intel         | DG43GT AAE62768-303         | Desktop     | [4cc21b00e7](https://linux-hardware.org/?probe=4cc21b00e7) | May 12, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | Notebook    | [795e44d159](https://linux-hardware.org/?probe=795e44d159) | May 12, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [f39ba53533](https://linux-hardware.org/?probe=f39ba53533) | May 12, 2023 |
| HP            | Stream Notebook             | Notebook    | [5ed3be74da](https://linux-hardware.org/?probe=5ed3be74da) | May 12, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [ceea346358](https://linux-hardware.org/?probe=ceea346358) | May 12, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [576d66cba7](https://linux-hardware.org/?probe=576d66cba7) | May 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [8375f52559](https://linux-hardware.org/?probe=8375f52559) | May 12, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [80158c51fb](https://linux-hardware.org/?probe=80158c51fb) | May 12, 2023 |
| HP            | 2B3B                        | All in one  | [a4c65ac28f](https://linux-hardware.org/?probe=a4c65ac28f) | May 12, 2023 |
| HP            | 2B3B                        | All in one  | [ca83ed5e3f](https://linux-hardware.org/?probe=ca83ed5e3f) | May 12, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [81f86e6678](https://linux-hardware.org/?probe=81f86e6678) | May 11, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [988367a195](https://linux-hardware.org/?probe=988367a195) | May 11, 2023 |
| Rombica       | myBook Zenith               | Notebook    | [f7438f1448](https://linux-hardware.org/?probe=f7438f1448) | May 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ecb43775d1](https://linux-hardware.org/?probe=ecb43775d1) | May 11, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [f9c1eb381f](https://linux-hardware.org/?probe=f9c1eb381f) | May 11, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [33f3e64e8f](https://linux-hardware.org/?probe=33f3e64e8f) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [dbf711a2f5](https://linux-hardware.org/?probe=dbf711a2f5) | May 11, 2023 |
| Apple         | Mac-F2218EC8                | All in one  | [6cab4970b0](https://linux-hardware.org/?probe=6cab4970b0) | May 11, 2023 |
| Dell          | 0GU083 A00                  | Desktop     | [eec8f60d12](https://linux-hardware.org/?probe=eec8f60d12) | May 11, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [622dd024aa](https://linux-hardware.org/?probe=622dd024aa) | May 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [3fbabd3df0](https://linux-hardware.org/?probe=3fbabd3df0) | May 11, 2023 |
| Dell          | Latitude 5490               | Notebook    | [2cba18ddec](https://linux-hardware.org/?probe=2cba18ddec) | May 11, 2023 |
| Lenovo        | Yoga 7 14IRL8 82YL          | Notebook    | [ae2fd3b0ae](https://linux-hardware.org/?probe=ae2fd3b0ae) | May 11, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [7995d3740a](https://linux-hardware.org/?probe=7995d3740a) | May 10, 2023 |
| MSI           | Stealth 14Studio A13VE      | Notebook    | [86f43bbff1](https://linux-hardware.org/?probe=86f43bbff1) | May 10, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [2864ff8227](https://linux-hardware.org/?probe=2864ff8227) | May 10, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [99af0c1e17](https://linux-hardware.org/?probe=99af0c1e17) | May 10, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e4b3bba2b5](https://linux-hardware.org/?probe=e4b3bba2b5) | May 10, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [297c4b54d4](https://linux-hardware.org/?probe=297c4b54d4) | May 10, 2023 |
| Acer          | Aspire 3935                 | Notebook    | [39cbd19b39](https://linux-hardware.org/?probe=39cbd19b39) | May 10, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [df94e4a72a](https://linux-hardware.org/?probe=df94e4a72a) | May 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [2e58ce6bd7](https://linux-hardware.org/?probe=2e58ce6bd7) | May 10, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [9f509a2647](https://linux-hardware.org/?probe=9f509a2647) | May 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5f4146c326](https://linux-hardware.org/?probe=5f4146c326) | May 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [87e3ae6f24](https://linux-hardware.org/?probe=87e3ae6f24) | May 10, 2023 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [39b8aee709](https://linux-hardware.org/?probe=39b8aee709) | May 10, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [1e41703eca](https://linux-hardware.org/?probe=1e41703eca) | May 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [727163d7b9](https://linux-hardware.org/?probe=727163d7b9) | May 09, 2023 |
| ASRock        | Z97 Extreme4                | Desktop     | [5803f15c1d](https://linux-hardware.org/?probe=5803f15c1d) | May 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [669dc67190](https://linux-hardware.org/?probe=669dc67190) | May 09, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [af31929040](https://linux-hardware.org/?probe=af31929040) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [8ca147188a](https://linux-hardware.org/?probe=8ca147188a) | May 09, 2023 |
| Acer          | Aspire TC-1760              | Desktop     | [24664f3383](https://linux-hardware.org/?probe=24664f3383) | May 09, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [de7b924fdb](https://linux-hardware.org/?probe=de7b924fdb) | May 08, 2023 |
| Medion        | E6234                       | Notebook    | [6c3bd7d77f](https://linux-hardware.org/?probe=6c3bd7d77f) | May 08, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [ba32d27df1](https://linux-hardware.org/?probe=ba32d27df1) | May 08, 2023 |
| HP            | 625                         | Notebook    | [956346de67](https://linux-hardware.org/?probe=956346de67) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0628913a60](https://linux-hardware.org/?probe=0628913a60) | May 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | Notebook    | [db609197b4](https://linux-hardware.org/?probe=db609197b4) | May 08, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [83c0648d66](https://linux-hardware.org/?probe=83c0648d66) | May 08, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [7934eebd9b](https://linux-hardware.org/?probe=7934eebd9b) | May 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7f274b189d](https://linux-hardware.org/?probe=7f274b189d) | May 08, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [ec04c034d3](https://linux-hardware.org/?probe=ec04c034d3) | May 08, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f23fb5cca0](https://linux-hardware.org/?probe=f23fb5cca0) | May 08, 2023 |
| HP            | Meep                        | Notebook    | [4b99a0c5f8](https://linux-hardware.org/?probe=4b99a0c5f8) | May 08, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a8d45ac430](https://linux-hardware.org/?probe=a8d45ac430) | May 07, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [c437a16a33](https://linux-hardware.org/?probe=c437a16a33) | May 07, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [a312f0545f](https://linux-hardware.org/?probe=a312f0545f) | May 07, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [9a068c66d5](https://linux-hardware.org/?probe=9a068c66d5) | May 07, 2023 |
| Medion        | E6234                       | Notebook    | [5afe99ed93](https://linux-hardware.org/?probe=5afe99ed93) | May 07, 2023 |
| Gigabyte      | Z690 AERO G                 | Desktop     | [7673380766](https://linux-hardware.org/?probe=7673380766) | May 07, 2023 |
| HP            | Meep                        | Notebook    | [46a81f105c](https://linux-hardware.org/?probe=46a81f105c) | May 07, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [b4e9bb9147](https://linux-hardware.org/?probe=b4e9bb9147) | May 07, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [febe8d60fc](https://linux-hardware.org/?probe=febe8d60fc) | May 07, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [2e25cad4b3](https://linux-hardware.org/?probe=2e25cad4b3) | May 07, 2023 |
| Razer         | Blade                       | Notebook    | [d90bda8f52](https://linux-hardware.org/?probe=d90bda8f52) | May 07, 2023 |
| Dell          | Latitude 5290               | Notebook    | [255da608b8](https://linux-hardware.org/?probe=255da608b8) | May 07, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [5e91733408](https://linux-hardware.org/?probe=5e91733408) | May 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [9355511511](https://linux-hardware.org/?probe=9355511511) | May 07, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [d5f70fc2eb](https://linux-hardware.org/?probe=d5f70fc2eb) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [50b503ae3e](https://linux-hardware.org/?probe=50b503ae3e) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [64bbfa416b](https://linux-hardware.org/?probe=64bbfa416b) | May 07, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [abc9ce4fa4](https://linux-hardware.org/?probe=abc9ce4fa4) | May 06, 2023 |
| Dell          | Latitude E6410              | Notebook    | [535fd92f64](https://linux-hardware.org/?probe=535fd92f64) | May 06, 2023 |
| Dell          | Latitude E4200              | Notebook    | [af2baa1787](https://linux-hardware.org/?probe=af2baa1787) | May 06, 2023 |
| ASUSTek       | M11BB                       | Desktop     | [35d2ca0280](https://linux-hardware.org/?probe=35d2ca0280) | May 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6a4a95e86f](https://linux-hardware.org/?probe=6a4a95e86f) | May 06, 2023 |
| Google        | Zako                        | Desktop     | [5d6aa6c0df](https://linux-hardware.org/?probe=5d6aa6c0df) | May 06, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [d4b401ef3f](https://linux-hardware.org/?probe=d4b401ef3f) | May 06, 2023 |
| ASUSTek       | Q405UA                      | Convertible | [f8f69fc110](https://linux-hardware.org/?probe=f8f69fc110) | May 06, 2023 |
| Dell          | Vostro 3360                 | Notebook    | [13a1e30b53](https://linux-hardware.org/?probe=13a1e30b53) | May 06, 2023 |
| Dell          | Precision 7740              | Notebook    | [4cd3b0701e](https://linux-hardware.org/?probe=4cd3b0701e) | May 06, 2023 |
| ASRock        | Z97 Extreme4                | Desktop     | [7b83def3e1](https://linux-hardware.org/?probe=7b83def3e1) | May 06, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [ecdd99c704](https://linux-hardware.org/?probe=ecdd99c704) | May 05, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7cf447e261](https://linux-hardware.org/?probe=7cf447e261) | May 05, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [6c96dbe3f3](https://linux-hardware.org/?probe=6c96dbe3f3) | May 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [9e469df99e](https://linux-hardware.org/?probe=9e469df99e) | May 05, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [af27e2497a](https://linux-hardware.org/?probe=af27e2497a) | May 05, 2023 |
| Toshiba       | PORTEGE Z30t-A              | Notebook    | [18cc14eee0](https://linux-hardware.org/?probe=18cc14eee0) | May 05, 2023 |
| HP            | 212B                        | Desktop     | [d71b834a1c](https://linux-hardware.org/?probe=d71b834a1c) | May 05, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0da080327f](https://linux-hardware.org/?probe=0da080327f) | May 05, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [d63ef842c1](https://linux-hardware.org/?probe=d63ef842c1) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b9cfd37540](https://linux-hardware.org/?probe=b9cfd37540) | May 05, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [1bc88df7d6](https://linux-hardware.org/?probe=1bc88df7d6) | May 05, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2fb5ac306a](https://linux-hardware.org/?probe=2fb5ac306a) | May 04, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [14a87bc11a](https://linux-hardware.org/?probe=14a87bc11a) | May 04, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [2f3264f25f](https://linux-hardware.org/?probe=2f3264f25f) | May 04, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 3 ... | Convertible | [23d2c52019](https://linux-hardware.org/?probe=23d2c52019) | May 04, 2023 |
| Google        | Meep                        | Notebook    | [1e5e0e6673](https://linux-hardware.org/?probe=1e5e0e6673) | May 04, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [8864ce10e7](https://linux-hardware.org/?probe=8864ce10e7) | May 03, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [8ef1ddf82a](https://linux-hardware.org/?probe=8ef1ddf82a) | May 03, 2023 |
| Dell          | 0RY007                      | Desktop     | [3ec4846de7](https://linux-hardware.org/?probe=3ec4846de7) | May 03, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [b8764f73bc](https://linux-hardware.org/?probe=b8764f73bc) | May 03, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [da5caa8155](https://linux-hardware.org/?probe=da5caa8155) | May 03, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | Notebook    | [bb924b0c19](https://linux-hardware.org/?probe=bb924b0c19) | May 03, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [3ec0caf9e8](https://linux-hardware.org/?probe=3ec0caf9e8) | May 03, 2023 |
| MSI           | Katana GF66 12UE            | Notebook    | [799a951714](https://linux-hardware.org/?probe=799a951714) | May 03, 2023 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [cd68a79e95](https://linux-hardware.org/?probe=cd68a79e95) | May 03, 2023 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [47ff74d363](https://linux-hardware.org/?probe=47ff74d363) | May 03, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [560b69d616](https://linux-hardware.org/?probe=560b69d616) | May 03, 2023 |
| Lenovo        | IdeaCentre K320 10031       | Desktop     | [86fc44372c](https://linux-hardware.org/?probe=86fc44372c) | May 03, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [81a4d2ac8b](https://linux-hardware.org/?probe=81a4d2ac8b) | May 03, 2023 |
| Dell          | 0RY007                      | Desktop     | [54e2c92bb9](https://linux-hardware.org/?probe=54e2c92bb9) | May 02, 2023 |
| HP            | 198E                        | Desktop     | [9c02a85763](https://linux-hardware.org/?probe=9c02a85763) | May 02, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [46ecc78df6](https://linux-hardware.org/?probe=46ecc78df6) | May 02, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [a31ef5e00e](https://linux-hardware.org/?probe=a31ef5e00e) | May 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0dd7d869b2](https://linux-hardware.org/?probe=0dd7d869b2) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [983ec204ab](https://linux-hardware.org/?probe=983ec204ab) | May 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5101f4e19d](https://linux-hardware.org/?probe=5101f4e19d) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [000c0450b9](https://linux-hardware.org/?probe=000c0450b9) | May 02, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [ed4aeb2282](https://linux-hardware.org/?probe=ed4aeb2282) | May 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [1362f2e3df](https://linux-hardware.org/?probe=1362f2e3df) | May 02, 2023 |
| HP            | Notebook                    | Notebook    | [749fa6a38e](https://linux-hardware.org/?probe=749fa6a38e) | May 02, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [e26aee893f](https://linux-hardware.org/?probe=e26aee893f) | May 01, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3a9a2590e3](https://linux-hardware.org/?probe=3a9a2590e3) | May 01, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [3c422c5e96](https://linux-hardware.org/?probe=3c422c5e96) | May 01, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [7b4e78233a](https://linux-hardware.org/?probe=7b4e78233a) | May 01, 2023 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [211eb49a00](https://linux-hardware.org/?probe=211eb49a00) | May 01, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3be920565f](https://linux-hardware.org/?probe=3be920565f) | May 01, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [03edfd3da7](https://linux-hardware.org/?probe=03edfd3da7) | May 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [22cf2ddf02](https://linux-hardware.org/?probe=22cf2ddf02) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [e89da96576](https://linux-hardware.org/?probe=e89da96576) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0aa06876c7](https://linux-hardware.org/?probe=0aa06876c7) | May 01, 2023 |
| Shuttle       | FS35V4                      | Desktop     | [137fda9bc6](https://linux-hardware.org/?probe=137fda9bc6) | May 01, 2023 |
| Medion        | E16402                      | Notebook    | [cff2f785ad](https://linux-hardware.org/?probe=cff2f785ad) | May 01, 2023 |
| Dell          | Latitude E6400              | Notebook    | [33b7764234](https://linux-hardware.org/?probe=33b7764234) | May 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5cfdd30fa7](https://linux-hardware.org/?probe=5cfdd30fa7) | May 01, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [aa8e8397f6](https://linux-hardware.org/?probe=aa8e8397f6) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5002NAU    | Notebook    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [c490c44357](https://linux-hardware.org/?probe=c490c44357) | May 01, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [4bec088d90](https://linux-hardware.org/?probe=4bec088d90) | Apr 30, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [705ff684a9](https://linux-hardware.org/?probe=705ff684a9) | Apr 30, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [93fef964a7](https://linux-hardware.org/?probe=93fef964a7) | Apr 30, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [467bb5ded2](https://linux-hardware.org/?probe=467bb5ded2) | Apr 30, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [9a1d443928](https://linux-hardware.org/?probe=9a1d443928) | Apr 30, 2023 |
| Samsung       | 950XED                      | Notebook    | [41f620de17](https://linux-hardware.org/?probe=41f620de17) | Apr 30, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [1714bffa0e](https://linux-hardware.org/?probe=1714bffa0e) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | Desktop     | [233ea7cdd8](https://linux-hardware.org/?probe=233ea7cdd8) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | Desktop     | [177fe2fc00](https://linux-hardware.org/?probe=177fe2fc00) | Apr 30, 2023 |
| Acer          | Peppy                       | Notebook    | [4caf11594a](https://linux-hardware.org/?probe=4caf11594a) | Apr 30, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [243a170e5a](https://linux-hardware.org/?probe=243a170e5a) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| HP            | ProLiant ML10 v2            | Desktop     | [3582be2f06](https://linux-hardware.org/?probe=3582be2f06) | Apr 30, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [2cd32d1efe](https://linux-hardware.org/?probe=2cd32d1efe) | Apr 30, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [da5f050510](https://linux-hardware.org/?probe=da5f050510) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [1e65b46a12](https://linux-hardware.org/?probe=1e65b46a12) | Apr 29, 2023 |
| Acer          | Aspire Z5600                | All in one  | [8a9edf5a44](https://linux-hardware.org/?probe=8a9edf5a44) | Apr 29, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [c952010dbb](https://linux-hardware.org/?probe=c952010dbb) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [6a102a2c37](https://linux-hardware.org/?probe=6a102a2c37) | Apr 29, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [04da6f1db9](https://linux-hardware.org/?probe=04da6f1db9) | Apr 29, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [22ad1f6bfb](https://linux-hardware.org/?probe=22ad1f6bfb) | Apr 29, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [91011c02d6](https://linux-hardware.org/?probe=91011c02d6) | Apr 29, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [ff448e32c3](https://linux-hardware.org/?probe=ff448e32c3) | Apr 29, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [c374148e49](https://linux-hardware.org/?probe=c374148e49) | Apr 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [4801547d54](https://linux-hardware.org/?probe=4801547d54) | Apr 29, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [e70ee6019c](https://linux-hardware.org/?probe=e70ee6019c) | Apr 29, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e4718d8b12](https://linux-hardware.org/?probe=e4718d8b12) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [740c70097e](https://linux-hardware.org/?probe=740c70097e) | Apr 29, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [033718212c](https://linux-hardware.org/?probe=033718212c) | Apr 28, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [004e0007e4](https://linux-hardware.org/?probe=004e0007e4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | Notebook    | [3f6a89023c](https://linux-hardware.org/?probe=3f6a89023c) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [216a4b9b67](https://linux-hardware.org/?probe=216a4b9b67) | Apr 28, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [77150d1166](https://linux-hardware.org/?probe=77150d1166) | Apr 28, 2023 |
| Lenovo        | 36DB No DPK                 | All in one  | [01458c55a9](https://linux-hardware.org/?probe=01458c55a9) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [6736f3d911](https://linux-hardware.org/?probe=6736f3d911) | Apr 28, 2023 |
| Lenovo        | 36DB No DPK                 | All in one  | [df53e54c69](https://linux-hardware.org/?probe=df53e54c69) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d97d6d6dff](https://linux-hardware.org/?probe=d97d6d6dff) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a808e47839](https://linux-hardware.org/?probe=a808e47839) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [67ae1efc54](https://linux-hardware.org/?probe=67ae1efc54) | Apr 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [b1e6130b77](https://linux-hardware.org/?probe=b1e6130b77) | Apr 28, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [2ba1bab0fe](https://linux-hardware.org/?probe=2ba1bab0fe) | Apr 28, 2023 |
| MSI           | Katana GF66 12UGS           | Notebook    | [3607ee704e](https://linux-hardware.org/?probe=3607ee704e) | Apr 28, 2023 |
| Lenovo        | NOK                         | Desktop     | [cf3db26781](https://linux-hardware.org/?probe=cf3db26781) | Apr 28, 2023 |
| Unknown       | G41                         | Desktop     | [2a6a185bec](https://linux-hardware.org/?probe=2a6a185bec) | Apr 28, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [3479673283](https://linux-hardware.org/?probe=3479673283) | Apr 28, 2023 |
| Acer          | ConceptD CN315-71P          | Notebook    | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Dell          | Latitude E5470              | Notebook    | [caac023f65](https://linux-hardware.org/?probe=caac023f65) | Apr 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [f65ece2859](https://linux-hardware.org/?probe=f65ece2859) | Apr 27, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [eb9967626a](https://linux-hardware.org/?probe=eb9967626a) | Apr 27, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [404ec697ac](https://linux-hardware.org/?probe=404ec697ac) | Apr 27, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [012329ee1f](https://linux-hardware.org/?probe=012329ee1f) | Apr 27, 2023 |
| MSI           | PE60 6QE                    | Notebook    | [1a5ae975ee](https://linux-hardware.org/?probe=1a5ae975ee) | Apr 27, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [a1391b4372](https://linux-hardware.org/?probe=a1391b4372) | Apr 27, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [de581801e8](https://linux-hardware.org/?probe=de581801e8) | Apr 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [f0a2365878](https://linux-hardware.org/?probe=f0a2365878) | Apr 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [9f3b8c952d](https://linux-hardware.org/?probe=9f3b8c952d) | Apr 27, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [c95605ef8e](https://linux-hardware.org/?probe=c95605ef8e) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [d49ace71b4](https://linux-hardware.org/?probe=d49ace71b4) | Apr 27, 2023 |
| Dell          | Latitude 5520               | Notebook    | [bec614b168](https://linux-hardware.org/?probe=bec614b168) | Apr 26, 2023 |
| HP            | 1905                        | Desktop     | [7b15ec2d7d](https://linux-hardware.org/?probe=7b15ec2d7d) | Apr 26, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [eaac4c0ba0](https://linux-hardware.org/?probe=eaac4c0ba0) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [8f417742d1](https://linux-hardware.org/?probe=8f417742d1) | Apr 26, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [7ca1ebbe7f](https://linux-hardware.org/?probe=7ca1ebbe7f) | Apr 26, 2023 |
| Dell          | Latitude 7420               | Notebook    | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| HP            | 1489                        | All in one  | [ebd3760355](https://linux-hardware.org/?probe=ebd3760355) | Apr 26, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [362ede5435](https://linux-hardware.org/?probe=362ede5435) | Apr 26, 2023 |
| ASUSTek       | H110-PLUS                   | Desktop     | [f8317bce7b](https://linux-hardware.org/?probe=f8317bce7b) | Apr 26, 2023 |
| Acer          | Swift SF313-53              | Notebook    | [b487229ea2](https://linux-hardware.org/?probe=b487229ea2) | Apr 25, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [37b593294a](https://linux-hardware.org/?probe=37b593294a) | Apr 25, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [2fa64e56ff](https://linux-hardware.org/?probe=2fa64e56ff) | Apr 25, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [dc3595e3cc](https://linux-hardware.org/?probe=dc3595e3cc) | Apr 25, 2023 |
| HP            | 240 G8                      | Notebook    | [ab322ed08e](https://linux-hardware.org/?probe=ab322ed08e) | Apr 25, 2023 |
| HP            | 240 G8                      | Notebook    | [8cf9892fe9](https://linux-hardware.org/?probe=8cf9892fe9) | Apr 25, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [e36216c3c7](https://linux-hardware.org/?probe=e36216c3c7) | Apr 25, 2023 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [4c775782ea](https://linux-hardware.org/?probe=4c775782ea) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e7b20d71b7](https://linux-hardware.org/?probe=e7b20d71b7) | Apr 25, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [2732f4b096](https://linux-hardware.org/?probe=2732f4b096) | Apr 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [7d3b6ba1a3](https://linux-hardware.org/?probe=7d3b6ba1a3) | Apr 25, 2023 |
| Dell          | 0K071D A01                  | Desktop     | [0c7edbd8ea](https://linux-hardware.org/?probe=0c7edbd8ea) | Apr 25, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [c5fa59465b](https://linux-hardware.org/?probe=c5fa59465b) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [5fb905227b](https://linux-hardware.org/?probe=5fb905227b) | Apr 25, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [f60927a4d8](https://linux-hardware.org/?probe=f60927a4d8) | Apr 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [65ccee11a0](https://linux-hardware.org/?probe=65ccee11a0) | Apr 24, 2023 |
| ICL           | RAYbook Si1512              | Notebook    | [4e960cbe90](https://linux-hardware.org/?probe=4e960cbe90) | Apr 24, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [26c754e5f0](https://linux-hardware.org/?probe=26c754e5f0) | Apr 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [070d7e791f](https://linux-hardware.org/?probe=070d7e791f) | Apr 24, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [84679bc442](https://linux-hardware.org/?probe=84679bc442) | Apr 24, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [609eeb8038](https://linux-hardware.org/?probe=609eeb8038) | Apr 24, 2023 |
| MSI           | H81M PRO-VD                 | Desktop     | [00ade274cb](https://linux-hardware.org/?probe=00ade274cb) | Apr 24, 2023 |
| Lenovo        | ThinkPad A285 20MXS0NJ00    | Notebook    | [f155ad2bf4](https://linux-hardware.org/?probe=f155ad2bf4) | Apr 24, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [216aaf8fff](https://linux-hardware.org/?probe=216aaf8fff) | Apr 24, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [88c455761b](https://linux-hardware.org/?probe=88c455761b) | Apr 24, 2023 |
| Gateway       | NV55C                       | Notebook    | [3c560a28cf](https://linux-hardware.org/?probe=3c560a28cf) | Apr 24, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [2d0269750e](https://linux-hardware.org/?probe=2d0269750e) | Apr 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2e7585d261](https://linux-hardware.org/?probe=2e7585d261) | Apr 24, 2023 |
| MSI           | B460M PRO-VDH               | Desktop     | [f7709c23a1](https://linux-hardware.org/?probe=f7709c23a1) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [59c225df6e](https://linux-hardware.org/?probe=59c225df6e) | Apr 24, 2023 |
| Lenovo        | 20RD001FHV                  | Notebook    | [782ded0435](https://linux-hardware.org/?probe=782ded0435) | Apr 24, 2023 |
| Samsung       | 950XED                      | Notebook    | [6226147e11](https://linux-hardware.org/?probe=6226147e11) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [b1c3492700](https://linux-hardware.org/?probe=b1c3492700) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [db8e950d12](https://linux-hardware.org/?probe=db8e950d12) | Apr 24, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [35a591e26a](https://linux-hardware.org/?probe=35a591e26a) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [298d51ae78](https://linux-hardware.org/?probe=298d51ae78) | Apr 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [bc1dca3c78](https://linux-hardware.org/?probe=bc1dca3c78) | Apr 24, 2023 |
| HP            | ZBook 17 G5                 | Notebook    | [c1d71592a4](https://linux-hardware.org/?probe=c1d71592a4) | Apr 24, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [6ed93f8338](https://linux-hardware.org/?probe=6ed93f8338) | Apr 24, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [c47ec3530e](https://linux-hardware.org/?probe=c47ec3530e) | Apr 24, 2023 |
| Dell          | G5 5590                     | Notebook    | [eef3722c35](https://linux-hardware.org/?probe=eef3722c35) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [0dfc7cce7a](https://linux-hardware.org/?probe=0dfc7cce7a) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [b80d03be6d](https://linux-hardware.org/?probe=b80d03be6d) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [09d116d762](https://linux-hardware.org/?probe=09d116d762) | Apr 23, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [df70910ec6](https://linux-hardware.org/?probe=df70910ec6) | Apr 23, 2023 |
| HP            | ZBook 17 G5                 | Notebook    | [ce9fd79431](https://linux-hardware.org/?probe=ce9fd79431) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [4e664e5e26](https://linux-hardware.org/?probe=4e664e5e26) | Apr 23, 2023 |
| Dell          | Precision M4400             | Notebook    | [0c367cbf45](https://linux-hardware.org/?probe=0c367cbf45) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4286A44       | Notebook    | [6b6e909d11](https://linux-hardware.org/?probe=6b6e909d11) | Apr 23, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [641374c815](https://linux-hardware.org/?probe=641374c815) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [aa01246f8b](https://linux-hardware.org/?probe=aa01246f8b) | Apr 23, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c9691c3866](https://linux-hardware.org/?probe=c9691c3866) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [658450824e](https://linux-hardware.org/?probe=658450824e) | Apr 23, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [90b7213592](https://linux-hardware.org/?probe=90b7213592) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [620334c0fc](https://linux-hardware.org/?probe=620334c0fc) | Apr 23, 2023 |
| Lenovo        | IdeaPadFlex 5 16IAU7 82R... | Convertible | [66cfd6f9a3](https://linux-hardware.org/?probe=66cfd6f9a3) | Apr 23, 2023 |
| ASRock        | A75M-HVS                    | Desktop     | [a4964506f7](https://linux-hardware.org/?probe=a4964506f7) | Apr 23, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [67f15c6f4a](https://linux-hardware.org/?probe=67f15c6f4a) | Apr 22, 2023 |
| Dell          | Latitude E6420              | Notebook    | [475a16531a](https://linux-hardware.org/?probe=475a16531a) | Apr 22, 2023 |
| Dell          | Precision M4400             | Notebook    | [291a0de9a8](https://linux-hardware.org/?probe=291a0de9a8) | Apr 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [60251e08f5](https://linux-hardware.org/?probe=60251e08f5) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [180784b3a2](https://linux-hardware.org/?probe=180784b3a2) | Apr 22, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [8209f53171](https://linux-hardware.org/?probe=8209f53171) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ce5e9aad85](https://linux-hardware.org/?probe=ce5e9aad85) | Apr 22, 2023 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [2afc5398b8](https://linux-hardware.org/?probe=2afc5398b8) | Apr 22, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [afdab44276](https://linux-hardware.org/?probe=afdab44276) | Apr 22, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [1f6e58080a](https://linux-hardware.org/?probe=1f6e58080a) | Apr 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [0f5a55a8d1](https://linux-hardware.org/?probe=0f5a55a8d1) | Apr 22, 2023 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [f916f697ed](https://linux-hardware.org/?probe=f916f697ed) | Apr 22, 2023 |
| Biostar       | H410MH S2                   | Desktop     | [0f2593dc78](https://linux-hardware.org/?probe=0f2593dc78) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [a60c54ec31](https://linux-hardware.org/?probe=a60c54ec31) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [63cafebe06](https://linux-hardware.org/?probe=63cafebe06) | Apr 21, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [7c0a7d4494](https://linux-hardware.org/?probe=7c0a7d4494) | Apr 21, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [2a5d9adcd4](https://linux-hardware.org/?probe=2a5d9adcd4) | Apr 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [85fa6bf3d5](https://linux-hardware.org/?probe=85fa6bf3d5) | Apr 21, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [f89cce4966](https://linux-hardware.org/?probe=f89cce4966) | Apr 21, 2023 |
| Dell          | Latitude E6420              | Notebook    | [5e3466ce98](https://linux-hardware.org/?probe=5e3466ce98) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d34d10b1ad](https://linux-hardware.org/?probe=d34d10b1ad) | Apr 20, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [293cc42c9d](https://linux-hardware.org/?probe=293cc42c9d) | Apr 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [05321d1ddd](https://linux-hardware.org/?probe=05321d1ddd) | Apr 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [42ef555f6c](https://linux-hardware.org/?probe=42ef555f6c) | Apr 20, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e09f00bead](https://linux-hardware.org/?probe=e09f00bead) | Apr 20, 2023 |
| HP            | Pavilion g4                 | Notebook    | [96a0210940](https://linux-hardware.org/?probe=96a0210940) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [170b38e40f](https://linux-hardware.org/?probe=170b38e40f) | Apr 20, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [9f81660d12](https://linux-hardware.org/?probe=9f81660d12) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b54a612e76](https://linux-hardware.org/?probe=b54a612e76) | Apr 20, 2023 |
| Crusaders ... | CS14D01                     | Notebook    | [b25acea9f7](https://linux-hardware.org/?probe=b25acea9f7) | Apr 19, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [c34c1abf02](https://linux-hardware.org/?probe=c34c1abf02) | Apr 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [88b9080a8c](https://linux-hardware.org/?probe=88b9080a8c) | Apr 17, 2023 |
| Dell          | Vostro 15 7510              | Notebook    | [d9e766f446](https://linux-hardware.org/?probe=d9e766f446) | Apr 16, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [04eead074d](https://linux-hardware.org/?probe=04eead074d) | Apr 14, 2023 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [d0742654bb](https://linux-hardware.org/?probe=d0742654bb) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [df35f6916a](https://linux-hardware.org/?probe=df35f6916a) | Apr 14, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [0c4578a674](https://linux-hardware.org/?probe=0c4578a674) | Apr 14, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [6b481f17c2](https://linux-hardware.org/?probe=6b481f17c2) | Apr 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [bcb170c5f0](https://linux-hardware.org/?probe=bcb170c5f0) | Apr 13, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c56952417d](https://linux-hardware.org/?probe=c56952417d) | Apr 11, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [be9d1636a7](https://linux-hardware.org/?probe=be9d1636a7) | Apr 09, 2023 |
| Acer          | Swift SF314-55G             | Notebook    | [e15eaec4c0](https://linux-hardware.org/?probe=e15eaec4c0) | Apr 07, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | Notebook    | [29f00590fb](https://linux-hardware.org/?probe=29f00590fb) | Apr 05, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [a1dceb9ce7](https://linux-hardware.org/?probe=a1dceb9ce7) | Apr 04, 2023 |
| Google        | Akemi                       | Notebook    | [14e5c7b93b](https://linux-hardware.org/?probe=14e5c7b93b) | Apr 04, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [dd3c0ff2e5](https://linux-hardware.org/?probe=dd3c0ff2e5) | Apr 03, 2023 |
| Samsung       | 767XCL                      | Notebook    | [b5a44d9194](https://linux-hardware.org/?probe=b5a44d9194) | Apr 03, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [2e820040bc](https://linux-hardware.org/?probe=2e820040bc) | Apr 02, 2023 |
| Dell          | Inspiron 5458               | Notebook    | [38b9db2538](https://linux-hardware.org/?probe=38b9db2538) | Apr 01, 2023 |
| Samsung       | 767XCL                      | Notebook    | [a3167908c0](https://linux-hardware.org/?probe=a3167908c0) | Apr 01, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [7a23362aac](https://linux-hardware.org/?probe=7a23362aac) | Mar 31, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | Notebook    | [13e8d4f50b](https://linux-hardware.org/?probe=13e8d4f50b) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b56e2a41ed](https://linux-hardware.org/?probe=b56e2a41ed) | Mar 31, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [426c2d06fd](https://linux-hardware.org/?probe=426c2d06fd) | Mar 30, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [8e1c758a05](https://linux-hardware.org/?probe=8e1c758a05) | Mar 26, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [aafbb2815f](https://linux-hardware.org/?probe=aafbb2815f) | Mar 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4f2d3a2402](https://linux-hardware.org/?probe=4f2d3a2402) | Mar 25, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [7f98044a04](https://linux-hardware.org/?probe=7f98044a04) | Mar 24, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [8c5fde8c1e](https://linux-hardware.org/?probe=8c5fde8c1e) | Mar 22, 2023 |
| Dell          | Latitude 7520               | Notebook    | [09c8e699d3](https://linux-hardware.org/?probe=09c8e699d3) | Mar 16, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [66094e937a](https://linux-hardware.org/?probe=66094e937a) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [49130084c4](https://linux-hardware.org/?probe=49130084c4) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [a6091bc2e2](https://linux-hardware.org/?probe=a6091bc2e2) | Mar 11, 2023 |
| HP            | 18E5                        | Desktop     | [82e5831486](https://linux-hardware.org/?probe=82e5831486) | Mar 10, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | Notebook    | [89e2fd827d](https://linux-hardware.org/?probe=89e2fd827d) | Mar 05, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [bb68a61939](https://linux-hardware.org/?probe=bb68a61939) | Mar 05, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [824ece168f](https://linux-hardware.org/?probe=824ece168f) | Mar 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [525be1bcbe](https://linux-hardware.org/?probe=525be1bcbe) | Mar 02, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | Notebook    | [830a8a94e2](https://linux-hardware.org/?probe=830a8a94e2) | Mar 02, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | Notebook    | [0bf8c9ca74](https://linux-hardware.org/?probe=0bf8c9ca74) | Mar 02, 2023 |
| AZW           | GTR V01                     | Mini pc     | [bfe7635484](https://linux-hardware.org/?probe=bfe7635484) | Mar 01, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [05ad6c694b](https://linux-hardware.org/?probe=05ad6c694b) | Mar 01, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [5beb40c486](https://linux-hardware.org/?probe=5beb40c486) | Feb 28, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [6677ab11b2](https://linux-hardware.org/?probe=6677ab11b2) | Feb 28, 2023 |
| Samsung       | 370E4K                      | Notebook    | [aba5535c2a](https://linux-hardware.org/?probe=aba5535c2a) | Feb 28, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [c361aabb21](https://linux-hardware.org/?probe=c361aabb21) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [17338cbd01](https://linux-hardware.org/?probe=17338cbd01) | Feb 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [580db05e08](https://linux-hardware.org/?probe=580db05e08) | Feb 27, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [a206715ec6](https://linux-hardware.org/?probe=a206715ec6) | Feb 26, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d227d114f4](https://linux-hardware.org/?probe=d227d114f4) | Feb 25, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [33dc8202e9](https://linux-hardware.org/?probe=33dc8202e9) | Feb 25, 2023 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [bb5da28703](https://linux-hardware.org/?probe=bb5da28703) | Feb 23, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [643d79fd46](https://linux-hardware.org/?probe=643d79fd46) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [ba0144c710](https://linux-hardware.org/?probe=ba0144c710) | Feb 20, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [628feb8b19](https://linux-hardware.org/?probe=628feb8b19) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [2f591ee9e3](https://linux-hardware.org/?probe=2f591ee9e3) | Feb 13, 2023 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [9e28099913](https://linux-hardware.org/?probe=9e28099913) | Feb 11, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Unknown       | Unknown                     | Soc         | [2ba7af4017](https://linux-hardware.org/?probe=2ba7af4017) | Feb 09, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [99dda6c06c](https://linux-hardware.org/?probe=99dda6c06c) | Feb 09, 2023 |
| Acer          | Aspire V5-552G              | Notebook    | [2750863407](https://linux-hardware.org/?probe=2750863407) | Feb 02, 2023 |
| Lenovo        | 3309 SDK0T76530 WIN 3556... | Mini pc     | [dc858e1b6d](https://linux-hardware.org/?probe=dc858e1b6d) | Jan 23, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a9eba68b79](https://linux-hardware.org/?probe=a9eba68b79) | Jan 14, 2023 |
| Samsung       | SBB-DA                      | Notebook    | [a4c6b4f454](https://linux-hardware.org/?probe=a4c6b4f454) | Jan 07, 2023 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [9e8c937daa](https://linux-hardware.org/?probe=9e8c937daa) | Dec 31, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [019236854d](https://linux-hardware.org/?probe=019236854d) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [d6f064e643](https://linux-hardware.org/?probe=d6f064e643) | Dec 30, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [28822be06e](https://linux-hardware.org/?probe=28822be06e) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [e1ae2ba145](https://linux-hardware.org/?probe=e1ae2ba145) | Dec 24, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [ba498df129](https://linux-hardware.org/?probe=ba498df129) | Dec 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d1342c521a](https://linux-hardware.org/?probe=d1342c521a) | Dec 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5c0099832f](https://linux-hardware.org/?probe=5c0099832f) | Dec 15, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [82edcc6c08](https://linux-hardware.org/?probe=82edcc6c08) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6f8c8644e2](https://linux-hardware.org/?probe=6f8c8644e2) | Dec 10, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [33f7ac03f4](https://linux-hardware.org/?probe=33f7ac03f4) | Nov 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e87a096d85](https://linux-hardware.org/?probe=e87a096d85) | Nov 27, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [9e465f741d](https://linux-hardware.org/?probe=9e465f741d) | Nov 26, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [1817579f89](https://linux-hardware.org/?probe=1817579f89) | Nov 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_23.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.2.0-20-generic        | 489       | 69.66%  |
| 6.2.0-23-generic        | 76        | 10.83%  |
| 5.19.0-21-generic       | 20        | 2.85%   |
| 6.2.0-24-generic        | 15        | 2.14%   |
| 6.2.0-18-generic        | 13        | 1.85%   |
| 5.19.0-41-generic       | 7         | 1%      |
| 6.3.2-060302-generic    | 6         | 0.85%   |
| 6.1.0-16-generic        | 6         | 0.85%   |
| 6.2.0-1004-raspi        | 4         | 0.57%   |
| 6.4.0-060400-generic    | 3         | 0.43%   |
| 6.3.4-060304-generic    | 3         | 0.43%   |
| 6.2.9-060209-generic    | 3         | 0.43%   |
| 6.2.0-19-generic        | 3         | 0.43%   |
| 6.2.0-1003-lowlatency   | 3         | 0.43%   |
| 5.19.0-31-generic       | 3         | 0.43%   |
| 5.19.0-28-generic       | 3         | 0.43%   |
| 6.3.6-060306-generic    | 2         | 0.28%   |
| 6.3.5-060305-generic    | 2         | 0.28%   |
| 5.19.0-42-generic       | 2         | 0.28%   |
| 5.19.0-40-generic       | 2         | 0.28%   |
| 5.19.0-38-generic       | 2         | 0.28%   |
| 6.4.0-rc6+              | 1         | 0.14%   |
| 6.3.8-x64v4-xanmod1     | 1         | 0.14%   |
| 6.3.3-surface           | 1         | 0.14%   |
| 6.3.1-x64v3-xanmod1     | 1         | 0.14%   |
| 6.3.1-060301-generic    | 1         | 0.14%   |
| 6.3.0-rc7               | 1         | 0.14%   |
| 6.3.0-060300rc7-generic | 1         | 0.14%   |
| 6.3.0-060300rc2-generic | 1         | 0.14%   |
| 6.3.0-060300-generic    | 1         | 0.14%   |
| 6.3.0+                  | 1         | 0.14%   |
| 6.2.6-060206-generic    | 1         | 0.14%   |
| 6.2.12-060212-generic   | 1         | 0.14%   |
| 6.2.11-060211-generic   | 1         | 0.14%   |
| 6.2.10-060210-generic   | 1         | 0.14%   |
| 6.2.0-1007-gcp          | 1         | 0.14%   |
| 6.2.0-1005-lowlatency   | 1         | 0.14%   |
| 6.2.0-1003-raspi        | 1         | 0.14%   |
| 6.2.0-060200rc7-generic | 1         | 0.14%   |
| 6.1.12-060112-generic   | 1         | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 599       | 86.31%  |
| 5.19.0  | 47        | 6.77%   |
| 6.1.0   | 7         | 1.01%   |
| 6.3.2   | 6         | 0.86%   |
| 6.3.0   | 5         | 0.72%   |
| 6.4.0   | 4         | 0.58%   |
| 6.3.4   | 3         | 0.43%   |
| 6.2.9   | 3         | 0.43%   |
| 6.3.6   | 2         | 0.29%   |
| 6.3.5   | 2         | 0.29%   |
| 6.3.1   | 2         | 0.29%   |
| 5.14.0  | 2         | 0.29%   |
| 6.3.8   | 1         | 0.14%   |
| 6.3.3   | 1         | 0.14%   |
| 6.2.6   | 1         | 0.14%   |
| 6.2.12  | 1         | 0.14%   |
| 6.2.11  | 1         | 0.14%   |
| 6.2.10  | 1         | 0.14%   |
| 6.1.12  | 1         | 0.14%   |
| 6.0.9   | 1         | 0.14%   |
| 5.19.5  | 1         | 0.14%   |
| 5.19.17 | 1         | 0.14%   |
| 5.15.0  | 1         | 0.14%   |
| 5.11.0  | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 606       | 87.32%  |
| 5.19    | 49        | 7.06%   |
| 6.3     | 22        | 3.17%   |
| 6.1     | 8         | 1.15%   |
| 6.4     | 4         | 0.58%   |
| 5.14    | 2         | 0.29%   |
| 6.0     | 1         | 0.14%   |
| 5.15    | 1         | 0.14%   |
| 5.11    | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 685       | 99.13%  |
| aarch64 | 4         | 0.58%   |
| riscv64 | 1         | 0.14%   |
| armv7l  | 1         | 0.14%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 667       | 96.39%  |
| X-Cinnamon      | 12        | 1.73%   |
| Unknown         | 10        | 1.45%   |
| GNOME Flashback | 2         | 0.29%   |
| mwm             | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 443       | 63.2%   |
| X11     | 247       | 35.24%  |
| Unknown | 6         | 0.86%   |
| Tty     | 5         | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM3    | 608       | 87.86%  |
| Unknown | 70        | 10.12%  |
| LightDM | 13        | 1.88%   |
| GDM     | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 334       | 47.99%  |
| de_DE   | 72        | 10.34%  |
| fr_FR   | 36        | 5.17%   |
| C       | 32        | 4.6%    |
| es_ES   | 27        | 3.88%   |
| pt_BR   | 23        | 3.3%    |
| en_GB   | 22        | 3.16%   |
| ru_RU   | 16        | 2.3%    |
| it_IT   | 15        | 2.16%   |
| en_AU   | 13        | 1.87%   |
| en_CA   | 11        | 1.58%   |
| pl_PL   | 9         | 1.29%   |
| cs_CZ   | 6         | 0.86%   |
| nl_NL   | 5         | 0.72%   |
| es_MX   | 5         | 0.72%   |
| zh_CN   | 4         | 0.57%   |
| fi_FI   | 4         | 0.57%   |
| de_AT   | 4         | 0.57%   |
| Unknown | 4         | 0.57%   |
| sv_SE   | 3         | 0.43%   |
| ro_RO   | 3         | 0.43%   |
| hu_HU   | 3         | 0.43%   |
| en_ZA   | 3         | 0.43%   |
| en_IN   | 3         | 0.43%   |
| en_IL   | 3         | 0.43%   |
| el_GR   | 3         | 0.43%   |
| de_CH   | 3         | 0.43%   |
| zh_TW   | 2         | 0.29%   |
| tr_TR   | 2         | 0.29%   |
| pt_PT   | 2         | 0.29%   |
| en_SG   | 2         | 0.29%   |
| en_NZ   | 2         | 0.29%   |
| ca_ES   | 2         | 0.29%   |
| bg_BG   | 2         | 0.29%   |
| nb_NO   | 1         | 0.14%   |
| lt_LT   | 1         | 0.14%   |
| ko_KR   | 1         | 0.14%   |
| ja_JP   | 1         | 0.14%   |
| hr_HR   | 1         | 0.14%   |
| fr_CH   | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 431       | 62.01%  |
| EFI  | 264       | 37.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Tmpfs   | 355       | 51.15%  |
| Ext4    | 316       | 45.53%  |
| Overlay | 12        | 1.73%   |
| Btrfs   | 6         | 0.86%   |
| Zfs     | 4         | 0.58%   |
| Xfs     | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 589       | 84.99%  |
| Unknown | 59        | 8.51%   |
| MBR     | 45        | 6.49%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 607       | 87.72%  |
| Yes       | 85        | 12.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 441       | 63.27%  |
| Yes       | 256       | 36.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 109       | 15.77%  |
| Lenovo                               | 108       | 15.63%  |
| Dell                                 | 91        | 13.17%  |
| Hewlett-Packard                      | 90        | 13.02%  |
| Acer                                 | 42        | 6.08%   |
| MSI                                  | 41        | 5.93%   |
| Gigabyte Technology                  | 30        | 4.34%   |
| Apple                                | 23        | 3.33%   |
| HUAWEI                               | 17        | 2.46%   |
| Intel                                | 14        | 2.03%   |
| ASRock                               | 14        | 2.03%   |
| Unknown                              | 10        | 1.45%   |
| Toshiba                              | 9         | 1.3%    |
| Samsung Electronics                  | 8         | 1.16%   |
| Timi                                 | 5         | 0.72%   |
| Raspberry Pi Foundation              | 5         | 0.72%   |
| Sony                                 | 4         | 0.58%   |
| Microsoft                            | 4         | 0.58%   |
| Google                               | 4         | 0.58%   |
| AZW                                  | 4         | 0.58%   |
| Shanghai Zhaoxin Semiconductor       | 3         | 0.43%   |
| Razer                                | 3         | 0.43%   |
| Notebook                             | 3         | 0.43%   |
| Medion                               | 3         | 0.43%   |
| Gateway                              | 3         | 0.43%   |
| Fujitsu                              | 3         | 0.43%   |
| Packard Bell                         | 2         | 0.29%   |
| HONOR                                | 2         | 0.29%   |
| Hampoo                               | 2         | 0.29%   |
| Alienware                            | 2         | 0.29%   |
| ZOTAC                                | 1         | 0.14%   |
| VALE                                 | 1         | 0.14%   |
| System76                             | 1         | 0.14%   |
| Supermicro                           | 1         | 0.14%   |
| Star Labs                            | 1         | 0.14%   |
| Shuttle                              | 1         | 0.14%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.14%   |
| Semp Toshiba                         | 1         | 0.14%   |
| Rombica                              | 1         | 0.14%   |
| Positivo                             | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 11        | 1.59%   |
| ASUS All Series              | 4         | 0.58%   |
| Shanghai Zhaoxin ZXE CRB     | 3         | 0.43%   |
| HUAWEI BOM-WXX9              | 3         | 0.43%   |
| HP Notebook                  | 3         | 0.43%   |
| Dell Latitude 7480           | 3         | 0.43%   |
| Apple MacBookPro9,2          | 3         | 0.43%   |
| Acer Swift SF314-512         | 3         | 0.43%   |
| Toshiba Satellite Pro C70-B  | 2         | 0.29%   |
| Timi Redmi Book Pro 14 2022  | 2         | 0.29%   |
| RPi Raspberry Pi             | 2         | 0.29%   |
| MSI Stealth 15M B12UE        | 2         | 0.29%   |
| MSI MS-7C95                  | 2         | 0.29%   |
| MSI MS-7721                  | 2         | 0.29%   |
| MSI Modern 14 A10M           | 2         | 0.29%   |
| Microsoft Surface Laptop Go  | 2         | 0.29%   |
| Intel NUC10i7FNH             | 2         | 0.29%   |
| Intel H61                    | 2         | 0.29%   |
| HUAWEI KLVD-WXX9             | 2         | 0.29%   |
| HUAWEI CREM-WXX9             | 2         | 0.29%   |
| HUAWEI BOHB-WAX9             | 2         | 0.29%   |
| HONOR BBR-WAX9               | 2         | 0.29%   |
| HP Pavilion x360 Convertible | 2         | 0.29%   |
| HP Pavilion Notebook         | 2         | 0.29%   |
| HP Pavilion dv6              | 2         | 0.29%   |
| HP Meep                      | 2         | 0.29%   |
| HP Laptop 15s-eq2xxx         | 2         | 0.29%   |
| HP Laptop 14-dq2xxx          | 2         | 0.29%   |
| HP EliteDesk 800 G2 DM 35W   | 2         | 0.29%   |
| HP EliteBook 840 G6          | 2         | 0.29%   |
| Hampoo I1D6_C109S_Hi10Pro    | 2         | 0.29%   |
| Dell XPS 15 9570             | 2         | 0.29%   |
| Dell XPS 15 9500             | 2         | 0.29%   |
| Dell Precision Tower 7810    | 2         | 0.29%   |
| Dell Precision 5570          | 2         | 0.29%   |
| Dell Latitude E5470          | 2         | 0.29%   |
| Dell Latitude 5440           | 2         | 0.29%   |
| Dell Inspiron 3442           | 2         | 0.29%   |
| Dell G5 5590                 | 2         | 0.29%   |
| AZW SER                      | 2         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 48        | 6.95%   |
| Dell Latitude        | 25        | 3.62%   |
| Dell Inspiron        | 23        | 3.33%   |
| Acer Aspire          | 22        | 3.18%   |
| ASUS PRIME           | 21        | 3.04%   |
| Lenovo IdeaPad       | 17        | 2.46%   |
| HP Pavilion          | 15        | 2.17%   |
| Dell XPS             | 15        | 2.17%   |
| ASUS VivoBook        | 15        | 2.17%   |
| HP EliteBook         | 13        | 1.88%   |
| ASUS TUF             | 12        | 1.74%   |
| HP Laptop            | 11        | 1.59%   |
| Unknown              | 11        | 1.59%   |
| Lenovo Yoga          | 10        | 1.45%   |
| Dell Precision       | 9         | 1.3%    |
| Dell OptiPlex        | 9         | 1.3%    |
| Acer Swift           | 9         | 1.3%    |
| Lenovo ThinkCentre   | 7         | 1.01%   |
| HP ProBook           | 7         | 1.01%   |
| ASUS ROG             | 7         | 1.01%   |
| Toshiba Satellite    | 6         | 0.87%   |
| HP ENVY              | 6         | 0.87%   |
| Dell Vostro          | 6         | 0.87%   |
| ASUS Zenbook         | 6         | 0.87%   |
| Acer Nitro           | 6         | 0.87%   |
| RPi Raspberry        | 5         | 0.72%   |
| Lenovo IdeaPadFlex   | 5         | 0.72%   |
| HP Compaq            | 5         | 0.72%   |
| ASUS ASUS            | 5         | 0.72%   |
| MSI Stealth          | 4         | 0.58%   |
| Microsoft Surface    | 4         | 0.58%   |
| Lenovo Legion        | 4         | 0.58%   |
| Lenovo IdeaCentre    | 4         | 0.58%   |
| HP EliteDesk         | 4         | 0.58%   |
| ASUS All             | 4         | 0.58%   |
| Shanghai Zhaoxin ZXE | 3         | 0.43%   |
| Razer Blade          | 3         | 0.43%   |
| HUAWEI BOM-WXX9      | 3         | 0.43%   |
| HP ZBook             | 3         | 0.43%   |
| HP Notebook          | 3         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 102       | 14.76%  |
| 2022    | 98        | 14.18%  |
| 2020    | 68        | 9.84%   |
| 2019    | 50        | 7.24%   |
| 2016    | 42        | 6.08%   |
| 2018    | 41        | 5.93%   |
| 2015    | 38        | 5.5%    |
| 2011    | 36        | 5.21%   |
| 2014    | 33        | 4.78%   |
| 2012    | 33        | 4.78%   |
| 2017    | 32        | 4.63%   |
| 2010    | 30        | 4.34%   |
| 2023    | 25        | 3.62%   |
| 2013    | 25        | 3.62%   |
| 2008    | 14        | 2.03%   |
| 2009    | 12        | 1.74%   |
| Unknown | 7         | 1.01%   |
| 2007    | 3         | 0.43%   |
| 2006    | 2         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 387       | 56.01%  |
| Desktop        | 213       | 30.82%  |
| Convertible    | 44        | 6.37%   |
| Mini pc        | 16        | 2.32%   |
| All in one     | 11        | 1.59%   |
| Tablet         | 10        | 1.45%   |
| System on chip | 6         | 0.87%   |
| Server         | 4         | 0.58%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 629       | 90.9%   |
| Enabled  | 63        | 9.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 685       | 99.13%  |
| Yes  | 6         | 0.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 178       | 25.72%  |
| 16.01-24.0      | 147       | 21.24%  |
| 8.01-16.0       | 112       | 16.18%  |
| 3.01-4.0        | 92        | 13.29%  |
| 32.01-64.0      | 85        | 12.28%  |
| 64.01-256.0     | 38        | 5.49%   |
| 24.01-32.0      | 29        | 4.19%   |
| 1.01-2.0        | 7         | 1.01%   |
| More than 256.0 | 2         | 0.29%   |
| 2.01-3.0        | 1         | 0.14%   |
| 0.51-1.0        | 1         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 218       | 30.92%  |
| 1.01-2.0   | 168       | 23.83%  |
| 4.01-8.0   | 162       | 22.98%  |
| 3.01-4.0   | 116       | 16.45%  |
| 8.01-16.0  | 33        | 4.68%   |
| 16.01-24.0 | 4         | 0.57%   |
| 24.01-32.0 | 2         | 0.28%   |
| 0.51-1.0   | 1         | 0.14%   |
| 0.01-0.5   | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 449       | 64.79%  |
| 2      | 153       | 22.08%  |
| 3      | 44        | 6.35%   |
| 4      | 23        | 3.32%   |
| 5      | 12        | 1.73%   |
| 6      | 8         | 1.15%   |
| 0      | 2         | 0.29%   |
| 8      | 1         | 0.14%   |
| 7      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 517       | 74.82%  |
| Yes       | 174       | 25.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 515       | 74.42%  |
| No        | 177       | 25.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 589       | 85.24%  |
| No        | 102       | 14.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 501       | 72.29%  |
| No        | 192       | 27.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 119       | 17.2%   |
| Germany      | 79        | 11.42%  |
| France       | 40        | 5.78%   |
| Brazil       | 36        | 5.2%    |
| Russia       | 29        | 4.19%   |
| Canada       | 28        | 4.05%   |
| Italy        | 26        | 3.76%   |
| UK           | 24        | 3.47%   |
| Spain        | 21        | 3.03%   |
| Australia    | 20        | 2.89%   |
| Netherlands  | 14        | 2.02%   |
| India        | 13        | 1.88%   |
| Switzerland  | 12        | 1.73%   |
| Sweden       | 12        | 1.73%   |
| Poland       | 11        | 1.59%   |
| Romania      | 10        | 1.45%   |
| Mexico       | 10        | 1.45%   |
| Czechia      | 10        | 1.45%   |
| China        | 10        | 1.45%   |
| Portugal     | 9         | 1.3%    |
| Austria      | 9         | 1.3%    |
| Turkey       | 8         | 1.16%   |
| Norway       | 7         | 1.01%   |
| Finland      | 7         | 1.01%   |
| Serbia       | 6         | 0.87%   |
| Israel       | 6         | 0.87%   |
| Greece       | 6         | 0.87%   |
| Belgium      | 6         | 0.87%   |
| South Africa | 5         | 0.72%   |
| Ireland      | 5         | 0.72%   |
| Iran         | 5         | 0.72%   |
| Chile        | 5         | 0.72%   |
| Philippines  | 4         | 0.58%   |
| Indonesia    | 4         | 0.58%   |
| Hong Kong    | 4         | 0.58%   |
| Argentina    | 4         | 0.58%   |
| Vietnam      | 3         | 0.43%   |
| Taiwan       | 3         | 0.43%   |
| New Zealand  | 3         | 0.43%   |
| Kenya        | 3         | 0.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 11        | 1.57%   |
| Moscow            | 8         | 1.14%   |
| Melbourne         | 7         | 1%      |
| Montreal          | 6         | 0.86%   |
| Berlin            | 6         | 0.86%   |
| St Petersburg     | 5         | 0.72%   |
| Frankfurt am Main | 5         | 0.72%   |
| Belgrade          | 5         | 0.72%   |
| Barcelona         | 5         | 0.72%   |
| Tehran            | 4         | 0.57%   |
| Prague            | 4         | 0.57%   |
| Oslo              | 4         | 0.57%   |
| Helsinki          | 4         | 0.57%   |
| Denver            | 4         | 0.57%   |
| Brussels          | 4         | 0.57%   |
| Zurich            | 3         | 0.43%   |
| Warsaw            | 3         | 0.43%   |
| Valencia          | 3         | 0.43%   |
| Toronto           | 3         | 0.43%   |
| Sydney            | 3         | 0.43%   |
| Santiago          | 3         | 0.43%   |
| San Francisco     | 3         | 0.43%   |
| Rio de Janeiro    | 3         | 0.43%   |
| Paris             | 3         | 0.43%   |
| Nairobi           | 3         | 0.43%   |
| Mumbai            | 3         | 0.43%   |
| Madrid            | 3         | 0.43%   |
| Kunming           | 3         | 0.43%   |
| Hamburg           | 3         | 0.43%   |
| Düsseldorf       | 3         | 0.43%   |
| Central           | 3         | 0.43%   |
| Calgary           | 3         | 0.43%   |
| Brisbane          | 3         | 0.43%   |
| Amsterdam         | 3         | 0.43%   |
| Wil               | 2         | 0.29%   |
| Vienna            | 2         | 0.29%   |
| Turin             | 2         | 0.29%   |
| Tel Aviv          | 2         | 0.29%   |
| Surrey            | 2         | 0.29%   |
| Stockholm         | 2         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 184       | 225    | 18.7%   |
| Seagate                     | 110       | 138    | 11.18%  |
| WDC                         | 109       | 141    | 11.08%  |
| SanDisk                     | 61        | 70     | 6.2%    |
| Kingston                    | 54        | 62     | 5.49%   |
| SK hynix                    | 46        | 48     | 4.67%   |
| Toshiba                     | 40        | 44     | 4.07%   |
| Unknown                     | 37        | 41     | 3.76%   |
| Micron Technology           | 32        | 37     | 3.25%   |
| Crucial                     | 28        | 30     | 2.85%   |
| KIOXIA                      | 26        | 27     | 2.64%   |
| Intel                       | 26        | 32     | 2.64%   |
| Hitachi                     | 20        | 23     | 2.03%   |
| Phison Electronics          | 16        | 18     | 1.63%   |
| China                       | 13        | 13     | 1.32%   |
| Apple                       | 12        | 14     | 1.22%   |
| Kingston Technology Company | 11        | 13     | 1.12%   |
| Phison                      | 9         | 10     | 0.91%   |
| HGST                        | 9         | 10     | 0.91%   |
| Micron/Crucial Technology   | 7         | 8      | 0.71%   |
| A-DATA Technology           | 6         | 7      | 0.61%   |
| Silicon Motion              | 5         | 5      | 0.51%   |
| LITEONIT                    | 5         | 6      | 0.51%   |
| UMIS                        | 4         | 4      | 0.41%   |
| Realtek Semiconductor       | 4         | 5      | 0.41%   |
| PNY                         | 4         | 5      | 0.41%   |
| LITEON                      | 4         | 6      | 0.41%   |
| Gigabyte Technology         | 4         | 4      | 0.41%   |
| Team                        | 3         | 3      | 0.3%    |
| SPCC                        | 3         | 3      | 0.3%    |
| SABRENT                     | 3         | 6      | 0.3%    |
| Patriot                     | 3         | 3      | 0.3%    |
| OCZ                         | 3         | 3      | 0.3%    |
| Netac                       | 3         | 3      | 0.3%    |
| Intenso                     | 3         | 5      | 0.3%    |
| FORESEE                     | 3         | 3      | 0.3%    |
| Unknown                     | 3         | 3      | 0.3%    |
| Union Memory                | 2         | 2      | 0.2%    |
| Transcend                   | 2         | 2      | 0.2%    |
| SSSTC                       | 2         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 26        | 2.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 13        | 1.23%   |
| Kingston SA400S37240G 240GB SSD                       | 11        | 1.04%   |
| Samsung SSD 850 EVO 250GB                             | 10        | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 10        | 0.95%   |
| Kingston SA400S37480G 480GB SSD                       | 10        | 0.95%   |
| Unknown MMC Card  64GB                                | 9         | 0.85%   |
| Seagate ST1000DM010-2EP102 1TB                        | 7         | 0.66%   |
| Samsung SSD 980 1TB                                   | 7         | 0.66%   |
| Phison E12 NVMe Controller 1TB                        | 7         | 0.66%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 7         | 0.66%   |
| Unknown SD/MMC/MS PRO 250GB                           | 6         | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB                        | 6         | 0.57%   |
| Seagate ST1000LM035-1RK172 1TB                        | 6         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 6         | 0.57%   |
| SanDisk NVMe SSD Drive 512GB                          | 6         | 0.57%   |
| Samsung SSD 870 EVO 500GB                             | 6         | 0.57%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                         | 6         | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 5         | 0.47%   |
| WDC WD20EZRX-00D8PB0 2TB                              | 5         | 0.47%   |
| Unknown MMC Card  32GB                                | 5         | 0.47%   |
| Toshiba MQ01ABF050 500GB                              | 5         | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB                        | 5         | 0.47%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 5         | 0.47%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 5         | 0.47%   |
| Samsung SSD 990 PRO 1TB                               | 5         | 0.47%   |
| Samsung SSD 860 EVO 500GB                             | 5         | 0.47%   |
| Samsung SSD 860 EVO 250GB                             | 5         | 0.47%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 5         | 0.47%   |
| Toshiba XG6 NVMe SSD Controller 2TB                   | 4         | 0.38%   |
| Toshiba DT01ACA100 1TB                                | 4         | 0.38%   |
| SK hynix HFM512GD3JX013N 512GB                        | 4         | 0.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 4         | 0.38%   |
| Seagate ST500DM002-1BD142 500GB                       | 4         | 0.38%   |
| Seagate ST4000DM004-2CV104 4TB                        | 4         | 0.38%   |
| Seagate ST3500418AS 500GB                             | 4         | 0.38%   |
| Seagate ST2000LM007-1R8174 2TB                        | 4         | 0.38%   |
| Seagate ST2000DM001-1ER164 2TB                        | 4         | 0.38%   |
| Kingston SA400S37960G 960GB SSD                       | 4         | 0.38%   |
| Intel SSD 660P Series 512GB                           | 4         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 108       | 136    | 39.42%  |
| WDC                 | 84        | 109    | 30.66%  |
| Toshiba             | 26        | 30     | 9.49%   |
| Hitachi             | 20        | 23     | 7.3%    |
| Samsung Electronics | 12        | 13     | 4.38%   |
| HGST                | 9         | 10     | 3.28%   |
| Unknown             | 6         | 6      | 2.19%   |
| Apple               | 4         | 4      | 1.46%   |
| JMicron Technology  | 1         | 1      | 0.36%   |
| HGST HTS            | 1         | 1      | 0.36%   |
| Fujitsu             | 1         | 1      | 0.36%   |
| ASMT                | 1         | 3      | 0.36%   |
| ASMedia             | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 71        | 85     | 24.4%   |
| Kingston            | 42        | 49     | 14.43%  |
| SanDisk             | 23        | 24     | 7.9%    |
| Crucial             | 23        | 25     | 7.9%    |
| WDC                 | 18        | 19     | 6.19%   |
| China               | 13        | 13     | 4.47%   |
| SK hynix            | 6         | 6      | 2.06%   |
| Micron Technology   | 6         | 7      | 2.06%   |
| Intel               | 6         | 8      | 2.06%   |
| A-DATA Technology   | 6         | 7      | 2.06%   |
| LITEONIT            | 5         | 6      | 1.72%   |
| LITEON              | 4         | 6      | 1.37%   |
| Apple               | 4         | 4      | 1.37%   |
| Team                | 3         | 3      | 1.03%   |
| SPCC                | 3         | 3      | 1.03%   |
| PNY                 | 3         | 3      | 1.03%   |
| Patriot             | 3         | 3      | 1.03%   |
| OCZ                 | 3         | 3      | 1.03%   |
| Toshiba             | 2         | 2      | 0.69%   |
| Smartbuy            | 2         | 3      | 0.69%   |
| OWC                 | 2         | 4      | 0.69%   |
| Netac               | 2         | 2      | 0.69%   |
| KingSpec            | 2         | 2      | 0.69%   |
| Intenso             | 2         | 3      | 0.69%   |
| Gigastone           | 2         | 2      | 0.69%   |
| Gigabyte Technology | 2         | 2      | 0.69%   |
| FORESEE             | 2         | 2      | 0.69%   |
| XrayDisk            | 1         | 1      | 0.34%   |
| WDC WDS2            | 1         | 1      | 0.34%   |
| Verbatim            | 1         | 2      | 0.34%   |
| Vaseky              | 1         | 1      | 0.34%   |
| TEXTORM             | 1         | 1      | 0.34%   |
| T-FORCE             | 1         | 1      | 0.34%   |
| S3+                 | 1         | 1      | 0.34%   |
| Rogueware           | 1         | 1      | 0.34%   |
| Plextor             | 1         | 1      | 0.34%   |
| Pioneer             | 1         | 1      | 0.34%   |
| Phison              | 1         | 1      | 0.34%   |
| ORTIAL              | 1         | 1      | 0.34%   |
| NT-512              | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 356       | 446    | 40.18%  |
| SSD     | 258       | 331    | 29.12%  |
| HDD     | 234       | 338    | 26.41%  |
| MMC     | 29        | 33     | 3.27%   |
| Unknown | 9         | 10     | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 390       | 634    | 47.91%  |
| NVMe | 355       | 438    | 43.61%  |
| SAS  | 40        | 53     | 4.91%   |
| MMC  | 29        | 33     | 3.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 284       | 388    | 55.58%  |
| 0.51-1.0   | 144       | 184    | 28.18%  |
| 1.01-2.0   | 49        | 52     | 9.59%   |
| 3.01-4.0   | 14        | 21     | 2.74%   |
| 4.01-10.0  | 14        | 17     | 2.74%   |
| 2.01-3.0   | 4         | 4      | 0.78%   |
| 10.01-20.0 | 2         | 3      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 196       | 27.8%   |
| 101-250        | 183       | 25.96%  |
| 501-1000       | 130       | 18.44%  |
| 51-100         | 44        | 6.24%   |
| 1001-2000      | 41        | 5.82%   |
| 1-20           | 32        | 4.54%   |
| More than 3000 | 30        | 4.26%   |
| 21-50          | 24        | 3.4%    |
| 2001-3000      | 20        | 2.84%   |
| Unknown        | 5         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 241       | 34.23%  |
| 21-50          | 175       | 24.86%  |
| 101-250        | 89        | 12.64%  |
| 51-100         | 82        | 11.65%  |
| 251-500        | 52        | 7.39%   |
| 501-1000       | 26        | 3.69%   |
| 1001-2000      | 14        | 1.99%   |
| More than 3000 | 11        | 1.56%   |
| 2001-3000      | 9         | 1.28%   |
| Unknown        | 5         | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD5000HHTZ-04N21V0 500GB             | 1         | 1      | 3.23%   |
| WDC WD5000AZLX-22JKKA0 500GB             | 1         | 1      | 3.23%   |
| WDC WD5000AAKX-001CA0 500GB              | 1         | 1      | 3.23%   |
| WDC WD5000AAKS-00UU3A0 500GB             | 1         | 1      | 3.23%   |
| WDC WD10SPZX-21Z10T0 1TB                 | 1         | 1      | 3.23%   |
| WDC WD10EZRZ-00HTKB0 1TB                 | 1         | 1      | 3.23%   |
| WDC WD10EZEX-60WN4A0 1TB                 | 1         | 1      | 3.23%   |
| WDC WD10EZEX-22MFCA0 1TB                 | 1         | 2      | 3.23%   |
| WDC WD10EARS-22Y5B1 1TB                  | 1         | 1      | 3.23%   |
| WDC WD Green M.2 2280 240GB SSD          | 1         | 1      | 3.23%   |
| SK hynix BC711 HFM001TD3JX013N 1TB       | 1         | 1      | 3.23%   |
| Seagate ST500DM002-1BD142 500GB          | 1         | 1      | 3.23%   |
| Seagate ST2000LX001-1RG174 2TB           | 1         | 1      | 3.23%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1      | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 960 EVO 250GB    | 1         | 1      | 3.23%   |
| Samsung Electronics HD502HJ 500GB        | 1         | 1      | 3.23%   |
| Samsung Electronics HD161GJ 160GB        | 1         | 1      | 3.23%   |
| Neo Forza NFS121SA312-6007000 120GB SSD  | 1         | 2      | 3.23%   |
| LITEONIT LCT-256M3S-41 7mm 256GB FDE SSD | 1         | 1      | 3.23%   |
| Kingston SV300S37A120G 120GB SSD         | 1         | 1      | 3.23%   |
| Kingston SUV400S37240G 240GB SSD         | 1         | 1      | 3.23%   |
| Hitachi HTS723225A7A365 OPAL 250GB       | 1         | 1      | 3.23%   |
| Hitachi HTS547564A9E384 640GB            | 1         | 1      | 3.23%   |
| Hitachi HDS721010CLA332 1TB              | 1         | 1      | 3.23%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 3.23%   |
| HGST HTS541010A9E680 1TB                 | 1         | 1      | 3.23%   |
| Gigabyte Technology GP-GM30512G-G 512GB  | 1         | 1      | 3.23%   |
| Fujitsu MHW2160BH 160GB                  | 1         | 1      | 3.23%   |
| Crucial CT512MX100SSD1 512GB             | 1         | 1      | 3.23%   |
| Unknown                                  | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 32.26%  |
| Seagate             | 4         | 4      | 12.9%   |
| Samsung Electronics | 3         | 3      | 9.68%   |
| Hitachi             | 3         | 3      | 9.68%   |
| Kingston            | 2         | 2      | 6.45%   |
| HGST                | 2         | 2      | 6.45%   |
| SK hynix            | 1         | 1      | 3.23%   |
| Neo                 | 1         | 2      | 3.23%   |
| LITEONIT            | 1         | 1      | 3.23%   |
| Gigabyte Technology | 1         | 1      | 3.23%   |
| Fujitsu             | 1         | 1      | 3.23%   |
| Crucial             | 1         | 1      | 3.23%   |
| Unknown             | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 42.86%  |
| Seagate             | 4         | 4      | 19.05%  |
| Hitachi             | 3         | 3      | 14.29%  |
| Samsung Electronics | 2         | 2      | 9.52%   |
| HGST                | 2         | 2      | 9.52%   |
| Fujitsu             | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 22     | 66.67%  |
| SSD  | 7         | 8      | 23.33%  |
| NVMe | 3         | 3      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model               | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| KingDian S400 120GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| KingDian | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 464       | 802    | 64.53%  |
| Works    | 226       | 322    | 31.43%  |
| Malfunc  | 28        | 33     | 3.89%   |
| Failed   | 1         | 1      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 432       | 46.01%  |
| Samsung Electronics                     | 114       | 12.14%  |
| AMD                                     | 107       | 11.4%   |
| SanDisk                                 | 50        | 5.32%   |
| SK hynix                                | 39        | 4.15%   |
| Phison Electronics                      | 28        | 2.98%   |
| Micron Technology                       | 26        | 2.77%   |
| KIOXIA                                  | 24        | 2.56%   |
| Kingston Technology Company             | 24        | 2.56%   |
| Toshiba America Info Systems            | 14        | 1.49%   |
| Micron/Crucial Technology               | 12        | 1.28%   |
| ASMedia Technology                      | 9         | 0.96%   |
| Union Memory (Shenzhen)                 | 6         | 0.64%   |
| Silicon Motion                          | 6         | 0.64%   |
| Realtek Semiconductor                   | 5         | 0.53%   |
| Marvell Technology Group                | 5         | 0.53%   |
| Solid State Storage Technology          | 4         | 0.43%   |
| Nvidia                                  | 4         | 0.43%   |
| Zhaoxin                                 | 3         | 0.32%   |
| Shenzhen Longsys Electronics            | 3         | 0.32%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.32%   |
| JMicron Technology                      | 3         | 0.32%   |
| Apple                                   | 3         | 0.32%   |
| ADATA Technology                        | 3         | 0.32%   |
| Yangtze Memory Technologies             | 2         | 0.21%   |
| Seagate Technology                      | 2         | 0.21%   |
| Transcend                               | 1         | 0.11%   |
| Solidigm                                | 1         | 0.11%   |
| Shenzhen Unionmemory Information System | 1         | 0.11%   |
| Netac Technology                        | 1         | 0.11%   |
| Lenovo                                  | 1         | 0.11%   |
| INNOGRIT                                | 1         | 0.11%   |
| Hewlett-Packard                         | 1         | 0.11%   |
| Broadcom / LSI                          | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 82        | 7.83%   |
| Intel Volume Management Device NVMe RAID Controller                            | 50        | 4.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 38        | 3.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 38        | 3.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 27        | 2.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 24        | 2.29%   |
| Samsung NVMe SSD Controller 980                                                | 23        | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 19        | 1.81%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 18        | 1.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 18        | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 17        | 1.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 16        | 1.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15        | 1.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 13        | 1.24%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 13        | 1.24%   |
| Micron NVMe Storage Controller                                                 | 12        | 1.15%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 12        | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                          | 12        | 1.15%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 1.05%   |
| Kingston Company Company Non-Volatile memory controller                        | 11        | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 1.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 1.05%   |
| Sandisk Non-Volatile memory controller                                         | 10        | 0.96%   |
| Phison E12 NVMe Controller                                                     | 10        | 0.96%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 10        | 0.96%   |
| KIOXIA Non-Volatile memory controller                                          | 10        | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 10        | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 10        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10        | 0.96%   |
| AMD 400 Series Chipset SATA Controller                                         | 10        | 0.96%   |
| Phison PS5013 E13 NVMe Controller                                              | 9         | 0.86%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 9         | 0.86%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 9         | 0.86%   |
| AMD 500 Series Chipset SATA Controller                                         | 9         | 0.86%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 8         | 0.76%   |
| Intel SATA Controller [RAID mode]                                              | 8         | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 8         | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 451       | 47.88%  |
| NVMe | 354       | 37.58%  |
| RAID | 90        | 9.55%   |
| IDE  | 47        | 4.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 526       | 76.12%  |
| AMD           | 156       | 22.58%  |
| ARM           | 5         | 0.72%   |
| CentaurHauls  | 3         | 0.43%   |
| sifive,u74-mc | 1         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 11        | 1.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 10        | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 7         | 1.01%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 7         | 1.01%   |
| Intel 12th Gen Core i7-12700H           | 7         | 1.01%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 7         | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 7         | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 6         | 0.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 6         | 0.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 6         | 0.87%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 6         | 0.87%   |
| Intel 12th Gen Core i7-1260P            | 6         | 0.87%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 6         | 0.87%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 6         | 0.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 5         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 5         | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 5         | 0.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 5         | 0.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 5         | 0.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 5         | 0.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 5         | 0.72%   |
| Intel 12th Gen Core i5-1240P            | 5         | 0.72%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 4         | 0.58%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 4         | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 4         | 0.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 4         | 0.58%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 4         | 0.58%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 4         | 0.58%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 4         | 0.58%   |
| Intel Core i3-10110U CPU @ 2.10GHz      | 4         | 0.58%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 4         | 0.58%   |
| Intel 13th Gen Core i9-13900K           | 4         | 0.58%   |
| Intel 12th Gen Core i7-12700            | 4         | 0.58%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 4         | 0.58%   |
| ARM Processor                           | 4         | 0.58%   |
| AMD Ryzen 9 7900X 12-Core Processor     | 4         | 0.58%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 4         | 0.58%   |
| AMD Ryzen 7 5825U with Radeon Graphics  | 4         | 0.58%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 4         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 137       | 19.83%  |
| Intel Core i5           | 132       | 19.1%   |
| Intel Core i7           | 130       | 18.81%  |
| AMD Ryzen 7             | 48        | 6.95%   |
| Intel Core i3           | 40        | 5.79%   |
| AMD Ryzen 5             | 40        | 5.79%   |
| Intel Core 2 Duo        | 27        | 3.91%   |
| Intel Celeron           | 25        | 3.62%   |
| AMD Ryzen 9             | 21        | 3.04%   |
| Intel Xeon              | 17        | 2.46%   |
| Intel Pentium           | 9         | 1.3%    |
| AMD Ryzen 7 PRO         | 6         | 0.87%   |
| Intel Core 2 Quad       | 5         | 0.72%   |
| AMD A10                 | 5         | 0.72%   |
| Intel Pentium Silver    | 4         | 0.58%   |
| AMD FX                  | 4         | 0.58%   |
| AMD A8                  | 4         | 0.58%   |
| Intel Atom              | 3         | 0.43%   |
| AMD Ryzen 3             | 3         | 0.43%   |
| AMD Phenom II X4        | 3         | 0.43%   |
| AMD E2                  | 3         | 0.43%   |
| AMD A4                  | 3         | 0.43%   |
| Intel Core i9           | 2         | 0.29%   |
| AMD Ryzen 5 PRO         | 2         | 0.29%   |
| AMD A6                  | 2         | 0.29%   |
| Intel Xeon Silver       | 1         | 0.14%   |
| Intel Xeon Gold         | 1         | 0.14%   |
| Intel Pentium Dual-Core | 1         | 0.14%   |
| Intel Pentium Dual      | 1         | 0.14%   |
| Intel Core m7           | 1         | 0.14%   |
| Intel Core M            | 1         | 0.14%   |
| Intel Celeron D         | 1         | 0.14%   |
| ARM BCM                 | 1         | 0.14%   |
| AMD Ryzen Threadripper  | 1         | 0.14%   |
| AMD Ryzen 3 PRO         | 1         | 0.14%   |
| AMD Phenom              | 1         | 0.14%   |
| AMD Athlon II X4        | 1         | 0.14%   |
| AMD Athlon II X3        | 1         | 0.14%   |
| AMD Athlon II X2        | 1         | 0.14%   |
| AMD Athlon II           | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 232       | 33.57%  |
| 2       | 200       | 28.94%  |
| 6       | 85        | 12.3%   |
| 8       | 77        | 11.14%  |
| 12      | 35        | 5.07%   |
| 14      | 18        | 2.6%    |
| 10      | 14        | 2.03%   |
| 16      | 9         | 1.3%    |
| 24      | 6         | 0.87%   |
| 3       | 4         | 0.58%   |
| 1       | 4         | 0.58%   |
| Unknown | 3         | 0.43%   |
| 32      | 2         | 0.29%   |
| 7       | 1         | 0.14%   |
| 5       | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 680       | 98.41%  |
| 2       | 8         | 1.16%   |
| Unknown | 3         | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 500       | 72.25%  |
| 1       | 189       | 27.31%  |
| Unknown | 3         | 0.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 687       | 99.42%  |
| 64-bit         | 2         | 0.29%   |
| Unknown        | 2         | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 597       | 86.27%  |
| 0x0a50000d | 11        | 1.59%   |
| 0x0a601203 | 9         | 1.3%    |
| 0x0a50000c | 8         | 1.16%   |
| 0x0a404102 | 8         | 1.16%   |
| 0x08608103 | 6         | 0.87%   |
| 0x08600106 | 6         | 0.87%   |
| 0x0a404101 | 4         | 0.58%   |
| 0x906a3    | 2         | 0.29%   |
| 0x806ec    | 2         | 0.29%   |
| 0x306a9    | 2         | 0.29%   |
| 0x0a704101 | 2         | 0.29%   |
| 0x0a20120a | 2         | 0.29%   |
| 0x08608102 | 2         | 0.29%   |
| 0x08108109 | 2         | 0.29%   |
| 0x0800820d | 2         | 0.29%   |
| 0x010000c8 | 2         | 0.29%   |
| 0xf64      | 1         | 0.14%   |
| 0x906ea    | 1         | 0.14%   |
| 0x90675    | 1         | 0.14%   |
| 0x806eb    | 1         | 0.14%   |
| 0x806c1    | 1         | 0.14%   |
| 0x506e3    | 1         | 0.14%   |
| 0x406e3    | 1         | 0.14%   |
| 0x306d4    | 1         | 0.14%   |
| 0x306c3    | 1         | 0.14%   |
| 0x1067a    | 1         | 0.14%   |
| 0x0a201205 | 1         | 0.14%   |
| 0x0a201025 | 1         | 0.14%   |
| 0x08a00006 | 1         | 0.14%   |
| 0x08701021 | 1         | 0.14%   |
| 0x08608104 | 1         | 0.14%   |
| 0x08600109 | 1         | 0.14%   |
| 0x08600103 | 1         | 0.14%   |
| 0x08108102 | 1         | 0.14%   |
| 0x08101016 | 1         | 0.14%   |
| 0x0810100b | 1         | 0.14%   |
| 0x07030105 | 1         | 0.14%   |
| 0x06006705 | 1         | 0.14%   |
| 0x06006704 | 1         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 107       | 15.44%  |
| Unknown          | 103       | 14.86%  |
| Skylake          | 44        | 6.35%   |
| IvyBridge        | 43        | 6.2%    |
| Haswell          | 43        | 6.2%    |
| TigerLake        | 41        | 5.92%   |
| Alderlake Hybrid | 41        | 5.92%   |
| Zen 3            | 39        | 5.63%   |
| SandyBridge      | 35        | 5.05%   |
| Penryn           | 29        | 4.18%   |
| Zen 2            | 20        | 2.89%   |
| CometLake        | 18        | 2.6%    |
| Broadwell        | 16        | 2.31%   |
| Zen+             | 14        | 2.02%   |
| Westmere         | 14        | 2.02%   |
| Goldmont plus    | 14        | 2.02%   |
| Silvermont       | 11        | 1.59%   |
| Piledriver       | 10        | 1.44%   |
| K10              | 8         | 1.15%   |
| IceLake          | 8         | 1.15%   |
| Excavator        | 8         | 1.15%   |
| Core             | 8         | 1.15%   |
| Puma             | 4         | 0.58%   |
| Zen              | 3         | 0.43%   |
| Goldmont         | 3         | 0.43%   |
| Nehalem          | 2         | 0.29%   |
| Tremont          | 1         | 0.14%   |
| Steamroller      | 1         | 0.14%   |
| NetBurst         | 1         | 0.14%   |
| K8 Hammer        | 1         | 0.14%   |
| K10 Llano        | 1         | 0.14%   |
| Gracemont        | 1         | 0.14%   |
| Bulldozer        | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 430       | 51.56%  |
| Nvidia                     | 210       | 25.18%  |
| AMD                        | 188       | 22.54%  |
| Zhaoxin                    | 3         | 0.36%   |
| Matrox Electronics Systems | 3         | 0.36%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 31        | 3.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 3.06%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 24        | 2.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 2.83%   |
| Intel HD Graphics 620                                                                    | 19        | 2.24%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 19        | 2.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 1.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.77%   |
| AMD Renoir                                                                               | 15        | 1.77%   |
| AMD Rembrandt [Radeon 680M]                                                              | 15        | 1.77%   |
| Intel UHD Graphics 620                                                                   | 14        | 1.65%   |
| AMD Lucienne                                                                             | 14        | 1.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.53%   |
| Intel HD Graphics 5500                                                                   | 13        | 1.53%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 1.41%   |
| Intel HD Graphics 530                                                                    | 12        | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 1.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.3%    |
| AMD Raphael                                                                              | 11        | 1.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11        | 1.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 1.18%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 9         | 1.06%   |
| Intel HD Graphics 630                                                                    | 9         | 1.06%   |
| AMD Barcelo                                                                              | 9         | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 0.94%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 8         | 0.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 0.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 0.94%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 7         | 0.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 0.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.71%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.59%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| 1 x Intel           | 300       | 43.35%  |
| 1 x AMD             | 145       | 20.95%  |
| Intel + Nvidia      | 104       | 15.03%  |
| 1 x Nvidia          | 80        | 11.56%  |
| AMD + Nvidia        | 22        | 3.18%   |
| Intel + AMD         | 15        | 2.17%   |
| Other               | 7         | 1.01%   |
| 2 x AMD             | 5         | 0.72%   |
| 2 x Intel           | 4         | 0.58%   |
| 1 x Zhaoxin         | 3         | 0.43%   |
| 2 x Nvidia          | 2         | 0.29%   |
| 1 x Matrox          | 2         | 0.29%   |
| 2 x Intel + 1 x AMD | 1         | 0.14%   |
| Nvidia + Matrox     | 1         | 0.14%   |
| Intel + 2 x Nvidia  | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 537       | 77.6%   |
| Proprietary | 131       | 18.93%  |
| Unknown     | 24        | 3.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 555       | 80.2%   |
| 0.01-0.5   | 48        | 6.94%   |
| 1.01-2.0   | 30        | 4.34%   |
| 3.01-4.0   | 18        | 2.6%    |
| 0.51-1.0   | 14        | 2.02%   |
| 7.01-8.0   | 11        | 1.59%   |
| 5.01-6.0   | 5         | 0.72%   |
| 16.01-24.0 | 5         | 0.72%   |
| 8.01-16.0  | 5         | 0.72%   |
| 2.01-3.0   | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 105       | 13.58%  |
| Samsung Electronics     | 87        | 11.25%  |
| BOE                     | 83        | 10.74%  |
| Chimei Innolux          | 64        | 8.28%   |
| LG Display              | 54        | 6.99%   |
| Goldstar                | 41        | 5.3%    |
| Dell                    | 41        | 5.3%    |
| Hewlett-Packard         | 29        | 3.75%   |
| Acer                    | 25        | 3.23%   |
| Ancor Communications    | 20        | 2.59%   |
| AOC                     | 18        | 2.33%   |
| Sharp                   | 17        | 2.2%    |
| Apple                   | 17        | 2.2%    |
| Philips                 | 14        | 1.81%   |
| Lenovo                  | 12        | 1.55%   |
| Iiyama                  | 11        | 1.42%   |
| CSO                     | 11        | 1.42%   |
| BenQ                    | 11        | 1.42%   |
| PANDA                   | 10        | 1.29%   |
| ViewSonic               | 9         | 1.16%   |
| InfoVision              | 9         | 1.16%   |
| MSI                     | 6         | 0.78%   |
| ASUSTek Computer        | 6         | 0.78%   |
| Sony                    | 4         | 0.52%   |
| Denver                  | 4         | 0.52%   |
| Chi Mei Optoelectronics | 4         | 0.52%   |
| Wacom                   | 3         | 0.39%   |
| Unknown (XXX)           | 3         | 0.39%   |
| Unknown                 | 3         | 0.39%   |
| Sceptre Tech            | 3         | 0.39%   |
| NEC Computers           | 3         | 0.39%   |
| Panasonic               | 2         | 0.26%   |
| MiTAC                   | 2         | 0.26%   |
| LG Philips              | 2         | 0.26%   |
| JVC                     | 2         | 0.26%   |
| HKC                     | 2         | 0.26%   |
| Hitachi                 | 2         | 0.26%   |
| Gigabyte Technology     | 2         | 0.26%   |
| Eizo                    | 2         | 0.26%   |
| ___                     | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 8         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 5         | 0.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 5         | 0.63%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 4         | 0.51%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 4         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 3         | 0.38%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.38%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 3         | 0.38%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 3         | 0.38%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO5799 1920x1080 344x194mm 15.5-inch        | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO0BA2 2560x1440 309x174mm 14.0-inch        | 3         | 0.38%   |
| Wacom Cintiq 13HD WAC1040 1920x1080 293x165mm 13.2-inch               | 2         | 0.25%   |
| Sony TV SNY4502 1920x1080                                             | 2         | 0.25%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch               | 2         | 0.25%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.25%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 530x300mm 24.0-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SDC4172 2880x1800 289x186mm 13.5-inch | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SDC416B 3840x2400 344x215mm 16.0-inch | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SAM0D47 1920x1080 885x498mm 40.0-inch | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 2         | 0.25%   |
| Samsung Electronics LC49G95T SAM7053 2560x1440 1193x336mm 48.8-inch   | 2         | 0.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.25%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2         | 0.25%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 2         | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.25%   |
| MSI MAG342CQR MSI3DB6 3440x1440 797x333mm 34.0-inch                   | 2         | 0.25%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 2         | 0.25%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 2         | 0.25%   |
| InfoVision LCD Monitor IVO057E 1366x768 309x174mm 14.0-inch           | 2         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 334       | 45.63%  |
| 1366x768 (WXGA)    | 100       | 13.66%  |
| 3840x2160 (4K)     | 61        | 8.33%   |
| 2560x1440 (QHD)    | 49        | 6.69%   |
| 1920x1200 (WUXGA)  | 28        | 3.83%   |
| 1600x900 (HD+)     | 22        | 3.01%   |
| 2560x1600          | 16        | 2.19%   |
| 3440x1440          | 14        | 1.91%   |
| 2880x1800          | 13        | 1.78%   |
| 1440x900 (WXGA+)   | 11        | 1.5%    |
| 1280x800 (WXGA)    | 10        | 1.37%   |
| 1280x1024 (SXGA)   | 10        | 1.37%   |
| 1680x1050 (WSXGA+) | 8         | 1.09%   |
| 3840x2400          | 7         | 0.96%   |
| 2560x1080          | 6         | 0.82%   |
| 3840x1080          | 5         | 0.68%   |
| 2736x1824          | 4         | 0.55%   |
| Unknown            | 4         | 0.55%   |
| 3840x1600          | 3         | 0.41%   |
| 2160x1440          | 3         | 0.41%   |
| 1920x540           | 3         | 0.41%   |
| 3200x1800 (QHD+)   | 2         | 0.27%   |
| 3000x2000          | 2         | 0.27%   |
| 2520x1680          | 2         | 0.27%   |
| 2256x1504          | 2         | 0.27%   |
| 2240x1400          | 2         | 0.27%   |
| 1280x720 (HD)      | 2         | 0.27%   |
| 5760x2160          | 1         | 0.14%   |
| 3456x2160          | 1         | 0.14%   |
| 3072x1920          | 1         | 0.14%   |
| 2880x1920          | 1         | 0.14%   |
| 2880x1620          | 1         | 0.14%   |
| 1920x1280          | 1         | 0.14%   |
| 1360x768           | 1         | 0.14%   |
| 1128x1504          | 1         | 0.14%   |
| 1024x768 (XGA)     | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 181       | 23.35%  |
| 13      | 90        | 11.61%  |
| 14      | 82        | 10.58%  |
| 27      | 63        | 8.13%   |
| 24      | 43        | 5.55%   |
| 23      | 43        | 5.55%   |
| 21      | 41        | 5.29%   |
| 17      | 32        | 4.13%   |
| 31      | 24        | 3.1%    |
| 16      | 20        | 2.58%   |
| 12      | 17        | 2.19%   |
| 34      | 15        | 1.94%   |
| Unknown | 15        | 1.94%   |
| 19      | 14        | 1.81%   |
| 20      | 11        | 1.42%   |
| 18      | 8         | 1.03%   |
| 40      | 6         | 0.77%   |
| 26      | 6         | 0.77%   |
| 11      | 6         | 0.77%   |
| 84      | 5         | 0.65%   |
| 72      | 5         | 0.65%   |
| 35      | 5         | 0.65%   |
| 22      | 5         | 0.65%   |
| 52      | 4         | 0.52%   |
| 32      | 4         | 0.52%   |
| 54      | 3         | 0.39%   |
| 48      | 3         | 0.39%   |
| 42      | 3         | 0.39%   |
| 25      | 3         | 0.39%   |
| 65      | 2         | 0.26%   |
| 49      | 2         | 0.26%   |
| 43      | 2         | 0.26%   |
| 37      | 2         | 0.26%   |
| 63      | 1         | 0.13%   |
| 61      | 1         | 0.13%   |
| 60      | 1         | 0.13%   |
| 58      | 1         | 0.13%   |
| 46      | 1         | 0.13%   |
| 38      | 1         | 0.13%   |
| 33      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 302       | 39.48%  |
| 501-600     | 144       | 18.82%  |
| 201-300     | 86        | 11.24%  |
| 401-500     | 71        | 9.28%   |
| 351-400     | 46        | 6.01%   |
| 601-700     | 32        | 4.18%   |
| 701-800     | 20        | 2.61%   |
| 1001-1500   | 19        | 2.48%   |
| Unknown     | 15        | 1.96%   |
| 801-900     | 13        | 1.7%    |
| 1501-2000   | 10        | 1.31%   |
| 901-1000    | 6         | 0.78%   |
| 101-200     | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 514       | 74.82%  |
| 16/10   | 100       | 14.56%  |
| 21/9    | 23        | 3.35%   |
| 3/2     | 16        | 2.33%   |
| 5/4     | 12        | 1.75%   |
| Unknown | 10        | 1.46%   |
| 32/9    | 7         | 1.02%   |
| 4/3     | 3         | 0.44%   |
| 6/5     | 1         | 0.15%   |
| 0.62    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 183       | 23.7%   |
| 81-90          | 126       | 16.32%  |
| 201-250        | 96        | 12.44%  |
| 301-350        | 68        | 8.81%   |
| 351-500        | 49        | 6.35%   |
| 71-80          | 48        | 6.22%   |
| 151-200        | 39        | 5.05%   |
| 251-300        | 26        | 3.37%   |
| 121-130        | 25        | 3.24%   |
| More than 1000 | 24        | 3.11%   |
| 111-120        | 18        | 2.33%   |
| 501-1000       | 18        | 2.33%   |
| Unknown        | 15        | 1.94%   |
| 61-70          | 13        | 1.68%   |
| 141-150        | 11        | 1.42%   |
| 51-60          | 7         | 0.91%   |
| 131-140        | 4         | 0.52%   |
| 1-40           | 1         | 0.13%   |
| 91-100         | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 219       | 29.24%  |
| 51-100        | 204       | 27.24%  |
| 101-120       | 171       | 22.83%  |
| 161-240       | 89        | 11.88%  |
| More than 240 | 34        | 4.54%   |
| 1-50          | 17        | 2.27%   |
| Unknown       | 15        | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 533       | 76.69%  |
| 2     | 110       | 15.83%  |
| 0     | 34        | 4.89%   |
| 3     | 15        | 2.16%   |
| 4     | 3         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 353       | 34.27%  |
| Realtek Semiconductor             | 351       | 34.08%  |
| Qualcomm Atheros                  | 75        | 7.28%   |
| Broadcom                          | 60        | 5.83%   |
| MediaTek                          | 43        | 4.17%   |
| TP-Link                           | 20        | 1.94%   |
| Ralink Technology                 | 8         | 0.78%   |
| DisplayLink                       | 8         | 0.78%   |
| Broadcom Limited                  | 8         | 0.78%   |
| ASIX Electronics                  | 8         | 0.78%   |
| Marvell Technology Group          | 7         | 0.68%   |
| Lenovo                            | 7         | 0.68%   |
| Xiaomi                            | 6         | 0.58%   |
| Aquantia                          | 6         | 0.58%   |
| Ralink                            | 5         | 0.49%   |
| NetGear                           | 5         | 0.49%   |
| D-Link                            | 5         | 0.49%   |
| Samsung Electronics               | 4         | 0.39%   |
| Nvidia                            | 4         | 0.39%   |
| Microsoft                         | 4         | 0.39%   |
| Huawei Technologies               | 4         | 0.39%   |
| Sierra Wireless                   | 3         | 0.29%   |
| Google                            | 3         | 0.29%   |
| Edimax Technology                 | 3         | 0.29%   |
| Dell                              | 3         | 0.29%   |
| ASUSTek Computer                  | 3         | 0.29%   |
| Mellanox Technologies             | 2         | 0.19%   |
| Hewlett-Packard                   | 2         | 0.19%   |
| Ericsson Business Mobile Networks | 2         | 0.19%   |
| Apple                             | 2         | 0.19%   |
| ZyDAS                             | 1         | 0.1%    |
| Z-Com                             | 1         | 0.1%    |
| Vimtron Electronics               | 1         | 0.1%    |
| U-Blox                            | 1         | 0.1%    |
| Quectel Wireless Solutions        | 1         | 0.1%    |
| Qualcomm Atheros Communications   | 1         | 0.1%    |
| Qualcomm                          | 1         | 0.1%    |
| MosChip Semiconductor             | 1         | 0.1%    |
| Microchip Technology              | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 202       | 16.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33        | 2.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 33        | 2.75%   |
| Intel Wi-Fi 6 AX201                                               | 32        | 2.67%   |
| Intel Wi-Fi 6 AX200                                               | 27        | 2.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 26        | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 24        | 2%      |
| Intel Wireless 8265 / 8275                                        | 22        | 1.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 18        | 1.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 17        | 1.42%   |
| Intel Wireless 8260                                               | 17        | 1.42%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 16        | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 1.33%   |
| Intel Wireless 7265                                               | 14        | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 1.17%   |
| Intel Ethernet Controller I225-V                                  | 13        | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 12        | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 0.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 10        | 0.83%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 10        | 0.83%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 9         | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.67%   |
| Intel Alder Lake-U CNVi: Wireless-AC                              | 8         | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 0.58%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 0.58%   |
| Intel Wireless 3165                                               | 7         | 0.58%   |
| Intel I211 Gigabit Network Connection                             | 7         | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 7         | 0.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 0.58%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 6         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 292       | 47.25%  |
| Realtek Semiconductor           | 107       | 17.31%  |
| Qualcomm Atheros                | 64        | 10.36%  |
| MediaTek                        | 42        | 6.8%    |
| Broadcom                        | 42        | 6.8%    |
| TP-Link                         | 20        | 3.24%   |
| Ralink Technology               | 8         | 1.29%   |
| Ralink                          | 5         | 0.81%   |
| NetGear                         | 5         | 0.81%   |
| D-Link                          | 5         | 0.81%   |
| Microsoft                       | 4         | 0.65%   |
| Broadcom Limited                | 4         | 0.65%   |
| Sierra Wireless                 | 3         | 0.49%   |
| Edimax Technology               | 3         | 0.49%   |
| ASUSTek Computer                | 3         | 0.49%   |
| ZyDAS                           | 1         | 0.16%   |
| Z-Com                           | 1         | 0.16%   |
| Quectel Wireless Solutions      | 1         | 0.16%   |
| Qualcomm Atheros Communications | 1         | 0.16%   |
| Qualcomm                        | 1         | 0.16%   |
| Marvell Technology Group        | 1         | 0.16%   |
| Linksys                         | 1         | 0.16%   |
| Guillemot                       | 1         | 0.16%   |
| Dell                            | 1         | 0.16%   |
| D-Link System                   | 1         | 0.16%   |
| AVM                             | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 33        | 5.3%    |
| Intel Wi-Fi 6 AX201                                            | 32        | 5.14%   |
| Intel Wi-Fi 6 AX200                                            | 27        | 4.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 26        | 4.17%   |
| Intel Wireless 8265 / 8275                                     | 22        | 3.53%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 18        | 2.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 17        | 2.73%   |
| Intel Wireless 8260                                            | 17        | 2.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 16        | 2.57%   |
| Intel Wireless 7265                                            | 14        | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 2.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 12        | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 12        | 1.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 1.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 10        | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 1.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 9         | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 1.28%   |
| Intel Alder Lake-U CNVi: Wireless-AC                           | 8         | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.12%   |
| Intel Wireless 3165                                            | 7         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 1.12%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 6         | 0.96%   |
| Realtek 802.11ac NIC                                           | 6         | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6         | 0.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 6         | 0.96%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 6         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 0.8%    |
| Intel Centrino Ultimate-N 6300                                 | 5         | 0.8%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 5         | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 0.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 4         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 297       | 53.8%   |
| Intel                    | 148       | 26.81%  |
| Broadcom                 | 24        | 4.35%   |
| Qualcomm Atheros         | 16        | 2.9%    |
| DisplayLink              | 8         | 1.45%   |
| ASIX Electronics         | 8         | 1.45%   |
| Lenovo                   | 7         | 1.27%   |
| Xiaomi                   | 6         | 1.09%   |
| Marvell Technology Group | 6         | 1.09%   |
| Aquantia                 | 6         | 1.09%   |
| Nvidia                   | 4         | 0.72%   |
| Broadcom Limited         | 4         | 0.72%   |
| Samsung Electronics      | 3         | 0.54%   |
| Google                   | 3         | 0.54%   |
| Mellanox Technologies    | 2         | 0.36%   |
| Huawei Technologies      | 2         | 0.36%   |
| Vimtron Electronics      | 1         | 0.18%   |
| TP-Link                  | 1         | 0.18%   |
| MosChip Semiconductor    | 1         | 0.18%   |
| Microchip Technology     | 1         | 0.18%   |
| MediaTek                 | 1         | 0.18%   |
| JMicron Technology       | 1         | 0.18%   |
| Hewlett-Packard          | 1         | 0.18%   |
| Apple                    | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 202       | 35.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33        | 5.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 4.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 24        | 4.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.84%   |
| Intel Ethernet Controller I225-V                                  | 13        | 2.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 2.13%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 1.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 1.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 1.24%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.24%   |
| Intel Ethernet Connection (7) I219-V                              | 7         | 1.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.89%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.89%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.89%   |
| Realtek Killer E3000 2.5GbE Controller                            | 4         | 0.71%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.71%   |
| Intel Ethernet Controller I226-V                                  | 4         | 0.71%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.71%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.71%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.53%   |
| Intel Ethernet Connection (17) I219-V                             | 3         | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.53%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.53%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.53%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3         | 0.53%   |
| Realtek PCIe GbE Family Controller                                | 2         | 0.35%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 589       | 52.87%  |
| Ethernet | 513       | 46.05%  |
| Modem    | 12        | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 446       | 63.08%  |
| Ethernet | 261       | 36.92%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 330       | 47.69%  |
| 2     | 327       | 47.25%  |
| 3     | 16        | 2.31%   |
| 0     | 16        | 2.31%   |
| 6     | 1         | 0.14%   |
| 5     | 1         | 0.14%   |
| 4     | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 472       | 68.11%  |
| Yes  | 221       | 31.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 263       | 52.18%  |
| Realtek Semiconductor           | 55        | 10.91%  |
| Qualcomm Atheros Communications | 31        | 6.15%   |
| IMC Networks                    | 26        | 5.16%   |
| Foxconn / Hon Hai               | 23        | 4.56%   |
| Broadcom                        | 17        | 3.37%   |
| Apple                           | 17        | 3.37%   |
| Cambridge Silicon Radio         | 15        | 2.98%   |
| Lite-On Technology              | 12        | 2.38%   |
| Realtek                         | 10        | 1.98%   |
| MediaTek                        | 9         | 1.79%   |
| ASUSTek Computer                | 6         | 1.19%   |
| TP-Link                         | 5         | 0.99%   |
| Hewlett-Packard                 | 3         | 0.6%    |
| Dell                            | 3         | 0.6%    |
| Toshiba                         | 2         | 0.4%    |
| Opticis                         | 2         | 0.4%    |
| Ralink Technology               | 1         | 0.2%    |
| Marvell Semiconductor           | 1         | 0.2%    |
| Integrated System Solution      | 1         | 0.2%    |
| Fujitsu                         | 1         | 0.2%    |
| Dynex                           | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 72        | 14.29%  |
| Intel Bluetooth wireless interface                  | 65        | 12.9%   |
| Realtek Bluetooth Radio                             | 45        | 8.93%   |
| Intel Bluetooth Device                              | 40        | 7.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 39        | 7.74%   |
| Intel AX200 Bluetooth                               | 26        | 5.16%   |
| Qualcomm Atheros  Bluetooth Device                  | 15        | 2.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 2.98%   |
| IMC Networks Wireless_Device                        | 13        | 2.58%   |
| IMC Networks Bluetooth Radio                        | 11        | 2.18%   |
| Foxconn / Hon Hai Wireless_Device                   | 11        | 2.18%   |
| Realtek Bluetooth Radio                             | 10        | 1.98%   |
| MediaTek Wireless_Device                            | 9         | 1.79%   |
| Intel AX210 Bluetooth                               | 9         | 1.79%   |
| Apple Bluetooth USB Host Controller                 | 7         | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.19%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 1.19%   |
| TP-Link UB500 Adapter                               | 5         | 0.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.99%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 0.99%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 5         | 0.99%   |
| Apple Bluetooth Host Controller                     | 5         | 0.99%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.79%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.79%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 0.79%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.6%    |
| Realtek RTL8723B Bluetooth                          | 3         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.6%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.6%    |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.6%    |
| Apple Bluetooth HCI                                 | 3         | 0.6%    |
| Opticis Bluetooth Radio                             | 2         | 0.4%    |
| Lite-On Wireless_Device                             | 2         | 0.4%    |
| Lite-On Bluetooth Device                            | 2         | 0.4%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.4%    |
| IMC Networks BCM20702A0                             | 2         | 0.4%    |
| Broadcom HP Portable Valentine                      | 2         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 512       | 53.39%  |
| AMD                                             | 185       | 19.29%  |
| Nvidia                                          | 150       | 15.64%  |
| C-Media Electronics                             | 18        | 1.88%   |
| Logitech                                        | 10        | 1.04%   |
| GN Netcom                                       | 10        | 1.04%   |
| Realtek Semiconductor                           | 7         | 0.73%   |
| Lenovo                                          | 7         | 0.73%   |
| Texas Instruments                               | 4         | 0.42%   |
| ASUSTek Computer                                | 4         | 0.42%   |
| Zhaoxin                                         | 3         | 0.31%   |
| VIA Technologies                                | 3         | 0.31%   |
| Razer USA                                       | 3         | 0.31%   |
| KORG                                            | 3         | 0.31%   |
| Generalplus Technology                          | 3         | 0.31%   |
| SteelSeries ApS                                 | 2         | 0.21%   |
| Samson Technologies                             | 2         | 0.21%   |
| Plantronics                                     | 2         | 0.21%   |
| Native Instruments                              | 2         | 0.21%   |
| Giga-Byte Technology                            | 2         | 0.21%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1         | 0.1%    |
| USB Audio                                       | 1         | 0.1%    |
| Tenx Technology                                 | 1         | 0.1%    |
| Superlux digit                                  | 1         | 0.1%    |
| Sennheiser Communications                       | 1         | 0.1%    |
| Scarlett                                        | 1         | 0.1%    |
| Samsung Electronics                             | 1         | 0.1%    |
| Nektar                                          | 1         | 0.1%    |
| Micro Star International                        | 1         | 0.1%    |
| M-Audio                                         | 1         | 0.1%    |
| Licensed by Sony Computer Entertainment America | 1         | 0.1%    |
| JMTek                                           | 1         | 0.1%    |
| Jieli Technology                                | 1         | 0.1%    |
| JBL                                             | 1         | 0.1%    |
| Huawei Technologies                             | 1         | 0.1%    |
| Hewlett-Packard                                 | 1         | 0.1%    |
| ESS Technology                                  | 1         | 0.1%    |
| DSEA A/S                                        | 1         | 0.1%    |
| Creative Technology                             | 1         | 0.1%    |
| Creative Labs                                   | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 91        | 7.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 57        | 4.98%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 56        | 4.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 41        | 3.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 37        | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 37        | 3.23%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 36        | 3.14%   |
| Intel Cannon Lake PCH cAVS                                                 | 28        | 2.45%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 28        | 2.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 22        | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18        | 1.57%   |
| Nvidia GA106 High Definition Audio Controller                              | 16        | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16        | 1.4%    |
| Intel Broadwell-U Audio Controller                                         | 16        | 1.4%    |
| Nvidia Audio device                                                        | 15        | 1.31%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 1.31%   |
| Intel Alder Lake-S HD Audio Controller                                     | 15        | 1.31%   |
| AMD Starship/Matisse HD Audio Controller                                   | 15        | 1.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 14        | 1.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 14        | 1.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 14        | 1.22%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 1.14%   |
| AMD FCH Azalia Controller                                                  | 13        | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 12        | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12        | 1.05%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 0.96%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 0.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 0.87%   |
| Intel Comet Lake PCH cAVS                                                  | 10        | 0.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10        | 0.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 9         | 0.79%   |
| Intel Alder Lake-U cAVS (Audio, Voice, Speech)                             | 9         | 0.79%   |
| Intel 200 Series PCH HD Audio                                              | 9         | 0.79%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 9         | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 0.7%    |
| Nvidia GM204 High Definition Audio Controller                              | 8         | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung Electronics                  | 83        | 22.37%  |
| SK hynix                             | 68        | 18.33%  |
| Micron Technology                    | 58        | 15.63%  |
| Kingston                             | 37        | 9.97%   |
| Crucial                              | 21        | 5.66%   |
| Unknown                              | 14        | 3.77%   |
| Corsair                              | 13        | 3.5%    |
| G.Skill                              | 10        | 2.7%    |
| Ramaxel Technology                   | 8         | 2.16%   |
| Unknown (ABCD)                       | 6         | 1.62%   |
| A-DATA Technology                    | 6         | 1.62%   |
| Transcend                            | 5         | 1.35%   |
| Smart                                | 5         | 1.35%   |
| GOODRAM                              | 4         | 1.08%   |
| Shenzhen WODPOSIT                    | 3         | 0.81%   |
| Elpida                               | 3         | 0.81%   |
| Unknown                              | 3         | 0.81%   |
| Timetec                              | 2         | 0.54%   |
| Team                                 | 2         | 0.54%   |
| Nanya Technology                     | 2         | 0.54%   |
| Unknown (0x9801)                     | 1         | 0.27%   |
| Unknown (0x0CDC)                     | 1         | 0.27%   |
| Unifosa                              | 1         | 0.27%   |
| Strontium                            | 1         | 0.27%   |
| Saikano                              | 1         | 0.27%   |
| PNY                                  | 1         | 0.27%   |
| Patriot Memory                       | 1         | 0.27%   |
| Patriot                              | 1         | 0.27%   |
| Lexar                                | 1         | 0.27%   |
| Kingmax                              | 1         | 0.27%   |
| KINGBANK                             | 1         | 0.27%   |
| Juhor                                | 1         | 0.27%   |
| Hewlett-Packard                      | 1         | 0.27%   |
| Gold Key                             | 1         | 0.27%   |
| Chun Well Technology Holding Limited | 1         | 0.27%   |
| ChangXin Memory                      | 1         | 0.27%   |
| Atermiter                            | 1         | 0.27%   |
| ASint Technology                     | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 6         | 1.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.55%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 5         | 1.29%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.03%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 4         | 1.03%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 1.03%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.77%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.77%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s            | 3         | 0.77%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.77%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.77%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 3         | 0.77%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.77%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.77%   |
| Unknown                                                          | 3         | 0.77%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.52%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.52%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 2         | 0.52%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.52%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.52%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 2         | 0.52%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.52%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.52%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.52%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 0.52%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.52%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.52%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s     | 2         | 0.52%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s           | 2         | 0.52%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s             | 2         | 0.52%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB SODIMM LPDDR5 6400MT/s           | 2         | 0.52%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 163       | 48.95%  |
| DDR3    | 55        | 16.52%  |
| DDR5    | 34        | 10.21%  |
| LPDDR4  | 28        | 8.41%   |
| LPDDR5  | 22        | 6.61%   |
| LPDDR3  | 11        | 3.3%    |
| SDRAM   | 9         | 2.7%    |
| DDR2    | 7         | 2.1%    |
| Unknown | 3         | 0.9%    |
| DDR     | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 194       | 58.61%  |
| DIMM         | 76        | 22.96%  |
| Row Of Chips | 56        | 16.92%  |
| Chip         | 4         | 1.21%   |
| Unknown      | 1         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 162       | 45.63%  |
| 4096  | 77        | 21.69%  |
| 16384 | 66        | 18.59%  |
| 32768 | 22        | 6.2%    |
| 2048  | 22        | 6.2%    |
| 1024  | 5         | 1.41%   |
| 1536  | 1         | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 85        | 23.81%  |
| 2667    | 45        | 12.61%  |
| 1600    | 43        | 12.04%  |
| 6400    | 23        | 6.44%   |
| 2400    | 23        | 6.44%   |
| 4800    | 19        | 5.32%   |
| 4267    | 17        | 4.76%   |
| 2133    | 12        | 3.36%   |
| 1333    | 10        | 2.8%    |
| 1867    | 6         | 1.68%   |
| 1334    | 6         | 1.68%   |
| 5600    | 5         | 1.4%    |
| 3600    | 5         | 1.4%    |
| 2666    | 5         | 1.4%    |
| 6000    | 4         | 1.12%   |
| 3733    | 4         | 1.12%   |
| 800     | 4         | 1.12%   |
| 5200    | 3         | 0.84%   |
| 2933    | 3         | 0.84%   |
| 2048    | 3         | 0.84%   |
| 667     | 3         | 0.84%   |
| Unknown | 3         | 0.84%   |
| 8400    | 2         | 0.56%   |
| 5808    | 2         | 0.56%   |
| 4266    | 2         | 0.56%   |
| 4199    | 2         | 0.56%   |
| 3866    | 2         | 0.56%   |
| 3400    | 2         | 0.56%   |
| 3266    | 2         | 0.56%   |
| 5500    | 1         | 0.28%   |
| 3800    | 1         | 0.28%   |
| 3666    | 1         | 0.28%   |
| 3466    | 1         | 0.28%   |
| 3334    | 1         | 0.28%   |
| 3066    | 1         | 0.28%   |
| 1866    | 1         | 0.28%   |
| 1067    | 1         | 0.28%   |
| 1066    | 1         | 0.28%   |
| 975     | 1         | 0.28%   |
| 533     | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 31.25%  |
| Hewlett-Packard     | 4         | 25%     |
| Seiko Epson         | 2         | 12.5%   |
| Canon               | 2         | 12.5%   |
| Brother Industries  | 2         | 12.5%   |
| QinHeng Electronics | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 6.25%   |
| Seiko Epson ET-2820 Series                   | 1         | 6.25%   |
| Samsung SCX-4623 Series                      | 1         | 6.25%   |
| Samsung SCX-3400 Series                      | 1         | 6.25%   |
| Samsung ML-216x Series Laser Printer         | 1         | 6.25%   |
| Samsung CLX-3170 Series                      | 1         | 6.25%   |
| Samsung C1860 Series                         | 1         | 6.25%   |
| QinHeng CH340S                               | 1         | 6.25%   |
| HP LaserJet Pro M201dw                       | 1         | 6.25%   |
| HP LaserJet P2055 series                     | 1         | 6.25%   |
| HP DeskJet 960c                              | 1         | 6.25%   |
| HP ColorLaserJet M253-M254                   | 1         | 6.25%   |
| Canon TS3100 series                          | 1         | 6.25%   |
| Canon TR4500 series                          | 1         | 6.25%   |
| Brother MFC-9330CDW                          | 1         | 6.25%   |
| Brother HL-2030 Laser Printer                | 1         | 6.25%   |

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
| Chicony Electronics                    | 90        | 19.78%  |
| Microdia                               | 45        | 9.89%   |
| IMC Networks                           | 43        | 9.45%   |
| Realtek Semiconductor                  | 33        | 7.25%   |
| Quanta                                 | 32        | 7.03%   |
| Logitech                               | 30        | 6.59%   |
| Luxvisions Innotech Limited            | 24        | 5.27%   |
| Apple                                  | 22        | 4.84%   |
| Sunplus Innovation Technology          | 19        | 4.18%   |
| Bison Electronics                      | 18        | 3.96%   |
| Syntek                                 | 10        | 2.2%    |
| Sonix Technology                       | 10        | 2.2%    |
| Cheng Uei Precision Industry (Foxlink) | 10        | 2.2%    |
| Acer                                   | 8         | 1.76%   |
| Lite-On Technology                     | 7         | 1.54%   |
| Alcor Micro                            | 6         | 1.32%   |
| Samsung Electronics                    | 5         | 1.1%    |
| Microsoft                              | 5         | 1.1%    |
| Suyin                                  | 4         | 0.88%   |
| Silicon Motion                         | 4         | 0.88%   |
| Importek                               | 4         | 0.88%   |
| USB Camera                             | 2         | 0.44%   |
| SunplusIT                              | 2         | 0.44%   |
| ShineTech                              | 2         | 0.44%   |
| Pixart Imaging                         | 2         | 0.44%   |
| ARC International                      | 2         | 0.44%   |
| Sunplus Technology                     | 1         | 0.22%   |
| Shine-optics                           | 1         | 0.22%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.22%   |
| Ricoh                                  | 1         | 0.22%   |
| Razer USA                              | 1         | 0.22%   |
| Linux Foundation HS                    | 1         | 0.22%   |
| Lenovo                                 | 1         | 0.22%   |
| KYE Systems (Mouse Systems)            | 1         | 0.22%   |
| Hewlett-Packard                        | 1         | 0.22%   |
| Generalplus Technology                 | 1         | 0.22%   |
| Foxconn / Hon Hai                      | 1         | 0.22%   |
| eMeet-200611                           | 1         | 0.22%   |
| eMeet                                  | 1         | 0.22%   |
| BKX-210918                             | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 25        | 5.39%   |
| Microdia Integrated_Webcam_HD                        | 19        | 4.09%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 13        | 2.8%    |
| IMC Networks Integrated Camera                       | 13        | 2.8%    |
| Chicony HP HD Camera                                 | 12        | 2.59%   |
| Logitech Webcam C270                                 | 10        | 2.16%   |
| Realtek Integrated_Webcam_HD                         | 9         | 1.94%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 8         | 1.72%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 8         | 1.72%   |
| Syntek Integrated Camera                             | 7         | 1.51%   |
| Luxvisions Innotech Limited Integrated Camera        | 7         | 1.51%   |
| Sunplus Integrated_Webcam_HD                         | 6         | 1.29%   |
| Sonix USB2.0 FHD UVC WebCam                          | 6         | 1.29%   |
| Realtek USB Camera                                   | 6         | 1.29%   |
| Quanta ov9734_techfront_camera                       | 6         | 1.29%   |
| Chicony HP Truevision HD                             | 6         | 1.29%   |
| Chicony HD WebCam                                    | 6         | 1.29%   |
| Samsung Galaxy A5 (MTP)                              | 5         | 1.08%   |
| Quanta HD User Facing                                | 5         | 1.08%   |
| Quanta HD Camera                                     | 5         | 1.08%   |
| Microdia Integrated_Webcam_FHD                       | 5         | 1.08%   |
| Logitech HD Pro Webcam C920                          | 5         | 1.08%   |
| Lite-On Integrated Camera                            | 5         | 1.08%   |
| Apple Built-in iSight                                | 5         | 1.08%   |
| Sonix USB2.0 HD UVC WebCam                           | 4         | 0.86%   |
| Microdia Webcam Vitade AF                            | 4         | 0.86%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 4         | 0.86%   |
| IMC Networks HD Camera                               | 4         | 0.86%   |
| Chicony HD User Facing                               | 4         | 0.86%   |
| Bison SunplusIT Integrated Camera                    | 4         | 0.86%   |
| Bison Integrated Camera                              | 4         | 0.86%   |
| Apple FaceTime HD Camera (Built-in)                  | 4         | 0.86%   |
| Acer Integrated Camera                               | 4         | 0.86%   |
| Sunplus FHD Camera Microphone                        | 3         | 0.65%   |
| Realtek Integrated Webcam HD                         | 3         | 0.65%   |
| Quanta HD Webcam                                     | 3         | 0.65%   |
| Quanta Acer FHD User Facing                          | 3         | 0.65%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 3         | 0.65%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 3         | 0.65%   |
| Luxvisions Innotech Limited HP HD Camera             | 3         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 31        | 29.52%  |
| Synaptics                          | 27        | 25.71%  |
| Validity Sensors                   | 26        | 24.76%  |
| Elan Microelectronics              | 9         | 8.57%   |
| LighTuning Technology              | 4         | 3.81%   |
| Upek                               | 3         | 2.86%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.86%   |
| STMicroelectronics                 | 1         | 0.95%   |
| Focal-systems.Corp                 | 1         | 0.95%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 21        | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 5.71%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 5.71%   |
| Elan ELAN:ARM-M4                                                           | 6         | 5.71%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 3.81%   |
| Synaptics WBDI                                                             | 4         | 3.81%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 3.81%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 3.81%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.86%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 2.86%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.86%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.86%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.86%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 2.86%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 2.86%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.9%    |
| Synaptics  WBDI                                                            | 2         | 1.9%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.9%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.9%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.95%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.95%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.95%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.95%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.95%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.95%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.95%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.95%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.95%   |
| Synaptics UWP WBDI                                                         | 1         | 0.95%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.95%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.95%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.95%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.95%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Broadcom        | 17        | 58.62%  |
| Alcor Micro     | 9         | 31.03%  |
| Upek            | 2         | 6.9%    |
| Hewlett-Packard | 1         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 9         | 31.03%  |
| Broadcom 5880                                              | 6         | 20.69%  |
| Broadcom 58200                                             | 6         | 20.69%  |
| Broadcom BCM5880 Secure Applications Processor             | 5         | 17.24%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 6.9%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)              | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 442       | 63.23%  |
| 1     | 203       | 29.04%  |
| 2     | 37        | 5.29%   |
| 3     | 11        | 1.57%   |
| 4     | 4         | 0.57%   |
| 10    | 1         | 0.14%   |
| 6     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 106       | 34.19%  |
| Graphics card            | 62        | 20%     |
| Net/wireless             | 29        | 9.35%   |
| Chipcard                 | 27        | 8.71%   |
| Camera                   | 22        | 7.1%    |
| Multimedia controller    | 20        | 6.45%   |
| Unassigned class         | 11        | 3.55%   |
| Communication controller | 9         | 2.9%    |
| Sound                    | 8         | 2.58%   |
| Storage                  | 4         | 1.29%   |
| Bluetooth                | 4         | 1.29%   |
| Card reader              | 3         | 0.97%   |
| Net/ethernet             | 2         | 0.65%   |
| Storage/ide              | 1         | 0.32%   |
| Network                  | 1         | 0.32%   |
| Modem                    | 1         | 0.32%   |

