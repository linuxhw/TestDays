Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [cca5aa2900](https://linux-hardware.org/?probe=cca5aa2900) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2c8c33becf](https://linux-hardware.org/?probe=2c8c33becf) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [97f8f86784](https://linux-hardware.org/?probe=97f8f86784) | Aug 04, 2021 |
| Notebook      | NJ50_70CU                   | Notebook    | [a9b3790d07](https://linux-hardware.org/?probe=a9b3790d07) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2d764714a4](https://linux-hardware.org/?probe=2d764714a4) | Aug 04, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [b2a62f65d6](https://linux-hardware.org/?probe=b2a62f65d6) | Aug 04, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [09a6257403](https://linux-hardware.org/?probe=09a6257403) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [eafaf5ece3](https://linux-hardware.org/?probe=eafaf5ece3) | Aug 04, 2021 |
| ASUSTek       | N53Ta                       | Notebook    | [896a02b57b](https://linux-hardware.org/?probe=896a02b57b) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c0bf2b7b10](https://linux-hardware.org/?probe=c0bf2b7b10) | Aug 03, 2021 |
| HP            | 3047h                       | Desktop     | [6294617672](https://linux-hardware.org/?probe=6294617672) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [3d29b58c58](https://linux-hardware.org/?probe=3d29b58c58) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [8b35a81ed6](https://linux-hardware.org/?probe=8b35a81ed6) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [87bca8ecbc](https://linux-hardware.org/?probe=87bca8ecbc) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [fbbd748072](https://linux-hardware.org/?probe=fbbd748072) | Aug 03, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [a7bdbd8ebe](https://linux-hardware.org/?probe=a7bdbd8ebe) | Aug 03, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [71738ebf7e](https://linux-hardware.org/?probe=71738ebf7e) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [06d86172a1](https://linux-hardware.org/?probe=06d86172a1) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [aa415746d6](https://linux-hardware.org/?probe=aa415746d6) | Aug 03, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c8674581d0](https://linux-hardware.org/?probe=c8674581d0) | Aug 03, 2021 |
| Dell          | Latitude E4310              | Notebook    | [75a9aa20f2](https://linux-hardware.org/?probe=75a9aa20f2) | Aug 03, 2021 |
| Google        | Enguarde                    | Notebook    | [c758164470](https://linux-hardware.org/?probe=c758164470) | Aug 03, 2021 |
| Lenovo        | ThinkPad R61e 7650DHU       | Notebook    | [82f2f3a1a7](https://linux-hardware.org/?probe=82f2f3a1a7) | Aug 03, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [1f83d95a2a](https://linux-hardware.org/?probe=1f83d95a2a) | Aug 03, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | Notebook    | [c14dd630ed](https://linux-hardware.org/?probe=c14dd630ed) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99ccdd5455](https://linux-hardware.org/?probe=99ccdd5455) | Aug 02, 2021 |
| Supermicro    | X11SSH-F                    | Desktop     | [641e4fd8ce](https://linux-hardware.org/?probe=641e4fd8ce) | Aug 02, 2021 |
| Lenovo        | Reno                        | Server      | [91a367ab6d](https://linux-hardware.org/?probe=91a367ab6d) | Aug 02, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [aa5aaf6fd0](https://linux-hardware.org/?probe=aa5aaf6fd0) | Aug 02, 2021 |
| SimpliVity    | 04N3DF A03                  | Server      | [c5705e6436](https://linux-hardware.org/?probe=c5705e6436) | Aug 02, 2021 |
| Google        | Stout                       | Notebook    | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | Notebook    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | Desktop     | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | Notebook    | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| ASUSTek       | A88X-PRO                    | Desktop     | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP            | 2187 A01                    | Desktop     | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [8f40021fde](https://linux-hardware.org/?probe=8f40021fde) | Aug 01, 2021 |
| ASRock        | J1900D2Y                    | Desktop     | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | Notebook    | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell          | 0WVYMC A00                  | Desktop     | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | Notebook    | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | Notebook    | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | Notebook    | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| Dell          | 0TY915                      | Desktop     | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek       | LEONITE                     | Desktop     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn       | 2AA9                        | Desktop     | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| ASRock        | B85M Pro4                   | Desktop     | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | Notebook    | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | Notebook    | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | Notebook    | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [cc099348c2](https://linux-hardware.org/?probe=cc099348c2) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | Notebook    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | Notebook    | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | Notebook    | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | Notebook    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Shuttle       | FX79R                       | Desktop     | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | Notebook    | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| Casper        | C17B                        | Notebook    | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | Notebook    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | Desktop     | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | Notebook    | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | Notebook    | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | Notebook    | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | Notebook    | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [52e5d3e16d](https://linux-hardware.org/?probe=52e5d3e16d) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | Desktop     | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [e7aeecff98](https://linux-hardware.org/?probe=e7aeecff98) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | Notebook    | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | Notebook    | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Dell          | Studio 1555                 | Notebook    | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | Notebook    | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | Notebook    | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | Notebook    | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | Notebook    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | Notebook    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1e2b68b7d8](https://linux-hardware.org/?probe=1e2b68b7d8) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | Notebook    | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | Desktop     | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | Desktop     | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | Desktop     | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| IBM           | I/O Port                    | Server      | [8538814cd6](https://linux-hardware.org/?probe=8538814cd6) | Jul 25, 2021 |
| Dell          | 0Y1057                      | Desktop     | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | Notebook    | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | Desktop     | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | Notebook    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | Notebook    | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | Notebook    | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | Notebook    | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | Desktop     | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [f8ad21d44a](https://linux-hardware.org/?probe=f8ad21d44a) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | Notebook    | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | Desktop     | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| Lenovo        | 3110 SDK0J40697 WIN 3305... | All in one  | [84b6274afe](https://linux-hardware.org/?probe=84b6274afe) | Jul 25, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e1db015807](https://linux-hardware.org/?probe=e1db015807) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | Notebook    | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | Notebook    | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | Notebook    | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | Notebook    | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Compulab      | fitlet2                     | Mini pc     | [9d1571afa4](https://linux-hardware.org/?probe=9d1571afa4) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | Desktop     | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | Desktop     | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | Notebook    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | Notebook    | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Protectli     | FW6                         | Desktop     | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Lenovo        | Yoga 710-11ISK 80TX         | Convertible | [c34bcc095c](https://linux-hardware.org/?probe=c34bcc095c) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | Desktop     | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | Desktop     | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [0c49a20e7c](https://linux-hardware.org/?probe=0c49a20e7c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | Desktop     | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | Notebook    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | Notebook    | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| Supermicro    | X11DDW-L                    | Server      | [6fab4e3135](https://linux-hardware.org/?probe=6fab4e3135) | Jul 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| Dell          | 0H5J4J A01                  | Server      | [fbdf83f7ff](https://linux-hardware.org/?probe=fbdf83f7ff) | Jul 17, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | Notebook    | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | Notebook    | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| Dell          | Latitude E6330              | Notebook    | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | Notebook    | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| MSI           | MS-6712                     | Desktop     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| HP            | Compaq 6830s                | Notebook    | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [457f309f39](https://linux-hardware.org/?probe=457f309f39) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [945a4600c4](https://linux-hardware.org/?probe=945a4600c4) | Jul 02, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | Notebook    | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| MSI           | B85M-G43                    | Desktop     | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2) (... | Phone       | [6805b89f3d](https://linux-hardware.org/?probe=6805b89f3d) | Jun 25, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | Desktop     | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| Dell          | 04WYPY A04                  | Server      | [20fa770830](https://linux-hardware.org/?probe=20fa770830) | Jun 22, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Dell          | Precision 3560              | Notebook    | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | Notebook    | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | Desktop     | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Unknown       | Helios64                    | Soc         | [33c6248333](https://linux-hardware.org/?probe=33c6248333) | Jun 11, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| Dell          | Latitude E7470              | Notebook    | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | Desktop     | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | Notebook    | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | Notebook    | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | Notebook    | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | Notebook    | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f77e2ebb10](https://linux-hardware.org/?probe=f77e2ebb10) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Toshiba       | Satellite U800W             | Notebook    | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [eb3d04e089](https://linux-hardware.org/?probe=eb3d04e089) | May 29, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [92aa2017b9](https://linux-hardware.org/?probe=92aa2017b9) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | CX700                       | Notebook    | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [7ca350189c](https://linux-hardware.org/?probe=7ca350189c) | May 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | Notebook    | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | Notebook    | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Dell          | Latitude 7410               | Convertible | [bc7c58f248](https://linux-hardware.org/?probe=bc7c58f248) | May 21, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [1c271464f4](https://linux-hardware.org/?probe=1c271464f4) | May 21, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7410               | Convertible | [cbd8832f44](https://linux-hardware.org/?probe=cbd8832f44) | May 19, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | Notebook    | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| sunxi         | Unknown                     | Soc         | [d54c3a2a33](https://linux-hardware.org/?probe=d54c3a2a33) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FEA0... | Convertible | [2a0eca4670](https://linux-hardware.org/?probe=2a0eca4670) | May 17, 2021 |
| HP            | Compaq Presario C700        | Notebook    | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| HP            | Split 13 x2 PC              | Notebook    | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| Biostar       | B450MH                      | Desktop     | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [446238dd0c](https://linux-hardware.org/?probe=446238dd0c) | Apr 25, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [bb76391a12](https://linux-hardware.org/?probe=bb76391a12) | Apr 25, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | Notebook    | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [c0536c5433](https://linux-hardware.org/?probe=c0536c5433) | Apr 13, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [935ccffcd5](https://linux-hardware.org/?probe=935ccffcd5) | Feb 01, 2021 |
| Unknown       | Shenzhen Amediatech Tech... | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| sunxi         | Unknown                     | Soc         | [604dd9d393](https://linux-hardware.org/?probe=604dd9d393) | Feb 25, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.0-8-amd64                 | 204       | 49.64%  |
| 5.10.0-7-amd64                 | 106       | 25.79%  |
| 5.10.0-6-amd64                 | 37        | 9%      |
| 5.11.22-1-pve                  | 5         | 1.22%   |
| 5.10.0-8-686-pae               | 3         | 0.73%   |
| 5.10.0-8-686                   | 3         | 0.73%   |
| 5.12.0-19.3-liquorix-amd64     | 2         | 0.49%   |
| 5.11.22-2-pve                  | 2         | 0.49%   |
| 5.10.0-8-rt-amd64              | 2         | 0.49%   |
| 5.10-sunxi64                   | 2         | 0.49%   |
| 4.19.0-14-amd64                | 2         | 0.49%   |
| 5.9.0-arm-64                   | 1         | 0.24%   |
| 5.8.0-3-amd64                  | 1         | 0.24%   |
| 5.4.18-sunxi64                 | 1         | 0.24%   |
| 5.4.0-73-generic               | 1         | 0.24%   |
| 5.14.0-rc3-prygun              | 1         | 0.24%   |
| 5.13.5-xanmod1                 | 1         | 0.24%   |
| 5.13.4-e5520                   | 1         | 0.24%   |
| 5.13.4                         | 1         | 0.24%   |
| 5.13.1a                        | 1         | 0.24%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1         | 0.24%   |
| 5.12.4                         | 1         | 0.24%   |
| 5.12.10                        | 1         | 0.24%   |
| 5.12.1                         | 1         | 0.24%   |
| 5.12.0-9.2-liquorix-amd64      | 1         | 0.24%   |
| 5.12.0-14.2-liquorix-amd64     | 1         | 0.24%   |
| 5.11.9+                        | 1         | 0.24%   |
| 5.11.22-3-pve                  | 1         | 0.24%   |
| 5.11.15-terranz                | 1         | 0.24%   |
| 5.11.15-051115-generic         | 1         | 0.24%   |
| 5.11.14                        | 1         | 0.24%   |
| 5.11.0-rc6                     | 1         | 0.24%   |
| 5.11.0-21.1-liquorix-amd64     | 1         | 0.24%   |
| 5.11.0-16.1-liquorix-amd64     | 1         | 0.24%   |
| 5.10.46custom                  | 1         | 0.24%   |
| 5.10.42+truenas                | 1         | 0.24%   |
| 5.10.40-ismynik                | 1         | 0.24%   |
| 5.10.38-falcot                 | 1         | 0.24%   |
| 5.10.35-rockchip64             | 1         | 0.24%   |
| 5.10.21-sunxi                  | 1         | 0.24%   |
| 5.10.12-sunxi                  | 1         | 0.24%   |
| 5.10.10-64                     | 1         | 0.24%   |
| 5.10.0-io7-amd64               | 1         | 0.24%   |
| 5.10.0-8-armmp                 | 1         | 0.24%   |
| 5.10.0-7-686-pae               | 1         | 0.24%   |
| 5.10.0-6-rt-amd64              | 1         | 0.24%   |
| 5.10.0-6-686                   | 1         | 0.24%   |
| 5.10.0-5-amd64                 | 1         | 0.24%   |
| 5.10.0-4-amd64                 | 1         | 0.24%   |
| 5.10.0-3-amd64                 | 1         | 0.24%   |
| 5.10.0-2-amd64                 | 1         | 0.24%   |
| 4.19.181-z580322               | 1         | 0.24%   |
| 4.19.0-16-amd64                | 1         | 0.24%   |
| 4.19.0-16-686-pae              | 1         | 0.24%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 355       | 88.53%  |
| 5.11.22  | 8         | 2%      |
| 4.19.0   | 4         | 1%      |
| 5.12.0   | 3         | 0.75%   |
| 5.11.0   | 3         | 0.75%   |
| 5.13.4   | 2         | 0.5%    |
| 5.11.15  | 2         | 0.5%    |
| 5.10     | 2         | 0.5%    |
| 5.9.0    | 1         | 0.25%   |
| 5.8.0    | 1         | 0.25%   |
| 5.4.18   | 1         | 0.25%   |
| 5.4.0    | 1         | 0.25%   |
| 5.14.0   | 1         | 0.25%   |
| 5.13.5   | 1         | 0.25%   |
| 5.13.1   | 1         | 0.25%   |
| 5.13.0   | 1         | 0.25%   |
| 5.12.4   | 1         | 0.25%   |
| 5.12.10  | 1         | 0.25%   |
| 5.12.1   | 1         | 0.25%   |
| 5.11.9   | 1         | 0.25%   |
| 5.11.14  | 1         | 0.25%   |
| 5.10.46  | 1         | 0.25%   |
| 5.10.42  | 1         | 0.25%   |
| 5.10.40  | 1         | 0.25%   |
| 5.10.38  | 1         | 0.25%   |
| 5.10.35  | 1         | 0.25%   |
| 5.10.21  | 1         | 0.25%   |
| 5.10.12  | 1         | 0.25%   |
| 5.10.10  | 1         | 0.25%   |
| 4.19.181 | 1         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 362       | 90.5%   |
| 5.11    | 15        | 3.75%   |
| 5.12    | 6         | 1.5%    |
| 5.13    | 5         | 1.25%   |
| 4.19    | 5         | 1.25%   |
| 5.4     | 2         | 0.5%    |
| 5       | 2         | 0.5%    |
| 5.9     | 1         | 0.25%   |
| 5.8     | 1         | 0.25%   |
| 5.14    | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 384       | 96%     |
| i686    | 9         | 2.25%   |
| aarch64 | 5         | 1.25%   |
| armv7l  | 2         | 0.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 110       | 27.3%   |
| KDE5             | 79        | 19.6%   |
| Unknown          | 58        | 14.39%  |
| XFCE             | 39        | 9.68%   |
| MATE             | 29        | 7.2%    |
| Cinnamon         | 14        | 3.47%   |
| LXQt             | 13        | 3.23%   |
| i3               | 11        | 2.73%   |
| LXDE             | 10        | 2.48%   |
| KDE              | 10        | 2.48%   |
| X-Cinnamon       | 8         | 1.99%   |
| Trinity          | 5         | 1.24%   |
| lightdm-xsession | 4         | 0.99%   |
| GNOME Flashback  | 4         | 0.99%   |
| sway             | 2         | 0.5%    |
| openbox          | 2         | 0.5%    |
| GNUstep          | 1         | 0.25%   |
| Enlightenment    | 1         | 0.25%   |
| default          | 1         | 0.25%   |
| Budgie           | 1         | 0.25%   |
| awesome          | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 244       | 60.7%   |
| Wayland | 88        | 21.89%  |
| Tty     | 36        | 8.96%   |
| Unknown | 34        | 8.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 112       | 27.86%  |
| GDM     | 103       | 25.62%  |
| Unknown | 92        | 22.89%  |
| SDDM    | 82        | 20.4%   |
| LightDM | 8         | 1.99%   |
| XDM     | 2         | 0.5%    |
| SLiM    | 2         | 0.5%    |
| KDM     | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 164       | 40.9%   |
| ru_RU   | 31        | 7.73%   |
| en_GB   | 30        | 7.48%   |
| Unknown | 25        | 6.23%   |
| de_DE   | 24        | 5.99%   |
| fr_FR   | 22        | 5.49%   |
| es_ES   | 11        | 2.74%   |
| pt_BR   | 9         | 2.24%   |
| pl_PL   | 9         | 2.24%   |
| en_IN   | 8         | 2%      |
| C       | 7         | 1.75%   |
| en_AU   | 5         | 1.25%   |
| it_IT   | 4         | 1%      |
| en_CA   | 4         | 1%      |
| tr_TR   | 3         | 0.75%   |
| nl_BE   | 3         | 0.75%   |
| ja_JP   | 3         | 0.75%   |
| hu_HU   | 3         | 0.75%   |
| de_CH   | 3         | 0.75%   |
| cs_CZ   | 3         | 0.75%   |
| uk_UA   | 2         | 0.5%    |
| ru_UA   | 2         | 0.5%    |
| ro_RO   | 2         | 0.5%    |
| pt_PT   | 2         | 0.5%    |
| hr_HR   | 2         | 0.5%    |
| es_AR   | 2         | 0.5%    |
| en_SG   | 2         | 0.5%    |
| en_HK   | 2         | 0.5%    |
| sv_SE   | 1         | 0.25%   |
| sr_RS   | 1         | 0.25%   |
| sk_SK   | 1         | 0.25%   |
| gl_ES   | 1         | 0.25%   |
| fi_FI   | 1         | 0.25%   |
| es_VE   | 1         | 0.25%   |
| es_US   | 1         | 0.25%   |
| es_MX   | 1         | 0.25%   |
| es_EC   | 1         | 0.25%   |
| es_CO   | 1         | 0.25%   |
| en_SI   | 1         | 0.25%   |
| en_PH   | 1         | 0.25%   |
| en_IE   | 1         | 0.25%   |
| ca_ES   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 254       | 63.18%  |
| BIOS | 148       | 36.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 306       | 76.5%   |
| Overlay | 42        | 10.5%   |
| Btrfs   | 28        | 7%      |
| Zfs     | 9         | 2.25%   |
| Xfs     | 5         | 1.25%   |
| Ext3    | 5         | 1.25%   |
| Unknown | 4         | 1%      |
| Rootfs  | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 275       | 68.41%  |
| MBR     | 89        | 22.14%  |
| Unknown | 38        | 9.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 319       | 79.55%  |
| Yes       | 82        | 20.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 291       | 72.57%  |
| Yes       | 110       | 27.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 83        | 20.75%  |
| ASUSTek Computer        | 59        | 14.75%  |
| Dell                    | 51        | 12.75%  |
| Hewlett-Packard         | 47        | 11.75%  |
| Gigabyte Technology     | 35        | 8.75%   |
| ASRock                  | 23        | 5.75%   |
| MSI                     | 22        | 5.5%    |
| Acer                    | 14        | 3.5%    |
| Apple                   | 13        | 3.25%   |
| Intel                   | 5         | 1.25%   |
| Toshiba                 | 3         | 0.75%   |
| Supermicro              | 3         | 0.75%   |
| sunxi                   | 3         | 0.75%   |
| HUAWEI                  | 3         | 0.75%   |
| Google                  | 3         | 0.75%   |
| Fujitsu                 | 3         | 0.75%   |
| Huanan                  | 2         | 0.5%    |
| Foxconn                 | 2         | 0.5%    |
| Unknown                 | 2         | 0.5%    |
| ZOTAC                   | 1         | 0.25%   |
| UNOWHY                  | 1         | 0.25%   |
| SLIMBOOK                | 1         | 0.25%   |
| SimpliVity              | 1         | 0.25%   |
| Shuttle                 | 1         | 0.25%   |
| Samsung Electronics     | 1         | 0.25%   |
| Raspberry Pi Foundation | 1         | 0.25%   |
| Quanta                  | 1         | 0.25%   |
| Protectli               | 1         | 0.25%   |
| Pine Microsystems       | 1         | 0.25%   |
| Pegatron                | 1         | 0.25%   |
| PC Specialist           | 1         | 0.25%   |
| Panasonic               | 1         | 0.25%   |
| Notebook                | 1         | 0.25%   |
| Monster                 | 1         | 0.25%   |
| Itautec                 | 1         | 0.25%   |
| IBM                     | 1         | 0.25%   |
| HARDKERNEL              | 1         | 0.25%   |
| ECS                     | 1         | 0.25%   |
| Compulab                | 1         | 0.25%   |
| Chuwi                   | 1         | 0.25%   |
| Casper                  | 1         | 0.25%   |
| Biostar                 | 1         | 0.25%   |
| ASRockRack              | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                          | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ASUS All Series                               | 4         | 1%      |
| Apple MacBookAir7,2                           | 4         | 1%      |
| Unknown                                       | 4         | 1%      |
| Gigabyte B550I AORUS PRO AX                   | 3         | 0.75%   |
| ASRock B450M Pro4                             | 3         | 0.75%   |
| Lenovo ThinkPad E475 20H40006US               | 2         | 0.5%    |
| Lenovo G50-80 80E5                            | 2         | 0.5%    |
| HUAWEI NBLK-WAX9X                             | 2         | 0.5%    |
| HP Z620 Workstation                           | 2         | 0.5%    |
| HP EliteBook 8460p                            | 2         | 0.5%    |
| Google Enguarde                               | 2         | 0.5%    |
| Gigabyte Z77-D3H                              | 2         | 0.5%    |
| Gigabyte Z370 AORUS Gaming 5                  | 2         | 0.5%    |
| Dell XPS 13 9310                              | 2         | 0.5%    |
| Dell XPS 13 7390                              | 2         | 0.5%    |
| Dell OptiPlex 760                             | 2         | 0.5%    |
| Dell Latitude 7480                            | 2         | 0.5%    |
| Dell Inspiron 5570                            | 2         | 0.5%    |
| Dell Inspiron 3793                            | 2         | 0.5%    |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA       | 2         | 0.5%    |
| ASUS PRIME B550-PLUS                          | 2         | 0.5%    |
| ASUS PRIME B450M-A                            | 2         | 0.5%    |
| Apple MacBookAir7,1                           | 2         | 0.5%    |
| ZOTAC ZBOX-EN1070/1060,EN1070K/1060K          | 1         | 0.25%   |
| UNOWHY Y13G002S4EI                            | 1         | 0.25%   |
| Toshiba Satellite U800W                       | 1         | 0.25%   |
| Toshiba Satellite S55-A                       | 1         | 0.25%   |
| Toshiba Satellite C45-A                       | 1         | 0.25%   |
| Supermicro SYS-6019P-WT                       | 1         | 0.25%   |
| Supermicro SYS-5038MA-H24TRF                  | 1         | 0.25%   |
| Supermicro SYS-5019S-MR                       | 1         | 0.25%   |
| sunxi Banana Pi BPI-M2-Ultra                  | 1         | 0.25%   |
| SLIMBOOK PROX14-AMD                           | 1         | 0.25%   |
| SimpliVity OmniCube CN-3400-1                 | 1         | 0.25%   |
| Shuttle SX79R                                 | 1         | 0.25%   |
| Samsung 370E4K                                | 1         | 0.25%   |
| RPi Raspberry Pi 2 Model B Rev 1.1            | 1         | 0.25%   |
| Quanta TWC                                    | 1         | 0.25%   |
| Protectli FW6                                 | 1         | 0.25%   |
| Pine Microsystems Pine64 PinePhone (1.2) (DT) | 1         | 0.25%   |
| Pegatron A15                                  | 1         | 0.25%   |
| PC Specialist NV4XMB,ME,MZ                    | 1         | 0.25%   |
| Panasonic CF-AX2LDCZMF                        | 1         | 0.25%   |
| Notebook NJ50_70CU                            | 1         | 0.25%   |
| MSI U90/U100                                  | 1         | 0.25%   |
| MSI MS-7C94                                   | 1         | 0.25%   |
| MSI MS-7C84                                   | 1         | 0.25%   |
| MSI MS-7C75                                   | 1         | 0.25%   |
| MSI MS-7C56                                   | 1         | 0.25%   |
| MSI MS-7C35                                   | 1         | 0.25%   |
| MSI MS-7B89                                   | 1         | 0.25%   |
| MSI MS-7B46                                   | 1         | 0.25%   |
| MSI MS-7B09                                   | 1         | 0.25%   |
| MSI MS-7A70                                   | 1         | 0.25%   |
| MSI MS-7A40                                   | 1         | 0.25%   |
| MSI MS-7A38                                   | 1         | 0.25%   |
| MSI MS-7995                                   | 1         | 0.25%   |
| MSI MS-7823                                   | 1         | 0.25%   |
| MSI MS-7759                                   | 1         | 0.25%   |
| MSI MS-7721                                   | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 59        | 14.75%  |
| ASUS PRIME                   | 15        | 3.75%   |
| Lenovo IdeaPad               | 14        | 3.5%    |
| Dell Inspiron                | 14        | 3.5%    |
| Acer Aspire                  | 11        | 2.75%   |
| HP ProBook                   | 9         | 2.25%   |
| HP EliteBook                 | 9         | 2.25%   |
| Dell XPS                     | 9         | 2.25%   |
| Dell OptiPlex                | 9         | 2.25%   |
| Dell Latitude                | 8         | 2%      |
| ASUS ROG                     | 7         | 1.75%   |
| Dell Precision               | 6         | 1.5%    |
| Apple MacBookAir7            | 6         | 1.5%    |
| HP Laptop                    | 5         | 1.25%   |
| HP Compaq                    | 5         | 1.25%   |
| ASUS ZenBook                 | 5         | 1.25%   |
| ASUS VivoBook                | 5         | 1.25%   |
| Lenovo Yoga                  | 4         | 1%      |
| ASUS All                     | 4         | 1%      |
| Unknown                      | 4         | 1%      |
| Toshiba Satellite            | 3         | 0.75%   |
| Lenovo ThinkCentre           | 3         | 0.75%   |
| Gigabyte B550I               | 3         | 0.75%   |
| Fujitsu LIFEBOOK             | 3         | 0.75%   |
| ASRock B450M                 | 3         | 0.75%   |
| Lenovo G50-80                | 2         | 0.5%    |
| HUAWEI NBLK-WAX9X            | 2         | 0.5%    |
| HP ZBook                     | 2         | 0.5%    |
| HP Z620                      | 2         | 0.5%    |
| HP ProLiant                  | 2         | 0.5%    |
| HP OMEN                      | 2         | 0.5%    |
| HP 250                       | 2         | 0.5%    |
| Google Enguarde              | 2         | 0.5%    |
| Gigabyte Z77-D3H             | 2         | 0.5%    |
| Gigabyte Z370                | 2         | 0.5%    |
| Gigabyte AERO                | 2         | 0.5%    |
| Dell Vostro                  | 2         | 0.5%    |
| Dell PowerEdge               | 2         | 0.5%    |
| ASRock Z97                   | 2         | 0.5%    |
| Acer Nitro                   | 2         | 0.5%    |
| ZOTAC ZBOX-EN1070            | 1         | 0.25%   |
| UNOWHY Y13G002S4EI           | 1         | 0.25%   |
| Supermicro SYS-6019P-WT      | 1         | 0.25%   |
| Supermicro SYS-5038MA-H24TRF | 1         | 0.25%   |
| Supermicro SYS-5019S-MR      | 1         | 0.25%   |
| sunxi Banana                 | 1         | 0.25%   |
| SLIMBOOK PROX14-AMD          | 1         | 0.25%   |
| SimpliVity OmniCube          | 1         | 0.25%   |
| Shuttle SX79R                | 1         | 0.25%   |
| Samsung 370E4K               | 1         | 0.25%   |
| RPi Raspberry                | 1         | 0.25%   |
| Quanta TWC                   | 1         | 0.25%   |
| Protectli FW6                | 1         | 0.25%   |
| Pine Microsystems Pine64     | 1         | 0.25%   |
| Pegatron A15                 | 1         | 0.25%   |
| PC Specialist NV4XMB         | 1         | 0.25%   |
| Panasonic CF-AX2LDCZMF       | 1         | 0.25%   |
| Notebook NJ50                | 1         | 0.25%   |
| MSI U90                      | 1         | 0.25%   |
| MSI MS-7C94                  | 1         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 87        | 21.75%  |
| 2021    | 70        | 17.5%   |
| 2019    | 55        | 13.75%  |
| 2018    | 39        | 9.75%   |
| 2016    | 21        | 5.25%   |
| 2012    | 20        | 5%      |
| 2013    | 18        | 4.5%    |
| 2014    | 16        | 4%      |
| 2015    | 13        | 3.25%   |
| 2011    | 11        | 2.75%   |
| 2009    | 11        | 2.75%   |
| 2010    | 9         | 2.25%   |
| 2017    | 8         | 2%      |
| Unknown | 7         | 1.75%   |
| 2008    | 6         | 1.5%    |
| 2007    | 4         | 1%      |
| 2006    | 2         | 0.5%    |
| 2004    | 2         | 0.5%    |
| 2001    | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 217       | 54.25%  |
| Desktop        | 152       | 38%     |
| Convertible    | 9         | 2.25%   |
| System on chip | 6         | 1.5%    |
| Server         | 6         | 1.5%    |
| Mini pc        | 5         | 1.25%   |
| Tablet         | 2         | 0.5%    |
| All in one     | 2         | 0.5%    |
| Phone          | 1         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 364       | 90.55%  |
| Enabled  | 38        | 9.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 396       | 99%     |
| Yes  | 4         | 1%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 113       | 28.25%  |
| 4.01-8.0        | 83        | 20.75%  |
| 8.01-16.0       | 63        | 15.75%  |
| 3.01-4.0        | 44        | 11%     |
| 32.01-64.0      | 41        | 10.25%  |
| 64.01-256.0     | 24        | 6%      |
| 1.01-2.0        | 14        | 3.5%    |
| 2.01-3.0        | 8         | 2%      |
| 24.01-32.0      | 3         | 0.75%   |
| 0.01-0.5        | 3         | 0.75%   |
| More than 256.0 | 2         | 0.5%    |
| 0.51-1.0        | 2         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 95        | 23.4%   |
| 2.01-3.0    | 88        | 21.67%  |
| 4.01-8.0    | 69        | 17%     |
| 3.01-4.0    | 56        | 13.79%  |
| 0.51-1.0    | 35        | 8.62%   |
| 8.01-16.0   | 33        | 8.13%   |
| 0.01-0.5    | 18        | 4.43%   |
| 24.01-32.0  | 4         | 0.99%   |
| 16.01-24.0  | 4         | 0.99%   |
| 32.01-64.0  | 3         | 0.74%   |
| 64.01-256.0 | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 207       | 51.75%  |
| 2      | 116       | 29%     |
| 3      | 32        | 8%      |
| 4      | 18        | 4.5%    |
| 5      | 12        | 3%      |
| 8      | 5         | 1.25%   |
| 9      | 3         | 0.75%   |
| 6      | 3         | 0.75%   |
| 0      | 2         | 0.5%    |
| 28     | 1         | 0.25%   |
| 10     | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 273       | 68.25%  |
| Yes       | 127       | 31.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 338       | 84.5%   |
| No        | 62        | 15.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 276       | 69%     |
| No        | 124       | 31%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 227       | 56.75%  |
| No        | 173       | 43.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 85        | 21.25%  |
| Russia                 | 37        | 9.25%   |
| Germany                | 36        | 9%      |
| France                 | 32        | 8%      |
| UK                     | 19        | 4.75%   |
| Spain                  | 16        | 4%      |
| Poland                 | 16        | 4%      |
| Ukraine                | 13        | 3.25%   |
| Brazil                 | 11        | 2.75%   |
| Netherlands            | 9         | 2.25%   |
| India                  | 8         | 2%      |
| Canada                 | 7         | 1.75%   |
| Greece                 | 6         | 1.5%    |
| Czechia                | 6         | 1.5%    |
| Australia              | 6         | 1.5%    |
| Switzerland            | 5         | 1.25%   |
| Mexico                 | 5         | 1.25%   |
| Italy                  | 5         | 1.25%   |
| Hungary                | 5         | 1.25%   |
| Turkey                 | 4         | 1%      |
| Thailand               | 4         | 1%      |
| Portugal               | 4         | 1%      |
| Norway                 | 4         | 1%      |
| Kazakhstan             | 4         | 1%      |
| Bulgaria               | 4         | 1%      |
| Belarus                | 4         | 1%      |
| Argentina              | 4         | 1%      |
| Japan                  | 3         | 0.75%   |
| Finland                | 3         | 0.75%   |
| Ecuador                | 3         | 0.75%   |
| Croatia                | 3         | 0.75%   |
| Belgium                | 3         | 0.75%   |
| Austria                | 3         | 0.75%   |
| Venezuela              | 2         | 0.5%    |
| Sweden                 | 2         | 0.5%    |
| Slovenia               | 2         | 0.5%    |
| Vietnam                | 1         | 0.25%   |
| Syria                  | 1         | 0.25%   |
| Singapore              | 1         | 0.25%   |
| Serbia                 | 1         | 0.25%   |
| Romania                | 1         | 0.25%   |
| Philippines            | 1         | 0.25%   |
| New Caledonia          | 1         | 0.25%   |
| Mongolia               | 1         | 0.25%   |
| Malaysia               | 1         | 0.25%   |
| Madagascar             | 1         | 0.25%   |
| Indonesia              | 1         | 0.25%   |
| Hong Kong              | 1         | 0.25%   |
| Denmark                | 1         | 0.25%   |
| Colombia               | 1         | 0.25%   |
| China                  | 1         | 0.25%   |
| Bosnia and Herzegovina | 1         | 0.25%   |
| Bangladesh             | 1         | 0.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Portland       | 23        | 5.74%   |
| St Petersburg  | 9         | 2.24%   |
| Paris          | 8         | 2%      |
| Lyon           | 6         | 1.5%    |
| Ocala          | 5         | 1.25%   |
| Kalamazoo      | 5         | 1.25%   |
| Athens         | 5         | 1.25%   |
| Warsaw         | 4         | 1%      |
| Sofia          | 4         | 1%      |
| Moscow         | 4         | 1%      |
| London         | 4         | 1%      |
| Kyiv           | 4         | 1%      |
| Ensenada       | 4         | 1%      |
| Berlin         | 4         | 1%      |
| Bengaluru      | 4         | 1%      |
| Bangkok        | 4         | 1%      |
| Vienna         | 3         | 0.75%   |
| Sunnyvale      | 3         | 0.75%   |
| Perm           | 3         | 0.75%   |
| Mesa           | 3         | 0.75%   |
| Madrid         | 3         | 0.75%   |
| Gloucester     | 3         | 0.75%   |
| Zagreb         | 2         | 0.5%    |
| Waregem        | 2         | 0.5%    |
| Sydney         | 2         | 0.5%    |
| Shizuoka       | 2         | 0.5%    |
| Saratov        | 2         | 0.5%    |
| Saint-Denis    | 2         | 0.5%    |
| Rio de Janeiro | 2         | 0.5%    |
| Prague         | 2         | 0.5%    |
| Oleksandrivka  | 2         | 0.5%    |
| Noblesville    | 2         | 0.5%    |
| New York       | 2         | 0.5%    |
| Munich         | 2         | 0.5%    |
| Mainz          | 2         | 0.5%    |
| Lublin         | 2         | 0.5%    |
| Las Vegas      | 2         | 0.5%    |
| Kharkiv        | 2         | 0.5%    |
| Istanbul       | 2         | 0.5%    |
| Hanover        | 2         | 0.5%    |
| Hakadal        | 2         | 0.5%    |
| Gorinchem      | 2         | 0.5%    |
| Fryazino       | 2         | 0.5%    |
| Donetsk        | 2         | 0.5%    |
| Cuenca         | 2         | 0.5%    |
| Clitheroe      | 2         | 0.5%    |
| Burnaby        | 2         | 0.5%    |
| Ankara         | 2         | 0.5%    |
| Amsterdam      | 2         | 0.5%    |
| Ajdov????ina   | 2         | 0.5%    |
| Érd           | 1         | 0.25%   |
| Zurich         | 1         | 0.25%   |
| Zaragoza       | 1         | 0.25%   |
| Yekaterinburg  | 1         | 0.25%   |
| Wroclaw        | 1         | 0.25%   |
| Woolloongabba  | 1         | 0.25%   |
| Woodstock      | 1         | 0.25%   |
| Wenatchee      | 1         | 0.25%   |
| Waterloo       | 1         | 0.25%   |
| Voerde         | 1         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 101       | 137    | 16.86%  |
| WDC                 | 96        | 167    | 16.03%  |
| Seagate             | 86        | 123    | 14.36%  |
| Toshiba             | 40        | 56     | 6.68%   |
| Kingston            | 39        | 45     | 6.51%   |
| Crucial             | 29        | 32     | 4.84%   |
| Unknown             | 27        | 37     | 4.51%   |
| Intel               | 19        | 26     | 3.17%   |
| SanDisk             | 17        | 21     | 2.84%   |
| Hitachi             | 14        | 15     | 2.34%   |
| SK Hynix            | 13        | 15     | 2.17%   |
| A-DATA Technology   | 11        | 15     | 1.84%   |
| HGST                | 9         | 12     | 1.5%    |
| Apple               | 9         | 9      | 1.5%    |
| SABRENT             | 8         | 8      | 1.34%   |
| China               | 6         | 6      | 1%      |
| PNY                 | 5         | 5      | 0.83%   |
| Micron Technology   | 5         | 5      | 0.83%   |
| KIOXIA              | 5         | 5      | 0.83%   |
| Transcend           | 4         | 5      | 0.67%   |
| SPCC                | 4         | 4      | 0.67%   |
| Union Memory        | 3         | 3      | 0.5%    |
| Phison              | 3         | 6      | 0.5%    |
| Patriot             | 3         | 3      | 0.5%    |
| LITEONIT            | 3         | 3      | 0.5%    |
| JMicron             | 3         | 3      | 0.5%    |
| Intenso             | 3         | 4      | 0.5%    |
| Gigabyte Technology | 3         | 3      | 0.5%    |
| Fujitsu             | 3         | 3      | 0.5%    |
| Phison Electronics  | 2         | 2      | 0.33%   |
| LITEON              | 2         | 2      | 0.33%   |
| Lenovo              | 2         | 2      | 0.33%   |
| Corsair             | 2         | 2      | 0.33%   |
| ZTC                 | 1         | 1      | 0.17%   |
| XPG                 | 1         | 1      | 0.17%   |
| TrueNAS             | 1         | 1      | 0.17%   |
| Team                | 1         | 1      | 0.17%   |
| T-FORCE             | 1         | 1      | 0.17%   |
| SILICONMOTION       | 1         | 1      | 0.17%   |
| Silicon Motion      | 1         | 2      | 0.17%   |
| OCZ                 | 1         | 1      | 0.17%   |
| Maxtor              | 1         | 2      | 0.17%   |
| Maximus             | 1         | 1      | 0.17%   |
| MaxDigital          | 1         | 2      | 0.17%   |
| Lexar               | 1         | 1      | 0.17%   |
| LDLC                | 1         | 1      | 0.17%   |
| KingDian            | 1         | 1      | 0.17%   |
| IBM-ESXS            | 1         | 2      | 0.17%   |
| GOODRAM             | 1         | 1      | 0.17%   |
| DOGFISH             | 1         | 1      | 0.17%   |
| ASUS-PHISON         | 1         | 1      | 0.17%   |
| Apacer              | 1         | 1      | 0.17%   |
| AMD                 | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB            | 12        | 1.75%   |
| Samsung SSD 970 EVO Plus 1TB       | 10        | 1.46%   |
| SABRENT Disk 160GB                 | 8         | 1.16%   |
| Samsung SSD 850 EVO 250GB          | 7         | 1.02%   |
| Kingston SA400S37120G 120GB SSD    | 7         | 1.02%   |
| Samsung SSD 970 EVO Plus 500GB     | 6         | 0.87%   |
| Samsung SSD 860 EVO 500GB          | 6         | 0.87%   |
| Samsung SSD 850 EVO 500GB          | 6         | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB     | 5         | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 0.73%   |
| Kingston SA400S37240G 240GB SSD    | 5         | 0.73%   |
| Crucial CT500MX500SSD1 500GB       | 5         | 0.73%   |
| Toshiba HDWD110 1TB                | 4         | 0.58%   |
| Toshiba DT01ACA200 2TB             | 4         | 0.58%   |
| Seagate ST500DM002-1BD142 500GB    | 4         | 0.58%   |
| Seagate ST4000DM004-2CV104 4TB     | 4         | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB     | 4         | 0.58%   |
| Samsung SSD 860 EVO 250GB          | 4         | 0.58%   |
| Kingston SV300S37A240G 240GB SSD   | 4         | 0.58%   |
| Kingston SV300S37A120G 120GB SSD   | 4         | 0.58%   |
| Crucial CT1000P1SSD8 1TB           | 4         | 0.58%   |
| Crucial CT1000MX500SSD1 1TB        | 4         | 0.58%   |
| Apple SSD SM0128G 121GB            | 4         | 0.58%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 3         | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 3         | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 3         | 0.44%   |
| WDC WD10SPZX-21Z10T0 1TB           | 3         | 0.44%   |
| Unknown DA4064  64GB               | 3         | 0.44%   |
| Toshiba MQ04ABF100 1TB             | 3         | 0.44%   |
| Toshiba DT01ACA300 3TB             | 3         | 0.44%   |
| Seagate ST2000LX001-1RG174 2TB     | 3         | 0.44%   |
| Seagate ST2000DM001-1ER164 2TB     | 3         | 0.44%   |
| Seagate Backup+ Hub BK 4TB         | 3         | 0.44%   |
| SanDisk SSD PLUS 240GB             | 3         | 0.44%   |
| Samsung SSD 860 EVO M.2 1TB        | 3         | 0.44%   |
| Samsung SSD 840 PRO Series 256GB   | 3         | 0.44%   |
| Kingston SUV400S37120G 120GB SSD   | 3         | 0.44%   |
| Hitachi HUS724040ALE641 4TB        | 3         | 0.44%   |
| HGST HTS721010A9E630 1TB           | 3         | 0.44%   |
| Crucial CT500P1SSD8 500GB          | 3         | 0.44%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 2         | 0.29%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 2         | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 2         | 0.29%   |
| WDC WD40EFRX-68N32N0 4TB           | 2         | 0.29%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 2         | 0.29%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 0.29%   |
| WDC WD20EARX-00PASB0 2TB           | 2         | 0.29%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 0.29%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2         | 0.29%   |
| WDC WD10EZEX-00BN5A0 1TB           | 2         | 0.29%   |
| WDC WD10EFRX-68FYTN0 1TB           | 2         | 0.29%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 2         | 0.29%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB | 2         | 0.29%   |
| Unknown SL16G  16GB                | 2         | 0.29%   |
| Unknown SD/MMC/MS PRO 32GB         | 2         | 0.29%   |
| Unknown MMC Card  64GB             | 2         | 0.29%   |
| Unknown MMC Card  32GB             | 2         | 0.29%   |
| Unknown HAG2e  16GB                | 2         | 0.29%   |
| Toshiba MQ01ACF032 320GB           | 2         | 0.29%   |
| Toshiba MQ01ABF050 500GB           | 2         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 79        | 106    | 37.98%  |
| WDC                 | 66        | 124    | 31.73%  |
| Toshiba             | 27        | 42     | 12.98%  |
| Hitachi             | 14        | 15     | 6.73%   |
| HGST                | 9         | 12     | 4.33%   |
| Samsung Electronics | 7         | 8      | 3.37%   |
| Fujitsu             | 3         | 3      | 1.44%   |
| SILICONMOTION       | 1         | 1      | 0.48%   |
| MaxDigital          | 1         | 2      | 0.48%   |
| IBM-ESXS            | 1         | 2      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 58        | 78     | 27.49%  |
| Kingston            | 31        | 37     | 14.69%  |
| Crucial             | 20        | 21     | 9.48%   |
| WDC                 | 13        | 16     | 6.16%   |
| SanDisk             | 12        | 15     | 5.69%   |
| A-DATA Technology   | 7         | 8      | 3.32%   |
| Intel               | 6         | 6      | 2.84%   |
| China               | 6         | 6      | 2.84%   |
| Apple               | 6         | 6      | 2.84%   |
| Transcend           | 4         | 5      | 1.9%    |
| Toshiba             | 4         | 5      | 1.9%    |
| PNY                 | 4         | 4      | 1.9%    |
| SPCC                | 3         | 3      | 1.42%   |
| SK Hynix            | 3         | 3      | 1.42%   |
| Seagate             | 3         | 3      | 1.42%   |
| Patriot             | 3         | 3      | 1.42%   |
| LITEONIT            | 3         | 3      | 1.42%   |
| Micron Technology   | 2         | 2      | 0.95%   |
| JMicron             | 2         | 2      | 0.95%   |
| Intenso             | 2         | 2      | 0.95%   |
| ZTC                 | 1         | 1      | 0.47%   |
| Unknown             | 1         | 1      | 0.47%   |
| Union Memory        | 1         | 1      | 0.47%   |
| TrueNAS             | 1         | 1      | 0.47%   |
| Team                | 1         | 1      | 0.47%   |
| T-FORCE             | 1         | 1      | 0.47%   |
| OCZ                 | 1         | 1      | 0.47%   |
| Maxtor              | 1         | 2      | 0.47%   |
| Maximus             | 1         | 1      | 0.47%   |
| LITEON              | 1         | 1      | 0.47%   |
| Lexar               | 1         | 1      | 0.47%   |
| LDLC                | 1         | 1      | 0.47%   |
| KingDian            | 1         | 1      | 0.47%   |
| GOODRAM             | 1         | 1      | 0.47%   |
| Gigabyte Technology | 1         | 1      | 0.47%   |
| DOGFISH             | 1         | 1      | 0.47%   |
| ASUS-PHISON         | 1         | 1      | 0.47%   |
| Apacer              | 1         | 1      | 0.47%   |
| AMD                 | 1         | 1      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 195       | 248    | 34.64%  |
| HDD     | 177       | 315    | 31.44%  |
| NVMe    | 156       | 191    | 27.71%  |
| MMC     | 24        | 35     | 4.26%   |
| Unknown | 11        | 19     | 1.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 289       | 544    | 58.62%  |
| NVMe | 149       | 183    | 30.22%  |
| SAS  | 31        | 46     | 6.29%   |
| MMC  | 24        | 35     | 4.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 204       | 298    | 52.17%  |
| 0.51-1.0   | 110       | 136    | 28.13%  |
| 1.01-2.0   | 42        | 50     | 10.74%  |
| 3.01-4.0   | 15        | 38     | 3.84%   |
| 2.01-3.0   | 10        | 15     | 2.56%   |
| 4.01-10.0  | 7         | 18     | 1.79%   |
| 10.01-20.0 | 3         | 8      | 0.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 89        | 22.14%  |
| 251-500        | 78        | 19.4%   |
| 501-1000       | 52        | 12.94%  |
| 1001-2000      | 43        | 10.7%   |
| More than 3000 | 35        | 8.71%   |
| 1-20           | 33        | 8.21%   |
| 51-100         | 26        | 6.47%   |
| Unknown        | 21        | 5.22%   |
| 21-50          | 14        | 3.48%   |
| 2001-3000      | 11        | 2.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 123       | 30.3%   |
| 21-50          | 52        | 12.81%  |
| 101-250        | 52        | 12.81%  |
| 51-100         | 43        | 10.59%  |
| 251-500        | 37        | 9.11%   |
| 501-1000       | 34        | 8.37%   |
| Unknown        | 21        | 5.17%   |
| 1001-2000      | 20        | 4.93%   |
| More than 3000 | 13        | 3.2%    |
| 2001-3000      | 8         | 1.97%   |
| 0              | 3         | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 2         | 2      | 3.03%   |
| Kingston SV300S37A120G 120GB SSD             | 2         | 2      | 3.03%   |
| WDC WD5003ABYX-18WERA0 500GB                 | 1         | 2      | 1.52%   |
| WDC WD5000AAKX-00U6AA0 500GB                 | 1         | 1      | 1.52%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1      | 1.52%   |
| WDC WD5000AAKS-22V1A0 500GB                  | 1         | 1      | 1.52%   |
| WDC WD5000AAJS-22A8B0 500GB                  | 1         | 1      | 1.52%   |
| WDC WD40EFZX-68AWUN0 4TB                     | 1         | 6      | 1.52%   |
| WDC WD400BB-00DEA0 40GB                      | 1         | 1      | 1.52%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 1.52%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 1      | 1.52%   |
| WDC WD20EARS-00MVWB0 2TB                     | 1         | 1      | 1.52%   |
| WDC WD1600AAJS-00L7A0 160GB                  | 1         | 1      | 1.52%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 1      | 1.52%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 1      | 1.52%   |
| WDC WD10JPVT-75A1YT0 1TB                     | 1         | 1      | 1.52%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 1         | 1      | 1.52%   |
| WDC WD10EZEX-00BN5A0 1TB                     | 1         | 1      | 1.52%   |
| WDC WD1001FALS-75J7B0 1TB                    | 1         | 1      | 1.52%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 1.52%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 1.52%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 1.52%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 1.52%   |
| Toshiba DT01ACA050 500GB                     | 1         | 1      | 1.52%   |
| SK Hynix PC401 NVMe 512GB                    | 1         | 2      | 1.52%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 1.52%   |
| Seagate ST9160310AS 160GB                    | 1         | 1      | 1.52%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 1.52%   |
| Seagate ST3320620A 320GB                     | 1         | 1      | 1.52%   |
| Seagate ST3200827AS 200GB                    | 1         | 1      | 1.52%   |
| Seagate ST32000542AS 2TB                     | 1         | 1      | 1.52%   |
| Seagate ST3160813AS 160GB                    | 1         | 1      | 1.52%   |
| Seagate ST31500341AS 1TB                     | 1         | 1      | 1.52%   |
| Seagate ST3120827AS 120GB                    | 1         | 1      | 1.52%   |
| Seagate ST31000333AS 1TB                     | 1         | 1      | 1.52%   |
| Seagate ST3000DM001-9YN166 3TB               | 1         | 1      | 1.52%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 1.52%   |
| Seagate ST2000LX001-1RG174 2TB               | 1         | 1      | 1.52%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 1.52%   |
| Seagate ST1000LX015-1U7172 1TB               | 1         | 1      | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 1.52%   |
| Seagate ST1000DM003-9YN162 1TB               | 1         | 1      | 1.52%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 1.52%   |
| SanDisk SSD PLUS 120 GB                      | 1         | 1      | 1.52%   |
| Samsung Electronics SSD 970 EVO 250GB        | 1         | 1      | 1.52%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 1.52%   |
| Samsung Electronics HD161GJ 160GB            | 1         | 1      | 1.52%   |
| PNY SSD2SC240G3LC709B121-460P 240GB          | 1         | 1      | 1.52%   |
| LITEONIT LMT-64M6M-HP 64GB SSD               | 1         | 1      | 1.52%   |
| Kingston SE100S3100G 100GB SSD               | 1         | 1      | 1.52%   |
| KingDian S280 240GB                          | 1         | 1      | 1.52%   |
| Intel SSDSC2KW120H6 120GB                    | 1         | 1      | 1.52%   |
| Intel SSDSC2BF180A4H 180GB                   | 1         | 1      | 1.52%   |
| Intel SSDPEKKW010T7 1TB                      | 1         | 2      | 1.52%   |
| Hitachi HUA722020ALA331 2TB                  | 1         | 1      | 1.52%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 1.52%   |
| Hitachi HTS543212L9A300 120GB                | 1         | 1      | 1.52%   |
| Hitachi HTS542512K9SA00 120GB                | 1         | 1      | 1.52%   |
| Hitachi HDS722525VLAT80 250GB                | 1         | 1      | 1.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 29.69%  |
| WDC                 | 17        | 24     | 26.56%  |
| Toshiba             | 5         | 5      | 7.81%   |
| Hitachi             | 5         | 5      | 7.81%   |
| Samsung Electronics | 3         | 4      | 4.69%   |
| Kingston            | 3         | 3      | 4.69%   |
| Intel               | 3         | 4      | 4.69%   |
| A-DATA Technology   | 3         | 4      | 4.69%   |
| SK Hynix            | 1         | 2      | 1.56%   |
| SanDisk             | 1         | 1      | 1.56%   |
| PNY                 | 1         | 1      | 1.56%   |
| LITEONIT            | 1         | 1      | 1.56%   |
| KingDian            | 1         | 1      | 1.56%   |
| HGST                | 1         | 1      | 1.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 39.58%  |
| WDC                 | 17        | 24     | 35.42%  |
| Toshiba             | 5         | 5      | 10.42%  |
| Hitachi             | 5         | 5      | 10.42%  |
| Samsung Electronics | 1         | 1      | 2.08%   |
| HGST                | 1         | 1      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 57     | 74.6%   |
| SSD  | 13        | 15     | 20.63%  |
| NVMe | 3         | 5      | 4.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1         | 1      | 50%     |
| Seagate ST3500830AS 500GB        | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 329       | 588    | 70.3%   |
| Detected | 77        | 141    | 16.45%  |
| Malfunc  | 60        | 77     | 12.82%  |
| Failed   | 2         | 2      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 240       | 47.9%   |
| AMD                          | 83        | 16.57%  |
| Samsung Electronics          | 55        | 10.98%  |
| Sandisk                      | 26        | 5.19%   |
| SK Hynix                     | 10        | 2%      |
| Phison Electronics           | 10        | 2%      |
| Micron/Crucial Technology    | 10        | 2%      |
| Kingston Technology Company  | 8         | 1.6%    |
| Toshiba America Info Systems | 7         | 1.4%    |
| ASMedia Technology           | 7         | 1.4%    |
| KIOXIA                       | 6         | 1.2%    |
| Marvell Technology Group     | 5         | 1%      |
| ADATA Technology             | 5         | 1%      |
| Nvidia                       | 4         | 0.8%    |
| JMicron Technology           | 4         | 0.8%    |
| Broadcom / LSI               | 4         | 0.8%    |
| Micron Technology            | 3         | 0.6%    |
| Union Memory (Shenzhen)      | 2         | 0.4%    |
| Lenovo                       | 2         | 0.4%    |
| Apple                        | 2         | 0.4%    |
| VIA Technologies             | 1         | 0.2%    |
| Silicon Motion               | 1         | 0.2%    |
| Silicon Image                | 1         | 0.2%    |
| Seagate Technology           | 1         | 0.2%    |
| OCZ Technology Group         | 1         | 0.2%    |
| LSI Logic / Symbios Logic    | 1         | 0.2%    |
| Lite-On Technology           | 1         | 0.2%    |
| Adaptec                      | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 58        | 10%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 33        | 5.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 23        | 3.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 21        | 3.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 17        | 2.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16        | 2.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 16        | 2.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13        | 2.24%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 11        | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10        | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10        | 1.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9         | 1.55%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 9         | 1.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 8         | 1.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 1.38%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 1.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8         | 1.38%   |
| Phison E12 NVMe Controller                                                              | 7         | 1.21%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 7         | 1.21%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 6         | 1.03%   |
| Samsung NVMe Controller                                                                 | 6         | 1.03%   |
| KIOXIA Non-Volatile memory controller                                                   | 6         | 1.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 1.03%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 5         | 0.86%   |
| Samsung Electronics SATA controller                                                     | 5         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5         | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 0.86%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5         | 0.86%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 0.69%   |
| Intel SSD 660P Series                                                                   | 4         | 0.69%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 4         | 0.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 0.69%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4         | 0.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4         | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4         | 0.69%   |
| SK Hynix NVMe SSD Controller                                                            | 3         | 0.52%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.52%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 0.52%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 0.52%   |
| Micron Non-Volatile memory controller                                                   | 3         | 0.52%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 0.52%   |
| Intel SSD 600P Series                                                                   | 3         | 0.52%   |
| Intel NVMe Optane Memory Series                                                         | 3         | 0.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.52%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3         | 0.52%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 3         | 0.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.52%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 0.52%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 281       | 54.67%  |
| NVMe | 149       | 28.99%  |
| IDE  | 41        | 7.98%   |
| RAID | 37        | 7.2%    |
| SAS  | 6         | 1.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 294       | 73.5%   |
| AMD    | 99        | 24.75%  |
| ARM    | 7         | 1.75%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 9         | 2.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 2%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 2%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 2%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 1.5%    |
| Intel Core i5-5250U CPU @ 1.60GHz             | 6         | 1.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.25%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.25%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 1.25%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 1.25%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1%      |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 1%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1%      |
| ARM Processor                                 | 4         | 1%      |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 1%      |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 3         | 0.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.75%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 3         | 0.75%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.75%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.75%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 3         | 0.75%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 3         | 0.75%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.75%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz           | 2         | 0.5%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 2         | 0.5%    |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.5%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.5%    |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 2         | 0.5%    |
| Intel Core i7-3537U CPU @ 2.00GHz             | 2         | 0.5%    |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.5%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.5%    |
| Intel Core i5-7500 CPU @ 3.40GHz              | 2         | 0.5%    |
| Intel Core i5-6600 CPU @ 3.30GHz              | 2         | 0.5%    |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 0.5%    |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.5%    |
| Intel Core i5-2500K CPU @ 3.30GHz             | 2         | 0.5%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.5%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.5%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.5%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.5%    |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 0.5%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.5%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 0.5%    |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 2         | 0.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 0.5%    |
| Intel Celeron M processor 900MHz              | 2         | 0.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 107       | 26.75%  |
| Intel Core i7          | 79        | 19.75%  |
| AMD Ryzen 5            | 29        | 7.25%   |
| Other                  | 23        | 5.75%   |
| AMD Ryzen 7            | 19        | 4.75%   |
| Intel Celeron          | 18        | 4.5%    |
| Intel Core i3          | 16        | 4%      |
| Intel Xeon             | 15        | 3.75%   |
| Intel Core 2 Duo       | 14        | 3.5%    |
| Intel Pentium          | 9         | 2.25%   |
| AMD Ryzen 7 PRO        | 7         | 1.75%   |
| AMD FX                 | 6         | 1.5%    |
| AMD Ryzen 9            | 5         | 1.25%   |
| AMD Ryzen 3            | 5         | 1.25%   |
| Intel Atom             | 4         | 1%      |
| AMD Ryzen Threadripper | 4         | 1%      |
| AMD Phenom II X4       | 4         | 1%      |
| Intel Core 2 Quad      | 3         | 0.75%   |
| Intel Pentium M        | 2         | 0.5%    |
| Intel Pentium Gold     | 2         | 0.5%    |
| Intel Core 2           | 2         | 0.5%    |
| Intel Celeron M        | 2         | 0.5%    |
| AMD Athlon X4          | 2         | 0.5%    |
| AMD A8                 | 2         | 0.5%    |
| AMD A10                | 2         | 0.5%    |
| Intel Xeon Silver      | 1         | 0.25%   |
| Intel Pentium Dual     | 1         | 0.25%   |
| Intel Pentium 4        | 1         | 0.25%   |
| Intel Core m7          | 1         | 0.25%   |
| Intel Core i9          | 1         | 0.25%   |
| ARM BCM                | 1         | 0.25%   |
| ARM Allwinner          | 1         | 0.25%   |
| ARM AArch64            | 1         | 0.25%   |
| AMD Sempron            | 1         | 0.25%   |
| AMD PRO A8             | 1         | 0.25%   |
| AMD Phenom II X3       | 1         | 0.25%   |
| AMD GX                 | 1         | 0.25%   |
| AMD C-30               | 1         | 0.25%   |
| AMD Athlon XP          | 1         | 0.25%   |
| AMD Athlon II X2       | 1         | 0.25%   |
| AMD Athlon II Neo      | 1         | 0.25%   |
| AMD Athlon Dual Core   | 1         | 0.25%   |
| AMD A6                 | 1         | 0.25%   |
| AMD A12                | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 152       | 38%     |
| 2      | 139       | 34.75%  |
| 6      | 45        | 11.25%  |
| 8      | 33        | 8.25%   |
| 1      | 15        | 3.75%   |
| 16     | 6         | 1.5%    |
| 12     | 6         | 1.5%    |
| 44     | 1         | 0.25%   |
| 32     | 1         | 0.25%   |
| 28     | 1         | 0.25%   |
| 3      | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 392       | 98%     |
| 2      | 8         | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 283       | 70.75%  |
| 1      | 117       | 29.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 388       | 97%     |
| 32-bit         | 8         | 2%      |
| 64-bit         | 2         | 0.5%    |
| Unknown        | 2         | 0.5%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 18.11%  |
| 0x306a9    | 28        | 6.95%   |
| 0x206a7    | 19        | 4.71%   |
| 0x306c3    | 15        | 3.72%   |
| 0x306d4    | 14        | 3.47%   |
| 0x08701021 | 14        | 3.47%   |
| 0x806c1    | 13        | 3.23%   |
| 0x906ea    | 12        | 2.98%   |
| 0x806ec    | 12        | 2.98%   |
| 0x806e9    | 11        | 2.73%   |
| 0x806ea    | 10        | 2.48%   |
| 0x406e3    | 9         | 2.23%   |
| 0x906e9    | 8         | 1.99%   |
| 0x706e5    | 8         | 1.99%   |
| 0x1067a    | 8         | 1.99%   |
| 0x08600106 | 8         | 1.99%   |
| 0x08108109 | 7         | 1.74%   |
| 0xa0652    | 6         | 1.49%   |
| 0x506e3    | 6         | 1.49%   |
| 0x206d7    | 6         | 1.49%   |
| 0x06003106 | 6         | 1.49%   |
| 0x806eb    | 5         | 1.24%   |
| 0x506c9    | 5         | 1.24%   |
| 0x40651    | 5         | 1.24%   |
| 0x306f2    | 4         | 0.99%   |
| 0x0a201009 | 4         | 0.99%   |
| 0x0800820d | 4         | 0.99%   |
| 0x30678    | 3         | 0.74%   |
| 0x20655    | 3         | 0.74%   |
| 0x08001138 | 3         | 0.74%   |
| 0x0600611a | 3         | 0.74%   |
| 0x06000852 | 3         | 0.74%   |
| 0x010000c8 | 3         | 0.74%   |
| 0x010000b6 | 3         | 0.74%   |
| 0xa0660    | 2         | 0.5%    |
| 0xa0655    | 2         | 0.5%    |
| 0x706a8    | 2         | 0.5%    |
| 0x6fd      | 2         | 0.5%    |
| 0x6fb      | 2         | 0.5%    |
| 0x6f6      | 2         | 0.5%    |
| 0x6d8      | 2         | 0.5%    |
| 0x695      | 2         | 0.5%    |
| 0x406c4    | 2         | 0.5%    |
| 0x406c3    | 2         | 0.5%    |
| 0x106c2    | 2         | 0.5%    |
| 0x0a201016 | 2         | 0.5%    |
| 0x08701013 | 2         | 0.5%    |
| 0x08108102 | 2         | 0.5%    |
| 0xf41      | 1         | 0.25%   |
| 0xf29      | 1         | 0.25%   |
| 0xa0671    | 1         | 0.25%   |
| 0xa0653    | 1         | 0.25%   |
| 0x906ed    | 1         | 0.25%   |
| 0x906ec    | 1         | 0.25%   |
| 0x906eb    | 1         | 0.25%   |
| 0x706a1    | 1         | 0.25%   |
| 0x6fa      | 1         | 0.25%   |
| 0x50657    | 1         | 0.25%   |
| 0x50654    | 1         | 0.25%   |
| 0x406f1    | 1         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 75        | 18.75%  |
| Zen 2         | 34        | 8.5%    |
| IvyBridge     | 34        | 8.5%    |
| Haswell       | 32        | 8%      |
| SandyBridge   | 25        | 6.25%   |
| Skylake       | 23        | 5.75%   |
| Zen+          | 19        | 4.75%   |
| TigerLake     | 15        | 3.75%   |
| Broadwell     | 15        | 3.75%   |
| CometLake     | 12        | 3%      |
| Penryn        | 11        | 2.75%   |
| Core          | 10        | 2.5%    |
| Zen 3         | 9         | 2.25%   |
| Unknown       | 9         | 2.25%   |
| Silvermont    | 8         | 2%      |
| K10           | 8         | 2%      |
| IceLake       | 8         | 2%      |
| Westmere      | 7         | 1.75%   |
| Steamroller   | 7         | 1.75%   |
| Zen           | 6         | 1.5%    |
| Goldmont      | 5         | 1.25%   |
| Piledriver    | 4         | 1%      |
| P6            | 4         | 1%      |
| Excavator     | 4         | 1%      |
| Goldmont plus | 3         | 0.75%   |
| NetBurst      | 2         | 0.5%    |
| Nehalem       | 2         | 0.5%    |
| Bulldozer     | 2         | 0.5%    |
| Bonnell       | 2         | 0.5%    |
| K8 Hammer     | 1         | 0.25%   |
| K6            | 1         | 0.25%   |
| K10 Llano     | 1         | 0.25%   |
| Jaguar        | 1         | 0.25%   |
| Bobcat        | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 229       | 50.44%  |
| Nvidia                     | 114       | 25.11%  |
| AMD                        | 100       | 22.03%  |
| ASPEED Technology          | 7         | 1.54%   |
| Matrox Electronics Systems | 4         | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 4.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 3.44%   |
| Intel UHD Graphics 620                                                                   | 15        | 3.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 15        | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 3.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 2.58%   |
| AMD Renoir                                                                               | 12        | 2.58%   |
| AMD Picasso                                                                              | 11        | 2.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.15%   |
| Intel HD Graphics 620                                                                    | 10        | 2.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.72%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.51%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 7         | 1.51%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7         | 1.51%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 1.29%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6         | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.29%   |
| Intel HD Graphics 6000                                                                   | 6         | 1.29%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.29%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.08%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.86%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.86%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 4         | 0.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.86%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.86%   |
| Intel HD Graphics 630                                                                    | 4         | 0.86%   |
| Intel HD Graphics 530                                                                    | 4         | 0.86%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.86%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.65%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 0.65%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.65%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.43%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.43%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.43%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.43%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.43%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.43%   |
| Nvidia GK104 [GeForce GTX 670]                                                           | 2         | 0.43%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.43%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.43%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 2         | 0.43%   |
| Nvidia G98 [Quadro NVS 295]                                                              | 2         | 0.43%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.43%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.43%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 173       | 43.03%  |
| 1 x AMD         | 81        | 20.15%  |
| 1 x Nvidia      | 68        | 16.92%  |
| Intel + Nvidia  | 43        | 10.7%   |
| Intel + AMD     | 11        | 2.74%   |
| Other           | 8         | 1.99%   |
| 1 x ASPEED      | 6         | 1.49%   |
| 2 x AMD         | 4         | 1%      |
| 1 x Matrox      | 3         | 0.75%   |
| AMD + Nvidia    | 3         | 0.75%   |
| Nvidia + Matrox | 1         | 0.25%   |
| AMD + ASPEED    | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 344       | 85.79%  |
| Proprietary | 43        | 10.72%  |
| Unknown     | 14        | 3.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 253       | 62.62%  |
| 1.01-2.0   | 34        | 8.42%   |
| 0.01-0.5   | 34        | 8.42%   |
| 0.51-1.0   | 25        | 6.19%   |
| 7.01-8.0   | 23        | 5.69%   |
| 3.01-4.0   | 22        | 5.45%   |
| 5.01-6.0   | 7         | 1.73%   |
| 2.01-3.0   | 2         | 0.5%    |
| 8.01-16.0  | 2         | 0.5%    |
| 24.01-32.0 | 1         | 0.25%   |
| 16.01-24.0 | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 49        | 11.01%  |
| Samsung Electronics     | 46        | 10.34%  |
| BOE                     | 40        | 8.99%   |
| Chimei Innolux          | 39        | 8.76%   |
| LG Display              | 36        | 8.09%   |
| Dell                    | 31        | 6.97%   |
| Goldstar                | 27        | 6.07%   |
| Acer                    | 18        | 4.04%   |
| Ancor Communications    | 17        | 3.82%   |
| Hewlett-Packard         | 14        | 3.15%   |
| BenQ                    | 14        | 3.15%   |
| Apple                   | 13        | 2.92%   |
| Sharp                   | 10        | 2.25%   |
| Philips                 | 10        | 2.25%   |
| AOC                     | 10        | 2.25%   |
| Lenovo                  | 9         | 2.02%   |
| NEC Computers           | 5         | 1.12%   |
| ASUSTek Computer        | 5         | 1.12%   |
| ViewSonic               | 4         | 0.9%    |
| InfoVision              | 4         | 0.9%    |
| Unknown                 | 3         | 0.67%   |
| Iiyama                  | 3         | 0.67%   |
| Vestel Elektronik       | 2         | 0.45%   |
| Sony                    | 2         | 0.45%   |
| LG Electronics          | 2         | 0.45%   |
| HannStar                | 2         | 0.45%   |
| Eizo                    | 2         | 0.45%   |
| CPT                     | 2         | 0.45%   |
| Chi Mei Optoelectronics | 2         | 0.45%   |
| ___                     | 1         | 0.22%   |
| Vizio                   | 1         | 0.22%   |
| TEO                     | 1         | 0.22%   |
| Prestigio               | 1         | 0.22%   |
| PANDA                   | 1         | 0.22%   |
| ODH                     | 1         | 0.22%   |
| NCS                     | 1         | 0.22%   |
| MSI                     | 1         | 0.22%   |
| MIT                     | 1         | 0.22%   |
| Mi                      | 1         | 0.22%   |
| Medion                  | 1         | 0.22%   |
| LPL                     | 1         | 0.22%   |
| JXG                     | 1         | 0.22%   |
| JVC                     | 1         | 0.22%   |
| JRY                     | 1         | 0.22%   |
| IOD                     | 1         | 0.22%   |
| INFOTRONIC              | 1         | 0.22%   |
| Idek Iiyama             | 1         | 0.22%   |
| HKC                     | 1         | 0.22%   |
| Hitachi                 | 1         | 0.22%   |
| CSO                     | 1         | 0.22%   |
| COBY                    | 1         | 0.22%   |
| CMN                     | 1         | 0.22%   |
| Belinea                 | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 4         | 0.88%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 4         | 0.88%   |
| NEC Computers LCD1550V NEC65C6 1024x768 304x228mm 15.0-inch            | 3         | 0.66%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch            | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 0.66%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                   | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch          | 3         | 0.66%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3         | 0.66%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 3         | 0.66%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 2         | 0.44%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 2         | 0.44%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 0.44%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                | 2         | 0.44%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                | 2         | 0.44%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 1050x590mm 47.4-inch | 2         | 0.44%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2         | 0.44%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 2         | 0.44%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                | 2         | 0.44%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 2         | 0.44%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2         | 0.44%   |
| Hewlett-Packard Z23i HWP308F 1920x1080 509x286mm 23.0-inch             | 2         | 0.44%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch           | 2         | 0.44%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2         | 0.44%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 2         | 0.44%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2         | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.44%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 2         | 0.44%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.44%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                      | 2         | 0.44%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 0.44%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.44%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                  | 2         | 0.44%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                  | 2         | 0.44%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                   | 2         | 0.44%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                  | 2         | 0.44%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                   | 2         | 0.44%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO5C2D 1920x1080 293x165mm 13.2-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch          | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 2         | 0.44%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 2         | 0.44%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch  | 2         | 0.44%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 185       | 42.82%  |
| 1366x768 (WXGA)    | 66        | 15.28%  |
| 3840x2160 (4K)     | 31        | 7.18%   |
| 2560x1440 (QHD)    | 27        | 6.25%   |
| 1600x900 (HD+)     | 20        | 4.63%   |
| 1920x1200 (WUXGA)  | 15        | 3.47%   |
| 1280x1024 (SXGA)   | 15        | 3.47%   |
| 1680x1050 (WSXGA+) | 13        | 3.01%   |
| 1440x900 (WXGA+)   | 12        | 2.78%   |
| 1280x800 (WXGA)    | 9         | 2.08%   |
| 1024x768 (XGA)     | 7         | 1.62%   |
| Unknown            | 5         | 1.16%   |
| 2560x1080          | 4         | 0.93%   |
| 2560x1600          | 3         | 0.69%   |
| 1600x1200          | 3         | 0.69%   |
| 3440x1440          | 2         | 0.46%   |
| 2288x1287          | 2         | 0.46%   |
| 1024x600           | 2         | 0.46%   |
| 7680x4320          | 1         | 0.23%   |
| 5760x1080          | 1         | 0.23%   |
| 4480x1440          | 1         | 0.23%   |
| 3840x2400          | 1         | 0.23%   |
| 3840x1080          | 1         | 0.23%   |
| 3360x1080          | 1         | 0.23%   |
| 2880x1800          | 1         | 0.23%   |
| 2256x1504          | 1         | 0.23%   |
| 2160x1440          | 1         | 0.23%   |
| 1920x540           | 1         | 0.23%   |
| 1792x768           | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 78        | 17.65%  |
| 13      | 61        | 13.8%   |
| 24      | 41        | 9.28%   |
| 14      | 41        | 9.28%   |
| 27      | 33        | 7.47%   |
| 23      | 32        | 7.24%   |
| 17      | 24        | 5.43%   |
| 21      | 21        | 4.75%   |
| 12      | 14        | 3.17%   |
| Unknown | 14        | 3.17%   |
| 11      | 12        | 2.71%   |
| 31      | 11        | 2.49%   |
| 19      | 9         | 2.04%   |
| 18      | 8         | 1.81%   |
| 22      | 6         | 1.36%   |
| 20      | 6         | 1.36%   |
| 34      | 5         | 1.13%   |
| 84      | 3         | 0.68%   |
| 28      | 3         | 0.68%   |
| 25      | 3         | 0.68%   |
| 142     | 2         | 0.45%   |
| 72      | 2         | 0.45%   |
| 47      | 2         | 0.45%   |
| 29      | 2         | 0.45%   |
| 10      | 2         | 0.45%   |
| 55      | 1         | 0.23%   |
| 48      | 1         | 0.23%   |
| 40      | 1         | 0.23%   |
| 38      | 1         | 0.23%   |
| 33      | 1         | 0.23%   |
| 32      | 1         | 0.23%   |
| 16      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 155       | 35.71%  |
| 501-600        | 94        | 21.66%  |
| 201-300        | 59        | 13.59%  |
| 401-500        | 47        | 10.83%  |
| 351-400        | 23        | 5.3%    |
| 601-700        | 22        | 5.07%   |
| Unknown        | 14        | 3.23%   |
| 701-800        | 7         | 1.61%   |
| 1501-2000      | 5         | 1.15%   |
| 1001-1500      | 4         | 0.92%   |
| More than 2000 | 2         | 0.46%   |
| 801-900        | 2         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 300       | 74.07%  |
| 16/10   | 48        | 11.85%  |
| 5/4     | 13        | 3.21%   |
| 4/3     | 13        | 3.21%   |
| Unknown | 13        | 3.21%   |
| 3/2     | 7         | 1.73%   |
| 21/9    | 7         | 1.73%   |
| 1.00    | 2         | 0.49%   |
| 6/5     | 1         | 0.25%   |
| 1.96    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 17.85%  |
| 81-90          | 77        | 17.62%  |
| 201-250        | 76        | 17.39%  |
| 301-350        | 33        | 7.55%   |
| 71-80          | 26        | 5.95%   |
| 351-500        | 22        | 5.03%   |
| 151-200        | 22        | 5.03%   |
| 251-300        | 18        | 4.12%   |
| 141-150        | 14        | 3.2%    |
| 121-130        | 14        | 3.2%    |
| Unknown        | 14        | 3.2%    |
| 61-70          | 13        | 2.97%   |
| 51-60          | 12        | 2.75%   |
| More than 1000 | 8         | 1.83%   |
| 501-1000       | 5         | 1.14%   |
| 131-140        | 3         | 0.69%   |
| 41-50          | 2         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 143       | 33.89%  |
| 51-100        | 139       | 32.94%  |
| 101-120       | 81        | 19.19%  |
| 161-240       | 29        | 6.87%   |
| Unknown       | 14        | 3.32%   |
| More than 240 | 8         | 1.9%    |
| 1-50          | 8         | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 302       | 75.12%  |
| 2     | 68        | 16.92%  |
| 0     | 22        | 5.47%   |
| 3     | 9         | 2.24%   |
| 4     | 1         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 222       | 40.29%  |
| Realtek Semiconductor             | 188       | 34.12%  |
| Qualcomm Atheros                  | 56        | 10.16%  |
| Broadcom                          | 26        | 4.72%   |
| Broadcom Limited                  | 11        | 2%      |
| Marvell Technology Group          | 5         | 0.91%   |
| Nvidia                            | 4         | 0.73%   |
| Ralink Technology                 | 3         | 0.54%   |
| Ralink                            | 3         | 0.54%   |
| Ericsson Business Mobile Networks | 3         | 0.54%   |
| Xiaomi                            | 2         | 0.36%   |
| Sierra Wireless                   | 2         | 0.36%   |
| Microsoft                         | 2         | 0.36%   |
| Microchip Technology              | 2         | 0.36%   |
| Edimax Technology                 | 2         | 0.36%   |
| DisplayLink                       | 2         | 0.36%   |
| Dell                              | 2         | 0.36%   |
| D-Link                            | 2         | 0.36%   |
| Cypress Semiconductor             | 2         | 0.36%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.18%   |
| TP-Link                           | 1         | 0.18%   |
| Qualcomm                          | 1         | 0.18%   |
| Mellanox Technologies             | 1         | 0.18%   |
| MEDIATEK                          | 1         | 0.18%   |
| IBM                               | 1         | 0.18%   |
| Huawei Technologies               | 1         | 0.18%   |
| Hewlett-Packard                   | 1         | 0.18%   |
| Fibocom                           | 1         | 0.18%   |
| Attansic Technology               | 1         | 0.18%   |
| Aquantia                          | 1         | 0.18%   |
| American Megatrends               | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 132       | 19.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26        | 3.91%   |
| Intel Wi-Fi 6 AX200                                               | 24        | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 2.11%   |
| Intel Wireless 8265 / 8275                                        | 14        | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 1.95%   |
| Intel Wireless 8260                                               | 13        | 1.95%   |
| Intel I211 Gigabit Network Connection                             | 13        | 1.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.5%    |
| Intel Ethernet Connection (2) I219-V                              | 10        | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.35%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 1.35%   |
| Intel Wireless 7260                                               | 8         | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.05%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 0.9%    |
| Intel Wireless 3165                                               | 6         | 0.9%    |
| Intel I210 Gigabit Network Connection                             | 6         | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.9%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 6         | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.75%   |
| Intel Wireless 7265                                               | 5         | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.75%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.75%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.6%    |
| Intel Wireless 3160                                               | 4         | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.6%    |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.6%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.6%    |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 3         | 0.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.45%   |
| Intel Wireless-AC 9260                                            | 3         | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.45%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.45%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.45%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.3%    |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A               | 2         | 0.3%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2         | 0.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 165       | 58.1%   |
| Qualcomm Atheros                  | 43        | 15.14%  |
| Realtek Semiconductor             | 36        | 12.68%  |
| Broadcom                          | 13        | 4.58%   |
| Broadcom Limited                  | 9         | 3.17%   |
| Ralink Technology                 | 3         | 1.06%   |
| Ralink                            | 3         | 1.06%   |
| Sierra Wireless                   | 2         | 0.7%    |
| Microsoft                         | 2         | 0.7%    |
| Edimax Technology                 | 2         | 0.7%    |
| TP-Link                           | 1         | 0.35%   |
| Qualcomm                          | 1         | 0.35%   |
| MEDIATEK                          | 1         | 0.35%   |
| Fibocom                           | 1         | 0.35%   |
| Ericsson Business Mobile Networks | 1         | 0.35%   |
| D-Link                            | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 24        | 8.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 4.91%   |
| Intel Wireless 8265 / 8275                                              | 14        | 4.91%   |
| Intel Wireless 8260                                                     | 13        | 4.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 3.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 3.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.16%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 3.16%   |
| Intel Wireless 7260                                                     | 8         | 2.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 2.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.11%   |
| Intel Wireless 3165                                                     | 6         | 2.11%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 2.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 2.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.11%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 6         | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.75%   |
| Intel Wireless 7265                                                     | 5         | 1.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 1.75%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.75%   |
| Intel Wireless 3160                                                     | 4         | 1.4%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.4%    |
| Intel Centrino Wireless-N 2230                                          | 4         | 1.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.05%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.05%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.05%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 2         | 0.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.7%    |
| Microsoft Xbox 360 Wireless Adapter                                     | 2         | 0.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.7%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.7%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 0.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.7%    |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.7%    |
| TP-Link Archer T4U ver.3                                                | 1         | 0.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.35%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.35%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.35%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.35%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.35%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.35%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.35%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.35%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.35%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.35%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1         | 0.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.35%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.35%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]             | 1         | 0.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 170       | 47.22%  |
| Intel                    | 126       | 35%     |
| Qualcomm Atheros         | 20        | 5.56%   |
| Broadcom                 | 17        | 4.72%   |
| Marvell Technology Group | 5         | 1.39%   |
| Nvidia                   | 4         | 1.11%   |
| Broadcom Limited         | 3         | 0.83%   |
| Xiaomi                   | 2         | 0.56%   |
| Microchip Technology     | 2         | 0.56%   |
| DisplayLink              | 2         | 0.56%   |
| Cypress Semiconductor    | 2         | 0.56%   |
| Mellanox Technologies    | 1         | 0.28%   |
| IBM                      | 1         | 0.28%   |
| Huawei Technologies      | 1         | 0.28%   |
| D-Link                   | 1         | 0.28%   |
| Attansic Technology      | 1         | 0.28%   |
| Aquantia                 | 1         | 0.28%   |
| American Megatrends      | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 132       | 35.48%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26        | 6.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 3.49%   |
| Intel I211 Gigabit Network Connection                             | 13        | 3.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 2.69%   |
| Intel Ethernet Connection (2) I219-V                              | 10        | 2.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.88%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.88%   |
| Intel I210 Gigabit Network Connection                             | 6         | 1.61%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.34%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 1.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.08%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.81%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.81%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.81%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.54%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.54%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.54%   |
| Intel Ethernet Controller 10G X550T                               | 2         | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.54%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.54%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.54%   |
| Cypress K38231_03                                                 | 2         | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.54%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 0.54%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.54%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.27%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.27%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.27%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.27%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.27%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.27%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.27%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 0.27%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.27%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.27%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.27%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.27%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.27%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.27%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 338       | 54.43%  |
| WiFi     | 275       | 44.28%  |
| Modem    | 8         | 1.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 267       | 52.05%  |
| WiFi     | 245       | 47.76%  |
| Modem    | 1         | 0.19%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 209       | 52.25%  |
| 1     | 161       | 40.25%  |
| 3     | 14        | 3.5%    |
| 0     | 9         | 2.25%   |
| 4     | 4         | 1%      |
| 13    | 1         | 0.25%   |
| 6     | 1         | 0.25%   |
| 5     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 317       | 79.05%  |
| Yes  | 84        | 20.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 126       | 55.02%  |
| Qualcomm Atheros Communications | 20        | 8.73%   |
| Realtek Semiconductor           | 17        | 7.42%   |
| Broadcom                        | 14        | 6.11%   |
| Cambridge Silicon Radio         | 11        | 4.8%    |
| Apple                           | 11        | 4.8%    |
| Lite-On Technology              | 8         | 3.49%   |
| IMC Networks                    | 4         | 1.75%   |
| ASUSTek Computer                | 4         | 1.75%   |
| Realtek                         | 3         | 1.31%   |
| Foxconn / Hon Hai               | 3         | 1.31%   |
| Toshiba                         | 2         | 0.87%   |
| Hewlett-Packard                 | 2         | 0.87%   |
| Dell                            | 2         | 0.87%   |
| Taiyo Yuden                     | 1         | 0.44%   |
| Ralink                          | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 54        | 23.58%  |
| Intel Bluetooth wireless interface                  | 24        | 10.48%  |
| Intel AX200 Bluetooth                               | 24        | 10.48%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 6.99%   |
| Realtek Bluetooth Radio                             | 14        | 6.11%   |
| Qualcomm Atheros  Bluetooth Device                  | 13        | 5.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 4.8%    |
| Apple Bluetooth USB Host Controller                 | 6         | 2.62%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 2.18%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.75%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.75%   |
| Realtek Bluetooth Radio                             | 3         | 1.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.31%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.31%   |
| Apple Bluetooth Host Controller                     | 3         | 1.31%   |
| Toshiba Bluetooth Device                            | 2         | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.87%   |
| Lite-On Bluetooth Device                            | 2         | 0.87%   |
| IMC Networks Bluetooth Radio                        | 2         | 0.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.87%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.87%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.44%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.44%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.44%   |
| Realtek CSR BS8510                                  | 1         | 0.44%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.44%   |
| Lite-On Wireless_Device                             | 1         | 0.44%   |
| Lite-On BCM43142A0                                  | 1         | 0.44%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.44%   |
| IMC Networks Bluetooth Device                       | 1         | 0.44%   |
| IMC Networks Bluetooth                              | 1         | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.44%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.44%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.44%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.44%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.44%   |
| Broadcom Bluetooth 3.0 Device                       | 1         | 0.44%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.44%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.44%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 0.44%   |
| ASUS Bluetooth Radio                                | 1         | 0.44%   |
| ASUS Bluetooth Adapter                              | 1         | 0.44%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.44%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 277       | 51.39%  |
| AMD                        | 112       | 20.78%  |
| Nvidia                     | 85        | 15.77%  |
| C-Media Electronics        | 14        | 2.6%    |
| Generalplus Technology     | 6         | 1.11%   |
| Logitech                   | 5         | 0.93%   |
| GYROCOM C&C                | 4         | 0.74%   |
| Creative Labs              | 4         | 0.74%   |
| Texas Instruments          | 3         | 0.56%   |
| Plantronics                | 3         | 0.56%   |
| GN Netcom                  | 3         | 0.56%   |
| Samson Technologies        | 2         | 0.37%   |
| BEHRINGER International    | 2         | 0.37%   |
| XMOS                       | 1         | 0.19%   |
| VIA Technologies           | 1         | 0.19%   |
| TEAC                       | 1         | 0.19%   |
| SteelSeries ApS            | 1         | 0.19%   |
| RODE Microphones           | 1         | 0.19%   |
| ROCCAT                     | 1         | 0.19%   |
| Razer USA                  | 1         | 0.19%   |
| PreSonus Audio Electronics | 1         | 0.19%   |
| JMTek                      | 1         | 0.19%   |
| Hewlett-Packard            | 1         | 0.19%   |
| Hangzhou Worlde            | 1         | 0.19%   |
| Dell                       | 1         | 0.19%   |
| Creative Technology        | 1         | 0.19%   |
| Blue Microphones           | 1         | 0.19%   |
| AXELVOX                    | 1         | 0.19%   |
| AVID Technology            | 1         | 0.19%   |
| Audioengine                | 1         | 0.19%   |
| ASUSTek Computer           | 1         | 0.19%   |
| Alesis                     | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 38        | 5.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 5.04%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 28        | 4.41%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 27        | 4.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 2.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 2.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 15        | 2.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 2.2%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14        | 2.2%    |
| Intel Broadwell-U Audio Controller                                                                | 14        | 2.2%    |
| Intel 200 Series PCH HD Audio                                                                     | 14        | 2.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 2.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 2.05%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 1.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 11        | 1.73%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 1.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.42%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.42%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 8         | 1.26%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.26%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.1%    |
| AMD Navi 10 HDMI Audio                                                                            | 7         | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 0.94%   |
| Generalplus Technology USB Audio Device                                                           | 6         | 0.94%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 0.79%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 5         | 0.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 5         | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 0.63%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 4         | 0.63%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 0.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.47%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.47%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.47%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.47%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 0.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.47%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.47%   |
| GYROCOM C&C Fiio E10                                                                              | 3         | 0.47%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 3         | 0.47%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.31%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.31%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.31%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.31%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 82        | 19.39%  |
| Samsung Electronics | 82        | 19.39%  |
| Kingston            | 57        | 13.48%  |
| Unknown             | 42        | 9.93%   |
| Crucial             | 34        | 8.04%   |
| Micron Technology   | 31        | 7.33%   |
| Corsair             | 30        | 7.09%   |
| G.Skill             | 15        | 3.55%   |
| A-DATA Technology   | 12        | 2.84%   |
| Ramaxel Technology  | 8         | 1.89%   |
| Elpida              | 5         | 1.18%   |
| Team                | 4         | 0.95%   |
| Patriot             | 3         | 0.71%   |
| Nanya Technology    | 3         | 0.71%   |
| Kllisre             | 3         | 0.71%   |
| Unknown (ABCD)      | 2         | 0.47%   |
| GOODRAM             | 2         | 0.47%   |
| V-Color             | 1         | 0.24%   |
| Unifosa             | 1         | 0.24%   |
| SMART Brazil        | 1         | 0.24%   |
| Smart               | 1         | 0.24%   |
| PNY                 | 1         | 0.24%   |
| Kingmax             | 1         | 0.24%   |
| KETECH              | 1         | 0.24%   |
| GeIL                | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.09%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 4         | 0.87%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.87%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 4         | 0.87%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s           | 4         | 0.87%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.65%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.65%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 3         | 0.65%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.65%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.65%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 3         | 0.65%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.65%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 3         | 0.65%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s            | 3         | 0.65%   |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                     | 2         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 2         | 0.43%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2         | 0.43%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 2         | 0.43%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                         | 2         | 0.43%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                       | 2         | 0.43%   |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s             | 2         | 0.43%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.43%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.43%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.43%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.43%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.43%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.43%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 2         | 0.43%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.43%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.43%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.43%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.43%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.43%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.43%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4096MB SODIMM DDR4 2667MT/s     | 2         | 0.43%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.43%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 2         | 0.43%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.43%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s               | 2         | 0.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                | 2         | 0.43%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                | 2         | 0.43%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s          | 2         | 0.43%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s              | 2         | 0.43%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s              | 2         | 0.43%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s              | 2         | 0.43%   |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s          | 2         | 0.43%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 2         | 0.43%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s           | 2         | 0.43%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 2         | 0.43%   |
| Crucial RAM CT8G4SFRA32A.C8FE 8GB SODIMM DDR4 3200MT/s           | 2         | 0.43%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s            | 2         | 0.43%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s          | 2         | 0.43%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s            | 2         | 0.43%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s                 | 1         | 0.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 182       | 50%     |
| DDR3    | 128       | 35.16%  |
| DDR2    | 17        | 4.67%   |
| LPDDR3  | 11        | 3.02%   |
| SDRAM   | 9         | 2.47%   |
| LPDDR4  | 8         | 2.2%    |
| Unknown | 8         | 2.2%    |
| DDR     | 1         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 198       | 54.55%  |
| DIMM         | 140       | 38.57%  |
| Row Of Chips | 21        | 5.79%   |
| Chip         | 2         | 0.55%   |
| RIMM         | 1         | 0.28%   |
| Unknown      | 1         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 143       | 36.39%  |
| 4096  | 105       | 26.72%  |
| 16384 | 62        | 15.78%  |
| 2048  | 40        | 10.18%  |
| 1024  | 19        | 4.83%   |
| 32768 | 17        | 4.33%   |
| 512   | 4         | 1.02%   |
| 256   | 2         | 0.51%   |
| 65536 | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 92        | 22.89%  |
| 2667    | 69        | 17.16%  |
| 3200    | 54        | 13.43%  |
| 1333    | 35        | 8.71%   |
| 2400    | 34        | 8.46%   |
| 2133    | 23        | 5.72%   |
| 1334    | 13        | 3.23%   |
| 3600    | 10        | 2.49%   |
| 1867    | 7         | 1.74%   |
| 800     | 7         | 1.74%   |
| 667     | 6         | 1.49%   |
| 2933    | 5         | 1.24%   |
| 400     | 5         | 1.24%   |
| Unknown | 5         | 1.24%   |
| 1067    | 4         | 1%      |
| 4267    | 3         | 0.75%   |
| 3466    | 3         | 0.75%   |
| 2666    | 3         | 0.75%   |
| 1866    | 3         | 0.75%   |
| 533     | 3         | 0.75%   |
| 3400    | 2         | 0.5%    |
| 3000    | 2         | 0.5%    |
| 1066    | 2         | 0.5%    |
| 4266    | 1         | 0.25%   |
| 4199    | 1         | 0.25%   |
| 3533    | 1         | 0.25%   |
| 3500    | 1         | 0.25%   |
| 3100    | 1         | 0.25%   |
| 3066    | 1         | 0.25%   |
| 2465    | 1         | 0.25%   |
| 2000    | 1         | 0.25%   |
| 1800    | 1         | 0.25%   |
| 1367    | 1         | 0.25%   |
| 975     | 1         | 0.25%   |
| 333     | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 44.44%  |
| Samsung Electronics | 2         | 22.22%  |
| Canon               | 2         | 22.22%  |
| Konica Minolta      | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-2010P Mono Laser Printer | 1         | 11.11%  |
| Samsung ML-1660 Series              | 1         | 11.11%  |
| Konica Minolta bizhub 4402P         | 1         | 11.11%  |
| HP LaserJet P1006                   | 1         | 11.11%  |
| HP LaserJet M101-M106               | 1         | 11.11%  |
| HP LaserJet 1200                    | 1         | 11.11%  |
| HP ENVY 4520 series                 | 1         | 11.11%  |
| Canon LiDE 400                      | 1         | 11.11%  |
| Canon iP2700 series                 | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 50%     |
| Canon       | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20            | 2         | 50%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 25%     |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 42        | 18.26%  |
| IMC Networks                           | 33        | 14.35%  |
| Acer                                   | 24        | 10.43%  |
| Microdia                               | 21        | 9.13%   |
| Logitech                               | 17        | 7.39%   |
| Realtek Semiconductor                  | 15        | 6.52%   |
| Lite-On Technology                     | 11        | 4.78%   |
| Quanta                                 | 10        | 4.35%   |
| Sunplus Innovation Technology          | 9         | 3.91%   |
| Suyin                                  | 6         | 2.61%   |
| Apple                                  | 5         | 2.17%   |
| Syntek                                 | 4         | 1.74%   |
| Luxvisions Innotech Limited            | 4         | 1.74%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 1.74%   |
| Samsung Electronics                    | 3         | 1.3%    |
| Z-Star Microelectronics                | 2         | 0.87%   |
| Genesys Logic                          | 2         | 0.87%   |
| Generalplus Technology                 | 2         | 0.87%   |
| eMPIA Technology                       | 2         | 0.87%   |
| Xiongmai                               | 1         | 0.43%   |
| SiGma Micro                            | 1         | 0.43%   |
| Razer USA                              | 1         | 0.43%   |
| Primax Electronics                     | 1         | 0.43%   |
| Pixart Imaging                         | 1         | 0.43%   |
| Lenovo                                 | 1         | 0.43%   |
| Jieli Technology                       | 1         | 0.43%   |
| Huawei Technologies                    | 1         | 0.43%   |
| Hewlett-Packard                        | 1         | 0.43%   |
| AVerMedia Technologies                 | 1         | 0.43%   |
| ARC International                      | 1         | 0.43%   |
| ALi                                    | 1         | 0.43%   |
| Alcor Micro                            | 1         | 0.43%   |
| A4Tech                                 | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 17        | 7.36%   |
| IMC Networks Integrated Camera           | 12        | 5.19%   |
| Acer Integrated Camera                   | 11        | 4.76%   |
| Microdia Integrated_Webcam_HD            | 10        | 4.33%   |
| Realtek Integrated_Webcam_HD             | 7         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam        | 7         | 3.03%   |
| Chicony HP HD Camera                     | 5         | 2.16%   |
| Chicony HD Webcam                        | 5         | 2.16%   |
| Acer SunplusIT Integrated Camera         | 5         | 2.16%   |
| Lite-On Integrated Camera                | 4         | 1.73%   |
| Sunplus Integrated_Webcam_HD             | 3         | 1.3%    |
| Samsung Galaxy A5 (MTP)                  | 3         | 1.3%    |
| Microdia Webcam Vitade AF                | 3         | 1.3%    |
| Logitech Webcam C270                     | 3         | 1.3%    |
| Logitech HD Pro Webcam C920              | 3         | 1.3%    |
| IMC Networks USB2.0 VGA UVC WebCam       | 3         | 1.3%    |
| IMC Networks USB2.0 HD IR UVC WebCam     | 3         | 1.3%    |
| Syntek Integrated Camera                 | 2         | 0.87%   |
| Realtek Integrated Webcam                | 2         | 0.87%   |
| Realtek EasyCamera                       | 2         | 0.87%   |
| Quanta HD Webcam                         | 2         | 0.87%   |
| Microdia USB Live camera                 | 2         | 0.87%   |
| Microdia Integrated Webcam HD            | 2         | 0.87%   |
| Luxvisions Innotech Limited HP HD Camera | 2         | 0.87%   |
| Logitech HD Webcam C910                  | 2         | 0.87%   |
| Logitech HD Webcam C615                  | 2         | 0.87%   |
| Logitech C505 HD Webcam                  | 2         | 0.87%   |
| Lite-On HP Webcam                        | 2         | 0.87%   |
| Lite-On HP HD Camera                     | 2         | 0.87%   |
| IMC Networks ov9734_azurewave_camera     | 2         | 0.87%   |
| IMC Networks Lenovo EasyCamera           | 2         | 0.87%   |
| Chicony USB2.0 Camera                    | 2         | 0.87%   |
| Chicony Lenovo EasyCamera                | 2         | 0.87%   |
| Chicony HP HD Webcam                     | 2         | 0.87%   |
| Apple FaceTime HD Camera                 | 2         | 0.87%   |
| Acer Lenovo Integrated Webcam            | 2         | 0.87%   |
| Acer EasyCamera                          | 2         | 0.87%   |
| Z-Star Venus USB2.0 Camera               | 1         | 0.43%   |
| Z-Star Sirius USB2.0 Camera              | 1         | 0.43%   |
| Xiongmai web camera                      | 1         | 0.43%   |
| Syntek USB 2.0 UVC PC Camera             | 1         | 0.43%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.43%   |
| Suyin Laptop_Integrated_Webcam_HD        | 1         | 0.43%   |
| Suyin HP TrueVision HD Integrated Webcam | 1         | 0.43%   |
| Suyin HP TrueVision Full HD              | 1         | 0.43%   |
| Suyin HD WebCam                          | 1         | 0.43%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.43%   |
| Suyin Acer CrystalEye Webcam             | 1         | 0.43%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 1         | 0.43%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 0.43%   |
| Sunplus Laptop Integrated Webcam FHD     | 1         | 0.43%   |
| Sunplus HP Universal Camera              | 1         | 0.43%   |
| Sunplus HD USB Camaer 4K                 | 1         | 0.43%   |
| Sunplus 1.3M HD WebCam                   | 1         | 0.43%   |
| SiGma Micro WebCam SiGma Micro           | 1         | 0.43%   |
| Realtek USB Camera                       | 1         | 0.43%   |
| Realtek Lenovo EasyCamera                | 1         | 0.43%   |
| Realtek HD WebCam                        | 1         | 0.43%   |
| Realtek Acer 640 x 480 laptop camera     | 1         | 0.43%   |
| Razer USA Razer Kiyo                     | 1         | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 18        | 37.5%   |
| Validity Sensors           | 11        | 22.92%  |
| Shenzhen Goodix Technology | 9         | 18.75%  |
| Upek                       | 4         | 8.33%   |
| Elan Microelectronics      | 3         | 6.25%   |
| AuthenTec                  | 2         | 4.17%   |
| LighTuning Technology      | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 14.58%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 10.42%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 10.42%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 8.33%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 6.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 3         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.17%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.08%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.08%   |
| Synaptics  WBDI                                                            | 1         | 2.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.08%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 2.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.08%   |
| Unknown                                                                    | 1         | 2.08%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 9         | 32.14%  |
| Broadcom              | 8         | 28.57%  |
| Lenovo                | 5         | 17.86%  |
| Upek                  | 3         | 10.71%  |
| Yubico.com            | 1         | 3.57%   |
| O2 Micro              | 1         | 3.57%   |
| Gemalto (was Gemplus) | 1         | 3.57%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 32.14%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 17.86%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 10.71%  |
| Broadcom 58200                                                               | 3         | 10.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 7.14%   |
| Broadcom 5880                                                                | 2         | 7.14%   |
| Yubico.com Yubikey 4 CCID                                                    | 1         | 3.57%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.57%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 3.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.57%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 299       | 74.19%  |
| 1     | 73        | 18.11%  |
| 2     | 26        | 6.45%   |
| 5     | 2         | 0.5%    |
| 3     | 2         | 0.5%    |
| 4     | 1         | 0.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 48        | 36.09%  |
| Chipcard                 | 22        | 16.54%  |
| Graphics card            | 21        | 15.79%  |
| Multimedia controller    | 13        | 9.77%   |
| Communication controller | 8         | 6.02%   |
| Net/wireless             | 7         | 5.26%   |
| Unassigned class         | 5         | 3.76%   |
| Storage                  | 3         | 2.26%   |
| Sound                    | 1         | 0.75%   |
| Network                  | 1         | 0.75%   |
| Modem                    | 1         | 0.75%   |
| Firewire controller      | 1         | 0.75%   |
| Card reader              | 1         | 0.75%   |
| Bluetooth                | 1         | 0.75%   |

