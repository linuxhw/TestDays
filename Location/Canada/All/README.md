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

Total: 6926

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 18E4                        | Desktop     | [1b1339be3d](https://linux-hardware.org/?probe=1b1339be3d) | Nov 02, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [fde67e1423](https://linux-hardware.org/?probe=fde67e1423) | Nov 02, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [e4d29df724](https://linux-hardware.org/?probe=e4d29df724) | Nov 02, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| Acer          | Aspire X1430                | Desktop     | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | 8054                        | Desktop     | [9e1b99d9bb](https://linux-hardware.org/?probe=9e1b99d9bb) | Nov 01, 2022 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [18db43ffed](https://linux-hardware.org/?probe=18db43ffed) | Oct 31, 2022 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [2ae72e7e22](https://linux-hardware.org/?probe=2ae72e7e22) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | Notebook    | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| Intel         | D33217GKE G76540-201        | Desktop     | [b3403874f4](https://linux-hardware.org/?probe=b3403874f4) | Oct 31, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [dfdf6532b6](https://linux-hardware.org/?probe=dfdf6532b6) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [b1027d78bc](https://linux-hardware.org/?probe=b1027d78bc) | Oct 31, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [296d9a0f38](https://linux-hardware.org/?probe=296d9a0f38) | Oct 31, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [07a165b373](https://linux-hardware.org/?probe=07a165b373) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [54c64976ee](https://linux-hardware.org/?probe=54c64976ee) | Oct 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [861aaf5a99](https://linux-hardware.org/?probe=861aaf5a99) | Oct 29, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [768d0e85c9](https://linux-hardware.org/?probe=768d0e85c9) | Oct 29, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [ce9df2cf8f](https://linux-hardware.org/?probe=ce9df2cf8f) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [91f4cd151f](https://linux-hardware.org/?probe=91f4cd151f) | Oct 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [30f6ad7a26](https://linux-hardware.org/?probe=30f6ad7a26) | Oct 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [b81923dbd2](https://linux-hardware.org/?probe=b81923dbd2) | Oct 29, 2022 |
| HP            | 18E4                        | Desktop     | [9d0444b1b8](https://linux-hardware.org/?probe=9d0444b1b8) | Oct 28, 2022 |
| Acer          | Aspire TC-710 V:1.1         | Desktop     | [b9c0f59afa](https://linux-hardware.org/?probe=b9c0f59afa) | Oct 28, 2022 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [22ec61d307](https://linux-hardware.org/?probe=22ec61d307) | Oct 28, 2022 |
| HP            | G60                         | Notebook    | [e9af8a9e61](https://linux-hardware.org/?probe=e9af8a9e61) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [ed6d5efa84](https://linux-hardware.org/?probe=ed6d5efa84) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [2829b0b18f](https://linux-hardware.org/?probe=2829b0b18f) | Oct 28, 2022 |
| Acer          | AOD257                      | Notebook    | [d3efba72cc](https://linux-hardware.org/?probe=d3efba72cc) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [6263763f01](https://linux-hardware.org/?probe=6263763f01) | Oct 27, 2022 |
| Acer          | AOD257                      | Notebook    | [c399f9db2b](https://linux-hardware.org/?probe=c399f9db2b) | Oct 27, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [f3c9ea3e12](https://linux-hardware.org/?probe=f3c9ea3e12) | Oct 27, 2022 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [ddfefe06a3](https://linux-hardware.org/?probe=ddfefe06a3) | Oct 27, 2022 |
| Oracle        | ASSY,MOTHERBOARD,1U         | Server      | [fec3d1a36e](https://linux-hardware.org/?probe=fec3d1a36e) | Oct 27, 2022 |
| Oracle        | ASSY,MB,X4-2, 1U            | Server      | [4622ac730a](https://linux-hardware.org/?probe=4622ac730a) | Oct 26, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [6faf6b40b1](https://linux-hardware.org/?probe=6faf6b40b1) | Oct 26, 2022 |
| Dell          | Precision 5570              | Notebook    | [67d7b55dab](https://linux-hardware.org/?probe=67d7b55dab) | Oct 26, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [c19eaa0502](https://linux-hardware.org/?probe=c19eaa0502) | Oct 26, 2022 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [126f440ca7](https://linux-hardware.org/?probe=126f440ca7) | Oct 26, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [07d56a833e](https://linux-hardware.org/?probe=07d56a833e) | Oct 25, 2022 |
| Panasonic     | CFSX4-1                     | Notebook    | [2ddae6e0e1](https://linux-hardware.org/?probe=2ddae6e0e1) | Oct 25, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [68aeedffa7](https://linux-hardware.org/?probe=68aeedffa7) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| Acer          | TravelMate B311-31          | Notebook    | [010dd1e876](https://linux-hardware.org/?probe=010dd1e876) | Oct 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [ce143b473f](https://linux-hardware.org/?probe=ce143b473f) | Oct 24, 2022 |
| ASRock        | Z97 Anniversary             | Desktop     | [9c94714d56](https://linux-hardware.org/?probe=9c94714d56) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [9312be9510](https://linux-hardware.org/?probe=9312be9510) | Oct 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [04ea0c7dd2](https://linux-hardware.org/?probe=04ea0c7dd2) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | Desktop     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [33bef6bb6f](https://linux-hardware.org/?probe=33bef6bb6f) | Oct 23, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [da114c9e74](https://linux-hardware.org/?probe=da114c9e74) | Oct 23, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [3d217d0a43](https://linux-hardware.org/?probe=3d217d0a43) | Oct 23, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [77bbf74390](https://linux-hardware.org/?probe=77bbf74390) | Oct 22, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [acbf2e94c1](https://linux-hardware.org/?probe=acbf2e94c1) | Oct 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [32a9b1de4f](https://linux-hardware.org/?probe=32a9b1de4f) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [66fae864f2](https://linux-hardware.org/?probe=66fae864f2) | Oct 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [2a02bdc30d](https://linux-hardware.org/?probe=2a02bdc30d) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [eaff8befe8](https://linux-hardware.org/?probe=eaff8befe8) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b2cc208474](https://linux-hardware.org/?probe=b2cc208474) | Oct 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [9042357a86](https://linux-hardware.org/?probe=9042357a86) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9f293160d5](https://linux-hardware.org/?probe=9f293160d5) | Oct 22, 2022 |
| Sony          | VPCEH3QFX                   | Notebook    | [def39e1ddd](https://linux-hardware.org/?probe=def39e1ddd) | Oct 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [21d541f98a](https://linux-hardware.org/?probe=21d541f98a) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [bfdfd5d11e](https://linux-hardware.org/?probe=bfdfd5d11e) | Oct 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ccc97b1211](https://linux-hardware.org/?probe=ccc97b1211) | Oct 21, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [0312fb4d88](https://linux-hardware.org/?probe=0312fb4d88) | Oct 21, 2022 |
| HP            | 18E4                        | Desktop     | [dfbdab6987](https://linux-hardware.org/?probe=dfbdab6987) | Oct 21, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | Notebook    | [77de0f71bd](https://linux-hardware.org/?probe=77de0f71bd) | Oct 21, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [837845f259](https://linux-hardware.org/?probe=837845f259) | Oct 20, 2022 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [9485d1e744](https://linux-hardware.org/?probe=9485d1e744) | Oct 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [33a4634aab](https://linux-hardware.org/?probe=33a4634aab) | Oct 20, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [b27ee147cf](https://linux-hardware.org/?probe=b27ee147cf) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6be0c6ee5f](https://linux-hardware.org/?probe=6be0c6ee5f) | Oct 20, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [a753c7bd58](https://linux-hardware.org/?probe=a753c7bd58) | Oct 20, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8105425af8](https://linux-hardware.org/?probe=8105425af8) | Oct 20, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [1f8284bf7d](https://linux-hardware.org/?probe=1f8284bf7d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6271fbb0fb](https://linux-hardware.org/?probe=6271fbb0fb) | Oct 19, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8dd98e14a1](https://linux-hardware.org/?probe=8dd98e14a1) | Oct 19, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [f275b2167f](https://linux-hardware.org/?probe=f275b2167f) | Oct 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [3c91e0c6ec](https://linux-hardware.org/?probe=3c91e0c6ec) | Oct 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00fece9d77](https://linux-hardware.org/?probe=00fece9d77) | Oct 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e000a30c5](https://linux-hardware.org/?probe=1e000a30c5) | Oct 18, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | Notebook    | [e480e5d6ae](https://linux-hardware.org/?probe=e480e5d6ae) | Oct 18, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [2a51555c53](https://linux-hardware.org/?probe=2a51555c53) | Oct 18, 2022 |
| Acer          | Spin SP513-52N              | Convertible | [465c32fbf8](https://linux-hardware.org/?probe=465c32fbf8) | Oct 18, 2022 |
| Acer          | Aspire one                  | Notebook    | [fced25613a](https://linux-hardware.org/?probe=fced25613a) | Oct 18, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [4b0c3a6022](https://linux-hardware.org/?probe=4b0c3a6022) | Oct 17, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [9fb7d8bf7f](https://linux-hardware.org/?probe=9fb7d8bf7f) | Oct 17, 2022 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [ac8367f142](https://linux-hardware.org/?probe=ac8367f142) | Oct 17, 2022 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [8c187fa369](https://linux-hardware.org/?probe=8c187fa369) | Oct 17, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [def45e1980](https://linux-hardware.org/?probe=def45e1980) | Oct 17, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [bc6696e1d5](https://linux-hardware.org/?probe=bc6696e1d5) | Oct 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6cbb7cbc35](https://linux-hardware.org/?probe=6cbb7cbc35) | Oct 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [ca934ff06b](https://linux-hardware.org/?probe=ca934ff06b) | Oct 16, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | Desktop     | [d91f9fb542](https://linux-hardware.org/?probe=d91f9fb542) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [daaa9d8dcc](https://linux-hardware.org/?probe=daaa9d8dcc) | Oct 16, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [63f9315478](https://linux-hardware.org/?probe=63f9315478) | Oct 16, 2022 |
| Google        | Coral                       | Notebook    | [a1811601a0](https://linux-hardware.org/?probe=a1811601a0) | Oct 15, 2022 |
| Google        | Coral                       | Notebook    | [93a674ea2b](https://linux-hardware.org/?probe=93a674ea2b) | Oct 15, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [beb41f73d2](https://linux-hardware.org/?probe=beb41f73d2) | Oct 15, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [7d6c345f35](https://linux-hardware.org/?probe=7d6c345f35) | Oct 15, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3a6855c328](https://linux-hardware.org/?probe=3a6855c328) | Oct 15, 2022 |
| Lenovo        | ThinkPad T460 20FMS4U300    | Notebook    | [bcdea92f5d](https://linux-hardware.org/?probe=bcdea92f5d) | Oct 15, 2022 |
| Lenovo        | ThinkPad T460 20FMS4U300    | Notebook    | [1a5aa81d1a](https://linux-hardware.org/?probe=1a5aa81d1a) | Oct 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [3f4c203116](https://linux-hardware.org/?probe=3f4c203116) | Oct 15, 2022 |
| Dell          | Latitude 3340               | Notebook    | [d99dbe3b99](https://linux-hardware.org/?probe=d99dbe3b99) | Oct 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d38b191e7](https://linux-hardware.org/?probe=2d38b191e7) | Oct 14, 2022 |
| HP            | 2B5B                        | Desktop     | [fc24a4bc99](https://linux-hardware.org/?probe=fc24a4bc99) | Oct 14, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2fb7882f4a](https://linux-hardware.org/?probe=2fb7882f4a) | Oct 14, 2022 |
| Dell          | Latitude E6400              | Notebook    | [3516901ea0](https://linux-hardware.org/?probe=3516901ea0) | Oct 14, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [76678b6d58](https://linux-hardware.org/?probe=76678b6d58) | Oct 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [f57f16d11b](https://linux-hardware.org/?probe=f57f16d11b) | Oct 13, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [55e6578ade](https://linux-hardware.org/?probe=55e6578ade) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4a4b8d42fc](https://linux-hardware.org/?probe=4a4b8d42fc) | Oct 13, 2022 |
| Dell          | 0D735T A00                  | Desktop     | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| Dell          | Precision M4800             | Notebook    | [9c9ad77c56](https://linux-hardware.org/?probe=9c9ad77c56) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| ASUSTek       | K53E                        | Notebook    | [ee3acd2da1](https://linux-hardware.org/?probe=ee3acd2da1) | Oct 11, 2022 |
| ASUSTek       | K53E                        | Notebook    | [8a8058467a](https://linux-hardware.org/?probe=8a8058467a) | Oct 11, 2022 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [89ee3db150](https://linux-hardware.org/?probe=89ee3db150) | Oct 11, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | Notebook    | [18c02300b9](https://linux-hardware.org/?probe=18c02300b9) | Oct 11, 2022 |
| Alienware     | Area-51m                    | Notebook    | [a227d548e4](https://linux-hardware.org/?probe=a227d548e4) | Oct 11, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c69cf9f20a](https://linux-hardware.org/?probe=c69cf9f20a) | Oct 11, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d96c361919](https://linux-hardware.org/?probe=d96c361919) | Oct 11, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [71c926fc14](https://linux-hardware.org/?probe=71c926fc14) | Oct 11, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [eca505496f](https://linux-hardware.org/?probe=eca505496f) | Oct 10, 2022 |
| Alienware     | 0NWN7M A00                  | Desktop     | [a7c3e67810](https://linux-hardware.org/?probe=a7c3e67810) | Oct 10, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [669c570a2e](https://linux-hardware.org/?probe=669c570a2e) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [11fb952122](https://linux-hardware.org/?probe=11fb952122) | Oct 10, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [b8e434e4db](https://linux-hardware.org/?probe=b8e434e4db) | Oct 10, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [8315e5ed7d](https://linux-hardware.org/?probe=8315e5ed7d) | Oct 10, 2022 |
| Dell          | 0X9M3X A01                  | Desktop     | [b729cadad8](https://linux-hardware.org/?probe=b729cadad8) | Oct 10, 2022 |
| HP            | 18E4                        | Desktop     | [6603067eba](https://linux-hardware.org/?probe=6603067eba) | Oct 10, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [c2193db5fb](https://linux-hardware.org/?probe=c2193db5fb) | Oct 09, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [0709f63ca7](https://linux-hardware.org/?probe=0709f63ca7) | Oct 09, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [db3419c5de](https://linux-hardware.org/?probe=db3419c5de) | Oct 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [1f013f181d](https://linux-hardware.org/?probe=1f013f181d) | Oct 09, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [19ad61d9c7](https://linux-hardware.org/?probe=19ad61d9c7) | Oct 09, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [67256f654b](https://linux-hardware.org/?probe=67256f654b) | Oct 08, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [b699753cc6](https://linux-hardware.org/?probe=b699753cc6) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [dfeb0c2791](https://linux-hardware.org/?probe=dfeb0c2791) | Oct 07, 2022 |
| Dell          | 0YP696 A00                  | Desktop     | [588d3a6132](https://linux-hardware.org/?probe=588d3a6132) | Oct 07, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [60c519a7dd](https://linux-hardware.org/?probe=60c519a7dd) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [b7c6acd46c](https://linux-hardware.org/?probe=b7c6acd46c) | Oct 06, 2022 |
| HP            | 18E4                        | Desktop     | [53c6bf7af4](https://linux-hardware.org/?probe=53c6bf7af4) | Oct 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | Notebook    | [b31ac1623d](https://linux-hardware.org/?probe=b31ac1623d) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | Notebook    | [9eaff58099](https://linux-hardware.org/?probe=9eaff58099) | Oct 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f7626421b2](https://linux-hardware.org/?probe=f7626421b2) | Oct 05, 2022 |
| Dell          | XPS 9320                    | Notebook    | [c4888023c3](https://linux-hardware.org/?probe=c4888023c3) | Oct 04, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [48901aff3f](https://linux-hardware.org/?probe=48901aff3f) | Oct 04, 2022 |
| Dell          | 082WXT A03                  | Desktop     | [dc5e0c794d](https://linux-hardware.org/?probe=dc5e0c794d) | Oct 04, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [4e56098080](https://linux-hardware.org/?probe=4e56098080) | Oct 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [6bc437ef3d](https://linux-hardware.org/?probe=6bc437ef3d) | Oct 03, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1f77699521](https://linux-hardware.org/?probe=1f77699521) | Oct 03, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [56fbace4f2](https://linux-hardware.org/?probe=56fbace4f2) | Oct 03, 2022 |
| Google        | Droid                       | Notebook    | [40550baeb8](https://linux-hardware.org/?probe=40550baeb8) | Oct 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [b2d146f923](https://linux-hardware.org/?probe=b2d146f923) | Oct 01, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [5c5353c8b6](https://linux-hardware.org/?probe=5c5353c8b6) | Oct 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [5077b42a8b](https://linux-hardware.org/?probe=5077b42a8b) | Oct 01, 2022 |
| ASRock        | Z77 Extreme3                | Desktop     | [c92633e1ee](https://linux-hardware.org/?probe=c92633e1ee) | Oct 01, 2022 |
| Dell          | Latitude E4300              | Notebook    | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| Lenovo        | ThinkPad T480 20L5001FUS    | Notebook    | [a7e0da7aa4](https://linux-hardware.org/?probe=a7e0da7aa4) | Sep 30, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [f9cf849f23](https://linux-hardware.org/?probe=f9cf849f23) | Sep 30, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [6cf53adb30](https://linux-hardware.org/?probe=6cf53adb30) | Sep 30, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [40e65e38cf](https://linux-hardware.org/?probe=40e65e38cf) | Sep 30, 2022 |
| HP            | 3398                        | Desktop     | [2f7b1d28b4](https://linux-hardware.org/?probe=2f7b1d28b4) | Sep 30, 2022 |
| HP            | 1496                        | Desktop     | [e89f06542b](https://linux-hardware.org/?probe=e89f06542b) | Sep 30, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [aa0eeeda6b](https://linux-hardware.org/?probe=aa0eeeda6b) | Sep 29, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [4118e245a3](https://linux-hardware.org/?probe=4118e245a3) | Sep 29, 2022 |
| Acer          | Veriton X6610G              | Desktop     | [66733e59e2](https://linux-hardware.org/?probe=66733e59e2) | Sep 29, 2022 |
| HP            | Notebook                    | Notebook    | [6b7215bcba](https://linux-hardware.org/?probe=6b7215bcba) | Sep 29, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [75c8af47c2](https://linux-hardware.org/?probe=75c8af47c2) | Sep 29, 2022 |
| Dell          | Latitude E6430              | Notebook    | [f3e5e0005d](https://linux-hardware.org/?probe=f3e5e0005d) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | Notebook    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [fe6539c021](https://linux-hardware.org/?probe=fe6539c021) | Sep 28, 2022 |
| Gigabyte      | AORUS 15P YD                | Notebook    | [61e297be71](https://linux-hardware.org/?probe=61e297be71) | Sep 28, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [8086625f5a](https://linux-hardware.org/?probe=8086625f5a) | Sep 28, 2022 |
| HP            | 212B                        | Desktop     | [38aa6e5478](https://linux-hardware.org/?probe=38aa6e5478) | Sep 28, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [bc3501546b](https://linux-hardware.org/?probe=bc3501546b) | Sep 28, 2022 |
| Dell          | 01V648 A06                  | Server      | [209c9b938c](https://linux-hardware.org/?probe=209c9b938c) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [89c48e7d5a](https://linux-hardware.org/?probe=89c48e7d5a) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b39aefdcda](https://linux-hardware.org/?probe=b39aefdcda) | Sep 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [fb2de59c3f](https://linux-hardware.org/?probe=fb2de59c3f) | Sep 27, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [e5405dd3d8](https://linux-hardware.org/?probe=e5405dd3d8) | Sep 27, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | Desktop     | [7af967061b](https://linux-hardware.org/?probe=7af967061b) | Sep 27, 2022 |
| Intel         | DP35DP AAD81073-208         | Desktop     | [031ff09179](https://linux-hardware.org/?probe=031ff09179) | Sep 27, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [ac96a56edf](https://linux-hardware.org/?probe=ac96a56edf) | Sep 27, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d7dcd834e2](https://linux-hardware.org/?probe=d7dcd834e2) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [45031620df](https://linux-hardware.org/?probe=45031620df) | Sep 27, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [4f58ff1174](https://linux-hardware.org/?probe=4f58ff1174) | Sep 26, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [a9ac678198](https://linux-hardware.org/?probe=a9ac678198) | Sep 26, 2022 |
| ASUSTek       | K52N                        | Notebook    | [8d7b00011f](https://linux-hardware.org/?probe=8d7b00011f) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| MSI           | GS65 Stealth 9SE            | Notebook    | [0c8e0eb1f5](https://linux-hardware.org/?probe=0c8e0eb1f5) | Sep 26, 2022 |
| MSI           | GE75 Raider 8SF             | Notebook    | [094a9b115b](https://linux-hardware.org/?probe=094a9b115b) | Sep 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [9a7ec70bad](https://linux-hardware.org/?probe=9a7ec70bad) | Sep 25, 2022 |
| Dell          | Inspiron 1440               | Notebook    | [c928a944c0](https://linux-hardware.org/?probe=c928a944c0) | Sep 24, 2022 |
| Gateway       | IPISB-VR                    | Desktop     | [21ee50eb69](https://linux-hardware.org/?probe=21ee50eb69) | Sep 24, 2022 |
| Dell          | Latitude E5510              | Notebook    | [04f4e9a803](https://linux-hardware.org/?probe=04f4e9a803) | Sep 24, 2022 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [405ea9a4ca](https://linux-hardware.org/?probe=405ea9a4ca) | Sep 24, 2022 |
| HP            | Notebook                    | Notebook    | [f4e47792c1](https://linux-hardware.org/?probe=f4e47792c1) | Sep 24, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [164ad85233](https://linux-hardware.org/?probe=164ad85233) | Sep 23, 2022 |
| Lenovo        | ThinkPad T61p 64575KU       | Notebook    | [a5e3ca7c25](https://linux-hardware.org/?probe=a5e3ca7c25) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ca6d2abcd9](https://linux-hardware.org/?probe=ca6d2abcd9) | Sep 23, 2022 |
| MSI           | 870-G45                     | Desktop     | [082307d0ce](https://linux-hardware.org/?probe=082307d0ce) | Sep 22, 2022 |
| HP            | 8309                        | Desktop     | [118f235878](https://linux-hardware.org/?probe=118f235878) | Sep 22, 2022 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [cdaec9c224](https://linux-hardware.org/?probe=cdaec9c224) | Sep 22, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [fb1cce613c](https://linux-hardware.org/?probe=fb1cce613c) | Sep 22, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [58b83fee74](https://linux-hardware.org/?probe=58b83fee74) | Sep 22, 2022 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [920bf9a750](https://linux-hardware.org/?probe=920bf9a750) | Sep 22, 2022 |
| Lenovo        | 1052 NOK                    | Desktop     | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [e40a8996c4](https://linux-hardware.org/?probe=e40a8996c4) | Sep 22, 2022 |
| Acer          | Aspire M3450                | Desktop     | [ff7d0a2394](https://linux-hardware.org/?probe=ff7d0a2394) | Sep 21, 2022 |
| Razer         | Blade                       | Notebook    | [c835fe2f90](https://linux-hardware.org/?probe=c835fe2f90) | Sep 21, 2022 |
| ASRock        | Z77 Extreme3                | Desktop     | [deb21d492d](https://linux-hardware.org/?probe=deb21d492d) | Sep 21, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Dell          | Latitude E4310              | Notebook    | [06dc3db422](https://linux-hardware.org/?probe=06dc3db422) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [090e33f643](https://linux-hardware.org/?probe=090e33f643) | Sep 20, 2022 |
| Acer          | Aspire E5-532               | Notebook    | [1d0f80e0f1](https://linux-hardware.org/?probe=1d0f80e0f1) | Sep 20, 2022 |
| Acer          | Aspire E5-532               | Notebook    | [f349ec9700](https://linux-hardware.org/?probe=f349ec9700) | Sep 20, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [df0348739e](https://linux-hardware.org/?probe=df0348739e) | Sep 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [9d26eb4243](https://linux-hardware.org/?probe=9d26eb4243) | Sep 19, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [66596e407c](https://linux-hardware.org/?probe=66596e407c) | Sep 19, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [d984474cba](https://linux-hardware.org/?probe=d984474cba) | Sep 19, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9776f2c20c](https://linux-hardware.org/?probe=9776f2c20c) | Sep 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [943bb9e023](https://linux-hardware.org/?probe=943bb9e023) | Sep 19, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [579f73fc88](https://linux-hardware.org/?probe=579f73fc88) | Sep 19, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [27d1f0c593](https://linux-hardware.org/?probe=27d1f0c593) | Sep 19, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [06f5febda2](https://linux-hardware.org/?probe=06f5febda2) | Sep 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [b707354c65](https://linux-hardware.org/?probe=b707354c65) | Sep 18, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [2e1e251503](https://linux-hardware.org/?probe=2e1e251503) | Sep 18, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [916e9d7e5e](https://linux-hardware.org/?probe=916e9d7e5e) | Sep 18, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [5f56e8b10f](https://linux-hardware.org/?probe=5f56e8b10f) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50da0a8acf](https://linux-hardware.org/?probe=50da0a8acf) | Sep 18, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [a191bd2a9f](https://linux-hardware.org/?probe=a191bd2a9f) | Sep 18, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [1f9f8ee511](https://linux-hardware.org/?probe=1f9f8ee511) | Sep 18, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| MSI           | 870-G45                     | Desktop     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| MSI           | 870-G45                     | Desktop     | [f360a57f01](https://linux-hardware.org/?probe=f360a57f01) | Sep 17, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [19d0260ef6](https://linux-hardware.org/?probe=19d0260ef6) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1b40e531b5](https://linux-hardware.org/?probe=1b40e531b5) | Sep 17, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4f1e683ced](https://linux-hardware.org/?probe=4f1e683ced) | Sep 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek       | LITHIUM                     | Desktop     | [3aab1aa49f](https://linux-hardware.org/?probe=3aab1aa49f) | Sep 16, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [e31f54dfa3](https://linux-hardware.org/?probe=e31f54dfa3) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [28a40721a8](https://linux-hardware.org/?probe=28a40721a8) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [70a944e816](https://linux-hardware.org/?probe=70a944e816) | Sep 16, 2022 |
| HP            | 1998                        | Desktop     | [f3ef7a85fe](https://linux-hardware.org/?probe=f3ef7a85fe) | Sep 16, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [31f9854044](https://linux-hardware.org/?probe=31f9854044) | Sep 16, 2022 |
| AZW           | GK mini                     | Desktop     | [19b8b4dc85](https://linux-hardware.org/?probe=19b8b4dc85) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a4dad191d2](https://linux-hardware.org/?probe=a4dad191d2) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [aa5d8a2fc6](https://linux-hardware.org/?probe=aa5d8a2fc6) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [8e62e03e0b](https://linux-hardware.org/?probe=8e62e03e0b) | Sep 15, 2022 |
| Google        | Droid                       | Notebook    | [b4acc4ee70](https://linux-hardware.org/?probe=b4acc4ee70) | Sep 15, 2022 |
| IBT.ca (IB... | MI836                       | Desktop     | [a180af0292](https://linux-hardware.org/?probe=a180af0292) | Sep 15, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [45309244c3](https://linux-hardware.org/?probe=45309244c3) | Sep 15, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [efb36530f1](https://linux-hardware.org/?probe=efb36530f1) | Sep 14, 2022 |
| Lenovo        | ThinkPad T510 4349BR8       | Notebook    | [d60b0c8539](https://linux-hardware.org/?probe=d60b0c8539) | Sep 14, 2022 |
| HP            | 1998                        | Desktop     | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [f614aa6ae7](https://linux-hardware.org/?probe=f614aa6ae7) | Sep 14, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [fc1d1cb3bc](https://linux-hardware.org/?probe=fc1d1cb3bc) | Sep 14, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [c3b834caec](https://linux-hardware.org/?probe=c3b834caec) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [3f34e5ed01](https://linux-hardware.org/?probe=3f34e5ed01) | Sep 14, 2022 |
| Dell          | Inspiron 5575               | Notebook    | [1ae871a545](https://linux-hardware.org/?probe=1ae871a545) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| HP            | 3031h                       | Desktop     | [9312c20d49](https://linux-hardware.org/?probe=9312c20d49) | Sep 13, 2022 |
| HP            | 3031h                       | Desktop     | [1bbfd867b0](https://linux-hardware.org/?probe=1bbfd867b0) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| DFI           | HD631-Q87CRM                | Desktop     | [b7ed9b1d64](https://linux-hardware.org/?probe=b7ed9b1d64) | Sep 12, 2022 |
| Dell          | XPS 9315                    | Notebook    | [77ecec9e58](https://linux-hardware.org/?probe=77ecec9e58) | Sep 12, 2022 |
| Dell          | XPS 9315                    | Notebook    | [cfaae58ffa](https://linux-hardware.org/?probe=cfaae58ffa) | Sep 12, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [47b15d6b6c](https://linux-hardware.org/?probe=47b15d6b6c) | Sep 12, 2022 |
| ECS           | Nettle3                     | Desktop     | [23f7f8708c](https://linux-hardware.org/?probe=23f7f8708c) | Sep 12, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [5a114e6867](https://linux-hardware.org/?probe=5a114e6867) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [276e6547f9](https://linux-hardware.org/?probe=276e6547f9) | Sep 11, 2022 |
| Dell          | Latitude 3190               | Notebook    | [14d836c020](https://linux-hardware.org/?probe=14d836c020) | Sep 11, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [bc6ffac174](https://linux-hardware.org/?probe=bc6ffac174) | Sep 11, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [f8be9f1680](https://linux-hardware.org/?probe=f8be9f1680) | Sep 11, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [51857d9758](https://linux-hardware.org/?probe=51857d9758) | Sep 11, 2022 |
| Lenovo        | ThinkPad L460 20FVS1BC0S    | Notebook    | [e668edf31d](https://linux-hardware.org/?probe=e668edf31d) | Sep 11, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [cf9447ce8c](https://linux-hardware.org/?probe=cf9447ce8c) | Sep 10, 2022 |
| HP            | 1998                        | Desktop     | [37cd896e72](https://linux-hardware.org/?probe=37cd896e72) | Sep 10, 2022 |
| HP            | 1998                        | Desktop     | [3da9c3ef8e](https://linux-hardware.org/?probe=3da9c3ef8e) | Sep 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [39c0297cb1](https://linux-hardware.org/?probe=39c0297cb1) | Sep 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [2c95ed7c92](https://linux-hardware.org/?probe=2c95ed7c92) | Sep 10, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2e9e331465](https://linux-hardware.org/?probe=2e9e331465) | Sep 10, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [9ce6958b9c](https://linux-hardware.org/?probe=9ce6958b9c) | Sep 09, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [c49fec0796](https://linux-hardware.org/?probe=c49fec0796) | Sep 09, 2022 |
| IBT.ca (IB... | MI836                       | Desktop     | [6155d5bd47](https://linux-hardware.org/?probe=6155d5bd47) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [48df4850fe](https://linux-hardware.org/?probe=48df4850fe) | Sep 09, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9690933a68](https://linux-hardware.org/?probe=9690933a68) | Sep 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f714986404](https://linux-hardware.org/?probe=f714986404) | Sep 08, 2022 |
| ASUSTek       | ROG Zephyrus S17 GX703HS... | Notebook    | [041c6dac05](https://linux-hardware.org/?probe=041c6dac05) | Sep 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3c4865fc8c](https://linux-hardware.org/?probe=3c4865fc8c) | Sep 08, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [e5067297e8](https://linux-hardware.org/?probe=e5067297e8) | Sep 07, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [6f32b647ec](https://linux-hardware.org/?probe=6f32b647ec) | Sep 07, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [2f4e7d54e0](https://linux-hardware.org/?probe=2f4e7d54e0) | Sep 07, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6d6c3a5320](https://linux-hardware.org/?probe=6d6c3a5320) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [47baad2eed](https://linux-hardware.org/?probe=47baad2eed) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [090d406ac3](https://linux-hardware.org/?probe=090d406ac3) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [d3d092e789](https://linux-hardware.org/?probe=d3d092e789) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [424adc035f](https://linux-hardware.org/?probe=424adc035f) | Sep 07, 2022 |
| ASUSTek       | ET2040I                     | Desktop     | [44ab433428](https://linux-hardware.org/?probe=44ab433428) | Sep 06, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [b506daf143](https://linux-hardware.org/?probe=b506daf143) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [ab4f06e457](https://linux-hardware.org/?probe=ab4f06e457) | Sep 05, 2022 |
| Lenovo        | ThinkPad X230 23252UU       | Notebook    | [0853f0ca45](https://linux-hardware.org/?probe=0853f0ca45) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [3c578ac6c8](https://linux-hardware.org/?probe=3c578ac6c8) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e6117fb016](https://linux-hardware.org/?probe=e6117fb016) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e8887916fa](https://linux-hardware.org/?probe=e8887916fa) | Sep 05, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [12fbd247f5](https://linux-hardware.org/?probe=12fbd247f5) | Sep 05, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [565c10e82f](https://linux-hardware.org/?probe=565c10e82f) | Sep 05, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e12af15c84](https://linux-hardware.org/?probe=e12af15c84) | Sep 05, 2022 |
| Samsung       | 730QED                      | Convertible | [9af6e3d69d](https://linux-hardware.org/?probe=9af6e3d69d) | Sep 05, 2022 |
| Dell          | Inspiron 15 3525            | Notebook    | [0ec2aca595](https://linux-hardware.org/?probe=0ec2aca595) | Sep 04, 2022 |
| ASUSTek       | Q170M-C                     | Desktop     | [6710f3ecd0](https://linux-hardware.org/?probe=6710f3ecd0) | Sep 04, 2022 |
| ASUSTek       | KCMA-D8                     | Desktop     | [df5fdfccf0](https://linux-hardware.org/?probe=df5fdfccf0) | Sep 04, 2022 |
| HP            | 2ADC                        | Desktop     | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| Intel         | DQ67SW AAG12527-306         | Desktop     | [9ab6c11be2](https://linux-hardware.org/?probe=9ab6c11be2) | Sep 04, 2022 |
| MSI           | H81M-E34                    | Desktop     | [0fa7f79fdc](https://linux-hardware.org/?probe=0fa7f79fdc) | Sep 03, 2022 |
| Lenovo        | IdeaPad Flex-15IWL 81SR     | Convertible | [6723781de1](https://linux-hardware.org/?probe=6723781de1) | Sep 03, 2022 |
| Dell          | 0FGCC7 A01                  | Server      | [4689cac5c7](https://linux-hardware.org/?probe=4689cac5c7) | Sep 03, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [9567e25730](https://linux-hardware.org/?probe=9567e25730) | Sep 03, 2022 |
| Lenovo        | ThinkPad T410 2518F5U       | Notebook    | [9b61c2fbcc](https://linux-hardware.org/?probe=9b61c2fbcc) | Sep 02, 2022 |
| Acer          | Aspire M3910                | Desktop     | [17c1079582](https://linux-hardware.org/?probe=17c1079582) | Sep 02, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [27840cf8d2](https://linux-hardware.org/?probe=27840cf8d2) | Sep 02, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [18756268eb](https://linux-hardware.org/?probe=18756268eb) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [b3b1ffd7ff](https://linux-hardware.org/?probe=b3b1ffd7ff) | Sep 02, 2022 |
| Acer          | Aspire TC-605               | Desktop     | [fa13174432](https://linux-hardware.org/?probe=fa13174432) | Sep 02, 2022 |
| Lenovo        | ThinkPad T410 2518F5U       | Notebook    | [95e8dcce67](https://linux-hardware.org/?probe=95e8dcce67) | Sep 02, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [969ebd4d3a](https://linux-hardware.org/?probe=969ebd4d3a) | Sep 01, 2022 |
| Dell          | 0R6PCT A01                  | Desktop     | [02af50752e](https://linux-hardware.org/?probe=02af50752e) | Sep 01, 2022 |
| Acer          | Aspire TC-605               | Desktop     | [fdc6b95d8b](https://linux-hardware.org/?probe=fdc6b95d8b) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a2878122de](https://linux-hardware.org/?probe=a2878122de) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [836d60c547](https://linux-hardware.org/?probe=836d60c547) | Sep 01, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [d48b9efca4](https://linux-hardware.org/?probe=d48b9efca4) | Sep 01, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [18822e9fbe](https://linux-hardware.org/?probe=18822e9fbe) | Sep 01, 2022 |
| Acer          | Aspire 5810T                | Notebook    | [6f807b1a84](https://linux-hardware.org/?probe=6f807b1a84) | Sep 01, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [d6e9455a63](https://linux-hardware.org/?probe=d6e9455a63) | Aug 31, 2022 |
| JGINYUE       | B85I PLUS V2.1              | Desktop     | [d171691ef3](https://linux-hardware.org/?probe=d171691ef3) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [6eeadaf886](https://linux-hardware.org/?probe=6eeadaf886) | Aug 31, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [b2456009ae](https://linux-hardware.org/?probe=b2456009ae) | Aug 31, 2022 |
| ASUSTek       | K401UQK                     | Notebook    | [4f026584d7](https://linux-hardware.org/?probe=4f026584d7) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [56e8f54a3e](https://linux-hardware.org/?probe=56e8f54a3e) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [20da9d42a4](https://linux-hardware.org/?probe=20da9d42a4) | Aug 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [39ae8218f6](https://linux-hardware.org/?probe=39ae8218f6) | Aug 30, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [413bd5a721](https://linux-hardware.org/?probe=413bd5a721) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [9274f5e876](https://linux-hardware.org/?probe=9274f5e876) | Aug 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a8acbb8d0b](https://linux-hardware.org/?probe=a8acbb8d0b) | Aug 28, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [b9803fd1ba](https://linux-hardware.org/?probe=b9803fd1ba) | Aug 28, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [f0e2de2452](https://linux-hardware.org/?probe=f0e2de2452) | Aug 28, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [3ce9a33fed](https://linux-hardware.org/?probe=3ce9a33fed) | Aug 28, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [2adf8e9ff6](https://linux-hardware.org/?probe=2adf8e9ff6) | Aug 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a328df0016](https://linux-hardware.org/?probe=a328df0016) | Aug 28, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [995ab78b23](https://linux-hardware.org/?probe=995ab78b23) | Aug 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [505d987d1e](https://linux-hardware.org/?probe=505d987d1e) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Lenovo        | ThinkPad T430 2349DG5       | Notebook    | [740898521d](https://linux-hardware.org/?probe=740898521d) | Aug 27, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [8faac70cfa](https://linux-hardware.org/?probe=8faac70cfa) | Aug 27, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [72cf4f38cf](https://linux-hardware.org/?probe=72cf4f38cf) | Aug 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [704ce84e6a](https://linux-hardware.org/?probe=704ce84e6a) | Aug 27, 2022 |
| Intel         | DH87RL AAG74240-401         | Desktop     | [814718547c](https://linux-hardware.org/?probe=814718547c) | Aug 27, 2022 |
| Lenovo        | ThinkPad T430 2344BMU       | Notebook    | [c164d20c15](https://linux-hardware.org/?probe=c164d20c15) | Aug 26, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [04f9f63255](https://linux-hardware.org/?probe=04f9f63255) | Aug 26, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [83377b24dc](https://linux-hardware.org/?probe=83377b24dc) | Aug 25, 2022 |
| MSI           | WF75 10TK                   | Notebook    | [8f395376ba](https://linux-hardware.org/?probe=8f395376ba) | Aug 25, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | Notebook    | [73a97b425c](https://linux-hardware.org/?probe=73a97b425c) | Aug 25, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [8d1cad5e52](https://linux-hardware.org/?probe=8d1cad5e52) | Aug 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [d2e2d5484c](https://linux-hardware.org/?probe=d2e2d5484c) | Aug 25, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [005afabbff](https://linux-hardware.org/?probe=005afabbff) | Aug 25, 2022 |
| HP            | 18E4                        | Desktop     | [13d5c6848a](https://linux-hardware.org/?probe=13d5c6848a) | Aug 24, 2022 |
| Google        | Rabbid                      | Notebook    | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [80cfa18cfd](https://linux-hardware.org/?probe=80cfa18cfd) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d1cae6aca8](https://linux-hardware.org/?probe=d1cae6aca8) | Aug 24, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [5e62f9adde](https://linux-hardware.org/?probe=5e62f9adde) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ba1940016e](https://linux-hardware.org/?probe=ba1940016e) | Aug 23, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [1de0aeba8f](https://linux-hardware.org/?probe=1de0aeba8f) | Aug 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [04b0de9007](https://linux-hardware.org/?probe=04b0de9007) | Aug 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bcd3bcb389](https://linux-hardware.org/?probe=bcd3bcb389) | Aug 22, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7c763e43c6](https://linux-hardware.org/?probe=7c763e43c6) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [5f90bb65a6](https://linux-hardware.org/?probe=5f90bb65a6) | Aug 21, 2022 |
| HP            | Pavilion 15                 | Notebook    | [c8d31e4708](https://linux-hardware.org/?probe=c8d31e4708) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| Sony          | VPCEB12FD                   | Notebook    | [f98be4240a](https://linux-hardware.org/?probe=f98be4240a) | Aug 20, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [f37fce9f01](https://linux-hardware.org/?probe=f37fce9f01) | Aug 20, 2022 |
| Toshiba       | PORTEGE M780                | Notebook    | [8b7e72c5d9](https://linux-hardware.org/?probe=8b7e72c5d9) | Aug 20, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [ca0fbaa451](https://linux-hardware.org/?probe=ca0fbaa451) | Aug 19, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [565a6f9022](https://linux-hardware.org/?probe=565a6f9022) | Aug 19, 2022 |
| ASUSTek       | M4A78-E                     | Desktop     | [76028e78e9](https://linux-hardware.org/?probe=76028e78e9) | Aug 19, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [1eca9d2f2d](https://linux-hardware.org/?probe=1eca9d2f2d) | Aug 19, 2022 |
| Intel         | DH87RL AAG74240-401         | Desktop     | [ebc0328fe0](https://linux-hardware.org/?probe=ebc0328fe0) | Aug 19, 2022 |
| Dell          | Latitude E6410              | Notebook    | [3304a70394](https://linux-hardware.org/?probe=3304a70394) | Aug 19, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| Dell          | 054KM3 A01                  | Desktop     | [3f966fdafa](https://linux-hardware.org/?probe=3f966fdafa) | Aug 17, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [ac42df990f](https://linux-hardware.org/?probe=ac42df990f) | Aug 17, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [eec78b1552](https://linux-hardware.org/?probe=eec78b1552) | Aug 17, 2022 |
| Intel         | DH87RL AAG74240-401         | Desktop     | [a8c5b732f4](https://linux-hardware.org/?probe=a8c5b732f4) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [3b35e8e9da](https://linux-hardware.org/?probe=3b35e8e9da) | Aug 17, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [1ab8003e04](https://linux-hardware.org/?probe=1ab8003e04) | Aug 17, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [2a3c6446e5](https://linux-hardware.org/?probe=2a3c6446e5) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [2a3764a87e](https://linux-hardware.org/?probe=2a3764a87e) | Aug 16, 2022 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | Notebook    | [4d5eb5e332](https://linux-hardware.org/?probe=4d5eb5e332) | Aug 15, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [5171fd1732](https://linux-hardware.org/?probe=5171fd1732) | Aug 15, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [56ee42afe3](https://linux-hardware.org/?probe=56ee42afe3) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [239daef655](https://linux-hardware.org/?probe=239daef655) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9ab7a2b695](https://linux-hardware.org/?probe=9ab7a2b695) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e75de6c205](https://linux-hardware.org/?probe=e75de6c205) | Aug 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [b44e802677](https://linux-hardware.org/?probe=b44e802677) | Aug 14, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [08ef9ef965](https://linux-hardware.org/?probe=08ef9ef965) | Aug 14, 2022 |
| HP            | 805D                        | Desktop     | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| MSI           | MS-B9351                    | Desktop     | [a5b1950761](https://linux-hardware.org/?probe=a5b1950761) | Aug 14, 2022 |
| MSI           | MS-B9351                    | Desktop     | [fbf08d2d76](https://linux-hardware.org/?probe=fbf08d2d76) | Aug 14, 2022 |
| Lenovo        | ThinkPad E550 20DF0040CA    | Notebook    | [0f657d4798](https://linux-hardware.org/?probe=0f657d4798) | Aug 14, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [286fd1791a](https://linux-hardware.org/?probe=286fd1791a) | Aug 14, 2022 |
| HP            | ENVY m6                     | Notebook    | [74d1a937cf](https://linux-hardware.org/?probe=74d1a937cf) | Aug 14, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [8b417889e1](https://linux-hardware.org/?probe=8b417889e1) | Aug 13, 2022 |
| Dell          | G3 3590                     | Notebook    | [fbe948e194](https://linux-hardware.org/?probe=fbe948e194) | Aug 13, 2022 |
| Toshiba       | PORTEGE M780                | Notebook    | [b7304a84fd](https://linux-hardware.org/?probe=b7304a84fd) | Aug 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [3a1e95f5d5](https://linux-hardware.org/?probe=3a1e95f5d5) | Aug 12, 2022 |
| Dell          | 08GMV7 A00                  | All in one  | [d796aac0eb](https://linux-hardware.org/?probe=d796aac0eb) | Aug 12, 2022 |
| Dell          | 08GMV7 A00                  | All in one  | [40803a469b](https://linux-hardware.org/?probe=40803a469b) | Aug 12, 2022 |
| Dell          | 07PR60 A02                  | Desktop     | [7ed59c8c10](https://linux-hardware.org/?probe=7ed59c8c10) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| Dell          | Latitude 7420               | Notebook    | [26cd6bbb87](https://linux-hardware.org/?probe=26cd6bbb87) | Aug 12, 2022 |
| Dell          | 0CNCJW A08                  | Server      | [b961bc0427](https://linux-hardware.org/?probe=b961bc0427) | Aug 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [462769d45e](https://linux-hardware.org/?probe=462769d45e) | Aug 11, 2022 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [df3068aea1](https://linux-hardware.org/?probe=df3068aea1) | Aug 10, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [21044cebb3](https://linux-hardware.org/?probe=21044cebb3) | Aug 10, 2022 |
| HP            | ProBook 4540s               | Notebook    | [426365299d](https://linux-hardware.org/?probe=426365299d) | Aug 10, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [b188230a8a](https://linux-hardware.org/?probe=b188230a8a) | Aug 10, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [7586fd5a58](https://linux-hardware.org/?probe=7586fd5a58) | Aug 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9c257fb6e7](https://linux-hardware.org/?probe=9c257fb6e7) | Aug 10, 2022 |
| HP            | Laptop 17-by1xxx            | Notebook    | [1be4a11102](https://linux-hardware.org/?probe=1be4a11102) | Aug 09, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9c5e5976db](https://linux-hardware.org/?probe=9c5e5976db) | Aug 08, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [59250f2c2f](https://linux-hardware.org/?probe=59250f2c2f) | Aug 08, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [10d18cd30b](https://linux-hardware.org/?probe=10d18cd30b) | Aug 08, 2022 |
| ASUSTek       | G10DK                       | Desktop     | [2401d4af44](https://linux-hardware.org/?probe=2401d4af44) | Aug 08, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [64e8ddf1c9](https://linux-hardware.org/?probe=64e8ddf1c9) | Aug 07, 2022 |
| ASUSTek       | TP410UAR                    | Convertible | [e1f77d1f94](https://linux-hardware.org/?probe=e1f77d1f94) | Aug 07, 2022 |
| AZW           | GTR V01                     | Mini pc     | [504142e8e0](https://linux-hardware.org/?probe=504142e8e0) | Aug 07, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3ef9c93317](https://linux-hardware.org/?probe=3ef9c93317) | Aug 06, 2022 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [c4a323d350](https://linux-hardware.org/?probe=c4a323d350) | Aug 06, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [73145490fa](https://linux-hardware.org/?probe=73145490fa) | Aug 06, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [dbf000aacd](https://linux-hardware.org/?probe=dbf000aacd) | Aug 06, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [dca6f9dfbd](https://linux-hardware.org/?probe=dca6f9dfbd) | Aug 06, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1b55cc875](https://linux-hardware.org/?probe=a1b55cc875) | Aug 06, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [b1ec54ce80](https://linux-hardware.org/?probe=b1ec54ce80) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [4acbeffc03](https://linux-hardware.org/?probe=4acbeffc03) | Aug 05, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [f25dd33bc3](https://linux-hardware.org/?probe=f25dd33bc3) | Aug 04, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [3b290b6c0b](https://linux-hardware.org/?probe=3b290b6c0b) | Aug 04, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [db66e72de8](https://linux-hardware.org/?probe=db66e72de8) | Aug 04, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [f9e07e62c2](https://linux-hardware.org/?probe=f9e07e62c2) | Aug 04, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [385e290982](https://linux-hardware.org/?probe=385e290982) | Aug 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [c7789bc8ca](https://linux-hardware.org/?probe=c7789bc8ca) | Aug 03, 2022 |
| Google        | Droid                       | Notebook    | [15d4518ba0](https://linux-hardware.org/?probe=15d4518ba0) | Aug 03, 2022 |
| Biostar       | TA880GU3+                   | Desktop     | [323c68d80f](https://linux-hardware.org/?probe=323c68d80f) | Aug 03, 2022 |
| HP            | 339A                        | Desktop     | [27ddbfd51d](https://linux-hardware.org/?probe=27ddbfd51d) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| HP            | 8433 11                     | Desktop     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [80512402c0](https://linux-hardware.org/?probe=80512402c0) | Aug 02, 2022 |
| Alienware     | x17 R2                      | Notebook    | [48772fabd8](https://linux-hardware.org/?probe=48772fabd8) | Aug 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [0df3af0bc5](https://linux-hardware.org/?probe=0df3af0bc5) | Aug 02, 2022 |
| Alienware     | x17 R2                      | Notebook    | [606b777651](https://linux-hardware.org/?probe=606b777651) | Aug 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [bfddbf1d22](https://linux-hardware.org/?probe=bfddbf1d22) | Aug 02, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | Desktop     | [4bd0f9e461](https://linux-hardware.org/?probe=4bd0f9e461) | Aug 02, 2022 |
| HP            | Unknown                     | Notebook    | [bd6c9221e7](https://linux-hardware.org/?probe=bd6c9221e7) | Aug 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [442aaa6069](https://linux-hardware.org/?probe=442aaa6069) | Aug 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [e4c6300b68](https://linux-hardware.org/?probe=e4c6300b68) | Aug 01, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [1e57f77386](https://linux-hardware.org/?probe=1e57f77386) | Aug 01, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [ec13dcb17f](https://linux-hardware.org/?probe=ec13dcb17f) | Aug 01, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [ec1e513893](https://linux-hardware.org/?probe=ec1e513893) | Aug 01, 2022 |
| Dell          | 0GXM1W A01                  | Desktop     | [91d2f28256](https://linux-hardware.org/?probe=91d2f28256) | Aug 01, 2022 |
| Dell          | 0GXM1W A01                  | Desktop     | [ab895fc1a2](https://linux-hardware.org/?probe=ab895fc1a2) | Aug 01, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [15382de4bf](https://linux-hardware.org/?probe=15382de4bf) | Aug 01, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [13cbc87486](https://linux-hardware.org/?probe=13cbc87486) | Jul 31, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| HP            | Laptop 15-dy3xxx            | Notebook    | [e54cde5e86](https://linux-hardware.org/?probe=e54cde5e86) | Jul 31, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a1923838e1](https://linux-hardware.org/?probe=a1923838e1) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [22b4bcc010](https://linux-hardware.org/?probe=22b4bcc010) | Jul 31, 2022 |
| Dell          | CS24-TY                     | Server      | [c307dd98ff](https://linux-hardware.org/?probe=c307dd98ff) | Jul 30, 2022 |
| EVGA          | 134-KS-E377                 | Desktop     | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7682000c35](https://linux-hardware.org/?probe=7682000c35) | Jul 30, 2022 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [2fe4fe7fe5](https://linux-hardware.org/?probe=2fe4fe7fe5) | Jul 30, 2022 |
| HP            | 339A                        | Desktop     | [7f2505acd4](https://linux-hardware.org/?probe=7f2505acd4) | Jul 30, 2022 |
| AMI           | T3 MRD                      | Notebook    | [7e0a2ced92](https://linux-hardware.org/?probe=7e0a2ced92) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [38fae80720](https://linux-hardware.org/?probe=38fae80720) | Jul 29, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | Notebook    | [5b91ff037d](https://linux-hardware.org/?probe=5b91ff037d) | Jul 29, 2022 |
| Clevo         | W150HNM/W170HN              | Notebook    | [31c83153b5](https://linux-hardware.org/?probe=31c83153b5) | Jul 29, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [a6237b3a28](https://linux-hardware.org/?probe=a6237b3a28) | Jul 29, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [a6113f2e35](https://linux-hardware.org/?probe=a6113f2e35) | Jul 29, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [5a12531bf9](https://linux-hardware.org/?probe=5a12531bf9) | Jul 29, 2022 |
| Dell          | 0CRWCR A01                  | All in one  | [e1cd0b697d](https://linux-hardware.org/?probe=e1cd0b697d) | Jul 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [03b39a36f1](https://linux-hardware.org/?probe=03b39a36f1) | Jul 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [dffaa71aed](https://linux-hardware.org/?probe=dffaa71aed) | Jul 28, 2022 |
| ASUSTek       | G10DK                       | Desktop     | [70a71d84a6](https://linux-hardware.org/?probe=70a71d84a6) | Jul 28, 2022 |
| Dell          | Latitude E7440              | Notebook    | [ff1e9aae86](https://linux-hardware.org/?probe=ff1e9aae86) | Jul 28, 2022 |
| HP            | 18E6                        | Desktop     | [60d1a8e6da](https://linux-hardware.org/?probe=60d1a8e6da) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [b6dea628df](https://linux-hardware.org/?probe=b6dea628df) | Jul 27, 2022 |
| Lenovo        | ThinkPad X270 20HMS0GJ00    | Notebook    | [fa45b52c07](https://linux-hardware.org/?probe=fa45b52c07) | Jul 27, 2022 |
| Dell          | 05DN3X A00                  | Desktop     | [e4c1d0bdeb](https://linux-hardware.org/?probe=e4c1d0bdeb) | Jul 27, 2022 |
| Lenovo        | ThinkPad T420 4236CTO       | Notebook    | [6797b09b3b](https://linux-hardware.org/?probe=6797b09b3b) | Jul 27, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fc499e7600](https://linux-hardware.org/?probe=fc499e7600) | Jul 27, 2022 |
| Dell          | XPS 17 9720                 | Notebook    | [5f7787d9e3](https://linux-hardware.org/?probe=5f7787d9e3) | Jul 27, 2022 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [c5f4ae1ac4](https://linux-hardware.org/?probe=c5f4ae1ac4) | Jul 26, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [f9003ad850](https://linux-hardware.org/?probe=f9003ad850) | Jul 26, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [4d6af73032](https://linux-hardware.org/?probe=4d6af73032) | Jul 26, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [b61b6b5fa5](https://linux-hardware.org/?probe=b61b6b5fa5) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| Lenovo        | ThinkPad W530 24472SU       | Notebook    | [52f731db42](https://linux-hardware.org/?probe=52f731db42) | Jul 25, 2022 |
| Dell          | CS24-TY                     | Server      | [230ad2532f](https://linux-hardware.org/?probe=230ad2532f) | Jul 24, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [acc848feda](https://linux-hardware.org/?probe=acc848feda) | Jul 24, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [0084e69574](https://linux-hardware.org/?probe=0084e69574) | Jul 24, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [60b06048f3](https://linux-hardware.org/?probe=60b06048f3) | Jul 24, 2022 |
| Gateway       | DX4840                      | Desktop     | [0df8a716b1](https://linux-hardware.org/?probe=0df8a716b1) | Jul 24, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [8e2855140c](https://linux-hardware.org/?probe=8e2855140c) | Jul 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [4c0cb4fd92](https://linux-hardware.org/?probe=4c0cb4fd92) | Jul 23, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [e31685e3ae](https://linux-hardware.org/?probe=e31685e3ae) | Jul 23, 2022 |
| Pegatron      | 2ACD                        | Desktop     | [c8ce65cd26](https://linux-hardware.org/?probe=c8ce65cd26) | Jul 23, 2022 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [54e6e291bd](https://linux-hardware.org/?probe=54e6e291bd) | Jul 22, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a86b33bdc2](https://linux-hardware.org/?probe=a86b33bdc2) | Jul 22, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [3b2f2c3bea](https://linux-hardware.org/?probe=3b2f2c3bea) | Jul 22, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [dace7a0b12](https://linux-hardware.org/?probe=dace7a0b12) | Jul 21, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [dce15b4c00](https://linux-hardware.org/?probe=dce15b4c00) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2e97c3de0b](https://linux-hardware.org/?probe=2e97c3de0b) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d567131bf9](https://linux-hardware.org/?probe=d567131bf9) | Jul 21, 2022 |
| Dell          | Precision 7560              | Notebook    | [c76f72f8c7](https://linux-hardware.org/?probe=c76f72f8c7) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| HP            | 158B                        | Desktop     | [017875f5a5](https://linux-hardware.org/?probe=017875f5a5) | Jul 21, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [afbe55b100](https://linux-hardware.org/?probe=afbe55b100) | Jul 20, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [f843e569ed](https://linux-hardware.org/?probe=f843e569ed) | Jul 20, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [0ce9af7993](https://linux-hardware.org/?probe=0ce9af7993) | Jul 20, 2022 |
| Dell          | G3 3590                     | Notebook    | [920eed9524](https://linux-hardware.org/?probe=920eed9524) | Jul 19, 2022 |
| ASUSTek       | X555QA                      | Notebook    | [a34b1c5684](https://linux-hardware.org/?probe=a34b1c5684) | Jul 18, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [6aac7a75e7](https://linux-hardware.org/?probe=6aac7a75e7) | Jul 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [10be1cd329](https://linux-hardware.org/?probe=10be1cd329) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [75990d47d7](https://linux-hardware.org/?probe=75990d47d7) | Jul 17, 2022 |
| MSI           | MEG B550 UNIFY              | Desktop     | [d6ecbbbfda](https://linux-hardware.org/?probe=d6ecbbbfda) | Jul 17, 2022 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [ec770759cd](https://linux-hardware.org/?probe=ec770759cd) | Jul 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [38ebe8f368](https://linux-hardware.org/?probe=38ebe8f368) | Jul 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [129bcce64f](https://linux-hardware.org/?probe=129bcce64f) | Jul 17, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [236812ea49](https://linux-hardware.org/?probe=236812ea49) | Jul 17, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [e8b9689526](https://linux-hardware.org/?probe=e8b9689526) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | Notebook    | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [e762750617](https://linux-hardware.org/?probe=e762750617) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a6e936c29d](https://linux-hardware.org/?probe=a6e936c29d) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d465259da1](https://linux-hardware.org/?probe=d465259da1) | Jul 16, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [c020ff87e8](https://linux-hardware.org/?probe=c020ff87e8) | Jul 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [556c813157](https://linux-hardware.org/?probe=556c813157) | Jul 16, 2022 |
| HP            | Notebook                    | Notebook    | [8ef9afa771](https://linux-hardware.org/?probe=8ef9afa771) | Jul 16, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [4d57e57019](https://linux-hardware.org/?probe=4d57e57019) | Jul 15, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [d5a6b5628b](https://linux-hardware.org/?probe=d5a6b5628b) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46ef1a2cd6](https://linux-hardware.org/?probe=46ef1a2cd6) | Jul 14, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [69b486ea31](https://linux-hardware.org/?probe=69b486ea31) | Jul 14, 2022 |
| AMI           | T3 MRD                      | Notebook    | [d29d5d14c8](https://linux-hardware.org/?probe=d29d5d14c8) | Jul 14, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [386dd1ac4b](https://linux-hardware.org/?probe=386dd1ac4b) | Jul 14, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | Notebook    | [e5c9e4e4d9](https://linux-hardware.org/?probe=e5c9e4e4d9) | Jul 13, 2022 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [e007a2fbc2](https://linux-hardware.org/?probe=e007a2fbc2) | Jul 13, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [a6d5a615d0](https://linux-hardware.org/?probe=a6d5a615d0) | Jul 13, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [fdae528732](https://linux-hardware.org/?probe=fdae528732) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [063f846aad](https://linux-hardware.org/?probe=063f846aad) | Jul 12, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [34c2c24b3b](https://linux-hardware.org/?probe=34c2c24b3b) | Jul 11, 2022 |
| Dell          | Latitude 5510               | Notebook    | [5f1abb9d12](https://linux-hardware.org/?probe=5f1abb9d12) | Jul 11, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [32cbf49371](https://linux-hardware.org/?probe=32cbf49371) | Jul 11, 2022 |
| AWOW          | NY41                        | Mini pc     | [a08b96a066](https://linux-hardware.org/?probe=a08b96a066) | Jul 11, 2022 |
| AWOW          | NY41                        | Mini pc     | [330ebff5e1](https://linux-hardware.org/?probe=330ebff5e1) | Jul 11, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [392310b916](https://linux-hardware.org/?probe=392310b916) | Jul 11, 2022 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [d088d6021c](https://linux-hardware.org/?probe=d088d6021c) | Jul 11, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [845bdfd72c](https://linux-hardware.org/?probe=845bdfd72c) | Jul 11, 2022 |
| Dell          | 09WH54 A00                  | Desktop     | [8570e35470](https://linux-hardware.org/?probe=8570e35470) | Jul 11, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [48c007b4e2](https://linux-hardware.org/?probe=48c007b4e2) | Jul 10, 2022 |
| Gigabyte      | Z270M-D3H-CF                | Desktop     | [df9ed91803](https://linux-hardware.org/?probe=df9ed91803) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| MSI           | 2AE0                        | Desktop     | [4732ee97fb](https://linux-hardware.org/?probe=4732ee97fb) | Jul 10, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [b161f9e458](https://linux-hardware.org/?probe=b161f9e458) | Jul 10, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | Notebook    | [2894597236](https://linux-hardware.org/?probe=2894597236) | Jul 10, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [2efb274f31](https://linux-hardware.org/?probe=2efb274f31) | Jul 10, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [e4f7616dee](https://linux-hardware.org/?probe=e4f7616dee) | Jul 10, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [00495f3422](https://linux-hardware.org/?probe=00495f3422) | Jul 09, 2022 |
| Google        | Eve                         | Convertible | [be0c82653c](https://linux-hardware.org/?probe=be0c82653c) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a9ff12a6e5](https://linux-hardware.org/?probe=a9ff12a6e5) | Jul 08, 2022 |
| Dell          | 0R849J A01                  | Desktop     | [3ea68d63c3](https://linux-hardware.org/?probe=3ea68d63c3) | Jul 08, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [5dc09a66d8](https://linux-hardware.org/?probe=5dc09a66d8) | Jul 08, 2022 |
| HP            | 85BA 00100                  | All in one  | [3acda0ef6a](https://linux-hardware.org/?probe=3acda0ef6a) | Jul 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [98711d54c1](https://linux-hardware.org/?probe=98711d54c1) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [fd0a9ef1c8](https://linux-hardware.org/?probe=fd0a9ef1c8) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [cc2f84d5d3](https://linux-hardware.org/?probe=cc2f84d5d3) | Jul 08, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4f51cd80f3](https://linux-hardware.org/?probe=4f51cd80f3) | Jul 08, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [35e1af0d15](https://linux-hardware.org/?probe=35e1af0d15) | Jul 08, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [5ecc52d011](https://linux-hardware.org/?probe=5ecc52d011) | Jul 08, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [2c457a6e4e](https://linux-hardware.org/?probe=2c457a6e4e) | Jul 07, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [80d9c382cd](https://linux-hardware.org/?probe=80d9c382cd) | Jul 07, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [9082e63d7d](https://linux-hardware.org/?probe=9082e63d7d) | Jul 07, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [106199561c](https://linux-hardware.org/?probe=106199561c) | Jul 07, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ff75212757](https://linux-hardware.org/?probe=ff75212757) | Jul 07, 2022 |
| Acer          | Nitro AN515-53              | Notebook    | [d31c5d1c11](https://linux-hardware.org/?probe=d31c5d1c11) | Jul 06, 2022 |
| Dell          | Latitude 7420               | Notebook    | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| Acer          | Nitro AN515-53              | Notebook    | [0304267499](https://linux-hardware.org/?probe=0304267499) | Jul 06, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [f188f66d12](https://linux-hardware.org/?probe=f188f66d12) | Jul 06, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [ebaa969297](https://linux-hardware.org/?probe=ebaa969297) | Jul 06, 2022 |
| Google        | Aleena                      | Notebook    | [33110c34a9](https://linux-hardware.org/?probe=33110c34a9) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [7a6f484b16](https://linux-hardware.org/?probe=7a6f484b16) | Jul 06, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [a4b4609db8](https://linux-hardware.org/?probe=a4b4609db8) | Jul 05, 2022 |
| ASUSTek       | G55VW                       | Notebook    | [fa0346f5df](https://linux-hardware.org/?probe=fa0346f5df) | Jul 05, 2022 |
| ASUSTek       | G55VW                       | Notebook    | [832ca8cf45](https://linux-hardware.org/?probe=832ca8cf45) | Jul 05, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [d14ad254ca](https://linux-hardware.org/?probe=d14ad254ca) | Jul 05, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [a9a0f46cc7](https://linux-hardware.org/?probe=a9a0f46cc7) | Jul 05, 2022 |
| Unknown       | Unknown                     | All in one  | [1498908025](https://linux-hardware.org/?probe=1498908025) | Jul 05, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [24a76119e1](https://linux-hardware.org/?probe=24a76119e1) | Jul 04, 2022 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [3199c023cb](https://linux-hardware.org/?probe=3199c023cb) | Jul 04, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [e0c6593aee](https://linux-hardware.org/?probe=e0c6593aee) | Jul 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [eb9c212159](https://linux-hardware.org/?probe=eb9c212159) | Jul 04, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [d3f8e6dee5](https://linux-hardware.org/?probe=d3f8e6dee5) | Jul 04, 2022 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [a21d756ee1](https://linux-hardware.org/?probe=a21d756ee1) | Jul 03, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [25e69108df](https://linux-hardware.org/?probe=25e69108df) | Jul 03, 2022 |
| Dell          | 0M6C7G A00                  | Desktop     | [5eee0db64f](https://linux-hardware.org/?probe=5eee0db64f) | Jul 03, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1a729c627d](https://linux-hardware.org/?probe=1a729c627d) | Jul 03, 2022 |
| Acer          | Aspire TC-280               | Desktop     | [7322461b76](https://linux-hardware.org/?probe=7322461b76) | Jul 03, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [8ac3e2bcbc](https://linux-hardware.org/?probe=8ac3e2bcbc) | Jul 02, 2022 |
| Acer          | Aspire 5742Z                | Notebook    | [46f56997be](https://linux-hardware.org/?probe=46f56997be) | Jul 02, 2022 |
| Acer          | Aspire TC-280               | Desktop     | [0e497c1c13](https://linux-hardware.org/?probe=0e497c1c13) | Jul 02, 2022 |
| Acer          | Nitro AN517-52              | Notebook    | [3920a80387](https://linux-hardware.org/?probe=3920a80387) | Jul 02, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [64eae559ae](https://linux-hardware.org/?probe=64eae559ae) | Jul 02, 2022 |
| Acer          | Nitro AN517-52              | Notebook    | [37fbd3a600](https://linux-hardware.org/?probe=37fbd3a600) | Jul 02, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [39684e88bc](https://linux-hardware.org/?probe=39684e88bc) | Jul 02, 2022 |
| Dell          | Precision 5550              | Notebook    | [0ddb8905e5](https://linux-hardware.org/?probe=0ddb8905e5) | Jul 01, 2022 |
| ASRock        | Z97 Anniversary             | Desktop     | [1e650b504d](https://linux-hardware.org/?probe=1e650b504d) | Jul 01, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [bbd0bf2dc0](https://linux-hardware.org/?probe=bbd0bf2dc0) | Jun 30, 2022 |
| Dell          | 0HJ054                      | Desktop     | [bb9d7a3a58](https://linux-hardware.org/?probe=bb9d7a3a58) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [804bbd8147](https://linux-hardware.org/?probe=804bbd8147) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [9fe936cec8](https://linux-hardware.org/?probe=9fe936cec8) | Jun 30, 2022 |
| Dell          | 0M858N A01                  | Desktop     | [6cc8dcd51e](https://linux-hardware.org/?probe=6cc8dcd51e) | Jun 29, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [2c8286100d](https://linux-hardware.org/?probe=2c8286100d) | Jun 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [9de675d3d1](https://linux-hardware.org/?probe=9de675d3d1) | Jun 29, 2022 |
| ASUSTek       | G752VT                      | Notebook    | [d51730ccbf](https://linux-hardware.org/?probe=d51730ccbf) | Jun 29, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [cf7b4fb7e1](https://linux-hardware.org/?probe=cf7b4fb7e1) | Jun 29, 2022 |
| Dell          | Latitude 5520               | Notebook    | [0504660b50](https://linux-hardware.org/?probe=0504660b50) | Jun 28, 2022 |
| MSI           | H310M PRO-VD                | Desktop     | [1aec9e08e9](https://linux-hardware.org/?probe=1aec9e08e9) | Jun 28, 2022 |
| MSI           | H310M PRO-VD                | Desktop     | [1812911a41](https://linux-hardware.org/?probe=1812911a41) | Jun 28, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [a27f696a28](https://linux-hardware.org/?probe=a27f696a28) | Jun 27, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [932496f041](https://linux-hardware.org/?probe=932496f041) | Jun 27, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [547346f0a9](https://linux-hardware.org/?probe=547346f0a9) | Jun 26, 2022 |
| Lenovo        | ThinkPad T400 6475AT3       | Notebook    | [55fd247328](https://linux-hardware.org/?probe=55fd247328) | Jun 26, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [57d9c7c28a](https://linux-hardware.org/?probe=57d9c7c28a) | Jun 24, 2022 |
| System76      | Darter Pro                  | Notebook    | [db7f217878](https://linux-hardware.org/?probe=db7f217878) | Jun 24, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [7528e47074](https://linux-hardware.org/?probe=7528e47074) | Jun 24, 2022 |
| Toshiba       | Satellite S50-A             | Notebook    | [c2e7c1b26d](https://linux-hardware.org/?probe=c2e7c1b26d) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [afce38a95a](https://linux-hardware.org/?probe=afce38a95a) | Jun 24, 2022 |
| Lenovo        | ThinkPad T420 4236J73       | Notebook    | [088ba8b97c](https://linux-hardware.org/?probe=088ba8b97c) | Jun 23, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [2c1f55aa8f](https://linux-hardware.org/?probe=2c1f55aa8f) | Jun 23, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [71f0d32783](https://linux-hardware.org/?probe=71f0d32783) | Jun 23, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c4524cb21f](https://linux-hardware.org/?probe=c4524cb21f) | Jun 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [cf4479fbe9](https://linux-hardware.org/?probe=cf4479fbe9) | Jun 22, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [8dca736a46](https://linux-hardware.org/?probe=8dca736a46) | Jun 21, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [834bed6eda](https://linux-hardware.org/?probe=834bed6eda) | Jun 21, 2022 |
| Lenovo        | ThinkPad T420 4236EF4       | Notebook    | [1894bb8853](https://linux-hardware.org/?probe=1894bb8853) | Jun 21, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [e32a4e0214](https://linux-hardware.org/?probe=e32a4e0214) | Jun 20, 2022 |
| Google        | Droid                       | Notebook    | [5a175a2a78](https://linux-hardware.org/?probe=5a175a2a78) | Jun 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a9a3470242](https://linux-hardware.org/?probe=a9a3470242) | Jun 19, 2022 |
| HP            | Pavilion dv7                | Notebook    | [ab34fbb528](https://linux-hardware.org/?probe=ab34fbb528) | Jun 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [4b10fd12ae](https://linux-hardware.org/?probe=4b10fd12ae) | Jun 19, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [f0cf5e0f30](https://linux-hardware.org/?probe=f0cf5e0f30) | Jun 18, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [bc61209d78](https://linux-hardware.org/?probe=bc61209d78) | Jun 18, 2022 |
| MSI           | H310M PRO-VD                | Desktop     | [6516a467b5](https://linux-hardware.org/?probe=6516a467b5) | Jun 17, 2022 |
| Dell          | Latitude E6540              | Notebook    | [4806aec13b](https://linux-hardware.org/?probe=4806aec13b) | Jun 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [145a1e77fc](https://linux-hardware.org/?probe=145a1e77fc) | Jun 16, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [9ab6f4690f](https://linux-hardware.org/?probe=9ab6f4690f) | Jun 16, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [bce90f59c8](https://linux-hardware.org/?probe=bce90f59c8) | Jun 16, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [6c1c388f3a](https://linux-hardware.org/?probe=6c1c388f3a) | Jun 15, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e11d001f52](https://linux-hardware.org/?probe=e11d001f52) | Jun 15, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [cc1947a21b](https://linux-hardware.org/?probe=cc1947a21b) | Jun 15, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [cba78f563c](https://linux-hardware.org/?probe=cba78f563c) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| ASRock        | H310M-ITX/ac                | Desktop     | [17063e8cc6](https://linux-hardware.org/?probe=17063e8cc6) | Jun 15, 2022 |
| Acer          | Aspire X1400                | Desktop     | [a90701fd86](https://linux-hardware.org/?probe=a90701fd86) | Jun 15, 2022 |
| Dell          | Precision 5550              | Notebook    | [f5f815ceed](https://linux-hardware.org/?probe=f5f815ceed) | Jun 14, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [d7cccd8f1d](https://linux-hardware.org/?probe=d7cccd8f1d) | Jun 14, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [c856f6d54f](https://linux-hardware.org/?probe=c856f6d54f) | Jun 14, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [aa4ef3154d](https://linux-hardware.org/?probe=aa4ef3154d) | Jun 14, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [23de86aa97](https://linux-hardware.org/?probe=23de86aa97) | Jun 14, 2022 |
| Dell          | 0D28YY A00                  | Desktop     | [18487dbcb1](https://linux-hardware.org/?probe=18487dbcb1) | Jun 14, 2022 |
| Alienware     | 0R3FWM A00                  | Desktop     | [6690a39447](https://linux-hardware.org/?probe=6690a39447) | Jun 13, 2022 |
| Notebook      | P65_P67SE                   | Notebook    | [590b7204da](https://linux-hardware.org/?probe=590b7204da) | Jun 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [e26e612120](https://linux-hardware.org/?probe=e26e612120) | Jun 13, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e18df87b93](https://linux-hardware.org/?probe=e18df87b93) | Jun 13, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9275d3d785](https://linux-hardware.org/?probe=9275d3d785) | Jun 13, 2022 |
| HP            | ProBook 470 G4              | Notebook    | [29f73d7f11](https://linux-hardware.org/?probe=29f73d7f11) | Jun 12, 2022 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | Notebook    | [9382b4e2c0](https://linux-hardware.org/?probe=9382b4e2c0) | Jun 12, 2022 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | Notebook    | [06526726ca](https://linux-hardware.org/?probe=06526726ca) | Jun 11, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [14b9e721b7](https://linux-hardware.org/?probe=14b9e721b7) | Jun 11, 2022 |
| HP            | Pavilion 17                 | Notebook    | [bed3614b80](https://linux-hardware.org/?probe=bed3614b80) | Jun 11, 2022 |
| Razer         | Blade                       | Notebook    | [df8f6881a7](https://linux-hardware.org/?probe=df8f6881a7) | Jun 10, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [148d14437b](https://linux-hardware.org/?probe=148d14437b) | Jun 10, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [693e499a6d](https://linux-hardware.org/?probe=693e499a6d) | Jun 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e92127f694](https://linux-hardware.org/?probe=e92127f694) | Jun 10, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [294890a076](https://linux-hardware.org/?probe=294890a076) | Jun 10, 2022 |
| Dell          | Latitude E5550              | Notebook    | [95baf2f400](https://linux-hardware.org/?probe=95baf2f400) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [92a20ee191](https://linux-hardware.org/?probe=92a20ee191) | Jun 08, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ff7b51ffc8](https://linux-hardware.org/?probe=ff7b51ffc8) | Jun 08, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [c18fee9219](https://linux-hardware.org/?probe=c18fee9219) | Jun 08, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [630d0bc381](https://linux-hardware.org/?probe=630d0bc381) | Jun 08, 2022 |
| Intel         | DG33FB AAD81072-306         | Desktop     | [78abe45a29](https://linux-hardware.org/?probe=78abe45a29) | Jun 08, 2022 |
| ASUSTek       | G752VT                      | Notebook    | [bb5bb68126](https://linux-hardware.org/?probe=bb5bb68126) | Jun 08, 2022 |
| Lenovo        | ThinkStation S20 410599U    | Desktop     | [072870fb4e](https://linux-hardware.org/?probe=072870fb4e) | Jun 07, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [8226efcb30](https://linux-hardware.org/?probe=8226efcb30) | Jun 07, 2022 |
| HP            | 8433 11                     | Desktop     | [fa4c4f5c0e](https://linux-hardware.org/?probe=fa4c4f5c0e) | Jun 07, 2022 |
| Lenovo        | ThinkStation S20 410599U    | Desktop     | [20df21f5d9](https://linux-hardware.org/?probe=20df21f5d9) | Jun 07, 2022 |
| Google        | Cave                        | Notebook    | [16183f9a77](https://linux-hardware.org/?probe=16183f9a77) | Jun 07, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [937c62f908](https://linux-hardware.org/?probe=937c62f908) | Jun 07, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [781ae865b0](https://linux-hardware.org/?probe=781ae865b0) | Jun 07, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [809d0bbd73](https://linux-hardware.org/?probe=809d0bbd73) | Jun 07, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [761d37bd31](https://linux-hardware.org/?probe=761d37bd31) | Jun 06, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [aab255864c](https://linux-hardware.org/?probe=aab255864c) | Jun 06, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [d88feaaf5e](https://linux-hardware.org/?probe=d88feaaf5e) | Jun 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [44afb95fbb](https://linux-hardware.org/?probe=44afb95fbb) | Jun 06, 2022 |
| System76      | Oryx Pro                    | Notebook    | [ec0e78e0f6](https://linux-hardware.org/?probe=ec0e78e0f6) | Jun 06, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [fffae020ba](https://linux-hardware.org/?probe=fffae020ba) | Jun 06, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [5745c8b787](https://linux-hardware.org/?probe=5745c8b787) | Jun 06, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [0d57c069a8](https://linux-hardware.org/?probe=0d57c069a8) | Jun 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [e636b14f58](https://linux-hardware.org/?probe=e636b14f58) | Jun 05, 2022 |
| ASRock        | Z97 Anniversary             | Desktop     | [b6a332c085](https://linux-hardware.org/?probe=b6a332c085) | Jun 04, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [3ebcdc19fa](https://linux-hardware.org/?probe=3ebcdc19fa) | Jun 04, 2022 |
| MSI           | GP72 6QF                    | Notebook    | [4f62904f80](https://linux-hardware.org/?probe=4f62904f80) | Jun 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [3fd62a1d06](https://linux-hardware.org/?probe=3fd62a1d06) | Jun 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7a8d99ead8](https://linux-hardware.org/?probe=7a8d99ead8) | Jun 04, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [d0797577a9](https://linux-hardware.org/?probe=d0797577a9) | Jun 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [cae8761200](https://linux-hardware.org/?probe=cae8761200) | Jun 03, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9404638832](https://linux-hardware.org/?probe=9404638832) | Jun 03, 2022 |
| HP            | 3397                        | Desktop     | [775c6990fd](https://linux-hardware.org/?probe=775c6990fd) | Jun 03, 2022 |
| HP            | 3397                        | Desktop     | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
| HP            | Pavilion x2 Detachable      | Tablet      | [d60056e177](https://linux-hardware.org/?probe=d60056e177) | Jun 03, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [ea24f8341e](https://linux-hardware.org/?probe=ea24f8341e) | Jun 02, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [d3799b37d7](https://linux-hardware.org/?probe=d3799b37d7) | Jun 02, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [c50bbae3e1](https://linux-hardware.org/?probe=c50bbae3e1) | Jun 02, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [dca80e1df5](https://linux-hardware.org/?probe=dca80e1df5) | Jun 02, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | Desktop     | [536c6e19de](https://linux-hardware.org/?probe=536c6e19de) | Jun 01, 2022 |
| Dell          | Latitude 7420               | Notebook    | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [aed2597085](https://linux-hardware.org/?probe=aed2597085) | Jun 01, 2022 |
| Lenovo        | Edge 15 80K9                | Notebook    | [5c8bb97759](https://linux-hardware.org/?probe=5c8bb97759) | Jun 01, 2022 |
| HP            | 339A                        | Desktop     | [c3c520f59b](https://linux-hardware.org/?probe=c3c520f59b) | Jun 01, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [82b4935292](https://linux-hardware.org/?probe=82b4935292) | Jun 01, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [b7db998ac4](https://linux-hardware.org/?probe=b7db998ac4) | May 31, 2022 |
| Apple         | MacBookAir4,1               | Notebook    | [a0b4c18cd0](https://linux-hardware.org/?probe=a0b4c18cd0) | May 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [ead15ec00b](https://linux-hardware.org/?probe=ead15ec00b) | May 31, 2022 |
| Lenovo        | Edge 15 80K9                | Notebook    | [586a31368f](https://linux-hardware.org/?probe=586a31368f) | May 30, 2022 |
| HP            | Stream Laptop 11-ak1xxx     | Notebook    | [2d2044b499](https://linux-hardware.org/?probe=2d2044b499) | May 30, 2022 |
| Dell          | 0R6PCT A01                  | Desktop     | [08c460e0a3](https://linux-hardware.org/?probe=08c460e0a3) | May 30, 2022 |
| Dell          | 0R6PCT A01                  | Desktop     | [89aadb96f3](https://linux-hardware.org/?probe=89aadb96f3) | May 30, 2022 |
| Dell          | Latitude 5289               | Notebook    | [f9e3e0fa57](https://linux-hardware.org/?probe=f9e3e0fa57) | May 30, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [cdc051336a](https://linux-hardware.org/?probe=cdc051336a) | May 30, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [2e1fd846a3](https://linux-hardware.org/?probe=2e1fd846a3) | May 30, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [5fdf8e3100](https://linux-hardware.org/?probe=5fdf8e3100) | May 29, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5e75c2d00d](https://linux-hardware.org/?probe=5e75c2d00d) | May 29, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [33a2de91a2](https://linux-hardware.org/?probe=33a2de91a2) | May 29, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [c07bfd58f1](https://linux-hardware.org/?probe=c07bfd58f1) | May 29, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [1416d5a87d](https://linux-hardware.org/?probe=1416d5a87d) | May 29, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [462a42a8c9](https://linux-hardware.org/?probe=462a42a8c9) | May 28, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [cd703bd1b1](https://linux-hardware.org/?probe=cd703bd1b1) | May 28, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [a7f61e2b9b](https://linux-hardware.org/?probe=a7f61e2b9b) | May 28, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [3442533a85](https://linux-hardware.org/?probe=3442533a85) | May 28, 2022 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [5d5ba64239](https://linux-hardware.org/?probe=5d5ba64239) | May 28, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [84cc31cb32](https://linux-hardware.org/?probe=84cc31cb32) | May 27, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [602f942afc](https://linux-hardware.org/?probe=602f942afc) | May 27, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [a7cb65fb76](https://linux-hardware.org/?probe=a7cb65fb76) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [a4f2a9b24b](https://linux-hardware.org/?probe=a4f2a9b24b) | May 27, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [641c79318b](https://linux-hardware.org/?probe=641c79318b) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [3143793e8f](https://linux-hardware.org/?probe=3143793e8f) | May 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [63690e08a1](https://linux-hardware.org/?probe=63690e08a1) | May 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [0560d4c462](https://linux-hardware.org/?probe=0560d4c462) | May 27, 2022 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [509fc21647](https://linux-hardware.org/?probe=509fc21647) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [43f315aa0c](https://linux-hardware.org/?probe=43f315aa0c) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [9b4287fa8b](https://linux-hardware.org/?probe=9b4287fa8b) | May 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [24b4b7cb04](https://linux-hardware.org/?probe=24b4b7cb04) | May 26, 2022 |
| Lenovo        | ThinkCentre M90p 5864AL2    | Desktop     | [679cfd5a27](https://linux-hardware.org/?probe=679cfd5a27) | May 26, 2022 |
| Dell          | G15 5515                    | Notebook    | [4f47780467](https://linux-hardware.org/?probe=4f47780467) | May 26, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [42577fc274](https://linux-hardware.org/?probe=42577fc274) | May 26, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [08f7af683d](https://linux-hardware.org/?probe=08f7af683d) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [db51e7c435](https://linux-hardware.org/?probe=db51e7c435) | May 26, 2022 |
| Dell          | Latitude E6420              | Notebook    | [425a9e4f0d](https://linux-hardware.org/?probe=425a9e4f0d) | May 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [75063d8f18](https://linux-hardware.org/?probe=75063d8f18) | May 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [0d1ba4ee73](https://linux-hardware.org/?probe=0d1ba4ee73) | May 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [c9c34c5c6f](https://linux-hardware.org/?probe=c9c34c5c6f) | May 26, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [a214740f99](https://linux-hardware.org/?probe=a214740f99) | May 25, 2022 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [1d7941d921](https://linux-hardware.org/?probe=1d7941d921) | May 25, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [f4afc8ed1d](https://linux-hardware.org/?probe=f4afc8ed1d) | May 25, 2022 |
| Intel         | S1200SP H57532-250          | Server      | [c8175992e0](https://linux-hardware.org/?probe=c8175992e0) | May 25, 2022 |
| Dell          | Precision 5550              | Notebook    | [6b17026494](https://linux-hardware.org/?probe=6b17026494) | May 24, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [7260e3bf3b](https://linux-hardware.org/?probe=7260e3bf3b) | May 24, 2022 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [0c5e493177](https://linux-hardware.org/?probe=0c5e493177) | May 24, 2022 |
| Dell          | Latitude D830               | Notebook    | [f2f09cee8c](https://linux-hardware.org/?probe=f2f09cee8c) | May 24, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [b31235961f](https://linux-hardware.org/?probe=b31235961f) | May 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7e8bde85cc](https://linux-hardware.org/?probe=7e8bde85cc) | May 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [02c35436fd](https://linux-hardware.org/?probe=02c35436fd) | May 24, 2022 |
| Dell          | Latitude E5450              | Notebook    | [7d23576abb](https://linux-hardware.org/?probe=7d23576abb) | May 23, 2022 |
| Dell          | Latitude E5450              | Notebook    | [f0c746ba9e](https://linux-hardware.org/?probe=f0c746ba9e) | May 23, 2022 |
| ASUSTek       | PRIME B660M-A AC D4         | Desktop     | [286688e46b](https://linux-hardware.org/?probe=286688e46b) | May 23, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [c7cf536a61](https://linux-hardware.org/?probe=c7cf536a61) | May 23, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4495957eae](https://linux-hardware.org/?probe=4495957eae) | May 23, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d49bf6427c](https://linux-hardware.org/?probe=d49bf6427c) | May 23, 2022 |
| MSI           | 2AE0                        | Desktop     | [ea14a764bb](https://linux-hardware.org/?probe=ea14a764bb) | May 22, 2022 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [f451e1b307](https://linux-hardware.org/?probe=f451e1b307) | May 22, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [9020ffe67d](https://linux-hardware.org/?probe=9020ffe67d) | May 22, 2022 |
| HP            | 3398                        | Desktop     | [d7e6c0c903](https://linux-hardware.org/?probe=d7e6c0c903) | May 22, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [a1d48698b0](https://linux-hardware.org/?probe=a1d48698b0) | May 22, 2022 |
| Lenovo        | ThinkPad W520 42763JF       | Notebook    | [2b87bae835](https://linux-hardware.org/?probe=2b87bae835) | May 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [261a0bf179](https://linux-hardware.org/?probe=261a0bf179) | May 21, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [06943bb7f1](https://linux-hardware.org/?probe=06943bb7f1) | May 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b6a4466bd7](https://linux-hardware.org/?probe=b6a4466bd7) | May 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d6b65a07a2](https://linux-hardware.org/?probe=d6b65a07a2) | May 21, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [42338941c5](https://linux-hardware.org/?probe=42338941c5) | May 21, 2022 |
| HP            | Notebook                    | Notebook    | [7e7b774d40](https://linux-hardware.org/?probe=7e7b774d40) | May 21, 2022 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| MSI           | MS-7A34                     | Notebook    | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| Dell          | 0D6H9T A02                  | Desktop     | [3f87c84f7a](https://linux-hardware.org/?probe=3f87c84f7a) | May 20, 2022 |
| MSI           | Stealth GS66 12UE           | Notebook    | [98bccdf1f2](https://linux-hardware.org/?probe=98bccdf1f2) | May 20, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1d5fec86a8](https://linux-hardware.org/?probe=1d5fec86a8) | May 20, 2022 |
| Dell          | Inspiron 5565               | Notebook    | [a583bbdc35](https://linux-hardware.org/?probe=a583bbdc35) | May 19, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [ee62ecda2e](https://linux-hardware.org/?probe=ee62ecda2e) | May 19, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [5ac7cb91c3](https://linux-hardware.org/?probe=5ac7cb91c3) | May 18, 2022 |
| Dell          | Latitude 5430 Rugged        | Notebook    | [c32e65738e](https://linux-hardware.org/?probe=c32e65738e) | May 18, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [e08308603a](https://linux-hardware.org/?probe=e08308603a) | May 18, 2022 |
| HP            | Pavilion g4                 | Notebook    | [dcb7b65b12](https://linux-hardware.org/?probe=dcb7b65b12) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [9ff24e3f8b](https://linux-hardware.org/?probe=9ff24e3f8b) | May 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [716443586f](https://linux-hardware.org/?probe=716443586f) | May 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [bc731dc190](https://linux-hardware.org/?probe=bc731dc190) | May 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [aa810f6e41](https://linux-hardware.org/?probe=aa810f6e41) | May 18, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [48b2a9b021](https://linux-hardware.org/?probe=48b2a9b021) | May 17, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [7ca9e60266](https://linux-hardware.org/?probe=7ca9e60266) | May 17, 2022 |
| HP            | 8704                        | Desktop     | [84fd199efc](https://linux-hardware.org/?probe=84fd199efc) | May 17, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [6459eab7e8](https://linux-hardware.org/?probe=6459eab7e8) | May 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [c006d01be7](https://linux-hardware.org/?probe=c006d01be7) | May 17, 2022 |
| MSI           | H310M PRO-VD                | Desktop     | [70a3302b36](https://linux-hardware.org/?probe=70a3302b36) | May 17, 2022 |
| MSI           | H310M PRO-VD                | Desktop     | [a04d3bd332](https://linux-hardware.org/?probe=a04d3bd332) | May 17, 2022 |
| HP            | 8704                        | Desktop     | [863dcbe2ae](https://linux-hardware.org/?probe=863dcbe2ae) | May 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [de37f2b586](https://linux-hardware.org/?probe=de37f2b586) | May 17, 2022 |
| Acer          | Aspire 5810T                | Notebook    | [1cf713e3df](https://linux-hardware.org/?probe=1cf713e3df) | May 16, 2022 |
| Alienware     | x17 R2                      | Notebook    | [b755419e26](https://linux-hardware.org/?probe=b755419e26) | May 16, 2022 |
| Apple         | MacBookAir4,1               | Notebook    | [c4773713e6](https://linux-hardware.org/?probe=c4773713e6) | May 16, 2022 |
| Apple         | MacBookAir4,1               | Notebook    | [928416ecd0](https://linux-hardware.org/?probe=928416ecd0) | May 16, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [2df08f807d](https://linux-hardware.org/?probe=2df08f807d) | May 15, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9445ab07bf](https://linux-hardware.org/?probe=9445ab07bf) | May 15, 2022 |
| Unknown       | Unknown                     | Notebook    | [1243a1c63a](https://linux-hardware.org/?probe=1243a1c63a) | May 15, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [653725bdde](https://linux-hardware.org/?probe=653725bdde) | May 15, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [b061586ff0](https://linux-hardware.org/?probe=b061586ff0) | May 14, 2022 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [35209e0a61](https://linux-hardware.org/?probe=35209e0a61) | May 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [0f4e4f3887](https://linux-hardware.org/?probe=0f4e4f3887) | May 14, 2022 |
| Acer          | Predator G9-593             | Notebook    | [ab4bc72022](https://linux-hardware.org/?probe=ab4bc72022) | May 14, 2022 |
| Intel         | S5520HC E26045-457          | Server      | [ce6fe2a9cd](https://linux-hardware.org/?probe=ce6fe2a9cd) | May 14, 2022 |
| ASUSTek       | Acacia                      | Desktop     | [4b633150fa](https://linux-hardware.org/?probe=4b633150fa) | May 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [2d1e8a0642](https://linux-hardware.org/?probe=2d1e8a0642) | May 14, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [423fbd3a54](https://linux-hardware.org/?probe=423fbd3a54) | May 14, 2022 |
| HP            | 8704                        | Desktop     | [979caa0192](https://linux-hardware.org/?probe=979caa0192) | May 13, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [6dee77b5ca](https://linux-hardware.org/?probe=6dee77b5ca) | May 13, 2022 |
| Dell          | Latitude E6400              | Notebook    | [2831bacde3](https://linux-hardware.org/?probe=2831bacde3) | May 13, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [6a39b7b0da](https://linux-hardware.org/?probe=6a39b7b0da) | May 13, 2022 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [cfff0d1922](https://linux-hardware.org/?probe=cfff0d1922) | May 13, 2022 |
| Acer          | Aspire X3400                | Desktop     | [9dd76b4599](https://linux-hardware.org/?probe=9dd76b4599) | May 13, 2022 |
| Acer          | Aspire X3400                | Desktop     | [b590b149fc](https://linux-hardware.org/?probe=b590b149fc) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [24d4683d52](https://linux-hardware.org/?probe=24d4683d52) | May 13, 2022 |
| Dell          | Latitude D830               | Notebook    | [d19fc99d54](https://linux-hardware.org/?probe=d19fc99d54) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [299f811f98](https://linux-hardware.org/?probe=299f811f98) | May 12, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [58c45bf845](https://linux-hardware.org/?probe=58c45bf845) | May 12, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [5de8d1f805](https://linux-hardware.org/?probe=5de8d1f805) | May 11, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [565dfeea66](https://linux-hardware.org/?probe=565dfeea66) | May 11, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [50747765ef](https://linux-hardware.org/?probe=50747765ef) | May 10, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [6e8c40ad7c](https://linux-hardware.org/?probe=6e8c40ad7c) | May 10, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [c1c837e821](https://linux-hardware.org/?probe=c1c837e821) | May 10, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c5bad2fcf9](https://linux-hardware.org/?probe=c5bad2fcf9) | May 10, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [d6dab8b59c](https://linux-hardware.org/?probe=d6dab8b59c) | May 10, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [dedc4ce0d5](https://linux-hardware.org/?probe=dedc4ce0d5) | May 10, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [e930eaf7f8](https://linux-hardware.org/?probe=e930eaf7f8) | May 10, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [e041ed14b2](https://linux-hardware.org/?probe=e041ed14b2) | May 10, 2022 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [5590d9a0f3](https://linux-hardware.org/?probe=5590d9a0f3) | May 10, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [ab85a57857](https://linux-hardware.org/?probe=ab85a57857) | May 10, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [82bbcd17e8](https://linux-hardware.org/?probe=82bbcd17e8) | May 10, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [d31e2badae](https://linux-hardware.org/?probe=d31e2badae) | May 09, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [48678afa40](https://linux-hardware.org/?probe=48678afa40) | May 09, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [1899727b8b](https://linux-hardware.org/?probe=1899727b8b) | May 09, 2022 |
| Acer          | Aspire Z3-705               | All in one  | [a25af1cf28](https://linux-hardware.org/?probe=a25af1cf28) | May 09, 2022 |
| ASUSTek       | P5QL PRO                    | Desktop     | [9ea782b1d2](https://linux-hardware.org/?probe=9ea782b1d2) | May 08, 2022 |
| Lenovo        | ThinkPad X131e 33691J6      | Notebook    | [1f492cb261](https://linux-hardware.org/?probe=1f492cb261) | May 08, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [bed44df427](https://linux-hardware.org/?probe=bed44df427) | May 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [180dd73bd6](https://linux-hardware.org/?probe=180dd73bd6) | May 07, 2022 |
| Acer          | Aspire 5810T                | Notebook    | [8d9b944789](https://linux-hardware.org/?probe=8d9b944789) | May 07, 2022 |
| HP            | 3397                        | Desktop     | [157ef440d8](https://linux-hardware.org/?probe=157ef440d8) | May 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0F40... | Notebook    | [9d6a8926ec](https://linux-hardware.org/?probe=9d6a8926ec) | May 06, 2022 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | Notebook    | [b13325e763](https://linux-hardware.org/?probe=b13325e763) | May 06, 2022 |
| MSI           | H310M PRO-VD                | Desktop     | [5f977ecef6](https://linux-hardware.org/?probe=5f977ecef6) | May 06, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| Toshiba       | Satellite C670D             | Notebook    | [3eedd8ce6b](https://linux-hardware.org/?probe=3eedd8ce6b) | May 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [7c416a8fb7](https://linux-hardware.org/?probe=7c416a8fb7) | May 05, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| ASUSTek       | VM42                        | Desktop     | [cb73da6c51](https://linux-hardware.org/?probe=cb73da6c51) | May 05, 2022 |
| ASUSTek       | VM42                        | Desktop     | [1fb131686b](https://linux-hardware.org/?probe=1fb131686b) | May 05, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [21e3f8a718](https://linux-hardware.org/?probe=21e3f8a718) | May 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [a23da6e2be](https://linux-hardware.org/?probe=a23da6e2be) | May 05, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [145317db95](https://linux-hardware.org/?probe=145317db95) | May 05, 2022 |
| Acer          | TravelMate P653-M           | Notebook    | [221d943970](https://linux-hardware.org/?probe=221d943970) | May 04, 2022 |
| ASRock        | X570 Extreme4               | Desktop     | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [30ff3d44b0](https://linux-hardware.org/?probe=30ff3d44b0) | May 04, 2022 |
| HP            | 2AF7                        | Desktop     | [de6583780a](https://linux-hardware.org/?probe=de6583780a) | May 04, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [7dc76bf420](https://linux-hardware.org/?probe=7dc76bf420) | May 04, 2022 |
| HP            | 2AF7                        | Desktop     | [ee82d627d6](https://linux-hardware.org/?probe=ee82d627d6) | May 04, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [6b9d36debb](https://linux-hardware.org/?probe=6b9d36debb) | May 04, 2022 |
| Alienware     | m15 R4                      | Notebook    | [3b09d65e13](https://linux-hardware.org/?probe=3b09d65e13) | May 04, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [00add28269](https://linux-hardware.org/?probe=00add28269) | May 03, 2022 |
| Acer          | Aspire XC-230               | Desktop     | [b80fa8b04f](https://linux-hardware.org/?probe=b80fa8b04f) | May 03, 2022 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [637890bd75](https://linux-hardware.org/?probe=637890bd75) | May 03, 2022 |
| Alienware     | m15 R4                      | Notebook    | [1f5f3048d6](https://linux-hardware.org/?probe=1f5f3048d6) | May 03, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [90aa5187ab](https://linux-hardware.org/?probe=90aa5187ab) | May 02, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [a792e309de](https://linux-hardware.org/?probe=a792e309de) | May 02, 2022 |
| MSI           | GS65 Stealth 8SG            | Notebook    | [05f80b3e70](https://linux-hardware.org/?probe=05f80b3e70) | May 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [ad5bf6fab1](https://linux-hardware.org/?probe=ad5bf6fab1) | May 01, 2022 |
| Samsung       | 950QCG                      | Convertible | [3010ee5185](https://linux-hardware.org/?probe=3010ee5185) | May 01, 2022 |
| Samsung       | 950QCG                      | Convertible | [257ee40584](https://linux-hardware.org/?probe=257ee40584) | May 01, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [dfc204b1b4](https://linux-hardware.org/?probe=dfc204b1b4) | May 01, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [a822b5b8e7](https://linux-hardware.org/?probe=a822b5b8e7) | May 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [6710b89c52](https://linux-hardware.org/?probe=6710b89c52) | Apr 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [3edd5f05f7](https://linux-hardware.org/?probe=3edd5f05f7) | Apr 30, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [90d6769c58](https://linux-hardware.org/?probe=90d6769c58) | Apr 30, 2022 |
| Lenovo        | ThinkPad Edge E530 62724... | Notebook    | [07334ae084](https://linux-hardware.org/?probe=07334ae084) | Apr 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [06b533396d](https://linux-hardware.org/?probe=06b533396d) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f157b373a1](https://linux-hardware.org/?probe=f157b373a1) | Apr 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f339d2405b](https://linux-hardware.org/?probe=f339d2405b) | Apr 29, 2022 |
| ASUSTek       | G55VW                       | Notebook    | [6bd8a1b04a](https://linux-hardware.org/?probe=6bd8a1b04a) | Apr 29, 2022 |
| Dell          | 0VNP2H A00                  | Desktop     | [bb480c7f9c](https://linux-hardware.org/?probe=bb480c7f9c) | Apr 29, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [7bac9962d9](https://linux-hardware.org/?probe=7bac9962d9) | Apr 29, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [5754b2db0d](https://linux-hardware.org/?probe=5754b2db0d) | Apr 29, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [b989838f70](https://linux-hardware.org/?probe=b989838f70) | Apr 29, 2022 |
| Rockchip      | RK3288 Asus Tinker Board... | Soc         | [db72a98d92](https://linux-hardware.org/?probe=db72a98d92) | Apr 29, 2022 |
| HP            | 8433 11                     | Desktop     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 2... | Tablet      | [bdb2f1c4ad](https://linux-hardware.org/?probe=bdb2f1c4ad) | Apr 29, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [681aa1a670](https://linux-hardware.org/?probe=681aa1a670) | Apr 29, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [d48d0527ee](https://linux-hardware.org/?probe=d48d0527ee) | Apr 28, 2022 |
| HP            | 1495                        | Desktop     | [b6e482940f](https://linux-hardware.org/?probe=b6e482940f) | Apr 28, 2022 |
| HP            | 1495                        | Desktop     | [632386ed8d](https://linux-hardware.org/?probe=632386ed8d) | Apr 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e3ea985a9e](https://linux-hardware.org/?probe=e3ea985a9e) | Apr 28, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [92e903308e](https://linux-hardware.org/?probe=92e903308e) | Apr 27, 2022 |
| Dell          | 0R1PCR A00                  | Desktop     | [feec38a0f5](https://linux-hardware.org/?probe=feec38a0f5) | Apr 27, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [f997f2d1c1](https://linux-hardware.org/?probe=f997f2d1c1) | Apr 27, 2022 |
| ASUSTek       | SABERTOOTH Z170 S           | Desktop     | [21663dc8b3](https://linux-hardware.org/?probe=21663dc8b3) | Apr 27, 2022 |
| System76      | Pangolin                    | Notebook    | [d326fc9a39](https://linux-hardware.org/?probe=d326fc9a39) | Apr 27, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [185c64fa0d](https://linux-hardware.org/?probe=185c64fa0d) | Apr 27, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [3c53a0e59d](https://linux-hardware.org/?probe=3c53a0e59d) | Apr 27, 2022 |
| HP            | Unknown                     | Notebook    | [32f3c98619](https://linux-hardware.org/?probe=32f3c98619) | Apr 27, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [68fdd1e81a](https://linux-hardware.org/?probe=68fdd1e81a) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Dell          | 06JWJY A01                  | Desktop     | [938679bafe](https://linux-hardware.org/?probe=938679bafe) | Apr 26, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [9384c00f6e](https://linux-hardware.org/?probe=9384c00f6e) | Apr 26, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [184c256d66](https://linux-hardware.org/?probe=184c256d66) | Apr 26, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [486215d495](https://linux-hardware.org/?probe=486215d495) | Apr 26, 2022 |
| HP            | 3397                        | Desktop     | [754e703cc5](https://linux-hardware.org/?probe=754e703cc5) | Apr 25, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [833d1610d5](https://linux-hardware.org/?probe=833d1610d5) | Apr 25, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [23c9792994](https://linux-hardware.org/?probe=23c9792994) | Apr 25, 2022 |
| Dell          | 05R2TK A01                  | All in one  | [317f2966c3](https://linux-hardware.org/?probe=317f2966c3) | Apr 25, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [17f9b4e988](https://linux-hardware.org/?probe=17f9b4e988) | Apr 25, 2022 |
| Dell          | Latitude D830               | Notebook    | [1c23417a15](https://linux-hardware.org/?probe=1c23417a15) | Apr 25, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [0199a1bcec](https://linux-hardware.org/?probe=0199a1bcec) | Apr 24, 2022 |
| MSI           | GP72 6QF                    | Notebook    | [8a2ac9964c](https://linux-hardware.org/?probe=8a2ac9964c) | Apr 24, 2022 |
| Alienware     | m15 R7                      | Notebook    | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| ASUSTek       | K55A                        | Notebook    | [079c627411](https://linux-hardware.org/?probe=079c627411) | Apr 24, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [33a9b533e8](https://linux-hardware.org/?probe=33a9b533e8) | Apr 23, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 787       | 16.31%  |
| Ubuntu 18.04        | 419       | 8.69%   |
| Ubuntu 22.04        | 118       | 2.45%   |
| OpenMandriva 4.2    | 115       | 2.38%   |
| KDE neon 20.04      | 99        | 2.05%   |
| Linux Mint 20.3     | 98        | 2.03%   |
| OpenMandriva 4.3    | 96        | 1.99%   |
| Xubuntu 20.04       | 94        | 1.95%   |
| Pop!_OS 20.04       | 88        | 1.82%   |
| Manjaro             | 86        | 1.78%   |
| Pop!_OS 21.04       | 84        | 1.74%   |
| Arch                | 81        | 1.68%   |
| Linux Mint 20.1     | 78        | 1.62%   |
| Linux Mint 19.3     | 76        | 1.58%   |
| Zorin 16            | 74        | 1.53%   |
| Debian 11           | 72        | 1.49%   |
| Ubuntu 19.10        | 71        | 1.47%   |
| Zorin 15            | 69        | 1.43%   |
| Ubuntu 21.10        | 69        | 1.43%   |
| Fedora 35           | 68        | 1.41%   |
| Ubuntu 20.10        | 66        | 1.37%   |
| Pop!_OS 20.10       | 65        | 1.35%   |
| Fedora 33           | 64        | 1.33%   |
| Linux Mint 20.2     | 63        | 1.31%   |
| Pop!_OS 22.04       | 60        | 1.24%   |
| Linux Mint 20       | 58        | 1.2%    |
| ArcoLinux Rolling   | 58        | 1.2%    |
| Fedora 32           | 56        | 1.16%   |
| Arch Rolling        | 56        | 1.16%   |
| Ubuntu 21.04        | 52        | 1.08%   |
| Fedora 34           | 50        | 1.04%   |
| Ubuntu 19.04        | 48        | 1%      |
| Pop!_OS 21.10       | 48        | 1%      |
| Fedora 36           | 39        | 0.81%   |
| Fedora 31           | 33        | 0.68%   |
| Debian 10           | 33        | 0.68%   |
| Kubuntu 20.04       | 29        | 0.6%    |
| EndeavourOS Rolling | 29        | 0.6%    |
| Linux Mint 19.2     | 28        | 0.58%   |
| BlackPanther 18.1   | 27        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1610      | 35.08%  |
| Linux Mint    | 413       | 9%      |
| Pop!_OS       | 331       | 7.21%   |
| Fedora        | 294       | 6.41%   |
| OpenMandriva  | 242       | 5.27%   |
| Manjaro       | 188       | 4.1%    |
| Zorin         | 152       | 3.31%   |
| Xubuntu       | 140       | 3.05%   |
| Debian        | 139       | 3.03%   |
| Arch          | 133       | 2.9%    |
| KDE neon      | 112       | 2.44%   |
| ROSA          | 75        | 1.63%   |
| Kubuntu       | 74        | 1.61%   |
| ArcoLinux     | 62        | 1.35%   |
| Gentoo        | 42        | 0.92%   |
| Elementary    | 41        | 0.89%   |
| Endless       | 35        | 0.76%   |
| Lubuntu       | 34        | 0.74%   |
| EndeavourOS   | 33        | 0.72%   |
| openSUSE      | 30        | 0.65%   |
| Ubuntu MATE   | 28        | 0.61%   |
| BlackPanther  | 27        | 0.59%   |
| Clear Linux   | 26        | 0.57%   |
| CentOS        | 26        | 0.57%   |
| Ubuntu Unity  | 24        | 0.52%   |
| Kali          | 23        | 0.5%    |
| Ubuntu Budgie | 21        | 0.46%   |
| LMDE          | 21        | 0.46%   |
| SteamOS       | 20        | 0.44%   |
| MX            | 13        | 0.28%   |
| Garuda Linux  | 13        | 0.28%   |
| Peppermint    | 10        | 0.22%   |
| LinuxFX       | 10        | 0.22%   |
| Parrot        | 8         | 0.17%   |
| Alpine        | 8         | 0.17%   |
| Reborn OS     | 7         | 0.15%   |
| Raspbian      | 7         | 0.15%   |
| Solus         | 6         | 0.13%   |
| Slackware     | 6         | 0.13%   |
| RHEL          | 6         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 112       | 2.09%   |
| 5.4.0-42-generic         | 92        | 1.71%   |
| 5.16.7-desktop-1omv4003  | 91        | 1.7%    |
| 5.11.0-27-generic        | 59        | 1.1%    |
| 5.4.0-58-generic         | 53        | 0.99%   |
| 5.4.0-48-generic         | 50        | 0.93%   |
| 5.3.0-40-generic         | 50        | 0.93%   |
| 5.4.0-52-generic         | 44        | 0.82%   |
| 5.4.0-29-generic         | 43        | 0.8%    |
| 5.8.0-7630-generic       | 42        | 0.78%   |
| 5.11.0-40-generic        | 42        | 0.78%   |
| 5.4.0-40-generic         | 38        | 0.71%   |
| 5.0.0-37-generic         | 38        | 0.71%   |
| 5.4.0-26-generic         | 36        | 0.67%   |
| 5.3.0-46-generic         | 35        | 0.65%   |
| 5.13.0-39-generic        | 35        | 0.65%   |
| 5.4.0-54-generic         | 34        | 0.63%   |
| 5.15.0-48-generic        | 33        | 0.61%   |
| 5.11.0-7620-generic      | 33        | 0.61%   |
| 5.4.0-37-generic         | 32        | 0.6%    |
| 5.15.0-47-generic        | 32        | 0.6%    |
| 5.8.0-50-generic         | 31        | 0.58%   |
| 5.4.0-66-generic         | 30        | 0.56%   |
| 5.15.0-41-generic        | 30        | 0.56%   |
| 5.4.0-45-generic         | 29        | 0.54%   |
| 5.15.0-46-generic        | 29        | 0.54%   |
| 5.4.0-47-generic         | 27        | 0.5%    |
| 5.11.0-38-generic        | 27        | 0.5%    |
| 5.4.0-91-generic         | 26        | 0.48%   |
| 5.4.0-7634-generic       | 26        | 0.48%   |
| 5.4.0-56-generic         | 26        | 0.48%   |
| 5.4.0-33-generic         | 26        | 0.48%   |
| 5.3.0-42-generic         | 26        | 0.48%   |
| 5.8.0-59-generic         | 25        | 0.47%   |
| 5.8.0-44-generic         | 25        | 0.47%   |
| 5.13.0-7614-generic      | 25        | 0.47%   |
| 5.8.0-43-generic         | 24        | 0.45%   |
| 5.8.0-41-generic         | 24        | 0.45%   |
| 5.4.0-74-generic         | 24        | 0.45%   |
| 5.3.0-28-generic         | 24        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1038      | 20.71%  |
| 5.11.0  | 351       | 7%      |
| 5.8.0   | 337       | 6.73%   |
| 4.15.0  | 317       | 6.33%   |
| 5.13.0  | 295       | 5.89%   |
| 5.3.0   | 272       | 5.43%   |
| 5.15.0  | 219       | 4.37%   |
| 5.0.0   | 151       | 3.01%   |
| 5.10.14 | 114       | 2.27%   |
| 4.18.0  | 106       | 2.12%   |
| 5.16.7  | 93        | 1.86%   |
| 5.10.0  | 91        | 1.82%   |
| 4.19.0  | 43        | 0.86%   |
| 5.19.0  | 27        | 0.54%   |
| 5.17.5  | 26        | 0.52%   |
| 5.15.5  | 23        | 0.46%   |
| 4.18.16 | 22        | 0.44%   |
| 4.9.20  | 20        | 0.4%    |
| 5.14.0  | 18        | 0.36%   |
| 4.4.0   | 18        | 0.36%   |
| 4.9.60  | 17        | 0.34%   |
| 5.16.0  | 15        | 0.3%    |
| 5.15.11 | 15        | 0.3%    |
| 5.12.4  | 15        | 0.3%    |
| 5.9.16  | 14        | 0.28%   |
| 5.9.11  | 14        | 0.28%   |
| 5.18.0  | 14        | 0.28%   |
| 5.17.9  | 14        | 0.28%   |
| 5.7.0   | 13        | 0.26%   |
| 3.10.0  | 13        | 0.26%   |
| 5.16.11 | 12        | 0.24%   |
| 5.15.15 | 12        | 0.24%   |
| 5.11.12 | 12        | 0.24%   |
| 5.19.9  | 11        | 0.22%   |
| 5.18.12 | 11        | 0.22%   |
| 5.17.15 | 11        | 0.22%   |
| 5.16.18 | 11        | 0.22%   |
| 5.13.19 | 11        | 0.22%   |
| 5.13.13 | 11        | 0.22%   |
| 5.9.8   | 10        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1128      | 22.91%  |
| 5.8     | 431       | 8.75%   |
| 5.11    | 406       | 8.25%   |
| 5.15    | 374       | 7.6%    |
| 5.13    | 350       | 7.11%   |
| 4.15    | 318       | 6.46%   |
| 5.10    | 308       | 6.26%   |
| 5.3     | 293       | 5.95%   |
| 5.16    | 197       | 4%      |
| 5.0     | 160       | 3.25%   |
| 4.18    | 128       | 2.6%    |
| 5.17    | 94        | 1.91%   |
| 5.9     | 84        | 1.71%   |
| 5.19    | 78        | 1.58%   |
| 5.14    | 72        | 1.46%   |
| 5.18    | 71        | 1.44%   |
| 5.12    | 71        | 1.44%   |
| 4.9     | 64        | 1.3%    |
| 5.6     | 60        | 1.22%   |
| 4.19    | 58        | 1.18%   |
| 5.7     | 51        | 1.04%   |
| 5.5     | 29        | 0.59%   |
| 4.4     | 22        | 0.45%   |
| 6.0     | 18        | 0.37%   |
| 3.10    | 16        | 0.33%   |
| 5.2     | 11        | 0.22%   |
| 4.1     | 6         | 0.12%   |
| 4.13    | 5         | 0.1%    |
| 5.1     | 4         | 0.08%   |
| 4.14    | 3         | 0.06%   |
| 4.8     | 2         | 0.04%   |
| 4.20    | 2         | 0.04%   |
| 4.16    | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| 5       | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| 4.11    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4236      | 96.23%  |
| i686    | 113       | 2.57%   |
| aarch64 | 33        | 0.75%   |
| armv7l  | 17        | 0.39%   |
| mips64  | 1         | 0.02%   |
| armv8l  | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| GNOME                | 2034      | 43.96%  |
| Unknown              | 661       | 14.29%  |
| KDE5                 | 627       | 13.55%  |
| XFCE                 | 336       | 7.26%   |
| X-Cinnamon           | 331       | 7.15%   |
| KDE                  | 145       | 3.13%   |
| MATE                 | 105       | 2.27%   |
| Cinnamon             | 61        | 1.32%   |
| KDE4                 | 57        | 1.23%   |
| Pantheon             | 39        | 0.84%   |
| LXQt                 | 38        | 0.82%   |
| i3                   | 33        | 0.71%   |
| Budgie               | 33        | 0.71%   |
| Unity                | 27        | 0.58%   |
| LXDE                 | 25        | 0.54%   |
| GNOME Flashback      | 18        | 0.39%   |
| Deepin               | 11        | 0.24%   |
| GNOME Classic        | 7         | 0.15%   |
| DWM                  | 7         | 0.15%   |
| qtile                | 6         | 0.13%   |
| Openbox              | 4         | 0.09%   |
| Enlightenment        | 4         | 0.09%   |
| awesome              | 4         | 0.09%   |
| sway                 | 2         | 0.04%   |
| xmonad               | 1         | 0.02%   |
| wmaker-common        | 1         | 0.02%   |
| ubuntustudio         | 1         | 0.02%   |
| trinity              | 1         | 0.02%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.02%   |
| spectrwm             | 1         | 0.02%   |
| river                | 1         | 0.02%   |
| Lubuntu              | 1         | 0.02%   |
| lightdm-xsession     | 1         | 0.02%   |
| LeftWM               | 1         | 0.02%   |
| hyprland             | 1         | 0.02%   |
| bspwm                | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3601      | 79.54%  |
| Wayland | 496       | 10.96%  |
| Unknown | 337       | 7.44%   |
| Tty     | 90        | 1.99%   |
| Web     | 3         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2660      | 58.09%  |
| SDDM    | 557       | 12.16%  |
| GDM     | 502       | 10.96%  |
| LightDM | 332       | 7.25%   |
| GDM3    | 311       | 6.79%   |
| TDM     | 142       | 3.1%    |
| KDM     | 51        | 1.11%   |
| XDM     | 11        | 0.24%   |
| SLiM    | 7         | 0.15%   |
| Ly      | 2         | 0.04%   |
| LXDM    | 2         | 0.04%   |
| MDM     | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_CA      | 2333      | 51.2%   |
| en_US      | 1115      | 24.47%  |
| Unknown    | 566       | 12.42%  |
| fr_CA      | 315       | 6.91%   |
| C          | 100       | 2.19%   |
| fr_FR      | 45        | 0.99%   |
| en_GB      | 23        | 0.5%    |
| en_AU      | 7         | 0.15%   |
| POSIX      | 6         | 0.13%   |
| zh_CN      | 4         | 0.09%   |
| pt_BR      | 4         | 0.09%   |
| es_ES      | 4         | 0.09%   |
| C.UTF8     | 4         | 0.09%   |
| uk_UA      | 3         | 0.07%   |
| ru_RU      | 3         | 0.07%   |
| en_IN      | 3         | 0.07%   |
| de_DE      | 3         | 0.07%   |
| zh_TW      | 2         | 0.04%   |
| pl_PL      | 2         | 0.04%   |
| pa_IN      | 2         | 0.04%   |
| ro_RO      | 1         | 0.02%   |
| nan_TW     | 1         | 0.02%   |
| iu_CA      | 1         | 0.02%   |
| hu_HU      | 1         | 0.02%   |
| ga_IE      | 1         | 0.02%   |
| es_CL      | 1         | 0.02%   |
| en_ZM      | 1         | 0.02%   |
| en_ZA      | 1         | 0.02%   |
| en_US.UTF8 | 1         | 0.02%   |
| en_NZ      | 1         | 0.02%   |
| en_FI      | 1         | 0.02%   |
| de_CH      | 1         | 0.02%   |
| co_FR      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2480      | 55.03%  |
| EFI  | 2027      | 44.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3493      | 77.35%  |
| Overlay | 344       | 7.62%   |
| Btrfs   | 343       | 7.6%    |
| Unknown | 177       | 3.92%   |
| Xfs     | 70        | 1.55%   |
| Zfs     | 40        | 0.89%   |
| Ext2    | 19        | 0.42%   |
| Ext3    | 10        | 0.22%   |
| Aufs    | 8         | 0.18%   |
| F2fs    | 6         | 0.13%   |
| Tmpfs   | 3         | 0.07%   |
| Jfs     | 2         | 0.04%   |
| XXX4    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2790      | 62.01%  |
| GPT     | 1268      | 28.18%  |
| MBR     | 441       | 9.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3793      | 84.31%  |
| Yes       | 706       | 15.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3294      | 73.36%  |
| Yes       | 1196      | 26.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 793       | 18.04%  |
| Dell                    | 650       | 14.78%  |
| Lenovo                  | 584       | 13.28%  |
| Hewlett-Packard         | 560       | 12.74%  |
| Acer                    | 342       | 7.78%   |
| Gigabyte Technology     | 272       | 6.19%   |
| MSI                     | 266       | 6.05%   |
| Apple                   | 157       | 3.57%   |
| ASRock                  | 111       | 2.52%   |
| Toshiba                 | 91        | 2.07%   |
| Intel                   | 66        | 1.5%    |
| Raspberry Pi Foundation | 34        | 0.77%   |
| Sony                    | 32        | 0.73%   |
| Alienware               | 32        | 0.73%   |
| Unknown                 | 30        | 0.68%   |
| Gateway                 | 28        | 0.64%   |
| Supermicro              | 25        | 0.57%   |
| Pegatron                | 25        | 0.57%   |
| Samsung Electronics     | 23        | 0.52%   |
| Foxconn                 | 23        | 0.52%   |
| Microsoft               | 22        | 0.5%    |
| Google                  | 19        | 0.43%   |
| Valve                   | 17        | 0.39%   |
| System76                | 15        | 0.34%   |
| Panasonic               | 14        | 0.32%   |
| Biostar                 | 10        | 0.23%   |
| ECS                     | 9         | 0.2%    |
| ZOTAC                   | 8         | 0.18%   |
| Fujitsu                 | 7         | 0.16%   |
| Razer                   | 6         | 0.14%   |
| HUAWEI                  | 5         | 0.11%   |
| eMachines               | 5         | 0.11%   |
| AMI                     | 5         | 0.11%   |
| TYAN Computer           | 4         | 0.09%   |
| Notebook                | 4         | 0.09%   |
| LG Electronics          | 4         | 0.09%   |
| Fanless Mini PC         | 4         | 0.09%   |
| EVGA                    | 4         | 0.09%   |
| BESSTAR Tech            | 4         | 0.09%   |
| AZW                     | 4         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 49        | 1.11%   |
| Unknown                            | 40        | 0.91%   |
| HP Notebook                        | 19        | 0.43%   |
| HP Pavilion g6                     | 18        | 0.41%   |
| Valve Jupiter                      | 17        | 0.39%   |
| ASUS TUF Gaming X570-PLUS          | 17        | 0.39%   |
| Acer Aspire A315-21                | 14        | 0.32%   |
| MSI MS-7C02                        | 13        | 0.3%    |
| Dell OptiPlex 790                  | 13        | 0.3%    |
| MSI MS-7C37                        | 12        | 0.27%   |
| Dell XPS 15 7590                   | 12        | 0.27%   |
| Dell Latitude E6410                | 12        | 0.27%   |
| RPi Raspberry Pi                   | 11        | 0.25%   |
| HP Z400 Workstation                | 11        | 0.25%   |
| Dell XPS 15 9500                   | 11        | 0.25%   |
| ASUS PRIME B450M-A                 | 11        | 0.25%   |
| HP Pavilion 15                     | 10        | 0.23%   |
| Dell Latitude E6420                | 10        | 0.23%   |
| ASUS TP410UAR                      | 10        | 0.23%   |
| ASUS ROG STRIX B450-F GAMING       | 10        | 0.23%   |
| Apple iMac8,1                      | 10        | 0.23%   |
| Apple iMac7,1                      | 10        | 0.23%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 9         | 0.2%    |
| MSI MS-7C84                        | 9         | 0.2%    |
| HP Pavilion Notebook               | 9         | 0.2%    |
| HP Pavilion dv6                    | 9         | 0.2%    |
| HP EliteBook 8460p                 | 9         | 0.2%    |
| Dell OptiPlex 780                  | 9         | 0.2%    |
| ASUS M5A99FX PRO R2.0              | 9         | 0.2%    |
| ASUS M5A97 LE R2.0                 | 9         | 0.2%    |
| ASRock B450M Pro4                  | 9         | 0.2%    |
| Toshiba Satellite A200             | 8         | 0.18%   |
| MSI MS-7693                        | 8         | 0.18%   |
| Gigabyte B450 AORUS PRO WIFI       | 8         | 0.18%   |
| Dell OptiPlex 7010                 | 8         | 0.18%   |
| Dell Inspiron 1545                 | 8         | 0.18%   |
| ASUS M5A97 R2.0                    | 8         | 0.18%   |
| Apple MacBookPro9,2                | 8         | 0.18%   |
| Apple MacBookPro8,1                | 8         | 0.18%   |
| Apple iMac12,1                     | 8         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 300       | 6.82%   |
| Acer Aspire         | 271       | 6.16%   |
| Dell Inspiron       | 145       | 3.3%    |
| Dell Latitude       | 136       | 3.09%   |
| Dell XPS            | 121       | 2.75%   |
| HP Pavilion         | 111       | 2.52%   |
| Dell OptiPlex       | 100       | 2.27%   |
| Lenovo ThinkCentre  | 90        | 2.05%   |
| ASUS ROG            | 87        | 1.98%   |
| ASUS PRIME          | 87        | 1.98%   |
| Toshiba Satellite   | 78        | 1.77%   |
| HP Compaq           | 78        | 1.77%   |
| Lenovo IdeaPad      | 71        | 1.61%   |
| HP EliteBook        | 69        | 1.57%   |
| ASUS TUF            | 51        | 1.16%   |
| ASUS All            | 49        | 1.11%   |
| Dell Precision      | 48        | 1.09%   |
| HP Laptop           | 46        | 1.05%   |
| Unknown             | 40        | 0.91%   |
| HP ProBook          | 38        | 0.86%   |
| ASUS VivoBook       | 38        | 0.86%   |
| RPi Raspberry       | 34        | 0.77%   |
| HP ENVY             | 32        | 0.73%   |
| Dell Vostro         | 28        | 0.64%   |
| Gigabyte X570       | 24        | 0.55%   |
| Dell Studio         | 23        | 0.52%   |
| Microsoft Surface   | 22        | 0.5%    |
| ASUS M5A97          | 22        | 0.5%    |
| HP EliteDesk        | 21        | 0.48%   |
| HP Notebook         | 19        | 0.43%   |
| Lenovo ThinkStation | 18        | 0.41%   |
| Gigabyte B450       | 18        | 0.41%   |
| Acer Nitro          | 18        | 0.41%   |
| Valve Jupiter       | 17        | 0.39%   |
| Lenovo Yoga         | 17        | 0.39%   |
| Dell PowerEdge      | 17        | 0.39%   |
| Lenovo Legion       | 16        | 0.36%   |
| ASUS SABERTOOTH     | 16        | 0.36%   |
| ASRock B450M        | 15        | 0.34%   |
| Acer Swift          | 15        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 395       | 8.98%   |
| 2012    | 386       | 8.78%   |
| 2020    | 385       | 8.76%   |
| 2019    | 382       | 8.69%   |
| 2011    | 381       | 8.66%   |
| 2013    | 319       | 7.25%   |
| 2017    | 298       | 6.78%   |
| 2010    | 279       | 6.35%   |
| 2014    | 254       | 5.78%   |
| 2008    | 231       | 5.25%   |
| 2016    | 198       | 4.5%    |
| 2015    | 191       | 4.34%   |
| 2009    | 191       | 4.34%   |
| 2021    | 174       | 3.96%   |
| 2007    | 150       | 3.41%   |
| 2006    | 60        | 1.36%   |
| 2022    | 58        | 1.32%   |
| Unknown | 38        | 0.86%   |
| 2005    | 21        | 0.48%   |
| 2004    | 6         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2066      | 46.99%  |
| Desktop        | 1942      | 44.17%  |
| Convertible    | 119       | 2.71%   |
| All in one     | 85        | 1.93%   |
| Server         | 56        | 1.27%   |
| Mini pc        | 49        | 1.11%   |
| System on chip | 43        | 0.98%   |
| Tablet         | 34        | 0.77%   |
| Phone          | 3         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4164      | 93.97%  |
| Enabled  | 267       | 6.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4364      | 99.25%  |
| Yes  | 33        | 0.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 964       | 21.57%  |
| 16.01-24.0      | 960       | 21.48%  |
| 8.01-16.0       | 823       | 18.42%  |
| 3.01-4.0        | 723       | 16.18%  |
| 32.01-64.0      | 495       | 11.08%  |
| 1.01-2.0        | 172       | 3.85%   |
| 64.01-256.0     | 136       | 3.04%   |
| 24.01-32.0      | 77        | 1.72%   |
| 2.01-3.0        | 68        | 1.52%   |
| 0.51-1.0        | 35        | 0.78%   |
| More than 256.0 | 8         | 0.18%   |
| 0.01-0.5        | 6         | 0.13%   |
| Unknown         | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1788      | 36.36%  |
| 2.01-3.0    | 1173      | 23.85%  |
| 4.01-8.0    | 689       | 14.01%  |
| 3.01-4.0    | 617       | 12.55%  |
| 0.51-1.0    | 322       | 6.55%   |
| 8.01-16.0   | 194       | 3.94%   |
| 0.01-0.5    | 76        | 1.55%   |
| 24.01-32.0  | 21        | 0.43%   |
| 32.01-64.0  | 15        | 0.31%   |
| 16.01-24.0  | 14        | 0.28%   |
| 64.01-256.0 | 5         | 0.1%    |
| Unknown     | 4         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2583      | 56.29%  |
| 2       | 1065      | 23.21%  |
| 3       | 411       | 8.96%   |
| 4       | 230       | 5.01%   |
| 5       | 111       | 2.42%   |
| 6       | 55        | 1.2%    |
| 0       | 48        | 1.05%   |
| 7       | 34        | 0.74%   |
| 8       | 19        | 0.41%   |
| 9       | 10        | 0.22%   |
| 10      | 7         | 0.15%   |
| 11      | 4         | 0.09%   |
| Unknown | 4         | 0.09%   |
| 12      | 3         | 0.07%   |
| 14      | 2         | 0.04%   |
| 13      | 2         | 0.04%   |
| 16      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2448      | 54.97%  |
| Yes       | 2005      | 45.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3881      | 88.02%  |
| No        | 528       | 11.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3263      | 73.61%  |
| No        | 1170      | 26.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2463      | 55.1%   |
| No        | 2007      | 44.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Canada  | 4397      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Toronto         | 459       | 9.92%   |
| Montreal        | 451       | 9.75%   |
| Vancouver       | 200       | 4.32%   |
| Calgary         | 181       | 3.91%   |
| Ottawa          | 167       | 3.61%   |
| Edmonton        | 149       | 3.22%   |
| Québec         | 94        | 2.03%   |
| Winnipeg        | 89        | 1.92%   |
| Mississauga     | 72        | 1.56%   |
| Victoria        | 66        | 1.43%   |
| Surrey          | 58        | 1.25%   |
| Regina          | 51        | 1.1%    |
| London          | 47        | 1.02%   |
| Brampton        | 47        | 1.02%   |
| Kitchener       | 46        | 0.99%   |
| Laval           | 45        | 0.97%   |
| Hamilton        | 43        | 0.93%   |
| Saskatoon       | 40        | 0.86%   |
| Gatineau        | 39        | 0.84%   |
| Burnaby         | 38        | 0.82%   |
| Windsor         | 35        | 0.76%   |
| Halifax         | 33        | 0.71%   |
| Oshawa          | 31        | 0.67%   |
| Sherbrooke      | 28        | 0.61%   |
| Kingston        | 28        | 0.61%   |
| Scarborough     | 27        | 0.58%   |
| Trois-Rivières | 25        | 0.54%   |
| New Westminster | 25        | 0.54%   |
| Richmond Hill   | 23        | 0.5%    |
| North Vancouver | 22        | 0.48%   |
| Moncton         | 22        | 0.48%   |
| Kelowna         | 22        | 0.48%   |
| Barrie          | 22        | 0.48%   |
| Oakville        | 21        | 0.45%   |
| Waterloo        | 20        | 0.43%   |
| Levis           | 20        | 0.43%   |
| Red Deer        | 19        | 0.41%   |
| Markham         | 19        | 0.41%   |
| Thunder Bay     | 18        | 0.39%   |
| Prince George   | 18        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 1247      | 2032   | 18.71%  |
| Seagate                   | 1232      | 2131   | 18.48%  |
| Samsung Electronics       | 908       | 1420   | 13.62%  |
| Kingston                  | 414       | 569    | 6.21%   |
| Toshiba                   | 361       | 467    | 5.42%   |
| Unknown                   | 287       | 391    | 4.31%   |
| SanDisk                   | 272       | 340    | 4.08%   |
| Hitachi                   | 242       | 320    | 3.63%   |
| Intel                     | 192       | 299    | 2.88%   |
| Crucial                   | 183       | 247    | 2.75%   |
| A-DATA Technology         | 157       | 208    | 2.36%   |
| SK hynix                  | 133       | 164    | 2%      |
| HGST                      | 111       | 143    | 1.67%   |
| Micron Technology         | 67        | 91     | 1.01%   |
| Apple                     | 58        | 72     | 0.87%   |
| Phison                    | 52        | 78     | 0.78%   |
| Fujitsu                   | 40        | 46     | 0.6%    |
| OCZ                       | 38        | 45     | 0.57%   |
| SPCC                      | 30        | 37     | 0.45%   |
| Corsair                   | 29        | 35     | 0.44%   |
| LITEONIT                  | 27        | 28     | 0.41%   |
| China                     | 27        | 30     | 0.41%   |
| KIOXIA                    | 26        | 31     | 0.39%   |
| PNY                       | 25        | 38     | 0.38%   |
| Silicon Motion            | 23        | 33     | 0.35%   |
| Patriot                   | 22        | 26     | 0.33%   |
| ASMT                      | 22        | 27     | 0.33%   |
| Mushkin                   | 21        | 25     | 0.32%   |
| Micron/Crucial Technology | 20        | 28     | 0.3%    |
| XPG                       | 18        | 26     | 0.27%   |
| Team                      | 18        | 20     | 0.27%   |
| Maxtor                    | 16        | 22     | 0.24%   |
| LITEON                    | 16        | 18     | 0.24%   |
| Hewlett-Packard           | 16        | 27     | 0.24%   |
| JMicron Technology        | 15        | 20     | 0.23%   |
| SABRENT                   | 13        | 17     | 0.2%    |
| KingFast                  | 13        | 16     | 0.2%    |
| Unknown                   | 12        | 12     | 0.18%   |
| TO Exter                  | 10        | 12     | 0.15%   |
| External                  | 10        | 17     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 101       | 1.33%   |
| Samsung SSD 850 EVO 250GB              | 74        | 0.98%   |
| Samsung SSD 860 EVO 500GB              | 66        | 0.87%   |
| Seagate ST2000DM008-2FR102 2TB         | 61        | 0.8%    |
| Kingston SA400S37120G 120GB SSD        | 56        | 0.74%   |
| Samsung NVMe SSD Drive 500GB           | 54        | 0.71%   |
| Samsung SSD 850 EVO 500GB              | 52        | 0.69%   |
| Samsung SSD 860 EVO 1TB                | 51        | 0.67%   |
| Unknown MMC Card  32GB                 | 50        | 0.66%   |
| SanDisk NVMe SSD Drive 500GB           | 49        | 0.65%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 47        | 0.62%   |
| Unknown SD/MMC/MS PRO 1TB              | 45        | 0.59%   |
| Kingston SA400S37480G 480GB SSD        | 45        | 0.59%   |
| Toshiba MQ01ABD100 1TB                 | 44        | 0.58%   |
| Kingston SV300S37A120G 120GB SSD       | 42        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB         | 41        | 0.54%   |
| Unknown MMC Card  64GB                 | 40        | 0.53%   |
| Seagate ST500DM002-1BD142 500GB        | 40        | 0.53%   |
| Seagate ST4000DM004-2CV104 4TB         | 40        | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 39        | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 39        | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB               | 37        | 0.49%   |
| Seagate ST2000DM001-1ER164 2TB         | 37        | 0.49%   |
| Seagate ST1000LX015-1U7172 1TB         | 37        | 0.49%   |
| Seagate ST1000LM035-1RK172 1TB         | 37        | 0.49%   |
| Samsung SSD 860 EVO 250GB              | 37        | 0.49%   |
| Seagate ST2000DM006-2DM164 2TB         | 35        | 0.46%   |
| SanDisk NVMe SSD Drive 1TB             | 35        | 0.46%   |
| Toshiba DT01ACA200 2TB                 | 33        | 0.43%   |
| Seagate ST1000DM003-1ER162 1TB         | 33        | 0.43%   |
| HGST HTS721010A9E630 1TB               | 33        | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB         | 32        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB            | 32        | 0.42%   |
| Seagate ST3500418AS 500GB              | 31        | 0.41%   |
| Seagate Expansion Desk 8TB             | 29        | 0.38%   |
| Seagate Expansion 2TB                  | 29        | 0.38%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 29        | 0.38%   |
| Samsung NVMe SSD Drive 512GB           | 29        | 0.38%   |
| Seagate ST31000528AS 1TB               | 28        | 0.37%   |
| Kingston SV300S37A240G 240GB SSD       | 27        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1191      | 2043   | 39.15%  |
| WDC                 | 989       | 1608   | 32.51%  |
| Toshiba             | 294       | 388    | 9.66%   |
| Hitachi             | 242       | 320    | 7.96%   |
| HGST                | 111       | 143    | 3.65%   |
| Samsung Electronics | 48        | 62     | 1.58%   |
| Unknown             | 45        | 58     | 1.48%   |
| Fujitsu             | 40        | 46     | 1.31%   |
| Apple               | 22        | 24     | 0.72%   |
| Maxtor              | 16        | 22     | 0.53%   |
| SABRENT             | 12        | 16     | 0.39%   |
| Maxone              | 6         | 8      | 0.2%    |
| JMicron Technology  | 4         | 4      | 0.13%   |
| ASMT                | 3         | 6      | 0.1%    |
| USB 3.0             | 2         | 5      | 0.07%   |
| Hewlett-Packard     | 2         | 9      | 0.07%   |
| DAS                 | 2         | 14     | 0.07%   |
| USB3.0              | 1         | 2      | 0.03%   |
| SATAFIRM            | 1         | 1      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 6      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| Maxtor 6            | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| KESU                | 1         | 2      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| External            | 1         | 1      | 0.03%   |
| DELLBOSS            | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 540       | 828    | 25.01%  |
| Kingston            | 357       | 491    | 16.54%  |
| WDC                 | 187       | 263    | 8.66%   |
| Crucial             | 164       | 211    | 7.6%    |
| A-DATA Technology   | 137       | 182    | 6.35%   |
| SanDisk             | 133       | 157    | 6.16%   |
| Intel               | 89        | 120    | 4.12%   |
| Micron Technology   | 48        | 68     | 2.22%   |
| OCZ                 | 37        | 41     | 1.71%   |
| Seagate             | 30        | 42     | 1.39%   |
| Apple               | 30        | 35     | 1.39%   |
| SK hynix            | 28        | 36     | 1.3%    |
| LITEONIT            | 27        | 28     | 1.25%   |
| China               | 27        | 30     | 1.25%   |
| SPCC                | 26        | 33     | 1.2%    |
| PNY                 | 25        | 38     | 1.16%   |
| Toshiba             | 22        | 26     | 1.02%   |
| Patriot             | 22        | 26     | 1.02%   |
| Mushkin             | 19        | 23     | 0.88%   |
| Corsair             | 18        | 20     | 0.83%   |
| ASMT                | 18        | 20     | 0.83%   |
| Team                | 17        | 19     | 0.79%   |
| LITEON              | 13        | 14     | 0.6%    |
| TO Exter            | 10        | 12     | 0.46%   |
| Hewlett-Packard     | 10        | 13     | 0.46%   |
| Dogfish             | 10        | 12     | 0.46%   |
| OWC                 | 8         | 17     | 0.37%   |
| Transcend           | 7         | 8      | 0.32%   |
| NGFF                | 6         | 7      | 0.28%   |
| KingDian            | 6         | 6      | 0.28%   |
| TCSUNBOW            | 5         | 6      | 0.23%   |
| Lexar               | 5         | 6      | 0.23%   |
| KingFast            | 5         | 5      | 0.23%   |
| WDC WDS             | 4         | 5      | 0.19%   |
| Vaseky              | 3         | 4      | 0.14%   |
| TSA                 | 3         | 3      | 0.14%   |
| SUNEAST             | 3         | 3      | 0.14%   |
| OCZ-VERTEX3         | 3         | 3      | 0.14%   |
| KingSpec            | 3         | 5      | 0.14%   |
| AMD                 | 3         | 4      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2504      | 4796   | 42.83%  |
| SSD     | 1846      | 2931   | 31.57%  |
| NVMe    | 1154      | 1735   | 19.74%  |
| MMC     | 229       | 309    | 3.92%   |
| Unknown | 114       | 161    | 1.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3533      | 7306   | 66.75%  |
| NVMe | 1142      | 1705   | 21.58%  |
| SAS  | 389       | 612    | 7.35%   |
| MMC  | 229       | 309    | 4.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2510      | 3960   | 52.57%  |
| 0.51-1.0   | 1374      | 2161   | 28.77%  |
| 1.01-2.0   | 484       | 828    | 10.14%  |
| 3.01-4.0   | 172       | 282    | 3.6%    |
| 4.01-10.0  | 127       | 275    | 2.66%   |
| 2.01-3.0   | 101       | 205    | 2.12%   |
| 10.01-20.0 | 6         | 10     | 0.13%   |
| 20.01-50.0 | 1         | 6      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1115      | 23.59%  |
| 251-500        | 1037      | 21.94%  |
| 501-1000       | 716       | 15.15%  |
| 1001-2000      | 389       | 8.23%   |
| 1-20           | 364       | 7.7%    |
| More than 3000 | 329       | 6.96%   |
| 51-100         | 255       | 5.39%   |
| 21-50          | 185       | 3.91%   |
| 2001-3000      | 170       | 3.6%    |
| Unknown        | 167       | 3.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1944      | 39.75%  |
| 21-50          | 815       | 16.66%  |
| 101-250        | 556       | 11.37%  |
| 51-100         | 494       | 10.1%   |
| 251-500        | 331       | 6.77%   |
| 501-1000       | 236       | 4.83%   |
| Unknown        | 167       | 3.41%   |
| 1001-2000      | 162       | 3.31%   |
| More than 3000 | 122       | 2.49%   |
| 2001-3000      | 64        | 1.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 8         | 9      | 2.01%   |
| Seagate ST500LM000-1EJ162 500GB     | 6         | 6      | 1.5%    |
| WDC WD2500HHTZ-04N21V0 250GB        | 5         | 5      | 1.25%   |
| WDC WD20EARS-00MVWB0 2TB            | 5         | 6      | 1.25%   |
| Seagate ST9500420AS 500GB           | 5         | 5      | 1.25%   |
| Seagate ST9500325AS 500GB           | 5         | 5      | 1.25%   |
| Seagate ST3500418AS 500GB           | 5         | 5      | 1.25%   |
| Seagate ST31000528AS 1TB            | 5         | 5      | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 6      | 1.25%   |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 1.25%   |
| WDC WD40EFRX-68WT0N0 4TB            | 4         | 17     | 1%      |
| Toshiba MQ01ABD100 1TB              | 4         | 5      | 1%      |
| Seagate ST500LT012-9WS142 500GB     | 4         | 4      | 1%      |
| Kingston SV300S37A120G 120GB SSD    | 4         | 6      | 1%      |
| Intel SSDSA1M080G2LE 80GB           | 4         | 4      | 1%      |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 1%      |
| WDC WD10EARX-00N0YB0 1TB            | 3         | 4      | 0.75%   |
| Seagate ST9320325AS 320GB           | 3         | 6      | 0.75%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 3      | 0.75%   |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 3      | 0.75%   |
| Seagate ST31500341AS 1TB            | 3         | 4      | 0.75%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 3      | 0.75%   |
| Seagate ST1000DM003-1ER162 1TB      | 3         | 4      | 0.75%   |
| Samsung Electronics SSD 870 EVO 1TB | 3         | 3      | 0.75%   |
| Hitachi HDS721010CLA332 1TB         | 3         | 3      | 0.75%   |
| HGST HTS725050A7E630 500GB          | 3         | 3      | 0.75%   |
| HGST HTS545050A7E680 500GB          | 3         | 3      | 0.75%   |
| Crucial CT1000P1SSD8 1TB            | 3         | 9      | 0.75%   |
| A-DATA Technology SX900 256GB SSD   | 3         | 3      | 0.75%   |
| WDC WD6400AAKS-22A7B2 640GB         | 2         | 2      | 0.5%    |
| WDC WD30EFRX-68EUZN0 3TB            | 2         | 2      | 0.5%    |
| WDC WD20EZRZ-00Z5HB0 2TB            | 2         | 2      | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 2      | 0.5%    |
| WDC WD10EZEX-08M2NA0 1TB            | 2         | 3      | 0.5%    |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 0.5%    |
| Toshiba MK2552GSX 250GB             | 2         | 2      | 0.5%    |
| Toshiba MK2035GSS 200GB             | 2         | 2      | 0.5%    |
| Seagate ST8000DM004-2CX188 8TB      | 2         | 4      | 0.5%    |
| Seagate ST8000AS0002-1NA17Z 8TB     | 2         | 2      | 0.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 128       | 163    | 33.33%  |
| WDC                 | 100       | 133    | 26.04%  |
| Hitachi             | 32        | 33     | 8.33%   |
| Samsung Electronics | 21        | 24     | 5.47%   |
| Toshiba             | 20        | 21     | 5.21%   |
| HGST                | 16        | 16     | 4.17%   |
| Kingston            | 14        | 19     | 3.65%   |
| Intel               | 12        | 13     | 3.13%   |
| Crucial             | 9         | 16     | 2.34%   |
| A-DATA Technology   | 9         | 9      | 2.34%   |
| SK hynix            | 3         | 3      | 0.78%   |
| LITEONIT            | 3         | 3      | 0.78%   |
| OCZ                 | 2         | 2      | 0.52%   |
| Mushkin             | 2         | 2      | 0.52%   |
| Fujitsu             | 2         | 2      | 0.52%   |
| ASMT                | 2         | 3      | 0.52%   |
| Apple               | 2         | 2      | 0.52%   |
| Micron Technology   | 1         | 1      | 0.26%   |
| Maxtor              | 1         | 1      | 0.26%   |
| LITEON              | 1         | 1      | 0.26%   |
| Hewlett-Packard     | 1         | 1      | 0.26%   |
| Drevo               | 1         | 1      | 0.26%   |
| DAS                 | 1         | 3      | 0.26%   |
| Corsair             | 1         | 1      | 0.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 128       | 163    | 41.29%  |
| WDC                 | 100       | 133    | 32.26%  |
| Hitachi             | 32        | 33     | 10.32%  |
| Toshiba             | 19        | 20     | 6.13%   |
| HGST                | 16        | 16     | 5.16%   |
| Samsung Electronics | 8         | 10     | 2.58%   |
| Fujitsu             | 2         | 2      | 0.65%   |
| Apple               | 2         | 2      | 0.65%   |
| Maxtor              | 1         | 1      | 0.32%   |
| DAS                 | 1         | 3      | 0.32%   |
| ASMT                | 1         | 2      | 0.32%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 292       | 385    | 79.56%  |
| SSD  | 63        | 69     | 17.17%  |
| NVMe | 12        | 19     | 3.27%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2003FYYS-18W0B0 2TB         | 1         | 1      | 20%     |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 20%     |
| LITEON CA3-8D512 512GB            | 1         | 2      | 20%     |
| Intel SSDSA1M160G2HP 160GB        | 1         | 1      | 20%     |
| Hewlett-Packard EF0450FARMV 450GB | 1         | 4      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| LITEON              | 1         | 2      | 20%     |
| Intel               | 1         | 1      | 20%     |
| Hewlett-Packard     | 1         | 4      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2987      | 6587   | 62.11%  |
| Works    | 1464      | 2863   | 30.44%  |
| Malfunc  | 353       | 473    | 7.34%   |
| Failed   | 5         | 9      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2859      | 51.33%  |
| AMD                              | 1012      | 18.17%  |
| Samsung Electronics              | 424       | 7.61%   |
| SanDisk                          | 260       | 4.67%   |
| ASMedia Technology               | 127       | 2.28%   |
| Marvell Technology Group         | 110       | 1.97%   |
| SK hynix                         | 104       | 1.87%   |
| Nvidia                           | 99        | 1.78%   |
| JMicron Technology               | 80        | 1.44%   |
| Phison Electronics               | 71        | 1.27%   |
| Kingston Technology Company      | 62        | 1.11%   |
| Toshiba America Info Systems     | 47        | 0.84%   |
| Micron/Crucial Technology        | 40        | 0.72%   |
| ADATA Technology                 | 39        | 0.7%    |
| LSI Logic / Symbios Logic        | 34        | 0.61%   |
| Silicon Motion                   | 32        | 0.57%   |
| KIOXIA                           | 29        | 0.52%   |
| Broadcom / LSI                   | 23        | 0.41%   |
| Micron Technology                | 20        | 0.36%   |
| Realtek Semiconductor            | 15        | 0.27%   |
| Silicon Image                    | 12        | 0.22%   |
| Seagate Technology               | 10        | 0.18%   |
| VIA Technologies                 | 7         | 0.13%   |
| Hewlett-Packard                  | 7         | 0.13%   |
| Lite-On Technology               | 6         | 0.11%   |
| Apple                            | 6         | 0.11%   |
| Union Memory (Shenzhen)          | 5         | 0.09%   |
| Lenovo                           | 5         | 0.09%   |
| Unknown                          | 4         | 0.07%   |
| HighPoint Technologies           | 4         | 0.07%   |
| Adaptec                          | 4         | 0.07%   |
| Silicon Integrated Systems [SiS] | 3         | 0.05%   |
| Integrated Technology Express    | 3         | 0.05%   |
| Shenzhen Longsys Electronics     | 2         | 0.04%   |
| ULi Electronics                  | 1         | 0.02%   |
| Solid State Storage Technology   | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Loongson Technology              | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 677       | 10.25%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 230       | 3.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 199       | 3.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 190       | 2.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 157       | 2.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 152       | 2.3%    |
| AMD 400 Series Chipset SATA Controller                                         | 148       | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 141       | 2.13%   |
| Intel SATA Controller [RAID mode]                                              | 125       | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 123       | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 120       | 1.82%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 120       | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 102       | 1.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 100       | 1.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 93        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 93        | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 84        | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 82        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 80        | 1.21%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 77        | 1.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 73        | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 73        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 72        | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 70        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 70        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 68        | 1.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 66        | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 65        | 0.98%   |
| AMD 500 Series Chipset SATA Controller                                         | 59        | 0.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 58        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 57        | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 56        | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 53        | 0.8%    |
| Samsung NVMe SSD Controller 980                                                | 51        | 0.77%   |
| Intel SSD 660P Series                                                          | 48        | 0.73%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 44        | 0.67%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 43        | 0.65%   |
| JMicron JMB363 SATA/IDE Controller                                             | 41        | 0.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 41        | 0.62%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 39        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3223      | 57.59%  |
| NVMe | 1158      | 20.69%  |
| IDE  | 738       | 13.19%  |
| RAID | 426       | 7.61%   |
| SAS  | 38        | 0.68%   |
| SCSI | 13        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 3174      | 72.19%  |
| AMD      | 1170      | 26.61%  |
| ARM      | 48        | 1.09%   |
| Unknown  | 4         | 0.09%   |
| QUALCOMM | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 52        | 1.18%   |
| AMD Ryzen 5 3600 6-Core Processor             | 43        | 0.98%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 37        | 0.84%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 35        | 0.79%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 35        | 0.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 33        | 0.75%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 33        | 0.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 33        | 0.75%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 32        | 0.73%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 31        | 0.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.68%   |
| ARM Processor                                 | 30        | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 0.66%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 29        | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 28        | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 28        | 0.64%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 26        | 0.59%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 26        | 0.59%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 25        | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 23        | 0.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 23        | 0.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 0.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 23        | 0.52%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 23        | 0.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 22        | 0.5%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 22        | 0.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 21        | 0.48%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 21        | 0.48%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 20        | 0.45%   |
| AMD FX-8350 Eight-Core Processor              | 20        | 0.45%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 19        | 0.43%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 19        | 0.43%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 18        | 0.41%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 18        | 0.41%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 18        | 0.41%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 17        | 0.39%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 939       | 21.33%  |
| Intel Core i7           | 925       | 21.01%  |
| Intel Core 2 Duo        | 227       | 5.16%   |
| Intel Core i3           | 224       | 5.09%   |
| AMD Ryzen 5             | 219       | 4.97%   |
| Other                   | 218       | 4.95%   |
| AMD Ryzen 7             | 203       | 4.61%   |
| Intel Xeon              | 163       | 3.7%    |
| Intel Celeron           | 123       | 2.79%   |
| AMD FX                  | 89        | 2.02%   |
| Intel Pentium           | 80        | 1.82%   |
| AMD Ryzen 9             | 79        | 1.79%   |
| AMD A6                  | 68        | 1.54%   |
| AMD A10                 | 62        | 1.41%   |
| Intel Core 2 Quad       | 59        | 1.34%   |
| Intel Atom              | 58        | 1.32%   |
| Intel Pentium Dual-Core | 55        | 1.25%   |
| AMD Ryzen 3             | 42        | 0.95%   |
| Intel Pentium Dual      | 38        | 0.86%   |
| Intel Core i9           | 38        | 0.86%   |
| AMD Athlon 64 X2        | 36        | 0.82%   |
| AMD A8                  | 36        | 0.82%   |
| Intel Core 2            | 33        | 0.75%   |
| AMD A4                  | 32        | 0.73%   |
| Intel Genuine           | 21        | 0.48%   |
| AMD Athlon II X2        | 20        | 0.45%   |
| AMD Phenom II X4        | 19        | 0.43%   |
| AMD Phenom              | 17        | 0.39%   |
| AMD E                   | 16        | 0.36%   |
| Intel Pentium D         | 15        | 0.34%   |
| AMD Phenom II X6        | 15        | 0.34%   |
| Intel Pentium Silver    | 14        | 0.32%   |
| Intel Pentium 4         | 14        | 0.32%   |
| AMD Ryzen Threadripper  | 13        | 0.3%    |
| AMD E2                  | 13        | 0.3%    |
| AMD Athlon              | 13        | 0.3%    |
| AMD E1                  | 12        | 0.27%   |
| ARM BCM                 | 9         | 0.2%    |
| AMD Turion 64 X2 Mobile | 9         | 0.2%    |
| AMD Ryzen 5 PRO         | 9         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1659      | 37.6%   |
| 4       | 1652      | 37.44%  |
| 6       | 445       | 10.09%  |
| 8       | 332       | 7.52%   |
| 1       | 99        | 2.24%   |
| 12      | 85        | 1.93%   |
| 16      | 43        | 0.97%   |
| 3       | 43        | 0.97%   |
| 10      | 18        | 0.41%   |
| 14      | 11        | 0.25%   |
| Unknown | 8         | 0.18%   |
| 24      | 7         | 0.16%   |
| 20      | 5         | 0.11%   |
| 56      | 2         | 0.05%   |
| 64      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 7       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4318      | 98.14%  |
| 2       | 75        | 1.7%    |
| Unknown | 6         | 0.14%   |
| 3       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2820      | 64.02%  |
| 1       | 1577      | 35.8%   |
| Unknown | 8         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4259      | 96.44%  |
| Unknown        | 112       | 2.54%   |
| 32-bit         | 38        | 0.86%   |
| 64-bit         | 7         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1087      | 23.82%  |
| 0x306a9    | 260       | 5.7%    |
| 0x206a7    | 253       | 5.54%   |
| 0x306c3    | 195       | 4.27%   |
| 0x1067a    | 170       | 3.73%   |
| 0x906ea    | 122       | 2.67%   |
| 0x506e3    | 84        | 1.84%   |
| 0x806ea    | 83        | 1.82%   |
| 0x20655    | 82        | 1.8%    |
| 0x08701021 | 79        | 1.73%   |
| 0x40651    | 76        | 1.67%   |
| 0x906e9    | 73        | 1.6%    |
| 0x6fd      | 67        | 1.47%   |
| 0x806e9    | 65        | 1.42%   |
| 0x406e3    | 63        | 1.38%   |
| 0x06001119 | 57        | 1.25%   |
| 0x806ec    | 54        | 1.18%   |
| 0x306d4    | 53        | 1.16%   |
| 0x20652    | 49        | 1.07%   |
| 0x6fb      | 48        | 1.05%   |
| 0x10676    | 48        | 1.05%   |
| 0x08701013 | 47        | 1.03%   |
| 0x106e5    | 46        | 1.01%   |
| 0x06000852 | 44        | 0.96%   |
| 0x0800820d | 43        | 0.94%   |
| 0x010000c8 | 43        | 0.94%   |
| 0xa0652    | 42        | 0.92%   |
| 0x806c1    | 40        | 0.88%   |
| 0x706e5    | 35        | 0.77%   |
| 0x30678    | 33        | 0.72%   |
| 0x206d7    | 33        | 0.72%   |
| 0x106a5    | 31        | 0.68%   |
| 0x08108109 | 28        | 0.61%   |
| 0x406c4    | 27        | 0.59%   |
| 0x906ed    | 25        | 0.55%   |
| 0x206c2    | 25        | 0.55%   |
| 0x03000027 | 25        | 0.55%   |
| 0x806eb    | 24        | 0.53%   |
| 0x306f2    | 24        | 0.53%   |
| 0x0a50000c | 24        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 578       | 13.14%  |
| Haswell          | 383       | 8.7%    |
| IvyBridge        | 347       | 7.89%   |
| SandyBridge      | 338       | 7.68%   |
| Penryn           | 266       | 6.05%   |
| Zen 2            | 226       | 5.14%   |
| Skylake          | 198       | 4.5%    |
| Core             | 183       | 4.16%   |
| Westmere         | 182       | 4.14%   |
| Zen+             | 136       | 3.09%   |
| Piledriver       | 130       | 2.95%   |
| Unknown          | 122       | 2.77%   |
| K10              | 113       | 2.57%   |
| Zen              | 106       | 2.41%   |
| CometLake        | 104       | 2.36%   |
| Silvermont       | 103       | 2.34%   |
| Zen 3            | 99        | 2.25%   |
| Nehalem          | 98        | 2.23%   |
| Excavator        | 81        | 1.84%   |
| Broadwell        | 80        | 1.82%   |
| TigerLake        | 63        | 1.43%   |
| K8 Hammer        | 60        | 1.36%   |
| Icelake          | 55        | 1.25%   |
| Puma             | 37        | 0.84%   |
| Goldmont plus    | 37        | 0.84%   |
| NetBurst         | 34        | 0.77%   |
| Bobcat           | 34        | 0.77%   |
| K10 Llano        | 32        | 0.73%   |
| Bulldozer        | 31        | 0.7%    |
| Bonnell          | 27        | 0.61%   |
| Jaguar           | 24        | 0.55%   |
| P6               | 23        | 0.52%   |
| Alderlake Hybrid | 22        | 0.5%    |
| Goldmont         | 18        | 0.41%   |
| Steamroller      | 16        | 0.36%   |
| K8 & K10 hybrid  | 10        | 0.23%   |
| Tremont          | 4         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2206      | 44.35%  |
| Nvidia                                       | 1444      | 29.03%  |
| AMD                                          | 1261      | 25.35%  |
| Matrox Electronics Systems                   | 36        | 0.72%   |
| ASPEED Technology                            | 18        | 0.36%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.06%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.04%   |
| VIA Technologies                             | 2         | 0.04%   |
| Loongson Technology                          | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 213       | 4.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 168       | 3.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 130       | 2.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 112       | 2.16%   |
| Intel UHD Graphics 620                                                                   | 111       | 2.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 90        | 1.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 89        | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 87        | 1.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 84        | 1.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 73        | 1.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 72        | 1.39%   |
| Intel HD Graphics 530                                                                    | 67        | 1.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 66        | 1.28%   |
| Intel HD Graphics 620                                                                    | 63        | 1.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 62        | 1.2%    |
| AMD Renoir                                                                               | 59        | 1.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 57        | 1.1%    |
| Intel HD Graphics 5500                                                                   | 57        | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 57        | 1.1%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 55        | 1.06%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 51        | 0.99%   |
| Intel HD Graphics 630                                                                    | 51        | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 49        | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 49        | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 0.93%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 47        | 0.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 45        | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 44        | 0.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 44        | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 42        | 0.81%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 42        | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 36        | 0.7%    |
| AMD Cezanne                                                                              | 36        | 0.7%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 34        | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 32        | 0.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 0.62%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 32        | 0.62%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 31        | 0.6%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 30        | 0.58%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 30        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x Intel                 | 1677      | 37.76%  |
| 1 x AMD                   | 1073      | 24.16%  |
| 1 x Nvidia                | 955       | 21.5%   |
| Intel + Nvidia            | 392       | 8.83%   |
| Intel + AMD               | 70        | 1.58%   |
| 2 x AMD                   | 62        | 1.4%    |
| Other                     | 55        | 1.24%   |
| AMD + Nvidia              | 53        | 1.19%   |
| 2 x Nvidia                | 34        | 0.77%   |
| 1 x Matrox                | 28        | 0.63%   |
| 1 x ASPEED                | 15        | 0.34%   |
| Nvidia + Matrox           | 7         | 0.16%   |
| 1 x SiS                   | 3         | 0.07%   |
| Intel + 2 x Nvidia        | 3         | 0.07%   |
| 2 x Intel                 | 2         | 0.05%   |
| 1 x VIA                   | 2         | 0.05%   |
| Nvidia + ASPEED           | 2         | 0.05%   |
| 5 x Nvidia                | 1         | 0.02%   |
| 2 x Loongson Technology   | 1         | 0.02%   |
| 1 x XGI                   | 1         | 0.02%   |
| 1 x Intel + 3 x AMD       | 1         | 0.02%   |
| AMD + 2 x Nvidia          | 1         | 0.02%   |
| AMD + XGI                 | 1         | 0.02%   |
| AMD + Nvidia + 1 x ASPEED | 1         | 0.02%   |
| AMD + Matrox              | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3418      | 76.41%  |
| Proprietary | 842       | 18.82%  |
| Unknown     | 213       | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2368      | 51.83%  |
| 0.01-0.5   | 581       | 12.72%  |
| 1.01-2.0   | 504       | 11.03%  |
| 0.51-1.0   | 350       | 7.66%   |
| 3.01-4.0   | 277       | 6.06%   |
| 7.01-8.0   | 265       | 5.8%    |
| 5.01-6.0   | 123       | 2.69%   |
| 8.01-16.0  | 58        | 1.27%   |
| 2.01-3.0   | 39        | 0.85%   |
| 4.01-5.0   | 2         | 0.04%   |
| 32.01-64.0 | 1         | 0.02%   |
| 16.01-24.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 656       | 13.28%  |
| AU Optronics            | 494       | 10%     |
| LG Display              | 368       | 7.45%   |
| Dell                    | 342       | 6.92%   |
| Goldstar                | 302       | 6.11%   |
| Chimei Innolux          | 268       | 5.42%   |
| Acer                    | 257       | 5.2%    |
| BOE                     | 223       | 4.51%   |
| Hewlett-Packard         | 209       | 4.23%   |
| Ancor Communications    | 182       | 3.68%   |
| BenQ                    | 146       | 2.95%   |
| Sharp                   | 143       | 2.89%   |
| Apple                   | 135       | 2.73%   |
| Lenovo                  | 118       | 2.39%   |
| ViewSonic               | 97        | 1.96%   |
| ASUSTek Computer        | 79        | 1.6%    |
| Chi Mei Optoelectronics | 68        | 1.38%   |
| LG Electronics          | 62        | 1.25%   |
| Unknown                 | 54        | 1.09%   |
| Philips                 | 52        | 1.05%   |
| Toshiba                 | 51        | 1.03%   |
| Sony                    | 47        | 0.95%   |
| AOC                     | 47        | 0.95%   |
| PANDA                   | 35        | 0.71%   |
| LG Philips              | 29        | 0.59%   |
| NEC Computers           | 23        | 0.47%   |
| Panasonic               | 22        | 0.45%   |
| InfoVision              | 20        | 0.4%    |
| HannStar                | 19        | 0.38%   |
| MSI                     | 18        | 0.36%   |
| Insignia                | 15        | 0.3%    |
| ANX                     | 14        | 0.28%   |
| Vizio                   | 12        | 0.24%   |
| Gigabyte Technology     | 12        | 0.24%   |
| AUS                     | 12        | 0.24%   |
| Gateway                 | 11        | 0.22%   |
| Sceptre Tech            | 9         | 0.18%   |
| Quanta Display          | 9         | 0.18%   |
| HKC                     | 9         | 0.18%   |
| Hitachi                 | 9         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 30        | 0.58%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 29        | 0.56%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 27        | 0.52%   |
| Toshiba TV TSB0206 1920x1080                                             | 19        | 0.37%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 19        | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.35%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 17        | 0.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 17        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.31%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 15        | 0.29%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch    | 15        | 0.29%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 14        | 0.27%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                   | 14        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 14        | 0.27%   |
| ANX ANX7530 U ANX7539 800x1280                                           | 14        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 13        | 0.25%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch           | 13        | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.23%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.23%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.23%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 11        | 0.21%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 11        | 0.21%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 11        | 0.21%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                        | 11        | 0.21%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 11        | 0.21%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch             | 11        | 0.21%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch    | 11        | 0.21%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 10        | 0.19%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 10        | 0.19%   |
| MSI G241VC MSI1462 1920x1080 521x294mm 23.6-inch                         | 10        | 0.19%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 10        | 0.19%   |
| Sharp HDMI SHP0FFB 1920x1080 820x460mm 37.0-inch                         | 9         | 0.17%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch        | 9         | 0.17%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 9         | 0.17%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 9         | 0.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 9         | 0.17%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 9         | 0.17%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 9         | 0.17%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 9         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1892      | 39.74%  |
| 1366x768 (WXGA)    | 757       | 15.9%   |
| 3840x2160 (4K)     | 314       | 6.6%    |
| 1680x1050 (WSXGA+) | 233       | 4.89%   |
| 1600x900 (HD+)     | 208       | 4.37%   |
| 2560x1440 (QHD)    | 199       | 4.18%   |
| 1280x1024 (SXGA)   | 178       | 3.74%   |
| 1280x800 (WXGA)    | 138       | 2.9%    |
| 1920x1200 (WUXGA)  | 130       | 2.73%   |
| 1440x900 (WXGA+)   | 120       | 2.52%   |
| Unknown            | 108       | 2.27%   |
| 1360x768           | 53        | 1.11%   |
| 3440x1440          | 48        | 1.01%   |
| 3840x1080          | 45        | 0.95%   |
| 2560x1080          | 28        | 0.59%   |
| 1920x540           | 28        | 0.59%   |
| 2880x1800          | 18        | 0.38%   |
| 2560x1600          | 18        | 0.38%   |
| 800x1280           | 17        | 0.36%   |
| 1600x1200          | 16        | 0.34%   |
| 3200x1800 (QHD+)   | 13        | 0.27%   |
| 1024x768 (XGA)     | 13        | 0.27%   |
| 1024x600           | 13        | 0.27%   |
| 1280x720 (HD)      | 12        | 0.25%   |
| 2736x1824          | 11        | 0.23%   |
| 3840x2400          | 10        | 0.21%   |
| 3840x1200          | 7         | 0.15%   |
| 3600x1080          | 7         | 0.15%   |
| 5760x1080          | 6         | 0.13%   |
| 2160x1440          | 6         | 0.13%   |
| 2048x1152          | 6         | 0.13%   |
| 7680x2160          | 5         | 0.11%   |
| 3200x1080          | 5         | 0.11%   |
| 3456x2160          | 4         | 0.08%   |
| 2288x1287          | 4         | 0.08%   |
| 5760x2160          | 3         | 0.06%   |
| 5120x1440          | 3         | 0.06%   |
| 4480x1440          | 3         | 0.06%   |
| 3280x1080          | 3         | 0.06%   |
| 3200x2000          | 3         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1082      | 22.12%  |
| 27      | 394       | 8.05%   |
| Unknown | 379       | 7.75%   |
| 13      | 364       | 7.44%   |
| 24      | 346       | 7.07%   |
| 23      | 336       | 6.87%   |
| 21      | 292       | 5.97%   |
| 14      | 281       | 5.74%   |
| 17      | 261       | 5.34%   |
| 19      | 161       | 3.29%   |
| 22      | 131       | 2.68%   |
| 31      | 123       | 2.51%   |
| 20      | 123       | 2.51%   |
| 18      | 66        | 1.35%   |
| 34      | 63        | 1.29%   |
| 12      | 63        | 1.29%   |
| 72      | 45        | 0.92%   |
| 84      | 43        | 0.88%   |
| 11      | 41        | 0.84%   |
| 32      | 33        | 0.67%   |
| 40      | 22        | 0.45%   |
| 25      | 21        | 0.43%   |
| 74      | 19        | 0.39%   |
| 54      | 18        | 0.37%   |
| 10      | 17        | 0.35%   |
| 37      | 16        | 0.33%   |
| 26      | 16        | 0.33%   |
| 16      | 12        | 0.25%   |
| 43      | 11        | 0.22%   |
| 48      | 10        | 0.2%    |
| 49      | 9         | 0.18%   |
| 46      | 9         | 0.18%   |
| 28      | 9         | 0.18%   |
| 47      | 7         | 0.14%   |
| 42      | 6         | 0.12%   |
| 39      | 6         | 0.12%   |
| 69      | 5         | 0.1%    |
| 52      | 5         | 0.1%    |
| 36      | 5         | 0.1%    |
| 35      | 5         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1569      | 32.84%  |
| 501-600        | 973       | 20.36%  |
| 401-500        | 664       | 13.9%   |
| Unknown        | 379       | 7.93%   |
| 351-400        | 333       | 6.97%   |
| 201-300        | 311       | 6.51%   |
| 601-700        | 182       | 3.81%   |
| 1501-2000      | 117       | 2.45%   |
| 701-800        | 100       | 2.09%   |
| 1001-1500      | 72        | 1.51%   |
| 801-900        | 53        | 1.11%   |
| 901-1000       | 20        | 0.42%   |
| 1-100          | 3         | 0.06%   |
| More than 2000 | 1         | 0.02%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3023      | 68.96%  |
| 16/10   | 661       | 15.08%  |
| Unknown | 303       | 6.91%   |
| 5/4     | 167       | 3.81%   |
| 21/9    | 69        | 1.57%   |
| 3/2     | 58        | 1.32%   |
| 4/3     | 43        | 0.98%   |
| 32/9    | 18        | 0.41%   |
| 0.62    | 15        | 0.34%   |
| 6/5     | 14        | 0.32%   |
| 1.96    | 4         | 0.09%   |
| 0.67    | 3         | 0.07%   |
| 3.40    | 2         | 0.05%   |
| 3.73    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 1.00    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1074      | 22.35%  |
| 201-250        | 889       | 18.5%   |
| 81-90          | 496       | 10.32%  |
| 301-350        | 405       | 8.43%   |
| Unknown        | 379       | 7.89%   |
| 151-200        | 356       | 7.41%   |
| 351-500        | 230       | 4.79%   |
| More than 1000 | 158       | 3.29%   |
| 121-130        | 154       | 3.2%    |
| 71-80          | 150       | 3.12%   |
| 141-150        | 131       | 2.73%   |
| 251-300        | 115       | 2.39%   |
| 501-1000       | 102       | 2.12%   |
| 61-70          | 51        | 1.06%   |
| 51-60          | 43        | 0.89%   |
| 131-140        | 27        | 0.56%   |
| 41-50          | 17        | 0.35%   |
| 111-120        | 16        | 0.33%   |
| 91-100         | 9         | 0.19%   |
| 1-40           | 4         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1703      | 36.59%  |
| 101-120       | 1163      | 24.99%  |
| 121-160       | 929       | 19.96%  |
| Unknown       | 379       | 8.14%   |
| 161-240       | 199       | 4.28%   |
| 1-50          | 177       | 3.8%    |
| More than 240 | 104       | 2.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3424      | 75.77%  |
| 2     | 755       | 16.71%  |
| 0     | 207       | 4.58%   |
| 3     | 121       | 2.68%   |
| 4     | 9         | 0.2%    |
| 5     | 2         | 0.04%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2295      | 34.59%  |
| Realtek Semiconductor           | 2056      | 30.99%  |
| Qualcomm Atheros                | 769       | 11.59%  |
| Broadcom                        | 468       | 7.05%   |
| Broadcom Limited                | 121       | 1.82%   |
| Marvell Technology Group        | 113       | 1.7%    |
| Ralink                          | 90        | 1.36%   |
| Nvidia                          | 85        | 1.28%   |
| Ralink Technology               | 69        | 1.04%   |
| TP-Link                         | 61        | 0.92%   |
| D-Link                          | 54        | 0.81%   |
| ASIX Electronics                | 53        | 0.8%    |
| Linksys                         | 39        | 0.59%   |
| MediaTek                        | 31        | 0.47%   |
| D-Link System                   | 31        | 0.47%   |
| Samsung Electronics             | 28        | 0.42%   |
| ASUSTek Computer                | 28        | 0.42%   |
| Qualcomm Atheros Communications | 22        | 0.33%   |
| NetGear                         | 18        | 0.27%   |
| Microsoft                       | 18        | 0.27%   |
| Aquantia                        | 17        | 0.26%   |
| DisplayLink                     | 15        | 0.23%   |
| Lenovo                          | 14        | 0.21%   |
| Google                          | 9         | 0.14%   |
| Belkin Components               | 9         | 0.14%   |
| Sierra Wireless                 | 8         | 0.12%   |
| Motorola PCS                    | 5         | 0.08%   |
| Microchip Technology            | 5         | 0.08%   |
| Edimax Technology               | 5         | 0.08%   |
| Arduino SA                      | 5         | 0.08%   |
| AMD                             | 5         | 0.08%   |
| VIA Technologies                | 4         | 0.06%   |
| Qualcomm                        | 4         | 0.06%   |
| Micro Star International        | 4         | 0.06%   |
| Apple                           | 4         | 0.06%   |
| ZyDAS                           | 3         | 0.05%   |
| Xiaomi                          | 3         | 0.05%   |
| Research In Motion              | 3         | 0.05%   |
| JMicron Technology              | 3         | 0.05%   |
| Hewlett-Packard                 | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1371      | 17.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 262       | 3.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 253       | 3.23%   |
| Intel Wi-Fi 6 AX200                                               | 217       | 2.77%   |
| Intel I211 Gigabit Network Connection                             | 147       | 1.88%   |
| Intel Wireless 8265 / 8275                                        | 127       | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 105       | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 100       | 1.28%   |
| Intel Wireless 7260                                               | 97        | 1.24%   |
| Intel Wireless 7265                                               | 92        | 1.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 84        | 1.07%   |
| Intel Ethernet Connection (2) I219-V                              | 84        | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 83        | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 83        | 1.06%   |
| Intel Ethernet Connection I217-LM                                 | 80        | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 77        | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 77        | 0.98%   |
| Intel Wireless 8260                                               | 76        | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 74        | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 69        | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 67        | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 66        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 63        | 0.8%    |
| Intel 82579V Gigabit Network Connection                           | 56        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 55        | 0.7%    |
| Intel Wireless-AC 9260                                            | 51        | 0.65%   |
| Intel Wi-Fi 6 AX201                                               | 47        | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 45        | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 45        | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 45        | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 43        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                          | 43        | 0.55%   |
| Intel Centrino Ultimate-N 6300                                    | 42        | 0.54%   |
| Intel Ethernet Controller I225-V                                  | 41        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 41        | 0.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 40        | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 39        | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 39        | 0.5%    |
| Intel Wireless 3165                                               | 39        | 0.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 37        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1550      | 44.08%  |
| Qualcomm Atheros                      | 613       | 17.43%  |
| Realtek Semiconductor                 | 474       | 13.48%  |
| Broadcom                              | 310       | 8.82%   |
| Ralink                                | 90        | 2.56%   |
| Broadcom Limited                      | 72        | 2.05%   |
| Ralink Technology                     | 69        | 1.96%   |
| TP-Link                               | 56        | 1.59%   |
| D-Link                                | 53        | 1.51%   |
| Linksys                               | 37        | 1.05%   |
| MediaTek                              | 30        | 0.85%   |
| ASUSTek Computer                      | 28        | 0.8%    |
| Qualcomm Atheros Communications       | 22        | 0.63%   |
| D-Link System                         | 19        | 0.54%   |
| NetGear                               | 18        | 0.51%   |
| Marvell Technology Group              | 18        | 0.51%   |
| Microsoft                             | 13        | 0.37%   |
| Belkin Components                     | 9         | 0.26%   |
| Sierra Wireless                       | 8         | 0.23%   |
| Edimax Technology                     | 5         | 0.14%   |
| Qualcomm                              | 4         | 0.11%   |
| Micro Star International              | 4         | 0.11%   |
| ZyDAS                                 | 3         | 0.09%   |
| Gemtek                                | 3         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| Wilocity                              | 1         | 0.03%   |
| Wacom                                 | 1         | 0.03%   |
| TRENDnet                              | 1         | 0.03%   |
| Dell                                  | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| Accton Technology                     | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 217       | 6.12%   |
| Intel Wireless 8265 / 8275                                     | 127       | 3.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 100       | 2.82%   |
| Intel Wireless 7260                                            | 97        | 2.73%   |
| Intel Wireless 7265                                            | 92        | 2.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 84        | 2.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 83        | 2.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 83        | 2.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 77        | 2.17%   |
| Intel Wireless 8260                                            | 76        | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 74        | 2.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 69        | 1.95%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 67        | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 66        | 1.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 63        | 1.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 55        | 1.55%   |
| Intel Wireless-AC 9260                                         | 51        | 1.44%   |
| Intel Wi-Fi 6 AX201                                            | 47        | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 45        | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 43        | 1.21%   |
| Intel Centrino Ultimate-N 6300                                 | 42        | 1.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 40        | 1.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 39        | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 39        | 1.1%    |
| Intel Wireless 3165                                            | 39        | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 37        | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 36        | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 32        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 31        | 0.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 31        | 0.87%   |
| Realtek 802.11ac NIC                                           | 30        | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 30        | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 30        | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 28        | 0.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 28        | 0.79%   |
| Intel Centrino Wireless-N 2230                                 | 28        | 0.79%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 28        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 27        | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 27        | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 27        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1851      | 44.79%  |
| Intel                                  | 1365      | 33.03%  |
| Broadcom                               | 242       | 5.86%   |
| Qualcomm Atheros                       | 237       | 5.73%   |
| Marvell Technology Group               | 95        | 2.3%    |
| Nvidia                                 | 84        | 2.03%   |
| Broadcom Limited                       | 54        | 1.31%   |
| ASIX Electronics                       | 53        | 1.28%   |
| Samsung Electronics                    | 28        | 0.68%   |
| Aquantia                               | 17        | 0.41%   |
| DisplayLink                            | 15        | 0.36%   |
| Lenovo                                 | 13        | 0.31%   |
| D-Link System                          | 12        | 0.29%   |
| Google                                 | 8         | 0.19%   |
| TP-Link                                | 7         | 0.17%   |
| VIA Technologies                       | 4         | 0.1%    |
| Apple                                  | 4         | 0.1%    |
| Xiaomi                                 | 3         | 0.07%   |
| Research In Motion                     | 3         | 0.07%   |
| Microsoft                              | 3         | 0.07%   |
| Microchip Technology                   | 3         | 0.07%   |
| JMicron Technology                     | 3         | 0.07%   |
| Hewlett-Packard                        | 3         | 0.07%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.05%   |
| Linksys                                | 2         | 0.05%   |
| LG Electronics                         | 2         | 0.05%   |
| ICS Advent                             | 2         | 0.05%   |
| IBM                                    | 2         | 0.05%   |
| Huawei Technologies                    | 2         | 0.05%   |
| D-Link                                 | 2         | 0.05%   |
| 3Com                                   | 2         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.02%   |
| Sun Microsystems                       | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| MediaTek                               | 1         | 0.02%   |
| HTC (High Tech Computer)               | 1         | 0.02%   |
| HMD Global                             | 1         | 0.02%   |
| Attansic Technology                    | 1         | 0.02%   |
| ADMtek                                 | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1371      | 32.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 262       | 6.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 253       | 5.97%   |
| Intel I211 Gigabit Network Connection                             | 147       | 3.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 105       | 2.48%   |
| Intel Ethernet Connection (2) I219-V                              | 84        | 1.98%   |
| Intel Ethernet Connection I217-LM                                 | 80        | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 76        | 1.79%   |
| Intel 82579V Gigabit Network Connection                           | 56        | 1.32%   |
| Intel Ethernet Connection (7) I219-V                              | 45        | 1.06%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 45        | 1.06%   |
| Intel 82577LM Gigabit Network Connection                          | 43        | 1.02%   |
| Intel Ethernet Controller I225-V                                  | 41        | 0.97%   |
| ASIX AX88179 Gigabit Ethernet                                     | 41        | 0.97%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 37        | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                             | 36        | 0.85%   |
| Intel 82574L Gigabit Network Connection                           | 36        | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 35        | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 33        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 0.71%   |
| Intel Ethernet Connection (2) I218-V                              | 30        | 0.71%   |
| Nvidia MCP61 Ethernet                                             | 29        | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 28        | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 28        | 0.66%   |
| Intel I210 Gigabit Network Connection                             | 27        | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25        | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 24        | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 24        | 0.57%   |
| Intel 82567LM Gigabit Network Connection                          | 24        | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 23        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 23        | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 23        | 0.54%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 23        | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 21        | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 20        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 19        | 0.45%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 19        | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 18        | 0.43%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3875      | 53.89%  |
| WiFi     | 3259      | 45.33%  |
| Modem    | 41        | 0.57%   |
| Unknown  | 15        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2430      | 52.45%  |
| Ethernet | 2202      | 47.53%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2460      | 55.56%  |
| 1     | 1703      | 38.46%  |
| 3     | 129       | 2.91%   |
| 0     | 93        | 2.1%    |
| 4     | 26        | 0.59%   |
| 5     | 10        | 0.23%   |
| 6     | 4         | 0.09%   |
| 22    | 1         | 0.02%   |
| 21    | 1         | 0.02%   |
| 12    | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3905      | 87.6%   |
| Yes  | 553       | 12.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1183      | 46.98%  |
| Broadcom                        | 189       | 7.51%   |
| Realtek Semiconductor           | 169       | 6.71%   |
| Qualcomm Atheros Communications | 168       | 6.67%   |
| Apple                           | 145       | 5.76%   |
| Cambridge Silicon Radio         | 140       | 5.56%   |
| Lite-On Technology              | 113       | 4.49%   |
| IMC Networks                    | 111       | 4.41%   |
| ASUSTek Computer                | 72        | 2.86%   |
| Foxconn / Hon Hai               | 61        | 2.42%   |
| Dell                            | 40        | 1.59%   |
| Hewlett-Packard                 | 27        | 1.07%   |
| Marvell Semiconductor           | 17        | 0.68%   |
| Toshiba                         | 14        | 0.56%   |
| Ralink                          | 13        | 0.52%   |
| Dynex                           | 13        | 0.52%   |
| Alps Electric                   | 6         | 0.24%   |
| Realtek                         | 5         | 0.2%    |
| Logitech                        | 5         | 0.2%    |
| Micro Star International        | 4         | 0.16%   |
| Primax Electronics              | 3         | 0.12%   |
| MediaTek                        | 3         | 0.12%   |
| Integrated System Solution      | 3         | 0.12%   |
| Ralink Technology               | 2         | 0.08%   |
| Zeevo                           | 1         | 0.04%   |
| TP-Link                         | 1         | 0.04%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Kensington                      | 1         | 0.04%   |
| HTC (High Tech Computer)        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Foxconn International           | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 430       | 17.06%  |
| Intel AX200 Bluetooth                                    | 210       | 8.33%   |
| Intel AX201 Bluetooth                                    | 165       | 6.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 140       | 5.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 132       | 5.24%   |
| Realtek Bluetooth Radio                                  | 110       | 4.36%   |
| Intel Wireless-AC 3168 Bluetooth                         | 83        | 3.29%   |
| Qualcomm Atheros  Bluetooth Device                       | 78        | 3.09%   |
| IMC Networks Bluetooth Radio                             | 55        | 2.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 52        | 2.06%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 50        | 1.98%   |
| Apple Bluetooth Host Controller                          | 50        | 1.98%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 49        | 1.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 42        | 1.67%   |
| Apple Bluetooth USB Host Controller                      | 41        | 1.63%   |
| Realtek  Bluetooth 4.2 Adapter                           | 36        | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                       | 34        | 1.35%   |
| Lite-On Atheros AR3012 Bluetooth                         | 32        | 1.27%   |
| Apple Bluetooth HCI                                      | 31        | 1.23%   |
| Intel AX210 Bluetooth                                    | 30        | 1.19%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 27        | 1.07%   |
| Broadcom BCM2045B (BDC-2.1)                              | 25        | 0.99%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 24        | 0.95%   |
| Lite-On Bluetooth Device                                 | 22        | 0.87%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 22        | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 21        | 0.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 20        | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 19        | 0.75%   |
| IMC Networks Bluetooth Device                            | 17        | 0.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 16        | 0.63%   |
| Broadcom HP Portable SoftSailing                         | 16        | 0.63%   |
| Intel Bluetooth Device                                   | 15        | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                         | 14        | 0.56%   |
| Ralink RT3290 Bluetooth                                  | 13        | 0.52%   |
| Marvell Bluetooth and Wireless LAN Composite             | 13        | 0.52%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 13        | 0.52%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 12        | 0.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 12        | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 12        | 0.48%   |
| IMC Networks Wireless_Device                             | 11        | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 3008      | 47.31%  |
| AMD                                             | 1433      | 22.54%  |
| Nvidia                                          | 1144      | 17.99%  |
| C-Media Electronics                             | 136       | 2.14%   |
| Logitech                                        | 71        | 1.12%   |
| Creative Labs                                   | 55        | 0.87%   |
| Corsair                                         | 26        | 0.41%   |
| Texas Instruments                               | 25        | 0.39%   |
| Realtek Semiconductor                           | 24        | 0.38%   |
| JMTek                                           | 23        | 0.36%   |
| Blue Microphones                                | 23        | 0.36%   |
| SteelSeries ApS                                 | 20        | 0.31%   |
| Creative Technology                             | 19        | 0.3%    |
| Focusrite-Novation                              | 17        | 0.27%   |
| Razer USA                                       | 16        | 0.25%   |
| Lenovo                                          | 16        | 0.25%   |
| GN Netcom                                       | 16        | 0.25%   |
| Kingston Technology                             | 15        | 0.24%   |
| Plantronics                                     | 13        | 0.2%    |
| GYROCOM C&C                                     | 13        | 0.2%    |
| Sony                                            | 12        | 0.19%   |
| Samson Technologies                             | 12        | 0.19%   |
| Generalplus Technology                          | 10        | 0.16%   |
| ASUSTek Computer                                | 9         | 0.14%   |
| VIA Technologies                                | 8         | 0.13%   |
| M-Audio                                         | 8         | 0.13%   |
| FiiO Electronics Technology                     | 7         | 0.11%   |
| Yamaha                                          | 6         | 0.09%   |
| XMOS                                            | 6         | 0.09%   |
| Sennheiser Communications                       | 6         | 0.09%   |
| SAVITECH                                        | 6         | 0.09%   |
| Dell                                            | 6         | 0.09%   |
| Bose                                            | 6         | 0.09%   |
| Tenx Technology                                 | 5         | 0.08%   |
| NAD Electronics                                 | 5         | 0.08%   |
| Cambridge Silicon Radio                         | 5         | 0.08%   |
| Audio-Technica                                  | 5         | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 4         | 0.06%   |
| Micro Star International                        | 4         | 0.06%   |
| Licensed by Sony Computer Entertainment America | 4         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 330       | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 290       | 3.89%   |
| Intel Sunrise Point-LP HD Audio                                            | 267       | 3.58%   |
| AMD Family 17h/19h HD Audio Controller                                     | 231       | 3.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 224       | 3%      |
| AMD Starship/Matisse HD Audio Controller                                   | 215       | 2.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 214       | 2.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 200       | 2.68%   |
| AMD FCH Azalia Controller                                                  | 188       | 2.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 169       | 2.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 162       | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 160       | 2.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 130       | 1.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 125       | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 112       | 1.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 105       | 1.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 104       | 1.39%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 99        | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 95        | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 91        | 1.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 91        | 1.22%   |
| Intel 8 Series HD Audio Controller                                         | 91        | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                   | 91        | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 87        | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 86        | 1.15%   |
| Intel 200 Series PCH HD Audio                                              | 83        | 1.11%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 80        | 1.07%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 78        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                  | 75        | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 70        | 0.94%   |
| Intel Broadwell-U Audio Controller                                         | 70        | 0.94%   |
| Nvidia GP104 High Definition Audio Controller                              | 66        | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 66        | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 65        | 0.87%   |
| Nvidia GK107 HDMI Audio Controller                                         | 63        | 0.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 63        | 0.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 61        | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 58        | 0.78%   |
| AMD Navi 10 HDMI Audio                                                     | 55        | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 50        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 483       | 19.63%  |
| SK hynix                                         | 456       | 18.54%  |
| Kingston                                         | 298       | 12.11%  |
| Unknown                                          | 257       | 10.45%  |
| Micron Technology                                | 241       | 9.8%    |
| G.Skill                                          | 166       | 6.75%   |
| Corsair                                          | 150       | 6.1%    |
| Crucial                                          | 111       | 4.51%   |
| Elpida                                           | 50        | 2.03%   |
| Nanya Technology                                 | 48        | 1.95%   |
| Ramaxel Technology                               | 38        | 1.54%   |
| A-DATA Technology                                | 36        | 1.46%   |
| Patriot                                          | 23        | 0.93%   |
| Unknown                                          | 10        | 0.41%   |
| Unknown (ABCD)                                   | 7         | 0.28%   |
| Transcend                                        | 7         | 0.28%   |
| Team                                             | 7         | 0.28%   |
| ASint Technology                                 | 7         | 0.28%   |
| Unifosa                                          | 6         | 0.24%   |
| Toshiba                                          | 6         | 0.24%   |
| Timetec                                          | 4         | 0.16%   |
| Avant                                            | 4         | 0.16%   |
| Qimonda                                          | 3         | 0.12%   |
| PNY                                              | 3         | 0.12%   |
| CSX                                              | 3         | 0.12%   |
| SHARETRONIC                                      | 2         | 0.08%   |
| OCZ                                              | 2         | 0.08%   |
| Neo Forza                                        | 2         | 0.08%   |
| Mushkin                                          | 2         | 0.08%   |
| Hewlett-Packard                                  | 2         | 0.08%   |
| Axiom                                            | 2         | 0.08%   |
| Apacer                                           | 2         | 0.08%   |
| Unknown (7F7F7F94FFFFFFFF)                       | 1         | 0.04%   |
| Unknown (0x505344323247363637325300000000000000) | 1         | 0.04%   |
| Unknown (0x4D342037305432383634515A332D43453620) | 1         | 0.04%   |
| Unknown (0x0C26)                                 | 1         | 0.04%   |
| Unknown (0x0080)                                 | 1         | 0.04%   |
| Unknown (08AE)                                   | 1         | 0.04%   |
| Thermaltake                                      | 1         | 0.04%   |
| Super Talent                                     | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 22        | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 19        | 0.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 18        | 0.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 18        | 0.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 18        | 0.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 17        | 0.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 16        | 0.6%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                | 16        | 0.6%    |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s            | 15        | 0.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 14        | 0.52%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 14        | 0.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 14        | 0.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 14        | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 13        | 0.49%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 13        | 0.49%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 12        | 0.45%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s                 | 12        | 0.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 0.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 10        | 0.37%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 10        | 0.37%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 10        | 0.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 10        | 0.37%   |
| Unknown                                                             | 10        | 0.37%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 9         | 0.34%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 9         | 0.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 9         | 0.34%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 9         | 0.34%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                             | 8         | 0.3%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 8         | 0.3%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 8         | 0.3%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 8         | 0.3%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 8         | 0.3%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 8         | 0.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 8         | 0.3%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 8         | 0.3%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                 | 8         | 0.3%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 8         | 0.3%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                 | 8         | 0.3%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s               | 8         | 0.3%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 7         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 894       | 42.8%   |
| DDR3    | 776       | 37.15%  |
| DDR2    | 129       | 6.18%   |
| Unknown | 65        | 3.11%   |
| LPDDR4  | 63        | 3.02%   |
| LPDDR3  | 63        | 3.02%   |
| SDRAM   | 61        | 2.92%   |
| DDR     | 26        | 1.24%   |
| DDR5    | 8         | 0.38%   |
| LPDDR5  | 2         | 0.1%    |
| DRAM    | 2         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1020      | 49.42%  |
| DIMM         | 892       | 43.22%  |
| Row Of Chips | 126       | 6.1%    |
| Chip         | 14        | 0.68%   |
| Unknown      | 9         | 0.44%   |
| FB-DIMM      | 3         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 830       | 35.73%  |
| 4096   | 669       | 28.8%   |
| 2048   | 334       | 14.38%  |
| 16384  | 321       | 13.82%  |
| 1024   | 104       | 4.48%   |
| 32768  | 52        | 2.24%   |
| 512    | 10        | 0.43%   |
| 129408 | 1         | 0.04%   |
| 65536  | 1         | 0.04%   |
| 256    | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 469       | 20.58%  |
| 3200    | 272       | 11.94%  |
| 2667    | 269       | 11.8%   |
| 1333    | 217       | 9.52%   |
| 2400    | 163       | 7.15%   |
| 2133    | 124       | 5.44%   |
| 3600    | 80        | 3.51%   |
| 667     | 68        | 2.98%   |
| 1334    | 63        | 2.76%   |
| 800     | 63        | 2.76%   |
| 1867    | 51        | 2.24%   |
| 1067    | 42        | 1.84%   |
| Unknown | 36        | 1.58%   |
| 1066    | 35        | 1.54%   |
| 4267    | 31        | 1.36%   |
| 2666    | 22        | 0.97%   |
| 3866    | 19        | 0.83%   |
| 3266    | 18        | 0.79%   |
| 3400    | 16        | 0.7%    |
| 3733    | 15        | 0.66%   |
| 3000    | 15        | 0.66%   |
| 1866    | 15        | 0.66%   |
| 4199    | 13        | 0.57%   |
| 3466    | 12        | 0.53%   |
| 3800    | 11        | 0.48%   |
| 2933    | 11        | 0.48%   |
| 533     | 11        | 0.48%   |
| 4800    | 9         | 0.39%   |
| 8400    | 8         | 0.35%   |
| 2048    | 7         | 0.31%   |
| 975     | 7         | 0.31%   |
| 400     | 7         | 0.31%   |
| 2800    | 6         | 0.26%   |
| 2000    | 6         | 0.26%   |
| 1639    | 6         | 0.26%   |
| 2465    | 5         | 0.22%   |
| 1800    | 5         | 0.22%   |
| 49926   | 4         | 0.18%   |
| 6400    | 4         | 0.18%   |
| 3334    | 4         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Brother Industries       | 64        | 35.16%  |
| Hewlett-Packard          | 53        | 29.12%  |
| Samsung Electronics      | 25        | 13.74%  |
| Canon                    | 24        | 13.19%  |
| Seiko Epson              | 8         | 4.4%    |
| Lexmark International    | 2         | 1.1%    |
| Dymo-CoStar              | 2         | 1.1%    |
| Dell                     | 2         | 1.1%    |
| Zhuhai Poskey Technology | 1         | 0.55%   |
| Prolific Technology      | 1         | 0.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Brother Printer                      | 9         | 4.81%   |
| HP LaserJet 1018                     | 5         | 2.67%   |
| Seiko Epson ET-3750 Series           | 4         | 2.14%   |
| HP LaserJet 1020                     | 4         | 2.14%   |
| Brother HL-L2390DW                   | 4         | 2.14%   |
| Brother HL-L2320D series             | 4         | 2.14%   |
| Brother HL-5370DW series             | 4         | 2.14%   |
| Samsung ML-216x Series Laser Printer | 3         | 1.6%    |
| Samsung ML-1670 Series               | 3         | 1.6%    |
| HP LaserJet 4250                     | 3         | 1.6%    |
| HP ENVY 4520 series                  | 3         | 1.6%    |
| HP DeskJet 3630 series               | 3         | 1.6%    |
| Canon PIXMA MG2900 Series            | 3         | 1.6%    |
| Brother MFC-J480DW                   | 3         | 1.6%    |
| Brother MFC-9130CW                   | 3         | 1.6%    |
| Brother HL-L2360D series             | 3         | 1.6%    |
| Brother HL-2270DW Laser Printer      | 3         | 1.6%    |
| Brother DCP-L2540DW                  | 3         | 1.6%    |
| Samsung ML-1660 Series               | 2         | 1.07%   |
| Samsung M267x 287x Series            | 2         | 1.07%   |
| Samsung M2070 Series                 | 2         | 1.07%   |
| HP OfficeJet 3830 series             | 2         | 1.07%   |
| HP LaserJet Pro M202dw               | 2         | 1.07%   |
| HP LaserJet M101-M106                | 2         | 1.07%   |
| HP DeskJet 3700 series               | 2         | 1.07%   |
| HP DeskJet 2620 All-in-One Printer   | 2         | 1.07%   |
| Dymo-CoStar LabelWriter 450          | 2         | 1.07%   |
| Canon PIXMA MX920 Series             | 2         | 1.07%   |
| Canon PIXMA MX530 Series             | 2         | 1.07%   |
| Canon MF3010                         | 2         | 1.07%   |
| Brother MFC-J485DW                   | 2         | 1.07%   |
| Brother MFC-9330CDW                  | 2         | 1.07%   |
| Brother HL-L3290CDW series           | 2         | 1.07%   |
| Brother HL-2140 series               | 2         | 1.07%   |
| Zhuhai Poskey Printer                | 1         | 0.53%   |
| Seiko Epson XP-4100 Series           | 1         | 0.53%   |
| Seiko Epson WF-3520 Series           | 1         | 0.53%   |
| Seiko Epson L3160 Series             | 1         | 0.53%   |
| Seiko Epson ET-4760 Series           | 1         | 0.53%   |
| Seiko Epson ET-3850 Series           | 1         | 0.53%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 17        | 60.71%  |
| Hewlett-Packard | 6         | 21.43%  |
| Seiko Epson     | 5         | 17.86%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 700F                                | 4         | 14.29%  |
| Canon CanoScan LiDE 220                                 | 4         | 14.29%  |
| Canon CanoScan LiDE 210                                 | 3         | 10.71%  |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 2         | 7.14%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1         | 3.57%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 3.57%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]           | 1         | 3.57%   |
| HP ScanJet G4050                                        | 1         | 3.57%   |
| HP ScanJet G4010                                        | 1         | 3.57%   |
| HP ScanJet 82x0C                                        | 1         | 3.57%   |
| HP ScanJet 5590                                         | 1         | 3.57%   |
| HP ScanJet 3670                                         | 1         | 3.57%   |
| HP ScanJet 2200c                                        | 1         | 3.57%   |
| Canon CanoScan LiDE 70                                  | 1         | 3.57%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 3.57%   |
| Canon CanoScan LiDE 200                                 | 1         | 3.57%   |
| Canon CanoScan LiDE 110                                 | 1         | 3.57%   |
| Canon CanoScan 4200F                                    | 1         | 3.57%   |
| Canon CanoScan                                          | 1         | 3.57%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 474       | 19.65%  |
| Microdia                               | 247       | 10.24%  |
| Logitech                               | 222       | 9.2%    |
| IMC Networks                           | 191       | 7.92%   |
| Realtek Semiconductor                  | 170       | 7.05%   |
| Acer                                   | 163       | 6.76%   |
| Apple                                  | 145       | 6.01%   |
| Sunplus Innovation Technology          | 123       | 5.1%    |
| Suyin                                  | 84        | 3.48%   |
| Quanta                                 | 81        | 3.36%   |
| Microsoft                              | 64        | 2.65%   |
| Cheng Uei Precision Industry (Foxlink) | 54        | 2.24%   |
| Syntek                                 | 35        | 1.45%   |
| Lite-On Technology                     | 34        | 1.41%   |
| Samsung Electronics                    | 31        | 1.29%   |
| Ricoh                                  | 26        | 1.08%   |
| Silicon Motion                         | 24        | 1%      |
| Lenovo                                 | 23        | 0.95%   |
| Luxvisions Innotech Limited            | 22        | 0.91%   |
| Importek                               | 18        | 0.75%   |
| Z-Star Microelectronics                | 14        | 0.58%   |
| Alcor Micro                            | 14        | 0.58%   |
| AVerMedia Technologies                 | 13        | 0.54%   |
| MacroSilicon                           | 12        | 0.5%    |
| ALi                                    | 9         | 0.37%   |
| OmniVision Technologies                | 8         | 0.33%   |
| Primax Electronics                     | 7         | 0.29%   |
| LG Electronics                         | 7         | 0.29%   |
| Cubeternet                             | 6         | 0.25%   |
| Creative Technology                    | 6         | 0.25%   |
| Razer USA                              | 5         | 0.21%   |
| Huawei Technologies                    | 5         | 0.21%   |
| Hewlett-Packard                        | 5         | 0.21%   |
| Genesys Logic                          | 5         | 0.21%   |
| 2M UVC CAMERA                          | 5         | 0.21%   |
| Unknown                                | 4         | 0.17%   |
| Sonix Technology                       | 4         | 0.17%   |
| Generalplus Technology                 | 4         | 0.17%   |
| Valve Software                         | 3         | 0.12%   |
| Linux Foundation                       | 3         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony integrated camera                | 97        | 3.99%   |
| Microdia Integrated_Webcam_HD            | 89        | 3.66%   |
| Realtek Integrated_Webcam_HD             | 66        | 2.71%   |
| IMC Networks USB2.0 HD UVC WebCam        | 66        | 2.71%   |
| Apple Built-in iSight                    | 52        | 2.14%   |
| Logitech HD Pro Webcam C920              | 50        | 2.06%   |
| Acer Integrated Camera                   | 46        | 1.89%   |
| Chicony HD WebCam                        | 45        | 1.85%   |
| Logitech Webcam C270                     | 44        | 1.81%   |
| IMC Networks Integrated Camera           | 41        | 1.69%   |
| Apple iPhone 5/5C/5S/6/SE                | 40        | 1.64%   |
| Samsung Galaxy series, misc. (MTP mode)  | 31        | 1.27%   |
| Apple FaceTime HD Camera (Built-in)      | 30        | 1.23%   |
| Microdia Integrated Webcam               | 29        | 1.19%   |
| Sunplus Integrated_Webcam_HD             | 26        | 1.07%   |
| Syntek Integrated Camera                 | 25        | 1.03%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 22        | 0.9%    |
| Sunplus HD WebCam                        | 21        | 0.86%   |
| Microdia Webcam Vitade AF                | 21        | 0.86%   |
| Chicony VGA WebCam                       | 21        | 0.86%   |
| Acer Lenovo EasyCamera                   | 20        | 0.82%   |
| Microsoft LifeCam HD-3000                | 19        | 0.78%   |
| Apple FaceTime HD Camera                 | 19        | 0.78%   |
| Logitech C922 Pro Stream Webcam          | 18        | 0.74%   |
| Lite-On Integrated Camera                | 18        | 0.74%   |
| Chicony USB2.0 HD UVC WebCam             | 17        | 0.7%    |
| Chicony HP Truevision HD                 | 17        | 0.7%    |
| Acer HD Webcam                           | 17        | 0.7%    |
| Chicony USB 2.0 Camera                   | 16        | 0.66%   |
| Quanta VGA WebCam                        | 15        | 0.62%   |
| Quanta HP TrueVision HD Camera           | 15        | 0.62%   |
| Quanta HD User Facing                    | 14        | 0.58%   |
| Microdia Laptop_Integrated_Webcam_HD     | 14        | 0.58%   |
| Acer SunplusIT Integrated Camera         | 14        | 0.58%   |
| Chicony TOSHIBA Web Camera - HD          | 13        | 0.53%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 12        | 0.49%   |
| Realtek USB Camera                       | 12        | 0.49%   |
| Logitech Webcam C930e                    | 12        | 0.49%   |
| Logitech HD Webcam C615                  | 12        | 0.49%   |
| Chicony USB2.0 VGA UVC WebCam            | 12        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 164       | 37.19%  |
| Synaptics                  | 104       | 23.58%  |
| Shenzhen Goodix Technology | 43        | 9.75%   |
| Elan Microelectronics      | 31        | 7.03%   |
| Upek                       | 30        | 6.8%    |
| AuthenTec                  | 27        | 6.12%   |
| LighTuning Technology      | 20        | 4.54%   |
| STMicroelectronics         | 15        | 3.4%    |
| Samsung Electronics        | 2         | 0.45%   |
| Microsoft                  | 2         | 0.45%   |
| HOLTEK                     | 1         | 0.23%   |
| Focal-systems.Corp         | 1         | 0.23%   |
| Dell                       | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 40        | 9.07%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 29        | 6.58%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 29        | 6.58%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 27        | 6.12%   |
| Elan ELAN:Fingerprint                                                      | 25        | 5.67%   |
| Unknown                                                                    | 24        | 5.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 4.99%   |
| Shenzhen Goodix FingerPrint                                                | 22        | 4.99%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 3.85%   |
| Validity Sensors VFS491                                                    | 17        | 3.85%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 3.85%   |
| STMicroelectronics Fingerprint Reader                                      | 15        | 3.4%    |
| AuthenTec AES2810                                                          | 13        | 2.95%   |
| Synaptics  WBDI                                                            | 12        | 2.72%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 2.49%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 2.49%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 2.27%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 2.27%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 1.81%   |
| LighTuning EgisTec_ES603                                                   | 8         | 1.81%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.59%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 7         | 1.59%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.36%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 1.36%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.13%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.13%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.91%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 0.68%   |
| AuthenTec AES1600                                                          | 3         | 0.68%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.45%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.45%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.45%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.45%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.45%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.45%   |
| Microsoft Fingerprint Reader                                               | 2         | 0.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.23%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.23%   |
| Synaptics WBDI Device                                                      | 1         | 0.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 73        | 42.44%  |
| Alcor Micro               | 33        | 19.19%  |
| O2 Micro                  | 22        | 12.79%  |
| Upek                      | 21        | 12.21%  |
| Lenovo                    | 11        | 6.4%    |
| Gemalto (was Gemplus)     | 3         | 1.74%   |
| Yubico.com                | 2         | 1.16%   |
| SCM Microsystems          | 2         | 1.16%   |
| Aladdin Knowledge Systems | 2         | 1.16%   |
| In Focus Systems          | 1         | 0.58%   |
| Giesecke & Devrient       | 1         | 0.58%   |
| Clay Logic                | 1         | 0.58%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 40        | 23.26%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 31        | 18.02%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 21        | 12.21%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 19        | 11.05%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 9.88%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 6.4%    |
| Broadcom 5880                                                                | 10        | 5.81%   |
| Broadcom 58200                                                               | 5         | 2.91%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.74%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.74%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.16%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.16%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.58%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.58%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.58%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.58%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.58%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.58%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.58%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.58%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3247      | 71.92%  |
| 1     | 1018      | 22.55%  |
| 2     | 200       | 4.43%   |
| 3     | 32        | 0.71%   |
| 4     | 11        | 0.24%   |
| 5     | 4         | 0.09%   |
| 8     | 2         | 0.04%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 433       | 28.66%  |
| Graphics card            | 285       | 18.86%  |
| Net/wireless             | 229       | 15.16%  |
| Chipcard                 | 157       | 10.39%  |
| Communication controller | 89        | 5.89%   |
| Multimedia controller    | 78        | 5.16%   |
| Unassigned class         | 40        | 2.65%   |
| Bluetooth                | 32        | 2.12%   |
| Storage                  | 29        | 1.92%   |
| Sound                    | 29        | 1.92%   |
| Camera                   | 24        | 1.59%   |
| Net/ethernet             | 22        | 1.46%   |
| Network                  | 14        | 0.93%   |
| Modem                    | 11        | 0.73%   |
| Storage/ide              | 7         | 0.46%   |
| Storage/raid             | 6         | 0.4%    |
| Dvb card                 | 6         | 0.4%    |
| Card reader              | 6         | 0.4%    |
| Firewire controller      | 5         | 0.33%   |
| Flash memory             | 4         | 0.26%   |
| Tv card                  | 2         | 0.13%   |
| Video                    | 1         | 0.07%   |
| Unclassified device      | 1         | 0.07%   |
| Storage/nvme             | 1         | 0.07%   |

