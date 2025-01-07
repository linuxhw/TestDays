Pop!_OS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS/Desktop/README.md) and [notebooks](/Dist/Pop!_OS/Notebook/README.md).

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

Total: 17699

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [1ff9c9f7cb](https://linux-hardware.org/?probe=1ff9c9f7cb) | Jan 06, 2025 |
| ASUSTek       | F5N                         | Notebook    | [b04fac9072](https://linux-hardware.org/?probe=b04fac9072) | Jan 06, 2025 |
| MSI           | Modern 15 H AI C1MTG        | Notebook    | [4e43ee30f8](https://linux-hardware.org/?probe=4e43ee30f8) | Jan 06, 2025 |
| MSI           | Modern 15 H AI C1MTG        | Notebook    | [ed4c4c8261](https://linux-hardware.org/?probe=ed4c4c8261) | Jan 06, 2025 |
| Acidanther... | Mac-4B682C642B45593E iMa... | All in one  | [105d641565](https://linux-hardware.org/?probe=105d641565) | Jan 06, 2025 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [8ad221e4e7](https://linux-hardware.org/?probe=8ad221e4e7) | Jan 06, 2025 |
| Dell          | Latitude 5320               | Notebook    | [c7f4eada6c](https://linux-hardware.org/?probe=c7f4eada6c) | Jan 06, 2025 |
| Acidanther... | Mac-4B682C642B45593E iMa... | All in one  | [3f87777dfa](https://linux-hardware.org/?probe=3f87777dfa) | Jan 05, 2025 |
| Gigabyte      | H370M D3H GSM-CF            | Desktop     | [639eb0e4fc](https://linux-hardware.org/?probe=639eb0e4fc) | Jan 05, 2025 |
| Lenovo        | ThinkPad T440s 20ARS46M0... | Notebook    | [17ac336e9c](https://linux-hardware.org/?probe=17ac336e9c) | Jan 05, 2025 |
| Gigabyte      | B650M D3HP                  | Desktop     | [0d0a62d437](https://linux-hardware.org/?probe=0d0a62d437) | Jan 05, 2025 |
| Lenovo        | ThinkPad T540p 20BFS0Y00... | Notebook    | [8e40087118](https://linux-hardware.org/?probe=8e40087118) | Jan 05, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [0699689325](https://linux-hardware.org/?probe=0699689325) | Jan 05, 2025 |
| ASUSTek       | X71Sr                       | Notebook    | [c76c5d5a1c](https://linux-hardware.org/?probe=c76c5d5a1c) | Jan 05, 2025 |
| Apple         | MacBookPro11,1              | Notebook    | [e994e68b69](https://linux-hardware.org/?probe=e994e68b69) | Jan 05, 2025 |
| Gigabyte      | B550 UD AC-Y1               | Desktop     | [b5d5a649e6](https://linux-hardware.org/?probe=b5d5a649e6) | Jan 05, 2025 |
| Apple         | MacBookPro5,5               | Notebook    | [de39de3147](https://linux-hardware.org/?probe=de39de3147) | Jan 05, 2025 |
| Shenzhen M... | F7BSC                       | Mini pc     | [abbe5e18a9](https://linux-hardware.org/?probe=abbe5e18a9) | Jan 04, 2025 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | Notebook    | [370ebbc151](https://linux-hardware.org/?probe=370ebbc151) | Jan 04, 2025 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6fc9bee528](https://linux-hardware.org/?probe=6fc9bee528) | Jan 04, 2025 |
| Apple         | Mac-F221BEC8                | Desktop     | [05de585a46](https://linux-hardware.org/?probe=05de585a46) | Jan 04, 2025 |
| Apple         | MacBookPro11,1              | Notebook    | [370a49426e](https://linux-hardware.org/?probe=370a49426e) | Jan 04, 2025 |
| ASUSTek       | X71Sr                       | Notebook    | [c17afe99ee](https://linux-hardware.org/?probe=c17afe99ee) | Jan 03, 2025 |
| Gigabyte      | H370M D3H GSM-CF            | Desktop     | [305c971d23](https://linux-hardware.org/?probe=305c971d23) | Jan 03, 2025 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [e8f18de27b](https://linux-hardware.org/?probe=e8f18de27b) | Jan 03, 2025 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [427c508e21](https://linux-hardware.org/?probe=427c508e21) | Jan 03, 2025 |
| ASRock        | B450M/ac                    | Desktop     | [58bf1994a2](https://linux-hardware.org/?probe=58bf1994a2) | Jan 03, 2025 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [91839e20df](https://linux-hardware.org/?probe=91839e20df) | Jan 03, 2025 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7526506dc2](https://linux-hardware.org/?probe=7526506dc2) | Jan 03, 2025 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [e91eadd16c](https://linux-hardware.org/?probe=e91eadd16c) | Jan 02, 2025 |
| System76      | Oryx Pro                    | Notebook    | [3e45c3caac](https://linux-hardware.org/?probe=3e45c3caac) | Jan 02, 2025 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [ca8b287117](https://linux-hardware.org/?probe=ca8b287117) | Jan 02, 2025 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [849e3021f2](https://linux-hardware.org/?probe=849e3021f2) | Jan 02, 2025 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [248a1406ed](https://linux-hardware.org/?probe=248a1406ed) | Jan 02, 2025 |
| Dell          | Inspiron 3558               | Notebook    | [06fdffd5e6](https://linux-hardware.org/?probe=06fdffd5e6) | Jan 02, 2025 |
| MSI           | B450 TOMAHAWK               | Desktop     | [77e32dabcd](https://linux-hardware.org/?probe=77e32dabcd) | Jan 02, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [3bb27ee500](https://linux-hardware.org/?probe=3bb27ee500) | Jan 02, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [f2f5dbd7b9](https://linux-hardware.org/?probe=f2f5dbd7b9) | Jan 01, 2025 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [497be29097](https://linux-hardware.org/?probe=497be29097) | Jan 01, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8782970610](https://linux-hardware.org/?probe=8782970610) | Jan 01, 2025 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a15d70317f](https://linux-hardware.org/?probe=a15d70317f) | Jan 01, 2025 |
| Dell          | Inspiron 7520               | Notebook    | [d24db96b79](https://linux-hardware.org/?probe=d24db96b79) | Jan 01, 2025 |
| ASUSTek       | PRIME B760M-A AX6 II        | Desktop     | [1012b4d63f](https://linux-hardware.org/?probe=1012b4d63f) | Jan 01, 2025 |
| ASUSTek       | PRIME B760M-A AX6 II        | Desktop     | [e3f9df9d9e](https://linux-hardware.org/?probe=e3f9df9d9e) | Jan 01, 2025 |
| MSI           | A68HM GAMING                | Desktop     | [d12ab6c4d3](https://linux-hardware.org/?probe=d12ab6c4d3) | Jan 01, 2025 |
| ASRock        | N68-S UCC                   | Desktop     | [b83c60bccf](https://linux-hardware.org/?probe=b83c60bccf) | Jan 01, 2025 |
| Dell          | G15 5520                    | Notebook    | [19d5a43273](https://linux-hardware.org/?probe=19d5a43273) | Jan 01, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [e6da658e0f](https://linux-hardware.org/?probe=e6da658e0f) | Jan 01, 2025 |
| Acer          | Aspire ES1-572              | Notebook    | [419ddbb177](https://linux-hardware.org/?probe=419ddbb177) | Dec 31, 2024 |
| Acer          | Aspire ES1-572              | Notebook    | [dc58f6466e](https://linux-hardware.org/?probe=dc58f6466e) | Dec 31, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [079f7f1707](https://linux-hardware.org/?probe=079f7f1707) | Dec 31, 2024 |
| ASRock        | H570M Pro4                  | Desktop     | [ae9219a819](https://linux-hardware.org/?probe=ae9219a819) | Dec 31, 2024 |
| ASRock        | N68-S UCC                   | Desktop     | [e48cfb70c6](https://linux-hardware.org/?probe=e48cfb70c6) | Dec 31, 2024 |
| ASRock        | N68-S UCC                   | Desktop     | [a53617b9d5](https://linux-hardware.org/?probe=a53617b9d5) | Dec 31, 2024 |
| Microsoft     | Surface Book                | Tablet      | [e334442819](https://linux-hardware.org/?probe=e334442819) | Dec 31, 2024 |
| Acer          | Aspire A114-32              | Notebook    | [3af2175d58](https://linux-hardware.org/?probe=3af2175d58) | Dec 31, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [903e299f16](https://linux-hardware.org/?probe=903e299f16) | Dec 30, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [77c2d20feb](https://linux-hardware.org/?probe=77c2d20feb) | Dec 30, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [a509973046](https://linux-hardware.org/?probe=a509973046) | Dec 30, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [1e4cb7054c](https://linux-hardware.org/?probe=1e4cb7054c) | Dec 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b16417fac3](https://linux-hardware.org/?probe=b16417fac3) | Dec 30, 2024 |
| HP            | EliteBook 840 Aero G8 No... | Notebook    | [af5219d90f](https://linux-hardware.org/?probe=af5219d90f) | Dec 30, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [4bccbc5b01](https://linux-hardware.org/?probe=4bccbc5b01) | Dec 29, 2024 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [f89abca0f9](https://linux-hardware.org/?probe=f89abca0f9) | Dec 29, 2024 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [0e48acaa7e](https://linux-hardware.org/?probe=0e48acaa7e) | Dec 29, 2024 |
| ASUSTek       | TP500LN                     | Notebook    | [beeccb21e7](https://linux-hardware.org/?probe=beeccb21e7) | Dec 29, 2024 |
| ASUSTek       | TP500LN                     | Notebook    | [e71efdddcc](https://linux-hardware.org/?probe=e71efdddcc) | Dec 29, 2024 |
| ASUSTek       | Z97-K                       | Desktop     | [53f0c1c555](https://linux-hardware.org/?probe=53f0c1c555) | Dec 29, 2024 |
| Lenovo        | Legion Pro 7 16ARX8H 82W... | Notebook    | [702096b561](https://linux-hardware.org/?probe=702096b561) | Dec 29, 2024 |
| Lenovo        | Legion Pro 7 16ARX8H 82W... | Notebook    | [968258cf48](https://linux-hardware.org/?probe=968258cf48) | Dec 29, 2024 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [9fa8931c0b](https://linux-hardware.org/?probe=9fa8931c0b) | Dec 29, 2024 |
| Lenovo        | 31900058 STD                | All in one  | [4eb5763e89](https://linux-hardware.org/?probe=4eb5763e89) | Dec 29, 2024 |
| ASUSTek       | F1A75-M-PRO R2.0            | Desktop     | [8485c1ce27](https://linux-hardware.org/?probe=8485c1ce27) | Dec 28, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [c93ac190a0](https://linux-hardware.org/?probe=c93ac190a0) | Dec 28, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [eb1589c7c0](https://linux-hardware.org/?probe=eb1589c7c0) | Dec 28, 2024 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [39e50a00e4](https://linux-hardware.org/?probe=39e50a00e4) | Dec 28, 2024 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [4182d5a5ec](https://linux-hardware.org/?probe=4182d5a5ec) | Dec 28, 2024 |
| HP            | 8265                        | Desktop     | [3b63487fcf](https://linux-hardware.org/?probe=3b63487fcf) | Dec 28, 2024 |
| HP            | EliteBook 8540p             | Notebook    | [3fba3ebc56](https://linux-hardware.org/?probe=3fba3ebc56) | Dec 27, 2024 |
| Acer          | Aspire VX5-591G             | Notebook    | [723f61dbcf](https://linux-hardware.org/?probe=723f61dbcf) | Dec 27, 2024 |
| Acer          | Aspire VX5-591G             | Notebook    | [773ac488ff](https://linux-hardware.org/?probe=773ac488ff) | Dec 27, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [b892b107e9](https://linux-hardware.org/?probe=b892b107e9) | Dec 27, 2024 |
| ASRock        | H110M-HDV                   | Desktop     | [4501aaefe1](https://linux-hardware.org/?probe=4501aaefe1) | Dec 27, 2024 |
| System76      | Gazelle                     | Notebook    | [cb477659f5](https://linux-hardware.org/?probe=cb477659f5) | Dec 27, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [5320a7c488](https://linux-hardware.org/?probe=5320a7c488) | Dec 27, 2024 |
| Fujitsu       | FARQ17004                   | Tablet      | [a8c473704c](https://linux-hardware.org/?probe=a8c473704c) | Dec 27, 2024 |
| Chuwi         | MiniBook X                  | Notebook    | [2959afdb7e](https://linux-hardware.org/?probe=2959afdb7e) | Dec 27, 2024 |
| ASRock        | H110M-HDV                   | Desktop     | [eb488f568b](https://linux-hardware.org/?probe=eb488f568b) | Dec 26, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [8c323a18f3](https://linux-hardware.org/?probe=8c323a18f3) | Dec 26, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [68bd4716f4](https://linux-hardware.org/?probe=68bd4716f4) | Dec 26, 2024 |
| Dell          | G15 5510                    | Notebook    | [e381abffc2](https://linux-hardware.org/?probe=e381abffc2) | Dec 26, 2024 |
| Acer          | Aspire E1-731               | Notebook    | [e633d3e555](https://linux-hardware.org/?probe=e633d3e555) | Dec 26, 2024 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [283a58ac15](https://linux-hardware.org/?probe=283a58ac15) | Dec 26, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [9fcbcdf645](https://linux-hardware.org/?probe=9fcbcdf645) | Dec 26, 2024 |
| System76      | Oryx Pro                    | Notebook    | [336ade52bd](https://linux-hardware.org/?probe=336ade52bd) | Dec 25, 2024 |
| Dell          | 0WPMFG A00                  | Desktop     | [32af132170](https://linux-hardware.org/?probe=32af132170) | Dec 25, 2024 |
| Dell          | 0XHGV1 A00                  | Desktop     | [017302e467](https://linux-hardware.org/?probe=017302e467) | Dec 25, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [fab3c1d036](https://linux-hardware.org/?probe=fab3c1d036) | Dec 25, 2024 |
| HP            | 8906 SMVB                   | Desktop     | [7c1ad30996](https://linux-hardware.org/?probe=7c1ad30996) | Dec 25, 2024 |
| MSI           | Z370 GAMING PRO CARBON A... | Desktop     | [46c1540093](https://linux-hardware.org/?probe=46c1540093) | Dec 24, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | Notebook    | [658f4969be](https://linux-hardware.org/?probe=658f4969be) | Dec 24, 2024 |
| Dell          | Precision 7670              | Notebook    | [7b879477ba](https://linux-hardware.org/?probe=7b879477ba) | Dec 24, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [bbae43def0](https://linux-hardware.org/?probe=bbae43def0) | Dec 24, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [dd6260a709](https://linux-hardware.org/?probe=dd6260a709) | Dec 24, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [9ea1b90178](https://linux-hardware.org/?probe=9ea1b90178) | Dec 23, 2024 |
| Gigabyte      | A620M DS3H                  | Desktop     | [2993fdb631](https://linux-hardware.org/?probe=2993fdb631) | Dec 23, 2024 |
| HP            | 3396                        | Desktop     | [6e2c93c063](https://linux-hardware.org/?probe=6e2c93c063) | Dec 23, 2024 |
| HP            | 3396                        | Desktop     | [a237d63fa3](https://linux-hardware.org/?probe=a237d63fa3) | Dec 23, 2024 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [5e9a07ac33](https://linux-hardware.org/?probe=5e9a07ac33) | Dec 23, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [ca3ac47c6d](https://linux-hardware.org/?probe=ca3ac47c6d) | Dec 23, 2024 |
| Gigabyte      | X570S AERO G                | Desktop     | [f4832ab80c](https://linux-hardware.org/?probe=f4832ab80c) | Dec 23, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b9260cccc7](https://linux-hardware.org/?probe=b9260cccc7) | Dec 22, 2024 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [a1beeae5b9](https://linux-hardware.org/?probe=a1beeae5b9) | Dec 22, 2024 |
| ASUSTek       | X510UQR                     | Notebook    | [f0c040e507](https://linux-hardware.org/?probe=f0c040e507) | Dec 22, 2024 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [bdb9de439f](https://linux-hardware.org/?probe=bdb9de439f) | Dec 22, 2024 |
| HP            | 3397                        | Desktop     | [d72e973be9](https://linux-hardware.org/?probe=d72e973be9) | Dec 22, 2024 |
| MSI           | B560M-A PRO                 | Desktop     | [814f11f38f](https://linux-hardware.org/?probe=814f11f38f) | Dec 22, 2024 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [a5df0d3fd9](https://linux-hardware.org/?probe=a5df0d3fd9) | Dec 22, 2024 |
| ASRock        | X670E PG Lightning          | Desktop     | [a87b7ceb23](https://linux-hardware.org/?probe=a87b7ceb23) | Dec 22, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c0bbc9c576](https://linux-hardware.org/?probe=c0bbc9c576) | Dec 22, 2024 |
| Acer          | Aspire E1-731               | Notebook    | [24c0bfe676](https://linux-hardware.org/?probe=24c0bfe676) | Dec 21, 2024 |
| Unknown       | X99-D8                      | Desktop     | [0bd81498ad](https://linux-hardware.org/?probe=0bd81498ad) | Dec 21, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [81c6c26fa4](https://linux-hardware.org/?probe=81c6c26fa4) | Dec 21, 2024 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS0... | Notebook    | [8eaf87896d](https://linux-hardware.org/?probe=8eaf87896d) | Dec 21, 2024 |
| ECS           | H61H2-M6                    | Desktop     | [ee83334d6e](https://linux-hardware.org/?probe=ee83334d6e) | Dec 21, 2024 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [5fddd22cc1](https://linux-hardware.org/?probe=5fddd22cc1) | Dec 20, 2024 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [58579615c1](https://linux-hardware.org/?probe=58579615c1) | Dec 20, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c83a325000](https://linux-hardware.org/?probe=c83a325000) | Dec 20, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ec52ae183b](https://linux-hardware.org/?probe=ec52ae183b) | Dec 19, 2024 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [cc8e8b062c](https://linux-hardware.org/?probe=cc8e8b062c) | Dec 19, 2024 |
| Gigabyte      | B550 GAMING X               | Desktop     | [5e7733d216](https://linux-hardware.org/?probe=5e7733d216) | Dec 19, 2024 |
| Medion        | S6445 MD61489               | Notebook    | [678fefd644](https://linux-hardware.org/?probe=678fefd644) | Dec 18, 2024 |
| Medion        | S6445 MD61489               | Notebook    | [ddd924a519](https://linux-hardware.org/?probe=ddd924a519) | Dec 18, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB0A... | Mini pc     | [b9a32b1575](https://linux-hardware.org/?probe=b9a32b1575) | Dec 18, 2024 |
| HP            | Notebook                    | Notebook    | [c08a1bb97f](https://linux-hardware.org/?probe=c08a1bb97f) | Dec 18, 2024 |
| MSI           | B150 GAMING M3              | Desktop     | [eb7d688010](https://linux-hardware.org/?probe=eb7d688010) | Dec 18, 2024 |
| ASUSTek       | X540LJ                      | Notebook    | [dff11ceadc](https://linux-hardware.org/?probe=dff11ceadc) | Dec 18, 2024 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [475c698644](https://linux-hardware.org/?probe=475c698644) | Dec 18, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [f332a63f55](https://linux-hardware.org/?probe=f332a63f55) | Dec 18, 2024 |
| Lenovo        | ThinkPad P53 MWS 15.6 (Q... | Notebook    | [a86913fde1](https://linux-hardware.org/?probe=a86913fde1) | Dec 18, 2024 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [3b9ab5404e](https://linux-hardware.org/?probe=3b9ab5404e) | Dec 17, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [29d91557b3](https://linux-hardware.org/?probe=29d91557b3) | Dec 17, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [62e2c7fe7b](https://linux-hardware.org/?probe=62e2c7fe7b) | Dec 17, 2024 |
| ASUSTek       | Z77-A                       | Desktop     | [905b20309d](https://linux-hardware.org/?probe=905b20309d) | Dec 17, 2024 |
| Lenovo        | ThinkPad L490 20Q6S23200    | Notebook    | [a13840a70a](https://linux-hardware.org/?probe=a13840a70a) | Dec 17, 2024 |
| Dell          | System XPS L502X            | Notebook    | [74f4e14d27](https://linux-hardware.org/?probe=74f4e14d27) | Dec 17, 2024 |
| Dell          | System XPS L502X            | Notebook    | [8aa720a976](https://linux-hardware.org/?probe=8aa720a976) | Dec 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [e7ce325050](https://linux-hardware.org/?probe=e7ce325050) | Dec 16, 2024 |
| Dell          | Latitude 7340               | Notebook    | [01bf0e0d2c](https://linux-hardware.org/?probe=01bf0e0d2c) | Dec 16, 2024 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [b74286b627](https://linux-hardware.org/?probe=b74286b627) | Dec 16, 2024 |
| Dell          | Latitude 9420               | Convertible | [663dfb6918](https://linux-hardware.org/?probe=663dfb6918) | Dec 16, 2024 |
| Acer          | Spin SP314-54N              | Convertible | [dfd01a6f96](https://linux-hardware.org/?probe=dfd01a6f96) | Dec 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [eaa6397d5e](https://linux-hardware.org/?probe=eaa6397d5e) | Dec 16, 2024 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [67fda65f1a](https://linux-hardware.org/?probe=67fda65f1a) | Dec 16, 2024 |
| System76      | Lemur Pro                   | Notebook    | [96252caa1e](https://linux-hardware.org/?probe=96252caa1e) | Dec 16, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3d5e444772](https://linux-hardware.org/?probe=3d5e444772) | Dec 16, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [e27d08b364](https://linux-hardware.org/?probe=e27d08b364) | Dec 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ec283efd6e](https://linux-hardware.org/?probe=ec283efd6e) | Dec 15, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [edc19c7235](https://linux-hardware.org/?probe=edc19c7235) | Dec 15, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [96ffa04014](https://linux-hardware.org/?probe=96ffa04014) | Dec 15, 2024 |
| Fujitsu       | FMVU14003                   | Notebook    | [2d5271bca3](https://linux-hardware.org/?probe=2d5271bca3) | Dec 15, 2024 |
| Intel         | NUC11PABi5 M68265-501       | Mini pc     | [b71f20be35](https://linux-hardware.org/?probe=b71f20be35) | Dec 15, 2024 |
| Lenovo        | LOQ 15IRX9 83DV             | Notebook    | [68a32fe043](https://linux-hardware.org/?probe=68a32fe043) | Dec 15, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [b3db914035](https://linux-hardware.org/?probe=b3db914035) | Dec 15, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [ee05cf00fc](https://linux-hardware.org/?probe=ee05cf00fc) | Dec 15, 2024 |
| Dell          | Latitude E6420              | Notebook    | [ed611bf07e](https://linux-hardware.org/?probe=ed611bf07e) | Dec 15, 2024 |
| JGINYUE       | B650I Night Devil Ver:      | Desktop     | [d98b74d533](https://linux-hardware.org/?probe=d98b74d533) | Dec 15, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [ea5d5a1d8f](https://linux-hardware.org/?probe=ea5d5a1d8f) | Dec 14, 2024 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [5af9a6f758](https://linux-hardware.org/?probe=5af9a6f758) | Dec 14, 2024 |
| LG Electro... | 17ZB90R-K.ADC8U1            | Notebook    | [a98308a8ff](https://linux-hardware.org/?probe=a98308a8ff) | Dec 14, 2024 |
| System76      | Galago Pro                  | Notebook    | [263161107b](https://linux-hardware.org/?probe=263161107b) | Dec 14, 2024 |
| Biostar       | A520MH                      | Desktop     | [46f468d23e](https://linux-hardware.org/?probe=46f468d23e) | Dec 14, 2024 |
| Gigabyte      | Z590 VISION D               | Desktop     | [e51c407f40](https://linux-hardware.org/?probe=e51c407f40) | Dec 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c5cf3c9a58](https://linux-hardware.org/?probe=c5cf3c9a58) | Dec 14, 2024 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [277adb5291](https://linux-hardware.org/?probe=277adb5291) | Dec 14, 2024 |
| Gigabyte      | X870 GAMING X WIFI7         | Desktop     | [bf3a0594a1](https://linux-hardware.org/?probe=bf3a0594a1) | Dec 14, 2024 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [fbf5a87269](https://linux-hardware.org/?probe=fbf5a87269) | Dec 14, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [8fd0a47047](https://linux-hardware.org/?probe=8fd0a47047) | Dec 13, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS        | Desktop     | [d46d8a8dc1](https://linux-hardware.org/?probe=d46d8a8dc1) | Dec 13, 2024 |
| Alienware     | 0K9TKY A00                  | Desktop     | [02f928f245](https://linux-hardware.org/?probe=02f928f245) | Dec 13, 2024 |
| Acer          | Nitro ANV15-41              | Notebook    | [d58a585fc6](https://linux-hardware.org/?probe=d58a585fc6) | Dec 13, 2024 |
| AMI           | Intel                       | Notebook    | [744da97070](https://linux-hardware.org/?probe=744da97070) | Dec 13, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [bc4af2a098](https://linux-hardware.org/?probe=bc4af2a098) | Dec 12, 2024 |
| Gigabyte      | B650 EAGLE                  | Desktop     | [b7d5b664b5](https://linux-hardware.org/?probe=b7d5b664b5) | Dec 12, 2024 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [adb22b56eb](https://linux-hardware.org/?probe=adb22b56eb) | Dec 12, 2024 |
| System76      | Oryx Pro                    | Notebook    | [c87371b1cb](https://linux-hardware.org/?probe=c87371b1cb) | Dec 12, 2024 |
| System76      | Thelio thelio-r2            | Desktop     | [7a66bf9502](https://linux-hardware.org/?probe=7a66bf9502) | Dec 12, 2024 |
| ASUSTek       | Z97-K                       | Desktop     | [8096f8f1b6](https://linux-hardware.org/?probe=8096f8f1b6) | Dec 12, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e0157671c5](https://linux-hardware.org/?probe=e0157671c5) | Dec 12, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [802c98fd5c](https://linux-hardware.org/?probe=802c98fd5c) | Dec 12, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [5979a585ea](https://linux-hardware.org/?probe=5979a585ea) | Dec 12, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [0913e12416](https://linux-hardware.org/?probe=0913e12416) | Dec 12, 2024 |
| Dell          | Latitude E7470              | Notebook    | [300b02bb07](https://linux-hardware.org/?probe=300b02bb07) | Dec 12, 2024 |
| Dell          | Latitude 7490               | Notebook    | [f97f9efaf8](https://linux-hardware.org/?probe=f97f9efaf8) | Dec 12, 2024 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [e5be77487d](https://linux-hardware.org/?probe=e5be77487d) | Dec 11, 2024 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [9fa51abc19](https://linux-hardware.org/?probe=9fa51abc19) | Dec 11, 2024 |
| Acer          | Aspire X3960                | Desktop     | [7bc5a0a910](https://linux-hardware.org/?probe=7bc5a0a910) | Dec 11, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [eee3f08a38](https://linux-hardware.org/?probe=eee3f08a38) | Dec 11, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [4caf21526d](https://linux-hardware.org/?probe=4caf21526d) | Dec 11, 2024 |
| Dell          | Inspiron 16 5645            | Notebook    | [0437f5d57e](https://linux-hardware.org/?probe=0437f5d57e) | Dec 11, 2024 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [ff47572b6b](https://linux-hardware.org/?probe=ff47572b6b) | Dec 11, 2024 |
| Gigabyte      | X870 EAGLE WIFI7            | Desktop     | [9d8f1f5a1c](https://linux-hardware.org/?probe=9d8f1f5a1c) | Dec 11, 2024 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [c252814d3e](https://linux-hardware.org/?probe=c252814d3e) | Dec 11, 2024 |
| Dell          | 09KPNV A01                  | Desktop     | [157ad19f93](https://linux-hardware.org/?probe=157ad19f93) | Dec 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9105942b15](https://linux-hardware.org/?probe=9105942b15) | Dec 10, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [d595bcedb4](https://linux-hardware.org/?probe=d595bcedb4) | Dec 10, 2024 |
| Lenovo        | B5400 20278                 | Notebook    | [e1b20f6c0b](https://linux-hardware.org/?probe=e1b20f6c0b) | Dec 10, 2024 |
| Lenovo        | ThinkPad X270 20HN001HUS    | Notebook    | [ef25178fec](https://linux-hardware.org/?probe=ef25178fec) | Dec 10, 2024 |
| Lenovo        | ThinkPad X270 20HN001HUS    | Notebook    | [954578185e](https://linux-hardware.org/?probe=954578185e) | Dec 10, 2024 |
| MSI           | Z270 SLI PLUS               | Desktop     | [4bd957e3ec](https://linux-hardware.org/?probe=4bd957e3ec) | Dec 10, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [861b5550d3](https://linux-hardware.org/?probe=861b5550d3) | Dec 10, 2024 |
| Dell          | Latitude E6330              | Notebook    | [dfc2aca866](https://linux-hardware.org/?probe=dfc2aca866) | Dec 09, 2024 |
| Dell          | 0478VN A00                  | Desktop     | [86908e3156](https://linux-hardware.org/?probe=86908e3156) | Dec 09, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7305cf039c](https://linux-hardware.org/?probe=7305cf039c) | Dec 09, 2024 |
| ASRock        | H610M-ITX/eDP               | Desktop     | [75e26c7c07](https://linux-hardware.org/?probe=75e26c7c07) | Dec 09, 2024 |
| HP            | ZBook 17 G5                 | Notebook    | [0f14052159](https://linux-hardware.org/?probe=0f14052159) | Dec 09, 2024 |
| Apple         | MacBookPro5,4               | Notebook    | [751741e751](https://linux-hardware.org/?probe=751741e751) | Dec 09, 2024 |
| Apple         | MacBookPro5,4               | Notebook    | [fd85f5ad8f](https://linux-hardware.org/?probe=fd85f5ad8f) | Dec 09, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [d873aaad11](https://linux-hardware.org/?probe=d873aaad11) | Dec 09, 2024 |
| AZW           | MINI S                      | Desktop     | [a82e287e6c](https://linux-hardware.org/?probe=a82e287e6c) | Dec 09, 2024 |
| ASRock        | H610M-ITX/eDP               | Desktop     | [e9eed28958](https://linux-hardware.org/?probe=e9eed28958) | Dec 09, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [58a0bf4e65](https://linux-hardware.org/?probe=58a0bf4e65) | Dec 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | Notebook    | [e8f69e44e3](https://linux-hardware.org/?probe=e8f69e44e3) | Dec 09, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4fef924a63](https://linux-hardware.org/?probe=4fef924a63) | Dec 09, 2024 |
| Eluktronic... | RP-15                       | Notebook    | [bc1a09c984](https://linux-hardware.org/?probe=bc1a09c984) | Dec 08, 2024 |
| Supermicro    | X9DRD-iF                    | Desktop     | [f90d8dfc09](https://linux-hardware.org/?probe=f90d8dfc09) | Dec 08, 2024 |
| Google        | Samus                       | Notebook    | [362b80bc7d](https://linux-hardware.org/?probe=362b80bc7d) | Dec 08, 2024 |
| Unknown       | Unknown                     | Notebook    | [954625623a](https://linux-hardware.org/?probe=954625623a) | Dec 08, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [4c1f450872](https://linux-hardware.org/?probe=4c1f450872) | Dec 08, 2024 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [79abd0b864](https://linux-hardware.org/?probe=79abd0b864) | Dec 08, 2024 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [28d11d7453](https://linux-hardware.org/?probe=28d11d7453) | Dec 08, 2024 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [13abb368c7](https://linux-hardware.org/?probe=13abb368c7) | Dec 08, 2024 |
| Dell          | Inspiron N4050              | Notebook    | [7194f36c08](https://linux-hardware.org/?probe=7194f36c08) | Dec 08, 2024 |
| ASUSTek       | B150M-C                     | Desktop     | [0e25bdfd87](https://linux-hardware.org/?probe=0e25bdfd87) | Dec 07, 2024 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [15ceab731a](https://linux-hardware.org/?probe=15ceab731a) | Dec 07, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [62f3ba4cc6](https://linux-hardware.org/?probe=62f3ba4cc6) | Dec 07, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [88d9510fcb](https://linux-hardware.org/?probe=88d9510fcb) | Dec 07, 2024 |
| Dell          | Inspiron 15 5510            | Notebook    | [bd969c198e](https://linux-hardware.org/?probe=bd969c198e) | Dec 07, 2024 |
| Supermicro    | X9DRD-iF                    | Desktop     | [24c2ea7bbd](https://linux-hardware.org/?probe=24c2ea7bbd) | Dec 07, 2024 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [89c4ef1413](https://linux-hardware.org/?probe=89c4ef1413) | Dec 07, 2024 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [40751025a5](https://linux-hardware.org/?probe=40751025a5) | Dec 07, 2024 |
| Lenovo        | ThinkPad P52 20MAS1WD0S     | Notebook    | [49359bfaf2](https://linux-hardware.org/?probe=49359bfaf2) | Dec 07, 2024 |
| Lenovo        | ThinkPad T420s 417032U      | Notebook    | [4ac33e7516](https://linux-hardware.org/?probe=4ac33e7516) | Dec 07, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [741eb16cb4](https://linux-hardware.org/?probe=741eb16cb4) | Dec 07, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [780d8477b4](https://linux-hardware.org/?probe=780d8477b4) | Dec 07, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4b14a65ae5](https://linux-hardware.org/?probe=4b14a65ae5) | Dec 07, 2024 |
| Dell          | 0CW954 A00                  | Server      | [e65588c0e0](https://linux-hardware.org/?probe=e65588c0e0) | Dec 07, 2024 |
| Lenovo        | Yoga Pro 7 14AHP9 83E3      | Notebook    | [8ff09eea32](https://linux-hardware.org/?probe=8ff09eea32) | Dec 06, 2024 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [2616e6e6d0](https://linux-hardware.org/?probe=2616e6e6d0) | Dec 06, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [a324fb8617](https://linux-hardware.org/?probe=a324fb8617) | Dec 06, 2024 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [e25da0298a](https://linux-hardware.org/?probe=e25da0298a) | Dec 06, 2024 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [386b5bb2fa](https://linux-hardware.org/?probe=386b5bb2fa) | Dec 06, 2024 |
| HP            | Dragonfly Pro ONE           | Notebook    | [6db18a33b7](https://linux-hardware.org/?probe=6db18a33b7) | Dec 06, 2024 |
| Dell          | Latitude 5490               | Notebook    | [04d3dd2626](https://linux-hardware.org/?probe=04d3dd2626) | Dec 05, 2024 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [c28dd5c7ab](https://linux-hardware.org/?probe=c28dd5c7ab) | Dec 05, 2024 |
| Dell          | Inspiron 16 7640 2-in-1     | Notebook    | [3af8e24702](https://linux-hardware.org/?probe=3af8e24702) | Dec 05, 2024 |
| Intel         | B75                         | Desktop     | [69a652cb51](https://linux-hardware.org/?probe=69a652cb51) | Dec 05, 2024 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [eb3f1d8587](https://linux-hardware.org/?probe=eb3f1d8587) | Dec 05, 2024 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [315414ee85](https://linux-hardware.org/?probe=315414ee85) | Dec 05, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [90ba8c71bd](https://linux-hardware.org/?probe=90ba8c71bd) | Dec 05, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [c294b554ab](https://linux-hardware.org/?probe=c294b554ab) | Dec 05, 2024 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [91d86a1a29](https://linux-hardware.org/?probe=91d86a1a29) | Dec 05, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [38917bc287](https://linux-hardware.org/?probe=38917bc287) | Dec 04, 2024 |
| Dell          | 09KPNV A00                  | Desktop     | [954003dcdc](https://linux-hardware.org/?probe=954003dcdc) | Dec 04, 2024 |
| ASRock        | X570 Taichi                 | Desktop     | [095dc95b9d](https://linux-hardware.org/?probe=095dc95b9d) | Dec 04, 2024 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [b1cf6cfea9](https://linux-hardware.org/?probe=b1cf6cfea9) | Dec 04, 2024 |
| ASUSTek       | N550JV                      | Notebook    | [e0700722fa](https://linux-hardware.org/?probe=e0700722fa) | Dec 04, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [67fde295de](https://linux-hardware.org/?probe=67fde295de) | Dec 04, 2024 |
| Gigabyte      | X870 EAGLE WIFI7            | Desktop     | [4178f34632](https://linux-hardware.org/?probe=4178f34632) | Dec 04, 2024 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [eea3d584af](https://linux-hardware.org/?probe=eea3d584af) | Dec 04, 2024 |
| Positivo      | POS-EIH61CQ                 | Desktop     | [d4fad86c11](https://linux-hardware.org/?probe=d4fad86c11) | Dec 04, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [23325c9670](https://linux-hardware.org/?probe=23325c9670) | Dec 03, 2024 |
| Dell          | Latitude 7214               | Notebook    | [e84846c90c](https://linux-hardware.org/?probe=e84846c90c) | Dec 03, 2024 |
| Fujitsu       | CELSIUS H920                | Notebook    | [8b524abe47](https://linux-hardware.org/?probe=8b524abe47) | Dec 03, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [2749a746c7](https://linux-hardware.org/?probe=2749a746c7) | Dec 03, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [e36eea22b1](https://linux-hardware.org/?probe=e36eea22b1) | Dec 03, 2024 |
| ASUSTek       | PRIME B350M-K               | Desktop     | [8e7c6af74e](https://linux-hardware.org/?probe=8e7c6af74e) | Dec 03, 2024 |
| HP            | 1905                        | Desktop     | [925e9c6a14](https://linux-hardware.org/?probe=925e9c6a14) | Dec 03, 2024 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3b2b2cdb80](https://linux-hardware.org/?probe=3b2b2cdb80) | Dec 03, 2024 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [898f745e60](https://linux-hardware.org/?probe=898f745e60) | Dec 03, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [b4a0a64ac0](https://linux-hardware.org/?probe=b4a0a64ac0) | Dec 03, 2024 |
| Acer          | Aspire A315-41              | Notebook    | [629a42a94d](https://linux-hardware.org/?probe=629a42a94d) | Dec 03, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [303b3a510d](https://linux-hardware.org/?probe=303b3a510d) | Dec 02, 2024 |
| Acer          | Aspire A315-41              | Notebook    | [dff6e368e4](https://linux-hardware.org/?probe=dff6e368e4) | Dec 02, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [98f50b0d90](https://linux-hardware.org/?probe=98f50b0d90) | Dec 02, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ad5a11492c](https://linux-hardware.org/?probe=ad5a11492c) | Dec 02, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [8240d92fbc](https://linux-hardware.org/?probe=8240d92fbc) | Dec 02, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e702910c8e](https://linux-hardware.org/?probe=e702910c8e) | Dec 02, 2024 |
| ASUSTek       | PRIME B760M-A AX6 II        | Desktop     | [66cdfbda88](https://linux-hardware.org/?probe=66cdfbda88) | Dec 02, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d71db12c0a](https://linux-hardware.org/?probe=d71db12c0a) | Dec 02, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e754157d76](https://linux-hardware.org/?probe=e754157d76) | Dec 02, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [265dad936c](https://linux-hardware.org/?probe=265dad936c) | Dec 01, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [6c84ee4665](https://linux-hardware.org/?probe=6c84ee4665) | Dec 01, 2024 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [fa59a3d752](https://linux-hardware.org/?probe=fa59a3d752) | Dec 01, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [6ba50b8196](https://linux-hardware.org/?probe=6ba50b8196) | Dec 01, 2024 |
| Framework     | Laptop                      | Notebook    | [dd1492ec61](https://linux-hardware.org/?probe=dd1492ec61) | Dec 01, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [882e0e49e0](https://linux-hardware.org/?probe=882e0e49e0) | Dec 01, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS       | Desktop     | [b2a46b17d9](https://linux-hardware.org/?probe=b2a46b17d9) | Dec 01, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [cfe2d2980e](https://linux-hardware.org/?probe=cfe2d2980e) | Dec 01, 2024 |
| HP            | 1905                        | Desktop     | [a3ed3e5797](https://linux-hardware.org/?probe=a3ed3e5797) | Dec 01, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [e75002ef8d](https://linux-hardware.org/?probe=e75002ef8d) | Dec 01, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [7f2c1251c1](https://linux-hardware.org/?probe=7f2c1251c1) | Dec 01, 2024 |
| Shenzhen M... | RPBNB                       | Desktop     | [471e0eae44](https://linux-hardware.org/?probe=471e0eae44) | Nov 30, 2024 |
| Dell          | 0VHWTR A02                  | Desktop     | [0295b5d88e](https://linux-hardware.org/?probe=0295b5d88e) | Nov 30, 2024 |
| Fujitsu       | CELSIUS H920                | Notebook    | [bae9e145b7](https://linux-hardware.org/?probe=bae9e145b7) | Nov 30, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | Notebook    | [296918a3b8](https://linux-hardware.org/?probe=296918a3b8) | Nov 30, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [be0716093f](https://linux-hardware.org/?probe=be0716093f) | Nov 30, 2024 |
| AZW           | MINI S                      | Desktop     | [b21eaf0955](https://linux-hardware.org/?probe=b21eaf0955) | Nov 29, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [a87d08ca42](https://linux-hardware.org/?probe=a87d08ca42) | Nov 28, 2024 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [8351202a05](https://linux-hardware.org/?probe=8351202a05) | Nov 28, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f8c81ccbdb](https://linux-hardware.org/?probe=f8c81ccbdb) | Nov 28, 2024 |
| HP            | 18E6                        | Desktop     | [8ff866b586](https://linux-hardware.org/?probe=8ff866b586) | Nov 28, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [0cfba5ec43](https://linux-hardware.org/?probe=0cfba5ec43) | Nov 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [90cef362ad](https://linux-hardware.org/?probe=90cef362ad) | Nov 27, 2024 |
| ASUSTek       | P5Q-WS                      | Desktop     | [9c1be46138](https://linux-hardware.org/?probe=9c1be46138) | Nov 27, 2024 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [66ed7c3731](https://linux-hardware.org/?probe=66ed7c3731) | Nov 26, 2024 |
| ASUSTek       | PRIME Z790-V AX             | Desktop     | [e3dda3c505](https://linux-hardware.org/?probe=e3dda3c505) | Nov 26, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b04303ec82](https://linux-hardware.org/?probe=b04303ec82) | Nov 26, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [bcc801145a](https://linux-hardware.org/?probe=bcc801145a) | Nov 25, 2024 |
| MSI           | H270-A PRO                  | Desktop     | [e2974172be](https://linux-hardware.org/?probe=e2974172be) | Nov 25, 2024 |
| Notebook      | NLxxPUx                     | Notebook    | [1f935fe7fc](https://linux-hardware.org/?probe=1f935fe7fc) | Nov 25, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [4f62376d84](https://linux-hardware.org/?probe=4f62376d84) | Nov 25, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | Notebook    | [ce9660e165](https://linux-hardware.org/?probe=ce9660e165) | Nov 25, 2024 |
| Lenovo        | 31900058 STD                | All in one  | [bebe350b46](https://linux-hardware.org/?probe=bebe350b46) | Nov 25, 2024 |
| Dell          | Inspiron 5480               | Notebook    | [ce8745ed99](https://linux-hardware.org/?probe=ce8745ed99) | Nov 24, 2024 |
| Lenovo        | ThinkPad T480s 20L8S27M0... | Notebook    | [8cf2b4511a](https://linux-hardware.org/?probe=8cf2b4511a) | Nov 24, 2024 |
| ASUSTek       | GL503VMF                    | Notebook    | [cb79d7ac34](https://linux-hardware.org/?probe=cb79d7ac34) | Nov 24, 2024 |
| Dell          | 0VHWTR A02                  | Desktop     | [c23095586a](https://linux-hardware.org/?probe=c23095586a) | Nov 24, 2024 |
| MSI           | GF63 8RC                    | Notebook    | [86cd8d621b](https://linux-hardware.org/?probe=86cd8d621b) | Nov 23, 2024 |
| Acer          | Aspire E1-731               | Notebook    | [f8b734fdc4](https://linux-hardware.org/?probe=f8b734fdc4) | Nov 23, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [5730687f62](https://linux-hardware.org/?probe=5730687f62) | Nov 23, 2024 |
| MSI           | H270-A PRO                  | Desktop     | [554c3ad6a6](https://linux-hardware.org/?probe=554c3ad6a6) | Nov 23, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [603ece14b5](https://linux-hardware.org/?probe=603ece14b5) | Nov 23, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2c25bb8e66](https://linux-hardware.org/?probe=2c25bb8e66) | Nov 23, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ffd1398e1b](https://linux-hardware.org/?probe=ffd1398e1b) | Nov 23, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [3da1cde3bf](https://linux-hardware.org/?probe=3da1cde3bf) | Nov 23, 2024 |
| HP            | Dragonfly Pro Laptop PC     | Notebook    | [4512acb105](https://linux-hardware.org/?probe=4512acb105) | Nov 23, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [9ad6cf1e22](https://linux-hardware.org/?probe=9ad6cf1e22) | Nov 22, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5233943083](https://linux-hardware.org/?probe=5233943083) | Nov 22, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [79597758d9](https://linux-hardware.org/?probe=79597758d9) | Nov 22, 2024 |
| Lenovo        | ThinkPad T490s 20NYS3NT0... | Notebook    | [89cbb90e46](https://linux-hardware.org/?probe=89cbb90e46) | Nov 21, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB0A... | Mini pc     | [a6240ab56c](https://linux-hardware.org/?probe=a6240ab56c) | Nov 21, 2024 |
| System76      | Gazelle                     | Notebook    | [b3ba386916](https://linux-hardware.org/?probe=b3ba386916) | Nov 21, 2024 |
| Dell          | Precision 5490              | Notebook    | [32bacf2696](https://linux-hardware.org/?probe=32bacf2696) | Nov 21, 2024 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [3c75cf4004](https://linux-hardware.org/?probe=3c75cf4004) | Nov 21, 2024 |
| Alienware     | 15 R2                       | Notebook    | [e19cff46a5](https://linux-hardware.org/?probe=e19cff46a5) | Nov 21, 2024 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [13b235f8ac](https://linux-hardware.org/?probe=13b235f8ac) | Nov 21, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [0b7cd81ab1](https://linux-hardware.org/?probe=0b7cd81ab1) | Nov 21, 2024 |
| Gigabyte      | B75M-D3H                    | Desktop     | [f4e6dc4230](https://linux-hardware.org/?probe=f4e6dc4230) | Nov 21, 2024 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [51cbd9f492](https://linux-hardware.org/?probe=51cbd9f492) | Nov 20, 2024 |
| Acer          | Aspire A315-51              | Notebook    | [291ffae1d7](https://linux-hardware.org/?probe=291ffae1d7) | Nov 20, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [96e3d3f74c](https://linux-hardware.org/?probe=96e3d3f74c) | Nov 20, 2024 |
| Lenovo        | ThinkPad T430s 2356CU8      | Notebook    | [88c764ac54](https://linux-hardware.org/?probe=88c764ac54) | Nov 20, 2024 |
| ASUSTek       | ROG Strix G18 G834JZR_G8... | Notebook    | [fbfffc7976](https://linux-hardware.org/?probe=fbfffc7976) | Nov 19, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [d9fa077e13](https://linux-hardware.org/?probe=d9fa077e13) | Nov 19, 2024 |
| ASRock        | X670E PG Lightning          | Desktop     | [07a38ec669](https://linux-hardware.org/?probe=07a38ec669) | Nov 19, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e208cd8e71](https://linux-hardware.org/?probe=e208cd8e71) | Nov 19, 2024 |
| MSI           | H61M-P31                    | Desktop     | [0209ef23d5](https://linux-hardware.org/?probe=0209ef23d5) | Nov 19, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [8801ad76a4](https://linux-hardware.org/?probe=8801ad76a4) | Nov 19, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [63467331fb](https://linux-hardware.org/?probe=63467331fb) | Nov 19, 2024 |
| MSI           | H61M-P31                    | Desktop     | [6ff594d173](https://linux-hardware.org/?probe=6ff594d173) | Nov 18, 2024 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [896963442d](https://linux-hardware.org/?probe=896963442d) | Nov 18, 2024 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [5590d9581e](https://linux-hardware.org/?probe=5590d9581e) | Nov 18, 2024 |
| PC Special... | NH5xAx                      | Notebook    | [61b94b9412](https://linux-hardware.org/?probe=61b94b9412) | Nov 18, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [56a3f6ca37](https://linux-hardware.org/?probe=56a3f6ca37) | Nov 18, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [024e56ebca](https://linux-hardware.org/?probe=024e56ebca) | Nov 17, 2024 |
| Matsushita... | CF-19FDGADCM                | Notebook    | [9fadfe6a9b](https://linux-hardware.org/?probe=9fadfe6a9b) | Nov 17, 2024 |
| Dell          | 0VHWTR A02                  | Desktop     | [c4fd80459e](https://linux-hardware.org/?probe=c4fd80459e) | Nov 17, 2024 |
| ASRock        | X670E PG Lightning          | Desktop     | [0db2e7e64c](https://linux-hardware.org/?probe=0db2e7e64c) | Nov 17, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [2c5311e308](https://linux-hardware.org/?probe=2c5311e308) | Nov 17, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [6ec5e5144f](https://linux-hardware.org/?probe=6ec5e5144f) | Nov 17, 2024 |
| Dell          | Inspiron 3558               | Notebook    | [f1630ad0da](https://linux-hardware.org/?probe=f1630ad0da) | Nov 17, 2024 |
| MSI           | GP60 2PE                    | Notebook    | [3d4814126b](https://linux-hardware.org/?probe=3d4814126b) | Nov 16, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [ff04745822](https://linux-hardware.org/?probe=ff04745822) | Nov 16, 2024 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [0c8044a2d4](https://linux-hardware.org/?probe=0c8044a2d4) | Nov 16, 2024 |
| ASUSTek       | Strix GL703GS_GL703GS       | Notebook    | [6ea29cc14a](https://linux-hardware.org/?probe=6ea29cc14a) | Nov 16, 2024 |
| Apple         | MacBookPro11,5              | Notebook    | [c2a112f067](https://linux-hardware.org/?probe=c2a112f067) | Nov 16, 2024 |
| Lenovo        | ThinkPad T460 20FN003LGE    | Notebook    | [06d3c3c63f](https://linux-hardware.org/?probe=06d3c3c63f) | Nov 16, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [5f6a56e720](https://linux-hardware.org/?probe=5f6a56e720) | Nov 16, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | Notebook    | [a14710d282](https://linux-hardware.org/?probe=a14710d282) | Nov 16, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b7df8d7127](https://linux-hardware.org/?probe=b7df8d7127) | Nov 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [48b24cce4c](https://linux-hardware.org/?probe=48b24cce4c) | Nov 16, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bd07d42d7c](https://linux-hardware.org/?probe=bd07d42d7c) | Nov 16, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [e839fa544a](https://linux-hardware.org/?probe=e839fa544a) | Nov 15, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [ff147ff990](https://linux-hardware.org/?probe=ff147ff990) | Nov 15, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [d13f4015bb](https://linux-hardware.org/?probe=d13f4015bb) | Nov 15, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [fc1124cd18](https://linux-hardware.org/?probe=fc1124cd18) | Nov 15, 2024 |
| Razer         | Blade                       | Notebook    | [0d6640fb39](https://linux-hardware.org/?probe=0d6640fb39) | Nov 15, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [054b123f91](https://linux-hardware.org/?probe=054b123f91) | Nov 15, 2024 |
| ASUSTek       | M3A                         | Desktop     | [d3f42b3ab8](https://linux-hardware.org/?probe=d3f42b3ab8) | Nov 15, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [e42cce2813](https://linux-hardware.org/?probe=e42cce2813) | Nov 15, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [1ff2d7429c](https://linux-hardware.org/?probe=1ff2d7429c) | Nov 15, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [792208442b](https://linux-hardware.org/?probe=792208442b) | Nov 14, 2024 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | Notebook    | [ec728fd727](https://linux-hardware.org/?probe=ec728fd727) | Nov 14, 2024 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [7c566f5d03](https://linux-hardware.org/?probe=7c566f5d03) | Nov 14, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [e872037135](https://linux-hardware.org/?probe=e872037135) | Nov 14, 2024 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [482dd6b939](https://linux-hardware.org/?probe=482dd6b939) | Nov 14, 2024 |
| AZW           | MINI S                      | Desktop     | [16e41e32ed](https://linux-hardware.org/?probe=16e41e32ed) | Nov 14, 2024 |
| AZW           | MINI S                      | Desktop     | [b766d78b0f](https://linux-hardware.org/?probe=b766d78b0f) | Nov 14, 2024 |
| Acer          | Nitro AN515-51              | Notebook    | [b4bf8cdee4](https://linux-hardware.org/?probe=b4bf8cdee4) | Nov 13, 2024 |
| MSI           | Vector 16 HX A13VHG         | Notebook    | [afef5ca6c4](https://linux-hardware.org/?probe=afef5ca6c4) | Nov 13, 2024 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [b27354f1ee](https://linux-hardware.org/?probe=b27354f1ee) | Nov 13, 2024 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | Notebook    | [14d794125a](https://linux-hardware.org/?probe=14d794125a) | Nov 12, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [5ddb463c28](https://linux-hardware.org/?probe=5ddb463c28) | Nov 12, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [b50cd6c13b](https://linux-hardware.org/?probe=b50cd6c13b) | Nov 12, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [feb8fd8dbc](https://linux-hardware.org/?probe=feb8fd8dbc) | Nov 12, 2024 |
| Dell          | 0D4MD1 A00                  | Desktop     | [8a55c02e08](https://linux-hardware.org/?probe=8a55c02e08) | Nov 12, 2024 |
| MSI           | Modern 14 A10RB             | Notebook    | [e0bf66102b](https://linux-hardware.org/?probe=e0bf66102b) | Nov 12, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [7965f306a8](https://linux-hardware.org/?probe=7965f306a8) | Nov 11, 2024 |
| Dell          | Precision 3561              | Notebook    | [43f06770e1](https://linux-hardware.org/?probe=43f06770e1) | Nov 11, 2024 |
| Acer          | Aspire 4752                 | Notebook    | [2f02f5ff8b](https://linux-hardware.org/?probe=2f02f5ff8b) | Nov 11, 2024 |
| Infinix       | INBOOK Y1 PLUS              | Notebook    | [53ea4dc826](https://linux-hardware.org/?probe=53ea4dc826) | Nov 11, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [d39f3e11a8](https://linux-hardware.org/?probe=d39f3e11a8) | Nov 11, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [3d0f0dc3a3](https://linux-hardware.org/?probe=3d0f0dc3a3) | Nov 11, 2024 |
| MSI           | Z270 SLI PLUS               | Desktop     | [ed80f0f9d6](https://linux-hardware.org/?probe=ed80f0f9d6) | Nov 11, 2024 |
| Toshiba       | Satellite L655D             | Notebook    | [9a6af30aa7](https://linux-hardware.org/?probe=9a6af30aa7) | Nov 10, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [83854ceaa7](https://linux-hardware.org/?probe=83854ceaa7) | Nov 10, 2024 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [d244f80fd9](https://linux-hardware.org/?probe=d244f80fd9) | Nov 10, 2024 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [ee28dd46d5](https://linux-hardware.org/?probe=ee28dd46d5) | Nov 10, 2024 |
| Gigabyte      | B650 GAMING X AX V2         | Desktop     | [06e904448b](https://linux-hardware.org/?probe=06e904448b) | Nov 09, 2024 |
| Acer          | Aspire E1-571G              | Notebook    | [b2eba6e770](https://linux-hardware.org/?probe=b2eba6e770) | Nov 09, 2024 |
| Intel         | X99H                        | Desktop     | [5e31d210ca](https://linux-hardware.org/?probe=5e31d210ca) | Nov 09, 2024 |
| Lenovo        | ThinkPad T490 20N3000KGE    | Notebook    | [8f487ff101](https://linux-hardware.org/?probe=8f487ff101) | Nov 09, 2024 |
| Acer          | Aspire A315-24PT            | Notebook    | [a780b016b5](https://linux-hardware.org/?probe=a780b016b5) | Nov 09, 2024 |
| Gigabyte      | B550 UD AC                  | Desktop     | [844ce5e614](https://linux-hardware.org/?probe=844ce5e614) | Nov 09, 2024 |
| Gigabyte      | B650 GAMING X AX V2         | Desktop     | [747035fcc0](https://linux-hardware.org/?probe=747035fcc0) | Nov 09, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [3c0fea8e9f](https://linux-hardware.org/?probe=3c0fea8e9f) | Nov 09, 2024 |
| Toshiba       | Satellite S40Dt-A           | Notebook    | [9df604ab8c](https://linux-hardware.org/?probe=9df604ab8c) | Nov 08, 2024 |
| Lenovo        | ThinkPad T490 20N3000KGE    | Notebook    | [97d3495f24](https://linux-hardware.org/?probe=97d3495f24) | Nov 08, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [cffb50d3fa](https://linux-hardware.org/?probe=cffb50d3fa) | Nov 08, 2024 |
| Intel         | DH61BF AAG81311-102         | Desktop     | [fa09fae0e6](https://linux-hardware.org/?probe=fa09fae0e6) | Nov 08, 2024 |
| MSI           | PRO B660-A DDR4             | Desktop     | [723518a192](https://linux-hardware.org/?probe=723518a192) | Nov 08, 2024 |
| Gigabyte      | AERO 15XV8                  | Notebook    | [ad28b2f598](https://linux-hardware.org/?probe=ad28b2f598) | Nov 07, 2024 |
| Acer          | Predator PT14-51            | Notebook    | [89ab08c4d5](https://linux-hardware.org/?probe=89ab08c4d5) | Nov 07, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [026f2ca004](https://linux-hardware.org/?probe=026f2ca004) | Nov 07, 2024 |
| Dell          | 0HY9JP A00                  | Desktop     | [ba793c9a96](https://linux-hardware.org/?probe=ba793c9a96) | Nov 07, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [de1c2a77a8](https://linux-hardware.org/?probe=de1c2a77a8) | Nov 07, 2024 |
| Gigabyte      | X870 GAMING WIFI6           | Desktop     | [92957f360a](https://linux-hardware.org/?probe=92957f360a) | Nov 06, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [86b3f8139b](https://linux-hardware.org/?probe=86b3f8139b) | Nov 06, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c53cffc662](https://linux-hardware.org/?probe=c53cffc662) | Nov 06, 2024 |
| ASRock        | B650 LiveMixer              | Desktop     | [312b0972f7](https://linux-hardware.org/?probe=312b0972f7) | Nov 06, 2024 |
| ASUSTek       | PRIME Z790-V AX             | Desktop     | [24710cb98a](https://linux-hardware.org/?probe=24710cb98a) | Nov 06, 2024 |
| ASUSTek       | PRIME Z790-V AX             | Desktop     | [3d09c0f78f](https://linux-hardware.org/?probe=3d09c0f78f) | Nov 06, 2024 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [45d0b46228](https://linux-hardware.org/?probe=45d0b46228) | Nov 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [92d4a2f482](https://linux-hardware.org/?probe=92d4a2f482) | Nov 05, 2024 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [7f51e7a50a](https://linux-hardware.org/?probe=7f51e7a50a) | Nov 05, 2024 |
| ASUSTek       | P7P55D-E                    | Desktop     | [e6cddc3d72](https://linux-hardware.org/?probe=e6cddc3d72) | Nov 05, 2024 |
| Dell          | 0RCPW3 A03                  | Desktop     | [dff53af38f](https://linux-hardware.org/?probe=dff53af38f) | Nov 05, 2024 |
| ASRock        | H87 Performance             | Desktop     | [5680ba8d20](https://linux-hardware.org/?probe=5680ba8d20) | Nov 04, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [49b45e8170](https://linux-hardware.org/?probe=49b45e8170) | Nov 04, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [488431591c](https://linux-hardware.org/?probe=488431591c) | Nov 04, 2024 |
| MSI           | Summit E16FlipEvo A11MT     | Notebook    | [70c39b3a00](https://linux-hardware.org/?probe=70c39b3a00) | Nov 04, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [9f80547082](https://linux-hardware.org/?probe=9f80547082) | Nov 04, 2024 |
| HP            | 2129                        | Desktop     | [0a6a53a99f](https://linux-hardware.org/?probe=0a6a53a99f) | Nov 04, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [bb5ceef12d](https://linux-hardware.org/?probe=bb5ceef12d) | Nov 04, 2024 |
| Dell          | 0VHWTR A02                  | Desktop     | [0510510273](https://linux-hardware.org/?probe=0510510273) | Nov 03, 2024 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | Notebook    | [2dd904a978](https://linux-hardware.org/?probe=2dd904a978) | Nov 03, 2024 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [bb50b544e2](https://linux-hardware.org/?probe=bb50b544e2) | Nov 03, 2024 |
| System76      | Serval WS                   | Notebook    | [3325ac75c2](https://linux-hardware.org/?probe=3325ac75c2) | Nov 03, 2024 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [a073c7cb1e](https://linux-hardware.org/?probe=a073c7cb1e) | Nov 03, 2024 |
| System76      | Pangolin                    | Notebook    | [d1958d8e54](https://linux-hardware.org/?probe=d1958d8e54) | Nov 02, 2024 |
| Dell          | 0JP3NX A01                  | Desktop     | [44c5885090](https://linux-hardware.org/?probe=44c5885090) | Nov 02, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [0f0375d12d](https://linux-hardware.org/?probe=0f0375d12d) | Nov 02, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [1c42e6c25f](https://linux-hardware.org/?probe=1c42e6c25f) | Nov 02, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [5370c39b49](https://linux-hardware.org/?probe=5370c39b49) | Nov 02, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1502CBA... | Notebook    | [2831ff1766](https://linux-hardware.org/?probe=2831ff1766) | Nov 02, 2024 |
| Dell          | Precision 3590              | Notebook    | [bc82f6333a](https://linux-hardware.org/?probe=bc82f6333a) | Nov 02, 2024 |
| Dell          | Latitude E4300              | Notebook    | [90b6823b82](https://linux-hardware.org/?probe=90b6823b82) | Nov 02, 2024 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [d6283216f3](https://linux-hardware.org/?probe=d6283216f3) | Nov 02, 2024 |
| Biostar       | A780L                       | Desktop     | [9fbbe8bb22](https://linux-hardware.org/?probe=9fbbe8bb22) | Nov 02, 2024 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [67f2f24139](https://linux-hardware.org/?probe=67f2f24139) | Nov 02, 2024 |
| Intel         | X99 V1.0                    | Desktop     | [41c10ad1c4](https://linux-hardware.org/?probe=41c10ad1c4) | Nov 01, 2024 |
| Google        | Samus                       | Notebook    | [6c26c1cab1](https://linux-hardware.org/?probe=6c26c1cab1) | Nov 01, 2024 |
| Google        | Samus                       | Notebook    | [190f904324](https://linux-hardware.org/?probe=190f904324) | Nov 01, 2024 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [f5901143d7](https://linux-hardware.org/?probe=f5901143d7) | Nov 01, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [06801a2213](https://linux-hardware.org/?probe=06801a2213) | Nov 01, 2024 |
| HP            | Pavilion dv9700             | Notebook    | [e649cb0d93](https://linux-hardware.org/?probe=e649cb0d93) | Nov 01, 2024 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [90ba5e792f](https://linux-hardware.org/?probe=90ba5e792f) | Nov 01, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [07c831fabd](https://linux-hardware.org/?probe=07c831fabd) | Nov 01, 2024 |
| Dell          | Latitude E4300              | Notebook    | [2c7555b016](https://linux-hardware.org/?probe=2c7555b016) | Oct 31, 2024 |
| Gigabyte      | AERO 15XV8                  | Notebook    | [10526455a3](https://linux-hardware.org/?probe=10526455a3) | Oct 31, 2024 |
| Intel         | X99                         | Desktop     | [1090396c96](https://linux-hardware.org/?probe=1090396c96) | Oct 31, 2024 |
| System76      | Darter Pro                  | Notebook    | [47e11617c9](https://linux-hardware.org/?probe=47e11617c9) | Oct 31, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [fe5d53b473](https://linux-hardware.org/?probe=fe5d53b473) | Oct 31, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [8a23e0e1bf](https://linux-hardware.org/?probe=8a23e0e1bf) | Oct 31, 2024 |
| Dell          | Inspiron 16 7640 2-in-1     | Notebook    | [f0a61a6b62](https://linux-hardware.org/?probe=f0a61a6b62) | Oct 31, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [99224e2693](https://linux-hardware.org/?probe=99224e2693) | Oct 31, 2024 |
| Dell          | 0D4MD1 A00                  | Desktop     | [ba7413667b](https://linux-hardware.org/?probe=ba7413667b) | Oct 31, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [ca851926b9](https://linux-hardware.org/?probe=ca851926b9) | Oct 31, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [3872f48485](https://linux-hardware.org/?probe=3872f48485) | Oct 30, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [df33da1aff](https://linux-hardware.org/?probe=df33da1aff) | Oct 30, 2024 |
| Gigabyte      | Z590I AORUS ULTRA           | Notebook    | [816bafe83f](https://linux-hardware.org/?probe=816bafe83f) | Oct 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [9589e6f064](https://linux-hardware.org/?probe=9589e6f064) | Oct 30, 2024 |
| Acer          | Aspire A515-54G             | Notebook    | [8b1abbd55e](https://linux-hardware.org/?probe=8b1abbd55e) | Oct 30, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [3e6d95febe](https://linux-hardware.org/?probe=3e6d95febe) | Oct 29, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [fc46ea6344](https://linux-hardware.org/?probe=fc46ea6344) | Oct 29, 2024 |
| MSI           | Modern 14 B11MOU            | Notebook    | [1347b3862f](https://linux-hardware.org/?probe=1347b3862f) | Oct 29, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | Notebook    | [8c5b5946e9](https://linux-hardware.org/?probe=8c5b5946e9) | Oct 29, 2024 |
| Dell          | 07T4MC A09                  | Desktop     | [e6f3a1ec08](https://linux-hardware.org/?probe=e6f3a1ec08) | Oct 29, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1f16dfb5a7](https://linux-hardware.org/?probe=1f16dfb5a7) | Oct 29, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6ba1445c64](https://linux-hardware.org/?probe=6ba1445c64) | Oct 29, 2024 |
| Toshiba       | Satellite C850-B225         | Notebook    | [962858a9aa](https://linux-hardware.org/?probe=962858a9aa) | Oct 29, 2024 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [34c1bd3c07](https://linux-hardware.org/?probe=34c1bd3c07) | Oct 29, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [2e04817d43](https://linux-hardware.org/?probe=2e04817d43) | Oct 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [e71f961f6b](https://linux-hardware.org/?probe=e71f961f6b) | Oct 28, 2024 |
| Dell          | Latitude E6430              | Notebook    | [3a0bf739f0](https://linux-hardware.org/?probe=3a0bf739f0) | Oct 28, 2024 |
| Daten Tecn... | DH3UP DC                    | Mini pc     | [94bcd25b76](https://linux-hardware.org/?probe=94bcd25b76) | Oct 28, 2024 |
| Lenovo        | ThinkPad X390 20Q1S6W600    | Notebook    | [8e5f1a7f66](https://linux-hardware.org/?probe=8e5f1a7f66) | Oct 27, 2024 |
| MSI           | Bravo 17 C7VFK              | Notebook    | [a7adfb673d](https://linux-hardware.org/?probe=a7adfb673d) | Oct 27, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [e2335cbea6](https://linux-hardware.org/?probe=e2335cbea6) | Oct 27, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [6b3fb2ce2d](https://linux-hardware.org/?probe=6b3fb2ce2d) | Oct 26, 2024 |
| System76      | Pangolin                    | Notebook    | [fb57203d8e](https://linux-hardware.org/?probe=fb57203d8e) | Oct 26, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [028685c0a9](https://linux-hardware.org/?probe=028685c0a9) | Oct 26, 2024 |
| Gigabyte      | G41M-Combo                  | Desktop     | [4ddd0f69f1](https://linux-hardware.org/?probe=4ddd0f69f1) | Oct 26, 2024 |
| Gigabyte      | G41M-Combo                  | Desktop     | [0fb81a0008](https://linux-hardware.org/?probe=0fb81a0008) | Oct 26, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [bfa95cffa8](https://linux-hardware.org/?probe=bfa95cffa8) | Oct 26, 2024 |
| Lenovo        | 3 15ADA05 81W1              | Notebook    | [909b98bfa8](https://linux-hardware.org/?probe=909b98bfa8) | Oct 26, 2024 |
| System76      | Lemur Pro                   | Notebook    | [c9d662ba98](https://linux-hardware.org/?probe=c9d662ba98) | Oct 26, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [9be6f0ffd0](https://linux-hardware.org/?probe=9be6f0ffd0) | Oct 25, 2024 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [260a0dccc2](https://linux-hardware.org/?probe=260a0dccc2) | Oct 25, 2024 |
| MSI           | Modern 14 B11MOU            | Notebook    | [e854e6170d](https://linux-hardware.org/?probe=e854e6170d) | Oct 25, 2024 |
| Alienware     | m16 R1                      | Notebook    | [da15c91477](https://linux-hardware.org/?probe=da15c91477) | Oct 25, 2024 |
| Alienware     | m16 R1                      | Notebook    | [1e49172947](https://linux-hardware.org/?probe=1e49172947) | Oct 25, 2024 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [424bbe5529](https://linux-hardware.org/?probe=424bbe5529) | Oct 25, 2024 |
| TB            | WTR R1                      | Desktop     | [deb31354cb](https://linux-hardware.org/?probe=deb31354cb) | Oct 25, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | Notebook    | [085e6bccdb](https://linux-hardware.org/?probe=085e6bccdb) | Oct 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | Notebook    | [100c697e15](https://linux-hardware.org/?probe=100c697e15) | Oct 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | Notebook    | [e8bafa71e4](https://linux-hardware.org/?probe=e8bafa71e4) | Oct 25, 2024 |
| HP            | Pavilion dv6                | Notebook    | [e0742f5a71](https://linux-hardware.org/?probe=e0742f5a71) | Oct 25, 2024 |
| HP            | Pavilion dv6                | Notebook    | [6038c991fd](https://linux-hardware.org/?probe=6038c991fd) | Oct 25, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d013c75bc0](https://linux-hardware.org/?probe=d013c75bc0) | Oct 25, 2024 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [81b90346d4](https://linux-hardware.org/?probe=81b90346d4) | Oct 25, 2024 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [3f56d7a7f5](https://linux-hardware.org/?probe=3f56d7a7f5) | Oct 25, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [ec5c700007](https://linux-hardware.org/?probe=ec5c700007) | Oct 24, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [84f4f906f2](https://linux-hardware.org/?probe=84f4f906f2) | Oct 24, 2024 |
| Dell          | 0K240Y A01                  | Desktop     | [0c8041b514](https://linux-hardware.org/?probe=0c8041b514) | Oct 24, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [51e502d243](https://linux-hardware.org/?probe=51e502d243) | Oct 24, 2024 |
| ASUSTek       | GL553VE                     | Notebook    | [ac2e87e2ce](https://linux-hardware.org/?probe=ac2e87e2ce) | Oct 23, 2024 |
| Itautec       | Infoway w7730               | Notebook    | [031ee64761](https://linux-hardware.org/?probe=031ee64761) | Oct 23, 2024 |
| Gigabyte      | B75M-D3H                    | Desktop     | [833b93b860](https://linux-hardware.org/?probe=833b93b860) | Oct 23, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cb81bdd86a](https://linux-hardware.org/?probe=cb81bdd86a) | Oct 23, 2024 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [3c7f38442a](https://linux-hardware.org/?probe=3c7f38442a) | Oct 23, 2024 |
| System76      | Pangolin                    | Notebook    | [802316e70a](https://linux-hardware.org/?probe=802316e70a) | Oct 23, 2024 |
| Dell          | Inspiron 7405 2n1           | Convertible | [99b535f927](https://linux-hardware.org/?probe=99b535f927) | Oct 23, 2024 |
| Gigabyte      | H370M D3H GSM-CF            | Desktop     | [069580c3b2](https://linux-hardware.org/?probe=069580c3b2) | Oct 22, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [4710ecffdc](https://linux-hardware.org/?probe=4710ecffdc) | Oct 22, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [841c88c37f](https://linux-hardware.org/?probe=841c88c37f) | Oct 22, 2024 |
| MSI           | GS60 6QE                    | Notebook    | [7e1d315d47](https://linux-hardware.org/?probe=7e1d315d47) | Oct 22, 2024 |
| IT Channel... | NP5x_6x_7x_SNx              | Notebook    | [f92a3a6051](https://linux-hardware.org/?probe=f92a3a6051) | Oct 21, 2024 |
| TB            | WTR R1                      | Desktop     | [77199b6dc7](https://linux-hardware.org/?probe=77199b6dc7) | Oct 21, 2024 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [1fcb0f751e](https://linux-hardware.org/?probe=1fcb0f751e) | Oct 21, 2024 |
| Positivo      | Schoolmate SF20GM7          | Notebook    | [4b0b1bae90](https://linux-hardware.org/?probe=4b0b1bae90) | Oct 21, 2024 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [640e88d05a](https://linux-hardware.org/?probe=640e88d05a) | Oct 21, 2024 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [70e4db0926](https://linux-hardware.org/?probe=70e4db0926) | Oct 21, 2024 |
| IT Channel... | PCX0DX                      | Notebook    | [c8d8110356](https://linux-hardware.org/?probe=c8d8110356) | Oct 21, 2024 |
| MSI           | X99S XPOWER AC              | Desktop     | [b089ed1300](https://linux-hardware.org/?probe=b089ed1300) | Oct 20, 2024 |
| System76      | Gazelle                     | Notebook    | [d1a78e6ac2](https://linux-hardware.org/?probe=d1a78e6ac2) | Oct 20, 2024 |
| HP            | ProBook 4740s               | Notebook    | [b2dd7236f6](https://linux-hardware.org/?probe=b2dd7236f6) | Oct 20, 2024 |
| ASRock        | B760M PG Riptide            | Desktop     | [dffb37693f](https://linux-hardware.org/?probe=dffb37693f) | Oct 20, 2024 |
| Acer          | Aspire 7745G                | Notebook    | [48cc1c84fc](https://linux-hardware.org/?probe=48cc1c84fc) | Oct 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [1380476f1e](https://linux-hardware.org/?probe=1380476f1e) | Oct 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [bd85cf1a79](https://linux-hardware.org/?probe=bd85cf1a79) | Oct 19, 2024 |
| HP            | Pavilion dv7                | Notebook    | [77e53f9398](https://linux-hardware.org/?probe=77e53f9398) | Oct 19, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b4ee7a4976](https://linux-hardware.org/?probe=b4ee7a4976) | Oct 19, 2024 |
| HP            | Pavilion HDX9200            | Notebook    | [1098a89014](https://linux-hardware.org/?probe=1098a89014) | Oct 19, 2024 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [c78732df23](https://linux-hardware.org/?probe=c78732df23) | Oct 19, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [519c6c9fce](https://linux-hardware.org/?probe=519c6c9fce) | Oct 19, 2024 |
| Biostar       | A780L                       | Desktop     | [ce27f19033](https://linux-hardware.org/?probe=ce27f19033) | Oct 19, 2024 |
| Dell          | Studio 1555                 | Notebook    | [709087cbff](https://linux-hardware.org/?probe=709087cbff) | Oct 19, 2024 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [ad76756fd0](https://linux-hardware.org/?probe=ad76756fd0) | Oct 19, 2024 |
| MSI           | PRO B650-P WIFI             | Desktop     | [19d2539e75](https://linux-hardware.org/?probe=19d2539e75) | Oct 19, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [e01db3c482](https://linux-hardware.org/?probe=e01db3c482) | Oct 19, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [0b40a221ac](https://linux-hardware.org/?probe=0b40a221ac) | Oct 18, 2024 |
| Sony          | VPCEH1M9R                   | Notebook    | [78491a0382](https://linux-hardware.org/?probe=78491a0382) | Oct 18, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [065239fc07](https://linux-hardware.org/?probe=065239fc07) | Oct 18, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | Notebook    | [62c3d2eddd](https://linux-hardware.org/?probe=62c3d2eddd) | Oct 17, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5dca39ff49](https://linux-hardware.org/?probe=5dca39ff49) | Oct 17, 2024 |
| MSI           | Katana 15 B13VFK            | Notebook    | [45d00541c0](https://linux-hardware.org/?probe=45d00541c0) | Oct 17, 2024 |
| Intel         | X99                         | Desktop     | [057dc6ac9f](https://linux-hardware.org/?probe=057dc6ac9f) | Oct 17, 2024 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [bc04563516](https://linux-hardware.org/?probe=bc04563516) | Oct 17, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [a10a4ae8fa](https://linux-hardware.org/?probe=a10a4ae8fa) | Oct 17, 2024 |
| HP            | 802F                        | Desktop     | [5553cbd4ca](https://linux-hardware.org/?probe=5553cbd4ca) | Oct 17, 2024 |
| HP            | ProBook 650 G2              | Notebook    | [8b6dc142e9](https://linux-hardware.org/?probe=8b6dc142e9) | Oct 17, 2024 |
| Lenovo        | ThinkPad P50 20EQS29A00     | Notebook    | [9cee201a44](https://linux-hardware.org/?probe=9cee201a44) | Oct 17, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5d46c792d0](https://linux-hardware.org/?probe=5d46c792d0) | Oct 17, 2024 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [3bdfd7779b](https://linux-hardware.org/?probe=3bdfd7779b) | Oct 16, 2024 |
| Toshiba       | QOSMIO X775                 | Notebook    | [de226c2b19](https://linux-hardware.org/?probe=de226c2b19) | Oct 16, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [7d89635983](https://linux-hardware.org/?probe=7d89635983) | Oct 16, 2024 |
| Notebook      | W65_W67RB                   | Notebook    | [69df44fe32](https://linux-hardware.org/?probe=69df44fe32) | Oct 16, 2024 |
| Notebook      | W65_W67RB                   | Notebook    | [a787a5ebbb](https://linux-hardware.org/?probe=a787a5ebbb) | Oct 16, 2024 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [9b12651c67](https://linux-hardware.org/?probe=9b12651c67) | Oct 16, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [0a10d42a20](https://linux-hardware.org/?probe=0a10d42a20) | Oct 16, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [b83fb99eb1](https://linux-hardware.org/?probe=b83fb99eb1) | Oct 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [a3e77b53eb](https://linux-hardware.org/?probe=a3e77b53eb) | Oct 16, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [637bebb3f3](https://linux-hardware.org/?probe=637bebb3f3) | Oct 16, 2024 |
| Gigabyte      | Z490 GAMING X AX            | Desktop     | [e726c70ed6](https://linux-hardware.org/?probe=e726c70ed6) | Oct 16, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [76a70beb84](https://linux-hardware.org/?probe=76a70beb84) | Oct 16, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [1d18778ca6](https://linux-hardware.org/?probe=1d18778ca6) | Oct 15, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [56fa2a9b2a](https://linux-hardware.org/?probe=56fa2a9b2a) | Oct 15, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [18cc7921db](https://linux-hardware.org/?probe=18cc7921db) | Oct 15, 2024 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [30fd511ed4](https://linux-hardware.org/?probe=30fd511ed4) | Oct 15, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [e6891ad523](https://linux-hardware.org/?probe=e6891ad523) | Oct 15, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [fdd792f39b](https://linux-hardware.org/?probe=fdd792f39b) | Oct 15, 2024 |
| ASRock        | B550 Taichi Razer Editio... | Desktop     | [6a3e9babae](https://linux-hardware.org/?probe=6a3e9babae) | Oct 15, 2024 |
| ASRock        | B550 Taichi Razer Editio... | Desktop     | [abd8353fc1](https://linux-hardware.org/?probe=abd8353fc1) | Oct 15, 2024 |
| MSI           | H310-F PRO                  | Desktop     | [96e06666bd](https://linux-hardware.org/?probe=96e06666bd) | Oct 15, 2024 |
| Lenovo        | ThinkPad T490s 20NYS3NT0... | Notebook    | [7dd8855689](https://linux-hardware.org/?probe=7dd8855689) | Oct 15, 2024 |
| Dell          | Latitude E7250              | Notebook    | [ce90b269d6](https://linux-hardware.org/?probe=ce90b269d6) | Oct 14, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [4b04c405ca](https://linux-hardware.org/?probe=4b04c405ca) | Oct 14, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [4ab8dafc86](https://linux-hardware.org/?probe=4ab8dafc86) | Oct 14, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [00304ae6db](https://linux-hardware.org/?probe=00304ae6db) | Oct 14, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [8fabff367d](https://linux-hardware.org/?probe=8fabff367d) | Oct 14, 2024 |
| ASRock        | B760M PG Riptide            | Desktop     | [f4e8c2acd6](https://linux-hardware.org/?probe=f4e8c2acd6) | Oct 14, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [a597c210a6](https://linux-hardware.org/?probe=a597c210a6) | Oct 14, 2024 |
| Koloe         | X58                         | Desktop     | [53ff53a4cc](https://linux-hardware.org/?probe=53ff53a4cc) | Oct 14, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [f20e6b3dc8](https://linux-hardware.org/?probe=f20e6b3dc8) | Oct 13, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [ecf92c84fe](https://linux-hardware.org/?probe=ecf92c84fe) | Oct 13, 2024 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [cc3ba34210](https://linux-hardware.org/?probe=cc3ba34210) | Oct 13, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [beeb197b20](https://linux-hardware.org/?probe=beeb197b20) | Oct 13, 2024 |
| ASRock        | AB350M-HDV R3.0             | Desktop     | [0caee97f69](https://linux-hardware.org/?probe=0caee97f69) | Oct 13, 2024 |
| ASUSTek       | E403NA                      | Notebook    | [9ae450e44c](https://linux-hardware.org/?probe=9ae450e44c) | Oct 13, 2024 |
| Dell          | 0CU409                      | Desktop     | [674f7bd1a1](https://linux-hardware.org/?probe=674f7bd1a1) | Oct 13, 2024 |
| Alienware     | 0N4R4N A00                  | Desktop     | [0cfa6f6b4b](https://linux-hardware.org/?probe=0cfa6f6b4b) | Oct 13, 2024 |
| Alienware     | m15 R7                      | Notebook    | [5322ba17a8](https://linux-hardware.org/?probe=5322ba17a8) | Oct 13, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [ec7fc07772](https://linux-hardware.org/?probe=ec7fc07772) | Oct 13, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [24c4bcf3e5](https://linux-hardware.org/?probe=24c4bcf3e5) | Oct 13, 2024 |
| System76      | Lemur                       | Notebook    | [61343c26b9](https://linux-hardware.org/?probe=61343c26b9) | Oct 13, 2024 |
| MSI           | MS-B9351                    | Desktop     | [9ab378024d](https://linux-hardware.org/?probe=9ab378024d) | Oct 13, 2024 |
| HP            | ZBook 15 G3                 | Notebook    | [396d9b1508](https://linux-hardware.org/?probe=396d9b1508) | Oct 12, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [ce0e497ca9](https://linux-hardware.org/?probe=ce0e497ca9) | Oct 12, 2024 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [fc5210bfe4](https://linux-hardware.org/?probe=fc5210bfe4) | Oct 12, 2024 |
| MSI           | Katana 15 B13VFK            | Notebook    | [d5a97499e2](https://linux-hardware.org/?probe=d5a97499e2) | Oct 12, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [8dc9ff9d77](https://linux-hardware.org/?probe=8dc9ff9d77) | Oct 12, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [700a309817](https://linux-hardware.org/?probe=700a309817) | Oct 12, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [57aa3bcdd4](https://linux-hardware.org/?probe=57aa3bcdd4) | Oct 12, 2024 |
| Framework     | Laptop                      | Notebook    | [5a875a182c](https://linux-hardware.org/?probe=5a875a182c) | Oct 11, 2024 |
| Framework     | Laptop                      | Notebook    | [829aae35c2](https://linux-hardware.org/?probe=829aae35c2) | Oct 11, 2024 |
| Dell          | XPS 13 9350                 | Notebook    | [d4ae2f6f73](https://linux-hardware.org/?probe=d4ae2f6f73) | Oct 11, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [4e4e4b33ec](https://linux-hardware.org/?probe=4e4e4b33ec) | Oct 11, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [b40e0a8447](https://linux-hardware.org/?probe=b40e0a8447) | Oct 11, 2024 |
| HP            | EliteBook 640 14 inch G1... | Notebook    | [eb78247aef](https://linux-hardware.org/?probe=eb78247aef) | Oct 11, 2024 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [530feba7a4](https://linux-hardware.org/?probe=530feba7a4) | Oct 11, 2024 |
| Dell          | G3 3579                     | Notebook    | [3f29ebd856](https://linux-hardware.org/?probe=3f29ebd856) | Oct 11, 2024 |
| AZW           | EQ                          | Mini pc     | [2c6d0486b6](https://linux-hardware.org/?probe=2c6d0486b6) | Oct 11, 2024 |
| AZW           | EQ                          | Mini pc     | [97ac401b69](https://linux-hardware.org/?probe=97ac401b69) | Oct 11, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [685ba31b0b](https://linux-hardware.org/?probe=685ba31b0b) | Oct 10, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [7b955e70d1](https://linux-hardware.org/?probe=7b955e70d1) | Oct 10, 2024 |
| ASUSTek       | B150M-C                     | Desktop     | [09809c7c01](https://linux-hardware.org/?probe=09809c7c01) | Oct 10, 2024 |
| ASUSTek       | B150M-C                     | Desktop     | [3c5997535c](https://linux-hardware.org/?probe=3c5997535c) | Oct 10, 2024 |
| MSI           | Katana 15 B13VFK            | Notebook    | [2dd48ca806](https://linux-hardware.org/?probe=2dd48ca806) | Oct 10, 2024 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [767fd4f4a9](https://linux-hardware.org/?probe=767fd4f4a9) | Oct 10, 2024 |
| Foxconn       | 2ADA                        | Desktop     | [1660f30544](https://linux-hardware.org/?probe=1660f30544) | Oct 10, 2024 |
| Dell          | 03VTJ7 A01                  | All in one  | [8af622d194](https://linux-hardware.org/?probe=8af622d194) | Oct 10, 2024 |
| MSI           | Modern 14 A10RB             | Notebook    | [148147f2d5](https://linux-hardware.org/?probe=148147f2d5) | Oct 10, 2024 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [c6cc33d55b](https://linux-hardware.org/?probe=c6cc33d55b) | Oct 10, 2024 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [783833587e](https://linux-hardware.org/?probe=783833587e) | Oct 10, 2024 |
| Foxconn       | 2ADA                        | Desktop     | [48ef106fef](https://linux-hardware.org/?probe=48ef106fef) | Oct 10, 2024 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [0658548720](https://linux-hardware.org/?probe=0658548720) | Oct 10, 2024 |
| Dell          | 096JG8 A00                  | Desktop     | [eeaa3bb7a6](https://linux-hardware.org/?probe=eeaa3bb7a6) | Oct 10, 2024 |
| System76      | Oryx Pro                    | Notebook    | [4a122791a4](https://linux-hardware.org/?probe=4a122791a4) | Oct 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [a3deb73e2b](https://linux-hardware.org/?probe=a3deb73e2b) | Oct 09, 2024 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [9cf0171a3a](https://linux-hardware.org/?probe=9cf0171a3a) | Oct 09, 2024 |
| Dell          | 096JG8 A00                  | Desktop     | [19449a27f3](https://linux-hardware.org/?probe=19449a27f3) | Oct 09, 2024 |
| System76      | Lemur Pro                   | Notebook    | [0e513dcca4](https://linux-hardware.org/?probe=0e513dcca4) | Oct 09, 2024 |
| Lenovo        | ThinkPad W530 24382MU       | Notebook    | [afbcd71537](https://linux-hardware.org/?probe=afbcd71537) | Oct 09, 2024 |
| MSI           | Modern 14 A10RB             | Notebook    | [f1b16a12ac](https://linux-hardware.org/?probe=f1b16a12ac) | Oct 09, 2024 |
| HP            | 2B4B                        | Desktop     | [0591688b19](https://linux-hardware.org/?probe=0591688b19) | Oct 09, 2024 |
| Dell          | Precision M4800             | Notebook    | [87e17e0353](https://linux-hardware.org/?probe=87e17e0353) | Oct 09, 2024 |
| Alienware     | m16 R2                      | Notebook    | [5fe417e971](https://linux-hardware.org/?probe=5fe417e971) | Oct 09, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [be147f67ae](https://linux-hardware.org/?probe=be147f67ae) | Oct 09, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1fc0dd6939](https://linux-hardware.org/?probe=1fc0dd6939) | Oct 09, 2024 |
| Alienware     | 0K9TKY A00                  | Desktop     | [eed362c8ce](https://linux-hardware.org/?probe=eed362c8ce) | Oct 09, 2024 |
| Dell          | Latitude 7400               | Notebook    | [22047a3cd0](https://linux-hardware.org/?probe=22047a3cd0) | Oct 09, 2024 |
| ASRock        | B760M PG Riptide            | Desktop     | [0112e0d2f6](https://linux-hardware.org/?probe=0112e0d2f6) | Oct 09, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [ea25986093](https://linux-hardware.org/?probe=ea25986093) | Oct 09, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | Notebook    | [4a70fc8e54](https://linux-hardware.org/?probe=4a70fc8e54) | Oct 08, 2024 |
| Fujitsu       | D3118-A1 S26361-D3118-A1    | Desktop     | [0b42d66aec](https://linux-hardware.org/?probe=0b42d66aec) | Oct 08, 2024 |
| Fujitsu       | D3118-A1 S26361-D3118-A1    | Desktop     | [f57726906e](https://linux-hardware.org/?probe=f57726906e) | Oct 08, 2024 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [863019f9d8](https://linux-hardware.org/?probe=863019f9d8) | Oct 08, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [0e2f27c078](https://linux-hardware.org/?probe=0e2f27c078) | Oct 08, 2024 |
| Dell          | Inspiron 5537               | Notebook    | [ae9d9a4bb9](https://linux-hardware.org/?probe=ae9d9a4bb9) | Oct 07, 2024 |
| ASUSTek       | PRIME B650M-A AX6           | Desktop     | [6597170653](https://linux-hardware.org/?probe=6597170653) | Oct 07, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [17c5459b00](https://linux-hardware.org/?probe=17c5459b00) | Oct 07, 2024 |
| ASUSTek       | PRIME B650M-A AX6           | Desktop     | [f4948e7ce8](https://linux-hardware.org/?probe=f4948e7ce8) | Oct 07, 2024 |
| ASUSTek       | P6X58D-E                    | Desktop     | [254590d90b](https://linux-hardware.org/?probe=254590d90b) | Oct 07, 2024 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | Desktop     | [8e7794b5e5](https://linux-hardware.org/?probe=8e7794b5e5) | Oct 07, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [4dc891703c](https://linux-hardware.org/?probe=4dc891703c) | Oct 07, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [78f8401511](https://linux-hardware.org/?probe=78f8401511) | Oct 07, 2024 |
| Dell          | Latitude 3420               | Notebook    | [6a7a1635f1](https://linux-hardware.org/?probe=6a7a1635f1) | Oct 07, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [2894d8b661](https://linux-hardware.org/?probe=2894d8b661) | Oct 07, 2024 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [08cfc5774e](https://linux-hardware.org/?probe=08cfc5774e) | Oct 06, 2024 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [224dee322a](https://linux-hardware.org/?probe=224dee322a) | Oct 06, 2024 |
| Lenovo        | 31900058 STD                | All in one  | [306f7a3dfa](https://linux-hardware.org/?probe=306f7a3dfa) | Oct 06, 2024 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [910f2543e2](https://linux-hardware.org/?probe=910f2543e2) | Oct 06, 2024 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [9789a4a540](https://linux-hardware.org/?probe=9789a4a540) | Oct 06, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [f0ff453f6e](https://linux-hardware.org/?probe=f0ff453f6e) | Oct 06, 2024 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [e395202fd1](https://linux-hardware.org/?probe=e395202fd1) | Oct 05, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [2965460cd4](https://linux-hardware.org/?probe=2965460cd4) | Oct 05, 2024 |
| Dell          | 0K240Y A01                  | Desktop     | [67e40a612b](https://linux-hardware.org/?probe=67e40a612b) | Oct 05, 2024 |
| System76      | Bonobo WS                   | Notebook    | [cb3f9574d5](https://linux-hardware.org/?probe=cb3f9574d5) | Oct 05, 2024 |
| Dell          | Inspiron 5379               | Notebook    | [d4ec7c3588](https://linux-hardware.org/?probe=d4ec7c3588) | Oct 05, 2024 |
| Gigabyte      | Z170-HD3-CF                 | Desktop     | [8ef4229227](https://linux-hardware.org/?probe=8ef4229227) | Oct 05, 2024 |
| Gigabyte      | Z170-HD3-CF                 | Desktop     | [b3d161f10c](https://linux-hardware.org/?probe=b3d161f10c) | Oct 05, 2024 |
| Dell          | 0F65XD A00                  | All in one  | [2c3b5d8503](https://linux-hardware.org/?probe=2c3b5d8503) | Oct 05, 2024 |
| Microsoft     | Surface Laptop 4            | Tablet      | [dc904edb7c](https://linux-hardware.org/?probe=dc904edb7c) | Oct 05, 2024 |
| ASRock        | 970 Extreme3                | Desktop     | [3350145c6a](https://linux-hardware.org/?probe=3350145c6a) | Oct 05, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [057d1d7a74](https://linux-hardware.org/?probe=057d1d7a74) | Oct 04, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [5a7e21c336](https://linux-hardware.org/?probe=5a7e21c336) | Oct 04, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [09718bd83a](https://linux-hardware.org/?probe=09718bd83a) | Oct 04, 2024 |
| ASRock        | 970 Extreme3                | Desktop     | [8eaad2bb51](https://linux-hardware.org/?probe=8eaad2bb51) | Oct 04, 2024 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [73a4fb7e13](https://linux-hardware.org/?probe=73a4fb7e13) | Oct 04, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [64e32d6a96](https://linux-hardware.org/?probe=64e32d6a96) | Oct 04, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [b675409877](https://linux-hardware.org/?probe=b675409877) | Oct 04, 2024 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [1c4d33ad9a](https://linux-hardware.org/?probe=1c4d33ad9a) | Oct 04, 2024 |
| HP            | Pavilion g6                 | Notebook    | [1a77adf7d3](https://linux-hardware.org/?probe=1a77adf7d3) | Oct 04, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [db53c1e876](https://linux-hardware.org/?probe=db53c1e876) | Oct 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E70... | Notebook    | [28caf4f8a8](https://linux-hardware.org/?probe=28caf4f8a8) | Oct 04, 2024 |
| MSI           | PRO B650-P WIFI             | Desktop     | [2d97f44bd4](https://linux-hardware.org/?probe=2d97f44bd4) | Oct 03, 2024 |
| MSI           | Katana 17 B13VGK            | Notebook    | [554bc53d9e](https://linux-hardware.org/?probe=554bc53d9e) | Oct 03, 2024 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [666ea6e8cf](https://linux-hardware.org/?probe=666ea6e8cf) | Oct 03, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [11620bee22](https://linux-hardware.org/?probe=11620bee22) | Oct 03, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [4462ad232a](https://linux-hardware.org/?probe=4462ad232a) | Oct 03, 2024 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [5a20f0fbcf](https://linux-hardware.org/?probe=5a20f0fbcf) | Oct 03, 2024 |
| MSI           | GP72M 7REX                  | Notebook    | [ed03e0a42a](https://linux-hardware.org/?probe=ed03e0a42a) | Oct 03, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [43ebb1e4ec](https://linux-hardware.org/?probe=43ebb1e4ec) | Oct 03, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [7d968335d4](https://linux-hardware.org/?probe=7d968335d4) | Oct 03, 2024 |
| HP            | Compaq Presario CQ41        | Notebook    | [8883290af4](https://linux-hardware.org/?probe=8883290af4) | Oct 03, 2024 |
| Unknown       | Unknown                     | Notebook    | [724da43eb0](https://linux-hardware.org/?probe=724da43eb0) | Oct 03, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [66c7197cab](https://linux-hardware.org/?probe=66c7197cab) | Oct 03, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [0b81ce4446](https://linux-hardware.org/?probe=0b81ce4446) | Oct 03, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [caae52edaa](https://linux-hardware.org/?probe=caae52edaa) | Oct 02, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6f1403e89a](https://linux-hardware.org/?probe=6f1403e89a) | Oct 02, 2024 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [234ffa3729](https://linux-hardware.org/?probe=234ffa3729) | Oct 02, 2024 |
| Gigabyte      | Z590 VISION D               | Desktop     | [992bb7d24d](https://linux-hardware.org/?probe=992bb7d24d) | Oct 02, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [603ca0f8d7](https://linux-hardware.org/?probe=603ca0f8d7) | Oct 02, 2024 |
| Toshiba       | Satellite Pro C50-B         | Notebook    | [73cecf0985](https://linux-hardware.org/?probe=73cecf0985) | Oct 02, 2024 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [e0b7091ba1](https://linux-hardware.org/?probe=e0b7091ba1) | Oct 01, 2024 |
| Lenovo        | Legion Pro 5 16IRX9 83DF    | Notebook    | [041554f4bd](https://linux-hardware.org/?probe=041554f4bd) | Oct 01, 2024 |
| Dell          | XPS 13 9350                 | Notebook    | [4b43e1f37c](https://linux-hardware.org/?probe=4b43e1f37c) | Oct 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [8f6ef31fc0](https://linux-hardware.org/?probe=8f6ef31fc0) | Oct 01, 2024 |
| Lenovo        | Yoga 7 14IRL8 82YL          | Convertible | [aa0237c753](https://linux-hardware.org/?probe=aa0237c753) | Oct 01, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [5719cacbe1](https://linux-hardware.org/?probe=5719cacbe1) | Oct 01, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [73dd513b22](https://linux-hardware.org/?probe=73dd513b22) | Oct 01, 2024 |
| Acer          | Aspire A515-55              | Notebook    | [38c3405231](https://linux-hardware.org/?probe=38c3405231) | Oct 01, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [7ca3c3aec3](https://linux-hardware.org/?probe=7ca3c3aec3) | Sep 30, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [2d94aeca06](https://linux-hardware.org/?probe=2d94aeca06) | Sep 30, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [98a4b8db1c](https://linux-hardware.org/?probe=98a4b8db1c) | Sep 30, 2024 |
| Dell          | Latitude E6320              | Notebook    | [e83def8251](https://linux-hardware.org/?probe=e83def8251) | Sep 30, 2024 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [57486ad52c](https://linux-hardware.org/?probe=57486ad52c) | Sep 30, 2024 |
| Dynabook      | TECRA A40-E                 | Notebook    | [78617fd33a](https://linux-hardware.org/?probe=78617fd33a) | Sep 30, 2024 |
| Samsung       | 750XED                      | Notebook    | [4678fb79d7](https://linux-hardware.org/?probe=4678fb79d7) | Sep 30, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [958be4ca06](https://linux-hardware.org/?probe=958be4ca06) | Sep 30, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a6e4176354](https://linux-hardware.org/?probe=a6e4176354) | Sep 30, 2024 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [b71712ef82](https://linux-hardware.org/?probe=b71712ef82) | Sep 30, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dbc07b818f](https://linux-hardware.org/?probe=dbc07b818f) | Sep 29, 2024 |
| HP            | 8597                        | Desktop     | [39f106b002](https://linux-hardware.org/?probe=39f106b002) | Sep 29, 2024 |
| HP            | 18E5                        | Desktop     | [e1758fc5c4](https://linux-hardware.org/?probe=e1758fc5c4) | Sep 29, 2024 |
| HP            | 1493                        | Desktop     | [6e42b160f1](https://linux-hardware.org/?probe=6e42b160f1) | Sep 29, 2024 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [506731ea8d](https://linux-hardware.org/?probe=506731ea8d) | Sep 29, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [f267e0be7a](https://linux-hardware.org/?probe=f267e0be7a) | Sep 29, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [3db990dffa](https://linux-hardware.org/?probe=3db990dffa) | Sep 29, 2024 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [eda2ccd052](https://linux-hardware.org/?probe=eda2ccd052) | Sep 29, 2024 |
| Dell          | 0KRC95 A00                  | Desktop     | [886b6b82bf](https://linux-hardware.org/?probe=886b6b82bf) | Sep 29, 2024 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ccbfad6c6d](https://linux-hardware.org/?probe=ccbfad6c6d) | Sep 29, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [c356997396](https://linux-hardware.org/?probe=c356997396) | Sep 28, 2024 |
| ASRock        | H470M-HDV/M.2               | Desktop     | [8158f71264](https://linux-hardware.org/?probe=8158f71264) | Sep 28, 2024 |
| Sony          | SVE15126CAB                 | Notebook    | [f60413658c](https://linux-hardware.org/?probe=f60413658c) | Sep 28, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [5bbf147e3a](https://linux-hardware.org/?probe=5bbf147e3a) | Sep 28, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [2660b5ddef](https://linux-hardware.org/?probe=2660b5ddef) | Sep 28, 2024 |
| PC Special... | Ionico 15 M                 | Notebook    | [1f586c152d](https://linux-hardware.org/?probe=1f586c152d) | Sep 27, 2024 |
| TianBei       | GOD88                       | Desktop     | [14aaf1d0f2](https://linux-hardware.org/?probe=14aaf1d0f2) | Sep 27, 2024 |
| Lenovo        | ThinkPad W550s 20E2000QU... | Notebook    | [5adcba6b0e](https://linux-hardware.org/?probe=5adcba6b0e) | Sep 27, 2024 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [1af97168e8](https://linux-hardware.org/?probe=1af97168e8) | Sep 27, 2024 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [7b4b348c98](https://linux-hardware.org/?probe=7b4b348c98) | Sep 27, 2024 |
| HP            | Spectre x360 Convertible    | Convertible | [571e547c1b](https://linux-hardware.org/?probe=571e547c1b) | Sep 27, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dc0da7194e](https://linux-hardware.org/?probe=dc0da7194e) | Sep 27, 2024 |
| ASUSTek       | K95VM                       | Notebook    | [ff438ad161](https://linux-hardware.org/?probe=ff438ad161) | Sep 27, 2024 |
| Acer          | Aspire R5-571T              | Convertible | [e962373988](https://linux-hardware.org/?probe=e962373988) | Sep 27, 2024 |
| Acer          | Aspire R5-571T              | Convertible | [915c7cb797](https://linux-hardware.org/?probe=915c7cb797) | Sep 27, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [35ddc3009c](https://linux-hardware.org/?probe=35ddc3009c) | Sep 27, 2024 |
| Dell          | 0VHWTR A02                  | Desktop     | [5edaae1ca1](https://linux-hardware.org/?probe=5edaae1ca1) | Sep 27, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [7956faa4b1](https://linux-hardware.org/?probe=7956faa4b1) | Sep 27, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [93e19e497d](https://linux-hardware.org/?probe=93e19e497d) | Sep 27, 2024 |
| ASRock        | N68-GS4 FX R2.0             | Notebook    | [5e82748806](https://linux-hardware.org/?probe=5e82748806) | Sep 26, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [48982f9836](https://linux-hardware.org/?probe=48982f9836) | Sep 26, 2024 |
| Lenovo        | ThinkPad W550s 20E2000QU... | Notebook    | [fe8af671af](https://linux-hardware.org/?probe=fe8af671af) | Sep 26, 2024 |
| PC Special... | P65_67HSHP                  | Notebook    | [2313271b0b](https://linux-hardware.org/?probe=2313271b0b) | Sep 26, 2024 |
| HP            | EliteBook 745 G2            | Notebook    | [6f10a18bc8](https://linux-hardware.org/?probe=6f10a18bc8) | Sep 25, 2024 |
| MSI           | H410M-A PRO                 | Desktop     | [13cba33fe8](https://linux-hardware.org/?probe=13cba33fe8) | Sep 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0e0ec9b83b](https://linux-hardware.org/?probe=0e0ec9b83b) | Sep 25, 2024 |
| HP            | ZBook 15 G5                 | Notebook    | [d62ce9aa5a](https://linux-hardware.org/?probe=d62ce9aa5a) | Sep 25, 2024 |
| System76      | Lemur Pro                   | Notebook    | [31bd01c8bf](https://linux-hardware.org/?probe=31bd01c8bf) | Sep 25, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | Notebook    | [624d235669](https://linux-hardware.org/?probe=624d235669) | Sep 25, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4bd09ca30d](https://linux-hardware.org/?probe=4bd09ca30d) | Sep 24, 2024 |
| Acer          | Swift SFX14-41G             | Notebook    | [ec357b358b](https://linux-hardware.org/?probe=ec357b358b) | Sep 24, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [c838d3cbb1](https://linux-hardware.org/?probe=c838d3cbb1) | Sep 24, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [05bb9f7907](https://linux-hardware.org/?probe=05bb9f7907) | Sep 24, 2024 |
| MACHINIST     | E5-MR9S V1.0                | Desktop     | [334e949999](https://linux-hardware.org/?probe=334e949999) | Sep 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2091c77d29](https://linux-hardware.org/?probe=2091c77d29) | Sep 24, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [e7c859dacc](https://linux-hardware.org/?probe=e7c859dacc) | Sep 24, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6bc276c52f](https://linux-hardware.org/?probe=6bc276c52f) | Sep 24, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c4e195980b](https://linux-hardware.org/?probe=c4e195980b) | Sep 23, 2024 |
| GPD           | G1619-04                    | Notebook    | [058bd4c7ff](https://linux-hardware.org/?probe=058bd4c7ff) | Sep 23, 2024 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [20e79a1fff](https://linux-hardware.org/?probe=20e79a1fff) | Sep 23, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E70... | Notebook    | [df85d46568](https://linux-hardware.org/?probe=df85d46568) | Sep 23, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [3702cf8035](https://linux-hardware.org/?probe=3702cf8035) | Sep 23, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [e6d5ee9fc0](https://linux-hardware.org/?probe=e6d5ee9fc0) | Sep 23, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [76e2b2a322](https://linux-hardware.org/?probe=76e2b2a322) | Sep 22, 2024 |
| Dell          | 0VHWTR A02                  | Desktop     | [d5a9f39421](https://linux-hardware.org/?probe=d5a9f39421) | Sep 22, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8ee1bad547](https://linux-hardware.org/?probe=8ee1bad547) | Sep 22, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [78e3642c86](https://linux-hardware.org/?probe=78e3642c86) | Sep 22, 2024 |
| MSI           | Katana GF76 11UE            | Notebook    | [e49bd98e54](https://linux-hardware.org/?probe=e49bd98e54) | Sep 22, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [dc1a763d32](https://linux-hardware.org/?probe=dc1a763d32) | Sep 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [28d162298f](https://linux-hardware.org/?probe=28d162298f) | Sep 22, 2024 |
| ASUSTek       | X541UJ                      | Notebook    | [cc2936a90c](https://linux-hardware.org/?probe=cc2936a90c) | Sep 22, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f1a006d1e1](https://linux-hardware.org/?probe=f1a006d1e1) | Sep 21, 2024 |
| Intel         | NUC13ANBi7 N13084-202       | Mini pc     | [51939428f0](https://linux-hardware.org/?probe=51939428f0) | Sep 21, 2024 |
| MSI           | Katana GF76 11UE            | Notebook    | [89bb8dc2c6](https://linux-hardware.org/?probe=89bb8dc2c6) | Sep 21, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [2f3706f0c5](https://linux-hardware.org/?probe=2f3706f0c5) | Sep 21, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [fdc7cf356a](https://linux-hardware.org/?probe=fdc7cf356a) | Sep 21, 2024 |
| Gigabyte      | B550 UD AC-Y1               | Desktop     | [aa5cd0be8f](https://linux-hardware.org/?probe=aa5cd0be8f) | Sep 21, 2024 |
| System76      | Oryx Pro                    | Notebook    | [6610d42db1](https://linux-hardware.org/?probe=6610d42db1) | Sep 20, 2024 |
| Lenovo        | 31900058 STD                | Desktop     | [87e28eedb3](https://linux-hardware.org/?probe=87e28eedb3) | Sep 20, 2024 |
| Lenovo        | ThinkPad T490 20N2S07G00    | Notebook    | [4a36fced72](https://linux-hardware.org/?probe=4a36fced72) | Sep 20, 2024 |
| HP            | Dragonfly Pro Laptop PC     | Notebook    | [9fb2ecaa2b](https://linux-hardware.org/?probe=9fb2ecaa2b) | Sep 20, 2024 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [22f518504d](https://linux-hardware.org/?probe=22f518504d) | Sep 20, 2024 |
| ASUSTek       | TUF Gaming B650-E WIFI      | Desktop     | [cbdf576f50](https://linux-hardware.org/?probe=cbdf576f50) | Sep 19, 2024 |
| ASUSTek       | G751JM                      | Notebook    | [87122432ea](https://linux-hardware.org/?probe=87122432ea) | Sep 19, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [dfc03a83e8](https://linux-hardware.org/?probe=dfc03a83e8) | Sep 19, 2024 |
| ASUSTek       | H81-GAMER                   | Desktop     | [be55c0ed79](https://linux-hardware.org/?probe=be55c0ed79) | Sep 19, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [068811de2e](https://linux-hardware.org/?probe=068811de2e) | Sep 19, 2024 |
| Dell          | Inspiron 7460               | Notebook    | [15df31e515](https://linux-hardware.org/?probe=15df31e515) | Sep 19, 2024 |
| Toshiba       | Satellite Pro C50-B         | Notebook    | [42a9f50fe0](https://linux-hardware.org/?probe=42a9f50fe0) | Sep 19, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e6a4fd809a](https://linux-hardware.org/?probe=e6a4fd809a) | Sep 18, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2aaab87e79](https://linux-hardware.org/?probe=2aaab87e79) | Sep 18, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | Desktop     | [0fd910b3ad](https://linux-hardware.org/?probe=0fd910b3ad) | Sep 18, 2024 |
| Dell          | XPS 13 9343                 | Notebook    | [da87bf7199](https://linux-hardware.org/?probe=da87bf7199) | Sep 18, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [09db67859d](https://linux-hardware.org/?probe=09db67859d) | Sep 18, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [bf484e7b21](https://linux-hardware.org/?probe=bf484e7b21) | Sep 18, 2024 |
| ASUSTek       | Z97-A                       | Desktop     | [15116f089f](https://linux-hardware.org/?probe=15116f089f) | Sep 18, 2024 |
| ASUSTek       | M4A78T-E                    | Desktop     | [b079e72277](https://linux-hardware.org/?probe=b079e72277) | Sep 18, 2024 |
| Lenovo        | ThinkPad T490 20N2S07G00    | Notebook    | [b44af6782f](https://linux-hardware.org/?probe=b44af6782f) | Sep 18, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [56e8709eb2](https://linux-hardware.org/?probe=56e8709eb2) | Sep 17, 2024 |
| Dell          | 0YJMC0 A01                  | Desktop     | [f4d1431f71](https://linux-hardware.org/?probe=f4d1431f71) | Sep 17, 2024 |
| Lenovo        | 333B SDK0T76465 WIN 3422... | Desktop     | [3ebea78539](https://linux-hardware.org/?probe=3ebea78539) | Sep 17, 2024 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [bc3c822394](https://linux-hardware.org/?probe=bc3c822394) | Sep 17, 2024 |
| ASRock        | B365M-HDV                   | Desktop     | [4f11e504a4](https://linux-hardware.org/?probe=4f11e504a4) | Sep 17, 2024 |
| ASRock        | B650I Lightning WiFi        | Desktop     | [f8098b07c0](https://linux-hardware.org/?probe=f8098b07c0) | Sep 17, 2024 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [546a79a8e1](https://linux-hardware.org/?probe=546a79a8e1) | Sep 17, 2024 |
| Samsung       | 730QDA                      | Convertible | [1394b7b8f0](https://linux-hardware.org/?probe=1394b7b8f0) | Sep 17, 2024 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [8d70e14b2c](https://linux-hardware.org/?probe=8d70e14b2c) | Sep 17, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [ebd8e172d8](https://linux-hardware.org/?probe=ebd8e172d8) | Sep 17, 2024 |
| HP            | Notebook                    | Notebook    | [e7a6a098de](https://linux-hardware.org/?probe=e7a6a098de) | Sep 16, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [4cec70b2ed](https://linux-hardware.org/?probe=4cec70b2ed) | Sep 16, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [72effb4ee2](https://linux-hardware.org/?probe=72effb4ee2) | Sep 16, 2024 |
| Lenovo        | ThinkPad T495 20NKS0JH00    | Notebook    | [9c1b1955e0](https://linux-hardware.org/?probe=9c1b1955e0) | Sep 16, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [0f1839e516](https://linux-hardware.org/?probe=0f1839e516) | Sep 16, 2024 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [bc22f163ca](https://linux-hardware.org/?probe=bc22f163ca) | Sep 16, 2024 |
| Google        | Bobba                       | Notebook    | [2b41ad3d59](https://linux-hardware.org/?probe=2b41ad3d59) | Sep 16, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [c77fca48aa](https://linux-hardware.org/?probe=c77fca48aa) | Sep 16, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K3C... | Notebook    | [8e2cbf4a4c](https://linux-hardware.org/?probe=8e2cbf4a4c) | Sep 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K3C... | Notebook    | [ba58290a64](https://linux-hardware.org/?probe=ba58290a64) | Sep 15, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [246cf80922](https://linux-hardware.org/?probe=246cf80922) | Sep 15, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [7091a187b3](https://linux-hardware.org/?probe=7091a187b3) | Sep 15, 2024 |
| Lenovo        | ThinkBook 16 G5+ APH 21K... | Notebook    | [27a7675f10](https://linux-hardware.org/?probe=27a7675f10) | Sep 15, 2024 |
| Dell          | Latitude 5310               | Notebook    | [f0c48c0f9b](https://linux-hardware.org/?probe=f0c48c0f9b) | Sep 15, 2024 |
| OEM           | X79G                        | Desktop     | [6469747833](https://linux-hardware.org/?probe=6469747833) | Sep 15, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [74c6dede90](https://linux-hardware.org/?probe=74c6dede90) | Sep 15, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [fc5fb22b68](https://linux-hardware.org/?probe=fc5fb22b68) | Sep 15, 2024 |
| Lenovo        | ThinkPad T490s 20NX0036U... | Notebook    | [67e46acf77](https://linux-hardware.org/?probe=67e46acf77) | Sep 15, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [bccbd4f8b4](https://linux-hardware.org/?probe=bccbd4f8b4) | Sep 15, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [55b783934d](https://linux-hardware.org/?probe=55b783934d) | Sep 14, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [cb87380418](https://linux-hardware.org/?probe=cb87380418) | Sep 14, 2024 |
| Dell          | Latitude 5310               | Notebook    | [7f39ee7afe](https://linux-hardware.org/?probe=7f39ee7afe) | Sep 14, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [83680c3917](https://linux-hardware.org/?probe=83680c3917) | Sep 14, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [bc6a4c8d93](https://linux-hardware.org/?probe=bc6a4c8d93) | Sep 14, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [f135e80c90](https://linux-hardware.org/?probe=f135e80c90) | Sep 14, 2024 |
| Lenovo        | Yoga 7 2-in-1 16AHP9 83D... | Convertible | [e628656b9c](https://linux-hardware.org/?probe=e628656b9c) | Sep 14, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d2eade6008](https://linux-hardware.org/?probe=d2eade6008) | Sep 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7c8b25d3fc](https://linux-hardware.org/?probe=7c8b25d3fc) | Sep 14, 2024 |
| MSI           | B75MA-P45                   | Desktop     | [5f511858b7](https://linux-hardware.org/?probe=5f511858b7) | Sep 13, 2024 |
| MSI           | B75MA-P45                   | Desktop     | [2268718971](https://linux-hardware.org/?probe=2268718971) | Sep 13, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [14c0a6e948](https://linux-hardware.org/?probe=14c0a6e948) | Sep 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c303f60d53](https://linux-hardware.org/?probe=c303f60d53) | Sep 12, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f7f43b9e05](https://linux-hardware.org/?probe=f7f43b9e05) | Sep 12, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FWS1... | Notebook    | [286d8bff4c](https://linux-hardware.org/?probe=286d8bff4c) | Sep 12, 2024 |
| HP            | EliteBook 8470w             | Notebook    | [a4891795bf](https://linux-hardware.org/?probe=a4891795bf) | Sep 12, 2024 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [fb65fd07fd](https://linux-hardware.org/?probe=fb65fd07fd) | Sep 12, 2024 |
| HP            | ProBook 440 G6              | Notebook    | [05e673b163](https://linux-hardware.org/?probe=05e673b163) | Sep 12, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [8af7dfeb86](https://linux-hardware.org/?probe=8af7dfeb86) | Sep 12, 2024 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [2478ecb6d7](https://linux-hardware.org/?probe=2478ecb6d7) | Sep 12, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [db5724bfce](https://linux-hardware.org/?probe=db5724bfce) | Sep 11, 2024 |
| Dell          | Latitude 5285               | Notebook    | [c6cfa428e6](https://linux-hardware.org/?probe=c6cfa428e6) | Sep 11, 2024 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [67b8e095f4](https://linux-hardware.org/?probe=67b8e095f4) | Sep 11, 2024 |
| Dell          | Latitude 5285               | Notebook    | [c01121651d](https://linux-hardware.org/?probe=c01121651d) | Sep 11, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [e40bbe8a99](https://linux-hardware.org/?probe=e40bbe8a99) | Sep 11, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [7db9f5c232](https://linux-hardware.org/?probe=7db9f5c232) | Sep 11, 2024 |
| Dell          | Vostro 2520                 | Notebook    | [39215cb0ac](https://linux-hardware.org/?probe=39215cb0ac) | Sep 11, 2024 |
| MSI           | 880GMS-E41                  | Desktop     | [2bf925c67c](https://linux-hardware.org/?probe=2bf925c67c) | Sep 11, 2024 |
| Dell          | 08NG84 A01                  | All in one  | [4806e29a9a](https://linux-hardware.org/?probe=4806e29a9a) | Sep 11, 2024 |
| ASRock        | Z390 Pro4                   | Desktop     | [ae24d0086f](https://linux-hardware.org/?probe=ae24d0086f) | Sep 11, 2024 |
| ASUSTek       | U36JC                       | Notebook    | [17939b0154](https://linux-hardware.org/?probe=17939b0154) | Sep 11, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [7d69f47d2e](https://linux-hardware.org/?probe=7d69f47d2e) | Sep 11, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [cfcf6ea362](https://linux-hardware.org/?probe=cfcf6ea362) | Sep 11, 2024 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | Notebook    | [19682cb902](https://linux-hardware.org/?probe=19682cb902) | Sep 10, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [e8ae45a202](https://linux-hardware.org/?probe=e8ae45a202) | Sep 10, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [d9d1b453e2](https://linux-hardware.org/?probe=d9d1b453e2) | Sep 10, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [35ebae4c04](https://linux-hardware.org/?probe=35ebae4c04) | Sep 10, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [d8b1c359a7](https://linux-hardware.org/?probe=d8b1c359a7) | Sep 10, 2024 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [80d75616ad](https://linux-hardware.org/?probe=80d75616ad) | Sep 10, 2024 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [cf75a7672b](https://linux-hardware.org/?probe=cf75a7672b) | Sep 10, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [8a13bf7683](https://linux-hardware.org/?probe=8a13bf7683) | Sep 10, 2024 |
| Dell          | Latitude E7450              | Notebook    | [c44971afd2](https://linux-hardware.org/?probe=c44971afd2) | Sep 10, 2024 |
| Notebook      | NJx0PU                      | Notebook    | [a3df6e5e48](https://linux-hardware.org/?probe=a3df6e5e48) | Sep 09, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [47253bcf4b](https://linux-hardware.org/?probe=47253bcf4b) | Sep 09, 2024 |
| Lenovo        | ThinkPad T420 4236PFG       | Notebook    | [7d198fc2a8](https://linux-hardware.org/?probe=7d198fc2a8) | Sep 09, 2024 |
| HP            | Notebook                    | Notebook    | [7392bbfc0f](https://linux-hardware.org/?probe=7392bbfc0f) | Sep 09, 2024 |
| Lenovo        | 1038 SDK0K17763 WIN 1801... | Server      | [e43c302ba4](https://linux-hardware.org/?probe=e43c302ba4) | Sep 09, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [7b19658095](https://linux-hardware.org/?probe=7b19658095) | Sep 09, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | Notebook    | [7c88f99720](https://linux-hardware.org/?probe=7c88f99720) | Sep 09, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [1897a60c78](https://linux-hardware.org/?probe=1897a60c78) | Sep 09, 2024 |
| ASRock        | A520M/ac                    | Desktop     | [a612bc35e1](https://linux-hardware.org/?probe=a612bc35e1) | Sep 09, 2024 |
| Intel         | NUC7i5BNB J31144-312        | Mini pc     | [6be9531947](https://linux-hardware.org/?probe=6be9531947) | Sep 08, 2024 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [e6c0c03a84](https://linux-hardware.org/?probe=e6c0c03a84) | Sep 08, 2024 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [c035e6b964](https://linux-hardware.org/?probe=c035e6b964) | Sep 08, 2024 |
| ASUSTek       | M4A785-M                    | Desktop     | [9182978bbb](https://linux-hardware.org/?probe=9182978bbb) | Sep 08, 2024 |
| HP            | 242 G1                      | Notebook    | [b3dea9f0da](https://linux-hardware.org/?probe=b3dea9f0da) | Sep 08, 2024 |
| HP            | Victus by Laptop PC         | Notebook    | [9e793a27cc](https://linux-hardware.org/?probe=9e793a27cc) | Sep 08, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [19a2d37f08](https://linux-hardware.org/?probe=19a2d37f08) | Sep 08, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [84cf77aa77](https://linux-hardware.org/?probe=84cf77aa77) | Sep 08, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a610abe7e7](https://linux-hardware.org/?probe=a610abe7e7) | Sep 08, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [6e97ea00ea](https://linux-hardware.org/?probe=6e97ea00ea) | Sep 08, 2024 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [7cb36d2589](https://linux-hardware.org/?probe=7cb36d2589) | Sep 07, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [c2cef73d11](https://linux-hardware.org/?probe=c2cef73d11) | Sep 07, 2024 |
| Intel         | BOX-J4105A V3.0             | Desktop     | [b1d4dd0bd4](https://linux-hardware.org/?probe=b1d4dd0bd4) | Sep 07, 2024 |
| Intel         | BOX-J4105A V3.0             | Desktop     | [01d917fce6](https://linux-hardware.org/?probe=01d917fce6) | Sep 07, 2024 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [3ccc7931f9](https://linux-hardware.org/?probe=3ccc7931f9) | Sep 07, 2024 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [347ed4b41d](https://linux-hardware.org/?probe=347ed4b41d) | Sep 07, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [8062c8c6db](https://linux-hardware.org/?probe=8062c8c6db) | Sep 07, 2024 |
| Lenovo        | ThinkPad P53s 20N60024US    | Notebook    | [641f3bbdd3](https://linux-hardware.org/?probe=641f3bbdd3) | Sep 06, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [825f329b50](https://linux-hardware.org/?probe=825f329b50) | Sep 05, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [670cadb94c](https://linux-hardware.org/?probe=670cadb94c) | Sep 05, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [522312baa5](https://linux-hardware.org/?probe=522312baa5) | Sep 05, 2024 |
| MSI           | Prestige 16 AI Evo B1MG     | Notebook    | [4d8f25ca50](https://linux-hardware.org/?probe=4d8f25ca50) | Sep 04, 2024 |
| Acer          | Aspire 7741                 | Notebook    | [7454e59875](https://linux-hardware.org/?probe=7454e59875) | Sep 04, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a2923c2916](https://linux-hardware.org/?probe=a2923c2916) | Sep 04, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [865f1eb417](https://linux-hardware.org/?probe=865f1eb417) | Sep 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0f5f95ee18](https://linux-hardware.org/?probe=0f5f95ee18) | Sep 04, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a62e0834a8](https://linux-hardware.org/?probe=a62e0834a8) | Sep 04, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f77ded39c0](https://linux-hardware.org/?probe=f77ded39c0) | Sep 04, 2024 |
| HP            | 3397                        | Desktop     | [010527f0d2](https://linux-hardware.org/?probe=010527f0d2) | Sep 04, 2024 |
| ASUSTek       | UX390UAK                    | Notebook    | [242fa7cdab](https://linux-hardware.org/?probe=242fa7cdab) | Sep 04, 2024 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [2e9c4a3189](https://linux-hardware.org/?probe=2e9c4a3189) | Sep 04, 2024 |
| EXTRA Comp... | exone go Premico 1580 X1... | Notebook    | [1703bad8ec](https://linux-hardware.org/?probe=1703bad8ec) | Sep 03, 2024 |
| Dell          | Inspiron 5566               | Notebook    | [84f12b65b5](https://linux-hardware.org/?probe=84f12b65b5) | Sep 03, 2024 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [ca76b9cc1f](https://linux-hardware.org/?probe=ca76b9cc1f) | Sep 03, 2024 |
| ASRock        | B650E PG-ITX WiFi           | Desktop     | [64739c4c52](https://linux-hardware.org/?probe=64739c4c52) | Sep 03, 2024 |
| ASRock        | B650E PG-ITX WiFi           | Desktop     | [2f6b2386f3](https://linux-hardware.org/?probe=2f6b2386f3) | Sep 03, 2024 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [3f9d434cda](https://linux-hardware.org/?probe=3f9d434cda) | Sep 03, 2024 |
| ASUSTek       | M4A78T-E                    | Desktop     | [ba9e4ef02e](https://linux-hardware.org/?probe=ba9e4ef02e) | Sep 03, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | Desktop     | [59c732d659](https://linux-hardware.org/?probe=59c732d659) | Sep 03, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | Desktop     | [f1cb450aad](https://linux-hardware.org/?probe=f1cb450aad) | Sep 03, 2024 |
| MSI           | Prestige 16 AI Evo B1MG     | Notebook    | [6218dfd8cc](https://linux-hardware.org/?probe=6218dfd8cc) | Sep 03, 2024 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [e22706262c](https://linux-hardware.org/?probe=e22706262c) | Sep 03, 2024 |
| Alienware     | 0K9TKY A00                  | Desktop     | [5cd57cb73f](https://linux-hardware.org/?probe=5cd57cb73f) | Sep 02, 2024 |
| ASUSTek       | N550LF                      | Notebook    | [62e647ec99](https://linux-hardware.org/?probe=62e647ec99) | Sep 02, 2024 |
| ASRock        | B450 Gaming K4              | Desktop     | [bbaaf71d62](https://linux-hardware.org/?probe=bbaaf71d62) | Sep 02, 2024 |
| Avell         | A52i                        | Notebook    | [c3a2ce627d](https://linux-hardware.org/?probe=c3a2ce627d) | Sep 02, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3af188ae70](https://linux-hardware.org/?probe=3af188ae70) | Sep 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a1e397371d](https://linux-hardware.org/?probe=a1e397371d) | Sep 02, 2024 |
| ASRock        | ALiveNF6G-VSTA              | Desktop     | [d5b3f47a4f](https://linux-hardware.org/?probe=d5b3f47a4f) | Sep 02, 2024 |
| ASRock        | ALiveNF6G-VSTA              | Desktop     | [e90b700498](https://linux-hardware.org/?probe=e90b700498) | Sep 02, 2024 |
| ASRock        | B550M Steel Legend          | Desktop     | [417c981b8f](https://linux-hardware.org/?probe=417c981b8f) | Sep 02, 2024 |
| Dell          | G7 7588                     | Notebook    | [ea9cfd2431](https://linux-hardware.org/?probe=ea9cfd2431) | Sep 02, 2024 |
| Toshiba       | Satellite P200D             | Notebook    | [ee90ede472](https://linux-hardware.org/?probe=ee90ede472) | Sep 02, 2024 |
| ASUSTek       | Q551LNB                     | Notebook    | [1b15832563](https://linux-hardware.org/?probe=1b15832563) | Sep 02, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7ce9667960](https://linux-hardware.org/?probe=7ce9667960) | Sep 02, 2024 |
| HP            | ENVY dv7                    | Notebook    | [d097b50f4b](https://linux-hardware.org/?probe=d097b50f4b) | Sep 01, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [a1c10987b2](https://linux-hardware.org/?probe=a1c10987b2) | Sep 01, 2024 |
| Dell          | Vostro 5490                 | Notebook    | [93c5d6537d](https://linux-hardware.org/?probe=93c5d6537d) | Sep 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [db303fb0b8](https://linux-hardware.org/?probe=db303fb0b8) | Sep 01, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [4609e527b3](https://linux-hardware.org/?probe=4609e527b3) | Sep 01, 2024 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [ec48a70ebf](https://linux-hardware.org/?probe=ec48a70ebf) | Sep 01, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [949ce28218](https://linux-hardware.org/?probe=949ce28218) | Sep 01, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [271ff0c532](https://linux-hardware.org/?probe=271ff0c532) | Sep 01, 2024 |
| Gigabyte      | H370M D3H GSM-CF            | Desktop     | [3341372848](https://linux-hardware.org/?probe=3341372848) | Aug 31, 2024 |
| ASRock        | B450 Gaming K4              | Desktop     | [1f76825972](https://linux-hardware.org/?probe=1f76825972) | Aug 31, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [975150d0fd](https://linux-hardware.org/?probe=975150d0fd) | Aug 31, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | Notebook    | [10ffbf2041](https://linux-hardware.org/?probe=10ffbf2041) | Aug 31, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [0515980bed](https://linux-hardware.org/?probe=0515980bed) | Aug 31, 2024 |
| Dell          | 0RK936                      | Desktop     | [eaa47d3a8d](https://linux-hardware.org/?probe=eaa47d3a8d) | Aug 30, 2024 |
| Pegatron      | 2AD3                        | Desktop     | [89dfc9f55e](https://linux-hardware.org/?probe=89dfc9f55e) | Aug 30, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [4c473e9fe3](https://linux-hardware.org/?probe=4c473e9fe3) | Aug 30, 2024 |
| ASUSTek       | H81M-E                      | Desktop     | [9dec794b7f](https://linux-hardware.org/?probe=9dec794b7f) | Aug 30, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [1275536428](https://linux-hardware.org/?probe=1275536428) | Aug 30, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [1e19fc2c83](https://linux-hardware.org/?probe=1e19fc2c83) | Aug 30, 2024 |
| Lenovo        | IdeaPad Y580                | Notebook    | [6173a7b633](https://linux-hardware.org/?probe=6173a7b633) | Aug 29, 2024 |
| Lenovo        | Z710 20250                  | Notebook    | [c3ff73a027](https://linux-hardware.org/?probe=c3ff73a027) | Aug 29, 2024 |
| Dell          | G15 Special Edition 5521    | Notebook    | [c48740cc71](https://linux-hardware.org/?probe=c48740cc71) | Aug 29, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e5c85f2d04](https://linux-hardware.org/?probe=e5c85f2d04) | Aug 29, 2024 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [a65838a8cd](https://linux-hardware.org/?probe=a65838a8cd) | Aug 29, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pop!_OS 22.04 | 5621      | 45.03%  |
| Pop!_OS 20.04 | 2138      | 17.13%  |
| Pop!_OS 21.04 | 1808      | 14.48%  |
| Pop!_OS 20.10 | 1653      | 13.24%  |
| Pop!_OS 21.10 | 1114      | 8.92%   |
| Pop!_OS 24.04 | 74        | 0.59%   |
| Pop!_OS 19.10 | 47        | 0.38%   |
| Pop!_OS 19.04 | 12        | 0.1%    |
| Pop!_OS 18.04 | 11        | 0.09%   |
| Pop!_OS 18.10 | 5         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Pop!_OS | 11917     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 6.9.3-76060903-generic              | 1069      | 7.84%   |
| 6.2.6-76060206-generic              | 844       | 6.19%   |
| 5.11.0-7620-generic                 | 839       | 6.15%   |
| 5.8.0-7630-generic                  | 739       | 5.42%   |
| 5.4.0-7634-generic                  | 668       | 4.9%    |
| 5.13.0-7614-generic                 | 497       | 3.65%   |
| 6.0.12-76060006-generic             | 484       | 3.55%   |
| 5.8.0-7642-generic                  | 484       | 3.55%   |
| 5.4.0-7642-generic                  | 466       | 3.42%   |
| 5.17.5-76051705-generic             | 465       | 3.41%   |
| 6.8.0-76060800daily20240311-generic | 461       | 3.38%   |
| 5.19.0-76051900-generic             | 451       | 3.31%   |
| 5.11.0-7614-generic                 | 442       | 3.24%   |
| 5.13.0-7620-generic                 | 411       | 3.01%   |
| 6.6.10-76060610-generic             | 322       | 2.36%   |
| 6.5.6-76060506-generic              | 312       | 2.29%   |
| 6.0.6-76060006-generic              | 303       | 2.22%   |
| 6.4.6-76060406-generic              | 301       | 2.21%   |
| 5.15.15-76051515-generic            | 280       | 2.05%   |
| 5.16.11-76051611-generic            | 264       | 1.94%   |
| 5.15.5-76051505-generic             | 238       | 1.75%   |
| 6.6.6-76060606-generic              | 234       | 1.72%   |
| 5.11.0-7612-generic                 | 224       | 1.64%   |
| 5.18.10-76051810-generic            | 216       | 1.58%   |
| 5.8.0-7625-generic                  | 197       | 1.45%   |
| 5.17.15-76051715-generic            | 190       | 1.39%   |
| 5.16.19-76051619-generic            | 180       | 1.32%   |
| 5.11.0-7633-generic                 | 179       | 1.31%   |
| 5.15.8-76051508-generic             | 169       | 1.24%   |
| 5.16.15-76051615-generic            | 151       | 1.11%   |
| 5.4.0-7626-generic                  | 144       | 1.06%   |
| 6.5.4-76060504-generic              | 132       | 0.97%   |
| 6.2.0-76060200-generic              | 123       | 0.9%    |
| 5.15.11-76051511-generic            | 117       | 0.86%   |
| 6.0.2-76060002-generic              | 92        | 0.67%   |
| 6.1.11-76060111-generic             | 91        | 0.67%   |
| 5.15.23-76051523-generic            | 91        | 0.67%   |
| 5.4.0-7625-generic                  | 74        | 0.54%   |
| 5.4.0-7629-generic                  | 62        | 0.45%   |
| 5.19.16-76051916-generic            | 43        | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 1627      | 12.12%  |
| 5.4.0   | 1373      | 10.23%  |
| 5.8.0   | 1360      | 10.13%  |
| 6.9.3   | 1070      | 7.97%   |
| 5.13.0  | 910       | 6.78%   |
| 6.2.6   | 845       | 6.29%   |
| 6.0.12  | 500       | 3.72%   |
| 5.17.5  | 468       | 3.49%   |
| 6.8.0   | 463       | 3.45%   |
| 5.19.0  | 455       | 3.39%   |
| 6.6.10  | 322       | 2.4%    |
| 6.5.6   | 312       | 2.32%   |
| 6.0.6   | 304       | 2.26%   |
| 6.4.6   | 301       | 2.24%   |
| 5.15.15 | 281       | 2.09%   |
| 5.16.11 | 264       | 1.97%   |
| 5.15.5  | 238       | 1.77%   |
| 6.6.6   | 234       | 1.74%   |
| 5.18.10 | 216       | 1.61%   |
| 5.17.15 | 190       | 1.42%   |
| 5.16.19 | 180       | 1.34%   |
| 5.15.8  | 169       | 1.26%   |
| 5.16.15 | 151       | 1.12%   |
| 6.5.4   | 132       | 0.98%   |
| 6.2.0   | 124       | 0.92%   |
| 5.15.11 | 117       | 0.87%   |
| 6.0.2   | 95        | 0.71%   |
| 6.1.11  | 92        | 0.69%   |
| 5.15.23 | 91        | 0.68%   |
| 5.3.0   | 51        | 0.38%   |
| 5.19.16 | 43        | 0.32%   |
| 6.0.3   | 40        | 0.3%    |
| 5.15.0  | 16        | 0.12%   |
| 5.0.0   | 12        | 0.09%   |
| 5.8.5   | 8         | 0.06%   |
| 5.7.0   | 8         | 0.06%   |
| 5.8.12  | 7         | 0.05%   |
| 4.18.0  | 7         | 0.05%   |
| 6.1.0   | 6         | 0.04%   |
| 5.13.12 | 6         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 1637      | 12.32%  |
| 5.8     | 1397      | 10.51%  |
| 5.4     | 1377      | 10.36%  |
| 6.9     | 1073      | 8.08%   |
| 6.2     | 967       | 7.28%   |
| 5.13    | 930       | 7%      |
| 6.0     | 917       | 6.9%    |
| 5.15    | 908       | 6.83%   |
| 5.17    | 658       | 4.95%   |
| 5.16    | 586       | 4.41%   |
| 6.6     | 544       | 4.09%   |
| 5.19    | 500       | 3.76%   |
| 6.8     | 468       | 3.52%   |
| 6.5     | 450       | 3.39%   |
| 6.4     | 309       | 2.33%   |
| 5.18    | 223       | 1.68%   |
| 6.1     | 109       | 0.82%   |
| 5.3     | 51        | 0.38%   |
| 5.10    | 28        | 0.21%   |
| 5.7     | 27        | 0.2%    |
| 5.12    | 19        | 0.14%   |
| 6.3     | 18        | 0.14%   |
| 5.14    | 16        | 0.12%   |
| 5.9     | 15        | 0.11%   |
| 5.6     | 15        | 0.11%   |
| 5.0     | 12        | 0.09%   |
| 4.18    | 8         | 0.06%   |
| 6.10    | 7         | 0.05%   |
| 6.7     | 5         | 0.04%   |
| 6.11    | 5         | 0.04%   |
| 6.12    | 3         | 0.02%   |
| 4.15    | 3         | 0.02%   |
| 5.1     | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 11895     | 99.82%  |
| aarch64 | 22        | 0.18%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 11478     | 95.65%  |
| KDE5            | 121       | 1.01%   |
| COSMIC          | 87        | 0.73%   |
| Unknown         | 80        | 0.67%   |
| KDE             | 60        | 0.5%    |
| X-Cinnamon      | 48        | 0.4%    |
| XFCE            | 21        | 0.18%   |
| MATE            | 21        | 0.18%   |
| GNOME Flashback | 20        | 0.17%   |
| Cinnamon        | 18        | 0.15%   |
| LXQt            | 14        | 0.12%   |
| Unity           | 11        | 0.09%   |
| i3              | 6         | 0.05%   |
| Budgie          | 6         | 0.05%   |
| awesome         | 3         | 0.03%   |
| Deepin          | 2         | 0.02%   |
| UKUI            | 1         | 0.01%   |
| pop             | 1         | 0.01%   |
| Pantheon        | 1         | 0.01%   |
| GNOME Classic   | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 11430     | 95.24%  |
| Wayland | 506       | 4.22%   |
| Unknown | 44        | 0.37%   |
| Tty     | 21        | 0.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 9244      | 76.57%  |
| GDM3           | 1535      | 12.72%  |
| GDM            | 1239      | 10.26%  |
| SDDM           | 26        | 0.22%   |
| COSMIC-GREETER | 14        | 0.12%   |
| TDM            | 8         | 0.07%   |
| LightDM        | 6         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 6833      | 56.77%  |
| en_GB   | 866       | 7.19%   |
| pt_BR   | 773       | 6.42%   |
| de_DE   | 601       | 4.99%   |
| C       | 418       | 3.47%   |
| en_AU   | 322       | 2.68%   |
| en_CA   | 266       | 2.21%   |
| fr_FR   | 247       | 2.05%   |
| it_IT   | 209       | 1.74%   |
| es_ES   | 182       | 1.51%   |
| ru_RU   | 154       | 1.28%   |
| pl_PL   | 114       | 0.95%   |
| Unknown | 95        | 0.79%   |
| pt_PT   | 79        | 0.66%   |
| sv_SE   | 75        | 0.62%   |
| nl_NL   | 64        | 0.53%   |
| en_IN   | 56        | 0.47%   |
| fi_FI   | 39        | 0.32%   |
| tr_TR   | 35        | 0.29%   |
| nb_NO   | 35        | 0.29%   |
| en_ZA   | 34        | 0.28%   |
| es_MX   | 32        | 0.27%   |
| fr_CA   | 29        | 0.24%   |
| es_AR   | 29        | 0.24%   |
| en_NZ   | 29        | 0.24%   |
| en_DK   | 29        | 0.24%   |
| es_CL   | 28        | 0.23%   |
| hu_HU   | 25        | 0.21%   |
| da_DK   | 25        | 0.21%   |
| cs_CZ   | 25        | 0.21%   |
| de_CH   | 20        | 0.17%   |
| ja_JP   | 17        | 0.14%   |
| en_IE   | 17        | 0.14%   |
| de_AT   | 17        | 0.14%   |
| sk_SK   | 16        | 0.13%   |
| zh_TW   | 14        | 0.12%   |
| nl_BE   | 14        | 0.12%   |
| zh_CN   | 13        | 0.11%   |
| hr_HR   | 12        | 0.1%    |
| fr_CH   | 11        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 8849      | 73.21%  |
| EFI  | 3238      | 26.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 11417     | 95.41%  |
| Btrfs   | 283       | 2.37%   |
| Overlay | 206       | 1.72%   |
| Xfs     | 35        | 0.29%   |
| Unknown | 14        | 0.12%   |
| Zfs     | 9         | 0.08%   |
| Tmpfs   | 1         | 0.01%   |
| Ext2    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 9179      | 76.22%  |
| GPT     | 2615      | 21.71%  |
| MBR     | 249       | 2.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 11601     | 96.93%  |
| Yes       | 368       | 3.07%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 10796     | 90.03%  |
| Yes       | 1195      | 9.97%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 2109      | 17.7%   |
| Lenovo                  | 1641      | 13.77%  |
| Dell                    | 1515      | 12.71%  |
| Hewlett-Packard         | 1297      | 10.88%  |
| MSI                     | 924       | 7.75%   |
| Gigabyte Technology     | 877       | 7.36%   |
| Acer                    | 558       | 4.68%   |
| Apple                   | 545       | 4.57%   |
| ASRock                  | 427       | 3.58%   |
| System76                | 281       | 2.36%   |
| Intel                   | 159       | 1.33%   |
| Toshiba                 | 119       | 1%      |
| Samsung Electronics     | 116       | 0.97%   |
| HUAWEI                  | 91        | 0.76%   |
| Alienware               | 76        | 0.64%   |
| Microsoft               | 69        | 0.58%   |
| Notebook                | 62        | 0.52%   |
| Fujitsu                 | 59        | 0.5%    |
| Unknown                 | 58        | 0.49%   |
| Sony                    | 55        | 0.46%   |
| Google                  | 54        | 0.45%   |
| Positivo                | 46        | 0.39%   |
| Pegatron                | 32        | 0.27%   |
| Razer                   | 28        | 0.23%   |
| Biostar                 | 27        | 0.23%   |
| Medion                  | 26        | 0.22%   |
| Supermicro              | 23        | 0.19%   |
| Framework               | 23        | 0.19%   |
| Raspberry Pi Foundation | 22        | 0.18%   |
| PC Specialist           | 21        | 0.18%   |
| Timi                    | 20        | 0.17%   |
| LG Electronics          | 20        | 0.17%   |
| Foxconn                 | 20        | 0.17%   |
| AZW                     | 19        | 0.16%   |
| ECS                     | 16        | 0.13%   |
| Packard Bell            | 15        | 0.13%   |
| TUXEDO                  | 14        | 0.12%   |
| Huanan                  | 14        | 0.12%   |
| Gateway                 | 14        | 0.12%   |
| BESSTAR Tech            | 14        | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ASUS All Series              | 108       | 0.91%   |
| Unknown                      | 77        | 0.65%   |
| System76 Oryx Pro            | 57        | 0.48%   |
| ASUS TUF Gaming X570-PLUS    | 50        | 0.42%   |
| System76 Lemur Pro           | 46        | 0.39%   |
| MSI MS-7C02                  | 37        | 0.31%   |
| Apple MacBookPro9,2          | 37        | 0.31%   |
| Dell XPS 15 7590             | 36        | 0.3%    |
| System76 Gazelle             | 35        | 0.29%   |
| ASUS ROG STRIX B550-F GAMING | 35        | 0.29%   |
| Gigabyte B450M DS3H          | 34        | 0.29%   |
| MSI MS-7C37                  | 33        | 0.28%   |
| MSI MS-7B86                  | 32        | 0.27%   |
| ASUS ROG STRIX B450-F GAMING | 31        | 0.26%   |
| Apple MacBookPro8,1          | 31        | 0.26%   |
| Apple MacBookAir7,2          | 28        | 0.23%   |
| Apple MacBookPro12,1         | 27        | 0.23%   |
| System76 Galago Pro          | 25        | 0.21%   |
| Dell OptiPlex 9020           | 25        | 0.21%   |
| ASUS PRIME B450M-A           | 25        | 0.21%   |
| System76 Darter Pro          | 24        | 0.2%    |
| HP Notebook                  | 24        | 0.2%    |
| Gigabyte X570 AORUS ELITE    | 23        | 0.19%   |
| Dell OptiPlex 7010           | 23        | 0.19%   |
| System76 Thelio              | 22        | 0.18%   |
| Dell XPS 15 9500             | 22        | 0.18%   |
| Apple MacBookAir6,2          | 22        | 0.18%   |
| HP Pavilion Notebook         | 20        | 0.17%   |
| MSI MS-7C91                  | 19        | 0.16%   |
| HP Pavilion 15               | 19        | 0.16%   |
| Gigabyte X570 AORUS MASTER   | 19        | 0.16%   |
| Gigabyte A320M-S2H           | 19        | 0.16%   |
| Apple MacBookPro11,1         | 19        | 0.16%   |
| HP Pavilion dv6              | 18        | 0.15%   |
| Dell XPS 15 9570             | 18        | 0.15%   |
| ASRock B450M Steel Legend    | 18        | 0.15%   |
| ASRock B450M Pro4            | 18        | 0.15%   |
| Apple MacBookPro11,3         | 18        | 0.15%   |
| MSI MS-7C56                  | 17        | 0.14%   |
| Apple MacBookPro7,1          | 17        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 696       | 5.84%   |
| ASUS ROG           | 432       | 3.63%   |
| Dell Inspiron      | 411       | 3.45%   |
| Lenovo IdeaPad     | 373       | 3.13%   |
| Acer Aspire        | 366       | 3.07%   |
| Dell Latitude      | 304       | 2.55%   |
| Dell XPS           | 260       | 2.18%   |
| ASUS PRIME         | 253       | 2.12%   |
| HP Pavilion        | 235       | 1.97%   |
| ASUS TUF           | 204       | 1.71%   |
| Dell OptiPlex      | 185       | 1.55%   |
| HP EliteBook       | 159       | 1.33%   |
| ASUS VivoBook      | 150       | 1.26%   |
| Dell Precision     | 146       | 1.23%   |
| HP Laptop          | 133       | 1.12%   |
| Lenovo Legion      | 120       | 1.01%   |
| ASUS All           | 108       | 0.91%   |
| Toshiba Satellite  | 102       | 0.86%   |
| HP ProBook         | 102       | 0.86%   |
| Lenovo Yoga        | 96        | 0.81%   |
| HP ENVY            | 90        | 0.76%   |
| Gigabyte X570      | 89        | 0.75%   |
| HP Compaq          | 87        | 0.73%   |
| ASUS ASUS          | 86        | 0.72%   |
| Dell Vostro        | 79        | 0.66%   |
| Unknown            | 77        | 0.65%   |
| Acer Nitro         | 74        | 0.62%   |
| Lenovo ThinkCentre | 71        | 0.6%    |
| Microsoft Surface  | 69        | 0.58%   |
| HP OMEN            | 59        | 0.5%    |
| Gigabyte B450      | 59        | 0.5%    |
| Apple MacBookPro11 | 58        | 0.49%   |
| System76 Oryx      | 57        | 0.48%   |
| ASUS Zenbook       | 55        | 0.46%   |
| Gigabyte B450M     | 52        | 0.44%   |
| System76 Lemur     | 50        | 0.42%   |
| Acer Swift         | 47        | 0.39%   |
| Apple MacBookPro8  | 46        | 0.39%   |
| Gigabyte B550      | 45        | 0.38%   |
| Apple MacBookPro9  | 45        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1359      | 11.4%   |
| 2020    | 1353      | 11.35%  |
| 2018    | 1289      | 10.82%  |
| 2021    | 1069      | 8.97%   |
| 2012    | 839       | 7.04%   |
| 2017    | 787       | 6.6%    |
| 2013    | 721       | 6.05%   |
| 2011    | 636       | 5.34%   |
| 2014    | 620       | 5.2%    |
| 2022    | 606       | 5.09%   |
| 2015    | 565       | 4.74%   |
| 2016    | 544       | 4.56%   |
| 2010    | 391       | 3.28%   |
| 2023    | 323       | 2.71%   |
| 2009    | 300       | 2.52%   |
| 2008    | 243       | 2.04%   |
| 2007    | 139       | 1.17%   |
| 2024    | 84        | 0.7%    |
| 2006    | 24        | 0.2%    |
| Unknown | 22        | 0.18%   |
| 2005    | 2         | 0.02%   |
| 2004    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 6593      | 55.32%  |
| Desktop        | 4457      | 37.4%   |
| Convertible    | 335       | 2.81%   |
| Mini pc        | 168       | 1.41%   |
| All in one     | 156       | 1.31%   |
| Tablet         | 142       | 1.19%   |
| Server         | 42        | 0.35%   |
| System on chip | 23        | 0.19%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 11909     | 99.92%  |
| Enabled  | 10        | 0.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 11708     | 98.25%  |
| Yes  | 209       | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 3125      | 25.86%  |
| 4.01-8.0        | 2508      | 20.75%  |
| 8.01-16.0       | 2202      | 18.22%  |
| 32.01-64.0      | 1853      | 15.33%  |
| 3.01-4.0        | 1316      | 10.89%  |
| 64.01-256.0     | 565       | 4.68%   |
| 24.01-32.0      | 318       | 2.63%   |
| 1.01-2.0        | 128       | 1.06%   |
| 2.01-3.0        | 57        | 0.47%   |
| More than 256.0 | 12        | 0.1%    |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 3494      | 26.7%   |
| 2.01-3.0    | 3398      | 25.97%  |
| 1.01-2.0    | 2499      | 19.1%   |
| 3.01-4.0    | 2429      | 18.56%  |
| 8.01-16.0   | 1029      | 7.86%   |
| 16.01-24.0  | 143       | 1.09%   |
| 24.01-32.0  | 40        | 0.31%   |
| 32.01-64.0  | 24        | 0.18%   |
| 0.51-1.0    | 23        | 0.18%   |
| 64.01-256.0 | 5         | 0.04%   |
| 0.01-0.5    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 6824      | 55.84%  |
| 2      | 3304      | 27.04%  |
| 3      | 1083      | 8.86%   |
| 4      | 522       | 4.27%   |
| 5      | 226       | 1.85%   |
| 6      | 105       | 0.86%   |
| 0      | 64        | 0.52%   |
| 7      | 43        | 0.35%   |
| 8      | 13        | 0.11%   |
| 9      | 11        | 0.09%   |
| 11     | 10        | 0.08%   |
| 12     | 3         | 0.02%   |
| 10     | 3         | 0.02%   |
| 14     | 2         | 0.02%   |
| 13     | 2         | 0.02%   |
| 26     | 1         | 0.01%   |
| 23     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |
| 20     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 8781      | 73.27%  |
| Yes       | 3204      | 26.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10084     | 84.26%  |
| No        | 1884      | 15.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9673      | 80.81%  |
| No        | 2297      | 19.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8306      | 69.06%  |
| No        | 3722      | 30.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 3570      | 29.8%   |
| Brazil       | 1056      | 8.82%   |
| Germany      | 844       | 7.05%   |
| UK           | 590       | 4.93%   |
| Canada       | 532       | 4.44%   |
| Australia    | 378       | 3.16%   |
| Italy        | 350       | 2.92%   |
| India        | 333       | 2.78%   |
| France       | 317       | 2.65%   |
| Netherlands  | 260       | 2.17%   |
| Russia       | 216       | 1.8%    |
| Poland       | 207       | 1.73%   |
| Sweden       | 202       | 1.69%   |
| Spain        | 178       | 1.49%   |
| Mexico       | 132       | 1.1%    |
| Portugal     | 131       | 1.09%   |
| Switzerland  | 121       | 1.01%   |
| Finland      | 111       | 0.93%   |
| Norway       | 108       | 0.9%    |
| South Africa | 105       | 0.88%   |
| Romania      | 101       | 0.84%   |
| Austria      | 98        | 0.82%   |
| Belgium      | 87        | 0.73%   |
| Denmark      | 85        | 0.71%   |
| New Zealand  | 84        | 0.7%    |
| Philippines  | 82        | 0.68%   |
| Turkey       | 79        | 0.66%   |
| Indonesia    | 77        | 0.64%   |
| Czechia      | 77        | 0.64%   |
| Argentina    | 77        | 0.64%   |
| Greece       | 75        | 0.63%   |
| Hungary      | 68        | 0.57%   |
| Chile        | 64        | 0.53%   |
| Japan        | 54        | 0.45%   |
| Bulgaria     | 54        | 0.45%   |
| Ireland      | 48        | 0.4%    |
| Serbia       | 43        | 0.36%   |
| Malaysia     | 43        | 0.36%   |
| Croatia      | 40        | 0.33%   |
| Slovakia     | 38        | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 130       | 1.03%   |
| Sydney         | 100       | 0.8%    |
| Melbourne      | 88        | 0.7%    |
| Berlin         | 74        | 0.59%   |
| Brisbane       | 67        | 0.53%   |
| Milan          | 65        | 0.52%   |
| Rio de Janeiro | 64        | 0.51%   |
| Helsinki       | 64        | 0.51%   |
| Warsaw         | 57        | 0.45%   |
| Vienna         | 57        | 0.45%   |
| New York       | 53        | 0.42%   |
| Moscow         | 53        | 0.42%   |
| Chicago        | 52        | 0.41%   |
| Dallas         | 49        | 0.39%   |
| Toronto        | 47        | 0.37%   |
| Denver         | 47        | 0.37%   |
| Bengaluru      | 46        | 0.37%   |
| London         | 45        | 0.36%   |
| Amsterdam      | 44        | 0.35%   |
| Seattle        | 43        | 0.34%   |
| Rome           | 43        | 0.34%   |
| Auckland       | 43        | 0.34%   |
| Paris          | 42        | 0.33%   |
| Montreal       | 39        | 0.31%   |
| Madrid         | 38        | 0.3%    |
| Los Angeles    | 38        | 0.3%    |
| Bucharest      | 36        | 0.29%   |
| Istanbul       | 35        | 0.28%   |
| Athens         | 35        | 0.28%   |
| Stockholm      | 34        | 0.27%   |
| Sofia          | 34        | 0.27%   |
| Miami          | 34        | 0.27%   |
| Calgary        | 34        | 0.27%   |
| Zurich         | 33        | 0.26%   |
| Lisbon         | 33        | 0.26%   |
| Johannesburg   | 33        | 0.26%   |
| Budapest       | 33        | 0.26%   |
| Atlanta        | 33        | 0.26%   |
| Hamburg        | 32        | 0.25%   |
| Edmonton       | 32        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 3384      | 5216   | 18.39%  |
| WDC                         | 2268      | 3190   | 12.33%  |
| Seagate                     | 2241      | 3285   | 12.18%  |
| SanDisk                     | 1277      | 1720   | 6.94%   |
| Kingston                    | 1000      | 1274   | 5.44%   |
| Toshiba                     | 907       | 1131   | 4.93%   |
| Crucial                     | 743       | 1005   | 4.04%   |
| SK hynix                    | 559       | 705    | 3.04%   |
| Unknown                     | 554       | 730    | 3.01%   |
| Intel                       | 508       | 679    | 2.76%   |
| Micron Technology           | 353       | 419    | 1.92%   |
| Hitachi                     | 345       | 454    | 1.88%   |
| HGST                        | 289       | 345    | 1.57%   |
| Apple                       | 270       | 318    | 1.47%   |
| A-DATA Technology           | 260       | 324    | 1.41%   |
| Phison                      | 257       | 360    | 1.4%    |
| Micron/Crucial Technology   | 211       | 289    | 1.15%   |
| China                       | 178       | 240    | 0.97%   |
| Silicon Motion              | 169       | 221    | 0.92%   |
| PNY                         | 165       | 206    | 0.9%    |
| Phison Electronics          | 152       | 225    | 0.83%   |
| KIOXIA                      | 138       | 161    | 0.75%   |
| Kingston Technology Company | 102       | 127    | 0.55%   |
| SPCC                        | 90        | 127    | 0.49%   |
| LITEON                      | 76        | 91     | 0.41%   |
| Team                        | 74        | 87     | 0.4%    |
| OCZ                         | 68        | 88     | 0.37%   |
| Transcend                   | 64        | 75     | 0.35%   |
| Realtek Semiconductor       | 64        | 73     | 0.35%   |
| Corsair                     | 58        | 74     | 0.32%   |
| Patriot                     | 57        | 80     | 0.31%   |
| XPG                         | 55        | 74     | 0.3%    |
| ADATA Technology            | 55        | 68     | 0.3%    |
| Hewlett-Packard             | 51        | 70     | 0.28%   |
| JMicron Technology          | 48        | 72     | 0.26%   |
| Intenso                     | 48        | 62     | 0.26%   |
| Unknown                     | 48        | 54     | 0.26%   |
| LITEONIT                    | 46        | 67     | 0.25%   |
| ASMT                        | 46        | 56     | 0.25%   |
| Netac                       | 41        | 51     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 247       | 1.21%   |
| Kingston SA400S37240G 240GB SSD                      | 243       | 1.19%   |
| Samsung NVMe SSD Drive 1TB                           | 198       | 0.97%   |
| Samsung NVMe SSD Drive 500GB                         | 178       | 0.87%   |
| Samsung SSD 850 EVO 250GB                            | 158       | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 153       | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                       | 151       | 0.74%   |
| Samsung SSD 860 EVO 500GB                            | 145       | 0.71%   |
| SanDisk NVMe SSD Drive 1TB                           | 137       | 0.67%   |
| Samsung SSD 850 EVO 500GB                            | 137       | 0.67%   |
| Samsung SSD 860 EVO 1TB                              | 127       | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB                       | 123       | 0.6%    |
| Unknown MMC Card  64GB                               | 121       | 0.59%   |
| Kingston SA400S37480G 480GB SSD                      | 121       | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB                       | 120       | 0.59%   |
| Samsung NVMe SSD Drive 512GB                         | 118       | 0.58%   |
| Kingston SA400S37120G 120GB SSD                      | 112       | 0.55%   |
| Crucial CT1000MX500SSD1 1TB                          | 108       | 0.53%   |
| SanDisk NVMe SSD Drive 500GB                         | 101       | 0.5%    |
| HGST HTS721010A9E630 1TB                             | 101       | 0.5%    |
| Crucial CT500MX500SSD1 500GB                         | 97        | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 94        | 0.46%   |
| Toshiba MQ01ABD100 1TB                               | 92        | 0.45%   |
| Samsung NVMe SSD Drive 256GB                         | 91        | 0.45%   |
| Seagate ST500DM002-1BD142 500GB                      | 88        | 0.43%   |
| Unknown MMC Card  32GB                               | 85        | 0.42%   |
| SanDisk NVMe SSD Drive 512GB                         | 79        | 0.39%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 79        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 78        | 0.38%   |
| Crucial CT240BX500SSD1 240GB                         | 76        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB                         | 75        | 0.37%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB               | 74        | 0.36%   |
| Unknown MMC Card  128GB                              | 70        | 0.34%   |
| Intel NVMe SSD Drive 512GB                           | 69        | 0.34%   |
| Seagate Expansion 1TB                                | 66        | 0.32%   |
| Samsung SSD 860 EVO 250GB                            | 65        | 0.32%   |
| Toshiba MQ04ABF100 1TB                               | 63        | 0.31%   |
| Toshiba DT01ACA100 1TB                               | 63        | 0.31%   |
| Unknown SD/MMC/MS PRO 128GB                          | 61        | 0.3%    |
| SK hynix NVMe SSD Drive 512GB                        | 61        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2167      | 3118   | 38.25%  |
| WDC                 | 1702      | 2404   | 30.04%  |
| Toshiba             | 637       | 784    | 11.24%  |
| Hitachi             | 345       | 454    | 6.09%   |
| HGST                | 289       | 345    | 5.1%    |
| Samsung Electronics | 174       | 207    | 3.07%   |
| Apple               | 72        | 86     | 1.27%   |
| Unknown             | 64        | 77     | 1.13%   |
| JMicron Technology  | 29        | 47     | 0.51%   |
| SABRENT             | 27        | 33     | 0.48%   |
| Maxtor              | 27        | 28     | 0.48%   |
| Fujitsu             | 26        | 31     | 0.46%   |
| ASMT                | 23        | 30     | 0.41%   |
| TO Exter            | 15        | 18     | 0.26%   |
| Hewlett-Packard     | 13        | 25     | 0.23%   |
| External            | 10        | 10     | 0.18%   |
| MaxDigital          | 4         | 4      | 0.07%   |
| USB                 | 3         | 4      | 0.05%   |
| LaCie               | 3         | 5      | 0.05%   |
| Intenso             | 3         | 8      | 0.05%   |
| ExcelStor           | 3         | 3      | 0.05%   |
| WD MediaMax         | 2         | 8      | 0.04%   |
| RSH-339             | 2         | 2      | 0.04%   |
| Magnetic Data       | 2         | 2      | 0.04%   |
| Inateck             | 2         | 2      | 0.04%   |
| HGST HTS            | 2         | 2      | 0.04%   |
| ASMedia             | 2         | 2      | 0.04%   |
| Unknown             | 2         | 3      | 0.04%   |
| XrayDisk            | 1         | 1      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| OEM                 | 1         | 1      | 0.02%   |
| Min Yi U            | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| KESU                | 1         | 1      | 0.02%   |
| HPE                 | 1         | 1      | 0.02%   |
| HGST HDN            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Glyph               | 1         | 2      | 0.02%   |
| DELLBOSS            | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1509      | 2213   | 24.41%  |
| Kingston            | 792       | 987    | 12.81%  |
| Crucial             | 662       | 883    | 10.71%  |
| SanDisk             | 550       | 708    | 8.9%    |
| WDC                 | 400       | 505    | 6.47%   |
| A-DATA Technology   | 199       | 250    | 3.22%   |
| China               | 176       | 238    | 2.85%   |
| Apple               | 169       | 190    | 2.73%   |
| PNY                 | 159       | 199    | 2.57%   |
| Intel               | 128       | 161    | 2.07%   |
| SK hynix            | 110       | 135    | 1.78%   |
| Micron Technology   | 100       | 112    | 1.62%   |
| Toshiba             | 84        | 97     | 1.36%   |
| SPCC                | 76        | 96     | 1.23%   |
| LITEON              | 70        | 85     | 1.13%   |
| OCZ                 | 67        | 84     | 1.08%   |
| Transcend           | 61        | 72     | 0.99%   |
| Team                | 58        | 70     | 0.94%   |
| Patriot             | 55        | 77     | 0.89%   |
| LITEONIT            | 46        | 67     | 0.74%   |
| Corsair             | 43        | 52     | 0.7%    |
| KingSpec            | 39        | 45     | 0.63%   |
| Seagate             | 38        | 54     | 0.61%   |
| Netac               | 35        | 42     | 0.57%   |
| Intenso             | 34        | 42     | 0.55%   |
| Lexar               | 31        | 41     | 0.5%    |
| Hewlett-Packard     | 29        | 37     | 0.47%   |
| Apacer              | 27        | 36     | 0.44%   |
| GOODRAM             | 19        | 21     | 0.31%   |
| KingDian            | 18        | 30     | 0.29%   |
| Gigabyte Technology | 18        | 21     | 0.29%   |
| Plextor             | 15        | 20     | 0.24%   |
| Mushkin             | 14        | 17     | 0.23%   |
| Dogfish             | 14        | 22     | 0.23%   |
| Verbatim            | 13        | 18     | 0.21%   |
| OWC                 | 11        | 21     | 0.18%   |
| KIOXIA-EXCERIA      | 10        | 11     | 0.16%   |
| Unknown             | 10        | 10     | 0.16%   |
| Maxtor              | 8         | 8      | 0.13%   |
| Fanxiang            | 8         | 12     | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 5472      | 8366   | 33.42%  |
| SSD     | 5342      | 8128   | 32.63%  |
| HDD     | 4823      | 7762   | 29.46%  |
| MMC     | 423       | 522    | 2.58%   |
| Unknown | 312       | 469    | 1.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 8038      | 15210  | 54.77%  |
| NVMe | 5461      | 8316   | 37.21%  |
| SAS  | 755       | 1199   | 5.14%   |
| MMC  | 423       | 522    | 2.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5769      | 8650   | 53.89%  |
| 0.51-1.0   | 3224      | 4537   | 30.12%  |
| 1.01-2.0   | 998       | 1483   | 9.32%   |
| 3.01-4.0   | 309       | 520    | 2.89%   |
| 4.01-10.0  | 190       | 344    | 1.77%   |
| 2.01-3.0   | 172       | 266    | 1.61%   |
| 10.01-20.0 | 43        | 90     | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3555      | 28.61%  |
| 251-500        | 3098      | 24.93%  |
| 501-1000       | 2402      | 19.33%  |
| 1001-2000      | 1206      | 9.71%   |
| More than 3000 | 642       | 5.17%   |
| 51-100         | 519       | 4.18%   |
| 2001-3000      | 404       | 3.25%   |
| 1-20           | 278       | 2.24%   |
| 21-50          | 238       | 1.92%   |
| Unknown        | 83        | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 4439      | 34.03%  |
| 21-50          | 2719      | 20.84%  |
| 101-250        | 1722      | 13.2%   |
| 51-100         | 1550      | 11.88%  |
| 251-500        | 1040      | 7.97%   |
| 501-1000       | 721       | 5.53%   |
| 1001-2000      | 399       | 3.06%   |
| More than 3000 | 228       | 1.75%   |
| 2001-3000      | 143       | 1.1%    |
| Unknown        | 83        | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 7         | 7      | 1.85%   |
| Seagate ST1000LM035-1RK172 1TB        | 6         | 6      | 1.59%   |
| HGST HTS725050A7E630 500GB            | 6         | 9      | 1.59%   |
| HGST HTS721010A9E630 1TB              | 6         | 6      | 1.59%   |
| HGST HTS541010A9E680 1TB              | 6         | 6      | 1.59%   |
| Seagate ST500LT012-9WS142 500GB       | 5         | 6      | 1.32%   |
| Seagate ST1000LX015-1U7172 1TB        | 5         | 5      | 1.32%   |
| SK hynix PC711 HFS001TDE9X073N 1TB    | 4         | 4      | 1.06%   |
| Seagate ST500DM002-1BD142 500GB       | 4         | 4      | 1.06%   |
| Crucial CT525MX300SSD1 528GB          | 4         | 4      | 1.06%   |
| WDC WD10JPCX-24UE4T0 1TB              | 3         | 3      | 0.79%   |
| WDC WD10EZEX-60WN4A0 1TB              | 3         | 3      | 0.79%   |
| Toshiba MQ01ABD100 1TB                | 3         | 3      | 0.79%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 0.79%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 0.79%   |
| Seagate ST3500418AS 500GB             | 3         | 3      | 0.79%   |
| Seagate ST1500DL003-9VT16L 1TB        | 3         | 5      | 0.79%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 3      | 0.79%   |
| Samsung Electronics HD502HI 500GB     | 3         | 5      | 0.79%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 5      | 0.79%   |
| Kingston SA400S37120G 120GB SSD       | 3         | 5      | 0.79%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 5      | 0.79%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 0.79%   |
| Crucial CT1000P1SSD8 1TB              | 3         | 3      | 0.79%   |
| WDC WD3200AAKS-75B3A0 320GB           | 2         | 2      | 0.53%   |
| WDC WD10JPVX-60JC3T0 1TB              | 2         | 2      | 0.53%   |
| WDC WD10EZEX-00BN5A0 1TB              | 2         | 3      | 0.53%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2         | 2      | 0.53%   |
| Toshiba MK7559GSXP 752GB              | 2         | 2      | 0.53%   |
| Toshiba HDWD110 1TB                   | 2         | 2      | 0.53%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 2         | 2      | 0.53%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 0.53%   |
| Seagate ST9750420AS 752GB             | 2         | 2      | 0.53%   |
| Seagate ST9500325AS 500GB             | 2         | 3      | 0.53%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 0.53%   |
| Seagate ST8000DM004-2CX188 8TB        | 2         | 2      | 0.53%   |
| Seagate ST3750528AS 752GB             | 2         | 2      | 0.53%   |
| Seagate ST3250310AS 250GB             | 2         | 4      | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 2      | 0.53%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 86        | 100    | 23.31%  |
| WDC                         | 76        | 98     | 20.6%   |
| Samsung Electronics         | 39        | 48     | 10.57%  |
| Toshiba                     | 25        | 26     | 6.78%   |
| HGST                        | 24        | 27     | 6.5%    |
| Kingston                    | 15        | 19     | 4.07%   |
| Crucial                     | 15        | 15     | 4.07%   |
| Hitachi                     | 14        | 17     | 3.79%   |
| SK hynix                    | 13        | 15     | 3.52%   |
| A-DATA Technology           | 10        | 10     | 2.71%   |
| Intel                       | 9         | 9      | 2.44%   |
| SanDisk                     | 8         | 8      | 2.17%   |
| Micron Technology           | 6         | 8      | 1.63%   |
| Apple                       | 4         | 4      | 1.08%   |
| China                       | 3         | 3      | 0.81%   |
| Team                        | 2         | 2      | 0.54%   |
| SPCC                        | 2         | 2      | 0.54%   |
| LITEON                      | 2         | 2      | 0.54%   |
| XPG                         | 1         | 1      | 0.27%   |
| WHALEKOM                    | 1         | 1      | 0.27%   |
| Silicon Motion              | 1         | 1      | 0.27%   |
| SABRENT                     | 1         | 1      | 0.27%   |
| S3+                         | 1         | 1      | 0.27%   |
| Plextor                     | 1         | 1      | 0.27%   |
| Maxtor                      | 1         | 1      | 0.27%   |
| Lexar                       | 1         | 1      | 0.27%   |
| Leven                       | 1         | 1      | 0.27%   |
| Kingston Technology Company | 1         | 1      | 0.27%   |
| Intenso                     | 1         | 1      | 0.27%   |
| Hewlett-Packard             | 1         | 1      | 0.27%   |
| Flashwar                    | 1         | 1      | 0.27%   |
| BAITITON                    | 1         | 1      | 0.27%   |
| ASMT                        | 1         | 1      | 0.27%   |
| Apacer                      | 1         | 1      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 86        | 100    | 36.29%  |
| WDC                 | 71        | 92     | 29.96%  |
| HGST                | 24        | 27     | 10.13%  |
| Toshiba             | 22        | 22     | 9.28%   |
| Hitachi             | 14        | 17     | 5.91%   |
| Samsung Electronics | 13        | 16     | 5.49%   |
| Apple               | 4         | 4      | 1.69%   |
| SABRENT             | 1         | 1      | 0.42%   |
| Maxtor              | 1         | 1      | 0.42%   |
| ASMT                | 1         | 1      | 0.42%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 222       | 281    | 62.54%  |
| SSD  | 90        | 103    | 25.35%  |
| NVMe | 43        | 45     | 12.11%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 12.5%   |
| Seagate ST3500418ASQ 500GB        | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 12.5%   |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 12.5%   |
| Patriot Pyro SSD 120GB            | 1         | 2      | 12.5%   |
| KingDian S400 120GB               | 1         | 2      | 12.5%   |
| Intenso JAJP600M1TB               | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 37.5%   |
| Seagate             | 2         | 2      | 25%     |
| Patriot             | 1         | 2      | 12.5%   |
| KingDian            | 1         | 2      | 12.5%   |
| Intenso             | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 9466      | 20232  | 75.49%  |
| Works    | 2723      | 4575   | 21.71%  |
| Malfunc  | 342       | 429    | 2.73%   |
| Failed   | 8         | 10     | 0.06%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7095      | 42.63%  |
| AMD                              | 2852      | 17.14%  |
| Samsung Electronics              | 2109      | 12.67%  |
| SanDisk                          | 939       | 5.64%   |
| SK hynix                         | 448       | 2.69%   |
| Phison Electronics               | 427       | 2.57%   |
| Kingston Technology Company      | 314       | 1.89%   |
| Micron/Crucial Technology        | 284       | 1.71%   |
| ASMedia Technology               | 264       | 1.59%   |
| Micron Technology                | 259       | 1.56%   |
| Toshiba America Info Systems     | 210       | 1.26%   |
| Silicon Motion                   | 197       | 1.18%   |
| Nvidia                           | 187       | 1.12%   |
| ADATA Technology                 | 149       | 0.9%    |
| Marvell Technology Group         | 147       | 0.88%   |
| KIOXIA                           | 137       | 0.82%   |
| JMicron Technology               | 107       | 0.64%   |
| Realtek Semiconductor            | 86        | 0.52%   |
| Solid State Storage Technology   | 52        | 0.31%   |
| Union Memory (Shenzhen)          | 43        | 0.26%   |
| MAXIO Technology (Hangzhou)      | 41        | 0.25%   |
| Seagate Technology               | 34        | 0.2%    |
| Broadcom / LSI                   | 34        | 0.2%    |
| Apple                            | 31        | 0.19%   |
| Shenzhen Longsys Electronics     | 28        | 0.17%   |
| LSI Logic / Symbios Logic        | 24        | 0.14%   |
| Solidigm                         | 20        | 0.12%   |
| Lite-On Technology               | 19        | 0.11%   |
| INNOGRIT                         | 15        | 0.09%   |
| VIA Technologies                 | 12        | 0.07%   |
| Silicon Integrated Systems [SiS] | 10        | 0.06%   |
| Silicon Image                    | 9         | 0.05%   |
| Lenovo                           | 9         | 0.05%   |
| Hewlett-Packard                  | 8         | 0.05%   |
| Netac Technology                 | 6         | 0.04%   |
| Adaptec                          | 6         | 0.04%   |
| Biwin Storage Technology         | 5         | 0.03%   |
| Hosin Global Electronics         | 4         | 0.02%   |
| Yangtze Memory Technologies      | 3         | 0.02%   |
| Transcend                        | 3         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1970      | 10.57%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1060      | 5.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 554       | 2.97%   |
| AMD 400 Series Chipset SATA Controller                                         | 529       | 2.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 469       | 2.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 450       | 2.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 399       | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 364       | 1.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 351       | 1.88%   |
| AMD 500 Series Chipset SATA Controller                                         | 347       | 1.86%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 315       | 1.69%   |
| Intel Volume Management Device NVMe RAID Controller                            | 307       | 1.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 297       | 1.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 267       | 1.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 263       | 1.41%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 249       | 1.34%   |
| Intel SATA Controller [RAID mode]                                              | 231       | 1.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 220       | 1.18%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 219       | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 217       | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 208       | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 191       | 1.02%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 190       | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 189       | 1.01%   |
| Phison E12 NVMe Controller                                                     | 187       | 1%      |
| Intel SSD 660P Series                                                          | 183       | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 178       | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 177       | 0.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 160       | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 159       | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 155       | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 148       | 0.79%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 147       | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 143       | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 140       | 0.75%   |
| AMD 600 Series Chipset SATA Controller                                         | 119       | 0.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 113       | 0.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 112       | 0.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 112       | 0.6%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 102       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 8688      | 53.59%  |
| NVMe | 5455      | 33.65%  |
| RAID | 1117      | 6.89%   |
| IDE  | 881       | 5.43%   |
| SAS  | 53        | 0.33%   |
| SCSI | 17        | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 8360      | 70.15%  |
| AMD    | 3536      | 29.67%  |
| ARM    | 22        | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 173       | 1.45%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 153       | 1.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 134       | 1.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 133       | 1.11%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 128       | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 125       | 1.05%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 119       | 1%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 119       | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 103       | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 101       | 0.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 94        | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 94        | 0.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 92        | 0.77%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 92        | 0.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 85        | 0.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 84        | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 84        | 0.7%    |
| AMD Ryzen 7 5800X 8-Core Processor            | 80        | 0.67%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 77        | 0.64%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 76        | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 75        | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 72        | 0.6%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 71        | 0.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 69        | 0.58%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 68        | 0.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 68        | 0.57%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 68        | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 66        | 0.55%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 66        | 0.55%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 63        | 0.53%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 63        | 0.53%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 60        | 0.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 59        | 0.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 54        | 0.45%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 54        | 0.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 53        | 0.44%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 52        | 0.44%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 52        | 0.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 52        | 0.44%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 51        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 2693      | 22.56%  |
| Intel Core i5           | 2556      | 21.41%  |
| AMD Ryzen 5             | 1119      | 9.37%   |
| Other                   | 1031      | 8.64%   |
| AMD Ryzen 7             | 976       | 8.18%   |
| Intel Core i3           | 631       | 5.29%   |
| AMD Ryzen 9             | 393       | 3.29%   |
| Intel Core 2 Duo        | 299       | 2.5%    |
| Intel Celeron           | 286       | 2.4%    |
| Intel Xeon              | 270       | 2.26%   |
| AMD FX                  | 153       | 1.28%   |
| AMD Ryzen 3             | 150       | 1.26%   |
| Intel Core i9           | 141       | 1.18%   |
| Intel Pentium           | 133       | 1.11%   |
| Intel Pentium Dual-Core | 74        | 0.62%   |
| AMD A8                  | 73        | 0.61%   |
| AMD A6                  | 73        | 0.61%   |
| AMD A10                 | 70        | 0.59%   |
| Intel Atom              | 69        | 0.58%   |
| AMD Ryzen 7 PRO         | 61        | 0.51%   |
| AMD Ryzen Threadripper  | 57        | 0.48%   |
| Intel Core 2 Quad       | 53        | 0.44%   |
| AMD A4                  | 46        | 0.39%   |
| AMD Ryzen 5 PRO         | 40        | 0.34%   |
| AMD Phenom II X4        | 40        | 0.34%   |
| AMD Athlon              | 37        | 0.31%   |
| Intel Core 2            | 35        | 0.29%   |
| AMD Athlon II X2        | 27        | 0.23%   |
| Intel Pentium Dual      | 22        | 0.18%   |
| Intel Pentium Silver    | 20        | 0.17%   |
| Intel Core              | 20        | 0.17%   |
| AMD Athlon II X4        | 20        | 0.17%   |
| Intel Genuine           | 19        | 0.16%   |
| Intel Core m3           | 18        | 0.15%   |
| AMD E                   | 17        | 0.14%   |
| AMD E1                  | 16        | 0.13%   |
| AMD Phenom II X6        | 15        | 0.13%   |
| AMD Athlon 64 X2        | 15        | 0.13%   |
| Intel Pentium Gold      | 14        | 0.12%   |
| AMD E2                  | 12        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 4243      | 35.54%  |
| 2       | 3444      | 28.84%  |
| 6       | 1706      | 14.29%  |
| 8       | 1480      | 12.4%   |
| 12      | 315       | 2.64%   |
| 16      | 205       | 1.72%   |
| 10      | 157       | 1.31%   |
| 14      | 140       | 1.17%   |
| 1       | 70        | 0.59%   |
| 3       | 62        | 0.52%   |
| 24      | 61        | 0.51%   |
| 32      | 18        | 0.15%   |
| 20      | 11        | 0.09%   |
| Unknown | 10        | 0.08%   |
| 64      | 5         | 0.04%   |
| 40      | 3         | 0.03%   |
| 36      | 2         | 0.02%   |
| 28      | 2         | 0.02%   |
| 18      | 2         | 0.02%   |
| 48      | 1         | 0.01%   |
| 9       | 1         | 0.01%   |
| 7       | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 11837     | 99.32%  |
| 2       | 71        | 0.6%    |
| Unknown | 10        | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 9352      | 78.37%  |
| 1       | 2565      | 21.5%   |
| Unknown | 10        | 0.08%   |
| 8       | 3         | 0.03%   |
| 16      | 2         | 0.02%   |
| 12      | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 11891     | 99.78%  |
| 64-bit         | 15        | 0.13%   |
| Unknown        | 11        | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8964      | 73.57%  |
| 0x906ea    | 194       | 1.59%   |
| 0x306a9    | 169       | 1.39%   |
| 0x206a7    | 148       | 1.21%   |
| 0x306c3    | 136       | 1.12%   |
| 0x806ea    | 127       | 1.04%   |
| 0x806ec    | 124       | 1.02%   |
| 0x806c1    | 118       | 0.97%   |
| 0x08701021 | 112       | 0.92%   |
| 0x406e3    | 96        | 0.79%   |
| 0x906e9    | 88        | 0.72%   |
| 0x40651    | 87        | 0.71%   |
| 0x806e9    | 81        | 0.66%   |
| 0x506e3    | 79        | 0.65%   |
| 0x0800820d | 79        | 0.65%   |
| 0x08701013 | 77        | 0.63%   |
| 0xa0652    | 75        | 0.62%   |
| 0x0a50000c | 73        | 0.6%    |
| 0x1067a    | 63        | 0.52%   |
| 0x08108109 | 59        | 0.48%   |
| 0x08600106 | 54        | 0.44%   |
| 0x08108102 | 51        | 0.42%   |
| 0x906ed    | 44        | 0.36%   |
| 0x306d4    | 44        | 0.36%   |
| 0x806d1    | 38        | 0.31%   |
| 0x806eb    | 37        | 0.3%    |
| 0x08608103 | 36        | 0.3%    |
| 0x20655    | 30        | 0.25%   |
| 0x08600104 | 29        | 0.24%   |
| 0x0a201016 | 28        | 0.23%   |
| 0x08001138 | 28        | 0.23%   |
| 0x706e5    | 27        | 0.22%   |
| 0x906a3    | 26        | 0.21%   |
| 0x406c4    | 26        | 0.21%   |
| 0x0810100b | 26        | 0.21%   |
| 0x0a404102 | 25        | 0.21%   |
| 0x06000852 | 25        | 0.21%   |
| 0x0a50000d | 24        | 0.2%    |
| 0x06006705 | 23        | 0.19%   |
| 0x0a601203 | 22        | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 2099      | 17.57%  |
| Haswell           | 1063      | 8.9%    |
| Unknown           | 901       | 7.54%   |
| Zen 2             | 846       | 7.08%   |
| IvyBridge         | 773       | 6.47%   |
| SandyBridge       | 739       | 6.19%   |
| Zen 3             | 706       | 5.91%   |
| Skylake           | 661       | 5.53%   |
| Zen+              | 567       | 4.75%   |
| CometLake         | 393       | 3.29%   |
| Penryn            | 375       | 3.14%   |
| TigerLake         | 362       | 3.03%   |
| Zen               | 276       | 2.31%   |
| Broadwell         | 273       | 2.29%   |
| Westmere          | 239       | 2%      |
| Piledriver        | 212       | 1.77%   |
| Alderlake Hybrid  | 184       | 1.54%   |
| Silvermont        | 163       | 1.36%   |
| IceLake           | 163       | 1.36%   |
| Core              | 154       | 1.29%   |
| K10               | 138       | 1.16%   |
| Nehalem           | 120       | 1%      |
| Excavator         | 107       | 0.9%    |
| Goldmont plus     | 103       | 0.86%   |
| Puma              | 49        | 0.41%   |
| Steamroller       | 47        | 0.39%   |
| Goldmont          | 43        | 0.36%   |
| Bobcat            | 35        | 0.29%   |
| K8 Hammer         | 34        | 0.28%   |
| K10 Llano         | 32        | 0.27%   |
| Jaguar            | 25        | 0.21%   |
| Bulldozer         | 17        | 0.14%   |
| K8 & K10 hybrid   | 11        | 0.09%   |
| NetBurst          | 9         | 0.08%   |
| Gracemont         | 7         | 0.06%   |
| Bonnell           | 7         | 0.06%   |
| Meteorlake Hybrid | 6         | 0.05%   |
| Tremont           | 5         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6275      | 42.69%  |
| Nvidia                           | 4918      | 33.46%  |
| AMD                              | 3467      | 23.59%  |
| Matrox Electronics Systems       | 19        | 0.13%   |
| ASPEED Technology                | 9         | 0.06%   |
| Silicon Integrated Systems [SiS] | 8         | 0.05%   |
| S3 Graphics                      | 1         | 0.01%   |
| 3Dfx Interactive                 | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 520       | 3.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 422       | 2.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 398       | 2.64%   |
| Intel UHD Graphics 620                                                                   | 333       | 2.21%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 333       | 2.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 329       | 2.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 322       | 2.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 320       | 2.12%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 272       | 1.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 271       | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 254       | 1.68%   |
| Intel HD Graphics 620                                                                    | 223       | 1.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 221       | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 217       | 1.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 213       | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 200       | 1.32%   |
| Intel HD Graphics 630                                                                    | 192       | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 190       | 1.26%   |
| Intel HD Graphics 5500                                                                   | 175       | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 168       | 1.11%   |
| Intel HD Graphics 530                                                                    | 164       | 1.09%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 143       | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 140       | 0.93%   |
| AMD Lucienne                                                                             | 138       | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 130       | 0.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 117       | 0.77%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 116       | 0.77%   |
| AMD Raphael                                                                              | 111       | 0.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 110       | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 109       | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 105       | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 103       | 0.68%   |
| AMD Rembrandt [Radeon 680M]                                                              | 102       | 0.68%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 96        | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 92        | 0.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 92        | 0.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 91        | 0.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 91        | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 85        | 0.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 85        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x Intel                 | 4069      | 33.76%  |
| 1 x Nvidia                | 2604      | 21.61%  |
| 1 x AMD                   | 2513      | 20.85%  |
| Intel + Nvidia            | 1777      | 14.75%  |
| AMD + Nvidia              | 444       | 3.68%   |
| Intel + AMD               | 277       | 2.3%    |
| 2 x AMD                   | 230       | 1.91%   |
| 2 x Nvidia                | 57        | 0.47%   |
| Other                     | 28        | 0.23%   |
| 1 x Matrox                | 10        | 0.08%   |
| 1 x SiS                   | 8         | 0.07%   |
| Nvidia + Matrox           | 6         | 0.05%   |
| Nvidia + ASPEED           | 5         | 0.04%   |
| Intel + 2 x Nvidia        | 4         | 0.03%   |
| AMD + ASPEED              | 3         | 0.02%   |
| 4 x Nvidia                | 2         | 0.02%   |
| 2 x Intel                 | 2         | 0.02%   |
| AMD + Matrox              | 2         | 0.02%   |
| 5 x Nvidia                | 1         | 0.01%   |
| 3 x Nvidia                | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox   | 1         | 0.01%   |
| 2 x AMD + 2 x Nvidia      | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia      | 1         | 0.01%   |
| 1 x S3 Graphics           | 1         | 0.01%   |
| Nvidia + 3Dfx Interactive | 1         | 0.01%   |
| Intel + AMD + 2 x Nvidia  | 1         | 0.01%   |
| 1 x ASPEED                | 1         | 0.01%   |
| AMD + 2 x Nvidia          | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 7622      | 63.12%  |
| Proprietary | 3951      | 32.72%  |
| Unknown     | 502       | 4.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8624      | 70.89%  |
| 1.01-2.0   | 739       | 6.07%   |
| 3.01-4.0   | 683       | 5.61%   |
| 7.01-8.0   | 662       | 5.44%   |
| 5.01-6.0   | 472       | 3.88%   |
| 0.01-0.5   | 412       | 3.39%   |
| 8.01-16.0  | 236       | 1.94%   |
| 0.51-1.0   | 210       | 1.73%   |
| 2.01-3.0   | 87        | 0.72%   |
| 16.01-24.0 | 35        | 0.29%   |
| 4.01-5.0   | 3         | 0.02%   |
| 32.01-64.0 | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1609      | 11.8%   |
| AU Optronics            | 1465      | 10.75%  |
| Chimei Innolux          | 1182      | 8.67%   |
| BOE                     | 1146      | 8.41%   |
| LG Display              | 1103      | 8.09%   |
| Goldstar                | 860       | 6.31%   |
| Dell                    | 824       | 6.04%   |
| Acer                    | 545       | 4%      |
| Apple                   | 426       | 3.12%   |
| Hewlett-Packard         | 409       | 3%      |
| AOC                     | 386       | 2.83%   |
| Sharp                   | 307       | 2.25%   |
| BenQ                    | 293       | 2.15%   |
| Ancor Communications    | 287       | 2.11%   |
| ASUSTek Computer        | 240       | 1.76%   |
| Philips                 | 224       | 1.64%   |
| Lenovo                  | 202       | 1.48%   |
| PANDA                   | 181       | 1.33%   |
| ViewSonic               | 120       | 0.88%   |
| Chi Mei Optoelectronics | 117       | 0.86%   |
| Iiyama                  | 105       | 0.77%   |
| MSI                     | 94        | 0.69%   |
| InfoVision              | 92        | 0.67%   |
| Sony                    | 82        | 0.6%    |
| Sceptre Tech            | 66        | 0.48%   |
| Vizio                   | 56        | 0.41%   |
| Panasonic               | 56        | 0.41%   |
| CSO                     | 54        | 0.4%    |
| Gigabyte Technology     | 51        | 0.37%   |
| Toshiba                 | 39        | 0.29%   |
| Unknown                 | 32        | 0.23%   |
| Eizo                    | 31        | 0.23%   |
| NEC Computers           | 30        | 0.22%   |
| Insignia                | 28        | 0.21%   |
| Vestel Elektronik       | 27        | 0.2%    |
| TMX                     | 27        | 0.2%    |
| Hitachi                 | 25        | 0.18%   |
| HKC                     | 24        | 0.18%   |
| Fujitsu Siemens         | 24        | 0.18%   |
| RTK                     | 21        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 81        | 0.58%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 77        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 65        | 0.46%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 64        | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 62        | 0.44%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 57        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 57        | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 57        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 53        | 0.38%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 45        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 41        | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 37        | 0.26%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 37        | 0.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 37        | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 34        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 33        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 33        | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 32        | 0.23%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 32        | 0.23%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 31        | 0.22%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 31        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 29        | 0.21%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 29        | 0.21%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 28        | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 28        | 0.2%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 28        | 0.2%    |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 27        | 0.19%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 27        | 0.19%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 27        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 27        | 0.19%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 26        | 0.18%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 26        | 0.18%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 25        | 0.18%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 24        | 0.17%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 23        | 0.16%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 22        | 0.16%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 22        | 0.16%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 21        | 0.15%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 21        | 0.15%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 21        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 6040      | 46.91%  |
| 1366x768 (WXGA)    | 1825      | 14.17%  |
| 3840x2160 (4K)     | 1167      | 9.06%   |
| 2560x1440 (QHD)    | 872       | 6.77%   |
| 1600x900 (HD+)     | 372       | 2.89%   |
| 1920x1200 (WUXGA)  | 337       | 2.62%   |
| 3440x1440          | 261       | 2.03%   |
| 1680x1050 (WSXGA+) | 235       | 1.82%   |
| 1440x900 (WXGA+)   | 234       | 1.82%   |
| 2560x1080          | 218       | 1.69%   |
| 1280x1024 (SXGA)   | 184       | 1.43%   |
| 2560x1600          | 177       | 1.37%   |
| 1280x800 (WXGA)    | 170       | 1.32%   |
| 2880x1800          | 112       | 0.87%   |
| 1360x768           | 82        | 0.64%   |
| 3840x1080          | 65        | 0.5%    |
| 3840x2400          | 53        | 0.41%   |
| 1920x540           | 52        | 0.4%    |
| 2160x1440          | 45        | 0.35%   |
| Unknown            | 43        | 0.33%   |
| 2256x1504          | 26        | 0.2%    |
| 3200x1800 (QHD+)   | 22        | 0.17%   |
| 2880x1920          | 21        | 0.16%   |
| 3840x1600          | 19        | 0.15%   |
| 3072x1920          | 19        | 0.15%   |
| 3000x2000          | 17        | 0.13%   |
| 1920x1280          | 17        | 0.13%   |
| 1024x768 (XGA)     | 17        | 0.13%   |
| 1280x720 (HD)      | 15        | 0.12%   |
| 1600x1200          | 14        | 0.11%   |
| 3200x2000          | 12        | 0.09%   |
| 3456x2160          | 9         | 0.07%   |
| 2736x1824          | 9         | 0.07%   |
| 2288x1287          | 9         | 0.07%   |
| 3840x1200          | 8         | 0.06%   |
| 3840x1100          | 8         | 0.06%   |
| 2520x1680          | 6         | 0.05%   |
| 2240x1400          | 6         | 0.05%   |
| 2048x1152          | 6         | 0.05%   |
| 2880x1620          | 5         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3316      | 24.37%  |
| 13      | 1316      | 9.67%   |
| 27      | 1270      | 9.33%   |
| 24      | 1098      | 8.07%   |
| 14      | 1020      | 7.5%    |
| 23      | 792       | 5.82%   |
| 17      | 629       | 4.62%   |
| 21      | 616       | 4.53%   |
| 31      | 581       | 4.27%   |
| 34      | 409       | 3.01%   |
| 19      | 236       | 1.73%   |
| 16      | 226       | 1.66%   |
| Unknown | 218       | 1.6%    |
| 18      | 193       | 1.42%   |
| 12      | 182       | 1.34%   |
| 22      | 156       | 1.15%   |
| 84      | 150       | 1.1%    |
| 20      | 140       | 1.03%   |
| 32      | 111       | 0.82%   |
| 11      | 101       | 0.74%   |
| 72      | 90        | 0.66%   |
| 40      | 85        | 0.62%   |
| 54      | 76        | 0.56%   |
| 48      | 59        | 0.43%   |
| 26      | 49        | 0.36%   |
| 25      | 46        | 0.34%   |
| 28      | 42        | 0.31%   |
| 52      | 35        | 0.26%   |
| 35      | 35        | 0.26%   |
| 49      | 30        | 0.22%   |
| 65      | 26        | 0.19%   |
| 46      | 25        | 0.18%   |
| 29      | 24        | 0.18%   |
| 37      | 23        | 0.17%   |
| 36      | 20        | 0.15%   |
| 33      | 19        | 0.14%   |
| 43      | 18        | 0.13%   |
| 42      | 15        | 0.11%   |
| 74      | 11        | 0.08%   |
| 38      | 10        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 5122      | 38.47%  |
| 501-600        | 2848      | 21.39%  |
| 401-500        | 1216      | 9.13%   |
| 201-300        | 1002      | 7.52%   |
| 601-700        | 804       | 6.04%   |
| 351-400        | 768       | 5.77%   |
| 701-800        | 546       | 4.1%    |
| 1001-1500      | 305       | 2.29%   |
| 1501-2000      | 267       | 2.01%   |
| Unknown        | 218       | 1.64%   |
| 801-900        | 170       | 1.28%   |
| 901-1000       | 36        | 0.27%   |
| More than 2000 | 7         | 0.05%   |
| 101-200        | 5         | 0.04%   |
| 1-100          | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 9398      | 78.53%  |
| 16/10   | 1440      | 12.03%  |
| 21/9    | 490       | 4.09%   |
| 5/4     | 183       | 1.53%   |
| 3/2     | 151       | 1.26%   |
| Unknown | 119       | 0.99%   |
| 32/9    | 76        | 0.64%   |
| 4/3     | 55        | 0.46%   |
| 6/5     | 10        | 0.08%   |
| 3.40    | 8         | 0.07%   |
| 3.20    | 7         | 0.06%   |
| 1.96    | 7         | 0.06%   |
| 1.00    | 7         | 0.06%   |
| 0.89    | 3         | 0.03%   |
| 0.62    | 3         | 0.03%   |
| 0.56    | 3         | 0.03%   |
| 3.73    | 2         | 0.02%   |
| 0.63    | 2         | 0.02%   |
| 6.00    | 1         | 0.01%   |
| 2.12    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 3312      | 24.64%  |
| 201-250        | 2083      | 15.5%   |
| 81-90          | 1822      | 13.56%  |
| 301-350        | 1303      | 9.69%   |
| 351-500        | 1162      | 8.65%   |
| 151-200        | 557       | 4.14%   |
| 121-130        | 502       | 3.73%   |
| 71-80          | 495       | 3.68%   |
| More than 1000 | 463       | 3.44%   |
| 251-300        | 398       | 2.96%   |
| 501-1000       | 296       | 2.2%    |
| 141-150        | 245       | 1.82%   |
| Unknown        | 218       | 1.62%   |
| 111-120        | 210       | 1.56%   |
| 61-70          | 166       | 1.24%   |
| 51-60          | 110       | 0.82%   |
| 131-140        | 57        | 0.42%   |
| 91-100         | 27        | 0.2%    |
| 41-50          | 8         | 0.06%   |
| 1-40           | 7         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 4106      | 31.7%   |
| 121-160       | 3844      | 29.67%  |
| 101-120       | 3050      | 23.54%  |
| 161-240       | 955       | 7.37%   |
| More than 240 | 417       | 3.22%   |
| 1-50          | 364       | 2.81%   |
| Unknown       | 218       | 1.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 9124      | 74.7%   |
| 2     | 2246      | 18.39%  |
| 0     | 528       | 4.32%   |
| 3     | 286       | 2.34%   |
| 4     | 26        | 0.21%   |
| 6     | 2         | 0.02%   |
| 5     | 2         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 6483      | 35.32%  |
| Intel                             | 6210      | 33.83%  |
| Qualcomm Atheros                  | 1763      | 9.61%   |
| Broadcom                          | 1048      | 5.71%   |
| MediaTek                          | 429       | 2.34%   |
| Broadcom Limited                  | 245       | 1.33%   |
| TP-Link                           | 199       | 1.08%   |
| Ralink Technology                 | 171       | 0.93%   |
| Marvell Technology Group          | 165       | 0.9%    |
| Nvidia                            | 141       | 0.77%   |
| Ralink                            | 122       | 0.66%   |
| Samsung Electronics               | 116       | 0.63%   |
| ASIX Electronics                  | 113       | 0.62%   |
| Microsoft                         | 93        | 0.51%   |
| NetGear                           | 68        | 0.37%   |
| Aquantia                          | 59        | 0.32%   |
| Xiaomi                            | 57        | 0.31%   |
| DisplayLink                       | 50        | 0.27%   |
| Qualcomm Atheros Communications   | 49        | 0.27%   |
| Dell                              | 46        | 0.25%   |
| Google                            | 45        | 0.25%   |
| Qualcomm                          | 43        | 0.23%   |
| InterBiometrics                   | 41        | 0.22%   |
| ASUSTek Computer                  | 41        | 0.22%   |
| Lenovo                            | 40        | 0.22%   |
| D-Link                            | 37        | 0.2%    |
| Sierra Wireless                   | 36        | 0.2%    |
| Huawei Technologies               | 35        | 0.19%   |
| Linksys                           | 30        | 0.16%   |
| Ericsson Business Mobile Networks | 24        | 0.13%   |
| OPPO Electronics                  | 22        | 0.12%   |
| JMicron Technology                | 22        | 0.12%   |
| OnePlus Technology (Shenzhen)     | 20        | 0.11%   |
| Motorola PCS                      | 20        | 0.11%   |
| Hewlett-Packard                   | 20        | 0.11%   |
| Edimax Technology                 | 20        | 0.11%   |
| D-Link System                     | 15        | 0.08%   |
| Fibocom                           | 13        | 0.07%   |
| Belkin Components                 | 12        | 0.07%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 4359      | 20.18%  |
| Intel Wi-Fi 6 AX200                                                    | 880       | 4.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 566       | 2.62%   |
| Intel I211 Gigabit Network Connection                                  | 480       | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                      | 470       | 2.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 389       | 1.8%    |
| Intel Wireless 8265 / 8275                                             | 370       | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 370       | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 328       | 1.52%   |
| Intel Wi-Fi 6 AX201                                                    | 284       | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 259       | 1.2%    |
| Intel Ethernet Controller I225-V                                       | 250       | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 244       | 1.13%   |
| Intel Wireless 7265                                                    | 243       | 1.13%   |
| Intel Wireless 7260                                                    | 240       | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 231       | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 217       | 1%      |
| Intel Wireless 8260                                                    | 216       | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 215       | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                         | 208       | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 200       | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                   | 193       | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 188       | 0.87%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 185       | 0.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 184       | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 178       | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 178       | 0.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 172       | 0.8%    |
| Intel Ethernet Connection I217-LM                                      | 162       | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 145       | 0.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 139       | 0.64%   |
| Intel Ethernet Connection (7) I219-V                                   | 135       | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 134       | 0.62%   |
| Intel Wireless 3165                                                    | 129       | 0.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 127       | 0.59%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 116       | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 115       | 0.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 112       | 0.52%   |
| Realtek 802.11ac NIC                                                   | 108       | 0.5%    |
| Broadcom BCM43142 802.11b/g/n                                          | 104       | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4917      | 47.98%  |
| Realtek Semiconductor                 | 1528      | 14.91%  |
| Qualcomm Atheros                      | 1368      | 13.35%  |
| Broadcom                              | 813       | 7.93%   |
| MediaTek                              | 363       | 3.54%   |
| Broadcom Limited                      | 198       | 1.93%   |
| TP-Link                               | 183       | 1.79%   |
| Ralink Technology                     | 171       | 1.67%   |
| Ralink                                | 122       | 1.19%   |
| Microsoft                             | 87        | 0.85%   |
| NetGear                               | 65        | 0.63%   |
| Marvell Technology Group              | 51        | 0.5%    |
| Qualcomm Atheros Communications       | 49        | 0.48%   |
| Dell                                  | 39        | 0.38%   |
| ASUSTek Computer                      | 38        | 0.37%   |
| Sierra Wireless                       | 36        | 0.35%   |
| D-Link                                | 34        | 0.33%   |
| Qualcomm                              | 33        | 0.32%   |
| Linksys                               | 26        | 0.25%   |
| Edimax Technology                     | 20        | 0.2%    |
| Fibocom                               | 13        | 0.13%   |
| Belkin Components                     | 11        | 0.11%   |
| D-Link System                         | 10        | 0.1%    |
| AVM                                   | 9         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 9         | 0.09%   |
| Hewlett-Packard                       | 8         | 0.08%   |
| Sitecom Europe                        | 6         | 0.06%   |
| Qualcomm Technologies                 | 6         | 0.06%   |
| Gemtek                                | 5         | 0.05%   |
| Mercucys                              | 4         | 0.04%   |
| Accton Technology                     | 4         | 0.04%   |
| IMC Networks                          | 3         | 0.03%   |
| ZyDAS                                 | 2         | 0.02%   |
| Wilocity                              | 2         | 0.02%   |
| Wacom                                 | 2         | 0.02%   |
| Samsung Electronics                   | 2         | 0.02%   |
| Ovislink                              | 2         | 0.02%   |
| Micro Star International              | 2         | 0.02%   |
| TRENDnet                              | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 880       | 8.53%   |
| Intel Wireless 8265 / 8275                                           | 370       | 3.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 328       | 3.18%   |
| Intel Wi-Fi 6 AX201                                                  | 284       | 2.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 259       | 2.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 244       | 2.36%   |
| Intel Wireless 7265                                                  | 243       | 2.35%   |
| Intel Wireless 7260                                                  | 240       | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 231       | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 217       | 2.1%    |
| Intel Wireless 8260                                                  | 216       | 2.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 215       | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 208       | 2.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 200       | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 188       | 1.82%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 185       | 1.79%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 184       | 1.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 178       | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 178       | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 172       | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 145       | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 134       | 1.3%    |
| Intel Wireless 3165                                                  | 129       | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 127       | 1.23%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 116       | 1.12%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 112       | 1.09%   |
| Realtek 802.11ac NIC                                                 | 108       | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                        | 104       | 1.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 99        | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 98        | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 94        | 0.91%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 90        | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 88        | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 86        | 0.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 85        | 0.82%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 82        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 77        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 76        | 0.74%   |
| Intel Wireless 3160                                                  | 73        | 0.71%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 71        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 5851      | 54.12%  |
| Intel                                  | 2933      | 27.13%  |
| Qualcomm Atheros                       | 541       | 5%      |
| Broadcom                               | 450       | 4.16%   |
| Nvidia                                 | 141       | 1.3%    |
| Marvell Technology Group               | 114       | 1.05%   |
| ASIX Electronics                       | 113       | 1.05%   |
| Samsung Electronics                    | 70        | 0.65%   |
| MediaTek                               | 65        | 0.6%    |
| Aquantia                               | 59        | 0.55%   |
| Xiaomi                                 | 57        | 0.53%   |
| Broadcom Limited                       | 52        | 0.48%   |
| DisplayLink                            | 50        | 0.46%   |
| Lenovo                                 | 40        | 0.37%   |
| Google                                 | 40        | 0.37%   |
| Huawei Technologies                    | 30        | 0.28%   |
| OPPO Electronics                       | 22        | 0.2%    |
| JMicron Technology                     | 22        | 0.2%    |
| Motorola PCS                           | 20        | 0.18%   |
| TP-Link                                | 16        | 0.15%   |
| OnePlus Technology (Shenzhen)          | 16        | 0.15%   |
| Qualcomm                               | 10        | 0.09%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.08%   |
| ICS Advent                             | 7         | 0.06%   |
| Microsoft                              | 6         | 0.06%   |
| Apple                                  | 6         | 0.06%   |
| VIA Technologies                       | 5         | 0.05%   |
| Hewlett-Packard                        | 5         | 0.05%   |
| D-Link System                          | 5         | 0.05%   |
| Mellanox Technologies                  | 4         | 0.04%   |
| Linksys                                | 4         | 0.04%   |
| American Megatrends                    | 4         | 0.04%   |
| T & A Mobile Phones                    | 3         | 0.03%   |
| NetGear                                | 3         | 0.03%   |
| LG Electronics                         | 3         | 0.03%   |
| D-Link                                 | 3         | 0.03%   |
| ASUSTek Computer                       | 3         | 0.03%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.02%   |
| LSI                                    | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 4359      | 39.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 566       | 5.11%   |
| Intel I211 Gigabit Network Connection                                  | 480       | 4.34%   |
| Realtek RTL8125 2.5GbE Controller                                      | 470       | 4.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 389       | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 370       | 3.34%   |
| Intel Ethernet Controller I225-V                                       | 250       | 2.26%   |
| Intel Ethernet Connection (2) I219-V                                   | 193       | 1.74%   |
| Intel Ethernet Connection I217-LM                                      | 162       | 1.46%   |
| Intel Ethernet Connection (7) I219-V                                   | 135       | 1.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 115       | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                  | 100       | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                          | 90        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 85        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 84        | 0.76%   |
| Intel Ethernet Connection I219-LM                                      | 83        | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                  | 79        | 0.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 75        | 0.68%   |
| Intel 82579V Gigabit Network Connection                                | 72        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 70        | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 70        | 0.63%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 70        | 0.63%   |
| Nvidia MCP79 Ethernet                                                  | 68        | 0.61%   |
| Intel Ethernet Connection I218-LM                                      | 67        | 0.61%   |
| Intel Ethernet Connection I217-V                                       | 63        | 0.57%   |
| Realtek Killer E2600 GbE Controller                                    | 57        | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                   | 57        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 55        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                   | 55        | 0.5%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 54        | 0.49%   |
| Intel I210 Gigabit Network Connection                                  | 53        | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                                  | 52        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 48        | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                                  | 48        | 0.43%   |
| Intel Ethernet Connection (6) I219-V                                   | 45        | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 45        | 0.41%   |
| Nvidia MCP61 Ethernet                                                  | 44        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 42        | 0.38%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 41        | 0.37%   |
| Intel 82574L Gigabit Network Connection                                | 40        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 10060     | 50.44%  |
| WiFi     | 9677      | 48.52%  |
| Modem    | 180       | 0.9%    |
| Unknown  | 26        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 7537      | 59.59%  |
| Ethernet | 5103      | 40.35%  |
| Modem    | 5         | 0.04%   |
| Unknown  | 3         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 6713      | 56.16%  |
| 1     | 4754      | 39.77%  |
| 3     | 293       | 2.45%   |
| 0     | 132       | 1.1%    |
| 4     | 48        | 0.4%    |
| 5     | 9         | 0.08%   |
| 10    | 2         | 0.02%   |
| 6     | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9134      | 75.24%  |
| Yes  | 3006      | 24.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 4316      | 51.33%  |
| Realtek Semiconductor           | 720       | 8.56%   |
| Qualcomm Atheros Communications | 589       | 7.01%   |
| Apple                           | 515       | 6.13%   |
| Cambridge Silicon Radio         | 405       | 4.82%   |
| IMC Networks                    | 367       | 4.36%   |
| Broadcom                        | 313       | 3.72%   |
| Foxconn / Hon Hai               | 255       | 3.03%   |
| Lite-On Technology              | 250       | 2.97%   |
| ASUSTek Computer                | 133       | 1.58%   |
| MediaTek                        | 100       | 1.19%   |
| Dell                            | 87        | 1.03%   |
| Marvell Semiconductor           | 54        | 0.64%   |
| Realtek                         | 49        | 0.58%   |
| Ralink                          | 38        | 0.45%   |
| Hewlett-Packard                 | 38        | 0.45%   |
| Toshiba                         | 36        | 0.43%   |
| TP-Link                         | 31        | 0.37%   |
| USI                             | 13        | 0.15%   |
| Foxconn International           | 13        | 0.15%   |
| Dynex                           | 11        | 0.13%   |
| Ralink Technology               | 9         | 0.11%   |
| Alps Electric                   | 8         | 0.1%    |
| Actions                         | 8         | 0.1%    |
| Integrated System Solution      | 5         | 0.06%   |
| Smart Modular Technologies      | 4         | 0.05%   |
| HTC (High Tech Computer)        | 4         | 0.05%   |
| Edimax Technology               | 4         | 0.05%   |
| Askey Computer                  | 4         | 0.05%   |
| Taiyo Yuden                     | 3         | 0.04%   |
| SINO WEALTH                     | 3         | 0.04%   |
| Qcom                            | 3         | 0.04%   |
| Opticis                         | 3         | 0.04%   |
| Micro Star International        | 3         | 0.04%   |
| Logitech                        | 3         | 0.04%   |
| Creative Technology             | 3         | 0.04%   |
| Fujitsu                         | 2         | 0.02%   |
| Conwise Technology              | 2         | 0.02%   |
| Belkin Components               | 2         | 0.02%   |
| Primax Electronics              | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1216      | 14.45%  |
| Intel AX200 Bluetooth                               | 838       | 9.96%   |
| Intel AX201 Bluetooth                               | 793       | 9.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 556       | 6.61%   |
| Realtek Bluetooth Radio                             | 434       | 5.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 405       | 4.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 317       | 3.77%   |
| Apple Bluetooth Host Controller                     | 259       | 3.08%   |
| Intel AX211 Bluetooth                               | 252       | 3%      |
| Intel AX210 Bluetooth                               | 175       | 2.08%   |
| Intel Wireless-AC 3168 Bluetooth                    | 173       | 2.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 171       | 2.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 157       | 1.87%   |
| Apple Bluetooth USB Host Controller                 | 156       | 1.85%   |
| IMC Networks Wireless_Device                        | 134       | 1.59%   |
| IMC Networks Bluetooth Radio                        | 114       | 1.35%   |
| MediaTek Wireless_Device                            | 100       | 1.19%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 90        | 1.07%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 85        | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                  | 81        | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 73        | 0.87%   |
| Foxconn / Hon Hai Wireless_Device                   | 72        | 0.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 64        | 0.76%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 62        | 0.74%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 61        | 0.72%   |
| IMC Networks Bluetooth Device                       | 60        | 0.71%   |
| Lite-On Bluetooth Device                            | 56        | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 55        | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 55        | 0.65%   |
| Realtek 802.11ac WLAN Adapter                       | 49        | 0.58%   |
| Realtek Bluetooth Radio                             | 49        | 0.58%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 49        | 0.58%   |
| Broadcom BCM2045B (BDC-2.1)                         | 42        | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 39        | 0.46%   |
| Ralink RT3290 Bluetooth                             | 38        | 0.45%   |
| Apple Bluetooth HCI                                 | 38        | 0.45%   |
| Marvell Bluetooth and Wireless LAN Composite        | 37        | 0.44%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 33        | 0.39%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 31        | 0.37%   |
| Lite-On Wireless_Device                             | 31        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 8064      | 43.59%  |
| AMD                                  | 4093      | 22.13%  |
| Nvidia                               | 3946      | 21.33%  |
| C-Media Electronics                  | 317       | 1.71%   |
| Logitech                             | 192       | 1.04%   |
| Kingston Technology                  | 98        | 0.53%   |
| JMTek                                | 95        | 0.51%   |
| Razer USA                            | 92        | 0.5%    |
| Creative Labs                        | 92        | 0.5%    |
| SteelSeries ApS                      | 81        | 0.44%   |
| Corsair                              | 78        | 0.42%   |
| ASUSTek Computer                     | 74        | 0.4%    |
| Texas Instruments                    | 73        | 0.39%   |
| Realtek Semiconductor                | 71        | 0.38%   |
| Focusrite-Novation                   | 66        | 0.36%   |
| Generalplus Technology               | 55        | 0.3%    |
| GN Netcom                            | 50        | 0.27%   |
| Creative Technology                  | 49        | 0.26%   |
| Micro Star International             | 47        | 0.25%   |
| Lenovo                               | 46        | 0.25%   |
| Blue Microphones                     | 40        | 0.22%   |
| Sony                                 | 36        | 0.19%   |
| Plantronics                          | 35        | 0.19%   |
| Apple                                | 30        | 0.16%   |
| Hewlett-Packard                      | 27        | 0.15%   |
| DSEA A/S                             | 23        | 0.12%   |
| Astro Gaming                         | 22        | 0.12%   |
| Giga-Byte Technology                 | 21        | 0.11%   |
| FiiO Electronics Technology          | 19        | 0.1%    |
| Valve Software                       | 18        | 0.1%    |
| Tenx Technology                      | 17        | 0.09%   |
| Turtle Beach                         | 16        | 0.09%   |
| Thesycon Systemsoftware & Consulting | 16        | 0.09%   |
| Samson Technologies                  | 16        | 0.09%   |
| Yamaha                               | 15        | 0.08%   |
| BEHRINGER International              | 14        | 0.08%   |
| SAVITECH                             | 13        | 0.07%   |
| M-Audio                              | 13        | 0.07%   |
| KTMicro                              | 13        | 0.07%   |
| Jieli Technology                     | 12        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 1489      | 6.75%   |
| Intel Sunrise Point-LP HD Audio                                            | 891       | 4.04%   |
| AMD Starship/Matisse HD Audio Controller                                   | 891       | 4.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 730       | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 686       | 3.11%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 647       | 2.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 605       | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 574       | 2.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 399       | 1.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 362       | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 359       | 1.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 359       | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 345       | 1.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 334       | 1.51%   |
| Intel 8 Series HD Audio Controller                                         | 332       | 1.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 328       | 1.49%   |
| Nvidia TU106 High Definition Audio Controller                              | 300       | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                            | 288       | 1.31%   |
| Intel Comet Lake PCH cAVS                                                  | 284       | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 265       | 1.2%    |
| Nvidia GA104 High Definition Audio Controller                              | 264       | 1.2%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 260       | 1.18%   |
| Intel Broadwell-U Audio Controller                                         | 258       | 1.17%   |
| Nvidia GP104 High Definition Audio Controller                              | 253       | 1.15%   |
| Nvidia TU116 High Definition Audio Controller                              | 251       | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 251       | 1.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 251       | 1.14%   |
| AMD FCH Azalia Controller                                                  | 251       | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 249       | 1.13%   |
| Intel 200 Series PCH HD Audio                                              | 245       | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 244       | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 239       | 1.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 237       | 1.07%   |
| Nvidia GP106 High Definition Audio Controller                              | 230       | 1.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 209       | 0.95%   |
| Nvidia GA106 High Definition Audio Controller                              | 194       | 0.88%   |
| AMD Navi 10 HDMI Audio                                                     | 183       | 0.83%   |
| Intel CM238 HD Audio Controller                                            | 179       | 0.81%   |
| Nvidia TU104 HD Audio Controller                                           | 167       | 0.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 165       | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 791       | 22.63%  |
| SK hynix                     | 638       | 18.25%  |
| Micron Technology            | 400       | 11.44%  |
| Kingston                     | 343       | 9.81%   |
| Corsair                      | 275       | 7.87%   |
| Crucial                      | 237       | 6.78%   |
| G.Skill                      | 168       | 4.81%   |
| Unknown                      | 141       | 4.03%   |
| A-DATA Technology            | 74        | 2.12%   |
| Team                         | 56        | 1.6%    |
| Ramaxel Technology           | 43        | 1.23%   |
| Unknown                      | 40        | 1.14%   |
| Smart                        | 38        | 1.09%   |
| Elpida                       | 32        | 0.92%   |
| Goldkey                      | 26        | 0.74%   |
| Neo Forza                    | 25        | 0.72%   |
| Unknown (ABCD)               | 20        | 0.57%   |
| Patriot                      | 15        | 0.43%   |
| Smart Brazil                 | 11        | 0.31%   |
| Nanya Technology             | 10        | 0.29%   |
| Teikon                       | 8         | 0.23%   |
| Apacer                       | 8         | 0.23%   |
| PNY                          | 6         | 0.17%   |
| Avant                        | 6         | 0.17%   |
| Transcend                    | 5         | 0.14%   |
| Timetec                      | 5         | 0.14%   |
| Silicon Power                | 4         | 0.11%   |
| GOODRAM                      | 4         | 0.11%   |
| Patriot Memory (PDP Systems) | 3         | 0.09%   |
| High Bridge                  | 3         | 0.09%   |
| GSkill                       | 3         | 0.09%   |
| CSX                          | 3         | 0.09%   |
| ChangXin Memory              | 3         | 0.09%   |
| ASint Technology             | 3         | 0.09%   |
| Wodposit                     | 2         | 0.06%   |
| Unifosa                      | 2         | 0.06%   |
| Patriot Memory               | 2         | 0.06%   |
| OLOY                         | 2         | 0.06%   |
| Gold Key                     | 2         | 0.06%   |
| AMD                          | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 56        | 1.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 41        | 1.11%   |
| Unknown                                                          | 40        | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 35        | 0.95%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 35        | 0.95%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 30        | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 27        | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 26        | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 24        | 0.65%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.62%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 23        | 0.62%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 21        | 0.57%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 20        | 0.54%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 19        | 0.52%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 17        | 0.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.46%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 0.46%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.46%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 17        | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 17        | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 16        | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.43%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 16        | 0.43%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 16        | 0.43%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.43%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 16        | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 15        | 0.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 15        | 0.41%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 14        | 0.38%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 13        | 0.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.35%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 0.35%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 0.35%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 13        | 0.35%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 13        | 0.35%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 13        | 0.35%   |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s         | 13        | 0.35%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 12        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1944      | 63.84%  |
| DDR3    | 538       | 17.67%  |
| DDR5    | 173       | 5.68%   |
| LPDDR4  | 133       | 4.37%   |
| LPDDR3  | 100       | 3.28%   |
| LPDDR5  | 89        | 2.92%   |
| DDR2    | 30        | 0.99%   |
| Unknown | 21        | 0.69%   |
| SDRAM   | 14        | 0.46%   |
| DDR     | 2         | 0.07%   |
| DRAM    | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1850      | 60.06%  |
| DIMM         | 847       | 27.5%   |
| Row Of Chips | 356       | 11.56%  |
| Chip         | 19        | 0.62%   |
| Unknown      | 7         | 0.23%   |
| RIMM         | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1424      | 43.3%   |
| 16384 | 797       | 24.23%  |
| 4096  | 673       | 20.46%  |
| 32768 | 223       | 6.78%   |
| 2048  | 143       | 4.35%   |
| 1024  | 23        | 0.7%    |
| 3072  | 2         | 0.06%   |
| 512   | 2         | 0.06%   |
| 65536 | 1         | 0.03%   |
| 49152 | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 705       | 21.42%  |
| 2667    | 619       | 18.81%  |
| 1600    | 381       | 11.58%  |
| 2400    | 251       | 7.63%   |
| 3600    | 172       | 5.23%   |
| 2133    | 161       | 4.89%   |
| 4800    | 87        | 2.64%   |
| 1333    | 85        | 2.58%   |
| 6400    | 74        | 2.25%   |
| 4267    | 70        | 2.13%   |
| 1867    | 58        | 1.76%   |
| 3733    | 48        | 1.46%   |
| 5600    | 44        | 1.34%   |
| 3800    | 42        | 1.28%   |
| 3266    | 38        | 1.15%   |
| 1334    | 36        | 1.09%   |
| 3000    | 35        | 1.06%   |
| 800     | 24        | 0.73%   |
| 3400    | 22        | 0.67%   |
| 8400    | 21        | 0.64%   |
| 6000    | 20        | 0.61%   |
| 4266    | 20        | 0.61%   |
| 4000    | 20        | 0.61%   |
| 2933    | 20        | 0.61%   |
| 1067    | 19        | 0.58%   |
| 2666    | 17        | 0.52%   |
| 3534    | 16        | 0.49%   |
| 1866    | 16        | 0.49%   |
| 667     | 14        | 0.43%   |
| 7500    | 13        | 0.4%    |
| 3466    | 13        | 0.4%    |
| 5200    | 12        | 0.36%   |
| 3866    | 11        | 0.33%   |
| 1800    | 11        | 0.33%   |
| Unknown | 11        | 0.33%   |
| 3066    | 7         | 0.21%   |
| 2800    | 7         | 0.21%   |
| 3666    | 6         | 0.18%   |
| 4400    | 5         | 0.15%   |
| 1066    | 5         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 68        | 30.63%  |
| Brother Industries    | 41        | 18.47%  |
| Canon                 | 34        | 15.32%  |
| Samsung Electronics   | 25        | 11.26%  |
| Seiko Epson           | 24        | 10.81%  |
| Dymo-CoStar           | 8         | 3.6%    |
| STMicroelectronics    | 3         | 1.35%   |
| Fuji Xerox            | 3         | 1.35%   |
| Xerox                 | 2         | 0.9%    |
| QinHeng Electronics   | 2         | 0.9%    |
| Kyocera               | 2         | 0.9%    |
| Dell                  | 2         | 0.9%    |
| Ricoh                 | 1         | 0.45%   |
| Prolific Technology   | 1         | 0.45%   |
| Pantum                | 1         | 0.45%   |
| Oki Data              | 1         | 0.45%   |
| MIIIW                 | 1         | 0.45%   |
| Lexmark International | 1         | 0.45%   |
| ICS Advent            | 1         | 0.45%   |
| Apple                 | 1         | 0.45%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP Deskjet 3050 J610 series                               | 5         | 2.24%   |
| Brother Printer                                           | 5         | 2.24%   |
| Samsung M2020 Series                                      | 4         | 1.79%   |
| Dymo-CoStar LabelWriter 450                               | 4         | 1.79%   |
| Canon PIXMA MX920 Series                                  | 4         | 1.79%   |
| Brother HL-2130 series                                    | 4         | 1.79%   |
| Seiko Epson ET-2700 Series                                | 3         | 1.35%   |
| Samsung SCX-3400 Series                                   | 3         | 1.35%   |
| Samsung ML-1640 Series Laser Printer                      | 3         | 1.35%   |
| HP LaserJet Professional P 1102w                          | 3         | 1.35%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 3         | 1.35%   |
| Canon PIXMA MG2500 Series                                 | 3         | 1.35%   |
| Brother HL-2270DW Laser Printer                           | 3         | 1.35%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 0.9%    |
| Seiko Epson WF-4830 Series                                | 2         | 0.9%    |
| Seiko Epson WF-3520 Series                                | 2         | 0.9%    |
| Seiko Epson L355 Series                                   | 2         | 0.9%    |
| Seiko Epson L3110 Series                                  | 2         | 0.9%    |
| Seiko Epson ET-3760 Series                                | 2         | 0.9%    |
| Seiko Epson ET-2600 Series                                | 2         | 0.9%    |
| Samsung M2070 Series                                      | 2         | 0.9%    |
| QinHeng CH340S                                            | 2         | 0.9%    |
| HP OfficeJet 3830 series                                  | 2         | 0.9%    |
| HP HP LaserJet M14-M17                                    | 2         | 0.9%    |
| HP ENVY Pro 6400 series                                   | 2         | 0.9%    |
| HP ENVY Photo 6200 series                                 | 2         | 0.9%    |
| HP ENVY 4520 series                                       | 2         | 0.9%    |
| HP ENVY 4500 series                                       | 2         | 0.9%    |
| HP DeskJet F4100 Printer series                           | 2         | 0.9%    |
| HP Deskjet F2280 series                                   | 2         | 0.9%    |
| HP DeskJet 2620 All-in-One Printer                        | 2         | 0.9%    |
| HP Deskjet 2540 series                                    | 2         | 0.9%    |
| HP DeskJet 2130 series                                    | 2         | 0.9%    |
| HP Deskjet 1050 J410                                      | 2         | 0.9%    |
| HP Deskjet 1000 J110 series                               | 2         | 0.9%    |
| Fuji Xerox DocuPrint CM315/318 z                          | 2         | 0.9%    |
| Canon TR4700 series                                       | 2         | 0.9%    |
| Canon LiDE 400                                            | 2         | 0.9%    |
| Brother HL-L3230CDW series                                | 2         | 0.9%    |
| Brother HL-1110 series                                    | 2         | 0.9%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 44%     |
| Seiko Epson     | 9         | 36%     |
| Hewlett-Packard | 4         | 16%     |
| Mustek Systems  | 1         | 4%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson Scanner                                     | 2         | 8%      |
| Seiko Epson Perfection V37/V370                         | 2         | 8%      |
| Canon CanoScan N1240U/LiDE 30                           | 2         | 8%      |
| Canon CanoScan LiDE 210                                 | 2         | 8%      |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 4%      |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 4%      |
| Seiko Epson GT-X700 [Perfection 4870]                   | 1         | 4%      |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 4%      |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1         | 4%      |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 4%      |
| HP Scanjet G2710                                        | 1         | 4%      |
| HP ScanJet 82x0C                                        | 1         | 4%      |
| HP Scanjet 300                                          | 1         | 4%      |
| HP ScanJet 2400c                                        | 1         | 4%      |
| Canon CanoScan N650U/N656U                              | 1         | 4%      |
| Canon CanoScan LiDE 60                                  | 1         | 4%      |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 4%      |
| Canon CanoScan LiDE 220                                 | 1         | 4%      |
| Canon CanoScan LiDE 200                                 | 1         | 4%      |
| Canon CanoScan LiDE 110                                 | 1         | 4%      |
| Canon CanoScan 9000F Mark II                            | 1         | 4%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1460      | 19.89%  |
| IMC Networks                           | 685       | 9.33%   |
| Microdia                               | 662       | 9.02%   |
| Realtek Semiconductor                  | 520       | 7.09%   |
| Logitech                               | 487       | 6.64%   |
| Bison Electronics                      | 436       | 5.94%   |
| Apple                                  | 386       | 5.26%   |
| Sunplus Innovation Technology          | 376       | 5.12%   |
| Quanta                                 | 349       | 4.76%   |
| Acer                                   | 224       | 3.05%   |
| Cheng Uei Precision Industry (Foxlink) | 209       | 2.85%   |
| Syntek                                 | 182       | 2.48%   |
| Suyin                                  | 156       | 2.13%   |
| Luxvisions Innotech Limited            | 151       | 2.06%   |
| Lite-On Technology                     | 146       | 1.99%   |
| Microsoft                              | 85        | 1.16%   |
| Silicon Motion                         | 79        | 1.08%   |
| Samsung Electronics                    | 60        | 0.82%   |
| Sonix Technology                       | 58        | 0.79%   |
| Alcor Micro                            | 47        | 0.64%   |
| Ricoh                                  | 42        | 0.57%   |
| Generalplus Technology                 | 34        | 0.46%   |
| SunplusIT                              | 25        | 0.34%   |
| Z-Star Microelectronics                | 24        | 0.33%   |
| Razer USA                              | 23        | 0.31%   |
| ARC International                      | 18        | 0.25%   |
| Valve Software                         | 16        | 0.22%   |
| ShineTech                              | 16        | 0.22%   |
| Primax Electronics                     | 15        | 0.2%    |
| Jieli Technology                       | 15        | 0.2%    |
| ALi                                    | 15        | 0.2%    |
| MacroSilicon                           | 14        | 0.19%   |
| Creative Technology                    | 14        | 0.19%   |
| Lenovo                                 | 13        | 0.18%   |
| OmniVision Technologies                | 12        | 0.16%   |
| Intel                                  | 12        | 0.16%   |
| Importek                               | 12        | 0.16%   |
| KYE Systems (Mouse Systems)            | 11        | 0.15%   |
| Hewlett-Packard                        | 10        | 0.14%   |
| DigiTech                               | 10        | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 317       | 4.28%   |
| Chicony Integrated Camera                           | 315       | 4.25%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 231       | 3.12%   |
| Realtek Integrated_Webcam_HD                        | 199       | 2.68%   |
| IMC Networks Integrated Camera                      | 199       | 2.68%   |
| Chicony HD Webcam                                   | 152       | 2.05%   |
| Acer BisonCam,NB Pro                                | 124       | 1.67%   |
| Syntek Integrated Camera                            | 123       | 1.66%   |
| Logitech HD Pro Webcam C920                         | 121       | 1.63%   |
| Bison Integrated Camera                             | 120       | 1.62%   |
| Apple Built-in iSight                               | 110       | 1.48%   |
| Chicony USB2.0 Camera                               | 103       | 1.39%   |
| Sunplus Integrated_Webcam_HD                        | 96        | 1.3%    |
| Apple FaceTime HD Camera                            | 92        | 1.24%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 86        | 1.16%   |
| Logitech Webcam C270                                | 85        | 1.15%   |
| Apple FaceTime HD Camera (Built-in)                 | 81        | 1.09%   |
| Bison HD Webcam                                     | 74        | 1%      |
| Quanta HD User Facing                               | 73        | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 66        | 0.89%   |
| Lite-On Integrated Camera                           | 59        | 0.8%    |
| Samsung Galaxy series, misc. (MTP mode)             | 57        | 0.77%   |
| Chicony HP HD Camera                                | 54        | 0.73%   |
| Logitech C922 Pro Stream Webcam                     | 51        | 0.69%   |
| Chicony HP Wide Vision HD Camera                    | 48        | 0.65%   |
| Bison SunplusIT Integrated Camera                   | 46        | 0.62%   |
| Microdia Webcam Vitade AF                           | 45        | 0.61%   |
| Chicony HD User Facing                              | 45        | 0.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 42        | 0.57%   |
| Microdia Integrated Webcam                          | 41        | 0.55%   |
| Chicony USB 2.0 Camera                              | 41        | 0.55%   |
| Sunplus HD WebCam                                   | 39        | 0.53%   |
| Chicony USB2.0 HD UVC WebCam                        | 39        | 0.53%   |
| Chicony Integrated Camera (1280x720@30)             | 39        | 0.53%   |
| Acer Integrated Camera                              | 39        | 0.53%   |
| Quanta HD Webcam                                    | 38        | 0.51%   |
| Sonix USB2.0 HD UVC WebCam                          | 37        | 0.5%    |
| Quanta HP TrueVision HD Camera                      | 37        | 0.5%    |
| Chicony TOSHIBA Web Camera - HD                     | 36        | 0.49%   |
| Sunplus ASUS Webcam                                 | 35        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 463       | 35.32%  |
| Validity Sensors                   | 366       | 27.92%  |
| Shenzhen Goodix Technology         | 233       | 17.77%  |
| Elan Microelectronics              | 74        | 5.64%   |
| Upek                               | 58        | 4.42%   |
| LighTuning Technology              | 51        | 3.89%   |
| AuthenTec                          | 34        | 2.59%   |
| Realtek USB2.0 Finger Print Bridge | 9         | 0.69%   |
| STMicroelectronics                 | 8         | 0.61%   |
| Focal-systems.Corp                 | 6         | 0.46%   |
| HOLTEK                             | 4         | 0.31%   |
| Samsung Electronics                | 3         | 0.23%   |
| DigitalPersona                     | 2         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 123       | 9.38%   |
| Shenzhen Goodix  Fingerprint Device                                        | 103       | 7.86%   |
| Shenzhen Goodix Fingerprint Reader                                         | 78        | 5.95%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 76        | 5.8%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 71        | 5.42%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 53        | 4.04%   |
| Shenzhen Goodix FingerPrint                                                | 52        | 3.97%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 48        | 3.66%   |
| Elan ELAN:Fingerprint                                                      | 41        | 3.13%   |
| Synaptics  WBDI                                                            | 35        | 2.67%   |
| Validity Sensors Synaptics WBDI                                            | 32        | 2.44%   |
| Synaptics TouchPad                                                         | 31        | 2.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 27        | 2.06%   |
| Validity Sensors VFS491                                                    | 26        | 1.98%   |
| Synaptics UWP WBDI                                                         | 26        | 1.98%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 26        | 1.98%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 25        | 1.91%   |
| Synaptics WBDI                                                             | 24        | 1.83%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 23        | 1.75%   |
| Validity Sensors Fingerprint scanner                                       | 23        | 1.75%   |
| Synaptics WBDI Device                                                      | 23        | 1.75%   |
| Elan ELAN:ARM-M4                                                           | 23        | 1.75%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 22        | 1.68%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 22        | 1.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 20        | 1.53%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 19        | 1.45%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 19        | 1.45%   |
| Synaptics Fingerprint reader [HP G6]                                       | 17        | 1.3%    |
| Unknown                                                                    | 17        | 1.3%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 1.07%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 13        | 0.99%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 0.92%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 12        | 0.92%   |
| Synaptics Prometheus Fingerprint Reader                                    | 10        | 0.76%   |
| AuthenTec Fingerprint Sensor                                               | 10        | 0.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 9         | 0.69%   |
| Synaptics UWP WBDI Device                                                  | 9         | 0.69%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 9         | 0.69%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 0.61%   |
| Elan WBF Fingerprint Sensor                                                | 8         | 0.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 220       | 47.62%  |
| Alcor Micro               | 129       | 27.92%  |
| Upek                      | 33        | 7.14%   |
| O2 Micro                  | 30        | 6.49%   |
| Lenovo                    | 22        | 4.76%   |
| SCM Microsystems          | 9         | 1.95%   |
| OmniKey                   | 5         | 1.08%   |
| Realtek Semiconductor     | 3         | 0.65%   |
| Gemalto (was Gemplus)     | 2         | 0.43%   |
| Chicony Electronics       | 2         | 0.43%   |
| Aladdin Knowledge Systems | 2         | 0.43%   |
| Advanced Card Systems     | 2         | 0.43%   |
| Yubico.com                | 1         | 0.22%   |
| Giesecke & Devrient       | 1         | 0.22%   |
| Clay Logic                | 1         | 0.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 127       | 27.49%  |
| Broadcom BCM5880 Secure Applications Processor                               | 60        | 12.99%  |
| Broadcom 5880                                                                | 59        | 12.77%  |
| Broadcom 58200                                                               | 52        | 11.26%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 46        | 9.96%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 33        | 7.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 5.63%   |
| Lenovo Integrated Smart Card Reader                                          | 22        | 4.76%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 7         | 1.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 0.87%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.65%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 3         | 0.65%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.43%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.43%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.43%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.43%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.22%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.22%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.22%   |
| OmniKey CardMan 4321                                                         | 1         | 0.22%   |
| OmniKey CardMan 1021                                                         | 1         | 0.22%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.22%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.22%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.22%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.22%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.22%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.22%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 8346      | 68.57%  |
| 1     | 3140      | 25.8%   |
| 2     | 587       | 4.82%   |
| 3     | 79        | 0.65%   |
| 4     | 12        | 0.1%    |
| 5     | 5         | 0.04%   |
| 7     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1284      | 28.71%  |
| Graphics card            | 778       | 17.4%   |
| Net/wireless             | 710       | 15.88%  |
| Multimedia controller    | 543       | 12.14%  |
| Chipcard                 | 442       | 9.88%   |
| Bluetooth                | 136       | 3.04%   |
| Camera                   | 129       | 2.88%   |
| Unassigned class         | 76        | 1.7%    |
| Communication controller | 74        | 1.65%   |
| Sound                    | 69        | 1.54%   |
| Net/ethernet             | 54        | 1.21%   |
| Storage                  | 49        | 1.1%    |
| Network                  | 30        | 0.67%   |
| Card reader              | 29        | 0.65%   |
| Storage/raid             | 25        | 0.56%   |
| Modem                    | 15        | 0.34%   |
| Storage/ide              | 11        | 0.25%   |
| Storage/nvme             | 6         | 0.13%   |
| Firewire controller      | 4         | 0.09%   |
| Dvb card                 | 3         | 0.07%   |
| Flash memory             | 2         | 0.04%   |
| Wireless                 | 1         | 0.02%   |
| Unclassified device      | 1         | 0.02%   |
| Tv card                  | 1         | 0.02%   |

