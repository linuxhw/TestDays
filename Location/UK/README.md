Linux in UK - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UK/Desktop/README.md) and [notebooks](/Location/UK/Notebook/README.md).

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

Total: 11046

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [dedc98e84e](https://linux-hardware.org/?probe=dedc98e84e) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [4cb72d56f7](https://linux-hardware.org/?probe=4cb72d56f7) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c23450b0df](https://linux-hardware.org/?probe=c23450b0df) | Jun 10, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [873975925d](https://linux-hardware.org/?probe=873975925d) | Jun 10, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [4b6aa9a912](https://linux-hardware.org/?probe=4b6aa9a912) | Jun 10, 2023 |
| HP            | ProBook 4510s               | Notebook    | [43a29ea83e](https://linux-hardware.org/?probe=43a29ea83e) | Jun 09, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [88020aee75](https://linux-hardware.org/?probe=88020aee75) | Jun 09, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [adcb3b193a](https://linux-hardware.org/?probe=adcb3b193a) | Jun 09, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [50c36acc0d](https://linux-hardware.org/?probe=50c36acc0d) | Jun 09, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [e68e693394](https://linux-hardware.org/?probe=e68e693394) | Jun 08, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [28a5b69096](https://linux-hardware.org/?probe=28a5b69096) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | Notebook    | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| AZW           | Green G4 10                 | Desktop     | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [697f2b18e8](https://linux-hardware.org/?probe=697f2b18e8) | Jun 08, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [4614addc21](https://linux-hardware.org/?probe=4614addc21) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [340054cdd5](https://linux-hardware.org/?probe=340054cdd5) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| HP            | 8350                        | Desktop     | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [73fa9d854f](https://linux-hardware.org/?probe=73fa9d854f) | Jun 07, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [cb8797fce5](https://linux-hardware.org/?probe=cb8797fce5) | Jun 07, 2023 |
| Dell          | XPS 9320                    | Notebook    | [ff5fc17acc](https://linux-hardware.org/?probe=ff5fc17acc) | Jun 07, 2023 |
| ECS           | GF8100VM-M5                 | Desktop     | [6aa065057f](https://linux-hardware.org/?probe=6aa065057f) | Jun 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [27771c5ea8](https://linux-hardware.org/?probe=27771c5ea8) | Jun 07, 2023 |
| Lenovo        | ThinkPad X61 7674GS3        | Notebook    | [629a290a98](https://linux-hardware.org/?probe=629a290a98) | Jun 07, 2023 |
| Foxconn       | H55M-S                      | Desktop     | [83b86844c0](https://linux-hardware.org/?probe=83b86844c0) | Jun 06, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [788ddd35a8](https://linux-hardware.org/?probe=788ddd35a8) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e4335c33f6](https://linux-hardware.org/?probe=e4335c33f6) | Jun 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [99a7a5bd6e](https://linux-hardware.org/?probe=99a7a5bd6e) | Jun 06, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [76a8e35b72](https://linux-hardware.org/?probe=76a8e35b72) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [413ef09459](https://linux-hardware.org/?probe=413ef09459) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [78459738e9](https://linux-hardware.org/?probe=78459738e9) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [b969b91080](https://linux-hardware.org/?probe=b969b91080) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [8c6a275a93](https://linux-hardware.org/?probe=8c6a275a93) | Jun 05, 2023 |
| Dell          | Latitude E5250              | Notebook    | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [e3f89d1faa](https://linux-hardware.org/?probe=e3f89d1faa) | Jun 04, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | Desktop     | [a6804d8ca1](https://linux-hardware.org/?probe=a6804d8ca1) | Jun 04, 2023 |
| MSI           | Katana GF66 11UG            | Notebook    | [d50f02e996](https://linux-hardware.org/?probe=d50f02e996) | Jun 04, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [5716ed966d](https://linux-hardware.org/?probe=5716ed966d) | Jun 04, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [a3d127e3ba](https://linux-hardware.org/?probe=a3d127e3ba) | Jun 04, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [e541266510](https://linux-hardware.org/?probe=e541266510) | Jun 04, 2023 |
| Dell          | Latitude E5520              | Notebook    | [7e2d1fdd22](https://linux-hardware.org/?probe=7e2d1fdd22) | Jun 04, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [fc6e3f084f](https://linux-hardware.org/?probe=fc6e3f084f) | Jun 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [77d585fa03](https://linux-hardware.org/?probe=77d585fa03) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [f39742476c](https://linux-hardware.org/?probe=f39742476c) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [efa49bf468](https://linux-hardware.org/?probe=efa49bf468) | Jun 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9085f3c8f7](https://linux-hardware.org/?probe=9085f3c8f7) | Jun 04, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [a9c6f5e0e6](https://linux-hardware.org/?probe=a9c6f5e0e6) | Jun 04, 2023 |
| HP            | Notebook                    | Notebook    | [45553d6493](https://linux-hardware.org/?probe=45553d6493) | Jun 04, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [406fc17c32](https://linux-hardware.org/?probe=406fc17c32) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [06752ca793](https://linux-hardware.org/?probe=06752ca793) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [dc8f67bb03](https://linux-hardware.org/?probe=dc8f67bb03) | Jun 03, 2023 |
| Foxconn       | A74ML-K                     | Desktop     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [7bdff81d7d](https://linux-hardware.org/?probe=7bdff81d7d) | Jun 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [e7409e91d9](https://linux-hardware.org/?probe=e7409e91d9) | Jun 03, 2023 |
| Sony          | SVF1521A1EW                 | Notebook    | [4e3fe0308e](https://linux-hardware.org/?probe=4e3fe0308e) | Jun 02, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [2604bac5a5](https://linux-hardware.org/?probe=2604bac5a5) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1b82c0c3c8](https://linux-hardware.org/?probe=1b82c0c3c8) | Jun 02, 2023 |
| Dell          | 0NNNCT A01                  | Desktop     | [1a1e7426a3](https://linux-hardware.org/?probe=1a1e7426a3) | Jun 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9a91f8aedc](https://linux-hardware.org/?probe=9a91f8aedc) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| Intel         | AB2L .A003                  | Mini pc     | [25fb11cde7](https://linux-hardware.org/?probe=25fb11cde7) | Jun 01, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Lenovo        | ThinkPad X61 7674GS3        | Notebook    | [194299200c](https://linux-hardware.org/?probe=194299200c) | Jun 01, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [16c536cda1](https://linux-hardware.org/?probe=16c536cda1) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [1a6c37d8f7](https://linux-hardware.org/?probe=1a6c37d8f7) | Jun 01, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [a13bd80e8a](https://linux-hardware.org/?probe=a13bd80e8a) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | Notebook    | [f3dc10c852](https://linux-hardware.org/?probe=f3dc10c852) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | Notebook    | [1d128e6153](https://linux-hardware.org/?probe=1d128e6153) | Jun 01, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [e822eb4072](https://linux-hardware.org/?probe=e822eb4072) | Jun 01, 2023 |
| Lenovo        | 370B SDK0J40700 WIN 3258... | All in one  | [e98c5409ac](https://linux-hardware.org/?probe=e98c5409ac) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [01692ad602](https://linux-hardware.org/?probe=01692ad602) | May 31, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [6b3efa1ef7](https://linux-hardware.org/?probe=6b3efa1ef7) | May 31, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [5f63504f03](https://linux-hardware.org/?probe=5f63504f03) | May 31, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [417320253a](https://linux-hardware.org/?probe=417320253a) | May 31, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [ac6f421fef](https://linux-hardware.org/?probe=ac6f421fef) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [c76d767402](https://linux-hardware.org/?probe=c76d767402) | May 31, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [8092b65afc](https://linux-hardware.org/?probe=8092b65afc) | May 31, 2023 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [4ed64d3d45](https://linux-hardware.org/?probe=4ed64d3d45) | May 30, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [3c6e8b6acd](https://linux-hardware.org/?probe=3c6e8b6acd) | May 29, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1c87272ed8](https://linux-hardware.org/?probe=1c87272ed8) | May 29, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Fusion5       | FWIN232                     | Tablet      | [9b5781e140](https://linux-hardware.org/?probe=9b5781e140) | May 28, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [2bb14772ce](https://linux-hardware.org/?probe=2bb14772ce) | May 28, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [7ac306d4fa](https://linux-hardware.org/?probe=7ac306d4fa) | May 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [66bff91fdb](https://linux-hardware.org/?probe=66bff91fdb) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Dell          | Latitude D630               | Notebook    | [ead768adbd](https://linux-hardware.org/?probe=ead768adbd) | May 27, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [3ad8935a92](https://linux-hardware.org/?probe=3ad8935a92) | May 27, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [9ee2d1266b](https://linux-hardware.org/?probe=9ee2d1266b) | May 27, 2023 |
| ASRock        | H510M-HDV                   | Desktop     | [27ca3c6650](https://linux-hardware.org/?probe=27ca3c6650) | May 27, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [0577b02521](https://linux-hardware.org/?probe=0577b02521) | May 27, 2023 |
| ASRock        | H510M-HDV                   | Desktop     | [c6315a675c](https://linux-hardware.org/?probe=c6315a675c) | May 27, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [ce0ecf0cce](https://linux-hardware.org/?probe=ce0ecf0cce) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | Desktop     | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [ecf6ecb00d](https://linux-hardware.org/?probe=ecf6ecb00d) | May 26, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | Notebook    | [0696598319](https://linux-hardware.org/?probe=0696598319) | May 26, 2023 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [9b2b467879](https://linux-hardware.org/?probe=9b2b467879) | May 26, 2023 |
| HP            | 8437                        | Desktop     | [c1c9154683](https://linux-hardware.org/?probe=c1c9154683) | May 26, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [5037ec3f4a](https://linux-hardware.org/?probe=5037ec3f4a) | May 26, 2023 |
| HP            | ENVY Laptop 13-ah0503na     | Notebook    | [cdf2d7b4b4](https://linux-hardware.org/?probe=cdf2d7b4b4) | May 25, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [a88cd7c5a6](https://linux-hardware.org/?probe=a88cd7c5a6) | May 25, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [afda741dec](https://linux-hardware.org/?probe=afda741dec) | May 25, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [7389c979b6](https://linux-hardware.org/?probe=7389c979b6) | May 25, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [e55e554596](https://linux-hardware.org/?probe=e55e554596) | May 25, 2023 |
| Dell          | Latitude 5521               | Notebook    | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [4bbba2e730](https://linux-hardware.org/?probe=4bbba2e730) | May 25, 2023 |
| Dell          | Latitude 7390               | Notebook    | [999bb94a31](https://linux-hardware.org/?probe=999bb94a31) | May 24, 2023 |
| Lenovo        | ThinkPad T431s 20ACA01V0... | Notebook    | [253f7d5359](https://linux-hardware.org/?probe=253f7d5359) | May 24, 2023 |
| Dell EMC      | Edge Gateway 3200           | Mini pc     | [617aeb0068](https://linux-hardware.org/?probe=617aeb0068) | May 24, 2023 |
| Lenovo        | ThinkPad W530 24472BG       | Notebook    | [6431c2bb45](https://linux-hardware.org/?probe=6431c2bb45) | May 24, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [f20bf1430d](https://linux-hardware.org/?probe=f20bf1430d) | May 24, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [af5b849c20](https://linux-hardware.org/?probe=af5b849c20) | May 23, 2023 |
| Lenovo        | ThinkPad T470s 20HGS4RU0... | Notebook    | [ac8df81694](https://linux-hardware.org/?probe=ac8df81694) | May 23, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [2cf9c98869](https://linux-hardware.org/?probe=2cf9c98869) | May 23, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [4da667cc7e](https://linux-hardware.org/?probe=4da667cc7e) | May 23, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a3817d2576](https://linux-hardware.org/?probe=a3817d2576) | May 23, 2023 |
| HP            | Notebook                    | Notebook    | [6e7c128799](https://linux-hardware.org/?probe=6e7c128799) | May 23, 2023 |
| HP            | 21EF                        | Desktop     | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3d594ff1da](https://linux-hardware.org/?probe=3d594ff1da) | May 23, 2023 |
| Lenovo        | ThinkPad L440 20AS001CUK    | Notebook    | [8d253e2d7e](https://linux-hardware.org/?probe=8d253e2d7e) | May 22, 2023 |
| HP            | 21EF                        | Desktop     | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d5b2c1e7b5](https://linux-hardware.org/?probe=d5b2c1e7b5) | May 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [5e89fe1dc9](https://linux-hardware.org/?probe=5e89fe1dc9) | May 22, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [56fba05f01](https://linux-hardware.org/?probe=56fba05f01) | May 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [2b3ef0afc4](https://linux-hardware.org/?probe=2b3ef0afc4) | May 22, 2023 |
| AZW           | U59                         | Desktop     | [59edf1c8a6](https://linux-hardware.org/?probe=59edf1c8a6) | May 22, 2023 |
| AZW           | U59                         | Desktop     | [b365dbf63a](https://linux-hardware.org/?probe=b365dbf63a) | May 22, 2023 |
| SYWZ          | S200 Series                 | Desktop     | [6878838d6f](https://linux-hardware.org/?probe=6878838d6f) | May 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [c7f1f9d62a](https://linux-hardware.org/?probe=c7f1f9d62a) | May 22, 2023 |
| Microsoft     | Surface Book                | Tablet      | [01c76b5ed7](https://linux-hardware.org/?probe=01c76b5ed7) | May 21, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [bc39784c46](https://linux-hardware.org/?probe=bc39784c46) | May 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a6f95de398](https://linux-hardware.org/?probe=a6f95de398) | May 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [548626d011](https://linux-hardware.org/?probe=548626d011) | May 21, 2023 |
| Unknown       | V00                         | Mini pc     | [7b8747aad5](https://linux-hardware.org/?probe=7b8747aad5) | May 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [05f3c4f274](https://linux-hardware.org/?probe=05f3c4f274) | May 21, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [d404dc5e03](https://linux-hardware.org/?probe=d404dc5e03) | May 21, 2023 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [5a30bf445a](https://linux-hardware.org/?probe=5a30bf445a) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [d549fb62db](https://linux-hardware.org/?probe=d549fb62db) | May 20, 2023 |
| Samsung       | DeskTop System              | Desktop     | [0f49fcc9e8](https://linux-hardware.org/?probe=0f49fcc9e8) | May 20, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [d5213cca3c](https://linux-hardware.org/?probe=d5213cca3c) | May 20, 2023 |
| ASUSTek       | X705UDR                     | Notebook    | [e1f2bf110a](https://linux-hardware.org/?probe=e1f2bf110a) | May 20, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [c6ce2f365a](https://linux-hardware.org/?probe=c6ce2f365a) | May 20, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [f051e7f6da](https://linux-hardware.org/?probe=f051e7f6da) | May 20, 2023 |
| HP            | 1905                        | Desktop     | [1ce2caa771](https://linux-hardware.org/?probe=1ce2caa771) | May 19, 2023 |
| Dell          | Latitude 7280               | Notebook    | [9b98a88e3d](https://linux-hardware.org/?probe=9b98a88e3d) | May 19, 2023 |
| HP            | 1905                        | Desktop     | [de8cea1b10](https://linux-hardware.org/?probe=de8cea1b10) | May 19, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [d52cf51575](https://linux-hardware.org/?probe=d52cf51575) | May 19, 2023 |
| Eii           | WSA116                      | Notebook    | [cff66832fd](https://linux-hardware.org/?probe=cff66832fd) | May 19, 2023 |
| Lenovo        | ThinkPad X240 20AMA21D00    | Notebook    | [a692a56bc0](https://linux-hardware.org/?probe=a692a56bc0) | May 19, 2023 |
| Advent        | Roma                        | Notebook    | [f6ca4c331a](https://linux-hardware.org/?probe=f6ca4c331a) | May 19, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [a6755db2c4](https://linux-hardware.org/?probe=a6755db2c4) | May 19, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [3f5ffac86c](https://linux-hardware.org/?probe=3f5ffac86c) | May 19, 2023 |
| Unknown       | V00                         | Mini pc     | [3abd6900c9](https://linux-hardware.org/?probe=3abd6900c9) | May 19, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [c2f9737977](https://linux-hardware.org/?probe=c2f9737977) | May 19, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [ce94bc6589](https://linux-hardware.org/?probe=ce94bc6589) | May 18, 2023 |
| Entroware     | Kratos                      | Notebook    | [ecf875b8e5](https://linux-hardware.org/?probe=ecf875b8e5) | May 18, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [7c4f12c4ed](https://linux-hardware.org/?probe=7c4f12c4ed) | May 18, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [52ee676c29](https://linux-hardware.org/?probe=52ee676c29) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [3c8dcfcf15](https://linux-hardware.org/?probe=3c8dcfcf15) | May 18, 2023 |
| HP            | 3398                        | Desktop     | [a49cbc797b](https://linux-hardware.org/?probe=a49cbc797b) | May 18, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ba813a3367](https://linux-hardware.org/?probe=ba813a3367) | May 18, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [d23967583a](https://linux-hardware.org/?probe=d23967583a) | May 18, 2023 |
| Lenovo        | ThinkPad Yoga 460 20EM00... | Convertible | [83edbdf941](https://linux-hardware.org/?probe=83edbdf941) | May 17, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [d4884bd764](https://linux-hardware.org/?probe=d4884bd764) | May 17, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [c6d11a2f8e](https://linux-hardware.org/?probe=c6d11a2f8e) | May 17, 2023 |
| Google        | Samus                       | Notebook    | [d627862e56](https://linux-hardware.org/?probe=d627862e56) | May 16, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | Desktop     | [af5b595698](https://linux-hardware.org/?probe=af5b595698) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [546f6e95e9](https://linux-hardware.org/?probe=546f6e95e9) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [54fc8d0489](https://linux-hardware.org/?probe=54fc8d0489) | May 16, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [9ea7971a18](https://linux-hardware.org/?probe=9ea7971a18) | May 16, 2023 |
| eMachines     | E625                        | Notebook    | [8638b2b8c8](https://linux-hardware.org/?probe=8638b2b8c8) | May 15, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [4ea868b4d1](https://linux-hardware.org/?probe=4ea868b4d1) | May 15, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [1bf9f3a0df](https://linux-hardware.org/?probe=1bf9f3a0df) | May 15, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [83f139d228](https://linux-hardware.org/?probe=83f139d228) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4b1b35b4ec](https://linux-hardware.org/?probe=4b1b35b4ec) | May 15, 2023 |
| Dell          | Inspiron 5405               | Notebook    | [9d3ae56a5e](https://linux-hardware.org/?probe=9d3ae56a5e) | May 15, 2023 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [cd0a78ce39](https://linux-hardware.org/?probe=cd0a78ce39) | May 14, 2023 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | Notebook    | [8921a6d64e](https://linux-hardware.org/?probe=8921a6d64e) | May 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [6df9aa02d5](https://linux-hardware.org/?probe=6df9aa02d5) | May 14, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| AMI           | Intel                       | Desktop     | [569d80a4a0](https://linux-hardware.org/?probe=569d80a4a0) | May 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [162219b0fe](https://linux-hardware.org/?probe=162219b0fe) | May 14, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [88a88bec15](https://linux-hardware.org/?probe=88a88bec15) | May 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [f5fa402f37](https://linux-hardware.org/?probe=f5fa402f37) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [49a47c559e](https://linux-hardware.org/?probe=49a47c559e) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [91986cf051](https://linux-hardware.org/?probe=91986cf051) | May 14, 2023 |
| Gigabyte      | 970A-DS3                    | Desktop     | [97ef085eca](https://linux-hardware.org/?probe=97ef085eca) | May 14, 2023 |
| ASUSTek       | X510UQR                     | Notebook    | [2062004d5f](https://linux-hardware.org/?probe=2062004d5f) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [46e74189f2](https://linux-hardware.org/?probe=46e74189f2) | May 13, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [892b6d56c8](https://linux-hardware.org/?probe=892b6d56c8) | May 13, 2023 |
| Dell          | G7 7700                     | Notebook    | [6568ba5b4d](https://linux-hardware.org/?probe=6568ba5b4d) | May 13, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [a60326fa0a](https://linux-hardware.org/?probe=a60326fa0a) | May 13, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [2d1acb409a](https://linux-hardware.org/?probe=2d1acb409a) | May 13, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [edc8069ae1](https://linux-hardware.org/?probe=edc8069ae1) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [1146828988](https://linux-hardware.org/?probe=1146828988) | May 13, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [fd2bd3be00](https://linux-hardware.org/?probe=fd2bd3be00) | May 13, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [971b7bfcd1](https://linux-hardware.org/?probe=971b7bfcd1) | May 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [82f01de919](https://linux-hardware.org/?probe=82f01de919) | May 12, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [8bad0045f6](https://linux-hardware.org/?probe=8bad0045f6) | May 12, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [78e2c8b948](https://linux-hardware.org/?probe=78e2c8b948) | May 12, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [c9ad858393](https://linux-hardware.org/?probe=c9ad858393) | May 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [01ee28074b](https://linux-hardware.org/?probe=01ee28074b) | May 12, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [f9c1eb381f](https://linux-hardware.org/?probe=f9c1eb381f) | May 11, 2023 |
| Toshiba       | Satellite C75-A             | Notebook    | [5be756cc91](https://linux-hardware.org/?probe=5be756cc91) | May 11, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [e18646482f](https://linux-hardware.org/?probe=e18646482f) | May 11, 2023 |
| Dell          | Latitude 7390               | Notebook    | [ab2ea4f7a0](https://linux-hardware.org/?probe=ab2ea4f7a0) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a7155be531](https://linux-hardware.org/?probe=a7155be531) | May 11, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [ec1f5e50b8](https://linux-hardware.org/?probe=ec1f5e50b8) | May 11, 2023 |
| Biostar       | H110MHV3                    | Desktop     | [e1ce381308](https://linux-hardware.org/?probe=e1ce381308) | May 11, 2023 |
| Biostar       | H110MHV3                    | Desktop     | [5b0f8f8419](https://linux-hardware.org/?probe=5b0f8f8419) | May 11, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a7178f5792](https://linux-hardware.org/?probe=a7178f5792) | May 11, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d3893db138](https://linux-hardware.org/?probe=d3893db138) | May 10, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [a196cd6710](https://linux-hardware.org/?probe=a196cd6710) | May 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [3ea46668c4](https://linux-hardware.org/?probe=3ea46668c4) | May 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [2b0bc04757](https://linux-hardware.org/?probe=2b0bc04757) | May 10, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [1060697095](https://linux-hardware.org/?probe=1060697095) | May 10, 2023 |
| Lenovo        | ThinkPad T450s 20BWS34A0... | Notebook    | [775c2839fa](https://linux-hardware.org/?probe=775c2839fa) | May 10, 2023 |
| Dell          | Latitude 5420               | Notebook    | [2f3519c123](https://linux-hardware.org/?probe=2f3519c123) | May 09, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [695a40ecc7](https://linux-hardware.org/?probe=695a40ecc7) | May 09, 2023 |
| Sony          | SVT1312B4E                  | Notebook    | [dc0f581bc3](https://linux-hardware.org/?probe=dc0f581bc3) | May 09, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [588003adc9](https://linux-hardware.org/?probe=588003adc9) | May 09, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [6c5da31f8b](https://linux-hardware.org/?probe=6c5da31f8b) | May 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| MSI           | MS-7502 Fab D               | Desktop     | [ca5881d77e](https://linux-hardware.org/?probe=ca5881d77e) | May 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0628913a60](https://linux-hardware.org/?probe=0628913a60) | May 08, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [e44f7dfac5](https://linux-hardware.org/?probe=e44f7dfac5) | May 08, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [cabb24b0e7](https://linux-hardware.org/?probe=cabb24b0e7) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f5499886e9](https://linux-hardware.org/?probe=f5499886e9) | May 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7f274b189d](https://linux-hardware.org/?probe=7f274b189d) | May 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a4f7fc7b31](https://linux-hardware.org/?probe=a4f7fc7b31) | May 08, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [dcf5cd4ca2](https://linux-hardware.org/?probe=dcf5cd4ca2) | May 08, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [332c45b4be](https://linux-hardware.org/?probe=332c45b4be) | May 07, 2023 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [2e778bdf24](https://linux-hardware.org/?probe=2e778bdf24) | May 07, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [30bd232e19](https://linux-hardware.org/?probe=30bd232e19) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [923397bc88](https://linux-hardware.org/?probe=923397bc88) | May 07, 2023 |
| Lenovo        | V110-15IKB 80TH             | Notebook    | [a908ca11db](https://linux-hardware.org/?probe=a908ca11db) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [f60c4cb29b](https://linux-hardware.org/?probe=f60c4cb29b) | May 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [369bf3dc68](https://linux-hardware.org/?probe=369bf3dc68) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [f7a174063f](https://linux-hardware.org/?probe=f7a174063f) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [b3c5b71d27](https://linux-hardware.org/?probe=b3c5b71d27) | May 07, 2023 |
| Dell          | Latitude E7440              | Notebook    | [e49cf2551c](https://linux-hardware.org/?probe=e49cf2551c) | May 07, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [af42781d8a](https://linux-hardware.org/?probe=af42781d8a) | May 06, 2023 |
| Dell          | Studio 1749                 | Notebook    | [43eb37cfd7](https://linux-hardware.org/?probe=43eb37cfd7) | May 06, 2023 |
| Dell          | Latitude E4200              | Notebook    | [af2baa1787](https://linux-hardware.org/?probe=af2baa1787) | May 06, 2023 |
| Acer          | Predator PO3-620            | Desktop     | [9ef46f7f3e](https://linux-hardware.org/?probe=9ef46f7f3e) | May 06, 2023 |
| MSI           | MS-7502 Fab D               | Desktop     | [9b80139aca](https://linux-hardware.org/?probe=9b80139aca) | May 06, 2023 |
| MSI           | MEG Z590 ACE GOLD EDITIO... | Desktop     | [e34348c1b5](https://linux-hardware.org/?probe=e34348c1b5) | May 06, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [70862b2870](https://linux-hardware.org/?probe=70862b2870) | May 06, 2023 |
| Google        | Samus                       | Notebook    | [aed9bd140f](https://linux-hardware.org/?probe=aed9bd140f) | May 06, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [a7ef6c976c](https://linux-hardware.org/?probe=a7ef6c976c) | May 06, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [644110c9b9](https://linux-hardware.org/?probe=644110c9b9) | May 06, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [ee58ce6d9c](https://linux-hardware.org/?probe=ee58ce6d9c) | May 06, 2023 |
| MSI           | GS43VR 7RE                  | Notebook    | [4eb5973faa](https://linux-hardware.org/?probe=4eb5973faa) | May 06, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [5c506f94e0](https://linux-hardware.org/?probe=5c506f94e0) | May 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [808f3370fc](https://linux-hardware.org/?probe=808f3370fc) | May 05, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [db330cab38](https://linux-hardware.org/?probe=db330cab38) | May 05, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [af27e2497a](https://linux-hardware.org/?probe=af27e2497a) | May 05, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [8e19b0629d](https://linux-hardware.org/?probe=8e19b0629d) | May 05, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f7f8025263](https://linux-hardware.org/?probe=f7f8025263) | May 05, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [64aa7fb49b](https://linux-hardware.org/?probe=64aa7fb49b) | May 05, 2023 |
| HP            | 304Ah                       | Desktop     | [d9a160845c](https://linux-hardware.org/?probe=d9a160845c) | May 05, 2023 |
| Medion        | Akoya E1317T                | Notebook    | [e8eb05a52a](https://linux-hardware.org/?probe=e8eb05a52a) | May 05, 2023 |
| HP            | 21EF                        | Desktop     | [6dd5a8409e](https://linux-hardware.org/?probe=6dd5a8409e) | May 05, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [624e1c3f06](https://linux-hardware.org/?probe=624e1c3f06) | May 05, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [7fd9fd4619](https://linux-hardware.org/?probe=7fd9fd4619) | May 04, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [040ab09ebe](https://linux-hardware.org/?probe=040ab09ebe) | May 04, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2fb5ac306a](https://linux-hardware.org/?probe=2fb5ac306a) | May 04, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [d4d069aa0c](https://linux-hardware.org/?probe=d4d069aa0c) | May 04, 2023 |
| HP            | 1589                        | Desktop     | [af8e129ecd](https://linux-hardware.org/?probe=af8e129ecd) | May 04, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e8c596445b](https://linux-hardware.org/?probe=e8c596445b) | May 04, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [372a18076a](https://linux-hardware.org/?probe=372a18076a) | May 04, 2023 |
| Google        | Samus                       | Notebook    | [a7dfa29233](https://linux-hardware.org/?probe=a7dfa29233) | May 04, 2023 |
| Supermicro    | H12SSL-NT                   | Server      | [6161a05cf1](https://linux-hardware.org/?probe=6161a05cf1) | May 04, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [61cde0d9b2](https://linux-hardware.org/?probe=61cde0d9b2) | May 04, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b3ed654fde](https://linux-hardware.org/?probe=b3ed654fde) | May 04, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6ec4c764ea](https://linux-hardware.org/?probe=6ec4c764ea) | May 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [df62d15ecc](https://linux-hardware.org/?probe=df62d15ecc) | May 03, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [7996838ce9](https://linux-hardware.org/?probe=7996838ce9) | May 03, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [aac11fced2](https://linux-hardware.org/?probe=aac11fced2) | May 03, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [c488f6ab32](https://linux-hardware.org/?probe=c488f6ab32) | May 03, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [da9c172649](https://linux-hardware.org/?probe=da9c172649) | May 03, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [b68d1b92de](https://linux-hardware.org/?probe=b68d1b92de) | May 03, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [c20844716d](https://linux-hardware.org/?probe=c20844716d) | May 03, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [f87b1ac774](https://linux-hardware.org/?probe=f87b1ac774) | May 03, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [d8b268f8f7](https://linux-hardware.org/?probe=d8b268f8f7) | May 03, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [3c7546e88a](https://linux-hardware.org/?probe=3c7546e88a) | May 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [388caab99a](https://linux-hardware.org/?probe=388caab99a) | May 02, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [26bb61d72f](https://linux-hardware.org/?probe=26bb61d72f) | May 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [ae3ef173a7](https://linux-hardware.org/?probe=ae3ef173a7) | May 02, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [ccc620956f](https://linux-hardware.org/?probe=ccc620956f) | May 02, 2023 |
| Advent        | Roma                        | Notebook    | [ec7568545d](https://linux-hardware.org/?probe=ec7568545d) | May 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [f28e109a4b](https://linux-hardware.org/?probe=f28e109a4b) | May 02, 2023 |
| ASUSTek       | X401A1                      | Notebook    | [2a7d35cc4e](https://linux-hardware.org/?probe=2a7d35cc4e) | May 01, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [3c422c5e96](https://linux-hardware.org/?probe=3c422c5e96) | May 01, 2023 |
| Samsung       | 950QDB                      | Convertible | [ecae18f163](https://linux-hardware.org/?probe=ecae18f163) | May 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a5a0f75aa](https://linux-hardware.org/?probe=7a5a0f75aa) | May 01, 2023 |
| Acer          | Aspire M3970                | Desktop     | [87a55abfa7](https://linux-hardware.org/?probe=87a55abfa7) | May 01, 2023 |
| lapbook       | S15 PRO                     | Notebook    | [d4b7c4a4db](https://linux-hardware.org/?probe=d4b7c4a4db) | May 01, 2023 |
| Dell          | Precision 5530              | Notebook    | [c8878b0f0f](https://linux-hardware.org/?probe=c8878b0f0f) | May 01, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f75b4a9457](https://linux-hardware.org/?probe=f75b4a9457) | May 01, 2023 |
| ASUSTek       | H81-PLUS                    | Desktop     | [3b45144d62](https://linux-hardware.org/?probe=3b45144d62) | Apr 30, 2023 |
| Toshiba       | EQUIUM P200                 | Notebook    | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [1e10eaa9ae](https://linux-hardware.org/?probe=1e10eaa9ae) | Apr 30, 2023 |
| Lenovo        | ThinkPad X230 2325V1K       | Notebook    | [d630569df9](https://linux-hardware.org/?probe=d630569df9) | Apr 30, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | Notebook    | [dff6f75899](https://linux-hardware.org/?probe=dff6f75899) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [f0a784354c](https://linux-hardware.org/?probe=f0a784354c) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [332a777929](https://linux-hardware.org/?probe=332a777929) | Apr 30, 2023 |
| HP            | 1998                        | Desktop     | [4ba5ef1211](https://linux-hardware.org/?probe=4ba5ef1211) | Apr 30, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7521d3d742](https://linux-hardware.org/?probe=7521d3d742) | Apr 30, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e3371ae2dc](https://linux-hardware.org/?probe=e3371ae2dc) | Apr 30, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [04a7cea7cb](https://linux-hardware.org/?probe=04a7cea7cb) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [da5f050510](https://linux-hardware.org/?probe=da5f050510) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [1e65b46a12](https://linux-hardware.org/?probe=1e65b46a12) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f2ad30321e](https://linux-hardware.org/?probe=f2ad30321e) | Apr 29, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6976f884e6](https://linux-hardware.org/?probe=6976f884e6) | Apr 29, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7c8260664a](https://linux-hardware.org/?probe=7c8260664a) | Apr 29, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [a158a30802](https://linux-hardware.org/?probe=a158a30802) | Apr 29, 2023 |
| Intel         | S5500BC E25124-453          | Server      | [94527a8584](https://linux-hardware.org/?probe=94527a8584) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [6b44ad5061](https://linux-hardware.org/?probe=6b44ad5061) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [ce73a703b6](https://linux-hardware.org/?probe=ce73a703b6) | Apr 29, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [e70d66b3ba](https://linux-hardware.org/?probe=e70d66b3ba) | Apr 29, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [855bed0070](https://linux-hardware.org/?probe=855bed0070) | Apr 28, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [8a23a0fef0](https://linux-hardware.org/?probe=8a23a0fef0) | Apr 28, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [831cd8fa39](https://linux-hardware.org/?probe=831cd8fa39) | Apr 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [d364cb5ac7](https://linux-hardware.org/?probe=d364cb5ac7) | Apr 28, 2023 |
| HP            | ENVY Notebook               | Notebook    | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [2dc65d8f07](https://linux-hardware.org/?probe=2dc65d8f07) | Apr 28, 2023 |
| Intel         | S5500BC E25124-453          | Server      | [567a76c24f](https://linux-hardware.org/?probe=567a76c24f) | Apr 28, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | Desktop     | [c8fe6ab042](https://linux-hardware.org/?probe=c8fe6ab042) | Apr 28, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | Notebook    | [6569669912](https://linux-hardware.org/?probe=6569669912) | Apr 28, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [9130280424](https://linux-hardware.org/?probe=9130280424) | Apr 28, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [2de1d6f6f5](https://linux-hardware.org/?probe=2de1d6f6f5) | Apr 28, 2023 |
| Dell          | Latitude E7450              | Notebook    | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [26c158df39](https://linux-hardware.org/?probe=26c158df39) | Apr 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [0958caf898](https://linux-hardware.org/?probe=0958caf898) | Apr 27, 2023 |
| HP            | 1589                        | Desktop     | [632f486421](https://linux-hardware.org/?probe=632f486421) | Apr 27, 2023 |
| Lenovo        | Legion 7-16-ITHg6 82K6      | Notebook    | [2baf2cbc85](https://linux-hardware.org/?probe=2baf2cbc85) | Apr 27, 2023 |
| Lenovo        | ThinkPad X230 2325O32       | Notebook    | [b38ef1a717](https://linux-hardware.org/?probe=b38ef1a717) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [ae51577ddc](https://linux-hardware.org/?probe=ae51577ddc) | Apr 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [19c2a17ec5](https://linux-hardware.org/?probe=19c2a17ec5) | Apr 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [6601cb2397](https://linux-hardware.org/?probe=6601cb2397) | Apr 26, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [e35780d356](https://linux-hardware.org/?probe=e35780d356) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [54dea0607f](https://linux-hardware.org/?probe=54dea0607f) | Apr 26, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [238598d9ab](https://linux-hardware.org/?probe=238598d9ab) | Apr 26, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [ac51617470](https://linux-hardware.org/?probe=ac51617470) | Apr 26, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [f0ea43f3fd](https://linux-hardware.org/?probe=f0ea43f3fd) | Apr 26, 2023 |
| Intel         | DQ67OW AAG12528-307         | Desktop     | [28245ea080](https://linux-hardware.org/?probe=28245ea080) | Apr 25, 2023 |
| HP            | 18E9                        | Desktop     | [b9bb679cca](https://linux-hardware.org/?probe=b9bb679cca) | Apr 25, 2023 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [8a600077f6](https://linux-hardware.org/?probe=8a600077f6) | Apr 25, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [19ca73662f](https://linux-hardware.org/?probe=19ca73662f) | Apr 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c5adfbd376](https://linux-hardware.org/?probe=c5adfbd376) | Apr 25, 2023 |
| Google        | Sasuke                      | Notebook    | [7615a1b1e5](https://linux-hardware.org/?probe=7615a1b1e5) | Apr 25, 2023 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [cd95f8ec71](https://linux-hardware.org/?probe=cd95f8ec71) | Apr 25, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [290a99fee9](https://linux-hardware.org/?probe=290a99fee9) | Apr 25, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [9306db1f90](https://linux-hardware.org/?probe=9306db1f90) | Apr 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [620668d216](https://linux-hardware.org/?probe=620668d216) | Apr 25, 2023 |
| Dell          | Latitude XT2                | Notebook    | [62df7dc069](https://linux-hardware.org/?probe=62df7dc069) | Apr 24, 2023 |
| Intel         | HM570                       | Desktop     | [1220357b3d](https://linux-hardware.org/?probe=1220357b3d) | Apr 24, 2023 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [f68e55cabc](https://linux-hardware.org/?probe=f68e55cabc) | Apr 24, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [c78c7e9ec1](https://linux-hardware.org/?probe=c78c7e9ec1) | Apr 24, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [267c5b8075](https://linux-hardware.org/?probe=267c5b8075) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [70d478e2eb](https://linux-hardware.org/?probe=70d478e2eb) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [2931b721a3](https://linux-hardware.org/?probe=2931b721a3) | Apr 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [df85ceaa6b](https://linux-hardware.org/?probe=df85ceaa6b) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [c47ec3530e](https://linux-hardware.org/?probe=c47ec3530e) | Apr 24, 2023 |
| HP            | Stream Notebook PC 13       | Notebook    | [455c6b5e28](https://linux-hardware.org/?probe=455c6b5e28) | Apr 23, 2023 |
| Linx          | LINX10V64                   | Tablet      | [84fc9aff4b](https://linux-hardware.org/?probe=84fc9aff4b) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [982ca9079d](https://linux-hardware.org/?probe=982ca9079d) | Apr 23, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [d8b51c995c](https://linux-hardware.org/?probe=d8b51c995c) | Apr 23, 2023 |
| MSI           | A88XM-E35                   | Desktop     | [c26812e2e1](https://linux-hardware.org/?probe=c26812e2e1) | Apr 23, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [bdfb512e83](https://linux-hardware.org/?probe=bdfb512e83) | Apr 23, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [25e942e55c](https://linux-hardware.org/?probe=25e942e55c) | Apr 22, 2023 |
| Gigabyte      | B460 HD3                    | Desktop     | [c9e3b1d5ea](https://linux-hardware.org/?probe=c9e3b1d5ea) | Apr 22, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | Notebook    | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [0cd5599131](https://linux-hardware.org/?probe=0cd5599131) | Apr 22, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [3c0a66f0fc](https://linux-hardware.org/?probe=3c0a66f0fc) | Apr 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [5aa26aea52](https://linux-hardware.org/?probe=5aa26aea52) | Apr 22, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [4f473af7a9](https://linux-hardware.org/?probe=4f473af7a9) | Apr 22, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [936e6fc768](https://linux-hardware.org/?probe=936e6fc768) | Apr 22, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [e0763f0f69](https://linux-hardware.org/?probe=e0763f0f69) | Apr 22, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [18391e6b6e](https://linux-hardware.org/?probe=18391e6b6e) | Apr 21, 2023 |
| HP            | 18E5                        | Desktop     | [0437b3deb1](https://linux-hardware.org/?probe=0437b3deb1) | Apr 21, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [f1227ea669](https://linux-hardware.org/?probe=f1227ea669) | Apr 21, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [6b0104f339](https://linux-hardware.org/?probe=6b0104f339) | Apr 21, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [03bcaf6334](https://linux-hardware.org/?probe=03bcaf6334) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [dfbfce9d2e](https://linux-hardware.org/?probe=dfbfce9d2e) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [6720e15331](https://linux-hardware.org/?probe=6720e15331) | Apr 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [66f95f2851](https://linux-hardware.org/?probe=66f95f2851) | Apr 21, 2023 |
| Google        | Swanky                      | Notebook    | [92156daf53](https://linux-hardware.org/?probe=92156daf53) | Apr 21, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [61d7104ec4](https://linux-hardware.org/?probe=61d7104ec4) | Apr 21, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [ea76b8632f](https://linux-hardware.org/?probe=ea76b8632f) | Apr 20, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [2afe988f2e](https://linux-hardware.org/?probe=2afe988f2e) | Apr 20, 2023 |
| Acer          | Aspire M3970                | Desktop     | [d43372f3fd](https://linux-hardware.org/?probe=d43372f3fd) | Apr 20, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [f8f6ec2123](https://linux-hardware.org/?probe=f8f6ec2123) | Apr 20, 2023 |
| Dell          | 05WNJ2 A02                  | Server      | [a0623dc5a7](https://linux-hardware.org/?probe=a0623dc5a7) | Apr 20, 2023 |
| Lenovo        | 300e 2nd Gen 82GK           | Convertible | [54c7413bc5](https://linux-hardware.org/?probe=54c7413bc5) | Apr 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [063b4867ba](https://linux-hardware.org/?probe=063b4867ba) | Apr 20, 2023 |
| Intel         | DG43GT AAE62768-301         | Desktop     | [643ed4ce33](https://linux-hardware.org/?probe=643ed4ce33) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | Notebook    | [1ba852f185](https://linux-hardware.org/?probe=1ba852f185) | Apr 20, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [68a7470480](https://linux-hardware.org/?probe=68a7470480) | Apr 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | Desktop     | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [04a458482b](https://linux-hardware.org/?probe=04a458482b) | Apr 19, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | Desktop     | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| Toshiba       | Satellite Pro C850-1HE      | Notebook    | [48d3d92f3d](https://linux-hardware.org/?probe=48d3d92f3d) | Apr 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [85700f4804](https://linux-hardware.org/?probe=85700f4804) | Apr 19, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [5cbbc95995](https://linux-hardware.org/?probe=5cbbc95995) | Apr 19, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [ff7225c921](https://linux-hardware.org/?probe=ff7225c921) | Apr 19, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a70cdf4848](https://linux-hardware.org/?probe=a70cdf4848) | Apr 19, 2023 |
| Dell          | G5 5590                     | Notebook    | [c7334114be](https://linux-hardware.org/?probe=c7334114be) | Apr 18, 2023 |
| Lenovo        | CRESCENTBAY 31900058 WIN... | All in one  | [529c1ed52a](https://linux-hardware.org/?probe=529c1ed52a) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [323dc7fa4b](https://linux-hardware.org/?probe=323dc7fa4b) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [28d52a565b](https://linux-hardware.org/?probe=28d52a565b) | Apr 18, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [c7a5aadd85](https://linux-hardware.org/?probe=c7a5aadd85) | Apr 18, 2023 |
| LG Electro... | 17Z90Q-K.AA78A1             | Notebook    | [594a7fa16b](https://linux-hardware.org/?probe=594a7fa16b) | Apr 18, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [c34c1abf02](https://linux-hardware.org/?probe=c34c1abf02) | Apr 18, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [4be523b9a9](https://linux-hardware.org/?probe=4be523b9a9) | Apr 18, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [5c07d2203c](https://linux-hardware.org/?probe=5c07d2203c) | Apr 17, 2023 |
| Samsung       | 930QED                      | Convertible | [fdfe04c5c9](https://linux-hardware.org/?probe=fdfe04c5c9) | Apr 17, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c5ceac2597](https://linux-hardware.org/?probe=c5ceac2597) | Apr 17, 2023 |
| Sony          | SVE1711C5E                  | Notebook    | [e4fbd8fca9](https://linux-hardware.org/?probe=e4fbd8fca9) | Apr 17, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [a70c93f2e7](https://linux-hardware.org/?probe=a70c93f2e7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| AZW           | Speed S                     | Desktop     | [7cf5e54f5b](https://linux-hardware.org/?probe=7cf5e54f5b) | Apr 16, 2023 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [fd0b3fe549](https://linux-hardware.org/?probe=fd0b3fe549) | Apr 16, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [3ad1ee8197](https://linux-hardware.org/?probe=3ad1ee8197) | Apr 16, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [2092251807](https://linux-hardware.org/?probe=2092251807) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9b05d61f11](https://linux-hardware.org/?probe=9b05d61f11) | Apr 16, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [000e6c6702](https://linux-hardware.org/?probe=000e6c6702) | Apr 16, 2023 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [44222bc590](https://linux-hardware.org/?probe=44222bc590) | Apr 16, 2023 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [592c412bd9](https://linux-hardware.org/?probe=592c412bd9) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [962c5734bc](https://linux-hardware.org/?probe=962c5734bc) | Apr 15, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [2e860ef402](https://linux-hardware.org/?probe=2e860ef402) | Apr 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [00ee6cd73f](https://linux-hardware.org/?probe=00ee6cd73f) | Apr 15, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [11b817e884](https://linux-hardware.org/?probe=11b817e884) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [19fc60d2a5](https://linux-hardware.org/?probe=19fc60d2a5) | Apr 14, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [f5940f5ed5](https://linux-hardware.org/?probe=f5940f5ed5) | Apr 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [f3248c9bca](https://linux-hardware.org/?probe=f3248c9bca) | Apr 14, 2023 |
| Acer          | Aspire M3970                | Desktop     | [0792e082e7](https://linux-hardware.org/?probe=0792e082e7) | Apr 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4f384271e](https://linux-hardware.org/?probe=d4f384271e) | Apr 14, 2023 |
| Clevo         | W760T/M740T/M760T           | Notebook    | [0dfaa8f0e8](https://linux-hardware.org/?probe=0dfaa8f0e8) | Apr 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [7bd7802e04](https://linux-hardware.org/?probe=7bd7802e04) | Apr 14, 2023 |
| HUAWEI        | MRG-WXX                     | Notebook    | [56c255e5f0](https://linux-hardware.org/?probe=56c255e5f0) | Apr 14, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [c76a516113](https://linux-hardware.org/?probe=c76a516113) | Apr 14, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [bd9c1c1e6d](https://linux-hardware.org/?probe=bd9c1c1e6d) | Apr 14, 2023 |
| HP            | Notebook                    | Notebook    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [0632bfe4d0](https://linux-hardware.org/?probe=0632bfe4d0) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [407ca5845d](https://linux-hardware.org/?probe=407ca5845d) | Apr 13, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [106963edf7](https://linux-hardware.org/?probe=106963edf7) | Apr 13, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [c3962286cb](https://linux-hardware.org/?probe=c3962286cb) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| Shuttle       | FH67                        | Desktop     | [daa2f39981](https://linux-hardware.org/?probe=daa2f39981) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | Notebook    | [9ac01d9237](https://linux-hardware.org/?probe=9ac01d9237) | Apr 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [615a9d3871](https://linux-hardware.org/?probe=615a9d3871) | Apr 12, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [401c4d8143](https://linux-hardware.org/?probe=401c4d8143) | Apr 12, 2023 |
| Sony          | SVE1711C5E                  | Notebook    | [07c6f843fb](https://linux-hardware.org/?probe=07c6f843fb) | Apr 12, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [551fabbc17](https://linux-hardware.org/?probe=551fabbc17) | Apr 12, 2023 |
| Dell          | 02K9CR A01                  | Desktop     | [45c419b8d6](https://linux-hardware.org/?probe=45c419b8d6) | Apr 12, 2023 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [19c864f074](https://linux-hardware.org/?probe=19c864f074) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Lenovo        | YB1-X91F                    | Convertible | [e4c0490b89](https://linux-hardware.org/?probe=e4c0490b89) | Apr 12, 2023 |
| Google        | Gnawty                      | Notebook    | [ddb0fea339](https://linux-hardware.org/?probe=ddb0fea339) | Apr 12, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [e92e5de977](https://linux-hardware.org/?probe=e92e5de977) | Apr 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [07bd1b4df7](https://linux-hardware.org/?probe=07bd1b4df7) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [8297ce2712](https://linux-hardware.org/?probe=8297ce2712) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [e3fc8c8f43](https://linux-hardware.org/?probe=e3fc8c8f43) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [7863ff02eb](https://linux-hardware.org/?probe=7863ff02eb) | Apr 11, 2023 |
| ASRock        | Z77 Pro4                    | Desktop     | [7f718ab68f](https://linux-hardware.org/?probe=7f718ab68f) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [01cae1e152](https://linux-hardware.org/?probe=01cae1e152) | Apr 10, 2023 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [6fd82ceaec](https://linux-hardware.org/?probe=6fd82ceaec) | Apr 09, 2023 |
| lapbook       | S15 PRO                     | Notebook    | [5a039fc6fb](https://linux-hardware.org/?probe=5a039fc6fb) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | Notebook    | [8def87668b](https://linux-hardware.org/?probe=8def87668b) | Apr 09, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [bc5cbcd2cb](https://linux-hardware.org/?probe=bc5cbcd2cb) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| Dell          | Inspiron 7570               | Notebook    | [2bac711aba](https://linux-hardware.org/?probe=2bac711aba) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [7dc7e5e5c3](https://linux-hardware.org/?probe=7dc7e5e5c3) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [b1c4404d58](https://linux-hardware.org/?probe=b1c4404d58) | Apr 09, 2023 |
| Dell          | 0PU052                      | Desktop     | [8f8c7f3a02](https://linux-hardware.org/?probe=8f8c7f3a02) | Apr 09, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [52728f9e37](https://linux-hardware.org/?probe=52728f9e37) | Apr 08, 2023 |
| Google        | Ampton                      | Notebook    | [e3945d7727](https://linux-hardware.org/?probe=e3945d7727) | Apr 08, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [14a3d5f4be](https://linux-hardware.org/?probe=14a3d5f4be) | Apr 08, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [5cf4615347](https://linux-hardware.org/?probe=5cf4615347) | Apr 08, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [ef0fbbe0aa](https://linux-hardware.org/?probe=ef0fbbe0aa) | Apr 08, 2023 |
| Dell          | 0KRC95 A01                  | Desktop     | [9300a95302](https://linux-hardware.org/?probe=9300a95302) | Apr 07, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [aab830c5dd](https://linux-hardware.org/?probe=aab830c5dd) | Apr 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0f3e23c7ce](https://linux-hardware.org/?probe=0f3e23c7ce) | Apr 07, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [8c4f851451](https://linux-hardware.org/?probe=8c4f851451) | Apr 07, 2023 |
| HP            | 82A2                        | Desktop     | [68d2b054d7](https://linux-hardware.org/?probe=68d2b054d7) | Apr 07, 2023 |
| Google        | Bluebird                    | Notebook    | [6ab22238ac](https://linux-hardware.org/?probe=6ab22238ac) | Apr 07, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [5dc44169d0](https://linux-hardware.org/?probe=5dc44169d0) | Apr 07, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [77c6d48d6b](https://linux-hardware.org/?probe=77c6d48d6b) | Apr 06, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [a0584206ea](https://linux-hardware.org/?probe=a0584206ea) | Apr 06, 2023 |
| Dell          | Latitude 7320               | Convertible | [1e86d8349b](https://linux-hardware.org/?probe=1e86d8349b) | Apr 06, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e05bffcc8a](https://linux-hardware.org/?probe=e05bffcc8a) | Apr 06, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [e2b1578d42](https://linux-hardware.org/?probe=e2b1578d42) | Apr 06, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [2cd7831b58](https://linux-hardware.org/?probe=2cd7831b58) | Apr 06, 2023 |
| Google        | Bard                        | Notebook    | [cc1d159d0c](https://linux-hardware.org/?probe=cc1d159d0c) | Apr 05, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [43469cea83](https://linux-hardware.org/?probe=43469cea83) | Apr 05, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [64c9557d34](https://linux-hardware.org/?probe=64c9557d34) | Apr 05, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8bf7c8a569](https://linux-hardware.org/?probe=8bf7c8a569) | Apr 05, 2023 |
| Dell          | Latitude E5550              | Notebook    | [5527315153](https://linux-hardware.org/?probe=5527315153) | Apr 05, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [011057afa2](https://linux-hardware.org/?probe=011057afa2) | Apr 05, 2023 |
| HP            | 0A9Ch                       | Desktop     | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [eadee78860](https://linux-hardware.org/?probe=eadee78860) | Apr 05, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [5c12ed53b7](https://linux-hardware.org/?probe=5c12ed53b7) | Apr 05, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [6896e5d9e2](https://linux-hardware.org/?probe=6896e5d9e2) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [540d1f11a6](https://linux-hardware.org/?probe=540d1f11a6) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [b5740f3323](https://linux-hardware.org/?probe=b5740f3323) | Apr 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [40ec4e3ec9](https://linux-hardware.org/?probe=40ec4e3ec9) | Apr 04, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [4e7cae1fde](https://linux-hardware.org/?probe=4e7cae1fde) | Apr 04, 2023 |
| ASUSTek       | X99-A II                    | Desktop     | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [d79463ea93](https://linux-hardware.org/?probe=d79463ea93) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [b7068fce05](https://linux-hardware.org/?probe=b7068fce05) | Apr 04, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ed948ed552](https://linux-hardware.org/?probe=ed948ed552) | Apr 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1eae1b3796](https://linux-hardware.org/?probe=1eae1b3796) | Apr 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [1af0b7675b](https://linux-hardware.org/?probe=1af0b7675b) | Apr 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [739f49ff7e](https://linux-hardware.org/?probe=739f49ff7e) | Apr 04, 2023 |
| Dell          | Studio 1558                 | Notebook    | [e9b75d657d](https://linux-hardware.org/?probe=e9b75d657d) | Apr 04, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [3e174ff8a3](https://linux-hardware.org/?probe=3e174ff8a3) | Apr 04, 2023 |
| Lenovo        | Brazos                      | Notebook    | [6415cb26c2](https://linux-hardware.org/?probe=6415cb26c2) | Apr 03, 2023 |
| ASRock        | 990FX Extreme3              | Desktop     | [013cd9b246](https://linux-hardware.org/?probe=013cd9b246) | Apr 03, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4061ae40b8](https://linux-hardware.org/?probe=4061ae40b8) | Apr 03, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [b65273209b](https://linux-hardware.org/?probe=b65273209b) | Apr 03, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| AZW           | GTR V01                     | Mini pc     | [83603a9aa8](https://linux-hardware.org/?probe=83603a9aa8) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [9a44a4b80a](https://linux-hardware.org/?probe=9a44a4b80a) | Apr 03, 2023 |
| Pegatron      | JESSE                       | Desktop     | [60c37e2dda](https://linux-hardware.org/?probe=60c37e2dda) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d7f3280e60](https://linux-hardware.org/?probe=d7f3280e60) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fb4f4da720](https://linux-hardware.org/?probe=fb4f4da720) | Apr 03, 2023 |
| Advent        | Roma                        | Notebook    | [e1bd64e5b5](https://linux-hardware.org/?probe=e1bd64e5b5) | Apr 03, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [daa2099403](https://linux-hardware.org/?probe=daa2099403) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8f8d89fe9a](https://linux-hardware.org/?probe=8f8d89fe9a) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a5d404ca3d](https://linux-hardware.org/?probe=a5d404ca3d) | Apr 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [77b1f3bc3e](https://linux-hardware.org/?probe=77b1f3bc3e) | Apr 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [65cee818b6](https://linux-hardware.org/?probe=65cee818b6) | Apr 02, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [36c7cf7a43](https://linux-hardware.org/?probe=36c7cf7a43) | Apr 02, 2023 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [48f07855d1](https://linux-hardware.org/?probe=48f07855d1) | Apr 02, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [c7791aac7c](https://linux-hardware.org/?probe=c7791aac7c) | Apr 02, 2023 |
| Lenovo        | ThinkPad T460p 20FXS08N0... | Notebook    | [ffcf174547](https://linux-hardware.org/?probe=ffcf174547) | Apr 02, 2023 |
| AZW           | U59                         | Desktop     | [ad59e8fe21](https://linux-hardware.org/?probe=ad59e8fe21) | Apr 02, 2023 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | Notebook    | [3ec9fed32b](https://linux-hardware.org/?probe=3ec9fed32b) | Apr 02, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [16e982e5cb](https://linux-hardware.org/?probe=16e982e5cb) | Apr 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [7d6ecc10d8](https://linux-hardware.org/?probe=7d6ecc10d8) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [58e2308d1e](https://linux-hardware.org/?probe=58e2308d1e) | Apr 02, 2023 |
| Acer          | Predator PO3-610            | Desktop     | [c5fd8fda48](https://linux-hardware.org/?probe=c5fd8fda48) | Apr 02, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [dda3791c20](https://linux-hardware.org/?probe=dda3791c20) | Apr 01, 2023 |
| Eii           | WSA116                      | Notebook    | [00bf1c190b](https://linux-hardware.org/?probe=00bf1c190b) | Apr 01, 2023 |
| ASUSTek       | U6Sg                        | Notebook    | [4fc2057b02](https://linux-hardware.org/?probe=4fc2057b02) | Apr 01, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [575a0650aa](https://linux-hardware.org/?probe=575a0650aa) | Apr 01, 2023 |
| ASUSTek       | U6Sg                        | Notebook    | [c97f807bb0](https://linux-hardware.org/?probe=c97f807bb0) | Apr 01, 2023 |
| HP            | Notebook                    | Notebook    | [348d80772f](https://linux-hardware.org/?probe=348d80772f) | Apr 01, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [cea0d2797d](https://linux-hardware.org/?probe=cea0d2797d) | Apr 01, 2023 |
| Acer          | H57M01                      | Desktop     | [215701a84d](https://linux-hardware.org/?probe=215701a84d) | Apr 01, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ecd633a350](https://linux-hardware.org/?probe=ecd633a350) | Apr 01, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [dc5fce2825](https://linux-hardware.org/?probe=dc5fce2825) | Apr 01, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [664da8ff45](https://linux-hardware.org/?probe=664da8ff45) | Apr 01, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [714ed0f007](https://linux-hardware.org/?probe=714ed0f007) | Apr 01, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [82d28ac7c0](https://linux-hardware.org/?probe=82d28ac7c0) | Apr 01, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [1146b0ebfc](https://linux-hardware.org/?probe=1146b0ebfc) | Apr 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [2628ea9d8e](https://linux-hardware.org/?probe=2628ea9d8e) | Apr 01, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [caaa544589](https://linux-hardware.org/?probe=caaa544589) | Apr 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [d9a7a6ccf6](https://linux-hardware.org/?probe=d9a7a6ccf6) | Mar 31, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | Desktop     | [49917003da](https://linux-hardware.org/?probe=49917003da) | Mar 31, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [dbe7f7ac9b](https://linux-hardware.org/?probe=dbe7f7ac9b) | Mar 31, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [8ce3dc1981](https://linux-hardware.org/?probe=8ce3dc1981) | Mar 31, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [68fce9ae2d](https://linux-hardware.org/?probe=68fce9ae2d) | Mar 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [d5e7a881e6](https://linux-hardware.org/?probe=d5e7a881e6) | Mar 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [5b3718d617](https://linux-hardware.org/?probe=5b3718d617) | Mar 31, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [fe51f2c62f](https://linux-hardware.org/?probe=fe51f2c62f) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [31d333ecc9](https://linux-hardware.org/?probe=31d333ecc9) | Mar 30, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [3bf5fd0cfd](https://linux-hardware.org/?probe=3bf5fd0cfd) | Mar 30, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [889f3e8521](https://linux-hardware.org/?probe=889f3e8521) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [492d575f31](https://linux-hardware.org/?probe=492d575f31) | Mar 30, 2023 |
| Lenovo        | ThinkPad T400 6475J92       | Notebook    | [1d3c812668](https://linux-hardware.org/?probe=1d3c812668) | Mar 30, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [53504486d2](https://linux-hardware.org/?probe=53504486d2) | Mar 29, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [029fa06a9a](https://linux-hardware.org/?probe=029fa06a9a) | Mar 29, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [1c80487906](https://linux-hardware.org/?probe=1c80487906) | Mar 29, 2023 |
| Dell          | Latitude 7430               | Notebook    | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| IP3 Tech      | IB8                         | Desktop     | [c12033f9e7](https://linux-hardware.org/?probe=c12033f9e7) | Mar 29, 2023 |
| Lenovo        | ThinkPad T460p 20HYSJKDO... | Notebook    | [1d24c2743f](https://linux-hardware.org/?probe=1d24c2743f) | Mar 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [a091222ad4](https://linux-hardware.org/?probe=a091222ad4) | Mar 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [40a3ae2220](https://linux-hardware.org/?probe=40a3ae2220) | Mar 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [a63f5d9198](https://linux-hardware.org/?probe=a63f5d9198) | Mar 28, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [f16690a3df](https://linux-hardware.org/?probe=f16690a3df) | Mar 28, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [8e7d5a0eb8](https://linux-hardware.org/?probe=8e7d5a0eb8) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2b09d1f769](https://linux-hardware.org/?probe=2b09d1f769) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a37020a71d](https://linux-hardware.org/?probe=a37020a71d) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [b8d58bafe3](https://linux-hardware.org/?probe=b8d58bafe3) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [68117fedfe](https://linux-hardware.org/?probe=68117fedfe) | Mar 28, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [03e9908048](https://linux-hardware.org/?probe=03e9908048) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [f511f8bcb1](https://linux-hardware.org/?probe=f511f8bcb1) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [face5f2ef3](https://linux-hardware.org/?probe=face5f2ef3) | Mar 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0b26a988f6](https://linux-hardware.org/?probe=0b26a988f6) | Mar 27, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [1dd1eab13e](https://linux-hardware.org/?probe=1dd1eab13e) | Mar 27, 2023 |
| HP            | 1998                        | Desktop     | [82adc9926e](https://linux-hardware.org/?probe=82adc9926e) | Mar 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6ddfac9d0](https://linux-hardware.org/?probe=d6ddfac9d0) | Mar 27, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [519fc70e27](https://linux-hardware.org/?probe=519fc70e27) | Mar 27, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [645c8515a1](https://linux-hardware.org/?probe=645c8515a1) | Mar 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [8a713b663d](https://linux-hardware.org/?probe=8a713b663d) | Mar 27, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [5dcd20300a](https://linux-hardware.org/?probe=5dcd20300a) | Mar 27, 2023 |
| Dell          | Latitude 7280               | Notebook    | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| ASUSTek       | M4A78-HTPC                  | Desktop     | [be398d5786](https://linux-hardware.org/?probe=be398d5786) | Mar 27, 2023 |
| HP            | 8704                        | Desktop     | [ab934a36cb](https://linux-hardware.org/?probe=ab934a36cb) | Mar 26, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [36c8e41310](https://linux-hardware.org/?probe=36c8e41310) | Mar 26, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [f1ed5dd70d](https://linux-hardware.org/?probe=f1ed5dd70d) | Mar 26, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [d18cb08996](https://linux-hardware.org/?probe=d18cb08996) | Mar 26, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [797053b2f7](https://linux-hardware.org/?probe=797053b2f7) | Mar 26, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bf08e5eecd](https://linux-hardware.org/?probe=bf08e5eecd) | Mar 26, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d79b6fc95c](https://linux-hardware.org/?probe=d79b6fc95c) | Mar 26, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [aeec5e2588](https://linux-hardware.org/?probe=aeec5e2588) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [22e7978cc8](https://linux-hardware.org/?probe=22e7978cc8) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [f889f2ddf5](https://linux-hardware.org/?probe=f889f2ddf5) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8fde777c54](https://linux-hardware.org/?probe=8fde777c54) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| LG Electro... | 16Z90Q-K.AA78A1             | Notebook    | [009542d035](https://linux-hardware.org/?probe=009542d035) | Mar 26, 2023 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [7e37be5b8c](https://linux-hardware.org/?probe=7e37be5b8c) | Mar 25, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [1ea635d2a0](https://linux-hardware.org/?probe=1ea635d2a0) | Mar 25, 2023 |
| HP            | Stream Notebook             | Notebook    | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| Dell          | Latitude E6420              | Notebook    | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [7ade2b1d1a](https://linux-hardware.org/?probe=7ade2b1d1a) | Mar 24, 2023 |
| Dell          | Precision 3510              | Notebook    | [2ea0671f5d](https://linux-hardware.org/?probe=2ea0671f5d) | Mar 24, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G513IE_G513IE     | Notebook    | [bc6baa37ef](https://linux-hardware.org/?probe=bc6baa37ef) | Mar 24, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [5bac43b2f0](https://linux-hardware.org/?probe=5bac43b2f0) | Mar 24, 2023 |
| Dell          | 0W13NR A08                  | Server      | [13bd99e4bc](https://linux-hardware.org/?probe=13bd99e4bc) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4731315325](https://linux-hardware.org/?probe=4731315325) | Mar 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [e4d1155524](https://linux-hardware.org/?probe=e4d1155524) | Mar 23, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| Notebook      | W510LU                      | Notebook    | [076125acc3](https://linux-hardware.org/?probe=076125acc3) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [70314c0c37](https://linux-hardware.org/?probe=70314c0c37) | Mar 23, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [10d078d9e2](https://linux-hardware.org/?probe=10d078d9e2) | Mar 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [8fc3d21cf8](https://linux-hardware.org/?probe=8fc3d21cf8) | Mar 22, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [9bfb72d26a](https://linux-hardware.org/?probe=9bfb72d26a) | Mar 21, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [d32441b2c3](https://linux-hardware.org/?probe=d32441b2c3) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [9c3ac61461](https://linux-hardware.org/?probe=9c3ac61461) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [10431e8027](https://linux-hardware.org/?probe=10431e8027) | Mar 20, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Acer          | Revo RL80                   | Desktop     | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| Fujitsu Si... | AMILO Xi 3670               | Notebook    | [bb018988d6](https://linux-hardware.org/?probe=bb018988d6) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [c9c86f1e79](https://linux-hardware.org/?probe=c9c86f1e79) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [436b9d15b0](https://linux-hardware.org/?probe=436b9d15b0) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [29a6e93a49](https://linux-hardware.org/?probe=29a6e93a49) | Mar 20, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [0d7cc03c37](https://linux-hardware.org/?probe=0d7cc03c37) | Mar 20, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [1840c57073](https://linux-hardware.org/?probe=1840c57073) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [8b7918d34b](https://linux-hardware.org/?probe=8b7918d34b) | Mar 20, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [9de8a9a50a](https://linux-hardware.org/?probe=9de8a9a50a) | Mar 20, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [cd5adbbfc0](https://linux-hardware.org/?probe=cd5adbbfc0) | Mar 19, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [87e3ca6a56](https://linux-hardware.org/?probe=87e3ca6a56) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [adc87fc9fa](https://linux-hardware.org/?probe=adc87fc9fa) | Mar 19, 2023 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [6681949ccc](https://linux-hardware.org/?probe=6681949ccc) | Mar 19, 2023 |
| Notebook      | N150ZU                      | Notebook    | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [63a8165aff](https://linux-hardware.org/?probe=63a8165aff) | Mar 19, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | Notebook    | [f60325ef42](https://linux-hardware.org/?probe=f60325ef42) | Mar 19, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [972b8e8c3c](https://linux-hardware.org/?probe=972b8e8c3c) | Mar 19, 2023 |
| HP            | 3397                        | Desktop     | [3f0b2c8e5b](https://linux-hardware.org/?probe=3f0b2c8e5b) | Mar 19, 2023 |
| Dell          | Inspiron 15 7510            | Notebook    | [f7aebbae36](https://linux-hardware.org/?probe=f7aebbae36) | Mar 18, 2023 |
| Unknown       | V00                         | Mini pc     | [6a0c74a051](https://linux-hardware.org/?probe=6a0c74a051) | Mar 18, 2023 |
| Unknown       | V00                         | Mini pc     | [d84f3134b9](https://linux-hardware.org/?probe=d84f3134b9) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [e10e576833](https://linux-hardware.org/?probe=e10e576833) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [a791424f94](https://linux-hardware.org/?probe=a791424f94) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [49df72f291](https://linux-hardware.org/?probe=49df72f291) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [1f939ee045](https://linux-hardware.org/?probe=1f939ee045) | Mar 18, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [06d89bd973](https://linux-hardware.org/?probe=06d89bd973) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [5e6e5276e3](https://linux-hardware.org/?probe=5e6e5276e3) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [9c677b7a7b](https://linux-hardware.org/?probe=9c677b7a7b) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [703cc66d3e](https://linux-hardware.org/?probe=703cc66d3e) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d58b6cfe61](https://linux-hardware.org/?probe=d58b6cfe61) | Mar 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [8c71ef60d0](https://linux-hardware.org/?probe=8c71ef60d0) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [def0907a23](https://linux-hardware.org/?probe=def0907a23) | Mar 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [7c909a0c5a](https://linux-hardware.org/?probe=7c909a0c5a) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [113406acd8](https://linux-hardware.org/?probe=113406acd8) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [e967c05c1e](https://linux-hardware.org/?probe=e967c05c1e) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [674c4a159e](https://linux-hardware.org/?probe=674c4a159e) | Mar 18, 2023 |
| Lenovo        | V580c 20160                 | Notebook    | [b7f2837ccd](https://linux-hardware.org/?probe=b7f2837ccd) | Mar 17, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [d9ac37a2da](https://linux-hardware.org/?probe=d9ac37a2da) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [63dba9dd56](https://linux-hardware.org/?probe=63dba9dd56) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [70a1f8041b](https://linux-hardware.org/?probe=70a1f8041b) | Mar 17, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [e4eb6f31af](https://linux-hardware.org/?probe=e4eb6f31af) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [761d6accb1](https://linux-hardware.org/?probe=761d6accb1) | Mar 16, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [2193d33376](https://linux-hardware.org/?probe=2193d33376) | Mar 16, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [9861151d08](https://linux-hardware.org/?probe=9861151d08) | Mar 16, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [907581c9cc](https://linux-hardware.org/?probe=907581c9cc) | Mar 16, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ccd15bcfae](https://linux-hardware.org/?probe=ccd15bcfae) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | Notebook    | [c6c5f88e4b](https://linux-hardware.org/?probe=c6c5f88e4b) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | Notebook    | [3c632e35c3](https://linux-hardware.org/?probe=3c632e35c3) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [dfe0b34f8b](https://linux-hardware.org/?probe=dfe0b34f8b) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [9f440a48b9](https://linux-hardware.org/?probe=9f440a48b9) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [0ee987e184](https://linux-hardware.org/?probe=0ee987e184) | Mar 15, 2023 |
| Timi          | RedmiBook 14                | Notebook    | [ff5feda02c](https://linux-hardware.org/?probe=ff5feda02c) | Mar 14, 2023 |
| ZOTAC         | ZBOXNANO-AQ01               | Mini pc     | [ad4d45d3fa](https://linux-hardware.org/?probe=ad4d45d3fa) | Mar 14, 2023 |
| ZOTAC         | ZBOXNANO-AQ01               | Mini pc     | [3d0b03a361](https://linux-hardware.org/?probe=3d0b03a361) | Mar 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | Notebook    | [0b9501dcc9](https://linux-hardware.org/?probe=0b9501dcc9) | Mar 14, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [e2f98f4fd2](https://linux-hardware.org/?probe=e2f98f4fd2) | Mar 14, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [9331f6026e](https://linux-hardware.org/?probe=9331f6026e) | Mar 14, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [7e90a81e0b](https://linux-hardware.org/?probe=7e90a81e0b) | Mar 14, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [d23ddde885](https://linux-hardware.org/?probe=d23ddde885) | Mar 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [1ad8d706ff](https://linux-hardware.org/?probe=1ad8d706ff) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [08924a17f9](https://linux-hardware.org/?probe=08924a17f9) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [ba5c82bc14](https://linux-hardware.org/?probe=ba5c82bc14) | Mar 14, 2023 |
| Google        | Teemo                       | Desktop     | [8082fe87d4](https://linux-hardware.org/?probe=8082fe87d4) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [b3bea1d3a0](https://linux-hardware.org/?probe=b3bea1d3a0) | Mar 14, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [2124288941](https://linux-hardware.org/?probe=2124288941) | Mar 13, 2023 |
| Dell          | 02M8NY A02                  | Desktop     | [b3c31072bb](https://linux-hardware.org/?probe=b3c31072bb) | Mar 13, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [12277151fa](https://linux-hardware.org/?probe=12277151fa) | Mar 13, 2023 |
| Acer          | EM61SM/EM61PM               | Desktop     | [9c746ee546](https://linux-hardware.org/?probe=9c746ee546) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f5215489c7](https://linux-hardware.org/?probe=f5215489c7) | Mar 13, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [8c344866da](https://linux-hardware.org/?probe=8c344866da) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [fdb6080ba5](https://linux-hardware.org/?probe=fdb6080ba5) | Mar 13, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [686fb235ce](https://linux-hardware.org/?probe=686fb235ce) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [12d8200114](https://linux-hardware.org/?probe=12d8200114) | Mar 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [ca456dde7d](https://linux-hardware.org/?probe=ca456dde7d) | Mar 13, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [9841e70d67](https://linux-hardware.org/?probe=9841e70d67) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [1b8b00dbc5](https://linux-hardware.org/?probe=1b8b00dbc5) | Mar 12, 2023 |
| OEGStone      | W240EU/W250EUQ/W270EUQ      | Notebook    | [45ea3c4094](https://linux-hardware.org/?probe=45ea3c4094) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [3b52326a3e](https://linux-hardware.org/?probe=3b52326a3e) | Mar 12, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [7ce318cc22](https://linux-hardware.org/?probe=7ce318cc22) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [2be528d875](https://linux-hardware.org/?probe=2be528d875) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | Notebook    | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [83dcd35e5f](https://linux-hardware.org/?probe=83dcd35e5f) | Mar 12, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [1ad7f4ea8e](https://linux-hardware.org/?probe=1ad7f4ea8e) | Mar 12, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [f6c972404c](https://linux-hardware.org/?probe=f6c972404c) | Mar 12, 2023 |
| Gigabyte      | H170M-D3H-CF                | Desktop     | [ec4064a64c](https://linux-hardware.org/?probe=ec4064a64c) | Mar 11, 2023 |
| Gigabyte      | H170M-D3H-CF                | Desktop     | [929aa1d9a8](https://linux-hardware.org/?probe=929aa1d9a8) | Mar 11, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [d841d9761a](https://linux-hardware.org/?probe=d841d9761a) | Mar 11, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [d822a4112f](https://linux-hardware.org/?probe=d822a4112f) | Mar 11, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b17210218f](https://linux-hardware.org/?probe=b17210218f) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [382901fcd7](https://linux-hardware.org/?probe=382901fcd7) | Mar 11, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [2f86f93df5](https://linux-hardware.org/?probe=2f86f93df5) | Mar 11, 2023 |
| ASUSTek       | P5E-V HDMI                  | Desktop     | [0f85d5d628](https://linux-hardware.org/?probe=0f85d5d628) | Mar 11, 2023 |
| Dell          | Latitude E6530              | Notebook    | [50a26c019d](https://linux-hardware.org/?probe=50a26c019d) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Google        | Ampton                      | Notebook    | [641b7d64fc](https://linux-hardware.org/?probe=641b7d64fc) | Mar 10, 2023 |
| Dell          | Inspiron 1750               | Notebook    | [354cdf8592](https://linux-hardware.org/?probe=354cdf8592) | Mar 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [d4cc4ff572](https://linux-hardware.org/?probe=d4cc4ff572) | Mar 10, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [9bcfd20d80](https://linux-hardware.org/?probe=9bcfd20d80) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [661125aac2](https://linux-hardware.org/?probe=661125aac2) | Mar 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [cd382356be](https://linux-hardware.org/?probe=cd382356be) | Mar 10, 2023 |
| Foxconn       | ETON                        | Desktop     | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [cd975ff510](https://linux-hardware.org/?probe=cd975ff510) | Mar 10, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [9c3d2e652a](https://linux-hardware.org/?probe=9c3d2e652a) | Mar 09, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [d35d11c64e](https://linux-hardware.org/?probe=d35d11c64e) | Mar 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [214efb1e94](https://linux-hardware.org/?probe=214efb1e94) | Mar 09, 2023 |
| Dell          | Latitude 7285               | Notebook    | [dfc4961010](https://linux-hardware.org/?probe=dfc4961010) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [026c39773a](https://linux-hardware.org/?probe=026c39773a) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | Notebook    | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d7129009b0](https://linux-hardware.org/?probe=d7129009b0) | Mar 09, 2023 |
| ASUSTek       | Maximus VI IMPACT           | Desktop     | [bca54b81fc](https://linux-hardware.org/?probe=bca54b81fc) | Mar 09, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [69f4444885](https://linux-hardware.org/?probe=69f4444885) | Mar 09, 2023 |
| AZW           | MINI S                      | Desktop     | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [fbb65f4a4e](https://linux-hardware.org/?probe=fbb65f4a4e) | Mar 09, 2023 |
| Google        | Cave                        | Notebook    | [37d6d413b7](https://linux-hardware.org/?probe=37d6d413b7) | Mar 09, 2023 |
| Supermicro    | X10DRi-LN4+                 | Desktop     | [4e805ce5a1](https://linux-hardware.org/?probe=4e805ce5a1) | Mar 08, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [705893644e](https://linux-hardware.org/?probe=705893644e) | Mar 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [69564be379](https://linux-hardware.org/?probe=69564be379) | Mar 08, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [519310d05f](https://linux-hardware.org/?probe=519310d05f) | Mar 08, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [46fa9eab7d](https://linux-hardware.org/?probe=46fa9eab7d) | Mar 08, 2023 |
| Entroware     | Apollo                      | Notebook    | [d1576010b3](https://linux-hardware.org/?probe=d1576010b3) | Mar 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [1851a5388e](https://linux-hardware.org/?probe=1851a5388e) | Mar 08, 2023 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [df3b5da4ce](https://linux-hardware.org/?probe=df3b5da4ce) | Mar 08, 2023 |
| Lenovo        | YB1-X91F                    | Tablet      | [5582ce4ba9](https://linux-hardware.org/?probe=5582ce4ba9) | Mar 08, 2023 |
| Foxconn       | ETON                        | Desktop     | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [87cbc99c85](https://linux-hardware.org/?probe=87cbc99c85) | Mar 08, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [30b6242c17](https://linux-hardware.org/?probe=30b6242c17) | Mar 07, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [54d0c16597](https://linux-hardware.org/?probe=54d0c16597) | Mar 07, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [30221f1500](https://linux-hardware.org/?probe=30221f1500) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [99d2997b98](https://linux-hardware.org/?probe=99d2997b98) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Dell          | 03TJ75 A00                  | Desktop     | [305d373dcd](https://linux-hardware.org/?probe=305d373dcd) | Mar 07, 2023 |
| Dell          | 0773VG A01                  | Desktop     | [d954bdd915](https://linux-hardware.org/?probe=d954bdd915) | Mar 07, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [ccd90a8ac4](https://linux-hardware.org/?probe=ccd90a8ac4) | Mar 07, 2023 |
| Dell          | 03TJ75 A00                  | Desktop     | [31c6d1fb3e](https://linux-hardware.org/?probe=31c6d1fb3e) | Mar 07, 2023 |
| Gigabyte      | Z690 GAMING X               | Desktop     | [b8dc3dd82b](https://linux-hardware.org/?probe=b8dc3dd82b) | Mar 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c5809ffd96](https://linux-hardware.org/?probe=c5809ffd96) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | Notebook    | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| Supermicro    | X10DRi-LN4+                 | Desktop     | [d445859477](https://linux-hardware.org/?probe=d445859477) | Mar 07, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [1209c224e1](https://linux-hardware.org/?probe=1209c224e1) | Mar 06, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8812bcfc2b](https://linux-hardware.org/?probe=8812bcfc2b) | Mar 06, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [f9f277d226](https://linux-hardware.org/?probe=f9f277d226) | Mar 06, 2023 |
| ASUSTek       | Z97-DELUXE/USB              | Desktop     | [46d851b146](https://linux-hardware.org/?probe=46d851b146) | Mar 06, 2023 |
| Acer          | Predator PH315-55           | Notebook    | [8465c0241c](https://linux-hardware.org/?probe=8465c0241c) | Mar 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [f6c973a00f](https://linux-hardware.org/?probe=f6c973a00f) | Mar 06, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [cc3e080ded](https://linux-hardware.org/?probe=cc3e080ded) | Mar 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [73eb839f5b](https://linux-hardware.org/?probe=73eb839f5b) | Mar 06, 2023 |
| Alienware     | Area-51m R2                 | Notebook    | [5726561947](https://linux-hardware.org/?probe=5726561947) | Mar 06, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [6a0179b36e](https://linux-hardware.org/?probe=6a0179b36e) | Mar 05, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | Notebook    | [f6863db7ca](https://linux-hardware.org/?probe=f6863db7ca) | Mar 05, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [c777bd0be1](https://linux-hardware.org/?probe=c777bd0be1) | Mar 05, 2023 |
| ASUSTek       | Maximus VI IMPACT           | Desktop     | [53d547f79c](https://linux-hardware.org/?probe=53d547f79c) | Mar 05, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [8bf9dd7b83](https://linux-hardware.org/?probe=8bf9dd7b83) | Mar 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [d1ada89fd6](https://linux-hardware.org/?probe=d1ada89fd6) | Mar 04, 2023 |
| MSI           | GS70 2QE                    | Notebook    | [3c8e62e276](https://linux-hardware.org/?probe=3c8e62e276) | Mar 04, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [3b1c7f5e26](https://linux-hardware.org/?probe=3b1c7f5e26) | Mar 04, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [b53bbf2061](https://linux-hardware.org/?probe=b53bbf2061) | Mar 04, 2023 |
| MSI           | GS70 2QE                    | Notebook    | [5c059744df](https://linux-hardware.org/?probe=5c059744df) | Mar 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | Notebook    | [89de1a18fe](https://linux-hardware.org/?probe=89de1a18fe) | Mar 04, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [621391a7e0](https://linux-hardware.org/?probe=621391a7e0) | Mar 04, 2023 |
| Lenovo        | ThinkPad T420 4236Q23       | Notebook    | [2aa5383e7e](https://linux-hardware.org/?probe=2aa5383e7e) | Mar 04, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3e484b7bac](https://linux-hardware.org/?probe=3e484b7bac) | Mar 04, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [48f407dbf7](https://linux-hardware.org/?probe=48f407dbf7) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c19189c929](https://linux-hardware.org/?probe=c19189c929) | Mar 04, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [6553b59bfe](https://linux-hardware.org/?probe=6553b59bfe) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9a42993edb](https://linux-hardware.org/?probe=9a42993edb) | Mar 03, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [11572533c2](https://linux-hardware.org/?probe=11572533c2) | Mar 03, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [3edae4d4f7](https://linux-hardware.org/?probe=3edae4d4f7) | Mar 03, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [3c74542aad](https://linux-hardware.org/?probe=3c74542aad) | Mar 02, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [7b7db7c319](https://linux-hardware.org/?probe=7b7db7c319) | Mar 02, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [5af7b05e04](https://linux-hardware.org/?probe=5af7b05e04) | Mar 02, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [2629f1915d](https://linux-hardware.org/?probe=2629f1915d) | Mar 02, 2023 |
| Dell          | Latitude E6410              | Notebook    | [3b99fd709e](https://linux-hardware.org/?probe=3b99fd709e) | Mar 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [83cbea47d9](https://linux-hardware.org/?probe=83cbea47d9) | Mar 02, 2023 |
| Acer          | Aspire A315-32              | Notebook    | [5203ce8a41](https://linux-hardware.org/?probe=5203ce8a41) | Mar 02, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [9036fa2ef1](https://linux-hardware.org/?probe=9036fa2ef1) | Mar 02, 2023 |
| HP            | 1998                        | Desktop     | [269c6134f1](https://linux-hardware.org/?probe=269c6134f1) | Mar 01, 2023 |
| Dell          | Latitude E7250              | Notebook    | [970d46cc83](https://linux-hardware.org/?probe=970d46cc83) | Mar 01, 2023 |
| AZW           | GTR V01                     | Mini pc     | [bfe7635484](https://linux-hardware.org/?probe=bfe7635484) | Mar 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [8c878d99a1](https://linux-hardware.org/?probe=8c878d99a1) | Mar 01, 2023 |
| Acer          | Predator PH517-61           | Notebook    | [2d1ec6c994](https://linux-hardware.org/?probe=2d1ec6c994) | Mar 01, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [eca37862f3](https://linux-hardware.org/?probe=eca37862f3) | Mar 01, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [784ef5ef12](https://linux-hardware.org/?probe=784ef5ef12) | Mar 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1025a9748f](https://linux-hardware.org/?probe=1025a9748f) | Mar 01, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [cd39348090](https://linux-hardware.org/?probe=cd39348090) | Mar 01, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [b1744130eb](https://linux-hardware.org/?probe=b1744130eb) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| Umbrel        | Home                        | Mini pc     | [f4afc80a6c](https://linux-hardware.org/?probe=f4afc80a6c) | Feb 28, 2023 |
| Alienware     | 15 R2                       | Notebook    | [f242145858](https://linux-hardware.org/?probe=f242145858) | Feb 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [bbc0d58ef1](https://linux-hardware.org/?probe=bbc0d58ef1) | Feb 28, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [48e150f274](https://linux-hardware.org/?probe=48e150f274) | Feb 28, 2023 |
| AZW           | Speed S                     | Desktop     | [e44ff0faf0](https://linux-hardware.org/?probe=e44ff0faf0) | Feb 28, 2023 |
| HP            | 83E2                        | Desktop     | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| Dell          | Latitude D630               | Notebook    | [5175558c99](https://linux-hardware.org/?probe=5175558c99) | Feb 28, 2023 |
| Dell          | Latitude E6440              | Notebook    | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| ASRock        | Z97 Pro3                    | Desktop     | [506d56faff](https://linux-hardware.org/?probe=506d56faff) | Feb 28, 2023 |
| AZW           | SEi                         | Notebook    | [6d0814dc9f](https://linux-hardware.org/?probe=6d0814dc9f) | Feb 28, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [b3c4d2985e](https://linux-hardware.org/?probe=b3c4d2985e) | Feb 27, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b5a08d19e9](https://linux-hardware.org/?probe=b5a08d19e9) | Feb 27, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| AZW           | SER                         | Mini pc     | [e086890e6a](https://linux-hardware.org/?probe=e086890e6a) | Feb 27, 2023 |
| ASRock        | Z97 Pro3                    | Desktop     | [626e67df35](https://linux-hardware.org/?probe=626e67df35) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [13edc00539](https://linux-hardware.org/?probe=13edc00539) | Feb 27, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [c2b3e01a45](https://linux-hardware.org/?probe=c2b3e01a45) | Feb 27, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [f15e5303f6](https://linux-hardware.org/?probe=f15e5303f6) | Feb 27, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [fe1c90a3aa](https://linux-hardware.org/?probe=fe1c90a3aa) | Feb 26, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [1213e49ca8](https://linux-hardware.org/?probe=1213e49ca8) | Feb 26, 2023 |
| HP            | 1998                        | Desktop     | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| Panasonic     | CF-31WEUEEBE                | Notebook    | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [15b2fe94ae](https://linux-hardware.org/?probe=15b2fe94ae) | Feb 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [87647b8c76](https://linux-hardware.org/?probe=87647b8c76) | Feb 26, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [d6805fb81b](https://linux-hardware.org/?probe=d6805fb81b) | Feb 25, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [64f304d41e](https://linux-hardware.org/?probe=64f304d41e) | Feb 25, 2023 |
| HP            | G62                         | Notebook    | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | Notebook    | [42b9d60137](https://linux-hardware.org/?probe=42b9d60137) | Feb 25, 2023 |
| Dell          | Latitude E6440              | Notebook    | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [4f9e90413b](https://linux-hardware.org/?probe=4f9e90413b) | Feb 25, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [87df24d8c2](https://linux-hardware.org/?probe=87df24d8c2) | Feb 25, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [d78e737aaf](https://linux-hardware.org/?probe=d78e737aaf) | Feb 25, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [ab8247e106](https://linux-hardware.org/?probe=ab8247e106) | Feb 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [af9891267d](https://linux-hardware.org/?probe=af9891267d) | Feb 24, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [cf2ff6c04b](https://linux-hardware.org/?probe=cf2ff6c04b) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [df96e94417](https://linux-hardware.org/?probe=df96e94417) | Feb 24, 2023 |
| Toshiba       | Satellite C850-1GF          | Notebook    | [f568855409](https://linux-hardware.org/?probe=f568855409) | Feb 24, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [123771dbb2](https://linux-hardware.org/?probe=123771dbb2) | Feb 24, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [7f29da1b6c](https://linux-hardware.org/?probe=7f29da1b6c) | Feb 24, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [e7edf0f7c3](https://linux-hardware.org/?probe=e7edf0f7c3) | Feb 23, 2023 |
| HP            | 1497                        | Desktop     | [478a5730f6](https://linux-hardware.org/?probe=478a5730f6) | Feb 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [7780f02f45](https://linux-hardware.org/?probe=7780f02f45) | Feb 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [8679998ec0](https://linux-hardware.org/?probe=8679998ec0) | Feb 23, 2023 |
| PC Special... | PD5x_7xPNP_PNN_PNT          | Notebook    | [cd71ec0b21](https://linux-hardware.org/?probe=cd71ec0b21) | Feb 23, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8f307a87e5](https://linux-hardware.org/?probe=8f307a87e5) | Feb 23, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [781c058256](https://linux-hardware.org/?probe=781c058256) | Feb 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [f92ac89547](https://linux-hardware.org/?probe=f92ac89547) | Feb 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [c570bb75bf](https://linux-hardware.org/?probe=c570bb75bf) | Feb 23, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [c3d9b18f7c](https://linux-hardware.org/?probe=c3d9b18f7c) | Feb 23, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [d19ee09dd3](https://linux-hardware.org/?probe=d19ee09dd3) | Feb 23, 2023 |
| Biostar       | B450MH                      | Desktop     | [7bd9274f23](https://linux-hardware.org/?probe=7bd9274f23) | Feb 23, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [2c74210fed](https://linux-hardware.org/?probe=2c74210fed) | Feb 23, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [d88dce11ff](https://linux-hardware.org/?probe=d88dce11ff) | Feb 22, 2023 |
| Lenovo        | ThinkPad X230 2325EJ0       | Notebook    | [3a2c22e22b](https://linux-hardware.org/?probe=3a2c22e22b) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 23551M9      | Notebook    | [91b6a109b4](https://linux-hardware.org/?probe=91b6a109b4) | Feb 22, 2023 |
| Lenovo        | ThinkPad X230 2325EJ0       | Notebook    | [06c8604990](https://linux-hardware.org/?probe=06c8604990) | Feb 22, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [3e5166108a](https://linux-hardware.org/?probe=3e5166108a) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4009d82fc8](https://linux-hardware.org/?probe=4009d82fc8) | Feb 22, 2023 |
| Google        | Droid                       | Notebook    | [e576f650b7](https://linux-hardware.org/?probe=e576f650b7) | Feb 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [67ba988b20](https://linux-hardware.org/?probe=67ba988b20) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [edbf6ce468](https://linux-hardware.org/?probe=edbf6ce468) | Feb 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [c51d4ef82a](https://linux-hardware.org/?probe=c51d4ef82a) | Feb 20, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [fb4420dbc4](https://linux-hardware.org/?probe=fb4420dbc4) | Feb 20, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [6799113f3e](https://linux-hardware.org/?probe=6799113f3e) | Feb 20, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [640cad4ab6](https://linux-hardware.org/?probe=640cad4ab6) | Feb 20, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0bc03f3b39](https://linux-hardware.org/?probe=0bc03f3b39) | Feb 20, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [11739ccfa1](https://linux-hardware.org/?probe=11739ccfa1) | Feb 20, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b184665592](https://linux-hardware.org/?probe=b184665592) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [542077cc42](https://linux-hardware.org/?probe=542077cc42) | Feb 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | Notebook    | [c79a8f48f9](https://linux-hardware.org/?probe=c79a8f48f9) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [2ccbfb422e](https://linux-hardware.org/?probe=2ccbfb422e) | Feb 20, 2023 |
| HUAWEI        | MateBook X                  | Notebook    | [cae415dee6](https://linux-hardware.org/?probe=cae415dee6) | Feb 20, 2023 |
| HUAWEI        | MateBook X                  | Notebook    | [6fed527c1b](https://linux-hardware.org/?probe=6fed527c1b) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [375a3684e2](https://linux-hardware.org/?probe=375a3684e2) | Feb 19, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [0bcbc517ca](https://linux-hardware.org/?probe=0bcbc517ca) | Feb 19, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [f347582e5c](https://linux-hardware.org/?probe=f347582e5c) | Feb 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [e7e9625ffc](https://linux-hardware.org/?probe=e7e9625ffc) | Feb 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f3552f5183](https://linux-hardware.org/?probe=f3552f5183) | Feb 19, 2023 |
| Lenovo        | ThinkPad E555 20DH000TUK    | Notebook    | [b2d5c9de8b](https://linux-hardware.org/?probe=b2d5c9de8b) | Feb 19, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [2c41f563a1](https://linux-hardware.org/?probe=2c41f563a1) | Feb 19, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [c32182253e](https://linux-hardware.org/?probe=c32182253e) | Feb 19, 2023 |
| MSI           | Z97M GAMING                 | Desktop     | [e983a3704e](https://linux-hardware.org/?probe=e983a3704e) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [03952a6c01](https://linux-hardware.org/?probe=03952a6c01) | Feb 18, 2023 |
| Intel         | JSL MRD                     | Desktop     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1133      | 14.46%  |
| Ubuntu 18.04       | 599       | 7.65%   |
| Ubuntu 22.04       | 409       | 5.22%   |
| Zorin 16           | 197       | 2.51%   |
| Debian 11          | 168       | 2.14%   |
| Arch Rolling       | 145       | 1.85%   |
| OpenMandriva 4.3   | 144       | 1.84%   |
| OpenMandriva 4.2   | 133       | 1.7%    |
| Pop!_OS 22.04      | 131       | 1.67%   |
| Manjaro            | 116       | 1.48%   |
| Linux Mint 20.3    | 115       | 1.47%   |
| Linux Mint 20.2    | 112       | 1.43%   |
| Linux Mint 19.3    | 112       | 1.43%   |
| KDE neon 20.04     | 112       | 1.43%   |
| Pop!_OS 20.04      | 108       | 1.38%   |
| Ubuntu 19.04       | 105       | 1.34%   |
| ArcoLinux Rolling  | 103       | 1.31%   |
| Ubuntu 20.10       | 100       | 1.28%   |
| Pop!_OS 21.04      | 100       | 1.28%   |
| Arch               | 97        | 1.24%   |
| Ubuntu 21.10       | 94        | 1.2%    |
| Zorin 15           | 93        | 1.19%   |
| Linux Mint 21.1    | 91        | 1.16%   |
| Ubuntu 19.10       | 89        | 1.14%   |
| Pop!_OS 20.10      | 86        | 1.1%    |
| Linux Mint 20.1    | 86        | 1.1%    |
| Ubuntu 21.04       | 81        | 1.03%   |
| OpenMandriva 23.01 | 79        | 1.01%   |
| Xubuntu 20.04      | 77        | 0.98%   |
| Fedora 36          | 68        | 0.87%   |
| Linux Mint 20      | 67        | 0.86%   |
| Fedora 37          | 67        | 0.86%   |
| OpenMandriva 23.03 | 61        | 0.78%   |
| Fedora 34          | 60        | 0.77%   |
| Kubuntu 20.04      | 59        | 0.75%   |
| Pop!_OS 21.10      | 57        | 0.73%   |
| Fedora 35          | 57        | 0.73%   |
| Ubuntu 18.10       | 56        | 0.71%   |
| Linux Mint 21      | 51        | 0.65%   |
| Ubuntu 22.10       | 50        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2653      | 35.6%   |
| Linux Mint    | 662       | 8.88%   |
| Pop!_OS       | 458       | 6.15%   |
| OpenMandriva  | 454       | 6.09%   |
| Fedora        | 405       | 5.43%   |
| Zorin         | 300       | 4.03%   |
| Debian        | 271       | 3.64%   |
| Arch          | 240       | 3.22%   |
| Manjaro       | 236       | 3.17%   |
| Kubuntu       | 164       | 2.2%    |
| KDE neon      | 154       | 2.07%   |
| Xubuntu       | 147       | 1.97%   |
| ArcoLinux     | 107       | 1.44%   |
| SteamOS       | 88        | 1.18%   |
| ROSA          | 79        | 1.06%   |
| Elementary    | 74        | 0.99%   |
| Gentoo        | 72        | 0.97%   |
| openSUSE      | 71        | 0.95%   |
| Ubuntu MATE   | 63        | 0.85%   |
| Endless       | 54        | 0.72%   |
| Lubuntu       | 53        | 0.71%   |
| Ubuntu Unity  | 49        | 0.66%   |
| Kali          | 48        | 0.64%   |
| Clear Linux   | 46        | 0.62%   |
| BlackPanther  | 42        | 0.56%   |
| LMDE          | 28        | 0.38%   |
| CentOS        | 27        | 0.36%   |
| Ubuntu Budgie | 24        | 0.32%   |
| MX            | 24        | 0.32%   |
| EndeavourOS   | 24        | 0.32%   |
| Nobara        | 23        | 0.31%   |
| Garuda Linux  | 23        | 0.31%   |
| Raspbian      | 22        | 0.3%    |
| RHEL          | 17        | 0.23%   |
| Peppermint    | 17        | 0.23%   |
| Parrot        | 16        | 0.21%   |
| Slackware     | 12        | 0.16%   |
| NixOS         | 12        | 0.16%   |
| Alpine        | 9         | 0.12%   |
| Reborn OS     | 7         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 152       | 1.74%   |
| 5.16.7-desktop-1omv4003  | 136       | 1.56%   |
| 5.10.14-desktop-1omv4002 | 130       | 1.49%   |
| 5.4.0-48-generic         | 81        | 0.93%   |
| 5.15.0-56-generic        | 81        | 0.93%   |
| 5.4.0-52-generic         | 76        | 0.87%   |
| 5.4.0-29-generic         | 73        | 0.84%   |
| 6.1.1-desktop-1omv2290   | 71        | 0.81%   |
| 5.4.0-26-generic         | 70        | 0.8%    |
| 5.3.0-28-generic         | 65        | 0.74%   |
| 5.15.0-52-generic        | 65        | 0.74%   |
| 5.15.0-46-generic        | 64        | 0.73%   |
| 5.15.0-58-generic        | 63        | 0.72%   |
| 6.2.6-desktop-1omv2390   | 61        | 0.7%    |
| 5.3.0-40-generic         | 60        | 0.69%   |
| 5.4.0-40-generic         | 53        | 0.61%   |
| 5.4.0-58-generic         | 51        | 0.58%   |
| 5.4.0-37-generic         | 51        | 0.58%   |
| 5.11.0-27-generic        | 51        | 0.58%   |
| 5.4.0-65-generic         | 45        | 0.52%   |
| 5.4.0-33-generic         | 45        | 0.52%   |
| 5.11.0-38-generic        | 45        | 0.52%   |
| 5.0.0-32-generic         | 45        | 0.52%   |
| 5.4.0-91-generic         | 43        | 0.49%   |
| 5.19.0-35-generic        | 43        | 0.49%   |
| 5.13.0-7614-generic      | 43        | 0.49%   |
| 5.11.0-25-generic        | 43        | 0.49%   |
| 5.4.0-7634-generic       | 41        | 0.47%   |
| 5.4.0-54-generic         | 41        | 0.47%   |
| 5.3.0-46-generic         | 41        | 0.47%   |
| 5.4.0-74-generic         | 40        | 0.46%   |
| 5.4.0-66-generic         | 40        | 0.46%   |
| 5.8.0-7630-generic       | 39        | 0.45%   |
| 5.8.0-43-generic         | 39        | 0.45%   |
| 5.11.0-7620-generic      | 39        | 0.45%   |
| 5.0.0-37-generic         | 39        | 0.45%   |
| 5.15.0-48-generic        | 38        | 0.44%   |
| 5.13.0-28-generic        | 38        | 0.44%   |
| 5.11.0-40-generic        | 38        | 0.44%   |
| 5.3.0-42-generic         | 37        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1506      | 18.54%  |
| 5.15.0  | 701       | 8.63%   |
| 5.11.0  | 455       | 5.6%    |
| 5.13.0  | 451       | 5.55%   |
| 5.8.0   | 449       | 5.53%   |
| 4.15.0  | 417       | 5.13%   |
| 5.3.0   | 374       | 4.6%    |
| 5.0.0   | 244       | 3%      |
| 5.19.0  | 237       | 2.92%   |
| 5.10.0  | 196       | 2.41%   |
| 4.18.0  | 181       | 2.23%   |
| 5.16.7  | 137       | 1.69%   |
| 5.10.14 | 130       | 1.6%    |
| 6.2.6   | 91        | 1.12%   |
| 6.1.1   | 76        | 0.94%   |
| 4.19.0  | 57        | 0.7%    |
| 6.2.0   | 39        | 0.48%   |
| 5.17.5  | 36        | 0.44%   |
| 5.14.0  | 34        | 0.42%   |
| 4.18.16 | 32        | 0.39%   |
| 6.0.0   | 30        | 0.37%   |
| 6.1.0   | 28        | 0.34%   |
| 6.0.6   | 26        | 0.32%   |
| 6.0.12  | 26        | 0.32%   |
| 4.9.60  | 26        | 0.32%   |
| 5.9.16  | 25        | 0.31%   |
| 5.18.0  | 22        | 0.27%   |
| 4.4.0   | 21        | 0.26%   |
| 5.17.1  | 19        | 0.23%   |
| 5.16.13 | 19        | 0.23%   |
| 5.18.12 | 18        | 0.22%   |
| 5.16.11 | 18        | 0.22%   |
| 5.15.12 | 17        | 0.21%   |
| 5.13.12 | 17        | 0.21%   |
| 5.7.0   | 16        | 0.2%    |
| 5.6.14  | 16        | 0.2%    |
| 5.16.0  | 16        | 0.2%    |
| 4.9.20  | 16        | 0.2%    |
| 6.1.9   | 15        | 0.18%   |
| 5.17.0  | 15        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1597      | 19.94%  |
| 5.15    | 893       | 11.15%  |
| 5.13    | 537       | 6.7%    |
| 5.8     | 536       | 6.69%   |
| 5.11    | 513       | 6.4%    |
| 5.10    | 460       | 5.74%   |
| 5.3     | 424       | 5.29%   |
| 4.15    | 419       | 5.23%   |
| 5.19    | 327       | 4.08%   |
| 5.0     | 254       | 3.17%   |
| 5.16    | 248       | 3.1%    |
| 6.1     | 222       | 2.77%   |
| 6.2     | 220       | 2.75%   |
| 4.18    | 216       | 2.7%    |
| 6.0     | 152       | 1.9%    |
| 5.17    | 107       | 1.34%   |
| 5.14    | 103       | 1.29%   |
| 5.9     | 95        | 1.19%   |
| 5.18    | 93        | 1.16%   |
| 4.19    | 90        | 1.12%   |
| 5.12    | 88        | 1.1%    |
| 5.6     | 77        | 0.96%   |
| 4.9     | 73        | 0.91%   |
| 5.7     | 68        | 0.85%   |
| 5.5     | 42        | 0.52%   |
| 6.3     | 36        | 0.45%   |
| 4.4     | 25        | 0.31%   |
| 5.2     | 23        | 0.29%   |
| 5.1     | 16        | 0.2%    |
| 4.14    | 10        | 0.12%   |
| 4.1     | 9         | 0.11%   |
| 3.10    | 9         | 0.11%   |
| 4.20    | 5         | 0.06%   |
| 4.13    | 5         | 0.06%   |
| 3.13    | 4         | 0.05%   |
| 4.16    | 3         | 0.04%   |
| 4.12    | 3         | 0.04%   |
| 4.8     | 2         | 0.02%   |
| 6.4     | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6883      | 96.24%  |
| i686    | 176       | 2.46%   |
| aarch64 | 66        | 0.92%   |
| armv7l  | 26        | 0.36%   |
| armv6l  | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 3398      | 45.29%  |
| KDE5             | 1223      | 16.3%   |
| Unknown          | 942       | 12.56%  |
| X-Cinnamon       | 533       | 7.1%    |
| XFCE             | 499       | 6.65%   |
| MATE             | 189       | 2.52%   |
| KDE              | 177       | 2.36%   |
| Cinnamon         | 88        | 1.17%   |
| Pantheon         | 70        | 0.93%   |
| Unity            | 51        | 0.68%   |
| LXQt             | 50        | 0.67%   |
| LXDE             | 49        | 0.65%   |
| KDE4             | 36        | 0.48%   |
| Budgie           | 33        | 0.44%   |
| i3               | 31        | 0.41%   |
| GNOME Flashback  | 26        | 0.35%   |
| Deepin           | 14        | 0.19%   |
| sway             | 13        | 0.17%   |
| Openbox          | 11        | 0.15%   |
| GNOME Classic    | 10        | 0.13%   |
| qtile            | 8         | 0.11%   |
| awesome          | 8         | 0.11%   |
| lightdm-xsession | 7         | 0.09%   |
| xmonad           | 5         | 0.07%   |
| bspwm            | 5         | 0.07%   |
| trinity          | 3         | 0.04%   |
| Enlightenment    | 3         | 0.04%   |
| DWM              | 3         | 0.04%   |
| mwm              | 2         | 0.03%   |
| i3-with-shmlog   | 2         | 0.03%   |
| Hyprland         | 2         | 0.03%   |
| Cutefish         | 2         | 0.03%   |
| chadwm           | 2         | 0.03%   |
| xubuntu          | 1         | 0.01%   |
| WindowMaker      | 1         | 0.01%   |
| Phosh:GNOME      | 1         | 0.01%   |
| LeftWM           | 1         | 0.01%   |
| icewm            | 1         | 0.01%   |
| GNUstep          | 1         | 0.01%   |
| BunsenLabs       | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5702      | 77.59%  |
| Wayland | 1004      | 13.66%  |
| Unknown | 463       | 6.3%    |
| Tty     | 179       | 2.44%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4121      | 55.22%  |
| SDDM    | 1010      | 13.53%  |
| GDM3    | 729       | 9.77%   |
| GDM     | 721       | 9.66%   |
| LightDM | 608       | 8.15%   |
| TDM     | 197       | 2.64%   |
| KDM     | 35        | 0.47%   |
| XDM     | 15        | 0.2%    |
| LXDM    | 9         | 0.12%   |
| SLiM    | 6         | 0.08%   |
| Ly      | 6         | 0.08%   |
| GREETD  | 2         | 0.03%   |
| XINIT   | 1         | 0.01%   |
| NODM    | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| CDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| en_GB          | 5295      | 72.19%  |
| en_US          | 899       | 12.26%  |
| Unknown        | 815       | 11.11%  |
| C              | 112       | 1.53%   |
| pl_PL          | 57        | 0.78%   |
| POSIX          | 14        | 0.19%   |
| ru_RU          | 13        | 0.18%   |
| de_DE          | 12        | 0.16%   |
| it_IT          | 10        | 0.14%   |
| fr_FR          | 10        | 0.14%   |
| en_IE          | 10        | 0.14%   |
| en_CA          | 10        | 0.14%   |
| en_AU          | 7         | 0.1%    |
| ro_RO          | 6         | 0.08%   |
| en_IN          | 6         | 0.08%   |
| cs_CZ          | 6         | 0.08%   |
| hu_HU          | 5         | 0.07%   |
| es_ES          | 5         | 0.07%   |
| C.UTF8         | 5         | 0.07%   |
| pt_PT          | 4         | 0.05%   |
| zh_CN          | 3         | 0.04%   |
| sk_SK          | 3         | 0.04%   |
| pt_BR          | 3         | 0.04%   |
| uk_UA          | 2         | 0.03%   |
| nl_NL          | 2         | 0.03%   |
| lt_LT          | 2         | 0.03%   |
| en_GB.iso88591 | 2         | 0.03%   |
| da_DK          | 2         | 0.03%   |
| bg_BG          | 2         | 0.03%   |
| wbp_AU         | 1         | 0.01%   |
| tr_TR          | 1         | 0.01%   |
| ru_UA          | 1         | 0.01%   |
| nl_BE          | 1         | 0.01%   |
| fi_FI          | 1         | 0.01%   |
| et_EE          | 1         | 0.01%   |
| en_ZA          | 1         | 0.01%   |
| en_US.utf-8    | 1         | 0.01%   |
| en_IL          | 1         | 0.01%   |
| en_HK          | 1         | 0.01%   |
| en_GG          | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3842      | 52.57%  |
| EFI  | 3467      | 47.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5695      | 77.53%  |
| Btrfs    | 640       | 8.71%   |
| Overlay  | 500       | 6.81%   |
| Unknown  | 233       | 3.17%   |
| Xfs      | 105       | 1.43%   |
| Tmpfs    | 65        | 0.88%   |
| Zfs      | 62        | 0.84%   |
| Ext2     | 21        | 0.29%   |
| Ext3     | 11        | 0.15%   |
| F2fs     | 9         | 0.12%   |
| Aufs     | 2         | 0.03%   |
| Reiserfs | 1         | 0.01%   |
| Lvm      | 1         | 0.01%   |
| ExX4     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4269      | 58.14%  |
| GPT     | 2414      | 32.87%  |
| MBR     | 660       | 8.99%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6210      | 84.98%  |
| Yes       | 1098      | 15.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5305      | 72.89%  |
| Yes       | 1973      | 27.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1110      | 15.54%  |
| ASUSTek Computer        | 1040      | 14.56%  |
| Hewlett-Packard         | 901       | 12.61%  |
| Lenovo                  | 884       | 12.37%  |
| Gigabyte Technology     | 514       | 7.19%   |
| MSI                     | 399       | 5.58%   |
| Acer                    | 339       | 4.74%   |
| ASRock                  | 215       | 3.01%   |
| Apple                   | 210       | 2.94%   |
| Toshiba                 | 167       | 2.34%   |
| Intel                   | 128       | 1.79%   |
| Samsung Electronics     | 85        | 1.19%   |
| Valve                   | 80        | 1.12%   |
| Raspberry Pi Foundation | 74        | 1.04%   |
| Sony                    | 60        | 0.84%   |
| Unknown                 | 55        | 0.77%   |
| Fujitsu                 | 45        | 0.63%   |
| PC Specialist           | 44        | 0.62%   |
| Microsoft               | 44        | 0.62%   |
| HUAWEI                  | 44        | 0.62%   |
| Google                  | 43        | 0.6%    |
| Packard Bell            | 35        | 0.49%   |
| Foxconn                 | 33        | 0.46%   |
| Notebook                | 30        | 0.42%   |
| Alienware               | 26        | 0.36%   |
| AZW                     | 24        | 0.34%   |
| Pegatron                | 22        | 0.31%   |
| Fujitsu Siemens         | 21        | 0.29%   |
| Star Labs               | 19        | 0.27%   |
| Razer                   | 19        | 0.27%   |
| Medion                  | 18        | 0.25%   |
| Biostar                 | 18        | 0.25%   |
| GEO                     | 17        | 0.24%   |
| Linx                    | 15        | 0.21%   |
| Entroware               | 15        | 0.21%   |
| Dixonsxp                | 14        | 0.2%    |
| AMI                     | 14        | 0.2%    |
| TUXEDO                  | 13        | 0.18%   |
| Supermicro              | 11        | 0.15%   |
| Clevo                   | 11        | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Valve Jupiter                      | 80        | 1.12%   |
| Unknown                            | 78        | 1.09%   |
| ASUS All Series                    | 74        | 1.04%   |
| Dell OptiPlex 7010                 | 30        | 0.42%   |
| MSI MS-7C02                        | 29        | 0.41%   |
| HP Pavilion g6                     | 24        | 0.34%   |
| RPi Raspberry Pi                   | 23        | 0.32%   |
| MSI MS-7C37                        | 21        | 0.29%   |
| Dell OptiPlex 755                  | 21        | 0.29%   |
| HP Notebook                        | 20        | 0.28%   |
| ASUS TUF Gaming X570-PLUS          | 20        | 0.28%   |
| ASUS M5A78L-M/USB3                 | 20        | 0.28%   |
| HP Pavilion 15                     | 19        | 0.27%   |
| Dell OptiPlex 780                  | 19        | 0.27%   |
| ASUS ROG STRIX B450-F GAMING       | 19        | 0.27%   |
| Dell OptiPlex 790                  | 17        | 0.24%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 16        | 0.22%   |
| Dell XPS 15 7590                   | 16        | 0.22%   |
| HP Pavilion Notebook               | 15        | 0.21%   |
| Dell Inspiron 1545                 | 15        | 0.21%   |
| Gigabyte 970A-DS3P                 | 14        | 0.2%    |
| Dell XPS 15 9560                   | 14        | 0.2%    |
| Gigabyte X570 AORUS ELITE          | 13        | 0.18%   |
| Dell XPS 13 9380                   | 13        | 0.18%   |
| Dell XPS 13 9370                   | 13        | 0.18%   |
| ASUS PRIME A320M-K                 | 13        | 0.18%   |
| MSI MS-7C91                        | 12        | 0.17%   |
| Gigabyte GA-78LMT-USB3             | 12        | 0.17%   |
| Dell XPS 15 9570                   | 12        | 0.17%   |
| Dell XPS 13 9360                   | 12        | 0.17%   |
| Dell OptiPlex 3020                 | 12        | 0.17%   |
| Dell Latitude E6400                | 12        | 0.17%   |
| Toshiba Satellite C660             | 11        | 0.15%   |
| Microsoft Surface Pro 4            | 11        | 0.15%   |
| Lenovo V145-15AST 81MT             | 11        | 0.15%   |
| HP ProLiant MicroServer            | 11        | 0.15%   |
| Dell XPS 13 7390                   | 11        | 0.15%   |
| Dell Latitude E6410                | 11        | 0.15%   |
| ASUS ROG STRIX B550-F GAMING       | 11        | 0.15%   |
| MSI MS-7B85                        | 10        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 409       | 5.72%   |
| Dell Latitude          | 259       | 3.62%   |
| Acer Aspire            | 244       | 3.41%   |
| Dell Inspiron          | 232       | 3.25%   |
| Dell OptiPlex          | 197       | 2.76%   |
| Dell XPS               | 184       | 2.58%   |
| ASUS ROG               | 160       | 2.24%   |
| HP Pavilion            | 153       | 2.14%   |
| Toshiba Satellite      | 145       | 2.03%   |
| Lenovo IdeaPad         | 136       | 1.9%    |
| ASUS PRIME             | 125       | 1.75%   |
| HP EliteBook           | 107       | 1.5%    |
| Dell Precision         | 100       | 1.4%    |
| HP Compaq              | 95        | 1.33%   |
| Valve Jupiter          | 80        | 1.12%   |
| Unknown                | 78        | 1.09%   |
| RPi Raspberry          | 74        | 1.04%   |
| ASUS All               | 74        | 1.04%   |
| Lenovo ThinkCentre     | 69        | 0.97%   |
| HP Laptop              | 62        | 0.87%   |
| HP ProBook             | 61        | 0.85%   |
| ASUS TUF               | 59        | 0.83%   |
| HP ENVY                | 54        | 0.76%   |
| ASUS VivoBook          | 54        | 0.76%   |
| Lenovo Yoga            | 48        | 0.67%   |
| Dell Vostro            | 46        | 0.64%   |
| Microsoft Surface      | 44        | 0.62%   |
| HP ProLiant            | 35        | 0.49%   |
| Gigabyte X570          | 35        | 0.49%   |
| HP EliteDesk           | 30        | 0.42%   |
| ASUS M5A78L-M          | 30        | 0.42%   |
| MSI MS-7C02            | 29        | 0.41%   |
| HP Stream              | 28        | 0.39%   |
| ASUS ZenBook           | 28        | 0.39%   |
| Gigabyte GA-78LMT-USB3 | 27        | 0.38%   |
| HP Spectre             | 26        | 0.36%   |
| Lenovo Legion          | 25        | 0.35%   |
| Acer Swift             | 25        | 0.35%   |
| MSI MS-7C37            | 21        | 0.29%   |
| Lenovo ThinkBook       | 21        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 686       | 9.6%    |
| 2019    | 623       | 8.72%   |
| 2020    | 584       | 8.17%   |
| 2012    | 562       | 7.87%   |
| 2013    | 505       | 7.07%   |
| 2017    | 479       | 6.7%    |
| 2011    | 475       | 6.65%   |
| 2014    | 442       | 6.19%   |
| 2021    | 415       | 5.81%   |
| 2015    | 389       | 5.44%   |
| 2010    | 381       | 5.33%   |
| 2016    | 362       | 5.07%   |
| 2009    | 290       | 4.06%   |
| 2008    | 278       | 3.89%   |
| 2022    | 265       | 3.71%   |
| 2007    | 191       | 2.67%   |
| 2006    | 83        | 1.16%   |
| Unknown | 73        | 1.02%   |
| 2005    | 26        | 0.36%   |
| 2023    | 24        | 0.34%   |
| 2004    | 6         | 0.08%   |
| 2003    | 3         | 0.04%   |
| 2002    | 3         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3631      | 50.82%  |
| Desktop        | 2854      | 39.94%  |
| Convertible    | 153       | 2.14%   |
| Mini pc        | 143       | 2%      |
| All in one     | 121       | 1.69%   |
| Tablet         | 95        | 1.33%   |
| System on chip | 85        | 1.19%   |
| Server         | 58        | 0.81%   |
| Phone          | 4         | 0.06%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6636      | 92.14%  |
| Enabled  | 566       | 7.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7081      | 99.1%   |
| Yes  | 64        | 0.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1616      | 22.21%  |
| 16.01-24.0      | 1560      | 21.44%  |
| 8.01-16.0       | 1261      | 17.33%  |
| 3.01-4.0        | 1241      | 17.05%  |
| 32.01-64.0      | 772       | 10.61%  |
| 1.01-2.0        | 312       | 4.29%   |
| 64.01-256.0     | 203       | 2.79%   |
| 2.01-3.0        | 128       | 1.76%   |
| 24.01-32.0      | 109       | 1.5%    |
| 0.51-1.0        | 59        | 0.81%   |
| More than 256.0 | 11        | 0.15%   |
| 0.01-0.5        | 5         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 2949      | 36.8%   |
| 2.01-3.0    | 1983      | 24.74%  |
| 4.01-8.0    | 1089      | 13.59%  |
| 3.01-4.0    | 977       | 12.19%  |
| 0.51-1.0    | 502       | 6.26%   |
| 8.01-16.0   | 311       | 3.88%   |
| 0.01-0.5    | 110       | 1.37%   |
| 16.01-24.0  | 47        | 0.59%   |
| 24.01-32.0  | 20        | 0.25%   |
| 32.01-64.0  | 18        | 0.22%   |
| 64.01-256.0 | 4         | 0.05%   |
| Unknown     | 4         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4170      | 56.35%  |
| 2       | 1845      | 24.93%  |
| 3       | 601       | 8.12%   |
| 4       | 330       | 4.46%   |
| 5       | 182       | 2.46%   |
| 6       | 93        | 1.26%   |
| 0       | 76        | 1.03%   |
| 7       | 40        | 0.54%   |
| 8       | 16        | 0.22%   |
| 9       | 14        | 0.19%   |
| Unknown | 8         | 0.11%   |
| 11      | 7         | 0.09%   |
| 10      | 6         | 0.08%   |
| 12      | 5         | 0.07%   |
| 13      | 3         | 0.04%   |
| 25      | 1         | 0.01%   |
| 21      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4318      | 59.81%  |
| Yes       | 2901      | 40.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6009      | 83.95%  |
| No        | 1149      | 16.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5456      | 75.67%  |
| No        | 1754      | 24.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4207      | 58.12%  |
| No        | 3032      | 41.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 7145      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| London              | 465       | 5.89%   |
| Manchester          | 168       | 2.13%   |
| Birmingham          | 131       | 1.66%   |
| Bristol             | 127       | 1.61%   |
| Glasgow             | 113       | 1.43%   |
| Edinburgh           | 109       | 1.38%   |
| Nottingham          | 99        | 1.25%   |
| Sheffield           | 98        | 1.24%   |
| Liverpool           | 93        | 1.18%   |
| Leeds               | 92        | 1.17%   |
| Reading             | 72        | 0.91%   |
| Islington           | 70        | 0.89%   |
| Norwich             | 63        | 0.8%    |
| Cambridge           | 63        | 0.8%    |
| Southampton         | 53        | 0.67%   |
| Milton Keynes       | 51        | 0.65%   |
| Croydon             | 51        | 0.65%   |
| Derby               | 50        | 0.63%   |
| Leicester           | 49        | 0.62%   |
| Coventry            | 48        | 0.61%   |
| Bradford            | 45        | 0.57%   |
| Cardiff             | 44        | 0.56%   |
| Newcastle upon Tyne | 43        | 0.54%   |
| York                | 42        | 0.53%   |
| Oxford              | 41        | 0.52%   |
| Hackney             | 40        | 0.51%   |
| Aberdeen            | 40        | 0.51%   |
| Gloucester          | 39        | 0.49%   |
| Swindon             | 38        | 0.48%   |
| Brighton            | 37        | 0.47%   |
| Wolverhampton       | 36        | 0.46%   |
| Plymouth            | 36        | 0.46%   |
| Bolton              | 36        | 0.46%   |
| Wigan               | 34        | 0.43%   |
| Sunderland          | 33        | 0.42%   |
| Walsall             | 32        | 0.41%   |
| Kensington          | 31        | 0.39%   |
| Harrow              | 31        | 0.39%   |
| Stoke-on-Trent      | 30        | 0.38%   |
| Clapham             | 30        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1646      | 2582   | 15.22%  |
| Seagate                     | 1613      | 2690   | 14.91%  |
| WDC                         | 1492      | 2464   | 13.79%  |
| Toshiba                     | 724       | 999    | 6.69%   |
| Sandisk                     | 643       | 863    | 5.94%   |
| Unknown                     | 592       | 805    | 5.47%   |
| Crucial                     | 570       | 817    | 5.27%   |
| Kingston                    | 454       | 617    | 4.2%    |
| Hitachi                     | 397       | 550    | 3.67%   |
| Intel                       | 227       | 305    | 2.1%    |
| SK hynix                    | 225       | 266    | 2.08%   |
| HGST                        | 165       | 241    | 1.53%   |
| Phison                      | 156       | 208    | 1.44%   |
| Micron Technology           | 119       | 141    | 1.1%    |
| China                       | 111       | 152    | 1.03%   |
| Apple                       | 110       | 151    | 1.02%   |
| A-DATA Technology           | 98        | 128    | 0.91%   |
| KIOXIA                      | 69        | 91     | 0.64%   |
| OCZ                         | 65        | 74     | 0.6%    |
| PNY                         | 63        | 78     | 0.58%   |
| Phison Electronics          | 61        | 88     | 0.56%   |
| Maxtor                      | 57        | 86     | 0.53%   |
| LITEON                      | 57        | 69     | 0.53%   |
| Silicon Motion              | 55        | 69     | 0.51%   |
| Transcend                   | 51        | 61     | 0.47%   |
| Corsair                     | 50        | 69     | 0.46%   |
| Micron/Crucial Technology   | 48        | 62     | 0.44%   |
| Unknown                     | 45        | 57     | 0.42%   |
| Fujitsu                     | 44        | 61     | 0.41%   |
| LITEONIT                    | 32        | 40     | 0.3%    |
| Integral                    | 30        | 35     | 0.28%   |
| JMicron Technology          | 28        | 40     | 0.26%   |
| Netac                       | 26        | 35     | 0.24%   |
| Kingston Technology Company | 26        | 27     | 0.24%   |
| SABRENT                     | 24        | 28     | 0.22%   |
| Patriot                     | 24        | 37     | 0.22%   |
| ASMT                        | 24        | 55     | 0.22%   |
| Gigabyte Technology         | 23        | 30     | 0.21%   |
| SPCC                        | 19        | 32     | 0.18%   |
| Drevo                       | 19        | 31     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 122       | 1%      |
| Seagate ST3500312CS 500GB                           | 91        | 0.75%   |
| Samsung SSD 850 EVO 250GB                           | 90        | 0.74%   |
| Kingston SA400S37240G 240GB SSD                     | 85        | 0.7%    |
| Samsung SSD 850 EVO 500GB                           | 79        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB                      | 78        | 0.64%   |
| Crucial CT1000MX500SSD1 1TB                         | 78        | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 75        | 0.62%   |
| Unknown MMC Card  64GB                              | 74        | 0.61%   |
| Crucial CT500MX500SSD1 500GB                        | 72        | 0.59%   |
| Seagate ST2000DM008-2FR102 2TB                      | 71        | 0.58%   |
| Samsung SSD 860 EVO 500GB                           | 67        | 0.55%   |
| Kingston SA400S37120G 120GB SSD                     | 66        | 0.54%   |
| Seagate ST1000LM035-1RK172 1TB                      | 65        | 0.53%   |
| Samsung NVMe SSD Drive 500GB                        | 63        | 0.52%   |
| Seagate ST500DM002-1BD142 500GB                     | 61        | 0.5%    |
| Unknown MMC Card  128GB                             | 59        | 0.48%   |
| Toshiba MQ01ABD100 1TB                              | 59        | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB                        | 59        | 0.48%   |
| Samsung SSD 860 EVO 1TB                             | 58        | 0.48%   |
| Samsung NVMe SSD Drive 512GB                        | 54        | 0.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 54        | 0.44%   |
| Samsung NVMe SSD Drive 1TB                          | 50        | 0.41%   |
| Crucial CT240BX500SSD1 240GB                        | 50        | 0.41%   |
| Samsung NVMe SSD Drive 256GB                        | 49        | 0.4%    |
| Unknown                                             | 45        | 0.37%   |
| Unknown SD/MMC/MS PRO 64GB                          | 43        | 0.35%   |
| Crucial CT250MX500SSD1 250GB                        | 43        | 0.35%   |
| Seagate Expansion 1TB                               | 40        | 0.33%   |
| Samsung SSD 840 EVO 250GB                           | 40        | 0.33%   |
| Kingston SV300S37A120G 120GB SSD                    | 40        | 0.33%   |
| Toshiba DT01ACA100 1TB                              | 38        | 0.31%   |
| Seagate ST4000DM004-2CV104 4TB                      | 38        | 0.31%   |
| SanDisk NVMe SSD Drive 1TB                          | 38        | 0.31%   |
| Unknown MMC Card  16GB                              | 37        | 0.3%    |
| Seagate ST2000DM001-1ER164 2TB                      | 37        | 0.3%    |
| HGST HTS721010A9E630 1TB                            | 37        | 0.3%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 35        | 0.29%   |
| Toshiba MQ01ABF050 500GB                            | 35        | 0.29%   |
| Seagate ST1000DM003-1ER162 1TB                      | 35        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1562      | 2581   | 36.17%  |
| WDC                 | 1164      | 1985   | 26.96%  |
| Toshiba             | 535       | 738    | 12.39%  |
| Hitachi             | 396       | 548    | 9.17%   |
| Samsung Electronics | 218       | 307    | 5.05%   |
| HGST                | 163       | 238    | 3.77%   |
| Unknown             | 50        | 67     | 1.16%   |
| Apple               | 48        | 58     | 1.11%   |
| Maxtor              | 47        | 75     | 1.09%   |
| Fujitsu             | 44        | 61     | 1.02%   |
| Hewlett-Packard     | 15        | 50     | 0.35%   |
| ASMT                | 11        | 39     | 0.25%   |
| USB3.0              | 9         | 14     | 0.21%   |
| ASMedia             | 7         | 13     | 0.16%   |
| SSK                 | 6         | 7      | 0.14%   |
| WD MediaMax         | 4         | 4      | 0.09%   |
| HPE                 | 4         | 6      | 0.09%   |
| External            | 4         | 4      | 0.09%   |
| LaCie               | 3         | 3      | 0.07%   |
| ASMT109x            | 3         | 5      | 0.07%   |
| USB                 | 2         | 2      | 0.05%   |
| RSH-339             | 2         | 2      | 0.05%   |
| KESU                | 2         | 6      | 0.05%   |
| JMicron Technology  | 2         | 5      | 0.05%   |
| IBM/Hitachi         | 2         | 2      | 0.05%   |
| ExcelStor           | 2         | 4      | 0.05%   |
| SAGE                | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| NETAPP              | 1         | 4      | 0.02%   |
| Maxone              | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |
| LIO-ORG             | 1         | 8      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| HGST HTS            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Advantech           | 1         | 1      | 0.02%   |
| Unknown             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 817       | 1224   | 22.38%  |
| Crucial             | 522       | 760    | 14.3%   |
| SanDisk             | 429       | 551    | 11.75%  |
| Kingston            | 381       | 516    | 10.44%  |
| WDC                 | 199       | 273    | 5.45%   |
| China               | 107       | 146    | 2.93%   |
| Intel               | 91        | 104    | 2.49%   |
| A-DATA Technology   | 76        | 97     | 2.08%   |
| OCZ                 | 65        | 74     | 1.78%   |
| Toshiba             | 61        | 77     | 1.67%   |
| PNY                 | 60        | 71     | 1.64%   |
| Micron Technology   | 60        | 71     | 1.64%   |
| SK hynix            | 55        | 68     | 1.51%   |
| LITEON              | 55        | 67     | 1.51%   |
| Apple               | 48        | 62     | 1.31%   |
| Transcend           | 47        | 57     | 1.29%   |
| LITEONIT            | 32        | 40     | 0.88%   |
| Integral            | 30        | 35     | 0.82%   |
| Corsair             | 30        | 43     | 0.82%   |
| Netac               | 25        | 32     | 0.68%   |
| Patriot             | 24        | 37     | 0.66%   |
| SABRENT             | 23        | 27     | 0.63%   |
| Seagate             | 22        | 26     | 0.6%    |
| Drevo               | 19        | 31     | 0.52%   |
| Gigabyte Technology | 17        | 22     | 0.47%   |
| SPCC                | 15        | 28     | 0.41%   |
| Unknown             | 14        | 19     | 0.38%   |
| Team                | 14        | 15     | 0.38%   |
| Lexar               | 13        | 15     | 0.36%   |
| KIOXIA-EXCERIA      | 13        | 17     | 0.36%   |
| JMicron Technology  | 13        | 19     | 0.36%   |
| TO Exter            | 12        | 14     | 0.33%   |
| ASMT                | 12        | 15     | 0.33%   |
| Vaseky              | 11        | 16     | 0.3%    |
| TCSUNBOW            | 11        | 17     | 0.3%    |
| ORTIAL              | 11        | 11     | 0.3%    |
| Maxtor              | 10        | 11     | 0.27%   |
| Unknown             | 8         | 9      | 0.22%   |
| Plextor             | 7         | 10     | 0.19%   |
| KingDian            | 7         | 10     | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3509      | 6847   | 37.1%   |
| SSD     | 3072      | 4975   | 32.48%  |
| NVMe    | 2181      | 3172   | 23.06%  |
| MMC     | 546       | 726    | 5.77%   |
| Unknown | 150       | 226    | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5323      | 11239  | 62.46%  |
| NVMe | 2178      | 3157   | 25.56%  |
| MMC  | 546       | 726    | 6.41%   |
| SAS  | 475       | 824    | 5.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3963      | 6515   | 55.6%   |
| 0.51-1.0   | 1912      | 2972   | 26.82%  |
| 1.01-2.0   | 659       | 1125   | 9.25%   |
| 3.01-4.0   | 217       | 432    | 3.04%   |
| 2.01-3.0   | 171       | 315    | 2.4%    |
| 4.01-10.0  | 158       | 372    | 2.22%   |
| 10.01-20.0 | 47        | 90     | 0.66%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2031      | 26.66%  |
| 251-500        | 1498      | 19.66%  |
| 501-1000       | 1144      | 15.02%  |
| 1001-2000      | 602       | 7.9%    |
| 1-20           | 542       | 7.11%   |
| 51-100         | 493       | 6.47%   |
| More than 3000 | 483       | 6.34%   |
| 21-50          | 355       | 4.66%   |
| 2001-3000      | 237       | 3.11%   |
| Unknown        | 233       | 3.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3132      | 39.63%  |
| 21-50          | 1286      | 16.27%  |
| 101-250        | 925       | 11.7%   |
| 51-100         | 829       | 10.49%  |
| 251-500        | 581       | 7.35%   |
| 501-1000       | 391       | 4.95%   |
| 1001-2000      | 258       | 3.26%   |
| Unknown        | 233       | 2.95%   |
| More than 3000 | 175       | 2.21%   |
| 2001-3000      | 92        | 1.16%   |
| 0              | 2         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 8         | 12     | 1.45%   |
| Seagate ST9500325AS 500GB                | 7         | 11     | 1.27%   |
| Seagate ST500DM002-1BD142 500GB          | 6         | 6      | 1.08%   |
| Seagate ST3500418AS 500GB                | 6         | 6      | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB           | 6         | 6      | 1.08%   |
| HGST HTS725050A7E630 500GB               | 6         | 9      | 1.08%   |
| Seagate ST500LM021-1KJ152 500GB          | 5         | 5      | 0.9%    |
| Seagate ST3500312CS 500GB                | 5         | 7      | 0.9%    |
| Samsung Electronics HD103UJ 1TB          | 5         | 7      | 0.9%    |
| Seagate ST2000DM001-1CH164 2TB           | 4         | 5      | 0.72%   |
| Samsung Electronics SSD 960 EVO 250GB    | 4         | 5      | 0.72%   |
| Samsung Electronics HD103SJ 1TB          | 4         | 5      | 0.72%   |
| Hitachi HTS547575A9E384 752GB            | 4         | 6      | 0.72%   |
| Hitachi HTS545025B9A300 250GB            | 4         | 4      | 0.72%   |
| Hitachi HDT721010SLA360 1TB              | 4         | 5      | 0.72%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 0.72%   |
| WDC WD5000BEVT-75A0RT0 500GB             | 3         | 5      | 0.54%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 3         | 10     | 0.54%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 3         | 3      | 0.54%   |
| Toshiba MK1656GSY 160GB                  | 3         | 3      | 0.54%   |
| Toshiba DT01ACA050 500GB                 | 3         | 4      | 0.54%   |
| Seagate ST3500620AS 500GB                | 3         | 4      | 0.54%   |
| Seagate ST2000DM006-2DM164 2TB           | 3         | 3      | 0.54%   |
| Seagate ST1000LM014-SSHD-8GB             | 3         | 4      | 0.54%   |
| SanDisk SSD PLUS 480GB                   | 3         | 3      | 0.54%   |
| Samsung Electronics SSD 840 Series 120GB | 3         | 3      | 0.54%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 3      | 0.54%   |
| Intel SSDPEKKW512G7 512GB                | 3         | 5      | 0.54%   |
| Hitachi HUA723030ALA640 3TB              | 3         | 4      | 0.54%   |
| Hitachi HTS542512K9SA00 120GB            | 3         | 3      | 0.54%   |
| Hitachi HDS721010CLA332 1TB              | 3         | 3      | 0.54%   |
| Hitachi HDP725050GLA360 500GB            | 3         | 3      | 0.54%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 0.54%   |
| Crucial CT525MX300SSD4 528GB             | 3         | 3      | 0.54%   |
| Crucial CT480M500SSD1 480GB              | 3         | 3      | 0.54%   |
| WDC WD800JD-00HKA0 80GB                  | 2         | 2      | 0.36%   |
| WDC WD6400AAKS-22A7B2 640GB              | 2         | 2      | 0.36%   |
| WDC WD6400AAKS-22A7B0 640GB              | 2         | 2      | 0.36%   |
| WDC WD5000BEVT-60A0RT0 500GB             | 2         | 3      | 0.36%   |
| WDC WD5000AAKX-75U6AA0 500GB             | 2         | 2      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 135       | 168    | 25.38%  |
| WDC                 | 111       | 175    | 20.86%  |
| Hitachi             | 63        | 87     | 11.84%  |
| Samsung Electronics | 46        | 59     | 8.65%   |
| Toshiba             | 34        | 40     | 6.39%   |
| Crucial             | 27        | 33     | 5.08%   |
| HGST                | 17        | 20     | 3.2%    |
| Intel               | 16        | 24     | 3.01%   |
| SanDisk             | 13        | 17     | 2.44%   |
| Kingston            | 9         | 11     | 1.69%   |
| SK hynix            | 6         | 6      | 1.13%   |
| Micron Technology   | 5         | 5      | 0.94%   |
| LITEON              | 5         | 5      | 0.94%   |
| Fujitsu             | 5         | 5      | 0.94%   |
| A-DATA Technology   | 5         | 5      | 0.94%   |
| Maxtor              | 4         | 4      | 0.75%   |
| Drevo               | 4         | 10     | 0.75%   |
| Hewlett-Packard     | 3         | 3      | 0.56%   |
| Corsair             | 3         | 7      | 0.56%   |
| WD MediaMax         | 2         | 2      | 0.38%   |
| Unknown             | 2         | 2      | 0.38%   |
| OCZ                 | 2         | 2      | 0.38%   |
| China               | 2         | 2      | 0.38%   |
| BAITITON            | 2         | 5      | 0.38%   |
| Zheino              | 1         | 2      | 0.19%   |
| VENO                | 1         | 1      | 0.19%   |
| Team                | 1         | 1      | 0.19%   |
| KingSpec            | 1         | 1      | 0.19%   |
| faspeed             | 1         | 1      | 0.19%   |
| BIWIN               | 1         | 1      | 0.19%   |
| Apple               | 1         | 2      | 0.19%   |
| Apacer              | 1         | 1      | 0.19%   |
| AGI                 | 1         | 1      | 0.19%   |
| 2-Power             | 1         | 1      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 135       | 168    | 34.35%  |
| WDC                 | 108       | 172    | 27.48%  |
| Hitachi             | 63        | 87     | 16.03%  |
| Toshiba             | 33        | 39     | 8.4%    |
| Samsung Electronics | 20        | 27     | 5.09%   |
| HGST                | 17        | 20     | 4.33%   |
| Fujitsu             | 5         | 5      | 1.27%   |
| Maxtor              | 4         | 4      | 1.02%   |
| Hewlett-Packard     | 3         | 3      | 0.76%   |
| WD MediaMax         | 2         | 2      | 0.51%   |
| Unknown             | 2         | 2      | 0.51%   |
| Apple               | 1         | 2      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 354       | 531    | 71.95%  |
| SSD  | 116       | 149    | 23.58%  |
| NVMe | 22        | 30     | 4.47%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB  | 2         | 3      | 25%     |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 12.5%   |
| Toshiba DT01ACA100 1TB            | 1         | 1      | 12.5%   |
| Seagate ST3160815AS 160GB         | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 12.5%   |
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 12.5%   |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 5      | 50%     |
| Samsung Electronics | 2         | 2      | 25%     |
| Seagate             | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4786      | 10424  | 62.09%  |
| Works    | 2438      | 4803   | 31.63%  |
| Malfunc  | 477       | 710    | 6.19%   |
| Failed   | 7         | 9      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4489      | 49.92%  |
| AMD                              | 1540      | 17.12%  |
| Samsung Electronics              | 828       | 9.21%   |
| SanDisk                          | 362       | 4.03%   |
| Phison Electronics               | 242       | 2.69%   |
| ASMedia Technology               | 178       | 1.98%   |
| SK hynix                         | 165       | 1.83%   |
| Nvidia                           | 149       | 1.66%   |
| Toshiba America Info Systems     | 146       | 1.62%   |
| Marvell Technology Group         | 116       | 1.29%   |
| Kingston Technology Company      | 99        | 1.1%    |
| Micron/Crucial Technology        | 93        | 1.03%   |
| JMicron Technology               | 88        | 0.98%   |
| KIOXIA                           | 64        | 0.71%   |
| Silicon Motion                   | 62        | 0.69%   |
| Micron Technology                | 62        | 0.69%   |
| ADATA Technology                 | 43        | 0.48%   |
| LSI Logic / Symbios Logic        | 35        | 0.39%   |
| Broadcom / LSI                   | 23        | 0.26%   |
| VIA Technologies                 | 21        | 0.23%   |
| Seagate Technology               | 21        | 0.23%   |
| Silicon Image                    | 19        | 0.21%   |
| Apple                            | 18        | 0.2%    |
| Silicon Integrated Systems [SiS] | 15        | 0.17%   |
| Hewlett-Packard                  | 15        | 0.17%   |
| O2 Micro                         | 12        | 0.13%   |
| Solid State Storage Technology   | 10        | 0.11%   |
| Lenovo                           | 10        | 0.11%   |
| Adaptec                          | 10        | 0.11%   |
| Union Memory (Shenzhen)          | 9         | 0.1%    |
| Realtek Semiconductor            | 9         | 0.1%    |
| Shenzhen Longsys Electronics     | 6         | 0.07%   |
| Lite-On Technology               | 6         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.06%   |
| Yangtze Memory Technologies      | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| Netac Technology                 | 2         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.02%   |
| Dell                             | 2         | 0.02%   |
| ULi Electronics                  | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1040      | 9.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 425       | 4.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 302       | 2.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 290       | 2.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 274       | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 244       | 2.32%   |
| AMD 400 Series Chipset SATA Controller                                         | 218       | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 182       | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 180       | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 180       | 1.71%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 170       | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 165       | 1.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 164       | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 145       | 1.38%   |
| Intel Volume Management Device NVMe RAID Controller                            | 142       | 1.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 136       | 1.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 135       | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 129       | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 125       | 1.19%   |
| Intel SATA Controller [RAID mode]                                              | 124       | 1.18%   |
| Samsung NVMe SSD Controller 980                                                | 120       | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 115       | 1.09%   |
| Phison E12 NVMe Controller                                                     | 115       | 1.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 114       | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 113       | 1.07%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 106       | 1.01%   |
| AMD 500 Series Chipset SATA Controller                                         | 103       | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 101       | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 100       | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 92        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 90        | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 89        | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 86        | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 84        | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 77        | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 77        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 73        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 72        | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 65        | 0.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 63        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5077      | 56%     |
| NVMe | 2198      | 24.24%  |
| IDE  | 1113      | 12.28%  |
| RAID | 612       | 6.75%   |
| SAS  | 39        | 0.43%   |
| SCSI | 27        | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 5187      | 72.6%   |
| AMD          | 1866      | 26.12%  |
| ARM          | 90        | 1.26%   |
| QUALCOMM     | 1         | 0.01%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Custom APU 0405                     | 80        | 1.12%   |
| AMD Ryzen 5 3600 6-Core Processor       | 78        | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 68        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 64        | 0.89%   |
| ARM Processor                           | 64        | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 55        | 0.77%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 52        | 0.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 49        | 0.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 49        | 0.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 47        | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 47        | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 46        | 0.64%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 44        | 0.61%   |
| AMD FX-8350 Eight-Core Processor        | 43        | 0.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 41        | 0.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 41        | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 40        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 39        | 0.54%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 39        | 0.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 39        | 0.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 38        | 0.53%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 38        | 0.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 38        | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 37        | 0.52%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 37        | 0.52%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 37        | 0.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 36        | 0.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 36        | 0.5%    |
| Intel Core i7-2600 CPU @ 3.40GHz        | 35        | 0.49%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 35        | 0.49%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 35        | 0.49%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 33        | 0.46%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 31        | 0.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 31        | 0.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 31        | 0.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 30        | 0.42%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 30        | 0.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 29        | 0.4%    |
| AMD Ryzen 5 5600X 6-Core Processor      | 29        | 0.4%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 28        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1434      | 20.03%  |
| Intel Core i7           | 1332      | 18.6%   |
| Other                   | 505       | 7.05%   |
| Intel Core i3           | 448       | 6.26%   |
| AMD Ryzen 5             | 375       | 5.24%   |
| Intel Celeron           | 356       | 4.97%   |
| AMD Ryzen 7             | 319       | 4.46%   |
| Intel Core 2 Duo        | 318       | 4.44%   |
| Intel Xeon              | 202       | 2.82%   |
| Intel Pentium           | 188       | 2.63%   |
| AMD FX                  | 152       | 2.12%   |
| AMD Ryzen 9             | 146       | 2.04%   |
| Intel Atom              | 127       | 1.77%   |
| AMD A6                  | 84        | 1.17%   |
| AMD Ryzen 3             | 80        | 1.12%   |
| AMD A8                  | 80        | 1.12%   |
| Intel Pentium Dual-Core | 76        | 1.06%   |
| Intel Core 2 Quad       | 66        | 0.92%   |
| AMD A10                 | 56        | 0.78%   |
| Intel Core 2            | 55        | 0.77%   |
| Intel Core i9           | 53        | 0.74%   |
| Intel Pentium Dual      | 43        | 0.6%    |
| AMD A4                  | 42        | 0.59%   |
| AMD Athlon II X2        | 41        | 0.57%   |
| AMD Phenom II X4        | 34        | 0.47%   |
| Intel Genuine           | 28        | 0.39%   |
| AMD Ryzen Threadripper  | 27        | 0.38%   |
| ARM BCM                 | 25        | 0.35%   |
| AMD Athlon 64 X2        | 25        | 0.35%   |
| AMD Athlon              | 24        | 0.34%   |
| Intel Pentium 4         | 23        | 0.32%   |
| AMD E1                  | 23        | 0.32%   |
| AMD E                   | 22        | 0.31%   |
| Intel Celeron Dual-Core | 20        | 0.28%   |
| Intel Pentium Silver    | 17        | 0.24%   |
| Intel Pentium D         | 17        | 0.24%   |
| AMD Athlon II X4        | 17        | 0.24%   |
| AMD Ryzen 7 PRO         | 15        | 0.21%   |
| Intel Celeron M         | 14        | 0.2%    |
| AMD Phenom              | 14        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2893      | 40.41%  |
| 4       | 2510      | 35.06%  |
| 6       | 669       | 9.34%   |
| 8       | 528       | 7.38%   |
| 1       | 184       | 2.57%   |
| 12      | 133       | 1.86%   |
| 16      | 83        | 1.16%   |
| 3       | 62        | 0.87%   |
| 10      | 34        | 0.47%   |
| 14      | 28        | 0.39%   |
| 24      | 14        | 0.2%    |
| 32      | 6         | 0.08%   |
| 20      | 3         | 0.04%   |
| Unknown | 3         | 0.04%   |
| 64      | 2         | 0.03%   |
| 40      | 2         | 0.03%   |
| 28      | 2         | 0.03%   |
| 44      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7046      | 98.61%  |
| 2       | 91        | 1.27%   |
| 4       | 3         | 0.04%   |
| Unknown | 3         | 0.04%   |
| 3       | 2         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4600      | 64.32%  |
| 1       | 2549      | 35.64%  |
| Unknown | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6919      | 96.47%  |
| Unknown        | 175       | 2.44%   |
| 32-bit         | 73        | 1.02%   |
| 64-bit         | 5         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1914      | 25.75%  |
| 0x306a9    | 373       | 5.02%   |
| 0x206a7    | 368       | 4.95%   |
| 0x306c3    | 310       | 4.17%   |
| 0x1067a    | 268       | 3.61%   |
| 0x906ea    | 163       | 2.19%   |
| 0x806ea    | 143       | 1.92%   |
| 0x506e3    | 142       | 1.91%   |
| 0x08701021 | 137       | 1.84%   |
| 0x806ec    | 128       | 1.72%   |
| 0x806e9    | 128       | 1.72%   |
| 0x406e3    | 128       | 1.72%   |
| 0x40651    | 121       | 1.63%   |
| 0x20655    | 116       | 1.56%   |
| 0x806c1    | 113       | 1.52%   |
| 0x906e9    | 110       | 1.48%   |
| 0x306d4    | 109       | 1.47%   |
| 0x6fd      | 95        | 1.28%   |
| 0x406c4    | 90        | 1.21%   |
| 0x010000c8 | 82        | 1.1%    |
| 0x06000852 | 78        | 1.05%   |
| 0x30678    | 72        | 0.97%   |
| 0x06001119 | 67        | 0.9%    |
| 0x0800820d | 66        | 0.89%   |
| 0x10676    | 64        | 0.86%   |
| 0x08108109 | 60        | 0.81%   |
| 0x08701013 | 55        | 0.74%   |
| 0x6fb      | 53        | 0.71%   |
| 0x506c9    | 53        | 0.71%   |
| 0xa0652    | 51        | 0.69%   |
| 0x706e5    | 50        | 0.67%   |
| 0x20652    | 47        | 0.63%   |
| 0x0a50000c | 46        | 0.62%   |
| 0x06006705 | 46        | 0.62%   |
| 0x906ed    | 45        | 0.61%   |
| 0x406c3    | 43        | 0.58%   |
| 0x08108102 | 40        | 0.54%   |
| 0x706a1    | 38        | 0.51%   |
| 0x08600106 | 38        | 0.51%   |
| 0x206c2    | 37        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1020      | 14.24%  |
| Haswell          | 595       | 8.31%   |
| SandyBridge      | 494       | 6.9%    |
| IvyBridge        | 485       | 6.77%   |
| Penryn           | 395       | 5.52%   |
| Skylake          | 369       | 5.15%   |
| Zen 2            | 354       | 4.94%   |
| Unknown          | 305       | 4.26%   |
| Silvermont       | 263       | 3.67%   |
| Core             | 261       | 3.64%   |
| Westmere         | 247       | 3.45%   |
| Zen+             | 233       | 3.25%   |
| Piledriver       | 202       | 2.82%   |
| Zen 3            | 181       | 2.53%   |
| K10              | 178       | 2.49%   |
| TigerLake        | 161       | 2.25%   |
| Broadwell        | 159       | 2.22%   |
| Zen              | 155       | 2.16%   |
| CometLake        | 132       | 1.84%   |
| Excavator        | 114       | 1.59%   |
| IceLake          | 106       | 1.48%   |
| Goldmont plus    | 89        | 1.24%   |
| Nehalem          | 79        | 1.1%    |
| Alderlake Hybrid | 73        | 1.02%   |
| Goldmont         | 64        | 0.89%   |
| K8 Hammer        | 59        | 0.82%   |
| Puma             | 58        | 0.81%   |
| Steamroller      | 54        | 0.75%   |
| Bobcat           | 47        | 0.66%   |
| NetBurst         | 45        | 0.63%   |
| Bonnell          | 43        | 0.6%    |
| P6               | 39        | 0.54%   |
| Jaguar           | 29        | 0.4%    |
| Bulldozer        | 28        | 0.39%   |
| Tremont          | 16        | 0.22%   |
| K8 & K10 hybrid  | 13        | 0.18%   |
| K10 Llano        | 12        | 0.17%   |
| K6               | 4         | 0.06%   |
| Gracemont        | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3940      | 48.83%  |
| Nvidia                                       | 2212      | 27.42%  |
| AMD                                          | 1834      | 22.73%  |
| Matrox Electronics Systems                   | 39        | 0.48%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.19%   |
| ASPEED Technology                            | 12        | 0.15%   |
| ATI Technologies                             | 8         | 0.1%    |
| VIA Technologies                             | 5         | 0.06%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| Alliance Semiconductor                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 364       | 4.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 270       | 3.24%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 167       | 2%      |
| Intel UHD Graphics 620                                                                   | 163       | 1.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 160       | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 158       | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 155       | 1.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 152       | 1.82%   |
| Intel Core Processor Integrated Graphics Controller                                      | 150       | 1.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 144       | 1.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 140       | 1.68%   |
| Intel HD Graphics 620                                                                    | 136       | 1.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 129       | 1.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 129       | 1.55%   |
| Intel HD Graphics 5500                                                                   | 110       | 1.32%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 109       | 1.31%   |
| Intel HD Graphics 630                                                                    | 108       | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 104       | 1.25%   |
| Intel HD Graphics 530                                                                    | 102       | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 100       | 1.2%    |
| AMD Renoir                                                                               | 96        | 1.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 93        | 1.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 92        | 1.1%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 81        | 0.97%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 80        | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 75        | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 70        | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 62        | 0.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 62        | 0.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 61        | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 58        | 0.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 57        | 0.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 57        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 56        | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 56        | 0.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 55        | 0.66%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 53        | 0.64%   |
| Intel HD Graphics 500                                                                    | 51        | 0.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 49        | 0.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 48        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 3063      | 42.45%  |
| 1 x AMD                              | 1559      | 21.6%   |
| 1 x Nvidia                           | 1416      | 19.62%  |
| Intel + Nvidia                       | 668       | 9.26%   |
| Intel + AMD                          | 106       | 1.47%   |
| Other                                | 102       | 1.41%   |
| AMD + Nvidia                         | 85        | 1.18%   |
| 2 x AMD                              | 83        | 1.15%   |
| 1 x Matrox                           | 34        | 0.47%   |
| 2 x Nvidia                           | 30        | 0.42%   |
| 2 x Intel                            | 20        | 0.28%   |
| 1 x SiS                              | 14        | 0.19%   |
| Nvidia + ASPEED                      | 7         | 0.1%    |
| 1 x VIA                              | 5         | 0.07%   |
| 1 x ASPEED                           | 5         | 0.07%   |
| Nvidia + Matrox                      | 4         | 0.06%   |
| Intel + AMD + 1 x Nvidia             | 3         | 0.04%   |
| 2 x AMD + 1 x Nvidia                 | 2         | 0.03%   |
| Intel + 2 x Nvidia                   | 2         | 0.03%   |
| 3 x AMD                              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.01%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.01%   |
| 1 x XGI                              | 1         | 0.01%   |
| 1 x Intel + 3 x Nvidia               | 1         | 0.01%   |
| 1 x Huawei Technologies              | 1         | 0.01%   |
| AMD + SiS                            | 1         | 0.01%   |
| AMD + ASPEED                         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5646      | 77.51%  |
| Proprietary | 1278      | 17.55%  |
| Unknown     | 360       | 4.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4189      | 56.68%  |
| 0.01-0.5   | 831       | 11.24%  |
| 1.01-2.0   | 766       | 10.36%  |
| 0.51-1.0   | 502       | 6.79%   |
| 3.01-4.0   | 433       | 5.86%   |
| 7.01-8.0   | 332       | 4.49%   |
| 5.01-6.0   | 168       | 2.27%   |
| 8.01-16.0  | 113       | 1.53%   |
| 2.01-3.0   | 50        | 0.68%   |
| 16.01-24.0 | 4         | 0.05%   |
| 4.01-5.0   | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |
| 0          | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 884       | 11.76%  |
| AU Optronics            | 811       | 10.79%  |
| LG Display              | 647       | 8.61%   |
| Dell                    | 528       | 7.03%   |
| Chimei Innolux          | 500       | 6.65%   |
| BOE                     | 472       | 6.28%   |
| Acer                    | 328       | 4.36%   |
| Goldstar                | 252       | 3.35%   |
| Hewlett-Packard         | 245       | 3.26%   |
| BenQ                    | 236       | 3.14%   |
| AOC                     | 235       | 3.13%   |
| Sharp                   | 219       | 2.91%   |
| Apple                   | 168       | 2.24%   |
| Iiyama                  | 160       | 2.13%   |
| Lenovo                  | 141       | 1.88%   |
| Ancor Communications    | 137       | 1.82%   |
| Philips                 | 117       | 1.56%   |
| ViewSonic               | 84        | 1.12%   |
| Chi Mei Optoelectronics | 81        | 1.08%   |
| Sony                    | 78        | 1.04%   |
| Unknown                 | 65        | 0.86%   |
| ASUSTek Computer        | 65        | 0.86%   |
| HannStar                | 62        | 0.83%   |
| PANDA                   | 60        | 0.8%    |
| Panasonic               | 56        | 0.75%   |
| LG Philips              | 47        | 0.63%   |
| Toshiba                 | 45        | 0.6%    |
| Vestel Elektronik       | 43        | 0.57%   |
| LG Electronics          | 41        | 0.55%   |
| InfoVision              | 40        | 0.53%   |
| Valve                   | 37        | 0.49%   |
| NEC Computers           | 33        | 0.44%   |
| MSI                     | 30        | 0.4%    |
| Analogix                | 26        | 0.35%   |
| Gigabyte Technology     | 21        | 0.28%   |
| CSO                     | 19        | 0.25%   |
| OEM                     | 18        | 0.24%   |
| Hitachi                 | 18        | 0.24%   |
| Idek Iiyama             | 16        | 0.21%   |
| MiTAC                   | 15        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch | 42        | 0.54%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 42        | 0.54%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 35        | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 32        | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 32        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 30        | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 28        | 0.36%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 28        | 0.36%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 27        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 27        | 0.35%   |
| Analogix ANX7530 U ANX7539 800x1280 60x50mm 3.1-inch                 | 26        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 22        | 0.28%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                      | 22        | 0.28%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                      | 20        | 0.26%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 19        | 0.24%   |
| Panasonic TV MEIA296 3840x2160 708x398mm 32.0-inch                   | 18        | 0.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 18        | 0.23%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                   | 18        | 0.23%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 17        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 17        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 17        | 0.22%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch         | 16        | 0.21%   |
| OEM 26_LCD_TV OEM3700 1920x1080                                      | 16        | 0.21%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                    | 16        | 0.21%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 15        | 0.19%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 15        | 0.19%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 15        | 0.19%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch        | 15        | 0.19%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 14        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 14        | 0.18%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch         | 14        | 0.18%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 13        | 0.17%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 13        | 0.17%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch         | 13        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 13        | 0.17%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 13        | 0.17%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 13        | 0.17%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 13        | 0.17%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 13        | 0.17%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 13        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2971      | 40.97%  |
| 1366x768 (WXGA)    | 1233      | 17%     |
| 3840x2160 (4K)     | 562       | 7.75%   |
| 2560x1440 (QHD)    | 388       | 5.35%   |
| 1280x1024 (SXGA)   | 244       | 3.36%   |
| 1280x800 (WXGA)    | 207       | 2.85%   |
| 1600x900 (HD+)     | 195       | 2.69%   |
| 1680x1050 (WSXGA+) | 189       | 2.61%   |
| 1440x900 (WXGA+)   | 181       | 2.5%    |
| 1920x1200 (WUXGA)  | 169       | 2.33%   |
| Unknown            | 110       | 1.52%   |
| 3440x1440          | 92        | 1.27%   |
| 800x1280           | 59        | 0.81%   |
| 1360x768           | 57        | 0.79%   |
| 2560x1080          | 56        | 0.77%   |
| 2560x1600          | 52        | 0.72%   |
| 3840x1080          | 50        | 0.69%   |
| 1920x540           | 49        | 0.68%   |
| 3840x2400          | 31        | 0.43%   |
| 2880x1800          | 30        | 0.41%   |
| 1024x768 (XGA)     | 30        | 0.41%   |
| 3200x1800 (QHD+)   | 24        | 0.33%   |
| 2736x1824          | 24        | 0.33%   |
| 1600x1200          | 23        | 0.32%   |
| 2160x1440          | 19        | 0.26%   |
| 1280x720 (HD)      | 18        | 0.25%   |
| 1024x600           | 18        | 0.25%   |
| 2288x1287          | 10        | 0.14%   |
| 1920x1280          | 9         | 0.12%   |
| 5120x1440          | 8         | 0.11%   |
| 5760x1080          | 7         | 0.1%    |
| 3840x1200          | 6         | 0.08%   |
| 3072x1920          | 6         | 0.08%   |
| 2256x1504          | 6         | 0.08%   |
| 7680x2160          | 5         | 0.07%   |
| 3200x1080          | 5         | 0.07%   |
| 2880x1920          | 5         | 0.07%   |
| 2560x1700          | 5         | 0.07%   |
| 1680x945           | 5         | 0.07%   |
| 5760x2160          | 4         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1684      | 22.55%  |
| 13      | 725       | 9.71%   |
| 27      | 582       | 7.79%   |
| 24      | 533       | 7.14%   |
| Unknown | 497       | 6.65%   |
| 23      | 454       | 6.08%   |
| 14      | 423       | 5.66%   |
| 21      | 417       | 5.58%   |
| 17      | 372       | 4.98%   |
| 12      | 218       | 2.92%   |
| 19      | 199       | 2.66%   |
| 31      | 161       | 2.16%   |
| 11      | 116       | 1.55%   |
| 22      | 115       | 1.54%   |
| 84      | 114       | 1.53%   |
| 34      | 110       | 1.47%   |
| 18      | 85        | 1.14%   |
| 20      | 77        | 1.03%   |
| 72      | 59        | 0.79%   |
| 26      | 43        | 0.58%   |
| 16      | 42        | 0.56%   |
| 25      | 40        | 0.54%   |
| 32      | 39        | 0.52%   |
| 10      | 38        | 0.51%   |
| 7       | 35        | 0.47%   |
| 54      | 30        | 0.4%    |
| 3       | 26        | 0.35%   |
| 48      | 19        | 0.25%   |
| 40      | 19        | 0.25%   |
| 33      | 19        | 0.25%   |
| 28      | 18        | 0.24%   |
| 65      | 16        | 0.21%   |
| 39      | 16        | 0.21%   |
| 60      | 11        | 0.15%   |
| 46      | 11        | 0.15%   |
| 52      | 10        | 0.13%   |
| 55      | 9         | 0.12%   |
| 35      | 9         | 0.12%   |
| 43      | 8         | 0.11%   |
| 142     | 7         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2477      | 33.62%  |
| 501-600        | 1473      | 19.99%  |
| 201-300        | 817       | 11.09%  |
| 401-500        | 775       | 10.52%  |
| Unknown        | 497       | 6.75%   |
| 351-400        | 446       | 6.05%   |
| 601-700        | 267       | 3.62%   |
| 1501-2000      | 175       | 2.38%   |
| 701-800        | 173       | 2.35%   |
| 1001-1500      | 133       | 1.81%   |
| 1-100          | 59        | 0.8%    |
| 801-900        | 47        | 0.64%   |
| 901-1000       | 14        | 0.19%   |
| More than 2000 | 9         | 0.12%   |
| 101-200        | 6         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4949      | 72.08%  |
| 16/10   | 855       | 12.45%  |
| Unknown | 435       | 6.34%   |
| 5/4     | 226       | 3.29%   |
| 21/9    | 132       | 1.92%   |
| 3/2     | 95        | 1.38%   |
| 4/3     | 65        | 0.95%   |
| 6/5     | 36        | 0.52%   |
| 0.67    | 35        | 0.51%   |
| 32/9    | 22        | 0.32%   |
| 1.00    | 11        | 0.16%   |
| 3.20    | 2         | 0.03%   |
| 3.40    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1679      | 22.7%   |
| 201-250        | 1212      | 16.39%  |
| 81-90          | 768       | 10.38%  |
| 301-350        | 613       | 8.29%   |
| Unknown        | 497       | 6.72%   |
| 151-200        | 413       | 5.58%   |
| 71-80          | 394       | 5.33%   |
| 351-500        | 350       | 4.73%   |
| More than 1000 | 277       | 3.74%   |
| 121-130        | 213       | 2.88%   |
| 251-300        | 206       | 2.78%   |
| 61-70          | 191       | 2.58%   |
| 141-150        | 165       | 2.23%   |
| 51-60          | 121       | 1.64%   |
| 501-1000       | 94        | 1.27%   |
| 1-40           | 65        | 0.88%   |
| 131-140        | 48        | 0.65%   |
| 111-120        | 43        | 0.58%   |
| 41-50          | 34        | 0.46%   |
| 91-100         | 14        | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2274      | 31.51%  |
| 101-120       | 1788      | 24.77%  |
| 121-160       | 1701      | 23.57%  |
| 161-240       | 515       | 7.14%   |
| Unknown       | 497       | 6.89%   |
| More than 240 | 249       | 3.45%   |
| 1-50          | 193       | 2.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5878      | 80.26%  |
| 2     | 969       | 13.23%  |
| 0     | 365       | 4.98%   |
| 3     | 102       | 1.39%   |
| 4     | 9         | 0.12%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3572      | 33.63%  |
| Intel                             | 3534      | 33.28%  |
| Qualcomm Atheros                  | 1070      | 10.08%  |
| Broadcom                          | 736       | 6.93%   |
| Ralink Technology                 | 201       | 1.89%   |
| Marvell Technology Group          | 168       | 1.58%   |
| Broadcom Limited                  | 152       | 1.43%   |
| Nvidia                            | 120       | 1.13%   |
| TP-Link                           | 113       | 1.06%   |
| Ralink                            | 112       | 1.05%   |
| MediaTek                          | 90        | 0.85%   |
| ASIX Electronics                  | 45        | 0.42%   |
| Ericsson Business Mobile Networks | 40        | 0.38%   |
| DisplayLink                       | 39        | 0.37%   |
| Samsung Electronics               | 38        | 0.36%   |
| Microsoft                         | 37        | 0.35%   |
| Dell                              | 36        | 0.34%   |
| NetGear                           | 29        | 0.27%   |
| Belkin Components                 | 28        | 0.26%   |
| Qualcomm Atheros Communications   | 27        | 0.25%   |
| Lenovo                            | 27        | 0.25%   |
| Huawei Technologies               | 26        | 0.24%   |
| Edimax Technology                 | 24        | 0.23%   |
| Qualcomm                          | 20        | 0.19%   |
| Aquantia                          | 20        | 0.19%   |
| Hewlett-Packard                   | 18        | 0.17%   |
| ASUSTek Computer                  | 16        | 0.15%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.14%   |
| Sierra Wireless                   | 14        | 0.13%   |
| Microchip Technology              | 12        | 0.11%   |
| Mellanox Technologies             | 11        | 0.1%    |
| JMicron Technology                | 11        | 0.1%    |
| Google                            | 11        | 0.1%    |
| Xiaomi                            | 10        | 0.09%   |
| VIA Technologies                  | 10        | 0.09%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.08%   |
| D-Link                            | 9         | 0.08%   |
| Apple                             | 9         | 0.08%   |
| D-Link System                     | 8         | 0.08%   |
| OPPO Electronics                  | 7         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2315      | 18.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 418       | 3.33%   |
| Intel Wi-Fi 6 AX200                                               | 346       | 2.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 293       | 2.33%   |
| Intel I211 Gigabit Network Connection                             | 239       | 1.9%    |
| Intel Wireless 8265 / 8275                                        | 204       | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 182       | 1.45%   |
| Intel Wireless 7265                                               | 170       | 1.35%   |
| Intel Wireless 7260                                               | 166       | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 152       | 1.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 150       | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 140       | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 139       | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 136       | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 128       | 1.02%   |
| Intel Wireless 3165                                               | 122       | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 122       | 0.97%   |
| Intel Wireless 8260                                               | 121       | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 120       | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 116       | 0.92%   |
| Intel Wi-Fi 6 AX201                                               | 109       | 0.87%   |
| Intel Ethernet Connection I217-LM                                 | 105       | 0.84%   |
| Intel Wireless-AC 9260                                            | 88        | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 87        | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 86        | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 83        | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 79        | 0.63%   |
| Realtek 802.11ac NIC                                              | 76        | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 75        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 72        | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 71        | 0.56%   |
| Intel Ethernet Controller I225-V                                  | 69        | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 68        | 0.54%   |
| Ralink MT7601U Wireless Adapter                                   | 68        | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 68        | 0.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 68        | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                     | 67        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 65        | 0.52%   |
| Intel 82579V Gigabit Network Connection                           | 65        | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 64        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2559      | 43.91%  |
| Realtek Semiconductor           | 1024      | 17.57%  |
| Qualcomm Atheros                | 872       | 14.96%  |
| Broadcom                        | 464       | 7.96%   |
| Ralink Technology               | 201       | 3.45%   |
| Ralink                          | 111       | 1.9%    |
| Broadcom Limited                | 110       | 1.89%   |
| TP-Link                         | 102       | 1.75%   |
| MediaTek                        | 80        | 1.37%   |
| Microsoft                       | 35        | 0.6%    |
| Marvell Technology Group        | 35        | 0.6%    |
| NetGear                         | 29        | 0.5%    |
| Belkin Components               | 28        | 0.48%   |
| Qualcomm Atheros Communications | 27        | 0.46%   |
| Edimax Technology               | 24        | 0.41%   |
| Dell                            | 21        | 0.36%   |
| ASUSTek Computer                | 15        | 0.26%   |
| Sierra Wireless                 | 14        | 0.24%   |
| Qualcomm                        | 10        | 0.17%   |
| D-Link                          | 9         | 0.15%   |
| D-Link System                   | 7         | 0.12%   |
| Micro Star International        | 6         | 0.1%    |
| IMC Networks                    | 6         | 0.1%    |
| ZyDAS                           | 4         | 0.07%   |
| Linksys                         | 4         | 0.07%   |
| Fibocom                         | 4         | 0.07%   |
| Wacom                           | 3         | 0.05%   |
| TRENDnet                        | 3         | 0.05%   |
| Sitecom Europe                  | 3         | 0.05%   |
| Gemtek                          | 3         | 0.05%   |
| Wilocity                        | 2         | 0.03%   |
| Hewlett-Packard                 | 2         | 0.03%   |
| Texas Instruments               | 1         | 0.02%   |
| Senao                           | 1         | 0.02%   |
| Philips (or NXP)                | 1         | 0.02%   |
| InProComm                       | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| CyberTAN Technology             | 1         | 0.02%   |
| BUFFALO                         | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 346       | 5.89%   |
| Intel Wireless 8265 / 8275                                              | 204       | 3.47%   |
| Intel Wireless 7265                                                     | 170       | 2.89%   |
| Intel Wireless 7260                                                     | 166       | 2.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 152       | 2.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 150       | 2.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 139       | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 136       | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 128       | 2.18%   |
| Intel Wireless 3165                                                     | 122       | 2.08%   |
| Intel Wireless 8260                                                     | 121       | 2.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 120       | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 116       | 1.97%   |
| Intel Wi-Fi 6 AX201                                                     | 109       | 1.85%   |
| Intel Wireless-AC 9260                                                  | 88        | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 87        | 1.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 86        | 1.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 83        | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 79        | 1.34%   |
| Realtek 802.11ac NIC                                                    | 76        | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 75        | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 72        | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 71        | 1.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 68        | 1.16%   |
| Ralink MT7601U Wireless Adapter                                         | 68        | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 68        | 1.16%   |
| Broadcom BCM43142 802.11b/g/n                                           | 67        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 65        | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 57        | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 57        | 0.97%   |
| Intel Wireless 3160                                                     | 56        | 0.95%   |
| Ralink RT5370 Wireless Adapter                                          | 55        | 0.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 55        | 0.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 55        | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 50        | 0.85%   |
| Intel WiFi Link 5100                                                    | 50        | 0.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 45        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                          | 44        | 0.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 43        | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 41        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3119      | 48.91%  |
| Intel                                  | 1913      | 30%     |
| Broadcom                               | 381       | 5.97%   |
| Qualcomm Atheros                       | 295       | 4.63%   |
| Marvell Technology Group               | 133       | 2.09%   |
| Nvidia                                 | 120       | 1.88%   |
| Broadcom Limited                       | 45        | 0.71%   |
| ASIX Electronics                       | 45        | 0.71%   |
| DisplayLink                            | 39        | 0.61%   |
| Samsung Electronics                    | 28        | 0.44%   |
| Lenovo                                 | 26        | 0.41%   |
| Huawei Technologies                    | 22        | 0.34%   |
| Aquantia                               | 20        | 0.31%   |
| Silicon Integrated Systems [SiS]       | 14        | 0.22%   |
| TP-Link                                | 12        | 0.19%   |
| Microchip Technology                   | 11        | 0.17%   |
| JMicron Technology                     | 11        | 0.17%   |
| Google                                 | 11        | 0.17%   |
| Xiaomi                                 | 10        | 0.16%   |
| VIA Technologies                       | 10        | 0.16%   |
| Qualcomm                               | 10        | 0.16%   |
| Mellanox Technologies                  | 10        | 0.16%   |
| MediaTek                               | 9         | 0.14%   |
| OnePlus Technology (Shenzhen)          | 8         | 0.13%   |
| OPPO Electronics                       | 7         | 0.11%   |
| Apple                                  | 7         | 0.11%   |
| ZTE WCDMA Technologies MSM             | 6         | 0.09%   |
| Motorola PCS                           | 6         | 0.09%   |
| ICS Advent                             | 5         | 0.08%   |
| Attansic Technology                    | 5         | 0.08%   |
| T & A Mobile Phones                    | 4         | 0.06%   |
| Standard Microsystems                  | 4         | 0.06%   |
| Hewlett-Packard                        | 4         | 0.06%   |
| HTC (High Tech Computer)               | 3         | 0.05%   |
| Emulex                                 | 3         | 0.05%   |
| 3Com                                   | 3         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| Research In Motion                     | 2         | 0.03%   |
| QLogic                                 | 2         | 0.03%   |
| Microsoft                              | 2         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2315      | 35.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 418       | 6.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 293       | 4.48%   |
| Intel I211 Gigabit Network Connection                             | 239       | 3.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 182       | 2.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 140       | 2.14%   |
| Intel Ethernet Connection (2) I219-V                              | 122       | 1.87%   |
| Intel Ethernet Connection I217-LM                                 | 105       | 1.61%   |
| Intel Ethernet Controller I225-V                                  | 69        | 1.06%   |
| Intel Ethernet Connection (7) I219-V                              | 68        | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 65        | 0.99%   |
| Intel 82577LM Gigabit Network Connection                          | 64        | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 60        | 0.92%   |
| Intel Ethernet Connection I218-LM                                 | 59        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 51        | 0.78%   |
| Nvidia MCP61 Ethernet                                             | 51        | 0.78%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 45        | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 43        | 0.66%   |
| Intel 82574L Gigabit Network Connection                           | 43        | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42        | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 42        | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 42        | 0.64%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 42        | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 41        | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 41        | 0.63%   |
| Intel Ethernet Connection (2) I218-V                              | 40        | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 37        | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 36        | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 36        | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 35        | 0.54%   |
| Intel Ethernet Connection (6) I219-V                              | 35        | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 34        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 33        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 33        | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 31        | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 29        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 28        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 26        | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 26        | 0.4%    |
| Nvidia MCP79 Ethernet                                             | 26        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6003      | 51.72%  |
| WiFi     | 5449      | 46.95%  |
| Modem    | 136       | 1.17%   |
| Unknown  | 18        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4224      | 57.23%  |
| Ethernet | 3155      | 42.74%  |
| Modem    | 1         | 0.01%   |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3741      | 52%     |
| 1     | 3025      | 42.05%  |
| 0     | 195       | 2.71%   |
| 3     | 164       | 2.28%   |
| 4     | 41        | 0.57%   |
| 5     | 18        | 0.25%   |
| 6     | 8         | 0.11%   |
| 8     | 2         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6334      | 87.33%  |
| Yes  | 919       | 12.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1984      | 46.43%  |
| Realtek Semiconductor           | 346       | 8.1%    |
| Cambridge Silicon Radio         | 323       | 7.56%   |
| Qualcomm Atheros Communications | 303       | 7.09%   |
| Broadcom                        | 278       | 6.51%   |
| Apple                           | 192       | 4.49%   |
| IMC Networks                    | 187       | 4.38%   |
| Foxconn / Hon Hai               | 111       | 2.6%    |
| Lite-On Technology              | 102       | 2.39%   |
| Dell                            | 75        | 1.76%   |
| ASUSTek Computer                | 73        | 1.71%   |
| Toshiba                         | 55        | 1.29%   |
| Hewlett-Packard                 | 42        | 0.98%   |
| Marvell Semiconductor           | 33        | 0.77%   |
| Realtek                         | 22        | 0.51%   |
| Belkin Components               | 19        | 0.44%   |
| MediaTek                        | 18        | 0.42%   |
| Alps Electric                   | 18        | 0.42%   |
| Foxconn International           | 14        | 0.33%   |
| TP-Link                         | 12        | 0.28%   |
| Integrated System Solution      | 10        | 0.23%   |
| Ralink                          | 9         | 0.21%   |
| Taiyo Yuden                     | 6         | 0.14%   |
| Ralink Technology               | 6         | 0.14%   |
| Askey Computer                  | 6         | 0.14%   |
| Micro Star International        | 5         | 0.12%   |
| Logitech                        | 4         | 0.09%   |
| HTC (High Tech Computer)        | 4         | 0.09%   |
| USI                             | 3         | 0.07%   |
| Edimax Technology               | 3         | 0.07%   |
| Unknown                         | 3         | 0.07%   |
| Sitecom Europe                  | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Cypress Semiconductor           | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 792       | 18.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 323       | 7.56%   |
| Intel AX200 Bluetooth                               | 318       | 7.44%   |
| Intel AX201 Bluetooth                               | 307       | 7.18%   |
| Realtek Bluetooth Radio                             | 213       | 4.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 209       | 4.89%   |
| IMC Networks Bluetooth Radio                        | 122       | 2.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 114       | 2.67%   |
| Apple Bluetooth Host Controller                     | 93        | 2.18%   |
| Realtek  Bluetooth 4.2 Adapter                      | 84        | 1.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 80        | 1.87%   |
| Intel Bluetooth Device                              | 79        | 1.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 76        | 1.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 71        | 1.66%   |
| Intel AX210 Bluetooth                               | 71        | 1.66%   |
| Intel Wireless-AC 3168 Bluetooth                    | 68        | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 61        | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                  | 57        | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 56        | 1.31%   |
| Apple Bluetooth USB Host Controller                 | 49        | 1.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 40        | 0.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 40        | 0.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 33        | 0.77%   |
| Marvell Bluetooth and Wireless LAN Composite        | 29        | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 29        | 0.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 29        | 0.68%   |
| IMC Networks Bluetooth Device                       | 26        | 0.61%   |
| Dell DW375 Bluetooth Module                         | 26        | 0.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 26        | 0.61%   |
| Lite-On Bluetooth Device                            | 24        | 0.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 23        | 0.54%   |
| Realtek RTL8821A Bluetooth                          | 22        | 0.51%   |
| Realtek Bluetooth Radio                             | 22        | 0.51%   |
| IMC Networks Wireless_Device                        | 22        | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 0.49%   |
| Apple Bluetooth HCI                                 | 21        | 0.49%   |
| Dell BCM20702A0 Bluetooth Module                    | 19        | 0.44%   |
| MediaTek Wireless_Device                            | 18        | 0.42%   |
| Toshiba Bluetooth Device                            | 17        | 0.4%    |
| Realtek RTL8723B Bluetooth                          | 16        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4914      | 49.56%  |
| AMD                                  | 2110      | 21.28%  |
| Nvidia                               | 1739      | 17.54%  |
| C-Media Electronics                  | 183       | 1.85%   |
| Creative Labs                        | 91        | 0.92%   |
| Logitech                             | 63        | 0.64%   |
| Texas Instruments                    | 55        | 0.55%   |
| Realtek Semiconductor                | 38        | 0.38%   |
| JMTek                                | 36        | 0.36%   |
| Focusrite-Novation                   | 36        | 0.36%   |
| ASUSTek Computer                     | 32        | 0.32%   |
| Creative Technology                  | 30        | 0.3%    |
| GN Netcom                            | 29        | 0.29%   |
| SteelSeries ApS                      | 28        | 0.28%   |
| Razer USA                            | 28        | 0.28%   |
| Plantronics                          | 26        | 0.26%   |
| Micro Star International             | 21        | 0.21%   |
| Corsair                              | 21        | 0.21%   |
| Blue Microphones                     | 20        | 0.2%    |
| VIA Technologies                     | 19        | 0.19%   |
| Lenovo                               | 19        | 0.19%   |
| Kingston Technology                  | 18        | 0.18%   |
| Apple                                | 16        | 0.16%   |
| Silicon Integrated Systems [SiS]     | 15        | 0.15%   |
| Generalplus Technology               | 15        | 0.15%   |
| Tenx Technology                      | 10        | 0.1%    |
| Dell                                 | 10        | 0.1%    |
| BEHRINGER International              | 10        | 0.1%    |
| XMOS                                 | 9         | 0.09%   |
| Sennheiser Communications            | 9         | 0.09%   |
| DSEA A/S                             | 9         | 0.09%   |
| ATI Technologies                     | 9         | 0.09%   |
| Sony                                 | 8         | 0.08%   |
| Hewlett-Packard                      | 8         | 0.08%   |
| GYROCOM C&C                          | 8         | 0.08%   |
| AKAI Professional M.I.               | 8         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 7         | 0.07%   |
| KTMicro                              | 7         | 0.07%   |
| Conexant Systems                     | 7         | 0.07%   |
| Yamaha                               | 6         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 501       | 4.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 476       | 4.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 440       | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 427       | 3.64%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 336       | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 330       | 2.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 295       | 2.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 285       | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 264       | 2.25%   |
| AMD FCH Azalia Controller                                                                         | 251       | 2.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 241       | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 236       | 2.01%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 197       | 1.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 183       | 1.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 179       | 1.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 177       | 1.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 166       | 1.41%   |
| Intel 8 Series HD Audio Controller                                                                | 162       | 1.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 160       | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 160       | 1.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 153       | 1.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 153       | 1.3%    |
| Intel 200 Series PCH HD Audio                                                                     | 145       | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 144       | 1.23%   |
| Intel Broadwell-U Audio Controller                                                                | 144       | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 137       | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 127       | 1.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 111       | 0.95%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 110       | 0.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 109       | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 108       | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 106       | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 103       | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 103       | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 102       | 0.87%   |
| Intel Comet Lake PCH cAVS                                                                         | 99        | 0.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 93        | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 88        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 87        | 0.74%   |
| Nvidia High Definition Audio Controller                                                           | 83        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 771       | 19.64%  |
| SK hynix            | 688       | 17.52%  |
| Corsair             | 468       | 11.92%  |
| Micron Technology   | 395       | 10.06%  |
| Crucial             | 381       | 9.7%    |
| Unknown             | 380       | 9.68%   |
| Kingston            | 345       | 8.79%   |
| Ramaxel Technology  | 62        | 1.58%   |
| A-DATA Technology   | 55        | 1.4%    |
| Nanya Technology    | 49        | 1.25%   |
| Elpida              | 49        | 1.25%   |
| G.Skill             | 39        | 0.99%   |
| Unknown (ABCD)      | 36        | 0.92%   |
| Team                | 29        | 0.74%   |
| Patriot             | 19        | 0.48%   |
| Unknown             | 18        | 0.46%   |
| Transcend           | 10        | 0.25%   |
| Hewlett-Packard     | 9         | 0.23%   |
| Qimonda             | 8         | 0.2%    |
| ASint Technology    | 7         | 0.18%   |
| A Force             | 7         | 0.18%   |
| Toshiba             | 6         | 0.15%   |
| Timetec             | 6         | 0.15%   |
| Apacer              | 6         | 0.15%   |
| Goodram             | 5         | 0.13%   |
| GSkill              | 4         | 0.1%    |
| KLEVV               | 3         | 0.08%   |
| Essencore           | 3         | 0.08%   |
| Axiom               | 3         | 0.08%   |
| 4ea5                | 3         | 0.08%   |
| V-Color             | 2         | 0.05%   |
| Unknown (F301)      | 2         | 0.05%   |
| Unknown (0x0702)    | 2         | 0.05%   |
| Unknown (0B38)      | 2         | 0.05%   |
| Thermaltake         | 2         | 0.05%   |
| Neo Forza           | 2         | 0.05%   |
| Lexar               | 2         | 0.05%   |
| Innodisk            | 2         | 0.05%   |
| Infineon            | 2         | 0.05%   |
| ff                  | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 45        | 1.06%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 41        | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 33        | 0.78%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 27        | 0.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 26        | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 23        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.52%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 21        | 0.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.5%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 20        | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 19        | 0.45%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.42%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 18        | 0.42%   |
| Unknown                                                          | 18        | 0.42%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 17        | 0.4%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 16        | 0.38%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 16        | 0.38%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 16        | 0.38%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.35%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 15        | 0.35%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 14        | 0.33%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 14        | 0.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 14        | 0.33%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.33%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 14        | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 13        | 0.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.31%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 0.28%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 12        | 0.28%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 12        | 0.28%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 11        | 0.26%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1539      | 44.95%  |
| DDR3    | 1121      | 32.74%  |
| DDR2    | 191       | 5.58%   |
| LPDDR4  | 146       | 4.26%   |
| LPDDR3  | 118       | 3.45%   |
| Unknown | 110       | 3.21%   |
| SDRAM   | 104       | 3.04%   |
| DDR5    | 46        | 1.34%   |
| DDR     | 25        | 0.73%   |
| LPDDR5  | 16        | 0.47%   |
| DRAM    | 8         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1770      | 52.4%   |
| DIMM         | 1297      | 38.4%   |
| Row Of Chips | 257       | 7.61%   |
| Chip         | 22        | 0.65%   |
| Unknown      | 22        | 0.65%   |
| RIMM         | 6         | 0.18%   |
| FB-DIMM      | 4         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1388      | 37.55%  |
| 4096   | 1006      | 27.22%  |
| 16384  | 541       | 14.64%  |
| 2048   | 468       | 12.66%  |
| 1024   | 150       | 4.06%   |
| 32768  | 121       | 3.27%   |
| 512    | 17        | 0.46%   |
| 256    | 2         | 0.05%   |
| 131072 | 1         | 0.03%   |
| 16     | 1         | 0.03%   |
| 13     | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 737       | 19.85%  |
| 2667    | 489       | 13.17%  |
| 3200    | 441       | 11.88%  |
| 2400    | 298       | 8.03%   |
| 1333    | 265       | 7.14%   |
| 2133    | 186       | 5.01%   |
| 3600    | 119       | 3.2%    |
| 667     | 106       | 2.85%   |
| 1867    | 97        | 2.61%   |
| 1334    | 90        | 2.42%   |
| 800     | 89        | 2.4%    |
| Unknown | 61        | 1.64%   |
| 4267    | 59        | 1.59%   |
| 1067    | 46        | 1.24%   |
| 3400    | 40        | 1.08%   |
| 3266    | 39        | 1.05%   |
| 1066    | 39        | 1.05%   |
| 3000    | 36        | 0.97%   |
| 4800    | 33        | 0.89%   |
| 3733    | 32        | 0.86%   |
| 2048    | 31        | 0.83%   |
| 1866    | 30        | 0.81%   |
| 4199    | 23        | 0.62%   |
| 2800    | 23        | 0.62%   |
| 3533    | 21        | 0.57%   |
| 2933    | 21        | 0.57%   |
| 2666    | 21        | 0.57%   |
| 533     | 21        | 0.57%   |
| 1800    | 19        | 0.51%   |
| 6400    | 18        | 0.48%   |
| 400     | 16        | 0.43%   |
| 4266    | 15        | 0.4%    |
| 3800    | 12        | 0.32%   |
| 975     | 12        | 0.32%   |
| 3666    | 7         | 0.19%   |
| 1639    | 7         | 0.19%   |
| 49926   | 6         | 0.16%   |
| 8400    | 6         | 0.16%   |
| 6000    | 6         | 0.16%   |
| 3534    | 6         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 71        | 42.01%  |
| Canon                 | 30        | 17.75%  |
| Seiko Epson           | 15        | 8.88%   |
| Samsung Electronics   | 15        | 8.88%   |
| Brother Industries    | 15        | 8.88%   |
| Prolific Technology   | 5         | 2.96%   |
| Lexmark International | 4         | 2.37%   |
| STMicroelectronics    | 2         | 1.18%   |
| QinHeng Electronics   | 2         | 1.18%   |
| Oki Data              | 2         | 1.18%   |
| Kyocera               | 2         | 1.18%   |
| Dymo-CoStar           | 2         | 1.18%   |
| Seiko Instruments     | 1         | 0.59%   |
| Ricoh                 | 1         | 0.59%   |
| Dell                  | 1         | 0.59%   |
| Apple                 | 1         | 0.59%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                       | 7         | 4.09%   |
| HP ENVY 4520 series                                       | 6         | 3.51%   |
| Prolific PL2305 Parallel Port                             | 5         | 2.92%   |
| HP ENVY 5000 series                                       | 5         | 2.92%   |
| Canon PIXMA MG2500 Series                                 | 5         | 2.92%   |
| HP DeskJet 2600 series                                    | 4         | 2.34%   |
| HP DeskJet 2130 series                                    | 3         | 1.75%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.17%   |
| Seiko Epson XP-243 245 247 Series                         | 2         | 1.17%   |
| Seiko Epson XP-200 Series                                 | 2         | 1.17%   |
| Samsung ML-2250 Series                                    | 2         | 1.17%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.17%   |
| Samsung C43x Series                                       | 2         | 1.17%   |
| QinHeng CH340S                                            | 2         | 1.17%   |
| Oki Data USB Device                                       | 2         | 1.17%   |
| HP LaserJet P2015 series                                  | 2         | 1.17%   |
| HP LaserJet 200 colorMFP M276nw                           | 2         | 1.17%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.17%   |
| HP Deskjet F2280 series                                   | 2         | 1.17%   |
| HP DeskJet 3700 series                                    | 2         | 1.17%   |
| HP DeskJet 3630 series                                    | 2         | 1.17%   |
| HP Deskjet 2540 series                                    | 2         | 1.17%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.17%   |
| HP Color LaserJet CP1215                                  | 2         | 1.17%   |
| Canon PIXMA MX920 Series                                  | 2         | 1.17%   |
| Canon PIXMA MP495                                         | 2         | 1.17%   |
| Canon PIXMA MG3600 Series                                 | 2         | 1.17%   |
| Canon MG5700 series                                       | 2         | 1.17%   |
| Canon LiDE 300                                            | 2         | 1.17%   |
| Canon iP7200 series                                       | 2         | 1.17%   |
| Brother HL-3140CW series                                  | 2         | 1.17%   |
| Brother DCP-7055 scanner/printer                          | 2         | 1.17%   |
| Seiko Instruments SLP-450 Driver                          | 1         | 0.58%   |
| Seiko Epson XP-211 214 216 Series                         | 1         | 0.58%   |
| Seiko Epson WF-3520 Series                                | 1         | 0.58%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.58%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.58%   |
| Seiko Epson L355 Series                                   | 1         | 0.58%   |
| Samsung SCX-4300 Series                                   | 1         | 0.58%   |
| Samsung SCX-4200 series                                   | 1         | 0.58%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 25        | 62.5%   |
| Seiko Epson        | 8         | 20%     |
| Hewlett-Packard    | 3         | 7.5%    |
| Ultima Electronics | 2         | 5%      |
| Mustek Systems     | 1         | 2.5%    |
| AGFA-Gevaert NV    | 1         | 2.5%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30                                                         | 5         | 12.5%   |
| Canon CanoScan LiDE 220                                                               | 4         | 10%     |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3         | 7.5%    |
| Canon CanoScan LiDE 200                                                               | 3         | 7.5%    |
| Canon CanoScan LiDE 110                                                               | 3         | 7.5%    |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 5%      |
| Seiko Epson Scanner                                                                   | 2         | 5%      |
| HP ScanJet 5300c/5370c                                                                | 2         | 5%      |
| Canon CanoScan LiDE 100                                                               | 2         | 5%      |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 1         | 2.5%    |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.5%    |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 2.5%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 2.5%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 2.5%    |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 2.5%    |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1         | 2.5%    |
| HP Scanjet G2710                                                                      | 1         | 2.5%    |
| Canon CanoScan LiDE 90                                                                | 1         | 2.5%    |
| Canon CanoScan LiDE 70                                                                | 1         | 2.5%    |
| Canon CanoScan LiDE 600F                                                              | 1         | 2.5%    |
| Canon CanoScan LiDE 210                                                               | 1         | 2.5%    |
| Canon CanoScan 3000/3000F/3000ex                                                      | 1         | 2.5%    |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 1         | 2.5%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 870       | 21.35%  |
| Microdia                               | 423       | 10.38%  |
| Realtek Semiconductor                  | 320       | 7.85%   |
| IMC Networks                           | 285       | 6.99%   |
| Logitech                               | 281       | 6.9%    |
| Sunplus Innovation Technology          | 197       | 4.83%   |
| Apple                                  | 158       | 3.88%   |
| Bison Electronics                      | 145       | 3.56%   |
| Cheng Uei Precision Industry (Foxlink) | 138       | 3.39%   |
| Quanta                                 | 136       | 3.34%   |
| Suyin                                  | 117       | 2.87%   |
| Acer                                   | 107       | 2.63%   |
| Lite-On Technology                     | 94        | 2.31%   |
| Microsoft                              | 79        | 1.94%   |
| Syntek                                 | 77        | 1.89%   |
| Silicon Motion                         | 62        | 1.52%   |
| Alcor Micro                            | 52        | 1.28%   |
| Samsung Electronics                    | 47        | 1.15%   |
| Ricoh                                  | 43        | 1.06%   |
| Lenovo                                 | 39        | 0.96%   |
| Luxvisions Innotech Limited            | 33        | 0.81%   |
| Z-Star Microelectronics                | 30        | 0.74%   |
| ARC International                      | 27        | 0.66%   |
| Generalplus Technology                 | 26        | 0.64%   |
| GEMBIRD                                | 21        | 0.52%   |
| MacroSilicon                           | 16        | 0.39%   |
| Creative Technology                    | 16        | 0.39%   |
| Sonix Technology                       | 15        | 0.37%   |
| ALi                                    | 13        | 0.32%   |
| Primax Electronics                     | 12        | 0.29%   |
| Razer USA                              | 10        | 0.25%   |
| Aveo Technology                        | 10        | 0.25%   |
| Huawei Technologies                    | 9         | 0.22%   |
| Shenzhen Kingcome Optoelectronic       | 8         | 0.2%    |
| Hewlett-Packard                        | 8         | 0.2%    |
| OmniVision Technologies                | 7         | 0.17%   |
| Intel                                  | 7         | 0.17%   |
| Genesys Logic                          | 7         | 0.17%   |
| Tobii Technology AB                    | 6         | 0.15%   |
| SunplusIT                              | 6         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 182       | 4.42%   |
| Chicony Integrated Camera                               | 148       | 3.59%   |
| Realtek Integrated_Webcam_HD                            | 105       | 2.55%   |
| Logitech HD Pro Webcam C920                             | 92        | 2.23%   |
| IMC Networks Integrated Camera                          | 81        | 1.97%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 79        | 1.92%   |
| Sunplus Integrated_Webcam_HD                            | 62        | 1.51%   |
| Chicony HD WebCam                                       | 62        | 1.51%   |
| Logitech Webcam C270                                    | 54        | 1.31%   |
| Chicony TOSHIBA Web Camera - HD                         | 50        | 1.21%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 47        | 1.14%   |
| Apple FaceTime HD Camera (Built-in)                     | 47        | 1.14%   |
| Apple Built-in iSight                                   | 46        | 1.12%   |
| Chicony USB2.0 Camera                                   | 39        | 0.95%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 39        | 0.95%   |
| Microdia Integrated Webcam                              | 37        | 0.9%    |
| Microdia Webcam Vitade AF                               | 34        | 0.83%   |
| Chicony USB 2.0 Camera                                  | 34        | 0.83%   |
| Microsoft LifeCam HD-3000                               | 32        | 0.78%   |
| Lite-On Integrated Camera                               | 32        | 0.78%   |
| Bison Integrated Camera                                 | 31        | 0.75%   |
| Acer BisonCam,NB Pro                                    | 31        | 0.75%   |
| Realtek USB Camera                                      | 30        | 0.73%   |
| Chicony HP TrueVision HD                                | 30        | 0.73%   |
| Chicony HP TrueVision HD Camera                         | 29        | 0.7%    |
| Chicony HP HD Camera                                    | 29        | 0.7%    |
| Syntek Integrated Camera                                | 28        | 0.68%   |
| Chicony HP Wide Vision HD Camera                        | 27        | 0.66%   |
| Chicony EasyCamera                                      | 27        | 0.66%   |
| ARC International Camera                                | 27        | 0.66%   |
| Syntek Lenovo EasyCamera                                | 25        | 0.61%   |
| Bison SunplusIT Integrated Camera                       | 25        | 0.61%   |
| Alcor Micro USB 2.0 Camera                              | 25        | 0.61%   |
| Chicony VGA Webcam                                      | 24        | 0.58%   |
| Quanta HD User Facing                                   | 23        | 0.56%   |
| Microsoft LifeCam Cinema                                | 23        | 0.56%   |
| Chicony Integrated Camera (1280x720@30)                 | 23        | 0.56%   |
| Apple FaceTime HD Camera                                | 23        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 22        | 0.53%   |
| Acer Integrated Camera                                  | 21        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 217       | 31.13%  |
| Synaptics                          | 186       | 26.69%  |
| Shenzhen Goodix Technology         | 109       | 15.64%  |
| Upek                               | 49        | 7.03%   |
| AuthenTec                          | 47        | 6.74%   |
| LighTuning Technology              | 33        | 4.73%   |
| Elan Microelectronics              | 33        | 4.73%   |
| STMicroelectronics                 | 16        | 2.3%    |
| Samsung Electronics                | 3         | 0.43%   |
| HOLTEK                             | 2         | 0.29%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.14%   |
| Focal-systems.Corp                 | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 59        | 8.46%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 47        | 6.74%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 6.03%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 5.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 36        | 5.16%   |
| Synaptics UWP WBDI                                                         | 31        | 4.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 3.87%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 3.44%   |
| Shenzhen Goodix FingerPrint                                                | 23        | 3.3%    |
| Validity Sensors Synaptics WBDI                                            | 21        | 3.01%   |
| Synaptics  WBDI                                                            | 19        | 2.73%   |
| Validity Sensors VFS491                                                    | 16        | 2.3%    |
| STMicroelectronics Fingerprint Reader                                      | 16        | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 15        | 2.15%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 2.15%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 15        | 2.15%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 2.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 2.01%   |
| Elan ELAN:Fingerprint                                                      | 14        | 2.01%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 1.87%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 1.72%   |
| AuthenTec AES2810                                                          | 11        | 1.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.43%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.43%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.43%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 10        | 1.43%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.29%   |
| Elan ELAN:ARM-M4                                                           | 9         | 1.29%   |
| Unknown                                                                    | 9         | 1.29%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 8         | 1.15%   |
| Synaptics WBDI Device                                                      | 8         | 1.15%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.15%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1%      |
| Synaptics WBDI                                                             | 6         | 0.86%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 6         | 0.86%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.86%   |
| AuthenTec AES1600                                                          | 6         | 0.86%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.72%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.72%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 172       | 51.65%  |
| Alcor Micro               | 74        | 22.22%  |
| Upek                      | 26        | 7.81%   |
| Lenovo                    | 24        | 7.21%   |
| O2 Micro                  | 22        | 6.61%   |
| Gemalto (was Gemplus)     | 4         | 1.2%    |
| SCM Microsystems          | 3         | 0.9%    |
| Yubico.com                | 1         | 0.3%    |
| Purism, SPC               | 1         | 0.3%    |
| OmniKey                   | 1         | 0.3%    |
| Hewlett-Packard           | 1         | 0.3%    |
| Clay Logic                | 1         | 0.3%    |
| Chicony Electronics       | 1         | 0.3%    |
| BIT4ID                    | 1         | 0.3%    |
| Aladdin Knowledge Systems | 1         | 0.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 69        | 20.72%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 69        | 20.72%  |
| Broadcom 5880                                                                | 44        | 13.21%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 31        | 9.31%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 7.81%   |
| Broadcom 58200                                                               | 26        | 7.81%   |
| Lenovo Integrated Smart Card Reader                                          | 22        | 6.61%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 5.11%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.5%    |
| Alcor Micro Watchdata W 1981                                                 | 5         | 1.5%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.9%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.6%    |
| Lenovo Smartcard Keyboard                                                    | 2         | 0.6%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.6%    |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.3%    |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.3%    |
| Purism, SPC Librem Key                                                       | 1         | 0.3%    |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.3%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.3%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.3%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.3%    |
| BIT4ID miniLector EVO                                                        | 1         | 0.3%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5192      | 70.73%  |
| 1     | 1691      | 23.04%  |
| 2     | 373       | 5.08%   |
| 3     | 59        | 0.8%    |
| 4     | 13        | 0.18%   |
| 5     | 6         | 0.08%   |
| 7     | 3         | 0.04%   |
| 6     | 3         | 0.04%   |
| 8     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 678       | 26.07%  |
| Graphics card            | 542       | 20.84%  |
| Net/wireless             | 421       | 16.19%  |
| Chipcard                 | 304       | 11.69%  |
| Multimedia controller    | 160       | 6.15%   |
| Communication controller | 116       | 4.46%   |
| Sound                    | 58        | 2.23%   |
| Unassigned class         | 57        | 2.19%   |
| Camera                   | 56        | 2.15%   |
| Bluetooth                | 53        | 2.04%   |
| Storage                  | 40        | 1.54%   |
| Net/ethernet             | 24        | 0.92%   |
| Card reader              | 21        | 0.81%   |
| Modem                    | 18        | 0.69%   |
| Network                  | 16        | 0.62%   |
| Storage/raid             | 10        | 0.38%   |
| Flash memory             | 8         | 0.31%   |
| Dvb card                 | 6         | 0.23%   |
| Firewire controller      | 5         | 0.19%   |
| Storage/ide              | 4         | 0.15%   |
| Storage/nvme             | 3         | 0.12%   |
| Unclassified device      | 1         | 0.04%   |

