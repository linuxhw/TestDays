Linux in Canada - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Canada/Desktop/README.md) and [notebooks](/Location/Canada/Notebook/README.md).

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

Total: 9195

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| BESSTAR Te... | UM700                       | Desktop     | [d635105967](https://linux-hardware.org/?probe=d635105967) | Sep 07, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Matsushita... | CF-74JCJBDAM                | Notebook    | [0cc1e4014d](https://linux-hardware.org/?probe=0cc1e4014d) | Sep 07, 2023 |
| Google        | Blooguard                   | Notebook    | [c9dec98f0f](https://linux-hardware.org/?probe=c9dec98f0f) | Sep 07, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [32c21f0b73](https://linux-hardware.org/?probe=32c21f0b73) | Sep 07, 2023 |
| Dell          | 0R96K1 A00                  | Mini pc     | [3498c7ff1c](https://linux-hardware.org/?probe=3498c7ff1c) | Sep 07, 2023 |
| Dell          | 0HMX8D A01                  | Desktop     | [48fa151690](https://linux-hardware.org/?probe=48fa151690) | Sep 06, 2023 |
| Intel         | DN2800MT AAG23738-803       | Desktop     | [8bdf13908a](https://linux-hardware.org/?probe=8bdf13908a) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [b5f142ae13](https://linux-hardware.org/?probe=b5f142ae13) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| Unknown       | HX90                        | Desktop     | [928ebd5aa7](https://linux-hardware.org/?probe=928ebd5aa7) | Sep 06, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [17702812ba](https://linux-hardware.org/?probe=17702812ba) | Sep 06, 2023 |
| Alienware     | 0446JC A01                  | Desktop     | [d0c3088707](https://linux-hardware.org/?probe=d0c3088707) | Sep 06, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [7b717719f5](https://linux-hardware.org/?probe=7b717719f5) | Sep 05, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [5728a3a48b](https://linux-hardware.org/?probe=5728a3a48b) | Sep 05, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [fdecc11aba](https://linux-hardware.org/?probe=fdecc11aba) | Sep 05, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [5b5728ae8d](https://linux-hardware.org/?probe=5b5728ae8d) | Sep 05, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2d6aa7667d](https://linux-hardware.org/?probe=2d6aa7667d) | Sep 05, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [97e43e20d7](https://linux-hardware.org/?probe=97e43e20d7) | Sep 05, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [0b87bf5b4b](https://linux-hardware.org/?probe=0b87bf5b4b) | Sep 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [5738356b52](https://linux-hardware.org/?probe=5738356b52) | Sep 05, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [46627e6392](https://linux-hardware.org/?probe=46627e6392) | Sep 04, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [18d9c74d60](https://linux-hardware.org/?probe=18d9c74d60) | Sep 04, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [c4334a53b6](https://linux-hardware.org/?probe=c4334a53b6) | Sep 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [2a53f8dc55](https://linux-hardware.org/?probe=2a53f8dc55) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d99ec42689](https://linux-hardware.org/?probe=d99ec42689) | Sep 04, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [2ba34b459a](https://linux-hardware.org/?probe=2ba34b459a) | Sep 04, 2023 |
| Sony          | VPCEB27FX                   | Notebook    | [268d3a14a7](https://linux-hardware.org/?probe=268d3a14a7) | Sep 04, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [06571c70a0](https://linux-hardware.org/?probe=06571c70a0) | Sep 04, 2023 |
| Lenovo        | ThinkCentre M58p 7484AEF    | Desktop     | [ccffd7e998](https://linux-hardware.org/?probe=ccffd7e998) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [518f9f381b](https://linux-hardware.org/?probe=518f9f381b) | Sep 04, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [91bc08d933](https://linux-hardware.org/?probe=91bc08d933) | Sep 03, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | Notebook    | [20be702d65](https://linux-hardware.org/?probe=20be702d65) | Sep 03, 2023 |
| HP            | 1825                        | Desktop     | [38d038d2ad](https://linux-hardware.org/?probe=38d038d2ad) | Sep 03, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [8ed88aa6f1](https://linux-hardware.org/?probe=8ed88aa6f1) | Sep 03, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [3e995d059e](https://linux-hardware.org/?probe=3e995d059e) | Sep 03, 2023 |
| Google        | Droid                       | Notebook    | [da26431a82](https://linux-hardware.org/?probe=da26431a82) | Sep 03, 2023 |
| Google        | Droid                       | Notebook    | [278861e9e8](https://linux-hardware.org/?probe=278861e9e8) | Sep 03, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2f09a79291](https://linux-hardware.org/?probe=2f09a79291) | Sep 03, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [d6b74ca876](https://linux-hardware.org/?probe=d6b74ca876) | Sep 03, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [9c71da2165](https://linux-hardware.org/?probe=9c71da2165) | Sep 03, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [e9faf4759d](https://linux-hardware.org/?probe=e9faf4759d) | Sep 03, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [eaac06d18a](https://linux-hardware.org/?probe=eaac06d18a) | Sep 03, 2023 |
| Intel         | DQ77KB AAG40294-401         | Desktop     | [656df7cddd](https://linux-hardware.org/?probe=656df7cddd) | Sep 02, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [adacf1a54a](https://linux-hardware.org/?probe=adacf1a54a) | Sep 02, 2023 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [1283f01588](https://linux-hardware.org/?probe=1283f01588) | Sep 02, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [d25c5d75c1](https://linux-hardware.org/?probe=d25c5d75c1) | Sep 02, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [0f1a250c7f](https://linux-hardware.org/?probe=0f1a250c7f) | Sep 02, 2023 |
| Dell          | Precision 5540              | Notebook    | [3d800b12e0](https://linux-hardware.org/?probe=3d800b12e0) | Sep 02, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [affa07b412](https://linux-hardware.org/?probe=affa07b412) | Sep 02, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [9f8e38af3e](https://linux-hardware.org/?probe=9f8e38af3e) | Sep 02, 2023 |
| Lenovo        | ThinkPad W510 438923U       | Notebook    | [b0648eccac](https://linux-hardware.org/?probe=b0648eccac) | Sep 02, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [8194030163](https://linux-hardware.org/?probe=8194030163) | Sep 02, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [a00c4f0a62](https://linux-hardware.org/?probe=a00c4f0a62) | Sep 02, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [28fc3470c8](https://linux-hardware.org/?probe=28fc3470c8) | Sep 01, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [04f5152e0c](https://linux-hardware.org/?probe=04f5152e0c) | Sep 01, 2023 |
| MOTION        | NVX00                       | Notebook    | [8e26121033](https://linux-hardware.org/?probe=8e26121033) | Aug 31, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [5b79d93d0a](https://linux-hardware.org/?probe=5b79d93d0a) | Aug 31, 2023 |
| Inventec      | 0PY33N A01                  | Mini pc     | [453f0672c9](https://linux-hardware.org/?probe=453f0672c9) | Aug 31, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [f5aaee7de3](https://linux-hardware.org/?probe=f5aaee7de3) | Aug 31, 2023 |
| MSI           | MS-7E06                     | Notebook    | [afd9e6ccb2](https://linux-hardware.org/?probe=afd9e6ccb2) | Aug 30, 2023 |
| HP            | 3647h                       | Desktop     | [50ac4e01a4](https://linux-hardware.org/?probe=50ac4e01a4) | Aug 30, 2023 |
| Dell          | Latitude 3510               | Notebook    | [220b298103](https://linux-hardware.org/?probe=220b298103) | Aug 30, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [8ba058add5](https://linux-hardware.org/?probe=8ba058add5) | Aug 30, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [071785ab97](https://linux-hardware.org/?probe=071785ab97) | Aug 30, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [9374424bbd](https://linux-hardware.org/?probe=9374424bbd) | Aug 30, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [958ecd81e5](https://linux-hardware.org/?probe=958ecd81e5) | Aug 30, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2e3c70287a](https://linux-hardware.org/?probe=2e3c70287a) | Aug 30, 2023 |
| ASRock        | Z490M Pro4                  | Desktop     | [e07d4a9c90](https://linux-hardware.org/?probe=e07d4a9c90) | Aug 30, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [36cc5803b3](https://linux-hardware.org/?probe=36cc5803b3) | Aug 29, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [a41a08d4ae](https://linux-hardware.org/?probe=a41a08d4ae) | Aug 29, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [62ff88eaf7](https://linux-hardware.org/?probe=62ff88eaf7) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [b5ee83c5af](https://linux-hardware.org/?probe=b5ee83c5af) | Aug 29, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [9bbb56c640](https://linux-hardware.org/?probe=9bbb56c640) | Aug 29, 2023 |
| System76      | Galago Pro                  | Notebook    | [31330746e6](https://linux-hardware.org/?probe=31330746e6) | Aug 29, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [ebcf95d8ae](https://linux-hardware.org/?probe=ebcf95d8ae) | Aug 28, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [ef8ecfcb2e](https://linux-hardware.org/?probe=ef8ecfcb2e) | Aug 28, 2023 |
| Acer          | Aspire TC-330               | Desktop     | [d8182593c2](https://linux-hardware.org/?probe=d8182593c2) | Aug 28, 2023 |
| Acer          | Aspire M3470                | Desktop     | [60d18d6d6e](https://linux-hardware.org/?probe=60d18d6d6e) | Aug 28, 2023 |
| Toshiba       | Satellite Pro C70-C         | Notebook    | [eb9fbb104c](https://linux-hardware.org/?probe=eb9fbb104c) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [4bff36d914](https://linux-hardware.org/?probe=4bff36d914) | Aug 28, 2023 |
| MSI           | B85M-G43                    | Desktop     | [96fd52d530](https://linux-hardware.org/?probe=96fd52d530) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [e165507af8](https://linux-hardware.org/?probe=e165507af8) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [329d960437](https://linux-hardware.org/?probe=329d960437) | Aug 27, 2023 |
| Acer          | Aspire M3470                | Desktop     | [7e6d230bf5](https://linux-hardware.org/?probe=7e6d230bf5) | Aug 27, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [20eda7fab5](https://linux-hardware.org/?probe=20eda7fab5) | Aug 26, 2023 |
| Lenovo        | ThinkPad T420 4236AK9       | Notebook    | [46a647db9b](https://linux-hardware.org/?probe=46a647db9b) | Aug 26, 2023 |
| Dell          | Precision M4600             | Notebook    | [fcc3763c08](https://linux-hardware.org/?probe=fcc3763c08) | Aug 26, 2023 |
| Lenovo        | ThinkPad T410 25222AU       | Notebook    | [fdc78cf5a0](https://linux-hardware.org/?probe=fdc78cf5a0) | Aug 26, 2023 |
| HP            | Laptop 17-ca2xxx            | Notebook    | [f6d894d339](https://linux-hardware.org/?probe=f6d894d339) | Aug 26, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [f09b86405b](https://linux-hardware.org/?probe=f09b86405b) | Aug 26, 2023 |
| Unknown       | MediaTek kodama sku288      | Soc         | [7c4afe8e55](https://linux-hardware.org/?probe=7c4afe8e55) | Aug 26, 2023 |
| Unknown       | MediaTek kodama sku288      | Soc         | [1b7e6141b6](https://linux-hardware.org/?probe=1b7e6141b6) | Aug 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [3c528e98c6](https://linux-hardware.org/?probe=3c528e98c6) | Aug 26, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [eab204cfc9](https://linux-hardware.org/?probe=eab204cfc9) | Aug 26, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [03740cd24c](https://linux-hardware.org/?probe=03740cd24c) | Aug 25, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [51d4eefbc9](https://linux-hardware.org/?probe=51d4eefbc9) | Aug 25, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [cee65701f2](https://linux-hardware.org/?probe=cee65701f2) | Aug 25, 2023 |
| Dell          | Inspiron 5585               | Notebook    | [49a9e7dbf0](https://linux-hardware.org/?probe=49a9e7dbf0) | Aug 25, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [a36ead7d8d](https://linux-hardware.org/?probe=a36ead7d8d) | Aug 25, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [7d896ad750](https://linux-hardware.org/?probe=7d896ad750) | Aug 24, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [4d01543131](https://linux-hardware.org/?probe=4d01543131) | Aug 24, 2023 |
| System76      | Gazelle                     | Notebook    | [ee67365e0c](https://linux-hardware.org/?probe=ee67365e0c) | Aug 24, 2023 |
| Dell          | Latitude 5510               | Notebook    | [d0b9ab746d](https://linux-hardware.org/?probe=d0b9ab746d) | Aug 24, 2023 |
| Lenovo        | ThinkPad T450s 20BWS2M30... | Notebook    | [052c7eaa90](https://linux-hardware.org/?probe=052c7eaa90) | Aug 24, 2023 |
| ASUSTek       | Z9NA-D6                     | Server      | [4e4302c5f0](https://linux-hardware.org/?probe=4e4302c5f0) | Aug 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [19433fe76f](https://linux-hardware.org/?probe=19433fe76f) | Aug 24, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [2431197665](https://linux-hardware.org/?probe=2431197665) | Aug 24, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582HM_... | Notebook    | [2281d96afb](https://linux-hardware.org/?probe=2281d96afb) | Aug 24, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [bca12d1c12](https://linux-hardware.org/?probe=bca12d1c12) | Aug 24, 2023 |
| HP            | 1589                        | Desktop     | [982f4f1442](https://linux-hardware.org/?probe=982f4f1442) | Aug 24, 2023 |
| HP            | 1589                        | Desktop     | [cd1492c33d](https://linux-hardware.org/?probe=cd1492c33d) | Aug 24, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [8b76616574](https://linux-hardware.org/?probe=8b76616574) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [9a98c147d4](https://linux-hardware.org/?probe=9a98c147d4) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3723979edb](https://linux-hardware.org/?probe=3723979edb) | Aug 24, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [967160a534](https://linux-hardware.org/?probe=967160a534) | Aug 24, 2023 |
| Xplore        | iX104C6                     | Notebook    | [5d8ea1a454](https://linux-hardware.org/?probe=5d8ea1a454) | Aug 24, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [816f3ce721](https://linux-hardware.org/?probe=816f3ce721) | Aug 24, 2023 |
| HP            | EliteBook 8530w             | Notebook    | [3ee1fe77ce](https://linux-hardware.org/?probe=3ee1fe77ce) | Aug 23, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [840f045f31](https://linux-hardware.org/?probe=840f045f31) | Aug 23, 2023 |
| MSI           | GP72 6QF                    | Notebook    | [3afc91a639](https://linux-hardware.org/?probe=3afc91a639) | Aug 23, 2023 |
| HP            | Presario V2000 (ES307UA#... | Notebook    | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d0695420dd](https://linux-hardware.org/?probe=d0695420dd) | Aug 23, 2023 |
| HP            | 18E4                        | Desktop     | [0235c76e04](https://linux-hardware.org/?probe=0235c76e04) | Aug 23, 2023 |
| ASUSTek       | G751JM                      | Notebook    | [7cdb0c52e4](https://linux-hardware.org/?probe=7cdb0c52e4) | Aug 23, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [3bdb30f543](https://linux-hardware.org/?probe=3bdb30f543) | Aug 22, 2023 |
| Lenovo        | H415                        | Desktop     | [e6277f1ab8](https://linux-hardware.org/?probe=e6277f1ab8) | Aug 22, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [0bba785aee](https://linux-hardware.org/?probe=0bba785aee) | Aug 21, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [bed7c98349](https://linux-hardware.org/?probe=bed7c98349) | Aug 21, 2023 |
| Dell          | Latitude 5510               | Notebook    | [e5d8770a77](https://linux-hardware.org/?probe=e5d8770a77) | Aug 21, 2023 |
| Lenovo        | ThinkPad X220 42902WU       | Notebook    | [9fd887dc27](https://linux-hardware.org/?probe=9fd887dc27) | Aug 21, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [da3f4808a1](https://linux-hardware.org/?probe=da3f4808a1) | Aug 20, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [c6f278a589](https://linux-hardware.org/?probe=c6f278a589) | Aug 20, 2023 |
| ASUSTek       | M51BC                       | Desktop     | [4a81412fdd](https://linux-hardware.org/?probe=4a81412fdd) | Aug 20, 2023 |
| HP            | 3032h                       | Desktop     | [f3292df409](https://linux-hardware.org/?probe=f3292df409) | Aug 20, 2023 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [04df52e837](https://linux-hardware.org/?probe=04df52e837) | Aug 20, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [ed71bba366](https://linux-hardware.org/?probe=ed71bba366) | Aug 19, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [030cbe1086](https://linux-hardware.org/?probe=030cbe1086) | Aug 19, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [f06dbc1b8c](https://linux-hardware.org/?probe=f06dbc1b8c) | Aug 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8e7844a79d](https://linux-hardware.org/?probe=8e7844a79d) | Aug 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [d109b04177](https://linux-hardware.org/?probe=d109b04177) | Aug 19, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [3f5b46c0f1](https://linux-hardware.org/?probe=3f5b46c0f1) | Aug 19, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [0657120653](https://linux-hardware.org/?probe=0657120653) | Aug 19, 2023 |
| Dell          | 0PU052                      | Desktop     | [2b5816a194](https://linux-hardware.org/?probe=2b5816a194) | Aug 19, 2023 |
| Dell          | 0HT36J A01                  | All in one  | [670a695599](https://linux-hardware.org/?probe=670a695599) | Aug 18, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [93530d7cb1](https://linux-hardware.org/?probe=93530d7cb1) | Aug 18, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8bb2d02e4d](https://linux-hardware.org/?probe=8bb2d02e4d) | Aug 18, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8958908392](https://linux-hardware.org/?probe=8958908392) | Aug 17, 2023 |
| Panasonic     | CF-31AQAAA1M                | Notebook    | [64416dbba5](https://linux-hardware.org/?probe=64416dbba5) | Aug 17, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [31447ef238](https://linux-hardware.org/?probe=31447ef238) | Aug 17, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [8c57c50f82](https://linux-hardware.org/?probe=8c57c50f82) | Aug 17, 2023 |
| Dell          | Precision 5540              | Notebook    | [a0a36884a0](https://linux-hardware.org/?probe=a0a36884a0) | Aug 17, 2023 |
| Dell          | Inspiron 1200               | Notebook    | [2340dcab47](https://linux-hardware.org/?probe=2340dcab47) | Aug 17, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [0a48b003bb](https://linux-hardware.org/?probe=0a48b003bb) | Aug 17, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8c850ed196](https://linux-hardware.org/?probe=8c850ed196) | Aug 17, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [59385e7c8b](https://linux-hardware.org/?probe=59385e7c8b) | Aug 17, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [4337d3d1e2](https://linux-hardware.org/?probe=4337d3d1e2) | Aug 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7c1a42d442](https://linux-hardware.org/?probe=7c1a42d442) | Aug 17, 2023 |
| HP            | 1496                        | Desktop     | [19743e6f33](https://linux-hardware.org/?probe=19743e6f33) | Aug 17, 2023 |
| Dell          | XPS 9320                    | Notebook    | [cb112d9f03](https://linux-hardware.org/?probe=cb112d9f03) | Aug 17, 2023 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [0daae7dcb4](https://linux-hardware.org/?probe=0daae7dcb4) | Aug 16, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [6aa6913c91](https://linux-hardware.org/?probe=6aa6913c91) | Aug 16, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 81BL     | Notebook    | [a69ad2f7b8](https://linux-hardware.org/?probe=a69ad2f7b8) | Aug 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [2ac8f6838a](https://linux-hardware.org/?probe=2ac8f6838a) | Aug 15, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [65f7a020fe](https://linux-hardware.org/?probe=65f7a020fe) | Aug 14, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [69b51e3f5a](https://linux-hardware.org/?probe=69b51e3f5a) | Aug 14, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [0e51f02009](https://linux-hardware.org/?probe=0e51f02009) | Aug 14, 2023 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [a8f732a826](https://linux-hardware.org/?probe=a8f732a826) | Aug 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [24b85b3417](https://linux-hardware.org/?probe=24b85b3417) | Aug 14, 2023 |
| HP            | 18E4                        | Desktop     | [4fd89c22ae](https://linux-hardware.org/?probe=4fd89c22ae) | Aug 14, 2023 |
| Google        | Blooglet                    | Notebook    | [b9967e65c2](https://linux-hardware.org/?probe=b9967e65c2) | Aug 14, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [b310a70636](https://linux-hardware.org/?probe=b310a70636) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | Notebook    | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| MSI           | PRO Z790-A WIFI DDR4        | Desktop     | [ccce0b0c19](https://linux-hardware.org/?probe=ccce0b0c19) | Aug 13, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d760e3f4c4](https://linux-hardware.org/?probe=d760e3f4c4) | Aug 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [4eeea4cc95](https://linux-hardware.org/?probe=4eeea4cc95) | Aug 13, 2023 |
| HP            | 3646h                       | Desktop     | [b3c30163f9](https://linux-hardware.org/?probe=b3c30163f9) | Aug 13, 2023 |
| HP            | 3646h                       | Desktop     | [180d25235f](https://linux-hardware.org/?probe=180d25235f) | Aug 13, 2023 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [0ea140ff49](https://linux-hardware.org/?probe=0ea140ff49) | Aug 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [21abd7288e](https://linux-hardware.org/?probe=21abd7288e) | Aug 12, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [8321dcc5ea](https://linux-hardware.org/?probe=8321dcc5ea) | Aug 12, 2023 |
| Dell          | 0FDT3J A01                  | Server      | [fce762afa4](https://linux-hardware.org/?probe=fce762afa4) | Aug 12, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4f6d84a4dd](https://linux-hardware.org/?probe=4f6d84a4dd) | Aug 12, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [2b46218f49](https://linux-hardware.org/?probe=2b46218f49) | Aug 11, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [77714a2920](https://linux-hardware.org/?probe=77714a2920) | Aug 11, 2023 |
| HP            | Notebook                    | Notebook    | [de8a0230c4](https://linux-hardware.org/?probe=de8a0230c4) | Aug 11, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [95d93fda2c](https://linux-hardware.org/?probe=95d93fda2c) | Aug 11, 2023 |
| Dell          | 0KV3RP A00                  | Desktop     | [47c45a45e5](https://linux-hardware.org/?probe=47c45a45e5) | Aug 11, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [0b5cf409d8](https://linux-hardware.org/?probe=0b5cf409d8) | Aug 11, 2023 |
| AZW           | Green G4 10                 | Desktop     | [a574280172](https://linux-hardware.org/?probe=a574280172) | Aug 11, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [0384e8a950](https://linux-hardware.org/?probe=0384e8a950) | Aug 11, 2023 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [a88d7e81e5](https://linux-hardware.org/?probe=a88d7e81e5) | Aug 11, 2023 |
| Google        | Bobba360                    | Notebook    | [128700115a](https://linux-hardware.org/?probe=128700115a) | Aug 10, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [f542bb8447](https://linux-hardware.org/?probe=f542bb8447) | Aug 10, 2023 |
| Dell          | Latitude 3540               | Notebook    | [496e3ab340](https://linux-hardware.org/?probe=496e3ab340) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [6bf6a38fba](https://linux-hardware.org/?probe=6bf6a38fba) | Aug 10, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [63f0153cfe](https://linux-hardware.org/?probe=63f0153cfe) | Aug 10, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f7fe8fc7f3](https://linux-hardware.org/?probe=f7fe8fc7f3) | Aug 10, 2023 |
| Google        | Snappy                      | Notebook    | [73ecdd5048](https://linux-hardware.org/?probe=73ecdd5048) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [75b55100a9](https://linux-hardware.org/?probe=75b55100a9) | Aug 10, 2023 |
| Dell          | Precision 5540              | Notebook    | [e68fee1e24](https://linux-hardware.org/?probe=e68fee1e24) | Aug 10, 2023 |
| Gateway       | NV57H                       | Notebook    | [826aaf5dd8](https://linux-hardware.org/?probe=826aaf5dd8) | Aug 10, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [8fbbf1483d](https://linux-hardware.org/?probe=8fbbf1483d) | Aug 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [09037ac346](https://linux-hardware.org/?probe=09037ac346) | Aug 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f6040edeb0](https://linux-hardware.org/?probe=f6040edeb0) | Aug 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3b02fcaeb7](https://linux-hardware.org/?probe=3b02fcaeb7) | Aug 09, 2023 |
| Google        | Bobba360                    | Notebook    | [fa4a78b024](https://linux-hardware.org/?probe=fa4a78b024) | Aug 09, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [f50b51555f](https://linux-hardware.org/?probe=f50b51555f) | Aug 09, 2023 |
| System76      | Darter Pro                  | Notebook    | [5162d61c01](https://linux-hardware.org/?probe=5162d61c01) | Aug 09, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [37b2f22e1f](https://linux-hardware.org/?probe=37b2f22e1f) | Aug 09, 2023 |
| Dell          | Latitude 3350               | Notebook    | [77100b2ef6](https://linux-hardware.org/?probe=77100b2ef6) | Aug 09, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [78859b39fb](https://linux-hardware.org/?probe=78859b39fb) | Aug 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [f48f680274](https://linux-hardware.org/?probe=f48f680274) | Aug 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [f64529e38b](https://linux-hardware.org/?probe=f64529e38b) | Aug 08, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [9eccce625b](https://linux-hardware.org/?probe=9eccce625b) | Aug 08, 2023 |
| HP            | Laptop 14-dq3xxx            | Notebook    | [c547f01fbb](https://linux-hardware.org/?probe=c547f01fbb) | Aug 08, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [088a8fad47](https://linux-hardware.org/?probe=088a8fad47) | Aug 08, 2023 |
| Supermicro    | X10SRG-F                    | Desktop     | [3bdaa7bfef](https://linux-hardware.org/?probe=3bdaa7bfef) | Aug 08, 2023 |
| AZW           | MINI S 10                   | Desktop     | [1de6b9a754](https://linux-hardware.org/?probe=1de6b9a754) | Aug 08, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [0ee8428f91](https://linux-hardware.org/?probe=0ee8428f91) | Aug 07, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [a79335e604](https://linux-hardware.org/?probe=a79335e604) | Aug 07, 2023 |
| Dell          | Latitude 7300               | Notebook    | [932f04033c](https://linux-hardware.org/?probe=932f04033c) | Aug 07, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [047ae922f7](https://linux-hardware.org/?probe=047ae922f7) | Aug 07, 2023 |
| AZW           | SEi                         | Desktop     | [b38e4eec2e](https://linux-hardware.org/?probe=b38e4eec2e) | Aug 07, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5777798e8f](https://linux-hardware.org/?probe=5777798e8f) | Aug 07, 2023 |
| Acer          | E1-510                      | Notebook    | [2d6776c4fe](https://linux-hardware.org/?probe=2d6776c4fe) | Aug 06, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [341fecf811](https://linux-hardware.org/?probe=341fecf811) | Aug 06, 2023 |
| Lenovo        | ThinkCentre M57 6072BJU     | Desktop     | [9c0231c0f3](https://linux-hardware.org/?probe=9c0231c0f3) | Aug 06, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [9688966097](https://linux-hardware.org/?probe=9688966097) | Aug 06, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [bd989967e7](https://linux-hardware.org/?probe=bd989967e7) | Aug 06, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [feaab502d6](https://linux-hardware.org/?probe=feaab502d6) | Aug 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ce147f9768](https://linux-hardware.org/?probe=ce147f9768) | Aug 06, 2023 |
| Gateway       | SX2185                      | Desktop     | [a6df16b355](https://linux-hardware.org/?probe=a6df16b355) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [0219350ae0](https://linux-hardware.org/?probe=0219350ae0) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [350a405f33](https://linux-hardware.org/?probe=350a405f33) | Aug 05, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [8cc106746a](https://linux-hardware.org/?probe=8cc106746a) | Aug 05, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [d3630fa2ed](https://linux-hardware.org/?probe=d3630fa2ed) | Aug 05, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [ae0b8a9e36](https://linux-hardware.org/?probe=ae0b8a9e36) | Aug 05, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [4f2449c578](https://linux-hardware.org/?probe=4f2449c578) | Aug 05, 2023 |
| Lenovo        | ThinkPad X131e 33671S2      | Notebook    | [3f83b5efac](https://linux-hardware.org/?probe=3f83b5efac) | Aug 05, 2023 |
| ASUSTek       | Z97-PRO/USB                 | Desktop     | [edd74878c3](https://linux-hardware.org/?probe=edd74878c3) | Aug 05, 2023 |
| Corsair       | Voyager a1600               | Notebook    | [6dea5f2c0c](https://linux-hardware.org/?probe=6dea5f2c0c) | Aug 04, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [ff55512c0e](https://linux-hardware.org/?probe=ff55512c0e) | Aug 04, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [67cea35f6d](https://linux-hardware.org/?probe=67cea35f6d) | Aug 04, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [1b1f671f30](https://linux-hardware.org/?probe=1b1f671f30) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3c3d90d709](https://linux-hardware.org/?probe=3c3d90d709) | Aug 04, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [8f3b8dea26](https://linux-hardware.org/?probe=8f3b8dea26) | Aug 04, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [b9bb38ddd4](https://linux-hardware.org/?probe=b9bb38ddd4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [7d86876920](https://linux-hardware.org/?probe=7d86876920) | Aug 03, 2023 |
| Pegatron      | Eureka3                     | Desktop     | [a999a00c0a](https://linux-hardware.org/?probe=a999a00c0a) | Aug 03, 2023 |
| Dell          | Latitude 5440               | Notebook    | [5791d15bc8](https://linux-hardware.org/?probe=5791d15bc8) | Aug 02, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [fd259f2acd](https://linux-hardware.org/?probe=fd259f2acd) | Aug 02, 2023 |
| Dell          | Latitude 5540               | Notebook    | [e521b93e2f](https://linux-hardware.org/?probe=e521b93e2f) | Aug 02, 2023 |
| Dell          | Latitude 5440               | Notebook    | [5b0eb512d1](https://linux-hardware.org/?probe=5b0eb512d1) | Aug 02, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [d041df173b](https://linux-hardware.org/?probe=d041df173b) | Aug 02, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [542578b4cf](https://linux-hardware.org/?probe=542578b4cf) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [944afe5083](https://linux-hardware.org/?probe=944afe5083) | Aug 02, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [74f1782ead](https://linux-hardware.org/?probe=74f1782ead) | Aug 02, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [9042ebc249](https://linux-hardware.org/?probe=9042ebc249) | Aug 01, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [53468c11bf](https://linux-hardware.org/?probe=53468c11bf) | Aug 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [896569d1d6](https://linux-hardware.org/?probe=896569d1d6) | Aug 01, 2023 |
| HP            | 18E7                        | Desktop     | [339050cd65](https://linux-hardware.org/?probe=339050cd65) | Aug 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [1768a6834a](https://linux-hardware.org/?probe=1768a6834a) | Aug 01, 2023 |
| ASUSTek       | P6X58D-E                    | Desktop     | [84a5ec2d0b](https://linux-hardware.org/?probe=84a5ec2d0b) | Aug 01, 2023 |
| ASUSTek       | X751LA                      | Notebook    | [928a69b9af](https://linux-hardware.org/?probe=928a69b9af) | Aug 01, 2023 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [287ea63732](https://linux-hardware.org/?probe=287ea63732) | Aug 01, 2023 |
| Lenovo        | 3000 C100 07612GU           | Notebook    | [3941ecc4f2](https://linux-hardware.org/?probe=3941ecc4f2) | Aug 01, 2023 |
| Dell          | 0HJ054                      | Desktop     | [85ceb83c22](https://linux-hardware.org/?probe=85ceb83c22) | Jul 31, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [96e95e4bd2](https://linux-hardware.org/?probe=96e95e4bd2) | Jul 31, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [067b112fb8](https://linux-hardware.org/?probe=067b112fb8) | Jul 31, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [de727e7124](https://linux-hardware.org/?probe=de727e7124) | Jul 31, 2023 |
| ASRock        | FM2A75 Pro4                 | Desktop     | [831157a9ac](https://linux-hardware.org/?probe=831157a9ac) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50s 20FLCTO1WW    | Notebook    | [1594795f9e](https://linux-hardware.org/?probe=1594795f9e) | Jul 31, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [80ab0f5cd2](https://linux-hardware.org/?probe=80ab0f5cd2) | Jul 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0DT0... | Notebook    | [bd0d0f2888](https://linux-hardware.org/?probe=bd0d0f2888) | Jul 30, 2023 |
| HP            | ProBook 4540s               | Notebook    | [0fae07b574](https://linux-hardware.org/?probe=0fae07b574) | Jul 30, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [4f2f49a6b2](https://linux-hardware.org/?probe=4f2f49a6b2) | Jul 30, 2023 |
| BOSGAME       | U56                         | Notebook    | [39d52e51f5](https://linux-hardware.org/?probe=39d52e51f5) | Jul 30, 2023 |
| MSI           | B250 PC MATE                | Desktop     | [9163341ff4](https://linux-hardware.org/?probe=9163341ff4) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [c3101b6a76](https://linux-hardware.org/?probe=c3101b6a76) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [915938d446](https://linux-hardware.org/?probe=915938d446) | Jul 30, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [b49f52b2e1](https://linux-hardware.org/?probe=b49f52b2e1) | Jul 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [74a7a53f6a](https://linux-hardware.org/?probe=74a7a53f6a) | Jul 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [cd073a7899](https://linux-hardware.org/?probe=cd073a7899) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e62cce964c](https://linux-hardware.org/?probe=e62cce964c) | Jul 29, 2023 |
| HP            | ProBook 455R G6             | Notebook    | [3731e7465c](https://linux-hardware.org/?probe=3731e7465c) | Jul 29, 2023 |
| Dell          | Latitude 5520               | Notebook    | [5151c4275a](https://linux-hardware.org/?probe=5151c4275a) | Jul 29, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [532a72a722](https://linux-hardware.org/?probe=532a72a722) | Jul 29, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [76394a9fc7](https://linux-hardware.org/?probe=76394a9fc7) | Jul 29, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [d94c3cc0e8](https://linux-hardware.org/?probe=d94c3cc0e8) | Jul 28, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [21aa433472](https://linux-hardware.org/?probe=21aa433472) | Jul 28, 2023 |
| HP            | 1825                        | Desktop     | [7bd4e99efa](https://linux-hardware.org/?probe=7bd4e99efa) | Jul 28, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [2d141d703d](https://linux-hardware.org/?probe=2d141d703d) | Jul 28, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [78e12df29a](https://linux-hardware.org/?probe=78e12df29a) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [ea402f269e](https://linux-hardware.org/?probe=ea402f269e) | Jul 28, 2023 |
| Alienware     | m17 R4                      | Notebook    | [eece2da9ed](https://linux-hardware.org/?probe=eece2da9ed) | Jul 27, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [9b7b328324](https://linux-hardware.org/?probe=9b7b328324) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4152e1f98e](https://linux-hardware.org/?probe=4152e1f98e) | Jul 27, 2023 |
| HP            | 829A                        | Mini pc     | [c78cd4ea03](https://linux-hardware.org/?probe=c78cd4ea03) | Jul 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [f41d6c4f4b](https://linux-hardware.org/?probe=f41d6c4f4b) | Jul 26, 2023 |
| HP            | G60                         | Notebook    | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [3cb74490f6](https://linux-hardware.org/?probe=3cb74490f6) | Jul 25, 2023 |
| Google        | Droid                       | Notebook    | [ae803483c2](https://linux-hardware.org/?probe=ae803483c2) | Jul 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [5e77384bb8](https://linux-hardware.org/?probe=5e77384bb8) | Jul 25, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f01ec95642](https://linux-hardware.org/?probe=f01ec95642) | Jul 25, 2023 |
| HP            | ProBook 4540s               | Notebook    | [5c4b165cea](https://linux-hardware.org/?probe=5c4b165cea) | Jul 25, 2023 |
| HP            | ProBook 4540s               | Notebook    | [4ad8be01ca](https://linux-hardware.org/?probe=4ad8be01ca) | Jul 25, 2023 |
| Lenovo        | ThinkPad T430 2347H91       | Notebook    | [0ed3c4bc6a](https://linux-hardware.org/?probe=0ed3c4bc6a) | Jul 25, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [5c52eecd16](https://linux-hardware.org/?probe=5c52eecd16) | Jul 25, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [562e6e1026](https://linux-hardware.org/?probe=562e6e1026) | Jul 25, 2023 |
| Dell          | Latitude 7490               | Notebook    | [066e3b9518](https://linux-hardware.org/?probe=066e3b9518) | Jul 25, 2023 |
| Dell          | 0X501H A00                  | Desktop     | [407c19b590](https://linux-hardware.org/?probe=407c19b590) | Jul 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [a7d120e20a](https://linux-hardware.org/?probe=a7d120e20a) | Jul 24, 2023 |
| Lenovo        | ThinkPad T420s 417152U      | Notebook    | [22e09689b0](https://linux-hardware.org/?probe=22e09689b0) | Jul 24, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [a3284cc458](https://linux-hardware.org/?probe=a3284cc458) | Jul 24, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [60c98c273e](https://linux-hardware.org/?probe=60c98c273e) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [032db75736](https://linux-hardware.org/?probe=032db75736) | Jul 23, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3511a9786a](https://linux-hardware.org/?probe=3511a9786a) | Jul 23, 2023 |
| Lenovo        | ThinkPad P53 20QN004BCA     | Notebook    | [04a2ed4bd2](https://linux-hardware.org/?probe=04a2ed4bd2) | Jul 23, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [63fb3abc69](https://linux-hardware.org/?probe=63fb3abc69) | Jul 23, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [1ee910fc1c](https://linux-hardware.org/?probe=1ee910fc1c) | Jul 22, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [d02b0e9f74](https://linux-hardware.org/?probe=d02b0e9f74) | Jul 22, 2023 |
| Gateway       | NV57H                       | Notebook    | [3209dcf267](https://linux-hardware.org/?probe=3209dcf267) | Jul 22, 2023 |
| Gateway       | NV57H                       | Notebook    | [35dac8980f](https://linux-hardware.org/?probe=35dac8980f) | Jul 22, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [ce4d5128af](https://linux-hardware.org/?probe=ce4d5128af) | Jul 22, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [a96fbb9461](https://linux-hardware.org/?probe=a96fbb9461) | Jul 22, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [46283ad18b](https://linux-hardware.org/?probe=46283ad18b) | Jul 22, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [3edbf4710e](https://linux-hardware.org/?probe=3edbf4710e) | Jul 22, 2023 |
| HP            | Pavilion dv7                | Notebook    | [a74719eac2](https://linux-hardware.org/?probe=a74719eac2) | Jul 21, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | Notebook    | [27b5dabe8d](https://linux-hardware.org/?probe=27b5dabe8d) | Jul 21, 2023 |
| HP            | 18E7                        | Desktop     | [de29afa344](https://linux-hardware.org/?probe=de29afa344) | Jul 21, 2023 |
| Dell          | 00010C A00                  | Desktop     | [40543af7a5](https://linux-hardware.org/?probe=40543af7a5) | Jul 21, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [3e6dc436dd](https://linux-hardware.org/?probe=3e6dc436dd) | Jul 21, 2023 |
| Intel         | DP67BG AAG10491-400         | Desktop     | [084b222fa7](https://linux-hardware.org/?probe=084b222fa7) | Jul 21, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [c058e8c58e](https://linux-hardware.org/?probe=c058e8c58e) | Jul 20, 2023 |
| Intel         | DP67BG AAG10491-400         | Desktop     | [e0ff2f40fa](https://linux-hardware.org/?probe=e0ff2f40fa) | Jul 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fb09f582c5](https://linux-hardware.org/?probe=fb09f582c5) | Jul 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2fcc9e6028](https://linux-hardware.org/?probe=2fcc9e6028) | Jul 20, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [43cb18f0ee](https://linux-hardware.org/?probe=43cb18f0ee) | Jul 20, 2023 |
| Lenovo        | ThinkPad 20JB002BUS         | Tablet      | [ac659620e6](https://linux-hardware.org/?probe=ac659620e6) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [cb0ad6375e](https://linux-hardware.org/?probe=cb0ad6375e) | Jul 20, 2023 |
| MSI           | 870-G45                     | Desktop     | [af7442187f](https://linux-hardware.org/?probe=af7442187f) | Jul 20, 2023 |
| ASUSTek       | M11AD                       | Desktop     | [8a8cb2c3e4](https://linux-hardware.org/?probe=8a8cb2c3e4) | Jul 20, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [991cab2fa3](https://linux-hardware.org/?probe=991cab2fa3) | Jul 19, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0C800     | Notebook    | [b894a6d96b](https://linux-hardware.org/?probe=b894a6d96b) | Jul 19, 2023 |
| ASUSTek       | GL502VM                     | Notebook    | [dd46e07611](https://linux-hardware.org/?probe=dd46e07611) | Jul 19, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [91f1d1f94f](https://linux-hardware.org/?probe=91f1d1f94f) | Jul 19, 2023 |
| AZW           | U59                         | Desktop     | [1c919967a8](https://linux-hardware.org/?probe=1c919967a8) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [8cb16d19aa](https://linux-hardware.org/?probe=8cb16d19aa) | Jul 19, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [3121fc5450](https://linux-hardware.org/?probe=3121fc5450) | Jul 18, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [efd490f52d](https://linux-hardware.org/?probe=efd490f52d) | Jul 18, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [14478a9226](https://linux-hardware.org/?probe=14478a9226) | Jul 18, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | Desktop     | [e62367803c](https://linux-hardware.org/?probe=e62367803c) | Jul 18, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | Desktop     | [41e06d3720](https://linux-hardware.org/?probe=41e06d3720) | Jul 18, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [02f8df2129](https://linux-hardware.org/?probe=02f8df2129) | Jul 18, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [e7e056881b](https://linux-hardware.org/?probe=e7e056881b) | Jul 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [058672ddad](https://linux-hardware.org/?probe=058672ddad) | Jul 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [babb224527](https://linux-hardware.org/?probe=babb224527) | Jul 18, 2023 |
| ASUSTek       | M11AD                       | Desktop     | [4019d4eb57](https://linux-hardware.org/?probe=4019d4eb57) | Jul 18, 2023 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [574cd2e0f8](https://linux-hardware.org/?probe=574cd2e0f8) | Jul 17, 2023 |
| Google        | Phaser360                   | Notebook    | [1e66458514](https://linux-hardware.org/?probe=1e66458514) | Jul 17, 2023 |
| System76      | Serval WS                   | Notebook    | [a916a92726](https://linux-hardware.org/?probe=a916a92726) | Jul 17, 2023 |
| ASUSTek       | X751LA                      | Notebook    | [345fab37ab](https://linux-hardware.org/?probe=345fab37ab) | Jul 17, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7006e50178](https://linux-hardware.org/?probe=7006e50178) | Jul 17, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [55a5100039](https://linux-hardware.org/?probe=55a5100039) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [ad8f031cb2](https://linux-hardware.org/?probe=ad8f031cb2) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [151797320d](https://linux-hardware.org/?probe=151797320d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e760f4570f](https://linux-hardware.org/?probe=e760f4570f) | Jul 16, 2023 |
| Gateway       | SX2185                      | Desktop     | [1fe932f485](https://linux-hardware.org/?probe=1fe932f485) | Jul 15, 2023 |
| Gateway       | SX2185                      | Desktop     | [00e7bb0f9f](https://linux-hardware.org/?probe=00e7bb0f9f) | Jul 15, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [e8f1a169a1](https://linux-hardware.org/?probe=e8f1a169a1) | Jul 15, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [9eff556aca](https://linux-hardware.org/?probe=9eff556aca) | Jul 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e983b50085](https://linux-hardware.org/?probe=e983b50085) | Jul 15, 2023 |
| MSI           | 870-G45                     | Desktop     | [9fff23ac6a](https://linux-hardware.org/?probe=9fff23ac6a) | Jul 14, 2023 |
| System76      | Pangolin                    | Notebook    | [486df7ead2](https://linux-hardware.org/?probe=486df7ead2) | Jul 14, 2023 |
| Dell          | Precision 5480              | Notebook    | [57d3fff688](https://linux-hardware.org/?probe=57d3fff688) | Jul 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [065aed3358](https://linux-hardware.org/?probe=065aed3358) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [21fc63e4dd](https://linux-hardware.org/?probe=21fc63e4dd) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [4092f45d41](https://linux-hardware.org/?probe=4092f45d41) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [1ee27caac4](https://linux-hardware.org/?probe=1ee27caac4) | Jul 14, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [2afe11b7e4](https://linux-hardware.org/?probe=2afe11b7e4) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e84bf83ac1](https://linux-hardware.org/?probe=e84bf83ac1) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3428c47b0c](https://linux-hardware.org/?probe=3428c47b0c) | Jul 13, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [093938a09b](https://linux-hardware.org/?probe=093938a09b) | Jul 13, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [df7a7f2c36](https://linux-hardware.org/?probe=df7a7f2c36) | Jul 13, 2023 |
| Panasonic     | CF-S10CDHEDM                | Notebook    | [55204a29c3](https://linux-hardware.org/?probe=55204a29c3) | Jul 12, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8807f705d0](https://linux-hardware.org/?probe=8807f705d0) | Jul 12, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [414c5bc2c0](https://linux-hardware.org/?probe=414c5bc2c0) | Jul 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [15c5dec8dc](https://linux-hardware.org/?probe=15c5dec8dc) | Jul 12, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [41a05302e8](https://linux-hardware.org/?probe=41a05302e8) | Jul 12, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [077367f0bd](https://linux-hardware.org/?probe=077367f0bd) | Jul 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [27df8fc0e5](https://linux-hardware.org/?probe=27df8fc0e5) | Jul 11, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [7a6bfcf1a9](https://linux-hardware.org/?probe=7a6bfcf1a9) | Jul 11, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2397913be3](https://linux-hardware.org/?probe=2397913be3) | Jul 11, 2023 |
| Dell          | Latitude E5540              | Notebook    | [cdad6cb751](https://linux-hardware.org/?probe=cdad6cb751) | Jul 11, 2023 |
| Lenovo        | IdeaPad Z570 10249UU        | Notebook    | [4179167c95](https://linux-hardware.org/?probe=4179167c95) | Jul 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [ee2dc6ac7b](https://linux-hardware.org/?probe=ee2dc6ac7b) | Jul 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [c44f642440](https://linux-hardware.org/?probe=c44f642440) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d73ac20739](https://linux-hardware.org/?probe=d73ac20739) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [beef3128c2](https://linux-hardware.org/?probe=beef3128c2) | Jul 10, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [957c1976c6](https://linux-hardware.org/?probe=957c1976c6) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [cf25605b3a](https://linux-hardware.org/?probe=cf25605b3a) | Jul 10, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [7d5e51d9a8](https://linux-hardware.org/?probe=7d5e51d9a8) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [3c3c2ac038](https://linux-hardware.org/?probe=3c3c2ac038) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [707f0b8eeb](https://linux-hardware.org/?probe=707f0b8eeb) | Jul 10, 2023 |
| HP            | 1496                        | Desktop     | [48292f90f9](https://linux-hardware.org/?probe=48292f90f9) | Jul 10, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [1312271ad3](https://linux-hardware.org/?probe=1312271ad3) | Jul 10, 2023 |
| HP            | 2B3E                        | All in one  | [9ec58b6284](https://linux-hardware.org/?probe=9ec58b6284) | Jul 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [59f9ee3ee8](https://linux-hardware.org/?probe=59f9ee3ee8) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [1e27d93bb4](https://linux-hardware.org/?probe=1e27d93bb4) | Jul 09, 2023 |
| MSI           | B360M MORTAR TITANIUM       | Desktop     | [31b2aa5991](https://linux-hardware.org/?probe=31b2aa5991) | Jul 08, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [3540170054](https://linux-hardware.org/?probe=3540170054) | Jul 08, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [8dd1516457](https://linux-hardware.org/?probe=8dd1516457) | Jul 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a686a6eed6](https://linux-hardware.org/?probe=a686a6eed6) | Jul 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4a761f6a66](https://linux-hardware.org/?probe=4a761f6a66) | Jul 08, 2023 |
| Dell          | Latitude 5540               | Notebook    | [1bd623d7b0](https://linux-hardware.org/?probe=1bd623d7b0) | Jul 07, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [12e3f9ecc7](https://linux-hardware.org/?probe=12e3f9ecc7) | Jul 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| Lenovo        | ThinkPad T510 4349RK6       | Notebook    | [e25d3f6783](https://linux-hardware.org/?probe=e25d3f6783) | Jul 07, 2023 |
| Lenovo        | ThinkPad T450s 20BWS0PJ0... | Notebook    | [2345d00757](https://linux-hardware.org/?probe=2345d00757) | Jul 07, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [23c5c27995](https://linux-hardware.org/?probe=23c5c27995) | Jul 07, 2023 |
| Dell          | Latitude 3540               | Notebook    | [4ebbd2913f](https://linux-hardware.org/?probe=4ebbd2913f) | Jul 06, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [68235880f7](https://linux-hardware.org/?probe=68235880f7) | Jul 06, 2023 |
| Framework     | Laptop                      | Notebook    | [ea4c4585d0](https://linux-hardware.org/?probe=ea4c4585d0) | Jul 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [f99a1ccf8f](https://linux-hardware.org/?probe=f99a1ccf8f) | Jul 06, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [5e66adbc36](https://linux-hardware.org/?probe=5e66adbc36) | Jul 06, 2023 |
| Dell          | 0C2425 A00                  | Desktop     | [130edcd2b5](https://linux-hardware.org/?probe=130edcd2b5) | Jul 06, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [f255433162](https://linux-hardware.org/?probe=f255433162) | Jul 06, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [a5176fb830](https://linux-hardware.org/?probe=a5176fb830) | Jul 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [d58bb46843](https://linux-hardware.org/?probe=d58bb46843) | Jul 05, 2023 |
| ASUSTek       | TP501UA                     | Notebook    | [ee28aacdd1](https://linux-hardware.org/?probe=ee28aacdd1) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [46e6f4b081](https://linux-hardware.org/?probe=46e6f4b081) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [6bf093ef61](https://linux-hardware.org/?probe=6bf093ef61) | Jul 05, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [7a15493631](https://linux-hardware.org/?probe=7a15493631) | Jul 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [3707ca3e1d](https://linux-hardware.org/?probe=3707ca3e1d) | Jul 05, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [79c5344e62](https://linux-hardware.org/?probe=79c5344e62) | Jul 04, 2023 |
| Microsoft     | Surface Book 2              | Tablet      | [eb928a82c9](https://linux-hardware.org/?probe=eb928a82c9) | Jul 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [09627980f5](https://linux-hardware.org/?probe=09627980f5) | Jul 04, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [9ec1de725f](https://linux-hardware.org/?probe=9ec1de725f) | Jul 04, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [663261b61f](https://linux-hardware.org/?probe=663261b61f) | Jul 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [5d1b3596c1](https://linux-hardware.org/?probe=5d1b3596c1) | Jul 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [3290dd955a](https://linux-hardware.org/?probe=3290dd955a) | Jul 03, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [77a720dc31](https://linux-hardware.org/?probe=77a720dc31) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d17e5d7807](https://linux-hardware.org/?probe=d17e5d7807) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [29897719d5](https://linux-hardware.org/?probe=29897719d5) | Jul 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [da271abdd3](https://linux-hardware.org/?probe=da271abdd3) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [364082f281](https://linux-hardware.org/?probe=364082f281) | Jul 03, 2023 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [34832945aa](https://linux-hardware.org/?probe=34832945aa) | Jul 02, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [4f24850748](https://linux-hardware.org/?probe=4f24850748) | Jul 02, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [e112fcd006](https://linux-hardware.org/?probe=e112fcd006) | Jul 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [92bf7e658e](https://linux-hardware.org/?probe=92bf7e658e) | Jul 02, 2023 |
| HP            | 1497                        | Desktop     | [e282eb8fe1](https://linux-hardware.org/?probe=e282eb8fe1) | Jul 02, 2023 |
| MSI           | GT72VR 6RD                  | Notebook    | [ea6887d031](https://linux-hardware.org/?probe=ea6887d031) | Jul 01, 2023 |
| Dell          | Latitude 3500               | Notebook    | [8e82f9abda](https://linux-hardware.org/?probe=8e82f9abda) | Jul 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [ca6243303f](https://linux-hardware.org/?probe=ca6243303f) | Jul 01, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [585ee2564e](https://linux-hardware.org/?probe=585ee2564e) | Jul 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [57424619e8](https://linux-hardware.org/?probe=57424619e8) | Jul 01, 2023 |
| HP            | ENVY m6                     | Notebook    | [b4f8d19895](https://linux-hardware.org/?probe=b4f8d19895) | Jun 30, 2023 |
| HP            | 8158 A01                    | Mini pc     | [6137e1cbbb](https://linux-hardware.org/?probe=6137e1cbbb) | Jun 30, 2023 |
| Gigabyte      | B550 UD AC                  | Desktop     | [7d7d37522c](https://linux-hardware.org/?probe=7d7d37522c) | Jun 30, 2023 |
| Dell          | Latitude E5440              | Notebook    | [1fd8c9652a](https://linux-hardware.org/?probe=1fd8c9652a) | Jun 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [70ed50862c](https://linux-hardware.org/?probe=70ed50862c) | Jun 30, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [5907f43d41](https://linux-hardware.org/?probe=5907f43d41) | Jun 30, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [ef3b3cf51e](https://linux-hardware.org/?probe=ef3b3cf51e) | Jun 30, 2023 |
| Samsung       | R430/R480                   | Notebook    | [485a09a0d2](https://linux-hardware.org/?probe=485a09a0d2) | Jun 30, 2023 |
| AZW           | MINI S 10                   | Desktop     | [84eec8c276](https://linux-hardware.org/?probe=84eec8c276) | Jun 29, 2023 |
| MSI           | P67A-G43                    | Desktop     | [8e5f71c975](https://linux-hardware.org/?probe=8e5f71c975) | Jun 29, 2023 |
| AZW           | MINI S 10                   | Desktop     | [d1795fbf64](https://linux-hardware.org/?probe=d1795fbf64) | Jun 29, 2023 |
| HP            | 8055                        | Desktop     | [47536e2cde](https://linux-hardware.org/?probe=47536e2cde) | Jun 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2dd6be0ddc](https://linux-hardware.org/?probe=2dd6be0ddc) | Jun 29, 2023 |
| Dell          | 0PU052                      | Desktop     | [b4fde65c68](https://linux-hardware.org/?probe=b4fde65c68) | Jun 29, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [c3118a3d89](https://linux-hardware.org/?probe=c3118a3d89) | Jun 29, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [89f1647ea1](https://linux-hardware.org/?probe=89f1647ea1) | Jun 29, 2023 |
| Lenovo        | ThinkPad Edge E545 20B2S... | Notebook    | [c7e71c8c0b](https://linux-hardware.org/?probe=c7e71c8c0b) | Jun 29, 2023 |
| Lenovo        | ThinkPad Edge E545 20B2S... | Notebook    | [0c3b48af38](https://linux-hardware.org/?probe=0c3b48af38) | Jun 29, 2023 |
| HP            | ProLiant DL160 G6           | Server      | [8a47bef402](https://linux-hardware.org/?probe=8a47bef402) | Jun 29, 2023 |
| Lenovo        | ThinkPad T580 20LAS0DL00    | Notebook    | [5d27a44710](https://linux-hardware.org/?probe=5d27a44710) | Jun 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [92a71d25d7](https://linux-hardware.org/?probe=92a71d25d7) | Jun 28, 2023 |
| Dell          | Latitude 3500               | Notebook    | [e1831984f8](https://linux-hardware.org/?probe=e1831984f8) | Jun 28, 2023 |
| Acer          | Aspire Z3-705               | All in one  | [058c58505d](https://linux-hardware.org/?probe=058c58505d) | Jun 28, 2023 |
| HP            | 8459                        | Desktop     | [7b60320110](https://linux-hardware.org/?probe=7b60320110) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [2debd02f0c](https://linux-hardware.org/?probe=2debd02f0c) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [3b775b8099](https://linux-hardware.org/?probe=3b775b8099) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [afe6ac4f32](https://linux-hardware.org/?probe=afe6ac4f32) | Jun 27, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d0d602b518](https://linux-hardware.org/?probe=d0d602b518) | Jun 27, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [d61ba42fcf](https://linux-hardware.org/?probe=d61ba42fcf) | Jun 27, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9e3cbeb0f5](https://linux-hardware.org/?probe=9e3cbeb0f5) | Jun 27, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [765d0708eb](https://linux-hardware.org/?probe=765d0708eb) | Jun 26, 2023 |
| ASRock        | G31M-S                      | Desktop     | [2437008395](https://linux-hardware.org/?probe=2437008395) | Jun 26, 2023 |
| Dell          | 0PU052                      | Desktop     | [34eaa7185d](https://linux-hardware.org/?probe=34eaa7185d) | Jun 26, 2023 |
| HP            | 82A2                        | Desktop     | [aa7e838d53](https://linux-hardware.org/?probe=aa7e838d53) | Jun 26, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [076507dc77](https://linux-hardware.org/?probe=076507dc77) | Jun 26, 2023 |
| Gateway       | NV57H                       | Notebook    | [a49db45595](https://linux-hardware.org/?probe=a49db45595) | Jun 26, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [dfc817892b](https://linux-hardware.org/?probe=dfc817892b) | Jun 26, 2023 |
| Gateway       | NV57H                       | Notebook    | [ee84597590](https://linux-hardware.org/?probe=ee84597590) | Jun 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f36489e090](https://linux-hardware.org/?probe=f36489e090) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [4518a77b73](https://linux-hardware.org/?probe=4518a77b73) | Jun 26, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [d34d125de2](https://linux-hardware.org/?probe=d34d125de2) | Jun 26, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [77e0f0541a](https://linux-hardware.org/?probe=77e0f0541a) | Jun 26, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [1858ae62ee](https://linux-hardware.org/?probe=1858ae62ee) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [501d3b5530](https://linux-hardware.org/?probe=501d3b5530) | Jun 25, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | Notebook    | [68117675ab](https://linux-hardware.org/?probe=68117675ab) | Jun 25, 2023 |
| ASUSTek       | E403SA                      | Notebook    | [bdc47269c3](https://linux-hardware.org/?probe=bdc47269c3) | Jun 25, 2023 |
| Lenovo        | ThinkCentre M57 6072BJU     | Desktop     | [0343a0d640](https://linux-hardware.org/?probe=0343a0d640) | Jun 25, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [4493e92d84](https://linux-hardware.org/?probe=4493e92d84) | Jun 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [cf3b44c0b6](https://linux-hardware.org/?probe=cf3b44c0b6) | Jun 25, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [614687bba4](https://linux-hardware.org/?probe=614687bba4) | Jun 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [17c221fa68](https://linux-hardware.org/?probe=17c221fa68) | Jun 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6c015f633b](https://linux-hardware.org/?probe=6c015f633b) | Jun 24, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [090549881a](https://linux-hardware.org/?probe=090549881a) | Jun 24, 2023 |
| ASUSTek       | Berkeley                    | Desktop     | [5d4d2adebe](https://linux-hardware.org/?probe=5d4d2adebe) | Jun 24, 2023 |
| Xplore        | iX104C6                     | Notebook    | [23bb4c656b](https://linux-hardware.org/?probe=23bb4c656b) | Jun 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f87146e2d5](https://linux-hardware.org/?probe=f87146e2d5) | Jun 23, 2023 |
| HP            | 8055                        | Desktop     | [21f11f538d](https://linux-hardware.org/?probe=21f11f538d) | Jun 23, 2023 |
| HP            | 8055                        | Desktop     | [54e0de7a72](https://linux-hardware.org/?probe=54e0de7a72) | Jun 23, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3789bc7deb](https://linux-hardware.org/?probe=3789bc7deb) | Jun 23, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [7ba7b1dc58](https://linux-hardware.org/?probe=7ba7b1dc58) | Jun 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [abbb1b897d](https://linux-hardware.org/?probe=abbb1b897d) | Jun 22, 2023 |
| Google        | Kefka                       | Notebook    | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| ASRock        | NUC-TGL                     | Desktop     | [6dcb1eb43d](https://linux-hardware.org/?probe=6dcb1eb43d) | Jun 22, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [08974b3246](https://linux-hardware.org/?probe=08974b3246) | Jun 22, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [a6a3ed2eae](https://linux-hardware.org/?probe=a6a3ed2eae) | Jun 21, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [60babdeb16](https://linux-hardware.org/?probe=60babdeb16) | Jun 21, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [481ef14837](https://linux-hardware.org/?probe=481ef14837) | Jun 21, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [caaf6ce403](https://linux-hardware.org/?probe=caaf6ce403) | Jun 21, 2023 |
| Dell          | 0GM819                      | Desktop     | [5823b51b38](https://linux-hardware.org/?probe=5823b51b38) | Jun 20, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [3d50367e9f](https://linux-hardware.org/?probe=3d50367e9f) | Jun 20, 2023 |
| MSI           | Z77A-G41                    | Desktop     | [e7e4924bda](https://linux-hardware.org/?probe=e7e4924bda) | Jun 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [e5db90d1b4](https://linux-hardware.org/?probe=e5db90d1b4) | Jun 20, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [05b8720dce](https://linux-hardware.org/?probe=05b8720dce) | Jun 19, 2023 |
| Amlogic       | Meson GXL (S905X) P212 D... | Soc         | [7c79fa6641](https://linux-hardware.org/?probe=7c79fa6641) | Jun 19, 2023 |
| Dell          | 0PU052                      | Desktop     | [2eb6dceca9](https://linux-hardware.org/?probe=2eb6dceca9) | Jun 19, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [f38684c33d](https://linux-hardware.org/?probe=f38684c33d) | Jun 19, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [320b7a9b98](https://linux-hardware.org/?probe=320b7a9b98) | Jun 19, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [32990a28e8](https://linux-hardware.org/?probe=32990a28e8) | Jun 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [e3ded6b5e4](https://linux-hardware.org/?probe=e3ded6b5e4) | Jun 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [640ff2ce2e](https://linux-hardware.org/?probe=640ff2ce2e) | Jun 19, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [70d76362e2](https://linux-hardware.org/?probe=70d76362e2) | Jun 19, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [125b4fefa5](https://linux-hardware.org/?probe=125b4fefa5) | Jun 19, 2023 |
| Intel         | NUC6i7KYB H90766-409        | Mini pc     | [0a2b143bf1](https://linux-hardware.org/?probe=0a2b143bf1) | Jun 19, 2023 |
| Dell          | System XPS L502X            | Notebook    | [463e017820](https://linux-hardware.org/?probe=463e017820) | Jun 19, 2023 |
| Lenovo        | ThinkPad E590 20NB001JUS    | Notebook    | [5fb441bf83](https://linux-hardware.org/?probe=5fb441bf83) | Jun 18, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [f977b4851c](https://linux-hardware.org/?probe=f977b4851c) | Jun 18, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [cb20c2c912](https://linux-hardware.org/?probe=cb20c2c912) | Jun 18, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [97699ce0ff](https://linux-hardware.org/?probe=97699ce0ff) | Jun 18, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [299db094f8](https://linux-hardware.org/?probe=299db094f8) | Jun 18, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| HP            | Pavilion dv7                | Notebook    | [166b70ddad](https://linux-hardware.org/?probe=166b70ddad) | Jun 18, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [ef0c9e5597](https://linux-hardware.org/?probe=ef0c9e5597) | Jun 18, 2023 |
| Google        | Kefka                       | Notebook    | [86421e3d29](https://linux-hardware.org/?probe=86421e3d29) | Jun 18, 2023 |
| Valve         | Jupiter                     | Notebook    | [9da2af6fe5](https://linux-hardware.org/?probe=9da2af6fe5) | Jun 18, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [b61e6bc6d2](https://linux-hardware.org/?probe=b61e6bc6d2) | Jun 17, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [71c3b52599](https://linux-hardware.org/?probe=71c3b52599) | Jun 17, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [d415965e91](https://linux-hardware.org/?probe=d415965e91) | Jun 17, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f8aca3e72](https://linux-hardware.org/?probe=0f8aca3e72) | Jun 17, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e26a82f97f](https://linux-hardware.org/?probe=e26a82f97f) | Jun 17, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [268b733c44](https://linux-hardware.org/?probe=268b733c44) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [84b103464e](https://linux-hardware.org/?probe=84b103464e) | Jun 16, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [c47a9a7bb8](https://linux-hardware.org/?probe=c47a9a7bb8) | Jun 16, 2023 |
| Acer          | Aspire V3-572P              | Notebook    | [49302da0a9](https://linux-hardware.org/?probe=49302da0a9) | Jun 16, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [3b94657fa0](https://linux-hardware.org/?probe=3b94657fa0) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [96be22e98f](https://linux-hardware.org/?probe=96be22e98f) | Jun 15, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9604c6211e](https://linux-hardware.org/?probe=9604c6211e) | Jun 15, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [5a1e944af2](https://linux-hardware.org/?probe=5a1e944af2) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [3b552a7f4a](https://linux-hardware.org/?probe=3b552a7f4a) | Jun 15, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [ae4444566b](https://linux-hardware.org/?probe=ae4444566b) | Jun 14, 2023 |
| HP            | 2820h                       | Desktop     | [41fa36550a](https://linux-hardware.org/?probe=41fa36550a) | Jun 14, 2023 |
| Dell          | 0GU083 A00                  | Desktop     | [3d6b3b5013](https://linux-hardware.org/?probe=3d6b3b5013) | Jun 14, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f6175fd764](https://linux-hardware.org/?probe=f6175fd764) | Jun 14, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [143672bf6c](https://linux-hardware.org/?probe=143672bf6c) | Jun 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [b639a64b45](https://linux-hardware.org/?probe=b639a64b45) | Jun 14, 2023 |
| Lenovo        | IdeaPadFlex 5 16IRU8 82Y... | Convertible | [97e81b884c](https://linux-hardware.org/?probe=97e81b884c) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [051cebacd1](https://linux-hardware.org/?probe=051cebacd1) | Jun 14, 2023 |
| MSI           | GE62 2QF                    | Notebook    | [aabf8f661a](https://linux-hardware.org/?probe=aabf8f661a) | Jun 14, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [ad75eab286](https://linux-hardware.org/?probe=ad75eab286) | Jun 13, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [6291133649](https://linux-hardware.org/?probe=6291133649) | Jun 13, 2023 |
| Acer          | Aspire V3-572P              | Notebook    | [12f6b82789](https://linux-hardware.org/?probe=12f6b82789) | Jun 13, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [b303846ade](https://linux-hardware.org/?probe=b303846ade) | Jun 13, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [f4f10ca549](https://linux-hardware.org/?probe=f4f10ca549) | Jun 13, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0579a4f6f3](https://linux-hardware.org/?probe=0579a4f6f3) | Jun 13, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [c1f5bf2148](https://linux-hardware.org/?probe=c1f5bf2148) | Jun 13, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [2b88daaaea](https://linux-hardware.org/?probe=2b88daaaea) | Jun 13, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [c3f70b8f48](https://linux-hardware.org/?probe=c3f70b8f48) | Jun 13, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [ca84981180](https://linux-hardware.org/?probe=ca84981180) | Jun 12, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [5678f7fb1f](https://linux-hardware.org/?probe=5678f7fb1f) | Jun 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7be8732d39](https://linux-hardware.org/?probe=7be8732d39) | Jun 12, 2023 |
| Fujitsu       | T900                        | Notebook    | [4716750f3f](https://linux-hardware.org/?probe=4716750f3f) | Jun 12, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [cba5fb51f8](https://linux-hardware.org/?probe=cba5fb51f8) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3c7683dfc4](https://linux-hardware.org/?probe=3c7683dfc4) | Jun 11, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [740fb14b2f](https://linux-hardware.org/?probe=740fb14b2f) | Jun 11, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [8a07e36a48](https://linux-hardware.org/?probe=8a07e36a48) | Jun 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8738063b30](https://linux-hardware.org/?probe=8738063b30) | Jun 11, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [43991c533e](https://linux-hardware.org/?probe=43991c533e) | Jun 10, 2023 |
| MSI           | MS-B9321                    | Desktop     | [a7a878dbe6](https://linux-hardware.org/?probe=a7a878dbe6) | Jun 10, 2023 |
| ASRock        | B550AM Gaming               | Desktop     | [eca79c3bbb](https://linux-hardware.org/?probe=eca79c3bbb) | Jun 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [4c9c3d929b](https://linux-hardware.org/?probe=4c9c3d929b) | Jun 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8e10de95af](https://linux-hardware.org/?probe=8e10de95af) | Jun 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [1a36e2fa98](https://linux-hardware.org/?probe=1a36e2fa98) | Jun 10, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [42722d78d8](https://linux-hardware.org/?probe=42722d78d8) | Jun 10, 2023 |
| Sony          | VPCF120FD                   | Notebook    | [47f02bd498](https://linux-hardware.org/?probe=47f02bd498) | Jun 10, 2023 |
| Lenovo        | 3172 SDK0J40697 WIN 3305... | Mini pc     | [7f437dc929](https://linux-hardware.org/?probe=7f437dc929) | Jun 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0e34d2ee28](https://linux-hardware.org/?probe=0e34d2ee28) | Jun 09, 2023 |
| Sony          | VPCEB2AFD                   | Notebook    | [1d9d6ddd74](https://linux-hardware.org/?probe=1d9d6ddd74) | Jun 09, 2023 |
| Panasonic     | CF-S10CDHEDM                | Notebook    | [19b6085754](https://linux-hardware.org/?probe=19b6085754) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [6e5323aa42](https://linux-hardware.org/?probe=6e5323aa42) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [fc4b07cbb0](https://linux-hardware.org/?probe=fc4b07cbb0) | Jun 09, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [09344fa63e](https://linux-hardware.org/?probe=09344fa63e) | Jun 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8173a6e67f](https://linux-hardware.org/?probe=8173a6e67f) | Jun 08, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [52df878410](https://linux-hardware.org/?probe=52df878410) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [05973f7d9b](https://linux-hardware.org/?probe=05973f7d9b) | Jun 08, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [7775c4c871](https://linux-hardware.org/?probe=7775c4c871) | Jun 07, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [3a43778152](https://linux-hardware.org/?probe=3a43778152) | Jun 07, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [eb3fbddd2c](https://linux-hardware.org/?probe=eb3fbddd2c) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 4282AB9       | Notebook    | [790550e99f](https://linux-hardware.org/?probe=790550e99f) | Jun 06, 2023 |
| HP            | 83E1                        | Desktop     | [227e410c6f](https://linux-hardware.org/?probe=227e410c6f) | Jun 06, 2023 |
| Lenovo        | 30D0 NOK                    | Desktop     | [045b011b7a](https://linux-hardware.org/?probe=045b011b7a) | Jun 06, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [bbbe24d6b6](https://linux-hardware.org/?probe=bbbe24d6b6) | Jun 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9c282e76a6](https://linux-hardware.org/?probe=9c282e76a6) | Jun 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [1c99e1316c](https://linux-hardware.org/?probe=1c99e1316c) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [60fb09bf5e](https://linux-hardware.org/?probe=60fb09bf5e) | Jun 05, 2023 |
| MSI           | B250 GAMING PRO CARBON      | Desktop     | [32da3735d9](https://linux-hardware.org/?probe=32da3735d9) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4592ff63f3](https://linux-hardware.org/?probe=4592ff63f3) | Jun 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [aa2925f22f](https://linux-hardware.org/?probe=aa2925f22f) | Jun 05, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0DR0... | Notebook    | [6fad1535c3](https://linux-hardware.org/?probe=6fad1535c3) | Jun 04, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [fb0c1a4922](https://linux-hardware.org/?probe=fb0c1a4922) | Jun 04, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [a90856c944](https://linux-hardware.org/?probe=a90856c944) | Jun 04, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [3fc6303165](https://linux-hardware.org/?probe=3fc6303165) | Jun 03, 2023 |
| Dell          | Precision 5540              | Notebook    | [f9f2304792](https://linux-hardware.org/?probe=f9f2304792) | Jun 03, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| MSI           | B250 GAMING PRO CARBON      | Desktop     | [ef7acf6baa](https://linux-hardware.org/?probe=ef7acf6baa) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [21b7236d20](https://linux-hardware.org/?probe=21b7236d20) | Jun 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [e28ef4a6b7](https://linux-hardware.org/?probe=e28ef4a6b7) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| ASUSTek       | Maximus Formula             | Desktop     | [6a70fa0a86](https://linux-hardware.org/?probe=6a70fa0a86) | Jun 02, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [d75ea1f93f](https://linux-hardware.org/?probe=d75ea1f93f) | Jun 02, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [047bfb6e8e](https://linux-hardware.org/?probe=047bfb6e8e) | Jun 02, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [becb85a201](https://linux-hardware.org/?probe=becb85a201) | Jun 02, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [7789b12750](https://linux-hardware.org/?probe=7789b12750) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [29c4ba7312](https://linux-hardware.org/?probe=29c4ba7312) | Jun 01, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [57db123250](https://linux-hardware.org/?probe=57db123250) | Jun 01, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [7070e55aa0](https://linux-hardware.org/?probe=7070e55aa0) | Jun 01, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [28eec89b69](https://linux-hardware.org/?probe=28eec89b69) | Jun 01, 2023 |
| Lenovo        | ThinkPad W510 4391B49       | Notebook    | [1e1004a387](https://linux-hardware.org/?probe=1e1004a387) | Jun 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a28272d6e](https://linux-hardware.org/?probe=9a28272d6e) | Jun 01, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [b3eed1356b](https://linux-hardware.org/?probe=b3eed1356b) | Jun 01, 2023 |
| Dell          | Latitude E5540              | Notebook    | [83d7c0065d](https://linux-hardware.org/?probe=83d7c0065d) | Jun 01, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [8bc281486e](https://linux-hardware.org/?probe=8bc281486e) | May 31, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3b9639141c](https://linux-hardware.org/?probe=3b9639141c) | May 31, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [32a85827df](https://linux-hardware.org/?probe=32a85827df) | May 31, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [e45b1707bd](https://linux-hardware.org/?probe=e45b1707bd) | May 31, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [0b958e0c5c](https://linux-hardware.org/?probe=0b958e0c5c) | May 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [cffbd92b9f](https://linux-hardware.org/?probe=cffbd92b9f) | May 31, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [4a3e8c4d6f](https://linux-hardware.org/?probe=4a3e8c4d6f) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [698e3b5e35](https://linux-hardware.org/?probe=698e3b5e35) | May 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [399cce0d30](https://linux-hardware.org/?probe=399cce0d30) | May 30, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [67c96085bf](https://linux-hardware.org/?probe=67c96085bf) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [1793fc9d72](https://linux-hardware.org/?probe=1793fc9d72) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [94fda2dea0](https://linux-hardware.org/?probe=94fda2dea0) | May 30, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c98400b6eb](https://linux-hardware.org/?probe=c98400b6eb) | May 30, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [98e2096ab6](https://linux-hardware.org/?probe=98e2096ab6) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | Notebook    | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [26f783c383](https://linux-hardware.org/?probe=26f783c383) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [531455206b](https://linux-hardware.org/?probe=531455206b) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8b1445b47c](https://linux-hardware.org/?probe=8b1445b47c) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [06318d2354](https://linux-hardware.org/?probe=06318d2354) | May 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [a47a934500](https://linux-hardware.org/?probe=a47a934500) | May 29, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [c24eb2f7dd](https://linux-hardware.org/?probe=c24eb2f7dd) | May 29, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [52517395ca](https://linux-hardware.org/?probe=52517395ca) | May 29, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [6dc6a9d6f5](https://linux-hardware.org/?probe=6dc6a9d6f5) | May 29, 2023 |
| Lenovo        | ThinkCentre M58p 6137AU8    | Desktop     | [bd80dea70f](https://linux-hardware.org/?probe=bd80dea70f) | May 29, 2023 |
| Lenovo        | ThinkPad T420 4236N79       | Notebook    | [9908724093](https://linux-hardware.org/?probe=9908724093) | May 28, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [8bdf6722e2](https://linux-hardware.org/?probe=8bdf6722e2) | May 28, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [22cbc01649](https://linux-hardware.org/?probe=22cbc01649) | May 28, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [993b013d0a](https://linux-hardware.org/?probe=993b013d0a) | May 28, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e38da09f](https://linux-hardware.org/?probe=e2e38da09f) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| Dell          | Latitude E6330              | Notebook    | [dd302db25c](https://linux-hardware.org/?probe=dd302db25c) | May 27, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [741e0e805b](https://linux-hardware.org/?probe=741e0e805b) | May 27, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [b2672eb1db](https://linux-hardware.org/?probe=b2672eb1db) | May 27, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [906e585809](https://linux-hardware.org/?probe=906e585809) | May 27, 2023 |
| Dell          | Latitude E6330              | Notebook    | [f93b318d71](https://linux-hardware.org/?probe=f93b318d71) | May 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [f1b7ea69ea](https://linux-hardware.org/?probe=f1b7ea69ea) | May 27, 2023 |
| Lenovo        | Unknown                     | Notebook    | [dbf5c576b2](https://linux-hardware.org/?probe=dbf5c576b2) | May 27, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [33eb5df96b](https://linux-hardware.org/?probe=33eb5df96b) | May 26, 2023 |
| Samsung       | 910S3G/910S3T               | Notebook    | [e041a5365e](https://linux-hardware.org/?probe=e041a5365e) | May 26, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [d229a8eb01](https://linux-hardware.org/?probe=d229a8eb01) | May 26, 2023 |
| Dell          | 0K095G A02                  | Desktop     | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [5b0dffc2c3](https://linux-hardware.org/?probe=5b0dffc2c3) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| Acer          | Aspire M3910                | Desktop     | [f4dedc13f9](https://linux-hardware.org/?probe=f4dedc13f9) | May 25, 2023 |
| Acer          | Aspire V3-551               | Notebook    | [316db578fe](https://linux-hardware.org/?probe=316db578fe) | May 25, 2023 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [b00cde0e71](https://linux-hardware.org/?probe=b00cde0e71) | May 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [84756c6406](https://linux-hardware.org/?probe=84756c6406) | May 25, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [52e1964d2c](https://linux-hardware.org/?probe=52e1964d2c) | May 25, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [3a85770148](https://linux-hardware.org/?probe=3a85770148) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [9294d16ea5](https://linux-hardware.org/?probe=9294d16ea5) | May 25, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [1523787171](https://linux-hardware.org/?probe=1523787171) | May 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [89d040ffaf](https://linux-hardware.org/?probe=89d040ffaf) | May 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [0a2dc161fe](https://linux-hardware.org/?probe=0a2dc161fe) | May 24, 2023 |
| Alienware     | 17 R3                       | Notebook    | [a567b379a1](https://linux-hardware.org/?probe=a567b379a1) | May 24, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d99af6bab2](https://linux-hardware.org/?probe=d99af6bab2) | May 24, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [deff44e62e](https://linux-hardware.org/?probe=deff44e62e) | May 24, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [48bd340a09](https://linux-hardware.org/?probe=48bd340a09) | May 24, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ed936908c9](https://linux-hardware.org/?probe=ed936908c9) | May 23, 2023 |
| HP            | 81B3                        | Desktop     | [6b35d06402](https://linux-hardware.org/?probe=6b35d06402) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a605d12e2d](https://linux-hardware.org/?probe=a605d12e2d) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a1770c45b0](https://linux-hardware.org/?probe=a1770c45b0) | May 23, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [35a7542634](https://linux-hardware.org/?probe=35a7542634) | May 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [12a444a75a](https://linux-hardware.org/?probe=12a444a75a) | May 23, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [241bd90f1f](https://linux-hardware.org/?probe=241bd90f1f) | May 23, 2023 |
| Lenovo        | ThinkPad T540p 20BF001NU... | Notebook    | [2a770d2eac](https://linux-hardware.org/?probe=2a770d2eac) | May 23, 2023 |
| HP            | 0AECh D                     | Desktop     | [06f56df636](https://linux-hardware.org/?probe=06f56df636) | May 23, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [719fbbd5a5](https://linux-hardware.org/?probe=719fbbd5a5) | May 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [aa33ddd283](https://linux-hardware.org/?probe=aa33ddd283) | May 23, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [7978c97691](https://linux-hardware.org/?probe=7978c97691) | May 22, 2023 |
| Lenovo        | ThinkPad T490 20N3S4VV00    | Notebook    | [5c190a4d57](https://linux-hardware.org/?probe=5c190a4d57) | May 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0f9deafb62](https://linux-hardware.org/?probe=0f9deafb62) | May 22, 2023 |
| HP            | 18E4                        | Desktop     | [5601900c8b](https://linux-hardware.org/?probe=5601900c8b) | May 22, 2023 |
| Unknown       | DT138IB                     | Desktop     | [130e17f9e3](https://linux-hardware.org/?probe=130e17f9e3) | May 21, 2023 |
| Sony          | VPCF120FD                   | Notebook    | [a438459d06](https://linux-hardware.org/?probe=a438459d06) | May 21, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [1c5c9709dd](https://linux-hardware.org/?probe=1c5c9709dd) | May 21, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Dell          | 0YP9G7 A00                  | Desktop     | [18853bc139](https://linux-hardware.org/?probe=18853bc139) | May 21, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [7815f47a45](https://linux-hardware.org/?probe=7815f47a45) | May 21, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [867806192a](https://linux-hardware.org/?probe=867806192a) | May 21, 2023 |
| Dell          | 0H28RR A07                  | Server      | [1dd21b89e9](https://linux-hardware.org/?probe=1dd21b89e9) | May 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [298317e388](https://linux-hardware.org/?probe=298317e388) | May 21, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [a3a157f327](https://linux-hardware.org/?probe=a3a157f327) | May 21, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [b60db9bc14](https://linux-hardware.org/?probe=b60db9bc14) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [5ae19394fc](https://linux-hardware.org/?probe=5ae19394fc) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [14548bc77a](https://linux-hardware.org/?probe=14548bc77a) | May 20, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b07192ce16](https://linux-hardware.org/?probe=b07192ce16) | May 19, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [e168b46b94](https://linux-hardware.org/?probe=e168b46b94) | May 19, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b001b01a08](https://linux-hardware.org/?probe=b001b01a08) | May 19, 2023 |
| BOSGAME       | B95                         | Notebook    | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| HP            | HDX18                       | Notebook    | [fbfe87f9b5](https://linux-hardware.org/?probe=fbfe87f9b5) | May 19, 2023 |
| HP            | HDX18                       | Notebook    | [a0d050763b](https://linux-hardware.org/?probe=a0d050763b) | May 19, 2023 |
| MSI           | MS-B9311                    | Desktop     | [3cfc1fbb83](https://linux-hardware.org/?probe=3cfc1fbb83) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| HP            | 18E9                        | Desktop     | [2128541eb5](https://linux-hardware.org/?probe=2128541eb5) | May 18, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [e0ebac1371](https://linux-hardware.org/?probe=e0ebac1371) | May 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [a33efd912c](https://linux-hardware.org/?probe=a33efd912c) | May 18, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [85da02478a](https://linux-hardware.org/?probe=85da02478a) | May 17, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [d98feea8ad](https://linux-hardware.org/?probe=d98feea8ad) | May 17, 2023 |
| Acer          | Swift SF316-51              | Notebook    | [663e7fe745](https://linux-hardware.org/?probe=663e7fe745) | May 17, 2023 |
| ASUSTek       | D700SC                      | Desktop     | [eab212a67d](https://linux-hardware.org/?probe=eab212a67d) | May 17, 2023 |
| ASRock        | Z97 Professional            | Desktop     | [7d0ecd3359](https://linux-hardware.org/?probe=7d0ecd3359) | May 17, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [aa87f447d5](https://linux-hardware.org/?probe=aa87f447d5) | May 16, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [c7c487333a](https://linux-hardware.org/?probe=c7c487333a) | May 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [afbef25815](https://linux-hardware.org/?probe=afbef25815) | May 16, 2023 |
| Dell          | Precision 5540              | Notebook    | [a97a05dd0e](https://linux-hardware.org/?probe=a97a05dd0e) | May 16, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [a399b17822](https://linux-hardware.org/?probe=a399b17822) | May 16, 2023 |
| HP            | 18E4                        | Desktop     | [7560196205](https://linux-hardware.org/?probe=7560196205) | May 16, 2023 |
| MSI           | 3664h                       | Desktop     | [b45eee9c3a](https://linux-hardware.org/?probe=b45eee9c3a) | May 16, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [aeb8c0e04f](https://linux-hardware.org/?probe=aeb8c0e04f) | May 16, 2023 |
| Supermicro    | H12DSU-iN                   | Desktop     | [05b2b86f35](https://linux-hardware.org/?probe=05b2b86f35) | May 15, 2023 |
| HP            | 18E9                        | Desktop     | [59a47f84ec](https://linux-hardware.org/?probe=59a47f84ec) | May 15, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [4b60a3d942](https://linux-hardware.org/?probe=4b60a3d942) | May 15, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [5c97b405b5](https://linux-hardware.org/?probe=5c97b405b5) | May 15, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [465488c540](https://linux-hardware.org/?probe=465488c540) | May 15, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [a431f34e2b](https://linux-hardware.org/?probe=a431f34e2b) | May 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [a2c1fd19aa](https://linux-hardware.org/?probe=a2c1fd19aa) | May 14, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [2ab0709f22](https://linux-hardware.org/?probe=2ab0709f22) | May 14, 2023 |
| Acer          | Aspire Z3-705               | All in one  | [1198d368c9](https://linux-hardware.org/?probe=1198d368c9) | May 14, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [7380a83f05](https://linux-hardware.org/?probe=7380a83f05) | May 14, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [1f657b2f59](https://linux-hardware.org/?probe=1f657b2f59) | May 14, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [0f70383aab](https://linux-hardware.org/?probe=0f70383aab) | May 14, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [760b21cf70](https://linux-hardware.org/?probe=760b21cf70) | May 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [413d3b7b92](https://linux-hardware.org/?probe=413d3b7b92) | May 14, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [784de41090](https://linux-hardware.org/?probe=784de41090) | May 14, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e3dedcbd6a](https://linux-hardware.org/?probe=e3dedcbd6a) | May 14, 2023 |
| Dell          | Precision 5540              | Notebook    | [22e1b4dbd4](https://linux-hardware.org/?probe=22e1b4dbd4) | May 14, 2023 |
| Dell          | Latitude 5490               | Notebook    | [57e94dd4b7](https://linux-hardware.org/?probe=57e94dd4b7) | May 14, 2023 |
| HP            | 18E4                        | Desktop     | [4dc91feab7](https://linux-hardware.org/?probe=4dc91feab7) | May 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [59a9ba6e16](https://linux-hardware.org/?probe=59a9ba6e16) | May 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [5ce272e9ee](https://linux-hardware.org/?probe=5ce272e9ee) | May 13, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a69d13961](https://linux-hardware.org/?probe=2a69d13961) | May 13, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [79db0c9b3c](https://linux-hardware.org/?probe=79db0c9b3c) | May 13, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [71f1904bc6](https://linux-hardware.org/?probe=71f1904bc6) | May 13, 2023 |
| Google        | Kled                        | Notebook    | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| Panasonic     | CF-19-8                     | Notebook    | [1aa7d4071a](https://linux-hardware.org/?probe=1aa7d4071a) | May 12, 2023 |
| System76      | Gazelle                     | Notebook    | [83ef9e6d2d](https://linux-hardware.org/?probe=83ef9e6d2d) | May 12, 2023 |
| Samsung       | R430/R480                   | Notebook    | [076f13d198](https://linux-hardware.org/?probe=076f13d198) | May 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [208afe074a](https://linux-hardware.org/?probe=208afe074a) | May 12, 2023 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [0953c12312](https://linux-hardware.org/?probe=0953c12312) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c590339049](https://linux-hardware.org/?probe=c590339049) | May 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [9d7e434968](https://linux-hardware.org/?probe=9d7e434968) | May 12, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [f9a67e4a1f](https://linux-hardware.org/?probe=f9a67e4a1f) | May 11, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [18a4110763](https://linux-hardware.org/?probe=18a4110763) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0ae43bcc58](https://linux-hardware.org/?probe=0ae43bcc58) | May 11, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [96310a4cfe](https://linux-hardware.org/?probe=96310a4cfe) | May 11, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [ed6a0c4e82](https://linux-hardware.org/?probe=ed6a0c4e82) | May 11, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1e4f2a0daf](https://linux-hardware.org/?probe=1e4f2a0daf) | May 10, 2023 |
| HP            | Laptop 17-by2xxx            | Notebook    | [21faeddba9](https://linux-hardware.org/?probe=21faeddba9) | May 10, 2023 |
| Dell          | 0YTPH7 A01                  | All in one  | [e84bcda5c6](https://linux-hardware.org/?probe=e84bcda5c6) | May 10, 2023 |
| Google        | Edgar                       | Notebook    | [372d5c177f](https://linux-hardware.org/?probe=372d5c177f) | May 10, 2023 |
| HP            | 18E4                        | Desktop     | [2a528dc758](https://linux-hardware.org/?probe=2a528dc758) | May 10, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [deecc1260f](https://linux-hardware.org/?probe=deecc1260f) | May 10, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [3a9528f661](https://linux-hardware.org/?probe=3a9528f661) | May 10, 2023 |
| ASRock        | Z97 Extreme4                | Desktop     | [5803f15c1d](https://linux-hardware.org/?probe=5803f15c1d) | May 09, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [baa9914fa3](https://linux-hardware.org/?probe=baa9914fa3) | May 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [64bd100bb5](https://linux-hardware.org/?probe=64bd100bb5) | May 09, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [f173eb5463](https://linux-hardware.org/?probe=f173eb5463) | May 09, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [9726453f00](https://linux-hardware.org/?probe=9726453f00) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [47fea42b65](https://linux-hardware.org/?probe=47fea42b65) | May 09, 2023 |
| Acer          | Aspire TC-1760              | Desktop     | [24664f3383](https://linux-hardware.org/?probe=24664f3383) | May 09, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [eb9f5de2f5](https://linux-hardware.org/?probe=eb9f5de2f5) | May 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [8cc543c6af](https://linux-hardware.org/?probe=8cc543c6af) | May 09, 2023 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [0971c53d86](https://linux-hardware.org/?probe=0971c53d86) | May 09, 2023 |
| HP            | Laptop 15                   | Notebook    | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [c40e865226](https://linux-hardware.org/?probe=c40e865226) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d055c2e022](https://linux-hardware.org/?probe=d055c2e022) | May 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [28a1f44a1e](https://linux-hardware.org/?probe=28a1f44a1e) | May 08, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [baf643f95f](https://linux-hardware.org/?probe=baf643f95f) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [6bc581f37c](https://linux-hardware.org/?probe=6bc581f37c) | May 08, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [69dfa20c09](https://linux-hardware.org/?probe=69dfa20c09) | May 07, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d58e08c9ab](https://linux-hardware.org/?probe=d58e08c9ab) | May 07, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [d5f70fc2eb](https://linux-hardware.org/?probe=d5f70fc2eb) | May 07, 2023 |
| Datto         | SSD                         | Desktop     | [c086218bd4](https://linux-hardware.org/?probe=c086218bd4) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [8c5b603452](https://linux-hardware.org/?probe=8c5b603452) | May 07, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [33b7a6ba7c](https://linux-hardware.org/?probe=33b7a6ba7c) | May 06, 2023 |
| HP            | ENVY TS 17                  | Notebook    | [d18f9c3e77](https://linux-hardware.org/?probe=d18f9c3e77) | May 06, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [ebafddb3f1](https://linux-hardware.org/?probe=ebafddb3f1) | May 06, 2023 |
| Alienware     | 0R3FWM A00                  | Desktop     | [c6dbe0270a](https://linux-hardware.org/?probe=c6dbe0270a) | May 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1143344e93](https://linux-hardware.org/?probe=1143344e93) | May 06, 2023 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [d572509eb2](https://linux-hardware.org/?probe=d572509eb2) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [620d5955bb](https://linux-hardware.org/?probe=620d5955bb) | May 06, 2023 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | Notebook    | [21ef45e81c](https://linux-hardware.org/?probe=21ef45e81c) | May 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [308afd60ea](https://linux-hardware.org/?probe=308afd60ea) | May 06, 2023 |
| GPD           | G1618-04                    | All in one  | [1ac75759ce](https://linux-hardware.org/?probe=1ac75759ce) | May 06, 2023 |
| ASRock        | Z97 Extreme4                | Desktop     | [7b83def3e1](https://linux-hardware.org/?probe=7b83def3e1) | May 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [2f59970cf9](https://linux-hardware.org/?probe=2f59970cf9) | May 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f0bc6ca2dd](https://linux-hardware.org/?probe=f0bc6ca2dd) | May 05, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0da080327f](https://linux-hardware.org/?probe=0da080327f) | May 05, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [6ea350c49d](https://linux-hardware.org/?probe=6ea350c49d) | May 05, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [f688c82ff2](https://linux-hardware.org/?probe=f688c82ff2) | May 05, 2023 |
| Dell          | Latitude 5401               | Notebook    | [671e11d184](https://linux-hardware.org/?probe=671e11d184) | May 05, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [72336867ab](https://linux-hardware.org/?probe=72336867ab) | May 04, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [44c5b43b8d](https://linux-hardware.org/?probe=44c5b43b8d) | May 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e49682836a](https://linux-hardware.org/?probe=e49682836a) | May 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [424f0dca9d](https://linux-hardware.org/?probe=424f0dca9d) | May 04, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [1c26fc22d1](https://linux-hardware.org/?probe=1c26fc22d1) | May 04, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [6a70490cd6](https://linux-hardware.org/?probe=6a70490cd6) | May 03, 2023 |
| HP            | 18E4                        | Desktop     | [d1344e36dd](https://linux-hardware.org/?probe=d1344e36dd) | May 03, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [f677ec7e51](https://linux-hardware.org/?probe=f677ec7e51) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [ee72f0090b](https://linux-hardware.org/?probe=ee72f0090b) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [6d2d5b74d2](https://linux-hardware.org/?probe=6d2d5b74d2) | May 03, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [7beeddc27c](https://linux-hardware.org/?probe=7beeddc27c) | May 03, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| HP            | 198E                        | Desktop     | [9c02a85763](https://linux-hardware.org/?probe=9c02a85763) | May 02, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [6f015f949c](https://linux-hardware.org/?probe=6f015f949c) | May 02, 2023 |
| Dell          | 0D735T A00                  | Desktop     | [3070f4e7da](https://linux-hardware.org/?probe=3070f4e7da) | May 02, 2023 |
| Google        | Kip                         | Notebook    | [19b726ec68](https://linux-hardware.org/?probe=19b726ec68) | May 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [9cee4296b5](https://linux-hardware.org/?probe=9cee4296b5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [a9406a1851](https://linux-hardware.org/?probe=a9406a1851) | May 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2849b9a200](https://linux-hardware.org/?probe=2849b9a200) | May 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [1362f2e3df](https://linux-hardware.org/?probe=1362f2e3df) | May 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ecc18e59bc](https://linux-hardware.org/?probe=ecc18e59bc) | May 01, 2023 |
| HP            | 3031h                       | Desktop     | [84140549cd](https://linux-hardware.org/?probe=84140549cd) | May 01, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [5c00e2d415](https://linux-hardware.org/?probe=5c00e2d415) | May 01, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [b293ade39d](https://linux-hardware.org/?probe=b293ade39d) | May 01, 2023 |
| Lenovo        | ThinkCentre M71e 5033A1U    | Desktop     | [2e39bbf0cf](https://linux-hardware.org/?probe=2e39bbf0cf) | May 01, 2023 |
| HP            | 3033h                       | Desktop     | [31a4e00c60](https://linux-hardware.org/?probe=31a4e00c60) | May 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [5b8daf89b4](https://linux-hardware.org/?probe=5b8daf89b4) | May 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [0f39841ca1](https://linux-hardware.org/?probe=0f39841ca1) | May 01, 2023 |
| HP            | 3648h                       | Desktop     | [38ab69c4e2](https://linux-hardware.org/?probe=38ab69c4e2) | May 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [1605338d8f](https://linux-hardware.org/?probe=1605338d8f) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [e89da96576](https://linux-hardware.org/?probe=e89da96576) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0aa06876c7](https://linux-hardware.org/?probe=0aa06876c7) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Alienware     | m17 R5 AMD                  | Notebook    | [4e665db2b1](https://linux-hardware.org/?probe=4e665db2b1) | May 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [45dad4b8e9](https://linux-hardware.org/?probe=45dad4b8e9) | May 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [34e7df2c84](https://linux-hardware.org/?probe=34e7df2c84) | May 01, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [457abef5d3](https://linux-hardware.org/?probe=457abef5d3) | May 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2a2bf698ed](https://linux-hardware.org/?probe=2a2bf698ed) | May 01, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [a3c89effff](https://linux-hardware.org/?probe=a3c89effff) | May 01, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [1f1cb63edc](https://linux-hardware.org/?probe=1f1cb63edc) | May 01, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [1298b74530](https://linux-hardware.org/?probe=1298b74530) | Apr 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [3695c070f9](https://linux-hardware.org/?probe=3695c070f9) | Apr 30, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [f1db72cddb](https://linux-hardware.org/?probe=f1db72cddb) | Apr 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f46e9f6ba7](https://linux-hardware.org/?probe=f46e9f6ba7) | Apr 30, 2023 |
| HP            | 828A                        | Desktop     | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [a5fbe31c54](https://linux-hardware.org/?probe=a5fbe31c54) | Apr 30, 2023 |
| HP            | 18E4                        | Desktop     | [da858ea464](https://linux-hardware.org/?probe=da858ea464) | Apr 30, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e59a8bf7d1](https://linux-hardware.org/?probe=e59a8bf7d1) | Apr 30, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [c2e2e1d130](https://linux-hardware.org/?probe=c2e2e1d130) | Apr 30, 2023 |
| Acer          | Aspire Z5600                | All in one  | [8a9edf5a44](https://linux-hardware.org/?probe=8a9edf5a44) | Apr 29, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | Notebook    | [2545d9dd31](https://linux-hardware.org/?probe=2545d9dd31) | Apr 29, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [1d00cc1f78](https://linux-hardware.org/?probe=1d00cc1f78) | Apr 29, 2023 |
| Lenovo        | XXXX 3000 H210              | Desktop     | [96644846f5](https://linux-hardware.org/?probe=96644846f5) | Apr 29, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [9a9fdf0dd3](https://linux-hardware.org/?probe=9a9fdf0dd3) | Apr 29, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [59b9a9ceb3](https://linux-hardware.org/?probe=59b9a9ceb3) | Apr 29, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [033718212c](https://linux-hardware.org/?probe=033718212c) | Apr 28, 2023 |
| HP            | G62                         | Notebook    | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| ASUSTek       | N550JX                      | Notebook    | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| HP            | Pavilion dv7                | Notebook    | [346cbe0e48](https://linux-hardware.org/?probe=346cbe0e48) | Apr 28, 2023 |
| HP            | Pavilion dv7                | Notebook    | [afafdbce36](https://linux-hardware.org/?probe=afafdbce36) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f1679a62d0](https://linux-hardware.org/?probe=f1679a62d0) | Apr 28, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3342a295e8](https://linux-hardware.org/?probe=3342a295e8) | Apr 28, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [38c117ee87](https://linux-hardware.org/?probe=38c117ee87) | Apr 28, 2023 |
| ASRock        | H170A-X1                    | Desktop     | [a89448e417](https://linux-hardware.org/?probe=a89448e417) | Apr 28, 2023 |
| Dell          | 0XNNCJ A03                  | Server      | [ad555bfde2](https://linux-hardware.org/?probe=ad555bfde2) | Apr 27, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [49033dd76c](https://linux-hardware.org/?probe=49033dd76c) | Apr 27, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [ce35b62e32](https://linux-hardware.org/?probe=ce35b62e32) | Apr 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9fdfb825c7](https://linux-hardware.org/?probe=9fdfb825c7) | Apr 27, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [f3b21405ff](https://linux-hardware.org/?probe=f3b21405ff) | Apr 27, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [4363ca582a](https://linux-hardware.org/?probe=4363ca582a) | Apr 26, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [f5de49d5b3](https://linux-hardware.org/?probe=f5de49d5b3) | Apr 26, 2023 |
| HP            | 8309                        | Desktop     | [cde28bd710](https://linux-hardware.org/?probe=cde28bd710) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [96006a1098](https://linux-hardware.org/?probe=96006a1098) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [a3df65a55c](https://linux-hardware.org/?probe=a3df65a55c) | Apr 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b24f39801d](https://linux-hardware.org/?probe=b24f39801d) | Apr 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| Acer          | Swift SF313-53              | Notebook    | [b487229ea2](https://linux-hardware.org/?probe=b487229ea2) | Apr 25, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7967ed6e8f](https://linux-hardware.org/?probe=7967ed6e8f) | Apr 25, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [c897ecd954](https://linux-hardware.org/?probe=c897ecd954) | Apr 25, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e8318168c4](https://linux-hardware.org/?probe=e8318168c4) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [cc14ce03b0](https://linux-hardware.org/?probe=cc14ce03b0) | Apr 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f878b7d23a](https://linux-hardware.org/?probe=f878b7d23a) | Apr 25, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [135216cc27](https://linux-hardware.org/?probe=135216cc27) | Apr 25, 2023 |
| Acer          | Spin SP513-52N              | Convertible | [bdab97deeb](https://linux-hardware.org/?probe=bdab97deeb) | Apr 25, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [0cfe2b34f5](https://linux-hardware.org/?probe=0cfe2b34f5) | Apr 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [d9ad034d8c](https://linux-hardware.org/?probe=d9ad034d8c) | Apr 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b72361ca9e](https://linux-hardware.org/?probe=b72361ca9e) | Apr 24, 2023 |
| Alienware     | 13 R2                       | Notebook    | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [6531aafbfe](https://linux-hardware.org/?probe=6531aafbfe) | Apr 24, 2023 |
| Acer          | Aspire V5-552P              | Notebook    | [28c276f9da](https://linux-hardware.org/?probe=28c276f9da) | Apr 23, 2023 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [06859fe586](https://linux-hardware.org/?probe=06859fe586) | Apr 23, 2023 |
| HP            | Pavilion dv7                | Notebook    | [0ca422761e](https://linux-hardware.org/?probe=0ca422761e) | Apr 23, 2023 |
| HP            | Pavilion dv7                | Notebook    | [8b90982317](https://linux-hardware.org/?probe=8b90982317) | Apr 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [db614f561e](https://linux-hardware.org/?probe=db614f561e) | Apr 23, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [3321ccb912](https://linux-hardware.org/?probe=3321ccb912) | Apr 23, 2023 |
| Google        | Kefka                       | Notebook    | [2802d83837](https://linux-hardware.org/?probe=2802d83837) | Apr 23, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [cd11cc0e25](https://linux-hardware.org/?probe=cd11cc0e25) | Apr 23, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [acb9cde3d7](https://linux-hardware.org/?probe=acb9cde3d7) | Apr 23, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [9a0f95336c](https://linux-hardware.org/?probe=9a0f95336c) | Apr 23, 2023 |
| ASUSTek       | P8H77-I                     | Desktop     | [e2276c080b](https://linux-hardware.org/?probe=e2276c080b) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [ea9dd842c0](https://linux-hardware.org/?probe=ea9dd842c0) | Apr 22, 2023 |
| ASUSTek       | Zenbook UP6502ZD_UP6502Z... | Convertible | [9cd180c75a](https://linux-hardware.org/?probe=9cd180c75a) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [63599179ae](https://linux-hardware.org/?probe=63599179ae) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | Notebook    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [06bc639254](https://linux-hardware.org/?probe=06bc639254) | Apr 22, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [5eb2235e10](https://linux-hardware.org/?probe=5eb2235e10) | Apr 22, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [cc1233b9b9](https://linux-hardware.org/?probe=cc1233b9b9) | Apr 21, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [15cc4335c7](https://linux-hardware.org/?probe=15cc4335c7) | Apr 21, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [84a6fd49fa](https://linux-hardware.org/?probe=84a6fd49fa) | Apr 21, 2023 |
| HP            | 1905                        | Desktop     | [9e047f751d](https://linux-hardware.org/?probe=9e047f751d) | Apr 21, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [f2f6b7ab4e](https://linux-hardware.org/?probe=f2f6b7ab4e) | Apr 21, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [97eec10e18](https://linux-hardware.org/?probe=97eec10e18) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [f1345bd185](https://linux-hardware.org/?probe=f1345bd185) | Apr 21, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [8e7095e453](https://linux-hardware.org/?probe=8e7095e453) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [44459cbe3a](https://linux-hardware.org/?probe=44459cbe3a) | Apr 20, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6b5cc099a0](https://linux-hardware.org/?probe=6b5cc099a0) | Apr 20, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [1383ab9981](https://linux-hardware.org/?probe=1383ab9981) | Apr 20, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3e1880b375](https://linux-hardware.org/?probe=3e1880b375) | Apr 20, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f83e11ca39](https://linux-hardware.org/?probe=f83e11ca39) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [7310d7f91b](https://linux-hardware.org/?probe=7310d7f91b) | Apr 19, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [cc76c44731](https://linux-hardware.org/?probe=cc76c44731) | Apr 19, 2023 |
| HP            | Pavilion dv7                | Notebook    | [f5c84d7a1b](https://linux-hardware.org/?probe=f5c84d7a1b) | Apr 19, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [86e2d42f73](https://linux-hardware.org/?probe=86e2d42f73) | Apr 19, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [748e08d7c7](https://linux-hardware.org/?probe=748e08d7c7) | Apr 19, 2023 |
| Intel         | DH61AG AAG23736-504         | Desktop     | [9a853b9c86](https://linux-hardware.org/?probe=9a853b9c86) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [1a5add814c](https://linux-hardware.org/?probe=1a5add814c) | Apr 18, 2023 |
| Dell          | Latitude E5550              | Notebook    | [ce824f113c](https://linux-hardware.org/?probe=ce824f113c) | Apr 18, 2023 |
| Dell          | Latitude E5550              | Notebook    | [7611d6e018](https://linux-hardware.org/?probe=7611d6e018) | Apr 18, 2023 |
| Dell          | 0KRC95 A00                  | Desktop     | [99ea2c7790](https://linux-hardware.org/?probe=99ea2c7790) | Apr 18, 2023 |
| Lenovo        | ThinkPad Edge 031946U       | Notebook    | [f9d813509a](https://linux-hardware.org/?probe=f9d813509a) | Apr 18, 2023 |
| Dell          | 0XHYJF A00                  | All in one  | [9348834e54](https://linux-hardware.org/?probe=9348834e54) | Apr 18, 2023 |
| Dell          | 0XHYJF A00                  | All in one  | [c8804b1836](https://linux-hardware.org/?probe=c8804b1836) | Apr 18, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 816       | 12.88%  |
| Ubuntu 18.04       | 423       | 6.68%   |
| Ubuntu 22.04       | 335       | 5.29%   |
| Pop!_OS 22.04      | 146       | 2.3%    |
| Debian 11          | 135       | 2.13%   |
| Linux Mint 20.3    | 119       | 1.88%   |
| OpenMandriva 4.3   | 118       | 1.86%   |
| Zorin 16           | 117       | 1.85%   |
| OpenMandriva 4.2   | 116       | 1.83%   |
| Arch Rolling       | 111       | 1.75%   |
| Manjaro            | 104       | 1.64%   |
| KDE neon 20.04     | 100       | 1.58%   |
| Xubuntu 20.04      | 97        | 1.53%   |
| ArcoLinux Rolling  | 91        | 1.44%   |
| Pop!_OS 20.04      | 89        | 1.4%    |
| Pop!_OS 21.04      | 84        | 1.33%   |
| Linux Mint 21.1    | 82        | 1.29%   |
| Arch               | 80        | 1.26%   |
| Linux Mint 20.1    | 78        | 1.23%   |
| Fedora 38          | 78        | 1.23%   |
| Linux Mint 19.3    | 76        | 1.2%    |
| Ubuntu 19.10       | 71        | 1.12%   |
| Zorin 15           | 69        | 1.09%   |
| Ubuntu 21.10       | 69        | 1.09%   |
| Fedora 35          | 68        | 1.07%   |
| Ubuntu 20.10       | 67        | 1.06%   |
| OpenMandriva 23.01 | 67        | 1.06%   |
| Pop!_OS 20.10      | 65        | 1.03%   |
| Linux Mint 20.2    | 65        | 1.03%   |
| Fedora 33          | 65        | 1.03%   |
| Fedora 37          | 62        | 0.98%   |
| OpenMandriva 23.03 | 61        | 0.96%   |
| Linux Mint 20      | 60        | 0.95%   |
| Ubuntu 22.10       | 57        | 0.9%    |
| Fedora 32          | 56        | 0.88%   |
| Ubuntu 21.04       | 53        | 0.84%   |
| Linux Mint 21      | 51        | 0.8%    |
| Fedora 34          | 51        | 0.8%    |
| Ubuntu 23.04       | 50        | 0.79%   |
| Ubuntu 19.04       | 48        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1940      | 32.4%   |
| Linux Mint    | 548       | 9.15%   |
| Fedora        | 420       | 7.01%   |
| Pop!_OS       | 415       | 6.93%   |
| OpenMandriva  | 414       | 6.91%   |
| Debian        | 244       | 4.07%   |
| Manjaro       | 223       | 3.72%   |
| Zorin         | 195       | 3.26%   |
| Arch          | 185       | 3.09%   |
| Xubuntu       | 158       | 2.64%   |
| KDE neon      | 136       | 2.27%   |
| Kubuntu       | 104       | 1.74%   |
| ArcoLinux     | 97        | 1.62%   |
| ROSA          | 76        | 1.27%   |
| Gentoo        | 61        | 1.02%   |
| openSUSE      | 52        | 0.87%   |
| Elementary    | 51        | 0.85%   |
| EndeavourOS   | 46        | 0.77%   |
| SteamOS       | 40        | 0.67%   |
| Lubuntu       | 38        | 0.63%   |
| Endless       | 36        | 0.6%    |
| Ubuntu MATE   | 33        | 0.55%   |
| Kali          | 30        | 0.5%    |
| Ubuntu Unity  | 28        | 0.47%   |
| Clear Linux   | 28        | 0.47%   |
| CentOS        | 28        | 0.47%   |
| BlackPanther  | 28        | 0.47%   |
| MX            | 27        | 0.45%   |
| LMDE          | 25        | 0.42%   |
| Garuda Linux  | 23        | 0.38%   |
| Ubuntu Budgie | 22        | 0.37%   |
| Nobara        | 18        | 0.3%    |
| Alpine        | 12        | 0.2%    |
| Peppermint    | 11        | 0.18%   |
| Parrot        | 11        | 0.18%   |
| LinuxFX       | 11        | 0.18%   |
| Rocky Linux   | 9         | 0.15%   |
| RHEL          | 9         | 0.15%   |
| Raspbian      | 9         | 0.15%   |
| Xero          | 8         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 113       | 1.6%    |
| 5.16.7-desktop-1omv4003  | 111       | 1.57%   |
| 5.4.0-42-generic         | 92        | 1.3%    |
| 5.15.0-56-generic        | 69        | 0.98%   |
| 6.1.1-desktop-1omv2290   | 61        | 0.86%   |
| 6.2.6-desktop-1omv2390   | 59        | 0.84%   |
| 5.11.0-27-generic        | 59        | 0.84%   |
| 5.15.0-58-generic        | 56        | 0.79%   |
| 5.4.0-58-generic         | 53        | 0.75%   |
| 5.4.0-48-generic         | 50        | 0.71%   |
| 5.3.0-40-generic         | 50        | 0.71%   |
| 5.15.0-52-generic        | 45        | 0.64%   |
| 5.4.0-52-generic         | 44        | 0.62%   |
| 5.4.0-29-generic         | 43        | 0.61%   |
| 5.8.0-7630-generic       | 42        | 0.59%   |
| 5.11.0-40-generic        | 42        | 0.59%   |
| 5.4.0-40-generic         | 38        | 0.54%   |
| 5.0.0-37-generic         | 38        | 0.54%   |
| 5.4.0-26-generic         | 36        | 0.51%   |
| 5.13.0-39-generic        | 36        | 0.51%   |
| 6.2.0-26-generic         | 35        | 0.5%    |
| 5.4.0-54-generic         | 35        | 0.5%    |
| 5.3.0-46-generic         | 35        | 0.5%    |
| 5.15.0-48-generic        | 35        | 0.5%    |
| 6.2.6-76060206-generic   | 34        | 0.48%   |
| 5.15.0-47-generic        | 33        | 0.47%   |
| 5.15.0-41-generic        | 33        | 0.47%   |
| 5.11.0-7620-generic      | 33        | 0.47%   |
| 5.4.0-37-generic         | 32        | 0.45%   |
| 5.8.0-50-generic         | 31        | 0.44%   |
| 5.4.0-66-generic         | 30        | 0.42%   |
| 5.15.0-46-generic        | 30        | 0.42%   |
| 6.2.0-20-generic         | 29        | 0.41%   |
| 5.4.0-45-generic         | 29        | 0.41%   |
| 5.15.0-69-generic        | 28        | 0.4%    |
| 5.4.0-47-generic         | 27        | 0.38%   |
| 5.15.0-60-generic        | 27        | 0.38%   |
| 5.11.0-38-generic        | 27        | 0.38%   |
| 5.4.0-91-generic         | 26        | 0.37%   |
| 5.4.0-7634-generic       | 26        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1075      | 16.29%  |
| 5.15.0  | 545       | 8.26%   |
| 5.11.0  | 353       | 5.35%   |
| 5.8.0   | 338       | 5.12%   |
| 4.15.0  | 322       | 4.88%   |
| 5.13.0  | 319       | 4.83%   |
| 5.3.0   | 272       | 4.12%   |
| 5.19.0  | 208       | 3.15%   |
| 5.0.0   | 151       | 2.29%   |
| 5.10.0  | 143       | 2.17%   |
| 5.10.14 | 115       | 1.74%   |
| 5.16.7  | 113       | 1.71%   |
| 4.18.0  | 110       | 1.67%   |
| 6.2.6   | 99        | 1.5%    |
| 6.2.0   | 94        | 1.42%   |
| 6.1.1   | 69        | 1.05%   |
| 6.1.0   | 47        | 0.71%   |
| 4.19.0  | 43        | 0.65%   |
| 6.4.11  | 31        | 0.47%   |
| 6.0.12  | 30        | 0.45%   |
| 6.0.0   | 28        | 0.42%   |
| 5.14.0  | 28        | 0.42%   |
| 6.0.6   | 27        | 0.41%   |
| 5.17.5  | 26        | 0.39%   |
| 6.2.9   | 23        | 0.35%   |
| 5.15.5  | 23        | 0.35%   |
| 4.18.16 | 23        | 0.35%   |
| 4.9.20  | 20        | 0.3%    |
| 4.4.0   | 19        | 0.29%   |
| 6.3.5   | 18        | 0.27%   |
| 4.9.60  | 17        | 0.26%   |
| 5.18.0  | 16        | 0.24%   |
| 5.12.4  | 16        | 0.24%   |
| 5.16.0  | 15        | 0.23%   |
| 5.15.11 | 15        | 0.23%   |
| 6.4.8   | 14        | 0.21%   |
| 6.2.10  | 14        | 0.21%   |
| 5.9.16  | 14        | 0.21%   |
| 5.9.11  | 14        | 0.21%   |
| 5.17.9  | 14        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1165      | 17.96%  |
| 5.15    | 733       | 11.3%   |
| 5.8     | 432       | 6.66%   |
| 5.11    | 408       | 6.29%   |
| 5.13    | 374       | 5.77%   |
| 5.10    | 366       | 5.64%   |
| 4.15    | 323       | 4.98%   |
| 6.2     | 295       | 4.55%   |
| 5.3     | 294       | 4.53%   |
| 5.19    | 267       | 4.12%   |
| 5.16    | 219       | 3.38%   |
| 6.1     | 204       | 3.15%   |
| 5.0     | 160       | 2.47%   |
| 6.0     | 152       | 2.34%   |
| 4.18    | 133       | 2.05%   |
| 6.4     | 100       | 1.54%   |
| 5.17    | 98        | 1.51%   |
| 6.3     | 94        | 1.45%   |
| 5.14    | 86        | 1.33%   |
| 5.9     | 84        | 1.3%    |
| 5.18    | 75        | 1.16%   |
| 5.12    | 72        | 1.11%   |
| 4.9     | 66        | 1.02%   |
| 5.6     | 61        | 0.94%   |
| 4.19    | 58        | 0.89%   |
| 5.7     | 51        | 0.79%   |
| 5.5     | 29        | 0.45%   |
| 4.4     | 23        | 0.35%   |
| 3.10    | 16        | 0.25%   |
| 5.2     | 11        | 0.17%   |
| 4.1     | 6         | 0.09%   |
| 6.5     | 5         | 0.08%   |
| 4.13    | 5         | 0.08%   |
| 5.1     | 4         | 0.06%   |
| 4.14    | 3         | 0.05%   |
| 4.8     | 2         | 0.03%   |
| 4.20    | 2         | 0.03%   |
| 4.16    | 2         | 0.03%   |
| 4.12    | 2         | 0.03%   |
| Unknown | 2         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5541      | 96.77%  |
| i686    | 118       | 2.06%   |
| aarch64 | 44        | 0.77%   |
| armv7l  | 19        | 0.33%   |
| mips64  | 2         | 0.03%   |
| armv8l  | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| GNOME                | 2635      | 43.78%  |
| KDE5                 | 1011      | 16.8%   |
| Unknown              | 739       | 12.28%  |
| X-Cinnamon           | 451       | 7.49%   |
| XFCE                 | 426       | 7.08%   |
| KDE                  | 146       | 2.43%   |
| MATE                 | 134       | 2.23%   |
| Cinnamon             | 73        | 1.21%   |
| KDE4                 | 57        | 0.95%   |
| LXQt                 | 50        | 0.83%   |
| Pantheon             | 48        | 0.8%    |
| i3                   | 43        | 0.71%   |
| Budgie               | 34        | 0.56%   |
| LXDE                 | 32        | 0.53%   |
| Unity                | 31        | 0.52%   |
| GNOME Flashback      | 21        | 0.35%   |
| Deepin               | 14        | 0.23%   |
| GNOME Classic        | 10        | 0.17%   |
| DWM                  | 8         | 0.13%   |
| qtile                | 7         | 0.12%   |
| awesome              | 7         | 0.12%   |
| sway                 | 6         | 0.1%    |
| Openbox              | 5         | 0.08%   |
| Hyprland             | 5         | 0.08%   |
| Enlightenment        | 4         | 0.07%   |
| xmonad               | 3         | 0.05%   |
| lightdm-xsession     | 2         | 0.03%   |
| chadwm               | 2         | 0.03%   |
| bspwm                | 2         | 0.03%   |
| xsession             | 1         | 0.02%   |
| wmaker-common        | 1         | 0.02%   |
| ubuntustudio         | 1         | 0.02%   |
| trinity              | 1         | 0.02%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.02%   |
| spectrwm             | 1         | 0.02%   |
| river                | 1         | 0.02%   |
| Lubuntu              | 1         | 0.02%   |
| LeftWM               | 1         | 0.02%   |
| Jwm                  | 1         | 0.02%   |
| herbstluftwm         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4465      | 75.52%  |
| Wayland | 922       | 15.6%   |
| Unknown | 372       | 6.29%   |
| Tty     | 148       | 2.5%    |
| Web     | 5         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3147      | 52.63%  |
| SDDM    | 869       | 14.53%  |
| GDM3    | 624       | 10.43%  |
| GDM     | 592       | 9.9%    |
| LightDM | 519       | 8.68%   |
| TDM     | 142       | 2.37%   |
| KDM     | 51        | 0.85%   |
| XDM     | 13        | 0.22%   |
| SLiM    | 7         | 0.12%   |
| Ly      | 6         | 0.1%    |
| LXDM    | 5         | 0.08%   |
| GREETD  | 2         | 0.03%   |
| NODM    | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| LY-DM   | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_CA      | 3047      | 51.33%  |
| en_US      | 1601      | 26.97%  |
| Unknown    | 582       | 9.8%    |
| fr_CA      | 404       | 6.81%   |
| C          | 128       | 2.16%   |
| fr_FR      | 61        | 1.03%   |
| en_GB      | 35        | 0.59%   |
| en_AU      | 9         | 0.15%   |
| POSIX      | 8         | 0.13%   |
| C.UTF8     | 7         | 0.12%   |
| zh_CN      | 4         | 0.07%   |
| pt_BR      | 4         | 0.07%   |
| hu_HU      | 4         | 0.07%   |
| es_ES      | 4         | 0.07%   |
| en_IN      | 4         | 0.07%   |
| zh_TW      | 3         | 0.05%   |
| uk_UA      | 3         | 0.05%   |
| ru_RU      | 3         | 0.05%   |
| pa_IN      | 3         | 0.05%   |
| de_DE      | 3         | 0.05%   |
| pl_PL      | 2         | 0.03%   |
| ro_RO      | 1         | 0.02%   |
| nan_TW     | 1         | 0.02%   |
| iu_CA      | 1         | 0.02%   |
| hr_HR      | 1         | 0.02%   |
| ga_IE      | 1         | 0.02%   |
| es_CL      | 1         | 0.02%   |
| es_BO      | 1         | 0.02%   |
| en_ZM      | 1         | 0.02%   |
| en_ZA      | 1         | 0.02%   |
| en_US.UTF8 | 1         | 0.02%   |
| en_NZ      | 1         | 0.02%   |
| en_IE      | 1         | 0.02%   |
| en_FI      | 1         | 0.02%   |
| en_DK      | 1         | 0.02%   |
| de_CH      | 1         | 0.02%   |
| co_FR      | 1         | 0.02%   |
| ar_EG      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3139      | 53.37%  |
| EFI  | 2743      | 46.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 4340      | 73.51%  |
| Btrfs   | 588       | 9.96%   |
| Overlay | 489       | 8.28%   |
| Unknown | 177       | 3%      |
| Tmpfs   | 107       | 1.81%   |
| Xfs     | 96        | 1.63%   |
| Zfs     | 57        | 0.97%   |
| Ext2    | 19        | 0.32%   |
| Ext3    | 10        | 0.17%   |
| F2fs    | 9         | 0.15%   |
| Aufs    | 8         | 0.14%   |
| Jfs     | 2         | 0.03%   |
| XXX4    | 1         | 0.02%   |
| Rootfs  | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3203      | 54.39%  |
| GPT     | 2098      | 35.63%  |
| MBR     | 588       | 9.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4921      | 83.88%  |
| Yes       | 946       | 16.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4289      | 73.33%  |
| Yes       | 1560      | 26.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1074      | 18.78%  |
| Dell                    | 830       | 14.51%  |
| Lenovo                  | 765       | 13.37%  |
| Hewlett-Packard         | 707       | 12.36%  |
| Acer                    | 406       | 7.1%    |
| MSI                     | 371       | 6.49%   |
| Gigabyte Technology     | 335       | 5.86%   |
| Apple                   | 202       | 3.53%   |
| ASRock                  | 151       | 2.64%   |
| Toshiba                 | 103       | 1.8%    |
| Intel                   | 84        | 1.47%   |
| Alienware               | 41        | 0.72%   |
| Raspberry Pi Foundation | 38        | 0.66%   |
| Sony                    | 37        | 0.65%   |
| Microsoft               | 37        | 0.65%   |
| Unknown                 | 37        | 0.65%   |
| Valve                   | 35        | 0.61%   |
| Google                  | 35        | 0.61%   |
| Pegatron                | 31        | 0.54%   |
| Supermicro              | 30        | 0.52%   |
| Gateway                 | 30        | 0.52%   |
| Samsung Electronics     | 28        | 0.49%   |
| Foxconn                 | 26        | 0.45%   |
| System76                | 24        | 0.42%   |
| AZW                     | 20        | 0.35%   |
| Panasonic               | 19        | 0.33%   |
| ECS                     | 12        | 0.21%   |
| Biostar                 | 11        | 0.19%   |
| ZOTAC                   | 9         | 0.16%   |
| Fujitsu                 | 9         | 0.16%   |
| Razer                   | 8         | 0.14%   |
| Framework               | 8         | 0.14%   |
| ASRockRack              | 6         | 0.1%    |
| AMI                     | 6         | 0.1%    |
| Notebook                | 5         | 0.09%   |
| LG Electronics          | 5         | 0.09%   |
| HUAWEI                  | 5         | 0.09%   |
| Fanless Mini PC         | 5         | 0.09%   |
| EVGA                    | 5         | 0.09%   |
| eMachines               | 5         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 66        | 1.15%   |
| Unknown                            | 49        | 0.86%   |
| Valve Jupiter                      | 35        | 0.61%   |
| ASUS TUF Gaming X570-PLUS          | 24        | 0.42%   |
| HP Notebook                        | 23        | 0.4%    |
| HP Pavilion g6                     | 19        | 0.33%   |
| MSI MS-7C37                        | 15        | 0.26%   |
| Acer Aspire A315-21                | 15        | 0.26%   |
| Dell OptiPlex 790                  | 14        | 0.24%   |
| Dell Latitude E6420                | 14        | 0.24%   |
| ASUS PRIME B450M-A                 | 14        | 0.24%   |
| Apple iMac8,1                      | 14        | 0.24%   |
| MSI MS-7C02                        | 13        | 0.23%   |
| Dell XPS 15 7590                   | 13        | 0.23%   |
| Dell Latitude E6410                | 13        | 0.23%   |
| ASRock B450M Pro4                  | 13        | 0.23%   |
| RPi Raspberry Pi                   | 12        | 0.21%   |
| MSI MS-7C95                        | 12        | 0.21%   |
| HP Z400 Workstation                | 12        | 0.21%   |
| HP Pavilion dv6                    | 12        | 0.21%   |
| Dell XPS 15 9500                   | 12        | 0.21%   |
| Apple MacBookPro8,1                | 12        | 0.21%   |
| MSI MS-7C56                        | 11        | 0.19%   |
| HP Pavilion 15                     | 11        | 0.19%   |
| Dell OptiPlex 7010                 | 11        | 0.19%   |
| Apple MacBookPro9,2                | 11        | 0.19%   |
| Apple iMac7,1                      | 11        | 0.19%   |
| MSI MS-7C84                        | 10        | 0.17%   |
| HP Pavilion Notebook               | 10        | 0.17%   |
| HP EliteBook 8460p                 | 10        | 0.17%   |
| Dell OptiPlex 9020                 | 10        | 0.17%   |
| Dell OptiPlex 780                  | 10        | 0.17%   |
| ASUS TP410UAR                      | 10        | 0.17%   |
| ASUS ROG STRIX B450-F GAMING       | 10        | 0.17%   |
| ASUS M5A97 R2.0                    | 10        | 0.17%   |
| ASUS M5A97 LE R2.0                 | 10        | 0.17%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 9         | 0.16%   |
| MSI MS-7C91                        | 9         | 0.16%   |
| MSI MS-7693                        | 9         | 0.16%   |
| Gigabyte B450 AORUS PRO WIFI       | 9         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 381       | 6.66%   |
| Acer Aspire         | 317       | 5.54%   |
| Dell Latitude       | 186       | 3.25%   |
| Dell Inspiron       | 174       | 3.04%   |
| Dell XPS            | 148       | 2.59%   |
| Dell OptiPlex       | 133       | 2.33%   |
| ASUS PRIME          | 132       | 2.31%   |
| ASUS ROG            | 129       | 2.26%   |
| HP Pavilion         | 127       | 2.22%   |
| Lenovo ThinkCentre  | 122       | 2.13%   |
| Lenovo IdeaPad      | 94        | 1.64%   |
| HP Compaq           | 93        | 1.63%   |
| HP EliteBook        | 91        | 1.59%   |
| Toshiba Satellite   | 87        | 1.52%   |
| ASUS VivoBook       | 71        | 1.24%   |
| Dell Precision      | 67        | 1.17%   |
| ASUS TUF            | 67        | 1.17%   |
| ASUS All            | 66        | 1.15%   |
| HP Laptop           | 59        | 1.03%   |
| Unknown             | 49        | 0.86%   |
| HP ProBook          | 46        | 0.8%    |
| HP ENVY             | 46        | 0.8%    |
| RPi Raspberry       | 38        | 0.66%   |
| Microsoft Surface   | 37        | 0.65%   |
| Valve Jupiter       | 35        | 0.61%   |
| Dell Vostro         | 32        | 0.56%   |
| Gigabyte X570       | 31        | 0.54%   |
| ASUS ZenBook        | 31        | 0.54%   |
| HP EliteDesk        | 29        | 0.51%   |
| Dell Studio         | 28        | 0.49%   |
| Lenovo Yoga         | 26        | 0.45%   |
| ASUS M5A97          | 25        | 0.44%   |
| Lenovo Legion       | 24        | 0.42%   |
| HP Notebook         | 23        | 0.4%    |
| Acer Swift          | 23        | 0.4%    |
| Gigabyte B450       | 22        | 0.38%   |
| Acer Nitro          | 22        | 0.38%   |
| Dell PowerEdge      | 21        | 0.37%   |
| Lenovo ThinkStation | 20        | 0.35%   |
| ASRock B450M        | 20        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 504       | 8.81%   |
| 2020    | 496       | 8.67%   |
| 2012    | 485       | 8.48%   |
| 2019    | 471       | 8.23%   |
| 2011    | 458       | 8.01%   |
| 2013    | 399       | 6.98%   |
| 2017    | 360       | 6.29%   |
| 2014    | 330       | 5.77%   |
| 2010    | 323       | 5.65%   |
| 2021    | 283       | 4.95%   |
| 2008    | 271       | 4.74%   |
| 2016    | 262       | 4.58%   |
| 2015    | 245       | 4.28%   |
| 2022    | 243       | 4.25%   |
| 2009    | 235       | 4.11%   |
| 2007    | 170       | 2.97%   |
| 2006    | 72        | 1.26%   |
| Unknown | 49        | 0.86%   |
| 2023    | 34        | 0.59%   |
| 2005    | 23        | 0.4%    |
| 2004    | 6         | 0.1%    |
| 2003    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2655      | 46.42%  |
| Desktop        | 2539      | 44.39%  |
| Convertible    | 161       | 2.81%   |
| All in one     | 108       | 1.89%   |
| Mini pc        | 79        | 1.38%   |
| Server         | 68        | 1.19%   |
| System on chip | 55        | 0.96%   |
| Tablet         | 52        | 0.91%   |
| Phone          | 3         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5403      | 93.7%   |
| Enabled  | 363       | 6.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5666      | 99.02%  |
| Yes  | 56        | 0.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1266      | 21.72%  |
| 4.01-8.0        | 1238      | 21.24%  |
| 8.01-16.0       | 1051      | 18.03%  |
| 3.01-4.0        | 881       | 15.12%  |
| 32.01-64.0      | 709       | 12.17%  |
| 64.01-256.0     | 217       | 3.72%   |
| 1.01-2.0        | 209       | 3.59%   |
| 24.01-32.0      | 122       | 2.09%   |
| 2.01-3.0        | 75        | 1.29%   |
| 0.51-1.0        | 38        | 0.65%   |
| More than 256.0 | 12        | 0.21%   |
| 0.01-0.5        | 8         | 0.14%   |
| Unknown         | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2161      | 33.58%  |
| 2.01-3.0        | 1568      | 24.36%  |
| 4.01-8.0        | 1008      | 15.66%  |
| 3.01-4.0        | 836       | 12.99%  |
| 0.51-1.0        | 384       | 5.97%   |
| 8.01-16.0       | 290       | 4.51%   |
| 0.01-0.5        | 98        | 1.52%   |
| 16.01-24.0      | 31        | 0.48%   |
| 24.01-32.0      | 26        | 0.4%    |
| 32.01-64.0      | 23        | 0.36%   |
| 64.01-256.0     | 6         | 0.09%   |
| Unknown         | 4         | 0.06%   |
| More than 256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3348      | 56.03%  |
| 2       | 1390      | 23.26%  |
| 3       | 525       | 8.79%   |
| 4       | 310       | 5.19%   |
| 5       | 148       | 2.48%   |
| 6       | 78        | 1.31%   |
| 0       | 60        | 1%      |
| 7       | 41        | 0.69%   |
| 8       | 24        | 0.4%    |
| 9       | 14        | 0.23%   |
| 11      | 9         | 0.15%   |
| 10      | 8         | 0.13%   |
| 12      | 6         | 0.1%    |
| 13      | 5         | 0.08%   |
| Unknown | 4         | 0.07%   |
| 14      | 2         | 0.03%   |
| 26      | 1         | 0.02%   |
| 19      | 1         | 0.02%   |
| 16      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3382      | 58.47%  |
| Yes       | 2402      | 41.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4972      | 86.67%  |
| No        | 765       | 13.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4292      | 74.46%  |
| No        | 1472      | 25.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3336      | 57.4%   |
| No        | 2476      | 42.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Canada  | 5720      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Toronto         | 585       | 9.68%   |
| Montreal        | 577       | 9.55%   |
| Vancouver       | 256       | 4.23%   |
| Calgary         | 235       | 3.89%   |
| Ottawa          | 212       | 3.51%   |
| Edmonton        | 192       | 3.18%   |
| Québec         | 126       | 2.08%   |
| Winnipeg        | 121       | 2%      |
| Mississauga     | 88        | 1.46%   |
| Victoria        | 84        | 1.39%   |
| Surrey          | 73        | 1.21%   |
| Laval           | 64        | 1.06%   |
| London          | 63        | 1.04%   |
| Kitchener       | 63        | 1.04%   |
| Brampton        | 63        | 1.04%   |
| Regina          | 59        | 0.98%   |
| Saskatoon       | 55        | 0.91%   |
| Hamilton        | 53        | 0.88%   |
| Burnaby         | 52        | 0.86%   |
| Oshawa          | 49        | 0.81%   |
| Gatineau        | 49        | 0.81%   |
| Windsor         | 44        | 0.73%   |
| Halifax         | 43        | 0.71%   |
| Scarborough     | 41        | 0.68%   |
| Sherbrooke      | 38        | 0.63%   |
| Kingston        | 36        | 0.6%    |
| Richmond Hill   | 32        | 0.53%   |
| New Westminster | 32        | 0.53%   |
| Markham         | 32        | 0.53%   |
| Trois-Rivières | 30        | 0.5%    |
| Kelowna         | 29        | 0.48%   |
| Barrie          | 29        | 0.48%   |
| Oakville        | 28        | 0.46%   |
| Moncton         | 28        | 0.46%   |
| North Vancouver | 26        | 0.43%   |
| Waterloo        | 25        | 0.41%   |
| Fredericton     | 24        | 0.4%    |
| Burlington      | 24        | 0.4%    |
| Thunder Bay     | 23        | 0.38%   |
| Red Deer        | 23        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 1559      | 2635   | 17.74%  |
| Seagate                     | 1521      | 2687   | 17.3%   |
| Samsung Electronics         | 1237      | 1968   | 14.07%  |
| Kingston                    | 540       | 749    | 6.14%   |
| Toshiba                     | 455       | 595    | 5.18%   |
| SanDisk                     | 447       | 575    | 5.09%   |
| Unknown                     | 366       | 507    | 4.16%   |
| Hitachi                     | 292       | 404    | 3.32%   |
| Intel                       | 267       | 401    | 3.04%   |
| Crucial                     | 247       | 355    | 2.81%   |
| A-DATA Technology           | 197       | 267    | 2.24%   |
| SK hynix                    | 185       | 232    | 2.1%    |
| HGST                        | 143       | 186    | 1.63%   |
| Micron Technology           | 98        | 135    | 1.11%   |
| Apple                       | 67        | 84     | 0.76%   |
| Phison                      | 57        | 84     | 0.65%   |
| SPCC                        | 51        | 68     | 0.58%   |
| KIOXIA                      | 46        | 53     | 0.52%   |
| Fujitsu                     | 43        | 59     | 0.49%   |
| OCZ                         | 40        | 54     | 0.46%   |
| Corsair                     | 38        | 47     | 0.43%   |
| Silicon Motion              | 36        | 61     | 0.41%   |
| China                       | 36        | 40     | 0.41%   |
| Micron/Crucial Technology   | 35        | 54     | 0.4%    |
| PNY                         | 34        | 52     | 0.39%   |
| LITEONIT                    | 31        | 35     | 0.35%   |
| Phison Electronics          | 29        | 34     | 0.33%   |
| Kingston Technology Company | 27        | 32     | 0.31%   |
| Patriot                     | 26        | 31     | 0.3%    |
| Mushkin                     | 25        | 30     | 0.28%   |
| ASMT                        | 25        | 33     | 0.28%   |
| Team                        | 24        | 32     | 0.27%   |
| JMicron Technology          | 24        | 33     | 0.27%   |
| Unknown                     | 24        | 24     | 0.27%   |
| LITEON                      | 22        | 24     | 0.25%   |
| XPG                         | 21        | 30     | 0.24%   |
| Hewlett-Packard             | 21        | 32     | 0.24%   |
| KingFast                    | 20        | 23     | 0.23%   |
| Maxtor                      | 19        | 25     | 0.22%   |
| SABRENT                     | 17        | 22     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 129       | 1.29%   |
| Samsung SSD 850 EVO 250GB                             | 91        | 0.91%   |
| Samsung SSD 860 EVO 500GB                             | 89        | 0.89%   |
| Seagate ST2000DM008-2FR102 2TB                        | 75        | 0.75%   |
| Samsung SSD 850 EVO 500GB                             | 67        | 0.67%   |
| Kingston SA400S37120G 120GB SSD                       | 67        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB                        | 63        | 0.63%   |
| Samsung SSD 860 EVO 1TB                               | 62        | 0.62%   |
| Kingston SA400S37480G 480GB SSD                       | 61        | 0.61%   |
| Unknown MMC Card  64GB                                | 59        | 0.59%   |
| Unknown MMC Card  32GB                                | 56        | 0.56%   |
| Toshiba MQ01ABD100 1TB                                | 55        | 0.55%   |
| SanDisk NVMe SSD Drive 1TB                            | 55        | 0.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 55        | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB                        | 54        | 0.54%   |
| SanDisk NVMe SSD Drive 500GB                          | 54        | 0.54%   |
| Samsung NVMe SSD Drive 500GB                          | 54        | 0.54%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 52        | 0.52%   |
| Unknown SD/MMC/MS PRO 1GB                             | 52        | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB                        | 50        | 0.5%    |
| Seagate ST500DM002-1BD142 500GB                       | 48        | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 47        | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 46        | 0.46%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 45        | 0.45%   |
| Samsung SSD 860 EVO 250GB                             | 45        | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                      | 44        | 0.44%   |
| Seagate ST1000LX015-1U7172 1TB                        | 43        | 0.43%   |
| Seagate ST2000DM006-2DM164 2TB                        | 42        | 0.42%   |
| Seagate ST2000DM001-1ER164 2TB                        | 42        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB                           | 42        | 0.42%   |
| Seagate ST1000DM003-1CH162 1TB                        | 41        | 0.41%   |
| HGST HTS721010A9E630 1TB                              | 41        | 0.41%   |
| Toshiba DT01ACA200 2TB                                | 38        | 0.38%   |
| Seagate Expansion Desk 2TB                            | 38        | 0.38%   |
| Seagate ST1000DM003-1ER162 1TB                        | 37        | 0.37%   |
| Toshiba DT01ACA100 1TB                                | 35        | 0.35%   |
| Seagate Expansion 2TB                                 | 35        | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 33        | 0.33%   |
| Seagate ST3500418AS 500GB                             | 32        | 0.32%   |
| Kingston SV300S37A240G 240GB SSD                      | 32        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1469      | 2568   | 38.98%  |
| WDC                 | 1227      | 2083   | 32.56%  |
| Toshiba             | 365       | 486    | 9.68%   |
| Hitachi             | 292       | 404    | 7.75%   |
| HGST                | 143       | 186    | 3.79%   |
| Samsung Electronics | 60        | 85     | 1.59%   |
| Unknown             | 52        | 74     | 1.38%   |
| Fujitsu             | 43        | 59     | 1.14%   |
| Apple               | 24        | 26     | 0.64%   |
| Maxtor              | 19        | 25     | 0.5%    |
| SABRENT             | 16        | 21     | 0.42%   |
| External            | 14        | 21     | 0.37%   |
| Maxone              | 7         | 9      | 0.19%   |
| ASMT                | 7         | 9      | 0.19%   |
| JMicron Technology  | 5         | 8      | 0.13%   |
| QNAP                | 3         | 8      | 0.08%   |
| USB 3.0             | 2         | 6      | 0.05%   |
| Hewlett-Packard     | 2         | 9      | 0.05%   |
| DAS                 | 2         | 14     | 0.05%   |
| ACASIS              | 2         | 2      | 0.05%   |
| USB3.0              | 1         | 2      | 0.03%   |
| SINTECHI            | 1         | 1      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| Maxtor 6            | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| KESU                | 1         | 2      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| DellEMC             | 1         | 8      | 0.03%   |
| DELLBOSS            | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 708       | 1078   | 25.04%  |
| Kingston            | 453       | 625    | 16.02%  |
| WDC                 | 251       | 351    | 8.88%   |
| Crucial             | 222       | 309    | 7.85%   |
| SanDisk             | 178       | 212    | 6.3%    |
| A-DATA Technology   | 172       | 235    | 6.08%   |
| Intel               | 115       | 154    | 4.07%   |
| Micron Technology   | 56        | 82     | 1.98%   |
| SPCC                | 47        | 64     | 1.66%   |
| OCZ                 | 39        | 50     | 1.38%   |
| China               | 36        | 40     | 1.27%   |
| Apple               | 36        | 42     | 1.27%   |
| SK hynix            | 35        | 45     | 1.24%   |
| Seagate             | 35        | 54     | 1.24%   |
| PNY                 | 34        | 52     | 1.2%    |
| LITEONIT            | 31        | 35     | 1.1%    |
| Toshiba             | 28        | 33     | 0.99%   |
| Patriot             | 25        | 30     | 0.88%   |
| Mushkin             | 23        | 28     | 0.81%   |
| Team                | 22        | 30     | 0.78%   |
| Corsair             | 21        | 24     | 0.74%   |
| LITEON              | 18        | 19     | 0.64%   |
| Dogfish             | 16        | 20     | 0.57%   |
| ASMT                | 15        | 18     | 0.53%   |
| TO Exter            | 13        | 15     | 0.46%   |
| Hewlett-Packard     | 13        | 16     | 0.46%   |
| OWC                 | 11        | 25     | 0.39%   |
| Lexar               | 11        | 14     | 0.39%   |
| KingFast            | 9         | 9      | 0.32%   |
| JMicron Technology  | 9         | 12     | 0.32%   |
| NGFF                | 8         | 10     | 0.28%   |
| KingSpec            | 8         | 13     | 0.28%   |
| KingDian            | 8         | 8      | 0.28%   |
| Transcend           | 7         | 8      | 0.25%   |
| Timetec             | 7         | 19     | 0.25%   |
| Vaseky              | 5         | 6      | 0.18%   |
| TCSUNBOW            | 5         | 6      | 0.18%   |
| T-FORCE             | 5         | 6      | 0.18%   |
| WDC WDS             | 4         | 5      | 0.14%   |
| Super Talent        | 4         | 6      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3087      | 6127   | 40.14%  |
| SSD     | 2409      | 3914   | 31.32%  |
| NVMe    | 1729      | 2667   | 22.48%  |
| MMC     | 313       | 424    | 4.07%   |
| Unknown | 153       | 208    | 1.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4396      | 9438   | 63.35%  |
| NVMe | 1726      | 2651   | 24.87%  |
| SAS  | 504       | 827    | 7.26%   |
| MMC  | 313       | 424    | 4.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3126      | 5028   | 51.8%   |
| 0.51-1.0   | 1738      | 2787   | 28.8%   |
| 1.01-2.0   | 630       | 1133   | 10.44%  |
| 3.01-4.0   | 199       | 365    | 3.3%    |
| 4.01-10.0  | 178       | 411    | 2.95%   |
| 2.01-3.0   | 145       | 275    | 2.4%    |
| 10.01-20.0 | 19        | 42     | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1406      | 22.81%  |
| 251-500        | 1304      | 21.15%  |
| 501-1000       | 979       | 15.88%  |
| 1001-2000      | 536       | 8.69%   |
| 1-20           | 491       | 7.96%   |
| More than 3000 | 466       | 7.56%   |
| 51-100         | 325       | 5.27%   |
| 21-50          | 223       | 3.62%   |
| Unknown        | 223       | 3.62%   |
| 2001-3000      | 212       | 3.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2461      | 38.42%  |
| 21-50          | 1063      | 16.59%  |
| 101-250        | 723       | 11.29%  |
| 51-100         | 681       | 10.63%  |
| 251-500        | 448       | 6.99%   |
| 501-1000       | 323       | 5.04%   |
| 1001-2000      | 223       | 3.48%   |
| Unknown        | 223       | 3.48%   |
| More than 3000 | 172       | 2.68%   |
| 2001-3000      | 88        | 1.37%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 10        | 11     | 1.81%   |
| Seagate ST500DM002-1BD142 500GB     | 8         | 9      | 1.45%   |
| Toshiba MQ01ABD100 1TB              | 6         | 8      | 1.08%   |
| Seagate ST9500325AS 500GB           | 6         | 6      | 1.08%   |
| Seagate ST500LM000-1EJ162 500GB     | 6         | 6      | 1.08%   |
| Seagate ST31000528AS 1TB            | 6         | 8      | 1.08%   |
| HGST HTS541010A9E680 1TB            | 6         | 6      | 1.08%   |
| WDC WD2500HHTZ-04N21V0 250GB        | 5         | 5      | 0.9%    |
| WDC WD20EARS-00MVWB0 2TB            | 5         | 6      | 0.9%    |
| Seagate ST9500420AS 500GB           | 5         | 5      | 0.9%    |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 0.9%    |
| Seagate ST500LM021-1KJ152 500GB     | 5         | 14     | 0.9%    |
| Seagate ST3500418AS 500GB           | 5         | 6      | 0.9%    |
| Kingston SV300S37A120G 120GB SSD    | 5         | 7      | 0.9%    |
| Hitachi HDS721010CLA332 1TB         | 5         | 5      | 0.9%    |
| HGST HTS725050A7E630 500GB          | 5         | 6      | 0.9%    |
| HGST HTS721010A9E630 1TB            | 5         | 5      | 0.9%    |
| WDC WD40EFRX-68WT0N0 4TB            | 4         | 17     | 0.72%   |
| Toshiba MK2555GSXF 250GB            | 4         | 4      | 0.72%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 5      | 0.72%   |
| Seagate ST31500341AS 1TB            | 4         | 4      | 0.72%   |
| Seagate ST2000DM001-1CH164 2TB      | 4         | 4      | 0.72%   |
| Samsung Electronics SSD 870 EVO 1TB | 4         | 5      | 0.72%   |
| Intel SSDSA1M080G2LE 80GB           | 4         | 4      | 0.72%   |
| HGST HTS545050A7E680 500GB          | 4         | 4      | 0.72%   |
| WDC WD6400AAKS-22A7B2 640GB         | 3         | 3      | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB            | 3         | 5      | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3         | 3      | 0.54%   |
| WDC WD10EARX-00N0YB0 1TB            | 3         | 4      | 0.54%   |
| WDC WD1001FALS-00J7B1 1TB           | 3         | 4      | 0.54%   |
| Toshiba MK3261GSYN 320GB            | 3         | 3      | 0.54%   |
| Seagate ST9320325AS 320GB           | 3         | 6      | 0.54%   |
| Seagate ST500LM000-1EJ162-SSHD-8GB  | 3         | 3      | 0.54%   |
| Seagate ST3250310AS 250GB           | 3         | 4      | 0.54%   |
| Seagate ST1000LX015-1U7172 1TB      | 3         | 4      | 0.54%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 3      | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB      | 3         | 4      | 0.54%   |
| Hitachi HTS541616J9SA00 160GB       | 3         | 3      | 0.54%   |
| Crucial CT1000P1SSD8 1TB            | 3         | 9      | 0.54%   |
| A-DATA Technology SX900 256GB SSD   | 3         | 3      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 168       | 232    | 31.7%   |
| WDC                   | 128       | 177    | 24.15%  |
| Hitachi               | 46        | 48     | 8.68%   |
| Toshiba               | 36        | 38     | 6.79%   |
| Samsung Electronics   | 32        | 47     | 6.04%   |
| HGST                  | 22        | 23     | 4.15%   |
| Kingston              | 20        | 27     | 3.77%   |
| Intel                 | 18        | 20     | 3.4%    |
| Crucial               | 11        | 18     | 2.08%   |
| A-DATA Technology     | 11        | 12     | 2.08%   |
| SK hynix              | 3         | 3      | 0.57%   |
| Mushkin               | 3         | 3      | 0.57%   |
| LITEONIT              | 3         | 3      | 0.57%   |
| Fujitsu               | 3         | 9      | 0.57%   |
| Apple                 | 3         | 3      | 0.57%   |
| Sandisk               | 2         | 2      | 0.38%   |
| OCZ                   | 2         | 2      | 0.38%   |
| Maxtor                | 2         | 2      | 0.38%   |
| KingSpec              | 2         | 2      | 0.38%   |
| Hewlett-Packard       | 2         | 2      | 0.38%   |
| China                 | 2         | 2      | 0.38%   |
| ASMT                  | 2         | 3      | 0.38%   |
| Timetec               | 1         | 3      | 0.19%   |
| Super Talent          | 1         | 1      | 0.19%   |
| Realtek Semiconductor | 1         | 1      | 0.19%   |
| Micron Technology     | 1         | 1      | 0.19%   |
| LITEON                | 1         | 1      | 0.19%   |
| LaCie                 | 1         | 1      | 0.19%   |
| Drevo                 | 1         | 1      | 0.19%   |
| DAS                   | 1         | 3      | 0.19%   |
| Corsair               | 1         | 1      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 168       | 232    | 40.58%  |
| WDC                 | 127       | 176    | 30.68%  |
| Hitachi             | 46        | 48     | 11.11%  |
| Toshiba             | 33        | 35     | 7.97%   |
| HGST                | 22        | 23     | 5.31%   |
| Samsung Electronics | 9         | 18     | 2.17%   |
| Fujitsu             | 3         | 9      | 0.72%   |
| Maxtor              | 2         | 2      | 0.48%   |
| Apple               | 2         | 2      | 0.48%   |
| LaCie               | 1         | 1      | 0.24%   |
| DAS                 | 1         | 3      | 0.24%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 387       | 549    | 76.94%  |
| SSD  | 94        | 111    | 18.69%  |
| NVMe | 22        | 31     | 4.37%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2003FYYS-18W0B0 2TB         | 1         | 1      | 16.67%  |
| Samsung Electronics HM160HC 160GB | 1         | 2      | 16.67%  |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 16.67%  |
| LITEON CA3-8D512 512GB            | 1         | 2      | 16.67%  |
| Intel SSDSA1M160G2HP 160GB        | 1         | 1      | 16.67%  |
| Hewlett-Packard EF0450FARMV 450GB | 1         | 4      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 33.33%  |
| WDC                 | 1         | 1      | 16.67%  |
| LITEON              | 1         | 2      | 16.67%  |
| Intel               | 1         | 1      | 16.67%  |
| Hewlett-Packard     | 1         | 4      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3708      | 8374   | 58.97%  |
| Works    | 2088      | 4264   | 33.21%  |
| Malfunc  | 486       | 691    | 7.73%   |
| Failed   | 6         | 11     | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3634      | 49.06%  |
| AMD                              | 1317      | 17.78%  |
| Samsung Electronics              | 606       | 8.18%   |
| SanDisk                          | 417       | 5.63%   |
| ASMedia Technology               | 172       | 2.32%   |
| SK hynix                         | 145       | 1.96%   |
| Marvell Technology Group         | 138       | 1.86%   |
| Nvidia                           | 119       | 1.61%   |
| Kingston Technology Company      | 113       | 1.53%   |
| Phison Electronics               | 101       | 1.36%   |
| JMicron Technology               | 97        | 1.31%   |
| Toshiba America Info Systems     | 65        | 0.88%   |
| Micron/Crucial Technology        | 61        | 0.82%   |
| ADATA Technology                 | 56        | 0.76%   |
| Silicon Motion                   | 49        | 0.66%   |
| KIOXIA                           | 48        | 0.65%   |
| Micron Technology                | 44        | 0.59%   |
| LSI Logic / Symbios Logic        | 42        | 0.57%   |
| Broadcom / LSI                   | 32        | 0.43%   |
| Realtek Semiconductor            | 22        | 0.3%    |
| Seagate Technology               | 17        | 0.23%   |
| Silicon Image                    | 16        | 0.22%   |
| Union Memory (Shenzhen)          | 12        | 0.16%   |
| VIA Technologies                 | 11        | 0.15%   |
| Hewlett-Packard                  | 8         | 0.11%   |
| Apple                            | 8         | 0.11%   |
| Lite-On Technology               | 7         | 0.09%   |
| Lenovo                           | 7         | 0.09%   |
| Solid State Storage Technology   | 5         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.07%   |
| INNOGRIT                         | 5         | 0.07%   |
| Shenzhen Longsys Electronics     | 4         | 0.05%   |
| HighPoint Technologies           | 4         | 0.05%   |
| Adaptec                          | 4         | 0.05%   |
| Silicon Integrated Systems [SiS] | 3         | 0.04%   |
| Integrated Technology Express    | 3         | 0.04%   |
| OCZ Technology Group             | 2         | 0.03%   |
| O2 Micro                         | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.01%   |
| ULi Electronics                  | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 876       | 10.07%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 300       | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 258       | 2.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 221       | 2.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 192       | 2.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 187       | 2.15%   |
| AMD 400 Series Chipset SATA Controller                                         | 180       | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 175       | 2.01%   |
| Intel SATA Controller [RAID mode]                                              | 159       | 1.83%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 158       | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 150       | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 148       | 1.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 130       | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 128       | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 110       | 1.26%   |
| AMD 500 Series Chipset SATA Controller                                         | 107       | 1.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 105       | 1.21%   |
| Intel Volume Management Device NVMe RAID Controller                            | 105       | 1.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 105       | 1.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 103       | 1.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 97        | 1.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 96        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 94        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 90        | 1.03%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 89        | 1.02%   |
| Samsung NVMe SSD Controller 980                                                | 89        | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 88        | 1.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 87        | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 85        | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 79        | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 79        | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 78        | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 75        | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 74        | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 69        | 0.79%   |
| Intel SSD 660P Series                                                          | 63        | 0.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 54        | 0.62%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 54        | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                          | 52        | 0.6%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 51        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4133      | 55.97%  |
| NVMe | 1743      | 23.61%  |
| IDE  | 867       | 11.74%  |
| RAID | 572       | 7.75%   |
| SAS  | 56        | 0.76%   |
| SCSI | 13        | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 4100      | 71.68%  |
| AMD      | 1554      | 27.17%  |
| ARM      | 59        | 1.03%   |
| Unknown  | 6         | 0.1%    |
| QUALCOMM | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 63        | 1.1%    |
| AMD Ryzen 5 3600 6-Core Processor       | 51        | 0.89%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 46        | 0.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 45        | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 45        | 0.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 44        | 0.77%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 40        | 0.7%    |
| AMD Ryzen 7 3700X 8-Core Processor      | 40        | 0.7%    |
| ARM Processor                           | 38        | 0.66%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 37        | 0.65%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 36        | 0.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 36        | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 35        | 0.61%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 35        | 0.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 35        | 0.61%   |
| AMD Custom APU 0405                     | 35        | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 34        | 0.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 34        | 0.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 34        | 0.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 34        | 0.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 33        | 0.58%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 31        | 0.54%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 30        | 0.52%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 29        | 0.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 28        | 0.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 28        | 0.49%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 28        | 0.49%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 28        | 0.49%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 27        | 0.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 27        | 0.47%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 27        | 0.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 27        | 0.47%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 26        | 0.45%   |
| AMD FX-8350 Eight-Core Processor        | 26        | 0.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 25        | 0.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 25        | 0.44%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 25        | 0.44%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 24        | 0.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 23        | 0.4%    |
| Intel Core i7-2600K CPU @ 3.40GHz       | 23        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1206      | 21.04%  |
| Intel Core i7           | 1160      | 20.24%  |
| Other                   | 398       | 6.94%   |
| AMD Ryzen 7             | 309       | 5.39%   |
| AMD Ryzen 5             | 307       | 5.36%   |
| Intel Core i3           | 283       | 4.94%   |
| Intel Core 2 Duo        | 272       | 4.75%   |
| Intel Xeon              | 207       | 3.61%   |
| Intel Celeron           | 174       | 3.04%   |
| AMD Ryzen 9             | 121       | 2.11%   |
| AMD FX                  | 114       | 1.99%   |
| Intel Pentium           | 99        | 1.73%   |
| AMD A6                  | 82        | 1.43%   |
| AMD A10                 | 72        | 1.26%   |
| Intel Core 2 Quad       | 71        | 1.24%   |
| Intel Atom              | 67        | 1.17%   |
| Intel Pentium Dual-Core | 59        | 1.03%   |
| AMD Ryzen 3             | 54        | 0.94%   |
| Intel Core i9           | 49        | 0.85%   |
| AMD A8                  | 44        | 0.77%   |
| AMD Athlon 64 X2        | 41        | 0.72%   |
| Intel Pentium Dual      | 40        | 0.7%    |
| Intel Core 2            | 37        | 0.65%   |
| AMD A4                  | 37        | 0.65%   |
| Intel Genuine           | 22        | 0.38%   |
| AMD Phenom II X4        | 22        | 0.38%   |
| AMD Athlon II X2        | 22        | 0.38%   |
| AMD E                   | 19        | 0.33%   |
| Intel Pentium Silver    | 18        | 0.31%   |
| AMD Phenom II X6        | 18        | 0.31%   |
| AMD Phenom              | 17        | 0.3%    |
| Intel Pentium D         | 16        | 0.28%   |
| Intel Pentium 4         | 16        | 0.28%   |
| AMD Athlon              | 16        | 0.28%   |
| AMD Ryzen Threadripper  | 15        | 0.26%   |
| AMD E2                  | 13        | 0.23%   |
| AMD E1                  | 13        | 0.23%   |
| AMD Ryzen 5 PRO         | 12        | 0.21%   |
| AMD A12                 | 12        | 0.21%   |
| ARM BCM                 | 11        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2139      | 37.26%  |
| 2       | 2033      | 35.42%  |
| 6       | 595       | 10.37%  |
| 8       | 483       | 8.41%   |
| 12      | 129       | 2.25%   |
| 1       | 115       | 2%      |
| 16      | 75        | 1.31%   |
| 3       | 54        | 0.94%   |
| 10      | 42        | 0.73%   |
| 14      | 35        | 0.61%   |
| 24      | 15        | 0.26%   |
| Unknown | 11        | 0.19%   |
| 20      | 7         | 0.12%   |
| 56      | 2         | 0.03%   |
| 128     | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 52      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 7       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5622      | 98.22%  |
| 2       | 90        | 1.57%   |
| Unknown | 9         | 0.16%   |
| 3       | 3         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3751      | 65.43%  |
| 1       | 1969      | 34.35%  |
| Unknown | 11        | 0.19%   |
| 12      | 1         | 0.02%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5569      | 97.02%  |
| Unknown        | 121       | 2.11%   |
| 32-bit         | 41        | 0.71%   |
| 64-bit         | 9         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1771      | 29.59%  |
| 0x306a9    | 304       | 5.08%   |
| 0x206a7    | 288       | 4.81%   |
| 0x306c3    | 235       | 3.93%   |
| 0x1067a    | 188       | 3.14%   |
| 0x906ea    | 136       | 2.27%   |
| 0x506e3    | 105       | 1.75%   |
| 0x806ea    | 98        | 1.64%   |
| 0x08701021 | 94        | 1.57%   |
| 0x40651    | 93        | 1.55%   |
| 0x906e9    | 88        | 1.47%   |
| 0x20655    | 88        | 1.47%   |
| 0x806e9    | 76        | 1.27%   |
| 0x6fd      | 76        | 1.27%   |
| 0x406e3    | 74        | 1.24%   |
| 0x806ec    | 66        | 1.1%    |
| 0x06001119 | 60        | 1%      |
| 0x306d4    | 57        | 0.95%   |
| 0x20652    | 56        | 0.94%   |
| 0x10676    | 56        | 0.94%   |
| 0x806c1    | 54        | 0.9%    |
| 0x06000852 | 52        | 0.87%   |
| 0x106e5    | 51        | 0.85%   |
| 0x08701013 | 51        | 0.85%   |
| 0x6fb      | 50        | 0.84%   |
| 0x0800820d | 50        | 0.84%   |
| 0xa0652    | 46        | 0.77%   |
| 0x0a50000c | 45        | 0.75%   |
| 0x010000c8 | 45        | 0.75%   |
| 0x706e5    | 40        | 0.67%   |
| 0x30678    | 38        | 0.63%   |
| 0x906a3    | 36        | 0.6%    |
| 0x206d7    | 36        | 0.6%    |
| 0x906ed    | 35        | 0.58%   |
| 0x406c4    | 35        | 0.58%   |
| 0x08108109 | 35        | 0.58%   |
| 0x106a5    | 32        | 0.53%   |
| 0x206c2    | 30        | 0.5%    |
| 0x03000027 | 29        | 0.48%   |
| 0x08108102 | 28        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 746       | 13.02%  |
| Haswell          | 500       | 8.73%   |
| IvyBridge        | 424       | 7.4%    |
| SandyBridge      | 417       | 7.28%   |
| Penryn           | 314       | 5.48%   |
| Zen 2            | 280       | 4.89%   |
| Skylake          | 268       | 4.68%   |
| Unknown          | 264       | 4.61%   |
| Westmere         | 222       | 3.88%   |
| Core             | 208       | 3.63%   |
| Zen 3            | 197       | 3.44%   |
| Zen+             | 167       | 2.91%   |
| Piledriver       | 161       | 2.81%   |
| Silvermont       | 132       | 2.3%    |
| CometLake        | 131       | 2.29%   |
| K10              | 130       | 2.27%   |
| Zen              | 117       | 2.04%   |
| Nehalem          | 111       | 1.94%   |
| Broadwell        | 107       | 1.87%   |
| TigerLake        | 98        | 1.71%   |
| Excavator        | 95        | 1.66%   |
| Alderlake Hybrid | 88        | 1.54%   |
| IceLake          | 81        | 1.41%   |
| K8 Hammer        | 67        | 1.17%   |
| Goldmont plus    | 56        | 0.98%   |
| Puma             | 42        | 0.73%   |
| K10 Llano        | 41        | 0.72%   |
| Bobcat           | 40        | 0.7%    |
| NetBurst         | 37        | 0.65%   |
| Bulldozer        | 35        | 0.61%   |
| Bonnell          | 28        | 0.49%   |
| Goldmont         | 27        | 0.47%   |
| Jaguar           | 26        | 0.45%   |
| P6               | 25        | 0.44%   |
| Steamroller      | 24        | 0.42%   |
| K8 & K10 hybrid  | 12        | 0.21%   |
| Tremont          | 9         | 0.16%   |
| Gracemont        | 2         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2901      | 44.72%  |
| Nvidia                                       | 1850      | 28.52%  |
| AMD                                          | 1656      | 25.53%  |
| Matrox Electronics Systems                   | 43        | 0.66%   |
| ASPEED Technology                            | 28        | 0.43%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.03%   |
| VIA Technologies                             | 2         | 0.03%   |
| Loongson Technology                          | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 269       | 4%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 196       | 2.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 158       | 2.35%   |
| Intel UHD Graphics 620                                                                   | 148       | 2.2%    |
| Intel Core Processor Integrated Graphics Controller                                      | 135       | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 130       | 1.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 117       | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 102       | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 96        | 1.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 95        | 1.41%   |
| Intel HD Graphics 530                                                                    | 93        | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 93        | 1.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 91        | 1.35%   |
| Intel HD Graphics 620                                                                    | 82        | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 79        | 1.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 77        | 1.14%   |
| Intel HD Graphics 5500                                                                   | 75        | 1.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 72        | 1.07%   |
| AMD Renoir                                                                               | 72        | 1.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 72        | 1.07%   |
| Intel HD Graphics 630                                                                    | 67        | 1%      |
| Nvidia GK208B [GeForce GT 710]                                                           | 66        | 0.98%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 65        | 0.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 61        | 0.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 57        | 0.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 57        | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 56        | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 53        | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 53        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 51        | 0.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 50        | 0.74%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 49        | 0.73%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 49        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 43        | 0.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 42        | 0.62%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 41        | 0.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 40        | 0.59%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 40        | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 38        | 0.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 37        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x Intel                 | 2205      | 38.14%  |
| 1 x AMD                   | 1400      | 24.22%  |
| 1 x Nvidia                | 1197      | 20.71%  |
| Intel + Nvidia            | 507       | 8.77%   |
| AMD + Nvidia              | 91        | 1.57%   |
| 2 x AMD                   | 81        | 1.4%    |
| Intel + AMD               | 81        | 1.4%    |
| Other                     | 74        | 1.28%   |
| 2 x Nvidia                | 40        | 0.69%   |
| 1 x Matrox                | 32        | 0.55%   |
| 1 x ASPEED                | 22        | 0.38%   |
| 2 x Intel                 | 18        | 0.31%   |
| Nvidia + Matrox           | 9         | 0.16%   |
| Nvidia + ASPEED           | 4         | 0.07%   |
| Intel + 2 x Nvidia        | 4         | 0.07%   |
| 1 x SiS                   | 3         | 0.05%   |
| 1 x VIA                   | 2         | 0.03%   |
| AMD + 2 x Nvidia          | 2         | 0.03%   |
| AMD + Matrox              | 2         | 0.03%   |
| 5 x Nvidia                | 1         | 0.02%   |
| 2 x Loongson Technology   | 1         | 0.02%   |
| 1 x XGI                   | 1         | 0.02%   |
| 1 x Intel + 3 x AMD       | 1         | 0.02%   |
| Intel + ASPEED            | 1         | 0.02%   |
| AMD + XGI                 | 1         | 0.02%   |
| AMD + Nvidia + 1 x ASPEED | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4475      | 76.9%   |
| Proprietary | 1074      | 18.46%  |
| Unknown     | 270       | 4.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3255      | 54.78%  |
| 0.01-0.5   | 704       | 11.85%  |
| 1.01-2.0   | 580       | 9.76%   |
| 0.51-1.0   | 408       | 6.87%   |
| 7.01-8.0   | 342       | 5.76%   |
| 3.01-4.0   | 329       | 5.54%   |
| 5.01-6.0   | 155       | 2.61%   |
| 8.01-16.0  | 106       | 1.78%   |
| 2.01-3.0   | 49        | 0.82%   |
| 16.01-24.0 | 9         | 0.15%   |
| 4.01-5.0   | 4         | 0.07%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 828       | 12.99%  |
| AU Optronics            | 616       | 9.66%   |
| LG Display              | 456       | 7.15%   |
| Dell                    | 431       | 6.76%   |
| Goldstar                | 386       | 6.05%   |
| Chimei Innolux          | 363       | 5.69%   |
| Acer                    | 355       | 5.57%   |
| BOE                     | 318       | 4.99%   |
| Hewlett-Packard         | 265       | 4.16%   |
| Ancor Communications    | 227       | 3.56%   |
| Sharp                   | 181       | 2.84%   |
| BenQ                    | 180       | 2.82%   |
| Apple                   | 176       | 2.76%   |
| Lenovo                  | 154       | 2.42%   |
| ASUSTek Computer        | 129       | 2.02%   |
| ViewSonic               | 124       | 1.95%   |
| Chi Mei Optoelectronics | 80        | 1.25%   |
| LG Electronics          | 69        | 1.08%   |
| Toshiba                 | 66        | 1.04%   |
| Sony                    | 64        | 1%      |
| Philips                 | 63        | 0.99%   |
| Unknown                 | 62        | 0.97%   |
| AOC                     | 56        | 0.88%   |
| PANDA                   | 49        | 0.77%   |
| MSI                     | 32        | 0.5%    |
| LG Philips              | 32        | 0.5%    |
| InfoVision              | 32        | 0.5%    |
| Panasonic               | 26        | 0.41%   |
| NEC Computers           | 25        | 0.39%   |
| Valve                   | 22        | 0.35%   |
| Gigabyte Technology     | 21        | 0.33%   |
| HannStar                | 20        | 0.31%   |
| Unknown                 | 19        | 0.3%    |
| HKC                     | 17        | 0.27%   |
| Insignia                | 16        | 0.25%   |
| Sceptre Tech            | 15        | 0.24%   |
| Gateway                 | 15        | 0.24%   |
| CSO                     | 14        | 0.22%   |
| AUS                     | 13        | 0.2%    |
| Vizio                   | 12        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 37        | 0.55%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 33        | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 32        | 0.48%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 26        | 0.39%   |
| Toshiba TV TSB0206 1920x1080                                          | 24        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 21        | 0.31%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 20        | 0.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 20        | 0.3%    |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 20        | 0.3%    |
| Unknown                                                               | 19        | 0.28%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 18        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 18        | 0.27%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 17        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 17        | 0.25%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 17        | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 16        | 0.24%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 16        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 16        | 0.24%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 15        | 0.22%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 15        | 0.22%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 14        | 0.21%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 14        | 0.21%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 14        | 0.21%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                | 14        | 0.21%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 14        | 0.21%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch        | 13        | 0.19%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 13        | 0.19%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 13        | 0.19%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 12        | 0.18%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                | 12        | 0.18%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 12        | 0.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 12        | 0.18%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 12        | 0.18%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 12        | 0.18%   |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                     | 12        | 0.18%   |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                       | 11        | 0.16%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 11        | 0.16%   |
| Sharp HDMI SHP0FFB 1920x1080 820x460mm 37.0-inch                      | 11        | 0.16%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 11        | 0.16%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 11        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2456      | 40.03%  |
| 1366x768 (WXGA)    | 929       | 15.14%  |
| 3840x2160 (4K)     | 438       | 7.14%   |
| 2560x1440 (QHD)    | 304       | 4.95%   |
| 1680x1050 (WSXGA+) | 287       | 4.68%   |
| 1600x900 (HD+)     | 255       | 4.16%   |
| 1280x1024 (SXGA)   | 194       | 3.16%   |
| 1920x1200 (WUXGA)  | 180       | 2.93%   |
| 1280x800 (WXGA)    | 160       | 2.61%   |
| 1440x900 (WXGA+)   | 151       | 2.46%   |
| Unknown            | 128       | 2.09%   |
| 3440x1440          | 68        | 1.11%   |
| 1360x768           | 64        | 1.04%   |
| 3840x1080          | 53        | 0.86%   |
| 2560x1080          | 41        | 0.67%   |
| 1920x540           | 39        | 0.64%   |
| 2880x1800          | 35        | 0.57%   |
| 2560x1600          | 30        | 0.49%   |
| 800x1280           | 22        | 0.36%   |
| 1024x768 (XGA)     | 19        | 0.31%   |
| 1600x1200          | 18        | 0.29%   |
| 2736x1824          | 17        | 0.28%   |
| 3840x2400          | 16        | 0.26%   |
| 3200x1800 (QHD+)   | 16        | 0.26%   |
| 1280x720 (HD)      | 14        | 0.23%   |
| 1024x600           | 13        | 0.21%   |
| 2256x1504          | 11        | 0.18%   |
| 2160x1440          | 8         | 0.13%   |
| 5760x1080          | 7         | 0.11%   |
| 3840x1200          | 7         | 0.11%   |
| 3600x1080          | 7         | 0.11%   |
| 2288x1287          | 7         | 0.11%   |
| 1920x1280          | 7         | 0.11%   |
| 7680x2160          | 6         | 0.1%    |
| 4480x1440          | 6         | 0.1%    |
| 3200x2000          | 6         | 0.1%    |
| 2048x1152          | 6         | 0.1%    |
| 3456x2160          | 5         | 0.08%   |
| 3200x1080          | 5         | 0.08%   |
| 5760x2160          | 4         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1355      | 21.4%   |
| 27      | 547       | 8.64%   |
| 13      | 480       | 7.58%   |
| 24      | 462       | 7.3%    |
| Unknown | 423       | 6.68%   |
| 23      | 418       | 6.6%    |
| 14      | 384       | 6.06%   |
| 21      | 381       | 6.02%   |
| 17      | 309       | 4.88%   |
| 19      | 194       | 3.06%   |
| 31      | 182       | 2.87%   |
| 20      | 165       | 2.61%   |
| 22      | 164       | 2.59%   |
| 34      | 94        | 1.48%   |
| 12      | 82        | 1.29%   |
| 18      | 77        | 1.22%   |
| 72      | 69        | 1.09%   |
| 11      | 63        | 0.99%   |
| 84      | 62        | 0.98%   |
| 32      | 39        | 0.62%   |
| 40      | 31        | 0.49%   |
| 54      | 30        | 0.47%   |
| 25      | 27        | 0.43%   |
| 16      | 25        | 0.39%   |
| 74      | 24        | 0.38%   |
| 26      | 22        | 0.35%   |
| 10      | 20        | 0.32%   |
| 7       | 20        | 0.32%   |
| 37      | 19        | 0.3%    |
| 28      | 17        | 0.27%   |
| 43      | 15        | 0.24%   |
| 48      | 14        | 0.22%   |
| 39      | 11        | 0.17%   |
| 36      | 11        | 0.17%   |
| 49      | 8         | 0.13%   |
| 46      | 8         | 0.13%   |
| 35      | 7         | 0.11%   |
| 65      | 6         | 0.09%   |
| 52      | 6         | 0.09%   |
| 42      | 6         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1995      | 32.25%  |
| 501-600        | 1290      | 20.85%  |
| 401-500        | 859       | 13.89%  |
| 201-300        | 428       | 6.92%   |
| Unknown        | 423       | 6.84%   |
| 351-400        | 397       | 6.42%   |
| 601-700        | 268       | 4.33%   |
| 1501-2000      | 165       | 2.67%   |
| 701-800        | 146       | 2.36%   |
| 1001-1500      | 93        | 1.5%    |
| 801-900        | 72        | 1.16%   |
| 901-1000       | 23        | 0.37%   |
| 1-100          | 22        | 0.36%   |
| More than 2000 | 4         | 0.06%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3946      | 69.77%  |
| 16/10   | 865       | 15.29%  |
| Unknown | 345       | 6.1%    |
| 5/4     | 183       | 3.24%   |
| 21/9    | 104       | 1.84%   |
| 3/2     | 84        | 1.49%   |
| 4/3     | 51        | 0.9%    |
| 32/9    | 24        | 0.42%   |
| 0.67    | 20        | 0.35%   |
| 6/5     | 16        | 0.28%   |
| 1.96    | 5         | 0.09%   |
| 1.00    | 4         | 0.07%   |
| 3.40    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 3.33    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 11/10   | 1         | 0.02%   |
| 0.89    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1333      | 21.39%  |
| 201-250        | 1141      | 18.31%  |
| 81-90          | 660       | 10.59%  |
| 301-350        | 564       | 9.05%   |
| 151-200        | 450       | 7.22%   |
| Unknown        | 423       | 6.79%   |
| 351-500        | 334       | 5.36%   |
| More than 1000 | 235       | 3.77%   |
| 71-80          | 201       | 3.23%   |
| 121-130        | 190       | 3.05%   |
| 251-300        | 162       | 2.6%    |
| 141-150        | 144       | 2.31%   |
| 501-1000       | 125       | 2.01%   |
| 51-60          | 67        | 1.08%   |
| 61-70          | 66        | 1.06%   |
| 111-120        | 42        | 0.67%   |
| 131-140        | 36        | 0.58%   |
| 1-40           | 23        | 0.37%   |
| 41-50          | 18        | 0.29%   |
| 91-100         | 17        | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2185      | 36.33%  |
| 101-120       | 1478      | 24.58%  |
| 121-160       | 1236      | 20.55%  |
| Unknown       | 423       | 7.03%   |
| 161-240       | 316       | 5.25%   |
| 1-50          | 228       | 3.79%   |
| More than 240 | 148       | 2.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4445      | 75.49%  |
| 2     | 986       | 16.75%  |
| 0     | 279       | 4.74%   |
| 3     | 160       | 2.72%   |
| 4     | 15        | 0.25%   |
| 5     | 2         | 0.03%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3042      | 35.41%  |
| Realtek Semiconductor           | 2678      | 31.18%  |
| Qualcomm Atheros                | 921       | 10.72%  |
| Broadcom                        | 576       | 6.71%   |
| Broadcom Limited                | 142       | 1.65%   |
| Marvell Technology Group        | 136       | 1.58%   |
| Ralink                          | 105       | 1.22%   |
| MediaTek                        | 104       | 1.21%   |
| Nvidia                          | 102       | 1.19%   |
| Ralink Technology               | 80        | 0.93%   |
| TP-Link                         | 76        | 0.88%   |
| D-Link                          | 70        | 0.81%   |
| ASIX Electronics                | 67        | 0.78%   |
| Linksys                         | 49        | 0.57%   |
| Samsung Electronics             | 38        | 0.44%   |
| ASUSTek Computer                | 36        | 0.42%   |
| D-Link System                   | 35        | 0.41%   |
| Qualcomm Atheros Communications | 28        | 0.33%   |
| Aquantia                        | 24        | 0.28%   |
| Microsoft                       | 22        | 0.26%   |
| NetGear                         | 21        | 0.24%   |
| DisplayLink                     | 20        | 0.23%   |
| Lenovo                          | 17        | 0.2%    |
| Google                          | 13        | 0.15%   |
| Sierra Wireless                 | 10        | 0.12%   |
| Qualcomm                        | 10        | 0.12%   |
| Belkin Components               | 10        | 0.12%   |
| Mellanox Technologies           | 7         | 0.08%   |
| Apple                           | 7         | 0.08%   |
| Motorola PCS                    | 6         | 0.07%   |
| Dell                            | 6         | 0.07%   |
| AMD                             | 6         | 0.07%   |
| VIA Technologies                | 5         | 0.06%   |
| Microchip Technology            | 5         | 0.06%   |
| Micro Star International        | 5         | 0.06%   |
| Hewlett-Packard                 | 5         | 0.06%   |
| Gemtek                          | 5         | 0.06%   |
| Edimax Technology               | 5         | 0.06%   |
| Arduino SA                      | 5         | 0.06%   |
| LG Electronics                  | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1770      | 17.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 322       | 3.16%   |
| Intel Wi-Fi 6 AX200                                               | 294       | 2.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 282       | 2.77%   |
| Intel Wireless 8265 / 8275                                        | 181       | 1.78%   |
| Intel I211 Gigabit Network Connection                             | 175       | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 148       | 1.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 144       | 1.41%   |
| Intel Wireless 7260                                               | 133       | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 125       | 1.23%   |
| Intel Wireless 7265                                               | 120       | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 111       | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 104       | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 102       | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 101       | 0.99%   |
| Intel Wireless 8260                                               | 99        | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 96        | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 95        | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 93        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 88        | 0.86%   |
| Intel Ethernet Controller I225-V                                  | 88        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 87        | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 81        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 76        | 0.75%   |
| Intel Wi-Fi 6 AX201                                               | 74        | 0.73%   |
| Intel 82579V Gigabit Network Connection                           | 69        | 0.68%   |
| Intel Wireless-AC 9260                                            | 67        | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 65        | 0.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 60        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 59        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 55        | 0.54%   |
| Intel Wireless 3165                                               | 55        | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 55        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 54        | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                     | 54        | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 53        | 0.52%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 53        | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 53        | 0.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 52        | 0.51%   |
| Intel Centrino Ultimate-N 6300                                    | 52        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2106      | 45.71%  |
| Qualcomm Atheros                      | 730       | 15.85%  |
| Realtek Semiconductor                 | 627       | 13.61%  |
| Broadcom                              | 380       | 8.25%   |
| Ralink                                | 105       | 2.28%   |
| MediaTek                              | 100       | 2.17%   |
| Broadcom Limited                      | 86        | 1.87%   |
| Ralink Technology                     | 80        | 1.74%   |
| TP-Link                               | 70        | 1.52%   |
| D-Link                                | 68        | 1.48%   |
| Linksys                               | 47        | 1.02%   |
| ASUSTek Computer                      | 36        | 0.78%   |
| Qualcomm Atheros Communications       | 28        | 0.61%   |
| Marvell Technology Group              | 23        | 0.5%    |
| D-Link System                         | 22        | 0.48%   |
| NetGear                               | 21        | 0.46%   |
| Microsoft                             | 16        | 0.35%   |
| Sierra Wireless                       | 10        | 0.22%   |
| Belkin Components                     | 10        | 0.22%   |
| Qualcomm                              | 9         | 0.2%    |
| Micro Star International              | 5         | 0.11%   |
| Gemtek                                | 5         | 0.11%   |
| Edimax Technology                     | 5         | 0.11%   |
| ZyDAS                                 | 3         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.07%   |
| TRENDnet                              | 2         | 0.04%   |
| Dell                                  | 2         | 0.04%   |
| Wilocity                              | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Panasonic (Matsushita)                | 1         | 0.02%   |
| Cypress Semiconductor                 | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| Belkin                                | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 294       | 6.32%   |
| Intel Wireless 8265 / 8275                                     | 181       | 3.89%   |
| Intel Wireless 7260                                            | 133       | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 125       | 2.69%   |
| Intel Wireless 7265                                            | 120       | 2.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 104       | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 102       | 2.19%   |
| Intel Wireless 8260                                            | 99        | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 96        | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 95        | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 93        | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 88        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 87        | 1.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 81        | 1.74%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 76        | 1.63%   |
| Intel Wi-Fi 6 AX201                                            | 74        | 1.59%   |
| Intel Wireless-AC 9260                                         | 67        | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 65        | 1.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 60        | 1.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 55        | 1.18%   |
| Intel Wireless 3165                                            | 55        | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 53        | 1.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 53        | 1.14%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 52        | 1.12%   |
| Intel Centrino Ultimate-N 6300                                 | 52        | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 51        | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 49        | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 49        | 1.05%   |
| Realtek 802.11ac NIC                                           | 45        | 0.97%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 43        | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 40        | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 39        | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 39        | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 38        | 0.82%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 38        | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 36        | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 36        | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 35        | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 34        | 0.73%   |
| Intel Centrino Wireless-N 2230                                 | 34        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2391      | 44.95%  |
| Intel                             | 1785      | 33.56%  |
| Broadcom                          | 300       | 5.64%   |
| Qualcomm Atheros                  | 285       | 5.36%   |
| Marvell Technology Group          | 113       | 2.12%   |
| Nvidia                            | 101       | 1.9%    |
| ASIX Electronics                  | 67        | 1.26%   |
| Broadcom Limited                  | 61        | 1.15%   |
| Samsung Electronics               | 37        | 0.7%    |
| Aquantia                          | 24        | 0.45%   |
| DisplayLink                       | 20        | 0.38%   |
| Lenovo                            | 16        | 0.3%    |
| D-Link System                     | 13        | 0.24%   |
| Google                            | 11        | 0.21%   |
| TP-Link                           | 8         | 0.15%   |
| Mellanox Technologies             | 7         | 0.13%   |
| Apple                             | 7         | 0.13%   |
| VIA Technologies                  | 5         | 0.09%   |
| Hewlett-Packard                   | 5         | 0.09%   |
| Microsoft                         | 4         | 0.08%   |
| LG Electronics                    | 4         | 0.08%   |
| D-Link                            | 4         | 0.08%   |
| Xiaomi                            | 3         | 0.06%   |
| Research In Motion                | 3         | 0.06%   |
| Microchip Technology              | 3         | 0.06%   |
| MediaTek                          | 3         | 0.06%   |
| JMicron Technology                | 3         | 0.06%   |
| Dell                              | 3         | 0.06%   |
| American Megatrends               | 3         | 0.06%   |
| 3Com                              | 3         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.04%   |
| Motorola PCS                      | 2         | 0.04%   |
| Linksys                           | 2         | 0.04%   |
| ICS Advent                        | 2         | 0.04%   |
| IBM                               | 2         | 0.04%   |
| Huawei Technologies               | 2         | 0.04%   |
| HMD Global                        | 2         | 0.04%   |
| Chelsio Communications            | 2         | 0.04%   |
| Sundance Technology Inc / IC Plus | 1         | 0.02%   |
| Sun Microsystems                  | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1770      | 32.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 322       | 5.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 282       | 5.16%   |
| Intel I211 Gigabit Network Connection                             | 175       | 3.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 148       | 2.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 144       | 2.63%   |
| Intel Ethernet Connection I217-LM                                 | 111       | 2.03%   |
| Intel Ethernet Connection (2) I219-V                              | 101       | 1.85%   |
| Intel Ethernet Controller I225-V                                  | 88        | 1.61%   |
| Intel 82579V Gigabit Network Connection                           | 69        | 1.26%   |
| Intel Ethernet Connection (7) I219-V                              | 59        | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 55        | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                             | 54        | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 54        | 0.99%   |
| Intel 82577LM Gigabit Network Connection                          | 53        | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 50        | 0.91%   |
| Intel 82574L Gigabit Network Connection                           | 50        | 0.91%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 45        | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 43        | 0.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 43        | 0.79%   |
| Intel Ethernet Connection (2) I218-V                              | 40        | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 37        | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 37        | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 34        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 32        | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 30        | 0.55%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.55%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 29        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 29        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 28        | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                             | 28        | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 28        | 0.51%   |
| Nvidia MCP79 Ethernet                                             | 26        | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 26        | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 25        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 24        | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 24        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4965      | 53.27%  |
| WiFi     | 4286      | 45.98%  |
| Modem    | 58        | 0.62%   |
| Unknown  | 12        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3179      | 52.75%  |
| Ethernet | 2847      | 47.25%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3168      | 54.97%  |
| 1     | 2241      | 38.89%  |
| 3     | 179       | 3.11%   |
| 0     | 115       | 2%      |
| 4     | 32        | 0.56%   |
| 5     | 13        | 0.23%   |
| 6     | 7         | 0.12%   |
| 12    | 2         | 0.03%   |
| 8     | 2         | 0.03%   |
| 22    | 1         | 0.02%   |
| 21    | 1         | 0.02%   |
| 10    | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4946      | 85.13%  |
| Yes  | 864       | 14.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1655      | 48.52%  |
| Realtek Semiconductor           | 226       | 6.63%   |
| Broadcom                        | 224       | 6.57%   |
| Qualcomm Atheros Communications | 223       | 6.54%   |
| Apple                           | 188       | 5.51%   |
| Cambridge Silicon Radio         | 175       | 5.13%   |
| IMC Networks                    | 169       | 4.95%   |
| Lite-On Technology              | 133       | 3.9%    |
| Foxconn / Hon Hai               | 97        | 2.84%   |
| ASUSTek Computer                | 90        | 2.64%   |
| Dell                            | 42        | 1.23%   |
| Hewlett-Packard                 | 31        | 0.91%   |
| MediaTek                        | 27        | 0.79%   |
| Marvell Semiconductor           | 21        | 0.62%   |
| Ralink                          | 16        | 0.47%   |
| Toshiba                         | 15        | 0.44%   |
| Dynex                           | 14        | 0.41%   |
| TP-Link                         | 11        | 0.32%   |
| Realtek                         | 10        | 0.29%   |
| Alps Electric                   | 8         | 0.23%   |
| Micro Star International        | 5         | 0.15%   |
| Logitech                        | 5         | 0.15%   |
| USI                             | 3         | 0.09%   |
| Primax Electronics              | 3         | 0.09%   |
| Integrated System Solution      | 3         | 0.09%   |
| SINO WEALTH                     | 2         | 0.06%   |
| Ralink Technology               | 2         | 0.06%   |
| Zeevo                           | 1         | 0.03%   |
| Taiyo Yuden                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Nintendo                        | 1         | 0.03%   |
| Kensington                      | 1         | 0.03%   |
| ISSC                            | 1         | 0.03%   |
| HTC (High Tech Computer)        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Foxconn International           | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| D-Link System                   | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 585       | 17.12%  |
| Intel AX200 Bluetooth                                    | 281       | 8.22%   |
| Intel AX201 Bluetooth                                    | 248       | 7.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 175       | 5.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 172       | 5.03%   |
| Intel Bluetooth Device                                   | 168       | 4.92%   |
| Realtek Bluetooth Radio                                  | 162       | 4.74%   |
| Qualcomm Atheros  Bluetooth Device                       | 108       | 3.16%   |
| IMC Networks Bluetooth Radio                             | 86        | 2.52%   |
| Apple Bluetooth Host Controller                          | 85        | 2.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 64        | 1.87%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 62        | 1.81%   |
| Intel AX210 Bluetooth                                    | 59        | 1.73%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 59        | 1.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 50        | 1.46%   |
| Realtek  Bluetooth 4.2 Adapter                           | 42        | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                       | 41        | 1.2%    |
| Apple Bluetooth USB Host Controller                      | 38        | 1.11%   |
| Apple Bluetooth HCI                                      | 37        | 1.08%   |
| Lite-On Atheros AR3012 Bluetooth                         | 36        | 1.05%   |
| Broadcom BCM2045B (BDC-2.1)                              | 35        | 1.02%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 33        | 0.97%   |
| IMC Networks Wireless_Device                             | 31        | 0.91%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 31        | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 28        | 0.82%   |
| MediaTek Wireless_Device                                 | 27        | 0.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 27        | 0.79%   |
| Lite-On Bluetooth Device                                 | 24        | 0.7%    |
| IMC Networks Bluetooth Device                            | 23        | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 22        | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 22        | 0.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 21        | 0.61%   |
| Broadcom HP Portable SoftSailing                         | 18        | 0.53%   |
| Ralink RT3290 Bluetooth                                  | 16        | 0.47%   |
| Marvell Bluetooth and Wireless LAN Composite             | 16        | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                         | 16        | 0.47%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 15        | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 14        | 0.41%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 14        | 0.41%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 14        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3890      | 46.83%  |
| AMD                                  | 1889      | 22.74%  |
| Nvidia                               | 1489      | 17.93%  |
| C-Media Electronics                  | 172       | 2.07%   |
| Logitech                             | 94        | 1.13%   |
| Creative Labs                        | 64        | 0.77%   |
| Corsair                              | 36        | 0.43%   |
| Realtek Semiconductor                | 35        | 0.42%   |
| Texas Instruments                    | 32        | 0.39%   |
| JMTek                                | 32        | 0.39%   |
| Razer USA                            | 28        | 0.34%   |
| Blue Microphones                     | 28        | 0.34%   |
| SteelSeries ApS                      | 27        | 0.33%   |
| Focusrite-Novation                   | 27        | 0.33%   |
| Creative Technology                  | 27        | 0.33%   |
| ASUSTek Computer                     | 25        | 0.3%    |
| Kingston Technology                  | 22        | 0.26%   |
| GN Netcom                            | 21        | 0.25%   |
| Plantronics                          | 20        | 0.24%   |
| Lenovo                               | 18        | 0.22%   |
| Samson Technologies                  | 15        | 0.18%   |
| GYROCOM C&C                          | 14        | 0.17%   |
| Sony                                 | 12        | 0.14%   |
| Micro Star International             | 12        | 0.14%   |
| Generalplus Technology               | 12        | 0.14%   |
| VIA Technologies                     | 11        | 0.13%   |
| M-Audio                              | 10        | 0.12%   |
| Hewlett-Packard                      | 9         | 0.11%   |
| Dell                                 | 9         | 0.11%   |
| XMOS                                 | 7         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 7         | 0.08%   |
| SAVITECH                             | 7         | 0.08%   |
| FiiO Electronics Technology          | 7         | 0.08%   |
| Cambridge Silicon Radio              | 7         | 0.08%   |
| Audio-Technica                       | 7         | 0.08%   |
| Yamaha                               | 6         | 0.07%   |
| Tenx Technology                      | 6         | 0.07%   |
| Bose                                 | 6         | 0.07%   |
| Apple                                | 6         | 0.07%   |
| Sennheiser Communications            | 5         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 399       | 4.07%   |
| AMD Family 17h/19h HD Audio Controller                                     | 383       | 3.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 358       | 3.65%   |
| Intel Sunrise Point-LP HD Audio                                            | 352       | 3.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 293       | 2.99%   |
| AMD Starship/Matisse HD Audio Controller                                   | 293       | 2.99%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 256       | 2.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 237       | 2.42%   |
| AMD FCH Azalia Controller                                                  | 224       | 2.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 218       | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 200       | 2.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 193       | 1.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 184       | 1.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 160       | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 152       | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 141       | 1.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 121       | 1.23%   |
| Intel 8 Series HD Audio Controller                                         | 121       | 1.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 121       | 1.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 119       | 1.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 112       | 1.14%   |
| Intel 200 Series PCH HD Audio                                              | 110       | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 108       | 1.1%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 107       | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                   | 105       | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 99        | 1.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 98        | 1%      |
| Intel Comet Lake PCH cAVS                                                  | 94        | 0.96%   |
| Intel Broadwell-U Audio Controller                                         | 92        | 0.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 92        | 0.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 91        | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                              | 86        | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                              | 86        | 0.88%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 86        | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 84        | 0.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 84        | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                              | 81        | 0.83%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 79        | 0.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 78        | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                         | 75        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 662       | 19.53%  |
| SK hynix                   | 619       | 18.26%  |
| Kingston                   | 400       | 11.8%   |
| Micron Technology          | 343       | 10.12%  |
| Unknown                    | 321       | 9.47%   |
| G.Skill                    | 238       | 7.02%   |
| Corsair                    | 218       | 6.43%   |
| Crucial                    | 149       | 4.4%    |
| Elpida                     | 62        | 1.83%   |
| Nanya Technology           | 58        | 1.71%   |
| A-DATA Technology          | 55        | 1.62%   |
| Ramaxel Technology         | 53        | 1.56%   |
| Patriot                    | 33        | 0.97%   |
| Unknown                    | 26        | 0.77%   |
| Team                       | 19        | 0.56%   |
| Timetec                    | 11        | 0.32%   |
| Unknown (ABCD)             | 9         | 0.27%   |
| Unifosa                    | 8         | 0.24%   |
| Transcend                  | 8         | 0.24%   |
| ASint Technology           | 8         | 0.24%   |
| Toshiba                    | 6         | 0.18%   |
| Goldkey                    | 5         | 0.15%   |
| ff                         | 5         | 0.15%   |
| Avant                      | 5         | 0.15%   |
| 4ea5                       | 5         | 0.15%   |
| Neo Forza                  | 4         | 0.12%   |
| CSX                        | 4         | 0.12%   |
| Sesame                     | 3         | 0.09%   |
| Qimonda                    | 3         | 0.09%   |
| PNY                        | 3         | 0.09%   |
| OCZ                        | 3         | 0.09%   |
| Hewlett-Packard            | 3         | 0.09%   |
| Unknown (7F7F7F94FFFFFFFF) | 2         | 0.06%   |
| Unknown (0x0C26)           | 2         | 0.06%   |
| SHARETRONIC                | 2         | 0.06%   |
| Mushkin                    | 2         | 0.06%   |
| fef5                       | 2         | 0.06%   |
| Axiom                      | 2         | 0.06%   |
| Apacer                     | 2         | 0.06%   |
| Unknown (0x7FFF)           | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 34        | 0.93%   |
| Unknown                                                          | 26        | 0.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 24        | 0.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 22        | 0.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 0.6%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 22        | 0.6%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 21        | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 20        | 0.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.52%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s          | 19        | 0.52%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s              | 18        | 0.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.46%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.46%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3866MT/s           | 17        | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 16        | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 15        | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 14        | 0.38%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 0.35%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 13        | 0.35%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 13        | 0.35%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 13        | 0.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.35%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 13        | 0.35%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 12        | 0.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 11        | 0.3%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 11        | 0.3%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 10        | 0.27%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.27%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 10        | 0.27%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 10        | 0.27%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.27%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 0.27%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 10        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR4            | 1234      | 42.82%  |
| DDR3            | 1032      | 35.81%  |
| DDR2            | 157       | 5.45%   |
| LPDDR4          | 106       | 3.68%   |
| LPDDR3          | 83        | 2.88%   |
| SDRAM           | 80        | 2.78%   |
| Unknown         | 70        | 2.43%   |
| DDR5            | 61        | 2.12%   |
| DDR             | 35        | 1.21%   |
| LPDDR5          | 19        | 0.66%   |
| DRAM            | 4         | 0.14%   |
| Logical non-vol | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1398      | 49.07%  |
| DIMM            | 1222      | 42.89%  |
| Row Of Chips    | 190       | 6.67%   |
| Chip            | 20        | 0.7%    |
| Unknown         | 14        | 0.49%   |
| FB-DIMM         | 4         | 0.14%   |
| Proprietary Car | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1195      | 37.27%  |
| 4096   | 828       | 25.83%  |
| 16384  | 485       | 15.13%  |
| 2048   | 427       | 13.32%  |
| 1024   | 133       | 4.15%   |
| 32768  | 115       | 3.59%   |
| 512    | 16        | 0.5%    |
| 65536  | 3         | 0.09%   |
| 256    | 2         | 0.06%   |
| 129408 | 1         | 0.03%   |
| 64     | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 615       | 19.52%  |
| 3200    | 400       | 12.69%  |
| 2667    | 360       | 11.42%  |
| 1333    | 266       | 8.44%   |
| 2400    | 212       | 6.73%   |
| 2133    | 156       | 4.95%   |
| 3600    | 110       | 3.49%   |
| 667     | 85        | 2.7%    |
| 1334    | 84        | 2.67%   |
| 1867    | 81        | 2.57%   |
| 800     | 75        | 2.38%   |
| 4267    | 51        | 1.62%   |
| 1067    | 51        | 1.62%   |
| Unknown | 46        | 1.46%   |
| 1066    | 39        | 1.24%   |
| 4800    | 38        | 1.21%   |
| 3266    | 32        | 1.02%   |
| 6400    | 26        | 0.83%   |
| 1866    | 26        | 0.83%   |
| 3866    | 25        | 0.79%   |
| 3733    | 25        | 0.79%   |
| 3800    | 23        | 0.73%   |
| 1800    | 21        | 0.67%   |
| 2666    | 18        | 0.57%   |
| 3400    | 15        | 0.48%   |
| 3000    | 15        | 0.48%   |
| 2933    | 15        | 0.48%   |
| 533     | 15        | 0.48%   |
| 4199    | 14        | 0.44%   |
| 8400    | 13        | 0.41%   |
| 4266    | 13        | 0.41%   |
| 3533    | 13        | 0.41%   |
| 975     | 10        | 0.32%   |
| 2800    | 9         | 0.29%   |
| 2048    | 9         | 0.29%   |
| 3666    | 8         | 0.25%   |
| 3534    | 8         | 0.25%   |
| 2465    | 8         | 0.25%   |
| 1639    | 8         | 0.25%   |
| 400     | 8         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Brother Industries       | 75        | 32.47%  |
| Hewlett-Packard          | 65        | 28.14%  |
| Samsung Electronics      | 35        | 15.15%  |
| Canon                    | 31        | 13.42%  |
| Seiko Epson              | 12        | 5.19%   |
| Lexmark International    | 4         | 1.73%   |
| Dymo-CoStar              | 3         | 1.3%    |
| Dell                     | 2         | 0.87%   |
| Zhuhai Poskey Technology | 1         | 0.43%   |
| Xerox                    | 1         | 0.43%   |
| QinHeng Electronics      | 1         | 0.43%   |
| Prolific Technology      | 1         | 0.43%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Brother Printer                      | 11        | 4.64%   |
| HP LaserJet 1020                     | 6         | 2.53%   |
| Brother HL-L2320D series             | 6         | 2.53%   |
| HP LaserJet 1018                     | 5         | 2.11%   |
| Brother HL-L2390DW                   | 5         | 2.11%   |
| Seiko Epson L6160 Series             | 4         | 1.69%   |
| Samsung ML-216x Series Laser Printer | 4         | 1.69%   |
| Brother MFC-J480DW                   | 4         | 1.69%   |
| Brother HL-5370DW series             | 4         | 1.69%   |
| Brother HL-2270DW Laser Printer      | 4         | 1.69%   |
| Samsung ML-1670 Series               | 3         | 1.27%   |
| Samsung M267x 287x Series            | 3         | 1.27%   |
| HP LaserJet 4250                     | 3         | 1.27%   |
| HP ENVY 4520 series                  | 3         | 1.27%   |
| HP DeskJet 3630 series               | 3         | 1.27%   |
| HP DeskJet 2600 series               | 3         | 1.27%   |
| Canon PIXMA MX920 Series             | 3         | 1.27%   |
| Canon PIXMA MG2900 Series            | 3         | 1.27%   |
| Brother MFC-9130CW                   | 3         | 1.27%   |
| Brother HL-L2360D series             | 3         | 1.27%   |
| Brother DCP-L2540DW                  | 3         | 1.27%   |
| Seiko Epson WF-3520 Series           | 2         | 0.84%   |
| Seiko Epson ET-3850 Series           | 2         | 0.84%   |
| Samsung SCX-3200 Series              | 2         | 0.84%   |
| Samsung ML-1660 Series               | 2         | 0.84%   |
| Samsung M2070 Series                 | 2         | 0.84%   |
| Samsung M2020 Series                 | 2         | 0.84%   |
| Samsung CLP-310 Color Laser Printer  | 2         | 0.84%   |
| Samsung C460 Series                  | 2         | 0.84%   |
| HP OfficeJet 3830 series             | 2         | 0.84%   |
| HP LaserJet Pro M201dw               | 2         | 0.84%   |
| HP LaserJet M101-M106                | 2         | 0.84%   |
| HP DeskJet F4200 series              | 2         | 0.84%   |
| HP DeskJet 3700 series               | 2         | 0.84%   |
| HP Deskjet 3050A                     | 2         | 0.84%   |
| HP Color LaserJet CP1215             | 2         | 0.84%   |
| Dymo-CoStar LabelWriter 450          | 2         | 0.84%   |
| Canon PIXMA MX530 Series             | 2         | 0.84%   |
| Canon MG2100 series                  | 2         | 0.84%   |
| Canon MF4410                         | 2         | 0.84%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 22        | 56.41%  |
| Hewlett-Packard | 9         | 23.08%  |
| Seiko Epson     | 7         | 17.95%  |
| AGFA-Gevaert NV | 1         | 2.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                 | 5         | 12.82%  |
| Canon CanoScan LiDE 700F                                | 4         | 10.26%  |
| Canon CanoScan LiDE 220                                 | 4         | 10.26%  |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 2         | 5.13%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]           | 2         | 5.13%   |
| HP ScanJet 82x0C                                        | 2         | 5.13%   |
| Canon CanoScan LiDE 120                                 | 2         | 5.13%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1         | 2.56%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 2.56%   |
| Seiko Epson GT-6600U [Perfection 610]                   | 1         | 2.56%   |
| HP ScanJet G4050                                        | 1         | 2.56%   |
| HP ScanJet G4010                                        | 1         | 2.56%   |
| HP ScanJet 5590                                         | 1         | 2.56%   |
| HP ScanJet 5200c                                        | 1         | 2.56%   |
| HP ScanJet 3670                                         | 1         | 2.56%   |
| HP ScanJet 3400cse                                      | 1         | 2.56%   |
| HP ScanJet 2200c                                        | 1         | 2.56%   |
| Canon CanoScan LiDE 70                                  | 1         | 2.56%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 2.56%   |
| Canon CanoScan LIDE 25                                  | 1         | 2.56%   |
| Canon CanoScan LiDE 200                                 | 1         | 2.56%   |
| Canon CanoScan LiDE 110                                 | 1         | 2.56%   |
| Canon CanoScan 4200F                                    | 1         | 2.56%   |
| Canon CanoScan                                          | 1         | 2.56%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                      | 1         | 2.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 592       | 18.84%  |
| Microdia                               | 322       | 10.25%  |
| Logitech                               | 304       | 9.68%   |
| IMC Networks                           | 265       | 8.43%   |
| Realtek Semiconductor                  | 219       | 6.97%   |
| Apple                                  | 188       | 5.98%   |
| Bison Electronics                      | 168       | 5.35%   |
| Sunplus Innovation Technology          | 162       | 5.16%   |
| Quanta                                 | 113       | 3.6%    |
| Suyin                                  | 98        | 3.12%   |
| Microsoft                              | 79        | 2.51%   |
| Cheng Uei Precision Industry (Foxlink) | 70        | 2.23%   |
| Lite-On Technology                     | 43        | 1.37%   |
| Acer                                   | 43        | 1.37%   |
| Syntek                                 | 42        | 1.34%   |
| Samsung Electronics                    | 42        | 1.34%   |
| Luxvisions Innotech Limited            | 41        | 1.3%    |
| Silicon Motion                         | 30        | 0.95%   |
| Ricoh                                  | 30        | 0.95%   |
| Lenovo                                 | 25        | 0.8%    |
| Importek                               | 20        | 0.64%   |
| Z-Star Microelectronics                | 19        | 0.6%    |
| AVerMedia Technologies                 | 17        | 0.54%   |
| MacroSilicon                           | 14        | 0.45%   |
| Alcor Micro                            | 14        | 0.45%   |
| Sonix Technology                       | 13        | 0.41%   |
| OmniVision Technologies                | 9         | 0.29%   |
| Generalplus Technology                 | 9         | 0.29%   |
| ALi                                    | 9         | 0.29%   |
| 2M UVC CAMERA                          | 9         | 0.29%   |
| LG Electronics                         | 8         | 0.25%   |
| Cubeternet                             | 8         | 0.25%   |
| Primax Electronics                     | 7         | 0.22%   |
| Creative Technology                    | 7         | 0.22%   |
| Linux Foundation                       | 6         | 0.19%   |
| Razer USA                              | 5         | 0.16%   |
| Huawei Technologies                    | 5         | 0.16%   |
| Hewlett-Packard                        | 5         | 0.16%   |
| Genesys Logic                          | 5         | 0.16%   |
| WaveRider Communications               | 4         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 133       | 4.2%    |
| Microdia Integrated_Webcam_HD           | 119       | 3.76%   |
| IMC Networks USB2.0 HD UVC WebCam       | 98        | 3.09%   |
| Realtek Integrated_Webcam_HD            | 84        | 2.65%   |
| Logitech HD Pro Webcam C920             | 82        | 2.59%   |
| Apple Built-in iSight                   | 68        | 2.15%   |
| Logitech Webcam C270                    | 59        | 1.86%   |
| Bison Integrated Camera                 | 55        | 1.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 54        | 1.7%    |
| IMC Networks Integrated Camera          | 53        | 1.67%   |
| Chicony HD WebCam                       | 46        | 1.45%   |
| Samsung Galaxy series, misc. (MTP mode) | 42        | 1.33%   |
| Sunplus Integrated_Webcam_HD            | 36        | 1.14%   |
| Microdia Integrated Webcam              | 34        | 1.07%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 34        | 1.07%   |
| Apple FaceTime HD Camera (Built-in)     | 33        | 1.04%   |
| Syntek Integrated Camera                | 29        | 0.92%   |
| Microdia Webcam Vitade AF               | 28        | 0.88%   |
| Sunplus HD WebCam                       | 27        | 0.85%   |
| Apple FaceTime HD Camera                | 27        | 0.85%   |
| Logitech C922 Pro Stream Webcam         | 26        | 0.82%   |
| Microsoft LifeCam HD-3000               | 24        | 0.76%   |
| Chicony VGA WebCam                      | 23        | 0.73%   |
| Chicony HP TrueVision HD                | 22        | 0.69%   |
| Chicony HP HD Camera                    | 21        | 0.66%   |
| Quanta HD User Facing                   | 20        | 0.63%   |
| Lite-On Integrated Camera               | 20        | 0.63%   |
| Chicony USB2.0 HD UVC WebCam            | 20        | 0.63%   |
| Quanta VGA WebCam                       | 19        | 0.6%    |
| Bison HD Webcam                         | 19        | 0.6%    |
| Quanta HP TrueVision HD Camera          | 18        | 0.57%   |
| Bison SunplusIT Integrated Camera       | 17        | 0.54%   |
| Realtek USB Camera                      | 16        | 0.5%    |
| Chicony USB 2.0 Camera                  | 16        | 0.5%    |
| Chicony TOSHIBA Web Camera - HD         | 16        | 0.5%    |
| Bison Lenovo EasyCamera                 | 16        | 0.5%    |
| IMC Networks VGA UVC WebCam             | 15        | 0.47%   |
| Chicony HD User Facing                  | 15        | 0.47%   |
| AVerMedia Live Streamer CAM 313         | 15        | 0.47%   |
| Sunplus HP HD Webcam [Fixed]            | 14        | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 219       | 37.5%   |
| Synaptics                          | 139       | 23.8%   |
| Shenzhen Goodix Technology         | 57        | 9.76%   |
| Elan Microelectronics              | 44        | 7.53%   |
| Upek                               | 37        | 6.34%   |
| AuthenTec                          | 35        | 5.99%   |
| LighTuning Technology              | 25        | 4.28%   |
| STMicroelectronics                 | 16        | 2.74%   |
| Focal-systems.Corp                 | 4         | 0.68%   |
| Samsung Electronics                | 2         | 0.34%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.34%   |
| Microsoft                          | 2         | 0.34%   |
| HOLTEK                             | 1         | 0.17%   |
| Dell                               | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 48        | 8.22%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 40        | 6.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 36        | 6.16%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 35        | 5.99%   |
| Elan ELAN:Fingerprint                                                      | 30        | 5.14%   |
| Validity Sensors Synaptics WBDI                                            | 29        | 4.97%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 4.79%   |
| Shenzhen Goodix FingerPrint                                                | 25        | 4.28%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 3.25%   |
| Validity Sensors VFS491                                                    | 19        | 3.25%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 2.91%   |
| STMicroelectronics Fingerprint Reader                                      | 16        | 2.74%   |
| Synaptics  WBDI                                                            | 15        | 2.57%   |
| Shenzhen Goodix  Fingerprint Device                                        | 15        | 2.57%   |
| AuthenTec AES2810                                                          | 15        | 2.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 2.4%    |
| Synaptics WBDI                                                             | 14        | 2.4%    |
| Validity Sensors Fingerprint scanner                                       | 11        | 1.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 1.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 10        | 1.71%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 1.54%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.37%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 1.37%   |
| Synaptics UWP WBDI                                                         | 8         | 1.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.2%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.2%    |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.2%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 1.2%    |
| Synaptics UWP WBDI Device                                                  | 6         | 1.03%   |
| Elan WBF Fingerprint Sensor                                                | 6         | 1.03%   |
| Elan ELAN:ARM-M4                                                           | 6         | 1.03%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 0.86%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.68%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.68%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.51%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 3         | 0.51%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 0.51%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.51%   |
| AuthenTec AES1600                                                          | 3         | 0.51%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 94        | 46.08%  |
| Alcor Micro               | 38        | 18.63%  |
| O2 Micro                  | 25        | 12.25%  |
| Upek                      | 22        | 10.78%  |
| Lenovo                    | 12        | 5.88%   |
| Gemalto (was Gemplus)     | 4         | 1.96%   |
| Yubico.com                | 2         | 0.98%   |
| SCM Microsystems          | 2         | 0.98%   |
| Aladdin Knowledge Systems | 2         | 0.98%   |
| In Focus Systems          | 1         | 0.49%   |
| Giesecke & Devrient       | 1         | 0.49%   |
| Clay Logic                | 1         | 0.49%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 50        | 24.51%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 35        | 17.16%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 10.78%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 10.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 9.31%   |
| Broadcom 5880                                                                | 15        | 7.35%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 5.88%   |
| Broadcom 58200                                                               | 9         | 4.41%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.96%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 1.96%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.47%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.98%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.49%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.49%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.49%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.49%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.49%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.49%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.49%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.49%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4174      | 70.95%  |
| 1     | 1370      | 23.29%  |
| 2     | 268       | 4.56%   |
| 3     | 46        | 0.78%   |
| 4     | 16        | 0.27%   |
| 5     | 5         | 0.08%   |
| 8     | 2         | 0.03%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 573       | 28.01%  |
| Graphics card            | 437       | 21.36%  |
| Net/wireless             | 298       | 14.57%  |
| Chipcard                 | 186       | 9.09%   |
| Communication controller | 119       | 5.82%   |
| Multimedia controller    | 115       | 5.62%   |
| Unassigned class         | 49        | 2.39%   |
| Bluetooth                | 43        | 2.1%    |
| Camera                   | 40        | 1.96%   |
| Storage                  | 36        | 1.76%   |
| Sound                    | 35        | 1.71%   |
| Net/ethernet             | 28        | 1.37%   |
| Network                  | 17        | 0.83%   |
| Modem                    | 15        | 0.73%   |
| Card reader              | 10        | 0.49%   |
| Storage/ide              | 9         | 0.44%   |
| Dvb card                 | 9         | 0.44%   |
| Firewire controller      | 8         | 0.39%   |
| Storage/raid             | 7         | 0.34%   |
| Flash memory             | 5         | 0.24%   |
| Tv card                  | 3         | 0.15%   |
| Video                    | 1         | 0.05%   |
| Unclassified device      | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |

