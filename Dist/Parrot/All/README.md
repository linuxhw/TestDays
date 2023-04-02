Parrot - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Parrot.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot/Desktop/README.md) and [notebooks](/Dist/Parrot/Notebook/README.md).

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

Total: 583

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Google        | Lillipup                    | Notebook    | [09292890c9](https://linux-hardware.org/?probe=09292890c9) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0180776452](https://linux-hardware.org/?probe=0180776452) | Mar 26, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [728805785d](https://linux-hardware.org/?probe=728805785d) | Mar 25, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [35030027f5](https://linux-hardware.org/?probe=35030027f5) | Mar 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [0927eb4ba9](https://linux-hardware.org/?probe=0927eb4ba9) | Mar 17, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6752797fe9](https://linux-hardware.org/?probe=6752797fe9) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e0019e450](https://linux-hardware.org/?probe=2e0019e450) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [47f7858a60](https://linux-hardware.org/?probe=47f7858a60) | Mar 07, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [143b06f2d6](https://linux-hardware.org/?probe=143b06f2d6) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [fe287f85c8](https://linux-hardware.org/?probe=fe287f85c8) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [d3bb7ff642](https://linux-hardware.org/?probe=d3bb7ff642) | Mar 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| ASRock        | B560M-C                     | Desktop     | [a93d64aa2c](https://linux-hardware.org/?probe=a93d64aa2c) | Feb 28, 2023 |
| ASRock        | B560M-C                     | Desktop     | [cbbd0a63d4](https://linux-hardware.org/?probe=cbbd0a63d4) | Feb 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [418b5dd7ff](https://linux-hardware.org/?probe=418b5dd7ff) | Feb 27, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [13355a7d07](https://linux-hardware.org/?probe=13355a7d07) | Feb 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [85bc55a850](https://linux-hardware.org/?probe=85bc55a850) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [1237b75ae4](https://linux-hardware.org/?probe=1237b75ae4) | Feb 24, 2023 |
| Dell          | 0C1R19 A02                  | Desktop     | [42ff2c0844](https://linux-hardware.org/?probe=42ff2c0844) | Feb 22, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [1d234f85b4](https://linux-hardware.org/?probe=1d234f85b4) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [5b6b8eee92](https://linux-hardware.org/?probe=5b6b8eee92) | Feb 22, 2023 |
| ASRock        | B560M-C                     | Desktop     | [0641c704e9](https://linux-hardware.org/?probe=0641c704e9) | Feb 20, 2023 |
| Biostar       | B450MH                      | Desktop     | [963e90387d](https://linux-hardware.org/?probe=963e90387d) | Feb 17, 2023 |
| Google        | Robo360                     | Notebook    | [e7c85b2410](https://linux-hardware.org/?probe=e7c85b2410) | Feb 09, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bfb29a2d13](https://linux-hardware.org/?probe=bfb29a2d13) | Feb 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [725e7248ee](https://linux-hardware.org/?probe=725e7248ee) | Feb 04, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [9f67df0760](https://linux-hardware.org/?probe=9f67df0760) | Feb 03, 2023 |
| ASRock        | Z87M Extreme4               | Desktop     | [8821f128c8](https://linux-hardware.org/?probe=8821f128c8) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS2J300    | Notebook    | [741b347456](https://linux-hardware.org/?probe=741b347456) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d800b8a4b9](https://linux-hardware.org/?probe=d800b8a4b9) | Jan 30, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [15644c39de](https://linux-hardware.org/?probe=15644c39de) | Jan 25, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [91e33f05ed](https://linux-hardware.org/?probe=91e33f05ed) | Jan 24, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [eb10e25652](https://linux-hardware.org/?probe=eb10e25652) | Jan 23, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [6552c7b8b3](https://linux-hardware.org/?probe=6552c7b8b3) | Jan 22, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [64164ef7df](https://linux-hardware.org/?probe=64164ef7df) | Jan 20, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [46befb7112](https://linux-hardware.org/?probe=46befb7112) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Quanta        | TW9/SW9                     | Notebook    | [4a196739f5](https://linux-hardware.org/?probe=4a196739f5) | Jan 18, 2023 |
| Lenovo        | ThinkPad E590 20NB0003AD    | Notebook    | [fe3de007e1](https://linux-hardware.org/?probe=fe3de007e1) | Jan 16, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Dell          | Latitude E6520              | Notebook    | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [9496d56fab](https://linux-hardware.org/?probe=9496d56fab) | Jan 04, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [aaac67afbe](https://linux-hardware.org/?probe=aaac67afbe) | Dec 23, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d45689035c](https://linux-hardware.org/?probe=d45689035c) | Dec 19, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a17338c77a](https://linux-hardware.org/?probe=a17338c77a) | Dec 17, 2022 |
| HP            | 3397                        | Desktop     | [33ba62be32](https://linux-hardware.org/?probe=33ba62be32) | Dec 10, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0e7586e771](https://linux-hardware.org/?probe=0e7586e771) | Dec 06, 2022 |
| Dell          | G3 3500                     | Notebook    | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| MSI           | GT60                        | Notebook    | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Quanta        | TW9/SW9                     | Notebook    | [5bfeb648aa](https://linux-hardware.org/?probe=5bfeb648aa) | Nov 28, 2022 |
| Quanta        | TW9/SW9                     | Notebook    | [ba75780c3e](https://linux-hardware.org/?probe=ba75780c3e) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [d57a12d93c](https://linux-hardware.org/?probe=d57a12d93c) | Nov 20, 2022 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [7928d11567](https://linux-hardware.org/?probe=7928d11567) | Nov 19, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| Dell          | 0C1R19 A02                  | Desktop     | [514ae17aa9](https://linux-hardware.org/?probe=514ae17aa9) | Nov 06, 2022 |
| HP            | 89B5 A                      | Desktop     | [1b04604c98](https://linux-hardware.org/?probe=1b04604c98) | Nov 03, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9eec3492e9](https://linux-hardware.org/?probe=9eec3492e9) | Oct 30, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c6a7aeb8ad](https://linux-hardware.org/?probe=c6a7aeb8ad) | Oct 30, 2022 |
| Dell          | Latitude 3350               | Notebook    | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5b16264bea](https://linux-hardware.org/?probe=5b16264bea) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [afd2f21c66](https://linux-hardware.org/?probe=afd2f21c66) | Oct 26, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| Dell          | Latitude E5500              | Notebook    | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [fbd3c71f34](https://linux-hardware.org/?probe=fbd3c71f34) | Oct 23, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [6595a0b531](https://linux-hardware.org/?probe=6595a0b531) | Oct 19, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6a85eb0ff4](https://linux-hardware.org/?probe=6a85eb0ff4) | Oct 14, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [d84fc5ce81](https://linux-hardware.org/?probe=d84fc5ce81) | Oct 13, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [2a896ec4f6](https://linux-hardware.org/?probe=2a896ec4f6) | Oct 13, 2022 |
| Clevo         | W25xHPx                     | Notebook    | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| Irbis         | NB121                       | Notebook    | [04f312f46b](https://linux-hardware.org/?probe=04f312f46b) | Oct 13, 2022 |
| Irbis         | NB121                       | Notebook    | [ff99468633](https://linux-hardware.org/?probe=ff99468633) | Oct 13, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [7ba818df9e](https://linux-hardware.org/?probe=7ba818df9e) | Oct 11, 2022 |
| Alienware     | m15 R7                      | Notebook    | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Lenovo        | LEGIONC7 82EH               | Notebook    | [880c4773fd](https://linux-hardware.org/?probe=880c4773fd) | Oct 06, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | Notebook    | [5b3df02ed5](https://linux-hardware.org/?probe=5b3df02ed5) | Oct 03, 2022 |
| HP            | Unknown                     | Notebook    | [0a6433c4fe](https://linux-hardware.org/?probe=0a6433c4fe) | Oct 03, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | Notebook    | [70451644fc](https://linux-hardware.org/?probe=70451644fc) | Oct 03, 2022 |
| BANGHO        | GAMER GM-X 15s              | Notebook    | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | Desktop     | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| HP            | Presario CQ58               | Notebook    | [4bb50cd19d](https://linux-hardware.org/?probe=4bb50cd19d) | Sep 28, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [7ad1831ce9](https://linux-hardware.org/?probe=7ad1831ce9) | Sep 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [9616464154](https://linux-hardware.org/?probe=9616464154) | Sep 26, 2022 |
| Dell          | Latitude 3350               | Notebook    | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Toshiba       | Satellite C855D             | Notebook    | [bae94a45be](https://linux-hardware.org/?probe=bae94a45be) | Sep 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f8de7730b6](https://linux-hardware.org/?probe=f8de7730b6) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [315af016c7](https://linux-hardware.org/?probe=315af016c7) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4e798ff22](https://linux-hardware.org/?probe=d4e798ff22) | Sep 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [1de889aa64](https://linux-hardware.org/?probe=1de889aa64) | Sep 05, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1d04855f84](https://linux-hardware.org/?probe=1d04855f84) | Aug 29, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7439a7400d](https://linux-hardware.org/?probe=7439a7400d) | Aug 27, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [fa26302bd8](https://linux-hardware.org/?probe=fa26302bd8) | Aug 27, 2022 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| Standard      | Unknown                     | Notebook    | [782f229d6c](https://linux-hardware.org/?probe=782f229d6c) | Aug 17, 2022 |
| Panasonic     | CF-31JBGNNDM                | Notebook    | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [47608d95ea](https://linux-hardware.org/?probe=47608d95ea) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [0bd14e553d](https://linux-hardware.org/?probe=0bd14e553d) | Aug 10, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Dell          | Latitude E6420              | Notebook    | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| Gateway       | SX2855                      | Desktop     | [a896e3b0f7](https://linux-hardware.org/?probe=a896e3b0f7) | Jul 30, 2022 |
| HP            | 250 G2                      | Notebook    | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [26be63e8a0](https://linux-hardware.org/?probe=26be63e8a0) | Jul 25, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [0bacf44374](https://linux-hardware.org/?probe=0bacf44374) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [007eeacf86](https://linux-hardware.org/?probe=007eeacf86) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8ce974e537](https://linux-hardware.org/?probe=8ce974e537) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | Notebook    | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [4d3cf557ba](https://linux-hardware.org/?probe=4d3cf557ba) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | Notebook    | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [9e9ca5b39a](https://linux-hardware.org/?probe=9e9ca5b39a) | Jul 19, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [0539efedb2](https://linux-hardware.org/?probe=0539efedb2) | Jul 18, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2c55e11e85](https://linux-hardware.org/?probe=2c55e11e85) | Jul 18, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [0e0a7a2fbc](https://linux-hardware.org/?probe=0e0a7a2fbc) | Jul 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [a7de2e1421](https://linux-hardware.org/?probe=a7de2e1421) | Jul 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [623281f994](https://linux-hardware.org/?probe=623281f994) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [713bd9f4b0](https://linux-hardware.org/?probe=713bd9f4b0) | Jul 14, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [49e71e9dc1](https://linux-hardware.org/?probe=49e71e9dc1) | Jul 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f6c3c6f86e](https://linux-hardware.org/?probe=f6c3c6f86e) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c680f5f212](https://linux-hardware.org/?probe=c680f5f212) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Lenovo        | ThinkPad L430 2465C32       | Notebook    | [f088c4ae11](https://linux-hardware.org/?probe=f088c4ae11) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [e022aed2bc](https://linux-hardware.org/?probe=e022aed2bc) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8b55dcfd2d](https://linux-hardware.org/?probe=8b55dcfd2d) | Jun 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6f3036d638](https://linux-hardware.org/?probe=6f3036d638) | Jun 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6348a01f19](https://linux-hardware.org/?probe=6348a01f19) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | Notebook    | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Unknown       | TB-4000                     | Desktop     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [7e3fc5fe06](https://linux-hardware.org/?probe=7e3fc5fe06) | Jun 02, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [02ace99875](https://linux-hardware.org/?probe=02ace99875) | Jun 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [449fc46111](https://linux-hardware.org/?probe=449fc46111) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | Notebook    | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| MSI           | GE62 6QE                    | Notebook    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Timi          | TM1613                      | Notebook    | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | Notebook    | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| HP            | 1495                        | Desktop     | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b3afe4ff08](https://linux-hardware.org/?probe=b3afe4ff08) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [320ae25dbf](https://linux-hardware.org/?probe=320ae25dbf) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | Notebook    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | Notebook    | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | Notebook    | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | Notebook    | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Unknown       | TB-4000                     | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Unknown       | TB-4000                     | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | Notebook    | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Unknown       | TB-4000                     | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Microsoft     | Surface Book                | Tablet      | [327a2ec07f](https://linux-hardware.org/?probe=327a2ec07f) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [1e5331da8c](https://linux-hardware.org/?probe=1e5331da8c) | Jan 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [8f4b5410ad](https://linux-hardware.org/?probe=8f4b5410ad) | Jan 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | Notebook    | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | Notebook    | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | Notebook    | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock        | Z87 Killer                  | Desktop     | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| Dell          | 0T2HR0 A00                  | Desktop     | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| Radxa         | ROCK 5B                     | Soc         | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b741d2ab2b](https://linux-hardware.org/?probe=b741d2ab2b) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | Notebook    | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| HP            | Pavilion dv7                | Notebook    | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | Notebook    | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| HP            | 1850                        | Desktop     | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | Notebook    | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | Notebook    | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| HP            | 1850                        | Desktop     | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| MSI           | GE73 Raider RGB 8RE         | Notebook    | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | Notebook    | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | Notebook    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Intel         | NUC8i7HVB J68196-601        | Mini pc     | [d186af4ee3](https://linux-hardware.org/?probe=d186af4ee3) | May 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | Notebook    | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| Dell          | 0C1R19 A02                  | Desktop     | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| HP            | 8430 1000                   | All in one  | [5c5adcc248](https://linux-hardware.org/?probe=5c5adcc248) | Apr 24, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | Notebook    | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | Notebook    | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| HP            | 339A                        | Desktop     | [b105e94284](https://linux-hardware.org/?probe=b105e94284) | Feb 20, 2021 |
| HP            | 339A                        | Desktop     | [3dfdd6aa5e](https://linux-hardware.org/?probe=3dfdd6aa5e) | Feb 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| MSI           | B250M MORTAR                | Desktop     | [be8a65f362](https://linux-hardware.org/?probe=be8a65f362) | Feb 02, 2021 |
| Dell          | 0CU409                      | Desktop     | [64c8a84081](https://linux-hardware.org/?probe=64c8a84081) | Jan 29, 2021 |
| HP            | ENVY 15                     | Notebook    | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Acer          | Aspire X3990                | Desktop     | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| Acer          | Aspire X3990                | Desktop     | [1660d13b44](https://linux-hardware.org/?probe=1660d13b44) | Jan 12, 2021 |
| HP            | 3047h                       | Desktop     | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| Dell          | Latitude 7390               | Notebook    | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| Medion        | MS-7621                     | Desktop     | [74c49730d1](https://linux-hardware.org/?probe=74c49730d1) | Dec 27, 2020 |
| Positivo      | POS-PIG43BC                 | Desktop     | [146c7d86bb](https://linux-hardware.org/?probe=146c7d86bb) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | Notebook    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | Notebook    | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | Notebook    | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| HP            | 3047h                       | Desktop     | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [7918687a8b](https://linux-hardware.org/?probe=7918687a8b) | Nov 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f95c24897c](https://linux-hardware.org/?probe=f95c24897c) | Oct 30, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f7a2b660d8](https://linux-hardware.org/?probe=f7a2b660d8) | Oct 29, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c687805b04](https://linux-hardware.org/?probe=c687805b04) | Oct 29, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| ECS           | A740GM-M                    | Desktop     | [423f49affd](https://linux-hardware.org/?probe=423f49affd) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | Notebook    | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | Notebook    | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | Notebook    | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [2bc8fbe372](https://linux-hardware.org/?probe=2bc8fbe372) | Sep 27, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | Notebook    | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [4ad16b3038](https://linux-hardware.org/?probe=4ad16b3038) | Sep 20, 2020 |
| Alienware     | 17 R4                       | Notebook    | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [f88025bc71](https://linux-hardware.org/?probe=f88025bc71) | Sep 16, 2020 |
| Dell          | Latitude 3400               | Notebook    | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | Notebook    | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | Notebook    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [c87fcab7c7](https://linux-hardware.org/?probe=c87fcab7c7) | Aug 26, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [608ad8477d](https://linux-hardware.org/?probe=608ad8477d) | Aug 22, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | Notebook    | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | Notebook    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | Notebook    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | Notebook    | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | Notebook    | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | Notebook    | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [1d8d1db67e](https://linux-hardware.org/?probe=1d8d1db67e) | Jul 04, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [06e9599063](https://linux-hardware.org/?probe=06e9599063) | Jul 04, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [dda8536e62](https://linux-hardware.org/?probe=dda8536e62) | Jun 11, 2020 |
| Dell          | G7 7790                     | Notebook    | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | Notebook    | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Biostar       | H77MU3                      | Desktop     | [048ffba01b](https://linux-hardware.org/?probe=048ffba01b) | May 24, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7c05b67968](https://linux-hardware.org/?probe=7c05b67968) | May 22, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fc8bf8a5a6](https://linux-hardware.org/?probe=fc8bf8a5a6) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | Notebook    | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5e5d0a24f3](https://linux-hardware.org/?probe=5e5d0a24f3) | May 15, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5a56c30293](https://linux-hardware.org/?probe=5a56c30293) | May 06, 2020 |
| ASUSTek       | X442URR                     | Notebook    | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | Notebook    | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | Notebook    | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | Notebook    | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | Notebook    | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | 05DN3X A00                  | Desktop     | [7424c0caba](https://linux-hardware.org/?probe=7424c0caba) | May 02, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [3dc6534b5f](https://linux-hardware.org/?probe=3dc6534b5f) | May 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6835f4fe95](https://linux-hardware.org/?probe=6835f4fe95) | Apr 28, 2020 |
| Dell          | Latitude E6420              | Notebook    | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | Notebook    | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [6e636c5fd2](https://linux-hardware.org/?probe=6e636c5fd2) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [d19700bc2d](https://linux-hardware.org/?probe=d19700bc2d) | Apr 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [72dcfa02ca](https://linux-hardware.org/?probe=72dcfa02ca) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [37c314650f](https://linux-hardware.org/?probe=37c314650f) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [9a9b368a7c](https://linux-hardware.org/?probe=9a9b368a7c) | Apr 26, 2020 |
| Dell          | XPS 12-9Q33                 | Notebook    | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| ASUSTek       | K31CD-K                     | Desktop     | [b4ad316fa2](https://linux-hardware.org/?probe=b4ad316fa2) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [661761d2ca](https://linux-hardware.org/?probe=661761d2ca) | Apr 14, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [5512733c4a](https://linux-hardware.org/?probe=5512733c4a) | Apr 14, 2020 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [93da68c7fb](https://linux-hardware.org/?probe=93da68c7fb) | Apr 12, 2020 |
| Dell          | Inspiron 5721               | Notebook    | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | Notebook    | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [224ebfd9b3](https://linux-hardware.org/?probe=224ebfd9b3) | Mar 30, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [79e98a64cf](https://linux-hardware.org/?probe=79e98a64cf) | Mar 30, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | Notebook    | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [cf7e8cd869](https://linux-hardware.org/?probe=cf7e8cd869) | Mar 16, 2020 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [05f8c8eef4](https://linux-hardware.org/?probe=05f8c8eef4) | Feb 29, 2020 |
| HP            | Laptop 17-by0xxx            | Notebook    | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [2bfc7eae61](https://linux-hardware.org/?probe=2bfc7eae61) | Feb 06, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [1e8ccbe5b9](https://linux-hardware.org/?probe=1e8ccbe5b9) | Feb 04, 2020 |
| Notebook      | W510TU                      | Notebook    | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | Notebook    | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [38658290e2](https://linux-hardware.org/?probe=38658290e2) | Jan 19, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [05e5552eea](https://linux-hardware.org/?probe=05e5552eea) | Jan 19, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | Notebook    | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | Notebook    | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [51389e5c4a](https://linux-hardware.org/?probe=51389e5c4a) | Dec 07, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | Notebook    | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | Notebook    | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | Notebook    | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | Notebook    | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | Notebook    | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | Notebook    | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | Notebook    | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Parrot/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Parrot 5.0   | 118       | 27.7%   |
| Parrot 4.11  | 93        | 21.83%  |
| Parrot 5.1   | 72        | 16.9%   |
| Parrot 4.10  | 60        | 14.08%  |
| Parrot 4.8   | 23        | 5.4%    |
| Parrot 4.9   | 22        | 5.16%   |
| Parrot 5.2   | 19        | 4.46%   |
| Parrot 4.7   | 13        | 3.05%   |
| Parrot 4.6   | 2         | 0.47%   |
| Parrot 4.5   | 1         | 0.23%   |
| Parrot 4.4   | 1         | 0.23%   |
| Parrot 4.2.2 | 1         | 0.23%   |
| Parrot 3.10  | 1         | 0.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Parrot | 405       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.0-12parrot1-amd64   | 56        | 12.87%  |
| 5.14.0-9parrot1-amd64    | 53        | 12.18%  |
| 5.10.0-6parrot1-amd64    | 34        | 7.82%   |
| 5.7.0-2parrot2-amd64     | 33        | 7.59%   |
| 5.18.0-14parrot1-amd64   | 32        | 7.36%   |
| 6.0.0-2parrot1-amd64     | 31        | 7.13%   |
| 6.0.0-12parrot1-amd64    | 26        | 5.98%   |
| 5.5.0-1parrot1-amd64     | 24        | 5.52%   |
| 5.10.0-8parrot1-amd64    | 18        | 4.14%   |
| 5.18.0-1parrot1-amd64    | 17        | 3.91%   |
| 5.4.0-4parrot1-amd64     | 16        | 3.68%   |
| 5.15.0-15parrot1-amd64   | 11        | 2.53%   |
| 5.14.0-2parrot1-amd64    | 11        | 2.53%   |
| 5.6.0-2parrot1-amd64     | 10        | 2.3%    |
| 5.9.0-2parrot1-amd64     | 9         | 2.07%   |
| 5.8.0-2parrot1-amd64     | 6         | 1.38%   |
| 5.4.0-2parrot1-amd64     | 5         | 1.15%   |
| 5.10.0-3parrot1-amd64    | 5         | 1.15%   |
| 5.8.0-1parrot1-amd64     | 4         | 0.92%   |
| 5.10.0-5parrot1-amd64    | 4         | 0.92%   |
| 5.4.0-3parrot1-amd64     | 3         | 0.69%   |
| 5.3.0-3parrot3-amd64     | 3         | 0.69%   |
| 5.2.0-2parrot1-amd64     | 3         | 0.69%   |
| 4.19.0-parrot4-28t-amd64 | 3         | 0.69%   |
| 6.0.5-x64v1-xanmod1      | 2         | 0.46%   |
| 4.18.0-parrot10-amd64    | 2         | 0.46%   |
| 5.7.0-rc6-galliumos      | 1         | 0.23%   |
| 5.4.0-2parrot1-686-pae   | 1         | 0.23%   |
| 5.4.0-1parrot1-amd64     | 1         | 0.23%   |
| 5.3.0-3parrot3-686-pae   | 1         | 0.23%   |
| 5.3.0-1parrot1-amd64     | 1         | 0.23%   |
| 5.16.0-12parrot1-686-pae | 1         | 0.23%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.23%   |
| 5.10.92-v8+              | 1         | 0.23%   |
| 5.10.0-kali6-amd64       | 1         | 0.23%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.23%   |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.23%   |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.23%   |
| 4.14.0-parrot7-amd64     | 1         | 0.23%   |
| Unknown                  | 1         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 63        | 14.62%  |
| 5.14.0  | 62        | 14.39%  |
| 5.16.0  | 57        | 13.23%  |
| 6.0.0   | 56        | 12.99%  |
| 5.18.0  | 48        | 11.14%  |
| 5.7.0   | 34        | 7.89%   |
| 5.4.0   | 26        | 6.03%   |
| 5.5.0   | 24        | 5.57%   |
| 5.15.0  | 12        | 2.78%   |
| 5.8.0   | 10        | 2.32%   |
| 5.6.0   | 10        | 2.32%   |
| 5.9.0   | 9         | 2.09%   |
| 5.3.0   | 5         | 1.16%   |
| 4.19.0  | 4         | 0.93%   |
| 5.2.0   | 3         | 0.7%    |
| 6.0.5   | 2         | 0.46%   |
| 4.18.0  | 2         | 0.46%   |
| 5.10.92 | 1         | 0.23%   |
| 5.1.0   | 1         | 0.23%   |
| 4.14.0  | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 64        | 14.85%  |
| 5.14    | 62        | 14.39%  |
| 6.0     | 58        | 13.46%  |
| 5.16    | 57        | 13.23%  |
| 5.18    | 48        | 11.14%  |
| 5.7     | 34        | 7.89%   |
| 5.4     | 26        | 6.03%   |
| 5.5     | 24        | 5.57%   |
| 5.15    | 12        | 2.78%   |
| 5.8     | 10        | 2.32%   |
| 5.6     | 10        | 2.32%   |
| 5.9     | 9         | 2.09%   |
| 5.3     | 5         | 1.16%   |
| 4.19    | 4         | 0.93%   |
| 5.2     | 3         | 0.7%    |
| 4.18    | 2         | 0.46%   |
| 5.1     | 1         | 0.23%   |
| 4.14    | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 402       | 99.26%  |
| i686    | 2         | 0.49%   |
| aarch64 | 1         | 0.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| MATE          | 292       | 70.36%  |
| KDE5          | 67        | 16.14%  |
| Unknown       | 22        | 5.3%    |
| KDE           | 20        | 4.82%   |
| XFCE          | 9         | 2.17%   |
| GNOME         | 2         | 0.48%   |
| LXDE          | 1         | 0.24%   |
| GNOME Classic | 1         | 0.24%   |
| Cinnamon      | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 398       | 98.27%  |
| Wayland | 3         | 0.74%   |
| Tty     | 3         | 0.74%   |
| Unknown | 1         | 0.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 196       | 47.12%  |
| Unknown | 133       | 31.97%  |
| TDM     | 71        | 17.07%  |
| SDDM    | 8         | 1.92%   |
| GDM     | 8         | 1.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 221       | 54.3%   |
| en_GB   | 26        | 6.39%   |
| fr_FR   | 20        | 4.91%   |
| es_ES   | 15        | 3.69%   |
| Unknown | 15        | 3.69%   |
| ru_RU   | 14        | 3.44%   |
| en_AU   | 12        | 2.95%   |
| pl_PL   | 11        | 2.7%    |
| de_DE   | 11        | 2.7%    |
| pt_BR   | 10        | 2.46%   |
| en_IN   | 9         | 2.21%   |
| it_IT   | 7         | 1.72%   |
| es_MX   | 4         | 0.98%   |
| en_CA   | 3         | 0.74%   |
| cs_CZ   | 3         | 0.74%   |
| es_CL   | 2         | 0.49%   |
| es_AR   | 2         | 0.49%   |
| en_HK   | 2         | 0.49%   |
| en_DK   | 2         | 0.49%   |
| tr_TR   | 1         | 0.25%   |
| ru_UA   | 1         | 0.25%   |
| pt_PT   | 1         | 0.25%   |
| nl_BE   | 1         | 0.25%   |
| mk_MK   | 1         | 0.25%   |
| id_ID   | 1         | 0.25%   |
| fr_CA   | 1         | 0.25%   |
| fi_FI   | 1         | 0.25%   |
| es_PE   | 1         | 0.25%   |
| es_CO   | 1         | 0.25%   |
| en_ZW   | 1         | 0.25%   |
| en_ZA   | 1         | 0.25%   |
| en_NZ   | 1         | 0.25%   |
| en_NG   | 1         | 0.25%   |
| de_AT   | 1         | 0.25%   |
| C       | 1         | 0.25%   |
| arn_CL  | 1         | 0.25%   |
| an_ES   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 246       | 59.56%  |
| EFI  | 167       | 40.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 321       | 78.1%   |
| Ext4    | 58        | 14.11%  |
| Overlay | 13        | 3.16%   |
| Xfs     | 12        | 2.92%   |
| Unknown | 7         | 1.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 172       | 41.45%  |
| Unknown | 167       | 40.24%  |
| MBR     | 76        | 18.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 360       | 87.38%  |
| Yes       | 52        | 12.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 266       | 65.2%   |
| Yes       | 142       | 34.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 73        | 18.02%  |
| Lenovo                  | 64        | 15.8%   |
| Dell                    | 59        | 14.57%  |
| ASUSTek Computer        | 56        | 13.83%  |
| Acer                    | 23        | 5.68%   |
| MSI                     | 17        | 4.2%    |
| Gigabyte Technology     | 15        | 3.7%    |
| Apple                   | 14        | 3.46%   |
| Toshiba                 | 8         | 1.98%   |
| Samsung Electronics     | 5         | 1.23%   |
| HUAWEI                  | 5         | 1.23%   |
| Alienware               | 5         | 1.23%   |
| ASRock                  | 4         | 0.99%   |
| Unknown                 | 4         | 0.99%   |
| Sony                    | 3         | 0.74%   |
| Microsoft               | 3         | 0.74%   |
| Gateway                 | 3         | 0.74%   |
| Fujitsu                 | 3         | 0.74%   |
| Foxconn                 | 3         | 0.74%   |
| Razer                   | 2         | 0.49%   |
| Quanta                  | 2         | 0.49%   |
| Positivo                | 2         | 0.49%   |
| Google                  | 2         | 0.49%   |
| ECS                     | 2         | 0.49%   |
| Biostar                 | 2         | 0.49%   |
| ZOTAC                   | 1         | 0.25%   |
| Wortmann AG             | 1         | 0.25%   |
| Wistron                 | 1         | 0.25%   |
| Toxic                   | 1         | 0.25%   |
| Timi                    | 1         | 0.25%   |
| System76                | 1         | 0.25%   |
| Standard                | 1         | 0.25%   |
| Raspberry Pi Foundation | 1         | 0.25%   |
| Radxa                   | 1         | 0.25%   |
| Positivo Bahia - VAIO   | 1         | 0.25%   |
| Pegatron                | 1         | 0.25%   |
| Panasonic               | 1         | 0.25%   |
| Notebook                | 1         | 0.25%   |
| Metabox                 | 1         | 0.25%   |
| Jumper                  | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 7         | 1.73%   |
| MSI Modern 15 A5M                  | 3         | 0.74%   |
| Lenovo IdeaPad 3 15IIL05 81WE      | 3         | 0.74%   |
| HP Pavilion 15                     | 3         | 0.74%   |
| HP Notebook                        | 3         | 0.74%   |
| HP ENVY x360 Convertible 13-bd0xxx | 3         | 0.74%   |
| HP EliteBook 8470p                 | 3         | 0.74%   |
| Dell Latitude E6420                | 3         | 0.74%   |
| Dell Inspiron MM061                | 3         | 0.74%   |
| Quanta TW9/SW9                     | 2         | 0.49%   |
| MSI Katana GF66 12UC               | 2         | 0.49%   |
| Microsoft Surface Pro 3            | 2         | 0.49%   |
| HP ProDesk 600 G1 SFF              | 2         | 0.49%   |
| HP ProBook 650 G1                  | 2         | 0.49%   |
| HP Pavilion dv6                    | 2         | 0.49%   |
| Gigabyte AX370-Gaming              | 2         | 0.49%   |
| Foxconn s5710t                     | 2         | 0.49%   |
| Dell OptiPlex 3020                 | 2         | 0.49%   |
| Dell Latitude E7440                | 2         | 0.49%   |
| Dell Latitude E6410                | 2         | 0.49%   |
| Dell Inspiron 5676                 | 2         | 0.49%   |
| ASUS Q524UQ                        | 2         | 0.49%   |
| ASUS M5A78L-M/USB3                 | 2         | 0.49%   |
| ASUS H110I-PLUS                    | 2         | 0.49%   |
| ASUS Basic 3221BM                  | 2         | 0.49%   |
| Apple MacBookPro8,1                | 2         | 0.49%   |
| Apple MacBookAir7,2                | 2         | 0.49%   |
| Apple iMac9,1                      | 2         | 0.49%   |
| Acer Nitro AN515-54                | 2         | 0.49%   |
| Acer Aspire ES1-111M               | 2         | 0.49%   |
| Wortmann AG TERRA_MOBILE_1542      | 1         | 0.25%   |
| Wistron FMVDD2A0H0                 | 1         | 0.25%   |
| Toxic GM7MQ8P                      | 1         | 0.25%   |
| Toshiba Satellite-L845             | 1         | 0.25%   |
| Toshiba Satellite L775D            | 1         | 0.25%   |
| Toshiba Satellite L750             | 1         | 0.25%   |
| Toshiba Satellite L655             | 1         | 0.25%   |
| Toshiba Satellite L300D            | 1         | 0.25%   |
| Toshiba Satellite Click 2 L35W-B   | 1         | 0.25%   |
| Toshiba Satellite C855D            | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 32        | 7.9%    |
| Dell Inspiron         | 22        | 5.43%   |
| Dell Latitude         | 20        | 4.94%   |
| HP Pavilion           | 16        | 3.95%   |
| Lenovo IdeaPad        | 13        | 3.21%   |
| Acer Aspire           | 12        | 2.96%   |
| HP Laptop             | 9         | 2.22%   |
| HP ENVY               | 9         | 2.22%   |
| HP EliteBook          | 9         | 2.22%   |
| Toshiba Satellite     | 7         | 1.73%   |
| Unknown               | 7         | 1.73%   |
| HP Compaq             | 6         | 1.48%   |
| Dell OptiPlex         | 6         | 1.48%   |
| HP ProBook            | 5         | 1.23%   |
| ASUS PRIME            | 5         | 1.23%   |
| HP ZBook              | 4         | 0.99%   |
| ASUS VivoBook         | 4         | 0.99%   |
| ASUS ASUS             | 4         | 0.99%   |
| Acer Nitro            | 4         | 0.99%   |
| MSI Modern            | 3         | 0.74%   |
| MSI Katana            | 3         | 0.74%   |
| Microsoft Surface     | 3         | 0.74%   |
| Lenovo Yoga           | 3         | 0.74%   |
| HP Victus             | 3         | 0.74%   |
| HP Notebook           | 3         | 0.74%   |
| Fujitsu LIFEBOOK      | 3         | 0.74%   |
| Dell XPS              | 3         | 0.74%   |
| ASUS ROG              | 3         | 0.74%   |
| Acer Swift            | 3         | 0.74%   |
| Acer Predator         | 3         | 0.74%   |
| Razer Blade           | 2         | 0.49%   |
| Quanta TW9            | 2         | 0.49%   |
| MSI GT60              | 2         | 0.49%   |
| Lenovo Legion         | 2         | 0.49%   |
| HP ProDesk            | 2         | 0.49%   |
| HP 250                | 2         | 0.49%   |
| Gigabyte AX370-Gaming | 2         | 0.49%   |
| Foxconn s5710t        | 2         | 0.49%   |
| Dell Vostro           | 2         | 0.49%   |
| Dell Precision        | 2         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 45        | 11.11%  |
| 2011    | 42        | 10.37%  |
| 2019    | 40        | 9.88%   |
| 2018    | 36        | 8.89%   |
| 2013    | 35        | 8.64%   |
| 2012    | 31        | 7.65%   |
| 2020    | 29        | 7.16%   |
| 2016    | 29        | 7.16%   |
| 2017    | 24        | 5.93%   |
| 2014    | 18        | 4.44%   |
| 2010    | 18        | 4.44%   |
| 2015    | 15        | 3.7%    |
| 2022    | 14        | 3.46%   |
| 2008    | 8         | 1.98%   |
| 2007    | 8         | 1.98%   |
| 2009    | 7         | 1.73%   |
| 2006    | 4         | 0.99%   |
| 2023    | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 285       | 70.37%  |
| Desktop        | 92        | 22.72%  |
| Convertible    | 17        | 4.2%    |
| Tablet         | 4         | 0.99%   |
| All in one     | 3         | 0.74%   |
| System on chip | 2         | 0.49%   |
| Mini pc        | 2         | 0.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 405       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 403       | 99.51%  |
| Yes  | 2         | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 100       | 24.33%  |
| 16.01-24.0  | 94        | 22.87%  |
| 8.01-16.0   | 89        | 21.65%  |
| 3.01-4.0    | 70        | 17.03%  |
| 32.01-64.0  | 31        | 7.54%   |
| 1.01-2.0    | 12        | 2.92%   |
| 64.01-256.0 | 8         | 1.95%   |
| 24.01-32.0  | 4         | 0.97%   |
| 2.01-3.0    | 3         | 0.73%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 143       | 33.41%  |
| 1.01-2.0   | 141       | 32.94%  |
| 3.01-4.0   | 63        | 14.72%  |
| 4.01-8.0   | 50        | 11.68%  |
| 0.51-1.0   | 19        | 4.44%   |
| 8.01-16.0  | 9         | 2.1%    |
| 0.01-0.5   | 2         | 0.47%   |
| 16.01-24.0 | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 248       | 60.05%  |
| 2      | 128       | 30.99%  |
| 3      | 22        | 5.33%   |
| 4      | 8         | 1.94%   |
| 5      | 4         | 0.97%   |
| 0      | 2         | 0.48%   |
| 6      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 282       | 68.78%  |
| Yes       | 128       | 31.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 334       | 82.27%  |
| No        | 72        | 17.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 374       | 91.89%  |
| No        | 33        | 8.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 281       | 68.54%  |
| No        | 129       | 31.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 132       | 32.2%   |
| Germany      | 23        | 5.61%   |
| France       | 20        | 4.88%   |
| Spain        | 19        | 4.63%   |
| Brazil       | 16        | 3.9%    |
| Russia       | 15        | 3.66%   |
| UK           | 13        | 3.17%   |
| Netherlands  | 12        | 2.93%   |
| Italy        | 11        | 2.68%   |
| India        | 11        | 2.68%   |
| Australia    | 10        | 2.44%   |
| Mexico       | 9         | 2.2%    |
| Canada       | 8         | 1.95%   |
| Poland       | 6         | 1.46%   |
| Kenya        | 6         | 1.46%   |
| Czechia      | 5         | 1.22%   |
| Bangladesh   | 5         | 1.22%   |
| Sweden       | 4         | 0.98%   |
| Indonesia    | 4         | 0.98%   |
| Denmark      | 4         | 0.98%   |
| Austria      | 4         | 0.98%   |
| Algeria      | 4         | 0.98%   |
| Turkey       | 3         | 0.73%   |
| South Africa | 3         | 0.73%   |
| Mongolia     | 3         | 0.73%   |
| Iraq         | 3         | 0.73%   |
| Finland      | 3         | 0.73%   |
| Chile        | 3         | 0.73%   |
| Switzerland  | 2         | 0.49%   |
| Puerto Rico  | 2         | 0.49%   |
| Portugal     | 2         | 0.49%   |
| Pakistan     | 2         | 0.49%   |
| Nepal        | 2         | 0.49%   |
| Namibia      | 2         | 0.49%   |
| Morocco      | 2         | 0.49%   |
| Japan        | 2         | 0.49%   |
| Hong Kong    | 2         | 0.49%   |
| Egypt        | 2         | 0.49%   |
| Bulgaria     | 2         | 0.49%   |
| Belgium      | 2         | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Amsterdam           | 6         | 1.41%   |
| Nairobi             | 5         | 1.17%   |
| Moscow              | 5         | 1.17%   |
| Sydney              | 4         | 0.94%   |
| Melbourne           | 4         | 0.94%   |
| Madrid              | 4         | 0.94%   |
| Lyon                | 4         | 0.94%   |
| Los Angeles         | 4         | 0.94%   |
| Houston             | 4         | 0.94%   |
| Dhaka               | 4         | 0.94%   |
| Dallas              | 4         | 0.94%   |
| Chicago             | 4         | 0.94%   |
| Warsaw              | 3         | 0.7%    |
| Vienna              | 3         | 0.7%    |
| Ulan Bator          | 3         | 0.7%    |
| Seattle             | 3         | 0.7%    |
| Pensacola           | 3         | 0.7%    |
| Paris               | 3         | 0.7%    |
| London              | 3         | 0.7%    |
| Indianapolis        | 3         | 0.7%    |
| Eugene              | 3         | 0.7%    |
| Berlin              | 3         | 0.7%    |
| Barcelona           | 3         | 0.7%    |
| Atlanta             | 3         | 0.7%    |
| Zurich              | 2         | 0.47%   |
| Visalia             | 2         | 0.47%   |
| Villa del Rio       | 2         | 0.47%   |
| Uherské Hradiště | 2         | 0.47%   |
| Tokyo               | 2         | 0.47%   |
| Tangier             | 2         | 0.47%   |
| Stockholm           | 2         | 0.47%   |
| St Petersburg       | 2         | 0.47%   |
| Sao Paulo           | 2         | 0.47%   |
| San Juan            | 2         | 0.47%   |
| Saint Paul          | 2         | 0.47%   |
| Ruskin              | 2         | 0.47%   |
| Rome                | 2         | 0.47%   |
| Reading             | 2         | 0.47%   |
| Pretoria            | 2         | 0.47%   |
| Prague              | 2         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 85        | 110    | 15.12%  |
| Samsung Electronics | 81        | 105    | 14.41%  |
| Seagate             | 66        | 84     | 11.74%  |
| Toshiba             | 61        | 66     | 10.85%  |
| Unknown             | 35        | 37     | 6.23%   |
| Kingston            | 32        | 34     | 5.69%   |
| SanDisk             | 24        | 33     | 4.27%   |
| Hitachi             | 19        | 22     | 3.38%   |
| Crucial             | 16        | 21     | 2.85%   |
| SK hynix            | 14        | 17     | 2.49%   |
| Micron Technology   | 14        | 14     | 2.49%   |
| HGST                | 14        | 17     | 2.49%   |
| Intel               | 12        | 25     | 2.14%   |
| China               | 8         | 11     | 1.42%   |
| A-DATA Technology   | 7         | 7      | 1.25%   |
| Apple               | 6         | 6      | 1.07%   |
| Phison              | 4         | 4      | 0.71%   |
| KIOXIA              | 4         | 5      | 0.71%   |
| YMTC                | 3         | 3      | 0.53%   |
| Team                | 3         | 4      | 0.53%   |
| PNY                 | 3         | 3      | 0.53%   |
| LITEONIT            | 3         | 3      | 0.53%   |
| LITEON              | 3         | 3      | 0.53%   |
| JMicron Technology  | 3         | 3      | 0.53%   |
| Fujitsu             | 3         | 3      | 0.53%   |
| Unknown             | 3         | 3      | 0.53%   |
| SPCC                | 2         | 2      | 0.36%   |
| Silicon Motion      | 2         | 2      | 0.36%   |
| Intenso             | 2         | 3      | 0.36%   |
| HUAWEI              | 2         | 2      | 0.36%   |
| Corsair             | 2         | 3      | 0.36%   |
| BR                  | 2         | 2      | 0.36%   |
| W800SH              | 1         | 1      | 0.18%   |
| Unknown (583)       | 1         | 1      | 0.18%   |
| Transcend           | 1         | 1      | 0.18%   |
| S3+                 | 1         | 1      | 0.18%   |
| RZX                 | 1         | 1      | 0.18%   |
| ROG                 | 1         | 1      | 0.18%   |
| Plextor             | 1         | 1      | 0.18%   |
| Patriot             | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB              | 10        | 1.62%   |
| Unknown SD/MMC/MS PRO 64GB          | 7         | 1.13%   |
| Toshiba MQ01ABF050 500GB            | 7         | 1.13%   |
| Toshiba MQ01ABD100 1TB              | 7         | 1.13%   |
| Samsung SSD 860 EVO 500GB           | 7         | 1.13%   |
| Toshiba DT01ACA200 2TB              | 6         | 0.97%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 5         | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 0.81%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 0.81%   |
| Kingston NVMe SSD Drive 512GB       | 5         | 0.81%   |
| HGST HTS721010A9E630 1TB            | 5         | 0.81%   |
| HGST HTS541010A9E680 1TB            | 5         | 0.81%   |
| Unknown MMC Card  32GB              | 4         | 0.65%   |
| Seagate ST31000528AS 1TB            | 4         | 0.65%   |
| SanDisk SSD PLUS 1000GB             | 4         | 0.65%   |
| Samsung SSD 850 EVO 250GB           | 4         | 0.65%   |
| Intel HBRPEKNX0202AH 512GB          | 4         | 0.65%   |
| WDC WD5000AADS-00S9B0 500GB         | 3         | 0.48%   |
| WDC WD10SPZX-75Z10T2 1TB            | 3         | 0.48%   |
| Toshiba MQ01ABD075 752GB            | 3         | 0.48%   |
| Toshiba DT01ACA100 1TB              | 3         | 0.48%   |
| Seagate ST9250315AS 250GB           | 3         | 0.48%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 0.48%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.48%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 0.48%   |
| Seagate ST250DM000-1BD141 250GB     | 3         | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 0.48%   |
| Seagate Expansion+ 2TB              | 3         | 0.48%   |
| SanDisk NVMe SSD Drive 1TB          | 3         | 0.48%   |
| Samsung SSD 980 1TB                 | 3         | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB        | 3         | 0.48%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.48%   |
| Samsung HM500JI 500GB               | 3         | 0.48%   |
| Kingston SA400S37480G 480GB SSD     | 3         | 0.48%   |
| JMicron Generic 500GB               | 3         | 0.48%   |
| Intel HBRPEKNX0202AHO 32GB          | 3         | 0.48%   |
| Unknown                             | 3         | 0.48%   |
| YMTC PC005 256GB                    | 2         | 0.32%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2         | 0.32%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 84     | 28.57%  |
| WDC                 | 61        | 79     | 26.41%  |
| Toshiba             | 52        | 56     | 22.51%  |
| Hitachi             | 19        | 22     | 8.23%   |
| HGST                | 14        | 17     | 6.06%   |
| Samsung Electronics | 10        | 12     | 4.33%   |
| Unknown             | 7         | 8      | 3.03%   |
| Fujitsu             | 1         | 1      | 0.43%   |
| ASMedia             | 1         | 1      | 0.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 46     | 21.18%  |
| Kingston            | 20        | 22     | 11.76%  |
| SanDisk             | 14        | 16     | 8.24%   |
| Crucial             | 14        | 19     | 8.24%   |
| WDC                 | 12        | 13     | 7.06%   |
| China               | 8         | 11     | 4.71%   |
| Micron Technology   | 5         | 5      | 2.94%   |
| Apple               | 5         | 5      | 2.94%   |
| Toshiba             | 4         | 5      | 2.35%   |
| Team                | 3         | 4      | 1.76%   |
| PNY                 | 3         | 3      | 1.76%   |
| LITEONIT            | 3         | 3      | 1.76%   |
| LITEON              | 3         | 3      | 1.76%   |
| JMicron Technology  | 3         | 3      | 1.76%   |
| Unknown             | 2         | 2      | 1.18%   |
| SPCC                | 2         | 2      | 1.18%   |
| Intenso             | 2         | 3      | 1.18%   |
| Intel               | 2         | 2      | 1.18%   |
| Fujitsu             | 2         | 2      | 1.18%   |
| Corsair             | 2         | 3      | 1.18%   |
| BR                  | 2         | 2      | 1.18%   |
| A-DATA Technology   | 2         | 2      | 1.18%   |
| Unknown             | 2         | 2      | 1.18%   |
| W800SH              | 1         | 1      | 0.59%   |
| Transcend           | 1         | 1      | 0.59%   |
| SK hynix            | 1         | 1      | 0.59%   |
| S3+                 | 1         | 1      | 0.59%   |
| RZX                 | 1         | 1      | 0.59%   |
| Plextor             | 1         | 1      | 0.59%   |
| Patriot             | 1         | 1      | 0.59%   |
| OCZ                 | 1         | 1      | 0.59%   |
| Netac               | 1         | 1      | 0.59%   |
| KingSpec            | 1         | 2      | 0.59%   |
| KingFast            | 1         | 1      | 0.59%   |
| HS-SSD-C100         | 1         | 1      | 0.59%   |
| Hewlett-Packard     | 1         | 1      | 0.59%   |
| GOODRAM             | 1         | 1      | 0.59%   |
| FORESEE             | 1         | 1      | 0.59%   |
| BHT                 | 1         | 1      | 0.59%   |
| ASMT                | 1         | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 200       | 280    | 39.22%  |
| SSD     | 152       | 198    | 29.8%   |
| NVMe    | 127       | 170    | 24.9%   |
| MMC     | 25        | 29     | 4.9%    |
| Unknown | 6         | 6      | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 295       | 454    | 62.11%  |
| NVMe | 127       | 169    | 26.74%  |
| SAS  | 28        | 31     | 5.89%   |
| MMC  | 25        | 29     | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 213       | 306    | 58.84%  |
| 0.51-1.0   | 121       | 138    | 33.43%  |
| 1.01-2.0   | 22        | 28     | 6.08%   |
| 3.01-4.0   | 3         | 3      | 0.83%   |
| 4.01-10.0  | 2         | 2      | 0.55%   |
| 2.01-3.0   | 1         | 1      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 102       | 24.46%  |
| 101-250        | 83        | 19.9%   |
| 501-1000       | 71        | 17.03%  |
| 1001-2000      | 52        | 12.47%  |
| Unknown        | 43        | 10.31%  |
| 51-100         | 22        | 5.28%   |
| 21-50          | 16        | 3.84%   |
| 1-20           | 11        | 2.64%   |
| 2001-3000      | 9         | 2.16%   |
| More than 3000 | 8         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 129       | 30.28%  |
| 51-100         | 69        | 16.2%   |
| 1-20           | 62        | 14.55%  |
| 101-250        | 60        | 14.08%  |
| Unknown        | 43        | 10.09%  |
| 251-500        | 37        | 8.69%   |
| 501-1000       | 16        | 3.76%   |
| 1001-2000      | 4         | 0.94%   |
| More than 3000 | 3         | 0.7%    |
| 0              | 2         | 0.47%   |
| 2001-3000      | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB                   | 3         | 3      | 4.84%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 3.23%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                  | 2         | 3      | 3.23%   |
| WDC WD5000AAKS-75V0A0 500GB                         | 1         | 1      | 1.61%   |
| WDC WD5000AADS-00S9B0 500GB                         | 1         | 1      | 1.61%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1      | 1.61%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 1.61%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 1.61%   |
| WDC WD2003FZEX-00Z4SA0 2TB                          | 1         | 1      | 1.61%   |
| WDC WD10JUCX-63WPNY0 1TB                            | 1         | 1      | 1.61%   |
| WDC WD10EZRX-00L4HB0 1TB                            | 1         | 1      | 1.61%   |
| WDC WD10EADS-22M2B0 1TB                             | 1         | 1      | 1.61%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 1.61%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 1.61%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 1.61%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 1.61%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 1.61%   |
| Seagate ST500NM0011 500GB                           | 1         | 1      | 1.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 1.61%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 1.61%   |
| Seagate ST3320418AS 320GB                           | 1         | 1      | 1.61%   |
| Seagate ST3250824AS 250GB                           | 1         | 1      | 1.61%   |
| Seagate ST320LT007-9ZV142 320GB                     | 1         | 1      | 1.61%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 1.61%   |
| Seagate ST3160215AS 160GB                           | 1         | 1      | 1.61%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 1.61%   |
| Seagate ST250DM000-1BD141 250GB                     | 1         | 1      | 1.61%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 1.61%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 1         | 2      | 1.61%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 1.61%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 1.61%   |
| SanDisk SSD PLUS 480GB                              | 1         | 1      | 1.61%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1      | 1.61%   |
| SanDisk SD8SBAT256G1122 256GB SSD                   | 1         | 1      | 1.61%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 1.61%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 1.61%   |
| Samsung Electronics HD161HJ 160GB                   | 1         | 1      | 1.61%   |
| Samsung Electronics HD154UI 1TB                     | 1         | 1      | 1.61%   |
| Plextor PX-512M6Pro 512GB SSD                       | 1         | 1      | 1.61%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 1.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 17     | 23.33%  |
| WDC                 | 9         | 9      | 15%     |
| Samsung Electronics | 7         | 7      | 11.67%  |
| SanDisk             | 5         | 6      | 8.33%   |
| Hitachi             | 5         | 5      | 8.33%   |
| Toshiba             | 4         | 4      | 6.67%   |
| HGST                | 3         | 3      | 5%      |
| A-DATA Technology   | 3         | 3      | 5%      |
| SK hynix            | 1         | 1      | 1.67%   |
| Plextor             | 1         | 1      | 1.67%   |
| Micron Technology   | 1         | 1      | 1.67%   |
| LITEON              | 1         | 1      | 1.67%   |
| Kingston            | 1         | 1      | 1.67%   |
| Intel               | 1         | 1      | 1.67%   |
| Hewlett-Packard     | 1         | 1      | 1.67%   |
| Fujitsu             | 1         | 1      | 1.67%   |
| Crucial             | 1         | 1      | 1.67%   |
| Unknown             | 1         | 1      | 1.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 17     | 33.33%  |
| WDC                 | 9         | 9      | 21.43%  |
| Samsung Electronics | 6         | 6      | 14.29%  |
| Hitachi             | 5         | 5      | 11.9%   |
| Toshiba             | 4         | 4      | 9.52%   |
| HGST                | 3         | 3      | 7.14%   |
| Fujitsu             | 1         | 1      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 45     | 66.67%  |
| SSD  | 14        | 15     | 25.93%  |
| NVMe | 4         | 4      | 7.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1         | 1      | 50%     |
| Intenso SSD SATAIII 512GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Intenso | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 213       | 283    | 45.81%  |
| Detected | 200       | 334    | 43.01%  |
| Malfunc  | 50        | 64     | 10.75%  |
| Failed   | 2         | 2      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 287       | 58.81%  |
| AMD                          | 60        | 12.3%   |
| Samsung Electronics          | 41        | 8.4%    |
| SanDisk                      | 24        | 4.92%   |
| SK hynix                     | 13        | 2.66%   |
| Kingston Technology Company  | 12        | 2.46%   |
| Micron Technology            | 9         | 1.84%   |
| Nvidia                       | 8         | 1.64%   |
| Toshiba America Info Systems | 5         | 1.02%   |
| Silicon Motion               | 4         | 0.82%   |
| Phison Electronics           | 4         | 0.82%   |
| KIOXIA                       | 4         | 0.82%   |
| ASMedia Technology           | 4         | 0.82%   |
| Yangtze Memory Technologies  | 3         | 0.61%   |
| ADATA Technology             | 3         | 0.61%   |
| Micron/Crucial Technology    | 2         | 0.41%   |
| VIA Technologies             | 1         | 0.2%    |
| Realtek Semiconductor        | 1         | 0.2%    |
| Marvell Technology Group     | 1         | 0.2%    |
| JMicron Technology           | 1         | 0.2%    |
| Apple                        | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 42        | 7.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 29        | 5.21%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 24        | 4.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 23        | 4.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 23        | 4.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 20        | 3.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 18        | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 13        | 2.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 11        | 1.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11        | 1.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 11        | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 1.97%   |
| Samsung NVMe SSD Controller 980                                                         | 10        | 1.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 1.8%    |
| Micron NVMe Storage Controller                                                          | 9         | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 1.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8         | 1.44%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 1.26%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 6         | 1.08%   |
| Intel NVMe Controller                                                                   | 6         | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 6         | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 6         | 1.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6         | 1.08%   |
| SanDisk NVMe Controller                                                                 | 5         | 0.9%    |
| Kingston Company Company Non-Volatile memory controller                                 | 5         | 0.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 5         | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 0.9%    |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 5         | 0.9%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 5         | 0.9%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 5         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 5         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 0.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 0.9%    |
| SK hynix BC511                                                                          | 4         | 0.72%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4         | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 4         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 274       | 54.37%  |
| NVMe | 127       | 25.2%   |
| RAID | 53        | 10.52%  |
| IDE  | 50        | 9.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 329       | 81.23%  |
| AMD    | 75        | 18.52%  |
| ARM    | 1         | 0.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 10        | 2.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 9         | 2.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 8         | 1.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 8         | 1.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 7         | 1.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 5         | 1.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 5         | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 5         | 1.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 1.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 4         | 0.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 4         | 0.99%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 0.99%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 4         | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 0.99%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 4         | 0.99%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 4         | 0.99%   |
| Intel 12th Gen Core i7-12700H               | 4         | 0.99%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3         | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 3         | 0.74%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3         | 0.74%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 0.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 3         | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 0.74%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 3         | 0.74%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 3         | 0.74%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 3         | 0.74%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 3         | 0.74%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 0.74%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 0.74%   |
| Intel 12th Gen Core i5-12500H               | 3         | 0.74%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 3         | 0.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 3         | 0.74%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 3         | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 3         | 0.74%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 2         | 0.49%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2         | 0.49%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 2         | 0.49%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 2         | 0.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 99        | 24.44%  |
| Intel Core i7           | 90        | 22.22%  |
| Other                   | 46        | 11.36%  |
| Intel Core i3           | 37        | 9.14%   |
| Intel Celeron           | 16        | 3.95%   |
| AMD Ryzen 7             | 16        | 3.95%   |
| AMD Ryzen 5             | 15        | 3.7%    |
| Intel Core 2 Duo        | 14        | 3.46%   |
| AMD A6                  | 8         | 1.98%   |
| Intel Pentium           | 7         | 1.73%   |
| Intel Xeon              | 5         | 1.23%   |
| AMD Ryzen 3             | 5         | 1.23%   |
| AMD FX                  | 5         | 1.23%   |
| Intel Pentium Dual-Core | 4         | 0.99%   |
| Intel Core 2            | 4         | 0.99%   |
| Intel Atom              | 3         | 0.74%   |
| AMD E1                  | 3         | 0.74%   |
| AMD A4                  | 3         | 0.74%   |
| Intel Pentium Silver    | 2         | 0.49%   |
| Intel Core 2 Quad       | 2         | 0.49%   |
| AMD Phenom II X4        | 2         | 0.49%   |
| AMD Athlon II X2        | 2         | 0.49%   |
| AMD A8                  | 2         | 0.49%   |
| AMD A10                 | 2         | 0.49%   |
| Intel Pentium Dual      | 1         | 0.25%   |
| Intel Core M            | 1         | 0.25%   |
| Intel Core i9           | 1         | 0.25%   |
| Intel Core 2 Extreme    | 1         | 0.25%   |
| AMD Ryzen Threadripper  | 1         | 0.25%   |
| AMD Ryzen 9             | 1         | 0.25%   |
| AMD Phenom              | 1         | 0.25%   |
| AMD E2                  | 1         | 0.25%   |
| AMD E                   | 1         | 0.25%   |
| AMD C-50                | 1         | 0.25%   |
| AMD Athlon X2           | 1         | 0.25%   |
| AMD Athlon 64 X2        | 1         | 0.25%   |
| AMD Athlon 64           | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 187       | 46.17%  |
| 4      | 139       | 34.32%  |
| 6      | 32        | 7.9%    |
| 8      | 22        | 5.43%   |
| 12     | 9         | 2.22%   |
| 14     | 5         | 1.23%   |
| 1      | 5         | 1.23%   |
| 10     | 4         | 0.99%   |
| 3      | 2         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 404       | 99.75%  |
| 2      | 1         | 0.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 282       | 69.63%  |
| 1      | 123       | 30.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 400       | 98.77%  |
| Unknown        | 5         | 1.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 178       | 42.69%  |
| 0x206a7    | 26        | 6.24%   |
| 0x306a9    | 17        | 4.08%   |
| 0x806c1    | 15        | 3.6%    |
| 0x906a3    | 11        | 2.64%   |
| 0x806ec    | 11        | 2.64%   |
| 0x406e3    | 11        | 2.64%   |
| 0x906ea    | 9         | 2.16%   |
| 0x806e9    | 9         | 2.16%   |
| 0x306c3    | 9         | 2.16%   |
| 0xa0652    | 8         | 1.92%   |
| 0x906e9    | 8         | 1.92%   |
| 0x806ea    | 8         | 1.92%   |
| 0x40651    | 7         | 1.68%   |
| 0x706a8    | 6         | 1.44%   |
| 0x1067a    | 6         | 1.44%   |
| 0x706e5    | 5         | 1.2%    |
| 0x6f6      | 4         | 0.96%   |
| 0x08108109 | 4         | 0.96%   |
| 0x906a4    | 3         | 0.72%   |
| 0x806d1    | 3         | 0.72%   |
| 0x406c4    | 3         | 0.72%   |
| 0x306d4    | 3         | 0.72%   |
| 0x0a50000c | 3         | 0.72%   |
| 0x08600106 | 3         | 0.72%   |
| 0x07030105 | 3         | 0.72%   |
| 0x06006705 | 3         | 0.72%   |
| 0x906ed    | 2         | 0.48%   |
| 0x806eb    | 2         | 0.48%   |
| 0x6fd      | 2         | 0.48%   |
| 0x08701021 | 2         | 0.48%   |
| 0x08608103 | 2         | 0.48%   |
| 0x08001138 | 2         | 0.48%   |
| 0x06001119 | 2         | 0.48%   |
| 0x06000852 | 2         | 0.48%   |
| 0x03000027 | 2         | 0.48%   |
| 0x010000c8 | 2         | 0.48%   |
| 0xa0660    | 1         | 0.24%   |
| 0xa0655    | 1         | 0.24%   |
| 0x90672    | 1         | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 75        | 18.52%  |
| SandyBridge      | 40        | 9.88%   |
| Haswell          | 33        | 8.15%   |
| IvyBridge        | 28        | 6.91%   |
| Skylake          | 23        | 5.68%   |
| TigerLake        | 22        | 5.43%   |
| Penryn           | 19        | 4.69%   |
| Alderlake Hybrid | 14        | 3.46%   |
| Broadwell        | 13        | 3.21%   |
| CometLake        | 12        | 2.96%   |
| Unknown          | 11        | 2.72%   |
| Silvermont       | 10        | 2.47%   |
| Piledriver       | 10        | 2.47%   |
| Core             | 10        | 2.47%   |
| Zen+             | 9         | 2.22%   |
| Zen 2            | 9         | 2.22%   |
| Icelake          | 8         | 1.98%   |
| Goldmont plus    | 8         | 1.98%   |
| Zen 3            | 7         | 1.73%   |
| Zen              | 7         | 1.73%   |
| Westmere         | 6         | 1.48%   |
| K10              | 6         | 1.48%   |
| Excavator        | 6         | 1.48%   |
| Puma             | 3         | 0.74%   |
| Nehalem          | 3         | 0.74%   |
| K10 Llano        | 3         | 0.74%   |
| Jaguar           | 3         | 0.74%   |
| K8 Hammer        | 2         | 0.49%   |
| Bobcat           | 2         | 0.49%   |
| Steamroller      | 1         | 0.25%   |
| K8 & K10 hybrid  | 1         | 0.25%   |
| Goldmont         | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 283       | 54.74%  |
| Nvidia | 138       | 26.69%  |
| AMD    | 96        | 18.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 34        | 6.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 4.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 3.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 3.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 2.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 2.87%   |
| Intel UHD Graphics 620                                                                   | 12        | 2.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.1%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 11        | 2.1%    |
| Intel HD Graphics 5500                                                                   | 10        | 1.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.91%   |
| Intel HD Graphics 620                                                                    | 9         | 1.72%   |
| Intel HD Graphics 630                                                                    | 8         | 1.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.15%   |
| AMD Renoir                                                                               | 6         | 1.15%   |
| AMD Lucienne                                                                             | 6         | 1.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.15%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 0.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 0.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 0.96%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.96%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.96%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.76%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.76%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 4         | 0.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.76%   |
| Intel HD Graphics 530                                                                    | 4         | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.76%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 0.76%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.57%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 179       | 43.98%  |
| Intel + Nvidia | 79        | 19.41%  |
| 1 x AMD        | 70        | 17.2%   |
| 1 x Nvidia     | 51        | 12.53%  |
| Intel + AMD    | 17        | 4.18%   |
| AMD + Nvidia   | 8         | 1.97%   |
| Other          | 1         | 0.25%   |
| 2 x Nvidia     | 1         | 0.25%   |
| 2 x AMD        | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 355       | 87.22%  |
| Proprietary | 45        | 11.06%  |
| Unknown     | 7         | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 301       | 73.06%  |
| 1.01-2.0   | 30        | 7.28%   |
| 0.51-1.0   | 24        | 5.83%   |
| 3.01-4.0   | 23        | 5.58%   |
| 0.01-0.5   | 20        | 4.85%   |
| 7.01-8.0   | 8         | 1.94%   |
| 5.01-6.0   | 4         | 0.97%   |
| 2.01-3.0   | 2         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 72        | 16.07%  |
| LG Display              | 58        | 12.95%  |
| BOE                     | 56        | 12.5%   |
| Samsung Electronics     | 52        | 11.61%  |
| Chimei Innolux          | 41        | 9.15%   |
| Dell                    | 16        | 3.57%   |
| Apple                   | 13        | 2.9%    |
| Acer                    | 10        | 2.23%   |
| Hewlett-Packard         | 9         | 2.01%   |
| Chi Mei Optoelectronics | 8         | 1.79%   |
| BenQ                    | 8         | 1.79%   |
| Ancor Communications    | 8         | 1.79%   |
| Goldstar                | 7         | 1.56%   |
| Unknown                 | 6         | 1.34%   |
| Sharp                   | 6         | 1.34%   |
| Philips                 | 6         | 1.34%   |
| AOC                     | 6         | 1.34%   |
| Lenovo                  | 5         | 1.12%   |
| InfoVision              | 5         | 1.12%   |
| PANDA                   | 4         | 0.89%   |
| Panasonic               | 4         | 0.89%   |
| ViewSonic               | 3         | 0.67%   |
| Toshiba                 | 3         | 0.67%   |
| NEC Computers           | 3         | 0.67%   |
| Eizo                    | 3         | 0.67%   |
| AUS                     | 3         | 0.67%   |
| ___                     | 2         | 0.45%   |
| Vizio                   | 2         | 0.45%   |
| STD                     | 2         | 0.45%   |
| Sceptre Tech            | 2         | 0.45%   |
| Insignia                | 2         | 0.45%   |
| CSO                     | 2         | 0.45%   |
| VOR                     | 1         | 0.22%   |
| VIZ                     | 1         | 0.22%   |
| Unknown (AAA)           | 1         | 0.22%   |
| STA                     | 1         | 0.22%   |
| Sony                    | 1         | 0.22%   |
| Sceptre                 | 1         | 0.22%   |
| SANYO                   | 1         | 0.22%   |
| RIS                     | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 4         | 0.88%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 3         | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.66%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.66%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch          | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.66%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 3         | 0.66%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 0.66%   |
| ___ LCD TV ___9000 1360x768                                           | 2         | 0.44%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 2         | 0.44%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                      | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.44%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.44%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 2         | 0.44%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch          | 2         | 0.44%   |
| Panasonic TV MEIA08F 1920x540                                         | 2         | 0.44%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 2         | 0.44%   |
| NEC Computers EA243WM NEC6863 1920x1200 519x324mm 24.1-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 2         | 0.44%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 2         | 0.44%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 2         | 0.44%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 2         | 0.44%   |
| Dell P2210 DEL404C 1680x1050 474x296mm 22.0-inch                      | 2         | 0.44%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.44%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 2         | 0.44%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                 | 2         | 0.44%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 0.44%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 0.44%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                     | 2         | 0.44%   |
| AUS LCD Monitor VG245 1920x1080                                       | 2         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 197       | 46.03%  |
| 1366x768 (WXGA)    | 105       | 24.53%  |
| 1600x900 (HD+)     | 17        | 3.97%   |
| 1680x1050 (WSXGA+) | 15        | 3.5%    |
| 3840x2160 (4K)     | 12        | 2.8%    |
| 1280x800 (WXGA)    | 12        | 2.8%    |
| 1440x900 (WXGA+)   | 11        | 2.57%   |
| 1280x1024 (SXGA)   | 9         | 2.1%    |
| 2560x1440 (QHD)    | 7         | 1.64%   |
| 1920x1200 (WUXGA)  | 7         | 1.64%   |
| 1360x768           | 6         | 1.4%    |
| 2160x1440          | 4         | 0.93%   |
| 2880x1800          | 3         | 0.7%    |
| 2560x1600          | 3         | 0.7%    |
| 2560x1080          | 3         | 0.7%    |
| 1920x540           | 3         | 0.7%    |
| Unknown            | 3         | 0.7%    |
| 3840x1080          | 2         | 0.47%   |
| 3200x1080          | 2         | 0.47%   |
| 1280x720 (HD)      | 2         | 0.47%   |
| 1024x768 (XGA)     | 2         | 0.47%   |
| 3840x2400          | 1         | 0.23%   |
| 2240x1400          | 1         | 0.23%   |
| 1920x515           | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 144       | 32.14%  |
| 14      | 47        | 10.49%  |
| 13      | 47        | 10.49%  |
| 17      | 33        | 7.37%   |
| 24      | 24        | 5.36%   |
| Unknown | 21        | 4.69%   |
| 27      | 19        | 4.24%   |
| 23      | 16        | 3.57%   |
| 12      | 14        | 3.13%   |
| 21      | 12        | 2.68%   |
| 31      | 11        | 2.46%   |
| 22      | 11        | 2.46%   |
| 19      | 8         | 1.79%   |
| 11      | 7         | 1.56%   |
| 32      | 6         | 1.34%   |
| 16      | 6         | 1.34%   |
| 40      | 4         | 0.89%   |
| 72      | 3         | 0.67%   |
| 54      | 2         | 0.45%   |
| 48      | 2         | 0.45%   |
| 20      | 2         | 0.45%   |
| 18      | 2         | 0.45%   |
| 84      | 1         | 0.22%   |
| 52      | 1         | 0.22%   |
| 42      | 1         | 0.22%   |
| 41      | 1         | 0.22%   |
| 34      | 1         | 0.22%   |
| 29      | 1         | 0.22%   |
| 25      | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 222       | 50.11%  |
| 501-600     | 54        | 12.19%  |
| 201-300     | 43        | 9.71%   |
| 351-400     | 37        | 8.35%   |
| 401-500     | 31        | 7%      |
| Unknown     | 21        | 4.74%   |
| 601-700     | 13        | 2.93%   |
| 701-800     | 7         | 1.58%   |
| 1001-1500   | 5         | 1.13%   |
| 801-900     | 4         | 0.9%    |
| 1501-2000   | 4         | 0.9%    |
| 901-1000    | 2         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 325       | 79.46%  |
| 16/10   | 49        | 11.98%  |
| Unknown | 13        | 3.18%   |
| 5/4     | 8         | 1.96%   |
| 32/9    | 4         | 0.98%   |
| 4/3     | 3         | 0.73%   |
| 3/2     | 3         | 0.73%   |
| 21/9    | 2         | 0.49%   |
| 6/5     | 1         | 0.24%   |
| 3.73    | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 147       | 32.74%  |
| 81-90          | 75        | 16.7%   |
| 201-250        | 53        | 11.8%   |
| 121-130        | 25        | 5.57%   |
| Unknown        | 21        | 4.68%   |
| 71-80          | 20        | 4.45%   |
| 301-350        | 20        | 4.45%   |
| 351-500        | 18        | 4.01%   |
| 61-70          | 13        | 2.9%    |
| 151-200        | 13        | 2.9%    |
| 251-300        | 9         | 2%      |
| More than 1000 | 8         | 1.78%   |
| 51-60          | 7         | 1.56%   |
| 141-150        | 7         | 1.56%   |
| 501-1000       | 7         | 1.56%   |
| 131-140        | 3         | 0.67%   |
| 111-120        | 3         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 148       | 34.18%  |
| 101-120       | 113       | 26.1%   |
| 51-100        | 106       | 24.48%  |
| 161-240       | 26        | 6%      |
| Unknown       | 21        | 4.85%   |
| 1-50          | 11        | 2.54%   |
| More than 240 | 8         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 337       | 81.6%   |
| 2     | 61        | 14.77%  |
| 0     | 8         | 1.94%   |
| 3     | 7         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 228       | 32.71%  |
| Intel                                  | 211       | 30.27%  |
| Qualcomm Atheros                       | 71        | 10.19%  |
| Broadcom                               | 35        | 5.02%   |
| Ralink Technology                      | 16        | 2.3%    |
| TP-Link                                | 13        | 1.87%   |
| MediaTek                               | 12        | 1.72%   |
| Samsung Electronics                    | 11        | 1.58%   |
| Broadcom Limited                       | 11        | 1.58%   |
| Qualcomm Atheros Communications        | 9         | 1.29%   |
| Nvidia                                 | 7         | 1%      |
| NetGear                                | 6         | 0.86%   |
| Huawei Technologies                    | 6         | 0.86%   |
| Xiaomi                                 | 5         | 0.72%   |
| Ralink                                 | 5         | 0.72%   |
| ASUSTek Computer                       | 5         | 0.72%   |
| Microsoft                              | 4         | 0.57%   |
| Marvell Technology Group               | 4         | 0.57%   |
| Mercucys                               | 3         | 0.43%   |
| D-Link System                          | 3         | 0.43%   |
| vivo                                   | 2         | 0.29%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.29%   |
| Qualcomm                               | 2         | 0.29%   |
| OPPO Electronics                       | 2         | 0.29%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.29%   |
| Linksys                                | 2         | 0.29%   |
| Lenovo                                 | 2         | 0.29%   |
| Ericsson Business Mobile Networks      | 2         | 0.29%   |
| D-Link                                 | 2         | 0.29%   |
| ASIX Electronics                       | 2         | 0.29%   |
| Apple                                  | 2         | 0.29%   |
| ZyXEL Communications                   | 1         | 0.14%   |
| Sagem                                  | 1         | 0.14%   |
| JMicron Technology                     | 1         | 0.14%   |
| ICS Advent                             | 1         | 0.14%   |
| Gemtek                                 | 1         | 0.14%   |
| Fibocom                                | 1         | 0.14%   |
| DisplayLink                            | 1         | 0.14%   |
| Davicom Semiconductor                  | 1         | 0.14%   |
| Belkin Components                      | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 135       | 16.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 4.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23        | 2.81%   |
| Intel Wi-Fi 6 AX201                                               | 18        | 2.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 16        | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 13        | 1.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 13        | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 1.47%   |
| Intel Wireless 8265 / 8275                                        | 12        | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.34%   |
| Intel Wireless 7265                                               | 10        | 1.22%   |
| Intel Wireless 7260                                               | 10        | 1.22%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 1.22%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 9         | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                   | 9         | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 0.98%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 7         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 7         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.73%   |
| Realtek 802.11ac NIC                                              | 6         | 0.73%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 6         | 0.73%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.73%   |
| Intel Wireless 8260                                               | 6         | 0.73%   |
| Intel Wireless 3165                                               | 6         | 0.73%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.73%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.73%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 5         | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 5         | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.61%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 5         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.61%   |
| Intel Wireless 3160                                               | 5         | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 186       | 42.08%  |
| Realtek Semiconductor           | 83        | 18.78%  |
| Qualcomm Atheros                | 53        | 11.99%  |
| Broadcom                        | 29        | 6.56%   |
| Ralink Technology               | 16        | 3.62%   |
| TP-Link                         | 13        | 2.94%   |
| Qualcomm Atheros Communications | 9         | 2.04%   |
| MediaTek                        | 9         | 2.04%   |
| Broadcom Limited                | 8         | 1.81%   |
| NetGear                         | 6         | 1.36%   |
| Ralink                          | 5         | 1.13%   |
| ASUSTek Computer                | 5         | 1.13%   |
| Microsoft                       | 4         | 0.9%    |
| Mercucys                        | 3         | 0.68%   |
| Marvell Technology Group        | 3         | 0.68%   |
| Linksys                         | 2         | 0.45%   |
| D-Link                          | 2         | 0.45%   |
| ZyXEL Communications            | 1         | 0.23%   |
| Sagem                           | 1         | 0.23%   |
| Gemtek                          | 1         | 0.23%   |
| Fibocom                         | 1         | 0.23%   |
| D-Link System                   | 1         | 0.23%   |
| Belkin Components               | 1         | 0.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 18        | 4.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 16        | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 2.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 13        | 2.93%   |
| Intel Wireless 8265 / 8275                                     | 12        | 2.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 2.48%   |
| Intel Wireless 7265                                            | 10        | 2.26%   |
| Intel Wireless 7260                                            | 10        | 2.26%   |
| Intel Wi-Fi 6 AX200                                            | 10        | 2.26%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 9         | 2.03%   |
| Qualcomm Atheros AR9271 802.11n                                | 9         | 2.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 2.03%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 2.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 2.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 8         | 1.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 7         | 1.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 7         | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 1.58%   |
| Realtek 802.11ac NIC                                           | 6         | 1.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 6         | 1.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.35%   |
| Intel Wireless 8260                                            | 6         | 1.35%   |
| Intel Wireless 3165                                            | 6         | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.13%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 5         | 1.13%   |
| Intel Wireless 3160                                            | 5         | 1.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 1.13%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 4         | 0.9%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 4         | 0.9%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.9%    |
| Ralink MT7601U Wireless Adapter                                | 4         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 0.9%    |
| Intel Centrino Advanced-N 6235                                 | 4         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 195       | 54.17%  |
| Intel                                  | 76        | 21.11%  |
| Qualcomm Atheros                       | 28        | 7.78%   |
| Samsung Electronics                    | 11        | 3.06%   |
| Broadcom                               | 11        | 3.06%   |
| Nvidia                                 | 7         | 1.94%   |
| Xiaomi                                 | 5         | 1.39%   |
| MediaTek                               | 3         | 0.83%   |
| Broadcom Limited                       | 3         | 0.83%   |
| Qualcomm                               | 2         | 0.56%   |
| OPPO Electronics                       | 2         | 0.56%   |
| Lenovo                                 | 2         | 0.56%   |
| Huawei Technologies                    | 2         | 0.56%   |
| D-Link System                          | 2         | 0.56%   |
| ASIX Electronics                       | 2         | 0.56%   |
| Apple                                  | 2         | 0.56%   |
| vivo                                   | 1         | 0.28%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.28%   |
| Marvell Technology Group               | 1         | 0.28%   |
| JMicron Technology                     | 1         | 0.28%   |
| ICS Advent                             | 1         | 0.28%   |
| DisplayLink                            | 1         | 0.28%   |
| Davicom Semiconductor                  | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 135       | 36.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 9.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23        | 6.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 3.29%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 1.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 1.64%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.64%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 1.64%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 5         | 1.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 1.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1.1%    |
| Intel I211 Gigabit Network Connection                             | 4         | 1.1%    |
| Intel Ethernet Connection I217-V                                  | 4         | 1.1%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.82%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.82%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.82%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.55%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.55%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.55%   |
| OPPO RMX3263                                                      | 2         | 0.55%   |
| MediaTek U318AA                                                   | 2         | 0.55%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.55%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.55%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.55%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 375       | 52.23%  |
| Ethernet | 332       | 46.24%  |
| Modem    | 6         | 0.84%   |
| Unknown  | 5         | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 287       | 67.37%  |
| Ethernet | 137       | 32.16%  |
| Unknown  | 2         | 0.47%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 236       | 58.13%  |
| 1     | 154       | 37.93%  |
| 0     | 8         | 1.97%   |
| 3     | 7         | 1.72%   |
| 4     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 331       | 80.54%  |
| Yes     | 79        | 19.22%  |
| Unknown | 1         | 0.24%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 141       | 49.82%  |
| Qualcomm Atheros Communications | 28        | 9.89%   |
| Realtek Semiconductor           | 26        | 9.19%   |
| Broadcom                        | 16        | 5.65%   |
| Cambridge Silicon Radio         | 12        | 4.24%   |
| Apple                           | 12        | 4.24%   |
| IMC Networks                    | 10        | 3.53%   |
| Foxconn / Hon Hai               | 9         | 3.18%   |
| Lite-On Technology              | 8         | 2.83%   |
| Dell                            | 5         | 1.77%   |
| Toshiba                         | 3         | 1.06%   |
| MediaTek                        | 3         | 1.06%   |
| Marvell Semiconductor           | 3         | 1.06%   |
| Ralink                          | 2         | 0.71%   |
| TP-Link                         | 1         | 0.35%   |
| Realtek                         | 1         | 0.35%   |
| Dynex                           | 1         | 0.35%   |
| ASUSTek Computer                | 1         | 0.35%   |
| Alps Electric                   | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 48        | 16.96%  |
| Intel AX201 Bluetooth                                                               | 38        | 13.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 25        | 8.83%   |
| Realtek Bluetooth Radio                                                             | 15        | 5.3%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 4.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 12        | 4.24%   |
| Intel AX200 Bluetooth                                                               | 9         | 3.18%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 2.83%   |
| Intel Bluetooth Device                                                              | 6         | 2.12%   |
| Apple Bluetooth Host Controller                                                     | 5         | 1.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.41%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.41%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.41%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.41%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 1.41%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 1.41%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 1.41%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 1.06%   |
| MediaTek Wireless_Device                                                            | 3         | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.06%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.06%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.06%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.06%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.06%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.06%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 1.06%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.71%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.71%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.71%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.71%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.71%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 2         | 0.71%   |
| Lite-On Wireless_Device                                                             | 2         | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.71%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.71%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.71%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.71%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.35%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 319       | 61.46%  |
| Nvidia                 | 93        | 17.92%  |
| AMD                    | 89        | 17.15%  |
| C-Media Electronics    | 4         | 0.77%   |
| Logitech               | 2         | 0.39%   |
| JMTek                  | 2         | 0.39%   |
| Yamaha                 | 1         | 0.19%   |
| Tenx Technology        | 1         | 0.19%   |
| SteelSeries ApS        | 1         | 0.19%   |
| Samson Technologies    | 1         | 0.19%   |
| Lenovo                 | 1         | 0.19%   |
| GYROCOM C&C            | 1         | 0.19%   |
| Guillemot              | 1         | 0.19%   |
| GN Netcom              | 1         | 0.19%   |
| Generalplus Technology | 1         | 0.19%   |
| Apple                  | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 38        | 6.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 36        | 5.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 32        | 5.16%   |
| AMD Family 17h/19h HD Audio Controller                                     | 25        | 4.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 22        | 3.55%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 2.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16        | 2.58%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 2.58%   |
| AMD FCH Azalia Controller                                                  | 16        | 2.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 15        | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 2.26%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 14        | 2.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 2.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 2.1%    |
| Intel Broadwell-U Audio Controller                                         | 13        | 2.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13        | 2.1%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 12        | 1.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10        | 1.61%   |
| Intel Comet Lake PCH cAVS                                                  | 10        | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 1.45%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.13%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 1.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.13%   |
| AMD Kabini HDMI/DP Audio                                                   | 7         | 1.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7         | 1.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.97%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 0.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 0.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 0.97%   |
| Nvidia Audio device                                                        | 5         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.81%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 0.81%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 82        | 26.54%  |
| SK hynix            | 49        | 15.86%  |
| Micron Technology   | 48        | 15.53%  |
| Unknown             | 23        | 7.44%   |
| Crucial             | 22        | 7.12%   |
| Kingston            | 19        | 6.15%   |
| Corsair             | 10        | 3.24%   |
| Elpida              | 8         | 2.59%   |
| Ramaxel Technology  | 7         | 2.27%   |
| A-DATA Technology   | 6         | 1.94%   |
| Unknown (ABCD)      | 5         | 1.62%   |
| Nanya Technology    | 5         | 1.62%   |
| G.Skill             | 5         | 1.62%   |
| Team                | 3         | 0.97%   |
| Transcend           | 2         | 0.65%   |
| Smart               | 2         | 0.65%   |
| PNY                 | 2         | 0.65%   |
| Unifosa             | 1         | 0.32%   |
| Timetec             | 1         | 0.32%   |
| Teikon              | 1         | 0.32%   |
| Silicon Power       | 1         | 0.32%   |
| Saikano             | 1         | 0.32%   |
| S                   | 1         | 0.32%   |
| Patriot             | 1         | 0.32%   |
| fef5                | 1         | 0.32%   |
| ChangXin Memory     | 1         | 0.32%   |
| Avant               | 1         | 0.32%   |
| AMD                 | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 2.16%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.23%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.23%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 1.23%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.93%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.93%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.93%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.93%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.93%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.93%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.93%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.93%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.62%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 2         | 0.62%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.62%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 2         | 0.62%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 0.62%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.62%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.62%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.62%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.62%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.62%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.62%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.62%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.62%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.62%   |
| Samsung RAM M4 70T2953CZ3-CE6 1024MB SODIMM DDR2 667MT/s         | 2         | 0.62%   |
| Samsung RAM K4AAG165WA-BCWE 8GB SODIMM DDR4 3200MT/s             | 2         | 0.62%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 0.62%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 121       | 45.15%  |
| DDR3    | 96        | 35.82%  |
| LPDDR4  | 16        | 5.97%   |
| LPDDR3  | 9         | 3.36%   |
| DDR2    | 8         | 2.99%   |
| Unknown | 8         | 2.99%   |
| DDR5    | 4         | 1.49%   |
| SDRAM   | 3         | 1.12%   |
| LPDDR5  | 2         | 0.75%   |
| DDR     | 1         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 193       | 72.56%  |
| DIMM         | 47        | 17.67%  |
| Row Of Chips | 23        | 8.65%   |
| Unknown      | 2         | 0.75%   |
| Chip         | 1         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 109       | 38.25%  |
| 4096  | 91        | 31.93%  |
| 16384 | 33        | 11.58%  |
| 2048  | 33        | 11.58%  |
| 1024  | 12        | 4.21%   |
| 32768 | 7         | 2.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 64        | 21.92%  |
| 2667    | 57        | 19.52%  |
| 3200    | 45        | 15.41%  |
| 2400    | 25        | 8.56%   |
| 1334    | 16        | 5.48%   |
| 2133    | 13        | 4.45%   |
| 1333    | 13        | 4.45%   |
| 1867    | 7         | 2.4%    |
| 4800    | 5         | 1.71%   |
| Unknown | 5         | 1.71%   |
| 3600    | 4         | 1.37%   |
| 3266    | 4         | 1.37%   |
| 1067    | 4         | 1.37%   |
| 1066    | 4         | 1.37%   |
| 4267    | 3         | 1.03%   |
| 800     | 3         | 1.03%   |
| 667     | 3         | 1.03%   |
| 6400    | 2         | 0.68%   |
| 3733    | 2         | 0.68%   |
| 3000    | 2         | 0.68%   |
| 8400    | 1         | 0.34%   |
| 3466    | 1         | 0.34%   |
| 3100    | 1         | 0.34%   |
| 2666    | 1         | 0.34%   |
| 2200    | 1         | 0.34%   |
| 2048    | 1         | 0.34%   |
| 1866    | 1         | 0.34%   |
| 1800    | 1         | 0.34%   |
| 975     | 1         | 0.34%   |
| 533     | 1         | 0.34%   |
| 400     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 25%     |
| Hewlett-Packard    | 1         | 25%     |
| Dymo-CoStar        | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Seiko Epson L120 Series      | 1         | 25%     |
| HP OfficeJet Pro 7720 series | 1         | 25%     |
| Dymo-CoStar LabelWriter 450  | 1         | 25%     |
| Brother HL-1210W series      | 1         | 25%     |

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


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 77        | 26.46%  |
| IMC Networks                           | 30        | 10.31%  |
| Acer                                   | 28        | 9.62%   |
| Microdia                               | 23        | 7.9%    |
| Realtek Semiconductor                  | 18        | 6.19%   |
| Sunplus Innovation Technology          | 16        | 5.5%    |
| Quanta                                 | 15        | 5.15%   |
| Apple                                  | 14        | 4.81%   |
| Syntek                                 | 7         | 2.41%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.41%   |
| Logitech                               | 6         | 2.06%   |
| Suyin                                  | 5         | 1.72%   |
| Ricoh                                  | 5         | 1.72%   |
| Luxvisions Innotech Limited            | 5         | 1.72%   |
| Samsung Electronics                    | 4         | 1.37%   |
| Sonix Technology                       | 3         | 1.03%   |
| Silicon Motion                         | 3         | 1.03%   |
| Lite-On Technology                     | 3         | 1.03%   |
| Alcor Micro                            | 3         | 1.03%   |
| USB Camera                             | 2         | 0.69%   |
| Microsoft                              | 2         | 0.69%   |
| LG Electronics                         | 2         | 0.69%   |
| Importek                               | 2         | 0.69%   |
| Creative Technology                    | 2         | 0.69%   |
| USB Camera CS                          | 1         | 0.34%   |
| Tobii Technology AB                    | 1         | 0.34%   |
| Teslong Camera                         | 1         | 0.34%   |
| Razer USA                              | 1         | 0.34%   |
| Primax Electronics                     | 1         | 0.34%   |
| Jieli Technology                       | 1         | 0.34%   |
| Goertek Electronics                    | 1         | 0.34%   |
| Bison Electronics                      | 1         | 0.34%   |
| ALi                                    | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 13        | 4.44%   |
| Realtek Integrated_Webcam_HD         | 11        | 3.75%   |
| IMC Networks Integrated Camera       | 9         | 3.07%   |
| IMC Networks USB2.0 HD UVC WebCam    | 8         | 2.73%   |
| Acer HD Webcam                       | 8         | 2.73%   |
| Syntek Integrated Camera             | 6         | 2.05%   |
| Microdia Integrated_Webcam_HD        | 6         | 2.05%   |
| Chicony HP Truevision HD             | 6         | 2.05%   |
| Chicony HD Webcam                    | 6         | 2.05%   |
| Chicony HD User Facing               | 6         | 2.05%   |
| Chicony USB2.0 Camera                | 5         | 1.71%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X      | 5         | 1.71%   |
| Sunplus Integrated_Webcam_HD         | 4         | 1.37%   |
| Samsung Galaxy A5 (MTP)              | 4         | 1.37%   |
| Microdia Webcam Vitade AF            | 4         | 1.37%   |
| Apple Built-in iSight                | 4         | 1.37%   |
| Acer SunplusIT Integrated Camera     | 4         | 1.37%   |
| Acer Integrated Camera               | 4         | 1.37%   |
| Acer EasyCamera                      | 4         | 1.37%   |
| Quanta HP TrueVision HD Camera       | 3         | 1.02%   |
| Quanta HD User Facing                | 3         | 1.02%   |
| Microdia PC Microscope camera        | 3         | 1.02%   |
| Microdia Integrated Webcam           | 3         | 1.02%   |
| IMC Networks HD Camera               | 3         | 1.02%   |
| Chicony USB2.0 HD UVC WebCam         | 3         | 1.02%   |
| Chicony HP HD Camera                 | 3         | 1.02%   |
| Chicony EasyCamera                   | 3         | 1.02%   |
| Apple FaceTime HD Camera             | 3         | 1.02%   |
| Alcor Micro USB 2.0 Camera           | 3         | 1.02%   |
| USB Camera USB Camera                | 2         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD | 2         | 0.68%   |
| Sunplus Laptop Integrated Webcam FHD | 2         | 0.68%   |
| Sunplus HD WebCam                    | 2         | 0.68%   |
| Sonix USB2.0 HD UVC WebCam           | 2         | 0.68%   |
| Realtek Integrated Webcam            | 2         | 0.68%   |
| Quanta VGA WebCam                    | 2         | 0.68%   |
| Quanta HP Wide Vision HD Camera      | 2         | 0.68%   |
| Microsoft LifeCam Rear               | 2         | 0.68%   |
| Microsoft LifeCam Front              | 2         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_HD | 2         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 36.36%  |
| Synaptics                  | 19        | 34.55%  |
| Shenzhen Goodix Technology | 6         | 10.91%  |
| Elan Microelectronics      | 4         | 7.27%   |
| Upek                       | 2         | 3.64%   |
| LighTuning Technology      | 2         | 3.64%   |
| AuthenTec                  | 2         | 3.64%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 5.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.45%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 5.45%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 5.45%   |
| Synaptics UWP WBDI                                                         | 3         | 5.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 5.45%   |
| Validity Sensors VFS491                                                    | 2         | 3.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.64%   |
| Synaptics  WBDI                                                            | 2         | 3.64%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.64%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.64%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.82%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.82%   |
| Synaptics WBDI                                                             | 1         | 1.82%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.82%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.82%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.82%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.82%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 11        | 57.89%  |
| Alcor Micro      | 5         | 26.32%  |
| SCM Microsystems | 1         | 5.26%   |
| OmniKey          | 1         | 5.26%   |
| O2 Micro         | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 36.84%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 26.32%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 15.79%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 5.26%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.26%   |
| Broadcom 5880                                                                | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 256       | 62.14%  |
| 1     | 128       | 31.07%  |
| 2     | 26        | 6.31%   |
| 3     | 2         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 56        | 31.46%  |
| Graphics card            | 32        | 17.98%  |
| Net/wireless             | 31        | 17.42%  |
| Chipcard                 | 17        | 9.55%   |
| Multimedia controller    | 15        | 8.43%   |
| Camera                   | 8         | 4.49%   |
| Storage                  | 6         | 3.37%   |
| Network                  | 3         | 1.69%   |
| Net/ethernet             | 2         | 1.12%   |
| Communication controller | 2         | 1.12%   |
| Bluetooth                | 2         | 1.12%   |
| Storage/raid             | 1         | 0.56%   |
| Sound                    | 1         | 0.56%   |
| Modem                    | 1         | 0.56%   |
| Card reader              | 1         | 0.56%   |

