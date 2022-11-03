Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 3251

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E475 20H40006US    | [d59bd1e8f1](https://linux-hardware.org/?probe=d59bd1e8f1) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [4342ecb0f9](https://linux-hardware.org/?probe=4342ecb0f9) | Nov 02, 2022 |
| Google        | Terra                       | [46299bf228](https://linux-hardware.org/?probe=46299bf228) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [fd32769391](https://linux-hardware.org/?probe=fd32769391) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [d3c1c92563](https://linux-hardware.org/?probe=d3c1c92563) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [0ffaee423b](https://linux-hardware.org/?probe=0ffaee423b) | Nov 02, 2022 |
| ASUSTek       | 1005HA                      | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | G42                         | [18c487d99d](https://linux-hardware.org/?probe=18c487d99d) | Nov 02, 2022 |
| Digma         | EVE 11 C422 ES1068EW        | [f5177de131](https://linux-hardware.org/?probe=f5177de131) | Nov 02, 2022 |
| Toshiba       | Satellite L755              | [dc3d60731e](https://linux-hardware.org/?probe=dc3d60731e) | Nov 01, 2022 |
| Acer          | Aspire one                  | [bfb9f97d74](https://linux-hardware.org/?probe=bfb9f97d74) | Oct 31, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c9e0b81f80](https://linux-hardware.org/?probe=c9e0b81f80) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| ASUSTek       | G75VW                       | [6f1d41a85c](https://linux-hardware.org/?probe=6f1d41a85c) | Oct 31, 2022 |
| Acer          | Aspire one                  | [82b34552f6](https://linux-hardware.org/?probe=82b34552f6) | Oct 31, 2022 |
| Aquarius      | NS585                       | [e4b4e0456d](https://linux-hardware.org/?probe=e4b4e0456d) | Oct 31, 2022 |
| Apple         | MacBookPro5,5               | [00e1f1f754](https://linux-hardware.org/?probe=00e1f1f754) | Oct 31, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a872c9888a](https://linux-hardware.org/?probe=a872c9888a) | Oct 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [45f670d99f](https://linux-hardware.org/?probe=45f670d99f) | Oct 30, 2022 |
| Acer          | Aspire A515-51G             | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| ASUSTek       | N751JK                      | [eea92055f3](https://linux-hardware.org/?probe=eea92055f3) | Oct 30, 2022 |
| Dell          | Latitude 5501               | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| Notebook      | W230SD                      | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Dell          | Latitude 5590               | [c7fa986fbd](https://linux-hardware.org/?probe=c7fa986fbd) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| Insyde        | Braswell                    | [d98b2d9661](https://linux-hardware.org/?probe=d98b2d9661) | Oct 29, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | [4acb2d0863](https://linux-hardware.org/?probe=4acb2d0863) | Oct 29, 2022 |
| Dell          | XPS 17 9720                 | [270b988521](https://linux-hardware.org/?probe=270b988521) | Oct 29, 2022 |
| Dell          | Precision 7520              | [30f6ad7a26](https://linux-hardware.org/?probe=30f6ad7a26) | Oct 29, 2022 |
| Dell          | Precision 7520              | [b81923dbd2](https://linux-hardware.org/?probe=b81923dbd2) | Oct 29, 2022 |
| MSI           | Modern 15 A10RBS            | [ddc3eded89](https://linux-hardware.org/?probe=ddc3eded89) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [60d1db050b](https://linux-hardware.org/?probe=60d1db050b) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [2a9f06c2b4](https://linux-hardware.org/?probe=2a9f06c2b4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [787904d265](https://linux-hardware.org/?probe=787904d265) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [0971db18ed](https://linux-hardware.org/?probe=0971db18ed) | Oct 28, 2022 |
| Toshiba       | Satellite L755              | [0fa70f29d4](https://linux-hardware.org/?probe=0fa70f29d4) | Oct 28, 2022 |
| Lenovo        | ThinkPad T530 239242U       | [dbf70338e9](https://linux-hardware.org/?probe=dbf70338e9) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| Dell          | Latitude 5280               | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Dell          | XPS 17 9700                 | [81121b7762](https://linux-hardware.org/?probe=81121b7762) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [0696abd43c](https://linux-hardware.org/?probe=0696abd43c) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [d42867d201](https://linux-hardware.org/?probe=d42867d201) | Oct 28, 2022 |
| ASUSTek       | X555QG                      | [bace747804](https://linux-hardware.org/?probe=bace747804) | Oct 28, 2022 |
| Acer          | Aspire A715-75G             | [78b0c55e62](https://linux-hardware.org/?probe=78b0c55e62) | Oct 28, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [02c6d1fe1a](https://linux-hardware.org/?probe=02c6d1fe1a) | Oct 28, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | [768c6c8357](https://linux-hardware.org/?probe=768c6c8357) | Oct 28, 2022 |
| SANTECH       | NHx0DB,DE                   | [db8c0489f4](https://linux-hardware.org/?probe=db8c0489f4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [63565608d1](https://linux-hardware.org/?probe=63565608d1) | Oct 28, 2022 |
| Google        | Boten                       | [2ed6baabf0](https://linux-hardware.org/?probe=2ed6baabf0) | Oct 27, 2022 |
| HP            | ZBook 15 G3                 | [2b886c255e](https://linux-hardware.org/?probe=2b886c255e) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [24da197a3a](https://linux-hardware.org/?probe=24da197a3a) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [3ab1fbc8e8](https://linux-hardware.org/?probe=3ab1fbc8e8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [faafe16cfb](https://linux-hardware.org/?probe=faafe16cfb) | Oct 27, 2022 |
| THTF          | CR F860-T1                  | [0e20f4f61a](https://linux-hardware.org/?probe=0e20f4f61a) | Oct 27, 2022 |
| ASUSTek       | X541UAK                     | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bfd570bbef](https://linux-hardware.org/?probe=bfd570bbef) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [58820ca517](https://linux-hardware.org/?probe=58820ca517) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [6b9a3ab27e](https://linux-hardware.org/?probe=6b9a3ab27e) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [a5bd8bebc7](https://linux-hardware.org/?probe=a5bd8bebc7) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bce3a8b1b3](https://linux-hardware.org/?probe=bce3a8b1b3) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [65a1d5242f](https://linux-hardware.org/?probe=65a1d5242f) | Oct 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| ASUSTek       | 1005HA                      | [118fed891f](https://linux-hardware.org/?probe=118fed891f) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [93b8dd8c3e](https://linux-hardware.org/?probe=93b8dd8c3e) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [5e08852d18](https://linux-hardware.org/?probe=5e08852d18) | Oct 25, 2022 |
| Lenovo        | Z50-70 20354                | [08b673e57b](https://linux-hardware.org/?probe=08b673e57b) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [438afb4185](https://linux-hardware.org/?probe=438afb4185) | Oct 25, 2022 |
| Toshiba       | dynabook MX/33KBL           | [7ee9057da2](https://linux-hardware.org/?probe=7ee9057da2) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [eae727e6a0](https://linux-hardware.org/?probe=eae727e6a0) | Oct 24, 2022 |
| Packard Be... | DOT S                       | [f280a6ccbc](https://linux-hardware.org/?probe=f280a6ccbc) | Oct 24, 2022 |
| Lenovo        | ThinkPad T470 20HES4VB00    | [f7b39d371a](https://linux-hardware.org/?probe=f7b39d371a) | Oct 24, 2022 |
| Packard Be... | H17HV                       | [2e94cfdd84](https://linux-hardware.org/?probe=2e94cfdd84) | Oct 24, 2022 |
| Alienware     | M11xR3                      | [62bf8b7b02](https://linux-hardware.org/?probe=62bf8b7b02) | Oct 24, 2022 |
| HP            | Pavilion g4                 | [3b6666b5ba](https://linux-hardware.org/?probe=3b6666b5ba) | Oct 24, 2022 |
| Lenovo        | V310-14IKB 80T2             | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| Dell          | Precision 7750              | [dd51bb7ccd](https://linux-hardware.org/?probe=dd51bb7ccd) | Oct 23, 2022 |
| HP            | Pavilion g4                 | [487a972bda](https://linux-hardware.org/?probe=487a972bda) | Oct 23, 2022 |
| Panasonic     | CF-LX3J-50M3                | [949acb4c3a](https://linux-hardware.org/?probe=949acb4c3a) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [6437fb22e1](https://linux-hardware.org/?probe=6437fb22e1) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [a19b5987c6](https://linux-hardware.org/?probe=a19b5987c6) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [88af6c857c](https://linux-hardware.org/?probe=88af6c857c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [246517ceab](https://linux-hardware.org/?probe=246517ceab) | Oct 22, 2022 |
| ASUSTek       | X756UQK                     | [2570a4e51f](https://linux-hardware.org/?probe=2570a4e51f) | Oct 22, 2022 |
| Toshiba       | Satellite P50-B-103         | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Apple         | MacBook5,2                  | [165ce75570](https://linux-hardware.org/?probe=165ce75570) | Oct 21, 2022 |
| Acer          | Swift SF314-42              | [2449f6a1b7](https://linux-hardware.org/?probe=2449f6a1b7) | Oct 21, 2022 |
| Aquarius      | NS585                       | [c953c5090c](https://linux-hardware.org/?probe=c953c5090c) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b13dc58884](https://linux-hardware.org/?probe=b13dc58884) | Oct 20, 2022 |
| ASUSTek       | G75VW                       | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| HP            | EliteBook 745 G3            | [3bfbc8dcac](https://linux-hardware.org/?probe=3bfbc8dcac) | Oct 20, 2022 |
| HP            | Laptop 15-ef2xxx            | [823d998220](https://linux-hardware.org/?probe=823d998220) | Oct 20, 2022 |
| Apple         | MacBook5,2                  | [1e76467975](https://linux-hardware.org/?probe=1e76467975) | Oct 20, 2022 |
| Aquarius      | NS585                       | [a134ed693c](https://linux-hardware.org/?probe=a134ed693c) | Oct 20, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [162e7a20b2](https://linux-hardware.org/?probe=162e7a20b2) | Oct 20, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| HP            | 245 G7                      | [9ec088c343](https://linux-hardware.org/?probe=9ec088c343) | Oct 19, 2022 |
| ASUSTek       | X541NA                      | [5b61fd3a38](https://linux-hardware.org/?probe=5b61fd3a38) | Oct 19, 2022 |
| Dell          | Inspiron 7590               | [43ec5b2df8](https://linux-hardware.org/?probe=43ec5b2df8) | Oct 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [67ebd92594](https://linux-hardware.org/?probe=67ebd92594) | Oct 19, 2022 |
| Acer          | Aspire A315-23G             | [93584b3b67](https://linux-hardware.org/?probe=93584b3b67) | Oct 19, 2022 |
| Fujitsu       | LIFEBOOK E753               | [1fbb05ae6b](https://linux-hardware.org/?probe=1fbb05ae6b) | Oct 18, 2022 |
| HP            | EliteBook 745 G3            | [e800d683ef](https://linux-hardware.org/?probe=e800d683ef) | Oct 18, 2022 |
| ASUSTek       | G75VW                       | [5ee12be257](https://linux-hardware.org/?probe=5ee12be257) | Oct 18, 2022 |
| UNOWHY        | Y13G010S4EI                 | [f7f13866aa](https://linux-hardware.org/?probe=f7f13866aa) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IAH7 82S... | [dfa3140411](https://linux-hardware.org/?probe=dfa3140411) | Oct 17, 2022 |
| Dell          | XPS 17 9700                 | [5368bd3ad6](https://linux-hardware.org/?probe=5368bd3ad6) | Oct 17, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e076f9208c](https://linux-hardware.org/?probe=e076f9208c) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | [10bcc184e7](https://linux-hardware.org/?probe=10bcc184e7) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | [a88a291921](https://linux-hardware.org/?probe=a88a291921) | Oct 16, 2022 |
| Lenovo        | Legion Y545 81Q6            | [b6162e2c5e](https://linux-hardware.org/?probe=b6162e2c5e) | Oct 16, 2022 |
| Dell          | Inspiron 1545               | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| Dell          | Latitude 3320               | [e4645890b8](https://linux-hardware.org/?probe=e4645890b8) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | [ae7d737ee5](https://linux-hardware.org/?probe=ae7d737ee5) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | [5cbc449f36](https://linux-hardware.org/?probe=5cbc449f36) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | [fb37bc6617](https://linux-hardware.org/?probe=fb37bc6617) | Oct 15, 2022 |
| HP            | EliteBook Folio 1040 G1     | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Panasonic     | CF-LX3J-50M3                | [95386977de](https://linux-hardware.org/?probe=95386977de) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [8cf96a6d0b](https://linux-hardware.org/?probe=8cf96a6d0b) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [a68e7df338](https://linux-hardware.org/?probe=a68e7df338) | Oct 14, 2022 |
| Dell          | Latitude E6330              | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| Dell          | Inspiron 5502               | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| MSI           | MS-N014                     | [87e6e540be](https://linux-hardware.org/?probe=87e6e540be) | Oct 14, 2022 |
| Google        | Robo                        | [d070697e72](https://linux-hardware.org/?probe=d070697e72) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a1b02901a1](https://linux-hardware.org/?probe=a1b02901a1) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a0f4cd454d](https://linux-hardware.org/?probe=a0f4cd454d) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dfc5a5f754](https://linux-hardware.org/?probe=dfc5a5f754) | Oct 13, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [e560a29570](https://linux-hardware.org/?probe=e560a29570) | Oct 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [00d174fcf4](https://linux-hardware.org/?probe=00d174fcf4) | Oct 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ccee0b66d9](https://linux-hardware.org/?probe=ccee0b66d9) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | [22904f1270](https://linux-hardware.org/?probe=22904f1270) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | [ecd8555f97](https://linux-hardware.org/?probe=ecd8555f97) | Oct 12, 2022 |
| Thomson       | N14C4WH64                   | [bfc16b9ded](https://linux-hardware.org/?probe=bfc16b9ded) | Oct 12, 2022 |
| ASUSTek       | N53Jg                       | [0b4302ed6c](https://linux-hardware.org/?probe=0b4302ed6c) | Oct 11, 2022 |
| Apple         | MacBookAir7,2               | [8b4c66e10a](https://linux-hardware.org/?probe=8b4c66e10a) | Oct 11, 2022 |
| Dell          | Precision 7720              | [2252c7bd79](https://linux-hardware.org/?probe=2252c7bd79) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| Apple         | MacBook5,2                  | [4687cf8900](https://linux-hardware.org/?probe=4687cf8900) | Oct 10, 2022 |
| Toshiba       | Satellite A100              | [f280857c1c](https://linux-hardware.org/?probe=f280857c1c) | Oct 09, 2022 |
| Dell          | Inspiron 14 5420            | [d9f937a8c4](https://linux-hardware.org/?probe=d9f937a8c4) | Oct 09, 2022 |
| HP            | Pavilion TS 11              | [1a6ea38863](https://linux-hardware.org/?probe=1a6ea38863) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [7785f0ebfb](https://linux-hardware.org/?probe=7785f0ebfb) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [487fd1959f](https://linux-hardware.org/?probe=487fd1959f) | Oct 08, 2022 |
| MSI           | Prestige 14Evo A11M         | [68137e0e8d](https://linux-hardware.org/?probe=68137e0e8d) | Oct 07, 2022 |
| HP            | Pavilion dv7                | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [e6eac5c882](https://linux-hardware.org/?probe=e6eac5c882) | Oct 07, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [b27c3b70a7](https://linux-hardware.org/?probe=b27c3b70a7) | Oct 07, 2022 |
| Shanghai Z... | ZXE CRB                     | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | [1b09c0a820](https://linux-hardware.org/?probe=1b09c0a820) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | [0fa7893206](https://linux-hardware.org/?probe=0fa7893206) | Oct 06, 2022 |
| Acer          | Predator PH315-53           | [0f3387ce35](https://linux-hardware.org/?probe=0f3387ce35) | Oct 06, 2022 |
| Toshiba       | Satellite L40               | [0f3e9273a6](https://linux-hardware.org/?probe=0f3e9273a6) | Oct 06, 2022 |
| Google        | Akemi                       | [5a165f46bc](https://linux-hardware.org/?probe=5a165f46bc) | Oct 05, 2022 |
| HP            | EliteBook 8570p             | [3079a45a56](https://linux-hardware.org/?probe=3079a45a56) | Oct 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [96b4cda722](https://linux-hardware.org/?probe=96b4cda722) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | [02d4090cce](https://linux-hardware.org/?probe=02d4090cce) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | [4f037d4c3d](https://linux-hardware.org/?probe=4f037d4c3d) | Oct 05, 2022 |
| Toshiba       | NB505                       | [9de39780b5](https://linux-hardware.org/?probe=9de39780b5) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [dea0d04059](https://linux-hardware.org/?probe=dea0d04059) | Oct 05, 2022 |
| Acer          | Aspire A315-23G             | [ab3508b938](https://linux-hardware.org/?probe=ab3508b938) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | EliteBook 8460p             | [8b9d1152e4](https://linux-hardware.org/?probe=8b9d1152e4) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8631c6f717](https://linux-hardware.org/?probe=8631c6f717) | Oct 04, 2022 |
| MSI           | GF65 Thin 10SDR             | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| HP            | EliteBook 735 G6            | [c3f86b0e1a](https://linux-hardware.org/?probe=c3f86b0e1a) | Oct 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [33b42f3ed1](https://linux-hardware.org/?probe=33b42f3ed1) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [5b2fac59ea](https://linux-hardware.org/?probe=5b2fac59ea) | Oct 04, 2022 |
| Shanghai Z... | ZXE CRB                     | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Lenovo        | ThinkPad Twist 20C41A3      | [3da96ac399](https://linux-hardware.org/?probe=3da96ac399) | Oct 04, 2022 |
| Acer          | Aspire A315-56              | [e799907aba](https://linux-hardware.org/?probe=e799907aba) | Oct 04, 2022 |
| Dell          | Precision M4800             | [1099761dca](https://linux-hardware.org/?probe=1099761dca) | Oct 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [31fa8b62ff](https://linux-hardware.org/?probe=31fa8b62ff) | Oct 04, 2022 |
| UNOWHY        | Y13G010S4EI                 | [38f5b56e5d](https://linux-hardware.org/?probe=38f5b56e5d) | Oct 04, 2022 |
| Dell          | Inspiron 5590               | [ed3bf1e99b](https://linux-hardware.org/?probe=ed3bf1e99b) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | [81ac41d8b9](https://linux-hardware.org/?probe=81ac41d8b9) | Oct 03, 2022 |
| Dell          | Latitude 2110               | [3fbbac2c8a](https://linux-hardware.org/?probe=3fbbac2c8a) | Oct 03, 2022 |
| ASUSTek       | 1225B                       | [9bb2d54ca7](https://linux-hardware.org/?probe=9bb2d54ca7) | Oct 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [64f2393fde](https://linux-hardware.org/?probe=64f2393fde) | Oct 03, 2022 |
| Toshiba       | Satellite L855              | [66e22581f7](https://linux-hardware.org/?probe=66e22581f7) | Oct 03, 2022 |
| Dell          | Precision 3570              | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Apple         | MacBookAir7,2               | [ae39aea3e9](https://linux-hardware.org/?probe=ae39aea3e9) | Oct 02, 2022 |
| Lenovo        | ThinkPad T460s 20F90060G... | [8d17d38142](https://linux-hardware.org/?probe=8d17d38142) | Oct 02, 2022 |
| ASUSTek       | X71Q                        | [830c8ab6d2](https://linux-hardware.org/?probe=830c8ab6d2) | Oct 02, 2022 |
| Toshiba       | Satellite L45               | [79ff097329](https://linux-hardware.org/?probe=79ff097329) | Oct 02, 2022 |
| Acer          | Aspire A715-41G             | [1a473e9809](https://linux-hardware.org/?probe=1a473e9809) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | [fbe1e53387](https://linux-hardware.org/?probe=fbe1e53387) | Oct 01, 2022 |
| Lenovo        | ThinkPad L380 20M5SSIN11    | [0cad79b1f7](https://linux-hardware.org/?probe=0cad79b1f7) | Sep 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [786e0c1f5d](https://linux-hardware.org/?probe=786e0c1f5d) | Sep 30, 2022 |
| HP            | Pavilion Notebook           | [ee72cbd627](https://linux-hardware.org/?probe=ee72cbd627) | Sep 29, 2022 |
| HP            | Compaq nx6325 (EY344EA#A... | [8808f98c62](https://linux-hardware.org/?probe=8808f98c62) | Sep 29, 2022 |
| ASUSTek       | N53SV                       | [6652e85ddd](https://linux-hardware.org/?probe=6652e85ddd) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [ca9c7bf57b](https://linux-hardware.org/?probe=ca9c7bf57b) | Sep 28, 2022 |
| Lenovo        | G50-70 20351                | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [56e06deea2](https://linux-hardware.org/?probe=56e06deea2) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [2d7ce63bce](https://linux-hardware.org/?probe=2d7ce63bce) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Dell          | Inspiron 15-3567            | [9ae6efbc0f](https://linux-hardware.org/?probe=9ae6efbc0f) | Sep 25, 2022 |
| HUAWEI        | RLEF-XX                     | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| Dell          | Inspiron 14 5425            | [209be443ac](https://linux-hardware.org/?probe=209be443ac) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [0adb7bc0b1](https://linux-hardware.org/?probe=0adb7bc0b1) | Sep 24, 2022 |
| VIT           | P2402                       | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| Samsung       | 550XBE/350XBE               | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Google        | Robo                        | [4772493ae3](https://linux-hardware.org/?probe=4772493ae3) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | [077c05c78d](https://linux-hardware.org/?probe=077c05c78d) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [f77dda559d](https://linux-hardware.org/?probe=f77dda559d) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [412296c83f](https://linux-hardware.org/?probe=412296c83f) | Sep 22, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [db6f733994](https://linux-hardware.org/?probe=db6f733994) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [21ba0d8f46](https://linux-hardware.org/?probe=21ba0d8f46) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [0c4627555a](https://linux-hardware.org/?probe=0c4627555a) | Sep 22, 2022 |
| Dell          | Inspiron 5537               | [7e3170527c](https://linux-hardware.org/?probe=7e3170527c) | Sep 22, 2022 |
| HP            | Notebook                    | [18b9221add](https://linux-hardware.org/?probe=18b9221add) | Sep 22, 2022 |
| Toshiba       | Satellite P745              | [963d04c729](https://linux-hardware.org/?probe=963d04c729) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | [630b3877c4](https://linux-hardware.org/?probe=630b3877c4) | Sep 22, 2022 |
| MSI           | GS60 2PE                    | [1aaaa99706](https://linux-hardware.org/?probe=1aaaa99706) | Sep 22, 2022 |
| HP            | Presario CQ57               | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Avell High... | B.ON                        | [95c7e35ef3](https://linux-hardware.org/?probe=95c7e35ef3) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | [41af175db4](https://linux-hardware.org/?probe=41af175db4) | Sep 21, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| Avell High... | B.ON                        | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| Dell          | Precision 7540              | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [0ada4a5b83](https://linux-hardware.org/?probe=0ada4a5b83) | Sep 20, 2022 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [5861c90514](https://linux-hardware.org/?probe=5861c90514) | Sep 20, 2022 |
| HP            | EliteBook 840 14 inch G9... | [450a86c900](https://linux-hardware.org/?probe=450a86c900) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad X260 20F5003EMB    | [302eacc4ff](https://linux-hardware.org/?probe=302eacc4ff) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad SL400 2743AQC      | [beb74c65cc](https://linux-hardware.org/?probe=beb74c65cc) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HP            | 15                          | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [0f049ae5d6](https://linux-hardware.org/?probe=0f049ae5d6) | Sep 19, 2022 |
| HP            | 15                          | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| HP            | G42                         | [3f584eb1af](https://linux-hardware.org/?probe=3f584eb1af) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Panasonic     | CF-53JAWZYDE                | [f8b1ca10d1](https://linux-hardware.org/?probe=f8b1ca10d1) | Sep 19, 2022 |
| Acer          | Aspire A315-23G             | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| Lenovo        | IdeaPad 720s-13ARR 81BR     | [fa45602fc5](https://linux-hardware.org/?probe=fa45602fc5) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [b94564300a](https://linux-hardware.org/?probe=b94564300a) | Sep 18, 2022 |
| Dell          | Latitude E6330              | [bbb0a5f1a1](https://linux-hardware.org/?probe=bbb0a5f1a1) | Sep 18, 2022 |
| Dell          | Latitude 3310               | [4de8502362](https://linux-hardware.org/?probe=4de8502362) | Sep 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [87c3b99589](https://linux-hardware.org/?probe=87c3b99589) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | [3de0a6e725](https://linux-hardware.org/?probe=3de0a6e725) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [6c5b0c0659](https://linux-hardware.org/?probe=6c5b0c0659) | Sep 17, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [1fa176a244](https://linux-hardware.org/?probe=1fa176a244) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [8c355ea88e](https://linux-hardware.org/?probe=8c355ea88e) | Sep 17, 2022 |
| HP            | Notebook                    | [9fcfcab16e](https://linux-hardware.org/?probe=9fcfcab16e) | Sep 17, 2022 |
| HP            | Unknown                     | [e87c925eb0](https://linux-hardware.org/?probe=e87c925eb0) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7e865e8b3f](https://linux-hardware.org/?probe=7e865e8b3f) | Sep 16, 2022 |
| Aquarius      | NS585                       | [84054aaa40](https://linux-hardware.org/?probe=84054aaa40) | Sep 16, 2022 |
| HP            | Stream Laptop 11-y0XX       | [b030fff6bb](https://linux-hardware.org/?probe=b030fff6bb) | Sep 16, 2022 |
| Aquarius      | NS585                       | [c4ad74720a](https://linux-hardware.org/?probe=c4ad74720a) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Aquarius      | NS585                       | [400485718e](https://linux-hardware.org/?probe=400485718e) | Sep 16, 2022 |
| Lenovo        | G50-45 80E3                 | [59c06bcd6f](https://linux-hardware.org/?probe=59c06bcd6f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [382325db11](https://linux-hardware.org/?probe=382325db11) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [a1f16914f7](https://linux-hardware.org/?probe=a1f16914f7) | Sep 16, 2022 |
| Aquarius      | NS585                       | [249e3f9a7c](https://linux-hardware.org/?probe=249e3f9a7c) | Sep 16, 2022 |
| Acer          | Aspire A315-23G             | [283a38bb80](https://linux-hardware.org/?probe=283a38bb80) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [14cbf91f0c](https://linux-hardware.org/?probe=14cbf91f0c) | Sep 15, 2022 |
| Google        | Stout                       | [82b966b9ad](https://linux-hardware.org/?probe=82b966b9ad) | Sep 15, 2022 |
| Aquarius      | NS585                       | [e86929e9a3](https://linux-hardware.org/?probe=e86929e9a3) | Sep 15, 2022 |
| Aquarius      | NS585                       | [a1568949cd](https://linux-hardware.org/?probe=a1568949cd) | Sep 15, 2022 |
| Aquarius      | NS585                       | [feedc8a0ba](https://linux-hardware.org/?probe=feedc8a0ba) | Sep 15, 2022 |
| Aquarius      | NS585                       | [eb2906fdc5](https://linux-hardware.org/?probe=eb2906fdc5) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3bf32bc004](https://linux-hardware.org/?probe=3bf32bc004) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | [aa5d8a2fc6](https://linux-hardware.org/?probe=aa5d8a2fc6) | Sep 15, 2022 |
| Positivo      | Mobile                      | [f0f7335929](https://linux-hardware.org/?probe=f0f7335929) | Sep 15, 2022 |
| INFINITY      | Unknown                     | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [5bdc2b7041](https://linux-hardware.org/?probe=5bdc2b7041) | Sep 14, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| Google        | Terra                       | [9dae30736d](https://linux-hardware.org/?probe=9dae30736d) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8fb883495e](https://linux-hardware.org/?probe=8fb883495e) | Sep 14, 2022 |
| Aquarius      | NS585                       | [2c51e9e9c2](https://linux-hardware.org/?probe=2c51e9e9c2) | Sep 14, 2022 |
| Aquarius      | NS585                       | [54a3f9eec9](https://linux-hardware.org/?probe=54a3f9eec9) | Sep 14, 2022 |
| Aquarius      | NS585                       | [3760a35f01](https://linux-hardware.org/?probe=3760a35f01) | Sep 14, 2022 |
| Dell          | Precision 3571              | [72e1a27ea7](https://linux-hardware.org/?probe=72e1a27ea7) | Sep 14, 2022 |
| Aquarius      | NS585                       | [7927c44ef0](https://linux-hardware.org/?probe=7927c44ef0) | Sep 14, 2022 |
| Aquarius      | NS585                       | [eaa0e46c9f](https://linux-hardware.org/?probe=eaa0e46c9f) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8935b3f204](https://linux-hardware.org/?probe=8935b3f204) | Sep 14, 2022 |
| Aquarius      | NS585                       | [a904acc9e9](https://linux-hardware.org/?probe=a904acc9e9) | Sep 14, 2022 |
| Aquarius      | NS585                       | [7f883700cf](https://linux-hardware.org/?probe=7f883700cf) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8ef03a6208](https://linux-hardware.org/?probe=8ef03a6208) | Sep 14, 2022 |
| Aquarius      | NS585                       | [c3f844b853](https://linux-hardware.org/?probe=c3f844b853) | Sep 14, 2022 |
| Aquarius      | NS585                       | [0a77a87395](https://linux-hardware.org/?probe=0a77a87395) | Sep 14, 2022 |
| Aquarius      | NS585                       | [344bf802ef](https://linux-hardware.org/?probe=344bf802ef) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | [6be4965b4d](https://linux-hardware.org/?probe=6be4965b4d) | Sep 14, 2022 |
| Aquarius      | NS585                       | [f627c1d051](https://linux-hardware.org/?probe=f627c1d051) | Sep 14, 2022 |
| Aquarius      | NS585                       | [67eca2e394](https://linux-hardware.org/?probe=67eca2e394) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8c8644f284](https://linux-hardware.org/?probe=8c8644f284) | Sep 14, 2022 |
| Aquarius      | NS585                       | [09ca233ab5](https://linux-hardware.org/?probe=09ca233ab5) | Sep 14, 2022 |
| Dell          | Latitude E7250              | [80a2e50cfc](https://linux-hardware.org/?probe=80a2e50cfc) | Sep 14, 2022 |
| Aquarius      | NS585                       | [df1a5c5ca1](https://linux-hardware.org/?probe=df1a5c5ca1) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | [b8665b7aed](https://linux-hardware.org/?probe=b8665b7aed) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | [e65b9d439e](https://linux-hardware.org/?probe=e65b9d439e) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | [22c2adf69b](https://linux-hardware.org/?probe=22c2adf69b) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [c8994c7912](https://linux-hardware.org/?probe=c8994c7912) | Sep 14, 2022 |
| Dell          | Inspiron 15-7568            | [c3b834caec](https://linux-hardware.org/?probe=c3b834caec) | Sep 14, 2022 |
| Google        | Terra                       | [a7150f06c7](https://linux-hardware.org/?probe=a7150f06c7) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| Aquarius      | NS585                       | [f76497447f](https://linux-hardware.org/?probe=f76497447f) | Sep 13, 2022 |
| Aquarius      | NS585                       | [042a81998b](https://linux-hardware.org/?probe=042a81998b) | Sep 13, 2022 |
| Aquarius      | NS585                       | [e5078cd5f4](https://linux-hardware.org/?probe=e5078cd5f4) | Sep 13, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7acd0e62aa](https://linux-hardware.org/?probe=7acd0e62aa) | Sep 12, 2022 |
| Google        | Terra                       | [6b591d8c39](https://linux-hardware.org/?probe=6b591d8c39) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| Google        | Reks                        | [28f0932e1a](https://linux-hardware.org/?probe=28f0932e1a) | Sep 12, 2022 |
| Lenovo        | ThinkPad X240 20AL00ETGE    | [95a3df06c9](https://linux-hardware.org/?probe=95a3df06c9) | Sep 12, 2022 |
| MSI           | Modern 15 A11M              | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| MSI           | GS60 2PE                    | [0164cbee91](https://linux-hardware.org/?probe=0164cbee91) | Sep 12, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [3a6e62d846](https://linux-hardware.org/?probe=3a6e62d846) | Sep 12, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c18f89b2bb](https://linux-hardware.org/?probe=c18f89b2bb) | Sep 11, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [cd49377ddf](https://linux-hardware.org/?probe=cd49377ddf) | Sep 11, 2022 |
| HP            | G42                         | [092b9e2c38](https://linux-hardware.org/?probe=092b9e2c38) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | [cca78f4488](https://linux-hardware.org/?probe=cca78f4488) | Sep 11, 2022 |
| Lenovo        | ThinkPad L460 20FVS1BC0S    | [e668edf31d](https://linux-hardware.org/?probe=e668edf31d) | Sep 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5a7c8dfacf](https://linux-hardware.org/?probe=5a7c8dfacf) | Sep 10, 2022 |
| Google        | Treeya                      | [d7a00caa63](https://linux-hardware.org/?probe=d7a00caa63) | Sep 10, 2022 |
| Lenovo        | G50-45 80E3                 | [2f4b4e4203](https://linux-hardware.org/?probe=2f4b4e4203) | Sep 10, 2022 |
| ASUSTek       | X200CA                      | [70c2613095](https://linux-hardware.org/?probe=70c2613095) | Sep 09, 2022 |
| Acer          | AO532h                      | [3ea8a4ba38](https://linux-hardware.org/?probe=3ea8a4ba38) | Sep 09, 2022 |
| Toshiba       | Satellite L40               | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Dell          | Latitude E6330              | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [92ae6811fa](https://linux-hardware.org/?probe=92ae6811fa) | Sep 09, 2022 |
| HP            | Compaq 8510w                | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [d37b0f4483](https://linux-hardware.org/?probe=d37b0f4483) | Sep 08, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [c8f2e1da45](https://linux-hardware.org/?probe=c8f2e1da45) | Sep 08, 2022 |
| Google        | Reks                        | [a171b11595](https://linux-hardware.org/?probe=a171b11595) | Sep 08, 2022 |
| ASUSTek       | UX430UAR                    | [478d0564a6](https://linux-hardware.org/?probe=478d0564a6) | Sep 08, 2022 |
| HP            | ProBook 440 G7              | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| ASUSTek       | X441NA                      | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| Acer          | Aspire 5738                 | [141712c674](https://linux-hardware.org/?probe=141712c674) | Sep 07, 2022 |
| Lenovo        | B570e 521524G               | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| HP            | Laptop 17-ca0xxx            | [c65eb0b5c8](https://linux-hardware.org/?probe=c65eb0b5c8) | Sep 07, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [044bee5e0c](https://linux-hardware.org/?probe=044bee5e0c) | Sep 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [c0e98bf9e5](https://linux-hardware.org/?probe=c0e98bf9e5) | Sep 06, 2022 |
| Aquarius      | NS585                       | [74e50c07d8](https://linux-hardware.org/?probe=74e50c07d8) | Sep 06, 2022 |
| HP            | ENVY 17                     | [63411dc061](https://linux-hardware.org/?probe=63411dc061) | Sep 06, 2022 |
| Lenovo        | ThinkPad P51s 20HB000URT    | [8214e1ba30](https://linux-hardware.org/?probe=8214e1ba30) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | [fefa3f4935](https://linux-hardware.org/?probe=fefa3f4935) | Sep 06, 2022 |
| HP            | ProBook 640 G4              | [b76e5a62e8](https://linux-hardware.org/?probe=b76e5a62e8) | Sep 06, 2022 |
| Dell          | Latitude 5530               | [4a2fb0c4c2](https://linux-hardware.org/?probe=4a2fb0c4c2) | Sep 06, 2022 |
| Dell          | Latitude 5530               | [a0896a063c](https://linux-hardware.org/?probe=a0896a063c) | Sep 06, 2022 |
| ASUSTek       | X555LAB                     | [b10937286d](https://linux-hardware.org/?probe=b10937286d) | Sep 06, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [6bd37547d3](https://linux-hardware.org/?probe=6bd37547d3) | Sep 05, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [4c68e17f1a](https://linux-hardware.org/?probe=4c68e17f1a) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e6117fb016](https://linux-hardware.org/?probe=e6117fb016) | Sep 05, 2022 |
| Dell          | Vostro 15 5510              | [beb1aeb4ad](https://linux-hardware.org/?probe=beb1aeb4ad) | Sep 05, 2022 |
| Acer          | Aspire A517-52G             | [c1709e40b7](https://linux-hardware.org/?probe=c1709e40b7) | Sep 05, 2022 |
| Unknown       | Unknown                     | [efb1e9883d](https://linux-hardware.org/?probe=efb1e9883d) | Sep 05, 2022 |
| Unknown       | Unknown                     | [20178af23f](https://linux-hardware.org/?probe=20178af23f) | Sep 05, 2022 |
| Dell          | Latitude E6330              | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [ea93dfd855](https://linux-hardware.org/?probe=ea93dfd855) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 232438J       | [dca0e2fa77](https://linux-hardware.org/?probe=dca0e2fa77) | Sep 04, 2022 |
| HP            | Compaq 8510w                | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| PC Special... | 14 Fusion IV                | [dd9ed93b55](https://linux-hardware.org/?probe=dd9ed93b55) | Sep 03, 2022 |
| HP            | Compaq 6910p                | [0165c7d3c6](https://linux-hardware.org/?probe=0165c7d3c6) | Sep 03, 2022 |
| Aquarius      | NS585                       | [b11a34556d](https://linux-hardware.org/?probe=b11a34556d) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Acer          | Aspire A315-23G             | [9a2200f8f8](https://linux-hardware.org/?probe=9a2200f8f8) | Sep 03, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c8bf09dd8d](https://linux-hardware.org/?probe=c8bf09dd8d) | Sep 02, 2022 |
| Aquarius      | NS585                       | [86de3c4954](https://linux-hardware.org/?probe=86de3c4954) | Sep 02, 2022 |
| Dell          | XPS 13 9350                 | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Google        | Enguarde                    | [50369de0be](https://linux-hardware.org/?probe=50369de0be) | Sep 01, 2022 |
| Dell          | Latitude E6330              | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| MSI           | Katana GF66 12UC            | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| Google        | Enguarde                    | [b59a9615cd](https://linux-hardware.org/?probe=b59a9615cd) | Sep 01, 2022 |
| Google        | Enguarde                    | [7acc7436b0](https://linux-hardware.org/?probe=7acc7436b0) | Sep 01, 2022 |
| Google        | Enguarde                    | [671a062f6e](https://linux-hardware.org/?probe=671a062f6e) | Sep 01, 2022 |
| Google        | Enguarde                    | [baabafd42b](https://linux-hardware.org/?probe=baabafd42b) | Sep 01, 2022 |
| Google        | Enguarde                    | [4c1595c83e](https://linux-hardware.org/?probe=4c1595c83e) | Sep 01, 2022 |
| Google        | Enguarde                    | [bb6b28b279](https://linux-hardware.org/?probe=bb6b28b279) | Sep 01, 2022 |
| Google        | Terra                       | [b7940ab738](https://linux-hardware.org/?probe=b7940ab738) | Sep 01, 2022 |
| Google        | Enguarde                    | [0cbe57b975](https://linux-hardware.org/?probe=0cbe57b975) | Sep 01, 2022 |
| Google        | Enguarde                    | [9f20842cc5](https://linux-hardware.org/?probe=9f20842cc5) | Sep 01, 2022 |
| Google        | Enguarde                    | [06969489cc](https://linux-hardware.org/?probe=06969489cc) | Sep 01, 2022 |
| Google        | Enguarde                    | [2b4231258e](https://linux-hardware.org/?probe=2b4231258e) | Sep 01, 2022 |
| Google        | Enguarde                    | [1a0596c60d](https://linux-hardware.org/?probe=1a0596c60d) | Sep 01, 2022 |
| Google        | Enguarde                    | [4dfdb5e364](https://linux-hardware.org/?probe=4dfdb5e364) | Sep 01, 2022 |
| Google        | Enguarde                    | [c6db81251c](https://linux-hardware.org/?probe=c6db81251c) | Sep 01, 2022 |
| Google        | Enguarde                    | [05f112ddb7](https://linux-hardware.org/?probe=05f112ddb7) | Sep 01, 2022 |
| Dell          | Vostro 15 5510              | [e14cc69370](https://linux-hardware.org/?probe=e14cc69370) | Sep 01, 2022 |
| ASUSTek       | K50IJ                       | [10dd5d1e15](https://linux-hardware.org/?probe=10dd5d1e15) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| ASUSTek       | UX550VD                     | [a43d53b3b7](https://linux-hardware.org/?probe=a43d53b3b7) | Sep 01, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [7277e72eb4](https://linux-hardware.org/?probe=7277e72eb4) | Aug 31, 2022 |
| Dell          | Latitude E6330              | [b5766d41fa](https://linux-hardware.org/?probe=b5766d41fa) | Aug 31, 2022 |
| HP            | 250 G8 Notebook PC          | [c0a39342c3](https://linux-hardware.org/?probe=c0a39342c3) | Aug 31, 2022 |
| HP            | Compaq 8510w                | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| HP            | Compaq nc6400 (RU626ET#A... | [e94cb8e943](https://linux-hardware.org/?probe=e94cb8e943) | Aug 30, 2022 |
| Google        | Reks                        | [71f6228c3d](https://linux-hardware.org/?probe=71f6228c3d) | Aug 30, 2022 |
| Google        | Reks                        | [48174b01b3](https://linux-hardware.org/?probe=48174b01b3) | Aug 30, 2022 |
| ASUSTek       | X550CC                      | [f9a9be3a35](https://linux-hardware.org/?probe=f9a9be3a35) | Aug 30, 2022 |
| Google        | Terra                       | [25f50ae6d9](https://linux-hardware.org/?probe=25f50ae6d9) | Aug 30, 2022 |
| Google        | Reks                        | [e768a1940e](https://linux-hardware.org/?probe=e768a1940e) | Aug 30, 2022 |
| Lenovo        | ThinkPad L490 20Q5001YPB    | [daae538154](https://linux-hardware.org/?probe=daae538154) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [30b240a3fe](https://linux-hardware.org/?probe=30b240a3fe) | Aug 29, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [ddc175428b](https://linux-hardware.org/?probe=ddc175428b) | Aug 29, 2022 |
| Dell          | Latitude 5590               | [e06f40dae9](https://linux-hardware.org/?probe=e06f40dae9) | Aug 29, 2022 |
| Acer          | TravelMate P215-53          | [4ba2e9fbba](https://linux-hardware.org/?probe=4ba2e9fbba) | Aug 29, 2022 |
| ASUSTek       | K55VM                       | [ec5806d544](https://linux-hardware.org/?probe=ec5806d544) | Aug 29, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| Dell          | Latitude 5420               | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [a10cbdb73b](https://linux-hardware.org/?probe=a10cbdb73b) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [562d827323](https://linux-hardware.org/?probe=562d827323) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c155c4b324](https://linux-hardware.org/?probe=c155c4b324) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8231da35ed](https://linux-hardware.org/?probe=8231da35ed) | Aug 27, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2KU0... | [6500c142f5](https://linux-hardware.org/?probe=6500c142f5) | Aug 27, 2022 |
| Medion        | Akoya P2213T                | [c8d10c3b3f](https://linux-hardware.org/?probe=c8d10c3b3f) | Aug 27, 2022 |
| Google        | Terra                       | [717b3cc17f](https://linux-hardware.org/?probe=717b3cc17f) | Aug 26, 2022 |
| Google        | Terra                       | [f9856d813e](https://linux-hardware.org/?probe=f9856d813e) | Aug 26, 2022 |
| ASUSTek       | X455LD                      | [5351e31366](https://linux-hardware.org/?probe=5351e31366) | Aug 26, 2022 |
| Lenovo        | ThinkPad T590 20N4001NUS    | [479ef1a89c](https://linux-hardware.org/?probe=479ef1a89c) | Aug 26, 2022 |
| ASUSTek       | M70Vn                       | [2e84d460f5](https://linux-hardware.org/?probe=2e84d460f5) | Aug 26, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [73c598ebe7](https://linux-hardware.org/?probe=73c598ebe7) | Aug 26, 2022 |
| Lenovo        | ThinkPad T400 2768BM2       | [f2d91055c9](https://linux-hardware.org/?probe=f2d91055c9) | Aug 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [a624a45cda](https://linux-hardware.org/?probe=a624a45cda) | Aug 26, 2022 |
| HP            | ProBook 450 G6              | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [843ee79f1b](https://linux-hardware.org/?probe=843ee79f1b) | Aug 25, 2022 |
| Google        | Terra                       | [72965945d5](https://linux-hardware.org/?probe=72965945d5) | Aug 25, 2022 |
| Google        | Terra                       | [78436fd3bf](https://linux-hardware.org/?probe=78436fd3bf) | Aug 25, 2022 |
| Apple         | MacBookAir7,2               | [b2dc63405c](https://linux-hardware.org/?probe=b2dc63405c) | Aug 25, 2022 |
| Dell          | Inspiron 600m               | [6acc515c79](https://linux-hardware.org/?probe=6acc515c79) | Aug 25, 2022 |
| Dell          | Latitude 3570               | [287cfa2ce8](https://linux-hardware.org/?probe=287cfa2ce8) | Aug 25, 2022 |
| Lenovo        | ThinkPad E490 20N8001EUS    | [1620f0e5ff](https://linux-hardware.org/?probe=1620f0e5ff) | Aug 24, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| Dell          | XPS 15 9500                 | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| HP            | Laptop 14-dq2xxx            | [bc4f5f8811](https://linux-hardware.org/?probe=bc4f5f8811) | Aug 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [8b346ab142](https://linux-hardware.org/?probe=8b346ab142) | Aug 24, 2022 |
| Google        | Reks                        | [043b648dc5](https://linux-hardware.org/?probe=043b648dc5) | Aug 23, 2022 |
| Google        | Terra                       | [b720f3ca23](https://linux-hardware.org/?probe=b720f3ca23) | Aug 23, 2022 |
| Google        | Terra                       | [0fd5baced8](https://linux-hardware.org/?probe=0fd5baced8) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | [dfbced302f](https://linux-hardware.org/?probe=dfbced302f) | Aug 23, 2022 |
| Google        | Terra                       | [92efdef775](https://linux-hardware.org/?probe=92efdef775) | Aug 23, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [e5d3453caa](https://linux-hardware.org/?probe=e5d3453caa) | Aug 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | [91f1311a5f](https://linux-hardware.org/?probe=91f1311a5f) | Aug 23, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [801a4be04d](https://linux-hardware.org/?probe=801a4be04d) | Aug 23, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [2ac415ca87](https://linux-hardware.org/?probe=2ac415ca87) | Aug 23, 2022 |
| Dell          | Vostro 15 5510              | [3224d8bdcc](https://linux-hardware.org/?probe=3224d8bdcc) | Aug 23, 2022 |
| VANT          | MOOVE3-15                   | [854b7f42d4](https://linux-hardware.org/?probe=854b7f42d4) | Aug 22, 2022 |
| Acer          | Aspire 5742                 | [6692313edb](https://linux-hardware.org/?probe=6692313edb) | Aug 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [2431fa78d1](https://linux-hardware.org/?probe=2431fa78d1) | Aug 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [532e1358b6](https://linux-hardware.org/?probe=532e1358b6) | Aug 21, 2022 |
| Dell          | XPS 15 9550                 | [8ab7fcb6ff](https://linux-hardware.org/?probe=8ab7fcb6ff) | Aug 21, 2022 |
| Dell          | Precision 7720              | [60ad0b7b3d](https://linux-hardware.org/?probe=60ad0b7b3d) | Aug 21, 2022 |
| Positivo      | Mobile                      | [8678ddf7ac](https://linux-hardware.org/?probe=8678ddf7ac) | Aug 20, 2022 |
| Positivo      | Mobile                      | [d1cf6b8c9e](https://linux-hardware.org/?probe=d1cf6b8c9e) | Aug 20, 2022 |
| VANT          | MOOVE3-15                   | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| Dell          | Vostro 15 5510              | [9f5e59e0b9](https://linux-hardware.org/?probe=9f5e59e0b9) | Aug 20, 2022 |
| MSI           | GF75 Thin 10SCSXR           | [095c130069](https://linux-hardware.org/?probe=095c130069) | Aug 20, 2022 |
| HP            | 620                         | [d3b1eb8b4e](https://linux-hardware.org/?probe=d3b1eb8b4e) | Aug 20, 2022 |
| HP            | Laptop 17-cp0xxx            | [6ba8616656](https://linux-hardware.org/?probe=6ba8616656) | Aug 20, 2022 |
| Google        | Reks                        | [e5cde69ff7](https://linux-hardware.org/?probe=e5cde69ff7) | Aug 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [9e72f598eb](https://linux-hardware.org/?probe=9e72f598eb) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [45bfdfa985](https://linux-hardware.org/?probe=45bfdfa985) | Aug 19, 2022 |
| HP            | 620                         | [259635c419](https://linux-hardware.org/?probe=259635c419) | Aug 19, 2022 |
| ICL           | N7x0WU                      | [7b9c4ad6b1](https://linux-hardware.org/?probe=7b9c4ad6b1) | Aug 19, 2022 |
| HP            | Compaq nx7300 (RH678EA#A... | [6fc01cef23](https://linux-hardware.org/?probe=6fc01cef23) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [e6003f393e](https://linux-hardware.org/?probe=e6003f393e) | Aug 19, 2022 |
| Dell          | Latitude 5500               | [1c7c8639aa](https://linux-hardware.org/?probe=1c7c8639aa) | Aug 19, 2022 |
| Google        | Reks                        | [d09d250717](https://linux-hardware.org/?probe=d09d250717) | Aug 18, 2022 |
| Google        | Terra                       | [4eca7693ab](https://linux-hardware.org/?probe=4eca7693ab) | Aug 18, 2022 |
| Google        | Reks                        | [9fc034e8a0](https://linux-hardware.org/?probe=9fc034e8a0) | Aug 18, 2022 |
| Google        | Terra                       | [aabdca917b](https://linux-hardware.org/?probe=aabdca917b) | Aug 18, 2022 |
| Acer          | TravelMate 5620             | [5b1df1054c](https://linux-hardware.org/?probe=5b1df1054c) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Dell          | Vostro 3405                 | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Acer          | TravelMate 5620             | [cdb6e6d5d6](https://linux-hardware.org/?probe=cdb6e6d5d6) | Aug 17, 2022 |
| ASUSTek       | K70IJ                       | [99bb1459e7](https://linux-hardware.org/?probe=99bb1459e7) | Aug 17, 2022 |
| Shuttle       | DS437                       | [21e0ca6a77](https://linux-hardware.org/?probe=21e0ca6a77) | Aug 17, 2022 |
| Dell          | Precision M6600             | [2e1eaedbc4](https://linux-hardware.org/?probe=2e1eaedbc4) | Aug 17, 2022 |
| HP            | Laptop 14-dq2xxx            | [9cefc23bb3](https://linux-hardware.org/?probe=9cefc23bb3) | Aug 17, 2022 |
| HP            | 255 G5 Notebook PC          | [fdeea5b020](https://linux-hardware.org/?probe=fdeea5b020) | Aug 16, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [74e8d1be5b](https://linux-hardware.org/?probe=74e8d1be5b) | Aug 16, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [d04d18b241](https://linux-hardware.org/?probe=d04d18b241) | Aug 16, 2022 |
| Dell          | Inspiron 5547               | [84a3ba511d](https://linux-hardware.org/?probe=84a3ba511d) | Aug 16, 2022 |
| PCBOX         | Kant                        | [1b5c160d93](https://linux-hardware.org/?probe=1b5c160d93) | Aug 16, 2022 |
| Google        | Terra                       | [8c5b7a9814](https://linux-hardware.org/?probe=8c5b7a9814) | Aug 15, 2022 |
| Google        | Terra                       | [43c28dadff](https://linux-hardware.org/?probe=43c28dadff) | Aug 15, 2022 |
| Google        | Terra                       | [98b7a9a377](https://linux-hardware.org/?probe=98b7a9a377) | Aug 15, 2022 |
| Google        | Terra                       | [3bfcb2b1b4](https://linux-hardware.org/?probe=3bfcb2b1b4) | Aug 15, 2022 |
| Dell          | Latitude 5420               | [0dec3e9676](https://linux-hardware.org/?probe=0dec3e9676) | Aug 15, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Toshiba       | Satellite P50-B-103         | [39da8f51fe](https://linux-hardware.org/?probe=39da8f51fe) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | [eeed6b3d08](https://linux-hardware.org/?probe=eeed6b3d08) | Aug 14, 2022 |
| Dell          | Latitude E5430 vPro         | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| Acer          | Aspire A315-23G             | [cdba281a27](https://linux-hardware.org/?probe=cdba281a27) | Aug 13, 2022 |
| Apple         | MacBookPro12,1              | [8b417889e1](https://linux-hardware.org/?probe=8b417889e1) | Aug 13, 2022 |
| HP            | Presario CQ56               | [48dfc2da91](https://linux-hardware.org/?probe=48dfc2da91) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | [188bfa465d](https://linux-hardware.org/?probe=188bfa465d) | Aug 13, 2022 |
| Dell          | Latitude E6330              | [b48c021700](https://linux-hardware.org/?probe=b48c021700) | Aug 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [94eb72e4ac](https://linux-hardware.org/?probe=94eb72e4ac) | Aug 13, 2022 |
| HP            | Pavilion Notebook           | [3dd4d44be4](https://linux-hardware.org/?probe=3dd4d44be4) | Aug 12, 2022 |
| Acer          | Aspire A114-33              | [471a1ec71e](https://linux-hardware.org/?probe=471a1ec71e) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [ed37ad46b6](https://linux-hardware.org/?probe=ed37ad46b6) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [2fab557514](https://linux-hardware.org/?probe=2fab557514) | Aug 12, 2022 |
| Dell          | XPS 13 9350                 | [6f828c5743](https://linux-hardware.org/?probe=6f828c5743) | Aug 12, 2022 |
| Apple         | MacBookAir7,2               | [c38e80ade4](https://linux-hardware.org/?probe=c38e80ade4) | Aug 11, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [efd4ec3ee7](https://linux-hardware.org/?probe=efd4ec3ee7) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [d64d35a05d](https://linux-hardware.org/?probe=d64d35a05d) | Aug 11, 2022 |
| Dell          | Latitude 6430U              | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [23b946fc6d](https://linux-hardware.org/?probe=23b946fc6d) | Aug 11, 2022 |
| Toshiba       | Satellite M645              | [9fa1e00c24](https://linux-hardware.org/?probe=9fa1e00c24) | Aug 10, 2022 |
| Toshiba       | TECRA R950                  | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| ASUSTek       | X751LJ                      | [5c3767ccc2](https://linux-hardware.org/?probe=5c3767ccc2) | Aug 10, 2022 |
| Dell          | Latitude E6420              | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| GPU Compan... | GWTC116-2                   | [b92ffbefad](https://linux-hardware.org/?probe=b92ffbefad) | Aug 09, 2022 |
| ASUSTek       | X751LJ                      | [e35689c8f1](https://linux-hardware.org/?probe=e35689c8f1) | Aug 09, 2022 |
| Acer          | Aspire A515-56              | [21fdf57c32](https://linux-hardware.org/?probe=21fdf57c32) | Aug 09, 2022 |
| HP            | EliteBook 725 G3            | [7e36a68724](https://linux-hardware.org/?probe=7e36a68724) | Aug 09, 2022 |
| NVN-ED01      | Unknown                     | [0a677cad6c](https://linux-hardware.org/?probe=0a677cad6c) | Aug 09, 2022 |
| Alienware     | m15 R6                      | [675208eaec](https://linux-hardware.org/?probe=675208eaec) | Aug 09, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [b8ae818291](https://linux-hardware.org/?probe=b8ae818291) | Aug 08, 2022 |
| Dell          | Latitude E7450              | [f2d8a030f4](https://linux-hardware.org/?probe=f2d8a030f4) | Aug 08, 2022 |
| HP            | EliteBook 725 G3            | [e48eff307c](https://linux-hardware.org/?probe=e48eff307c) | Aug 08, 2022 |
| Acer          | Aspire A315-23G             | [46b74e61f0](https://linux-hardware.org/?probe=46b74e61f0) | Aug 08, 2022 |
| Dell          | Latitude E6430              | [17d0fce9e5](https://linux-hardware.org/?probe=17d0fce9e5) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | [b1420b630f](https://linux-hardware.org/?probe=b1420b630f) | Aug 07, 2022 |
| Acer          | Aspire 5738                 | [31d08ab231](https://linux-hardware.org/?probe=31d08ab231) | Aug 07, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [19b3f7fe4b](https://linux-hardware.org/?probe=19b3f7fe4b) | Aug 07, 2022 |
| Dell          | Precision 7720              | [db2f868372](https://linux-hardware.org/?probe=db2f868372) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0564acfb6c](https://linux-hardware.org/?probe=0564acfb6c) | Aug 07, 2022 |
| SANTECH       | NHx0DB,DE                   | [1eba623e90](https://linux-hardware.org/?probe=1eba623e90) | Aug 06, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [53c997fe1f](https://linux-hardware.org/?probe=53c997fe1f) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d5786b75a3](https://linux-hardware.org/?probe=d5786b75a3) | Aug 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [24d8a6228c](https://linux-hardware.org/?probe=24d8a6228c) | Aug 05, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [83c6e58e51](https://linux-hardware.org/?probe=83c6e58e51) | Aug 05, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d12e654f35](https://linux-hardware.org/?probe=d12e654f35) | Aug 05, 2022 |
| HP            | ProBook 430 G5              | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | [9d032c38b4](https://linux-hardware.org/?probe=9d032c38b4) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | [433126127b](https://linux-hardware.org/?probe=433126127b) | Aug 05, 2022 |
| Acer          | Aspire 5315                 | [7be46d4930](https://linux-hardware.org/?probe=7be46d4930) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [87d90381e1](https://linux-hardware.org/?probe=87d90381e1) | Aug 04, 2022 |
| HP            | EliteBook 8460p             | [7948505598](https://linux-hardware.org/?probe=7948505598) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e74155922c](https://linux-hardware.org/?probe=e74155922c) | Aug 04, 2022 |
| Acer          | AO532h                      | [9a35f25fba](https://linux-hardware.org/?probe=9a35f25fba) | Aug 04, 2022 |
| Acer          | Aspire A315-23G             | [52e4d5e94f](https://linux-hardware.org/?probe=52e4d5e94f) | Aug 03, 2022 |
| Google        | Droid                       | [15d4518ba0](https://linux-hardware.org/?probe=15d4518ba0) | Aug 03, 2022 |
| ASUSTek       | X756UQK                     | [97b2316a06](https://linux-hardware.org/?probe=97b2316a06) | Aug 03, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [94ccc2e14f](https://linux-hardware.org/?probe=94ccc2e14f) | Aug 03, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [0bf365f767](https://linux-hardware.org/?probe=0bf365f767) | Aug 02, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [e586e6ee53](https://linux-hardware.org/?probe=e586e6ee53) | Aug 02, 2022 |
| HP            | 255 G3                      | [46ad188006](https://linux-hardware.org/?probe=46ad188006) | Aug 02, 2022 |
| HUAWEI        | CREM-WXX9                   | [9e48213e39](https://linux-hardware.org/?probe=9e48213e39) | Aug 02, 2022 |
| HUAWEI        | CREM-WXX9                   | [2efb41280c](https://linux-hardware.org/?probe=2efb41280c) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5d4fdde00](https://linux-hardware.org/?probe=f5d4fdde00) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| Dell          | Inspiron 13-7378            | [c08447d945](https://linux-hardware.org/?probe=c08447d945) | Aug 01, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [ae2fa8b811](https://linux-hardware.org/?probe=ae2fa8b811) | Aug 01, 2022 |
| Dell          | Latitude 7420               | [d498af2db5](https://linux-hardware.org/?probe=d498af2db5) | Aug 01, 2022 |
| Toshiba       | TECRA Z40-C                 | [9612659f60](https://linux-hardware.org/?probe=9612659f60) | Aug 01, 2022 |
| Apple         | MacBookPro11,5              | [24ccaddbf8](https://linux-hardware.org/?probe=24ccaddbf8) | Jul 31, 2022 |
| HP            | ProBook 4310s               | [d15b493637](https://linux-hardware.org/?probe=d15b493637) | Jul 31, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [9b362907fc](https://linux-hardware.org/?probe=9b362907fc) | Jul 30, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [61aed5ab55](https://linux-hardware.org/?probe=61aed5ab55) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | [1b94bd5797](https://linux-hardware.org/?probe=1b94bd5797) | Jul 29, 2022 |
| Acer          | AO756                       | [8203ac54d7](https://linux-hardware.org/?probe=8203ac54d7) | Jul 29, 2022 |
| ASUSTek       | GL553VE                     | [0bbcd152c5](https://linux-hardware.org/?probe=0bbcd152c5) | Jul 29, 2022 |
| Samsung       | R505                        | [4f92cf3c93](https://linux-hardware.org/?probe=4f92cf3c93) | Jul 29, 2022 |
| Lenovo        | ThinkPad L480 20LS002CPB    | [35764371d6](https://linux-hardware.org/?probe=35764371d6) | Jul 29, 2022 |
| Dell          | Latitude E5500              | [ba214335da](https://linux-hardware.org/?probe=ba214335da) | Jul 28, 2022 |
| HP            | Compaq 8510p                | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Lenovo        | S21e-20 80M4                | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [87f0eb95eb](https://linux-hardware.org/?probe=87f0eb95eb) | Jul 27, 2022 |
| HP            | Stream Notebook PC 11       | [e3c8a52e5b](https://linux-hardware.org/?probe=e3c8a52e5b) | Jul 27, 2022 |
| Acer          | Aspire A515-43              | [d378021961](https://linux-hardware.org/?probe=d378021961) | Jul 26, 2022 |
| ASUSTek       | ZenBook UX325UA             | [587ea51239](https://linux-hardware.org/?probe=587ea51239) | Jul 26, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [8aa5207a61](https://linux-hardware.org/?probe=8aa5207a61) | Jul 26, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [fc5bf3cb22](https://linux-hardware.org/?probe=fc5bf3cb22) | Jul 26, 2022 |
| HONOR         | BBR-WAX9                    | [afe7a4d56a](https://linux-hardware.org/?probe=afe7a4d56a) | Jul 26, 2022 |
| Lenovo        | G410 20237                  | [c23a040e55](https://linux-hardware.org/?probe=c23a040e55) | Jul 25, 2022 |
| HP            | Notebook                    | [fdc7478b06](https://linux-hardware.org/?probe=fdc7478b06) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bf2cecb453](https://linux-hardware.org/?probe=bf2cecb453) | Jul 25, 2022 |
| Acer          | Aspire A315-23G             | [df57effbc5](https://linux-hardware.org/?probe=df57effbc5) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e2a1804b90](https://linux-hardware.org/?probe=e2a1804b90) | Jul 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [04737cec4e](https://linux-hardware.org/?probe=04737cec4e) | Jul 24, 2022 |
| Dell          | Latitude E5430 non-vPro     | [f8808faaf0](https://linux-hardware.org/?probe=f8808faaf0) | Jul 24, 2022 |
| HP            | ProBook 450 G3              | [288db20204](https://linux-hardware.org/?probe=288db20204) | Jul 23, 2022 |
| ASUSTek       | X541UVK                     | [fb1513d31e](https://linux-hardware.org/?probe=fb1513d31e) | Jul 21, 2022 |
| Dell          | Latitude 5420               | [51cf24b119](https://linux-hardware.org/?probe=51cf24b119) | Jul 21, 2022 |
| HP            | ZBook 15 G3                 | [758ce4f6b4](https://linux-hardware.org/?probe=758ce4f6b4) | Jul 21, 2022 |
| Unknown       | W1415A                      | [3a2f4f9848](https://linux-hardware.org/?probe=3a2f4f9848) | Jul 21, 2022 |
| Acer          | TravelMate 8371             | [4af529e1c4](https://linux-hardware.org/?probe=4af529e1c4) | Jul 20, 2022 |
| Avell High... | A40 LIV                     | [7a685eedd0](https://linux-hardware.org/?probe=7a685eedd0) | Jul 20, 2022 |
| Lenovo        | G550 2958                   | [caeec900b9](https://linux-hardware.org/?probe=caeec900b9) | Jul 19, 2022 |
| Acer          | Aspire A515-45              | [4189e96860](https://linux-hardware.org/?probe=4189e96860) | Jul 19, 2022 |
| HP            | 255 G8 Notebook PC          | [59e9017400](https://linux-hardware.org/?probe=59e9017400) | Jul 19, 2022 |
| Sony          | VPCEH37FJ                   | [1cc39f5c15](https://linux-hardware.org/?probe=1cc39f5c15) | Jul 19, 2022 |
| Lenovo        | G550 2958                   | [ee73634801](https://linux-hardware.org/?probe=ee73634801) | Jul 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [9d756ec471](https://linux-hardware.org/?probe=9d756ec471) | Jul 18, 2022 |
| HP            | Compaq 6910p                | [e6a5ffa902](https://linux-hardware.org/?probe=e6a5ffa902) | Jul 18, 2022 |
| Razer         | Blade 15 Advanced Model ... | [8f3842495f](https://linux-hardware.org/?probe=8f3842495f) | Jul 18, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [56fbc3bbaa](https://linux-hardware.org/?probe=56fbc3bbaa) | Jul 18, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [aa5bdf4dd0](https://linux-hardware.org/?probe=aa5bdf4dd0) | Jul 18, 2022 |
| Acer          | Aspire A315-23G             | [268d2145ff](https://linux-hardware.org/?probe=268d2145ff) | Jul 17, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [42d7df651d](https://linux-hardware.org/?probe=42d7df651d) | Jul 17, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [9fd4b3dd50](https://linux-hardware.org/?probe=9fd4b3dd50) | Jul 17, 2022 |
| Lenovo        | ThinkPad P51s 20HB000URT    | [7f9c1a586d](https://linux-hardware.org/?probe=7f9c1a586d) | Jul 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [41fd0bf728](https://linux-hardware.org/?probe=41fd0bf728) | Jul 16, 2022 |
| Dell          | Vostro 3550                 | [9bd81d608a](https://linux-hardware.org/?probe=9bd81d608a) | Jul 15, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [e442e954fb](https://linux-hardware.org/?probe=e442e954fb) | Jul 15, 2022 |
| HP            | Unknown                     | [e4ccba30f8](https://linux-hardware.org/?probe=e4ccba30f8) | Jul 15, 2022 |
| GPU Compan... | GWTN156-9                   | [df5c4b480d](https://linux-hardware.org/?probe=df5c4b480d) | Jul 15, 2022 |
| Acer          | Aspire 7741                 | [c243e256b8](https://linux-hardware.org/?probe=c243e256b8) | Jul 14, 2022 |
| Acer          | Aspire 7741                 | [0578837b28](https://linux-hardware.org/?probe=0578837b28) | Jul 14, 2022 |
| Acer          | AOD257                      | [ba11099c7f](https://linux-hardware.org/?probe=ba11099c7f) | Jul 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [63c4a7a0bd](https://linux-hardware.org/?probe=63c4a7a0bd) | Jul 14, 2022 |
| HP            | Pavilion g4                 | [40067cace0](https://linux-hardware.org/?probe=40067cace0) | Jul 14, 2022 |
| Acer          | Aspire A315-23G             | [09f86c23ae](https://linux-hardware.org/?probe=09f86c23ae) | Jul 14, 2022 |
| Dell          | Latitude 5310               | [bc161b95e9](https://linux-hardware.org/?probe=bc161b95e9) | Jul 13, 2022 |
| HP            | Laptop 15-ef2xxx            | [77bf0433d1](https://linux-hardware.org/?probe=77bf0433d1) | Jul 13, 2022 |
| HP            | Laptop 15-ef2xxx            | [6b488ff0fd](https://linux-hardware.org/?probe=6b488ff0fd) | Jul 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [3a612ba2bd](https://linux-hardware.org/?probe=3a612ba2bd) | Jul 12, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | [8c160ae192](https://linux-hardware.org/?probe=8c160ae192) | Jul 12, 2022 |
| HP            | 250 G8 Notebook PC          | [17cdd0291e](https://linux-hardware.org/?probe=17cdd0291e) | Jul 12, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [7cab42adeb](https://linux-hardware.org/?probe=7cab42adeb) | Jul 12, 2022 |
| ASUSTek       | X541UJ                      | [1725714269](https://linux-hardware.org/?probe=1725714269) | Jul 11, 2022 |
| ASUSTek       | X541UJ                      | [cc10e6800a](https://linux-hardware.org/?probe=cc10e6800a) | Jul 11, 2022 |
| Dell          | Latitude 5510               | [5f1abb9d12](https://linux-hardware.org/?probe=5f1abb9d12) | Jul 11, 2022 |
| Lenovo        | ThinkPad T490 20N3SEYA00    | [3370fd5142](https://linux-hardware.org/?probe=3370fd5142) | Jul 11, 2022 |
| HP            | Pavilion g4                 | [96ba266748](https://linux-hardware.org/?probe=96ba266748) | Jul 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [7cfc308ed6](https://linux-hardware.org/?probe=7cfc308ed6) | Jul 10, 2022 |
| Acer          | Aspire A315-23G             | [a2ef844aef](https://linux-hardware.org/?probe=a2ef844aef) | Jul 10, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [6f45ac99b1](https://linux-hardware.org/?probe=6f45ac99b1) | Jul 08, 2022 |
| Acer          | Aspire A715-75G             | [4a6cc98dd6](https://linux-hardware.org/?probe=4a6cc98dd6) | Jul 08, 2022 |
| Dell          | Latitude D620               | [70be0d553e](https://linux-hardware.org/?probe=70be0d553e) | Jul 08, 2022 |
| Google        | Terra                       | [7623f51d7a](https://linux-hardware.org/?probe=7623f51d7a) | Jul 08, 2022 |
| HUAWEI        | BOD-WXX9                    | [f4d2c6bb1e](https://linux-hardware.org/?probe=f4d2c6bb1e) | Jul 08, 2022 |
| AZW           | T3 MRD                      | [7f8d8245e1](https://linux-hardware.org/?probe=7f8d8245e1) | Jul 08, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6a78826e86](https://linux-hardware.org/?probe=6a78826e86) | Jul 07, 2022 |
| Dell          | Latitude 5285               | [1faeae7b00](https://linux-hardware.org/?probe=1faeae7b00) | Jul 07, 2022 |
| HP            | Laptop 15-bw0xx             | [c5cc2b52bb](https://linux-hardware.org/?probe=c5cc2b52bb) | Jul 07, 2022 |
| Dell          | Vostro 15 3510              | [bb44d4f6ba](https://linux-hardware.org/?probe=bb44d4f6ba) | Jul 07, 2022 |
| Google        | Enguarde                    | [bd97b057e3](https://linux-hardware.org/?probe=bd97b057e3) | Jul 06, 2022 |
| Google        | Peppy                       | [fe053f74c7](https://linux-hardware.org/?probe=fe053f74c7) | Jul 06, 2022 |
| Google        | Coral                       | [47442944de](https://linux-hardware.org/?probe=47442944de) | Jul 06, 2022 |
| HP            | EliteBook 2530p             | [a4b4609db8](https://linux-hardware.org/?probe=a4b4609db8) | Jul 05, 2022 |
| ASUSTek       | G55VW                       | [fa0346f5df](https://linux-hardware.org/?probe=fa0346f5df) | Jul 05, 2022 |
| ASUSTek       | G55VW                       | [832ca8cf45](https://linux-hardware.org/?probe=832ca8cf45) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| Dell          | Latitude 5421               | [8a40be5ce5](https://linux-hardware.org/?probe=8a40be5ce5) | Jul 05, 2022 |
| Unknown       | Unknown                     | [78e8133c88](https://linux-hardware.org/?probe=78e8133c88) | Jul 03, 2022 |
| Dell          | Vostro 3549                 | [d23ff685fc](https://linux-hardware.org/?probe=d23ff685fc) | Jul 03, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [75f07cbe46](https://linux-hardware.org/?probe=75f07cbe46) | Jul 02, 2022 |
| Acer          | Nitro AN517-52              | [3920a80387](https://linux-hardware.org/?probe=3920a80387) | Jul 02, 2022 |
| Unknown       | Unknown                     | [72833df63f](https://linux-hardware.org/?probe=72833df63f) | Jul 02, 2022 |
| Acer          | Nitro AN517-52              | [37fbd3a600](https://linux-hardware.org/?probe=37fbd3a600) | Jul 02, 2022 |
| Acer          | Aspire A315-23G             | [6fc80d8654](https://linux-hardware.org/?probe=6fc80d8654) | Jul 02, 2022 |
| Dell          | Vostro 3550                 | [d68e2660b7](https://linux-hardware.org/?probe=d68e2660b7) | Jul 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [9b8bb07ff0](https://linux-hardware.org/?probe=9b8bb07ff0) | Jul 01, 2022 |
| ASUSTek       | X756UQK                     | [62595fe324](https://linux-hardware.org/?probe=62595fe324) | Jul 01, 2022 |
| Sony          | VPCEH37FJ                   | [509fe56362](https://linux-hardware.org/?probe=509fe56362) | Jul 01, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [75b3bd3b8c](https://linux-hardware.org/?probe=75b3bd3b8c) | Jun 30, 2022 |
| Acer          | Aspire V3-571G              | [e5283c0142](https://linux-hardware.org/?probe=e5283c0142) | Jun 30, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [980925115f](https://linux-hardware.org/?probe=980925115f) | Jun 30, 2022 |
| Acer          | Aspire V3-571G              | [5e795f7aa1](https://linux-hardware.org/?probe=5e795f7aa1) | Jun 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a423eae14](https://linux-hardware.org/?probe=3a423eae14) | Jun 30, 2022 |
| Acer          | Aspire A315-23G             | [f5ca75e65b](https://linux-hardware.org/?probe=f5ca75e65b) | Jun 30, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [91c5f849c5](https://linux-hardware.org/?probe=91c5f849c5) | Jun 29, 2022 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [4b2106c800](https://linux-hardware.org/?probe=4b2106c800) | Jun 29, 2022 |
| Dell          | Latitude D610               | [0d55e1e388](https://linux-hardware.org/?probe=0d55e1e388) | Jun 29, 2022 |
| Lenovo        | ThinkPad X230 2325AEG       | [eaa3a2096e](https://linux-hardware.org/?probe=eaa3a2096e) | Jun 29, 2022 |
| Dell          | Latitude 5430               | [119502eddb](https://linux-hardware.org/?probe=119502eddb) | Jun 29, 2022 |
| HP            | EliteBook 840 G3            | [d7282a0f61](https://linux-hardware.org/?probe=d7282a0f61) | Jun 29, 2022 |
| ASUSTek       | G752VT                      | [d51730ccbf](https://linux-hardware.org/?probe=d51730ccbf) | Jun 29, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [c4dea8fa5d](https://linux-hardware.org/?probe=c4dea8fa5d) | Jun 28, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | [01fbfc98f8](https://linux-hardware.org/?probe=01fbfc98f8) | Jun 27, 2022 |
| BenQ          | Joybook Lite U102           | [49bbad20bd](https://linux-hardware.org/?probe=49bbad20bd) | Jun 27, 2022 |
| Dell          | Vostro 3550                 | [5c998424fb](https://linux-hardware.org/?probe=5c998424fb) | Jun 27, 2022 |
| HP            | EliteBook 840 G1            | [a1bfc8261f](https://linux-hardware.org/?probe=a1bfc8261f) | Jun 27, 2022 |
| Lenovo        | ThinkPad T470 20HES07J00    | [4be29eb5f1](https://linux-hardware.org/?probe=4be29eb5f1) | Jun 27, 2022 |
| HP            | ProBook 440 G0              | [4dbdbb04d3](https://linux-hardware.org/?probe=4dbdbb04d3) | Jun 27, 2022 |
| Aquarius      | NS585                       | [107a5ae472](https://linux-hardware.org/?probe=107a5ae472) | Jun 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | [b947b14fe4](https://linux-hardware.org/?probe=b947b14fe4) | Jun 27, 2022 |
| Dell          | Latitude E6520              | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Dell          | Inspiron 5502               | [c3e90d4ebd](https://linux-hardware.org/?probe=c3e90d4ebd) | Jun 26, 2022 |
| Acer          | Aspire A114-31              | [8fd4467dfd](https://linux-hardware.org/?probe=8fd4467dfd) | Jun 25, 2022 |
| Dell          | Latitude E6520              | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| Lenovo        | Edge 15 80K9                | [9399fd58cc](https://linux-hardware.org/?probe=9399fd58cc) | Jun 25, 2022 |
| Medion        | E16402                      | [1e16a44daa](https://linux-hardware.org/?probe=1e16a44daa) | Jun 25, 2022 |
| Dell          | Latitude E6330              | [969981b8cb](https://linux-hardware.org/?probe=969981b8cb) | Jun 25, 2022 |
| Lenovo        | ThinkPad T61 7659CA1        | [adce1c6762](https://linux-hardware.org/?probe=adce1c6762) | Jun 25, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [ba9c4d7141](https://linux-hardware.org/?probe=ba9c4d7141) | Jun 25, 2022 |
| ASUSTek       | X751LK                      | [e864b5e674](https://linux-hardware.org/?probe=e864b5e674) | Jun 24, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [eaf51fc79f](https://linux-hardware.org/?probe=eaf51fc79f) | Jun 24, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d742e624c6](https://linux-hardware.org/?probe=d742e624c6) | Jun 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [8df3dc4de2](https://linux-hardware.org/?probe=8df3dc4de2) | Jun 23, 2022 |
| Aquarius      | NS585                       | [1e0b20db82](https://linux-hardware.org/?probe=1e0b20db82) | Jun 23, 2022 |
| Dell          | Latitude 5490               | [f0726860d4](https://linux-hardware.org/?probe=f0726860d4) | Jun 23, 2022 |
| Dell          | Precision 7560              | [760bb908b9](https://linux-hardware.org/?probe=760bb908b9) | Jun 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [a2a6f48fe2](https://linux-hardware.org/?probe=a2a6f48fe2) | Jun 22, 2022 |
| Dell          | Latitude E6440              | [ea3bfb384f](https://linux-hardware.org/?probe=ea3bfb384f) | Jun 22, 2022 |
| HP            | 255 G3                      | [def96ad707](https://linux-hardware.org/?probe=def96ad707) | Jun 21, 2022 |
| Dell          | G15 5510                    | [cfd6e8f4d6](https://linux-hardware.org/?probe=cfd6e8f4d6) | Jun 21, 2022 |
| Fujitsu       | LIFEBOOK E744               | [093dfd12e4](https://linux-hardware.org/?probe=093dfd12e4) | Jun 21, 2022 |
| Fujitsu       | LIFEBOOK E744               | [b741aac903](https://linux-hardware.org/?probe=b741aac903) | Jun 21, 2022 |
| HP            | 250 G6 Notebook PC          | [30d0a46d81](https://linux-hardware.org/?probe=30d0a46d81) | Jun 21, 2022 |
| Acer          | Nitro AN515-55              | [b3b8a4d0c8](https://linux-hardware.org/?probe=b3b8a4d0c8) | Jun 21, 2022 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [bd4de35624](https://linux-hardware.org/?probe=bd4de35624) | Jun 20, 2022 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [9dd9dbdaa4](https://linux-hardware.org/?probe=9dd9dbdaa4) | Jun 20, 2022 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [0483d0dd9e](https://linux-hardware.org/?probe=0483d0dd9e) | Jun 20, 2022 |
| ASUSTek       | X556UQK                     | [6ce6e1d459](https://linux-hardware.org/?probe=6ce6e1d459) | Jun 20, 2022 |
| Samsung       | 935XDB                      | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f013ebb91b](https://linux-hardware.org/?probe=f013ebb91b) | Jun 20, 2022 |
| Aquarius      | NS585                       | [b08de59180](https://linux-hardware.org/?probe=b08de59180) | Jun 20, 2022 |
| Aquarius      | NS585                       | [28e0ced692](https://linux-hardware.org/?probe=28e0ced692) | Jun 20, 2022 |
| Aquarius      | NS585                       | [446cb710dc](https://linux-hardware.org/?probe=446cb710dc) | Jun 20, 2022 |
| Lenovo        | ThinkPad T470 20HD000EUK    | [6cc2ca4099](https://linux-hardware.org/?probe=6cc2ca4099) | Jun 19, 2022 |
| Acer          | Aspire V5-571               | [694dbcacc1](https://linux-hardware.org/?probe=694dbcacc1) | Jun 19, 2022 |
| Dell          | Inspiron 7370               | [e8a53b7f1b](https://linux-hardware.org/?probe=e8a53b7f1b) | Jun 18, 2022 |
| Acer          | Aspire A315-23G             | [2ec41b35a4](https://linux-hardware.org/?probe=2ec41b35a4) | Jun 18, 2022 |
| ASUSTek       | S550CM                      | [43ddcf21fb](https://linux-hardware.org/?probe=43ddcf21fb) | Jun 17, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [8d56f09226](https://linux-hardware.org/?probe=8d56f09226) | Jun 17, 2022 |
| Acer          | Nitro AN515-51              | [51caf7f2a3](https://linux-hardware.org/?probe=51caf7f2a3) | Jun 16, 2022 |
| Aquarius      | NS585                       | [e569242ae1](https://linux-hardware.org/?probe=e569242ae1) | Jun 16, 2022 |
| Aquarius      | NS585                       | [955b8f0fb2](https://linux-hardware.org/?probe=955b8f0fb2) | Jun 16, 2022 |
| Aquarius      | NS585                       | [815d2fd86a](https://linux-hardware.org/?probe=815d2fd86a) | Jun 16, 2022 |
| Aquarius      | NS585                       | [95b4800d70](https://linux-hardware.org/?probe=95b4800d70) | Jun 16, 2022 |
| Aquarius      | NS585                       | [944dcbf099](https://linux-hardware.org/?probe=944dcbf099) | Jun 16, 2022 |
| HUAWEI        | KLVD-WXX9                   | [4c97b8cc3a](https://linux-hardware.org/?probe=4c97b8cc3a) | Jun 16, 2022 |
| HP            | Stream Laptop 11-y0XX       | [5a762627ab](https://linux-hardware.org/?probe=5a762627ab) | Jun 16, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [b61e91e363](https://linux-hardware.org/?probe=b61e91e363) | Jun 15, 2022 |
| Aquarius      | NS585                       | [bf740af11c](https://linux-hardware.org/?probe=bf740af11c) | Jun 15, 2022 |
| Aquarius      | NS585                       | [e2906f745c](https://linux-hardware.org/?probe=e2906f745c) | Jun 15, 2022 |
| Aquarius      | NS585                       | [ced17caa07](https://linux-hardware.org/?probe=ced17caa07) | Jun 15, 2022 |
| Aquarius      | NS585                       | [08614740a5](https://linux-hardware.org/?probe=08614740a5) | Jun 15, 2022 |
| Aquarius      | NS585                       | [ba7a3660fb](https://linux-hardware.org/?probe=ba7a3660fb) | Jun 15, 2022 |
| Aquarius      | NS585                       | [a2cfae14e3](https://linux-hardware.org/?probe=a2cfae14e3) | Jun 15, 2022 |
| Aquarius      | NS585                       | [ea1cdaa121](https://linux-hardware.org/?probe=ea1cdaa121) | Jun 15, 2022 |
| Aquarius      | NS585                       | [358e315ac6](https://linux-hardware.org/?probe=358e315ac6) | Jun 15, 2022 |
| Aquarius      | NS585                       | [906c1b911b](https://linux-hardware.org/?probe=906c1b911b) | Jun 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ce37872e58](https://linux-hardware.org/?probe=ce37872e58) | Jun 15, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [60969fcd9a](https://linux-hardware.org/?probe=60969fcd9a) | Jun 15, 2022 |
| Google        | Celes                       | [7f6beef1e7](https://linux-hardware.org/?probe=7f6beef1e7) | Jun 15, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [8f42361336](https://linux-hardware.org/?probe=8f42361336) | Jun 14, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [e06841340d](https://linux-hardware.org/?probe=e06841340d) | Jun 14, 2022 |
| Acer          | Aspire A315-23G             | [b7223cfa1f](https://linux-hardware.org/?probe=b7223cfa1f) | Jun 14, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [67dece9099](https://linux-hardware.org/?probe=67dece9099) | Jun 13, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [0da40dea6c](https://linux-hardware.org/?probe=0da40dea6c) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [537b26aaf0](https://linux-hardware.org/?probe=537b26aaf0) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | [f7d3ee91c6](https://linux-hardware.org/?probe=f7d3ee91c6) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | [4347d50981](https://linux-hardware.org/?probe=4347d50981) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [ca2c0e822c](https://linux-hardware.org/?probe=ca2c0e822c) | Jun 11, 2022 |
| Acer          | Aspire T5000                | [38e164657d](https://linux-hardware.org/?probe=38e164657d) | Jun 11, 2022 |
| HP            | EliteBook 840 G6            | [f2351bb361](https://linux-hardware.org/?probe=f2351bb361) | Jun 11, 2022 |
| ASUSTek       | N550JK                      | [2c4116c1eb](https://linux-hardware.org/?probe=2c4116c1eb) | Jun 10, 2022 |
| Aquarius      | NS585                       | [bec14fe850](https://linux-hardware.org/?probe=bec14fe850) | Jun 10, 2022 |
| Dell          | Latitude 5310               | [fe0ffed6e4](https://linux-hardware.org/?probe=fe0ffed6e4) | Jun 10, 2022 |
| Dell          | Latitude E6410              | [6e26870ebe](https://linux-hardware.org/?probe=6e26870ebe) | Jun 10, 2022 |
| HP            | 240 G7                      | [bf52288eb2](https://linux-hardware.org/?probe=bf52288eb2) | Jun 10, 2022 |
| HUAWEI        | NBD-WXX9                    | [b8e097f983](https://linux-hardware.org/?probe=b8e097f983) | Jun 10, 2022 |
| Lenovo        | IdeaPad 5-15IIL05 81YK      | [b194866bb7](https://linux-hardware.org/?probe=b194866bb7) | Jun 10, 2022 |
| ASUSTek       | X541UAK                     | [111ebf5004](https://linux-hardware.org/?probe=111ebf5004) | Jun 09, 2022 |
| HP            | Pavilion 17                 | [f4afc30981](https://linux-hardware.org/?probe=f4afc30981) | Jun 09, 2022 |
| Acer          | Aspire R5-471T              | [d621ad4f4a](https://linux-hardware.org/?probe=d621ad4f4a) | Jun 09, 2022 |
| Aquarius      | NS585                       | [43bdbb4f7c](https://linux-hardware.org/?probe=43bdbb4f7c) | Jun 09, 2022 |
| Fujitsu       | LIFEBOOK E752               | [6047335005](https://linux-hardware.org/?probe=6047335005) | Jun 09, 2022 |
| ASUSTek       | X541UAK                     | [6903499468](https://linux-hardware.org/?probe=6903499468) | Jun 08, 2022 |
| Aquarius      | NS585                       | [5b578cce47](https://linux-hardware.org/?probe=5b578cce47) | Jun 08, 2022 |
| Aquarius      | NS585                       | [c621cccd03](https://linux-hardware.org/?probe=c621cccd03) | Jun 08, 2022 |
| Aquarius      | NS585                       | [901fd6aaa4](https://linux-hardware.org/?probe=901fd6aaa4) | Jun 08, 2022 |
| HP            | Pavilion 15                 | [08a042a74a](https://linux-hardware.org/?probe=08a042a74a) | Jun 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| ASUSTek       | G752VT                      | [bb5bb68126](https://linux-hardware.org/?probe=bb5bb68126) | Jun 08, 2022 |
| Dell          | Vostro 15 3510              | [471dc7f2db](https://linux-hardware.org/?probe=471dc7f2db) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [ea589a3279](https://linux-hardware.org/?probe=ea589a3279) | Jun 07, 2022 |
| Flipkart I... | NKi510TL85S                 | [6e1326c27f](https://linux-hardware.org/?probe=6e1326c27f) | Jun 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [b2f7663fc9](https://linux-hardware.org/?probe=b2f7663fc9) | Jun 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [39bb0fa0c5](https://linux-hardware.org/?probe=39bb0fa0c5) | Jun 07, 2022 |
| Apple         | MacBookPro11,4              | [d6662c5acf](https://linux-hardware.org/?probe=d6662c5acf) | Jun 07, 2022 |
| Toshiba       | Satellite L850              | [809d0bbd73](https://linux-hardware.org/?probe=809d0bbd73) | Jun 07, 2022 |
| Toshiba       | Satellite L850              | [761d37bd31](https://linux-hardware.org/?probe=761d37bd31) | Jun 06, 2022 |
| Insyde        | GeminiLake                  | [4f2f6240b1](https://linux-hardware.org/?probe=4f2f6240b1) | Jun 06, 2022 |
| Insyde        | GeminiLake                  | [1c308cac35](https://linux-hardware.org/?probe=1c308cac35) | Jun 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [721f0da2de](https://linux-hardware.org/?probe=721f0da2de) | Jun 05, 2022 |
| Dell          | Latitude E6400              | [e4f54892c2](https://linux-hardware.org/?probe=e4f54892c2) | Jun 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f3bdd4cf82](https://linux-hardware.org/?probe=f3bdd4cf82) | Jun 05, 2022 |
| HP            | 250 G7 Notebook PC          | [ab5f939022](https://linux-hardware.org/?probe=ab5f939022) | Jun 04, 2022 |
| HP            | 250 G7 Notebook PC          | [f2ad368041](https://linux-hardware.org/?probe=f2ad368041) | Jun 04, 2022 |
| HP            | 250 G7 Notebook PC          | [1053e6f6d2](https://linux-hardware.org/?probe=1053e6f6d2) | Jun 04, 2022 |
| Dell          | Vostro 3480                 | [31825ebb84](https://linux-hardware.org/?probe=31825ebb84) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [eaad038fde](https://linux-hardware.org/?probe=eaad038fde) | Jun 03, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9533388943](https://linux-hardware.org/?probe=9533388943) | Jun 03, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [2b704f7e81](https://linux-hardware.org/?probe=2b704f7e81) | Jun 03, 2022 |
| Aquarius      | NS585                       | [1747344540](https://linux-hardware.org/?probe=1747344540) | Jun 03, 2022 |
| Aquarius      | NS585                       | [1cf86cb83b](https://linux-hardware.org/?probe=1cf86cb83b) | Jun 03, 2022 |
| Aquarius      | NS585                       | [27744ecba9](https://linux-hardware.org/?probe=27744ecba9) | Jun 03, 2022 |
| Acer          | Aspire A315-23G             | [7b3b8ff142](https://linux-hardware.org/?probe=7b3b8ff142) | Jun 03, 2022 |
| Acer          | Aspire A315-23G             | [cfb73d2727](https://linux-hardware.org/?probe=cfb73d2727) | Jun 02, 2022 |
| Apple         | MacBookPro11,1              | [b12802bc7a](https://linux-hardware.org/?probe=b12802bc7a) | Jun 02, 2022 |
| HP            | 250 G6 Notebook PC          | [878274dbce](https://linux-hardware.org/?probe=878274dbce) | Jun 02, 2022 |
| HP            | Pavilion g6                 | [7840b394d3](https://linux-hardware.org/?probe=7840b394d3) | Jun 02, 2022 |
| TEKNOSERVI... | PORTATIL TTL 14             | [7af14493e8](https://linux-hardware.org/?probe=7af14493e8) | Jun 01, 2022 |
| HP            | Pavilion g4                 | [321300f927](https://linux-hardware.org/?probe=321300f927) | Jun 01, 2022 |
| Lenovo        | ThinkPad T440s 20AQ008FU... | [3b5255ec2c](https://linux-hardware.org/?probe=3b5255ec2c) | Jun 01, 2022 |
| Dell          | Latitude E6400              | [85d314bfd8](https://linux-hardware.org/?probe=85d314bfd8) | May 31, 2022 |
| Aquarius      | NS585                       | [44bd30c95d](https://linux-hardware.org/?probe=44bd30c95d) | May 31, 2022 |
| Aquarius      | NS585                       | [2a7545f0f9](https://linux-hardware.org/?probe=2a7545f0f9) | May 31, 2022 |
| Aquarius      | NS585                       | [12e45f7665](https://linux-hardware.org/?probe=12e45f7665) | May 31, 2022 |
| Aquarius      | NS585                       | [c420e4cafb](https://linux-hardware.org/?probe=c420e4cafb) | May 31, 2022 |
| Aquarius      | NS585                       | [e562931a35](https://linux-hardware.org/?probe=e562931a35) | May 31, 2022 |
| Aquarius      | NS585                       | [0d31fa737e](https://linux-hardware.org/?probe=0d31fa737e) | May 31, 2022 |
| Aquarius      | NS585                       | [6e5a613444](https://linux-hardware.org/?probe=6e5a613444) | May 31, 2022 |
| Aquarius      | NS585                       | [7744e6a785](https://linux-hardware.org/?probe=7744e6a785) | May 31, 2022 |
| Aquarius      | NS585                       | [828c791c7c](https://linux-hardware.org/?probe=828c791c7c) | May 31, 2022 |
| Aquarius      | NS585                       | [ff8ca3e68b](https://linux-hardware.org/?probe=ff8ca3e68b) | May 31, 2022 |
| Aquarius      | NS585                       | [dbbe2e1b71](https://linux-hardware.org/?probe=dbbe2e1b71) | May 31, 2022 |
| Aquarius      | NS585                       | [099918e5b2](https://linux-hardware.org/?probe=099918e5b2) | May 31, 2022 |
| Aquarius      | NS585                       | [bdcf61dc44](https://linux-hardware.org/?probe=bdcf61dc44) | May 31, 2022 |
| Aquarius      | NS585                       | [e41a23ba31](https://linux-hardware.org/?probe=e41a23ba31) | May 31, 2022 |
| Dell          | Latitude E6400              | [f5ae9fef9c](https://linux-hardware.org/?probe=f5ae9fef9c) | May 31, 2022 |
| Aquarius      | NS585                       | [ff453a32b6](https://linux-hardware.org/?probe=ff453a32b6) | May 31, 2022 |
| Aquarius      | NS585                       | [1ed72b7951](https://linux-hardware.org/?probe=1ed72b7951) | May 31, 2022 |
| Aquarius      | NS585                       | [222ff0011e](https://linux-hardware.org/?probe=222ff0011e) | May 31, 2022 |
| Acer          | Aspire T5000                | [7bdeb5fb3b](https://linux-hardware.org/?probe=7bdeb5fb3b) | May 31, 2022 |
| Alienware     | 15 R2                       | [776abe61ea](https://linux-hardware.org/?probe=776abe61ea) | May 31, 2022 |
| Acer          | Aspire E5-575G              | [7c44163245](https://linux-hardware.org/?probe=7c44163245) | May 31, 2022 |
| SANTECH       | NHx0DB,DE                   | [4fbdcfe44b](https://linux-hardware.org/?probe=4fbdcfe44b) | May 30, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [883f055fb1](https://linux-hardware.org/?probe=883f055fb1) | May 30, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [e475b560cf](https://linux-hardware.org/?probe=e475b560cf) | May 30, 2022 |
| Notebook      | W65_67SJ                    | [2f6d77befb](https://linux-hardware.org/?probe=2f6d77befb) | May 29, 2022 |
| Lenovo        | ThinkPad W500 4061W8H       | [db9160e089](https://linux-hardware.org/?probe=db9160e089) | May 29, 2022 |
| Dell          | Vostro 3546                 | [3acd5d4cb0](https://linux-hardware.org/?probe=3acd5d4cb0) | May 28, 2022 |
| ASUSTek       | 900                         | [e50c30c38d](https://linux-hardware.org/?probe=e50c30c38d) | May 28, 2022 |
| ASUSTek       | 900                         | [dfd6af657c](https://linux-hardware.org/?probe=dfd6af657c) | May 28, 2022 |
| HP            | Notebook                    | [9900044e89](https://linux-hardware.org/?probe=9900044e89) | May 27, 2022 |
| HP            | 255 G8 Notebook PC          | [9430147fab](https://linux-hardware.org/?probe=9430147fab) | May 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d2581e2c05](https://linux-hardware.org/?probe=d2581e2c05) | May 27, 2022 |
| MSI           | Katana GF66 11UD            | [f3ee20f625](https://linux-hardware.org/?probe=f3ee20f625) | May 27, 2022 |
| HP            | Pavilion g6                 | [0e98027e39](https://linux-hardware.org/?probe=0e98027e39) | May 26, 2022 |
| ASUSTek       | K43E                        | [968007a0a9](https://linux-hardware.org/?probe=968007a0a9) | May 26, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [9ebff03a43](https://linux-hardware.org/?probe=9ebff03a43) | May 26, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [cc80808aea](https://linux-hardware.org/?probe=cc80808aea) | May 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [f5488ccb22](https://linux-hardware.org/?probe=f5488ccb22) | May 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [75063d8f18](https://linux-hardware.org/?probe=75063d8f18) | May 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [0d1ba4ee73](https://linux-hardware.org/?probe=0d1ba4ee73) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [86f00d534a](https://linux-hardware.org/?probe=86f00d534a) | May 26, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [0f450fb6e0](https://linux-hardware.org/?probe=0f450fb6e0) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [3929f17532](https://linux-hardware.org/?probe=3929f17532) | May 26, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [29b8def5b3](https://linux-hardware.org/?probe=29b8def5b3) | May 25, 2022 |
| Apple         | MacBookPro15,2              | [c0fe1740e0](https://linux-hardware.org/?probe=c0fe1740e0) | May 25, 2022 |
| Dell          | Latitude 5310               | [2117fbfccb](https://linux-hardware.org/?probe=2117fbfccb) | May 25, 2022 |
| Acer          | Aspire A315-23              | [dd46d19f05](https://linux-hardware.org/?probe=dd46d19f05) | May 25, 2022 |
| MSI           | GP62MVR 6RF                 | [1dd5741ea8](https://linux-hardware.org/?probe=1dd5741ea8) | May 25, 2022 |
| Dell          | Inspiron 3543               | [c48c32ae19](https://linux-hardware.org/?probe=c48c32ae19) | May 25, 2022 |
| Acer          | Nitro AN515-42              | [c755d907ca](https://linux-hardware.org/?probe=c755d907ca) | May 24, 2022 |
| Dell          | Latitude 5310               | [cb40714b3f](https://linux-hardware.org/?probe=cb40714b3f) | May 24, 2022 |
| Dell          | Latitude 5300               | [b2e8f91f15](https://linux-hardware.org/?probe=b2e8f91f15) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1d8684d1f5](https://linux-hardware.org/?probe=1d8684d1f5) | May 23, 2022 |
| Samsung       | SR70S/SR71S                 | [53642077bd](https://linux-hardware.org/?probe=53642077bd) | May 23, 2022 |
| Google        | Glimmer                     | [f16458e3ea](https://linux-hardware.org/?probe=f16458e3ea) | May 22, 2022 |
| LG Electro... | A410-G.BC48P1               | [fb2344f915](https://linux-hardware.org/?probe=fb2344f915) | May 22, 2022 |
| Dell          | Inspiron 1545               | [890010e793](https://linux-hardware.org/?probe=890010e793) | May 21, 2022 |
| ASUSTek       | 900                         | [082b51aa29](https://linux-hardware.org/?probe=082b51aa29) | May 21, 2022 |
| Lenovo        | ThinkPad E550 20DF002YUS    | [fe9f7989ef](https://linux-hardware.org/?probe=fe9f7989ef) | May 21, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c273310228](https://linux-hardware.org/?probe=c273310228) | May 20, 2022 |
| HP            | 250 G3                      | [463622ad88](https://linux-hardware.org/?probe=463622ad88) | May 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2972e28673](https://linux-hardware.org/?probe=2972e28673) | May 19, 2022 |
| Dell          | Latitude E4310              | [79cda1608c](https://linux-hardware.org/?probe=79cda1608c) | May 19, 2022 |
| System76      | Kudu                        | [78ce5e3b3e](https://linux-hardware.org/?probe=78ce5e3b3e) | May 19, 2022 |
| Acer          | Aspire 5750                 | [4c6bbffcae](https://linux-hardware.org/?probe=4c6bbffcae) | May 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61e58bea6c](https://linux-hardware.org/?probe=61e58bea6c) | May 17, 2022 |
| HP            | ProBook 4720s               | [887ea9cd89](https://linux-hardware.org/?probe=887ea9cd89) | May 16, 2022 |
| Lenovo        | V145-15AST 81MT             | [486b786e45](https://linux-hardware.org/?probe=486b786e45) | May 16, 2022 |
| HP            | ProBook 4720s               | [09bb5a5088](https://linux-hardware.org/?probe=09bb5a5088) | May 16, 2022 |
| Dell          | Precision 3551              | [f134f92d00](https://linux-hardware.org/?probe=f134f92d00) | May 16, 2022 |
| ASUSTek       | X550LD                      | [75c6734097](https://linux-hardware.org/?probe=75c6734097) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [f0fef230c2](https://linux-hardware.org/?probe=f0fef230c2) | May 15, 2022 |
| Lenovo        | ThinkPad W520 4284D47       | [2f0e46cc27](https://linux-hardware.org/?probe=2f0e46cc27) | May 15, 2022 |
| Lenovo        | ThinkPad X260 20F5S4C000    | [66fe039d1a](https://linux-hardware.org/?probe=66fe039d1a) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3f84f4220e](https://linux-hardware.org/?probe=3f84f4220e) | May 14, 2022 |
| Lenovo        | ThinkPad X260 20F5S4C000    | [96693754dd](https://linux-hardware.org/?probe=96693754dd) | May 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [d8cfc5384f](https://linux-hardware.org/?probe=d8cfc5384f) | May 13, 2022 |
| Dell          | System Inspiron N7110       | [f397801c5f](https://linux-hardware.org/?probe=f397801c5f) | May 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8866f1fd7c](https://linux-hardware.org/?probe=8866f1fd7c) | May 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [76a04f4e4e](https://linux-hardware.org/?probe=76a04f4e4e) | May 13, 2022 |
| HP            | EliteBook 820 G1            | [dd51bb3592](https://linux-hardware.org/?probe=dd51bb3592) | May 12, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [8431edf013](https://linux-hardware.org/?probe=8431edf013) | May 12, 2022 |
| Acer          | Aspire 5750                 | [008e256981](https://linux-hardware.org/?probe=008e256981) | May 12, 2022 |
| HP            | Notebook                    | [3b4cd7fe5a](https://linux-hardware.org/?probe=3b4cd7fe5a) | May 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [53aed63d64](https://linux-hardware.org/?probe=53aed63d64) | May 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7d03983e37](https://linux-hardware.org/?probe=7d03983e37) | May 11, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| HP            | 250 G6 Notebook PC          | [f2f010a36d](https://linux-hardware.org/?probe=f2f010a36d) | May 11, 2022 |
| HP            | ENVY TS 17                  | [2423c94072](https://linux-hardware.org/?probe=2423c94072) | May 10, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3314cd39d7](https://linux-hardware.org/?probe=3314cd39d7) | May 10, 2022 |
| HP            | EliteBook 840 G3            | [9d0ee854e4](https://linux-hardware.org/?probe=9d0ee854e4) | May 10, 2022 |
| Acer          | Swift SF314-52              | [ee252c0c42](https://linux-hardware.org/?probe=ee252c0c42) | May 10, 2022 |
| Thirdwave     | DX-T7                       | [b90ec1bf3a](https://linux-hardware.org/?probe=b90ec1bf3a) | May 10, 2022 |
| Apple         | MacBook1,1                  | [399e291a66](https://linux-hardware.org/?probe=399e291a66) | May 09, 2022 |
| Acer          | Aspire 5750                 | [200ac122e9](https://linux-hardware.org/?probe=200ac122e9) | May 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [65ef6677b9](https://linux-hardware.org/?probe=65ef6677b9) | May 09, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [019117605e](https://linux-hardware.org/?probe=019117605e) | May 08, 2022 |
| Acer          | Aspire 5755G                | [634471ce19](https://linux-hardware.org/?probe=634471ce19) | May 08, 2022 |
| ASUSTek       | 900                         | [a4dc643c13](https://linux-hardware.org/?probe=a4dc643c13) | May 08, 2022 |
| Dell          | Inspiron 13-7378            | [7a8fd14c85](https://linux-hardware.org/?probe=7a8fd14c85) | May 08, 2022 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | [8fa9fd80a0](https://linux-hardware.org/?probe=8fa9fd80a0) | May 07, 2022 |
| SLIMBOOK      | Essential15L                | [1a244b5f4a](https://linux-hardware.org/?probe=1a244b5f4a) | May 07, 2022 |
| SLIMBOOK      | Essential15L                | [4f64e62082](https://linux-hardware.org/?probe=4f64e62082) | May 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [591d3fa922](https://linux-hardware.org/?probe=591d3fa922) | May 07, 2022 |
| Dell          | Latitude E6330              | [cbfc4e6f78](https://linux-hardware.org/?probe=cbfc4e6f78) | May 07, 2022 |
| Lenovo        | ThinkPad W540 20BG0011US    | [1679543d3d](https://linux-hardware.org/?probe=1679543d3d) | May 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS1U60... | [ffafca2b97](https://linux-hardware.org/?probe=ffafca2b97) | May 06, 2022 |
| Lenovo        | Z710 20250                  | [955a89377b](https://linux-hardware.org/?probe=955a89377b) | May 06, 2022 |
| ASUSTek       | UX430UAR                    | [6d471de246](https://linux-hardware.org/?probe=6d471de246) | May 05, 2022 |
| ASUSTek       | UX430UAR                    | [4aea04443a](https://linux-hardware.org/?probe=4aea04443a) | May 05, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [5cba3c93ba](https://linux-hardware.org/?probe=5cba3c93ba) | May 05, 2022 |
| Lenovo        | ThinkPad L412 0585AV3       | [4208da52ad](https://linux-hardware.org/?probe=4208da52ad) | May 04, 2022 |
| HP            | Pavilion g7                 | [e213ff845c](https://linux-hardware.org/?probe=e213ff845c) | May 04, 2022 |
| Dell          | Latitude 5300               | [fa0246b764](https://linux-hardware.org/?probe=fa0246b764) | May 04, 2022 |
| Dell          | Latitude 3520               | [586dc3475e](https://linux-hardware.org/?probe=586dc3475e) | May 04, 2022 |
| HP            | ProBook 4330s               | [7cad0acb2c](https://linux-hardware.org/?probe=7cad0acb2c) | May 04, 2022 |
| HP            | ProBook 4330s               | [ca6474fbfc](https://linux-hardware.org/?probe=ca6474fbfc) | May 04, 2022 |
| Acer          | Aspire A315-23G             | [f749343aee](https://linux-hardware.org/?probe=f749343aee) | May 03, 2022 |
| ASUSTek       | E403SA                      | [c59815fc46](https://linux-hardware.org/?probe=c59815fc46) | May 02, 2022 |
| ASUSTek       | A6G                         | [a873db0112](https://linux-hardware.org/?probe=a873db0112) | May 02, 2022 |
| ASUSTek       | E403SA                      | [1036fd29cb](https://linux-hardware.org/?probe=1036fd29cb) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [20420f0426](https://linux-hardware.org/?probe=20420f0426) | May 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [414334d8e3](https://linux-hardware.org/?probe=414334d8e3) | May 01, 2022 |
| Acer          | Aspire E1-532               | [38d01733a6](https://linux-hardware.org/?probe=38d01733a6) | May 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [acdc37bb16](https://linux-hardware.org/?probe=acdc37bb16) | May 01, 2022 |
| Dell          | Precision M6500             | [a3d82a4f1a](https://linux-hardware.org/?probe=a3d82a4f1a) | Apr 30, 2022 |
| Dell          | Precision M6500             | [cb7e68eb50](https://linux-hardware.org/?probe=cb7e68eb50) | Apr 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e14a2c047d](https://linux-hardware.org/?probe=e14a2c047d) | Apr 30, 2022 |
| HP            | Stream Notebook PC 13       | [f4eb2d351c](https://linux-hardware.org/?probe=f4eb2d351c) | Apr 30, 2022 |
| Dell          | Inspiron 15-3565            | [a26578c0fc](https://linux-hardware.org/?probe=a26578c0fc) | Apr 30, 2022 |
| Dell          | Inspiron N5050              | [7d3cb853e6](https://linux-hardware.org/?probe=7d3cb853e6) | Apr 29, 2022 |
| Google        | Enguarde                    | [878203f099](https://linux-hardware.org/?probe=878203f099) | Apr 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [df82c076b8](https://linux-hardware.org/?probe=df82c076b8) | Apr 29, 2022 |
| Google        | Enguarde                    | [194e2eb81b](https://linux-hardware.org/?probe=194e2eb81b) | Apr 28, 2022 |
| Acer          | Aspire A315-42G             | [03c0f64a6e](https://linux-hardware.org/?probe=03c0f64a6e) | Apr 28, 2022 |
| Google        | Enguarde                    | [37794c3d3a](https://linux-hardware.org/?probe=37794c3d3a) | Apr 28, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [f98b9b686e](https://linux-hardware.org/?probe=f98b9b686e) | Apr 28, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [674c8c1bf3](https://linux-hardware.org/?probe=674c8c1bf3) | Apr 28, 2022 |
| Dell          | Inspiron 15-3565            | [66d159169f](https://linux-hardware.org/?probe=66d159169f) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [73de8fd9f4](https://linux-hardware.org/?probe=73de8fd9f4) | Apr 26, 2022 |
| Dell          | XPS 17 9710                 | [c7dfc69b32](https://linux-hardware.org/?probe=c7dfc69b32) | Apr 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [5c309ec35d](https://linux-hardware.org/?probe=5c309ec35d) | Apr 26, 2022 |
| Intel         | Crestline & ICH8M Chipse... | [b410b890ef](https://linux-hardware.org/?probe=b410b890ef) | Apr 26, 2022 |
| Intel         | Crestline & ICH8M Chipse... | [4435386574](https://linux-hardware.org/?probe=4435386574) | Apr 26, 2022 |
| HP            | Notebook                    | [94f0ce7610](https://linux-hardware.org/?probe=94f0ce7610) | Apr 26, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [2d1a1334c6](https://linux-hardware.org/?probe=2d1a1334c6) | Apr 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 578       | 21.89%  |
| 5.10.0-10-amd64        | 489       | 18.52%  |
| 5.10.0-9-amd64         | 169       | 6.4%    |
| 5.10.0-7-amd64         | 167       | 6.32%   |
| 5.10.0-16-amd64        | 161       | 6.1%    |
| 5.10.0-13-amd64        | 148       | 5.6%    |
| 5.10.0-18-amd64        | 129       | 4.88%   |
| 5.10.0-11-amd64        | 102       | 3.86%   |
| 5.10.0-14-amd64        | 78        | 2.95%   |
| 5.10.0-17-amd64        | 71        | 2.69%   |
| 5.10.0-15-amd64        | 42        | 1.59%   |
| 5.10.0-12-amd64        | 40        | 1.51%   |
| 5.10.0-19-amd64        | 36        | 1.36%   |
| 5.10.0-6-amd64         | 28        | 1.06%   |
| 5.10.0-2-amd64         | 28        | 1.06%   |
| 5.10.0-13-686-pae      | 26        | 0.98%   |
| 5.18.0-0.deb11.4-amd64 | 17        | 0.64%   |
| 5.14.0-0.bpo.2-amd64   | 16        | 0.61%   |
| 5.15.0-2-amd64         | 14        | 0.53%   |
| 5.10.0-3-amd64         | 13        | 0.49%   |
| 5.16.0-0.bpo.4-amd64   | 12        | 0.45%   |
| 5.10.0-9-686-pae       | 9         | 0.34%   |
| 5.10.0-8-686-pae       | 9         | 0.34%   |
| 5.10.0-13-686          | 9         | 0.34%   |
| 5.18.0-0.bpo.1-amd64   | 8         | 0.3%    |
| 5.15.0-0.bpo.2-amd64   | 8         | 0.3%    |
| 5.19.0-2-amd64         | 7         | 0.27%   |
| 5.10.0-9-686           | 7         | 0.27%   |
| 5.18.0-2-amd64         | 6         | 0.23%   |
| 5.19.0-1-amd64         | 5         | 0.19%   |
| 5.10.0-5-amd64         | 5         | 0.19%   |
| 5.10.0-4-amd64         | 5         | 0.19%   |
| 5.10.0-18-686-pae      | 5         | 0.19%   |
| 5.10.0-10-686-pae      | 5         | 0.19%   |
| 5.10.0-1-amd64         | 5         | 0.19%   |
| 5.17.0-1-amd64         | 4         | 0.15%   |
| 5.16.0-5-amd64         | 4         | 0.15%   |
| 5.16.0-3-amd64         | 4         | 0.15%   |
| 5.16.0-1-amd64         | 4         | 0.15%   |
| 5.15.0-1-amd64         | 4         | 0.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 2240      | 90.54%  |
| 5.18.0   | 36        | 1.46%   |
| 5.15.0   | 36        | 1.46%   |
| 5.16.0   | 31        | 1.25%   |
| 5.14.0   | 23        | 0.93%   |
| 5.19.0   | 17        | 0.69%   |
| 5.17.0   | 12        | 0.49%   |
| 4.19.0   | 7         | 0.28%   |
| 5.13.19  | 3         | 0.12%   |
| 5.12.0   | 3         | 0.12%   |
| 5.10.60  | 3         | 0.12%   |
| 5.17.5   | 2         | 0.08%   |
| 5.17.11  | 2         | 0.08%   |
| 5.15.35  | 2         | 0.08%   |
| 5.13.8   | 2         | 0.08%   |
| 5.11.0   | 2         | 0.08%   |
| 5.10.109 | 2         | 0.08%   |
| 4.9.0    | 2         | 0.08%   |
| 6.0.2    | 1         | 0.04%   |
| 5.4.157  | 1         | 0.04%   |
| 5.19.9   | 1         | 0.04%   |
| 5.19.10  | 1         | 0.04%   |
| 5.19.1   | 1         | 0.04%   |
| 5.18.6   | 1         | 0.04%   |
| 5.18.15  | 1         | 0.04%   |
| 5.17.4   | 1         | 0.04%   |
| 5.17.14  | 1         | 0.04%   |
| 5.16.5   | 1         | 0.04%   |
| 5.15.8   | 1         | 0.04%   |
| 5.15.7   | 1         | 0.04%   |
| 5.15.6.1 | 1         | 0.04%   |
| 5.15.34  | 1         | 0.04%   |
| 5.15.32  | 1         | 0.04%   |
| 5.15.30  | 1         | 0.04%   |
| 5.15.3   | 1         | 0.04%   |
| 5.15.17  | 1         | 0.04%   |
| 5.15.13  | 1         | 0.04%   |
| 5.15.11  | 1         | 0.04%   |
| 5.14.9   | 1         | 0.04%   |
| 5.14.7   | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2252      | 91.1%   |
| 5.15    | 46        | 1.86%   |
| 5.18    | 38        | 1.54%   |
| 5.16    | 32        | 1.29%   |
| 5.14    | 27        | 1.09%   |
| 5.19    | 20        | 0.81%   |
| 5.17    | 18        | 0.73%   |
| 5.13    | 9         | 0.36%   |
| 4.19    | 9         | 0.36%   |
| 5.12    | 6         | 0.24%   |
| 5.11    | 6         | 0.24%   |
| 5.1     | 2         | 0.08%   |
| 4.9     | 2         | 0.08%   |
| 6.0     | 1         | 0.04%   |
| 5.4     | 1         | 0.04%   |
| 5.15.6  | 1         | 0.04%   |
| 3.8     | 1         | 0.04%   |
| 3.10    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2332      | 95.89%  |
| i686   | 98        | 4.03%   |
| armv7l | 2         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 920       | 37.32%  |
| GNOME            | 592       | 24.02%  |
| KDE5             | 281       | 11.4%   |
| XFCE             | 253       | 10.26%  |
| MATE             | 81        | 3.29%   |
| LXDE             | 63        | 2.56%   |
| X-Cinnamon       | 59        | 2.39%   |
| Cinnamon         | 53        | 2.15%   |
| i3               | 33        | 1.34%   |
| LXQt             | 28        | 1.14%   |
| KDE              | 26        | 1.05%   |
| GNOME Flashback  | 21        | 0.85%   |
| lightdm-xsession | 13        | 0.53%   |
| Openbox          | 10        | 0.41%   |
| trinity          | 6         | 0.24%   |
| GNOME Classic    | 5         | 0.2%    |
| Cutefish         | 3         | 0.12%   |
| sway             | 2         | 0.08%   |
| ICEWM            | 2         | 0.08%   |
| Enlightenment    | 2         | 0.08%   |
| DWM              | 2         | 0.08%   |
| Budgie           | 2         | 0.08%   |
| awesome          | 2         | 0.08%   |
| xmonad           | 1         | 0.04%   |
| wmaker-common    | 1         | 0.04%   |
| matchbox         | 1         | 0.04%   |
| jwm              | 1         | 0.04%   |
| default          | 1         | 0.04%   |
| Deepin           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1079      | 43.77%  |
| Unknown | 862       | 34.97%  |
| Wayland | 450       | 18.26%  |
| Tty     | 74        | 3%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1204      | 48.94%  |
| GDM     | 498       | 20.24%  |
| LightDM | 375       | 15.24%  |
| SDDM    | 262       | 10.65%  |
| TDM     | 70        | 2.85%   |
| GDM3    | 44        | 1.79%   |
| XDM     | 3         | 0.12%   |
| SLiM    | 3         | 0.12%   |
| KDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 690       | 28.11%  |
| en_US   | 675       | 27.49%  |
| ru_RU   | 209       | 8.51%   |
| de_DE   | 120       | 4.89%   |
| fr_FR   | 107       | 4.36%   |
| en_GB   | 98        | 3.99%   |
| es_ES   | 85        | 3.46%   |
| it_IT   | 55        | 2.24%   |
| pt_BR   | 53        | 2.16%   |
| pl_PL   | 50        | 2.04%   |
| en_CA   | 24        | 0.98%   |
| es_MX   | 22        | 0.9%    |
| en_AU   | 21        | 0.86%   |
| en_IN   | 14        | 0.57%   |
| zh_CN   | 13        | 0.53%   |
| es_AR   | 12        | 0.49%   |
| C       | 12        | 0.49%   |
| es_CL   | 11        | 0.45%   |
| hu_HU   | 10        | 0.41%   |
| es_VE   | 10        | 0.41%   |
| sv_SE   | 8         | 0.33%   |
| en_IE   | 8         | 0.33%   |
| de_AT   | 8         | 0.33%   |
| nl_NL   | 7         | 0.29%   |
| ja_JP   | 7         | 0.29%   |
| fi_FI   | 7         | 0.29%   |
| tr_TR   | 6         | 0.24%   |
| pt_PT   | 6         | 0.24%   |
| es_CO   | 6         | 0.24%   |
| de_CH   | 6         | 0.24%   |
| nb_NO   | 5         | 0.2%    |
| en_ZA   | 5         | 0.2%    |
| en_SG   | 5         | 0.2%    |
| en_NZ   | 5         | 0.2%    |
| cs_CZ   | 5         | 0.2%    |
| uk_UA   | 4         | 0.16%   |
| es_PE   | 4         | 0.16%   |
| en_DK   | 4         | 0.16%   |
| zh_TW   | 3         | 0.12%   |
| nn_NO   | 3         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1679      | 68.56%  |
| BIOS | 770       | 31.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1414      | 58%     |
| Overlay | 917       | 37.61%  |
| Btrfs   | 65        | 2.67%   |
| Xfs     | 23        | 0.94%   |
| Zfs     | 8         | 0.33%   |
| Tmpfs   | 4         | 0.16%   |
| Unknown | 3         | 0.12%   |
| Ext2    | 2         | 0.08%   |
| Rootfs  | 1         | 0.04%   |
| Ext3    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1689      | 68.71%  |
| MBR     | 418       | 17.01%  |
| Unknown | 351       | 14.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1880      | 76.73%  |
| Yes       | 570       | 23.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1835      | 74.75%  |
| Yes       | 620       | 25.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Apple                          | 559       | 22.99%  |
| Lenovo                         | 484       | 19.91%  |
| Hewlett-Packard                | 324       | 13.33%  |
| Dell                           | 271       | 11.15%  |
| ASUSTek Computer               | 202       | 8.31%   |
| Acer                           | 133       | 5.47%   |
| Google                         | 115       | 4.73%   |
| Aquarius                       | 44        | 1.81%   |
| MSI                            | 36        | 1.48%   |
| Toshiba                        | 30        | 1.23%   |
| Samsung Electronics            | 27        | 1.11%   |
| HUAWEI                         | 22        | 0.9%    |
| Sony                           | 16        | 0.66%   |
| Notebook                       | 12        | 0.49%   |
| Unknown                        | 11        | 0.45%   |
| Packard Bell                   | 9         | 0.37%   |
| Fujitsu                        | 9         | 0.37%   |
| Clevo                          | 6         | 0.25%   |
| Timi                           | 5         | 0.21%   |
| TUXEDO                         | 4         | 0.16%   |
| SLIMBOOK                       | 4         | 0.16%   |
| Panasonic                      | 4         | 0.16%   |
| Medion                         | 4         | 0.16%   |
| LG Electronics                 | 4         | 0.16%   |
| IBM                            | 4         | 0.16%   |
| HONOR                          | 4         | 0.16%   |
| GPU Company                    | 4         | 0.16%   |
| Fujitsu Siemens                | 4         | 0.16%   |
| Alienware                      | 4         | 0.16%   |
| System76                       | 3         | 0.12%   |
| Positivo                       | 3         | 0.12%   |
| PC Specialist                  | 3         | 0.12%   |
| Intel                          | 3         | 0.12%   |
| Gigabyte Technology            | 3         | 0.12%   |
| Avell High Performance         | 3         | 0.12%   |
| Shanghai Zhaoxin Semiconductor | 2         | 0.08%   |
| Razer                          | 2         | 0.08%   |
| Jumper                         | 2         | 0.08%   |
| Insyde                         | 2         | 0.08%   |
| Getac                          | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 305       | 12.55%  |
| Apple MacBookAir7,1                   | 75        | 3.09%   |
| Google Enguarde                       | 74        | 3.04%   |
| Apple MacBookAir7,2                   | 73        | 3%      |
| Apple MacBook2,1                      | 55        | 2.26%   |
| Aquarius NS585                        | 44        | 1.81%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.99%   |
| Apple MacBook4,1                      | 21        | 0.86%   |
| Google Terra                          | 18        | 0.74%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.66%   |
| Unknown                               | 16        | 0.66%   |
| Acer Aspire A315-23                   | 15        | 0.62%   |
| ASUS 1005HA                           | 14        | 0.58%   |
| HP Notebook                           | 11        | 0.45%   |
| HP Pavilion g6                        | 10        | 0.41%   |
| Google Reks                           | 9         | 0.37%   |
| HP EliteBook 8460p                    | 8         | 0.33%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 6         | 0.25%   |
| HP Laptop 15-db1xxx                   | 6         | 0.25%   |
| HP Laptop 15-db0xxx                   | 6         | 0.25%   |
| HP Laptop 15-bw0xx                    | 6         | 0.25%   |
| HP 250 G7 Notebook PC                 | 6         | 0.25%   |
| Dell XPS 13 9310                      | 6         | 0.25%   |
| Dell Latitude E6330                   | 6         | 0.25%   |
| Dell Inspiron 5100                    | 6         | 0.25%   |
| Apple MacBook7,1                      | 6         | 0.25%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 5         | 0.21%   |
| Dell Latitude E6420                   | 5         | 0.21%   |
| Dell Latitude 7480                    | 5         | 0.21%   |
| Acer Aspire A515-56                   | 5         | 0.21%   |
| Samsung 300E4C/300E5C/300E7C          | 4         | 0.16%   |
| Lenovo IdeaPad S145-15API 81V7        | 4         | 0.16%   |
| Lenovo IdeaPad L340-15API 81LW        | 4         | 0.16%   |
| Lenovo IdeaPad 3 15ALC6 82MF          | 4         | 0.16%   |
| Lenovo B50-30 20382                   | 4         | 0.16%   |
| HP Laptop 15s-fq2xxx                  | 4         | 0.16%   |
| HP EliteBook 840 G8 Notebook PC       | 4         | 0.16%   |
| HP EliteBook 840 G3                   | 4         | 0.16%   |
| HP Compaq nx6110 (PZ065UA#ABA)        | 4         | 0.16%   |
| HP 255 G8 Notebook PC                 | 4         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 330       | 13.57%  |
| Apple MacBook5    | 305       | 12.55%  |
| Apple MacBookAir7 | 148       | 6.09%   |
| Dell Latitude     | 98        | 4.03%   |
| Acer Aspire       | 89        | 3.66%   |
| Dell Inspiron     | 85        | 3.5%    |
| Lenovo IdeaPad    | 81        | 3.33%   |
| Google Enguarde   | 74        | 3.04%   |
| HP EliteBook      | 55        | 2.26%   |
| Apple MacBook2    | 55        | 2.26%   |
| HP Pavilion       | 53        | 2.18%   |
| HP Laptop         | 52        | 2.14%   |
| Aquarius NS585    | 44        | 1.81%   |
| HP ProBook        | 43        | 1.77%   |
| Dell XPS          | 34        | 1.4%    |
| ASUS VivoBook     | 26        | 1.07%   |
| Toshiba Satellite | 24        | 0.99%   |
| Dell Vostro       | 24        | 0.99%   |
| Dell Precision    | 22        | 0.9%    |
| HP Compaq         | 21        | 0.86%   |
| Apple MacBook4    | 21        | 0.86%   |
| ASUS ZenBook      | 19        | 0.78%   |
| Google Terra      | 18        | 0.74%   |
| HP 250            | 17        | 0.7%    |
| ASUS ASUS         | 16        | 0.66%   |
| Unknown           | 16        | 0.66%   |
| HP ZBook          | 15        | 0.62%   |
| ASUS 1005HA       | 14        | 0.58%   |
| Acer TravelMate   | 12        | 0.49%   |
| HP Notebook       | 11        | 0.45%   |
| Acer Swift        | 11        | 0.45%   |
| Lenovo ThinkBook  | 10        | 0.41%   |
| ASUS ROG          | 10        | 0.41%   |
| HP ENVY           | 9         | 0.37%   |
| Google Reks       | 9         | 0.37%   |
| Acer Nitro        | 9         | 0.37%   |
| HP Stream         | 8         | 0.33%   |
| HP 255            | 8         | 0.33%   |
| Fujitsu LIFEBOOK  | 8         | 0.33%   |
| Lenovo Legion     | 7         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 359       | 14.77%  |
| 2020    | 242       | 9.95%   |
| 2021    | 236       | 9.71%   |
| 2019    | 235       | 9.67%   |
| 2016    | 164       | 6.75%   |
| 2015    | 160       | 6.58%   |
| 2018    | 133       | 5.47%   |
| 2012    | 131       | 5.39%   |
| 2017    | 119       | 4.9%    |
| 2011    | 117       | 4.81%   |
| 2013    | 97        | 3.99%   |
| 2007    | 90        | 3.7%    |
| 2014    | 88        | 3.62%   |
| 2022    | 81        | 3.33%   |
| 2010    | 69        | 2.84%   |
| 2008    | 66        | 2.71%   |
| 2005    | 16        | 0.66%   |
| 2006    | 13        | 0.53%   |
| 2003    | 8         | 0.33%   |
| 2004    | 4         | 0.16%   |
| Unknown | 2         | 0.08%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2431      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2246      | 92.05%  |
| Enabled  | 194       | 7.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2315      | 95.19%  |
| Yes  | 117       | 4.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 659       | 26.96%  |
| 3.01-4.0    | 477       | 19.52%  |
| 1.01-2.0    | 425       | 17.39%  |
| 16.01-24.0  | 338       | 13.83%  |
| 8.01-16.0   | 279       | 11.42%  |
| 32.01-64.0  | 112       | 4.58%   |
| 2.01-3.0    | 52        | 2.13%   |
| 0.51-1.0    | 46        | 1.88%   |
| 64.01-256.0 | 25        | 1.02%   |
| 24.01-32.0  | 20        | 0.82%   |
| 0.01-0.5    | 10        | 0.41%   |
| Unknown     | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1194      | 47.1%   |
| 2.01-3.0   | 443       | 17.48%  |
| 0.51-1.0   | 278       | 10.97%  |
| 4.01-8.0   | 263       | 10.37%  |
| 3.01-4.0   | 214       | 8.44%   |
| 8.01-16.0  | 67        | 2.64%   |
| 0.01-0.5   | 65        | 2.56%   |
| 16.01-24.0 | 5         | 0.2%    |
| 32.01-64.0 | 2         | 0.08%   |
| 24.01-32.0 | 2         | 0.08%   |
| Unknown    | 2         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2041      | 83.2%   |
| 2      | 354       | 14.43%  |
| 3      | 34        | 1.39%   |
| 0      | 14        | 0.57%   |
| 4      | 7         | 0.29%   |
| 5      | 2         | 0.08%   |
| 7      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1523      | 62.55%  |
| Yes       | 912       | 37.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1924      | 79.01%  |
| No        | 511       | 20.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2400      | 98.68%  |
| No        | 32        | 1.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2037      | 83.45%  |
| No        | 404       | 16.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 930       | 38.11%  |
| Russia      | 216       | 8.85%   |
| Germany     | 172       | 7.05%   |
| France      | 130       | 5.33%   |
| Spain       | 106       | 4.34%   |
| Brazil      | 73        | 2.99%   |
| Poland      | 66        | 2.7%    |
| Italy       | 65        | 2.66%   |
| UK          | 53        | 2.17%   |
| Netherlands | 35        | 1.43%   |
| Canada      | 35        | 1.43%   |
| Mexico      | 29        | 1.19%   |
| Sweden      | 25        | 1.02%   |
| China       | 24        | 0.98%   |
| Australia   | 23        | 0.94%   |
| Argentina   | 22        | 0.9%    |
| Ukraine     | 21        | 0.86%   |
| Switzerland | 21        | 0.86%   |
| India       | 19        | 0.78%   |
| Turkey      | 18        | 0.74%   |
| Austria     | 16        | 0.66%   |
| Norway      | 14        | 0.57%   |
| Czechia     | 14        | 0.57%   |
| Hungary     | 13        | 0.53%   |
| Greece      | 13        | 0.53%   |
| Chile       | 13        | 0.53%   |
| Venezuela   | 12        | 0.49%   |
| Portugal    | 12        | 0.49%   |
| Finland     | 12        | 0.49%   |
| Colombia    | 12        | 0.49%   |
| Japan       | 11        | 0.45%   |
| Belgium     | 11        | 0.45%   |
| Indonesia   | 10        | 0.41%   |
| Romania     | 9         | 0.37%   |
| Ireland     | 9         | 0.37%   |
| Bulgaria    | 9         | 0.37%   |
| New Zealand | 8         | 0.33%   |
| Croatia     | 8         | 0.33%   |
| Thailand    | 7         | 0.29%   |
| Slovenia    | 7         | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 537       | 21.23%  |
| Dover-Foxcroft    | 229       | 9.05%   |
| Voronezh          | 128       | 5.06%   |
| Seville           | 31        | 1.23%   |
| Paris             | 24        | 0.95%   |
| St Petersburg     | 22        | 0.87%   |
| Madrid            | 20        | 0.79%   |
| Berlin            | 19        | 0.75%   |
| Warsaw            | 15        | 0.59%   |
| Moscow            | 14        | 0.55%   |
| Amsterdam         | 14        | 0.55%   |
| Munich            | 13        | 0.51%   |
| Barcelona         | 13        | 0.51%   |
| Vienna            | 12        | 0.47%   |
| London            | 12        | 0.47%   |
| Milan             | 11        | 0.43%   |
| Blizniew          | 11        | 0.43%   |
| Toronto           | 8         | 0.32%   |
| Sydney            | 8         | 0.32%   |
| Lyon              | 8         | 0.32%   |
| Athens            | 8         | 0.32%   |
| Zagreb            | 7         | 0.28%   |
| Sao Paulo         | 7         | 0.28%   |
| Prague            | 7         | 0.28%   |
| Perm              | 7         | 0.28%   |
| Natal             | 7         | 0.28%   |
| Mesa              | 7         | 0.28%   |
| Dublin            | 7         | 0.28%   |
| San Jose          | 6         | 0.24%   |
| Manchester        | 6         | 0.24%   |
| Istanbul          | 6         | 0.24%   |
| Helsinki          | 6         | 0.24%   |
| Frankfurt am Main | 6         | 0.24%   |
| Caracas           | 6         | 0.24%   |
| Brisbane          | 6         | 0.24%   |
| Bengaluru         | 6         | 0.24%   |
| Bangkok           | 6         | 0.24%   |
| Yekaterinburg     | 5         | 0.2%    |
| Turin             | 5         | 0.2%    |
| Leimen            | 5         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 354       | 424    | 12.62%  |
| WDC                       | 282       | 332    | 10.05%  |
| Fujitsu                   | 238       | 241    | 8.48%   |
| Toshiba                   | 230       | 245    | 8.2%    |
| Seagate                   | 227       | 266    | 8.09%   |
| Unknown                   | 195       | 244    | 6.95%   |
| Apple                     | 160       | 185    | 5.7%    |
| Kingston                  | 145       | 177    | 5.17%   |
| SanDisk                   | 122       | 146    | 4.35%   |
| SK hynix                  | 103       | 115    | 3.67%   |
| Crucial                   | 103       | 122    | 3.67%   |
| Hitachi                   | 83        | 94     | 2.96%   |
| A-DATA Technology         | 81        | 150    | 2.89%   |
| Intel                     | 59        | 64     | 2.1%    |
| Micron Technology         | 57        | 58     | 2.03%   |
| HGST                      | 42        | 50     | 1.5%    |
| KIOXIA                    | 30        | 34     | 1.07%   |
| China                     | 20        | 20     | 0.71%   |
| LITEON                    | 17        | 19     | 0.61%   |
| SABRENT                   | 16        | 17     | 0.57%   |
| Transcend                 | 13        | 18     | 0.46%   |
| Phison                    | 13        | 17     | 0.46%   |
| Silicon Motion            | 12        | 13     | 0.43%   |
| Unknown                   | 12        | 12     | 0.43%   |
| PNY                       | 10        | 10     | 0.36%   |
| Intenso                   | 10        | 12     | 0.36%   |
| LITEONIT                  | 9         | 10     | 0.32%   |
| SPCC                      | 8         | 9      | 0.29%   |
| GOODRAM                   | 8         | 9      | 0.29%   |
| Patriot                   | 6         | 6      | 0.21%   |
| Lenovo                    | 6         | 7      | 0.21%   |
| KIOXIA-EXCERIA            | 5         | 6      | 0.18%   |
| JMicron Technology        | 5         | 5      | 0.18%   |
| Apacer                    | 5         | 5      | 0.18%   |
| Union Memory              | 4         | 4      | 0.14%   |
| UMIS                      | 4         | 6      | 0.14%   |
| Team                      | 4         | 4      | 0.14%   |
| SSSTC                     | 4         | 4      | 0.14%   |
| Netac                     | 4         | 4      | 0.14%   |
| Micron/Crucial Technology | 4         | 4      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 201       | 7.01%   |
| Apple SSD AP0128H 121GB              | 75        | 2.62%   |
| Apple SSD SM0128G 121GB              | 70        | 2.44%   |
| Toshiba MK1655GSXF 160GB             | 46        | 1.61%   |
| A-DATA SU800 512GB SSD               | 44        | 1.54%   |
| Toshiba MK1653GSX 160GB              | 43        | 1.5%    |
| Unknown AGND3R  16GB                 | 39        | 1.36%   |
| Seagate ST1000LM035-1RK172 1TB       | 37        | 1.29%   |
| Kingston SA400S37120G 120GB SSD      | 31        | 1.08%   |
| Unknown HAG2e  16GB                  | 30        | 1.05%   |
| Kingston SA400S37240G 240GB SSD      | 27        | 0.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 23        | 0.8%    |
| Unknown SDW16G  16GB                 | 21        | 0.73%   |
| Toshiba MQ01ABF050 500GB             | 20        | 0.7%    |
| Toshiba MQ04ABF100 1TB               | 19        | 0.66%   |
| WDC WD1600BUDT-63DPZY0 160GB         | 16        | 0.56%   |
| Samsung SSD 860 EVO 500GB            | 16        | 0.56%   |
| SABRENT Disk 500GB                   | 16        | 0.56%   |
| HGST HTS721010A9E630 1TB             | 15        | 0.52%   |
| Crucial CT500MX500SSD1 500GB         | 15        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB          | 14        | 0.49%   |
| Unknown MMC Card  32GB               | 13        | 0.45%   |
| Seagate ST500LT012-1DG142 500GB      | 13        | 0.45%   |
| SanDisk SD8SBAT128G1122 128GB SSD    | 13        | 0.45%   |
| Kingston SV300S37A120G 120GB SSD     | 13        | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB         | 12        | 0.42%   |
| Unknown                              | 12        | 0.42%   |
| Toshiba MQ01ABD100 1TB               | 11        | 0.38%   |
| Fujitsu MHY2120BH 120GB              | 11        | 0.38%   |
| WDC WD10SPZX-24Z10 1TB               | 10        | 0.35%   |
| Seagate ST980811AS 80GB              | 10        | 0.35%   |
| Kingston SA400S37480G 480GB SSD      | 10        | 0.35%   |
| Intel SSDPEKNW512G8 512GB            | 10        | 0.35%   |
| Toshiba MK5065GSXF 500GB             | 9         | 0.31%   |
| SanDisk SD8SN8U128G1001 128GB SSD    | 9         | 0.31%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 9         | 0.31%   |
| Samsung MZNTY128HDHP-000L1 128GB SSD | 9         | 0.31%   |
| Intel SSDPEKNW512G8H 512GB           | 9         | 0.31%   |
| Fujitsu MHY2080BH 80GB               | 9         | 0.31%   |
| Crucial CT120BX500SSD1 120GB         | 9         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Fujitsu             | 238       | 241    | 24.69%  |
| Seagate             | 219       | 257    | 22.72%  |
| Toshiba             | 191       | 201    | 19.81%  |
| WDC                 | 152       | 166    | 15.77%  |
| Hitachi             | 83        | 94     | 8.61%   |
| HGST                | 42        | 50     | 4.36%   |
| SABRENT             | 16        | 17     | 1.66%   |
| Samsung Electronics | 10        | 11     | 1.04%   |
| Unknown             | 5         | 8      | 0.52%   |
| USB3.0              | 1         | 1      | 0.1%    |
| Unknown (CF)        | 1         | 1      | 0.1%    |
| SILICONMOTION       | 1         | 1      | 0.1%    |
| Maxone              | 1         | 1      | 0.1%    |
| Intenso             | 1         | 1      | 0.1%    |
| IBM/Hitachi         | 1         | 1      | 0.1%    |
| ASMT109x            | 1         | 1      | 0.1%    |
| ASMT                | 1         | 2      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 167       | 196    | 19.28%  |
| Kingston            | 114       | 145    | 13.16%  |
| SanDisk             | 90        | 110    | 10.39%  |
| Crucial             | 90        | 107    | 10.39%  |
| Apple               | 80        | 84     | 9.24%   |
| A-DATA Technology   | 61        | 119    | 7.04%   |
| WDC                 | 29        | 40     | 3.35%   |
| Micron Technology   | 23        | 23     | 2.66%   |
| China               | 20        | 20     | 2.31%   |
| SK hynix            | 19        | 23     | 2.19%   |
| LITEON              | 15        | 17     | 1.73%   |
| Intel               | 15        | 16     | 1.73%   |
| Transcend           | 12        | 17     | 1.39%   |
| Toshiba             | 12        | 12     | 1.39%   |
| PNY                 | 9         | 9      | 1.04%   |
| LITEONIT            | 9         | 10     | 1.04%   |
| Intenso             | 9         | 11     | 1.04%   |
| SPCC                | 6         | 7      | 0.69%   |
| Patriot             | 6         | 6      | 0.69%   |
| GOODRAM             | 6         | 7      | 0.69%   |
| Team                | 4         | 4      | 0.46%   |
| Netac               | 4         | 4      | 0.46%   |
| Lexar               | 4         | 5      | 0.46%   |
| Apacer              | 4         | 4      | 0.46%   |
| Seagate             | 3         | 3      | 0.35%   |
| Plextor             | 3         | 3      | 0.35%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.35%   |
| ZTC                 | 2         | 3      | 0.23%   |
| Unknown             | 2         | 2      | 0.23%   |
| OCZ                 | 2         | 2      | 0.23%   |
| Kingchuxing         | 2         | 2      | 0.23%   |
| Dogfish             | 2         | 2      | 0.23%   |
| Corsair             | 2         | 2      | 0.23%   |
| ASUS-PHISON         | 2         | 2      | 0.23%   |
| Unknown             | 2         | 2      | 0.23%   |
| XrayDisk            | 1         | 1      | 0.12%   |
| Win Memory          | 1         | 1      | 0.12%   |
| W800SH              | 1         | 1      | 0.12%   |
| Vaseky              | 1         | 2      | 0.12%   |
| Union Memory        | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 936       | 1054   | 34.54%  |
| SSD     | 825       | 1063   | 30.44%  |
| NVMe    | 726       | 888    | 26.79%  |
| MMC     | 202       | 248    | 7.45%   |
| Unknown | 21        | 22     | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1632      | 2042   | 61.98%  |
| NVMe | 723       | 883    | 27.46%  |
| MMC  | 202       | 248    | 7.67%   |
| SAS  | 76        | 102    | 2.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1309      | 1551   | 75.06%  |
| 0.51-1.0   | 396       | 518    | 22.71%  |
| 1.01-2.0   | 27        | 33     | 1.55%   |
| 3.01-4.0   | 8         | 11     | 0.46%   |
| 2.01-3.0   | 2         | 2      | 0.11%   |
| 4.01-10.0  | 2         | 2      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 691       | 27.67%  |
| Unknown        | 636       | 25.47%  |
| 251-500        | 415       | 16.62%  |
| 501-1000       | 251       | 10.05%  |
| 1-20           | 166       | 6.65%   |
| 51-100         | 129       | 5.17%   |
| 1001-2000      | 99        | 3.96%   |
| 21-50          | 62        | 2.48%   |
| 2001-3000      | 27        | 1.08%   |
| More than 3000 | 21        | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 921       | 36.26%  |
| Unknown        | 636       | 25.04%  |
| 21-50          | 267       | 10.51%  |
| 101-250        | 225       | 8.86%   |
| 51-100         | 225       | 8.86%   |
| 251-500        | 139       | 5.47%   |
| 501-1000       | 78        | 3.07%   |
| 1001-2000      | 29        | 1.14%   |
| 0              | 9         | 0.35%   |
| More than 3000 | 8         | 0.31%   |
| 2001-3000      | 3         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 20        | 20     | 8.51%   |
| Toshiba MK1653GSX 160GB                             | 9         | 9      | 3.83%   |
| Toshiba MK1655GSXF 160GB                            | 7         | 7      | 2.98%   |
| Hitachi HTS543216L9SA02 160GB                       | 6         | 6      | 2.55%   |
| Seagate ST9500325AS 500GB                           | 5         | 5      | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 6      | 2.13%   |
| Hitachi HTS542512K9SA00 120GB                       | 5         | 6      | 2.13%   |
| WDC WD1600BUDT-63DPZY0 160GB                        | 4         | 4      | 1.7%    |
| Seagate ST9500420AS 500GB                           | 4         | 4      | 1.7%    |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 3      | 1.28%   |
| Seagate ST500LM000-SSHD-8GB                         | 3         | 3      | 1.28%   |
| Hitachi HTS545050B9A300 500GB                       | 3         | 3      | 1.28%   |
| HGST HTS725050A7E630 500GB                          | 3         | 3      | 1.28%   |
| HGST HTS541010A9E680 1TB                            | 3         | 3      | 1.28%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 3      | 0.85%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 2      | 0.85%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 2      | 0.85%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 0.85%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 2         | 2      | 0.85%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 2         | 2      | 0.85%   |
| SK hynix HFS256G39MND-2300A 256GB SSD               | 2         | 2      | 0.85%   |
| Seagate ST980811AS 80GB                             | 2         | 2      | 0.85%   |
| Seagate ST94811A 40GB                               | 2         | 2      | 0.85%   |
| Seagate ST500LT012-9WS142 500GB                     | 2         | 2      | 0.85%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 2      | 0.85%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 2      | 0.85%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.85%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 2      | 0.85%   |
| Hitachi HTS547575A9E384 752GB                       | 2         | 2      | 0.85%   |
| Hitachi HTS545032B9A300 320GB                       | 2         | 4      | 0.85%   |
| Hitachi HTS542516K9SA00 160GB                       | 2         | 2      | 0.85%   |
| Hitachi HTS541060G9AT00 64GB                        | 2         | 3      | 0.85%   |
| Crucial CT275MX300SSD1 275GB                        | 2         | 2      | 0.85%   |
| WDC WD7500BPVX-22JC3T0 752GB                        | 1         | 1      | 0.43%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1         | 1      | 0.43%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 0.43%   |
| WDC WD5000BPVT-22HXZT1 500GB                        | 1         | 1      | 0.43%   |
| WDC WD5000BPVT-08HXZT1 500GB                        | 1         | 1      | 0.43%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 0.43%   |
| WDC WD1600BUDT-73DPZY0 160GB                        | 1         | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 48     | 18.8%   |
| Hitachi             | 39        | 44     | 16.67%  |
| Toshiba             | 28        | 28     | 11.97%  |
| Fujitsu             | 28        | 28     | 11.97%  |
| WDC                 | 20        | 21     | 8.55%   |
| SK hynix            | 12        | 12     | 5.13%   |
| HGST                | 12        | 13     | 5.13%   |
| Samsung Electronics | 10        | 11     | 4.27%   |
| Micron Technology   | 7         | 7      | 2.99%   |
| Kingston            | 7         | 7      | 2.99%   |
| Intel               | 6         | 7      | 2.56%   |
| SanDisk             | 4         | 5      | 1.71%   |
| Crucial             | 4         | 4      | 1.71%   |
| LITEONIT            | 3         | 3      | 1.28%   |
| LITEON              | 3         | 3      | 1.28%   |
| A-DATA Technology   | 2         | 2      | 0.85%   |
| ShiJi               | 1         | 1      | 0.43%   |
| Lenovo              | 1         | 1      | 0.43%   |
| IBM/Hitachi         | 1         | 1      | 0.43%   |
| GOODRAM             | 1         | 1      | 0.43%   |
| DGM                 | 1         | 1      | 0.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 48     | 25.14%  |
| Hitachi             | 39        | 44     | 22.29%  |
| Toshiba             | 28        | 28     | 16%     |
| Fujitsu             | 28        | 28     | 16%     |
| WDC                 | 20        | 21     | 11.43%  |
| HGST                | 12        | 13     | 6.86%   |
| Samsung Electronics | 3         | 3      | 1.71%   |
| IBM/Hitachi         | 1         | 1      | 0.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 175       | 186    | 74.79%  |
| SSD  | 49        | 52     | 20.94%  |
| NVMe | 10        | 10     | 4.27%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                 | 1         | 1      | 20%     |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 20%     |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 20%     |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB | 1         | 1      | 20%     |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 40%     |
| WDC                 | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1770      | 2215   | 68.84%  |
| Detected | 563       | 806    | 21.9%   |
| Malfunc  | 232       | 248    | 9.02%   |
| Failed   | 5         | 5      | 0.19%   |
| Limited  | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1295      | 48.92%  |
| Nvidia                           | 316       | 11.94%  |
| Samsung Electronics              | 261       | 9.86%   |
| AMD                              | 238       | 8.99%   |
| SanDisk                          | 126       | 4.76%   |
| SK hynix                         | 82        | 3.1%    |
| Apple                            | 80        | 3.02%   |
| Micron Technology                | 34        | 1.28%   |
| Toshiba America Info Systems     | 32        | 1.21%   |
| Kingston Technology Company      | 31        | 1.17%   |
| KIOXIA                           | 29        | 1.1%    |
| ADATA Technology                 | 22        | 0.83%   |
| Silicon Motion                   | 20        | 0.76%   |
| Phison Electronics               | 20        | 0.76%   |
| Micron/Crucial Technology        | 16        | 0.6%    |
| Solid State Storage Technology   | 9         | 0.34%   |
| Union Memory (Shenzhen)          | 7         | 0.26%   |
| Shenzhen Longsys Electronics     | 4         | 0.15%   |
| Realtek Semiconductor            | 4         | 0.15%   |
| Lenovo                           | 4         | 0.15%   |
| Unknown                          | 3         | 0.11%   |
| ULi Electronics                  | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| Lite-On Technology               | 2         | 0.08%   |
| ASMedia Technology               | 2         | 0.08%   |
| Yangtze Memory Technologies      | 1         | 0.04%   |
| VIA Technologies                 | 1         | 0.04%   |
| Silicon Image                    | 1         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.04%   |
| Marvell Technology Group         | 1         | 0.04%   |
| JMicron Technology               | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 AHCI Controller                                                   | 308       | 10.78%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 219       | 7.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 160       | 5.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 138       | 4.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 105       | 3.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 85        | 2.98%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 83        | 2.91%   |
| Intel Volume Management Device NVMe RAID Controller                            | 81        | 2.84%   |
| Apple S1X NVMe Controller                                                      | 76        | 2.66%   |
| Samsung Electronics SATA controller                                            | 75        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 75        | 2.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 66        | 2.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 60        | 2.1%    |
| Samsung NVMe SSD Controller 980                                                | 54        | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 53        | 1.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 49        | 1.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 48        | 1.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 45        | 1.58%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 44        | 1.54%   |
| SK hynix Gold P31 SSD                                                          | 39        | 1.37%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 39        | 1.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 37        | 1.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 35        | 1.23%   |
| Micron Non-Volatile memory controller                                          | 34        | 1.19%   |
| Intel Tiger Lake-LP SATA Controller                                            | 34        | 1.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 30        | 1.05%   |
| Intel SSD 660P Series                                                          | 28        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 28        | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                          | 27        | 0.95%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 25        | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 25        | 0.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 24        | 0.84%   |
| SanDisk Non-Volatile memory controller                                         | 24        | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 23        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 21        | 0.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 0.7%    |
| SK hynix BC511                                                                 | 17        | 0.6%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 17        | 0.6%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 17        | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 17        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1685      | 60.42%  |
| NVMe | 724       | 25.96%  |
| IDE  | 211       | 7.57%   |
| RAID | 169       | 6.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2090      | 85.94%  |
| AMD          | 338       | 13.9%   |
| CentaurHauls | 2         | 0.08%   |
| ARM          | 2         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 307       | 12.61%  |
| Intel Core i5-5250U CPU @ 1.60GHz             | 142       | 5.83%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 85        | 3.49%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 58        | 2.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 54        | 2.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 46        | 1.89%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 45        | 1.85%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 44        | 1.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 32        | 1.31%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 32        | 1.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 26        | 1.07%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 26        | 1.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 25        | 1.03%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 25        | 1.03%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.99%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 23        | 0.94%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 23        | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 22        | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 22        | 0.9%    |
| Intel Atom CPU N270 @ 1.60GHz                 | 22        | 0.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 19        | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 18        | 0.74%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 18        | 0.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 17        | 0.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 17        | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 16        | 0.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 16        | 0.66%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 16        | 0.66%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 15        | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 14        | 0.58%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 14        | 0.58%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 13        | 0.53%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.53%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 13        | 0.53%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 13        | 0.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 12        | 0.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 11        | 0.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 11        | 0.45%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 11        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 583       | 23.97%  |
| Intel Core 2 Duo               | 394       | 16.2%   |
| Intel Core i7                  | 345       | 14.19%  |
| Intel Celeron                  | 217       | 8.92%   |
| Other                          | 194       | 7.98%   |
| Intel Core i3                  | 145       | 5.96%   |
| AMD Ryzen 5                    | 113       | 4.65%   |
| Intel Core 2                   | 60        | 2.47%   |
| Intel Atom                     | 57        | 2.34%   |
| AMD Ryzen 7                    | 48        | 1.97%   |
| Intel Pentium                  | 46        | 1.89%   |
| AMD Ryzen 7 PRO                | 23        | 0.95%   |
| AMD A6                         | 21        | 0.86%   |
| Intel Pentium M                | 17        | 0.7%    |
| Intel Genuine                  | 13        | 0.53%   |
| AMD Ryzen 3                    | 12        | 0.49%   |
| AMD A4                         | 11        | 0.45%   |
| AMD Ryzen 9                    | 10        | 0.41%   |
| Intel Pentium Dual             | 8         | 0.33%   |
| Intel Celeron M                | 8         | 0.33%   |
| AMD E1                         | 8         | 0.33%   |
| AMD A8                         | 8         | 0.33%   |
| Intel Pentium Dual-Core        | 7         | 0.29%   |
| AMD Ryzen 5 PRO                | 7         | 0.29%   |
| AMD A10                        | 7         | 0.29%   |
| Intel Pentium 4                | 6         | 0.25%   |
| AMD A12                        | 6         | 0.25%   |
| Intel Core i9                  | 5         | 0.21%   |
| Intel Xeon                     | 4         | 0.16%   |
| Intel Pentium Silver           | 4         | 0.16%   |
| AMD E2                         | 4         | 0.16%   |
| Intel Pentium Gold             | 3         | 0.12%   |
| Intel Mobile Pentium 4         | 3         | 0.12%   |
| AMD PRO A10                    | 3         | 0.12%   |
| AMD E                          | 3         | 0.12%   |
| AMD C-60                       | 3         | 0.12%   |
| AMD Athlon                     | 3         | 0.12%   |
| Intel Core m3                  | 2         | 0.08%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.08%   |
| AMD Turion 64 Mobile           | 2         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1450      | 59.62%  |
| 4      | 638       | 26.23%  |
| 1      | 117       | 4.81%   |
| 6      | 116       | 4.77%   |
| 8      | 99        | 4.07%   |
| 10     | 5         | 0.21%   |
| 14     | 4         | 0.16%   |
| 12     | 3         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2431      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1465      | 60.26%  |
| 1      | 965       | 39.7%   |
| 4      | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2358      | 97%     |
| 32-bit         | 69        | 2.84%   |
| Unknown        | 4         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 380       | 15.45%  |
| 0x1067a    | 345       | 14.02%  |
| 0x306d4    | 191       | 7.76%   |
| 0x806c1    | 103       | 4.19%   |
| 0x306a9    | 100       | 4.07%   |
| 0x30678    | 92        | 3.74%   |
| 0x206a7    | 86        | 3.5%    |
| 0x806ec    | 75        | 3.05%   |
| 0x806e9    | 69        | 2.8%    |
| 0x6f6      | 60        | 2.44%   |
| 0x806ea    | 54        | 2.2%    |
| 0x406e3    | 50        | 2.03%   |
| 0x40651    | 49        | 1.99%   |
| 0x906eb    | 44        | 1.79%   |
| 0x406c4    | 39        | 1.59%   |
| 0xa0652    | 38        | 1.54%   |
| 0x306c3    | 36        | 1.46%   |
| 0x08108109 | 36        | 1.46%   |
| 0x08600106 | 32        | 1.3%    |
| 0x20655    | 30        | 1.22%   |
| 0x0600611a | 30        | 1.22%   |
| 0x906ea    | 29        | 1.18%   |
| 0x10676    | 29        | 1.18%   |
| 0x08608103 | 29        | 1.18%   |
| 0x0a50000c | 27        | 1.1%    |
| 0x706e5    | 24        | 0.98%   |
| 0x106c2    | 24        | 0.98%   |
| 0x706a8    | 18        | 0.73%   |
| 0x806eb    | 17        | 0.69%   |
| 0x6fd      | 17        | 0.69%   |
| 0x06006705 | 17        | 0.69%   |
| 0x6d8      | 16        | 0.65%   |
| 0x506e3    | 16        | 0.65%   |
| 0x506c9    | 16        | 0.65%   |
| 0x08108102 | 16        | 0.65%   |
| 0x106ca    | 15        | 0.61%   |
| 0x906e9    | 14        | 0.57%   |
| 0x806d1    | 13        | 0.53%   |
| 0x6e8      | 10        | 0.41%   |
| 0xf29      | 9         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Penryn           | 383       | 15.73%  |
| KabyLake         | 377       | 15.48%  |
| Broadwell        | 204       | 8.38%   |
| Silvermont       | 150       | 6.16%   |
| IvyBridge        | 136       | 5.59%   |
| TigerLake        | 133       | 5.46%   |
| Haswell          | 114       | 4.68%   |
| SandyBridge      | 112       | 4.6%    |
| Core             | 98        | 4.02%   |
| Skylake          | 88        | 3.61%   |
| Zen+             | 71        | 2.92%   |
| Zen 2            | 64        | 2.63%   |
| Excavator        | 60        | 2.46%   |
| Westmere         | 53        | 2.18%   |
| Unknown          | 51        | 2.09%   |
| CometLake        | 47        | 1.93%   |
| Bonnell          | 44        | 1.81%   |
| IceLake          | 39        | 1.6%    |
| Zen 3            | 34        | 1.4%    |
| P6               | 34        | 1.4%    |
| Goldmont plus    | 28        | 1.15%   |
| Goldmont         | 19        | 0.78%   |
| Zen              | 16        | 0.66%   |
| Bobcat           | 14        | 0.57%   |
| Puma             | 13        | 0.53%   |
| NetBurst         | 9         | 0.37%   |
| K10 Llano        | 9         | 0.37%   |
| Jaguar           | 7         | 0.29%   |
| Piledriver       | 6         | 0.25%   |
| Tremont          | 5         | 0.21%   |
| K8 Hammer        | 5         | 0.21%   |
| Alderlake Hybrid | 4         | 0.16%   |
| K10              | 3         | 0.12%   |
| Nehalem          | 2         | 0.08%   |
| K8 & K10 hybrid  | 2         | 0.08%   |
| Steamroller      | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1674      | 58.82%  |
| Nvidia                           | 723       | 25.4%   |
| AMD                              | 443       | 15.57%  |
| Zhaoxin                          | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 2         | 0.07%   |
| VIA Technologies                 | 1         | 0.04%   |
| S3 Graphics                      | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 305       | 10.12%  |
| Intel HD Graphics 6000                                                                   | 148       | 4.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 125       | 4.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 121       | 4.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 101       | 3.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 97        | 3.22%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 91        | 3.02%   |
| Intel UHD Graphics 620                                                                   | 73        | 2.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 73        | 2.42%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 67        | 2.22%   |
| AMD Renoir                                                                               | 64        | 2.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 62        | 2.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 61        | 2.02%   |
| Intel HD Graphics 620                                                                    | 57        | 1.89%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 55        | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 53        | 1.76%   |
| Intel HD Graphics 5500                                                                   | 50        | 1.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 48        | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 48        | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 48        | 1.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 46        | 1.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 1.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 41        | 1.36%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 39        | 1.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 1.29%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 39        | 1.29%   |
| AMD Lucienne                                                                             | 33        | 1.09%   |
| AMD Cezanne                                                                              | 31        | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 30        | 1%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 25        | 0.83%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 24        | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 22        | 0.73%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 21        | 0.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 21        | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 20        | 0.66%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 20        | 0.66%   |
| Intel HD Graphics 530                                                                    | 19        | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 0.56%   |
| Intel HD Graphics 630                                                                    | 17        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1295      | 53.18%  |
| 1 x Nvidia      | 365       | 14.99%  |
| Intel + Nvidia  | 319       | 13.1%   |
| 1 x AMD         | 318       | 13.06%  |
| Intel + AMD     | 57        | 2.34%   |
| AMD + Nvidia    | 41        | 1.68%   |
| 2 x AMD         | 27        | 1.11%   |
| Other           | 7         | 0.29%   |
| 1 x Zhaoxin     | 2         | 0.08%   |
| 1 x SiS         | 2         | 0.08%   |
| 1 x VIA         | 1         | 0.04%   |
| 1 x S3 Graphics | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2109      | 86.26%  |
| Unknown     | 199       | 8.14%   |
| Proprietary | 137       | 5.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1732      | 70.64%  |
| 0.01-0.5   | 486       | 19.82%  |
| 1.01-2.0   | 93        | 3.79%   |
| 3.01-4.0   | 64        | 2.61%   |
| 0.51-1.0   | 55        | 2.24%   |
| 5.01-6.0   | 10        | 0.41%   |
| 7.01-8.0   | 7         | 0.29%   |
| 2.01-3.0   | 4         | 0.16%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 558       | 21.85%  |
| AU Optronics            | 387       | 15.15%  |
| BOE                     | 334       | 13.08%  |
| LG Display              | 266       | 10.42%  |
| Chimei Innolux          | 260       | 10.18%  |
| Samsung Electronics     | 171       | 6.7%    |
| Lenovo                  | 54        | 2.11%   |
| Sharp                   | 51        | 2%      |
| Dell                    | 44        | 1.72%   |
| Goldstar                | 42        | 1.64%   |
| Chi Mei Optoelectronics | 38        | 1.49%   |
| BenQ                    | 29        | 1.14%   |
| InfoVision              | 28        | 1.1%    |
| Hewlett-Packard         | 27        | 1.06%   |
| PANDA                   | 24        | 0.94%   |
| HannStar                | 22        | 0.86%   |
| Ancor Communications    | 18        | 0.7%    |
| Unknown                 | 17        | 0.67%   |
| Philips                 | 17        | 0.67%   |
| LG Philips              | 16        | 0.63%   |
| AOC                     | 16        | 0.63%   |
| Iiyama                  | 13        | 0.51%   |
| CSO                     | 12        | 0.47%   |
| Acer                    | 12        | 0.47%   |
| ViewSonic               | 11        | 0.43%   |
| Sony                    | 6         | 0.23%   |
| CPT                     | 5         | 0.2%    |
| Quanta Display          | 4         | 0.16%   |
| Pixio                   | 4         | 0.16%   |
| Panasonic               | 4         | 0.16%   |
| NEC Computers           | 4         | 0.16%   |
| Eizo                    | 4         | 0.16%   |
| Toshiba                 | 3         | 0.12%   |
| TMX                     | 3         | 0.12%   |
| MSI                     | 3         | 0.12%   |
| AGO                     | 3         | 0.12%   |
| ___                     | 2         | 0.08%   |
| SLD                     | 2         | 0.08%   |
| RTK                     | 2         | 0.08%   |
| Mi                      | 2         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                      | 199       | 7.73%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 150       | 5.83%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 52        | 2.02%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 41        | 1.59%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 40        | 1.55%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                      | 35        | 1.36%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 34        | 1.32%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 25        | 0.97%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 23        | 0.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 21        | 0.82%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                      | 21        | 0.82%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 20        | 0.78%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 18        | 0.7%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 16        | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 16        | 0.62%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 15        | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 14        | 0.54%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                      | 13        | 0.51%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 12        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 11        | 0.43%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 11        | 0.43%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 11        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 10        | 0.39%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 9         | 0.35%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 9         | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 9         | 0.35%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 9         | 0.35%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch               | 8         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 8         | 0.31%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                     | 8         | 0.31%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 8         | 0.31%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 8         | 0.31%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 8         | 0.31%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 8         | 0.31%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 8         | 0.31%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 7         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 7         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 7         | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 7         | 0.27%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                   | 6         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 819       | 33.75%  |
| 1366x768 (WXGA)    | 643       | 26.49%  |
| 1280x800 (WXGA)    | 444       | 18.29%  |
| 1440x900 (WXGA+)   | 102       | 4.2%    |
| 1600x900 (HD+)     | 93        | 3.83%   |
| 3840x2160 (4K)     | 60        | 2.47%   |
| 2560x1440 (QHD)    | 47        | 1.94%   |
| 1920x1200 (WUXGA)  | 39        | 1.61%   |
| 1024x600           | 39        | 1.61%   |
| 1280x1024 (SXGA)   | 17        | 0.7%    |
| 2560x1600          | 15        | 0.62%   |
| 2288x1287          | 15        | 0.62%   |
| 1360x768           | 11        | 0.45%   |
| 1024x768 (XGA)     | 11        | 0.45%   |
| 1680x1050 (WSXGA+) | 10        | 0.41%   |
| 3840x2400          | 9         | 0.37%   |
| 2560x1080          | 9         | 0.37%   |
| 2880x1800          | 8         | 0.33%   |
| 2160x1440          | 6         | 0.25%   |
| 3440x1440          | 5         | 0.21%   |
| 1400x1050          | 3         | 0.12%   |
| 3840x1100          | 2         | 0.08%   |
| 3840x1080          | 2         | 0.08%   |
| 3200x1800 (QHD+)   | 2         | 0.08%   |
| 2256x1504          | 2         | 0.08%   |
| 1600x1200          | 2         | 0.08%   |
| Unknown            | 2         | 0.08%   |
| 3840x1600          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |
| 1920x515           | 1         | 0.04%   |
| 1920x1280          | 1         | 0.04%   |
| 1792x768           | 1         | 0.04%   |
| 1024x576           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 758       | 29.74%  |
| 15      | 680       | 26.68%  |
| 14      | 269       | 10.55%  |
| 11      | 220       | 8.63%   |
| 17      | 116       | 4.55%   |
| 12      | 82        | 3.22%   |
| 24      | 77        | 3.02%   |
| 27      | 54        | 2.12%   |
| 23      | 53        | 2.08%   |
| 21      | 46        | 1.8%    |
| 10      | 38        | 1.49%   |
| 19      | 20        | 0.78%   |
| 18      | 20        | 0.78%   |
| 142     | 15        | 0.59%   |
| Unknown | 13        | 0.51%   |
| 31      | 12        | 0.47%   |
| 16      | 10        | 0.39%   |
| 34      | 8         | 0.31%   |
| 25      | 8         | 0.31%   |
| 32      | 7         | 0.27%   |
| 22      | 6         | 0.24%   |
| 29      | 5         | 0.2%    |
| 20      | 5         | 0.2%    |
| 72      | 4         | 0.16%   |
| 84      | 3         | 0.12%   |
| 40      | 3         | 0.12%   |
| 54      | 2         | 0.08%   |
| 52      | 2         | 0.08%   |
| 46      | 2         | 0.08%   |
| 28      | 2         | 0.08%   |
| 8       | 2         | 0.08%   |
| 55      | 1         | 0.04%   |
| 49      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 43      | 1         | 0.04%   |
| 37      | 1         | 0.04%   |
| 33      | 1         | 0.04%   |
| 26      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1117      | 44.13%  |
| 201-300        | 922       | 36.43%  |
| 501-600        | 174       | 6.87%   |
| 351-400        | 134       | 5.29%   |
| 401-500        | 89        | 3.52%   |
| 601-700        | 29        | 1.15%   |
| More than 2000 | 15        | 0.59%   |
| 701-800        | 15        | 0.59%   |
| Unknown        | 13        | 0.51%   |
| 1001-1500      | 10        | 0.4%    |
| 1501-2000      | 7         | 0.28%   |
| 801-900        | 4         | 0.16%   |
| 101-200        | 2         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1586      | 68.66%  |
| 16/10   | 635       | 27.49%  |
| 4/3     | 18        | 0.78%   |
| 5/4     | 17        | 0.74%   |
| 1.00    | 15        | 0.65%   |
| 3/2     | 14        | 0.61%   |
| 21/9    | 11        | 0.48%   |
| Unknown | 5         | 0.22%   |
| 2.65    | 4         | 0.17%   |
| 3.40    | 2         | 0.09%   |
| 32/9    | 1         | 0.04%   |
| 3.73    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 860       | 33.84%  |
| 101-110        | 683       | 26.88%  |
| 51-60          | 222       | 8.74%   |
| 71-80          | 164       | 6.45%   |
| 201-250        | 141       | 5.55%   |
| 121-130        | 94        | 3.7%    |
| 61-70          | 78        | 3.07%   |
| 301-350        | 54        | 2.13%   |
| 251-300        | 39        | 1.53%   |
| 41-50          | 38        | 1.5%    |
| 151-200        | 35        | 1.38%   |
| 351-500        | 30        | 1.18%   |
| 141-150        | 29        | 1.14%   |
| More than 1000 | 27        | 1.06%   |
| Unknown        | 13        | 0.51%   |
| 131-140        | 12        | 0.47%   |
| 501-1000       | 8         | 0.31%   |
| 91-100         | 7         | 0.28%   |
| 111-120        | 5         | 0.2%    |
| 1-40           | 2         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1073      | 42.89%  |
| 101-120       | 909       | 36.33%  |
| 51-100        | 309       | 12.35%  |
| 161-240       | 123       | 4.92%   |
| More than 240 | 44        | 1.76%   |
| 1-50          | 31        | 1.24%   |
| Unknown       | 13        | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1925      | 78.28%  |
| 2     | 304       | 12.36%  |
| 0     | 196       | 7.97%   |
| 3     | 33        | 1.34%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1103      | 28.04%  |
| Realtek Semiconductor             | 972       | 24.71%  |
| Broadcom                          | 490       | 12.46%  |
| Qualcomm Atheros                  | 462       | 11.75%  |
| Nvidia                            | 315       | 8.01%   |
| Broadcom Limited                  | 195       | 4.96%   |
| Marvell Technology Group          | 101       | 2.57%   |
| MediaTek                          | 31        | 0.79%   |
| Ralink                            | 29        | 0.74%   |
| ASIX Electronics                  | 22        | 0.56%   |
| TP-Link                           | 21        | 0.53%   |
| Dell                              | 17        | 0.43%   |
| Samsung Electronics               | 16        | 0.41%   |
| Sierra Wireless                   | 14        | 0.36%   |
| Ralink Technology                 | 11        | 0.28%   |
| Qualcomm                          | 11        | 0.28%   |
| DisplayLink                       | 11        | 0.28%   |
| Xiaomi                            | 9         | 0.23%   |
| Lenovo                            | 9         | 0.23%   |
| JMicron Technology                | 8         | 0.2%    |
| FIBOCOM                           | 6         | 0.15%   |
| Cypress Semiconductor             | 6         | 0.15%   |
| ICS Advent                        | 5         | 0.13%   |
| Huawei Technologies               | 5         | 0.13%   |
| Hewlett-Packard                   | 5         | 0.13%   |
| Ericsson Business Mobile Networks | 5         | 0.13%   |
| ASUSTek Computer                  | 5         | 0.13%   |
| Qualcomm Atheros Communications   | 4         | 0.1%    |
| NetGear                           | 4         | 0.1%    |
| Attansic Technology               | 4         | 0.1%    |
| AMD                               | 4         | 0.1%    |
| Microchip Technology              | 3         | 0.08%   |
| Apple                             | 3         | 0.08%   |
| ULi Electronics                   | 2         | 0.05%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.05%   |
| OPPO Electronics                  | 2         | 0.05%   |
| National Semiconductor            | 2         | 0.05%   |
| Motorola PCS                      | 2         | 0.05%   |
| D-Link                            | 2         | 0.05%   |
| Z-Com                             | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 615       | 13.47%  |
| Nvidia MCP79 Ethernet                                                                 | 309       | 6.77%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 307       | 6.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 154       | 3.37%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 151       | 3.31%   |
| Intel Wireless 7260                                                                   | 120       | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 115       | 2.52%   |
| Intel Wireless 8265 / 8275                                                            | 94        | 2.06%   |
| Intel Wi-Fi 6 AX201                                                                   | 91        | 1.99%   |
| Intel Wi-Fi 6 AX200                                                                   | 85        | 1.86%   |
| Intel Wireless 7265                                                                   | 84        | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 82        | 1.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 77        | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 65        | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 65        | 1.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 58        | 1.27%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 56        | 1.23%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 55        | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 55        | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 53        | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 48        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 48        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 48        | 1.05%   |
| Intel Wireless 8260                                                                   | 46        | 1.01%   |
| Intel Ethernet Connection (4) I219-V                                                  | 39        | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 38        | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 35        | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 31        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 29        | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 26        | 0.57%   |
| Intel Wireless 3165                                                                   | 24        | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 24        | 0.53%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 24        | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 23        | 0.5%    |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 23        | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 22        | 0.48%   |
| Intel Ethernet Connection I219-LM                                                     | 22        | 0.48%   |
| Intel Ethernet Connection I218-LM                                                     | 22        | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 22        | 0.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 21        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1049      | 42.21%  |
| Broadcom                        | 430       | 17.3%   |
| Qualcomm Atheros                | 424       | 17.06%  |
| Realtek Semiconductor           | 273       | 10.99%  |
| Broadcom Limited                | 178       | 7.16%   |
| MediaTek                        | 30        | 1.21%   |
| Ralink                          | 29        | 1.17%   |
| Sierra Wireless                 | 14        | 0.56%   |
| Ralink Technology               | 11        | 0.44%   |
| TP-Link                         | 9         | 0.36%   |
| Dell                            | 9         | 0.36%   |
| FIBOCOM                         | 6         | 0.24%   |
| ASUSTek Computer                | 5         | 0.2%    |
| Qualcomm Atheros Communications | 4         | 0.16%   |
| Qualcomm                        | 4         | 0.16%   |
| NetGear                         | 4         | 0.16%   |
| Z-Com                           | 1         | 0.04%   |
| Wilocity                        | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| 3Com                            | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 307       | 12.31%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 151       | 6.05%   |
| Intel Wireless 7260                                                                   | 120       | 4.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 115       | 4.61%   |
| Intel Wireless 8265 / 8275                                                            | 94        | 3.77%   |
| Intel Wi-Fi 6 AX201                                                                   | 91        | 3.65%   |
| Intel Wi-Fi 6 AX200                                                                   | 85        | 3.41%   |
| Intel Wireless 7265                                                                   | 84        | 3.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 65        | 2.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 65        | 2.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 58        | 2.33%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 55        | 2.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 55        | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 53        | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 48        | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 48        | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 48        | 1.92%   |
| Intel Wireless 8260                                                                   | 46        | 1.84%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 38        | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 35        | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 31        | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 29        | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 26        | 1.04%   |
| Intel Wireless 3165                                                                   | 24        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 24        | 0.96%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 23        | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 21        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 20        | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 20        | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 19        | 0.76%   |
| Intel Wireless 3160                                                                   | 19        | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 19        | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 19        | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 18        | 0.72%   |
| Intel Centrino Advanced-N 6200                                                        | 18        | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 18        | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 14        | 0.56%   |
| Intel Centrino Wireless-N 2230                                                        | 14        | 0.56%   |
| Intel Centrino Ultimate-N 6300                                                        | 14        | 0.56%   |
| Intel Wireless-AC 9260                                                                | 13        | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 869       | 43.45%  |
| Intel                            | 400       | 20%     |
| Nvidia                           | 315       | 15.75%  |
| Marvell Technology Group         | 101       | 5.05%   |
| Qualcomm Atheros                 | 86        | 4.3%    |
| Broadcom                         | 74        | 3.7%    |
| ASIX Electronics                 | 22        | 1.1%    |
| Broadcom Limited                 | 19        | 0.95%   |
| Samsung Electronics              | 16        | 0.8%    |
| TP-Link                          | 12        | 0.6%    |
| DisplayLink                      | 11        | 0.55%   |
| Xiaomi                           | 9         | 0.45%   |
| Lenovo                           | 9         | 0.45%   |
| JMicron Technology               | 8         | 0.4%    |
| Qualcomm                         | 7         | 0.35%   |
| Cypress Semiconductor            | 6         | 0.3%    |
| ICS Advent                       | 5         | 0.25%   |
| Attansic Technology              | 4         | 0.2%    |
| Microchip Technology             | 3         | 0.15%   |
| Huawei Technologies              | 3         | 0.15%   |
| Apple                            | 3         | 0.15%   |
| Silicon Integrated Systems [SiS] | 2         | 0.1%    |
| OPPO Electronics                 | 2         | 0.1%    |
| National Semiconductor           | 2         | 0.1%    |
| Motorola PCS                     | 2         | 0.1%    |
| D-Link                           | 2         | 0.1%    |
| VIA Technologies                 | 1         | 0.05%   |
| Spreadtrum Communications        | 1         | 0.05%   |
| MosChip Semiconductor            | 1         | 0.05%   |
| MediaTek                         | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Google                           | 1         | 0.05%   |
| Davicom Semiconductor            | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 615       | 30.46%  |
| Nvidia MCP79 Ethernet                                             | 309       | 15.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 154       | 7.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 82        | 4.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 77        | 3.81%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 56        | 2.77%   |
| Intel Ethernet Connection (4) I219-V                              | 39        | 1.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 1.19%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 1.14%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 22        | 1.09%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                             | 22        | 1.09%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.94%   |
| Intel Ethernet Connection (6) I219-V                              | 18        | 0.89%   |
| Intel Ethernet Connection (13) I219-V                             | 17        | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 17        | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 0.64%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.59%   |
| Intel Ethernet Connection (10) I219-V                             | 12        | 0.59%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 11        | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 11        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 11        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9         | 0.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 9         | 0.45%   |
| Intel 82566MM Gigabit Network Connection                          | 9         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.4%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 8         | 0.4%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 7         | 0.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.35%   |
| Intel Ethernet Connection (11) I219-LM                            | 7         | 0.35%   |
| Broadcom BCM4401 100Base-T                                        | 7         | 0.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 0.3%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 6         | 0.3%    |
| Nvidia MCP89 Ethernet                                             | 6         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2402      | 54.88%  |
| Ethernet | 1922      | 43.91%  |
| Modem    | 50        | 1.14%   |
| Unknown  | 3         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1883      | 73.67%  |
| Ethernet | 673       | 26.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1752      | 72.01%  |
| 1     | 634       | 26.06%  |
| 3     | 24        | 0.99%   |
| 0     | 22        | 0.9%    |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2057      | 84.06%  |
| Yes  | 390       | 15.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 805       | 39.27%  |
| Apple                           | 549       | 26.78%  |
| Realtek Semiconductor           | 160       | 7.8%    |
| Qualcomm Atheros Communications | 156       | 7.61%   |
| Broadcom                        | 78        | 3.8%    |
| Lite-On Technology              | 72        | 3.51%   |
| IMC Networks                    | 69        | 3.37%   |
| Foxconn / Hon Hai               | 37        | 1.8%    |
| Dell                            | 27        | 1.32%   |
| Cambridge Silicon Radio         | 23        | 1.12%   |
| Hewlett-Packard                 | 18        | 0.88%   |
| Ralink                          | 11        | 0.54%   |
| Realtek                         | 10        | 0.49%   |
| ASUSTek Computer                | 10        | 0.49%   |
| Toshiba                         | 9         | 0.44%   |
| Ralink Technology               | 4         | 0.2%    |
| Taiyo Yuden                     | 3         | 0.15%   |
| Foxconn International           | 3         | 0.15%   |
| MediaTek                        | 2         | 0.1%    |
| Alps Electric                   | 2         | 0.1%    |
| Qcom                            | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 364       | 17.76%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 300       | 14.63%  |
| Intel AX201 Bluetooth                               | 159       | 7.76%   |
| Apple Bluetooth USB Host Controller                 | 150       | 7.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 124       | 6.05%   |
| Realtek Bluetooth Radio                             | 101       | 4.93%   |
| Qualcomm Atheros  Bluetooth Device                  | 100       | 4.88%   |
| Intel AX200 Bluetooth                               | 85        | 4.15%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 3.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 40        | 1.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 30        | 1.46%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23        | 1.12%   |
| IMC Networks Bluetooth Radio                        | 22        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 21        | 1.02%   |
| Apple Bluetooth Host Controller                     | 20        | 0.98%   |
| Lite-On Bluetooth Device                            | 19        | 0.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 18        | 0.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 17        | 0.83%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.78%   |
| IMC Networks Bluetooth Device                       | 15        | 0.73%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 13        | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 13        | 0.63%   |
| Intel AX210 Bluetooth                               | 13        | 0.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 0.59%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 11        | 0.54%   |
| IMC Networks Wireless_Device                        | 11        | 0.54%   |
| Realtek RTL8723B Bluetooth                          | 10        | 0.49%   |
| Realtek Bluetooth Radio                             | 10        | 0.49%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 0.49%   |
| Dell BCM20702A0 Bluetooth Module                    | 10        | 0.49%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.44%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.44%   |
| Intel Bluetooth Device                              | 8         | 0.39%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 8         | 0.39%   |
| Lite-On Wireless_Device                             | 7         | 0.34%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.34%   |
| Dell DW375 Bluetooth Module                         | 7         | 0.34%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 6         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1755      | 63.77%  |
| Nvidia                           | 510       | 18.53%  |
| AMD                              | 366       | 13.3%   |
| C-Media Electronics              | 17        | 0.62%   |
| Logitech                         | 12        | 0.44%   |
| Realtek Semiconductor            | 9         | 0.33%   |
| Generalplus Technology           | 9         | 0.33%   |
| Texas Instruments                | 8         | 0.29%   |
| Lenovo                           | 8         | 0.29%   |
| Plantronics                      | 7         | 0.25%   |
| GN Netcom                        | 6         | 0.22%   |
| Hewlett-Packard                  | 5         | 0.18%   |
| Creative Technology              | 5         | 0.18%   |
| Zhaoxin                          | 2         | 0.07%   |
| ULi Electronics                  | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 2         | 0.07%   |
| Microsoft                        | 2         | 0.07%   |
| Kingston Technology              | 2         | 0.07%   |
| JMTek                            | 2         | 0.07%   |
| CMX Systems                      | 2         | 0.07%   |
| VIA Technologies                 | 1         | 0.04%   |
| Toshiba                          | 1         | 0.04%   |
| Thomann                          | 1         | 0.04%   |
| Tenx Technology                  | 1         | 0.04%   |
| Syntek                           | 1         | 0.04%   |
| SteelSeries ApS                  | 1         | 0.04%   |
| Sennheiser Communications        | 1         | 0.04%   |
| SAVITECH                         | 1         | 0.04%   |
| Samsung Electronics              | 1         | 0.04%   |
| RODE Microphones                 | 1         | 0.04%   |
| Razer USA                        | 1         | 0.04%   |
| Pixart Imaging                   | 1         | 0.04%   |
| Microdia                         | 1         | 0.04%   |
| M-Audio                          | 1         | 0.04%   |
| ESS Technology                   | 1         | 0.04%   |
| Elite Silicon                    | 1         | 0.04%   |
| Elgato Systems                   | 1         | 0.04%   |
| Corsair                          | 1         | 0.04%   |
| AudioQuest                       | 1         | 0.04%   |
| ASUSTek Computer                 | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 High Definition Audio                                                                | 310       | 9.19%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 225       | 6.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 215       | 6.37%   |
| Intel Broadwell-U Audio Controller                                                                | 204       | 6.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 201       | 5.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 162       | 4.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 132       | 3.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 114       | 3.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 106       | 3.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 96        | 2.84%   |
| Intel Cannon Lake PCH cAVS                                                                        | 86        | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 86        | 2.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 86        | 2.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 63        | 1.87%   |
| Intel 8 Series HD Audio Controller                                                                | 63        | 1.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 59        | 1.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 59        | 1.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 59        | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 58        | 1.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 57        | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 55        | 1.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 51        | 1.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 48        | 1.42%   |
| Intel Comet Lake PCH cAVS                                                                         | 45        | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 43        | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 43        | 1.27%   |
| AMD FCH Azalia Controller                                                                         | 42        | 1.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 41        | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 28        | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 27        | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 21        | 0.62%   |
| AMD High Definition Audio Controller                                                              | 21        | 0.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 20        | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 19        | 0.56%   |
| Intel CM238 HD Audio Controller                                                                   | 19        | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 19        | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 0.5%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 16        | 0.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 0.41%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 12        | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 779       | 32.18%  |
| Samsung Electronics | 624       | 25.77%  |
| Micron Technology   | 233       | 9.62%   |
| Kingston            | 146       | 6.03%   |
| Crucial             | 137       | 5.66%   |
| Unknown             | 133       | 5.49%   |
| Elpida              | 81        | 3.35%   |
| A-DATA Technology   | 43        | 1.78%   |
| Ramaxel Technology  | 40        | 1.65%   |
| Nanya Technology    | 29        | 1.2%    |
| Corsair             | 26        | 1.07%   |
| Unknown             | 23        | 0.95%   |
| GOODRAM             | 18        | 0.74%   |
| Unknown (ABCD)      | 13        | 0.54%   |
| Team                | 12        | 0.5%    |
| Smart               | 12        | 0.5%    |
| Transcend           | 8         | 0.33%   |
| G.Skill             | 8         | 0.33%   |
| Patriot             | 5         | 0.21%   |
| ASint Technology    | 4         | 0.17%   |
| Apacer              | 4         | 0.17%   |
| Wilk                | 3         | 0.12%   |
| Smart Brazil        | 3         | 0.12%   |
| Unknown (89F7)      | 2         | 0.08%   |
| Unifosa             | 2         | 0.08%   |
| Teikon              | 2         | 0.08%   |
| Silicon Power       | 2         | 0.08%   |
| Shenzhen WODPOSIT   | 2         | 0.08%   |
| PNY                 | 2         | 0.08%   |
| Neo Forza           | 2         | 0.08%   |
| Infineon            | 2         | 0.08%   |
| Goldkey             | 2         | 0.08%   |
| Avant               | 2         | 0.08%   |
| AMD                 | 2         | 0.08%   |
| 48spaces            | 2         | 0.08%   |
| Unknown (D386)      | 1         | 0.04%   |
| Unknown (08C8)      | 1         | 0.04%   |
| SHARETRONIC         | 1         | 0.04%   |
| Sesame              | 1         | 0.04%   |
| Qimonda             | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 257       | 10.21%  |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 2.7%    |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 61        | 2.42%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 60        | 2.38%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 1.75%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 36        | 1.43%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 1.15%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 27        | 1.07%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 0.99%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.99%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 24        | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.95%   |
| Unknown                                                          | 23        | 0.91%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 22        | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 22        | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 21        | 0.83%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 20        | 0.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 0.68%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 16        | 0.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.64%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s             | 16        | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 15        | 0.6%    |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 15        | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 13        | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 13        | 0.52%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 13        | 0.52%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.48%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 12        | 0.48%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 12        | 0.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 11        | 0.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.44%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 10        | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 761       | 35.54%  |
| DDR3    | 708       | 33.07%  |
| DDR2    | 451       | 21.06%  |
| LPDDR3  | 70        | 3.27%   |
| LPDDR4  | 64        | 2.99%   |
| SDRAM   | 45        | 2.1%    |
| DDR     | 26        | 1.21%   |
| Unknown | 9         | 0.42%   |
| DRAM    | 4         | 0.19%   |
| DDR5    | 2         | 0.09%   |
| LPDDR5  | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1979      | 91.96%  |
| Row Of Chips | 112       | 5.2%    |
| Unknown      | 34        | 1.58%   |
| Chip         | 23        | 1.07%   |
| DIMM         | 4         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 597       | 26.09%  |
| 8192  | 584       | 25.52%  |
| 1024  | 445       | 19.45%  |
| 2048  | 383       | 16.74%  |
| 16384 | 198       | 8.65%   |
| 32768 | 45        | 1.97%   |
| 512   | 26        | 1.14%   |
| 256   | 10        | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 558       | 24.62%  |
| 2667    | 361       | 15.93%  |
| 3200    | 315       | 13.9%   |
| 800     | 311       | 13.72%  |
| 667     | 123       | 5.43%   |
| 2400    | 116       | 5.12%   |
| 1334    | 81        | 3.57%   |
| 2133    | 73        | 3.22%   |
| 1333    | 69        | 3.05%   |
| Unknown | 50        | 2.21%   |
| 4267    | 30        | 1.32%   |
| 1867    | 29        | 1.28%   |
| 1067    | 29        | 1.28%   |
| 3266    | 22        | 0.97%   |
| 4199    | 15        | 0.66%   |
| 533     | 14        | 0.62%   |
| 2048    | 8         | 0.35%   |
| 975     | 8         | 0.35%   |
| 333     | 8         | 0.35%   |
| 266     | 7         | 0.31%   |
| 8400    | 6         | 0.26%   |
| 4266    | 5         | 0.22%   |
| 1066    | 5         | 0.22%   |
| 1866    | 4         | 0.18%   |
| 400     | 4         | 0.18%   |
| 4800    | 3         | 0.13%   |
| 3733    | 2         | 0.09%   |
| 2933    | 2         | 0.09%   |
| 2666    | 2         | 0.09%   |
| 6400    | 1         | 0.04%   |
| 3000    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 1596    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |
| 200     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 31.25%  |
| Xerox               | 4         | 25%     |
| Canon               | 3         | 18.75%  |
| Brother Industries  | 3         | 18.75%  |
| Samsung Electronics | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Xerox B205                          | 4         | 25%     |
| Samsung ML-2010P Mono Laser Printer | 1         | 6.25%   |
| HP LaserJet 1160 series             | 1         | 6.25%   |
| HP LaserJet 1022                    | 1         | 6.25%   |
| HP Ink Tank 110 series              | 1         | 6.25%   |
| HP DeskJet 2620 All-in-One Printer  | 1         | 6.25%   |
| HP DeskJet 2130 series              | 1         | 6.25%   |
| Canon PIXMA MX920 Series            | 1         | 6.25%   |
| Canon LBP3010/LBP3018/LBP3050       | 1         | 6.25%   |
| Canon G3010 series                  | 1         | 6.25%   |
| Brother PT-9500PC                   | 1         | 6.25%   |
| Brother MFC-L2707DW                 | 1         | 6.25%   |
| Brother HL-L2340D series            | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 4         | 66.67%  |
| Seiko Epson | 2         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                       | 2         | 33.33%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 16.67%  |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 16.67%  |
| Canon CanoScan LIDE 25                        | 1         | 16.67%  |
| Canon CanoScan LiDE 220                       | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 401       | 23.64%  |
| IMC Networks                           | 205       | 12.09%  |
| Acer                                   | 181       | 10.67%  |
| Quanta                                 | 177       | 10.44%  |
| Microdia                               | 135       | 7.96%   |
| Realtek Semiconductor                  | 123       | 7.25%   |
| Sunplus Innovation Technology          | 69        | 4.07%   |
| Cheng Uei Precision Industry (Foxlink) | 58        | 3.42%   |
| Suyin                                  | 50        | 2.95%   |
| Lite-On Technology                     | 41        | 2.42%   |
| Syntek                                 | 40        | 2.36%   |
| Luxvisions Innotech Limited            | 38        | 2.24%   |
| Apple                                  | 28        | 1.65%   |
| Logitech                               | 21        | 1.24%   |
| Silicon Motion                         | 17        | 1%      |
| Alcor Micro                            | 14        | 0.83%   |
| Lenovo                                 | 13        | 0.77%   |
| Ricoh                                  | 10        | 0.59%   |
| Z-Star Microelectronics                | 7         | 0.41%   |
| Sonix Technology                       | 7         | 0.41%   |
| Primax Electronics                     | 5         | 0.29%   |
| Importek                               | 5         | 0.29%   |
| ALi                                    | 5         | 0.29%   |
| Y Media                                | 3         | 0.18%   |
| SunplusIT                              | 3         | 0.18%   |
| Samsung Electronics                    | 3         | 0.18%   |
| Intel                                  | 3         | 0.18%   |
| Genesys Logic                          | 3         | 0.18%   |
| Sunplus Technology                     | 2         | 0.12%   |
| OmniVision Technologies                | 2         | 0.12%   |
| Mimaki Engineering                     | 2         | 0.12%   |
| Microsoft                              | 2         | 0.12%   |
| Unknown                                | 1         | 0.06%   |
| U0AS01A-0                              | 1         | 0.06%   |
| ShineTech                              | 1         | 0.06%   |
| Pixart Imaging                         | 1         | 0.06%   |
| Nebraska Furniture Mart                | 1         | 0.06%   |
| MacroSilicon                           | 1         | 0.06%   |
| LG Electronics                         | 1         | 0.06%   |
| Leap Motion                            | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 130       | 7.62%   |
| Microdia Integrated_Webcam_HD                       | 70        | 4.1%    |
| Quanta Chromebook HD Camera                         | 67        | 3.93%   |
| IMC Networks Integrated Camera                      | 64        | 3.75%   |
| Acer BisonCam, NB Pro                               | 51        | 2.99%   |
| Acer Integrated Camera                              | 48        | 2.81%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 44        | 2.58%   |
| Realtek Integrated_Webcam_HD                        | 40        | 2.34%   |
| Chicony HD WebCam                                   | 36        | 2.11%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 24        | 1.41%   |
| Chicony USB2.0 HD UVC WebCam                        | 23        | 1.35%   |
| Syntek Integrated Camera                            | 22        | 1.29%   |
| Sunplus Integrated_Webcam_HD                        | 21        | 1.23%   |
| Quanta HP TrueVision HD Camera                      | 21        | 1.23%   |
| Quanta VGA WebCam                                   | 20        | 1.17%   |
| Chicony HP HD Camera                                | 20        | 1.17%   |
| Quanta HD User Facing                               | 19        | 1.11%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 18        | 1.05%   |
| Lite-On Integrated Camera                           | 16        | 0.94%   |
| Acer SunplusIT Integrated Camera                    | 16        | 0.94%   |
| Chicony Chromebook HD Camera                        | 15        | 0.88%   |
| Realtek USB Camera                                  | 14        | 0.82%   |
| IMC Networks USB 2.0 Camera                         | 13        | 0.76%   |
| Chicony HP Webcam                                   | 12        | 0.7%    |
| Acer Lenovo Integrated Webcam                       | 12        | 0.7%    |
| Suyin HP Truevision HD                              | 11        | 0.64%   |
| Microdia Integrated Webcam                          | 11        | 0.64%   |
| Luxvisions Innotech Limited HP HD Camera            | 11        | 0.64%   |
| Lite-On HP HD Camera                                | 11        | 0.64%   |
| IMC Networks HD Camera                              | 11        | 0.64%   |
| Chicony Integrated Camera (1280x720@30)             | 11        | 0.64%   |
| Chicony HD User Facing                              | 11        | 0.64%   |
| Acer Lenovo EasyCamera                              | 11        | 0.64%   |
| Sunplus HD WebCam                                   | 10        | 0.59%   |
| Quanta HP HD Camera                                 | 10        | 0.59%   |
| Quanta HD Webcam                                    | 10        | 0.59%   |
| Apple Built-in iSight                               | 10        | 0.59%   |
| Realtek USB2.0 HD UVC WebCam                        | 9         | 0.53%   |
| Quanta HP Webcam                                    | 9         | 0.53%   |
| Chicony Lenovo EasyCamera                           | 9         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 129       | 35.73%  |
| Synaptics                  | 107       | 29.64%  |
| Shenzhen Goodix Technology | 53        | 14.68%  |
| AuthenTec                  | 19        | 5.26%   |
| Upek                       | 18        | 4.99%   |
| Elan Microelectronics      | 15        | 4.16%   |
| LighTuning Technology      | 13        | 3.6%    |
| STMicroelectronics         | 7         | 1.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 48        | 13.3%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 37        | 10.25%  |
| Shenzhen Goodix  FingerPrint Device                                        | 29        | 8.03%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 25        | 6.93%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 6.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 5.26%   |
| Unknown                                                                    | 18        | 4.99%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 4.43%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 3.32%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 3.32%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 3.05%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 2.77%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.77%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.49%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 1.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.66%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.39%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.39%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 1.39%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.39%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.39%   |
| LighTuning EgisTec_ES603                                                   | 5         | 1.39%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.39%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.11%   |
| Validity Sensors VFS491                                                    | 3         | 0.83%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.83%   |
| Synaptics  WBDI                                                            | 3         | 0.83%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.55%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.55%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.55%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.55%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.55%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.55%   |
| AuthenTec AES2810                                                          | 2         | 0.55%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.55%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.55%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.28%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.28%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.28%   |
| AuthenTec AES1600                                                          | 1         | 0.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 65        | 36.31%  |
| Broadcom                  | 60        | 33.52%  |
| Upek                      | 19        | 10.61%  |
| O2 Micro                  | 13        | 7.26%   |
| Lenovo                    | 11        | 6.15%   |
| Yubico.com                | 2         | 1.12%   |
| Gemalto (was Gemplus)     | 2         | 1.12%   |
| Aladdin Knowledge Systems | 2         | 1.12%   |
| SCM Microsystems          | 1         | 0.56%   |
| OmniKey                   | 1         | 0.56%   |
| Clay Logic                | 1         | 0.56%   |
| Cherry                    | 1         | 0.56%   |
| C3PO                      | 1         | 0.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 64        | 35.75%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 19        | 10.61%  |
| Broadcom BCM5880 Secure Applications Processor                               | 19        | 10.61%  |
| Broadcom 58200                                                               | 18        | 10.06%  |
| Broadcom 5880                                                                | 15        | 8.38%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 6.15%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 6.15%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 3.91%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.12%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.12%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.12%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.56%   |
| OmniKey CardMan 4321                                                         | 1         | 0.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.56%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.56%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.56%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.56%   |
| C3PO LTC31v2                                                                 | 1         | 0.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.56%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1434      | 58.39%  |
| 1     | 797       | 32.45%  |
| 2     | 177       | 7.21%   |
| 3     | 42        | 1.71%   |
| 4     | 4         | 0.16%   |
| 6     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 359       | 28.67%  |
| Graphics card            | 338       | 27%     |
| Multimedia controller    | 182       | 14.54%  |
| Chipcard                 | 162       | 12.94%  |
| Net/wireless             | 105       | 8.39%   |
| Bluetooth                | 27        | 2.16%   |
| Storage                  | 17        | 1.36%   |
| Communication controller | 17        | 1.36%   |
| Card reader              | 14        | 1.12%   |
| Camera                   | 10        | 0.8%    |
| Sound                    | 5         | 0.4%    |
| Network                  | 4         | 0.32%   |
| Net/ethernet             | 3         | 0.24%   |
| Modem                    | 3         | 0.24%   |
| Unassigned class         | 2         | 0.16%   |
| Flash memory             | 2         | 0.16%   |
| Tv card                  | 1         | 0.08%   |
| Firewire controller      | 1         | 0.08%   |

