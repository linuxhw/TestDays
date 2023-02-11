Fedora 37 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 37.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_37/Desktop/README.md) and [notebooks](/Dist/Fedora_37/Notebook/README.md).

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

Total: 1560

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [8bc290ef67](https://linux-hardware.org/?probe=8bc290ef67) | Feb 01, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [542173e9a2](https://linux-hardware.org/?probe=542173e9a2) | Feb 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [22abfb4a79](https://linux-hardware.org/?probe=22abfb4a79) | Feb 01, 2023 |
| Lenovo        | ThinkPad A485 20MVS0U500    | Notebook    | [b398a8e8e6](https://linux-hardware.org/?probe=b398a8e8e6) | Feb 01, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [ff305089b2](https://linux-hardware.org/?probe=ff305089b2) | Feb 01, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [1ebeeec517](https://linux-hardware.org/?probe=1ebeeec517) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [ffe1cabad7](https://linux-hardware.org/?probe=ffe1cabad7) | Feb 01, 2023 |
| Dell          | Inspiron 7501               | Notebook    | [426493e8a5](https://linux-hardware.org/?probe=426493e8a5) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [779b723b67](https://linux-hardware.org/?probe=779b723b67) | Feb 01, 2023 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [c102edf6a0](https://linux-hardware.org/?probe=c102edf6a0) | Feb 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [79c11af9ac](https://linux-hardware.org/?probe=79c11af9ac) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [5f2948351d](https://linux-hardware.org/?probe=5f2948351d) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4f8642280f](https://linux-hardware.org/?probe=4f8642280f) | Feb 01, 2023 |
| AZW           | U59                         | Desktop     | [9b73123be3](https://linux-hardware.org/?probe=9b73123be3) | Feb 01, 2023 |
| AZW           | U59                         | Desktop     | [74f028454a](https://linux-hardware.org/?probe=74f028454a) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [6b9dc508e1](https://linux-hardware.org/?probe=6b9dc508e1) | Feb 01, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [99127d4bed](https://linux-hardware.org/?probe=99127d4bed) | Feb 01, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [7ee6505f8d](https://linux-hardware.org/?probe=7ee6505f8d) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [1d212c67b2](https://linux-hardware.org/?probe=1d212c67b2) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4b8ddf5d09](https://linux-hardware.org/?probe=4b8ddf5d09) | Jan 31, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ecbd4ac8b6](https://linux-hardware.org/?probe=ecbd4ac8b6) | Jan 31, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | Notebook    | [85ac6a588d](https://linux-hardware.org/?probe=85ac6a588d) | Jan 31, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [3ccdc4fa2b](https://linux-hardware.org/?probe=3ccdc4fa2b) | Jan 31, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [4dcc88b215](https://linux-hardware.org/?probe=4dcc88b215) | Jan 31, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [2df9f60f2e](https://linux-hardware.org/?probe=2df9f60f2e) | Jan 31, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [a64ae29757](https://linux-hardware.org/?probe=a64ae29757) | Jan 31, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [318b0a5ecb](https://linux-hardware.org/?probe=318b0a5ecb) | Jan 31, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a06f4e8595](https://linux-hardware.org/?probe=a06f4e8595) | Jan 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [73bc9212a3](https://linux-hardware.org/?probe=73bc9212a3) | Jan 31, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [6e7d6aae31](https://linux-hardware.org/?probe=6e7d6aae31) | Jan 31, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [2f14c18867](https://linux-hardware.org/?probe=2f14c18867) | Jan 31, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [75fad3daf3](https://linux-hardware.org/?probe=75fad3daf3) | Jan 31, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ee60c1c921](https://linux-hardware.org/?probe=ee60c1c921) | Jan 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [87904d9d06](https://linux-hardware.org/?probe=87904d9d06) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [6a4a26884d](https://linux-hardware.org/?probe=6a4a26884d) | Jan 30, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [357d14774f](https://linux-hardware.org/?probe=357d14774f) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [8e4f1d2ed2](https://linux-hardware.org/?probe=8e4f1d2ed2) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | Notebook    | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M8S... | Convertible | [782e38cf06](https://linux-hardware.org/?probe=782e38cf06) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1ecef01472](https://linux-hardware.org/?probe=1ecef01472) | Jan 30, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [8d62c84240](https://linux-hardware.org/?probe=8d62c84240) | Jan 30, 2023 |
| HP            | Pavilion 15                 | Notebook    | [6ceccb3d73](https://linux-hardware.org/?probe=6ceccb3d73) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [585c3c8f85](https://linux-hardware.org/?probe=585c3c8f85) | Jan 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [24402e3d42](https://linux-hardware.org/?probe=24402e3d42) | Jan 30, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [1d06f2715a](https://linux-hardware.org/?probe=1d06f2715a) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [9b6a9a4ab5](https://linux-hardware.org/?probe=9b6a9a4ab5) | Jan 30, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [e8f09a159a](https://linux-hardware.org/?probe=e8f09a159a) | Jan 29, 2023 |
| Dell          | Vostro 7620                 | Notebook    | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| ASUSTek       | GA15DH                      | Desktop     | [767fe59cb7](https://linux-hardware.org/?probe=767fe59cb7) | Jan 29, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [2f9de3e332](https://linux-hardware.org/?probe=2f9de3e332) | Jan 29, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [bdb3c91476](https://linux-hardware.org/?probe=bdb3c91476) | Jan 29, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [e253d5b49b](https://linux-hardware.org/?probe=e253d5b49b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [db0e6c89b4](https://linux-hardware.org/?probe=db0e6c89b4) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [104fb04e91](https://linux-hardware.org/?probe=104fb04e91) | Jan 29, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ef43edeee5](https://linux-hardware.org/?probe=ef43edeee5) | Jan 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f9a823cb38](https://linux-hardware.org/?probe=f9a823cb38) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [e72f7f2fb1](https://linux-hardware.org/?probe=e72f7f2fb1) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [60c03ee1f7](https://linux-hardware.org/?probe=60c03ee1f7) | Jan 29, 2023 |
| Acer          | FMP55                       | Desktop     | [d091fbc8d3](https://linux-hardware.org/?probe=d091fbc8d3) | Jan 29, 2023 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [0d1e08db32](https://linux-hardware.org/?probe=0d1e08db32) | Jan 28, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [30549ebd3a](https://linux-hardware.org/?probe=30549ebd3a) | Jan 28, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [f8da74bad3](https://linux-hardware.org/?probe=f8da74bad3) | Jan 28, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8384a02b4b](https://linux-hardware.org/?probe=8384a02b4b) | Jan 28, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [53015adc9d](https://linux-hardware.org/?probe=53015adc9d) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | Notebook    | [ed1ce46901](https://linux-hardware.org/?probe=ed1ce46901) | Jan 28, 2023 |
| Lenovo        | ThinkPad 20FQ005TGE         | Convertible | [a8e34a1084](https://linux-hardware.org/?probe=a8e34a1084) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [844e4e4b2a](https://linux-hardware.org/?probe=844e4e4b2a) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | Notebook    | [ab3f84f96b](https://linux-hardware.org/?probe=ab3f84f96b) | Jan 28, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [8a5423443a](https://linux-hardware.org/?probe=8a5423443a) | Jan 28, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [7e6cf30d81](https://linux-hardware.org/?probe=7e6cf30d81) | Jan 28, 2023 |
| Timi          | A35S                        | Notebook    | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad T450s 20BWS23W0... | Notebook    | [41c82dbadb](https://linux-hardware.org/?probe=41c82dbadb) | Jan 27, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [d9f9d4bc89](https://linux-hardware.org/?probe=d9f9d4bc89) | Jan 27, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [676f900958](https://linux-hardware.org/?probe=676f900958) | Jan 27, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e619db262a](https://linux-hardware.org/?probe=e619db262a) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a69331d2ea](https://linux-hardware.org/?probe=a69331d2ea) | Jan 27, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [882bb3b505](https://linux-hardware.org/?probe=882bb3b505) | Jan 27, 2023 |
| MECHREVO      | Code10-7CC6U                | Notebook    | [86e769b2a3](https://linux-hardware.org/?probe=86e769b2a3) | Jan 27, 2023 |
| Dell          | Precision 3550              | Notebook    | [4c42615cef](https://linux-hardware.org/?probe=4c42615cef) | Jan 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [00e21c8359](https://linux-hardware.org/?probe=00e21c8359) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | Notebook    | [a2ad3f4eb3](https://linux-hardware.org/?probe=a2ad3f4eb3) | Jan 27, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c0ea09ef3c](https://linux-hardware.org/?probe=c0ea09ef3c) | Jan 27, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [3895a32819](https://linux-hardware.org/?probe=3895a32819) | Jan 27, 2023 |
| BYTENUC       | AZ51                        | Mini pc     | [8be36cd9c0](https://linux-hardware.org/?probe=8be36cd9c0) | Jan 27, 2023 |
| Dynabook      | TECRA A50-J                 | Notebook    | [3921b100b4](https://linux-hardware.org/?probe=3921b100b4) | Jan 27, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [1d79d6f224](https://linux-hardware.org/?probe=1d79d6f224) | Jan 26, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [37d2157b37](https://linux-hardware.org/?probe=37d2157b37) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [9dfc820ceb](https://linux-hardware.org/?probe=9dfc820ceb) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [0168a5cae2](https://linux-hardware.org/?probe=0168a5cae2) | Jan 26, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [4024f7c3bd](https://linux-hardware.org/?probe=4024f7c3bd) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | Notebook    | [a1dfc58700](https://linux-hardware.org/?probe=a1dfc58700) | Jan 26, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [7b711bee4f](https://linux-hardware.org/?probe=7b711bee4f) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [4213c95d3d](https://linux-hardware.org/?probe=4213c95d3d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [b44aa465bc](https://linux-hardware.org/?probe=b44aa465bc) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Multilaser    | PC150                       | Notebook    | [1c4ace00d1](https://linux-hardware.org/?probe=1c4ace00d1) | Jan 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [415b96672b](https://linux-hardware.org/?probe=415b96672b) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | Notebook    | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [f69047309d](https://linux-hardware.org/?probe=f69047309d) | Jan 26, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [8725d530e5](https://linux-hardware.org/?probe=8725d530e5) | Jan 26, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ea142e4848](https://linux-hardware.org/?probe=ea142e4848) | Jan 25, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [f03240c746](https://linux-hardware.org/?probe=f03240c746) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [af63cfc79a](https://linux-hardware.org/?probe=af63cfc79a) | Jan 25, 2023 |
| Clevo         | M815P                       | Notebook    | [cfc5f6689f](https://linux-hardware.org/?probe=cfc5f6689f) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX H370-I GAMING     | Desktop     | [decfe6ab97](https://linux-hardware.org/?probe=decfe6ab97) | Jan 25, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [4efa4db490](https://linux-hardware.org/?probe=4efa4db490) | Jan 25, 2023 |
| MSI           | GL63 8RC                    | Notebook    | [138e8de541](https://linux-hardware.org/?probe=138e8de541) | Jan 25, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [33292253d0](https://linux-hardware.org/?probe=33292253d0) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| Dynabook      | TECRA A50-J                 | Notebook    | [2f24f18672](https://linux-hardware.org/?probe=2f24f18672) | Jan 25, 2023 |
| Dell          | 0XFWHV A00                  | Desktop     | [52ee3df163](https://linux-hardware.org/?probe=52ee3df163) | Jan 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [993ba3e73b](https://linux-hardware.org/?probe=993ba3e73b) | Jan 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [82c3a80b93](https://linux-hardware.org/?probe=82c3a80b93) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [aa6488b6b8](https://linux-hardware.org/?probe=aa6488b6b8) | Jan 25, 2023 |
| Fujitsu Si... | AMILO Notebook Xa 3530      | Notebook    | [e8384494a3](https://linux-hardware.org/?probe=e8384494a3) | Jan 25, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [d8df4aafe8](https://linux-hardware.org/?probe=d8df4aafe8) | Jan 25, 2023 |
| Dell          | Inspiron 5468               | Notebook    | [3e59c1f38b](https://linux-hardware.org/?probe=3e59c1f38b) | Jan 25, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [cb02367642](https://linux-hardware.org/?probe=cb02367642) | Jan 25, 2023 |
| Dell          | Latitude 5420               | Notebook    | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Dell          | Latitude 5520               | Notebook    | [662284824b](https://linux-hardware.org/?probe=662284824b) | Jan 24, 2023 |
| HP            | ProBook 6570b               | Notebook    | [841250ba59](https://linux-hardware.org/?probe=841250ba59) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Dell          | Latitude E6410              | Notebook    | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | Notebook    | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Lenovo        | 36E9 SDK0T08861 WIN 3305... | Desktop     | [82705366d7](https://linux-hardware.org/?probe=82705366d7) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | Notebook    | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | Notebook    | [3fb25133ec](https://linux-hardware.org/?probe=3fb25133ec) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [43c26544a9](https://linux-hardware.org/?probe=43c26544a9) | Jan 24, 2023 |
| Google        | Treeya                      | Notebook    | [27a381272a](https://linux-hardware.org/?probe=27a381272a) | Jan 24, 2023 |
| Dell          | 0X30MX A00                  | Desktop     | [c323a1a215](https://linux-hardware.org/?probe=c323a1a215) | Jan 24, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a227de29c5](https://linux-hardware.org/?probe=a227de29c5) | Jan 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1887a95d31](https://linux-hardware.org/?probe=1887a95d31) | Jan 23, 2023 |
| Dell          | Precision 3551              | Notebook    | [1338d3df20](https://linux-hardware.org/?probe=1338d3df20) | Jan 23, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [335275777a](https://linux-hardware.org/?probe=335275777a) | Jan 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7572089dc3](https://linux-hardware.org/?probe=7572089dc3) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [2f215e1ce7](https://linux-hardware.org/?probe=2f215e1ce7) | Jan 23, 2023 |
| Dell          | Latitude 7490               | Notebook    | [e40bb2f01f](https://linux-hardware.org/?probe=e40bb2f01f) | Jan 23, 2023 |
| Dell          | Latitude 7490               | Notebook    | [31789ae630](https://linux-hardware.org/?probe=31789ae630) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [091effd2ac](https://linux-hardware.org/?probe=091effd2ac) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [0a597ba033](https://linux-hardware.org/?probe=0a597ba033) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [90884b19a9](https://linux-hardware.org/?probe=90884b19a9) | Jan 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS12Q3M     | Notebook    | [e46b5a8b46](https://linux-hardware.org/?probe=e46b5a8b46) | Jan 23, 2023 |
| Dell          | Latitude E6500              | Notebook    | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R500... | Convertible | [7f5181d202](https://linux-hardware.org/?probe=7f5181d202) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | Notebook    | [689fe06d4d](https://linux-hardware.org/?probe=689fe06d4d) | Jan 23, 2023 |
| Dynabook      | TECRA A50-J                 | Notebook    | [92690b43cd](https://linux-hardware.org/?probe=92690b43cd) | Jan 23, 2023 |
| Dell          | Inspiron 7786               | Convertible | [4a96e070dd](https://linux-hardware.org/?probe=4a96e070dd) | Jan 23, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [00f594a9cf](https://linux-hardware.org/?probe=00f594a9cf) | Jan 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [279452d293](https://linux-hardware.org/?probe=279452d293) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [d03b7c0a68](https://linux-hardware.org/?probe=d03b7c0a68) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [07005e3e32](https://linux-hardware.org/?probe=07005e3e32) | Jan 22, 2023 |
| Dell          | 0Y56T3 A00                  | Desktop     | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| MSI           | H510M PRO                   | Desktop     | [309f1bc61b](https://linux-hardware.org/?probe=309f1bc61b) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [e9c7c42a8b](https://linux-hardware.org/?probe=e9c7c42a8b) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8e037468e4](https://linux-hardware.org/?probe=8e037468e4) | Jan 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b3d64d2496](https://linux-hardware.org/?probe=b3d64d2496) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [d999192dbf](https://linux-hardware.org/?probe=d999192dbf) | Jan 22, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [3edd4ab0dc](https://linux-hardware.org/?probe=3edd4ab0dc) | Jan 22, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [43aaf27a04](https://linux-hardware.org/?probe=43aaf27a04) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6856fa4741](https://linux-hardware.org/?probe=6856fa4741) | Jan 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [0aa98390a7](https://linux-hardware.org/?probe=0aa98390a7) | Jan 21, 2023 |
| AZW           | GTR V02                     | Desktop     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Acer          | Predator G9-591             | Notebook    | [0544a1b07c](https://linux-hardware.org/?probe=0544a1b07c) | Jan 21, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [e8a0c0066b](https://linux-hardware.org/?probe=e8a0c0066b) | Jan 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [adeb24c41e](https://linux-hardware.org/?probe=adeb24c41e) | Jan 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [7a067fe264](https://linux-hardware.org/?probe=7a067fe264) | Jan 21, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [32faa4aac5](https://linux-hardware.org/?probe=32faa4aac5) | Jan 21, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3eb2d3a903](https://linux-hardware.org/?probe=3eb2d3a903) | Jan 21, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [20c0f69bb7](https://linux-hardware.org/?probe=20c0f69bb7) | Jan 21, 2023 |
| Dell          | G5 5587                     | Notebook    | [96ca22c550](https://linux-hardware.org/?probe=96ca22c550) | Jan 21, 2023 |
| Dell          | G5 5587                     | Notebook    | [a070a8ba69](https://linux-hardware.org/?probe=a070a8ba69) | Jan 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3432d7c1f5](https://linux-hardware.org/?probe=3432d7c1f5) | Jan 20, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [2f6bd134ae](https://linux-hardware.org/?probe=2f6bd134ae) | Jan 20, 2023 |
| Digma         | CITI 1804 CS1069EW          | Tablet      | [0443e57eca](https://linux-hardware.org/?probe=0443e57eca) | Jan 20, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [5bbd614c0f](https://linux-hardware.org/?probe=5bbd614c0f) | Jan 20, 2023 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [4f815d5b4f](https://linux-hardware.org/?probe=4f815d5b4f) | Jan 20, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [ed4c536efa](https://linux-hardware.org/?probe=ed4c536efa) | Jan 20, 2023 |
| HP            | 0AECh D                     | Desktop     | [b2ea95f507](https://linux-hardware.org/?probe=b2ea95f507) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | Notebook    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5f1447f874](https://linux-hardware.org/?probe=5f1447f874) | Jan 20, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [9d5faff505](https://linux-hardware.org/?probe=9d5faff505) | Jan 20, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [d5a2a6aaa8](https://linux-hardware.org/?probe=d5a2a6aaa8) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [15c0522754](https://linux-hardware.org/?probe=15c0522754) | Jan 19, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [e81652a68c](https://linux-hardware.org/?probe=e81652a68c) | Jan 19, 2023 |
| Dell          | Precision 3551              | Notebook    | [4ff5a0ab8d](https://linux-hardware.org/?probe=4ff5a0ab8d) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [0f079e1dc7](https://linux-hardware.org/?probe=0f079e1dc7) | Jan 19, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [90049e4bb7](https://linux-hardware.org/?probe=90049e4bb7) | Jan 19, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [d6a24ede85](https://linux-hardware.org/?probe=d6a24ede85) | Jan 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [6a47296f0c](https://linux-hardware.org/?probe=6a47296f0c) | Jan 19, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [33b364ed89](https://linux-hardware.org/?probe=33b364ed89) | Jan 19, 2023 |
| Samsung       | DP300A2A-B01RU SEC_SW_RE... | All in one  | [18d76fe11f](https://linux-hardware.org/?probe=18d76fe11f) | Jan 19, 2023 |
| Dell          | Latitude 3410               | Notebook    | [187aebc2cd](https://linux-hardware.org/?probe=187aebc2cd) | Jan 19, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [6d570a1aee](https://linux-hardware.org/?probe=6d570a1aee) | Jan 19, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [8303a9c2a0](https://linux-hardware.org/?probe=8303a9c2a0) | Jan 18, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| Dell          | 0XFRWW A00                  | Desktop     | [2b96d4b6f6](https://linux-hardware.org/?probe=2b96d4b6f6) | Jan 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [011b9a41cd](https://linux-hardware.org/?probe=011b9a41cd) | Jan 18, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [ff6ad7bf11](https://linux-hardware.org/?probe=ff6ad7bf11) | Jan 18, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [533d99e2f1](https://linux-hardware.org/?probe=533d99e2f1) | Jan 18, 2023 |
| Lenovo        | ThinkPad E15 20RD0011RT     | Notebook    | [d27ca45841](https://linux-hardware.org/?probe=d27ca45841) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ec05dd5768](https://linux-hardware.org/?probe=ec05dd5768) | Jan 18, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [01cf6039d0](https://linux-hardware.org/?probe=01cf6039d0) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| Dell          | Precision 3561              | Notebook    | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | Notebook    | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [1b916fe30d](https://linux-hardware.org/?probe=1b916fe30d) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| Lenovo        | Yoga 500-14IHW 80N5         | Notebook    | [e233e8d6d2](https://linux-hardware.org/?probe=e233e8d6d2) | Jan 18, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [4fba90df07](https://linux-hardware.org/?probe=4fba90df07) | Jan 17, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [4a997fa99d](https://linux-hardware.org/?probe=4a997fa99d) | Jan 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [f050195c33](https://linux-hardware.org/?probe=f050195c33) | Jan 17, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [a8fbe01fc5](https://linux-hardware.org/?probe=a8fbe01fc5) | Jan 17, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [8e21ef4b91](https://linux-hardware.org/?probe=8e21ef4b91) | Jan 17, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [469c40ec75](https://linux-hardware.org/?probe=469c40ec75) | Jan 17, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [8753bd8277](https://linux-hardware.org/?probe=8753bd8277) | Jan 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b45cef8a55](https://linux-hardware.org/?probe=b45cef8a55) | Jan 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [3dbc34a913](https://linux-hardware.org/?probe=3dbc34a913) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [681de2b0c1](https://linux-hardware.org/?probe=681de2b0c1) | Jan 17, 2023 |
| Dynabook      | PORTEGE X30W-K              | Convertible | [5c3d7c049e](https://linux-hardware.org/?probe=5c3d7c049e) | Jan 17, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [16be0552b2](https://linux-hardware.org/?probe=16be0552b2) | Jan 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [16c9b323c6](https://linux-hardware.org/?probe=16c9b323c6) | Jan 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b36d7e8eb](https://linux-hardware.org/?probe=7b36d7e8eb) | Jan 17, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [f1ee502754](https://linux-hardware.org/?probe=f1ee502754) | Jan 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0d91852ebf](https://linux-hardware.org/?probe=0d91852ebf) | Jan 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [aeb9ac591c](https://linux-hardware.org/?probe=aeb9ac591c) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [596219796d](https://linux-hardware.org/?probe=596219796d) | Jan 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [93380bb1f5](https://linux-hardware.org/?probe=93380bb1f5) | Jan 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b39c4fc9b7](https://linux-hardware.org/?probe=b39c4fc9b7) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [1c81e8c322](https://linux-hardware.org/?probe=1c81e8c322) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d5843b83af](https://linux-hardware.org/?probe=d5843b83af) | Jan 16, 2023 |
| PC Special... | Recoil II RTX               | Notebook    | [33850c8810](https://linux-hardware.org/?probe=33850c8810) | Jan 16, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [c06c7eedaf](https://linux-hardware.org/?probe=c06c7eedaf) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [b53dd87f87](https://linux-hardware.org/?probe=b53dd87f87) | Jan 16, 2023 |
| Schenker      | XMG CORE 15 (M22)           | Notebook    | [6c2b631f12](https://linux-hardware.org/?probe=6c2b631f12) | Jan 16, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [dd16b56d30](https://linux-hardware.org/?probe=dd16b56d30) | Jan 16, 2023 |
| HP            | 15                          | Notebook    | [ae082994e2](https://linux-hardware.org/?probe=ae082994e2) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [1de96d005a](https://linux-hardware.org/?probe=1de96d005a) | Jan 16, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [3390ce67a2](https://linux-hardware.org/?probe=3390ce67a2) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [f0eab1c81a](https://linux-hardware.org/?probe=f0eab1c81a) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e1aa5d3186](https://linux-hardware.org/?probe=e1aa5d3186) | Jan 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1a51848ffb](https://linux-hardware.org/?probe=1a51848ffb) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [b36eb94e80](https://linux-hardware.org/?probe=b36eb94e80) | Jan 16, 2023 |
| Dell          | 0M863N A01                  | Desktop     | [1dff7cb016](https://linux-hardware.org/?probe=1dff7cb016) | Jan 16, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4d2e9f3ee4](https://linux-hardware.org/?probe=4d2e9f3ee4) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | Notebook    | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9ac2f0ab83](https://linux-hardware.org/?probe=9ac2f0ab83) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b68ce1375d](https://linux-hardware.org/?probe=b68ce1375d) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [4850c49a4a](https://linux-hardware.org/?probe=4850c49a4a) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [448ae92dc8](https://linux-hardware.org/?probe=448ae92dc8) | Jan 15, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [978682daa6](https://linux-hardware.org/?probe=978682daa6) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [972e3e026a](https://linux-hardware.org/?probe=972e3e026a) | Jan 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [57d99b139f](https://linux-hardware.org/?probe=57d99b139f) | Jan 15, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [cefbe7ee6e](https://linux-hardware.org/?probe=cefbe7ee6e) | Jan 15, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [fcc6481e2a](https://linux-hardware.org/?probe=fcc6481e2a) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [983230429d](https://linux-hardware.org/?probe=983230429d) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | Notebook    | [ebe90b5052](https://linux-hardware.org/?probe=ebe90b5052) | Jan 15, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [20625ce99d](https://linux-hardware.org/?probe=20625ce99d) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | Notebook    | [fe5c9c2425](https://linux-hardware.org/?probe=fe5c9c2425) | Jan 14, 2023 |
| AZW           | GTR V02                     | Desktop     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | Notebook    | [649546bc61](https://linux-hardware.org/?probe=649546bc61) | Jan 14, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [4ef76b2644](https://linux-hardware.org/?probe=4ef76b2644) | Jan 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [86fff559f5](https://linux-hardware.org/?probe=86fff559f5) | Jan 14, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | Notebook    | [bcbf941284](https://linux-hardware.org/?probe=bcbf941284) | Jan 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [efffe2d61b](https://linux-hardware.org/?probe=efffe2d61b) | Jan 14, 2023 |
| MSI           | PS63 Modern 8RC             | Notebook    | [e55e0d9d0a](https://linux-hardware.org/?probe=e55e0d9d0a) | Jan 14, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [3325b8ab60](https://linux-hardware.org/?probe=3325b8ab60) | Jan 14, 2023 |
| Dell          | 0W2F8G A01                  | Desktop     | [999fcca032](https://linux-hardware.org/?probe=999fcca032) | Jan 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [03f0709b21](https://linux-hardware.org/?probe=03f0709b21) | Jan 14, 2023 |
| System76      | Oryx Pro                    | Notebook    | [f706b667bb](https://linux-hardware.org/?probe=f706b667bb) | Jan 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [5047da7461](https://linux-hardware.org/?probe=5047da7461) | Jan 14, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [e292f699eb](https://linux-hardware.org/?probe=e292f699eb) | Jan 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9096450d56](https://linux-hardware.org/?probe=9096450d56) | Jan 14, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [6ae0a203a7](https://linux-hardware.org/?probe=6ae0a203a7) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [76ce1a38ba](https://linux-hardware.org/?probe=76ce1a38ba) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [0d01d0023b](https://linux-hardware.org/?probe=0d01d0023b) | Jan 13, 2023 |
| Dell          | Latitude 7430               | Notebook    | [9caa5939ef](https://linux-hardware.org/?probe=9caa5939ef) | Jan 13, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [61c432b134](https://linux-hardware.org/?probe=61c432b134) | Jan 13, 2023 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [40acaf3525](https://linux-hardware.org/?probe=40acaf3525) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| Supermicro    | X10DRi-LN4+                 | Server      | [f00173e1e2](https://linux-hardware.org/?probe=f00173e1e2) | Jan 13, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [b2c96e31d9](https://linux-hardware.org/?probe=b2c96e31d9) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [810b2daeef](https://linux-hardware.org/?probe=810b2daeef) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [f954b55a5c](https://linux-hardware.org/?probe=f954b55a5c) | Jan 13, 2023 |
| Toshiba       | Satellite L855D             | Notebook    | [0606d04520](https://linux-hardware.org/?probe=0606d04520) | Jan 13, 2023 |
| Dell          | Inspiron 5721               | Notebook    | [b9435f9f7d](https://linux-hardware.org/?probe=b9435f9f7d) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d4b0530f79](https://linux-hardware.org/?probe=d4b0530f79) | Jan 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [64c403ce6d](https://linux-hardware.org/?probe=64c403ce6d) | Jan 13, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | Notebook    | [28d821da5f](https://linux-hardware.org/?probe=28d821da5f) | Jan 13, 2023 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [4cf36f7404](https://linux-hardware.org/?probe=4cf36f7404) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f9d244586a](https://linux-hardware.org/?probe=f9d244586a) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [033a92981f](https://linux-hardware.org/?probe=033a92981f) | Jan 13, 2023 |
| HP            | 3047h                       | Desktop     | [5eb46c9039](https://linux-hardware.org/?probe=5eb46c9039) | Jan 12, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [150f12dceb](https://linux-hardware.org/?probe=150f12dceb) | Jan 12, 2023 |
| Dell          | G15 5520                    | Notebook    | [1aeaf74f9a](https://linux-hardware.org/?probe=1aeaf74f9a) | Jan 12, 2023 |
| HP            | 3047h                       | Desktop     | [0c035c1a04](https://linux-hardware.org/?probe=0c035c1a04) | Jan 12, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [f38e5f2a4e](https://linux-hardware.org/?probe=f38e5f2a4e) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Nitro AN517-42              | Notebook    | [c8440739f9](https://linux-hardware.org/?probe=c8440739f9) | Jan 12, 2023 |
| Samsung       | 950QED                      | Convertible | [0afc7e983a](https://linux-hardware.org/?probe=0afc7e983a) | Jan 12, 2023 |
| Dell          | Latitude E5550              | Notebook    | [0b14eb18d9](https://linux-hardware.org/?probe=0b14eb18d9) | Jan 12, 2023 |
| Samsung       | 950QED                      | Convertible | [9fe5e28749](https://linux-hardware.org/?probe=9fe5e28749) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2349W1C       | Notebook    | [1f310a8a2e](https://linux-hardware.org/?probe=1f310a8a2e) | Jan 12, 2023 |
| Unknown       | X79                         | Desktop     | [62bf02da9d](https://linux-hardware.org/?probe=62bf02da9d) | Jan 12, 2023 |
| Unknown       | X79                         | Desktop     | [aed457b56c](https://linux-hardware.org/?probe=aed457b56c) | Jan 12, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [28d13d17ba](https://linux-hardware.org/?probe=28d13d17ba) | Jan 12, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [3cfb7d9e7c](https://linux-hardware.org/?probe=3cfb7d9e7c) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [fad743f278](https://linux-hardware.org/?probe=fad743f278) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | Desktop     | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1270cfda4e](https://linux-hardware.org/?probe=1270cfda4e) | Jan 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8c1eb7fc02](https://linux-hardware.org/?probe=8c1eb7fc02) | Jan 11, 2023 |
| Dell          | Latitude E5550              | Notebook    | [5e76d378f9](https://linux-hardware.org/?probe=5e76d378f9) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f84f79fce7](https://linux-hardware.org/?probe=f84f79fce7) | Jan 11, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [ec0f3564ed](https://linux-hardware.org/?probe=ec0f3564ed) | Jan 11, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [a436e3e89f](https://linux-hardware.org/?probe=a436e3e89f) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c79ad1fc10](https://linux-hardware.org/?probe=c79ad1fc10) | Jan 11, 2023 |
| Acer          | Predator G9-591             | Notebook    | [aa9794813e](https://linux-hardware.org/?probe=aa9794813e) | Jan 11, 2023 |
| Dell          | Latitude E7440              | Notebook    | [bfdc9dfc63](https://linux-hardware.org/?probe=bfdc9dfc63) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [815ee96451](https://linux-hardware.org/?probe=815ee96451) | Jan 11, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [790736a10e](https://linux-hardware.org/?probe=790736a10e) | Jan 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fdb726b276](https://linux-hardware.org/?probe=fdb726b276) | Jan 11, 2023 |
| ASRock        | Z87 Extreme6                | Desktop     | [49e3d87de4](https://linux-hardware.org/?probe=49e3d87de4) | Jan 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [11aac46bdc](https://linux-hardware.org/?probe=11aac46bdc) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [dc3e0fffe7](https://linux-hardware.org/?probe=dc3e0fffe7) | Jan 10, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [3e54ca06f5](https://linux-hardware.org/?probe=3e54ca06f5) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [53d6bec0e8](https://linux-hardware.org/?probe=53d6bec0e8) | Jan 10, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [760cc2eaed](https://linux-hardware.org/?probe=760cc2eaed) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| Lenovo        | YG530-14ARR 81H9            | Convertible | [4af08e8513](https://linux-hardware.org/?probe=4af08e8513) | Jan 10, 2023 |
| Lenovo        | ThinkPad T590 20N5S4R800    | Notebook    | [51d6d75e64](https://linux-hardware.org/?probe=51d6d75e64) | Jan 10, 2023 |
| ASUSTek       | FX503VD                     | Notebook    | [c3a958527e](https://linux-hardware.org/?probe=c3a958527e) | Jan 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [0a5f45ca97](https://linux-hardware.org/?probe=0a5f45ca97) | Jan 10, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [37b5b1648e](https://linux-hardware.org/?probe=37b5b1648e) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [e16ef8937b](https://linux-hardware.org/?probe=e16ef8937b) | Jan 09, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [ef83299ad4](https://linux-hardware.org/?probe=ef83299ad4) | Jan 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [7c7c8175c0](https://linux-hardware.org/?probe=7c7c8175c0) | Jan 09, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [918dc5f283](https://linux-hardware.org/?probe=918dc5f283) | Jan 09, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [95cfb68187](https://linux-hardware.org/?probe=95cfb68187) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [e6cb9446f5](https://linux-hardware.org/?probe=e6cb9446f5) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [8ec4c19bf3](https://linux-hardware.org/?probe=8ec4c19bf3) | Jan 09, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [2fa89881b4](https://linux-hardware.org/?probe=2fa89881b4) | Jan 09, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2e13f150e6](https://linux-hardware.org/?probe=2e13f150e6) | Jan 09, 2023 |
| AZW           | GTR V02                     | Desktop     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [0b2f591376](https://linux-hardware.org/?probe=0b2f591376) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6e756926b8](https://linux-hardware.org/?probe=6e756926b8) | Jan 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d7820d12e5](https://linux-hardware.org/?probe=d7820d12e5) | Jan 09, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [92a4be502c](https://linux-hardware.org/?probe=92a4be502c) | Jan 09, 2023 |
| Acer          | Iconia W700                 | Notebook    | [bcfec36896](https://linux-hardware.org/?probe=bcfec36896) | Jan 09, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | Notebook    | [8c76c72880](https://linux-hardware.org/?probe=8c76c72880) | Jan 08, 2023 |
| HP            | ProBook 6465b               | Notebook    | [336f10e70b](https://linux-hardware.org/?probe=336f10e70b) | Jan 08, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [853f3c06ce](https://linux-hardware.org/?probe=853f3c06ce) | Jan 08, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [50e9caee7f](https://linux-hardware.org/?probe=50e9caee7f) | Jan 08, 2023 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [1ca4c751d8](https://linux-hardware.org/?probe=1ca4c751d8) | Jan 08, 2023 |
| Framework     | Laptop                      | Notebook    | [0c13e3ab8d](https://linux-hardware.org/?probe=0c13e3ab8d) | Jan 08, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [b4ed141fd3](https://linux-hardware.org/?probe=b4ed141fd3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | Notebook    | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [d2e10cee5b](https://linux-hardware.org/?probe=d2e10cee5b) | Jan 08, 2023 |
| Dell          | Latitude 3450               | Notebook    | [e4e8bee1cb](https://linux-hardware.org/?probe=e4e8bee1cb) | Jan 08, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [d3e35671cd](https://linux-hardware.org/?probe=d3e35671cd) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [afd852d260](https://linux-hardware.org/?probe=afd852d260) | Jan 08, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [b732d98167](https://linux-hardware.org/?probe=b732d98167) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [5f3e927024](https://linux-hardware.org/?probe=5f3e927024) | Jan 08, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [206359e4ad](https://linux-hardware.org/?probe=206359e4ad) | Jan 08, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [922b7a2305](https://linux-hardware.org/?probe=922b7a2305) | Jan 08, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [f75fea559f](https://linux-hardware.org/?probe=f75fea559f) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [eed9db8255](https://linux-hardware.org/?probe=eed9db8255) | Jan 08, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [6290949f56](https://linux-hardware.org/?probe=6290949f56) | Jan 08, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [a6c731c83b](https://linux-hardware.org/?probe=a6c731c83b) | Jan 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b0a36f054e](https://linux-hardware.org/?probe=b0a36f054e) | Jan 08, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [a43647cad6](https://linux-hardware.org/?probe=a43647cad6) | Jan 08, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [a33d9c5a74](https://linux-hardware.org/?probe=a33d9c5a74) | Jan 07, 2023 |
| Dell          | Latitude 9430               | Convertible | [d04e9626cf](https://linux-hardware.org/?probe=d04e9626cf) | Jan 07, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [595e6fa89a](https://linux-hardware.org/?probe=595e6fa89a) | Jan 07, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [f0a688060c](https://linux-hardware.org/?probe=f0a688060c) | Jan 07, 2023 |
| Lenovo        | ThinkPad T530 2392CTO       | Notebook    | [8c1cf48875](https://linux-hardware.org/?probe=8c1cf48875) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| Framework     | Laptop                      | Notebook    | [cfabfdec3c](https://linux-hardware.org/?probe=cfabfdec3c) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| System76      | Lemur Pro                   | Notebook    | [36156d9aa7](https://linux-hardware.org/?probe=36156d9aa7) | Jan 07, 2023 |
| Acer          | FMCP7A-ION-LE               | Desktop     | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| Dell          | Inspiron 13 5320            | Notebook    | [0007a36030](https://linux-hardware.org/?probe=0007a36030) | Jan 07, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [82052bbfcb](https://linux-hardware.org/?probe=82052bbfcb) | Jan 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [99e2769927](https://linux-hardware.org/?probe=99e2769927) | Jan 07, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [fff1e286b7](https://linux-hardware.org/?probe=fff1e286b7) | Jan 07, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [dfd35ce9ca](https://linux-hardware.org/?probe=dfd35ce9ca) | Jan 07, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [bf4c8770e7](https://linux-hardware.org/?probe=bf4c8770e7) | Jan 07, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [ff95fa094b](https://linux-hardware.org/?probe=ff95fa094b) | Jan 06, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1fc8d104f7](https://linux-hardware.org/?probe=1fc8d104f7) | Jan 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [0a6589c07d](https://linux-hardware.org/?probe=0a6589c07d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ab29e81efd](https://linux-hardware.org/?probe=ab29e81efd) | Jan 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [684653e302](https://linux-hardware.org/?probe=684653e302) | Jan 06, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [896288776d](https://linux-hardware.org/?probe=896288776d) | Jan 06, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [68e299de33](https://linux-hardware.org/?probe=68e299de33) | Jan 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9946b25232](https://linux-hardware.org/?probe=9946b25232) | Jan 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fd5120fea6](https://linux-hardware.org/?probe=fd5120fea6) | Jan 06, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| Lenovo        | ThinkPad T430 2349KB4       | Notebook    | [4546ecbe85](https://linux-hardware.org/?probe=4546ecbe85) | Jan 06, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6743fa1b](https://linux-hardware.org/?probe=ec6743fa1b) | Jan 06, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [c84d3b6b03](https://linux-hardware.org/?probe=c84d3b6b03) | Jan 06, 2023 |
| Dell          | G15 5525                    | Notebook    | [2c61cbc942](https://linux-hardware.org/?probe=2c61cbc942) | Jan 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bcc4cba81a](https://linux-hardware.org/?probe=bcc4cba81a) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cddb2a7b81](https://linux-hardware.org/?probe=cddb2a7b81) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [e417e45252](https://linux-hardware.org/?probe=e417e45252) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [e7b27ba60c](https://linux-hardware.org/?probe=e7b27ba60c) | Jan 06, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [7fe70dc4c8](https://linux-hardware.org/?probe=7fe70dc4c8) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [c47405aaf4](https://linux-hardware.org/?probe=c47405aaf4) | Jan 05, 2023 |
| Lenovo        | ThinkPad X220 4290KJ6       | Notebook    | [8296e61afd](https://linux-hardware.org/?probe=8296e61afd) | Jan 05, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [77651b16db](https://linux-hardware.org/?probe=77651b16db) | Jan 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [a559464349](https://linux-hardware.org/?probe=a559464349) | Jan 05, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [0ae0a8d91b](https://linux-hardware.org/?probe=0ae0a8d91b) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | Notebook    | [28af5637ef](https://linux-hardware.org/?probe=28af5637ef) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | Notebook    | [4605f322cb](https://linux-hardware.org/?probe=4605f322cb) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a2ec6616aa](https://linux-hardware.org/?probe=a2ec6616aa) | Jan 05, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [24d21ee9f1](https://linux-hardware.org/?probe=24d21ee9f1) | Jan 05, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [b7855a84cf](https://linux-hardware.org/?probe=b7855a84cf) | Jan 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1964dbc8e7](https://linux-hardware.org/?probe=1964dbc8e7) | Jan 05, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [d1c9231969](https://linux-hardware.org/?probe=d1c9231969) | Jan 05, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | Notebook    | [343d0f4c48](https://linux-hardware.org/?probe=343d0f4c48) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [39f45e87d1](https://linux-hardware.org/?probe=39f45e87d1) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [2f4bb5b17d](https://linux-hardware.org/?probe=2f4bb5b17d) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [272d23ec5d](https://linux-hardware.org/?probe=272d23ec5d) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [76f2ef98b9](https://linux-hardware.org/?probe=76f2ef98b9) | Jan 04, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [50d8f0c1cb](https://linux-hardware.org/?probe=50d8f0c1cb) | Jan 04, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [4c54844f40](https://linux-hardware.org/?probe=4c54844f40) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | Desktop     | [4453ef0d86](https://linux-hardware.org/?probe=4453ef0d86) | Jan 04, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [5c352967e4](https://linux-hardware.org/?probe=5c352967e4) | Jan 04, 2023 |
| HP            | Notebook                    | Notebook    | [679c0bfbe8](https://linux-hardware.org/?probe=679c0bfbe8) | Jan 04, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [6d6e710ac3](https://linux-hardware.org/?probe=6d6e710ac3) | Jan 04, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [7f62577241](https://linux-hardware.org/?probe=7f62577241) | Jan 04, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [0968211c5b](https://linux-hardware.org/?probe=0968211c5b) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [4195800fa5](https://linux-hardware.org/?probe=4195800fa5) | Jan 04, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [6a38362bbe](https://linux-hardware.org/?probe=6a38362bbe) | Jan 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [b363093f89](https://linux-hardware.org/?probe=b363093f89) | Jan 04, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [ad776cdf84](https://linux-hardware.org/?probe=ad776cdf84) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2849ffe456](https://linux-hardware.org/?probe=2849ffe456) | Jan 04, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [5741654cdc](https://linux-hardware.org/?probe=5741654cdc) | Jan 04, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [8e30a9a43e](https://linux-hardware.org/?probe=8e30a9a43e) | Jan 04, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [036ae164e8](https://linux-hardware.org/?probe=036ae164e8) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | Desktop     | [e03b53cc0e](https://linux-hardware.org/?probe=e03b53cc0e) | Jan 04, 2023 |
| Clevo         | M815P                       | Notebook    | [7f1503c5e6](https://linux-hardware.org/?probe=7f1503c5e6) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [d788f444ff](https://linux-hardware.org/?probe=d788f444ff) | Jan 03, 2023 |
| HP            | ProBook 6570b               | Notebook    | [875054c6d7](https://linux-hardware.org/?probe=875054c6d7) | Jan 03, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [496bc9b9cd](https://linux-hardware.org/?probe=496bc9b9cd) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [abdf0ab0b9](https://linux-hardware.org/?probe=abdf0ab0b9) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5c14d6ea96](https://linux-hardware.org/?probe=5c14d6ea96) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [40af3a30ca](https://linux-hardware.org/?probe=40af3a30ca) | Jan 03, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | Notebook    | [c621679405](https://linux-hardware.org/?probe=c621679405) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| Microsoft     | Surface Laptop Studio       | Tablet      | [084f1cf7cb](https://linux-hardware.org/?probe=084f1cf7cb) | Jan 03, 2023 |
| Positivo      | POS-EIB85CZ                 | Desktop     | [639f5a2bf7](https://linux-hardware.org/?probe=639f5a2bf7) | Jan 03, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Microsoft     | Surface Laptop Studio       | Tablet      | [ee3dc404e1](https://linux-hardware.org/?probe=ee3dc404e1) | Jan 03, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f1962e0076](https://linux-hardware.org/?probe=f1962e0076) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [d7c57c2bae](https://linux-hardware.org/?probe=d7c57c2bae) | Jan 03, 2023 |
| Toshiba       | Satellite C50-A             | Notebook    | [9b02393248](https://linux-hardware.org/?probe=9b02393248) | Jan 02, 2023 |
| PINE64        | Pinebook Pro                | Soc         | [d8cd86db45](https://linux-hardware.org/?probe=d8cd86db45) | Jan 02, 2023 |
| HP            | Notebook                    | Notebook    | [530e6cfeb9](https://linux-hardware.org/?probe=530e6cfeb9) | Jan 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [386eb7bc28](https://linux-hardware.org/?probe=386eb7bc28) | Jan 02, 2023 |
| Clevo         | M815P                       | Notebook    | [034cecc238](https://linux-hardware.org/?probe=034cecc238) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [7c98c0b00d](https://linux-hardware.org/?probe=7c98c0b00d) | Jan 02, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [daeb060f32](https://linux-hardware.org/?probe=daeb060f32) | Jan 02, 2023 |
| Acer          | Aspire A315-31              | Notebook    | [4a79c65764](https://linux-hardware.org/?probe=4a79c65764) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | X756UXK                     | Notebook    | [f0bc632c50](https://linux-hardware.org/?probe=f0bc632c50) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f85aeab3e5](https://linux-hardware.org/?probe=f85aeab3e5) | Jan 02, 2023 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [f39e3e8350](https://linux-hardware.org/?probe=f39e3e8350) | Jan 02, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [4e900247e4](https://linux-hardware.org/?probe=4e900247e4) | Jan 02, 2023 |
| ASRock        | Z77 Professional            | Desktop     | [bf09b21dc7](https://linux-hardware.org/?probe=bf09b21dc7) | Jan 02, 2023 |
| Dell          | Latitude 7410               | Notebook    | [acb8ce902e](https://linux-hardware.org/?probe=acb8ce902e) | Jan 01, 2023 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [8e9080dc74](https://linux-hardware.org/?probe=8e9080dc74) | Jan 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c753f769b4](https://linux-hardware.org/?probe=c753f769b4) | Jan 01, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [f84116ec07](https://linux-hardware.org/?probe=f84116ec07) | Jan 01, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [033b62b374](https://linux-hardware.org/?probe=033b62b374) | Jan 01, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [752fe53b7c](https://linux-hardware.org/?probe=752fe53b7c) | Jan 01, 2023 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [11f3804cb6](https://linux-hardware.org/?probe=11f3804cb6) | Jan 01, 2023 |
| Fujitsu       | LIFEBOOK U749               | Notebook    | [c09072c09f](https://linux-hardware.org/?probe=c09072c09f) | Jan 01, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [3b6d1593c8](https://linux-hardware.org/?probe=3b6d1593c8) | Jan 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [54089a466b](https://linux-hardware.org/?probe=54089a466b) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [f438866c0d](https://linux-hardware.org/?probe=f438866c0d) | Jan 01, 2023 |
| Lenovo        | ThinkPad X270 20K60018GE    | Notebook    | [a92939c1f5](https://linux-hardware.org/?probe=a92939c1f5) | Jan 01, 2023 |
| Lenovo        | ThinkPad X390 20Q00051GE    | Notebook    | [5b3d1b750d](https://linux-hardware.org/?probe=5b3d1b750d) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [c0fb48bccb](https://linux-hardware.org/?probe=c0fb48bccb) | Dec 31, 2022 |
| System76      | Oryx Pro                    | Notebook    | [0d65e57758](https://linux-hardware.org/?probe=0d65e57758) | Dec 31, 2022 |
| Lenovo        | ThinkPad X390 20Q00051GE    | Notebook    | [775096be09](https://linux-hardware.org/?probe=775096be09) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [322cf5484d](https://linux-hardware.org/?probe=322cf5484d) | Dec 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f16b55ea54](https://linux-hardware.org/?probe=f16b55ea54) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5fbe1632b0](https://linux-hardware.org/?probe=5fbe1632b0) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5a479fed95](https://linux-hardware.org/?probe=5a479fed95) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [591d985e85](https://linux-hardware.org/?probe=591d985e85) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c45e0f54fd](https://linux-hardware.org/?probe=c45e0f54fd) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| ASRock        | X79 Extreme6                | Desktop     | [5ea31811b4](https://linux-hardware.org/?probe=5ea31811b4) | Dec 30, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [4b3b106bee](https://linux-hardware.org/?probe=4b3b106bee) | Dec 30, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [4dba3b7c55](https://linux-hardware.org/?probe=4dba3b7c55) | Dec 30, 2022 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [f7ed4a6609](https://linux-hardware.org/?probe=f7ed4a6609) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d2cd50a2a6](https://linux-hardware.org/?probe=d2cd50a2a6) | Dec 30, 2022 |
| Timi          | A35S                        | Notebook    | [c62c9ae956](https://linux-hardware.org/?probe=c62c9ae956) | Dec 30, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [ae7d821823](https://linux-hardware.org/?probe=ae7d821823) | Dec 30, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [19b4bfd852](https://linux-hardware.org/?probe=19b4bfd852) | Dec 30, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [68b3b51892](https://linux-hardware.org/?probe=68b3b51892) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| MSI           | GP72MVR 7RFX                | Notebook    | [cefedef93c](https://linux-hardware.org/?probe=cefedef93c) | Dec 30, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [da812c8fa2](https://linux-hardware.org/?probe=da812c8fa2) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [b4a7d759f7](https://linux-hardware.org/?probe=b4a7d759f7) | Dec 30, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [770c5eee84](https://linux-hardware.org/?probe=770c5eee84) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8289d108fb](https://linux-hardware.org/?probe=8289d108fb) | Dec 30, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [eafab9edba](https://linux-hardware.org/?probe=eafab9edba) | Dec 30, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [d3daa756b4](https://linux-hardware.org/?probe=d3daa756b4) | Dec 30, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [bdc5158ffb](https://linux-hardware.org/?probe=bdc5158ffb) | Dec 29, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [3303908896](https://linux-hardware.org/?probe=3303908896) | Dec 29, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [b34f09894d](https://linux-hardware.org/?probe=b34f09894d) | Dec 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [51f9de5f53](https://linux-hardware.org/?probe=51f9de5f53) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [ed5315b768](https://linux-hardware.org/?probe=ed5315b768) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | Desktop     | [4cf9d40c0d](https://linux-hardware.org/?probe=4cf9d40c0d) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [3c627bc707](https://linux-hardware.org/?probe=3c627bc707) | Dec 29, 2022 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [b246257695](https://linux-hardware.org/?probe=b246257695) | Dec 29, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [2154a332b0](https://linux-hardware.org/?probe=2154a332b0) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | Desktop     | [7e53808767](https://linux-hardware.org/?probe=7e53808767) | Dec 29, 2022 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [6c67e1435e](https://linux-hardware.org/?probe=6c67e1435e) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [12c052156c](https://linux-hardware.org/?probe=12c052156c) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | Notebook    | [51bb19bbf2](https://linux-hardware.org/?probe=51bb19bbf2) | Dec 29, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [74f8dcfbb4](https://linux-hardware.org/?probe=74f8dcfbb4) | Dec 29, 2022 |
| Schenker      | VISION 16 Pro (L22)         | Notebook    | [bbd6e1daf5](https://linux-hardware.org/?probe=bbd6e1daf5) | Dec 29, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [d5d0e740c1](https://linux-hardware.org/?probe=d5d0e740c1) | Dec 29, 2022 |
| Schenker      | VISION 16 Pro (L22)         | Notebook    | [2412713729](https://linux-hardware.org/?probe=2412713729) | Dec 29, 2022 |
| Dell          | G5 5590                     | Notebook    | [58bd69f40b](https://linux-hardware.org/?probe=58bd69f40b) | Dec 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [8901206dd0](https://linux-hardware.org/?probe=8901206dd0) | Dec 28, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [269d455191](https://linux-hardware.org/?probe=269d455191) | Dec 28, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [e23c23e61f](https://linux-hardware.org/?probe=e23c23e61f) | Dec 28, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [5c4856e5c8](https://linux-hardware.org/?probe=5c4856e5c8) | Dec 28, 2022 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [0852995abb](https://linux-hardware.org/?probe=0852995abb) | Dec 28, 2022 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [6e3a112190](https://linux-hardware.org/?probe=6e3a112190) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [24b822291e](https://linux-hardware.org/?probe=24b822291e) | Dec 28, 2022 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [e12c24fd74](https://linux-hardware.org/?probe=e12c24fd74) | Dec 28, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0dc3c192fd](https://linux-hardware.org/?probe=0dc3c192fd) | Dec 28, 2022 |
| Google        | Voxel rev3                  | Notebook    | [430244f188](https://linux-hardware.org/?probe=430244f188) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [6240bc3677](https://linux-hardware.org/?probe=6240bc3677) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [f5689c6edc](https://linux-hardware.org/?probe=f5689c6edc) | Dec 28, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [dbc2d2fc6f](https://linux-hardware.org/?probe=dbc2d2fc6f) | Dec 28, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [790b3dcdde](https://linux-hardware.org/?probe=790b3dcdde) | Dec 28, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [7bb247e453](https://linux-hardware.org/?probe=7bb247e453) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| pine64,pin... | Pinebook Pro                | Soc         | [931d20e8ae](https://linux-hardware.org/?probe=931d20e8ae) | Dec 28, 2022 |
| Gigabyte      | B365M D2V                   | Desktop     | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| HP            | G62                         | Notebook    | [05ad917600](https://linux-hardware.org/?probe=05ad917600) | Dec 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f5ac2a0028](https://linux-hardware.org/?probe=f5ac2a0028) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [826a683b58](https://linux-hardware.org/?probe=826a683b58) | Dec 28, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | Notebook    | [00a92c3818](https://linux-hardware.org/?probe=00a92c3818) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [7aab4546f6](https://linux-hardware.org/?probe=7aab4546f6) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [56e25a5805](https://linux-hardware.org/?probe=56e25a5805) | Dec 28, 2022 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [3c25f43c23](https://linux-hardware.org/?probe=3c25f43c23) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| MSI           | GL63 8RC                    | Notebook    | [0b973e252f](https://linux-hardware.org/?probe=0b973e252f) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Itautec       | ST 4265                     | Desktop     | [38e4a07f9a](https://linux-hardware.org/?probe=38e4a07f9a) | Dec 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [f2751df7ec](https://linux-hardware.org/?probe=f2751df7ec) | Dec 27, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [4eda9a1749](https://linux-hardware.org/?probe=4eda9a1749) | Dec 27, 2022 |
| Dell          | Inspiron 15 3525            | Notebook    | [64a70af984](https://linux-hardware.org/?probe=64a70af984) | Dec 27, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [d4fff49f31](https://linux-hardware.org/?probe=d4fff49f31) | Dec 27, 2022 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [d7daff3ed1](https://linux-hardware.org/?probe=d7daff3ed1) | Dec 27, 2022 |
| Timi          | RedmiBook 15                | Notebook    | [cf38b14bc5](https://linux-hardware.org/?probe=cf38b14bc5) | Dec 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [e41c8ca4ee](https://linux-hardware.org/?probe=e41c8ca4ee) | Dec 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [f2c052dde9](https://linux-hardware.org/?probe=f2c052dde9) | Dec 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [2f5381fa26](https://linux-hardware.org/?probe=2f5381fa26) | Dec 26, 2022 |
| Itautec       | ST 4265                     | Desktop     | [8323542129](https://linux-hardware.org/?probe=8323542129) | Dec 26, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [dfedb566ff](https://linux-hardware.org/?probe=dfedb566ff) | Dec 26, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [812d6eb07e](https://linux-hardware.org/?probe=812d6eb07e) | Dec 26, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c7babe827f](https://linux-hardware.org/?probe=c7babe827f) | Dec 26, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [9d544fbcd4](https://linux-hardware.org/?probe=9d544fbcd4) | Dec 26, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [4e393c7334](https://linux-hardware.org/?probe=4e393c7334) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [ce352bf1b1](https://linux-hardware.org/?probe=ce352bf1b1) | Dec 26, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [e763dd5dfe](https://linux-hardware.org/?probe=e763dd5dfe) | Dec 26, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [3c2a7f9115](https://linux-hardware.org/?probe=3c2a7f9115) | Dec 26, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [d1938219e9](https://linux-hardware.org/?probe=d1938219e9) | Dec 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8d1181c71b](https://linux-hardware.org/?probe=8d1181c71b) | Dec 26, 2022 |
| Dell          | Latitude 5580               | Notebook    | [72c0e42aeb](https://linux-hardware.org/?probe=72c0e42aeb) | Dec 26, 2022 |
| Acer          | Aspire A315-59              | Notebook    | [6625ce058f](https://linux-hardware.org/?probe=6625ce058f) | Dec 25, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [2df0678d78](https://linux-hardware.org/?probe=2df0678d78) | Dec 25, 2022 |
| HP            | ProBook 6465b               | Notebook    | [d0f5218f72](https://linux-hardware.org/?probe=d0f5218f72) | Dec 25, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [4c97c87b61](https://linux-hardware.org/?probe=4c97c87b61) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [628cefc78a](https://linux-hardware.org/?probe=628cefc78a) | Dec 25, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [e9dbd838ec](https://linux-hardware.org/?probe=e9dbd838ec) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b6def743ea](https://linux-hardware.org/?probe=b6def743ea) | Dec 25, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [46705eb79f](https://linux-hardware.org/?probe=46705eb79f) | Dec 25, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [3d555f9bee](https://linux-hardware.org/?probe=3d555f9bee) | Dec 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [6c809c224c](https://linux-hardware.org/?probe=6c809c224c) | Dec 24, 2022 |
| Dell          | Latitude 5510               | Notebook    | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c7d8ce8f80](https://linux-hardware.org/?probe=c7d8ce8f80) | Dec 24, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [a48a2f6362](https://linux-hardware.org/?probe=a48a2f6362) | Dec 24, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [e853f645cf](https://linux-hardware.org/?probe=e853f645cf) | Dec 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| HP            | Pavilion g6                 | Notebook    | [71d7947da6](https://linux-hardware.org/?probe=71d7947da6) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| MSI           | Z270M MORTAR                | Desktop     | [70564a2846](https://linux-hardware.org/?probe=70564a2846) | Dec 24, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0AY0... | Notebook    | [28e67f37bc](https://linux-hardware.org/?probe=28e67f37bc) | Dec 24, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [bf8f02ac85](https://linux-hardware.org/?probe=bf8f02ac85) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f5fa069144](https://linux-hardware.org/?probe=f5fa069144) | Dec 24, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [ea57f4aa3a](https://linux-hardware.org/?probe=ea57f4aa3a) | Dec 24, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [926850a516](https://linux-hardware.org/?probe=926850a516) | Dec 24, 2022 |
| Dell          | Latitude 5420               | Notebook    | [201e81d0ed](https://linux-hardware.org/?probe=201e81d0ed) | Dec 23, 2022 |
| Dell          | Latitude 5420               | Notebook    | [9fd9875465](https://linux-hardware.org/?probe=9fd9875465) | Dec 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f114731a78](https://linux-hardware.org/?probe=f114731a78) | Dec 23, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [d933b1a80b](https://linux-hardware.org/?probe=d933b1a80b) | Dec 23, 2022 |
| Jooyon Tec... | J6BF                        | Notebook    | [dabe200abe](https://linux-hardware.org/?probe=dabe200abe) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | Notebook    | [756390ae0c](https://linux-hardware.org/?probe=756390ae0c) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | Notebook    | [c2dd56664a](https://linux-hardware.org/?probe=c2dd56664a) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [627186e9e8](https://linux-hardware.org/?probe=627186e9e8) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| Samsung       | 730QED                      | Convertible | [0c36621efa](https://linux-hardware.org/?probe=0c36621efa) | Dec 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [88df914367](https://linux-hardware.org/?probe=88df914367) | Dec 23, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [77e30fee83](https://linux-hardware.org/?probe=77e30fee83) | Dec 23, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [a208b5598e](https://linux-hardware.org/?probe=a208b5598e) | Dec 22, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [cccd3d01d7](https://linux-hardware.org/?probe=cccd3d01d7) | Dec 22, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [16b14098bf](https://linux-hardware.org/?probe=16b14098bf) | Dec 22, 2022 |
| Acer          | Aspire V5-571               | Notebook    | [b4de144f3e](https://linux-hardware.org/?probe=b4de144f3e) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [677cb5b0b3](https://linux-hardware.org/?probe=677cb5b0b3) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| AZW           | GTR V01                     | Mini pc     | [7502622c61](https://linux-hardware.org/?probe=7502622c61) | Dec 22, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [2b25ab8790](https://linux-hardware.org/?probe=2b25ab8790) | Dec 22, 2022 |
| ASRock        | H470M Pro4                  | Desktop     | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6eb006d2d4](https://linux-hardware.org/?probe=6eb006d2d4) | Dec 22, 2022 |
| GPD           | P3 MAX                      | Notebook    | [9069ed5580](https://linux-hardware.org/?probe=9069ed5580) | Dec 22, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [6db25ba5ca](https://linux-hardware.org/?probe=6db25ba5ca) | Dec 22, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [fb60e7984c](https://linux-hardware.org/?probe=fb60e7984c) | Dec 21, 2022 |
| ASUSTek       | X450CA                      | Notebook    | [5b793f14ff](https://linux-hardware.org/?probe=5b793f14ff) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [f39488c597](https://linux-hardware.org/?probe=f39488c597) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [0243df6ce4](https://linux-hardware.org/?probe=0243df6ce4) | Dec 21, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [5bc62fc208](https://linux-hardware.org/?probe=5bc62fc208) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [9c88ffc394](https://linux-hardware.org/?probe=9c88ffc394) | Dec 21, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | Notebook    | [77c9275988](https://linux-hardware.org/?probe=77c9275988) | Dec 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [ec20f98178](https://linux-hardware.org/?probe=ec20f98178) | Dec 21, 2022 |
| HP            | 8266                        | Desktop     | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [203652b6dd](https://linux-hardware.org/?probe=203652b6dd) | Dec 21, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | Notebook    | [1f1c718c61](https://linux-hardware.org/?probe=1f1c718c61) | Dec 21, 2022 |
| Timi          | Mi NoteBook Pro             | Notebook    | [b5bbb4f410](https://linux-hardware.org/?probe=b5bbb4f410) | Dec 21, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [2d446beedf](https://linux-hardware.org/?probe=2d446beedf) | Dec 21, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [8428e68855](https://linux-hardware.org/?probe=8428e68855) | Dec 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bd7ed31b20](https://linux-hardware.org/?probe=bd7ed31b20) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [f5f6093483](https://linux-hardware.org/?probe=f5f6093483) | Dec 21, 2022 |
| Dell          | Latitude 3420               | Notebook    | [99d501d768](https://linux-hardware.org/?probe=99d501d768) | Dec 20, 2022 |
| Intel         | H81                         | Desktop     | [747dd5e27a](https://linux-hardware.org/?probe=747dd5e27a) | Dec 20, 2022 |
| ASRock        | Z790 Pro RS WiFi            | Desktop     | [d54c198ec8](https://linux-hardware.org/?probe=d54c198ec8) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | Notebook    | [383b0f3311](https://linux-hardware.org/?probe=383b0f3311) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| HP            | ZBook 15                    | Notebook    | [a3bf671d64](https://linux-hardware.org/?probe=a3bf671d64) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Gigabyte      | GA-A75M-UD2H                | Desktop     | [f7e97a6c6c](https://linux-hardware.org/?probe=f7e97a6c6c) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [e04881408e](https://linux-hardware.org/?probe=e04881408e) | Dec 20, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [005d388376](https://linux-hardware.org/?probe=005d388376) | Dec 20, 2022 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [dbcde72217](https://linux-hardware.org/?probe=dbcde72217) | Dec 20, 2022 |
| Lenovo        | ThinkPad E15 20RD0011RT     | Notebook    | [bbfea042cd](https://linux-hardware.org/?probe=bbfea042cd) | Dec 20, 2022 |
| HP            | Pavilion dv6                | Notebook    | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9451dc3035](https://linux-hardware.org/?probe=9451dc3035) | Dec 20, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | Notebook    | [011d3e746d](https://linux-hardware.org/?probe=011d3e746d) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [60dbf09ee4](https://linux-hardware.org/?probe=60dbf09ee4) | Dec 20, 2022 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [3161a64c4b](https://linux-hardware.org/?probe=3161a64c4b) | Dec 19, 2022 |
| ASUSTek       | Zenbook UP6502ZD_UP6502Z... | Convertible | [6044a618cf](https://linux-hardware.org/?probe=6044a618cf) | Dec 19, 2022 |
| ATOPNUC       | MA90                        | Mini pc     | [8c397c3784](https://linux-hardware.org/?probe=8c397c3784) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [b30bf77d27](https://linux-hardware.org/?probe=b30bf77d27) | Dec 19, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [57d06c0f37](https://linux-hardware.org/?probe=57d06c0f37) | Dec 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [c67b4d2b31](https://linux-hardware.org/?probe=c67b4d2b31) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9f5a91c628](https://linux-hardware.org/?probe=9f5a91c628) | Dec 19, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [a2bee3bb3f](https://linux-hardware.org/?probe=a2bee3bb3f) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | Notebook    | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| MSI           | GE63 Raider RGB 8RF         | Notebook    | [a85193c482](https://linux-hardware.org/?probe=a85193c482) | Dec 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [714d2a6dea](https://linux-hardware.org/?probe=714d2a6dea) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [6a964b9d6b](https://linux-hardware.org/?probe=6a964b9d6b) | Dec 19, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [856515e522](https://linux-hardware.org/?probe=856515e522) | Dec 19, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [a5a207a46d](https://linux-hardware.org/?probe=a5a207a46d) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | Notebook    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [97d43c4ad3](https://linux-hardware.org/?probe=97d43c4ad3) | Dec 18, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [4251c08b5d](https://linux-hardware.org/?probe=4251c08b5d) | Dec 18, 2022 |
| Dell          | 0KRC95 A02                  | Desktop     | [e7bb083869](https://linux-hardware.org/?probe=e7bb083869) | Dec 18, 2022 |
| MSI           | Z87M GAMING                 | Desktop     | [bf27014217](https://linux-hardware.org/?probe=bf27014217) | Dec 18, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [757b666913](https://linux-hardware.org/?probe=757b666913) | Dec 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [23b255ed61](https://linux-hardware.org/?probe=23b255ed61) | Dec 18, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [3f76e320c0](https://linux-hardware.org/?probe=3f76e320c0) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [86c9426d80](https://linux-hardware.org/?probe=86c9426d80) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [05fcf7302f](https://linux-hardware.org/?probe=05fcf7302f) | Dec 18, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [e391c56a47](https://linux-hardware.org/?probe=e391c56a47) | Dec 18, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [2b0d31db9d](https://linux-hardware.org/?probe=2b0d31db9d) | Dec 18, 2022 |
| Lenovo        | ThinkPad W550s 20E2000PG... | Notebook    | [938c10075a](https://linux-hardware.org/?probe=938c10075a) | Dec 18, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b712a7bd77](https://linux-hardware.org/?probe=b712a7bd77) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [fed4383ac0](https://linux-hardware.org/?probe=fed4383ac0) | Dec 18, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [53c582a7f6](https://linux-hardware.org/?probe=53c582a7f6) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [561aa4411a](https://linux-hardware.org/?probe=561aa4411a) | Dec 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [56e75d70fa](https://linux-hardware.org/?probe=56e75d70fa) | Dec 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [ad9bf6b390](https://linux-hardware.org/?probe=ad9bf6b390) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c9cc617e08](https://linux-hardware.org/?probe=c9cc617e08) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [f047451b08](https://linux-hardware.org/?probe=f047451b08) | Dec 17, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [acca7c4697](https://linux-hardware.org/?probe=acca7c4697) | Dec 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [49969f1b81](https://linux-hardware.org/?probe=49969f1b81) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [df49d0114f](https://linux-hardware.org/?probe=df49d0114f) | Dec 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [a481e4a590](https://linux-hardware.org/?probe=a481e4a590) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| GPD           | P2 MAX                      | Notebook    | [de5983ec37](https://linux-hardware.org/?probe=de5983ec37) | Dec 17, 2022 |
| ASUSTek       | X45C                        | Notebook    | [80377ba23f](https://linux-hardware.org/?probe=80377ba23f) | Dec 17, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [26ecfabc95](https://linux-hardware.org/?probe=26ecfabc95) | Dec 17, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | Notebook    | [8d631bb590](https://linux-hardware.org/?probe=8d631bb590) | Dec 17, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [1bb7d1bffe](https://linux-hardware.org/?probe=1bb7d1bffe) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [88d55eced8](https://linux-hardware.org/?probe=88d55eced8) | Dec 17, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [5629961182](https://linux-hardware.org/?probe=5629961182) | Dec 17, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [5ab1c3b848](https://linux-hardware.org/?probe=5ab1c3b848) | Dec 17, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [645e7245d4](https://linux-hardware.org/?probe=645e7245d4) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [54132f7285](https://linux-hardware.org/?probe=54132f7285) | Dec 17, 2022 |
| HP            | 82F2 A01                    | Desktop     | [859d719a2a](https://linux-hardware.org/?probe=859d719a2a) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [2ba98da01d](https://linux-hardware.org/?probe=2ba98da01d) | Dec 16, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [50ba321b50](https://linux-hardware.org/?probe=50ba321b50) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a767e0fbf0](https://linux-hardware.org/?probe=a767e0fbf0) | Dec 16, 2022 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [86ab78d0be](https://linux-hardware.org/?probe=86ab78d0be) | Dec 16, 2022 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [a5bdc5f3c9](https://linux-hardware.org/?probe=a5bdc5f3c9) | Dec 16, 2022 |
| Dell          | Vostro 5590                 | Notebook    | [3735674d3f](https://linux-hardware.org/?probe=3735674d3f) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [f048f7fcdb](https://linux-hardware.org/?probe=f048f7fcdb) | Dec 16, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [7c678e18cd](https://linux-hardware.org/?probe=7c678e18cd) | Dec 16, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [ccfc358303](https://linux-hardware.org/?probe=ccfc358303) | Dec 16, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [9bfd668093](https://linux-hardware.org/?probe=9bfd668093) | Dec 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [04bbc083d7](https://linux-hardware.org/?probe=04bbc083d7) | Dec 16, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Lenovo        | ThinkPad W530 243858U       | Notebook    | [9dc4fb1abb](https://linux-hardware.org/?probe=9dc4fb1abb) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [955de558cb](https://linux-hardware.org/?probe=955de558cb) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [e1d8403247](https://linux-hardware.org/?probe=e1d8403247) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [bbf59c4c2a](https://linux-hardware.org/?probe=bbf59c4c2a) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [33d60ebbbe](https://linux-hardware.org/?probe=33d60ebbbe) | Dec 16, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [719f489e01](https://linux-hardware.org/?probe=719f489e01) | Dec 15, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [1749ece1b3](https://linux-hardware.org/?probe=1749ece1b3) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [b8cc280665](https://linux-hardware.org/?probe=b8cc280665) | Dec 15, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [75a24499f9](https://linux-hardware.org/?probe=75a24499f9) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1dd0f2a71f](https://linux-hardware.org/?probe=1dd0f2a71f) | Dec 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [85c38f0af3](https://linux-hardware.org/?probe=85c38f0af3) | Dec 15, 2022 |
| Lenovo        | 31900003 STD                | Desktop     | [81dea8d96e](https://linux-hardware.org/?probe=81dea8d96e) | Dec 15, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| MSI           | B550-A PRO B02              | Desktop     | [3a1ebe10f8](https://linux-hardware.org/?probe=3a1ebe10f8) | Dec 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2e9fac9df4](https://linux-hardware.org/?probe=2e9fac9df4) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [572f0231a5](https://linux-hardware.org/?probe=572f0231a5) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a0d17e1d50](https://linux-hardware.org/?probe=a0d17e1d50) | Dec 15, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [06d690e9fe](https://linux-hardware.org/?probe=06d690e9fe) | Dec 15, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [cb7bfc231e](https://linux-hardware.org/?probe=cb7bfc231e) | Dec 15, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [1380e253a5](https://linux-hardware.org/?probe=1380e253a5) | Dec 14, 2022 |
| Intel         | DQ67SW AAG12527-309         | Desktop     | [3b826b42e0](https://linux-hardware.org/?probe=3b826b42e0) | Dec 14, 2022 |
| Samsung       | 750XDA                      | Notebook    | [0120054e9f](https://linux-hardware.org/?probe=0120054e9f) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [fa4afa166d](https://linux-hardware.org/?probe=fa4afa166d) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [5cde0cdcc4](https://linux-hardware.org/?probe=5cde0cdcc4) | Dec 14, 2022 |
| HP            | 18E4                        | Desktop     | [fece9d45b4](https://linux-hardware.org/?probe=fece9d45b4) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [fe7f585504](https://linux-hardware.org/?probe=fe7f585504) | Dec 14, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [70992b154e](https://linux-hardware.org/?probe=70992b154e) | Dec 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [b2d808ab85](https://linux-hardware.org/?probe=b2d808ab85) | Dec 14, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [61c4e63c2d](https://linux-hardware.org/?probe=61c4e63c2d) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | Notebook    | [bed7f6d44e](https://linux-hardware.org/?probe=bed7f6d44e) | Dec 14, 2022 |
| Acer          | Aspire Z1801                | All in one  | [9d1453b919](https://linux-hardware.org/?probe=9d1453b919) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [95aca2679a](https://linux-hardware.org/?probe=95aca2679a) | Dec 14, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [44484456f8](https://linux-hardware.org/?probe=44484456f8) | Dec 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [1ccd39b328](https://linux-hardware.org/?probe=1ccd39b328) | Dec 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b20a4554c5](https://linux-hardware.org/?probe=b20a4554c5) | Dec 14, 2022 |
| Dell          | 0YJMC0 A01                  | Desktop     | [59de758672](https://linux-hardware.org/?probe=59de758672) | Dec 14, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [ec912efb6f](https://linux-hardware.org/?probe=ec912efb6f) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [1800fc9efb](https://linux-hardware.org/?probe=1800fc9efb) | Dec 14, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [2da9ae7906](https://linux-hardware.org/?probe=2da9ae7906) | Dec 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [034b34f6d6](https://linux-hardware.org/?probe=034b34f6d6) | Dec 13, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [bf6f0c23a2](https://linux-hardware.org/?probe=bf6f0c23a2) | Dec 13, 2022 |
| Pegatron      | C17A                        | Notebook    | [adde308568](https://linux-hardware.org/?probe=adde308568) | Dec 13, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [ed92313ebc](https://linux-hardware.org/?probe=ed92313ebc) | Dec 13, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [ca2ba2d622](https://linux-hardware.org/?probe=ca2ba2d622) | Dec 13, 2022 |
| Toshiba       | TECRA A10                   | Notebook    | [760bda2b7d](https://linux-hardware.org/?probe=760bda2b7d) | Dec 13, 2022 |
| Acer          | Predator G9-591             | Notebook    | [838b0e0f8c](https://linux-hardware.org/?probe=838b0e0f8c) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [466ea5976d](https://linux-hardware.org/?probe=466ea5976d) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [63cbf5d0e9](https://linux-hardware.org/?probe=63cbf5d0e9) | Dec 13, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [8489ca12d8](https://linux-hardware.org/?probe=8489ca12d8) | Dec 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [05ffc0ef7a](https://linux-hardware.org/?probe=05ffc0ef7a) | Dec 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [3eb157838e](https://linux-hardware.org/?probe=3eb157838e) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [3c5a5379a4](https://linux-hardware.org/?probe=3c5a5379a4) | Dec 13, 2022 |
| Dell          | Inspiron 13-5368            | Notebook    | [952dd9d819](https://linux-hardware.org/?probe=952dd9d819) | Dec 13, 2022 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [8abe5b6b3c](https://linux-hardware.org/?probe=8abe5b6b3c) | Dec 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [83c4f5978a](https://linux-hardware.org/?probe=83c4f5978a) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [d742af8997](https://linux-hardware.org/?probe=d742af8997) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [469dfe26a6](https://linux-hardware.org/?probe=469dfe26a6) | Dec 13, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [469a37f1e4](https://linux-hardware.org/?probe=469a37f1e4) | Dec 12, 2022 |
| Dell          | Inspiron 7380               | Notebook    | [29d4feb456](https://linux-hardware.org/?probe=29d4feb456) | Dec 12, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e008a86cd5](https://linux-hardware.org/?probe=e008a86cd5) | Dec 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [415666008a](https://linux-hardware.org/?probe=415666008a) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [a6b67497a1](https://linux-hardware.org/?probe=a6b67497a1) | Dec 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [bdddbb7807](https://linux-hardware.org/?probe=bdddbb7807) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | Notebook    | [9fb659eea3](https://linux-hardware.org/?probe=9fb659eea3) | Dec 12, 2022 |
| MSI           | GE63 Raider RGB 8RF         | Notebook    | [b311865418](https://linux-hardware.org/?probe=b311865418) | Dec 12, 2022 |
| MSI           | Modern 14 B11MOU            | Notebook    | [9739ffdf34](https://linux-hardware.org/?probe=9739ffdf34) | Dec 12, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [257e692fa4](https://linux-hardware.org/?probe=257e692fa4) | Dec 11, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [211e44e5d2](https://linux-hardware.org/?probe=211e44e5d2) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [50e8243e50](https://linux-hardware.org/?probe=50e8243e50) | Dec 11, 2022 |
| Acer          | Aspire E5-576G              | Notebook    | [9cc371883c](https://linux-hardware.org/?probe=9cc371883c) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | Notebook    | [5cdd66c849](https://linux-hardware.org/?probe=5cdd66c849) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | Notebook    | [624ea43f9d](https://linux-hardware.org/?probe=624ea43f9d) | Dec 11, 2022 |
| Notebook      | WA50SRQ                     | Notebook    | [da74211ac6](https://linux-hardware.org/?probe=da74211ac6) | Dec 11, 2022 |
| ASRock        | X79 Extreme6                | Desktop     | [8ef84e95c1](https://linux-hardware.org/?probe=8ef84e95c1) | Dec 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b5662e5fec](https://linux-hardware.org/?probe=b5662e5fec) | Dec 11, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [8c1901e5d6](https://linux-hardware.org/?probe=8c1901e5d6) | Dec 11, 2022 |
| ASRock        | 760GM-HD                    | Desktop     | [03fdf6453b](https://linux-hardware.org/?probe=03fdf6453b) | Dec 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [591f0ad589](https://linux-hardware.org/?probe=591f0ad589) | Dec 11, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [6bf96cf0fc](https://linux-hardware.org/?probe=6bf96cf0fc) | Dec 11, 2022 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [5941b1aed7](https://linux-hardware.org/?probe=5941b1aed7) | Dec 10, 2022 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [ab1334fca2](https://linux-hardware.org/?probe=ab1334fca2) | Dec 10, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Lenovo        | ThinkStation S30 056851U    | Desktop     | [8c7b6cfca0](https://linux-hardware.org/?probe=8c7b6cfca0) | Dec 10, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4f1f6fde97](https://linux-hardware.org/?probe=4f1f6fde97) | Dec 10, 2022 |
| MSI           | H97M-G43                    | Desktop     | [c62f2a0b49](https://linux-hardware.org/?probe=c62f2a0b49) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [0426545e91](https://linux-hardware.org/?probe=0426545e91) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [e80dfca4a8](https://linux-hardware.org/?probe=e80dfca4a8) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [25d5b5623b](https://linux-hardware.org/?probe=25d5b5623b) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [72f0e70b26](https://linux-hardware.org/?probe=72f0e70b26) | Dec 10, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [11df680f78](https://linux-hardware.org/?probe=11df680f78) | Dec 09, 2022 |
| Pegatron      | C17A                        | Notebook    | [2437a88730](https://linux-hardware.org/?probe=2437a88730) | Dec 09, 2022 |
| Gigabyte      | G31_ICH7                    | Desktop     | [d433eed3f1](https://linux-hardware.org/?probe=d433eed3f1) | Dec 09, 2022 |
| Dell          | 0GU083 A00                  | Desktop     | [1f3f73a41c](https://linux-hardware.org/?probe=1f3f73a41c) | Dec 09, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [ad09795330](https://linux-hardware.org/?probe=ad09795330) | Dec 09, 2022 |
| Schenker      | VIA 15                      | Notebook    | [25883b06a1](https://linux-hardware.org/?probe=25883b06a1) | Dec 09, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [e5ba0c8749](https://linux-hardware.org/?probe=e5ba0c8749) | Dec 09, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [b77b64cc48](https://linux-hardware.org/?probe=b77b64cc48) | Dec 09, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [c291bac936](https://linux-hardware.org/?probe=c291bac936) | Dec 09, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5250630bdd](https://linux-hardware.org/?probe=5250630bdd) | Dec 09, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [2dabd7cf91](https://linux-hardware.org/?probe=2dabd7cf91) | Dec 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bcb55a7e4c](https://linux-hardware.org/?probe=bcb55a7e4c) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [1595cc246a](https://linux-hardware.org/?probe=1595cc246a) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [94c151e95d](https://linux-hardware.org/?probe=94c151e95d) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [bddf744d58](https://linux-hardware.org/?probe=bddf744d58) | Dec 09, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [a875eabf3d](https://linux-hardware.org/?probe=a875eabf3d) | Dec 09, 2022 |
| HP            | Pavilion dv5                | Notebook    | [cdd08235ff](https://linux-hardware.org/?probe=cdd08235ff) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [6ab58fe686](https://linux-hardware.org/?probe=6ab58fe686) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [07e4a8072a](https://linux-hardware.org/?probe=07e4a8072a) | Dec 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [42f14a38dd](https://linux-hardware.org/?probe=42f14a38dd) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5544994d11](https://linux-hardware.org/?probe=5544994d11) | Dec 08, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| Shenzhen M... | HX90G                       | Desktop     | [83a892b661](https://linux-hardware.org/?probe=83a892b661) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [182678a056](https://linux-hardware.org/?probe=182678a056) | Dec 08, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [df78e85dfe](https://linux-hardware.org/?probe=df78e85dfe) | Dec 08, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [c3bf44d032](https://linux-hardware.org/?probe=c3bf44d032) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [5ed19862a7](https://linux-hardware.org/?probe=5ed19862a7) | Dec 08, 2022 |
| MSI           | H97M-G43                    | Desktop     | [53754acfcb](https://linux-hardware.org/?probe=53754acfcb) | Dec 08, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [dcf5539e74](https://linux-hardware.org/?probe=dcf5539e74) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e40a7efd61](https://linux-hardware.org/?probe=e40a7efd61) | Dec 08, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [f69d93aece](https://linux-hardware.org/?probe=f69d93aece) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [551e0142a8](https://linux-hardware.org/?probe=551e0142a8) | Dec 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [6f715ffe60](https://linux-hardware.org/?probe=6f715ffe60) | Dec 08, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [7f45781139](https://linux-hardware.org/?probe=7f45781139) | Dec 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [91aa6eb03e](https://linux-hardware.org/?probe=91aa6eb03e) | Dec 07, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [00995baaae](https://linux-hardware.org/?probe=00995baaae) | Dec 07, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [59118a0638](https://linux-hardware.org/?probe=59118a0638) | Dec 07, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d1e2a097a9](https://linux-hardware.org/?probe=d1e2a097a9) | Dec 07, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [9779817777](https://linux-hardware.org/?probe=9779817777) | Dec 07, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [efe4d93e2d](https://linux-hardware.org/?probe=efe4d93e2d) | Dec 07, 2022 |
| Google        | Eve                         | Convertible | [5269504bf0](https://linux-hardware.org/?probe=5269504bf0) | Dec 07, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [d5d013b642](https://linux-hardware.org/?probe=d5d013b642) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [a214979767](https://linux-hardware.org/?probe=a214979767) | Dec 07, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [06cc238c83](https://linux-hardware.org/?probe=06cc238c83) | Dec 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [811b0e1a71](https://linux-hardware.org/?probe=811b0e1a71) | Dec 06, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e87ced9ea4](https://linux-hardware.org/?probe=e87ced9ea4) | Dec 06, 2022 |
| Dell          | Latitude E6420              | Notebook    | [17c9263444](https://linux-hardware.org/?probe=17c9263444) | Dec 06, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [a3b78e7093](https://linux-hardware.org/?probe=a3b78e7093) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5be32d156a](https://linux-hardware.org/?probe=5be32d156a) | Dec 06, 2022 |
| Acer          | Predator G9-591             | Notebook    | [6e8fe2e030](https://linux-hardware.org/?probe=6e8fe2e030) | Dec 06, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [e9d00a798c](https://linux-hardware.org/?probe=e9d00a798c) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| Dell          | Inspiron 5482               | Convertible | [1acc329a88](https://linux-hardware.org/?probe=1acc329a88) | Dec 06, 2022 |
| BANGHO        | BES T5                      | Notebook    | [db1db74a86](https://linux-hardware.org/?probe=db1db74a86) | Dec 06, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [4f93d8895e](https://linux-hardware.org/?probe=4f93d8895e) | Dec 06, 2022 |
| HP            | 8767 A                      | Desktop     | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [12e33b1925](https://linux-hardware.org/?probe=12e33b1925) | Dec 06, 2022 |
| Acer          | FMP55                       | Desktop     | [78aabc71bf](https://linux-hardware.org/?probe=78aabc71bf) | Dec 05, 2022 |
| Unknown       | HX90                        | Desktop     | [9f3f9dec0b](https://linux-hardware.org/?probe=9f3f9dec0b) | Dec 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a6763bdd89](https://linux-hardware.org/?probe=a6763bdd89) | Dec 05, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [476763a913](https://linux-hardware.org/?probe=476763a913) | Dec 05, 2022 |
| HP            | 8860 A                      | Desktop     | [23fde1381a](https://linux-hardware.org/?probe=23fde1381a) | Dec 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c22a748043](https://linux-hardware.org/?probe=c22a748043) | Dec 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [e75a902d11](https://linux-hardware.org/?probe=e75a902d11) | Dec 05, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_37/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 6.0.15-300.fc37.x86_64           | 131       | 10.89%  |
| 6.0.12-300.fc37.x86_64           | 105       | 8.73%   |
| 6.0.8-300.fc37.x86_64            | 85        | 7.07%   |
| 6.0.9-300.fc37.x86_64            | 84        | 6.98%   |
| 6.0.7-301.fc37.x86_64            | 79        | 6.57%   |
| 6.0.11-300.fc37.x86_64           | 69        | 5.74%   |
| 6.1.7-200.fc37.x86_64            | 67        | 5.57%   |
| 6.0.10-300.fc37.x86_64           | 62        | 5.15%   |
| 6.1.6-200.fc37.x86_64            | 57        | 4.74%   |
| 6.0.18-300.fc37.x86_64           | 46        | 3.82%   |
| 6.0.16-300.fc37.x86_64           | 40        | 3.33%   |
| 5.19.16-301.fc37.x86_64          | 39        | 3.24%   |
| 6.1.5-200.fc37.x86_64            | 34        | 2.83%   |
| 6.0.17-300.fc37.x86_64           | 29        | 2.41%   |
| 6.0.14-300.fc37.x86_64           | 28        | 2.33%   |
| 6.1.8-200.fc37.x86_64            | 25        | 2.08%   |
| 6.0.13-300.fc37.x86_64           | 22        | 1.83%   |
| 5.19.13-300.fc37.x86_64          | 18        | 1.5%    |
| 5.19.8-300.fc37.x86_64           | 15        | 1.25%   |
| 5.19.9-300.fc37.x86_64           | 14        | 1.16%   |
| 5.19.7-300.fc37.x86_64           | 14        | 1.16%   |
| 6.0.6-300.fc37.x86_64            | 9         | 0.75%   |
| 5.19.15-301.fc37.x86_64          | 9         | 0.75%   |
| 5.19.14-300.fc37.x86_64          | 8         | 0.67%   |
| 5.19.12-300.fc37.x86_64          | 7         | 0.58%   |
| 5.19.10-300.fc37.x86_64          | 7         | 0.58%   |
| 6.0.5-300.fc37.x86_64            | 6         | 0.5%    |
| 5.19.16-300.fc37.x86_64          | 6         | 0.5%    |
| 5.19.11-300.fc37.x86_64          | 6         | 0.5%    |
| 5.17.5-300.fc36.x86_64           | 3         | 0.25%   |
| 6.1.2-200.fc37.x86_64            | 2         | 0.17%   |
| 6.1.0-0.rc4.34.inttf.fc37.x86_64 | 2         | 0.17%   |
| 6.0.9-302.rog.fc37.x86_64        | 2         | 0.17%   |
| 6.0.9-300.mbp.fc37.x86_64        | 2         | 0.17%   |
| 6.0.2-xm1.0.fc37.x86_64          | 2         | 0.17%   |
| 6.0.10-602.inttf.fc37.x86_64     | 2         | 0.17%   |
| 5.19.15-300.fc37.x86_64          | 2         | 0.17%   |
| 5.19.10-602.inttf.fc37.x86_64    | 2         | 0.17%   |
| 5.19.0-65.fc37.x86_64            | 2         | 0.17%   |
| 5.18.0-0.rc2.23.fc37.x86_64      | 2         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.15  | 134       | 11.14%  |
| 6.0.12  | 106       | 8.81%   |
| 6.0.9   | 91        | 7.56%   |
| 6.0.8   | 88        | 7.32%   |
| 6.0.7   | 81        | 6.73%   |
| 6.0.11  | 70        | 5.82%   |
| 6.1.7   | 67        | 5.57%   |
| 6.0.10  | 65        | 5.4%    |
| 6.1.6   | 57        | 4.74%   |
| 5.19.16 | 47        | 3.91%   |
| 6.0.18  | 46        | 3.82%   |
| 6.0.16  | 42        | 3.49%   |
| 6.1.5   | 35        | 2.91%   |
| 6.0.17  | 30        | 2.49%   |
| 6.0.14  | 28        | 2.33%   |
| 6.1.8   | 27        | 2.24%   |
| 6.0.13  | 23        | 1.91%   |
| 5.19.13 | 19        | 1.58%   |
| 5.19.8  | 16        | 1.33%   |
| 5.19.9  | 14        | 1.16%   |
| 5.19.7  | 14        | 1.16%   |
| 5.19.15 | 11        | 0.91%   |
| 6.1.0   | 9         | 0.75%   |
| 6.0.6   | 9         | 0.75%   |
| 5.19.14 | 9         | 0.75%   |
| 5.19.12 | 9         | 0.75%   |
| 5.19.10 | 9         | 0.75%   |
| 6.0.5   | 7         | 0.58%   |
| 5.19.11 | 6         | 0.5%    |
| 5.19.0  | 5         | 0.42%   |
| 5.18.0  | 4         | 0.33%   |
| 6.0.2   | 3         | 0.25%   |
| 6.0.0   | 3         | 0.25%   |
| 5.17.5  | 3         | 0.25%   |
| 6.2.0   | 2         | 0.17%   |
| 6.1.2   | 2         | 0.17%   |
| 6.1.1   | 2         | 0.17%   |
| 6.0.3   | 1         | 0.08%   |
| 5.8.15  | 1         | 0.08%   |
| 5.19.6  | 1         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 785       | 68.26%  |
| 6.1     | 194       | 16.87%  |
| 5.19    | 156       | 13.57%  |
| 5.18    | 5         | 0.43%   |
| 5.17    | 4         | 0.35%   |
| 6.2     | 2         | 0.17%   |
| 5.15    | 2         | 0.17%   |
| 5.8     | 1         | 0.09%   |
| 5.0     | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1120      | 99.56%  |
| aarch64 | 5         | 0.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| GNOME                        | 850       | 75.15%  |
| KDE5                         | 190       | 16.8%   |
| Unknown                      | 24        | 2.12%   |
| XFCE                         | 17        | 1.5%    |
| X-Cinnamon                   | 13        | 1.15%   |
| MATE                         | 9         | 0.8%    |
| Cinnamon                     | 8         | 0.71%   |
| i3                           | 7         | 0.62%   |
| LXDE                         | 4         | 0.35%   |
| sway                         | 2         | 0.18%   |
| LXQt                         | 2         | 0.18%   |
| xmonad                       | 1         | 0.09%   |
| qtile                        | 1         | 0.09%   |
| Phosh:GNOME                  | 1         | 0.09%   |
| KDE                          | 1         | 0.09%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 829       | 73.1%   |
| X11     | 274       | 24.16%  |
| Unknown | 18        | 1.59%   |
| Tty     | 13        | 1.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 589       | 52.03%  |
| GDM     | 388       | 34.28%  |
| SDDM    | 96        | 8.48%   |
| LightDM | 55        | 4.86%   |
| LXDM    | 3         | 0.27%   |
| GREETD  | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 591       | 52.39%  |
| en_GB   | 84        | 7.45%   |
| ru_RU   | 67        | 5.94%   |
| pt_BR   | 53        | 4.7%    |
| de_DE   | 49        | 4.34%   |
| fr_FR   | 36        | 3.19%   |
| it_IT   | 27        | 2.39%   |
| en_CA   | 25        | 2.22%   |
| en_AU   | 25        | 2.22%   |
| pl_PL   | 22        | 1.95%   |
| en_IN   | 18        | 1.6%    |
| es_ES   | 17        | 1.51%   |
| zh_CN   | 6         | 0.53%   |
| tr_TR   | 6         | 0.53%   |
| hu_HU   | 6         | 0.53%   |
| C       | 6         | 0.53%   |
| fi_FI   | 5         | 0.44%   |
| es_MX   | 5         | 0.44%   |
| es_CL   | 5         | 0.44%   |
| es_AR   | 5         | 0.44%   |
| de_AT   | 5         | 0.44%   |
| nl_NL   | 4         | 0.35%   |
| en_ZA   | 4         | 0.35%   |
| en_NZ   | 4         | 0.35%   |
| en_IE   | 4         | 0.35%   |
| de_CH   | 4         | 0.35%   |
| cs_CZ   | 4         | 0.35%   |
| zh_TW   | 3         | 0.27%   |
| en_PH   | 3         | 0.27%   |
| ca_ES   | 3         | 0.27%   |
| Unknown | 3         | 0.27%   |
| sv_SE   | 2         | 0.18%   |
| pt_PT   | 2         | 0.18%   |
| es_PE   | 2         | 0.18%   |
| en_DK   | 2         | 0.18%   |
| uk_UA   | 1         | 0.09%   |
| sk_SK   | 1         | 0.09%   |
| ru_UA   | 1         | 0.09%   |
| ro_RO   | 1         | 0.09%   |
| nb_NO   | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 938       | 83.08%  |
| BIOS | 191       | 16.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 922       | 81.81%  |
| Ext4    | 180       | 15.97%  |
| Xfs     | 19        | 1.69%   |
| Overlay | 4         | 0.35%   |
| F2fs    | 2         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 567       | 50.09%  |
| GPT     | 530       | 46.82%  |
| MBR     | 35        | 3.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1013      | 89.49%  |
| Yes       | 119       | 10.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 912       | 80.85%  |
| Yes       | 216       | 19.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 221       | 19.64%  |
| ASUSTek Computer    | 205       | 18.22%  |
| Dell                | 140       | 12.44%  |
| Hewlett-Packard     | 138       | 12.27%  |
| MSI                 | 75        | 6.67%   |
| Acer                | 62        | 5.51%   |
| Gigabyte Technology | 61        | 5.42%   |
| ASRock              | 33        | 2.93%   |
| HUAWEI              | 25        | 2.22%   |
| Apple               | 20        | 1.78%   |
| Intel               | 15        | 1.33%   |
| Timi                | 9         | 0.8%    |
| Samsung Electronics | 8         | 0.71%   |
| Microsoft           | 7         | 0.62%   |
| Google              | 7         | 0.62%   |
| Toshiba             | 6         | 0.53%   |
| TUXEDO              | 5         | 0.44%   |
| GPD                 | 5         | 0.44%   |
| Schenker            | 4         | 0.36%   |
| Chuwi               | 4         | 0.36%   |
| System76            | 3         | 0.27%   |
| Positivo            | 3         | 0.27%   |
| Pegatron            | 3         | 0.27%   |
| Framework           | 3         | 0.27%   |
| AZW                 | 3         | 0.27%   |
| Unknown             | 3         | 0.27%   |
| Sony                | 2         | 0.18%   |
| SLIMBOOK            | 2         | 0.18%   |
| PINE64              | 2         | 0.18%   |
| Notebook            | 2         | 0.18%   |
| MACHENIKE           | 2         | 0.18%   |
| LG Electronics      | 2         | 0.18%   |
| Fujitsu             | 2         | 0.18%   |
| Dynabook            | 2         | 0.18%   |
| Alienware           | 2         | 0.18%   |
| Valve               | 1         | 0.09%   |
| UNOWHY              | 1         | 0.09%   |
| TYAN Computer       | 1         | 0.09%   |
| TECNO               | 1         | 0.09%   |
| Tactus              | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 10        | 0.89%   |
| Dell OptiPlex 7010                       | 6         | 0.53%   |
| MSI MS-7C02                              | 4         | 0.36%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 4         | 0.36%   |
| HUAWEI CREM-WXX9                         | 4         | 0.36%   |
| ASUS TUF Gaming B550M-PLUS               | 4         | 0.36%   |
| ASUS ROG STRIX B450-F GAMING             | 4         | 0.36%   |
| Unknown                                  | 4         | 0.36%   |
| MSI MS-7C84                              | 3         | 0.27%   |
| MSI MS-7C56                              | 3         | 0.27%   |
| MSI MS-7C37                              | 3         | 0.27%   |
| MSI MS-7A38                              | 3         | 0.27%   |
| Lenovo ThinkBook 15 G3 ACL 21A4          | 3         | 0.27%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2        | 3         | 0.27%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5         | 3         | 0.27%   |
| Intel NUC8i7BEH                          | 3         | 0.27%   |
| HP OMEN by Laptop 16-c0xxx               | 3         | 0.27%   |
| GPD G1619-04                             | 3         | 0.27%   |
| Gigabyte B550M DS3H                      | 3         | 0.27%   |
| Dell XPS 15 9570                         | 3         | 0.27%   |
| Dell XPS 15 9520                         | 3         | 0.27%   |
| Dell Latitude 7490                       | 3         | 0.27%   |
| Dell Latitude 7480                       | 3         | 0.27%   |
| Dell Latitude 5420                       | 3         | 0.27%   |
| Dell Inspiron 5566                       | 3         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA   | 3         | 0.27%   |
| ASUS VivoBook_ASUSLaptop M5402RA_M5402RA | 3         | 0.27%   |
| ASUS TUF Gaming X570-PLUS                | 3         | 0.27%   |
| ASUS ROG STRIX X670E-F GAMING WIFI       | 3         | 0.27%   |
| ASUS ROG STRIX X570-E GAMING             | 3         | 0.27%   |
| ASUS ProArt Z690-CREATOR WIFI            | 3         | 0.27%   |
| ASUS ProArt X670E-CREATOR WIFI           | 3         | 0.27%   |
| ASUS PRIME X370-PRO                      | 3         | 0.27%   |
| ASUS PRIME B550-PLUS                     | 3         | 0.27%   |
| ASUS PRIME B450M-A II                    | 3         | 0.27%   |
| Apple MacBookPro9,2                      | 3         | 0.27%   |
| Acer Aspire A515-45                      | 3         | 0.27%   |
| Timi A35S                                | 2         | 0.18%   |
| Positivo POS-PIQ57BQ                     | 2         | 0.18%   |
| PINE64 Pinebook Pro                      | 2         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 121       | 10.76%  |
| Dell Inspiron      | 48        | 4.27%   |
| ASUS ROG           | 42        | 3.73%   |
| Lenovo IdeaPad     | 41        | 3.64%   |
| Dell Latitude      | 35        | 3.11%   |
| Acer Aspire        | 34        | 3.02%   |
| ASUS PRIME         | 33        | 2.93%   |
| HP Pavilion        | 25        | 2.22%   |
| HP Laptop          | 21        | 1.87%   |
| HP EliteBook       | 21        | 1.87%   |
| Dell XPS           | 21        | 1.87%   |
| ASUS VivoBook      | 21        | 1.87%   |
| ASUS TUF           | 20        | 1.78%   |
| Lenovo ThinkBook   | 18        | 1.6%    |
| Dell OptiPlex      | 15        | 1.33%   |
| ASUS ASUS          | 15        | 1.33%   |
| ASUS Zenbook       | 14        | 1.24%   |
| HP ProBook         | 13        | 1.16%   |
| HP ENVY            | 13        | 1.16%   |
| Acer Nitro         | 11        | 0.98%   |
| ASUS All           | 10        | 0.89%   |
| Lenovo Legion      | 9         | 0.8%    |
| HP ZBook           | 9         | 0.8%    |
| Dell Precision     | 9         | 0.8%    |
| Lenovo Yoga        | 8         | 0.71%   |
| Microsoft Surface  | 7         | 0.62%   |
| Lenovo ThinkCentre | 6         | 0.53%   |
| HP OMEN            | 6         | 0.53%   |
| Dell Vostro        | 6         | 0.53%   |
| ASUS ProArt        | 6         | 0.53%   |
| Acer Predator      | 6         | 0.53%   |
| Toshiba Satellite  | 5         | 0.44%   |
| MSI Modern         | 5         | 0.44%   |
| Gigabyte X570      | 5         | 0.44%   |
| Acer Swift         | 5         | 0.44%   |
| MSI MS-7C02        | 4         | 0.36%   |
| Lenovo IdeaPadFlex | 4         | 0.36%   |
| HUAWEI CREM-WXX9   | 4         | 0.36%   |
| HP Spectre         | 4         | 0.36%   |
| HP Compaq          | 4         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 198       | 17.6%   |
| 2022 | 167       | 14.84%  |
| 2020 | 166       | 14.76%  |
| 2019 | 128       | 11.38%  |
| 2018 | 113       | 10.04%  |
| 2017 | 72        | 6.4%    |
| 2013 | 55        | 4.89%   |
| 2012 | 52        | 4.62%   |
| 2015 | 37        | 3.29%   |
| 2016 | 35        | 3.11%   |
| 2014 | 33        | 2.93%   |
| 2011 | 21        | 1.87%   |
| 2010 | 21        | 1.87%   |
| 2009 | 12        | 1.07%   |
| 2008 | 11        | 0.98%   |
| 2007 | 2         | 0.18%   |
| 2006 | 2         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 669       | 59.47%  |
| Desktop        | 343       | 30.49%  |
| Convertible    | 64        | 5.69%   |
| Mini pc        | 19        | 1.69%   |
| Tablet         | 15        | 1.33%   |
| All in one     | 8         | 0.71%   |
| System on chip | 5         | 0.44%   |
| Server         | 2         | 0.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 869       | 76.9%   |
| Enabled  | 261       | 23.1%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1117      | 99.29%  |
| Yes  | 8         | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 289       | 25.6%   |
| 4.01-8.0        | 239       | 21.17%  |
| 8.01-16.0       | 229       | 20.28%  |
| 32.01-64.0      | 188       | 16.65%  |
| 3.01-4.0        | 79        | 7%      |
| 64.01-256.0     | 47        | 4.16%   |
| 24.01-32.0      | 39        | 3.45%   |
| 1.01-2.0        | 14        | 1.24%   |
| 2.01-3.0        | 3         | 0.27%   |
| More than 256.0 | 2         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 392       | 33.48%  |
| 3.01-4.0   | 278       | 23.74%  |
| 2.01-3.0   | 261       | 22.29%  |
| 1.01-2.0   | 110       | 9.39%   |
| 8.01-16.0  | 104       | 8.88%   |
| 0.51-1.0   | 14        | 1.2%    |
| 16.01-24.0 | 8         | 0.68%   |
| 24.01-32.0 | 2         | 0.17%   |
| 32.01-64.0 | 1         | 0.09%   |
| 0.01-0.5   | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 683       | 60.39%  |
| 2      | 281       | 24.85%  |
| 3      | 89        | 7.87%   |
| 4      | 40        | 3.54%   |
| 5      | 14        | 1.24%   |
| 6      | 8         | 0.71%   |
| 0      | 6         | 0.53%   |
| 7      | 4         | 0.35%   |
| 8      | 2         | 0.18%   |
| 18     | 1         | 0.09%   |
| 15     | 1         | 0.09%   |
| 12     | 1         | 0.09%   |
| 9      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 942       | 83.66%  |
| Yes       | 184       | 16.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 842       | 74.84%  |
| No        | 283       | 25.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 941       | 83.5%   |
| No        | 186       | 16.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 851       | 75.31%  |
| No        | 279       | 24.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 206       | 18.23%  |
| Germany      | 89        | 7.88%   |
| Russia       | 79        | 6.99%   |
| Brazil       | 73        | 6.46%   |
| Italy        | 56        | 4.96%   |
| France       | 45        | 3.98%   |
| India        | 41        | 3.63%   |
| Canada       | 38        | 3.36%   |
| UK           | 36        | 3.19%   |
| Poland       | 36        | 3.19%   |
| Australia    | 32        | 2.83%   |
| Spain        | 27        | 2.39%   |
| Netherlands  | 27        | 2.39%   |
| Austria      | 23        | 2.04%   |
| Turkey       | 19        | 1.68%   |
| Sweden       | 19        | 1.68%   |
| Switzerland  | 15        | 1.33%   |
| Czechia      | 13        | 1.15%   |
| Taiwan       | 12        | 1.06%   |
| Mexico       | 12        | 1.06%   |
| Hungary      | 12        | 1.06%   |
| Indonesia    | 10        | 0.88%   |
| Belgium      | 9         | 0.8%    |
| Argentina    | 9         | 0.8%    |
| Romania      | 8         | 0.71%   |
| Norway       | 8         | 0.71%   |
| Finland      | 8         | 0.71%   |
| Slovakia     | 6         | 0.53%   |
| Japan        | 6         | 0.53%   |
| Greece       | 6         | 0.53%   |
| South Africa | 5         | 0.44%   |
| Serbia       | 5         | 0.44%   |
| Portugal     | 5         | 0.44%   |
| Philippines  | 5         | 0.44%   |
| Ireland      | 5         | 0.44%   |
| Denmark      | 5         | 0.44%   |
| Chile        | 5         | 0.44%   |
| Vietnam      | 4         | 0.35%   |
| Thailand     | 4         | 0.35%   |
| Peru         | 4         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 20        | 1.74%   |
| Vienna            | 12        | 1.04%   |
| Warsaw            | 10        | 0.87%   |
| Sydney            | 10        | 0.87%   |
| Sao Paulo         | 9         | 0.78%   |
| Berlin            | 9         | 0.78%   |
| Madrid            | 8         | 0.69%   |
| London            | 8         | 0.69%   |
| St Petersburg     | 7         | 0.61%   |
| Melbourne         | 7         | 0.61%   |
| Frankfurt am Main | 7         | 0.61%   |
| Budapest          | 7         | 0.61%   |
| Amsterdam         | 7         | 0.61%   |
| Prague            | 6         | 0.52%   |
| Portland          | 6         | 0.52%   |
| New Taipei        | 6         | 0.52%   |
| Istanbul          | 6         | 0.52%   |
| Brisbane          | 6         | 0.52%   |
| Bengaluru         | 6         | 0.52%   |
| Porto Alegre      | 5         | 0.43%   |
| New York          | 5         | 0.43%   |
| Montreal          | 5         | 0.43%   |
| Krasnodar         | 5         | 0.43%   |
| Innsbruck         | 5         | 0.43%   |
| Helsinki          | 5         | 0.43%   |
| Zurich            | 4         | 0.35%   |
| Saratov           | 4         | 0.35%   |
| Paris             | 4         | 0.35%   |
| Palmas            | 4         | 0.35%   |
| Minsk             | 4         | 0.35%   |
| Milan             | 4         | 0.35%   |
| Miami             | 4         | 0.35%   |
| Jakarta           | 4         | 0.35%   |
| Izmir             | 4         | 0.35%   |
| Ho Chi Minh City  | 4         | 0.35%   |
| Hamburg           | 4         | 0.35%   |
| Easton            | 4         | 0.35%   |
| Delft             | 4         | 0.35%   |
| Cape Town         | 4         | 0.35%   |
| Bogotá           | 4         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 380       | 496    | 22.95%  |
| WDC                            | 186       | 265    | 11.23%  |
| Seagate                        | 151       | 195    | 9.12%   |
| Sandisk                        | 130       | 149    | 7.85%   |
| Kingston                       | 94        | 110    | 5.68%   |
| SK hynix                       | 84        | 86     | 5.07%   |
| Toshiba                        | 79        | 92     | 4.77%   |
| Crucial                        | 71        | 78     | 4.29%   |
| Intel                          | 57        | 69     | 3.44%   |
| Micron Technology              | 49        | 53     | 2.96%   |
| Unknown                        | 48        | 58     | 2.9%    |
| KIOXIA                         | 27        | 30     | 1.63%   |
| Phison Electronics             | 23        | 26     | 1.39%   |
| Micron/Crucial Technology      | 18        | 20     | 1.09%   |
| Hitachi                        | 18        | 22     | 1.09%   |
| HGST                           | 16        | 28     | 0.97%   |
| China                          | 15        | 18     | 0.91%   |
| A-DATA Technology              | 15        | 16     | 0.91%   |
| Apple                          | 12        | 15     | 0.72%   |
| SPCC                           | 9         | 12     | 0.54%   |
| LITEON                         | 9         | 9      | 0.54%   |
| Apacer                         | 9         | 11     | 0.54%   |
| ADATA Technology               | 8         | 8      | 0.48%   |
| Silicon Motion                 | 6         | 7      | 0.36%   |
| Realtek Semiconductor          | 6         | 6      | 0.36%   |
| PNY                            | 6         | 6      | 0.36%   |
| Netac                          | 6         | 8      | 0.36%   |
| Kingston Technology Company    | 6         | 6      | 0.36%   |
| Phison                         | 5         | 5      | 0.3%    |
| Lexar                          | 5         | 6      | 0.3%    |
| HS-SSD-E100                    | 5         | 5      | 0.3%    |
| FORESEE                        | 5         | 5      | 0.3%    |
| Corsair                        | 5         | 7      | 0.3%    |
| Unknown                        | 5         | 6      | 0.3%    |
| UMIS                           | 4         | 4      | 0.24%   |
| Transcend                      | 3         | 3      | 0.18%   |
| Solid State Storage Technology | 3         | 4      | 0.18%   |
| SABRENT                        | 3         | 3      | 0.18%   |
| Patriot                        | 3         | 3      | 0.18%   |
| Lite-On Technology             | 3         | 3      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 70        | 3.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 35        | 1.94%   |
| Kingston SA400S37240G 240GB SSD                      | 26        | 1.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB       | 17        | 0.94%   |
| Seagate ST1000LM035-1RK172 1TB                       | 16        | 0.89%   |
| Seagate ST2000DM008-2FR102 2TB                       | 15        | 0.83%   |
| Toshiba MQ04ABF100 1TB                               | 14        | 0.78%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 14        | 0.78%   |
| Crucial CT1000MX500SSD1 1TB                          | 14        | 0.78%   |
| Samsung SSD 870 EVO 500GB                            | 13        | 0.72%   |
| Samsung SSD 850 EVO 250GB                            | 12        | 0.67%   |
| Samsung SSD 860 EVO 500GB                            | 11        | 0.61%   |
| Crucial CT240BX500SSD1 240GB                         | 11        | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 10        | 0.55%   |
| Phison E12 NVMe Controller 1TB                       | 10        | 0.55%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 10        | 0.55%   |
| Seagate ST500DM002-1BD142 500GB                      | 9         | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                       | 9         | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB                       | 9         | 0.5%    |
| Samsung SSD 850 EVO 500GB                            | 9         | 0.5%    |
| Intel SSDPEKNU512GZ 512GB                            | 9         | 0.5%    |
| Intel SSD 660P Series 512GB                          | 9         | 0.5%    |
| Samsung SSD 980 PRO 1TB                              | 8         | 0.44%   |
| Samsung SSD 980 1TB                                  | 8         | 0.44%   |
| Samsung SSD 870 EVO 1TB                              | 8         | 0.44%   |
| Kingston SA400S37480G 480GB SSD                      | 8         | 0.44%   |
| Kingston SA400S37120G 120GB SSD                      | 8         | 0.44%   |
| Unknown MMC Card  64GB                               | 7         | 0.39%   |
| Unknown MMC Card  32GB                               | 7         | 0.39%   |
| Unknown MMC Card  128GB                              | 7         | 0.39%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 7         | 0.39%   |
| Sandisk WD Black SN850 2TB                           | 7         | 0.39%   |
| Samsung SSD 970 EVO Plus 2TB                         | 7         | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB                         | 7         | 0.39%   |
| Samsung SSD 860 EVO 250GB                            | 7         | 0.39%   |
| Samsung SSD 860 EVO 1TB                              | 7         | 0.39%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 7         | 0.39%   |
| Phison PS5013 E13 NVMe Controller 256GB              | 7         | 0.39%   |
| KIOXIA KBG40ZNV512G 512GB                            | 7         | 0.39%   |
| Crucial CT1000BX500SSD1 1TB                          | 7         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 149       | 193    | 39.73%  |
| WDC                 | 118       | 175    | 31.47%  |
| Toshiba             | 52        | 61     | 13.87%  |
| Hitachi             | 18        | 22     | 4.8%    |
| HGST                | 16        | 28     | 4.27%   |
| Samsung Electronics | 8         | 10     | 2.13%   |
| Unknown             | 4         | 4      | 1.07%   |
| SABRENT             | 3         | 3      | 0.8%    |
| USB3.0              | 1         | 1      | 0.27%   |
| Maxtor              | 1         | 1      | 0.27%   |
| JMicron Technology  | 1         | 3      | 0.27%   |
| Inateck             | 1         | 1      | 0.27%   |
| External            | 1         | 1      | 0.27%   |
| ASMT                | 1         | 2      | 0.27%   |
| Apple               | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 120       | 156    | 26.26%  |
| Crucial             | 62        | 67     | 13.57%  |
| Kingston            | 61        | 71     | 13.35%  |
| SanDisk             | 38        | 40     | 8.32%   |
| WDC                 | 30        | 35     | 6.56%   |
| China               | 15        | 18     | 3.28%   |
| SK hynix            | 10        | 10     | 2.19%   |
| Micron Technology   | 10        | 10     | 2.19%   |
| Intel               | 10        | 12     | 2.19%   |
| Toshiba             | 7         | 7      | 1.53%   |
| LITEON              | 7         | 7      | 1.53%   |
| Apple               | 7         | 7      | 1.53%   |
| Apacer              | 7         | 8      | 1.53%   |
| SPCC                | 6         | 8      | 1.31%   |
| PNY                 | 6         | 6      | 1.31%   |
| Netac               | 5         | 6      | 1.09%   |
| Lexar               | 5         | 6      | 1.09%   |
| A-DATA Technology   | 4         | 4      | 0.88%   |
| Patriot             | 3         | 3      | 0.66%   |
| GOODRAM             | 3         | 5      | 0.66%   |
| Unknown             | 2         | 2      | 0.44%   |
| Transcend           | 2         | 2      | 0.44%   |
| Plextor             | 2         | 2      | 0.44%   |
| OCZ                 | 2         | 2      | 0.44%   |
| FORESEE             | 2         | 2      | 0.44%   |
| Corsair             | 2         | 3      | 0.44%   |
| Unknown             | 2         | 2      | 0.44%   |
| XSTAR               | 1         | 1      | 0.22%   |
| WDC WDS             | 1         | 1      | 0.22%   |
| Teclast             | 1         | 2      | 0.22%   |
| Team                | 1         | 2      | 0.22%   |
| Super Talent        | 1         | 1      | 0.22%   |
| SCY                 | 1         | 1      | 0.22%   |
| Ramaxel Technology  | 1         | 1      | 0.22%   |
| OWC                 | 1         | 1      | 0.22%   |
| Mushkin             | 1         | 1      | 0.22%   |
| Mercury             | 1         | 1      | 0.22%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.22%   |
| KingSpec            | 1         | 1      | 0.22%   |
| KingFast            | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 726       | 921    | 48.18%  |
| SSD     | 403       | 532    | 26.74%  |
| HDD     | 313       | 506    | 20.77%  |
| MMC     | 43        | 51     | 2.85%   |
| Unknown | 22        | 24     | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 726       | 920    | 52.69%  |
| SATA | 564       | 1002   | 40.93%  |
| SAS  | 45        | 61     | 3.27%   |
| MMC  | 43        | 51     | 3.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 380       | 509    | 50.26%  |
| 0.51-1.0   | 235       | 306    | 31.08%  |
| 1.01-2.0   | 72        | 95     | 9.52%   |
| 3.01-4.0   | 28        | 41     | 3.7%    |
| 4.01-10.0  | 21        | 33     | 2.78%   |
| 2.01-3.0   | 17        | 35     | 2.25%   |
| 10.01-20.0 | 3         | 19     | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 246       | 21.62%  |
| 251-500        | 217       | 19.07%  |
| 1001-2000      | 163       | 14.32%  |
| 1-20           | 131       | 11.51%  |
| 101-250        | 113       | 9.93%   |
| Unknown        | 92        | 8.08%   |
| More than 3000 | 76        | 6.68%   |
| 2001-3000      | 55        | 4.83%   |
| 51-100         | 28        | 2.46%   |
| 21-50          | 17        | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 313       | 27.05%  |
| 21-50          | 176       | 15.21%  |
| 101-250        | 153       | 13.22%  |
| 51-100         | 124       | 10.72%  |
| 251-500        | 113       | 9.77%   |
| 501-1000       | 103       | 8.9%    |
| Unknown        | 92        | 7.95%   |
| 1001-2000      | 50        | 4.32%   |
| More than 3000 | 20        | 1.73%   |
| 2001-3000      | 13        | 1.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB   | 3         | 3      | 3.9%    |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 3      | 2.6%    |
| Intel SSDSC2CT120A3 120GB             | 2         | 4      | 2.6%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 1.3%    |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 1.3%    |
| WDC WD5000AVVS-63H0B1 500GB           | 1         | 1      | 1.3%    |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 1.3%    |
| WDC WD5000AAKX-603CA0 500GB           | 1         | 1      | 1.3%    |
| WDC WD40EZRZ-00WN9B0 4TB              | 1         | 1      | 1.3%    |
| WDC WD3200BPVT-80JJ5T0 320GB          | 1         | 1      | 1.3%    |
| WDC WD3200AAKS-00V1A0 320GB           | 1         | 1      | 1.3%    |
| WDC WD3200AAKS-00UU3A0 320GB          | 1         | 1      | 1.3%    |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 1      | 1.3%    |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 1      | 1.3%    |
| WDC WD20EZRX-22D8PB0 2TB              | 1         | 1      | 1.3%    |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 1      | 1.3%    |
| WDC WD15EARS-00MVWB0 1TB              | 1         | 1      | 1.3%    |
| WDC WD140EDFZ-11A0VA0 14TB            | 1         | 2      | 1.3%    |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 2      | 1.3%    |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 1.3%    |
| WDC WD10EFRX-68FYTN0 1TB              | 1         | 1      | 1.3%    |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 1.3%    |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 1.3%    |
| Toshiba MK7559GSXP 752GB              | 1         | 1      | 1.3%    |
| Toshiba MK5061GSY 500GB               | 1         | 1      | 1.3%    |
| Toshiba MK3265GSX 320GB               | 1         | 1      | 1.3%    |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 1.3%    |
| Toshiba MK1237GSX 120GB               | 1         | 1      | 1.3%    |
| Toshiba KBG30ZMS512G NVMe 512GB       | 1         | 1      | 1.3%    |
| SPCC SPCCSolidStateDisk 128GB SSD     | 1         | 1      | 1.3%    |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 1.3%    |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 1.3%    |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.3%    |
| Seagate ST9320325AS 320GB             | 1         | 1      | 1.3%    |
| Seagate ST8000NE001-2M7101 8TB        | 1         | 1      | 1.3%    |
| Seagate ST6000DM003-2CY186 6TB        | 1         | 1      | 1.3%    |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.3%    |
| Seagate ST500LM000-SSHD-8GB           | 1         | 1      | 1.3%    |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.3%    |
| Seagate ST4000LM024-2AN17V 4TB        | 1         | 1      | 1.3%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 25     | 29.17%  |
| WDC                 | 17        | 21     | 23.61%  |
| Samsung Electronics | 8         | 12     | 11.11%  |
| Toshiba             | 7         | 7      | 9.72%   |
| Intel               | 3         | 5      | 4.17%   |
| Crucial             | 3         | 3      | 4.17%   |
| SK hynix            | 2         | 2      | 2.78%   |
| Micron Technology   | 2         | 2      | 2.78%   |
| SPCC                | 1         | 1      | 1.39%   |
| Maxtor              | 1         | 1      | 1.39%   |
| Kingston            | 1         | 1      | 1.39%   |
| Hitachi             | 1         | 1      | 1.39%   |
| HGST                | 1         | 1      | 1.39%   |
| Corsair             | 1         | 1      | 1.39%   |
| Apple               | 1         | 1      | 1.39%   |
| AMD                 | 1         | 2      | 1.39%   |
| Unknown             | 1         | 1      | 1.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 25     | 42%     |
| WDC                 | 16        | 20     | 32%     |
| Toshiba             | 6         | 6      | 12%     |
| Samsung Electronics | 4         | 6      | 8%      |
| Maxtor              | 1         | 1      | 2%      |
| Hitachi             | 1         | 1      | 2%      |
| HGST                | 1         | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 60     | 67.16%  |
| SSD  | 19        | 24     | 28.36%  |
| NVMe | 3         | 3      | 4.48%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| SPCC M.2 PCIe SSD 2TB           | 1         | 1      | 33.33%  |
| Seagate ST31000528AS 1TB        | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 980 1TB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SPCC                | 1         | 1      | 33.33%  |
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 645       | 1139   | 53.35%  |
| Works    | 497       | 805    | 41.11%  |
| Malfunc  | 64        | 87     | 5.29%   |
| Failed   | 3         | 3      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 588       | 36.16%  |
| Samsung Electronics            | 277       | 17.04%  |
| AMD                            | 251       | 15.44%  |
| SanDisk                        | 136       | 8.36%   |
| SK hynix                       | 74        | 4.55%   |
| Micron Technology              | 40        | 2.46%   |
| Kingston Technology Company    | 40        | 2.46%   |
| Phison Electronics             | 34        | 2.09%   |
| Micron/Crucial Technology      | 25        | 1.54%   |
| Toshiba America Info Systems   | 24        | 1.48%   |
| KIOXIA                         | 23        | 1.41%   |
| ASMedia Technology             | 20        | 1.23%   |
| ADATA Technology               | 18        | 1.11%   |
| Silicon Motion                 | 10        | 0.62%   |
| Marvell Technology Group       | 10        | 0.62%   |
| Realtek Semiconductor          | 8         | 0.49%   |
| Union Memory (Shenzhen)        | 6         | 0.37%   |
| Lite-On Technology             | 5         | 0.31%   |
| Solid State Storage Technology | 4         | 0.25%   |
| Yangtze Memory Technologies    | 3         | 0.18%   |
| Shenzhen Longsys Electronics   | 3         | 0.18%   |
| Nvidia                         | 3         | 0.18%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.18%   |
| JMicron Technology             | 3         | 0.18%   |
| Broadcom / LSI                 | 3         | 0.18%   |
| Biwin Storage Technology       | 3         | 0.18%   |
| Apple                          | 3         | 0.18%   |
| VIA Technologies               | 2         | 0.12%   |
| LSI Logic / Symbios Logic      | 2         | 0.12%   |
| Transcend                      | 1         | 0.06%   |
| Solidigm                       | 1         | 0.06%   |
| Seagate Technology             | 1         | 0.06%   |
| Netac Technology               | 1         | 0.06%   |
| Lenovo                         | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 163       | 9.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 121       | 6.84%   |
| Intel Volume Management Device NVMe RAID Controller                            | 81        | 4.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 70        | 3.95%   |
| Samsung NVMe SSD Controller 980                                                | 68        | 3.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 56        | 3.16%   |
| SanDisk Non-Volatile memory controller                                         | 41        | 2.32%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 40        | 2.26%   |
| Micron Non-Volatile memory controller                                          | 40        | 2.26%   |
| AMD 400 Series Chipset SATA Controller                                         | 39        | 2.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 37        | 2.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 33        | 1.86%   |
| AMD 500 Series Chipset SATA Controller                                         | 30        | 1.69%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 28        | 1.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 25        | 1.41%   |
| Kingston Company Company Non-Volatile memory controller                        | 24        | 1.36%   |
| Intel Tiger Lake-LP SATA Controller                                            | 23        | 1.3%    |
| Intel Non-Volatile memory controller                                           | 23        | 1.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 23        | 1.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 23        | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                          | 21        | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 21        | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 20        | 1.13%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 19        | 1.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 19        | 1.07%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 18        | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 17        | 0.96%   |
| AMD SATA controller                                                            | 17        | 0.96%   |
| Phison E12 NVMe Controller                                                     | 16        | 0.9%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 16        | 0.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 16        | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 16        | 0.9%    |
| Intel SATA Controller [RAID mode]                                              | 15        | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 15        | 0.85%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 14        | 0.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 14        | 0.79%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 13        | 0.73%   |
| Intel SSD 660P Series                                                          | 13        | 0.73%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 13        | 0.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 12        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 723       | 44.85%  |
| SATA | 698       | 43.3%   |
| RAID | 137       | 8.5%    |
| IDE  | 48        | 2.98%   |
| SAS  | 5         | 0.31%   |
| SCSI | 1         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 755       | 67.11%  |
| AMD    | 365       | 32.44%  |
| ARM    | 5         | 0.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 33        | 2.93%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 2.04%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 18        | 1.6%    |
| AMD Ryzen 5 3600 6-Core Processor             | 16        | 1.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 1.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 1.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 1.24%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 14        | 1.24%   |
| Intel 12th Gen Core i7-12700H                 | 14        | 1.24%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 14        | 1.24%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 1.16%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 13        | 1.16%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 1.07%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 12        | 1.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 1.07%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 12        | 1.07%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 12        | 1.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 0.98%   |
| Intel 12th Gen Core i5-1240P                  | 10        | 0.89%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 10        | 0.89%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 9         | 0.8%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 9         | 0.8%    |
| AMD Ryzen 9 7950X 16-Core Processor           | 9         | 0.8%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 0.8%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 9         | 0.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 0.71%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 8         | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.71%   |
| Intel 12th Gen Core i5-1235U                  | 8         | 0.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 0.62%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.62%   |
| Intel 12th Gen Core i9-12900H                 | 7         | 0.62%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 7         | 0.62%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 0.62%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 7         | 0.62%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 7         | 0.62%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.62%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 7         | 0.62%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 7         | 0.62%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 7         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i7                        | 215       | 19.11%  |
| Other                                | 200       | 17.78%  |
| Intel Core i5                        | 192       | 17.07%  |
| AMD Ryzen 5                          | 121       | 10.76%  |
| AMD Ryzen 7                          | 114       | 10.13%  |
| Intel Core i3                        | 52        | 4.62%   |
| AMD Ryzen 9                          | 46        | 4.09%   |
| Intel Celeron                        | 25        | 2.22%   |
| Intel Xeon                           | 17        | 1.51%   |
| AMD Ryzen 3                          | 14        | 1.24%   |
| AMD Ryzen 7 PRO                      | 13        | 1.16%   |
| AMD Ryzen 5 PRO                      | 13        | 1.16%   |
| Intel Pentium                        | 11        | 0.98%   |
| Intel Core 2 Duo                     | 11        | 0.98%   |
| Intel Atom                           | 11        | 0.98%   |
| Intel Core i9                        | 10        | 0.89%   |
| AMD FX                               | 10        | 0.89%   |
| AMD A4                               | 7         | 0.62%   |
| Intel Core 2 Quad                    | 5         | 0.44%   |
| AMD A6                               | 5         | 0.44%   |
| Intel Pentium Silver                 | 4         | 0.36%   |
| Intel Pentium Dual-Core              | 4         | 0.36%   |
| AMD A10                              | 4         | 0.36%   |
| AMD Phenom II X6                     | 3         | 0.27%   |
| AMD A8                               | 3         | 0.27%   |
| AMD Ryzen Threadripper               | 2         | 0.18%   |
| AMD Phenom II X4                     | 2         | 0.18%   |
| Intel Pentium Gold                   | 1         | 0.09%   |
| Intel Pentium Dual                   | 1         | 0.09%   |
| Intel Core m5                        | 1         | 0.09%   |
| Intel Core m3                        | 1         | 0.09%   |
| Intel Core 2                         | 1         | 0.09%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.09%   |
| AMD Ryzen 3 PRO                      | 1         | 0.09%   |
| AMD PRO A10                          | 1         | 0.09%   |
| AMD E1                               | 1         | 0.09%   |
| AMD Athlon II X4                     | 1         | 0.09%   |
| AMD Athlon II X2                     | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 397       | 35.29%  |
| 2       | 244       | 21.69%  |
| 8       | 179       | 15.91%  |
| 6       | 174       | 15.47%  |
| 12      | 46        | 4.09%   |
| 14      | 26        | 2.31%   |
| 10      | 24        | 2.13%   |
| 16      | 22        | 1.96%   |
| 3       | 4         | 0.36%   |
| 1       | 3         | 0.27%   |
| 24      | 2         | 0.18%   |
| Unknown | 2         | 0.18%   |
| 36      | 1         | 0.09%   |
| 32      | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1116      | 99.2%   |
| 2       | 7         | 0.62%   |
| Unknown | 2         | 0.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 949       | 84.28%  |
| 1       | 175       | 15.54%  |
| Unknown | 2         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1121      | 99.64%  |
| 64-bit         | 4         | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 71        | 6.29%   |
| Unknown    | 59        | 5.23%   |
| 0x306a9    | 58        | 5.14%   |
| 0x906a3    | 50        | 4.43%   |
| 0x0a50000c | 49        | 4.34%   |
| 0x806ec    | 48        | 4.25%   |
| 0x806ea    | 46        | 4.07%   |
| 0x906ea    | 37        | 3.28%   |
| 0x08701021 | 36        | 3.19%   |
| 0x306c3    | 31        | 2.75%   |
| 0x806e9    | 29        | 2.57%   |
| 0x08600106 | 25        | 2.21%   |
| 0x206a7    | 24        | 2.13%   |
| 0x506e3    | 23        | 2.04%   |
| 0x406e3    | 23        | 2.04%   |
| 0x08608103 | 21        | 1.86%   |
| 0xa0652    | 19        | 1.68%   |
| 0x306d4    | 19        | 1.68%   |
| 0x906e9    | 18        | 1.59%   |
| 0x08108109 | 17        | 1.51%   |
| 0x906a4    | 16        | 1.42%   |
| 0x40651    | 16        | 1.42%   |
| 0x90672    | 15        | 1.33%   |
| 0x0a50000d | 15        | 1.33%   |
| 0x906ed    | 14        | 1.24%   |
| 0x806eb    | 13        | 1.15%   |
| 0x806d1    | 13        | 1.15%   |
| 0x1067a    | 13        | 1.15%   |
| 0x0a601203 | 13        | 1.15%   |
| 0x0a404102 | 13        | 1.15%   |
| 0x0a201016 | 13        | 1.15%   |
| 0x0a404101 | 12        | 1.06%   |
| 0x706e5    | 11        | 0.97%   |
| 0x706a8    | 11        | 0.97%   |
| 0x08600104 | 10        | 0.89%   |
| 0x806c2    | 9         | 0.8%    |
| 0x0a20120a | 9         | 0.8%    |
| 0x08701013 | 8         | 0.71%   |
| 0x0810100b | 8         | 0.71%   |
| 0x06006705 | 8         | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 224       | 19.91%  |
| Zen 3            | 112       | 9.96%   |
| Alderlake Hybrid | 89        | 7.91%   |
| Zen 2            | 88        | 7.82%   |
| TigerLake        | 85        | 7.56%   |
| Unknown          | 80        | 7.11%   |
| IvyBridge        | 59        | 5.24%   |
| Haswell          | 52        | 4.62%   |
| Skylake          | 50        | 4.44%   |
| SandyBridge      | 31        | 2.76%   |
| CometLake        | 31        | 2.76%   |
| Zen+             | 30        | 2.67%   |
| Icelake          | 30        | 2.67%   |
| Zen              | 21        | 1.87%   |
| Broadwell        | 20        | 1.78%   |
| Silvermont       | 15        | 1.33%   |
| Penryn           | 15        | 1.33%   |
| Westmere         | 13        | 1.16%   |
| Goldmont plus    | 13        | 1.16%   |
| Piledriver       | 12        | 1.07%   |
| Excavator        | 11        | 0.98%   |
| Core             | 9         | 0.8%    |
| Tremont          | 6         | 0.53%   |
| K10              | 6         | 0.53%   |
| Goldmont         | 5         | 0.44%   |
| Nehalem          | 4         | 0.36%   |
| Steamroller      | 3         | 0.27%   |
| Jaguar           | 3         | 0.27%   |
| Bonnell          | 3         | 0.27%   |
| K10 Llano        | 2         | 0.18%   |
| Bulldozer        | 2         | 0.18%   |
| K8 & K10 hybrid  | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 616       | 44.7%   |
| Nvidia            | 381       | 27.65%  |
| AMD               | 379       | 27.5%   |
| ASPEED Technology | 2         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 74        | 5.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 57        | 4.03%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 47        | 3.32%   |
| AMD Renoir                                                                | 41        | 2.9%    |
| Intel UHD Graphics 620                                                    | 40        | 2.83%   |
| Intel HD Graphics 620                                                     | 33        | 2.33%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 33        | 2.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 33        | 2.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 32        | 2.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 32        | 2.26%   |
| AMD Lucienne                                                              | 31        | 2.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 26        | 1.84%   |
| AMD Rembrandt [Radeon 680M]                                               | 25        | 1.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 23        | 1.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 22        | 1.56%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                | 20        | 1.41%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 18        | 1.27%   |
| Intel HD Graphics 5500                                                    | 18        | 1.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 18        | 1.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 17        | 1.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 16        | 1.13%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 16        | 1.13%   |
| AMD Raphael                                                               | 16        | 1.13%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                      | 16        | 1.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 15        | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 14        | 0.99%   |
| AMD Barcelo                                                               | 14        | 0.99%   |
| Nvidia GP108M [GeForce MX150]                                             | 13        | 0.92%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 13        | 0.92%   |
| Intel HD Graphics 630                                                     | 13        | 0.92%   |
| Intel HD Graphics 530                                                     | 13        | 0.92%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 12        | 0.85%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 11        | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 10        | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 10        | 0.71%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 10        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 9         | 0.64%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 9         | 0.64%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 9         | 0.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 9         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 403       | 35.79%  |
| 1 x AMD                 | 291       | 25.84%  |
| Intel + Nvidia          | 179       | 15.9%   |
| 1 x Nvidia              | 149       | 13.23%  |
| AMD + Nvidia            | 46        | 4.09%   |
| 2 x AMD                 | 24        | 2.13%   |
| Intel + AMD             | 18        | 1.6%    |
| 2 x Intel               | 6         | 0.53%   |
| Other                   | 5         | 0.44%   |
| 2 x Nvidia              | 2         | 0.18%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.09%   |
| Nvidia + ASPEED         | 1         | 0.09%   |
| Intel + 2 x Nvidia      | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 890       | 78.83%  |
| Proprietary | 210       | 18.6%   |
| Unknown     | 29        | 2.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 581       | 51.23%  |
| 0.01-0.5   | 141       | 12.43%  |
| 1.01-2.0   | 113       | 9.96%   |
| 7.01-8.0   | 88        | 7.76%   |
| 3.01-4.0   | 79        | 6.97%   |
| 0.51-1.0   | 56        | 4.94%   |
| 5.01-6.0   | 34        | 3%      |
| 8.01-16.0  | 33        | 2.91%   |
| 2.01-3.0   | 7         | 0.62%   |
| 16.01-24.0 | 2         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 166       | 12.62%  |
| AU Optronics            | 162       | 12.32%  |
| Chimei Innolux          | 124       | 9.43%   |
| Samsung Electronics     | 118       | 8.97%   |
| LG Display              | 98        | 7.45%   |
| Dell                    | 92        | 7%      |
| Goldstar                | 72        | 5.48%   |
| Hewlett-Packard         | 46        | 3.5%    |
| Acer                    | 38        | 2.89%   |
| AOC                     | 36        | 2.74%   |
| BenQ                    | 31        | 2.36%   |
| Lenovo                  | 29        | 2.21%   |
| Sharp                   | 26        | 1.98%   |
| CSO                     | 22        | 1.67%   |
| PANDA                   | 20        | 1.52%   |
| ASUSTek Computer        | 20        | 1.52%   |
| Philips                 | 18        | 1.37%   |
| Apple                   | 16        | 1.22%   |
| InfoVision              | 15        | 1.14%   |
| Ancor Communications    | 15        | 1.14%   |
| Sceptre Tech            | 9         | 0.68%   |
| MSI                     | 9         | 0.68%   |
| Iiyama                  | 9         | 0.68%   |
| Mi                      | 8         | 0.61%   |
| Gigabyte Technology     | 8         | 0.61%   |
| ViewSonic               | 6         | 0.46%   |
| Sony                    | 6         | 0.46%   |
| Panasonic               | 6         | 0.46%   |
| Toshiba                 | 5         | 0.38%   |
| JDI                     | 5         | 0.38%   |
| Eizo                    | 5         | 0.38%   |
| Chi Mei Optoelectronics | 5         | 0.38%   |
| TMX                     | 4         | 0.3%    |
| Pixio                   | 4         | 0.3%    |
| NEC Computers           | 4         | 0.3%    |
| ONN                     | 3         | 0.23%   |
| HUAWEI                  | 3         | 0.23%   |
| Vizio                   | 2         | 0.15%   |
| Vestel Elektronik       | 2         | 0.15%   |
| Unknown                 | 2         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 11        | 0.81%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 10        | 0.74%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 9         | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 8         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 8         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 6         | 0.44%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.44%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.37%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 5         | 0.37%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.37%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 5         | 0.37%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 4         | 0.29%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 4         | 0.29%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 4         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 0.29%   |
| Lenovo LEN L28u-30 LEN65FA 3840x2160 621x341mm 27.9-inch              | 4         | 0.29%   |
| CSO LCD Monitor CSO160A 2560x1600 345x215mm 16.0-inch                 | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 0.29%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 4         | 0.29%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 4         | 0.29%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 4         | 0.29%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 4         | 0.29%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 4         | 0.29%   |
| AU Optronics LCD Monitor AUOA08B 1920x1080 344x193mm 15.5-inch        | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 4         | 0.29%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 4         | 0.29%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 3         | 0.22%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 3         | 0.22%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 3         | 0.22%   |
| Mi Monitor XMI3446 3440x1440 797x334mm 34.0-inch                      | 3         | 0.22%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 621       | 49.96%  |
| 1366x768 (WXGA)    | 113       | 9.09%   |
| 3840x2160 (4K)     | 104       | 8.37%   |
| 2560x1440 (QHD)    | 103       | 8.29%   |
| 1920x1200 (WUXGA)  | 44        | 3.54%   |
| 2560x1600          | 42        | 3.38%   |
| 3440x1440          | 35        | 2.82%   |
| 1600x900 (HD+)     | 27        | 2.17%   |
| 2880x1800          | 21        | 1.69%   |
| 1280x1024 (SXGA)   | 19        | 1.53%   |
| 2560x1080          | 15        | 1.21%   |
| 1680x1050 (WSXGA+) | 13        | 1.05%   |
| 1280x800 (WXGA)    | 9         | 0.72%   |
| 1440x900 (WXGA+)   | 8         | 0.64%   |
| 2160x1440          | 6         | 0.48%   |
| 3840x2400          | 5         | 0.4%    |
| 2256x1504          | 5         | 0.4%    |
| 1360x768           | 5         | 0.4%    |
| 3000x2000          | 4         | 0.32%   |
| 2520x1680          | 4         | 0.32%   |
| 3840x1080          | 3         | 0.24%   |
| 3456x2160          | 3         | 0.24%   |
| 2736x1824          | 3         | 0.24%   |
| 1920x1280          | 3         | 0.24%   |
| 1600x1200          | 3         | 0.24%   |
| 3200x2000          | 2         | 0.16%   |
| 2288x1287          | 2         | 0.16%   |
| 2240x1400          | 2         | 0.16%   |
| 2160x1350          | 2         | 0.16%   |
| 1024x768 (XGA)     | 2         | 0.16%   |
| 800x1280           | 1         | 0.08%   |
| 3840x1600          | 1         | 0.08%   |
| 3200x1800 (QHD+)   | 1         | 0.08%   |
| 3120x1600          | 1         | 0.08%   |
| 3072x1920          | 1         | 0.08%   |
| 2880x864           | 1         | 0.08%   |
| 2880x1620          | 1         | 0.08%   |
| 2560x2880          | 1         | 0.08%   |
| 2400x1600          | 1         | 0.08%   |
| 2304x1440          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 339       | 25.43%  |
| 13      | 148       | 11.1%   |
| 14      | 138       | 10.35%  |
| 27      | 136       | 10.2%   |
| 24      | 97        | 7.28%   |
| 23      | 76        | 5.7%    |
| 21      | 52        | 3.9%    |
| 31      | 43        | 3.23%   |
| 34      | 42        | 3.15%   |
| 16      | 41        | 3.08%   |
| 17      | 35        | 2.63%   |
| 12      | 19        | 1.43%   |
| 20      | 14        | 1.05%   |
| 19      | 14        | 1.05%   |
| Unknown | 13        | 0.98%   |
| 25      | 11        | 0.83%   |
| 18      | 11        | 0.83%   |
| 40      | 10        | 0.75%   |
| 32      | 10        | 0.75%   |
| 26      | 10        | 0.75%   |
| 11      | 10        | 0.75%   |
| 22      | 9         | 0.68%   |
| 84      | 8         | 0.6%    |
| 29      | 6         | 0.45%   |
| 72      | 5         | 0.38%   |
| 54      | 4         | 0.3%    |
| 48      | 4         | 0.3%    |
| 28      | 4         | 0.3%    |
| 39      | 3         | 0.23%   |
| 10      | 3         | 0.23%   |
| 142     | 2         | 0.15%   |
| 52      | 2         | 0.15%   |
| 42      | 2         | 0.15%   |
| 36      | 2         | 0.15%   |
| 33      | 2         | 0.15%   |
| 65      | 1         | 0.08%   |
| 50      | 1         | 0.08%   |
| 47      | 1         | 0.08%   |
| 44      | 1         | 0.08%   |
| 43      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 578       | 44.36%  |
| 501-600        | 289       | 22.18%  |
| 201-300        | 108       | 8.29%   |
| 401-500        | 87        | 6.68%   |
| 601-700        | 68        | 5.22%   |
| 351-400        | 56        | 4.3%    |
| 701-800        | 55        | 4.22%   |
| 801-900        | 14        | 1.07%   |
| 1501-2000      | 13        | 1%      |
| 1001-1500      | 13        | 1%      |
| Unknown        | 13        | 1%      |
| 901-1000       | 6         | 0.46%   |
| More than 2000 | 2         | 0.15%   |
| 1-100          | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 895       | 77.29%  |
| 16/10   | 149       | 12.87%  |
| 21/9    | 48        | 4.15%   |
| 3/2     | 27        | 2.33%   |
| 5/4     | 15        | 1.3%    |
| 4/3     | 12        | 1.04%   |
| Unknown | 4         | 0.35%   |
| 32/9    | 3         | 0.26%   |
| 1.00    | 2         | 0.17%   |
| 3.33    | 1         | 0.09%   |
| 0.89    | 1         | 0.09%   |
| 0.67    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 343       | 25.87%  |
| 81-90          | 222       | 16.74%  |
| 201-250        | 181       | 13.65%  |
| 301-350        | 143       | 10.78%  |
| 351-500        | 103       | 7.77%   |
| 71-80          | 63        | 4.75%   |
| 151-200        | 50        | 3.77%   |
| 251-300        | 47        | 3.54%   |
| 111-120        | 36        | 2.71%   |
| 121-130        | 29        | 2.19%   |
| More than 1000 | 24        | 1.81%   |
| 501-1000       | 24        | 1.81%   |
| 61-70          | 15        | 1.13%   |
| Unknown        | 13        | 0.98%   |
| 51-60          | 12        | 0.9%    |
| 141-150        | 10        | 0.75%   |
| 91-100         | 6         | 0.45%   |
| 131-140        | 3         | 0.23%   |
| 41-50          | 1         | 0.08%   |
| 1-40           | 1         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 441       | 34.62%  |
| 51-100        | 335       | 26.3%   |
| 101-120       | 239       | 18.76%  |
| 161-240       | 172       | 13.5%   |
| More than 240 | 55        | 4.32%   |
| 1-50          | 19        | 1.49%   |
| Unknown       | 13        | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 842       | 73.92%  |
| 2     | 238       | 20.9%   |
| 0     | 31        | 2.72%   |
| 3     | 26        | 2.28%   |
| 5     | 1         | 0.09%   |
| 4     | 1         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 665       | 40.72%  |
| Realtek Semiconductor             | 572       | 35.03%  |
| Qualcomm Atheros                  | 114       | 6.98%   |
| MediaTek                          | 75        | 4.59%   |
| Broadcom                          | 50        | 3.06%   |
| TP-Link                           | 18        | 1.1%    |
| Ralink Technology                 | 10        | 0.61%   |
| Ralink                            | 9         | 0.55%   |
| Broadcom Limited                  | 9         | 0.55%   |
| Aquantia                          | 9         | 0.55%   |
| Sierra Wireless                   | 8         | 0.49%   |
| Qualcomm                          | 8         | 0.49%   |
| Lenovo                            | 8         | 0.49%   |
| Google                            | 7         | 0.43%   |
| ASIX Electronics                  | 7         | 0.43%   |
| D-Link                            | 6         | 0.37%   |
| Xiaomi                            | 5         | 0.31%   |
| Samsung Electronics               | 5         | 0.31%   |
| Microsoft                         | 5         | 0.31%   |
| Marvell Technology Group          | 5         | 0.31%   |
| ASUSTek Computer                  | 4         | 0.24%   |
| Hewlett-Packard                   | 3         | 0.18%   |
| Fibocom                           | 3         | 0.18%   |
| Dell                              | 3         | 0.18%   |
| Nvidia                            | 2         | 0.12%   |
| Huawei Technologies               | 2         | 0.12%   |
| Ericsson Business Mobile Networks | 2         | 0.12%   |
| DisplayLink                       | 2         | 0.12%   |
| Apple                             | 2         | 0.12%   |
| OPPO Electronics                  | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.06%   |
| NetGear                           | 1         | 0.06%   |
| Motorola PCS                      | 1         | 0.06%   |
| Microchip Technology              | 1         | 0.06%   |
| Mellanox Technologies             | 1         | 0.06%   |
| Linksys                           | 1         | 0.06%   |
| JMicron Technology                | 1         | 0.06%   |
| InterBiometrics                   | 1         | 0.06%   |
| ICS Advent                        | 1         | 0.06%   |
| D-Link System                     | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 361       | 18.7%   |
| Intel Wi-Fi 6 AX200                                               | 90        | 4.66%   |
| Intel Wi-Fi 6 AX201                                               | 71        | 3.68%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 57        | 2.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 48        | 2.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 47        | 2.44%   |
| Intel Wireless 8265 / 8275                                        | 44        | 2.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 41        | 2.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 2.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 38        | 1.97%   |
| Intel I211 Gigabit Network Connection                             | 34        | 1.76%   |
| Intel Ethernet Controller I225-V                                  | 32        | 1.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 29        | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 29        | 1.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 27        | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 24        | 1.24%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 23        | 1.19%   |
| Intel Wireless 8260                                               | 22        | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 22        | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 19        | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 18        | 0.93%   |
| Intel Wireless 7265                                               | 18        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                              | 18        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 18        | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 17        | 0.88%   |
| Intel Wireless 7260                                               | 17        | 0.88%   |
| Intel Wireless-AC 9260                                            | 15        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 15        | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 0.67%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 0.62%   |
| Realtek Realtek Network controller                                | 11        | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 11        | 0.57%   |
| Intel Ethernet Connection (10) I219-V                             | 11        | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 10        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.52%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 10        | 0.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 9         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 550       | 55.89%  |
| Realtek Semiconductor             | 150       | 15.24%  |
| Qualcomm Atheros                  | 93        | 9.45%   |
| MediaTek                          | 75        | 7.62%   |
| Broadcom                          | 32        | 3.25%   |
| TP-Link                           | 16        | 1.63%   |
| Ralink Technology                 | 10        | 1.02%   |
| Ralink                            | 9         | 0.91%   |
| Broadcom Limited                  | 9         | 0.91%   |
| Sierra Wireless                   | 8         | 0.81%   |
| Qualcomm                          | 5         | 0.51%   |
| Microsoft                         | 4         | 0.41%   |
| D-Link                            | 4         | 0.41%   |
| ASUSTek Computer                  | 4         | 0.41%   |
| Fibocom                           | 3         | 0.3%    |
| Dell                              | 3         | 0.3%    |
| Marvell Technology Group          | 2         | 0.2%    |
| Hewlett-Packard                   | 2         | 0.2%    |
| NetGear                           | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |
| Ericsson Business Mobile Networks | 1         | 0.1%    |
| D-Link System                     | 1         | 0.1%    |
| AboCom Systems                    | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 90        | 9.13%   |
| Intel Wi-Fi 6 AX201                                            | 71        | 7.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 57        | 5.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 47        | 4.77%   |
| Intel Wireless 8265 / 8275                                     | 44        | 4.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 38        | 3.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 29        | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 29        | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 24        | 2.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 23        | 2.33%   |
| Intel Wireless 8260                                            | 22        | 2.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 22        | 2.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21        | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 19        | 1.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 18        | 1.83%   |
| Intel Wireless 7265                                            | 18        | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 18        | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 17        | 1.72%   |
| Intel Wireless 7260                                            | 17        | 1.72%   |
| Intel Wireless-AC 9260                                         | 15        | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 15        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13        | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 11        | 1.12%   |
| Realtek Realtek Network controller                             | 10        | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 10        | 1.01%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 10        | 1.01%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 9         | 0.91%   |
| Intel Wireless 3165                                            | 9         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 0.71%   |
| Intel Wireless 3160                                            | 6         | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 0.61%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 0.61%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 0.61%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 0.61%   |
| Sierra Wireless EM7455                                         | 5         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 5         | 0.51%   |
| Realtek 802.11ac NIC                                           | 5         | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 499       | 54.84%  |
| Intel                         | 295       | 32.42%  |
| Broadcom                      | 26        | 2.86%   |
| Qualcomm Atheros              | 25        | 2.75%   |
| Aquantia                      | 9         | 0.99%   |
| Lenovo                        | 8         | 0.88%   |
| Google                        | 7         | 0.77%   |
| ASIX Electronics              | 7         | 0.77%   |
| Xiaomi                        | 5         | 0.55%   |
| Samsung Electronics           | 5         | 0.55%   |
| Qualcomm                      | 3         | 0.33%   |
| Marvell Technology Group      | 3         | 0.33%   |
| TP-Link                       | 2         | 0.22%   |
| Nvidia                        | 2         | 0.22%   |
| DisplayLink                   | 2         | 0.22%   |
| D-Link                        | 2         | 0.22%   |
| Apple                         | 2         | 0.22%   |
| OPPO Electronics              | 1         | 0.11%   |
| OnePlus Technology (Shenzhen) | 1         | 0.11%   |
| Motorola PCS                  | 1         | 0.11%   |
| Microsoft                     | 1         | 0.11%   |
| Mellanox Technologies         | 1         | 0.11%   |
| JMicron Technology            | 1         | 0.11%   |
| ICS Advent                    | 1         | 0.11%   |
| Hewlett-Packard               | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 361       | 38.61%  |
| Realtek RTL8125 2.5GbE Controller                                   | 48        | 5.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 41        | 4.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 39        | 4.17%   |
| Intel I211 Gigabit Network Connection                               | 34        | 3.64%   |
| Intel Ethernet Controller I225-V                                    | 32        | 3.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 27        | 2.89%   |
| Intel Ethernet Connection (4) I219-LM                               | 19        | 2.03%   |
| Intel Ethernet Connection (2) I219-V                                | 18        | 1.93%   |
| Intel Ethernet Connection (7) I219-V                                | 12        | 1.28%   |
| Intel Ethernet Connection (10) I219-V                               | 11        | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                               | 10        | 1.07%   |
| Intel Ethernet Connection I218-LM                                   | 9         | 0.96%   |
| Intel Ethernet Connection (4) I219-V                                | 9         | 0.96%   |
| Intel Ethernet Connection (13) I219-V                               | 9         | 0.96%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 8         | 0.86%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 8         | 0.86%   |
| Intel Ethernet Connection (16) I219-V                               | 8         | 0.86%   |
| Intel Ethernet Connection I219-LM                                   | 7         | 0.75%   |
| Intel Ethernet Connection (6) I219-V                                | 7         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                               | 7         | 0.75%   |
| Intel 82574L Gigabit Network Connection                             | 7         | 0.75%   |
| Intel Ethernet Connection I219-V                                    | 6         | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                       | 6         | 0.64%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 5         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 5         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 5         | 0.53%   |
| Lenovo ThinkPad TBT 3 Dock                                          | 5         | 0.53%   |
| Intel Ethernet Connection I217-LM                                   | 5         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                               | 5         | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                   | 5         | 0.53%   |
| Realtek Killer E3000 2.5GbE Controller                              | 4         | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 4         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 4         | 0.43%   |
| Intel Ethernet Connection I217-V                                    | 4         | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                               | 4         | 0.43%   |
| Intel Ethernet Connection (2) I218-V                                | 4         | 0.43%   |
| Intel 82579V Gigabit Network Connection                             | 4         | 0.43%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 4         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 940       | 52.57%  |
| Ethernet | 839       | 46.92%  |
| Modem    | 7         | 0.39%   |
| Unknown  | 2         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 782       | 65.66%  |
| Ethernet | 409       | 34.34%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 561       | 49.73%  |
| 1     | 501       | 44.41%  |
| 3     | 43        | 3.81%   |
| 0     | 16        | 1.42%   |
| 4     | 5         | 0.44%   |
| 9     | 1         | 0.09%   |
| 5     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 812       | 71.73%  |
| Yes  | 320       | 28.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 493       | 57.26%  |
| Realtek Semiconductor           | 90        | 10.45%  |
| Cambridge Silicon Radio         | 39        | 4.53%   |
| Foxconn / Hon Hai               | 37        | 4.3%    |
| IMC Networks                    | 36        | 4.18%   |
| Qualcomm Atheros Communications | 35        | 4.07%   |
| Lite-On Technology              | 31        | 3.6%    |
| Broadcom                        | 22        | 2.56%   |
| Apple                           | 17        | 1.97%   |
| MediaTek                        | 14        | 1.63%   |
| TP-Link                         | 13        | 1.51%   |
| Realtek                         | 13        | 1.51%   |
| ASUSTek Computer                | 4         | 0.46%   |
| Opticis                         | 3         | 0.35%   |
| Toshiba                         | 2         | 0.23%   |
| Marvell Semiconductor           | 2         | 0.23%   |
| Hewlett-Packard                 | 2         | 0.23%   |
| Belkin Components               | 2         | 0.23%   |
| USI                             | 1         | 0.12%   |
| Unknown                         | 1         | 0.12%   |
| SIN                             | 1         | 0.12%   |
| HTC (High Tech Computer)        | 1         | 0.12%   |
| Dell                            | 1         | 0.12%   |
| Corsair                         | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 168       | 19.47%  |
| Intel Bluetooth wireless interface                  | 102       | 11.82%  |
| Intel AX200 Bluetooth                               | 87        | 10.08%  |
| Realtek Bluetooth Radio                             | 73        | 8.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 71        | 8.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 39        | 4.52%   |
| Foxconn / Hon Hai Wireless_Device                   | 33        | 3.82%   |
| Intel AX210 Bluetooth                               | 30        | 3.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 24        | 2.78%   |
| Lite-On Bluetooth Device                            | 19        | 2.2%    |
| Intel Wireless-AC 3168 Bluetooth                    | 18        | 2.09%   |
| IMC Networks Wireless_Device                        | 15        | 1.74%   |
| MediaTek Wireless_Device                            | 14        | 1.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 1.62%   |
| TP-Link TPuLink UB500 Adapter                       | 13        | 1.51%   |
| Realtek Bluetooth Radio                             | 13        | 1.51%   |
| IMC Networks Bluetooth Radio                        | 12        | 1.39%   |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 1.27%   |
| Lite-On Wireless_Device                             | 8         | 0.93%   |
| Apple Bluetooth USB Host Controller                 | 8         | 0.93%   |
| Apple Bluetooth Host Controller                     | 8         | 0.93%   |
| IMC Networks Bluetooth Device                       | 7         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 0.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 6         | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.58%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 0.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.35%   |
| Opticis Bluetooth Radio                             | 3         | 0.35%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.35%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 3         | 0.35%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.23%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.23%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.23%   |
| Lite-On Bluetooth Radio                             | 2         | 0.23%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.23%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.23%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 0.23%   |
| USI Bluetooth Device                                | 1         | 0.12%   |
| Unknown Bluetooth Device                            | 1         | 0.12%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 736       | 44.23%  |
| AMD                                  | 409       | 24.58%  |
| Nvidia                               | 264       | 15.87%  |
| C-Media Electronics                  | 30        | 1.8%    |
| Logitech                             | 23        | 1.38%   |
| Razer USA                            | 13        | 0.78%   |
| Lenovo                               | 11        | 0.66%   |
| Kingston Technology                  | 10        | 0.6%    |
| Creative Labs                        | 10        | 0.6%    |
| ASUSTek Computer                     | 9         | 0.54%   |
| SteelSeries ApS                      | 8         | 0.48%   |
| Plantronics                          | 8         | 0.48%   |
| GN Netcom                            | 8         | 0.48%   |
| Realtek Semiconductor                | 7         | 0.42%   |
| Focusrite-Novation                   | 7         | 0.42%   |
| Generalplus Technology               | 6         | 0.36%   |
| Corsair                              | 5         | 0.3%    |
| VIA Technologies                     | 4         | 0.24%   |
| Sony                                 | 4         | 0.24%   |
| Samson Technologies                  | 4         | 0.24%   |
| RODE Microphones                     | 4         | 0.24%   |
| Micro Star International             | 4         | 0.24%   |
| JMTek                                | 4         | 0.24%   |
| Hewlett-Packard                      | 4         | 0.24%   |
| Creative Technology                  | 4         | 0.24%   |
| Texas Instruments                    | 3         | 0.18%   |
| Samsung Electronics                  | 3         | 0.18%   |
| Giga-Byte Technology                 | 3         | 0.18%   |
| Blue Microphones                     | 3         | 0.18%   |
| Asahi Kasei Microsystems             | 3         | 0.18%   |
| Apple                                | 3         | 0.18%   |
| XMOS                                 | 2         | 0.12%   |
| Trust                                | 2         | 0.12%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.12%   |
| PreSonus Audio Electronics           | 2         | 0.12%   |
| Medeli Electronics                   | 2         | 0.12%   |
| LG Electronics                       | 2         | 0.12%   |
| FiiO Electronics Technology          | 2         | 0.12%   |
| Dell                                 | 2         | 0.12%   |
| Antlion Audio                        | 2         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 221       | 10.9%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 137       | 6.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 102       | 5.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 84        | 4.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 80        | 3.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 67        | 3.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 60        | 2.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 50        | 2.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 47        | 2.32%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 40        | 1.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 37        | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 36        | 1.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 35        | 1.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 34        | 1.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 26        | 1.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 25        | 1.23%   |
| Nvidia GA106 High Definition Audio Controller                              | 24        | 1.18%   |
| Intel Comet Lake PCH cAVS                                                  | 24        | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23        | 1.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 23        | 1.13%   |
| Nvidia TU106 High Definition Audio Controller                              | 21        | 1.04%   |
| Nvidia GA104 High Definition Audio Controller                              | 21        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 20        | 0.99%   |
| Intel Alder Lake-S HD Audio Controller                                     | 20        | 0.99%   |
| Intel 200 Series PCH HD Audio                                              | 20        | 0.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 19        | 0.94%   |
| Intel Broadwell-U Audio Controller                                         | 19        | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 18        | 0.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 0.79%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                              | 15        | 0.74%   |
| Nvidia Audio device                                                        | 15        | 0.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15        | 0.74%   |
| AMD Navi 10 HDMI Audio                                                     | 14        | 0.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14        | 0.69%   |
| Nvidia TU104 HD Audio Controller                                           | 13        | 0.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 13        | 0.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13        | 0.64%   |
| Nvidia GP106 High Definition Audio Controller                              | 12        | 0.59%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 12        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 156       | 24.07%  |
| SK hynix            | 118       | 18.21%  |
| Micron Technology   | 80        | 12.35%  |
| Kingston            | 60        | 9.26%   |
| Crucial             | 38        | 5.86%   |
| G.Skill             | 35        | 5.4%    |
| Corsair             | 33        | 5.09%   |
| Unknown             | 21        | 3.24%   |
| A-DATA Technology   | 20        | 3.09%   |
| Unknown             | 14        | 2.16%   |
| Ramaxel Technology  | 11        | 1.7%    |
| Team                | 9         | 1.39%   |
| Unknown (ABCD)      | 5         | 0.77%   |
| Elpida              | 5         | 0.77%   |
| Smart               | 4         | 0.62%   |
| Patriot             | 4         | 0.62%   |
| Nanya Technology    | 4         | 0.62%   |
| Avant               | 3         | 0.46%   |
| Unifosa             | 2         | 0.31%   |
| Goldkey             | 2         | 0.31%   |
| Gold Key            | 2         | 0.31%   |
| Apacer              | 2         | 0.31%   |
| Wilk                | 1         | 0.15%   |
| Transcend           | 1         | 0.15%   |
| Timetec             | 1         | 0.15%   |
| Teikon              | 1         | 0.15%   |
| Smart Brazil        | 1         | 0.15%   |
| Silicon Power       | 1         | 0.15%   |
| Qumo                | 1         | 0.15%   |
| Qimonda             | 1         | 0.15%   |
| PUSKILL             | 1         | 0.15%   |
| PNY                 | 1         | 0.15%   |
| Miron               | 1         | 0.15%   |
| Lexar Co Limited    | 1         | 0.15%   |
| Lexar               | 1         | 0.15%   |
| Kllisre             | 1         | 0.15%   |
| High Bridge         | 1         | 0.15%   |
| Hewlett-Packard     | 1         | 0.15%   |
| GOODRAM             | 1         | 0.15%   |
| ASint Technology    | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 14        | 2.03%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 1.74%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 9         | 1.31%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 1.16%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.16%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 8         | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 7         | 1.02%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 1.02%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.87%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 6         | 0.87%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.73%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 5         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.58%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.58%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 4         | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.58%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.58%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.58%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 4         | 0.58%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 4         | 0.58%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.44%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 3         | 0.44%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.44%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 3         | 0.44%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 3         | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.44%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.44%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 3         | 0.44%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 3         | 0.44%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 3         | 0.44%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 3         | 0.44%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 3         | 0.44%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.44%   |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s          | 3         | 0.44%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 334       | 60.07%  |
| DDR3    | 93        | 16.73%  |
| DDR5    | 34        | 6.12%   |
| LPDDR4  | 32        | 5.76%   |
| LPDDR5  | 23        | 4.14%   |
| LPDDR3  | 21        | 3.78%   |
| DDR2    | 11        | 1.98%   |
| Unknown | 5         | 0.9%    |
| SDRAM   | 3         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 315       | 55.95%  |
| DIMM         | 151       | 26.82%  |
| Row Of Chips | 89        | 15.81%  |
| Chip         | 3         | 0.53%   |
| Unknown      | 3         | 0.53%   |
| FB-DIMM      | 2         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 278       | 47.77%  |
| 4096  | 122       | 20.96%  |
| 16384 | 104       | 17.87%  |
| 2048  | 38        | 6.53%   |
| 32768 | 33        | 5.67%   |
| 1024  | 7         | 1.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 166       | 28.09%  |
| 2667    | 88        | 14.89%  |
| 1600    | 64        | 10.83%  |
| 2400    | 43        | 7.28%   |
| 2133    | 26        | 4.4%    |
| 4800    | 25        | 4.23%   |
| 6400    | 23        | 3.89%   |
| 3600    | 20        | 3.38%   |
| 1333    | 18        | 3.05%   |
| 4267    | 14        | 2.37%   |
| 1867    | 12        | 2.03%   |
| 3466    | 9         | 1.52%   |
| 4266    | 8         | 1.35%   |
| 800     | 7         | 1.18%   |
| 3266    | 5         | 0.85%   |
| 667     | 5         | 0.85%   |
| 5200    | 4         | 0.68%   |
| 3866    | 4         | 0.68%   |
| 3733    | 4         | 0.68%   |
| 1800    | 4         | 0.68%   |
| 1334    | 4         | 0.68%   |
| 5600    | 3         | 0.51%   |
| 3000    | 3         | 0.51%   |
| 2666    | 3         | 0.51%   |
| 1866    | 3         | 0.51%   |
| 8400    | 2         | 0.34%   |
| 3400    | 2         | 0.34%   |
| 3333    | 2         | 0.34%   |
| 1066    | 2         | 0.34%   |
| 933     | 2         | 0.34%   |
| 533     | 2         | 0.34%   |
| 400     | 2         | 0.34%   |
| Unknown | 2         | 0.34%   |
| 5808    | 1         | 0.17%   |
| 4133    | 1         | 0.17%   |
| 3800    | 1         | 0.17%   |
| 3666    | 1         | 0.17%   |
| 3100    | 1         | 0.17%   |
| 2933    | 1         | 0.17%   |
| 2800    | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 5         | 31.25%  |
| Brother Industries    | 5         | 31.25%  |
| Seiko Epson           | 2         | 12.5%   |
| Samsung Electronics   | 1         | 6.25%   |
| Prolific Technology   | 1         | 6.25%   |
| Lexmark International | 1         | 6.25%   |
| Canon                 | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson Printer           | 1         | 6.25%   |
| Seiko Epson L300 Series       | 1         | 6.25%   |
| Samsung ML-2855 Series        | 1         | 6.25%   |
| Prolific PL2305 Parallel Port | 1         | 6.25%   |
| Lexmark International B2236dw | 1         | 6.25%   |
| HP Officejet 2620 series      | 1         | 6.25%   |
| HP LaserJet 1010              | 1         | 6.25%   |
| HP ENVY Photo 7800 series     | 1         | 6.25%   |
| HP DeskJet F300 series        | 1         | 6.25%   |
| HP DeskJet 3630 series        | 1         | 6.25%   |
| Canon LiDE 400                | 1         | 6.25%   |
| Brother MFC-7460DN            | 1         | 6.25%   |
| Brother HL-L2350DW series     | 1         | 6.25%   |
| Brother HL-L2300D series      | 1         | 6.25%   |
| Brother DCP-L2510D series     | 1         | 6.25%   |
| Brother DCP-1600              | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 183       | 23.05%  |
| IMC Networks                           | 99        | 12.47%  |
| Microdia                               | 73        | 9.19%   |
| Quanta                                 | 66        | 8.31%   |
| Acer                                   | 60        | 7.56%   |
| Logitech                               | 53        | 6.68%   |
| Realtek Semiconductor                  | 37        | 4.66%   |
| Sunplus Innovation Technology          | 29        | 3.65%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 3.27%   |
| Syntek                                 | 21        | 2.64%   |
| Luxvisions Innotech Limited            | 21        | 2.64%   |
| Apple                                  | 20        | 2.52%   |
| Lite-On Technology                     | 16        | 2.02%   |
| Sonix Technology                       | 12        | 1.51%   |
| Microsoft                              | 10        | 1.26%   |
| Silicon Motion                         | 6         | 0.76%   |
| Suyin                                  | 5         | 0.63%   |
| SunplusIT                              | 5         | 0.63%   |
| Samsung Electronics                    | 5         | 0.63%   |
| Tripath Technology                     | 4         | 0.5%    |
| KYE Systems (Mouse Systems)            | 4         | 0.5%    |
| MacroSilicon                           | 3         | 0.38%   |
| LG Electronics                         | 3         | 0.38%   |
| Alcor Micro                            | 3         | 0.38%   |
| Trust                                  | 2         | 0.25%   |
| Lenovo                                 | 2         | 0.25%   |
| icSpring                               | 2         | 0.25%   |
| Hewlett-Packard                        | 2         | 0.25%   |
| ARC International                      | 2         | 0.25%   |
| A4Tech                                 | 2         | 0.25%   |
| WCM_USB                                | 1         | 0.13%   |
| USB Camera CS                          | 1         | 0.13%   |
| Unknown                                | 1         | 0.13%   |
| SN0002                                 | 1         | 0.13%   |
| Smartronix                             | 1         | 0.13%   |
| Razer USA                              | 1         | 0.13%   |
| Primax Electronics                     | 1         | 0.13%   |
| Novatek Microelectronics               | 1         | 0.13%   |
| Nikon                                  | 1         | 0.13%   |
| Integrated Technology Express          | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 64        | 8.02%   |
| Microdia Integrated_Webcam_HD                        | 40        | 5.01%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 34        | 4.26%   |
| IMC Networks Integrated Camera                       | 28        | 3.51%   |
| Acer Integrated Camera                               | 26        | 3.26%   |
| Realtek Integrated_Webcam_HD                         | 23        | 2.88%   |
| Chicony HD Webcam                                    | 17        | 2.13%   |
| Syntek Integrated Camera                             | 13        | 1.63%   |
| Quanta HD User Facing                                | 13        | 1.63%   |
| Quanta HP HD Camera                                  | 11        | 1.38%   |
| IMC Networks HD Camera                               | 11        | 1.38%   |
| Logitech HD Pro Webcam C920                          | 9         | 1.13%   |
| Chicony HP TrueVision HD Camera                      | 9         | 1.13%   |
| Sonix USB2.0 HD UVC WebCam                           | 8         | 1%      |
| Quanta HP Wide Vision HD Camera                      | 8         | 1%      |
| Microdia Integrated_Webcam_FHD                       | 8         | 1%      |
| Lite-On Integrated Camera                            | 8         | 1%      |
| Chicony Integrated Camera (1280x720@30)              | 8         | 1%      |
| Chicony HP Wide Vision HD Camera                     | 8         | 1%      |
| Apple iPhone 5/5C/5S/6/SE                            | 8         | 1%      |
| Sunplus Integrated_Webcam_HD                         | 7         | 0.88%   |
| Quanta HP TrueVision HD Camera                       | 7         | 0.88%   |
| Logitech Webcam C270                                 | 7         | 0.88%   |
| Chicony HD User Facing                               | 7         | 0.88%   |
| Quanta HD Webcam                                     | 6         | 0.75%   |
| Logitech C922 Pro Stream Webcam                      | 6         | 0.75%   |
| Chicony HP HD Camera                                 | 6         | 0.75%   |
| Chicony EasyCamera                                   | 6         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 6         | 0.75%   |
| Apple FaceTime HD Camera (Built-in)                  | 6         | 0.75%   |
| Acer HD Webcam                                       | 6         | 0.75%   |
| Samsung Galaxy A5 (MTP)                              | 5         | 0.63%   |
| Quanta VGA WebCam                                    | 5         | 0.63%   |
| Microdia Webcam Vitade AF                            | 5         | 0.63%   |
| Microdia USB 2.0 Camera                              | 5         | 0.63%   |
| Luxvisions Innotech Limited Integrated Camera        | 5         | 0.63%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 0.63%   |
| Logitech HD Webcam C525                              | 5         | 0.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 5         | 0.63%   |
| Chicony USB 2.0 Camera                               | 5         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 76        | 41.08%  |
| Shenzhen Goodix Technology         | 45        | 24.32%  |
| Validity Sensors                   | 36        | 19.46%  |
| Elan Microelectronics              | 16        | 8.65%   |
| LighTuning Technology              | 5         | 2.7%    |
| AuthenTec                          | 3         | 1.62%   |
| Upek                               | 2         | 1.08%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.54%   |
| Microsoft                          | 1         | 0.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 33        | 17.84%  |
| Shenzhen Goodix  Fingerprint Device                                        | 32        | 17.3%   |
| Unknown                                                                    | 25        | 13.51%  |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 5.95%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 4.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 4.86%   |
| Elan ELAN:ARM-M4                                                           | 9         | 4.86%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 3.78%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 3.78%   |
| Synaptics  WBDI                                                            | 6         | 3.24%   |
| Elan ELAN:Fingerprint                                                      | 6         | 3.24%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.16%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 1.08%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.08%   |
| LighTuning Fingerprint Sensor                                              | 2         | 1.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.08%   |
| AuthenTec AES1600                                                          | 2         | 1.08%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.54%   |
| Validity Sensors VFS491                                                    | 1         | 0.54%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.54%   |
| Synaptics WBDI Device                                                      | 1         | 0.54%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.54%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.54%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.54%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.54%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.54%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.54%   |
| AuthenTec AES2810                                                          | 1         | 0.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 31        | 46.97%  |
| Broadcom              | 25        | 37.88%  |
| Upek                  | 4         | 6.06%   |
| Lenovo                | 3         | 4.55%   |
| Yubico.com            | 1         | 1.52%   |
| O2 Micro              | 1         | 1.52%   |
| Gemalto (was Gemplus) | 1         | 1.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 31        | 46.97%  |
| Broadcom 58200                                                               | 11        | 16.67%  |
| Broadcom 5880                                                                | 7         | 10.61%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 7.58%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 6.06%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.03%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.52%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 749       | 65.93%  |
| 1     | 322       | 28.35%  |
| 2     | 45        | 3.96%   |
| 3     | 10        | 0.88%   |
| 4     | 6         | 0.53%   |
| 5     | 3         | 0.26%   |
| 8     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 183       | 39.52%  |
| Graphics card            | 103       | 22.25%  |
| Multimedia controller    | 55        | 11.88%  |
| Net/wireless             | 31        | 6.7%    |
| Camera                   | 28        | 6.05%   |
| Chipcard                 | 15        | 3.24%   |
| Sound                    | 13        | 2.81%   |
| Communication controller | 8         | 1.73%   |
| Card reader              | 7         | 1.51%   |
| Net/ethernet             | 5         | 1.08%   |
| Bluetooth                | 5         | 1.08%   |
| Storage/raid             | 3         | 0.65%   |
| Network                  | 3         | 0.65%   |
| Unassigned class         | 2         | 0.43%   |
| Storage                  | 1         | 0.22%   |
| Modem                    | 1         | 0.22%   |

