Ubuntu 23.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 517

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Timi          | Redmi Book Pro 14 2022      | [b5d1a7e115](https://linux-hardware.org/?probe=b5d1a7e115) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430 2347AT2       | [951adb91cd](https://linux-hardware.org/?probe=951adb91cd) | Jun 30, 2023 |
| HP            | ProBook 650 G5              | [99a03772fb](https://linux-hardware.org/?probe=99a03772fb) | Jun 30, 2023 |
| HP            | Laptop 17-cp2xxx            | [2012cd2c37](https://linux-hardware.org/?probe=2012cd2c37) | Jun 30, 2023 |
| HP            | 245 G6 Notebook PC          | [22a896d74b](https://linux-hardware.org/?probe=22a896d74b) | Jun 30, 2023 |
| Dell          | Latitude 5440               | [7868400967](https://linux-hardware.org/?probe=7868400967) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1e4c2cf905](https://linux-hardware.org/?probe=1e4c2cf905) | Jun 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [b98433fa84](https://linux-hardware.org/?probe=b98433fa84) | Jun 29, 2023 |
| Acer          | NC-A515-51G-59DM            | [a521f2cc60](https://linux-hardware.org/?probe=a521f2cc60) | Jun 29, 2023 |
| Intel         | Whiskey Platform            | [1caca06d89](https://linux-hardware.org/?probe=1caca06d89) | Jun 29, 2023 |
| ASUSTek       | K56CB                       | [952909bc80](https://linux-hardware.org/?probe=952909bc80) | Jun 29, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [61930889dc](https://linux-hardware.org/?probe=61930889dc) | Jun 29, 2023 |
| Unknown       | Unknown                     | [d358089f32](https://linux-hardware.org/?probe=d358089f32) | Jun 29, 2023 |
| HP            | Laptop 17-cp2xxx            | [f1a1aa76e2](https://linux-hardware.org/?probe=f1a1aa76e2) | Jun 29, 2023 |
| Sony          | SVE17137CXB                 | [ed6f82dc16](https://linux-hardware.org/?probe=ed6f82dc16) | Jun 29, 2023 |
| Acer          | Nitro AN515-55              | [a41ff8c573](https://linux-hardware.org/?probe=a41ff8c573) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | [3c4acbf380](https://linux-hardware.org/?probe=3c4acbf380) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ff560998d8](https://linux-hardware.org/?probe=ff560998d8) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7017964456](https://linux-hardware.org/?probe=7017964456) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | [8ae62960d8](https://linux-hardware.org/?probe=8ae62960d8) | Jun 28, 2023 |
| Acer          | Nitro AN515-54              | [b30ff15571](https://linux-hardware.org/?probe=b30ff15571) | Jun 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [90a10ed8ed](https://linux-hardware.org/?probe=90a10ed8ed) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [4e40b350ca](https://linux-hardware.org/?probe=4e40b350ca) | Jun 28, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | [1d6bf708ce](https://linux-hardware.org/?probe=1d6bf708ce) | Jun 28, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [8ef6f6f24a](https://linux-hardware.org/?probe=8ef6f6f24a) | Jun 27, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [d4c9f8de35](https://linux-hardware.org/?probe=d4c9f8de35) | Jun 27, 2023 |
| HP            | ENVY 15                     | [0d46d829d2](https://linux-hardware.org/?probe=0d46d829d2) | Jun 27, 2023 |
| HP            | ENVY 15                     | [189cf01c37](https://linux-hardware.org/?probe=189cf01c37) | Jun 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7497c404d4](https://linux-hardware.org/?probe=7497c404d4) | Jun 27, 2023 |
| Daten Tecn... | ESTELAR                     | [0052df6a90](https://linux-hardware.org/?probe=0052df6a90) | Jun 27, 2023 |
| Daten Tecn... | ESTELAR                     | [d5f99bced6](https://linux-hardware.org/?probe=d5f99bced6) | Jun 26, 2023 |
| HUAWEI        | BOM-WXX9                    | [2e9bc10188](https://linux-hardware.org/?probe=2e9bc10188) | Jun 26, 2023 |
| Gateway       | NV57H                       | [a49db45595](https://linux-hardware.org/?probe=a49db45595) | Jun 26, 2023 |
| Gateway       | NV57H                       | [ee84597590](https://linux-hardware.org/?probe=ee84597590) | Jun 26, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | [70a6547925](https://linux-hardware.org/?probe=70a6547925) | Jun 26, 2023 |
| Star Labs     | LabTop                      | [87a0d9dc09](https://linux-hardware.org/?probe=87a0d9dc09) | Jun 26, 2023 |
| Acer          | TravelMate 6493             | [490906b996](https://linux-hardware.org/?probe=490906b996) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [286826f3b2](https://linux-hardware.org/?probe=286826f3b2) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b15f68a294](https://linux-hardware.org/?probe=b15f68a294) | Jun 25, 2023 |
| Acer          | Nitro AN517-54              | [9a87719748](https://linux-hardware.org/?probe=9a87719748) | Jun 25, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [9f1f9757a2](https://linux-hardware.org/?probe=9f1f9757a2) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [223911e8f0](https://linux-hardware.org/?probe=223911e8f0) | Jun 25, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | [1809b4709e](https://linux-hardware.org/?probe=1809b4709e) | Jun 25, 2023 |
| HP            | EliteBook 840 G4            | [2e20ab8996](https://linux-hardware.org/?probe=2e20ab8996) | Jun 25, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [7d8f0212e9](https://linux-hardware.org/?probe=7d8f0212e9) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | [ade3806ebb](https://linux-hardware.org/?probe=ade3806ebb) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [8a22a7fba4](https://linux-hardware.org/?probe=8a22a7fba4) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | [b82cc440a0](https://linux-hardware.org/?probe=b82cc440a0) | Jun 24, 2023 |
| Dell          | G5 5590                     | [6d6974b0eb](https://linux-hardware.org/?probe=6d6974b0eb) | Jun 24, 2023 |
| HP            | ENVY 15                     | [3918cca1e5](https://linux-hardware.org/?probe=3918cca1e5) | Jun 23, 2023 |
| Acer          | Swift SFE16-42              | [9afa4fb174](https://linux-hardware.org/?probe=9afa4fb174) | Jun 22, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [44050251e9](https://linux-hardware.org/?probe=44050251e9) | Jun 22, 2023 |
| Positivo      | Mobile                      | [f9a55866f0](https://linux-hardware.org/?probe=f9a55866f0) | Jun 22, 2023 |
| Positivo      | Mobile                      | [25df2e5abc](https://linux-hardware.org/?probe=25df2e5abc) | Jun 22, 2023 |
| Acer          | Aspire E5-575G              | [0fb6c61a2b](https://linux-hardware.org/?probe=0fb6c61a2b) | Jun 21, 2023 |
| Acer          | Aspire A515-53G             | [430cfefc6a](https://linux-hardware.org/?probe=430cfefc6a) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | [f96a1a3552](https://linux-hardware.org/?probe=f96a1a3552) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | [52c4c32098](https://linux-hardware.org/?probe=52c4c32098) | Jun 21, 2023 |
| HP            | EliteBook 830 G6            | [7a29f3d086](https://linux-hardware.org/?probe=7a29f3d086) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [513165d4f6](https://linux-hardware.org/?probe=513165d4f6) | Jun 20, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [b51dda105a](https://linux-hardware.org/?probe=b51dda105a) | Jun 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [bff08fbf94](https://linux-hardware.org/?probe=bff08fbf94) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [15e75e17fc](https://linux-hardware.org/?probe=15e75e17fc) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [6dea148dd7](https://linux-hardware.org/?probe=6dea148dd7) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [91f85b5bb5](https://linux-hardware.org/?probe=91f85b5bb5) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [93f576698e](https://linux-hardware.org/?probe=93f576698e) | Jun 19, 2023 |
| HP            | Laptop 15-rb0xx             | [067eeb10e5](https://linux-hardware.org/?probe=067eeb10e5) | Jun 19, 2023 |
| HP            | Notebook                    | [6df5e3f6ff](https://linux-hardware.org/?probe=6df5e3f6ff) | Jun 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [948225d98e](https://linux-hardware.org/?probe=948225d98e) | Jun 18, 2023 |
| Toshiba       | Satellite-L845              | [cfe5a81354](https://linux-hardware.org/?probe=cfe5a81354) | Jun 18, 2023 |
| ASUSTek       | X555LJ                      | [a4bea0f3e3](https://linux-hardware.org/?probe=a4bea0f3e3) | Jun 18, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [8bf2dd01d7](https://linux-hardware.org/?probe=8bf2dd01d7) | Jun 18, 2023 |
| Panasonic     | CF-54-2                     | [48b7e4f212](https://linux-hardware.org/?probe=48b7e4f212) | Jun 18, 2023 |
| HP            | Pavilion dv6                | [f47b055767](https://linux-hardware.org/?probe=f47b055767) | Jun 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | [8f32e75d6e](https://linux-hardware.org/?probe=8f32e75d6e) | Jun 18, 2023 |
| Medion        | S15449                      | [9ee17b411b](https://linux-hardware.org/?probe=9ee17b411b) | Jun 17, 2023 |
| HP            | ENVY 15                     | [10a4cb8865](https://linux-hardware.org/?probe=10a4cb8865) | Jun 17, 2023 |
| Acer          | Aspire A715-71G             | [0ef00ccccc](https://linux-hardware.org/?probe=0ef00ccccc) | Jun 16, 2023 |
| Toshiba       | Satellite C870-199          | [cc18b4ff53](https://linux-hardware.org/?probe=cc18b4ff53) | Jun 16, 2023 |
| MSI           | GF63 Thin 10SC              | [cd928f7cc4](https://linux-hardware.org/?probe=cd928f7cc4) | Jun 16, 2023 |
| MSI           | GF63 Thin 10SC              | [3204bd2215](https://linux-hardware.org/?probe=3204bd2215) | Jun 16, 2023 |
| Packard Be... | EasyNote TK87               | [eeb1bdc4d1](https://linux-hardware.org/?probe=eeb1bdc4d1) | Jun 15, 2023 |
| Packard Be... | EasyNote TK87               | [3ba89fb405](https://linux-hardware.org/?probe=3ba89fb405) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [fe65868ffe](https://linux-hardware.org/?probe=fe65868ffe) | Jun 15, 2023 |
| MSI           | Stealth GS77 12UE           | [48df655e45](https://linux-hardware.org/?probe=48df655e45) | Jun 15, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [e9aeb26aeb](https://linux-hardware.org/?probe=e9aeb26aeb) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [f675b70f23](https://linux-hardware.org/?probe=f675b70f23) | Jun 14, 2023 |
| Dell          | XPS 15 9510                 | [9a8a71741e](https://linux-hardware.org/?probe=9a8a71741e) | Jun 14, 2023 |
| Sony          | SVS1312J3EW                 | [6668ed0dbe](https://linux-hardware.org/?probe=6668ed0dbe) | Jun 14, 2023 |
| PC Special... | P65_P67RGRERA               | [49773a4767](https://linux-hardware.org/?probe=49773a4767) | Jun 14, 2023 |
| ASUSTek       | N73SV                       | [b3b70ef13b](https://linux-hardware.org/?probe=b3b70ef13b) | Jun 14, 2023 |
| Toshiba       | PORTEGE X30-D               | [9f26d41d53](https://linux-hardware.org/?probe=9f26d41d53) | Jun 14, 2023 |
| Samsung       | 670Z5E                      | [20f84530c7](https://linux-hardware.org/?probe=20f84530c7) | Jun 14, 2023 |
| Acer          | Nitro AN517-54              | [d0187875be](https://linux-hardware.org/?probe=d0187875be) | Jun 13, 2023 |
| Dell          | Vostro 3420                 | [1ede32fb28](https://linux-hardware.org/?probe=1ede32fb28) | Jun 13, 2023 |
| Dell          | Inspiron 13-7359            | [3ddafcad45](https://linux-hardware.org/?probe=3ddafcad45) | Jun 13, 2023 |
| Alienware     | m15 R7                      | [c4a2634a83](https://linux-hardware.org/?probe=c4a2634a83) | Jun 13, 2023 |
| Alienware     | m15 R7                      | [7b53840b8b](https://linux-hardware.org/?probe=7b53840b8b) | Jun 13, 2023 |
| Apple         | MacBookPro5,5               | [b303846ade](https://linux-hardware.org/?probe=b303846ade) | Jun 13, 2023 |
| Toshiba       | Satellite P755              | [3b0c830987](https://linux-hardware.org/?probe=3b0c830987) | Jun 13, 2023 |
| Dell          | Latitude E7250              | [cc9fc2bace](https://linux-hardware.org/?probe=cc9fc2bace) | Jun 13, 2023 |
| Dell          | 500                         | [b220c5553e](https://linux-hardware.org/?probe=b220c5553e) | Jun 12, 2023 |
| MSI           | Stealth 15M B12UE           | [aabb8192ee](https://linux-hardware.org/?probe=aabb8192ee) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | [b31d9c8e55](https://linux-hardware.org/?probe=b31d9c8e55) | Jun 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | [235239b42b](https://linux-hardware.org/?probe=235239b42b) | Jun 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [d2c4574d58](https://linux-hardware.org/?probe=d2c4574d58) | Jun 11, 2023 |
| ASUSTek       | G750JM                      | [da1f33a87b](https://linux-hardware.org/?probe=da1f33a87b) | Jun 11, 2023 |
| Dell          | Latitude 7480               | [03b8f5a162](https://linux-hardware.org/?probe=03b8f5a162) | Jun 11, 2023 |
| Dell          | Precision 5570              | [32975fdf08](https://linux-hardware.org/?probe=32975fdf08) | Jun 11, 2023 |
| ASUSTek       | GX501VIK                    | [e54a895262](https://linux-hardware.org/?probe=e54a895262) | Jun 11, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | [3d3375df75](https://linux-hardware.org/?probe=3d3375df75) | Jun 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [65a47406b0](https://linux-hardware.org/?probe=65a47406b0) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0XV0... | [b2f7d876c7](https://linux-hardware.org/?probe=b2f7d876c7) | Jun 10, 2023 |
| MSI           | Prestige 13Evo A13M         | [3feb3bce01](https://linux-hardware.org/?probe=3feb3bce01) | Jun 10, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [4b6aa9a912](https://linux-hardware.org/?probe=4b6aa9a912) | Jun 10, 2023 |
| Dell          | Latitude E5500              | [41ad12c465](https://linux-hardware.org/?probe=41ad12c465) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [246facab73](https://linux-hardware.org/?probe=246facab73) | Jun 10, 2023 |
| Sony          | VPCF120FD                   | [47f02bd498](https://linux-hardware.org/?probe=47f02bd498) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [233dac6c68](https://linux-hardware.org/?probe=233dac6c68) | Jun 09, 2023 |
| Dell          | XPS 9320                    | [c9f26e18c2](https://linux-hardware.org/?probe=c9f26e18c2) | Jun 09, 2023 |
| Dell          | Inspiron 15-5568            | [19b686b7d7](https://linux-hardware.org/?probe=19b686b7d7) | Jun 09, 2023 |
| HP            | Laptop 15s-fq2xxx           | [09ba95bf3b](https://linux-hardware.org/?probe=09ba95bf3b) | Jun 08, 2023 |
| ASUSTek       | X455LA                      | [583596672d](https://linux-hardware.org/?probe=583596672d) | Jun 08, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [8fa2e2acc9](https://linux-hardware.org/?probe=8fa2e2acc9) | Jun 08, 2023 |
| Dell          | Inspiron 5379               | [b161b2177a](https://linux-hardware.org/?probe=b161b2177a) | Jun 08, 2023 |
| Gigabyte      | P2542                       | [12a2415432](https://linux-hardware.org/?probe=12a2415432) | Jun 08, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ea8584cbda](https://linux-hardware.org/?probe=ea8584cbda) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | [76ca69b8cc](https://linux-hardware.org/?probe=76ca69b8cc) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | [3932ac5190](https://linux-hardware.org/?probe=3932ac5190) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | [ff2ebbb0ae](https://linux-hardware.org/?probe=ff2ebbb0ae) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [265c19be27](https://linux-hardware.org/?probe=265c19be27) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [b0435761df](https://linux-hardware.org/?probe=b0435761df) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [a76212cc40](https://linux-hardware.org/?probe=a76212cc40) | Jun 07, 2023 |
| HP            | Laptop 15s-fq2xxx           | [9d0aa12b81](https://linux-hardware.org/?probe=9d0aa12b81) | Jun 06, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e56988bf8e](https://linux-hardware.org/?probe=e56988bf8e) | Jun 06, 2023 |
| Dell          | Latitude 7480               | [61c800a3b4](https://linux-hardware.org/?probe=61c800a3b4) | Jun 06, 2023 |
| Notebook      | P65xHP                      | [bf35e218d7](https://linux-hardware.org/?probe=bf35e218d7) | Jun 06, 2023 |
| Toshiba       | PORTEGE X30-D               | [262ee566e1](https://linux-hardware.org/?probe=262ee566e1) | Jun 06, 2023 |
| HP            | EliteBook 840 G6            | [0763f751ac](https://linux-hardware.org/?probe=0763f751ac) | Jun 05, 2023 |
| Notebook      | P65xHP                      | [51834b893c](https://linux-hardware.org/?probe=51834b893c) | Jun 05, 2023 |
| Toshiba       | Satellite Pro C70-B         | [d4bc6d6c8c](https://linux-hardware.org/?probe=d4bc6d6c8c) | Jun 04, 2023 |
| Sony          | VPCEH2H4E                   | [793e883d0c](https://linux-hardware.org/?probe=793e883d0c) | Jun 04, 2023 |
| Dell          | Inspiron 3442               | [5c1f2cc0d3](https://linux-hardware.org/?probe=5c1f2cc0d3) | Jun 04, 2023 |
| Acer          | Swift SF314-43              | [969354604a](https://linux-hardware.org/?probe=969354604a) | Jun 04, 2023 |
| Dell          | Latitude E5520              | [7e2d1fdd22](https://linux-hardware.org/?probe=7e2d1fdd22) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | [f39742476c](https://linux-hardware.org/?probe=f39742476c) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | [efa49bf468](https://linux-hardware.org/?probe=efa49bf468) | Jun 04, 2023 |
| Dell          | Latitude E5510              | [353a2174af](https://linux-hardware.org/?probe=353a2174af) | Jun 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [6d8d7f6384](https://linux-hardware.org/?probe=6d8d7f6384) | Jun 04, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [4f62d33d84](https://linux-hardware.org/?probe=4f62d33d84) | Jun 04, 2023 |
| ASUSTek       | K52Je                       | [0190eef08c](https://linux-hardware.org/?probe=0190eef08c) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [069b512b91](https://linux-hardware.org/?probe=069b512b91) | Jun 03, 2023 |
| Lenovo        | ThinkPad T420 4236WQD       | [69a63f31e1](https://linux-hardware.org/?probe=69a63f31e1) | Jun 03, 2023 |
| HP            | ENVY 17                     | [79fd438f05](https://linux-hardware.org/?probe=79fd438f05) | Jun 03, 2023 |
| Dell          | Latitude 5491               | [6a8a7e6188](https://linux-hardware.org/?probe=6a8a7e6188) | Jun 03, 2023 |
| Acer          | Aspire 7750G                | [160d4525c6](https://linux-hardware.org/?probe=160d4525c6) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [fa4bd41f4b](https://linux-hardware.org/?probe=fa4bd41f4b) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [959b76650d](https://linux-hardware.org/?probe=959b76650d) | Jun 02, 2023 |
| Acer          | Aspire ES1-523              | [a080a07f52](https://linux-hardware.org/?probe=a080a07f52) | Jun 02, 2023 |
| Acer          | Aspire 7750G                | [e94cab5008](https://linux-hardware.org/?probe=e94cab5008) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1aea71b6c0](https://linux-hardware.org/?probe=1aea71b6c0) | Jun 02, 2023 |
| Unknown       | Unknown                     | [655398fc94](https://linux-hardware.org/?probe=655398fc94) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1bdb74a8ba](https://linux-hardware.org/?probe=1bdb74a8ba) | Jun 02, 2023 |
| HP            | ProBook 6450b               | [d3d4e45f9d](https://linux-hardware.org/?probe=d3d4e45f9d) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [f66667b7fb](https://linux-hardware.org/?probe=f66667b7fb) | Jun 01, 2023 |
| Dell          | XPS 15 9570                 | [6d7803788d](https://linux-hardware.org/?probe=6d7803788d) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | [8a69d6c123](https://linux-hardware.org/?probe=8a69d6c123) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | [ecfe7565f4](https://linux-hardware.org/?probe=ecfe7565f4) | Jun 01, 2023 |
| HP            | EliteBook 2560p             | [e822eb4072](https://linux-hardware.org/?probe=e822eb4072) | Jun 01, 2023 |
| ASUSTek       | K53SK                       | [9b376cdd45](https://linux-hardware.org/?probe=9b376cdd45) | Jun 01, 2023 |
| HP            | Pavilion Notebook           | [3fb05bfb0b](https://linux-hardware.org/?probe=3fb05bfb0b) | May 31, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [560680687c](https://linux-hardware.org/?probe=560680687c) | May 31, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | [239faf8c55](https://linux-hardware.org/?probe=239faf8c55) | May 31, 2023 |
| HONOR         | BBR-WAX9                    | [8630cfad52](https://linux-hardware.org/?probe=8630cfad52) | May 31, 2023 |
| Acer          | Nitro AN515-54              | [7c031081c5](https://linux-hardware.org/?probe=7c031081c5) | May 31, 2023 |
| Acer          | Swift SF314-512             | [a8c97baf10](https://linux-hardware.org/?probe=a8c97baf10) | May 31, 2023 |
| ASUSTek       | ROG Strix G513RS_G513RS     | [69b1782cce](https://linux-hardware.org/?probe=69b1782cce) | May 31, 2023 |
| ASUSTek       | K53SK                       | [bfd926c8da](https://linux-hardware.org/?probe=bfd926c8da) | May 30, 2023 |
| VALE          | Notebook Classic C140       | [cdc6168586](https://linux-hardware.org/?probe=cdc6168586) | May 30, 2023 |
| Gigabyte      | P2542                       | [b1064cae7a](https://linux-hardware.org/?probe=b1064cae7a) | May 30, 2023 |
| Dell          | Inspiron 15-3567            | [e51e0ef0da](https://linux-hardware.org/?probe=e51e0ef0da) | May 30, 2023 |
| Gigabyte      | P2542                       | [7cded000f2](https://linux-hardware.org/?probe=7cded000f2) | May 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [8002face48](https://linux-hardware.org/?probe=8002face48) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cddd43859b](https://linux-hardware.org/?probe=cddd43859b) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [46f455ce35](https://linux-hardware.org/?probe=46f455ce35) | May 30, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [1e0fbe86da](https://linux-hardware.org/?probe=1e0fbe86da) | May 29, 2023 |
| Alienware     | x15 R1                      | [19e9b8e338](https://linux-hardware.org/?probe=19e9b8e338) | May 29, 2023 |
| HONOR         | BBR-WAX9                    | [e57b9850f8](https://linux-hardware.org/?probe=e57b9850f8) | May 28, 2023 |
| ALLDOCUBE     | i1405C                      | [7e4475ef13](https://linux-hardware.org/?probe=7e4475ef13) | May 28, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c2408a1885](https://linux-hardware.org/?probe=c2408a1885) | May 28, 2023 |
| Apple         | MacBookPro10,2              | [34d96aa1df](https://linux-hardware.org/?probe=34d96aa1df) | May 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [c7afdbbd76](https://linux-hardware.org/?probe=c7afdbbd76) | May 28, 2023 |
| AVITA         | NE14A2                      | [89c5edafbc](https://linux-hardware.org/?probe=89c5edafbc) | May 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | [618a907425](https://linux-hardware.org/?probe=618a907425) | May 27, 2023 |
| Dell          | Vostro 15 3515              | [2fadb86df4](https://linux-hardware.org/?probe=2fadb86df4) | May 27, 2023 |
| Dell          | Latitude 5440               | [9ed4f0e7ac](https://linux-hardware.org/?probe=9ed4f0e7ac) | May 27, 2023 |
| Dell          | Latitude 5480               | [c7566d1ab9](https://linux-hardware.org/?probe=c7566d1ab9) | May 27, 2023 |
| Dell          | Latitude 5480               | [5327e82af6](https://linux-hardware.org/?probe=5327e82af6) | May 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [57b9304725](https://linux-hardware.org/?probe=57b9304725) | May 27, 2023 |
| Acer          | Aspire A315-22              | [18a13174aa](https://linux-hardware.org/?probe=18a13174aa) | May 27, 2023 |
| Dell          | Latitude 7480               | [2c74ec8198](https://linux-hardware.org/?probe=2c74ec8198) | May 27, 2023 |
| Toshiba       | Satellite Pro C70-B         | [3058a75499](https://linux-hardware.org/?probe=3058a75499) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [433b367e58](https://linux-hardware.org/?probe=433b367e58) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [ac85063e46](https://linux-hardware.org/?probe=ac85063e46) | May 26, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [b8bb801b93](https://linux-hardware.org/?probe=b8bb801b93) | May 26, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [a8c4cf6158](https://linux-hardware.org/?probe=a8c4cf6158) | May 26, 2023 |
| Acer          | Predator PT316-51s          | [0242988287](https://linux-hardware.org/?probe=0242988287) | May 26, 2023 |
| HP            | ENVY Laptop 13-ah0503na     | [cdf2d7b4b4](https://linux-hardware.org/?probe=cdf2d7b4b4) | May 25, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [0316f8d274](https://linux-hardware.org/?probe=0316f8d274) | May 25, 2023 |
| Lenovo        | ThinkPad T580 20LAS62M07    | [48ad025649](https://linux-hardware.org/?probe=48ad025649) | May 25, 2023 |
| Google        | Akali 360                   | [2a4bbc5d81](https://linux-hardware.org/?probe=2a4bbc5d81) | May 25, 2023 |
| Acer          | Aspire A715-51G             | [53cbfa6255](https://linux-hardware.org/?probe=53cbfa6255) | May 25, 2023 |
| Toshiba       | Satellite Pro C650          | [50fc04b16c](https://linux-hardware.org/?probe=50fc04b16c) | May 25, 2023 |
| Mediacom      | SMARTBOOK ONE               | [ad010a6b3e](https://linux-hardware.org/?probe=ad010a6b3e) | May 25, 2023 |
| HP            | ZBook Studio G3             | [a7274d19af](https://linux-hardware.org/?probe=a7274d19af) | May 24, 2023 |
| Dell          | Latitude 7390               | [999bb94a31](https://linux-hardware.org/?probe=999bb94a31) | May 24, 2023 |
| HUAWEI        | BOD-WXX9                    | [9486b7ca4f](https://linux-hardware.org/?probe=9486b7ca4f) | May 24, 2023 |
| HP            | Laptop 15s-fq4xxx           | [810c2ac411](https://linux-hardware.org/?probe=810c2ac411) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [4c512786cc](https://linux-hardware.org/?probe=4c512786cc) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [da0b980bc3](https://linux-hardware.org/?probe=da0b980bc3) | May 24, 2023 |
| Allview       | Allbook H                   | [8b0c0a3436](https://linux-hardware.org/?probe=8b0c0a3436) | May 24, 2023 |
| Dell          | Precision 3571              | [3806fcdb9c](https://linux-hardware.org/?probe=3806fcdb9c) | May 24, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | [306ecade71](https://linux-hardware.org/?probe=306ecade71) | May 24, 2023 |
| Dell          | Inspiron 5720               | [c9eaabeb95](https://linux-hardware.org/?probe=c9eaabeb95) | May 24, 2023 |
| HP            | Pavilion dv5                | [2906e3ff3b](https://linux-hardware.org/?probe=2906e3ff3b) | May 24, 2023 |
| HP            | 15                          | [b62229cac1](https://linux-hardware.org/?probe=b62229cac1) | May 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | [4c3c861f80](https://linux-hardware.org/?probe=4c3c861f80) | May 23, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [77f092da32](https://linux-hardware.org/?probe=77f092da32) | May 23, 2023 |
| Dell          | Inspiron 1525               | [a92437f5aa](https://linux-hardware.org/?probe=a92437f5aa) | May 23, 2023 |
| ASUSTek       | X751MA                      | [674b64f381](https://linux-hardware.org/?probe=674b64f381) | May 23, 2023 |
| HP            | Laptop 14s-fq1xxx           | [73d0ff64b6](https://linux-hardware.org/?probe=73d0ff64b6) | May 23, 2023 |
| Acer          | Aspire E5-553               | [3740264eb0](https://linux-hardware.org/?probe=3740264eb0) | May 23, 2023 |
| HP            | 250 G6 Notebook PC          | [431f2db1fc](https://linux-hardware.org/?probe=431f2db1fc) | May 23, 2023 |
| HP            | Laptop 14-dq2xxx            | [fe7d1e1f90](https://linux-hardware.org/?probe=fe7d1e1f90) | May 22, 2023 |
| Dell          | Inspiron 1525               | [2afda2396c](https://linux-hardware.org/?probe=2afda2396c) | May 22, 2023 |
| Acer          | Nitro AN515-46              | [702a597b36](https://linux-hardware.org/?probe=702a597b36) | May 22, 2023 |
| Acer          | Swift SF514-56T             | [81a0e002b7](https://linux-hardware.org/?probe=81a0e002b7) | May 22, 2023 |
| Dell          | Latitude 3420               | [d598f2634f](https://linux-hardware.org/?probe=d598f2634f) | May 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS1GQ00    | [1ea9bac322](https://linux-hardware.org/?probe=1ea9bac322) | May 22, 2023 |
| MSI           | Stealth 15M B12UE           | [4051f4b27d](https://linux-hardware.org/?probe=4051f4b27d) | May 22, 2023 |
| HUAWEI        | NBM-WXX9                    | [e3ea42dd02](https://linux-hardware.org/?probe=e3ea42dd02) | May 22, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [55a289b426](https://linux-hardware.org/?probe=55a289b426) | May 21, 2023 |
| Apple         | MacBookPro14,2              | [d29f7a36f9](https://linux-hardware.org/?probe=d29f7a36f9) | May 21, 2023 |
| Dell          | Latitude E6530              | [7c04efc558](https://linux-hardware.org/?probe=7c04efc558) | May 21, 2023 |
| Dell          | Inspiron 3542               | [166b73ef05](https://linux-hardware.org/?probe=166b73ef05) | May 20, 2023 |
| HP            | Pavilion dv6                | [17ac43247a](https://linux-hardware.org/?probe=17ac43247a) | May 20, 2023 |
| Unknown       | Unknown                     | [c7157cc723](https://linux-hardware.org/?probe=c7157cc723) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [de162ff16c](https://linux-hardware.org/?probe=de162ff16c) | May 20, 2023 |
| Acer          | Nitro AN517-54              | [105fb43fc1](https://linux-hardware.org/?probe=105fb43fc1) | May 20, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [42ab4c7e67](https://linux-hardware.org/?probe=42ab4c7e67) | May 20, 2023 |
| MSI           | VR601                       | [7f9381407d](https://linux-hardware.org/?probe=7f9381407d) | May 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5bac34a5f5](https://linux-hardware.org/?probe=5bac34a5f5) | May 19, 2023 |
| Dell          | Inspiron 3442               | [a8bb37c78e](https://linux-hardware.org/?probe=a8bb37c78e) | May 19, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [9475bc847b](https://linux-hardware.org/?probe=9475bc847b) | May 19, 2023 |
| HP            | Pavilion dv6                | [4fb1281981](https://linux-hardware.org/?probe=4fb1281981) | May 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [7af74c5864](https://linux-hardware.org/?probe=7af74c5864) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [161776168b](https://linux-hardware.org/?probe=161776168b) | May 18, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [e17fc662cc](https://linux-hardware.org/?probe=e17fc662cc) | May 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [b5d454d4ec](https://linux-hardware.org/?probe=b5d454d4ec) | May 18, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | [d1569df0f6](https://linux-hardware.org/?probe=d1569df0f6) | May 18, 2023 |
| HP            | Laptop 14-dq0xxx            | [1923d74fbc](https://linux-hardware.org/?probe=1923d74fbc) | May 18, 2023 |
| Dell          | Precision 5570              | [c9e52e6e8c](https://linux-hardware.org/?probe=c9e52e6e8c) | May 18, 2023 |
| MSI           | GF63 Thin 11SC              | [89e05e4477](https://linux-hardware.org/?probe=89e05e4477) | May 17, 2023 |
| Dell          | Latitude E6530              | [e6064ac95c](https://linux-hardware.org/?probe=e6064ac95c) | May 17, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | [58b895e713](https://linux-hardware.org/?probe=58b895e713) | May 16, 2023 |
| Toshiba       | IS 1413G                    | [df01be5efd](https://linux-hardware.org/?probe=df01be5efd) | May 16, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ba609eb1e6](https://linux-hardware.org/?probe=ba609eb1e6) | May 15, 2023 |
| VALE          | Notebook Classic C140       | [656e811dfb](https://linux-hardware.org/?probe=656e811dfb) | May 14, 2023 |
| Acer          | Aspire A717-72G             | [1ab0673015](https://linux-hardware.org/?probe=1ab0673015) | May 14, 2023 |
| Acer          | Aspire A717-72G             | [62a46acc18](https://linux-hardware.org/?probe=62a46acc18) | May 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [b08b887e1a](https://linux-hardware.org/?probe=b08b887e1a) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [020d4612bd](https://linux-hardware.org/?probe=020d4612bd) | May 14, 2023 |
| HP            | Notebook                    | [decd46d3ed](https://linux-hardware.org/?probe=decd46d3ed) | May 14, 2023 |
| HP            | Laptop 14-dq2xxx            | [274fbdb43e](https://linux-hardware.org/?probe=274fbdb43e) | May 14, 2023 |
| Toshiba       | IS 1413G                    | [821d79dc3f](https://linux-hardware.org/?probe=821d79dc3f) | May 14, 2023 |
| MSI           | GS75 Stealth 10SFS          | [a2116b61ea](https://linux-hardware.org/?probe=a2116b61ea) | May 14, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [803f9dba3c](https://linux-hardware.org/?probe=803f9dba3c) | May 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [09eb36df64](https://linux-hardware.org/?probe=09eb36df64) | May 13, 2023 |
| Dell          | Inspiron 7520               | [d06731c12e](https://linux-hardware.org/?probe=d06731c12e) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5768cd981e](https://linux-hardware.org/?probe=5768cd981e) | May 13, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [66bff684b7](https://linux-hardware.org/?probe=66bff684b7) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | [14eae60f4f](https://linux-hardware.org/?probe=14eae60f4f) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | [7ac717a41d](https://linux-hardware.org/?probe=7ac717a41d) | May 13, 2023 |
| Samsung       | 960XFH                      | [6d6b4a9c5e](https://linux-hardware.org/?probe=6d6b4a9c5e) | May 12, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | [795e44d159](https://linux-hardware.org/?probe=795e44d159) | May 12, 2023 |
| ASUSTek       | X555LJ                      | [f39ba53533](https://linux-hardware.org/?probe=f39ba53533) | May 12, 2023 |
| HP            | Stream Notebook             | [5ed3be74da](https://linux-hardware.org/?probe=5ed3be74da) | May 12, 2023 |
| Apple         | MacBookPro11,2              | [ceea346358](https://linux-hardware.org/?probe=ceea346358) | May 12, 2023 |
| Apple         | MacBookPro11,4              | [576d66cba7](https://linux-hardware.org/?probe=576d66cba7) | May 12, 2023 |
| Unknown       | Unknown                     | [8375f52559](https://linux-hardware.org/?probe=8375f52559) | May 12, 2023 |
| HP            | EliteBook 840 G6            | [80158c51fb](https://linux-hardware.org/?probe=80158c51fb) | May 12, 2023 |
| Dell          | Vostro 3500                 | [81f86e6678](https://linux-hardware.org/?probe=81f86e6678) | May 11, 2023 |
| Rombica       | myBook Zenith               | [f7438f1448](https://linux-hardware.org/?probe=f7438f1448) | May 11, 2023 |
| Apple         | MacBookPro9,2               | [ecb43775d1](https://linux-hardware.org/?probe=ecb43775d1) | May 11, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [f9c1eb381f](https://linux-hardware.org/?probe=f9c1eb381f) | May 11, 2023 |
| Unknown       | Unknown                     | [3fbabd3df0](https://linux-hardware.org/?probe=3fbabd3df0) | May 11, 2023 |
| Dell          | Latitude 5490               | [2cba18ddec](https://linux-hardware.org/?probe=2cba18ddec) | May 11, 2023 |
| Lenovo        | Yoga 7 14IRL8 82YL          | [ae2fd3b0ae](https://linux-hardware.org/?probe=ae2fd3b0ae) | May 11, 2023 |
| MSI           | Stealth 14Studio A13VE      | [86f43bbff1](https://linux-hardware.org/?probe=86f43bbff1) | May 10, 2023 |
| Acer          | Aspire 3935                 | [39cbd19b39](https://linux-hardware.org/?probe=39cbd19b39) | May 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [2e58ce6bd7](https://linux-hardware.org/?probe=2e58ce6bd7) | May 10, 2023 |
| Unknown       | Unknown                     | [87e3ae6f24](https://linux-hardware.org/?probe=87e3ae6f24) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [727163d7b9](https://linux-hardware.org/?probe=727163d7b9) | May 09, 2023 |
| Dell          | XPS 13 9380                 | [af31929040](https://linux-hardware.org/?probe=af31929040) | May 09, 2023 |
| Medion        | E6234                       | [6c3bd7d77f](https://linux-hardware.org/?probe=6c3bd7d77f) | May 08, 2023 |
| Toshiba       | Satellite L650              | [ba32d27df1](https://linux-hardware.org/?probe=ba32d27df1) | May 08, 2023 |
| HP            | 625                         | [956346de67](https://linux-hardware.org/?probe=956346de67) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0628913a60](https://linux-hardware.org/?probe=0628913a60) | May 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | [db609197b4](https://linux-hardware.org/?probe=db609197b4) | May 08, 2023 |
| Acer          | Swift SFA16-41              | [7934eebd9b](https://linux-hardware.org/?probe=7934eebd9b) | May 08, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f23fb5cca0](https://linux-hardware.org/?probe=f23fb5cca0) | May 08, 2023 |
| HP            | Meep                        | [4b99a0c5f8](https://linux-hardware.org/?probe=4b99a0c5f8) | May 08, 2023 |
| Apple         | MacBookPro9,2               | [a8d45ac430](https://linux-hardware.org/?probe=a8d45ac430) | May 07, 2023 |
| Toshiba       | IS 1413G                    | [c437a16a33](https://linux-hardware.org/?probe=c437a16a33) | May 07, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [a312f0545f](https://linux-hardware.org/?probe=a312f0545f) | May 07, 2023 |
| HP            | EliteBook 850 G3            | [9a068c66d5](https://linux-hardware.org/?probe=9a068c66d5) | May 07, 2023 |
| Medion        | E6234                       | [5afe99ed93](https://linux-hardware.org/?probe=5afe99ed93) | May 07, 2023 |
| HP            | Meep                        | [46a81f105c](https://linux-hardware.org/?probe=46a81f105c) | May 07, 2023 |
| Dell          | XPS 13 9380                 | [b4e9bb9147](https://linux-hardware.org/?probe=b4e9bb9147) | May 07, 2023 |
| ASUSTek       | X555LJ                      | [febe8d60fc](https://linux-hardware.org/?probe=febe8d60fc) | May 07, 2023 |
| ASUSTek       | X555LJ                      | [2e25cad4b3](https://linux-hardware.org/?probe=2e25cad4b3) | May 07, 2023 |
| Razer         | Blade                       | [d90bda8f52](https://linux-hardware.org/?probe=d90bda8f52) | May 07, 2023 |
| Dell          | Latitude 5290               | [255da608b8](https://linux-hardware.org/?probe=255da608b8) | May 07, 2023 |
| Dell          | XPS 13 9343                 | [5e91733408](https://linux-hardware.org/?probe=5e91733408) | May 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [9355511511](https://linux-hardware.org/?probe=9355511511) | May 07, 2023 |
| Dell          | Inspiron 5521               | [d5f70fc2eb](https://linux-hardware.org/?probe=d5f70fc2eb) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [50b503ae3e](https://linux-hardware.org/?probe=50b503ae3e) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [64bbfa416b](https://linux-hardware.org/?probe=64bbfa416b) | May 07, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [abc9ce4fa4](https://linux-hardware.org/?probe=abc9ce4fa4) | May 06, 2023 |
| Dell          | Latitude E6410              | [535fd92f64](https://linux-hardware.org/?probe=535fd92f64) | May 06, 2023 |
| Dell          | Latitude E4200              | [af2baa1787](https://linux-hardware.org/?probe=af2baa1787) | May 06, 2023 |
| Acer          | Aspire 5810T                | [d4b401ef3f](https://linux-hardware.org/?probe=d4b401ef3f) | May 06, 2023 |
| Dell          | Vostro 3360                 | [13a1e30b53](https://linux-hardware.org/?probe=13a1e30b53) | May 06, 2023 |
| Dell          | Precision 7740              | [4cd3b0701e](https://linux-hardware.org/?probe=4cd3b0701e) | May 06, 2023 |
| Acer          | Aspire 5810T                | [ecdd99c704](https://linux-hardware.org/?probe=ecdd99c704) | May 05, 2023 |
| HP            | Pavilion g6                 | [9e469df99e](https://linux-hardware.org/?probe=9e469df99e) | May 05, 2023 |
| Toshiba       | PORTEGE Z30t-A              | [18cc14eee0](https://linux-hardware.org/?probe=18cc14eee0) | May 05, 2023 |
| Shanghai Z... | ZXE CRB                     | [d63ef842c1](https://linux-hardware.org/?probe=d63ef842c1) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b9cfd37540](https://linux-hardware.org/?probe=b9cfd37540) | May 05, 2023 |
| Google        | Meep                        | [1e5e0e6673](https://linux-hardware.org/?probe=1e5e0e6673) | May 04, 2023 |
| Dell          | XPS 13 9300                 | [8864ce10e7](https://linux-hardware.org/?probe=8864ce10e7) | May 03, 2023 |
| Dell          | XPS 13 9300                 | [8ef1ddf82a](https://linux-hardware.org/?probe=8ef1ddf82a) | May 03, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | [bb924b0c19](https://linux-hardware.org/?probe=bb924b0c19) | May 03, 2023 |
| MSI           | Katana GF66 12UE            | [799a951714](https://linux-hardware.org/?probe=799a951714) | May 03, 2023 |
| Lenovo        | G500s 20245                 | [560b69d616](https://linux-hardware.org/?probe=560b69d616) | May 03, 2023 |
| Toshiba       | IS 1413G                    | [81a4d2ac8b](https://linux-hardware.org/?probe=81a4d2ac8b) | May 03, 2023 |
| Acer          | Aspire E1-571               | [46ecc78df6](https://linux-hardware.org/?probe=46ecc78df6) | May 02, 2023 |
| HP            | EliteBook Folio G1          | [a31ef5e00e](https://linux-hardware.org/?probe=a31ef5e00e) | May 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5101f4e19d](https://linux-hardware.org/?probe=5101f4e19d) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [000c0450b9](https://linux-hardware.org/?probe=000c0450b9) | May 02, 2023 |
| HP            | Notebook                    | [749fa6a38e](https://linux-hardware.org/?probe=749fa6a38e) | May 02, 2023 |
| Acer          | Nitro AN515-44              | [e26aee893f](https://linux-hardware.org/?probe=e26aee893f) | May 01, 2023 |
| HUAWEI        | BOHB-WAX9                   | [3a9a2590e3](https://linux-hardware.org/?probe=3a9a2590e3) | May 01, 2023 |
| HP            | ProBook 430 G4              | [3c422c5e96](https://linux-hardware.org/?probe=3c422c5e96) | May 01, 2023 |
| Acer          | Aspire E1-571               | [7b4e78233a](https://linux-hardware.org/?probe=7b4e78233a) | May 01, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3be920565f](https://linux-hardware.org/?probe=3be920565f) | May 01, 2023 |
| Medion        | E16402                      | [cff2f785ad](https://linux-hardware.org/?probe=cff2f785ad) | May 01, 2023 |
| Dell          | Latitude E6400              | [33b7764234](https://linux-hardware.org/?probe=33b7764234) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5002NAU    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| HP            | EliteBook 840 G3            | [c490c44357](https://linux-hardware.org/?probe=c490c44357) | May 01, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [4bec088d90](https://linux-hardware.org/?probe=4bec088d90) | Apr 30, 2023 |
| Dell          | XPS 15 9500                 | [93fef964a7](https://linux-hardware.org/?probe=93fef964a7) | Apr 30, 2023 |
| Samsung       | 950XED                      | [41f620de17](https://linux-hardware.org/?probe=41f620de17) | Apr 30, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [1714bffa0e](https://linux-hardware.org/?probe=1714bffa0e) | Apr 30, 2023 |
| Acer          | Peppy                       | [4caf11594a](https://linux-hardware.org/?probe=4caf11594a) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [da5f050510](https://linux-hardware.org/?probe=da5f050510) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [1e65b46a12](https://linux-hardware.org/?probe=1e65b46a12) | Apr 29, 2023 |
| ASUSTek       | X751MA                      | [c952010dbb](https://linux-hardware.org/?probe=c952010dbb) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | [6a102a2c37](https://linux-hardware.org/?probe=6a102a2c37) | Apr 29, 2023 |
| Dell          | Inspiron N5110              | [04da6f1db9](https://linux-hardware.org/?probe=04da6f1db9) | Apr 29, 2023 |
| MSI           | Modern 14 A10M              | [22ad1f6bfb](https://linux-hardware.org/?probe=22ad1f6bfb) | Apr 29, 2023 |
| Acer          | Aspire E5-553               | [ff448e32c3](https://linux-hardware.org/?probe=ff448e32c3) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| Samsung       | 930X2K/931X2K               | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | [004e0007e4](https://linux-hardware.org/?probe=004e0007e4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | [3f6a89023c](https://linux-hardware.org/?probe=3f6a89023c) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [216a4b9b67](https://linux-hardware.org/?probe=216a4b9b67) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [6736f3d911](https://linux-hardware.org/?probe=6736f3d911) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [a808e47839](https://linux-hardware.org/?probe=a808e47839) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [67ae1efc54](https://linux-hardware.org/?probe=67ae1efc54) | Apr 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | [b1e6130b77](https://linux-hardware.org/?probe=b1e6130b77) | Apr 28, 2023 |
| Acer          | Swift SF314-512             | [2ba1bab0fe](https://linux-hardware.org/?probe=2ba1bab0fe) | Apr 28, 2023 |
| MSI           | Katana GF66 12UGS           | [3607ee704e](https://linux-hardware.org/?probe=3607ee704e) | Apr 28, 2023 |
| Dell          | XPS 15 9570                 | [3479673283](https://linux-hardware.org/?probe=3479673283) | Apr 28, 2023 |
| Acer          | ConceptD CN315-71P          | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Dell          | Latitude E5470              | [caac023f65](https://linux-hardware.org/?probe=caac023f65) | Apr 27, 2023 |
| Valve         | Jupiter                     | [f65ece2859](https://linux-hardware.org/?probe=f65ece2859) | Apr 27, 2023 |
| ASUSTek       | X751MA                      | [eb9967626a](https://linux-hardware.org/?probe=eb9967626a) | Apr 27, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [404ec697ac](https://linux-hardware.org/?probe=404ec697ac) | Apr 27, 2023 |
| Dell          | Inspiron 5567               | [012329ee1f](https://linux-hardware.org/?probe=012329ee1f) | Apr 27, 2023 |
| MSI           | PE60 6QE                    | [1a5ae975ee](https://linux-hardware.org/?probe=1a5ae975ee) | Apr 27, 2023 |
| Acer          | Aspire 5742G                | [a1391b4372](https://linux-hardware.org/?probe=a1391b4372) | Apr 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [f0a2365878](https://linux-hardware.org/?probe=f0a2365878) | Apr 27, 2023 |
| Dell          | Inspiron 5558               | [9f3b8c952d](https://linux-hardware.org/?probe=9f3b8c952d) | Apr 27, 2023 |
| Acer          | Aspire E1-571               | [c95605ef8e](https://linux-hardware.org/?probe=c95605ef8e) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [d49ace71b4](https://linux-hardware.org/?probe=d49ace71b4) | Apr 27, 2023 |
| Dell          | Latitude 5520               | [bec614b168](https://linux-hardware.org/?probe=bec614b168) | Apr 26, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [7ca1ebbe7f](https://linux-hardware.org/?probe=7ca1ebbe7f) | Apr 26, 2023 |
| Dell          | Latitude 7420               | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| ASUSTek       | X541SA                      | [362ede5435](https://linux-hardware.org/?probe=362ede5435) | Apr 26, 2023 |
| Acer          | Swift SF313-53              | [b487229ea2](https://linux-hardware.org/?probe=b487229ea2) | Apr 25, 2023 |
| MSI           | Modern 14 A10M              | [dc3595e3cc](https://linux-hardware.org/?probe=dc3595e3cc) | Apr 25, 2023 |
| HP            | 240 G8                      | [ab322ed08e](https://linux-hardware.org/?probe=ab322ed08e) | Apr 25, 2023 |
| HP            | 240 G8                      | [8cf9892fe9](https://linux-hardware.org/?probe=8cf9892fe9) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e7b20d71b7](https://linux-hardware.org/?probe=e7b20d71b7) | Apr 25, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [2732f4b096](https://linux-hardware.org/?probe=2732f4b096) | Apr 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [7d3b6ba1a3](https://linux-hardware.org/?probe=7d3b6ba1a3) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [5fb905227b](https://linux-hardware.org/?probe=5fb905227b) | Apr 25, 2023 |
| Dell          | XPS 13 9310                 | [65ccee11a0](https://linux-hardware.org/?probe=65ccee11a0) | Apr 24, 2023 |
| ICL           | RAYbook Si1512              | [4e960cbe90](https://linux-hardware.org/?probe=4e960cbe90) | Apr 24, 2023 |
| ASUSTek       | GL752VW                     | [26c754e5f0](https://linux-hardware.org/?probe=26c754e5f0) | Apr 24, 2023 |
| Dell          | XPS 13 9310                 | [070d7e791f](https://linux-hardware.org/?probe=070d7e791f) | Apr 24, 2023 |
| Acer          | Aspire 5742G                | [84679bc442](https://linux-hardware.org/?probe=84679bc442) | Apr 24, 2023 |
| Lenovo        | ThinkPad A285 20MXS0NJ00    | [f155ad2bf4](https://linux-hardware.org/?probe=f155ad2bf4) | Apr 24, 2023 |
| ASUSTek       | GL752VW                     | [216aaf8fff](https://linux-hardware.org/?probe=216aaf8fff) | Apr 24, 2023 |
| Gateway       | NV55C                       | [3c560a28cf](https://linux-hardware.org/?probe=3c560a28cf) | Apr 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2e7585d261](https://linux-hardware.org/?probe=2e7585d261) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [59c225df6e](https://linux-hardware.org/?probe=59c225df6e) | Apr 24, 2023 |
| Lenovo        | 20RD001FHV                  | [782ded0435](https://linux-hardware.org/?probe=782ded0435) | Apr 24, 2023 |
| Samsung       | 950XED                      | [6226147e11](https://linux-hardware.org/?probe=6226147e11) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [b1c3492700](https://linux-hardware.org/?probe=b1c3492700) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [db8e950d12](https://linux-hardware.org/?probe=db8e950d12) | Apr 24, 2023 |
| Acer          | Aspire A515-47              | [35a591e26a](https://linux-hardware.org/?probe=35a591e26a) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| Shanghai Z... | ZXE CRB                     | [298d51ae78](https://linux-hardware.org/?probe=298d51ae78) | Apr 24, 2023 |
| Dell          | Latitude E5470              | [bc1dca3c78](https://linux-hardware.org/?probe=bc1dca3c78) | Apr 24, 2023 |
| HP            | ZBook 17 G5                 | [c1d71592a4](https://linux-hardware.org/?probe=c1d71592a4) | Apr 24, 2023 |
| Acer          | Aspire A317-53              | [c47ec3530e](https://linux-hardware.org/?probe=c47ec3530e) | Apr 24, 2023 |
| Dell          | G5 5590                     | [eef3722c35](https://linux-hardware.org/?probe=eef3722c35) | Apr 23, 2023 |
| HP            | ZBook 17 G5                 | [ce9fd79431](https://linux-hardware.org/?probe=ce9fd79431) | Apr 23, 2023 |
| Dell          | Precision M4400             | [0c367cbf45](https://linux-hardware.org/?probe=0c367cbf45) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4286A44       | [6b6e909d11](https://linux-hardware.org/?probe=6b6e909d11) | Apr 23, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [641374c815](https://linux-hardware.org/?probe=641374c815) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [aa01246f8b](https://linux-hardware.org/?probe=aa01246f8b) | Apr 23, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [90b7213592](https://linux-hardware.org/?probe=90b7213592) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [620334c0fc](https://linux-hardware.org/?probe=620334c0fc) | Apr 23, 2023 |
| Dell          | Latitude E6420              | [475a16531a](https://linux-hardware.org/?probe=475a16531a) | Apr 22, 2023 |
| Dell          | Precision M4400             | [291a0de9a8](https://linux-hardware.org/?probe=291a0de9a8) | Apr 22, 2023 |
| Acer          | Nitro AN515-58              | [60251e08f5](https://linux-hardware.org/?probe=60251e08f5) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ce5e9aad85](https://linux-hardware.org/?probe=ce5e9aad85) | Apr 22, 2023 |
| Acer          | Aspire 7750G                | [afdab44276](https://linux-hardware.org/?probe=afdab44276) | Apr 22, 2023 |
| Acer          | Aspire 7750G                | [1f6e58080a](https://linux-hardware.org/?probe=1f6e58080a) | Apr 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [0f5a55a8d1](https://linux-hardware.org/?probe=0f5a55a8d1) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | [63cafebe06](https://linux-hardware.org/?probe=63cafebe06) | Apr 21, 2023 |
| ASUSTek       | N53SN                       | [7c0a7d4494](https://linux-hardware.org/?probe=7c0a7d4494) | Apr 21, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [2a5d9adcd4](https://linux-hardware.org/?probe=2a5d9adcd4) | Apr 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [85fa6bf3d5](https://linux-hardware.org/?probe=85fa6bf3d5) | Apr 21, 2023 |
| Dell          | Latitude E6420              | [5e3466ce98](https://linux-hardware.org/?probe=5e3466ce98) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | [d34d10b1ad](https://linux-hardware.org/?probe=d34d10b1ad) | Apr 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [05321d1ddd](https://linux-hardware.org/?probe=05321d1ddd) | Apr 20, 2023 |
| Dell          | Inspiron 3501               | [e09f00bead](https://linux-hardware.org/?probe=e09f00bead) | Apr 20, 2023 |
| HP            | Pavilion g4                 | [96a0210940](https://linux-hardware.org/?probe=96a0210940) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | [b54a612e76](https://linux-hardware.org/?probe=b54a612e76) | Apr 20, 2023 |
| Crusaders ... | CS14D01                     | [b25acea9f7](https://linux-hardware.org/?probe=b25acea9f7) | Apr 19, 2023 |
| Dell          | Vostro 15 7510              | [d9e766f446](https://linux-hardware.org/?probe=d9e766f446) | Apr 16, 2023 |
| HUAWEI        | BOM-WXX9                    | [04eead074d](https://linux-hardware.org/?probe=04eead074d) | Apr 14, 2023 |
| HUAWEI        | HLY-WX9XX                   | [d0742654bb](https://linux-hardware.org/?probe=d0742654bb) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [df35f6916a](https://linux-hardware.org/?probe=df35f6916a) | Apr 14, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | [0c4578a674](https://linux-hardware.org/?probe=0c4578a674) | Apr 14, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [6b481f17c2](https://linux-hardware.org/?probe=6b481f17c2) | Apr 13, 2023 |
| HUAWEI        | BOM-WXX9                    | [c56952417d](https://linux-hardware.org/?probe=c56952417d) | Apr 11, 2023 |
| Toshiba       | IS 1413G                    | [be9d1636a7](https://linux-hardware.org/?probe=be9d1636a7) | Apr 09, 2023 |
| Acer          | Swift SF314-55G             | [e15eaec4c0](https://linux-hardware.org/?probe=e15eaec4c0) | Apr 07, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [29f00590fb](https://linux-hardware.org/?probe=29f00590fb) | Apr 05, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [a1dceb9ce7](https://linux-hardware.org/?probe=a1dceb9ce7) | Apr 04, 2023 |
| Google        | Akemi                       | [14e5c7b93b](https://linux-hardware.org/?probe=14e5c7b93b) | Apr 04, 2023 |
| HUAWEI        | CREM-WXX9                   | [dd3c0ff2e5](https://linux-hardware.org/?probe=dd3c0ff2e5) | Apr 03, 2023 |
| Samsung       | 767XCL                      | [b5a44d9194](https://linux-hardware.org/?probe=b5a44d9194) | Apr 03, 2023 |
| Dell          | Inspiron 5458               | [38b9db2538](https://linux-hardware.org/?probe=38b9db2538) | Apr 01, 2023 |
| Samsung       | 767XCL                      | [a3167908c0](https://linux-hardware.org/?probe=a3167908c0) | Apr 01, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [13e8d4f50b](https://linux-hardware.org/?probe=13e8d4f50b) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b56e2a41ed](https://linux-hardware.org/?probe=b56e2a41ed) | Mar 31, 2023 |
| Shanghai Z... | ZXE CRB                     | [aafbb2815f](https://linux-hardware.org/?probe=aafbb2815f) | Mar 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4f2d3a2402](https://linux-hardware.org/?probe=4f2d3a2402) | Mar 25, 2023 |
| Shanghai Z... | ZXE CRB                     | [7f98044a04](https://linux-hardware.org/?probe=7f98044a04) | Mar 24, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [8c5fde8c1e](https://linux-hardware.org/?probe=8c5fde8c1e) | Mar 22, 2023 |
| Dell          | Latitude 7520               | [09c8e699d3](https://linux-hardware.org/?probe=09c8e699d3) | Mar 16, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [66094e937a](https://linux-hardware.org/?probe=66094e937a) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | [49130084c4](https://linux-hardware.org/?probe=49130084c4) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | [a6091bc2e2](https://linux-hardware.org/?probe=a6091bc2e2) | Mar 11, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [89e2fd827d](https://linux-hardware.org/?probe=89e2fd827d) | Mar 05, 2023 |
| Shanghai Z... | ZXE CRB                     | [bb68a61939](https://linux-hardware.org/?probe=bb68a61939) | Mar 05, 2023 |
| Lenovo        | E51-80 80QB                 | [824ece168f](https://linux-hardware.org/?probe=824ece168f) | Mar 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [525be1bcbe](https://linux-hardware.org/?probe=525be1bcbe) | Mar 02, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [830a8a94e2](https://linux-hardware.org/?probe=830a8a94e2) | Mar 02, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [0bf8c9ca74](https://linux-hardware.org/?probe=0bf8c9ca74) | Mar 02, 2023 |
| Toshiba       | IS 1413G                    | [05ad6c694b](https://linux-hardware.org/?probe=05ad6c694b) | Mar 01, 2023 |
| HP            | Laptop 17-by3xxx            | [5beb40c486](https://linux-hardware.org/?probe=5beb40c486) | Feb 28, 2023 |
| Samsung       | 370E4K                      | [aba5535c2a](https://linux-hardware.org/?probe=aba5535c2a) | Feb 28, 2023 |
| Toshiba       | IS 1413G                    | [c361aabb21](https://linux-hardware.org/?probe=c361aabb21) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | [17338cbd01](https://linux-hardware.org/?probe=17338cbd01) | Feb 27, 2023 |
| Apple         | MacBookPro10,1              | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| HP            | EliteBook 840 G2            | [33dc8202e9](https://linux-hardware.org/?probe=33dc8202e9) | Feb 25, 2023 |
| HUAWEI        | CREM-WXX9                   | [643d79fd46](https://linux-hardware.org/?probe=643d79fd46) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [ba0144c710](https://linux-hardware.org/?probe=ba0144c710) | Feb 20, 2023 |
| Apple         | MacBookPro13,3              | [628feb8b19](https://linux-hardware.org/?probe=628feb8b19) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | [2f591ee9e3](https://linux-hardware.org/?probe=2f591ee9e3) | Feb 13, 2023 |
| Timi          | RedmiBook 15                | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Acer          | Aspire V5-552G              | [2750863407](https://linux-hardware.org/?probe=2750863407) | Feb 02, 2023 |
| HP            | ProBook 6560b               | [a9eba68b79](https://linux-hardware.org/?probe=a9eba68b79) | Jan 14, 2023 |
| Samsung       | SBB-DA                      | [a4c6b4f454](https://linux-hardware.org/?probe=a4c6b4f454) | Jan 07, 2023 |
| MSI           | Raider GE67HX 12UGS         | [28822be06e](https://linux-hardware.org/?probe=28822be06e) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [e1ae2ba145](https://linux-hardware.org/?probe=e1ae2ba145) | Dec 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d1342c521a](https://linux-hardware.org/?probe=d1342c521a) | Dec 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5c0099832f](https://linux-hardware.org/?probe=5c0099832f) | Dec 15, 2022 |
| Lenovo        | B50-70 20384                | [82edcc6c08](https://linux-hardware.org/?probe=82edcc6c08) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | [6f8c8644e2](https://linux-hardware.org/?probe=6f8c8644e2) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [33f7ac03f4](https://linux-hardware.org/?probe=33f7ac03f4) | Nov 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| Apple         | MacBookPro9,2               | [e87a096d85](https://linux-hardware.org/?probe=e87a096d85) | Nov 27, 2022 |
| Apple         | MacBookPro9,2               | [9e465f741d](https://linux-hardware.org/?probe=9e465f741d) | Nov 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_23.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.0-20-generic        | 263       | 66.75%  |
| 6.2.0-23-generic        | 40        | 10.15%  |
| 5.19.0-21-generic       | 15        | 3.81%   |
| 6.2.0-18-generic        | 11        | 2.79%   |
| 6.2.0-24-generic        | 10        | 2.54%   |
| 5.19.0-41-generic       | 6         | 1.52%   |
| 6.1.0-16-generic        | 5         | 1.27%   |
| 6.4.0-060400-generic    | 3         | 0.76%   |
| 6.2.9-060209-generic    | 3         | 0.76%   |
| 5.19.0-31-generic       | 3         | 0.76%   |
| 6.3.5-060305-generic    | 2         | 0.51%   |
| 6.3.2-060302-generic    | 2         | 0.51%   |
| 6.2.0-19-generic        | 2         | 0.51%   |
| 6.2.0-1003-lowlatency   | 2         | 0.51%   |
| 5.19.0-40-generic       | 2         | 0.51%   |
| 5.19.0-28-generic       | 2         | 0.51%   |
| 6.3.8-x64v4-xanmod1     | 1         | 0.25%   |
| 6.3.1-x64v3-xanmod1     | 1         | 0.25%   |
| 6.3.0-rc7               | 1         | 0.25%   |
| 6.3.0-060300rc7-generic | 1         | 0.25%   |
| 6.3.0-060300-generic    | 1         | 0.25%   |
| 6.3.0+                  | 1         | 0.25%   |
| 6.2.6-060206-generic    | 1         | 0.25%   |
| 6.2.12-060212-generic   | 1         | 0.25%   |
| 6.2.11-060211-generic   | 1         | 0.25%   |
| 6.2.0-1005-lowlatency   | 1         | 0.25%   |
| 6.1.0-daily-20221223    | 1         | 0.25%   |
| 6.0.9-060009-generic    | 1         | 0.25%   |
| 5.19.0-46-generic       | 1         | 0.25%   |
| 5.19.0-43-generic       | 1         | 0.25%   |
| 5.19.0-42-generic       | 1         | 0.25%   |
| 5.19.0-38-generic       | 1         | 0.25%   |
| 5.19.0-35-generic       | 1         | 0.25%   |
| 5.19.0-29-generic       | 1         | 0.25%   |
| 5.19.0-26-generic       | 1         | 0.25%   |
| 5.15.0-50-generic       | 1         | 0.25%   |
| 5.14.0-1054-oem         | 1         | 0.25%   |
| 5.14.0-1033-oem         | 1         | 0.25%   |
| 5.11.0-33-generic       | 1         | 0.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 324       | 83.29%  |
| 5.19.0  | 35        | 9%      |
| 6.1.0   | 6         | 1.54%   |
| 6.3.0   | 4         | 1.03%   |
| 6.4.0   | 3         | 0.77%   |
| 6.2.9   | 3         | 0.77%   |
| 6.3.5   | 2         | 0.51%   |
| 6.3.2   | 2         | 0.51%   |
| 5.14.0  | 2         | 0.51%   |
| 6.3.8   | 1         | 0.26%   |
| 6.3.1   | 1         | 0.26%   |
| 6.2.6   | 1         | 0.26%   |
| 6.2.12  | 1         | 0.26%   |
| 6.2.11  | 1         | 0.26%   |
| 6.0.9   | 1         | 0.26%   |
| 5.15.0  | 1         | 0.26%   |
| 5.11.0  | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 330       | 84.83%  |
| 5.19    | 35        | 9%      |
| 6.3     | 10        | 2.57%   |
| 6.1     | 6         | 1.54%   |
| 6.4     | 3         | 0.77%   |
| 5.14    | 2         | 0.51%   |
| 6.0     | 1         | 0.26%   |
| 5.15    | 1         | 0.26%   |
| 5.11    | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 387       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 378       | 97.42%  |
| X-Cinnamon      | 5         | 1.29%   |
| Unknown         | 4         | 1.03%   |
| GNOME Flashback | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 250       | 63.61%  |
| X11     | 138       | 35.11%  |
| Unknown | 5         | 1.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 345       | 88.92%  |
| Unknown | 38        | 9.79%   |
| LightDM | 5         | 1.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 174       | 44.73%  |
| de_DE   | 36        | 9.25%   |
| fr_FR   | 20        | 5.14%   |
| es_ES   | 19        | 4.88%   |
| C       | 17        | 4.37%   |
| pt_BR   | 15        | 3.86%   |
| en_GB   | 14        | 3.6%    |
| it_IT   | 12        | 3.08%   |
| ru_RU   | 11        | 2.83%   |
| pl_PL   | 8         | 2.06%   |
| en_AU   | 8         | 2.06%   |
| es_MX   | 4         | 1.03%   |
| en_CA   | 4         | 1.03%   |
| Unknown | 4         | 1.03%   |
| nl_NL   | 3         | 0.77%   |
| hu_HU   | 3         | 0.77%   |
| en_ZA   | 3         | 0.77%   |
| zh_CN   | 2         | 0.51%   |
| sv_SE   | 2         | 0.51%   |
| fi_FI   | 2         | 0.51%   |
| en_IN   | 2         | 0.51%   |
| el_GR   | 2         | 0.51%   |
| de_CH   | 2         | 0.51%   |
| cs_CZ   | 2         | 0.51%   |
| ca_ES   | 2         | 0.51%   |
| bg_BG   | 2         | 0.51%   |
| tr_TR   | 1         | 0.26%   |
| ro_RO   | 1         | 0.26%   |
| pt_PT   | 1         | 0.26%   |
| nb_NO   | 1         | 0.26%   |
| ja_JP   | 1         | 0.26%   |
| hr_HR   | 1         | 0.26%   |
| fr_CA   | 1         | 0.26%   |
| fa_IR   | 1         | 0.26%   |
| et_EE   | 1         | 0.26%   |
| es_CR   | 1         | 0.26%   |
| es_CL   | 1         | 0.26%   |
| en_SG   | 1         | 0.26%   |
| en_IL   | 1         | 0.26%   |
| en_IE   | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 223       | 57.33%  |
| EFI  | 166       | 42.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 187       | 48.2%   |
| Tmpfs   | 186       | 47.94%  |
| Overlay | 9         | 2.32%   |
| Btrfs   | 4         | 1.03%   |
| Zfs     | 2         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 338       | 87.11%  |
| Unknown | 32        | 8.25%   |
| MBR     | 18        | 4.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 353       | 91.21%  |
| Yes       | 34        | 8.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 254       | 64.8%   |
| Yes       | 138       | 35.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 75        | 19.38%  |
| Dell                           | 64        | 16.54%  |
| Hewlett-Packard                | 60        | 15.5%   |
| ASUSTek Computer               | 39        | 10.08%  |
| Acer                           | 37        | 9.56%   |
| HUAWEI                         | 17        | 4.39%   |
| MSI                            | 15        | 3.88%   |
| Apple                          | 12        | 3.1%    |
| Toshiba                        | 9         | 2.33%   |
| Samsung Electronics            | 7         | 1.81%   |
| Timi                           | 4         | 1.03%   |
| Sony                           | 4         | 1.03%   |
| Unknown                        | 4         | 1.03%   |
| Shanghai Zhaoxin Semiconductor | 3         | 0.78%   |
| Razer                          | 3         | 0.78%   |
| Notebook                       | 3         | 0.78%   |
| Medion                         | 3         | 0.78%   |
| Google                         | 3         | 0.78%   |
| Packard Bell                   | 2         | 0.52%   |
| HONOR                          | 2         | 0.52%   |
| Gateway                        | 2         | 0.52%   |
| Alienware                      | 2         | 0.52%   |
| VALE                           | 1         | 0.26%   |
| Star Labs                      | 1         | 0.26%   |
| Semp Toshiba                   | 1         | 0.26%   |
| Rombica                        | 1         | 0.26%   |
| Positivo                       | 1         | 0.26%   |
| PC Specialist                  | 1         | 0.26%   |
| Panasonic                      | 1         | 0.26%   |
| Olivetti                       | 1         | 0.26%   |
| Mediacom                       | 1         | 0.26%   |
| Intel                          | 1         | 0.26%   |
| ICL                            | 1         | 0.26%   |
| Gigabyte Technology            | 1         | 0.26%   |
| Daten Tecnologia               | 1         | 0.26%   |
| Crusaders Corporate (Pty)      | 1         | 0.26%   |
| AVITA                          | 1         | 0.26%   |
| Allview                        | 1         | 0.26%   |
| ALLDOCUBE                      | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 4         | 1.03%   |
| Shanghai Zhaoxin ZXE CRB                 | 3         | 0.78%   |
| HUAWEI BOM-WXX9                          | 3         | 0.78%   |
| HP Notebook                              | 3         | 0.78%   |
| Dell Latitude 7480                       | 3         | 0.78%   |
| Apple MacBookPro9,2                      | 3         | 0.78%   |
| Acer Swift SF314-512                     | 3         | 0.78%   |
| Toshiba Satellite Pro C70-B              | 2         | 0.52%   |
| Timi Redmi Book Pro 14 2022              | 2         | 0.52%   |
| MSI Stealth 15M B12UE                    | 2         | 0.52%   |
| MSI Modern 14 A10M                       | 2         | 0.52%   |
| HUAWEI KLVD-WXX9                         | 2         | 0.52%   |
| HUAWEI CREM-WXX9                         | 2         | 0.52%   |
| HUAWEI BOHB-WAX9                         | 2         | 0.52%   |
| HONOR BBR-WAX9                           | 2         | 0.52%   |
| HP Pavilion Notebook                     | 2         | 0.52%   |
| HP Pavilion dv6                          | 2         | 0.52%   |
| HP Meep                                  | 2         | 0.52%   |
| HP Laptop 15s-eq2xxx                     | 2         | 0.52%   |
| HP Laptop 14-dq2xxx                      | 2         | 0.52%   |
| HP EliteBook 840 G6                      | 2         | 0.52%   |
| Dell XPS 15 9570                         | 2         | 0.52%   |
| Dell XPS 15 9500                         | 2         | 0.52%   |
| Dell Precision 5570                      | 2         | 0.52%   |
| Dell Latitude E5470                      | 2         | 0.52%   |
| Dell Latitude 5440                       | 2         | 0.52%   |
| Dell Inspiron 3442                       | 2         | 0.52%   |
| Dell G5 5590                             | 2         | 0.52%   |
| ASUS Zenbook UM5302TA_UM5302TA           | 2         | 0.52%   |
| ASUS X751MA                              | 2         | 0.52%   |
| ASUS VivoBook_ASUSLaptop M3500QA_M3500QA | 2         | 0.52%   |
| Acer Aspire E5-575G                      | 2         | 0.52%   |
| VALE Notebook Classic C140               | 1         | 0.26%   |
| Toshiba Satellite-L845                   | 1         | 0.26%   |
| Toshiba Satellite Pro C650               | 1         | 0.26%   |
| Toshiba Satellite P755                   | 1         | 0.26%   |
| Toshiba Satellite L650                   | 1         | 0.26%   |
| Toshiba Satellite C870-199               | 1         | 0.26%   |
| Toshiba PORTEGE Z30t-A                   | 1         | 0.26%   |
| Toshiba PORTEGE X30-D                    | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 41        | 10.59%  |
| Dell Latitude         | 25        | 6.46%   |
| Acer Aspire           | 18        | 4.65%   |
| Lenovo IdeaPad        | 16        | 4.13%   |
| Dell Inspiron         | 16        | 4.13%   |
| ASUS VivoBook         | 14        | 3.62%   |
| HP Pavilion           | 12        | 3.1%    |
| HP Laptop             | 11        | 2.84%   |
| HP EliteBook          | 11        | 2.84%   |
| Dell XPS              | 11        | 2.84%   |
| Acer Swift            | 9         | 2.33%   |
| Toshiba Satellite     | 6         | 1.55%   |
| HP ProBook            | 6         | 1.55%   |
| Acer Nitro            | 6         | 1.55%   |
| Dell Precision        | 5         | 1.29%   |
| ASUS ASUS             | 5         | 1.29%   |
| MSI Stealth           | 4         | 1.03%   |
| Lenovo Legion         | 4         | 1.03%   |
| Dell Vostro           | 4         | 1.03%   |
| ASUS Zenbook          | 4         | 1.03%   |
| Unknown               | 4         | 1.03%   |
| Shanghai Zhaoxin ZXE  | 3         | 0.78%   |
| Razer Blade           | 3         | 0.78%   |
| Lenovo Yoga           | 3         | 0.78%   |
| HUAWEI BOM-WXX9       | 3         | 0.78%   |
| HP ZBook              | 3         | 0.78%   |
| HP Notebook           | 3         | 0.78%   |
| HP ENVY               | 3         | 0.78%   |
| Apple MacBookPro9     | 3         | 0.78%   |
| Toshiba PORTEGE       | 2         | 0.52%   |
| Timi Redmi            | 2         | 0.52%   |
| Packard Bell EasyNote | 2         | 0.52%   |
| MSI Modern            | 2         | 0.52%   |
| MSI Katana            | 2         | 0.52%   |
| MSI GF63              | 2         | 0.52%   |
| Lenovo ThinkBook      | 2         | 0.52%   |
| HUAWEI KLVD-WXX9      | 2         | 0.52%   |
| HUAWEI CREM-WXX9      | 2         | 0.52%   |
| HUAWEI BOHB-WAX9      | 2         | 0.52%   |
| HONOR BBR-WAX9        | 2         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 71        | 18.35%  |
| 2022    | 52        | 13.44%  |
| 2020    | 42        | 10.85%  |
| 2019    | 29        | 7.49%   |
| 2016    | 28        | 7.24%   |
| 2011    | 23        | 5.94%   |
| 2018    | 21        | 5.43%   |
| 2017    | 18        | 4.65%   |
| 2012    | 18        | 4.65%   |
| 2014    | 17        | 4.39%   |
| 2015    | 16        | 4.13%   |
| 2023    | 14        | 3.62%   |
| 2010    | 13        | 3.36%   |
| 2013    | 9         | 2.33%   |
| 2008    | 8         | 2.07%   |
| 2009    | 6         | 1.55%   |
| 2007    | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 387       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 342       | 88.37%  |
| Enabled  | 45        | 11.63%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 382       | 98.71%  |
| Yes  | 5         | 1.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 116       | 29.97%  |
| 16.01-24.0  | 85        | 21.96%  |
| 8.01-16.0   | 70        | 18.09%  |
| 3.01-4.0    | 53        | 13.7%   |
| 32.01-64.0  | 37        | 9.56%   |
| 24.01-32.0  | 14        | 3.62%   |
| 64.01-256.0 | 8         | 2.07%   |
| 1.01-2.0    | 4         | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 121       | 30.56%  |
| 1.01-2.0   | 95        | 23.99%  |
| 4.01-8.0   | 89        | 22.47%  |
| 3.01-4.0   | 70        | 17.68%  |
| 8.01-16.0  | 17        | 4.29%   |
| 16.01-24.0 | 3         | 0.76%   |
| 24.01-32.0 | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 299       | 77.26%  |
| 2      | 79        | 20.41%  |
| 3      | 7         | 1.81%   |
| 4      | 2         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 302       | 78.04%  |
| Yes       | 85        | 21.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 256       | 66.15%  |
| No        | 131       | 33.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 383       | 98.97%  |
| No        | 4         | 1.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 334       | 85.86%  |
| No        | 55        | 14.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 50        | 12.89%  |
| Germany                | 41        | 10.57%  |
| France                 | 23        | 5.93%   |
| Brazil                 | 23        | 5.93%   |
| Russia                 | 22        | 5.67%   |
| Italy                  | 19        | 4.9%    |
| Spain                  | 16        | 4.12%   |
| UK                     | 13        | 3.35%   |
| Australia              | 12        | 3.09%   |
| Poland                 | 9         | 2.32%   |
| India                  | 9         | 2.32%   |
| Netherlands            | 8         | 2.06%   |
| Mexico                 | 8         | 2.06%   |
| Romania                | 7         | 1.8%    |
| Canada                 | 7         | 1.8%    |
| Switzerland            | 6         | 1.55%   |
| Sweden                 | 6         | 1.55%   |
| Norway                 | 6         | 1.55%   |
| Turkey                 | 5         | 1.29%   |
| Czechia                | 5         | 1.29%   |
| China                  | 5         | 1.29%   |
| Portugal               | 4         | 1.03%   |
| Chile                  | 4         | 1.03%   |
| Belgium                | 4         | 1.03%   |
| Vietnam                | 3         | 0.77%   |
| South Africa           | 3         | 0.77%   |
| Kenya                  | 3         | 0.77%   |
| Ireland                | 3         | 0.77%   |
| Hungary                | 3         | 0.77%   |
| Greece                 | 3         | 0.77%   |
| Finland                | 3         | 0.77%   |
| Egypt                  | 3         | 0.77%   |
| Bosnia and Herzegovina | 3         | 0.77%   |
| Austria                | 3         | 0.77%   |
| Slovakia               | 2         | 0.52%   |
| Serbia                 | 2         | 0.52%   |
| Qatar                  | 2         | 0.52%   |
| Philippines            | 2         | 0.52%   |
| Japan                  | 2         | 0.52%   |
| Israel                 | 2         | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 7         | 1.78%   |
| Berlin            | 6         | 1.53%   |
| Barcelona         | 5         | 1.27%   |
| Sao Paulo         | 4         | 1.02%   |
| Oslo              | 4         | 1.02%   |
| Zurich            | 3         | 0.76%   |
| St Petersburg     | 3         | 0.76%   |
| Santiago          | 3         | 0.76%   |
| Rio de Janeiro    | 3         | 0.76%   |
| Nairobi           | 3         | 0.76%   |
| Mumbai            | 3         | 0.76%   |
| Montreal          | 3         | 0.76%   |
| Melbourne         | 3         | 0.76%   |
| Madrid            | 3         | 0.76%   |
| Frankfurt am Main | 3         | 0.76%   |
| Denver            | 3         | 0.76%   |
| Brussels          | 3         | 0.76%   |
| Warsaw            | 2         | 0.51%   |
| Turin             | 2         | 0.51%   |
| Toronto           | 2         | 0.51%   |
| Tel Aviv          | 2         | 0.51%   |
| Stockholm         | 2         | 0.51%   |
| Sofia             | 2         | 0.51%   |
| Sarajevo          | 2         | 0.51%   |
| Prague            | 2         | 0.51%   |
| Perth             | 2         | 0.51%   |
| Paris             | 2         | 0.51%   |
| Orenburg          | 2         | 0.51%   |
| Milan             | 2         | 0.51%   |
| Melun             | 2         | 0.51%   |
| Kunming           | 2         | 0.51%   |
| Krakow            | 2         | 0.51%   |
| Jianshui          | 2         | 0.51%   |
| Helsinki          | 2         | 0.51%   |
| Hamburg           | 2         | 0.51%   |
| Guadalajara       | 2         | 0.51%   |
| Ghaziabad         | 2         | 0.51%   |
| Düsseldorf       | 2         | 0.51%   |
| Doha              | 2         | 0.51%   |
| Da Nang           | 2         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 84        | 95     | 18.18%  |
| WDC                         | 36        | 39     | 7.79%   |
| Sandisk                     | 33        | 37     | 7.14%   |
| SK hynix                    | 32        | 34     | 6.93%   |
| Kingston                    | 30        | 33     | 6.49%   |
| Seagate                     | 25        | 28     | 5.41%   |
| Micron Technology           | 24        | 27     | 5.19%   |
| Unknown                     | 20        | 22     | 4.33%   |
| Toshiba                     | 20        | 22     | 4.33%   |
| KIOXIA                      | 18        | 18     | 3.9%    |
| Intel                       | 15        | 18     | 3.25%   |
| Crucial                     | 13        | 14     | 2.81%   |
| Phison Electronics          | 9         | 10     | 1.95%   |
| China                       | 9         | 9      | 1.95%   |
| Apple                       | 8         | 10     | 1.73%   |
| HGST                        | 6         | 7      | 1.3%    |
| Phison                      | 5         | 5      | 1.08%   |
| Hitachi                     | 5         | 5      | 1.08%   |
| Silicon Motion              | 4         | 4      | 0.87%   |
| LITEONIT                    | 4         | 5      | 0.87%   |
| Team                        | 3         | 3      | 0.65%   |
| LITEON                      | 3         | 5      | 0.65%   |
| Kingston Technology Company | 3         | 3      | 0.65%   |
| A-DATA Technology           | 3         | 3      | 0.65%   |
| Union Memory                | 2         | 2      | 0.43%   |
| SSSTC                       | 2         | 2      | 0.43%   |
| SPCC                        | 2         | 2      | 0.43%   |
| Realtek Semiconductor       | 2         | 2      | 0.43%   |
| Netac                       | 2         | 2      | 0.43%   |
| Intenso                     | 2         | 4      | 0.43%   |
| GOODRAM                     | 2         | 2      | 0.43%   |
| Gigabyte Technology         | 2         | 2      | 0.43%   |
| FORESEE                     | 2         | 2      | 0.43%   |
| ADATA Technology            | 2         | 2      | 0.43%   |
| YMTC                        | 1         | 1      | 0.22%   |
| XrayDisk                    | 1         | 1      | 0.22%   |
| XPG                         | 1         | 1      | 0.22%   |
| WDC WDS2                    | 1         | 1      | 0.22%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.22%   |
| UMIS                        | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 12        | 2.53%   |
| Kingston SA400S37240G 240GB SSD                       | 7         | 1.48%   |
| SanDisk NVMe SSD Drive 512GB                          | 6         | 1.27%   |
| Kingston SA400S37480G 480GB SSD                       | 6         | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB                        | 5         | 1.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 5         | 1.05%   |
| Phison E12 NVMe Controller 1TB                        | 5         | 1.05%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                         | 5         | 1.05%   |
| Unknown MMC Card  64GB                                | 4         | 0.84%   |
| Unknown MMC Card  32GB                                | 4         | 0.84%   |
| Toshiba MQ01ABF050 500GB                              | 4         | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 4         | 0.84%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 4         | 0.84%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 4         | 0.84%   |
| Unknown SD/MMC/MS PRO 250GB                           | 3         | 0.63%   |
| Unknown MMC Card  16GB                                | 3         | 0.63%   |
| Toshiba XG6 NVMe SSD Controller 2TB                   | 3         | 0.63%   |
| SK hynix HFS256G39TND-N210A 256GB SSD                 | 3         | 0.63%   |
| SK hynix HFM512GD3JX013N 512GB                        | 3         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 3         | 0.63%   |
| Samsung SSD 870 EVO 500GB                             | 3         | 0.63%   |
| Samsung SSD 850 EVO 250GB                             | 3         | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 3         | 0.63%   |
| Samsung MZVL21T0HCLR-00B00 1TB                        | 3         | 0.63%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 3         | 0.63%   |
| KIOXIA KBG40ZNV512G 512GB                             | 3         | 0.63%   |
| Kingston SA400S37960G 960GB SSD                       | 3         | 0.63%   |
| Intel SSD 660P Series 512GB                           | 3         | 0.63%   |
| HGST HTS721010A9E630 1TB                              | 3         | 0.63%   |
| China 256GB SSD                                       | 3         | 0.63%   |
| WDC WD10SPZX-00Z10T0 1TB                              | 2         | 0.42%   |
| WDC PC SN730 SDBPNTY-512G                             | 2         | 0.42%   |
| Unknown MMC Card  128GB                               | 2         | 0.42%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 0.42%   |
| Team T253512GB SSD                                    | 2         | 0.42%   |
| SK hynix PC801 NVMe 1TB                               | 2         | 0.42%   |
| SK hynix PC601 NVMe 512GB                             | 2         | 0.42%   |
| SK hynix HFM001TD3JX013N 1TB                          | 2         | 0.42%   |
| SK hynix BC511 256GB                                  | 2         | 0.42%   |
| Seagate Expansion HDD 8TB                             | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 28     | 34.25%  |
| WDC                 | 17        | 18     | 23.29%  |
| Toshiba             | 11        | 13     | 15.07%  |
| HGST                | 6         | 7      | 8.22%   |
| Hitachi             | 5         | 5      | 6.85%   |
| Unknown             | 3         | 3      | 4.11%   |
| Samsung Electronics | 2         | 2      | 2.74%   |
| JMicron Technology  | 1         | 1      | 1.37%   |
| HGST HTS            | 1         | 1      | 1.37%   |
| Fujitsu             | 1         | 1      | 1.37%   |
| Apple               | 1         | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 35     | 21.62%  |
| Kingston            | 23        | 26     | 15.54%  |
| Crucial             | 11        | 12     | 7.43%   |
| WDC                 | 9         | 10     | 6.08%   |
| SanDisk             | 9         | 9      | 6.08%   |
| China               | 9         | 9      | 6.08%   |
| SK hynix            | 6         | 6      | 4.05%   |
| Micron Technology   | 4         | 4      | 2.7%    |
| LITEONIT            | 4         | 5      | 2.7%    |
| Apple               | 4         | 4      | 2.7%    |
| Team                | 3         | 3      | 2.03%   |
| LITEON              | 3         | 5      | 2.03%   |
| A-DATA Technology   | 3         | 3      | 2.03%   |
| SPCC                | 2         | 2      | 1.35%   |
| Netac               | 2         | 2      | 1.35%   |
| Intenso             | 2         | 3      | 1.35%   |
| Intel               | 2         | 3      | 1.35%   |
| Gigabyte Technology | 2         | 2      | 1.35%   |
| XrayDisk            | 1         | 1      | 0.68%   |
| WDC WDS2            | 1         | 1      | 0.68%   |
| Toshiba             | 1         | 1      | 0.68%   |
| Smartbuy            | 1         | 1      | 0.68%   |
| S3+                 | 1         | 1      | 0.68%   |
| PNY                 | 1         | 1      | 0.68%   |
| Plextor             | 1         | 1      | 0.68%   |
| Pioneer             | 1         | 1      | 0.68%   |
| Patriot             | 1         | 1      | 0.68%   |
| ORTIAL              | 1         | 1      | 0.68%   |
| NT-512              | 1         | 1      | 0.68%   |
| Lexar               | 1         | 1      | 0.68%   |
| KINGBANK            | 1         | 1      | 0.68%   |
| INTEL SS            | 1         | 2      | 0.68%   |
| GOODRAM             | 1         | 1      | 0.68%   |
| GLOWAY              | 1         | 1      | 0.68%   |
| FORESEE             | 1         | 1      | 0.68%   |
| Unknown             | 1         | 1      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 210       | 244    | 47.84%  |
| SSD     | 136       | 162    | 30.98%  |
| HDD     | 73        | 80     | 16.63%  |
| MMC     | 17        | 19     | 3.87%   |
| Unknown | 3         | 4      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 210       | 244    | 48.95%  |
| SATA | 186       | 227    | 43.36%  |
| MMC  | 17        | 19     | 3.96%   |
| SAS  | 16        | 19     | 3.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 146       | 174    | 68.87%  |
| 0.51-1.0   | 54        | 55     | 25.47%  |
| 1.01-2.0   | 8         | 9      | 3.77%   |
| 4.01-10.0  | 4         | 4      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 124       | 31.23%  |
| 251-500        | 121       | 30.48%  |
| 501-1000       | 65        | 16.37%  |
| 51-100         | 24        | 6.05%   |
| 21-50          | 17        | 4.28%   |
| 1-20           | 17        | 4.28%   |
| 1001-2000      | 15        | 3.78%   |
| More than 3000 | 5         | 1.26%   |
| 2001-3000      | 5         | 1.26%   |
| Unknown        | 4         | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 138       | 34.94%  |
| 21-50     | 102       | 25.82%  |
| 101-250   | 54        | 13.67%  |
| 51-100    | 47        | 11.9%   |
| 251-500   | 29        | 7.34%   |
| 501-1000  | 15        | 3.8%    |
| 1001-2000 | 4         | 1.01%   |
| Unknown   | 4         | 1.01%   |
| 2001-3000 | 2         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB                 | 1         | 1      | 9.09%   |
| WDC WD Green M.2 2280 240GB SSD          | 1         | 1      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 9.09%   |
| LITEONIT LCT-256M3S-41 7mm 256GB FDE SSD | 1         | 1      | 9.09%   |
| Hitachi HTS723225A7A365 OPAL 250GB       | 1         | 1      | 9.09%   |
| Hitachi HTS547564A9E384 640GB            | 1         | 1      | 9.09%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 9.09%   |
| HGST HTS541010A9E680 1TB                 | 1         | 1      | 9.09%   |
| Fujitsu MHW2160BH 160GB                  | 1         | 1      | 9.09%   |
| Unknown                                  | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 2         | 2      | 18.18%  |
| Seagate  | 2         | 2      | 18.18%  |
| Hitachi  | 2         | 2      | 18.18%  |
| HGST     | 2         | 2      | 18.18%  |
| LITEONIT | 1         | 1      | 9.09%   |
| Fujitsu  | 1         | 1      | 9.09%   |
| Unknown  | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 25%     |
| Hitachi | 2         | 2      | 25%     |
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Fujitsu | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 72.73%  |
| SSD  | 3         | 3      | 27.27%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 247       | 343    | 62.37%  |
| Works    | 138       | 155    | 34.85%  |
| Malfunc  | 11        | 11     | 2.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 245       | 49.2%   |
| Samsung Electronics                     | 54        | 10.84%  |
| AMD                                     | 36        | 7.23%   |
| SanDisk                                 | 34        | 6.83%   |
| SK hynix                                | 26        | 5.22%   |
| Micron Technology                       | 20        | 4.02%   |
| Phison Electronics                      | 16        | 3.21%   |
| KIOXIA                                  | 16        | 3.21%   |
| Toshiba America Info Systems            | 10        | 2.01%   |
| Kingston Technology Company             | 9         | 1.81%   |
| Solid State Storage Technology          | 4         | 0.8%    |
| Silicon Motion                          | 4         | 0.8%    |
| Zhaoxin                                 | 3         | 0.6%    |
| Union Memory (Shenzhen)                 | 3         | 0.6%    |
| Micron/Crucial Technology               | 3         | 0.6%    |
| ADATA Technology                        | 3         | 0.6%    |
| Shenzhen Longsys Electronics            | 2         | 0.4%    |
| Realtek Semiconductor                   | 2         | 0.4%    |
| Apple                                   | 2         | 0.4%    |
| Yangtze Memory Technologies             | 1         | 0.2%    |
| Transcend                               | 1         | 0.2%    |
| Shenzhen Unionmemory Information System | 1         | 0.2%    |
| Nvidia                                  | 1         | 0.2%    |
| Lenovo                                  | 1         | 0.2%    |
| ASMedia Technology                      | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                            | 38        | 7.2%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 34        | 6.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 32        | 6.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 23        | 4.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 19        | 3.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 3.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 3.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 16        | 3.03%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 12        | 2.27%   |
| Samsung NVMe SSD Controller 980                                                | 12        | 2.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 11        | 2.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 2.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 1.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 1.7%    |
| Micron NVMe Storage Controller                                                 | 9         | 1.7%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 9         | 1.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 1.7%    |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 1.52%   |
| SanDisk Non-Volatile memory controller                                         | 7         | 1.33%   |
| Phison PS5013 E13 NVMe Controller                                              | 7         | 1.33%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 7         | 1.33%   |
| KIOXIA Non-Volatile memory controller                                          | 7         | 1.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 1.33%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 6         | 1.14%   |
| Phison E12 NVMe Controller                                                     | 6         | 1.14%   |
| Intel Non-Volatile memory controller                                           | 6         | 1.14%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 6         | 1.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 1.14%   |
| SK hynix Non-Volatile memory controller                                        | 5         | 0.95%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 0.95%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 5         | 0.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 0.95%   |
| SK hynix BC511 NVMe SSD                                                        | 4         | 0.76%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 0.76%   |
| Intel SSD 660P Series                                                          | 4         | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 229       | 45.17%  |
| NVMe | 209       | 41.22%  |
| RAID | 60        | 11.83%  |
| IDE  | 9         | 1.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 309       | 79.84%  |
| AMD          | 75        | 19.38%  |
| CentaurHauls | 3         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 8         | 2.07%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 7         | 1.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 7         | 1.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 6         | 1.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 6         | 1.55%   |
| Intel 12th Gen Core i7-12700H                  | 6         | 1.55%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz        | 6         | 1.55%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 6         | 1.55%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 6         | 1.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 5         | 1.29%   |
| Intel Core i7-6600U CPU @ 2.60GHz              | 5         | 1.29%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 5         | 1.29%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 5         | 1.29%   |
| Intel Core i5-5200U CPU @ 2.20GHz              | 5         | 1.29%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 5         | 1.29%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 5         | 1.29%   |
| Intel 12th Gen Core i7-1260P                   | 5         | 1.29%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 5         | 1.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 4         | 1.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 4         | 1.03%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 4         | 1.03%   |
| Intel Core i7-2630QM CPU @ 2.00GHz             | 4         | 1.03%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 4         | 1.03%   |
| Intel Core i3-10110U CPU @ 2.10GHz             | 4         | 1.03%   |
| Intel 12th Gen Core i5-1240P                   | 4         | 1.03%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz        | 4         | 1.03%   |
| Intel Core i7-6500U CPU @ 2.50GHz              | 3         | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz              | 3         | 0.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 3         | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 3         | 0.78%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 3         | 0.78%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 3         | 0.78%   |
| Intel Core i3 CPU M 370 @ 2.40GHz              | 3         | 0.78%   |
| Intel 12th Gen Core i7-12650H                  | 3         | 0.78%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 3         | 0.78%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz        | 3         | 0.78%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 3         | 0.78%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 3         | 0.78%   |
| AMD Ryzen 5 5600H with Radeon Graphics         | 3         | 0.78%   |
| AMD Ryzen 5 4600H with Radeon Graphics         | 3         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 85        | 21.96%  |
| Intel Core i5        | 81        | 20.93%  |
| Intel Core i7        | 79        | 20.41%  |
| AMD Ryzen 7          | 29        | 7.49%   |
| Intel Core i3        | 25        | 6.46%   |
| AMD Ryzen 5          | 19        | 4.91%   |
| Intel Celeron        | 17        | 4.39%   |
| Intel Core 2 Duo     | 12        | 3.1%    |
| Intel Pentium        | 6         | 1.55%   |
| AMD Ryzen 9          | 6         | 1.55%   |
| AMD Ryzen 7 PRO      | 4         | 1.03%   |
| Intel Pentium Silver | 3         | 0.78%   |
| AMD E2               | 3         | 0.78%   |
| AMD A8               | 3         | 0.78%   |
| Intel Core i9        | 2         | 0.52%   |
| AMD Ryzen 5 PRO      | 2         | 0.52%   |
| AMD Ryzen 3          | 2         | 0.52%   |
| AMD A4               | 2         | 0.52%   |
| AMD A10              | 2         | 0.52%   |
| Intel Xeon           | 1         | 0.26%   |
| Intel Pentium Dual   | 1         | 0.26%   |
| Intel Core m7        | 1         | 0.26%   |
| Intel Core M         | 1         | 0.26%   |
| AMD Athlon II        | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 150       | 38.76%  |
| 4      | 116       | 29.97%  |
| 8      | 45        | 11.63%  |
| 6      | 35        | 9.04%   |
| 14     | 15        | 3.88%   |
| 12     | 12        | 3.1%    |
| 10     | 9         | 2.33%   |
| 16     | 2         | 0.52%   |
| 24     | 1         | 0.26%   |
| 5      | 1         | 0.26%   |
| 1      | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 387       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 315       | 81.4%   |
| 1      | 72        | 18.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 387       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 335       | 86.34%  |
| 0x0a404102 | 6         | 1.55%   |
| 0x08608103 | 6         | 1.55%   |
| 0x0a50000c | 5         | 1.29%   |
| 0x08600106 | 5         | 1.29%   |
| 0x0a404101 | 4         | 1.03%   |
| 0x0a50000d | 3         | 0.77%   |
| 0x906a3    | 2         | 0.52%   |
| 0x806ec    | 2         | 0.52%   |
| 0x306a9    | 2         | 0.52%   |
| 0x08608102 | 2         | 0.52%   |
| 0x906ea    | 1         | 0.26%   |
| 0x806c1    | 1         | 0.26%   |
| 0x506e3    | 1         | 0.26%   |
| 0x406e3    | 1         | 0.26%   |
| 0x306d4    | 1         | 0.26%   |
| 0x0a704101 | 1         | 0.26%   |
| 0x08a00006 | 1         | 0.26%   |
| 0x08608104 | 1         | 0.26%   |
| 0x08600109 | 1         | 0.26%   |
| 0x08600103 | 1         | 0.26%   |
| 0x08108109 | 1         | 0.26%   |
| 0x08108102 | 1         | 0.26%   |
| 0x0810100b | 1         | 0.26%   |
| 0x07030105 | 1         | 0.26%   |
| 0x06006704 | 1         | 0.26%   |
| 0x06006113 | 1         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 72        | 18.56%  |
| Unknown          | 53        | 13.66%  |
| TigerLake        | 34        | 8.76%   |
| Alderlake Hybrid | 29        | 7.47%   |
| IvyBridge        | 25        | 6.44%   |
| Skylake          | 22        | 5.67%   |
| SandyBridge      | 22        | 5.67%   |
| Haswell          | 16        | 4.12%   |
| Zen 3            | 15        | 3.87%   |
| Broadwell        | 13        | 3.35%   |
| Zen 2            | 12        | 3.09%   |
| Goldmont plus    | 11        | 2.84%   |
| Westmere         | 10        | 2.58%   |
| Penryn           | 9         | 2.32%   |
| CometLake        | 9         | 2.32%   |
| Zen+             | 6         | 1.55%   |
| Excavator        | 6         | 1.55%   |
| Silvermont       | 5         | 1.29%   |
| Core             | 4         | 1.03%   |
| Puma             | 3         | 0.77%   |
| IceLake          | 3         | 0.77%   |
| Goldmont         | 3         | 0.77%   |
| Zen              | 1         | 0.26%   |
| Steamroller      | 1         | 0.26%   |
| Piledriver       | 1         | 0.26%   |
| Nehalem          | 1         | 0.26%   |
| K10 Llano        | 1         | 0.26%   |
| K10              | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 293       | 57.68%  |
| Nvidia  | 118       | 23.23%  |
| AMD     | 94        | 18.5%   |
| Zhaoxin | 3         | 0.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 25        | 4.88%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 23        | 4.49%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 21        | 4.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 20        | 3.91%   |
| Intel HD Graphics 620                                                                 | 15        | 2.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 14        | 2.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 14        | 2.73%   |
| AMD Rembrandt [Radeon 680M]                                                           | 13        | 2.54%   |
| AMD Lucienne                                                                          | 13        | 2.54%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 12        | 2.34%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 12        | 2.34%   |
| AMD Renoir                                                                            | 12        | 2.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 11        | 2.15%   |
| Intel HD Graphics 5500                                                                | 11        | 2.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 11        | 2.15%   |
| Intel UHD Graphics 620                                                                | 10        | 1.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 10        | 1.95%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 9         | 1.76%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 8         | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 8         | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 8         | 1.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 7         | 1.37%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 7         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                                   | 7         | 1.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 7         | 1.37%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 6         | 1.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 1.17%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 4         | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 4         | 0.78%   |
| Intel HD Graphics 630                                                                 | 4         | 0.78%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                 | 4         | 0.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 4         | 0.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 4         | 0.78%   |
| AMD Barcelo                                                                           | 4         | 0.78%   |
| Zhaoxin ZX-E C-960 GPU                                                                | 3         | 0.59%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.59%   |
| Nvidia GF119M [GeForce GT 520M]                                                       | 3         | 0.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 185       | 47.8%   |
| Intel + Nvidia | 93        | 24.03%  |
| 1 x AMD        | 65        | 16.8%   |
| AMD + Nvidia   | 15        | 3.88%   |
| Intel + AMD    | 13        | 3.36%   |
| 1 x Nvidia     | 10        | 2.58%   |
| 1 x Zhaoxin    | 3         | 0.78%   |
| Other          | 1         | 0.26%   |
| 2 x Intel      | 1         | 0.26%   |
| 2 x AMD        | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 303       | 78.29%  |
| Proprietary | 72        | 18.6%   |
| Unknown     | 12        | 3.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 320       | 82.69%  |
| 0.01-0.5   | 30        | 7.75%   |
| 1.01-2.0   | 19        | 4.91%   |
| 3.01-4.0   | 7         | 1.81%   |
| 0.51-1.0   | 7         | 1.81%   |
| 5.01-6.0   | 3         | 0.78%   |
| 8.01-16.0  | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 96        | 21.05%  |
| BOE                     | 69        | 15.13%  |
| Chimei Innolux          | 60        | 13.16%  |
| LG Display              | 46        | 10.09%  |
| Samsung Electronics     | 40        | 8.77%   |
| Sharp                   | 14        | 3.07%   |
| Goldstar                | 14        | 3.07%   |
| Apple                   | 11        | 2.41%   |
| PANDA                   | 10        | 2.19%   |
| Dell                    | 10        | 2.19%   |
| CSO                     | 10        | 2.19%   |
| Hewlett-Packard         | 8         | 1.75%   |
| Lenovo                  | 5         | 1.1%    |
| InfoVision              | 5         | 1.1%    |
| Ancor Communications    | 5         | 1.1%    |
| Sony                    | 4         | 0.88%   |
| Philips                 | 4         | 0.88%   |
| Chi Mei Optoelectronics | 4         | 0.88%   |
| BenQ                    | 4         | 0.88%   |
| Acer                    | 4         | 0.88%   |
| Iiyama                  | 3         | 0.66%   |
| Denver                  | 3         | 0.66%   |
| AOC                     | 3         | 0.66%   |
| ViewSonic               | 2         | 0.44%   |
| Unknown                 | 2         | 0.44%   |
| Panasonic               | 2         | 0.44%   |
| LG Philips              | 2         | 0.44%   |
| ASUSTek Computer        | 2         | 0.44%   |
| WST                     | 1         | 0.22%   |
| Wacom                   | 1         | 0.22%   |
| Vestel Elektronik       | 1         | 0.22%   |
| Unknown (XXX)           | 1         | 0.22%   |
| Tianma XM               | 1         | 0.22%   |
| Sceptre Tech            | 1         | 0.22%   |
| MStar                   | 1         | 0.22%   |
| MSI                     | 1         | 0.22%   |
| Medion Akoya            | 1         | 0.22%   |
| KDC                     | 1         | 0.22%   |
| iQual                   | 1         | 0.22%   |
| HYT                     | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 8         | 1.74%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 5         | 1.09%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 5         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.87%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 4         | 0.87%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 4         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 3         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.65%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 3         | 0.65%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 3         | 0.65%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO5799 1920x1080 344x194mm 15.5-inch        | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.65%   |
| AU Optronics LCD Monitor AUO0BA2 2560x1440 309x174mm 14.0-inch        | 3         | 0.65%   |
| Sony TV SNY4502 1920x1080                                             | 2         | 0.44%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch               | 2         | 0.44%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4172 2880x1800 289x186mm 13.5-inch | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SDC416B 3840x2400 344x215mm 16.0-inch | 2         | 0.44%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.44%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 2         | 0.44%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 2         | 0.44%   |
| InfoVision LCD Monitor IVO057E 1366x768 309x174mm 14.0-inch           | 2         | 0.44%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2         | 0.44%   |
| Denver UWQHD-100-V2 LHC3500 3440x1440 798x342mm 34.2-inch             | 2         | 0.44%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 2         | 0.44%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                     | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 2         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 199       | 46.71%  |
| 1366x768 (WXGA)    | 90        | 21.13%  |
| 3840x2160 (4K)     | 18        | 4.23%   |
| 1600x900 (HD+)     | 17        | 3.99%   |
| 2560x1440 (QHD)    | 15        | 3.52%   |
| 2560x1600          | 13        | 3.05%   |
| 2880x1800          | 11        | 2.58%   |
| 1920x1200 (WUXGA)  | 11        | 2.58%   |
| 1280x800 (WXGA)    | 10        | 2.35%   |
| 3440x1440          | 9         | 2.11%   |
| 3840x2400          | 5         | 1.17%   |
| 2160x1440          | 3         | 0.7%    |
| 1680x1050 (WSXGA+) | 3         | 0.7%    |
| 1440x900 (WXGA+)   | 3         | 0.7%    |
| 1280x1024 (SXGA)   | 3         | 0.7%    |
| 2560x1080          | 2         | 0.47%   |
| 2520x1680          | 2         | 0.47%   |
| 2256x1504          | 2         | 0.47%   |
| 2240x1400          | 2         | 0.47%   |
| 3840x1600          | 1         | 0.23%   |
| 3456x2160          | 1         | 0.23%   |
| 3200x1800 (QHD+)   | 1         | 0.23%   |
| 3072x1920          | 1         | 0.23%   |
| 3000x2000          | 1         | 0.23%   |
| 2880x1620          | 1         | 0.23%   |
| 1920x540           | 1         | 0.23%   |
| 1920x1280          | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 172       | 37.72%  |
| 13      | 71        | 15.57%  |
| 14      | 67        | 14.69%  |
| 17      | 28        | 6.14%   |
| 16      | 16        | 3.51%   |
| 27      | 15        | 3.29%   |
| 12      | 12        | 2.63%   |
| 23      | 11        | 2.41%   |
| 24      | 9         | 1.97%   |
| 34      | 8         | 1.75%   |
| 21      | 8         | 1.75%   |
| 11      | 5         | 1.1%    |
| 20      | 4         | 0.88%   |
| Unknown | 4         | 0.88%   |
| 72      | 3         | 0.66%   |
| 35      | 3         | 0.66%   |
| 25      | 3         | 0.66%   |
| 22      | 3         | 0.66%   |
| 84      | 2         | 0.44%   |
| 54      | 2         | 0.44%   |
| 58      | 1         | 0.22%   |
| 52      | 1         | 0.22%   |
| 49      | 1         | 0.22%   |
| 42      | 1         | 0.22%   |
| 37      | 1         | 0.22%   |
| 32      | 1         | 0.22%   |
| 31      | 1         | 0.22%   |
| 26      | 1         | 0.22%   |
| 19      | 1         | 0.22%   |
| 8       | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 271       | 60.09%  |
| 201-300     | 61        | 13.53%  |
| 501-600     | 37        | 8.2%    |
| 351-400     | 37        | 8.2%    |
| 401-500     | 15        | 3.33%   |
| 701-800     | 9         | 2%      |
| 1501-2000   | 5         | 1.11%   |
| 1001-1500   | 5         | 1.11%   |
| 801-900     | 4         | 0.89%   |
| Unknown     | 4         | 0.89%   |
| 601-700     | 1         | 0.22%   |
| 101-200     | 1         | 0.22%   |
| 901-1000    | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 311       | 78.34%  |
| 16/10   | 58        | 14.61%  |
| 21/9    | 12        | 3.02%   |
| 3/2     | 9         | 2.27%   |
| 5/4     | 2         | 0.5%    |
| Unknown | 2         | 0.5%    |
| 6/5     | 1         | 0.25%   |
| 32/9    | 1         | 0.25%   |
| 0.62    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 172       | 37.64%  |
| 81-90          | 109       | 23.85%  |
| 71-80          | 28        | 6.13%   |
| 201-250        | 25        | 5.47%   |
| 121-130        | 25        | 5.47%   |
| 301-350        | 16        | 3.5%    |
| 111-120        | 15        | 3.28%   |
| 351-500        | 13        | 2.84%   |
| 61-70          | 12        | 2.63%   |
| More than 1000 | 10        | 2.19%   |
| 151-200        | 8         | 1.75%   |
| 251-300        | 7         | 1.53%   |
| 51-60          | 5         | 1.09%   |
| Unknown        | 4         | 0.88%   |
| 131-140        | 3         | 0.66%   |
| 501-1000       | 2         | 0.44%   |
| 1-40           | 1         | 0.22%   |
| 141-150        | 1         | 0.22%   |
| 91-100         | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 188       | 42.34%  |
| 101-120       | 109       | 24.55%  |
| 161-240       | 60        | 13.51%  |
| 51-100        | 53        | 11.94%  |
| More than 240 | 23        | 5.18%   |
| 1-50          | 7         | 1.58%   |
| Unknown       | 4         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 302       | 77.63%  |
| 2     | 62        | 15.94%  |
| 3     | 12        | 3.08%   |
| 0     | 12        | 3.08%   |
| 4     | 1         | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 214       | 36.27%  |
| Realtek Semiconductor             | 190       | 32.2%   |
| Qualcomm Atheros                  | 59        | 10%     |
| Broadcom                          | 33        | 5.59%   |
| MediaTek                          | 23        | 3.9%    |
| DisplayLink                       | 8         | 1.36%   |
| Broadcom Limited                  | 8         | 1.36%   |
| TP-Link                           | 6         | 1.02%   |
| ASIX Electronics                  | 6         | 1.02%   |
| Lenovo                            | 5         | 0.85%   |
| Xiaomi                            | 4         | 0.68%   |
| Sierra Wireless                   | 3         | 0.51%   |
| Ralink Technology                 | 3         | 0.51%   |
| Marvell Technology Group          | 3         | 0.51%   |
| Dell                              | 3         | 0.51%   |
| Ralink                            | 2         | 0.34%   |
| Huawei Technologies               | 2         | 0.34%   |
| Hewlett-Packard                   | 2         | 0.34%   |
| Ericsson Business Mobile Networks | 2         | 0.34%   |
| Vimtron Electronics               | 1         | 0.17%   |
| U-Blox                            | 1         | 0.17%   |
| Samsung Electronics               | 1         | 0.17%   |
| Quectel Wireless Solutions        | 1         | 0.17%   |
| Qualcomm                          | 1         | 0.17%   |
| Nvidia                            | 1         | 0.17%   |
| MosChip Semiconductor             | 1         | 0.17%   |
| JMicron Technology                | 1         | 0.17%   |
| Google                            | 1         | 0.17%   |
| Flipper Devices                   | 1         | 0.17%   |
| Edimax Technology                 | 1         | 0.17%   |
| D-Link System                     | 1         | 0.17%   |
| D-Link                            | 1         | 0.17%   |
| ASUSTek Computer                  | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 13.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 3.9%    |
| Intel Wi-Fi 6 AX201                                               | 25        | 3.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 24        | 3.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 21        | 3.03%   |
| Intel Wi-Fi 6 AX200                                               | 17        | 2.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 2.31%   |
| Intel Wireless 8260                                               | 14        | 2.02%   |
| Intel Wireless 8265 / 8275                                        | 13        | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 1.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 12        | 1.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 1.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 10        | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 1.44%   |
| Intel Wireless 7265                                               | 10        | 1.44%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 1.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.15%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 8         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 8         | 1.15%   |
| Intel Alder Lake-U CNVi: Wireless-AC                              | 8         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.01%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 6         | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.72%   |
| Intel Wireless 3165                                               | 5         | 0.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 5         | 0.72%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.58%   |
| Intel WiFi Link 5100                                              | 4         | 0.58%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 208       | 51.61%  |
| Realtek Semiconductor      | 68        | 16.87%  |
| Qualcomm Atheros           | 54        | 13.4%   |
| Broadcom                   | 26        | 6.45%   |
| MediaTek                   | 22        | 5.46%   |
| TP-Link                    | 6         | 1.49%   |
| Broadcom Limited           | 4         | 0.99%   |
| Sierra Wireless            | 3         | 0.74%   |
| Ralink Technology          | 3         | 0.74%   |
| Ralink                     | 2         | 0.5%    |
| Quectel Wireless Solutions | 1         | 0.25%   |
| Qualcomm                   | 1         | 0.25%   |
| Edimax Technology          | 1         | 0.25%   |
| Dell                       | 1         | 0.25%   |
| D-Link System              | 1         | 0.25%   |
| D-Link                     | 1         | 0.25%   |
| ASUSTek Computer           | 1         | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 25        | 6.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 24        | 5.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 21        | 5.16%   |
| Intel Wi-Fi 6 AX200                                            | 17        | 4.18%   |
| Intel Wireless 8260                                            | 14        | 3.44%   |
| Intel Wireless 8265 / 8275                                     | 13        | 3.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 3.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 12        | 2.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 2.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 10        | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 2.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 2.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 10        | 2.46%   |
| Intel Wireless 7265                                            | 10        | 2.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9         | 2.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 1.97%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 8         | 1.97%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 1.97%   |
| Intel Alder Lake-U CNVi: Wireless-AC                           | 8         | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 1.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 1.47%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.23%   |
| Intel Wireless 3165                                            | 5         | 1.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 5         | 1.23%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 1.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.98%   |
| Intel WiFi Link 5100                                           | 4         | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.98%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 0.74%   |
| Intel Wireless 7260                                            | 3         | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 0.74%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 3         | 0.74%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.74%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.74%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 151       | 54.71%  |
| Intel                    | 64        | 23.19%  |
| Broadcom                 | 11        | 3.99%   |
| Qualcomm Atheros         | 10        | 3.62%   |
| DisplayLink              | 8         | 2.9%    |
| ASIX Electronics         | 6         | 2.17%   |
| Lenovo                   | 5         | 1.81%   |
| Xiaomi                   | 4         | 1.45%   |
| Broadcom Limited         | 4         | 1.45%   |
| Marvell Technology Group | 3         | 1.09%   |
| Vimtron Electronics      | 1         | 0.36%   |
| TP-Link                  | 1         | 0.36%   |
| Samsung Electronics      | 1         | 0.36%   |
| Nvidia                   | 1         | 0.36%   |
| MosChip Semiconductor    | 1         | 0.36%   |
| MediaTek                 | 1         | 0.36%   |
| JMicron Technology       | 1         | 0.36%   |
| Huawei Technologies      | 1         | 0.36%   |
| Hewlett-Packard          | 1         | 0.36%   |
| Google                   | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 33.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 9.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 5.76%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 3.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 3.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 6         | 2.16%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 2.16%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.44%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.08%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 1.08%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.08%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.08%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 1.08%   |
| Realtek PCIe GbE Family Controller                                | 2         | 0.72%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.72%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.72%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.72%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 0.72%   |
| Intel Ethernet Controller I219-LM                                 | 2         | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.72%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 2         | 0.72%   |
| DisplayLink USB 3.0 Docking Station                               | 2         | 0.72%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.36%   |
| Vimtron Mobile Composite Device Bus                               | 1         | 0.36%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.36%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 383       | 59.1%   |
| Ethernet | 257       | 39.66%  |
| Modem    | 8         | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 325       | 81.86%  |
| Ethernet | 72        | 18.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 223       | 57.47%  |
| 1     | 160       | 41.24%  |
| 0     | 3         | 0.77%   |
| 3     | 2         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 270       | 69.59%  |
| Yes  | 118       | 30.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 180       | 53.73%  |
| Realtek Semiconductor           | 36        | 10.75%  |
| Qualcomm Atheros Communications | 28        | 8.36%   |
| Foxconn / Hon Hai               | 16        | 4.78%   |
| IMC Networks                    | 15        | 4.48%   |
| Broadcom                        | 14        | 4.18%   |
| Realtek                         | 10        | 2.99%   |
| Lite-On Technology              | 10        | 2.99%   |
| Apple                           | 9         | 2.69%   |
| Hewlett-Packard                 | 3         | 0.9%    |
| Dell                            | 3         | 0.9%    |
| Cambridge Silicon Radio         | 3         | 0.9%    |
| Toshiba                         | 2         | 0.6%    |
| Opticis                         | 2         | 0.6%    |
| TP-Link                         | 1         | 0.3%    |
| Ralink Technology               | 1         | 0.3%    |
| Fujitsu                         | 1         | 0.3%    |
| ASUSTek Computer                | 1         | 0.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 51        | 15.22%  |
| Intel Bluetooth wireless interface                  | 45        | 13.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 9.55%   |
| Realtek Bluetooth Radio                             | 28        | 8.36%   |
| Intel Bluetooth Device                              | 24        | 7.16%   |
| Intel AX200 Bluetooth                               | 16        | 4.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 4.18%   |
| Realtek Bluetooth Radio                             | 10        | 2.99%   |
| IMC Networks Wireless_Device                        | 9         | 2.69%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 2.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 1.79%   |
| IMC Networks Bluetooth Radio                        | 5         | 1.49%   |
| Apple Bluetooth Host Controller                     | 5         | 1.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.19%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 1.19%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 1.19%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 1.19%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 1.19%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.19%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.9%    |
| Intel AX210 Bluetooth                               | 3         | 0.9%    |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 0.9%    |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.9%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.6%    |
| Opticis Bluetooth Radio                             | 2         | 0.6%    |
| Lite-On Wireless_Device                             | 2         | 0.6%    |
| Lite-On Bluetooth Device                            | 2         | 0.6%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.6%    |
| Broadcom HP Portable Valentine                      | 2         | 0.6%    |
| TP-Link UB500 Adapter                               | 1         | 0.3%    |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.3%    |
| Toshiba BCM43142A0                                  | 1         | 0.3%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.3%    |
| Lite-On Bluetooth Radio                             | 1         | 0.3%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 308       | 62.1%   |
| AMD                                          | 81        | 16.33%  |
| Nvidia                                       | 67        | 13.51%  |
| Lenovo                                       | 6         | 1.21%   |
| C-Media Electronics                          | 6         | 1.21%   |
| Realtek Semiconductor                        | 4         | 0.81%   |
| GN Netcom                                    | 4         | 0.81%   |
| Zhaoxin                                      | 3         | 0.6%    |
| Plantronics                                  | 2         | 0.4%    |
| Generalplus Technology                       | 2         | 0.4%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.2%    |
| VIA Technologies                             | 1         | 0.2%    |
| Texas Instruments                            | 1         | 0.2%    |
| Superlux digit                               | 1         | 0.2%    |
| Sennheiser Communications                    | 1         | 0.2%    |
| Scarlett                                     | 1         | 0.2%    |
| Razer USA                                    | 1         | 0.2%    |
| Native Instruments                           | 1         | 0.2%    |
| M-Audio                                      | 1         | 0.2%    |
| Jieli Technology                             | 1         | 0.2%    |
| Huawei Technologies                          | 1         | 0.2%    |
| DSEA A/S                                     | 1         | 0.2%    |
| Antlion Audio                                | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 55        | 9.29%   |
| Intel Sunrise Point-LP HD Audio                                            | 45        | 7.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 38        | 6.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 34        | 5.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 28        | 4.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 26        | 4.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 3.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 2.53%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 14        | 2.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 2.2%    |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 2.2%    |
| Intel Broadwell-U Audio Controller                                         | 13        | 2.2%    |
| Nvidia GA106 High Definition Audio Controller                              | 12        | 2.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 12        | 2.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 11        | 1.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 1.86%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1.69%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 1.69%   |
| Nvidia Audio device                                                        | 9         | 1.52%   |
| Intel Alder Lake-U cAVS (Audio, Voice, Speech)                             | 9         | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 1.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.01%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 1.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.01%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 0.84%   |
| Intel CM238 HD Audio Controller                                            | 5         | 0.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.84%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 0.84%   |
| Realtek Semiconductor USB Audio                                            | 4         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 0.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 0.68%   |
| AMD High Definition Audio Controller                                       | 4         | 0.68%   |
| Zhaoxin ZX-E High Definition Audio Controller                              | 3         | 0.51%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller   | 3         | 0.51%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 23.58%  |
| SK hynix            | 52        | 22.71%  |
| Micron Technology   | 47        | 20.52%  |
| Kingston            | 16        | 6.99%   |
| Crucial             | 11        | 4.8%    |
| Unknown (ABCD)      | 6         | 2.62%   |
| Unknown             | 5         | 2.18%   |
| Smart               | 5         | 2.18%   |
| Ramaxel Technology  | 5         | 2.18%   |
| A-DATA Technology   | 5         | 2.18%   |
| Transcend           | 3         | 1.31%   |
| Shenzhen WODPOSIT   | 3         | 1.31%   |
| Timetec             | 2         | 0.87%   |
| GOODRAM             | 2         | 0.87%   |
| Elpida              | 2         | 0.87%   |
| Unknown (0x0CDC)    | 1         | 0.44%   |
| Saikano             | 1         | 0.44%   |
| PNY                 | 1         | 0.44%   |
| Patriot             | 1         | 0.44%   |
| Nanya Technology    | 1         | 0.44%   |
| Kingmax             | 1         | 0.44%   |
| KINGBANK            | 1         | 0.44%   |
| Gold Key            | 1         | 0.44%   |
| Corsair             | 1         | 0.44%   |
| ChangXin Memory     | 1         | 0.44%   |
| Unknown             | 1         | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 6         | 2.51%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 2.51%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 4         | 1.67%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 4         | 1.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 1.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 1.26%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.26%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s            | 3         | 1.26%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.26%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.26%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.26%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 2         | 0.84%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.84%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 2         | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.84%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.84%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 2         | 0.84%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.84%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.84%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.84%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.84%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.84%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 0.84%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.84%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.84%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.84%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s     | 2         | 0.84%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB SODIMM LPDDR5 6400MT/s           | 2         | 0.84%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.84%   |
| Micron RAM MT40A512M16LY-075:E 4GB SODIMM DDR4 3200MT/s          | 2         | 0.84%   |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                     | 2         | 0.84%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.84%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.84%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.84%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.84%   |
| Kingston RAM 99P5700-042.A00G 16GB SODIMM DDR4 3200MT/s          | 2         | 0.84%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 103       | 51.5%   |
| DDR3   | 35        | 17.5%   |
| LPDDR5 | 19        | 9.5%    |
| LPDDR4 | 18        | 9%      |
| DDR5   | 15        | 7.5%    |
| LPDDR3 | 5         | 2.5%    |
| SDRAM  | 3         | 1.5%    |
| DDR2   | 2         | 1%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 160       | 79.6%   |
| Row Of Chips | 37        | 18.41%  |
| Chip         | 3         | 1.49%   |
| Unknown      | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 109       | 50%     |
| 4096  | 53        | 24.31%  |
| 16384 | 37        | 16.97%  |
| 2048  | 10        | 4.59%   |
| 32768 | 7         | 3.21%   |
| 1536  | 1         | 0.46%   |
| 1024  | 1         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 61        | 28.11%  |
| 2667    | 34        | 15.67%  |
| 1600    | 29        | 13.36%  |
| 6400    | 18        | 8.29%   |
| 2400    | 15        | 6.91%   |
| 4800    | 14        | 6.45%   |
| 4267    | 10        | 4.61%   |
| 2133    | 7         | 3.23%   |
| 1334    | 4         | 1.84%   |
| 1333    | 4         | 1.84%   |
| 2666    | 3         | 1.38%   |
| 8400    | 2         | 0.92%   |
| 2048    | 2         | 0.92%   |
| 1867    | 2         | 0.92%   |
| 5600    | 1         | 0.46%   |
| 5500    | 1         | 0.46%   |
| 5200    | 1         | 0.46%   |
| 4266    | 1         | 0.46%   |
| 4199    | 1         | 0.46%   |
| 3733    | 1         | 0.46%   |
| 3266    | 1         | 0.46%   |
| 2933    | 1         | 0.46%   |
| 975     | 1         | 0.46%   |
| 800     | 1         | 0.46%   |
| 667     | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 1         | 33.33%  |
| HP LaserJet Pro M201dw               | 1         | 33.33%  |
| Canon TS3100 series                  | 1         | 33.33%  |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 81        | 23.48%  |
| Microdia                               | 38        | 11.01%  |
| IMC Networks                           | 38        | 11.01%  |
| Quanta                                 | 31        | 8.99%   |
| Realtek Semiconductor                  | 30        | 8.7%    |
| Sunplus Innovation Technology          | 17        | 4.93%   |
| Luxvisions Innotech Limited            | 17        | 4.93%   |
| Bison Electronics                      | 15        | 4.35%   |
| Apple                                  | 9         | 2.61%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.32%   |
| Acer                                   | 8         | 2.32%   |
| Sonix Technology                       | 7         | 2.03%   |
| Syntek                                 | 6         | 1.74%   |
| Alcor Micro                            | 6         | 1.74%   |
| Silicon Motion                         | 4         | 1.16%   |
| Logitech                               | 4         | 1.16%   |
| Lite-On Technology                     | 4         | 1.16%   |
| Importek                               | 4         | 1.16%   |
| Suyin                                  | 3         | 0.87%   |
| USB Camera                             | 2         | 0.58%   |
| ShineTech                              | 2         | 0.58%   |
| SunplusIT                              | 1         | 0.29%   |
| Sunplus Technology                     | 1         | 0.29%   |
| Shine-optics                           | 1         | 0.29%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.29%   |
| Samsung Electronics                    | 1         | 0.29%   |
| Ricoh                                  | 1         | 0.29%   |
| Pixart Imaging                         | 1         | 0.29%   |
| Microsoft                              | 1         | 0.29%   |
| Lenovo                                 | 1         | 0.29%   |
| Foxconn / Hon Hai                      | 1         | 0.29%   |
| BKX-210918                             | 1         | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 24        | 6.86%   |
| Microdia Integrated_Webcam_HD                        | 17        | 4.86%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 12        | 3.43%   |
| IMC Networks Integrated Camera                       | 12        | 3.43%   |
| Chicony HP HD Camera                                 | 11        | 3.14%   |
| Realtek Integrated_Webcam_HD                         | 8         | 2.29%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 8         | 2.29%   |
| Sunplus Integrated_Webcam_HD                         | 6         | 1.71%   |
| Realtek USB Camera                                   | 6         | 1.71%   |
| Quanta ov9734_techfront_camera                       | 6         | 1.71%   |
| Chicony HP Truevision HD                             | 6         | 1.71%   |
| Chicony HD WebCam                                    | 6         | 1.71%   |
| Quanta HD User Facing                                | 5         | 1.43%   |
| Syntek Integrated Camera                             | 4         | 1.14%   |
| Sonix USB2.0 HD UVC WebCam                           | 4         | 1.14%   |
| Quanta HD Camera                                     | 4         | 1.14%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 4         | 1.14%   |
| IMC Networks HD Camera                               | 4         | 1.14%   |
| Chicony HD User Facing                               | 4         | 1.14%   |
| Acer Integrated Camera                               | 4         | 1.14%   |
| Sonix USB2.0 FHD UVC WebCam                          | 3         | 0.86%   |
| Quanta HD Webcam                                     | 3         | 0.86%   |
| Quanta Acer FHD User Facing                          | 3         | 0.86%   |
| Microdia Webcam Vitade AF                            | 3         | 0.86%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 3         | 0.86%   |
| Microdia Integrated_Webcam_FHD                       | 3         | 0.86%   |
| Luxvisions Innotech Limited Integrated Camera        | 3         | 0.86%   |
| Lite-On Integrated Camera                            | 3         | 0.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 0.86%   |
| IMC Networks Integrated RGB Camera                   | 3         | 0.86%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 0.86%   |
| Chicony TOSHIBA Web Camera - HD                      | 3         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 3         | 0.86%   |
| Bison SunplusIT Integrated Camera                    | 3         | 0.86%   |
| Apple FaceTime HD Camera                             | 3         | 0.86%   |
| USB Camera USB Camera                                | 2         | 0.57%   |
| Sunplus XiaoMi USB 2.0 Webcam                        | 2         | 0.57%   |
| Sunplus HD WebCam                                    | 2         | 0.57%   |
| Sunplus FHD Camera Microphone                        | 2         | 0.57%   |
| ShineTech HD Camera                                  | 2         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 26        | 31.33%  |
| Validity Sensors                   | 21        | 25.3%   |
| Synaptics                          | 18        | 21.69%  |
| Elan Microelectronics              | 9         | 10.84%  |
| Upek                               | 3         | 3.61%   |
| LighTuning Technology              | 3         | 3.61%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 2.41%   |
| Focal-systems.Corp                 | 1         | 1.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                             | 21        | 25.3%   |
| Elan ELAN:ARM-M4                                                | 6         | 7.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 5         | 6.02%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 4         | 4.82%   |
| Shenzhen Goodix FingerPrint                                     | 4         | 4.82%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 3         | 3.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 3         | 3.61%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 3         | 3.61%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 3         | 3.61%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 3         | 3.61%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 3         | 3.61%   |
| Elan ELAN:Fingerprint                                           | 3         | 3.61%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 2.41%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 2         | 2.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 2         | 2.41%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 2.41%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 2.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 2.41%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 1.2%    |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 1.2%    |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 1.2%    |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 1.2%    |
| Validity Sensors Fingerprint scanner                            | 1         | 1.2%    |
| Synaptics WBDI                                                  | 1         | 1.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 1.2%    |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 1.2%    |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.2%    |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 1.2%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Broadcom        | 17        | 60.71%  |
| Alcor Micro     | 8         | 28.57%  |
| Upek            | 2         | 7.14%   |
| Hewlett-Packard | 1         | 3.57%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 8         | 28.57%  |
| Broadcom 5880                                              | 6         | 21.43%  |
| Broadcom 58200                                             | 6         | 21.43%  |
| Broadcom BCM5880 Secure Applications Processor             | 5         | 17.86%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 7.14%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)              | 1         | 3.57%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 211       | 53.96%  |
| 1     | 135       | 34.53%  |
| 2     | 32        | 8.18%   |
| 3     | 9         | 2.3%    |
| 4     | 3         | 0.77%   |
| 10    | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 84        | 37%     |
| Graphics card            | 49        | 21.59%  |
| Chipcard                 | 26        | 11.45%  |
| Camera                   | 19        | 8.37%   |
| Net/wireless             | 17        | 7.49%   |
| Multimedia controller    | 13        | 5.73%   |
| Sound                    | 6         | 2.64%   |
| Storage                  | 4         | 1.76%   |
| Net/ethernet             | 2         | 0.88%   |
| Communication controller | 2         | 0.88%   |
| Card reader              | 2         | 0.88%   |
| Bluetooth                | 2         | 0.88%   |
| Modem                    | 1         | 0.44%   |

