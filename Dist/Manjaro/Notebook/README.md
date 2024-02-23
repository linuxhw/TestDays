Manjaro - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 6138

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A517-51G             | [2788a21644](https://linux-hardware.org/?probe=2788a21644) | Feb 02, 2024 |
| HP            | 255 15.6 inch G10           | [86bdc742bd](https://linux-hardware.org/?probe=86bdc742bd) | Feb 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [6f80a7214c](https://linux-hardware.org/?probe=6f80a7214c) | Feb 01, 2024 |
| Dell          | Latitude 7490               | [f6c07c876d](https://linux-hardware.org/?probe=f6c07c876d) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480 20L6S4XW00    | [a24ce87b69](https://linux-hardware.org/?probe=a24ce87b69) | Feb 01, 2024 |
| Thomson       | N15C8BK2T                   | [5de65dcec1](https://linux-hardware.org/?probe=5de65dcec1) | Jan 31, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [4af4b18a2c](https://linux-hardware.org/?probe=4af4b18a2c) | Jan 31, 2024 |
| HP            | Laptop 15-fc0xxx            | [28e16f1c53](https://linux-hardware.org/?probe=28e16f1c53) | Jan 31, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [fff51c5158](https://linux-hardware.org/?probe=fff51c5158) | Jan 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [bc89935fa2](https://linux-hardware.org/?probe=bc89935fa2) | Jan 29, 2024 |
| Apple         | MacBookPro14,1              | [596ac6a467](https://linux-hardware.org/?probe=596ac6a467) | Jan 29, 2024 |
| HP            | Stream Laptop 14-DS0xxx     | [b2cff77c57](https://linux-hardware.org/?probe=b2cff77c57) | Jan 29, 2024 |
| Fujitsu       | LIFEBOOK E744               | [0bdbea7dcb](https://linux-hardware.org/?probe=0bdbea7dcb) | Jan 29, 2024 |
| Fujitsu       | LIFEBOOK E744               | [3e03ee6e0f](https://linux-hardware.org/?probe=3e03ee6e0f) | Jan 29, 2024 |
| HP            | EliteBook 840 g5            | [b9ca87e1e4](https://linux-hardware.org/?probe=b9ca87e1e4) | Jan 28, 2024 |
| ASUSTek       | K52JU                       | [066d333914](https://linux-hardware.org/?probe=066d333914) | Jan 28, 2024 |
| Dell          | Inspiron 15-3567            | [9ce085875f](https://linux-hardware.org/?probe=9ce085875f) | Jan 27, 2024 |
| Lenovo        | ThinkPad T495 20NKS5AU00    | [e382eee8ac](https://linux-hardware.org/?probe=e382eee8ac) | Jan 27, 2024 |
| Dell          | Latitude E7270              | [7ebc1a4cdb](https://linux-hardware.org/?probe=7ebc1a4cdb) | Jan 27, 2024 |
| ARDOR GAMI... | PD5x_7xSNC_SND_SNE          | [398529b5cb](https://linux-hardware.org/?probe=398529b5cb) | Jan 27, 2024 |
| HP            | Pavilion 14                 | [93fffe502f](https://linux-hardware.org/?probe=93fffe502f) | Jan 27, 2024 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [6db5a094d7](https://linux-hardware.org/?probe=6db5a094d7) | Jan 26, 2024 |
| ASUSTek       | X550VXK                     | [4f8a5aa2c2](https://linux-hardware.org/?probe=4f8a5aa2c2) | Jan 26, 2024 |
| ASUSTek       | GR8                         | [f43a22b48b](https://linux-hardware.org/?probe=f43a22b48b) | Jan 26, 2024 |
| Acer          | Swift SF314-43              | [bfbce1457c](https://linux-hardware.org/?probe=bfbce1457c) | Jan 25, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | [2915b21d64](https://linux-hardware.org/?probe=2915b21d64) | Jan 25, 2024 |
| Dell          | Inspiron 5770               | [6cf464989f](https://linux-hardware.org/?probe=6cf464989f) | Jan 24, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [362ad8ae7e](https://linux-hardware.org/?probe=362ad8ae7e) | Jan 24, 2024 |
| Lenovo        | Legion 5 15ARH05 82B5       | [356b235b8b](https://linux-hardware.org/?probe=356b235b8b) | Jan 24, 2024 |
| HUAWEI        | RLEF-XX                     | [dc4ce0b71d](https://linux-hardware.org/?probe=dc4ce0b71d) | Jan 24, 2024 |
| HUAWEI        | RLEF-XX                     | [c53987023c](https://linux-hardware.org/?probe=c53987023c) | Jan 24, 2024 |
| HP            | Laptop 15-fc0xxx            | [20be72b253](https://linux-hardware.org/?probe=20be72b253) | Jan 24, 2024 |
| ASUSTek       | X541UJ                      | [e5a64b928d](https://linux-hardware.org/?probe=e5a64b928d) | Jan 23, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [15666b6776](https://linux-hardware.org/?probe=15666b6776) | Jan 23, 2024 |
| Dell          | Latitude E7450              | [1b19ab817a](https://linux-hardware.org/?probe=1b19ab817a) | Jan 23, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [19eaa1abc0](https://linux-hardware.org/?probe=19eaa1abc0) | Jan 22, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [9a1d16aad2](https://linux-hardware.org/?probe=9a1d16aad2) | Jan 21, 2024 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [379e6473d5](https://linux-hardware.org/?probe=379e6473d5) | Jan 21, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [de30e068d6](https://linux-hardware.org/?probe=de30e068d6) | Jan 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [52783252de](https://linux-hardware.org/?probe=52783252de) | Jan 21, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a8c56ec5a7](https://linux-hardware.org/?probe=a8c56ec5a7) | Jan 21, 2024 |
| HP            | Victus by Laptop 16-d0xx... | [11e78ca269](https://linux-hardware.org/?probe=11e78ca269) | Jan 20, 2024 |
| Notebook      | W350STQ/W370ST              | [a61e368a41](https://linux-hardware.org/?probe=a61e368a41) | Jan 19, 2024 |
| Apple         | MacBookAir7,2               | [8efc1fa078](https://linux-hardware.org/?probe=8efc1fa078) | Jan 19, 2024 |
| Apple         | MacBookAir7,2               | [14a15f0dc3](https://linux-hardware.org/?probe=14a15f0dc3) | Jan 19, 2024 |
| Lenovo        | Z50-70 20354                | [fb225848f0](https://linux-hardware.org/?probe=fb225848f0) | Jan 19, 2024 |
| Razer         | Blade                       | [e99ad5cc36](https://linux-hardware.org/?probe=e99ad5cc36) | Jan 19, 2024 |
| Acer          | Aspire A315-35              | [dafaf99dd0](https://linux-hardware.org/?probe=dafaf99dd0) | Jan 19, 2024 |
| realme        | CloudProXXXX                | [a82160e17d](https://linux-hardware.org/?probe=a82160e17d) | Jan 19, 2024 |
| HP            | 255 15.6 inch G10           | [b852473447](https://linux-hardware.org/?probe=b852473447) | Jan 17, 2024 |
| Lenovo        | Z50-70 20354                | [2e0947a80d](https://linux-hardware.org/?probe=2e0947a80d) | Jan 17, 2024 |
| Lenovo        | ThinkPad T430 2344BMU       | [75e86c5b31](https://linux-hardware.org/?probe=75e86c5b31) | Jan 17, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [4b41c2825f](https://linux-hardware.org/?probe=4b41c2825f) | Jan 17, 2024 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [6274216b05](https://linux-hardware.org/?probe=6274216b05) | Jan 16, 2024 |
| Medion        | Scout E10                   | [10da5c077d](https://linux-hardware.org/?probe=10da5c077d) | Jan 16, 2024 |
| Apple         | MacBookPro9,1               | [3b43ca4be8](https://linux-hardware.org/?probe=3b43ca4be8) | Jan 16, 2024 |
| Lenovo        | ThinkPad X270 20K5S1A524    | [2943099ca8](https://linux-hardware.org/?probe=2943099ca8) | Jan 15, 2024 |
| HP            | ProBook 4340s               | [45354af236](https://linux-hardware.org/?probe=45354af236) | Jan 14, 2024 |
| HP            | ProBook 4340s               | [aea3678636](https://linux-hardware.org/?probe=aea3678636) | Jan 14, 2024 |
| HUAWEI        | BOM-WXX9                    | [f15e99bc7d](https://linux-hardware.org/?probe=f15e99bc7d) | Jan 13, 2024 |
| HUAWEI        | BOD-WXX9                    | [fe4ed2794f](https://linux-hardware.org/?probe=fe4ed2794f) | Jan 13, 2024 |
| HUAWEI        | BOD-WXX9                    | [b5c9600b1e](https://linux-hardware.org/?probe=b5c9600b1e) | Jan 13, 2024 |
| Acer          | Aspire A517-51G             | [5a9f65787f](https://linux-hardware.org/?probe=5a9f65787f) | Jan 13, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [301f2ec339](https://linux-hardware.org/?probe=301f2ec339) | Jan 12, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [84d67dfe96](https://linux-hardware.org/?probe=84d67dfe96) | Jan 12, 2024 |
| MSI           | Katana 17 B13VFK            | [f5b006ea89](https://linux-hardware.org/?probe=f5b006ea89) | Jan 12, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [c913eb2c1b](https://linux-hardware.org/?probe=c913eb2c1b) | Jan 12, 2024 |
| Alienware     | 17 R5                       | [4588195d7c](https://linux-hardware.org/?probe=4588195d7c) | Jan 12, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [3be44d9c7c](https://linux-hardware.org/?probe=3be44d9c7c) | Jan 12, 2024 |
| HP            | ZBook Firefly 15 inch G8... | [1601348335](https://linux-hardware.org/?probe=1601348335) | Jan 11, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [0d7230b853](https://linux-hardware.org/?probe=0d7230b853) | Jan 11, 2024 |
| HP            | Notebook                    | [53e2f16b51](https://linux-hardware.org/?probe=53e2f16b51) | Jan 11, 2024 |
| Dell          | Latitude E7440              | [08decb079c](https://linux-hardware.org/?probe=08decb079c) | Jan 11, 2024 |
| HP            | Victus by Gaming Laptop ... | [6394ca334a](https://linux-hardware.org/?probe=6394ca334a) | Jan 10, 2024 |
| Lenovo        | ThinkPad T430 2344BMU       | [1a57fd0154](https://linux-hardware.org/?probe=1a57fd0154) | Jan 10, 2024 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [12b7a5f613](https://linux-hardware.org/?probe=12b7a5f613) | Jan 10, 2024 |
| HP            | Pavilion 15                 | [e719d4a0cf](https://linux-hardware.org/?probe=e719d4a0cf) | Jan 09, 2024 |
| HP            | Pavilion 15                 | [850d28e06d](https://linux-hardware.org/?probe=850d28e06d) | Jan 09, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [b6445a9a78](https://linux-hardware.org/?probe=b6445a9a78) | Jan 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [158040c457](https://linux-hardware.org/?probe=158040c457) | Jan 09, 2024 |
| Dell          | Latitude 5590               | [80ab1a3a35](https://linux-hardware.org/?probe=80ab1a3a35) | Jan 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [eab14c8b91](https://linux-hardware.org/?probe=eab14c8b91) | Jan 08, 2024 |
| HP            | Laptop 15-fc0xxx            | [468f756c7f](https://linux-hardware.org/?probe=468f756c7f) | Jan 08, 2024 |
| Medion        | S15449                      | [89a6d2fd3f](https://linux-hardware.org/?probe=89a6d2fd3f) | Jan 07, 2024 |
| MSI           | GP75 Leopard 10SFK          | [0fe5251d6d](https://linux-hardware.org/?probe=0fe5251d6d) | Jan 07, 2024 |
| Notebook      | P7xxDM-G                    | [7213fe2836](https://linux-hardware.org/?probe=7213fe2836) | Jan 06, 2024 |
| MSI           | GP75 Leopard 10SFK          | [ad83163c98](https://linux-hardware.org/?probe=ad83163c98) | Jan 06, 2024 |
| Acer          | Predator PH717-72           | [cfa0e5b6c6](https://linux-hardware.org/?probe=cfa0e5b6c6) | Jan 05, 2024 |
| Acer          | Nitro AN515-44              | [6a2df7d4aa](https://linux-hardware.org/?probe=6a2df7d4aa) | Jan 04, 2024 |
| Dell          | Latitude E5530 non-vPro     | [219adf28d5](https://linux-hardware.org/?probe=219adf28d5) | Jan 04, 2024 |
| Dell          | XPS 15 9520                 | [5b8e6d2ed8](https://linux-hardware.org/?probe=5b8e6d2ed8) | Jan 04, 2024 |
| Dell          | XPS 15 9510                 | [7df831af81](https://linux-hardware.org/?probe=7df831af81) | Jan 04, 2024 |
| Dell          | XPS 15 9510                 | [338187cb01](https://linux-hardware.org/?probe=338187cb01) | Jan 04, 2024 |
| Dell          | XPS 15 9520                 | [c0b874f6b0](https://linux-hardware.org/?probe=c0b874f6b0) | Jan 04, 2024 |
| LG Electro... | 23V545-G.BK55P1             | [6cf752515c](https://linux-hardware.org/?probe=6cf752515c) | Jan 04, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [cafe81526a](https://linux-hardware.org/?probe=cafe81526a) | Jan 04, 2024 |
| Dell          | XPS 15 9530                 | [fbd8a37b00](https://linux-hardware.org/?probe=fbd8a37b00) | Jan 04, 2024 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [050bd9db54](https://linux-hardware.org/?probe=050bd9db54) | Jan 04, 2024 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [2575bb7352](https://linux-hardware.org/?probe=2575bb7352) | Jan 04, 2024 |
| Irbis         | NB264                       | [c42f5880cc](https://linux-hardware.org/?probe=c42f5880cc) | Jan 03, 2024 |
| Lenovo        | ThinkPad X260 20F5A1AC00    | [b14e96fc5f](https://linux-hardware.org/?probe=b14e96fc5f) | Jan 03, 2024 |
| HP            | OMEN by Laptop              | [cb6a8b401a](https://linux-hardware.org/?probe=cb6a8b401a) | Jan 02, 2024 |
| Lenovo        | ThinkPad L460 20FU001LGE    | [37f558fd5b](https://linux-hardware.org/?probe=37f558fd5b) | Jan 02, 2024 |
| TUXEDO        | Pulse 15 Gen1               | [84278ca428](https://linux-hardware.org/?probe=84278ca428) | Jan 02, 2024 |
| Notebook      | N14xWU                      | [0460984dea](https://linux-hardware.org/?probe=0460984dea) | Jan 02, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | [095d9cbf7e](https://linux-hardware.org/?probe=095d9cbf7e) | Jan 01, 2024 |
| Dell          | Latitude 7490               | [efab03db5f](https://linux-hardware.org/?probe=efab03db5f) | Jan 01, 2024 |
| Lenovo        | ThinkPad X390 20Q0004VUS    | [4bd6b36cd6](https://linux-hardware.org/?probe=4bd6b36cd6) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p 20AWS4YE0... | [74d75dc18d](https://linux-hardware.org/?probe=74d75dc18d) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p 20AWS4UD0... | [0305a2f3cf](https://linux-hardware.org/?probe=0305a2f3cf) | Dec 30, 2023 |
| Dell          | Latitude E7440              | [d9fb6a9ead](https://linux-hardware.org/?probe=d9fb6a9ead) | Dec 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [394c35d74b](https://linux-hardware.org/?probe=394c35d74b) | Dec 30, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [5cfb3467bc](https://linux-hardware.org/?probe=5cfb3467bc) | Dec 29, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [751429a259](https://linux-hardware.org/?probe=751429a259) | Dec 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [d5ac5fcf72](https://linux-hardware.org/?probe=d5ac5fcf72) | Dec 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [990d141701](https://linux-hardware.org/?probe=990d141701) | Dec 28, 2023 |
| Dell          | Latitude 7490               | [7eab9f671e](https://linux-hardware.org/?probe=7eab9f671e) | Dec 28, 2023 |
| Google        | Dratini                     | [a81971bf37](https://linux-hardware.org/?probe=a81971bf37) | Dec 28, 2023 |
| HP            | ProBook 6470b               | [60858223c4](https://linux-hardware.org/?probe=60858223c4) | Dec 28, 2023 |
| HUAWEI        | HVY-WXX9                    | [313a669de8](https://linux-hardware.org/?probe=313a669de8) | Dec 27, 2023 |
| Panasonic     | FZ-M1CCA17E3                | [c55632d60a](https://linux-hardware.org/?probe=c55632d60a) | Dec 27, 2023 |
| Samsung       | 550XCJ/550XCR               | [c62c257897](https://linux-hardware.org/?probe=c62c257897) | Dec 27, 2023 |
| Apple         | MacBookPro9,2               | [99dfa98b06](https://linux-hardware.org/?probe=99dfa98b06) | Dec 27, 2023 |
| Dell          | Inspiron N5110              | [87efb02531](https://linux-hardware.org/?probe=87efb02531) | Dec 27, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [97f532d3c8](https://linux-hardware.org/?probe=97f532d3c8) | Dec 26, 2023 |
| Dell          | Precision 7520              | [e4390e22b6](https://linux-hardware.org/?probe=e4390e22b6) | Dec 26, 2023 |
| MECHREVO      | Jiaolong16Q Series GM6BG... | [900da4b920](https://linux-hardware.org/?probe=900da4b920) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [522209b304](https://linux-hardware.org/?probe=522209b304) | Dec 26, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5HM0... | [79bfce6143](https://linux-hardware.org/?probe=79bfce6143) | Dec 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ef5699b685](https://linux-hardware.org/?probe=ef5699b685) | Dec 24, 2023 |
| Apple         | MacBookAir7,2               | [03b1209523](https://linux-hardware.org/?probe=03b1209523) | Dec 24, 2023 |
| Apple         | MacBookAir7,2               | [b7f3ca9ba4](https://linux-hardware.org/?probe=b7f3ca9ba4) | Dec 23, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [6cc304ea54](https://linux-hardware.org/?probe=6cc304ea54) | Dec 23, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [a72824a48c](https://linux-hardware.org/?probe=a72824a48c) | Dec 23, 2023 |
| Dell          | Latitude 5580               | [e20360557a](https://linux-hardware.org/?probe=e20360557a) | Dec 22, 2023 |
| Acer          | Aspire A315-35              | [52af26d8a1](https://linux-hardware.org/?probe=52af26d8a1) | Dec 21, 2023 |
| TUXEDO        | Book XP15 / XP17 Gen12      | [62624ca97b](https://linux-hardware.org/?probe=62624ca97b) | Dec 21, 2023 |
| Lenovo        | ThinkPad X201 3680WXT       | [a6e0d33afd](https://linux-hardware.org/?probe=a6e0d33afd) | Dec 21, 2023 |
| Alienware     | m16 R1 AMD                  | [8fc737975c](https://linux-hardware.org/?probe=8fc737975c) | Dec 21, 2023 |
| Acer          | Nitro AN515-43              | [963de967ae](https://linux-hardware.org/?probe=963de967ae) | Dec 19, 2023 |
| Dell          | Latitude 7490               | [6fe6e99364](https://linux-hardware.org/?probe=6fe6e99364) | Dec 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS19500     | [7067fb02ed](https://linux-hardware.org/?probe=7067fb02ed) | Dec 18, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7b5e55e475](https://linux-hardware.org/?probe=7b5e55e475) | Dec 18, 2023 |
| Lenovo        | ThinkPad T460 20FNS11S00    | [901a636942](https://linux-hardware.org/?probe=901a636942) | Dec 17, 2023 |
| Acer          | Aspire 1810TZ               | [b935091ecd](https://linux-hardware.org/?probe=b935091ecd) | Dec 17, 2023 |
| Acer          | Aspire 1810TZ               | [14b5a5a3ca](https://linux-hardware.org/?probe=14b5a5a3ca) | Dec 17, 2023 |
| Lenovo        | ThinkPad T460 20FNS11S00    | [34acff5fa8](https://linux-hardware.org/?probe=34acff5fa8) | Dec 17, 2023 |
| Lenovo        | ThinkPad T460 20FNS11S00    | [8a344f72ea](https://linux-hardware.org/?probe=8a344f72ea) | Dec 17, 2023 |
| HP            | Stream Laptop 14-DS0xxx     | [3e26902ac1](https://linux-hardware.org/?probe=3e26902ac1) | Dec 15, 2023 |
| HUAWEI        | CREFG-XX                    | [ee1bdd536f](https://linux-hardware.org/?probe=ee1bdd536f) | Dec 15, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [165e16505d](https://linux-hardware.org/?probe=165e16505d) | Dec 14, 2023 |
| Acer          | TMP645-M                    | [55c3db256a](https://linux-hardware.org/?probe=55c3db256a) | Dec 13, 2023 |
| GEO           | GEOBOOK 2E                  | [86b33e33ca](https://linux-hardware.org/?probe=86b33e33ca) | Dec 12, 2023 |
| GEO           | GEOBOOK 2E                  | [cac69d7624](https://linux-hardware.org/?probe=cac69d7624) | Dec 12, 2023 |
| ASUSTek       | X550VB                      | [cfc8172838](https://linux-hardware.org/?probe=cfc8172838) | Dec 11, 2023 |
| Lenovo        | ThinkPad T470s 20HF005NU... | [0d9a5839df](https://linux-hardware.org/?probe=0d9a5839df) | Dec 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [e7febd26d4](https://linux-hardware.org/?probe=e7febd26d4) | Dec 10, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [2ba6a00229](https://linux-hardware.org/?probe=2ba6a00229) | Dec 10, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [d906394ed7](https://linux-hardware.org/?probe=d906394ed7) | Dec 10, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [b3f7b8b30a](https://linux-hardware.org/?probe=b3f7b8b30a) | Dec 09, 2023 |
| ASUSTek       | S551LN                      | [4684efbcaa](https://linux-hardware.org/?probe=4684efbcaa) | Dec 09, 2023 |
| Samsung       | R428/P428                   | [bcfc7ba90f](https://linux-hardware.org/?probe=bcfc7ba90f) | Dec 09, 2023 |
| ASUSTek       | S551LN                      | [47aafe0845](https://linux-hardware.org/?probe=47aafe0845) | Dec 08, 2023 |
| Dell          | Latitude 7410               | [5d528f2b74](https://linux-hardware.org/?probe=5d528f2b74) | Dec 08, 2023 |
| Dell          | Latitude 7400               | [692f8c13ff](https://linux-hardware.org/?probe=692f8c13ff) | Dec 07, 2023 |
| Alienware     | m18 R1                      | [79c8580eb9](https://linux-hardware.org/?probe=79c8580eb9) | Dec 07, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [7606deffc4](https://linux-hardware.org/?probe=7606deffc4) | Dec 07, 2023 |
| Alienware     | m18 R1                      | [4a4c2cec97](https://linux-hardware.org/?probe=4a4c2cec97) | Dec 06, 2023 |
| Lenovo        | ThinkPad X220 4290JN8       | [f9cec63bf8](https://linux-hardware.org/?probe=f9cec63bf8) | Dec 06, 2023 |
| Samsung       | RV419/RV420                 | [5f29bdfad1](https://linux-hardware.org/?probe=5f29bdfad1) | Dec 05, 2023 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | [e238c1edb9](https://linux-hardware.org/?probe=e238c1edb9) | Dec 05, 2023 |
| Dell          | XPS 13 9343                 | [d5ee40d605](https://linux-hardware.org/?probe=d5ee40d605) | Dec 05, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [fe06cb32bc](https://linux-hardware.org/?probe=fe06cb32bc) | Dec 05, 2023 |
| Lenovo        | ThinkPad L590 20Q7001CGE    | [03b128fbc9](https://linux-hardware.org/?probe=03b128fbc9) | Dec 04, 2023 |
| HP            | ProBook 430 G6              | [a7dd623bb6](https://linux-hardware.org/?probe=a7dd623bb6) | Dec 04, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [452f677f7f](https://linux-hardware.org/?probe=452f677f7f) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | [e6f0d9a3ae](https://linux-hardware.org/?probe=e6f0d9a3ae) | Dec 03, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [3a6eb27098](https://linux-hardware.org/?probe=3a6eb27098) | Dec 02, 2023 |
| Dell          | Precision 7520              | [3651203e23](https://linux-hardware.org/?probe=3651203e23) | Dec 01, 2023 |
| Acer          | Nitro AN515-54              | [3953185e28](https://linux-hardware.org/?probe=3953185e28) | Dec 01, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [bd0ae5856a](https://linux-hardware.org/?probe=bd0ae5856a) | Nov 30, 2023 |
| HP            | Laptop 15-dw0xxx            | [e9e1177170](https://linux-hardware.org/?probe=e9e1177170) | Nov 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S4XW00    | [13a434ff63](https://linux-hardware.org/?probe=13a434ff63) | Nov 30, 2023 |
| HP            | EliteBook 840 G1            | [da1096c1ed](https://linux-hardware.org/?probe=da1096c1ed) | Nov 29, 2023 |
| Acer          | Aspire ES1-523              | [10c0db94d1](https://linux-hardware.org/?probe=10c0db94d1) | Nov 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [d0c3893980](https://linux-hardware.org/?probe=d0c3893980) | Nov 29, 2023 |
| Notebook      | P7xxTM                      | [d1a0cf0f45](https://linux-hardware.org/?probe=d1a0cf0f45) | Nov 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [6ccad5b430](https://linux-hardware.org/?probe=6ccad5b430) | Nov 28, 2023 |
| TECNO Mobi... | MEGABOOK T14TA              | [602741eba3](https://linux-hardware.org/?probe=602741eba3) | Nov 26, 2023 |
| Fujitsu       | LIFEBOOK E4511              | [a849237ab7](https://linux-hardware.org/?probe=a849237ab7) | Nov 26, 2023 |
| Shenzhen W... | Alder Lake N                | [0cd16ad752](https://linux-hardware.org/?probe=0cd16ad752) | Nov 25, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [5d6b4323e5](https://linux-hardware.org/?probe=5d6b4323e5) | Nov 24, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [2a29f65958](https://linux-hardware.org/?probe=2a29f65958) | Nov 24, 2023 |
| Gateway       | P-6301                      | [d16a00d10d](https://linux-hardware.org/?probe=d16a00d10d) | Nov 24, 2023 |
| Gateway       | P-6301                      | [d9c74ac6f8](https://linux-hardware.org/?probe=d9c74ac6f8) | Nov 24, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [1dea02682f](https://linux-hardware.org/?probe=1dea02682f) | Nov 24, 2023 |
| Acer          | Aspire A315-35              | [6115c9c76e](https://linux-hardware.org/?probe=6115c9c76e) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S9GM01    | [9c8590e300](https://linux-hardware.org/?probe=9c8590e300) | Nov 23, 2023 |
| Acer          | Aspire V5-573G              | [dea4d9231a](https://linux-hardware.org/?probe=dea4d9231a) | Nov 23, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [6f740bc140](https://linux-hardware.org/?probe=6f740bc140) | Nov 22, 2023 |
| Acer          | Aspire ES1-531              | [01d429e284](https://linux-hardware.org/?probe=01d429e284) | Nov 22, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [6791592808](https://linux-hardware.org/?probe=6791592808) | Nov 22, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [69d5dcd30b](https://linux-hardware.org/?probe=69d5dcd30b) | Nov 22, 2023 |
| HP            | EliteBook 8470p             | [40b88a9c74](https://linux-hardware.org/?probe=40b88a9c74) | Nov 21, 2023 |
| Google        | Pujjo                       | [a196388078](https://linux-hardware.org/?probe=a196388078) | Nov 21, 2023 |
| HP            | ProBook 635 Aero G8 Note... | [cb6bad64b4](https://linux-hardware.org/?probe=cb6bad64b4) | Nov 21, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [eb4b335400](https://linux-hardware.org/?probe=eb4b335400) | Nov 21, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [463f733cdb](https://linux-hardware.org/?probe=463f733cdb) | Nov 20, 2023 |
| MSI           | Thin GF63 12VF              | [ca1a9ef401](https://linux-hardware.org/?probe=ca1a9ef401) | Nov 20, 2023 |
| Apple         | MacBookPro9,2               | [828da99472](https://linux-hardware.org/?probe=828da99472) | Nov 20, 2023 |
| Alurin        | ALU-BAR-R555-000-156        | [ce453601f1](https://linux-hardware.org/?probe=ce453601f1) | Nov 19, 2023 |
| HP            | Pavilion dv6                | [15c38c7e03](https://linux-hardware.org/?probe=15c38c7e03) | Nov 19, 2023 |
| Acer          | Predator PH315-52           | [b53d35a567](https://linux-hardware.org/?probe=b53d35a567) | Nov 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [9fd0ad28e8](https://linux-hardware.org/?probe=9fd0ad28e8) | Nov 19, 2023 |
| Acer          | Aspire A315-35              | [78dac027a1](https://linux-hardware.org/?probe=78dac027a1) | Nov 19, 2023 |
| HP            | ProBook 440 G7              | [b3b8fff6bb](https://linux-hardware.org/?probe=b3b8fff6bb) | Nov 19, 2023 |
| HP            | Laptop 15-ef3xxx            | [196040012f](https://linux-hardware.org/?probe=196040012f) | Nov 18, 2023 |
| Acer          | Aspire A515-55              | [3ce3a10b05](https://linux-hardware.org/?probe=3ce3a10b05) | Nov 18, 2023 |
| Medion        | E4251 MD61435               | [01ea5c9a87](https://linux-hardware.org/?probe=01ea5c9a87) | Nov 17, 2023 |
| HP            | EliteBook 850 G6            | [fa0b8c4a6a](https://linux-hardware.org/?probe=fa0b8c4a6a) | Nov 17, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [75009bf512](https://linux-hardware.org/?probe=75009bf512) | Nov 17, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [492ee4603f](https://linux-hardware.org/?probe=492ee4603f) | Nov 15, 2023 |
| HUAWEI        | BOM-WXX9                    | [c4db182f7c](https://linux-hardware.org/?probe=c4db182f7c) | Nov 15, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [3394acc120](https://linux-hardware.org/?probe=3394acc120) | Nov 14, 2023 |
| Thomson       | N14C4WH64                   | [79fb5c8b87](https://linux-hardware.org/?probe=79fb5c8b87) | Nov 14, 2023 |
| HP            | EliteBook 8470p             | [a5def4d720](https://linux-hardware.org/?probe=a5def4d720) | Nov 14, 2023 |
| Timi          | Mi Laptop Pro 15 2020       | [ade278e9c7](https://linux-hardware.org/?probe=ade278e9c7) | Nov 13, 2023 |
| HUAWEI        | BOM-WXX9                    | [56107ca4c0](https://linux-hardware.org/?probe=56107ca4c0) | Nov 12, 2023 |
| HP            | EliteBook 8470p             | [87ddc0384e](https://linux-hardware.org/?probe=87ddc0384e) | Nov 11, 2023 |
| Acer          | Nitro AN515-51              | [bcbad28ab7](https://linux-hardware.org/?probe=bcbad28ab7) | Nov 11, 2023 |
| HP            | ZBook 17 G6                 | [c9f63fc134](https://linux-hardware.org/?probe=c9f63fc134) | Nov 11, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [4c87f0ac2c](https://linux-hardware.org/?probe=4c87f0ac2c) | Nov 10, 2023 |
| ASUSTek       | N56VB                       | [2b545ce55f](https://linux-hardware.org/?probe=2b545ce55f) | Nov 10, 2023 |
| HUAWEI        | KLVD-WXX9                   | [0de73c41cd](https://linux-hardware.org/?probe=0de73c41cd) | Nov 10, 2023 |
| Dell          | Inspiron 3543               | [0be0ae7171](https://linux-hardware.org/?probe=0be0ae7171) | Nov 09, 2023 |
| Apple         | MacBookPro6,2               | [c59084f5fe](https://linux-hardware.org/?probe=c59084f5fe) | Nov 09, 2023 |
| Apple         | MacBookPro6,2               | [0cdc1967cc](https://linux-hardware.org/?probe=0cdc1967cc) | Nov 09, 2023 |
| MSI           | Prestige 14Evo A12M         | [fc8b4307d1](https://linux-hardware.org/?probe=fc8b4307d1) | Nov 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [58c681b475](https://linux-hardware.org/?probe=58c681b475) | Nov 09, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [4a82e665de](https://linux-hardware.org/?probe=4a82e665de) | Nov 08, 2023 |
| Olivetti      | P55-AEU-323-4G320           | [5d53de5c7d](https://linux-hardware.org/?probe=5d53de5c7d) | Nov 08, 2023 |
| Maibenben     | MaiBook M                   | [2fb76b07c1](https://linux-hardware.org/?probe=2fb76b07c1) | Nov 08, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [da358e24b6](https://linux-hardware.org/?probe=da358e24b6) | Nov 07, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [895fc6adb6](https://linux-hardware.org/?probe=895fc6adb6) | Nov 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [5a5dbd719b](https://linux-hardware.org/?probe=5a5dbd719b) | Nov 07, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [d847f42603](https://linux-hardware.org/?probe=d847f42603) | Nov 07, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [752c83c717](https://linux-hardware.org/?probe=752c83c717) | Nov 07, 2023 |
| Acer          | Aspire A315-35              | [61fdbe9ec2](https://linux-hardware.org/?probe=61fdbe9ec2) | Nov 07, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [ed6ede63bc](https://linux-hardware.org/?probe=ed6ede63bc) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [7433f93679](https://linux-hardware.org/?probe=7433f93679) | Nov 07, 2023 |
| HP            | EliteBook 840 14 inch G9... | [09b818e1d3](https://linux-hardware.org/?probe=09b818e1d3) | Nov 07, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [437f0962bf](https://linux-hardware.org/?probe=437f0962bf) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e149cb0865](https://linux-hardware.org/?probe=e149cb0865) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [94fdbbd7bd](https://linux-hardware.org/?probe=94fdbbd7bd) | Nov 06, 2023 |
| Acer          | Aspire A515-51              | [5fafb134cf](https://linux-hardware.org/?probe=5fafb134cf) | Nov 06, 2023 |
| Dell          | Precision M4800             | [e67352eb0f](https://linux-hardware.org/?probe=e67352eb0f) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8e3e7668cf](https://linux-hardware.org/?probe=8e3e7668cf) | Nov 05, 2023 |
| HP            | 530                         | [710ba89827](https://linux-hardware.org/?probe=710ba89827) | Nov 05, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [3f295082ce](https://linux-hardware.org/?probe=3f295082ce) | Nov 05, 2023 |
| HP            | 255 G7 Notebook PC          | [bdd24f60d2](https://linux-hardware.org/?probe=bdd24f60d2) | Nov 05, 2023 |
| Apple         | MacBookPro10,1              | [8efb96e5d7](https://linux-hardware.org/?probe=8efb96e5d7) | Nov 04, 2023 |
| Apple         | MacBookPro10,1              | [e6459bb42f](https://linux-hardware.org/?probe=e6459bb42f) | Nov 04, 2023 |
| Dell          | XPS 13 9310                 | [5ff7f9b284](https://linux-hardware.org/?probe=5ff7f9b284) | Nov 04, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [ded1d73643](https://linux-hardware.org/?probe=ded1d73643) | Nov 03, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | [4d3101d9f8](https://linux-hardware.org/?probe=4d3101d9f8) | Nov 02, 2023 |
| Acer          | Predator PH315-53           | [476a922e2f](https://linux-hardware.org/?probe=476a922e2f) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480 20L60017UK    | [e8b030e97f](https://linux-hardware.org/?probe=e8b030e97f) | Nov 02, 2023 |
| Gigabyte      | AORUS 17G KD                | [ac471f8580](https://linux-hardware.org/?probe=ac471f8580) | Nov 02, 2023 |
| Lenovo        | G40-45 80E1                 | [fffa5fb420](https://linux-hardware.org/?probe=fffa5fb420) | Nov 02, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | [fab360eece](https://linux-hardware.org/?probe=fab360eece) | Nov 02, 2023 |
| Panasonic     | CF-54-1                     | [b7d7cde99a](https://linux-hardware.org/?probe=b7d7cde99a) | Nov 01, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [a7f47546e5](https://linux-hardware.org/?probe=a7f47546e5) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [d64009bcc1](https://linux-hardware.org/?probe=d64009bcc1) | Nov 01, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [8901bca741](https://linux-hardware.org/?probe=8901bca741) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [f5d0c4d34a](https://linux-hardware.org/?probe=f5d0c4d34a) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [0a7341e5e0](https://linux-hardware.org/?probe=0a7341e5e0) | Nov 01, 2023 |
| Dell          | Precision 5550              | [87a9861125](https://linux-hardware.org/?probe=87a9861125) | Nov 01, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | [a2273dea0e](https://linux-hardware.org/?probe=a2273dea0e) | Nov 01, 2023 |
| ASUSTek       | N56VB                       | [9775caad00](https://linux-hardware.org/?probe=9775caad00) | Oct 31, 2023 |
| ASUSTek       | N56VB                       | [45280b44d0](https://linux-hardware.org/?probe=45280b44d0) | Oct 31, 2023 |
| Dell          | XPS 15 9510                 | [d370c488e4](https://linux-hardware.org/?probe=d370c488e4) | Oct 31, 2023 |
| Acer          | Aspire A315-35              | [c26ec81fab](https://linux-hardware.org/?probe=c26ec81fab) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [ed27ef3491](https://linux-hardware.org/?probe=ed27ef3491) | Oct 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [9dd62a1bb2](https://linux-hardware.org/?probe=9dd62a1bb2) | Oct 31, 2023 |
| TECNO         | MEGABOOK T1                 | [2bab6515f4](https://linux-hardware.org/?probe=2bab6515f4) | Oct 30, 2023 |
| Dell          | Latitude 7370               | [f47b42c0b0](https://linux-hardware.org/?probe=f47b42c0b0) | Oct 30, 2023 |
| Sony          | SVE1511B1RB                 | [74651497a9](https://linux-hardware.org/?probe=74651497a9) | Oct 30, 2023 |
| ASUSTek       | K84L                        | [e6d103b3e4](https://linux-hardware.org/?probe=e6d103b3e4) | Oct 29, 2023 |
| Dell          | Latitude E5400              | [169d73bee0](https://linux-hardware.org/?probe=169d73bee0) | Oct 28, 2023 |
| HUAWEI        | MACHD-WXX9                  | [551a5c8aa2](https://linux-hardware.org/?probe=551a5c8aa2) | Oct 28, 2023 |
| HP            | Notebook                    | [715435e533](https://linux-hardware.org/?probe=715435e533) | Oct 28, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [b7f872ea23](https://linux-hardware.org/?probe=b7f872ea23) | Oct 27, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [755d25d933](https://linux-hardware.org/?probe=755d25d933) | Oct 26, 2023 |
| Gigabyte      | AERO 17 XE5                 | [47d1cb500e](https://linux-hardware.org/?probe=47d1cb500e) | Oct 25, 2023 |
| Acer          | Aspire A515-57G             | [d61428d56d](https://linux-hardware.org/?probe=d61428d56d) | Oct 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [1bd81ebf81](https://linux-hardware.org/?probe=1bd81ebf81) | Oct 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S4M20... | [799084c1a9](https://linux-hardware.org/?probe=799084c1a9) | Oct 23, 2023 |
| HP            | Laptop 17-cp0xxx            | [1a97d77c76](https://linux-hardware.org/?probe=1a97d77c76) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [bd89e392d1](https://linux-hardware.org/?probe=bd89e392d1) | Oct 23, 2023 |
| HP            | EliteBook 8470p             | [c927a93a85](https://linux-hardware.org/?probe=c927a93a85) | Oct 23, 2023 |
| Google        | Gandof                      | [7a07edf626](https://linux-hardware.org/?probe=7a07edf626) | Oct 23, 2023 |
| HP            | EliteBook 8470p             | [bebe071d7c](https://linux-hardware.org/?probe=bebe071d7c) | Oct 23, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [93043f297f](https://linux-hardware.org/?probe=93043f297f) | Oct 22, 2023 |
| Acer          | Aspire A315-35              | [ee15c1dbea](https://linux-hardware.org/?probe=ee15c1dbea) | Oct 22, 2023 |
| Apple         | MacBookPro8,1               | [fde726622c](https://linux-hardware.org/?probe=fde726622c) | Oct 22, 2023 |
| Apple         | MacBookPro8,1               | [116946c81c](https://linux-hardware.org/?probe=116946c81c) | Oct 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [43f9375597](https://linux-hardware.org/?probe=43f9375597) | Oct 21, 2023 |
| MSI           | GL62VR 7RFX                 | [0d88fb381c](https://linux-hardware.org/?probe=0d88fb381c) | Oct 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9403CVA... | [eaffd30f59](https://linux-hardware.org/?probe=eaffd30f59) | Oct 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9403CVA... | [aafd893b0d](https://linux-hardware.org/?probe=aafd893b0d) | Oct 21, 2023 |
| HP            | Laptop 14-ck0xxx            | [8ef0f47332](https://linux-hardware.org/?probe=8ef0f47332) | Oct 20, 2023 |
| Eluktronic... | MECH-15 G3                  | [1b63389cc6](https://linux-hardware.org/?probe=1b63389cc6) | Oct 20, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [79a2d6de1a](https://linux-hardware.org/?probe=79a2d6de1a) | Oct 19, 2023 |
| Lenovo        | Legion R7000P APH8 82Y9     | [9c6fb34bab](https://linux-hardware.org/?probe=9c6fb34bab) | Oct 18, 2023 |
| Lenovo        | Legion 5 82B5               | [fecce40ebb](https://linux-hardware.org/?probe=fecce40ebb) | Oct 18, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [9729d18e10](https://linux-hardware.org/?probe=9729d18e10) | Oct 16, 2023 |
| Acer          | Aspire ES1-523              | [6f80d0517c](https://linux-hardware.org/?probe=6f80d0517c) | Oct 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0504910ad7](https://linux-hardware.org/?probe=0504910ad7) | Oct 16, 2023 |
| Acer          | Aspire ES1-523              | [2dfea2666c](https://linux-hardware.org/?probe=2dfea2666c) | Oct 15, 2023 |
| Clevo         | W150ER                      | [e119814a32](https://linux-hardware.org/?probe=e119814a32) | Oct 14, 2023 |
| HP            | 15                          | [f5392b4484](https://linux-hardware.org/?probe=f5392b4484) | Oct 14, 2023 |
| HP            | Pavilion dv7                | [ae2789f31f](https://linux-hardware.org/?probe=ae2789f31f) | Oct 14, 2023 |
| HP            | Pavilion dv7                | [de47e931a1](https://linux-hardware.org/?probe=de47e931a1) | Oct 14, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [39e3632f1f](https://linux-hardware.org/?probe=39e3632f1f) | Oct 11, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [b1b0f03790](https://linux-hardware.org/?probe=b1b0f03790) | Oct 11, 2023 |
| HP            | EliteBook 8560w             | [00580f0c7d](https://linux-hardware.org/?probe=00580f0c7d) | Oct 10, 2023 |
| HP            | EliteBook 8560w             | [6e046b22c3](https://linux-hardware.org/?probe=6e046b22c3) | Oct 10, 2023 |
| Lenovo        | G40-45 80E1                 | [1bb42f8755](https://linux-hardware.org/?probe=1bb42f8755) | Oct 09, 2023 |
| Gateway       | NV57H                       | [141355e1e3](https://linux-hardware.org/?probe=141355e1e3) | Oct 09, 2023 |
| HUAWEI        | HN-WX9X                     | [a46f5ac57a](https://linux-hardware.org/?probe=a46f5ac57a) | Oct 09, 2023 |
| Dell          | Vostro 7590                 | [d7188e68cb](https://linux-hardware.org/?probe=d7188e68cb) | Oct 08, 2023 |
| Dell          | Precision 7710              | [6dcd757659](https://linux-hardware.org/?probe=6dcd757659) | Oct 07, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [da6b1b88e6](https://linux-hardware.org/?probe=da6b1b88e6) | Oct 06, 2023 |
| Acer          | Aspire ES1-732              | [9f011f4756](https://linux-hardware.org/?probe=9f011f4756) | Oct 04, 2023 |
| Acer          | Nitro AN515-44              | [faf6d73cad](https://linux-hardware.org/?probe=faf6d73cad) | Oct 04, 2023 |
| HP            | Laptop 14-ck0xxx            | [c41cd8be8e](https://linux-hardware.org/?probe=c41cd8be8e) | Oct 03, 2023 |
| Lenovo        | ThinkPad L430 24662W2       | [21ee2a6e8f](https://linux-hardware.org/?probe=21ee2a6e8f) | Oct 03, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | [ad3d8f3522](https://linux-hardware.org/?probe=ad3d8f3522) | Oct 02, 2023 |
| Lenovo        | ThinkPad T420s 4170CTO      | [f141fc2bd7](https://linux-hardware.org/?probe=f141fc2bd7) | Oct 02, 2023 |
| Dell          | Precision 5480              | [21bd104767](https://linux-hardware.org/?probe=21bd104767) | Oct 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4e0bb2d740](https://linux-hardware.org/?probe=4e0bb2d740) | Oct 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [840bfbb2cb](https://linux-hardware.org/?probe=840bfbb2cb) | Oct 01, 2023 |
| HUAWEI        | VLT-WX0                     | [6778af4012](https://linux-hardware.org/?probe=6778af4012) | Oct 01, 2023 |
| Dell          | G7 7700                     | [62bd529b36](https://linux-hardware.org/?probe=62bd529b36) | Oct 01, 2023 |
| HUAWEI        | MateBook X                  | [5479e52948](https://linux-hardware.org/?probe=5479e52948) | Oct 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [2d1ada9dbe](https://linux-hardware.org/?probe=2d1ada9dbe) | Sep 30, 2023 |
| Dell          | Precision 7710              | [89731f9b0e](https://linux-hardware.org/?probe=89731f9b0e) | Sep 29, 2023 |
| Acer          | Nitro AN515-43              | [e55a394d41](https://linux-hardware.org/?probe=e55a394d41) | Sep 29, 2023 |
| Lenovo        | ThinkPad X260 20F60097US    | [607d788fde](https://linux-hardware.org/?probe=607d788fde) | Sep 28, 2023 |
| Acer          | Aspire ES1-732              | [f30d62d67b](https://linux-hardware.org/?probe=f30d62d67b) | Sep 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | [4c1a2e1e21](https://linux-hardware.org/?probe=4c1a2e1e21) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | [3ee705f2f3](https://linux-hardware.org/?probe=3ee705f2f3) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | [2b86c9fac4](https://linux-hardware.org/?probe=2b86c9fac4) | Sep 28, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [0dcef3e6c3](https://linux-hardware.org/?probe=0dcef3e6c3) | Sep 27, 2023 |
| Dell          | Inspiron N5040              | [c48d158b62](https://linux-hardware.org/?probe=c48d158b62) | Sep 27, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [84ad07c3f9](https://linux-hardware.org/?probe=84ad07c3f9) | Sep 27, 2023 |
| Packard Be... | EasyNote TK85               | [79e6dd1302](https://linux-hardware.org/?probe=79e6dd1302) | Sep 27, 2023 |
| Google        | Blorb                       | [efa4ad9e2c](https://linux-hardware.org/?probe=efa4ad9e2c) | Sep 26, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [3b76e2cd65](https://linux-hardware.org/?probe=3b76e2cd65) | Sep 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [124f7a0f29](https://linux-hardware.org/?probe=124f7a0f29) | Sep 26, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [381be3d212](https://linux-hardware.org/?probe=381be3d212) | Sep 25, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [508cf38973](https://linux-hardware.org/?probe=508cf38973) | Sep 24, 2023 |
| HP            | ENVY m4                     | [8d7da36940](https://linux-hardware.org/?probe=8d7da36940) | Sep 24, 2023 |
| HP            | Laptop 15-ef2xxx            | [4fb741bdb3](https://linux-hardware.org/?probe=4fb741bdb3) | Sep 23, 2023 |
| Packard Be... | EasyNote TK85               | [c970ee5a12](https://linux-hardware.org/?probe=c970ee5a12) | Sep 23, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [14d87bfb5d](https://linux-hardware.org/?probe=14d87bfb5d) | Sep 22, 2023 |
| Fujitsu       | LIFEBOOK E752               | [c2d2a28c33](https://linux-hardware.org/?probe=c2d2a28c33) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | [ae7455bac3](https://linux-hardware.org/?probe=ae7455bac3) | Sep 21, 2023 |
| Dell          | Precision 7520              | [2fd68ca236](https://linux-hardware.org/?probe=2fd68ca236) | Sep 21, 2023 |
| Dell          | Inspiron 3542               | [b449a82c4f](https://linux-hardware.org/?probe=b449a82c4f) | Sep 21, 2023 |
| Dell          | Latitude E5430 non-vPro     | [192f065f70](https://linux-hardware.org/?probe=192f065f70) | Sep 21, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [063f211c4d](https://linux-hardware.org/?probe=063f211c4d) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | [6337af2f4c](https://linux-hardware.org/?probe=6337af2f4c) | Sep 20, 2023 |
| ASUSTek       | Z450UA                      | [60d85e59da](https://linux-hardware.org/?probe=60d85e59da) | Sep 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [00c6b8cced](https://linux-hardware.org/?probe=00c6b8cced) | Sep 20, 2023 |
| Chuwi         | GemiBook Pro                | [d8305c7c45](https://linux-hardware.org/?probe=d8305c7c45) | Sep 20, 2023 |
| Lenovo        | ThinkPad T450 20BUS0H200    | [c38151f281](https://linux-hardware.org/?probe=c38151f281) | Sep 20, 2023 |
| Chuwi         | GemiBook Pro                | [7ff48f538f](https://linux-hardware.org/?probe=7ff48f538f) | Sep 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [286398db3c](https://linux-hardware.org/?probe=286398db3c) | Sep 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [ad024119be](https://linux-hardware.org/?probe=ad024119be) | Sep 19, 2023 |
| HP            | 255 G8 Notebook PC          | [c2cd300139](https://linux-hardware.org/?probe=c2cd300139) | Sep 19, 2023 |
| Acer          | Aspire E5-774G              | [19e013b8e8](https://linux-hardware.org/?probe=19e013b8e8) | Sep 18, 2023 |
| Lenovo        | G40-45 80E1                 | [417ad95c4c](https://linux-hardware.org/?probe=417ad95c4c) | Sep 18, 2023 |
| Razer         | Blade 15 Base Model (Lat... | [15dd923faa](https://linux-hardware.org/?probe=15dd923faa) | Sep 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [10709d2c51](https://linux-hardware.org/?probe=10709d2c51) | Sep 17, 2023 |
| Acer          | Nitro AN515-44              | [a25ee31882](https://linux-hardware.org/?probe=a25ee31882) | Sep 17, 2023 |
| Apple         | MacBookPro9,2               | [b8459514db](https://linux-hardware.org/?probe=b8459514db) | Sep 17, 2023 |
| Lenovo        | G40-45 80E1                 | [c27b81ea3e](https://linux-hardware.org/?probe=c27b81ea3e) | Sep 17, 2023 |
| Razer         | Blade 15 Base Model (Lat... | [2e5c8bb8ed](https://linux-hardware.org/?probe=2e5c8bb8ed) | Sep 17, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [0ebcb848ff](https://linux-hardware.org/?probe=0ebcb848ff) | Sep 16, 2023 |
| Acer          | Aspire E1-522               | [cbc5e29bf6](https://linux-hardware.org/?probe=cbc5e29bf6) | Sep 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [567443136d](https://linux-hardware.org/?probe=567443136d) | Sep 15, 2023 |
| MSI           | Modern 15 B7M               | [4d35879250](https://linux-hardware.org/?probe=4d35879250) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | [2073aca95d](https://linux-hardware.org/?probe=2073aca95d) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | [fa484cf261](https://linux-hardware.org/?probe=fa484cf261) | Sep 15, 2023 |
| HUAWEI        | HKD-WXX                     | [4d0eb9b8d2](https://linux-hardware.org/?probe=4d0eb9b8d2) | Sep 15, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [bc597f4c0c](https://linux-hardware.org/?probe=bc597f4c0c) | Sep 14, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [5d79965e45](https://linux-hardware.org/?probe=5d79965e45) | Sep 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1703cfdd5e](https://linux-hardware.org/?probe=1703cfdd5e) | Sep 13, 2023 |
| Dell          | Latitude 7410               | [59abc2d869](https://linux-hardware.org/?probe=59abc2d869) | Sep 12, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [d4e392a0ad](https://linux-hardware.org/?probe=d4e392a0ad) | Sep 12, 2023 |
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | [9506117d6f](https://linux-hardware.org/?probe=9506117d6f) | Sep 12, 2023 |
| HP            | 620                         | [59577ac122](https://linux-hardware.org/?probe=59577ac122) | Sep 12, 2023 |
| HP            | 250 G7 Notebook PC          | [6a7ee91a3f](https://linux-hardware.org/?probe=6a7ee91a3f) | Sep 11, 2023 |
| ASUSTek       | GL553VW                     | [3859055e8d](https://linux-hardware.org/?probe=3859055e8d) | Sep 11, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [667560b69c](https://linux-hardware.org/?probe=667560b69c) | Sep 11, 2023 |
| Toshiba       | Satellite M645              | [40c02e9bc9](https://linux-hardware.org/?probe=40c02e9bc9) | Sep 10, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [6b9804a536](https://linux-hardware.org/?probe=6b9804a536) | Sep 10, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [d824341957](https://linux-hardware.org/?probe=d824341957) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [3021f551f4](https://linux-hardware.org/?probe=3021f551f4) | Sep 09, 2023 |
| HUAWEI        | HKD-WXX                     | [524bbba65a](https://linux-hardware.org/?probe=524bbba65a) | Sep 09, 2023 |
| MSI           | GP75 Leopard 10SEK          | [11e5581873](https://linux-hardware.org/?probe=11e5581873) | Sep 08, 2023 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | [650c9dbdd3](https://linux-hardware.org/?probe=650c9dbdd3) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [699fb7e97e](https://linux-hardware.org/?probe=699fb7e97e) | Sep 07, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [84368e642c](https://linux-hardware.org/?probe=84368e642c) | Sep 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | [6c4c9936b0](https://linux-hardware.org/?probe=6c4c9936b0) | Sep 06, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [89ce951011](https://linux-hardware.org/?probe=89ce951011) | Sep 05, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [ca342c2a7e](https://linux-hardware.org/?probe=ca342c2a7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad T430 2349KQ3       | [287ea35176](https://linux-hardware.org/?probe=287ea35176) | Sep 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [945acb9ea2](https://linux-hardware.org/?probe=945acb9ea2) | Sep 04, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [24a7c8a496](https://linux-hardware.org/?probe=24a7c8a496) | Sep 04, 2023 |
| MSI           | Prestige 14Evo A12M         | [d7b4b0f2f1](https://linux-hardware.org/?probe=d7b4b0f2f1) | Sep 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [8146fce36b](https://linux-hardware.org/?probe=8146fce36b) | Sep 03, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [7ebd20a049](https://linux-hardware.org/?probe=7ebd20a049) | Sep 03, 2023 |
| Notebook      | NK50S5_SZ                   | [f0718be353](https://linux-hardware.org/?probe=f0718be353) | Sep 03, 2023 |
| Google        | Galtic                      | [e9ccd3a286](https://linux-hardware.org/?probe=e9ccd3a286) | Sep 01, 2023 |
| Acer          | Aspire 5715Z                | [1cb91dff9e](https://linux-hardware.org/?probe=1cb91dff9e) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | [e9f211faf1](https://linux-hardware.org/?probe=e9f211faf1) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | [b1a3900bdd](https://linux-hardware.org/?probe=b1a3900bdd) | Sep 01, 2023 |
| BANGHO        | GM-15Z12 RTX3060 i7         | [4e77460452](https://linux-hardware.org/?probe=4e77460452) | Aug 31, 2023 |
| Acer          | Aspire E5-774G              | [0e6c0b300b](https://linux-hardware.org/?probe=0e6c0b300b) | Aug 31, 2023 |
| Lenovo        | V17 G4 IRU 83A2             | [a5fd9c62e8](https://linux-hardware.org/?probe=a5fd9c62e8) | Aug 30, 2023 |
| ASUSTek       | P552LA                      | [6eca0a231c](https://linux-hardware.org/?probe=6eca0a231c) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop      | [c9fa671277](https://linux-hardware.org/?probe=c9fa671277) | Aug 29, 2023 |
| GPU Compan... | GWNC21524                   | [4a38e28073](https://linux-hardware.org/?probe=4a38e28073) | Aug 29, 2023 |
| GPD           | G1619-01                    | [0e12028a4d](https://linux-hardware.org/?probe=0e12028a4d) | Aug 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | [d0453c59f5](https://linux-hardware.org/?probe=d0453c59f5) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [efc8be8369](https://linux-hardware.org/?probe=efc8be8369) | Aug 28, 2023 |
| HUAWEI        | CREF-XX                     | [2d9703804d](https://linux-hardware.org/?probe=2d9703804d) | Aug 27, 2023 |
| Lenovo        | Legion 5 82B5               | [c154878ecd](https://linux-hardware.org/?probe=c154878ecd) | Aug 26, 2023 |
| HP            | ProBook 450 15.6 inch G1... | [973d7867a4](https://linux-hardware.org/?probe=973d7867a4) | Aug 26, 2023 |
| Lenovo        | ThinkPad T430 2349KAG       | [f2348b8eee](https://linux-hardware.org/?probe=f2348b8eee) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [24c8bedd43](https://linux-hardware.org/?probe=24c8bedd43) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [d31df9053b](https://linux-hardware.org/?probe=d31df9053b) | Aug 23, 2023 |
| Gigabyte      | G5 MD                       | [74fe0374b3](https://linux-hardware.org/?probe=74fe0374b3) | Aug 23, 2023 |
| Dell          | XPS 15 9550                 | [3c5cdd0318](https://linux-hardware.org/?probe=3c5cdd0318) | Aug 23, 2023 |
| Dell          | Inspiron 3583               | [69d3db7d28](https://linux-hardware.org/?probe=69d3db7d28) | Aug 23, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [3231dcefb4](https://linux-hardware.org/?probe=3231dcefb4) | Aug 22, 2023 |
| Dell          | Latitude E6430              | [839ae55173](https://linux-hardware.org/?probe=839ae55173) | Aug 21, 2023 |
| Lenovo        | ThinkPad L430 24662W2       | [10b7d76c38](https://linux-hardware.org/?probe=10b7d76c38) | Aug 20, 2023 |
| Dell          | Latitude E6430              | [4fc5a7442a](https://linux-hardware.org/?probe=4fc5a7442a) | Aug 20, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [f8c85e442f](https://linux-hardware.org/?probe=f8c85e442f) | Aug 19, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | [47b747684d](https://linux-hardware.org/?probe=47b747684d) | Aug 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [540a2db767](https://linux-hardware.org/?probe=540a2db767) | Aug 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [99b060481a](https://linux-hardware.org/?probe=99b060481a) | Aug 18, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | [753e0098e5](https://linux-hardware.org/?probe=753e0098e5) | Aug 17, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [3b6cc87ac7](https://linux-hardware.org/?probe=3b6cc87ac7) | Aug 17, 2023 |
| HP            | ProBook 4540s               | [c965074769](https://linux-hardware.org/?probe=c965074769) | Aug 17, 2023 |
| Packard Be... | EasyNote ENTG81BA           | [086cffe9b9](https://linux-hardware.org/?probe=086cffe9b9) | Aug 16, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [e9690dda8e](https://linux-hardware.org/?probe=e9690dda8e) | Aug 16, 2023 |
| MSI           | GS60 6QE                    | [3372d46d8c](https://linux-hardware.org/?probe=3372d46d8c) | Aug 16, 2023 |
| HP            | 15                          | [9b9e2459a8](https://linux-hardware.org/?probe=9b9e2459a8) | Aug 15, 2023 |
| Packard Be... | EasyNote TK85               | [214e2092c6](https://linux-hardware.org/?probe=214e2092c6) | Aug 15, 2023 |
| ASUSTek       | N76VZ                       | [639ec473a1](https://linux-hardware.org/?probe=639ec473a1) | Aug 15, 2023 |
| Razer         | Blade 17 (Mid 2021) - RZ... | [a14844e2b4](https://linux-hardware.org/?probe=a14844e2b4) | Aug 14, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [076c807d2d](https://linux-hardware.org/?probe=076c807d2d) | Aug 14, 2023 |
| HP            | OMEN by Laptop              | [e0e2f927ae](https://linux-hardware.org/?probe=e0e2f927ae) | Aug 13, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | [f709dd85f7](https://linux-hardware.org/?probe=f709dd85f7) | Aug 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [fe5f1d5c1b](https://linux-hardware.org/?probe=fe5f1d5c1b) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1d5206dc94](https://linux-hardware.org/?probe=1d5206dc94) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [79cc445925](https://linux-hardware.org/?probe=79cc445925) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [b9d1b6d44a](https://linux-hardware.org/?probe=b9d1b6d44a) | Aug 12, 2023 |
| HP            | Laptop 14-dq1xxx            | [6f5a32d65f](https://linux-hardware.org/?probe=6f5a32d65f) | Aug 11, 2023 |
| Acer          | TMP255-M                    | [0b1adaea4e](https://linux-hardware.org/?probe=0b1adaea4e) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | [49a3480efb](https://linux-hardware.org/?probe=49a3480efb) | Aug 11, 2023 |
| Positivo      | Presley 3                   | [16ddbd1a75](https://linux-hardware.org/?probe=16ddbd1a75) | Aug 10, 2023 |
| Positivo      | Presley 3                   | [9edde2ea30](https://linux-hardware.org/?probe=9edde2ea30) | Aug 09, 2023 |
| Chuwi         | GemiBook Pro                | [3702186068](https://linux-hardware.org/?probe=3702186068) | Aug 08, 2023 |
| Lenovo        | ThinkPad T440 20B7S4NV07    | [af7992a11e](https://linux-hardware.org/?probe=af7992a11e) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | [77f61b77f5](https://linux-hardware.org/?probe=77f61b77f5) | Aug 08, 2023 |
| Lenovo        | ThinkPad X230 2324BV7       | [e1f092d38b](https://linux-hardware.org/?probe=e1f092d38b) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | [fa4f74161f](https://linux-hardware.org/?probe=fa4f74161f) | Aug 08, 2023 |
| ASUSTek       | N550LF                      | [57f7da9570](https://linux-hardware.org/?probe=57f7da9570) | Aug 08, 2023 |
| Jumper        | QCYL-200                    | [24da6190dc](https://linux-hardware.org/?probe=24da6190dc) | Aug 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b73a01acaf](https://linux-hardware.org/?probe=b73a01acaf) | Aug 07, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [9094c29548](https://linux-hardware.org/?probe=9094c29548) | Aug 07, 2023 |
| Dell          | Vostro 3480                 | [78fbe42595](https://linux-hardware.org/?probe=78fbe42595) | Aug 07, 2023 |
| Acer          | Aspire E5-553G              | [f7845429c8](https://linux-hardware.org/?probe=f7845429c8) | Aug 07, 2023 |
| Dell          | Latitude 5480               | [f3f7a29ca0](https://linux-hardware.org/?probe=f3f7a29ca0) | Aug 07, 2023 |
| Dell          | Inspiron 15 3525            | [36a20bb009](https://linux-hardware.org/?probe=36a20bb009) | Aug 07, 2023 |
| HUAWEI        | KPRC-WX0                    | [f84c568d4b](https://linux-hardware.org/?probe=f84c568d4b) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [f2d72fe710](https://linux-hardware.org/?probe=f2d72fe710) | Aug 07, 2023 |
| Acer          | Aspire A514-54              | [e9dfd6bbb6](https://linux-hardware.org/?probe=e9dfd6bbb6) | Aug 06, 2023 |
| Acer          | Aspire A514-54              | [0a7dc12f31](https://linux-hardware.org/?probe=0a7dc12f31) | Aug 06, 2023 |
| HP            | 250 G6 Notebook PC          | [c130dece41](https://linux-hardware.org/?probe=c130dece41) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | [a58ca66b2f](https://linux-hardware.org/?probe=a58ca66b2f) | Aug 06, 2023 |
| Dell          | XPS 15 7590                 | [6a53759849](https://linux-hardware.org/?probe=6a53759849) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | [52bf9ffa35](https://linux-hardware.org/?probe=52bf9ffa35) | Aug 06, 2023 |
| Acer          | Aspire A317-53              | [5bb0feab0c](https://linux-hardware.org/?probe=5bb0feab0c) | Aug 06, 2023 |
| Lenovo        | B330-15IKBR 81M1            | [f03fa524d7](https://linux-hardware.org/?probe=f03fa524d7) | Aug 05, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [5e28b5b07a](https://linux-hardware.org/?probe=5e28b5b07a) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [6fd7ffb05b](https://linux-hardware.org/?probe=6fd7ffb05b) | Aug 04, 2023 |
| SANTECH       | NL5xNU                      | [68d1f62251](https://linux-hardware.org/?probe=68d1f62251) | Aug 04, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [0f5b976e39](https://linux-hardware.org/?probe=0f5b976e39) | Aug 02, 2023 |
| Dell          | Inspiron 5566               | [c4e404738e](https://linux-hardware.org/?probe=c4e404738e) | Aug 01, 2023 |
| Apple         | MacBookPro8,1               | [56e2fa207e](https://linux-hardware.org/?probe=56e2fa207e) | Aug 01, 2023 |
| Lenovo        | B330-15IKBR 81M1            | [1f69ed5c1e](https://linux-hardware.org/?probe=1f69ed5c1e) | Aug 01, 2023 |
| TUXEDO        | N7x0WU                      | [05c525a9a7](https://linux-hardware.org/?probe=05c525a9a7) | Jul 31, 2023 |
| HP            | ProBook 4740s               | [d0aae87145](https://linux-hardware.org/?probe=d0aae87145) | Jul 31, 2023 |
| HP            | ProBook 4740s               | [985ee4b495](https://linux-hardware.org/?probe=985ee4b495) | Jul 30, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [1fe8eab1c6](https://linux-hardware.org/?probe=1fe8eab1c6) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | [c8391bd952](https://linux-hardware.org/?probe=c8391bd952) | Jul 29, 2023 |
| HP            | Laptop 17-cn0xxx            | [d23aa8f750](https://linux-hardware.org/?probe=d23aa8f750) | Jul 29, 2023 |
| Dell          | XPS 17 9720                 | [1006fe2c7b](https://linux-hardware.org/?probe=1006fe2c7b) | Jul 29, 2023 |
| Dell          | Inspiron N4050              | [701402e2a7](https://linux-hardware.org/?probe=701402e2a7) | Jul 29, 2023 |
| Dell          | XPS 15 9500                 | [151b7d8d31](https://linux-hardware.org/?probe=151b7d8d31) | Jul 29, 2023 |
| Lenovo        | ThinkPad T420 4180C31       | [7fafc1656d](https://linux-hardware.org/?probe=7fafc1656d) | Jul 28, 2023 |
| Lenovo        | ThinkPad E575 20H8S02W00    | [afde3ea804](https://linux-hardware.org/?probe=afde3ea804) | Jul 28, 2023 |
| HP            | EliteBook 2540p             | [cedff6ca6f](https://linux-hardware.org/?probe=cedff6ca6f) | Jul 28, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [c51105da6a](https://linux-hardware.org/?probe=c51105da6a) | Jul 28, 2023 |
| Valve         | Jupiter                     | [b32778a4bd](https://linux-hardware.org/?probe=b32778a4bd) | Jul 28, 2023 |
| Google        | Blooglet                    | [d8c14e29b6](https://linux-hardware.org/?probe=d8c14e29b6) | Jul 27, 2023 |
| Acer          | TMP255-M                    | [25d376a674](https://linux-hardware.org/?probe=25d376a674) | Jul 26, 2023 |
| Dell          | Latitude E5430 non-vPro     | [b5b201f80a](https://linux-hardware.org/?probe=b5b201f80a) | Jul 26, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [784b86f367](https://linux-hardware.org/?probe=784b86f367) | Jul 25, 2023 |
| MSI           | Prestige 14Evo A12M         | [4872d1fdf6](https://linux-hardware.org/?probe=4872d1fdf6) | Jul 25, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [9acc2dda36](https://linux-hardware.org/?probe=9acc2dda36) | Jul 25, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [346055ca33](https://linux-hardware.org/?probe=346055ca33) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [5262229deb](https://linux-hardware.org/?probe=5262229deb) | Jul 25, 2023 |
| Acer          | TMP255-M                    | [c4bfc82a98](https://linux-hardware.org/?probe=c4bfc82a98) | Jul 24, 2023 |
| Acer          | TMP255-M                    | [7a57ee89af](https://linux-hardware.org/?probe=7a57ee89af) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [7a6a20b8ed](https://linux-hardware.org/?probe=7a6a20b8ed) | Jul 23, 2023 |
| Medion        | E4251 MD61435               | [4cd0b97344](https://linux-hardware.org/?probe=4cd0b97344) | Jul 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [46218bae31](https://linux-hardware.org/?probe=46218bae31) | Jul 23, 2023 |
| Dell          | Vostro 3578                 | [bd32828bf5](https://linux-hardware.org/?probe=bd32828bf5) | Jul 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [7a3abd2e4d](https://linux-hardware.org/?probe=7a3abd2e4d) | Jul 22, 2023 |
| HP            | ZBook 15 G2                 | [1c164d4bc9](https://linux-hardware.org/?probe=1c164d4bc9) | Jul 21, 2023 |
| ASUSTek       | GL702VM                     | [f2a5e69f00](https://linux-hardware.org/?probe=f2a5e69f00) | Jul 20, 2023 |
| Acer          | Predator PH315-53           | [3d0b2577a1](https://linux-hardware.org/?probe=3d0b2577a1) | Jul 18, 2023 |
| HONOR         | BBR-WAX9                    | [b098dc2f61](https://linux-hardware.org/?probe=b098dc2f61) | Jul 17, 2023 |
| HP            | Laptop 17-cn0xxx            | [e2973a88aa](https://linux-hardware.org/?probe=e2973a88aa) | Jul 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b0c8aaef19](https://linux-hardware.org/?probe=b0c8aaef19) | Jul 16, 2023 |
| HP            | ZBook 15 G4                 | [ad6ff2b754](https://linux-hardware.org/?probe=ad6ff2b754) | Jul 16, 2023 |
| ASUSTek       | X75A1                       | [745ef2a79f](https://linux-hardware.org/?probe=745ef2a79f) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | [d06ca4b9c2](https://linux-hardware.org/?probe=d06ca4b9c2) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | [103e7e5196](https://linux-hardware.org/?probe=103e7e5196) | Jul 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [5e43c9d869](https://linux-hardware.org/?probe=5e43c9d869) | Jul 15, 2023 |
| Acer          | Aspire A515-41G             | [a9cb1108f6](https://linux-hardware.org/?probe=a9cb1108f6) | Jul 15, 2023 |
| Acer          | Aspire A515-43              | [6b86cc4c89](https://linux-hardware.org/?probe=6b86cc4c89) | Jul 15, 2023 |
| HP            | Laptop 17-cn0xxx            | [479e8276b4](https://linux-hardware.org/?probe=479e8276b4) | Jul 15, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [567736ec02](https://linux-hardware.org/?probe=567736ec02) | Jul 14, 2023 |
| Acer          | Nitro AN515-55              | [c9a21bf55e](https://linux-hardware.org/?probe=c9a21bf55e) | Jul 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [be15faa71b](https://linux-hardware.org/?probe=be15faa71b) | Jul 14, 2023 |
| HP            | EliteBook 840 14 inch G9... | [4b9cba03ac](https://linux-hardware.org/?probe=4b9cba03ac) | Jul 13, 2023 |
| Acer          | Aspire E5-774G              | [7f06f99146](https://linux-hardware.org/?probe=7f06f99146) | Jul 13, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [e69bd50c8e](https://linux-hardware.org/?probe=e69bd50c8e) | Jul 13, 2023 |
| ASUSTek       | X456UV                      | [b0a9e3905f](https://linux-hardware.org/?probe=b0a9e3905f) | Jul 13, 2023 |
| Dell          | Latitude E6400              | [c8cf9bcf47](https://linux-hardware.org/?probe=c8cf9bcf47) | Jul 13, 2023 |
| HP            | Compaq Presario CQ40        | [fbc602a7b6](https://linux-hardware.org/?probe=fbc602a7b6) | Jul 12, 2023 |
| Dell          | Inspiron 5737               | [fa1cb6ffb8](https://linux-hardware.org/?probe=fa1cb6ffb8) | Jul 12, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [ef1f607a84](https://linux-hardware.org/?probe=ef1f607a84) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | [cb6e26bcb4](https://linux-hardware.org/?probe=cb6e26bcb4) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | [37049406c3](https://linux-hardware.org/?probe=37049406c3) | Jul 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [8b9677cc2a](https://linux-hardware.org/?probe=8b9677cc2a) | Jul 10, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [acdd4ea952](https://linux-hardware.org/?probe=acdd4ea952) | Jul 10, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [59b334f01a](https://linux-hardware.org/?probe=59b334f01a) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | [8f40997f5f](https://linux-hardware.org/?probe=8f40997f5f) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | [7d19e6a8f5](https://linux-hardware.org/?probe=7d19e6a8f5) | Jul 10, 2023 |
| Dell          | Latitude 3490               | [6fcb4ace67](https://linux-hardware.org/?probe=6fcb4ace67) | Jul 10, 2023 |
| Acer          | Nitro AN515-43              | [b463aaca78](https://linux-hardware.org/?probe=b463aaca78) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK LH532              | [3cad86057a](https://linux-hardware.org/?probe=3cad86057a) | Jul 09, 2023 |
| HUAWEI        | KLVL-WXX9                   | [e853f79dd4](https://linux-hardware.org/?probe=e853f79dd4) | Jul 09, 2023 |
| Acer          | TravelMate P2510-G2-M       | [c96a405528](https://linux-hardware.org/?probe=c96a405528) | Jul 09, 2023 |
| Acer          | Aspire A515-56              | [9dee0fcab9](https://linux-hardware.org/?probe=9dee0fcab9) | Jul 09, 2023 |
| Fujitsu       | LIFEBOOK S752               | [a2bd9b682d](https://linux-hardware.org/?probe=a2bd9b682d) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [e87ea192ea](https://linux-hardware.org/?probe=e87ea192ea) | Jul 08, 2023 |
| ASUSTek       | UX550VE                     | [b782a00935](https://linux-hardware.org/?probe=b782a00935) | Jul 08, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | [59782374c4](https://linux-hardware.org/?probe=59782374c4) | Jul 07, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [4e47f48ca8](https://linux-hardware.org/?probe=4e47f48ca8) | Jul 07, 2023 |
| Framework     | Laptop                      | [ea4c4585d0](https://linux-hardware.org/?probe=ea4c4585d0) | Jul 06, 2023 |
| HP            | 255 G7 Notebook PC          | [23a6105e01](https://linux-hardware.org/?probe=23a6105e01) | Jul 06, 2023 |
| ASUSTek       | K53SV                       | [851a3a00cf](https://linux-hardware.org/?probe=851a3a00cf) | Jul 05, 2023 |
| Dell          | Latitude 3490               | [a730cef547](https://linux-hardware.org/?probe=a730cef547) | Jul 05, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f3828ea18b](https://linux-hardware.org/?probe=f3828ea18b) | Jul 04, 2023 |
| MSI           | FX603                       | [8b0664bd4e](https://linux-hardware.org/?probe=8b0664bd4e) | Jul 04, 2023 |
| Packard Be... | EasyNote MH36               | [87873c1e0e](https://linux-hardware.org/?probe=87873c1e0e) | Jul 03, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [cc0464c9a4](https://linux-hardware.org/?probe=cc0464c9a4) | Jul 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [6686fca24b](https://linux-hardware.org/?probe=6686fca24b) | Jul 03, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [ccb318cd32](https://linux-hardware.org/?probe=ccb318cd32) | Jul 03, 2023 |
| HP            | EliteBook 8460p             | [40b92fc7ba](https://linux-hardware.org/?probe=40b92fc7ba) | Jul 02, 2023 |
| Dell          | Inspiron 5566               | [c0fa0d6c73](https://linux-hardware.org/?probe=c0fa0d6c73) | Jul 02, 2023 |
| Teclast       | F15Plus 2                   | [29b2c807e6](https://linux-hardware.org/?probe=29b2c807e6) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | [f182eda3d3](https://linux-hardware.org/?probe=f182eda3d3) | Jul 01, 2023 |
| Teclast       | F15Plus 2                   | [4593b411f0](https://linux-hardware.org/?probe=4593b411f0) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [559c10480e](https://linux-hardware.org/?probe=559c10480e) | Jun 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e555922bb2](https://linux-hardware.org/?probe=e555922bb2) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | [954ac9a8e4](https://linux-hardware.org/?probe=954ac9a8e4) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | [9d40263129](https://linux-hardware.org/?probe=9d40263129) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | [4e47d108a0](https://linux-hardware.org/?probe=4e47d108a0) | Jun 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d058f48980](https://linux-hardware.org/?probe=d058f48980) | Jun 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [1c349accca](https://linux-hardware.org/?probe=1c349accca) | Jun 29, 2023 |
| Alienware     | 17 R4                       | [e7f3110f1f](https://linux-hardware.org/?probe=e7f3110f1f) | Jun 29, 2023 |
| Google        | Reef                        | [221e64e148](https://linux-hardware.org/?probe=221e64e148) | Jun 29, 2023 |
| Acer          | Aspire VN7-593G             | [2302cbfba7](https://linux-hardware.org/?probe=2302cbfba7) | Jun 28, 2023 |
| Chuwi         | GemiBook                    | [90f0de1460](https://linux-hardware.org/?probe=90f0de1460) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [2debd02f0c](https://linux-hardware.org/?probe=2debd02f0c) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [3b775b8099](https://linux-hardware.org/?probe=3b775b8099) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0c87fda1f9](https://linux-hardware.org/?probe=0c87fda1f9) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | [5e6365efcf](https://linux-hardware.org/?probe=5e6365efcf) | Jun 27, 2023 |
| Dell          | Inspiron 3442               | [6e179dbfb0](https://linux-hardware.org/?probe=6e179dbfb0) | Jun 26, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [9dbf9f98a6](https://linux-hardware.org/?probe=9dbf9f98a6) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [4518a77b73](https://linux-hardware.org/?probe=4518a77b73) | Jun 26, 2023 |
| Acer          | Nitro AN517-54              | [9af91d0ced](https://linux-hardware.org/?probe=9af91d0ced) | Jun 26, 2023 |
| HP            | EliteBook 8740w             | [e460d017ec](https://linux-hardware.org/?probe=e460d017ec) | Jun 25, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [df9521a37d](https://linux-hardware.org/?probe=df9521a37d) | Jun 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [01a9e10a34](https://linux-hardware.org/?probe=01a9e10a34) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | [3e08f1644a](https://linux-hardware.org/?probe=3e08f1644a) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | [574653afac](https://linux-hardware.org/?probe=574653afac) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | [fa6b09cc1d](https://linux-hardware.org/?probe=fa6b09cc1d) | Jun 23, 2023 |
| Dell          | XPS 13 9370                 | [7ba7b1dc58](https://linux-hardware.org/?probe=7ba7b1dc58) | Jun 22, 2023 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [38c278b214](https://linux-hardware.org/?probe=38c278b214) | Jun 22, 2023 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [816c32de98](https://linux-hardware.org/?probe=816c32de98) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | [f1e506486c](https://linux-hardware.org/?probe=f1e506486c) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [8e74890c4f](https://linux-hardware.org/?probe=8e74890c4f) | Jun 19, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [98f052ad58](https://linux-hardware.org/?probe=98f052ad58) | Jun 19, 2023 |
| Framework     | Laptop                      | [7d010a367e](https://linux-hardware.org/?probe=7d010a367e) | Jun 19, 2023 |
| MSI           | GT70 2OC/2OD                | [adee2af879](https://linux-hardware.org/?probe=adee2af879) | Jun 19, 2023 |
| Dell          | Inspiron 5566               | [be5a148c53](https://linux-hardware.org/?probe=be5a148c53) | Jun 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | [591e97398c](https://linux-hardware.org/?probe=591e97398c) | Jun 18, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [c454cb2cf0](https://linux-hardware.org/?probe=c454cb2cf0) | Jun 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | [0875b8b413](https://linux-hardware.org/?probe=0875b8b413) | Jun 18, 2023 |
| HP            | Laptop 15-dy1xxx            | [93e28671fa](https://linux-hardware.org/?probe=93e28671fa) | Jun 18, 2023 |
| Samsung       | 300E5K/300E5Q               | [a281272278](https://linux-hardware.org/?probe=a281272278) | Jun 17, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [97a4ed6110](https://linux-hardware.org/?probe=97a4ed6110) | Jun 17, 2023 |
| Dell          | Latitude 5491               | [0673ab5ff5](https://linux-hardware.org/?probe=0673ab5ff5) | Jun 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [5b54def91d](https://linux-hardware.org/?probe=5b54def91d) | Jun 16, 2023 |
| Dell          | Latitude E5400              | [f5d066d8fc](https://linux-hardware.org/?probe=f5d066d8fc) | Jun 16, 2023 |
| HONOR         | NMH-WCX9                    | [39b295867e](https://linux-hardware.org/?probe=39b295867e) | Jun 15, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [b1e56a3c92](https://linux-hardware.org/?probe=b1e56a3c92) | Jun 15, 2023 |
| Unknown       | Unknown                     | [3a944bbbd5](https://linux-hardware.org/?probe=3a944bbbd5) | Jun 15, 2023 |
| Unknown       | Unknown                     | [581aba0aa2](https://linux-hardware.org/?probe=581aba0aa2) | Jun 15, 2023 |
| HONOR         | NMH-WCX9                    | [8515730b56](https://linux-hardware.org/?probe=8515730b56) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [3b552a7f4a](https://linux-hardware.org/?probe=3b552a7f4a) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | [8f84dca464](https://linux-hardware.org/?probe=8f84dca464) | Jun 14, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [2eed8e0355](https://linux-hardware.org/?probe=2eed8e0355) | Jun 13, 2023 |
| Google        | Atlas                       | [ecd53b626a](https://linux-hardware.org/?probe=ecd53b626a) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [542a1217bd](https://linux-hardware.org/?probe=542a1217bd) | Jun 13, 2023 |
| ASUSTek       | UX530UQ                     | [c952ec8390](https://linux-hardware.org/?probe=c952ec8390) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [0b717c2785](https://linux-hardware.org/?probe=0b717c2785) | Jun 13, 2023 |
| Schenker      | VIA 15 Pro                  | [311a7e116c](https://linux-hardware.org/?probe=311a7e116c) | Jun 13, 2023 |
| Acer          | Aspire A517-53G             | [a4c87fb2bc](https://linux-hardware.org/?probe=a4c87fb2bc) | Jun 12, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | [ceae8212bf](https://linux-hardware.org/?probe=ceae8212bf) | Jun 12, 2023 |
| Acer          | Aspire A517-53G             | [2069778d1f](https://linux-hardware.org/?probe=2069778d1f) | Jun 12, 2023 |
| Acer          | Aspire A315-510P            | [705ad3c316](https://linux-hardware.org/?probe=705ad3c316) | Jun 12, 2023 |
| MSI           | Prestige 14Evo A12M         | [3e121c01dd](https://linux-hardware.org/?probe=3e121c01dd) | Jun 12, 2023 |
| Emdoor        | AG958                       | [1688cc07b6](https://linux-hardware.org/?probe=1688cc07b6) | Jun 11, 2023 |
| Dell          | Latitude 5580               | [1e37ff326f](https://linux-hardware.org/?probe=1e37ff326f) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [0d419f2c9d](https://linux-hardware.org/?probe=0d419f2c9d) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [afc5d143fe](https://linux-hardware.org/?probe=afc5d143fe) | Jun 11, 2023 |
| Acer          | Aspire A317-33              | [f62e645bd3](https://linux-hardware.org/?probe=f62e645bd3) | Jun 11, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9747487f82](https://linux-hardware.org/?probe=9747487f82) | Jun 11, 2023 |
| HP            | ProBook 470 G0              | [d3fdf73c3e](https://linux-hardware.org/?probe=d3fdf73c3e) | Jun 10, 2023 |
| MSI           | GS60 6QE                    | [e04ff9df40](https://linux-hardware.org/?probe=e04ff9df40) | Jun 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fa84ae9906](https://linux-hardware.org/?probe=fa84ae9906) | Jun 10, 2023 |
| ASUSTek       | UX530UQ                     | [71d0ddd2f0](https://linux-hardware.org/?probe=71d0ddd2f0) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | [3742e80123](https://linux-hardware.org/?probe=3742e80123) | Jun 09, 2023 |
| HP            | 240 G6 Notebook PC          | [f7470e08b0](https://linux-hardware.org/?probe=f7470e08b0) | Jun 08, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [bb571d888d](https://linux-hardware.org/?probe=bb571d888d) | Jun 08, 2023 |
| Dell          | XPS 17 9730                 | [5be9db17d1](https://linux-hardware.org/?probe=5be9db17d1) | Jun 08, 2023 |
| WOOKING       | X16                         | [aa543651fc](https://linux-hardware.org/?probe=aa543651fc) | Jun 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| Google        | Chell                       | [cace26f9f9](https://linux-hardware.org/?probe=cace26f9f9) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | [cbb39d8d29](https://linux-hardware.org/?probe=cbb39d8d29) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | [47fd407976](https://linux-hardware.org/?probe=47fd407976) | Jun 07, 2023 |
| Acer          | Aspire A314-36M             | [7cab0d1591](https://linux-hardware.org/?probe=7cab0d1591) | Jun 06, 2023 |
| Dell          | Latitude 5530               | [44aa9db289](https://linux-hardware.org/?probe=44aa9db289) | Jun 06, 2023 |
| HONOR         | HYM-WXX                     | [964cd10c8e](https://linux-hardware.org/?probe=964cd10c8e) | Jun 05, 2023 |
| Dell          | Latitude 3340               | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [13f3f67373](https://linux-hardware.org/?probe=13f3f67373) | Jun 04, 2023 |
| MSI           | GS60 6QE                    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| HONOR         | HGF-WX6                     | [13d0d7b145](https://linux-hardware.org/?probe=13d0d7b145) | Jun 03, 2023 |
| Dell          | XPS 15 9530                 | [31400c0b8a](https://linux-hardware.org/?probe=31400c0b8a) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [359d31bb8c](https://linux-hardware.org/?probe=359d31bb8c) | Jun 02, 2023 |
| Lenovo        | G50-45 80E3                 | [3bc50c5ccb](https://linux-hardware.org/?probe=3bc50c5ccb) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b34bb8b33a](https://linux-hardware.org/?probe=b34bb8b33a) | Jun 02, 2023 |
| MSI           | U200                        | [a217267eb0](https://linux-hardware.org/?probe=a217267eb0) | Jun 01, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [d25f4736b7](https://linux-hardware.org/?probe=d25f4736b7) | Jun 01, 2023 |
| Apple         | MacBookPro11,1              | [fd232702db](https://linux-hardware.org/?probe=fd232702db) | Jun 01, 2023 |
| Acer          | Aspire 3830TG               | [abd7d9a412](https://linux-hardware.org/?probe=abd7d9a412) | May 31, 2023 |
| Dell          | Precision 3550              | [bddf57400b](https://linux-hardware.org/?probe=bddf57400b) | May 31, 2023 |
| Dell          | System Vostro 3750          | [f77ea94512](https://linux-hardware.org/?probe=f77ea94512) | May 31, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [a5ebbfe1ef](https://linux-hardware.org/?probe=a5ebbfe1ef) | May 31, 2023 |
| HP            | Pavilion dv4                | [75797b5ec9](https://linux-hardware.org/?probe=75797b5ec9) | May 31, 2023 |
| Acer          | Aspire A315-59              | [3f08f70d3a](https://linux-hardware.org/?probe=3f08f70d3a) | May 31, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [8092b65afc](https://linux-hardware.org/?probe=8092b65afc) | May 31, 2023 |
| HP            | Laptop 15-ef2xxx            | [2139621391](https://linux-hardware.org/?probe=2139621391) | May 31, 2023 |
| HP            | Laptop 15-gw0xxx            | [ebc3d97429](https://linux-hardware.org/?probe=ebc3d97429) | May 30, 2023 |
| HP            | Laptop 15-gw0xxx            | [97382e45f8](https://linux-hardware.org/?probe=97382e45f8) | May 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Apple         | MacBookPro11,1              | [ac2f40b972](https://linux-hardware.org/?probe=ac2f40b972) | May 30, 2023 |
| Apple         | MacBookPro11,1              | [f45bc9a282](https://linux-hardware.org/?probe=f45bc9a282) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [c507b25480](https://linux-hardware.org/?probe=c507b25480) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| Dell          | Vostro 1015                 | [ebb5445720](https://linux-hardware.org/?probe=ebb5445720) | May 29, 2023 |
| Apple         | MacBookPro8,1               | [d8aa236e2d](https://linux-hardware.org/?probe=d8aa236e2d) | May 28, 2023 |
| Lenovo        | ThinkPad X230 2325SV7       | [6affd0b8ee](https://linux-hardware.org/?probe=6affd0b8ee) | May 28, 2023 |
| HP            | ProBook 6560b               | [972d01f49f](https://linux-hardware.org/?probe=972d01f49f) | May 28, 2023 |
| HP            | ProBook 6560b               | [9fd712c62d](https://linux-hardware.org/?probe=9fd712c62d) | May 28, 2023 |
| Unknown       | Unknown                     | [b294c91e3a](https://linux-hardware.org/?probe=b294c91e3a) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | [fb534d212e](https://linux-hardware.org/?probe=fb534d212e) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | [6b753016ff](https://linux-hardware.org/?probe=6b753016ff) | May 28, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| Dell          | Vostro 1015                 | [5098185f54](https://linux-hardware.org/?probe=5098185f54) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1fea1a6529](https://linux-hardware.org/?probe=1fea1a6529) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [c5baa41ff7](https://linux-hardware.org/?probe=c5baa41ff7) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [a03284052b](https://linux-hardware.org/?probe=a03284052b) | May 24, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [f9103674dc](https://linux-hardware.org/?probe=f9103674dc) | May 22, 2023 |
| HP            | EliteBook 2570p             | [60ec2d6e04](https://linux-hardware.org/?probe=60ec2d6e04) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [fa899a9a41](https://linux-hardware.org/?probe=fa899a9a41) | May 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [19416d3973](https://linux-hardware.org/?probe=19416d3973) | May 21, 2023 |
| Getac         | V110G3                      | [4a80145aac](https://linux-hardware.org/?probe=4a80145aac) | May 21, 2023 |
| HP            | Laptop 17-cn2xxx            | [953734fc80](https://linux-hardware.org/?probe=953734fc80) | May 20, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [3976703e20](https://linux-hardware.org/?probe=3976703e20) | May 20, 2023 |
| Getac         | V110G3                      | [1b04290d0e](https://linux-hardware.org/?probe=1b04290d0e) | May 19, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [6c83146909](https://linux-hardware.org/?probe=6c83146909) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [1ed7f81c69](https://linux-hardware.org/?probe=1ed7f81c69) | May 18, 2023 |
| ASUSTek       | ROG Strix G733CX_G743CX     | [744f091c75](https://linux-hardware.org/?probe=744f091c75) | May 18, 2023 |
| Dell          | Inspiron 15-7568            | [77675ecccd](https://linux-hardware.org/?probe=77675ecccd) | May 17, 2023 |
| Acer          | Swift SFA16-41              | [8b1e6a5baf](https://linux-hardware.org/?probe=8b1e6a5baf) | May 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [0770462dab](https://linux-hardware.org/?probe=0770462dab) | May 15, 2023 |
| Dell          | Inspiron 3542               | [a6ffd0df31](https://linux-hardware.org/?probe=a6ffd0df31) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [bfd8d8244b](https://linux-hardware.org/?probe=bfd8d8244b) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| HP            | Laptop 15-ef2xxx            | [f732fbd488](https://linux-hardware.org/?probe=f732fbd488) | May 14, 2023 |
| Dell          | XPS 15 9570                 | [59214a0e61](https://linux-hardware.org/?probe=59214a0e61) | May 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [fb58a4d348](https://linux-hardware.org/?probe=fb58a4d348) | May 14, 2023 |
| Dell          | Vostro 5471                 | [745ae69749](https://linux-hardware.org/?probe=745ae69749) | May 14, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [acc449dad2](https://linux-hardware.org/?probe=acc449dad2) | May 14, 2023 |
| HP            | Pavilion dv6                | [c164fc1080](https://linux-hardware.org/?probe=c164fc1080) | May 14, 2023 |
| HP            | Pavilion dv6                | [b4c4fde79d](https://linux-hardware.org/?probe=b4c4fde79d) | May 14, 2023 |
| Schenker      | VISION (E22)                | [582ac3cbf5](https://linux-hardware.org/?probe=582ac3cbf5) | May 13, 2023 |
| Sony          | SVE1513Z1EB                 | [d47ba48012](https://linux-hardware.org/?probe=d47ba48012) | May 12, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2674c1ddb6](https://linux-hardware.org/?probe=2674c1ddb6) | May 12, 2023 |
| Dell          | Inspiron 15-7568            | [bb8fe2215b](https://linux-hardware.org/?probe=bb8fe2215b) | May 12, 2023 |
| MSI           | GT70 2PC                    | [c98c889dbf](https://linux-hardware.org/?probe=c98c889dbf) | May 11, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [e855bafa57](https://linux-hardware.org/?probe=e855bafa57) | May 11, 2023 |
| Dell          | Precision 7520              | [184802dbab](https://linux-hardware.org/?probe=184802dbab) | May 11, 2023 |
| Itautec       | Infoway w7440               | [41eee30825](https://linux-hardware.org/?probe=41eee30825) | May 11, 2023 |
| Dell          | Latitude E6440              | [ea902a82a4](https://linux-hardware.org/?probe=ea902a82a4) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57a74239f8](https://linux-hardware.org/?probe=57a74239f8) | May 10, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [962ca6e507](https://linux-hardware.org/?probe=962ca6e507) | May 10, 2023 |
| Acer          | TravelMate P653-M           | [a0f805c8ca](https://linux-hardware.org/?probe=a0f805c8ca) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0b797e8428](https://linux-hardware.org/?probe=0b797e8428) | May 10, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [69f4dd51d9](https://linux-hardware.org/?probe=69f4dd51d9) | May 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [fa734dc49a](https://linux-hardware.org/?probe=fa734dc49a) | May 09, 2023 |
| Dell          | XPS 15 9520                 | [86136dd98f](https://linux-hardware.org/?probe=86136dd98f) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0fc6f7617](https://linux-hardware.org/?probe=e0fc6f7617) | May 08, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| Toshiba       | Satellite L855              | [5e78ff90cc](https://linux-hardware.org/?probe=5e78ff90cc) | May 08, 2023 |
| TUXEDO        | N24_25BU                    | [9cd4e499ae](https://linux-hardware.org/?probe=9cd4e499ae) | May 07, 2023 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [a9fe0fdf88](https://linux-hardware.org/?probe=a9fe0fdf88) | May 07, 2023 |
| Dell          | Inspiron 5585               | [f838e48bd3](https://linux-hardware.org/?probe=f838e48bd3) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | [c1a5a5b4d9](https://linux-hardware.org/?probe=c1a5a5b4d9) | May 07, 2023 |
| HP            | EliteBook 840 G6            | [a86bd404e0](https://linux-hardware.org/?probe=a86bd404e0) | May 07, 2023 |
| Gigabyte      | G5 MD                       | [7ad914a8a9](https://linux-hardware.org/?probe=7ad914a8a9) | May 06, 2023 |
| Acer          | Nitro AN517-54              | [0a66f5d4e4](https://linux-hardware.org/?probe=0a66f5d4e4) | May 06, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [9b843f40a1](https://linux-hardware.org/?probe=9b843f40a1) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | [dd6f6a940f](https://linux-hardware.org/?probe=dd6f6a940f) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | [c7b66fbdc3](https://linux-hardware.org/?probe=c7b66fbdc3) | May 05, 2023 |
| HP            | Laptop 15-dy1xxx            | [dd238f7e60](https://linux-hardware.org/?probe=dd238f7e60) | May 04, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [ce70c65f11](https://linux-hardware.org/?probe=ce70c65f11) | May 03, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [6a70490cd6](https://linux-hardware.org/?probe=6a70490cd6) | May 03, 2023 |
| HP            | Compaq Presario C700        | [8c62d76e28](https://linux-hardware.org/?probe=8c62d76e28) | May 03, 2023 |
| Acer          | Swift SF114-32              | [19a489c33e](https://linux-hardware.org/?probe=19a489c33e) | May 03, 2023 |
| Acer          | Nitro AN517-54              | [c26b48854d](https://linux-hardware.org/?probe=c26b48854d) | May 03, 2023 |
| MECHREVO      | WUJIE16 Pro                 | [c19e8370e5](https://linux-hardware.org/?probe=c19e8370e5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | [9cee4296b5](https://linux-hardware.org/?probe=9cee4296b5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | [a9406a1851](https://linux-hardware.org/?probe=a9406a1851) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [558cde0a43](https://linux-hardware.org/?probe=558cde0a43) | Apr 30, 2023 |
| HP            | ProBook 450 G7              | [a1c1008bf1](https://linux-hardware.org/?probe=a1c1008bf1) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Sony          | VPCSB2A7R                   | [f089770d02](https://linux-hardware.org/?probe=f089770d02) | Apr 28, 2023 |
| Sony          | VPCSB2A7R                   | [89f52ca147](https://linux-hardware.org/?probe=89f52ca147) | Apr 28, 2023 |
| HP            | ENVY Notebook               | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fe959d51ab](https://linux-hardware.org/?probe=fe959d51ab) | Apr 27, 2023 |
| MECHREVO      | X3 Series GK7CP6R           | [c764a98c9d](https://linux-hardware.org/?probe=c764a98c9d) | Apr 27, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4fb9a937f3](https://linux-hardware.org/?probe=4fb9a937f3) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [d470349226](https://linux-hardware.org/?probe=d470349226) | Apr 26, 2023 |
| Dell          | Inspiron N4030              | [a0f1823b8e](https://linux-hardware.org/?probe=a0f1823b8e) | Apr 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20bf63821f](https://linux-hardware.org/?probe=20bf63821f) | Apr 25, 2023 |
| Dell          | XPS 15 9500                 | [861431db35](https://linux-hardware.org/?probe=861431db35) | Apr 25, 2023 |
| Emdoor        | AG958                       | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Medion        | E4251                       | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| Dell          | XPS 17 9720                 | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Google        | Fleex                       | [19603bb256](https://linux-hardware.org/?probe=19603bb256) | Apr 22, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [6e1df0f6ee](https://linux-hardware.org/?probe=6e1df0f6ee) | Apr 21, 2023 |
| Emdoor        | AG958                       | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [888b7bed45](https://linux-hardware.org/?probe=888b7bed45) | Apr 21, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [84a6fd49fa](https://linux-hardware.org/?probe=84a6fd49fa) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [87538ce2ba](https://linux-hardware.org/?probe=87538ce2ba) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| HP            | Laptop 15-dw3xxx            | [648c4c3622](https://linux-hardware.org/?probe=648c4c3622) | Apr 20, 2023 |
| HP            | ProBook 4540s               | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| Dell          | Precision 3550              | [2f1a7d66f4](https://linux-hardware.org/?probe=2f1a7d66f4) | Apr 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [cb5a9be901](https://linux-hardware.org/?probe=cb5a9be901) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [3d2366f479](https://linux-hardware.org/?probe=3d2366f479) | Apr 18, 2023 |
| HONOR         | HYM-WXX                     | [49d7cdd068](https://linux-hardware.org/?probe=49d7cdd068) | Apr 18, 2023 |
| HP            | 250 G7 Notebook PC          | [6696ce8fd6](https://linux-hardware.org/?probe=6696ce8fd6) | Apr 17, 2023 |
| Dell          | Precision 3571              | [d1fcff8b8f](https://linux-hardware.org/?probe=d1fcff8b8f) | Apr 17, 2023 |
| Dell          | Latitude 5500               | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3e9d210a94](https://linux-hardware.org/?probe=3e9d210a94) | Apr 16, 2023 |
| Positivo      | C14CR01                     | [a5fc85315a](https://linux-hardware.org/?probe=a5fc85315a) | Apr 16, 2023 |
| Acer          | Nitro AN515-46              | [502263c435](https://linux-hardware.org/?probe=502263c435) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | [33c25e0c22](https://linux-hardware.org/?probe=33c25e0c22) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | [33936188c8](https://linux-hardware.org/?probe=33936188c8) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| AZW           | GT-R                        | [c37dabb7a7](https://linux-hardware.org/?probe=c37dabb7a7) | Apr 15, 2023 |
| HP            | ProBook 640 G1              | [2b7836fd04](https://linux-hardware.org/?probe=2b7836fd04) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| Unknown       | Unknown                     | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Samsung       | 270E5G/270E5U               | [ea58c893c1](https://linux-hardware.org/?probe=ea58c893c1) | Apr 13, 2023 |
| Unknown       | Unknown                     | [3637a41ac7](https://linux-hardware.org/?probe=3637a41ac7) | Apr 13, 2023 |
| Apple         | MacBookPro7,1               | [7c28a5666c](https://linux-hardware.org/?probe=7c28a5666c) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | [d1ecfaf06b](https://linux-hardware.org/?probe=d1ecfaf06b) | Apr 12, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [426140ece2](https://linux-hardware.org/?probe=426140ece2) | Apr 12, 2023 |
| Acer          | Aspire A515-57              | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| Dell          | Precision 5520              | [32eb960b25](https://linux-hardware.org/?probe=32eb960b25) | Apr 12, 2023 |
| Sony          | VPCSB2A7R                   | [1620c38937](https://linux-hardware.org/?probe=1620c38937) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [5a4d307476](https://linux-hardware.org/?probe=5a4d307476) | Apr 09, 2023 |
| MACHENIKE     | T58-V                       | [9a70cca135](https://linux-hardware.org/?probe=9a70cca135) | Apr 08, 2023 |
| Fujitsu       | LIFEBOOK E746               | [11cc5eca09](https://linux-hardware.org/?probe=11cc5eca09) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| Acer          | Nitro AN515-46              | [6611343c84](https://linux-hardware.org/?probe=6611343c84) | Apr 05, 2023 |
| Acer          | Nitro AN515-46              | [1dcee27dff](https://linux-hardware.org/?probe=1dcee27dff) | Apr 05, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [770d8a9253](https://linux-hardware.org/?probe=770d8a9253) | Apr 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [8c29713fe9](https://linux-hardware.org/?probe=8c29713fe9) | Apr 05, 2023 |
| LG Electro... | Kabylake Platform           | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| Toshiba       | QOSMIO F750                 | [695bc9e499](https://linux-hardware.org/?probe=695bc9e499) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [56119c4c93](https://linux-hardware.org/?probe=56119c4c93) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| HP            | EliteBook 850 G6            | [303d201aa6](https://linux-hardware.org/?probe=303d201aa6) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [04afa2e378](https://linux-hardware.org/?probe=04afa2e378) | Apr 04, 2023 |
| Timi          | RedmiBook 16                | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fc6e550ca1](https://linux-hardware.org/?probe=fc6e550ca1) | Apr 03, 2023 |
| Sony          | VPCF236FM                   | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ed69a3bba9](https://linux-hardware.org/?probe=ed69a3bba9) | Apr 02, 2023 |
| Star Labs     | StarBook                    | [8712994e3c](https://linux-hardware.org/?probe=8712994e3c) | Apr 01, 2023 |
| Dell          | XPS 13 9380                 | [47557561a9](https://linux-hardware.org/?probe=47557561a9) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [d35ddee3e1](https://linux-hardware.org/?probe=d35ddee3e1) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| HP            | 250 G3                      | [519b0e31a8](https://linux-hardware.org/?probe=519b0e31a8) | Mar 30, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | [1b3629b77e](https://linux-hardware.org/?probe=1b3629b77e) | Mar 30, 2023 |
| Dell          | Precision M6400             | [293957e2c0](https://linux-hardware.org/?probe=293957e2c0) | Mar 30, 2023 |
| HP            | OMEN by Laptop              | [c6e4da00ac](https://linux-hardware.org/?probe=c6e4da00ac) | Mar 30, 2023 |
| Framework     | Laptop                      | [ef17714efa](https://linux-hardware.org/?probe=ef17714efa) | Mar 30, 2023 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [eb153b5f5d](https://linux-hardware.org/?probe=eb153b5f5d) | Mar 29, 2023 |
| HP            | Notebook                    | [ea7c0e1a2c](https://linux-hardware.org/?probe=ea7c0e1a2c) | Mar 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c393e49ce3](https://linux-hardware.org/?probe=c393e49ce3) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e7608e5c20](https://linux-hardware.org/?probe=e7608e5c20) | Mar 28, 2023 |
| Acer          | Swift SFX14-41G             | [20df1488bd](https://linux-hardware.org/?probe=20df1488bd) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [01a09bc2c7](https://linux-hardware.org/?probe=01a09bc2c7) | Mar 27, 2023 |
| Dell          | Precision 3571              | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| Toshiba       | QOSMIO F750                 | [b52a3268f6](https://linux-hardware.org/?probe=b52a3268f6) | Mar 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [a438a0c994](https://linux-hardware.org/?probe=a438a0c994) | Mar 27, 2023 |
| Dell          | G15 5515                    | [9c13066534](https://linux-hardware.org/?probe=9c13066534) | Mar 27, 2023 |
| MSI           | GT70 2PE                    | [be727f6f39](https://linux-hardware.org/?probe=be727f6f39) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [91e01e5646](https://linux-hardware.org/?probe=91e01e5646) | Mar 26, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [13e0523db8](https://linux-hardware.org/?probe=13e0523db8) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| Dell          | Vostro 15-3568              | [bc2447e1e5](https://linux-hardware.org/?probe=bc2447e1e5) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | [f027c9ca09](https://linux-hardware.org/?probe=f027c9ca09) | Mar 25, 2023 |
| Dell          | Vostro 15-3568              | [e6ee9fc566](https://linux-hardware.org/?probe=e6ee9fc566) | Mar 25, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [5377aa4b23](https://linux-hardware.org/?probe=5377aa4b23) | Mar 24, 2023 |
| realme        | CloudProXXXX                | [aaafa41631](https://linux-hardware.org/?probe=aaafa41631) | Mar 23, 2023 |
| Dell          | XPS 9315                    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [90ef1729ef](https://linux-hardware.org/?probe=90ef1729ef) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [48f86bde7c](https://linux-hardware.org/?probe=48f86bde7c) | Mar 22, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [88d49f423d](https://linux-hardware.org/?probe=88d49f423d) | Mar 22, 2023 |
| Dell          | XPS 15 9500                 | [893f51c005](https://linux-hardware.org/?probe=893f51c005) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| ASUSTek       | TP500LB                     | [20b2caf568](https://linux-hardware.org/?probe=20b2caf568) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3f233b6f9d](https://linux-hardware.org/?probe=3f233b6f9d) | Mar 20, 2023 |
| Dell          | XPS 15 9520                 | [b6ffb56057](https://linux-hardware.org/?probe=b6ffb56057) | Mar 20, 2023 |
| Acer          | Aspire E5-573G              | [e1c4772d0d](https://linux-hardware.org/?probe=e1c4772d0d) | Mar 19, 2023 |
| Acer          | Aspire E5-573G              | [68cf28bafe](https://linux-hardware.org/?probe=68cf28bafe) | Mar 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S64C00    | [d91384b02c](https://linux-hardware.org/?probe=d91384b02c) | Mar 19, 2023 |
| HP            | Laptop 15-rb0xx             | [d7ed5ce80d](https://linux-hardware.org/?probe=d7ed5ce80d) | Mar 19, 2023 |
| HP            | 245 G8                      | [5b1606146f](https://linux-hardware.org/?probe=5b1606146f) | Mar 19, 2023 |
| Sony          | SVZ1311C5E                  | [e433359eb9](https://linux-hardware.org/?probe=e433359eb9) | Mar 18, 2023 |
| Dell          | Latitude E5470              | [6565aa43e3](https://linux-hardware.org/?probe=6565aa43e3) | Mar 18, 2023 |
| Itautec       | Infoway w7440               | [c1e90dd1a3](https://linux-hardware.org/?probe=c1e90dd1a3) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc76a5003](https://linux-hardware.org/?probe=ecc76a5003) | Mar 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [4ff2145364](https://linux-hardware.org/?probe=4ff2145364) | Mar 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | [dd58f68013](https://linux-hardware.org/?probe=dd58f68013) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| Sony          | SVF1521Q1EW                 | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | [2eff18f570](https://linux-hardware.org/?probe=2eff18f570) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | [2c0d31ff9e](https://linux-hardware.org/?probe=2c0d31ff9e) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [a99c892744](https://linux-hardware.org/?probe=a99c892744) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | [4853be01f6](https://linux-hardware.org/?probe=4853be01f6) | Mar 14, 2023 |
| Sony          | VPCEB4L1E                   | [d91d243c75](https://linux-hardware.org/?probe=d91d243c75) | Mar 14, 2023 |
| Dell          | G5 5587                     | [4ff3c98faf](https://linux-hardware.org/?probe=4ff3c98faf) | Mar 14, 2023 |
| Dell          | XPS 15 7590                 | [5997bff822](https://linux-hardware.org/?probe=5997bff822) | Mar 14, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b4f32e23c4](https://linux-hardware.org/?probe=b4f32e23c4) | Mar 14, 2023 |
| HONOR         | BMH-WCX9                    | [d53fa296bf](https://linux-hardware.org/?probe=d53fa296bf) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [3dc28679cc](https://linux-hardware.org/?probe=3dc28679cc) | Mar 14, 2023 |
| Positivo      | Q464B                       | [5bd9649f43](https://linux-hardware.org/?probe=5bd9649f43) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9f6119111f](https://linux-hardware.org/?probe=9f6119111f) | Mar 13, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | [41cee24fa8](https://linux-hardware.org/?probe=41cee24fa8) | Mar 13, 2023 |
| HP            | Pavilion dv7                | [b0834fe20e](https://linux-hardware.org/?probe=b0834fe20e) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [5329567562](https://linux-hardware.org/?probe=5329567562) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| Apple         | MacBookPro14,1              | [999c455869](https://linux-hardware.org/?probe=999c455869) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ad61830c15](https://linux-hardware.org/?probe=ad61830c15) | Mar 12, 2023 |
| GPD           | G1621-02                    | [21394d0975](https://linux-hardware.org/?probe=21394d0975) | Mar 12, 2023 |
| Medion        | E4251                       | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| Apple         | MacBookPro14,1              | [593c3e084d](https://linux-hardware.org/?probe=593c3e084d) | Mar 12, 2023 |
| HP            | Laptop 15-dw3xxx            | [cc73320a47](https://linux-hardware.org/?probe=cc73320a47) | Mar 12, 2023 |
| HP            | Laptop 15-dy1xxx            | [ac6452184d](https://linux-hardware.org/?probe=ac6452184d) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| HP            | EliteBook 845 14 inch G9... | [5dfc4ceb2a](https://linux-hardware.org/?probe=5dfc4ceb2a) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| Unknown       | Unknown                     | [5d585fb91b](https://linux-hardware.org/?probe=5d585fb91b) | Mar 11, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| Medion        | Akoya E6412T                | [d8941697fd](https://linux-hardware.org/?probe=d8941697fd) | Mar 09, 2023 |
| Dell          | Latitude 5590               | [d7d667d45f](https://linux-hardware.org/?probe=d7d667d45f) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | [3f6f0bc1a2](https://linux-hardware.org/?probe=3f6f0bc1a2) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | [04d6eb5847](https://linux-hardware.org/?probe=04d6eb5847) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | [141222a198](https://linux-hardware.org/?probe=141222a198) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | [2f2541bbf1](https://linux-hardware.org/?probe=2f2541bbf1) | Mar 08, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [4b82b56d82](https://linux-hardware.org/?probe=4b82b56d82) | Mar 08, 2023 |
| Infinix       | INBOOK X2 GEN11             | [3d14886d4c](https://linux-hardware.org/?probe=3d14886d4c) | Mar 07, 2023 |
| Infinix       | INBOOK X2 GEN11             | [124b1af920](https://linux-hardware.org/?probe=124b1af920) | Mar 07, 2023 |
| Dell          | Latitude 5330               | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [d62df340f9](https://linux-hardware.org/?probe=d62df340f9) | Mar 06, 2023 |
| Acer          | Predator PH315-55           | [8465c0241c](https://linux-hardware.org/?probe=8465c0241c) | Mar 06, 2023 |
| Alienware     | Area-51m R2                 | [5726561947](https://linux-hardware.org/?probe=5726561947) | Mar 06, 2023 |
| Unknown       | Unknown                     | [8b7f7b9440](https://linux-hardware.org/?probe=8b7f7b9440) | Mar 05, 2023 |
| Dell          | Inspiron 17-7779            | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| Google        | Delbin                      | [3817b0d62d](https://linux-hardware.org/?probe=3817b0d62d) | Mar 05, 2023 |
| Dell          | XPS 15 9500                 | [47df9846bb](https://linux-hardware.org/?probe=47df9846bb) | Mar 04, 2023 |
| HP            | Pavilion 15                 | [50a27abb52](https://linux-hardware.org/?probe=50a27abb52) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [645b47cfa2](https://linux-hardware.org/?probe=645b47cfa2) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| Acer          | Nitro AN515-45              | [c3043c0cba](https://linux-hardware.org/?probe=c3043c0cba) | Mar 03, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| Dell          | Latitude 5421               | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| Sony          | SVF1521Q1EW                 | [3c74542aad](https://linux-hardware.org/?probe=3c74542aad) | Mar 02, 2023 |
| Sony          | SVF1521Q1EW                 | [7b7db7c319](https://linux-hardware.org/?probe=7b7db7c319) | Mar 02, 2023 |
| Dell          | Vostro 3500                 | [4e540e33b1](https://linux-hardware.org/?probe=4e540e33b1) | Mar 01, 2023 |
| Positivo      | C14CR21                     | [d0041f93e1](https://linux-hardware.org/?probe=d0041f93e1) | Mar 01, 2023 |
| HP            | EliteBook 755 G5            | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Dell          | Latitude E7450              | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [3ab9ad10d8](https://linux-hardware.org/?probe=3ab9ad10d8) | Feb 28, 2023 |
| Dell          | XPS 13 9380                 | [e888e1330d](https://linux-hardware.org/?probe=e888e1330d) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | [18fdb45ec1](https://linux-hardware.org/?probe=18fdb45ec1) | Feb 27, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [da19f23a14](https://linux-hardware.org/?probe=da19f23a14) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| System76      | Serval WS                   | [1b136ec80d](https://linux-hardware.org/?probe=1b136ec80d) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| HP            | G60                         | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Manjaro        | 1702      | 38.07%  |
| Manjaro 22.0.0 | 188       | 4.2%    |
| Manjaro 20.2.1 | 163       | 3.65%   |
| Manjaro 20.1   | 142       | 3.18%   |
| Manjaro 20.2   | 140       | 3.13%   |
| Manjaro 20.0.3 | 125       | 2.8%    |
| Manjaro 21.2.6 | 113       | 2.53%   |
| Manjaro 23.0.0 | 104       | 2.33%   |
| Manjaro 21.1.0 | 89        | 1.99%   |
| Manjaro 18.1.5 | 83        | 1.86%   |
| Manjaro 21.2.0 | 72        | 1.61%   |
| Manjaro 21.0.7 | 70        | 1.57%   |
| Manjaro 21.2.5 | 65        | 1.45%   |
| Manjaro 21.1.6 | 63        | 1.41%   |
| Manjaro 19.0.2 | 55        | 1.23%   |
| Manjaro 20.0   | 52        | 1.16%   |
| Manjaro 23.1.0 | 48        | 1.07%   |
| Manjaro 21.2.1 | 48        | 1.07%   |
| Manjaro 18.0.4 | 47        | 1.05%   |
| Manjaro 21.0   | 46        | 1.03%   |
| Manjaro 21.0.5 | 44        | 0.98%   |
| Manjaro 22.1.0 | 41        | 0.92%   |
| Manjaro 20.1.1 | 41        | 0.92%   |
| Manjaro 20.1.2 | 40        | 0.89%   |
| Manjaro 22.0.4 | 37        | 0.83%   |
| Manjaro 21.2.3 | 37        | 0.83%   |
| Manjaro 20.0.1 | 36        | 0.81%   |
| Manjaro 21.3.7 | 34        | 0.76%   |
| Manjaro 21.2.2 | 31        | 0.69%   |
| Manjaro 21.0.4 | 31        | 0.69%   |
| Manjaro 21.3.6 | 29        | 0.65%   |
| Manjaro 21.2.4 | 29        | 0.65%   |
| Manjaro 23.0.4 | 27        | 0.6%    |
| Manjaro 21.1.2 | 25        | 0.56%   |
| Manjaro 23.1.3 | 24        | 0.54%   |
| Manjaro 21.1.4 | 24        | 0.54%   |
| Manjaro 23.0.2 | 23        | 0.51%   |
| Manjaro 22.0.5 | 23        | 0.51%   |
| Manjaro 21.0.1 | 20        | 0.45%   |
| Manjaro 18.1.4 | 20        | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Manjaro | 4101      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 161       | 3.33%   |
| 5.13.19-2-MANJARO | 95        | 1.97%   |
| 5.9.11-3-MANJARO  | 73        | 1.51%   |
| 5.8.11-1-MANJARO  | 69        | 1.43%   |
| 5.8.6-1-MANJARO   | 68        | 1.41%   |
| 5.15.32-1-MANJARO | 63        | 1.3%    |
| 5.15.28-1-MANJARO | 61        | 1.26%   |
| 5.10.42-1-MANJARO | 57        | 1.18%   |
| 5.8.18-1-MANJARO  | 55        | 1.14%   |
| 5.15.12-1-MANJARO | 52        | 1.08%   |
| 6.1.1-1-MANJARO   | 51        | 1.06%   |
| 6.1.12-1-MANJARO  | 49        | 1.01%   |
| 6.1.31-2-MANJARO  | 48        | 0.99%   |
| 5.8.16-2-MANJARO  | 41        | 0.85%   |
| 5.15.65-1-MANJARO | 40        | 0.83%   |
| 5.10.2-2-MANJARO  | 40        | 0.83%   |
| 5.6.16-1-MANJARO  | 39        | 0.81%   |
| 5.15.60-1-MANJARO | 39        | 0.81%   |
| 5.10.7-3-MANJARO  | 38        | 0.79%   |
| 5.12.9-1-MANJARO  | 36        | 0.75%   |
| 6.5.5-1-MANJARO   | 35        | 0.72%   |
| 6.6.8-2-MANJARO   | 33        | 0.68%   |
| 5.6.19-2-MANJARO  | 33        | 0.68%   |
| 5.15.74-3-MANJARO | 31        | 0.64%   |
| 5.15.7-1-MANJARO  | 31        | 0.64%   |
| 5.7.9-1-MANJARO   | 30        | 0.62%   |
| 5.6.15-1-MANJARO  | 30        | 0.62%   |
| 5.15.81-1-MANJARO | 30        | 0.62%   |
| 5.15.78-1-MANJARO | 30        | 0.62%   |
| 5.15.41-1-MANJARO | 30        | 0.62%   |
| 5.10.36-2-MANJARO | 30        | 0.62%   |
| 5.7.17-2-MANJARO  | 29        | 0.6%    |
| 5.7.0-3-MANJARO   | 29        | 0.6%    |
| 5.8.3-2-MANJARO   | 28        | 0.58%   |
| 5.15.25-1-MANJARO | 28        | 0.58%   |
| 5.14.10-1-MANJARO | 28        | 0.58%   |
| 5.10.34-1-MANJARO | 27        | 0.56%   |
| 6.5.3-1-MANJARO   | 25        | 0.52%   |
| 5.16.14-1-MANJARO | 25        | 0.52%   |
| 5.15.85-1-MANJARO | 25        | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.16  | 161       | 3.34%   |
| 5.13.19 | 96        | 1.99%   |
| 5.9.11  | 77        | 1.6%    |
| 5.8.11  | 69        | 1.43%   |
| 5.8.6   | 68        | 1.41%   |
| 5.15.32 | 64        | 1.33%   |
| 5.15.28 | 61        | 1.26%   |
| 5.10.42 | 57        | 1.18%   |
| 5.8.18  | 55        | 1.14%   |
| 6.1.31  | 53        | 1.1%    |
| 5.15.12 | 52        | 1.08%   |
| 6.1.1   | 51        | 1.06%   |
| 6.1.12  | 49        | 1.02%   |
| 5.8.16  | 42        | 0.87%   |
| 5.15.65 | 40        | 0.83%   |
| 5.10.2  | 40        | 0.83%   |
| 5.6.16  | 39        | 0.81%   |
| 5.15.60 | 39        | 0.81%   |
| 5.10.7  | 39        | 0.81%   |
| 5.7.0   | 36        | 0.75%   |
| 5.12.9  | 36        | 0.75%   |
| 6.5.5   | 35        | 0.73%   |
| 5.6.19  | 35        | 0.73%   |
| 6.6.8   | 33        | 0.68%   |
| 5.9.1   | 33        | 0.68%   |
| 5.15.74 | 32        | 0.66%   |
| 5.15.7  | 32        | 0.66%   |
| 5.7.9   | 30        | 0.62%   |
| 5.6.15  | 30        | 0.62%   |
| 5.17.1  | 30        | 0.62%   |
| 5.15.81 | 30        | 0.62%   |
| 5.15.78 | 30        | 0.62%   |
| 5.15.41 | 30        | 0.62%   |
| 5.10.36 | 30        | 0.62%   |
| 5.7.17  | 29        | 0.6%    |
| 5.8.3   | 28        | 0.58%   |
| 5.15.25 | 28        | 0.58%   |
| 5.14.10 | 28        | 0.58%   |
| 5.10.34 | 27        | 0.56%   |
| 5.19.0  | 26        | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 730       | 16.05%  |
| 5.10    | 508       | 11.17%  |
| 6.1     | 427       | 9.39%   |
| 5.4     | 360       | 7.92%   |
| 5.9     | 322       | 7.08%   |
| 5.8     | 291       | 6.4%    |
| 5.13    | 204       | 4.49%   |
| 5.6     | 199       | 4.38%   |
| 5.7     | 137       | 3.01%   |
| 6.5     | 133       | 2.92%   |
| 4.19    | 121       | 2.66%   |
| 5.16    | 100       | 2.2%    |
| 6.6     | 97        | 2.13%   |
| 5.12    | 94        | 2.07%   |
| 6.0     | 82        | 1.8%    |
| 5.11    | 81        | 1.78%   |
| 5.14    | 77        | 1.69%   |
| 5.19    | 74        | 1.63%   |
| 5.18    | 70        | 1.54%   |
| 5.17    | 70        | 1.54%   |
| 5.3     | 64        | 1.41%   |
| 5.5     | 62        | 1.36%   |
| 6.4     | 45        | 0.99%   |
| 6.2     | 45        | 0.99%   |
| 6.3     | 44        | 0.97%   |
| 4.14    | 25        | 0.55%   |
| 5.2     | 23        | 0.51%   |
| 5.0     | 17        | 0.37%   |
| 6.7     | 14        | 0.31%   |
| 5.1     | 13        | 0.29%   |
| 4.20    | 9         | 0.2%    |
| 4.18    | 7         | 0.15%   |
| 4.9     | 2         | 0.04%   |
| 4.16    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 4099      | 99.95%  |
| i686   | 2         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| KDE5                 | 1569      | 37.22%  |
| GNOME                | 918       | 21.77%  |
| XFCE                 | 885       | 20.99%  |
| KDE                  | 281       | 6.67%   |
| Unknown              | 204       | 4.84%   |
| X-Cinnamon           | 99        | 2.35%   |
| i3                   | 88        | 2.09%   |
| MATE                 | 42        | 1%      |
| Cinnamon             | 31        | 0.74%   |
| Deepin               | 25        | 0.59%   |
| Budgie               | 16        | 0.38%   |
| Awesome              | 11        | 0.26%   |
| sway                 | 9         | 0.21%   |
| LXQt                 | 8         | 0.19%   |
| LXDE                 | 6         | 0.14%   |
| qtile                | 3         | 0.07%   |
| i3-with-shmlog       | 3         | 0.07%   |
| Hyprland             | 3         | 0.07%   |
| leftwm               | 2         | 0.05%   |
| GNOME Flashback      | 2         | 0.05%   |
| DWM                  | 2         | 0.05%   |
| bspwm                | 2         | 0.05%   |
| Yaru:ubuntu:GNOME    | 1         | 0.02%   |
| xinitrc              | 1         | 0.02%   |
| Unity                | 1         | 0.02%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.02%   |
| herbstluftwm         | 1         | 0.02%   |
| GNOME Classic        | 1         | 0.02%   |
| Enlightenment        | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3398      | 81.51%  |
| Wayland | 639       | 15.33%  |
| Unknown | 97        | 2.33%   |
| Tty     | 35        | 0.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1691      | 40.33%  |
| SDDM    | 1061      | 25.3%   |
| LightDM | 738       | 17.6%   |
| GDM     | 565       | 13.47%  |
| TDM     | 123       | 2.93%   |
| LXDM    | 5         | 0.12%   |
| GREETD  | 5         | 0.12%   |
| Ly      | 2         | 0.05%   |
| XDM     | 1         | 0.02%   |
| SLiM    | 1         | 0.02%   |
| CDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1771      | 42.71%  |
| de_DE   | 304       | 7.33%   |
| ru_RU   | 289       | 6.97%   |
| en_GB   | 276       | 6.66%   |
| Unknown | 251       | 6.05%   |
| pt_BR   | 175       | 4.22%   |
| fr_FR   | 111       | 2.68%   |
| it_IT   | 93        | 2.24%   |
| es_ES   | 82        | 1.98%   |
| pl_PL   | 74        | 1.78%   |
| en_CA   | 73        | 1.76%   |
| en_IN   | 63        | 1.52%   |
| es_MX   | 49        | 1.18%   |
| en_AU   | 44        | 1.06%   |
| zh_CN   | 37        | 0.89%   |
| de_AT   | 24        | 0.58%   |
| ru_UA   | 20        | 0.48%   |
| nl_NL   | 19        | 0.46%   |
| es_AR   | 18        | 0.43%   |
| C       | 18        | 0.43%   |
| pt_PT   | 16        | 0.39%   |
| en_IE   | 16        | 0.39%   |
| tr_TR   | 14        | 0.34%   |
| es_CL   | 14        | 0.34%   |
| cs_CZ   | 14        | 0.34%   |
| sv_SE   | 13        | 0.31%   |
| en_DK   | 13        | 0.31%   |
| de_CH   | 13        | 0.31%   |
| uk_UA   | 12        | 0.29%   |
| hu_HU   | 12        | 0.29%   |
| es_CO   | 12        | 0.29%   |
| el_GR   | 11        | 0.27%   |
| fi_FI   | 10        | 0.24%   |
| en_ZA   | 10        | 0.24%   |
| en_NZ   | 10        | 0.24%   |
| nl_BE   | 9         | 0.22%   |
| zh_TW   | 7         | 0.17%   |
| ro_RO   | 7         | 0.17%   |
| nb_NO   | 7         | 0.17%   |
| ja_JP   | 7         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 2159      | 51.9%   |
| EFI  | 2001      | 48.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3422      | 82.68%  |
| Btrfs    | 410       | 9.91%   |
| Overlay  | 91        | 2.2%    |
| Unknown  | 83        | 2.01%   |
| Tmpfs    | 73        | 1.76%   |
| Xfs      | 38        | 0.92%   |
| F2fs     | 12        | 0.29%   |
| Ext3     | 4         | 0.1%    |
| Reiserfs | 3         | 0.07%   |
| Ext2     | 2         | 0.05%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2026      | 48.54%  |
| Unknown | 1806      | 43.27%  |
| MBR     | 342       | 8.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3746      | 90.31%  |
| Yes       | 402       | 9.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2978      | 71.59%  |
| Yes       | 1182      | 28.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 1016      | 24.77%  |
| Hewlett-Packard      | 701       | 17.09%  |
| Dell                 | 596       | 14.53%  |
| ASUSTek Computer     | 499       | 12.17%  |
| Acer                 | 332       | 8.1%    |
| MSI                  | 117       | 2.85%   |
| Apple                | 103       | 2.51%   |
| HUAWEI               | 77        | 1.88%   |
| Toshiba              | 64        | 1.56%   |
| Samsung Electronics  | 63        | 1.54%   |
| Timi                 | 41        | 1%      |
| Sony                 | 34        | 0.83%   |
| Google               | 34        | 0.83%   |
| Notebook             | 33        | 0.8%    |
| Fujitsu              | 33        | 0.8%    |
| TUXEDO               | 26        | 0.63%   |
| Unknown              | 22        | 0.54%   |
| Razer                | 17        | 0.41%   |
| Alienware            | 17        | 0.41%   |
| Schenker             | 14        | 0.34%   |
| HONOR                | 13        | 0.32%   |
| Packard Bell         | 12        | 0.29%   |
| LG Electronics       | 12        | 0.29%   |
| Gigabyte Technology  | 12        | 0.29%   |
| Framework            | 12        | 0.29%   |
| Chuwi                | 10        | 0.24%   |
| Positivo             | 9         | 0.22%   |
| Panasonic            | 9         | 0.22%   |
| Medion               | 9         | 0.22%   |
| System76             | 8         | 0.2%    |
| Clevo                | 8         | 0.2%    |
| Monster              | 6         | 0.15%   |
| GPD                  | 6         | 0.15%   |
| Multilaser           | 5         | 0.12%   |
| MECHREVO             | 5         | 0.12%   |
| Star Labs            | 4         | 0.1%    |
| PC Specialist        | 4         | 0.1%    |
| Intel Client Systems | 4         | 0.1%    |
| Gateway              | 4         | 0.1%    |
| TrekStor             | 3         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 32        | 0.78%   |
| HP Notebook                          | 24        | 0.59%   |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 16        | 0.39%   |
| Lenovo Legion 5 15ARH05 82B5         | 14        | 0.34%   |
| Dell XPS 13 9310                     | 14        | 0.34%   |
| Dell XPS 15 9500                     | 13        | 0.32%   |
| HP Pavilion Notebook                 | 12        | 0.29%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 11        | 0.27%   |
| HP Pavilion dv7                      | 11        | 0.27%   |
| Dell Inspiron 3542                   | 11        | 0.27%   |
| Apple MacBookPro9,2                  | 11        | 0.27%   |
| HP Pavilion dv6                      | 10        | 0.24%   |
| HP Pavilion 15                       | 10        | 0.24%   |
| HP OMEN by Laptop                    | 10        | 0.24%   |
| HP Laptop 15-bs0xx                   | 10        | 0.24%   |
| Dell XPS 15 7590                     | 10        | 0.24%   |
| Apple MacBookAir7,2                  | 10        | 0.24%   |
| HP Pavilion g6                       | 9         | 0.22%   |
| HP 15                                | 9         | 0.22%   |
| Dell XPS 15 9570                     | 9         | 0.22%   |
| Dell XPS 15 9560                     | 9         | 0.22%   |
| Dell XPS 13 7390                     | 9         | 0.22%   |
| Dell Latitude E6430                  | 9         | 0.22%   |
| Lenovo Z50-70 20354                  | 8         | 0.2%    |
| Lenovo Y520-15IKBN 80WK              | 8         | 0.2%    |
| Lenovo Legion 5 15ARH05H 82B1        | 8         | 0.2%    |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 8         | 0.2%    |
| HP Laptop 15s-eq2xxx                 | 8         | 0.2%    |
| HP 250 G7 Notebook PC                | 8         | 0.2%    |
| Dell Inspiron N5110                  | 8         | 0.2%    |
| ASUS TUF Gaming FX505DT_FX505DT      | 8         | 0.2%    |
| Apple MacBookPro8,1                  | 8         | 0.2%    |
| Timi TM1701                          | 7         | 0.17%   |
| Lenovo Yoga Slim 7 14ARE05 82A2      | 7         | 0.17%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 7         | 0.17%   |
| HUAWEI NBLK-WAX9X                    | 7         | 0.17%   |
| HUAWEI KLVL-WXX9                     | 7         | 0.17%   |
| HP EliteBook 8470p                   | 7         | 0.17%   |
| Dell Latitude E5530 non-vPro         | 7         | 0.17%   |
| Dell Latitude 5480                   | 7         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 476       | 11.61%  |
| Lenovo IdeaPad     | 268       | 6.53%   |
| Acer Aspire        | 212       | 5.17%   |
| Dell Inspiron      | 185       | 4.51%   |
| Dell Latitude      | 161       | 3.93%   |
| HP Pavilion        | 153       | 3.73%   |
| Dell XPS           | 114       | 2.78%   |
| HP Laptop          | 113       | 2.76%   |
| HP EliteBook       | 107       | 2.61%   |
| HP ProBook         | 105       | 2.56%   |
| ASUS VivoBook      | 92        | 2.24%   |
| Lenovo Legion      | 83        | 2.02%   |
| ASUS ROG           | 63        | 1.54%   |
| Toshiba Satellite  | 57        | 1.39%   |
| Dell Precision     | 51        | 1.24%   |
| Dell Vostro        | 41        | 1%      |
| ASUS ZenBook       | 40        | 0.98%   |
| Acer Swift         | 39        | 0.95%   |
| Acer Nitro         | 35        | 0.85%   |
| HP OMEN            | 32        | 0.78%   |
| ASUS TUF           | 32        | 0.78%   |
| Unknown            | 32        | 0.78%   |
| Fujitsu LIFEBOOK   | 29        | 0.71%   |
| Lenovo ThinkBook   | 28        | 0.68%   |
| ASUS ASUS          | 28        | 0.68%   |
| HP ENVY            | 27        | 0.66%   |
| Lenovo Yoga        | 25        | 0.61%   |
| HP Notebook        | 24        | 0.59%   |
| HP ZBook           | 23        | 0.56%   |
| HP 250             | 22        | 0.54%   |
| Timi RedmiBook     | 16        | 0.39%   |
| Razer Blade        | 16        | 0.39%   |
| HP Compaq          | 16        | 0.39%   |
| Acer Predator      | 16        | 0.39%   |
| Dell G3            | 15        | 0.37%   |
| Acer TravelMate    | 15        | 0.37%   |
| HP 255             | 14        | 0.34%   |
| HP 15              | 14        | 0.34%   |
| Apple MacBookPro11 | 14        | 0.34%   |
| Apple MacBookPro9  | 13        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 549       | 13.39%  |
| 2019    | 509       | 12.41%  |
| 2018    | 406       | 9.9%    |
| 2021    | 394       | 9.61%   |
| 2017    | 322       | 7.85%   |
| 2012    | 291       | 7.1%    |
| 2014    | 237       | 5.78%   |
| 2013    | 230       | 5.61%   |
| 2015    | 208       | 5.07%   |
| 2011    | 208       | 5.07%   |
| 2016    | 206       | 5.02%   |
| 2022    | 162       | 3.95%   |
| 2010    | 119       | 2.9%    |
| 2008    | 93        | 2.27%   |
| 2023    | 58        | 1.41%   |
| 2009    | 57        | 1.39%   |
| 2007    | 40        | 0.98%   |
| 2006    | 8         | 0.2%    |
| Unknown | 3         | 0.07%   |
| 2005    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4101      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4099      | 99.9%   |
| Enabled  | 4         | 0.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4049      | 98.73%  |
| Yes  | 52        | 1.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1226      | 29.57%  |
| 16.01-24.0  | 881       | 21.25%  |
| 8.01-16.0   | 871       | 21.01%  |
| 3.01-4.0    | 574       | 13.84%  |
| 32.01-64.0  | 355       | 8.56%   |
| 24.01-32.0  | 81        | 1.95%   |
| 1.01-2.0    | 70        | 1.69%   |
| 64.01-256.0 | 56        | 1.35%   |
| 2.01-3.0    | 31        | 0.75%   |
| 0.51-1.0    | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1222      | 26.95%  |
| 1.01-2.0   | 1098      | 24.21%  |
| 4.01-8.0   | 967       | 21.32%  |
| 3.01-4.0   | 799       | 17.62%  |
| 8.01-16.0  | 270       | 5.95%   |
| 0.51-1.0   | 142       | 3.13%   |
| 16.01-24.0 | 20        | 0.44%   |
| 24.01-32.0 | 8         | 0.18%   |
| 0.01-0.5   | 7         | 0.15%   |
| 32.01-64.0 | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2841      | 67.98%  |
| 2      | 1149      | 27.49%  |
| 3      | 150       | 3.59%   |
| 0      | 19        | 0.45%   |
| 4      | 17        | 0.41%   |
| 7      | 2         | 0.05%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3108      | 75.4%   |
| Yes       | 1014      | 24.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3120      | 75.82%  |
| No        | 995       | 24.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4057      | 98.83%  |
| No        | 48        | 1.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3403      | 82.34%  |
| No        | 730       | 17.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 604       | 14.62%  |
| Germany     | 456       | 11.04%  |
| Russia      | 383       | 9.27%   |
| Brazil      | 252       | 6.1%    |
| France      | 159       | 3.85%   |
| Italy       | 145       | 3.51%   |
| UK          | 140       | 3.39%   |
| Poland      | 125       | 3.03%   |
| Canada      | 113       | 2.74%   |
| Spain       | 111       | 2.69%   |
| India       | 106       | 2.57%   |
| Netherlands | 100       | 2.42%   |
| Ukraine     | 89        | 2.15%   |
| Mexico      | 70        | 1.69%   |
| China       | 59        | 1.43%   |
| Austria     | 56        | 1.36%   |
| Australia   | 52        | 1.26%   |
| Turkey      | 48        | 1.16%   |
| Sweden      | 47        | 1.14%   |
| Switzerland | 42        | 1.02%   |
| Romania     | 41        | 0.99%   |
| Indonesia   | 40        | 0.97%   |
| Czechia     | 37        | 0.9%    |
| Portugal    | 36        | 0.87%   |
| Belgium     | 36        | 0.87%   |
| Belarus     | 34        | 0.82%   |
| Greece      | 33        | 0.8%    |
| Hungary     | 32        | 0.77%   |
| Bulgaria    | 29        | 0.7%    |
| Norway      | 28        | 0.68%   |
| Finland     | 28        | 0.68%   |
| Argentina   | 27        | 0.65%   |
| Colombia    | 25        | 0.61%   |
| Denmark     | 23        | 0.56%   |
| Taiwan      | 22        | 0.53%   |
| Chile       | 21        | 0.51%   |
| Iran        | 20        | 0.48%   |
| Bangladesh  | 19        | 0.46%   |
| Japan       | 17        | 0.41%   |
| Croatia     | 17        | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 95        | 2.18%   |
| St Petersburg     | 55        | 1.26%   |
| Berlin            | 38        | 0.87%   |
| Vienna            | 37        | 0.85%   |
| Paris             | 36        | 0.83%   |
| Sao Paulo         | 31        | 0.71%   |
| Kyiv              | 26        | 0.6%    |
| Amsterdam         | 26        | 0.6%    |
| Warsaw            | 25        | 0.57%   |
| Frankfurt am Main | 24        | 0.55%   |
| Milan             | 21        | 0.48%   |
| Munich            | 20        | 0.46%   |
| Minsk             | 20        | 0.46%   |
| Bengaluru         | 20        | 0.46%   |
| Toronto           | 18        | 0.41%   |
| Prague            | 18        | 0.41%   |
| Novosibirsk       | 18        | 0.41%   |
| Madrid            | 18        | 0.41%   |
| Istanbul          | 18        | 0.41%   |
| Helsinki          | 16        | 0.37%   |
| Hamburg           | 16        | 0.37%   |
| Rome              | 15        | 0.34%   |
| Mexico City       | 15        | 0.34%   |
| Melbourne         | 15        | 0.34%   |
| London            | 15        | 0.34%   |
| Budapest          | 15        | 0.34%   |
| Bucharest         | 15        | 0.34%   |
| Yekaterinburg     | 13        | 0.3%    |
| The Hague         | 13        | 0.3%    |
| Seattle           | 13        | 0.3%    |
| Dhaka             | 13        | 0.3%    |
| Brasília         | 13        | 0.3%    |
| Barcelona         | 13        | 0.3%    |
| Athens            | 13        | 0.3%    |
| Sofia             | 12        | 0.28%   |
| Cologne           | 12        | 0.28%   |
| Bogotá           | 12        | 0.28%   |
| Belgrade          | 12        | 0.28%   |
| Zagreb            | 11        | 0.25%   |
| Sydney            | 11        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 969       | 1280   | 17.94%  |
| WDC                            | 552       | 665    | 10.22%  |
| Seagate                        | 500       | 645    | 9.26%   |
| SanDisk                        | 387       | 492    | 7.17%   |
| Toshiba                        | 386       | 452    | 7.15%   |
| Kingston                       | 289       | 335    | 5.35%   |
| SK hynix                       | 275       | 335    | 5.09%   |
| Unknown                        | 273       | 331    | 5.05%   |
| Crucial                        | 194       | 241    | 3.59%   |
| Intel                          | 183       | 229    | 3.39%   |
| Micron Technology              | 150       | 192    | 2.78%   |
| HGST                           | 149       | 178    | 2.76%   |
| Hitachi                        | 95        | 110    | 1.76%   |
| KIOXIA                         | 71        | 82     | 1.31%   |
| A-DATA Technology              | 65        | 78     | 1.2%    |
| Apple                          | 64        | 78     | 1.18%   |
| China                          | 48        | 51     | 0.89%   |
| Phison                         | 47        | 69     | 0.87%   |
| Micron/Crucial Technology      | 36        | 44     | 0.67%   |
| Silicon Motion                 | 34        | 39     | 0.63%   |
| Phison Electronics             | 34        | 38     | 0.63%   |
| Transcend                      | 33        | 39     | 0.61%   |
| LITEONIT                       | 28        | 34     | 0.52%   |
| GOODRAM                        | 28        | 47     | 0.52%   |
| LITEON                         | 27        | 30     | 0.5%    |
| JMicron Technology             | 21        | 22     | 0.39%   |
| Kingston Technology Company    | 20        | 20     | 0.37%   |
| Union Memory (Shenzhen)        | 16        | 16     | 0.3%    |
| SPCC                           | 15        | 17     | 0.28%   |
| ADATA Technology               | 15        | 17     | 0.28%   |
| Plextor                        | 14        | 22     | 0.26%   |
| Intenso                        | 14        | 15     | 0.26%   |
| Unknown                        | 14        | 17     | 0.26%   |
| Solid State Storage Technology | 12        | 20     | 0.22%   |
| Patriot                        | 12        | 12     | 0.22%   |
| PNY                            | 10        | 14     | 0.19%   |
| Fujitsu                        | 10        | 10     | 0.19%   |
| XPG                            | 9         | 15     | 0.17%   |
| Solid State Storage            | 9         | 9      | 0.17%   |
| Realtek Semiconductor          | 9         | 10     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 98        | 1.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 96        | 1.7%    |
| Samsung NVMe SSD Drive 512GB                       | 65        | 1.15%   |
| Toshiba MQ01ABD100 1TB                             | 59        | 1.05%   |
| HGST HTS721010A9E630 1TB                           | 55        | 0.98%   |
| Toshiba MQ04ABF100 1TB                             | 52        | 0.92%   |
| SK hynix NVMe SSD Drive 512GB                      | 46        | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 45        | 0.8%    |
| SanDisk NVMe SSD Drive 512GB                       | 43        | 0.76%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 43        | 0.76%   |
| Kingston SA400S37240G 240GB SSD                    | 43        | 0.76%   |
| Unknown MMC Card  64GB                             | 41        | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 39        | 0.69%   |
| Unknown MMC Card  32GB                             | 38        | 0.67%   |
| Toshiba MQ01ABF050 500GB                           | 37        | 0.66%   |
| Crucial CT500MX500SSD1 500GB                       | 33        | 0.59%   |
| Kingston SA400S37480G 480GB SSD                    | 31        | 0.55%   |
| Intel NVMe SSD Drive 512GB                         | 30        | 0.53%   |
| Unknown SD/MMC/MS PRO 256GB                        | 29        | 0.51%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 29        | 0.51%   |
| Samsung NVMe SSD Drive 1TB                         | 29        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                        | 28        | 0.5%    |
| Seagate ST1000LM049-2GH172 1TB                     | 26        | 0.46%   |
| SanDisk NVMe SSD Drive 256GB                       | 26        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB                    | 25        | 0.44%   |
| Unknown MMC Card  128GB                            | 24        | 0.43%   |
| Samsung SSD 860 EVO 500GB                          | 24        | 0.43%   |
| Samsung SSD 850 EVO 500GB                          | 24        | 0.43%   |
| Kingston SA400S37120G 120GB SSD                    | 24        | 0.43%   |
| HGST HTS545050A7E680 500GB                         | 24        | 0.43%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 23        | 0.41%   |
| Samsung NVMe SSD Drive 1024GB                      | 23        | 0.41%   |
| SK hynix NVMe SSD Drive 256GB                      | 22        | 0.39%   |
| Seagate ST9500325AS 500GB                          | 22        | 0.39%   |
| Seagate Expansion 1TB                              | 22        | 0.39%   |
| WDC WD10SPZX-24Z10 1TB                             | 20        | 0.35%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 20        | 0.35%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 20        | 0.35%   |
| Intel SSD 660P Series 1024GB                       | 20        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 19        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 486       | 622    | 34.08%  |
| WDC                 | 361       | 427    | 25.32%  |
| Toshiba             | 243       | 281    | 17.04%  |
| HGST                | 149       | 178    | 10.45%  |
| Hitachi             | 95        | 110    | 6.66%   |
| Unknown             | 31        | 34     | 2.17%   |
| Samsung Electronics | 15        | 17     | 1.05%   |
| JMicron Technology  | 11        | 11     | 0.77%   |
| Fujitsu             | 10        | 10     | 0.7%    |
| Apple               | 6         | 7      | 0.42%   |
| TO Exter            | 4         | 5      | 0.28%   |
| SSK                 | 2         | 3      | 0.14%   |
| Intenso             | 2         | 2      | 0.14%   |
| USB3.0              | 1         | 1      | 0.07%   |
| QNAP                | 1         | 1      | 0.07%   |
| MARSHAL             | 1         | 1      | 0.07%   |
| KESU                | 1         | 1      | 0.07%   |
| Inateck             | 1         | 1      | 0.07%   |
| Hewlett-Packard     | 1         | 1      | 0.07%   |
| External            | 1         | 1      | 0.07%   |
| ASMT                | 1         | 1      | 0.07%   |
| Apricorn            | 1         | 1      | 0.07%   |
| ACASIS              | 1         | 1      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 376       | 470    | 22.66%  |
| Kingston            | 207       | 233    | 12.48%  |
| Crucial             | 181       | 228    | 10.91%  |
| SanDisk             | 140       | 187    | 8.44%   |
| WDC                 | 95        | 114    | 5.73%   |
| Micron Technology   | 55        | 72     | 3.32%   |
| A-DATA Technology   | 50        | 58     | 3.01%   |
| SK hynix            | 48        | 59     | 2.89%   |
| China               | 48        | 51     | 2.89%   |
| Apple               | 42        | 47     | 2.53%   |
| Intel               | 40        | 46     | 2.41%   |
| Toshiba             | 34        | 40     | 2.05%   |
| Transcend           | 31        | 36     | 1.87%   |
| LITEONIT            | 28        | 34     | 1.69%   |
| GOODRAM             | 27        | 46     | 1.63%   |
| LITEON              | 24        | 27     | 1.45%   |
| Plextor             | 13        | 21     | 0.78%   |
| Intenso             | 12        | 13     | 0.72%   |
| Patriot             | 11        | 11     | 0.66%   |
| SPCC                | 10        | 11     | 0.6%    |
| PNY                 | 9         | 13     | 0.54%   |
| OCZ                 | 9         | 10     | 0.54%   |
| Netac               | 9         | 15     | 0.54%   |
| KingSpec            | 8         | 9      | 0.48%   |
| Unknown             | 7         | 10     | 0.42%   |
| Seagate             | 6         | 10     | 0.36%   |
| Apacer              | 6         | 6      | 0.36%   |
| Hewlett-Packard     | 5         | 8      | 0.3%    |
| Corsair             | 5         | 5      | 0.3%    |
| SABRENT             | 4         | 4      | 0.24%   |
| Mushkin             | 4         | 6      | 0.24%   |
| Lexar               | 4         | 4      | 0.24%   |
| FORESEE             | 4         | 4      | 0.24%   |
| Emtec               | 4         | 4      | 0.24%   |
| BHT                 | 4         | 5      | 0.24%   |
| Unknown             | 3         | 4      | 0.18%   |
| TwinMOS             | 3         | 5      | 0.18%   |
| Team                | 3         | 4      | 0.18%   |
| Gigabyte Technology | 3         | 4      | 0.18%   |
| XrayDisk            | 2         | 2      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1883      | 2570   | 37.09%  |
| SSD     | 1532      | 2049   | 30.18%  |
| HDD     | 1368      | 1718   | 26.95%  |
| MMC     | 226       | 277    | 4.45%   |
| Unknown | 68        | 81     | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2493      | 3593   | 51.87%  |
| NVMe | 1882      | 2556   | 39.16%  |
| MMC  | 226       | 277    | 4.7%    |
| SAS  | 205       | 269    | 4.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1781      | 2386   | 62.25%  |
| 0.51-1.0   | 976       | 1232   | 34.11%  |
| 1.01-2.0   | 79        | 102    | 2.76%   |
| 4.01-10.0  | 16        | 23     | 0.56%   |
| 3.01-4.0   | 6         | 21     | 0.21%   |
| 2.01-3.0   | 2         | 2      | 0.07%   |
| 10.01-20.0 | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1120      | 26.33%  |
| 251-500        | 1097      | 25.79%  |
| 501-1000       | 676       | 15.89%  |
| 1001-2000      | 352       | 8.27%   |
| Unknown        | 325       | 7.64%   |
| 51-100         | 263       | 6.18%   |
| 1-20           | 150       | 3.53%   |
| 21-50          | 119       | 2.8%    |
| More than 3000 | 83        | 1.95%   |
| 2001-3000      | 69        | 1.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1028      | 23.15%  |
| 21-50          | 834       | 18.78%  |
| 101-250        | 737       | 16.6%   |
| 51-100         | 660       | 14.86%  |
| 251-500        | 465       | 10.47%  |
| Unknown        | 325       | 7.32%   |
| 501-1000       | 267       | 6.01%   |
| 1001-2000      | 84        | 1.89%   |
| 2001-3000      | 20        | 0.45%   |
| More than 3000 | 18        | 0.41%   |
| 0              | 3         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 11     | 4.46%   |
| HGST HTS721010A9E630 1TB                            | 9         | 9      | 4.02%   |
| HGST HTS545050A7E680 500GB                          | 9         | 9      | 4.02%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 8      | 2.68%   |
| HGST HTS545050A7E380 500GB                          | 6         | 6      | 2.68%   |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 22     | 2.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 5      | 2.23%   |
| HGST HTS725050A7E630 500GB                          | 5         | 5      | 2.23%   |
| Seagate ST9320325AS 320GB                           | 4         | 5      | 1.79%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 1.34%   |
| Toshiba MQ01ABD050 500GB                            | 3         | 3      | 1.34%   |
| Seagate ST9500325AS 500GB                           | 3         | 4      | 1.34%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 1.34%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 1.34%   |
| Hitachi HTS723232A7A364 320GB                       | 3         | 3      | 1.34%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 1.34%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 3      | 0.89%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 2         | 2      | 0.89%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 0.89%   |
| Seagate ST9750420AS 752GB                           | 2         | 2      | 0.89%   |
| Seagate ST9500423AS 500GB                           | 2         | 2      | 0.89%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 2      | 0.89%   |
| Seagate ST1000LX015-1U7172 1TB                      | 2         | 5      | 0.89%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 3      | 0.89%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 2      | 0.89%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.89%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 0.89%   |
| Crucial CT525MX300SSD1 528GB                        | 2         | 2      | 0.89%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 1      | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 0.45%   |
| WDC WD800BEVS-22RST0 80GB                           | 1         | 1      | 0.45%   |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 1      | 0.45%   |
| WDC WD5000LPVX-08V0TT5 500GB                        | 1         | 1      | 0.45%   |
| WDC WD5000LPLX-00ZNTT0 500GB                        | 1         | 1      | 0.45%   |
| WDC WD5000LPCX-22VHAT0 500GB                        | 1         | 1      | 0.45%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 1      | 0.45%   |
| WDC WD5000BPVT-60HXZT3 500GB                        | 1         | 1      | 0.45%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 1      | 0.45%   |
| WDC WD5000BEVT-75A0RT0 500GB                        | 1         | 1      | 0.45%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 1      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 55        | 84     | 24.66%  |
| HGST                        | 34        | 34     | 15.25%  |
| WDC                         | 25        | 28     | 11.21%  |
| Toshiba                     | 24        | 28     | 10.76%  |
| Hitachi                     | 20        | 21     | 8.97%   |
| Samsung Electronics         | 9         | 10     | 4.04%   |
| Crucial                     | 9         | 12     | 4.04%   |
| SK hynix                    | 7         | 11     | 3.14%   |
| SanDisk                     | 6         | 6      | 2.69%   |
| Intel                       | 5         | 6      | 2.24%   |
| Micron Technology           | 4         | 6      | 1.79%   |
| Kingston                    | 4         | 4      | 1.79%   |
| LITEON                      | 3         | 3      | 1.35%   |
| A-DATA Technology           | 3         | 4      | 1.35%   |
| TwinMOS                     | 1         | 1      | 0.45%   |
| Realtek                     | 1         | 1      | 0.45%   |
| Netac                       | 1         | 1      | 0.45%   |
| MARSHAL                     | 1         | 1      | 0.45%   |
| LITEONIT                    | 1         | 1      | 0.45%   |
| Kingston Technology Company | 1         | 1      | 0.45%   |
| KingSpec                    | 1         | 1      | 0.45%   |
| IM3D                        | 1         | 1      | 0.45%   |
| Faspeed                     | 1         | 1      | 0.45%   |
| Corsair                     | 1         | 1      | 0.45%   |
| ASMT                        | 1         | 1      | 0.45%   |
| Apple                       | 1         | 1      | 0.45%   |
| Apacer                      | 1         | 1      | 0.45%   |
| ADATA Technology            | 1         | 1      | 0.45%   |
| Unknown                     | 1         | 1      | 0.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 84     | 35.71%  |
| HGST                | 34        | 34     | 22.08%  |
| WDC                 | 23        | 26     | 14.94%  |
| Toshiba             | 20        | 24     | 12.99%  |
| Hitachi             | 20        | 21     | 12.99%  |
| Samsung Electronics | 1         | 1      | 0.65%   |
| MARSHAL             | 1         | 1      | 0.65%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 153       | 191    | 69.23%  |
| SSD  | 57        | 69     | 25.79%  |
| NVMe | 11        | 12     | 4.98%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 33.33%  |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 33.33%  |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2608      | 4081   | 59.25%  |
| Works    | 1575      | 2339   | 35.78%  |
| Malfunc  | 216       | 272    | 4.91%   |
| Failed   | 3         | 3      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2639      | 51.07%  |
| Samsung Electronics                  | 642       | 12.43%  |
| AMD                                  | 574       | 11.11%  |
| SanDisk                              | 338       | 6.54%   |
| SK hynix                             | 225       | 4.35%   |
| Toshiba America Info Systems         | 105       | 2.03%   |
| Kingston Technology Company          | 102       | 1.97%   |
| Micron Technology                    | 94        | 1.82%   |
| Phison Electronics                   | 85        | 1.65%   |
| KIOXIA                               | 80        | 1.55%   |
| Micron/Crucial Technology            | 48        | 0.93%   |
| Silicon Motion                       | 36        | 0.7%    |
| ADATA Technology                     | 33        | 0.64%   |
| Union Memory (Shenzhen)              | 29        | 0.56%   |
| Solid State Storage Technology       | 22        | 0.43%   |
| Nvidia                               | 19        | 0.37%   |
| Apple                                | 15        | 0.29%   |
| Shenzhen Longsys Electronics         | 12        | 0.23%   |
| Realtek Semiconductor                | 12        | 0.23%   |
| Lite-On Technology                   | 12        | 0.23%   |
| MAXIO Technology (Hangzhou)          | 6         | 0.12%   |
| Marvell Technology Group             | 6         | 0.12%   |
| Yangtze Memory Technologies          | 5         | 0.1%    |
| Seagate Technology                   | 5         | 0.1%    |
| Lenovo                               | 4         | 0.08%   |
| Biwin Storage Technology             | 4         | 0.08%   |
| JMicron Technology                   | 3         | 0.06%   |
| ASMedia Technology                   | 3         | 0.06%   |
| Transcend                            | 2         | 0.04%   |
| Unknown                              | 2         | 0.04%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.02%   |
| Silicon Image                        | 1         | 0.02%   |
| Ramaxel Technology(Shenzhen) Limited | 1         | 0.02%   |
| Netac Technology                     | 1         | 0.02%   |
| INNOGRIT                             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 533       | 9.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 356       | 6.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 332       | 6.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 281       | 5.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 241       | 4.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 175       | 3.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 170       | 3.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 164       | 3.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 139       | 2.58%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 135       | 2.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 129       | 2.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 120       | 2.23%   |
| Intel Volume Management Device NVMe RAID Controller                            | 113       | 2.1%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 99        | 1.84%   |
| Intel SSD 660P Series                                                          | 78        | 1.45%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 69        | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 66        | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 66        | 1.22%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 65        | 1.21%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 65        | 1.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 65        | 1.21%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 62        | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 61        | 1.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 56        | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                          | 50        | 0.93%   |
| SK hynix BC511 NVMe SSD                                                        | 46        | 0.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 44        | 0.82%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 43        | 0.8%    |
| Intel Tiger Lake-LP SATA Controller                                            | 42        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 42        | 0.78%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 41        | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 41        | 0.76%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 40        | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 32        | 0.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 32        | 0.59%   |
| Phison E12 NVMe Controller                                                     | 31        | 0.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 30        | 0.56%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 29        | 0.54%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 28        | 0.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 26        | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2814      | 54.4%   |
| NVMe | 1886      | 36.46%  |
| RAID | 365       | 7.06%   |
| IDE  | 108       | 2.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3164      | 77.15%  |
| AMD    | 937       | 22.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 88        | 2.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 73        | 1.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 72        | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 71        | 1.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 71        | 1.73%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 69        | 1.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 68        | 1.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 67        | 1.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 63        | 1.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 61        | 1.49%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 59        | 1.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 58        | 1.41%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 56        | 1.36%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 52        | 1.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 47        | 1.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 47        | 1.14%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 47        | 1.14%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 46        | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 44        | 1.07%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 39        | 0.95%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 39        | 0.95%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 37        | 0.9%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 37        | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 36        | 0.88%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 36        | 0.88%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 35        | 0.85%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 35        | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 34        | 0.83%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 31        | 0.75%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 30        | 0.73%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 29        | 0.71%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 29        | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.71%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 29        | 0.71%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 28        | 0.68%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 26        | 0.63%   |
| Intel 12th Gen Core i7-12700H                 | 26        | 0.63%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 26        | 0.63%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 24        | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 1061      | 25.83%  |
| Intel Core i7                  | 1042      | 25.37%  |
| Other                          | 343       | 8.35%   |
| AMD Ryzen 7                    | 304       | 7.4%    |
| AMD Ryzen 5                    | 277       | 6.74%   |
| Intel Core i3                  | 258       | 6.28%   |
| Intel Celeron                  | 165       | 4.02%   |
| Intel Core 2 Duo               | 96        | 2.34%   |
| Intel Pentium                  | 85        | 2.07%   |
| AMD Ryzen 3                    | 56        | 1.36%   |
| AMD Ryzen 9                    | 43        | 1.05%   |
| AMD Ryzen 7 PRO                | 40        | 0.97%   |
| AMD A6                         | 28        | 0.68%   |
| AMD A10                        | 26        | 0.63%   |
| Intel Atom                     | 25        | 0.61%   |
| Intel Core i9                  | 24        | 0.58%   |
| AMD A8                         | 23        | 0.56%   |
| Intel Pentium Silver           | 21        | 0.51%   |
| AMD E1                         | 21        | 0.51%   |
| AMD A4                         | 21        | 0.51%   |
| Intel Pentium Dual-Core        | 20        | 0.49%   |
| AMD E                          | 17        | 0.41%   |
| Intel Core 2                   | 12        | 0.29%   |
| AMD E2                         | 10        | 0.24%   |
| AMD Ryzen 5 PRO                | 9         | 0.22%   |
| Intel Core m3                  | 7         | 0.17%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.17%   |
| AMD Athlon                     | 7         | 0.17%   |
| AMD A12                        | 6         | 0.15%   |
| Intel Genuine                  | 5         | 0.12%   |
| Intel Xeon                     | 4         | 0.1%    |
| Intel Core m7                  | 4         | 0.1%    |
| AMD FX                         | 4         | 0.1%    |
| Intel Pentium Dual             | 3         | 0.07%   |
| Intel Core m5                  | 3         | 0.07%   |
| Intel Celeron Dual-Core        | 3         | 0.07%   |
| AMD Athlon X2                  | 3         | 0.07%   |
| Intel Core M                   | 2         | 0.05%   |
| Intel Core 2 Quad              | 2         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1696      | 41.33%  |
| 4       | 1483      | 36.14%  |
| 6       | 407       | 9.92%   |
| 8       | 393       | 9.58%   |
| 14      | 46        | 1.12%   |
| 12      | 29        | 0.71%   |
| 10      | 19        | 0.46%   |
| 1       | 18        | 0.44%   |
| 16      | 7         | 0.17%   |
| 3       | 3         | 0.07%   |
| 24      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4101      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 3395      | 82.68%  |
| 1       | 710       | 17.29%  |
| Unknown | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4038      | 98.42%  |
| Unknown        | 65        | 1.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2148      | 50.74%  |
| 0x306a9    | 148       | 3.5%    |
| 0x806ea    | 121       | 2.86%   |
| 0x906ea    | 119       | 2.81%   |
| 0x806ec    | 110       | 2.6%    |
| 0x806c1    | 101       | 2.39%   |
| 0x806e9    | 81        | 1.91%   |
| 0x206a7    | 80        | 1.89%   |
| 0x406e3    | 75        | 1.77%   |
| 0x40651    | 75        | 1.77%   |
| 0x08108102 | 67        | 1.58%   |
| 0x0a50000c | 64        | 1.51%   |
| 0x306c3    | 62        | 1.46%   |
| 0x08600106 | 61        | 1.44%   |
| 0x306d4    | 59        | 1.39%   |
| 0x906e9    | 53        | 1.25%   |
| 0xa0652    | 48        | 1.13%   |
| 0x08600103 | 48        | 1.13%   |
| 0x08108109 | 48        | 1.13%   |
| 0x806eb    | 42        | 0.99%   |
| 0x706e5    | 41        | 0.97%   |
| 0x08600104 | 40        | 0.94%   |
| 0x08608103 | 38        | 0.9%    |
| 0x1067a    | 32        | 0.76%   |
| 0x506e3    | 31        | 0.73%   |
| 0x20655    | 31        | 0.73%   |
| 0x906a3    | 28        | 0.66%   |
| 0x806d1    | 21        | 0.5%    |
| 0x30678    | 17        | 0.4%    |
| 0x506c9    | 16        | 0.38%   |
| 0x0a404102 | 16        | 0.38%   |
| 0x0810100b | 16        | 0.38%   |
| 0x406c4    | 15        | 0.35%   |
| 0x06006705 | 15        | 0.35%   |
| 0x706a1    | 14        | 0.33%   |
| 0x0a50000d | 12        | 0.28%   |
| 0x0600611a | 12        | 0.28%   |
| 0x906ed    | 11        | 0.26%   |
| 0x0a50000b | 11        | 0.26%   |
| 0x08600102 | 11        | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 971       | 23.65%  |
| Haswell          | 321       | 7.82%   |
| IvyBridge        | 295       | 7.19%   |
| Zen 2            | 238       | 5.8%    |
| Skylake          | 228       | 5.55%   |
| SandyBridge      | 219       | 5.33%   |
| Unknown          | 203       | 4.95%   |
| TigerLake        | 185       | 4.51%   |
| Zen+             | 181       | 4.41%   |
| Broadwell        | 157       | 3.82%   |
| Zen 3            | 154       | 3.75%   |
| CometLake        | 105       | 2.56%   |
| Penryn           | 102       | 2.48%   |
| Westmere         | 101       | 2.46%   |
| IceLake          | 99        | 2.41%   |
| Silvermont       | 88        | 2.14%   |
| Goldmont plus    | 68        | 1.66%   |
| Excavator        | 62        | 1.51%   |
| Alderlake Hybrid | 57        | 1.39%   |
| Core             | 40        | 0.97%   |
| Zen              | 39        | 0.95%   |
| Goldmont         | 36        | 0.88%   |
| Puma             | 28        | 0.68%   |
| Bobcat           | 27        | 0.66%   |
| Piledriver       | 24        | 0.58%   |
| Jaguar           | 20        | 0.49%   |
| Nehalem          | 11        | 0.27%   |
| K10 Llano        | 10        | 0.24%   |
| K8 Hammer        | 9         | 0.22%   |
| K10              | 7         | 0.17%   |
| Steamroller      | 5         | 0.12%   |
| K8 & K10 hybrid  | 5         | 0.12%   |
| Bonnell          | 5         | 0.12%   |
| Tremont          | 4         | 0.1%    |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2946      | 53.81%  |
| Nvidia | 1425      | 26.03%  |
| AMD    | 1104      | 20.16%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 281       | 5.03%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 227       | 4.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 206       | 3.69%   |
| Intel UHD Graphics 620                                                                   | 197       | 3.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 192       | 3.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 183       | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 177       | 3.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 163       | 2.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 161       | 2.88%   |
| Intel HD Graphics 620                                                                    | 140       | 2.51%   |
| Intel HD Graphics 5500                                                                   | 133       | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 125       | 2.24%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 123       | 2.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 116       | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 112       | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 103       | 1.84%   |
| Intel HD Graphics 630                                                                    | 94        | 1.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 79        | 1.41%   |
| AMD Lucienne                                                                             | 78        | 1.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 73        | 1.31%   |
| Intel HD Graphics 530                                                                    | 69        | 1.24%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 68        | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 61        | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 58        | 1.04%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 54        | 0.97%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 53        | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 52        | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 50        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 49        | 0.88%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 47        | 0.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 44        | 0.79%   |
| Nvidia GP108M [GeForce MX150]                                                            | 43        | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 43        | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 39        | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 38        | 0.68%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 37        | 0.66%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 37        | 0.66%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 37        | 0.66%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 36        | 0.64%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 36        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1758      | 42.74%  |
| Intel + Nvidia     | 1048      | 25.48%  |
| 1 x AMD            | 715       | 17.38%  |
| 1 x Nvidia         | 190       | 4.62%   |
| AMD + Nvidia       | 183       | 4.45%   |
| Intel + AMD        | 130       | 3.16%   |
| 2 x AMD            | 78        | 1.9%    |
| 2 x Intel          | 4         | 0.1%    |
| Other              | 3         | 0.07%   |
| 2 x Nvidia         | 3         | 0.07%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3304      | 79.65%  |
| Proprietary | 841       | 20.27%  |
| Unknown     | 3         | 0.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3180      | 76.41%  |
| 0.01-0.5   | 338       | 8.12%   |
| 1.01-2.0   | 259       | 6.22%   |
| 3.01-4.0   | 132       | 3.17%   |
| 0.51-1.0   | 128       | 3.08%   |
| 5.01-6.0   | 62        | 1.49%   |
| 7.01-8.0   | 39        | 0.94%   |
| 8.01-16.0  | 12        | 0.29%   |
| 2.01-3.0   | 11        | 0.26%   |
| 16.01-24.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 829       | 17.04%  |
| BOE                     | 733       | 15.07%  |
| Chimei Innolux          | 721       | 14.82%  |
| LG Display              | 706       | 14.51%  |
| Samsung Electronics     | 396       | 8.14%   |
| Sharp                   | 151       | 3.1%    |
| Dell                    | 136       | 2.8%    |
| Goldstar                | 121       | 2.49%   |
| Apple                   | 105       | 2.16%   |
| PANDA                   | 103       | 2.12%   |
| Chi Mei Optoelectronics | 85        | 1.75%   |
| Lenovo                  | 76        | 1.56%   |
| Hewlett-Packard         | 62        | 1.27%   |
| Philips                 | 47        | 0.97%   |
| BenQ                    | 43        | 0.88%   |
| Acer                    | 41        | 0.84%   |
| AOC                     | 39        | 0.8%    |
| Ancor Communications    | 39        | 0.8%    |
| InfoVision              | 36        | 0.74%   |
| CSO                     | 35        | 0.72%   |
| ViewSonic               | 26        | 0.53%   |
| TMX                     | 21        | 0.43%   |
| Iiyama                  | 19        | 0.39%   |
| ASUSTek Computer        | 19        | 0.39%   |
| LGD                     | 18        | 0.37%   |
| LG Philips              | 18        | 0.37%   |
| Sony                    | 15        | 0.31%   |
| Panasonic               | 12        | 0.25%   |
| CPT                     | 12        | 0.25%   |
| Unknown                 | 10        | 0.21%   |
| Toshiba                 | 9         | 0.18%   |
| NEC Computers           | 9         | 0.18%   |
| Unknown                 | 7         | 0.14%   |
| MSI                     | 7         | 0.14%   |
| Insignia                | 7         | 0.14%   |
| LG Electronics          | 6         | 0.12%   |
| HannStar                | 6         | 0.12%   |
| JDI                     | 5         | 0.1%    |
| HKC                     | 5         | 0.1%    |
| Gigabyte Technology     | 5         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 46        | 0.93%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 45        | 0.91%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 44        | 0.89%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 36        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 28        | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 23        | 0.47%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 22        | 0.45%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 22        | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 19        | 0.39%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 19        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 19        | 0.39%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 18        | 0.37%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 18        | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.32%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 15        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 15        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 15        | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 15        | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 15        | 0.3%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 15        | 0.3%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 14        | 0.28%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.26%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 13        | 0.26%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 12        | 0.24%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 12        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 12        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 12        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.24%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 12        | 0.24%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 12        | 0.24%   |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch                    | 12        | 0.24%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch           | 12        | 0.24%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 12        | 0.24%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.24%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 11        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 11        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2251      | 49.63%  |
| 1366x768 (WXGA)    | 1072      | 23.63%  |
| 3840x2160 (4K)     | 192       | 4.23%   |
| 1600x900 (HD+)     | 160       | 3.53%   |
| 2560x1440 (QHD)    | 142       | 3.13%   |
| 1280x800 (WXGA)    | 98        | 2.16%   |
| 1920x1200 (WUXGA)  | 91        | 2.01%   |
| 2560x1600          | 71        | 1.57%   |
| 1440x900 (WXGA+)   | 66        | 1.46%   |
| 2880x1800          | 51        | 1.12%   |
| 1680x1050 (WSXGA+) | 39        | 0.86%   |
| 2560x1080          | 30        | 0.66%   |
| 2160x1440          | 25        | 0.55%   |
| 3840x2400          | 24        | 0.53%   |
| Unknown            | 24        | 0.53%   |
| 3440x1440          | 19        | 0.42%   |
| 1280x1024 (SXGA)   | 18        | 0.4%    |
| 3200x1800 (QHD+)   | 15        | 0.33%   |
| 1360x768           | 15        | 0.33%   |
| 2256x1504          | 14        | 0.31%   |
| 3840x1080          | 12        | 0.26%   |
| 3456x2160          | 12        | 0.26%   |
| 3200x2000          | 10        | 0.22%   |
| 2880x1620          | 7         | 0.15%   |
| 2520x1680          | 7         | 0.15%   |
| 3840x1600          | 6         | 0.13%   |
| 3000x2000          | 6         | 0.13%   |
| 1920x540           | 6         | 0.13%   |
| 1920x1280          | 6         | 0.13%   |
| 3286x1080          | 4         | 0.09%   |
| 2240x1400          | 4         | 0.09%   |
| 3840x1200          | 3         | 0.07%   |
| 2880x1920          | 3         | 0.07%   |
| 1600x1200          | 3         | 0.07%   |
| 1024x600           | 3         | 0.07%   |
| 800x1280           | 2         | 0.04%   |
| 3840x1100          | 2         | 0.04%   |
| 3072x1920          | 2         | 0.04%   |
| 2560x1700          | 2         | 0.04%   |
| 800x480            | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2028      | 41.91%  |
| 13      | 690       | 14.26%  |
| 14      | 619       | 12.79%  |
| 17      | 311       | 6.43%   |
| 27      | 172       | 3.55%   |
| 24      | 162       | 3.35%   |
| 23      | 136       | 2.81%   |
| 12      | 103       | 2.13%   |
| 21      | 97        | 2%      |
| Unknown | 86        | 1.78%   |
| 16      | 76        | 1.57%   |
| 31      | 54        | 1.12%   |
| 11      | 53        | 1.1%    |
| 34      | 42        | 0.87%   |
| 18      | 27        | 0.56%   |
| 19      | 25        | 0.52%   |
| 22      | 23        | 0.48%   |
| 40      | 15        | 0.31%   |
| 84      | 13        | 0.27%   |
| 20      | 13        | 0.27%   |
| 32      | 10        | 0.21%   |
| 26      | 9         | 0.19%   |
| 72      | 8         | 0.17%   |
| 54      | 8         | 0.17%   |
| 37      | 7         | 0.14%   |
| 25      | 5         | 0.1%    |
| 86      | 4         | 0.08%   |
| 52      | 4         | 0.08%   |
| 28      | 4         | 0.08%   |
| 10      | 4         | 0.08%   |
| 74      | 3         | 0.06%   |
| 48      | 3         | 0.06%   |
| 33      | 3         | 0.06%   |
| 8       | 3         | 0.06%   |
| 65      | 2         | 0.04%   |
| 49      | 2         | 0.04%   |
| 42      | 2         | 0.04%   |
| 35      | 2         | 0.04%   |
| 29      | 2         | 0.04%   |
| 7       | 2         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 3034      | 63.22%  |
| 201-300     | 472       | 9.84%   |
| 501-600     | 438       | 9.13%   |
| 351-400     | 376       | 7.83%   |
| 401-500     | 173       | 3.6%    |
| Unknown     | 86        | 1.79%   |
| 601-700     | 80        | 1.67%   |
| 701-800     | 56        | 1.17%   |
| 1501-2000   | 27        | 0.56%   |
| 801-900     | 25        | 0.52%   |
| 1001-1500   | 24        | 0.5%    |
| 101-200     | 3         | 0.06%   |
| 901-1000    | 3         | 0.06%   |
| 1-100       | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3534      | 83.37%  |
| 16/10   | 464       | 10.95%  |
| 3/2     | 73        | 1.72%   |
| Unknown | 70        | 1.65%   |
| 21/9    | 52        | 1.23%   |
| 5/4     | 17        | 0.4%    |
| 4/3     | 9         | 0.21%   |
| 32/9    | 7         | 0.17%   |
| 0.56    | 4         | 0.09%   |
| 3.40    | 2         | 0.05%   |
| 0.67    | 2         | 0.05%   |
| 0.62    | 2         | 0.05%   |
| 6/5     | 1         | 0.02%   |
| 1.00    | 1         | 0.02%   |
| 0.63    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2023      | 41.93%  |
| 81-90          | 1079      | 22.36%  |
| 201-250        | 346       | 7.17%   |
| 121-130        | 270       | 5.6%    |
| 71-80          | 226       | 4.68%   |
| 301-350        | 178       | 3.69%   |
| 351-500        | 114       | 2.36%   |
| 61-70          | 97        | 2.01%   |
| Unknown        | 86        | 1.78%   |
| 111-120        | 66        | 1.37%   |
| 151-200        | 60        | 1.24%   |
| 51-60          | 55        | 1.14%   |
| More than 1000 | 48        | 0.99%   |
| 251-300        | 47        | 0.97%   |
| 131-140        | 38        | 0.79%   |
| 141-150        | 32        | 0.66%   |
| 501-1000       | 30        | 0.62%   |
| 91-100         | 21        | 0.44%   |
| 1-40           | 5         | 0.1%    |
| 41-50          | 4         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2139      | 45.09%  |
| 101-120       | 1198      | 25.25%  |
| 51-100        | 688       | 14.5%   |
| 161-240       | 403       | 8.49%   |
| More than 240 | 185       | 3.9%    |
| Unknown       | 86        | 1.81%   |
| 1-50          | 45        | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3325      | 79.43%  |
| 2     | 755       | 18.04%  |
| 3     | 79        | 1.89%   |
| 0     | 18        | 0.43%   |
| 4     | 9         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 2286      | 35.59%  |
| Realtek Semiconductor                  | 2267      | 35.29%  |
| Qualcomm Atheros                       | 822       | 12.8%   |
| Broadcom                               | 297       | 4.62%   |
| MediaTek                               | 130       | 2.02%   |
| Broadcom Limited                       | 80        | 1.25%   |
| Ralink                                 | 50        | 0.78%   |
| TP-Link                                | 41        | 0.64%   |
| ASIX Electronics                       | 41        | 0.64%   |
| Ralink Technology                      | 37        | 0.58%   |
| Sierra Wireless                        | 32        | 0.5%    |
| Xiaomi                                 | 29        | 0.45%   |
| Marvell Technology Group               | 28        | 0.44%   |
| Lenovo                                 | 28        | 0.44%   |
| DisplayLink                            | 26        | 0.4%    |
| Dell                                   | 23        | 0.36%   |
| Qualcomm                               | 19        | 0.3%    |
| Hewlett-Packard                        | 16        | 0.25%   |
| Samsung Electronics                    | 15        | 0.23%   |
| JMicron Technology                     | 15        | 0.23%   |
| Huawei Technologies                    | 15        | 0.23%   |
| Ericsson Business Mobile Networks      | 14        | 0.22%   |
| ASUSTek Computer                       | 10        | 0.16%   |
| Nvidia                                 | 9         | 0.14%   |
| Fibocom                                | 9         | 0.14%   |
| Qualcomm Atheros Communications        | 7         | 0.11%   |
| NetGear                                | 7         | 0.11%   |
| Linksys                                | 7         | 0.11%   |
| D-Link                                 | 7         | 0.11%   |
| Google                                 | 6         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.08%   |
| Edimax Technology                      | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.06%   |
| Apple                                  | 4         | 0.06%   |
| Quectel Wireless Solutions             | 3         | 0.05%   |
| ZyXEL Communications                   | 2         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| OPPO Electronics                       | 2         | 0.03%   |
| Motorola PCS                           | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1440      | 18.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 337       | 4.4%    |
| Intel Wi-Fi 6 AX200                                                    | 321       | 4.19%   |
| Intel Wireless 8265 / 8275                                             | 201       | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 192       | 2.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 174       | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 167       | 2.18%   |
| Intel Wireless 7260                                                    | 150       | 1.96%   |
| Intel Wireless 7265                                                    | 142       | 1.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 137       | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 133       | 1.74%   |
| Intel Wi-Fi 6 AX201                                                    | 132       | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 127       | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 123       | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 112       | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 98        | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 96        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 96        | 1.25%   |
| Intel Wireless 8260                                                    | 93        | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 90        | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 86        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 78        | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 75        | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 68        | 0.89%   |
| Intel Wireless 3165                                                    | 68        | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 62        | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 60        | 0.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 56        | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                                  | 55        | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 45        | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                                  | 45        | 0.59%   |
| Intel Wireless 3160                                                    | 44        | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 44        | 0.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 43        | 0.56%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 43        | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 43        | 0.56%   |
| Intel Ethernet Connection I217-LM                                      | 41        | 0.54%   |
| Intel Ethernet Connection I218-LM                                      | 40        | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                   | 40        | 0.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 40        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2227      | 52.01%  |
| Qualcomm Atheros                      | 691       | 16.14%  |
| Realtek Semiconductor                 | 689       | 16.09%  |
| Broadcom                              | 229       | 5.35%   |
| MediaTek                              | 122       | 2.85%   |
| Broadcom Limited                      | 62        | 1.45%   |
| Ralink                                | 50        | 1.17%   |
| Ralink Technology                     | 37        | 0.86%   |
| TP-Link                               | 36        | 0.84%   |
| Sierra Wireless                       | 32        | 0.75%   |
| Dell                                  | 17        | 0.4%    |
| Qualcomm                              | 13        | 0.3%    |
| Fibocom                               | 9         | 0.21%   |
| ASUSTek Computer                      | 8         | 0.19%   |
| Qualcomm Atheros Communications       | 7         | 0.16%   |
| NetGear                               | 7         | 0.16%   |
| Linksys                               | 7         | 0.16%   |
| Ericsson Business Mobile Networks     | 7         | 0.16%   |
| D-Link                                | 7         | 0.16%   |
| Hewlett-Packard                       | 5         | 0.12%   |
| Edimax Technology                     | 5         | 0.12%   |
| Quectel Wireless Solutions            | 3         | 0.07%   |
| ZyXEL Communications                  | 2         | 0.05%   |
| Microsoft                             | 2         | 0.05%   |
| ZyDAS                                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Qualcomm Technologies                 | 1         | 0.02%   |
| Mercucys                              | 1         | 0.02%   |
| D-Link System                         | 1         | 0.02%   |
| Belkin Components                     | 1         | 0.02%   |
| Apple                                 | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 321       | 7.44%   |
| Intel Wireless 8265 / 8275                                     | 201       | 4.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 192       | 4.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 167       | 3.87%   |
| Intel Wireless 7260                                            | 150       | 3.48%   |
| Intel Wireless 7265                                            | 142       | 3.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 137       | 3.17%   |
| Intel Wi-Fi 6 AX201                                            | 132       | 3.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 127       | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 123       | 2.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 112       | 2.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 98        | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 96        | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 96        | 2.22%   |
| Intel Wireless 8260                                            | 93        | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 90        | 2.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 86        | 1.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 78        | 1.81%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 75        | 1.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 68        | 1.58%   |
| Intel Wireless 3165                                            | 68        | 1.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 62        | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 60        | 1.39%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 56        | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 45        | 1.04%   |
| Intel Wireless 3160                                            | 44        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 44        | 1.02%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 43        | 1%      |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 43        | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 43        | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 40        | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                  | 38        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 37        | 0.86%   |
| Intel Centrino Wireless-N 2230                                 | 36        | 0.83%   |
| Intel Centrino Advanced-N 6235                                 | 33        | 0.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 32        | 0.74%   |
| Intel Centrino Ultimate-N 6300                                 | 31        | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 28        | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 27        | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 26        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1997      | 61.37%  |
| Intel                                  | 671       | 20.62%  |
| Qualcomm Atheros                       | 202       | 6.21%   |
| Broadcom                               | 112       | 3.44%   |
| ASIX Electronics                       | 41        | 1.26%   |
| Xiaomi                                 | 28        | 0.86%   |
| Marvell Technology Group               | 28        | 0.86%   |
| Lenovo                                 | 28        | 0.86%   |
| DisplayLink                            | 26        | 0.8%    |
| Broadcom Limited                       | 21        | 0.65%   |
| JMicron Technology                     | 15        | 0.46%   |
| Samsung Electronics                    | 14        | 0.43%   |
| Nvidia                                 | 9         | 0.28%   |
| MediaTek                               | 7         | 0.22%   |
| Huawei Technologies                    | 7         | 0.22%   |
| Qualcomm                               | 6         | 0.18%   |
| TP-Link                                | 5         | 0.15%   |
| Google                                 | 5         | 0.15%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.12%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.12%   |
| Hewlett-Packard                        | 3         | 0.09%   |
| Apple                                  | 3         | 0.09%   |
| Spreadtrum Communications              | 2         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.06%   |
| OPPO Electronics                       | 2         | 0.06%   |
| Motorola PCS                           | 2         | 0.06%   |
| ICS Advent                             | 2         | 0.06%   |
| Attansic Technology                    | 2         | 0.06%   |
| ASUSTek Computer                       | 2         | 0.06%   |
| T & A Mobile Phones                    | 1         | 0.03%   |
| Microchip Technology                   | 1         | 0.03%   |
| HTC (High Tech Computer)               | 1         | 0.03%   |
| Foxconn / Hon Hai                      | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1440      | 43.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 337       | 10.21%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 174       | 5.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 133       | 4.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 55        | 1.67%   |
| Intel Ethernet Connection (3) I218-LM                                  | 45        | 1.36%   |
| Intel Ethernet Connection I217-LM                                      | 41        | 1.24%   |
| Intel Ethernet Connection I218-LM                                      | 40        | 1.21%   |
| Intel Ethernet Connection (4) I219-V                                   | 40        | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                          | 36        | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 34        | 1.03%   |
| Intel Ethernet Connection I219-LM                                      | 31        | 0.94%   |
| Intel 82577LM Gigabit Network Connection                               | 30        | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 28        | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                      | 27        | 0.82%   |
| Realtek Killer E2600 GbE Controller                                    | 26        | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                   | 26        | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 23        | 0.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 23        | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 22        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                  | 22        | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 21        | 0.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 21        | 0.64%   |
| Intel Ethernet Connection (6) I219-LM                                  | 20        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 19        | 0.58%   |
| Intel Ethernet Connection I219-V                                       | 19        | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 16        | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 16        | 0.48%   |
| Intel 82567LM Gigabit Network Connection                               | 16        | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 15        | 0.45%   |
| Intel Ethernet Connection (10) I219-V                                  | 15        | 0.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 15        | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 14        | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 14        | 0.42%   |
| Intel Ethernet Connection I217-V                                       | 13        | 0.39%   |
| Intel 82579V Gigabit Network Connection                                | 13        | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                                  | 12        | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 11        | 0.33%   |
| Intel Ethernet Connection (13) I219-V                                  | 11        | 0.33%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 11        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4058      | 56.31%  |
| Ethernet | 3112      | 43.18%  |
| Modem    | 35        | 0.49%   |
| Unknown  | 2         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3520      | 81.26%  |
| Ethernet | 812       | 18.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2810      | 68.45%  |
| 1     | 1212      | 29.52%  |
| 0     | 44        | 1.07%   |
| 3     | 39        | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3416      | 81.82%  |
| Yes  | 759       | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1831      | 53.37%  |
| Realtek Semiconductor           | 403       | 11.75%  |
| Qualcomm Atheros Communications | 322       | 9.39%   |
| IMC Networks                    | 186       | 5.42%   |
| Lite-On Technology              | 152       | 4.43%   |
| Broadcom                        | 111       | 3.24%   |
| Foxconn / Hon Hai               | 100       | 2.91%   |
| Apple                           | 86        | 2.51%   |
| Realtek                         | 44        | 1.28%   |
| Cambridge Silicon Radio         | 40        | 1.17%   |
| Ralink                          | 26        | 0.76%   |
| Hewlett-Packard                 | 24        | 0.7%    |
| Dell                            | 24        | 0.7%    |
| Toshiba                         | 14        | 0.41%   |
| MediaTek                        | 11        | 0.32%   |
| Opticis                         | 9         | 0.26%   |
| Foxconn International           | 9         | 0.26%   |
| ASUSTek Computer                | 9         | 0.26%   |
| Ralink Technology               | 6         | 0.17%   |
| Alps Electric                   | 6         | 0.17%   |
| Askey Computer                  | 4         | 0.12%   |
| USI                             | 3         | 0.09%   |
| TP-Link                         | 3         | 0.09%   |
| Fujitsu                         | 2         | 0.06%   |
| Belkin Components               | 2         | 0.06%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 649       | 18.89%  |
| Intel AX201 Bluetooth                               | 312       | 9.08%   |
| Intel AX200 Bluetooth                               | 311       | 9.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 296       | 8.61%   |
| Realtek Bluetooth Radio                             | 272       | 7.92%   |
| Qualcomm Atheros  Bluetooth Device                  | 160       | 4.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 98        | 2.85%   |
| Intel Bluetooth Device                              | 75        | 2.18%   |
| IMC Networks Bluetooth Radio                        | 68        | 1.98%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 61        | 1.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 54        | 1.57%   |
| Intel AX210 Bluetooth                               | 53        | 1.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 47        | 1.37%   |
| IMC Networks Wireless_Device                        | 47        | 1.37%   |
| Apple Bluetooth Host Controller                     | 45        | 1.31%   |
| Realtek Bluetooth Radio                             | 44        | 1.28%   |
| Intel Wireless-AC 3168 Bluetooth                    | 41        | 1.19%   |
| Lite-On Bluetooth Device                            | 40        | 1.16%   |
| IMC Networks Bluetooth Device                       | 40        | 1.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 40        | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 39        | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 38        | 1.11%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 35        | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                  | 35        | 1.02%   |
| Apple Bluetooth USB Host Controller                 | 35        | 1.02%   |
| Foxconn / Hon Hai Wireless_Device                   | 33        | 0.96%   |
| Ralink RT3290 Bluetooth                             | 26        | 0.76%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 22        | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 22        | 0.64%   |
| Lite-On Wireless_Device                             | 20        | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 16        | 0.47%   |
| Realtek RTL8723B Bluetooth                          | 15        | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                    | 15        | 0.44%   |
| Broadcom HP Portable SoftSailing                    | 14        | 0.41%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.41%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 12        | 0.35%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 9         | 0.26%   |
| Opticis Bluetooth Radio                             | 9         | 0.26%   |
| MediaTek Wireless_Device                            | 9         | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3119      | 61.35%  |
| AMD                                  | 1003      | 19.73%  |
| Nvidia                               | 618       | 12.16%  |
| C-Media Electronics                  | 45        | 0.89%   |
| Realtek Semiconductor                | 29        | 0.57%   |
| Lenovo                               | 27        | 0.53%   |
| Logitech                             | 24        | 0.47%   |
| GN Netcom                            | 18        | 0.35%   |
| JMTek                                | 17        | 0.33%   |
| Kingston Technology                  | 13        | 0.26%   |
| Generalplus Technology               | 12        | 0.24%   |
| Texas Instruments                    | 10        | 0.2%    |
| SteelSeries ApS                      | 10        | 0.2%    |
| Plantronics                          | 10        | 0.2%    |
| Apple                                | 8         | 0.16%   |
| Focusrite-Novation                   | 7         | 0.14%   |
| Razer USA                            | 6         | 0.12%   |
| Hewlett-Packard                      | 6         | 0.12%   |
| Samson Technologies                  | 5         | 0.1%    |
| GYROCOM C&C                          | 5         | 0.1%    |
| Creative Technology                  | 5         | 0.1%    |
| Sony                                 | 4         | 0.08%   |
| KTMicro                              | 4         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.06%   |
| Sennheiser Communications            | 3         | 0.06%   |
| RODE Microphones                     | 3         | 0.06%   |
| Huawei Technologies                  | 3         | 0.06%   |
| DSEA A/S                             | 3         | 0.06%   |
| Corsair                              | 3         | 0.06%   |
| Audio-Technica                       | 3         | 0.06%   |
| ASUSTek Computer                     | 3         | 0.06%   |
| Yamaha                               | 2         | 0.04%   |
| Samsung Electronics                  | 2         | 0.04%   |
| Other World Computing                | 2         | 0.04%   |
| No brand                             | 2         | 0.04%   |
| M-Audio                              | 2         | 0.04%   |
| Cambridge Silicon Radio              | 2         | 0.04%   |
| Blue Microphones                     | 2         | 0.04%   |
| AudioQuest                           | 2         | 0.04%   |
| Astro Gaming                         | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 715       | 11.3%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 506       | 8%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 365       | 5.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 329       | 5.2%    |
| Intel Cannon Lake PCH cAVS                                                                        | 223       | 3.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 198       | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 185       | 2.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 185       | 2.92%   |
| Intel 8 Series HD Audio Controller                                                                | 181       | 2.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 180       | 2.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 166       | 2.62%   |
| Intel Broadwell-U Audio Controller                                                                | 157       | 2.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 155       | 2.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 139       | 2.2%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 118       | 1.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 112       | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 106       | 1.68%   |
| Intel CM238 HD Audio Controller                                                                   | 106       | 1.68%   |
| AMD FCH Azalia Controller                                                                         | 97        | 1.53%   |
| Intel Comet Lake PCH cAVS                                                                         | 92        | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 81        | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 79        | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 77        | 1.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 77        | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                                          | 75        | 1.19%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 74        | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 68        | 1.07%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 62        | 0.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 61        | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 55        | 0.87%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 50        | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 44        | 0.7%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 44        | 0.7%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 41        | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 39        | 0.62%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 36        | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 36        | 0.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 36        | 0.57%   |
| Nvidia Audio device                                                                               | 35        | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 35        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 950       | 31.64%  |
| SK hynix            | 636       | 21.18%  |
| Micron Technology   | 420       | 13.99%  |
| Kingston            | 274       | 9.12%   |
| Crucial             | 148       | 4.93%   |
| Unknown             | 107       | 3.56%   |
| A-DATA Technology   | 68        | 2.26%   |
| Ramaxel Technology  | 67        | 2.23%   |
| Elpida              | 46        | 1.53%   |
| Corsair             | 42        | 1.4%    |
| Nanya Technology    | 32        | 1.07%   |
| G.Skill             | 27        | 0.9%    |
| GOODRAM             | 19        | 0.63%   |
| Smart               | 18        | 0.6%    |
| Unknown (ABCD)      | 17        | 0.57%   |
| Transcend           | 16        | 0.53%   |
| Unknown             | 14        | 0.47%   |
| Patriot             | 12        | 0.4%    |
| Team                | 11        | 0.37%   |
| AMD                 | 8         | 0.27%   |
| Apacer              | 7         | 0.23%   |
| ASint Technology    | 6         | 0.2%    |
| Teikon              | 5         | 0.17%   |
| Smart Brazil        | 4         | 0.13%   |
| Goldkey             | 4         | 0.13%   |
| Silicon Power       | 3         | 0.1%    |
| SHARETRONIC         | 3         | 0.1%    |
| Avant               | 3         | 0.1%    |
| Atermiter           | 3         | 0.1%    |
| Timetec             | 2         | 0.07%   |
| Qumo                | 2         | 0.07%   |
| Qimonda             | 2         | 0.07%   |
| Kllisre             | 2         | 0.07%   |
| ff                  | 2         | 0.07%   |
| 4ea5                | 2         | 0.07%   |
| V-Color             | 1         | 0.03%   |
| Unknown (768A)      | 1         | 0.03%   |
| Unknown (0x8AF1)    | 1         | 0.03%   |
| Unknown (0x0B6B)    | 1         | 0.03%   |
| Unknown (0x02BA)    | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 60        | 1.89%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 55        | 1.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 50        | 1.58%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 46        | 1.45%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 37        | 1.17%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 35        | 1.1%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 33        | 1.04%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 31        | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 30        | 0.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 29        | 0.91%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 28        | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 26        | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 26        | 0.82%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 26        | 0.82%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 25        | 0.79%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 25        | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 23        | 0.73%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 21        | 0.66%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 21        | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 20        | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 20        | 0.63%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 19        | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 19        | 0.6%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 19        | 0.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 18        | 0.57%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 18        | 0.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 18        | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 18        | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 16        | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 15        | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 15        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 15        | 0.47%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 15        | 0.47%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 14        | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 14        | 0.44%   |
| Unknown                                                             | 14        | 0.44%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 13        | 0.41%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 13        | 0.41%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 13        | 0.41%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 13        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1388      | 55.41%  |
| DDR3    | 726       | 28.98%  |
| LPDDR4  | 134       | 5.35%   |
| LPDDR3  | 104       | 4.15%   |
| DDR5    | 44        | 1.76%   |
| SDRAM   | 37        | 1.48%   |
| DDR2    | 35        | 1.4%    |
| LPDDR5  | 28        | 1.12%   |
| Unknown | 5         | 0.2%    |
| DRAM    | 2         | 0.08%   |
| DDR     | 2         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2158      | 85.87%  |
| Row Of Chips | 314       | 12.5%   |
| Chip         | 20        | 0.8%    |
| Unknown      | 13        | 0.52%   |
| DIMM         | 8         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1220      | 44.41%  |
| 4096  | 793       | 28.87%  |
| 16384 | 412       | 15%     |
| 2048  | 203       | 7.39%   |
| 32768 | 85        | 3.09%   |
| 1024  | 32        | 1.16%   |
| 3072  | 1         | 0.04%   |
| 512   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 655       | 23.99%  |
| 3200    | 574       | 21.03%  |
| 1600    | 562       | 20.59%  |
| 2400    | 212       | 7.77%   |
| 2133    | 161       | 5.9%    |
| 1334    | 101       | 3.7%    |
| 1333    | 59        | 2.16%   |
| 4267    | 55        | 2.01%   |
| 3266    | 55        | 2.01%   |
| 4800    | 38        | 1.39%   |
| 1867    | 34        | 1.25%   |
| 1067    | 27        | 0.99%   |
| 6400    | 26        | 0.95%   |
| 4199    | 26        | 0.95%   |
| Unknown | 22        | 0.81%   |
| 667     | 21        | 0.77%   |
| 4266    | 20        | 0.73%   |
| 800     | 11        | 0.4%    |
| 975     | 10        | 0.37%   |
| 3733    | 9         | 0.33%   |
| 2048    | 9         | 0.33%   |
| 1066    | 7         | 0.26%   |
| 8400    | 6         | 0.22%   |
| 5600    | 6         | 0.22%   |
| 2933    | 4         | 0.15%   |
| 1866    | 3         | 0.11%   |
| 3000    | 2         | 0.07%   |
| 1200    | 2         | 0.07%   |
| 333     | 2         | 0.07%   |
| 65535   | 1         | 0.04%   |
| 7467    | 1         | 0.04%   |
| 5200    | 1         | 0.04%   |
| 3800    | 1         | 0.04%   |
| 3600    | 1         | 0.04%   |
| 2800    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |
| 666     | 1         | 0.04%   |
| 533     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 25%     |
| Seiko Epson         | 7         | 21.88%  |
| Brother Industries  | 5         | 15.63%  |
| Canon               | 4         | 12.5%   |
| Samsung Electronics | 2         | 6.25%   |
| Xiaomi              | 1         | 3.13%   |
| STMicroelectronics  | 1         | 3.13%   |
| Sagem               | 1         | 3.13%   |
| Pantum              | 1         | 3.13%   |
| Kyocera             | 1         | 3.13%   |
| Dymo-CoStar         | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP ENVY 4520 series                                       | 2         | 6.25%   |
| Brother HL-L2300D series                                  | 2         | 6.25%   |
| Xiaomi MiMouse 2                                          | 1         | 3.13%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.13%   |
| Seiko Epson Printer                                       | 1         | 3.13%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 3.13%   |
| Seiko Epson L365 Series                                   | 1         | 3.13%   |
| Seiko Epson L355 Series                                   | 1         | 3.13%   |
| Seiko Epson L3250 Series                                  | 1         | 3.13%   |
| Seiko Epson L3150 Series                                  | 1         | 3.13%   |
| Seiko Epson ET-2850 Series                                | 1         | 3.13%   |
| Samsung ML-1865                                           | 1         | 3.13%   |
| Samsung CLX-3180 Series                                   | 1         | 3.13%   |
| Sagem Laser Pro LL                                        | 1         | 3.13%   |
| Pantum P2200W-series                                      | 1         | 3.13%   |
| Kyocera FS-1030D printer                                  | 1         | 3.13%   |
| HP Officejet 4500 G510g-m                                 | 1         | 3.13%   |
| HP LaserJet P1102                                         | 1         | 3.13%   |
| HP Ink Tank Wireless 410 series                           | 1         | 3.13%   |
| HP Ink Tank 310 series                                    | 1         | 3.13%   |
| HP DeskJet 2700 series                                    | 1         | 3.13%   |
| HP DeskJet 1110 series                                    | 1         | 3.13%   |
| Dymo-CoStar DYMO LabelWriter 450 Twin Turbo               | 1         | 3.13%   |
| Canon TS300 series                                        | 1         | 3.13%   |
| Canon TR4500 series                                       | 1         | 3.13%   |
| Canon PIXMA MG3600 Series                                 | 1         | 3.13%   |
| Canon G4010 series                                        | 1         | 3.13%   |
| Brother QL-500 label printer                              | 1         | 3.13%   |
| Brother MFC-L2710DW series                                | 1         | 3.13%   |
| Brother HL-1110 series                                    | 1         | 3.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 7         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20     | 2         | 28.57%  |
| Canon CanoScan LiDE 220                | 2         | 28.57%  |
| Canon CanoScan LiDE 500F               | 1         | 14.29%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 14.29%  |
| Canon CanoScan LiDE 110                | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 889       | 23.67%  |
| IMC Networks                           | 518       | 13.79%  |
| Realtek Semiconductor                  | 310       | 8.25%   |
| Microdia                               | 293       | 7.8%    |
| Quanta                                 | 245       | 6.52%   |
| Bison Electronics                      | 233       | 6.2%    |
| Sunplus Innovation Technology          | 187       | 4.98%   |
| Cheng Uei Precision Industry (Foxlink) | 140       | 3.73%   |
| Syntek                                 | 113       | 3.01%   |
| Lite-On Technology                     | 110       | 2.93%   |
| Acer                                   | 95        | 2.53%   |
| Suyin                                  | 93        | 2.48%   |
| Apple                                  | 70        | 1.86%   |
| Silicon Motion                         | 59        | 1.57%   |
| Logitech                               | 59        | 1.57%   |
| Luxvisions Innotech Limited            | 57        | 1.52%   |
| Alcor Micro                            | 39        | 1.04%   |
| Samsung Electronics                    | 24        | 0.64%   |
| Sonix Technology                       | 23        | 0.61%   |
| Ricoh                                  | 22        | 0.59%   |
| Lenovo                                 | 15        | 0.4%    |
| Microsoft                              | 12        | 0.32%   |
| SunplusIT                              | 11        | 0.29%   |
| Importek                               | 11        | 0.29%   |
| Primax Electronics                     | 10        | 0.27%   |
| USB Camera                             | 7         | 0.19%   |
| DigiTech                               | 7         | 0.19%   |
| ShineTech                              | 6         | 0.16%   |
| ALi                                    | 6         | 0.16%   |
| Z-Star Microelectronics                | 5         | 0.13%   |
| Intel                                  | 5         | 0.13%   |
| Genesys Logic                          | 5         | 0.13%   |
| Denron                                 | 5         | 0.13%   |
| Y Media                                | 4         | 0.11%   |
| OmniVision Technologies                | 4         | 0.11%   |
| GEMBIRD                                | 4         | 0.11%   |
| USB Camera CS                          | 3         | 0.08%   |
| Tobii Technology AB                    | 3         | 0.08%   |
| MacroSilicon                           | 3         | 0.08%   |
| Creative Technology                    | 3         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 231       | 6.13%   |
| IMC Networks Integrated Camera                      | 169       | 4.48%   |
| Microdia Integrated_Webcam_HD                       | 148       | 3.93%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 133       | 3.53%   |
| Realtek Integrated_Webcam_HD                        | 119       | 3.16%   |
| Chicony HD WebCam                                   | 106       | 2.81%   |
| Bison Integrated Camera                             | 79        | 2.1%    |
| Syntek Integrated Camera                            | 75        | 1.99%   |
| Sunplus Integrated_Webcam_HD                        | 64        | 1.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 48        | 1.27%   |
| Quanta HD User Facing                               | 43        | 1.14%   |
| Lite-On Integrated Camera                           | 41        | 1.09%   |
| Quanta HP TrueVision HD Camera                      | 37        | 0.98%   |
| Chicony HP HD Camera                                | 29        | 0.77%   |
| Chicony HD User Facing                              | 28        | 0.74%   |
| Bison Lenovo EasyCamera                             | 28        | 0.74%   |
| Microdia Integrated Webcam                          | 27        | 0.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 27        | 0.72%   |
| Lite-On HP HD Camera                                | 27        | 0.72%   |
| Realtek USB Camera                                  | 26        | 0.69%   |
| Chicony USB2.0 Camera                               | 26        | 0.69%   |
| Chicony HP Truevision HD camera                     | 26        | 0.69%   |
| Quanta HD Webcam                                    | 25        | 0.66%   |
| Chicony USB2.0 HD UVC WebCam                        | 25        | 0.66%   |
| Chicony HP Wide Vision HD Camera                    | 25        | 0.66%   |
| Acer SunplusIT Integrated Camera                    | 25        | 0.66%   |
| Samsung Galaxy series, misc. (MTP mode)             | 24        | 0.64%   |
| Chicony HP TrueVision HD                            | 24        | 0.64%   |
| IMC Networks HD Camera                              | 23        | 0.61%   |
| Chicony Lenovo EasyCamera                           | 23        | 0.61%   |
| Chicony EasyCamera                                  | 23        | 0.61%   |
| Apple FaceTime HD Camera                            | 23        | 0.61%   |
| Acer Integrated Camera                              | 23        | 0.61%   |
| Realtek USB2.0 HD UVC WebCam                        | 22        | 0.58%   |
| Microdia Laptop_Integrated_Webcam_HD                | 22        | 0.58%   |
| Chicony Integrated Camera (1280x720@30)             | 22        | 0.58%   |
| Syntek Lenovo EasyCamera                            | 21        | 0.56%   |
| Sunplus HD WebCam                                   | 21        | 0.56%   |
| Quanta HP Wide Vision HD Camera                     | 21        | 0.56%   |
| IMC Networks HP TrueVision HD Camera                | 21        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 261       | 31.37%  |
| Synaptics                          | 223       | 26.8%   |
| Shenzhen Goodix Technology         | 174       | 20.91%  |
| Elan Microelectronics              | 65        | 7.81%   |
| LighTuning Technology              | 37        | 4.45%   |
| Upek                               | 28        | 3.37%   |
| AuthenTec                          | 22        | 2.64%   |
| STMicroelectronics                 | 7         | 0.84%   |
| Focal-systems.Corp                 | 5         | 0.6%    |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.48%   |
| Samsung Electronics                | 3         | 0.36%   |
| DigitalPersona                     | 2         | 0.24%   |
| HOLTEK                             | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 99        | 11.9%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 71        | 8.53%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 54        | 6.49%   |
| Shenzhen Goodix Fingerprint Reader                                         | 45        | 5.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 41        | 4.93%   |
| Elan ELAN:Fingerprint                                                      | 40        | 4.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 32        | 3.85%   |
| Shenzhen Goodix FingerPrint                                                | 30        | 3.61%   |
| Validity Sensors Synaptics WBDI                                            | 25        | 3%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 25        | 3%      |
| Elan ELAN:ARM-M4                                                           | 24        | 2.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 23        | 2.76%   |
| Synaptics Fingerprint reader [HP G6]                                       | 22        | 2.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 2.4%    |
| Validity Sensors VFS491                                                    | 20        | 2.4%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 18        | 2.16%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 1.8%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 15        | 1.8%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.68%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 1.68%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 1.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 1.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.32%   |
| Synaptics WBDI                                                             | 11        | 1.32%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 11        | 1.32%   |
| Synaptics  WBDI                                                            | 9         | 1.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.08%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 0.96%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.96%   |
| Synaptics UWP WBDI Device                                                  | 7         | 0.84%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.84%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 0.72%   |
| Synaptics WBDI Device                                                      | 6         | 0.72%   |
| Synaptics UWP WBDI                                                         | 6         | 0.72%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 0.6%    |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 5         | 0.6%    |
| AuthenTec AES2810                                                          | 5         | 0.6%    |
| Unknown                                                                    | 5         | 0.6%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.48%   |
| Synaptics TouchPad                                                         | 4         | 0.48%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 103       | 37.05%  |
| Alcor Micro               | 99        | 35.61%  |
| Upek                      | 19        | 6.83%   |
| O2 Micro                  | 19        | 6.83%   |
| Lenovo                    | 17        | 6.12%   |
| Yubico.com                | 8         | 2.88%   |
| Gemalto (was Gemplus)     | 5         | 1.8%    |
| Reiner SCT Kartensysteme  | 1         | 0.36%   |
| Realtek Semiconductor     | 1         | 0.36%   |
| OmniKey                   | 1         | 0.36%   |
| Hewlett-Packard           | 1         | 0.36%   |
| Clay Logic                | 1         | 0.36%   |
| C3PO                      | 1         | 0.36%   |
| Aladdin Knowledge Systems | 1         | 0.36%   |
| Advanced Card Systems     | 1         | 0.36%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 99        | 35.61%  |
| Broadcom BCM5880 Secure Applications Processor                               | 37        | 13.31%  |
| Broadcom 5880                                                                | 32        | 11.51%  |
| Broadcom 58200                                                               | 20        | 7.19%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 19        | 6.83%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 6.47%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 6.12%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 5.04%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 2.52%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.08%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.36%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.36%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.36%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.36%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.36%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.36%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.36%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.36%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.36%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.36%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.36%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.36%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2510      | 59.96%  |
| 1     | 1336      | 31.92%  |
| 2     | 315       | 7.53%   |
| 3     | 21        | 0.5%    |
| 4     | 4         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 817       | 41.2%   |
| Graphics card            | 361       | 18.2%   |
| Chipcard                 | 252       | 12.71%  |
| Multimedia controller    | 174       | 8.77%   |
| Net/wireless             | 153       | 7.72%   |
| Camera                   | 63        | 3.18%   |
| Net/ethernet             | 52        | 2.62%   |
| Bluetooth                | 41        | 2.07%   |
| Storage                  | 20        | 1.01%   |
| Card reader              | 17        | 0.86%   |
| Sound                    | 11        | 0.55%   |
| Communication controller | 8         | 0.4%    |
| Network                  | 4         | 0.2%    |
| Modem                    | 4         | 0.2%    |
| Dvb card                 | 4         | 0.2%    |
| Storage/nvme             | 2         | 0.1%    |

