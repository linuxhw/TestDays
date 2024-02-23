Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

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

Total: 6102

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-F4218FC8 DVT            | All in one  | [7e9ecedb98](https://linux-hardware.org/?probe=7e9ecedb98) | Feb 02, 2024 |
| Gigabyte      | GA-990FXA-UD7               | Desktop     | [66768ccdf7](https://linux-hardware.org/?probe=66768ccdf7) | Feb 02, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [3074b7c2a6](https://linux-hardware.org/?probe=3074b7c2a6) | Feb 02, 2024 |
| Gigabyte      | GA-990FXA-UD7               | Desktop     | [4726161c35](https://linux-hardware.org/?probe=4726161c35) | Feb 02, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [62dc25b8b6](https://linux-hardware.org/?probe=62dc25b8b6) | Feb 02, 2024 |
| Apple         | Mac-F4218FC8 DVT            | All in one  | [9b97e0a028](https://linux-hardware.org/?probe=9b97e0a028) | Feb 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [4fa0768f2b](https://linux-hardware.org/?probe=4fa0768f2b) | Feb 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [69b18742b6](https://linux-hardware.org/?probe=69b18742b6) | Feb 01, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [3cedb3c573](https://linux-hardware.org/?probe=3cedb3c573) | Feb 01, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [45207cf034](https://linux-hardware.org/?probe=45207cf034) | Jan 31, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [8ddfa07beb](https://linux-hardware.org/?probe=8ddfa07beb) | Jan 31, 2024 |
| HP            | ProBook 6570b               | Notebook    | [20537302e6](https://linux-hardware.org/?probe=20537302e6) | Jan 31, 2024 |
| Huanan        | X99-8M-F V1.4               | Desktop     | [7625188b91](https://linux-hardware.org/?probe=7625188b91) | Jan 31, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d1065a1aca](https://linux-hardware.org/?probe=d1065a1aca) | Jan 30, 2024 |
| Acer          | Aspire 9420                 | Notebook    | [d0c7154097](https://linux-hardware.org/?probe=d0c7154097) | Jan 30, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [073f673b78](https://linux-hardware.org/?probe=073f673b78) | Jan 29, 2024 |
| Dell          | 0RY007                      | Desktop     | [151f303198](https://linux-hardware.org/?probe=151f303198) | Jan 29, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [3cffc989aa](https://linux-hardware.org/?probe=3cffc989aa) | Jan 29, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [31ce3ae751](https://linux-hardware.org/?probe=31ce3ae751) | Jan 29, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [292b1b06ca](https://linux-hardware.org/?probe=292b1b06ca) | Jan 28, 2024 |
| ASRock        | G31M-S                      | Desktop     | [3030db55a6](https://linux-hardware.org/?probe=3030db55a6) | Jan 28, 2024 |
| Acer          | Aspire M3-581G              | Notebook    | [b91416ad7c](https://linux-hardware.org/?probe=b91416ad7c) | Jan 28, 2024 |
| MSI           | Z490-A PRO                  | Desktop     | [a851d2d2fe](https://linux-hardware.org/?probe=a851d2d2fe) | Jan 28, 2024 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [fd0ab9a9ac](https://linux-hardware.org/?probe=fd0ab9a9ac) | Jan 28, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [47f8ef1ba6](https://linux-hardware.org/?probe=47f8ef1ba6) | Jan 27, 2024 |
| Dell          | Latitude E6430              | Notebook    | [237d6e4d3e](https://linux-hardware.org/?probe=237d6e4d3e) | Jan 27, 2024 |
| Dell          | 0Y5DDC A00                  | Desktop     | [1912506274](https://linux-hardware.org/?probe=1912506274) | Jan 26, 2024 |
| Quanta        | XV1                         | All in one  | [b39049cedd](https://linux-hardware.org/?probe=b39049cedd) | Jan 26, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [1abc8128a3](https://linux-hardware.org/?probe=1abc8128a3) | Jan 26, 2024 |
| HP            | 3647h                       | Desktop     | [14bc5e74bc](https://linux-hardware.org/?probe=14bc5e74bc) | Jan 26, 2024 |
| Dell          | 048DY8 A01                  | Desktop     | [d5e6914489](https://linux-hardware.org/?probe=d5e6914489) | Jan 26, 2024 |
| Toshiba       | Satellite R630              | Notebook    | [c888a8f4d5](https://linux-hardware.org/?probe=c888a8f4d5) | Jan 24, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [18de9933d4](https://linux-hardware.org/?probe=18de9933d4) | Jan 24, 2024 |
| Alienware     | 07W25T A01                  | Desktop     | [538d2e2b5f](https://linux-hardware.org/?probe=538d2e2b5f) | Jan 24, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [214ebad454](https://linux-hardware.org/?probe=214ebad454) | Jan 24, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [f2a415adc9](https://linux-hardware.org/?probe=f2a415adc9) | Jan 24, 2024 |
| Dell          | 0D28YY A00                  | Desktop     | [8d8d8005b1](https://linux-hardware.org/?probe=8d8d8005b1) | Jan 23, 2024 |
| HP            | ZBook Studio G5             | Notebook    | [114d79aa75](https://linux-hardware.org/?probe=114d79aa75) | Jan 23, 2024 |
| Dell          | Latitude E5420              | Notebook    | [8347319849](https://linux-hardware.org/?probe=8347319849) | Jan 23, 2024 |
| HP            | Pavilion g4                 | Notebook    | [f0cc56ebca](https://linux-hardware.org/?probe=f0cc56ebca) | Jan 23, 2024 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [eed9a3591f](https://linux-hardware.org/?probe=eed9a3591f) | Jan 23, 2024 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [8479b771e4](https://linux-hardware.org/?probe=8479b771e4) | Jan 23, 2024 |
| HP            | 8523 A01                    | Mini pc     | [cfec865f42](https://linux-hardware.org/?probe=cfec865f42) | Jan 23, 2024 |
| HP            | 8523 A01                    | Mini pc     | [ad950a4d7d](https://linux-hardware.org/?probe=ad950a4d7d) | Jan 23, 2024 |
| Google        | Kefka                       | Notebook    | [6cb0b95d02](https://linux-hardware.org/?probe=6cb0b95d02) | Jan 22, 2024 |
| HP            | Notebook                    | Notebook    | [8359e2a5dd](https://linux-hardware.org/?probe=8359e2a5dd) | Jan 22, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [8dacf655a4](https://linux-hardware.org/?probe=8dacf655a4) | Jan 22, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [c3f3bb78c6](https://linux-hardware.org/?probe=c3f3bb78c6) | Jan 22, 2024 |
| HP            | ProBook 430 G4              | Notebook    | [046036e7e3](https://linux-hardware.org/?probe=046036e7e3) | Jan 22, 2024 |
| HP            | ProBook 430 G4              | Notebook    | [262a8552de](https://linux-hardware.org/?probe=262a8552de) | Jan 22, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [a0c06abcbd](https://linux-hardware.org/?probe=a0c06abcbd) | Jan 22, 2024 |
| Dell          | Latitude 5490               | Notebook    | [ebc5bed33f](https://linux-hardware.org/?probe=ebc5bed33f) | Jan 22, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [41a378391c](https://linux-hardware.org/?probe=41a378391c) | Jan 22, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [a8893e7742](https://linux-hardware.org/?probe=a8893e7742) | Jan 22, 2024 |
| Alienware     | 07W25T A01                  | Desktop     | [2a7a6fd405](https://linux-hardware.org/?probe=2a7a6fd405) | Jan 22, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [af0244605f](https://linux-hardware.org/?probe=af0244605f) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [024b0a26f9](https://linux-hardware.org/?probe=024b0a26f9) | Jan 21, 2024 |
| MSI           | 760GM-P34                   | Desktop     | [3eb4ebb737](https://linux-hardware.org/?probe=3eb4ebb737) | Jan 21, 2024 |
| Toshiba       | Satellite L640              | Notebook    | [7478e6971b](https://linux-hardware.org/?probe=7478e6971b) | Jan 21, 2024 |
| HP            | Notebook                    | Notebook    | [2dcfaac5fd](https://linux-hardware.org/?probe=2dcfaac5fd) | Jan 21, 2024 |
| Foxconn       | 946 7MA Series              | Desktop     | [40261803d6](https://linux-hardware.org/?probe=40261803d6) | Jan 21, 2024 |
| Acer          | TravelMate Spin P614RN-5    | Convertible | [875bdb70a2](https://linux-hardware.org/?probe=875bdb70a2) | Jan 20, 2024 |
| Sony          | VGN-NS11Z_S                 | Notebook    | [64fa921691](https://linux-hardware.org/?probe=64fa921691) | Jan 20, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [4257aab3ea](https://linux-hardware.org/?probe=4257aab3ea) | Jan 20, 2024 |
| Dell          | Inspiron 3531               | Notebook    | [afc0f1a968](https://linux-hardware.org/?probe=afc0f1a968) | Jan 20, 2024 |
| AZW           | SER                         | Mini pc     | [c91aa206d4](https://linux-hardware.org/?probe=c91aa206d4) | Jan 20, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [becbec6f26](https://linux-hardware.org/?probe=becbec6f26) | Jan 20, 2024 |
| Acer          | Aspire E5-551G              | Notebook    | [c4bd469e8d](https://linux-hardware.org/?probe=c4bd469e8d) | Jan 19, 2024 |
| Acer          | Aspire E5-523               | Notebook    | [02378722b6](https://linux-hardware.org/?probe=02378722b6) | Jan 19, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [c3733ef1e3](https://linux-hardware.org/?probe=c3733ef1e3) | Jan 18, 2024 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [518ca600f6](https://linux-hardware.org/?probe=518ca600f6) | Jan 18, 2024 |
| Dell          | 0GTK4K A02                  | Desktop     | [a4aef81553](https://linux-hardware.org/?probe=a4aef81553) | Jan 18, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [ae841d1af4](https://linux-hardware.org/?probe=ae841d1af4) | Jan 17, 2024 |
| HP            | ZBook 14u G6                | Notebook    | [668a33bda1](https://linux-hardware.org/?probe=668a33bda1) | Jan 17, 2024 |
| Toshiba       | Satellite A665              | Notebook    | [66c11ee330](https://linux-hardware.org/?probe=66c11ee330) | Jan 17, 2024 |
| Toshiba       | Satellite C850-B820         | Notebook    | [321a8ae666](https://linux-hardware.org/?probe=321a8ae666) | Jan 17, 2024 |
| Toshiba       | Satellite A665              | Notebook    | [640deb41af](https://linux-hardware.org/?probe=640deb41af) | Jan 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [0e05a50329](https://linux-hardware.org/?probe=0e05a50329) | Jan 16, 2024 |
| HP            | Pavilion 17                 | Notebook    | [3594afe0d4](https://linux-hardware.org/?probe=3594afe0d4) | Jan 16, 2024 |
| Intel         | Unknown                     | Notebook    | [dfd975eff3](https://linux-hardware.org/?probe=dfd975eff3) | Jan 15, 2024 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [4c5f54d07e](https://linux-hardware.org/?probe=4c5f54d07e) | Jan 15, 2024 |
| Dell          | OptiPlex 7050               | Desktop     | [f0c2b782ff](https://linux-hardware.org/?probe=f0c2b782ff) | Jan 15, 2024 |
| Intel         | X99-P4 V5.0                 | Desktop     | [574a971f93](https://linux-hardware.org/?probe=574a971f93) | Jan 14, 2024 |
| ASUSTek       | Z170-P                      | Desktop     | [b3d8c3265d](https://linux-hardware.org/?probe=b3d8c3265d) | Jan 14, 2024 |
| Lenovo        | ThinkCentre M70E 0830W36    | Desktop     | [f28fd8d379](https://linux-hardware.org/?probe=f28fd8d379) | Jan 14, 2024 |
| Sony          | VGN-NS11Z_S                 | Notebook    | [863785eef9](https://linux-hardware.org/?probe=863785eef9) | Jan 13, 2024 |
| Quanta        | XV1                         | All in one  | [112581cd19](https://linux-hardware.org/?probe=112581cd19) | Jan 13, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [75a54dcccf](https://linux-hardware.org/?probe=75a54dcccf) | Jan 13, 2024 |
| Toshiba       | Satellite R630              | Notebook    | [0e83a06873](https://linux-hardware.org/?probe=0e83a06873) | Jan 13, 2024 |
| Acer          | Aspire V5-573G              | Notebook    | [09ddfeab43](https://linux-hardware.org/?probe=09ddfeab43) | Jan 12, 2024 |
| HP            | 3647h                       | Desktop     | [e9767a4e96](https://linux-hardware.org/?probe=e9767a4e96) | Jan 12, 2024 |
| HP            | 3647h                       | Desktop     | [39414040e7](https://linux-hardware.org/?probe=39414040e7) | Jan 12, 2024 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [de5d52bcd5](https://linux-hardware.org/?probe=de5d52bcd5) | Jan 12, 2024 |
| Gateway       | SX2851                      | Desktop     | [0cbcae7c27](https://linux-hardware.org/?probe=0cbcae7c27) | Jan 11, 2024 |
| Acer          | Veriton X490G               | Desktop     | [1110362d9a](https://linux-hardware.org/?probe=1110362d9a) | Jan 11, 2024 |
| ASUSTek       | N56JR                       | Notebook    | [513c456753](https://linux-hardware.org/?probe=513c456753) | Jan 11, 2024 |
| Dell          | 0T1D10 A01                  | Desktop     | [0c1256487e](https://linux-hardware.org/?probe=0c1256487e) | Jan 11, 2024 |
| Medion        | E4251 MD61435               | Notebook    | [6a9251fa94](https://linux-hardware.org/?probe=6a9251fa94) | Jan 11, 2024 |
| HP            | Pavilion Sleekbook 14       | Notebook    | [9f54d91b95](https://linux-hardware.org/?probe=9f54d91b95) | Jan 10, 2024 |
| Toshiba       | Satellite L845              | Notebook    | [e45e9517b3](https://linux-hardware.org/?probe=e45e9517b3) | Jan 10, 2024 |
| Dell          | Inspiron 7737               | Notebook    | [ae41cf1d2f](https://linux-hardware.org/?probe=ae41cf1d2f) | Jan 10, 2024 |
| Acer          | Aspire E1-570G              | Notebook    | [2bb5dcf476](https://linux-hardware.org/?probe=2bb5dcf476) | Jan 10, 2024 |
| ASUSTek       | X200CA                      | Notebook    | [c27c1b9fc2](https://linux-hardware.org/?probe=c27c1b9fc2) | Jan 10, 2024 |
| Toshiba       | Satellite C850              | Notebook    | [38fb6d3619](https://linux-hardware.org/?probe=38fb6d3619) | Jan 09, 2024 |
| Toshiba       | Satellite C850              | Notebook    | [c6faf796f4](https://linux-hardware.org/?probe=c6faf796f4) | Jan 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [ca7b5632f4](https://linux-hardware.org/?probe=ca7b5632f4) | Jan 09, 2024 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [d5486716d1](https://linux-hardware.org/?probe=d5486716d1) | Jan 09, 2024 |
| HONOR         | BBR-WAX9                    | Notebook    | [b9d1ee2b4c](https://linux-hardware.org/?probe=b9d1ee2b4c) | Jan 08, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [6a5afb5dec](https://linux-hardware.org/?probe=6a5afb5dec) | Jan 08, 2024 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [c428c1eb3e](https://linux-hardware.org/?probe=c428c1eb3e) | Jan 08, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [50877161c2](https://linux-hardware.org/?probe=50877161c2) | Jan 08, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [cb7c295dc6](https://linux-hardware.org/?probe=cb7c295dc6) | Jan 08, 2024 |
| ASUSTek       | UL50VT                      | Notebook    | [428d20a1eb](https://linux-hardware.org/?probe=428d20a1eb) | Jan 07, 2024 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ac3aa9697a](https://linux-hardware.org/?probe=ac3aa9697a) | Jan 07, 2024 |
| Acer          | Swift SF314-511             | Notebook    | [14eac9efff](https://linux-hardware.org/?probe=14eac9efff) | Jan 07, 2024 |
| Acer          | Aspire E1-570G              | Notebook    | [3c08b1958e](https://linux-hardware.org/?probe=3c08b1958e) | Jan 07, 2024 |
| Intel         | H61                         | Desktop     | [a0d05acffb](https://linux-hardware.org/?probe=a0d05acffb) | Jan 07, 2024 |
| Dell          | Latitude E5420              | Notebook    | [40835d5737](https://linux-hardware.org/?probe=40835d5737) | Jan 07, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [b02f06751f](https://linux-hardware.org/?probe=b02f06751f) | Jan 07, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [8f181c2fb8](https://linux-hardware.org/?probe=8f181c2fb8) | Jan 07, 2024 |
| Biostar       | A320MH                      | Desktop     | [9bec9420ab](https://linux-hardware.org/?probe=9bec9420ab) | Jan 06, 2024 |
| ASUSTek       | B85M-E                      | Desktop     | [1f5304b336](https://linux-hardware.org/?probe=1f5304b336) | Jan 06, 2024 |
| ASUSTek       | B85M-E                      | Desktop     | [7c7fb3af69](https://linux-hardware.org/?probe=7c7fb3af69) | Jan 06, 2024 |
| Lenovo        | ThinkPad T520 4243F53       | Notebook    | [900bfdd9a8](https://linux-hardware.org/?probe=900bfdd9a8) | Jan 06, 2024 |
| ASRock        | G31M-S                      | Desktop     | [1b44835106](https://linux-hardware.org/?probe=1b44835106) | Jan 06, 2024 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [f9b4427f39](https://linux-hardware.org/?probe=f9b4427f39) | Jan 06, 2024 |
| Dell          | 0HN7XN A01                  | Desktop     | [f154d2ee51](https://linux-hardware.org/?probe=f154d2ee51) | Jan 06, 2024 |
| HP            | ENVY dv6                    | Notebook    | [12f54bd4e0](https://linux-hardware.org/?probe=12f54bd4e0) | Jan 06, 2024 |
| ASUSTek       | PRIME X399-A                | Desktop     | [5f016cc67b](https://linux-hardware.org/?probe=5f016cc67b) | Jan 05, 2024 |
| Dell          | 0T1D10 A01                  | Desktop     | [36fd42ae37](https://linux-hardware.org/?probe=36fd42ae37) | Jan 05, 2024 |
| Dell          | 0HN7XN A01                  | Desktop     | [91b070152e](https://linux-hardware.org/?probe=91b070152e) | Jan 05, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [37ea5af9b1](https://linux-hardware.org/?probe=37ea5af9b1) | Jan 04, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [debaccaee2](https://linux-hardware.org/?probe=debaccaee2) | Jan 04, 2024 |
| ASUSTek       | E201NA                      | Notebook    | [91cac0307a](https://linux-hardware.org/?probe=91cac0307a) | Jan 04, 2024 |
| Lenovo        | ThinkCentre M71e 3156PT5    | Desktop     | [53089d138d](https://linux-hardware.org/?probe=53089d138d) | Jan 03, 2024 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [64811dfb22](https://linux-hardware.org/?probe=64811dfb22) | Jan 03, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [e15430e53e](https://linux-hardware.org/?probe=e15430e53e) | Jan 02, 2024 |
| Dell          | 0D28YY A01                  | Desktop     | [f67d5d22eb](https://linux-hardware.org/?probe=f67d5d22eb) | Jan 02, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1V60... | Notebook    | [ca5f55438f](https://linux-hardware.org/?probe=ca5f55438f) | Jan 02, 2024 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [0db9ec67ac](https://linux-hardware.org/?probe=0db9ec67ac) | Jan 02, 2024 |
| Apple         | Mac-F22C86C8                | Mini pc     | [b1e1f0314c](https://linux-hardware.org/?probe=b1e1f0314c) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [d2112b91c1](https://linux-hardware.org/?probe=d2112b91c1) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [252e78398a](https://linux-hardware.org/?probe=252e78398a) | Jan 01, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [a37bbce8de](https://linux-hardware.org/?probe=a37bbce8de) | Dec 31, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [bdc19328ef](https://linux-hardware.org/?probe=bdc19328ef) | Dec 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [d975ab384e](https://linux-hardware.org/?probe=d975ab384e) | Dec 31, 2023 |
| Dell          | 0RW199                      | Desktop     | [62dc9ffa33](https://linux-hardware.org/?probe=62dc9ffa33) | Dec 31, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [e330d0191e](https://linux-hardware.org/?probe=e330d0191e) | Dec 31, 2023 |
| Acer          | Aspire 8943G                | Notebook    | [a75a2524f2](https://linux-hardware.org/?probe=a75a2524f2) | Dec 31, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [ac506b01e6](https://linux-hardware.org/?probe=ac506b01e6) | Dec 30, 2023 |
| HP            | 82F1                        | Desktop     | [9fc9cb3de0](https://linux-hardware.org/?probe=9fc9cb3de0) | Dec 30, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [c58ff5350b](https://linux-hardware.org/?probe=c58ff5350b) | Dec 30, 2023 |
| Pegatron      | 2A9A                        | Desktop     | [92def1bf4a](https://linux-hardware.org/?probe=92def1bf4a) | Dec 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7dca6779be](https://linux-hardware.org/?probe=7dca6779be) | Dec 29, 2023 |
| Sony          | VGN-CR21S_W                 | Notebook    | [732175d0f6](https://linux-hardware.org/?probe=732175d0f6) | Dec 29, 2023 |
| ASRock        | B550M-C                     | Desktop     | [ba3fa09385](https://linux-hardware.org/?probe=ba3fa09385) | Dec 29, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [7a34810f0e](https://linux-hardware.org/?probe=7a34810f0e) | Dec 29, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [9189ed311a](https://linux-hardware.org/?probe=9189ed311a) | Dec 29, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4d46811257](https://linux-hardware.org/?probe=4d46811257) | Dec 29, 2023 |
| HP            | ZBook 14u G6                | Notebook    | [409e402108](https://linux-hardware.org/?probe=409e402108) | Dec 28, 2023 |
| Lenovo        | No DPK                      | All in one  | [e47b692f60](https://linux-hardware.org/?probe=e47b692f60) | Dec 28, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [52ae549c99](https://linux-hardware.org/?probe=52ae549c99) | Dec 28, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [59c76d34e1](https://linux-hardware.org/?probe=59c76d34e1) | Dec 27, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [403dd9f171](https://linux-hardware.org/?probe=403dd9f171) | Dec 27, 2023 |
| HP            | Compaq 2510p                | Notebook    | [b7b88f9c1c](https://linux-hardware.org/?probe=b7b88f9c1c) | Dec 27, 2023 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [a3bb952104](https://linux-hardware.org/?probe=a3bb952104) | Dec 27, 2023 |
| ASUSTek       | M4A79T Deluxe               | Desktop     | [167d330ef0](https://linux-hardware.org/?probe=167d330ef0) | Dec 27, 2023 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [30d2bb71e5](https://linux-hardware.org/?probe=30d2bb71e5) | Dec 27, 2023 |
| Lenovo        | No DPK                      | All in one  | [961bd36b3d](https://linux-hardware.org/?probe=961bd36b3d) | Dec 27, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [bc9feace53](https://linux-hardware.org/?probe=bc9feace53) | Dec 27, 2023 |
| Pegatron      | 2A9A                        | Desktop     | [e67022179a](https://linux-hardware.org/?probe=e67022179a) | Dec 26, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [ae928b9cc1](https://linux-hardware.org/?probe=ae928b9cc1) | Dec 25, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [52a5621ef8](https://linux-hardware.org/?probe=52a5621ef8) | Dec 25, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [0cee3977a0](https://linux-hardware.org/?probe=0cee3977a0) | Dec 25, 2023 |
| Dell          | 0MN1TX A04                  | Desktop     | [ba94c75ba0](https://linux-hardware.org/?probe=ba94c75ba0) | Dec 25, 2023 |
| HP            | ENVY dv6                    | Notebook    | [e7d00bdca8](https://linux-hardware.org/?probe=e7d00bdca8) | Dec 25, 2023 |
| HP            | ENVY dv6                    | Notebook    | [7feb95b534](https://linux-hardware.org/?probe=7feb95b534) | Dec 25, 2023 |
| HP            | 2AF7                        | Desktop     | [2fc4d5dd6b](https://linux-hardware.org/?probe=2fc4d5dd6b) | Dec 24, 2023 |
| HP            | 2AF7                        | Desktop     | [baa5012432](https://linux-hardware.org/?probe=baa5012432) | Dec 24, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [2f8f606e9f](https://linux-hardware.org/?probe=2f8f606e9f) | Dec 24, 2023 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [dd911fd507](https://linux-hardware.org/?probe=dd911fd507) | Dec 24, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [6ee70cb266](https://linux-hardware.org/?probe=6ee70cb266) | Dec 24, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d949738171](https://linux-hardware.org/?probe=d949738171) | Dec 24, 2023 |
| Dell          | Latitude E6430              | Notebook    | [c821d379ec](https://linux-hardware.org/?probe=c821d379ec) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [a69b3fa1ca](https://linux-hardware.org/?probe=a69b3fa1ca) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [9ac48a1719](https://linux-hardware.org/?probe=9ac48a1719) | Dec 24, 2023 |
| HP            | Notebook                    | Notebook    | [69bef099c0](https://linux-hardware.org/?probe=69bef099c0) | Dec 24, 2023 |
| ASUSTek       | M2V                         | Desktop     | [67c7bc43ed](https://linux-hardware.org/?probe=67c7bc43ed) | Dec 23, 2023 |
| ASUSTek       | M2V                         | Desktop     | [1d6970f290](https://linux-hardware.org/?probe=1d6970f290) | Dec 23, 2023 |
| HP            | 1998                        | Desktop     | [8eb25518c4](https://linux-hardware.org/?probe=8eb25518c4) | Dec 23, 2023 |
| HP            | Victus by 15.6 inch Gami... | Notebook    | [b74170ede4](https://linux-hardware.org/?probe=b74170ede4) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [b4d280ac6a](https://linux-hardware.org/?probe=b4d280ac6a) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [421d62894b](https://linux-hardware.org/?probe=421d62894b) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [dceb1203ed](https://linux-hardware.org/?probe=dceb1203ed) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [b9557b6218](https://linux-hardware.org/?probe=b9557b6218) | Dec 23, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [9c0210d1ed](https://linux-hardware.org/?probe=9c0210d1ed) | Dec 22, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [972b407abc](https://linux-hardware.org/?probe=972b407abc) | Dec 22, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [084e48827c](https://linux-hardware.org/?probe=084e48827c) | Dec 21, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [83183dbb01](https://linux-hardware.org/?probe=83183dbb01) | Dec 21, 2023 |
| Lenovo        | ThinkPad X131e 33691K7      | Notebook    | [360dc0f244](https://linux-hardware.org/?probe=360dc0f244) | Dec 21, 2023 |
| Dell          | Latitude E7270              | Notebook    | [4574a46c78](https://linux-hardware.org/?probe=4574a46c78) | Dec 21, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [f9d9539e00](https://linux-hardware.org/?probe=f9d9539e00) | Dec 21, 2023 |
| ASUSTek       | E201NA                      | Notebook    | [ee5e05ce6d](https://linux-hardware.org/?probe=ee5e05ce6d) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6311def15e](https://linux-hardware.org/?probe=6311def15e) | Dec 21, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [8b094a74c9](https://linux-hardware.org/?probe=8b094a74c9) | Dec 21, 2023 |
| HP            | 1000                        | Notebook    | [2279f68ba4](https://linux-hardware.org/?probe=2279f68ba4) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [5266cee35b](https://linux-hardware.org/?probe=5266cee35b) | Dec 21, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c0c637bbba](https://linux-hardware.org/?probe=c0c637bbba) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | Notebook    | [50a3c349a0](https://linux-hardware.org/?probe=50a3c349a0) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | Notebook    | [f79ed192ac](https://linux-hardware.org/?probe=f79ed192ac) | Dec 21, 2023 |
| Dell          | 0FM586                      | Desktop     | [eadcdb629b](https://linux-hardware.org/?probe=eadcdb629b) | Dec 20, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [caa584d966](https://linux-hardware.org/?probe=caa584d966) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [af51ef8978](https://linux-hardware.org/?probe=af51ef8978) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7cda066ff6](https://linux-hardware.org/?probe=7cda066ff6) | Dec 20, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [6a601de5d5](https://linux-hardware.org/?probe=6a601de5d5) | Dec 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [f7cd6db92f](https://linux-hardware.org/?probe=f7cd6db92f) | Dec 20, 2023 |
| HP            | 1998                        | Desktop     | [bc41363911](https://linux-hardware.org/?probe=bc41363911) | Dec 20, 2023 |
| Framework     | Laptop                      | Notebook    | [2aab7ea892](https://linux-hardware.org/?probe=2aab7ea892) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bcae8d434f](https://linux-hardware.org/?probe=bcae8d434f) | Dec 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [582c2df7b1](https://linux-hardware.org/?probe=582c2df7b1) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [91b5e05490](https://linux-hardware.org/?probe=91b5e05490) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [fde7aeea9c](https://linux-hardware.org/?probe=fde7aeea9c) | Dec 19, 2023 |
| Google        | Phaser360                   | Notebook    | [c739678794](https://linux-hardware.org/?probe=c739678794) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [780a4cf454](https://linux-hardware.org/?probe=780a4cf454) | Dec 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0VU00    | Notebook    | [ecca798714](https://linux-hardware.org/?probe=ecca798714) | Dec 18, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [c2b96a9e0f](https://linux-hardware.org/?probe=c2b96a9e0f) | Dec 18, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [74cdfd92c0](https://linux-hardware.org/?probe=74cdfd92c0) | Dec 18, 2023 |
| HP            | ZBook 14u G6                | Notebook    | [125dbde28d](https://linux-hardware.org/?probe=125dbde28d) | Dec 17, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [2b9510004d](https://linux-hardware.org/?probe=2b9510004d) | Dec 17, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [a411802ac6](https://linux-hardware.org/?probe=a411802ac6) | Dec 17, 2023 |
| Sony          | VGN-FW455J                  | Notebook    | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [7962dd075b](https://linux-hardware.org/?probe=7962dd075b) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [304fbf1e83](https://linux-hardware.org/?probe=304fbf1e83) | Dec 17, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [4e3b49ab8e](https://linux-hardware.org/?probe=4e3b49ab8e) | Dec 17, 2023 |
| Irbis         | NB12                        | Notebook    | [f6eb11e455](https://linux-hardware.org/?probe=f6eb11e455) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [ad9eaf3ae6](https://linux-hardware.org/?probe=ad9eaf3ae6) | Dec 16, 2023 |
| Google        | Phaser360                   | Notebook    | [784ed40440](https://linux-hardware.org/?probe=784ed40440) | Dec 16, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [56e1b0ed26](https://linux-hardware.org/?probe=56e1b0ed26) | Dec 16, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [30f8fe050c](https://linux-hardware.org/?probe=30f8fe050c) | Dec 16, 2023 |
| HP            | Notebook                    | Notebook    | [4973d42380](https://linux-hardware.org/?probe=4973d42380) | Dec 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [faf62fd1be](https://linux-hardware.org/?probe=faf62fd1be) | Dec 16, 2023 |
| HP            | Notebook                    | Notebook    | [a960b17c37](https://linux-hardware.org/?probe=a960b17c37) | Dec 16, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [1bd6eab773](https://linux-hardware.org/?probe=1bd6eab773) | Dec 15, 2023 |
| Dell          | 0FM586                      | Desktop     | [c895a8d51f](https://linux-hardware.org/?probe=c895a8d51f) | Dec 15, 2023 |
| Medion        | P7624                       | Notebook    | [4828985ec0](https://linux-hardware.org/?probe=4828985ec0) | Dec 15, 2023 |
| Medion        | P7624                       | Notebook    | [050fbbd613](https://linux-hardware.org/?probe=050fbbd613) | Dec 15, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [de4b8201ef](https://linux-hardware.org/?probe=de4b8201ef) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [646c709529](https://linux-hardware.org/?probe=646c709529) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [b5fefd59fe](https://linux-hardware.org/?probe=b5fefd59fe) | Dec 15, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [7d20d738b1](https://linux-hardware.org/?probe=7d20d738b1) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [734375c1cc](https://linux-hardware.org/?probe=734375c1cc) | Dec 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | Notebook    | [5ae09c04d4](https://linux-hardware.org/?probe=5ae09c04d4) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3eb792873c](https://linux-hardware.org/?probe=3eb792873c) | Dec 14, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [048f7ace00](https://linux-hardware.org/?probe=048f7ace00) | Dec 14, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [85f532c1c5](https://linux-hardware.org/?probe=85f532c1c5) | Dec 13, 2023 |
| Positivo      | POS-PIQ57BQ POSITIVO        | Desktop     | [1a2fe7c9ef](https://linux-hardware.org/?probe=1a2fe7c9ef) | Dec 13, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [41dbdcf594](https://linux-hardware.org/?probe=41dbdcf594) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [f9933769ef](https://linux-hardware.org/?probe=f9933769ef) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [27b99be924](https://linux-hardware.org/?probe=27b99be924) | Dec 12, 2023 |
| HP            | Notebook                    | Notebook    | [972e86b7cf](https://linux-hardware.org/?probe=972e86b7cf) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [f779186ae7](https://linux-hardware.org/?probe=f779186ae7) | Dec 11, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [311c3a6954](https://linux-hardware.org/?probe=311c3a6954) | Dec 11, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [a644fcc63e](https://linux-hardware.org/?probe=a644fcc63e) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [332492b0c4](https://linux-hardware.org/?probe=332492b0c4) | Dec 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [d0ff744f50](https://linux-hardware.org/?probe=d0ff744f50) | Dec 10, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [e7dbed1e89](https://linux-hardware.org/?probe=e7dbed1e89) | Dec 10, 2023 |
| Dell          | 0FM586                      | Desktop     | [2bf8665376](https://linux-hardware.org/?probe=2bf8665376) | Dec 10, 2023 |
| MSI           | 2AE0                        | Desktop     | [29c5d75dcf](https://linux-hardware.org/?probe=29c5d75dcf) | Dec 10, 2023 |
| MSI           | 2AE0                        | Desktop     | [63543021ec](https://linux-hardware.org/?probe=63543021ec) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [5522722e53](https://linux-hardware.org/?probe=5522722e53) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [52e1cb6958](https://linux-hardware.org/?probe=52e1cb6958) | Dec 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [949de6a6a9](https://linux-hardware.org/?probe=949de6a6a9) | Dec 10, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [3f4af9bbdd](https://linux-hardware.org/?probe=3f4af9bbdd) | Dec 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [514899b0b9](https://linux-hardware.org/?probe=514899b0b9) | Dec 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bc892e5d3b](https://linux-hardware.org/?probe=bc892e5d3b) | Dec 09, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [e2c932c285](https://linux-hardware.org/?probe=e2c932c285) | Dec 09, 2023 |
| Acer          | AOD257                      | Notebook    | [79c121ca0e](https://linux-hardware.org/?probe=79c121ca0e) | Dec 09, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [d2abe7128b](https://linux-hardware.org/?probe=d2abe7128b) | Dec 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [955f530c70](https://linux-hardware.org/?probe=955f530c70) | Dec 08, 2023 |
| Acer          | AOD257                      | Notebook    | [c817dc5cca](https://linux-hardware.org/?probe=c817dc5cca) | Dec 08, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [045ab5efca](https://linux-hardware.org/?probe=045ab5efca) | Dec 08, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [88c39cda86](https://linux-hardware.org/?probe=88c39cda86) | Dec 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [fc2efc3edb](https://linux-hardware.org/?probe=fc2efc3edb) | Dec 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | Notebook    | [767b4efa54](https://linux-hardware.org/?probe=767b4efa54) | Dec 06, 2023 |
| MSI           | MS-7309                     | Desktop     | [bfc6167f25](https://linux-hardware.org/?probe=bfc6167f25) | Dec 06, 2023 |
| MSI           | MS-7309                     | Desktop     | [556b1ebd9a](https://linux-hardware.org/?probe=556b1ebd9a) | Dec 06, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [bfd0ab0fc0](https://linux-hardware.org/?probe=bfd0ab0fc0) | Dec 06, 2023 |
| Dell          | Latitude 7490               | Notebook    | [364b5c38d4](https://linux-hardware.org/?probe=364b5c38d4) | Dec 06, 2023 |
| Gateway       | SX2851                      | Desktop     | [2ec497373d](https://linux-hardware.org/?probe=2ec497373d) | Dec 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1748ab2263](https://linux-hardware.org/?probe=1748ab2263) | Dec 05, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [3792e939db](https://linux-hardware.org/?probe=3792e939db) | Dec 05, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [549c56d2f8](https://linux-hardware.org/?probe=549c56d2f8) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [9714fadd61](https://linux-hardware.org/?probe=9714fadd61) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [23937a8b80](https://linux-hardware.org/?probe=23937a8b80) | Dec 04, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0d13c9a0b6](https://linux-hardware.org/?probe=0d13c9a0b6) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dcb521e9aa](https://linux-hardware.org/?probe=dcb521e9aa) | Dec 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [4800fa6c99](https://linux-hardware.org/?probe=4800fa6c99) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [6bc5e84b91](https://linux-hardware.org/?probe=6bc5e84b91) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [813edffc94](https://linux-hardware.org/?probe=813edffc94) | Dec 04, 2023 |
| HP            | 3031h                       | Desktop     | [06a9e0c346](https://linux-hardware.org/?probe=06a9e0c346) | Dec 04, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [4e67d597e1](https://linux-hardware.org/?probe=4e67d597e1) | Dec 04, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [45d1723559](https://linux-hardware.org/?probe=45d1723559) | Dec 03, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [1e4dda911f](https://linux-hardware.org/?probe=1e4dda911f) | Dec 03, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [e4f6d008cc](https://linux-hardware.org/?probe=e4f6d008cc) | Dec 03, 2023 |
| MSI           | 870A-G54                    | Desktop     | [46f9552be9](https://linux-hardware.org/?probe=46f9552be9) | Dec 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [42ddf2c00c](https://linux-hardware.org/?probe=42ddf2c00c) | Dec 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [dca543f661](https://linux-hardware.org/?probe=dca543f661) | Dec 03, 2023 |
| HP            | Pavilion dv5                | Notebook    | [40e03f76cf](https://linux-hardware.org/?probe=40e03f76cf) | Dec 03, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [7a932c5570](https://linux-hardware.org/?probe=7a932c5570) | Dec 02, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [9b46bc6583](https://linux-hardware.org/?probe=9b46bc6583) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [f2a9f68180](https://linux-hardware.org/?probe=f2a9f68180) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [e6d3755007](https://linux-hardware.org/?probe=e6d3755007) | Dec 02, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [5d98fa1470](https://linux-hardware.org/?probe=5d98fa1470) | Dec 02, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [9dea837056](https://linux-hardware.org/?probe=9dea837056) | Dec 02, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [f1e82db736](https://linux-hardware.org/?probe=f1e82db736) | Dec 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aab717794b](https://linux-hardware.org/?probe=aab717794b) | Dec 01, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [ca692e6dcb](https://linux-hardware.org/?probe=ca692e6dcb) | Dec 01, 2023 |
| MSI           | MPG Z590M GAMING EDGE WI... | Desktop     | [a8495b2209](https://linux-hardware.org/?probe=a8495b2209) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [72702ceb3f](https://linux-hardware.org/?probe=72702ceb3f) | Dec 01, 2023 |
| HP            | 15                          | Notebook    | [7bd98a81f6](https://linux-hardware.org/?probe=7bd98a81f6) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [02f2ca658e](https://linux-hardware.org/?probe=02f2ca658e) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e812beed5d](https://linux-hardware.org/?probe=e812beed5d) | Dec 01, 2023 |
| Acer          | Extensa M2610 V:1.0         | Desktop     | [e4c1bd6f51](https://linux-hardware.org/?probe=e4c1bd6f51) | Nov 30, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [33126bb441](https://linux-hardware.org/?probe=33126bb441) | Nov 30, 2023 |
| Toshiba       | Satellite L850D-131         | Notebook    | [483c7cfdf6](https://linux-hardware.org/?probe=483c7cfdf6) | Nov 30, 2023 |
| AMI           | AMD                         | Notebook    | [9f3f9ba617](https://linux-hardware.org/?probe=9f3f9ba617) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5602CBA... | Notebook    | [0c08316018](https://linux-hardware.org/?probe=0c08316018) | Nov 29, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [062cd64553](https://linux-hardware.org/?probe=062cd64553) | Nov 29, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [423e8001ab](https://linux-hardware.org/?probe=423e8001ab) | Nov 29, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [c934dcacd6](https://linux-hardware.org/?probe=c934dcacd6) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| Medion        | Erazer P7643 MD60133        | Notebook    | [65f090fe28](https://linux-hardware.org/?probe=65f090fe28) | Nov 28, 2023 |
| HP            | 15                          | Notebook    | [c1ca96368f](https://linux-hardware.org/?probe=c1ca96368f) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | Notebook    | [f99e3c8556](https://linux-hardware.org/?probe=f99e3c8556) | Nov 28, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [f85fb01be1](https://linux-hardware.org/?probe=f85fb01be1) | Nov 28, 2023 |
| HP            | 15                          | Notebook    | [aba1e87e5c](https://linux-hardware.org/?probe=aba1e87e5c) | Nov 28, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [7d6885561f](https://linux-hardware.org/?probe=7d6885561f) | Nov 28, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [e106315577](https://linux-hardware.org/?probe=e106315577) | Nov 28, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [6d2e371a5f](https://linux-hardware.org/?probe=6d2e371a5f) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | Desktop     | [bfd90230bc](https://linux-hardware.org/?probe=bfd90230bc) | Nov 27, 2023 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [38dd158d3e](https://linux-hardware.org/?probe=38dd158d3e) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | Desktop     | [4b2fec8699](https://linux-hardware.org/?probe=4b2fec8699) | Nov 27, 2023 |
| Dell          | Latitude D830               | Notebook    | [2e017edf81](https://linux-hardware.org/?probe=2e017edf81) | Nov 27, 2023 |
| HP            | ENVY m6                     | Notebook    | [41cff88708](https://linux-hardware.org/?probe=41cff88708) | Nov 26, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [fb45c81af9](https://linux-hardware.org/?probe=fb45c81af9) | Nov 26, 2023 |
| AZW           | Green G3                    | Desktop     | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| Toshiba       | TECRA W50-A                 | Notebook    | [91a2348496](https://linux-hardware.org/?probe=91a2348496) | Nov 25, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [e4062fc1e4](https://linux-hardware.org/?probe=e4062fc1e4) | Nov 25, 2023 |
| HP            | 82F1                        | Desktop     | [09c7b87413](https://linux-hardware.org/?probe=09c7b87413) | Nov 24, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [c9522c065e](https://linux-hardware.org/?probe=c9522c065e) | Nov 24, 2023 |
| HP            | 82F1                        | Desktop     | [9ed00910d4](https://linux-hardware.org/?probe=9ed00910d4) | Nov 24, 2023 |
| Lenovo        | ThinkPad T570 20HAS0K501    | Notebook    | [4fe6d8f889](https://linux-hardware.org/?probe=4fe6d8f889) | Nov 24, 2023 |
| Lenovo        | MAHOBAY Win8 STD EM DPK ... | All in one  | [a86dba284f](https://linux-hardware.org/?probe=a86dba284f) | Nov 24, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [6930db743c](https://linux-hardware.org/?probe=6930db743c) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [eb779ea004](https://linux-hardware.org/?probe=eb779ea004) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [0d60447eea](https://linux-hardware.org/?probe=0d60447eea) | Nov 24, 2023 |
| HP            | G5000 (GF767EA#B1A)         | Notebook    | [5239511cca](https://linux-hardware.org/?probe=5239511cca) | Nov 24, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [9d5752b2d8](https://linux-hardware.org/?probe=9d5752b2d8) | Nov 24, 2023 |
| Unknown       | M17                         | Notebook    | [d3d7d176b4](https://linux-hardware.org/?probe=d3d7d176b4) | Nov 23, 2023 |
| Medion        | E5214                       | Notebook    | [f3ab89b2d3](https://linux-hardware.org/?probe=f3ab89b2d3) | Nov 23, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [87ccf00042](https://linux-hardware.org/?probe=87ccf00042) | Nov 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [c883420b97](https://linux-hardware.org/?probe=c883420b97) | Nov 23, 2023 |
| Gigabyte      | GA-MA74GMT-S2               | Desktop     | [440e7b6c7c](https://linux-hardware.org/?probe=440e7b6c7c) | Nov 23, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [3b995f6b47](https://linux-hardware.org/?probe=3b995f6b47) | Nov 23, 2023 |
| Toshiba       | Satellite L850D-131         | Notebook    | [8810505a5a](https://linux-hardware.org/?probe=8810505a5a) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [37a1e3b979](https://linux-hardware.org/?probe=37a1e3b979) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0137a4a556](https://linux-hardware.org/?probe=0137a4a556) | Nov 23, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [c5a84018e9](https://linux-hardware.org/?probe=c5a84018e9) | Nov 23, 2023 |
| HP            | 3029h                       | Desktop     | [2dd2ec759b](https://linux-hardware.org/?probe=2dd2ec759b) | Nov 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [fca11dfd70](https://linux-hardware.org/?probe=fca11dfd70) | Nov 23, 2023 |
| Acer          | Aspire ES1-731              | Notebook    | [649e8a4e24](https://linux-hardware.org/?probe=649e8a4e24) | Nov 22, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [8d492b21b0](https://linux-hardware.org/?probe=8d492b21b0) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [343ba69496](https://linux-hardware.org/?probe=343ba69496) | Nov 22, 2023 |
| HP            | 3561                        | All in one  | [aef249e21a](https://linux-hardware.org/?probe=aef249e21a) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [b365872b3f](https://linux-hardware.org/?probe=b365872b3f) | Nov 22, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [1f07a66db1](https://linux-hardware.org/?probe=1f07a66db1) | Nov 22, 2023 |
| Samsung       | 530XBB                      | Notebook    | [c31efedbdf](https://linux-hardware.org/?probe=c31efedbdf) | Nov 22, 2023 |
| ASUSTek       | E201NA                      | Notebook    | [11f7e8f675](https://linux-hardware.org/?probe=11f7e8f675) | Nov 22, 2023 |
| HP            | EliteBook Folio 1020 G1     | Notebook    | [022f885fe9](https://linux-hardware.org/?probe=022f885fe9) | Nov 22, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [94885b9878](https://linux-hardware.org/?probe=94885b9878) | Nov 21, 2023 |
| AZW           | MINI S 10                   | Desktop     | [47bd270ae8](https://linux-hardware.org/?probe=47bd270ae8) | Nov 21, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [c363e01e5f](https://linux-hardware.org/?probe=c363e01e5f) | Nov 21, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [f9136272f9](https://linux-hardware.org/?probe=f9136272f9) | Nov 21, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [6e0d000498](https://linux-hardware.org/?probe=6e0d000498) | Nov 20, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [3664fc3164](https://linux-hardware.org/?probe=3664fc3164) | Nov 20, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6c2755ced9](https://linux-hardware.org/?probe=6c2755ced9) | Nov 20, 2023 |
| Lenovo        | ThinkPad Edge E530 32599... | Notebook    | [f472f3fd2e](https://linux-hardware.org/?probe=f472f3fd2e) | Nov 20, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8fbd1e56eb](https://linux-hardware.org/?probe=8fbd1e56eb) | Nov 20, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [84df1d0476](https://linux-hardware.org/?probe=84df1d0476) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [97b8871652](https://linux-hardware.org/?probe=97b8871652) | Nov 20, 2023 |
| Medion        | E5214                       | Notebook    | [8e3148e284](https://linux-hardware.org/?probe=8e3148e284) | Nov 20, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [e0a3622122](https://linux-hardware.org/?probe=e0a3622122) | Nov 20, 2023 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [8047aac511](https://linux-hardware.org/?probe=8047aac511) | Nov 20, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [9137a70965](https://linux-hardware.org/?probe=9137a70965) | Nov 20, 2023 |
| AZW           | MINI S 10                   | Desktop     | [a1358be402](https://linux-hardware.org/?probe=a1358be402) | Nov 20, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [468cc043b8](https://linux-hardware.org/?probe=468cc043b8) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [be15ab8952](https://linux-hardware.org/?probe=be15ab8952) | Nov 19, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [626d8d9409](https://linux-hardware.org/?probe=626d8d9409) | Nov 19, 2023 |
| Intel         | H61                         | Desktop     | [bdab1dc80a](https://linux-hardware.org/?probe=bdab1dc80a) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [747979b60f](https://linux-hardware.org/?probe=747979b60f) | Nov 19, 2023 |
| Intel         | H61                         | Desktop     | [4b5806ba4c](https://linux-hardware.org/?probe=4b5806ba4c) | Nov 19, 2023 |
| Acer          | Spin SP513-52N              | Convertible | [339c8003a9](https://linux-hardware.org/?probe=339c8003a9) | Nov 19, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [6876ff8fc6](https://linux-hardware.org/?probe=6876ff8fc6) | Nov 19, 2023 |
| Acer          | Extensa M2610 V:1.0         | Desktop     | [7b70ac1965](https://linux-hardware.org/?probe=7b70ac1965) | Nov 19, 2023 |
| Medion        | E5214                       | Notebook    | [4513f3394d](https://linux-hardware.org/?probe=4513f3394d) | Nov 18, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [b62a8b07f4](https://linux-hardware.org/?probe=b62a8b07f4) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | Desktop     | [cb10d99771](https://linux-hardware.org/?probe=cb10d99771) | Nov 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ec19f0fa52](https://linux-hardware.org/?probe=ec19f0fa52) | Nov 18, 2023 |
| Lenovo        | ThinkCentre M90p 5536Y1K    | Desktop     | [6bdc4cb524](https://linux-hardware.org/?probe=6bdc4cb524) | Nov 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [75cd18198b](https://linux-hardware.org/?probe=75cd18198b) | Nov 18, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b3da1a92d0](https://linux-hardware.org/?probe=b3da1a92d0) | Nov 17, 2023 |
| Compaq        | Presario CQ-17              | Notebook    | [7b53a480e4](https://linux-hardware.org/?probe=7b53a480e4) | Nov 17, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [54bad5da51](https://linux-hardware.org/?probe=54bad5da51) | Nov 17, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [d087235304](https://linux-hardware.org/?probe=d087235304) | Nov 17, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [9974b99f5a](https://linux-hardware.org/?probe=9974b99f5a) | Nov 16, 2023 |
| HP            | Pavilion g7                 | Notebook    | [9f8b6f3432](https://linux-hardware.org/?probe=9f8b6f3432) | Nov 16, 2023 |
| HP            | Pavilion g7                 | Notebook    | [0c4816a4f2](https://linux-hardware.org/?probe=0c4816a4f2) | Nov 16, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [df572cd989](https://linux-hardware.org/?probe=df572cd989) | Nov 15, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7edaa0f1be](https://linux-hardware.org/?probe=7edaa0f1be) | Nov 15, 2023 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [559ef6212b](https://linux-hardware.org/?probe=559ef6212b) | Nov 15, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [d79f8e5ed5](https://linux-hardware.org/?probe=d79f8e5ed5) | Nov 14, 2023 |
| HP            | ZBook 14u G6                | Notebook    | [c6471dbbfd](https://linux-hardware.org/?probe=c6471dbbfd) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | Notebook    | [8c4d2fca5a](https://linux-hardware.org/?probe=8c4d2fca5a) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | Notebook    | [5efc66eebc](https://linux-hardware.org/?probe=5efc66eebc) | Nov 14, 2023 |
| HP            | Compaq 6910p                | Notebook    | [019a154d30](https://linux-hardware.org/?probe=019a154d30) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [513485cc8f](https://linux-hardware.org/?probe=513485cc8f) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | Notebook    | [077bbdc325](https://linux-hardware.org/?probe=077bbdc325) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | Notebook    | [5e50f31cbb](https://linux-hardware.org/?probe=5e50f31cbb) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [d00bbdf844](https://linux-hardware.org/?probe=d00bbdf844) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [493702778b](https://linux-hardware.org/?probe=493702778b) | Nov 14, 2023 |
| Fujitsu       | D2619 S26361-D2619-N15 W... | Server      | [d9f5b1502c](https://linux-hardware.org/?probe=d9f5b1502c) | Nov 14, 2023 |
| Fujitsu       | D2619 S26361-D2619-N15 W... | Server      | [56925134d7](https://linux-hardware.org/?probe=56925134d7) | Nov 14, 2023 |
| JHZD          | BQM5                        | Desktop     | [cab813ae6e](https://linux-hardware.org/?probe=cab813ae6e) | Nov 14, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [f961fee784](https://linux-hardware.org/?probe=f961fee784) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [3c336ad6e1](https://linux-hardware.org/?probe=3c336ad6e1) | Nov 14, 2023 |
| Lenovo        | ThinkPad E550 20DF00CNGE    | Notebook    | [35e0f85cf3](https://linux-hardware.org/?probe=35e0f85cf3) | Nov 13, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [73a53ca5a4](https://linux-hardware.org/?probe=73a53ca5a4) | Nov 13, 2023 |
| Dell          | 0RW199                      | Desktop     | [e3b364ccd6](https://linux-hardware.org/?probe=e3b364ccd6) | Nov 13, 2023 |
| Intel         | H61                         | Desktop     | [cbefae3544](https://linux-hardware.org/?probe=cbefae3544) | Nov 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a0105ee2c8](https://linux-hardware.org/?probe=a0105ee2c8) | Nov 13, 2023 |
| HP            | 15                          | Notebook    | [20b22b2eeb](https://linux-hardware.org/?probe=20b22b2eeb) | Nov 13, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [83d6eddd15](https://linux-hardware.org/?probe=83d6eddd15) | Nov 12, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [8bcc86ef17](https://linux-hardware.org/?probe=8bcc86ef17) | Nov 12, 2023 |
| HP            | ProLiant ML350e Gen8 v2     | Desktop     | [f5de128dd1](https://linux-hardware.org/?probe=f5de128dd1) | Nov 12, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [d46548a5e6](https://linux-hardware.org/?probe=d46548a5e6) | Nov 12, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [cd4230cf5b](https://linux-hardware.org/?probe=cd4230cf5b) | Nov 12, 2023 |
| HUAWEI        | RLEFG-XX                    | Notebook    | [5f413be4fc](https://linux-hardware.org/?probe=5f413be4fc) | Nov 12, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [1d2a92df29](https://linux-hardware.org/?probe=1d2a92df29) | Nov 12, 2023 |
| Lenovo        | ThinkPad E580 20KS001RGE    | Notebook    | [55b706c3ec](https://linux-hardware.org/?probe=55b706c3ec) | Nov 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [4c40c1d213](https://linux-hardware.org/?probe=4c40c1d213) | Nov 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [16acb0dabc](https://linux-hardware.org/?probe=16acb0dabc) | Nov 11, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [b3c59942a1](https://linux-hardware.org/?probe=b3c59942a1) | Nov 11, 2023 |
| Intel         | H61                         | Desktop     | [c65f2e03f6](https://linux-hardware.org/?probe=c65f2e03f6) | Nov 11, 2023 |
| HP            | Presario CQ62               | Notebook    | [584d709751](https://linux-hardware.org/?probe=584d709751) | Nov 11, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [1b3661590f](https://linux-hardware.org/?probe=1b3661590f) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [13798a5389](https://linux-hardware.org/?probe=13798a5389) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b962155541](https://linux-hardware.org/?probe=b962155541) | Nov 11, 2023 |
| Dell          | Precision M6800             | Notebook    | [4ad69afe3a](https://linux-hardware.org/?probe=4ad69afe3a) | Nov 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e4fd0fa1f0](https://linux-hardware.org/?probe=e4fd0fa1f0) | Nov 10, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [fda2670cc5](https://linux-hardware.org/?probe=fda2670cc5) | Nov 10, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [08c8ac6e4d](https://linux-hardware.org/?probe=08c8ac6e4d) | Nov 09, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [c0e0567705](https://linux-hardware.org/?probe=c0e0567705) | Nov 09, 2023 |
| Lenovo        | Z40-70 20366                | Notebook    | [f1968605c1](https://linux-hardware.org/?probe=f1968605c1) | Nov 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [97e4b3093b](https://linux-hardware.org/?probe=97e4b3093b) | Nov 09, 2023 |
| Dell          | 0RW199                      | Desktop     | [11e414d343](https://linux-hardware.org/?probe=11e414d343) | Nov 08, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [6a30b05dcb](https://linux-hardware.org/?probe=6a30b05dcb) | Nov 08, 2023 |
| PEAQ          | PNB C1014-I1B1 MD99447      | Notebook    | [33d5a0aa8c](https://linux-hardware.org/?probe=33d5a0aa8c) | Nov 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b48cc5df9c](https://linux-hardware.org/?probe=b48cc5df9c) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [cc75144dea](https://linux-hardware.org/?probe=cc75144dea) | Nov 08, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [38b21b9f64](https://linux-hardware.org/?probe=38b21b9f64) | Nov 08, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [f77e4d524d](https://linux-hardware.org/?probe=f77e4d524d) | Nov 08, 2023 |
| HP            | Compaq 6830s                | Notebook    | [069a45be37](https://linux-hardware.org/?probe=069a45be37) | Nov 08, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [abb549b943](https://linux-hardware.org/?probe=abb549b943) | Nov 07, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [b7e993f677](https://linux-hardware.org/?probe=b7e993f677) | Nov 07, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [864f50cabf](https://linux-hardware.org/?probe=864f50cabf) | Nov 07, 2023 |
| Fujitsu Si... | AMILO Li 1818               | Notebook    | [ab74cc1cc6](https://linux-hardware.org/?probe=ab74cc1cc6) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [c2434cadfc](https://linux-hardware.org/?probe=c2434cadfc) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [a5628b0f9d](https://linux-hardware.org/?probe=a5628b0f9d) | Nov 07, 2023 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [ef772812b1](https://linux-hardware.org/?probe=ef772812b1) | Nov 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [eea33256f6](https://linux-hardware.org/?probe=eea33256f6) | Nov 07, 2023 |
| Lenovo        | IdeaPad S400u 20213         | Notebook    | [5ddd610c2d](https://linux-hardware.org/?probe=5ddd610c2d) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [5d63a1487d](https://linux-hardware.org/?probe=5d63a1487d) | Nov 06, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [4ef314d383](https://linux-hardware.org/?probe=4ef314d383) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [6c8bb1840e](https://linux-hardware.org/?probe=6c8bb1840e) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0facd311dc](https://linux-hardware.org/?probe=0facd311dc) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [27740d5118](https://linux-hardware.org/?probe=27740d5118) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| Dell          | Latitude E7450              | Notebook    | [71fe592aa3](https://linux-hardware.org/?probe=71fe592aa3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| HP            | 1497                        | Desktop     | [734abf0595](https://linux-hardware.org/?probe=734abf0595) | Nov 05, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [9d8a12d929](https://linux-hardware.org/?probe=9d8a12d929) | Nov 05, 2023 |
| Gigabyte      | M5NM1AI-GB                  | Desktop     | [99e2275a93](https://linux-hardware.org/?probe=99e2275a93) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [dbd2e07499](https://linux-hardware.org/?probe=dbd2e07499) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e98e6bb977](https://linux-hardware.org/?probe=e98e6bb977) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Toshiba       | STI 001359                  | Desktop     | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [1173519349](https://linux-hardware.org/?probe=1173519349) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| TrekStor      | Surfbook W2                 | Notebook    | [cfee0c0363](https://linux-hardware.org/?probe=cfee0c0363) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| Timi          | A35                         | Notebook    | [1baa5932cc](https://linux-hardware.org/?probe=1baa5932cc) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| Dell          | Latitude E6520              | Notebook    | [a0e05f5040](https://linux-hardware.org/?probe=a0e05f5040) | Nov 02, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [ea9f809740](https://linux-hardware.org/?probe=ea9f809740) | Nov 02, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4372a2d9eb](https://linux-hardware.org/?probe=4372a2d9eb) | Nov 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | U36SD                       | Notebook    | [e2045d61a5](https://linux-hardware.org/?probe=e2045d61a5) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [ef9bc3cc1e](https://linux-hardware.org/?probe=ef9bc3cc1e) | Nov 02, 2023 |
| ONDA          | Tablet                      | Tablet      | [1f8b5d6c72](https://linux-hardware.org/?probe=1f8b5d6c72) | Nov 01, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [bc8414b164](https://linux-hardware.org/?probe=bc8414b164) | Nov 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [6db0212093](https://linux-hardware.org/?probe=6db0212093) | Nov 01, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [73a395f017](https://linux-hardware.org/?probe=73a395f017) | Nov 01, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [3b667e2123](https://linux-hardware.org/?probe=3b667e2123) | Oct 31, 2023 |
| Pegatron      | EVANS                       | Desktop     | [3ea2a80843](https://linux-hardware.org/?probe=3ea2a80843) | Oct 31, 2023 |
| Pegatron      | EVANS                       | Desktop     | [52c3eeea68](https://linux-hardware.org/?probe=52c3eeea68) | Oct 31, 2023 |
| RCA           | W122SC24T2                  | Tablet      | [1313389b98](https://linux-hardware.org/?probe=1313389b98) | Oct 31, 2023 |
| RCA           | W122SC24T2                  | Tablet      | [f46f159a0c](https://linux-hardware.org/?probe=f46f159a0c) | Oct 31, 2023 |
| Sony          | SVS15116GAB                 | Notebook    | [03634a7731](https://linux-hardware.org/?probe=03634a7731) | Oct 30, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [185b65ebc1](https://linux-hardware.org/?probe=185b65ebc1) | Oct 30, 2023 |
| HP            | 21F5 0A                     | Desktop     | [097ce56daf](https://linux-hardware.org/?probe=097ce56daf) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [627ed781b5](https://linux-hardware.org/?probe=627ed781b5) | Oct 30, 2023 |
| HP            | 15                          | Notebook    | [1480b12f56](https://linux-hardware.org/?probe=1480b12f56) | Oct 30, 2023 |
| HP            | Notebook                    | Notebook    | [5538a0e3b2](https://linux-hardware.org/?probe=5538a0e3b2) | Oct 30, 2023 |
| HP            | Pavilion dv4                | Notebook    | [854806c6f4](https://linux-hardware.org/?probe=854806c6f4) | Oct 29, 2023 |
| HP            | 1998                        | Desktop     | [2182b05a45](https://linux-hardware.org/?probe=2182b05a45) | Oct 29, 2023 |
| HP            | ENVY 17                     | Notebook    | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [28f261fb9a](https://linux-hardware.org/?probe=28f261fb9a) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | Notebook    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [e13de47400](https://linux-hardware.org/?probe=e13de47400) | Oct 29, 2023 |
| Lenovo        | ThinkPad E420 1141BTU       | Notebook    | [867e950bca](https://linux-hardware.org/?probe=867e950bca) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [a123ac023f](https://linux-hardware.org/?probe=a123ac023f) | Oct 29, 2023 |
| MSI           | Z370M MORTAR                | Desktop     | [0af3708cd3](https://linux-hardware.org/?probe=0af3708cd3) | Oct 29, 2023 |
| HP            | 18E4                        | Desktop     | [b192ce4f35](https://linux-hardware.org/?probe=b192ce4f35) | Oct 28, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [97eabba1a8](https://linux-hardware.org/?probe=97eabba1a8) | Oct 28, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [c2bc73c67b](https://linux-hardware.org/?probe=c2bc73c67b) | Oct 28, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [b9830b7f02](https://linux-hardware.org/?probe=b9830b7f02) | Oct 28, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [98c2ece6fd](https://linux-hardware.org/?probe=98c2ece6fd) | Oct 28, 2023 |
| HP            | ENVY 17                     | Notebook    | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| Acer          | TravelMate Spin P614RN-5    | Convertible | [e337a1e208](https://linux-hardware.org/?probe=e337a1e208) | Oct 27, 2023 |
| HCL Infosy... | HCL ME Laptop               | Notebook    | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| MSI           | Boston                      | Desktop     | [66f7505c8b](https://linux-hardware.org/?probe=66f7505c8b) | Oct 27, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [516a5ee33b](https://linux-hardware.org/?probe=516a5ee33b) | Oct 27, 2023 |
| HP            | 2215                        | Desktop     | [01fd79c4fe](https://linux-hardware.org/?probe=01fd79c4fe) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [463b5f73b5](https://linux-hardware.org/?probe=463b5f73b5) | Oct 26, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [763e54c87b](https://linux-hardware.org/?probe=763e54c87b) | Oct 26, 2023 |
| HP            | G61                         | Notebook    | [d184a33522](https://linux-hardware.org/?probe=d184a33522) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [67021475e9](https://linux-hardware.org/?probe=67021475e9) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [ec0dcdaa76](https://linux-hardware.org/?probe=ec0dcdaa76) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [4f4d354524](https://linux-hardware.org/?probe=4f4d354524) | Oct 26, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [ca4ce5575c](https://linux-hardware.org/?probe=ca4ce5575c) | Oct 26, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4699d107df](https://linux-hardware.org/?probe=4699d107df) | Oct 26, 2023 |
| LORD ELECT... | Guso G4x + ICH7 Series M... | Desktop     | [c6f81cf996](https://linux-hardware.org/?probe=c6f81cf996) | Oct 25, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [e0534a1c2a](https://linux-hardware.org/?probe=e0534a1c2a) | Oct 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [cd1abadd3a](https://linux-hardware.org/?probe=cd1abadd3a) | Oct 25, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6f9c14dc54](https://linux-hardware.org/?probe=6f9c14dc54) | Oct 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [039878b1b2](https://linux-hardware.org/?probe=039878b1b2) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| Gigabyte      | B85M-D3V Plus               | Desktop     | [845b1f10ef](https://linux-hardware.org/?probe=845b1f10ef) | Oct 24, 2023 |
| Dell          | 0RCPW3 A03                  | Desktop     | [a461b9f3e7](https://linux-hardware.org/?probe=a461b9f3e7) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [905555c7d5](https://linux-hardware.org/?probe=905555c7d5) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [5f6d67d67e](https://linux-hardware.org/?probe=5f6d67d67e) | Oct 23, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [cd4e6f4d07](https://linux-hardware.org/?probe=cd4e6f4d07) | Oct 23, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [961b658ac5](https://linux-hardware.org/?probe=961b658ac5) | Oct 23, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | Notebook    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| ONDA          | Tablet                      | Tablet      | [2ef7c07bdf](https://linux-hardware.org/?probe=2ef7c07bdf) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ff9e1d6c16](https://linux-hardware.org/?probe=ff9e1d6c16) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9999b4b89a](https://linux-hardware.org/?probe=9999b4b89a) | Oct 22, 2023 |
| Dell          | Precision 7530              | Notebook    | [92f2a2c99e](https://linux-hardware.org/?probe=92f2a2c99e) | Oct 22, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [081a658255](https://linux-hardware.org/?probe=081a658255) | Oct 21, 2023 |
| TrekStor      | Surfbook W2                 | Notebook    | [001d67067b](https://linux-hardware.org/?probe=001d67067b) | Oct 21, 2023 |
| ONDA          | Tablet                      | Tablet      | [835a5e9d6d](https://linux-hardware.org/?probe=835a5e9d6d) | Oct 21, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [5536078e9f](https://linux-hardware.org/?probe=5536078e9f) | Oct 21, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [ef8c0bb04c](https://linux-hardware.org/?probe=ef8c0bb04c) | Oct 21, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [330cbe85c6](https://linux-hardware.org/?probe=330cbe85c6) | Oct 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a7ee33da8f](https://linux-hardware.org/?probe=a7ee33da8f) | Oct 21, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [d8b8f7bafe](https://linux-hardware.org/?probe=d8b8f7bafe) | Oct 20, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [cb8d8311e7](https://linux-hardware.org/?probe=cb8d8311e7) | Oct 20, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [3dd8426b8f](https://linux-hardware.org/?probe=3dd8426b8f) | Oct 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [af96c09a64](https://linux-hardware.org/?probe=af96c09a64) | Oct 19, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [77079711d3](https://linux-hardware.org/?probe=77079711d3) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7fed113f9b](https://linux-hardware.org/?probe=7fed113f9b) | Oct 19, 2023 |
| ALLDOCUBE     | KnoteGo                     | Tablet      | [17833d30dc](https://linux-hardware.org/?probe=17833d30dc) | Oct 19, 2023 |
| HP            | 829A                        | Mini pc     | [8a3f72e9ef](https://linux-hardware.org/?probe=8a3f72e9ef) | Oct 19, 2023 |
| Dell          | Latitude 5490               | Notebook    | [cdf021cc62](https://linux-hardware.org/?probe=cdf021cc62) | Oct 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [060a642de4](https://linux-hardware.org/?probe=060a642de4) | Oct 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [051cd3c21e](https://linux-hardware.org/?probe=051cd3c21e) | Oct 19, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d37e5bc4f2](https://linux-hardware.org/?probe=d37e5bc4f2) | Oct 19, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [21a2a5b900](https://linux-hardware.org/?probe=21a2a5b900) | Oct 18, 2023 |
| ONDA          | Tablet                      | Tablet      | [6a43a8d57d](https://linux-hardware.org/?probe=6a43a8d57d) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | Desktop     | [bdc9d825d8](https://linux-hardware.org/?probe=bdc9d825d8) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | Desktop     | [ec5284109e](https://linux-hardware.org/?probe=ec5284109e) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [9a6fd46a7d](https://linux-hardware.org/?probe=9a6fd46a7d) | Oct 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [03cf657f5a](https://linux-hardware.org/?probe=03cf657f5a) | Oct 17, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [848b8d7c20](https://linux-hardware.org/?probe=848b8d7c20) | Oct 17, 2023 |
| Lenovo        | ThinkPad T440 20B7S1D200    | Notebook    | [43185c1e5b](https://linux-hardware.org/?probe=43185c1e5b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [76e5cf1323](https://linux-hardware.org/?probe=76e5cf1323) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a0f3ae3d1a](https://linux-hardware.org/?probe=a0f3ae3d1a) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [16a117accb](https://linux-hardware.org/?probe=16a117accb) | Oct 15, 2023 |
| HP            | Pavilion g7                 | Notebook    | [309ca4d5c7](https://linux-hardware.org/?probe=309ca4d5c7) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [d43a466e59](https://linux-hardware.org/?probe=d43a466e59) | Oct 14, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [39e9986b39](https://linux-hardware.org/?probe=39e9986b39) | Oct 14, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6321b8063](https://linux-hardware.org/?probe=c6321b8063) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [35a5d0ac7c](https://linux-hardware.org/?probe=35a5d0ac7c) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [081856b4e9](https://linux-hardware.org/?probe=081856b4e9) | Oct 14, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [0db9d6a5cf](https://linux-hardware.org/?probe=0db9d6a5cf) | Oct 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [f4e7334b7e](https://linux-hardware.org/?probe=f4e7334b7e) | Oct 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [c2cbb1c407](https://linux-hardware.org/?probe=c2cbb1c407) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [17d1931208](https://linux-hardware.org/?probe=17d1931208) | Oct 13, 2023 |
| MSI           | B85M-E45                    | Desktop     | [6ad9d3ff3c](https://linux-hardware.org/?probe=6ad9d3ff3c) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [ffd832c09d](https://linux-hardware.org/?probe=ffd832c09d) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [c70591ee60](https://linux-hardware.org/?probe=c70591ee60) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [314d81343b](https://linux-hardware.org/?probe=314d81343b) | Oct 12, 2023 |
| Schenker      | XMG CORE (REN/M20)          | Notebook    | [48ee28954d](https://linux-hardware.org/?probe=48ee28954d) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e276347e0a](https://linux-hardware.org/?probe=e276347e0a) | Oct 12, 2023 |
| Acer          | Aspire A317-55P             | Notebook    | [a4e8b9c99a](https://linux-hardware.org/?probe=a4e8b9c99a) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [916bfc1646](https://linux-hardware.org/?probe=916bfc1646) | Oct 11, 2023 |
| Acer          | Aspire A317-55P             | Notebook    | [3805200b55](https://linux-hardware.org/?probe=3805200b55) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [cc50dc0894](https://linux-hardware.org/?probe=cc50dc0894) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [754748eac6](https://linux-hardware.org/?probe=754748eac6) | Oct 11, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [adda7a23c2](https://linux-hardware.org/?probe=adda7a23c2) | Oct 11, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [44a7bac1b9](https://linux-hardware.org/?probe=44a7bac1b9) | Oct 10, 2023 |
| AMI           | Intel                       | Desktop     | [1615dc16ba](https://linux-hardware.org/?probe=1615dc16ba) | Oct 10, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [df54ad11e5](https://linux-hardware.org/?probe=df54ad11e5) | Oct 10, 2023 |
| ASUSTek       | K42F                        | Notebook    | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Lenovo        | Tiger Hill                  | Desktop     | [cdd9f65bf5](https://linux-hardware.org/?probe=cdd9f65bf5) | Oct 10, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [c4ae24b408](https://linux-hardware.org/?probe=c4ae24b408) | Oct 10, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [9b41869902](https://linux-hardware.org/?probe=9b41869902) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [53e4e70567](https://linux-hardware.org/?probe=53e4e70567) | Oct 09, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [332ce6061d](https://linux-hardware.org/?probe=332ce6061d) | Oct 09, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [8984311ce7](https://linux-hardware.org/?probe=8984311ce7) | Oct 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [1eeecb8823](https://linux-hardware.org/?probe=1eeecb8823) | Oct 08, 2023 |
| HP            | Pavilion 15                 | Notebook    | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [067260a51f](https://linux-hardware.org/?probe=067260a51f) | Oct 08, 2023 |
| Shuttle       | FS110                       | Desktop     | [cd7c40ed57](https://linux-hardware.org/?probe=cd7c40ed57) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS08W0... | Notebook    | [24dee8bc07](https://linux-hardware.org/?probe=24dee8bc07) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [b82e5d0718](https://linux-hardware.org/?probe=b82e5d0718) | Oct 07, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [f347154767](https://linux-hardware.org/?probe=f347154767) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Pegatron      | EVANS                       | Desktop     | [f798f24c90](https://linux-hardware.org/?probe=f798f24c90) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [299eee42c7](https://linux-hardware.org/?probe=299eee42c7) | Oct 07, 2023 |
| Alienware     | M14xR2                      | Notebook    | [3b7dd3717c](https://linux-hardware.org/?probe=3b7dd3717c) | Oct 07, 2023 |
| Dynabook      | PORTEGE X30W-J              | Convertible | [aa212009a2](https://linux-hardware.org/?probe=aa212009a2) | Oct 06, 2023 |
| Dell          | Precision 5530              | Notebook    | [38fdcea75f](https://linux-hardware.org/?probe=38fdcea75f) | Oct 06, 2023 |
| Thomson       | GEN360-4C128BK              | Notebook    | [ec04ddb0ba](https://linux-hardware.org/?probe=ec04ddb0ba) | Oct 06, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| Intel         | X99                         | Desktop     | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7add8932c3](https://linux-hardware.org/?probe=7add8932c3) | Oct 06, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [9be367f445](https://linux-hardware.org/?probe=9be367f445) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [ff815f228b](https://linux-hardware.org/?probe=ff815f228b) | Oct 05, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [b8f2dc6919](https://linux-hardware.org/?probe=b8f2dc6919) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [8313e4fb72](https://linux-hardware.org/?probe=8313e4fb72) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a6668a2378](https://linux-hardware.org/?probe=a6668a2378) | Oct 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [de22cbed3e](https://linux-hardware.org/?probe=de22cbed3e) | Oct 04, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c3e7936a83](https://linux-hardware.org/?probe=c3e7936a83) | Oct 04, 2023 |
| Dell          | 0RW199                      | Desktop     | [f829184aa0](https://linux-hardware.org/?probe=f829184aa0) | Oct 04, 2023 |
| Dell          | G3 3579                     | Notebook    | [7730315a91](https://linux-hardware.org/?probe=7730315a91) | Oct 04, 2023 |
| Lenovo        | Tiger Hill                  | Desktop     | [4a3ef3e12f](https://linux-hardware.org/?probe=4a3ef3e12f) | Oct 03, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [1e6ec4d559](https://linux-hardware.org/?probe=1e6ec4d559) | Oct 03, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c474599b04](https://linux-hardware.org/?probe=c474599b04) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [0ebc5c48b5](https://linux-hardware.org/?probe=0ebc5c48b5) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [00afde76db](https://linux-hardware.org/?probe=00afde76db) | Oct 03, 2023 |
| Pegatron      | EVANS                       | Desktop     | [3f2a4fe53e](https://linux-hardware.org/?probe=3f2a4fe53e) | Oct 03, 2023 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [c23994e74a](https://linux-hardware.org/?probe=c23994e74a) | Oct 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b210c95b8e](https://linux-hardware.org/?probe=b210c95b8e) | Oct 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [2519f8a695](https://linux-hardware.org/?probe=2519f8a695) | Oct 02, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | Notebook    | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| MSI           | B85M-E45                    | Desktop     | [12fa4b4da3](https://linux-hardware.org/?probe=12fa4b4da3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | Desktop     | [2c6f35e1d3](https://linux-hardware.org/?probe=2c6f35e1d3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | Desktop     | [ded620f59b](https://linux-hardware.org/?probe=ded620f59b) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [5698c85faa](https://linux-hardware.org/?probe=5698c85faa) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [056bfb8474](https://linux-hardware.org/?probe=056bfb8474) | Oct 01, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [dfa1322112](https://linux-hardware.org/?probe=dfa1322112) | Oct 01, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [8d558a64e8](https://linux-hardware.org/?probe=8d558a64e8) | Oct 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [127980fc54](https://linux-hardware.org/?probe=127980fc54) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [e0cdb74f25](https://linux-hardware.org/?probe=e0cdb74f25) | Oct 01, 2023 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Acer          | Predator G3610              | Desktop     | [cddfa514ba](https://linux-hardware.org/?probe=cddfa514ba) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| MP            | MS-7848                     | Desktop     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [145f7eccd3](https://linux-hardware.org/?probe=145f7eccd3) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | Notebook    | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| HP            | 2B35                        | Desktop     | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | Notebook    | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | Notebook    | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| HP            | Notebook                    | Notebook    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [e7e87a1269](https://linux-hardware.org/?probe=e7e87a1269) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [0c8a57738d](https://linux-hardware.org/?probe=0c8a57738d) | Sep 25, 2023 |
| AZW           | SER                         | Mini pc     | [8e73904b3c](https://linux-hardware.org/?probe=8e73904b3c) | Sep 25, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a778013e21](https://linux-hardware.org/?probe=a778013e21) | Sep 25, 2023 |
| Intel         | W7645                       | Notebook    | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [29feb62e32](https://linux-hardware.org/?probe=29feb62e32) | Sep 25, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [863dfa9b96](https://linux-hardware.org/?probe=863dfa9b96) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | Notebook    | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| Alienware     | M17x                        | Notebook    | [5c6b700486](https://linux-hardware.org/?probe=5c6b700486) | Sep 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [6d75f2f29b](https://linux-hardware.org/?probe=6d75f2f29b) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Sary          | Tab2                        | Tablet      | [7078e2b899](https://linux-hardware.org/?probe=7078e2b899) | Sep 23, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [fdfd7f2e50](https://linux-hardware.org/?probe=fdfd7f2e50) | Sep 23, 2023 |
| Sary          | Tab2                        | Tablet      | [913ec00764](https://linux-hardware.org/?probe=913ec00764) | Sep 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [6897fc6f5a](https://linux-hardware.org/?probe=6897fc6f5a) | Sep 23, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [fd3ce44501](https://linux-hardware.org/?probe=fd3ce44501) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | Notebook    | [8b5a2354c5](https://linux-hardware.org/?probe=8b5a2354c5) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | Notebook    | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [81bf9d5194](https://linux-hardware.org/?probe=81bf9d5194) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| AZW           | MINI S 10                   | Desktop     | [e393d95960](https://linux-hardware.org/?probe=e393d95960) | Sep 21, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | Notebook    | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Lenovo        | ThinkPad T570 20HAS1PC00    | Notebook    | [218325e9e3](https://linux-hardware.org/?probe=218325e9e3) | Sep 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | Notebook    | [85a0203a02](https://linux-hardware.org/?probe=85a0203a02) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [dd7f2cf2b2](https://linux-hardware.org/?probe=dd7f2cf2b2) | Sep 20, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | Notebook    | [c96d3bf498](https://linux-hardware.org/?probe=c96d3bf498) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | Desktop     | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [fcdaf47870](https://linux-hardware.org/?probe=fcdaf47870) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4dc880c6f](https://linux-hardware.org/?probe=e4dc880c6f) | Sep 20, 2023 |
| Dell          | 0RW199                      | Desktop     | [2857c6ada1](https://linux-hardware.org/?probe=2857c6ada1) | Sep 20, 2023 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [83af285806](https://linux-hardware.org/?probe=83af285806) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [3d4f35cc26](https://linux-hardware.org/?probe=3d4f35cc26) | Sep 19, 2023 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [fcd8ef31df](https://linux-hardware.org/?probe=fcd8ef31df) | Sep 19, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [9fb8b99e70](https://linux-hardware.org/?probe=9fb8b99e70) | Sep 19, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [ca70cb035f](https://linux-hardware.org/?probe=ca70cb035f) | Sep 19, 2023 |
| Biostar       | H61MLC                      | Desktop     | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [f45c7732e3](https://linux-hardware.org/?probe=f45c7732e3) | Sep 19, 2023 |
| AZW           | GTR V21                     | Desktop     | [5066e153f8](https://linux-hardware.org/?probe=5066e153f8) | Sep 19, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [d03b8c1860](https://linux-hardware.org/?probe=d03b8c1860) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [202375fbb7](https://linux-hardware.org/?probe=202375fbb7) | Sep 18, 2023 |
| HP            | 3047h                       | Desktop     | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [9e7069cdc3](https://linux-hardware.org/?probe=9e7069cdc3) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | Notebook    | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | Notebook    | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [08ed0347db](https://linux-hardware.org/?probe=08ed0347db) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [d4d891ca35](https://linux-hardware.org/?probe=d4d891ca35) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [e639402c30](https://linux-hardware.org/?probe=e639402c30) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [b42ad40603](https://linux-hardware.org/?probe=b42ad40603) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [3a230dc10f](https://linux-hardware.org/?probe=3a230dc10f) | Sep 16, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3774dfea8e](https://linux-hardware.org/?probe=3774dfea8e) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [87f26cde55](https://linux-hardware.org/?probe=87f26cde55) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [72503b214c](https://linux-hardware.org/?probe=72503b214c) | Sep 16, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [16c14700d3](https://linux-hardware.org/?probe=16c14700d3) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [00fd2287c0](https://linux-hardware.org/?probe=00fd2287c0) | Sep 16, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [f6be487f38](https://linux-hardware.org/?probe=f6be487f38) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| ASUSTek       | K54C                        | Notebook    | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [5cd83bcad9](https://linux-hardware.org/?probe=5cd83bcad9) | Sep 15, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2c412a10ca](https://linux-hardware.org/?probe=2c412a10ca) | Sep 15, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [def911de73](https://linux-hardware.org/?probe=def911de73) | Sep 14, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [83cb90361c](https://linux-hardware.org/?probe=83cb90361c) | Sep 14, 2023 |
| Itautec       | Infoway                     | Notebook    | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| HP            | Notebook                    | Notebook    | [29f1834722](https://linux-hardware.org/?probe=29f1834722) | Sep 14, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [bba9e61120](https://linux-hardware.org/?probe=bba9e61120) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [3cba209625](https://linux-hardware.org/?probe=3cba209625) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [4dcd4e8234](https://linux-hardware.org/?probe=4dcd4e8234) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [cbfa4c2641](https://linux-hardware.org/?probe=cbfa4c2641) | Sep 13, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b94c2a0420](https://linux-hardware.org/?probe=b94c2a0420) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Sony          | VPCEB1E1E                   | Notebook    | [cbd095ee01](https://linux-hardware.org/?probe=cbd095ee01) | Sep 12, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [5358fa25ef](https://linux-hardware.org/?probe=5358fa25ef) | Sep 12, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | Desktop     | [e4f73d159c](https://linux-hardware.org/?probe=e4f73d159c) | Sep 12, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [8ddbf6665f](https://linux-hardware.org/?probe=8ddbf6665f) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [9fc04871b0](https://linux-hardware.org/?probe=9fc04871b0) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [a80cffbabe](https://linux-hardware.org/?probe=a80cffbabe) | Sep 11, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | Desktop     | [c57a3a012d](https://linux-hardware.org/?probe=c57a3a012d) | Sep 11, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| ASUSTek       | PRIME H370-A                | Desktop     | [c757d0e2c3](https://linux-hardware.org/?probe=c757d0e2c3) | Sep 11, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [39a15ba0ca](https://linux-hardware.org/?probe=39a15ba0ca) | Sep 10, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [26fc33cb75](https://linux-hardware.org/?probe=26fc33cb75) | Sep 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| ASUSTek       | X541UA                      | Notebook    | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [3ee6c9a460](https://linux-hardware.org/?probe=3ee6c9a460) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [6f66e35ec3](https://linux-hardware.org/?probe=6f66e35ec3) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [9306917366](https://linux-hardware.org/?probe=9306917366) | Sep 09, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [382cd978ab](https://linux-hardware.org/?probe=382cd978ab) | Sep 08, 2023 |
| HP            | 8523 A01                    | Mini pc     | [b050702ce4](https://linux-hardware.org/?probe=b050702ce4) | Sep 08, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [c936953cf7](https://linux-hardware.org/?probe=c936953cf7) | Sep 08, 2023 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [1d9d7c7f78](https://linux-hardware.org/?probe=1d9d7c7f78) | Sep 08, 2023 |
| HP            | 8299                        | Desktop     | [df4048bcc4](https://linux-hardware.org/?probe=df4048bcc4) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| Acer          | Aspire X1470                | Desktop     | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | Desktop     | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [6bb77310bf](https://linux-hardware.org/?probe=6bb77310bf) | Sep 06, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [a7e1067ce7](https://linux-hardware.org/?probe=a7e1067ce7) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [53bfbec77e](https://linux-hardware.org/?probe=53bfbec77e) | Sep 06, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3227a8a6bc](https://linux-hardware.org/?probe=3227a8a6bc) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | Notebook    | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Alienware     | 0446JC A01                  | Desktop     | [d0c3088707](https://linux-hardware.org/?probe=d0c3088707) | Sep 06, 2023 |
| Framework     | Laptop                      | Notebook    | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| HP            | 0B54h D                     | Desktop     | [6fc93ef4ee](https://linux-hardware.org/?probe=6fc93ef4ee) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [f8ec276ea3](https://linux-hardware.org/?probe=f8ec276ea3) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [788841792b](https://linux-hardware.org/?probe=788841792b) | Sep 04, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [7f0254a775](https://linux-hardware.org/?probe=7f0254a775) | Sep 04, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Dell          | G15 5511                    | Notebook    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [2c9b64c445](https://linux-hardware.org/?probe=2c9b64c445) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | Notebook    | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [eee58fd067](https://linux-hardware.org/?probe=eee58fd067) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| AMI           | Intel                       | Convertible | [dd24abacfc](https://linux-hardware.org/?probe=dd24abacfc) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [f05f130786](https://linux-hardware.org/?probe=f05f130786) | Sep 02, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [7f9db7db99](https://linux-hardware.org/?probe=7f9db7db99) | Sep 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [027ceec09f](https://linux-hardware.org/?probe=027ceec09f) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [24743bf01d](https://linux-hardware.org/?probe=24743bf01d) | Sep 01, 2023 |
| Dell          | Latitude 5400               | Notebook    | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | Notebook    | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | Notebook    | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [be8b002a45](https://linux-hardware.org/?probe=be8b002a45) | Aug 31, 2023 |
| HP            | 15                          | Notebook    | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | Notebook    | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | Notebook    | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [d963970016](https://linux-hardware.org/?probe=d963970016) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| HP            | 8054                        | Desktop     | [f73271d96e](https://linux-hardware.org/?probe=f73271d96e) | Aug 30, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3fb03adafb](https://linux-hardware.org/?probe=3fb03adafb) | Aug 29, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | Notebook    | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [eba7f74017](https://linux-hardware.org/?probe=eba7f74017) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | Notebook    | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [fffbca3973](https://linux-hardware.org/?probe=fffbca3973) | Aug 28, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Intel         | H61                         | Desktop     | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [cb2419d3df](https://linux-hardware.org/?probe=cb2419d3df) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4357727561](https://linux-hardware.org/?probe=4357727561) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [929efec703](https://linux-hardware.org/?probe=929efec703) | Aug 27, 2023 |
| eMachines     | EL1352                      | Desktop     | [5f9258beb2](https://linux-hardware.org/?probe=5f9258beb2) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Google        | Rammus                      | Notebook    | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| GuoGuang      | IC2M1028N                   | Desktop     | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| Samsung       | 960QFG                      | Convertible | [400b83d634](https://linux-hardware.org/?probe=400b83d634) | Aug 24, 2023 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [42d3a714ac](https://linux-hardware.org/?probe=42d3a714ac) | Aug 24, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | Notebook    | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| AZW           | MINI S                      | Desktop     | [7712e558c5](https://linux-hardware.org/?probe=7712e558c5) | Aug 24, 2023 |
| AZW           | MINI S                      | Desktop     | [6296a4f71d](https://linux-hardware.org/?probe=6296a4f71d) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| HP            | 8299                        | Desktop     | [aa27bed4f1](https://linux-hardware.org/?probe=aa27bed4f1) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | Notebook    | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b52370ec1](https://linux-hardware.org/?probe=9b52370ec1) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [51e91dd03e](https://linux-hardware.org/?probe=51e91dd03e) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [409855b61b](https://linux-hardware.org/?probe=409855b61b) | Aug 21, 2023 |
| Dell          | Precision M4700             | Notebook    | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| HP            | Notebook                    | Notebook    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | Notebook    | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | Notebook    | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | Notebook    | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | Notebook    | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [2ac06099d8](https://linux-hardware.org/?probe=2ac06099d8) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [f06dbc1b8c](https://linux-hardware.org/?probe=f06dbc1b8c) | Aug 19, 2023 |
| HP            | 3047h                       | Desktop     | [91d9eaa1de](https://linux-hardware.org/?probe=91d9eaa1de) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [d109b04177](https://linux-hardware.org/?probe=d109b04177) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| HP            | 3047h                       | Desktop     | [a4aa888c24](https://linux-hardware.org/?probe=a4aa888c24) | Aug 18, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 237       | 5.19%   |
| 5.11.0-38-generic | 180       | 3.94%   |
| 5.11.0-27-generic | 156       | 3.41%   |
| 5.15.0-58-generic | 152       | 3.33%   |
| 5.15.0-46-generic | 152       | 3.33%   |
| 5.15.0-52-generic | 151       | 3.3%    |
| 5.15.0-67-generic | 143       | 3.13%   |
| 5.15.0-91-generic | 141       | 3.09%   |
| 5.15.0-69-generic | 136       | 2.98%   |
| 5.15.0-78-generic | 131       | 2.87%   |
| 5.13.0-30-generic | 126       | 2.76%   |
| 5.11.0-40-generic | 124       | 2.71%   |
| 5.13.0-39-generic | 122       | 2.67%   |
| 5.15.0-60-generic | 109       | 2.39%   |
| 5.11.0-41-generic | 108       | 2.36%   |
| 5.15.0-76-generic | 107       | 2.34%   |
| 5.11.0-37-generic | 107       | 2.34%   |
| 5.15.0-71-generic | 106       | 2.32%   |
| 5.11.0-43-generic | 101       | 2.21%   |
| 5.15.0-48-generic | 95        | 2.08%   |
| 5.11.0-34-generic | 94        | 2.06%   |
| 5.15.0-88-generic | 93        | 2.04%   |
| 5.13.0-40-generic | 90        | 1.97%   |
| 5.15.0-84-generic | 81        | 1.77%   |
| 5.15.0-53-generic | 81        | 1.77%   |
| 5.15.0-41-generic | 77        | 1.68%   |
| 5.13.0-44-generic | 76        | 1.66%   |
| 5.13.0-35-generic | 74        | 1.62%   |
| 5.13.0-28-generic | 73        | 1.6%    |
| 5.15.0-89-generic | 71        | 1.55%   |
| 5.15.0-73-generic | 70        | 1.53%   |
| 5.15.0-86-generic | 68        | 1.49%   |
| 5.15.0-72-generic | 60        | 1.31%   |
| 5.15.0-83-generic | 59        | 1.29%   |
| 5.13.0-52-generic | 59        | 1.29%   |
| 5.13.0-27-generic | 59        | 1.29%   |
| 5.15.0-79-generic | 55        | 1.2%    |
| 5.13.0-41-generic | 54        | 1.18%   |
| 5.15.0-87-generic | 45        | 0.98%   |
| 5.13.0-51-generic | 42        | 0.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 2246      | 54.89%  |
| 5.11.0  | 951       | 23.24%  |
| 5.13.0  | 769       | 18.79%  |
| 5.8.0   | 54        | 1.32%   |
| 5.14.0  | 10        | 0.24%   |
| 6.3.13  | 5         | 0.12%   |
| 6.5.7   | 4         | 0.1%    |
| 5.4.0   | 4         | 0.1%    |
| 6.2.16  | 3         | 0.07%   |
| 6.3.2   | 2         | 0.05%   |
| 6.0.9   | 2         | 0.05%   |
| 5.19.12 | 2         | 0.05%   |
| 5.19.0  | 2         | 0.05%   |
| 5.18.15 | 2         | 0.05%   |
| 5.17.5  | 2         | 0.05%   |
| 5.17.1  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |
| 5.10.0  | 2         | 0.05%   |
| 6.6.7   | 1         | 0.02%   |
| 6.6.1   | 1         | 0.02%   |
| 6.3.1   | 1         | 0.02%   |
| 6.3.0   | 1         | 0.02%   |
| 6.2.7   | 1         | 0.02%   |
| 6.2.14  | 1         | 0.02%   |
| 6.1.8   | 1         | 0.02%   |
| 6.1.7   | 1         | 0.02%   |
| 6.1.22  | 1         | 0.02%   |
| 6.0.8   | 1         | 0.02%   |
| 6.0.19  | 1         | 0.02%   |
| 6.0.0   | 1         | 0.02%   |
| 5.4.180 | 1         | 0.02%   |
| 5.19.9  | 1         | 0.02%   |
| 5.19.6  | 1         | 0.02%   |
| 5.19.2  | 1         | 0.02%   |
| 5.19.14 | 1         | 0.02%   |
| 5.19.1  | 1         | 0.02%   |
| 5.18.6  | 1         | 0.02%   |
| 5.18.19 | 1         | 0.02%   |
| 5.17.9  | 1         | 0.02%   |
| 5.16.5  | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 2249      | 54.97%  |
| 5.11    | 951       | 23.25%  |
| 5.13    | 770       | 18.82%  |
| 5.8     | 54        | 1.32%   |
| 5.14    | 10        | 0.24%   |
| 6.3     | 9         | 0.22%   |
| 5.19    | 9         | 0.22%   |
| 6.2     | 5         | 0.12%   |
| 6.0     | 5         | 0.12%   |
| 5.4     | 5         | 0.12%   |
| 5.17    | 5         | 0.12%   |
| 5.16    | 5         | 0.12%   |
| 6.5     | 4         | 0.1%    |
| 5.18    | 4         | 0.1%    |
| 6.6     | 2         | 0.05%   |
| 6.1     | 2         | 0.05%   |
| 5.10    | 2         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 3930      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 3343      | 84.33%  |
| XFCE       | 569       | 14.35%  |
| Unknown    | 23        | 0.58%   |
| KDE5       | 9         | 0.23%   |
| X-Cinnamon | 5         | 0.13%   |
| Budgie     | 4         | 0.1%    |
| Cinnamon   | 3         | 0.08%   |
| Unity      | 2         | 0.05%   |
| i3         | 2         | 0.05%   |
| MATE       | 1         | 0.03%   |
| LXQt       | 1         | 0.03%   |
| LXDE       | 1         | 0.03%   |
| KDE        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3871      | 97.9%   |
| Wayland | 73        | 1.85%   |
| Unknown | 8         | 0.2%    |
| Tty     | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3061      | 76.79%  |
| GDM     | 419       | 10.51%  |
| GDM3    | 362       | 9.08%   |
| LightDM | 140       | 3.51%   |
| SDDM    | 2         | 0.05%   |
| TDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 1548      | 39.18%  |
| de_DE | 385       | 9.74%   |
| en_GB | 267       | 6.76%   |
| pt_BR | 218       | 5.52%   |
| fr_FR | 149       | 3.77%   |
| es_ES | 126       | 3.19%   |
| it_IT | 123       | 3.11%   |
| en_CA | 109       | 2.76%   |
| en_IN | 100       | 2.53%   |
| pl_PL | 96        | 2.43%   |
| en_AU | 73        | 1.85%   |
| nl_NL | 70        | 1.77%   |
| es_MX | 56        | 1.42%   |
| ru_RU | 48        | 1.21%   |
| en_ZA | 38        | 0.96%   |
| pt_PT | 32        | 0.81%   |
| cs_CZ | 32        | 0.81%   |
| hu_HU | 30        | 0.76%   |
| es_AR | 30        | 0.76%   |
| sv_SE | 25        | 0.63%   |
| tr_TR | 23        | 0.58%   |
| en_NZ | 23        | 0.58%   |
| nl_BE | 20        | 0.51%   |
| es_CL | 19        | 0.48%   |
| de_CH | 19        | 0.48%   |
| fr_BE | 18        | 0.46%   |
| de_AT | 16        | 0.4%    |
| fr_CA | 14        | 0.35%   |
| es_CO | 13        | 0.33%   |
| ja_JP | 12        | 0.3%    |
| fi_FI | 12        | 0.3%    |
| el_GR | 11        | 0.28%   |
| da_DK | 11        | 0.28%   |
| nb_NO | 10        | 0.25%   |
| en_PH | 10        | 0.25%   |
| sk_SK | 9         | 0.23%   |
| es_VE | 9         | 0.23%   |
| ar_EG | 9         | 0.23%   |
| es_CR | 8         | 0.2%    |
| en_IE | 8         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2303      | 57.82%  |
| BIOS | 1680      | 42.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3636      | 91.75%  |
| Tmpfs    | 122       | 3.08%   |
| Zfs      | 72        | 1.82%   |
| Overlay  | 65        | 1.64%   |
| Btrfs    | 41        | 1.03%   |
| Xfs      | 9         | 0.23%   |
| Ext2     | 9         | 0.23%   |
| Ext3     | 7         | 0.18%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3238      | 81.3%   |
| GPT     | 577       | 14.49%  |
| MBR     | 168       | 4.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3829      | 97.16%  |
| Yes       | 112       | 2.84%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3553      | 90.11%  |
| Yes       | 390       | 9.89%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 656       | 16.69%  |
| ASUSTek Computer    | 559       | 14.22%  |
| Lenovo              | 518       | 13.18%  |
| Dell                | 518       | 13.18%  |
| Gigabyte Technology | 223       | 5.67%   |
| Acer                | 206       | 5.24%   |
| MSI                 | 186       | 4.73%   |
| Apple               | 143       | 3.64%   |
| ASRock              | 94        | 2.39%   |
| Toshiba             | 92        | 2.34%   |
| Intel               | 68        | 1.73%   |
| Unknown             | 46        | 1.17%   |
| Samsung Electronics | 41        | 1.04%   |
| Sony                | 35        | 0.89%   |
| Google              | 34        | 0.87%   |
| Fujitsu             | 30        | 0.76%   |
| Microsoft           | 26        | 0.66%   |
| HUAWEI              | 25        | 0.64%   |
| Pegatron            | 21        | 0.53%   |
| Biostar             | 21        | 0.53%   |
| Packard Bell        | 19        | 0.48%   |
| Positivo            | 18        | 0.46%   |
| AZW                 | 17        | 0.43%   |
| Medion              | 16        | 0.41%   |
| Alienware           | 16        | 0.41%   |
| Foxconn             | 15        | 0.38%   |
| Chuwi               | 11        | 0.28%   |
| AMI                 | 11        | 0.28%   |
| Notebook            | 9         | 0.23%   |
| Fujitsu Siemens     | 8         | 0.2%    |
| Multilaser          | 7         | 0.18%   |
| GPU Company         | 7         | 0.18%   |
| Gateway             | 6         | 0.15%   |
| BESSTAR Tech        | 6         | 0.15%   |
| Thomson             | 5         | 0.13%   |
| LG Electronics      | 5         | 0.13%   |
| ECS                 | 5         | 0.13%   |
| TrekStor            | 4         | 0.1%    |
| Semp Toshiba        | 4         | 0.1%    |
| RCA                 | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 59        | 1.5%    |
| ASUS All Series              | 33        | 0.84%   |
| HP Notebook                  | 26        | 0.66%   |
| HP Pavilion Notebook         | 14        | 0.36%   |
| HP 15                        | 13        | 0.33%   |
| Dell OptiPlex 7010           | 13        | 0.33%   |
| MSI MS-7817                  | 9         | 0.23%   |
| HP Pavilion dv7              | 9         | 0.23%   |
| HP Pavilion dv6              | 9         | 0.23%   |
| HP Pavilion 15               | 9         | 0.23%   |
| Dell OptiPlex 790            | 9         | 0.23%   |
| Intel H61                    | 8         | 0.2%    |
| ASUS TUF Gaming X570-PLUS    | 8         | 0.2%    |
| Apple MacBookPro8,1          | 8         | 0.2%    |
| Apple iMac12,2               | 8         | 0.2%    |
| Apple iMac12,1               | 8         | 0.2%    |
| Microsoft Surface Pro        | 7         | 0.18%   |
| Lenovo MIIX 320-10ICR 80XF   | 7         | 0.18%   |
| Dell OptiPlex 780            | 7         | 0.18%   |
| Dell OptiPlex 380            | 7         | 0.18%   |
| ASUS M5A78L-M/USB3           | 7         | 0.18%   |
| Apple MacBookPro12,1         | 7         | 0.18%   |
| Apple iMac10,1               | 7         | 0.18%   |
| MSI MS-7C02                  | 6         | 0.15%   |
| Microsoft Surface Pro 4      | 6         | 0.15%   |
| HP Pavilion g7               | 6         | 0.15%   |
| Gigabyte B450 AORUS M        | 6         | 0.15%   |
| Gigabyte A320M-S2H           | 6         | 0.15%   |
| Dell OptiPlex 3010           | 6         | 0.15%   |
| Dell Latitude E6540          | 6         | 0.15%   |
| Dell Latitude E6520          | 6         | 0.15%   |
| Dell Latitude E6430          | 6         | 0.15%   |
| Dell Inspiron 15-3567        | 6         | 0.15%   |
| ASUS M5A97 R2.0              | 6         | 0.15%   |
| MSI MS-7C37                  | 5         | 0.13%   |
| Lenovo IdeaPad 3 15ALC6 82KU | 5         | 0.13%   |
| HP ProBook 640 G1            | 5         | 0.13%   |
| HP Pavilion g6               | 5         | 0.13%   |
| HP EliteDesk 800 G1 SFF      | 5         | 0.13%   |
| HP EliteBook 8460p           | 5         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 167       | 4.25%   |
| Acer Aspire           | 140       | 3.56%   |
| Dell Inspiron         | 137       | 3.49%   |
| Dell Latitude         | 135       | 3.44%   |
| HP Pavilion           | 130       | 3.31%   |
| Lenovo IdeaPad        | 125       | 3.18%   |
| Dell OptiPlex         | 99        | 2.52%   |
| Toshiba Satellite     | 75        | 1.91%   |
| HP EliteBook          | 71        | 1.81%   |
| HP Compaq             | 61        | 1.55%   |
| Unknown               | 59        | 1.5%    |
| ASUS ROG              | 58        | 1.48%   |
| HP ProBook            | 54        | 1.37%   |
| Lenovo ThinkCentre    | 50        | 1.27%   |
| ASUS PRIME            | 50        | 1.27%   |
| HP Laptop             | 48        | 1.22%   |
| ASUS TUF              | 42        | 1.07%   |
| Dell Precision        | 39        | 0.99%   |
| ASUS VivoBook         | 38        | 0.97%   |
| Lenovo Yoga           | 33        | 0.84%   |
| Dell XPS              | 33        | 0.84%   |
| ASUS All              | 33        | 0.84%   |
| Dell Vostro           | 32        | 0.81%   |
| HP ENVY               | 31        | 0.79%   |
| Microsoft Surface     | 26        | 0.66%   |
| HP Notebook           | 26        | 0.66%   |
| HP EliteDesk          | 23        | 0.59%   |
| HP Stream             | 19        | 0.48%   |
| ASUS ZenBook          | 16        | 0.41%   |
| Apple iMac12          | 16        | 0.41%   |
| Packard Bell EasyNote | 15        | 0.38%   |
| HP 15                 | 15        | 0.38%   |
| ASUS ASUS             | 15        | 0.38%   |
| Lenovo Legion         | 14        | 0.36%   |
| HP OMEN               | 14        | 0.36%   |
| HP ProDesk            | 13        | 0.33%   |
| Gigabyte B450         | 13        | 0.33%   |
| Fujitsu ESPRIMO       | 13        | 0.33%   |
| Lenovo MIIX           | 11        | 0.28%   |
| Lenovo IdeaCentre     | 11        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 329       | 8.37%   |
| 2012    | 328       | 8.35%   |
| 2021    | 323       | 8.22%   |
| 2011    | 321       | 8.17%   |
| 2018    | 299       | 7.61%   |
| 2020    | 292       | 7.43%   |
| 2019    | 269       | 6.84%   |
| 2014    | 263       | 6.69%   |
| 2017    | 255       | 6.49%   |
| 2010    | 222       | 5.65%   |
| 2016    | 210       | 5.34%   |
| 2015    | 197       | 5.01%   |
| 2008    | 165       | 4.2%    |
| 2009    | 145       | 3.69%   |
| 2022    | 123       | 3.13%   |
| 2007    | 96        | 2.44%   |
| 2023    | 58        | 1.48%   |
| 2006    | 26        | 0.66%   |
| 2005    | 6         | 0.15%   |
| Unknown | 3         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2162      | 55.01%  |
| Desktop     | 1429      | 36.36%  |
| Convertible | 102       | 2.6%    |
| All in one  | 94        | 2.39%   |
| Tablet      | 67        | 1.7%    |
| Mini pc     | 66        | 1.68%   |
| Server      | 10        | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3471      | 87.5%   |
| Enabled  | 496       | 12.5%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3892      | 99.03%  |
| Yes  | 38        | 0.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1095      | 27.59%  |
| 3.01-4.0        | 842       | 21.21%  |
| 16.01-24.0      | 687       | 17.31%  |
| 8.01-16.0       | 657       | 16.55%  |
| 32.01-64.0      | 308       | 7.76%   |
| 1.01-2.0        | 180       | 4.54%   |
| 64.01-256.0     | 81        | 2.04%   |
| 2.01-3.0        | 56        | 1.41%   |
| 24.01-32.0      | 54        | 1.36%   |
| 0.51-1.0        | 8         | 0.2%    |
| More than 256.0 | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1570      | 36.46%  |
| 2.01-3.0   | 1426      | 33.12%  |
| 3.01-4.0   | 605       | 14.05%  |
| 4.01-8.0   | 516       | 11.98%  |
| 8.01-16.0  | 85        | 1.97%   |
| 0.51-1.0   | 83        | 1.93%   |
| 16.01-24.0 | 12        | 0.28%   |
| 24.01-32.0 | 6         | 0.14%   |
| 32.01-64.0 | 2         | 0.05%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2565      | 63.82%  |
| 2      | 969       | 24.11%  |
| 3      | 235       | 5.85%   |
| 4      | 119       | 2.96%   |
| 5      | 57        | 1.42%   |
| 6      | 34        | 0.85%   |
| 0      | 15        | 0.37%   |
| 7      | 12        | 0.3%    |
| 8      | 9         | 0.22%   |
| 51     | 1         | 0.02%   |
| 30     | 1         | 0.02%   |
| 11     | 1         | 0.02%   |
| 9      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2272      | 57.5%   |
| Yes       | 1679      | 42.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3286      | 83.42%  |
| No        | 653       | 16.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3136      | 79.45%  |
| No        | 811       | 20.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2357      | 59.39%  |
| No        | 1612      | 40.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 912       | 23.12%  |
| Germany      | 419       | 10.62%  |
| Brazil       | 244       | 6.19%   |
| UK           | 243       | 6.16%   |
| Canada       | 138       | 3.5%    |
| Italy        | 136       | 3.45%   |
| France       | 135       | 3.42%   |
| Spain        | 134       | 3.4%    |
| Netherlands  | 116       | 2.94%   |
| India        | 104       | 2.64%   |
| Poland       | 93        | 2.36%   |
| Mexico       | 75        | 1.9%    |
| Australia    | 75        | 1.9%    |
| Belgium      | 56        | 1.42%   |
| Russia       | 47        | 1.19%   |
| Sweden       | 46        | 1.17%   |
| South Africa | 42        | 1.06%   |
| Austria      | 42        | 1.06%   |
| Portugal     | 41        | 1.04%   |
| Switzerland  | 40        | 1.01%   |
| Argentina    | 39        | 0.99%   |
| Czechia      | 36        | 0.91%   |
| Turkey       | 35        | 0.89%   |
| Hungary      | 34        | 0.86%   |
| Romania      | 31        | 0.79%   |
| Greece       | 31        | 0.79%   |
| Norway       | 29        | 0.74%   |
| New Zealand  | 25        | 0.63%   |
| Japan        | 23        | 0.58%   |
| Denmark      | 23        | 0.58%   |
| Chile        | 23        | 0.58%   |
| Finland      | 22        | 0.56%   |
| Egypt        | 22        | 0.56%   |
| Colombia     | 21        | 0.53%   |
| Indonesia    | 19        | 0.48%   |
| Serbia       | 18        | 0.46%   |
| Bulgaria     | 16        | 0.41%   |
| Ireland      | 14        | 0.35%   |
| Slovakia     | 13        | 0.33%   |
| Malaysia     | 13        | 0.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 37        | 0.9%    |
| Munich            | 26        | 0.63%   |
| Madrid            | 24        | 0.58%   |
| Vienna            | 22        | 0.53%   |
| Athens            | 22        | 0.53%   |
| Sydney            | 21        | 0.51%   |
| Rome              | 21        | 0.51%   |
| Rio de Janeiro    | 20        | 0.48%   |
| New York          | 20        | 0.48%   |
| Hamburg           | 19        | 0.46%   |
| Sao Paulo         | 18        | 0.44%   |
| Milan             | 18        | 0.44%   |
| Amsterdam         | 16        | 0.39%   |
| Paris             | 15        | 0.36%   |
| Montreal          | 15        | 0.36%   |
| Denver            | 15        | 0.36%   |
| Dallas            | 15        | 0.36%   |
| Melbourne         | 13        | 0.31%   |
| London            | 13        | 0.31%   |
| Cape Town         | 13        | 0.31%   |
| Johannesburg      | 12        | 0.29%   |
| Delhi             | 12        | 0.29%   |
| Bucharest         | 12        | 0.29%   |
| Toronto           | 11        | 0.27%   |
| Stockholm         | 11        | 0.27%   |
| Seattle           | 11        | 0.27%   |
| Salt Lake City    | 11        | 0.27%   |
| Phoenix           | 11        | 0.27%   |
| Mexico City       | 11        | 0.27%   |
| Istanbul          | 11        | 0.27%   |
| Houston           | 11        | 0.27%   |
| Frankfurt am Main | 11        | 0.27%   |
| Bogotá           | 11        | 0.27%   |
| Bengaluru         | 11        | 0.27%   |
| Auckland          | 11        | 0.27%   |
| Valencia          | 10        | 0.24%   |
| San José         | 10        | 0.24%   |
| Perth             | 10        | 0.24%   |
| Moscow            | 10        | 0.24%   |
| Krakow            | 10        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 806       | 1163   | 14.48%  |
| Samsung Electronics         | 740       | 1074   | 13.3%   |
| WDC                         | 722       | 1000   | 12.97%  |
| Toshiba                     | 385       | 490    | 6.92%   |
| SanDisk                     | 339       | 432    | 6.09%   |
| Unknown                     | 331       | 467    | 5.95%   |
| Kingston                    | 299       | 422    | 5.37%   |
| Crucial                     | 200       | 243    | 3.59%   |
| Hitachi                     | 169       | 221    | 3.04%   |
| SK hynix                    | 117       | 136    | 2.1%    |
| Intel                       | 113       | 145    | 2.03%   |
| HGST                        | 91        | 113    | 1.63%   |
| China                       | 83        | 100    | 1.49%   |
| Micron Technology           | 79        | 96     | 1.42%   |
| A-DATA Technology           | 71        | 91     | 1.28%   |
| Apple                       | 66        | 76     | 1.19%   |
| Intenso                     | 48        | 51     | 0.86%   |
| Silicon Motion              | 41        | 54     | 0.74%   |
| KIOXIA                      | 38        | 43     | 0.68%   |
| Unknown                     | 37        | 41     | 0.66%   |
| PNY                         | 36        | 48     | 0.65%   |
| Phison                      | 36        | 43     | 0.65%   |
| SPCC                        | 32        | 46     | 0.57%   |
| Patriot                     | 28        | 37     | 0.5%    |
| Netac                       | 28        | 32     | 0.5%    |
| Micron/Crucial Technology   | 26        | 33     | 0.47%   |
| GOODRAM                     | 25        | 30     | 0.45%   |
| JMicron Technology          | 24        | 29     | 0.43%   |
| Phison Electronics          | 21        | 24     | 0.38%   |
| OCZ                         | 19        | 22     | 0.34%   |
| LITEON                      | 18        | 20     | 0.32%   |
| Team                        | 17        | 20     | 0.31%   |
| LITEONIT                    | 17        | 19     | 0.31%   |
| Lexar                       | 17        | 18     | 0.31%   |
| Kingston Technology Company | 16        | 20     | 0.29%   |
| KingSpec                    | 16        | 19     | 0.29%   |
| Transcend                   | 15        | 33     | 0.27%   |
| Hewlett-Packard             | 15        | 21     | 0.27%   |
| Realtek Semiconductor       | 14        | 15     | 0.25%   |
| MAXIO Technology (Hangzhou) | 14        | 14     | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                              | 99        | 1.62%   |
| Unknown MMC Card  32GB                              | 96        | 1.57%   |
| Kingston SA400S37240G 240GB SSD                     | 75        | 1.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 52        | 0.85%   |
| Seagate ST1000LM035-1RK172 1TB                      | 50        | 0.82%   |
| Seagate ST500DM002-1BD142 500GB                     | 49        | 0.8%    |
| Toshiba MQ01ABD100 1TB                              | 45        | 0.74%   |
| Kingston SA400S37480G 480GB SSD                     | 41        | 0.67%   |
| Crucial CT240BX500SSD1 240GB                        | 41        | 0.67%   |
| Unknown MMC Card  128GB                             | 40        | 0.66%   |
| Samsung SSD 860 EVO 500GB                           | 39        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                     | 38        | 0.62%   |
| Unknown                                             | 37        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 35        | 0.57%   |
| Seagate ST500LT012-1DG142 500GB                     | 32        | 0.52%   |
| Unknown SD/MMC/MS PRO 256GB                         | 31        | 0.51%   |
| Toshiba MQ01ABF050 500GB                            | 31        | 0.51%   |
| Seagate ST1000DM010-2EP102 1TB                      | 31        | 0.51%   |
| Samsung SSD 850 EVO 250GB                           | 31        | 0.51%   |
| Toshiba MQ04ABF100 1TB                              | 28        | 0.46%   |
| Samsung SSD 850 EVO 500GB                           | 26        | 0.43%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 26        | 0.43%   |
| Crucial CT500MX500SSD1 500GB                        | 26        | 0.43%   |
| Samsung NVMe SSD Drive 512GB                        | 25        | 0.41%   |
| Samsung NVMe SSD Drive 1TB                          | 25        | 0.41%   |
| Seagate ST9500325AS 500GB                           | 24        | 0.39%   |
| Seagate ST1000DM003-1CH162 1TB                      | 23        | 0.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 23        | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 22        | 0.36%   |
| Seagate Expansion 1TB                               | 21        | 0.34%   |
| SanDisk NVMe SSD Drive 256GB                        | 21        | 0.34%   |
| Samsung SSD 870 EVO 1TB                             | 21        | 0.34%   |
| Samsung NVMe SSD Drive 500GB                        | 21        | 0.34%   |
| Crucial CT1000MX500SSD1 1TB                         | 21        | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 20        | 0.33%   |
| Kingston SV300S37A120G 120GB SSD                    | 20        | 0.33%   |
| Toshiba HDWD110 1TB                                 | 19        | 0.31%   |
| HGST HTS721010A9E630 1TB                            | 19        | 0.31%   |
| Crucial CT480BX500SSD1 480GB                        | 19        | 0.31%   |
| Unknown MMC Card  16GB                              | 18        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 794       | 1134   | 36.31%  |
| WDC                 | 618       | 846    | 28.26%  |
| Toshiba             | 300       | 388    | 13.72%  |
| Hitachi             | 169       | 221    | 7.73%   |
| HGST                | 91        | 113    | 4.16%   |
| Samsung Electronics | 89        | 109    | 4.07%   |
| Unknown             | 32        | 40     | 1.46%   |
| Apple               | 29        | 33     | 1.33%   |
| JMicron Technology  | 16        | 18     | 0.73%   |
| Maxtor              | 13        | 17     | 0.59%   |
| Fujitsu             | 13        | 15     | 0.59%   |
| Hewlett-Packard     | 4         | 7      | 0.18%   |
| Intenso             | 3         | 3      | 0.14%   |
| USB3.0              | 2         | 3      | 0.09%   |
| SSK                 | 2         | 2      | 0.09%   |
| XrayDisk            | 1         | 1      | 0.05%   |
| WD MediaMax         | 1         | 1      | 0.05%   |
| Unknown (CF)        | 1         | 1      | 0.05%   |
| TO Exter            | 1         | 1      | 0.05%   |
| TDAS                | 1         | 3      | 0.05%   |
| SABRENT             | 1         | 1      | 0.05%   |
| QUANTUM             | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| HGST HTS            | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |
| ACASIS              | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 374       | 529    | 19.45%  |
| Kingston            | 250       | 339    | 13%     |
| Crucial             | 191       | 232    | 9.93%   |
| SanDisk             | 181       | 231    | 9.41%   |
| WDC                 | 84        | 109    | 4.37%   |
| China               | 82        | 99     | 4.26%   |
| A-DATA Technology   | 62        | 82     | 3.22%   |
| Intel               | 43        | 50     | 2.24%   |
| Toshiba             | 40        | 47     | 2.08%   |
| PNY                 | 36        | 48     | 1.87%   |
| SK hynix            | 33        | 33     | 1.72%   |
| Micron Technology   | 33        | 38     | 1.72%   |
| Intenso             | 32        | 34     | 1.66%   |
| SPCC                | 31        | 45     | 1.61%   |
| Apple               | 31        | 35     | 1.61%   |
| Netac               | 28        | 31     | 1.46%   |
| Patriot             | 27        | 36     | 1.4%    |
| GOODRAM             | 23        | 28     | 1.2%    |
| OCZ                 | 18        | 21     | 0.94%   |
| LITEON              | 18        | 20     | 0.94%   |
| Team                | 17        | 20     | 0.88%   |
| LITEONIT            | 17        | 19     | 0.88%   |
| Lexar               | 16        | 17     | 0.83%   |
| Transcend           | 15        | 33     | 0.78%   |
| KingSpec            | 15        | 18     | 0.78%   |
| Unknown             | 12        | 15     | 0.62%   |
| Apacer              | 11        | 14     | 0.57%   |
| SABRENT             | 10        | 12     | 0.52%   |
| Hewlett-Packard     | 10        | 13     | 0.52%   |
| Gigabyte Technology | 9         | 10     | 0.47%   |
| Fanxiang            | 7         | 8      | 0.36%   |
| Leven               | 6         | 7      | 0.31%   |
| ASMT                | 6         | 6      | 0.31%   |
| Verbatim            | 5         | 5      | 0.26%   |
| Teclast             | 5         | 5      | 0.26%   |
| Plextor             | 5         | 6      | 0.26%   |
| Phison              | 5         | 8      | 0.26%   |
| Mushkin             | 5         | 5      | 0.26%   |
| FORESEE             | 5         | 6      | 0.26%   |
| Super Talent        | 4         | 5      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1877      | 2963   | 37.17%  |
| SSD     | 1726      | 2483   | 34.18%  |
| NVMe    | 1018      | 1413   | 20.16%  |
| MMC     | 309       | 419    | 6.12%   |
| Unknown | 120       | 156    | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3048      | 5261   | 66.25%  |
| NVMe | 1017      | 1409   | 22.1%   |
| MMC  | 309       | 419    | 6.72%   |
| SAS  | 227       | 345    | 4.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2258      | 3328   | 60.83%  |
| 0.51-1.0   | 1032      | 1446   | 27.8%   |
| 1.01-2.0   | 261       | 366    | 7.03%   |
| 3.01-4.0   | 62        | 132    | 1.67%   |
| 4.01-10.0  | 53        | 82     | 1.43%   |
| 2.01-3.0   | 39        | 65     | 1.05%   |
| 10.01-20.0 | 6         | 25     | 0.16%   |
| 20.01-50.0 | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1315      | 32.25%  |
| 251-500        | 992       | 24.33%  |
| 501-1000       | 623       | 15.28%  |
| 51-100         | 338       | 8.29%   |
| 1001-2000      | 248       | 6.08%   |
| 21-50          | 191       | 4.68%   |
| More than 3000 | 147       | 3.6%    |
| 1-20           | 97        | 2.38%   |
| 2001-3000      | 76        | 1.86%   |
| Unknown        | 51        | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1556      | 36.4%   |
| 21-50          | 1219      | 28.51%  |
| 51-100         | 521       | 12.19%  |
| 101-250        | 423       | 9.89%   |
| 251-500        | 225       | 5.26%   |
| 501-1000       | 134       | 3.13%   |
| More than 3000 | 66        | 1.54%   |
| 1001-2000      | 57        | 1.33%   |
| Unknown        | 51        | 1.19%   |
| 2001-3000      | 23        | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                   | 4         | 4      | 3.48%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 2.61%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.61%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 2         | 2      | 1.74%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 1.74%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.74%   |
| Seagate ST9500420AS 500GB                | 2         | 2      | 1.74%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 1.74%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.74%   |
| Seagate ST500DM002-1BD142 500GB          | 2         | 2      | 1.74%   |
| Seagate ST1000LM048-2E7172 1TB           | 2         | 2      | 1.74%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 1.74%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 1.74%   |
| HGST HTS545050A7E380 500GB               | 2         | 3      | 1.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1         | 1      | 0.87%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.87%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.87%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.87%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 0.87%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 0.87%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 0.87%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1         | 1      | 0.87%   |
| WDC WD20EZRX-22D8PB0 2TB                 | 1         | 1      | 0.87%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1         | 1      | 0.87%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 0.87%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 0.87%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 0.87%   |
| WDC WD Green 2.5 1000GB SSD              | 1         | 1      | 0.87%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.87%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.87%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 0.87%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 0.87%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 0.87%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 0.87%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 0.87%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 0.87%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 0.87%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 39     | 33.33%  |
| WDC                 | 19        | 20     | 16.67%  |
| Toshiba             | 15        | 15     | 13.16%  |
| HGST                | 11        | 12     | 9.65%   |
| Kingston            | 6         | 6      | 5.26%   |
| Samsung Electronics | 5         | 5      | 4.39%   |
| Hitachi             | 3         | 3      | 2.63%   |
| SK hynix            | 2         | 2      | 1.75%   |
| Intel               | 2         | 2      | 1.75%   |
| A-DATA Technology   | 2         | 2      | 1.75%   |
| Teclast             | 1         | 1      | 0.88%   |
| Silicon Motion      | 1         | 1      | 0.88%   |
| POLION              | 1         | 1      | 0.88%   |
| OCZ                 | 1         | 1      | 0.88%   |
| Netac               | 1         | 1      | 0.88%   |
| Maxtor              | 1         | 1      | 0.88%   |
| LITEONIT            | 1         | 1      | 0.88%   |
| Hewlett-Packard     | 1         | 1      | 0.88%   |
| Drevo               | 1         | 1      | 0.88%   |
| China               | 1         | 1      | 0.88%   |
| Unknown             | 1         | 1      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 39     | 44.71%  |
| WDC                 | 17        | 18     | 20%     |
| Toshiba             | 12        | 12     | 14.12%  |
| HGST                | 11        | 12     | 12.94%  |
| Samsung Electronics | 3         | 3      | 3.53%   |
| Hitachi             | 3         | 3      | 3.53%   |
| Maxtor              | 1         | 1      | 1.18%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 81        | 88     | 73.64%  |
| SSD  | 25        | 25     | 22.73%  |
| NVMe | 4         | 4      | 3.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3483      | 6572   | 85.72%  |
| Works    | 469       | 742    | 11.54%  |
| Malfunc  | 108       | 117    | 2.66%   |
| Failed   | 2         | 2      | 0.05%   |
| Fixed    | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2677      | 56.95%  |
| AMD                              | 727       | 15.46%  |
| Samsung Electronics              | 350       | 7.45%   |
| SanDisk                          | 179       | 3.81%   |
| SK hynix                         | 79        | 1.68%   |
| Kingston Technology Company      | 72        | 1.53%   |
| Nvidia                           | 68        | 1.45%   |
| ASMedia Technology               | 61        | 1.3%    |
| Phison Electronics               | 58        | 1.23%   |
| Micron Technology                | 47        | 1%      |
| Silicon Motion                   | 46        | 0.98%   |
| Toshiba America Info Systems     | 45        | 0.96%   |
| KIOXIA                           | 40        | 0.85%   |
| JMicron Technology               | 40        | 0.85%   |
| Marvell Technology Group         | 37        | 0.79%   |
| Micron/Crucial Technology        | 35        | 0.74%   |
| ADATA Technology                 | 22        | 0.47%   |
| MAXIO Technology (Hangzhou)      | 16        | 0.34%   |
| Realtek Semiconductor            | 15        | 0.32%   |
| VIA Technologies                 | 11        | 0.23%   |
| Seagate Technology               | 9         | 0.19%   |
| Silicon Image                    | 8         | 0.17%   |
| Union Memory (Shenzhen)          | 7         | 0.15%   |
| Solid State Storage Technology   | 6         | 0.13%   |
| Lite-On Technology               | 6         | 0.13%   |
| Apple                            | 5         | 0.11%   |
| Shenzhen Longsys Electronics     | 4         | 0.09%   |
| LSI Logic / Symbios Logic        | 4         | 0.09%   |
| INNOGRIT                         | 4         | 0.09%   |
| Broadcom / LSI                   | 4         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| OCZ Technology Group             | 2         | 0.04%   |
| Netac Technology                 | 2         | 0.04%   |
| Lenovo                           | 2         | 0.04%   |
| TenaFe                           | 1         | 0.02%   |
| Nextorage                        | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 478       | 8.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 201       | 3.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 199       | 3.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 193       | 3.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 145       | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 137       | 2.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 134       | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 112       | 2.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 101       | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 90        | 1.66%   |
| Intel Volume Management Device NVMe RAID Controller                            | 89        | 1.64%   |
| AMD 400 Series Chipset SATA Controller                                         | 87        | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 85        | 1.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 84        | 1.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 81        | 1.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 79        | 1.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 77        | 1.42%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 74        | 1.37%   |
| Intel SATA Controller [RAID mode]                                              | 73        | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 73        | 1.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 71        | 1.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 71        | 1.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 69        | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 63        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 59        | 1.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 55        | 1.02%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 55        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 54        | 1%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 52        | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 51        | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 49        | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 46        | 0.85%   |
| AMD 500 Series Chipset SATA Controller                                         | 46        | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 43        | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                            | 42        | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 42        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                          | 40        | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 36        | 0.66%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 36        | 0.66%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 35        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2917      | 60.41%  |
| NVMe | 1017      | 21.06%  |
| IDE  | 534       | 11.06%  |
| RAID | 350       | 7.25%   |
| SAS  | 8         | 0.17%   |
| SCSI | 3         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3077      | 78.3%   |
| AMD    | 853       | 21.7%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 52        | 1.32%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 42        | 1.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 40        | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 34        | 0.86%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 34        | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 29        | 0.74%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 28        | 0.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 28        | 0.71%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 28        | 0.71%   |
| AMD Ryzen 5 3600 6-Core Processor             | 28        | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 27        | 0.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 24        | 0.61%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 23        | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 0.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 22        | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 0.56%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 22        | 0.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 21        | 0.53%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 0.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 20        | 0.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 20        | 0.51%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.46%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 18        | 0.46%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 17        | 0.43%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.43%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 17        | 0.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 16        | 0.41%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 16        | 0.41%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 16        | 0.41%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 16        | 0.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.38%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 15        | 0.38%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 15        | 0.38%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 15        | 0.38%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 15        | 0.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 15        | 0.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 15        | 0.38%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 15        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 911       | 23.16%  |
| Intel Core i7           | 565       | 14.37%  |
| Intel Core i3           | 365       | 9.28%   |
| Intel Celeron           | 270       | 6.86%   |
| Other                   | 240       | 6.1%    |
| AMD Ryzen 5             | 204       | 5.19%   |
| Intel Core 2 Duo        | 192       | 4.88%   |
| Intel Atom              | 124       | 3.15%   |
| AMD Ryzen 7             | 123       | 3.13%   |
| Intel Pentium           | 113       | 2.87%   |
| Intel Xeon              | 85        | 2.16%   |
| AMD Ryzen 9             | 59        | 1.5%    |
| AMD FX                  | 58        | 1.47%   |
| Intel Pentium Dual-Core | 55        | 1.4%    |
| AMD A6                  | 48        | 1.22%   |
| AMD Ryzen 3             | 38        | 0.97%   |
| Intel Core 2 Quad       | 36        | 0.92%   |
| AMD A8                  | 36        | 0.92%   |
| AMD A10                 | 35        | 0.89%   |
| Intel Pentium Dual      | 34        | 0.86%   |
| AMD A4                  | 33        | 0.84%   |
| AMD Athlon II X2        | 25        | 0.64%   |
| Intel Core 2            | 23        | 0.58%   |
| AMD Phenom II X4        | 19        | 0.48%   |
| AMD E1                  | 17        | 0.43%   |
| Intel Pentium Silver    | 16        | 0.41%   |
| Intel Core i9           | 15        | 0.38%   |
| AMD Athlon 64 X2        | 13        | 0.33%   |
| Intel Core M            | 12        | 0.31%   |
| AMD Athlon              | 12        | 0.31%   |
| Intel Pentium Gold      | 11        | 0.28%   |
| AMD Phenom II X6        | 11        | 0.28%   |
| AMD E                   | 11        | 0.28%   |
| AMD Turion 64 X2 Mobile | 8         | 0.2%    |
| Intel Pentium 4         | 7         | 0.18%   |
| AMD E2                  | 7         | 0.18%   |
| AMD Athlon II X4        | 7         | 0.18%   |
| AMD Athlon II           | 6         | 0.15%   |
| Intel Core m5           | 5         | 0.13%   |
| AMD Ryzen 7 PRO         | 5         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1827      | 46.44%  |
| 4      | 1411      | 35.87%  |
| 6      | 295       | 7.5%    |
| 8      | 205       | 5.21%   |
| 1      | 54        | 1.37%   |
| 12     | 48        | 1.22%   |
| 10     | 27        | 0.69%   |
| 16     | 26        | 0.66%   |
| 3      | 22        | 0.56%   |
| 14     | 12        | 0.31%   |
| 24     | 4         | 0.1%    |
| 28     | 2         | 0.05%   |
| 40     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3914      | 99.59%  |
| 2      | 16        | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2375      | 60.42%  |
| 1      | 1556      | 39.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3930      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 298       | 7.46%   |
| 0x306a9    | 296       | 7.41%   |
| Unknown    | 288       | 7.21%   |
| 0x306c3    | 232       | 5.81%   |
| 0x1067a    | 189       | 4.73%   |
| 0x40651    | 113       | 2.83%   |
| 0x806c1    | 106       | 2.65%   |
| 0x406e3    | 104       | 2.6%    |
| 0x20655    | 99        | 2.48%   |
| 0x806e9    | 96        | 2.4%    |
| 0x306d4    | 89        | 2.23%   |
| 0x506e3    | 85        | 2.13%   |
| 0x30678    | 83        | 2.08%   |
| 0x406c4    | 82        | 2.05%   |
| 0x906ea    | 72        | 1.8%    |
| 0x806ec    | 71        | 1.78%   |
| 0x806ea    | 71        | 1.78%   |
| 0x906e9    | 66        | 1.65%   |
| 0x706a8    | 63        | 1.58%   |
| 0x6fd      | 62        | 1.55%   |
| 0x08701021 | 51        | 1.28%   |
| 0x08108109 | 49        | 1.23%   |
| 0x506c9    | 46        | 1.15%   |
| 0x706e5    | 44        | 1.1%    |
| 0x20652    | 40        | 1%      |
| 0x10676    | 40        | 1%      |
| 0x010000c8 | 39        | 0.98%   |
| 0x06000852 | 38        | 0.95%   |
| 0x406c3    | 33        | 0.83%   |
| 0x6fb      | 31        | 0.78%   |
| 0x0a50000c | 31        | 0.78%   |
| 0x06001119 | 29        | 0.73%   |
| 0x0800820d | 27        | 0.68%   |
| 0x07030105 | 27        | 0.68%   |
| 0x08600106 | 26        | 0.65%   |
| 0x06006705 | 26        | 0.65%   |
| 0xa0655    | 25        | 0.63%   |
| 0xa0653    | 24        | 0.6%    |
| 0x0a50000d | 23        | 0.58%   |
| 0x08608103 | 23        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 462       | 11.75%  |
| Haswell          | 381       | 9.69%   |
| SandyBridge      | 321       | 8.16%   |
| IvyBridge        | 318       | 8.09%   |
| Penryn           | 236       | 6%      |
| Silvermont       | 214       | 5.44%   |
| Skylake          | 198       | 5.04%   |
| Westmere         | 151       | 3.84%   |
| Core             | 135       | 3.43%   |
| Zen 2            | 123       | 3.13%   |
| TigerLake        | 120       | 3.05%   |
| Zen 3            | 112       | 2.85%   |
| Zen+             | 102       | 2.59%   |
| Unknown          | 101       | 2.57%   |
| Broadwell        | 96        | 2.44%   |
| Goldmont plus    | 88        | 2.24%   |
| K10              | 87        | 2.21%   |
| CometLake        | 77        | 1.96%   |
| Piledriver       | 74        | 1.88%   |
| IceLake          | 73        | 1.86%   |
| Excavator        | 68        | 1.73%   |
| Zen              | 55        | 1.4%    |
| Goldmont         | 49        | 1.25%   |
| Puma             | 42        | 1.07%   |
| Alderlake Hybrid | 39        | 0.99%   |
| Nehalem          | 38        | 0.97%   |
| K8 Hammer        | 28        | 0.71%   |
| Jaguar           | 26        | 0.66%   |
| Bobcat           | 21        | 0.53%   |
| K10 Llano        | 18        | 0.46%   |
| Steamroller      | 17        | 0.43%   |
| Bulldozer        | 16        | 0.41%   |
| Bonnell          | 16        | 0.41%   |
| Tremont          | 15        | 0.38%   |
| NetBurst         | 10        | 0.25%   |
| K8 & K10 hybrid  | 5         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2402      | 53.27%  |
| Nvidia                           | 1070      | 23.73%  |
| AMD                              | 1021      | 22.64%  |
| Matrox Electronics Systems       | 6         | 0.13%   |
| VIA Technologies                 | 4         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| ASPEED Technology                | 2         | 0.04%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 245       | 5.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 187       | 4.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 117       | 2.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 115       | 2.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 100       | 2.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 96        | 2.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 95        | 2.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 95        | 2.05%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 91        | 1.97%   |
| Intel HD Graphics 620                                                                    | 81        | 1.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 77        | 1.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 72        | 1.55%   |
| Intel UHD Graphics 620                                                                   | 71        | 1.53%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 71        | 1.53%   |
| Intel HD Graphics 5500                                                                   | 56        | 1.21%   |
| Intel HD Graphics 630                                                                    | 54        | 1.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 54        | 1.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 51        | 1.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 50        | 1.08%   |
| Intel HD Graphics 530                                                                    | 49        | 1.06%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 48        | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 44        | 0.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 43        | 0.93%   |
| Intel HD Graphics 500                                                                    | 42        | 0.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 0.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 41        | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 38        | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 38        | 0.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 38        | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 37        | 0.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 35        | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 32        | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 32        | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 32        | 0.69%   |
| AMD Lucienne                                                                             | 32        | 0.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 28        | 0.6%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 27        | 0.58%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 25        | 0.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 24        | 0.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 23        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 1901      | 48.13%  |
| 1 x AMD              | 822       | 20.81%  |
| 1 x Nvidia           | 650       | 16.46%  |
| Intel + Nvidia       | 347       | 8.78%   |
| Intel + AMD          | 94        | 2.38%   |
| 2 x AMD              | 53        | 1.34%   |
| AMD + Nvidia         | 53        | 1.34%   |
| 2 x Nvidia           | 7         | 0.18%   |
| Other                | 6         | 0.15%   |
| 1 x VIA              | 4         | 0.1%    |
| 1 x Matrox           | 4         | 0.1%    |
| 1 x SiS              | 3         | 0.08%   |
| 1 x ASPEED           | 2         | 0.05%   |
| 2 x Intel            | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.03%   |
| Nvidia + Matrox      | 1         | 0.03%   |
| AMD + Matrox         | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3188      | 80.59%  |
| Proprietary | 624       | 15.77%  |
| Unknown     | 144       | 3.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2385      | 59.65%  |
| 0.01-0.5   | 474       | 11.86%  |
| 1.01-2.0   | 368       | 9.2%    |
| 0.51-1.0   | 325       | 8.13%   |
| 3.01-4.0   | 182       | 4.55%   |
| 7.01-8.0   | 128       | 3.2%    |
| 5.01-6.0   | 56        | 1.4%    |
| 8.01-16.0  | 43        | 1.08%   |
| 2.01-3.0   | 33        | 0.83%   |
| 16.01-24.0 | 4         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 511       | 12.82%  |
| AU Optronics            | 473       | 11.87%  |
| BOE                     | 353       | 8.86%   |
| Chimei Innolux          | 348       | 8.73%   |
| LG Display              | 342       | 8.58%   |
| Dell                    | 189       | 4.74%   |
| Goldstar                | 178       | 4.47%   |
| Hewlett-Packard         | 142       | 3.56%   |
| Apple                   | 123       | 3.09%   |
| Acer                    | 114       | 2.86%   |
| AOC                     | 89        | 2.23%   |
| Philips                 | 88        | 2.21%   |
| Lenovo                  | 72        | 1.81%   |
| Ancor Communications    | 68        | 1.71%   |
| Chi Mei Optoelectronics | 67        | 1.68%   |
| BenQ                    | 64        | 1.61%   |
| Sharp                   | 54        | 1.35%   |
| Sony                    | 33        | 0.83%   |
| LG Philips              | 32        | 0.8%    |
| ViewSonic               | 31        | 0.78%   |
| LG Electronics          | 31        | 0.78%   |
| PANDA                   | 29        | 0.73%   |
| InfoVision              | 29        | 0.73%   |
| Unknown                 | 29        | 0.73%   |
| Unknown                 | 25        | 0.63%   |
| Vizio                   | 23        | 0.58%   |
| ASUSTek Computer        | 23        | 0.58%   |
| Iiyama                  | 21        | 0.53%   |
| Fujitsu Siemens         | 16        | 0.4%    |
| Sceptre Tech            | 15        | 0.38%   |
| Toshiba                 | 13        | 0.33%   |
| Panasonic               | 13        | 0.33%   |
| NEC Computers           | 13        | 0.33%   |
| Eizo                    | 13        | 0.33%   |
| CPT                     | 12        | 0.3%    |
| MSI                     | 11        | 0.28%   |
| HPN                     | 10        | 0.25%   |
| HannStar                | 10        | 0.25%   |
| FUS                     | 7         | 0.18%   |
| Microstep               | 6         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 29        | 0.71%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 22        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 20        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 18        | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.39%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 15        | 0.37%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 15        | 0.37%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.37%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 14        | 0.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 13        | 0.32%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 0.29%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 12        | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.29%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 11        | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 11        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 10        | 0.24%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 9         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 9         | 0.22%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 9         | 0.22%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 9         | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 8         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 8         | 0.2%    |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                         | 8         | 0.2%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 7         | 0.17%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.17%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 7         | 0.17%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 7         | 0.17%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 7         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1481      | 38.12%  |
| 1366x768 (WXGA)    | 963       | 24.79%  |
| 3840x2160 (4K)     | 204       | 5.25%   |
| 1600x900 (HD+)     | 204       | 5.25%   |
| 2560x1440 (QHD)    | 112       | 2.88%   |
| 1280x800 (WXGA)    | 108       | 2.78%   |
| 1680x1050 (WSXGA+) | 107       | 2.75%   |
| 1440x900 (WXGA+)   | 106       | 2.73%   |
| 1280x1024 (SXGA)   | 95        | 2.45%   |
| Unknown            | 70        | 1.8%    |
| 1920x1200 (WUXGA)  | 59        | 1.52%   |
| 1360x768           | 42        | 1.08%   |
| 3440x1440          | 39        | 1%      |
| 3840x1080          | 36        | 0.93%   |
| 2560x1080          | 32        | 0.82%   |
| 2560x1600          | 31        | 0.8%    |
| 2736x1824          | 18        | 0.46%   |
| 1920x540           | 18        | 0.46%   |
| 2880x1800          | 12        | 0.31%   |
| 2160x1440          | 12        | 0.31%   |
| 3200x1800 (QHD+)   | 10        | 0.26%   |
| 2256x1504          | 10        | 0.26%   |
| 1024x768 (XGA)     | 9         | 0.23%   |
| 1600x1200          | 8         | 0.21%   |
| 3840x2400          | 7         | 0.18%   |
| 1280x720 (HD)      | 7         | 0.18%   |
| 1024x600           | 5         | 0.13%   |
| 5760x1080          | 4         | 0.1%    |
| 3840x1600          | 4         | 0.1%    |
| 1920x1280          | 4         | 0.1%    |
| 4480x1440          | 3         | 0.08%   |
| 3600x1080          | 3         | 0.08%   |
| 2880x1920          | 3         | 0.08%   |
| 1920x515           | 3         | 0.08%   |
| 7680x2160          | 2         | 0.05%   |
| 5760x2160          | 2         | 0.05%   |
| 5120x1440          | 2         | 0.05%   |
| 4480x1600          | 2         | 0.05%   |
| 4480x1080          | 2         | 0.05%   |
| 3360x1080          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1011      | 25.6%   |
| 13      | 383       | 9.7%    |
| Unknown | 311       | 7.88%   |
| 14      | 298       | 7.55%   |
| 17      | 228       | 5.77%   |
| 27      | 220       | 5.57%   |
| 24      | 193       | 4.89%   |
| 21      | 182       | 4.61%   |
| 23      | 175       | 4.43%   |
| 19      | 107       | 2.71%   |
| 11      | 98        | 2.48%   |
| 31      | 91        | 2.3%    |
| 12      | 87        | 2.2%    |
| 20      | 82        | 2.08%   |
| 18      | 82        | 2.08%   |
| 22      | 69        | 1.75%   |
| 34      | 53        | 1.34%   |
| 16      | 31        | 0.79%   |
| 40      | 28        | 0.71%   |
| 54      | 23        | 0.58%   |
| 84      | 22        | 0.56%   |
| 72      | 19        | 0.48%   |
| 32      | 17        | 0.43%   |
| 26      | 16        | 0.41%   |
| 10      | 15        | 0.38%   |
| 25      | 12        | 0.3%    |
| 52      | 8         | 0.2%    |
| 49      | 8         | 0.2%    |
| 36      | 7         | 0.18%   |
| 65      | 6         | 0.15%   |
| 48      | 6         | 0.15%   |
| 28      | 5         | 0.13%   |
| 46      | 4         | 0.1%    |
| 37      | 4         | 0.1%    |
| 29      | 4         | 0.1%    |
| 74      | 3         | 0.08%   |
| 64      | 3         | 0.08%   |
| 58      | 3         | 0.08%   |
| 42      | 3         | 0.08%   |
| 39      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1536      | 39.47%  |
| 501-600        | 554       | 14.23%  |
| 401-500        | 463       | 11.9%   |
| 201-300        | 385       | 9.89%   |
| Unknown        | 311       | 7.99%   |
| 351-400        | 271       | 6.96%   |
| 601-700        | 125       | 3.21%   |
| 701-800        | 80        | 2.06%   |
| 1001-1500      | 73        | 1.88%   |
| 1501-2000      | 47        | 1.21%   |
| 801-900        | 38        | 0.98%   |
| 901-1000       | 6         | 0.15%   |
| 101-200        | 2         | 0.05%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2707      | 73.96%  |
| 16/10   | 426       | 11.64%  |
| Unknown | 276       | 7.54%   |
| 5/4     | 86        | 2.35%   |
| 21/9    | 61        | 1.67%   |
| 3/2     | 54        | 1.48%   |
| 4/3     | 26        | 0.71%   |
| 32/9    | 12        | 0.33%   |
| 6/5     | 5         | 0.14%   |
| 3.73    | 3         | 0.08%   |
| 0.62    | 2         | 0.05%   |
| 1.00    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1005      | 25.61%  |
| 81-90          | 548       | 13.97%  |
| 201-250        | 499       | 12.72%  |
| Unknown        | 311       | 7.93%   |
| 151-200        | 256       | 6.52%   |
| 301-350        | 229       | 5.84%   |
| 351-500        | 171       | 4.36%   |
| 121-130        | 158       | 4.03%   |
| 71-80          | 145       | 3.7%    |
| 141-150        | 112       | 2.85%   |
| More than 1000 | 110       | 2.8%    |
| 51-60          | 100       | 2.55%   |
| 61-70          | 73        | 1.86%   |
| 251-300        | 69        | 1.76%   |
| 501-1000       | 60        | 1.53%   |
| 111-120        | 27        | 0.69%   |
| 131-140        | 26        | 0.66%   |
| 41-50          | 13        | 0.33%   |
| 91-100         | 10        | 0.25%   |
| 1-40           | 2         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1150      | 30%     |
| 51-100        | 1119      | 29.19%  |
| 121-160       | 880       | 22.96%  |
| Unknown       | 311       | 8.11%   |
| 161-240       | 202       | 5.27%   |
| 1-50          | 108       | 2.82%   |
| More than 240 | 63        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3343      | 83.58%  |
| 2     | 474       | 11.85%  |
| 0     | 143       | 3.58%   |
| 3     | 35        | 0.88%   |
| 4     | 4         | 0.1%    |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2111      | 35.27%  |
| Intel                             | 1722      | 28.77%  |
| Qualcomm Atheros                  | 718       | 11.99%  |
| Broadcom                          | 423       | 7.07%   |
| Broadcom Limited                  | 121       | 2.02%   |
| TP-Link                           | 88        | 1.47%   |
| Ralink Technology                 | 87        | 1.45%   |
| Marvell Technology Group          | 83        | 1.39%   |
| MediaTek                          | 70        | 1.17%   |
| Ralink                            | 69        | 1.15%   |
| Nvidia                            | 60        | 1%      |
| Samsung Electronics               | 40        | 0.67%   |
| ASIX Electronics                  | 32        | 0.53%   |
| NetGear                           | 25        | 0.42%   |
| Dell                              | 25        | 0.42%   |
| DisplayLink                       | 21        | 0.35%   |
| Xiaomi                            | 19        | 0.32%   |
| Qualcomm Atheros Communications   | 17        | 0.28%   |
| Sierra Wireless                   | 16        | 0.27%   |
| Microsoft                         | 16        | 0.27%   |
| Huawei Technologies               | 16        | 0.27%   |
| JMicron Technology                | 13        | 0.22%   |
| D-Link System                     | 13        | 0.22%   |
| D-Link                            | 13        | 0.22%   |
| Hewlett-Packard                   | 12        | 0.2%    |
| OPPO Electronics                  | 10        | 0.17%   |
| Edimax Technology                 | 10        | 0.17%   |
| ASUSTek Computer                  | 10        | 0.17%   |
| Motorola PCS                      | 8         | 0.13%   |
| Qualcomm                          | 7         | 0.12%   |
| Linksys                           | 7         | 0.12%   |
| Ericsson Business Mobile Networks | 7         | 0.12%   |
| Aquantia                          | 6         | 0.1%    |
| T & A Mobile Phones               | 5         | 0.08%   |
| Google                            | 5         | 0.08%   |
| Belkin Components                 | 5         | 0.08%   |
| VIA Technologies                  | 4         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.07%   |
| ZyDAS                             | 3         | 0.05%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1325      | 19%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 314       | 4.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 175       | 2.51%   |
| Intel Wi-Fi 6 AX200                                                    | 119       | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 117       | 1.68%   |
| Intel Wireless 7265                                                    | 113       | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 102       | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 99        | 1.42%   |
| Intel Wireless 7260                                                    | 94        | 1.35%   |
| Intel Wireless 8265 / 8275                                             | 92        | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                      | 83        | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 83        | 1.19%   |
| Intel Wi-Fi 6 AX201                                                    | 83        | 1.19%   |
| Intel Ethernet Connection I217-LM                                      | 82        | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 80        | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 65        | 0.93%   |
| Intel Wireless 3165                                                    | 64        | 0.92%   |
| Intel Wireless 8260                                                    | 63        | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                          | 61        | 0.87%   |
| Intel I211 Gigabit Network Connection                                  | 60        | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 59        | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 56        | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 55        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 49        | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 48        | 0.69%   |
| Realtek 802.11ac NIC                                                   | 48        | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 47        | 0.67%   |
| Intel Ethernet Controller I225-V                                       | 43        | 0.62%   |
| Intel Ethernet Connection (2) I219-V                                   | 43        | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 41        | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 41        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 39        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 39        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                        | 38        | 0.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 38        | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 37        | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 36        | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 36        | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 34        | 0.49%   |
| Intel WiFi Link 5100                                                   | 31        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1310      | 38.9%   |
| Realtek Semiconductor                 | 634       | 18.82%  |
| Qualcomm Atheros                      | 571       | 16.95%  |
| Broadcom                              | 296       | 8.79%   |
| Ralink Technology                     | 87        | 2.58%   |
| Broadcom Limited                      | 79        | 2.35%   |
| TP-Link                               | 77        | 2.29%   |
| Ralink                                | 69        | 2.05%   |
| MediaTek                              | 60        | 1.78%   |
| NetGear                               | 25        | 0.74%   |
| Marvell Technology Group              | 22        | 0.65%   |
| Qualcomm Atheros Communications       | 17        | 0.5%    |
| Sierra Wireless                       | 16        | 0.48%   |
| Dell                                  | 14        | 0.42%   |
| Microsoft                             | 13        | 0.39%   |
| D-Link                                | 13        | 0.39%   |
| D-Link System                         | 11        | 0.33%   |
| Edimax Technology                     | 10        | 0.3%    |
| ASUSTek Computer                      | 8         | 0.24%   |
| Linksys                               | 6         | 0.18%   |
| Belkin Components                     | 5         | 0.15%   |
| ZyDAS                                 | 3         | 0.09%   |
| ZyXEL Communications                  | 2         | 0.06%   |
| TRENDnet                              | 2         | 0.06%   |
| Hewlett-Packard                       | 2         | 0.06%   |
| Gemtek                                | 2         | 0.06%   |
| Fibocom                               | 2         | 0.06%   |
| AVM                                   | 2         | 0.06%   |
| Xiaomi                                | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Qualcomm                              | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Ovislink                              | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |
| Ericsson Business Mobile Networks     | 1         | 0.03%   |
| Askey Computer                        | 1         | 0.03%   |
| ADMtek                                | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 119       | 3.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 117       | 3.44%   |
| Intel Wireless 7265                                            | 113       | 3.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 102       | 3%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 99        | 2.91%   |
| Intel Wireless 7260                                            | 94        | 2.76%   |
| Intel Wireless 8265 / 8275                                     | 92        | 2.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 83        | 2.44%   |
| Intel Wi-Fi 6 AX201                                            | 83        | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 80        | 2.35%   |
| Intel Wireless 3165                                            | 64        | 1.88%   |
| Intel Wireless 8260                                            | 63        | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                  | 61        | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 59        | 1.73%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 56        | 1.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 55        | 1.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 49        | 1.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 48        | 1.41%   |
| Realtek 802.11ac NIC                                           | 48        | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 47        | 1.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 41        | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 41        | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 39        | 1.15%   |
| Ralink MT7601U Wireless Adapter                                | 38        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 38        | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 37        | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 36        | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 34        | 1%      |
| Intel WiFi Link 5100                                           | 31        | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 28        | 0.82%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 28        | 0.82%   |
| Intel Centrino Ultimate-N 6300                                 | 28        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 27        | 0.79%   |
| Intel Wireless 3160                                            | 26        | 0.76%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 24        | 0.71%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 24        | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 24        | 0.71%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 24        | 0.71%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 23        | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 22        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1831      | 52.92%  |
| Intel                             | 850       | 24.57%  |
| Qualcomm Atheros                  | 203       | 5.87%   |
| Broadcom                          | 184       | 5.32%   |
| Marvell Technology Group          | 61        | 1.76%   |
| Nvidia                            | 60        | 1.73%   |
| Broadcom Limited                  | 44        | 1.27%   |
| Samsung Electronics               | 39        | 1.13%   |
| ASIX Electronics                  | 32        | 0.92%   |
| DisplayLink                       | 21        | 0.61%   |
| Xiaomi                            | 18        | 0.52%   |
| JMicron Technology                | 13        | 0.38%   |
| Huawei Technologies               | 13        | 0.38%   |
| TP-Link                           | 11        | 0.32%   |
| OPPO Electronics                  | 10        | 0.29%   |
| MediaTek                          | 9         | 0.26%   |
| Qualcomm                          | 6         | 0.17%   |
| Aquantia                          | 6         | 0.17%   |
| Motorola PCS                      | 5         | 0.14%   |
| Google                            | 5         | 0.14%   |
| VIA Technologies                  | 4         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.09%   |
| Hewlett-Packard                   | 3         | 0.09%   |
| Sundance Technology Inc / IC Plus | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.06%   |
| Microsoft                         | 2         | 0.06%   |
| Lenovo                            | 2         | 0.06%   |
| ICS Advent                        | 2         | 0.06%   |
| HMD Global                        | 2         | 0.06%   |
| D-Link System                     | 2         | 0.06%   |
| ASUSTek Computer                  | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| T & A Mobile Phones               | 1         | 0.03%   |
| Sun Microsystems                  | 1         | 0.03%   |
| Research In Motion                | 1         | 0.03%   |
| Novatel Wireless                  | 1         | 0.03%   |
| Motorola BCS                      | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| LG Electronics                    | 1         | 0.03%   |
| HTC (High Tech Computer)          | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1325      | 37.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 314       | 8.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 175       | 4.99%   |
| Realtek RTL8125 2.5GbE Controller                                      | 83        | 2.37%   |
| Intel Ethernet Connection I217-LM                                      | 82        | 2.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 65        | 1.85%   |
| Intel I211 Gigabit Network Connection                                  | 60        | 1.71%   |
| Intel Ethernet Controller I225-V                                       | 43        | 1.23%   |
| Intel Ethernet Connection (2) I219-V                                   | 43        | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 39        | 1.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 36        | 1.03%   |
| Intel Ethernet Connection I219-LM                                      | 28        | 0.8%    |
| Intel Ethernet Connection I217-V                                       | 28        | 0.8%    |
| Intel Ethernet Connection I218-LM                                      | 27        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                          | 27        | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 26        | 0.74%   |
| Nvidia MCP79 Ethernet                                                  | 26        | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 25        | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                                  | 23        | 0.66%   |
| Intel 82577LM Gigabit Network Connection                               | 23        | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 22        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 22        | 0.63%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 21        | 0.6%    |
| Nvidia MCP61 Ethernet                                                  | 19        | 0.54%   |
| Intel 82579V Gigabit Network Connection                                | 19        | 0.54%   |
| Intel Ethernet Connection I219-V                                       | 18        | 0.51%   |
| Intel 82567LM Gigabit Network Connection                               | 18        | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 17        | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 17        | 0.48%   |
| Intel Ethernet Connection (7) I219-V                                   | 17        | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 17        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 16        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 16        | 0.46%   |
| Intel Ethernet Connection (4) I219-V                                   | 16        | 0.46%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 16        | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 16        | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 15        | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 15        | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                                  | 14        | 0.4%    |
| Intel Ethernet Connection (2) I218-V                                   | 14        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3277      | 50.58%  |
| WiFi     | 3139      | 48.45%  |
| Modem    | 50        | 0.77%   |
| Unknown  | 13        | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2459      | 60.21%  |
| Ethernet | 1620      | 39.67%  |
| Unknown  | 3         | 0.07%   |
| Modem    | 2         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2127      | 53.92%  |
| 1     | 1612      | 40.86%  |
| 0     | 130       | 3.3%    |
| 3     | 69        | 1.75%   |
| 5     | 3         | 0.08%   |
| 4     | 3         | 0.08%   |
| 7     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2712      | 67.88%  |
| Yes  | 1283      | 32.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1009      | 42.22%  |
| Realtek Semiconductor           | 289       | 12.09%  |
| Qualcomm Atheros Communications | 209       | 8.74%   |
| Broadcom                        | 133       | 5.56%   |
| Apple                           | 132       | 5.52%   |
| Cambridge Silicon Radio         | 125       | 5.23%   |
| IMC Networks                    | 101       | 4.23%   |
| Foxconn / Hon Hai               | 63        | 2.64%   |
| Lite-On Technology              | 60        | 2.51%   |
| Dell                            | 43        | 1.8%    |
| ASUSTek Computer                | 35        | 1.46%   |
| Hewlett-Packard                 | 34        | 1.42%   |
| Toshiba                         | 31        | 1.3%    |
| Marvell Semiconductor           | 21        | 0.88%   |
| Ralink                          | 18        | 0.75%   |
| MediaTek                        | 16        | 0.67%   |
| Realtek                         | 12        | 0.5%    |
| TP-Link                         | 8         | 0.33%   |
| Foxconn International           | 7         | 0.29%   |
| Alps Electric                   | 7         | 0.29%   |
| Integrated System Solution      | 6         | 0.25%   |
| Dynex                           | 5         | 0.21%   |
| Unknown                         | 5         | 0.21%   |
| Belkin Components               | 4         | 0.17%   |
| Askey Computer                  | 3         | 0.13%   |
| Actions                         | 3         | 0.13%   |
| Ralink Technology               | 2         | 0.08%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| National Semiconductor          | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Conwise Technology              | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 429       | 17.93%  |
| Realtek Bluetooth Radio                             | 213       | 8.9%    |
| Intel AX201 Bluetooth                               | 152       | 6.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 127       | 5.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 125       | 5.22%   |
| Intel AX200 Bluetooth                               | 104       | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                  | 90        | 3.76%   |
| Apple Bluetooth Host Controller                     | 60        | 2.51%   |
| Realtek  Bluetooth 4.2 Adapter                      | 57        | 2.38%   |
| Intel AX210 Bluetooth                               | 52        | 2.17%   |
| Intel Bluetooth Device                              | 41        | 1.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 39        | 1.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 37        | 1.55%   |
| IMC Networks Bluetooth Device                       | 35        | 1.46%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 33        | 1.38%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 31        | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 29        | 1.21%   |
| IMC Networks Bluetooth Radio                        | 29        | 1.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.13%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 26        | 1.09%   |
| Apple Bluetooth USB Host Controller                 | 24        | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 23        | 0.96%   |
| Marvell Bluetooth and Wireless LAN Composite        | 20        | 0.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 20        | 0.84%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 0.84%   |
| IMC Networks Wireless_Device                        | 20        | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.84%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 19        | 0.79%   |
| Ralink RT3290 Bluetooth                             | 18        | 0.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 18        | 0.75%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 18        | 0.75%   |
| MediaTek Wireless_Device                            | 15        | 0.63%   |
| Dell DW375 Bluetooth Module                         | 15        | 0.63%   |
| Apple Bluetooth HCI                                 | 15        | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 14        | 0.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 0.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 13        | 0.54%   |
| Realtek Bluetooth Radio                             | 12        | 0.5%    |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.5%    |
| Lite-On Bluetooth Device                            | 11        | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2907      | 55.27%  |
| AMD                                          | 1087      | 20.67%  |
| Nvidia                                       | 839       | 15.95%  |
| C-Media Electronics                          | 64        | 1.22%   |
| Creative Labs                                | 25        | 0.48%   |
| JMTek                                        | 22        | 0.42%   |
| Logitech                                     | 21        | 0.4%    |
| Generalplus Technology                       | 18        | 0.34%   |
| Texas Instruments                            | 17        | 0.32%   |
| Kingston Technology                          | 17        | 0.32%   |
| ASUSTek Computer                             | 17        | 0.32%   |
| Realtek Semiconductor                        | 13        | 0.25%   |
| Plantronics                                  | 11        | 0.21%   |
| VIA Technologies                             | 10        | 0.19%   |
| Razer USA                                    | 10        | 0.19%   |
| GN Netcom                                    | 10        | 0.19%   |
| Creative Technology                          | 10        | 0.19%   |
| KTMicro                                      | 9         | 0.17%   |
| Tenx Technology                              | 7         | 0.13%   |
| SteelSeries ApS                              | 7         | 0.13%   |
| Micro Star International                     | 6         | 0.11%   |
| Lenovo                                       | 6         | 0.11%   |
| Focusrite-Novation                           | 6         | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.1%    |
| Corsair                                      | 5         | 0.1%    |
| PreSonus Audio Electronics                   | 4         | 0.08%   |
| BR23                                         | 4         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.06%   |
| Sennheiser Communications                    | 3         | 0.06%   |
| RODE Microphones                             | 3         | 0.06%   |
| BEHRINGER International                      | 3         | 0.06%   |
| Astro Gaming                                 | 3         | 0.06%   |
| Asahi Kasei Microsystems                     | 3         | 0.06%   |
| Apple                                        | 3         | 0.06%   |
| AKAI Professional M.I.                       | 3         | 0.06%   |
| Yamaha                                       | 2         | 0.04%   |
| XMOS                                         | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.04%   |
| Sony                                         | 2         | 0.04%   |
| SAVITECH                                     | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 314       | 5.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 304       | 4.86%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 288       | 4.61%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 266       | 4.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 230       | 3.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 164       | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 159       | 2.54%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 148       | 2.37%   |
| AMD FCH Azalia Controller                                                                         | 147       | 2.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 127       | 2.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 126       | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 120       | 1.92%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 118       | 1.89%   |
| Intel 8 Series HD Audio Controller                                                                | 117       | 1.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 113       | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 113       | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 94        | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 92        | 1.47%   |
| Intel Broadwell-U Audio Controller                                                                | 91        | 1.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 88        | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 88        | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 85        | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 85        | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 71        | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 69        | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 67        | 1.07%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 65        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 63        | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 63        | 1.01%   |
| Intel 200 Series PCH HD Audio                                                                     | 57        | 0.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 56        | 0.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 53        | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 49        | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 47        | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 47        | 0.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 47        | 0.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 45        | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 44        | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 43        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 43        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 214       | 24.21%  |
| SK hynix               | 162       | 18.33%  |
| Micron Technology      | 95        | 10.75%  |
| Unknown                | 80        | 9.05%   |
| Kingston               | 72        | 8.14%   |
| Crucial                | 47        | 5.32%   |
| Unknown (ABCD)         | 26        | 2.94%   |
| Corsair                | 26        | 2.94%   |
| G.Skill                | 25        | 2.83%   |
| A-DATA Technology      | 17        | 1.92%   |
| Team                   | 14        | 1.58%   |
| Elpida                 | 14        | 1.58%   |
| Ramaxel Technology     | 12        | 1.36%   |
| Unknown                | 9         | 1.02%   |
| Nanya Technology       | 8         | 0.9%    |
| Smart                  | 7         | 0.79%   |
| Patriot                | 5         | 0.57%   |
| Timetec                | 4         | 0.45%   |
| Transcend              | 3         | 0.34%   |
| Avant                  | 3         | 0.34%   |
| Wilk                   | 2         | 0.23%   |
| Unifosa                | 2         | 0.23%   |
| Teikon                 | 2         | 0.23%   |
| Qimonda                | 2         | 0.23%   |
| ff                     | 2         | 0.23%   |
| fef5                   | 2         | 0.23%   |
| Apacer                 | 2         | 0.23%   |
| 4ea5                   | 2         | 0.23%   |
| Unknown (08B5)         | 1         | 0.11%   |
| Unknown (07F7)         | 1         | 0.11%   |
| Unknown (000080B30080) | 1         | 0.11%   |
| SUPER KINGSTEK         | 1         | 0.11%   |
| Strontium              | 1         | 0.11%   |
| Smart Brazil           | 1         | 0.11%   |
| Silicon Power          | 1         | 0.11%   |
| SHARETRONIC            | 1         | 0.11%   |
| PUSKILL                | 1         | 0.11%   |
| ProMos/Mosel Vitelic   | 1         | 0.11%   |
| pqi                    | 1         | 0.11%   |
| PNY                    | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 22        | 2.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 11        | 1.17%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 10        | 1.07%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 10        | 1.07%   |
| Unknown                                                             | 9         | 0.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 8         | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 8         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 7         | 0.75%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 7         | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 0.75%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 7         | 0.75%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                        | 6         | 0.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 0.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 6         | 0.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 6         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 6         | 0.64%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 5         | 0.53%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s              | 5         | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.53%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 5         | 0.53%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 5         | 0.53%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 5         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 4         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 4         | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 4         | 0.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 4         | 0.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 4         | 0.43%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 4         | 0.43%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 4         | 0.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 4         | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 0.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.43%   |
| Samsung RAM M471A1G44BB0-CWE 8192MB Row Of Chips DDR4 3200MT/s      | 4         | 0.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 4         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 3         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 323       | 42.61%  |
| DDR3    | 269       | 35.49%  |
| LPDDR4  | 56        | 7.39%   |
| LPDDR3  | 30        | 3.96%   |
| DDR2    | 30        | 3.96%   |
| SDRAM   | 18        | 2.37%   |
| Unknown | 17        | 2.24%   |
| DDR5    | 7         | 0.92%   |
| LPDDR5  | 4         | 0.53%   |
| DDR     | 4         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 473       | 62.32%  |
| DIMM         | 192       | 25.3%   |
| Row Of Chips | 76        | 10.01%  |
| Chip         | 9         | 1.19%   |
| Unknown      | 8         | 1.05%   |
| FB-DIMM      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 324       | 38.53%  |
| 4096  | 252       | 29.96%  |
| 2048  | 119       | 14.15%  |
| 16384 | 93        | 11.06%  |
| 32768 | 26        | 3.09%   |
| 1024  | 25        | 2.97%   |
| 512   | 2         | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 171       | 20.8%   |
| 3200    | 136       | 16.55%  |
| 2667    | 109       | 13.26%  |
| 2400    | 73        | 8.88%   |
| 1333    | 53        | 6.45%   |
| 2133    | 32        | 3.89%   |
| 1334    | 26        | 3.16%   |
| 1867    | 19        | 2.31%   |
| 4267    | 17        | 2.07%   |
| 3600    | 16        | 1.95%   |
| Unknown | 15        | 1.82%   |
| 800     | 14        | 1.7%    |
| 667     | 14        | 1.7%    |
| 1066    | 12        | 1.46%   |
| 3266    | 10        | 1.22%   |
| 4800    | 7         | 0.85%   |
| 3733    | 7         | 0.85%   |
| 2048    | 7         | 0.85%   |
| 1866    | 7         | 0.85%   |
| 3000    | 6         | 0.73%   |
| 1800    | 6         | 0.73%   |
| 1067    | 6         | 0.73%   |
| 6400    | 5         | 0.61%   |
| 8400    | 4         | 0.49%   |
| 3800    | 4         | 0.49%   |
| 975     | 4         | 0.49%   |
| 4266    | 3         | 0.36%   |
| 4199    | 3         | 0.36%   |
| 2666    | 3         | 0.36%   |
| 3866    | 2         | 0.24%   |
| 3666    | 2         | 0.24%   |
| 3500    | 2         | 0.24%   |
| 3466    | 2         | 0.24%   |
| 3400    | 2         | 0.24%   |
| 2933    | 2         | 0.24%   |
| 400     | 2         | 0.24%   |
| 6000    | 1         | 0.12%   |
| 5600    | 1         | 0.12%   |
| 5354    | 1         | 0.12%   |
| 5200    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 34        | 33.01%  |
| Canon                 | 19        | 18.45%  |
| Brother Industries    | 18        | 17.48%  |
| Seiko Epson           | 14        | 13.59%  |
| Samsung Electronics   | 10        | 9.71%   |
| Lexmark International | 3         | 2.91%   |
| Zebra                 | 1         | 0.97%   |
| Ricoh                 | 1         | 0.97%   |
| QinHeng Electronics   | 1         | 0.97%   |
| Konica Minolta        | 1         | 0.97%   |
| GG IMAGE              | 1         | 0.97%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                     | 3         | 2.91%   |
| HP DeskJet 2700 series                       | 3         | 2.91%   |
| Samsung C460 Series                          | 2         | 1.94%   |
| HP OfficeJet 6950                            | 2         | 1.94%   |
| HP LaserJet Professional P1102w              | 2         | 1.94%   |
| HP ENVY Photo 6200 series                    | 2         | 1.94%   |
| HP ENVY 4520 series                          | 2         | 1.94%   |
| HP DeskJet 2130 series                       | 2         | 1.94%   |
| Canon TS3100 series                          | 2         | 1.94%   |
| Canon PIXMA MG3600 Series                    | 2         | 1.94%   |
| Canon LiDE 400                               | 2         | 1.94%   |
| Brother HL-2140 series                       | 2         | 1.94%   |
| Zebra ZP 450 Printer                         | 1         | 0.97%   |
| Seiko Epson XP-7100 Series                   | 1         | 0.97%   |
| Seiko Epson XP-235 Series                    | 1         | 0.97%   |
| Seiko Epson XP-200 Series                    | 1         | 0.97%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.97%   |
| Seiko Epson L805 Series                      | 1         | 0.97%   |
| Seiko Epson L6270 Series                     | 1         | 0.97%   |
| Seiko Epson L355 Series                      | 1         | 0.97%   |
| Seiko Epson L3250 Series                     | 1         | 0.97%   |
| Seiko Epson L3150 Series                     | 1         | 0.97%   |
| Seiko Epson ET-2820 Series                   | 1         | 0.97%   |
| Seiko Epson AcuLaser C1700                   | 1         | 0.97%   |
| Samsung SCX-483x 5x3x Series                 | 1         | 0.97%   |
| Samsung SCX-4623 Series                      | 1         | 0.97%   |
| Samsung SCX-4200 series                      | 1         | 0.97%   |
| Samsung SCX-3400 Series                      | 1         | 0.97%   |
| Samsung ML-2950 Series                       | 1         | 0.97%   |
| Samsung ML-216x Series Laser Printer         | 1         | 0.97%   |
| Samsung M2070 Series                         | 1         | 0.97%   |
| Samsung M2020 Series                         | 1         | 0.97%   |
| Ricoh SP 112SU                               | 1         | 0.97%   |
| QinHeng CH340S                               | 1         | 0.97%   |
| Lexmark International MX310dn                | 1         | 0.97%   |
| Lexmark International Laser Printer E232     | 1         | 0.97%   |
| Lexmark International 2400 series            | 1         | 0.97%   |
| Konica Minolta PagePro 1380MF                | 1         | 0.97%   |
| HP Smart Tank 510 series                     | 1         | 0.97%   |
| HP PSC 1100 series                           | 1         | 0.97%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 12        | 63.16%  |
| Seiko Epson     | 4         | 21.05%  |
| Hewlett-Packard | 3         | 15.79%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 3         | 15%     |
| Canon CanoScan LiDE 90                      | 2         | 10%     |
| Canon CanoScan LiDE 220                     | 2         | 10%     |
| Seiko Epson Scanner                         | 1         | 5%      |
| HP ScanJet 2400c                            | 1         | 5%      |
| HP Scanjet 200                              | 1         | 5%      |
| HP PSC 1200                                 | 1         | 5%      |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 5%      |
| Canon CanoScan LiDE 60                      | 1         | 5%      |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 1         | 5%      |
| Canon CanoScan LIDE 25                      | 1         | 5%      |
| Canon CanoScan LiDE 110                     | 1         | 5%      |
| Canon CanoScan LiDE 100                     | 1         | 5%      |
| Canon CanoScan D660U                        | 1         | 5%      |
| Canon CanoScan 8800F                        | 1         | 5%      |
| Canon CanoScan 5600F                        | 1         | 5%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 477       | 20.68%  |
| Microdia                               | 206       | 8.93%   |
| Realtek Semiconductor                  | 192       | 8.32%   |
| IMC Networks                           | 167       | 7.24%   |
| Sunplus Innovation Technology          | 131       | 5.68%   |
| Apple                                  | 116       | 5.03%   |
| Bison Electronics                      | 109       | 4.72%   |
| Cheng Uei Precision Industry (Foxlink) | 101       | 4.38%   |
| Quanta                                 | 96        | 4.16%   |
| Logitech                               | 89        | 3.86%   |
| Suyin                                  | 80        | 3.47%   |
| Syntek                                 | 65        | 2.82%   |
| Lite-On Technology                     | 47        | 2.04%   |
| Acer                                   | 40        | 1.73%   |
| Alcor Micro                            | 37        | 1.6%    |
| Silicon Motion                         | 35        | 1.52%   |
| Luxvisions Innotech Limited            | 26        | 1.13%   |
| Ricoh                                  | 22        | 0.95%   |
| Microsoft                              | 22        | 0.95%   |
| Samsung Electronics                    | 21        | 0.91%   |
| Sonix Technology                       | 17        | 0.74%   |
| Z-Star Microelectronics                | 14        | 0.61%   |
| USB Camera                             | 14        | 0.61%   |
| Primax Electronics                     | 12        | 0.52%   |
| Generalplus Technology                 | 12        | 0.52%   |
| ARC International                      | 10        | 0.43%   |
| SunplusIT                              | 9         | 0.39%   |
| Lenovo                                 | 9         | 0.39%   |
| GEMBIRD                                | 9         | 0.39%   |
| ALi                                    | 8         | 0.35%   |
| Importek                               | 6         | 0.26%   |
| Y Media                                | 5         | 0.22%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.22%   |
| Jieli Technology                       | 5         | 0.22%   |
| Genesys Logic                          | 5         | 0.22%   |
| Sunplus Technology                     | 4         | 0.17%   |
| Razer USA                              | 4         | 0.17%   |
| OmniVision Technologies                | 4         | 0.17%   |
| Intel                                  | 4         | 0.17%   |
| Creative Technology                    | 4         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 82        | 3.53%   |
| Microdia Integrated_Webcam_HD                       | 48        | 2.07%   |
| Realtek Integrated_Webcam_HD                        | 45        | 1.94%   |
| Syntek Integrated Camera                            | 42        | 1.81%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 42        | 1.81%   |
| Apple FaceTime HD Camera (Built-in)                 | 41        | 1.77%   |
| Chicony HD WebCam                                   | 40        | 1.72%   |
| IMC Networks Integrated Camera                      | 34        | 1.46%   |
| Bison Integrated Camera                             | 34        | 1.46%   |
| Realtek USB Camera                                  | 32        | 1.38%   |
| Apple Built-in iSight                               | 30        | 1.29%   |
| Chicony HP Truevision HD                            | 29        | 1.25%   |
| Microdia Integrated Webcam                          | 26        | 1.12%   |
| Sunplus Integrated_Webcam_HD                        | 24        | 1.03%   |
| Chicony TOSHIBA Web Camera - HD                     | 24        | 1.03%   |
| Bison Lenovo EasyCamera                             | 24        | 1.03%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 24        | 1.03%   |
| Samsung Galaxy series, misc. (MTP mode)             | 21        | 0.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 21        | 0.9%    |
| Logitech Webcam C270                                | 20        | 0.86%   |
| Microdia Webcam Vitade AF                           | 18        | 0.78%   |
| Alcor Micro USB 2.0 Camera                          | 18        | 0.78%   |
| Lite-On HP HD Camera                                | 17        | 0.73%   |
| Chicony EasyCamera                                  | 17        | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 17        | 0.73%   |
| Sunplus HD WebCam                                   | 16        | 0.69%   |
| Microdia USB 2.0 Camera                             | 16        | 0.69%   |
| Realtek Integrated Webcam                           | 15        | 0.65%   |
| Realtek HP Truevision HD                            | 15        | 0.65%   |
| Chicony USB2.0 VGA UVC WebCam                       | 15        | 0.65%   |
| Chicony HP TrueVision HD Camera                     | 15        | 0.65%   |
| Apple FaceTime HD Camera                            | 15        | 0.65%   |
| USB Camera USB Camera                               | 14        | 0.6%    |
| Quanta HP Wide Vision HD Camera                     | 14        | 0.6%    |
| Quanta HD User Facing                               | 14        | 0.6%    |
| Logitech HD Pro Webcam C920                         | 14        | 0.6%    |
| Chicony VGA WebCam                                  | 14        | 0.6%    |
| Chicony Lenovo EasyCamera                           | 14        | 0.6%    |
| Chicony HP HD Camera                                | 14        | 0.6%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 13        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 152       | 40.64%  |
| Synaptics                          | 62        | 16.58%  |
| Shenzhen Goodix Technology         | 50        | 13.37%  |
| AuthenTec                          | 35        | 9.36%   |
| Upek                               | 24        | 6.42%   |
| Elan Microelectronics              | 22        | 5.88%   |
| LighTuning Technology              | 13        | 3.48%   |
| STMicroelectronics                 | 7         | 1.87%   |
| Samsung Electronics                | 3         | 0.8%    |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.8%    |
| Next Biometrics                    | 1         | 0.27%   |
| HOLTEK                             | 1         | 0.27%   |
| Focal-systems.Corp                 | 1         | 0.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 8.02%   |
| Shenzhen Goodix  Fingerprint Device                                        | 29        | 7.75%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                                         | 18        | 4.81%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 16        | 4.28%   |
| Validity Sensors VFS491                                                    | 15        | 4.01%   |
| Elan ELAN:ARM-M4                                                           | 15        | 4.01%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 3.48%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 3.21%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 3.21%   |
| AuthenTec AES2810                                                          | 11        | 2.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.67%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 2.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 2.67%   |
| Synaptics UWP WBDI                                                         | 9         | 2.41%   |
| Synaptics  WBDI                                                            | 9         | 2.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 2.41%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 2.41%   |
| Synaptics WBDI                                                             | 8         | 2.14%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 1.87%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.87%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.87%   |
| Elan ELAN:Fingerprint                                                      | 7         | 1.87%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 1.6%    |
| LighTuning Fingerprint Sensor                                              | 5         | 1.34%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.34%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.34%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.07%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 1.07%   |
| AuthenTec AES1600                                                          | 4         | 1.07%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.8%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.8%    |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.8%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.8%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.53%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.53%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.53%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.53%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 81        | 51.92%  |
| Alcor Micro                       | 26        | 16.67%  |
| O2 Micro                          | 16        | 10.26%  |
| Lenovo                            | 7         | 4.49%   |
| Upek                              | 6         | 3.85%   |
| VASCO Data Security International | 3         | 1.92%   |
| SCM Microsystems                  | 3         | 1.92%   |
| Realtek Semiconductor             | 3         | 1.92%   |
| Yubico.com                        | 2         | 1.28%   |
| Fujitsu Siemens Computers         | 2         | 1.28%   |
| Advanced Card Systems             | 2         | 1.28%   |
| Reiner SCT Kartensysteme          | 1         | 0.64%   |
| OmniKey                           | 1         | 0.64%   |
| Jing-Mold Enterprise              | 1         | 0.64%   |
| Gemalto (was Gemplus)             | 1         | 0.64%   |
| Chicony Electronics               | 1         | 0.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 19.23%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 16.67%  |
| Broadcom 5880                                                                | 23        | 14.74%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 12.82%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 9.62%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 4.49%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 3.85%   |
| Broadcom 58200                                                               | 6         | 3.85%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.92%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.28%   |
| VASCO Data Security International DIGIPASS 870                               | 2         | 1.28%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.28%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 2         | 1.28%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.28%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.64%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.64%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.64%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.64%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.64%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 0.64%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.64%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.64%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.64%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2826      | 70.61%  |
| 1     | 948       | 23.69%  |
| 2     | 203       | 5.07%   |
| 3     | 22        | 0.55%   |
| 4     | 2         | 0.05%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 368       | 26.61%  |
| Graphics card            | 296       | 21.4%   |
| Net/wireless             | 249       | 18%     |
| Multimedia controller    | 160       | 11.57%  |
| Chipcard                 | 144       | 10.41%  |
| Communication controller | 29        | 2.1%    |
| Storage                  | 28        | 2.02%   |
| Bluetooth                | 28        | 2.02%   |
| Sound                    | 13        | 0.94%   |
| Unassigned class         | 11        | 0.8%    |
| Camera                   | 10        | 0.72%   |
| Net/ethernet             | 8         | 0.58%   |
| Storage/raid             | 7         | 0.51%   |
| Modem                    | 7         | 0.51%   |
| Network                  | 6         | 0.43%   |
| Dvb card                 | 5         | 0.36%   |
| Card reader              | 5         | 0.36%   |
| Storage/ide              | 4         | 0.29%   |
| Storage/nvme             | 2         | 0.14%   |
| Flash memory             | 2         | 0.14%   |
| Unclassified device      | 1         | 0.07%   |

