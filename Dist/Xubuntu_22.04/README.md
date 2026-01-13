Xubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Xubuntu_22.04/Notebook/README.md).

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

Total: 1297

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | T100HAN                     | Notebook    | [c7df26701e](https://linux-hardware.org/?probe=c7df26701e) | Jan 03, 2026 |
| ASRock        | B450 Pro4                   | Desktop     | [51f2950a0d](https://linux-hardware.org/?probe=51f2950a0d) | Dec 25, 2025 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [bb9dd8e4e2](https://linux-hardware.org/?probe=bb9dd8e4e2) | Dec 23, 2025 |
| Acer          | Aspire E5-771G              | Notebook    | [35d04177f4](https://linux-hardware.org/?probe=35d04177f4) | Dec 23, 2025 |
| AZW           | MINI S                      | Mini pc     | [591c5d32cc](https://linux-hardware.org/?probe=591c5d32cc) | Dec 17, 2025 |
| Dell          | 0WR7PY A03                  | Desktop     | [7b32997cf2](https://linux-hardware.org/?probe=7b32997cf2) | Dec 10, 2025 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3ca7bf1a68](https://linux-hardware.org/?probe=3ca7bf1a68) | Nov 16, 2025 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [1bdbfd82d8](https://linux-hardware.org/?probe=1bdbfd82d8) | Nov 16, 2025 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [33a8fe694d](https://linux-hardware.org/?probe=33a8fe694d) | Oct 29, 2025 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [261705e25b](https://linux-hardware.org/?probe=261705e25b) | Oct 07, 2025 |
| Dell          | Latitude E4300              | Notebook    | [c5e0ea5ed3](https://linux-hardware.org/?probe=c5e0ea5ed3) | Oct 07, 2025 |
| Dell          | 06FW8M A05                  | Server      | [0aaa4ba9d5](https://linux-hardware.org/?probe=0aaa4ba9d5) | Sep 28, 2025 |
| Apple         | MacBook6,1                  | Notebook    | [b2d237ff99](https://linux-hardware.org/?probe=b2d237ff99) | Sep 26, 2025 |
| Dell          | 0NT78X A03                  | Server      | [f29f76c333](https://linux-hardware.org/?probe=f29f76c333) | Sep 22, 2025 |
| Dell          | G3 3579                     | Notebook    | [08f64d0e91](https://linux-hardware.org/?probe=08f64d0e91) | Sep 18, 2025 |
| Toshiba       | TECRA A50-A                 | Notebook    | [a4afe1b0c8](https://linux-hardware.org/?probe=a4afe1b0c8) | Sep 12, 2025 |
| Medion        | H110H4-EM                   | Desktop     | [9736aa70f5](https://linux-hardware.org/?probe=9736aa70f5) | Sep 09, 2025 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [b8498e312f](https://linux-hardware.org/?probe=b8498e312f) | Aug 29, 2025 |
| HP            | ZBook 17 G3                 | Notebook    | [94181a63aa](https://linux-hardware.org/?probe=94181a63aa) | Aug 29, 2025 |
| AZW           | MINI S                      | Mini pc     | [e5da2614e9](https://linux-hardware.org/?probe=e5da2614e9) | Aug 19, 2025 |
| OrangePi      | Zero3                       | Soc         | [5f5a8e90fd](https://linux-hardware.org/?probe=5f5a8e90fd) | Aug 18, 2025 |
| AZW           | SER V1.0                    | Desktop     | [db19e257b7](https://linux-hardware.org/?probe=db19e257b7) | Aug 01, 2025 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [c4ad575646](https://linux-hardware.org/?probe=c4ad575646) | Jul 30, 2025 |
| Acer          | Aspire one 1-431            | Notebook    | [f7c14c5561](https://linux-hardware.org/?probe=f7c14c5561) | Jul 28, 2025 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [f055011fd7](https://linux-hardware.org/?probe=f055011fd7) | Jul 22, 2025 |
| Acer          | Aspire 7739ZG               | Notebook    | [56a56c8810](https://linux-hardware.org/?probe=56a56c8810) | Jul 21, 2025 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [cd36452cb2](https://linux-hardware.org/?probe=cd36452cb2) | Jul 21, 2025 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [f76b354b32](https://linux-hardware.org/?probe=f76b354b32) | Jul 21, 2025 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [a67a7af07b](https://linux-hardware.org/?probe=a67a7af07b) | Jul 10, 2025 |
| Shenzhen M... | F7BSW                       | Mini pc     | [550c9f392d](https://linux-hardware.org/?probe=550c9f392d) | Jun 11, 2025 |
| Shenzhen M... | F7BSW                       | Mini pc     | [62eb3d13a6](https://linux-hardware.org/?probe=62eb3d13a6) | Jun 11, 2025 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [eb0fbb49a2](https://linux-hardware.org/?probe=eb0fbb49a2) | Jun 10, 2025 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [ae7ba9f7c6](https://linux-hardware.org/?probe=ae7ba9f7c6) | May 30, 2025 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [3e216b1761](https://linux-hardware.org/?probe=3e216b1761) | May 29, 2025 |
| Dell          | 0K240Y A02                  | Desktop     | [8f1ec741a0](https://linux-hardware.org/?probe=8f1ec741a0) | May 28, 2025 |
| Dell          | 0K240Y A02                  | Desktop     | [c9c1fb73ae](https://linux-hardware.org/?probe=c9c1fb73ae) | May 28, 2025 |
| Gigabyte      | N3050ND3H                   | Desktop     | [3745e66d2c](https://linux-hardware.org/?probe=3745e66d2c) | May 26, 2025 |
| Gigabyte      | N3050ND3H                   | Desktop     | [2ef93a7f1c](https://linux-hardware.org/?probe=2ef93a7f1c) | May 25, 2025 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [2acb7680de](https://linux-hardware.org/?probe=2acb7680de) | May 23, 2025 |
| Dell          | 0X8DXD A01                  | Desktop     | [f98ffeddc7](https://linux-hardware.org/?probe=f98ffeddc7) | May 12, 2025 |
| HP            | 82DD                        | All in one  | [4173108e63](https://linux-hardware.org/?probe=4173108e63) | May 10, 2025 |
| Dell          | Inspiron 7520               | Notebook    | [59a05dbbfe](https://linux-hardware.org/?probe=59a05dbbfe) | May 02, 2025 |
| Dell          | 09D2HH A00                  | Desktop     | [ef417bed29](https://linux-hardware.org/?probe=ef417bed29) | Apr 28, 2025 |
| Lenovo        | ThinkBook 16 G5+ APH 21K... | Notebook    | [3e10ae4c6d](https://linux-hardware.org/?probe=3e10ae4c6d) | Apr 22, 2025 |
| Dell          | 04YP6J A02                  | Desktop     | [dc171a8d29](https://linux-hardware.org/?probe=dc171a8d29) | Apr 18, 2025 |
| HP            | Pavilion Laptop 14-bk0xx    | Notebook    | [7721b6732c](https://linux-hardware.org/?probe=7721b6732c) | Apr 16, 2025 |
| ATOPNUC       | AG40                        | Mini pc     | [6900ee8624](https://linux-hardware.org/?probe=6900ee8624) | Apr 10, 2025 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | Notebook    | [aea006a546](https://linux-hardware.org/?probe=aea006a546) | Apr 08, 2025 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | Notebook    | [e6778c5cbf](https://linux-hardware.org/?probe=e6778c5cbf) | Apr 08, 2025 |
| Gigabyte      | MZBSWAP-K4                  | Desktop     | [7d6782eaa8](https://linux-hardware.org/?probe=7d6782eaa8) | Apr 07, 2025 |
| Dell          | Latitude 5411               | Notebook    | [50e44370d5](https://linux-hardware.org/?probe=50e44370d5) | Apr 05, 2025 |
| Dell          | 0GN6JF A01                  | Desktop     | [0f4b7ea2e2](https://linux-hardware.org/?probe=0f4b7ea2e2) | Mar 30, 2025 |
| Radxa         | ROCK Pi 4A                  | Soc         | [601a6ab861](https://linux-hardware.org/?probe=601a6ab861) | Mar 28, 2025 |
| Radxa         | ROCK Pi 4A                  | Soc         | [2fe0ea0895](https://linux-hardware.org/?probe=2fe0ea0895) | Mar 28, 2025 |
| Intel         | H81U                        | Notebook    | [d04b5fb57d](https://linux-hardware.org/?probe=d04b5fb57d) | Mar 21, 2025 |
| MSI           | Modern 15 A5M               | Notebook    | [8e70dd34ba](https://linux-hardware.org/?probe=8e70dd34ba) | Mar 21, 2025 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [ce9c81b769](https://linux-hardware.org/?probe=ce9c81b769) | Mar 17, 2025 |
| Acer          | Predator G3-605             | Desktop     | [782bedfef3](https://linux-hardware.org/?probe=782bedfef3) | Mar 16, 2025 |
| Unknown       | Unknown                     | Soc         | [362e708577](https://linux-hardware.org/?probe=362e708577) | Mar 15, 2025 |
| PC Special... | NH5x_7xDPx                  | Notebook    | [46ac90a9c2](https://linux-hardware.org/?probe=46ac90a9c2) | Mar 07, 2025 |
| Dell          | 07N90W A01                  | Desktop     | [cdfc04728d](https://linux-hardware.org/?probe=cdfc04728d) | Feb 24, 2025 |
| ASUSTek       | GL502VM                     | Notebook    | [82f8d204e4](https://linux-hardware.org/?probe=82f8d204e4) | Feb 23, 2025 |
| ASUSTek       | PN50                        | Mini pc     | [def3f65fdb](https://linux-hardware.org/?probe=def3f65fdb) | Feb 22, 2025 |
| Lenovo        | G550 20023                  | Notebook    | [f9f8de8a01](https://linux-hardware.org/?probe=f9f8de8a01) | Feb 19, 2025 |
| HP            | Pavilion Laptop 14-bk0xx    | Notebook    | [6432ee069f](https://linux-hardware.org/?probe=6432ee069f) | Feb 14, 2025 |
| Dell          | Inspiron 15 3520            | Notebook    | [77b4da5e12](https://linux-hardware.org/?probe=77b4da5e12) | Feb 07, 2025 |
| Fujitsu Si... | AMILO La1703                | Notebook    | [30d37a66f4](https://linux-hardware.org/?probe=30d37a66f4) | Feb 05, 2025 |
| Acer          | Aspire A315-33              | Notebook    | [5e8c75e023](https://linux-hardware.org/?probe=5e8c75e023) | Jan 29, 2025 |
| Acer          | Aspire A315-33              | Notebook    | [c4f546783c](https://linux-hardware.org/?probe=c4f546783c) | Jan 29, 2025 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [d16217a656](https://linux-hardware.org/?probe=d16217a656) | Jan 28, 2025 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [20dfac74b1](https://linux-hardware.org/?probe=20dfac74b1) | Jan 25, 2025 |
| Sony          | VPCS13L9E                   | Notebook    | [5cbe2b53cf](https://linux-hardware.org/?probe=5cbe2b53cf) | Jan 25, 2025 |
| Unknown       | CreateBest ZB3588           | Soc         | [f7f2b29a0d](https://linux-hardware.org/?probe=f7f2b29a0d) | Jan 15, 2025 |
| Dell          | 09WH54 A00                  | Desktop     | [d1332901ea](https://linux-hardware.org/?probe=d1332901ea) | Jan 13, 2025 |
| Intel         | D54250WYK H13922-303        | Desktop     | [dc4e6b8688](https://linux-hardware.org/?probe=dc4e6b8688) | Jan 13, 2025 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [e27afefb0e](https://linux-hardware.org/?probe=e27afefb0e) | Jan 12, 2025 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [8591f7eb34](https://linux-hardware.org/?probe=8591f7eb34) | Jan 10, 2025 |
| Dell          | Inspiron 15 3515            | Notebook    | [ca2cc3e4ae](https://linux-hardware.org/?probe=ca2cc3e4ae) | Jan 02, 2025 |
| Lenovo        | ThinkPad R61 8918DFG        | Notebook    | [a7030c8afc](https://linux-hardware.org/?probe=a7030c8afc) | Dec 29, 2024 |
| ASUSTek       | X541UVK                     | Notebook    | [e84d6fc1f1](https://linux-hardware.org/?probe=e84d6fc1f1) | Dec 26, 2024 |
| HP            | Pavilion g7                 | Notebook    | [349ddf33a4](https://linux-hardware.org/?probe=349ddf33a4) | Dec 23, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [1e6b1c0777](https://linux-hardware.org/?probe=1e6b1c0777) | Dec 23, 2024 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [83a10df0af](https://linux-hardware.org/?probe=83a10df0af) | Dec 16, 2024 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [65a80c8ae1](https://linux-hardware.org/?probe=65a80c8ae1) | Dec 15, 2024 |
| Packard Be... | EasyNote MH36               | Notebook    | [f7069c0d8b](https://linux-hardware.org/?probe=f7069c0d8b) | Dec 09, 2024 |
| HP            | 15                          | Notebook    | [9abcf874e9](https://linux-hardware.org/?probe=9abcf874e9) | Nov 28, 2024 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [61e673309f](https://linux-hardware.org/?probe=61e673309f) | Nov 27, 2024 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [0d40b44d15](https://linux-hardware.org/?probe=0d40b44d15) | Nov 27, 2024 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [9b1d667645](https://linux-hardware.org/?probe=9b1d667645) | Nov 23, 2024 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [416650beef](https://linux-hardware.org/?probe=416650beef) | Nov 23, 2024 |
| Pegatron      | 2AC2                        | Desktop     | [24efcbf074](https://linux-hardware.org/?probe=24efcbf074) | Nov 23, 2024 |
| Dell          | 051FJ8 A02                  | Desktop     | [66b7975345](https://linux-hardware.org/?probe=66b7975345) | Nov 20, 2024 |
| HP            | 15                          | Notebook    | [ae229ea058](https://linux-hardware.org/?probe=ae229ea058) | Nov 19, 2024 |
| Lenovo        | ThinkPad A475 20KMS0MR00    | Notebook    | [57d3147d55](https://linux-hardware.org/?probe=57d3147d55) | Nov 18, 2024 |
| Lenovo        | ThinkPad A475 20KMS0MR00    | Notebook    | [54c2687b9b](https://linux-hardware.org/?probe=54c2687b9b) | Nov 16, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [556af0bd7a](https://linux-hardware.org/?probe=556af0bd7a) | Nov 14, 2024 |
| Dell          | Latitude 7340               | Notebook    | [ad73fedd66](https://linux-hardware.org/?probe=ad73fedd66) | Nov 13, 2024 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [07bf1053a6](https://linux-hardware.org/?probe=07bf1053a6) | Nov 12, 2024 |
| Acer          | Swift SF314-512             | Notebook    | [78edb25f37](https://linux-hardware.org/?probe=78edb25f37) | Nov 09, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [09bd105ca4](https://linux-hardware.org/?probe=09bd105ca4) | Nov 09, 2024 |
| Lenovo        | ThinkPad T530 2429A94       | Notebook    | [65b19adb3c](https://linux-hardware.org/?probe=65b19adb3c) | Oct 30, 2024 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [6a3c1dda1a](https://linux-hardware.org/?probe=6a3c1dda1a) | Oct 30, 2024 |
| HP            | 3029h                       | Desktop     | [83bfbe4bbe](https://linux-hardware.org/?probe=83bfbe4bbe) | Oct 28, 2024 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [7c3872493b](https://linux-hardware.org/?probe=7c3872493b) | Oct 24, 2024 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [73dfa63259](https://linux-hardware.org/?probe=73dfa63259) | Oct 23, 2024 |
| AZW           | GK mini                     | Mini pc     | [8bcf6d53a1](https://linux-hardware.org/?probe=8bcf6d53a1) | Oct 17, 2024 |
| Google        | Candy                       | Notebook    | [0657332520](https://linux-hardware.org/?probe=0657332520) | Oct 17, 2024 |
| Dell          | Latitude 3540               | Notebook    | [5ab18fa675](https://linux-hardware.org/?probe=5ab18fa675) | Oct 15, 2024 |
| ASRock        | Z370 Pro4                   | Desktop     | [8be5788f0f](https://linux-hardware.org/?probe=8be5788f0f) | Oct 14, 2024 |
| Google        | Reks                        | Notebook    | [7654a0cc4c](https://linux-hardware.org/?probe=7654a0cc4c) | Oct 12, 2024 |
| ASUSTek       | P5E                         | Desktop     | [cdbc95990e](https://linux-hardware.org/?probe=cdbc95990e) | Oct 11, 2024 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [c7823c9fd3](https://linux-hardware.org/?probe=c7823c9fd3) | Oct 05, 2024 |
| Dell          | 0RY007                      | Desktop     | [aef3641a97](https://linux-hardware.org/?probe=aef3641a97) | Oct 03, 2024 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [b60d9ddc7c](https://linux-hardware.org/?probe=b60d9ddc7c) | Oct 01, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [50a08b9a0d](https://linux-hardware.org/?probe=50a08b9a0d) | Oct 01, 2024 |
| Alienware     | M11xR3                      | Notebook    | [640a59c53a](https://linux-hardware.org/?probe=640a59c53a) | Sep 25, 2024 |
| ASRock        | H510 Pro BTC+               | Desktop     | [a1ae1e84a3](https://linux-hardware.org/?probe=a1ae1e84a3) | Sep 18, 2024 |
| Supermicro    | X8DTN                       | Server      | [3c6d5d3b61](https://linux-hardware.org/?probe=3c6d5d3b61) | Sep 13, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [12bdde9ebc](https://linux-hardware.org/?probe=12bdde9ebc) | Sep 11, 2024 |
| Gigabyte      | Z87-HD3                     | Desktop     | [5ce754d8ac](https://linux-hardware.org/?probe=5ce754d8ac) | Sep 08, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [7c9759b951](https://linux-hardware.org/?probe=7c9759b951) | Sep 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [76a130d405](https://linux-hardware.org/?probe=76a130d405) | Sep 07, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f896396077](https://linux-hardware.org/?probe=f896396077) | Sep 04, 2024 |
| Dell          | Latitude 5300               | Notebook    | [2bb6cd074d](https://linux-hardware.org/?probe=2bb6cd074d) | Sep 04, 2024 |
| Packard Be... | IMEDIA S2185                | Desktop     | [2881d2dd1c](https://linux-hardware.org/?probe=2881d2dd1c) | Sep 04, 2024 |
| Dell          | 0P658H A05                  | Server      | [c5009a5fee](https://linux-hardware.org/?probe=c5009a5fee) | Sep 04, 2024 |
| HP            | Pavilion dm4                | Notebook    | [cadd83c1c1](https://linux-hardware.org/?probe=cadd83c1c1) | Sep 04, 2024 |
| MSI           | H81M-P33                    | Desktop     | [e042807dc2](https://linux-hardware.org/?probe=e042807dc2) | Sep 01, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [89910d636e](https://linux-hardware.org/?probe=89910d636e) | Aug 31, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [af2f92a36b](https://linux-hardware.org/?probe=af2f92a36b) | Aug 31, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [bea9bcf4a7](https://linux-hardware.org/?probe=bea9bcf4a7) | Aug 29, 2024 |
| Acer          | Aspire E1-571               | Notebook    | [3d7216a60a](https://linux-hardware.org/?probe=3d7216a60a) | Aug 21, 2024 |
| HP            | Pavilion dv6                | Notebook    | [d66efbf40c](https://linux-hardware.org/?probe=d66efbf40c) | Aug 20, 2024 |
| Biostar       | B350ET2                     | Desktop     | [435502bdae](https://linux-hardware.org/?probe=435502bdae) | Aug 17, 2024 |
| Biostar       | B350ET2                     | Desktop     | [1c9548b133](https://linux-hardware.org/?probe=1c9548b133) | Aug 17, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [ff742887ee](https://linux-hardware.org/?probe=ff742887ee) | Aug 17, 2024 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [326191891a](https://linux-hardware.org/?probe=326191891a) | Aug 17, 2024 |
| ASUSTek       | H87-PRO                     | Desktop     | [2df8b23618](https://linux-hardware.org/?probe=2df8b23618) | Aug 15, 2024 |
| MSI           | Z77A-G41                    | Desktop     | [85eb1d0f02](https://linux-hardware.org/?probe=85eb1d0f02) | Aug 09, 2024 |
| Dell          | Latitude 3540               | Notebook    | [c211e993f2](https://linux-hardware.org/?probe=c211e993f2) | Aug 07, 2024 |
| Dell          | Latitude 3540               | Notebook    | [5694031221](https://linux-hardware.org/?probe=5694031221) | Aug 07, 2024 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [b208c323dd](https://linux-hardware.org/?probe=b208c323dd) | Aug 07, 2024 |
| Unknown       | axera,ax650x                | Soc         | [91d750536e](https://linux-hardware.org/?probe=91d750536e) | Aug 05, 2024 |
| HP            | 1790                        | Desktop     | [8104bc2455](https://linux-hardware.org/?probe=8104bc2455) | Aug 03, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [5914942e68](https://linux-hardware.org/?probe=5914942e68) | Jul 31, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [1d1515aa10](https://linux-hardware.org/?probe=1d1515aa10) | Jul 28, 2024 |
| Dell          | 0P658H A05                  | Server      | [5e284b9d77](https://linux-hardware.org/?probe=5e284b9d77) | Jul 28, 2024 |
| ASRock        | N68-S3 UCC                  | Desktop     | [cc2c1f8fd5](https://linux-hardware.org/?probe=cc2c1f8fd5) | Jul 27, 2024 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [7be453f1ba](https://linux-hardware.org/?probe=7be453f1ba) | Jul 27, 2024 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [475f183aa6](https://linux-hardware.org/?probe=475f183aa6) | Jul 27, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [7dbae4d4d0](https://linux-hardware.org/?probe=7dbae4d4d0) | Jul 26, 2024 |
| OrangePi      | Zero2 W                     | Soc         | [afa5a07c4b](https://linux-hardware.org/?probe=afa5a07c4b) | Jul 25, 2024 |
| ASRock        | N68-S3 UCC                  | Desktop     | [ebee0b577f](https://linux-hardware.org/?probe=ebee0b577f) | Jul 23, 2024 |
| Dell          | 0F5C5X A00                  | Desktop     | [006ce103a9](https://linux-hardware.org/?probe=006ce103a9) | Jul 18, 2024 |
| ASUSTek       | X555YI                      | Notebook    | [5b525693e5](https://linux-hardware.org/?probe=5b525693e5) | Jul 17, 2024 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [54c2bc8ab6](https://linux-hardware.org/?probe=54c2bc8ab6) | Jul 17, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [75dbf5b437](https://linux-hardware.org/?probe=75dbf5b437) | Jul 16, 2024 |
| Dell          | 0XKH0D A02                  | Desktop     | [0781f0c28d](https://linux-hardware.org/?probe=0781f0c28d) | Jul 12, 2024 |
| Dell          | 0XKH0D A02                  | Desktop     | [c2611748dd](https://linux-hardware.org/?probe=c2611748dd) | Jul 12, 2024 |
| Gigabyte      | B550M K                     | Desktop     | [ea2aa30897](https://linux-hardware.org/?probe=ea2aa30897) | Jul 11, 2024 |
| Gigabyte      | B85-HD3                     | Desktop     | [ce9e0e79fb](https://linux-hardware.org/?probe=ce9e0e79fb) | Jul 10, 2024 |
| Acer          | Aspire 5251                 | Notebook    | [ee4236aa4b](https://linux-hardware.org/?probe=ee4236aa4b) | Jul 05, 2024 |
| Acer          | Aspire 5251                 | Notebook    | [738fcb5042](https://linux-hardware.org/?probe=738fcb5042) | Jul 04, 2024 |
| Dell          | Latitude 5411               | Notebook    | [de4b92c6d7](https://linux-hardware.org/?probe=de4b92c6d7) | Jul 02, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [0a8491e8c6](https://linux-hardware.org/?probe=0a8491e8c6) | Jul 02, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [ee86f5ecfa](https://linux-hardware.org/?probe=ee86f5ecfa) | Jul 02, 2024 |
| HP            | Pavilion x2 Detachable      | Notebook    | [3f4813d1b6](https://linux-hardware.org/?probe=3f4813d1b6) | Jul 01, 2024 |
| HP            | Laptop 14-bw0xx             | Notebook    | [9ac841dacf](https://linux-hardware.org/?probe=9ac841dacf) | Jun 29, 2024 |
| HP            | 3029h                       | Desktop     | [5be522cd78](https://linux-hardware.org/?probe=5be522cd78) | Jun 28, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f44a6b32d8](https://linux-hardware.org/?probe=f44a6b32d8) | Jun 27, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [1e0a97a5f1](https://linux-hardware.org/?probe=1e0a97a5f1) | Jun 24, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [6c9ebe6ce2](https://linux-hardware.org/?probe=6c9ebe6ce2) | Jun 22, 2024 |
| Dell          | 088DT1 A00                  | Desktop     | [63c22aab38](https://linux-hardware.org/?probe=63c22aab38) | Jun 22, 2024 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [ccdf03b592](https://linux-hardware.org/?probe=ccdf03b592) | Jun 19, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [a40ce4c093](https://linux-hardware.org/?probe=a40ce4c093) | Jun 18, 2024 |
| Sony          | VPCCW2S8E                   | Notebook    | [0020b32401](https://linux-hardware.org/?probe=0020b32401) | Jun 17, 2024 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [04002fe8fb](https://linux-hardware.org/?probe=04002fe8fb) | Jun 17, 2024 |
| MSI           | MS-B1831                    | Desktop     | [8e56f848ac](https://linux-hardware.org/?probe=8e56f848ac) | Jun 16, 2024 |
| HP            | 8643 SMVB                   | Desktop     | [21b770ac23](https://linux-hardware.org/?probe=21b770ac23) | Jun 15, 2024 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [a13acdf786](https://linux-hardware.org/?probe=a13acdf786) | Jun 14, 2024 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [fffccdaea1](https://linux-hardware.org/?probe=fffccdaea1) | Jun 14, 2024 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [23f82615a3](https://linux-hardware.org/?probe=23f82615a3) | Jun 12, 2024 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [2094539dff](https://linux-hardware.org/?probe=2094539dff) | Jun 09, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [258aafdc3f](https://linux-hardware.org/?probe=258aafdc3f) | Jun 07, 2024 |
| Dell          | 0M3F6C A01                  | Desktop     | [d9355d53f8](https://linux-hardware.org/?probe=d9355d53f8) | Jun 07, 2024 |
| ASUSTek       | M51AC                       | Desktop     | [8b39e8a250](https://linux-hardware.org/?probe=8b39e8a250) | Jun 06, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [055665c491](https://linux-hardware.org/?probe=055665c491) | Jun 05, 2024 |
| ASUSTek       | ET1612I                     | Desktop     | [589954115c](https://linux-hardware.org/?probe=589954115c) | Jun 03, 2024 |
| Dell          | 0FM586                      | Desktop     | [480574c2be](https://linux-hardware.org/?probe=480574c2be) | Jun 03, 2024 |
| Dell          | 0P658H A05                  | Server      | [47c556be06](https://linux-hardware.org/?probe=47c556be06) | Jun 02, 2024 |
| HP            | Pavilion dv7                | Notebook    | [826b443536](https://linux-hardware.org/?probe=826b443536) | May 31, 2024 |
| Dell          | 0FM586                      | Desktop     | [c192f1ab3d](https://linux-hardware.org/?probe=c192f1ab3d) | May 30, 2024 |
| Acer          | Aspire SW5-012              | Notebook    | [39dbf768d7](https://linux-hardware.org/?probe=39dbf768d7) | May 30, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [7362f68c8c](https://linux-hardware.org/?probe=7362f68c8c) | May 29, 2024 |
| Dell          | Inspiron 3421               | Notebook    | [26c6e28f8c](https://linux-hardware.org/?probe=26c6e28f8c) | May 28, 2024 |
| ASUSTek       | E200HA                      | Notebook    | [528fdeaaba](https://linux-hardware.org/?probe=528fdeaaba) | May 28, 2024 |
| ASUSTek       | K54C                        | Notebook    | [a7e501420d](https://linux-hardware.org/?probe=a7e501420d) | May 27, 2024 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4fb3692ff1](https://linux-hardware.org/?probe=4fb3692ff1) | May 27, 2024 |
| Dell          | 0CRH6C A01                  | Desktop     | [9d92d084e8](https://linux-hardware.org/?probe=9d92d084e8) | May 27, 2024 |
| Medion        | E15309                      | Notebook    | [b095da9dbd](https://linux-hardware.org/?probe=b095da9dbd) | May 26, 2024 |
| Rockchip      | Orange Pi 5                 | Soc         | [59ff8bf9b8](https://linux-hardware.org/?probe=59ff8bf9b8) | May 25, 2024 |
| Lenovo        | ThinkPad W540 20BHS22200    | Notebook    | [4e16082fc6](https://linux-hardware.org/?probe=4e16082fc6) | May 24, 2024 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [41d19e4004](https://linux-hardware.org/?probe=41d19e4004) | May 20, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [533a0b51a1](https://linux-hardware.org/?probe=533a0b51a1) | May 18, 2024 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [2851cf1093](https://linux-hardware.org/?probe=2851cf1093) | May 17, 2024 |
| Dell          | 088DT1 A00                  | Desktop     | [5fdb3e7792](https://linux-hardware.org/?probe=5fdb3e7792) | May 15, 2024 |
| HP            | 8777 01011                  | Mini pc     | [deb8dcec1d](https://linux-hardware.org/?probe=deb8dcec1d) | May 15, 2024 |
| HP            | 3115m                       | Notebook    | [45bdc53959](https://linux-hardware.org/?probe=45bdc53959) | May 14, 2024 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [fa97930352](https://linux-hardware.org/?probe=fa97930352) | May 13, 2024 |
| Acer          | P7YE0                       | Notebook    | [21da78891a](https://linux-hardware.org/?probe=21da78891a) | May 08, 2024 |
| Lenovo        | 7Z74CTO1WW 07               | Server      | [ecd5a5be36](https://linux-hardware.org/?probe=ecd5a5be36) | May 07, 2024 |
| Dell          | 088DT1 A00                  | Desktop     | [edb955bd5e](https://linux-hardware.org/?probe=edb955bd5e) | May 07, 2024 |
| Dell          | Precision 7710              | Notebook    | [c89fe612a1](https://linux-hardware.org/?probe=c89fe612a1) | May 06, 2024 |
| Dell          | Precision 7710              | Notebook    | [52c6c4a64a](https://linux-hardware.org/?probe=52c6c4a64a) | May 06, 2024 |
| Amlogic       | Meson GXL (S905X) P212 D... | Soc         | [1df5ef59da](https://linux-hardware.org/?probe=1df5ef59da) | May 05, 2024 |
| Toshiba       | Satellite A200              | Notebook    | [47b52c0fce](https://linux-hardware.org/?probe=47b52c0fce) | May 02, 2024 |
| Dell          | 0N867P A02                  | Desktop     | [7b2f6946b9](https://linux-hardware.org/?probe=7b2f6946b9) | May 01, 2024 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [0663c3f0ee](https://linux-hardware.org/?probe=0663c3f0ee) | Apr 30, 2024 |
| Acer          | Aspire A515-44              | Notebook    | [d580243e57](https://linux-hardware.org/?probe=d580243e57) | Apr 30, 2024 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [e55bcf23cf](https://linux-hardware.org/?probe=e55bcf23cf) | Apr 30, 2024 |
| Acer          | Aspire A515-51              | Notebook    | [083965d3db](https://linux-hardware.org/?probe=083965d3db) | Apr 30, 2024 |
| AZW           | EQ                          | Desktop     | [dc09b0ecbc](https://linux-hardware.org/?probe=dc09b0ecbc) | Apr 29, 2024 |
| AZW           | EQ                          | Desktop     | [9e4f615d36](https://linux-hardware.org/?probe=9e4f615d36) | Apr 29, 2024 |
| HP            | Notebook                    | Notebook    | [0f3465e86c](https://linux-hardware.org/?probe=0f3465e86c) | Apr 28, 2024 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [afc8b7bd9f](https://linux-hardware.org/?probe=afc8b7bd9f) | Apr 28, 2024 |
| Intel         | AB2L .A001                  | Mini pc     | [b9bb546172](https://linux-hardware.org/?probe=b9bb546172) | Apr 27, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [b83cef7cdd](https://linux-hardware.org/?probe=b83cef7cdd) | Apr 27, 2024 |
| Lenovo        | ThinkPad W541 20EGS03W15    | Notebook    | [32ac46c0a5](https://linux-hardware.org/?probe=32ac46c0a5) | Apr 27, 2024 |
| HP            | Mini 210-1000               | Notebook    | [26d3ef8d19](https://linux-hardware.org/?probe=26d3ef8d19) | Apr 27, 2024 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [4652a98a00](https://linux-hardware.org/?probe=4652a98a00) | Apr 24, 2024 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [3feeb1bdac](https://linux-hardware.org/?probe=3feeb1bdac) | Apr 24, 2024 |
| Lenovo        | ThinkPad Twist 33474HU      | Notebook    | [98b9979ec3](https://linux-hardware.org/?probe=98b9979ec3) | Apr 23, 2024 |
| Apple         | MacBookPro5,2               | Notebook    | [a5052885f7](https://linux-hardware.org/?probe=a5052885f7) | Apr 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a399c9a39f](https://linux-hardware.org/?probe=a399c9a39f) | Apr 22, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [37c91e715a](https://linux-hardware.org/?probe=37c91e715a) | Apr 22, 2024 |
| Dell          | 0MN1TX A02                  | Desktop     | [2aa151f159](https://linux-hardware.org/?probe=2aa151f159) | Apr 20, 2024 |
| Dell          | 0MN1TX A02                  | Desktop     | [cfac7f54ed](https://linux-hardware.org/?probe=cfac7f54ed) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [5e4c324298](https://linux-hardware.org/?probe=5e4c324298) | Apr 18, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [2ff2120005](https://linux-hardware.org/?probe=2ff2120005) | Apr 15, 2024 |
| Sony          | VPCF12M1E                   | Notebook    | [a07e465b04](https://linux-hardware.org/?probe=a07e465b04) | Apr 15, 2024 |
| Dell          | 0FF3FN A00                  | Desktop     | [b1bddc88aa](https://linux-hardware.org/?probe=b1bddc88aa) | Apr 15, 2024 |
| Dell          | 0WG864                      | Desktop     | [b430ed12b5](https://linux-hardware.org/?probe=b430ed12b5) | Apr 15, 2024 |
| Sony          | VPCF12M1E                   | Notebook    | [b4adc4cd67](https://linux-hardware.org/?probe=b4adc4cd67) | Apr 13, 2024 |
| ASRock        | A75M-HVS                    | Desktop     | [fc26a8b5fa](https://linux-hardware.org/?probe=fc26a8b5fa) | Apr 12, 2024 |
| Fujitsu       | FujitsuTP7000 -1            | Desktop     | [1d3918f13c](https://linux-hardware.org/?probe=1d3918f13c) | Apr 11, 2024 |
| Dell          | 0FF3FN A00                  | Desktop     | [979d51faa5](https://linux-hardware.org/?probe=979d51faa5) | Apr 10, 2024 |
| Shenzhen M... | F7BFD                       | Desktop     | [98e43e8de4](https://linux-hardware.org/?probe=98e43e8de4) | Apr 09, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [cee98f0931](https://linux-hardware.org/?probe=cee98f0931) | Apr 09, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [ed8a461ca7](https://linux-hardware.org/?probe=ed8a461ca7) | Apr 09, 2024 |
| Philco        | 14I                         | Notebook    | [c7ac543990](https://linux-hardware.org/?probe=c7ac543990) | Apr 09, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [ac69abc7f8](https://linux-hardware.org/?probe=ac69abc7f8) | Apr 08, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [a49c3b9526](https://linux-hardware.org/?probe=a49c3b9526) | Apr 08, 2024 |
| HP            | 15                          | Notebook    | [81bbe62a62](https://linux-hardware.org/?probe=81bbe62a62) | Apr 08, 2024 |
| Dell          | 088DT1 A00                  | Desktop     | [c11b83e86b](https://linux-hardware.org/?probe=c11b83e86b) | Apr 08, 2024 |
| Hardkernel    | ODROID-H2                   | Desktop     | [64075f354e](https://linux-hardware.org/?probe=64075f354e) | Apr 07, 2024 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [3baacd7e39](https://linux-hardware.org/?probe=3baacd7e39) | Apr 07, 2024 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [48ffb129cb](https://linux-hardware.org/?probe=48ffb129cb) | Apr 06, 2024 |
| Dell          | Latitude 5330               | Notebook    | [3327ec32e4](https://linux-hardware.org/?probe=3327ec32e4) | Apr 06, 2024 |
| Gigabyte      | M68M-S2P                    | Desktop     | [2711aee181](https://linux-hardware.org/?probe=2711aee181) | Apr 05, 2024 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [690d2ee78f](https://linux-hardware.org/?probe=690d2ee78f) | Apr 05, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [f3587d854e](https://linux-hardware.org/?probe=f3587d854e) | Apr 05, 2024 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [1479db147d](https://linux-hardware.org/?probe=1479db147d) | Apr 04, 2024 |
| Acer          | Aspire A515-44              | Notebook    | [4b51c98fb6](https://linux-hardware.org/?probe=4b51c98fb6) | Apr 04, 2024 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [b57ab21576](https://linux-hardware.org/?probe=b57ab21576) | Apr 03, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [dfef032d35](https://linux-hardware.org/?probe=dfef032d35) | Apr 03, 2024 |
| MSI           | X58 Pro                     | Desktop     | [9b0fab5acc](https://linux-hardware.org/?probe=9b0fab5acc) | Apr 02, 2024 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [9ce8633d67](https://linux-hardware.org/?probe=9ce8633d67) | Apr 02, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [84ed1b3cc5](https://linux-hardware.org/?probe=84ed1b3cc5) | Apr 01, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [0df7a90dcd](https://linux-hardware.org/?probe=0df7a90dcd) | Apr 01, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0bd97f775d](https://linux-hardware.org/?probe=0bd97f775d) | Apr 01, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d952efad38](https://linux-hardware.org/?probe=d952efad38) | Apr 01, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [1115e42390](https://linux-hardware.org/?probe=1115e42390) | Mar 30, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [a09b8ab7cc](https://linux-hardware.org/?probe=a09b8ab7cc) | Mar 29, 2024 |
| HP            | Elite x2 1012 G1            | Notebook    | [5e19a7d027](https://linux-hardware.org/?probe=5e19a7d027) | Mar 29, 2024 |
| HP            | Elite x2 1012 G1            | Notebook    | [2d13f6d55a](https://linux-hardware.org/?probe=2d13f6d55a) | Mar 29, 2024 |
| Dell          | Latitude E6520              | Notebook    | [b0934dd20e](https://linux-hardware.org/?probe=b0934dd20e) | Mar 27, 2024 |
| Toshiba       | Satellite C70D-B            | Notebook    | [6800119330](https://linux-hardware.org/?probe=6800119330) | Mar 27, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [62ff739b8b](https://linux-hardware.org/?probe=62ff739b8b) | Mar 27, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [15137ac3a5](https://linux-hardware.org/?probe=15137ac3a5) | Mar 27, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [ee2674fe55](https://linux-hardware.org/?probe=ee2674fe55) | Mar 26, 2024 |
| Dell          | Latitude E5510              | Notebook    | [3f05300c5e](https://linux-hardware.org/?probe=3f05300c5e) | Mar 26, 2024 |
| Intel         | X99                         | Desktop     | [2479fc825c](https://linux-hardware.org/?probe=2479fc825c) | Mar 25, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | Notebook    | [eb09797dad](https://linux-hardware.org/?probe=eb09797dad) | Mar 25, 2024 |
| Lenovo        | ThinkPad L512 2598W2P       | Notebook    | [29d9529699](https://linux-hardware.org/?probe=29d9529699) | Mar 24, 2024 |
| Shenzhen M... | F7BFD                       | Desktop     | [64942ccf25](https://linux-hardware.org/?probe=64942ccf25) | Mar 24, 2024 |
| MACHINIST     | E5-MR9A V1.0                | Desktop     | [24cd2954c5](https://linux-hardware.org/?probe=24cd2954c5) | Mar 24, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [052a56e30a](https://linux-hardware.org/?probe=052a56e30a) | Mar 23, 2024 |
| Toshiba       | Satellite C70D-B            | Notebook    | [85a82b979c](https://linux-hardware.org/?probe=85a82b979c) | Mar 23, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [e18375e687](https://linux-hardware.org/?probe=e18375e687) | Mar 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | Notebook    | [4d1bc02be0](https://linux-hardware.org/?probe=4d1bc02be0) | Mar 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | Notebook    | [0f6120fef2](https://linux-hardware.org/?probe=0f6120fef2) | Mar 23, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [1398cdcdf9](https://linux-hardware.org/?probe=1398cdcdf9) | Mar 22, 2024 |
| MSI           | 760GM-P21                   | Desktop     | [9ea00e6ebb](https://linux-hardware.org/?probe=9ea00e6ebb) | Mar 22, 2024 |
| Intel         | H81                         | Desktop     | [9faff0c332](https://linux-hardware.org/?probe=9faff0c332) | Mar 21, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [9df4721239](https://linux-hardware.org/?probe=9df4721239) | Mar 20, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [62f6992f05](https://linux-hardware.org/?probe=62f6992f05) | Mar 20, 2024 |
| eMachines     | eME642G                     | Notebook    | [8759a11aca](https://linux-hardware.org/?probe=8759a11aca) | Mar 20, 2024 |
| Supermicro    | X8DTN                       | Server      | [180b7199c4](https://linux-hardware.org/?probe=180b7199c4) | Mar 19, 2024 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [e003a1215d](https://linux-hardware.org/?probe=e003a1215d) | Mar 19, 2024 |
| Supermicro    | X8DTN                       | Server      | [a7ef5b23a1](https://linux-hardware.org/?probe=a7ef5b23a1) | Mar 18, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [aff15cce95](https://linux-hardware.org/?probe=aff15cce95) | Mar 17, 2024 |
| Lenovo        | G70-70 80HW0014FR           | Notebook    | [8fd24b2766](https://linux-hardware.org/?probe=8fd24b2766) | Mar 17, 2024 |
| Lenovo        | G70-70 80HW0014FR           | Notebook    | [ebb00d0246](https://linux-hardware.org/?probe=ebb00d0246) | Mar 17, 2024 |
| eMachines     | eME642G                     | Notebook    | [7d7230a747](https://linux-hardware.org/?probe=7d7230a747) | Mar 16, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [8f589013b1](https://linux-hardware.org/?probe=8f589013b1) | Mar 15, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [2d1ccd0458](https://linux-hardware.org/?probe=2d1ccd0458) | Mar 15, 2024 |
| Fujitsu       | FARQ10003                   | Notebook    | [85d8b675fc](https://linux-hardware.org/?probe=85d8b675fc) | Mar 14, 2024 |
| HP            | 2175                        | Desktop     | [f43124076c](https://linux-hardware.org/?probe=f43124076c) | Mar 14, 2024 |
| Dell          | 088DT1 A00                  | Desktop     | [8eb20f3ee6](https://linux-hardware.org/?probe=8eb20f3ee6) | Mar 12, 2024 |
| Dell          | 0J3C2F A02                  | Desktop     | [bebba9cf4a](https://linux-hardware.org/?probe=bebba9cf4a) | Mar 12, 2024 |
| HP            | 250 G6 Notebook PC          | Notebook    | [6b050fbf71](https://linux-hardware.org/?probe=6b050fbf71) | Mar 12, 2024 |
| Dell          | 0FF3FN A00                  | Desktop     | [78dd6f891e](https://linux-hardware.org/?probe=78dd6f891e) | Mar 11, 2024 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [dd2cc3d3df](https://linux-hardware.org/?probe=dd2cc3d3df) | Mar 11, 2024 |
| Dell          | 0VHXCD A03                  | Desktop     | [4ea894ca73](https://linux-hardware.org/?probe=4ea894ca73) | Mar 10, 2024 |
| Toshiba       | Satellite A200              | Notebook    | [7197835980](https://linux-hardware.org/?probe=7197835980) | Mar 08, 2024 |
| HP            | 3397                        | Desktop     | [571ec29e07](https://linux-hardware.org/?probe=571ec29e07) | Mar 07, 2024 |
| Dell          | Latitude 5280               | Notebook    | [59fcb83d4a](https://linux-hardware.org/?probe=59fcb83d4a) | Mar 07, 2024 |
| Dell          | Latitude 5280               | Notebook    | [eca7be25aa](https://linux-hardware.org/?probe=eca7be25aa) | Mar 07, 2024 |
| Notebook      | W54_55_94_95_97AU,AUQ       | Notebook    | [b16fb5307b](https://linux-hardware.org/?probe=b16fb5307b) | Mar 07, 2024 |
| HP            | 2129                        | Desktop     | [c06e16031f](https://linux-hardware.org/?probe=c06e16031f) | Mar 07, 2024 |
| HP            | 2129                        | Desktop     | [5f2414ecf8](https://linux-hardware.org/?probe=5f2414ecf8) | Mar 07, 2024 |
| HP            | 1998                        | Desktop     | [bd3e35eb3f](https://linux-hardware.org/?probe=bd3e35eb3f) | Mar 06, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [23a8bcc014](https://linux-hardware.org/?probe=23a8bcc014) | Mar 06, 2024 |
| Lenovo        | ThinkPad T470p 20J6S00UH... | Notebook    | [b35deb0a8c](https://linux-hardware.org/?probe=b35deb0a8c) | Mar 06, 2024 |
| Lenovo        | ThinkPad A475 20KMS0MR00    | Notebook    | [0351009764](https://linux-hardware.org/?probe=0351009764) | Mar 05, 2024 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [4d165bc18c](https://linux-hardware.org/?probe=4d165bc18c) | Mar 05, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1c340dbb25](https://linux-hardware.org/?probe=1c340dbb25) | Mar 04, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [9552e898d6](https://linux-hardware.org/?probe=9552e898d6) | Mar 04, 2024 |
| Lenovo        | ThinkPad A475 20KMS0MR00    | Notebook    | [eead5309ca](https://linux-hardware.org/?probe=eead5309ca) | Mar 04, 2024 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [3a3676f133](https://linux-hardware.org/?probe=3a3676f133) | Mar 04, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [fc50b125e5](https://linux-hardware.org/?probe=fc50b125e5) | Mar 04, 2024 |
| HP            | 240 G7 Notebook PC          | Notebook    | [7556bb7dcb](https://linux-hardware.org/?probe=7556bb7dcb) | Mar 04, 2024 |
| Acer          | Extensa 5620                | Notebook    | [184149092e](https://linux-hardware.org/?probe=184149092e) | Mar 02, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [abfba381b6](https://linux-hardware.org/?probe=abfba381b6) | Mar 02, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [5d03e50172](https://linux-hardware.org/?probe=5d03e50172) | Mar 02, 2024 |
| HP            | 212A                        | Desktop     | [688db14d79](https://linux-hardware.org/?probe=688db14d79) | Feb 29, 2024 |
| Dell          | Inspiron 15 3520            | Notebook    | [22b06310de](https://linux-hardware.org/?probe=22b06310de) | Feb 29, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6b541baebc](https://linux-hardware.org/?probe=6b541baebc) | Feb 28, 2024 |
| Acer          | Aspire 5742G                | Notebook    | [ec33f6391f](https://linux-hardware.org/?probe=ec33f6391f) | Feb 27, 2024 |
| Dell          | Latitude 3590               | Notebook    | [cfd80ed606](https://linux-hardware.org/?probe=cfd80ed606) | Feb 25, 2024 |
| Acer          | Aspire 5742G                | Notebook    | [4ab95b25ed](https://linux-hardware.org/?probe=4ab95b25ed) | Feb 24, 2024 |
| ASUSTek       | Z170-K                      | Desktop     | [790bcad6c3](https://linux-hardware.org/?probe=790bcad6c3) | Feb 23, 2024 |
| Dell          | 088DT1 A00                  | Desktop     | [688b84c15c](https://linux-hardware.org/?probe=688b84c15c) | Feb 23, 2024 |
| HP            | 8777 01011                  | Mini pc     | [7694754fa7](https://linux-hardware.org/?probe=7694754fa7) | Feb 23, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [9cc44f0ff5](https://linux-hardware.org/?probe=9cc44f0ff5) | Feb 22, 2024 |
| Shenzhen M... | F7BFD                       | Desktop     | [ed5d36c89f](https://linux-hardware.org/?probe=ed5d36c89f) | Feb 22, 2024 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [f4df789f90](https://linux-hardware.org/?probe=f4df789f90) | Feb 19, 2024 |
| ASUSTek       | P6T SE                      | Desktop     | [19014495ef](https://linux-hardware.org/?probe=19014495ef) | Feb 18, 2024 |
| Dell          | 088DT1 A00                  | Desktop     | [1442765491](https://linux-hardware.org/?probe=1442765491) | Feb 17, 2024 |
| Dell          | 088DT1 A00                  | Desktop     | [90fc76d5f0](https://linux-hardware.org/?probe=90fc76d5f0) | Feb 17, 2024 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [0495f0384b](https://linux-hardware.org/?probe=0495f0384b) | Feb 17, 2024 |
| Intel         | DB75EN                      | Desktop     | [d2fb5b9c49](https://linux-hardware.org/?probe=d2fb5b9c49) | Feb 15, 2024 |
| Intel         | D54250WYK H13922-303        | Desktop     | [2c7d744bc7](https://linux-hardware.org/?probe=2c7d744bc7) | Feb 14, 2024 |
| Toshiba       | dynabook EX/45CW            | Notebook    | [15397b8cd4](https://linux-hardware.org/?probe=15397b8cd4) | Feb 14, 2024 |
| Lenovo        | NOK                         | Desktop     | [ee3d0a6048](https://linux-hardware.org/?probe=ee3d0a6048) | Feb 11, 2024 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [3f7984a7cb](https://linux-hardware.org/?probe=3f7984a7cb) | Feb 10, 2024 |
| Toshiba       | Satellite S55-A             | Notebook    | [b8c672ccc5](https://linux-hardware.org/?probe=b8c672ccc5) | Feb 10, 2024 |
| Acer          | Aspire A515-52K             | Notebook    | [08c3bcf367](https://linux-hardware.org/?probe=08c3bcf367) | Feb 07, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [eebc3497e7](https://linux-hardware.org/?probe=eebc3497e7) | Feb 06, 2024 |
| Lenovo        | NOK                         | Desktop     | [24ed0846b2](https://linux-hardware.org/?probe=24ed0846b2) | Feb 05, 2024 |
| Intel         | DB75EN                      | Desktop     | [0ec38bc63a](https://linux-hardware.org/?probe=0ec38bc63a) | Feb 04, 2024 |
| Intel         | NUC9i5QNB K49247-403        | Mini pc     | [9050f9f095](https://linux-hardware.org/?probe=9050f9f095) | Feb 04, 2024 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | Desktop     | [a87f78b559](https://linux-hardware.org/?probe=a87f78b559) | Feb 03, 2024 |
| Dell          | 0P658H A05                  | Server      | [38486457e6](https://linux-hardware.org/?probe=38486457e6) | Feb 03, 2024 |
| MSI           | Modern 15 A10M              | Notebook    | [22f3c2e58e](https://linux-hardware.org/?probe=22f3c2e58e) | Feb 02, 2024 |
| Acer          | NC-F5-771G-72XY             | Notebook    | [2f4c6fbadb](https://linux-hardware.org/?probe=2f4c6fbadb) | Feb 02, 2024 |
| Apple         | MacBookPro5,4               | Notebook    | [c22226fe6f](https://linux-hardware.org/?probe=c22226fe6f) | Feb 01, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [920b1ecb34](https://linux-hardware.org/?probe=920b1ecb34) | Jan 31, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [ad26dae776](https://linux-hardware.org/?probe=ad26dae776) | Jan 30, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [bc4394a85f](https://linux-hardware.org/?probe=bc4394a85f) | Jan 30, 2024 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [737d54004b](https://linux-hardware.org/?probe=737d54004b) | Jan 29, 2024 |
| ASUSTek       | X205TA                      | Notebook    | [83899dcb83](https://linux-hardware.org/?probe=83899dcb83) | Jan 27, 2024 |
| Lenovo        | ThinkPad T400 6474AW6       | Notebook    | [0ddfcaf599](https://linux-hardware.org/?probe=0ddfcaf599) | Jan 27, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [c85674acbd](https://linux-hardware.org/?probe=c85674acbd) | Jan 26, 2024 |
| PC Special... | NH5x_7xDPx                  | Notebook    | [0f28a5d513](https://linux-hardware.org/?probe=0f28a5d513) | Jan 26, 2024 |
| Intel         | DB75EN                      | Desktop     | [41cea41d1e](https://linux-hardware.org/?probe=41cea41d1e) | Jan 26, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [51346a4084](https://linux-hardware.org/?probe=51346a4084) | Jan 25, 2024 |
| Dell          | Latitude 7340               | Notebook    | [880054b099](https://linux-hardware.org/?probe=880054b099) | Jan 25, 2024 |
| Dell          | 0K240Y A01                  | Desktop     | [fe08501f76](https://linux-hardware.org/?probe=fe08501f76) | Jan 24, 2024 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [5a5ec0016f](https://linux-hardware.org/?probe=5a5ec0016f) | Jan 24, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d11d529522](https://linux-hardware.org/?probe=d11d529522) | Jan 23, 2024 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [545e0a6896](https://linux-hardware.org/?probe=545e0a6896) | Jan 23, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [dc061193f2](https://linux-hardware.org/?probe=dc061193f2) | Jan 22, 2024 |
| AOpen         | D2644 S26361-D2644          | Desktop     | [f45673bd59](https://linux-hardware.org/?probe=f45673bd59) | Jan 22, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [b6fa224856](https://linux-hardware.org/?probe=b6fa224856) | Jan 21, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [4254242157](https://linux-hardware.org/?probe=4254242157) | Jan 21, 2024 |
| Intel         | DB75EN                      | Desktop     | [f639799c41](https://linux-hardware.org/?probe=f639799c41) | Jan 21, 2024 |
| Dell          | 0F5C5X A00                  | Desktop     | [f320dddb34](https://linux-hardware.org/?probe=f320dddb34) | Jan 19, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [bcbb9c099f](https://linux-hardware.org/?probe=bcbb9c099f) | Jan 16, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [6d2801d1d8](https://linux-hardware.org/?probe=6d2801d1d8) | Jan 14, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [77032de9df](https://linux-hardware.org/?probe=77032de9df) | Jan 14, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [5dacf75c7d](https://linux-hardware.org/?probe=5dacf75c7d) | Jan 12, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [1ad7806df7](https://linux-hardware.org/?probe=1ad7806df7) | Jan 12, 2024 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [b6d8783c20](https://linux-hardware.org/?probe=b6d8783c20) | Jan 12, 2024 |
| Dell          | 0T0MHW A03                  | Desktop     | [2ad439d95f](https://linux-hardware.org/?probe=2ad439d95f) | Jan 11, 2024 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [ce397f675e](https://linux-hardware.org/?probe=ce397f675e) | Jan 10, 2024 |
| Microsoft     | Surface Pro 7               | Tablet      | [f02310e366](https://linux-hardware.org/?probe=f02310e366) | Jan 10, 2024 |
| Dell          | Inspiron 14-3452            | Notebook    | [0e47261be0](https://linux-hardware.org/?probe=0e47261be0) | Jan 09, 2024 |
| Dell          | Inspiron 14-3452            | Notebook    | [1834cfc875](https://linux-hardware.org/?probe=1834cfc875) | Jan 09, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [511526bcf7](https://linux-hardware.org/?probe=511526bcf7) | Jan 08, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [00ef8580ff](https://linux-hardware.org/?probe=00ef8580ff) | Jan 07, 2024 |
| Apple         | MacBook5,2                  | Notebook    | [2ed16f6a80](https://linux-hardware.org/?probe=2ed16f6a80) | Jan 07, 2024 |
| Lenovo        | IdeaPad 510S-13ISK 80SJ     | Notebook    | [90fe273da6](https://linux-hardware.org/?probe=90fe273da6) | Jan 06, 2024 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [e131bcc2a6](https://linux-hardware.org/?probe=e131bcc2a6) | Jan 06, 2024 |
| Acer          | Aspire A517-52              | Notebook    | [610817c6c9](https://linux-hardware.org/?probe=610817c6c9) | Jan 05, 2024 |
| Gigabyte      | P55-UD3R                    | Desktop     | [44658131d3](https://linux-hardware.org/?probe=44658131d3) | Jan 05, 2024 |
| Dell          | 0P658H A05                  | Server      | [74f28d91a3](https://linux-hardware.org/?probe=74f28d91a3) | Jan 05, 2024 |
| HP            | Pavilion dv7                | Notebook    | [dc31f854de](https://linux-hardware.org/?probe=dc31f854de) | Jan 04, 2024 |
| Dell          | 0P658H A05                  | Server      | [1ae3680481](https://linux-hardware.org/?probe=1ae3680481) | Jan 01, 2024 |
| Dell          | Latitude 7390               | Notebook    | [8c74383dab](https://linux-hardware.org/?probe=8c74383dab) | Dec 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [1f73670f10](https://linux-hardware.org/?probe=1f73670f10) | Dec 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [889337bb1c](https://linux-hardware.org/?probe=889337bb1c) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [38b1c283b4](https://linux-hardware.org/?probe=38b1c283b4) | Dec 26, 2023 |
| Intel         | DB75EN                      | Desktop     | [c2c820f0d9](https://linux-hardware.org/?probe=c2c820f0d9) | Dec 25, 2023 |
| Intel         | DB75EN                      | Desktop     | [6ec790f3fc](https://linux-hardware.org/?probe=6ec790f3fc) | Dec 24, 2023 |
| eMachines     | E527                        | Notebook    | [cf5b096be7](https://linux-hardware.org/?probe=cf5b096be7) | Dec 22, 2023 |
| Gigabyte      | P35-DS3R                    | Desktop     | [741ad16651](https://linux-hardware.org/?probe=741ad16651) | Dec 22, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [07a7762b25](https://linux-hardware.org/?probe=07a7762b25) | Dec 21, 2023 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [16a8e6f875](https://linux-hardware.org/?probe=16a8e6f875) | Dec 21, 2023 |
| Sony          | VGN-NW270F                  | Notebook    | [eee640a54d](https://linux-hardware.org/?probe=eee640a54d) | Dec 20, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [ee1a222677](https://linux-hardware.org/?probe=ee1a222677) | Dec 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [4cc379dfbd](https://linux-hardware.org/?probe=4cc379dfbd) | Dec 19, 2023 |
| HP            | Notebook                    | Notebook    | [31d6fc4280](https://linux-hardware.org/?probe=31d6fc4280) | Dec 19, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [a6ae535887](https://linux-hardware.org/?probe=a6ae535887) | Dec 18, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [06556bd61a](https://linux-hardware.org/?probe=06556bd61a) | Dec 17, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [ce0e0e1bc1](https://linux-hardware.org/?probe=ce0e0e1bc1) | Dec 17, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [f0ed04c975](https://linux-hardware.org/?probe=f0ed04c975) | Dec 16, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [6a2633018c](https://linux-hardware.org/?probe=6a2633018c) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [e7ca2f3a6e](https://linux-hardware.org/?probe=e7ca2f3a6e) | Dec 14, 2023 |
| HP            | 212B                        | Desktop     | [1ce8b8d929](https://linux-hardware.org/?probe=1ce8b8d929) | Dec 14, 2023 |
| Intel         | H310 Series                 | Desktop     | [9565b22822](https://linux-hardware.org/?probe=9565b22822) | Dec 13, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [2204183295](https://linux-hardware.org/?probe=2204183295) | Dec 12, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [63cf57fa53](https://linux-hardware.org/?probe=63cf57fa53) | Dec 12, 2023 |
| Dell          | Inspiron 7591               | Notebook    | [10a266d0ff](https://linux-hardware.org/?probe=10a266d0ff) | Dec 12, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [e223660e23](https://linux-hardware.org/?probe=e223660e23) | Dec 11, 2023 |
| Lenovo        | ThinkPad T530 2429W1E       | Notebook    | [02a4811e8d](https://linux-hardware.org/?probe=02a4811e8d) | Dec 10, 2023 |
| ASUSTek       | PRIME H510M-A WIFI          | Desktop     | [ba43863b29](https://linux-hardware.org/?probe=ba43863b29) | Dec 09, 2023 |
| Dell          | Inspiron 7591               | Notebook    | [7907f73ee0](https://linux-hardware.org/?probe=7907f73ee0) | Dec 09, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [74440ebfad](https://linux-hardware.org/?probe=74440ebfad) | Dec 07, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [beaa75c727](https://linux-hardware.org/?probe=beaa75c727) | Dec 06, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | Notebook    | [0c680c33ec](https://linux-hardware.org/?probe=0c680c33ec) | Dec 05, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [7b1c8f906b](https://linux-hardware.org/?probe=7b1c8f906b) | Dec 04, 2023 |
| Dell          | Latitude 7370               | Notebook    | [30fc1de681](https://linux-hardware.org/?probe=30fc1de681) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [203357a4dd](https://linux-hardware.org/?probe=203357a4dd) | Dec 03, 2023 |
| Intel         | DB75EN                      | Desktop     | [15f11719b5](https://linux-hardware.org/?probe=15f11719b5) | Dec 02, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [c8e6af0346](https://linux-hardware.org/?probe=c8e6af0346) | Nov 30, 2023 |
| Dell          | Latitude 7370               | Notebook    | [356b2e9e31](https://linux-hardware.org/?probe=356b2e9e31) | Nov 30, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [7c7825a9c9](https://linux-hardware.org/?probe=7c7825a9c9) | Nov 30, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [c179f18d96](https://linux-hardware.org/?probe=c179f18d96) | Nov 27, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [4b14c830c0](https://linux-hardware.org/?probe=4b14c830c0) | Nov 26, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [d3697eee2c](https://linux-hardware.org/?probe=d3697eee2c) | Nov 24, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [8edef55308](https://linux-hardware.org/?probe=8edef55308) | Nov 24, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [78748bcf50](https://linux-hardware.org/?probe=78748bcf50) | Nov 24, 2023 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [0edf2befff](https://linux-hardware.org/?probe=0edf2befff) | Nov 21, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [b6cfe558cb](https://linux-hardware.org/?probe=b6cfe558cb) | Nov 21, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9701d268e8](https://linux-hardware.org/?probe=9701d268e8) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [2b84d65d1a](https://linux-hardware.org/?probe=2b84d65d1a) | Nov 20, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [d5ccc9cfc9](https://linux-hardware.org/?probe=d5ccc9cfc9) | Nov 20, 2023 |
| Thomson       | N15C8BK2T                   | Notebook    | [e5a62b2035](https://linux-hardware.org/?probe=e5a62b2035) | Nov 18, 2023 |
| HP            | 21B4 A01                    | Desktop     | [73a4740b8f](https://linux-hardware.org/?probe=73a4740b8f) | Nov 18, 2023 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [b8bca4e3cd](https://linux-hardware.org/?probe=b8bca4e3cd) | Nov 18, 2023 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [8a23e4f586](https://linux-hardware.org/?probe=8a23e4f586) | Nov 16, 2023 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [7fabbf9cb1](https://linux-hardware.org/?probe=7fabbf9cb1) | Nov 16, 2023 |
| OrangePi      | 4 LTS                       | Soc         | [a770db570a](https://linux-hardware.org/?probe=a770db570a) | Nov 15, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [6806c7c828](https://linux-hardware.org/?probe=6806c7c828) | Nov 15, 2023 |
| Lenovo        | IdeaPad S300 9803           | Notebook    | [21f7433934](https://linux-hardware.org/?probe=21f7433934) | Nov 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS2P703    | Notebook    | [b15506a2b9](https://linux-hardware.org/?probe=b15506a2b9) | Nov 14, 2023 |
| Dell          | Latitude E5420              | Notebook    | [dc67f70b3b](https://linux-hardware.org/?probe=dc67f70b3b) | Nov 13, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [7deb21f5d9](https://linux-hardware.org/?probe=7deb21f5d9) | Nov 13, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [aefe53a7b6](https://linux-hardware.org/?probe=aefe53a7b6) | Nov 13, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [238b7326f1](https://linux-hardware.org/?probe=238b7326f1) | Nov 10, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [c1a263f3b5](https://linux-hardware.org/?probe=c1a263f3b5) | Nov 08, 2023 |
| OrangePi      | 4 LTS                       | Soc         | [04e71993b5](https://linux-hardware.org/?probe=04e71993b5) | Nov 08, 2023 |
| ASUSTek       | P5K                         | Desktop     | [4870e13f93](https://linux-hardware.org/?probe=4870e13f93) | Nov 08, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [d918aae63e](https://linux-hardware.org/?probe=d918aae63e) | Nov 06, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [ef019ff242](https://linux-hardware.org/?probe=ef019ff242) | Nov 06, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [de892702f8](https://linux-hardware.org/?probe=de892702f8) | Nov 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fefb7e12d2](https://linux-hardware.org/?probe=fefb7e12d2) | Nov 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a871f012a2](https://linux-hardware.org/?probe=a871f012a2) | Nov 02, 2023 |
| Medion        | E3223                       | Convertible | [e35701b198](https://linux-hardware.org/?probe=e35701b198) | Oct 31, 2023 |
| AMI           | Intel                       | Notebook    | [98d35ad708](https://linux-hardware.org/?probe=98d35ad708) | Oct 31, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [6273e445bd](https://linux-hardware.org/?probe=6273e445bd) | Oct 30, 2023 |
| OrangePi      | Zero3                       | Soc         | [6d3ecf003f](https://linux-hardware.org/?probe=6d3ecf003f) | Oct 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a718d2e0ba](https://linux-hardware.org/?probe=a718d2e0ba) | Oct 28, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [c866e0068b](https://linux-hardware.org/?probe=c866e0068b) | Oct 28, 2023 |
| Lenovo        | ThinkPad T61 64607EU        | Notebook    | [413cefff03](https://linux-hardware.org/?probe=413cefff03) | Oct 26, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [1d3f58a610](https://linux-hardware.org/?probe=1d3f58a610) | Oct 25, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [78702b9deb](https://linux-hardware.org/?probe=78702b9deb) | Oct 23, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [1f7af8af3e](https://linux-hardware.org/?probe=1f7af8af3e) | Oct 23, 2023 |
| Dell          | Latitude 3490               | Notebook    | [174ee1b12e](https://linux-hardware.org/?probe=174ee1b12e) | Oct 20, 2023 |
| Dell          | 0XKH0D A02                  | Desktop     | [bba36c01cf](https://linux-hardware.org/?probe=bba36c01cf) | Oct 19, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [e657535210](https://linux-hardware.org/?probe=e657535210) | Oct 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d519c10989](https://linux-hardware.org/?probe=d519c10989) | Oct 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [626c7e1591](https://linux-hardware.org/?probe=626c7e1591) | Oct 16, 2023 |
| HP            | 18E5                        | Desktop     | [d869fcd6dc](https://linux-hardware.org/?probe=d869fcd6dc) | Oct 16, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [949b939768](https://linux-hardware.org/?probe=949b939768) | Oct 16, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [18922baf01](https://linux-hardware.org/?probe=18922baf01) | Oct 15, 2023 |
| Acer          | Aspire A317-51K             | Notebook    | [b342c56fc5](https://linux-hardware.org/?probe=b342c56fc5) | Oct 15, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [7f99209a06](https://linux-hardware.org/?probe=7f99209a06) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [430df05ea3](https://linux-hardware.org/?probe=430df05ea3) | Oct 14, 2023 |
| HP            | 339A                        | Desktop     | [188e7d023e](https://linux-hardware.org/?probe=188e7d023e) | Oct 14, 2023 |
| Dell          | Latitude 7330               | Notebook    | [8632b84be8](https://linux-hardware.org/?probe=8632b84be8) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [edb8f551bf](https://linux-hardware.org/?probe=edb8f551bf) | Oct 14, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [b7a193296f](https://linux-hardware.org/?probe=b7a193296f) | Oct 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [41ca042a36](https://linux-hardware.org/?probe=41ca042a36) | Oct 14, 2023 |
| Lenovo        | ThinkPad T430u 3352A83      | Notebook    | [c5a829d842](https://linux-hardware.org/?probe=c5a829d842) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [1a8e527488](https://linux-hardware.org/?probe=1a8e527488) | Oct 13, 2023 |
| Dell          | Latitude 5411               | Notebook    | [48ecb46d24](https://linux-hardware.org/?probe=48ecb46d24) | Oct 09, 2023 |
| MSI           | GP65 Leopard 10SDK          | Notebook    | [6b02c3ce0f](https://linux-hardware.org/?probe=6b02c3ce0f) | Oct 08, 2023 |
| HP            | Pavilion g4                 | Notebook    | [3e5383da88](https://linux-hardware.org/?probe=3e5383da88) | Oct 08, 2023 |
| HP            | Pavilion g4                 | Notebook    | [cab160aff3](https://linux-hardware.org/?probe=cab160aff3) | Oct 08, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a92453737d](https://linux-hardware.org/?probe=a92453737d) | Oct 06, 2023 |
| OrangePi      | Zero3                       | Soc         | [a97205648a](https://linux-hardware.org/?probe=a97205648a) | Oct 05, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [a1f4e6f6cc](https://linux-hardware.org/?probe=a1f4e6f6cc) | Oct 05, 2023 |
| HP            | 18E5                        | Desktop     | [653e855c90](https://linux-hardware.org/?probe=653e855c90) | Oct 05, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [870556d425](https://linux-hardware.org/?probe=870556d425) | Oct 04, 2023 |
| Fujitsu Si... | LIFEBOOK T4215              | Notebook    | [392481b855](https://linux-hardware.org/?probe=392481b855) | Oct 04, 2023 |
| HP            | 09F8h                       | Desktop     | [996f1179ba](https://linux-hardware.org/?probe=996f1179ba) | Oct 02, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [df644adbab](https://linux-hardware.org/?probe=df644adbab) | Oct 01, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [2ccade9ad8](https://linux-hardware.org/?probe=2ccade9ad8) | Oct 01, 2023 |
| HP            | 18E5                        | Desktop     | [1f3e02bd3e](https://linux-hardware.org/?probe=1f3e02bd3e) | Oct 01, 2023 |
| Medion        | B660M DS3H AX DDR4          | Desktop     | [1dbbeda8cd](https://linux-hardware.org/?probe=1dbbeda8cd) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | Desktop     | [57a42b9ccf](https://linux-hardware.org/?probe=57a42b9ccf) | Sep 30, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [27b01f468d](https://linux-hardware.org/?probe=27b01f468d) | Sep 30, 2023 |
| Lenovo        | NOK                         | Desktop     | [95ba956749](https://linux-hardware.org/?probe=95ba956749) | Sep 28, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [060deb4c88](https://linux-hardware.org/?probe=060deb4c88) | Sep 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [275018a17e](https://linux-hardware.org/?probe=275018a17e) | Sep 26, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f3b7fdc0c1](https://linux-hardware.org/?probe=f3b7fdc0c1) | Sep 26, 2023 |
| Medion        | MS-7848                     | Desktop     | [5ce2a07d18](https://linux-hardware.org/?probe=5ce2a07d18) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [61f61b1b63](https://linux-hardware.org/?probe=61f61b1b63) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [ffb5ff9359](https://linux-hardware.org/?probe=ffb5ff9359) | Sep 25, 2023 |
| Toshiba       | Satellite C50D-A-10E        | Notebook    | [46f0ec000d](https://linux-hardware.org/?probe=46f0ec000d) | Sep 24, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [fe5f9ad018](https://linux-hardware.org/?probe=fe5f9ad018) | Sep 23, 2023 |
| ASUSTek       | X510UQR                     | Notebook    | [364ee59aef](https://linux-hardware.org/?probe=364ee59aef) | Sep 23, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | Desktop     | [c3043092b9](https://linux-hardware.org/?probe=c3043092b9) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [a6fd72ec9a](https://linux-hardware.org/?probe=a6fd72ec9a) | Sep 20, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [d2fe3f1d44](https://linux-hardware.org/?probe=d2fe3f1d44) | Sep 19, 2023 |
| Lenovo        | ThinkPad T430 2349BG6       | Notebook    | [dbd8f7715f](https://linux-hardware.org/?probe=dbd8f7715f) | Sep 19, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [f2d4f47a8e](https://linux-hardware.org/?probe=f2d4f47a8e) | Sep 18, 2023 |
| Dell          | Latitude 3520               | Notebook    | [c74d2293dd](https://linux-hardware.org/?probe=c74d2293dd) | Sep 18, 2023 |
| Intel         | NUC11TNBi5 M11904-403       | Mini pc     | [e2504a32cf](https://linux-hardware.org/?probe=e2504a32cf) | Sep 15, 2023 |
| Lenovo        | ThinkPad T450 20BVA01QHV    | Notebook    | [4f0a2bdfdc](https://linux-hardware.org/?probe=4f0a2bdfdc) | Sep 15, 2023 |
| ASUSTek       | K72Dr                       | Notebook    | [46edd6eb72](https://linux-hardware.org/?probe=46edd6eb72) | Sep 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [cf69e328c4](https://linux-hardware.org/?probe=cf69e328c4) | Sep 14, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [08e19ba183](https://linux-hardware.org/?probe=08e19ba183) | Sep 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b6a4327a8b](https://linux-hardware.org/?probe=b6a4327a8b) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [a51361ebb2](https://linux-hardware.org/?probe=a51361ebb2) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [00cbde2fb9](https://linux-hardware.org/?probe=00cbde2fb9) | Sep 12, 2023 |
| Medion        | Akoya P2213T                | Notebook    | [7d201de7d6](https://linux-hardware.org/?probe=7d201de7d6) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5b93cd5b36](https://linux-hardware.org/?probe=5b93cd5b36) | Sep 11, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [7caa16d219](https://linux-hardware.org/?probe=7caa16d219) | Sep 11, 2023 |
| Olivetti      | OLIBOOK PX5-XXXAES          | Notebook    | [70225c18e1](https://linux-hardware.org/?probe=70225c18e1) | Sep 10, 2023 |
| Lenovo        | ThinkPad X250 20CLA1YJUK    | Notebook    | [a068fec56f](https://linux-hardware.org/?probe=a068fec56f) | Sep 09, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [b3756f752a](https://linux-hardware.org/?probe=b3756f752a) | Sep 08, 2023 |
| Medion        | Akoya P2213T                | Notebook    | [2464869ce2](https://linux-hardware.org/?probe=2464869ce2) | Sep 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [af67c49814](https://linux-hardware.org/?probe=af67c49814) | Sep 06, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [1056a6ebb4](https://linux-hardware.org/?probe=1056a6ebb4) | Sep 06, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [b9dddc1ef8](https://linux-hardware.org/?probe=b9dddc1ef8) | Sep 06, 2023 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [da9dc1f5d9](https://linux-hardware.org/?probe=da9dc1f5d9) | Sep 05, 2023 |
| Unknown       | SEI Robotics SEI610         | Soc         | [9b43cf14a3](https://linux-hardware.org/?probe=9b43cf14a3) | Sep 04, 2023 |
| HP            | 198E                        | Desktop     | [7f57cfbacc](https://linux-hardware.org/?probe=7f57cfbacc) | Sep 04, 2023 |
| AMD           | A88K                        | Desktop     | [d58c29d4ad](https://linux-hardware.org/?probe=d58c29d4ad) | Sep 03, 2023 |
| HP            | 2B2C                        | Desktop     | [a24d61a0f4](https://linux-hardware.org/?probe=a24d61a0f4) | Sep 02, 2023 |
| HP            | 198E                        | Desktop     | [3f3cb2e64c](https://linux-hardware.org/?probe=3f3cb2e64c) | Sep 02, 2023 |
| AMD           | A88K                        | Desktop     | [08a455504f](https://linux-hardware.org/?probe=08a455504f) | Sep 01, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [5ef4c889a4](https://linux-hardware.org/?probe=5ef4c889a4) | Aug 31, 2023 |
| OrangePi      | Zero3                       | Soc         | [34919a3af1](https://linux-hardware.org/?probe=34919a3af1) | Aug 31, 2023 |
| Dell          | Latitude E5510              | Notebook    | [61f6df7426](https://linux-hardware.org/?probe=61f6df7426) | Aug 29, 2023 |
| HP            | Pavilion 17                 | Notebook    | [ba077d7ea1](https://linux-hardware.org/?probe=ba077d7ea1) | Aug 29, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [74ad31c9de](https://linux-hardware.org/?probe=74ad31c9de) | Aug 29, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [f94a46ad17](https://linux-hardware.org/?probe=f94a46ad17) | Aug 28, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [f520b2dd72](https://linux-hardware.org/?probe=f520b2dd72) | Aug 28, 2023 |
| Unknown       | SEI Robotics SEI610         | Soc         | [9ee073735e](https://linux-hardware.org/?probe=9ee073735e) | Aug 28, 2023 |
| ASUSTek       | ROG Strix G733PY_G733PY     | Notebook    | [b886de0613](https://linux-hardware.org/?probe=b886de0613) | Aug 28, 2023 |
| HP            | Pavilion 17                 | Notebook    | [1d04c114d6](https://linux-hardware.org/?probe=1d04c114d6) | Aug 26, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [6edcb45992](https://linux-hardware.org/?probe=6edcb45992) | Aug 26, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [b7dce1f6e0](https://linux-hardware.org/?probe=b7dce1f6e0) | Aug 25, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [082e1c2cc1](https://linux-hardware.org/?probe=082e1c2cc1) | Aug 24, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [4d01543131](https://linux-hardware.org/?probe=4d01543131) | Aug 24, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [a7fbf7edf2](https://linux-hardware.org/?probe=a7fbf7edf2) | Aug 24, 2023 |
| Lenovo        | ThinkPad T460s 20F9003VM... | Notebook    | [e6e076d380](https://linux-hardware.org/?probe=e6e076d380) | Aug 23, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [b40144bd93](https://linux-hardware.org/?probe=b40144bd93) | Aug 22, 2023 |
| Acer          | TMP255-M                    | Notebook    | [4d5632e2d0](https://linux-hardware.org/?probe=4d5632e2d0) | Aug 22, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [aad70f30d7](https://linux-hardware.org/?probe=aad70f30d7) | Aug 21, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [22efc40cfd](https://linux-hardware.org/?probe=22efc40cfd) | Aug 21, 2023 |
| HP            | Presario CQ42               | Notebook    | [183f035603](https://linux-hardware.org/?probe=183f035603) | Aug 20, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a8a0c22567](https://linux-hardware.org/?probe=a8a0c22567) | Aug 20, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [ea6fdc81ab](https://linux-hardware.org/?probe=ea6fdc81ab) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f626ffa833](https://linux-hardware.org/?probe=f626ffa833) | Aug 17, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [48af3e541c](https://linux-hardware.org/?probe=48af3e541c) | Aug 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [5b482b674c](https://linux-hardware.org/?probe=5b482b674c) | Aug 16, 2023 |
| Lenovo        | ThinkPad X250 20CM001RMC    | Notebook    | [618a7e3e29](https://linux-hardware.org/?probe=618a7e3e29) | Aug 14, 2023 |
| Lenovo        | B50-50 80S2                 | Notebook    | [6c897e0c63](https://linux-hardware.org/?probe=6c897e0c63) | Aug 14, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [10d9228c2d](https://linux-hardware.org/?probe=10d9228c2d) | Aug 12, 2023 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [0ea140ff49](https://linux-hardware.org/?probe=0ea140ff49) | Aug 12, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [60de8d6d38](https://linux-hardware.org/?probe=60de8d6d38) | Aug 11, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [09000d6461](https://linux-hardware.org/?probe=09000d6461) | Aug 10, 2023 |
| Dell          | Latitude 3540               | Notebook    | [496e3ab340](https://linux-hardware.org/?probe=496e3ab340) | Aug 10, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [c05973af65](https://linux-hardware.org/?probe=c05973af65) | Aug 10, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [c5a255abcb](https://linux-hardware.org/?probe=c5a255abcb) | Aug 10, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [63f0153cfe](https://linux-hardware.org/?probe=63f0153cfe) | Aug 10, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [cc5ec06f60](https://linux-hardware.org/?probe=cc5ec06f60) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [14e4cbffd4](https://linux-hardware.org/?probe=14e4cbffd4) | Aug 08, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [150d68269d](https://linux-hardware.org/?probe=150d68269d) | Aug 08, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [047ae922f7](https://linux-hardware.org/?probe=047ae922f7) | Aug 07, 2023 |
| Dell          | Latitude 5411               | Notebook    | [2d69739196](https://linux-hardware.org/?probe=2d69739196) | Aug 07, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [341fecf811](https://linux-hardware.org/?probe=341fecf811) | Aug 06, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | Desktop     | [13f47a5399](https://linux-hardware.org/?probe=13f47a5399) | Aug 06, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0ffd23b534](https://linux-hardware.org/?probe=0ffd23b534) | Aug 04, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [122ba504c1](https://linux-hardware.org/?probe=122ba504c1) | Aug 04, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [a61b8168b7](https://linux-hardware.org/?probe=a61b8168b7) | Aug 02, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [485793f801](https://linux-hardware.org/?probe=485793f801) | Aug 02, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [80558a1dcd](https://linux-hardware.org/?probe=80558a1dcd) | Aug 02, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [aa9fd10def](https://linux-hardware.org/?probe=aa9fd10def) | Aug 01, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [67fbb84480](https://linux-hardware.org/?probe=67fbb84480) | Jul 31, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [1df8f3a3ed](https://linux-hardware.org/?probe=1df8f3a3ed) | Jul 29, 2023 |
| Medion        | Akoya P2213T                | Notebook    | [740da3bf14](https://linux-hardware.org/?probe=740da3bf14) | Jul 29, 2023 |
| Gateway       | NV57H                       | Notebook    | [efc311477f](https://linux-hardware.org/?probe=efc311477f) | Jul 28, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [136cb11fa2](https://linux-hardware.org/?probe=136cb11fa2) | Jul 28, 2023 |
| Samsung       | N250P/N145P                 | Notebook    | [6b6e675a4c](https://linux-hardware.org/?probe=6b6e675a4c) | Jul 28, 2023 |
| Acer          | Extensa 2510                | Notebook    | [b276a715eb](https://linux-hardware.org/?probe=b276a715eb) | Jul 27, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | Desktop     | [23633cafce](https://linux-hardware.org/?probe=23633cafce) | Jul 27, 2023 |
| Toshiba       | STI 005492G                 | Desktop     | [6e73cad7e4](https://linux-hardware.org/?probe=6e73cad7e4) | Jul 27, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [6a1aa5fbc8](https://linux-hardware.org/?probe=6a1aa5fbc8) | Jul 26, 2023 |
| Acer          | AOD255                      | Notebook    | [4f96dbf750](https://linux-hardware.org/?probe=4f96dbf750) | Jul 25, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [e1db241198](https://linux-hardware.org/?probe=e1db241198) | Jul 24, 2023 |
| Acer          | AOD255                      | Notebook    | [3543f0800e](https://linux-hardware.org/?probe=3543f0800e) | Jul 24, 2023 |
| MSI           | MEGA BOOK GX620             | Notebook    | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [38856f8131](https://linux-hardware.org/?probe=38856f8131) | Jul 21, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [977443386e](https://linux-hardware.org/?probe=977443386e) | Jul 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [187cbf1010](https://linux-hardware.org/?probe=187cbf1010) | Jul 21, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [287298e199](https://linux-hardware.org/?probe=287298e199) | Jul 21, 2023 |
| Itautec       | Infoway w7535               | Notebook    | [bde95c0c99](https://linux-hardware.org/?probe=bde95c0c99) | Jul 21, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [94c330e355](https://linux-hardware.org/?probe=94c330e355) | Jul 19, 2023 |
| Thomson       | N15C8BK2T                   | Notebook    | [2e04333da5](https://linux-hardware.org/?probe=2e04333da5) | Jul 19, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [08fc7fff38](https://linux-hardware.org/?probe=08fc7fff38) | Jul 17, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [c9a443767b](https://linux-hardware.org/?probe=c9a443767b) | Jul 16, 2023 |
| MSI           | Modern 15 A10RBS            | Notebook    | [fde24c2a13](https://linux-hardware.org/?probe=fde24c2a13) | Jul 15, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [0bd37865ac](https://linux-hardware.org/?probe=0bd37865ac) | Jul 15, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [d18c64af74](https://linux-hardware.org/?probe=d18c64af74) | Jul 14, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [e3e2452c10](https://linux-hardware.org/?probe=e3e2452c10) | Jul 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | Notebook    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [5aacfb69aa](https://linux-hardware.org/?probe=5aacfb69aa) | Jul 12, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8807f705d0](https://linux-hardware.org/?probe=8807f705d0) | Jul 12, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [d4bc86a90a](https://linux-hardware.org/?probe=d4bc86a90a) | Jul 12, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [5477254db4](https://linux-hardware.org/?probe=5477254db4) | Jul 10, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [db2ec8adc8](https://linux-hardware.org/?probe=db2ec8adc8) | Jul 08, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [4aba66ddfb](https://linux-hardware.org/?probe=4aba66ddfb) | Jul 07, 2023 |
| Dell          | Latitude 3540               | Notebook    | [4ebbd2913f](https://linux-hardware.org/?probe=4ebbd2913f) | Jul 06, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [abc4554a51](https://linux-hardware.org/?probe=abc4554a51) | Jul 04, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [983745a0d2](https://linux-hardware.org/?probe=983745a0d2) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [a5bd493e91](https://linux-hardware.org/?probe=a5bd493e91) | Jul 03, 2023 |
| Google        | Snappy                      | Notebook    | [683d8bf80a](https://linux-hardware.org/?probe=683d8bf80a) | Jul 02, 2023 |
| Google        | Snappy                      | Notebook    | [d3502a53cc](https://linux-hardware.org/?probe=d3502a53cc) | Jul 02, 2023 |
| HP            | Pavilion 17                 | Notebook    | [e6daccb5b9](https://linux-hardware.org/?probe=e6daccb5b9) | Jul 02, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [7c14851b62](https://linux-hardware.org/?probe=7c14851b62) | Jul 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [5270a5ddc7](https://linux-hardware.org/?probe=5270a5ddc7) | Jul 01, 2023 |
| Dynabook      | B65/ER                      | Notebook    | [8f6f243e98](https://linux-hardware.org/?probe=8f6f243e98) | Jul 01, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [196daaa768](https://linux-hardware.org/?probe=196daaa768) | Jun 30, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [8e7db66929](https://linux-hardware.org/?probe=8e7db66929) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [79f2cae4d6](https://linux-hardware.org/?probe=79f2cae4d6) | Jun 30, 2023 |
| Google        | Fleex                       | Notebook    | [7e3eb2d4f9](https://linux-hardware.org/?probe=7e3eb2d4f9) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [06d27800c2](https://linux-hardware.org/?probe=06d27800c2) | Jun 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| ASUSTek       | H61M-CS                     | Desktop     | [2878c06857](https://linux-hardware.org/?probe=2878c06857) | Jun 26, 2023 |
| HP            | 339A                        | Desktop     | [ff38f43250](https://linux-hardware.org/?probe=ff38f43250) | Jun 25, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [338b2e7db3](https://linux-hardware.org/?probe=338b2e7db3) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [7d1989fd84](https://linux-hardware.org/?probe=7d1989fd84) | Jun 24, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [a39abe1278](https://linux-hardware.org/?probe=a39abe1278) | Jun 24, 2023 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [2e4e948549](https://linux-hardware.org/?probe=2e4e948549) | Jun 22, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [8f879f5566](https://linux-hardware.org/?probe=8f879f5566) | Jun 21, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [66736b8fbb](https://linux-hardware.org/?probe=66736b8fbb) | Jun 21, 2023 |
| Intel         | H61                         | Desktop     | [d8de2bb1a7](https://linux-hardware.org/?probe=d8de2bb1a7) | Jun 20, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [ade4d4c90c](https://linux-hardware.org/?probe=ade4d4c90c) | Jun 19, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [154f9809e6](https://linux-hardware.org/?probe=154f9809e6) | Jun 18, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [66ce1a98a8](https://linux-hardware.org/?probe=66ce1a98a8) | Jun 18, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [10b3b517f3](https://linux-hardware.org/?probe=10b3b517f3) | Jun 18, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [4f0ec49165](https://linux-hardware.org/?probe=4f0ec49165) | Jun 17, 2023 |
| Unknown       | Minix Neo U9-H              | Soc         | [7b845b4b0b](https://linux-hardware.org/?probe=7b845b4b0b) | Jun 16, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [5a31ac8b21](https://linux-hardware.org/?probe=5a31ac8b21) | Jun 15, 2023 |
| Samsung       | 760XDA                      | Notebook    | [f0decf4dbe](https://linux-hardware.org/?probe=f0decf4dbe) | Jun 14, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [b0afd2fa7b](https://linux-hardware.org/?probe=b0afd2fa7b) | Jun 13, 2023 |
| Dell          | Latitude 5411               | Notebook    | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| Xunlong       | Orange Pi PC                | Soc         | [2a93adb1f0](https://linux-hardware.org/?probe=2a93adb1f0) | Jun 12, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [69f20a331c](https://linux-hardware.org/?probe=69f20a331c) | Jun 12, 2023 |
| Biostar       | TPower I45                  | Desktop     | [b88767bce0](https://linux-hardware.org/?probe=b88767bce0) | Jun 11, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| MSI           | A55M-E35                    | Desktop     | [7800efb785](https://linux-hardware.org/?probe=7800efb785) | Jun 08, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [2f5adf59a3](https://linux-hardware.org/?probe=2f5adf59a3) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Dell          | Precision 5510              | Notebook    | [9888f3aedd](https://linux-hardware.org/?probe=9888f3aedd) | Jun 06, 2023 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [83988ad739](https://linux-hardware.org/?probe=83988ad739) | Jun 06, 2023 |
| HP            | 8768 A                      | Desktop     | [17d0560a85](https://linux-hardware.org/?probe=17d0560a85) | Jun 05, 2023 |
| HP            | 21B4 A01                    | Desktop     | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [c716b12ee2](https://linux-hardware.org/?probe=c716b12ee2) | Jun 02, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Unknown       | Unknown                     | Notebook    | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Acer          | Veriton N4620G              | Desktop     | [4f2cc019b8](https://linux-hardware.org/?probe=4f2cc019b8) | May 26, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| Dell          | Latitude E4200              | Notebook    | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| Unknown       | 1.0                         | Desktop     | [54d3a069a4](https://linux-hardware.org/?probe=54d3a069a4) | May 22, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [584948af65](https://linux-hardware.org/?probe=584948af65) | May 19, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0b802ad297](https://linux-hardware.org/?probe=0b802ad297) | May 19, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bd7e95bf66](https://linux-hardware.org/?probe=bd7e95bf66) | May 18, 2023 |
| Pegatron      | Benicia                     | Desktop     | [8d49889e39](https://linux-hardware.org/?probe=8d49889e39) | May 18, 2023 |
| Google        | Snappy                      | Notebook    | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3a7b647f0b](https://linux-hardware.org/?probe=3a7b647f0b) | May 17, 2023 |
| HP            | 09F8h                       | Desktop     | [380bbcda71](https://linux-hardware.org/?probe=380bbcda71) | May 17, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0b0b5e02cc](https://linux-hardware.org/?probe=0b0b5e02cc) | May 13, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87edc3a632](https://linux-hardware.org/?probe=87edc3a632) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2d3692d380](https://linux-hardware.org/?probe=2d3692d380) | May 11, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [3c43bfe7bc](https://linux-hardware.org/?probe=3c43bfe7bc) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7b53d1c3dc](https://linux-hardware.org/?probe=7b53d1c3dc) | May 11, 2023 |
| Dell          | Latitude E4310              | Notebook    | [84d1a3fda9](https://linux-hardware.org/?probe=84d1a3fda9) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Unknown       | Kontron BL i.MX8MM OSM-S... | Soc         | [958fed11ae](https://linux-hardware.org/?probe=958fed11ae) | May 10, 2023 |
| Google        | Edgar                       | Notebook    | [372d5c177f](https://linux-hardware.org/?probe=372d5c177f) | May 10, 2023 |
| Gigabyte      | A7 K1                       | Notebook    | [1c37df2d10](https://linux-hardware.org/?probe=1c37df2d10) | May 09, 2023 |
| Google        | Snappy                      | Notebook    | [52836871bb](https://linux-hardware.org/?probe=52836871bb) | May 09, 2023 |
| Google        | Snappy                      | Notebook    | [a026aff306](https://linux-hardware.org/?probe=a026aff306) | May 09, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [0f322b6e3f](https://linux-hardware.org/?probe=0f322b6e3f) | May 08, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [c7d1eac585](https://linux-hardware.org/?probe=c7d1eac585) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [ebafddb3f1](https://linux-hardware.org/?probe=ebafddb3f1) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [307dfb1c46](https://linux-hardware.org/?probe=307dfb1c46) | May 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [c693555567](https://linux-hardware.org/?probe=c693555567) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [bbac197d5d](https://linux-hardware.org/?probe=bbac197d5d) | May 04, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [11e132041b](https://linux-hardware.org/?probe=11e132041b) | May 04, 2023 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [b735e1019b](https://linux-hardware.org/?probe=b735e1019b) | May 03, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| HP            | 15                          | Notebook    | [17817f5320](https://linux-hardware.org/?probe=17817f5320) | May 02, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [36f4134c6b](https://linux-hardware.org/?probe=36f4134c6b) | May 01, 2023 |
| Toshiba       | EQUIUM P200                 | Notebook    | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | Notebook    | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| SGIN          | M15                         | Notebook    | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [4382f0cce7](https://linux-hardware.org/?probe=4382f0cce7) | Apr 27, 2023 |
| HP            | 1632                        | Desktop     | [b818834691](https://linux-hardware.org/?probe=b818834691) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [caae9b5992](https://linux-hardware.org/?probe=caae9b5992) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | Notebook    | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [4611a1d998](https://linux-hardware.org/?probe=4611a1d998) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | Notebook    | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| HP            | 0AECh D                     | Desktop     | [827246f901](https://linux-hardware.org/?probe=827246f901) | Apr 22, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3e1880b375](https://linux-hardware.org/?probe=3e1880b375) | Apr 20, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [9f2a1a2c93](https://linux-hardware.org/?probe=9f2a1a2c93) | Apr 19, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [222f45e8c6](https://linux-hardware.org/?probe=222f45e8c6) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4c6934e946](https://linux-hardware.org/?probe=4c6934e946) | Apr 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5fc4a56d59](https://linux-hardware.org/?probe=5fc4a56d59) | Apr 17, 2023 |
| ASRock        | N3700-ITX                   | Desktop     | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASRock        | X370 Killer SLI             | Desktop     | [912a7f830b](https://linux-hardware.org/?probe=912a7f830b) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [b901ff7e98](https://linux-hardware.org/?probe=b901ff7e98) | Apr 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [7f4ed3cfde](https://linux-hardware.org/?probe=7f4ed3cfde) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Nuvision      | Aptio CRB                   | Mini pc     | [93fae77e6c](https://linux-hardware.org/?probe=93fae77e6c) | Apr 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Medion        | MS-7848                     | Desktop     | [40e46961a4](https://linux-hardware.org/?probe=40e46961a4) | Apr 08, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [71ee0575d4](https://linux-hardware.org/?probe=71ee0575d4) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [c7444ac7f0](https://linux-hardware.org/?probe=c7444ac7f0) | Apr 07, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [fc1b119dca](https://linux-hardware.org/?probe=fc1b119dca) | Apr 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [2ac5f02bb5](https://linux-hardware.org/?probe=2ac5f02bb5) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5aa68e620c](https://linux-hardware.org/?probe=5aa68e620c) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | Notebook    | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [f7cdc4223d](https://linux-hardware.org/?probe=f7cdc4223d) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| Medion        | S321X                       | Notebook    | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| MSI           | MS-AA8B 100                 | All in one  | [8f698075ee](https://linux-hardware.org/?probe=8f698075ee) | Mar 27, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [426c7d7939](https://linux-hardware.org/?probe=426c7d7939) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [a822425dcf](https://linux-hardware.org/?probe=a822425dcf) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| MSI           | H81M-E33                    | Desktop     | [47f031e68c](https://linux-hardware.org/?probe=47f031e68c) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bbd16627c2](https://linux-hardware.org/?probe=bbd16627c2) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | Notebook    | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [5c07e530e9](https://linux-hardware.org/?probe=5c07e530e9) | Mar 21, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| Gateway       | EC14 Series                 | Notebook    | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4cad3cfe12](https://linux-hardware.org/?probe=4cad3cfe12) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | Notebook    | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a6af61dfb4](https://linux-hardware.org/?probe=a6af61dfb4) | Mar 13, 2023 |
| Google        | Kefka                       | Notebook    | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ac565d5d7d](https://linux-hardware.org/?probe=ac565d5d7d) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | Notebook    | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| Foxconn       | ETON                        | Desktop     | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ad41e0e370](https://linux-hardware.org/?probe=ad41e0e370) | Mar 09, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Foxconn       | ETON                        | Desktop     | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [44509323b0](https://linux-hardware.org/?probe=44509323b0) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [32dedf99a8](https://linux-hardware.org/?probe=32dedf99a8) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [5bd9a1c0d2](https://linux-hardware.org/?probe=5bd9a1c0d2) | Mar 07, 2023 |
| Toshiba       | Satellite C55D-B            | Notebook    | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ec9c2f21a5](https://linux-hardware.org/?probe=ec9c2f21a5) | Mar 05, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [e513434675](https://linux-hardware.org/?probe=e513434675) | Mar 04, 2023 |
| Radxa         | ROCK Pi 4C+                 | Soc         | [5c3d9047bd](https://linux-hardware.org/?probe=5c3d9047bd) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| OEM           | Unknown                     | Desktop     | [d0f1ae246c](https://linux-hardware.org/?probe=d0f1ae246c) | Mar 03, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [e367c45f3b](https://linux-hardware.org/?probe=e367c45f3b) | Mar 03, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| Google        | Nautilus                    | Convertible | [5aff7271ac](https://linux-hardware.org/?probe=5aff7271ac) | Mar 02, 2023 |
| AZW           | GTR V01                     | Mini pc     | [09e66839c3](https://linux-hardware.org/?probe=09e66839c3) | Mar 01, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [525ac20362](https://linux-hardware.org/?probe=525ac20362) | Feb 26, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| Dell          | Studio 1450                 | Notebook    | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [c9adb74693](https://linux-hardware.org/?probe=c9adb74693) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Sony          | VPCEA3S1E                   | Notebook    | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [40c415883e](https://linux-hardware.org/?probe=40c415883e) | Feb 16, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [21ad600245](https://linux-hardware.org/?probe=21ad600245) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| ASRock        | AOD790GX/128M               | Desktop     | [693f4f40f8](https://linux-hardware.org/?probe=693f4f40f8) | Feb 13, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Dell          | Latitude E5450              | Notebook    | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [59a015c31d](https://linux-hardware.org/?probe=59a015c31d) | Feb 11, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| HP            | 240 G3                      | Notebook    | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | Notebook    | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [a05562bc52](https://linux-hardware.org/?probe=a05562bc52) | Feb 02, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [10421fe598](https://linux-hardware.org/?probe=10421fe598) | Jan 30, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Notebook      | W65_67SZ                    | Notebook    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7e91e49912](https://linux-hardware.org/?probe=7e91e49912) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3324fafe5a](https://linux-hardware.org/?probe=3324fafe5a) | Jan 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b5e6a74fcb](https://linux-hardware.org/?probe=b5e6a74fcb) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Gigabyte      | 8I945GMF                    | Desktop     | [2971006e43](https://linux-hardware.org/?probe=2971006e43) | Jan 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Dell          | Venue 11 Pro 7139           | Notebook    | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d5ad4c9486](https://linux-hardware.org/?probe=d5ad4c9486) | Jan 17, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a49a3ddeaa](https://linux-hardware.org/?probe=a49a3ddeaa) | Jan 17, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| HP            | 873A A01                    | Mini pc     | [5c3be4e9aa](https://linux-hardware.org/?probe=5c3be4e9aa) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [ef5e737fd6](https://linux-hardware.org/?probe=ef5e737fd6) | Jan 04, 2023 |
| MiPi PC       | Mini PC                     | Mini pc     | [776c827bdb](https://linux-hardware.org/?probe=776c827bdb) | Jan 03, 2023 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [da1db1e278](https://linux-hardware.org/?probe=da1db1e278) | Jan 02, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | Notebook    | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| Dell          | Latitude E5450              | Notebook    | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Sony          | VPCS12V9E                   | Notebook    | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [f64e5ab064](https://linux-hardware.org/?probe=f64e5ab064) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | Notebook    | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [282ef194e5](https://linux-hardware.org/?probe=282ef194e5) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [d65a8640af](https://linux-hardware.org/?probe=d65a8640af) | Dec 11, 2022 |
| HP            | 1497                        | Desktop     | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Fusion5       | Lapbook T90B                | Notebook    | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 44        | 4.1%    |
| 5.15.0-52-generic | 35        | 3.26%   |
| 5.15.0-47-generic | 31        | 2.89%   |
| 6.2.0-26-generic  | 30        | 2.8%    |
| 5.15.0-58-generic | 27        | 2.52%   |
| 5.15.0-48-generic | 25        | 2.33%   |
| 6.5.0-26-generic  | 23        | 2.15%   |
| 5.15.0-60-generic | 23        | 2.15%   |
| 5.15.0-25-generic | 22        | 2.05%   |
| 6.2.0-39-generic  | 20        | 1.87%   |
| 5.15.0-67-generic | 20        | 1.87%   |
| 5.15.0-46-generic | 17        | 1.59%   |
| 6.5.0-35-generic  | 16        | 1.49%   |
| 5.15.0-43-generic | 15        | 1.4%    |
| 6.2.0-36-generic  | 14        | 1.31%   |
| 6.2.0-32-generic  | 14        | 1.31%   |
| 5.19.0-35-generic | 14        | 1.31%   |
| 5.15.0-71-generic | 14        | 1.31%   |
| 5.15.0-53-generic | 14        | 1.31%   |
| 5.15.0-27-generic | 14        | 1.31%   |
| 6.2.0-37-generic  | 13        | 1.21%   |
| 5.19.0-45-generic | 13        | 1.21%   |
| 5.19.0-41-generic | 13        | 1.21%   |
| 6.5.0-15-generic  | 12        | 1.12%   |
| 5.19.0-46-generic | 12        | 1.12%   |
| 6.5.0-41-generic  | 11        | 1.03%   |
| 6.5.0-25-generic  | 11        | 1.03%   |
| 6.5.0-21-generic  | 11        | 1.03%   |
| 5.15.0-78-generic | 11        | 1.03%   |
| 5.15.0-69-generic | 11        | 1.03%   |
| 6.8.0-40-generic  | 10        | 0.93%   |
| 6.5.0-28-generic  | 10        | 0.93%   |
| 6.5.0-18-generic  | 10        | 0.93%   |
| 6.5.0-14-generic  | 10        | 0.93%   |
| 5.19.0-50-generic | 10        | 0.93%   |
| 5.19.0-38-generic | 10        | 0.93%   |
| 5.15.0-91-generic | 10        | 0.93%   |
| 5.15.0-57-generic | 10        | 0.93%   |
| 5.19.0-43-generic | 9         | 0.84%   |
| 5.15.0-76-generic | 9         | 0.84%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 524       | 53.52%  |
| 6.5.0    | 116       | 11.85%  |
| 6.2.0    | 114       | 11.64%  |
| 5.19.0   | 92        | 9.4%    |
| 6.8.0    | 48        | 4.9%    |
| 5.17.0   | 11        | 1.12%   |
| 6.1.0    | 10        | 1.02%   |
| 6.1.31   | 5         | 0.51%   |
| 6.1.30   | 3         | 0.31%   |
| 6.0.0    | 3         | 0.31%   |
| 5.13.0   | 3         | 0.31%   |
| 5.10.110 | 3         | 0.31%   |
| 6.2.7    | 2         | 0.2%    |
| 5.4.0    | 2         | 0.2%    |
| 5.18.0   | 2         | 0.2%    |
| 5.15.93  | 2         | 0.2%    |
| 4.19.241 | 2         | 0.2%    |
| 6.6.2    | 1         | 0.1%    |
| 6.6.16   | 1         | 0.1%    |
| 6.5.7    | 1         | 0.1%    |
| 6.4.8    | 1         | 0.1%    |
| 6.4.15   | 1         | 0.1%    |
| 6.4.0    | 1         | 0.1%    |
| 6.3.3    | 1         | 0.1%    |
| 6.3.12   | 1         | 0.1%    |
| 6.2.9    | 1         | 0.1%    |
| 6.2.2    | 1         | 0.1%    |
| 6.2.10   | 1         | 0.1%    |
| 6.1.83   | 1         | 0.1%    |
| 6.1.6    | 1         | 0.1%    |
| 6.1.50   | 1         | 0.1%    |
| 6.1.43   | 1         | 0.1%    |
| 6.1.10   | 1         | 0.1%    |
| 6.0.9    | 1         | 0.1%    |
| 6.0.7    | 1         | 0.1%    |
| 5.19.5   | 1         | 0.1%    |
| 5.19.17  | 1         | 0.1%    |
| 5.19.13  | 1         | 0.1%    |
| 5.19.1   | 1         | 0.1%    |
| 5.18.5   | 1         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 534       | 54.6%   |
| 6.2     | 119       | 12.17%  |
| 6.5     | 117       | 11.96%  |
| 5.19    | 96        | 9.82%   |
| 6.8     | 48        | 4.91%   |
| 6.1     | 22        | 2.25%   |
| 5.17    | 13        | 1.33%   |
| 6.0     | 5         | 0.51%   |
| 5.18    | 4         | 0.41%   |
| 5.10    | 4         | 0.41%   |
| 6.4     | 3         | 0.31%   |
| 5.13    | 3         | 0.31%   |
| 6.6     | 2         | 0.2%    |
| 6.3     | 2         | 0.2%    |
| 5.4     | 2         | 0.2%    |
| 4.19    | 2         | 0.2%    |
| 5.16    | 1         | 0.1%    |
| 4.15    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 916       | 96.93%  |
| aarch64 | 24        | 2.54%   |
| armv7l  | 5         | 0.53%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 920       | 97.05%  |
| GNOME           | 18        | 1.9%    |
| KDE5            | 3         | 0.32%   |
| X-Cinnamon      | 2         | 0.21%   |
| i3              | 2         | 0.21%   |
| GNOME Flashback | 2         | 0.21%   |
| LXDE            | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 897       | 94.32%  |
| Tty     | 38        | 4%      |
| Wayland | 13        | 1.37%   |
| Unknown | 2         | 0.21%   |
| Web     | 1         | 0.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 804       | 84.81%  |
| Unknown | 69        | 7.28%   |
| GDM3    | 61        | 6.43%   |
| SDDM    | 10        | 1.05%   |
| SLiM    | 2         | 0.21%   |
| LXDM    | 1         | 0.11%   |
| GDM     | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 372       | 39.32%  |
| fr_FR   | 126       | 13.32%  |
| de_DE   | 100       | 10.57%  |
| it_IT   | 51        | 5.39%   |
| pt_BR   | 36        | 3.81%   |
| en_GB   | 36        | 3.81%   |
| ru_RU   | 25        | 2.64%   |
| en_CA   | 25        | 2.64%   |
| C       | 18        | 1.9%    |
| es_ES   | 17        | 1.8%    |
| pl_PL   | 15        | 1.59%   |
| en_AU   | 14        | 1.48%   |
| en_IN   | 9         | 0.95%   |
| cs_CZ   | 9         | 0.95%   |
| zh_CN   | 7         | 0.74%   |
| nl_NL   | 6         | 0.63%   |
| ja_JP   | 5         | 0.53%   |
| hu_HU   | 5         | 0.53%   |
| es_AR   | 5         | 0.53%   |
| es_VE   | 4         | 0.42%   |
| es_MX   | 4         | 0.42%   |
| de_CH   | 4         | 0.42%   |
| tr_TR   | 3         | 0.32%   |
| nl_BE   | 3         | 0.32%   |
| fr_BE   | 3         | 0.32%   |
| fi_FI   | 3         | 0.32%   |
| es_CO   | 3         | 0.32%   |
| es_CL   | 3         | 0.32%   |
| ru_UA   | 2         | 0.21%   |
| ro_RO   | 2         | 0.21%   |
| pt_PT   | 2         | 0.21%   |
| fr_CA   | 2         | 0.21%   |
| en_ZA   | 2         | 0.21%   |
| en_NZ   | 2         | 0.21%   |
| en_IE   | 2         | 0.21%   |
| de_AT   | 2         | 0.21%   |
| Unknown | 2         | 0.21%   |
| zh_TW   | 1         | 0.11%   |
| sv_SE   | 1         | 0.11%   |
| sl_SI   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 481       | 50.31%  |
| BIOS | 475       | 49.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 762       | 78.72%  |
| Tmpfs   | 139       | 14.36%  |
| Overlay | 32        | 3.31%   |
| Zfs     | 16        | 1.65%   |
| Btrfs   | 16        | 1.65%   |
| Ext3    | 2         | 0.21%   |
| Xfs     | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 692       | 71.86%  |
| MBR     | 161       | 16.72%  |
| Unknown | 110       | 11.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 825       | 85.76%  |
| Yes       | 137       | 14.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 662       | 69.68%  |
| Yes       | 288       | 30.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 151       | 15.98%  |
| ASUSTek Computer                     | 130       | 13.76%  |
| Hewlett-Packard                      | 127       | 13.44%  |
| Dell                                 | 125       | 13.23%  |
| Acer                                 | 54        | 5.71%   |
| Gigabyte Technology                  | 52        | 5.5%    |
| MSI                                  | 47        | 4.97%   |
| Apple                                | 25        | 2.65%   |
| ASRock                               | 22        | 2.33%   |
| Intel                                | 17        | 1.8%    |
| Google                               | 16        | 1.69%   |
| Toshiba                              | 15        | 1.59%   |
| Unknown                              | 15        | 1.59%   |
| Fujitsu                              | 9         | 0.95%   |
| Sony                                 | 8         | 0.85%   |
| Medion                               | 8         | 0.85%   |
| Samsung Electronics                  | 7         | 0.74%   |
| AZW                                  | 7         | 0.74%   |
| Rockchip                             | 6         | 0.63%   |
| OrangePi                             | 6         | 0.63%   |
| Supermicro                           | 5         | 0.53%   |
| Packard Bell                         | 5         | 0.53%   |
| GPU Company                          | 5         | 0.53%   |
| Notebook                             | 4         | 0.42%   |
| HUAWEI                               | 4         | 0.42%   |
| Radxa                                | 3         | 0.32%   |
| Pegatron                             | 3         | 0.32%   |
| Foxconn                              | 3         | 0.32%   |
| eMachines                            | 3         | 0.32%   |
| AMI                                  | 3         | 0.32%   |
| Xunlong                              | 2         | 0.21%   |
| sunxi                                | 2         | 0.21%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.21%   |
| PCWare                               | 2         | 0.21%   |
| Microsoft                            | 2         | 0.21%   |
| MACHINIST                            | 2         | 0.21%   |
| Itautec                              | 2         | 0.21%   |
| Inventec                             | 2         | 0.21%   |
| HONOR                                | 2         | 0.21%   |
| Gateway                              | 2         | 0.21%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 17        | 1.8%    |
| ASUS All Series                        | 7         | 0.74%   |
| Dell OptiPlex 7010                     | 6         | 0.63%   |
| OrangePi Zero3                         | 4         | 0.42%   |
| HP EliteBook 840 G3                    | 4         | 0.42%   |
| Google Snappy                          | 4         | 0.42%   |
| MSI MS-7D43                            | 3         | 0.32%   |
| MSI MS-7721                            | 3         | 0.32%   |
| Lenovo ThinkCentre M83z 10C20003FR     | 3         | 0.32%   |
| HP Pavilion dv7                        | 3         | 0.32%   |
| HP Pavilion dv6                        | 3         | 0.32%   |
| HP Pavilion 17                         | 3         | 0.32%   |
| HP Laptop 15s-fq2xxx                   | 3         | 0.32%   |
| HP 15                                  | 3         | 0.32%   |
| ASUS PRIME A320M-K                     | 3         | 0.32%   |
| ASUS K30AD_M31AD_M51AD                 | 3         | 0.32%   |
| Apple MacBookPro8,1                    | 3         | 0.32%   |
| Acer Switch SW312-31                   | 3         | 0.32%   |
| Toshiba Satellite A200                 | 2         | 0.21%   |
| Rockchip RK3318 BOX                    | 2         | 0.21%   |
| Rockchip Orange Pi 5                   | 2         | 0.21%   |
| MSI MS-7D46                            | 2         | 0.21%   |
| MSI MS-7D25                            | 2         | 0.21%   |
| MSI MS-7C52                            | 2         | 0.21%   |
| MSI MS-7817                            | 2         | 0.21%   |
| MSI MS-7758                            | 2         | 0.21%   |
| Lenovo V530S-07ICB 10TX0010PB          | 2         | 0.21%   |
| Lenovo ThinkPad P50 20EN0013US         | 2         | 0.21%   |
| Lenovo ThinkCentre M75q-1 11A5S0BB01   | 2         | 0.21%   |
| Lenovo IdeaPad 5 15ABA7 82SG           | 2         | 0.21%   |
| Lenovo IdeaPad 100-15IBY 80MJ          | 2         | 0.21%   |
| Lenovo IdeaPad 1 15AMN7 82VG           | 2         | 0.21%   |
| Inventec Dell Thin Client Desktop 5060 | 2         | 0.21%   |
| Intel D54250WYK H13922-303             | 2         | 0.21%   |
| HUAWEI BOHK-WAX9X                      | 2         | 0.21%   |
| HP t620 Quad Core TC                   | 2         | 0.21%   |
| HP Stream Laptop 14-ds0xxx             | 2         | 0.21%   |
| HP Pavilion Notebook                   | 2         | 0.21%   |
| HP Pavilion g7                         | 2         | 0.21%   |
| HP Pavilion g6                         | 2         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 72        | 7.62%   |
| Acer Aspire           | 35        | 3.7%    |
| Dell Latitude         | 34        | 3.6%    |
| Lenovo IdeaPad        | 27        | 2.86%   |
| HP Pavilion           | 27        | 2.86%   |
| Dell Inspiron         | 25        | 2.65%   |
| Dell OptiPlex         | 22        | 2.33%   |
| ASUS PRIME            | 20        | 2.12%   |
| ASUS ROG              | 17        | 1.8%    |
| Unknown               | 17        | 1.8%    |
| HP EliteBook          | 16        | 1.69%   |
| Lenovo ThinkCentre    | 13        | 1.38%   |
| HP Laptop             | 13        | 1.38%   |
| Dell XPS              | 13        | 1.38%   |
| Dell Precision        | 12        | 1.27%   |
| Toshiba Satellite     | 11        | 1.16%   |
| HP Compaq             | 10        | 1.06%   |
| ASUS VivoBook         | 9         | 0.95%   |
| ASUS TUF              | 8         | 0.85%   |
| ASUS All              | 7         | 0.74%   |
| Lenovo Yoga           | 6         | 0.63%   |
| HP ProBook            | 6         | 0.63%   |
| Dell Vostro           | 6         | 0.63%   |
| Dell PowerEdge        | 6         | 0.63%   |
| Lenovo ThinkBook      | 5         | 0.53%   |
| HP EliteDesk          | 5         | 0.53%   |
| ASUS ASUS             | 5         | 0.53%   |
| OrangePi Zero3        | 4         | 0.42%   |
| HP Stream             | 4         | 0.42%   |
| HP 255                | 4         | 0.42%   |
| HP 250                | 4         | 0.42%   |
| Google Snappy         | 4         | 0.42%   |
| Acer Veriton          | 4         | 0.42%   |
| Radxa ROCK            | 3         | 0.32%   |
| Packard Bell EasyNote | 3         | 0.32%   |
| MSI MS-7D43           | 3         | 0.32%   |
| MSI MS-7721           | 3         | 0.32%   |
| MSI Modern            | 3         | 0.32%   |
| HP ZBook              | 3         | 0.32%   |
| HP 15                 | 3         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 78        | 8.25%   |
| 2013    | 72        | 7.62%   |
| 2020    | 71        | 7.51%   |
| 2012    | 64        | 6.77%   |
| 2022    | 60        | 6.35%   |
| 2018    | 59        | 6.24%   |
| 2014    | 59        | 6.24%   |
| 2017    | 58        | 6.14%   |
| 2015    | 57        | 6.03%   |
| 2011    | 54        | 5.71%   |
| 2016    | 52        | 5.5%    |
| 2010    | 51        | 5.4%    |
| 2019    | 45        | 4.76%   |
| 2009    | 36        | 3.81%   |
| 2023    | 30        | 3.17%   |
| 2008    | 30        | 3.17%   |
| Unknown | 29        | 3.07%   |
| 2007    | 24        | 2.54%   |
| 2006    | 8         | 0.85%   |
| 2025    | 3         | 0.32%   |
| 2024    | 3         | 0.32%   |
| 2005    | 2         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 509       | 53.86%  |
| Desktop        | 337       | 35.66%  |
| System on chip | 28        | 2.96%   |
| Mini pc        | 26        | 2.75%   |
| Convertible    | 14        | 1.48%   |
| Server         | 13        | 1.38%   |
| All in one     | 12        | 1.27%   |
| Tablet         | 6         | 0.63%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 878       | 91.94%  |
| Enabled  | 77        | 8.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 929       | 98.31%  |
| Yes  | 16        | 1.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 232       | 24.32%  |
| 4.01-8.0        | 223       | 23.38%  |
| 16.01-24.0      | 149       | 15.62%  |
| 8.01-16.0       | 130       | 13.63%  |
| 32.01-64.0      | 87        | 9.12%   |
| 1.01-2.0        | 42        | 4.4%    |
| 64.01-256.0     | 40        | 4.19%   |
| 24.01-32.0      | 24        | 2.52%   |
| 2.01-3.0        | 17        | 1.78%   |
| 0.51-1.0        | 5         | 0.52%   |
| More than 256.0 | 4         | 0.42%   |
| 0.01-0.5        | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 370       | 36.24%  |
| 2.01-3.0   | 251       | 24.58%  |
| 4.01-8.0   | 136       | 13.32%  |
| 3.01-4.0   | 111       | 10.87%  |
| 0.51-1.0   | 81        | 7.93%   |
| 8.01-16.0  | 52        | 5.09%   |
| 16.01-24.0 | 11        | 1.08%   |
| 0.01-0.5   | 6         | 0.59%   |
| 24.01-32.0 | 2         | 0.2%    |
| 32.01-64.0 | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 604       | 62.79%  |
| 2      | 230       | 23.91%  |
| 3      | 62        | 6.44%   |
| 4      | 31        | 3.22%   |
| 5      | 14        | 1.46%   |
| 6      | 8         | 0.83%   |
| 0      | 5         | 0.52%   |
| 7      | 4         | 0.42%   |
| 22     | 1         | 0.1%    |
| 10     | 1         | 0.1%    |
| 9      | 1         | 0.1%    |
| 8      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 585       | 61.77%  |
| Yes       | 362       | 38.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 787       | 83.19%  |
| No        | 159       | 16.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 707       | 74.5%   |
| No        | 242       | 25.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 543       | 57.28%  |
| No        | 405       | 42.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 165       | 17.37%  |
| France      | 131       | 13.79%  |
| Germany     | 120       | 12.63%  |
| Italy       | 57        | 6%      |
| Brazil      | 45        | 4.74%   |
| Russia      | 35        | 3.68%   |
| Canada      | 32        | 3.37%   |
| UK          | 29        | 3.05%   |
| Poland      | 28        | 2.95%   |
| Spain       | 20        | 2.11%   |
| Sweden      | 18        | 1.89%   |
| Netherlands | 17        | 1.79%   |
| Czechia     | 16        | 1.68%   |
| Australia   | 14        | 1.47%   |
| India       | 13        | 1.37%   |
| Belgium     | 13        | 1.37%   |
| Mexico      | 12        | 1.26%   |
| Switzerland | 10        | 1.05%   |
| China       | 10        | 1.05%   |
| Argentina   | 10        | 1.05%   |
| Japan       | 8         | 0.84%   |
| Austria     | 8         | 0.84%   |
| Colombia    | 7         | 0.74%   |
| Iran        | 6         | 0.63%   |
| Hungary     | 6         | 0.63%   |
| Greece      | 6         | 0.63%   |
| Serbia      | 5         | 0.53%   |
| Portugal    | 5         | 0.53%   |
| Malaysia    | 5         | 0.53%   |
| Finland     | 5         | 0.53%   |
| Belarus     | 5         | 0.53%   |
| Venezuela   | 4         | 0.42%   |
| Turkey      | 4         | 0.42%   |
| Slovenia    | 4         | 0.42%   |
| Romania     | 4         | 0.42%   |
| New Zealand | 4         | 0.42%   |
| Indonesia   | 4         | 0.42%   |
| Denmark     | 4         | 0.42%   |
| Bulgaria    | 4         | 0.42%   |
| Vietnam     | 3         | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 14        | 1.41%   |
| Berlin           | 12        | 1.21%   |
| Warsaw           | 11        | 1.11%   |
| Milan            | 9         | 0.91%   |
| Munich           | 8         | 0.81%   |
| Melbourne        | 8         | 0.81%   |
| Rome             | 7         | 0.71%   |
| Moscow           | 7         | 0.71%   |
| Stuttgart        | 6         | 0.61%   |
| St Petersburg    | 6         | 0.61%   |
| Springfield      | 6         | 0.61%   |
| Hamburg          | 6         | 0.61%   |
| Amsterdam        | 6         | 0.61%   |
| Toulouse         | 5         | 0.5%    |
| Rio de Janeiro   | 5         | 0.5%    |
| Prague           | 5         | 0.5%    |
| Helsinki         | 5         | 0.5%    |
| Harrisonburg     | 5         | 0.5%    |
| Budapest         | 5         | 0.5%    |
| Valenciennes     | 4         | 0.4%    |
| Uppsala          | 4         | 0.4%    |
| Toronto          | 4         | 0.4%    |
| Tehran           | 4         | 0.4%    |
| Sydney           | 4         | 0.4%    |
| Rho              | 4         | 0.4%    |
| Los Angeles      | 4         | 0.4%    |
| Hanover          | 4         | 0.4%    |
| Dublin           | 4         | 0.4%    |
| Copenhagen       | 4         | 0.4%    |
| Bucharest        | 4         | 0.4%    |
| Athens           | 4         | 0.4%    |
| Washington       | 3         | 0.3%    |
| Sombor           | 3         | 0.3%    |
| Shanghai         | 3         | 0.3%    |
| Santiago de Cali | 3         | 0.3%    |
| Puteaux          | 3         | 0.3%    |
| Nykvarn          | 3         | 0.3%    |
| North Hills      | 3         | 0.3%    |
| Muncie           | 3         | 0.3%    |
| Montreal         | 3         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 199       | 262    | 14.83%  |
| WDC                         | 187       | 283    | 13.93%  |
| Seagate                     | 145       | 202    | 10.8%   |
| Unknown                     | 99        | 129    | 7.38%   |
| Kingston                    | 92        | 116    | 6.86%   |
| SanDisk                     | 72        | 86     | 5.37%   |
| Toshiba                     | 57        | 72     | 4.25%   |
| Hitachi                     | 50        | 85     | 3.73%   |
| Crucial                     | 44        | 51     | 3.28%   |
| SK hynix                    | 38        | 45     | 2.83%   |
| Intel                       | 31        | 36     | 2.31%   |
| Micron Technology           | 23        | 27     | 1.71%   |
| China                       | 19        | 23     | 1.42%   |
| HGST                        | 18        | 27     | 1.34%   |
| PNY                         | 17        | 23     | 1.27%   |
| A-DATA Technology           | 17        | 24     | 1.27%   |
| SPCC                        | 14        | 19     | 1.04%   |
| Unknown                     | 14        | 14     | 1.04%   |
| Intenso                     | 10        | 10     | 0.75%   |
| KIOXIA                      | 9         | 12     | 0.67%   |
| Transcend                   | 8         | 12     | 0.6%    |
| Phison Electronics          | 8         | 13     | 0.6%    |
| Kingston Technology Company | 8         | 13     | 0.6%    |
| Apple                       | 8         | 11     | 0.6%    |
| Phison                      | 7         | 14     | 0.52%   |
| Patriot                     | 6         | 6      | 0.45%   |
| Hewlett-Packard             | 6         | 9      | 0.45%   |
| Fujitsu                     | 6         | 6      | 0.45%   |
| Silicon Motion              | 5         | 5      | 0.37%   |
| Gigabyte Technology         | 5         | 8      | 0.37%   |
| ASMT                        | 5         | 11     | 0.37%   |
| TO Exter                    | 4         | 5      | 0.3%    |
| PHD 3.0                     | 4         | 5      | 0.3%    |
| LITEON                      | 4         | 4      | 0.3%    |
| USB3.0                      | 3         | 5      | 0.22%   |
| Team                        | 3         | 6      | 0.22%   |
| SSK                         | 3         | 4      | 0.22%   |
| Realtek Semiconductor       | 3         | 4      | 0.22%   |
| Netac                       | 3         | 3      | 0.22%   |
| Maxtor                      | 3         | 3      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 20        | 1.36%   |
| Samsung SSD 860 EVO 500GB                         | 19        | 1.29%   |
| Unknown                                           | 14        | 0.95%   |
| Kingston SA400S37480G 480GB SSD                   | 13        | 0.89%   |
| Unknown SD/MMC/MS PRO 2GB                         | 11        | 0.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 11        | 0.75%   |
| Crucial CT480BX500SSD1 480GB                      | 10        | 0.68%   |
| Unknown MMC Card  32GB                            | 9         | 0.61%   |
| Toshiba DT01ACA100 1TB                            | 9         | 0.61%   |
| Seagate ST500LT012-1DG142 500GB                   | 9         | 0.61%   |
| Seagate ST500DM002-1BD142 500GB                   | 8         | 0.54%   |
| Kingston SA400S37120G 120GB SSD                   | 8         | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB                    | 7         | 0.48%   |
| Samsung SSD 850 EVO 500GB                         | 7         | 0.48%   |
| Unknown MMC Card  64GB                            | 6         | 0.41%   |
| Toshiba MQ01ABF050 500GB                          | 6         | 0.41%   |
| Seagate ST1000LM048-2E7172 1TB                    | 6         | 0.41%   |
| Samsung SSD 850 EVO 250GB                         | 6         | 0.41%   |
| Intel SSDPEKNU512GZ 512GB                         | 6         | 0.41%   |
| WDC WD5000AAKX-08U6AA0 500GB                      | 5         | 0.34%   |
| Unknown MMC Card  16GB                            | 5         | 0.34%   |
| Unknown MMC Card  128GB                           | 5         | 0.34%   |
| Toshiba HDWD110 1TB                               | 5         | 0.34%   |
| Toshiba DT01ACA200 2TB                            | 5         | 0.34%   |
| Seagate ST2000DM008-2FR102 2TB                    | 5         | 0.34%   |
| Seagate ST2000DM001-1ER164 2TB                    | 5         | 0.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 5         | 0.34%   |
| Seagate ST1000DM003-1CH162 1TB                    | 5         | 0.34%   |
| SanDisk SDSSDA240G 240GB                          | 5         | 0.34%   |
| SanDisk DF4064  64GB                              | 5         | 0.34%   |
| Samsung SSD 970 EVO Plus 1TB                      | 5         | 0.34%   |
| Samsung SSD 870 QVO 1TB                           | 5         | 0.34%   |
| Samsung SSD 870 EVO 1TB                           | 5         | 0.34%   |
| Kingston SV300S37A120G 120GB SSD                  | 5         | 0.34%   |
| Crucial CT500MX500SSD1 500GB                      | 5         | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB                      | 4         | 0.27%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 4         | 0.27%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 4         | 0.27%   |
| TO Exter nal USB 3.0 250GB                        | 4         | 0.27%   |
| Seagate ST9500420AS 500GB                         | 4         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 151       | 238    | 31.72%  |
| Seagate             | 145       | 200    | 30.46%  |
| Hitachi             | 50        | 85     | 10.5%   |
| Toshiba             | 48        | 62     | 10.08%  |
| Samsung Electronics | 18        | 22     | 3.78%   |
| HGST                | 18        | 27     | 3.78%   |
| Unknown             | 11        | 13     | 2.31%   |
| Fujitsu             | 6         | 6      | 1.26%   |
| TO Exter            | 4         | 5      | 0.84%   |
| ASMT                | 4         | 7      | 0.84%   |
| USB3.0              | 3         | 5      | 0.63%   |
| SSK                 | 3         | 4      | 0.63%   |
| Maxtor              | 2         | 2      | 0.42%   |
| Hewlett-Packard     | 2         | 2      | 0.42%   |
| ASMedia             | 2         | 2      | 0.42%   |
| Apple               | 2         | 2      | 0.42%   |
| MaxDigital          | 1         | 1      | 0.21%   |
| MARVELL             | 1         | 1      | 0.21%   |
| LaCie               | 1         | 1      | 0.21%   |
| JMicron Technology  | 1         | 1      | 0.21%   |
| ICY BOX             | 1         | 1      | 0.21%   |
| IBM-ESXS            | 1         | 9      | 0.21%   |
| HGST HTS            | 1         | 2      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 101       | 127    | 22.05%  |
| Kingston            | 77        | 93     | 16.81%  |
| Crucial             | 38        | 45     | 8.3%    |
| SanDisk             | 37        | 45     | 8.08%   |
| WDC                 | 22        | 24     | 4.8%    |
| China               | 19        | 23     | 4.15%   |
| PNY                 | 16        | 22     | 3.49%   |
| A-DATA Technology   | 16        | 23     | 3.49%   |
| SPCC                | 13        | 15     | 2.84%   |
| Intel               | 11        | 13     | 2.4%    |
| Micron Technology   | 10        | 11     | 2.18%   |
| Intenso             | 10        | 10     | 2.18%   |
| Transcend           | 6         | 9      | 1.31%   |
| Patriot             | 6         | 6      | 1.31%   |
| Toshiba             | 5         | 5      | 1.09%   |
| SK hynix            | 5         | 5      | 1.09%   |
| PHD 3.0             | 4         | 5      | 0.87%   |
| LITEON              | 4         | 4      | 0.87%   |
| KingDian            | 3         | 3      | 0.66%   |
| Apple               | 3         | 3      | 0.66%   |
| Apacer              | 3         | 3      | 0.66%   |
| TEXTORM             | 2         | 2      | 0.44%   |
| Team                | 2         | 5      | 0.44%   |
| OCZ                 | 2         | 2      | 0.44%   |
| Netac               | 2         | 2      | 0.44%   |
| LITEONIT            | 2         | 2      | 0.44%   |
| Lexar               | 2         | 2      | 0.44%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.44%   |
| Hewlett-Packard     | 2         | 3      | 0.44%   |
| GOODRAM             | 2         | 2      | 0.44%   |
| Gigabyte Technology | 2         | 2      | 0.44%   |
| FORESEE             | 2         | 5      | 0.44%   |
| Corsair             | 2         | 2      | 0.44%   |
| BHT                 | 2         | 2      | 0.44%   |
| Wodposit            | 1         | 1      | 0.22%   |
| Verbatim            | 1         | 1      | 0.22%   |
| Veno                | 1         | 1      | 0.22%   |
| Vaseky              | 1         | 1      | 0.22%   |
| Timetec             | 1         | 1      | 0.22%   |
| SSSTC               | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 412       | 553    | 34.08%  |
| HDD     | 397       | 698    | 32.84%  |
| NVMe    | 278       | 384    | 22.99%  |
| MMC     | 103       | 135    | 8.52%   |
| Unknown | 19        | 22     | 1.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 664       | 1176   | 59.93%  |
| NVMe | 277       | 382    | 25%     |
| MMC  | 103       | 135    | 9.3%    |
| SAS  | 64        | 99     | 5.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 521       | 748    | 60.79%  |
| 0.51-1.0   | 211       | 310    | 24.62%  |
| 1.01-2.0   | 67        | 90     | 7.82%   |
| 3.01-4.0   | 36        | 71     | 4.2%    |
| 2.01-3.0   | 8         | 11     | 0.93%   |
| 4.01-10.0  | 8         | 12     | 0.93%   |
| 10.01-20.0 | 6         | 9      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 260       | 26.83%  |
| 251-500        | 243       | 25.08%  |
| 501-1000       | 137       | 14.14%  |
| 1001-2000      | 86        | 8.88%   |
| 51-100         | 69        | 7.12%   |
| 1-20           | 59        | 6.09%   |
| More than 3000 | 47        | 4.85%   |
| 21-50          | 41        | 4.23%   |
| 2001-3000      | 25        | 2.58%   |
| Unknown        | 2         | 0.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 306       | 30.45%  |
| 21-50          | 188       | 18.71%  |
| 101-250        | 152       | 15.12%  |
| 51-100         | 120       | 11.94%  |
| 251-500        | 107       | 10.65%  |
| 501-1000       | 60        | 5.97%   |
| 1001-2000      | 39        | 3.88%   |
| 2001-3000      | 16        | 1.59%   |
| More than 3000 | 15        | 1.49%   |
| Unknown        | 2         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 2.27%   |
| Toshiba DT01ACA100 1TB                | 2         | 2      | 1.52%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 1.52%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 1.52%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 1.52%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 1.52%   |
| Seagate ST320LT007-9ZV142 320GB       | 2         | 2      | 1.52%   |
| Seagate ST1000DM003-1ER162 1TB        | 2         | 2      | 1.52%   |
| HGST HUS724040ALA640 4TB              | 2         | 8      | 1.52%   |
| Wodposit SSD 128GB                    | 1         | 1      | 0.76%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 0.76%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 0.76%   |
| WDC WD5000LPVT-08G33T1 500GB          | 1         | 1      | 0.76%   |
| WDC WD5000LPLX-75ZNTT1 500GB          | 1         | 1      | 0.76%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 0.76%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 0.76%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1         | 1      | 0.76%   |
| WDC WD3200AVJS-63N9A0 320GB           | 1         | 1      | 0.76%   |
| WDC WD3200AAKS-75B3A0 320GB           | 1         | 2      | 0.76%   |
| WDC WD3200AAKS-00L9A0 320GB           | 1         | 1      | 0.76%   |
| WDC WD2500AAKS-00VSA0 250GB           | 1         | 1      | 0.76%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1         | 1      | 0.76%   |
| WDC WD20EARS-00MVWB0 2TB              | 1         | 1      | 0.76%   |
| WDC WD2003FYYS-05T9B0 2TB             | 1         | 1      | 0.76%   |
| WDC WD2002FYPS-02W3B0 2TB             | 1         | 1      | 0.76%   |
| WDC WD1200BEVS-60UST0 120GB           | 1         | 1      | 0.76%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 0.76%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1         | 1      | 0.76%   |
| WDC WD10EAVS-00D7B1 1TB               | 1         | 1      | 0.76%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 0.76%   |
| WDC WD10EARS-003BB1 1TB               | 1         | 1      | 0.76%   |
| WDC WD1003FBYX-01Y7B1 1TB             | 1         | 1      | 0.76%   |
| WDC WD1001FALS-40Y6A0 1TB             | 1         | 2      | 0.76%   |
| Toshiba MK5065GSXN 500GB              | 1         | 1      | 0.76%   |
| Toshiba MK1633GSG 160GB               | 1         | 2      | 0.76%   |
| Toshiba MK1246GSX 120GB               | 1         | 1      | 0.76%   |
| SSSTC CVB-8D128-HP 128GB              | 1         | 1      | 0.76%   |
| SK hynix HFS256G32TNH-73A0A 256GB SSD | 1         | 1      | 0.76%   |
| Seagate ST9500423AS 500GB             | 1         | 1      | 0.76%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 0.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 35     | 24.62%  |
| WDC                 | 22        | 25     | 16.92%  |
| Hitachi             | 17        | 20     | 13.08%  |
| Samsung Electronics | 10        | 12     | 7.69%   |
| Kingston            | 7         | 8      | 5.38%   |
| Toshiba             | 5         | 6      | 3.85%   |
| SanDisk             | 4         | 4      | 3.08%   |
| HGST                | 4         | 10     | 3.08%   |
| Fujitsu             | 4         | 4      | 3.08%   |
| Micron Technology   | 3         | 3      | 2.31%   |
| Intel               | 3         | 3      | 2.31%   |
| LITEON              | 2         | 2      | 1.54%   |
| Apple               | 2         | 2      | 1.54%   |
| A-DATA Technology   | 2         | 2      | 1.54%   |
| Wodposit            | 1         | 1      | 0.77%   |
| SSSTC               | 1         | 1      | 0.77%   |
| SK hynix            | 1         | 1      | 0.77%   |
| PNY                 | 1         | 1      | 0.77%   |
| Maxtor              | 1         | 1      | 0.77%   |
| JMicron Technology  | 1         | 1      | 0.77%   |
| Intenso             | 1         | 1      | 0.77%   |
| ICY BOX             | 1         | 1      | 0.77%   |
| Hewlett-Packard     | 1         | 1      | 0.77%   |
| Crucial             | 1         | 1      | 0.77%   |
| China               | 1         | 1      | 0.77%   |
| ASMT                | 1         | 4      | 0.77%   |
| Unknown             | 1         | 1      | 0.77%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 35     | 34.41%  |
| WDC                 | 20        | 23     | 21.51%  |
| Hitachi             | 17        | 20     | 18.28%  |
| Samsung Electronics | 6         | 8      | 6.45%   |
| Toshiba             | 5         | 6      | 5.38%   |
| HGST                | 4         | 10     | 4.3%    |
| Fujitsu             | 4         | 4      | 4.3%    |
| Maxtor              | 1         | 1      | 1.08%   |
| JMicron Technology  | 1         | 1      | 1.08%   |
| ICY BOX             | 1         | 1      | 1.08%   |
| Hewlett-Packard     | 1         | 1      | 1.08%   |
| ASMT                | 1         | 4      | 1.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 87        | 114    | 70.73%  |
| SSD  | 34        | 36     | 27.64%  |
| NVMe | 2         | 2      | 1.63%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 3      | 50%     |
| JMicron Technology Tech 250GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 1         | 3      | 50%     |
| JMicron Technology | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 524       | 883    | 49.86%  |
| Detected | 403       | 753    | 38.34%  |
| Malfunc  | 122       | 152    | 11.61%  |
| Failed   | 2         | 4      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 601       | 53.52%  |
| AMD                                     | 172       | 15.32%  |
| Samsung Electronics                     | 89        | 7.93%   |
| Sandisk                                 | 42        | 3.74%   |
| SK hynix                                | 31        | 2.76%   |
| Kingston Technology Company             | 25        | 2.23%   |
| Phison Electronics                      | 21        | 1.87%   |
| Nvidia                                  | 16        | 1.42%   |
| JMicron Technology                      | 16        | 1.42%   |
| Micron Technology                       | 13        | 1.16%   |
| Marvell Technology Group                | 11        | 0.98%   |
| ASMedia Technology                      | 11        | 0.98%   |
| KIOXIA                                  | 9         | 0.8%    |
| Silicon Motion                          | 8         | 0.71%   |
| Realtek Semiconductor                   | 7         | 0.62%   |
| Micron/Crucial Technology               | 7         | 0.62%   |
| MAXIO Technology (Hangzhou)             | 5         | 0.45%   |
| Broadcom / LSI                          | 5         | 0.45%   |
| Toshiba America Info Systems            | 4         | 0.36%   |
| Silicon Image                           | 4         | 0.36%   |
| VIA Technologies                        | 3         | 0.27%   |
| LSI Logic / Symbios Logic               | 3         | 0.27%   |
| Apple                                   | 3         | 0.27%   |
| Transcend                               | 2         | 0.18%   |
| Shenzhen Longsys Electronics            | 2         | 0.18%   |
| Lenovo                                  | 2         | 0.18%   |
| ADATA Technology                        | 2         | 0.18%   |
| Adaptec                                 | 2         | 0.18%   |
| Union Memory (Shenzhen)                 | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.09%   |
| Shenzhen Unionmemory Information System | 1         | 0.09%   |
| Netac Technology                        | 1         | 0.09%   |
| INNOGRIT                                | 1         | 0.09%   |
| Hosin Global Electronics                | 1         | 0.09%   |
| Biwin Storage Technology                | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 117       | 9.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 53        | 4.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 40        | 3.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 35        | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 33        | 2.55%   |
| Intel Volume Management Device NVMe RAID Controller                              | 33        | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 26        | 2.01%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 22        | 1.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 20        | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 20        | 1.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 19        | 1.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 18        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 18        | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                           | 18        | 1.39%   |
| AMD 400 Series Chipset SATA Controller                                           | 18        | 1.39%   |
| Intel SATA Controller [RAID mode]                                                | 17        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 16        | 1.23%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 15        | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 15        | 1.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 15        | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 15        | 1.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 15        | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 15        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 15        | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 14        | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 14        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 14        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 14        | 1.08%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 13        | 1%      |
| Intel Tiger Lake-LP SATA Controller                                              | 13        | 1%      |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 13        | 1%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 13        | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 12        | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 12        | 0.93%   |
| JMicron JMB363 SATA/IDE Controller                                               | 11        | 0.85%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 11        | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 11        | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 11        | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 10        | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 678       | 58.85%  |
| NVMe | 277       | 24.05%  |
| IDE  | 108       | 9.38%   |
| RAID | 81        | 7.03%   |
| SAS  | 6         | 0.52%   |
| SCSI | 2         | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 691       | 73.12%  |
| AMD    | 225       | 23.81%  |
| ARM    | 29        | 3.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ARM Processor                           | 24        | 2.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 13        | 1.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 10        | 1.06%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 10        | 1.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 10        | 1.06%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 9         | 0.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 8         | 0.85%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 8         | 0.85%   |
| AMD Ryzen 5 3600 6-Core Processor       | 8         | 0.85%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 7         | 0.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 6         | 0.63%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 6         | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 0.63%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 6         | 0.63%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 6         | 0.63%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 6         | 0.63%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 6         | 0.63%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 5         | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 5         | 0.53%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 5         | 0.53%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 5         | 0.53%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 0.53%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 5         | 0.53%   |
| Intel Core i3-4150 CPU @ 3.50GHz        | 5         | 0.53%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 5         | 0.53%   |
| Intel 12th Gen Core i7-1260P            | 5         | 0.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 5         | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 0.42%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 4         | 0.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 4         | 0.42%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 0.42%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 4         | 0.42%   |
| Intel Core i3 CPU M 330 @ 2.13GHz       | 4         | 0.42%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 4         | 0.42%   |
| Intel Celeron N4120 CPU @ 1.10GHz       | 4         | 0.42%   |
| Intel Celeron CPU N3450 @ 1.10GHz       | 4         | 0.42%   |
| Intel Celeron CPU N3160 @ 1.60GHz       | 4         | 0.42%   |
| Intel Celeron CPU 847 @ 1.10GHz         | 4         | 0.42%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 4         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 175       | 18.5%   |
| Intel Core i7           | 111       | 11.73%  |
| Other                   | 110       | 11.63%  |
| Intel Celeron           | 93        | 9.83%   |
| Intel Core i3           | 74        | 7.82%   |
| AMD Ryzen 5             | 52        | 5.5%    |
| Intel Core 2 Duo        | 43        | 4.55%   |
| AMD Ryzen 7             | 41        | 4.33%   |
| Intel Xeon              | 30        | 3.17%   |
| Intel Pentium           | 19        | 2.01%   |
| Intel Atom              | 18        | 1.9%    |
| AMD Ryzen 9             | 14        | 1.48%   |
| AMD A4                  | 11        | 1.16%   |
| AMD A8                  | 10        | 1.06%   |
| Intel Pentium Dual-Core | 9         | 0.95%   |
| AMD Ryzen 3             | 9         | 0.95%   |
| AMD FX                  | 9         | 0.95%   |
| AMD A6                  | 9         | 0.95%   |
| Intel Core 2            | 8         | 0.85%   |
| Intel Core 2 Quad       | 7         | 0.74%   |
| AMD Ryzen 5 PRO         | 7         | 0.74%   |
| AMD Athlon II X2        | 7         | 0.74%   |
| AMD Ryzen 7 PRO         | 6         | 0.63%   |
| Intel Pentium Dual      | 5         | 0.53%   |
| AMD E1                  | 5         | 0.53%   |
| ARM Allwinner           | 4         | 0.42%   |
| AMD Phenom II X4        | 4         | 0.42%   |
| AMD GX                  | 4         | 0.42%   |
| AMD Athlon              | 4         | 0.42%   |
| AMD A10                 | 4         | 0.42%   |
| Intel Genuine           | 3         | 0.32%   |
| AMD Ryzen Threadripper  | 3         | 0.32%   |
| AMD E2                  | 3         | 0.32%   |
| AMD Athlon II           | 3         | 0.32%   |
| AMD Athlon 64 X2        | 3         | 0.32%   |
| Intel Pentium Silver    | 2         | 0.21%   |
| Intel Pentium 4         | 2         | 0.21%   |
| Intel Core i9           | 2         | 0.21%   |
| AMD V120                | 2         | 0.21%   |
| AMD Phenom II X6        | 2         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 394       | 41.61%  |
| 4       | 312       | 32.95%  |
| 6       | 83        | 8.76%   |
| 8       | 65        | 6.86%   |
| 1       | 18        | 1.9%    |
| 10      | 17        | 1.8%    |
| Unknown | 15        | 1.58%   |
| 16      | 13        | 1.37%   |
| 12      | 13        | 1.37%   |
| 14      | 6         | 0.63%   |
| 3       | 4         | 0.42%   |
| 64      | 2         | 0.21%   |
| 24      | 2         | 0.21%   |
| 18      | 2         | 0.21%   |
| 20      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 919       | 97.25%  |
| Unknown | 15        | 1.59%   |
| 2       | 11        | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 557       | 58.94%  |
| 1       | 373       | 39.47%  |
| Unknown | 15        | 1.59%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 936       | 99.05%  |
| Unknown        | 6         | 0.63%   |
| 64-bit         | 3         | 0.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 488       | 50.47%  |
| 0x806c1    | 21        | 2.17%   |
| 0x306c3    | 21        | 2.17%   |
| 0x306a9    | 19        | 1.96%   |
| 0x206a7    | 17        | 1.76%   |
| 0x1067a    | 14        | 1.45%   |
| 0x506e3    | 12        | 1.24%   |
| 0x406e3    | 12        | 1.24%   |
| 0x506c9    | 11        | 1.14%   |
| 0x08608103 | 11        | 1.14%   |
| 0x08108109 | 11        | 1.14%   |
| 0x906ea    | 10        | 1.03%   |
| 0x406c4    | 10        | 1.03%   |
| 0x406c3    | 10        | 1.03%   |
| 0x20655    | 10        | 1.03%   |
| 0x010000c8 | 10        | 1.03%   |
| 0x806ec    | 9         | 0.93%   |
| 0x806e9    | 9         | 0.93%   |
| 0x706a8    | 8         | 0.83%   |
| 0x306d4    | 8         | 0.83%   |
| 0x07030105 | 8         | 0.83%   |
| 0x806ea    | 7         | 0.72%   |
| 0x40651    | 7         | 0.72%   |
| 0x30678    | 7         | 0.72%   |
| 0xa0652    | 6         | 0.62%   |
| 0x906e9    | 6         | 0.62%   |
| 0x20652    | 6         | 0.62%   |
| 0x106e5    | 6         | 0.62%   |
| 0x0a50000c | 6         | 0.62%   |
| 0x08701021 | 6         | 0.62%   |
| 0x0800820d | 6         | 0.62%   |
| 0x06006705 | 6         | 0.62%   |
| 0x06000852 | 6         | 0.62%   |
| 0x906a3    | 5         | 0.52%   |
| 0x706a1    | 5         | 0.52%   |
| 0x6fd      | 5         | 0.52%   |
| 0x6f6      | 5         | 0.52%   |
| 0x10676    | 5         | 0.52%   |
| 0x0700010f | 5         | 0.52%   |
| 0x05000119 | 5         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 96        | 10.11%  |
| Haswell          | 89        | 9.37%   |
| Unknown          | 86        | 9.05%   |
| SandyBridge      | 61        | 6.42%   |
| Penryn           | 52        | 5.47%   |
| IvyBridge        | 50        | 5.26%   |
| Silvermont       | 49        | 5.16%   |
| Skylake          | 48        | 5.05%   |
| Zen 2            | 36        | 3.79%   |
| Westmere         | 32        | 3.37%   |
| TigerLake        | 31        | 3.26%   |
| Zen 3            | 30        | 3.16%   |
| Core             | 29        | 3.05%   |
| Alderlake Hybrid | 28        | 2.95%   |
| Zen+             | 26        | 2.74%   |
| Broadwell        | 22        | 2.32%   |
| K10              | 21        | 2.21%   |
| Goldmont plus    | 21        | 2.21%   |
| CometLake        | 18        | 1.89%   |
| Goldmont         | 16        | 1.68%   |
| Piledriver       | 15        | 1.58%   |
| Excavator        | 14        | 1.47%   |
| Puma             | 12        | 1.26%   |
| IceLake          | 12        | 1.26%   |
| Nehalem          | 11        | 1.16%   |
| Zen              | 9         | 0.95%   |
| Bobcat           | 7         | 0.74%   |
| K10 Llano        | 6         | 0.63%   |
| Jaguar           | 6         | 0.63%   |
| Bonnell          | 6         | 0.63%   |
| Steamroller      | 4         | 0.42%   |
| NetBurst         | 3         | 0.32%   |
| K8 Hammer        | 3         | 0.32%   |
| Tremont          | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 547       | 52.29%  |
| Nvidia                           | 251       | 24%     |
| AMD                              | 236       | 22.56%  |
| Matrox Electronics Systems       | 6         | 0.57%   |
| ASPEED Technology                | 5         | 0.48%   |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 47        | 4.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 33        | 3.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 27        | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 25        | 2.31%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 2.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 1.85%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 19        | 1.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 1.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 19        | 1.76%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 18        | 1.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 1.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 1.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 1.48%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 15        | 1.39%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 15        | 1.39%   |
| AMD Lucienne                                                                             | 15        | 1.39%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 1.39%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 14        | 1.29%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 14        | 1.29%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 13        | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 1.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 1.02%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 1.02%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 10        | 0.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 0.83%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8         | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 0.74%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 8         | 0.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 0.65%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 7         | 0.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 0.65%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 6         | 0.55%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 0.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 6         | 0.55%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 440       | 46.46%  |
| 1 x AMD            | 186       | 19.64%  |
| 1 x Nvidia         | 148       | 15.63%  |
| Intel + Nvidia     | 73        | 7.71%   |
| Other              | 33        | 3.48%   |
| AMD + Nvidia       | 22        | 2.32%   |
| Intel + AMD        | 16        | 1.69%   |
| 2 x AMD            | 13        | 1.37%   |
| 1 x Matrox         | 4         | 0.42%   |
| Nvidia + ASPEED    | 3         | 0.32%   |
| 2 x Nvidia         | 2         | 0.21%   |
| Intel + 2 x Nvidia | 2         | 0.21%   |
| 1 x ASPEED         | 2         | 0.21%   |
| 1 x SiS            | 1         | 0.11%   |
| Nvidia + Matrox    | 1         | 0.11%   |
| AMD + Matrox       | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 763       | 79.81%  |
| Proprietary | 128       | 13.39%  |
| Unknown     | 65        | 6.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 647       | 67.61%  |
| 0.01-0.5   | 104       | 10.87%  |
| 1.01-2.0   | 62        | 6.48%   |
| 0.51-1.0   | 62        | 6.48%   |
| 3.01-4.0   | 35        | 3.66%   |
| 5.01-6.0   | 16        | 1.67%   |
| 7.01-8.0   | 14        | 1.46%   |
| 8.01-16.0  | 12        | 1.25%   |
| 2.01-3.0   | 3         | 0.31%   |
| 32.01-64.0 | 1         | 0.1%    |
| 4.01-5.0   | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 124       | 12.36%  |
| Samsung Electronics     | 103       | 10.27%  |
| LG Display              | 90        | 8.97%   |
| BOE                     | 88        | 8.77%   |
| Dell                    | 80        | 7.98%   |
| Chimei Innolux          | 66        | 6.58%   |
| Hewlett-Packard         | 49        | 4.89%   |
| Goldstar                | 41        | 4.09%   |
| Acer                    | 30        | 2.99%   |
| AOC                     | 28        | 2.79%   |
| Apple                   | 22        | 2.19%   |
| Lenovo                  | 21        | 2.09%   |
| Philips                 | 19        | 1.89%   |
| BenQ                    | 17        | 1.69%   |
| Ancor Communications    | 17        | 1.69%   |
| ViewSonic               | 15        | 1.5%    |
| Iiyama                  | 15        | 1.5%    |
| InfoVision              | 11        | 1.1%    |
| Chi Mei Optoelectronics | 11        | 1.1%    |
| PANDA                   | 10        | 1%      |
| Sharp                   | 9         | 0.9%    |
| Fujitsu Siemens         | 8         | 0.8%    |
| ASUSTek Computer        | 7         | 0.7%    |
| RTK                     | 6         | 0.6%    |
| Sony                    | 5         | 0.5%    |
| Sceptre Tech            | 5         | 0.5%    |
| LG Philips              | 5         | 0.5%    |
| NEC Computers           | 4         | 0.4%    |
| Eizo                    | 4         | 0.4%    |
| Denver                  | 4         | 0.4%    |
| Unknown                 | 3         | 0.3%    |
| Toshiba                 | 3         | 0.3%    |
| Mi                      | 3         | 0.3%    |
| KDC                     | 3         | 0.3%    |
| IBM                     | 3         | 0.3%    |
| HannStar                | 3         | 0.3%    |
| Vizio                   | 2         | 0.2%    |
| SNC                     | 2         | 0.2%    |
| Medion                  | 2         | 0.2%    |
| LG Electronics          | 2         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.48%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.39%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 4         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 4         | 0.39%   |
| Sony Nvidia Defaul t Flat Panel SNY05FA 1366x768 309x174mm 14.0-inch     | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 3         | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.29%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 3         | 0.29%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.29%   |
| Lenovo LEN-M82-C LEN00A2 1920x1080 476x268mm 21.5-inch                   | 3         | 0.29%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 3         | 0.29%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 3         | 0.29%   |
| Denver MO-HHS-32C LHCFFFF 1920x1080 699x393mm 31.6-inch                  | 3         | 0.29%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                         | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 3         | 0.29%   |
| BOE LCD Monitor BOE08C2 1920x1080 344x194mm 15.5-inch                    | 3         | 0.29%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 3         | 0.29%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 3         | 0.29%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 3         | 0.29%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                       | 3         | 0.29%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 3         | 0.29%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.29%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.29%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 2         | 0.19%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch     | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch    | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 890x500mm 40.2-inch    | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                        | 2         | 0.19%   |
| RTK LCD Monitor RTK2136 1600x900 434x236mm 19.4-inch                     | 2         | 0.19%   |
| RTK ALOLG RTK3B3A 1920x1080 300x260mm 15.6-inch                          | 2         | 0.19%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                  | 2         | 0.19%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                   | 2         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 410       | 42.18%  |
| 1366x768 (WXGA)    | 185       | 19.03%  |
| 1600x900 (HD+)     | 56        | 5.76%   |
| 3840x2160 (4K)     | 45        | 4.63%   |
| 2560x1440 (QHD)    | 44        | 4.53%   |
| 1280x1024 (SXGA)   | 32        | 3.29%   |
| 1920x1200 (WUXGA)  | 31        | 3.19%   |
| 1280x800 (WXGA)    | 30        | 3.09%   |
| 1440x900 (WXGA+)   | 28        | 2.88%   |
| 1680x1050 (WSXGA+) | 27        | 2.78%   |
| 2560x1600          | 10        | 1.03%   |
| 1024x768 (XGA)     | 10        | 1.03%   |
| 3440x1440          | 6         | 0.62%   |
| 2560x1080          | 6         | 0.62%   |
| 1600x1200          | 6         | 0.62%   |
| 1360x768           | 6         | 0.62%   |
| 3840x1080          | 4         | 0.41%   |
| 1024x600           | 4         | 0.41%   |
| 3840x1600          | 3         | 0.31%   |
| 2160x1440          | 3         | 0.31%   |
| Unknown            | 3         | 0.31%   |
| 2880x1800          | 2         | 0.21%   |
| 2256x1504          | 2         | 0.21%   |
| 1920x540           | 2         | 0.21%   |
| 1280x720 (HD)      | 2         | 0.21%   |
| 7680x1080          | 1         | 0.1%    |
| 3840x2400          | 1         | 0.1%    |
| 3456x2160          | 1         | 0.1%    |
| 3200x1800 (QHD+)   | 1         | 0.1%    |
| 2880x1920          | 1         | 0.1%    |
| 2880x1620          | 1         | 0.1%    |
| 2304x1440          | 1         | 0.1%    |
| 2288x1287          | 1         | 0.1%    |
| 2240x1400          | 1         | 0.1%    |
| 2048x1152          | 1         | 0.1%    |
| 1920x515           | 1         | 0.1%    |
| 1920x1280          | 1         | 0.1%    |
| 1400x1050          | 1         | 0.1%    |
| 1366x912           | 1         | 0.1%    |
| 1280x960           | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 243       | 23.92%  |
| 24      | 88        | 8.66%   |
| 14      | 81        | 7.97%   |
| 13      | 80        | 7.87%   |
| 27      | 69        | 6.79%   |
| 23      | 66        | 6.5%    |
| 17      | 59        | 5.81%   |
| 21      | 53        | 5.22%   |
| 19      | 40        | 3.94%   |
| 18      | 27        | 2.66%   |
| Unknown | 24        | 2.36%   |
| 20      | 22        | 2.17%   |
| 12      | 22        | 2.17%   |
| 31      | 19        | 1.87%   |
| 11      | 18        | 1.77%   |
| 22      | 16        | 1.57%   |
| 16      | 15        | 1.48%   |
| 34      | 9         | 0.89%   |
| 25      | 7         | 0.69%   |
| 63      | 6         | 0.59%   |
| 32      | 6         | 0.59%   |
| 40      | 5         | 0.49%   |
| 26      | 5         | 0.49%   |
| 10      | 5         | 0.49%   |
| 84      | 4         | 0.39%   |
| 49      | 4         | 0.39%   |
| 37      | 4         | 0.39%   |
| 29      | 4         | 0.39%   |
| 54      | 3         | 0.3%    |
| 72      | 2         | 0.2%    |
| 42      | 2         | 0.2%    |
| 28      | 2         | 0.2%    |
| 142     | 1         | 0.1%    |
| 86      | 1         | 0.1%    |
| 48      | 1         | 0.1%    |
| 43      | 1         | 0.1%    |
| 30      | 1         | 0.1%    |
| 6       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 383       | 38.3%   |
| 501-600        | 215       | 21.5%   |
| 401-500        | 143       | 14.3%   |
| 201-300        | 89        | 8.9%    |
| 351-400        | 64        | 6.4%    |
| 601-700        | 32        | 3.2%    |
| Unknown        | 24        | 2.4%    |
| 701-800        | 15        | 1.5%    |
| 1001-1500      | 15        | 1.5%    |
| 801-900        | 9         | 0.9%    |
| 1501-2000      | 6         | 0.6%    |
| 901-1000       | 3         | 0.3%    |
| More than 2000 | 1         | 0.1%    |
| 101-200        | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 703       | 76%     |
| 16/10   | 128       | 13.84%  |
| 5/4     | 30        | 3.24%   |
| 4/3     | 18        | 1.95%   |
| Unknown | 15        | 1.62%   |
| 21/9    | 12        | 1.3%    |
| 3/2     | 9         | 0.97%   |
| 32/9    | 5         | 0.54%   |
| 6/5     | 2         | 0.22%   |
| 3.73    | 1         | 0.11%   |
| 1.00    | 1         | 0.11%   |
| 0.56    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 242       | 23.98%  |
| 201-250        | 181       | 17.94%  |
| 81-90          | 126       | 12.49%  |
| 151-200        | 83        | 8.23%   |
| 301-350        | 72        | 7.14%   |
| 141-150        | 41        | 4.06%   |
| 351-500        | 39        | 3.87%   |
| 121-130        | 35        | 3.47%   |
| 71-80          | 33        | 3.27%   |
| 251-300        | 29        | 2.87%   |
| Unknown        | 24        | 2.38%   |
| 61-70          | 21        | 2.08%   |
| More than 1000 | 18        | 1.78%   |
| 51-60          | 18        | 1.78%   |
| 501-1000       | 15        | 1.49%   |
| 111-120        | 11        | 1.09%   |
| 131-140        | 10        | 0.99%   |
| 41-50          | 5         | 0.5%    |
| 91-100         | 5         | 0.5%    |
| 1-40           | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 344       | 35.46%  |
| 101-120       | 278       | 28.66%  |
| 121-160       | 251       | 25.88%  |
| 161-240       | 48        | 4.95%   |
| Unknown       | 24        | 2.47%   |
| 1-50          | 15        | 1.55%   |
| More than 240 | 10        | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 762       | 79.54%  |
| 2     | 136       | 14.2%   |
| 0     | 39        | 4.07%   |
| 3     | 21        | 2.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 519       | 37.2%   |
| Intel                             | 437       | 31.33%  |
| Qualcomm Atheros                  | 127       | 9.1%    |
| Broadcom                          | 77        | 5.52%   |
| MediaTek                          | 26        | 1.86%   |
| Broadcom Limited                  | 20        | 1.43%   |
| Ralink Technology                 | 18        | 1.29%   |
| Marvell Technology Group          | 17        | 1.22%   |
| TP-Link                           | 14        | 1%      |
| Nvidia                            | 14        | 1%      |
| Ralink                            | 10        | 0.72%   |
| ASIX Electronics                  | 10        | 0.72%   |
| Samsung Electronics               | 9         | 0.65%   |
| Qualcomm                          | 7         | 0.5%    |
| Sierra Wireless                   | 6         | 0.43%   |
| Dell                              | 6         | 0.43%   |
| Xiaomi                            | 4         | 0.29%   |
| Qualcomm Atheros Communications   | 4         | 0.29%   |
| NetGear                           | 4         | 0.29%   |
| Microchip Technology              | 4         | 0.29%   |
| Huawei Technologies               | 4         | 0.29%   |
| Hewlett-Packard                   | 4         | 0.29%   |
| D-Link System                     | 4         | 0.29%   |
| Ericsson Business Mobile Networks | 3         | 0.22%   |
| D-Link                            | 3         | 0.22%   |
| Belkin Components                 | 3         | 0.22%   |
| Aquantia                          | 3         | 0.22%   |
| Shenzhen Goodix Technology        | 2         | 0.14%   |
| OPPO Electronics                  | 2         | 0.14%   |
| Microsoft                         | 2         | 0.14%   |
| JMicron Technology                | 2         | 0.14%   |
| Insyde Software                   | 2         | 0.14%   |
| DisplayLink                       | 2         | 0.14%   |
| ZyDAS                             | 1         | 0.07%   |
| Zoom Telephonics                  | 1         | 0.07%   |
| Wilocity                          | 1         | 0.07%   |
| TRENDnet                          | 1         | 0.07%   |
| STMicroelectronics                | 1         | 0.07%   |
| Spreadtrum Communications         | 1         | 0.07%   |
| SEGGER                            | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 327       | 19.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 57        | 3.44%   |
| Intel Wi-Fi 6 AX200                                                    | 34        | 2.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 33        | 1.99%   |
| Realtek RTL8125 2.5GbE Controller                                      | 32        | 1.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 29        | 1.75%   |
| Intel Wireless 8260                                                    | 25        | 1.51%   |
| Intel Wireless 7260                                                    | 25        | 1.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 24        | 1.45%   |
| Intel Wireless 7265                                                    | 24        | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 21        | 1.27%   |
| Intel Wi-Fi 6 AX201                                                    | 20        | 1.21%   |
| Intel Ethernet Connection I217-LM                                      | 20        | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 19        | 1.15%   |
| Realtek 802.11ac NIC                                                   | 16        | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 16        | 0.97%   |
| Intel Wireless 8265 / 8275                                             | 16        | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 15        | 0.91%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 15        | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 14        | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 13        | 0.79%   |
| Intel Wireless 3165                                                    | 13        | 0.79%   |
| Intel I211 Gigabit Network Connection                                  | 13        | 0.79%   |
| Intel Ethernet Connection (2) I219-V                                   | 13        | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 13        | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 12        | 0.73%   |
| Intel Ethernet Controller I225-V                                       | 12        | 0.73%   |
| Intel Ethernet Connection I217-V                                       | 12        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 12        | 0.73%   |
| Ralink MT7601U Wireless Adapter                                        | 11        | 0.66%   |
| Intel Ethernet Connection I219-LM                                      | 11        | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 11        | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                          | 11        | 0.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 10        | 0.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 9         | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 9         | 0.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 9         | 0.54%   |
| Intel Centrino Advanced-N 6200                                         | 9         | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 8         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 322       | 42.99%  |
| Realtek Semiconductor           | 158       | 21.09%  |
| Qualcomm Atheros                | 108       | 14.42%  |
| Broadcom                        | 47        | 6.28%   |
| MediaTek                        | 25        | 3.34%   |
| Ralink Technology               | 18        | 2.4%    |
| TP-Link                         | 13        | 1.74%   |
| Ralink                          | 10        | 1.34%   |
| Broadcom Limited                | 9         | 1.2%    |
| Sierra Wireless                 | 6         | 0.8%    |
| Qualcomm                        | 6         | 0.8%    |
| Qualcomm Atheros Communications | 4         | 0.53%   |
| NetGear                         | 4         | 0.53%   |
| Dell                            | 3         | 0.4%    |
| D-Link                          | 3         | 0.4%    |
| Belkin Components               | 3         | 0.4%    |
| D-Link System                   | 2         | 0.27%   |
| ZyDAS                           | 1         | 0.13%   |
| Wilocity                        | 1         | 0.13%   |
| TRENDnet                        | 1         | 0.13%   |
| Microsoft                       | 1         | 0.13%   |
| Marvell Technology Group        | 1         | 0.13%   |
| Fibocom                         | 1         | 0.13%   |
| BUFFALO                         | 1         | 0.13%   |
| ASUSTek Computer                | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 34        | 4.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 29        | 3.81%   |
| Intel Wireless 8260                                                  | 25        | 3.28%   |
| Intel Wireless 7260                                                  | 25        | 3.28%   |
| Intel Wireless 7265                                                  | 24        | 3.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 21        | 2.76%   |
| Intel Wi-Fi 6 AX201                                                  | 20        | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 19        | 2.49%   |
| Realtek 802.11ac NIC                                                 | 16        | 2.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 16        | 2.1%    |
| Intel Wireless 8265 / 8275                                           | 16        | 2.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 15        | 1.97%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 15        | 1.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 14        | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 13        | 1.71%   |
| Intel Wireless 3165                                                  | 13        | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 12        | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 12        | 1.57%   |
| Ralink MT7601U Wireless Adapter                                      | 11        | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 11        | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                        | 11        | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 10        | 1.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 9         | 1.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 9         | 1.18%   |
| Intel Centrino Advanced-N 6200                                       | 9         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 9         | 1.18%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 8         | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 8         | 1.05%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 8         | 1.05%   |
| Intel Wireless 3160                                                  | 8         | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 8         | 1.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 8         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 8         | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 7         | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 7         | 0.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 7         | 0.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 7         | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 7         | 0.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 7         | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 6         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 447       | 52.28%  |
| Intel                     | 235       | 27.49%  |
| Broadcom                  | 40        | 4.68%   |
| Qualcomm Atheros          | 31        | 3.63%   |
| Marvell Technology Group  | 16        | 1.87%   |
| Nvidia                    | 14        | 1.64%   |
| Broadcom Limited          | 11        | 1.29%   |
| ASIX Electronics          | 10        | 1.17%   |
| Samsung Electronics       | 9         | 1.05%   |
| Xiaomi                    | 4         | 0.47%   |
| Hewlett-Packard           | 4         | 0.47%   |
| Microchip Technology      | 3         | 0.35%   |
| Huawei Technologies       | 3         | 0.35%   |
| Aquantia                  | 3         | 0.35%   |
| OPPO Electronics          | 2         | 0.23%   |
| JMicron Technology        | 2         | 0.23%   |
| Insyde Software           | 2         | 0.23%   |
| DisplayLink               | 2         | 0.23%   |
| D-Link System             | 2         | 0.23%   |
| TP-Link                   | 1         | 0.12%   |
| Spreadtrum Communications | 1         | 0.12%   |
| Qualcomm                  | 1         | 0.12%   |
| NetXen Incorporated       | 1         | 0.12%   |
| Microsoft                 | 1         | 0.12%   |
| MediaTek                  | 1         | 0.12%   |
| Linksys                   | 1         | 0.12%   |
| LG Electronics            | 1         | 0.12%   |
| Lenovo                    | 1         | 0.12%   |
| ICS Advent                | 1         | 0.12%   |
| IBM                       | 1         | 0.12%   |
| Google                    | 1         | 0.12%   |
| Dell                      | 1         | 0.12%   |
| Attansic Technology       | 1         | 0.12%   |
| Apple                     | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 327       | 37.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 57        | 6.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 33        | 3.78%   |
| Realtek RTL8125 2.5GbE Controller                                      | 32        | 3.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 24        | 2.75%   |
| Intel Ethernet Connection I217-LM                                      | 20        | 2.29%   |
| Intel I211 Gigabit Network Connection                                  | 13        | 1.49%   |
| Intel Ethernet Connection (2) I219-V                                   | 13        | 1.49%   |
| Intel Ethernet Controller I225-V                                       | 12        | 1.37%   |
| Intel Ethernet Connection I217-V                                       | 12        | 1.37%   |
| Intel Ethernet Connection I219-LM                                      | 11        | 1.26%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 1.03%   |
| Nvidia MCP61 Ethernet                                                  | 8         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 8         | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7         | 0.8%    |
| Intel 82579V Gigabit Network Connection                                | 7         | 0.8%    |
| Intel 82577LM Gigabit Network Connection                               | 7         | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 6         | 0.69%   |
| Nvidia MCP79 Ethernet                                                  | 6         | 0.69%   |
| Intel I210 Gigabit Network Connection                                  | 6         | 0.69%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 0.69%   |
| Intel 82567LM Gigabit Network Connection                               | 6         | 0.69%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 6         | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                  | 5         | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 4         | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 4         | 0.46%   |
| Intel Ethernet Connection (16) I219-V                                  | 4         | 0.46%   |
| Intel Ethernet Connection (14) I219-V                                  | 4         | 0.46%   |
| Intel Ethernet Connection (13) I219-V                                  | 4         | 0.46%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 0.46%   |
| Intel 82566MM Gigabit Network Connection                               | 4         | 0.46%   |
| HP HP lt4120 Snapdragon X5 LTE                                         | 4         | 0.46%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 4         | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.34%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 786       | 52.05%  |
| WiFi     | 705       | 46.69%  |
| Modem    | 17        | 1.13%   |
| Unknown  | 2         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 570       | 59.01%  |
| Ethernet | 396       | 40.99%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 503       | 52.95%  |
| 1     | 374       | 39.37%  |
| 0     | 47        | 4.95%   |
| 3     | 18        | 1.89%   |
| 4     | 5         | 0.53%   |
| 7     | 1         | 0.11%   |
| 6     | 1         | 0.11%   |
| 5     | 1         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 645       | 67.26%  |
| Yes  | 314       | 32.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 246       | 44.65%  |
| Realtek Semiconductor           | 74        | 13.43%  |
| Qualcomm Atheros Communications | 33        | 5.99%   |
| Broadcom                        | 33        | 5.99%   |
| Cambridge Silicon Radio         | 30        | 5.44%   |
| IMC Networks                    | 22        | 3.99%   |
| Foxconn / Hon Hai               | 22        | 3.99%   |
| Apple                           | 22        | 3.99%   |
| Lite-On Technology              | 21        | 3.81%   |
| MediaTek                        | 7         | 1.27%   |
| Hewlett-Packard                 | 6         | 1.09%   |
| Dell                            | 6         | 1.09%   |
| ASUSTek Computer                | 5         | 0.91%   |
| Realtek                         | 4         | 0.73%   |
| Foxconn International           | 3         | 0.54%   |
| USI                             | 2         | 0.36%   |
| TP-Link                         | 2         | 0.36%   |
| Toshiba                         | 2         | 0.36%   |
| Ralink Technology               | 2         | 0.36%   |
| Taiyo Yuden                     | 1         | 0.18%   |
| Ralink                          | 1         | 0.18%   |
| Micro Star International        | 1         | 0.18%   |
| Marvell Semiconductor           | 1         | 0.18%   |
| Fujitsu                         | 1         | 0.18%   |
| Edimax Technology               | 1         | 0.18%   |
| Chicony Electronics             | 1         | 0.18%   |
| Alps Electric                   | 1         | 0.18%   |
| AICSemi                         | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 109       | 19.71%  |
| Realtek Bluetooth Radio                             | 52        | 9.4%    |
| Intel AX201 Bluetooth                               | 40        | 7.23%   |
| Intel AX200 Bluetooth                               | 31        | 5.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 30        | 5.42%   |
| Intel Bluetooth Device                              | 20        | 3.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 3.44%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 2.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 1.99%   |
| Intel AX210 Bluetooth                               | 11        | 1.99%   |
| Apple Bluetooth Host Controller                     | 11        | 1.99%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 1.81%   |
| IMC Networks Bluetooth Radio                        | 10        | 1.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.08%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 1.08%   |
| MediaTek Wireless_Device                            | 6         | 1.08%   |
| IMC Networks Bluetooth Device                       | 6         | 1.08%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 1.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.9%    |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.9%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 5         | 0.9%    |
| Realtek Bluetooth Radio                             | 4         | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.72%   |
| Lite-On Bluetooth Device                            | 4         | 0.72%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 0.72%   |
| IMC Networks Wireless_Device                        | 4         | 0.72%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.72%   |
| Broadcom BCM20702A0                                 | 4         | 0.72%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.72%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.54%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.54%   |
| Lite-On Wireless_Device                             | 3         | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.54%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.54%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.54%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 660       | 54.5%   |
| AMD                                          | 248       | 20.48%  |
| Nvidia                                       | 189       | 15.61%  |
| Creative Labs                                | 10        | 0.83%   |
| C-Media Electronics                          | 10        | 0.83%   |
| Texas Instruments                            | 7         | 0.58%   |
| Logitech                                     | 6         | 0.5%    |
| Tenx Technology                              | 4         | 0.33%   |
| GN Netcom                                    | 4         | 0.33%   |
| Generalplus Technology                       | 4         | 0.33%   |
| ASUSTek Computer                             | 4         | 0.33%   |
| M-Audio                                      | 3         | 0.25%   |
| Lenovo                                       | 3         | 0.25%   |
| JMTek                                        | 3         | 0.25%   |
| Hewlett-Packard                              | 3         | 0.25%   |
| DSEA A/S                                     | 3         | 0.25%   |
| Creative Technology                          | 3         | 0.25%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.17%   |
| VIA Technologies                             | 2         | 0.17%   |
| SAVITECH                                     | 2         | 0.17%   |
| Realtek Semiconductor                        | 2         | 0.17%   |
| Razer USA                                    | 2         | 0.17%   |
| Micro Star International                     | 2         | 0.17%   |
| Medeli Electronics                           | 2         | 0.17%   |
| Focusrite-Novation                           | 2         | 0.17%   |
| Corsair                                      | 2         | 0.17%   |
| BEHRINGER International                      | 2         | 0.17%   |
| XMOS                                         | 1         | 0.08%   |
| Trust International                          | 1         | 0.08%   |
| Trust                                        | 1         | 0.08%   |
| Textech International                        | 1         | 0.08%   |
| TEAC                                         | 1         | 0.08%   |
| STMicroelectronics                           | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.08%   |
| Samson Technologies                          | 1         | 0.08%   |
| Roland                                       | 1         | 0.08%   |
| Reloop                                       | 1         | 0.08%   |
| PreSonus Audio Electronics                   | 1         | 0.08%   |
| Plantronics                                  | 1         | 0.08%   |
| Nordic Semiconductor ASA                     | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 89        | 6.12%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 60        | 4.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 56        | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 53        | 3.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 50        | 3.44%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 50        | 3.44%   |
| AMD FCH Azalia Controller                                                                         | 41        | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 36        | 2.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 35        | 2.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 34        | 2.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 31        | 2.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 28        | 1.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 26        | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 24        | 1.65%   |
| AMD Kabini HDMI/DP Audio                                                                          | 23        | 1.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 22        | 1.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 22        | 1.51%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 21        | 1.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 21        | 1.44%   |
| Intel 8 Series HD Audio Controller                                                                | 21        | 1.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21        | 1.44%   |
| Intel Cannon Lake PCH cAVS                                                                        | 20        | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 1.31%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 1.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 18        | 1.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 1.17%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 1.1%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 16        | 1.1%    |
| AMD Radeon High Definition Audio Controller                                                       | 15        | 1.03%   |
| Intel 200 Series PCH HD Audio                                                                     | 14        | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 0.89%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 13        | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 12        | 0.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 12        | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 11        | 0.76%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 0.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 11        | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 10        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 182       | 22.75%  |
| SK hynix                   | 141       | 17.63%  |
| Unknown                    | 94        | 11.75%  |
| Kingston                   | 85        | 10.63%  |
| Micron Technology          | 62        | 7.75%   |
| Crucial                    | 56        | 7%      |
| Corsair                    | 34        | 4.25%   |
| Ramaxel Technology         | 21        | 2.63%   |
| G.Skill                    | 20        | 2.5%    |
| Unknown (ABCD)             | 18        | 2.25%   |
| Nanya Technology           | 15        | 1.88%   |
| Unknown                    | 15        | 1.88%   |
| A-DATA Technology          | 10        | 1.25%   |
| Elpida                     | 7         | 0.88%   |
| Smart                      | 6         | 0.75%   |
| Transcend                  | 3         | 0.38%   |
| fef5                       | 3         | 0.38%   |
| V-Color                    | 2         | 0.25%   |
| Silicon Power              | 2         | 0.25%   |
| Unknown (AB)               | 1         | 0.13%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.13%   |
| Unknown (0x0B15)           | 1         | 0.13%   |
| Unifosa                    | 1         | 0.13%   |
| Timetec                    | 1         | 0.13%   |
| Ramos Technology           | 1         | 0.13%   |
| Qumo                       | 1         | 0.13%   |
| Qimonda                    | 1         | 0.13%   |
| PNY                        | 1         | 0.13%   |
| Mushkin                    | 1         | 0.13%   |
| Micron/Elpida              | 1         | 0.13%   |
| Melco                      | 1         | 0.13%   |
| KETECH                     | 1         | 0.13%   |
| Hikvision                  | 1         | 0.13%   |
| Goldenmars                 | 1         | 0.13%   |
| GLOWAY                     | 1         | 0.13%   |
| GIGA-BYTE                  | 1         | 0.13%   |
| GeIL                       | 1         | 0.13%   |
| Foxline                    | 1         | 0.13%   |
| Essencore                  | 1         | 0.13%   |
| Daten Tecnologia           | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 15        | 1.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 12        | 1.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 1.16%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 8         | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.93%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 6         | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.7%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.58%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.58%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 5         | 0.58%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 4         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 4         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.46%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 4         | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 4         | 0.46%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 4         | 0.46%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 4         | 0.46%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 4         | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.46%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.46%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 4         | 0.46%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s          | 4         | 0.46%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s            | 4         | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 3         | 0.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.35%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.35%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.35%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 3         | 0.35%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s             | 3         | 0.35%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 3         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 277       | 39.86%  |
| DDR3    | 242       | 34.82%  |
| DDR2    | 41        | 5.9%    |
| LPDDR4  | 37        | 5.32%   |
| SDRAM   | 23        | 3.31%   |
| Unknown | 23        | 3.31%   |
| DDR5    | 17        | 2.45%   |
| LPDDR5  | 14        | 2.01%   |
| LPDDR3  | 14        | 2.01%   |
| DRAM    | 5         | 0.72%   |
| DDR     | 2         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 393       | 57.12%  |
| DIMM         | 241       | 35.03%  |
| Row Of Chips | 42        | 6.1%    |
| Unknown      | 7         | 1.02%   |
| Chip         | 5         | 0.73%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 237       | 31.6%   |
| 4096  | 207       | 27.6%   |
| 16384 | 123       | 16.4%   |
| 2048  | 121       | 16.13%  |
| 1024  | 30        | 4%      |
| 32768 | 27        | 3.6%    |
| 512   | 3         | 0.4%    |
| 65536 | 1         | 0.13%   |
| 1536  | 1         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 156       | 20.91%  |
| 3200    | 120       | 16.09%  |
| 2667    | 82        | 10.99%  |
| 2400    | 58        | 7.77%   |
| 1333    | 47        | 6.3%    |
| 2133    | 32        | 4.29%   |
| 667     | 24        | 3.22%   |
| 1334    | 21        | 2.82%   |
| 3600    | 17        | 2.28%   |
| 1067    | 15        | 2.01%   |
| Unknown | 15        | 2.01%   |
| 800     | 13        | 1.74%   |
| 4800    | 9         | 1.21%   |
| 1867    | 9         | 1.21%   |
| 6400    | 8         | 1.07%   |
| 4267    | 8         | 1.07%   |
| 3733    | 8         | 1.07%   |
| 3266    | 8         | 1.07%   |
| 1066    | 8         | 1.07%   |
| 4199    | 7         | 0.94%   |
| 2666    | 6         | 0.8%    |
| 5600    | 5         | 0.67%   |
| 3000    | 5         | 0.67%   |
| 2000    | 5         | 0.67%   |
| 1866    | 5         | 0.67%   |
| 1800    | 5         | 0.67%   |
| 7500    | 4         | 0.54%   |
| 3466    | 3         | 0.4%    |
| 2048    | 3         | 0.4%    |
| 8400    | 2         | 0.27%   |
| 6000    | 2         | 0.27%   |
| 4266    | 2         | 0.27%   |
| 4000    | 2         | 0.27%   |
| 3800    | 2         | 0.27%   |
| 3400    | 2         | 0.27%   |
| 2933    | 2         | 0.27%   |
| 2134    | 2         | 0.27%   |
| 1776    | 2         | 0.27%   |
| 1639    | 2         | 0.27%   |
| 975     | 2         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 36%     |
| Brother Industries  | 4         | 16%     |
| Samsung Electronics | 3         | 12%     |
| Seiko Epson         | 2         | 8%      |
| Zebra               | 1         | 4%      |
| Xiaomi              | 1         | 4%      |
| QinHeng Electronics | 1         | 4%      |
| Minolta             | 1         | 4%      |
| Kyocera             | 1         | 4%      |
| Canon               | 1         | 4%      |
| Belkin Components   | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Zebra ZTC ZP 500 (ZPL)                 | 1         | 4%      |
| Xiaomi MiMouse 2                       | 1         | 4%      |
| Seiko Epson L120 Series                | 1         | 4%      |
| Seiko Epson ET-2710 Series             | 1         | 4%      |
| Samsung SF-760 Series                  | 1         | 4%      |
| Samsung ML-1865                        | 1         | 4%      |
| Samsung ML-1630 Series                 | 1         | 4%      |
| QinHeng CH340S                         | 1         | 4%      |
| Minolta PagePro 1300W                  | 1         | 4%      |
| Kyocera FS-1300D                       | 1         | 4%      |
| HP Officejet 4500 G510n-z              | 1         | 4%      |
| HP LaserJet P1102                      | 1         | 4%      |
| HP LaserJet 400 M401dne                | 1         | 4%      |
| HP ENVY Pro 6400 series                | 1         | 4%      |
| HP DeskJet F4100 Printer series        | 1         | 4%      |
| HP DeskJet D1360                       | 1         | 4%      |
| HP DeskJet 840c                        | 1         | 4%      |
| HP DeskJet 810c/812c                   | 1         | 4%      |
| HP Deskjet 3070 B611 series            | 1         | 4%      |
| Canon TS3500 series                    | 1         | 4%      |
| Brother QL-560 Label Printer           | 1         | 4%      |
| Brother MFC-9130CW                     | 1         | 4%      |
| Brother HL-2030 Laser Printer          | 1         | 4%      |
| Brother DCP-7040                       | 1         | 4%      |
| Belkin Components IEEE-1284 Controller | 1         | 4%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 66.67%  |
| Seiko Epson     | 2         | 22.22%  |
| Hewlett-Packard | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                | 3         | 33.33%  |
| Seiko Epson GT-9800F [Perfection 3200] | 1         | 11.11%  |
| Seiko Epson GT-1500 [GT-D1000]         | 1         | 11.11%  |
| HP ScanJet 7400c                       | 1         | 11.11%  |
| Canon CanoScan LIDE 25                 | 1         | 11.11%  |
| Canon CanoScan LiDE 110                | 1         | 11.11%  |
| Canon CanoScan 4400F                   | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 122       | 21.67%  |
| Realtek Semiconductor                  | 41        | 7.28%   |
| Microdia                               | 41        | 7.28%   |
| IMC Networks                           | 39        | 6.93%   |
| Bison Electronics                      | 36        | 6.39%   |
| Quanta                                 | 34        | 6.04%   |
| Logitech                               | 33        | 5.86%   |
| Sunplus Innovation Technology          | 26        | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 25        | 4.44%   |
| Suyin                                  | 19        | 3.37%   |
| Apple                                  | 19        | 3.37%   |
| Syntek                                 | 12        | 2.13%   |
| Luxvisions Innotech Limited            | 12        | 2.13%   |
| Lite-On Technology                     | 11        | 1.95%   |
| Silicon Motion                         | 8         | 1.42%   |
| Z-Star Microelectronics                | 7         | 1.24%   |
| Sonix Technology                       | 6         | 1.07%   |
| Samsung Electronics                    | 6         | 1.07%   |
| Ricoh                                  | 6         | 1.07%   |
| Microsoft                              | 5         | 0.89%   |
| Alcor Micro                            | 5         | 0.89%   |
| MacroSilicon                           | 3         | 0.53%   |
| Lenovo                                 | 3         | 0.53%   |
| Jieli Technology                       | 3         | 0.53%   |
| icSpring                               | 3         | 0.53%   |
| Generalplus Technology                 | 3         | 0.53%   |
| USB Camera CS                          | 2         | 0.36%   |
| SunplusIT                              | 2         | 0.36%   |
| Sunplus Technology                     | 2         | 0.36%   |
| Shinetech                              | 2         | 0.36%   |
| KYE Systems (Mouse Systems)            | 2         | 0.36%   |
| Importek                               | 2         | 0.36%   |
| ARC International                      | 2         | 0.36%   |
| Xiongmai                               | 1         | 0.18%   |
| Xiaomi                                 | 1         | 0.18%   |
| Web Camera                             | 1         | 0.18%   |
| ValueHD                                | 1         | 0.18%   |
| Trust                                  | 1         | 0.18%   |
| Ruision                                | 1         | 0.18%   |
| Primax Electronics                     | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 36        | 6.36%   |
| Microdia Integrated_Webcam_HD                       | 14        | 2.47%   |
| Realtek Integrated_Webcam_HD                        | 12        | 2.12%   |
| Bison Integrated Camera                             | 12        | 2.12%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 11        | 1.94%   |
| Chicony HD WebCam                                   | 11        | 1.94%   |
| Sunplus Integrated_Webcam_HD                        | 10        | 1.77%   |
| Apple Built-in iSight                               | 10        | 1.77%   |
| Quanta HD User Facing                               | 9         | 1.59%   |
| IMC Networks Integrated Camera                      | 9         | 1.59%   |
| Chicony TOSHIBA Web Camera - HD                     | 9         | 1.59%   |
| Syntek Integrated Camera                            | 8         | 1.41%   |
| Logitech Webcam C270                                | 7         | 1.24%   |
| Logitech C922 Pro Stream Webcam                     | 7         | 1.24%   |
| Samsung Galaxy series, misc. (MTP mode)             | 6         | 1.06%   |
| Microdia USB 2.0 Camera                             | 6         | 1.06%   |
| Lite-On Integrated Camera                           | 6         | 1.06%   |
| Chicony HP Truevision HD camera                     | 6         | 1.06%   |
| Sunplus Integrated_Webcam_FHD                       | 5         | 0.88%   |
| Quanta HP TrueVision HD Camera                      | 5         | 0.88%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 5         | 0.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 5         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 5         | 0.88%   |
| Bison Lenovo EasyCamera                             | 5         | 0.88%   |
| Realtek Lenovo EasyCamera                           | 4         | 0.71%   |
| Quanta HP Webcam                                    | 4         | 0.71%   |
| Logitech HD Pro Webcam C920                         | 4         | 0.71%   |
| Chicony Chicony USB2.0 Camera                       | 4         | 0.71%   |
| Chicony 1.3M Webcam                                 | 4         | 0.71%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 0.71%   |
| Alcor Micro USB 2.0 Camera                          | 4         | 0.71%   |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 0.53%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 0.53%   |
| Ricoh Sony Visual Communication Camera              | 3         | 0.53%   |
| Realtek USB Camera                                  | 3         | 0.53%   |
| Realtek Integrated_Webcam_FHD                       | 3         | 0.53%   |
| Realtek Acer 640 x 480 laptop camera                | 3         | 0.53%   |
| Quanta HP HD Camera                                 | 3         | 0.53%   |
| Microdia Webcam Vitade AF                           | 3         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 33        | 36.26%  |
| Synaptics                          | 16        | 17.58%  |
| Shenzhen Goodix Technology         | 14        | 15.38%  |
| Upek                               | 10        | 10.99%  |
| Elan Microelectronics              | 6         | 6.59%   |
| STMicroelectronics                 | 4         | 4.4%    |
| AuthenTec                          | 3         | 3.3%    |
| Realtek USB2.0 Finger Print Bridge | 2         | 2.2%    |
| LighTuning Technology              | 1         | 1.1%    |
| Gingytech                          | 1         | 1.1%    |
| Focal-systems.Corp                 | 1         | 1.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 10        | 10.99%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 9         | 9.89%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 8         | 8.79%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 8         | 8.79%   |
| Validity Sensors Synaptics WBDI                                 | 5         | 5.49%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 5         | 5.49%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 4         | 4.4%    |
| STMicroelectronics Fingerprint Reader                           | 4         | 4.4%    |
| Elan ELAN:ARM-M4                                                | 4         | 4.4%    |
| Validity Sensors VFS451 Fingerprint Reader                      | 3         | 3.3%    |
| Synaptics  WBDI                                                 | 3         | 3.3%    |
| Synaptics Prometheus Fingerprint Reader                         | 3         | 3.3%    |
| Shenzhen Goodix Fingerprint Reader                              | 3         | 3.3%    |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 2.2%    |
| Synaptics UWP WBDI Device                                       | 2         | 2.2%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 2.2%    |
| Elan ELAN:Fingerprint                                           | 2         | 2.2%    |
| AuthenTec AES2501 Fingerprint Sensor                            | 2         | 2.2%    |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 1.1%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 1.1%    |
| Validity Sensors Fingerprint scanner                            | 1         | 1.1%    |
| Upek TCS5B Fingerprint sensor                                   | 1         | 1.1%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.1%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 1.1%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.1%    |
| Shenzhen Goodix FingerPrint                                     | 1         | 1.1%    |
| LighTuning Fingerprint Sensor                                   | 1         | 1.1%    |
| Gingytech Fingerprint sensor                                    | 1         | 1.1%    |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 1.1%    |
| AuthenTec AES2810                                               | 1         | 1.1%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 22        | 44%     |
| Alcor Micro              | 17        | 34%     |
| Lenovo                   | 5         | 10%     |
| O2 Micro                 | 4         | 8%      |
| Reiner SCT Kartensysteme | 1         | 2%      |
| In Focus Systems         | 1         | 2%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 34%     |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 14%     |
| Broadcom 5880                                                                | 6         | 12%     |
| Lenovo Integrated Smart Card Reader                                          | 5         | 10%     |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 5         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 6%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 4%      |
| Broadcom 58200                                                               | 2         | 4%      |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 2%      |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2%      |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 2%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 688       | 71.74%  |
| 1     | 208       | 21.69%  |
| 2     | 55        | 5.74%   |
| 3     | 7         | 0.73%   |
| 5     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 88        | 26.83%  |
| Graphics card            | 77        | 23.48%  |
| Chipcard                 | 48        | 14.63%  |
| Camera                   | 25        | 7.62%   |
| Net/wireless             | 24        | 7.32%   |
| Unassigned class         | 12        | 3.66%   |
| Multimedia controller    | 11        | 3.35%   |
| Bluetooth                | 10        | 3.05%   |
| Communication controller | 8         | 2.44%   |
| Network                  | 6         | 1.83%   |
| Storage                  | 5         | 1.52%   |
| Net/ethernet             | 5         | 1.52%   |
| Card reader              | 5         | 1.52%   |
| Sound                    | 3         | 0.91%   |
| Dvb card                 | 1         | 0.3%    |

