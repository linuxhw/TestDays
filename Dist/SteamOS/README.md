SteamOS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for SteamOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/SteamOS/Desktop/README.md) and [notebooks](/Dist/SteamOS/Notebook/README.md).

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

Total: 531

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | Notebook    | [ec26a28bff](https://linux-hardware.org/?probe=ec26a28bff) | Dec 01, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [f00a357dbe](https://linux-hardware.org/?probe=f00a357dbe) | Nov 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [a9299c074e](https://linux-hardware.org/?probe=a9299c074e) | Nov 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [0f40429822](https://linux-hardware.org/?probe=0f40429822) | Nov 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [de1a950876](https://linux-hardware.org/?probe=de1a950876) | Nov 29, 2022 |
| MSI           | 970A-G46                    | Desktop     | [3cd88e88d3](https://linux-hardware.org/?probe=3cd88e88d3) | Nov 28, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [637e97b132](https://linux-hardware.org/?probe=637e97b132) | Nov 28, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [8263c8ba6f](https://linux-hardware.org/?probe=8263c8ba6f) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [f0d9943604](https://linux-hardware.org/?probe=f0d9943604) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [81b0ea6c7a](https://linux-hardware.org/?probe=81b0ea6c7a) | Nov 27, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [ee234d62ec](https://linux-hardware.org/?probe=ee234d62ec) | Nov 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [1d12c5839a](https://linux-hardware.org/?probe=1d12c5839a) | Nov 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [bee2852cb0](https://linux-hardware.org/?probe=bee2852cb0) | Nov 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [ea37f7d713](https://linux-hardware.org/?probe=ea37f7d713) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [caf4a9c4d8](https://linux-hardware.org/?probe=caf4a9c4d8) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [c17d27ef9b](https://linux-hardware.org/?probe=c17d27ef9b) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [0a172d85fd](https://linux-hardware.org/?probe=0a172d85fd) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [7412d8b03b](https://linux-hardware.org/?probe=7412d8b03b) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [24d078fe91](https://linux-hardware.org/?probe=24d078fe91) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [5751db0994](https://linux-hardware.org/?probe=5751db0994) | Nov 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [29f6c597e4](https://linux-hardware.org/?probe=29f6c597e4) | Nov 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [6049221fab](https://linux-hardware.org/?probe=6049221fab) | Nov 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c3a9fe5ae](https://linux-hardware.org/?probe=4c3a9fe5ae) | Nov 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [575ab984df](https://linux-hardware.org/?probe=575ab984df) | Nov 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e7b9730a4](https://linux-hardware.org/?probe=1e7b9730a4) | Nov 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9f2caddf6](https://linux-hardware.org/?probe=e9f2caddf6) | Nov 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [dd6f589d44](https://linux-hardware.org/?probe=dd6f589d44) | Nov 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [0e77de9dba](https://linux-hardware.org/?probe=0e77de9dba) | Nov 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c278b19567](https://linux-hardware.org/?probe=c278b19567) | Nov 20, 2022 |
| HP            | 8626                        | Desktop     | [f2098a2414](https://linux-hardware.org/?probe=f2098a2414) | Nov 19, 2022 |
| HP            | 8626                        | Desktop     | [05ebc14932](https://linux-hardware.org/?probe=05ebc14932) | Nov 19, 2022 |
| HP            | Pavilion 17                 | Notebook    | [1d4d49c9e4](https://linux-hardware.org/?probe=1d4d49c9e4) | Nov 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [c89535828a](https://linux-hardware.org/?probe=c89535828a) | Nov 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [5932954a14](https://linux-hardware.org/?probe=5932954a14) | Nov 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [d7c9c529b6](https://linux-hardware.org/?probe=d7c9c529b6) | Nov 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [d008ed40fe](https://linux-hardware.org/?probe=d008ed40fe) | Nov 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [01e0010535](https://linux-hardware.org/?probe=01e0010535) | Nov 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [4ab915f825](https://linux-hardware.org/?probe=4ab915f825) | Nov 15, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [48916ecbfa](https://linux-hardware.org/?probe=48916ecbfa) | Nov 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [92eb4009f3](https://linux-hardware.org/?probe=92eb4009f3) | Nov 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [0bd1833d8c](https://linux-hardware.org/?probe=0bd1833d8c) | Nov 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [f90da254ff](https://linux-hardware.org/?probe=f90da254ff) | Nov 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [0046f0e15d](https://linux-hardware.org/?probe=0046f0e15d) | Nov 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [649043bb19](https://linux-hardware.org/?probe=649043bb19) | Nov 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c1a39b012](https://linux-hardware.org/?probe=5c1a39b012) | Nov 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [62e925fd8a](https://linux-hardware.org/?probe=62e925fd8a) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [829b573205](https://linux-hardware.org/?probe=829b573205) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [ed3f6fb61d](https://linux-hardware.org/?probe=ed3f6fb61d) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [c1805091ef](https://linux-hardware.org/?probe=c1805091ef) | Nov 12, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [85ef5eaf43](https://linux-hardware.org/?probe=85ef5eaf43) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [54bca16c61](https://linux-hardware.org/?probe=54bca16c61) | Nov 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [34582d82a1](https://linux-hardware.org/?probe=34582d82a1) | Nov 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [6227fbbebb](https://linux-hardware.org/?probe=6227fbbebb) | Nov 10, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [2067c76d7b](https://linux-hardware.org/?probe=2067c76d7b) | Nov 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [340ef95fd9](https://linux-hardware.org/?probe=340ef95fd9) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [5673f6f505](https://linux-hardware.org/?probe=5673f6f505) | Nov 08, 2022 |
| Intel         | NUC8i7HVB J68196-503        | Mini pc     | [71a3658f21](https://linux-hardware.org/?probe=71a3658f21) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [020eadb15a](https://linux-hardware.org/?probe=020eadb15a) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3e3e947f9e](https://linux-hardware.org/?probe=3e3e947f9e) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [1991a35643](https://linux-hardware.org/?probe=1991a35643) | Nov 08, 2022 |
| GPD           | G1619-04                    | Notebook    | [0c0542ac2e](https://linux-hardware.org/?probe=0c0542ac2e) | Nov 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [88af410b70](https://linux-hardware.org/?probe=88af410b70) | Nov 07, 2022 |
| GPD           | G1619-04                    | Notebook    | [ce6d16840e](https://linux-hardware.org/?probe=ce6d16840e) | Nov 07, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [de347eb300](https://linux-hardware.org/?probe=de347eb300) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [695f4b6a83](https://linux-hardware.org/?probe=695f4b6a83) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [9e7987531b](https://linux-hardware.org/?probe=9e7987531b) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [2cc3a0b5de](https://linux-hardware.org/?probe=2cc3a0b5de) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [df94c19aa6](https://linux-hardware.org/?probe=df94c19aa6) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [55420be889](https://linux-hardware.org/?probe=55420be889) | Nov 05, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [a0b134897f](https://linux-hardware.org/?probe=a0b134897f) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [f23e197251](https://linux-hardware.org/?probe=f23e197251) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [946d382a37](https://linux-hardware.org/?probe=946d382a37) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c5b229108](https://linux-hardware.org/?probe=5c5b229108) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [62160ec2e5](https://linux-hardware.org/?probe=62160ec2e5) | Nov 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b4f9d04f4d](https://linux-hardware.org/?probe=b4f9d04f4d) | Nov 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [1757bc1f5a](https://linux-hardware.org/?probe=1757bc1f5a) | Nov 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [f6295954bc](https://linux-hardware.org/?probe=f6295954bc) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [13e280e72f](https://linux-hardware.org/?probe=13e280e72f) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [cf9998e9b9](https://linux-hardware.org/?probe=cf9998e9b9) | Nov 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [9d237f0d30](https://linux-hardware.org/?probe=9d237f0d30) | Oct 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [92b732ad9a](https://linux-hardware.org/?probe=92b732ad9a) | Oct 31, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [7712ce88c4](https://linux-hardware.org/?probe=7712ce88c4) | Oct 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4c562a178](https://linux-hardware.org/?probe=d4c562a178) | Oct 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d381c1626](https://linux-hardware.org/?probe=2d381c1626) | Oct 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [dfc3eee826](https://linux-hardware.org/?probe=dfc3eee826) | Oct 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [0405c29890](https://linux-hardware.org/?probe=0405c29890) | Oct 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [b4ba1b8d5a](https://linux-hardware.org/?probe=b4ba1b8d5a) | Oct 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [127bd00558](https://linux-hardware.org/?probe=127bd00558) | Oct 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [7cc988201b](https://linux-hardware.org/?probe=7cc988201b) | Oct 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [746fdbcdec](https://linux-hardware.org/?probe=746fdbcdec) | Oct 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [088235cbff](https://linux-hardware.org/?probe=088235cbff) | Oct 26, 2022 |
| Google        | Droid                       | Notebook    | [c8e4007ce4](https://linux-hardware.org/?probe=c8e4007ce4) | Oct 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [dc86de125e](https://linux-hardware.org/?probe=dc86de125e) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [98a9dbc46f](https://linux-hardware.org/?probe=98a9dbc46f) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [c12839567e](https://linux-hardware.org/?probe=c12839567e) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [6ed87cbcfb](https://linux-hardware.org/?probe=6ed87cbcfb) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [fe664e172e](https://linux-hardware.org/?probe=fe664e172e) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [1963771551](https://linux-hardware.org/?probe=1963771551) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [e474d0929b](https://linux-hardware.org/?probe=e474d0929b) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [6e4712d276](https://linux-hardware.org/?probe=6e4712d276) | Oct 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [719742423c](https://linux-hardware.org/?probe=719742423c) | Oct 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [3e696c2b87](https://linux-hardware.org/?probe=3e696c2b87) | Oct 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [b05efe341f](https://linux-hardware.org/?probe=b05efe341f) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [39c064d0df](https://linux-hardware.org/?probe=39c064d0df) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [302efb993a](https://linux-hardware.org/?probe=302efb993a) | Oct 22, 2022 |
| ADVANCE       | PS5077                      | Notebook    | [998e544711](https://linux-hardware.org/?probe=998e544711) | Oct 22, 2022 |
| ADVANCE       | PS5077                      | Notebook    | [97bfff0fc6](https://linux-hardware.org/?probe=97bfff0fc6) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [024fdc987b](https://linux-hardware.org/?probe=024fdc987b) | Oct 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [13c98e0adc](https://linux-hardware.org/?probe=13c98e0adc) | Oct 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [2582be110d](https://linux-hardware.org/?probe=2582be110d) | Oct 21, 2022 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [9485d1e744](https://linux-hardware.org/?probe=9485d1e744) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [6249475f24](https://linux-hardware.org/?probe=6249475f24) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [7cb825e738](https://linux-hardware.org/?probe=7cb825e738) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [ea0d3e9186](https://linux-hardware.org/?probe=ea0d3e9186) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [a314a908eb](https://linux-hardware.org/?probe=a314a908eb) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [53e7ae8cd4](https://linux-hardware.org/?probe=53e7ae8cd4) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [bdca0279e2](https://linux-hardware.org/?probe=bdca0279e2) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [3fada6964f](https://linux-hardware.org/?probe=3fada6964f) | Oct 19, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [59904b8a87](https://linux-hardware.org/?probe=59904b8a87) | Oct 19, 2022 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | Notebook    | [429cfdd3df](https://linux-hardware.org/?probe=429cfdd3df) | Oct 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e000a30c5](https://linux-hardware.org/?probe=1e000a30c5) | Oct 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [a52a79aad6](https://linux-hardware.org/?probe=a52a79aad6) | Oct 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [0a198cb541](https://linux-hardware.org/?probe=0a198cb541) | Oct 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [fb6fa1c746](https://linux-hardware.org/?probe=fb6fa1c746) | Oct 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c513b151b](https://linux-hardware.org/?probe=1c513b151b) | Oct 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [992d2b539a](https://linux-hardware.org/?probe=992d2b539a) | Oct 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [0526c93d55](https://linux-hardware.org/?probe=0526c93d55) | Oct 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [8a5f4671f1](https://linux-hardware.org/?probe=8a5f4671f1) | Oct 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [281229d9ba](https://linux-hardware.org/?probe=281229d9ba) | Oct 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [dde3144879](https://linux-hardware.org/?probe=dde3144879) | Oct 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [7559400f9a](https://linux-hardware.org/?probe=7559400f9a) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [022a7cab63](https://linux-hardware.org/?probe=022a7cab63) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [bd47ebea62](https://linux-hardware.org/?probe=bd47ebea62) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [627b9225cb](https://linux-hardware.org/?probe=627b9225cb) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9ed7280a28](https://linux-hardware.org/?probe=9ed7280a28) | Oct 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d38b191e7](https://linux-hardware.org/?probe=2d38b191e7) | Oct 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [e5f2c8aaae](https://linux-hardware.org/?probe=e5f2c8aaae) | Oct 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [261a0464f4](https://linux-hardware.org/?probe=261a0464f4) | Oct 14, 2022 |
| AZW           | MINI S                      | Notebook    | [d12969169f](https://linux-hardware.org/?probe=d12969169f) | Oct 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [cb0355ddf3](https://linux-hardware.org/?probe=cb0355ddf3) | Oct 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [ec6c38cc2e](https://linux-hardware.org/?probe=ec6c38cc2e) | Oct 13, 2022 |
| HP            | 8433 11                     | Desktop     | [fed45efc8d](https://linux-hardware.org/?probe=fed45efc8d) | Oct 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [62bdf474b3](https://linux-hardware.org/?probe=62bdf474b3) | Oct 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [6da0b199d1](https://linux-hardware.org/?probe=6da0b199d1) | Oct 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [c06c56de15](https://linux-hardware.org/?probe=c06c56de15) | Oct 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c324f424d](https://linux-hardware.org/?probe=4c324f424d) | Oct 10, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2e1db47b63](https://linux-hardware.org/?probe=2e1db47b63) | Oct 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [a5c71515b9](https://linux-hardware.org/?probe=a5c71515b9) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb5a512250](https://linux-hardware.org/?probe=eb5a512250) | Oct 09, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [9873ba1845](https://linux-hardware.org/?probe=9873ba1845) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [34b991043f](https://linux-hardware.org/?probe=34b991043f) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [c5c31bcc13](https://linux-hardware.org/?probe=c5c31bcc13) | Oct 08, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [f2b2df8e8c](https://linux-hardware.org/?probe=f2b2df8e8c) | Oct 08, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [b161e7fe73](https://linux-hardware.org/?probe=b161e7fe73) | Oct 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [30d44ab77b](https://linux-hardware.org/?probe=30d44ab77b) | Oct 08, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [4bea37497e](https://linux-hardware.org/?probe=4bea37497e) | Oct 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d8b46d523](https://linux-hardware.org/?probe=2d8b46d523) | Oct 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [e064c0c3be](https://linux-hardware.org/?probe=e064c0c3be) | Oct 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [ee7a8c8340](https://linux-hardware.org/?probe=ee7a8c8340) | Oct 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [1ebf39c097](https://linux-hardware.org/?probe=1ebf39c097) | Oct 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c1c51b96ef](https://linux-hardware.org/?probe=c1c51b96ef) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [8dcc3b36a0](https://linux-hardware.org/?probe=8dcc3b36a0) | Oct 06, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [2e6852099a](https://linux-hardware.org/?probe=2e6852099a) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [28900801aa](https://linux-hardware.org/?probe=28900801aa) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [9222d376ab](https://linux-hardware.org/?probe=9222d376ab) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [4905b59499](https://linux-hardware.org/?probe=4905b59499) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [64f5b28613](https://linux-hardware.org/?probe=64f5b28613) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [641bcdd8c5](https://linux-hardware.org/?probe=641bcdd8c5) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [2f421c5aa6](https://linux-hardware.org/?probe=2f421c5aa6) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [c1206634aa](https://linux-hardware.org/?probe=c1206634aa) | Oct 05, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [150cd334ca](https://linux-hardware.org/?probe=150cd334ca) | Oct 05, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [7ac647f707](https://linux-hardware.org/?probe=7ac647f707) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [ac2707d2e6](https://linux-hardware.org/?probe=ac2707d2e6) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [9dd9e70e1f](https://linux-hardware.org/?probe=9dd9e70e1f) | Oct 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [70f65d68fc](https://linux-hardware.org/?probe=70f65d68fc) | Oct 04, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [2163cddbe4](https://linux-hardware.org/?probe=2163cddbe4) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [aee559f8bf](https://linux-hardware.org/?probe=aee559f8bf) | Oct 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [4bc40da6ce](https://linux-hardware.org/?probe=4bc40da6ce) | Oct 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [047b9291b1](https://linux-hardware.org/?probe=047b9291b1) | Oct 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [6bc437ef3d](https://linux-hardware.org/?probe=6bc437ef3d) | Oct 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [c411f31824](https://linux-hardware.org/?probe=c411f31824) | Oct 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [e051d6a0a9](https://linux-hardware.org/?probe=e051d6a0a9) | Oct 02, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f5e8b6c1eb](https://linux-hardware.org/?probe=f5e8b6c1eb) | Oct 02, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [8e5a2bb3a6](https://linux-hardware.org/?probe=8e5a2bb3a6) | Oct 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [5692645981](https://linux-hardware.org/?probe=5692645981) | Oct 02, 2022 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [3e25da0356](https://linux-hardware.org/?probe=3e25da0356) | Oct 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [12f0d9358a](https://linux-hardware.org/?probe=12f0d9358a) | Oct 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [9ea6c15d28](https://linux-hardware.org/?probe=9ea6c15d28) | Oct 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [dab0a00c02](https://linux-hardware.org/?probe=dab0a00c02) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [4d1b722861](https://linux-hardware.org/?probe=4d1b722861) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9737fcadf](https://linux-hardware.org/?probe=e9737fcadf) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [5e7ec518d4](https://linux-hardware.org/?probe=5e7ec518d4) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [a031955ffb](https://linux-hardware.org/?probe=a031955ffb) | Sep 30, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [5746aa7609](https://linux-hardware.org/?probe=5746aa7609) | Sep 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [66731152dd](https://linux-hardware.org/?probe=66731152dd) | Sep 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [679b3600fa](https://linux-hardware.org/?probe=679b3600fa) | Sep 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [92b774ed77](https://linux-hardware.org/?probe=92b774ed77) | Sep 29, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [46e48bc4c1](https://linux-hardware.org/?probe=46e48bc4c1) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [bdc84f1b9b](https://linux-hardware.org/?probe=bdc84f1b9b) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| GPD           | G1619-04                    | Notebook    | [9e99ae15fb](https://linux-hardware.org/?probe=9e99ae15fb) | Sep 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [9a2af6352a](https://linux-hardware.org/?probe=9a2af6352a) | Sep 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [0f1c8fad1c](https://linux-hardware.org/?probe=0f1c8fad1c) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [c3305d9bff](https://linux-hardware.org/?probe=c3305d9bff) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [8c94cd9bd3](https://linux-hardware.org/?probe=8c94cd9bd3) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [ebf3e70cf7](https://linux-hardware.org/?probe=ebf3e70cf7) | Sep 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [315719a312](https://linux-hardware.org/?probe=315719a312) | Sep 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [f5183f3eed](https://linux-hardware.org/?probe=f5183f3eed) | Sep 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [6ddd668003](https://linux-hardware.org/?probe=6ddd668003) | Sep 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [b70be12594](https://linux-hardware.org/?probe=b70be12594) | Sep 24, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5d02471757](https://linux-hardware.org/?probe=5d02471757) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [d03b845c90](https://linux-hardware.org/?probe=d03b845c90) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ca6d2abcd9](https://linux-hardware.org/?probe=ca6d2abcd9) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [ce15d6d4bb](https://linux-hardware.org/?probe=ce15d6d4bb) | Sep 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [f9230d9e82](https://linux-hardware.org/?probe=f9230d9e82) | Sep 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [a39be03b34](https://linux-hardware.org/?probe=a39be03b34) | Sep 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [7bc45b1077](https://linux-hardware.org/?probe=7bc45b1077) | Sep 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [721ede2e11](https://linux-hardware.org/?probe=721ede2e11) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [83ed33f7e6](https://linux-hardware.org/?probe=83ed33f7e6) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [e60653a4c7](https://linux-hardware.org/?probe=e60653a4c7) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [090e33f643](https://linux-hardware.org/?probe=090e33f643) | Sep 20, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [8d8440548e](https://linux-hardware.org/?probe=8d8440548e) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [919ae4fe6c](https://linux-hardware.org/?probe=919ae4fe6c) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [5ed6e54010](https://linux-hardware.org/?probe=5ed6e54010) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [52352bab7a](https://linux-hardware.org/?probe=52352bab7a) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [84051314e8](https://linux-hardware.org/?probe=84051314e8) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [de74f87be5](https://linux-hardware.org/?probe=de74f87be5) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [8273135785](https://linux-hardware.org/?probe=8273135785) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [4b802a9fe9](https://linux-hardware.org/?probe=4b802a9fe9) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [e65c41605f](https://linux-hardware.org/?probe=e65c41605f) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [b2a1aea8e2](https://linux-hardware.org/?probe=b2a1aea8e2) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [b667f00856](https://linux-hardware.org/?probe=b667f00856) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [221fd3ae1c](https://linux-hardware.org/?probe=221fd3ae1c) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [c4dd2bf91f](https://linux-hardware.org/?probe=c4dd2bf91f) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [0db4b64dcd](https://linux-hardware.org/?probe=0db4b64dcd) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [4540c4e930](https://linux-hardware.org/?probe=4540c4e930) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [47ac328960](https://linux-hardware.org/?probe=47ac328960) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [28a40721a8](https://linux-hardware.org/?probe=28a40721a8) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [f686754b27](https://linux-hardware.org/?probe=f686754b27) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [9adc000021](https://linux-hardware.org/?probe=9adc000021) | Sep 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9493095ab1](https://linux-hardware.org/?probe=9493095ab1) | Sep 15, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [9919cebdfe](https://linux-hardware.org/?probe=9919cebdfe) | Sep 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9817414c4e](https://linux-hardware.org/?probe=9817414c4e) | Sep 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [0925a55100](https://linux-hardware.org/?probe=0925a55100) | Sep 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [b2b312e843](https://linux-hardware.org/?probe=b2b312e843) | Sep 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [694e9a60ad](https://linux-hardware.org/?probe=694e9a60ad) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [438ec3fe41](https://linux-hardware.org/?probe=438ec3fe41) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| MSI           | 970A-G46                    | Desktop     | [5f7482fe88](https://linux-hardware.org/?probe=5f7482fe88) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [1dc4620833](https://linux-hardware.org/?probe=1dc4620833) | Sep 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [2c95ed7c92](https://linux-hardware.org/?probe=2c95ed7c92) | Sep 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [17eea2b641](https://linux-hardware.org/?probe=17eea2b641) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [49694d92f6](https://linux-hardware.org/?probe=49694d92f6) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [48df4850fe](https://linux-hardware.org/?probe=48df4850fe) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [c63b3ff391](https://linux-hardware.org/?probe=c63b3ff391) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [cb5ede9c6f](https://linux-hardware.org/?probe=cb5ede9c6f) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [9fce9d23c8](https://linux-hardware.org/?probe=9fce9d23c8) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [7d45c49609](https://linux-hardware.org/?probe=7d45c49609) | Sep 08, 2022 |
| Microsoft     | Surface Pro 8               | Tablet      | [e450ddeea6](https://linux-hardware.org/?probe=e450ddeea6) | Sep 08, 2022 |
| ASUSTek       | ROG Zephyrus S17 GX703HS... | Notebook    | [041c6dac05](https://linux-hardware.org/?probe=041c6dac05) | Sep 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3c4865fc8c](https://linux-hardware.org/?probe=3c4865fc8c) | Sep 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [1669287cbb](https://linux-hardware.org/?probe=1669287cbb) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [47baad2eed](https://linux-hardware.org/?probe=47baad2eed) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb15307366](https://linux-hardware.org/?probe=eb15307366) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [8cd669599d](https://linux-hardware.org/?probe=8cd669599d) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [090d406ac3](https://linux-hardware.org/?probe=090d406ac3) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [3f0eb4cd71](https://linux-hardware.org/?probe=3f0eb4cd71) | Sep 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [04c7e44198](https://linux-hardware.org/?probe=04c7e44198) | Sep 05, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [fc14fdd03a](https://linux-hardware.org/?probe=fc14fdd03a) | Sep 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [584ea1ade0](https://linux-hardware.org/?probe=584ea1ade0) | Sep 05, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [2d99107aa6](https://linux-hardware.org/?probe=2d99107aa6) | Sep 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [bf34e42b02](https://linux-hardware.org/?probe=bf34e42b02) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [f9942c8a6b](https://linux-hardware.org/?probe=f9942c8a6b) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [93771f5a6b](https://linux-hardware.org/?probe=93771f5a6b) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [08728d3dc1](https://linux-hardware.org/?probe=08728d3dc1) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [a8038907ed](https://linux-hardware.org/?probe=a8038907ed) | Sep 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [f35ef3a2e1](https://linux-hardware.org/?probe=f35ef3a2e1) | Sep 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [e12248df34](https://linux-hardware.org/?probe=e12248df34) | Sep 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [ad3ce497e7](https://linux-hardware.org/?probe=ad3ce497e7) | Sep 02, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [f4142b2ff8](https://linux-hardware.org/?probe=f4142b2ff8) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [c0094f39c5](https://linux-hardware.org/?probe=c0094f39c5) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [b3b1ffd7ff](https://linux-hardware.org/?probe=b3b1ffd7ff) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [3fdc8df5b2](https://linux-hardware.org/?probe=3fdc8df5b2) | Sep 02, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bdae2c60cd](https://linux-hardware.org/?probe=bdae2c60cd) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [c89533e9a2](https://linux-hardware.org/?probe=c89533e9a2) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [c348c06118](https://linux-hardware.org/?probe=c348c06118) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [60db4bfa03](https://linux-hardware.org/?probe=60db4bfa03) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [5a2483051c](https://linux-hardware.org/?probe=5a2483051c) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b928ad313](https://linux-hardware.org/?probe=0b928ad313) | Aug 31, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1f4a6a9ec3](https://linux-hardware.org/?probe=1f4a6a9ec3) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [dbc549504c](https://linux-hardware.org/?probe=dbc549504c) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [1b38f48059](https://linux-hardware.org/?probe=1b38f48059) | Aug 30, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [6d2717b230](https://linux-hardware.org/?probe=6d2717b230) | Aug 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [40b9dd39a6](https://linux-hardware.org/?probe=40b9dd39a6) | Aug 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [ea6506cc93](https://linux-hardware.org/?probe=ea6506cc93) | Aug 30, 2022 |
| MSI           | MS-B9201                    | Desktop     | [b5c80c8c2c](https://linux-hardware.org/?probe=b5c80c8c2c) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [844a0c00e2](https://linux-hardware.org/?probe=844a0c00e2) | Aug 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [830c22afde](https://linux-hardware.org/?probe=830c22afde) | Aug 29, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [1763ee1dd0](https://linux-hardware.org/?probe=1763ee1dd0) | Aug 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [43ec7fb445](https://linux-hardware.org/?probe=43ec7fb445) | Aug 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [3848655fce](https://linux-hardware.org/?probe=3848655fce) | Aug 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [9e3df56c3b](https://linux-hardware.org/?probe=9e3df56c3b) | Aug 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [cd6744821b](https://linux-hardware.org/?probe=cd6744821b) | Aug 27, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [521dd85c98](https://linux-hardware.org/?probe=521dd85c98) | Aug 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [8027445785](https://linux-hardware.org/?probe=8027445785) | Aug 26, 2022 |
| Dell          | Precision 7720              | Notebook    | [7fafc0e50b](https://linux-hardware.org/?probe=7fafc0e50b) | Aug 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [447edaff49](https://linux-hardware.org/?probe=447edaff49) | Aug 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [67b791eb17](https://linux-hardware.org/?probe=67b791eb17) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [ebd183fc4b](https://linux-hardware.org/?probe=ebd183fc4b) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [b74760105e](https://linux-hardware.org/?probe=b74760105e) | Aug 25, 2022 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [663bc0a517](https://linux-hardware.org/?probe=663bc0a517) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [5064c9f57b](https://linux-hardware.org/?probe=5064c9f57b) | Aug 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [de49ccefa5](https://linux-hardware.org/?probe=de49ccefa5) | Aug 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c88b729d3](https://linux-hardware.org/?probe=4c88b729d3) | Aug 23, 2022 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [e934af2a60](https://linux-hardware.org/?probe=e934af2a60) | Aug 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ba1940016e](https://linux-hardware.org/?probe=ba1940016e) | Aug 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [161cc0c135](https://linux-hardware.org/?probe=161cc0c135) | Aug 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [078b8e8ff1](https://linux-hardware.org/?probe=078b8e8ff1) | Aug 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [04b0de9007](https://linux-hardware.org/?probe=04b0de9007) | Aug 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c25a3bf8a](https://linux-hardware.org/?probe=1c25a3bf8a) | Aug 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [bc83cf9f77](https://linux-hardware.org/?probe=bc83cf9f77) | Aug 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [36124147ef](https://linux-hardware.org/?probe=36124147ef) | Aug 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb63fecd35](https://linux-hardware.org/?probe=eb63fecd35) | Aug 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [d6b92d1aa0](https://linux-hardware.org/?probe=d6b92d1aa0) | Aug 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [bff4d1ca46](https://linux-hardware.org/?probe=bff4d1ca46) | Aug 19, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9661c799c9](https://linux-hardware.org/?probe=9661c799c9) | Aug 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [87f3603202](https://linux-hardware.org/?probe=87f3603202) | Aug 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [f0dc30e9f8](https://linux-hardware.org/?probe=f0dc30e9f8) | Aug 17, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [af4a593873](https://linux-hardware.org/?probe=af4a593873) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [c395a0f9db](https://linux-hardware.org/?probe=c395a0f9db) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [90ac03e747](https://linux-hardware.org/?probe=90ac03e747) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [53429d945b](https://linux-hardware.org/?probe=53429d945b) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9ab7a2b695](https://linux-hardware.org/?probe=9ab7a2b695) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [2adcfce1c0](https://linux-hardware.org/?probe=2adcfce1c0) | Aug 14, 2022 |
| MSI           | MS-B9351                    | Desktop     | [a5b1950761](https://linux-hardware.org/?probe=a5b1950761) | Aug 14, 2022 |
| MSI           | MS-B9351                    | Desktop     | [fbf08d2d76](https://linux-hardware.org/?probe=fbf08d2d76) | Aug 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9f1f10a4c](https://linux-hardware.org/?probe=e9f1f10a4c) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dcd9be004c](https://linux-hardware.org/?probe=dcd9be004c) | Aug 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [50596cb93b](https://linux-hardware.org/?probe=50596cb93b) | Aug 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [54ea6926a0](https://linux-hardware.org/?probe=54ea6926a0) | Aug 13, 2022 |
| HP            | 2B3E                        | All in one  | [1ba4759f2c](https://linux-hardware.org/?probe=1ba4759f2c) | Aug 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [3a1e95f5d5](https://linux-hardware.org/?probe=3a1e95f5d5) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [b63f9aedab](https://linux-hardware.org/?probe=b63f9aedab) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [822737452b](https://linux-hardware.org/?probe=822737452b) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [9839802d27](https://linux-hardware.org/?probe=9839802d27) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [6b9bfad898](https://linux-hardware.org/?probe=6b9bfad898) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [c6e02c54e7](https://linux-hardware.org/?probe=c6e02c54e7) | Aug 11, 2022 |
| HP            | Laptop 14z-fq0000           | Notebook    | [9c62f8d392](https://linux-hardware.org/?probe=9c62f8d392) | Aug 11, 2022 |
| Microsoft     | Surface Pro 8               | Tablet      | [a5f743f641](https://linux-hardware.org/?probe=a5f743f641) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [90e751b5cf](https://linux-hardware.org/?probe=90e751b5cf) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [6223a43fe2](https://linux-hardware.org/?probe=6223a43fe2) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [2cec170e55](https://linux-hardware.org/?probe=2cec170e55) | Aug 10, 2022 |
| AMI           | Unknown                     | Notebook    | [5cee81ed21](https://linux-hardware.org/?probe=5cee81ed21) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [68214f1af2](https://linux-hardware.org/?probe=68214f1af2) | Aug 10, 2022 |
| AMI           | Unknown                     | Notebook    | [7752037bab](https://linux-hardware.org/?probe=7752037bab) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [e4914b879a](https://linux-hardware.org/?probe=e4914b879a) | Aug 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [a5b1208abc](https://linux-hardware.org/?probe=a5b1208abc) | Aug 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [a50e78265a](https://linux-hardware.org/?probe=a50e78265a) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8ef9609a7](https://linux-hardware.org/?probe=d8ef9609a7) | Aug 07, 2022 |
| Dell          | 00F82W A00                  | Desktop     | [8e74c57731](https://linux-hardware.org/?probe=8e74c57731) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [64a0d92417](https://linux-hardware.org/?probe=64a0d92417) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [b6c7ee76fa](https://linux-hardware.org/?probe=b6c7ee76fa) | Aug 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [6bbc4f3d0a](https://linux-hardware.org/?probe=6bbc4f3d0a) | Aug 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [d15c62e29a](https://linux-hardware.org/?probe=d15c62e29a) | Aug 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [6f76f9d91a](https://linux-hardware.org/?probe=6f76f9d91a) | Aug 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [4403a80bdc](https://linux-hardware.org/?probe=4403a80bdc) | Aug 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [8689254ee7](https://linux-hardware.org/?probe=8689254ee7) | Aug 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [bfddbf1d22](https://linux-hardware.org/?probe=bfddbf1d22) | Aug 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [fdb514a999](https://linux-hardware.org/?probe=fdb514a999) | Aug 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [e4c6300b68](https://linux-hardware.org/?probe=e4c6300b68) | Aug 01, 2022 |
| Gigabyte      | H310M S2V                   | Desktop     | [329d2071a9](https://linux-hardware.org/?probe=329d2071a9) | Aug 01, 2022 |
| GPD           | G1619-02                    | Notebook    | [c61c4280c8](https://linux-hardware.org/?probe=c61c4280c8) | Jul 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [ee3b662083](https://linux-hardware.org/?probe=ee3b662083) | Jul 30, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [9a18d7476f](https://linux-hardware.org/?probe=9a18d7476f) | Jul 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [225e2c825e](https://linux-hardware.org/?probe=225e2c825e) | Jul 29, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [4a6c9ef157](https://linux-hardware.org/?probe=4a6c9ef157) | Jul 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [dffaa71aed](https://linux-hardware.org/?probe=dffaa71aed) | Jul 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [35608b206c](https://linux-hardware.org/?probe=35608b206c) | Jul 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [e35fa6e699](https://linux-hardware.org/?probe=e35fa6e699) | Jul 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [f43cbe28e9](https://linux-hardware.org/?probe=f43cbe28e9) | Jul 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4e4413f9b](https://linux-hardware.org/?probe=d4e4413f9b) | Jul 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [9c34e91c79](https://linux-hardware.org/?probe=9c34e91c79) | Jul 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [b605f923c6](https://linux-hardware.org/?probe=b605f923c6) | Jul 25, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [6b300beb70](https://linux-hardware.org/?probe=6b300beb70) | Jul 25, 2022 |
| ASRock        | A520M-ITX/ac                | Desktop     | [876c779461](https://linux-hardware.org/?probe=876c779461) | Jul 25, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [ce14e41b96](https://linux-hardware.org/?probe=ce14e41b96) | Jul 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [3e7b7cb8cd](https://linux-hardware.org/?probe=3e7b7cb8cd) | Jul 23, 2022 |
| Alienware     | m17                         | Notebook    | [e14db26b9b](https://linux-hardware.org/?probe=e14db26b9b) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ca07489d53](https://linux-hardware.org/?probe=ca07489d53) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d0db23de3](https://linux-hardware.org/?probe=2d0db23de3) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [4aece18875](https://linux-hardware.org/?probe=4aece18875) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [44dca72cbb](https://linux-hardware.org/?probe=44dca72cbb) | Jul 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [96af389676](https://linux-hardware.org/?probe=96af389676) | Jul 22, 2022 |
| ASRock        | X570 Extreme4 WiFi ax       | Notebook    | [bc52038c74](https://linux-hardware.org/?probe=bc52038c74) | Jul 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [0cd166bdb1](https://linux-hardware.org/?probe=0cd166bdb1) | Jul 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [02c47a57e5](https://linux-hardware.org/?probe=02c47a57e5) | Jul 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [2c1ad04467](https://linux-hardware.org/?probe=2c1ad04467) | Jul 18, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [7f27efe00e](https://linux-hardware.org/?probe=7f27efe00e) | Jul 17, 2022 |
| HP            | Pavilion 17                 | Notebook    | [722f4eb4a9](https://linux-hardware.org/?probe=722f4eb4a9) | Jul 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [b639365efd](https://linux-hardware.org/?probe=b639365efd) | Jul 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [eec9897935](https://linux-hardware.org/?probe=eec9897935) | Jul 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4be0d94b4](https://linux-hardware.org/?probe=d4be0d94b4) | Jul 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [d2f117e7f3](https://linux-hardware.org/?probe=d2f117e7f3) | Jul 14, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [e157e6d524](https://linux-hardware.org/?probe=e157e6d524) | Jul 14, 2022 |
| AYANEO        | NEXT Pro                    | Tablet      | [12b2ede47c](https://linux-hardware.org/?probe=12b2ede47c) | Jul 12, 2022 |
| AYANEO        | NEXT Pro                    | Tablet      | [4dc9fd4b9e](https://linux-hardware.org/?probe=4dc9fd4b9e) | Jul 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [f7d66c8d35](https://linux-hardware.org/?probe=f7d66c8d35) | Jul 10, 2022 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [2f3e59dc30](https://linux-hardware.org/?probe=2f3e59dc30) | Jul 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [0c2ea27c49](https://linux-hardware.org/?probe=0c2ea27c49) | Jul 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [98711d54c1](https://linux-hardware.org/?probe=98711d54c1) | Jul 08, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [c3c73948f5](https://linux-hardware.org/?probe=c3c73948f5) | Jul 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3ede093138](https://linux-hardware.org/?probe=3ede093138) | Jul 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [663562cc6b](https://linux-hardware.org/?probe=663562cc6b) | Jul 06, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [61eaf99aca](https://linux-hardware.org/?probe=61eaf99aca) | Jul 05, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [812733dd89](https://linux-hardware.org/?probe=812733dd89) | Jul 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [e640bab55c](https://linux-hardware.org/?probe=e640bab55c) | Jul 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [0bd46afcda](https://linux-hardware.org/?probe=0bd46afcda) | Jul 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [ac0c161f66](https://linux-hardware.org/?probe=ac0c161f66) | Jul 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [c591d23b4d](https://linux-hardware.org/?probe=c591d23b4d) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d82f88e20c](https://linux-hardware.org/?probe=d82f88e20c) | Jul 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [261590e542](https://linux-hardware.org/?probe=261590e542) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [7c233f0a07](https://linux-hardware.org/?probe=7c233f0a07) | Jun 29, 2022 |
| HP            | x2 210 G2                   | Tablet      | [812530aed8](https://linux-hardware.org/?probe=812530aed8) | Jun 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [e80815c8d4](https://linux-hardware.org/?probe=e80815c8d4) | Jun 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [65e5ab29fd](https://linux-hardware.org/?probe=65e5ab29fd) | Jun 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [e51f5d8645](https://linux-hardware.org/?probe=e51f5d8645) | Jun 26, 2022 |
| Alienware     | 02XRCM A01                  | Desktop     | [c70647bab0](https://linux-hardware.org/?probe=c70647bab0) | Jun 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [b4dd19f939](https://linux-hardware.org/?probe=b4dd19f939) | Jun 25, 2022 |
| AZW           | SER V01                     | Mini pc     | [295a32d26e](https://linux-hardware.org/?probe=295a32d26e) | Jun 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [c9ed3cf311](https://linux-hardware.org/?probe=c9ed3cf311) | Jun 23, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [1a568c2e5f](https://linux-hardware.org/?probe=1a568c2e5f) | Jun 23, 2022 |
| ASUSTek       | Q524UQK                     | Convertible | [fd5f128747](https://linux-hardware.org/?probe=fd5f128747) | Jun 23, 2022 |
| Dell          | G15 5510                    | Notebook    | [9c5777f505](https://linux-hardware.org/?probe=9c5777f505) | Jun 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [213fbe4dd2](https://linux-hardware.org/?probe=213fbe4dd2) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [262a7f0cd4](https://linux-hardware.org/?probe=262a7f0cd4) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [f8722866b2](https://linux-hardware.org/?probe=f8722866b2) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [aa18022bce](https://linux-hardware.org/?probe=aa18022bce) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [000682313d](https://linux-hardware.org/?probe=000682313d) | Jun 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [363ab9e4ea](https://linux-hardware.org/?probe=363ab9e4ea) | Jun 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [dd5765a418](https://linux-hardware.org/?probe=dd5765a418) | Jun 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [8e293bb4b1](https://linux-hardware.org/?probe=8e293bb4b1) | Jun 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [ff0ce08944](https://linux-hardware.org/?probe=ff0ce08944) | Jun 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [68a581ae0b](https://linux-hardware.org/?probe=68a581ae0b) | Jun 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [df3f1b5d8f](https://linux-hardware.org/?probe=df3f1b5d8f) | Jun 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [17406c8741](https://linux-hardware.org/?probe=17406c8741) | Jun 11, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [7ccfe2d3a7](https://linux-hardware.org/?probe=7ccfe2d3a7) | Jun 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [715e914cba](https://linux-hardware.org/?probe=715e914cba) | Jun 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [2fb1bfad12](https://linux-hardware.org/?probe=2fb1bfad12) | Jun 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [322bdc2ce3](https://linux-hardware.org/?probe=322bdc2ce3) | Jun 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [780d6b923a](https://linux-hardware.org/?probe=780d6b923a) | Jun 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b3a08001ed](https://linux-hardware.org/?probe=b3a08001ed) | Jun 01, 2022 |
| ASRock        | B550 PG Velocita            | Desktop     | [0d7f71a24d](https://linux-hardware.org/?probe=0d7f71a24d) | May 30, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [e415de106f](https://linux-hardware.org/?probe=e415de106f) | May 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [0af4b9c805](https://linux-hardware.org/?probe=0af4b9c805) | May 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [06b56d54d4](https://linux-hardware.org/?probe=06b56d54d4) | May 28, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [31f246f96e](https://linux-hardware.org/?probe=31f246f96e) | May 27, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [1d381d6ec9](https://linux-hardware.org/?probe=1d381d6ec9) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e966da4f8](https://linux-hardware.org/?probe=1e966da4f8) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [c716690aa2](https://linux-hardware.org/?probe=c716690aa2) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [43f315aa0c](https://linux-hardware.org/?probe=43f315aa0c) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [d4bef1e450](https://linux-hardware.org/?probe=d4bef1e450) | May 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b672eefb50](https://linux-hardware.org/?probe=b672eefb50) | May 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [dee0bbedd1](https://linux-hardware.org/?probe=dee0bbedd1) | May 25, 2022 |
| HP            | 8158 A01                    | Mini pc     | [0d32a2b2e3](https://linux-hardware.org/?probe=0d32a2b2e3) | May 24, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [da9b5c2be2](https://linux-hardware.org/?probe=da9b5c2be2) | May 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [c34173715a](https://linux-hardware.org/?probe=c34173715a) | May 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [6ca95b630c](https://linux-hardware.org/?probe=6ca95b630c) | May 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [7d3f9c0a5f](https://linux-hardware.org/?probe=7d3f9c0a5f) | May 23, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [b5d37bf4f2](https://linux-hardware.org/?probe=b5d37bf4f2) | May 22, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [fc970670a8](https://linux-hardware.org/?probe=fc970670a8) | May 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [595b06f6c9](https://linux-hardware.org/?probe=595b06f6c9) | May 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [d706d00651](https://linux-hardware.org/?probe=d706d00651) | May 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [317e492fa3](https://linux-hardware.org/?probe=317e492fa3) | May 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [79f6db1d69](https://linux-hardware.org/?probe=79f6db1d69) | May 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [771539d18d](https://linux-hardware.org/?probe=771539d18d) | May 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c826aed5e](https://linux-hardware.org/?probe=1c826aed5e) | Apr 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c43342014](https://linux-hardware.org/?probe=4c43342014) | Apr 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [8564bded7f](https://linux-hardware.org/?probe=8564bded7f) | Apr 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [d761657c3a](https://linux-hardware.org/?probe=d761657c3a) | Apr 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [f2e59fcb97](https://linux-hardware.org/?probe=f2e59fcb97) | Apr 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [4f23fab4fd](https://linux-hardware.org/?probe=4f23fab4fd) | Apr 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [ed07e93435](https://linux-hardware.org/?probe=ed07e93435) | Apr 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [48aacdeee8](https://linux-hardware.org/?probe=48aacdeee8) | Apr 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [6a042646dd](https://linux-hardware.org/?probe=6a042646dd) | Apr 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4c9dba2a1](https://linux-hardware.org/?probe=d4c9dba2a1) | Apr 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [852b6fb53a](https://linux-hardware.org/?probe=852b6fb53a) | Apr 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [6129b15fb5](https://linux-hardware.org/?probe=6129b15fb5) | Apr 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [ec05067a1d](https://linux-hardware.org/?probe=ec05067a1d) | Apr 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [180c84c856](https://linux-hardware.org/?probe=180c84c856) | Apr 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8625616de](https://linux-hardware.org/?probe=d8625616de) | Mar 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [d181a912af](https://linux-hardware.org/?probe=d181a912af) | Mar 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b6a21cf35](https://linux-hardware.org/?probe=0b6a21cf35) | Mar 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [85328e8f3d](https://linux-hardware.org/?probe=85328e8f3d) | Mar 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [023aea75e1](https://linux-hardware.org/?probe=023aea75e1) | Mar 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [c7f6388908](https://linux-hardware.org/?probe=c7f6388908) | Mar 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/SteamOS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| SteamOS 3.3.1                | 107       | 23.83%  |
| SteamOS 3.3.2                | 94        | 20.94%  |
| SteamOS 3.3                  | 87        | 19.38%  |
| SteamOS 3.2                  | 59        | 13.14%  |
| SteamOS 3.4                  | 32        | 7.13%   |
| SteamOS Snapshot             | 26        | 5.79%   |
| SteamOS 3.2 (steamdeck-main) | 14        | 3.12%   |
| SteamOS 3.1                  | 11        | 2.45%   |
| SteamOS                      | 9         | 2%      |
| SteamOS Rolling              | 8         | 1.78%   |
| SteamOS 3.5                  | 2         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SteamOS | 431       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                            | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| 5.13.0-valve21.1-1-neptune-02211-gc54cda5a36f3     | 110       | 24.39%  |
| 5.13.0-valve21.3-1-neptune                         | 101       | 22.39%  |
| 5.13.0-valve15-1-neptune-02197-gf6ec7ad3762a       | 54        | 11.97%  |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 36        | 7.98%   |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 31        | 6.87%   |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 24        | 5.32%   |
| 5.13.0-valve10.1-1-neptune-02144-g7fffaf925dfb     | 16        | 3.55%   |
| 5.13.0-valve10.3-1-neptune-02176-g5fe416c4acd8     | 13        | 2.88%   |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 12        | 2.66%   |
| 5.13.0-valve31-1-neptune                           | 11        | 2.44%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 9         | 2%      |
| 5.13.0-valve24-1-neptune                           | 7         | 1.55%   |
| 5.13.0-valve21.2-1-neptune                         | 6         | 1.33%   |
| 5.13.0-valve14-1-neptune-02195-g5b0f749d00fa       | 5         | 1.11%   |
| 5.13.0-valve20-1-neptune-02207-gbd986a7e1c7f       | 4         | 0.89%   |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 3         | 0.67%   |
| 5.15.60-1-lts                                      | 2         | 0.44%   |
| 5.15.54-1-lts                                      | 2         | 0.44%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2         | 0.44%   |
| 6.0.7-zen3-xanmod1-1                               | 1         | 0.22%   |
| 5.16.2-arch1-1                                     | 1         | 0.22%   |
| 5.15.79-1-lts                                      | 1         | 0.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 418       | 96.31%  |
| 5.18.1  | 9         | 2.07%   |
| 5.15.60 | 2         | 0.46%   |
| 5.15.54 | 2         | 0.46%   |
| 6.0.7   | 1         | 0.23%   |
| 5.16.2  | 1         | 0.23%   |
| 5.15.79 | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 418       | 96.31%  |
| 5.18    | 9         | 2.07%   |
| 5.15    | 5         | 1.15%   |
| 6.0     | 1         | 0.23%   |
| 5.16    | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 431       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| KDE5      | 426       | 98.61%  |
| Unknown   | 3         | 0.69%   |
| gamescope | 2         | 0.46%   |
| GNOME     | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 425       | 98.38%  |
| Wayland | 3         | 0.69%   |
| Tty     | 2         | 0.46%   |
| Unknown | 2         | 0.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 424       | 98.38%  |
| SDDM    | 7         | 1.62%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| en_US        | 368       | 85.19%  |
| en_GB        | 10        | 2.31%   |
| fr_FR        | 9         | 2.08%   |
| de_DE        | 9         | 2.08%   |
| en_DE        | 5         | 1.16%   |
| an_ES        | 5         | 1.16%   |
| zh_CN        | 3         | 0.69%   |
| pt_PT        | 2         | 0.46%   |
| es_ES        | 2         | 0.46%   |
| en_NL        | 2         | 0.46%   |
| sk_SK        | 1         | 0.23%   |
| ru_RU        | 1         | 0.23%   |
| pt_BR        | 1         | 0.23%   |
| pl_PL        | 1         | 0.23%   |
| nl_NL        | 1         | 0.23%   |
| it_IT        | 1         | 0.23%   |
| hr_HR        | 1         | 0.23%   |
| fr_BE        | 1         | 0.23%   |
| et_EE        | 1         | 0.23%   |
| en_SE        | 1         | 0.23%   |
| en_IE        | 1         | 0.23%   |
| en_HK        | 1         | 0.23%   |
| en_GB.UTF-12 | 1         | 0.23%   |
| en_CA        | 1         | 0.23%   |
| de_AT        | 1         | 0.23%   |
| C            | 1         | 0.23%   |
| ba_RU        | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 421       | 97.68%  |
| EFI  | 10        | 2.32%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 430       | 99.77%  |
| Ext4  | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 421       | 97.45%  |
| GPT     | 11        | 2.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 425       | 98.61%  |
| Yes       | 6         | 1.39%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 429       | 99.54%  |
| Yes       | 2         | 0.46%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Valve                  | 333       | 77.26%  |
| ASUSTek Computer       | 17        | 3.94%   |
| Gigabyte Technology    | 13        | 3.02%   |
| Hewlett-Packard        | 11        | 2.55%   |
| Lenovo                 | 9         | 2.09%   |
| MSI                    | 8         | 1.86%   |
| Dell                   | 6         | 1.39%   |
| ASRock                 | 6         | 1.39%   |
| Apple                  | 6         | 1.39%   |
| GPD                    | 4         | 0.93%   |
| AOKZOE                 | 3         | 0.7%    |
| AZW                    | 2         | 0.46%   |
| Alienware              | 2         | 0.46%   |
| Acer                   | 2         | 0.46%   |
| Samsung Electronics    | 1         | 0.23%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.23%   |
| Microsoft              | 1         | 0.23%   |
| Intel                  | 1         | 0.23%   |
| Google                 | 1         | 0.23%   |
| AYANEO                 | 1         | 0.23%   |
| AMI                    | 1         | 0.23%   |
| ADVANCE                | 1         | 0.23%   |
| Unknown                | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Valve Jupiter                          | 333       | 77.26%  |
| GPD G1619-04                           | 3         | 0.7%    |
| ASUS All Series                        | 3         | 0.7%    |
| AOKZOE A1 AR07                         | 3         | 0.7%    |
| HP Pavilion 17                         | 2         | 0.46%   |
| Gigabyte B450 AORUS M                  | 2         | 0.46%   |
| ASUS ROG STRIX B550-F GAMING           | 2         | 0.46%   |
| Unknown                                | 2         | 0.46%   |
| Samsung 950XDB/951XDB/950XDY           | 1         | 0.23%   |
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER     | 1         | 0.23%   |
| MSI MS-7C02                            | 1         | 0.23%   |
| MSI MS-7B79                            | 1         | 0.23%   |
| MSI MS-7B09                            | 1         | 0.23%   |
| MSI MS-7A33                            | 1         | 0.23%   |
| MSI MS-7693                            | 1         | 0.23%   |
| MSI MPG H510 Trident 3 (MS-B935)       | 1         | 0.23%   |
| MSI H310 Gaming Trident3 (MS-B920)     | 1         | 0.23%   |
| MSI GP66 Leopard 11UH                  | 1         | 0.23%   |
| Microsoft Surface Pro 8                | 1         | 0.23%   |
| Lenovo ThinkCentre M920x 10S2S00V00    | 1         | 0.23%   |
| Lenovo ThinkCentre M720q 10T700A9UK    | 1         | 0.23%   |
| Lenovo ThinkCentre M720q 10T7002CUS    | 1         | 0.23%   |
| Lenovo ThinkBook 13s G3 ACN 20YA       | 1         | 0.23%   |
| Lenovo Legion Y740-15IRHg 81UH         | 1         | 0.23%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 0.23%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 0.23%   |
| Lenovo IdeaPad 3 15ITL6 82H8           | 1         | 0.23%   |
| Lenovo IdeaPad 1 14IAU7 82QC           | 1         | 0.23%   |
| Intel NUC8i7HVK                        | 1         | 0.23%   |
| HP x2 210 G2                           | 1         | 0.23%   |
| HP t630 Thin Client                    | 1         | 0.23%   |
| HP ProDesk 405 G4 Desktop Mini         | 1         | 0.23%   |
| HP Pavilion x360 Convertible 14-dy0xxx | 1         | 0.23%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 1         | 0.23%   |
| HP Pavilion Gaming Laptop 15-dk0xxx    | 1         | 0.23%   |
| HP Pavilion Gaming Desktop 690-00xx    | 1         | 0.23%   |
| HP Laptop 14z-fq0000                   | 1         | 0.23%   |
| HP 27-p055na                           | 1         | 0.23%   |
| GPD G1619-02                           | 1         | 0.23%   |
| Google Droid                           | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Valve Jupiter              | 333       | 77.26%  |
| HP Pavilion                | 6         | 1.39%   |
| ASUS ROG                   | 4         | 0.93%   |
| Lenovo ThinkCentre         | 3         | 0.7%    |
| Lenovo IdeaPad             | 3         | 0.7%    |
| GPD G1619-04               | 3         | 0.7%    |
| ASUS PRIME                 | 3         | 0.7%    |
| ASUS All                   | 3         | 0.7%    |
| AOKZOE A1                  | 3         | 0.7%    |
| Gigabyte X570              | 2         | 0.46%   |
| Gigabyte B450M             | 2         | 0.46%   |
| Gigabyte B450              | 2         | 0.46%   |
| Dell XPS                   | 2         | 0.46%   |
| Dell Precision             | 2         | 0.46%   |
| ASRock X570                | 2         | 0.46%   |
| Apple MacBookAir6          | 2         | 0.46%   |
| Acer Aspire                | 2         | 0.46%   |
| Unknown                    | 2         | 0.46%   |
| Samsung 950XDB             | 1         | 0.23%   |
| ONE-NETBOOK TECHNOLOGY ONE | 1         | 0.23%   |
| MSI MS-7C02                | 1         | 0.23%   |
| MSI MS-7B79                | 1         | 0.23%   |
| MSI MS-7B09                | 1         | 0.23%   |
| MSI MS-7A33                | 1         | 0.23%   |
| MSI MS-7693                | 1         | 0.23%   |
| MSI MPG                    | 1         | 0.23%   |
| MSI H310                   | 1         | 0.23%   |
| MSI GP66                   | 1         | 0.23%   |
| Microsoft Surface          | 1         | 0.23%   |
| Lenovo ThinkBook           | 1         | 0.23%   |
| Lenovo Legion              | 1         | 0.23%   |
| Lenovo IdeaPadFlex         | 1         | 0.23%   |
| Intel NUC8i7HVK            | 1         | 0.23%   |
| HP x2                      | 1         | 0.23%   |
| HP t630                    | 1         | 0.23%   |
| HP ProDesk                 | 1         | 0.23%   |
| HP Laptop                  | 1         | 0.23%   |
| HP 27-p055na               | 1         | 0.23%   |
| GPD G1619-02               | 1         | 0.23%   |
| Google Droid               | 1         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 334       | 77.49%  |
| 2021    | 22        | 5.1%    |
| 2020    | 13        | 3.02%   |
| 2019    | 12        | 2.78%   |
| Unknown | 12        | 2.78%   |
| 2018    | 10        | 2.32%   |
| 2016    | 8         | 1.86%   |
| 2017    | 7         | 1.62%   |
| 2013    | 6         | 1.39%   |
| 2015    | 2         | 0.46%   |
| 2014    | 2         | 0.46%   |
| 2012    | 2         | 0.46%   |
| 2011    | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 367       | 85.15%  |
| Desktop     | 44        | 10.21%  |
| Mini pc     | 8         | 1.86%   |
| Tablet      | 7         | 1.62%   |
| Convertible | 3         | 0.7%    |
| All in one  | 2         | 0.46%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 431       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 430       | 99.77%  |
| Yes  | 1         | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 352       | 81.67%  |
| 16.01-24.0  | 35        | 8.12%   |
| 4.01-8.0    | 16        | 3.71%   |
| 32.01-64.0  | 12        | 2.78%   |
| 24.01-32.0  | 8         | 1.86%   |
| 3.01-4.0    | 4         | 0.93%   |
| 64.01-256.0 | 4         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 228       | 51.35%  |
| 3.01-4.0  | 102       | 22.97%  |
| 4.01-8.0  | 60        | 13.51%  |
| 1.01-2.0  | 53        | 11.94%  |
| 8.01-16.0 | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 248       | 56.75%  |
| 1      | 157       | 35.93%  |
| 3      | 18        | 4.12%   |
| 4      | 6         | 1.37%   |
| 5      | 3         | 0.69%   |
| 0      | 2         | 0.46%   |
| 11     | 1         | 0.23%   |
| 7      | 1         | 0.23%   |
| 6      | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 417       | 96.75%  |
| Yes       | 14        | 3.25%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 265       | 60.78%  |
| Yes       | 171       | 39.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 413       | 95.82%  |
| No        | 18        | 4.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 398       | 92.13%  |
| No        | 34        | 7.87%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 192       | 44.55%  |
| UK          | 54        | 12.53%  |
| Germany     | 40        | 9.28%   |
| Canada      | 20        | 4.64%   |
| France      | 16        | 3.71%   |
| Spain       | 14        | 3.25%   |
| Netherlands | 11        | 2.55%   |
| Poland      | 9         | 2.09%   |
| China       | 6         | 1.39%   |
| Austria     | 6         | 1.39%   |
| Romania     | 5         | 1.16%   |
| Russia      | 4         | 0.93%   |
| Italy       | 4         | 0.93%   |
| Australia   | 4         | 0.93%   |
| Sweden      | 3         | 0.7%    |
| Hong Kong   | 3         | 0.7%    |
| Czechia     | 3         | 0.7%    |
| Brazil      | 3         | 0.7%    |
| Slovakia    | 2         | 0.46%   |
| Portugal    | 2         | 0.46%   |
| Oman        | 2         | 0.46%   |
| Moldova     | 2         | 0.46%   |
| Latvia      | 2         | 0.46%   |
| Ireland     | 2         | 0.46%   |
| Hungary     | 2         | 0.46%   |
| Estonia     | 2         | 0.46%   |
| Denmark     | 2         | 0.46%   |
| Belgium     | 2         | 0.46%   |
| Turkey      | 1         | 0.23%   |
| Peru        | 1         | 0.23%   |
| Palestine   | 1         | 0.23%   |
| Mexico      | 1         | 0.23%   |
| Malaysia    | 1         | 0.23%   |
| Kuwait      | 1         | 0.23%   |
| Japan       | 1         | 0.23%   |
| Indonesia   | 1         | 0.23%   |
| Honduras    | 1         | 0.23%   |
| Guatemala   | 1         | 0.23%   |
| Greece      | 1         | 0.23%   |
| Finland     | 1         | 0.23%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Portland            | 4         | 0.92%   |
| Madrid              | 4         | 0.92%   |
| Austin              | 4         | 0.92%   |
| Valencia            | 3         | 0.69%   |
| Seattle             | 3         | 0.69%   |
| Nottingham          | 3         | 0.69%   |
| Newcastle upon Tyne | 3         | 0.69%   |
| Brooklyn            | 3         | 0.69%   |
| Washington          | 2         | 0.46%   |
| Warsaw              | 2         | 0.46%   |
| Sunnyvale           | 2         | 0.46%   |
| Stuttgart           | 2         | 0.46%   |
| South Holland       | 2         | 0.46%   |
| Riga                | 2         | 0.46%   |
| Queens              | 2         | 0.46%   |
| Prague              | 2         | 0.46%   |
| Phoenix             | 2         | 0.46%   |
| Paris               | 2         | 0.46%   |
| Oxford              | 2         | 0.46%   |
| Oklahoma City       | 2         | 0.46%   |
| Norwich             | 2         | 0.46%   |
| North Shields       | 2         | 0.46%   |
| Muscat              | 2         | 0.46%   |
| Moscow              | 2         | 0.46%   |
| Mississauga         | 2         | 0.46%   |
| Miami               | 2         | 0.46%   |
| Manchester          | 2         | 0.46%   |
| Los Angeles         | 2         | 0.46%   |
| London              | 2         | 0.46%   |
| Henderson           | 2         | 0.46%   |
| Gothenburg          | 2         | 0.46%   |
| Germantown          | 2         | 0.46%   |
| Dresden             | 2         | 0.46%   |
| Detroit             | 2         | 0.46%   |
| Dallas              | 2         | 0.46%   |
| Columbus            | 2         | 0.46%   |
| Colorado Springs    | 2         | 0.46%   |
| Charlotte           | 2         | 0.46%   |
| Calgary             | 2         | 0.46%   |
| Bristol             | 2         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Unknown                        | 187       | 203    | 25.03%  |
| Kingston                       | 84        | 92     | 11.24%  |
| Phison                         | 80        | 83     | 10.71%  |
| Samsung Electronics            | 60        | 77     | 8.03%   |
| Kingston Technology Company    | 50        | 50     | 6.69%   |
| Unknown                        | 47        | 49     | 6.29%   |
| Phison Electronics             | 44        | 47     | 5.89%   |
| O2 Micro                       | 30        | 31     | 4.02%   |
| Sandisk                        | 25        | 29     | 3.35%   |
| Silicon Motion                 | 20        | 22     | 2.68%   |
| Seagate                        | 17        | 21     | 2.28%   |
| SK hynix                       | 11        | 15     | 1.47%   |
| WDC                            | 10        | 13     | 1.34%   |
| Crucial                        | 8         | 9      | 1.07%   |
| Toshiba                        | 7         | 9      | 0.94%   |
| PNY                            | 6         | 7      | 0.8%    |
| KIOXIA                         | 5         | 6      | 0.67%   |
| Intel                          | 5         | 5      | 0.67%   |
| Apple                          | 5         | 7      | 0.67%   |
| A-DATA Technology              | 5         | 5      | 0.67%   |
| Solid State Storage Technology | 4         | 4      | 0.54%   |
| Micron/Crucial Technology      | 4         | 4      | 0.54%   |
| China                          | 3         | 6      | 0.4%    |
| Biwin Storage Technology       | 3         | 3      | 0.4%    |
| ADATA Technology               | 3         | 4      | 0.4%    |
| Realtek Semiconductor          | 2         | 2      | 0.27%   |
| JMicron Technology             | 2         | 2      | 0.27%   |
| ASMT                           | 2         | 2      | 0.27%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.13%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.13%   |
| TrekStor                       | 1         | 1      | 0.13%   |
| SSK                            | 1         | 1      | 0.13%   |
| SPCC                           | 1         | 2      | 0.13%   |
| Realtek                        | 1         | 1      | 0.13%   |
| NGFF                           | 1         | 1      | 0.13%   |
| Mushkin                        | 1         | 1      | 0.13%   |
| Micron Technology              | 1         | 1      | 0.13%   |
| Lexar 25                       | 1         | 1      | 0.13%   |
| KingSpec                       | 1         | 1      | 0.13%   |
| Inateck                        | 1         | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown MMC Card  512GB                               | 72        | 9.31%   |
| Phison NVMe SSD Drive 512GB                           | 55        | 7.12%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB               | 50        | 6.47%   |
| Unknown                                               | 47        | 6.08%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 42        | 5.43%   |
| Kingston NVMe SSD Drive 512GB                         | 42        | 5.43%   |
| Unknown MMC Card  256GB                               | 40        | 5.17%   |
| Kingston NVMe SSD Drive 256GB                         | 32        | 4.14%   |
| Unknown MMC Card  128GB                               | 28        | 3.62%   |
| Phison NVMe SSD Drive 256GB                           | 18        | 2.33%   |
| O2 Micro E2M2 64GB                                    | 16        | 2.07%   |
| O2 Micro NVMe SSD Drive 64GB                          | 15        | 1.94%   |
| Samsung MZ9LQ256HBJD-00BVL 256GB                      | 12        | 1.55%   |
| Unknown MMC Card  393GB                               | 9         | 1.16%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                      | 9         | 1.16%   |
| Unknown MMC Card  64GB                                | 8         | 1.03%   |
| Unknown MMC Card  32GB                                | 8         | 1.03%   |
| Silicon Motion NVMe SSD Drive 512GB                   | 8         | 1.03%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 6         | 0.78%   |
| Silicon Motion NVMe SSD Drive 256GB                   | 5         | 0.65%   |
| Samsung NVMe SSD Drive 512GB                          | 5         | 0.65%   |
| Samsung NVMe SSD Drive 1TB                            | 5         | 0.65%   |
| Unknown MMC Card  500GB                               | 3         | 0.39%   |
| Unknown MMC Card  498GB                               | 3         | 0.39%   |
| Unknown MMC Card  16GB                                | 3         | 0.39%   |
| SK hynix BC711 NVMe 256GB                             | 3         | 0.39%   |
| Sandisk WDC PC SN530 SDBPTPZ-1T00 1024GB              | 3         | 0.39%   |
| Sandisk PC SN530 NVMe WDC 256GB                       | 3         | 0.39%   |
| Samsung NVMe SSD Drive 1024GB                         | 3         | 0.39%   |
| Crucial CT1000BX500SSD1 1TB                           | 3         | 0.39%   |
| Unknown MMC Card  250GB                               | 2         | 0.26%   |
| Unknown MMC Card  196GB                               | 2         | 0.26%   |
| SK hynix NVMe SSD Drive 256GB                         | 2         | 0.26%   |
| SK hynix NVMe SSD Drive 1024GB                        | 2         | 0.26%   |
| Seagate ST1000LM014-1EJ164 1TB                        | 2         | 0.26%   |
| Sandisk WDC PC SN530 SDBPMPZ-256G-1101 256GB          | 2         | 0.26%   |
| SanDisk NVMe SSD Drive 512GB                          | 2         | 0.26%   |
| SanDisk NVMe SSD Drive 500GB                          | 2         | 0.26%   |
| Samsung SSD 970 EVO Plus 1TB                          | 2         | 0.26%   |
| Samsung SSD 870 QVO 2TB                               | 2         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 20     | 53.33%  |
| WDC     | 6         | 8      | 20%     |
| Toshiba | 5         | 7      | 16.67%  |
| Apple   | 2         | 4      | 6.67%   |
| ASMT    | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 23     | 23.88%  |
| Crucial             | 8         | 9      | 11.94%  |
| PNY                 | 6         | 7      | 8.96%   |
| Kingston            | 6         | 7      | 8.96%   |
| SanDisk             | 5         | 6      | 7.46%   |
| A-DATA Technology   | 5         | 5      | 7.46%   |
| WDC                 | 4         | 4      | 5.97%   |
| China               | 3         | 6      | 4.48%   |
| JMicron Technology  | 2         | 2      | 2.99%   |
| Apple               | 2         | 2      | 2.99%   |
| TrekStor            | 1         | 1      | 1.49%   |
| SPCC                | 1         | 2      | 1.49%   |
| NGFF                | 1         | 1      | 1.49%   |
| Mushkin             | 1         | 1      | 1.49%   |
| Lexar 25            | 1         | 1      | 1.49%   |
| KingSpec            | 1         | 1      | 1.49%   |
| Intel               | 1         | 1      | 1.49%   |
| HP Phison           | 1         | 1      | 1.49%   |
| Corsair             | 1         | 1      | 1.49%   |
| ASMT                | 1         | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 400       | 451    | 56.34%  |
| MMC     | 228       | 247    | 32.11%  |
| SSD     | 50        | 82     | 7.04%   |
| HDD     | 26        | 40     | 3.66%   |
| Unknown | 6         | 7      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 400       | 446    | 57.22%  |
| MMC  | 228       | 247    | 32.62%  |
| SATA | 56        | 112    | 8.01%   |
| SAS  | 15        | 22     | 2.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 66     | 52.5%   |
| 0.51-1.0   | 25        | 36     | 31.25%  |
| 1.01-2.0   | 6         | 10     | 7.5%    |
| 3.01-4.0   | 3         | 4      | 3.75%   |
| 2.01-3.0   | 2         | 3      | 2.5%    |
| 4.01-10.0  | 2         | 3      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 198       | 45.41%  |
| 101-250        | 130       | 29.82%  |
| 501-1000       | 50        | 11.47%  |
| 51-100         | 30        | 6.88%   |
| 1001-2000      | 18        | 4.13%   |
| More than 3000 | 6         | 1.38%   |
| 2001-3000      | 3         | 0.69%   |
| 21-50          | 1         | 0.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 151       | 34.01%  |
| 251-500        | 103       | 23.2%   |
| 1-20           | 60        | 13.51%  |
| 21-50          | 57        | 12.84%  |
| 51-100         | 51        | 11.49%  |
| 501-1000       | 14        | 3.15%   |
| 1001-2000      | 5         | 1.13%   |
| More than 3000 | 2         | 0.45%   |
| 2001-3000      | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 426       | 813    | 97.71%  |
| Works    | 10        | 14     | 2.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Kingston Technology Company    | 124       | 25.78%  |
| Phison Electronics             | 121       | 25.16%  |
| Samsung Electronics            | 47        | 9.77%   |
| Intel                          | 38        | 7.9%    |
| AMD                            | 36        | 7.48%   |
| O2 Micro                       | 30        | 6.24%   |
| SanDisk                        | 22        | 4.57%   |
| Silicon Motion                 | 20        | 4.16%   |
| SK hynix                       | 11        | 2.29%   |
| KIOXIA                         | 5         | 1.04%   |
| Solid State Storage Technology | 4         | 0.83%   |
| Micron/Crucial Technology      | 4         | 0.83%   |
| Biwin Storage Technology       | 4         | 0.83%   |
| Toshiba America Info Systems   | 3         | 0.62%   |
| ADATA Technology               | 3         | 0.62%   |
| Realtek Semiconductor          | 2         | 0.42%   |
| Yangtze Memory Technologies    | 1         | 0.21%   |
| Union Memory (Shenzhen)        | 1         | 0.21%   |
| Seagate Technology             | 1         | 0.21%   |
| Micron Technology              | 1         | 0.21%   |
| Marvell Technology Group       | 1         | 0.21%   |
| INNOGRIT                       | 1         | 0.21%   |
| Apple                          | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Kingston Company OM3PDP3 NVMe SSD                                             | 121       | 24.2%   |
| Phison PS5013 E13 NVMe Controller                                             | 113       | 22.6%   |
| Samsung NVMe SSD Controller 980                                               | 35        | 7%      |
| O2 Micro Non-Volatile memory controller                                       | 30        | 6%      |
| AMD FCH SATA Controller [AHCI mode]                                           | 26        | 5.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 19        | 3.8%    |
| SanDisk Non-Volatile memory controller                                        | 13        | 2.6%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                | 9         | 1.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 7         | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                        | 7         | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 6         | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                        | 6         | 1.2%    |
| Phison E12 NVMe Controller                                                    | 5         | 1%      |
| KIOXIA NVMe SSD Controller BG4                                                | 5         | 1%      |
| Solid State Storage Non-Volatile memory controller                            | 4         | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                           | 4         | 0.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 4         | 0.8%    |
| Biwin Storage Non-Volatile memory controller                                  | 4         | 0.8%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 3         | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 3         | 0.6%    |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 3         | 0.6%    |
| Intel SSD 660P Series                                                         | 3         | 0.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 0.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 3         | 0.6%    |
| AMD 300 Series Chipset SATA Controller                                        | 3         | 0.6%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 2         | 0.4%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 2         | 0.4%    |
| SanDisk PC SN530 NVMe SSD                                                     | 2         | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 0.4%    |
| Phison Electronics Non-Volatile memory controller                             | 2         | 0.4%    |
| Kingston Company Company Non-Volatile memory controller                       | 2         | 0.4%    |
| Intel Tiger Lake-LP SATA Controller                                           | 2         | 0.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 0.4%    |
| AMD X370 Series Chipset SATA Controller                                       | 2         | 0.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2         | 0.4%    |
| AMD FCH SATA Controller D                                                     | 2         | 0.4%    |
| Yangtze Memory Non-Volatile memory controller                                 | 1         | 0.2%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 1         | 0.2%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.2%    |
| Toshiba America Info Systems Toshiba America Info SATA controller             | 1         | 0.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 400       | 84.03%  |
| SATA | 67        | 14.08%  |
| RAID | 8         | 1.68%   |
| IDE  | 1         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 383       | 88.86%  |
| Intel  | 48        | 11.14%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD Custom APU 0405                      | 333       | 77.26%  |
| AMD Ryzen 7 6800U with Radeon Graphics   | 6         | 1.39%   |
| AMD Ryzen 9 3900X 12-Core Processor      | 4         | 0.93%   |
| AMD Ryzen 7 4800U with Radeon Graphics   | 3         | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz        | 2         | 0.46%   |
| Intel Core i7-6700K CPU @ 4.00GHz        | 2         | 0.46%   |
| Intel Core i5-4260U CPU @ 1.40GHz        | 2         | 0.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 0.46%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz  | 2         | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor       | 2         | 0.46%   |
| AMD Ryzen 5 5600H with Radeon Graphics   | 2         | 0.46%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 2         | 0.46%   |
| AMD Ryzen 5 4500U with Radeon Graphics   | 2         | 0.46%   |
| AMD Ryzen 5 3600X 6-Core Processor       | 2         | 0.46%   |
| AMD Ryzen 5 2600 Six-Core Processor      | 2         | 0.46%   |
| Intel Xeon W-3223 CPU @ 3.50GHz          | 1         | 0.23%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz      | 1         | 0.23%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz      | 1         | 0.23%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz     | 1         | 0.23%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 0.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 1         | 0.23%   |
| Intel Core i7-8809G CPU @ 3.10GHz        | 1         | 0.23%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 1         | 0.23%   |
| Intel Core i7-7700K CPU @ 4.20GHz        | 1         | 0.23%   |
| Intel Core i7-7560U CPU @ 2.40GHz        | 1         | 0.23%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 1         | 0.23%   |
| Intel Core i7-4578U CPU @ 3.00GHz        | 1         | 0.23%   |
| Intel Core i7-10870H CPU @ 2.20GHz       | 1         | 0.23%   |
| Intel Core i5-9400 CPU @ 2.90GHz         | 1         | 0.23%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 0.23%   |
| Intel Core i5-8600T CPU @ 2.30GHz        | 1         | 0.23%   |
| Intel Core i5-8500T CPU @ 2.10GHz        | 1         | 0.23%   |
| Intel Core i5-8400T CPU @ 1.70GHz        | 1         | 0.23%   |
| Intel Core i5-8259U CPU @ 2.30GHz        | 1         | 0.23%   |
| Intel Core i5-6600 CPU @ 3.30GHz         | 1         | 0.23%   |
| Intel Core i5-6400T CPU @ 2.20GHz        | 1         | 0.23%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1         | 0.23%   |
| Intel Core i5-4440 CPU @ 3.10GHz         | 1         | 0.23%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 1         | 0.23%   |
| Intel Core i5-2435M CPU @ 2.40GHz        | 1         | 0.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 344       | 79.81%  |
| AMD Ryzen 5            | 18        | 4.18%   |
| AMD Ryzen 7            | 17        | 3.94%   |
| Intel Core i5          | 15        | 3.48%   |
| Intel Core i7          | 12        | 2.78%   |
| AMD Ryzen 9            | 7         | 1.62%   |
| Intel Xeon             | 4         | 0.93%   |
| Intel Core i3          | 2         | 0.46%   |
| Intel Atom             | 2         | 0.46%   |
| AMD FX                 | 2         | 0.46%   |
| Intel Pentium Silver   | 1         | 0.23%   |
| Intel Celeron          | 1         | 0.23%   |
| AMD Ryzen Threadripper | 1         | 0.23%   |
| AMD Ryzen 5 PRO        | 1         | 0.23%   |
| AMD Embedded           | 1         | 0.23%   |
| AMD Athlon             | 1         | 0.23%   |
| AMD A8                 | 1         | 0.23%   |
| AMD A10                | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 361       | 83.76%  |
| 8      | 25        | 5.8%    |
| 6      | 25        | 5.8%    |
| 2      | 13        | 3.02%   |
| 12     | 6         | 1.39%   |
| 3      | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 431       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 412       | 95.37%  |
| 1      | 20        | 4.63%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 431       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 421       | 97.68%  |
| 0x08900201 | 6         | 1.39%   |
| 0x906e9    | 1         | 0.23%   |
| 0x0a50000c | 1         | 0.23%   |
| 0x0a404102 | 1         | 0.23%   |
| 0x08600106 | 1         | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 346       | 80.28%  |
| KabyLake      | 16        | 3.71%   |
| Zen 2         | 15        | 3.48%   |
| Zen 3         | 11        | 2.55%   |
| Zen+          | 8         | 1.86%   |
| Haswell       | 7         | 1.62%   |
| TigerLake     | 6         | 1.39%   |
| Skylake       | 6         | 1.39%   |
| Zen           | 4         | 0.93%   |
| Piledriver    | 4         | 0.93%   |
| Silvermont    | 2         | 0.46%   |
| SandyBridge   | 2         | 0.46%   |
| IvyBridge     | 1         | 0.23%   |
| Goldmont plus | 1         | 0.23%   |
| Excavator     | 1         | 0.23%   |
| CometLake     | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 389       | 86.83%  |
| Intel  | 32        | 7.14%   |
| Nvidia | 27        | 6.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 333       | 74.33%  |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 1.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.34%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 1.34%   |
| AMD Renoir                                                                               | 5         | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.12%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 4         | 0.89%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 0.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.67%   |
| Intel HD Graphics 530                                                                    | 3         | 0.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.67%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 3         | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.45%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.45%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.45%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 0.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.45%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 0.45%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 0.45%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.45%   |
| Nvidia TU117M                                                                            | 1         | 0.22%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.22%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.22%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.22%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.22%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.22%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.22%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1         | 0.22%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.22%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.22%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 0.22%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.22%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.22%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.22%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1         | 0.22%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 383       | 88.86%  |
| 1 x Intel      | 19        | 4.41%   |
| 1 x Nvidia     | 15        | 3.48%   |
| Intel + Nvidia | 7         | 1.62%   |
| AMD + Nvidia   | 5         | 1.16%   |
| Other          | 1         | 0.23%   |
| Intel + AMD    | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 408       | 94.66%  |
| Proprietary | 23        | 5.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 405       | 93.97%  |
| 7.01-8.0   | 6         | 1.39%   |
| 3.01-4.0   | 6         | 1.39%   |
| 0.51-1.0   | 5         | 1.16%   |
| 5.01-6.0   | 3         | 0.7%    |
| 1.01-2.0   | 2         | 0.46%   |
| 0.01-0.5   | 2         | 0.46%   |
| 16.01-24.0 | 1         | 0.23%   |
| 8.01-16.0  | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| ANX                  | 189       | 36.21%  |
| Analogix             | 121       | 23.18%  |
| Valve                | 29        | 5.56%   |
| Goldstar             | 22        | 4.21%   |
| Samsung Electronics  | 19        | 3.64%   |
| Dell                 | 8         | 1.53%   |
| BOE                  | 8         | 1.53%   |
| Ancor Communications | 8         | 1.53%   |
| ASUSTek Computer     | 7         | 1.34%   |
| AOC                  | 7         | 1.34%   |
| Vizio                | 6         | 1.15%   |
| Sony                 | 6         | 1.15%   |
| Philips              | 6         | 1.15%   |
| Chimei Innolux       | 6         | 1.15%   |
| Acer                 | 6         | 1.15%   |
| RTK                  | 5         | 0.96%   |
| Hewlett-Packard      | 5         | 0.96%   |
| AU Optronics         | 5         | 0.96%   |
| Apple                | 4         | 0.77%   |
| ViewSonic            | 3         | 0.57%   |
| Sharp                | 3         | 0.57%   |
| MSI                  | 3         | 0.57%   |
| LG Display           | 3         | 0.57%   |
| JDI                  | 3         | 0.57%   |
| BenQ                 | 3         | 0.57%   |
| Sun                  | 2         | 0.38%   |
| Pixio                | 2         | 0.38%   |
| MSF                  | 2         | 0.38%   |
| Microsoft            | 2         | 0.38%   |
| Hitachi              | 2         | 0.38%   |
| ___                  | 1         | 0.19%   |
| ZSC                  | 1         | 0.19%   |
| YTH                  | 1         | 0.19%   |
| Wacom                | 1         | 0.19%   |
| Unknown              | 1         | 0.19%   |
| Toshiba              | 1         | 0.19%   |
| TCL                  | 1         | 0.19%   |
| Sceptre Tech         | 1         | 0.19%   |
| SANYO                | 1         | 0.19%   |
| PANDA                | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ANX ANX7530 U ANX7539 800x1280                                         | 189       | 35.93%  |
| Analogix ANX7530 U ANX7539 800x1280                                    | 121       | 23%     |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 29        | 5.51%   |
| RTK FHD RTK2A3B 1920x1080 597x336mm 27.0-inch                          | 4         | 0.76%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 4         | 0.76%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                     | 3         | 0.57%   |
| Vizio E50-C1 VIZ1004 1920x1080 1095x616mm 49.5-inch                    | 2         | 0.38%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                 | 2         | 0.38%   |
| Sony TV *00 SNY7A04 3840x2160 1218x685mm 55.0-inch                     | 2         | 0.38%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch     | 2         | 0.38%   |
| MSF W0550U99GE-D MSF1003 1080x1920                                     | 2         | 0.38%   |
| Microsoft Xbox One MSH0001 1920x1080 520x290mm 23.4-inch               | 2         | 0.38%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                | 2         | 0.38%   |
| Goldstar ULTRAWIDE GSM5AFB 2560x1080 798x334mm 34.1-inch               | 2         | 0.38%   |
| Goldstar 34GN850 GSM774A 3440x1440 800x335mm 34.1-inch                 | 2         | 0.38%   |
| Goldstar 27GN7 GSM5B8D 1920x1080 600x303mm 26.5-inch                   | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch       | 2         | 0.38%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch       | 2         | 0.38%   |
| Ancor Communications ASUS VH242H ACI24F3 1920x1080 521x293mm 23.5-inch | 2         | 0.38%   |
| ___ LCD TV ___9000 1360x768                                            | 1         | 0.19%   |
| ZSC FHD HDR ZSCBC32 1920x1080 344x195mm 15.6-inch                      | 1         | 0.19%   |
| YTH HS133PC YTH1330 1920x1080 255x220mm 13.3-inch                      | 1         | 0.19%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch               | 1         | 0.19%   |
| Vizio VO320E VIZ0035 1366x768 700x390mm 31.5-inch                      | 1         | 0.19%   |
| Vizio V585x-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                   | 1         | 0.19%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1         | 0.19%   |
| Vizio D24f4-J01 VIZ1044 1920x1080 527x296mm 23.8-inch                  | 1         | 0.19%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1         | 0.19%   |
| ViewSonic VX2858Sml VSCD02F 1920x1080 621x341mm 27.9-inch              | 1         | 0.19%   |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch            | 1         | 0.19%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                     | 1         | 0.19%   |
| Toshiba TV TSB010E 1920x1080 1014x573mm 45.9-inch                      | 1         | 0.19%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                    | 1         | 0.19%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 0.19%   |
| Sony TV *00 SNYF303 1920x1080 1218x685mm 55.0-inch                     | 1         | 0.19%   |
| Sony TV *00 SNY8204 3840x2160 1085x610mm 49.0-inch                     | 1         | 0.19%   |
| Sony BW8 MS_9001 2560x1600                                             | 1         | 0.19%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch                | 1         | 0.19%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.19%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 800x1280           | 328       | 64.57%  |
| 1920x1080 (FHD)    | 85        | 16.73%  |
| 3840x2160 (4K)     | 30        | 5.91%   |
| 2560x1440 (QHD)    | 19        | 3.74%   |
| 3440x1440          | 9         | 1.77%   |
| 2560x1080          | 6         | 1.18%   |
| 2560x1600          | 5         | 0.98%   |
| 1366x768 (WXGA)    | 5         | 0.98%   |
| 3840x1080          | 3         | 0.59%   |
| 1920x1200 (WUXGA)  | 2         | 0.39%   |
| 1600x900 (HD+)     | 2         | 0.39%   |
| 1600x2560          | 2         | 0.39%   |
| 1440x900 (WXGA+)   | 2         | 0.39%   |
| 1280x800 (WXGA)    | 2         | 0.39%   |
| 3840x1600          | 1         | 0.2%    |
| 3200x1800 (QHD+)   | 1         | 0.2%    |
| 2880x1920          | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1680x1050 (WSXGA+) | 1         | 0.2%    |
| 1400x1050          | 1         | 0.2%    |
| 1360x768           | 1         | 0.2%    |
| 1024x768 (XGA)     | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 307       | 59.5%   |
| 7       | 30        | 5.81%   |
| 27      | 29        | 5.62%   |
| 15      | 19        | 3.68%   |
| 23      | 17        | 3.29%   |
| 24      | 14        | 2.71%   |
| 34      | 13        | 2.52%   |
| 21      | 8         | 1.55%   |
| 31      | 7         | 1.36%   |
| 13      | 7         | 1.36%   |
| 72      | 6         | 1.16%   |
| 46      | 6         | 1.16%   |
| 17      | 5         | 0.97%   |
| 14      | 5         | 0.97%   |
| 49      | 4         | 0.78%   |
| 40      | 4         | 0.78%   |
| 84      | 3         | 0.58%   |
| 8       | 3         | 0.58%   |
| 65      | 2         | 0.39%   |
| 64      | 2         | 0.39%   |
| 57      | 2         | 0.39%   |
| 55      | 2         | 0.39%   |
| 54      | 2         | 0.39%   |
| 48      | 2         | 0.39%   |
| 36      | 2         | 0.39%   |
| 32      | 2         | 0.39%   |
| 86      | 1         | 0.19%   |
| 75      | 1         | 0.19%   |
| 69      | 1         | 0.19%   |
| 52      | 1         | 0.19%   |
| 43      | 1         | 0.19%   |
| 42      | 1         | 0.19%   |
| 37      | 1         | 0.19%   |
| 35      | 1         | 0.19%   |
| 28      | 1         | 0.19%   |
| 26      | 1         | 0.19%   |
| 18      | 1         | 0.19%   |
| 11      | 1         | 0.19%   |
| 10      | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 307       | 59.73%  |
| 501-600     | 55        | 10.7%   |
| 1-100       | 29        | 5.64%   |
| 301-350     | 25        | 4.86%   |
| 1001-1500   | 22        | 4.28%   |
| 701-800     | 17        | 3.31%   |
| 601-700     | 13        | 2.53%   |
| 1501-2000   | 12        | 2.33%   |
| 401-500     | 9         | 1.75%   |
| 201-300     | 8         | 1.56%   |
| 801-900     | 6         | 1.17%   |
| 351-400     | 5         | 0.97%   |
| 101-200     | 4         | 0.78%   |
| 901-1000    | 2         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 0.62  | 306       | 60.24%  |
| 16/9  | 142       | 27.95%  |
| 0.67  | 29        | 5.71%   |
| 21/9  | 15        | 2.95%   |
| 16/10 | 7         | 1.38%   |
| 32/9  | 4         | 0.79%   |
| 3/2   | 2         | 0.39%   |
| 0.58  | 2         | 0.39%   |
| 1.00  | 1         | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 307       | 59.61%  |
| 1-40           | 33        | 6.41%   |
| 201-250        | 32        | 6.21%   |
| 301-350        | 30        | 5.83%   |
| More than 1000 | 25        | 4.85%   |
| 351-500        | 25        | 4.85%   |
| 101-110        | 18        | 3.5%    |
| 501-1000       | 17        | 3.3%    |
| 81-90          | 7         | 1.36%   |
| 251-300        | 6         | 1.17%   |
| 71-80          | 5         | 0.97%   |
| 121-130        | 5         | 0.97%   |
| 51-60          | 1         | 0.19%   |
| 41-50          | 1         | 0.19%   |
| 151-200        | 1         | 0.19%   |
| 141-150        | 1         | 0.19%   |
| 91-100         | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 307       | 59.84%  |
| 51-100        | 76        | 14.81%  |
| 161-240       | 39        | 7.6%    |
| 101-120       | 38        | 7.41%   |
| 121-160       | 30        | 5.85%   |
| 1-50          | 20        | 3.9%    |
| More than 240 | 3         | 0.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 351       | 80.69%  |
| 2     | 81        | 18.62%  |
| 3     | 3         | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 383       | 70.4%   |
| ASIX Electronics              | 52        | 9.56%   |
| Intel                         | 51        | 9.38%   |
| MediaTek                      | 8         | 1.47%   |
| Broadcom                      | 8         | 1.47%   |
| Microsoft                     | 7         | 1.29%   |
| TP-Link                       | 6         | 1.1%    |
| Qualcomm Atheros              | 6         | 1.1%    |
| Google                        | 3         | 0.55%   |
| DisplayLink                   | 3         | 0.55%   |
| Broadcom Limited              | 3         | 0.55%   |
| Samsung Electronics           | 2         | 0.37%   |
| Ralink Technology             | 2         | 0.37%   |
| Lenovo                        | 2         | 0.37%   |
| OPPO Electronics              | 1         | 0.18%   |
| OnePlus Technology (Shenzhen) | 1         | 0.18%   |
| Huawei Technologies           | 1         | 0.18%   |
| Edimax Technology             | 1         | 0.18%   |
| Dell                          | 1         | 0.18%   |
| AVM                           | 1         | 0.18%   |
| Aquantia                      | 1         | 0.18%   |
| Apple                         | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 333       | 54.59%  |
| ASIX AX88179 Gigabit Ethernet                                     | 52        | 8.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 6.56%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 6.07%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 1.15%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.15%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 6         | 0.98%   |
| Microsoft XBOX ACC                                                | 5         | 0.82%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.82%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.66%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.49%   |
| Intel Wireless 7265                                               | 3         | 0.49%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.33%   |
| Realtek 802.11ac NIC                                              | 2         | 0.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.33%   |
| Intel Wireless 8260                                               | 2         | 0.33%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.33%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.33%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.33%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 0.33%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1         | 0.16%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.16%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.16%   |
| TP-Link 802.11ac NIC                                              | 1         | 0.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.16%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 342       | 80.47%  |
| Intel                 | 41        | 9.65%   |
| MediaTek              | 8         | 1.88%   |
| Microsoft             | 7         | 1.65%   |
| Broadcom              | 7         | 1.65%   |
| TP-Link               | 6         | 1.41%   |
| Qualcomm Atheros      | 6         | 1.41%   |
| Broadcom Limited      | 3         | 0.71%   |
| Ralink Technology     | 2         | 0.47%   |
| Edimax Technology     | 1         | 0.24%   |
| Dell                  | 1         | 0.24%   |
| AVM                   | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 333       | 78.35%  |
| Intel Wi-Fi 6 AX200                                                                           | 13        | 3.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 7         | 1.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 6         | 1.41%   |
| Microsoft XBOX ACC                                                                            | 5         | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 4         | 0.94%   |
| Intel Wi-Fi 6 AX201                                                                           | 4         | 0.94%   |
| Intel Wireless 7265                                                                           | 3         | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 3         | 0.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2         | 0.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 0.47%   |
| Realtek 802.11ac NIC                                                                          | 2         | 0.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 0.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 2         | 0.47%   |
| Intel Wireless 8260                                                                           | 2         | 0.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2         | 0.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2         | 0.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 2         | 0.47%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 0.24%   |
| TP-Link Archer T4U ver.3                                                                      | 1         | 0.24%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1         | 0.24%   |
| TP-Link 802.11ac NIC                                                                          | 1         | 0.24%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.24%   |
| Realtek Realtek Network controller                                                            | 1         | 0.24%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.24%   |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 0.24%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.24%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1         | 0.24%   |
| Microsoft Wireless XBox Controller Dongle                                                     | 1         | 0.24%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 0.24%   |
| Intel Wireless 3165                                                                           | 1         | 0.24%   |
| Intel WiFi Link 5100                                                                          | 1         | 0.24%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 1         | 0.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 0.24%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 0.24%   |
| Intel Centrino Advanced-N 6235                                                                | 1         | 0.24%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 1         | 0.24%   |
| Edimax AC600 USB                                                                              | 1         | 0.24%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 85        | 46.96%  |
| ASIX Electronics              | 52        | 28.73%  |
| Intel                         | 25        | 13.81%  |
| Google                        | 3         | 1.66%   |
| DisplayLink                   | 3         | 1.66%   |
| Broadcom                      | 3         | 1.66%   |
| Samsung Electronics           | 2         | 1.1%    |
| Qualcomm Atheros              | 2         | 1.1%    |
| Lenovo                        | 2         | 1.1%    |
| OPPO Electronics              | 1         | 0.55%   |
| OnePlus Technology (Shenzhen) | 1         | 0.55%   |
| Huawei Technologies           | 1         | 0.55%   |
| Aquantia                      | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| ASIX AX88179 Gigabit Ethernet                                     | 52        | 28.26%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 21.74%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 20.11%  |
| Intel I211 Gigabit Network Connection                             | 7         | 3.8%    |
| Intel Ethernet Controller I225-V                                  | 5         | 2.72%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 2.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.63%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.09%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.09%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 1.09%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.09%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.54%   |
| OPPO SDM665-IDP _SN:18689828                                      | 1         | 0.54%   |
| OnePlus (Shenzhen) AC2003                                         | 1         | 0.54%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.54%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.54%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.54%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.54%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.54%   |
| Huawei SNE-LX1                                                    | 1         | 0.54%   |
| Google Pixel 7                                                    | 1         | 0.54%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1         | 0.54%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.54%   |
| DisplayLink USB-C Dual-4K Dock                                    | 1         | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 413       | 70.72%  |
| Ethernet | 170       | 29.11%  |
| Modem    | 1         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 369       | 79.7%   |
| Ethernet | 94        | 20.3%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 386       | 89.56%  |
| 2     | 42        | 9.74%   |
| 3     | 3         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 278       | 64.06%  |
| Yes  | 156       | 35.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| IMC Networks                    | 333       | 83.46%  |
| Intel                           | 37        | 9.27%   |
| Realtek Semiconductor           | 6         | 1.5%    |
| Qualcomm Atheros Communications | 5         | 1.25%   |
| Apple                           | 5         | 1.25%   |
| MediaTek                        | 4         | 1%      |
| Broadcom                        | 2         | 0.5%    |
| ASUSTek Computer                | 2         | 0.5%    |
| TP-Link                         | 1         | 0.25%   |
| Lite-On Technology              | 1         | 0.25%   |
| Integrated System Solution      | 1         | 0.25%   |
| Foxconn / Hon Hai               | 1         | 0.25%   |
| Cambridge Silicon Radio         | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                          | 333       | 83.46%  |
| Intel AX200 Bluetooth                                 | 11        | 2.76%   |
| Intel Bluetooth wireless interface                    | 9         | 2.26%   |
| Intel AX210 Bluetooth                                 | 7         | 1.75%   |
| Intel AX201 Bluetooth                                 | 5         | 1.25%   |
| MediaTek Wireless_Device                              | 4         | 1%      |
| Realtek Bluetooth Radio                               | 3         | 0.75%   |
| Qualcomm Atheros  Bluetooth Device                    | 3         | 0.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3         | 0.75%   |
| Apple Bluetooth USB Host Controller                   | 3         | 0.75%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2         | 0.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 0.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2         | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2         | 0.5%    |
| Apple Bluetooth Host Controller                       | 2         | 0.5%    |
| TP-Link UB500 Adapter                                 | 1         | 0.25%   |
| Realtek Bluetooth 5.1 Radio                           | 1         | 0.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1         | 0.25%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1         | 0.25%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1         | 0.25%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.25%   |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 0.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 1         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| AMD                         | 396       | 77.8%   |
| Intel                       | 45        | 8.84%   |
| Nvidia                      | 24        | 4.72%   |
| Logitech                    | 7         | 1.38%   |
| Realtek Semiconductor       | 3         | 0.59%   |
| Corsair                     | 3         | 0.59%   |
| C-Media Electronics         | 3         | 0.59%   |
| Tenx Technology             | 2         | 0.39%   |
| Sony                        | 2         | 0.39%   |
| Lenovo                      | 2         | 0.39%   |
| Kingston Technology         | 2         | 0.39%   |
| JMTek                       | 2         | 0.39%   |
| Generalplus Technology      | 2         | 0.39%   |
| FiiO Electronics Technology | 2         | 0.39%   |
| Blue Microphones            | 2         | 0.39%   |
| Apple                       | 2         | 0.39%   |
| Valve Software              | 1         | 0.2%    |
| SteelSeries ApS             | 1         | 0.2%    |
| Razer USA                   | 1         | 0.2%    |
| Quanta                      | 1         | 0.2%    |
| Nreal                       | 1         | 0.2%    |
| MosArt Semiconductor        | 1         | 0.2%    |
| KTMicro                     | 1         | 0.2%    |
| GN Netcom                   | 1         | 0.2%    |
| Creative Labs               | 1         | 0.2%    |
| Alesis                      | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller                      | 339       | 61.08%  |
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 4.32%   |
| AMD Starship/Matisse HD Audio Controller                                   | 13        | 2.34%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 2.34%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 10        | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8         | 1.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8         | 1.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.08%   |
| AMD Navi 10 HDMI Audio                                                     | 6         | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.9%    |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 0.72%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 0.72%   |
| Realtek Semiconductor USB Audio                                            | 3         | 0.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.54%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.54%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 0.54%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 0.54%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 0.54%   |
| Tenx Technology USB AUDIO                                                  | 2         | 0.36%   |
| Sony DualSense wireless controller (PS5)                                   | 2         | 0.36%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.36%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.36%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.36%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.36%   |
| JMTek USB PnP Audio Device                                                 | 2         | 0.36%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 0.36%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 0.36%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.36%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 0.36%   |
| Generalplus Technology USB Audio Device                                    | 2         | 0.36%   |
| FiiO Electronics Technology K3                                             | 2         | 0.36%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.36%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.36%   |
| AMD FCH Azalia Controller                                                  | 2         | 0.36%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1         | 0.18%   |
| SteelSeries ApS SteelSeries Arctis Pro                                     | 1         | 0.18%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 7         | 58.33%  |
| SK hynix            | 1         | 8.33%   |
| Samsung Electronics | 1         | 8.33%   |
| Micron Technology   | 1         | 8.33%   |
| G.Skill             | 1         | 8.33%   |
| Crucial             | 1         | 8.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown                                                | 7         | 58.33%  |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 8.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s  | 1         | 8.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s   | 1         | 8.33%   |
| G.Skill RAM F4-2666C19-16GRS 16GB SODIMM DDR4 2667MT/s | 1         | 8.33%   |
| Crucial RAM CT8G4SFS832A.C8FR 8GB SODIMM DDR4 3200MT/s | 1         | 8.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| LPDDR5  | 6         | 54.55%  |
| DDR4    | 4         | 36.36%  |
| Unknown | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 11        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 7         | 63.64%  |
| 8192  | 3         | 27.27%  |
| 16384 | 1         | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 4266  | 6         | 54.55%  |
| 3200  | 3         | 27.27%  |
| 6400  | 1         | 9.09%   |
| 2667  | 1         | 9.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| HP Laserjet CP1525nw | 1         | 100%    |

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
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 16.33%  |
| Logitech                               | 5         | 10.2%   |
| Apple                                  | 5         | 10.2%   |
| Microdia                               | 4         | 8.16%   |
| Tripath Technology                     | 3         | 6.12%   |
| Realtek Semiconductor                  | 3         | 6.12%   |
| Quanta                                 | 3         | 6.12%   |
| Acer                                   | 3         | 6.12%   |
| Sunplus Innovation Technology          | 2         | 4.08%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.08%   |
| Valve Software                         | 1         | 2.04%   |
| Unknown                                | 1         | 2.04%   |
| Tobii Technology AB                    | 1         | 2.04%   |
| Syntek                                 | 1         | 2.04%   |
| Suyin                                  | 1         | 2.04%   |
| SunplusIT                              | 1         | 2.04%   |
| Samsung Electronics                    | 1         | 2.04%   |
| Magic Control Technology               | 1         | 2.04%   |
| Luxvisions Innotech Limited            | 1         | 2.04%   |
| IMC Networks                           | 1         | 2.04%   |
| AVerMedia Technologies                 | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Tripath USB Camera                                                            | 3         | 6.12%   |
| Apple iPhone 5/5C/5S/6/SE                                                     | 3         | 6.12%   |
| Microdia Webcam Vitade AF                                                     | 2         | 4.08%   |
| Chicony HD User Facing                                                        | 2         | 4.08%   |
| Acer Integrated Camera                                                        | 2         | 4.08%   |
| Valve Software 3D Camera                                                      | 1         | 2.04%   |
| Unknown 720p HD Camera                                                        | 1         | 2.04%   |
| Tobii AB EyeChip                                                              | 1         | 2.04%   |
| Syntek Integrated Camera                                                      | 1         | 2.04%   |
| Suyin HP Truevision HD                                                        | 1         | 2.04%   |
| SunplusIT CODi A05020 Webcam                                                  | 1         | 2.04%   |
| Sunplus USB 2.0 Camera                                                        | 1         | 2.04%   |
| Sunplus Integrated_Webcam_FHD                                                 | 1         | 2.04%   |
| Samsung Galaxy series, misc. (MTP mode)                                       | 1         | 2.04%   |
| Realtek WEB CAMERA M9 Pro                                                     | 1         | 2.04%   |
| Realtek USB Camera                                                            | 1         | 2.04%   |
| Realtek Integrated_Webcam_HD                                                  | 1         | 2.04%   |
| Quanta VGA WebCam                                                             | 1         | 2.04%   |
| Quanta HP Wide Vision HD Camera                                               | 1         | 2.04%   |
| Quanta HD Camera                                                              | 1         | 2.04%   |
| Microdia Integrated_Webcam_HD                                                 | 1         | 2.04%   |
| Microdia Integrated Webcam HD                                                 | 1         | 2.04%   |
| Magic Control j5 WebCam JVCU100                                               | 1         | 2.04%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                           | 1         | 2.04%   |
| Logitech Webcam C930e                                                         | 1         | 2.04%   |
| Logitech HD Webcam C615                                                       | 1         | 2.04%   |
| Logitech HD Webcam C525                                                       | 1         | 2.04%   |
| Logitech HD Pro Webcam C920                                                   | 1         | 2.04%   |
| Logitech CrystalCam                                                           | 1         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                                             | 1         | 2.04%   |
| Chicony USB2.0 HD UVC WebCam                                                  | 1         | 2.04%   |
| Chicony Integrated Camera (1280x720@30)                                       | 1         | 2.04%   |
| Chicony Integrated Camera                                                     | 1         | 2.04%   |
| Chicony HP Wide Vision HD Camera                                              | 1         | 2.04%   |
| Chicony HP TrueVision HD Camera                                               | 1         | 2.04%   |
| Chicony HP High Definition 1MP Webcam                                         | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) SunplusIT INC. HP Truevision HD Webcam | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                       | 1         | 2.04%   |
| AVerMedia Live Streamer CAM 313                                               | 1         | 2.04%   |
| Apple FaceTime HD Camera (Built-in)                                           | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 1         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 33.33%  |
| Elan Microelectronics      | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device         | 1         | 33.33%  |
| Elan fingerprint sensor [FeinTech FPS00200] | 1         | 33.33%  |
| Unknown                                     | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| SCM Microsystems | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| SCM Microsystems SCR3500 A Contact Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 391       | 90.72%  |
| 1     | 29        | 6.73%   |
| 2     | 10        | 2.32%   |
| 4     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 18        | 35.29%  |
| Multimedia controller | 18        | 35.29%  |
| Graphics card         | 4         | 7.84%   |
| Unassigned class      | 3         | 5.88%   |
| Fingerprint reader    | 3         | 5.88%   |
| Storage/nvme          | 1         | 1.96%   |
| Sound                 | 1         | 1.96%   |
| Net/ethernet          | 1         | 1.96%   |
| Modem                 | 1         | 1.96%   |
| Chipcard              | 1         | 1.96%   |

