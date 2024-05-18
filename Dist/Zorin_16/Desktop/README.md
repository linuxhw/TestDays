Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

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

Total: 2319

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | H55                         | [83c1ac4239](https://linux-hardware.org/?probe=83c1ac4239) | May 07, 2024 |
| Dell          | 0M5DCD A00                  | [f390e47ea1](https://linux-hardware.org/?probe=f390e47ea1) | May 03, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [257f9cdad4](https://linux-hardware.org/?probe=257f9cdad4) | May 03, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [1a3ebd462f](https://linux-hardware.org/?probe=1a3ebd462f) | May 02, 2024 |
| AOpen         | D1009 A1A4                  | [f5399e68ef](https://linux-hardware.org/?probe=f5399e68ef) | Apr 27, 2024 |
| ASUSTek       | M4A78 PRO                   | [4a79911a5b](https://linux-hardware.org/?probe=4a79911a5b) | Apr 24, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [12f44c7a5a](https://linux-hardware.org/?probe=12f44c7a5a) | Apr 23, 2024 |
| Lenovo        | 3098 SDK0E50510 WIN         | [6f1ba910cd](https://linux-hardware.org/?probe=6f1ba910cd) | Apr 23, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [b3fc204759](https://linux-hardware.org/?probe=b3fc204759) | Apr 14, 2024 |
| ASUSTek       | P8Z68-V GEN3                | [39d3eeda79](https://linux-hardware.org/?probe=39d3eeda79) | Apr 12, 2024 |
| ASUSTek       | CM6870                      | [0c29f72def](https://linux-hardware.org/?probe=0c29f72def) | Apr 10, 2024 |
| Dell          | 0XCR8D A01                  | [9d38e92df0](https://linux-hardware.org/?probe=9d38e92df0) | Apr 09, 2024 |
| Dell          | 0XCR8D A01                  | [a0b8193ba4](https://linux-hardware.org/?probe=a0b8193ba4) | Apr 09, 2024 |
| Dell          | 0VYXHD A00                  | [c0cfa74664](https://linux-hardware.org/?probe=c0cfa74664) | Apr 09, 2024 |
| MSI           | H81M-E34                    | [62882b5228](https://linux-hardware.org/?probe=62882b5228) | Apr 02, 2024 |
| ASUSTek       | PRIME X570-PRO              | [740eb90402](https://linux-hardware.org/?probe=740eb90402) | Mar 30, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [00e4cbdc6e](https://linux-hardware.org/?probe=00e4cbdc6e) | Mar 29, 2024 |
| ASUSTek       | M5A78L-M LX3                | [a549e35cf7](https://linux-hardware.org/?probe=a549e35cf7) | Mar 26, 2024 |
| HP            | 3029h                       | [1913f87768](https://linux-hardware.org/?probe=1913f87768) | Mar 25, 2024 |
| HP            | 8767 A                      | [167796eedc](https://linux-hardware.org/?probe=167796eedc) | Mar 25, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [f8ca0e66e2](https://linux-hardware.org/?probe=f8ca0e66e2) | Mar 24, 2024 |
| MSI           | H81M-E34                    | [5ab741f203](https://linux-hardware.org/?probe=5ab741f203) | Mar 21, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [f7f667d127](https://linux-hardware.org/?probe=f7f667d127) | Mar 21, 2024 |
| Intel         | DQ45CB AAE30148-207         | [779eb3b38f](https://linux-hardware.org/?probe=779eb3b38f) | Mar 20, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9ce06e146a](https://linux-hardware.org/?probe=9ce06e146a) | Mar 19, 2024 |
| Dell          | 0T656F A01                  | [325c5efb6e](https://linux-hardware.org/?probe=325c5efb6e) | Mar 18, 2024 |
| ASUSTek       | PRIME B250M-A               | [6477033da6](https://linux-hardware.org/?probe=6477033da6) | Mar 18, 2024 |
| eMachines     | MCP61PM-GM                  | [c92849e391](https://linux-hardware.org/?probe=c92849e391) | Mar 18, 2024 |
| Dell          | 0M9KCM A02                  | [7823cafa72](https://linux-hardware.org/?probe=7823cafa72) | Mar 15, 2024 |
| Dell          | 0M9KCM A02                  | [6dd5b76d21](https://linux-hardware.org/?probe=6dd5b76d21) | Mar 15, 2024 |
| Supermicro    | C7Q67 V1.01                 | [4fe003a84f](https://linux-hardware.org/?probe=4fe003a84f) | Mar 13, 2024 |
| Foxconn       | 946 7MA Series              | [7453cdde18](https://linux-hardware.org/?probe=7453cdde18) | Mar 09, 2024 |
| Biostar       | G41-M7                      | [54836e3fbe](https://linux-hardware.org/?probe=54836e3fbe) | Mar 08, 2024 |
| ASUSTek       | P8Z77-V PRO                 | [b18d2c6cab](https://linux-hardware.org/?probe=b18d2c6cab) | Mar 08, 2024 |
| ASUSTek       | M5A78L-M LX3                | [445ff9dc64](https://linux-hardware.org/?probe=445ff9dc64) | Feb 28, 2024 |
| ASUSTek       | P8Z77-V LX                  | [4d913de0c0](https://linux-hardware.org/?probe=4d913de0c0) | Feb 21, 2024 |
| ASUSTek       | P8Z77-V LX                  | [bddbc049f7](https://linux-hardware.org/?probe=bddbc049f7) | Feb 21, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [9d5c5dfeb7](https://linux-hardware.org/?probe=9d5c5dfeb7) | Feb 20, 2024 |
| Gigabyte      | H61M-DS2                    | [581dd97a4d](https://linux-hardware.org/?probe=581dd97a4d) | Feb 20, 2024 |
| ASUSTek       | B85M-E                      | [d1bbdc0a03](https://linux-hardware.org/?probe=d1bbdc0a03) | Feb 19, 2024 |
| AZW           | Gemini T45                  | [9a81383d10](https://linux-hardware.org/?probe=9a81383d10) | Feb 19, 2024 |
| Gigabyte      | M720-US3                    | [79c1cffeae](https://linux-hardware.org/?probe=79c1cffeae) | Feb 17, 2024 |
| Gigabyte      | M720-US3                    | [340b590f33](https://linux-hardware.org/?probe=340b590f33) | Feb 17, 2024 |
| ASUSTek       | P8Z77-V LX                  | [2d74906a7d](https://linux-hardware.org/?probe=2d74906a7d) | Feb 16, 2024 |
| ASUSTek       | Rampage II Extreme          | [42f4db38c2](https://linux-hardware.org/?probe=42f4db38c2) | Feb 16, 2024 |
| ASUSTek       | M5A78L-M LX3                | [78b9324e29](https://linux-hardware.org/?probe=78b9324e29) | Feb 16, 2024 |
| Dell          | 0C522T A00                  | [fc865abc9f](https://linux-hardware.org/?probe=fc865abc9f) | Feb 16, 2024 |
| ASRock        | AB350 Pro4                  | [5b8e7f1992](https://linux-hardware.org/?probe=5b8e7f1992) | Feb 14, 2024 |
| Acer          | Acadia V1.34                | [6807342689](https://linux-hardware.org/?probe=6807342689) | Feb 13, 2024 |
| Dell          | 0VYXHD A00                  | [134cac2a6d](https://linux-hardware.org/?probe=134cac2a6d) | Feb 11, 2024 |
| Dell          | 0VYXHD A00                  | [8178dd22d5](https://linux-hardware.org/?probe=8178dd22d5) | Feb 11, 2024 |
| Dell          | 0VRWRC A00                  | [1dfe3721a8](https://linux-hardware.org/?probe=1dfe3721a8) | Feb 09, 2024 |
| ASRock        | B250M-HDV PS                | [b18ea679bb](https://linux-hardware.org/?probe=b18ea679bb) | Feb 08, 2024 |
| MSI           | B450M GAMING PLUS           | [62af32fc16](https://linux-hardware.org/?probe=62af32fc16) | Feb 07, 2024 |
| ASUSTek       | M2N68-AM Plus               | [8800fba01e](https://linux-hardware.org/?probe=8800fba01e) | Feb 06, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [927466a797](https://linux-hardware.org/?probe=927466a797) | Feb 05, 2024 |
| Dell          | 0G214D A00                  | [1a1b425da2](https://linux-hardware.org/?probe=1a1b425da2) | Feb 04, 2024 |
| ASRock        | 4Core1600-D800              | [70cc10cb2c](https://linux-hardware.org/?probe=70cc10cb2c) | Feb 04, 2024 |
| Gigabyte      | GA-990FXA-UD7               | [50c2a07f8a](https://linux-hardware.org/?probe=50c2a07f8a) | Feb 04, 2024 |
| ASRock        | 4Core1600-D800              | [c34e1b1365](https://linux-hardware.org/?probe=c34e1b1365) | Feb 04, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [39712fdfe2](https://linux-hardware.org/?probe=39712fdfe2) | Feb 03, 2024 |
| ASRock        | G31M-S                      | [a596a04111](https://linux-hardware.org/?probe=a596a04111) | Feb 03, 2024 |
| Gigabyte      | GA-990FXA-UD7               | [66768ccdf7](https://linux-hardware.org/?probe=66768ccdf7) | Feb 02, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [3074b7c2a6](https://linux-hardware.org/?probe=3074b7c2a6) | Feb 02, 2024 |
| Gigabyte      | GA-990FXA-UD7               | [4726161c35](https://linux-hardware.org/?probe=4726161c35) | Feb 02, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [62dc25b8b6](https://linux-hardware.org/?probe=62dc25b8b6) | Feb 02, 2024 |
| Unknown       | Unknown                     | [4fa0768f2b](https://linux-hardware.org/?probe=4fa0768f2b) | Feb 01, 2024 |
| Unknown       | Unknown                     | [69b18742b6](https://linux-hardware.org/?probe=69b18742b6) | Feb 01, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [3cedb3c573](https://linux-hardware.org/?probe=3cedb3c573) | Feb 01, 2024 |
| Huanan        | X99-8M-F V1.4               | [7625188b91](https://linux-hardware.org/?probe=7625188b91) | Jan 31, 2024 |
| Gigabyte      | H110M-H-CF                  | [d1065a1aca](https://linux-hardware.org/?probe=d1065a1aca) | Jan 30, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [073f673b78](https://linux-hardware.org/?probe=073f673b78) | Jan 29, 2024 |
| Dell          | 0RY007                      | [151f303198](https://linux-hardware.org/?probe=151f303198) | Jan 29, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [292b1b06ca](https://linux-hardware.org/?probe=292b1b06ca) | Jan 28, 2024 |
| ASRock        | G31M-S                      | [3030db55a6](https://linux-hardware.org/?probe=3030db55a6) | Jan 28, 2024 |
| MSI           | Z490-A PRO                  | [a851d2d2fe](https://linux-hardware.org/?probe=a851d2d2fe) | Jan 28, 2024 |
| Gigabyte      | Z97X-UD5H                   | [fd0ab9a9ac](https://linux-hardware.org/?probe=fd0ab9a9ac) | Jan 28, 2024 |
| Dell          | 0GDG8Y A00                  | [47f8ef1ba6](https://linux-hardware.org/?probe=47f8ef1ba6) | Jan 27, 2024 |
| Dell          | 0Y5DDC A00                  | [1912506274](https://linux-hardware.org/?probe=1912506274) | Jan 26, 2024 |
| ASUSTek       | CM6870                      | [1abc8128a3](https://linux-hardware.org/?probe=1abc8128a3) | Jan 26, 2024 |
| HP            | 3647h                       | [14bc5e74bc](https://linux-hardware.org/?probe=14bc5e74bc) | Jan 26, 2024 |
| Dell          | 048DY8 A01                  | [d5e6914489](https://linux-hardware.org/?probe=d5e6914489) | Jan 26, 2024 |
| Dell          | 0GDG8Y A00                  | [18de9933d4](https://linux-hardware.org/?probe=18de9933d4) | Jan 24, 2024 |
| Alienware     | 07W25T A01                  | [538d2e2b5f](https://linux-hardware.org/?probe=538d2e2b5f) | Jan 24, 2024 |
| Dell          | 0D28YY A00                  | [8d8d8005b1](https://linux-hardware.org/?probe=8d8d8005b1) | Jan 23, 2024 |
| Gigabyte      | X58A-UD3R                   | [eed9a3591f](https://linux-hardware.org/?probe=eed9a3591f) | Jan 23, 2024 |
| Gigabyte      | X58A-UD3R                   | [8479b771e4](https://linux-hardware.org/?probe=8479b771e4) | Jan 23, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [41a378391c](https://linux-hardware.org/?probe=41a378391c) | Jan 22, 2024 |
| Alienware     | 07W25T A01                  | [2a7a6fd405](https://linux-hardware.org/?probe=2a7a6fd405) | Jan 22, 2024 |
| MSI           | 760GM-P34                   | [3eb4ebb737](https://linux-hardware.org/?probe=3eb4ebb737) | Jan 21, 2024 |
| Foxconn       | 946 7MA Series              | [40261803d6](https://linux-hardware.org/?probe=40261803d6) | Jan 21, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [c3733ef1e3](https://linux-hardware.org/?probe=c3733ef1e3) | Jan 18, 2024 |
| ASUSTek       | PRIME B460M-A               | [518ca600f6](https://linux-hardware.org/?probe=518ca600f6) | Jan 18, 2024 |
| Dell          | 0GTK4K A02                  | [a4aef81553](https://linux-hardware.org/?probe=a4aef81553) | Jan 18, 2024 |
| Intel         | DQ67SW AAG12527-310         | [4c5f54d07e](https://linux-hardware.org/?probe=4c5f54d07e) | Jan 15, 2024 |
| Dell          | OptiPlex 7050               | [f0c2b782ff](https://linux-hardware.org/?probe=f0c2b782ff) | Jan 15, 2024 |
| Intel         | X99-P4 V5.0                 | [574a971f93](https://linux-hardware.org/?probe=574a971f93) | Jan 14, 2024 |
| ASUSTek       | Z170-P                      | [b3d8c3265d](https://linux-hardware.org/?probe=b3d8c3265d) | Jan 14, 2024 |
| Lenovo        | ThinkCentre M70E 0830W36    | [f28fd8d379](https://linux-hardware.org/?probe=f28fd8d379) | Jan 14, 2024 |
| HP            | 3647h                       | [e9767a4e96](https://linux-hardware.org/?probe=e9767a4e96) | Jan 12, 2024 |
| HP            | 3647h                       | [39414040e7](https://linux-hardware.org/?probe=39414040e7) | Jan 12, 2024 |
| Gateway       | SX2851                      | [0cbcae7c27](https://linux-hardware.org/?probe=0cbcae7c27) | Jan 11, 2024 |
| Acer          | Veriton X490G               | [1110362d9a](https://linux-hardware.org/?probe=1110362d9a) | Jan 11, 2024 |
| Dell          | 0T1D10 A01                  | [0c1256487e](https://linux-hardware.org/?probe=0c1256487e) | Jan 11, 2024 |
| Unknown       | Unknown                     | [ca7b5632f4](https://linux-hardware.org/?probe=ca7b5632f4) | Jan 09, 2024 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [d5486716d1](https://linux-hardware.org/?probe=d5486716d1) | Jan 09, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | [50877161c2](https://linux-hardware.org/?probe=50877161c2) | Jan 08, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | [cb7c295dc6](https://linux-hardware.org/?probe=cb7c295dc6) | Jan 08, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [ac3aa9697a](https://linux-hardware.org/?probe=ac3aa9697a) | Jan 07, 2024 |
| Intel         | H61                         | [a0d05acffb](https://linux-hardware.org/?probe=a0d05acffb) | Jan 07, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [8f181c2fb8](https://linux-hardware.org/?probe=8f181c2fb8) | Jan 07, 2024 |
| Biostar       | A320MH                      | [9bec9420ab](https://linux-hardware.org/?probe=9bec9420ab) | Jan 06, 2024 |
| ASUSTek       | B85M-E                      | [1f5304b336](https://linux-hardware.org/?probe=1f5304b336) | Jan 06, 2024 |
| ASUSTek       | B85M-E                      | [7c7fb3af69](https://linux-hardware.org/?probe=7c7fb3af69) | Jan 06, 2024 |
| ASRock        | G31M-S                      | [1b44835106](https://linux-hardware.org/?probe=1b44835106) | Jan 06, 2024 |
| Dell          | 0HN7XN A01                  | [f154d2ee51](https://linux-hardware.org/?probe=f154d2ee51) | Jan 06, 2024 |
| ASUSTek       | PRIME X399-A                | [5f016cc67b](https://linux-hardware.org/?probe=5f016cc67b) | Jan 05, 2024 |
| Dell          | 0T1D10 A01                  | [36fd42ae37](https://linux-hardware.org/?probe=36fd42ae37) | Jan 05, 2024 |
| Dell          | 0HN7XN A01                  | [91b070152e](https://linux-hardware.org/?probe=91b070152e) | Jan 05, 2024 |
| Lenovo        | ThinkCentre M71e 3156PT5    | [53089d138d](https://linux-hardware.org/?probe=53089d138d) | Jan 03, 2024 |
| Intel         | DQ67SW AAG12527-310         | [64811dfb22](https://linux-hardware.org/?probe=64811dfb22) | Jan 03, 2024 |
| Dell          | 0D28YY A01                  | [f67d5d22eb](https://linux-hardware.org/?probe=f67d5d22eb) | Jan 02, 2024 |
| Gigabyte      | Z590 UD AC                  | [0db9ec67ac](https://linux-hardware.org/?probe=0db9ec67ac) | Jan 02, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [d2112b91c1](https://linux-hardware.org/?probe=d2112b91c1) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [252e78398a](https://linux-hardware.org/?probe=252e78398a) | Jan 01, 2024 |
| ASUSTek       | CM6870                      | [bdc19328ef](https://linux-hardware.org/?probe=bdc19328ef) | Dec 31, 2023 |
| Dell          | 0RW199                      | [62dc9ffa33](https://linux-hardware.org/?probe=62dc9ffa33) | Dec 31, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [e330d0191e](https://linux-hardware.org/?probe=e330d0191e) | Dec 31, 2023 |
| ASUSTek       | PRIME X399-A                | [ac506b01e6](https://linux-hardware.org/?probe=ac506b01e6) | Dec 30, 2023 |
| HP            | 82F1                        | [9fc9cb3de0](https://linux-hardware.org/?probe=9fc9cb3de0) | Dec 30, 2023 |
| Dell          | 0VRWRC A00                  | [c58ff5350b](https://linux-hardware.org/?probe=c58ff5350b) | Dec 30, 2023 |
| Pegatron      | 2A9A                        | [92def1bf4a](https://linux-hardware.org/?probe=92def1bf4a) | Dec 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7dca6779be](https://linux-hardware.org/?probe=7dca6779be) | Dec 29, 2023 |
| ASRock        | B550M-C                     | [ba3fa09385](https://linux-hardware.org/?probe=ba3fa09385) | Dec 29, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [7a34810f0e](https://linux-hardware.org/?probe=7a34810f0e) | Dec 29, 2023 |
| ASUSTek       | PRIME X399-A                | [4d46811257](https://linux-hardware.org/?probe=4d46811257) | Dec 29, 2023 |
| Dell          | 0GDG8Y A00                  | [59c76d34e1](https://linux-hardware.org/?probe=59c76d34e1) | Dec 27, 2023 |
| ASUSTek       | M4A79T Deluxe               | [167d330ef0](https://linux-hardware.org/?probe=167d330ef0) | Dec 27, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [bc9feace53](https://linux-hardware.org/?probe=bc9feace53) | Dec 27, 2023 |
| Pegatron      | 2A9A                        | [e67022179a](https://linux-hardware.org/?probe=e67022179a) | Dec 26, 2023 |
| Dell          | 0GDG8Y A00                  | [52a5621ef8](https://linux-hardware.org/?probe=52a5621ef8) | Dec 25, 2023 |
| Intel         | DH77EB AAG39073-304         | [0cee3977a0](https://linux-hardware.org/?probe=0cee3977a0) | Dec 25, 2023 |
| Dell          | 0MN1TX A04                  | [ba94c75ba0](https://linux-hardware.org/?probe=ba94c75ba0) | Dec 25, 2023 |
| HP            | 2AF7                        | [2fc4d5dd6b](https://linux-hardware.org/?probe=2fc4d5dd6b) | Dec 24, 2023 |
| HP            | 2AF7                        | [baa5012432](https://linux-hardware.org/?probe=baa5012432) | Dec 24, 2023 |
| HP            | 0B4Ch D                     | [2f8f606e9f](https://linux-hardware.org/?probe=2f8f606e9f) | Dec 24, 2023 |
| HP            | 0B4Ch D                     | [6ee70cb266](https://linux-hardware.org/?probe=6ee70cb266) | Dec 24, 2023 |
| ASUSTek       | M2V                         | [67c7bc43ed](https://linux-hardware.org/?probe=67c7bc43ed) | Dec 23, 2023 |
| ASUSTek       | M2V                         | [1d6970f290](https://linux-hardware.org/?probe=1d6970f290) | Dec 23, 2023 |
| HP            | 1998                        | [8eb25518c4](https://linux-hardware.org/?probe=8eb25518c4) | Dec 23, 2023 |
| Gigabyte      | B650 GAMING X AX            | [9c0210d1ed](https://linux-hardware.org/?probe=9c0210d1ed) | Dec 22, 2023 |
| Gigabyte      | B450 AORUS M                | [084e48827c](https://linux-hardware.org/?probe=084e48827c) | Dec 21, 2023 |
| Intel         | DH77EB AAG39073-304         | [83183dbb01](https://linux-hardware.org/?probe=83183dbb01) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6311def15e](https://linux-hardware.org/?probe=6311def15e) | Dec 21, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [8b094a74c9](https://linux-hardware.org/?probe=8b094a74c9) | Dec 21, 2023 |
| ASUSTek       | M5A99X EVO                  | [c0c637bbba](https://linux-hardware.org/?probe=c0c637bbba) | Dec 21, 2023 |
| Dell          | 0FM586                      | [eadcdb629b](https://linux-hardware.org/?probe=eadcdb629b) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [af51ef8978](https://linux-hardware.org/?probe=af51ef8978) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7cda066ff6](https://linux-hardware.org/?probe=7cda066ff6) | Dec 20, 2023 |
| HP            | 1998                        | [bc41363911](https://linux-hardware.org/?probe=bc41363911) | Dec 20, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a411802ac6](https://linux-hardware.org/?probe=a411802ac6) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [ad9eaf3ae6](https://linux-hardware.org/?probe=ad9eaf3ae6) | Dec 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [faf62fd1be](https://linux-hardware.org/?probe=faf62fd1be) | Dec 16, 2023 |
| Dell          | 0FM586                      | [c895a8d51f](https://linux-hardware.org/?probe=c895a8d51f) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [646c709529](https://linux-hardware.org/?probe=646c709529) | Dec 15, 2023 |
| Gigabyte      | H410M H V3                  | [048f7ace00](https://linux-hardware.org/?probe=048f7ace00) | Dec 14, 2023 |
| Dell          | 0GDG8Y A00                  | [85f532c1c5](https://linux-hardware.org/?probe=85f532c1c5) | Dec 13, 2023 |
| Positivo      | POS-PIQ57BQ POSITIVO        | [1a2fe7c9ef](https://linux-hardware.org/?probe=1a2fe7c9ef) | Dec 13, 2023 |
| ASUSTek       | Maximus VII HERO            | [f779186ae7](https://linux-hardware.org/?probe=f779186ae7) | Dec 11, 2023 |
| HP            | 8643 SMVB                   | [d0ff744f50](https://linux-hardware.org/?probe=d0ff744f50) | Dec 10, 2023 |
| HP            | 8643 SMVB                   | [e7dbed1e89](https://linux-hardware.org/?probe=e7dbed1e89) | Dec 10, 2023 |
| Dell          | 0FM586                      | [2bf8665376](https://linux-hardware.org/?probe=2bf8665376) | Dec 10, 2023 |
| MSI           | 2AE0                        | [29c5d75dcf](https://linux-hardware.org/?probe=29c5d75dcf) | Dec 10, 2023 |
| MSI           | 2AE0                        | [63543021ec](https://linux-hardware.org/?probe=63543021ec) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [5522722e53](https://linux-hardware.org/?probe=5522722e53) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [52e1cb6958](https://linux-hardware.org/?probe=52e1cb6958) | Dec 10, 2023 |
| ASUSTek       | PRIME A320M-K               | [bc892e5d3b](https://linux-hardware.org/?probe=bc892e5d3b) | Dec 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [955f530c70](https://linux-hardware.org/?probe=955f530c70) | Dec 08, 2023 |
| MSI           | MS-7309                     | [bfc6167f25](https://linux-hardware.org/?probe=bfc6167f25) | Dec 06, 2023 |
| MSI           | MS-7309                     | [556b1ebd9a](https://linux-hardware.org/?probe=556b1ebd9a) | Dec 06, 2023 |
| Gateway       | SX2851                      | [2ec497373d](https://linux-hardware.org/?probe=2ec497373d) | Dec 05, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [3792e939db](https://linux-hardware.org/?probe=3792e939db) | Dec 05, 2023 |
| Lenovo        | SHARKBAY NOK                | [549c56d2f8](https://linux-hardware.org/?probe=549c56d2f8) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [9714fadd61](https://linux-hardware.org/?probe=9714fadd61) | Dec 04, 2023 |
| ASUSTek       | PRIME B450M-A               | [23937a8b80](https://linux-hardware.org/?probe=23937a8b80) | Dec 04, 2023 |
| Gigabyte      | B365M DS3H                  | [0d13c9a0b6](https://linux-hardware.org/?probe=0d13c9a0b6) | Dec 04, 2023 |
| Unknown       | Unknown                     | [4800fa6c99](https://linux-hardware.org/?probe=4800fa6c99) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | [6bc5e84b91](https://linux-hardware.org/?probe=6bc5e84b91) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | [813edffc94](https://linux-hardware.org/?probe=813edffc94) | Dec 04, 2023 |
| HP            | 3031h                       | [06a9e0c346](https://linux-hardware.org/?probe=06a9e0c346) | Dec 04, 2023 |
| MSI           | 870A-G54                    | [46f9552be9](https://linux-hardware.org/?probe=46f9552be9) | Dec 03, 2023 |
| Unknown       | Unknown                     | [dca543f661](https://linux-hardware.org/?probe=dca543f661) | Dec 03, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [7a932c5570](https://linux-hardware.org/?probe=7a932c5570) | Dec 02, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [9b46bc6583](https://linux-hardware.org/?probe=9b46bc6583) | Dec 02, 2023 |
| MSI           | MPG Z590M GAMING EDGE WI... | [a8495b2209](https://linux-hardware.org/?probe=a8495b2209) | Dec 01, 2023 |
| Acer          | Extensa M2610 V:1.0         | [e4c1bd6f51](https://linux-hardware.org/?probe=e4c1bd6f51) | Nov 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | [062cd64553](https://linux-hardware.org/?probe=062cd64553) | Nov 29, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [7d6885561f](https://linux-hardware.org/?probe=7d6885561f) | Nov 28, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [e106315577](https://linux-hardware.org/?probe=e106315577) | Nov 28, 2023 |
| Acer          | Aspire TC-280               | [bfd90230bc](https://linux-hardware.org/?probe=bfd90230bc) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | [4b2fec8699](https://linux-hardware.org/?probe=4b2fec8699) | Nov 27, 2023 |
| AZW           | Green G3                    | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [e4062fc1e4](https://linux-hardware.org/?probe=e4062fc1e4) | Nov 25, 2023 |
| HP            | 82F1                        | [09c7b87413](https://linux-hardware.org/?probe=09c7b87413) | Nov 24, 2023 |
| HP            | 82F1                        | [9ed00910d4](https://linux-hardware.org/?probe=9ed00910d4) | Nov 24, 2023 |
| Gigabyte      | GA-MA74GMT-S2               | [440e7b6c7c](https://linux-hardware.org/?probe=440e7b6c7c) | Nov 23, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [c5a84018e9](https://linux-hardware.org/?probe=c5a84018e9) | Nov 23, 2023 |
| HP            | 3029h                       | [2dd2ec759b](https://linux-hardware.org/?probe=2dd2ec759b) | Nov 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | [fca11dfd70](https://linux-hardware.org/?probe=fca11dfd70) | Nov 23, 2023 |
| MSI           | Z390-A PRO                  | [1f07a66db1](https://linux-hardware.org/?probe=1f07a66db1) | Nov 22, 2023 |
| AZW           | MINI S 10                   | [47bd270ae8](https://linux-hardware.org/?probe=47bd270ae8) | Nov 21, 2023 |
| Gigabyte      | H77N-WIFI                   | [6e0d000498](https://linux-hardware.org/?probe=6e0d000498) | Nov 20, 2023 |
| Gigabyte      | GA-MA78G-DS3H               | [8047aac511](https://linux-hardware.org/?probe=8047aac511) | Nov 20, 2023 |
| MSI           | Z97-G55 SLI                 | [9137a70965](https://linux-hardware.org/?probe=9137a70965) | Nov 20, 2023 |
| AZW           | MINI S 10                   | [a1358be402](https://linux-hardware.org/?probe=a1358be402) | Nov 20, 2023 |
| Intel         | H61                         | [bdab1dc80a](https://linux-hardware.org/?probe=bdab1dc80a) | Nov 19, 2023 |
| Intel         | H61                         | [4b5806ba4c](https://linux-hardware.org/?probe=4b5806ba4c) | Nov 19, 2023 |
| Acer          | Extensa M2610 V:1.0         | [7b70ac1965](https://linux-hardware.org/?probe=7b70ac1965) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [cb10d99771](https://linux-hardware.org/?probe=cb10d99771) | Nov 18, 2023 |
| Lenovo        | ThinkCentre M90p 5536Y1K    | [6bdc4cb524](https://linux-hardware.org/?probe=6bdc4cb524) | Nov 18, 2023 |
| Lenovo        | SHARKBAY NOK                | [d087235304](https://linux-hardware.org/?probe=d087235304) | Nov 17, 2023 |
| ECS           | H61H2-M2                    | [df572cd989](https://linux-hardware.org/?probe=df572cd989) | Nov 15, 2023 |
| JHZD          | BQM5                        | [cab813ae6e](https://linux-hardware.org/?probe=cab813ae6e) | Nov 14, 2023 |
| Gigabyte      | Z390 UD                     | [f961fee784](https://linux-hardware.org/?probe=f961fee784) | Nov 14, 2023 |
| Dell          | 0RW199                      | [e3b364ccd6](https://linux-hardware.org/?probe=e3b364ccd6) | Nov 13, 2023 |
| Intel         | H61                         | [cbefae3544](https://linux-hardware.org/?probe=cbefae3544) | Nov 13, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [8bcc86ef17](https://linux-hardware.org/?probe=8bcc86ef17) | Nov 12, 2023 |
| HP            | ProLiant ML350e Gen8 v2     | [f5de128dd1](https://linux-hardware.org/?probe=f5de128dd1) | Nov 12, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [d46548a5e6](https://linux-hardware.org/?probe=d46548a5e6) | Nov 12, 2023 |
| Dell          | 0HN7XN A01                  | [cd4230cf5b](https://linux-hardware.org/?probe=cd4230cf5b) | Nov 12, 2023 |
| Intel         | H61                         | [c65f2e03f6](https://linux-hardware.org/?probe=c65f2e03f6) | Nov 11, 2023 |
| Gigabyte      | H510M H                     | [08c8ac6e4d](https://linux-hardware.org/?probe=08c8ac6e4d) | Nov 09, 2023 |
| Gigabyte      | H510M H                     | [c0e0567705](https://linux-hardware.org/?probe=c0e0567705) | Nov 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [97e4b3093b](https://linux-hardware.org/?probe=97e4b3093b) | Nov 09, 2023 |
| Dell          | 0RW199                      | [11e414d343](https://linux-hardware.org/?probe=11e414d343) | Nov 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b48cc5df9c](https://linux-hardware.org/?probe=b48cc5df9c) | Nov 08, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [abb549b943](https://linux-hardware.org/?probe=abb549b943) | Nov 07, 2023 |
| Dell          | 0KWVT8 A03                  | [864f50cabf](https://linux-hardware.org/?probe=864f50cabf) | Nov 07, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [4ef314d383](https://linux-hardware.org/?probe=4ef314d383) | Nov 06, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [6c8bb1840e](https://linux-hardware.org/?probe=6c8bb1840e) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| HP            | 1497                        | [734abf0595](https://linux-hardware.org/?probe=734abf0595) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [9d8a12d929](https://linux-hardware.org/?probe=9d8a12d929) | Nov 05, 2023 |
| Gigabyte      | M5NM1AI-GB                  | [99e2275a93](https://linux-hardware.org/?probe=99e2275a93) | Nov 05, 2023 |
| Unknown       | Unknown                     | [dbd2e07499](https://linux-hardware.org/?probe=dbd2e07499) | Nov 05, 2023 |
| Unknown       | Unknown                     | [e98e6bb977](https://linux-hardware.org/?probe=e98e6bb977) | Nov 05, 2023 |
| Toshiba       | STI 001359                  | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | [bc8414b164](https://linux-hardware.org/?probe=bc8414b164) | Nov 01, 2023 |
| Gigabyte      | H510M H                     | [6db0212093](https://linux-hardware.org/?probe=6db0212093) | Nov 01, 2023 |
| Lenovo        | MAHOBAY                     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| MSI           | A320M PRO-M2 V2             | [3b667e2123](https://linux-hardware.org/?probe=3b667e2123) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [3ea2a80843](https://linux-hardware.org/?probe=3ea2a80843) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [52c3eeea68](https://linux-hardware.org/?probe=52c3eeea68) | Oct 31, 2023 |
| HP            | 21F5 0A                     | [097ce56daf](https://linux-hardware.org/?probe=097ce56daf) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| HP            | 1998                        | [2182b05a45](https://linux-hardware.org/?probe=2182b05a45) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [28f261fb9a](https://linux-hardware.org/?probe=28f261fb9a) | Oct 29, 2023 |
| MSI           | Z370M MORTAR                | [0af3708cd3](https://linux-hardware.org/?probe=0af3708cd3) | Oct 29, 2023 |
| HP            | 18E4                        | [b192ce4f35](https://linux-hardware.org/?probe=b192ce4f35) | Oct 28, 2023 |
| Dell          | 06X1TJ A00                  | [c2bc73c67b](https://linux-hardware.org/?probe=c2bc73c67b) | Oct 28, 2023 |
| ASUSTek       | P8B75-M                     | [b9830b7f02](https://linux-hardware.org/?probe=b9830b7f02) | Oct 28, 2023 |
| MSI           | Boston                      | [66f7505c8b](https://linux-hardware.org/?probe=66f7505c8b) | Oct 27, 2023 |
| HP            | 2215                        | [01fd79c4fe](https://linux-hardware.org/?probe=01fd79c4fe) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [463b5f73b5](https://linux-hardware.org/?probe=463b5f73b5) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [67021475e9](https://linux-hardware.org/?probe=67021475e9) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | [ec0dcdaa76](https://linux-hardware.org/?probe=ec0dcdaa76) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | [4f4d354524](https://linux-hardware.org/?probe=4f4d354524) | Oct 26, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [ca4ce5575c](https://linux-hardware.org/?probe=ca4ce5575c) | Oct 26, 2023 |
| LORD ELECT... | Guso G4x + ICH7 Series M... | [c6f81cf996](https://linux-hardware.org/?probe=c6f81cf996) | Oct 25, 2023 |
| ASUSTek       | P8Z77-V LX                  | [6f9c14dc54](https://linux-hardware.org/?probe=6f9c14dc54) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| Gigabyte      | B85M-D3V Plus               | [845b1f10ef](https://linux-hardware.org/?probe=845b1f10ef) | Oct 24, 2023 |
| Dell          | 0RCPW3 A03                  | [a461b9f3e7](https://linux-hardware.org/?probe=a461b9f3e7) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | [905555c7d5](https://linux-hardware.org/?probe=905555c7d5) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | [5f6d67d67e](https://linux-hardware.org/?probe=5f6d67d67e) | Oct 23, 2023 |
| ASRock        | AB350 Pro4                  | [961b658ac5](https://linux-hardware.org/?probe=961b658ac5) | Oct 23, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | [ff9e1d6c16](https://linux-hardware.org/?probe=ff9e1d6c16) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | [9999b4b89a](https://linux-hardware.org/?probe=9999b4b89a) | Oct 22, 2023 |
| ASUSTek       | SABERTOOTH P67              | [5536078e9f](https://linux-hardware.org/?probe=5536078e9f) | Oct 21, 2023 |
| ASRock        | B450 Pro4                   | [d8b8f7bafe](https://linux-hardware.org/?probe=d8b8f7bafe) | Oct 20, 2023 |
| Lenovo        | SHARKBAY NOK                | [cb8d8311e7](https://linux-hardware.org/?probe=cb8d8311e7) | Oct 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [af96c09a64](https://linux-hardware.org/?probe=af96c09a64) | Oct 19, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [77079711d3](https://linux-hardware.org/?probe=77079711d3) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7fed113f9b](https://linux-hardware.org/?probe=7fed113f9b) | Oct 19, 2023 |
| EPSON DIRE... | AT992E                      | [bdc9d825d8](https://linux-hardware.org/?probe=bdc9d825d8) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | [ec5284109e](https://linux-hardware.org/?probe=ec5284109e) | Oct 18, 2023 |
| Unknown       | Unknown                     | [03cf657f5a](https://linux-hardware.org/?probe=03cf657f5a) | Oct 17, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [16a117accb](https://linux-hardware.org/?probe=16a117accb) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | [d43a466e59](https://linux-hardware.org/?probe=d43a466e59) | Oct 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [f4e7334b7e](https://linux-hardware.org/?probe=f4e7334b7e) | Oct 14, 2023 |
| ASUSTek       | P7H55-M LX                  | [17d1931208](https://linux-hardware.org/?probe=17d1931208) | Oct 13, 2023 |
| MSI           | B85M-E45                    | [6ad9d3ff3c](https://linux-hardware.org/?probe=6ad9d3ff3c) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [ffd832c09d](https://linux-hardware.org/?probe=ffd832c09d) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [c70591ee60](https://linux-hardware.org/?probe=c70591ee60) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | [cc50dc0894](https://linux-hardware.org/?probe=cc50dc0894) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | [754748eac6](https://linux-hardware.org/?probe=754748eac6) | Oct 11, 2023 |
| Dell          | 0XHGV1 A00                  | [adda7a23c2](https://linux-hardware.org/?probe=adda7a23c2) | Oct 11, 2023 |
| AMI           | Intel                       | [1615dc16ba](https://linux-hardware.org/?probe=1615dc16ba) | Oct 10, 2023 |
| Lenovo        | Tiger Hill                  | [cdd9f65bf5](https://linux-hardware.org/?probe=cdd9f65bf5) | Oct 10, 2023 |
| Gigabyte      | H55M-USB3                   | [c4ae24b408](https://linux-hardware.org/?probe=c4ae24b408) | Oct 10, 2023 |
| Unknown       | Unknown                     | [1eeecb8823](https://linux-hardware.org/?probe=1eeecb8823) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [067260a51f](https://linux-hardware.org/?probe=067260a51f) | Oct 08, 2023 |
| Shuttle       | FS110                       | [cd7c40ed57](https://linux-hardware.org/?probe=cd7c40ed57) | Oct 08, 2023 |
| MSI           | G41M-P33 Combo              | [b82e5d0718](https://linux-hardware.org/?probe=b82e5d0718) | Oct 07, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [f347154767](https://linux-hardware.org/?probe=f347154767) | Oct 07, 2023 |
| Pegatron      | EVANS                       | [f798f24c90](https://linux-hardware.org/?probe=f798f24c90) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | [299eee42c7](https://linux-hardware.org/?probe=299eee42c7) | Oct 07, 2023 |
| Intel         | X99                         | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| Gigabyte      | H510M H                     | [9be367f445](https://linux-hardware.org/?probe=9be367f445) | Oct 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [ff815f228b](https://linux-hardware.org/?probe=ff815f228b) | Oct 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [a6668a2378](https://linux-hardware.org/?probe=a6668a2378) | Oct 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [de22cbed3e](https://linux-hardware.org/?probe=de22cbed3e) | Oct 04, 2023 |
| Dell          | 0RW199                      | [f829184aa0](https://linux-hardware.org/?probe=f829184aa0) | Oct 04, 2023 |
| Lenovo        | Tiger Hill                  | [4a3ef3e12f](https://linux-hardware.org/?probe=4a3ef3e12f) | Oct 03, 2023 |
| Pegatron      | EVANS                       | [3f2a4fe53e](https://linux-hardware.org/?probe=3f2a4fe53e) | Oct 03, 2023 |
| Gigabyte      | Z270-HD3-CF                 | [c23994e74a](https://linux-hardware.org/?probe=c23994e74a) | Oct 02, 2023 |
| MSI           | B85M-E45                    | [12fa4b4da3](https://linux-hardware.org/?probe=12fa4b4da3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | [2c6f35e1d3](https://linux-hardware.org/?probe=2c6f35e1d3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | [ded620f59b](https://linux-hardware.org/?probe=ded620f59b) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [5698c85faa](https://linux-hardware.org/?probe=5698c85faa) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [056bfb8474](https://linux-hardware.org/?probe=056bfb8474) | Oct 01, 2023 |
| Intel         | X79M-S                      | [dfa1322112](https://linux-hardware.org/?probe=dfa1322112) | Oct 01, 2023 |
| MSI           | B75MA-E33                   | [8d558a64e8](https://linux-hardware.org/?probe=8d558a64e8) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [e0cdb74f25](https://linux-hardware.org/?probe=e0cdb74f25) | Oct 01, 2023 |
| Acer          | Predator G3610              | [cddfa514ba](https://linux-hardware.org/?probe=cddfa514ba) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| MP            | MS-7848                     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| Gigabyte      | 970A-DS3P                   | [145f7eccd3](https://linux-hardware.org/?probe=145f7eccd3) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| HP            | 2B35                        | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| MSI           | A320M-A PRO MAX             | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Dell          | 0NW6H5 A00                  | [e7e87a1269](https://linux-hardware.org/?probe=e7e87a1269) | Sep 26, 2023 |
| Dell          | 0Y5DDC A00                  | [29feb62e32](https://linux-hardware.org/?probe=29feb62e32) | Sep 25, 2023 |
| Dell          | 0D28YY A01                  | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Dell          | 0HN7XN A01                  | [fd3ce44501](https://linux-hardware.org/?probe=fd3ce44501) | Sep 23, 2023 |
| Unknown       | Unknown                     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| AZW           | MINI S 10                   | [e393d95960](https://linux-hardware.org/?probe=e393d95960) | Sep 21, 2023 |
| Gigabyte      | GA-870A-UD3                 | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Dell          | 0F3KHR A00                  | [dd7f2cf2b2](https://linux-hardware.org/?probe=dd7f2cf2b2) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | [fcdaf47870](https://linux-hardware.org/?probe=fcdaf47870) | Sep 20, 2023 |
| Unknown       | Unknown                     | [e4dc880c6f](https://linux-hardware.org/?probe=e4dc880c6f) | Sep 20, 2023 |
| Dell          | 0RW199                      | [2857c6ada1](https://linux-hardware.org/?probe=2857c6ada1) | Sep 20, 2023 |
| Gigabyte      | Z790 UD AC                  | [83af285806](https://linux-hardware.org/?probe=83af285806) | Sep 20, 2023 |
| Biostar       | H61MLC                      | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| ASRock        | AB350 Pro4                  | [f45c7732e3](https://linux-hardware.org/?probe=f45c7732e3) | Sep 19, 2023 |
| AZW           | GTR V21                     | [5066e153f8](https://linux-hardware.org/?probe=5066e153f8) | Sep 19, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [202375fbb7](https://linux-hardware.org/?probe=202375fbb7) | Sep 18, 2023 |
| HP            | 3047h                       | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [9e7069cdc3](https://linux-hardware.org/?probe=9e7069cdc3) | Sep 17, 2023 |
| Dell          | 0C27VV A02                  | [08ed0347db](https://linux-hardware.org/?probe=08ed0347db) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [d4d891ca35](https://linux-hardware.org/?probe=d4d891ca35) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | [b42ad40603](https://linux-hardware.org/?probe=b42ad40603) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | [3a230dc10f](https://linux-hardware.org/?probe=3a230dc10f) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| MSI           | B550-A PRO                  | [83cb90361c](https://linux-hardware.org/?probe=83cb90361c) | Sep 14, 2023 |
| MSI           | Z170A-G45 GAMING            | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [3cba209625](https://linux-hardware.org/?probe=3cba209625) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [4dcd4e8234](https://linux-hardware.org/?probe=4dcd4e8234) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [cbfa4c2641](https://linux-hardware.org/?probe=cbfa4c2641) | Sep 13, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [b94c2a0420](https://linux-hardware.org/?probe=b94c2a0420) | Sep 13, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [e4f73d159c](https://linux-hardware.org/?probe=e4f73d159c) | Sep 12, 2023 |
| Gigabyte      | B85M-HD3                    | [8ddbf6665f](https://linux-hardware.org/?probe=8ddbf6665f) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [9fc04871b0](https://linux-hardware.org/?probe=9fc04871b0) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [a80cffbabe](https://linux-hardware.org/?probe=a80cffbabe) | Sep 11, 2023 |
| Dell          | 0HY9JP A02                  | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [c57a3a012d](https://linux-hardware.org/?probe=c57a3a012d) | Sep 11, 2023 |
| ASUSTek       | PRIME H370-A                | [c757d0e2c3](https://linux-hardware.org/?probe=c757d0e2c3) | Sep 11, 2023 |
| ASUSTek       | CG8270                      | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | [6f66e35ec3](https://linux-hardware.org/?probe=6f66e35ec3) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | [9306917366](https://linux-hardware.org/?probe=9306917366) | Sep 09, 2023 |
| HP            | 8299                        | [df4048bcc4](https://linux-hardware.org/?probe=df4048bcc4) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Dell          | 02YYK5 A01                  | [6bb77310bf](https://linux-hardware.org/?probe=6bb77310bf) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | [53bfbec77e](https://linux-hardware.org/?probe=53bfbec77e) | Sep 06, 2023 |
| Gigabyte      | 970A-DS3P                   | [3227a8a6bc](https://linux-hardware.org/?probe=3227a8a6bc) | Sep 06, 2023 |
| Alienware     | 0446JC A01                  | [d0c3088707](https://linux-hardware.org/?probe=d0c3088707) | Sep 06, 2023 |
| HP            | 0B54h D                     | [6fc93ef4ee](https://linux-hardware.org/?probe=6fc93ef4ee) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [f8ec276ea3](https://linux-hardware.org/?probe=f8ec276ea3) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | [788841792b](https://linux-hardware.org/?probe=788841792b) | Sep 04, 2023 |
| Inventec      | Z CLASS A02                 | [7f0254a775](https://linux-hardware.org/?probe=7f0254a775) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Dell          | 0D28YY A01                  | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Gigabyte      | Z97X-UD5H                   | [2c9b64c445](https://linux-hardware.org/?probe=2c9b64c445) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [eee58fd067](https://linux-hardware.org/?probe=eee58fd067) | Sep 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Intel         | X79M-S                      | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [be8b002a45](https://linux-hardware.org/?probe=be8b002a45) | Aug 31, 2023 |
| Intel         | DB85FL AAG89861-201         | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Lenovo        | SDK0E50510 WIN              | [d963970016](https://linux-hardware.org/?probe=d963970016) | Aug 30, 2023 |
| HP            | 8054                        | [f73271d96e](https://linux-hardware.org/?probe=f73271d96e) | Aug 30, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3fb03adafb](https://linux-hardware.org/?probe=3fb03adafb) | Aug 29, 2023 |
| Dell          | 0GY6Y8 A02                  | [fffbca3973](https://linux-hardware.org/?probe=fffbca3973) | Aug 28, 2023 |
| Intel         | H61                         | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [929efec703](https://linux-hardware.org/?probe=929efec703) | Aug 27, 2023 |
| eMachines     | EL1352                      | [5f9258beb2](https://linux-hardware.org/?probe=5f9258beb2) | Aug 27, 2023 |
| GuoGuang      | IC2M1028N                   | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| MSI           | Z87 MPOWER MAX              | [42d3a714ac](https://linux-hardware.org/?probe=42d3a714ac) | Aug 24, 2023 |
| AZW           | MINI S                      | [7712e558c5](https://linux-hardware.org/?probe=7712e558c5) | Aug 24, 2023 |
| AZW           | MINI S                      | [6296a4f71d](https://linux-hardware.org/?probe=6296a4f71d) | Aug 24, 2023 |
| HP            | 8299                        | [aa27bed4f1](https://linux-hardware.org/?probe=aa27bed4f1) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| Unknown       | Unknown                     | [9b52370ec1](https://linux-hardware.org/?probe=9b52370ec1) | Aug 22, 2023 |
| Unknown       | Unknown                     | [51e91dd03e](https://linux-hardware.org/?probe=51e91dd03e) | Aug 22, 2023 |
| Dell          | 0GY6Y8 A02                  | [409855b61b](https://linux-hardware.org/?probe=409855b61b) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [2ac06099d8](https://linux-hardware.org/?probe=2ac06099d8) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| ASUSTek       | P5L-MX                      | [f06dbc1b8c](https://linux-hardware.org/?probe=f06dbc1b8c) | Aug 19, 2023 |
| HP            | 3047h                       | [91d9eaa1de](https://linux-hardware.org/?probe=91d9eaa1de) | Aug 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [d109b04177](https://linux-hardware.org/?probe=d109b04177) | Aug 19, 2023 |
| HP            | 3047h                       | [a4aa888c24](https://linux-hardware.org/?probe=a4aa888c24) | Aug 18, 2023 |
| HP            | 3032h                       | [34a300f540](https://linux-hardware.org/?probe=34a300f540) | Aug 17, 2023 |
| Intel         | X79M-S                      | [d79895d82c](https://linux-hardware.org/?probe=d79895d82c) | Aug 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [7c1a42d442](https://linux-hardware.org/?probe=7c1a42d442) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Dell          | 0M6C7G A00                  | [50731e7c54](https://linux-hardware.org/?probe=50731e7c54) | Aug 16, 2023 |
| ASRock        | 970 Pro3 R2.0               | [50b5957370](https://linux-hardware.org/?probe=50b5957370) | Aug 16, 2023 |
| Biostar       | H410MH                      | [abe98ae584](https://linux-hardware.org/?probe=abe98ae584) | Aug 15, 2023 |
| Gigabyte      | H110M-H-CF                  | [bb4bf558dd](https://linux-hardware.org/?probe=bb4bf558dd) | Aug 15, 2023 |
| Dell          | 02YRK5 A02                  | [e79cdd0ba3](https://linux-hardware.org/?probe=e79cdd0ba3) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | [dea6e2f8b8](https://linux-hardware.org/?probe=dea6e2f8b8) | Aug 13, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [7e47b7128b](https://linux-hardware.org/?probe=7e47b7128b) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | [1034423357](https://linux-hardware.org/?probe=1034423357) | Aug 13, 2023 |
| Biostar       | A770 A2+                    | [ff8bec8b75](https://linux-hardware.org/?probe=ff8bec8b75) | Aug 12, 2023 |
| MSI           | 2AE0                        | [b8a2a0eb5c](https://linux-hardware.org/?probe=b8a2a0eb5c) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [d35bac0620](https://linux-hardware.org/?probe=d35bac0620) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [fb7d0009fd](https://linux-hardware.org/?probe=fb7d0009fd) | Aug 12, 2023 |
| HP            | 3032h                       | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Intel         | DZ68BC AAG30742-401         | [9bf37df045](https://linux-hardware.org/?probe=9bf37df045) | Aug 10, 2023 |
| Dell          | 0WMJ54 A01                  | [6e9ca3c833](https://linux-hardware.org/?probe=6e9ca3c833) | Aug 09, 2023 |
| HP            | 3032h                       | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Intel         | X79M-S                      | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Gigabyte      | B450 AORUS M                | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| Pegatron      | IPMMB-MQ1                   | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [1af709c14e](https://linux-hardware.org/?probe=1af709c14e) | Aug 05, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3bc330734d](https://linux-hardware.org/?probe=3bc330734d) | Aug 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [5d998a099e](https://linux-hardware.org/?probe=5d998a099e) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [e57d71e056](https://linux-hardware.org/?probe=e57d71e056) | Aug 05, 2023 |
| Unknown       | Unknown                     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| ASRock        | N68-VS3 UCC                 | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| Gigabyte      | B550M DS3H AC               | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Intel         | X79M-S                      | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| HP            | 89B5 A                      | [cb6f36f32c](https://linux-hardware.org/?probe=cb6f36f32c) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Unknown       | Unknown                     | [731a8b0e31](https://linux-hardware.org/?probe=731a8b0e31) | Aug 02, 2023 |
| ASUSTek       | P8H61-M LX                  | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| HP            | 1496                        | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| ASUSTek       | M4N68T-M LE                 | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| Gigabyte      | M68MT-S2                    | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| MSI           | B75MA-E33                   | [310207e0fd](https://linux-hardware.org/?probe=310207e0fd) | Jul 29, 2023 |
| Pegatron      | BOWIE                       | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| HP            | 3397                        | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [e7fdf45ff0](https://linux-hardware.org/?probe=e7fdf45ff0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [2f12124bed](https://linux-hardware.org/?probe=2f12124bed) | Jul 27, 2023 |
| MP            | MS-7848                     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Acer          | Elena                       | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| ASUSTek       | B250 MINING EXPERT          | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| Dell          | 088DT1 A01                  | [1355a4f2f4](https://linux-hardware.org/?probe=1355a4f2f4) | Jul 25, 2023 |
| HP            | 8350                        | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| Dell          | 0MN1TX A04                  | [4ff31f4185](https://linux-hardware.org/?probe=4ff31f4185) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| ASUSTek       | F1A55-M LX                  | [87b85c2e28](https://linux-hardware.org/?probe=87b85c2e28) | Jul 22, 2023 |
| ASRock        | B85M                        | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| HP            | 3048h                       | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| HP            | 3047h                       | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [9afd0f1d0f](https://linux-hardware.org/?probe=9afd0f1d0f) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [35c4e6ad97](https://linux-hardware.org/?probe=35c4e6ad97) | Jul 20, 2023 |
| HP            | 8767 A                      | [d5275f1025](https://linux-hardware.org/?probe=d5275f1025) | Jul 20, 2023 |
| Dell          | 0F5C5X A00                  | [3832c8f626](https://linux-hardware.org/?probe=3832c8f626) | Jul 20, 2023 |
| Dell          | 0C27VV A02                  | [da1c963814](https://linux-hardware.org/?probe=da1c963814) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | [02008985ce](https://linux-hardware.org/?probe=02008985ce) | Jul 19, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [57b17e7ae1](https://linux-hardware.org/?probe=57b17e7ae1) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| Dell          | 0FDY5C A00                  | [35399aae18](https://linux-hardware.org/?probe=35399aae18) | Jul 14, 2023 |
| Dell          | 0D441T A03                  | [622890c12a](https://linux-hardware.org/?probe=622890c12a) | Jul 14, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [b690698c10](https://linux-hardware.org/?probe=b690698c10) | Jul 12, 2023 |
| HP            | 8299                        | [763cebf303](https://linux-hardware.org/?probe=763cebf303) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| Dell          | 09WH54 A00                  | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| ASRock        | B460M Pro4                  | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [213c80bbee](https://linux-hardware.org/?probe=213c80bbee) | Jul 09, 2023 |
| ASUSTek       | PRIME B350M-A               | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| Dell          | 0HN7XN A01                  | [24a4044173](https://linux-hardware.org/?probe=24a4044173) | Jul 06, 2023 |
| Gigabyte      | B75M-D3H                    | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| ASRock        | FP6D4-P1                    | [42b5bdcdd7](https://linux-hardware.org/?probe=42b5bdcdd7) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| Intel         | H55                         | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| HP            | 21F5 0A                     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [452fe27c46](https://linux-hardware.org/?probe=452fe27c46) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [168d5b0b7b](https://linux-hardware.org/?probe=168d5b0b7b) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| Dell          | 0GY6Y8 A02                  | [729dbec695](https://linux-hardware.org/?probe=729dbec695) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| MSI           | PRO Z690-A WIFI             | [2bc4b36c94](https://linux-hardware.org/?probe=2bc4b36c94) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [c787bf91c3](https://linux-hardware.org/?probe=c787bf91c3) | Jul 02, 2023 |
| Win Elemen... | M9                          | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [a4e29f77e5](https://linux-hardware.org/?probe=a4e29f77e5) | Jul 01, 2023 |
| MSI           | H61M-P31                    | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Gigabyte      | G31M-ES2L                   | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| ASUSTek       | P5B                         | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Dell          | 0G9322                      | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Intel         | D34010WYK H14771-304        | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| AZW           | GTR V02                     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| Pegatron      | BOWIE                       | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| ASRock        | B85M                        | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| ASUSTek       | P5B                         | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| MP            | MS-7848                     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Nvidia        | MCP79                       | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| HP            | 8350                        | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Nvidia        | MCP79                       | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| ASUSTek       | B75M-A                      | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| Dell          | 0G9322                      | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| MSI           | B450 TOMAHAWK               | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Acer          | Predator G3-605             | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| Dell          | 0G9322                      | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| HP            | 18E5                        | [23e2edb1fe](https://linux-hardware.org/?probe=23e2edb1fe) | May 26, 2023 |
| Dell          | 0K095G A02                  | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| HP            | 21D0                        | [8e52c2613c](https://linux-hardware.org/?probe=8e52c2613c) | May 26, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [61dc4c5620](https://linux-hardware.org/?probe=61dc4c5620) | May 25, 2023 |
| ECS           | H510H6-M2                   | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| Vorke         | V1 Plus                     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| ECS           | H510H6-M2                   | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| HP            | 8906 SMVB                   | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| Pegatron      | 2AC2A                       | [f9e504a430](https://linux-hardware.org/?probe=f9e504a430) | May 24, 2023 |
| HP            | 21EF                        | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | H81M-E34                    | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| HP            | 21EF                        | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| ASRock        | H77M                        | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| HP            | 18E5                        | [d1bc34770d](https://linux-hardware.org/?probe=d1bc34770d) | May 22, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Dell          | 02N3WF A01                  | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| Gigabyte      | X570 GAMING X               | [8a6ad6c590](https://linux-hardware.org/?probe=8a6ad6c590) | May 19, 2023 |
| Dell          | 0GDG8Y A00                  | [514fe06c9e](https://linux-hardware.org/?probe=514fe06c9e) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| Gigabyte      | H81M-DS2                    | [754dc9d1fc](https://linux-hardware.org/?probe=754dc9d1fc) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Acer          | Revo 70                     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| HP            | 2B02                        | [a6bf09d51c](https://linux-hardware.org/?probe=a6bf09d51c) | May 17, 2023 |
| Pegatron      | Benicia                     | [e6ee1c66f6](https://linux-hardware.org/?probe=e6ee1c66f6) | May 17, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d3c3cc9f96](https://linux-hardware.org/?probe=d3c3cc9f96) | May 15, 2023 |
| Intel         | Tiger Hill                  | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [dd8c6c3811](https://linux-hardware.org/?probe=dd8c6c3811) | May 15, 2023 |
| HP            | 18E5                        | [7d5ceb9f5d](https://linux-hardware.org/?probe=7d5ceb9f5d) | May 15, 2023 |
| Gigabyte      | GA-970A-UD3                 | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| ASUSTek       | K8N-DRE                     | [395dc0cfb3](https://linux-hardware.org/?probe=395dc0cfb3) | May 13, 2023 |
| ASUSTek       | K8N-DRE                     | [f55a0c735f](https://linux-hardware.org/?probe=f55a0c735f) | May 13, 2023 |
| Vorke         | V1 Plus                     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e844f3a6fe](https://linux-hardware.org/?probe=e844f3a6fe) | May 13, 2023 |
| Acer          | Predator G3-605             | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| Acer          | Predator G3-605             | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | [080f1c13d8](https://linux-hardware.org/?probe=080f1c13d8) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e2c57c80fc](https://linux-hardware.org/?probe=e2c57c80fc) | May 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d041d35517](https://linux-hardware.org/?probe=d041d35517) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3ab5dcb5d](https://linux-hardware.org/?probe=d3ab5dcb5d) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [22778449cc](https://linux-hardware.org/?probe=22778449cc) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [ffd84ff48e](https://linux-hardware.org/?probe=ffd84ff48e) | May 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [abf6d2bf1d](https://linux-hardware.org/?probe=abf6d2bf1d) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d45b33c736](https://linux-hardware.org/?probe=d45b33c736) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| HP            | 339A                        | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| ASRockRack    | D1521D4I2                   | [136a9303c0](https://linux-hardware.org/?probe=136a9303c0) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| MSI           | X570-A PRO                  | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| MSI           | X570-A PRO                  | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d571b75547](https://linux-hardware.org/?probe=d571b75547) | May 05, 2023 |
| ASRock        | B550M-HDV                   | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Unknown       | Unknown                     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| ASRock        | H81M-HDS                    | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Dell          | 09WH54 A00                  | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| Intel         | H55                         | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| ASRock        | H61M-DGS                    | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| Unknown       | Unknown                     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Unknown       | Unknown                     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| eMachines     | MCP61PM-GM                  | [ff00693839](https://linux-hardware.org/?probe=ff00693839) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| ASUSTek       | P5Q                         | [57e3cfa7dc](https://linux-hardware.org/?probe=57e3cfa7dc) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| Gigabyte      | B650M DS3H                  | [3d07651a47](https://linux-hardware.org/?probe=3d07651a47) | Apr 24, 2023 |
| Dell          | 03NVJ6 A01                  | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Unknown       | G41                         | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [25ee911879](https://linux-hardware.org/?probe=25ee911879) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [468824c4d9](https://linux-hardware.org/?probe=468824c4d9) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| Dell          | 0F373D A00                  | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| Gigabyte      | B650M DS3H                  | [de196a2cfa](https://linux-hardware.org/?probe=de196a2cfa) | Apr 21, 2023 |
| ASUSTek       | H110M-R                     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| HP            | 2ADE                        | [1a3d108a58](https://linux-hardware.org/?probe=1a3d108a58) | Apr 20, 2023 |
| HP            | 8054                        | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Dell          | 0WMJ54 A01                  | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| ASL           | BayTrail JHS773             | [3a5977ad04](https://linux-hardware.org/?probe=3a5977ad04) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [119560d8db](https://linux-hardware.org/?probe=119560d8db) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| MSI           | MEG X570 UNIFY              | [b2311e7cac](https://linux-hardware.org/?probe=b2311e7cac) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| ASRock        | H61M-DGS                    | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| Intel         | H61                         | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| MSI           | B75MA-E33                   | [d50de3a52c](https://linux-hardware.org/?probe=d50de3a52c) | Apr 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Biostar       | TZ75B                       | [c6720e2db2](https://linux-hardware.org/?probe=c6720e2db2) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [e9c2f8d5ba](https://linux-hardware.org/?probe=e9c2f8d5ba) | Apr 14, 2023 |
| Intel         | H61                         | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Gigabyte      | M68MT-S2                    | [ac4059b403](https://linux-hardware.org/?probe=ac4059b403) | Apr 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | [6f7e9a6bb2](https://linux-hardware.org/?probe=6f7e9a6bb2) | Apr 13, 2023 |
| ASUSTek       | B85M-G                      | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [82a946e356](https://linux-hardware.org/?probe=82a946e356) | Apr 12, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1627e0654a](https://linux-hardware.org/?probe=1627e0654a) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | [57aa7d103d](https://linux-hardware.org/?probe=57aa7d103d) | Apr 11, 2023 |
| ASUSTek       | P5K                         | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| MSI           | B75MA-E33                   | [27e5e2df0d](https://linux-hardware.org/?probe=27e5e2df0d) | Apr 06, 2023 |
| Dell          | 0GY6Y8 A01                  | [ecba971f16](https://linux-hardware.org/?probe=ecba971f16) | Apr 06, 2023 |
| ASUSTek       | H87-PRO                     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [68d14e873f](https://linux-hardware.org/?probe=68d14e873f) | Apr 05, 2023 |
| eMachines     | MCP61PM-GM                  | [dc35ec4564](https://linux-hardware.org/?probe=dc35ec4564) | Apr 04, 2023 |
| Gigabyte      | H410M S2 V3                 | [fdff0f112e](https://linux-hardware.org/?probe=fdff0f112e) | Apr 04, 2023 |
| Medion        | MS-7707                     | [c490d9dc74](https://linux-hardware.org/?probe=c490d9dc74) | Apr 04, 2023 |
| eMachines     | MCP61PM-GM                  | [59f9325843](https://linux-hardware.org/?probe=59f9325843) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| Acer          | Veriton X4610G              | [49b3c45306](https://linux-hardware.org/?probe=49b3c45306) | Apr 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ea4626fdcc](https://linux-hardware.org/?probe=ea4626fdcc) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [118effffda](https://linux-hardware.org/?probe=118effffda) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| Pegatron      | 2ACF                        | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| Acer          | Predator G3-605             | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | 0K240Y A02                  | [ca6aacf14e](https://linux-hardware.org/?probe=ca6aacf14e) | Mar 31, 2023 |
| Dell          | 09M8Y8 A01                  | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | Benicia                     | [7332efabad](https://linux-hardware.org/?probe=7332efabad) | Mar 30, 2023 |
| HOUTER        | ORO-PC                      | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Gigabyte      | H310M H x.x                 | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| MSI           | B560M-A PRO                 | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [c97dbb0917](https://linux-hardware.org/?probe=c97dbb0917) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| AZW           | MINI S                      | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [e859e77bc7](https://linux-hardware.org/?probe=e859e77bc7) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [ce7e17cb45](https://linux-hardware.org/?probe=ce7e17cb45) | Mar 24, 2023 |
| ASRock        | X570 Steel Legend           | [05d4059f59](https://linux-hardware.org/?probe=05d4059f59) | Mar 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| Intel         | G41                         | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d0b0015eb2](https://linux-hardware.org/?probe=d0b0015eb2) | Mar 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9409e4e133](https://linux-hardware.org/?probe=9409e4e133) | Mar 20, 2023 |
| Acer          | Revo RL80                   | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| MSI           | B75MA-E33                   | [cddf0b016f](https://linux-hardware.org/?probe=cddf0b016f) | Mar 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [75996f8bcf](https://linux-hardware.org/?probe=75996f8bcf) | Mar 19, 2023 |
| HP            | 158A                        | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| HP            | 2B01                        | [1a096f9b36](https://linux-hardware.org/?probe=1a096f9b36) | Mar 19, 2023 |
| MSI           | B75MA-E33                   | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [5f4a932bcd](https://linux-hardware.org/?probe=5f4a932bcd) | Mar 18, 2023 |
| HP            | 83E1                        | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| Dell          | 0D28YY A01                  | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| HP            | 158A                        | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [3388dd991a](https://linux-hardware.org/?probe=3388dd991a) | Mar 15, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Gigabyte      | H55M-S2H                    | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| HP            | 83E1                        | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| Soncview      | G41D3C                      | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| Gigabyte      | H97M-D3H                    | [178af6e35b](https://linux-hardware.org/?probe=178af6e35b) | Mar 12, 2023 |
| HP            | 18E7                        | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| Dell          | 0GM819                      | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Acer          | WG43M                       | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Pegatron      | 2ACB                        | [1599d2a2ef](https://linux-hardware.org/?probe=1599d2a2ef) | Mar 09, 2023 |
| Unknown       | HX90                        | [21530c00a4](https://linux-hardware.org/?probe=21530c00a4) | Mar 09, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [8115c702cb](https://linux-hardware.org/?probe=8115c702cb) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Dell          | 0T10XW A00                  | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| Dell          | 0JC474                      | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| Apple         | Mac-F221BEC8                | [f3c06b377f](https://linux-hardware.org/?probe=f3c06b377f) | Mar 04, 2023 |
| ASUSTek       | H81M-K                      | [05507dab01](https://linux-hardware.org/?probe=05507dab01) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| Unknown       | Rev.00                      | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| HP            | 805D                        | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Google        | Buddy                       | [ac3d9aaed0](https://linux-hardware.org/?probe=ac3d9aaed0) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [6c62bbbf3b](https://linux-hardware.org/?probe=6c62bbbf3b) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [2479c3c245](https://linux-hardware.org/?probe=2479c3c245) | Feb 27, 2023 |
| HP            | 1998                        | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [a21ea9613b](https://linux-hardware.org/?probe=a21ea9613b) | Feb 26, 2023 |
| MSI           | B75MA-E33                   | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | H81M-P33                    | [1bc1cedec6](https://linux-hardware.org/?probe=1bc1cedec6) | Feb 25, 2023 |
| ASUSTek       | PRIME B560M-A               | [7357439273](https://linux-hardware.org/?probe=7357439273) | Feb 25, 2023 |
| HP            | 2AF7                        | [a8eba0b0c4](https://linux-hardware.org/?probe=a8eba0b0c4) | Feb 25, 2023 |
| HP            | 2AF7                        | [3bf3afd1d5](https://linux-hardware.org/?probe=3bf3afd1d5) | Feb 25, 2023 |
| HP            | 2129                        | [5118eb06d4](https://linux-hardware.org/?probe=5118eb06d4) | Feb 24, 2023 |
| Dell          | 0HN7XN A01                  | [f283ae7cb2](https://linux-hardware.org/?probe=f283ae7cb2) | Feb 23, 2023 |
| HP            | 2129                        | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| ASUSTek       | F2A55-M                     | [c9d150f24c](https://linux-hardware.org/?probe=c9d150f24c) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [40e2157901](https://linux-hardware.org/?probe=40e2157901) | Feb 21, 2023 |
| HP            | 1850                        | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| eMachines     | MCP61PM-GM                  | [aeafa2dbee](https://linux-hardware.org/?probe=aeafa2dbee) | Feb 19, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [be0f73193d](https://linux-hardware.org/?probe=be0f73193d) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [c784a261d4](https://linux-hardware.org/?probe=c784a261d4) | Feb 19, 2023 |
| Gigabyte      | H81M-S2H                    | [d6f4d9d8df](https://linux-hardware.org/?probe=d6f4d9d8df) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| MSI           | 760GM-P23                   | [529e0929d2](https://linux-hardware.org/?probe=529e0929d2) | Feb 17, 2023 |
| Gigabyte      | 990FXA-UD3                  | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| MSI           | Z370M MORTAR                | [5ac9c9a924](https://linux-hardware.org/?probe=5ac9c9a924) | Feb 15, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| Google        | Teemo                       | [53bf6d19ca](https://linux-hardware.org/?probe=53bf6d19ca) | Feb 14, 2023 |
| MSI           | MS-B9181                    | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Alienware     | 0N43JM A00                  | [ef1d9239ab](https://linux-hardware.org/?probe=ef1d9239ab) | Feb 12, 2023 |
| Lenovo        | ThinkServer TS140           | [59eeaafe59](https://linux-hardware.org/?probe=59eeaafe59) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Unknown       | Unknown                     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [a789235fe3](https://linux-hardware.org/?probe=a789235fe3) | Feb 11, 2023 |
| HP            | 8054                        | [55c5642509](https://linux-hardware.org/?probe=55c5642509) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [f3919f8d69](https://linux-hardware.org/?probe=f3919f8d69) | Feb 11, 2023 |
| Unknown       | Unknown                     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | 8643 SMVB                   | [5e8a88b237](https://linux-hardware.org/?probe=5e8a88b237) | Feb 11, 2023 |
| ASUSTek       | P5K                         | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| Unknown       | Unknown                     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| MSI           | GF615M-P31                  | [36dcd2e516](https://linux-hardware.org/?probe=36dcd2e516) | Feb 10, 2023 |
| Gigabyte      | X570 GAMING X               | [458744c54d](https://linux-hardware.org/?probe=458744c54d) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | [dd9b71e8d2](https://linux-hardware.org/?probe=dd9b71e8d2) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [dd76c764a1](https://linux-hardware.org/?probe=dd76c764a1) | Feb 08, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [37aec8a881](https://linux-hardware.org/?probe=37aec8a881) | Feb 08, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [e7ee51ecdd](https://linux-hardware.org/?probe=e7ee51ecdd) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | CRESCENTBAY                 | [1830edf54c](https://linux-hardware.org/?probe=1830edf54c) | Feb 07, 2023 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [96f24866e0](https://linux-hardware.org/?probe=96f24866e0) | Feb 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [0de7e3b318](https://linux-hardware.org/?probe=0de7e3b318) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| HP            | 2B47                        | [3db96ac186](https://linux-hardware.org/?probe=3db96ac186) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e5a1cf7284](https://linux-hardware.org/?probe=e5a1cf7284) | Feb 03, 2023 |
| MSI           | B85M-E45                    | [13453f924e](https://linux-hardware.org/?probe=13453f924e) | Feb 03, 2023 |
| Intel         | X58                         | [55a6a5bd82](https://linux-hardware.org/?probe=55a6a5bd82) | Feb 03, 2023 |
| HP            | 1825                        | [fd942fd3ba](https://linux-hardware.org/?probe=fd942fd3ba) | Feb 02, 2023 |
| Dell          | 0D28YY A01                  | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MSI           | H81M-P33                    | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| HP            | 1791                        | [0cb5402c68](https://linux-hardware.org/?probe=0cb5402c68) | Jan 29, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [bc4b6513bb](https://linux-hardware.org/?probe=bc4b6513bb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| HP            | 843F                        | [5e9a5d2afd](https://linux-hardware.org/?probe=5e9a5d2afd) | Jan 28, 2023 |
| MSI           | PRO H610M-G DDR4            | [ad4f37d5a4](https://linux-hardware.org/?probe=ad4f37d5a4) | Jan 28, 2023 |
| HP            | 2B47                        | [cce5f9ec07](https://linux-hardware.org/?probe=cce5f9ec07) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| ASRock        | H87 Pro4                    | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| Acer          | RS880M05                    | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| ASRock        | H61M                        | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| HP            | 89B5 A                      | [1b6e288840](https://linux-hardware.org/?probe=1b6e288840) | Jan 21, 2023 |
| HP            | 843F                        | [07f6efa703](https://linux-hardware.org/?probe=07f6efa703) | Jan 20, 2023 |
| ASUSTek       | M4A3000E                    | [650236c7cc](https://linux-hardware.org/?probe=650236c7cc) | Jan 19, 2023 |
| ASRock        | B450 Pro4                   | [8131194ea1](https://linux-hardware.org/?probe=8131194ea1) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| HP            | 843F                        | [83ca70ac2d](https://linux-hardware.org/?probe=83ca70ac2d) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | [4f8a71f0c5](https://linux-hardware.org/?probe=4f8a71f0c5) | Jan 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| HP            | 3397                        | [a58c9ac196](https://linux-hardware.org/?probe=a58c9ac196) | Jan 17, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Unknown       | Unknown                     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Unknown       | Unknown                     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
| HP            | 3397                        | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Acer          | FRS690L                     | [5b27fe10aa](https://linux-hardware.org/?probe=5b27fe10aa) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [07cedbf55a](https://linux-hardware.org/?probe=07cedbf55a) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| ASUSTek       | H87-PRO                     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| HP            | 843B                        | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| HP            | 843B                        | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| ASUSTek       | M4A88T-M                    | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| HP            | 2129                        | [4d6113e60d](https://linux-hardware.org/?probe=4d6113e60d) | Jan 08, 2023 |
| ASRock        | X670E PG Lightning          | [2b3261504f](https://linux-hardware.org/?probe=2b3261504f) | Jan 08, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 73       | 4.26%   |
| 5.11.0-38-generic | 62       | 3.62%   |
| 5.15.0-67-generic | 58       | 3.38%   |
| 5.15.0-91-generic | 56       | 3.27%   |
| 5.15.0-69-generic | 56       | 3.27%   |
| 5.15.0-46-generic | 56       | 3.27%   |
| 5.11.0-27-generic | 55       | 3.21%   |
| 5.11.0-40-generic | 50       | 2.92%   |
| 5.15.0-52-generic | 49       | 2.86%   |
| 5.13.0-39-generic | 49       | 2.86%   |
| 5.15.0-78-generic | 48       | 2.8%    |
| 5.15.0-60-generic | 46       | 2.68%   |
| 5.15.0-58-generic | 46       | 2.68%   |
| 5.11.0-41-generic | 42       | 2.45%   |
| 5.15.0-71-generic | 41       | 2.39%   |
| 5.15.0-48-generic | 41       | 2.39%   |
| 5.13.0-30-generic | 40       | 2.33%   |
| 5.13.0-40-generic | 38       | 2.22%   |
| 5.15.0-76-generic | 37       | 2.16%   |
| 5.11.0-43-generic | 36       | 2.1%    |
| 5.15.0-41-generic | 35       | 2.04%   |
| 5.11.0-37-generic | 35       | 2.04%   |
| 5.15.0-84-generic | 34       | 1.98%   |
| 5.11.0-34-generic | 32       | 1.87%   |
| 5.13.0-28-generic | 31       | 1.81%   |
| 5.15.0-88-generic | 29       | 1.69%   |
| 5.15.0-53-generic | 29       | 1.69%   |
| 5.13.0-35-generic | 28       | 1.63%   |
| 5.15.0-73-generic | 27       | 1.57%   |
| 5.13.0-27-generic | 27       | 1.57%   |
| 5.15.0-83-generic | 25       | 1.46%   |
| 5.13.0-41-generic | 25       | 1.46%   |
| 5.15.0-89-generic | 24       | 1.4%    |
| 5.15.0-72-generic | 24       | 1.4%    |
| 5.13.0-52-generic | 24       | 1.4%    |
| 5.13.0-44-generic | 21       | 1.22%   |
| 5.15.0-87-generic | 20       | 1.17%   |
| 5.15.0-79-generic | 19       | 1.11%   |
| 5.15.0-92-generic | 18       | 1.05%   |
| 5.15.0-86-generic | 18       | 1.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 848      | 55.86%  |
| 5.11.0  | 332      | 21.87%  |
| 5.13.0  | 294      | 19.37%  |
| 5.8.0   | 25       | 1.65%   |
| 5.4.0   | 2        | 0.13%   |
| 6.5.7   | 1        | 0.07%   |
| 6.3.2   | 1        | 0.07%   |
| 6.3.0   | 1        | 0.07%   |
| 6.2.7   | 1        | 0.07%   |
| 6.2.16  | 1        | 0.07%   |
| 6.1.8   | 1        | 0.07%   |
| 6.1.7   | 1        | 0.07%   |
| 6.0.9   | 1        | 0.07%   |
| 6.0.8   | 1        | 0.07%   |
| 5.19.6  | 1        | 0.07%   |
| 5.19.2  | 1        | 0.07%   |
| 5.19.12 | 1        | 0.07%   |
| 5.17.9  | 1        | 0.07%   |
| 5.17.5  | 1        | 0.07%   |
| 5.17.1  | 1        | 0.07%   |
| 5.15.13 | 1        | 0.07%   |
| 5.14.0  | 1        | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 849      | 55.97%  |
| 5.11    | 332      | 21.89%  |
| 5.13    | 294      | 19.38%  |
| 5.8     | 25       | 1.65%   |
| 5.19    | 3        | 0.2%    |
| 5.17    | 3        | 0.2%    |
| 6.3     | 2        | 0.13%   |
| 6.2     | 2        | 0.13%   |
| 6.0     | 2        | 0.13%   |
| 5.4     | 2        | 0.13%   |
| 6.5     | 1        | 0.07%   |
| 6.1     | 1        | 0.07%   |
| 5.14    | 1        | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1460     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 1251     | 85.16%  |
| XFCE       | 206      | 14.02%  |
| Unknown    | 5        | 0.34%   |
| X-Cinnamon | 2        | 0.14%   |
| KDE5       | 2        | 0.14%   |
| Cinnamon   | 2        | 0.14%   |
| MATE       | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1446     | 98.7%   |
| Wayland | 16       | 1.09%   |
| Tty     | 2        | 0.14%   |
| Unknown | 1        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1221     | 82.5%   |
| GDM3    | 111      | 7.5%    |
| GDM     | 110      | 7.43%   |
| LightDM | 37       | 2.5%    |
| TDM     | 1        | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 592      | 40.44%  |
| de_DE       | 145      | 9.9%    |
| en_GB       | 99       | 6.76%   |
| pt_BR       | 97       | 6.63%   |
| fr_FR       | 53       | 3.62%   |
| en_CA       | 45       | 3.07%   |
| it_IT       | 40       | 2.73%   |
| pl_PL       | 32       | 2.19%   |
| es_ES       | 32       | 2.19%   |
| en_IN       | 29       | 1.98%   |
| en_AU       | 28       | 1.91%   |
| nl_NL       | 27       | 1.84%   |
| ru_RU       | 18       | 1.23%   |
| es_AR       | 18       | 1.23%   |
| hu_HU       | 16       | 1.09%   |
| es_MX       | 14       | 0.96%   |
| en_ZA       | 14       | 0.96%   |
| cs_CZ       | 10       | 0.68%   |
| pt_PT       | 9        | 0.61%   |
| nl_BE       | 8        | 0.55%   |
| fr_CA       | 8        | 0.55%   |
| tr_TR       | 6        | 0.41%   |
| sv_SE       | 6        | 0.41%   |
| sk_SK       | 6        | 0.41%   |
| nb_NO       | 6        | 0.41%   |
| fi_FI       | 6        | 0.41%   |
| es_VE       | 6        | 0.41%   |
| es_CL       | 6        | 0.41%   |
| en_NZ       | 6        | 0.41%   |
| el_GR       | 6        | 0.41%   |
| ja_JP       | 5        | 0.34%   |
| da_DK       | 5        | 0.34%   |
| ar_EG       | 5        | 0.34%   |
| en_PH       | 4        | 0.27%   |
| de_CH       | 4        | 0.27%   |
| zh_CN       | 3        | 0.2%    |
| sr_RS@latin | 3        | 0.2%    |
| sl_SI       | 3        | 0.2%    |
| fr_BE       | 3        | 0.2%    |
| es_CR       | 3        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 791      | 53.63%  |
| EFI  | 684      | 46.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1354     | 92.11%  |
| Tmpfs    | 41       | 2.79%   |
| Zfs      | 29       | 1.97%   |
| Overlay  | 21       | 1.43%   |
| Btrfs    | 13       | 0.88%   |
| Xfs      | 5        | 0.34%   |
| Ext3     | 3        | 0.2%    |
| Ext2     | 3        | 0.2%    |
| Reiserfs | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1272     | 86%     |
| GPT     | 130      | 8.79%   |
| MBR     | 77       | 5.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1415     | 96.65%  |
| Yes       | 49       | 3.35%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1319     | 89.91%  |
| Yes       | 148      | 10.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 338      | 23.15%  |
| Gigabyte Technology | 222      | 15.21%  |
| Dell                | 160      | 10.96%  |
| MSI                 | 153      | 10.48%  |
| Hewlett-Packard     | 140      | 9.59%   |
| ASRock              | 97       | 6.64%   |
| Lenovo              | 69       | 4.73%   |
| Intel               | 45       | 3.08%   |
| Acer                | 28       | 1.92%   |
| Unknown             | 25       | 1.71%   |
| Biostar             | 22       | 1.51%   |
| Pegatron            | 21       | 1.44%   |
| Fujitsu             | 17       | 1.16%   |
| Foxconn             | 16       | 1.1%    |
| AZW                 | 9        | 0.62%   |
| Alienware           | 6        | 0.41%   |
| Positivo            | 5        | 0.34%   |
| ECS                 | 5        | 0.34%   |
| Apple               | 5        | 0.34%   |
| OEM                 | 4        | 0.27%   |
| Huanan              | 4        | 0.27%   |
| Google              | 4        | 0.27%   |
| BESSTAR Tech        | 4        | 0.27%   |
| Shuttle             | 3        | 0.21%   |
| Medion              | 3        | 0.21%   |
| Gateway             | 3        | 0.21%   |
| eMachines           | 3        | 0.21%   |
| QIYIDA              | 2        | 0.14%   |
| PCWare              | 2        | 0.14%   |
| Packard Bell        | 2        | 0.14%   |
| MAXSUN              | 2        | 0.14%   |
| LORD ELECTRONICS    | 2        | 0.14%   |
| JGINYUE             | 2        | 0.14%   |
| Fujitsu Siemens     | 2        | 0.14%   |
| Wortmann AG         | 1        | 0.07%   |
| WIPRO               | 1        | 0.07%   |
| Win Element         | 1        | 0.07%   |
| Vorke               | 1        | 0.07%   |
| TYAN Computer       | 1        | 0.07%   |
| System76            | 1        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 33       | 2.26%   |
| Unknown                          | 26       | 1.78%   |
| Dell OptiPlex 7010               | 13       | 0.89%   |
| MSI MS-7817                      | 10       | 0.68%   |
| Dell OptiPlex 790                | 9        | 0.62%   |
| ASUS TUF Gaming X570-PLUS        | 9        | 0.62%   |
| Intel H61                        | 8        | 0.55%   |
| Dell OptiPlex 780                | 7        | 0.48%   |
| Dell OptiPlex 380                | 7        | 0.48%   |
| ASUS M5A78L-M/USB3               | 7        | 0.48%   |
| MSI MS-7C37                      | 6        | 0.41%   |
| MSI MS-7C02                      | 6        | 0.41%   |
| Gigabyte B450 AORUS M            | 6        | 0.41%   |
| Gigabyte A320M-S2H               | 6        | 0.41%   |
| Dell OptiPlex 3010               | 6        | 0.41%   |
| ASUS M5A97 R2.0                  | 6        | 0.41%   |
| HP EliteDesk 800 G1 SFF          | 5        | 0.34%   |
| HP Compaq Pro 6300 SFF           | 5        | 0.34%   |
| Dell Precision WorkStation T3500 | 5        | 0.34%   |
| Dell OptiPlex 990                | 5        | 0.34%   |
| Dell OptiPlex 7050               | 5        | 0.34%   |
| Dell OptiPlex 360                | 5        | 0.34%   |
| Dell OptiPlex 3020               | 5        | 0.34%   |
| ASUS P8Z77-V LX                  | 5        | 0.34%   |
| ASRock B450 Pro4                 | 5        | 0.34%   |
| MSI MS-7C75                      | 4        | 0.27%   |
| MSI MS-7B89                      | 4        | 0.27%   |
| MSI MS-7B86                      | 4        | 0.27%   |
| Intel X79M-S                     | 4        | 0.27%   |
| Intel H55                        | 4        | 0.27%   |
| HP ProDesk 600 G1 SFF            | 4        | 0.27%   |
| HP Compaq Elite 8300 SFF         | 4        | 0.27%   |
| Gigabyte X570 AORUS ELITE        | 4        | 0.27%   |
| Gigabyte H110M-H                 | 4        | 0.27%   |
| Gigabyte GA-78LMT-USB3 6.0       | 4        | 0.27%   |
| Gigabyte GA-78LMT-S2             | 4        | 0.27%   |
| Dell OptiPlex 9020               | 4        | 0.27%   |
| Dell OptiPlex 7040               | 4        | 0.27%   |
| Dell OptiPlex 7020               | 4        | 0.27%   |
| Dell OptiPlex 3050               | 4        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 102      | 6.99%   |
| ASUS PRIME             | 52       | 3.56%   |
| Lenovo ThinkCentre     | 48       | 3.29%   |
| ASUS ROG               | 43       | 2.95%   |
| HP Compaq              | 40       | 2.74%   |
| ASUS TUF               | 39       | 2.67%   |
| ASUS All               | 33       | 2.26%   |
| Unknown                | 26       | 1.78%   |
| HP EliteDesk           | 22       | 1.51%   |
| Dell Precision         | 19       | 1.3%    |
| Dell Inspiron          | 15       | 1.03%   |
| Acer Aspire            | 14       | 0.96%   |
| Gigabyte B450          | 13       | 0.89%   |
| Fujitsu ESPRIMO        | 13       | 0.89%   |
| HP ProDesk             | 12       | 0.82%   |
| HP Pavilion            | 12       | 0.82%   |
| ASUS M5A78L-M          | 11       | 0.75%   |
| MSI MS-7817            | 10       | 0.68%   |
| ASUS M5A97             | 10       | 0.68%   |
| Gigabyte X570          | 9        | 0.62%   |
| Lenovo IdeaCentre      | 8        | 0.55%   |
| Intel H61              | 8        | 0.55%   |
| Gigabyte B450M         | 8        | 0.55%   |
| ASRock B450            | 8        | 0.55%   |
| Gigabyte GA-78LMT-USB3 | 7        | 0.48%   |
| Gigabyte A320M-S2H     | 7        | 0.48%   |
| Dell XPS               | 7        | 0.48%   |
| ASUS P8Z77-V           | 7        | 0.48%   |
| ASUS P8H61-M           | 7        | 0.48%   |
| ASRock B450M           | 7        | 0.48%   |
| MSI MS-7C37            | 6        | 0.41%   |
| MSI MS-7C02            | 6        | 0.41%   |
| Dell Vostro            | 6        | 0.41%   |
| Gigabyte B550M         | 5        | 0.34%   |
| ASRock 970             | 5        | 0.34%   |
| Alienware Aurora       | 5        | 0.34%   |
| Acer Veriton           | 5        | 0.34%   |
| MSI MS-7C75            | 4        | 0.27%   |
| MSI MS-7B89            | 4        | 0.27%   |
| MSI MS-7B86            | 4        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 140      | 9.59%   |
| 2012    | 130      | 8.9%    |
| 2018    | 126      | 8.63%   |
| 2011    | 125      | 8.56%   |
| 2014    | 110      | 7.53%   |
| 2019    | 99       | 6.78%   |
| 2020    | 97       | 6.64%   |
| 2010    | 89       | 6.1%    |
| 2021    | 87       | 5.96%   |
| 2017    | 87       | 5.96%   |
| 2009    | 73       | 5%      |
| 2008    | 68       | 4.66%   |
| 2016    | 57       | 3.9%    |
| 2015    | 49       | 3.36%   |
| 2022    | 45       | 3.08%   |
| 2007    | 34       | 2.33%   |
| 2023    | 20       | 1.37%   |
| 2006    | 15       | 1.03%   |
| 2005    | 6        | 0.41%   |
| Unknown | 3        | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1460     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1373     | 93.72%  |
| Enabled  | 92       | 6.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1456     | 99.73%  |
| Yes  | 4        | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 363      | 24.53%  |
| 8.01-16.0       | 309      | 20.88%  |
| 4.01-8.0        | 247      | 16.69%  |
| 3.01-4.0        | 210      | 14.19%  |
| 32.01-64.0      | 201      | 13.58%  |
| 64.01-256.0     | 59       | 3.99%   |
| 24.01-32.0      | 38       | 2.57%   |
| 1.01-2.0        | 29       | 1.96%   |
| 2.01-3.0        | 20       | 1.35%   |
| 0.51-1.0        | 3        | 0.2%    |
| More than 256.0 | 1        | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 574      | 35.72%  |
| 2.01-3.0   | 491      | 30.55%  |
| 4.01-8.0   | 231      | 14.37%  |
| 3.01-4.0   | 229      | 14.25%  |
| 8.01-16.0  | 43       | 2.68%   |
| 0.51-1.0   | 25       | 1.56%   |
| 16.01-24.0 | 9        | 0.56%   |
| 32.01-64.0 | 2        | 0.12%   |
| 24.01-32.0 | 2        | 0.12%   |
| 0.01-0.5   | 1        | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 668      | 44.39%  |
| 2      | 425      | 28.24%  |
| 3      | 186      | 12.36%  |
| 4      | 109      | 7.24%   |
| 5      | 56       | 3.72%   |
| 6      | 33       | 2.19%   |
| 7      | 11       | 0.73%   |
| 8      | 8        | 0.53%   |
| 0      | 6        | 0.4%    |
| 51     | 1        | 0.07%   |
| 11     | 1        | 0.07%   |
| 9      | 1        | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 748      | 50.85%  |
| Yes       | 723      | 49.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1443     | 98.84%  |
| No        | 17       | 1.16%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 757      | 51.32%  |
| No        | 718      | 48.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 965      | 65.51%  |
| Yes       | 508      | 34.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 380      | 25.94%  |
| Germany      | 155      | 10.58%  |
| Brazil       | 105      | 7.17%   |
| UK           | 95       | 6.48%   |
| Canada       | 58       | 3.96%   |
| Italy        | 49       | 3.34%   |
| France       | 49       | 3.34%   |
| Netherlands  | 42       | 2.87%   |
| Poland       | 37       | 2.53%   |
| Spain        | 33       | 2.25%   |
| India        | 30       | 2.05%   |
| Australia    | 29       | 1.98%   |
| Argentina    | 21       | 1.43%   |
| Hungary      | 19       | 1.3%    |
| Belgium      | 19       | 1.3%    |
| Mexico       | 18       | 1.23%   |
| Russia       | 15       | 1.02%   |
| Denmark      | 15       | 1.02%   |
| South Africa | 14       | 0.96%   |
| Portugal     | 14       | 0.96%   |
| Sweden       | 13       | 0.89%   |
| Greece       | 13       | 0.89%   |
| Norway       | 12       | 0.82%   |
| Czechia      | 12       | 0.82%   |
| Serbia       | 11       | 0.75%   |
| Egypt        | 11       | 0.75%   |
| Turkey       | 10       | 0.68%   |
| Switzerland  | 10       | 0.68%   |
| Finland      | 9        | 0.61%   |
| Chile        | 9        | 0.61%   |
| Slovakia     | 8        | 0.55%   |
| Malaysia     | 8        | 0.55%   |
| Venezuela    | 7        | 0.48%   |
| Romania      | 7        | 0.48%   |
| New Zealand  | 7        | 0.48%   |
| Slovenia     | 6        | 0.41%   |
| Japan        | 6        | 0.41%   |
| Indonesia    | 5        | 0.34%   |
| Bulgaria     | 5        | 0.34%   |
| Philippines  | 4        | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Berlin         | 13       | 0.85%   |
| Rio de Janeiro | 12       | 0.78%   |
| Munich         | 10       | 0.65%   |
| Houston        | 9        | 0.59%   |
| Cape Town      | 8        | 0.52%   |
| Athens         | 8        | 0.52%   |
| Sao Paulo      | 7        | 0.46%   |
| Milan          | 7        | 0.46%   |
| Sydney         | 6        | 0.39%   |
| Rome           | 6        | 0.39%   |
| Phoenix        | 6        | 0.39%   |
| Montreal       | 6        | 0.39%   |
| Hamburg        | 6        | 0.39%   |
| Denver         | 6        | 0.39%   |
| Copenhagen     | 6        | 0.39%   |
| Calgary        | 6        | 0.39%   |
| Atlanta        | 6        | 0.39%   |
| Portland       | 5        | 0.33%   |
| Perth          | 5        | 0.33%   |
| Lisbon         | 5        | 0.33%   |
| Dallas         | 5        | 0.33%   |
| Buenos Aires   | 5        | 0.33%   |
| Adelaide       | 5        | 0.33%   |
| Wylie          | 4        | 0.26%   |
| The Hague      | 4        | 0.26%   |
| Santiago       | 4        | 0.26%   |
| San Jose       | 4        | 0.26%   |
| Salt Lake City | 4        | 0.26%   |
| Richmond       | 4        | 0.26%   |
| Prague         | 4        | 0.26%   |
| Minneapolis    | 4        | 0.26%   |
| Melbourne      | 4        | 0.26%   |
| Krakow         | 4        | 0.26%   |
| Johannesburg   | 4        | 0.26%   |
| Dayton         | 4        | 0.26%   |
| Budapest       | 4        | 0.26%   |
| Brussels       | 4        | 0.26%   |
| Brasília      | 4        | 0.26%   |
| Bolton         | 4        | 0.26%   |
| Bengaluru      | 4        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 490      | 773    | 18.82%  |
| WDC                         | 435      | 651    | 16.71%  |
| Samsung Electronics         | 336      | 528    | 12.9%   |
| Kingston                    | 166      | 242    | 6.37%   |
| Toshiba                     | 139      | 211    | 5.34%   |
| SanDisk                     | 138      | 194    | 5.3%    |
| Crucial                     | 106      | 128    | 4.07%   |
| Hitachi                     | 104      | 130    | 3.99%   |
| China                       | 43       | 50     | 1.65%   |
| A-DATA Technology           | 34       | 47     | 1.31%   |
| Unknown                     | 31       | 60     | 1.19%   |
| Silicon Motion              | 27       | 37     | 1.04%   |
| Intel                       | 26       | 31     | 1%      |
| PNY                         | 21       | 30     | 0.81%   |
| Intenso                     | 21       | 24     | 0.81%   |
| SK hynix                    | 20       | 25     | 0.77%   |
| Phison                      | 20       | 22     | 0.77%   |
| HGST                        | 20       | 28     | 0.77%   |
| Micron/Crucial Technology   | 18       | 23     | 0.69%   |
| Patriot                     | 15       | 21     | 0.58%   |
| SPCC                        | 14       | 21     | 0.54%   |
| Maxtor                      | 14       | 18     | 0.54%   |
| GOODRAM                     | 14       | 18     | 0.54%   |
| Micron Technology           | 13       | 13     | 0.5%    |
| Phison Electronics          | 12       | 15     | 0.46%   |
| Lexar                       | 12       | 13     | 0.46%   |
| Unknown                     | 12       | 13     | 0.46%   |
| OCZ                         | 11       | 13     | 0.42%   |
| MAXIO Technology (Hangzhou) | 11       | 11     | 0.42%   |
| JMicron Technology          | 11       | 13     | 0.42%   |
| Realtek Semiconductor       | 10       | 10     | 0.38%   |
| KingSpec                    | 10       | 13     | 0.38%   |
| Hewlett-Packard             | 10       | 14     | 0.38%   |
| Netac                       | 9        | 14     | 0.35%   |
| Gigabyte Technology         | 9        | 11     | 0.35%   |
| Apple                       | 9        | 10     | 0.35%   |
| Apacer                      | 9        | 12     | 0.35%   |
| Kingston Technology Company | 8        | 11     | 0.31%   |
| XPG                         | 7        | 8      | 0.27%   |
| Team                        | 7        | 9      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 49       | 1.63%   |
| Kingston SA400S37240G 240GB SSD                       | 44       | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB                        | 31       | 1.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 27       | 0.9%    |
| Samsung SSD 860 EVO 500GB                             | 26       | 0.87%   |
| Crucial CT240BX500SSD1 240GB                          | 25       | 0.83%   |
| Seagate ST1000DM003-1CH162 1TB                        | 23       | 0.77%   |
| Samsung SSD 850 EVO 250GB                             | 22       | 0.73%   |
| Kingston SA400S37120G 120GB SSD                       | 22       | 0.73%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 21       | 0.7%    |
| Toshiba HDWD110 1TB                                   | 19       | 0.63%   |
| Kingston SA400S37480G 480GB SSD                       | 19       | 0.63%   |
| Samsung NVMe SSD Drive 1TB                            | 17       | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB                        | 16       | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                        | 16       | 0.53%   |
| Toshiba DT01ACA100 1TB                                | 15       | 0.5%    |
| Seagate ST3500418AS 500GB                             | 15       | 0.5%    |
| Seagate ST1000DM003-1ER162 1TB                        | 14       | 0.47%   |
| Samsung NVMe SSD Drive 500GB                          | 14       | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 14       | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                      | 14       | 0.47%   |
| Unknown SD/MMC/MS PRO 128GB                           | 13       | 0.43%   |
| Toshiba DT01ACA050 500GB                              | 13       | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB                        | 13       | 0.43%   |
| Seagate ST3500413AS 500GB                             | 13       | 0.43%   |
| Seagate ST3500312CS 500GB                             | 13       | 0.43%   |
| Crucial CT1000MX500SSD1 1TB                           | 13       | 0.43%   |
| Seagate ST1000DM003-1SB102 1TB                        | 12       | 0.4%    |
| SanDisk NVMe SSD Drive 500GB                          | 12       | 0.4%    |
| SanDisk NVMe SSD Drive 1TB                            | 12       | 0.4%    |
| Samsung SSD 870 EVO 1TB                               | 12       | 0.4%    |
| Samsung SSD 850 EVO 500GB                             | 12       | 0.4%    |
| Crucial CT500MX500SSD1 500GB                          | 12       | 0.4%    |
| Unknown                                               | 12       | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB                        | 11       | 0.37%   |
| Samsung SSD 870 EVO 500GB                             | 11       | 0.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB     | 11       | 0.37%   |
| Toshiba DT01ACA200 2TB                                | 10       | 0.33%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 10       | 0.33%   |
| Seagate ST31000528AS 1TB                              | 10       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 483      | 751    | 38.33%  |
| WDC                 | 397      | 581    | 31.51%  |
| Toshiba             | 122      | 191    | 9.68%   |
| Hitachi             | 104      | 130    | 8.25%   |
| Samsung Electronics | 72       | 93     | 5.71%   |
| HGST                | 20       | 28     | 1.59%   |
| Unknown             | 14       | 19     | 1.11%   |
| Maxtor              | 14       | 18     | 1.11%   |
| JMicron Technology  | 8        | 9      | 0.63%   |
| Apple               | 6        | 7      | 0.48%   |
| SABRENT             | 5        | 6      | 0.4%    |
| Hewlett-Packard     | 4        | 7      | 0.32%   |
| USB3.0              | 2        | 3      | 0.16%   |
| WD MediaMax         | 1        | 1      | 0.08%   |
| Unknown (CF)        | 1        | 1      | 0.08%   |
| TDAS                | 1        | 3      | 0.08%   |
| QUANTUM             | 1        | 1      | 0.08%   |
| Intenso             | 1        | 1      | 0.08%   |
| IBM/Hitachi         | 1        | 1      | 0.08%   |
| HGST HTS            | 1        | 1      | 0.08%   |
| ASMT                | 1        | 2      | 0.08%   |
| ACASIS              | 1        | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 180      | 263    | 19.42%  |
| Kingston            | 137      | 186    | 14.78%  |
| Crucial             | 101      | 123    | 10.9%   |
| SanDisk             | 81       | 111    | 8.74%   |
| WDC                 | 47       | 60     | 5.07%   |
| China               | 43       | 50     | 4.64%   |
| A-DATA Technology   | 32       | 45     | 3.45%   |
| PNY                 | 21       | 30     | 2.27%   |
| Intel               | 16       | 18     | 1.73%   |
| Intenso             | 15       | 18     | 1.62%   |
| SPCC                | 14       | 21     | 1.51%   |
| Patriot             | 14       | 20     | 1.51%   |
| GOODRAM             | 13       | 17     | 1.4%    |
| Lexar               | 12       | 13     | 1.29%   |
| Toshiba             | 11       | 13     | 1.19%   |
| OCZ                 | 11       | 13     | 1.19%   |
| Netac               | 9        | 13     | 0.97%   |
| KingSpec            | 9        | 12     | 0.97%   |
| Apacer              | 9        | 12     | 0.97%   |
| SK hynix            | 8        | 8      | 0.86%   |
| Micron Technology   | 8        | 8      | 0.86%   |
| Team                | 7        | 9      | 0.76%   |
| Gigabyte Technology | 7        | 8      | 0.76%   |
| Transcend           | 6        | 7      | 0.65%   |
| Hewlett-Packard     | 6        | 7      | 0.65%   |
| Leven               | 5        | 6      | 0.54%   |
| Unknown             | 5        | 6      | 0.54%   |
| Super Talent        | 4        | 5      | 0.43%   |
| Seagate             | 4        | 8      | 0.43%   |
| KIOXIA-EXCERIA      | 4        | 8      | 0.43%   |
| Verbatim            | 3        | 3      | 0.32%   |
| LITEON              | 3        | 3      | 0.32%   |
| Fanxiang            | 3        | 3      | 0.32%   |
| Corsair             | 3        | 8      | 0.32%   |
| Acer                | 3        | 5      | 0.32%   |
| XrayDisk            | 2        | 3      | 0.22%   |
| Teclast             | 2        | 2      | 0.22%   |
| Plextor             | 2        | 3      | 0.22%   |
| Pioneer             | 2        | 2      | 0.22%   |
| ORTIAL              | 2        | 2      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 972      | 1855   | 44.46%  |
| SSD     | 780      | 1235   | 35.68%  |
| NVMe    | 359      | 555    | 16.42%  |
| Unknown | 68       | 93     | 3.11%   |
| MMC     | 7        | 9      | 0.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1346     | 3008   | 73.83%  |
| NVMe | 357      | 551    | 19.58%  |
| SAS  | 113      | 179    | 6.2%    |
| MMC  | 7        | 9      | 0.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1010     | 1718   | 53.78%  |
| 0.51-1.0   | 510      | 796    | 27.16%  |
| 1.01-2.0   | 212      | 308    | 11.29%  |
| 3.01-4.0   | 66       | 136    | 3.51%   |
| 2.01-3.0   | 36       | 52     | 1.92%   |
| 4.01-10.0  | 36       | 52     | 1.92%   |
| 10.01-20.0 | 7        | 26     | 0.37%   |
| 20.01-50.0 | 1        | 2      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 452      | 29.39%  |
| 251-500        | 353      | 22.95%  |
| 501-1000       | 250      | 16.25%  |
| 1001-2000      | 155      | 10.08%  |
| More than 3000 | 113      | 7.35%   |
| 51-100         | 82       | 5.33%   |
| 2001-3000      | 48       | 3.12%   |
| 21-50          | 34       | 2.21%   |
| 1-20           | 33       | 2.15%   |
| Unknown        | 18       | 1.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 505      | 31.48%  |
| 21-50          | 421      | 26.25%  |
| 51-100         | 199      | 12.41%  |
| 101-250        | 159      | 9.91%   |
| 251-500        | 111      | 6.92%   |
| 501-1000       | 79       | 4.93%   |
| More than 3000 | 54       | 3.37%   |
| 1001-2000      | 41       | 2.56%   |
| Unknown        | 18       | 1.12%   |
| 2001-3000      | 17       | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD30EFRX-68EUZN0 3TB                 | 2        | 2      | 3.92%   |
| Seagate ST500DM002-1BD142 500GB          | 2        | 2      | 3.92%   |
| HGST HTS541010A9E680 1TB                 | 2        | 2      | 3.92%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1        | 1      | 1.96%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1        | 1      | 1.96%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1        | 1      | 1.96%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1        | 1      | 1.96%   |
| WDC WD20EZRX-22D8PB0 2TB                 | 1        | 1      | 1.96%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1        | 1      | 1.96%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1        | 2      | 1.96%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1        | 1      | 1.96%   |
| WDC WD Green 2.5 1000GB                  | 1        | 1      | 1.96%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1        | 1      | 1.96%   |
| Toshiba MQ01ABD100 1TB                   | 1        | 1      | 1.96%   |
| Toshiba MK8046GSX 80GB                   | 1        | 1      | 1.96%   |
| Toshiba MK3265GSX 320GB                  | 1        | 1      | 1.96%   |
| Toshiba MG03ACA200 2TB                   | 1        | 1      | 1.96%   |
| Toshiba DT01ACA100 1TB                   | 1        | 1      | 1.96%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1        | 1      | 1.96%   |
| Seagate ST9500420AS 500GB                | 1        | 1      | 1.96%   |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 1      | 1.96%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 1.96%   |
| Seagate ST3500514NS 500GB                | 1        | 1      | 1.96%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 1.96%   |
| Seagate ST3500312CS 500GB                | 1        | 1      | 1.96%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 1.96%   |
| Seagate ST3320620AS 320GB                | 1        | 1      | 1.96%   |
| Seagate ST3250318AS 250GB                | 1        | 1      | 1.96%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 1      | 1.96%   |
| Seagate ST320LT009-9WC142 320GB          | 1        | 1      | 1.96%   |
| Seagate ST3160310CS 160GB                | 1        | 1      | 1.96%   |
| Seagate ST2000LM007-1R8174 2TB           | 1        | 1      | 1.96%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 1        | 1      | 1.96%   |
| Seagate ST2000DX002-2DV164 2TB           | 1        | 1      | 1.96%   |
| Seagate ST2000DM008-2FR102 2TB           | 1        | 1      | 1.96%   |
| Seagate ST2000DM001-9YN164 2TB           | 1        | 1      | 1.96%   |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1      | 1.96%   |
| Samsung Electronics HD161HJ 160GB        | 1        | 1      | 1.96%   |
| Samsung Electronics HD154UI 1TB          | 1        | 1      | 1.96%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 20     | 38%     |
| WDC                 | 11       | 12     | 22%     |
| Toshiba             | 6        | 6      | 12%     |
| HGST                | 3        | 3      | 6%      |
| Samsung Electronics | 2        | 2      | 4%      |
| Kingston            | 2        | 2      | 4%      |
| A-DATA Technology   | 2        | 2      | 4%      |
| Silicon Motion      | 1        | 1      | 2%      |
| OCZ                 | 1        | 1      | 2%      |
| Maxtor              | 1        | 1      | 2%      |
| Intel               | 1        | 1      | 2%      |
| China               | 1        | 1      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 20     | 48.72%  |
| WDC                 | 9        | 10     | 23.08%  |
| Toshiba             | 5        | 5      | 12.82%  |
| HGST                | 3        | 3      | 7.69%   |
| Samsung Electronics | 2        | 2      | 5.13%   |
| Maxtor              | 1        | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 35       | 41     | 76.09%  |
| SSD  | 9        | 9      | 19.57%  |
| NVMe | 2        | 2      | 4.35%   |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1350     | 3377   | 88.7%   |
| Works    | 127      | 318    | 8.34%   |
| Malfunc  | 45       | 52     | 2.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 961      | 48.05%  |
| AMD                            | 452      | 22.6%   |
| Samsung Electronics            | 118      | 5.9%    |
| SanDisk                        | 67       | 3.35%   |
| ASMedia Technology             | 59       | 2.95%   |
| Kingston Technology Company    | 43       | 2.15%   |
| JMicron Technology             | 41       | 2.05%   |
| Nvidia                         | 35       | 1.75%   |
| Phison Electronics             | 34       | 1.7%    |
| Marvell Technology Group       | 31       | 1.55%   |
| Silicon Motion                 | 29       | 1.45%   |
| Micron/Crucial Technology      | 23       | 1.15%   |
| MAXIO Technology (Hangzhou)    | 12       | 0.6%    |
| ADATA Technology               | 12       | 0.6%    |
| SK hynix                       | 11       | 0.55%   |
| Realtek Semiconductor          | 10       | 0.5%    |
| VIA Technologies               | 8        | 0.4%    |
| Silicon Image                  | 8        | 0.4%    |
| Seagate Technology             | 8        | 0.4%    |
| KIOXIA                         | 8        | 0.4%    |
| Toshiba America Info Systems   | 5        | 0.25%   |
| Micron Technology              | 5        | 0.25%   |
| Shenzhen Longsys Electronics   | 4        | 0.2%    |
| INNOGRIT                       | 3        | 0.15%   |
| Broadcom / LSI                 | 3        | 0.15%   |
| TenaFe                         | 1        | 0.05%   |
| Solid State Storage Technology | 1        | 0.05%   |
| OCZ Technology Group           | 1        | 0.05%   |
| Nextorage                      | 1        | 0.05%   |
| Netac Technology               | 1        | 0.05%   |
| Lite-On Technology             | 1        | 0.05%   |
| Integrated Technology Express  | 1        | 0.05%   |
| HighPoint Technologies         | 1        | 0.05%   |
| Beijing Starblaze Technology   | 1        | 0.05%   |
| Apple                          | 1        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 234      | 9.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 148      | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 94       | 3.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 87       | 3.46%   |
| AMD 400 Series Chipset SATA Controller                                                  | 87       | 3.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 81       | 3.22%   |
| Intel SATA Controller [RAID mode]                                                       | 70       | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 70       | 2.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 69       | 2.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 60       | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 57       | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 57       | 2.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 53       | 2.1%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 53       | 2.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 49       | 1.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 47       | 1.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 36       | 1.43%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 36       | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 35       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 34       | 1.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 30       | 1.19%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 26       | 1.03%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 24       | 0.95%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 23       | 0.91%   |
| AMD FCH SATA Controller D                                                               | 22       | 0.87%   |
| Nvidia MCP61 SATA Controller                                                            | 21       | 0.83%   |
| AMD 300 Series Chipset SATA Controller                                                  | 21       | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 18       | 0.71%   |
| Phison E12 NVMe Controller                                                              | 18       | 0.71%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 18       | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 17       | 0.68%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 16       | 0.64%   |
| Nvidia MCP61 IDE                                                                        | 16       | 0.64%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 16       | 0.64%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 16       | 0.64%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 15       | 0.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 15       | 0.6%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 15       | 0.6%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 15       | 0.6%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 14       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1158     | 57.41%  |
| IDE  | 381      | 18.89%  |
| NVMe | 356      | 17.65%  |
| RAID | 113      | 5.6%    |
| SAS  | 6        | 0.3%    |
| SCSI | 3        | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 974      | 66.71%  |
| AMD    | 486      | 33.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 28       | 1.91%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 26       | 1.77%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 24       | 1.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 22       | 1.5%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 17       | 1.16%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 16       | 1.09%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 16       | 1.09%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 16       | 1.09%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 15       | 1.02%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 15       | 1.02%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 15       | 1.02%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 14       | 0.96%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 14       | 0.96%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 13       | 0.89%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 13       | 0.89%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 13       | 0.89%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 13       | 0.89%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 13       | 0.89%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 12       | 0.82%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 12       | 0.82%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 11       | 0.75%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 11       | 0.75%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 11       | 0.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 10       | 0.68%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 9        | 0.61%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 9        | 0.61%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 9        | 0.61%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 9        | 0.61%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 9        | 0.61%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 8        | 0.55%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 8        | 0.55%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 8        | 0.55%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 8        | 0.55%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 8        | 0.55%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 8        | 0.55%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 8        | 0.55%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 8        | 0.55%   |
| AMD FX-8350 Eight-Core Processor            | 8        | 0.55%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 7        | 0.48%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 7        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 291      | 19.9%   |
| Intel Core i7           | 168      | 11.49%  |
| Intel Core i3           | 133      | 9.1%    |
| AMD Ryzen 5             | 121      | 8.28%   |
| Intel Xeon              | 77       | 5.27%   |
| AMD Ryzen 7             | 61       | 4.17%   |
| AMD FX                  | 56       | 3.83%   |
| Other                   | 52       | 3.56%   |
| Intel Core 2 Duo        | 49       | 3.35%   |
| AMD Ryzen 9             | 47       | 3.21%   |
| Intel Celeron           | 40       | 2.74%   |
| Intel Core 2 Quad       | 36       | 2.46%   |
| Intel Pentium Dual-Core | 33       | 2.26%   |
| Intel Pentium           | 30       | 2.05%   |
| AMD Athlon II X2        | 26       | 1.78%   |
| AMD Ryzen 3             | 24       | 1.64%   |
| Intel Pentium Dual      | 22       | 1.5%    |
| AMD Phenom II X4        | 19       | 1.3%    |
| AMD A8                  | 15       | 1.03%   |
| AMD A10                 | 15       | 1.03%   |
| AMD A6                  | 14       | 0.96%   |
| Intel Core i9           | 13       | 0.89%   |
| AMD Athlon 64 X2        | 12       | 0.82%   |
| AMD Phenom II X6        | 11       | 0.75%   |
| Intel Atom              | 9        | 0.62%   |
| Intel Core 2            | 8        | 0.55%   |
| AMD Athlon              | 8        | 0.55%   |
| Intel Pentium 4         | 7        | 0.48%   |
| AMD Athlon II X4        | 7        | 0.48%   |
| Intel Pentium Gold      | 5        | 0.34%   |
| AMD Athlon II X3        | 5        | 0.34%   |
| AMD A4                  | 5        | 0.34%   |
| AMD Phenom              | 4        | 0.27%   |
| AMD E1                  | 4        | 0.27%   |
| AMD Sempron             | 3        | 0.21%   |
| AMD Ryzen 5 PRO         | 3        | 0.21%   |
| AMD PRO A10             | 3        | 0.21%   |
| AMD GX                  | 3        | 0.21%   |
| Intel Pentium D         | 2        | 0.14%   |
| AMD Ryzen Threadripper  | 2        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 603      | 41.22%  |
| 2      | 418      | 28.57%  |
| 6      | 194      | 13.26%  |
| 8      | 118      | 8.07%   |
| 12     | 36       | 2.46%   |
| 1      | 30       | 2.05%   |
| 16     | 23       | 1.57%   |
| 3      | 21       | 1.44%   |
| 10     | 14       | 0.96%   |
| 28     | 2        | 0.14%   |
| 24     | 2        | 0.14%   |
| 14     | 2        | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1450     | 99.32%  |
| 2      | 10       | 0.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 780      | 53.35%  |
| 1      | 682      | 46.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1460     | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 170      | 11.46%  |
| Unknown    | 120      | 8.09%   |
| 0x306a9    | 111      | 7.48%   |
| 0x206a7    | 101      | 6.81%   |
| 0x1067a    | 90       | 6.07%   |
| 0x506e3    | 59       | 3.98%   |
| 0x08701021 | 51       | 3.44%   |
| 0x06000852 | 39       | 2.63%   |
| 0x906e9    | 32       | 2.16%   |
| 0x906ea    | 31       | 2.09%   |
| 0x0800820d | 29       | 1.96%   |
| 0x010000c8 | 27       | 1.82%   |
| 0x6fd      | 26       | 1.75%   |
| 0xa0655    | 24       | 1.62%   |
| 0xa0653    | 24       | 1.62%   |
| 0x0a201016 | 20       | 1.35%   |
| 0x08108109 | 19       | 1.28%   |
| 0x06001119 | 18       | 1.21%   |
| 0x0600063e | 16       | 1.08%   |
| 0xa0671    | 15       | 1.01%   |
| 0x6fb      | 15       | 1.01%   |
| 0x20655    | 15       | 1.01%   |
| 0x08001138 | 15       | 1.01%   |
| 0x906ed    | 14       | 0.94%   |
| 0x906eb    | 13       | 0.88%   |
| 0x010000dc | 13       | 0.88%   |
| 0x010000db | 13       | 0.88%   |
| 0x306e4    | 11       | 0.74%   |
| 0x106e5    | 11       | 0.74%   |
| 0x0a50000d | 11       | 0.74%   |
| 0x08701013 | 11       | 0.74%   |
| 0x90672    | 10       | 0.67%   |
| 0x306f2    | 10       | 0.67%   |
| 0x206d7    | 10       | 0.67%   |
| 0x20652    | 10       | 0.67%   |
| 0x106a5    | 10       | 0.67%   |
| 0x10676    | 10       | 0.67%   |
| 0x06003106 | 10       | 0.67%   |
| 0x0a601203 | 9        | 0.61%   |
| 0x0a20120a | 9        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 196      | 13.41%  |
| IvyBridge        | 125      | 8.55%   |
| SandyBridge      | 116      | 7.93%   |
| Penryn           | 106      | 7.25%   |
| KabyLake         | 104      | 7.11%   |
| Zen 2            | 81       | 5.54%   |
| K10              | 75       | 5.13%   |
| Zen 3            | 71       | 4.86%   |
| Skylake          | 61       | 4.17%   |
| Piledriver       | 60       | 4.1%    |
| Core             | 55       | 3.76%   |
| Zen+             | 51       | 3.49%   |
| CometLake        | 51       | 3.49%   |
| Zen              | 46       | 3.15%   |
| Unknown          | 39       | 2.67%   |
| Westmere         | 33       | 2.26%   |
| Nehalem          | 27       | 1.85%   |
| K8 Hammer        | 18       | 1.23%   |
| Icelake          | 16       | 1.09%   |
| Bulldozer        | 16       | 1.09%   |
| Excavator        | 15       | 1.03%   |
| Alderlake Hybrid | 14       | 0.96%   |
| Silvermont       | 13       | 0.89%   |
| Steamroller      | 11       | 0.75%   |
| NetBurst         | 10       | 0.68%   |
| Puma             | 7        | 0.48%   |
| Jaguar           | 7        | 0.48%   |
| Broadwell        | 7        | 0.48%   |
| Bonnell          | 7        | 0.48%   |
| K10 Llano        | 6        | 0.41%   |
| Goldmont plus    | 5        | 0.34%   |
| Bobcat           | 5        | 0.34%   |
| Tremont          | 4        | 0.27%   |
| Goldmont         | 3        | 0.21%   |
| TigerLake        | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 574      | 36.65%  |
| Intel                      | 512      | 32.69%  |
| AMD                        | 475      | 30.33%  |
| VIA Technologies           | 2        | 0.13%   |
| Matrox Electronics Systems | 1        | 0.06%   |
| ATI Technologies           | 1        | 0.06%   |
| ASPEED Technology          | 1        | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 93       | 5.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 60       | 3.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 54       | 3.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 49       | 3.07%   |
| Nvidia GK208B [GeForce GT 710]                                              | 39       | 2.44%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 37       | 2.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 33       | 2.07%   |
| Intel HD Graphics 530                                                       | 30       | 1.88%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 27       | 1.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 26       | 1.63%   |
| Intel HD Graphics 630                                                       | 22       | 1.38%   |
| Nvidia GK208B [GeForce GT 730]                                              | 21       | 1.31%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 21       | 1.31%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 20       | 1.25%   |
| Intel Core Processor Integrated Graphics Controller                         | 20       | 1.25%   |
| Nvidia GF119 [GeForce GT 610]                                               | 18       | 1.13%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 18       | 1.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 17       | 1.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 17       | 1.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 16       | 1%      |
| Nvidia TU117 [GeForce GTX 1650]                                             | 15       | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                  | 15       | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 15       | 0.94%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 15       | 0.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 15       | 0.94%   |
| AMD RS780L [Radeon 3000]                                                    | 15       | 0.94%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 13       | 0.81%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 13       | 0.81%   |
| Nvidia GF108 [GeForce GT 730]                                               | 12       | 0.75%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 12       | 0.75%   |
| Nvidia GF108 [GeForce GT 630]                                               | 11       | 0.69%   |
| AMD Raphael                                                                 | 11       | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 10       | 0.63%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 10       | 0.63%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 10       | 0.63%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 9        | 0.56%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 9        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 8        | 0.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 8        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 529      | 35.84%  |
| 1 x Intel            | 449      | 30.42%  |
| 1 x AMD              | 434      | 29.4%   |
| Intel + Nvidia       | 16       | 1.08%   |
| 2 x AMD              | 15       | 1.02%   |
| AMD + Nvidia         | 15       | 1.02%   |
| Intel + AMD          | 10       | 0.68%   |
| 2 x Nvidia           | 3        | 0.2%    |
| 1 x VIA              | 2        | 0.14%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.07%   |
| 1 x Matrox           | 1        | 0.07%   |
| 1 x ASPEED           | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1021     | 69.13%  |
| Proprietary | 362      | 24.51%  |
| Unknown     | 94       | 6.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 650      | 43.59%  |
| 1.01-2.0   | 184      | 12.34%  |
| 0.51-1.0   | 177      | 11.87%  |
| 0.01-0.5   | 148      | 9.93%   |
| 3.01-4.0   | 121      | 8.12%   |
| 7.01-8.0   | 111      | 7.44%   |
| 8.01-16.0  | 41       | 2.75%   |
| 5.01-6.0   | 36       | 2.41%   |
| 2.01-3.0   | 19       | 1.27%   |
| 16.01-24.0 | 4        | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 229      | 15.95%  |
| Dell                 | 140      | 9.75%   |
| Goldstar             | 134      | 9.33%   |
| Hewlett-Packard      | 111      | 7.73%   |
| Acer                 | 96       | 6.69%   |
| AOC                  | 80       | 5.57%   |
| Philips              | 73       | 5.08%   |
| Ancor Communications | 51       | 3.55%   |
| BenQ                 | 50       | 3.48%   |
| LG Electronics       | 30       | 2.09%   |
| ViewSonic            | 28       | 1.95%   |
| Lenovo               | 26       | 1.81%   |
| Unknown              | 24       | 1.67%   |
| Unknown              | 23       | 1.6%    |
| Sony                 | 20       | 1.39%   |
| Iiyama               | 16       | 1.11%   |
| ASUSTek Computer     | 16       | 1.11%   |
| Sceptre Tech         | 14       | 0.97%   |
| NEC Computers        | 13       | 0.91%   |
| Fujitsu Siemens      | 13       | 0.91%   |
| Vizio                | 10       | 0.7%    |
| HPN                  | 10       | 0.7%    |
| Eizo                 | 10       | 0.7%    |
| Toshiba              | 9        | 0.63%   |
| MSI                  | 8        | 0.56%   |
| FUS                  | 8        | 0.56%   |
| Panasonic            | 6        | 0.42%   |
| Microstep            | 6        | 0.42%   |
| Idek Iiyama          | 6        | 0.42%   |
| AUS                  | 6        | 0.42%   |
| Vestel               | 5        | 0.35%   |
| Pixio                | 5        | 0.35%   |
| Medion               | 5        | 0.35%   |
| Gigabyte Technology  | 5        | 0.35%   |
| Unknown (XXX)        | 4        | 0.28%   |
| RTK                  | 4        | 0.28%   |
| Lenovo Group Limited | 4        | 0.28%   |
| ITE                  | 4        | 0.28%   |
| HannStar             | 4        | 0.28%   |
| Envision             | 4        | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 23       | 1.51%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10       | 0.66%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 9        | 0.59%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 7        | 0.46%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 6        | 0.39%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 5        | 0.33%   |
| Philips LCD Monitor FTV 1920x1080                                     | 5        | 0.33%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 5        | 0.33%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 4        | 0.26%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                      | 4        | 0.26%   |
| Hewlett-Packard 24f HPN3546 1920x1080 527x296mm 23.8-inch             | 4        | 0.26%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                   | 4        | 0.26%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 4        | 0.26%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                             | 3        | 0.2%    |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 3        | 0.2%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 3        | 0.2%    |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch              | 3        | 0.2%    |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch     | 3        | 0.2%    |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch     | 3        | 0.2%    |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 3        | 0.2%    |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 3        | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.2%    |
| Philips PHL 277E6 PHLC0E6 1920x1080 598x336mm 27.0-inch               | 3        | 0.2%    |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 3        | 0.2%    |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch           | 3        | 0.2%    |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch          | 3        | 0.2%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 3        | 0.2%    |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 3        | 0.2%    |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                    | 3        | 0.2%    |
| Dell P2719H DEL4185 1920x1080 598x336mm 27.0-inch                     | 3        | 0.2%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 3        | 0.2%    |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                     | 3        | 0.2%    |
| Dell LCD Monitor E228WFP                                              | 3        | 0.2%    |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                     | 3        | 0.2%    |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 3        | 0.2%    |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 3        | 0.2%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 3        | 0.2%    |
| ___ LCDTV16 ___9000 1360x768                                          | 2        | 0.13%   |
| Xiaomi Mi TV XMD00E2 1920x1080 708x398mm 32.0-inch                    | 2        | 0.13%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch             | 2        | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 598      | 42.08%  |
| 3840x2160 (4K)     | 126      | 8.87%   |
| 1280x1024 (SXGA)   | 83       | 5.84%   |
| 1680x1050 (WSXGA+) | 81       | 5.7%    |
| 2560x1440 (QHD)    | 69       | 4.86%   |
| 1600x900 (HD+)     | 64       | 4.5%    |
| Unknown            | 61       | 4.29%   |
| 1366x768 (WXGA)    | 59       | 4.15%   |
| 1440x900 (WXGA+)   | 54       | 3.8%    |
| 1360x768           | 33       | 2.32%   |
| 3440x1440          | 32       | 2.25%   |
| 3840x1080          | 31       | 2.18%   |
| 1920x1200 (WUXGA)  | 31       | 2.18%   |
| 2560x1080          | 17       | 1.2%    |
| 1920x540           | 12       | 0.84%   |
| 1024x768 (XGA)     | 10       | 0.7%    |
| 1600x1200          | 7        | 0.49%   |
| 3840x1600          | 4        | 0.28%   |
| 1280x720 (HD)      | 4        | 0.28%   |
| 4480x1440          | 3        | 0.21%   |
| 5760x2160          | 2        | 0.14%   |
| 5760x1080          | 2        | 0.14%   |
| 5120x1440          | 2        | 0.14%   |
| 4480x1080          | 2        | 0.14%   |
| 3600x1080          | 2        | 0.14%   |
| 3360x1080          | 2        | 0.14%   |
| 3200x1200          | 2        | 0.14%   |
| 3120x1050          | 2        | 0.14%   |
| 2944x1080          | 2        | 0.14%   |
| 2560x1600          | 2        | 0.14%   |
| 1280x960           | 2        | 0.14%   |
| 7680x2160          | 1        | 0.07%   |
| 6880x1440          | 1        | 0.07%   |
| 6400x1440          | 1        | 0.07%   |
| 5440x1080          | 1        | 0.07%   |
| 5040x1050          | 1        | 0.07%   |
| 4480x1600          | 1        | 0.07%   |
| 4160x1440          | 1        | 0.07%   |
| 3780x2160          | 1        | 0.07%   |
| 3360x1050          | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 269      | 19.12%  |
| 24      | 143      | 10.16%  |
| 27      | 140      | 9.95%   |
| 21      | 132      | 9.38%   |
| 23      | 124      | 8.81%   |
| 19      | 92       | 6.54%   |
| 20      | 73       | 5.19%   |
| 31      | 66       | 4.69%   |
| 22      | 56       | 3.98%   |
| 18      | 55       | 3.91%   |
| 17      | 40       | 2.84%   |
| 34      | 33       | 2.35%   |
| 40      | 23       | 1.63%   |
| 15      | 21       | 1.49%   |
| 84      | 14       | 1%      |
| 72      | 14       | 1%      |
| 54      | 14       | 1%      |
| 32      | 13       | 0.92%   |
| 26      | 9        | 0.64%   |
| 25      | 7        | 0.5%    |
| 36      | 6        | 0.43%   |
| 65      | 5        | 0.36%   |
| 52      | 5        | 0.36%   |
| 49      | 5        | 0.36%   |
| 28      | 5        | 0.36%   |
| 48      | 4        | 0.28%   |
| 46      | 3        | 0.21%   |
| 35      | 3        | 0.21%   |
| 33      | 3        | 0.21%   |
| 29      | 3        | 0.21%   |
| 74      | 2        | 0.14%   |
| 60      | 2        | 0.14%   |
| 58      | 2        | 0.14%   |
| 57      | 2        | 0.14%   |
| 42      | 2        | 0.14%   |
| 41      | 2        | 0.14%   |
| 37      | 2        | 0.14%   |
| 142     | 1        | 0.07%   |
| 86      | 1        | 0.07%   |
| 75      | 1        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 373      | 27.45%  |
| 401-500        | 351      | 25.83%  |
| Unknown        | 269      | 19.79%  |
| 601-700        | 93       | 6.84%   |
| 301-350        | 60       | 4.42%   |
| 701-800        | 55       | 4.05%   |
| 1001-1500      | 45       | 3.31%   |
| 351-400        | 44       | 3.24%   |
| 1501-2000      | 33       | 2.43%   |
| 801-900        | 29       | 2.13%   |
| 901-1000       | 5        | 0.37%   |
| More than 2000 | 1        | 0.07%   |
| 201-300        | 1        | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 748      | 57.06%  |
| Unknown | 247      | 18.84%  |
| 16/10   | 162      | 12.36%  |
| 5/4     | 75       | 5.72%   |
| 21/9    | 42       | 3.2%    |
| 4/3     | 21       | 1.6%    |
| 32/9    | 9        | 0.69%   |
| 6/5     | 5        | 0.38%   |
| 3/2     | 1        | 0.08%   |
| 1.00    | 1        | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 365      | 26.37%  |
| Unknown        | 269      | 19.44%  |
| 151-200        | 209      | 15.1%   |
| 301-350        | 143      | 10.33%  |
| 351-500        | 122      | 8.82%   |
| 141-150        | 78       | 5.64%   |
| More than 1000 | 70       | 5.06%   |
| 251-300        | 57       | 4.12%   |
| 501-1000       | 46       | 3.32%   |
| 101-110        | 16       | 1.16%   |
| 111-120        | 4        | 0.29%   |
| 81-90          | 1        | 0.07%   |
| 71-80          | 1        | 0.07%   |
| 131-140        | 1        | 0.07%   |
| 121-130        | 1        | 0.07%   |
| 91-100         | 1        | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 737      | 55.71%  |
| Unknown | 269      | 20.33%  |
| 101-120 | 194      | 14.66%  |
| 1-50    | 67       | 5.06%   |
| 121-160 | 40       | 3.02%   |
| 161-240 | 16       | 1.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1178     | 79.01%  |
| 2     | 195      | 13.08%  |
| 0     | 97       | 6.51%   |
| 3     | 19       | 1.27%   |
| 4     | 2        | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 926      | 42.77%  |
| Intel                             | 595      | 27.48%  |
| Qualcomm Atheros                  | 136      | 6.28%   |
| Broadcom                          | 75       | 3.46%   |
| Ralink Technology                 | 71       | 3.28%   |
| TP-Link                           | 58       | 2.68%   |
| Nvidia                            | 30       | 1.39%   |
| MediaTek                          | 30       | 1.39%   |
| Ralink                            | 29       | 1.34%   |
| NetGear                           | 18       | 0.83%   |
| Samsung Electronics               | 17       | 0.79%   |
| Broadcom Limited                  | 13       | 0.6%    |
| Microsoft                         | 12       | 0.55%   |
| Marvell Technology Group          | 12       | 0.55%   |
| D-Link                            | 12       | 0.55%   |
| Qualcomm Atheros Communications   | 11       | 0.51%   |
| Xiaomi                            | 10       | 0.46%   |
| D-Link System                     | 10       | 0.46%   |
| ASIX Electronics                  | 10       | 0.46%   |
| Huawei Technologies               | 8        | 0.37%   |
| ASUSTek Computer                  | 7        | 0.32%   |
| Aquantia                          | 7        | 0.32%   |
| Edimax Technology                 | 6        | 0.28%   |
| OPPO Electronics                  | 4        | 0.18%   |
| Motorola PCS                      | 4        | 0.18%   |
| Linksys                           | 4        | 0.18%   |
| DisplayLink                       | 4        | 0.18%   |
| Belkin Components                 | 4        | 0.18%   |
| ZyDAS                             | 2        | 0.09%   |
| VIA Technologies                  | 2        | 0.09%   |
| Sundance Technology Inc / IC Plus | 2        | 0.09%   |
| QinHeng Electronics               | 2        | 0.09%   |
| Motorola                          | 2        | 0.09%   |
| Gemtek                            | 2        | 0.09%   |
| AVM                               | 2        | 0.09%   |
| Arduino SA                        | 2        | 0.09%   |
| ZyXEL Communications              | 1        | 0.05%   |
| U-Blox                            | 1        | 0.05%   |
| TRENDnet                          | 1        | 0.05%   |
| T & A Mobile Phones               | 1        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 689      | 28.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 81       | 3.3%    |
| Realtek RTL8125 2.5GbE Controller                                      | 74       | 3.01%   |
| Intel Wi-Fi 6 AX200                                                    | 60       | 2.44%   |
| Intel I211 Gigabit Network Connection                                  | 60       | 2.44%   |
| Intel Ethernet Connection I217-LM                                      | 56       | 2.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 55       | 2.24%   |
| Intel Ethernet Connection (2) I219-V                                   | 43       | 1.75%   |
| Intel Ethernet Controller I225-V                                       | 36       | 1.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 35       | 1.43%   |
| Realtek 802.11ac NIC                                                   | 35       | 1.43%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 33       | 1.34%   |
| Ralink MT7601U Wireless Adapter                                        | 31       | 1.26%   |
| Intel Ethernet Connection I217-V                                       | 25       | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 25       | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 23       | 0.94%   |
| Intel Wireless 7265                                                    | 21       | 0.86%   |
| Nvidia MCP61 Ethernet                                                  | 20       | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 19       | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 18       | 0.73%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 17       | 0.69%   |
| Intel 82579V Gigabit Network Connection                                | 17       | 0.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 16       | 0.65%   |
| Ralink RT5370 Wireless Adapter                                         | 15       | 0.61%   |
| Intel Ethernet Connection (7) I219-V                                   | 15       | 0.61%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 14       | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                  | 14       | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                   | 14       | 0.57%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 14       | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 13       | 0.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 13       | 0.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 13       | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 12       | 0.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 11       | 0.45%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 11       | 0.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 10       | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 10       | 0.41%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 10       | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 10       | 0.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 10       | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 230      | 27.35%  |
| Realtek Semiconductor                 | 228      | 27.11%  |
| Ralink Technology                     | 71       | 8.44%   |
| Qualcomm Atheros                      | 68       | 8.09%   |
| TP-Link                               | 56       | 6.66%   |
| Broadcom                              | 33       | 3.92%   |
| Ralink                                | 29       | 3.45%   |
| MediaTek                              | 26       | 3.09%   |
| NetGear                               | 18       | 2.14%   |
| Microsoft                             | 12       | 1.43%   |
| D-Link                                | 12       | 1.43%   |
| Qualcomm Atheros Communications       | 11       | 1.31%   |
| D-Link System                         | 8        | 0.95%   |
| Edimax Technology                     | 6        | 0.71%   |
| ASUSTek Computer                      | 6        | 0.71%   |
| Broadcom Limited                      | 5        | 0.59%   |
| Linksys                               | 4        | 0.48%   |
| Belkin Components                     | 4        | 0.48%   |
| ZyDAS                                 | 2        | 0.24%   |
| Gemtek                                | 2        | 0.24%   |
| AVM                                   | 2        | 0.24%   |
| ZyXEL Communications                  | 1        | 0.12%   |
| Xiaomi                                | 1        | 0.12%   |
| TRENDnet                              | 1        | 0.12%   |
| Panasonic (Matsushita)                | 1        | 0.12%   |
| Ovislink                              | 1        | 0.12%   |
| Marvell Technology Group              | 1        | 0.12%   |
| ADMtek                                | 1        | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 60       | 7.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 35       | 4.1%    |
| Realtek 802.11ac NIC                                           | 35       | 4.1%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 33       | 3.87%   |
| Ralink MT7601U Wireless Adapter                                | 31       | 3.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 25       | 2.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 23       | 2.7%    |
| Intel Wireless 7265                                            | 21       | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19       | 2.23%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 17       | 1.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 16       | 1.88%   |
| Ralink RT5370 Wireless Adapter                                 | 15       | 1.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 14       | 1.64%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 14       | 1.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 13       | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13       | 1.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 11       | 1.29%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 11       | 1.29%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 10       | 1.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 10       | 1.17%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 10       | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10       | 1.17%   |
| Intel Wireless 7260                                            | 10       | 1.17%   |
| Intel Wireless 3165                                            | 9        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9        | 1.06%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 8        | 0.94%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 8        | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8        | 0.94%   |
| Qualcomm Atheros AR9271 802.11n                                | 8        | 0.94%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 8        | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7        | 0.82%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 7        | 0.82%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 7        | 0.82%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 6        | 0.7%    |
| Ralink RT2561/RT61 802.11g PCI                                 | 6        | 0.7%    |
| Microsoft Xbox 360 Wireless Adapter                            | 6        | 0.7%    |
| MediaTek WiFi                                                  | 6        | 0.7%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 5        | 0.59%   |
| TP-Link 802.11ac WLAN Adapter                                  | 5        | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 843      | 54.42%  |
| Intel                             | 461      | 29.76%  |
| Qualcomm Atheros                  | 72       | 4.65%   |
| Broadcom                          | 43       | 2.78%   |
| Nvidia                            | 30       | 1.94%   |
| Samsung Electronics               | 17       | 1.1%    |
| Marvell Technology Group          | 11       | 0.71%   |
| ASIX Electronics                  | 10       | 0.65%   |
| Xiaomi                            | 9        | 0.58%   |
| Broadcom Limited                  | 8        | 0.52%   |
| Huawei Technologies               | 7        | 0.45%   |
| Aquantia                          | 7        | 0.45%   |
| OPPO Electronics                  | 4        | 0.26%   |
| MediaTek                          | 4        | 0.26%   |
| DisplayLink                       | 4        | 0.26%   |
| VIA Technologies                  | 2        | 0.13%   |
| TP-Link                           | 2        | 0.13%   |
| Sundance Technology Inc / IC Plus | 2        | 0.13%   |
| Motorola PCS                      | 2        | 0.13%   |
| D-Link System                     | 2        | 0.13%   |
| Research In Motion                | 1        | 0.06%   |
| Qualcomm                          | 1        | 0.06%   |
| JMicron Technology                | 1        | 0.06%   |
| ICS Advent                        | 1        | 0.06%   |
| HMD Global                        | 1        | 0.06%   |
| Google                            | 1        | 0.06%   |
| ASUSTek Computer                  | 1        | 0.06%   |
| Apple                             | 1        | 0.06%   |
| Accton Technology                 | 1        | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 689      | 43.58%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 81       | 5.12%   |
| Realtek RTL8125 2.5GbE Controller                                      | 74       | 4.68%   |
| Intel I211 Gigabit Network Connection                                  | 60       | 3.8%    |
| Intel Ethernet Connection I217-LM                                      | 56       | 3.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 55       | 3.48%   |
| Intel Ethernet Connection (2) I219-V                                   | 43       | 2.72%   |
| Intel Ethernet Controller I225-V                                       | 36       | 2.28%   |
| Intel Ethernet Connection I217-V                                       | 25       | 1.58%   |
| Nvidia MCP61 Ethernet                                                  | 20       | 1.27%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 18       | 1.14%   |
| Intel 82579V Gigabit Network Connection                                | 17       | 1.08%   |
| Intel Ethernet Connection (7) I219-V                                   | 15       | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                                  | 14       | 0.89%   |
| Intel Ethernet Connection (2) I218-V                                   | 14       | 0.89%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 13       | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 12       | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 10       | 0.63%   |
| Intel 82574L Gigabit Network Connection                                | 10       | 0.63%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 10       | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 9        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 9        | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8        | 0.51%   |
| Intel Ethernet Connection (12) I219-V                                  | 8        | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 8        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 7        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 7        | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                                  | 7        | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 7        | 0.44%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7        | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 6        | 0.38%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 6        | 0.38%   |
| Intel 82578DM Gigabit Network Connection                               | 6        | 0.38%   |
| Intel 82578DC Gigabit Network Connection                               | 6        | 0.38%   |
| Huawei VTR-L09                                                         | 6        | 0.38%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 6        | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 5        | 0.32%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 5        | 0.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 5        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1443     | 64.97%  |
| WiFi     | 759      | 34.17%  |
| Modem    | 14       | 0.63%   |
| Unknown  | 5        | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1086     | 70.66%  |
| WiFi     | 448      | 29.15%  |
| Unknown  | 2        | 0.13%   |
| Modem    | 1        | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 941      | 63.93%  |
| 2     | 460      | 31.25%  |
| 3     | 51       | 3.46%   |
| 0     | 15       | 1.02%   |
| 5     | 2        | 0.14%   |
| 4     | 2        | 0.14%   |
| 7     | 1        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 971      | 65.39%  |
| Yes  | 514      | 34.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 193      | 37.19%  |
| Cambridge Silicon Radio         | 103      | 19.85%  |
| Realtek Semiconductor           | 72       | 13.87%  |
| Broadcom                        | 30       | 5.78%   |
| ASUSTek Computer                | 24       | 4.62%   |
| Qualcomm Atheros Communications | 18       | 3.47%   |
| IMC Networks                    | 14       | 2.7%    |
| MediaTek                        | 12       | 2.31%   |
| TP-Link                         | 8        | 1.54%   |
| Apple                           | 8        | 1.54%   |
| Dynex                           | 5        | 0.96%   |
| Foxconn / Hon Hai               | 4        | 0.77%   |
| Realtek                         | 3        | 0.58%   |
| Lite-On Technology              | 3        | 0.58%   |
| Integrated System Solution      | 3        | 0.58%   |
| Belkin Components               | 3        | 0.58%   |
| Actions                         | 3        | 0.58%   |
| Unknown                         | 3        | 0.58%   |
| Dell                            | 2        | 0.39%   |
| Sitecom Europe                  | 1        | 0.19%   |
| Ralink                          | 1        | 0.19%   |
| National Semiconductor          | 1        | 0.19%   |
| Micro Star International        | 1        | 0.19%   |
| Marvell Semiconductor           | 1        | 0.19%   |
| Logitech                        | 1        | 0.19%   |
| Edimax Technology               | 1        | 0.19%   |
| D-Link System                   | 1        | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 103      | 19.85%  |
| Realtek Bluetooth Radio                                  | 58       | 11.18%  |
| Intel AX200 Bluetooth                                    | 46       | 8.86%   |
| Intel Bluetooth wireless interface                       | 36       | 6.94%   |
| Intel AX210 Bluetooth                                    | 29       | 5.59%   |
| Intel Wireless-AC 3168 Bluetooth                         | 24       | 4.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 18       | 3.47%   |
| Intel AX201 Bluetooth                                    | 13       | 2.5%    |
| MediaTek Wireless_Device                                 | 12       | 2.31%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 12       | 2.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 11       | 2.12%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 11       | 2.12%   |
| IMC Networks Bluetooth Radio                             | 9        | 1.73%   |
| TP-Link UB500 Adapter                                    | 8        | 1.54%   |
| Intel Bluetooth Device                                   | 8        | 1.54%   |
| Realtek  Bluetooth 4.2 Adapter                           | 6        | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 5        | 0.96%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 5        | 0.96%   |
| Apple Bluetooth Host Controller                          | 5        | 0.96%   |
| Realtek 802.11ac WLAN Adapter                            | 4        | 0.77%   |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 0.77%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 4        | 0.77%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 4        | 0.77%   |
| ASUS Bluetooth Radio                                     | 4        | 0.77%   |
| ASUS ASUS USB-BT500                                      | 4        | 0.77%   |
| Realtek RTL8821A Bluetooth                               | 3        | 0.58%   |
| Realtek Bluetooth Radio                                  | 3        | 0.58%   |
| Lite-On Bluetooth Device                                 | 3        | 0.58%   |
| Intel AX211 Bluetooth                                    | 3        | 0.58%   |
| IMC Networks Wireless_Device                             | 3        | 0.58%   |
| Foxconn / Hon Hai Wireless_Device                        | 3        | 0.58%   |
| Broadcom HP Portable Bumble Bee                          | 3        | 0.58%   |
| Broadcom Bluetooth 2.0+eDR dongle                        | 3        | 0.58%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 3        | 0.58%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 3        | 0.58%   |
| ASUS Qualcomm Bluetooth 4.1                              | 3        | 0.58%   |
| Actions general adapter                                  | 3        | 0.58%   |
| Unknown                                                  | 3        | 0.58%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 2        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 948      | 38.88%  |
| AMD                                          | 625      | 25.64%  |
| Nvidia                                       | 542      | 22.23%  |
| C-Media Electronics                          | 58       | 2.38%   |
| Creative Labs                                | 26       | 1.07%   |
| Logitech                                     | 17       | 0.7%    |
| JMTek                                        | 17       | 0.7%    |
| ASUSTek Computer                             | 16       | 0.66%   |
| Kingston Technology                          | 15       | 0.62%   |
| Generalplus Technology                       | 12       | 0.49%   |
| Texas Instruments                            | 9        | 0.37%   |
| VIA Technologies                             | 8        | 0.33%   |
| Razer USA                                    | 8        | 0.33%   |
| Plantronics                                  | 8        | 0.33%   |
| Creative Technology                          | 7        | 0.29%   |
| Micro Star International                     | 6        | 0.25%   |
| GN Netcom                                    | 6        | 0.25%   |
| Zoran Co. Personal Media Division (Nogatech) | 5        | 0.21%   |
| Tenx Technology                              | 5        | 0.21%   |
| Realtek Semiconductor                        | 5        | 0.21%   |
| KTMicro                                      | 4        | 0.16%   |
| Focusrite-Novation                           | 4        | 0.16%   |
| BR25                                         | 4        | 0.16%   |
| SteelSeries ApS                              | 3        | 0.12%   |
| RODE Microphones                             | 3        | 0.12%   |
| Astro Gaming                                 | 3        | 0.12%   |
| Asahi Kasei Microsystems                     | 3        | 0.12%   |
| Yamaha                                       | 2        | 0.08%   |
| Sony                                         | 2        | 0.08%   |
| Samsung Electronics                          | 2        | 0.08%   |
| Microsoft                                    | 2        | 0.08%   |
| Lenovo                                       | 2        | 0.08%   |
| DSEA A/S                                     | 2        | 0.08%   |
| DCMT Technology                              | 2        | 0.08%   |
| Corsair                                      | 2        | 0.08%   |
| Cambridge Audio                              | 2        | 0.08%   |
| Blue Microphones                             | 2        | 0.08%   |
| BEHRINGER International                      | 2        | 0.08%   |
| Audio-Technica                               | 2        | 0.08%   |
| ZOOM                                         | 1        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 157      | 5.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 135      | 4.75%   |
| AMD Starship/Matisse HD Audio Controller                                          | 121      | 4.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 120      | 4.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 109      | 3.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 91       | 3.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 87       | 3.06%   |
| AMD Family 17h/19h HD Audio Controller                                            | 80       | 2.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 65       | 2.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 60       | 2.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 57       | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 55       | 1.93%   |
| Intel 200 Series PCH HD Audio                                                     | 53       | 1.86%   |
| AMD FCH Azalia Controller                                                         | 52       | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                        | 44       | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 42       | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 37       | 1.3%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 35       | 1.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 34       | 1.2%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 34       | 1.2%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 33       | 1.16%   |
| Nvidia TU116 High Definition Audio Controller                                     | 32       | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                                     | 31       | 1.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 30       | 1.05%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 30       | 1.05%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 28       | 0.98%   |
| Nvidia GF119 HDMI Audio Controller                                                | 27       | 0.95%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 27       | 0.95%   |
| Nvidia High Definition Audio Controller                                           | 25       | 0.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 25       | 0.88%   |
| AMD Navi 10 HDMI Audio                                                            | 24       | 0.84%   |
| Nvidia GP106 High Definition Audio Controller                                     | 23       | 0.81%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 23       | 0.81%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 22       | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                                     | 21       | 0.74%   |
| Nvidia MCP61 High Definition Audio                                                | 21       | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                                     | 21       | 0.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 21       | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                                     | 20       | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 20       | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 36       | 16.29%  |
| Kingston            | 30       | 13.57%  |
| Samsung Electronics | 26       | 11.76%  |
| Corsair             | 22       | 9.95%   |
| G.Skill             | 20       | 9.05%   |
| SK hynix            | 18       | 8.14%   |
| Crucial             | 17       | 7.69%   |
| Team                | 11       | 4.98%   |
| Micron Technology   | 9        | 4.07%   |
| Unknown             | 5        | 2.26%   |
| Nanya Technology    | 3        | 1.36%   |
| A-DATA Technology   | 3        | 1.36%   |
| Wilk                | 2        | 0.9%    |
| Unifosa             | 2        | 0.9%    |
| Ramaxel Technology  | 2        | 0.9%    |
| Patriot             | 2        | 0.9%    |
| Avant               | 2        | 0.9%    |
| Transcend           | 1        | 0.45%   |
| Timetec             | 1        | 0.45%   |
| SUPER KINGSTEK      | 1        | 0.45%   |
| Qimonda             | 1        | 0.45%   |
| Patriot Memory      | 1        | 0.45%   |
| Goldkey             | 1        | 0.45%   |
| Golden Empire       | 1        | 0.45%   |
| F7852C80            | 1        | 0.45%   |
| Elpida              | 1        | 0.45%   |
| Apacer              | 1        | 0.45%   |
| AMD                 | 1        | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 6        | 2.48%   |
| Unknown                                                 | 5        | 2.07%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s     | 3        | 1.24%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s    | 3        | 1.24%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 1.24%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 3        | 1.24%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 2        | 0.83%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 0.83%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2        | 0.83%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 2        | 0.83%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s     | 2        | 0.83%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3200MT/s      | 2        | 0.83%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1067MT/s      | 2        | 0.83%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.83%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 0.83%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s  | 2        | 0.83%   |
| Samsung RAM M378B1G73DB0-CK0 8192MB DIMM DDR3 2133MT/s  | 2        | 0.83%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s     | 2        | 0.83%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 2        | 0.83%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 2        | 0.83%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 0.83%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s     | 2        | 0.83%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 0.83%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 2        | 0.83%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 2        | 0.83%   |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3600MT/s   | 2        | 0.83%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s  | 2        | 0.83%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s | 2        | 0.83%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s   | 2        | 0.83%   |
| Wilk RAM IRX3200D464L16A/16G 16384MB DIMM DDR4 3200MT/s | 1        | 0.41%   |
| Wilk RAM GX3236D464S/8GSBS1 8192MB DIMM DDR4 3467MT/s   | 1        | 0.41%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM SDRAM                       | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s               | 1        | 0.41%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.41%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 0.41%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 0.41%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                  | 1        | 0.41%   |
| Unknown RAM Module 512MB DIMM 667MT/s                   | 1        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 85       | 43.37%  |
| DDR3    | 72       | 36.73%  |
| Unknown | 12       | 6.12%   |
| SDRAM   | 9        | 4.59%   |
| DDR2    | 8        | 4.08%   |
| DDR5    | 4        | 2.04%   |
| DDR     | 3        | 1.53%   |
| LPDDR4  | 2        | 1.02%   |
| DRAM    | 1        | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 179      | 93.23%  |
| SODIMM       | 10       | 5.21%   |
| Row Of Chips | 2        | 1.04%   |
| FB-DIMM      | 1        | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 87       | 40.47%  |
| 4096  | 56       | 26.05%  |
| 2048  | 25       | 11.63%  |
| 16384 | 23       | 10.7%   |
| 32768 | 16       | 7.44%   |
| 1024  | 7        | 3.26%   |
| 512   | 1        | 0.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 39       | 18.22%  |
| 1333    | 27       | 12.62%  |
| 3200    | 22       | 10.28%  |
| 3600    | 15       | 7.01%   |
| 2667    | 10       | 4.67%   |
| 2133    | 9        | 4.21%   |
| 2400    | 7        | 3.27%   |
| 3733    | 6        | 2.8%    |
| 3000    | 6        | 2.8%    |
| 1866    | 6        | 2.8%    |
| 1800    | 6        | 2.8%    |
| 800     | 6        | 2.8%    |
| Unknown | 5        | 2.34%   |
| 4800    | 3        | 1.4%    |
| 3866    | 3        | 1.4%    |
| 3800    | 3        | 1.4%    |
| 3400    | 3        | 1.4%    |
| 2666    | 3        | 1.4%    |
| 1867    | 3        | 1.4%    |
| 667     | 3        | 1.4%    |
| 3666    | 2        | 0.93%   |
| 3500    | 2        | 0.93%   |
| 3466    | 2        | 0.93%   |
| 1066    | 2        | 0.93%   |
| 400     | 2        | 0.93%   |
| 6000    | 1        | 0.47%   |
| 5354    | 1        | 0.47%   |
| 5200    | 1        | 0.47%   |
| 4266    | 1        | 0.47%   |
| 4000    | 1        | 0.47%   |
| 3933    | 1        | 0.47%   |
| 3534    | 1        | 0.47%   |
| 3467    | 1        | 0.47%   |
| 3066    | 1        | 0.47%   |
| 2933    | 1        | 0.47%   |
| 2800    | 1        | 0.47%   |
| 2733    | 1        | 0.47%   |
| 2465    | 1        | 0.47%   |
| 2200    | 1        | 0.47%   |
| 2000    | 1        | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 24       | 28.92%  |
| Canon                 | 16       | 19.28%  |
| Brother Industries    | 15       | 18.07%  |
| Seiko Epson           | 11       | 13.25%  |
| Samsung Electronics   | 11       | 13.25%  |
| Lexmark International | 2        | 2.41%   |
| Ricoh                 | 1        | 1.2%    |
| QinHeng Electronics   | 1        | 1.2%    |
| Konica Minolta        | 1        | 1.2%    |
| GG IMAGE              | 1        | 1.2%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson L3110 Series                     | 2        | 2.41%   |
| Samsung M2070 Series                         | 2        | 2.41%   |
| Samsung C460 Series                          | 2        | 2.41%   |
| HP OfficeJet 6950                            | 2        | 2.41%   |
| HP LaserJet Professional P1102w              | 2        | 2.41%   |
| HP ENVY 4520 series                          | 2        | 2.41%   |
| HP DeskJet 2700 series                       | 2        | 2.41%   |
| HP DeskJet 2130 series                       | 2        | 2.41%   |
| Canon PIXMA MG3600 Series                    | 2        | 2.41%   |
| Canon LiDE 400                               | 2        | 2.41%   |
| Seiko Epson XP-7100 Series                   | 1        | 1.2%    |
| Seiko Epson XP-205 207 Series                | 1        | 1.2%    |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 1.2%    |
| Seiko Epson L805 Series                      | 1        | 1.2%    |
| Seiko Epson L355 Series                      | 1        | 1.2%    |
| Seiko Epson ET-3850 Series                   | 1        | 1.2%    |
| Seiko Epson ET-2820 Series                   | 1        | 1.2%    |
| Seiko Epson ET-2800 Series                   | 1        | 1.2%    |
| Seiko Epson ET-2710 Series                   | 1        | 1.2%    |
| Samsung SCX-483x 5x3x Series                 | 1        | 1.2%    |
| Samsung SCX-4623 Series                      | 1        | 1.2%    |
| Samsung SCX-4200 series                      | 1        | 1.2%    |
| Samsung SCX-3400 Series                      | 1        | 1.2%    |
| Samsung ML-2950 Series                       | 1        | 1.2%    |
| Samsung ML-216x Series Laser Printer         | 1        | 1.2%    |
| Samsung M2020 Series                         | 1        | 1.2%    |
| Ricoh SP 112SU                               | 1        | 1.2%    |
| QinHeng CH340S                               | 1        | 1.2%    |
| Lexmark International MX310dn                | 1        | 1.2%    |
| Lexmark International Laser Printer E232     | 1        | 1.2%    |
| Konica Minolta PagePro 1380MF                | 1        | 1.2%    |
| HP Smart Tank 510 series                     | 1        | 1.2%    |
| HP PSC 1100 series                           | 1        | 1.2%    |
| HP Officejet 6600                            | 1        | 1.2%    |
| HP OfficeJet 5600 (USBHUB)                   | 1        | 1.2%    |
| HP OfficeJet 4650 series                     | 1        | 1.2%    |
| HP LaserJet Pro M148-M149                    | 1        | 1.2%    |
| HP LaserJet 1320                             | 1        | 1.2%    |
| HP ENVY Photo 7800 series                    | 1        | 1.2%    |
| HP ENVY 5000 series                          | 1        | 1.2%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 10       | 71.43%  |
| Hewlett-Packard | 3        | 21.43%  |
| Seiko Epson     | 1        | 7.14%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon CanoScan LiDE 220                | 2        | 13.33%  |
| Seiko Epson Scanner                    | 1        | 6.67%   |
| HP ScanJet 2400c                       | 1        | 6.67%   |
| HP Scanjet 200                         | 1        | 6.67%   |
| HP PSC 1200                            | 1        | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20     | 1        | 6.67%   |
| Canon CanoScan LiDE 90                 | 1        | 6.67%   |
| Canon CanoScan LiDE 60                 | 1        | 6.67%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1        | 6.67%   |
| Canon CanoScan LiDE 110                | 1        | 6.67%   |
| Canon CanoScan LiDE 100                | 1        | 6.67%   |
| Canon CanoScan D660U                   | 1        | 6.67%   |
| Canon CanoScan 8800F                   | 1        | 6.67%   |
| Canon CanoScan 5600F                   | 1        | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 67       | 27.57%  |
| Microdia                      | 24       | 9.88%   |
| Microsoft                     | 16       | 6.58%   |
| Sunplus Innovation Technology | 15       | 6.17%   |
| Generalplus Technology        | 10       | 4.12%   |
| Apple                         | 10       | 4.12%   |
| Samsung Electronics           | 8        | 3.29%   |
| Chicony Electronics           | 8        | 3.29%   |
| ARC International             | 7        | 2.88%   |
| Z-Star Microelectronics       | 5        | 2.06%   |
| Jieli Technology              | 5        | 2.06%   |
| Realtek Semiconductor         | 4        | 1.65%   |
| Razer USA                     | 4        | 1.65%   |
| Creative Technology           | 4        | 1.65%   |
| Tobii Technology AB           | 3        | 1.23%   |
| GEMBIRD                       | 3        | 1.23%   |
| A4Tech                        | 3        | 1.23%   |
| 2M UVC CAMERA                 | 3        | 1.23%   |
| Xiongmai                      | 2        | 0.82%   |
| WaveRider Communications      | 2        | 0.82%   |
| Trust                         | 2        | 0.82%   |
| Suyin                         | 2        | 0.82%   |
| MacroSilicon                  | 2        | 0.82%   |
| lihappe8                      | 2        | 0.82%   |
| IMC Networks                  | 2        | 0.82%   |
| Guillemot                     | 2        | 0.82%   |
| Genesys Logic                 | 2        | 0.82%   |
| Cubeternet                    | 2        | 0.82%   |
| Aveo Technology               | 2        | 0.82%   |
| Xiaomi                        | 1        | 0.41%   |
| Unknown                       | 1        | 0.41%   |
| Teslong Camera                | 1        | 0.41%   |
| Sweex                         | 1        | 0.41%   |
| Sunplus Technology            | 1        | 0.41%   |
| Sonix Technology              | 1        | 0.41%   |
| Silicon Motion                | 1        | 0.41%   |
| Ruision                       | 1        | 0.41%   |
| Pixart Imaging                | 1        | 0.41%   |
| Lenovo                        | 1        | 0.41%   |
| KYE Systems (Mouse Systems)   | 1        | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 17       | 6.94%   |
| Logitech HD Pro Webcam C920             | 13       | 5.31%   |
| Microsoft LifeCam HD-3000               | 9        | 3.67%   |
| Microdia USB 2.0 Camera                 | 9        | 3.67%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 9        | 3.67%   |
| Samsung Galaxy series, misc. (MTP mode) | 8        | 3.27%   |
| ARC International Camera                | 7        | 2.86%   |
| Sunplus PC Camera                       | 6        | 2.45%   |
| Microdia Webcam Vitade AF               | 6        | 2.45%   |
| Logitech HD Webcam C615                 | 6        | 2.45%   |
| Logitech C920 PRO HD Webcam             | 5        | 2.04%   |
| Jieli USB PHY 2.0                       | 5        | 2.04%   |
| Sunplus HD 720P webcam                  | 4        | 1.63%   |
| Razer USA Gaming Webcam [Kiyo]          | 4        | 1.63%   |
| Generalplus CAMERA - UVC                | 4        | 1.63%   |
| Generalplus 808 Camera                  | 4        | 1.63%   |
| Chicony HP High Definition 1MP Webcam   | 4        | 1.63%   |
| Tobii AB EyeChip                        | 3        | 1.22%   |
| Microsoft LifeCam VX-500 [1357]         | 3        | 1.22%   |
| Microdia Integrated Camera              | 3        | 1.22%   |
| Logitech Webcam C925e                   | 3        | 1.22%   |
| Logitech HD Webcam C910                 | 3        | 1.22%   |
| Chicony CNF8050 Webcam                  | 3        | 1.22%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam     | 3        | 1.22%   |
| Z-Star Venus USB2.0 Camera              | 2        | 0.82%   |
| Z-Star Integrated Camera                | 2        | 0.82%   |
| Xiongmai web camera                     | 2        | 0.82%   |
| WaveRider USB Live camera               | 2        | 0.82%   |
| Suyin HD WebCam                         | 2        | 0.82%   |
| Microsoft MicrosoftÂ LifeCam Cinema    | 2        | 0.82%   |
| Microdia USB Live camera                | 2        | 0.82%   |
| Logitech Webcam C310                    | 2        | 0.82%   |
| Logitech QuickCam Pro for Notebooks     | 2        | 0.82%   |
| Logitech HD Webcam C525                 | 2        | 0.82%   |
| Logitech C922 Pro Stream Webcam         | 2        | 0.82%   |
| lihappe8 USB 2.0 Camera                 | 2        | 0.82%   |
| Generalplus GENERAL WEBCAM              | 2        | 0.82%   |
| GEMBIRD USB2.0 PC CAMERA                | 2        | 0.82%   |
| Creative Live! Cam Sync HD [VF0770]     | 2        | 0.82%   |
| Aveo USB2.0 Camera                      | 2        | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 2        | 66.67%  |
| AuthenTec             | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor        | 2        | 66.67%  |
| AuthenTec AES2501 Fingerprint Sensor | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2        | 16.67%  |
| Advanced Card Systems             | 2        | 16.67%  |
| VASCO Data Security International | 1        | 8.33%   |
| SCM Microsystems                  | 1        | 8.33%   |
| Reiner SCT Kartensysteme          | 1        | 8.33%   |
| Jing-Mold Enterprise              | 1        | 8.33%   |
| Gemalto (was Gemplus)             | 1        | 8.33%   |
| Fujitsu Siemens Computers         | 1        | 8.33%   |
| Chicony Electronics               | 1        | 8.33%   |
| Alcor Micro                       | 1        | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                 | 2        | 16.67%  |
| VASCO Data Security International Digipass 905 SmartCard Reader   | 1        | 8.33%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader            | 1        | 8.33%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                   | 1        | 8.33%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 8.33%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                 | 1        | 8.33%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                     | 1        | 8.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard              | 1        | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                               | 1        | 8.33%   |
| Advanced Card Systems ACR39U                                      | 1        | 8.33%   |
| Advanced Card Systems ACR1281 1S Dual Reader                      | 1        | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1184     | 79.46%  |
| 1     | 269      | 18.05%  |
| 2     | 32       | 2.15%   |
| 3     | 4        | 0.27%   |
| 4     | 1        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 132      | 39.64%  |
| Net/wireless             | 128      | 38.44%  |
| Communication controller | 14       | 4.2%    |
| Multimedia controller    | 10       | 3%      |
| Unassigned class         | 9        | 2.7%    |
| Chipcard                 | 8        | 2.4%    |
| Storage/raid             | 7        | 2.1%    |
| Bluetooth                | 5        | 1.5%    |
| Modem                    | 4        | 1.2%    |
| Sound                    | 3        | 0.9%    |
| Fingerprint reader       | 3        | 0.9%    |
| Network                  | 2        | 0.6%    |
| Net/ethernet             | 2        | 0.6%    |
| Card reader              | 2        | 0.6%    |
| Camera                   | 2        | 0.6%    |
| Storage/ide              | 1        | 0.3%    |
| Dvb card                 | 1        | 0.3%    |

