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

Total: 3108

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f3e1bb3812](https://linux-hardware.org/?probe=f3e1bb3812) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [483fc71762](https://linux-hardware.org/?probe=483fc71762) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [0a1e2a7f23](https://linux-hardware.org/?probe=0a1e2a7f23) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [742b085257](https://linux-hardware.org/?probe=742b085257) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [836fcda626](https://linux-hardware.org/?probe=836fcda626) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [3e208faa6e](https://linux-hardware.org/?probe=3e208faa6e) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f20a32551b](https://linux-hardware.org/?probe=f20a32551b) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [bd9c532bbc](https://linux-hardware.org/?probe=bd9c532bbc) | Aug 10, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [e323e9cd7e](https://linux-hardware.org/?probe=e323e9cd7e) | Aug 10, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [a3b9be2f56](https://linux-hardware.org/?probe=a3b9be2f56) | Aug 10, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [4d7fbea818](https://linux-hardware.org/?probe=4d7fbea818) | Aug 09, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [bdc11616d7](https://linux-hardware.org/?probe=bdc11616d7) | Aug 08, 2023 |
| HP            | Unknown                     | Notebook    | [567a10ceb2](https://linux-hardware.org/?probe=567a10ceb2) | Aug 08, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | Notebook    | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [3d49205e68](https://linux-hardware.org/?probe=3d49205e68) | Aug 06, 2023 |
| Toshiba       | Satellite C670D-11P         | Notebook    | [a5c49672d6](https://linux-hardware.org/?probe=a5c49672d6) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [e3fd0f4808](https://linux-hardware.org/?probe=e3fd0f4808) | Aug 04, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [f420f3e1e6](https://linux-hardware.org/?probe=f420f3e1e6) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | Desktop     | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNP           | Notebook    | [508c18e563](https://linux-hardware.org/?probe=508c18e563) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [53c9161fc5](https://linux-hardware.org/?probe=53c9161fc5) | Aug 03, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [a449d60316](https://linux-hardware.org/?probe=a449d60316) | Aug 03, 2023 |
| Dell          | Latitude E7240              | Notebook    | [87a0310cf0](https://linux-hardware.org/?probe=87a0310cf0) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [e0c07e2d0c](https://linux-hardware.org/?probe=e0c07e2d0c) | Aug 02, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [a06a335d70](https://linux-hardware.org/?probe=a06a335d70) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c88a2ad597](https://linux-hardware.org/?probe=c88a2ad597) | Aug 01, 2023 |
| HP            | Unknown                     | Notebook    | [a4d8377dfa](https://linux-hardware.org/?probe=a4d8377dfa) | Aug 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [d8272e8eeb](https://linux-hardware.org/?probe=d8272e8eeb) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [436e1e4e01](https://linux-hardware.org/?probe=436e1e4e01) | Jul 29, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [7d5b443b84](https://linux-hardware.org/?probe=7d5b443b84) | Jul 29, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [1b9bb7c266](https://linux-hardware.org/?probe=1b9bb7c266) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [1950bcc818](https://linux-hardware.org/?probe=1950bcc818) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Acer          | Spin SP111-31               | Convertible | [003fa350a2](https://linux-hardware.org/?probe=003fa350a2) | Jul 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S55L00    | Notebook    | [5b3742984b](https://linux-hardware.org/?probe=5b3742984b) | Jul 27, 2023 |
| Lenovo        | 3743 SDK0J40700 WIN 3258... | Desktop     | [546f011b1a](https://linux-hardware.org/?probe=546f011b1a) | Jul 27, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [47e831a79a](https://linux-hardware.org/?probe=47e831a79a) | Jul 26, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [4fc2e4c331](https://linux-hardware.org/?probe=4fc2e4c331) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [a060c0999b](https://linux-hardware.org/?probe=a060c0999b) | Jul 26, 2023 |
| Lenovo        | ThinkPad E480 20KN001QMX    | Notebook    | [1ff9753d17](https://linux-hardware.org/?probe=1ff9753d17) | Jul 25, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [ac63d4a30c](https://linux-hardware.org/?probe=ac63d4a30c) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fa1cd70a3](https://linux-hardware.org/?probe=9fa1cd70a3) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1e169f0ba8](https://linux-hardware.org/?probe=1e169f0ba8) | Jul 23, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [52541ec1ed](https://linux-hardware.org/?probe=52541ec1ed) | Jul 23, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [f291f72d81](https://linux-hardware.org/?probe=f291f72d81) | Jul 23, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [bbd3181f1f](https://linux-hardware.org/?probe=bbd3181f1f) | Jul 22, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [9ab47777ca](https://linux-hardware.org/?probe=9ab47777ca) | Jul 21, 2023 |
| HP            | ProBook 4530s               | Notebook    | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [c3994db136](https://linux-hardware.org/?probe=c3994db136) | Jul 21, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [b1a5c8b10d](https://linux-hardware.org/?probe=b1a5c8b10d) | Jul 20, 2023 |
| HP            | 15                          | Notebook    | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| ASUSTek       | A_F_K20BF                   | Desktop     | [f2ae40130e](https://linux-hardware.org/?probe=f2ae40130e) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [805d981913](https://linux-hardware.org/?probe=805d981913) | Jul 19, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [db2a22c2eb](https://linux-hardware.org/?probe=db2a22c2eb) | Jul 19, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [b12aa2eb63](https://linux-hardware.org/?probe=b12aa2eb63) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | Notebook    | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Dell          | 0MN1TX A01                  | Desktop     | [696072cf7c](https://linux-hardware.org/?probe=696072cf7c) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [d2c6c9bcba](https://linux-hardware.org/?probe=d2c6c9bcba) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f4bc253638](https://linux-hardware.org/?probe=f4bc253638) | Jul 17, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [e707b1595f](https://linux-hardware.org/?probe=e707b1595f) | Jul 17, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [65a6e11166](https://linux-hardware.org/?probe=65a6e11166) | Jul 17, 2023 |
| MSI           | GF65 Thin 10SER             | Notebook    | [27966135e2](https://linux-hardware.org/?probe=27966135e2) | Jul 16, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [21950296b4](https://linux-hardware.org/?probe=21950296b4) | Jul 16, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [0063ae1936](https://linux-hardware.org/?probe=0063ae1936) | Jul 16, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [6758dfb731](https://linux-hardware.org/?probe=6758dfb731) | Jul 15, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [801eb1eb3c](https://linux-hardware.org/?probe=801eb1eb3c) | Jul 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Alienware     | x15 R1                      | Notebook    | [a72051a57e](https://linux-hardware.org/?probe=a72051a57e) | Jul 13, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | Notebook    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ab0a96405e](https://linux-hardware.org/?probe=ab0a96405e) | Jul 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [30403bcd32](https://linux-hardware.org/?probe=30403bcd32) | Jul 12, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [c3b936e87a](https://linux-hardware.org/?probe=c3b936e87a) | Jul 12, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [161a78ce7d](https://linux-hardware.org/?probe=161a78ce7d) | Jul 11, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [cfc5e42de6](https://linux-hardware.org/?probe=cfc5e42de6) | Jul 11, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d0035bb703](https://linux-hardware.org/?probe=d0035bb703) | Jul 10, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [2992a0aea9](https://linux-hardware.org/?probe=2992a0aea9) | Jul 10, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [57cc83ff44](https://linux-hardware.org/?probe=57cc83ff44) | Jul 10, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [4b33cf2e09](https://linux-hardware.org/?probe=4b33cf2e09) | Jul 09, 2023 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [c7d3e6a151](https://linux-hardware.org/?probe=c7d3e6a151) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [ecd8f6cdd2](https://linux-hardware.org/?probe=ecd8f6cdd2) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [0ea27ea171](https://linux-hardware.org/?probe=0ea27ea171) | Jul 09, 2023 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [bdf5ce2163](https://linux-hardware.org/?probe=bdf5ce2163) | Jul 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [5f28888f0d](https://linux-hardware.org/?probe=5f28888f0d) | Jul 06, 2023 |
| Medion        | ML-210007                   | Notebook    | [192b83694f](https://linux-hardware.org/?probe=192b83694f) | Jul 06, 2023 |
| Medion        | ML-210007                   | Notebook    | [8bc97d58d2](https://linux-hardware.org/?probe=8bc97d58d2) | Jul 06, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [9c0f0d40b9](https://linux-hardware.org/?probe=9c0f0d40b9) | Jul 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [348b9a4a73](https://linux-hardware.org/?probe=348b9a4a73) | Jul 05, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [fceaf9bea9](https://linux-hardware.org/?probe=fceaf9bea9) | Jul 04, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [b6d0f85342](https://linux-hardware.org/?probe=b6d0f85342) | Jul 04, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [e2c9e04a7c](https://linux-hardware.org/?probe=e2c9e04a7c) | Jul 04, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [50b65edbc0](https://linux-hardware.org/?probe=50b65edbc0) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [e0fc7e357f](https://linux-hardware.org/?probe=e0fc7e357f) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [0ca36f92b8](https://linux-hardware.org/?probe=0ca36f92b8) | Jul 03, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [066d1a2fa8](https://linux-hardware.org/?probe=066d1a2fa8) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80810e133e](https://linux-hardware.org/?probe=80810e133e) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [48df5942cf](https://linux-hardware.org/?probe=48df5942cf) | Jul 02, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f91dbee23b](https://linux-hardware.org/?probe=f91dbee23b) | Jul 02, 2023 |
| Acer          | Predator G9-593             | Notebook    | [127df9999f](https://linux-hardware.org/?probe=127df9999f) | Jul 01, 2023 |
| TrekStor      | YOURBOOK C11B               | Convertible | [8c2340f01f](https://linux-hardware.org/?probe=8c2340f01f) | Jul 01, 2023 |
| Acer          | Predator G9-593             | Notebook    | [d4dca39223](https://linux-hardware.org/?probe=d4dca39223) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [7f9164d1e0](https://linux-hardware.org/?probe=7f9164d1e0) | Jun 29, 2023 |
| Acer          | Aspire XC-840               | Desktop     | [76c750aae4](https://linux-hardware.org/?probe=76c750aae4) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | Notebook    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [a91acc04b6](https://linux-hardware.org/?probe=a91acc04b6) | Jun 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [cc161cc65b](https://linux-hardware.org/?probe=cc161cc65b) | Jun 28, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [32e4f74711](https://linux-hardware.org/?probe=32e4f74711) | Jun 28, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [9450fc030e](https://linux-hardware.org/?probe=9450fc030e) | Jun 27, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [566e7a4396](https://linux-hardware.org/?probe=566e7a4396) | Jun 26, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [165584477b](https://linux-hardware.org/?probe=165584477b) | Jun 25, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [3c8a1b23bb](https://linux-hardware.org/?probe=3c8a1b23bb) | Jun 24, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [e10aa58dda](https://linux-hardware.org/?probe=e10aa58dda) | Jun 24, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [510d2844bd](https://linux-hardware.org/?probe=510d2844bd) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [56208916c9](https://linux-hardware.org/?probe=56208916c9) | Jun 23, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [3d506cafad](https://linux-hardware.org/?probe=3d506cafad) | Jun 22, 2023 |
| MSI           | GX60 1AC                    | Notebook    | [8e15fea8cd](https://linux-hardware.org/?probe=8e15fea8cd) | Jun 22, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7ac67acfed](https://linux-hardware.org/?probe=7ac67acfed) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [a7b7b2c413](https://linux-hardware.org/?probe=a7b7b2c413) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d4bd011ff9](https://linux-hardware.org/?probe=d4bd011ff9) | Jun 21, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [30f85c0f2e](https://linux-hardware.org/?probe=30f85c0f2e) | Jun 21, 2023 |
| MSI           | Katana GF76 12UD            | Notebook    | [1897f5f0cb](https://linux-hardware.org/?probe=1897f5f0cb) | Jun 20, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9e30c629f3](https://linux-hardware.org/?probe=9e30c629f3) | Jun 19, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [6579287940](https://linux-hardware.org/?probe=6579287940) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0c5693c658](https://linux-hardware.org/?probe=0c5693c658) | Jun 18, 2023 |
| OEM           | ALDER LAKE JHS64S           | Desktop     | [0eb1dc0b8e](https://linux-hardware.org/?probe=0eb1dc0b8e) | Jun 16, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [b0361fedbc](https://linux-hardware.org/?probe=b0361fedbc) | Jun 16, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [da6bfc34aa](https://linux-hardware.org/?probe=da6bfc34aa) | Jun 15, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [74a69e5cca](https://linux-hardware.org/?probe=74a69e5cca) | Jun 15, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [a0e0ea6aa1](https://linux-hardware.org/?probe=a0e0ea6aa1) | Jun 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [91af63490c](https://linux-hardware.org/?probe=91af63490c) | Jun 15, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [294cbcd9cd](https://linux-hardware.org/?probe=294cbcd9cd) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [11fa244fa5](https://linux-hardware.org/?probe=11fa244fa5) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [e9aeb26aeb](https://linux-hardware.org/?probe=e9aeb26aeb) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [f675b70f23](https://linux-hardware.org/?probe=f675b70f23) | Jun 14, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [bbcb31d079](https://linux-hardware.org/?probe=bbcb31d079) | Jun 14, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [ff01549321](https://linux-hardware.org/?probe=ff01549321) | Jun 14, 2023 |
| Dell          | Latitude 7480               | Notebook    | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [3a8338d906](https://linux-hardware.org/?probe=3a8338d906) | Jun 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [cda9f3da9c](https://linux-hardware.org/?probe=cda9f3da9c) | Jun 13, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [93cd1fd89c](https://linux-hardware.org/?probe=93cd1fd89c) | Jun 13, 2023 |
| Dell          | Latitude 3320               | Notebook    | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | Notebook    | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [88fc978934](https://linux-hardware.org/?probe=88fc978934) | Jun 12, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [0b737be0c6](https://linux-hardware.org/?probe=0b737be0c6) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5f4978fc61](https://linux-hardware.org/?probe=5f4978fc61) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8a3bd0a576](https://linux-hardware.org/?probe=8a3bd0a576) | Jun 11, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [2838a84809](https://linux-hardware.org/?probe=2838a84809) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [d58405f7c1](https://linux-hardware.org/?probe=d58405f7c1) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [86b377710d](https://linux-hardware.org/?probe=86b377710d) | Jun 10, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [2c8c27897b](https://linux-hardware.org/?probe=2c8c27897b) | Jun 09, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [8fa2e2acc9](https://linux-hardware.org/?probe=8fa2e2acc9) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6a98d856ee](https://linux-hardware.org/?probe=6a98d856ee) | Jun 07, 2023 |
| Dell          | Latitude 3340               | Notebook    | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [4d71226d7c](https://linux-hardware.org/?probe=4d71226d7c) | Jun 04, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [48eb50cc43](https://linux-hardware.org/?probe=48eb50cc43) | Jun 03, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [79de4bed98](https://linux-hardware.org/?probe=79de4bed98) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eda1870d76](https://linux-hardware.org/?probe=eda1870d76) | May 31, 2023 |
| Gigabyte      | X99-UD7 WIFI-CF             | Desktop     | [955e65b76f](https://linux-hardware.org/?probe=955e65b76f) | May 31, 2023 |
| Timi          | RedmiBook 14 II             | Notebook    | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [5271bd0b88](https://linux-hardware.org/?probe=5271bd0b88) | May 30, 2023 |
| MSI           | Katana GF76 12UD            | Notebook    | [b1b1816b59](https://linux-hardware.org/?probe=b1b1816b59) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | Notebook    | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [2f1017a58e](https://linux-hardware.org/?probe=2f1017a58e) | May 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [32fee60a54](https://linux-hardware.org/?probe=32fee60a54) | May 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ec91d28c95](https://linux-hardware.org/?probe=ec91d28c95) | May 28, 2023 |
| HP            | Compaq 6730s                | Notebook    | [fe2b8b63ac](https://linux-hardware.org/?probe=fe2b8b63ac) | May 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [f4411b6232](https://linux-hardware.org/?probe=f4411b6232) | May 27, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [07ecf79e17](https://linux-hardware.org/?probe=07ecf79e17) | May 26, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c4af5a7969](https://linux-hardware.org/?probe=c4af5a7969) | May 26, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [aa99fb811d](https://linux-hardware.org/?probe=aa99fb811d) | May 26, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [dbfc9be02f](https://linux-hardware.org/?probe=dbfc9be02f) | May 26, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25f6dcaefc](https://linux-hardware.org/?probe=25f6dcaefc) | May 25, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [486d6ac497](https://linux-hardware.org/?probe=486d6ac497) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| congatec      | conga-TA7 A.4               | Mini pc     | [686699557a](https://linux-hardware.org/?probe=686699557a) | May 24, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f2477906c7](https://linux-hardware.org/?probe=f2477906c7) | May 23, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [266235dc3b](https://linux-hardware.org/?probe=266235dc3b) | May 23, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [73d0ff64b6](https://linux-hardware.org/?probe=73d0ff64b6) | May 23, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [0cba90ce8e](https://linux-hardware.org/?probe=0cba90ce8e) | May 23, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [df04cb5fb1](https://linux-hardware.org/?probe=df04cb5fb1) | May 22, 2023 |
| Lenovo        | ThinkPad T550 20CJS1V900    | Notebook    | [9bc275ef54](https://linux-hardware.org/?probe=9bc275ef54) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [117bc29848](https://linux-hardware.org/?probe=117bc29848) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [e3af81180a](https://linux-hardware.org/?probe=e3af81180a) | May 22, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [11c329d15a](https://linux-hardware.org/?probe=11c329d15a) | May 22, 2023 |
| MSI           | Z87-G43                     | Desktop     | [2fa7c1d81d](https://linux-hardware.org/?probe=2fa7c1d81d) | May 21, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [b3564ca1cf](https://linux-hardware.org/?probe=b3564ca1cf) | May 20, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [cce6eaa028](https://linux-hardware.org/?probe=cce6eaa028) | May 20, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [15d9163f08](https://linux-hardware.org/?probe=15d9163f08) | May 20, 2023 |
| HP            | Compaq 6730s                | Notebook    | [632961079b](https://linux-hardware.org/?probe=632961079b) | May 20, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | Desktop     | [693c7b6d9b](https://linux-hardware.org/?probe=693c7b6d9b) | May 18, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [7a2e636353](https://linux-hardware.org/?probe=7a2e636353) | May 18, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [ca0ae58640](https://linux-hardware.org/?probe=ca0ae58640) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | Notebook    | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| Acer          | Revo 70                     | Desktop     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [0829603c60](https://linux-hardware.org/?probe=0829603c60) | May 17, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [7d818512b8](https://linux-hardware.org/?probe=7d818512b8) | May 17, 2023 |
| Packard Be... | EasyNote TV43CM             | Notebook    | [66dbc844c7](https://linux-hardware.org/?probe=66dbc844c7) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [8c10a0ad96](https://linux-hardware.org/?probe=8c10a0ad96) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [be5ad76a6e](https://linux-hardware.org/?probe=be5ad76a6e) | May 16, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7d44c65f86](https://linux-hardware.org/?probe=7d44c65f86) | May 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [36df0e0f57](https://linux-hardware.org/?probe=36df0e0f57) | May 14, 2023 |
| MSI           | H110I PRO                   | Desktop     | [1224d45c07](https://linux-hardware.org/?probe=1224d45c07) | May 14, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [df19e8413c](https://linux-hardware.org/?probe=df19e8413c) | May 14, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [beb403e4e0](https://linux-hardware.org/?probe=beb403e4e0) | May 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [5ab21854e6](https://linux-hardware.org/?probe=5ab21854e6) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [c5c05f7e4c](https://linux-hardware.org/?probe=c5c05f7e4c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | Notebook    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [d835755922](https://linux-hardware.org/?probe=d835755922) | May 12, 2023 |
| HP            | ProBook 6470b               | Notebook    | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | Notebook    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [cbc84d049a](https://linux-hardware.org/?probe=cbc84d049a) | May 12, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [c458dad4b3](https://linux-hardware.org/?probe=c458dad4b3) | May 12, 2023 |
| ASUSTek       | Rampage IV FORMULA          | Desktop     | [b44dd1286b](https://linux-hardware.org/?probe=b44dd1286b) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [c51d42778d](https://linux-hardware.org/?probe=c51d42778d) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [e65b0be462](https://linux-hardware.org/?probe=e65b0be462) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [e661dd9daf](https://linux-hardware.org/?probe=e661dd9daf) | May 11, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [721f9583d7](https://linux-hardware.org/?probe=721f9583d7) | May 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [bd7c97ad54](https://linux-hardware.org/?probe=bd7c97ad54) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9cbcc36a48](https://linux-hardware.org/?probe=9cbcc36a48) | May 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [483f4bbb5d](https://linux-hardware.org/?probe=483f4bbb5d) | May 10, 2023 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [535cc48341](https://linux-hardware.org/?probe=535cc48341) | May 08, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4c3e0a0ac6](https://linux-hardware.org/?probe=4c3e0a0ac6) | May 08, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [08df3c35ee](https://linux-hardware.org/?probe=08df3c35ee) | May 08, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [3ac194e77a](https://linux-hardware.org/?probe=3ac194e77a) | May 07, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [1c84c61678](https://linux-hardware.org/?probe=1c84c61678) | May 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [893f259653](https://linux-hardware.org/?probe=893f259653) | May 07, 2023 |
| MSI           | MS-B120                     | Mini pc     | [836697d300](https://linux-hardware.org/?probe=836697d300) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c88845ae9b](https://linux-hardware.org/?probe=c88845ae9b) | May 06, 2023 |
| Dell          | Vostro 3360                 | Notebook    | [13a1e30b53](https://linux-hardware.org/?probe=13a1e30b53) | May 06, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [14c71828ca](https://linux-hardware.org/?probe=14c71828ca) | May 05, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [3f515702d2](https://linux-hardware.org/?probe=3f515702d2) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| Dell          | 02N3WF A02                  | Desktop     | [3f10b3ca43](https://linux-hardware.org/?probe=3f10b3ca43) | May 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [0b217b3ccc](https://linux-hardware.org/?probe=0b217b3ccc) | May 04, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [2f6fd9e5b0](https://linux-hardware.org/?probe=2f6fd9e5b0) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6cbfaabd66](https://linux-hardware.org/?probe=6cbfaabd66) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [4762d9bb4e](https://linux-hardware.org/?probe=4762d9bb4e) | May 03, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | Notebook    | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e8721751c6](https://linux-hardware.org/?probe=e8721751c6) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e426e8e40b](https://linux-hardware.org/?probe=e426e8e40b) | May 03, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [973f9c6467](https://linux-hardware.org/?probe=973f9c6467) | May 01, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [92f7217eb7](https://linux-hardware.org/?probe=92f7217eb7) | May 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [22cf2ddf02](https://linux-hardware.org/?probe=22cf2ddf02) | May 01, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [56db7fc27f](https://linux-hardware.org/?probe=56db7fc27f) | May 01, 2023 |
| Shuttle       | FS35V4                      | Desktop     | [137fda9bc6](https://linux-hardware.org/?probe=137fda9bc6) | May 01, 2023 |
| MSI           | MS-B120                     | Mini pc     | [8019bfa6d4](https://linux-hardware.org/?probe=8019bfa6d4) | Apr 30, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4f10159e93](https://linux-hardware.org/?probe=4f10159e93) | Apr 30, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [4b47a4606b](https://linux-hardware.org/?probe=4b47a4606b) | Apr 29, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d97d6d6dff](https://linux-hardware.org/?probe=d97d6d6dff) | Apr 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [1a73639c02](https://linux-hardware.org/?probe=1a73639c02) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [a6eba14ab4](https://linux-hardware.org/?probe=a6eba14ab4) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6f56840307](https://linux-hardware.org/?probe=6f56840307) | Apr 28, 2023 |
| Dell          | Latitude 5430               | Notebook    | [644e44f95a](https://linux-hardware.org/?probe=644e44f95a) | Apr 28, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [c53a69bd72](https://linux-hardware.org/?probe=c53a69bd72) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [07572e6599](https://linux-hardware.org/?probe=07572e6599) | Apr 27, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ff439c208a](https://linux-hardware.org/?probe=ff439c208a) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [69f1753783](https://linux-hardware.org/?probe=69f1753783) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [067bc49888](https://linux-hardware.org/?probe=067bc49888) | Apr 26, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [c6a1179816](https://linux-hardware.org/?probe=c6a1179816) | Apr 25, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [4fcb9881b2](https://linux-hardware.org/?probe=4fcb9881b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [21c872ac1c](https://linux-hardware.org/?probe=21c872ac1c) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [99e0054492](https://linux-hardware.org/?probe=99e0054492) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [86b56d3e69](https://linux-hardware.org/?probe=86b56d3e69) | Apr 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [adab9d9f6b](https://linux-hardware.org/?probe=adab9d9f6b) | Apr 22, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [17c955a974](https://linux-hardware.org/?probe=17c955a974) | Apr 21, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [cb9c80dbba](https://linux-hardware.org/?probe=cb9c80dbba) | Apr 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [68d07ba405](https://linux-hardware.org/?probe=68d07ba405) | Apr 20, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [3f12350d47](https://linux-hardware.org/?probe=3f12350d47) | Apr 20, 2023 |
| Dell          | Latitude 7490               | Notebook    | [57a719ce62](https://linux-hardware.org/?probe=57a719ce62) | Apr 20, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [69c613b55f](https://linux-hardware.org/?probe=69c613b55f) | Apr 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [83c6b6137d](https://linux-hardware.org/?probe=83c6b6137d) | Apr 20, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [b45a30f071](https://linux-hardware.org/?probe=b45a30f071) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6SV0... | Notebook    | [8f05b53b93](https://linux-hardware.org/?probe=8f05b53b93) | Apr 17, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [4278a9f497](https://linux-hardware.org/?probe=4278a9f497) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | Notebook    | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [39106da598](https://linux-hardware.org/?probe=39106da598) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a9f8183365](https://linux-hardware.org/?probe=a9f8183365) | Apr 16, 2023 |
| Unknown       | Unknown                     | Phone       | [3d8d71ba51](https://linux-hardware.org/?probe=3d8d71ba51) | Apr 16, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [a51c500b65](https://linux-hardware.org/?probe=a51c500b65) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [b259f47200](https://linux-hardware.org/?probe=b259f47200) | Apr 15, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [40894d0141](https://linux-hardware.org/?probe=40894d0141) | Apr 14, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [d2c04327fb](https://linux-hardware.org/?probe=d2c04327fb) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [b7786541c0](https://linux-hardware.org/?probe=b7786541c0) | Apr 13, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [ec6dc0883b](https://linux-hardware.org/?probe=ec6dc0883b) | Apr 13, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [66924704d2](https://linux-hardware.org/?probe=66924704d2) | Apr 12, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [87d43c1f1d](https://linux-hardware.org/?probe=87d43c1f1d) | Apr 12, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a291f82fe3](https://linux-hardware.org/?probe=a291f82fe3) | Apr 12, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [810aed46d0](https://linux-hardware.org/?probe=810aed46d0) | Apr 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5db9e8f875](https://linux-hardware.org/?probe=5db9e8f875) | Apr 11, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [7ddf3af042](https://linux-hardware.org/?probe=7ddf3af042) | Apr 11, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [e3eee10ad1](https://linux-hardware.org/?probe=e3eee10ad1) | Apr 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [d5fb19d97c](https://linux-hardware.org/?probe=d5fb19d97c) | Apr 08, 2023 |
| HP            | ProBook 4530s               | Notebook    | [efd084d9d5](https://linux-hardware.org/?probe=efd084d9d5) | Apr 07, 2023 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [0ddbf6cc2e](https://linux-hardware.org/?probe=0ddbf6cc2e) | Apr 07, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [a0c75732ae](https://linux-hardware.org/?probe=a0c75732ae) | Apr 06, 2023 |
| LG Electro... | Kabylake Platform           | Notebook    | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [0f4a907d19](https://linux-hardware.org/?probe=0f4a907d19) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [d337edfd9a](https://linux-hardware.org/?probe=d337edfd9a) | Apr 05, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6ddafae4d0](https://linux-hardware.org/?probe=6ddafae4d0) | Apr 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [01f2e4a69f](https://linux-hardware.org/?probe=01f2e4a69f) | Apr 05, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [f49ec499ed](https://linux-hardware.org/?probe=f49ec499ed) | Apr 04, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [68322a0698](https://linux-hardware.org/?probe=68322a0698) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [53fc9d8c25](https://linux-hardware.org/?probe=53fc9d8c25) | Apr 04, 2023 |
| Dell          | Precision 5530              | Notebook    | [bf568860cb](https://linux-hardware.org/?probe=bf568860cb) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [550f1d522d](https://linux-hardware.org/?probe=550f1d522d) | Apr 04, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [56a619b537](https://linux-hardware.org/?probe=56a619b537) | Apr 04, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [08074927ff](https://linux-hardware.org/?probe=08074927ff) | Apr 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d57f6cb4c6](https://linux-hardware.org/?probe=d57f6cb4c6) | Apr 03, 2023 |
| Intel         | NUC12WSBi5 M63398-302       | Mini pc     | [785a41f4e9](https://linux-hardware.org/?probe=785a41f4e9) | Apr 02, 2023 |
| Acer          | Predator G3-605             | Desktop     | [f7ca1573d0](https://linux-hardware.org/?probe=f7ca1573d0) | Apr 02, 2023 |
| Acer          | Predator G3-605             | Desktop     | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [06275c19f3](https://linux-hardware.org/?probe=06275c19f3) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [36e57fb4cf](https://linux-hardware.org/?probe=36e57fb4cf) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a89c429c84](https://linux-hardware.org/?probe=a89c429c84) | Mar 31, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| HP            | 82B4                        | Desktop     | [9712d04ab5](https://linux-hardware.org/?probe=9712d04ab5) | Mar 30, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [f897573506](https://linux-hardware.org/?probe=f897573506) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [50affe59d1](https://linux-hardware.org/?probe=50affe59d1) | Mar 28, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b74b7f7d31](https://linux-hardware.org/?probe=b74b7f7d31) | Mar 28, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [f0e6089a6e](https://linux-hardware.org/?probe=f0e6089a6e) | Mar 28, 2023 |
| Acer          | Nitro N50-640               | Desktop     | [2219ec0fad](https://linux-hardware.org/?probe=2219ec0fad) | Mar 27, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [011d1b8bf7](https://linux-hardware.org/?probe=011d1b8bf7) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [c5a3b374a7](https://linux-hardware.org/?probe=c5a3b374a7) | Mar 27, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [8a1c592e98](https://linux-hardware.org/?probe=8a1c592e98) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [f403538019](https://linux-hardware.org/?probe=f403538019) | Mar 26, 2023 |
| HP            | 1998                        | Desktop     | [346f37956b](https://linux-hardware.org/?probe=346f37956b) | Mar 26, 2023 |
| Gigabyte      | AORUS 15G KC                | Notebook    | [d87e89d84f](https://linux-hardware.org/?probe=d87e89d84f) | Mar 26, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [6f9300474f](https://linux-hardware.org/?probe=6f9300474f) | Mar 26, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [d1baffa910](https://linux-hardware.org/?probe=d1baffa910) | Mar 25, 2023 |
| HP            | 2B05                        | Desktop     | [b34e6d230c](https://linux-hardware.org/?probe=b34e6d230c) | Mar 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b2cdf1deb7](https://linux-hardware.org/?probe=b2cdf1deb7) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [1e549ae67e](https://linux-hardware.org/?probe=1e549ae67e) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [09fec047e4](https://linux-hardware.org/?probe=09fec047e4) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bf24fe6112](https://linux-hardware.org/?probe=bf24fe6112) | Mar 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [883d4de906](https://linux-hardware.org/?probe=883d4de906) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [b4c65fead7](https://linux-hardware.org/?probe=b4c65fead7) | Mar 21, 2023 |
| Shuttle       | SH570                       | Desktop     | [3ef2bf52b7](https://linux-hardware.org/?probe=3ef2bf52b7) | Mar 21, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [240444cad9](https://linux-hardware.org/?probe=240444cad9) | Mar 21, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [a9a586ef2d](https://linux-hardware.org/?probe=a9a586ef2d) | Mar 20, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [51e5415bb0](https://linux-hardware.org/?probe=51e5415bb0) | Mar 19, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [c88d5f831a](https://linux-hardware.org/?probe=c88d5f831a) | Mar 19, 2023 |
| Intel         | NUC5CPYB H61145-412         | Mini pc     | [a87d0fe300](https://linux-hardware.org/?probe=a87d0fe300) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bd119c8898](https://linux-hardware.org/?probe=bd119c8898) | Mar 17, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [87ba801b00](https://linux-hardware.org/?probe=87ba801b00) | Mar 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d95b09eda0](https://linux-hardware.org/?probe=d95b09eda0) | Mar 17, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [dfb8518fa9](https://linux-hardware.org/?probe=dfb8518fa9) | Mar 16, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [bb4f0202b7](https://linux-hardware.org/?probe=bb4f0202b7) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Google        | Rabbid                      | Notebook    | [621762ceec](https://linux-hardware.org/?probe=621762ceec) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | Notebook    | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [016f5cd3be](https://linux-hardware.org/?probe=016f5cd3be) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | Desktop     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [070c7d809a](https://linux-hardware.org/?probe=070c7d809a) | Mar 13, 2023 |
| GPD           | P2 MAX                      | Notebook    | [dd958bf28e](https://linux-hardware.org/?probe=dd958bf28e) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [12120178de](https://linux-hardware.org/?probe=12120178de) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| HP            | 1825                        | Desktop     | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [1169593829](https://linux-hardware.org/?probe=1169593829) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [76e4cc71f5](https://linux-hardware.org/?probe=76e4cc71f5) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [75fc2c0a15](https://linux-hardware.org/?probe=75fc2c0a15) | Mar 12, 2023 |
| HP            | 1998                        | Desktop     | [68d7c4350d](https://linux-hardware.org/?probe=68d7c4350d) | Mar 12, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c22a046fc6](https://linux-hardware.org/?probe=c22a046fc6) | Mar 11, 2023 |
| SiYW          | V200 Series                 | Desktop     | [7c3751c888](https://linux-hardware.org/?probe=7c3751c888) | Mar 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [0555c85a89](https://linux-hardware.org/?probe=0555c85a89) | Mar 11, 2023 |
| HP            | 18E5                        | Desktop     | [82e5831486](https://linux-hardware.org/?probe=82e5831486) | Mar 10, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [03f44a913e](https://linux-hardware.org/?probe=03f44a913e) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4d15122995](https://linux-hardware.org/?probe=4d15122995) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc6e719e99](https://linux-hardware.org/?probe=cc6e719e99) | Mar 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d1768ecbaa](https://linux-hardware.org/?probe=d1768ecbaa) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [081ecd2050](https://linux-hardware.org/?probe=081ecd2050) | Mar 07, 2023 |
| HP            | Presario CQ57               | Notebook    | [33b1812664](https://linux-hardware.org/?probe=33b1812664) | Mar 06, 2023 |
| HP            | Presario CQ57               | Notebook    | [26ec55c2cb](https://linux-hardware.org/?probe=26ec55c2cb) | Mar 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0d202dc031](https://linux-hardware.org/?probe=0d202dc031) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8814af9b71](https://linux-hardware.org/?probe=8814af9b71) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [deb075440f](https://linux-hardware.org/?probe=deb075440f) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [f21bd9cc58](https://linux-hardware.org/?probe=f21bd9cc58) | Mar 05, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [19bd4c1e4e](https://linux-hardware.org/?probe=19bd4c1e4e) | Mar 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f9a2075d54](https://linux-hardware.org/?probe=f9a2075d54) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Dell          | Precision 3551              | Notebook    | [7c1bc8355a](https://linux-hardware.org/?probe=7c1bc8355a) | Mar 03, 2023 |
| Clevo         | W25xHNx                     | Notebook    | [5227127f81](https://linux-hardware.org/?probe=5227127f81) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [f3defb812b](https://linux-hardware.org/?probe=f3defb812b) | Mar 03, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [41d9c3d9ed](https://linux-hardware.org/?probe=41d9c3d9ed) | Mar 02, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a279108842](https://linux-hardware.org/?probe=a279108842) | Mar 02, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | Desktop     | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [3cd0e65d1f](https://linux-hardware.org/?probe=3cd0e65d1f) | Feb 27, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [2fe31a709a](https://linux-hardware.org/?probe=2fe31a709a) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [5ef01d46d4](https://linux-hardware.org/?probe=5ef01d46d4) | Feb 25, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0AE0... | Notebook    | [7f8c9de1aa](https://linux-hardware.org/?probe=7f8c9de1aa) | Feb 24, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [fc86b476d7](https://linux-hardware.org/?probe=fc86b476d7) | Feb 22, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [de328ac1ad](https://linux-hardware.org/?probe=de328ac1ad) | Feb 22, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [da461191e8](https://linux-hardware.org/?probe=da461191e8) | Feb 21, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [54b9c4c95c](https://linux-hardware.org/?probe=54b9c4c95c) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ecc97fee86](https://linux-hardware.org/?probe=ecc97fee86) | Feb 21, 2023 |
| Dell          | Precision M4800             | Notebook    | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| ASUSTek       | G501VW                      | Notebook    | [6e014311b2](https://linux-hardware.org/?probe=6e014311b2) | Feb 20, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [5aa73f71fd](https://linux-hardware.org/?probe=5aa73f71fd) | Feb 20, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [7427fa6886](https://linux-hardware.org/?probe=7427fa6886) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [2b56edae65](https://linux-hardware.org/?probe=2b56edae65) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [dde311dcb2](https://linux-hardware.org/?probe=dde311dcb2) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [96b350db9f](https://linux-hardware.org/?probe=96b350db9f) | Feb 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f594570a77](https://linux-hardware.org/?probe=f594570a77) | Feb 16, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [8e521a2efc](https://linux-hardware.org/?probe=8e521a2efc) | Feb 16, 2023 |
| GPD           | P2 MAX                      | Notebook    | [9a623b2196](https://linux-hardware.org/?probe=9a623b2196) | Feb 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [eac9c046ac](https://linux-hardware.org/?probe=eac9c046ac) | Feb 15, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [3717c2476f](https://linux-hardware.org/?probe=3717c2476f) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4e3ff30332](https://linux-hardware.org/?probe=4e3ff30332) | Feb 15, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [eb40144624](https://linux-hardware.org/?probe=eb40144624) | Feb 13, 2023 |
| HP            | 8455                        | Desktop     | [f75db6c5d5](https://linux-hardware.org/?probe=f75db6c5d5) | Feb 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [3a18e2226c](https://linux-hardware.org/?probe=3a18e2226c) | Feb 12, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [004535fd1c](https://linux-hardware.org/?probe=004535fd1c) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c1ac37fee3](https://linux-hardware.org/?probe=c1ac37fee3) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| MSI           | MS-B120                     | Mini pc     | [1d365cbddd](https://linux-hardware.org/?probe=1d365cbddd) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [a60a4191b8](https://linux-hardware.org/?probe=a60a4191b8) | Feb 10, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| AZW           | GTR V01                     | Mini pc     | [2898aebf10](https://linux-hardware.org/?probe=2898aebf10) | Feb 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| Dell          | Latitude E7250              | Notebook    | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [3797cf0990](https://linux-hardware.org/?probe=3797cf0990) | Feb 07, 2023 |
| ASUSTek       | EB1501P                     | Desktop     | [687e52dcb1](https://linux-hardware.org/?probe=687e52dcb1) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [e553ba2549](https://linux-hardware.org/?probe=e553ba2549) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [d888ff5291](https://linux-hardware.org/?probe=d888ff5291) | Feb 06, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [0c6df9267b](https://linux-hardware.org/?probe=0c6df9267b) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [452216b5ed](https://linux-hardware.org/?probe=452216b5ed) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | Notebook    | [bbe182e4c2](https://linux-hardware.org/?probe=bbe182e4c2) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [f265a0e81e](https://linux-hardware.org/?probe=f265a0e81e) | Feb 04, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [9e2380e15d](https://linux-hardware.org/?probe=9e2380e15d) | Feb 03, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [fac45201b3](https://linux-hardware.org/?probe=fac45201b3) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [1752779e0c](https://linux-hardware.org/?probe=1752779e0c) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [ef707954b8](https://linux-hardware.org/?probe=ef707954b8) | Feb 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [6e089e22b1](https://linux-hardware.org/?probe=6e089e22b1) | Feb 01, 2023 |
| Dell          | Latitude 7420               | Notebook    | [f0b8816283](https://linux-hardware.org/?probe=f0b8816283) | Feb 01, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [f1a9c37047](https://linux-hardware.org/?probe=f1a9c37047) | Jan 31, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [fe2a413caa](https://linux-hardware.org/?probe=fe2a413caa) | Jan 31, 2023 |
| Dell          | Latitude 7420               | Notebook    | [55f81648a1](https://linux-hardware.org/?probe=55f81648a1) | Jan 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| Dell          | Latitude D630C              | Notebook    | [401357bc99](https://linux-hardware.org/?probe=401357bc99) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | Notebook    | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [f01366b131](https://linux-hardware.org/?probe=f01366b131) | Jan 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [54ba66711b](https://linux-hardware.org/?probe=54ba66711b) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [756bf12bd7](https://linux-hardware.org/?probe=756bf12bd7) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [c4a13a66ed](https://linux-hardware.org/?probe=c4a13a66ed) | Jan 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [cb00a3e89d](https://linux-hardware.org/?probe=cb00a3e89d) | Jan 24, 2023 |
| Google        | Link                        | Notebook    | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [1a9bed0cf3](https://linux-hardware.org/?probe=1a9bed0cf3) | Jan 23, 2023 |
| Dell          | 0Y56T3 A00                  | Desktop     | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| AZW           | GTR V01                     | Mini pc     | [1d4c2002d5](https://linux-hardware.org/?probe=1d4c2002d5) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| AMI           | Intel                       | Notebook    | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fa1f3d8e3b](https://linux-hardware.org/?probe=fa1f3d8e3b) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [1d10977303](https://linux-hardware.org/?probe=1d10977303) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [fdbbb4a832](https://linux-hardware.org/?probe=fdbbb4a832) | Jan 21, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [80e51b3319](https://linux-hardware.org/?probe=80e51b3319) | Jan 20, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [d7e7799006](https://linux-hardware.org/?probe=d7e7799006) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [e221c08388](https://linux-hardware.org/?probe=e221c08388) | Jan 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [d2bb65ed09](https://linux-hardware.org/?probe=d2bb65ed09) | Jan 18, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6d6698b316](https://linux-hardware.org/?probe=6d6698b316) | Jan 18, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [8bfae8a964](https://linux-hardware.org/?probe=8bfae8a964) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0e57f4ecbe](https://linux-hardware.org/?probe=0e57f4ecbe) | Jan 15, 2023 |
| Star Labs     | StarBook                    | Notebook    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [5b26575c52](https://linux-hardware.org/?probe=5b26575c52) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [0533348a3f](https://linux-hardware.org/?probe=0533348a3f) | Jan 14, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [b0308f4270](https://linux-hardware.org/?probe=b0308f4270) | Jan 13, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [bb85f0bdc7](https://linux-hardware.org/?probe=bb85f0bdc7) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [262fe40796](https://linux-hardware.org/?probe=262fe40796) | Jan 12, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [18bdf2650e](https://linux-hardware.org/?probe=18bdf2650e) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | Desktop     | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| Dell          | Studio 1749                 | Notebook    | [28a19b2c03](https://linux-hardware.org/?probe=28a19b2c03) | Jan 11, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [7697ff8cb4](https://linux-hardware.org/?probe=7697ff8cb4) | Jan 11, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [994306b125](https://linux-hardware.org/?probe=994306b125) | Jan 11, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [72bf3e7a8b](https://linux-hardware.org/?probe=72bf3e7a8b) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [aacfe1b351](https://linux-hardware.org/?probe=aacfe1b351) | Jan 11, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [5cfaf7d715](https://linux-hardware.org/?probe=5cfaf7d715) | Jan 10, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [59155b3092](https://linux-hardware.org/?probe=59155b3092) | Jan 10, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [ac85316fc2](https://linux-hardware.org/?probe=ac85316fc2) | Jan 09, 2023 |
| MSI           | GP60 2PE                    | Notebook    | [e1506ca6f6](https://linux-hardware.org/?probe=e1506ca6f6) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [980ee9f42c](https://linux-hardware.org/?probe=980ee9f42c) | Jan 07, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [e64152748d](https://linux-hardware.org/?probe=e64152748d) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Samsung       | R530/R730                   | Notebook    | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Precision M90               | Notebook    | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a24229bc3b](https://linux-hardware.org/?probe=a24229bc3b) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2849ffe456](https://linux-hardware.org/?probe=2849ffe456) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [77cc17c28c](https://linux-hardware.org/?probe=77cc17c28c) | Jan 02, 2023 |
| Foxconn       | 2AAF                        | Desktop     | [813a45dc50](https://linux-hardware.org/?probe=813a45dc50) | Jan 01, 2023 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [de65990b87](https://linux-hardware.org/?probe=de65990b87) | Jan 01, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [273f6722e0](https://linux-hardware.org/?probe=273f6722e0) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [34cd286c5f](https://linux-hardware.org/?probe=34cd286c5f) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [15c60654b3](https://linux-hardware.org/?probe=15c60654b3) | Dec 30, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [87d0f67d84](https://linux-hardware.org/?probe=87d0f67d84) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [b89e7eb1c9](https://linux-hardware.org/?probe=b89e7eb1c9) | Dec 28, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [f37619077b](https://linux-hardware.org/?probe=f37619077b) | Dec 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e979df032a](https://linux-hardware.org/?probe=e979df032a) | Dec 26, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [82a5aa7ead](https://linux-hardware.org/?probe=82a5aa7ead) | Dec 26, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| GMKtec        | NucBox8                     | Server      | [abc999a1a4](https://linux-hardware.org/?probe=abc999a1a4) | Dec 24, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| Dell          | Latitude 3380               | Notebook    | [e4847d5b1f](https://linux-hardware.org/?probe=e4847d5b1f) | Dec 24, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [92f12e3ec7](https://linux-hardware.org/?probe=92f12e3ec7) | Dec 24, 2022 |
| GMKtec        | NucBox8                     | Server      | [66b0fbce86](https://linux-hardware.org/?probe=66b0fbce86) | Dec 24, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [3237ff6784](https://linux-hardware.org/?probe=3237ff6784) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [ba82bee4c7](https://linux-hardware.org/?probe=ba82bee4c7) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [a2a2f20ef4](https://linux-hardware.org/?probe=a2a2f20ef4) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92515d8a95](https://linux-hardware.org/?probe=92515d8a95) | Dec 21, 2022 |
| Schenker      | XMG APEX 15 MAX (E22)       | Notebook    | [6b46538fea](https://linux-hardware.org/?probe=6b46538fea) | Dec 21, 2022 |
| Dell          | 0020HJ A01                  | Server      | [e266254c60](https://linux-hardware.org/?probe=e266254c60) | Dec 21, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [5477e8f714](https://linux-hardware.org/?probe=5477e8f714) | Dec 21, 2022 |
| Dell          | Latitude 3380               | Notebook    | [808c693271](https://linux-hardware.org/?probe=808c693271) | Dec 20, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [8a09a51987](https://linux-hardware.org/?probe=8a09a51987) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4fbc0ddbd5](https://linux-hardware.org/?probe=4fbc0ddbd5) | Dec 20, 2022 |
| HP            | 18E7                        | Desktop     | [31011a35a4](https://linux-hardware.org/?probe=31011a35a4) | Dec 17, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [3b48a01ef2](https://linux-hardware.org/?probe=3b48a01ef2) | Dec 16, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ffa7e28596](https://linux-hardware.org/?probe=ffa7e28596) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [bc3635620b](https://linux-hardware.org/?probe=bc3635620b) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [888e6092a6](https://linux-hardware.org/?probe=888e6092a6) | Dec 15, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [5248ee7dbe](https://linux-hardware.org/?probe=5248ee7dbe) | Dec 15, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [3403282c8c](https://linux-hardware.org/?probe=3403282c8c) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | Desktop     | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a0d408fecd](https://linux-hardware.org/?probe=a0d408fecd) | Dec 15, 2022 |
| Dell          | Latitude E7240              | Notebook    | [c47fc4fadf](https://linux-hardware.org/?probe=c47fc4fadf) | Dec 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6b47a036ab](https://linux-hardware.org/?probe=6b47a036ab) | Dec 14, 2022 |
| Insyde        | G0975                       | Notebook    | [1f4823542d](https://linux-hardware.org/?probe=1f4823542d) | Dec 14, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [39a9464c10](https://linux-hardware.org/?probe=39a9464c10) | Dec 14, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5a9654c743](https://linux-hardware.org/?probe=5a9654c743) | Dec 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [05ffc0ef7a](https://linux-hardware.org/?probe=05ffc0ef7a) | Dec 13, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [502792fe8a](https://linux-hardware.org/?probe=502792fe8a) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [7b8b3c2a86](https://linux-hardware.org/?probe=7b8b3c2a86) | Dec 12, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [65c6c18ffe](https://linux-hardware.org/?probe=65c6c18ffe) | Dec 12, 2022 |
| Dell          | Latitude 5430               | Notebook    | [b439d1e1a4](https://linux-hardware.org/?probe=b439d1e1a4) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| Google        | Orco                        | Notebook    | [40acd3207e](https://linux-hardware.org/?probe=40acd3207e) | Dec 10, 2022 |
| Google        | Orco                        | Notebook    | [9c369b40b3](https://linux-hardware.org/?probe=9c369b40b3) | Dec 10, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3a91c2e245](https://linux-hardware.org/?probe=3a91c2e245) | Dec 07, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | Notebook    | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [310ff494e7](https://linux-hardware.org/?probe=310ff494e7) | Dec 06, 2022 |
| HP            | 18E5                        | Desktop     | [9158a7ab6b](https://linux-hardware.org/?probe=9158a7ab6b) | Dec 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | Notebook    | [d01d1e9652](https://linux-hardware.org/?probe=d01d1e9652) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [ff90421b87](https://linux-hardware.org/?probe=ff90421b87) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [3bc6ea9cfa](https://linux-hardware.org/?probe=3bc6ea9cfa) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [aaed16d626](https://linux-hardware.org/?probe=aaed16d626) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [cd63efdbd4](https://linux-hardware.org/?probe=cd63efdbd4) | Dec 05, 2022 |
| SiYW          | V200 Series                 | Desktop     | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| Sony          | VPCEB1M1E                   | Notebook    | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [d8d5459ad6](https://linux-hardware.org/?probe=d8d5459ad6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [1dddd99280](https://linux-hardware.org/?probe=1dddd99280) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F10034MX    | Notebook    | [34842eb8d9](https://linux-hardware.org/?probe=34842eb8d9) | Dec 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | Notebook    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [258c074e40](https://linux-hardware.org/?probe=258c074e40) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [29ec19d38e](https://linux-hardware.org/?probe=29ec19d38e) | Nov 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [997ffc40f0](https://linux-hardware.org/?probe=997ffc40f0) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [efacbf6215](https://linux-hardware.org/?probe=efacbf6215) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [85ac938c0c](https://linux-hardware.org/?probe=85ac938c0c) | Nov 29, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [96b383097b](https://linux-hardware.org/?probe=96b383097b) | Nov 29, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | Notebook    | [97fda88c7b](https://linux-hardware.org/?probe=97fda88c7b) | Nov 28, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8f8f53c15b](https://linux-hardware.org/?probe=8f8f53c15b) | Nov 27, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ac8f0475f1](https://linux-hardware.org/?probe=ac8f0475f1) | Nov 27, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [669f6eaf1c](https://linux-hardware.org/?probe=669f6eaf1c) | Nov 26, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [b59180988d](https://linux-hardware.org/?probe=b59180988d) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | Notebook    | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [7121172cc6](https://linux-hardware.org/?probe=7121172cc6) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [c150f785ea](https://linux-hardware.org/?probe=c150f785ea) | Nov 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [52b55ea024](https://linux-hardware.org/?probe=52b55ea024) | Nov 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7ea2296eaf](https://linux-hardware.org/?probe=7ea2296eaf) | Nov 21, 2022 |
| AZW           | GTR V01                     | Mini pc     | [2042d4c2c0](https://linux-hardware.org/?probe=2042d4c2c0) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4f36ecd91b](https://linux-hardware.org/?probe=4f36ecd91b) | Nov 19, 2022 |
| ASRock        | Z790 PG Riptide             | Desktop     | [c852740256](https://linux-hardware.org/?probe=c852740256) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f10fc36516](https://linux-hardware.org/?probe=f10fc36516) | Nov 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3534f07f4a](https://linux-hardware.org/?probe=3534f07f4a) | Nov 18, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [86a2f7caea](https://linux-hardware.org/?probe=86a2f7caea) | Nov 18, 2022 |
| Dell          | Latitude 5310               | Notebook    | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | Notebook    | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [4c5a2a2f55](https://linux-hardware.org/?probe=4c5a2a2f55) | Nov 16, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [e6600fae5a](https://linux-hardware.org/?probe=e6600fae5a) | Nov 16, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| ASUSTek       | 2A73h                       | Desktop     | [08e4620733](https://linux-hardware.org/?probe=08e4620733) | Nov 13, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0bc3c759d6](https://linux-hardware.org/?probe=0bc3c759d6) | Nov 13, 2022 |
| ASUSTek       | 2A73h                       | Desktop     | [557fb98d98](https://linux-hardware.org/?probe=557fb98d98) | Nov 13, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [091c048c2a](https://linux-hardware.org/?probe=091c048c2a) | Nov 12, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [8dee2ceeb0](https://linux-hardware.org/?probe=8dee2ceeb0) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6eedcdeb01](https://linux-hardware.org/?probe=6eedcdeb01) | Nov 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [48f127b453](https://linux-hardware.org/?probe=48f127b453) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [fd835d99e7](https://linux-hardware.org/?probe=fd835d99e7) | Nov 10, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [fae66184f2](https://linux-hardware.org/?probe=fae66184f2) | Nov 10, 2022 |
| ASUSTek       | U36SD                       | Notebook    | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [ed07b564ec](https://linux-hardware.org/?probe=ed07b564ec) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| HP            | 828A                        | Desktop     | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [92c837ff5a](https://linux-hardware.org/?probe=92c837ff5a) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [298819594a](https://linux-hardware.org/?probe=298819594a) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [2765ed4857](https://linux-hardware.org/?probe=2765ed4857) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [dd2877fcc2](https://linux-hardware.org/?probe=dd2877fcc2) | Nov 05, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [d95735860b](https://linux-hardware.org/?probe=d95735860b) | Nov 05, 2022 |
| Acer          | Predator G3610              | Desktop     | [783c053a62](https://linux-hardware.org/?probe=783c053a62) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ad1ae18c98](https://linux-hardware.org/?probe=ad1ae18c98) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [9d1ba43c71](https://linux-hardware.org/?probe=9d1ba43c71) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [dac055fa29](https://linux-hardware.org/?probe=dac055fa29) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [5c0a96cd5b](https://linux-hardware.org/?probe=5c0a96cd5b) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [95b5255056](https://linux-hardware.org/?probe=95b5255056) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [df00a6281b](https://linux-hardware.org/?probe=df00a6281b) | Nov 03, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [2ec155a4b6](https://linux-hardware.org/?probe=2ec155a4b6) | Nov 03, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [72467c5d61](https://linux-hardware.org/?probe=72467c5d61) | Oct 31, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d99707ef15](https://linux-hardware.org/?probe=d99707ef15) | Oct 29, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [063675c104](https://linux-hardware.org/?probe=063675c104) | Oct 29, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e51ca052ec](https://linux-hardware.org/?probe=e51ca052ec) | Oct 28, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [cd6e5e2095](https://linux-hardware.org/?probe=cd6e5e2095) | Oct 27, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [3c67c8efb7](https://linux-hardware.org/?probe=3c67c8efb7) | Oct 27, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [f95081e76e](https://linux-hardware.org/?probe=f95081e76e) | Oct 27, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [0fcfd33f95](https://linux-hardware.org/?probe=0fcfd33f95) | Oct 27, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [51cf8b4f9d](https://linux-hardware.org/?probe=51cf8b4f9d) | Oct 25, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | 2B05                        | Desktop     | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [302efb993a](https://linux-hardware.org/?probe=302efb993a) | Oct 22, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [8f3fdb4d9c](https://linux-hardware.org/?probe=8f3fdb4d9c) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [024fdc987b](https://linux-hardware.org/?probe=024fdc987b) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [6249475f24](https://linux-hardware.org/?probe=6249475f24) | Oct 20, 2022 |
| Fujitsu Si... | D2399 S26361-D2399          | Desktop     | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f3ac5bf3df](https://linux-hardware.org/?probe=f3ac5bf3df) | Oct 20, 2022 |
| HP            | 8056                        | Desktop     | [37ed8a6b64](https://linux-hardware.org/?probe=37ed8a6b64) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d727afe327](https://linux-hardware.org/?probe=d727afe327) | Oct 17, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [09a4ac981b](https://linux-hardware.org/?probe=09a4ac981b) | Oct 17, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [4138cb5064](https://linux-hardware.org/?probe=4138cb5064) | Oct 17, 2022 |
| HP            | 2AE2                        | Desktop     | [a1a8fcfe49](https://linux-hardware.org/?probe=a1a8fcfe49) | Oct 17, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [2438851671](https://linux-hardware.org/?probe=2438851671) | Oct 16, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [10a3014c1a](https://linux-hardware.org/?probe=10a3014c1a) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [8457aa21e7](https://linux-hardware.org/?probe=8457aa21e7) | Oct 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [4f52cb1040](https://linux-hardware.org/?probe=4f52cb1040) | Oct 15, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [689281cab0](https://linux-hardware.org/?probe=689281cab0) | Oct 15, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Acer          | Aspire 8950G                | Notebook    | [8888f23e03](https://linux-hardware.org/?probe=8888f23e03) | Oct 14, 2022 |
| Lenovo        | ThinkPad E595 20NF001HMX    | Notebook    | [1ae4e8967a](https://linux-hardware.org/?probe=1ae4e8967a) | Oct 14, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | Desktop     | [89060aa147](https://linux-hardware.org/?probe=89060aa147) | Oct 13, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [512238de46](https://linux-hardware.org/?probe=512238de46) | Oct 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [10ea852e71](https://linux-hardware.org/?probe=10ea852e71) | Oct 12, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [27b7798784](https://linux-hardware.org/?probe=27b7798784) | Oct 11, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [ef1a363500](https://linux-hardware.org/?probe=ef1a363500) | Oct 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c52e60caae](https://linux-hardware.org/?probe=c52e60caae) | Oct 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [92704e062f](https://linux-hardware.org/?probe=92704e062f) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [28d49251c7](https://linux-hardware.org/?probe=28d49251c7) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [16a6152e10](https://linux-hardware.org/?probe=16a6152e10) | Oct 02, 2022 |
| Dell          | Latitude E6320              | Notebook    | [69290cc372](https://linux-hardware.org/?probe=69290cc372) | Oct 02, 2022 |
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
| TUXEDO        | Unknown                     | Notebook    | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [a68d3f20eb](https://linux-hardware.org/?probe=a68d3f20eb) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Lenovo        | Yoga 13sACN 2021 82CY       | Notebook    | [d374a74e0d](https://linux-hardware.org/?probe=d374a74e0d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [5ed0ffde54](https://linux-hardware.org/?probe=5ed0ffde54) | Sep 22, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1bec04d42d](https://linux-hardware.org/?probe=1bec04d42d) | Sep 21, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b35ec1a833](https://linux-hardware.org/?probe=b35ec1a833) | Sep 21, 2022 |
| HP            | Pavilion g7                 | Notebook    | [a5f3f12174](https://linux-hardware.org/?probe=a5f3f12174) | Sep 20, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [af2eb79f4c](https://linux-hardware.org/?probe=af2eb79f4c) | Sep 20, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| HP            | 2B05                        | Desktop     | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4995ae034f](https://linux-hardware.org/?probe=4995ae034f) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4bf59d7938](https://linux-hardware.org/?probe=4bf59d7938) | Sep 19, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
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
| Ubuntu 20.04                 | 270       | 12.03%  |
| Ubuntu 22.04                 | 144       | 6.42%   |
| Ubuntu 18.04                 | 131       | 5.84%   |
| Arch Rolling                 | 61        | 2.72%   |
| Debian 11                    | 56        | 2.5%    |
| Pop!_OS 21.04                | 49        | 2.18%   |
| Manjaro                      | 46        | 2.05%   |
| Pop!_OS 22.04                | 44        | 1.96%   |
| OpenMandriva 4.3             | 40        | 1.78%   |
| Arch                         | 40        | 1.78%   |
| OpenMandriva 4.2             | 39        | 1.74%   |
| Zorin 16                     | 38        | 1.69%   |
| KDE neon 20.04               | 38        | 1.69%   |
| ArcoLinux Rolling            | 34        | 1.52%   |
| Linux Mint 21.1              | 33        | 1.47%   |
| Pop!_OS 20.04                | 31        | 1.38%   |
| Linux Mint 20.3              | 31        | 1.38%   |
| Debian 12                    | 30        | 1.34%   |
| Ubuntu 21.10                 | 29        | 1.29%   |
| Ubuntu 21.04                 | 29        | 1.29%   |
| Pop!_OS 20.10                | 29        | 1.29%   |
| Fedora 37                    | 29        | 1.29%   |
| Fedora 35                    | 29        | 1.29%   |
| openSUSE Tumbleweed-XXXXXXXX | 28        | 1.25%   |
| Ubuntu 19.04                 | 27        | 1.2%    |
| Fedora 34                    | 25        | 1.11%   |
| Ubuntu 19.10                 | 24        | 1.07%   |
| Fedora 36                    | 23        | 1.02%   |
| Fedora 32                    | 23        | 1.02%   |
| Zorin 15                     | 22        | 0.98%   |
| Linux Mint 20.2              | 20        | 0.89%   |
| Linux Mint 20                | 20        | 0.89%   |
| Xubuntu 20.04                | 19        | 0.85%   |
| Ubuntu 20.10                 | 19        | 0.85%   |
| Fedora 33                    | 19        | 0.85%   |
| Fedora 38                    | 18        | 0.8%    |
| Linux Mint 20.1              | 17        | 0.76%   |
| Ubuntu 22.10                 | 15        | 0.67%   |
| Fedora 31                    | 15        | 0.67%   |
| Debian 10                    | 15        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 686       | 31.97%  |
| Fedora        | 173       | 8.06%   |
| Linux Mint    | 162       | 7.55%   |
| Pop!_OS       | 159       | 7.41%   |
| Debian        | 119       | 5.55%   |
| OpenMandriva  | 108       | 5.03%   |
| Arch          | 100       | 4.66%   |
| Manjaro       | 92        | 4.29%   |
| Zorin         | 60        | 2.8%    |
| KDE neon      | 48        | 2.24%   |
| Xubuntu       | 44        | 2.05%   |
| ArcoLinux     | 39        | 1.82%   |
| openSUSE      | 34        | 1.58%   |
| Gentoo        | 33        | 1.54%   |
| Kubuntu       | 29        | 1.35%   |
| Kali          | 21        | 0.98%   |
| ROSA          | 20        | 0.93%   |
| EndeavourOS   | 17        | 0.79%   |
| Ubuntu MATE   | 16        | 0.75%   |
| Elementary    | 16        | 0.75%   |
| CentOS        | 14        | 0.65%   |
| Endless       | 10        | 0.47%   |
| Clear Linux   | 10        | 0.47%   |
| LMDE          | 9         | 0.42%   |
| Ubuntu Unity  | 8         | 0.37%   |
| SteamOS       | 8         | 0.37%   |
| Nobara        | 8         | 0.37%   |
| MX            | 8         | 0.37%   |
| Lubuntu       | 7         | 0.33%   |
| Ubuntu Budgie | 6         | 0.28%   |
| Peppermint    | 6         | 0.28%   |
| Garuda Linux  | 6         | 0.28%   |
| BunsenLabs    | 6         | 0.28%   |
| Solus         | 5         | 0.23%   |
| Parrot        | 5         | 0.23%   |
| Slackware     | 4         | 0.19%   |
| BlackPanther  | 4         | 0.19%   |
| Alpine        | 4         | 0.19%   |
| Ubuntu Studio | 3         | 0.14%   |
| Raspbian      | 3         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 39        | 1.59%   |
| 5.16.7-desktop-1omv4003  | 38        | 1.55%   |
| 5.4.0-42-generic         | 33        | 1.34%   |
| 5.15.0-56-generic        | 29        | 1.18%   |
| 5.4.0-58-generic         | 21        | 0.86%   |
| 5.4.0-48-generic         | 20        | 0.81%   |
| 5.15.0-52-generic        | 19        | 0.77%   |
| 5.11.0-7620-generic      | 19        | 0.77%   |
| 5.3.0-40-generic         | 17        | 0.69%   |
| 5.13.0-7614-generic      | 17        | 0.69%   |
| 5.4.0-52-generic         | 16        | 0.65%   |
| 5.15.0-46-generic        | 15        | 0.61%   |
| 5.13.0-30-generic        | 15        | 0.61%   |
| 5.4.0-40-generic         | 14        | 0.57%   |
| 5.15.0-58-generic        | 14        | 0.57%   |
| 5.13.0-39-generic        | 14        | 0.57%   |
| 5.4.0-7634-generic       | 13        | 0.53%   |
| 5.15.0-48-generic        | 13        | 0.53%   |
| 5.4.0-54-generic         | 12        | 0.49%   |
| 5.4.0-33-generic         | 12        | 0.49%   |
| 5.15.0-78-generic        | 12        | 0.49%   |
| 5.11.0-37-generic        | 12        | 0.49%   |
| 6.2.6-desktop-1omv2390   | 11        | 0.45%   |
| 6.2.6-76060206-generic   | 11        | 0.45%   |
| 5.8.0-48-generic         | 11        | 0.45%   |
| 5.4.0-70-generic         | 11        | 0.45%   |
| 5.19.0-35-generic        | 11        | 0.45%   |
| 5.15.0-60-generic        | 11        | 0.45%   |
| 5.15.0-53-generic        | 11        | 0.45%   |
| 5.15.0-50-generic        | 11        | 0.45%   |
| 5.11.0-7614-generic      | 11        | 0.45%   |
| 5.10.0-8-amd64           | 11        | 0.45%   |
| 6.2.0-20-generic         | 10        | 0.41%   |
| 6.1.0-9-amd64            | 10        | 0.41%   |
| 6.1.0-7-amd64            | 10        | 0.41%   |
| 5.8.0-43-generic         | 10        | 0.41%   |
| 5.4.0-65-generic         | 10        | 0.41%   |
| 5.4.0-29-generic         | 10        | 0.41%   |
| 5.19.0-38-generic        | 10        | 0.41%   |
| 5.15.0-41-generic        | 10        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 338       | 14.45%  |
| 5.15.0  | 212       | 9.06%   |
| 5.11.0  | 129       | 5.52%   |
| 5.13.0  | 120       | 5.13%   |
| 5.8.0   | 98        | 4.19%   |
| 4.15.0  | 81        | 3.46%   |
| 5.3.0   | 76        | 3.25%   |
| 5.10.0  | 76        | 3.25%   |
| 5.19.0  | 71        | 3.04%   |
| 5.0.0   | 59        | 2.52%   |
| 4.18.0  | 47        | 2.01%   |
| 6.1.0   | 46        | 1.97%   |
| 5.10.14 | 40        | 1.71%   |
| 5.16.7  | 39        | 1.67%   |
| 6.2.6   | 23        | 0.98%   |
| 6.2.0   | 23        | 0.98%   |
| 5.17.5  | 13        | 0.56%   |
| 6.1.1   | 12        | 0.51%   |
| 5.14.0  | 12        | 0.51%   |
| 4.19.0  | 11        | 0.47%   |
| 6.0.12  | 10        | 0.43%   |
| 5.18.0  | 10        | 0.43%   |
| 5.12.4  | 10        | 0.43%   |
| 6.2.9   | 9         | 0.38%   |
| 5.17.1  | 9         | 0.38%   |
| 5.16.0  | 8         | 0.34%   |
| 6.3.1   | 7         | 0.3%    |
| 6.1.12  | 7         | 0.3%    |
| 5.7.0   | 7         | 0.3%    |
| 5.19.16 | 7         | 0.3%    |
| 5.15.7  | 7         | 0.3%    |
| 6.4.3   | 6         | 0.26%   |
| 6.3.7   | 6         | 0.26%   |
| 6.3.0   | 6         | 0.26%   |
| 6.1.11  | 6         | 0.26%   |
| 5.9.0   | 6         | 0.26%   |
| 5.8.1   | 6         | 0.26%   |
| 5.15.5  | 6         | 0.26%   |
| 4.9.20  | 6         | 0.26%   |
| 6.3.8   | 5         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 368       | 16.03%  |
| 5.15    | 277       | 12.07%  |
| 5.10    | 162       | 7.06%   |
| 5.11    | 158       | 6.88%   |
| 5.13    | 140       | 6.1%    |
| 5.8     | 135       | 5.88%   |
| 6.1     | 93        | 4.05%   |
| 5.19    | 89        | 3.88%   |
| 5.3     | 88        | 3.83%   |
| 4.15    | 81        | 3.53%   |
| 5.16    | 80        | 3.49%   |
| 6.2     | 76        | 3.31%   |
| 5.0     | 62        | 2.7%    |
| 4.18    | 54        | 2.35%   |
| 5.17    | 48        | 2.09%   |
| 6.0     | 46        | 2%      |
| 6.3     | 40        | 1.74%   |
| 5.18    | 37        | 1.61%   |
| 5.12    | 36        | 1.57%   |
| 5.9     | 33        | 1.44%   |
| 5.14    | 33        | 1.44%   |
| 5.6     | 28        | 1.22%   |
| 5.7     | 24        | 1.05%   |
| 4.19    | 23        | 1%      |
| 6.4     | 18        | 0.78%   |
| 4.9     | 16        | 0.7%    |
| 5.5     | 15        | 0.65%   |
| 5.1     | 7         | 0.31%   |
| 5.2     | 6         | 0.26%   |
| 4.4     | 6         | 0.26%   |
| 4.14    | 3         | 0.13%   |
| 4.1     | 3         | 0.13%   |
| 4.20    | 2         | 0.09%   |
| 4.12    | 2         | 0.09%   |
| 3.10    | 2         | 0.09%   |
| 5       | 1         | 0.04%   |
| 4.16    | 1         | 0.04%   |
| 4.13    | 1         | 0.04%   |
| 3.2     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2017      | 97.77%  |
| i686    | 24        | 1.16%   |
| aarch64 | 15        | 0.73%   |
| armv7l  | 5         | 0.24%   |
| i586    | 1         | 0.05%   |
| armv8l  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1007      | 46.58%  |
| KDE5            | 301       | 13.92%  |
| Unknown         | 279       | 12.9%   |
| XFCE            | 170       | 7.86%   |
| X-Cinnamon      | 137       | 6.34%   |
| KDE             | 70        | 3.24%   |
| MATE            | 42        | 1.94%   |
| Cinnamon        | 19        | 0.88%   |
| i3              | 17        | 0.79%   |
| Pantheon        | 15        | 0.69%   |
| LXQt            | 14        | 0.65%   |
| LXDE            | 14        | 0.65%   |
| KDE4            | 11        | 0.51%   |
| Budgie          | 10        | 0.46%   |
| Unity           | 9         | 0.42%   |
| Deepin          | 7         | 0.32%   |
| awesome         | 6         | 0.28%   |
| GNOME Flashback | 5         | 0.23%   |
| GNOME Classic   | 5         | 0.23%   |
| sway            | 4         | 0.19%   |
| Openbox         | 4         | 0.19%   |
| DWM             | 3         | 0.14%   |
| qtile           | 2         | 0.09%   |
| LeftWM          | 2         | 0.09%   |
| BunsenLabs      | 2         | 0.09%   |
| xmonad          | 1         | 0.05%   |
| Trinity         | 1         | 0.05%   |
| spectrwm        | 1         | 0.05%   |
| Hyprland        | 1         | 0.05%   |
| GNOME-Flashback | 1         | 0.05%   |
| Enlightenment   | 1         | 0.05%   |
| bspwm           | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1535      | 72.41%  |
| Wayland     | 368       | 17.36%  |
| Unknown     | 138       | 6.51%   |
| Tty         | 78        | 3.68%   |
| Unspecified | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1106      | 51.49%  |
| SDDM    | 267       | 12.43%  |
| GDM3    | 254       | 11.82%  |
| GDM     | 234       | 10.89%  |
| LightDM | 194       | 9.03%   |
| TDM     | 63        | 2.93%   |
| KDM     | 11        | 0.51%   |
| XDM     | 6         | 0.28%   |
| Ly      | 6         | 0.28%   |
| LXDM    | 6         | 0.28%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1018      | 48%     |
| sv_SE       | 585       | 27.58%  |
| Unknown     | 227       | 10.7%   |
| en_GB       | 135       | 6.36%   |
| C           | 53        | 2.5%    |
| de_DE       | 15        | 0.71%   |
| ru_RU       | 14        | 0.66%   |
| en_SE       | 8         | 0.38%   |
| pl_PL       | 7         | 0.33%   |
| en_DK       | 7         | 0.33%   |
| uk_UA       | 4         | 0.19%   |
| fr_FR       | 4         | 0.19%   |
| nb_NO       | 3         | 0.14%   |
| fi_FI       | 3         | 0.14%   |
| en_CA       | 3         | 0.14%   |
| bg_BG       | 3         | 0.14%   |
| POSIX       | 2         | 0.09%   |
| lt_LT       | 2         | 0.09%   |
| it_IT       | 2         | 0.09%   |
| en_US.utf-8 | 2         | 0.09%   |
| en_IE       | 2         | 0.09%   |
| en_AG       | 2         | 0.09%   |
| el_GR       | 2         | 0.09%   |
| C.UTF8      | 2         | 0.09%   |
| zh_CN       | 1         | 0.05%   |
| tr_TR       | 1         | 0.05%   |
| sv_SE.UTF8  | 1         | 0.05%   |
| sv_FI       | 1         | 0.05%   |
| sma_SE      | 1         | 0.05%   |
| nn_NO       | 1         | 0.05%   |
| hu_HU       | 1         | 0.05%   |
| hr_HR       | 1         | 0.05%   |
| gl_ES       | 1         | 0.05%   |
| es_VE       | 1         | 0.05%   |
| es_ES       | 1         | 0.05%   |
| en_IN       | 1         | 0.05%   |
| en_GB.UTF8  | 1         | 0.05%   |
| en_GB.utf-8 | 1         | 0.05%   |
| en_AU       | 1         | 0.05%   |
| bs_BA       | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1099      | 51.82%  |
| BIOS | 1022      | 48.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1570      | 73.81%  |
| Btrfs    | 239       | 11.24%  |
| Overlay  | 141       | 6.63%   |
| Unknown  | 59        | 2.77%   |
| Tmpfs    | 48        | 2.26%   |
| Xfs      | 35        | 1.65%   |
| Zfs      | 18        | 0.85%   |
| Ext2     | 7         | 0.33%   |
| F2fs     | 6         | 0.28%   |
| Ext3     | 2         | 0.09%   |
| XXXXXXX  | 1         | 0.05%   |
| Reiserfs | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1110      | 52.06%  |
| GPT     | 840       | 39.4%   |
| MBR     | 182       | 8.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1833      | 87.33%  |
| Yes       | 266       | 12.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1604      | 76.49%  |
| Yes       | 493       | 23.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 453       | 21.96%  |
| Lenovo                  | 310       | 15.03%  |
| Hewlett-Packard         | 301       | 14.59%  |
| Dell                    | 219       | 10.62%  |
| MSI                     | 148       | 7.17%   |
| Gigabyte Technology     | 133       | 6.45%   |
| Acer                    | 102       | 4.94%   |
| Apple                   | 68        | 3.3%    |
| ASRock                  | 48        | 2.33%   |
| Intel                   | 29        | 1.41%   |
| Toshiba                 | 17        | 0.82%   |
| Fujitsu                 | 17        | 0.82%   |
| Raspberry Pi Foundation | 16        | 0.78%   |
| Sony                    | 15        | 0.73%   |
| Packard Bell            | 13        | 0.63%   |
| Unknown                 | 12        | 0.58%   |
| Samsung Electronics     | 10        | 0.48%   |
| Notebook                | 9         | 0.44%   |
| Google                  | 9         | 0.44%   |
| Supermicro              | 8         | 0.39%   |
| Microsoft               | 7         | 0.34%   |
| Fujitsu Siemens         | 7         | 0.34%   |
| Foxconn                 | 7         | 0.34%   |
| Valve                   | 6         | 0.29%   |
| Pegatron                | 6         | 0.29%   |
| AAEON                   | 5         | 0.24%   |
| Maxtang                 | 4         | 0.19%   |
| HUAWEI                  | 4         | 0.19%   |
| TUXEDO                  | 3         | 0.15%   |
| Star Labs               | 3         | 0.15%   |
| Clevo                   | 3         | 0.15%   |
| Alienware               | 3         | 0.15%   |
| Timi                    | 2         | 0.1%    |
| Shuttle                 | 2         | 0.1%    |
| Schenker                | 2         | 0.1%    |
| Razer                   | 2         | 0.1%    |
| PC Specialist           | 2         | 0.1%    |
| OEM                     | 2         | 0.1%    |
| Linx                    | 2         | 0.1%    |
| LG Electronics          | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS All Series                      | 21        | 1.02%   |
| Unknown                              | 16        | 0.78%   |
| ASUS ROG STRIX B450-F GAMING         | 12        | 0.58%   |
| ASUS ROG STRIX X570-F GAMING         | 10        | 0.48%   |
| ASUS ROG STRIX B550-F GAMING         | 9         | 0.44%   |
| MSI MS-7C37                          | 8         | 0.39%   |
| ASUS PRIME X470-PRO                  | 8         | 0.39%   |
| Dell XPS 13 9370                     | 7         | 0.34%   |
| ASUS Z170 PRO GAMING                 | 7         | 0.34%   |
| Valve Jupiter                        | 6         | 0.29%   |
| HP EliteBook Folio 9470m             | 6         | 0.29%   |
| Dell Precision 5540                  | 6         | 0.29%   |
| Apple MacBookPro9,2                  | 6         | 0.29%   |
| MSI MS-7C52                          | 5         | 0.24%   |
| MSI MS-7C02                          | 5         | 0.24%   |
| MSI MS-7817                          | 5         | 0.24%   |
| Lenovo Yoga C740-14IML 81TC          | 5         | 0.24%   |
| Lenovo MIIX 310-10ICR 80SG           | 5         | 0.24%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5     | 5         | 0.24%   |
| HP ProBook 640 G1                    | 5         | 0.24%   |
| HP Pavilion dv7                      | 5         | 0.24%   |
| HP Pavilion 15                       | 5         | 0.24%   |
| HP EliteBook 840 G3                  | 5         | 0.24%   |
| HP EliteBook 840 G2                  | 5         | 0.24%   |
| Gigabyte B550 AORUS ELITE V2         | 5         | 0.24%   |
| Gigabyte B450M DS3H                  | 5         | 0.24%   |
| Dell XPS 13 9310                     | 5         | 0.24%   |
| Dell OptiPlex 7010                   | 5         | 0.24%   |
| ASUS TUF Gaming X570-PLUS            | 5         | 0.24%   |
| ASUS ROG STRIX B550-I GAMING         | 5         | 0.24%   |
| ASUS ROG STRIX B350-F GAMING         | 5         | 0.24%   |
| ASUS PRIME X370-PRO                  | 5         | 0.24%   |
| ASUS M5A97 R2.0                      | 5         | 0.24%   |
| Apple MacBookPro11,3                 | 5         | 0.24%   |
| Acer Aspire V3-571                   | 5         | 0.24%   |
| RPi Raspberry Pi 4 Model B Rev 1.4   | 4         | 0.19%   |
| Maxtang FP30                         | 4         | 0.19%   |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX | 4         | 0.19%   |
| Lenovo ThinkPad L13 Gen 2 20VJS6RY00 | 4         | 0.19%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2    | 4         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 170       | 8.24%   |
| ASUS ROG              | 104       | 5.04%   |
| HP EliteBook          | 86        | 4.17%   |
| Acer Aspire           | 64        | 3.1%    |
| Dell Latitude         | 63        | 3.05%   |
| ASUS PRIME            | 52        | 2.52%   |
| Dell Precision        | 51        | 2.47%   |
| Dell XPS              | 46        | 2.23%   |
| HP Pavilion           | 42        | 2.04%   |
| Lenovo IdeaPad        | 38        | 1.84%   |
| HP ProBook            | 37        | 1.79%   |
| Dell OptiPlex         | 31        | 1.5%    |
| HP Compaq             | 28        | 1.36%   |
| Lenovo Yoga           | 24        | 1.16%   |
| ASUS TUF              | 22        | 1.07%   |
| ASUS All              | 21        | 1.02%   |
| ASUS VivoBook         | 20        | 0.97%   |
| HP ZBook              | 17        | 0.82%   |
| HP ENVY               | 17        | 0.82%   |
| RPi Raspberry         | 16        | 0.78%   |
| HP Laptop             | 16        | 0.78%   |
| Unknown               | 16        | 0.78%   |
| Toshiba Satellite     | 14        | 0.68%   |
| Lenovo Legion         | 12        | 0.58%   |
| Dell Inspiron         | 12        | 0.58%   |
| ASUS ZenBook          | 12        | 0.58%   |
| HP EliteDesk          | 11        | 0.53%   |
| Gigabyte X570         | 10        | 0.48%   |
| ASUS P8Z77-V          | 10        | 0.48%   |
| Acer Swift            | 10        | 0.48%   |
| Packard Bell EasyNote | 9         | 0.44%   |
| Lenovo ThinkCentre    | 9         | 0.44%   |
| Lenovo IdeaCentre     | 9         | 0.44%   |
| Dell Vostro           | 9         | 0.44%   |
| Acer Predator         | 9         | 0.44%   |
| MSI MS-7C37           | 8         | 0.39%   |
| Gigabyte B450M        | 8         | 0.39%   |
| ASUS SABERTOOTH       | 8         | 0.39%   |
| Acer Nitro            | 8         | 0.39%   |
| Microsoft Surface     | 7         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 220       | 10.66%  |
| 2019    | 207       | 10.03%  |
| 2020    | 185       | 8.97%   |
| 2021    | 154       | 7.46%   |
| 2013    | 152       | 7.37%   |
| 2012    | 150       | 7.27%   |
| 2017    | 148       | 7.17%   |
| 2011    | 142       | 6.88%   |
| 2015    | 128       | 6.2%    |
| 2014    | 111       | 5.38%   |
| 2016    | 109       | 5.28%   |
| 2010    | 91        | 4.41%   |
| 2022    | 74        | 3.59%   |
| 2008    | 56        | 2.71%   |
| 2009    | 54        | 2.62%   |
| 2007    | 38        | 1.84%   |
| Unknown | 15        | 0.73%   |
| 2006    | 10        | 0.48%   |
| 2023    | 9         | 0.44%   |
| 2005    | 8         | 0.39%   |
| 2004    | 1         | 0.05%   |
| 2002    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1062      | 51.48%  |
| Desktop        | 827       | 40.09%  |
| Convertible    | 60        | 2.91%   |
| Mini pc        | 43        | 2.08%   |
| All in one     | 19        | 0.92%   |
| System on chip | 18        | 0.87%   |
| Tablet         | 17        | 0.82%   |
| Server         | 14        | 0.68%   |
| Phone          | 3         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1887      | 90.98%  |
| Enabled  | 187       | 9.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2050      | 99.37%  |
| Yes  | 13        | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 499       | 23.86%  |
| 4.01-8.0        | 453       | 21.66%  |
| 8.01-16.0       | 356       | 17.03%  |
| 32.01-64.0      | 318       | 15.21%  |
| 3.01-4.0        | 261       | 12.48%  |
| 64.01-256.0     | 73        | 3.49%   |
| 1.01-2.0        | 55        | 2.63%   |
| 24.01-32.0      | 41        | 1.96%   |
| 2.01-3.0        | 16        | 0.77%   |
| 0.51-1.0        | 16        | 0.77%   |
| More than 256.0 | 2         | 0.1%    |
| 0.01-0.5        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 707       | 31.06%  |
| 2.01-3.0   | 559       | 24.56%  |
| 4.01-8.0   | 422       | 18.54%  |
| 3.01-4.0   | 309       | 13.58%  |
| 8.01-16.0  | 120       | 5.27%   |
| 0.51-1.0   | 102       | 4.48%   |
| 16.01-24.0 | 28        | 1.23%   |
| 0.01-0.5   | 22        | 0.97%   |
| 24.01-32.0 | 5         | 0.22%   |
| 32.01-64.0 | 1         | 0.04%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1265      | 59.5%   |
| 2      | 446       | 20.98%  |
| 3      | 185       | 8.7%    |
| 4      | 108       | 5.08%   |
| 5      | 44        | 2.07%   |
| 6      | 30        | 1.41%   |
| 0      | 21        | 0.99%   |
| 7      | 17        | 0.8%    |
| 8      | 5         | 0.24%   |
| 10     | 2         | 0.09%   |
| 26     | 1         | 0.05%   |
| 11     | 1         | 0.05%   |
| 9      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1422      | 68.53%  |
| Yes       | 653       | 31.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1788      | 86.46%  |
| No        | 280       | 13.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1509      | 72.55%  |
| No        | 571       | 27.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1286      | 61.41%  |
| No        | 808       | 38.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 2063      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Stockholm               | 398       | 17.94%  |
| Gothenburg              | 225       | 10.14%  |
| Malmo                   | 107       | 4.82%   |
| Uppsala                 | 59        | 2.66%   |
| Lund                    | 45        | 2.03%   |
| Linköping              | 41        | 1.85%   |
| Västerås              | 36        | 1.62%   |
| Bromma                  | 29        | 1.31%   |
| Sollentuna              | 27        | 1.22%   |
| Vaxjo                   | 25        | 1.13%   |
| Umeå                   | 24        | 1.08%   |
| Saltsjoe-Boo            | 24        | 1.08%   |
| Norrköping             | 24        | 1.08%   |
| Sundsvall               | 23        | 1.04%   |
| Solna                   | 23        | 1.04%   |
| Örebro                 | 23        | 1.04%   |
| Sundbyberg              | 20        | 0.9%    |
| Vaestra Froelunda       | 19        | 0.86%   |
| Karlstad                | 19        | 0.86%   |
| Haegersten              | 19        | 0.86%   |
| Huddinge                | 17        | 0.77%   |
| Helsingborg             | 17        | 0.77%   |
| Taby                    | 16        | 0.72%   |
| Södertälje            | 15        | 0.68%   |
| Karlskrona              | 15        | 0.68%   |
| Gävle                  | 15        | 0.68%   |
| Bandhagen               | 15        | 0.68%   |
| Kista                   | 14        | 0.63%   |
| Halmstad                | 14        | 0.63%   |
| Nyköping               | 13        | 0.59%   |
| Norsborg                | 12        | 0.54%   |
| Moelndal                | 12        | 0.54%   |
| Staffanstorp            | 11        | 0.5%    |
| Spanga                  | 11        | 0.5%    |
| Skövde                 | 11        | 0.5%    |
| Landskrona              | 11        | 0.5%    |
| Katrineholm             | 11        | 0.5%    |
| Järfälla Municipality | 11        | 0.5%    |
| Upplands Vasby          | 10        | 0.45%   |
| Alvsjo                  | 10        | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 690       | 1099   | 22.44%  |
| WDC                         | 409       | 652    | 13.3%   |
| Seagate                     | 377       | 605    | 12.26%  |
| Kingston                    | 236       | 331    | 7.67%   |
| Intel                       | 167       | 219    | 5.43%   |
| Sandisk                     | 155       | 198    | 5.04%   |
| Toshiba                     | 151       | 198    | 4.91%   |
| Unknown                     | 108       | 137    | 3.51%   |
| Hitachi                     | 86        | 121    | 2.8%    |
| SK hynix                    | 83        | 95     | 2.7%    |
| Crucial                     | 75        | 106    | 2.44%   |
| Micron Technology           | 69        | 83     | 2.24%   |
| HGST                        | 50        | 59     | 1.63%   |
| Apple                       | 35        | 43     | 1.14%   |
| Phison                      | 23        | 27     | 0.75%   |
| OCZ                         | 23        | 29     | 0.75%   |
| Corsair                     | 23        | 30     | 0.75%   |
| Kingston Technology Company | 22        | 26     | 0.72%   |
| A-DATA Technology           | 21        | 21     | 0.68%   |
| LITEON                      | 18        | 24     | 0.59%   |
| KIOXIA                      | 18        | 19     | 0.59%   |
| Phison Electronics          | 14        | 17     | 0.46%   |
| Transcend                   | 11        | 12     | 0.36%   |
| LITEONIT                    | 11        | 18     | 0.36%   |
| Intenso                     | 11        | 14     | 0.36%   |
| Fujitsu                     | 11        | 17     | 0.36%   |
| Silicon Motion              | 10        | 27     | 0.33%   |
| PNY                         | 9         | 11     | 0.29%   |
| China                       | 9         | 9      | 0.29%   |
| Maxtor                      | 7         | 7      | 0.23%   |
| Micron/Crucial Technology   | 6         | 10     | 0.2%    |
| LaCie                       | 6         | 7      | 0.2%    |
| JMicron Technology          | 6         | 6      | 0.2%    |
| ASMT                        | 6         | 6      | 0.2%    |
| Unknown                     | 6         | 6      | 0.2%    |
| SPCC                        | 5         | 15     | 0.16%   |
| Lenovo                      | 5         | 5      | 0.16%   |
| Verbatim                    | 4         | 7      | 0.13%   |
| Hewlett-Packard             | 4         | 6      | 0.13%   |
| XPG                         | 3         | 3      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 54        | 1.53%   |
| Samsung SSD 850 EVO 500GB                           | 43        | 1.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 37        | 1.05%   |
| Kingston SA400S37120G 120GB SSD                     | 37        | 1.05%   |
| Kingston SA400S37240G 240GB SSD                     | 31        | 0.88%   |
| Kingston SV300S37A120G 120GB SSD                    | 29        | 0.82%   |
| Samsung SSD 860 EVO 250GB                           | 26        | 0.74%   |
| Samsung SSD 840 EVO 250GB                           | 26        | 0.74%   |
| Samsung NVMe SSD Drive 500GB                        | 25        | 0.71%   |
| Kingston SA400S37480G 480GB SSD                     | 25        | 0.71%   |
| Samsung SSD 860 EVO 500GB                           | 24        | 0.68%   |
| Seagate ST4000DM004-2CV104 4TB                      | 23        | 0.65%   |
| Samsung NVMe SSD Drive 512GB                        | 20        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB                      | 19        | 0.54%   |
| SanDisk NVMe SSD Drive 1TB                          | 18        | 0.51%   |
| Samsung SSD 970 EVO Plus 500GB                      | 18        | 0.51%   |
| Unknown MMC Card  32GB                              | 17        | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB                      | 16        | 0.45%   |
| Samsung SSD 860 EVO 1TB                             | 16        | 0.45%   |
| Samsung NVMe SSD Drive 1TB                          | 16        | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 16        | 0.45%   |
| Samsung NVMe SSD Drive 256GB                        | 15        | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 14        | 0.4%    |
| WDC WD30EFRX-68EUZN0 3TB                            | 14        | 0.4%    |
| Seagate ST500DM002-1BD142 500GB                     | 14        | 0.4%    |
| Seagate ST2000DM006-2DM164 2TB                      | 14        | 0.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 14        | 0.4%    |
| HGST HTS721010A9E630 1TB                            | 14        | 0.4%    |
| Seagate ST4000VN008-2DR166 4TB                      | 13        | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB                      | 13        | 0.37%   |
| SanDisk NVMe SSD Drive 512GB                        | 13        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB                        | 13        | 0.37%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 13        | 0.37%   |
| Unknown SD/MMC/MS PRO 128GB                         | 12        | 0.34%   |
| Toshiba NVMe SSD Drive 512GB                        | 12        | 0.34%   |
| Seagate Expansion 1TB                               | 12        | 0.34%   |
| Samsung SSD 840 EVO 500GB                           | 12        | 0.34%   |
| Samsung NVMe SSD Drive 1024GB                       | 12        | 0.34%   |
| Unknown MMC Card  16GB                              | 11        | 0.31%   |
| SK hynix NVMe SSD Drive 512GB                       | 11        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 371       | 590    | 36.37%  |
| WDC                 | 313       | 516    | 30.69%  |
| Hitachi             | 86        | 121    | 8.43%   |
| Toshiba             | 81        | 110    | 7.94%   |
| Samsung Electronics | 57        | 92     | 5.59%   |
| HGST                | 50        | 59     | 4.9%    |
| Unknown             | 13        | 15     | 1.27%   |
| Fujitsu             | 11        | 17     | 1.08%   |
| Apple               | 11        | 11     | 1.08%   |
| Maxtor              | 6         | 6      | 0.59%   |
| ASMT                | 5         | 5      | 0.49%   |
| JMicron Technology  | 4         | 4      | 0.39%   |
| Intenso             | 3         | 3      | 0.29%   |
| ASMedia             | 3         | 3      | 0.29%   |
| Hewlett-Packard     | 2         | 4      | 0.2%    |
| USB3.0              | 1         | 1      | 0.1%    |
| MARVELL             | 1         | 1      | 0.1%    |
| LaCie               | 1         | 1      | 0.1%    |
| IB                  | 1         | 2      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 387       | 571    | 33.56%  |
| Kingston            | 181       | 249    | 15.7%   |
| Intel               | 95        | 123    | 8.24%   |
| SanDisk             | 76        | 94     | 6.59%   |
| Crucial             | 71        | 100    | 6.16%   |
| WDC                 | 60        | 80     | 5.2%    |
| Micron Technology   | 42        | 54     | 3.64%   |
| SK hynix            | 25        | 28     | 2.17%   |
| OCZ                 | 23        | 29     | 1.99%   |
| Apple               | 22        | 28     | 1.91%   |
| Toshiba             | 20        | 27     | 1.73%   |
| LITEON              | 17        | 23     | 1.47%   |
| Corsair             | 14        | 16     | 1.21%   |
| A-DATA Technology   | 12        | 12     | 1.04%   |
| Transcend           | 11        | 12     | 0.95%   |
| LITEONIT            | 11        | 18     | 0.95%   |
| China               | 9         | 9      | 0.78%   |
| Intenso             | 7         | 7      | 0.61%   |
| PNY                 | 6         | 8      | 0.52%   |
| SPCC                | 5         | 15     | 0.43%   |
| Verbatim            | 4         | 7      | 0.35%   |
| M4-CT128            | 3         | 3      | 0.26%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.26%   |
| Seagate             | 2         | 4      | 0.17%   |
| Patriot             | 2         | 3      | 0.17%   |
| OCZ-VERTEX3         | 2         | 2      | 0.17%   |
| KingSpec            | 2         | 2      | 0.17%   |
| INTEL SS            | 2         | 3      | 0.17%   |
| GOODRAM             | 2         | 3      | 0.17%   |
| Emtec               | 2         | 2      | 0.17%   |
| Apacer              | 2         | 2      | 0.17%   |
| XSTAR               | 1         | 2      | 0.09%   |
| WDC WDS2            | 1         | 1      | 0.09%   |
| WDC WDS1            | 1         | 1      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| tigo                | 1         | 1      | 0.09%   |
| Team                | 1         | 1      | 0.09%   |
| StoreJet            | 1         | 1      | 0.09%   |
| Star                | 1         | 1      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 990       | 1574   | 35.87%  |
| HDD     | 832       | 1561   | 30.14%  |
| NVMe    | 803       | 1130   | 29.09%  |
| MMC     | 101       | 120    | 3.66%   |
| Unknown | 34        | 43     | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1447      | 2984   | 58.42%  |
| NVMe | 801       | 1125   | 32.34%  |
| SAS  | 128       | 199    | 5.17%   |
| MMC  | 101       | 120    | 4.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1180      | 1913   | 59.72%  |
| 0.51-1.0   | 439       | 659    | 22.22%  |
| 1.01-2.0   | 169       | 253    | 8.55%   |
| 3.01-4.0   | 78        | 128    | 3.95%   |
| 2.01-3.0   | 59        | 93     | 2.99%   |
| 4.01-10.0  | 44        | 80     | 2.23%   |
| 10.01-20.0 | 7         | 9      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 590       | 26.93%  |
| 251-500        | 477       | 21.77%  |
| 501-1000       | 290       | 13.24%  |
| 1-20           | 183       | 8.35%   |
| 1001-2000      | 175       | 7.99%   |
| More than 3000 | 161       | 7.35%   |
| 51-100         | 106       | 4.84%   |
| Unknown        | 81        | 3.7%    |
| 2001-3000      | 68        | 3.1%    |
| 21-50          | 60        | 2.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 838       | 37.39%  |
| 21-50          | 328       | 14.64%  |
| 101-250        | 293       | 13.07%  |
| 51-100         | 235       | 10.49%  |
| 251-500        | 157       | 7.01%   |
| 501-1000       | 132       | 5.89%   |
| Unknown        | 81        | 3.61%   |
| 1001-2000      | 72        | 3.21%   |
| More than 3000 | 58        | 2.59%   |
| 2001-3000      | 45        | 2.01%   |
| 0              | 2         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 5         | 5      | 2.94%   |
| Seagate ST9250410AS 250GB                      | 3         | 4      | 1.76%   |
| Samsung Electronics SSD 870 EVO 1TB            | 3         | 3      | 1.76%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 3         | 4      | 1.76%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 1.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 2         | 2      | 1.18%   |
| WDC WD5000AAKX-75U6AA0 500GB                   | 2         | 2      | 1.18%   |
| WDC WD5000AAKX-22ERMA0 500GB                   | 2         | 2      | 1.18%   |
| Seagate ST9500420AS 500GB                      | 2         | 2      | 1.18%   |
| Seagate ST4000DM004-2CV104 4TB                 | 2         | 2      | 1.18%   |
| Seagate ST3500418AS 500GB                      | 2         | 2      | 1.18%   |
| Seagate ST2000DM001-1CH164 2TB                 | 2         | 2      | 1.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2         | 2      | 1.18%   |
| Samsung Electronics SP2504C 250GB              | 2         | 2      | 1.18%   |
| Samsung Electronics HD501LJ 500GB              | 2         | 2      | 1.18%   |
| Samsung Electronics HD300LJ 304GB              | 2         | 2      | 1.18%   |
| Intel SSDSC2BW480A4 480GB                      | 2         | 3      | 1.18%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 1.18%   |
| Crucial CT525MX300SSD1 528GB                   | 2         | 2      | 1.18%   |
| WDC WD7500AACS-00ZJB0 752GB                    | 1         | 1      | 0.59%   |
| WDC WD740GD-00FLA1 74GB                        | 1         | 1      | 0.59%   |
| WDC WD6400AAKS-22A7B2 640GB                    | 1         | 1      | 0.59%   |
| WDC WD60EFRX-68L0BN1 6TB                       | 1         | 6      | 0.59%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 0.59%   |
| WDC WD5000BPKT-60PK4T0 500GB                   | 1         | 1      | 0.59%   |
| WDC WD5000AZRX-00A8LB0 500GB                   | 1         | 2      | 0.59%   |
| WDC WD5000AAKS-00A7B2 500GB                    | 1         | 1      | 0.59%   |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 2      | 0.59%   |
| WDC WD4003FZEX-00Z4SA0 4TB                     | 1         | 2      | 0.59%   |
| WDC WD3200AAKS-75L9A0 320GB                    | 1         | 1      | 0.59%   |
| WDC WD3200AAKS-00B3A0 320GB                    | 1         | 4      | 0.59%   |
| WDC WD30EFRX-68AX9N0 3TB                       | 1         | 1      | 0.59%   |
| WDC WD20EARS-00MVWB0 2TB                       | 1         | 1      | 0.59%   |
| WDC WD15EARS-00Z5B1 1TB                        | 1         | 1      | 0.59%   |
| WDC WD15EADS-00P8B0 1TB                        | 1         | 2      | 0.59%   |
| WDC WD10EZEX-21M2NA0 1TB                       | 1         | 2      | 0.59%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1         | 3      | 0.59%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 0.59%   |
| WDC WD10EFRX-68FYTN0 1TB                       | 1         | 1      | 0.59%   |
| WDC WD10EARS-00Y5B1 1TB                        | 1         | 2      | 0.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 46     | 23.64%  |
| WDC                 | 28        | 50     | 16.97%  |
| Samsung Electronics | 20        | 20     | 12.12%  |
| Hitachi             | 16        | 18     | 9.7%    |
| Intel               | 13        | 16     | 7.88%   |
| HGST                | 7         | 7      | 4.24%   |
| Toshiba             | 5         | 6      | 3.03%   |
| Kingston            | 5         | 5      | 3.03%   |
| Crucial             | 5         | 5      | 3.03%   |
| Micron Technology   | 4         | 5      | 2.42%   |
| OCZ                 | 3         | 5      | 1.82%   |
| Corsair             | 3         | 3      | 1.82%   |
| SK hynix            | 2         | 2      | 1.21%   |
| SanDisk             | 2         | 2      | 1.21%   |
| LITEONIT            | 2         | 2      | 1.21%   |
| Fujitsu             | 2         | 2      | 1.21%   |
| Apple               | 2         | 2      | 1.21%   |
| Union Memory        | 1         | 1      | 0.61%   |
| Transcend           | 1         | 1      | 0.61%   |
| Team                | 1         | 1      | 0.61%   |
| PNY                 | 1         | 2      | 0.61%   |
| Hewlett-Packard     | 1         | 1      | 0.61%   |
| China               | 1         | 1      | 0.61%   |
| A-DATA Technology   | 1         | 1      | 0.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 46     | 35.78%  |
| WDC                 | 26        | 48     | 23.85%  |
| Hitachi             | 16        | 18     | 14.68%  |
| Samsung Electronics | 12        | 12     | 11.01%  |
| HGST                | 7         | 7      | 6.42%   |
| Toshiba             | 4         | 5      | 3.67%   |
| Fujitsu             | 2         | 2      | 1.83%   |
| Apple               | 2         | 2      | 1.83%   |
| Hewlett-Packard     | 1         | 1      | 0.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 105       | 141    | 66.04%  |
| SSD  | 47        | 56     | 29.56%  |
| NVMe | 7         | 7      | 4.4%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                                 | 1         | 1      | 50%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1309      | 2771   | 57.84%  |
| Works    | 799       | 1451   | 35.31%  |
| Malfunc  | 153       | 204    | 6.76%   |
| Failed   | 2         | 2      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1274      | 47.27%  |
| AMD                              | 444       | 16.47%  |
| Samsung Electronics              | 354       | 13.14%  |
| SanDisk                          | 118       | 4.38%   |
| Kingston Technology Company      | 79        | 2.93%   |
| SK hynix                         | 57        | 2.12%   |
| Toshiba America Info Systems     | 54        | 2%      |
| Phison Electronics               | 47        | 1.74%   |
| ASMedia Technology               | 45        | 1.67%   |
| JMicron Technology               | 36        | 1.34%   |
| Marvell Technology Group         | 32        | 1.19%   |
| Micron Technology                | 28        | 1.04%   |
| Nvidia                           | 22        | 0.82%   |
| KIOXIA                           | 17        | 0.63%   |
| Silicon Motion                   | 12        | 0.45%   |
| ADATA Technology                 | 12        | 0.45%   |
| Micron/Crucial Technology        | 9         | 0.33%   |
| Silicon Image                    | 6         | 0.22%   |
| VIA Technologies                 | 5         | 0.19%   |
| Union Memory (Shenzhen)          | 5         | 0.19%   |
| Lite-On Technology               | 5         | 0.19%   |
| Lenovo                           | 5         | 0.19%   |
| Broadcom / LSI                   | 4         | 0.15%   |
| Apple                            | 4         | 0.15%   |
| Solid State Storage Technology   | 3         | 0.11%   |
| Silicon Integrated Systems [SiS] | 3         | 0.11%   |
| Seagate Technology               | 3         | 0.11%   |
| Realtek Semiconductor            | 3         | 0.11%   |
| LSI Logic / Symbios Logic        | 3         | 0.11%   |
| Hewlett-Packard                  | 3         | 0.11%   |
| Integrated Technology Express    | 1         | 0.04%   |
| HighPoint Technologies           | 1         | 0.04%   |
| Adaptec                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 295       | 9.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 189       | 6.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 96        | 3.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 92        | 2.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 79        | 2.57%   |
| AMD 400 Series Chipset SATA Controller                                         | 74        | 2.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 60        | 1.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 60        | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 57        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 54        | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 53        | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 51        | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 48        | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 46        | 1.49%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 46        | 1.49%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 44        | 1.43%   |
| AMD 500 Series Chipset SATA Controller                                         | 41        | 1.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 40        | 1.3%    |
| Samsung NVMe SSD Controller 980                                                | 39        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 39        | 1.27%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 38        | 1.23%   |
| Intel SSD 660P Series                                                          | 38        | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 38        | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 37        | 1.2%    |
| Intel SATA Controller [RAID mode]                                              | 37        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 35        | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 34        | 1.1%    |
| Kingston Company A2000 NVMe SSD                                                | 33        | 1.07%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 30        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 30        | 0.97%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 28        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 24        | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 0.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 23        | 0.75%   |
| Phison E12 NVMe Controller                                                     | 22        | 0.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 22        | 0.71%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 21        | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 21        | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 19        | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                          | 19        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1471      | 54.89%  |
| NVMe | 809       | 30.19%  |
| IDE  | 233       | 8.69%   |
| RAID | 156       | 5.82%   |
| SAS  | 8         | 0.3%    |
| SCSI | 3         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1499      | 72.66%  |
| AMD      | 543       | 26.32%  |
| ARM      | 20        | 0.97%   |
| QUALCOMM | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 29        | 1.4%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 29        | 1.4%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 25        | 1.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 24        | 1.16%   |
| AMD Ryzen 5 3600 6-Core Processor           | 24        | 1.16%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 19        | 0.92%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 18        | 0.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 16        | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 16        | 0.77%   |
| ARM Processor                               | 15        | 0.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 14        | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 13        | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 13        | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 13        | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 13        | 0.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 13        | 0.63%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 13        | 0.63%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 12        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 11        | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 11        | 0.53%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 11        | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 11        | 0.53%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 11        | 0.53%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 11        | 0.53%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 11        | 0.53%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 11        | 0.53%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 11        | 0.53%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 10        | 0.48%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 10        | 0.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 10        | 0.48%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 10        | 0.48%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 10        | 0.48%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 10        | 0.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 10        | 0.48%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 10        | 0.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 9         | 0.44%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 9         | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9         | 0.44%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 9         | 0.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 9         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 496       | 24.02%  |
| Intel Core i7           | 461       | 22.32%  |
| Other                   | 157       | 7.6%    |
| AMD Ryzen 5             | 138       | 6.68%   |
| AMD Ryzen 7             | 115       | 5.57%   |
| Intel Core i3           | 84        | 4.07%   |
| Intel Celeron           | 75        | 3.63%   |
| Intel Core 2 Duo        | 61        | 2.95%   |
| AMD Ryzen 9             | 59        | 2.86%   |
| Intel Xeon              | 48        | 2.32%   |
| AMD FX                  | 34        | 1.65%   |
| Intel Pentium           | 33        | 1.6%    |
| Intel Atom              | 27        | 1.31%   |
| AMD Ryzen 3             | 19        | 0.92%   |
| Intel Core i9           | 17        | 0.82%   |
| Intel Core 2 Quad       | 15        | 0.73%   |
| AMD A8                  | 15        | 0.73%   |
| Intel Core 2            | 13        | 0.63%   |
| AMD A6                  | 12        | 0.58%   |
| AMD Ryzen Threadripper  | 11        | 0.53%   |
| Intel Genuine           | 10        | 0.48%   |
| AMD Phenom II X4        | 10        | 0.48%   |
| AMD A4                  | 10        | 0.48%   |
| Intel Pentium Dual-Core | 9         | 0.44%   |
| AMD Ryzen 7 PRO         | 9         | 0.44%   |
| AMD A10                 | 9         | 0.44%   |
| AMD E                   | 8         | 0.39%   |
| AMD Ryzen 5 PRO         | 7         | 0.34%   |
| AMD Phenom II X6        | 7         | 0.34%   |
| AMD E1                  | 7         | 0.34%   |
| AMD Athlon 64 X2        | 7         | 0.34%   |
| Intel Pentium Silver    | 6         | 0.29%   |
| AMD Athlon II X2        | 6         | 0.29%   |
| Intel Pentium Dual      | 5         | 0.24%   |
| ARM BCM                 | 5         | 0.24%   |
| AMD Ryzen Embedded      | 5         | 0.24%   |
| Intel Pentium M         | 3         | 0.15%   |
| Intel Core m3           | 3         | 0.15%   |
| Intel Celeron Dual-Core | 3         | 0.15%   |
| AMD Turion 64 X2 Mobile | 3         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 785       | 37.96%  |
| 2       | 673       | 32.54%  |
| 6       | 254       | 12.28%  |
| 8       | 184       | 8.9%    |
| 12      | 52        | 2.51%   |
| 16      | 31        | 1.5%    |
| 1       | 31        | 1.5%    |
| 3       | 19        | 0.92%   |
| 14      | 12        | 0.58%   |
| 10      | 12        | 0.58%   |
| Unknown | 5         | 0.24%   |
| 18      | 4         | 0.19%   |
| 32      | 2         | 0.1%    |
| 64      | 1         | 0.05%   |
| 28      | 1         | 0.05%   |
| 24      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2036      | 98.69%  |
| 2       | 22        | 1.07%   |
| Unknown | 4         | 0.19%   |
| 3       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1427      | 69.04%  |
| 1       | 635       | 30.72%  |
| Unknown | 5         | 0.24%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2014      | 97.44%  |
| Unknown        | 41        | 1.98%   |
| 32-bit         | 11        | 0.53%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 599       | 27.85%  |
| 0x306c3    | 100       | 4.65%   |
| 0x206a7    | 90        | 4.18%   |
| 0x306a9    | 88        | 4.09%   |
| 0x40651    | 49        | 2.28%   |
| 0x906ea    | 48        | 2.23%   |
| 0x1067a    | 48        | 2.23%   |
| 0x806ec    | 47        | 2.19%   |
| 0x806ea    | 47        | 2.19%   |
| 0x806c1    | 47        | 2.19%   |
| 0x506e3    | 45        | 2.09%   |
| 0x906e9    | 43        | 2%      |
| 0x406e3    | 43        | 2%      |
| 0x306d4    | 43        | 2%      |
| 0x806e9    | 41        | 1.91%   |
| 0x08701021 | 40        | 1.86%   |
| 0x20655    | 28        | 1.3%    |
| 0x0a50000c | 23        | 1.07%   |
| 0x08108109 | 23        | 1.07%   |
| 0x08701013 | 20        | 0.93%   |
| 0x0800820d | 20        | 0.93%   |
| 0x406c4    | 19        | 0.88%   |
| 0x08600106 | 18        | 0.84%   |
| 0x906ed    | 15        | 0.7%    |
| 0x06000852 | 15        | 0.7%    |
| 0x806eb    | 14        | 0.65%   |
| 0x6fd      | 14        | 0.65%   |
| 0x306f2    | 14        | 0.65%   |
| 0x0a201009 | 14        | 0.65%   |
| 0x0810100b | 14        | 0.65%   |
| 0x010000c8 | 14        | 0.65%   |
| 0xa0652    | 13        | 0.6%    |
| 0x30678    | 13        | 0.6%    |
| 0x106e5    | 13        | 0.6%    |
| 0x06001119 | 13        | 0.6%    |
| 0x906a3    | 12        | 0.56%   |
| 0x6f6      | 12        | 0.56%   |
| 0x08608103 | 12        | 0.56%   |
| 0x08001138 | 12        | 0.56%   |
| 0x10676    | 11        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 361       | 17.46%  |
| Haswell          | 216       | 10.45%  |
| SandyBridge      | 133       | 6.43%   |
| IvyBridge        | 130       | 6.29%   |
| Skylake          | 126       | 6.1%    |
| Zen 2            | 118       | 5.71%   |
| Unknown          | 90        | 4.35%   |
| Zen 3            | 88        | 4.26%   |
| Penryn           | 73        | 3.53%   |
| Zen+             | 70        | 3.39%   |
| TigerLake        | 60        | 2.9%    |
| Broadwell        | 57        | 2.76%   |
| Silvermont       | 54        | 2.61%   |
| Zen              | 52        | 2.52%   |
| Westmere         | 51        | 2.47%   |
| Core             | 49        | 2.37%   |
| K10              | 41        | 1.98%   |
| Piledriver       | 40        | 1.94%   |
| CometLake        | 37        | 1.79%   |
| Alderlake Hybrid | 32        | 1.55%   |
| Icelake          | 23        | 1.11%   |
| Nehalem          | 22        | 1.06%   |
| Goldmont plus    | 22        | 1.06%   |
| Excavator        | 18        | 0.87%   |
| K8 Hammer        | 14        | 0.68%   |
| K10 Llano        | 12        | 0.58%   |
| Goldmont         | 11        | 0.53%   |
| Bobcat           | 11        | 0.53%   |
| Jaguar           | 10        | 0.48%   |
| Bulldozer        | 10        | 0.48%   |
| Puma             | 8         | 0.39%   |
| Bonnell          | 8         | 0.39%   |
| P6               | 5         | 0.24%   |
| Tremont          | 4         | 0.19%   |
| Steamroller      | 3         | 0.15%   |
| NetBurst         | 3         | 0.15%   |
| K8 & K10 hybrid  | 3         | 0.15%   |
| K6               | 1         | 0.05%   |
| Geode            | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1075      | 44.89%  |
| Nvidia                           | 757       | 31.61%  |
| AMD                              | 544       | 22.71%  |
| Matrox Electronics Systems       | 9         | 0.38%   |
| ASPEED Technology                | 7         | 0.29%   |
| Silicon Integrated Systems [SiS] | 3         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 88        | 3.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 72        | 2.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 63        | 2.54%   |
| Intel UHD Graphics 620                                                                   | 61        | 2.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 51        | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 50        | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 49        | 1.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 47        | 1.9%    |
| Intel HD Graphics 620                                                                    | 43        | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 1.74%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 42        | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 39        | 1.57%   |
| Intel HD Graphics 5500                                                                   | 38        | 1.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 35        | 1.41%   |
| AMD Renoir                                                                               | 34        | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 34        | 1.37%   |
| Intel HD Graphics 630                                                                    | 33        | 1.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 1.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 27        | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 27        | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 25        | 1.01%   |
| Intel HD Graphics 530                                                                    | 23        | 0.93%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 23        | 0.93%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 20        | 0.81%   |
| AMD Lucienne                                                                             | 20        | 0.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 0.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 19        | 0.77%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 18        | 0.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 18        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 17        | 0.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 17        | 0.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 16        | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 16        | 0.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 0.65%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 16        | 0.65%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 16        | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 0.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 774       | 37.23%  |
| 1 x Nvidia               | 478       | 22.99%  |
| 1 x AMD                  | 431       | 20.73%  |
| Intel + Nvidia           | 231       | 11.11%  |
| 2 x AMD                  | 41        | 1.97%   |
| AMD + Nvidia             | 38        | 1.83%   |
| Intel + AMD              | 34        | 1.64%   |
| Other                    | 22        | 1.06%   |
| 1 x Matrox               | 7         | 0.34%   |
| 1 x ASPEED               | 7         | 0.34%   |
| 2 x Nvidia               | 5         | 0.24%   |
| 1 x SiS                  | 3         | 0.14%   |
| 2 x Intel                | 2         | 0.1%    |
| Intel + 2 x Nvidia       | 2         | 0.1%    |
| Intel + AMD + 1 x Nvidia | 2         | 0.1%    |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.05%   |
| Nvidia + Matrox          | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1547      | 73.77%  |
| Proprietary | 457       | 21.79%  |
| Unknown     | 93        | 4.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1161      | 54.58%  |
| 1.01-2.0   | 228       | 10.72%  |
| 0.01-0.5   | 217       | 10.2%   |
| 0.51-1.0   | 131       | 6.16%   |
| 3.01-4.0   | 128       | 6.02%   |
| 7.01-8.0   | 127       | 5.97%   |
| 5.01-6.0   | 62        | 2.91%   |
| 8.01-16.0  | 42        | 1.97%   |
| 2.01-3.0   | 24        | 1.13%   |
| 16.01-24.0 | 7         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 294       | 12.56%  |
| Samsung Electronics     | 279       | 11.92%  |
| LG Display              | 176       | 7.52%   |
| Chimei Innolux          | 164       | 7.01%   |
| Dell                    | 135       | 5.77%   |
| BenQ                    | 119       | 5.08%   |
| Philips                 | 109       | 4.66%   |
| BOE                     | 105       | 4.49%   |
| Ancor Communications    | 97        | 4.14%   |
| Hewlett-Packard         | 94        | 4.02%   |
| AOC                     | 90        | 3.84%   |
| Acer                    | 82        | 3.5%    |
| Sharp                   | 60        | 2.56%   |
| Goldstar                | 60        | 2.56%   |
| Apple                   | 55        | 2.35%   |
| Lenovo                  | 46        | 1.96%   |
| ASUSTek Computer        | 34        | 1.45%   |
| Chi Mei Optoelectronics | 24        | 1.03%   |
| MSI                     | 23        | 0.98%   |
| InfoVision              | 23        | 0.98%   |
| Eizo                    | 22        | 0.94%   |
| LG Philips              | 17        | 0.73%   |
| Vestel Elektronik       | 15        | 0.64%   |
| Sony                    | 15        | 0.64%   |
| CSO                     | 15        | 0.64%   |
| Unknown                 | 13        | 0.56%   |
| Panasonic               | 12        | 0.51%   |
| LG Electronics          | 11        | 0.47%   |
| Fujitsu Siemens         | 10        | 0.43%   |
| PANDA                   | 9         | 0.38%   |
| ViewSonic               | 8         | 0.34%   |
| Gigabyte Technology     | 7         | 0.3%    |
| VOXICON                 | 5         | 0.21%   |
| Toshiba                 | 5         | 0.21%   |
| Microstep               | 5         | 0.21%   |
| LGD                     | 5         | 0.21%   |
| BOE Technology Group    | 5         | 0.21%   |
| Quanta Display          | 4         | 0.17%   |
| Positivo                | 4         | 0.17%   |
| Onkyo                   | 4         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 15        | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 15        | 0.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 12        | 0.49%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 10        | 0.41%   |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                  | 9         | 0.37%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 9         | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 8         | 0.33%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 8         | 0.33%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                      | 8         | 0.33%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 8         | 0.33%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 0.29%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 7         | 0.29%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 6         | 0.25%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                  | 6         | 0.25%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch           | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 6         | 0.25%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 6         | 0.25%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 6         | 0.25%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 6         | 0.25%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 5         | 0.21%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 5         | 0.21%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 940x530mm 42.5-inch            | 5         | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 5         | 0.21%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 5         | 0.21%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 5         | 0.21%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 5         | 0.21%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch          | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 5         | 0.21%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch      | 5         | 0.21%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 5         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 982       | 43.84%  |
| 1366x768 (WXGA)    | 264       | 11.79%  |
| 3840x2160 (4K)     | 192       | 8.57%   |
| 2560x1440 (QHD)    | 188       | 8.39%   |
| 1680x1050 (WSXGA+) | 79        | 3.53%   |
| 1920x1200 (WUXGA)  | 73        | 3.26%   |
| 3440x1440          | 57        | 2.54%   |
| 1600x900 (HD+)     | 47        | 2.1%    |
| 1280x1024 (SXGA)   | 47        | 2.1%    |
| 1280x800 (WXGA)    | 45        | 2.01%   |
| Unknown            | 38        | 1.7%    |
| 2560x1600          | 31        | 1.38%   |
| 1440x900 (WXGA+)   | 29        | 1.29%   |
| 2880x1800          | 19        | 0.85%   |
| 3840x2400          | 18        | 0.8%    |
| 3840x1080          | 17        | 0.76%   |
| 1024x768 (XGA)     | 13        | 0.58%   |
| 1360x768           | 11        | 0.49%   |
| 1920x540           | 9         | 0.4%    |
| 1280x720 (HD)      | 8         | 0.36%   |
| 3200x1800 (QHD+)   | 7         | 0.31%   |
| 2736x1824          | 7         | 0.31%   |
| 2560x1080          | 6         | 0.27%   |
| 800x1280           | 5         | 0.22%   |
| 1024x600           | 5         | 0.22%   |
| 3840x1600          | 4         | 0.18%   |
| 6400x2160          | 3         | 0.13%   |
| 5760x2160          | 3         | 0.13%   |
| 5760x1080          | 3         | 0.13%   |
| 2288x1287          | 3         | 0.13%   |
| 2160x1440          | 3         | 0.13%   |
| 4480x1440          | 2         | 0.09%   |
| 3840x1200          | 2         | 0.09%   |
| 3200x1200          | 2         | 0.09%   |
| 1280x768           | 2         | 0.09%   |
| 7280x2160          | 1         | 0.04%   |
| 5520x2160          | 1         | 0.04%   |
| 5360x1440          | 1         | 0.04%   |
| 4864x1080          | 1         | 0.04%   |
| 4240x1440          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 414       | 17.85%  |
| 13      | 271       | 11.69%  |
| 27      | 255       | 11%     |
| 24      | 241       | 10.39%  |
| 14      | 176       | 7.59%   |
| Unknown | 145       | 6.25%   |
| 23      | 140       | 6.04%   |
| 17      | 87        | 3.75%   |
| 21      | 69        | 2.98%   |
| 12      | 65        | 2.8%    |
| 31      | 57        | 2.46%   |
| 22      | 56        | 2.41%   |
| 34      | 52        | 2.24%   |
| 19      | 46        | 1.98%   |
| 84      | 37        | 1.6%    |
| 11      | 27        | 1.16%   |
| 16      | 20        | 0.86%   |
| 32      | 19        | 0.82%   |
| 72      | 12        | 0.52%   |
| 20      | 11        | 0.47%   |
| 65      | 10        | 0.43%   |
| 25      | 10        | 0.43%   |
| 42      | 9         | 0.39%   |
| 54      | 8         | 0.34%   |
| 18      | 8         | 0.34%   |
| 35      | 7         | 0.3%    |
| 39      | 6         | 0.26%   |
| 48      | 5         | 0.22%   |
| 40      | 5         | 0.22%   |
| 37      | 5         | 0.22%   |
| 29      | 5         | 0.22%   |
| 10      | 5         | 0.22%   |
| 50      | 4         | 0.17%   |
| 49      | 4         | 0.17%   |
| 46      | 3         | 0.13%   |
| 33      | 3         | 0.13%   |
| 3       | 3         | 0.13%   |
| 55      | 2         | 0.09%   |
| 47      | 2         | 0.09%   |
| 26      | 2         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 728       | 32.13%  |
| 501-600        | 579       | 25.55%  |
| 201-300        | 249       | 10.99%  |
| 401-500        | 154       | 6.8%    |
| Unknown        | 145       | 6.4%    |
| 351-400        | 120       | 5.3%    |
| 601-700        | 85        | 3.75%   |
| 701-800        | 74        | 3.27%   |
| 1501-2000      | 51        | 2.25%   |
| 1001-1500      | 40        | 1.77%   |
| 801-900        | 22        | 0.97%   |
| 901-1000       | 12        | 0.53%   |
| 1-100          | 5         | 0.22%   |
| More than 2000 | 1         | 0.04%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1475      | 70.91%  |
| 16/10   | 310       | 14.9%   |
| Unknown | 132       | 6.35%   |
| 21/9    | 64        | 3.08%   |
| 5/4     | 49        | 2.36%   |
| 3/2     | 19        | 0.91%   |
| 4/3     | 15        | 0.72%   |
| 32/9    | 6         | 0.29%   |
| 6/5     | 5         | 0.24%   |
| 0.67    | 2         | 0.1%    |
| 3.40    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.45    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 408       | 17.9%   |
| 201-250        | 377       | 16.54%  |
| 81-90          | 319       | 14%     |
| 301-350        | 257       | 11.28%  |
| Unknown        | 145       | 6.36%   |
| 351-500        | 139       | 6.1%    |
| 71-80          | 129       | 5.66%   |
| 251-300        | 95        | 4.17%   |
| More than 1000 | 82        | 3.6%    |
| 151-200        | 69        | 3.03%   |
| 121-130        | 66        | 2.9%    |
| 61-70          | 59        | 2.59%   |
| 501-1000       | 37        | 1.62%   |
| 51-60          | 28        | 1.23%   |
| 111-120        | 22        | 0.97%   |
| 141-150        | 17        | 0.75%   |
| 131-140        | 13        | 0.57%   |
| 41-50          | 6         | 0.26%   |
| 91-100         | 6         | 0.26%   |
| 1-40           | 5         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 709       | 32.01%  |
| 121-160       | 572       | 25.82%  |
| 101-120       | 476       | 21.49%  |
| 161-240       | 176       | 7.95%   |
| Unknown       | 145       | 6.55%   |
| More than 240 | 83        | 3.75%   |
| 1-50          | 54        | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1574      | 74.35%  |
| 2     | 385       | 18.19%  |
| 0     | 106       | 5.01%   |
| 3     | 46        | 2.17%   |
| 4     | 6         | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1167      | 38.98%  |
| Realtek Semiconductor                  | 902       | 30.13%  |
| Qualcomm Atheros                       | 284       | 9.49%   |
| Broadcom                               | 179       | 5.98%   |
| MediaTek                               | 50        | 1.67%   |
| Broadcom Limited                       | 45        | 1.5%    |
| Marvell Technology Group               | 30        | 1%      |
| Ralink                                 | 22        | 0.73%   |
| ASIX Electronics                       | 21        | 0.7%    |
| Nvidia                                 | 18        | 0.6%    |
| Hewlett-Packard                        | 18        | 0.6%    |
| Lenovo                                 | 16        | 0.53%   |
| ASUSTek Computer                       | 16        | 0.53%   |
| TP-Link                                | 15        | 0.5%    |
| Microsoft                              | 15        | 0.5%    |
| Sierra Wireless                        | 14        | 0.47%   |
| Dell                                   | 14        | 0.47%   |
| D-Link System                          | 14        | 0.47%   |
| NetGear                                | 13        | 0.43%   |
| Ralink Technology                      | 12        | 0.4%    |
| D-Link                                 | 11        | 0.37%   |
| DisplayLink                            | 10        | 0.33%   |
| Huawei Technologies                    | 9         | 0.3%    |
| Ericsson Business Mobile Networks      | 8         | 0.27%   |
| Samsung Electronics                    | 6         | 0.2%    |
| Qualcomm Atheros Communications        | 6         | 0.2%    |
| Aquantia                               | 6         | 0.2%    |
| Qualcomm                               | 5         | 0.17%   |
| Fibocom                                | 5         | 0.17%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.1%    |
| Microchip Technology                   | 3         | 0.1%    |
| Linksys                                | 3         | 0.1%    |
| Belkin Components                      | 3         | 0.1%    |
| Arduino SA                             | 3         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 2         | 0.07%   |
| Xiaomi                                 | 2         | 0.07%   |
| Wacom                                  | 2         | 0.07%   |
| Texas Instruments                      | 2         | 0.07%   |
| Standard Microsystems                  | 2         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 633       | 17.6%   |
| Intel I211 Gigabit Network Connection                             | 103       | 2.86%   |
| Intel Wi-Fi 6 AX200                                               | 97        | 2.7%    |
| Intel Wireless 8265 / 8275                                        | 96        | 2.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 72        | 2%      |
| Intel Wireless 7260                                               | 69        | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69        | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 57        | 1.59%   |
| Intel Wireless 8260                                               | 53        | 1.47%   |
| Intel Ethernet Connection (2) I219-V                              | 51        | 1.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 50        | 1.39%   |
| Intel Wireless 7265                                               | 50        | 1.39%   |
| Intel Wi-Fi 6 AX201                                               | 48        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 40        | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 36        | 1%      |
| Intel Ethernet Connection I217-LM                                 | 36        | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 34        | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 33        | 0.92%   |
| Intel Ethernet Controller I225-V                                  | 33        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 30        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 30        | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 28        | 0.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 28        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 28        | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 28        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 0.7%    |
| Intel Wireless-AC 9260                                            | 24        | 0.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 24        | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 24        | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 23        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.64%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 23        | 0.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 22        | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 0.58%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 21        | 0.58%   |
| Intel Wireless 3160                                               | 20        | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 827       | 51.66%  |
| Qualcomm Atheros                  | 220       | 13.74%  |
| Realtek Semiconductor             | 194       | 12.12%  |
| Broadcom                          | 116       | 7.25%   |
| MediaTek                          | 49        | 3.06%   |
| Broadcom Limited                  | 27        | 1.69%   |
| Ralink                            | 22        | 1.37%   |
| ASUSTek Computer                  | 16        | 1%      |
| Sierra Wireless                   | 14        | 0.87%   |
| NetGear                           | 13        | 0.81%   |
| TP-Link                           | 12        | 0.75%   |
| Ralink Technology                 | 12        | 0.75%   |
| Microsoft                         | 10        | 0.62%   |
| D-Link System                     | 10        | 0.62%   |
| D-Link                            | 10        | 0.62%   |
| Dell                              | 8         | 0.5%    |
| Qualcomm Atheros Communications   | 6         | 0.37%   |
| Marvell Technology Group          | 5         | 0.31%   |
| Fibocom                           | 5         | 0.31%   |
| Hewlett-Packard                   | 4         | 0.25%   |
| Qualcomm                          | 3         | 0.19%   |
| Belkin Components                 | 3         | 0.19%   |
| Wacom                             | 2         | 0.12%   |
| Linksys                           | 2         | 0.12%   |
| Ericsson Business Mobile Networks | 2         | 0.12%   |
| Edimax Technology                 | 2         | 0.12%   |
| ZyXEL Communications              | 1         | 0.06%   |
| Wilocity                          | 1         | 0.06%   |
| Sitecom Europe                    | 1         | 0.06%   |
| Micro Star International          | 1         | 0.06%   |
| IMC Networks                      | 1         | 0.06%   |
| Fujitsu Siemens Computers         | 1         | 0.06%   |
| Chu Yuen Enterprise               | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 97        | 6.02%   |
| Intel Wireless 8265 / 8275                                     | 96        | 5.96%   |
| Intel Wireless 7260                                            | 69        | 4.28%   |
| Intel Wireless 8260                                            | 53        | 3.29%   |
| Intel Wireless 7265                                            | 50        | 3.1%    |
| Intel Wi-Fi 6 AX201                                            | 48        | 2.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 40        | 2.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 36        | 2.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 34        | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 33        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 30        | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 30        | 1.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 28        | 1.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 28        | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 1.55%   |
| Intel Wireless-AC 9260                                         | 24        | 1.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 24        | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 24        | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 23        | 1.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 22        | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 21        | 1.3%    |
| Intel Wireless 3160                                            | 20        | 1.24%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 20        | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 18        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 18        | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 17        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 17        | 1.06%   |
| Intel Wireless 3165                                            | 17        | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 16        | 0.99%   |
| Intel Centrino Advanced-N 6200                                 | 15        | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 15        | 0.93%   |
| Intel Centrino Advanced-N 6235                                 | 14        | 0.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 13        | 0.81%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 13        | 0.81%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 12        | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 12        | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 11        | 0.68%   |
| Sierra Wireless EM7455                                         | 10        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 822       | 43.65%  |
| Intel                                  | 705       | 37.44%  |
| Qualcomm Atheros                       | 97        | 5.15%   |
| Broadcom                               | 89        | 4.73%   |
| Marvell Technology Group               | 25        | 1.33%   |
| ASIX Electronics                       | 21        | 1.12%   |
| Broadcom Limited                       | 19        | 1.01%   |
| Nvidia                                 | 18        | 0.96%   |
| Lenovo                                 | 15        | 0.8%    |
| DisplayLink                            | 10        | 0.53%   |
| Huawei Technologies                    | 7         | 0.37%   |
| Aquantia                               | 6         | 0.32%   |
| Samsung Electronics                    | 5         | 0.27%   |
| Microsoft                              | 5         | 0.27%   |
| Hewlett-Packard                        | 5         | 0.27%   |
| D-Link System                          | 4         | 0.21%   |
| TP-Link                                | 3         | 0.16%   |
| Microchip Technology                   | 3         | 0.16%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.11%   |
| Xiaomi                                 | 2         | 0.11%   |
| Standard Microsystems                  | 2         | 0.11%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.11%   |
| Qualcomm                               | 2         | 0.11%   |
| JMicron Technology                     | 2         | 0.11%   |
| ICS Advent                             | 2         | 0.11%   |
| VIA Technologies                       | 1         | 0.05%   |
| Unknown                                | 1         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| Linksys                                | 1         | 0.05%   |
| Gemtek                                 | 1         | 0.05%   |
| D-Link                                 | 1         | 0.05%   |
| Apple                                  | 1         | 0.05%   |
| 3Com                                   | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 633       | 32.78%  |
| Intel I211 Gigabit Network Connection                             | 103       | 5.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 72        | 3.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69        | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 57        | 2.95%   |
| Intel Ethernet Connection (2) I219-V                              | 51        | 2.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 50        | 2.59%   |
| Intel Ethernet Connection I217-LM                                 | 36        | 1.86%   |
| Intel Ethernet Controller I225-V                                  | 33        | 1.71%   |
| Intel Ethernet Connection (7) I219-V                              | 28        | 1.45%   |
| Intel 82579V Gigabit Network Connection                           | 28        | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 1.24%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 1.19%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 1.19%   |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 1.09%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 1.04%   |
| Intel Ethernet Connection (6) I219-V                              | 20        | 1.04%   |
| Intel Ethernet Connection (2) I218-V                              | 20        | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 18        | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 17        | 0.88%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.83%   |
| Intel I210 Gigabit Network Connection                             | 15        | 0.78%   |
| Intel Ethernet Connection I219-V                                  | 15        | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 15        | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.73%   |
| Intel Ethernet Connection (13) I219-V                             | 12        | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.57%   |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                             | 8         | 0.41%   |
| Intel 82566MM Gigabit Network Connection                          | 8         | 0.41%   |
| DisplayLink Dell Universal Dock D6000                             | 8         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1783      | 53.32%  |
| WiFi     | 1507      | 45.07%  |
| Modem    | 42        | 1.26%   |
| Unknown  | 12        | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1122      | 52.28%  |
| Ethernet | 1022      | 47.62%  |
| Unknown  | 2         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1085      | 52.36%  |
| 1     | 873       | 42.13%  |
| 3     | 55        | 2.65%   |
| 0     | 40        | 1.93%   |
| 4     | 12        | 0.58%   |
| 5     | 5         | 0.24%   |
| 9     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1964      | 94.65%  |
| Yes  | 111       | 5.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 678       | 52.27%  |
| Realtek Semiconductor           | 91        | 7.02%   |
| Qualcomm Atheros Communications | 72        | 5.55%   |
| IMC Networks                    | 62        | 4.78%   |
| Apple                           | 62        | 4.78%   |
| Cambridge Silicon Radio         | 61        | 4.7%    |
| ASUSTek Computer                | 61        | 4.7%    |
| Broadcom                        | 54        | 4.16%   |
| Foxconn / Hon Hai               | 48        | 3.7%    |
| Lite-On Technology              | 34        | 2.62%   |
| Hewlett-Packard                 | 16        | 1.23%   |
| Dell                            | 16        | 1.23%   |
| Ralink                          | 7         | 0.54%   |
| MediaTek                        | 7         | 0.54%   |
| Toshiba                         | 5         | 0.39%   |
| Marvell Semiconductor           | 5         | 0.39%   |
| Realtek                         | 3         | 0.23%   |
| Ralink Technology               | 2         | 0.15%   |
| Micro Star International        | 2         | 0.15%   |
| HTC (High Tech Computer)        | 2         | 0.15%   |
| Chicony Electronics             | 2         | 0.15%   |
| USI                             | 1         | 0.08%   |
| Fujitsu                         | 1         | 0.08%   |
| Creative Technology             | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |
| Alps Electric                   | 1         | 0.08%   |
| Actions                         | 1         | 0.08%   |
| Unknown                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 288       | 22.12%  |
| Intel AX201 Bluetooth                               | 107       | 8.22%   |
| Intel AX200 Bluetooth                               | 93        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 75        | 5.76%   |
| Realtek Bluetooth Radio                             | 64        | 4.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 61        | 4.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 27        | 2.07%   |
| Apple Bluetooth Host Controller                     | 27        | 2.07%   |
| IMC Networks Bluetooth Radio                        | 26        | 2%      |
| Intel Wireless-AC 3168 Bluetooth                    | 23        | 1.77%   |
| Intel AX210 Bluetooth                               | 23        | 1.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 22        | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 1.69%   |
| Intel Bluetooth Device                              | 21        | 1.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 20        | 1.54%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 1.54%   |
| Apple Bluetooth USB Host Controller                 | 19        | 1.46%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 1.38%   |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 1.31%   |
| IMC Networks Wireless_Device                        | 14        | 1.08%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 1%      |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 1%      |
| IMC Networks Bluetooth Device                       | 12        | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 0.84%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 11        | 0.84%   |
| Lite-On Bluetooth Device                            | 10        | 0.77%   |
| ASUS ASUS USB-BT500                                 | 10        | 0.77%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.61%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 0.61%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.61%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.54%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.54%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 6         | 0.46%   |
| Broadcom HP Portable Bumble Bee                     | 6         | 0.46%   |
| ASUS Bluetooth Radio                                | 6         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1424      | 46.38%  |
| AMD                              | 635       | 20.68%  |
| Nvidia                           | 573       | 18.66%  |
| C-Media Electronics              | 55        | 1.79%   |
| Logitech                         | 37        | 1.21%   |
| Creative Labs                    | 21        | 0.68%   |
| SteelSeries ApS                  | 20        | 0.65%   |
| Kingston Technology              | 19        | 0.62%   |
| Realtek Semiconductor            | 15        | 0.49%   |
| Plantronics                      | 15        | 0.49%   |
| GN Netcom                        | 14        | 0.46%   |
| Creative Technology              | 14        | 0.46%   |
| Texas Instruments                | 13        | 0.42%   |
| Lenovo                           | 12        | 0.39%   |
| Focusrite-Novation               | 10        | 0.33%   |
| Corsair                          | 10        | 0.33%   |
| ASUSTek Computer                 | 10        | 0.33%   |
| Razer USA                        | 9         | 0.29%   |
| Micro Star International         | 8         | 0.26%   |
| SAVITECH                         | 7         | 0.23%   |
| RODE Microphones                 | 7         | 0.23%   |
| GYROCOM C&C                      | 6         | 0.2%    |
| Yamaha                           | 5         | 0.16%   |
| JMTek                            | 5         | 0.16%   |
| Blue Microphones                 | 5         | 0.16%   |
| Sennheiser Communications        | 4         | 0.13%   |
| Hewlett-Packard                  | 4         | 0.13%   |
| Apple                            | 4         | 0.13%   |
| Antlion Audio                    | 4         | 0.13%   |
| XMOS                             | 3         | 0.1%    |
| VIA Technologies                 | 3         | 0.1%    |
| Sony                             | 3         | 0.1%    |
| Silicon Integrated Systems [SiS] | 3         | 0.1%    |
| Scarlett                         | 3         | 0.1%    |
| Samsung Electronics              | 3         | 0.1%    |
| Samson Technologies              | 3         | 0.1%    |
| PreSonus Audio Electronics       | 3         | 0.1%    |
| Generalplus Technology           | 3         | 0.1%    |
| BEHRINGER International          | 3         | 0.1%    |
| Valve Software                   | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 173       | 4.78%   |
| Intel Sunrise Point-LP HD Audio                                            | 166       | 4.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 131       | 3.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 118       | 3.26%   |
| AMD Starship/Matisse HD Audio Controller                                   | 118       | 3.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 105       | 2.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 91        | 2.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 85        | 2.35%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 81        | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 70        | 1.93%   |
| Intel Haswell-ULT HD Audio Controller                                      | 63        | 1.74%   |
| Intel 8 Series HD Audio Controller                                         | 63        | 1.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 62        | 1.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 60        | 1.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 58        | 1.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 58        | 1.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 54        | 1.49%   |
| AMD FCH Azalia Controller                                                  | 52        | 1.44%   |
| Intel 200 Series PCH HD Audio                                              | 50        | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 50        | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 49        | 1.35%   |
| Intel Broadwell-U Audio Controller                                         | 49        | 1.35%   |
| Nvidia GP106 High Definition Audio Controller                              | 48        | 1.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 46        | 1.27%   |
| Nvidia GP104 High Definition Audio Controller                              | 44        | 1.21%   |
| Nvidia TU106 High Definition Audio Controller                              | 40        | 1.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 38        | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 36        | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                               | 30        | 0.83%   |
| Intel CM238 HD Audio Controller                                            | 30        | 0.83%   |
| Nvidia GM204 High Definition Audio Controller                              | 29        | 0.8%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 29        | 0.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 28        | 0.77%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 28        | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 27        | 0.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 27        | 0.75%   |
| AMD Navi 10 HDMI Audio                                                     | 27        | 0.75%   |
| Intel Comet Lake PCH cAVS                                                  | 26        | 0.72%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 26        | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                         | 25        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 274       | 22.31%  |
| SK hynix                     | 202       | 16.45%  |
| Corsair                      | 164       | 13.36%  |
| Kingston                     | 148       | 12.05%  |
| Micron Technology            | 138       | 11.24%  |
| Unknown                      | 96        | 7.82%   |
| Crucial                      | 67        | 5.46%   |
| G.Skill                      | 34        | 2.77%   |
| Ramaxel Technology           | 16        | 1.3%    |
| Elpida                       | 15        | 1.22%   |
| A-DATA Technology            | 14        | 1.14%   |
| Unknown (ABCD)               | 10        | 0.81%   |
| Nanya Technology             | 8         | 0.65%   |
| Unknown                      | 8         | 0.65%   |
| Patriot                      | 4         | 0.33%   |
| Team                         | 3         | 0.24%   |
| Transcend                    | 2         | 0.16%   |
| Qimonda                      | 2         | 0.16%   |
| GSkill                       | 2         | 0.16%   |
| GOODRAM                      | 2         | 0.16%   |
| G-Alantic                    | 2         | 0.16%   |
| Avant                        | 2         | 0.16%   |
| Unknown (AB)                 | 1         | 0.08%   |
| Unknown (836D)               | 1         | 0.08%   |
| Unifosa                      | 1         | 0.08%   |
| TEXTORM                      | 1         | 0.08%   |
| SHARETRONIC                  | 1         | 0.08%   |
| Patriot Memory (PDP Systems) | 1         | 0.08%   |
| Netlist                      | 1         | 0.08%   |
| Neo Forza                    | 1         | 0.08%   |
| Innodisk                     | 1         | 0.08%   |
| Hyundai lnc                  | 1         | 0.08%   |
| Hewlett-Packard              | 1         | 0.08%   |
| fef5                         | 1         | 0.08%   |
| ASint Technology             | 1         | 0.08%   |
| Apacer                       | 1         | 0.08%   |
| Ankowall                     | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 24        | 1.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 13        | 0.99%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 12        | 0.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 12        | 0.92%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 11        | 0.84%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s             | 11        | 0.84%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s            | 9         | 0.69%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                      | 8         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 8         | 0.61%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 8         | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 8         | 0.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s             | 8         | 0.61%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s               | 8         | 0.61%   |
| Unknown                                                           | 8         | 0.61%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s         | 7         | 0.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 7         | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 7         | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 7         | 0.53%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s          | 6         | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 6         | 0.46%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s            | 6         | 0.46%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s     | 6         | 0.46%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s             | 6         | 0.46%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s         | 6         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 5         | 0.38%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 5         | 0.38%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 5         | 0.38%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s  | 5         | 0.38%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s             | 5         | 0.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s             | 5         | 0.38%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s             | 5         | 0.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                 | 5         | 0.38%   |
| Corsair RAM CMK8GX4M2A2666C16 4GB DIMM DDR4 2747MT/s              | 5         | 0.38%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s             | 5         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                       | 4         | 0.31%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 4         | 0.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 0.31%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.31%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 4         | 0.31%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s           | 4         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 544       | 49.45%  |
| DDR3    | 338       | 30.73%  |
| LPDDR4  | 55        | 5%      |
| DDR2    | 39        | 3.55%   |
| LPDDR3  | 36        | 3.27%   |
| SDRAM   | 25        | 2.27%   |
| DDR5    | 23        | 2.09%   |
| Unknown | 19        | 1.73%   |
| DDR     | 9         | 0.82%   |
| LPDDR5  | 8         | 0.73%   |
| DRAM    | 4         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 585       | 53.28%  |
| DIMM         | 404       | 36.79%  |
| Row Of Chips | 90        | 8.2%    |
| Chip         | 11        | 1%      |
| Unknown      | 4         | 0.36%   |
| RIMM         | 3         | 0.27%   |
| FB-DIMM      | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 479       | 40.66%  |
| 4096    | 271       | 23.01%  |
| 16384   | 224       | 19.02%  |
| 2048    | 134       | 11.38%  |
| 32768   | 32        | 2.72%   |
| 1024    | 31        | 2.63%   |
| 512     | 6         | 0.51%   |
| Unknown | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 222       | 18.88%  |
| 3200    | 161       | 13.69%  |
| 2667    | 134       | 11.39%  |
| 2400    | 90        | 7.65%   |
| 2133    | 81        | 6.89%   |
| 3600    | 60        | 5.1%    |
| 1333    | 58        | 4.93%   |
| 4267    | 28        | 2.38%   |
| 1334    | 26        | 2.21%   |
| 667     | 26        | 2.21%   |
| 1867    | 24        | 2.04%   |
| Unknown | 21        | 1.79%   |
| 800     | 20        | 1.7%    |
| 4800    | 16        | 1.36%   |
| 1067    | 15        | 1.28%   |
| 3400    | 13        | 1.11%   |
| 3000    | 12        | 1.02%   |
| 3533    | 11        | 0.94%   |
| 1800    | 11        | 0.94%   |
| 6400    | 10        | 0.85%   |
| 4266    | 10        | 0.85%   |
| 1066    | 10        | 0.85%   |
| 3733    | 9         | 0.77%   |
| 3266    | 9         | 0.77%   |
| 2666    | 9         | 0.77%   |
| 3800    | 8         | 0.68%   |
| 4199    | 6         | 0.51%   |
| 2933    | 6         | 0.51%   |
| 1866    | 6         | 0.51%   |
| 3466    | 5         | 0.43%   |
| 2747    | 5         | 0.43%   |
| 3866    | 4         | 0.34%   |
| 8400    | 3         | 0.26%   |
| 6000    | 3         | 0.26%   |
| 2000    | 3         | 0.26%   |
| 49926   | 2         | 0.17%   |
| 5600    | 2         | 0.17%   |
| 3933    | 2         | 0.17%   |
| 3666    | 2         | 0.17%   |
| 3151    | 2         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 41.94%  |
| Brother Industries    | 6         | 19.35%  |
| Samsung Electronics   | 5         | 16.13%  |
| Canon                 | 3         | 9.68%   |
| Seiko Epson           | 2         | 6.45%   |
| Oki Data              | 1         | 3.23%   |
| Lexmark International | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 2         | 6.45%   |
| HP LaserJet 1020                     | 2         | 6.45%   |
| Seiko Epson XP-4100 Series           | 1         | 3.23%   |
| Seiko Epson Printer                  | 1         | 3.23%   |
| Samsung SCX-3200 Series              | 1         | 3.23%   |
| Samsung M2070 Series                 | 1         | 3.23%   |
| Samsung Color Laser Printer          | 1         | 3.23%   |
| Oki Data USB Device                  | 1         | 3.23%   |
| Lexmark International MX317dn        | 1         | 3.23%   |
| HP OfficeJet Pro 8730                | 1         | 3.23%   |
| HP OfficeJet G55                     | 1         | 3.23%   |
| HP LaserJet Professional P 1102w     | 1         | 3.23%   |
| HP LaserJet P2035                    | 1         | 3.23%   |
| HP LaserJet 1320                     | 1         | 3.23%   |
| HP ENVY 4520 series                  | 1         | 3.23%   |
| HP DeskJet 5650c                     | 1         | 3.23%   |
| HP Deskjet 3050 J610 series          | 1         | 3.23%   |
| HP DeskJet 2700 series               | 1         | 3.23%   |
| HP DeskJet 2130 series               | 1         | 3.23%   |
| HP Color LaserJet CP1215             | 1         | 3.23%   |
| Canon LBP7010C/7018C                 | 1         | 3.23%   |
| Canon LBP6200                        | 1         | 3.23%   |
| Canon CanoScan LiDE 300              | 1         | 3.23%   |
| Brother QL-500 label printer         | 1         | 3.23%   |
| Brother HL-5150D series              | 1         | 3.23%   |
| Brother HL-2270DW Laser Printer      | 1         | 3.23%   |
| Brother HL-2130 series               | 1         | 3.23%   |
| Brother DCP-7055W                    | 1         | 3.23%   |
| Brother DCP-7040                     | 1         | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 8         | 80%     |
| Seiko Epson     | 1         | 10%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                     | 2         | 20%     |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 10%     |
| HP ScanJet 2200c                            | 1         | 10%     |
| Canon CanoScan LiDE 700F                    | 1         | 10%     |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |
| Canon CanoScan LiDE 120                     | 1         | 10%     |
| Canon CanoScan LiDE 110                     | 1         | 10%     |
| Canon CanoScan 4400F                        | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 262       | 22.64%  |
| Microdia                               | 107       | 9.25%   |
| IMC Networks                           | 96        | 8.3%    |
| Logitech                               | 92        | 7.95%   |
| Realtek Semiconductor                  | 72        | 6.22%   |
| Bison Electronics                      | 61        | 5.27%   |
| Sunplus Innovation Technology          | 50        | 4.32%   |
| Apple                                  | 50        | 4.32%   |
| Cheng Uei Precision Industry (Foxlink) | 45        | 3.89%   |
| Quanta                                 | 43        | 3.72%   |
| Lite-On Technology                     | 37        | 3.2%    |
| Acer                                   | 34        | 2.94%   |
| Syntek                                 | 31        | 2.68%   |
| Suyin                                  | 28        | 2.42%   |
| Luxvisions Innotech Limited            | 15        | 1.3%    |
| Samsung Electronics                    | 14        | 1.21%   |
| Microsoft                              | 12        | 1.04%   |
| Ricoh                                  | 10        | 0.86%   |
| Lenovo                                 | 10        | 0.86%   |
| Alcor Micro                            | 9         | 0.78%   |
| Silicon Motion                         | 7         | 0.61%   |
| ALi                                    | 6         | 0.52%   |
| Z-Star Microelectronics                | 5         | 0.43%   |
| Creative Technology                    | 5         | 0.43%   |
| Trust                                  | 4         | 0.35%   |
| Primax Electronics                     | 4         | 0.35%   |
| Sonix Technology                       | 3         | 0.26%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.26%   |
| Generalplus Technology                 | 3         | 0.26%   |
| DigiTech                               | 3         | 0.26%   |
| ARC International                      | 3         | 0.26%   |
| SunplusIT                              | 2         | 0.17%   |
| Sunplus Technology                     | 2         | 0.17%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.17%   |
| LG Electronics                         | 2         | 0.17%   |
| Importek                               | 2         | 0.17%   |
| Valve Software                         | 1         | 0.09%   |
| Tobii Technology AB                    | 1         | 0.09%   |
| Sony                                   | 1         | 0.09%   |
| Razer USA                              | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 64        | 5.46%   |
| Microdia Integrated_Webcam_HD                                            | 48        | 4.1%    |
| IMC Networks USB2.0 HD UVC WebCam                                        | 38        | 3.24%   |
| IMC Networks Integrated Camera                                           | 30        | 2.56%   |
| Realtek Integrated_Webcam_HD                                             | 25        | 2.13%   |
| Syntek Integrated Camera                                                 | 23        | 1.96%   |
| Chicony HD WebCam                                                        | 21        | 1.79%   |
| Chicony HP HD Camera                                                     | 20        | 1.71%   |
| Logitech HD Pro Webcam C920                                              | 17        | 1.45%   |
| Logitech Webcam C270                                                     | 16        | 1.37%   |
| Acer Integrated Camera                                                   | 15        | 1.28%   |
| Sunplus HD WebCam                                                        | 14        | 1.19%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 14        | 1.19%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                          | 14        | 1.19%   |
| Logitech C922 Pro Stream Webcam                                          | 13        | 1.11%   |
| Lite-On HP HD Camera                                                     | 13        | 1.11%   |
| Bison Integrated Camera                                                  | 13        | 1.11%   |
| Quanta HP HD Camera                                                      | 12        | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 12        | 1.02%   |
| Bison SunplusIT Integrated Camera                                        | 12        | 1.02%   |
| Apple Built-in iSight                                                    | 12        | 1.02%   |
| Sunplus Integrated_Webcam_HD                                             | 11        | 0.94%   |
| Apple FaceTime HD Camera (Built-in)                                      | 11        | 0.94%   |
| Lite-On Integrated Camera                                                | 10        | 0.85%   |
| Bison Lenovo EasyCamera                                                  | 10        | 0.85%   |
| Lite-On HP HD Webcam                                                     | 9         | 0.77%   |
| Chicony HP HD Webcam [Fixed]                                             | 9         | 0.77%   |
| Chicony HP HD Webcam                                                     | 9         | 0.77%   |
| Apple FaceTime HD Camera                                                 | 9         | 0.77%   |
| Quanta HD User Facing                                                    | 8         | 0.68%   |
| Microdia USB 2.0 Camera                                                  | 8         | 0.68%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 8         | 0.68%   |
| Chicony HP Wide Vision HD Camera                                         | 8         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 8         | 0.68%   |
| Syntek Lenovo EasyCamera                                                 | 7         | 0.6%    |
| Suyin HP Truevision HD                                                   | 7         | 0.6%    |
| Chicony USB2.0 HD UVC WebCam                                             | 7         | 0.6%    |
| Chicony USB2.0 Camera                                                    | 7         | 0.6%    |
| Chicony Integrated HP HD Webcam                                          | 7         | 0.6%    |
| Chicony HP Truevision HD                                                 | 7         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 126       | 43.75%  |
| Synaptics                  | 87        | 30.21%  |
| Shenzhen Goodix Technology | 27        | 9.38%   |
| Elan Microelectronics      | 13        | 4.51%   |
| Upek                       | 11        | 3.82%   |
| AuthenTec                  | 11        | 3.82%   |
| LighTuning Technology      | 7         | 2.43%   |
| STMicroelectronics         | 6         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 14.58%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 5.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 16        | 5.56%   |
| Shenzhen Goodix FingerPrint                                                | 13        | 4.51%   |
| Validity Sensors VFS491                                                    | 12        | 4.17%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 3.82%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 3.47%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 3.47%   |
| Synaptics WBDI                                                             | 9         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.78%   |
| Elan ELAN:Fingerprint                                                      | 8         | 2.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.43%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.08%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.74%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.74%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.74%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.74%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 1.74%   |
| AuthenTec AES2810                                                          | 5         | 1.74%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.74%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.39%   |
| Synaptics UWP WBDI                                                         | 4         | 1.39%   |
| Synaptics  WBDI                                                            | 4         | 1.39%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.39%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 1.04%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.04%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 3         | 1.04%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.04%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.69%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.69%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.69%   |
| Unknown                                                                    | 2         | 0.69%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.35%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 65        | 42.76%  |
| Broadcom                          | 58        | 38.16%  |
| O2 Micro                          | 11        | 7.24%   |
| Lenovo                            | 6         | 3.95%   |
| Upek                              | 5         | 3.29%   |
| Gemalto (was Gemplus)             | 2         | 1.32%   |
| Yubico.com                        | 1         | 0.66%   |
| VASCO Data Security International | 1         | 0.66%   |
| Hewlett-Packard                   | 1         | 0.66%   |
| Chicony Electronics               | 1         | 0.66%   |
| Cherry                            | 1         | 0.66%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 62        | 40.79%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 11.18%  |
| Broadcom 58200                                                               | 16        | 10.53%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 7.89%   |
| Broadcom 5880                                                                | 12        | 7.89%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 5.92%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3.95%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 3.29%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.97%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.32%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.32%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.66%   |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.66%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.66%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.66%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.66%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.66%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1390      | 65.85%  |
| 1     | 550       | 26.05%  |
| 2     | 146       | 6.92%   |
| 3     | 17        | 0.81%   |
| 4     | 6         | 0.28%   |
| 7     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 286       | 31.92%  |
| Graphics card            | 157       | 17.52%  |
| Chipcard                 | 136       | 15.18%  |
| Net/wireless             | 84        | 9.38%   |
| Multimedia controller    | 56        | 6.25%   |
| Communication controller | 41        | 4.58%   |
| Camera                   | 30        | 3.35%   |
| Unassigned class         | 27        | 3.01%   |
| Bluetooth                | 22        | 2.46%   |
| Sound                    | 17        | 1.9%    |
| Card reader              | 13        | 1.45%   |
| Net/ethernet             | 9         | 1%      |
| Storage                  | 4         | 0.45%   |
| Storage/ata              | 2         | 0.22%   |
| Network                  | 2         | 0.22%   |
| Modem                    | 2         | 0.22%   |
| Flash memory             | 2         | 0.22%   |
| Firewire controller      | 2         | 0.22%   |
| Storage/raid             | 1         | 0.11%   |
| Storage/nvme             | 1         | 0.11%   |
| Storage/ide              | 1         | 0.11%   |
| Dvb card                 | 1         | 0.11%   |

