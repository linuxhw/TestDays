Linux Mint - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Linux Mint.

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

Total: 8853

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 806A                        | [72e5b78d96](https://linux-hardware.org/?probe=72e5b78d96) | Dec 31, 2022 |
| Lenovo        | ThinkCentre M90 3692X01     | [702838caff](https://linux-hardware.org/?probe=702838caff) | Dec 31, 2022 |
| Dell          | 0JP3NX A01                  | [0749146323](https://linux-hardware.org/?probe=0749146323) | Dec 31, 2022 |
| Gigabyte      | B75M-D3V                    | [ce23d2f7cd](https://linux-hardware.org/?probe=ce23d2f7cd) | Dec 31, 2022 |
| ASRock        | B360M Performance           | [679d25f9be](https://linux-hardware.org/?probe=679d25f9be) | Dec 31, 2022 |
| Lenovo        | ThinkCentre M58p 9728W47    | [68bc291efd](https://linux-hardware.org/?probe=68bc291efd) | Dec 31, 2022 |
| AZW           | Green G2                    | [257948e699](https://linux-hardware.org/?probe=257948e699) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | [9d307c5f2f](https://linux-hardware.org/?probe=9d307c5f2f) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | [bc835cbca9](https://linux-hardware.org/?probe=bc835cbca9) | Dec 31, 2022 |
| Foxconn       | 2ADA                        | [92ce347d5f](https://linux-hardware.org/?probe=92ce347d5f) | Dec 31, 2022 |
| MSI           | Boston                      | [a5fd252dc2](https://linux-hardware.org/?probe=a5fd252dc2) | Dec 30, 2022 |
| Gigabyte      | H55M-USB3                   | [8fdced7ae8](https://linux-hardware.org/?probe=8fdced7ae8) | Dec 30, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [6de26a316e](https://linux-hardware.org/?probe=6de26a316e) | Dec 30, 2022 |
| AZW           | Green G2                    | [33f1a5c1a9](https://linux-hardware.org/?probe=33f1a5c1a9) | Dec 30, 2022 |
| ASRock        | X670E Steel Legend          | [6aa950201f](https://linux-hardware.org/?probe=6aa950201f) | Dec 30, 2022 |
| MSI           | 760GM-P23                   | [06c8e21a6f](https://linux-hardware.org/?probe=06c8e21a6f) | Dec 30, 2022 |
| ASUSTek       | P7P55D-E                    | [f725a0095a](https://linux-hardware.org/?probe=f725a0095a) | Dec 30, 2022 |
| ASRock        | H270 Pro4                   | [669d1fd05e](https://linux-hardware.org/?probe=669d1fd05e) | Dec 30, 2022 |
| HP            | 2B36                        | [4b363628a9](https://linux-hardware.org/?probe=4b363628a9) | Dec 30, 2022 |
| HP            | 2B36                        | [be6670b1ad](https://linux-hardware.org/?probe=be6670b1ad) | Dec 30, 2022 |
| Gigabyte      | H55M-USB3                   | [6621ba66ac](https://linux-hardware.org/?probe=6621ba66ac) | Dec 30, 2022 |
| MSI           | X570-A PRO                  | [7af9125172](https://linux-hardware.org/?probe=7af9125172) | Dec 29, 2022 |
| Dell          | 0UW457 A04                  | [047e7036d4](https://linux-hardware.org/?probe=047e7036d4) | Dec 29, 2022 |
| Gigabyte      | M61SME-S2L                  | [660194090d](https://linux-hardware.org/?probe=660194090d) | Dec 29, 2022 |
| Gigabyte      | M61SME-S2L                  | [7ba365cac3](https://linux-hardware.org/?probe=7ba365cac3) | Dec 29, 2022 |
| ASUSTek       | Z87M-PLUS                   | [6dac0c0943](https://linux-hardware.org/?probe=6dac0c0943) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2d47973101](https://linux-hardware.org/?probe=2d47973101) | Dec 29, 2022 |
| Gigabyte      | Z77M-D3H                    | [f20c6365d3](https://linux-hardware.org/?probe=f20c6365d3) | Dec 28, 2022 |
| Gigabyte      | A320M-H-CF                  | [83608f4248](https://linux-hardware.org/?probe=83608f4248) | Dec 28, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e9a313bb81](https://linux-hardware.org/?probe=e9a313bb81) | Dec 28, 2022 |
| Gigabyte      | Z370XP SLI-CF               | [be56999d2a](https://linux-hardware.org/?probe=be56999d2a) | Dec 28, 2022 |
| HP            | 339A                        | [eb2bb9bcec](https://linux-hardware.org/?probe=eb2bb9bcec) | Dec 28, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [d0969c6a4c](https://linux-hardware.org/?probe=d0969c6a4c) | Dec 28, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [8a4dce4662](https://linux-hardware.org/?probe=8a4dce4662) | Dec 28, 2022 |
| Dell          | 0D883F A06                  | [23c5689182](https://linux-hardware.org/?probe=23c5689182) | Dec 28, 2022 |
| Dell          | 0D883F A06                  | [8e9e780028](https://linux-hardware.org/?probe=8e9e780028) | Dec 28, 2022 |
| Dell          | 0JP3NX A01                  | [acbe3ce1ef](https://linux-hardware.org/?probe=acbe3ce1ef) | Dec 28, 2022 |
| Dell          | 0YXT71 A01                  | [ed5e31a6bc](https://linux-hardware.org/?probe=ed5e31a6bc) | Dec 28, 2022 |
| MSI           | MAG B550M MORTAR            | [bf50da5153](https://linux-hardware.org/?probe=bf50da5153) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [71bccea2dc](https://linux-hardware.org/?probe=71bccea2dc) | Dec 28, 2022 |
| ASRock        | H270 Pro4                   | [18c67453d3](https://linux-hardware.org/?probe=18c67453d3) | Dec 28, 2022 |
| ASRock        | H270 Pro4                   | [411b246a3f](https://linux-hardware.org/?probe=411b246a3f) | Dec 28, 2022 |
| Apple         | Mac-F221BEC8                | [85730ed1a1](https://linux-hardware.org/?probe=85730ed1a1) | Dec 28, 2022 |
| ASRock        | 4CoreDual-SATA2             | [05ae1afd3f](https://linux-hardware.org/?probe=05ae1afd3f) | Dec 28, 2022 |
| Apple         | Mac-F221BEC8                | [94ae481e51](https://linux-hardware.org/?probe=94ae481e51) | Dec 27, 2022 |
| HP            | 304Bh                       | [d85d0d4017](https://linux-hardware.org/?probe=d85d0d4017) | Dec 27, 2022 |
| MSI           | Z97 PC Mate                 | [defccc0ef1](https://linux-hardware.org/?probe=defccc0ef1) | Dec 27, 2022 |
| Unknown       | Unknown                     | [ccce0caf7e](https://linux-hardware.org/?probe=ccce0caf7e) | Dec 27, 2022 |
| ASUSTek       | PRIME X570-P                | [fba6e6e090](https://linux-hardware.org/?probe=fba6e6e090) | Dec 27, 2022 |
| Megaware      | MW-H61M-2H v1.3 - 17/07/... | [868a87a1f8](https://linux-hardware.org/?probe=868a87a1f8) | Dec 27, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [31f25029c1](https://linux-hardware.org/?probe=31f25029c1) | Dec 27, 2022 |
| Dell          | 040DDP A01                  | [92825b79ee](https://linux-hardware.org/?probe=92825b79ee) | Dec 27, 2022 |
| Gigabyte      | GA-890XA-UD3                | [492719506f](https://linux-hardware.org/?probe=492719506f) | Dec 27, 2022 |
| HP            | 304Bh                       | [02c61d35f2](https://linux-hardware.org/?probe=02c61d35f2) | Dec 27, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [f51a366bc2](https://linux-hardware.org/?probe=f51a366bc2) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [305018336b](https://linux-hardware.org/?probe=305018336b) | Dec 26, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [e8dce940d8](https://linux-hardware.org/?probe=e8dce940d8) | Dec 26, 2022 |
| ASUSTek       | M4A88T-V EVO/USB3           | [05163a2fb9](https://linux-hardware.org/?probe=05163a2fb9) | Dec 26, 2022 |
| ECS           | H81H3-WM                    | [6791862ef9](https://linux-hardware.org/?probe=6791862ef9) | Dec 25, 2022 |
| HP            | 1495                        | [681abdb8a2](https://linux-hardware.org/?probe=681abdb8a2) | Dec 25, 2022 |
| ASUSTek       | F1A55-M LX R2.0             | [177c5ee2a6](https://linux-hardware.org/?probe=177c5ee2a6) | Dec 25, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [cbbfeef21b](https://linux-hardware.org/?probe=cbbfeef21b) | Dec 25, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [30c464408a](https://linux-hardware.org/?probe=30c464408a) | Dec 25, 2022 |
| HP            | 8265                        | [30ff2fbdaa](https://linux-hardware.org/?probe=30ff2fbdaa) | Dec 25, 2022 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [384d09ccdb](https://linux-hardware.org/?probe=384d09ccdb) | Dec 25, 2022 |
| Dell          | 0DN075                      | [9fd08be389](https://linux-hardware.org/?probe=9fd08be389) | Dec 25, 2022 |
| HP            | 8265                        | [188eaf4f00](https://linux-hardware.org/?probe=188eaf4f00) | Dec 24, 2022 |
| ASRock        | FM2A78M-HD+ R2.0            | [ff69d47b58](https://linux-hardware.org/?probe=ff69d47b58) | Dec 24, 2022 |
| ASRock        | FM2A78M-HD+ R2.0            | [696403dae4](https://linux-hardware.org/?probe=696403dae4) | Dec 24, 2022 |
| ASUSTek       | P7P55D-E                    | [a6be229477](https://linux-hardware.org/?probe=a6be229477) | Dec 24, 2022 |
| AMI           | Cherry Trail FFD            | [7070bf387d](https://linux-hardware.org/?probe=7070bf387d) | Dec 24, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [03c35b7588](https://linux-hardware.org/?probe=03c35b7588) | Dec 24, 2022 |
| ASUSTek       | PRIME Z390-A                | [da48bed048](https://linux-hardware.org/?probe=da48bed048) | Dec 24, 2022 |
| HP            | 8061                        | [4427032526](https://linux-hardware.org/?probe=4427032526) | Dec 24, 2022 |
| MiTAC         | PD14RI                      | [eb02828e7c](https://linux-hardware.org/?probe=eb02828e7c) | Dec 24, 2022 |
| MSI           | H61M-P20                    | [07b5fe983c](https://linux-hardware.org/?probe=07b5fe983c) | Dec 24, 2022 |
| MSI           | H61M-P20                    | [e1d50cc8f4](https://linux-hardware.org/?probe=e1d50cc8f4) | Dec 24, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [568df9daf7](https://linux-hardware.org/?probe=568df9daf7) | Dec 23, 2022 |
| ASUSTek       | M2N-SLI DELUXE              | [0836c3b800](https://linux-hardware.org/?probe=0836c3b800) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [9e19c2db67](https://linux-hardware.org/?probe=9e19c2db67) | Dec 23, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [723811132a](https://linux-hardware.org/?probe=723811132a) | Dec 23, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [3073d2d4e1](https://linux-hardware.org/?probe=3073d2d4e1) | Dec 23, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [73c8ec2eb1](https://linux-hardware.org/?probe=73c8ec2eb1) | Dec 22, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [ec808658f8](https://linux-hardware.org/?probe=ec808658f8) | Dec 22, 2022 |
| Intel         | X99                         | [24e1c625cb](https://linux-hardware.org/?probe=24e1c625cb) | Dec 22, 2022 |
| Gigabyte      | GA-990FXA-D3                | [30822e6e18](https://linux-hardware.org/?probe=30822e6e18) | Dec 22, 2022 |
| Dell          | 0H4VK7 A01                  | [c2f0c73bec](https://linux-hardware.org/?probe=c2f0c73bec) | Dec 22, 2022 |
| ASUSTek       | Z170-A                      | [9790670c6f](https://linux-hardware.org/?probe=9790670c6f) | Dec 22, 2022 |
| HP            | 8027                        | [752200e795](https://linux-hardware.org/?probe=752200e795) | Dec 22, 2022 |
| ASUSTek       | Z87-K                       | [41fcdb5532](https://linux-hardware.org/?probe=41fcdb5532) | Dec 22, 2022 |
| HP            | 8265                        | [9050546a5b](https://linux-hardware.org/?probe=9050546a5b) | Dec 22, 2022 |
| Dell          | 0T10XW A00                  | [b8f7268dcf](https://linux-hardware.org/?probe=b8f7268dcf) | Dec 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [ec54aedcc6](https://linux-hardware.org/?probe=ec54aedcc6) | Dec 21, 2022 |
| Dell          | 0RY007                      | [0cdfef97e7](https://linux-hardware.org/?probe=0cdfef97e7) | Dec 21, 2022 |
| Dell          | 018D1Y A00                  | [d63c07df34](https://linux-hardware.org/?probe=d63c07df34) | Dec 21, 2022 |
| HP            | 339A                        | [77b8b56b9d](https://linux-hardware.org/?probe=77b8b56b9d) | Dec 21, 2022 |
| HP            | 3047h                       | [f5492c4ad4](https://linux-hardware.org/?probe=f5492c4ad4) | Dec 21, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [afc187a5af](https://linux-hardware.org/?probe=afc187a5af) | Dec 21, 2022 |
| Intel         | X99 V1.0                    | [20c96ed6dd](https://linux-hardware.org/?probe=20c96ed6dd) | Dec 21, 2022 |
| Intel         | B75                         | [368e71afd7](https://linux-hardware.org/?probe=368e71afd7) | Dec 21, 2022 |
| Gigabyte      | B85M-D3H                    | [0b63acf3b2](https://linux-hardware.org/?probe=0b63acf3b2) | Dec 20, 2022 |
| Foxconn       | 17A0                        | [58a3486afd](https://linux-hardware.org/?probe=58a3486afd) | Dec 20, 2022 |
| HP            | 806A                        | [2bd948ac57](https://linux-hardware.org/?probe=2bd948ac57) | Dec 20, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5d3e747abe](https://linux-hardware.org/?probe=5d3e747abe) | Dec 20, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a92a6ed3bb](https://linux-hardware.org/?probe=a92a6ed3bb) | Dec 20, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [47397487a7](https://linux-hardware.org/?probe=47397487a7) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [e954c9ca37](https://linux-hardware.org/?probe=e954c9ca37) | Dec 19, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [831f650b05](https://linux-hardware.org/?probe=831f650b05) | Dec 19, 2022 |
| AMI           | Cherry Trail CR             | [ad74aff6fa](https://linux-hardware.org/?probe=ad74aff6fa) | Dec 19, 2022 |
| HP            | 2AA7 H                      | [4da43e6303](https://linux-hardware.org/?probe=4da43e6303) | Dec 19, 2022 |
| HP            | 2AA7 H                      | [9d33375e52](https://linux-hardware.org/?probe=9d33375e52) | Dec 19, 2022 |
| Intel         | D34010WYK H14771-304        | [c47ff5ba34](https://linux-hardware.org/?probe=c47ff5ba34) | Dec 19, 2022 |
| HP            | 83EF                        | [755cb8dac5](https://linux-hardware.org/?probe=755cb8dac5) | Dec 19, 2022 |
| ASUSTek       | M2N-TE                      | [b67e414d65](https://linux-hardware.org/?probe=b67e414d65) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M70E 0830W4E    | [199c8776ef](https://linux-hardware.org/?probe=199c8776ef) | Dec 18, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [e8b08e9f68](https://linux-hardware.org/?probe=e8b08e9f68) | Dec 18, 2022 |
| Dell          | 018D1Y A00                  | [03db07e80d](https://linux-hardware.org/?probe=03db07e80d) | Dec 18, 2022 |
| ASUSTek       | PRIME B550M-A WIFI II       | [2d5d4c1d6b](https://linux-hardware.org/?probe=2d5d4c1d6b) | Dec 18, 2022 |
| ASRock        | Z77 Extreme4                | [ac3472dcd0](https://linux-hardware.org/?probe=ac3472dcd0) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [39bac65c16](https://linux-hardware.org/?probe=39bac65c16) | Dec 18, 2022 |
| HP            | ProLiant ML350 G6           | [3b242628e4](https://linux-hardware.org/?probe=3b242628e4) | Dec 18, 2022 |
| ASUSTek       | PRIME Z270-A                | [43da35f265](https://linux-hardware.org/?probe=43da35f265) | Dec 18, 2022 |
| ASUSTek       | PRIME Z270-A                | [8044fca8f3](https://linux-hardware.org/?probe=8044fca8f3) | Dec 18, 2022 |
| Dell          | 018D1Y A00                  | [b43ca20e72](https://linux-hardware.org/?probe=b43ca20e72) | Dec 18, 2022 |
| Supermicro    | X9SCL/X9SCM                 | [ff98a90e45](https://linux-hardware.org/?probe=ff98a90e45) | Dec 18, 2022 |
| ASUSTek       | P7H55D-M EVO                | [1e294ecd38](https://linux-hardware.org/?probe=1e294ecd38) | Dec 18, 2022 |
| AZW           | Green G2                    | [a0a0c95e0b](https://linux-hardware.org/?probe=a0a0c95e0b) | Dec 17, 2022 |
| Dell          | 018D1Y A00                  | [d2076f2a7a](https://linux-hardware.org/?probe=d2076f2a7a) | Dec 17, 2022 |
| ASRock        | 960GC-GS FX                 | [a61b5c0129](https://linux-hardware.org/?probe=a61b5c0129) | Dec 17, 2022 |
| HP            | 18E7                        | [31011a35a4](https://linux-hardware.org/?probe=31011a35a4) | Dec 17, 2022 |
| Acer          | Aspire XC-1660 V:1.1        | [88aa1f841a](https://linux-hardware.org/?probe=88aa1f841a) | Dec 17, 2022 |
| ASRock        | Z77 Extreme4                | [84c83fa399](https://linux-hardware.org/?probe=84c83fa399) | Dec 17, 2022 |
| Gigabyte      | Z390 UD                     | [3af8ddb8cc](https://linux-hardware.org/?probe=3af8ddb8cc) | Dec 17, 2022 |
| Foxconn       | 17A0                        | [be57227f43](https://linux-hardware.org/?probe=be57227f43) | Dec 17, 2022 |
| Dell          | 0WR7PY A01                  | [5c1e2b0030](https://linux-hardware.org/?probe=5c1e2b0030) | Dec 17, 2022 |
| HP            | 8027                        | [07834099d5](https://linux-hardware.org/?probe=07834099d5) | Dec 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [823a0ca3c4](https://linux-hardware.org/?probe=823a0ca3c4) | Dec 17, 2022 |
| Intel         | H55                         | [c034f3b3db](https://linux-hardware.org/?probe=c034f3b3db) | Dec 16, 2022 |
| Gigabyte      | B85-HD3                     | [d314ce4539](https://linux-hardware.org/?probe=d314ce4539) | Dec 16, 2022 |
| Gigabyte      | B85-HD3                     | [e87a16ee1f](https://linux-hardware.org/?probe=e87a16ee1f) | Dec 16, 2022 |
| HP            | 1998                        | [5c59186efc](https://linux-hardware.org/?probe=5c59186efc) | Dec 16, 2022 |
| ASUSTek       | P5LD2-VM                    | [b2ae663fec](https://linux-hardware.org/?probe=b2ae663fec) | Dec 16, 2022 |
| AZW           | Green G2                    | [2491cf766c](https://linux-hardware.org/?probe=2491cf766c) | Dec 16, 2022 |
| Foxconn       | 17A0                        | [b2185eeab5](https://linux-hardware.org/?probe=b2185eeab5) | Dec 16, 2022 |
| AZW           | Green G2                    | [58411901b6](https://linux-hardware.org/?probe=58411901b6) | Dec 16, 2022 |
| Gigabyte      | GA-M56S-S3                  | [077f863ca3](https://linux-hardware.org/?probe=077f863ca3) | Dec 15, 2022 |
| ASRock        | X570 Steel Legend           | [0de958194e](https://linux-hardware.org/?probe=0de958194e) | Dec 15, 2022 |
| Gigabyte      | B550M DS3H                  | [81092c4ca4](https://linux-hardware.org/?probe=81092c4ca4) | Dec 15, 2022 |
| Dell          | 0M5DCD A00                  | [5357f2124d](https://linux-hardware.org/?probe=5357f2124d) | Dec 14, 2022 |
| HP            | 843C                        | [e647aa1207](https://linux-hardware.org/?probe=e647aa1207) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | [a607679697](https://linux-hardware.org/?probe=a607679697) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | [9bd8fecf82](https://linux-hardware.org/?probe=9bd8fecf82) | Dec 14, 2022 |
| Gigabyte      | B75-D3V                     | [f46b869c82](https://linux-hardware.org/?probe=f46b869c82) | Dec 14, 2022 |
| Google        | Panther                     | [a46174ed14](https://linux-hardware.org/?probe=a46174ed14) | Dec 14, 2022 |
| VXL           | M6V90AI-VL                  | [a16094bb41](https://linux-hardware.org/?probe=a16094bb41) | Dec 14, 2022 |
| Gigabyte      | GA-970A-D3                  | [9bc1aec0dc](https://linux-hardware.org/?probe=9bc1aec0dc) | Dec 14, 2022 |
| Intel         | DP67BG AAG10491-401         | [3b1fe2cc85](https://linux-hardware.org/?probe=3b1fe2cc85) | Dec 13, 2022 |
| ECS           | GeForce7050M-M              | [118a28442e](https://linux-hardware.org/?probe=118a28442e) | Dec 13, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [70506a428c](https://linux-hardware.org/?probe=70506a428c) | Dec 13, 2022 |
| ASRock        | H510M-HDV                   | [16d5f27d87](https://linux-hardware.org/?probe=16d5f27d87) | Dec 13, 2022 |
| MSI           | Z490-A PRO                  | [8fc0ca8378](https://linux-hardware.org/?probe=8fc0ca8378) | Dec 12, 2022 |
| HP            | 1998                        | [358e1a1af1](https://linux-hardware.org/?probe=358e1a1af1) | Dec 12, 2022 |
| AMI           | Cherry Trail CR             | [868f4725db](https://linux-hardware.org/?probe=868f4725db) | Dec 12, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [259f85d65b](https://linux-hardware.org/?probe=259f85d65b) | Dec 12, 2022 |
| Biostar       | A960D+V2                    | [6dea2bd72f](https://linux-hardware.org/?probe=6dea2bd72f) | Dec 12, 2022 |
| ASRock        | N68C-S UCC                  | [c405e5bd16](https://linux-hardware.org/?probe=c405e5bd16) | Dec 12, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [9a73e431ee](https://linux-hardware.org/?probe=9a73e431ee) | Dec 12, 2022 |
| HP            | 339A                        | [63c184fafd](https://linux-hardware.org/?probe=63c184fafd) | Dec 12, 2022 |
| ASRock        | N68C-S UCC                  | [6fa4a67111](https://linux-hardware.org/?probe=6fa4a67111) | Dec 12, 2022 |
| Dell          | 042P49 A01                  | [fc5be35686](https://linux-hardware.org/?probe=fc5be35686) | Dec 12, 2022 |
| HP            | 1998                        | [935ab0a3a2](https://linux-hardware.org/?probe=935ab0a3a2) | Dec 11, 2022 |
| HP            | 1589                        | [4aa31e9d16](https://linux-hardware.org/?probe=4aa31e9d16) | Dec 11, 2022 |
| Gigabyte      | F2A88X-D3H                  | [31cd7cded9](https://linux-hardware.org/?probe=31cd7cded9) | Dec 11, 2022 |
| Biostar       | A520MH                      | [b6c4fdd80b](https://linux-hardware.org/?probe=b6c4fdd80b) | Dec 11, 2022 |
| Gigabyte      | P67A-D3-B3                  | [9ed715edc4](https://linux-hardware.org/?probe=9ed715edc4) | Dec 11, 2022 |
| Dell          | 0F896N A03                  | [8dec293f40](https://linux-hardware.org/?probe=8dec293f40) | Dec 11, 2022 |
| AZW           | Gemini T45                  | [e0b5dab1b4](https://linux-hardware.org/?probe=e0b5dab1b4) | Dec 11, 2022 |
| AZW           | Gemini T45                  | [d169b1be26](https://linux-hardware.org/?probe=d169b1be26) | Dec 11, 2022 |
| Intel         | DX58SO AAE29331-702         | [685274600b](https://linux-hardware.org/?probe=685274600b) | Dec 10, 2022 |
| ASRock        | Z270 Pro4                   | [9810ecf266](https://linux-hardware.org/?probe=9810ecf266) | Dec 10, 2022 |
| ASUSTek       | BM5242                      | [d37b75dc52](https://linux-hardware.org/?probe=d37b75dc52) | Dec 10, 2022 |
| ASUSTek       | BM5242                      | [7c17c8d773](https://linux-hardware.org/?probe=7c17c8d773) | Dec 10, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [830ec0e7be](https://linux-hardware.org/?probe=830ec0e7be) | Dec 10, 2022 |
| ASUSTek       | Z170M-PLUS/BR               | [62779a600c](https://linux-hardware.org/?probe=62779a600c) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [967204fede](https://linux-hardware.org/?probe=967204fede) | Dec 09, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [629f7c7977](https://linux-hardware.org/?probe=629f7c7977) | Dec 09, 2022 |
| ASUSTek       | Z170M-PLUS/BR               | [ac8d321e9a](https://linux-hardware.org/?probe=ac8d321e9a) | Dec 09, 2022 |
| Gigabyte      | EP45-DS4P                   | [5acdccf7c0](https://linux-hardware.org/?probe=5acdccf7c0) | Dec 09, 2022 |
| Dell          | 0JP3NX A01                  | [db2f15960f](https://linux-hardware.org/?probe=db2f15960f) | Dec 08, 2022 |
| Acer          | Aspire TC-780               | [a100b3cd38](https://linux-hardware.org/?probe=a100b3cd38) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [e6c64e15dd](https://linux-hardware.org/?probe=e6c64e15dd) | Dec 08, 2022 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | [3814024cdc](https://linux-hardware.org/?probe=3814024cdc) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [19986ba651](https://linux-hardware.org/?probe=19986ba651) | Dec 08, 2022 |
| Medion        | TJ4125                      | [62b9f7158b](https://linux-hardware.org/?probe=62b9f7158b) | Dec 08, 2022 |
| ASRock        | X570 Steel Legend           | [84c7e04946](https://linux-hardware.org/?probe=84c7e04946) | Dec 08, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [9ce2c75190](https://linux-hardware.org/?probe=9ce2c75190) | Dec 08, 2022 |
| PCWare        | IPMH61R3                    | [d216c11fea](https://linux-hardware.org/?probe=d216c11fea) | Dec 08, 2022 |
| Dell          | 0M5DCD A00                  | [db7ce2f1a1](https://linux-hardware.org/?probe=db7ce2f1a1) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [68004f52cd](https://linux-hardware.org/?probe=68004f52cd) | Dec 08, 2022 |
| ASUSTek       | F2A55                       | [a8ed6d4071](https://linux-hardware.org/?probe=a8ed6d4071) | Dec 08, 2022 |
| ASRock        | H61M-HVGS                   | [7bde3abe5d](https://linux-hardware.org/?probe=7bde3abe5d) | Dec 08, 2022 |
| Lenovo        | Annapurna CRB NOK           | [548e2f6cd0](https://linux-hardware.org/?probe=548e2f6cd0) | Dec 08, 2022 |
| HP            | 8643 SMVB                   | [7f0372385d](https://linux-hardware.org/?probe=7f0372385d) | Dec 07, 2022 |
| MSI           | H81M-P33                    | [9ba738605c](https://linux-hardware.org/?probe=9ba738605c) | Dec 07, 2022 |
| MSI           | H81M-P33                    | [bb540dbfb1](https://linux-hardware.org/?probe=bb540dbfb1) | Dec 07, 2022 |
| Foxconn       | 17A0                        | [2f3b2f9fbb](https://linux-hardware.org/?probe=2f3b2f9fbb) | Dec 07, 2022 |
| HP            | 8061                        | [6e4cb7cde8](https://linux-hardware.org/?probe=6e4cb7cde8) | Dec 07, 2022 |
| ASRock        | X570 Steel Legend           | [580fb6172f](https://linux-hardware.org/?probe=580fb6172f) | Dec 07, 2022 |
| Gigabyte      | B360N WIFI-CF               | [5abfdbdcba](https://linux-hardware.org/?probe=5abfdbdcba) | Dec 07, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [9d8dee4e41](https://linux-hardware.org/?probe=9d8dee4e41) | Dec 07, 2022 |
| Gigabyte      | X299 AORUS Gaming 7 Pro     | [2d095f898e](https://linux-hardware.org/?probe=2d095f898e) | Dec 07, 2022 |
| Pegatron      | 2AC3                        | [a2ef826e8b](https://linux-hardware.org/?probe=a2ef826e8b) | Dec 07, 2022 |
| Gigabyte      | X570 GAMING X               | [1d3a7d8bfb](https://linux-hardware.org/?probe=1d3a7d8bfb) | Dec 06, 2022 |
| HP            | 3397                        | [efcd9d806e](https://linux-hardware.org/?probe=efcd9d806e) | Dec 06, 2022 |
| HP            | 843C                        | [278cbd2708](https://linux-hardware.org/?probe=278cbd2708) | Dec 06, 2022 |
| MSI           | B450M PRO-M2                | [4be2d528de](https://linux-hardware.org/?probe=4be2d528de) | Dec 06, 2022 |
| MSI           | B450M PRO-M2                | [787a504fd5](https://linux-hardware.org/?probe=787a504fd5) | Dec 06, 2022 |
| Dell          | 0HN7XN A00                  | [f2ba8a7d55](https://linux-hardware.org/?probe=f2ba8a7d55) | Dec 06, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [3912675c64](https://linux-hardware.org/?probe=3912675c64) | Dec 06, 2022 |
| Dell          | 0HN7XN A00                  | [927991f54f](https://linux-hardware.org/?probe=927991f54f) | Dec 06, 2022 |
| Dell          | 0HN7XN A01                  | [72203965d8](https://linux-hardware.org/?probe=72203965d8) | Dec 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1421946e24](https://linux-hardware.org/?probe=1421946e24) | Dec 05, 2022 |
| Gigabyte      | H510M S2H V2                | [b0b53bc408](https://linux-hardware.org/?probe=b0b53bc408) | Dec 05, 2022 |
| Lenovo        | ThinkCentre M58 7637AD4     | [fa5c9707de](https://linux-hardware.org/?probe=fa5c9707de) | Dec 05, 2022 |
| AZW           | Green G2                    | [dd9b6cf42c](https://linux-hardware.org/?probe=dd9b6cf42c) | Dec 05, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [d0230b5c69](https://linux-hardware.org/?probe=d0230b5c69) | Dec 05, 2022 |
| HP            | 8061                        | [9d30b0126f](https://linux-hardware.org/?probe=9d30b0126f) | Dec 05, 2022 |
| ASRock        | B450M-HDV R4.0              | [53ae0e1b6c](https://linux-hardware.org/?probe=53ae0e1b6c) | Dec 05, 2022 |
| HP            | 18E4                        | [8e84f33d20](https://linux-hardware.org/?probe=8e84f33d20) | Dec 05, 2022 |
| HP            | 3047h                       | [0cfbce3bfa](https://linux-hardware.org/?probe=0cfbce3bfa) | Dec 04, 2022 |
| HP            | 3047h                       | [79d18abae5](https://linux-hardware.org/?probe=79d18abae5) | Dec 04, 2022 |
| Unknown       | Unknown                     | [a89e9e55cb](https://linux-hardware.org/?probe=a89e9e55cb) | Dec 04, 2022 |
| Intel         | Unknown                     | [d00187a52a](https://linux-hardware.org/?probe=d00187a52a) | Dec 04, 2022 |
| MSI           | MAG B550M MORTAR            | [ad81cbb6e4](https://linux-hardware.org/?probe=ad81cbb6e4) | Dec 04, 2022 |
| Dell          | 0DFRFW A01                  | [a3ee070c79](https://linux-hardware.org/?probe=a3ee070c79) | Dec 03, 2022 |
| Dell          | 0DFRFW A01                  | [45543562ff](https://linux-hardware.org/?probe=45543562ff) | Dec 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [78746e7632](https://linux-hardware.org/?probe=78746e7632) | Dec 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [ead86b243b](https://linux-hardware.org/?probe=ead86b243b) | Dec 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [059ed32da0](https://linux-hardware.org/?probe=059ed32da0) | Dec 03, 2022 |
| ASUSTek       | P8H61-M LX                  | [a7b285d49f](https://linux-hardware.org/?probe=a7b285d49f) | Dec 03, 2022 |
| ASUSTek       | P8H61-M LX                  | [cd75a3e13f](https://linux-hardware.org/?probe=cd75a3e13f) | Dec 03, 2022 |
| Dell          | 0C27VV A01                  | [f39ec1d618](https://linux-hardware.org/?probe=f39ec1d618) | Dec 03, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [f14eadc80d](https://linux-hardware.org/?probe=f14eadc80d) | Dec 02, 2022 |
| Intel         | X99                         | [bd1d84cf82](https://linux-hardware.org/?probe=bd1d84cf82) | Dec 02, 2022 |
| Gigabyte      | B85M-D3H                    | [5e58cb10a5](https://linux-hardware.org/?probe=5e58cb10a5) | Dec 02, 2022 |
| Gigabyte      | B85M-D3H                    | [81315b2876](https://linux-hardware.org/?probe=81315b2876) | Dec 02, 2022 |
| Intel         | X99                         | [4051f684d8](https://linux-hardware.org/?probe=4051f684d8) | Dec 02, 2022 |
| Dell          | OptiPlex 3020               | [d4a0d26b8b](https://linux-hardware.org/?probe=d4a0d26b8b) | Dec 02, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [13b2f864f8](https://linux-hardware.org/?probe=13b2f864f8) | Dec 02, 2022 |
| HP            | 8643 SMVB                   | [53791932e4](https://linux-hardware.org/?probe=53791932e4) | Dec 02, 2022 |
| Gigabyte      | GA-E6010N                   | [5fddeb1852](https://linux-hardware.org/?probe=5fddeb1852) | Dec 02, 2022 |
| AZW           | Green G2                    | [69ae0f5b9c](https://linux-hardware.org/?probe=69ae0f5b9c) | Dec 02, 2022 |
| ASUSTek       | A88XM-A                     | [f883ed1fd1](https://linux-hardware.org/?probe=f883ed1fd1) | Dec 01, 2022 |
| ASUSTek       | P8H67                       | [31a7799a34](https://linux-hardware.org/?probe=31a7799a34) | Dec 01, 2022 |
| Gigabyte      | GA-990FXA-UD7               | [e300be2b5e](https://linux-hardware.org/?probe=e300be2b5e) | Dec 01, 2022 |
| HP            | 18E9                        | [9086d1a1e5](https://linux-hardware.org/?probe=9086d1a1e5) | Dec 01, 2022 |
| ECS           | H61H2-WM                    | [9a7a280b58](https://linux-hardware.org/?probe=9a7a280b58) | Dec 01, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [24dd5413fa](https://linux-hardware.org/?probe=24dd5413fa) | Nov 30, 2022 |
| Gigabyte      | Z87-HD3                     | [d9a78cb529](https://linux-hardware.org/?probe=d9a78cb529) | Nov 30, 2022 |
| Dell          | 0M5DCD A00                  | [e9fae02409](https://linux-hardware.org/?probe=e9fae02409) | Nov 30, 2022 |
| Gigabyte      | G33M-S2                     | [3d6a965dd4](https://linux-hardware.org/?probe=3d6a965dd4) | Nov 30, 2022 |
| ASUSTek       | Benicia                     | [e5468e4258](https://linux-hardware.org/?probe=e5468e4258) | Nov 30, 2022 |
| Dell          | 0D28YY A00                  | [4af0b7dc59](https://linux-hardware.org/?probe=4af0b7dc59) | Nov 30, 2022 |
| Dell          | 0D28YY A00                  | [bc8c993489](https://linux-hardware.org/?probe=bc8c993489) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | [ede29d01f8](https://linux-hardware.org/?probe=ede29d01f8) | Nov 30, 2022 |
| ASRock        | AB350 Pro4                  | [de19b92dda](https://linux-hardware.org/?probe=de19b92dda) | Nov 30, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [b38075cef4](https://linux-hardware.org/?probe=b38075cef4) | Nov 29, 2022 |
| HP            | 18E4                        | [39b839e527](https://linux-hardware.org/?probe=39b839e527) | Nov 29, 2022 |
| ASRock        | N68-S3 UCC                  | [fd6f368580](https://linux-hardware.org/?probe=fd6f368580) | Nov 29, 2022 |
| ASUSTek       | P8H77-M                     | [4aafb7e858](https://linux-hardware.org/?probe=4aafb7e858) | Nov 29, 2022 |
| Gigabyte      | 946GMX-S2                   | [6c97b310fb](https://linux-hardware.org/?probe=6c97b310fb) | Nov 29, 2022 |
| HP            | 806A                        | [82128d6a8b](https://linux-hardware.org/?probe=82128d6a8b) | Nov 28, 2022 |
| Gigabyte      | GA-MA770-UD3                | [be98ffe55b](https://linux-hardware.org/?probe=be98ffe55b) | Nov 28, 2022 |
| Dell          | 040DDP A00                  | [6bf43c8793](https://linux-hardware.org/?probe=6bf43c8793) | Nov 28, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [fa5d6f5ca6](https://linux-hardware.org/?probe=fa5d6f5ca6) | Nov 28, 2022 |
| Dell          | 0DR845                      | [57f2ea3914](https://linux-hardware.org/?probe=57f2ea3914) | Nov 27, 2022 |
| Dell          | 0DR845                      | [f28560630d](https://linux-hardware.org/?probe=f28560630d) | Nov 27, 2022 |
| ASUSTek       | M5A78L-M LX                 | [c924457e4b](https://linux-hardware.org/?probe=c924457e4b) | Nov 27, 2022 |
| AMD           | 58514                       | [7558bc36a0](https://linux-hardware.org/?probe=7558bc36a0) | Nov 27, 2022 |
| ASRock        | 970 Pro3 R2.0               | [79cce0ef33](https://linux-hardware.org/?probe=79cce0ef33) | Nov 27, 2022 |
| HP            | 18E4                        | [11c1530767](https://linux-hardware.org/?probe=11c1530767) | Nov 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | [b5260b5609](https://linux-hardware.org/?probe=b5260b5609) | Nov 26, 2022 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [eb0921d1f6](https://linux-hardware.org/?probe=eb0921d1f6) | Nov 26, 2022 |
| MSI           | 970 GAMING                  | [82a3d83d20](https://linux-hardware.org/?probe=82a3d83d20) | Nov 26, 2022 |
| MSI           | X370 GAMING M7 ACK          | [c2dca9687b](https://linux-hardware.org/?probe=c2dca9687b) | Nov 26, 2022 |
| Gigabyte      | GA-MA770-UD3                | [0f4c0786c2](https://linux-hardware.org/?probe=0f4c0786c2) | Nov 26, 2022 |
| ASRock        | H61M-DGS R2.0               | [189b3c0ea0](https://linux-hardware.org/?probe=189b3c0ea0) | Nov 26, 2022 |
| MSI           | B550-A PRO                  | [8d0b06aa1d](https://linux-hardware.org/?probe=8d0b06aa1d) | Nov 26, 2022 |
| Intel         | H61                         | [76825e4753](https://linux-hardware.org/?probe=76825e4753) | Nov 25, 2022 |
| Intel         | D525MW AAE93082-401         | [d480b7ef56](https://linux-hardware.org/?probe=d480b7ef56) | Nov 25, 2022 |
| Intel         | D525MW AAE93082-401         | [d3b2f8aaf7](https://linux-hardware.org/?probe=d3b2f8aaf7) | Nov 25, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | [dad5599996](https://linux-hardware.org/?probe=dad5599996) | Nov 24, 2022 |
| HP            | 339A                        | [52f957ef60](https://linux-hardware.org/?probe=52f957ef60) | Nov 24, 2022 |
| Unknown       | Unknown                     | [0904a442f0](https://linux-hardware.org/?probe=0904a442f0) | Nov 24, 2022 |
| ASRock        | B550M Pro4                  | [3ba26453f1](https://linux-hardware.org/?probe=3ba26453f1) | Nov 24, 2022 |
| ASUSTek       | PRIME Z270-K                | [e311874280](https://linux-hardware.org/?probe=e311874280) | Nov 24, 2022 |
| HP            | 806A                        | [ee8a1db4f4](https://linux-hardware.org/?probe=ee8a1db4f4) | Nov 24, 2022 |
| Gigabyte      | A320M-H-CF                  | [036dcac9fa](https://linux-hardware.org/?probe=036dcac9fa) | Nov 24, 2022 |
| ASUSTek       | B85-PRO GAMER               | [6d87497f34](https://linux-hardware.org/?probe=6d87497f34) | Nov 23, 2022 |
| Medion        | TJ4125                      | [84084e5cdc](https://linux-hardware.org/?probe=84084e5cdc) | Nov 23, 2022 |
| Medion        | TJ4125                      | [810477dfd9](https://linux-hardware.org/?probe=810477dfd9) | Nov 23, 2022 |
| HP            | 18E4                        | [8dd5fdb580](https://linux-hardware.org/?probe=8dd5fdb580) | Nov 23, 2022 |
| Dell          | 0P01GV A03                  | [470e942150](https://linux-hardware.org/?probe=470e942150) | Nov 23, 2022 |
| HP            | 3397                        | [eb8968148c](https://linux-hardware.org/?probe=eb8968148c) | Nov 23, 2022 |
| ASRock        | Q1900B-ITX                  | [7239c46e95](https://linux-hardware.org/?probe=7239c46e95) | Nov 23, 2022 |
| Intel         | B75                         | [24b64d225a](https://linux-hardware.org/?probe=24b64d225a) | Nov 22, 2022 |
| MSI           | Z87-G45 GAMING              | [66383ce902](https://linux-hardware.org/?probe=66383ce902) | Nov 22, 2022 |
| PCWare        | IPMH61R2                    | [93db11744b](https://linux-hardware.org/?probe=93db11744b) | Nov 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | [62048f37d6](https://linux-hardware.org/?probe=62048f37d6) | Nov 22, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [ba7795ec44](https://linux-hardware.org/?probe=ba7795ec44) | Nov 22, 2022 |
| MSI           | IONA                        | [39bcd0f2d8](https://linux-hardware.org/?probe=39bcd0f2d8) | Nov 22, 2022 |
| ASRock        | H81M-DGS R2.0               | [0354f9cb0e](https://linux-hardware.org/?probe=0354f9cb0e) | Nov 21, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | [fabd2d4455](https://linux-hardware.org/?probe=fabd2d4455) | Nov 21, 2022 |
| Gigabyte      | GA-MA770-UD3                | [b963fb74e2](https://linux-hardware.org/?probe=b963fb74e2) | Nov 21, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f4e5d3bd1c](https://linux-hardware.org/?probe=f4e5d3bd1c) | Nov 21, 2022 |
| MSI           | A68HM-E33 V2                | [a93dbf13df](https://linux-hardware.org/?probe=a93dbf13df) | Nov 21, 2022 |
| MSI           | A68HM-E33 V2                | [50ca61403f](https://linux-hardware.org/?probe=50ca61403f) | Nov 21, 2022 |
| HP            | 82B4                        | [c56604f389](https://linux-hardware.org/?probe=c56604f389) | Nov 21, 2022 |
| ASUSTek       | P6T DELUXE                  | [54f10b9d0b](https://linux-hardware.org/?probe=54f10b9d0b) | Nov 21, 2022 |
| ASUSTek       | P6T DELUXE                  | [576ca67a28](https://linux-hardware.org/?probe=576ca67a28) | Nov 21, 2022 |
| Gigabyte      | B450 AORUS M                | [7ccd7842c1](https://linux-hardware.org/?probe=7ccd7842c1) | Nov 21, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [4599b81a6b](https://linux-hardware.org/?probe=4599b81a6b) | Nov 21, 2022 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [79403c8f5d](https://linux-hardware.org/?probe=79403c8f5d) | Nov 20, 2022 |
| ASUSTek       | Z97M-PLUS                   | [7ad1a412ae](https://linux-hardware.org/?probe=7ad1a412ae) | Nov 20, 2022 |
| Gigabyte      | Z77X-D3H                    | [1702f14317](https://linux-hardware.org/?probe=1702f14317) | Nov 20, 2022 |
| Gigabyte      | EP45-UD3LR                  | [75a8f2a500](https://linux-hardware.org/?probe=75a8f2a500) | Nov 20, 2022 |
| ASUSTek       | P8H67-M PRO                 | [55bd7957b4](https://linux-hardware.org/?probe=55bd7957b4) | Nov 20, 2022 |
| AZW           | Green G2                    | [85d7c0c54b](https://linux-hardware.org/?probe=85d7c0c54b) | Nov 20, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [35d824783a](https://linux-hardware.org/?probe=35d824783a) | Nov 20, 2022 |
| Gigabyte      | Z490 AORUS PRO AX           | [abe3da973c](https://linux-hardware.org/?probe=abe3da973c) | Nov 19, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [24518f7bf0](https://linux-hardware.org/?probe=24518f7bf0) | Nov 19, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [1cc37489d5](https://linux-hardware.org/?probe=1cc37489d5) | Nov 19, 2022 |
| Gigabyte      | H81M-HD3                    | [d858d2656d](https://linux-hardware.org/?probe=d858d2656d) | Nov 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f1724d63d5](https://linux-hardware.org/?probe=f1724d63d5) | Nov 19, 2022 |
| Acer          | Aspire TC-1760              | [a4f03aea9c](https://linux-hardware.org/?probe=a4f03aea9c) | Nov 19, 2022 |
| ASUSTek       | P5KPL/1600                  | [b2e20d7f28](https://linux-hardware.org/?probe=b2e20d7f28) | Nov 19, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a0495a1ea1](https://linux-hardware.org/?probe=a0495a1ea1) | Nov 18, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [2089ec3efb](https://linux-hardware.org/?probe=2089ec3efb) | Nov 18, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [ea98e803d1](https://linux-hardware.org/?probe=ea98e803d1) | Nov 18, 2022 |
| HP            | 8643 SMVB                   | [fc34170a10](https://linux-hardware.org/?probe=fc34170a10) | Nov 18, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [de3eac26e1](https://linux-hardware.org/?probe=de3eac26e1) | Nov 18, 2022 |
| ASUSTek       | P8B75-V                     | [6f3b172132](https://linux-hardware.org/?probe=6f3b172132) | Nov 18, 2022 |
| HP            | 0A08h                       | [99ca72c75c](https://linux-hardware.org/?probe=99ca72c75c) | Nov 18, 2022 |
| HP            | 0A08h                       | [0e935d58d0](https://linux-hardware.org/?probe=0e935d58d0) | Nov 18, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [b06d8265c4](https://linux-hardware.org/?probe=b06d8265c4) | Nov 17, 2022 |
| Dell          | 05GD68 A00                  | [d0da497d43](https://linux-hardware.org/?probe=d0da497d43) | Nov 17, 2022 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [169294b358](https://linux-hardware.org/?probe=169294b358) | Nov 17, 2022 |
| HP            | 8169                        | [6dd9ea2ef0](https://linux-hardware.org/?probe=6dd9ea2ef0) | Nov 17, 2022 |
| Biostar       | TH67XE                      | [47da767a5a](https://linux-hardware.org/?probe=47da767a5a) | Nov 16, 2022 |
| Mediacom      | M-AO241/64                  | [8312099aa4](https://linux-hardware.org/?probe=8312099aa4) | Nov 16, 2022 |
| MSI           | X370 GAMING M7 ACK          | [6d27500df5](https://linux-hardware.org/?probe=6d27500df5) | Nov 16, 2022 |
| ASRock        | N68-S3 UCC                  | [3f0f992387](https://linux-hardware.org/?probe=3f0f992387) | Nov 16, 2022 |
| Dell          | 0K3CM7 A00                  | [85e5ea1485](https://linux-hardware.org/?probe=85e5ea1485) | Nov 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [e2492ba1c1](https://linux-hardware.org/?probe=e2492ba1c1) | Nov 16, 2022 |
| MSI           | X370 GAMING M7 ACK          | [56a3ecf6d9](https://linux-hardware.org/?probe=56a3ecf6d9) | Nov 16, 2022 |
| Dell          | 0WR7PY A02                  | [feeb9c7afd](https://linux-hardware.org/?probe=feeb9c7afd) | Nov 15, 2022 |
| Acer          | Aspire X3470                | [ccaec6d2cb](https://linux-hardware.org/?probe=ccaec6d2cb) | Nov 15, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [6dd2bbbe51](https://linux-hardware.org/?probe=6dd2bbbe51) | Nov 15, 2022 |
| AZW           | Green G2                    | [27def57052](https://linux-hardware.org/?probe=27def57052) | Nov 15, 2022 |
| ASRock        | B150M-HDS                   | [032d8f7c3c](https://linux-hardware.org/?probe=032d8f7c3c) | Nov 15, 2022 |
| ASRock        | H81M-DGS R2.0               | [f56f2c6a53](https://linux-hardware.org/?probe=f56f2c6a53) | Nov 14, 2022 |
| Acer          | Aspire TC-780               | [4687e7d178](https://linux-hardware.org/?probe=4687e7d178) | Nov 14, 2022 |
| HP            | 0AA8h                       | [0f88d64eeb](https://linux-hardware.org/?probe=0f88d64eeb) | Nov 14, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [21ea41871f](https://linux-hardware.org/?probe=21ea41871f) | Nov 14, 2022 |
| ASUSTek       | PRIME A520M-A II            | [ff1f659f4e](https://linux-hardware.org/?probe=ff1f659f4e) | Nov 14, 2022 |
| ASUSTek       | PRIME A520M-A II            | [a316ed1e2c](https://linux-hardware.org/?probe=a316ed1e2c) | Nov 14, 2022 |
| Huanan        | X99-F8                      | [0e3b4121ea](https://linux-hardware.org/?probe=0e3b4121ea) | Nov 14, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [00db55919b](https://linux-hardware.org/?probe=00db55919b) | Nov 14, 2022 |
| Acer          | Aspire XC-840               | [fe8db55aac](https://linux-hardware.org/?probe=fe8db55aac) | Nov 14, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [dd28f73303](https://linux-hardware.org/?probe=dd28f73303) | Nov 14, 2022 |
| ASUSTek       | P6T DELUXE                  | [3726e23d23](https://linux-hardware.org/?probe=3726e23d23) | Nov 14, 2022 |
| PCWare        | IPMH61R3                    | [7b7925f93d](https://linux-hardware.org/?probe=7b7925f93d) | Nov 13, 2022 |
| MSI           | B75MA-E33                   | [9db352ce8b](https://linux-hardware.org/?probe=9db352ce8b) | Nov 13, 2022 |
| MSI           | B450 GAMING PLUS            | [2964de32f4](https://linux-hardware.org/?probe=2964de32f4) | Nov 13, 2022 |
| ASRock        | B660M-HDV                   | [eeaa5c82ea](https://linux-hardware.org/?probe=eeaa5c82ea) | Nov 13, 2022 |
| Gigabyte      | Z390 M-CF                   | [047686dabd](https://linux-hardware.org/?probe=047686dabd) | Nov 13, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [081e103f77](https://linux-hardware.org/?probe=081e103f77) | Nov 13, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [1c9bb380ab](https://linux-hardware.org/?probe=1c9bb380ab) | Nov 13, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [f18af41d42](https://linux-hardware.org/?probe=f18af41d42) | Nov 13, 2022 |
| MSI           | ZH77A-G43                   | [a8f49c1ad8](https://linux-hardware.org/?probe=a8f49c1ad8) | Nov 13, 2022 |
| ASRock        | B450M Pro4                  | [11d46f72ea](https://linux-hardware.org/?probe=11d46f72ea) | Nov 13, 2022 |
| Unknown       | Unknown                     | [b89a0c7341](https://linux-hardware.org/?probe=b89a0c7341) | Nov 13, 2022 |
| ASUSTek       | 2A73h                       | [08e4620733](https://linux-hardware.org/?probe=08e4620733) | Nov 13, 2022 |
| HP            | 339A                        | [c995f831b8](https://linux-hardware.org/?probe=c995f831b8) | Nov 13, 2022 |
| ASUSTek       | 2A73h                       | [557fb98d98](https://linux-hardware.org/?probe=557fb98d98) | Nov 13, 2022 |
| Intel         | H55                         | [b3cbb34a98](https://linux-hardware.org/?probe=b3cbb34a98) | Nov 12, 2022 |
| Intel         | H55                         | [c4171c6957](https://linux-hardware.org/?probe=c4171c6957) | Nov 12, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [3c567aa946](https://linux-hardware.org/?probe=3c567aa946) | Nov 12, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [632037506d](https://linux-hardware.org/?probe=632037506d) | Nov 12, 2022 |
| Gateway       | SX2110GA                    | [10c89cd51a](https://linux-hardware.org/?probe=10c89cd51a) | Nov 12, 2022 |
| Dell          | 051FJ8 A00                  | [374843d786](https://linux-hardware.org/?probe=374843d786) | Nov 11, 2022 |
| Dell          | 051FJ8 A00                  | [a49f180f2d](https://linux-hardware.org/?probe=a49f180f2d) | Nov 11, 2022 |
| Unknown       | Unknown                     | [e0b38a3d54](https://linux-hardware.org/?probe=e0b38a3d54) | Nov 11, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [4fddb7605a](https://linux-hardware.org/?probe=4fddb7605a) | Nov 11, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [779188af6a](https://linux-hardware.org/?probe=779188af6a) | Nov 11, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [902fafd6cd](https://linux-hardware.org/?probe=902fafd6cd) | Nov 11, 2022 |
| ASUSTek       | Benicia                     | [03ce113379](https://linux-hardware.org/?probe=03ce113379) | Nov 11, 2022 |
| Intel         | DG41WV AAE90316-102         | [517598326a](https://linux-hardware.org/?probe=517598326a) | Nov 10, 2022 |
| Gigabyte      | X58A-UD3R                   | [14afa89833](https://linux-hardware.org/?probe=14afa89833) | Nov 10, 2022 |
| Lenovo        | ThinkCentre M58p 9728W47    | [48e81f1349](https://linux-hardware.org/?probe=48e81f1349) | Nov 10, 2022 |
| AZW           | Green G2                    | [265221b91d](https://linux-hardware.org/?probe=265221b91d) | Nov 10, 2022 |
| ASUSTek       | P5K/EPU                     | [4bd9a2de61](https://linux-hardware.org/?probe=4bd9a2de61) | Nov 10, 2022 |
| Dell          | 00V62H A01                  | [d5f5f32529](https://linux-hardware.org/?probe=d5f5f32529) | Nov 10, 2022 |
| Gigabyte      | H55M-S2H                    | [8af42c3646](https://linux-hardware.org/?probe=8af42c3646) | Nov 10, 2022 |
| ASUSTek       | P5K/EPU                     | [cd3706107a](https://linux-hardware.org/?probe=cd3706107a) | Nov 10, 2022 |
| Gigabyte      | H55M-S2H                    | [18d013bbc8](https://linux-hardware.org/?probe=18d013bbc8) | Nov 10, 2022 |
| ASUSTek       | Leonite2                    | [67db8fec5f](https://linux-hardware.org/?probe=67db8fec5f) | Nov 10, 2022 |
| Dell          | 02YYK5 A01                  | [8fdc8aaeae](https://linux-hardware.org/?probe=8fdc8aaeae) | Nov 10, 2022 |
| Dell          | 02YYK5 A01                  | [95df3e5e22](https://linux-hardware.org/?probe=95df3e5e22) | Nov 10, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [ddbdf3da0f](https://linux-hardware.org/?probe=ddbdf3da0f) | Nov 10, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [4b5ec389d9](https://linux-hardware.org/?probe=4b5ec389d9) | Nov 09, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [292caf8ccf](https://linux-hardware.org/?probe=292caf8ccf) | Nov 09, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b2d88e2356](https://linux-hardware.org/?probe=b2d88e2356) | Nov 09, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [3ffeeccb58](https://linux-hardware.org/?probe=3ffeeccb58) | Nov 08, 2022 |
| Gigabyte      | Z77X-D3H                    | [09e3734a06](https://linux-hardware.org/?probe=09e3734a06) | Nov 08, 2022 |
| Intel         | H61                         | [67af788bd9](https://linux-hardware.org/?probe=67af788bd9) | Nov 08, 2022 |
| Gigabyte      | Z170X-Gaming 7              | [4ae32a2dcc](https://linux-hardware.org/?probe=4ae32a2dcc) | Nov 08, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [c90eda7941](https://linux-hardware.org/?probe=c90eda7941) | Nov 08, 2022 |
| MSI           | Z77A-G43                    | [6dd1e1dc43](https://linux-hardware.org/?probe=6dd1e1dc43) | Nov 07, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [0aad7f7578](https://linux-hardware.org/?probe=0aad7f7578) | Nov 07, 2022 |
| Unknown       | Unknown                     | [dc375c11c7](https://linux-hardware.org/?probe=dc375c11c7) | Nov 07, 2022 |
| Dell          | 0DF42J A00                  | [67928f8921](https://linux-hardware.org/?probe=67928f8921) | Nov 07, 2022 |
| ASRock        | H97M Pro4                   | [4714142eaf](https://linux-hardware.org/?probe=4714142eaf) | Nov 07, 2022 |
| ASRock        | H97M Pro4                   | [61a1e01bea](https://linux-hardware.org/?probe=61a1e01bea) | Nov 07, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [10343f043a](https://linux-hardware.org/?probe=10343f043a) | Nov 07, 2022 |
| AZW           | Green G2                    | [3ed644a27e](https://linux-hardware.org/?probe=3ed644a27e) | Nov 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | [32bb86a1e6](https://linux-hardware.org/?probe=32bb86a1e6) | Nov 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | [c91e77c03a](https://linux-hardware.org/?probe=c91e77c03a) | Nov 06, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [07e637210f](https://linux-hardware.org/?probe=07e637210f) | Nov 06, 2022 |
| ASUSTek       | P5K                         | [6085242cc3](https://linux-hardware.org/?probe=6085242cc3) | Nov 06, 2022 |
| ASUSTek       | P5K                         | [7cddfe4e9a](https://linux-hardware.org/?probe=7cddfe4e9a) | Nov 06, 2022 |
| Dell          | 040DDP A00                  | [6179dcf9ae](https://linux-hardware.org/?probe=6179dcf9ae) | Nov 05, 2022 |
| Gigabyte      | 990FXA-UD7                  | [d4d7721821](https://linux-hardware.org/?probe=d4d7721821) | Nov 05, 2022 |
| ASRock        | B450M Steel Legend          | [1534af11b9](https://linux-hardware.org/?probe=1534af11b9) | Nov 05, 2022 |
| HP            | 8053                        | [20c566d4e7](https://linux-hardware.org/?probe=20c566d4e7) | Nov 05, 2022 |
| Gigabyte      | Z170X-Gaming 7              | [be2ceae6ca](https://linux-hardware.org/?probe=be2ceae6ca) | Nov 05, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [ffb4ff83fd](https://linux-hardware.org/?probe=ffb4ff83fd) | Nov 05, 2022 |
| ASRock        | M3A770DE                    | [5188bac576](https://linux-hardware.org/?probe=5188bac576) | Nov 04, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [069116f50a](https://linux-hardware.org/?probe=069116f50a) | Nov 04, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [2b3848b2cb](https://linux-hardware.org/?probe=2b3848b2cb) | Nov 04, 2022 |
| ASUSTek       | Amberine M                  | [f598d98461](https://linux-hardware.org/?probe=f598d98461) | Nov 04, 2022 |
| HP            | 3396                        | [d6867789ca](https://linux-hardware.org/?probe=d6867789ca) | Nov 04, 2022 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [14dc45e331](https://linux-hardware.org/?probe=14dc45e331) | Nov 04, 2022 |
| MSI           | B450-A PRO                  | [8ef3469319](https://linux-hardware.org/?probe=8ef3469319) | Nov 04, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ee74ab18df](https://linux-hardware.org/?probe=ee74ab18df) | Nov 04, 2022 |
| MSI           | H510M PRO                   | [16980e0782](https://linux-hardware.org/?probe=16980e0782) | Nov 04, 2022 |
| Dell          | 00V62H A01                  | [d2ba0a8916](https://linux-hardware.org/?probe=d2ba0a8916) | Nov 04, 2022 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [9aa8622017](https://linux-hardware.org/?probe=9aa8622017) | Nov 04, 2022 |
| Dell          | 00V62H A01                  | [57bf24f3da](https://linux-hardware.org/?probe=57bf24f3da) | Nov 04, 2022 |
| MSI           | H510M PRO                   | [646aee082a](https://linux-hardware.org/?probe=646aee082a) | Nov 04, 2022 |
| Intel         | DG33BU AAD79951-407         | [e692849b95](https://linux-hardware.org/?probe=e692849b95) | Nov 04, 2022 |
| ASUSTek       | M3A78 PRO                   | [93b2e9aea5](https://linux-hardware.org/?probe=93b2e9aea5) | Nov 04, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [411ea09aee](https://linux-hardware.org/?probe=411ea09aee) | Nov 03, 2022 |
| ASUSTek       | M3A78 PRO                   | [5466838c04](https://linux-hardware.org/?probe=5466838c04) | Nov 03, 2022 |
| MSI           | B85M PRO-VD                 | [46a3742fd3](https://linux-hardware.org/?probe=46a3742fd3) | Nov 03, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [5ace066925](https://linux-hardware.org/?probe=5ace066925) | Nov 03, 2022 |
| Gigabyte      | Z87M-D3H                    | [f427764e2c](https://linux-hardware.org/?probe=f427764e2c) | Nov 03, 2022 |
| Gigabyte      | H310M H                     | [7a49c87643](https://linux-hardware.org/?probe=7a49c87643) | Nov 02, 2022 |
| Gigabyte      | H310M H                     | [382965c890](https://linux-hardware.org/?probe=382965c890) | Nov 02, 2022 |
| HP            | 3397                        | [24eb596bce](https://linux-hardware.org/?probe=24eb596bce) | Nov 02, 2022 |
| HP            | 1589                        | [81a347a6a7](https://linux-hardware.org/?probe=81a347a6a7) | Nov 02, 2022 |
| Dell          | 02YRK5 A02                  | [2c63ff26e5](https://linux-hardware.org/?probe=2c63ff26e5) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d28b33e126](https://linux-hardware.org/?probe=d28b33e126) | Nov 01, 2022 |
| Dell          | 0XR1GT A00                  | [8f551aaa52](https://linux-hardware.org/?probe=8f551aaa52) | Nov 01, 2022 |
| Dell          | 088DT1 A01                  | [efcbf8a2eb](https://linux-hardware.org/?probe=efcbf8a2eb) | Nov 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [a3a55bf3e4](https://linux-hardware.org/?probe=a3a55bf3e4) | Nov 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [8d99f1fb3b](https://linux-hardware.org/?probe=8d99f1fb3b) | Nov 01, 2022 |
| ASUSTek       | B150M-V PLUS                | [a451844625](https://linux-hardware.org/?probe=a451844625) | Nov 01, 2022 |
| HP            | 8054                        | [9e1b99d9bb](https://linux-hardware.org/?probe=9e1b99d9bb) | Nov 01, 2022 |
| Dell          | 040DDP A00                  | [22b1e93203](https://linux-hardware.org/?probe=22b1e93203) | Oct 31, 2022 |
| ASUSTek       | Z87-K                       | [7edc0875ed](https://linux-hardware.org/?probe=7edc0875ed) | Oct 31, 2022 |
| Pegatron      | 2AABh                       | [94dd13992c](https://linux-hardware.org/?probe=94dd13992c) | Oct 31, 2022 |
| MSI           | H110M PRO-VD PLUS           | [ced3229025](https://linux-hardware.org/?probe=ced3229025) | Oct 31, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [e309413fea](https://linux-hardware.org/?probe=e309413fea) | Oct 31, 2022 |
| ASUSTek       | P8H77-M                     | [2ae72e7e22](https://linux-hardware.org/?probe=2ae72e7e22) | Oct 31, 2022 |
| Gigabyte      | GA-MA770-UD3                | [e49d4af683](https://linux-hardware.org/?probe=e49d4af683) | Oct 31, 2022 |
| HP            | 18E4                        | [89b197e8a9](https://linux-hardware.org/?probe=89b197e8a9) | Oct 31, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [14e8385f99](https://linux-hardware.org/?probe=14e8385f99) | Oct 31, 2022 |
| Gigabyte      | A520M H                     | [0a8043d206](https://linux-hardware.org/?probe=0a8043d206) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | [13741c554f](https://linux-hardware.org/?probe=13741c554f) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | [e6e466cd8f](https://linux-hardware.org/?probe=e6e466cd8f) | Oct 31, 2022 |
| ASRock        | Z97 Extreme3                | [c741e4ffe8](https://linux-hardware.org/?probe=c741e4ffe8) | Oct 31, 2022 |
| MSI           | Z97 GAMING 3                | [cc2d45c3ff](https://linux-hardware.org/?probe=cc2d45c3ff) | Oct 30, 2022 |
| Gigabyte      | X570 GAMING X               | [d6c135685f](https://linux-hardware.org/?probe=d6c135685f) | Oct 30, 2022 |
| MSI           | Z97 GAMING 3                | [c0926e68a0](https://linux-hardware.org/?probe=c0926e68a0) | Oct 30, 2022 |
| Pegatron      | IPMIP-GS                    | [4e46d903ae](https://linux-hardware.org/?probe=4e46d903ae) | Oct 30, 2022 |
| MSI           | A320M PRO-M2 V2             | [d7c699118b](https://linux-hardware.org/?probe=d7c699118b) | Oct 30, 2022 |
| ASUSTek       | A88XM-PLUS                  | [10aa435a0b](https://linux-hardware.org/?probe=10aa435a0b) | Oct 30, 2022 |
| MSI           | Z77A-GD65                   | [a7bc380726](https://linux-hardware.org/?probe=a7bc380726) | Oct 30, 2022 |
| Dell          | 0M5DCD A00                  | [c3049c59a8](https://linux-hardware.org/?probe=c3049c59a8) | Oct 30, 2022 |
| Dell          | 0M5DCD A00                  | [daae18ab91](https://linux-hardware.org/?probe=daae18ab91) | Oct 30, 2022 |
| ASUSTek       | G11CD                       | [2a9d64387c](https://linux-hardware.org/?probe=2a9d64387c) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [eb71b41aa8](https://linux-hardware.org/?probe=eb71b41aa8) | Oct 29, 2022 |
| HP            | 0AECh D                     | [ee09a01e9e](https://linux-hardware.org/?probe=ee09a01e9e) | Oct 29, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [290f3b115f](https://linux-hardware.org/?probe=290f3b115f) | Oct 29, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [bf841b86f5](https://linux-hardware.org/?probe=bf841b86f5) | Oct 29, 2022 |
| ASUSTek       | M4A785-M                    | [73eae83658](https://linux-hardware.org/?probe=73eae83658) | Oct 29, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [650f1fd648](https://linux-hardware.org/?probe=650f1fd648) | Oct 29, 2022 |
| Gigabyte      | GA-MA770-UD3                | [52a6d45e82](https://linux-hardware.org/?probe=52a6d45e82) | Oct 29, 2022 |
| ASUSTek       | PRIME A320I-K               | [91f4cd151f](https://linux-hardware.org/?probe=91f4cd151f) | Oct 29, 2022 |
| ASRock        | FM2A88X-ITX+                | [00b65eaa83](https://linux-hardware.org/?probe=00b65eaa83) | Oct 29, 2022 |
| Techvision    | TVI7309X B0                 | [65b5280dd1](https://linux-hardware.org/?probe=65b5280dd1) | Oct 29, 2022 |
| ASUSTek       | PRIME H410M-K               | [5a371accfe](https://linux-hardware.org/?probe=5a371accfe) | Oct 29, 2022 |
| ASRock        | B85 Pro4                    | [856d32288b](https://linux-hardware.org/?probe=856d32288b) | Oct 29, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [7d5d2ec0ba](https://linux-hardware.org/?probe=7d5d2ec0ba) | Oct 28, 2022 |
| ASRock        | Z370 Pro4                   | [04e898b2f6](https://linux-hardware.org/?probe=04e898b2f6) | Oct 28, 2022 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [8c85b7ec2e](https://linux-hardware.org/?probe=8c85b7ec2e) | Oct 28, 2022 |
| Lenovo        | MAHOBAY NOK                 | [267b0a3f94](https://linux-hardware.org/?probe=267b0a3f94) | Oct 28, 2022 |
| Gigabyte      | GA-MA790FX-DQ6              | [8ba31a020c](https://linux-hardware.org/?probe=8ba31a020c) | Oct 28, 2022 |
| HP            | 339A                        | [0fdbd7b1d7](https://linux-hardware.org/?probe=0fdbd7b1d7) | Oct 28, 2022 |
| AZW           | Green G2                    | [628aba3de0](https://linux-hardware.org/?probe=628aba3de0) | Oct 27, 2022 |
| Lenovo        | 0B98401 PRO                 | [99f9bbd5ad](https://linux-hardware.org/?probe=99f9bbd5ad) | Oct 27, 2022 |
| MSI           | H110M PRO-VD PLUS           | [d3c4092754](https://linux-hardware.org/?probe=d3c4092754) | Oct 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [81e31b481f](https://linux-hardware.org/?probe=81e31b481f) | Oct 27, 2022 |
| ASRock        | H61M-VG4                    | [25b8826346](https://linux-hardware.org/?probe=25b8826346) | Oct 27, 2022 |
| HP            | 1589                        | [4a15b6de0f](https://linux-hardware.org/?probe=4a15b6de0f) | Oct 27, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [9285fb0d9d](https://linux-hardware.org/?probe=9285fb0d9d) | Oct 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | [4659be383c](https://linux-hardware.org/?probe=4659be383c) | Oct 27, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [469345600b](https://linux-hardware.org/?probe=469345600b) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [26c34998ae](https://linux-hardware.org/?probe=26c34998ae) | Oct 26, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [8c97ee418a](https://linux-hardware.org/?probe=8c97ee418a) | Oct 26, 2022 |
| HP            | 1494                        | [fa63090109](https://linux-hardware.org/?probe=fa63090109) | Oct 26, 2022 |
| ASUSTek       | Z87-A                       | [0b4711df41](https://linux-hardware.org/?probe=0b4711df41) | Oct 26, 2022 |
| Gigabyte      | GA-MA770-UD3                | [dbb72f4c00](https://linux-hardware.org/?probe=dbb72f4c00) | Oct 26, 2022 |
| PCWare        | IPMH61R3                    | [9f9410b99d](https://linux-hardware.org/?probe=9f9410b99d) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [705e51d33e](https://linux-hardware.org/?probe=705e51d33e) | Oct 25, 2022 |
| ASUSTek       | Z87-PRO                     | [a48316f550](https://linux-hardware.org/?probe=a48316f550) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [824eb583d8](https://linux-hardware.org/?probe=824eb583d8) | Oct 25, 2022 |
| Alienware     | 046MHW A00                  | [592883e78e](https://linux-hardware.org/?probe=592883e78e) | Oct 25, 2022 |
| Alienware     | 046MHW A00                  | [734fb9ac8c](https://linux-hardware.org/?probe=734fb9ac8c) | Oct 25, 2022 |
| Gigabyte      | H97M-D3H                    | [72532e08fe](https://linux-hardware.org/?probe=72532e08fe) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | [a38f9baa55](https://linux-hardware.org/?probe=a38f9baa55) | Oct 25, 2022 |
| ASRock        | 4Core1600-GLAN/M            | [33bf20761f](https://linux-hardware.org/?probe=33bf20761f) | Oct 25, 2022 |
| Gigabyte      | 970A-DS3P                   | [995f7abb0c](https://linux-hardware.org/?probe=995f7abb0c) | Oct 25, 2022 |
| HP            | 805F                        | [eaa3994f86](https://linux-hardware.org/?probe=eaa3994f86) | Oct 25, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [ef9fdf5dcd](https://linux-hardware.org/?probe=ef9fdf5dcd) | Oct 25, 2022 |
| Gigabyte      | F2A78M-HD2                  | [6cffc39cfc](https://linux-hardware.org/?probe=6cffc39cfc) | Oct 25, 2022 |
| Gigabyte      | P41T-D3                     | [fa69e3fada](https://linux-hardware.org/?probe=fa69e3fada) | Oct 25, 2022 |
| Gigabyte      | P41T-D3                     | [c96d8030a6](https://linux-hardware.org/?probe=c96d8030a6) | Oct 25, 2022 |
| Gigabyte      | 965P-DS3                    | [18dad8d151](https://linux-hardware.org/?probe=18dad8d151) | Oct 25, 2022 |
| Gigabyte      | Z87-HD3                     | [da7fe35832](https://linux-hardware.org/?probe=da7fe35832) | Oct 25, 2022 |
| Unknown       | SKYBAY                      | [63f22191e8](https://linux-hardware.org/?probe=63f22191e8) | Oct 24, 2022 |
| HP            | 805A                        | [dbe3ff75e8](https://linux-hardware.org/?probe=dbe3ff75e8) | Oct 24, 2022 |
| HP            | 1589                        | [0be048ec45](https://linux-hardware.org/?probe=0be048ec45) | Oct 24, 2022 |
| ASRock        | H61M-VG4                    | [b393d57b17](https://linux-hardware.org/?probe=b393d57b17) | Oct 24, 2022 |
| MSI           | B350M PRO-VD PLUS           | [93068b4cf8](https://linux-hardware.org/?probe=93068b4cf8) | Oct 24, 2022 |
| ASRock        | H61M-VG4                    | [1e80f1de23](https://linux-hardware.org/?probe=1e80f1de23) | Oct 24, 2022 |
| Dell          | 0J3C2F A00                  | [d165241883](https://linux-hardware.org/?probe=d165241883) | Oct 24, 2022 |
| ASUSTek       | P8Z68-V LX                  | [86cff422a6](https://linux-hardware.org/?probe=86cff422a6) | Oct 23, 2022 |
| Biostar       | TH67XE                      | [b523b997f6](https://linux-hardware.org/?probe=b523b997f6) | Oct 23, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [eafcc0b1b0](https://linux-hardware.org/?probe=eafcc0b1b0) | Oct 23, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [b7b190000b](https://linux-hardware.org/?probe=b7b190000b) | Oct 23, 2022 |
| MSI           | A320M PRO-M2 V2             | [1691497b7a](https://linux-hardware.org/?probe=1691497b7a) | Oct 23, 2022 |
| Unknown       | 1.0                         | [2a12c33601](https://linux-hardware.org/?probe=2a12c33601) | Oct 23, 2022 |
| AZW           | Green G2                    | [56ee35acfc](https://linux-hardware.org/?probe=56ee35acfc) | Oct 23, 2022 |
| Gigabyte      | H87-HD3                     | [bdd6e6d3a5](https://linux-hardware.org/?probe=bdd6e6d3a5) | Oct 23, 2022 |
| Lenovo        | ThinkServer TS140           | [6f0f7b249a](https://linux-hardware.org/?probe=6f0f7b249a) | Oct 22, 2022 |
| MSI           | B550-A PRO                  | [52d3513a9c](https://linux-hardware.org/?probe=52d3513a9c) | Oct 22, 2022 |
| Gigabyte      | A520M DS3H                  | [3faf4b3ca9](https://linux-hardware.org/?probe=3faf4b3ca9) | Oct 22, 2022 |
| HP            | 213D A01                    | [c7ffdb8626](https://linux-hardware.org/?probe=c7ffdb8626) | Oct 22, 2022 |
| ASRock        | B450M-HDV R4.0              | [0ec4fb54a6](https://linux-hardware.org/?probe=0ec4fb54a6) | Oct 21, 2022 |
| MSI           | B550-A PRO                  | [d17faed180](https://linux-hardware.org/?probe=d17faed180) | Oct 21, 2022 |
| ASRock        | B450M-HDV R4.0              | [1f659498a2](https://linux-hardware.org/?probe=1f659498a2) | Oct 21, 2022 |
| MSI           | H81M-E34                    | [b036f0d602](https://linux-hardware.org/?probe=b036f0d602) | Oct 21, 2022 |
| MSI           | H81M-P33                    | [4bc1726059](https://linux-hardware.org/?probe=4bc1726059) | Oct 21, 2022 |
| MSI           | Z97 GAMING 3                | [2b5803628a](https://linux-hardware.org/?probe=2b5803628a) | Oct 20, 2022 |
| MSI           | Z97 GAMING 3                | [94c634f9b8](https://linux-hardware.org/?probe=94c634f9b8) | Oct 20, 2022 |
| MSI           | H110M GAMING                | [20689f6175](https://linux-hardware.org/?probe=20689f6175) | Oct 20, 2022 |
| Acer          | Extensa M2610 V:1.0         | [1791236969](https://linux-hardware.org/?probe=1791236969) | Oct 20, 2022 |
| Acer          | Extensa M2610 V:1.0         | [e482e312c8](https://linux-hardware.org/?probe=e482e312c8) | Oct 20, 2022 |
| Dell          | 0J3C2F A00                  | [c97e42e738](https://linux-hardware.org/?probe=c97e42e738) | Oct 20, 2022 |
| ASRock        | X399 Taichi                 | [0c5809902b](https://linux-hardware.org/?probe=0c5809902b) | Oct 20, 2022 |
| HP            | 3047h                       | [1a0f4c46f9](https://linux-hardware.org/?probe=1a0f4c46f9) | Oct 20, 2022 |
| ASRock        | N68C-GS FX                  | [9e0b1677e4](https://linux-hardware.org/?probe=9e0b1677e4) | Oct 20, 2022 |
| ASUSTek       | H170M-PLUS                  | [e34cb7ea31](https://linux-hardware.org/?probe=e34cb7ea31) | Oct 20, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | [13830a8b2b](https://linux-hardware.org/?probe=13830a8b2b) | Oct 20, 2022 |
| Dell          | 0PC5F7 A02                  | [1e54b1512b](https://linux-hardware.org/?probe=1e54b1512b) | Oct 20, 2022 |
| ECS           | H61H2-WM                    | [934781c2fb](https://linux-hardware.org/?probe=934781c2fb) | Oct 19, 2022 |
| HP            | 802F                        | [9e51fdba18](https://linux-hardware.org/?probe=9e51fdba18) | Oct 19, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [7f736b0a22](https://linux-hardware.org/?probe=7f736b0a22) | Oct 19, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [116fff483b](https://linux-hardware.org/?probe=116fff483b) | Oct 19, 2022 |
| ASUSTek       | M3N78-VM                    | [825d6ebf7f](https://linux-hardware.org/?probe=825d6ebf7f) | Oct 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e0b5c85988](https://linux-hardware.org/?probe=e0b5c85988) | Oct 18, 2022 |
| Dell          | 09WH54 A00                  | [b16396bd74](https://linux-hardware.org/?probe=b16396bd74) | Oct 18, 2022 |
| Gigabyte      | B450M GAMING                | [e1eacaa737](https://linux-hardware.org/?probe=e1eacaa737) | Oct 18, 2022 |
| Acer          | Aspire M1930                | [5b9cbd4f58](https://linux-hardware.org/?probe=5b9cbd4f58) | Oct 18, 2022 |
| Dell          | 0XHGV1 A01                  | [fcac80ff4a](https://linux-hardware.org/?probe=fcac80ff4a) | Oct 18, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [ef6d1400a3](https://linux-hardware.org/?probe=ef6d1400a3) | Oct 17, 2022 |
| ASRock        | X300-ITX                    | [a391ce99bf](https://linux-hardware.org/?probe=a391ce99bf) | Oct 17, 2022 |
| ASUSTek       | Maximus IV Extreme          | [d84677af13](https://linux-hardware.org/?probe=d84677af13) | Oct 17, 2022 |
| Dell          | 0J3C2F A02                  | [284e02a5b2](https://linux-hardware.org/?probe=284e02a5b2) | Oct 17, 2022 |
| ASUSTek       | PRIME A520M-A II            | [cbf3a839e2](https://linux-hardware.org/?probe=cbf3a839e2) | Oct 17, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [2d7d5c19c0](https://linux-hardware.org/?probe=2d7d5c19c0) | Oct 17, 2022 |
| Shuttle       | FS81                        | [61c0ca02f3](https://linux-hardware.org/?probe=61c0ca02f3) | Oct 16, 2022 |
| MSI           | A68HM-E33 V2                | [ff59edf4e0](https://linux-hardware.org/?probe=ff59edf4e0) | Oct 16, 2022 |
| ASUSTek       | PRO B460M-C                 | [eb850e075d](https://linux-hardware.org/?probe=eb850e075d) | Oct 16, 2022 |
| Acer          | Aspire M1930                | [9fa87ae442](https://linux-hardware.org/?probe=9fa87ae442) | Oct 16, 2022 |
| ASUSTek       | PRIME B450M-K II            | [d1d815635a](https://linux-hardware.org/?probe=d1d815635a) | Oct 16, 2022 |
| Dell          | 0D6H9T A00                  | [52dec54de2](https://linux-hardware.org/?probe=52dec54de2) | Oct 16, 2022 |
| AZW           | Green G2                    | [f7a9322b66](https://linux-hardware.org/?probe=f7a9322b66) | Oct 16, 2022 |
| Pegatron      | 2A84h                       | [5b46511238](https://linux-hardware.org/?probe=5b46511238) | Oct 15, 2022 |
| HP            | 8027                        | [9f3d6e24b5](https://linux-hardware.org/?probe=9f3d6e24b5) | Oct 15, 2022 |
| Acer          | Aspire TC-865 V:1.1         | [dd4d81390a](https://linux-hardware.org/?probe=dd4d81390a) | Oct 15, 2022 |
| MSI           | A68HM-E33 V2                | [b2a7c6be3a](https://linux-hardware.org/?probe=b2a7c6be3a) | Oct 15, 2022 |
| Acer          | Aspire TC-865 V:1.1         | [dfe2b3b3bf](https://linux-hardware.org/?probe=dfe2b3b3bf) | Oct 15, 2022 |
| Dell          | 09KPNV A01                  | [5261790ba7](https://linux-hardware.org/?probe=5261790ba7) | Oct 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [3f4c203116](https://linux-hardware.org/?probe=3f4c203116) | Oct 15, 2022 |
| Dell          | 051FJ8 A00                  | [4df6746d88](https://linux-hardware.org/?probe=4df6746d88) | Oct 15, 2022 |
| Dell          | 051FJ8 A00                  | [9008c96170](https://linux-hardware.org/?probe=9008c96170) | Oct 15, 2022 |
| Gigabyte      | P55M-UD2                    | [0e3ba8fdb3](https://linux-hardware.org/?probe=0e3ba8fdb3) | Oct 14, 2022 |
| ASRock        | 970M Pro3                   | [ca8ac557b3](https://linux-hardware.org/?probe=ca8ac557b3) | Oct 14, 2022 |
| Unknown       | Unknown                     | [8a680cbcbe](https://linux-hardware.org/?probe=8a680cbcbe) | Oct 13, 2022 |
| ASUSTek       | P8H67-V                     | [0a4b34dba9](https://linux-hardware.org/?probe=0a4b34dba9) | Oct 13, 2022 |
| Gigabyte      | H81M-S2H                    | [3e38f64c1c](https://linux-hardware.org/?probe=3e38f64c1c) | Oct 13, 2022 |
| ASUSTek       | PRIME A520M-A II            | [736d5cdccc](https://linux-hardware.org/?probe=736d5cdccc) | Oct 13, 2022 |
| MSI           | A320M PRO-M2 V2             | [6c895cb5df](https://linux-hardware.org/?probe=6c895cb5df) | Oct 13, 2022 |
| ASUSTek       | PRIME A520M-K               | [e1bdf49dbf](https://linux-hardware.org/?probe=e1bdf49dbf) | Oct 13, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [3ffa813244](https://linux-hardware.org/?probe=3ffa813244) | Oct 13, 2022 |
| Toshiba       | STI 005492G                 | [e803b9bcf3](https://linux-hardware.org/?probe=e803b9bcf3) | Oct 13, 2022 |
| Acer          | Aspire XC100A               | [6fade2c77f](https://linux-hardware.org/?probe=6fade2c77f) | Oct 13, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [e172a9d71b](https://linux-hardware.org/?probe=e172a9d71b) | Oct 13, 2022 |
| Gigabyte      | P55A-UD3                    | [100f7e1b46](https://linux-hardware.org/?probe=100f7e1b46) | Oct 12, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [f7e78e8188](https://linux-hardware.org/?probe=f7e78e8188) | Oct 12, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [9744660229](https://linux-hardware.org/?probe=9744660229) | Oct 12, 2022 |
| Gigabyte      | 946GMX-S2                   | [491d0c69ca](https://linux-hardware.org/?probe=491d0c69ca) | Oct 12, 2022 |
| Gigabyte      | X570S GAMING X              | [e966aea162](https://linux-hardware.org/?probe=e966aea162) | Oct 12, 2022 |
| Gigabyte      | 946GMX-S2                   | [09ee887f3a](https://linux-hardware.org/?probe=09ee887f3a) | Oct 12, 2022 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | [f3b5809fc9](https://linux-hardware.org/?probe=f3b5809fc9) | Oct 12, 2022 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | [1798dba7f1](https://linux-hardware.org/?probe=1798dba7f1) | Oct 12, 2022 |
| ASUSTek       | P8H77-M PRO                 | [16bee4f203](https://linux-hardware.org/?probe=16bee4f203) | Oct 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [f293609698](https://linux-hardware.org/?probe=f293609698) | Oct 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [ca3428ecf2](https://linux-hardware.org/?probe=ca3428ecf2) | Oct 12, 2022 |
| ASUSTek       | P8H67-M LE                  | [4f4f9e3cef](https://linux-hardware.org/?probe=4f4f9e3cef) | Oct 11, 2022 |
| ASUSTek       | P8Z77-V                     | [27b7798784](https://linux-hardware.org/?probe=27b7798784) | Oct 11, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [0e8d79a9a9](https://linux-hardware.org/?probe=0e8d79a9a9) | Oct 11, 2022 |
| Gigabyte      | X299X DESIGNARE 10G         | [fd590a067e](https://linux-hardware.org/?probe=fd590a067e) | Oct 10, 2022 |
| BESSTAR Te... | T3 MRD                      | [d223d492fe](https://linux-hardware.org/?probe=d223d492fe) | Oct 10, 2022 |
| Dell          | 0RW203                      | [306036aa6f](https://linux-hardware.org/?probe=306036aa6f) | Oct 10, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [9e82633709](https://linux-hardware.org/?probe=9e82633709) | Oct 10, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [dd3d3724d6](https://linux-hardware.org/?probe=dd3d3724d6) | Oct 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2b7e826ffe](https://linux-hardware.org/?probe=2b7e826ffe) | Oct 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [32d74cab14](https://linux-hardware.org/?probe=32d74cab14) | Oct 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [abbdbe7e68](https://linux-hardware.org/?probe=abbdbe7e68) | Oct 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [c2193db5fb](https://linux-hardware.org/?probe=c2193db5fb) | Oct 09, 2022 |
| ASUSTek       | P5Q Premium                 | [8c0a201199](https://linux-hardware.org/?probe=8c0a201199) | Oct 09, 2022 |
| ECS           | A890GXM-A2                  | [d6f77b12c2](https://linux-hardware.org/?probe=d6f77b12c2) | Oct 09, 2022 |
| Intel         | DG965LV AAD36275-502        | [e46b9af4cb](https://linux-hardware.org/?probe=e46b9af4cb) | Oct 09, 2022 |
| ASRock        | 970M Pro3                   | [9eaf0bffca](https://linux-hardware.org/?probe=9eaf0bffca) | Oct 09, 2022 |
| ASUSTek       | P8H77-M PRO                 | [ec2b212e33](https://linux-hardware.org/?probe=ec2b212e33) | Oct 09, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [37068529a1](https://linux-hardware.org/?probe=37068529a1) | Oct 09, 2022 |
| Gigabyte      | F2A68HM-S1                  | [379f85dfb3](https://linux-hardware.org/?probe=379f85dfb3) | Oct 09, 2022 |
| Gigabyte      | F2A68HM-S1                  | [f02be8db4c](https://linux-hardware.org/?probe=f02be8db4c) | Oct 09, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [f80d633c86](https://linux-hardware.org/?probe=f80d633c86) | Oct 09, 2022 |
| Gigabyte      | GA-970A-D3                  | [b43b76907b](https://linux-hardware.org/?probe=b43b76907b) | Oct 08, 2022 |
| ASRock        | A320M-HDV R4.0              | [5793d73ce0](https://linux-hardware.org/?probe=5793d73ce0) | Oct 08, 2022 |
| Gigabyte      | B365M D3H-CF                | [2ad7a0c296](https://linux-hardware.org/?probe=2ad7a0c296) | Oct 08, 2022 |
| ASUSTek       | P8H67-M LE                  | [9cd069f242](https://linux-hardware.org/?probe=9cd069f242) | Oct 07, 2022 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [8ac874aef9](https://linux-hardware.org/?probe=8ac874aef9) | Oct 07, 2022 |
| ASRock        | B450M Pro4                  | [f1eaa7e9cc](https://linux-hardware.org/?probe=f1eaa7e9cc) | Oct 07, 2022 |
| ASRock        | 970M Pro3                   | [76d2eeb1d0](https://linux-hardware.org/?probe=76d2eeb1d0) | Oct 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [b457bc3cd2](https://linux-hardware.org/?probe=b457bc3cd2) | Oct 07, 2022 |
| Inventec      | DQ Class A02                | [08c66f26fe](https://linux-hardware.org/?probe=08c66f26fe) | Oct 07, 2022 |
| HP            | ProLiant ML110 Gen9         | [de23da6c1d](https://linux-hardware.org/?probe=de23da6c1d) | Oct 07, 2022 |
| MSI           | B550-A PRO                  | [364bf92a01](https://linux-hardware.org/?probe=364bf92a01) | Oct 07, 2022 |
| ASRock        | 970M Pro3                   | [9d6e9e9a08](https://linux-hardware.org/?probe=9d6e9e9a08) | Oct 07, 2022 |
| ASUSTek       | M3N78-VM                    | [828ba358e2](https://linux-hardware.org/?probe=828ba358e2) | Oct 06, 2022 |
| ASUSTek       | M3N78-VM                    | [6743600262](https://linux-hardware.org/?probe=6743600262) | Oct 06, 2022 |
| Lenovo        | 3853RN9                     | [4274c2b526](https://linux-hardware.org/?probe=4274c2b526) | Oct 06, 2022 |
| Lenovo        | 3853RN9                     | [41bfe2f107](https://linux-hardware.org/?probe=41bfe2f107) | Oct 06, 2022 |
| Gigabyte      | H87M-D3H                    | [8b9d7f32d1](https://linux-hardware.org/?probe=8b9d7f32d1) | Oct 06, 2022 |
| Dell          | 09KPNV A01                  | [6ad101df29](https://linux-hardware.org/?probe=6ad101df29) | Oct 06, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2423d31aeb](https://linux-hardware.org/?probe=2423d31aeb) | Oct 05, 2022 |
| MSI           | B450-A PRO                  | [5ff1f9c5c3](https://linux-hardware.org/?probe=5ff1f9c5c3) | Oct 05, 2022 |
| ASRock        | H61M-VG4                    | [7fe9bf7f20](https://linux-hardware.org/?probe=7fe9bf7f20) | Oct 05, 2022 |
| Gigabyte      | GA-MA69VM-S2                | [c6dd3eef5d](https://linux-hardware.org/?probe=c6dd3eef5d) | Oct 05, 2022 |
| MSI           | A320M-A PRO                 | [40dd630e96](https://linux-hardware.org/?probe=40dd630e96) | Oct 05, 2022 |
| MSI           | A520M-A PRO                 | [ce78c6c4ee](https://linux-hardware.org/?probe=ce78c6c4ee) | Oct 05, 2022 |
| Dell          | 088DT1 A00                  | [164b0caca9](https://linux-hardware.org/?probe=164b0caca9) | Oct 04, 2022 |
| Dell          | 088DT1 A01                  | [d2f8a7069b](https://linux-hardware.org/?probe=d2f8a7069b) | Oct 04, 2022 |
| MSI           | H81M-E34                    | [ddae6a50ce](https://linux-hardware.org/?probe=ddae6a50ce) | Oct 04, 2022 |
| HP            | 1497                        | [17a2f79f3f](https://linux-hardware.org/?probe=17a2f79f3f) | Oct 04, 2022 |
| HP            | 1497                        | [fab365512a](https://linux-hardware.org/?probe=fab365512a) | Oct 04, 2022 |
| ASUSTek       | G15DK                       | [3c8be02775](https://linux-hardware.org/?probe=3c8be02775) | Oct 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [9954860560](https://linux-hardware.org/?probe=9954860560) | Oct 04, 2022 |
| Biostar       | A960D+V2                    | [9199dbc3dc](https://linux-hardware.org/?probe=9199dbc3dc) | Oct 03, 2022 |
| ASUSTek       | G15DK                       | [76a03b7071](https://linux-hardware.org/?probe=76a03b7071) | Oct 03, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [b278d1ade6](https://linux-hardware.org/?probe=b278d1ade6) | Oct 03, 2022 |
| ASUSTek       | P8Z68-V LX                  | [42b887e821](https://linux-hardware.org/?probe=42b887e821) | Oct 03, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [44c003007e](https://linux-hardware.org/?probe=44c003007e) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M58p 6209CM1    | [15fb3b5261](https://linux-hardware.org/?probe=15fb3b5261) | Oct 02, 2022 |
| MSI           | X570-A PRO                  | [ba513cf2ee](https://linux-hardware.org/?probe=ba513cf2ee) | Oct 02, 2022 |
| Apple         | Mac-F221BEC8                | [15ed095440](https://linux-hardware.org/?probe=15ed095440) | Oct 02, 2022 |
| MSI           | 970A-G43                    | [c8f6fa5b53](https://linux-hardware.org/?probe=c8f6fa5b53) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [7309d377f6](https://linux-hardware.org/?probe=7309d377f6) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [aedfaab130](https://linux-hardware.org/?probe=aedfaab130) | Oct 02, 2022 |
| Unknown       | X79-P3                      | [9269fd5ff4](https://linux-hardware.org/?probe=9269fd5ff4) | Oct 01, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ff1c77c45a](https://linux-hardware.org/?probe=ff1c77c45a) | Oct 01, 2022 |
| Positivo      | POS-PIH81DL                 | [c17fe23ea7](https://linux-hardware.org/?probe=c17fe23ea7) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M58 9728AHG     | [a2bc7fc88f](https://linux-hardware.org/?probe=a2bc7fc88f) | Oct 01, 2022 |
| Dell          | 0RW203                      | [c8a408311d](https://linux-hardware.org/?probe=c8a408311d) | Oct 01, 2022 |
| ASUSTek       | B75M-A                      | [cbeab03cbd](https://linux-hardware.org/?probe=cbeab03cbd) | Oct 01, 2022 |
| Foxconn       | 2AB1                        | [18971aaf86](https://linux-hardware.org/?probe=18971aaf86) | Oct 01, 2022 |
| Apple         | Mac-F221BEC8                | [ab0a3e1a94](https://linux-hardware.org/?probe=ab0a3e1a94) | Sep 30, 2022 |
| Dell          | 0NK70N A03                  | [9cfa433855](https://linux-hardware.org/?probe=9cfa433855) | Sep 30, 2022 |
| ASUSTek       | P8H67-M                     | [583fe6d90d](https://linux-hardware.org/?probe=583fe6d90d) | Sep 30, 2022 |
| Lenovo        | ThinkCentre M58 9728AHG     | [773ae7f01e](https://linux-hardware.org/?probe=773ae7f01e) | Sep 30, 2022 |
| ASRock        | N68C-S UCC                  | [90d8579454](https://linux-hardware.org/?probe=90d8579454) | Sep 30, 2022 |
| Dell          | 0KJCC5 A00                  | [f9582eb0a8](https://linux-hardware.org/?probe=f9582eb0a8) | Sep 29, 2022 |
| HP            | 158A                        | [151ee8b7d6](https://linux-hardware.org/?probe=151ee8b7d6) | Sep 29, 2022 |
| HP            | 81C9                        | [c92ebd45a9](https://linux-hardware.org/?probe=c92ebd45a9) | Sep 29, 2022 |
| Acer          | Veriton X6610G              | [66733e59e2](https://linux-hardware.org/?probe=66733e59e2) | Sep 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [25e3064dd2](https://linux-hardware.org/?probe=25e3064dd2) | Sep 29, 2022 |
| Dell          | 0NK70N A03                  | [7e2d1b00fd](https://linux-hardware.org/?probe=7e2d1b00fd) | Sep 28, 2022 |
| Dell          | 06D7TR A02                  | [a0d832ff6a](https://linux-hardware.org/?probe=a0d832ff6a) | Sep 28, 2022 |
| MSI           | X299 SLI PLUS               | [1695ba8137](https://linux-hardware.org/?probe=1695ba8137) | Sep 28, 2022 |
| ASUSTek       | PRIME B450M-K               | [262a244d81](https://linux-hardware.org/?probe=262a244d81) | Sep 28, 2022 |
| ASUSTek       | M5A97 R2.0                  | [9b3c73c104](https://linux-hardware.org/?probe=9b3c73c104) | Sep 28, 2022 |
| ASUSTek       | M5A97 R2.0                  | [4cdcef3ebd](https://linux-hardware.org/?probe=4cdcef3ebd) | Sep 28, 2022 |
| MSI           | B550-A PRO                  | [2a5a7aeb95](https://linux-hardware.org/?probe=2a5a7aeb95) | Sep 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [63cd838fcc](https://linux-hardware.org/?probe=63cd838fcc) | Sep 27, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1979013fa2](https://linux-hardware.org/?probe=1979013fa2) | Sep 27, 2022 |
| HP            | 8433 11                     | [a1d424bced](https://linux-hardware.org/?probe=a1d424bced) | Sep 27, 2022 |
| HP            | 802F                        | [12645dcde4](https://linux-hardware.org/?probe=12645dcde4) | Sep 27, 2022 |
| Dell          | 018D1Y A00                  | [744202f733](https://linux-hardware.org/?probe=744202f733) | Sep 26, 2022 |
| Biostar       | TH67XE                      | [24df0079b5](https://linux-hardware.org/?probe=24df0079b5) | Sep 26, 2022 |
| HP            | 1494                        | [aa2bd7da6c](https://linux-hardware.org/?probe=aa2bd7da6c) | Sep 26, 2022 |
| ASUSTek       | P5N7A-VM                    | [e8ac8a9926](https://linux-hardware.org/?probe=e8ac8a9926) | Sep 26, 2022 |
| Gigabyte      | 970A-DS3P                   | [202e51c5d3](https://linux-hardware.org/?probe=202e51c5d3) | Sep 26, 2022 |
| MSI           | A68HM-E33 V2                | [939c0c0a19](https://linux-hardware.org/?probe=939c0c0a19) | Sep 25, 2022 |
| ASUSTek       | B150-PLUS                   | [c64181dd6a](https://linux-hardware.org/?probe=c64181dd6a) | Sep 25, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [dfdb7b73ae](https://linux-hardware.org/?probe=dfdb7b73ae) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [208c7988f7](https://linux-hardware.org/?probe=208c7988f7) | Sep 25, 2022 |
| HP            | 8433 11                     | [dffc61c155](https://linux-hardware.org/?probe=dffc61c155) | Sep 24, 2022 |
| HP            | 802F                        | [2390f9c154](https://linux-hardware.org/?probe=2390f9c154) | Sep 24, 2022 |
| ASUSTek       | Leonite2                    | [f7e1dc7c9d](https://linux-hardware.org/?probe=f7e1dc7c9d) | Sep 24, 2022 |
| ASUSTek       | Leonite2                    | [63d494787f](https://linux-hardware.org/?probe=63d494787f) | Sep 24, 2022 |
| ASRock        | 4CoreDual-SATA2             | [eb0e992df7](https://linux-hardware.org/?probe=eb0e992df7) | Sep 24, 2022 |
| Dell          | 0C7195                      | [9711ab00d7](https://linux-hardware.org/?probe=9711ab00d7) | Sep 24, 2022 |
| Gigabyte      | G31M-S2C                    | [d0aa96a903](https://linux-hardware.org/?probe=d0aa96a903) | Sep 24, 2022 |
| MSI           | H510M PRO                   | [bb7475d072](https://linux-hardware.org/?probe=bb7475d072) | Sep 24, 2022 |
| Lenovo        | NO DPK                      | [7bdaedd0f7](https://linux-hardware.org/?probe=7bdaedd0f7) | Sep 24, 2022 |
| Gateway       | IPISB-VR                    | [21ee50eb69](https://linux-hardware.org/?probe=21ee50eb69) | Sep 24, 2022 |
| ASUSTek       | P8B75-M LE                  | [8975676700](https://linux-hardware.org/?probe=8975676700) | Sep 24, 2022 |
| ASRock        | X399 Taichi                 | [e6de41eac0](https://linux-hardware.org/?probe=e6de41eac0) | Sep 24, 2022 |
| HP            | 8643 SMVB                   | [c2e100d58d](https://linux-hardware.org/?probe=c2e100d58d) | Sep 24, 2022 |
| HP            | 802F                        | [1b25932752](https://linux-hardware.org/?probe=1b25932752) | Sep 23, 2022 |
| HP            | 8055                        | [a45563167c](https://linux-hardware.org/?probe=a45563167c) | Sep 23, 2022 |
| Medion        | B460H6-EM                   | [9ab2a06631](https://linux-hardware.org/?probe=9ab2a06631) | Sep 23, 2022 |
| ASUSTek       | M2N68-AM SE2                | [412f70b76b](https://linux-hardware.org/?probe=412f70b76b) | Sep 23, 2022 |
| Medion        | H110H4-EM                   | [2fa25ddedf](https://linux-hardware.org/?probe=2fa25ddedf) | Sep 23, 2022 |
| Dell          | 0WR7PY A02                  | [0c47cbc25d](https://linux-hardware.org/?probe=0c47cbc25d) | Sep 23, 2022 |
| Medion        | H110H4-EM                   | [8e7d4a7aeb](https://linux-hardware.org/?probe=8e7d4a7aeb) | Sep 23, 2022 |
| Dell          | 0WR7PY A02                  | [53fc678043](https://linux-hardware.org/?probe=53fc678043) | Sep 23, 2022 |
| HP            | 0AA0h                       | [5757039d29](https://linux-hardware.org/?probe=5757039d29) | Sep 23, 2022 |
| MSI           | B350 PC MATE                | [0c4332eead](https://linux-hardware.org/?probe=0c4332eead) | Sep 23, 2022 |
| HP            | 1494                        | [cd3778e7eb](https://linux-hardware.org/?probe=cd3778e7eb) | Sep 22, 2022 |
| MSI           | 760GM-P34                   | [af750add66](https://linux-hardware.org/?probe=af750add66) | Sep 22, 2022 |
| HP            | 1494                        | [4a3ad3e89d](https://linux-hardware.org/?probe=4a3ad3e89d) | Sep 22, 2022 |
| ASUSTek       | M5A78L-M LX3                | [75a6fc3a08](https://linux-hardware.org/?probe=75a6fc3a08) | Sep 22, 2022 |
| Gigabyte      | 945GM-S2                    | [9fcea940e6](https://linux-hardware.org/?probe=9fcea940e6) | Sep 22, 2022 |
| Gigabyte      | 990FXA-UD5                  | [7c8d5609e0](https://linux-hardware.org/?probe=7c8d5609e0) | Sep 22, 2022 |
| ASUSTek       | P5B                         | [f265d37bf5](https://linux-hardware.org/?probe=f265d37bf5) | Sep 22, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [e1af6b9e74](https://linux-hardware.org/?probe=e1af6b9e74) | Sep 22, 2022 |
| OEM           | B75 Ver:1.41                | [e22d2bac17](https://linux-hardware.org/?probe=e22d2bac17) | Sep 22, 2022 |
| HP            | 802F                        | [1f4d3353d2](https://linux-hardware.org/?probe=1f4d3353d2) | Sep 22, 2022 |
| ASUSTek       | PRIME Z390-A                | [5e4d865987](https://linux-hardware.org/?probe=5e4d865987) | Sep 21, 2022 |
| HP            | 1494                        | [5018a8dade](https://linux-hardware.org/?probe=5018a8dade) | Sep 21, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | [67067bfc09](https://linux-hardware.org/?probe=67067bfc09) | Sep 21, 2022 |
| Gigabyte      | Z590 UD AC                  | [3add13cf6d](https://linux-hardware.org/?probe=3add13cf6d) | Sep 21, 2022 |
| Dell          | 0773VG A02                  | [84f143d4ea](https://linux-hardware.org/?probe=84f143d4ea) | Sep 21, 2022 |
| Dell          | 0D6H9T A00                  | [63b718ac3a](https://linux-hardware.org/?probe=63b718ac3a) | Sep 21, 2022 |
| ASUSTek       | PRIME B450M-A               | [2ac923fd8c](https://linux-hardware.org/?probe=2ac923fd8c) | Sep 21, 2022 |
| Dell          | 0D6H9T A00                  | [90437079a3](https://linux-hardware.org/?probe=90437079a3) | Sep 20, 2022 |
| Digiboard     | NM70-TI                     | [ace83d527c](https://linux-hardware.org/?probe=ace83d527c) | Sep 20, 2022 |
| ASUSTek       | Z97-A                       | [cc9467d0fe](https://linux-hardware.org/?probe=cc9467d0fe) | Sep 20, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [94d45ff789](https://linux-hardware.org/?probe=94d45ff789) | Sep 19, 2022 |
| HP            | 81C9                        | [3795beb1c4](https://linux-hardware.org/?probe=3795beb1c4) | Sep 19, 2022 |
| Intel         | DH61BF AAG81311-101         | [43c2f57807](https://linux-hardware.org/?probe=43c2f57807) | Sep 19, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [aba8915769](https://linux-hardware.org/?probe=aba8915769) | Sep 19, 2022 |
| Intel         | DG33BU AAD79951-407         | [d35104af13](https://linux-hardware.org/?probe=d35104af13) | Sep 19, 2022 |
| Gigabyte      | H97M-D3H                    | [57db36ecc9](https://linux-hardware.org/?probe=57db36ecc9) | Sep 19, 2022 |
| HP            | 0AA8h                       | [3c274fc7f3](https://linux-hardware.org/?probe=3c274fc7f3) | Sep 19, 2022 |
| Wistron       | ProLiant ML110 G6           | [c986542d56](https://linux-hardware.org/?probe=c986542d56) | Sep 18, 2022 |
| Wistron       | ProLiant ML110 G6           | [a17cc62b40](https://linux-hardware.org/?probe=a17cc62b40) | Sep 18, 2022 |
| Gigabyte      | H61M-DS2                    | [3a2c9cfad3](https://linux-hardware.org/?probe=3a2c9cfad3) | Sep 18, 2022 |
| Gigabyte      | F2A88X-D3H                  | [55ab1865a0](https://linux-hardware.org/?probe=55ab1865a0) | Sep 18, 2022 |
| BESSTAR Te... | TH50                        | [916e9d7e5e](https://linux-hardware.org/?probe=916e9d7e5e) | Sep 18, 2022 |
| HP            | 18E7                        | [710a40851e](https://linux-hardware.org/?probe=710a40851e) | Sep 18, 2022 |
| ASUSTek       | P5G41T-M LX                 | [50647a7656](https://linux-hardware.org/?probe=50647a7656) | Sep 17, 2022 |
| Foxconn       | G31MXP FAB:1.1              | [d401319e57](https://linux-hardware.org/?probe=d401319e57) | Sep 17, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b3350b3f69](https://linux-hardware.org/?probe=b3350b3f69) | Sep 17, 2022 |
| Intel         | X79M-S                      | [91e75d3183](https://linux-hardware.org/?probe=91e75d3183) | Sep 17, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [b9693eaf7c](https://linux-hardware.org/?probe=b9693eaf7c) | Sep 17, 2022 |
| Intel         | X79M-S                      | [48c5f5ed77](https://linux-hardware.org/?probe=48c5f5ed77) | Sep 17, 2022 |
| ASUSTek       | P5K                         | [4cf17a7b6f](https://linux-hardware.org/?probe=4cf17a7b6f) | Sep 17, 2022 |
| ASUSTek       | P5K                         | [4a3727841e](https://linux-hardware.org/?probe=4a3727841e) | Sep 17, 2022 |
| Dell          | 0F5C5X A00                  | [db1c09a2cc](https://linux-hardware.org/?probe=db1c09a2cc) | Sep 16, 2022 |
| System76      | Thelio Mira thelio-mira-... | [e5e20422fd](https://linux-hardware.org/?probe=e5e20422fd) | Sep 16, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [e6fe8aa148](https://linux-hardware.org/?probe=e6fe8aa148) | Sep 16, 2022 |
| ASUSTek       | P5B                         | [37bf9261b4](https://linux-hardware.org/?probe=37bf9261b4) | Sep 16, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [26699f7431](https://linux-hardware.org/?probe=26699f7431) | Sep 16, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [b8262094b0](https://linux-hardware.org/?probe=b8262094b0) | Sep 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c99c4f9785](https://linux-hardware.org/?probe=c99c4f9785) | Sep 15, 2022 |
| AZW           | GK mini                     | [19b8b4dc85](https://linux-hardware.org/?probe=19b8b4dc85) | Sep 15, 2022 |
| ASUSTek       | H81M-K                      | [fe48912653](https://linux-hardware.org/?probe=fe48912653) | Sep 15, 2022 |
| ASUSTek       | H81M-K                      | [a6bc49b4f3](https://linux-hardware.org/?probe=a6bc49b4f3) | Sep 15, 2022 |
| HP            | 18E6                        | [d95bebd7fe](https://linux-hardware.org/?probe=d95bebd7fe) | Sep 15, 2022 |
| HP            | 339A                        | [78e4f67b19](https://linux-hardware.org/?probe=78e4f67b19) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | [b05bacb493](https://linux-hardware.org/?probe=b05bacb493) | Sep 14, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [87f0f15c82](https://linux-hardware.org/?probe=87f0f15c82) | Sep 14, 2022 |
| Intel         | DH67BL AAG10189-209         | [3507c0cdb7](https://linux-hardware.org/?probe=3507c0cdb7) | Sep 14, 2022 |
| HP            | 18E6                        | [261f9e8c10](https://linux-hardware.org/?probe=261f9e8c10) | Sep 14, 2022 |
| AZW           | Green G2                    | [b52a17d2b2](https://linux-hardware.org/?probe=b52a17d2b2) | Sep 14, 2022 |
| ASUSTek       | P5B                         | [ae8f6e2ed7](https://linux-hardware.org/?probe=ae8f6e2ed7) | Sep 14, 2022 |
| Gigabyte      | B365M H                     | [20125b1c13](https://linux-hardware.org/?probe=20125b1c13) | Sep 13, 2022 |
| ASUSTek       | PRIME B350M-A               | [47b0975057](https://linux-hardware.org/?probe=47b0975057) | Sep 13, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | [70aa78efc6](https://linux-hardware.org/?probe=70aa78efc6) | Sep 13, 2022 |
| ASUSTek       | H81M-K                      | [19ddc4ed5d](https://linux-hardware.org/?probe=19ddc4ed5d) | Sep 13, 2022 |
| ASRock        | Z77 Pro4-M                  | [38928465ac](https://linux-hardware.org/?probe=38928465ac) | Sep 13, 2022 |
| Dell          | 0P01GV A03                  | [f23afc903c](https://linux-hardware.org/?probe=f23afc903c) | Sep 13, 2022 |
| ASUSTek       | PRIME B550M-A               | [fd2497acae](https://linux-hardware.org/?probe=fd2497acae) | Sep 12, 2022 |
| Gigabyte      | AX370-Gaming K3             | [e3720a691a](https://linux-hardware.org/?probe=e3720a691a) | Sep 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b251a95678](https://linux-hardware.org/?probe=b251a95678) | Sep 12, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [00bca0eeff](https://linux-hardware.org/?probe=00bca0eeff) | Sep 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b3c2018879](https://linux-hardware.org/?probe=b3c2018879) | Sep 12, 2022 |
| PCWare        | IPMH61R3                    | [2312ab0f92](https://linux-hardware.org/?probe=2312ab0f92) | Sep 12, 2022 |
| ASRock        | B450 Gaming K4              | [2391f4673a](https://linux-hardware.org/?probe=2391f4673a) | Sep 12, 2022 |
| ASRock        | B450 Gaming K4              | [89963f6bf1](https://linux-hardware.org/?probe=89963f6bf1) | Sep 12, 2022 |
| Gigabyte      | H61MS                       | [9b10176111](https://linux-hardware.org/?probe=9b10176111) | Sep 12, 2022 |
| Gigabyte      | H81M-D2V                    | [6da1838df1](https://linux-hardware.org/?probe=6da1838df1) | Sep 12, 2022 |
| Unknown       | Unknown                     | [637418c4f3](https://linux-hardware.org/?probe=637418c4f3) | Sep 12, 2022 |
| ASUSTek       | PRIME X370-PRO              | [2228f0dc13](https://linux-hardware.org/?probe=2228f0dc13) | Sep 12, 2022 |
| HP            | 8464                        | [50cb2002e6](https://linux-hardware.org/?probe=50cb2002e6) | Sep 12, 2022 |
| ECS           | G31T-M9                     | [547762d8bf](https://linux-hardware.org/?probe=547762d8bf) | Sep 11, 2022 |
| Dell          | 09KPNV A00                  | [7063a1b842](https://linux-hardware.org/?probe=7063a1b842) | Sep 11, 2022 |
| Dell          | 09KPNV A00                  | [8d243eeb2a](https://linux-hardware.org/?probe=8d243eeb2a) | Sep 11, 2022 |
| Gigabyte      | H61M-DS2                    | [105dae5731](https://linux-hardware.org/?probe=105dae5731) | Sep 11, 2022 |
| Pegatron      | Benicia                     | [1f8dceb256](https://linux-hardware.org/?probe=1f8dceb256) | Sep 11, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [c7eb1fd4ca](https://linux-hardware.org/?probe=c7eb1fd4ca) | Sep 11, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4df5d0194d](https://linux-hardware.org/?probe=4df5d0194d) | Sep 11, 2022 |
| Foxconn       | 2AA9                        | [b671b09c1a](https://linux-hardware.org/?probe=b671b09c1a) | Sep 11, 2022 |
| HP            | ProLiant MicroServer        | [a36990dcf7](https://linux-hardware.org/?probe=a36990dcf7) | Sep 10, 2022 |
| ASUSTek       | P5N7A-VM                    | [ac23f75aa7](https://linux-hardware.org/?probe=ac23f75aa7) | Sep 10, 2022 |
| ECS           | H61H2-M6                    | [99f3146843](https://linux-hardware.org/?probe=99f3146843) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | [d79e449b58](https://linux-hardware.org/?probe=d79e449b58) | Sep 10, 2022 |
| ASUSTek       | M5A78L/USB3                 | [49158d0782](https://linux-hardware.org/?probe=49158d0782) | Sep 10, 2022 |
| MSI           | B550-A PRO                  | [f1bdda02e5](https://linux-hardware.org/?probe=f1bdda02e5) | Sep 10, 2022 |
| ASUSTek       | H81M-E                      | [1a9835fb13](https://linux-hardware.org/?probe=1a9835fb13) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5aa9031e93](https://linux-hardware.org/?probe=5aa9031e93) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [81fcfbb095](https://linux-hardware.org/?probe=81fcfbb095) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | [1d6ec4fb3b](https://linux-hardware.org/?probe=1d6ec4fb3b) | Sep 10, 2022 |
| HP            | ProLiant MicroServer        | [6d58a3f327](https://linux-hardware.org/?probe=6d58a3f327) | Sep 09, 2022 |
| HP            | ProLiant MicroServer        | [08e7851933](https://linux-hardware.org/?probe=08e7851933) | Sep 09, 2022 |
| Gigabyte      | X570 AORUS PRO              | [8d1d861b1c](https://linux-hardware.org/?probe=8d1d861b1c) | Sep 09, 2022 |
| Dell          | 0P01GV A03                  | [d71609c89e](https://linux-hardware.org/?probe=d71609c89e) | Sep 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [951a99cc8f](https://linux-hardware.org/?probe=951a99cc8f) | Sep 09, 2022 |
| Dell          | 0C7195                      | [728b74ef0c](https://linux-hardware.org/?probe=728b74ef0c) | Sep 09, 2022 |
| Dell          | 08NPPY A00                  | [55cf772a79](https://linux-hardware.org/?probe=55cf772a79) | Sep 09, 2022 |
| MSI           | MS-7817                     | [99a24afc9e](https://linux-hardware.org/?probe=99a24afc9e) | Sep 09, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [2c39df8b9f](https://linux-hardware.org/?probe=2c39df8b9f) | Sep 08, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [246c6ed8a6](https://linux-hardware.org/?probe=246c6ed8a6) | Sep 08, 2022 |
| Packard Be... | IMEDIA S2883                | [c4fe9ee6f0](https://linux-hardware.org/?probe=c4fe9ee6f0) | Sep 08, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [04b2bf9115](https://linux-hardware.org/?probe=04b2bf9115) | Sep 08, 2022 |
| Gigabyte      | H310M S2P                   | [aaab0c5335](https://linux-hardware.org/?probe=aaab0c5335) | Sep 08, 2022 |
| ASUSTek       | PRIME B450M-K II            | [c7a272ed96](https://linux-hardware.org/?probe=c7a272ed96) | Sep 08, 2022 |
| Pegatron      | Benicia                     | [95339a1bdd](https://linux-hardware.org/?probe=95339a1bdd) | Sep 08, 2022 |
| Gigabyte      | M68MT-S2                    | [86af6e4676](https://linux-hardware.org/?probe=86af6e4676) | Sep 08, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a355222b61](https://linux-hardware.org/?probe=a355222b61) | Sep 07, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [a45b18c4bb](https://linux-hardware.org/?probe=a45b18c4bb) | Sep 07, 2022 |
| Dell          | 0JCTF8 A00                  | [7a0145000a](https://linux-hardware.org/?probe=7a0145000a) | Sep 07, 2022 |
| Dell          | 0DR845                      | [f945fc3f5e](https://linux-hardware.org/?probe=f945fc3f5e) | Sep 07, 2022 |
| Dell          | 0M863N A01                  | [a353883ee2](https://linux-hardware.org/?probe=a353883ee2) | Sep 07, 2022 |
| MSI           | Z170A GAMING PRO            | [e690f6c747](https://linux-hardware.org/?probe=e690f6c747) | Sep 06, 2022 |
| MSI           | Z97 PC Mate                 | [512c793b51](https://linux-hardware.org/?probe=512c793b51) | Sep 06, 2022 |
| MSI           | 760GM-P21                   | [c3eb52f6ab](https://linux-hardware.org/?probe=c3eb52f6ab) | Sep 06, 2022 |
| HP            | 8265                        | [2b74e032bd](https://linux-hardware.org/?probe=2b74e032bd) | Sep 06, 2022 |
| Gigabyte      | A320M-S2H-CF                | [bcdb385277](https://linux-hardware.org/?probe=bcdb385277) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [ab4f06e457](https://linux-hardware.org/?probe=ab4f06e457) | Sep 05, 2022 |
| ASUSTek       | H81M-PLUS                   | [826b486f77](https://linux-hardware.org/?probe=826b486f77) | Sep 05, 2022 |
| HP            | 8265                        | [f7f460fb43](https://linux-hardware.org/?probe=f7f460fb43) | Sep 05, 2022 |
| ASUSTek       | P9X79 DELUXE                | [2aa7ada396](https://linux-hardware.org/?probe=2aa7ada396) | Sep 05, 2022 |
| Gigabyte      | Z690 AERO G DDR4            | [ccd383a106](https://linux-hardware.org/?probe=ccd383a106) | Sep 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2176e4d70f](https://linux-hardware.org/?probe=2176e4d70f) | Sep 05, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [1f5b368c96](https://linux-hardware.org/?probe=1f5b368c96) | Sep 05, 2022 |
| Gigabyte      | GA-M56S-S3                  | [8b8ba6c7f9](https://linux-hardware.org/?probe=8b8ba6c7f9) | Sep 05, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [9cd2bcff37](https://linux-hardware.org/?probe=9cd2bcff37) | Sep 04, 2022 |
| AMI           | Cherry Trail CR             | [63136bf463](https://linux-hardware.org/?probe=63136bf463) | Sep 04, 2022 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | [ed16086671](https://linux-hardware.org/?probe=ed16086671) | Sep 04, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | [0859dbdb1c](https://linux-hardware.org/?probe=0859dbdb1c) | Sep 04, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [106bdf4d1b](https://linux-hardware.org/?probe=106bdf4d1b) | Sep 04, 2022 |
| Intel         | DQ67SW AAG12527-306         | [9ab6c11be2](https://linux-hardware.org/?probe=9ab6c11be2) | Sep 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [312013ef36](https://linux-hardware.org/?probe=312013ef36) | Sep 03, 2022 |
| Gigabyte      | B560 HD3                    | [35c081a440](https://linux-hardware.org/?probe=35c081a440) | Sep 03, 2022 |
| Gigabyte      | GA-880GA-UD3H               | [14af0852b9](https://linux-hardware.org/?probe=14af0852b9) | Sep 03, 2022 |
| Gigabyte      | GA-880GA-UD3H               | [6c80288d39](https://linux-hardware.org/?probe=6c80288d39) | Sep 03, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [709825bde3](https://linux-hardware.org/?probe=709825bde3) | Sep 03, 2022 |
| MSI           | H170 GAMING M3              | [b0d669cf4b](https://linux-hardware.org/?probe=b0d669cf4b) | Sep 03, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c13f075f83](https://linux-hardware.org/?probe=c13f075f83) | Sep 03, 2022 |
| ASRock        | 4CoreDual-SATA2             | [c64d84d331](https://linux-hardware.org/?probe=c64d84d331) | Sep 03, 2022 |
| Intel         | X79M-S                      | [a435283f55](https://linux-hardware.org/?probe=a435283f55) | Sep 03, 2022 |
| HP            | 2AF3                        | [58eae39fe2](https://linux-hardware.org/?probe=58eae39fe2) | Sep 03, 2022 |
| ASUSTek       | PRIME Z270-A                | [e742b2e06c](https://linux-hardware.org/?probe=e742b2e06c) | Sep 03, 2022 |
| ASRock        | Q1900-ITX                   | [3f3708d874](https://linux-hardware.org/?probe=3f3708d874) | Sep 02, 2022 |
| ASRock        | A520M-HVS                   | [69253a16ad](https://linux-hardware.org/?probe=69253a16ad) | Sep 02, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | [b765d1e662](https://linux-hardware.org/?probe=b765d1e662) | Sep 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [a2878122de](https://linux-hardware.org/?probe=a2878122de) | Sep 01, 2022 |
| Gigabyte      | Z370 HD3-OP-CF              | [55f8dbfb24](https://linux-hardware.org/?probe=55f8dbfb24) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [836d60c547](https://linux-hardware.org/?probe=836d60c547) | Sep 01, 2022 |
| Gigabyte      | Z370 HD3-OP-CF              | [ead5d021a7](https://linux-hardware.org/?probe=ead5d021a7) | Sep 01, 2022 |
| Gigabyte      | Z97-HD3                     | [32e71c2905](https://linux-hardware.org/?probe=32e71c2905) | Sep 01, 2022 |
| HP            | 1589                        | [fce9004571](https://linux-hardware.org/?probe=fce9004571) | Sep 01, 2022 |
| MSI           | H110M GAMING                | [2699df47df](https://linux-hardware.org/?probe=2699df47df) | Sep 01, 2022 |
| HP            | 3398                        | [8b5bad68cb](https://linux-hardware.org/?probe=8b5bad68cb) | Sep 01, 2022 |
| Gigabyte      | 990FXA-UD5                  | [e5364d8761](https://linux-hardware.org/?probe=e5364d8761) | Sep 01, 2022 |
| ECS           | H61H2-M2                    | [9735a8ef90](https://linux-hardware.org/?probe=9735a8ef90) | Sep 01, 2022 |
| Unknown       | HX90                        | [71295a28ed](https://linux-hardware.org/?probe=71295a28ed) | Sep 01, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [ea730c9b2d](https://linux-hardware.org/?probe=ea730c9b2d) | Sep 01, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [d98546fd95](https://linux-hardware.org/?probe=d98546fd95) | Aug 31, 2022 |
| Dell          | 0R092H                      | [1a3a337c23](https://linux-hardware.org/?probe=1a3a337c23) | Aug 31, 2022 |
| JGINYUE       | B85I PLUS V2.1              | [d171691ef3](https://linux-hardware.org/?probe=d171691ef3) | Aug 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [1f8274de5a](https://linux-hardware.org/?probe=1f8274de5a) | Aug 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [567bf4b44a](https://linux-hardware.org/?probe=567bf4b44a) | Aug 31, 2022 |
| ASUSTek       | GL10DH                      | [c197df704f](https://linux-hardware.org/?probe=c197df704f) | Aug 31, 2022 |
| HP            | 805A                        | [477936d851](https://linux-hardware.org/?probe=477936d851) | Aug 30, 2022 |
| ASRock        | N68-S UCC                   | [1d38f1f08e](https://linux-hardware.org/?probe=1d38f1f08e) | Aug 30, 2022 |
| ASUSTek       | M2N-TE                      | [82e7cc26e7](https://linux-hardware.org/?probe=82e7cc26e7) | Aug 30, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [70ee26740a](https://linux-hardware.org/?probe=70ee26740a) | Aug 30, 2022 |
| HP            | 2B36                        | [c6de6225af](https://linux-hardware.org/?probe=c6de6225af) | Aug 29, 2022 |
| OEM           | G41 775 ICH7 8712           | [4225df6517](https://linux-hardware.org/?probe=4225df6517) | Aug 29, 2022 |
| Gigabyte      | B365M D3H-CF                | [4a96f9e792](https://linux-hardware.org/?probe=4a96f9e792) | Aug 29, 2022 |
| Medion        | Cattle24 1M                 | [eb19c533e0](https://linux-hardware.org/?probe=eb19c533e0) | Aug 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [7a2c713719](https://linux-hardware.org/?probe=7a2c713719) | Aug 29, 2022 |
| ASRock        | N68-S                       | [9d18792f64](https://linux-hardware.org/?probe=9d18792f64) | Aug 29, 2022 |
| MSI           | MAG B550M MORTAR            | [82ff6d598a](https://linux-hardware.org/?probe=82ff6d598a) | Aug 29, 2022 |
| OEM           | Intel H81                   | [8732ebea02](https://linux-hardware.org/?probe=8732ebea02) | Aug 29, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [c7ace10271](https://linux-hardware.org/?probe=c7ace10271) | Aug 28, 2022 |
| Gigabyte      | GA-870A-UD3                 | [809a84e36c](https://linux-hardware.org/?probe=809a84e36c) | Aug 28, 2022 |
| Gigabyte      | GA-870A-UD3                 | [d037b5e961](https://linux-hardware.org/?probe=d037b5e961) | Aug 28, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [17e8c1560b](https://linux-hardware.org/?probe=17e8c1560b) | Aug 28, 2022 |
| Acer          | Aspire TC-780               | [eba35d616c](https://linux-hardware.org/?probe=eba35d616c) | Aug 28, 2022 |
| Unknown       | 1.0                         | [38ebf9fce3](https://linux-hardware.org/?probe=38ebf9fce3) | Aug 28, 2022 |
| Shuttle       | XH310V2                     | [375b995195](https://linux-hardware.org/?probe=375b995195) | Aug 28, 2022 |
| Gigabyte      | A320M-S2H-CF                | [b7ebc75f83](https://linux-hardware.org/?probe=b7ebc75f83) | Aug 28, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [942675a80c](https://linux-hardware.org/?probe=942675a80c) | Aug 28, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [273e1c9459](https://linux-hardware.org/?probe=273e1c9459) | Aug 27, 2022 |
| HP            | 2820h                       | [66e45394e9](https://linux-hardware.org/?probe=66e45394e9) | Aug 27, 2022 |
| Gigabyte      | M61PME-S2                   | [8f8107b683](https://linux-hardware.org/?probe=8f8107b683) | Aug 27, 2022 |
| ASUSTek       | Z170-K                      | [137641269c](https://linux-hardware.org/?probe=137641269c) | Aug 27, 2022 |
| Gigabyte      | M61PME-S2                   | [e3b89ab2db](https://linux-hardware.org/?probe=e3b89ab2db) | Aug 27, 2022 |
| Gigabyte      | Z490 UD                     | [a872472b1c](https://linux-hardware.org/?probe=a872472b1c) | Aug 26, 2022 |
| ECS           | H61H2-M2                    | [72ebc08e0c](https://linux-hardware.org/?probe=72ebc08e0c) | Aug 26, 2022 |
| ASUSTek       | M5A78L-M LX                 | [5efc5cdd53](https://linux-hardware.org/?probe=5efc5cdd53) | Aug 25, 2022 |
| ASUSTek       | Benicia                     | [08f930384d](https://linux-hardware.org/?probe=08f930384d) | Aug 25, 2022 |
| ASRock        | FM2A68M-DG3+                | [9076ba4635](https://linux-hardware.org/?probe=9076ba4635) | Aug 25, 2022 |
| ASRock        | FM2A68M-DG3+                | [6190b5c039](https://linux-hardware.org/?probe=6190b5c039) | Aug 25, 2022 |
| Lenovo        | SHARKBAY 0B98405 STD        | [f8f9cd2bfc](https://linux-hardware.org/?probe=f8f9cd2bfc) | Aug 25, 2022 |
| OEM           | Intel H81                   | [cbedace60c](https://linux-hardware.org/?probe=cbedace60c) | Aug 25, 2022 |
| MSI           | MS-7369                     | [3f701de216](https://linux-hardware.org/?probe=3f701de216) | Aug 25, 2022 |
| MSI           | H110M GAMING                | [67b7ccfcb9](https://linux-hardware.org/?probe=67b7ccfcb9) | Aug 25, 2022 |
| HP            | 18E4                        | [13d5c6848a](https://linux-hardware.org/?probe=13d5c6848a) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [94446a9884](https://linux-hardware.org/?probe=94446a9884) | Aug 24, 2022 |
| ASRock        | Z87 Extreme4                | [c1c23ef82f](https://linux-hardware.org/?probe=c1c23ef82f) | Aug 24, 2022 |
| ASUSTek       | P5B                         | [27c91a4b60](https://linux-hardware.org/?probe=27c91a4b60) | Aug 24, 2022 |
| HP            | 1906                        | [b26f30eca5](https://linux-hardware.org/?probe=b26f30eca5) | Aug 24, 2022 |
| IBASE Tech... | MI970VFA                    | [27fc0d8773](https://linux-hardware.org/?probe=27fc0d8773) | Aug 24, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [b5e5debf66](https://linux-hardware.org/?probe=b5e5debf66) | Aug 24, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [d396a491c2](https://linux-hardware.org/?probe=d396a491c2) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a8eb4233e8](https://linux-hardware.org/?probe=a8eb4233e8) | Aug 23, 2022 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [bb84a4e155](https://linux-hardware.org/?probe=bb84a4e155) | Aug 23, 2022 |
| ASUSTek       | H61M-C                      | [93ac400083](https://linux-hardware.org/?probe=93ac400083) | Aug 23, 2022 |
| ASUSTek       | VC66-C2                     | [f2f42bd538](https://linux-hardware.org/?probe=f2f42bd538) | Aug 23, 2022 |
| ASUSTek       | Z97-P                       | [bcd3bcb389](https://linux-hardware.org/?probe=bcd3bcb389) | Aug 22, 2022 |
| MSI           | P41T-C31                    | [f8487b4fdb](https://linux-hardware.org/?probe=f8487b4fdb) | Aug 22, 2022 |
| ASUSTek       | H110M-A/M.2                 | [dab0f526b0](https://linux-hardware.org/?probe=dab0f526b0) | Aug 22, 2022 |
| ASUSTek       | H61M-C                      | [8d187f0a28](https://linux-hardware.org/?probe=8d187f0a28) | Aug 22, 2022 |
| ASRock        | G41M-VS3                    | [659ccaca6e](https://linux-hardware.org/?probe=659ccaca6e) | Aug 22, 2022 |
| Dell          | 0T10XW A01                  | [30ebde5edc](https://linux-hardware.org/?probe=30ebde5edc) | Aug 21, 2022 |
| HP            | 2B36                        | [9890b96e0e](https://linux-hardware.org/?probe=9890b96e0e) | Aug 21, 2022 |
| MSI           | B550-A PRO                  | [421874f76a](https://linux-hardware.org/?probe=421874f76a) | Aug 21, 2022 |
| ECS           | H61H2-M2                    | [97ec1c67e8](https://linux-hardware.org/?probe=97ec1c67e8) | Aug 21, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [066815dcef](https://linux-hardware.org/?probe=066815dcef) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [aaf726faa0](https://linux-hardware.org/?probe=aaf726faa0) | Aug 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [ed2076bba5](https://linux-hardware.org/?probe=ed2076bba5) | Aug 20, 2022 |
| ASRock        | FM2A88X-ITX+                | [44940c79b7](https://linux-hardware.org/?probe=44940c79b7) | Aug 20, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [d5e91a17b8](https://linux-hardware.org/?probe=d5e91a17b8) | Aug 20, 2022 |
| ASUSTek       | PRIME B450M-K II            | [6b101e9381](https://linux-hardware.org/?probe=6b101e9381) | Aug 19, 2022 |
| HP            | 097Ch                       | [ac391817bc](https://linux-hardware.org/?probe=ac391817bc) | Aug 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [2494475fe0](https://linux-hardware.org/?probe=2494475fe0) | Aug 19, 2022 |
| Intel         | DH87RL AAG74240-401         | [ebc0328fe0](https://linux-hardware.org/?probe=ebc0328fe0) | Aug 19, 2022 |
| Acer          | Aspire XC-830               | [b3e0135d65](https://linux-hardware.org/?probe=b3e0135d65) | Aug 19, 2022 |
| MSI           | MS-7528                     | [723f567e19](https://linux-hardware.org/?probe=723f567e19) | Aug 19, 2022 |
| MSI           | MS-7528                     | [4d549f68ce](https://linux-hardware.org/?probe=4d549f68ce) | Aug 19, 2022 |
| ASUSTek       | H81M-E                      | [2b0b66767d](https://linux-hardware.org/?probe=2b0b66767d) | Aug 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX         | [49943f84c8](https://linux-hardware.org/?probe=49943f84c8) | Aug 18, 2022 |
| MSI           | B350M MORTAR                | [d1c6be49c4](https://linux-hardware.org/?probe=d1c6be49c4) | Aug 18, 2022 |
| Dell          | 05XGC8 A00                  | [43741daa2d](https://linux-hardware.org/?probe=43741daa2d) | Aug 18, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | [02f9463f2b](https://linux-hardware.org/?probe=02f9463f2b) | Aug 17, 2022 |
| ASRock        | 775Dual-VSTA                | [89ac2bb6fe](https://linux-hardware.org/?probe=89ac2bb6fe) | Aug 17, 2022 |
| HP            | 872B                        | [466f4962fe](https://linux-hardware.org/?probe=466f4962fe) | Aug 17, 2022 |
| ASUSTek       | P8B75-M LX                  | [1efeb7be2c](https://linux-hardware.org/?probe=1efeb7be2c) | Aug 17, 2022 |
| Intel         | DH87RL AAG74240-401         | [a8c5b732f4](https://linux-hardware.org/?probe=a8c5b732f4) | Aug 17, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Linux_Mint/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Linux Mint 20.3 | 1056     | 17.67%  |
| Linux Mint 20.1 | 898      | 15.03%  |
| Linux Mint 20.2 | 884      | 14.79%  |
| Linux Mint 19.3 | 852      | 14.26%  |
| Linux Mint 20   | 781      | 13.07%  |
| Linux Mint 19.1 | 402      | 6.73%   |
| Linux Mint 21   | 398      | 6.66%   |
| Linux Mint 19.2 | 322      | 5.39%   |
| Linux Mint 19   | 151      | 2.53%   |
| Linux Mint 18.3 | 133      | 2.23%   |
| Linux Mint 21.1 | 39       | 0.65%   |
| Linux Mint 18.2 | 30       | 0.5%    |
| Linux Mint 18.1 | 12       | 0.2%    |
| Linux Mint 18   | 9        | 0.15%   |
| Linux Mint 17.3 | 5        | 0.08%   |
| Linux Mint 17.1 | 2        | 0.03%   |
| Linux Mint 13   | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Linux Mint | 5518     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.0-91-generic  | 232      | 3.44%   |
| 5.4.0-58-generic  | 208      | 3.08%   |
| 5.4.0-42-generic  | 149      | 2.21%   |
| 5.4.0-74-generic  | 148      | 2.19%   |
| 5.4.0-65-generic  | 148      | 2.19%   |
| 5.4.0-77-generic  | 131      | 1.94%   |
| 5.4.0-81-generic  | 115      | 1.7%    |
| 5.0.0-32-generic  | 114      | 1.69%   |
| 5.4.0-72-generic  | 113      | 1.67%   |
| 5.4.0-66-generic  | 112      | 1.66%   |
| 5.4.0-88-generic  | 110      | 1.63%   |
| 4.15.0-54-generic | 107      | 1.59%   |
| 5.4.0-90-generic  | 105      | 1.56%   |
| 5.4.0-70-generic  | 105      | 1.56%   |
| 5.4.0-122-generic | 104      | 1.54%   |
| 5.4.0-73-generic  | 102      | 1.51%   |
| 5.4.0-107-generic | 102      | 1.51%   |
| 4.15.0-20-generic | 102      | 1.51%   |
| 5.15.0-56-generic | 100      | 1.48%   |
| 5.4.0-80-generic  | 98       | 1.45%   |
| 5.4.0-89-generic  | 91       | 1.35%   |
| 5.4.0-100-generic | 89       | 1.32%   |
| 5.15.0-52-generic | 87       | 1.29%   |
| 5.4.0-26-generic  | 84       | 1.24%   |
| 5.4.0-109-generic | 78       | 1.16%   |
| 5.4.0-48-generic  | 76       | 1.13%   |
| 5.4.0-121-generic | 75       | 1.11%   |
| 4.15.0-46-generic | 70       | 1.04%   |
| 5.4.0-52-generic  | 63       | 0.93%   |
| 5.15.0-48-generic | 63       | 0.93%   |
| 5.4.0-96-generic  | 62       | 0.92%   |
| 5.15.0-41-generic | 62       | 0.92%   |
| 5.4.0-104-generic | 58       | 0.86%   |
| 5.4.0-84-generic  | 57       | 0.84%   |
| 5.4.0-113-generic | 57       | 0.84%   |
| 5.3.0-46-generic  | 57       | 0.84%   |
| 5.15.0-47-generic | 57       | 0.84%   |
| 5.4.0-67-generic  | 53       | 0.79%   |
| 5.4.0-125-generic | 52       | 0.77%   |
| 5.4.0-99-generic  | 50       | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 3340     | 56.95%  |
| 4.15.0  | 891      | 15.19%  |
| 5.15.0  | 499      | 8.51%   |
| 5.3.0   | 355      | 6.05%   |
| 5.0.0   | 188      | 3.21%   |
| 5.13.0  | 124      | 2.11%   |
| 5.8.0   | 99       | 1.69%   |
| 5.11.0  | 71       | 1.21%   |
| 4.4.0   | 35       | 0.6%    |
| 4.10.0  | 34       | 0.58%   |
| 4.13.0  | 26       | 0.44%   |
| 4.18.0  | 23       | 0.39%   |
| 4.8.0   | 14       | 0.24%   |
| 5.14.0  | 10       | 0.17%   |
| 5.9.0   | 5        | 0.09%   |
| 5.19.0  | 5        | 0.09%   |
| 5.17.0  | 5        | 0.09%   |
| 5.10.0  | 5        | 0.09%   |
| 5.3.6   | 4        | 0.07%   |
| 6.0.0   | 3        | 0.05%   |
| 5.4.1   | 3        | 0.05%   |
| 5.16.0  | 3        | 0.05%   |
| 5.12.0  | 3        | 0.05%   |
| 5.0.9   | 3        | 0.05%   |
| 4.20.17 | 3        | 0.05%   |
| 4.11.0  | 3        | 0.05%   |
| 5.8.18  | 2        | 0.03%   |
| 5.7.19  | 2        | 0.03%   |
| 5.7.0   | 2        | 0.03%   |
| 5.18.12 | 2        | 0.03%   |
| 5.17.9  | 2        | 0.03%   |
| 5.15.5  | 2        | 0.03%   |
| 5.15.10 | 2        | 0.03%   |
| 5.13.4  | 2        | 0.03%   |
| 5.12.9  | 2        | 0.03%   |
| 5.11.6  | 2        | 0.03%   |
| 5.10.1  | 2        | 0.03%   |
| 5.0.21  | 2        | 0.03%   |
| 4.20.6  | 2        | 0.03%   |
| 4.16.0  | 2        | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 3346     | 57.08%  |
| 4.15    | 892      | 15.22%  |
| 5.15    | 508      | 8.67%   |
| 5.3     | 361      | 6.16%   |
| 5.0     | 199      | 3.39%   |
| 5.13    | 127      | 2.17%   |
| 5.8     | 103      | 1.76%   |
| 5.11    | 77       | 1.31%   |
| 4.4     | 35       | 0.6%    |
| 4.10    | 34       | 0.58%   |
| 4.13    | 27       | 0.46%   |
| 4.18    | 24       | 0.41%   |
| 5.10    | 14       | 0.24%   |
| 4.8     | 14       | 0.24%   |
| 5.17    | 12       | 0.2%    |
| 5.14    | 11       | 0.19%   |
| 5.9     | 8        | 0.14%   |
| 5.7     | 8        | 0.14%   |
| 4.20    | 8        | 0.14%   |
| 6.0     | 6        | 0.1%    |
| 5.16    | 6        | 0.1%    |
| 5.19    | 5        | 0.09%   |
| 5.12    | 5        | 0.09%   |
| 5.18    | 4        | 0.07%   |
| 5.6     | 3        | 0.05%   |
| 5.5     | 3        | 0.05%   |
| 5.2     | 3        | 0.05%   |
| 4.14    | 3        | 0.05%   |
| 4.11    | 3        | 0.05%   |
| 4.19    | 2        | 0.03%   |
| 4.16    | 2        | 0.03%   |
| 4.12    | 2        | 0.03%   |
| 3.19    | 2        | 0.03%   |
| 3.13    | 2        | 0.03%   |
| 4.17    | 1        | 0.02%   |
| 3.2     | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 5332     | 96.52%  |
| i686   | 192      | 3.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| X-Cinnamon      | 3269     | 57.45%  |
| MATE            | 711      | 12.5%   |
| Cinnamon        | 539      | 9.47%   |
| Unknown         | 527      | 9.26%   |
| XFCE            | 473      | 8.31%   |
| GNOME           | 108      | 1.9%    |
| KDE5            | 23       | 0.4%    |
| KDE             | 20       | 0.35%   |
| LXDE            | 6        | 0.11%   |
| Pantheon        | 2        | 0.04%   |
| KDE4            | 2        | 0.04%   |
| i3              | 2        | 0.04%   |
| Budgie          | 2        | 0.04%   |
| Trinity         | 1        | 0.02%   |
| qtile           | 1        | 0.02%   |
| LXQt            | 1        | 0.02%   |
| GNOME Flashback | 1        | 0.02%   |
| GNOME Classic   | 1        | 0.02%   |
| enlightenment   | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 5480     | 99.19%  |
| Tty     | 32       | 0.58%   |
| Wayland | 10       | 0.18%   |
| Unknown | 3        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3632     | 64.67%  |
| LightDM | 1131     | 20.14%  |
| TDM     | 775      | 13.8%   |
| MDM     | 41       | 0.73%   |
| SDDM    | 21       | 0.37%   |
| GDM     | 14       | 0.25%   |
| LXDM    | 1        | 0.02%   |
| GDM3    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1385     | 24.67%  |
| de_DE   | 790      | 14.07%  |
| Unknown | 681      | 12.13%  |
| pt_BR   | 439      | 7.82%   |
| ru_RU   | 242      | 4.31%   |
| en_GB   | 232      | 4.13%   |
| fr_FR   | 230      | 4.1%    |
| it_IT   | 150      | 2.67%   |
| en_CA   | 142      | 2.53%   |
| C       | 132      | 2.35%   |
| es_ES   | 128      | 2.28%   |
| pl_PL   | 102      | 1.82%   |
| en_AU   | 102      | 1.82%   |
| nl_NL   | 70       | 1.25%   |
| es_AR   | 61       | 1.09%   |
| pt_PT   | 41       | 0.73%   |
| cs_CZ   | 40       | 0.71%   |
| ru_UA   | 36       | 0.64%   |
| hu_HU   | 36       | 0.64%   |
| es_MX   | 33       | 0.59%   |
| de_AT   | 31       | 0.55%   |
| en_ZA   | 29       | 0.52%   |
| en_IN   | 29       | 0.52%   |
| fi_FI   | 27       | 0.48%   |
| de_CH   | 26       | 0.46%   |
| fr_CA   | 24       | 0.43%   |
| sv_SE   | 22       | 0.39%   |
| en_NZ   | 22       | 0.39%   |
| sk_SK   | 21       | 0.37%   |
| fr_BE   | 18       | 0.32%   |
| tr_TR   | 17       | 0.3%    |
| uk_UA   | 16       | 0.29%   |
| es_CO   | 15       | 0.27%   |
| es_CL   | 14       | 0.25%   |
| en_IE   | 14       | 0.25%   |
| nl_BE   | 13       | 0.23%   |
| en_PH   | 13       | 0.23%   |
| el_GR   | 13       | 0.23%   |
| ja_JP   | 11       | 0.2%    |
| es_PE   | 11       | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3524     | 62.88%  |
| EFI  | 2080     | 37.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 4816     | 85.83%  |
| Unknown | 512      | 9.12%   |
| Overlay | 112      | 2%      |
| Btrfs   | 108      | 1.92%   |
| Xfs     | 19       | 0.34%   |
| Ext2    | 17       | 0.3%    |
| Ext3    | 14       | 0.25%   |
| Zfs     | 8        | 0.14%   |
| Jfs     | 2        | 0.04%   |
| Aufs    | 2        | 0.04%   |
| Tmpfs   | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3714     | 66.33%  |
| GPT     | 1159     | 20.7%   |
| MBR     | 726      | 12.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 5054     | 90.65%  |
| Yes       | 521      | 9.35%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4467     | 79.97%  |
| Yes       | 1119     | 20.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1343     | 24.34%  |
| Gigabyte Technology | 942      | 17.07%  |
| MSI                 | 577      | 10.46%  |
| ASRock              | 529      | 9.59%   |
| Dell                | 463      | 8.39%   |
| Hewlett-Packard     | 417      | 7.56%   |
| Lenovo              | 182      | 3.3%    |
| Intel               | 161      | 2.92%   |
| Acer                | 105      | 1.9%    |
| Pegatron            | 88       | 1.59%   |
| Unknown             | 70       | 1.27%   |
| Foxconn             | 66       | 1.2%    |
| Biostar             | 66       | 1.2%    |
| ECS                 | 58       | 1.05%   |
| Fujitsu             | 47       | 0.85%   |
| Medion              | 41       | 0.74%   |
| Positivo            | 31       | 0.56%   |
| Fujitsu Siemens     | 27       | 0.49%   |
| PCWare              | 18       | 0.33%   |
| Apple               | 17       | 0.31%   |
| Gateway             | 15       | 0.27%   |
| Shuttle             | 14       | 0.25%   |
| Semp Toshiba        | 12       | 0.22%   |
| eMachines           | 12       | 0.22%   |
| Packard Bell        | 11       | 0.2%    |
| AZW                 | 11       | 0.2%    |
| OEM                 | 10       | 0.18%   |
| AMI                 | 10       | 0.18%   |
| Huanan              | 9        | 0.16%   |
| BESSTAR Tech        | 9        | 0.16%   |
| Itautec             | 8        | 0.14%   |
| Alienware           | 8        | 0.14%   |
| Supermicro          | 7        | 0.13%   |
| Megaware            | 5        | 0.09%   |
| AMD                 | 5        | 0.09%   |
| ABIT                | 5        | 0.09%   |
| Wistron             | 4        | 0.07%   |
| TYAN Computer       | 4        | 0.07%   |
| PCChips             | 4        | 0.07%   |
| Inventec            | 4        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 122      | 2.21%   |
| Unknown                      | 80       | 1.45%   |
| Dell OptiPlex 7010           | 29       | 0.53%   |
| Dell OptiPlex 790            | 28       | 0.51%   |
| MSI MS-7693                  | 27       | 0.49%   |
| ASUS M5A78L-M/USB3           | 27       | 0.49%   |
| Dell OptiPlex 780            | 26       | 0.47%   |
| ASUS TUF Gaming X570-PLUS    | 22       | 0.4%    |
| Gigabyte B450M DS3H          | 21       | 0.38%   |
| ASUS PRIME A320M-K           | 21       | 0.38%   |
| MSI MS-7C37                  | 20       | 0.36%   |
| MSI MS-7C02                  | 20       | 0.36%   |
| MSI MS-7817                  | 20       | 0.36%   |
| MSI MS-7721                  | 20       | 0.36%   |
| Dell OptiPlex 755            | 20       | 0.36%   |
| MSI MS-7C56                  | 19       | 0.34%   |
| Dell OptiPlex 9020           | 18       | 0.33%   |
| Dell OptiPlex 3020           | 18       | 0.33%   |
| MSI MS-7B86                  | 17       | 0.31%   |
| HP Compaq Elite 8300 SFF     | 17       | 0.31%   |
| Dell OptiPlex 390            | 17       | 0.31%   |
| HP EliteDesk 800 G1 SFF      | 16       | 0.29%   |
| Gigabyte 970A-DS3P           | 16       | 0.29%   |
| ASUS ROG STRIX B450-F GAMING | 16       | 0.29%   |
| MSI MS-7641                  | 15       | 0.27%   |
| HP Compaq 8200 Elite SFF PC  | 15       | 0.27%   |
| Dell OptiPlex 990            | 15       | 0.27%   |
| ASUS M5A97 R2.0              | 15       | 0.27%   |
| ASUS M5A78L-M PLUS/USB3      | 15       | 0.27%   |
| MSI MS-7B79                  | 14       | 0.25%   |
| Gigabyte GA-78LMT-USB3       | 14       | 0.25%   |
| Gigabyte G31M-ES2L           | 14       | 0.25%   |
| Dell OptiPlex 3010           | 14       | 0.25%   |
| ASRock N68C-S UCC            | 14       | 0.25%   |
| MSI MS-7A34                  | 13       | 0.24%   |
| Intel H61                    | 13       | 0.24%   |
| Intel H55                    | 13       | 0.24%   |
| HP Compaq Pro 6300 SFF       | 13       | 0.24%   |
| Dell OptiPlex 745            | 13       | 0.24%   |
| ASUS PRIME B450M-A           | 13       | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 287      | 5.2%    |
| ASUS PRIME              | 204      | 3.7%    |
| HP Compaq               | 190      | 3.44%   |
| ASUS All                | 122      | 2.21%   |
| Lenovo ThinkCentre      | 118      | 2.14%   |
| ASUS ROG                | 92       | 1.67%   |
| Unknown                 | 80       | 1.45%   |
| ASUS TUF                | 78       | 1.41%   |
| Acer Aspire             | 72       | 1.3%    |
| ASUS M5A78L-M           | 67       | 1.21%   |
| Dell Inspiron           | 66       | 1.2%    |
| HP EliteDesk            | 52       | 0.94%   |
| Dell Precision          | 45       | 0.82%   |
| ASUS P8H61-M            | 39       | 0.71%   |
| ASUS M5A97              | 36       | 0.65%   |
| HP ProDesk              | 34       | 0.62%   |
| Gigabyte B450           | 34       | 0.62%   |
| Gigabyte GA-78LMT-USB3  | 32       | 0.58%   |
| Fujitsu ESPRIMO         | 32       | 0.58%   |
| Gigabyte B450M          | 29       | 0.53%   |
| MSI MS-7693             | 27       | 0.49%   |
| ASRock B450M            | 27       | 0.49%   |
| ASUS SABERTOOTH         | 26       | 0.47%   |
| Acer Veriton            | 23       | 0.42%   |
| Gigabyte X570           | 22       | 0.4%    |
| Lenovo IdeaCentre       | 21       | 0.38%   |
| Gigabyte B550           | 21       | 0.38%   |
| MSI MS-7C37             | 20       | 0.36%   |
| MSI MS-7C02             | 20       | 0.36%   |
| MSI MS-7817             | 20       | 0.36%   |
| MSI MS-7721             | 20       | 0.36%   |
| HP Pavilion             | 20       | 0.36%   |
| Gigabyte Z390           | 20       | 0.36%   |
| Dell Vostro             | 20       | 0.36%   |
| MSI MS-7C56             | 19       | 0.34%   |
| Gigabyte A320M-S2H      | 18       | 0.33%   |
| ASUS P5KPL-AM           | 18       | 0.33%   |
| MSI MS-7B86             | 17       | 0.31%   |
| Gigabyte 970A-DS3P      | 17       | 0.31%   |
| Fujitsu Siemens ESPRIMO | 17       | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 602      | 10.91%  |
| 2011    | 526      | 9.53%   |
| 2013    | 493      | 8.93%   |
| 2018    | 476      | 8.63%   |
| 2009    | 383      | 6.94%   |
| 2010    | 368      | 6.67%   |
| 2014    | 361      | 6.54%   |
| 2020    | 326      | 5.91%   |
| 2019    | 317      | 5.74%   |
| 2017    | 301      | 5.45%   |
| 2008    | 289      | 5.24%   |
| 2007    | 249      | 4.51%   |
| 2015    | 236      | 4.28%   |
| 2016    | 225      | 4.08%   |
| 2021    | 160      | 2.9%    |
| 2006    | 112      | 2.03%   |
| 2005    | 33       | 0.6%    |
| 2022    | 31       | 0.56%   |
| 2004    | 14       | 0.25%   |
| 2003    | 11       | 0.2%    |
| 2002    | 3        | 0.05%   |
| Unknown | 2        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 5518     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 5365     | 96.93%  |
| Enabled  | 170      | 3.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 5515     | 99.95%  |
| Yes  | 3        | 0.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1293     | 22.98%  |
| 8.01-16.0       | 1179     | 20.96%  |
| 3.01-4.0        | 1055     | 18.75%  |
| 4.01-8.0        | 922      | 16.39%  |
| 32.01-64.0      | 591      | 10.5%   |
| 1.01-2.0        | 244      | 4.34%   |
| 64.01-256.0     | 128      | 2.28%   |
| 2.01-3.0        | 92       | 1.64%   |
| 24.01-32.0      | 87       | 1.55%   |
| 0.51-1.0        | 32       | 0.57%   |
| More than 256.0 | 2        | 0.04%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 2421     | 38.93%  |
| 2.01-3.0   | 1606     | 25.82%  |
| 4.01-8.0   | 731      | 11.75%  |
| 3.01-4.0   | 712      | 11.45%  |
| 0.51-1.0   | 509      | 8.18%   |
| 8.01-16.0  | 180      | 2.89%   |
| 16.01-24.0 | 22       | 0.35%   |
| 0.01-0.5   | 22       | 0.35%   |
| 24.01-32.0 | 11       | 0.18%   |
| Unknown    | 3        | 0.05%   |
| 32.01-64.0 | 2        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2309     | 40.18%  |
| 2       | 1719     | 29.92%  |
| 3       | 888      | 15.45%  |
| 4       | 450      | 7.83%   |
| 5       | 192      | 3.34%   |
| 6       | 82       | 1.43%   |
| 7       | 42       | 0.73%   |
| 0       | 29       | 0.5%    |
| 8       | 19       | 0.33%   |
| 9       | 8        | 0.14%   |
| 10      | 4        | 0.07%   |
| 14      | 2        | 0.03%   |
| 22      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3199     | 57.32%  |
| No        | 2382     | 42.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 5446     | 98.66%  |
| No        | 74       | 1.34%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3243     | 57.89%  |
| Yes       | 2359     | 42.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4175     | 74.47%  |
| Yes       | 1431     | 25.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 962      | 17.35%  |
| Germany      | 888      | 16.01%  |
| Brazil       | 636      | 11.47%  |
| Russia       | 370      | 6.67%   |
| France       | 252      | 4.54%   |
| UK           | 228      | 4.11%   |
| Canada       | 200      | 3.61%   |
| Italy        | 167      | 3.01%   |
| Spain        | 155      | 2.8%    |
| Poland       | 123      | 2.22%   |
| Netherlands  | 120      | 2.16%   |
| Australia    | 118      | 2.13%   |
| Ukraine      | 107      | 1.93%   |
| Argentina    | 67       | 1.21%   |
| Switzerland  | 59       | 1.06%   |
| Belgium      | 56       | 1.01%   |
| Austria      | 55       | 0.99%   |
| Czechia      | 51       | 0.92%   |
| Mexico       | 48       | 0.87%   |
| Hungary      | 48       | 0.87%   |
| Sweden       | 45       | 0.81%   |
| Portugal     | 41       | 0.74%   |
| Finland      | 38       | 0.69%   |
| South Africa | 36       | 0.65%   |
| India        | 36       | 0.65%   |
| Greece       | 30       | 0.54%   |
| Romania      | 27       | 0.49%   |
| Denmark      | 27       | 0.49%   |
| Turkey       | 26       | 0.47%   |
| Slovakia     | 25       | 0.45%   |
| New Zealand  | 25       | 0.45%   |
| Belarus      | 24       | 0.43%   |
| Colombia     | 23       | 0.41%   |
| Japan        | 21       | 0.38%   |
| Bulgaria     | 20       | 0.36%   |
| Serbia       | 19       | 0.34%   |
| Chile        | 18       | 0.32%   |
| Norway       | 17       | 0.31%   |
| Ireland      | 17       | 0.31%   |
| Indonesia    | 17       | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Sao Paulo         | 78       | 1.33%   |
| Moscow            | 72       | 1.23%   |
| Berlin            | 63       | 1.07%   |
| Hamburg           | 39       | 0.66%   |
| Rio de Janeiro    | 38       | 0.65%   |
| Vienna            | 36       | 0.61%   |
| Paris             | 31       | 0.53%   |
| St Petersburg     | 29       | 0.49%   |
| Munich            | 29       | 0.49%   |
| Montreal          | 26       | 0.44%   |
| Frankfurt am Main | 26       | 0.44%   |
| Amsterdam         | 26       | 0.44%   |
| Warsaw            | 25       | 0.43%   |
| Sydney            | 25       | 0.43%   |
| Madrid            | 25       | 0.43%   |
| Kyiv              | 24       | 0.41%   |
| London            | 22       | 0.38%   |
| Chicago           | 22       | 0.38%   |
| Rome              | 21       | 0.36%   |
| Brasília         | 21       | 0.36%   |
| Budapest          | 20       | 0.34%   |
| New York          | 19       | 0.32%   |
| Leipzig           | 19       | 0.32%   |
| Toronto           | 18       | 0.31%   |
| Melbourne         | 18       | 0.31%   |
| Cologne           | 18       | 0.31%   |
| Brisbane          | 18       | 0.31%   |
| Vancouver         | 16       | 0.27%   |
| Perth             | 16       | 0.27%   |
| Milan             | 16       | 0.27%   |
| Helsinki          | 16       | 0.27%   |
| Porto Alegre      | 14       | 0.24%   |
| Düsseldorf       | 14       | 0.24%   |
| Dresden           | 14       | 0.24%   |
| Belgrade          | 14       | 0.24%   |
| Barcelona         | 14       | 0.24%   |
| Athens            | 14       | 0.24%   |
| Stuttgart         | 13       | 0.22%   |
| Minsk             | 13       | 0.22%   |
| Mexico City       | 13       | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 2081     | 3490   | 21.19%  |
| Seagate                   | 2043     | 3340   | 20.8%   |
| Samsung Electronics       | 1400     | 2237   | 14.25%  |
| Kingston                  | 613      | 835    | 6.24%   |
| Toshiba                   | 463      | 613    | 4.71%   |
| Hitachi                   | 421      | 563    | 4.29%   |
| Crucial                   | 403      | 569    | 4.1%    |
| SanDisk                   | 382      | 542    | 3.89%   |
| A-DATA Technology         | 144      | 193    | 1.47%   |
| Maxtor                    | 120      | 167    | 1.22%   |
| Intel                     | 119      | 168    | 1.21%   |
| China                     | 101      | 122    | 1.03%   |
| Unknown                   | 99       | 165    | 1.01%   |
| HGST                      | 95       | 136    | 0.97%   |
| Intenso                   | 80       | 109    | 0.81%   |
| Phison                    | 70       | 102    | 0.71%   |
| SPCC                      | 61       | 80     | 0.62%   |
| OCZ                       | 61       | 77     | 0.62%   |
| Patriot                   | 57       | 68     | 0.58%   |
| PNY                       | 51       | 67     | 0.52%   |
| Corsair                   | 51       | 61     | 0.52%   |
| Silicon Motion            | 44       | 69     | 0.45%   |
| Transcend                 | 41       | 63     | 0.42%   |
| Micron Technology         | 38       | 45     | 0.39%   |
| SK hynix                  | 37       | 48     | 0.38%   |
| Goodram                   | 35       | 43     | 0.36%   |
| XPG                       | 27       | 38     | 0.27%   |
| Apacer                    | 26       | 30     | 0.26%   |
| Micron/Crucial Technology | 25       | 37     | 0.25%   |
| JMicron Technology        | 24       | 31     | 0.24%   |
| Plextor                   | 23       | 31     | 0.23%   |
| Unknown                   | 23       | 34     | 0.23%   |
| Fujitsu                   | 22       | 31     | 0.22%   |
| Team                      | 21       | 27     | 0.21%   |
| ASMT                      | 21       | 32     | 0.21%   |
| Lexar                     | 19       | 22     | 0.19%   |
| Hewlett-Packard           | 18       | 21     | 0.18%   |
| KingSpec                  | 17       | 30     | 0.17%   |
| Realtek Semiconductor     | 16       | 20     | 0.16%   |
| LITEON                    | 15       | 16     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 175      | 1.54%   |
| Kingston SA400S37240G 240GB SSD  | 147      | 1.3%    |
| Seagate ST1000DM010-2EP102 1TB   | 117      | 1.03%   |
| Toshiba DT01ACA100 1TB           | 115      | 1.01%   |
| Samsung SSD 850 EVO 250GB        | 111      | 0.98%   |
| Samsung SSD 860 EVO 500GB        | 95       | 0.84%   |
| Kingston SA400S37120G 120GB SSD  | 90       | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB         | 87       | 0.77%   |
| Seagate ST2000DM008-2FR102 2TB   | 81       | 0.71%   |
| Kingston SV300S37A120G 120GB SSD | 81       | 0.71%   |
| Seagate ST3500418AS 500GB        | 80       | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB   | 80       | 0.71%   |
| Seagate ST1000DM003-1ER162 1TB   | 72       | 0.64%   |
| Samsung SSD 850 EVO 500GB        | 69       | 0.61%   |
| Samsung SSD 860 EVO 1TB          | 67       | 0.59%   |
| Crucial CT240BX500SSD1 240GB     | 65       | 0.57%   |
| Samsung SSD 860 EVO 250GB        | 62       | 0.55%   |
| Seagate ST2000DM006-2DM164 2TB   | 60       | 0.53%   |
| WDC WD10EZEX-00BN5A0 1TB         | 58       | 0.51%   |
| Samsung NVMe SSD Drive 500GB     | 57       | 0.5%    |
| Crucial CT500MX500SSD1 500GB     | 57       | 0.5%    |
| Crucial CT1000MX500SSD1 1TB      | 57       | 0.5%    |
| Kingston SA400S37480G 480GB SSD  | 56       | 0.49%   |
| Seagate ST31000524AS 1TB         | 53       | 0.47%   |
| Seagate ST31000528AS 1TB         | 51       | 0.45%   |
| Toshiba HDWD110 1TB              | 50       | 0.44%   |
| Seagate ST2000DM001-1ER164 2TB   | 48       | 0.42%   |
| Seagate Expansion 4TB            | 48       | 0.42%   |
| Seagate ST2000DM001-1CH164 2TB   | 44       | 0.39%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 43       | 0.38%   |
| Seagate ST3500413AS 500GB        | 43       | 0.38%   |
| SanDisk SSD PLUS 240GB           | 43       | 0.38%   |
| Seagate ST4000DM004-2CV104 4TB   | 41       | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 40       | 0.35%   |
| SanDisk SDSSDA240G 240GB         | 40       | 0.35%   |
| Unknown SD/MMC/MS PRO 64GB       | 39       | 0.34%   |
| Toshiba DT01ACA200 2TB           | 39       | 0.34%   |
| Toshiba DT01ACA050 500GB         | 39       | 0.34%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 37       | 0.33%   |
| Seagate ST3500312CS 500GB        | 37       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2009     | 3249   | 35.98%  |
| WDC                 | 1882     | 3134   | 33.7%   |
| Samsung Electronics | 453      | 649    | 8.11%   |
| Toshiba             | 430      | 562    | 7.7%    |
| Hitachi             | 421      | 563    | 7.54%   |
| Maxtor              | 118      | 165    | 2.11%   |
| HGST                | 95       | 136    | 1.7%    |
| Unknown             | 47       | 64     | 0.84%   |
| Fujitsu             | 21       | 30     | 0.38%   |
| ASMT                | 19       | 30     | 0.34%   |
| Intenso             | 13       | 14     | 0.23%   |
| ExcelStor           | 7        | 9      | 0.13%   |
| Hewlett-Packard     | 6        | 7      | 0.11%   |
| WD MediaMax         | 5        | 12     | 0.09%   |
| JMicron Technology  | 5        | 8      | 0.09%   |
| Pioneer             | 4        | 5      | 0.07%   |
| HGST HTS            | 3        | 3      | 0.05%   |
| ASMT109x            | 3        | 3      | 0.05%   |
| ASMedia             | 3        | 3      | 0.05%   |
| Apple               | 3        | 3      | 0.05%   |
| USB3.0              | 2        | 2      | 0.04%   |
| USB                 | 2        | 2      | 0.04%   |
| SAGE                | 2        | 2      | 0.04%   |
| SABRENT             | 2        | 2      | 0.04%   |
| RSH-319             | 2        | 2      | 0.04%   |
| PHD 3.0             | 2        | 3      | 0.04%   |
| Maxtor 6            | 2        | 3      | 0.04%   |
| Maxone              | 2        | 2      | 0.04%   |
| HPE                 | 2        | 3      | 0.04%   |
| Unknown             | 2        | 4      | 0.04%   |
| USB 3.0             | 1        | 4      | 0.02%   |
| TrueNAS             | 1        | 3      | 0.02%   |
| TANDBERG            | 1        | 1      | 0.02%   |
| Synology            | 1        | 1      | 0.02%   |
| Storeva             | 1        | 1      | 0.02%   |
| Quantum             | 1        | 1      | 0.02%   |
| MaxDigital          | 1        | 1      | 0.02%   |
| MARVELL             | 1        | 1      | 0.02%   |
| Magnetic Data       | 1        | 1      | 0.02%   |
| LaCie               | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 724      | 1101   | 21.83%  |
| Kingston            | 542      | 732    | 16.34%  |
| Crucial             | 379      | 535    | 11.43%  |
| SanDisk             | 317      | 446    | 9.56%   |
| WDC                 | 224      | 305    | 6.76%   |
| A-DATA Technology   | 115      | 156    | 3.47%   |
| China               | 99       | 120    | 2.99%   |
| Intel               | 69       | 90     | 2.08%   |
| OCZ                 | 60       | 75     | 1.81%   |
| SPCC                | 57       | 76     | 1.72%   |
| Intenso             | 56       | 79     | 1.69%   |
| Patriot             | 54       | 65     | 1.63%   |
| PNY                 | 47       | 62     | 1.42%   |
| Transcend           | 37       | 52     | 1.12%   |
| Corsair             | 35       | 41     | 1.06%   |
| GOODRAM             | 34       | 42     | 1.03%   |
| Toshiba             | 33       | 42     | 1%      |
| Micron Technology   | 28       | 35     | 0.84%   |
| Apacer              | 23       | 27     | 0.69%   |
| Team                | 20       | 26     | 0.6%    |
| Plextor             | 20       | 25     | 0.6%    |
| SK hynix            | 19       | 23     | 0.57%   |
| Lexar               | 17       | 20     | 0.51%   |
| KingSpec            | 17       | 30     | 0.51%   |
| Seagate             | 14       | 24     | 0.42%   |
| LITEON              | 14       | 15     | 0.42%   |
| Unknown             | 14       | 22     | 0.42%   |
| TO Exter            | 12       | 18     | 0.36%   |
| LITEONIT            | 10       | 10     | 0.3%    |
| AMD                 | 10       | 10     | 0.3%    |
| JMicron Technology  | 9        | 11     | 0.27%   |
| Hewlett-Packard     | 9        | 11     | 0.27%   |
| KingDian            | 8        | 9      | 0.24%   |
| Gigabyte Technology | 8        | 17     | 0.24%   |
| Unknown             | 7        | 7      | 0.21%   |
| Smartbuy            | 7        | 11     | 0.21%   |
| Mushkin             | 7        | 10     | 0.21%   |
| Leven               | 7        | 7      | 0.21%   |
| Verbatim            | 6        | 7      | 0.18%   |
| Netac               | 6        | 11     | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 4219     | 8699   | 52.13%  |
| SSD     | 2791     | 4578   | 34.49%  |
| NVMe    | 896      | 1341   | 11.07%  |
| Unknown | 163      | 243    | 2.01%   |
| MMC     | 24       | 37     | 0.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 5221     | 12846  | 79.49%  |
| NVMe | 886      | 1321   | 13.49%  |
| SAS  | 437      | 694    | 6.65%   |
| MMC  | 24       | 37     | 0.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 4049     | 7470   | 53%     |
| 0.51-1.0   | 2123     | 3355   | 27.79%  |
| 1.01-2.0   | 811      | 1364   | 10.62%  |
| 3.01-4.0   | 290      | 494    | 3.8%    |
| 2.01-3.0   | 197      | 312    | 2.58%   |
| 4.01-10.0  | 145      | 236    | 1.9%    |
| 10.01-20.0 | 22       | 44     | 0.29%   |
| 0          | 2        | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1477     | 25.14%  |
| 251-500        | 1136     | 19.33%  |
| 501-1000       | 972      | 16.54%  |
| 1001-2000      | 724      | 12.32%  |
| More than 3000 | 569      | 9.68%   |
| 2001-3000      | 354      | 6.02%   |
| 51-100         | 343      | 5.84%   |
| 21-50          | 150      | 2.55%   |
| 1-20           | 113      | 1.92%   |
| Unknown        | 38       | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1367     | 22.3%   |
| 21-50          | 1145     | 18.68%  |
| 101-250        | 901      | 14.7%   |
| 51-100         | 791      | 12.9%   |
| 501-1000       | 565      | 9.22%   |
| 251-500        | 557      | 9.08%   |
| 1001-2000      | 389      | 6.34%   |
| More than 3000 | 218      | 3.56%   |
| 2001-3000      | 160      | 2.61%   |
| Unknown        | 38       | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 24       | 24     | 3.56%   |
| Seagate ST3500418AS 500GB             | 15       | 17     | 2.22%   |
| Seagate ST31000528AS 1TB              | 8        | 10     | 1.19%   |
| WDC WD10EARS-00Y5B1 1TB               | 6        | 6      | 0.89%   |
| Seagate ST3500320AS 500GB             | 6        | 8      | 0.89%   |
| Seagate ST31000524AS 1TB              | 6        | 7      | 0.89%   |
| Seagate ST1000DM003-9YN162 1TB        | 6        | 6      | 0.89%   |
| WDC WD10EZEX-00BN5A0 1TB              | 5        | 6      | 0.74%   |
| Seagate ST3250318AS 250GB             | 5        | 6      | 0.74%   |
| Seagate ST2000DM001-9YN164 2TB        | 5        | 5      | 0.74%   |
| Seagate ST2000DM001-1CH164 2TB        | 5        | 5      | 0.74%   |
| Seagate ST1500DL003-9VT16L 1TB        | 5        | 5      | 0.74%   |
| Seagate ST1000DM003-1CH162 1TB        | 5        | 6      | 0.74%   |
| Samsung Electronics HD502HI 500GB     | 5        | 5      | 0.74%   |
| Samsung Electronics HD322HJ 320GB     | 5        | 9      | 0.74%   |
| Crucial CT525MX300SSD1 528GB          | 5        | 5      | 0.74%   |
| WDC WD5000AAKX-001CA0 500GB           | 4        | 5      | 0.59%   |
| WDC WD5000AAKS-00A7B0 500GB           | 4        | 4      | 0.59%   |
| WDC WD3200AAJS-00L7A0 320GB           | 4        | 4      | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 4        | 4      | 0.59%   |
| Seagate ST31500341AS 1TB              | 4        | 5      | 0.59%   |
| Seagate ST1000DM003-1ER162 1TB        | 4        | 5      | 0.59%   |
| Samsung Electronics SSD 970 EVO 500GB | 4        | 5      | 0.59%   |
| Samsung Electronics HD501LJ 500GB     | 4        | 7      | 0.59%   |
| Samsung Electronics HD161HJ 160GB     | 4        | 4      | 0.59%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 4      | 0.59%   |
| Maxtor STM3250310AS 250GB             | 4        | 5      | 0.59%   |
| Hitachi HDS721010CLA332 1TB           | 4        | 4      | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3        | 3      | 0.44%   |
| WDC WD5000AAKX-003CA0 500GB           | 3        | 3      | 0.44%   |
| WDC WD40EFRX-68WT0N0 4TB              | 3        | 6      | 0.44%   |
| WDC WD3200AAJS-56M0A0 320GB           | 3        | 3      | 0.44%   |
| WDC WD20EZRX-00DC0B0 2TB              | 3        | 7      | 0.44%   |
| WDC WD10EADS-00L5B1 1TB               | 3        | 3      | 0.44%   |
| Seagate ST9500325AS 500GB             | 3        | 3      | 0.44%   |
| Seagate ST9320325AS 320GB             | 3        | 3      | 0.44%   |
| Seagate ST9250315AS 250GB             | 3        | 3      | 0.44%   |
| Seagate ST500LT012-1DG142 500GB       | 3        | 3      | 0.44%   |
| Seagate ST3500413AS 500GB             | 3        | 5      | 0.44%   |
| Seagate ST3250820AS 250GB             | 3        | 3      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 208      | 251    | 32.55%  |
| WDC                 | 175      | 220    | 27.39%  |
| Samsung Electronics | 71       | 88     | 11.11%  |
| Hitachi             | 47       | 55     | 7.36%   |
| Maxtor              | 19       | 25     | 2.97%   |
| Toshiba             | 18       | 18     | 2.82%   |
| Crucial             | 15       | 16     | 2.35%   |
| SanDisk             | 14       | 15     | 2.19%   |
| Kingston            | 13       | 14     | 2.03%   |
| Intel               | 7        | 7      | 1.1%    |
| Corsair             | 6        | 9      | 0.94%   |
| OCZ                 | 5        | 5      | 0.78%   |
| HGST                | 5        | 5      | 0.78%   |
| China               | 4        | 5      | 0.63%   |
| SPCC                | 3        | 4      | 0.47%   |
| A-DATA Technology   | 3        | 3      | 0.47%   |
| SK hynix            | 2        | 2      | 0.31%   |
| Plextor             | 2        | 2      | 0.31%   |
| Micron Technology   | 2        | 3      | 0.31%   |
| LITEONIT            | 2        | 2      | 0.31%   |
| Leven               | 2        | 2      | 0.31%   |
| LDLC                | 2        | 2      | 0.31%   |
| Kingmax             | 2        | 2      | 0.31%   |
| Intenso             | 2        | 2      | 0.31%   |
| Unknown             | 1        | 1      | 0.16%   |
| Transcend           | 1        | 1      | 0.16%   |
| Mushkin             | 1        | 1      | 0.16%   |
| HS-SSD-E100         | 1        | 1      | 0.16%   |
| Hewlett-Packard     | 1        | 1      | 0.16%   |
| Fujitsu             | 1        | 2      | 0.16%   |
| FEASSO              | 1        | 2      | 0.16%   |
| ExcelStor           | 1        | 1      | 0.16%   |
| ASMedia             | 1        | 1      | 0.16%   |
| Unknown             | 1        | 2      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 208      | 251    | 38.88%  |
| WDC                 | 171      | 215    | 31.96%  |
| Samsung Electronics | 60       | 75     | 11.21%  |
| Hitachi             | 47       | 55     | 8.79%   |
| Maxtor              | 19       | 25     | 3.55%   |
| Toshiba             | 18       | 18     | 3.36%   |
| HGST                | 5        | 5      | 0.93%   |
| Unknown             | 1        | 1      | 0.19%   |
| Hewlett-Packard     | 1        | 1      | 0.19%   |
| Fujitsu             | 1        | 2      | 0.19%   |
| FEASSO              | 1        | 2      | 0.19%   |
| ExcelStor           | 1        | 1      | 0.19%   |
| ASMedia             | 1        | 1      | 0.19%   |
| Unknown             | 1        | 2      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 479      | 654    | 82.16%  |
| SSD  | 94       | 104    | 16.12%  |
| NVMe | 10       | 12     | 1.72%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD252HJ 250GB | 2        | 2      | 28.57%  |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB   | 1        | 1      | 14.29%  |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 14.29%  |
| Hitachi HDS721050DLE630 500GB     | 1        | 1      | 14.29%  |
| Hitachi HDS721050CLA362 500GB     | 1        | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 4      | 57.14%  |
| Hitachi             | 2        | 2      | 28.57%  |
| Toshiba             | 1        | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3803     | 10373  | 62.29%  |
| Works    | 1727     | 3748   | 28.29%  |
| Malfunc  | 568      | 770    | 9.3%    |
| Failed   | 7        | 7      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3500     | 48.71%  |
| AMD                              | 1700     | 23.66%  |
| Samsung Electronics              | 359      | 5%      |
| Nvidia                           | 259      | 3.6%    |
| ASMedia Technology               | 226      | 3.15%   |
| JMicron Technology               | 202      | 2.81%   |
| Marvell Technology Group         | 198      | 2.76%   |
| SanDisk                          | 118      | 1.64%   |
| Phison Electronics               | 115      | 1.6%    |
| Kingston Technology Company      | 79       | 1.1%    |
| VIA Technologies                 | 75       | 1.04%   |
| Silicon Motion                   | 63       | 0.88%   |
| Micron/Crucial Technology        | 53       | 0.74%   |
| ADATA Technology                 | 48       | 0.67%   |
| Realtek Semiconductor            | 26       | 0.36%   |
| LSI Logic / Symbios Logic        | 20       | 0.28%   |
| SK hynix                         | 18       | 0.25%   |
| Silicon Image                    | 18       | 0.25%   |
| Adaptec                          | 13       | 0.18%   |
| Broadcom / LSI                   | 12       | 0.17%   |
| Micron Technology                | 11       | 0.15%   |
| Toshiba America Info Systems     | 10       | 0.14%   |
| Silicon Integrated Systems [SiS] | 9        | 0.13%   |
| Lite-On Technology               | 9        | 0.13%   |
| Seagate Technology               | 7        | 0.1%    |
| Integrated Technology Express    | 7        | 0.1%    |
| KIOXIA                           | 4        | 0.06%   |
| ULi Electronics                  | 3        | 0.04%   |
| Shenzhen Longsys Electronics     | 3        | 0.04%   |
| HighPoint Technologies           | 3        | 0.04%   |
| OCZ Technology Group             | 2        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 2        | 0.03%   |
| INNOGRIT                         | 2        | 0.03%   |
| Hewlett-Packard                  | 2        | 0.03%   |
| Union Memory (Shenzhen)          | 1        | 0.01%   |
| Transcend                        | 1        | 0.01%   |
| Solid State Storage Technology   | 1        | 0.01%   |
| Promise Technology               | 1        | 0.01%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.01%   |
| Beijing Starblaze Technology     | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 814      | 8.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 402      | 4.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 390      | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 357      | 3.72%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 343      | 3.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 311      | 3.24%   |
| AMD 400 Series Chipset SATA Controller                                                  | 297      | 3.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 264      | 2.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 260      | 2.71%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 258      | 2.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 236      | 2.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 227      | 2.37%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 207      | 2.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 206      | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 191      | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 191      | 1.99%   |
| Intel SATA Controller [RAID mode]                                                       | 186      | 1.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 169      | 1.76%   |
| Nvidia MCP61 SATA Controller                                                            | 157      | 1.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 128      | 1.34%   |
| Nvidia MCP61 IDE                                                                        | 126      | 1.31%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 103      | 1.07%   |
| AMD FCH SATA Controller D                                                               | 102      | 1.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 94       | 0.98%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 91       | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                                  | 91       | 0.95%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 80       | 0.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 76       | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 75       | 0.78%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 72       | 0.75%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 70       | 0.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 66       | 0.69%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 66       | 0.69%   |
| JMicron JMB368 IDE controller                                                           | 61       | 0.64%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 59       | 0.62%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 59       | 0.62%   |
| AMD FCH IDE Controller                                                                  | 59       | 0.62%   |
| Phison E12 NVMe Controller                                                              | 56       | 0.58%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 53       | 0.55%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 50       | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 4077     | 55.8%   |
| IDE  | 1973     | 27%     |
| NVMe | 896      | 12.26%  |
| RAID | 305      | 4.17%   |
| SAS  | 28       | 0.38%   |
| SCSI | 28       | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 3584     | 64.95%  |
| AMD          | 1932     | 35.01%  |
| CentaurHauls | 2        | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 87       | 1.57%   |
| AMD Ryzen 5 3600 6-Core Processor           | 84       | 1.52%   |
| AMD FX-8350 Eight-Core Processor            | 79       | 1.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 75       | 1.35%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 65       | 1.17%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 64       | 1.15%   |
| AMD FX-6300 Six-Core Processor              | 64       | 1.15%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 62       | 1.12%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 61       | 1.1%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 59       | 1.06%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 51       | 0.92%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 51       | 0.92%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 50       | 0.9%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 49       | 0.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 46       | 0.83%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 46       | 0.83%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 45       | 0.81%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 44       | 0.79%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 43       | 0.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 39       | 0.7%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 38       | 0.69%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 38       | 0.69%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 36       | 0.65%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 35       | 0.63%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 34       | 0.61%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 33       | 0.6%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 32       | 0.58%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 31       | 0.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 31       | 0.56%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 31       | 0.56%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 31       | 0.56%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 30       | 0.54%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 30       | 0.54%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 29       | 0.52%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 28       | 0.51%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 26       | 0.47%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 26       | 0.47%   |
| AMD FX-8320 Eight-Core Processor            | 26       | 0.47%   |
| AMD FX-4300 Quad-Core Processor             | 26       | 0.47%   |
| AMD Athlon II X2 250 Processor              | 26       | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 993      | 17.94%  |
| Intel Core i7           | 641      | 11.58%  |
| Intel Core i3           | 411      | 7.43%   |
| AMD Ryzen 5             | 382      | 6.9%    |
| AMD FX                  | 321      | 5.8%    |
| Intel Core 2 Duo        | 259      | 4.68%   |
| Intel Xeon              | 238      | 4.3%    |
| AMD Ryzen 7             | 217      | 3.92%   |
| Intel Core 2 Quad       | 178      | 3.22%   |
| Intel Celeron           | 171      | 3.09%   |
| Intel Pentium           | 168      | 3.04%   |
| Intel Pentium Dual-Core | 138      | 2.49%   |
| AMD Ryzen 3             | 104      | 1.88%   |
| AMD Phenom II X4        | 92       | 1.66%   |
| AMD Athlon 64 X2        | 87       | 1.57%   |
| Other                   | 84       | 1.52%   |
| AMD Athlon II X2        | 82       | 1.48%   |
| AMD Ryzen 9             | 71       | 1.28%   |
| AMD A8                  | 69       | 1.25%   |
| Intel Pentium Dual      | 58       | 1.05%   |
| AMD Athlon II X4        | 57       | 1.03%   |
| Intel Core 2            | 53       | 0.96%   |
| Intel Pentium 4         | 52       | 0.94%   |
| Intel Atom              | 48       | 0.87%   |
| AMD A4                  | 48       | 0.87%   |
| AMD A10                 | 48       | 0.87%   |
| Intel Core i9           | 41       | 0.74%   |
| AMD A6                  | 41       | 0.74%   |
| Intel Pentium D         | 36       | 0.65%   |
| AMD Phenom II X6        | 34       | 0.61%   |
| AMD Athlon              | 34       | 0.61%   |
| AMD Sempron             | 27       | 0.49%   |
| AMD Phenom              | 25       | 0.45%   |
| AMD Athlon II X3        | 23       | 0.42%   |
| Intel Pentium Gold      | 20       | 0.36%   |
| AMD Athlon X4           | 19       | 0.34%   |
| AMD Ryzen 5 PRO         | 16       | 0.29%   |
| AMD Phenom II X2        | 16       | 0.29%   |
| AMD Ryzen Threadripper  | 13       | 0.23%   |
| AMD Athlon 64           | 11       | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2254     | 40.66%  |
| 2       | 1763     | 31.81%  |
| 6       | 657      | 11.85%  |
| 8       | 353      | 6.37%   |
| 1       | 208      | 3.75%   |
| 3       | 131      | 2.36%   |
| 12      | 90       | 1.62%   |
| 16      | 34       | 0.61%   |
| 10      | 30       | 0.54%   |
| Unknown | 9        | 0.16%   |
| 24      | 5        | 0.09%   |
| 18      | 3        | 0.05%   |
| 20      | 2        | 0.04%   |
| 64      | 1        | 0.02%   |
| 32      | 1        | 0.02%   |
| 14      | 1        | 0.02%   |
| 5       | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 5464     | 99.02%  |
| 2      | 54       | 0.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2859     | 51.63%  |
| 2       | 2668     | 48.18%  |
| Unknown | 9        | 0.16%   |
| 8       | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 5142     | 92.1%   |
| Unknown        | 407      | 7.29%   |
| 32-bit         | 34       | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 595      | 10.5%   |
| 0x306c3    | 503      | 8.88%   |
| 0x206a7    | 432      | 7.62%   |
| 0x306a9    | 388      | 6.85%   |
| 0x1067a    | 372      | 6.56%   |
| 0x06000852 | 228      | 4.02%   |
| 0x506e3    | 193      | 3.41%   |
| 0x010000c8 | 174      | 3.07%   |
| 0x08701021 | 163      | 2.88%   |
| 0x906e9    | 145      | 2.56%   |
| 0x906ea    | 141      | 2.49%   |
| 0x0800820d | 121      | 2.14%   |
| 0x6fd      | 94       | 1.66%   |
| 0x6fb      | 92       | 1.62%   |
| 0x06001119 | 90       | 1.59%   |
| 0x10676    | 68       | 1.2%    |
| 0x08701013 | 66       | 1.16%   |
| 0x08108109 | 66       | 1.16%   |
| 0x106e5    | 61       | 1.08%   |
| 0x0600063e | 60       | 1.06%   |
| 0x010000db | 59       | 1.04%   |
| 0xa0655    | 58       | 1.02%   |
| 0x20655    | 53       | 0.94%   |
| 0x08001138 | 44       | 0.78%   |
| 0x06003106 | 44       | 0.78%   |
| 0x906ed    | 42       | 0.74%   |
| 0x20652    | 41       | 0.72%   |
| 0x306f2    | 40       | 0.71%   |
| 0xa0653    | 39       | 0.69%   |
| 0xa0671    | 38       | 0.67%   |
| 0x08001137 | 38       | 0.67%   |
| 0x0600611a | 34       | 0.6%    |
| 0x206c2    | 33       | 0.58%   |
| 0x0a50000c | 33       | 0.58%   |
| 0x6f6      | 32       | 0.56%   |
| 0x106a5    | 31       | 0.55%   |
| 0x0a201016 | 31       | 0.55%   |
| 0x08101016 | 31       | 0.55%   |
| 0x010000dc | 31       | 0.55%   |
| 0x03000027 | 30       | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 587      | 10.62%  |
| Penryn           | 489      | 8.85%   |
| SandyBridge      | 486      | 8.79%   |
| IvyBridge        | 448      | 8.1%    |
| KabyLake         | 409      | 7.4%    |
| K10              | 372      | 6.73%   |
| Piledriver       | 354      | 6.4%    |
| Zen 2            | 274      | 4.96%   |
| Core             | 273      | 4.94%   |
| Zen+             | 222      | 4.02%   |
| Skylake          | 222      | 4.02%   |
| Zen              | 188      | 3.4%    |
| Zen 3            | 142      | 2.57%   |
| Westmere         | 136      | 2.46%   |
| K8 Hammer        | 125      | 2.26%   |
| Nehalem          | 105      | 1.9%    |
| CometLake        | 105      | 1.9%    |
| NetBurst         | 104      | 1.88%   |
| Bulldozer        | 68       | 1.23%   |
| Steamroller      | 56       | 1.01%   |
| Silvermont       | 51       | 0.92%   |
| Unknown          | 48       | 0.87%   |
| Excavator        | 46       | 0.83%   |
| Bonnell          | 34       | 0.62%   |
| K10 Llano        | 33       | 0.6%    |
| Goldmont plus    | 32       | 0.58%   |
| Bobcat           | 25       | 0.45%   |
| Alderlake Hybrid | 20       | 0.36%   |
| Jaguar           | 18       | 0.33%   |
| Goldmont         | 17       | 0.31%   |
| Icelake          | 12       | 0.22%   |
| Broadwell        | 10       | 0.18%   |
| Puma             | 7        | 0.13%   |
| Tremont          | 4        | 0.07%   |
| K6               | 4        | 0.07%   |
| TigerLake        | 2        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 2273     | 38.94%  |
| Intel                                        | 1788     | 30.63%  |
| AMD                                          | 1727     | 29.59%  |
| VIA Technologies                             | 17       | 0.29%   |
| Matrox Electronics Systems                   | 14       | 0.24%   |
| Silicon Integrated Systems [SiS]             | 7        | 0.12%   |
| ATI Technologies                             | 5        | 0.09%   |
| S3 Graphics                                  | 3        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.03%   |
| ASPEED Technology                            | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 261      | 4.34%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 253      | 4.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 195      | 3.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 182      | 3.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 152      | 2.53%   |
| Nvidia GK208B [GeForce GT 710]                                              | 148      | 2.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 139      | 2.31%   |
| Intel HD Graphics 530                                                       | 113      | 1.88%   |
| Nvidia GT218 [GeForce 210]                                                  | 102      | 1.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 92       | 1.53%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 92       | 1.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 88       | 1.46%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 85       | 1.42%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 81       | 1.35%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 73       | 1.22%   |
| AMD RS780L [Radeon 3000]                                                    | 65       | 1.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 65       | 1.08%   |
| Intel HD Graphics 630                                                       | 63       | 1.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 61       | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                         | 60       | 1%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 53       | 0.88%   |
| Nvidia GK208B [GeForce GT 730]                                              | 53       | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 52       | 0.87%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 51       | 0.85%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 50       | 0.83%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 50       | 0.83%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 47       | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 47       | 0.78%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 47       | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 44       | 0.73%   |
| Nvidia GF119 [GeForce GT 610]                                               | 42       | 0.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 41       | 0.68%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 40       | 0.67%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 38       | 0.63%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 38       | 0.63%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 35       | 0.58%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 35       | 0.58%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 34       | 0.57%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 33       | 0.55%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 33       | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 2153     | 38.58%  |
| 1 x AMD             | 1597     | 28.61%  |
| 1 x Intel           | 1576     | 28.24%  |
| 2 x AMD             | 71       | 1.27%   |
| Intel + Nvidia      | 52       | 0.93%   |
| AMD + Nvidia        | 32       | 0.57%   |
| Intel + AMD         | 27       | 0.48%   |
| 2 x Nvidia          | 26       | 0.47%   |
| 1 x VIA             | 17       | 0.3%    |
| 1 x Matrox          | 14       | 0.25%   |
| 1 x SiS             | 7        | 0.13%   |
| 3 x AMD             | 2        | 0.04%   |
| 1 x S3 Graphics     | 2        | 0.04%   |
| Nvidia + XGI        | 2        | 0.04%   |
| Nvidia + ASPEED     | 1        | 0.02%   |
| Intel + 2 x Nvidia  | 1        | 0.02%   |
| Intel + S3 Graphics | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3706     | 65.84%  |
| Proprietary | 1657     | 29.44%  |
| Unknown     | 266      | 4.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1758     | 30.91%  |
| 1.01-2.0   | 1059     | 18.62%  |
| 0.51-1.0   | 840      | 14.77%  |
| 0.01-0.5   | 811      | 14.26%  |
| 3.01-4.0   | 508      | 8.93%   |
| 7.01-8.0   | 362      | 6.37%   |
| 5.01-6.0   | 199      | 3.5%    |
| 2.01-3.0   | 74       | 1.3%    |
| 8.01-16.0  | 66       | 1.16%   |
| 16.01-24.0 | 8        | 0.14%   |
| 4.01-5.0   | 2        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 967      | 16.95%  |
| Goldstar             | 601      | 10.54%  |
| Dell                 | 520      | 9.12%   |
| Acer                 | 435      | 7.63%   |
| Hewlett-Packard      | 376      | 6.59%   |
| AOC                  | 299      | 5.24%   |
| Ancor Communications | 274      | 4.8%    |
| BenQ                 | 254      | 4.45%   |
| Philips              | 249      | 4.37%   |
| LG Electronics       | 160      | 2.81%   |
| Unknown              | 137      | 2.4%    |
| ViewSonic            | 112      | 1.96%   |
| Iiyama               | 100      | 1.75%   |
| Sony                 | 73       | 1.28%   |
| ASUSTek Computer     | 67       | 1.17%   |
| Eizo                 | 60       | 1.05%   |
| NEC Computers        | 57       | 1%      |
| Lenovo               | 51       | 0.89%   |
| Fujitsu Siemens      | 47       | 0.82%   |
| HannStar             | 40       | 0.7%    |
| Vizio                | 36       | 0.63%   |
| Medion               | 33       | 0.58%   |
| Toshiba              | 28       | 0.49%   |
| Unknown              | 28       | 0.49%   |
| Sceptre Tech         | 26       | 0.46%   |
| Panasonic            | 26       | 0.46%   |
| Idek Iiyama          | 20       | 0.35%   |
| Sharp                | 17       | 0.3%    |
| Vestel Elektronik    | 16       | 0.28%   |
| MSI                  | 16       | 0.28%   |
| FUS                  | 16       | 0.28%   |
| AUS                  | 16       | 0.28%   |
| Hitachi              | 15       | 0.26%   |
| Gateway              | 14       | 0.25%   |
| Plain Tree Systems   | 12       | 0.21%   |
| Packard Bell         | 12       | 0.21%   |
| Insignia             | 12       | 0.21%   |
| ___                  | 11       | 0.19%   |
| VIZ                  | 11       | 0.19%   |
| Unknown (XXX)        | 11       | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 31       | 0.51%   |
| Unknown                                                               | 28       | 0.46%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 22       | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 18       | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 18       | 0.29%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 17       | 0.28%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 16       | 0.26%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 16       | 0.26%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 14       | 0.23%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 14       | 0.23%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 14       | 0.23%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 12       | 0.2%    |
| Unknown LCD Monitor SAMSUNG                                           | 11       | 0.18%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 11       | 0.18%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 11       | 0.18%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 10       | 0.16%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 10       | 0.16%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 10       | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 10       | 0.16%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 10       | 0.16%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 10       | 0.16%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 10       | 0.16%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 10       | 0.16%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                          | 10       | 0.16%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 10       | 0.16%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 9        | 0.15%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 9        | 0.15%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 9        | 0.15%   |
| Philips LCD Monitor FTV 1920x1080                                     | 9        | 0.15%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 9        | 0.15%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                        | 9        | 0.15%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 8        | 0.13%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 8        | 0.13%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 8        | 0.13%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 8        | 0.13%   |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch                     | 8        | 0.13%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 8        | 0.13%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch   | 7        | 0.11%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 7        | 0.11%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 7        | 0.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2404     | 42.38%  |
| 1280x1024 (SXGA)   | 489      | 8.62%   |
| 1680x1050 (WSXGA+) | 367      | 6.47%   |
| 3840x2160 (4K)     | 353      | 6.22%   |
| 1366x768 (WXGA)    | 296      | 5.22%   |
| 1440x900 (WXGA+)   | 253      | 4.46%   |
| 2560x1440 (QHD)    | 235      | 4.14%   |
| Unknown            | 221      | 3.9%    |
| 1600x900 (HD+)     | 191      | 3.37%   |
| 1920x1200 (WUXGA)  | 172      | 3.03%   |
| 1360x768           | 140      | 2.47%   |
| 2560x1080          | 74       | 1.3%    |
| 3840x1080          | 72       | 1.27%   |
| 1024x768 (XGA)     | 55       | 0.97%   |
| 3440x1440          | 40       | 0.71%   |
| 1600x1200          | 40       | 0.71%   |
| 1920x540           | 30       | 0.53%   |
| 1280x720 (HD)      | 21       | 0.37%   |
| 3200x1080          | 18       | 0.32%   |
| 3600x1080          | 14       | 0.25%   |
| 3840x1200          | 11       | 0.19%   |
| 2560x1600          | 10       | 0.18%   |
| 5760x1080          | 9        | 0.16%   |
| 4480x1440          | 9        | 0.16%   |
| 1280x960           | 8        | 0.14%   |
| 5120x1440          | 7        | 0.12%   |
| 3520x1080          | 7        | 0.12%   |
| 1152x864           | 7        | 0.12%   |
| 3360x1050          | 6        | 0.11%   |
| 3286x1080          | 6        | 0.11%   |
| 5120x1080          | 5        | 0.09%   |
| 3280x1080          | 5        | 0.09%   |
| 2288x1287          | 5        | 0.09%   |
| 1280x768           | 5        | 0.09%   |
| 3840x1600          | 4        | 0.07%   |
| 2960x1050          | 4        | 0.07%   |
| 2560x1024          | 4        | 0.07%   |
| 2048x1152          | 4        | 0.07%   |
| 2944x1080          | 3        | 0.05%   |
| 1280x800 (WXGA)    | 3        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1024     | 18.19%  |
| 24      | 614      | 10.9%   |
| 23      | 597      | 10.6%   |
| 21      | 560      | 9.94%   |
| 27      | 533      | 9.47%   |
| 19      | 405      | 7.19%   |
| 18      | 299      | 5.31%   |
| 22      | 245      | 4.35%   |
| 17      | 231      | 4.1%    |
| 20      | 225      | 4%      |
| 31      | 161      | 2.86%   |
| 15      | 102      | 1.81%   |
| 34      | 89       | 1.58%   |
| 84      | 65       | 1.15%   |
| 32      | 52       | 0.92%   |
| 72      | 50       | 0.89%   |
| 54      | 45       | 0.8%    |
| 40      | 40       | 0.71%   |
| 25      | 36       | 0.64%   |
| 26      | 21       | 0.37%   |
| 16      | 20       | 0.36%   |
| 46      | 17       | 0.3%    |
| 37      | 12       | 0.21%   |
| 28      | 12       | 0.21%   |
| 65      | 11       | 0.2%    |
| 52      | 11       | 0.2%    |
| 39      | 11       | 0.2%    |
| 33      | 11       | 0.2%    |
| 48      | 10       | 0.18%   |
| 36      | 9        | 0.16%   |
| 12      | 9        | 0.16%   |
| 47      | 8        | 0.14%   |
| 29      | 8        | 0.14%   |
| 13      | 8        | 0.14%   |
| 74      | 7        | 0.12%   |
| 60      | 6        | 0.11%   |
| 55      | 6        | 0.11%   |
| 42      | 6        | 0.11%   |
| 49      | 5        | 0.09%   |
| 30      | 5        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1653     | 30.04%  |
| 401-500        | 1458     | 26.49%  |
| Unknown        | 1024     | 18.61%  |
| 301-350        | 314      | 5.71%   |
| 351-400        | 274      | 4.98%   |
| 601-700        | 248      | 4.51%   |
| 701-800        | 161      | 2.93%   |
| 1001-1500      | 132      | 2.4%    |
| 1501-2000      | 129      | 2.34%   |
| 801-900        | 70       | 1.27%   |
| 201-300        | 22       | 0.4%    |
| 901-1000       | 15       | 0.27%   |
| More than 2000 | 3        | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2976     | 55.77%  |
| Unknown | 944      | 17.69%  |
| 16/10   | 709      | 13.29%  |
| 5/4     | 420      | 7.87%   |
| 4/3     | 124      | 2.32%   |
| 21/9    | 97       | 1.82%   |
| 3/2     | 27       | 0.51%   |
| 6/5     | 18       | 0.34%   |
| 32/9    | 10       | 0.19%   |
| 1.96    | 4        | 0.07%   |
| 1.00    | 4        | 0.07%   |
| 3.20    | 1        | 0.02%   |
| 2.00    | 1        | 0.02%   |
| 11/10   | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1635     | 29.53%  |
| Unknown        | 1024     | 18.49%  |
| 151-200        | 806      | 14.56%  |
| 301-350        | 543      | 9.81%   |
| 141-150        | 439      | 7.93%   |
| 351-500        | 333      | 6.01%   |
| 251-300        | 238      | 4.3%    |
| More than 1000 | 225      | 4.06%   |
| 501-1000       | 125      | 2.26%   |
| 101-110        | 88       | 1.59%   |
| 131-140        | 32       | 0.58%   |
| 111-120        | 22       | 0.4%    |
| 71-80          | 10       | 0.18%   |
| 121-130        | 7        | 0.13%   |
| 81-90          | 5        | 0.09%   |
| 91-100         | 5        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 3128     | 58.49%  |
| Unknown | 1024     | 19.15%  |
| 101-120 | 767      | 14.34%  |
| 1-50    | 241      | 4.51%   |
| 121-160 | 126      | 2.36%   |
| 161-240 | 62       | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 4535     | 80.72%  |
| 2     | 745      | 13.26%  |
| 0     | 262      | 4.66%   |
| 3     | 69       | 1.23%   |
| 4     | 7        | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 3489     | 44.56%  |
| Intel                                  | 1830     | 23.37%  |
| Qualcomm Atheros                       | 543      | 6.93%   |
| Ralink Technology                      | 273      | 3.49%   |
| Broadcom                               | 236      | 3.01%   |
| Nvidia                                 | 210      | 2.68%   |
| TP-Link                                | 161      | 2.06%   |
| Ralink                                 | 137      | 1.75%   |
| Marvell Technology Group               | 72       | 0.92%   |
| Qualcomm Atheros Communications        | 66       | 0.84%   |
| Broadcom Limited                       | 64       | 0.82%   |
| NetGear                                | 54       | 0.69%   |
| D-Link System                          | 51       | 0.65%   |
| Samsung Electronics                    | 50       | 0.64%   |
| MediaTek                               | 45       | 0.57%   |
| D-Link                                 | 42       | 0.54%   |
| VIA Technologies                       | 41       | 0.52%   |
| ASUSTek Computer                       | 37       | 0.47%   |
| Xiaomi                                 | 31       | 0.4%    |
| Microsoft                              | 24       | 0.31%   |
| Huawei Technologies                    | 24       | 0.31%   |
| ASIX Electronics                       | 24       | 0.31%   |
| IMC Networks                           | 22       | 0.28%   |
| Belkin Components                      | 22       | 0.28%   |
| Linksys                                | 20       | 0.26%   |
| Aquantia                               | 20       | 0.26%   |
| Edimax Technology                      | 19       | 0.24%   |
| Motorola PCS                           | 13       | 0.17%   |
| AVM                                    | 12       | 0.15%   |
| Sundance Technology Inc / IC Plus      | 10       | 0.13%   |
| Sitecom Europe                         | 9        | 0.11%   |
| Qualcomm                               | 8        | 0.1%    |
| DisplayLink                            | 7        | 0.09%   |
| ZyDAS                                  | 5        | 0.06%   |
| U-Blox                                 | 5        | 0.06%   |
| Sony Ericsson Mobile Communications AB | 5        | 0.06%   |
| Silicon Integrated Systems [SiS]       | 5        | 0.06%   |
| Motorola                               | 5        | 0.06%   |
| Microchip Technology                   | 5        | 0.06%   |
| Gemtek                                 | 5        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2778     | 32.06%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 269      | 3.1%    |
| Intel Ethernet Connection (2) I219-V                              | 183      | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 179      | 2.07%   |
| Intel I211 Gigabit Network Connection                             | 175      | 2.02%   |
| Intel Wi-Fi 6 AX200                                               | 165      | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 147      | 1.7%    |
| Nvidia MCP61 Ethernet                                             | 131      | 1.51%   |
| Ralink MT7601U Wireless Adapter                                   | 118      | 1.36%   |
| Intel Ethernet Connection I217-LM                                 | 105      | 1.21%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 98       | 1.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 95       | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 85       | 0.98%   |
| Intel 82579V Gigabit Network Connection                           | 83       | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 75       | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 73       | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 70       | 0.81%   |
| Realtek 802.11ac NIC                                              | 69       | 0.8%    |
| Intel Ethernet Connection I217-V                                  | 68       | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 65       | 0.75%   |
| Intel Ethernet Connection (2) I218-V                              | 60       | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                   | 53       | 0.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 51       | 0.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 48       | 0.55%   |
| Ralink RT5370 Wireless Adapter                                    | 47       | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 47       | 0.54%   |
| Intel Wireless-AC 9260                                            | 46       | 0.53%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 44       | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 44       | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 41       | 0.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 39       | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 38       | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 38       | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 37       | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 37       | 0.43%   |
| Intel 82574L Gigabit Network Connection                           | 37       | 0.43%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 35       | 0.4%    |
| Intel Wireless 3165                                               | 35       | 0.4%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 34       | 0.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 34       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 651      | 25.42%  |
| Intel                                 | 540      | 21.09%  |
| Ralink Technology                     | 273      | 10.66%  |
| Qualcomm Atheros                      | 268      | 10.46%  |
| TP-Link                               | 161      | 6.29%   |
| Ralink                                | 137      | 5.35%   |
| Broadcom                              | 78       | 3.05%   |
| Qualcomm Atheros Communications       | 66       | 2.58%   |
| NetGear                               | 54       | 2.11%   |
| D-Link                                | 42       | 1.64%   |
| ASUSTek Computer                      | 37       | 1.44%   |
| D-Link System                         | 30       | 1.17%   |
| MediaTek                              | 29       | 1.13%   |
| Microsoft                             | 24       | 0.94%   |
| IMC Networks                          | 22       | 0.86%   |
| Linksys                               | 20       | 0.78%   |
| Belkin Components                     | 20       | 0.78%   |
| Edimax Technology                     | 19       | 0.74%   |
| Broadcom Limited                      | 13       | 0.51%   |
| AVM                                   | 12       | 0.47%   |
| Sitecom Europe                        | 9        | 0.35%   |
| ZyDAS                                 | 5        | 0.2%    |
| Gemtek                                | 5        | 0.2%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5        | 0.2%    |
| Tenda                                 | 4        | 0.16%   |
| ZyXEL Communications                  | 3        | 0.12%   |
| TRENDnet                              | 3        | 0.12%   |
| Texas Instruments                     | 3        | 0.12%   |
| Marvell Technology Group              | 3        | 0.12%   |
| Accton Technology                     | 3        | 0.12%   |
| Wacom                                 | 2        | 0.08%   |
| VIA Technologies                      | 2        | 0.08%   |
| Samsung Electronics                   | 2        | 0.08%   |
| Mercucys                              | 2        | 0.08%   |
| Z-Com                                 | 1        | 0.04%   |
| Xiaomi                                | 1        | 0.04%   |
| Sagem                                 | 1        | 0.04%   |
| PLANEX                                | 1        | 0.04%   |
| Philips (or NXP)                      | 1        | 0.04%   |
| Netopia                               | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 165      | 6.34%   |
| Ralink MT7601U Wireless Adapter                                | 118      | 4.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 75       | 2.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 73       | 2.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 70       | 2.69%   |
| Realtek 802.11ac NIC                                           | 69       | 2.65%   |
| Qualcomm Atheros AR9271 802.11n                                | 53       | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 51       | 1.96%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 48       | 1.84%   |
| Ralink RT5370 Wireless Adapter                                 | 47       | 1.81%   |
| Intel Wireless-AC 9260                                         | 46       | 1.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 44       | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 41       | 1.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 39       | 1.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 35       | 1.34%   |
| Intel Wireless 3165                                            | 35       | 1.34%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 34       | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 34       | 1.31%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 30       | 1.15%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 29       | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 28       | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 28       | 1.08%   |
| Intel Wireless 7260                                            | 27       | 1.04%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 25       | 0.96%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 25       | 0.96%   |
| Intel Wireless 8260                                            | 24       | 0.92%   |
| Intel Wireless 7265                                            | 24       | 0.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 22       | 0.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 22       | 0.85%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 22       | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 21       | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 21       | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 20       | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 20       | 0.77%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 19       | 0.73%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 19       | 0.73%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 19       | 0.73%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 19       | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 18       | 0.69%   |
| Microsoft Xbox 360 Wireless Adapter                            | 18       | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 3238     | 55.29%  |
| Intel                                  | 1525     | 26.04%  |
| Qualcomm Atheros                       | 295      | 5.04%   |
| Nvidia                                 | 210      | 3.59%   |
| Broadcom                               | 158      | 2.7%    |
| Marvell Technology Group               | 69       | 1.18%   |
| Broadcom Limited                       | 51       | 0.87%   |
| Samsung Electronics                    | 48       | 0.82%   |
| VIA Technologies                       | 38       | 0.65%   |
| Xiaomi                                 | 30       | 0.51%   |
| ASIX Electronics                       | 24       | 0.41%   |
| D-Link System                          | 21       | 0.36%   |
| Aquantia                               | 20       | 0.34%   |
| MediaTek                               | 16       | 0.27%   |
| Huawei Technologies                    | 14       | 0.24%   |
| Sundance Technology Inc / IC Plus      | 10       | 0.17%   |
| Motorola PCS                           | 10       | 0.17%   |
| Qualcomm                               | 7        | 0.12%   |
| DisplayLink                            | 7        | 0.12%   |
| Silicon Integrated Systems [SiS]       | 5        | 0.09%   |
| ZTE WCDMA Technologies MSM             | 4        | 0.07%   |
| OPPO Electronics                       | 4        | 0.07%   |
| LG Electronics                         | 4        | 0.07%   |
| Google                                 | 4        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.05%   |
| Apple                                  | 3        | 0.05%   |
| 3Com                                   | 3        | 0.05%   |
| Spreadtrum Communications              | 2        | 0.03%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.03%   |
| Microchip Technology                   | 2        | 0.03%   |
| Mellanox Technologies                  | 2        | 0.03%   |
| JMicron Technology                     | 2        | 0.03%   |
| ICS Advent                             | 2        | 0.03%   |
| HTC (High Tech Computer)               | 2        | 0.03%   |
| ADMtek                                 | 2        | 0.03%   |
| vivo                                   | 1        | 0.02%   |
| ULi Electronics                        | 1        | 0.02%   |
| Trendchip Technologies                 | 1        | 0.02%   |
| Tehuti Networks                        | 1        | 0.02%   |
| T & A Mobile Phones                    | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2778     | 46.39%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 269      | 4.49%   |
| Intel Ethernet Connection (2) I219-V                              | 183      | 3.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 179      | 2.99%   |
| Intel I211 Gigabit Network Connection                             | 175      | 2.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 147      | 2.45%   |
| Nvidia MCP61 Ethernet                                             | 131      | 2.19%   |
| Intel Ethernet Connection I217-LM                                 | 105      | 1.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 98       | 1.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 95       | 1.59%   |
| Intel Ethernet Connection (7) I219-V                              | 85       | 1.42%   |
| Intel 82579V Gigabit Network Connection                           | 83       | 1.39%   |
| Intel Ethernet Connection I217-V                                  | 68       | 1.14%   |
| Intel Ethernet Controller I225-V                                  | 65       | 1.09%   |
| Intel Ethernet Connection (2) I218-V                              | 60       | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 47       | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 44       | 0.73%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 38       | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 38       | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 37       | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 37       | 0.62%   |
| Intel 82574L Gigabit Network Connection                           | 37       | 0.62%   |
| Intel 82578DM Gigabit Network Connection                          | 34       | 0.57%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 34       | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 32       | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 31       | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 28       | 0.47%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 28       | 0.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 24       | 0.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23       | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 22       | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 22       | 0.37%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 22       | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 22       | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22       | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19       | 0.32%   |
| Nvidia MCP77 Ethernet                                             | 19       | 0.32%   |
| Intel 82562V-2 10/100 Network Connection                          | 19       | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17       | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 17       | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5447     | 69.14%  |
| WiFi     | 2357     | 29.92%  |
| Modem    | 51       | 0.65%   |
| Unknown  | 23       | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4270     | 74.51%  |
| WiFi     | 1458     | 25.44%  |
| Unknown  | 3        | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3931     | 70.84%  |
| 2     | 1412     | 25.45%  |
| 3     | 126      | 2.27%   |
| 0     | 57       | 1.03%   |
| 4     | 14       | 0.25%   |
| 5     | 6        | 0.11%   |
| 7     | 2        | 0.04%   |
| 6     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 4570     | 81.46%  |
| Yes     | 1039     | 18.52%  |
| Unknown | 1        | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 482      | 33.01%  |
| Cambridge Silicon Radio         | 482      | 33.01%  |
| Realtek Semiconductor           | 106      | 7.26%   |
| Broadcom                        | 106      | 7.26%   |
| ASUSTek Computer                | 88       | 6.03%   |
| Qualcomm Atheros Communications | 49       | 3.36%   |
| IMC Networks                    | 31       | 2.12%   |
| Lite-On Technology              | 18       | 1.23%   |
| Apple                           | 17       | 1.16%   |
| Integrated System Solution      | 16       | 1.1%    |
| MediaTek                        | 10       | 0.68%   |
| Belkin Components               | 9        | 0.62%   |
| TP-Link                         | 5        | 0.34%   |
| Edimax Technology               | 5        | 0.34%   |
| Dell                            | 5        | 0.34%   |
| Conwise Technology              | 5        | 0.34%   |
| Dynex                           | 4        | 0.27%   |
| Ralink                          | 3        | 0.21%   |
| Logitech                        | 3        | 0.21%   |
| Motorola PCS                    | 2        | 0.14%   |
| Micro Star International        | 2        | 0.14%   |
| Hewlett-Packard                 | 2        | 0.14%   |
| Foxconn / Hon Hai               | 2        | 0.14%   |
| Roper                           | 1        | 0.07%   |
| Primax Electronics              | 1        | 0.07%   |
| Microsoft                       | 1        | 0.07%   |
| Kensington                      | 1        | 0.07%   |
| HTC (High Tech Computer)        | 1        | 0.07%   |
| Fujitsu Siemens Computers       | 1        | 0.07%   |
| D-Link                          | 1        | 0.07%   |
| Cypress Semiconductor           | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 481      | 32.88%  |
| Intel AX200 Bluetooth                                    | 145      | 9.91%   |
| Intel Bluetooth wireless interface                       | 117      | 8%      |
| Realtek Bluetooth Radio                                  | 74       | 5.06%   |
| Intel Wireless-AC 3168 Bluetooth                         | 67       | 4.58%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 63       | 4.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 45       | 3.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 41       | 2.8%    |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 38       | 2.6%    |
| Intel AX201 Bluetooth                                    | 31       | 2.12%   |
| Intel AX210 Bluetooth                                    | 27       | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                           | 23       | 1.57%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 17       | 1.16%   |
| IMC Networks Bluetooth Radio                             | 16       | 1.09%   |
| ASUS Bluetooth Device                                    | 16       | 1.09%   |
| Qualcomm Atheros  Bluetooth Device                       | 12       | 0.82%   |
| ASUS BCM20702A0                                          | 12       | 0.82%   |
| Lite-On Bluetooth Device                                 | 11       | 0.75%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 11       | 0.75%   |
| MediaTek Wireless_Device                                 | 10       | 0.68%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 9        | 0.62%   |
| ASUS Bluetooth Radio                                     | 8        | 0.55%   |
| Realtek RTL8821A Bluetooth                               | 7        | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 7        | 0.48%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 7        | 0.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 6        | 0.41%   |
| IMC Networks Bluetooth Device                            | 6        | 0.41%   |
| Broadcom BCM2045 Bluetooth                               | 6        | 0.41%   |
| ASUS Qualcomm Bluetooth 4.1                              | 6        | 0.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 6        | 0.41%   |
| Apple Bluetooth USB Host Controller                      | 6        | 0.41%   |
| TP-Link UB500 Adapter                                    | 5        | 0.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 5        | 0.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 5        | 0.34%   |
| Integrated System Solution Bluetooth Device              | 5        | 0.34%   |
| Conwise CW6622                                           | 5        | 0.34%   |
| Broadcom HP Bluethunder                                  | 5        | 0.34%   |
| Apple Bluetooth HCI                                      | 5        | 0.34%   |
| IMC Networks Wireless_Device                             | 4        | 0.27%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 4        | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 3381     | 38.04%  |
| AMD                                             | 2300     | 25.87%  |
| Nvidia                                          | 2074     | 23.33%  |
| C-Media Electronics                             | 238      | 2.68%   |
| Creative Labs                                   | 144      | 1.62%   |
| Logitech                                        | 88       | 0.99%   |
| VIA Technologies                                | 54       | 0.61%   |
| Texas Instruments                               | 49       | 0.55%   |
| Generalplus Technology                          | 42       | 0.47%   |
| JMTek                                           | 36       | 0.4%    |
| Kingston Technology                             | 32       | 0.36%   |
| Creative Technology                             | 30       | 0.34%   |
| GN Netcom                                       | 22       | 0.25%   |
| Razer USA                                       | 20       | 0.22%   |
| SteelSeries ApS                                 | 16       | 0.18%   |
| Plantronics                                     | 16       | 0.18%   |
| Tenx Technology                                 | 15       | 0.17%   |
| Corsair                                         | 15       | 0.17%   |
| Focusrite-Novation                              | 14       | 0.16%   |
| ASUSTek Computer                                | 14       | 0.16%   |
| M-Audio                                         | 11       | 0.12%   |
| Silicon Integrated Systems [SiS]                | 9        | 0.1%    |
| Samson Technologies                             | 9        | 0.1%    |
| Microsoft                                       | 8        | 0.09%   |
| DSEA A/S                                        | 8        | 0.09%   |
| Dell                                            | 8        | 0.09%   |
| Blue Microphones                                | 8        | 0.09%   |
| Yamaha                                          | 7        | 0.08%   |
| Realtek Semiconductor                           | 7        | 0.08%   |
| Ensoniq                                         | 7        | 0.08%   |
| BEHRINGER International                         | 7        | 0.08%   |
| XMOS                                            | 6        | 0.07%   |
| SAVITECH                                        | 6        | 0.07%   |
| KTMicro                                         | 6        | 0.07%   |
| Asahi Kasei Microsystems                        | 6        | 0.07%   |
| Sony                                            | 5        | 0.06%   |
| Sennheiser Communications                       | 5        | 0.06%   |
| Licensed by Sony Computer Entertainment America | 5        | 0.06%   |
| ATI Technologies                                | 5        | 0.06%   |
| AKAI Professional M.I.                          | 5        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 577      | 5.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 557      | 5.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 431      | 4.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 349      | 3.4%    |
| AMD Starship/Matisse HD Audio Controller                                          | 325      | 3.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 309      | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 277      | 2.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 257      | 2.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 242      | 2.36%   |
| AMD Family 17h/19h HD Audio Controller                                            | 230      | 2.24%   |
| AMD FCH Azalia Controller                                                         | 224      | 2.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 222      | 2.17%   |
| Intel 200 Series PCH HD Audio                                                     | 216      | 2.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 195      | 1.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 193      | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 181      | 1.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 157      | 1.53%   |
| Nvidia MCP61 High Definition Audio                                                | 152      | 1.48%   |
| Nvidia High Definition Audio Controller                                           | 149      | 1.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 146      | 1.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 142      | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                        | 140      | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 126      | 1.23%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 111      | 1.08%   |
| Nvidia GP106 High Definition Audio Controller                                     | 110      | 1.07%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 109      | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                     | 104      | 1.01%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 104      | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                                     | 101      | 0.99%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 101      | 0.99%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 95       | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                     | 93       | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 91       | 0.89%   |
| Nvidia GP108 High Definition Audio Controller                                     | 85       | 0.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 80       | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                                | 77       | 0.75%   |
| Nvidia GF119 HDMI Audio Controller                                                | 69       | 0.67%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 67       | 0.65%   |
| Nvidia GM206 High Definition Audio Controller                                     | 64       | 0.62%   |
| Nvidia GM204 High Definition Audio Controller                                     | 63       | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 431      | 17.39%  |
| Kingston            | 425      | 17.14%  |
| Corsair             | 290      | 11.7%   |
| SK hynix            | 214      | 8.63%   |
| Crucial             | 209      | 8.43%   |
| Samsung Electronics | 204      | 8.23%   |
| G.Skill             | 199      | 8.03%   |
| Micron Technology   | 94       | 3.79%   |
| A-DATA Technology   | 48       | 1.94%   |
| Patriot             | 39       | 1.57%   |
| Nanya Technology    | 38       | 1.53%   |
| Team                | 36       | 1.45%   |
| Ramaxel Technology  | 22       | 0.89%   |
| Elpida              | 19       | 0.77%   |
| GOODRAM             | 15       | 0.61%   |
| AMD                 | 15       | 0.61%   |
| Unknown             | 15       | 0.61%   |
| Transcend           | 10       | 0.4%    |
| Kingmax             | 10       | 0.4%    |
| Unknown (ABCD)      | 9        | 0.36%   |
| Unifosa             | 9        | 0.36%   |
| Smart               | 8        | 0.32%   |
| GeIL                | 8        | 0.32%   |
| Apacer              | 6        | 0.24%   |
| Teikon              | 5        | 0.2%    |
| Silicon Power       | 5        | 0.2%    |
| PNY                 | 5        | 0.2%    |
| Wilk Elektronik     | 4        | 0.16%   |
| Sesame              | 4        | 0.16%   |
| OCZ                 | 4        | 0.16%   |
| Multilaser          | 4        | 0.16%   |
| Kllisre             | 4        | 0.16%   |
| Avant               | 4        | 0.16%   |
| Unknown (0x8551)    | 3        | 0.12%   |
| TakeMS              | 3        | 0.12%   |
| Ramos Technology    | 3        | 0.12%   |
| Qumo                | 3        | 0.12%   |
| KETECH              | 3        | 0.12%   |
| CSX                 | 3        | 0.12%   |
| Wilk                | 2        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 31       | 1.14%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 27       | 0.99%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 23       | 0.85%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                 | 22       | 0.81%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 21       | 0.77%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 21       | 0.77%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s      | 18       | 0.66%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 17       | 0.63%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 16       | 0.59%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                 | 16       | 0.59%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 16       | 0.59%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 15       | 0.55%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s       | 15       | 0.55%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 15       | 0.55%   |
| Unknown                                                      | 15       | 0.55%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 14       | 0.51%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s          | 13       | 0.48%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                      | 12       | 0.44%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 12       | 0.44%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 12       | 0.44%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s          | 12       | 0.44%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s          | 12       | 0.44%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s        | 12       | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                  | 11       | 0.4%    |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s       | 11       | 0.4%    |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 11       | 0.4%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 11       | 0.4%    |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                 | 10       | 0.37%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                       | 10       | 0.37%   |
| Unknown RAM Module 1024MB DIMM SDRAM                         | 10       | 0.37%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                  | 10       | 0.37%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s         | 10       | 0.37%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s        | 10       | 0.37%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s          | 10       | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                  | 9        | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 9        | 0.33%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 9        | 0.33%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s          | 9        | 0.33%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s          | 9        | 0.33%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s          | 9        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 866      | 39.76%  |
| DDR3         | 822      | 37.74%  |
| Unknown      | 176      | 8.08%   |
| DDR2         | 152      | 6.98%   |
| SDRAM        | 112      | 5.14%   |
| DDR          | 32       | 1.47%   |
| LPDDR4       | 12       | 0.55%   |
| DDR5         | 3        | 0.14%   |
| DRAM         | 2        | 0.09%   |
| DDR2 FB-DIMM | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2014     | 94.24%  |
| SODIMM       | 113      | 5.29%   |
| FB-DIMM      | 6        | 0.28%   |
| RIMM         | 3        | 0.14%   |
| Row Of Chips | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 824      | 35%     |
| 4096  | 638      | 27.1%   |
| 2048  | 423      | 17.97%  |
| 16384 | 261      | 11.09%  |
| 1024  | 111      | 4.72%   |
| 32768 | 73       | 3.1%    |
| 512   | 19       | 0.81%   |
| 1536  | 2        | 0.08%   |
| 256   | 2        | 0.08%   |
| 16    | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 463      | 19.21%  |
| 1333    | 368      | 15.27%  |
| 3200    | 200      | 8.3%    |
| 2400    | 143      | 5.93%   |
| 3600    | 136      | 5.64%   |
| 800     | 124      | 5.15%   |
| 2133    | 113      | 4.69%   |
| 2667    | 106      | 4.4%    |
| 667     | 83       | 3.44%   |
| Unknown | 66       | 2.74%   |
| 1867    | 56       | 2.32%   |
| 3000    | 49       | 2.03%   |
| 1866    | 43       | 1.78%   |
| 2933    | 39       | 1.62%   |
| 3400    | 35       | 1.45%   |
| 3466    | 31       | 1.29%   |
| 1800    | 31       | 1.29%   |
| 1066    | 27       | 1.12%   |
| 2666    | 24       | 1%      |
| 3733    | 21       | 0.87%   |
| 3800    | 19       | 0.79%   |
| 3866    | 17       | 0.71%   |
| 2800    | 15       | 0.62%   |
| 400     | 15       | 0.62%   |
| 1067    | 14       | 0.58%   |
| 1334    | 10       | 0.41%   |
| 1648    | 9        | 0.37%   |
| 333     | 9        | 0.37%   |
| 2733    | 8        | 0.33%   |
| 2048    | 8        | 0.33%   |
| 2000    | 8        | 0.33%   |
| 3151    | 7        | 0.29%   |
| 1639    | 7        | 0.29%   |
| 2465    | 6        | 0.25%   |
| 533     | 6        | 0.25%   |
| 49926   | 5        | 0.21%   |
| 4800    | 5        | 0.21%   |
| 3334    | 5        | 0.21%   |
| 3100    | 5        | 0.21%   |
| 3007    | 5        | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 151      | 37.47%  |
| Brother Industries       | 90       | 22.33%  |
| Canon                    | 59       | 14.64%  |
| Samsung Electronics      | 32       | 7.94%   |
| Seiko Epson              | 31       | 7.69%   |
| QinHeng Electronics      | 6        | 1.49%   |
| Prolific Technology      | 5        | 1.24%   |
| Dymo-CoStar              | 4        | 0.99%   |
| Ricoh                    | 3        | 0.74%   |
| Pantum                   | 3        | 0.74%   |
| Panasonic (Matsushita)   | 3        | 0.74%   |
| Xerox                    | 2        | 0.5%    |
| Seiko Instruments        | 2        | 0.5%    |
| Kyocera                  | 2        | 0.5%    |
| Dell                     | 2        | 0.5%    |
| Sato                     | 1        | 0.25%   |
| Oki Data                 | 1        | 0.25%   |
| NXP Semiconductors       | 1        | 0.25%   |
| Magic Control Technology | 1        | 0.25%   |
| Lexmark International    | 1        | 0.25%   |
| Fuji Xerox               | 1        | 0.25%   |
| Agere Systems (Lucent)   | 1        | 0.25%   |
| Unknown                  | 1        | 0.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| HP LaserJet 1020                   | 7        | 1.72%   |
| QinHeng CH340S                     | 6        | 1.48%   |
| HP LaserJet Professional P1102w    | 6        | 1.48%   |
| HP DeskJet 2620 All-in-One Printer | 6        | 1.48%   |
| Brother Printer                    | 6        | 1.48%   |
| Samsung M2070 Series               | 5        | 1.23%   |
| Samsung M2020 Series               | 5        | 1.23%   |
| Prolific PL2305 Parallel Port      | 5        | 1.23%   |
| HP Officejet 4500 G510n-z          | 5        | 1.23%   |
| HP LaserJet P1005                  | 5        | 1.23%   |
| Brother HL-L2360D series           | 5        | 1.23%   |
| Samsung SCX-3400 Series            | 4        | 0.99%   |
| Samsung C48x Series                | 4        | 0.99%   |
| HP OfficeJet 5200 series           | 4        | 0.99%   |
| HP LaserJet 1018                   | 4        | 0.99%   |
| HP DeskJet F4200 series            | 4        | 0.99%   |
| Brother DCP-7055 scanner/printer   | 4        | 0.99%   |
| Seiko Epson L3150 Series           | 3        | 0.74%   |
| Seiko Epson L210 Series            | 3        | 0.74%   |
| Panasonic (Matsushita) KX-MB1500RU | 3        | 0.74%   |
| HP OfficeJet Pro 8020 series       | 3        | 0.74%   |
| HP OfficeJet Pro 69                | 3        | 0.74%   |
| HP LaserJet Professional P 1102w   | 3        | 0.74%   |
| HP LaserJet P1102                  | 3        | 0.74%   |
| HP ENVY 5540 series                | 3        | 0.74%   |
| HP ENVY 4520 series                | 3        | 0.74%   |
| HP DeskJet 3630 series             | 3        | 0.74%   |
| HP Deskjet 2540 series             | 3        | 0.74%   |
| HP DeskJet 2130 series             | 3        | 0.74%   |
| HP Deskjet 2050 J510               | 3        | 0.74%   |
| Canon LiDE 400                     | 3        | 0.74%   |
| Brother MFC-L8600CDW               | 3        | 0.74%   |
| Brother MFC-J497DW                 | 3        | 0.74%   |
| Brother HL-2270DW Laser Printer    | 3        | 0.74%   |
| Brother HL-1210W series            | 3        | 0.74%   |
| Brother HL-1110 series             | 3        | 0.74%   |
| Brother DCP-9020CDW                | 3        | 0.74%   |
| Seiko Epson Printer                | 2        | 0.49%   |
| Seiko Epson L365 Series            | 2        | 0.49%   |
| Seiko Epson L220 Series            | 2        | 0.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 68       | 59.65%  |
| Seiko Epson                 | 23       | 20.18%  |
| Hewlett-Packard             | 11       | 9.65%   |
| Mustek Systems              | 4        | 3.51%   |
| Ultima Electronics          | 2        | 1.75%   |
| AGFA-Gevaert NV             | 2        | 1.75%   |
| Acer Peripherals (now BenQ) | 2        | 1.75%   |
| UMAX                        | 1        | 0.88%   |
| Microtek International      | 1        | 0.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LIDE 25                                                                | 10       | 8.77%   |
| Canon CanoScan LiDE 110                                                               | 10       | 8.77%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 7        | 6.14%   |
| Canon CanoScan LiDE 120                                                               | 7        | 6.14%   |
| Canon CanoScan LiDE 220                                                               | 5        | 4.39%   |
| Canon CanoScan LiDE 210                                                               | 5        | 4.39%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 4        | 3.51%   |
| Canon CanoScan LiDE 700F                                                              | 4        | 3.51%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 3        | 2.63%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3        | 2.63%   |
| Canon CanoScan LiDE 90                                                                | 3        | 2.63%   |
| Canon CanoScan LiDE 60                                                                | 3        | 2.63%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2        | 1.75%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 2        | 1.75%   |
| Mustek Systems SNAPSCAN e22                                                           | 2        | 1.75%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 2        | 1.75%   |
| HP ScanJet 2400c                                                                      | 2        | 1.75%   |
| Canon CanoScan N650U/N656U                                                            | 2        | 1.75%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 1.75%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 2        | 1.75%   |
| Canon CanoScan LiDE 100                                                               | 2        | 1.75%   |
| Canon CanoScan 9000F Mark II                                                          | 2        | 1.75%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                           | 2        | 1.75%   |
| UMAX Astra 4400/4450                                                                  | 1        | 0.88%   |
| Seiko Epson Stylus Photo RX500/510                                                    | 1        | 0.88%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1        | 0.88%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1        | 0.88%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1        | 0.88%   |
| Seiko Epson GT-F600 [Perfection 4180]                                                 | 1        | 0.88%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1        | 0.88%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 0.88%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1        | 0.88%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 1        | 0.88%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1        | 0.88%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 0.88%   |
| Microtek International USB1200 Scanner                                                | 1        | 0.88%   |
| HP ScanJet G3010                                                                      | 1        | 0.88%   |
| HP ScanJet 5200c                                                                      | 1        | 0.88%   |
| HP ScanJet 4070 PhotoSmart                                                            | 1        | 0.88%   |
| HP ScanJet 3800c                                                                      | 1        | 0.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 379      | 34.45%  |
| Microdia                               | 105      | 9.55%   |
| Microsoft                              | 77       | 7%      |
| Samsung Electronics                    | 59       | 5.36%   |
| Generalplus Technology                 | 37       | 3.36%   |
| Chicony Electronics                    | 35       | 3.18%   |
| Z-Star Microelectronics                | 33       | 3%      |
| Sunplus Innovation Technology          | 32       | 2.91%   |
| GEMBIRD                                | 24       | 2.18%   |
| KYE Systems (Mouse Systems)            | 23       | 2.09%   |
| Creative Technology                    | 23       | 2.09%   |
| Realtek Semiconductor                  | 20       | 1.82%   |
| Apple                                  | 20       | 1.82%   |
| Aveo Technology                        | 17       | 1.55%   |
| IMC Networks                           | 15       | 1.36%   |
| ARC International                      | 13       | 1.18%   |
| Arkmicro Technologies                  | 12       | 1.09%   |
| Cubeternet                             | 10       | 0.91%   |
| Genesys Logic                          | 9        | 0.82%   |
| Sonix Technology                       | 8        | 0.73%   |
| MacroSilicon                           | 8        | 0.73%   |
| LG Electronics                         | 8        | 0.73%   |
| Jieli Technology                       | 8        | 0.73%   |
| Philips (or NXP)                       | 7        | 0.64%   |
| Alcor Micro                            | 7        | 0.64%   |
| Pixart Imaging                         | 6        | 0.55%   |
| Novatek Microelectronics               | 6        | 0.55%   |
| Hewlett-Packard                        | 6        | 0.55%   |
| Guillemot                              | 6        | 0.55%   |
| Trust                                  | 4        | 0.36%   |
| SJ-180517-N                            | 4        | 0.36%   |
| Silicon Motion                         | 4        | 0.36%   |
| Huawei Technologies                    | 4        | 0.36%   |
| AVerMedia Technologies                 | 4        | 0.36%   |
| Asuscom Network                        | 4        | 0.36%   |
| Unknown                                | 3        | 0.27%   |
| Syntek                                 | 3        | 0.27%   |
| HD USB Camera                          | 3        | 0.27%   |
| HD 2MP WEBCAM                          | 3        | 0.27%   |
| Cheng Uei Precision Industry (Foxlink) | 3        | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 93       | 8.44%   |
| Samsung Galaxy A5 (MTP)                           | 59       | 5.35%   |
| Logitech HD Pro Webcam C920                       | 42       | 3.81%   |
| Microsoft LifeCam HD-3000                         | 34       | 3.09%   |
| Microdia USB 2.0 Camera                           | 29       | 2.63%   |
| Microdia Webcam Vitade AF                         | 28       | 2.54%   |
| Logitech HD Webcam C525                           | 26       | 2.36%   |
| Logitech Webcam C310                              | 24       | 2.18%   |
| Logitech Webcam C170                              | 24       | 2.18%   |
| Apple iPhone5/5C/5S/6                             | 20       | 1.81%   |
| Microdia Camera                                   | 19       | 1.72%   |
| Generalplus GENERAL WEBCAM                        | 18       | 1.63%   |
| Microdia Sonix USB 2.0 Camera                     | 14       | 1.27%   |
| Z-Star Venus USB2.0 Camera                        | 13       | 1.18%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 13       | 1.18%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 13       | 1.18%   |
| ARC International Camera                          | 13       | 1.18%   |
| Sunplus Full HD webcam                            | 12       | 1.09%   |
| Logitech Webcam C210                              | 12       | 1.09%   |
| Logitech HD Webcam C615                           | 12       | 1.09%   |
| Chicony HP High Definition 1MP Webcam             | 11       | 1%      |
| Realtek Full HD webcam                            | 10       | 0.91%   |
| Logitech C922 Pro Stream Webcam                   | 10       | 0.91%   |
| Logitech C920 PRO HD Webcam                       | 10       | 0.91%   |
| IMC Networks XHC Camera                           | 10       | 0.91%   |
| GEMBIRD USB2.0 PC CAMERA                          | 9        | 0.82%   |
| Arkmicro USB2.0 PC CAMERA                         | 9        | 0.82%   |
| Sunplus SPCA2650 AV Camera                        | 8        | 0.73%   |
| Microsoft LifeCam Cinema                          | 8        | 0.73%   |
| Logitech Webcam C925e                             | 8        | 0.73%   |
| Logitech Webcam C200                              | 8        | 0.73%   |
| Logitech QuickCam Pro 9000                        | 8        | 0.73%   |
| Logitech HD Webcam C910                           | 8        | 0.73%   |
| Jieli USB PHY 2.0                                 | 8        | 0.73%   |
| Creative Live! Cam Chat HD [VF0700]               | 8        | 0.73%   |
| Microsoft LifeCam HD-5000                         | 7        | 0.64%   |
| Logitech HD Webcam C510                           | 7        | 0.64%   |
| Logitech BRIO Ultra HD Webcam                     | 7        | 0.64%   |
| Aveo UVC camera (Bresser microscope)              | 7        | 0.64%   |
| Aveo USB2.0 Camera                                | 7        | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 4        | 44.44%  |
| Upek                       | 1        | 11.11%  |
| Synaptics                  | 1        | 11.11%  |
| STMicroelectronics         | 1        | 11.11%  |
| Shenzhen Goodix Technology | 1        | 11.11%  |
| AuthenTec                  | 1        | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]            | 4        | 44.44%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 11.11%  |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1        | 11.11%  |
| STMicroelectronics Fingerprint Reader                  | 1        | 11.11%  |
| Shenzhen Goodix  Fingerprint Device                    | 1        | 11.11%  |
| AuthenTec AES2550 Fingerprint Sensor                   | 1        | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Alcor Micro                       | 8        | 24.24%  |
| OmniKey                           | 4        | 12.12%  |
| SCM Microsystems                  | 3        | 9.09%   |
| Realtek Semiconductor             | 2        | 6.06%   |
| Gemalto (was Gemplus)             | 2        | 6.06%   |
| Chicony Electronics               | 2        | 6.06%   |
| VASCO Data Security International | 1        | 3.03%   |
| Reiner SCT Kartensysteme          | 1        | 3.03%   |
| Precise Biometrics                | 1        | 3.03%   |
| In Focus Systems                  | 1        | 3.03%   |
| Hewlett-Packard                   | 1        | 3.03%   |
| Giesecke & Devrient               | 1        | 3.03%   |
| Fujitsu Siemens Computers         | 1        | 3.03%   |
| BIT4ID                            | 1        | 3.03%   |
| Aladdin R.D.                      | 1        | 3.03%   |
| Aladdin Knowledge Systems         | 1        | 3.03%   |
| Aktiv                             | 1        | 3.03%   |
| Advanced Card Systems             | 1        | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Alcor Micro Watchdata W 1981                                    | 5        | 15.15%  |
| OmniKey CardMan 3021 / 3121                                     | 3        | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                             | 3        | 9.09%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 2        | 6.06%   |
| Realtek Semiconductor Smart Card Reader Interface               | 2        | 6.06%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 2        | 6.06%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 2        | 6.06%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 3.03%   |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 3.03%   |
| Reiner SCT Kartensysteme tanJack USB                            | 1        | 3.03%   |
| Precise Biometrics 200 MC FingerPrint and SmartCard Reader      | 1        | 3.03%   |
| OmniKey CardMan 1021                                            | 1        | 3.03%   |
| In Focus Systems EMV Smartcard Reader                           | 1        | 3.03%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                   | 1        | 3.03%   |
| Giesecke & Devrient StarSign CUT                                | 1        | 3.03%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                   | 1        | 3.03%   |
| BIT4ID miniLector-S                                             | 1        | 3.03%   |
| Aladdin R.D. JaCarta                                            | 1        | 3.03%   |
| Aladdin Knowledge Systems Token JC                              | 1        | 3.03%   |
| Aktiv Rutoken lite                                              | 1        | 3.03%   |
| Advanced Card Systems ACR122U                                   | 1        | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 4651     | 82.36%  |
| 1     | 824      | 14.59%  |
| 2     | 131      | 2.32%   |
| 3     | 25       | 0.44%   |
| 4     | 9        | 0.16%   |
| 5     | 5        | 0.09%   |
| 6     | 2        | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 377      | 32.42%  |
| Net/wireless             | 314      | 27%     |
| Communication controller | 130      | 11.18%  |
| Unassigned class         | 52       | 4.47%   |
| Multimedia controller    | 44       | 3.78%   |
| Sound                    | 42       | 3.61%   |
| Network                  | 32       | 2.75%   |
| Bluetooth                | 27       | 2.32%   |
| Camera                   | 24       | 2.06%   |
| Chipcard                 | 20       | 1.72%   |
| Storage/raid             | 17       | 1.46%   |
| Net/ethernet             | 17       | 1.46%   |
| Card reader              | 17       | 1.46%   |
| Storage/ide              | 15       | 1.29%   |
| Modem                    | 13       | 1.12%   |
| Fingerprint reader       | 8        | 0.69%   |
| Dvb card                 | 7        | 0.6%    |
| Tv card                  | 2        | 0.17%   |
| Firewire controller      | 2        | 0.17%   |
| Unclassified device      | 1        | 0.09%   |
| Storage/nvme             | 1        | 0.09%   |
| Storage/ata              | 1        | 0.09%   |

