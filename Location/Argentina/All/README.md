Linux in Argentina - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Argentina.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Argentina/Desktop/README.md) and [notebooks](/Location/Argentina/Notebook/README.md).

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

Total: 2611

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Exo           | Smart Serie LT              | Notebook    | [bbecad1cea](https://linux-hardware.org/?probe=bbecad1cea) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [fc025a599d](https://linux-hardware.org/?probe=fc025a599d) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [f32fbdf6ea](https://linux-hardware.org/?probe=f32fbdf6ea) | Jun 10, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [abc3a3d8a1](https://linux-hardware.org/?probe=abc3a3d8a1) | Jun 09, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [fc826b3cb1](https://linux-hardware.org/?probe=fc826b3cb1) | Jun 09, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [b457e63434](https://linux-hardware.org/?probe=b457e63434) | Jun 09, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [fd3b70424a](https://linux-hardware.org/?probe=fd3b70424a) | Jun 09, 2023 |
| HP            | Notebook                    | Notebook    | [e292bb9d5a](https://linux-hardware.org/?probe=e292bb9d5a) | Jun 09, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [24f6f6e727](https://linux-hardware.org/?probe=24f6f6e727) | Jun 08, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [931b9e2b05](https://linux-hardware.org/?probe=931b9e2b05) | Jun 08, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [8d4e2bedde](https://linux-hardware.org/?probe=8d4e2bedde) | Jun 08, 2023 |
| Colorful T... | A520M-K PRO V14             | Desktop     | [48c4aa3d8c](https://linux-hardware.org/?probe=48c4aa3d8c) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [31a7447d8b](https://linux-hardware.org/?probe=31a7447d8b) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [267154b0d2](https://linux-hardware.org/?probe=267154b0d2) | Jun 08, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [ee2b6b0279](https://linux-hardware.org/?probe=ee2b6b0279) | Jun 08, 2023 |
| Intel         | HURONRIVER                  | Notebook    | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e45ed702a4](https://linux-hardware.org/?probe=e45ed702a4) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | Desktop     | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [43cffb0d0f](https://linux-hardware.org/?probe=43cffb0d0f) | Jun 04, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [cef2bf28c9](https://linux-hardware.org/?probe=cef2bf28c9) | Jun 04, 2023 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [e6492d37d8](https://linux-hardware.org/?probe=e6492d37d8) | Jun 03, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [c6ee1e5e32](https://linux-hardware.org/?probe=c6ee1e5e32) | Jun 02, 2023 |
| HP            | Split 13 x2 PC              | Notebook    | [5e3ae671cc](https://linux-hardware.org/?probe=5e3ae671cc) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [4a2e70149f](https://linux-hardware.org/?probe=4a2e70149f) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [b8fb5e55bc](https://linux-hardware.org/?probe=b8fb5e55bc) | Jun 01, 2023 |
| Positivo      | C500                        | Notebook    | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [670044aef5](https://linux-hardware.org/?probe=670044aef5) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1ea9c869ff](https://linux-hardware.org/?probe=1ea9c869ff) | May 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [b8e68f9227](https://linux-hardware.org/?probe=b8e68f9227) | May 29, 2023 |
| PCBOX         | Kant                        | Notebook    | [1e2f772d05](https://linux-hardware.org/?probe=1e2f772d05) | May 29, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [21261aa270](https://linux-hardware.org/?probe=21261aa270) | May 28, 2023 |
| Intel         | X99                         | Desktop     | [70895d913f](https://linux-hardware.org/?probe=70895d913f) | May 28, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bbd09f3d8f](https://linux-hardware.org/?probe=bbd09f3d8f) | May 27, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [184afbb9c3](https://linux-hardware.org/?probe=184afbb9c3) | May 26, 2023 |
| Lenovo        | ThinkPad E495 20NES0RS00    | Notebook    | [6f507e12bc](https://linux-hardware.org/?probe=6f507e12bc) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [63ba811050](https://linux-hardware.org/?probe=63ba811050) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [380b9a5005](https://linux-hardware.org/?probe=380b9a5005) | May 25, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a4690b7476](https://linux-hardware.org/?probe=a4690b7476) | May 25, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [82183f4762](https://linux-hardware.org/?probe=82183f4762) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8fb981666f](https://linux-hardware.org/?probe=8fb981666f) | May 24, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e4c9c425f8](https://linux-hardware.org/?probe=e4c9c425f8) | May 23, 2023 |
| MSI           | B460M PRO                   | Desktop     | [94ce62125f](https://linux-hardware.org/?probe=94ce62125f) | May 23, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [8ae80f0665](https://linux-hardware.org/?probe=8ae80f0665) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [584c6658c6](https://linux-hardware.org/?probe=584c6658c6) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [e7d7c8f7d8](https://linux-hardware.org/?probe=e7d7c8f7d8) | May 23, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [e250801798](https://linux-hardware.org/?probe=e250801798) | May 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [069d442d0d](https://linux-hardware.org/?probe=069d442d0d) | May 22, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [cb61728cb7](https://linux-hardware.org/?probe=cb61728cb7) | May 22, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [c2d03bd839](https://linux-hardware.org/?probe=c2d03bd839) | May 22, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [1dda8d01ad](https://linux-hardware.org/?probe=1dda8d01ad) | May 20, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [fe4d0a2ec3](https://linux-hardware.org/?probe=fe4d0a2ec3) | May 20, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c571a25585](https://linux-hardware.org/?probe=c571a25585) | May 19, 2023 |
| Lenovo        | IdeaPad U530 Touch 20289    | Notebook    | [72e254e4ee](https://linux-hardware.org/?probe=72e254e4ee) | May 19, 2023 |
| Philco        | PHN14C                      | Notebook    | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bd7e95bf66](https://linux-hardware.org/?probe=bd7e95bf66) | May 18, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [ca3fda27b5](https://linux-hardware.org/?probe=ca3fda27b5) | May 18, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [f720713dda](https://linux-hardware.org/?probe=f720713dda) | May 13, 2023 |
| HP            | 339A                        | Desktop     | [2ba14f8397](https://linux-hardware.org/?probe=2ba14f8397) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1713b94d26](https://linux-hardware.org/?probe=1713b94d26) | May 12, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [81711fd069](https://linux-hardware.org/?probe=81711fd069) | May 11, 2023 |
| Unknown       | M-140BI3                    | Notebook    | [eb6507c151](https://linux-hardware.org/?probe=eb6507c151) | May 11, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | Desktop     | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [efca4bf9af](https://linux-hardware.org/?probe=efca4bf9af) | May 10, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [35750a650a](https://linux-hardware.org/?probe=35750a650a) | May 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [813acd1225](https://linux-hardware.org/?probe=813acd1225) | May 10, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [fbe7b6d2bf](https://linux-hardware.org/?probe=fbe7b6d2bf) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [26e8efdd69](https://linux-hardware.org/?probe=26e8efdd69) | May 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [89ccdd7262](https://linux-hardware.org/?probe=89ccdd7262) | May 08, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [d63bc9aeca](https://linux-hardware.org/?probe=d63bc9aeca) | May 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [18dcba612c](https://linux-hardware.org/?probe=18dcba612c) | May 07, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [67b9224d87](https://linux-hardware.org/?probe=67b9224d87) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [6ec1762e12](https://linux-hardware.org/?probe=6ec1762e12) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [6816b3dddd](https://linux-hardware.org/?probe=6816b3dddd) | May 07, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e5488a0dc9](https://linux-hardware.org/?probe=e5488a0dc9) | May 06, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [2d41ef08f2](https://linux-hardware.org/?probe=2d41ef08f2) | May 05, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7cf447e261](https://linux-hardware.org/?probe=7cf447e261) | May 05, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [2e4e7c801d](https://linux-hardware.org/?probe=2e4e7c801d) | May 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e7f4d1fdda](https://linux-hardware.org/?probe=e7f4d1fdda) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [1f3953650c](https://linux-hardware.org/?probe=1f3953650c) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [417be33443](https://linux-hardware.org/?probe=417be33443) | May 05, 2023 |
| MSI           | 760GM-P34                   | Desktop     | [cb75fca473](https://linux-hardware.org/?probe=cb75fca473) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [218ba5d6a5](https://linux-hardware.org/?probe=218ba5d6a5) | May 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [92c9651e22](https://linux-hardware.org/?probe=92c9651e22) | May 04, 2023 |
| Intel         | DG43GT AAE62768-300         | Desktop     | [e0f10df0f9](https://linux-hardware.org/?probe=e0f10df0f9) | May 03, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2fabcbe5dc](https://linux-hardware.org/?probe=2fabcbe5dc) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fa453d9183](https://linux-hardware.org/?probe=fa453d9183) | May 02, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [f62abcbed6](https://linux-hardware.org/?probe=f62abcbed6) | May 02, 2023 |
| ASUSTek       | A55M-E                      | Desktop     | [927efc8106](https://linux-hardware.org/?probe=927efc8106) | May 02, 2023 |
| iQual         | NQ4X                        | Notebook    | [256ae92f40](https://linux-hardware.org/?probe=256ae92f40) | May 02, 2023 |
| ASUSTek       | A55M-E                      | Desktop     | [ee1054dc5c](https://linux-hardware.org/?probe=ee1054dc5c) | May 01, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [67da6cebd3](https://linux-hardware.org/?probe=67da6cebd3) | Apr 29, 2023 |
| HP            | Unknown                     | Notebook    | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| Dell          | Latitude E5410              | Notebook    | [1efb62110c](https://linux-hardware.org/?probe=1efb62110c) | Apr 27, 2023 |
| Dell          | Latitude E5410              | Notebook    | [02be2c8f0b](https://linux-hardware.org/?probe=02be2c8f0b) | Apr 26, 2023 |
| HP            | 81BB                        | All in one  | [65fb6f51d1](https://linux-hardware.org/?probe=65fb6f51d1) | Apr 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9e926f5c65](https://linux-hardware.org/?probe=9e926f5c65) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| HP            | 090Ch                       | Desktop     | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [7a1a8bb421](https://linux-hardware.org/?probe=7a1a8bb421) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [3fa24b1a91](https://linux-hardware.org/?probe=3fa24b1a91) | Apr 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [c8ec222920](https://linux-hardware.org/?probe=c8ec222920) | Apr 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2a02b4695b](https://linux-hardware.org/?probe=2a02b4695b) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [bf1dbf49a8](https://linux-hardware.org/?probe=bf1dbf49a8) | Apr 22, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [32ba023e2a](https://linux-hardware.org/?probe=32ba023e2a) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [cde822d71c](https://linux-hardware.org/?probe=cde822d71c) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5f61e3a174](https://linux-hardware.org/?probe=5f61e3a174) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b0b94f2462](https://linux-hardware.org/?probe=b0b94f2462) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d429a2c865](https://linux-hardware.org/?probe=d429a2c865) | Apr 21, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [f89cce4966](https://linux-hardware.org/?probe=f89cce4966) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f5da23bee0](https://linux-hardware.org/?probe=f5da23bee0) | Apr 20, 2023 |
| MSI           | GE62 6QD                    | Notebook    | [785d4c1655](https://linux-hardware.org/?probe=785d4c1655) | Apr 20, 2023 |
| Dell          | Latitude E6440              | Notebook    | [027d51d72d](https://linux-hardware.org/?probe=027d51d72d) | Apr 19, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6696ce8fd6](https://linux-hardware.org/?probe=6696ce8fd6) | Apr 17, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [b4e51d0af3](https://linux-hardware.org/?probe=b4e51d0af3) | Apr 17, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [a6ba0d9290](https://linux-hardware.org/?probe=a6ba0d9290) | Apr 17, 2023 |
| iQual         | NQ4X                        | Notebook    | [425ccf4057](https://linux-hardware.org/?probe=425ccf4057) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [9b23be6c48](https://linux-hardware.org/?probe=9b23be6c48) | Apr 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c5f2678609](https://linux-hardware.org/?probe=c5f2678609) | Apr 15, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [6419c7fb77](https://linux-hardware.org/?probe=6419c7fb77) | Apr 15, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [9d18bebcd7](https://linux-hardware.org/?probe=9d18bebcd7) | Apr 15, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [921a57413c](https://linux-hardware.org/?probe=921a57413c) | Apr 15, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [d1ed9e6040](https://linux-hardware.org/?probe=d1ed9e6040) | Apr 14, 2023 |
| HP            | Compaq Presario F700        | Notebook    | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Dell          | Latitude 5490               | Notebook    | [38ebdedf58](https://linux-hardware.org/?probe=38ebdedf58) | Apr 12, 2023 |
| HP            | 81BB                        | All in one  | [ef22a07523](https://linux-hardware.org/?probe=ef22a07523) | Apr 12, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [1649a1f9b5](https://linux-hardware.org/?probe=1649a1f9b5) | Apr 12, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [497756c5ab](https://linux-hardware.org/?probe=497756c5ab) | Apr 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [dc55b7997e](https://linux-hardware.org/?probe=dc55b7997e) | Apr 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b35d9a7487](https://linux-hardware.org/?probe=b35d9a7487) | Apr 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE1M    | Notebook    | [eb794b0dc7](https://linux-hardware.org/?probe=eb794b0dc7) | Apr 10, 2023 |
| Positivo      | A1000BW                     | Notebook    | [02295facdc](https://linux-hardware.org/?probe=02295facdc) | Apr 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [916db99ea5](https://linux-hardware.org/?probe=916db99ea5) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5a900adcdc](https://linux-hardware.org/?probe=5a900adcdc) | Apr 07, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [91fcea0b0f](https://linux-hardware.org/?probe=91fcea0b0f) | Apr 07, 2023 |
| Gigabyte      | AORUS 15P KD                | Notebook    | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [bb95a52e54](https://linux-hardware.org/?probe=bb95a52e54) | Apr 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [58f5904dec](https://linux-hardware.org/?probe=58f5904dec) | Apr 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [9f251621b1](https://linux-hardware.org/?probe=9f251621b1) | Apr 04, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f801258fa5](https://linux-hardware.org/?probe=f801258fa5) | Apr 04, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [47c6d88922](https://linux-hardware.org/?probe=47c6d88922) | Apr 03, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 80XB     | Convertible | [1e1b34725b](https://linux-hardware.org/?probe=1e1b34725b) | Apr 03, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [71f34e6ebc](https://linux-hardware.org/?probe=71f34e6ebc) | Apr 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [676156b5df](https://linux-hardware.org/?probe=676156b5df) | Apr 02, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5fc258772a](https://linux-hardware.org/?probe=5fc258772a) | Apr 01, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [2addcb84c6](https://linux-hardware.org/?probe=2addcb84c6) | Apr 01, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [f54ccba86f](https://linux-hardware.org/?probe=f54ccba86f) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [3c163a3b34](https://linux-hardware.org/?probe=3c163a3b34) | Mar 31, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [8d2858a444](https://linux-hardware.org/?probe=8d2858a444) | Mar 31, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [45a242d18f](https://linux-hardware.org/?probe=45a242d18f) | Mar 31, 2023 |
| Exo           | Smart XL4                   | Notebook    | [6421142cb6](https://linux-hardware.org/?probe=6421142cb6) | Mar 31, 2023 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [193d27ceac](https://linux-hardware.org/?probe=193d27ceac) | Mar 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [2ca1607b80](https://linux-hardware.org/?probe=2ca1607b80) | Mar 30, 2023 |
| AIR           | CX30500                     | Notebook    | [2ea4d0ec83](https://linux-hardware.org/?probe=2ea4d0ec83) | Mar 30, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [41a76fad3f](https://linux-hardware.org/?probe=41a76fad3f) | Mar 30, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [1e510aad42](https://linux-hardware.org/?probe=1e510aad42) | Mar 30, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [25cc7bfca2](https://linux-hardware.org/?probe=25cc7bfca2) | Mar 28, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b6184e813b](https://linux-hardware.org/?probe=b6184e813b) | Mar 28, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [f281edd494](https://linux-hardware.org/?probe=f281edd494) | Mar 28, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [709242697d](https://linux-hardware.org/?probe=709242697d) | Mar 27, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [a9ca07dc80](https://linux-hardware.org/?probe=a9ca07dc80) | Mar 27, 2023 |
| Sony          | VJFE52A0711H                | Notebook    | [f2186a4bc4](https://linux-hardware.org/?probe=f2186a4bc4) | Mar 27, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [dca4079e12](https://linux-hardware.org/?probe=dca4079e12) | Mar 26, 2023 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [c671afb118](https://linux-hardware.org/?probe=c671afb118) | Mar 26, 2023 |
| HP            | G42                         | Notebook    | [f1b5695907](https://linux-hardware.org/?probe=f1b5695907) | Mar 25, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [3677f24e87](https://linux-hardware.org/?probe=3677f24e87) | Mar 25, 2023 |
| Dell          | Latitude 5480               | Notebook    | [5886784510](https://linux-hardware.org/?probe=5886784510) | Mar 22, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [dcae89c3e5](https://linux-hardware.org/?probe=dcae89c3e5) | Mar 21, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9ff80f0344](https://linux-hardware.org/?probe=9ff80f0344) | Mar 21, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [708f22e8d7](https://linux-hardware.org/?probe=708f22e8d7) | Mar 19, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [eea214ee38](https://linux-hardware.org/?probe=eea214ee38) | Mar 18, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [0ac96925cd](https://linux-hardware.org/?probe=0ac96925cd) | Mar 16, 2023 |
| ECS           | A55F-M4                     | Desktop     | [eaee63c0f9](https://linux-hardware.org/?probe=eaee63c0f9) | Mar 14, 2023 |
| ECS           | A55F-M4                     | Desktop     | [667ab38865](https://linux-hardware.org/?probe=667ab38865) | Mar 14, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | Notebook    | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Exo           | Smart XS1                   | Notebook    | [e1e04684eb](https://linux-hardware.org/?probe=e1e04684eb) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [97504eea44](https://linux-hardware.org/?probe=97504eea44) | Mar 13, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e035b82dec](https://linux-hardware.org/?probe=e035b82dec) | Mar 13, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [07ebf171d6](https://linux-hardware.org/?probe=07ebf171d6) | Mar 12, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [309d95f00f](https://linux-hardware.org/?probe=309d95f00f) | Mar 11, 2023 |
| Intel         | H61                         | Desktop     | [5650f6d211](https://linux-hardware.org/?probe=5650f6d211) | Mar 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [284d2d79f0](https://linux-hardware.org/?probe=284d2d79f0) | Mar 11, 2023 |
| BANGHO        | LITE E34                    | Desktop     | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [1815783cfe](https://linux-hardware.org/?probe=1815783cfe) | Mar 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7236313c80](https://linux-hardware.org/?probe=7236313c80) | Mar 09, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [bb3776e45d](https://linux-hardware.org/?probe=bb3776e45d) | Mar 09, 2023 |
| eMachines     | eME730                      | Notebook    | [0e1683ee34](https://linux-hardware.org/?probe=0e1683ee34) | Mar 08, 2023 |
| eMachines     | eME730                      | Notebook    | [db15f88805](https://linux-hardware.org/?probe=db15f88805) | Mar 08, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | Notebook    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| Exo           | Smart Serie M               | Notebook    | [99c93d693a](https://linux-hardware.org/?probe=99c93d693a) | Mar 04, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [82994d7312](https://linux-hardware.org/?probe=82994d7312) | Mar 04, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [5523730c91](https://linux-hardware.org/?probe=5523730c91) | Mar 04, 2023 |
| Exo           | Smart Serie M               | Notebook    | [e7b817f5ed](https://linux-hardware.org/?probe=e7b817f5ed) | Mar 04, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [abb62fe86f](https://linux-hardware.org/?probe=abb62fe86f) | Mar 04, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [3c2ed7f053](https://linux-hardware.org/?probe=3c2ed7f053) | Mar 04, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ae8045e8dd](https://linux-hardware.org/?probe=ae8045e8dd) | Mar 04, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [aefca0b663](https://linux-hardware.org/?probe=aefca0b663) | Feb 28, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [12ccf2fe8b](https://linux-hardware.org/?probe=12ccf2fe8b) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [c7bb2ebe8b](https://linux-hardware.org/?probe=c7bb2ebe8b) | Feb 24, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c19b7cd0f5](https://linux-hardware.org/?probe=c19b7cd0f5) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [916f372721](https://linux-hardware.org/?probe=916f372721) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [6e82a5c5d6](https://linux-hardware.org/?probe=6e82a5c5d6) | Feb 24, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [f7d34fdd3a](https://linux-hardware.org/?probe=f7d34fdd3a) | Feb 24, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [a37b20471b](https://linux-hardware.org/?probe=a37b20471b) | Feb 23, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [2f9c2ec647](https://linux-hardware.org/?probe=2f9c2ec647) | Feb 23, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a5f65720f5](https://linux-hardware.org/?probe=a5f65720f5) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [cfcf2ff473](https://linux-hardware.org/?probe=cfcf2ff473) | Feb 21, 2023 |
| Exo           | Smart XL4                   | Notebook    | [6e97a3ff67](https://linux-hardware.org/?probe=6e97a3ff67) | Feb 21, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [bbef057c8f](https://linux-hardware.org/?probe=bbef057c8f) | Feb 21, 2023 |
| Dell          | Inspiron 3502               | Notebook    | [224f4edab7](https://linux-hardware.org/?probe=224f4edab7) | Feb 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [008d5e19e1](https://linux-hardware.org/?probe=008d5e19e1) | Feb 20, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b4b87d47fb](https://linux-hardware.org/?probe=b4b87d47fb) | Feb 17, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [38a92c4ace](https://linux-hardware.org/?probe=38a92c4ace) | Feb 15, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [ba53e8885b](https://linux-hardware.org/?probe=ba53e8885b) | Feb 13, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| BANGHO        | GM-15Z11 GF1650 i5          | Notebook    | [6cdb04950c](https://linux-hardware.org/?probe=6cdb04950c) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [a64bb02ece](https://linux-hardware.org/?probe=a64bb02ece) | Feb 10, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [a07b2a4444](https://linux-hardware.org/?probe=a07b2a4444) | Feb 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f8de6e450a](https://linux-hardware.org/?probe=f8de6e450a) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| ASRock        | B560 Pro4                   | Desktop     | [0243fe3621](https://linux-hardware.org/?probe=0243fe3621) | Feb 07, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [eca9b95b61](https://linux-hardware.org/?probe=eca9b95b61) | Feb 07, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [a1f33b7267](https://linux-hardware.org/?probe=a1f33b7267) | Feb 06, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [5ae73f08c5](https://linux-hardware.org/?probe=5ae73f08c5) | Feb 06, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [32f4028033](https://linux-hardware.org/?probe=32f4028033) | Feb 05, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [93ee4435a2](https://linux-hardware.org/?probe=93ee4435a2) | Feb 03, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [86667a843f](https://linux-hardware.org/?probe=86667a843f) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [03540bd8e5](https://linux-hardware.org/?probe=03540bd8e5) | Feb 02, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [a6584159ac](https://linux-hardware.org/?probe=a6584159ac) | Feb 02, 2023 |
| ECS           | P4M800PRO-M                 | Desktop     | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| ECS           | A55F-M4                     | Desktop     | [08af507321](https://linux-hardware.org/?probe=08af507321) | Feb 01, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [f6d37d568c](https://linux-hardware.org/?probe=f6d37d568c) | Feb 01, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [9fab32d6a5](https://linux-hardware.org/?probe=9fab32d6a5) | Feb 01, 2023 |
| Samsung       | SQ35S                       | Notebook    | [7ad1c8a94b](https://linux-hardware.org/?probe=7ad1c8a94b) | Feb 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [298b411767](https://linux-hardware.org/?probe=298b411767) | Jan 31, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5abc8dccdb](https://linux-hardware.org/?probe=5abc8dccdb) | Jan 31, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [e8f09a159a](https://linux-hardware.org/?probe=e8f09a159a) | Jan 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [5122097b1e](https://linux-hardware.org/?probe=5122097b1e) | Jan 29, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [d25a13d2c4](https://linux-hardware.org/?probe=d25a13d2c4) | Jan 28, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | Notebook    | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b2c04ca4b9](https://linux-hardware.org/?probe=b2c04ca4b9) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [1099a3c6c9](https://linux-hardware.org/?probe=1099a3c6c9) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [4944e0cddd](https://linux-hardware.org/?probe=4944e0cddd) | Jan 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [055d033d99](https://linux-hardware.org/?probe=055d033d99) | Jan 24, 2023 |
| Sony          | VPCEA30EL                   | Notebook    | [7de250ffe6](https://linux-hardware.org/?probe=7de250ffe6) | Jan 24, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| ECS           | A55F-M4                     | Desktop     | [db65e68855](https://linux-hardware.org/?probe=db65e68855) | Jan 23, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [458bb94702](https://linux-hardware.org/?probe=458bb94702) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [7ecc4d20c3](https://linux-hardware.org/?probe=7ecc4d20c3) | Jan 19, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [b0716d3518](https://linux-hardware.org/?probe=b0716d3518) | Jan 19, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [cb4c89a390](https://linux-hardware.org/?probe=cb4c89a390) | Jan 18, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| BANGHO        | MOV                         | Notebook    | [bc4f98d4ff](https://linux-hardware.org/?probe=bc4f98d4ff) | Jan 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [212fa962a2](https://linux-hardware.org/?probe=212fa962a2) | Jan 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [ca60f249a9](https://linux-hardware.org/?probe=ca60f249a9) | Jan 13, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [08638b9441](https://linux-hardware.org/?probe=08638b9441) | Jan 13, 2023 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [4a07474fa4](https://linux-hardware.org/?probe=4a07474fa4) | Jan 12, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [8243f25120](https://linux-hardware.org/?probe=8243f25120) | Jan 12, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [86a6601ce5](https://linux-hardware.org/?probe=86a6601ce5) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [46679246b9](https://linux-hardware.org/?probe=46679246b9) | Jan 11, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [790736a10e](https://linux-hardware.org/?probe=790736a10e) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8c480c028a](https://linux-hardware.org/?probe=8c480c028a) | Jan 10, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [ff6c949737](https://linux-hardware.org/?probe=ff6c949737) | Jan 09, 2023 |
| Dell          | Latitude 3490               | Notebook    | [7cf81f6b69](https://linux-hardware.org/?probe=7cf81f6b69) | Jan 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4334ec8d00](https://linux-hardware.org/?probe=4334ec8d00) | Jan 08, 2023 |
| ASUSTek       | M2N68-AM SE                 | Desktop     | [52a0fe59db](https://linux-hardware.org/?probe=52a0fe59db) | Jan 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [7ce97bb3ec](https://linux-hardware.org/?probe=7ce97bb3ec) | Jan 08, 2023 |
| HP            | 240 G8                      | Notebook    | [efc7e61483](https://linux-hardware.org/?probe=efc7e61483) | Jan 06, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [290ccc3261](https://linux-hardware.org/?probe=290ccc3261) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cddb2a7b81](https://linux-hardware.org/?probe=cddb2a7b81) | Jan 06, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [95db7fffba](https://linux-hardware.org/?probe=95db7fffba) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [aa23d3d6f0](https://linux-hardware.org/?probe=aa23d3d6f0) | Jan 04, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a4473dafda](https://linux-hardware.org/?probe=a4473dafda) | Jan 03, 2023 |
| Positivo      | Z100                        | Notebook    | [58b7c4d1ff](https://linux-hardware.org/?probe=58b7c4d1ff) | Jan 02, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [c6c0626dd1](https://linux-hardware.org/?probe=c6c0626dd1) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5fbe1632b0](https://linux-hardware.org/?probe=5fbe1632b0) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5a479fed95](https://linux-hardware.org/?probe=5a479fed95) | Dec 31, 2022 |
| Dell          | Latitude E6430              | Notebook    | [de9b03cf29](https://linux-hardware.org/?probe=de9b03cf29) | Dec 31, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [ed5315b768](https://linux-hardware.org/?probe=ed5315b768) | Dec 29, 2022 |
| Acer          | AO756                       | Notebook    | [d0cf64acd1](https://linux-hardware.org/?probe=d0cf64acd1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [e12c24fd74](https://linux-hardware.org/?probe=e12c24fd74) | Dec 28, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [8cbb4aa960](https://linux-hardware.org/?probe=8cbb4aa960) | Dec 28, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [d6e7a07be2](https://linux-hardware.org/?probe=d6e7a07be2) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| Exo           | Smart Serie M               | Notebook    | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c7babe827f](https://linux-hardware.org/?probe=c7babe827f) | Dec 26, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [5004189ba4](https://linux-hardware.org/?probe=5004189ba4) | Dec 26, 2022 |
| ASRock        | FM2A78M-HD+ R2.0            | Desktop     | [ff69d47b58](https://linux-hardware.org/?probe=ff69d47b58) | Dec 24, 2022 |
| ASRock        | FM2A78M-HD+ R2.0            | Desktop     | [696403dae4](https://linux-hardware.org/?probe=696403dae4) | Dec 24, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [7de172c3b1](https://linux-hardware.org/?probe=7de172c3b1) | Dec 23, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [668dac3d4c](https://linux-hardware.org/?probe=668dac3d4c) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [af0433651a](https://linux-hardware.org/?probe=af0433651a) | Dec 22, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [1f8d567742](https://linux-hardware.org/?probe=1f8d567742) | Dec 20, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [aaaf436994](https://linux-hardware.org/?probe=aaaf436994) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b34ce3474d](https://linux-hardware.org/?probe=b34ce3474d) | Dec 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [ae3789203b](https://linux-hardware.org/?probe=ae3789203b) | Dec 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [97aa100931](https://linux-hardware.org/?probe=97aa100931) | Dec 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [33bbc3a179](https://linux-hardware.org/?probe=33bbc3a179) | Dec 18, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [04cc986bf6](https://linux-hardware.org/?probe=04cc986bf6) | Dec 15, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| Dell          | Latitude 5520               | Notebook    | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| Exo           | Smart Serie M               | Notebook    | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [9866855d37](https://linux-hardware.org/?probe=9866855d37) | Dec 13, 2022 |
| Clevo         | M740TU/M760TU               | Notebook    | [5f1a4b58fb](https://linux-hardware.org/?probe=5f1a4b58fb) | Dec 13, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| MSI           | A55M-E33                    | Desktop     | [327967e6a4](https://linux-hardware.org/?probe=327967e6a4) | Dec 11, 2022 |
| Dell          | Latitude E6430              | Notebook    | [f28775142d](https://linux-hardware.org/?probe=f28775142d) | Dec 09, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | Desktop     | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| Dell          | G15 5515                    | Notebook    | [861bd0cabf](https://linux-hardware.org/?probe=861bd0cabf) | Dec 08, 2022 |
| HP            | Notebook                    | Notebook    | [37eead7e86](https://linux-hardware.org/?probe=37eead7e86) | Dec 07, 2022 |
| BANGHO        | BES T5                      | Notebook    | [db1db74a86](https://linux-hardware.org/?probe=db1db74a86) | Dec 06, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [7d42818fc5](https://linux-hardware.org/?probe=7d42818fc5) | Dec 06, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [3b87d266c2](https://linux-hardware.org/?probe=3b87d266c2) | Dec 02, 2022 |
| Dell          | Latitude E5450              | Notebook    | [305bf364f6](https://linux-hardware.org/?probe=305bf364f6) | Dec 01, 2022 |
| Dell          | Latitude E5450              | Notebook    | [2b934a729c](https://linux-hardware.org/?probe=2b934a729c) | Dec 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [becc2328fd](https://linux-hardware.org/?probe=becc2328fd) | Dec 01, 2022 |
| Lenovo        | ThinkCentre M70e 0809D1Y    | Desktop     | [0cd85fa9f3](https://linux-hardware.org/?probe=0cd85fa9f3) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | Notebook    | [81eca2f60e](https://linux-hardware.org/?probe=81eca2f60e) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | Notebook    | [5841aa11f1](https://linux-hardware.org/?probe=5841aa11f1) | Nov 30, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [3f545fe7c9](https://linux-hardware.org/?probe=3f545fe7c9) | Nov 29, 2022 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [8b3da34947](https://linux-hardware.org/?probe=8b3da34947) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Foxconn       | A74ML-K                     | Desktop     | [438e3ff761](https://linux-hardware.org/?probe=438e3ff761) | Nov 27, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Lenovo        | ThinkPad E14 20RBS3LE00     | Notebook    | [83203a04f2](https://linux-hardware.org/?probe=83203a04f2) | Nov 25, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [036dcac9fa](https://linux-hardware.org/?probe=036dcac9fa) | Nov 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [fdafa2db2a](https://linux-hardware.org/?probe=fdafa2db2a) | Nov 22, 2022 |
| HP            | Notebook                    | Notebook    | [ab824250b9](https://linux-hardware.org/?probe=ab824250b9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [498c078586](https://linux-hardware.org/?probe=498c078586) | Nov 21, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [abda5b4aaf](https://linux-hardware.org/?probe=abda5b4aaf) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7ffd8149f4](https://linux-hardware.org/?probe=7ffd8149f4) | Nov 21, 2022 |
| Dell          | Latitude E6510              | Notebook    | [c8b9fa9d0a](https://linux-hardware.org/?probe=c8b9fa9d0a) | Nov 20, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [86159f4ef3](https://linux-hardware.org/?probe=86159f4ef3) | Nov 20, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0734f58b03](https://linux-hardware.org/?probe=0734f58b03) | Nov 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [ebceee7ddf](https://linux-hardware.org/?probe=ebceee7ddf) | Nov 18, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [d22a7fff30](https://linux-hardware.org/?probe=d22a7fff30) | Nov 18, 2022 |
| ASUSTek       | K52Jc                       | Notebook    | [375bc280d3](https://linux-hardware.org/?probe=375bc280d3) | Nov 18, 2022 |
| Exo           | Smart XS1                   | Notebook    | [d51bf05ac5](https://linux-hardware.org/?probe=d51bf05ac5) | Nov 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [3964f95a8c](https://linux-hardware.org/?probe=3964f95a8c) | Nov 17, 2022 |
| Dell          | G15 5515                    | Notebook    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [ef34a2a126](https://linux-hardware.org/?probe=ef34a2a126) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [d82617ae65](https://linux-hardware.org/?probe=d82617ae65) | Nov 15, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [c6e254c4ed](https://linux-hardware.org/?probe=c6e254c4ed) | Nov 14, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [83e4ef99fb](https://linux-hardware.org/?probe=83e4ef99fb) | Nov 13, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7e9c7562d6](https://linux-hardware.org/?probe=7e9c7562d6) | Nov 13, 2022 |
| ASUSTek       | UX410UAK                    | Notebook    | [6653b6c4a5](https://linux-hardware.org/?probe=6653b6c4a5) | Nov 13, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [842f768168](https://linux-hardware.org/?probe=842f768168) | Nov 12, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [9b43ddbe11](https://linux-hardware.org/?probe=9b43ddbe11) | Nov 09, 2022 |
| Lenovo        | ThinkPad W541 20EGS0V700    | Notebook    | [d03ec65abc](https://linux-hardware.org/?probe=d03ec65abc) | Nov 08, 2022 |
| HP            | 240 G8                      | Notebook    | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d71ebfae8b](https://linux-hardware.org/?probe=d71ebfae8b) | Nov 07, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [8e89ed396e](https://linux-hardware.org/?probe=8e89ed396e) | Nov 05, 2022 |
| BANGHO        | W240HU/W250HUQ              | Notebook    | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Juana Mans... | SF20GM7                     | Notebook    | [8e8c4f52f4](https://linux-hardware.org/?probe=8e8c4f52f4) | Nov 04, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [f427764e2c](https://linux-hardware.org/?probe=f427764e2c) | Nov 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [deac1b706f](https://linux-hardware.org/?probe=deac1b706f) | Oct 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [a4e0449df5](https://linux-hardware.org/?probe=a4e0449df5) | Oct 30, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | Notebook    | [9cf3beb13f](https://linux-hardware.org/?probe=9cf3beb13f) | Oct 30, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | Notebook    | [36b3303b35](https://linux-hardware.org/?probe=36b3303b35) | Oct 30, 2022 |
| ASUSTek       | TUF H370-PRO GAMING WIFI    | Desktop     | [48cbfa7a78](https://linux-hardware.org/?probe=48cbfa7a78) | Oct 28, 2022 |
| Compaq        | Presario 21 VerX            | Notebook    | [97ee92b9d1](https://linux-hardware.org/?probe=97ee92b9d1) | Oct 28, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [3eeb2624bf](https://linux-hardware.org/?probe=3eeb2624bf) | Oct 27, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [c923b6d506](https://linux-hardware.org/?probe=c923b6d506) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1bc5db124b](https://linux-hardware.org/?probe=1bc5db124b) | Oct 27, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [9c19f9e755](https://linux-hardware.org/?probe=9c19f9e755) | Oct 27, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [eca0e58bd8](https://linux-hardware.org/?probe=eca0e58bd8) | Oct 25, 2022 |
| Dell          | Precision 5560              | Notebook    | [c6cfa3f96d](https://linux-hardware.org/?probe=c6cfa3f96d) | Oct 25, 2022 |
| Dell          | Precision 5560              | Notebook    | [e0dce17c1f](https://linux-hardware.org/?probe=e0dce17c1f) | Oct 25, 2022 |
| ASRock        | N68-S                       | Desktop     | [f1f502f834](https://linux-hardware.org/?probe=f1f502f834) | Oct 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [0c60239460](https://linux-hardware.org/?probe=0c60239460) | Oct 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3749438ef1](https://linux-hardware.org/?probe=3749438ef1) | Oct 24, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [25db15ea87](https://linux-hardware.org/?probe=25db15ea87) | Oct 24, 2022 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [8f793706c2](https://linux-hardware.org/?probe=8f793706c2) | Oct 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [4a17b0a89d](https://linux-hardware.org/?probe=4a17b0a89d) | Oct 22, 2022 |
| Intel         | Montevina CRB               | Notebook    | [11cb344c52](https://linux-hardware.org/?probe=11cb344c52) | Oct 22, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [c8a0b8e94f](https://linux-hardware.org/?probe=c8a0b8e94f) | Oct 20, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [2413dd813b](https://linux-hardware.org/?probe=2413dd813b) | Oct 19, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [d565cdf4a5](https://linux-hardware.org/?probe=d565cdf4a5) | Oct 19, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [3b8ac4e243](https://linux-hardware.org/?probe=3b8ac4e243) | Oct 19, 2022 |
| Positivo      | AT300i                      | Notebook    | [02190f570b](https://linux-hardware.org/?probe=02190f570b) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c4a0f6af56](https://linux-hardware.org/?probe=c4a0f6af56) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cde8c87a3a](https://linux-hardware.org/?probe=cde8c87a3a) | Oct 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1be458024b](https://linux-hardware.org/?probe=1be458024b) | Oct 15, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [603fc4f4cd](https://linux-hardware.org/?probe=603fc4f4cd) | Oct 15, 2022 |
| Dell          | Latitude E5450              | Notebook    | [68e2c17e2f](https://linux-hardware.org/?probe=68e2c17e2f) | Oct 15, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [85f4236c50](https://linux-hardware.org/?probe=85f4236c50) | Oct 15, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| BANGHO        | B801 IP-M23.62.06           | All in one  | [5a66a855a8](https://linux-hardware.org/?probe=5a66a855a8) | Oct 14, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [a14b57c22c](https://linux-hardware.org/?probe=a14b57c22c) | Oct 14, 2022 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [6a810d253c](https://linux-hardware.org/?probe=6a810d253c) | Oct 13, 2022 |
| Dell          | Latitude 7420               | Convertible | [dade6a2b21](https://linux-hardware.org/?probe=dade6a2b21) | Oct 13, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [13e68d4364](https://linux-hardware.org/?probe=13e68d4364) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [1444f8cc5b](https://linux-hardware.org/?probe=1444f8cc5b) | Oct 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [31fbbb40a0](https://linux-hardware.org/?probe=31fbbb40a0) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77d21da9a2](https://linux-hardware.org/?probe=77d21da9a2) | Oct 11, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [477851891a](https://linux-hardware.org/?probe=477851891a) | Oct 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7dcd7050ae](https://linux-hardware.org/?probe=7dcd7050ae) | Oct 10, 2022 |
| Positivo      | AT300i                      | Notebook    | [62b9d61028](https://linux-hardware.org/?probe=62b9d61028) | Oct 09, 2022 |
| Positivo      | AT300i                      | Notebook    | [8bbd312832](https://linux-hardware.org/?probe=8bbd312832) | Oct 09, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [6ea2c2d73b](https://linux-hardware.org/?probe=6ea2c2d73b) | Oct 08, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [7f78dda318](https://linux-hardware.org/?probe=7f78dda318) | Oct 07, 2022 |
| HP            | 339A                        | Desktop     | [0cb27058b8](https://linux-hardware.org/?probe=0cb27058b8) | Oct 07, 2022 |
| ASUSTek       | X505BP                      | Notebook    | [3ebba89d5e](https://linux-hardware.org/?probe=3ebba89d5e) | Oct 07, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [c621294169](https://linux-hardware.org/?probe=c621294169) | Oct 07, 2022 |
| Samsung       | 530U4E/540U4E               | Notebook    | [11ed7b9f37](https://linux-hardware.org/?probe=11ed7b9f37) | Oct 07, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| BANGHO        | GAMER GM-X 15s              | Notebook    | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0a022a22c6](https://linux-hardware.org/?probe=0a022a22c6) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7ed786bee9](https://linux-hardware.org/?probe=7ed786bee9) | Sep 30, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [51a7f36a69](https://linux-hardware.org/?probe=51a7f36a69) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| Biostar       | H55 HD                      | Desktop     | [bde8e0a133](https://linux-hardware.org/?probe=bde8e0a133) | Sep 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [d5a4d2ae41](https://linux-hardware.org/?probe=d5a4d2ae41) | Sep 28, 2022 |
| Positivo      | SW6H                        | Notebook    | [4cfa6665bb](https://linux-hardware.org/?probe=4cfa6665bb) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| System76      | Lemur Pro                   | Notebook    | [35340e6221](https://linux-hardware.org/?probe=35340e6221) | Sep 26, 2022 |
| NSX           | Celeron 14                  | Notebook    | [b8fdb14beb](https://linux-hardware.org/?probe=b8fdb14beb) | Sep 25, 2022 |
| NSX           | Celeron 14                  | Notebook    | [1d358a2828](https://linux-hardware.org/?probe=1d358a2828) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [f038a5908f](https://linux-hardware.org/?probe=f038a5908f) | Sep 23, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [628fd0d32d](https://linux-hardware.org/?probe=628fd0d32d) | Sep 21, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [b07937de6a](https://linux-hardware.org/?probe=b07937de6a) | Sep 20, 2022 |
| BANGHO        | BES G1529                   | Notebook    | [ce0db88361](https://linux-hardware.org/?probe=ce0db88361) | Sep 20, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [75854836f7](https://linux-hardware.org/?probe=75854836f7) | Sep 20, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [e4e09c23e5](https://linux-hardware.org/?probe=e4e09c23e5) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [f52b35d82d](https://linux-hardware.org/?probe=f52b35d82d) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b3350b3f69](https://linux-hardware.org/?probe=b3350b3f69) | Sep 17, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d4d8cc3f34](https://linux-hardware.org/?probe=d4d8cc3f34) | Sep 16, 2022 |
| Exo           | Smart XL4                   | Notebook    | [96f159b86f](https://linux-hardware.org/?probe=96f159b86f) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | Desktop     | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| HP            | Pavilion 17                 | Notebook    | [5d9be9b086](https://linux-hardware.org/?probe=5d9be9b086) | Sep 13, 2022 |
| Dell          | Precision 5550              | Notebook    | [82eebd67fd](https://linux-hardware.org/?probe=82eebd67fd) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [105dae5731](https://linux-hardware.org/?probe=105dae5731) | Sep 11, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [c9b78bb640](https://linux-hardware.org/?probe=c9b78bb640) | Sep 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [7d108d27ee](https://linux-hardware.org/?probe=7d108d27ee) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [a877bbf17d](https://linux-hardware.org/?probe=a877bbf17d) | Sep 09, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [86af6e4676](https://linux-hardware.org/?probe=86af6e4676) | Sep 08, 2022 |
| HP            | 245 G6                      | Notebook    | [054d226709](https://linux-hardware.org/?probe=054d226709) | Sep 07, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [35ead5350d](https://linux-hardware.org/?probe=35ead5350d) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c905c86c47](https://linux-hardware.org/?probe=c905c86c47) | Sep 07, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [efb1e9883d](https://linux-hardware.org/?probe=efb1e9883d) | Sep 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [20178af23f](https://linux-hardware.org/?probe=20178af23f) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [fc5e3d8261](https://linux-hardware.org/?probe=fc5e3d8261) | Sep 05, 2022 |
| Intel         | powered classmate PC        | Notebook    | [ed36baccf9](https://linux-hardware.org/?probe=ed36baccf9) | Aug 31, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [115b09b849](https://linux-hardware.org/?probe=115b09b849) | Aug 30, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [373a11a297](https://linux-hardware.org/?probe=373a11a297) | Aug 29, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [505eb9a97c](https://linux-hardware.org/?probe=505eb9a97c) | Aug 29, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [c107217cf8](https://linux-hardware.org/?probe=c107217cf8) | Aug 28, 2022 |
| BANGHO        | AERO X2 I1002               | Notebook    | [f24ddb9619](https://linux-hardware.org/?probe=f24ddb9619) | Aug 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [11cd220cfd](https://linux-hardware.org/?probe=11cd220cfd) | Aug 27, 2022 |
| Exo           | Smart Serie L               | Notebook    | [5cbaef571b](https://linux-hardware.org/?probe=5cbaef571b) | Aug 27, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [9fe64d4a60](https://linux-hardware.org/?probe=9fe64d4a60) | Aug 27, 2022 |
| HP            | Notebook                    | Notebook    | [2d11bc2975](https://linux-hardware.org/?probe=2d11bc2975) | Aug 26, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [c824203d0a](https://linux-hardware.org/?probe=c824203d0a) | Aug 24, 2022 |
| Standard      | AHV                         | Notebook    | [1a4d477350](https://linux-hardware.org/?probe=1a4d477350) | Aug 24, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [c3ddddae2c](https://linux-hardware.org/?probe=c3ddddae2c) | Aug 24, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6c0183592b](https://linux-hardware.org/?probe=6c0183592b) | Aug 23, 2022 |
| Sony          | VGN-NR210FH                 | Notebook    | [8c007bfa55](https://linux-hardware.org/?probe=8c007bfa55) | Aug 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [d4a7a111a7](https://linux-hardware.org/?probe=d4a7a111a7) | Aug 21, 2022 |
| Novatech      | C141WP-I5HS                 | Notebook    | [767c02caeb](https://linux-hardware.org/?probe=767c02caeb) | Aug 20, 2022 |
| Compaq        | Presario 21 VerX            | Notebook    | [97aa39b2ca](https://linux-hardware.org/?probe=97aa39b2ca) | Aug 19, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | Notebook    | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0dbc32a26d](https://linux-hardware.org/?probe=0dbc32a26d) | Aug 17, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [58f88a4494](https://linux-hardware.org/?probe=58f88a4494) | Aug 17, 2022 |
| HP            | Notebook                    | Notebook    | [784ad31f68](https://linux-hardware.org/?probe=784ad31f68) | Aug 17, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [e68b5affa4](https://linux-hardware.org/?probe=e68b5affa4) | Aug 16, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [7c3e324e4f](https://linux-hardware.org/?probe=7c3e324e4f) | Aug 16, 2022 |
| PCBOX         | Kant                        | Notebook    | [1b5c160d93](https://linux-hardware.org/?probe=1b5c160d93) | Aug 16, 2022 |
| Dell          | Latitude E6510              | Notebook    | [2a4c496cce](https://linux-hardware.org/?probe=2a4c496cce) | Aug 15, 2022 |
| ASRock        | H55M                        | Desktop     | [8d0bd0d2d2](https://linux-hardware.org/?probe=8d0bd0d2d2) | Aug 15, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [d5862f21f5](https://linux-hardware.org/?probe=d5862f21f5) | Aug 14, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [c001e6e62b](https://linux-hardware.org/?probe=c001e6e62b) | Aug 12, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [d08cbbc3d8](https://linux-hardware.org/?probe=d08cbbc3d8) | Aug 12, 2022 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [6b5082a45c](https://linux-hardware.org/?probe=6b5082a45c) | Aug 12, 2022 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [d77caddb55](https://linux-hardware.org/?probe=d77caddb55) | Aug 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [2f3db9cd91](https://linux-hardware.org/?probe=2f3db9cd91) | Aug 12, 2022 |
| HP            | Pavilion 17                 | Notebook    | [25a07691ec](https://linux-hardware.org/?probe=25a07691ec) | Aug 12, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [fad6aace6a](https://linux-hardware.org/?probe=fad6aace6a) | Aug 11, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [cac00fb432](https://linux-hardware.org/?probe=cac00fb432) | Aug 11, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [15488377fb](https://linux-hardware.org/?probe=15488377fb) | Aug 10, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [5484873fd7](https://linux-hardware.org/?probe=5484873fd7) | Aug 10, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [31bdc504d4](https://linux-hardware.org/?probe=31bdc504d4) | Aug 10, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [a6f68827fb](https://linux-hardware.org/?probe=a6f68827fb) | Aug 09, 2022 |
| NVN-ED01      | Unknown                     | Notebook    | [0a677cad6c](https://linux-hardware.org/?probe=0a677cad6c) | Aug 09, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [b8ae818291](https://linux-hardware.org/?probe=b8ae818291) | Aug 08, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [b07157a232](https://linux-hardware.org/?probe=b07157a232) | Aug 08, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [18d8a04343](https://linux-hardware.org/?probe=18d8a04343) | Aug 08, 2022 |
| Toshiba       | Satellite Pro L300D         | Notebook    | [b3ed30ac52](https://linux-hardware.org/?probe=b3ed30ac52) | Aug 07, 2022 |
| MSI           | CR620                       | Notebook    | [517b816cd7](https://linux-hardware.org/?probe=517b816cd7) | Aug 06, 2022 |
| Intel         | 945GCT-M                    | Desktop     | [0481d5180e](https://linux-hardware.org/?probe=0481d5180e) | Aug 06, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [ab52d0fc52](https://linux-hardware.org/?probe=ab52d0fc52) | Aug 05, 2022 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [0b4eaa2b43](https://linux-hardware.org/?probe=0b4eaa2b43) | Aug 03, 2022 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [beaaaa6f6e](https://linux-hardware.org/?probe=beaaaa6f6e) | Aug 03, 2022 |
| LG Electro... | R480-L.B211P1               | Notebook    | [307f422c53](https://linux-hardware.org/?probe=307f422c53) | Aug 03, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [e586e6ee53](https://linux-hardware.org/?probe=e586e6ee53) | Aug 02, 2022 |
| Intel         | DH55HC AAE70933-502         | Desktop     | [a484fb9cc8](https://linux-hardware.org/?probe=a484fb9cc8) | Aug 02, 2022 |
| Exo           | Exomate X352                | Notebook    | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [0b8452087a](https://linux-hardware.org/?probe=0b8452087a) | Aug 02, 2022 |
| Toshiba       | Satellite-C845              | Notebook    | [6ee9ea90a5](https://linux-hardware.org/?probe=6ee9ea90a5) | Aug 01, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [72278643e8](https://linux-hardware.org/?probe=72278643e8) | Aug 01, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [047d3c88ad](https://linux-hardware.org/?probe=047d3c88ad) | Jul 31, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [14bbcb7e47](https://linux-hardware.org/?probe=14bbcb7e47) | Jul 30, 2022 |
| ASRock        | Z97 Pro4                    | Desktop     | [0db03812df](https://linux-hardware.org/?probe=0db03812df) | Jul 29, 2022 |
| MSI           | Z370 GAMING M5              | Desktop     | [b9ec9e3dd4](https://linux-hardware.org/?probe=b9ec9e3dd4) | Jul 28, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [eb92148078](https://linux-hardware.org/?probe=eb92148078) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S31T0... | Notebook    | [60449c872b](https://linux-hardware.org/?probe=60449c872b) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [a2c2f04e29](https://linux-hardware.org/?probe=a2c2f04e29) | Jul 26, 2022 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [88b45b1956](https://linux-hardware.org/?probe=88b45b1956) | Jul 26, 2022 |
| ASUSTek       | X550ZA                      | Notebook    | [00126a3052](https://linux-hardware.org/?probe=00126a3052) | Jul 25, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [7ffde486ac](https://linux-hardware.org/?probe=7ffde486ac) | Jul 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f84af529bb](https://linux-hardware.org/?probe=f84af529bb) | Jul 24, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [72a44c6eea](https://linux-hardware.org/?probe=72a44c6eea) | Jul 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [73a12fbe59](https://linux-hardware.org/?probe=73a12fbe59) | Jul 21, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [321d2817a3](https://linux-hardware.org/?probe=321d2817a3) | Jul 21, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [6f5d960fdc](https://linux-hardware.org/?probe=6f5d960fdc) | Jul 21, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [2543aa4d88](https://linux-hardware.org/?probe=2543aa4d88) | Jul 21, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| Dell          | 0DR845                      | Desktop     | [cf4bcf9de8](https://linux-hardware.org/?probe=cf4bcf9de8) | Jul 19, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [475d626fd5](https://linux-hardware.org/?probe=475d626fd5) | Jul 19, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [48d9b9f502](https://linux-hardware.org/?probe=48d9b9f502) | Jul 18, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [70c17c522d](https://linux-hardware.org/?probe=70c17c522d) | Jul 18, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8ae373a79c](https://linux-hardware.org/?probe=8ae373a79c) | Jul 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5089cb3d81](https://linux-hardware.org/?probe=5089cb3d81) | Jul 17, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [3e2c54f9f1](https://linux-hardware.org/?probe=3e2c54f9f1) | Jul 17, 2022 |
| NSX           | SB142G                      | Notebook    | [12329702b6](https://linux-hardware.org/?probe=12329702b6) | Jul 15, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [0c08648c4d](https://linux-hardware.org/?probe=0c08648c4d) | Jul 15, 2022 |
| ASRock        | A55M-VS                     | Desktop     | [844ac53526](https://linux-hardware.org/?probe=844ac53526) | Jul 14, 2022 |
| ASRock        | A55M-VS                     | Desktop     | [3b8f491017](https://linux-hardware.org/?probe=3b8f491017) | Jul 14, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [5c5b387f6c](https://linux-hardware.org/?probe=5c5b387f6c) | Jul 14, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [c90a0cbab7](https://linux-hardware.org/?probe=c90a0cbab7) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [87fa08ea59](https://linux-hardware.org/?probe=87fa08ea59) | Jul 13, 2022 |
| Standard      | AHV                         | Notebook    | [2499cab6bd](https://linux-hardware.org/?probe=2499cab6bd) | Jul 12, 2022 |
| Lenovo        | ThinkPad L470 20J5S01L00    | Notebook    | [401e13e2a6](https://linux-hardware.org/?probe=401e13e2a6) | Jul 12, 2022 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [46d0d5dccc](https://linux-hardware.org/?probe=46d0d5dccc) | Jul 12, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [67d1588e47](https://linux-hardware.org/?probe=67d1588e47) | Jul 12, 2022 |
| BANGHO        | W240HU/W250HUQ              | Notebook    | [4f064a8dbc](https://linux-hardware.org/?probe=4f064a8dbc) | Jul 10, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [3aee4d5b24](https://linux-hardware.org/?probe=3aee4d5b24) | Jul 09, 2022 |
| ECS           | H110M4-C23                  | Desktop     | [4a4af6d2e9](https://linux-hardware.org/?probe=4a4af6d2e9) | Jul 08, 2022 |
| Dell          | Latitude 3520               | Notebook    | [8439c98834](https://linux-hardware.org/?probe=8439c98834) | Jul 07, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [5b90bd12c7](https://linux-hardware.org/?probe=5b90bd12c7) | Jul 07, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [9c2136e4eb](https://linux-hardware.org/?probe=9c2136e4eb) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [244b168c32](https://linux-hardware.org/?probe=244b168c32) | Jul 06, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [a9d516466a](https://linux-hardware.org/?probe=a9d516466a) | Jul 06, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [147320c75c](https://linux-hardware.org/?probe=147320c75c) | Jul 04, 2022 |
| NSX           | SB142G                      | Notebook    | [58158ab261](https://linux-hardware.org/?probe=58158ab261) | Jul 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [2a161e0d10](https://linux-hardware.org/?probe=2a161e0d10) | Jul 04, 2022 |
| Novatech      | C141WP-I5HS                 | Notebook    | [c487164618](https://linux-hardware.org/?probe=c487164618) | Jul 04, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ad993981af](https://linux-hardware.org/?probe=ad993981af) | Jul 02, 2022 |
| Intel         | DX58SO AAE29331-703         | Desktop     | [3b22974574](https://linux-hardware.org/?probe=3b22974574) | Jul 01, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [c38c4e9cb9](https://linux-hardware.org/?probe=c38c4e9cb9) | Jun 30, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [28479b3edf](https://linux-hardware.org/?probe=28479b3edf) | Jun 30, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [8d9a85c7f3](https://linux-hardware.org/?probe=8d9a85c7f3) | Jun 30, 2022 |
| MSI           | CR620                       | Notebook    | [0968b18823](https://linux-hardware.org/?probe=0968b18823) | Jun 30, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ddfd26738](https://linux-hardware.org/?probe=8ddfd26738) | Jun 29, 2022 |
| ASUSTek       | UX302LA                     | Notebook    | [6092e85ae8](https://linux-hardware.org/?probe=6092e85ae8) | Jun 29, 2022 |
| Dell          | Latitude 3410               | Notebook    | [050678128c](https://linux-hardware.org/?probe=050678128c) | Jun 29, 2022 |
| Dell          | Latitude 3590               | Notebook    | [b5d4509068](https://linux-hardware.org/?probe=b5d4509068) | Jun 29, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [ff60a3cb61](https://linux-hardware.org/?probe=ff60a3cb61) | Jun 28, 2022 |
| HP            | ProBook 455 G4              | Notebook    | [f54297787f](https://linux-hardware.org/?probe=f54297787f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [ec155fca3f](https://linux-hardware.org/?probe=ec155fca3f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [016ee6ec73](https://linux-hardware.org/?probe=016ee6ec73) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [af267c59cd](https://linux-hardware.org/?probe=af267c59cd) | Jun 28, 2022 |
| HP            | 8054                        | Desktop     | [82dd44f05f](https://linux-hardware.org/?probe=82dd44f05f) | Jun 26, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [90c166f77b](https://linux-hardware.org/?probe=90c166f77b) | Jun 25, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [3e16709617](https://linux-hardware.org/?probe=3e16709617) | Jun 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [21d2b9f0fb](https://linux-hardware.org/?probe=21d2b9f0fb) | Jun 23, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [92944b1e97](https://linux-hardware.org/?probe=92944b1e97) | Jun 22, 2022 |
| HP            | 3646h                       | Desktop     | [d27deccf27](https://linux-hardware.org/?probe=d27deccf27) | Jun 22, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [77c5ca4f1e](https://linux-hardware.org/?probe=77c5ca4f1e) | Jun 22, 2022 |
| HP            | 255 G3                      | Notebook    | [def96ad707](https://linux-hardware.org/?probe=def96ad707) | Jun 21, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [465ffdd126](https://linux-hardware.org/?probe=465ffdd126) | Jun 21, 2022 |
| Dell          | Latitude 3590               | Notebook    | [fdfd4be1e2](https://linux-hardware.org/?probe=fdfd4be1e2) | Jun 21, 2022 |
| System76      | Lemur Pro                   | Notebook    | [38b04af23d](https://linux-hardware.org/?probe=38b04af23d) | Jun 20, 2022 |
| ASUSTek       | UX410UAK                    | Notebook    | [0d2e384ebf](https://linux-hardware.org/?probe=0d2e384ebf) | Jun 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [4e35a154b5](https://linux-hardware.org/?probe=4e35a154b5) | Jun 18, 2022 |
| Toshiba       | Satellite-L845              | Notebook    | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [a56ff0b014](https://linux-hardware.org/?probe=a56ff0b014) | Jun 18, 2022 |
| ASRock        | G41M-GS                     | Desktop     | [9167934132](https://linux-hardware.org/?probe=9167934132) | Jun 18, 2022 |
| HP            | 0A60h                       | Desktop     | [cb42238223](https://linux-hardware.org/?probe=cb42238223) | Jun 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [9481bad179](https://linux-hardware.org/?probe=9481bad179) | Jun 17, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7eee6145a1](https://linux-hardware.org/?probe=7eee6145a1) | Jun 16, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [41495c085a](https://linux-hardware.org/?probe=41495c085a) | Jun 16, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [4e33fa1a1d](https://linux-hardware.org/?probe=4e33fa1a1d) | Jun 15, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [71f9801165](https://linux-hardware.org/?probe=71f9801165) | Jun 15, 2022 |
| MSI           | 3664h                       | Desktop     | [5fbb22c653](https://linux-hardware.org/?probe=5fbb22c653) | Jun 15, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [9916ed24a9](https://linux-hardware.org/?probe=9916ed24a9) | Jun 15, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [a3f29fd594](https://linux-hardware.org/?probe=a3f29fd594) | Jun 14, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [c8b26ae553](https://linux-hardware.org/?probe=c8b26ae553) | Jun 13, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [cdc0b49b72](https://linux-hardware.org/?probe=cdc0b49b72) | Jun 13, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [52efea465c](https://linux-hardware.org/?probe=52efea465c) | Jun 12, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [731e6f4aa8](https://linux-hardware.org/?probe=731e6f4aa8) | Jun 12, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [cae8181e7d](https://linux-hardware.org/?probe=cae8181e7d) | Jun 11, 2022 |
| Gadnic        | NOT00A1                     | Notebook    | [d63fbf4c2e](https://linux-hardware.org/?probe=d63fbf4c2e) | Jun 10, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [82aa782cce](https://linux-hardware.org/?probe=82aa782cce) | Jun 08, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [9ae6cc8594](https://linux-hardware.org/?probe=9ae6cc8594) | Jun 07, 2022 |
| ASRock        | H55M                        | Desktop     | [058eceb951](https://linux-hardware.org/?probe=058eceb951) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [ea589a3279](https://linux-hardware.org/?probe=ea589a3279) | Jun 07, 2022 |
| ASRock        | Z97M Anniversary            | Desktop     | [1855124dd3](https://linux-hardware.org/?probe=1855124dd3) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [09d190612b](https://linux-hardware.org/?probe=09d190612b) | Jun 06, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [b3a7546aa9](https://linux-hardware.org/?probe=b3a7546aa9) | Jun 06, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [6c408a6fd7](https://linux-hardware.org/?probe=6c408a6fd7) | Jun 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [321300f927](https://linux-hardware.org/?probe=321300f927) | Jun 01, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [94a496851b](https://linux-hardware.org/?probe=94a496851b) | Jun 01, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [ec364402d8](https://linux-hardware.org/?probe=ec364402d8) | May 31, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [d24672a3cd](https://linux-hardware.org/?probe=d24672a3cd) | May 31, 2022 |
| Positivo      | ONE700                      | All in one  | [0675afbbfb](https://linux-hardware.org/?probe=0675afbbfb) | May 29, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [30be732591](https://linux-hardware.org/?probe=30be732591) | May 29, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [7fd1e065eb](https://linux-hardware.org/?probe=7fd1e065eb) | May 29, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | Notebook    | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [8546d9cf10](https://linux-hardware.org/?probe=8546d9cf10) | May 27, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [bb0591d5c8](https://linux-hardware.org/?probe=bb0591d5c8) | May 26, 2022 |
| Juana Mans... | SF20GM7                     | Notebook    | [2078b0ab3f](https://linux-hardware.org/?probe=2078b0ab3f) | May 26, 2022 |
| American M... | K7S41GX                     | Desktop     | [b311270c22](https://linux-hardware.org/?probe=b311270c22) | May 26, 2022 |
| ASRock        | Z270 Gaming K6              | Desktop     | [fbf8e08024](https://linux-hardware.org/?probe=fbf8e08024) | May 25, 2022 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [36e5918bc8](https://linux-hardware.org/?probe=36e5918bc8) | May 25, 2022 |
| Positivo      | AT510                       | Notebook    | [2845c5ebd6](https://linux-hardware.org/?probe=2845c5ebd6) | May 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0754e1c6e6](https://linux-hardware.org/?probe=0754e1c6e6) | May 23, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [e59616f367](https://linux-hardware.org/?probe=e59616f367) | May 23, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [2cd1f7fd5e](https://linux-hardware.org/?probe=2cd1f7fd5e) | May 23, 2022 |
| Toshiba       | Unknown                     | Notebook    | [56ac954440](https://linux-hardware.org/?probe=56ac954440) | May 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [900181bbff](https://linux-hardware.org/?probe=900181bbff) | May 22, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6d384d3502](https://linux-hardware.org/?probe=6d384d3502) | May 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa4b76df10](https://linux-hardware.org/?probe=aa4b76df10) | May 21, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [830532746e](https://linux-hardware.org/?probe=830532746e) | May 20, 2022 |
| Dell          | Inspiron 3502               | Notebook    | [0d26fe46da](https://linux-hardware.org/?probe=0d26fe46da) | May 19, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [27289062cb](https://linux-hardware.org/?probe=27289062cb) | May 19, 2022 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | Desktop     | [ea23b1fec2](https://linux-hardware.org/?probe=ea23b1fec2) | May 18, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [13bacdb7b6](https://linux-hardware.org/?probe=13bacdb7b6) | May 18, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [66a07f5e71](https://linux-hardware.org/?probe=66a07f5e71) | May 18, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [3856a337bb](https://linux-hardware.org/?probe=3856a337bb) | May 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [2b8318661b](https://linux-hardware.org/?probe=2b8318661b) | May 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [09c8ff393f](https://linux-hardware.org/?probe=09c8ff393f) | May 16, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [3e3380c801](https://linux-hardware.org/?probe=3e3380c801) | May 15, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [fd15b34806](https://linux-hardware.org/?probe=fd15b34806) | May 13, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [5af3adc742](https://linux-hardware.org/?probe=5af3adc742) | May 13, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [40d9831b29](https://linux-hardware.org/?probe=40d9831b29) | May 12, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [d3088d7665](https://linux-hardware.org/?probe=d3088d7665) | May 11, 2022 |
| Positivo      | AT300b                      | Notebook    | [7f5c5ceed4](https://linux-hardware.org/?probe=7f5c5ceed4) | May 11, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [ba9835cb43](https://linux-hardware.org/?probe=ba9835cb43) | May 10, 2022 |
| Dell          | Latitude E6430              | Notebook    | [a188e200b3](https://linux-hardware.org/?probe=a188e200b3) | May 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Foxconn       | LIMA                        | Desktop     | [fc4662a00e](https://linux-hardware.org/?probe=fc4662a00e) | May 09, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ed1e3083d6](https://linux-hardware.org/?probe=ed1e3083d6) | May 09, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [422c9f9cae](https://linux-hardware.org/?probe=422c9f9cae) | May 09, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [f84e562503](https://linux-hardware.org/?probe=f84e562503) | May 06, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [76e6cc98aa](https://linux-hardware.org/?probe=76e6cc98aa) | May 05, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [40f4bf344a](https://linux-hardware.org/?probe=40f4bf344a) | May 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5a8fc607c4](https://linux-hardware.org/?probe=5a8fc607c4) | May 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3be0a0d66d](https://linux-hardware.org/?probe=3be0a0d66d) | May 03, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [8a7d82f85b](https://linux-hardware.org/?probe=8a7d82f85b) | May 03, 2022 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [f3791f34b1](https://linux-hardware.org/?probe=f3791f34b1) | May 02, 2022 |
| Intel         | powered classmate PC        | Tablet      | [61790801c2](https://linux-hardware.org/?probe=61790801c2) | May 01, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [dc1b877e42](https://linux-hardware.org/?probe=dc1b877e42) | May 01, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [48d3759522](https://linux-hardware.org/?probe=48d3759522) | Apr 30, 2022 |
| NSX           | SB1402                      | Notebook    | [c9d79a4fe5](https://linux-hardware.org/?probe=c9d79a4fe5) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b92517268e](https://linux-hardware.org/?probe=b92517268e) | Apr 30, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d3872db37e](https://linux-hardware.org/?probe=d3872db37e) | Apr 29, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [2cfdf9b28a](https://linux-hardware.org/?probe=2cfdf9b28a) | Apr 29, 2022 |
| Dell          | Latitude 5411               | Notebook    | [34c470e595](https://linux-hardware.org/?probe=34c470e595) | Apr 28, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [d7757bf097](https://linux-hardware.org/?probe=d7757bf097) | Apr 27, 2022 |
| NOBLEX        | N14WD21                     | Notebook    | [a8a7a4e1d5](https://linux-hardware.org/?probe=a8a7a4e1d5) | Apr 27, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [bf0a56358c](https://linux-hardware.org/?probe=bf0a56358c) | Apr 27, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| MSI           | 880GMA-E35                  | Desktop     | [6ff68166f7](https://linux-hardware.org/?probe=6ff68166f7) | Apr 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [00728feb75](https://linux-hardware.org/?probe=00728feb75) | Apr 26, 2022 |
| Lenovo        | ThinkPad E470 20H1A01YAC    | Notebook    | [cd8726de3c](https://linux-hardware.org/?probe=cd8726de3c) | Apr 26, 2022 |
| Dell          | Studio 1558                 | Notebook    | [b31435ef0c](https://linux-hardware.org/?probe=b31435ef0c) | Apr 24, 2022 |
| HP            | Notebook                    | Notebook    | [339f862ddd](https://linux-hardware.org/?probe=339f862ddd) | Apr 24, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [fb612cbcd5](https://linux-hardware.org/?probe=fb612cbcd5) | Apr 24, 2022 |
| ASUSTek       | X556UB                      | Notebook    | [a9d2922649](https://linux-hardware.org/?probe=a9d2922649) | Apr 23, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [86f45617ad](https://linux-hardware.org/?probe=86f45617ad) | Apr 22, 2022 |
| ASUSTek       | K53E                        | Notebook    | [14e628cbba](https://linux-hardware.org/?probe=14e628cbba) | Apr 22, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [d66e41c50e](https://linux-hardware.org/?probe=d66e41c50e) | Apr 22, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [c021555957](https://linux-hardware.org/?probe=c021555957) | Apr 21, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e7b66178ce](https://linux-hardware.org/?probe=e7b66178ce) | Apr 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6454c55f08](https://linux-hardware.org/?probe=6454c55f08) | Apr 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c00611352d](https://linux-hardware.org/?probe=c00611352d) | Apr 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f28318e17b](https://linux-hardware.org/?probe=f28318e17b) | Apr 14, 2022 |
| Dell          | Latitude E7250              | Notebook    | [2d0ac286da](https://linux-hardware.org/?probe=2d0ac286da) | Apr 14, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [624c5a033e](https://linux-hardware.org/?probe=624c5a033e) | Apr 14, 2022 |
| Dell          | Latitude 3520               | Notebook    | [8003f0258a](https://linux-hardware.org/?probe=8003f0258a) | Apr 14, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [a5a366f7e7](https://linux-hardware.org/?probe=a5a366f7e7) | Apr 13, 2022 |
| MSI           | H81M-E33                    | Desktop     | [460099f77f](https://linux-hardware.org/?probe=460099f77f) | Apr 13, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [9bcf0f1e4f](https://linux-hardware.org/?probe=9bcf0f1e4f) | Apr 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [52e0e2e934](https://linux-hardware.org/?probe=52e0e2e934) | Apr 12, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [d93ab23121](https://linux-hardware.org/?probe=d93ab23121) | Apr 10, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [de3e230ca3](https://linux-hardware.org/?probe=de3e230ca3) | Apr 10, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [cfa5407b7f](https://linux-hardware.org/?probe=cfa5407b7f) | Apr 10, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [48e5060f20](https://linux-hardware.org/?probe=48e5060f20) | Apr 10, 2022 |
| Unknown       | P4M800CE-8237               | Desktop     | [4c6b9a3f5e](https://linux-hardware.org/?probe=4c6b9a3f5e) | Apr 06, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [a19db5a006](https://linux-hardware.org/?probe=a19db5a006) | Apr 05, 2022 |
| Advantec      | CX23500W                    | Notebook    | [a3152e0a0f](https://linux-hardware.org/?probe=a3152e0a0f) | Apr 02, 2022 |
| Advantec      | CX23500W                    | Notebook    | [feb5c20169](https://linux-hardware.org/?probe=feb5c20169) | Apr 02, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [ddfbf2df5e](https://linux-hardware.org/?probe=ddfbf2df5e) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [5a8ee938ce](https://linux-hardware.org/?probe=5a8ee938ce) | Apr 01, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| Exo           | Smart XQ5c                  | Notebook    | [5653a02bd3](https://linux-hardware.org/?probe=5653a02bd3) | Mar 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [14bd2cc137](https://linux-hardware.org/?probe=14bd2cc137) | Mar 31, 2022 |
| Dell          | Latitude 3410               | Notebook    | [fd37f4137d](https://linux-hardware.org/?probe=fd37f4137d) | Mar 30, 2022 |
| MSI           | MS-7388                     | Desktop     | [d5eabb8266](https://linux-hardware.org/?probe=d5eabb8266) | Mar 30, 2022 |
| Kanji         | Tamura MAX DUO              | Convertible | [1434c90e55](https://linux-hardware.org/?probe=1434c90e55) | Mar 30, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f815e79449](https://linux-hardware.org/?probe=f815e79449) | Mar 30, 2022 |
| Lenovo        | V15-G2-ITL 82KB             | Notebook    | [38700103d3](https://linux-hardware.org/?probe=38700103d3) | Mar 29, 2022 |
| Toshiba       | PORTEGE R935                | Notebook    | [b209a8e000](https://linux-hardware.org/?probe=b209a8e000) | Mar 28, 2022 |
| HP            | 81BB                        | All in one  | [cb07426c3e](https://linux-hardware.org/?probe=cb07426c3e) | Mar 28, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [dfc5a02c31](https://linux-hardware.org/?probe=dfc5a02c31) | Mar 28, 2022 |
| Gigabyte      | Z490 AORUS ELITE            | Desktop     | [f8c03d6697](https://linux-hardware.org/?probe=f8c03d6697) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [92bbba70b0](https://linux-hardware.org/?probe=92bbba70b0) | Mar 28, 2022 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [dd1e7b6c4d](https://linux-hardware.org/?probe=dd1e7b6c4d) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [981757ce36](https://linux-hardware.org/?probe=981757ce36) | Mar 28, 2022 |
| HP            | 81BB                        | All in one  | [d3fec7d8f4](https://linux-hardware.org/?probe=d3fec7d8f4) | Mar 28, 2022 |
| Positivo      | Z100                        | Notebook    | [5577927db3](https://linux-hardware.org/?probe=5577927db3) | Mar 27, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [87a81b14f0](https://linux-hardware.org/?probe=87a81b14f0) | Mar 25, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b5ee1f293e](https://linux-hardware.org/?probe=b5ee1f293e) | Mar 25, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [d809ca0f7a](https://linux-hardware.org/?probe=d809ca0f7a) | Mar 25, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [2e006b534b](https://linux-hardware.org/?probe=2e006b534b) | Mar 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [984b59ccb9](https://linux-hardware.org/?probe=984b59ccb9) | Mar 24, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [90ce7b8310](https://linux-hardware.org/?probe=90ce7b8310) | Mar 24, 2022 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [d3623fd756](https://linux-hardware.org/?probe=d3623fd756) | Mar 24, 2022 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [1057b723a8](https://linux-hardware.org/?probe=1057b723a8) | Mar 24, 2022 |
| BGH e-Nova    | Unknown                     | Notebook    | [408be10e82](https://linux-hardware.org/?probe=408be10e82) | Mar 22, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b7444c471c](https://linux-hardware.org/?probe=b7444c471c) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [1fbe976538](https://linux-hardware.org/?probe=1fbe976538) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b664a23750](https://linux-hardware.org/?probe=b664a23750) | Mar 21, 2022 |
| HP            | 8054                        | Desktop     | [38288fadf8](https://linux-hardware.org/?probe=38288fadf8) | Mar 21, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [c845b9c738](https://linux-hardware.org/?probe=c845b9c738) | Mar 21, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [0008f2b843](https://linux-hardware.org/?probe=0008f2b843) | Mar 20, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [34d7600473](https://linux-hardware.org/?probe=34d7600473) | Mar 20, 2022 |
| BANGHO        | MAX G0101                   | Notebook    | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [bd7accdfd5](https://linux-hardware.org/?probe=bd7accdfd5) | Mar 20, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [555255cb84](https://linux-hardware.org/?probe=555255cb84) | Mar 19, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [116074683a](https://linux-hardware.org/?probe=116074683a) | Mar 19, 2022 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [2e70de8c8d](https://linux-hardware.org/?probe=2e70de8c8d) | Mar 19, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [74bdda89c3](https://linux-hardware.org/?probe=74bdda89c3) | Mar 18, 2022 |
| NSX           | SB142G                      | Notebook    | [0a13591ca3](https://linux-hardware.org/?probe=0a13591ca3) | Mar 18, 2022 |
| ASUSTek       | X505BP                      | Notebook    | [3dc5b19d13](https://linux-hardware.org/?probe=3dc5b19d13) | Mar 17, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b2ec039a2e](https://linux-hardware.org/?probe=b2ec039a2e) | Mar 17, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [39b60a2ef4](https://linux-hardware.org/?probe=39b60a2ef4) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [25c0bbffe2](https://linux-hardware.org/?probe=25c0bbffe2) | Mar 15, 2022 |
| Lenovo        | Edge 15 80H1                | Notebook    | [bd2b981053](https://linux-hardware.org/?probe=bd2b981053) | Mar 14, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7e32829960](https://linux-hardware.org/?probe=7e32829960) | Mar 13, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [5d8f77310a](https://linux-hardware.org/?probe=5d8f77310a) | Mar 11, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [c31b5d363f](https://linux-hardware.org/?probe=c31b5d363f) | Mar 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [fc3707d356](https://linux-hardware.org/?probe=fc3707d356) | Mar 09, 2022 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [5aa4d54781](https://linux-hardware.org/?probe=5aa4d54781) | Mar 09, 2022 |
| NOBLEX        | N14WD21                     | Notebook    | [c166ec8175](https://linux-hardware.org/?probe=c166ec8175) | Mar 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [96833919d2](https://linux-hardware.org/?probe=96833919d2) | Mar 08, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [7708a6ffb9](https://linux-hardware.org/?probe=7708a6ffb9) | Mar 07, 2022 |
| ASRock        | G41M-S3                     | Desktop     | [a5d8ab9493](https://linux-hardware.org/?probe=a5d8ab9493) | Mar 07, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | Notebook    | [3a01549416](https://linux-hardware.org/?probe=3a01549416) | Mar 06, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | Notebook    | [48d2d5d234](https://linux-hardware.org/?probe=48d2d5d234) | Mar 06, 2022 |
| Dell          | Latitude E5540              | Notebook    | [52a16c13b1](https://linux-hardware.org/?probe=52a16c13b1) | Mar 06, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [eca1413f3f](https://linux-hardware.org/?probe=eca1413f3f) | Mar 04, 2022 |
| Nvidia        | Tegra                       | Soc         | [904f2d4f21](https://linux-hardware.org/?probe=904f2d4f21) | Feb 28, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [e79a48e141](https://linux-hardware.org/?probe=e79a48e141) | Feb 27, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d4a3fb2dfc](https://linux-hardware.org/?probe=d4a3fb2dfc) | Feb 26, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [65eae3fe4c](https://linux-hardware.org/?probe=65eae3fe4c) | Feb 25, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [bf565614ca](https://linux-hardware.org/?probe=bf565614ca) | Feb 24, 2022 |
| ASRock        | G31M-S                      | Desktop     | [1ecf0fe3af](https://linux-hardware.org/?probe=1ecf0fe3af) | Feb 24, 2022 |
| Lenovo        | ChiefRiver                  | All in one  | [019a150df4](https://linux-hardware.org/?probe=019a150df4) | Feb 23, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [3f99c8072a](https://linux-hardware.org/?probe=3f99c8072a) | Feb 23, 2022 |
| Lenovo        | V15-G2-ITL 82KB             | Notebook    | [6d10cb57e1](https://linux-hardware.org/?probe=6d10cb57e1) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [09aca1c435](https://linux-hardware.org/?probe=09aca1c435) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [35c00d5889](https://linux-hardware.org/?probe=35c00d5889) | Feb 22, 2022 |
| ASRock        | K10N78M                     | Desktop     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [265235f4f4](https://linux-hardware.org/?probe=265235f4f4) | Feb 21, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [747899db53](https://linux-hardware.org/?probe=747899db53) | Feb 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [2a57fc9391](https://linux-hardware.org/?probe=2a57fc9391) | Feb 20, 2022 |
| ASUSTek       | X55C                        | Notebook    | [ae05784a4a](https://linux-hardware.org/?probe=ae05784a4a) | Feb 19, 2022 |
| Samsung       | SQ35S                       | Notebook    | [7f4f9ad483](https://linux-hardware.org/?probe=7f4f9ad483) | Feb 18, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [d9f8a4991e](https://linux-hardware.org/?probe=d9f8a4991e) | Feb 18, 2022 |
| Advantec      | C15B                        | Desktop     | [708b68ac89](https://linux-hardware.org/?probe=708b68ac89) | Feb 17, 2022 |
| ASUSTek       | PRIME Z270M-PLUS            | Desktop     | [0faabbb741](https://linux-hardware.org/?probe=0faabbb741) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [da103e44c5](https://linux-hardware.org/?probe=da103e44c5) | Feb 17, 2022 |
| ASUSTek       | X540UA                      | Notebook    | [681b4aca6f](https://linux-hardware.org/?probe=681b4aca6f) | Feb 16, 2022 |
| Radio Vict... | B34 SLIM                    | Notebook    | [8a100feae7](https://linux-hardware.org/?probe=8a100feae7) | Feb 16, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [0937e1da6a](https://linux-hardware.org/?probe=0937e1da6a) | Feb 14, 2022 |
| Dell          | 0RF705                      | Desktop     | [4369e75c27](https://linux-hardware.org/?probe=4369e75c27) | Feb 14, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [581ebd9976](https://linux-hardware.org/?probe=581ebd9976) | Feb 13, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [fc4efd1eff](https://linux-hardware.org/?probe=fc4efd1eff) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| ASRock        | H55M                        | Desktop     | [85a293bc45](https://linux-hardware.org/?probe=85a293bc45) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [196bd41500](https://linux-hardware.org/?probe=196bd41500) | Feb 12, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [e189ec36c5](https://linux-hardware.org/?probe=e189ec36c5) | Feb 12, 2022 |
| MSI           | GP72 6QE                    | Notebook    | [d4a2d3bb85](https://linux-hardware.org/?probe=d4a2d3bb85) | Feb 12, 2022 |
| MSI           | GP72 6QE                    | Notebook    | [9409e22a95](https://linux-hardware.org/?probe=9409e22a95) | Feb 12, 2022 |
| ASRock        | G31M-S                      | Desktop     | [0e52738a23](https://linux-hardware.org/?probe=0e52738a23) | Feb 11, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [b04de36c04](https://linux-hardware.org/?probe=b04de36c04) | Feb 11, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [0f65488b54](https://linux-hardware.org/?probe=0f65488b54) | Feb 11, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [da554d50b7](https://linux-hardware.org/?probe=da554d50b7) | Feb 10, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| BANGHO        | Suma 1025                   | Tablet      | [585ea8c657](https://linux-hardware.org/?probe=585ea8c657) | Feb 10, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [fc6c97721c](https://linux-hardware.org/?probe=fc6c97721c) | Feb 09, 2022 |
| Sony          | VJFE52A0711H                | Notebook    | [0a29c49c46](https://linux-hardware.org/?probe=0a29c49c46) | Feb 09, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [5beef7a5b1](https://linux-hardware.org/?probe=5beef7a5b1) | Feb 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [c71db9d118](https://linux-hardware.org/?probe=c71db9d118) | Feb 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [61aae88463](https://linux-hardware.org/?probe=61aae88463) | Feb 08, 2022 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [c4cba809c4](https://linux-hardware.org/?probe=c4cba809c4) | Feb 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [dbfba11836](https://linux-hardware.org/?probe=dbfba11836) | Feb 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [b6df9d3243](https://linux-hardware.org/?probe=b6df9d3243) | Feb 08, 2022 |
| HP            | Pavilion dv6                | Notebook    | [0ba10bc3bb](https://linux-hardware.org/?probe=0ba10bc3bb) | Feb 07, 2022 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [c6783b6b8b](https://linux-hardware.org/?probe=c6783b6b8b) | Feb 07, 2022 |
| HP            | 0A60h                       | Desktop     | [8c9b5ec56f](https://linux-hardware.org/?probe=8c9b5ec56f) | Feb 06, 2022 |
| Unknown       | 865G-M8                     | Desktop     | [ecc67cf3bc](https://linux-hardware.org/?probe=ecc67cf3bc) | Feb 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [c1fe9c81a0](https://linux-hardware.org/?probe=c1fe9c81a0) | Feb 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f92b5e4b44](https://linux-hardware.org/?probe=f92b5e4b44) | Feb 06, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0e2c677ddc](https://linux-hardware.org/?probe=0e2c677ddc) | Feb 03, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [fa4a95f3a5](https://linux-hardware.org/?probe=fa4a95f3a5) | Feb 03, 2022 |
| ASUSTek       | Maximus V GENE              | Desktop     | [749946734b](https://linux-hardware.org/?probe=749946734b) | Feb 03, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [23987146db](https://linux-hardware.org/?probe=23987146db) | Feb 02, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [a5298ee805](https://linux-hardware.org/?probe=a5298ee805) | Feb 02, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c7af52d518](https://linux-hardware.org/?probe=c7af52d518) | Feb 02, 2022 |
| Gigabyte      | A320M-HD2-CF                | Desktop     | [6ad345c1a5](https://linux-hardware.org/?probe=6ad345c1a5) | Feb 01, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | Desktop     | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [88085159bf](https://linux-hardware.org/?probe=88085159bf) | Jan 31, 2022 |
| Dell          | 0NX183 A01                  | Desktop     | [54e546f9ae](https://linux-hardware.org/?probe=54e546f9ae) | Jan 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c1494af863](https://linux-hardware.org/?probe=c1494af863) | Jan 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [690eba21e0](https://linux-hardware.org/?probe=690eba21e0) | Jan 30, 2022 |
| Unknown       | P4M800CE-8237               | Desktop     | [ff8ade4a5a](https://linux-hardware.org/?probe=ff8ade4a5a) | Jan 28, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [350f00e69f](https://linux-hardware.org/?probe=350f00e69f) | Jan 27, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [343ab23f97](https://linux-hardware.org/?probe=343ab23f97) | Jan 27, 2022 |
| Lenovo        | G40-80 80E4                 | Notebook    | [4c27ace709](https://linux-hardware.org/?probe=4c27ace709) | Jan 26, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [62e942ea94](https://linux-hardware.org/?probe=62e942ea94) | Jan 26, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [f8afc9746e](https://linux-hardware.org/?probe=f8afc9746e) | Jan 24, 2022 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [72a04dc661](https://linux-hardware.org/?probe=72a04dc661) | Jan 22, 2022 |
| Standard      | MB50II                      | Notebook    | [aa719e1665](https://linux-hardware.org/?probe=aa719e1665) | Jan 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [0f956f27ad](https://linux-hardware.org/?probe=0f956f27ad) | Jan 20, 2022 |
| Gadnic        | NOT00A1                     | Notebook    | [f1c6b56aa2](https://linux-hardware.org/?probe=f1c6b56aa2) | Jan 18, 2022 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [a6302c118b](https://linux-hardware.org/?probe=a6302c118b) | Jan 17, 2022 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [8a0c194baa](https://linux-hardware.org/?probe=8a0c194baa) | Jan 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b2ac4f1622](https://linux-hardware.org/?probe=b2ac4f1622) | Jan 13, 2022 |
| BANGHO        | MAX G0101                   | Notebook    | [0e5d4dfabf](https://linux-hardware.org/?probe=0e5d4dfabf) | Jan 13, 2022 |
| MSI           | MS-7309                     | Desktop     | [b980404ce1](https://linux-hardware.org/?probe=b980404ce1) | Jan 13, 2022 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [b5437027b1](https://linux-hardware.org/?probe=b5437027b1) | Jan 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2b44f3e733](https://linux-hardware.org/?probe=2b44f3e733) | Jan 12, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [137736d936](https://linux-hardware.org/?probe=137736d936) | Jan 11, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [7d5ceb70bb](https://linux-hardware.org/?probe=7d5ceb70bb) | Jan 10, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [6b1eb1745e](https://linux-hardware.org/?probe=6b1eb1745e) | Jan 10, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [50adc5f773](https://linux-hardware.org/?probe=50adc5f773) | Jan 08, 2022 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [1f828632ed](https://linux-hardware.org/?probe=1f828632ed) | Jan 07, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [9ac42b2131](https://linux-hardware.org/?probe=9ac42b2131) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [e8bc9392ff](https://linux-hardware.org/?probe=e8bc9392ff) | Jan 04, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [35c962a07f](https://linux-hardware.org/?probe=35c962a07f) | Jan 02, 2022 |
| VS Company    | MCP61M                      | Desktop     | [8009a6fbdf](https://linux-hardware.org/?probe=8009a6fbdf) | Jan 02, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b6b0572310](https://linux-hardware.org/?probe=b6b0572310) | Jan 02, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [dfa1412d12](https://linux-hardware.org/?probe=dfa1412d12) | Jan 01, 2022 |
| HP            | 0A60h                       | Desktop     | [2812050060](https://linux-hardware.org/?probe=2812050060) | Jan 01, 2022 |
| Dell          | Latitude E5540              | Notebook    | [1a112d75bc](https://linux-hardware.org/?probe=1a112d75bc) | Jan 01, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [4754d83d04](https://linux-hardware.org/?probe=4754d83d04) | Jan 01, 2022 |
| Exo           | HR14                        | Notebook    | [3a16049e36](https://linux-hardware.org/?probe=3a16049e36) | Dec 31, 2021 |
| Exo           | HR14                        | Notebook    | [8c3bf46eb1](https://linux-hardware.org/?probe=8c3bf46eb1) | Dec 31, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [c05333a0bc](https://linux-hardware.org/?probe=c05333a0bc) | Dec 31, 2021 |
| Intel         | Crestline & ICH8M Chipse... | Notebook    | [286566a874](https://linux-hardware.org/?probe=286566a874) | Dec 31, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9d60e196d4](https://linux-hardware.org/?probe=9d60e196d4) | Dec 31, 2021 |
| Lenovo        | G40-80 80E4                 | Notebook    | [993fe7cef6](https://linux-hardware.org/?probe=993fe7cef6) | Dec 30, 2021 |
| HP            | 15                          | Notebook    | [e0d79905e2](https://linux-hardware.org/?probe=e0d79905e2) | Dec 29, 2021 |
| Lenovo        | G470 20078                  | Notebook    | [d860437585](https://linux-hardware.org/?probe=d860437585) | Dec 28, 2021 |
| Intel         | DG965WH AAD41692-305        | Desktop     | [970dba93b8](https://linux-hardware.org/?probe=970dba93b8) | Dec 28, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [8c9f72d757](https://linux-hardware.org/?probe=8c9f72d757) | Dec 27, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [d02d1bb775](https://linux-hardware.org/?probe=d02d1bb775) | Dec 27, 2021 |
| System76      | Lemur Pro                   | Notebook    | [6dbfd95ccb](https://linux-hardware.org/?probe=6dbfd95ccb) | Dec 27, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d8a2a90482](https://linux-hardware.org/?probe=d8a2a90482) | Dec 27, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d2e019564f](https://linux-hardware.org/?probe=d2e019564f) | Dec 26, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [63b3337725](https://linux-hardware.org/?probe=63b3337725) | Dec 26, 2021 |
| Dell          | Inspiron 7791 2n1           | Convertible | [b5887ff3fd](https://linux-hardware.org/?probe=b5887ff3fd) | Dec 25, 2021 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [ab7902b875](https://linux-hardware.org/?probe=ab7902b875) | Dec 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [da08b0d873](https://linux-hardware.org/?probe=da08b0d873) | Dec 22, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [64492ac63b](https://linux-hardware.org/?probe=64492ac63b) | Dec 22, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [8df64a7f80](https://linux-hardware.org/?probe=8df64a7f80) | Dec 21, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [ce7e7de4b4](https://linux-hardware.org/?probe=ce7e7de4b4) | Dec 20, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [aaab97a820](https://linux-hardware.org/?probe=aaab97a820) | Dec 19, 2021 |
| Dell          | 0RF705                      | Desktop     | [b28693bf2b](https://linux-hardware.org/?probe=b28693bf2b) | Dec 19, 2021 |
| System76      | Lemur Pro                   | Notebook    | [aebe0acb39](https://linux-hardware.org/?probe=aebe0acb39) | Dec 18, 2021 |
| Compaq        | Presario 21                 | Notebook    | [86e7a85db3](https://linux-hardware.org/?probe=86e7a85db3) | Dec 16, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [915303d28d](https://linux-hardware.org/?probe=915303d28d) | Dec 16, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [15d1b4bba5](https://linux-hardware.org/?probe=15d1b4bba5) | Dec 16, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [4c02cd3e26](https://linux-hardware.org/?probe=4c02cd3e26) | Dec 15, 2021 |
| Lenovo        | ThinkPad X230 23254UY       | Notebook    | [99dbb19723](https://linux-hardware.org/?probe=99dbb19723) | Dec 15, 2021 |
| HONOR         | HLYL-WXX9                   | Notebook    | [0b6a9394b4](https://linux-hardware.org/?probe=0b6a9394b4) | Dec 15, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [bc401cc9a6](https://linux-hardware.org/?probe=bc401cc9a6) | Dec 14, 2021 |
| Lenovo        | ThinkPad X230 23252CG       | Notebook    | [e2ed9e27c3](https://linux-hardware.org/?probe=e2ed9e27c3) | Dec 14, 2021 |
| Gigabyte      | H510M H                     | Desktop     | [e66c15a464](https://linux-hardware.org/?probe=e66c15a464) | Dec 13, 2021 |
| Gigabyte      | H510M H                     | Desktop     | [53588115a6](https://linux-hardware.org/?probe=53588115a6) | Dec 13, 2021 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [903dfc6f62](https://linux-hardware.org/?probe=903dfc6f62) | Dec 13, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [9c83d97134](https://linux-hardware.org/?probe=9c83d97134) | Dec 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [6df961216e](https://linux-hardware.org/?probe=6df961216e) | Dec 12, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [60cdd8ce45](https://linux-hardware.org/?probe=60cdd8ce45) | Dec 11, 2021 |
| Quanta        | 2AC5                        | Desktop     | [0e0fcca430](https://linux-hardware.org/?probe=0e0fcca430) | Dec 10, 2021 |
| Quanta        | 2AC5                        | Desktop     | [d0c9fba2a4](https://linux-hardware.org/?probe=d0c9fba2a4) | Dec 10, 2021 |
| Toshiba       | TE5                         | Notebook    | [fb39721f00](https://linux-hardware.org/?probe=fb39721f00) | Dec 10, 2021 |
| ASRock        | QC6000M                     | Desktop     | [3475206cb1](https://linux-hardware.org/?probe=3475206cb1) | Dec 10, 2021 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [44fb1a2d77](https://linux-hardware.org/?probe=44fb1a2d77) | Dec 09, 2021 |
| Gigabyte      | H410M H                     | Desktop     | [a1b80c28f2](https://linux-hardware.org/?probe=a1b80c28f2) | Dec 09, 2021 |
| System76      | Lemur Pro                   | Notebook    | [6e54a15cf2](https://linux-hardware.org/?probe=6e54a15cf2) | Dec 08, 2021 |
| Exo           | C14C                        | Notebook    | [2e0765b245](https://linux-hardware.org/?probe=2e0765b245) | Dec 08, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [b041919f38](https://linux-hardware.org/?probe=b041919f38) | Dec 08, 2021 |
| Exo           | C14C                        | Notebook    | [1d4221ab9e](https://linux-hardware.org/?probe=1d4221ab9e) | Dec 06, 2021 |
| Positivo      | AT300b                      | Notebook    | [20b3635188](https://linux-hardware.org/?probe=20b3635188) | Dec 06, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [adf5a1b645](https://linux-hardware.org/?probe=adf5a1b645) | Dec 04, 2021 |
| Acer          | Aspire 5251                 | Notebook    | [30ef0eefda](https://linux-hardware.org/?probe=30ef0eefda) | Dec 04, 2021 |
| Intel         | powered classmate PC        | Tablet      | [09bfb979b0](https://linux-hardware.org/?probe=09bfb979b0) | Dec 03, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [4c79974ae8](https://linux-hardware.org/?probe=4c79974ae8) | Dec 03, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3f21e28b42](https://linux-hardware.org/?probe=3f21e28b42) | Dec 03, 2021 |
| Biostar       | NF61V-M2                    | Desktop     | [0d21d633c9](https://linux-hardware.org/?probe=0d21d633c9) | Dec 02, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Argentina/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 243       | 12.95%  |
| Ubuntu 18.04                 | 175       | 9.33%   |
| Ubuntu 22.04                 | 96        | 5.12%   |
| Debian 11                    | 65        | 3.46%   |
| OpenMandriva 4.2             | 56        | 2.99%   |
| OpenMandriva 4.3             | 55        | 2.93%   |
| Zorin 15                     | 37        | 1.97%   |
| Zorin 16                     | 32        | 1.71%   |
| Linux Mint 20.2              | 31        | 1.65%   |
| Manjaro                      | 30        | 1.6%    |
| Arch Rolling                 | 30        | 1.6%    |
| Linux Mint 20.3              | 28        | 1.49%   |
| Linux Mint 20.1              | 26        | 1.39%   |
| Linux Mint 20                | 26        | 1.39%   |
| Xubuntu 20.04                | 25        | 1.33%   |
| KDE neon 20.04               | 25        | 1.33%   |
| Linux Mint 19.3              | 24        | 1.28%   |
| Fedora 36                    | 24        | 1.28%   |
| BlackPanther 18.1            | 24        | 1.28%   |
| ArcoLinux Rolling            | 22        | 1.17%   |
| Ubuntu 19.04                 | 21        | 1.12%   |
| Arch                         | 20        | 1.07%   |
| Pop!_OS 22.04                | 19        | 1.01%   |
| Xubuntu 18.04                | 18        | 0.96%   |
| Fedora 33                    | 18        | 0.96%   |
| Linux Mint 21.1              | 17        | 0.91%   |
| Ubuntu 19.10                 | 16        | 0.85%   |
| Pop!_OS 21.04                | 16        | 0.85%   |
| OpenMandriva 23.03           | 16        | 0.85%   |
| Kubuntu 20.04                | 16        | 0.85%   |
| Ubuntu MATE 20.04            | 15        | 0.8%    |
| Ubuntu 21.10                 | 14        | 0.75%   |
| Ubuntu 21.04                 | 14        | 0.75%   |
| Fedora 37                    | 14        | 0.75%   |
| Fedora 34                    | 14        | 0.75%   |
| Fedora 32                    | 14        | 0.75%   |
| Debian 10                    | 14        | 0.75%   |
| Ubuntu 18.10                 | 13        | 0.69%   |
| Pop!_OS 20.04                | 13        | 0.69%   |
| openSUSE Tumbleweed-XXXXXXXX | 13        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 599       | 33.48%  |
| Linux Mint    | 166       | 9.28%   |
| OpenMandriva  | 134       | 7.49%   |
| Fedora        | 102       | 5.7%    |
| Debian        | 93        | 5.2%    |
| Zorin         | 71        | 3.97%   |
| Pop!_OS       | 62        | 3.47%   |
| Xubuntu       | 56        | 3.13%   |
| Manjaro       | 51        | 2.85%   |
| Arch          | 48        | 2.68%   |
| Endless       | 39        | 2.18%   |
| Kubuntu       | 35        | 1.96%   |
| KDE neon      | 34        | 1.9%    |
| BlackPanther  | 24        | 1.34%   |
| ROSA          | 23        | 1.29%   |
| Elementary    | 23        | 1.29%   |
| ArcoLinux     | 23        | 1.29%   |
| Ubuntu MATE   | 21        | 1.17%   |
| Lubuntu       | 19        | 1.06%   |
| openSUSE      | 14        | 0.78%   |
| Nobara        | 14        | 0.78%   |
| Ubuntu Budgie | 12        | 0.67%   |
| Ubuntu Unity  | 11        | 0.61%   |
| LMDE          | 11        | 0.61%   |
| Clear Linux   | 11        | 0.61%   |
| EndeavourOS   | 9         | 0.5%    |
| Gentoo        | 6         | 0.34%   |
| UbuntuDDE     | 5         | 0.28%   |
| Peppermint    | 5         | 0.28%   |
| MX            | 5         | 0.28%   |
| Kali          | 5         | 0.28%   |
| LinuxFX       | 4         | 0.22%   |
| Huayra        | 4         | 0.22%   |
| Solus         | 3         | 0.17%   |
| RHEL          | 3         | 0.17%   |
| Parrot        | 3         | 0.17%   |
| Deepin        | 3         | 0.17%   |
| Void Linux    | 2         | 0.11%   |
| Sparky        | 2         | 0.11%   |
| Rocky Linux   | 2         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 54        | 2.65%   |
| 5.16.7-desktop-1omv4003  | 53        | 2.6%    |
| 5.4.0-42-generic         | 44        | 2.16%   |
| 5.4.0-26-generic         | 25        | 1.23%   |
| 4.18.16-desktop-1bP      | 23        | 1.13%   |
| 5.4.0-52-generic         | 20        | 0.98%   |
| 5.4.0-48-generic         | 20        | 0.98%   |
| 5.3.0-40-generic         | 17        | 0.83%   |
| 5.15.0-41-generic        | 16        | 0.79%   |
| 6.2.6-desktop-1omv2390   | 15        | 0.74%   |
| 5.4.0-91-generic         | 14        | 0.69%   |
| 5.4.0-40-generic         | 14        | 0.69%   |
| 5.4.0-37-generic         | 14        | 0.69%   |
| 5.3.0-28-generic         | 14        | 0.69%   |
| 5.15.0-52-generic        | 14        | 0.69%   |
| 5.4.0-74-generic         | 13        | 0.64%   |
| 5.3.0-46-generic         | 13        | 0.64%   |
| 5.8.0-53-generic         | 12        | 0.59%   |
| 5.4.0-72-generic         | 12        | 0.59%   |
| 5.4.0-58-generic         | 12        | 0.59%   |
| 5.4.0-29-generic         | 12        | 0.59%   |
| 5.3.0-53-generic         | 12        | 0.59%   |
| 5.15.0-46-generic        | 12        | 0.59%   |
| 5.11.0-27-generic        | 12        | 0.59%   |
| 5.4.0-80-generic         | 11        | 0.54%   |
| 5.4.0-47-generic         | 11        | 0.54%   |
| 5.4.0-19-generic         | 11        | 0.54%   |
| 5.19.0-35-generic        | 11        | 0.54%   |
| 5.15.0-56-generic        | 11        | 0.54%   |
| 5.15.0-48-generic        | 11        | 0.54%   |
| 5.13.0-28-generic        | 11        | 0.54%   |
| 5.8.0-43-generic         | 10        | 0.49%   |
| 5.4.0-45-generic         | 10        | 0.49%   |
| 5.11.0-37-generic        | 10        | 0.49%   |
| 4.18.0-15-generic        | 10        | 0.49%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.44%   |
| 5.8.0-7630-generic       | 9         | 0.44%   |
| 5.8.0-59-generic         | 9         | 0.44%   |
| 5.8.0-14-generic         | 9         | 0.44%   |
| 5.4.0-65-generic         | 9         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 376       | 19.67%  |
| 5.15.0  | 149       | 7.79%   |
| 4.15.0  | 119       | 6.22%   |
| 5.8.0   | 97        | 5.07%   |
| 5.3.0   | 96        | 5.02%   |
| 5.11.0  | 77        | 4.03%   |
| 5.10.0  | 76        | 3.97%   |
| 5.13.0  | 72        | 3.77%   |
| 5.10.14 | 55        | 2.88%   |
| 5.0.0   | 55        | 2.88%   |
| 5.16.7  | 53        | 2.77%   |
| 4.18.0  | 51        | 2.67%   |
| 5.19.0  | 50        | 2.62%   |
| 4.19.0  | 27        | 1.41%   |
| 4.18.16 | 24        | 1.26%   |
| 6.2.6   | 17        | 0.89%   |
| 6.1.1   | 11        | 0.58%   |
| 5.14.0  | 10        | 0.52%   |
| 5.17.5  | 8         | 0.42%   |
| 6.2.8   | 7         | 0.37%   |
| 5.15.5  | 7         | 0.37%   |
| 5.11.12 | 7         | 0.37%   |
| 4.4.0   | 7         | 0.37%   |
| 6.0.8   | 6         | 0.31%   |
| 5.18.0  | 6         | 0.31%   |
| 5.13.13 | 6         | 0.31%   |
| 6.3.5   | 5         | 0.26%   |
| 6.0.9   | 5         | 0.26%   |
| 5.18.5  | 5         | 0.26%   |
| 5.18.16 | 5         | 0.26%   |
| 5.12.4  | 5         | 0.26%   |
| 4.9.20  | 5         | 0.26%   |
| 6.3.1   | 4         | 0.21%   |
| 6.1.0   | 4         | 0.21%   |
| 6.0.15  | 4         | 0.21%   |
| 6.0.12  | 4         | 0.21%   |
| 6.0.10  | 4         | 0.21%   |
| 5.9.16  | 4         | 0.21%   |
| 5.9.10  | 4         | 0.21%   |
| 5.8.6   | 4         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 391       | 20.75%  |
| 5.15    | 191       | 10.14%  |
| 5.10    | 158       | 8.39%   |
| 5.8     | 120       | 6.37%   |
| 4.15    | 119       | 6.32%   |
| 5.3     | 98        | 5.2%    |
| 5.11    | 98        | 5.2%    |
| 5.13    | 93        | 4.94%   |
| 4.18    | 77        | 4.09%   |
| 5.16    | 76        | 4.03%   |
| 5.19    | 74        | 3.93%   |
| 5.0     | 59        | 3.13%   |
| 6.2     | 42        | 2.23%   |
| 5.18    | 37        | 1.96%   |
| 6.0     | 33        | 1.75%   |
| 6.1     | 30        | 1.59%   |
| 4.19    | 30        | 1.59%   |
| 5.17    | 24        | 1.27%   |
| 5.14    | 19        | 1.01%   |
| 5.9     | 18        | 0.96%   |
| 4.9     | 17        | 0.9%    |
| 5.6     | 16        | 0.85%   |
| 6.3     | 13        | 0.69%   |
| 5.7     | 12        | 0.64%   |
| 5.12    | 12        | 0.64%   |
| 4.4     | 7         | 0.37%   |
| 5.5     | 6         | 0.32%   |
| 4.1     | 3         | 0.16%   |
| 4.20    | 2         | 0.11%   |
| 4.13    | 2         | 0.11%   |
| 3.10    | 2         | 0.11%   |
| 5.2     | 1         | 0.05%   |
| 5.1     | 1         | 0.05%   |
| 4.17    | 1         | 0.05%   |
| 4.10    | 1         | 0.05%   |
| 3.16    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1639      | 94.69%  |
| i686    | 89        | 5.14%   |
| aarch64 | 2         | 0.12%   |
| armv7l  | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 733       | 40.81%  |
| KDE5             | 287       | 15.98%  |
| Unknown          | 202       | 11.25%  |
| XFCE             | 182       | 10.13%  |
| X-Cinnamon       | 112       | 6.24%   |
| MATE             | 78        | 4.34%   |
| KDE              | 42        | 2.34%   |
| LXQt             | 22        | 1.22%   |
| Pantheon         | 20        | 1.11%   |
| Cinnamon         | 16        | 0.89%   |
| LXDE             | 15        | 0.84%   |
| KDE4             | 14        | 0.78%   |
| Budgie           | 14        | 0.78%   |
| i3               | 12        | 0.67%   |
| Unity            | 11        | 0.61%   |
| Deepin           | 8         | 0.45%   |
| xmonad           | 3         | 0.17%   |
| qtile            | 3         | 0.17%   |
| GNOME Flashback  | 3         | 0.17%   |
| bspwm            | 3         | 0.17%   |
| lightdm-xsession | 2         | 0.11%   |
| i3-with-shmlog   | 2         | 0.11%   |
| DWM              | 2         | 0.11%   |
| Cutefish         | 2         | 0.11%   |
| UKUI             | 1         | 0.06%   |
| trinity          | 1         | 0.06%   |
| sway             | 1         | 0.06%   |
| openbox          | 1         | 0.06%   |
| icewm            | 1         | 0.06%   |
| Enlightenment    | 1         | 0.06%   |
| BunsenLabs       | 1         | 0.06%   |
| awesome          | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1406      | 79.52%  |
| Wayland | 233       | 13.18%  |
| Unknown | 111       | 6.28%   |
| Tty     | 18        | 1.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 980       | 54.9%   |
| SDDM    | 264       | 14.79%  |
| GDM     | 164       | 9.19%   |
| LightDM | 157       | 8.8%    |
| GDM3    | 145       | 8.12%   |
| TDM     | 49        | 2.75%   |
| KDM     | 14        | 0.78%   |
| LXDM    | 4         | 0.22%   |
| SLiM    | 3         | 0.17%   |
| XDM     | 2         | 0.11%   |
| SLIMSKI | 1         | 0.06%   |
| Ly      | 1         | 0.06%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| es_AR       | 968       | 54.47%  |
| en_US       | 399       | 22.45%  |
| Unknown     | 207       | 11.65%  |
| es_ES       | 99        | 5.57%   |
| es_MX       | 39        | 2.19%   |
| C           | 28        | 1.58%   |
| en_GB       | 12        | 0.68%   |
| pt_BR       | 5         | 0.28%   |
| POSIX       | 2         | 0.11%   |
| it_IT       | 2         | 0.11%   |
| es_UY       | 2         | 0.11%   |
| es_US       | 2         | 0.11%   |
| es_CL       | 2         | 0.11%   |
| UTF-8       | 1         | 0.06%   |
| ru_RU       | 1         | 0.06%   |
| fr_FR       | 1         | 0.06%   |
| es_DO       | 1         | 0.06%   |
| es_AR.UtF-8 | 1         | 0.06%   |
| en_UTF-8    | 1         | 0.06%   |
| en_US.UTF8  | 1         | 0.06%   |
| en_CA       | 1         | 0.06%   |
| en_AG       | 1         | 0.06%   |
| C.UTF8      | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1019      | 57.54%  |
| EFI  | 752       | 42.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1387      | 78.41%  |
| Overlay | 165       | 9.33%   |
| Btrfs   | 118       | 6.67%   |
| Unknown | 52        | 2.94%   |
| Xfs     | 20        | 1.13%   |
| Tmpfs   | 10        | 0.57%   |
| Zfs     | 6         | 0.34%   |
| Ext2    | 5         | 0.28%   |
| Ext3    | 3         | 0.17%   |
| F2fs    | 2         | 0.11%   |
| Aufs    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1036      | 58.63%  |
| GPT     | 516       | 29.2%   |
| MBR     | 215       | 12.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1503      | 85.59%  |
| Yes       | 253       | 14.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1191      | 67.67%  |
| Yes       | 569       | 32.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 324       | 18.72%  |
| Lenovo                  | 233       | 13.46%  |
| Gigabyte Technology     | 217       | 12.54%  |
| Hewlett-Packard         | 152       | 8.78%   |
| Dell                    | 130       | 7.51%   |
| MSI                     | 107       | 6.18%   |
| ASRock                  | 95        | 5.49%   |
| Intel                   | 51        | 2.95%   |
| Acer                    | 46        | 2.66%   |
| BANGHO                  | 45        | 2.6%    |
| Exo                     | 32        | 1.85%   |
| Toshiba                 | 31        | 1.79%   |
| Samsung Electronics     | 28        | 1.62%   |
| Positivo                | 25        | 1.44%   |
| ECS                     | 18        | 1.04%   |
| Sony                    | 17        | 0.98%   |
| Apple                   | 17        | 0.98%   |
| Unknown                 | 15        | 0.87%   |
| Biostar                 | 11        | 0.64%   |
| Compal                  | 8         | 0.46%   |
| AMI                     | 8         | 0.46%   |
| Clevo                   | 7         | 0.4%    |
| Foxconn                 | 6         | 0.35%   |
| Standard                | 5         | 0.29%   |
| Quanta                  | 5         | 0.29%   |
| NOBLEX                  | 5         | 0.29%   |
| Coradir                 | 5         | 0.29%   |
| Advantec                | 5         | 0.29%   |
| System76                | 4         | 0.23%   |
| NSX                     | 4         | 0.23%   |
| HUAWEI                  | 4         | 0.23%   |
| PCBOX                   | 3         | 0.17%   |
| Kanji                   | 3         | 0.17%   |
| Juana Manso             | 3         | 0.17%   |
| A-DATA Technology       | 3         | 0.17%   |
| Raspberry Pi Foundation | 2         | 0.12%   |
| Radio Victoria Fueguina | 2         | 0.12%   |
| Pegatron                | 2         | 0.12%   |
| PCChips                 | 2         | 0.12%   |
| Packard Bell            | 2         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 29        | 1.68%   |
| MSI MS-7721                            | 22        | 1.27%   |
| ASUS All Series                        | 19        | 1.1%    |
| ASUS PRIME A320M-K                     | 13        | 0.75%   |
| Gigabyte F2A68HM-H                     | 12        | 0.69%   |
| Gigabyte H81M-H                        | 10        | 0.58%   |
| Lenovo V330-15IKB 81AX                 | 9         | 0.52%   |
| BANGHO MOV                             | 9         | 0.52%   |
| HP Notebook                            | 8         | 0.46%   |
| Gigabyte M68MT-S2                      | 8         | 0.46%   |
| Gigabyte A320M-S2H                     | 8         | 0.46%   |
| ASUS PRIME B450M-A                     | 8         | 0.46%   |
| ASUS P5KPL-AM SE                       | 8         | 0.46%   |
| MSI MS-7C52                            | 7         | 0.4%    |
| Lenovo ThinkPad L15 Gen 2 20X4S27200   | 7         | 0.4%    |
| HP Laptop 15-bs0xx                     | 7         | 0.4%    |
| Gigabyte H61M-S1                       | 7         | 0.4%    |
| Gigabyte H110M-H                       | 7         | 0.4%    |
| BANGHO Suma 1025                       | 7         | 0.4%    |
| MSI MS-7A15                            | 6         | 0.35%   |
| Lenovo G470 20078                      | 6         | 0.35%   |
| Intel powered classmate PC             | 6         | 0.35%   |
| Gigabyte F2A55M-HD2                    | 6         | 0.35%   |
| Gigabyte A320M-H                       | 6         | 0.35%   |
| BANGHO MAX G0101                       | 6         | 0.35%   |
| ASUS ROG STRIX B550-F GAMING           | 6         | 0.35%   |
| ASRock N68-VS3 FX                      | 6         | 0.35%   |
| HP Pavilion dv6                        | 5         | 0.29%   |
| Gigabyte A320M-S2H V2                  | 5         | 0.29%   |
| Exo CloudbookE15                       | 5         | 0.29%   |
| ECS H81H3-M4                           | 5         | 0.29%   |
| Dell Inspiron 1525                     | 5         | 0.29%   |
| Coradir Coradir/ES10IS5                | 5         | 0.29%   |
| BANGHO W240HU/W250HUQ                  | 5         | 0.29%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA | 5         | 0.29%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR   | 5         | 0.29%   |
| ASUS H61M-K                            | 5         | 0.29%   |
| Samsung 300E4C/300E5C/300E7C           | 4         | 0.23%   |
| MSI MS-7309                            | 4         | 0.23%   |
| Lenovo ThinkPad T430 2349DS5           | 4         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 83        | 4.79%   |
| Dell Inspiron      | 65        | 3.76%   |
| ASUS PRIME         | 52        | 3%      |
| Lenovo IdeaPad     | 45        | 2.6%    |
| Dell Latitude      | 41        | 2.37%   |
| HP Pavilion        | 40        | 2.31%   |
| Acer Aspire        | 38        | 2.2%    |
| ASUS VivoBook      | 33        | 1.91%   |
| Unknown            | 29        | 1.68%   |
| MSI MS-7721        | 22        | 1.27%   |
| HP Laptop          | 22        | 1.27%   |
| Toshiba Satellite  | 19        | 1.1%    |
| ASUS All           | 19        | 1.1%    |
| HP Compaq          | 15        | 0.87%   |
| ASUS ROG           | 14        | 0.81%   |
| Gigabyte A320M-S2H | 13        | 0.75%   |
| Exo Smart          | 13        | 0.75%   |
| Gigabyte F2A68HM-H | 12        | 0.69%   |
| Lenovo ThinkBook   | 11        | 0.64%   |
| HP 250             | 11        | 0.64%   |
| Lenovo ThinkCentre | 10        | 0.58%   |
| Gigabyte H81M-H    | 10        | 0.58%   |
| BANGHO MAX         | 10        | 0.58%   |
| ASUS M5A78L-M      | 10        | 0.58%   |
| Lenovo V330-15IKB  | 9         | 0.52%   |
| HP EliteBook       | 9         | 0.52%   |
| Dell OptiPlex      | 9         | 0.52%   |
| BANGHO MOV         | 9         | 0.52%   |
| HP Notebook        | 8         | 0.46%   |
| Gigabyte M68MT-S2  | 8         | 0.46%   |
| Gigabyte B450      | 8         | 0.46%   |
| BANGHO Suma        | 8         | 0.46%   |
| ASUS TUF           | 8         | 0.46%   |
| ASUS P5KPL-AM      | 8         | 0.46%   |
| ASRock N68-VS3     | 8         | 0.46%   |
| MSI MS-7C52        | 7         | 0.4%    |
| Gigabyte H61M-S1   | 7         | 0.4%    |
| Gigabyte H110M-H   | 7         | 0.4%    |
| Gigabyte B450M     | 7         | 0.4%    |
| ASUS ZenBook       | 7         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 156       | 9.01%   |
| 2012    | 152       | 8.78%   |
| 2018    | 133       | 7.68%   |
| 2011    | 129       | 7.45%   |
| 2019    | 124       | 7.16%   |
| 2020    | 123       | 7.11%   |
| 2015    | 117       | 6.76%   |
| 2013    | 116       | 6.7%    |
| 2021    | 114       | 6.59%   |
| 2014    | 107       | 6.18%   |
| 2010    | 106       | 6.12%   |
| 2016    | 86        | 4.97%   |
| 2008    | 76        | 4.39%   |
| 2009    | 73        | 4.22%   |
| 2007    | 53        | 3.06%   |
| 2006    | 36        | 2.08%   |
| 2022    | 12        | 0.69%   |
| Unknown | 9         | 0.52%   |
| 2004    | 5         | 0.29%   |
| 2005    | 3         | 0.17%   |
| 2001    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 921       | 53.21%  |
| Desktop        | 742       | 42.87%  |
| Convertible    | 25        | 1.44%   |
| Tablet         | 15        | 0.87%   |
| Mini pc        | 13        | 0.75%   |
| All in one     | 11        | 0.64%   |
| System on chip | 3         | 0.17%   |
| Server         | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1631      | 93.63%  |
| Enabled  | 111       | 6.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1729      | 99.88%  |
| Yes  | 2         | 0.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 431       | 24.59%  |
| 4.01-8.0    | 416       | 23.73%  |
| 8.01-16.0   | 326       | 18.6%   |
| 16.01-24.0  | 243       | 13.86%  |
| 1.01-2.0    | 151       | 8.61%   |
| 32.01-64.0  | 84        | 4.79%   |
| 2.01-3.0    | 41        | 2.34%   |
| 0.51-1.0    | 27        | 1.54%   |
| 24.01-32.0  | 21        | 1.2%    |
| 64.01-256.0 | 12        | 0.68%   |
| 0.01-0.5    | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 698       | 36.89%  |
| 2.01-3.0   | 458       | 24.21%  |
| 4.01-8.0   | 233       | 12.32%  |
| 3.01-4.0   | 218       | 11.52%  |
| 0.51-1.0   | 180       | 9.51%   |
| 8.01-16.0  | 70        | 3.7%    |
| 0.01-0.5   | 27        | 1.43%   |
| 16.01-24.0 | 8         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1109      | 62.48%  |
| 2      | 448       | 25.24%  |
| 3      | 135       | 7.61%   |
| 4      | 53        | 2.99%   |
| 5      | 13        | 0.73%   |
| 0      | 10        | 0.56%   |
| 6      | 3         | 0.17%   |
| 7      | 2         | 0.11%   |
| 28     | 1         | 0.06%   |
| 20     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1112      | 63.69%  |
| Yes       | 634       | 36.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1552      | 89.61%  |
| No        | 180       | 10.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1281      | 73.24%  |
| No        | 468       | 26.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 933       | 53.44%  |
| Yes       | 813       | 46.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Argentina | 1731      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Buenos Aires                | 413       | 22.79%  |
| Córdoba                    | 121       | 6.68%   |
| Rosario                     | 78        | 4.3%    |
| Mar del Plata               | 46        | 2.54%   |
| La Plata                    | 46        | 2.54%   |
| Lanus                       | 24        | 1.32%   |
| Corrientes                  | 24        | 1.32%   |
| Mendoza                     | 23        | 1.27%   |
| Avellaneda                  | 22        | 1.21%   |
| San Miguel de Tucumán      | 21        | 1.16%   |
| Lomas de Zamora             | 19        | 1.05%   |
| Quilmes                     | 17        | 0.94%   |
| Resistencia                 | 16        | 0.88%   |
| Ituzaingo                   | 16        | 0.88%   |
| Santa Fe                    | 15        | 0.83%   |
| Salta                       | 15        | 0.83%   |
| Ramos Mejia                 | 15        | 0.83%   |
| Bahía Blanca               | 15        | 0.83%   |
| Villa Ballester             | 14        | 0.77%   |
| Paraná                     | 14        | 0.77%   |
| Florencio Varela            | 14        | 0.77%   |
| Tandil                      | 13        | 0.72%   |
| Posadas                     | 13        | 0.72%   |
| Olivos                      | 13        | 0.72%   |
| Viedma                      | 12        | 0.66%   |
| Neuquén                    | 11        | 0.61%   |
| San Telmo                   | 10        | 0.55%   |
| San Juan                    | 10        | 0.55%   |
| Pilar                       | 10        | 0.55%   |
| Caseros                     | 10        | 0.55%   |
| Bariloche                   | 10        | 0.55%   |
| Villa Nueva                 | 9         | 0.5%    |
| San Nicolás de los Arroyos | 9         | 0.5%    |
| San Martín de los Andes    | 9         | 0.5%    |
| Godoy Cruz                  | 9         | 0.5%    |
| Burzaco                     | 9         | 0.5%    |
| Yerba Buena                 | 8         | 0.44%   |
| San Luis                    | 8         | 0.44%   |
| San Francisco               | 8         | 0.44%   |
| La Rioja                    | 8         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 662       | 996    | 27.85%  |
| Seagate                     | 324       | 418    | 13.63%  |
| Kingston                    | 311       | 393    | 13.08%  |
| Samsung Electronics         | 208       | 284    | 8.75%   |
| Toshiba                     | 193       | 243    | 8.12%   |
| Hitachi                     | 83        | 93     | 3.49%   |
| SanDisk                     | 66        | 94     | 2.78%   |
| Unknown                     | 64        | 81     | 2.69%   |
| HGST                        | 53        | 58     | 2.23%   |
| A-DATA Technology           | 46        | 52     | 1.94%   |
| SK hynix                    | 39        | 43     | 1.64%   |
| Gigabyte Technology         | 38        | 59     | 1.6%    |
| Crucial                     | 35        | 54     | 1.47%   |
| Intel                       | 21        | 40     | 0.88%   |
| Hewlett-Packard             | 18        | 25     | 0.76%   |
| Micron Technology           | 16        | 20     | 0.67%   |
| Maxtor                      | 14        | 15     | 0.59%   |
| Corsair                     | 12        | 12     | 0.5%    |
| PNY                         | 11        | 20     | 0.46%   |
| China                       | 11        | 13     | 0.46%   |
| Realtek Semiconductor       | 10        | 12     | 0.42%   |
| KIOXIA                      | 9         | 9      | 0.38%   |
| XPG                         | 8         | 9      | 0.34%   |
| Patriot                     | 7         | 9      | 0.29%   |
| Kimtigo                     | 7         | 7      | 0.29%   |
| ADATA Technology            | 7         | 8      | 0.29%   |
| Silicon Motion              | 6         | 7      | 0.25%   |
| Colorful                    | 6         | 7      | 0.25%   |
| Phison                      | 5         | 6      | 0.21%   |
| Lexar                       | 5         | 6      | 0.21%   |
| HS-SSD-C100                 | 5         | 7      | 0.21%   |
| Phison Electronics          | 4         | 5      | 0.17%   |
| Neo                         | 4         | 4      | 0.17%   |
| Hikvision                   | 4         | 4      | 0.17%   |
| Unknown                     | 4         | 4      | 0.17%   |
| Union Memory                | 3         | 3      | 0.13%   |
| OCZ                         | 3         | 3      | 0.13%   |
| Netac                       | 3         | 5      | 0.13%   |
| Micron/Crucial Technology   | 3         | 5      | 0.13%   |
| Kingston Technology Company | 3         | 3      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 98        | 3.74%   |
| Kingston SA400S37480G 480GB SSD      | 57        | 2.18%   |
| Seagate ST1000LM035-1RK172 1TB       | 43        | 1.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 36        | 1.37%   |
| WDC WD10EZEX-08WN4A0 1TB             | 34        | 1.3%    |
| Toshiba MQ01ABF050 500GB             | 30        | 1.15%   |
| Kingston SA400S37120G 120GB SSD      | 30        | 1.15%   |
| Toshiba MQ01ABD100 1TB               | 27        | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 26        | 0.99%   |
| Seagate ST1000DM010-2EP102 1TB       | 24        | 0.92%   |
| Seagate ST500DM002-1BD142 500GB      | 23        | 0.88%   |
| Kingston SV300S37A120G 120GB SSD     | 21        | 0.8%    |
| WDC WD5000AAKX-001CA0 500GB          | 20        | 0.76%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 19        | 0.73%   |
| WDC WD10EZEX-00BN5A0 1TB             | 18        | 0.69%   |
| Unknown MMC Card  32GB               | 18        | 0.69%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 17        | 0.65%   |
| Toshiba MQ04ABF100 1TB               | 15        | 0.57%   |
| Kingston SV300S37A240G 240GB SSD     | 15        | 0.57%   |
| Toshiba DT01ACA100 1TB               | 14        | 0.53%   |
| Seagate ST500LM030-2E717D 500GB      | 14        | 0.53%   |
| Kingston SUV400S37240G 240GB SSD     | 14        | 0.53%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 13        | 0.5%    |
| WDC WD5000AAKX-00ERMA0 500GB         | 13        | 0.5%    |
| Seagate ST500LT012-1DG142 500GB      | 13        | 0.5%    |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 13        | 0.5%    |
| WDC WD1600AABS-00PRA0 160GB          | 12        | 0.46%   |
| Toshiba MQ01ABD032 320GB             | 12        | 0.46%   |
| A-DATA SU630 240GB SSD               | 12        | 0.46%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 11        | 0.42%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 11        | 0.42%   |
| Toshiba DT01ACA050 500GB             | 11        | 0.42%   |
| Kingston SA400S37960G 960GB SSD      | 11        | 0.42%   |
| HGST HTS721010A9E630 1TB             | 11        | 0.42%   |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD | 11        | 0.42%   |
| Crucial CT240BX500SSD1 240GB         | 11        | 0.42%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 10        | 0.38%   |
| WDC WD20EZRX-00D8PB0 2TB             | 10        | 0.38%   |
| WDC WD10EZEX-21WN4A0 1TB             | 10        | 0.38%   |
| WDC WD10EZEX-00WN4A0 1TB             | 10        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 559       | 808    | 42.48%  |
| Seagate             | 318       | 410    | 24.16%  |
| Toshiba             | 175       | 221    | 13.3%   |
| Samsung Electronics | 105       | 142    | 7.98%   |
| Hitachi             | 83        | 93     | 6.31%   |
| HGST                | 53        | 58     | 4.03%   |
| Maxtor              | 11        | 11     | 0.84%   |
| Unknown             | 5         | 5      | 0.38%   |
| Fujitsu             | 3         | 3      | 0.23%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Quantum             | 1         | 1      | 0.08%   |
| ExcelStor           | 1         | 1      | 0.08%   |
| ASMT                | 1         | 2      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 279       | 354    | 39.52%  |
| WDC                 | 110       | 138    | 15.58%  |
| Samsung Electronics | 41        | 63     | 5.81%   |
| A-DATA Technology   | 39        | 43     | 5.52%   |
| SanDisk             | 35        | 43     | 4.96%   |
| Gigabyte Technology | 34        | 55     | 4.82%   |
| Crucial             | 34        | 53     | 4.82%   |
| PNY                 | 11        | 20     | 1.56%   |
| Hewlett-Packard     | 11        | 15     | 1.56%   |
| SK hynix            | 9         | 10     | 1.27%   |
| Corsair             | 9         | 9      | 1.27%   |
| China               | 8         | 10     | 1.13%   |
| Kimtigo             | 7         | 7      | 0.99%   |
| Intel               | 6         | 7      | 0.85%   |
| Colorful            | 6         | 7      | 0.85%   |
| Toshiba             | 5         | 5      | 0.71%   |
| Patriot             | 5         | 7      | 0.71%   |
| Micron Technology   | 5         | 7      | 0.71%   |
| Lexar               | 5         | 6      | 0.71%   |
| Seagate             | 4         | 6      | 0.57%   |
| OCZ                 | 3         | 3      | 0.42%   |
| Netac               | 3         | 5      | 0.42%   |
| Maxtor              | 3         | 4      | 0.42%   |
| Hikvision           | 3         | 3      | 0.42%   |
| FORESEE             | 3         | 3      | 0.42%   |
| WDC WDS2            | 2         | 2      | 0.28%   |
| Team                | 2         | 2      | 0.28%   |
| SPCC                | 2         | 2      | 0.28%   |
| LITEONIT            | 2         | 2      | 0.28%   |
| HS-SSD-C100         | 2         | 4      | 0.28%   |
| Apple               | 2         | 2      | 0.28%   |
| Unknown             | 2         | 2      | 0.28%   |
| XrayDisk            | 1         | 1      | 0.14%   |
| Transcend           | 1         | 1      | 0.14%   |
| tecmiyo             | 1         | 3      | 0.14%   |
| Super Talent        | 1         | 1      | 0.14%   |
| SMI                 | 1         | 1      | 0.14%   |
| Ramaxel Technology  | 1         | 1      | 0.14%   |
| NGFF                | 1         | 2      | 0.14%   |
| Neo                 | 1         | 1      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1142      | 1756   | 52.41%  |
| SSD     | 662       | 927    | 30.38%  |
| NVMe    | 295       | 420    | 13.54%  |
| MMC     | 61        | 79     | 2.8%    |
| Unknown | 19        | 17     | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1501      | 2669   | 79.71%  |
| NVMe | 295       | 420    | 15.67%  |
| MMC  | 61        | 79     | 3.24%   |
| SAS  | 26        | 31     | 1.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1154      | 1741   | 64.22%  |
| 0.51-1.0   | 515       | 744    | 28.66%  |
| 1.01-2.0   | 87        | 121    | 4.84%   |
| 3.01-4.0   | 18        | 27     | 1%      |
| 2.01-3.0   | 11        | 12     | 0.61%   |
| 4.01-10.0  | 11        | 19     | 0.61%   |
| 10.01-20.0 | 1         | 19     | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 534       | 29.12%  |
| 251-500        | 428       | 23.34%  |
| 501-1000       | 273       | 14.89%  |
| 1001-2000      | 144       | 7.85%   |
| 1-20           | 130       | 7.09%   |
| 51-100         | 120       | 6.54%   |
| 21-50          | 87        | 4.74%   |
| Unknown        | 43        | 2.34%   |
| 2001-3000      | 42        | 2.29%   |
| More than 3000 | 33        | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 766       | 40.55%  |
| 21-50          | 320       | 16.94%  |
| 101-250        | 248       | 13.13%  |
| 51-100         | 218       | 11.54%  |
| 251-500        | 139       | 7.36%   |
| 501-1000       | 92        | 4.87%   |
| 1001-2000      | 46        | 2.44%   |
| Unknown        | 43        | 2.28%   |
| 2001-3000      | 9         | 0.48%   |
| More than 3000 | 8         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB        | 7         | 9      | 3.48%   |
| Seagate ST1000LM035-1RK172 1TB     | 6         | 6      | 2.99%   |
| WDC WD10EZEX-00BN5A0 1TB           | 4         | 4      | 1.99%   |
| WDC WD10EARS-00Y5B1 1TB            | 4         | 4      | 1.99%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 3         | 3      | 1.49%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 3         | 3      | 1.49%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 3         | 3      | 1.49%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 3      | 1.49%   |
| Toshiba MQ01ABF050 500GB           | 3         | 3      | 1.49%   |
| Toshiba MQ01ABD100 1TB             | 3         | 6      | 1.49%   |
| Toshiba MK1665GSX 160GB            | 3         | 3      | 1.49%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 4      | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 1.49%   |
| Kingston SA400S37240G 240GB SSD    | 3         | 3      | 1.49%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 1.49%   |
| WDC WD5000AAKX-08ERMA0 500GB       | 2         | 2      | 1%      |
| WDC WD3200AAKS-00L9A0 320GB        | 2         | 2      | 1%      |
| WDC WD20EZRX-00D8PB0 2TB           | 2         | 2      | 1%      |
| WDC WD1002FAEX-00Y9A0 1TB          | 2         | 2      | 1%      |
| Toshiba MK7559GSXP 752GB           | 2         | 2      | 1%      |
| Seagate ST9500325AS 500GB          | 2         | 2      | 1%      |
| Seagate ST500LT012-1DG142 500GB    | 2         | 5      | 1%      |
| Seagate ST500LM030-2E717D 500GB    | 2         | 2      | 1%      |
| Seagate ST1500DL003-9VT16L 1TB     | 2         | 2      | 1%      |
| Seagate ST1000DM003-9YN162 1TB     | 2         | 2      | 1%      |
| Seagate ST1000DM003-1CH162 1TB     | 2         | 2      | 1%      |
| Samsung Electronics SP0411N 40GB   | 2         | 3      | 1%      |
| Samsung Electronics HN-M101MBB 1TB | 2         | 2      | 1%      |
| Samsung Electronics HD322HJ 320GB  | 2         | 2      | 1%      |
| Kingston SV300S37A120G 120GB SSD   | 2         | 2      | 1%      |
| Kingston SUV400S37240G 240GB SSD   | 2         | 2      | 1%      |
| HGST HTS721010A9E630 1TB           | 2         | 4      | 1%      |
| HGST HTS541075A9E680 752GB         | 2         | 2      | 1%      |
| XPG SPECTRIX S40G 4TB              | 1         | 1      | 0.5%    |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 4      | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 1      | 0.5%    |
| WDC WD800JD-00MSA1 80GB            | 1         | 1      | 0.5%    |
| WDC WD800BD-22MRA1 80GB            | 1         | 1      | 0.5%    |
| WDC WD800BB-75JHC0 80GB            | 1         | 1      | 0.5%    |
| WDC WD800BB-00JHC0 80GB            | 1         | 1      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 74        | 91     | 38.95%  |
| Seagate             | 41        | 47     | 21.58%  |
| Toshiba             | 21        | 24     | 11.05%  |
| Samsung Electronics | 17        | 19     | 8.95%   |
| Hitachi             | 10        | 11     | 5.26%   |
| HGST                | 10        | 12     | 5.26%   |
| Kingston            | 8         | 8      | 4.21%   |
| A-DATA Technology   | 3         | 3      | 1.58%   |
| Maxtor              | 2         | 2      | 1.05%   |
| XPG                 | 1         | 1      | 0.53%   |
| tecmiyo             | 1         | 3      | 0.53%   |
| SMI                 | 1         | 1      | 0.53%   |
| Quantum             | 1         | 1      | 0.53%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 69        | 83     | 40.83%  |
| Seagate             | 41        | 47     | 24.26%  |
| Toshiba             | 21        | 24     | 12.43%  |
| Samsung Electronics | 15        | 17     | 8.88%   |
| Hitachi             | 10        | 11     | 5.92%   |
| HGST                | 10        | 12     | 5.92%   |
| Maxtor              | 2         | 2      | 1.18%   |
| Quantum             | 1         | 1      | 0.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 159       | 197    | 88.33%  |
| SSD  | 19        | 24     | 10.56%  |
| NVMe | 2         | 2      | 1.11%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB       | 2         | 2      | 28.57%  |
| WDC WD1600BEVT-80A23T0 160GB      | 1         | 1      | 14.29%  |
| Toshiba MK6475GSX 640GB           | 1         | 1      | 14.29%  |
| Toshiba MK1665GSX 160GB           | 1         | 1      | 14.29%  |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 14.29%  |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 42.86%  |
| Toshiba             | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 2      | 28.57%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1093      | 1985   | 58.99%  |
| Works    | 576       | 984    | 31.08%  |
| Malfunc  | 177       | 223    | 9.55%   |
| Failed   | 7         | 7      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1100      | 56.12%  |
| AMD                              | 391       | 19.95%  |
| Nvidia                           | 81        | 4.13%   |
| Samsung Electronics              | 68        | 3.47%   |
| SanDisk                          | 64        | 3.27%   |
| Kingston Technology Company      | 37        | 1.89%   |
| SK hynix                         | 30        | 1.53%   |
| VIA Technologies                 | 28        | 1.43%   |
| Realtek Semiconductor            | 19        | 0.97%   |
| Phison Electronics               | 17        | 0.87%   |
| Silicon Integrated Systems [SiS] | 15        | 0.77%   |
| Toshiba America Info Systems     | 13        | 0.66%   |
| ASMedia Technology               | 13        | 0.66%   |
| Silicon Motion                   | 12        | 0.61%   |
| KIOXIA                           | 12        | 0.61%   |
| JMicron Technology               | 12        | 0.61%   |
| Micron Technology                | 10        | 0.51%   |
| Marvell Technology Group         | 10        | 0.51%   |
| ADATA Technology                 | 10        | 0.51%   |
| Union Memory (Shenzhen)          | 4         | 0.2%    |
| Micron/Crucial Technology        | 4         | 0.2%    |
| Silicon Image                    | 2         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 2         | 0.1%    |
| Promise Technology               | 1         | 0.05%   |
| Lite-On Technology               | 1         | 0.05%   |
| Broadcom / LSI                   | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |
| Adaptec                          | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 250       | 10.34%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 122       | 5.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 92        | 3.81%   |
| Nvidia MCP61 SATA Controller                                                            | 68        | 2.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 65        | 2.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 63        | 2.61%   |
| Nvidia MCP61 IDE                                                                        | 58        | 2.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 56        | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 53        | 2.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 51        | 2.11%   |
| AMD FCH SATA Controller D                                                               | 49        | 2.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 48        | 1.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 45        | 1.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 42        | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 38        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 36        | 1.49%   |
| AMD 400 Series Chipset SATA Controller                                                  | 36        | 1.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 32        | 1.32%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 31        | 1.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 31        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 31        | 1.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 29        | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 28        | 1.16%   |
| AMD FCH IDE Controller                                                                  | 28        | 1.16%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 27        | 1.12%   |
| Samsung NVMe SSD Controller 980                                                         | 26        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 26        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 26        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 26        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 24        | 0.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 23        | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 20        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 20        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 20        | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 19        | 0.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 18        | 0.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 18        | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 18        | 0.74%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 17        | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 17        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1261      | 62.06%  |
| IDE  | 388       | 19.09%  |
| NVMe | 297       | 14.62%  |
| RAID | 85        | 4.18%   |
| SCSI | 1         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1217      | 70.27%  |
| AMD    | 512       | 29.56%  |
| ARM    | 3         | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 27        | 1.56%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 26        | 1.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 18        | 1.04%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 17        | 0.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 0.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 16        | 0.92%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 16        | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 0.87%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 15        | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 0.81%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 14        | 0.81%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 14        | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.75%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 12        | 0.69%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 12        | 0.69%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 11        | 0.64%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 11        | 0.64%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 11        | 0.64%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 11        | 0.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 10        | 0.58%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 10        | 0.58%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 10        | 0.58%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 0.58%   |
| AMD Athlon II X2 250 Processor                | 10        | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 0.52%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 9         | 0.52%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 9         | 0.52%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 9         | 0.52%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 9         | 0.52%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 0.52%   |
| AMD FX-6300 Six-Core Processor                | 9         | 0.52%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 9         | 0.52%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 8         | 0.46%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 8         | 0.46%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 8         | 0.46%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.46%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 8         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 337       | 19.46%  |
| Intel Core i7           | 225       | 12.99%  |
| Intel Core i3           | 171       | 9.87%   |
| Intel Celeron           | 134       | 7.74%   |
| AMD Ryzen 5             | 90        | 5.2%    |
| Other                   | 73        | 4.21%   |
| Intel Atom              | 56        | 3.23%   |
| AMD Ryzen 7             | 55        | 3.18%   |
| Intel Pentium           | 54        | 3.12%   |
| Intel Core 2 Duo        | 49        | 2.83%   |
| Intel Pentium Dual-Core | 43        | 2.48%   |
| AMD A8                  | 36        | 2.08%   |
| AMD FX                  | 35        | 2.02%   |
| AMD A6                  | 33        | 1.91%   |
| AMD Ryzen 3             | 30        | 1.73%   |
| Intel Pentium Dual      | 25        | 1.44%   |
| AMD Athlon II X2        | 25        | 1.44%   |
| AMD A10                 | 24        | 1.39%   |
| AMD A4                  | 23        | 1.33%   |
| AMD Athlon 64 X2        | 22        | 1.27%   |
| AMD Sempron             | 18        | 1.04%   |
| AMD Athlon              | 17        | 0.98%   |
| AMD Phenom II X4        | 14        | 0.81%   |
| Intel Core 2            | 11        | 0.64%   |
| AMD Ryzen 9             | 11        | 0.64%   |
| Intel Pentium 4         | 10        | 0.58%   |
| Intel Pentium D         | 9         | 0.52%   |
| Intel Genuine           | 9         | 0.52%   |
| AMD Phenom II X6        | 8         | 0.46%   |
| AMD Athlon II X4        | 8         | 0.46%   |
| AMD A12                 | 6         | 0.35%   |
| Intel Xeon              | 5         | 0.29%   |
| Intel Core 2 Quad       | 5         | 0.29%   |
| AMD E1                  | 5         | 0.29%   |
| AMD Athlon II X3        | 5         | 0.29%   |
| AMD Athlon II           | 5         | 0.29%   |
| Intel Pentium Gold      | 4         | 0.23%   |
| AMD Phenom              | 4         | 0.23%   |
| Intel Core i9           | 3         | 0.17%   |
| AMD Ryzen 7 PRO         | 3         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 885       | 51.1%   |
| 4       | 517       | 29.85%  |
| 1       | 112       | 6.47%   |
| 6       | 107       | 6.18%   |
| 8       | 76        | 4.39%   |
| 3       | 20        | 1.15%   |
| 12      | 5         | 0.29%   |
| 16      | 4         | 0.23%   |
| Unknown | 3         | 0.17%   |
| 10      | 2         | 0.12%   |
| 24      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1727      | 99.77%  |
| 2       | 3         | 0.17%   |
| Unknown | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1032      | 59.55%  |
| 1       | 698       | 40.28%  |
| Unknown | 3         | 0.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1678      | 96.66%  |
| Unknown        | 31        | 1.79%   |
| 32-bit         | 20        | 1.15%   |
| 64-bit         | 7         | 0.4%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 381       | 21.12%  |
| 0x306a9    | 97        | 5.38%   |
| 0x206a7    | 97        | 5.38%   |
| 0x306c3    | 65        | 3.6%    |
| 0x1067a    | 62        | 3.44%   |
| 0x806e9    | 47        | 2.61%   |
| 0x806ec    | 44        | 2.44%   |
| 0x6fd      | 36        | 2%      |
| 0x08108109 | 35        | 1.94%   |
| 0x906e9    | 34        | 1.88%   |
| 0x406e3    | 34        | 1.88%   |
| 0x010000c8 | 34        | 1.88%   |
| 0x806c1    | 33        | 1.83%   |
| 0x806ea    | 31        | 1.72%   |
| 0x306d4    | 30        | 1.66%   |
| 0x30678    | 30        | 1.66%   |
| 0x906ea    | 28        | 1.55%   |
| 0x06001119 | 28        | 1.55%   |
| 0x40651    | 26        | 1.44%   |
| 0x506e3    | 25        | 1.39%   |
| 0x20655    | 25        | 1.39%   |
| 0x406c4    | 22        | 1.22%   |
| 0x06003106 | 22        | 1.22%   |
| 0x706e5    | 19        | 1.05%   |
| 0x08701021 | 19        | 1.05%   |
| 0x106ca    | 18        | 1%      |
| 0x506c9    | 16        | 0.89%   |
| 0x706a1    | 15        | 0.83%   |
| 0x0a50000c | 14        | 0.78%   |
| 0x08101016 | 14        | 0.78%   |
| 0x06000852 | 14        | 0.78%   |
| 0x0800820d | 13        | 0.72%   |
| 0x0600611a | 13        | 0.72%   |
| 0x06006118 | 13        | 0.72%   |
| 0x30661    | 12        | 0.67%   |
| 0x20652    | 12        | 0.67%   |
| 0x10676    | 12        | 0.67%   |
| 0xa0653    | 11        | 0.61%   |
| 0x706a8    | 11        | 0.61%   |
| 0x06006705 | 11        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 248       | 14.32%  |
| SandyBridge      | 116       | 6.7%    |
| IvyBridge        | 114       | 6.58%   |
| Haswell          | 111       | 6.41%   |
| Penryn           | 90        | 5.2%    |
| K10              | 89        | 5.14%   |
| Silvermont       | 82        | 4.73%   |
| Skylake          | 74        | 4.27%   |
| Zen+             | 68        | 3.93%   |
| Core             | 61        | 3.52%   |
| Piledriver       | 55        | 3.18%   |
| Zen 2            | 46        | 2.66%   |
| TigerLake        | 46        | 2.66%   |
| Excavator        | 44        | 2.54%   |
| Westmere         | 41        | 2.37%   |
| Zen              | 37        | 2.14%   |
| Zen 3            | 35        | 2.02%   |
| K8 Hammer        | 35        | 2.02%   |
| Bonnell          | 35        | 2.02%   |
| Broadwell        | 34        | 1.96%   |
| CometLake        | 33        | 1.91%   |
| Steamroller      | 32        | 1.85%   |
| Goldmont plus    | 32        | 1.85%   |
| IceLake          | 31        | 1.79%   |
| Unknown          | 25        | 1.44%   |
| NetBurst         | 22        | 1.27%   |
| Goldmont         | 18        | 1.04%   |
| Bulldozer        | 14        | 0.81%   |
| K10 Llano        | 13        | 0.75%   |
| P6               | 11        | 0.64%   |
| Jaguar           | 11        | 0.64%   |
| Nehalem          | 8         | 0.46%   |
| Bobcat           | 8         | 0.46%   |
| Puma             | 7         | 0.4%    |
| K8 & K10 hybrid  | 2         | 0.12%   |
| K6               | 2         | 0.12%   |
| Alderlake Hybrid | 2         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1034      | 54.28%  |
| AMD                              | 481       | 25.25%  |
| Nvidia                           | 365       | 19.16%  |
| Silicon Integrated Systems [SiS] | 12        | 0.63%   |
| VIA Technologies                 | 11        | 0.58%   |
| ATI Technologies                 | 2         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 105       | 5.34%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 73        | 3.71%   |
| Intel HD Graphics 620                                                                    | 60        | 3.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 48        | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 44        | 2.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 43        | 2.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 41        | 2.08%   |
| Intel UHD Graphics 620                                                                   | 38        | 1.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 38        | 1.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 38        | 1.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 34        | 1.73%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 1.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 33        | 1.68%   |
| Intel HD Graphics 5500                                                                   | 32        | 1.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 32        | 1.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 1.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 28        | 1.42%   |
| Intel HD Graphics 630                                                                    | 27        | 1.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 1.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 26        | 1.32%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 25        | 1.27%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 21        | 1.07%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 21        | 1.07%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 20        | 1.02%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 20        | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 0.97%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 19        | 0.97%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 19        | 0.97%   |
| Nvidia GT218 [GeForce 210]                                                               | 18        | 0.92%   |
| Intel HD Graphics 500                                                                    | 18        | 0.92%   |
| AMD Renoir                                                                               | 18        | 0.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 18        | 0.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 17        | 0.86%   |
| Intel HD Graphics 530                                                                    | 17        | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 16        | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 16        | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 16        | 0.81%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 15        | 0.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 15        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 882       | 50.72%  |
| 1 x AMD        | 407       | 23.4%   |
| 1 x Nvidia     | 236       | 13.57%  |
| Intel + Nvidia | 104       | 5.98%   |
| Intel + AMD    | 38        | 2.19%   |
| 2 x AMD        | 22        | 1.27%   |
| AMD + Nvidia   | 20        | 1.15%   |
| 1 x SiS        | 12        | 0.69%   |
| 1 x VIA        | 11        | 0.63%   |
| Other          | 3         | 0.17%   |
| 2 x Nvidia     | 2         | 0.12%   |
| 2 x Intel      | 2         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1493      | 85.56%  |
| Proprietary | 163       | 9.34%   |
| Unknown     | 89        | 5.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1041      | 58.61%  |
| 0.01-0.5   | 226       | 12.73%  |
| 1.01-2.0   | 204       | 11.49%  |
| 0.51-1.0   | 142       | 8%      |
| 3.01-4.0   | 94        | 5.29%   |
| 7.01-8.0   | 33        | 1.86%   |
| 5.01-6.0   | 21        | 1.18%   |
| 2.01-3.0   | 8         | 0.45%   |
| 8.01-16.0  | 7         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 441       | 24.18%  |
| Goldstar                | 210       | 11.51%  |
| AU Optronics            | 187       | 10.25%  |
| Chimei Innolux          | 164       | 8.99%   |
| BOE                     | 158       | 8.66%   |
| LG Display              | 126       | 6.91%   |
| InfoVision              | 40        | 2.19%   |
| Dell                    | 36        | 1.97%   |
| ViewSonic               | 34        | 1.86%   |
| Philips                 | 28        | 1.54%   |
| BenQ                    | 28        | 1.54%   |
| Hitachi                 | 22        | 1.21%   |
| Hewlett-Packard         | 21        | 1.15%   |
| SKY                     | 20        | 1.1%    |
| Lenovo                  | 19        | 1.04%   |
| LG Electronics          | 18        | 0.99%   |
| Chi Mei Optoelectronics | 18        | 0.99%   |
| Apple                   | 17        | 0.93%   |
| PANDA                   | 15        | 0.82%   |
| LG Philips              | 12        | 0.66%   |
| AOC                     | 12        | 0.66%   |
| Unknown                 | 11        | 0.6%    |
| InnoLux Display         | 10        | 0.55%   |
| SAC                     | 9         | 0.49%   |
| HannStar                | 9         | 0.49%   |
| STA                     | 8         | 0.44%   |
| Sharp                   | 8         | 0.44%   |
| Sony                    | 7         | 0.38%   |
| CPT                     | 7         | 0.38%   |
| ASUSTek Computer        | 7         | 0.38%   |
| MStar                   | 6         | 0.33%   |
| HKC                     | 6         | 0.33%   |
| Acer                    | 6         | 0.33%   |
| Unknown (XXX)           | 5         | 0.27%   |
| UTV                     | 4         | 0.22%   |
| SANYO                   | 4         | 0.22%   |
| KDC                     | 4         | 0.22%   |
| ITE                     | 4         | 0.22%   |
| GDH                     | 4         | 0.22%   |
| Daewoo                  | 4         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 21        | 1.12%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 18        | 0.96%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 18        | 0.96%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch          | 17        | 0.9%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 16        | 0.85%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 15        | 0.8%    |
| Hitachi HDMI HEC0088 1920x540                                        | 14        | 0.75%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 14        | 0.75%   |
| SKY TV-monitor SKY0001 1360x768 890x500mm 40.2-inch                  | 12        | 0.64%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 12        | 0.64%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                 | 12        | 0.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 11        | 0.59%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 11        | 0.59%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 11        | 0.59%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 10        | 0.53%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 10        | 0.53%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 10        | 0.53%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 9         | 0.48%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 9         | 0.48%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                | 9         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 9         | 0.48%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 8         | 0.43%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 8         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 8         | 0.43%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 8         | 0.43%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 8         | 0.43%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 440x250mm 19.9-inch    | 7         | 0.37%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 7         | 0.37%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 7         | 0.37%   |
| Goldstar E2340 GSM57C7 1920x1080 510x290mm 23.1-inch                 | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 7         | 0.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 7         | 0.37%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 6         | 0.32%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch    | 6         | 0.32%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 6         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 6         | 0.32%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 6         | 0.32%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                       | 6         | 0.32%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch          | 6         | 0.32%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 6         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 634       | 35.9%   |
| 1366x768 (WXGA)    | 613       | 34.71%  |
| 1280x1024 (SXGA)   | 63        | 3.57%   |
| 3840x2160 (4K)     | 60        | 3.4%    |
| 1600x900 (HD+)     | 57        | 3.23%   |
| 1440x900 (WXGA+)   | 48        | 2.72%   |
| 1280x800 (WXGA)    | 48        | 2.72%   |
| 1360x768           | 47        | 2.66%   |
| 1680x1050 (WSXGA+) | 46        | 2.6%    |
| 1920x1200 (WUXGA)  | 23        | 1.3%    |
| 1920x540           | 19        | 1.08%   |
| 2560x1440 (QHD)    | 11        | 0.62%   |
| 1024x600           | 11        | 0.62%   |
| Unknown            | 11        | 0.62%   |
| 2560x1080          | 10        | 0.57%   |
| 1024x768 (XGA)     | 9         | 0.51%   |
| 1280x720 (HD)      | 7         | 0.4%    |
| 3200x1800 (QHD+)   | 5         | 0.28%   |
| 1152x864           | 4         | 0.23%   |
| 3840x2400          | 3         | 0.17%   |
| 3840x1080          | 3         | 0.17%   |
| 3440x1440          | 3         | 0.17%   |
| 2560x1600          | 3         | 0.17%   |
| 2288x1287          | 3         | 0.17%   |
| 3456x2160          | 2         | 0.11%   |
| 2880x1800          | 2         | 0.11%   |
| 2160x1440          | 2         | 0.11%   |
| 2048x1152          | 2         | 0.11%   |
| 1280x960           | 2         | 0.11%   |
| 4093x4093          | 1         | 0.06%   |
| 3840x1100          | 1         | 0.06%   |
| 3600x1200          | 1         | 0.06%   |
| 3286x1080          | 1         | 0.06%   |
| 3280x1080          | 1         | 0.06%   |
| 3046x1050          | 1         | 0.06%   |
| 3000x2000          | 1         | 0.06%   |
| 2736x1824          | 1         | 0.06%   |
| 2646x1024          | 1         | 0.06%   |
| 2560x2880          | 1         | 0.06%   |
| 2048x1536          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 488       | 26.42%  |
| 14      | 187       | 10.12%  |
| 13      | 175       | 9.47%   |
| 21      | 147       | 7.96%   |
| 23      | 146       | 7.9%    |
| 18      | 120       | 6.5%    |
| 17      | 63        | 3.41%   |
| Unknown | 60        | 3.25%   |
| 24      | 58        | 3.14%   |
| 19      | 54        | 2.92%   |
| 20      | 45        | 2.44%   |
| 27      | 41        | 2.22%   |
| 40      | 35        | 1.89%   |
| 10      | 26        | 1.41%   |
| 22      | 21        | 1.14%   |
| 48      | 17        | 0.92%   |
| 12      | 17        | 0.92%   |
| 31      | 16        | 0.87%   |
| 16      | 16        | 0.87%   |
| 84      | 15        | 0.81%   |
| 52      | 15        | 0.81%   |
| 11      | 15        | 0.81%   |
| 32      | 12        | 0.65%   |
| 46      | 11        | 0.6%    |
| 34      | 11        | 0.6%    |
| 54      | 9         | 0.49%   |
| 142     | 3         | 0.16%   |
| 39      | 3         | 0.16%   |
| 26      | 3         | 0.16%   |
| 72      | 2         | 0.11%   |
| 65      | 2         | 0.11%   |
| 55      | 2         | 0.11%   |
| 47      | 2         | 0.11%   |
| 30      | 2         | 0.11%   |
| 25      | 2         | 0.11%   |
| 64      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 43      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |
| 41      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 821       | 45.06%  |
| 401-500        | 371       | 20.36%  |
| 501-600        | 232       | 12.73%  |
| 201-300        | 102       | 5.6%    |
| 351-400        | 68        | 3.73%   |
| Unknown        | 60        | 3.29%   |
| 1001-1500      | 59        | 3.24%   |
| 801-900        | 39        | 2.14%   |
| 601-700        | 24        | 1.32%   |
| 701-800        | 23        | 1.26%   |
| 1501-2000      | 17        | 0.93%   |
| More than 2000 | 3         | 0.16%   |
| 901-1000       | 3         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1316      | 79.85%  |
| 16/10   | 154       | 9.34%   |
| Unknown | 52        | 3.16%   |
| 5/4     | 44        | 2.67%   |
| 4/3     | 39        | 2.37%   |
| 1.96    | 14        | 0.85%   |
| 21/9    | 12        | 0.73%   |
| 3/2     | 10        | 0.61%   |
| 1.00    | 3         | 0.18%   |
| 32/9    | 2         | 0.12%   |
| 3.40    | 1         | 0.06%   |
| 0.89    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 468       | 25.63%  |
| 81-90          | 330       | 18.07%  |
| 201-250        | 329       | 18.02%  |
| 141-150        | 145       | 7.94%   |
| 151-200        | 126       | 6.9%    |
| 501-1000       | 69        | 3.78%   |
| Unknown        | 60        | 3.29%   |
| More than 1000 | 50        | 2.74%   |
| 301-350        | 43        | 2.35%   |
| 351-500        | 41        | 2.25%   |
| 71-80          | 33        | 1.81%   |
| 121-130        | 31        | 1.7%    |
| 111-120        | 28        | 1.53%   |
| 41-50          | 26        | 1.42%   |
| 51-60          | 16        | 0.88%   |
| 61-70          | 12        | 0.66%   |
| 251-300        | 9         | 0.49%   |
| 131-140        | 6         | 0.33%   |
| 91-100         | 4         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 694       | 38.75%  |
| 51-100        | 611       | 34.12%  |
| 121-160       | 288       | 16.08%  |
| 1-50          | 92        | 5.14%   |
| Unknown       | 60        | 3.35%   |
| 161-240       | 29        | 1.62%   |
| More than 240 | 17        | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1428      | 80.5%   |
| 2     | 259       | 14.6%   |
| 0     | 74        | 4.17%   |
| 3     | 12        | 0.68%   |
| 5     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1142      | 44.45%  |
| Intel                                 | 527       | 20.51%  |
| Qualcomm Atheros                      | 315       | 12.26%  |
| Broadcom                              | 89        | 3.46%   |
| Nvidia                                | 71        | 2.76%   |
| TP-Link                               | 69        | 2.69%   |
| Ralink Technology                     | 44        | 1.71%   |
| Marvell Technology Group              | 33        | 1.28%   |
| Qualcomm Atheros Communications       | 32        | 1.25%   |
| Broadcom Limited                      | 32        | 1.25%   |
| JMicron Technology                    | 25        | 0.97%   |
| Ralink                                | 23        | 0.9%    |
| Samsung Electronics                   | 21        | 0.82%   |
| VIA Technologies                      | 20        | 0.78%   |
| Silicon Integrated Systems [SiS]      | 15        | 0.58%   |
| Motorola PCS                          | 14        | 0.54%   |
| MediaTek                              | 14        | 0.54%   |
| Microsoft                             | 9         | 0.35%   |
| ASIX Electronics                      | 7         | 0.27%   |
| Xiaomi                                | 4         | 0.16%   |
| NetGear                               | 4         | 0.16%   |
| D-Link System                         | 4         | 0.16%   |
| Sundance Technology Inc / IC Plus     | 3         | 0.12%   |
| ICS Advent                            | 3         | 0.12%   |
| Ericsson Business Mobile Networks     | 3         | 0.12%   |
| DisplayLink                           | 3         | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.12%   |
| 3Com                                  | 3         | 0.12%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.08%   |
| T & A Mobile Phones                   | 2         | 0.08%   |
| Standard Microsystems                 | 2         | 0.08%   |
| Ovislink                              | 2         | 0.08%   |
| Linksys                               | 2         | 0.08%   |
| LG Electronics                        | 2         | 0.08%   |
| Huawei Technologies                   | 2         | 0.08%   |
| Encore Electronics                    | 2         | 0.08%   |
| Davicom Semiconductor                 | 2         | 0.08%   |
| D-Link                                | 2         | 0.08%   |
| Arduino SA                            | 2         | 0.08%   |
| ZyDAS                                 | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 780       | 25.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 173       | 5.7%    |
| Nvidia MCP61 Ethernet                                             | 62        | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 57        | 1.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 49        | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 45        | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 42        | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 42        | 1.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 41        | 1.35%   |
| Intel Wi-Fi 6 AX200                                               | 34        | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 33        | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 33        | 1.09%   |
| Intel Wi-Fi 6 AX201                                               | 32        | 1.06%   |
| Intel Wireless 3160                                               | 31        | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 29        | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                   | 29        | 0.96%   |
| Intel Wireless 3165                                               | 28        | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 28        | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 25        | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 24        | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 23        | 0.76%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 23        | 0.76%   |
| Intel Wireless 8265 / 8275                                        | 23        | 0.76%   |
| Intel Ethernet Connection (2) I219-V                              | 23        | 0.76%   |
| Ralink MT7601U Wireless Adapter                                   | 22        | 0.73%   |
| Intel Wireless 7260                                               | 22        | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 21        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21        | 0.69%   |
| Intel I211 Gigabit Network Connection                             | 21        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 21        | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 20        | 0.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 19        | 0.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 18        | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18        | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 17        | 0.56%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 16        | 0.53%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 16        | 0.53%   |
| Intel Wireless 7265                                               | 16        | 0.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 15        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 413       | 30.75%  |
| Realtek Semiconductor                 | 370       | 27.55%  |
| Qualcomm Atheros                      | 261       | 19.43%  |
| Broadcom                              | 75        | 5.58%   |
| TP-Link                               | 60        | 4.47%   |
| Ralink Technology                     | 44        | 3.28%   |
| Qualcomm Atheros Communications       | 32        | 2.38%   |
| Ralink                                | 23        | 1.71%   |
| Broadcom Limited                      | 19        | 1.41%   |
| MediaTek                              | 10        | 0.74%   |
| Microsoft                             | 8         | 0.6%    |
| NetGear                               | 4         | 0.3%    |
| Marvell Technology Group              | 4         | 0.3%    |
| D-Link System                         | 4         | 0.3%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.22%   |
| Ovislink                              | 2         | 0.15%   |
| Linksys                               | 2         | 0.15%   |
| Encore Electronics                    | 2         | 0.15%   |
| D-Link                                | 2         | 0.15%   |
| ZyDAS                                 | 1         | 0.07%   |
| Sierra Wireless                       | 1         | 0.07%   |
| Samsung Electronics                   | 1         | 0.07%   |
| Dell                                  | 1         | 0.07%   |
| Cisco Aironet Wireless Communications | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 57        | 4.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 49        | 3.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 45        | 3.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 42        | 3.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 42        | 3.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 41        | 3.03%   |
| Intel Wi-Fi 6 AX200                                                     | 34        | 2.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 33        | 2.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 33        | 2.44%   |
| Intel Wi-Fi 6 AX201                                                     | 32        | 2.36%   |
| Intel Wireless 3160                                                     | 31        | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 2.14%   |
| Qualcomm Atheros AR9271 802.11n                                         | 29        | 2.14%   |
| Intel Wireless 3165                                                     | 28        | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 2.07%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 23        | 1.7%    |
| Intel Wireless 8265 / 8275                                              | 23        | 1.7%    |
| Ralink MT7601U Wireless Adapter                                         | 22        | 1.62%   |
| Intel Wireless 7260                                                     | 22        | 1.62%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 21        | 1.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 1.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 20        | 1.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 19        | 1.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 18        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 1.26%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 16        | 1.18%   |
| Intel Wireless 7265                                                     | 16        | 1.18%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 15        | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 14        | 1.03%   |
| Intel Wireless 8260                                                     | 14        | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 1.03%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 13        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 0.96%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 12        | 0.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.89%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 12        | 0.89%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 11        | 0.81%   |
| Realtek 802.11n WLAN Adapter                                            | 11        | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1014      | 61.83%  |
| Intel                             | 233       | 14.21%  |
| Qualcomm Atheros                  | 112       | 6.83%   |
| Nvidia                            | 71        | 4.33%   |
| Marvell Technology Group          | 29        | 1.77%   |
| JMicron Technology                | 25        | 1.52%   |
| Broadcom                          | 25        | 1.52%   |
| VIA Technologies                  | 20        | 1.22%   |
| Samsung Electronics               | 18        | 1.1%    |
| Silicon Integrated Systems [SiS]  | 15        | 0.91%   |
| Broadcom Limited                  | 13        | 0.79%   |
| Motorola PCS                      | 12        | 0.73%   |
| TP-Link                           | 10        | 0.61%   |
| ASIX Electronics                  | 7         | 0.43%   |
| Xiaomi                            | 4         | 0.24%   |
| MediaTek                          | 4         | 0.24%   |
| Sundance Technology Inc / IC Plus | 3         | 0.18%   |
| ICS Advent                        | 3         | 0.18%   |
| DisplayLink                       | 3         | 0.18%   |
| 3Com                              | 3         | 0.18%   |
| T & A Mobile Phones               | 2         | 0.12%   |
| Standard Microsystems             | 2         | 0.12%   |
| Davicom Semiconductor             | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.06%   |
| Spreadtrum Communications         | 1         | 0.06%   |
| Microsoft                         | 1         | 0.06%   |
| Macronix [MXIC]                   | 1         | 0.06%   |
| LG Electronics                    | 1         | 0.06%   |
| Lenovo                            | 1         | 0.06%   |
| Huawei Technologies               | 1         | 0.06%   |
| Digitech Systems                  | 1         | 0.06%   |
| Aquantia                          | 1         | 0.06%   |
| 3DSP                              | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 780       | 47.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 173       | 10.44%  |
| Nvidia MCP61 Ethernet                                             | 62        | 3.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 25        | 1.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 24        | 1.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 23        | 1.39%   |
| Intel Ethernet Connection (2) I219-V                              | 23        | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21        | 1.27%   |
| Intel I211 Gigabit Network Connection                             | 21        | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 1.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18        | 1.09%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 16        | 0.97%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 0.84%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 13        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.78%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 12        | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 12        | 0.72%   |
| Motorola PCS moto g(40) fusion                                    | 12        | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 11        | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 0.66%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.66%   |
| Intel Ethernet Connection (10) I219-V                             | 11        | 0.66%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 9         | 0.54%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.42%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.42%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.42%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.42%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 6         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.36%   |
| Intel PRO/100 VE Network Connection                               | 6         | 0.36%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.36%   |
| Intel Ethernet Connection (2) I218-V                              | 6         | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.3%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 5         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1551      | 54.38%  |
| WiFi     | 1280      | 44.88%  |
| Modem    | 18        | 0.63%   |
| Unknown  | 3         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1053      | 59.26%  |
| Ethernet | 723       | 40.69%  |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 916       | 52.64%  |
| 1     | 752       | 43.22%  |
| 0     | 46        | 2.64%   |
| 3     | 22        | 1.26%   |
| 4     | 2         | 0.11%   |
| 32    | 1         | 0.06%   |
| 7     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1535      | 87.46%  |
| Yes  | 220       | 12.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 332       | 40.59%  |
| Realtek Semiconductor           | 152       | 18.58%  |
| Qualcomm Atheros Communications | 64        | 7.82%   |
| Cambridge Silicon Radio         | 54        | 6.6%    |
| IMC Networks                    | 43        | 5.26%   |
| Broadcom                        | 40        | 4.89%   |
| Lite-On Technology              | 34        | 4.16%   |
| Foxconn / Hon Hai               | 21        | 2.57%   |
| Apple                           | 16        | 1.96%   |
| Dell                            | 13        | 1.59%   |
| Toshiba                         | 9         | 1.1%    |
| ASUSTek Computer                | 8         | 0.98%   |
| Ralink                          | 7         | 0.86%   |
| Integrated System Solution      | 5         | 0.61%   |
| TP-Link                         | 3         | 0.37%   |
| Hewlett-Packard                 | 3         | 0.37%   |
| USI                             | 2         | 0.24%   |
| Qcom                            | 2         | 0.24%   |
| Marvell Semiconductor           | 2         | 0.24%   |
| Syntek                          | 1         | 0.12%   |
| Roper                           | 1         | 0.12%   |
| Realtek                         | 1         | 0.12%   |
| Logitech                        | 1         | 0.12%   |
| Foxconn International           | 1         | 0.12%   |
| Edimax Technology               | 1         | 0.12%   |
| Conwise Technology              | 1         | 0.12%   |
| Alps Electric                   | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 138       | 16.87%  |
| Realtek Bluetooth Radio                               | 85        | 10.39%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 55        | 6.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 54        | 6.6%    |
| Intel AX201 Bluetooth                                 | 52        | 6.36%   |
| Realtek  Bluetooth 4.2 Adapter                        | 44        | 5.38%   |
| Intel AX200 Bluetooth                                 | 35        | 4.28%   |
| Qualcomm Atheros  Bluetooth Device                    | 33        | 4.03%   |
| Intel Wireless-AC 3168 Bluetooth                      | 19        | 2.32%   |
| Realtek RTL8723B Bluetooth                            | 17        | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 16        | 1.96%   |
| IMC Networks Bluetooth Radio                          | 16        | 1.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 14        | 1.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 12        | 1.47%   |
| IMC Networks Bluetooth Device                         | 12        | 1.47%   |
| Lite-On Bluetooth Device                              | 11        | 1.34%   |
| Intel Bluetooth Device                                | 9         | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 8         | 0.98%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 8         | 0.98%   |
| Ralink RT3290 Bluetooth                               | 7         | 0.86%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 7         | 0.86%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                  | 7         | 0.86%   |
| Toshiba Bluetooth USB Host Controller                 | 6         | 0.73%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 6         | 0.73%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 6         | 0.73%   |
| Foxconn / Hon Hai Bluetooth Device                    | 6         | 0.73%   |
| Apple Bluetooth USB Host Controller                   | 6         | 0.73%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device          | 5         | 0.61%   |
| IMC Networks Wireless_Device                          | 5         | 0.61%   |
| Dell Wireless 365 Bluetooth                           | 5         | 0.61%   |
| Realtek RTL8821A Bluetooth                            | 4         | 0.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 4         | 0.49%   |
| Intel AX210 Bluetooth                                 | 4         | 0.49%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device       | 4         | 0.49%   |
| Dell DW375 Bluetooth Module                           | 4         | 0.49%   |
| Apple Bluetooth HCI                                   | 4         | 0.49%   |
| TP-Link UB500 Adapter                                 | 3         | 0.37%   |
| Lite-On Bluetooth Radio                               | 3         | 0.37%   |
| Lite-On Atheros AR3012 Bluetooth                      | 3         | 0.37%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 3         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1160      | 53.83%  |
| AMD                                             | 504       | 23.39%  |
| Nvidia                                          | 279       | 12.95%  |
| Logitech                                        | 37        | 1.72%   |
| C-Media Electronics                             | 30        | 1.39%   |
| VIA Technologies                                | 18        | 0.84%   |
| Silicon Integrated Systems [SiS]                | 15        | 0.7%    |
| Kingston Technology                             | 15        | 0.7%    |
| Texas Instruments                               | 8         | 0.37%   |
| Generalplus Technology                          | 7         | 0.32%   |
| Focusrite-Novation                              | 7         | 0.32%   |
| Creative Labs                                   | 7         | 0.32%   |
| Plantronics                                     | 6         | 0.28%   |
| M-Audio                                         | 4         | 0.19%   |
| GN Netcom                                       | 4         | 0.19%   |
| Elite Silicon                                   | 4         | 0.19%   |
| Samson Technologies                             | 3         | 0.14%   |
| Fry's Electronics                               | 3         | 0.14%   |
| ESI Audiotechnik                                | 3         | 0.14%   |
| Creative Technology                             | 3         | 0.14%   |
| ASUSTek Computer                                | 3         | 0.14%   |
| Astro Gaming                                    | 3         | 0.14%   |
| Realtek Semiconductor                           | 2         | 0.09%   |
| Razer USA                                       | 2         | 0.09%   |
| Microsoft                                       | 2         | 0.09%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.09%   |
| Ensoniq                                         | 2         | 0.09%   |
| BEHRINGER International                         | 2         | 0.09%   |
| ATI Technologies                                | 2         | 0.09%   |
| Yamaha                                          | 1         | 0.05%   |
| TEAC                                            | 1         | 0.05%   |
| Samsung Electronics                             | 1         | 0.05%   |
| Pro-Ject                                        | 1         | 0.05%   |
| Micro Star International                        | 1         | 0.05%   |
| Lenovo                                          | 1         | 0.05%   |
| JMTek                                           | 1         | 0.05%   |
| Holtek Semiconductor                            | 1         | 0.05%   |
| Hewlett-Packard                                 | 1         | 0.05%   |
| Giga-Byte Technology                            | 1         | 0.05%   |
| FDUCE PRO AUDIO MADE                            | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 143       | 5.44%   |
| AMD Family 17h/19h HD Audio Controller                                     | 129       | 4.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 126       | 4.79%   |
| AMD FCH Azalia Controller                                                  | 107       | 4.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 105       | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 102       | 3.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 81        | 3.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 75        | 2.85%   |
| Nvidia MCP61 High Definition Audio                                         | 65        | 2.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 65        | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 52        | 1.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 51        | 1.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 48        | 1.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 46        | 1.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 43        | 1.64%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 43        | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 42        | 1.6%    |
| AMD Starship/Matisse HD Audio Controller                                   | 41        | 1.56%   |
| AMD Kabini HDMI/DP Audio                                                   | 41        | 1.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 37        | 1.41%   |
| Intel Comet Lake PCH-LP cAVS                                               | 35        | 1.33%   |
| Intel Broadwell-U Audio Controller                                         | 34        | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 32        | 1.22%   |
| Intel Haswell-ULT HD Audio Controller                                      | 31        | 1.18%   |
| Intel 8 Series HD Audio Controller                                         | 31        | 1.18%   |
| Intel 200 Series PCH HD Audio                                              | 31        | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 30        | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 30        | 1.14%   |
| AMD Trinity HDMI Audio Controller                                          | 29        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 27        | 1.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 27        | 1.03%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 27        | 1.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 26        | 0.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 26        | 0.99%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 26        | 0.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 25        | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 25        | 0.95%   |
| Intel Cannon Lake PCH cAVS                                                 | 24        | 0.91%   |
| Nvidia High Definition Audio Controller                                    | 23        | 0.88%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 23        | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Kingston                                         | 251       | 24.23%  |
| Samsung Electronics                              | 186       | 17.95%  |
| SK hynix                                         | 127       | 12.26%  |
| Unknown                                          | 117       | 11.29%  |
| Crucial                                          | 53        | 5.12%   |
| Micron Technology                                | 50        | 4.83%   |
| A-DATA Technology                                | 37        | 3.57%   |
| Corsair                                          | 35        | 3.38%   |
| Unknown (ABCD)                                   | 13        | 1.25%   |
| Nanya Technology                                 | 13        | 1.25%   |
| Magnum Tech                                      | 13        | 1.25%   |
| Novatech                                         | 11        | 1.06%   |
| G.Skill                                          | 10        | 0.97%   |
| Goldkey                                          | 9         | 0.87%   |
| Elpida                                           | 9         | 0.87%   |
| Unknown                                          | 9         | 0.87%   |
| Patriot                                          | 8         | 0.77%   |
| Avant                                            | 8         | 0.77%   |
| Ramaxel Technology                               | 7         | 0.68%   |
| Transcend                                        | 5         | 0.48%   |
| Super Talent                                     | 5         | 0.48%   |
| Saikano                                          | 5         | 0.48%   |
| Memox                                            | 5         | 0.48%   |
| Hewlett-Packard                                  | 5         | 0.48%   |
| Team                                             | 4         | 0.39%   |
| PNY                                              | 3         | 0.29%   |
| Neo Forza                                        | 3         | 0.29%   |
| CSX                                              | 3         | 0.29%   |
| Apacer                                           | 3         | 0.29%   |
| 48spaces                                         | 3         | 0.29%   |
| Teikon                                           | 2         | 0.19%   |
| Ramos Technology                                 | 2         | 0.19%   |
| Netac                                            | 2         | 0.19%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.1%    |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.1%    |
| Unknown (07D5)                                   | 1         | 0.1%    |
| Toshiba                                          | 1         | 0.1%    |
| Thermaltake                                      | 1         | 0.1%    |
| SHARETRONIC                                      | 1         | 0.1%    |
| Qimonda                                          | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 1.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 1.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 12        | 1.07%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 1.07%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.07%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s              | 12        | 1.07%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.89%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 9         | 0.8%    |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s             | 9         | 0.8%    |
| Unknown                                                          | 9         | 0.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.71%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 8         | 0.71%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.63%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.63%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 7         | 0.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.54%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 6         | 0.54%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s              | 6         | 0.54%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.45%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 5         | 0.45%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.45%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.45%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.45%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s            | 5         | 0.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 4         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 4         | 0.36%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.36%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 4         | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.36%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 4         | 0.36%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.36%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.36%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.36%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.36%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 381       | 44%     |
| DDR3    | 325       | 37.53%  |
| DDR2    | 49        | 5.66%   |
| Unknown | 40        | 4.62%   |
| LPDDR4  | 25        | 2.89%   |
| SDRAM   | 21        | 2.42%   |
| LPDDR3  | 10        | 1.15%   |
| DDR     | 9         | 1.04%   |
| DRAM    | 4         | 0.46%   |
| LPDDR5  | 1         | 0.12%   |
| DDR5    | 1         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 486       | 56.18%  |
| DIMM         | 340       | 39.31%  |
| Row Of Chips | 36        | 4.16%   |
| Chip         | 2         | 0.23%   |
| Unknown      | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 377       | 38.55%  |
| 4096  | 293       | 29.96%  |
| 2048  | 147       | 15.03%  |
| 16384 | 101       | 10.33%  |
| 1024  | 34        | 3.48%   |
| 32768 | 19        | 1.94%   |
| 512   | 5         | 0.51%   |
| 6144  | 1         | 0.1%    |
| 256   | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 194       | 19.74%  |
| 2667    | 153       | 15.56%  |
| 3200    | 120       | 12.21%  |
| 1333    | 103       | 10.48%  |
| 2400    | 80        | 8.14%   |
| 2133    | 44        | 4.48%   |
| 1334    | 34        | 3.46%   |
| Unknown | 31        | 3.15%   |
| 667     | 25        | 2.54%   |
| 3600    | 21        | 2.14%   |
| 3266    | 15        | 1.53%   |
| 800     | 15        | 1.53%   |
| 3400    | 11        | 1.12%   |
| 2666    | 11        | 1.12%   |
| 1067    | 11        | 1.12%   |
| 1066    | 11        | 1.12%   |
| 533     | 11        | 1.12%   |
| 1866    | 10        | 1.02%   |
| 3466    | 9         | 0.92%   |
| 333     | 8         | 0.81%   |
| 3000    | 7         | 0.71%   |
| 4199    | 6         | 0.61%   |
| 400     | 6         | 0.61%   |
| 2933    | 5         | 0.51%   |
| 1867    | 5         | 0.51%   |
| 4267    | 4         | 0.41%   |
| 975     | 4         | 0.41%   |
| 2800    | 3         | 0.31%   |
| 2048    | 3         | 0.31%   |
| 8400    | 2         | 0.2%    |
| 3933    | 2         | 0.2%    |
| 3151    | 2         | 0.2%    |
| 3007    | 2         | 0.2%    |
| 6400    | 1         | 0.1%    |
| 4800    | 1         | 0.1%    |
| 4266    | 1         | 0.1%    |
| 3866    | 1         | 0.1%    |
| 3733    | 1         | 0.1%    |
| 3533    | 1         | 0.1%    |
| 3500    | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 27        | 46.55%  |
| Brother Industries  | 17        | 29.31%  |
| Seiko Epson         | 5         | 8.62%   |
| Samsung Electronics | 3         | 5.17%   |
| Ricoh               | 1         | 1.72%   |
| QinHeng Electronics | 1         | 1.72%   |
| Pantum              | 1         | 1.72%   |
| NXP Semiconductors  | 1         | 1.72%   |
| Kyocera             | 1         | 1.72%   |
| Graphtec America    | 1         | 1.72%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| HP LaserJet Professional P1102w               | 5         | 8.62%   |
| Brother HL-1200 series                        | 4         | 6.9%    |
| Brother HL-1110 series                        | 4         | 6.9%    |
| HP LaserJet Professional P 1102w              | 3         | 5.17%   |
| Brother HL-1210W series                       | 3         | 5.17%   |
| Samsung M2020 Series                          | 2         | 3.45%   |
| HP LaserJet P1006                             | 2         | 3.45%   |
| HP LaserJet P1005                             | 2         | 3.45%   |
| HP Ink Tank 110 series                        | 2         | 3.45%   |
| Brother HL-2130 series                        | 2         | 3.45%   |
| Brother DCP-7055 scanner/printer              | 2         | 3.45%   |
| Seiko Epson XP-243 245 247 Series             | 1         | 1.72%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.72%   |
| Seiko Epson L355 Series                       | 1         | 1.72%   |
| Seiko Epson L120 Series                       | 1         | 1.72%   |
| Seiko Epson ET-2700 Series                    | 1         | 1.72%   |
| Samsung Xerox Phaser 3117 Laser Printer       | 1         | 1.72%   |
| Ricoh Printing Support                        | 1         | 1.72%   |
| QinHeng CH340S                                | 1         | 1.72%   |
| Pantum P2500W series                          | 1         | 1.72%   |
| NXP Semiconductors Printer-80                 | 1         | 1.72%   |
| Kyocera ECOSYS M3550idn                       | 1         | 1.72%   |
| HP PSC 1400                                   | 1         | 1.72%   |
| HP Laserjet P1505                             | 1         | 1.72%   |
| HP LaserJet 3050                              | 1         | 1.72%   |
| HP LaserJet 1020                              | 1         | 1.72%   |
| HP Ink Tank Wireless 410 series               | 1         | 1.72%   |
| HP DeskJet F4100 Printer series               | 1         | 1.72%   |
| HP DeskJet F300 series                        | 1         | 1.72%   |
| HP DeskJet 810c/812c                          | 1         | 1.72%   |
| HP DeskJet 3630 series                        | 1         | 1.72%   |
| HP Deskjet 3050 J610 series                   | 1         | 1.72%   |
| HP DeskJet 2600 series                        | 1         | 1.72%   |
| HP Deskjet 2050 J510                          | 1         | 1.72%   |
| HP Color LaserJet Pro M478f-9f                | 1         | 1.72%   |
| Graphtec America Graphtec Printer             | 1         | 1.72%   |
| Brother DCP-1610NW                            | 1         | 1.72%   |
| Brother DCP-1600                              | 1         | 1.72%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP ScanJet 2400c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 211       | 20.73%  |
| IMC Networks                           | 92        | 9.04%   |
| Realtek Semiconductor                  | 83        | 8.15%   |
| Microdia                               | 74        | 7.27%   |
| Bison Electronics                      | 51        | 5.01%   |
| Acer                                   | 46        | 4.52%   |
| Logitech                               | 42        | 4.13%   |
| Sunplus Innovation Technology          | 38        | 3.73%   |
| Syntek                                 | 36        | 3.54%   |
| Alcor Micro                            | 33        | 3.24%   |
| Suyin                                  | 32        | 3.14%   |
| Silicon Motion                         | 32        | 3.14%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 3.14%   |
| Quanta                                 | 31        | 3.05%   |
| Apple                                  | 19        | 1.87%   |
| Samsung Electronics                    | 18        | 1.77%   |
| Z-Star Microelectronics                | 14        | 1.38%   |
| Luxvisions Innotech Limited            | 12        | 1.18%   |
| Lite-On Technology                     | 12        | 1.18%   |
| KYE Systems (Mouse Systems)            | 12        | 1.18%   |
| Generalplus Technology                 | 12        | 1.18%   |
| Ricoh                                  | 10        | 0.98%   |
| OmniVision Technologies                | 7         | 0.69%   |
| Microsoft                              | 7         | 0.69%   |
| Jieli Technology                       | 6         | 0.59%   |
| Sonix Technology                       | 5         | 0.49%   |
| icSpring                               | 5         | 0.49%   |
| SunplusIT                              | 4         | 0.39%   |
| GEMBIRD                                | 4         | 0.39%   |
| Cubeternet                             | 4         | 0.39%   |
| ALi                                    | 4         | 0.39%   |
| Y Media                                | 3         | 0.29%   |
| MacroSilicon                           | 3         | 0.29%   |
| Lenovo                                 | 3         | 0.29%   |
| Razer USA                              | 2         | 0.2%    |
| Pixart Imaging                         | 2         | 0.2%    |
| Intel                                  | 2         | 0.2%    |
| Importek                               | 2         | 0.2%    |
| Genesys Logic                          | 2         | 0.2%    |
| Aveo Technology                        | 2         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                         | 33        | 3.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 31        | 3.03%   |
| IMC Networks Integrated Camera                                 | 25        | 2.44%   |
| Alcor Micro USB 2.0 Camera                                     | 23        | 2.25%   |
| Realtek Integrated_Webcam_HD                                   | 21        | 2.05%   |
| Microdia Integrated_Webcam_HD                                  | 20        | 1.95%   |
| Bison Integrated Camera                                        | 20        | 1.95%   |
| Chicony Integrated Camera                                      | 19        | 1.86%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 17        | 1.66%   |
| Realtek USB Camera                                             | 17        | 1.66%   |
| Chicony Lenovo EasyCamera                                      | 15        | 1.46%   |
| Acer Integrated Camera                                         | 15        | 1.46%   |
| Chicony USB2.0 Camera                                          | 14        | 1.37%   |
| Syntek Integrated Camera                                       | 13        | 1.27%   |
| Logitech Webcam C270                                           | 13        | 1.27%   |
| Chicony HD Webcam                                              | 13        | 1.27%   |
| Sunplus Integrated_Webcam_HD                                   | 12        | 1.17%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 11        | 1.07%   |
| Chicony TOSHIBA Web Camera - HD                                | 10        | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 10        | 0.98%   |
| Luxvisions Innotech Limited Integrated Camera                  | 9         | 0.88%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 9         | 0.88%   |
| Silicon Motion WebCam SC-0311139N                              | 8         | 0.78%   |
| Logitech C922 Pro Stream Webcam                                | 8         | 0.78%   |
| Generalplus GENERAL WEBCAM                                     | 8         | 0.78%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 8         | 0.78%   |
| Chicony HP Wide Vision HD Camera                               | 8         | 0.78%   |
| Bison SunplusIT Integrated Camera                              | 8         | 0.78%   |
| Acer BisonCam, NB Pro                                          | 8         | 0.78%   |
| Microdia Webcam Vitade AF                                      | 7         | 0.68%   |
| Chicony Integrated Camera (1280x720@30)                        | 7         | 0.68%   |
| Chicony HP TrueVision HD Camera                                | 7         | 0.68%   |
| Bison Lenovo EasyCamera                                        | 7         | 0.68%   |
| Alcor Micro USB 2.0 PC Camera                                  | 7         | 0.68%   |
| Z-Star Webcam                                                  | 6         | 0.59%   |
| Syntek Lenovo EasyCamera                                       | 6         | 0.59%   |
| Syntek EasyCamera                                              | 6         | 0.59%   |
| Sunplus Asus Webcam                                            | 6         | 0.59%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 6         | 0.59%   |
| Microdia Integrated Webcam                                     | 6         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 44        | 36.07%  |
| Validity Sensors           | 31        | 25.41%  |
| Shenzhen Goodix Technology | 24        | 19.67%  |
| Elan Microelectronics      | 7         | 5.74%   |
| AuthenTec                  | 6         | 4.92%   |
| Upek                       | 4         | 3.28%   |
| LighTuning Technology      | 3         | 2.46%   |
| STMicroelectronics         | 1         | 0.82%   |
| Focal-systems.Corp         | 1         | 0.82%   |
| DigitalPersona             | 1         | 0.82%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 15.57%  |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 13.93%  |
| Synaptics  WBDI                                                            | 13        | 10.66%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 5.74%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 4.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 4.1%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.28%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 3.28%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.28%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.46%   |
| Synaptics WBDI                                                             | 3         | 2.46%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.46%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.46%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.64%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.64%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.64%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.64%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.64%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.64%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.64%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.82%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.82%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.82%   |
| Synaptics UWP WBDI                                                         | 1         | 0.82%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.82%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.82%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.82%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.82%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.82%   |
| AuthenTec AES2810                                                          | 1         | 0.82%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.82%   |
| Unknown                                                                    | 1         | 0.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 21        | 61.76%  |
| Upek        | 9         | 26.47%  |
| Lenovo      | 2         | 5.88%   |
| O2 Micro    | 1         | 2.94%   |
| Alcor Micro | 1         | 2.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 26.47%  |
| Broadcom 58200                                                               | 7         | 20.59%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 17.65%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 14.71%  |
| Broadcom 5880                                                                | 3         | 8.82%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.94%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 2.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1344      | 76.28%  |
| 1     | 364       | 20.66%  |
| 2     | 46        | 2.61%   |
| 3     | 5         | 0.28%   |
| 8     | 1         | 0.06%   |
| 5     | 1         | 0.06%   |
| 4     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 136       | 28.75%  |
| Fingerprint reader       | 121       | 25.58%  |
| Net/wireless             | 79        | 16.7%   |
| Chipcard                 | 32        | 6.77%   |
| Camera                   | 21        | 4.44%   |
| Multimedia controller    | 17        | 3.59%   |
| Communication controller | 14        | 2.96%   |
| Bluetooth                | 14        | 2.96%   |
| Sound                    | 9         | 1.9%    |
| Net/ethernet             | 9         | 1.9%    |
| Modem                    | 5         | 1.06%   |
| Network                  | 4         | 0.85%   |
| Unassigned class         | 3         | 0.63%   |
| Storage/ide              | 2         | 0.42%   |
| Flash memory             | 2         | 0.42%   |
| Firewire controller      | 2         | 0.42%   |
| Card reader              | 2         | 0.42%   |
| Dvb card                 | 1         | 0.21%   |

