MX 21 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_21/Desktop/README.md) and [notebooks](/Dist/MX_21/Notebook/README.md).

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

Total: 604

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [a322d502b8](https://linux-hardware.org/?probe=a322d502b8) | Jan 05, 2025 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [e052122061](https://linux-hardware.org/?probe=e052122061) | Dec 20, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [fb6b122d69](https://linux-hardware.org/?probe=fb6b122d69) | Dec 19, 2024 |
| Dell          | Latitude E5570              | Notebook    | [54e9a1a0b3](https://linux-hardware.org/?probe=54e9a1a0b3) | Dec 17, 2024 |
| Acer          | Swift SF314-57              | Notebook    | [fc0d1a098a](https://linux-hardware.org/?probe=fc0d1a098a) | Nov 25, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b2bdca3443](https://linux-hardware.org/?probe=b2bdca3443) | Nov 20, 2024 |
| Acer          | Aspire XC-605               | Desktop     | [5b81ea0b2c](https://linux-hardware.org/?probe=5b81ea0b2c) | Oct 27, 2024 |
| HP            | ProLiant DL360 G7           | Server      | [7926b0dc7f](https://linux-hardware.org/?probe=7926b0dc7f) | Oct 05, 2024 |
| Dell          | 0P096C A00                  | Desktop     | [e67dbd9311](https://linux-hardware.org/?probe=e67dbd9311) | Sep 29, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [fbffd2655c](https://linux-hardware.org/?probe=fbffd2655c) | Sep 05, 2024 |
| Lenovo        | V17 G2 ITL 82NX             | Notebook    | [ce81460fc8](https://linux-hardware.org/?probe=ce81460fc8) | Aug 31, 2024 |
| Lenovo        | ThinkPad 10 20C3S0HJ00      | Tablet      | [fbdcd41333](https://linux-hardware.org/?probe=fbdcd41333) | Jul 30, 2024 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [01b1c8c6cc](https://linux-hardware.org/?probe=01b1c8c6cc) | Jul 24, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [345fc32f50](https://linux-hardware.org/?probe=345fc32f50) | Jul 21, 2024 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [f0cc03e825](https://linux-hardware.org/?probe=f0cc03e825) | Jul 15, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [c54b7538dc](https://linux-hardware.org/?probe=c54b7538dc) | Jul 01, 2024 |
| Dell          | Inspiron 7500 2n1 Black     | Convertible | [18eb7baa73](https://linux-hardware.org/?probe=18eb7baa73) | Jun 11, 2024 |
| ASUSTek       | X205TA                      | Notebook    | [e39012d26d](https://linux-hardware.org/?probe=e39012d26d) | Jun 02, 2024 |
| Dell          | Inspiron 5584               | Notebook    | [0d061a3e07](https://linux-hardware.org/?probe=0d061a3e07) | May 31, 2024 |
| HP            | 620                         | Notebook    | [fc744613bf](https://linux-hardware.org/?probe=fc744613bf) | May 30, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d5c083c4c6](https://linux-hardware.org/?probe=d5c083c4c6) | May 27, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [29ebda2c17](https://linux-hardware.org/?probe=29ebda2c17) | May 23, 2024 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [74c8e530ad](https://linux-hardware.org/?probe=74c8e530ad) | May 22, 2024 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [de96d1e8d8](https://linux-hardware.org/?probe=de96d1e8d8) | May 22, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [cd1ed35419](https://linux-hardware.org/?probe=cd1ed35419) | May 02, 2024 |
| Lenovo        | ThinkPad E560 20EV0011GE    | Notebook    | [38ab585e58](https://linux-hardware.org/?probe=38ab585e58) | Apr 27, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [dc7cef1fe5](https://linux-hardware.org/?probe=dc7cef1fe5) | Apr 25, 2024 |
| ASRock        | X399 Taichi                 | Desktop     | [0aeb871159](https://linux-hardware.org/?probe=0aeb871159) | Apr 22, 2024 |
| HP            | 255 G1                      | Notebook    | [edea4d298e](https://linux-hardware.org/?probe=edea4d298e) | Apr 15, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [d6304d794d](https://linux-hardware.org/?probe=d6304d794d) | Apr 11, 2024 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a31a3d60b1](https://linux-hardware.org/?probe=a31a3d60b1) | Apr 01, 2024 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [ce4f787af2](https://linux-hardware.org/?probe=ce4f787af2) | Apr 01, 2024 |
| Acer          | Aspire E5-421G              | Notebook    | [f16af02ed4](https://linux-hardware.org/?probe=f16af02ed4) | Mar 26, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [904ac30154](https://linux-hardware.org/?probe=904ac30154) | Mar 23, 2024 |
| Gateway       | H57M01                      | Desktop     | [4254102990](https://linux-hardware.org/?probe=4254102990) | Mar 19, 2024 |
| Gateway       | H57M01                      | Desktop     | [162b2ed3b3](https://linux-hardware.org/?probe=162b2ed3b3) | Mar 17, 2024 |
| HP            | 255 G1                      | Notebook    | [097c812445](https://linux-hardware.org/?probe=097c812445) | Mar 16, 2024 |
| HP            | 620                         | Notebook    | [b5df7d8db3](https://linux-hardware.org/?probe=b5df7d8db3) | Mar 12, 2024 |
| HP            | 650                         | Notebook    | [96c8acc1a4](https://linux-hardware.org/?probe=96c8acc1a4) | Mar 11, 2024 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [5dc203d476](https://linux-hardware.org/?probe=5dc203d476) | Mar 10, 2024 |
| HP            | 8950                        | Desktop     | [ee925d29a1](https://linux-hardware.org/?probe=ee925d29a1) | Mar 08, 2024 |
| HP            | 8950                        | Desktop     | [f2b8f96540](https://linux-hardware.org/?probe=f2b8f96540) | Mar 08, 2024 |
| ASRock        | A300M-STX                   | Desktop     | [a92e2761aa](https://linux-hardware.org/?probe=a92e2761aa) | Mar 06, 2024 |
| HP            | Compaq nc6320 (RU397EA#A... | Notebook    | [edd727d30d](https://linux-hardware.org/?probe=edd727d30d) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480 20L6003PFR    | Notebook    | [d6ded6d32a](https://linux-hardware.org/?probe=d6ded6d32a) | Mar 03, 2024 |
| Dell          | System Inspiron N7110       | Notebook    | [6c1eb8d628](https://linux-hardware.org/?probe=6c1eb8d628) | Mar 02, 2024 |
| Foxconn       | 45GM/45CM/45CM-S            | Desktop     | [1dab02eb79](https://linux-hardware.org/?probe=1dab02eb79) | Feb 24, 2024 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | Desktop     | [3cf24bd897](https://linux-hardware.org/?probe=3cf24bd897) | Feb 18, 2024 |
| Dell          | Latitude E5540              | Notebook    | [9103e34326](https://linux-hardware.org/?probe=9103e34326) | Feb 17, 2024 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [bb7608ac6f](https://linux-hardware.org/?probe=bb7608ac6f) | Feb 15, 2024 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | Desktop     | [144333e02b](https://linux-hardware.org/?probe=144333e02b) | Feb 15, 2024 |
| LG Electro... | 17Z90N-V.BJ51P1             | Notebook    | [df1bbe4be6](https://linux-hardware.org/?probe=df1bbe4be6) | Feb 10, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [9c0a07bf2b](https://linux-hardware.org/?probe=9c0a07bf2b) | Feb 08, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [7350797e64](https://linux-hardware.org/?probe=7350797e64) | Feb 07, 2024 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f40c009358](https://linux-hardware.org/?probe=f40c009358) | Jan 11, 2024 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [029706288d](https://linux-hardware.org/?probe=029706288d) | Jan 04, 2024 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9dfa4f4d36](https://linux-hardware.org/?probe=9dfa4f4d36) | Jan 03, 2024 |
| Acer          | Aspire A515-43              | Notebook    | [68a2707c3f](https://linux-hardware.org/?probe=68a2707c3f) | Dec 31, 2023 |
| MSI           | MS-ACB31 100                | All in one  | [ffe63dc278](https://linux-hardware.org/?probe=ffe63dc278) | Dec 30, 2023 |
| Lenovo        | ThinkPad T460 20FMS0W32L    | Notebook    | [55200b6aa5](https://linux-hardware.org/?probe=55200b6aa5) | Dec 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [df3eb3c253](https://linux-hardware.org/?probe=df3eb3c253) | Dec 17, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [9a5c924695](https://linux-hardware.org/?probe=9a5c924695) | Nov 26, 2023 |
| Lenovo        | ThinkPad T500 20552CU       | Notebook    | [7389e9e37c](https://linux-hardware.org/?probe=7389e9e37c) | Nov 21, 2023 |
| Dell          | 0MNPJ9 A01                  | Desktop     | [80ded618fb](https://linux-hardware.org/?probe=80ded618fb) | Nov 19, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [90ce2b0711](https://linux-hardware.org/?probe=90ce2b0711) | Nov 13, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [0d65b73ae2](https://linux-hardware.org/?probe=0d65b73ae2) | Nov 07, 2023 |
| HP            | Compaq 6730s                | Notebook    | [073756d958](https://linux-hardware.org/?probe=073756d958) | Nov 03, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [2de4949247](https://linux-hardware.org/?probe=2de4949247) | Nov 01, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | Notebook    | [d267711f7e](https://linux-hardware.org/?probe=d267711f7e) | Nov 01, 2023 |
| AMI           | Intel                       | Notebook    | [42ebe1755f](https://linux-hardware.org/?probe=42ebe1755f) | Oct 30, 2023 |
| Dell          | 0K9T56 A00                  | All in one  | [e02693091f](https://linux-hardware.org/?probe=e02693091f) | Oct 25, 2023 |
| Dell          | 0K9T56 A00                  | All in one  | [cc8dcd6a8d](https://linux-hardware.org/?probe=cc8dcd6a8d) | Oct 24, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [f6a5fcd391](https://linux-hardware.org/?probe=f6a5fcd391) | Oct 21, 2023 |
| Acer          | Extensa 2519                | Notebook    | [4d8970a1f5](https://linux-hardware.org/?probe=4d8970a1f5) | Oct 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [20c026b8a7](https://linux-hardware.org/?probe=20c026b8a7) | Oct 16, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [da0024090d](https://linux-hardware.org/?probe=da0024090d) | Oct 16, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [e4f9055fce](https://linux-hardware.org/?probe=e4f9055fce) | Oct 09, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [e583e35b95](https://linux-hardware.org/?probe=e583e35b95) | Oct 03, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [538889d79f](https://linux-hardware.org/?probe=538889d79f) | Oct 03, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [d5e4f28683](https://linux-hardware.org/?probe=d5e4f28683) | Oct 02, 2023 |
| Fujitsu Si... | AMILO A1650G                | Notebook    | [ec61a60044](https://linux-hardware.org/?probe=ec61a60044) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c00e994c2c](https://linux-hardware.org/?probe=c00e994c2c) | Sep 21, 2023 |
| HP            | 620                         | Notebook    | [6fd1497e1a](https://linux-hardware.org/?probe=6fd1497e1a) | Sep 10, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [af96cda252](https://linux-hardware.org/?probe=af96cda252) | Sep 02, 2023 |
| Foxconn       | 2A92                        | Desktop     | [50ca8342d7](https://linux-hardware.org/?probe=50ca8342d7) | Sep 01, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [c8cc960675](https://linux-hardware.org/?probe=c8cc960675) | Aug 21, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [768e7b97fc](https://linux-hardware.org/?probe=768e7b97fc) | Aug 19, 2023 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [f059d25382](https://linux-hardware.org/?probe=f059d25382) | Aug 14, 2023 |
| Dell          | Latitude E5410              | Notebook    | [4ae8d448a2](https://linux-hardware.org/?probe=4ae8d448a2) | Aug 14, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [64a738d034](https://linux-hardware.org/?probe=64a738d034) | Aug 13, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [44556227ff](https://linux-hardware.org/?probe=44556227ff) | Aug 05, 2023 |
| OEM           | Intel H81                   | Desktop     | [82606b5050](https://linux-hardware.org/?probe=82606b5050) | Aug 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| Gigabyte      | B560 AORUS PRO AX           | Desktop     | [c7e057da76](https://linux-hardware.org/?probe=c7e057da76) | Aug 02, 2023 |
| HP            | 620                         | Notebook    | [4c04d9d11e](https://linux-hardware.org/?probe=4c04d9d11e) | Aug 01, 2023 |
| HP            | 620                         | Notebook    | [eafc7ac5c3](https://linux-hardware.org/?probe=eafc7ac5c3) | Aug 01, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [9042ebc249](https://linux-hardware.org/?probe=9042ebc249) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [f84a39b436](https://linux-hardware.org/?probe=f84a39b436) | Jul 31, 2023 |
| Intel         | JSL MRD                     | Desktop     | [feb19ee725](https://linux-hardware.org/?probe=feb19ee725) | Jul 29, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ca5990cfa3](https://linux-hardware.org/?probe=ca5990cfa3) | Jul 29, 2023 |
| ASUSTek       | LEUCITE3                    | Desktop     | [bb2046286f](https://linux-hardware.org/?probe=bb2046286f) | Jul 26, 2023 |
| ASUSTek       | LEUCITE3                    | Desktop     | [6ced09890f](https://linux-hardware.org/?probe=6ced09890f) | Jul 26, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [88f60930be](https://linux-hardware.org/?probe=88f60930be) | Jul 26, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [fd43074149](https://linux-hardware.org/?probe=fd43074149) | Jul 26, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [31c0d94d23](https://linux-hardware.org/?probe=31c0d94d23) | Jul 18, 2023 |
| CONNEX        | L1415-BAY                   | Notebook    | [8f5663e9c8](https://linux-hardware.org/?probe=8f5663e9c8) | Jul 18, 2023 |
| ASRock        | B660M-HDV                   | Desktop     | [3a0685bcf0](https://linux-hardware.org/?probe=3a0685bcf0) | Jul 18, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [782127b6f6](https://linux-hardware.org/?probe=782127b6f6) | Jul 17, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [d1ef43e488](https://linux-hardware.org/?probe=d1ef43e488) | Jul 16, 2023 |
| Dell          | System XPS L502X            | Notebook    | [e6b4c3cf4e](https://linux-hardware.org/?probe=e6b4c3cf4e) | Jul 12, 2023 |
| Acer          | Aspire ES1-511              | Notebook    | [1e7434d3b0](https://linux-hardware.org/?probe=1e7434d3b0) | Jul 10, 2023 |
| Medion        | MS-7667                     | Desktop     | [52ff08b634](https://linux-hardware.org/?probe=52ff08b634) | Jul 09, 2023 |
| HP            | 620                         | Notebook    | [5f88c564fd](https://linux-hardware.org/?probe=5f88c564fd) | Jul 08, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [ab21b766b6](https://linux-hardware.org/?probe=ab21b766b6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [5bba6eb442](https://linux-hardware.org/?probe=5bba6eb442) | Jul 07, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [68235880f7](https://linux-hardware.org/?probe=68235880f7) | Jul 06, 2023 |
| AOpen         | D1009 A1A4                  | Desktop     | [2819e086aa](https://linux-hardware.org/?probe=2819e086aa) | Jul 02, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [d04862302e](https://linux-hardware.org/?probe=d04862302e) | Jul 01, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [291c477bd0](https://linux-hardware.org/?probe=291c477bd0) | Jul 01, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [cd65c92d12](https://linux-hardware.org/?probe=cd65c92d12) | Jun 27, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [e3b1cdc71c](https://linux-hardware.org/?probe=e3b1cdc71c) | Jun 27, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f4540c6370](https://linux-hardware.org/?probe=f4540c6370) | Jun 27, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [cadc656340](https://linux-hardware.org/?probe=cadc656340) | Jun 25, 2023 |
| HP            | Spectre Folio Convertibl... | Convertible | [123d2215a1](https://linux-hardware.org/?probe=123d2215a1) | Jun 25, 2023 |
| Dell          | Latitude E6510              | Notebook    | [a85838194d](https://linux-hardware.org/?probe=a85838194d) | Jun 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [ed43d5454c](https://linux-hardware.org/?probe=ed43d5454c) | Jun 18, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [56c650c8b1](https://linux-hardware.org/?probe=56c650c8b1) | Jun 15, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [6e5323aa42](https://linux-hardware.org/?probe=6e5323aa42) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [fc4b07cbb0](https://linux-hardware.org/?probe=fc4b07cbb0) | Jun 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [85520c9a0b](https://linux-hardware.org/?probe=85520c9a0b) | Jun 08, 2023 |
| Dell          | Latitude E6540              | Notebook    | [30f20f78ac](https://linux-hardware.org/?probe=30f20f78ac) | Jun 08, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [4c56663011](https://linux-hardware.org/?probe=4c56663011) | Jun 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Dell          | Latitude E6510              | Notebook    | [49743c8db7](https://linux-hardware.org/?probe=49743c8db7) | Jun 04, 2023 |
| Dell          | Latitude E6510              | Notebook    | [51c45b0aa7](https://linux-hardware.org/?probe=51c45b0aa7) | Jun 04, 2023 |
| MSI           | U200                        | Notebook    | [01900b8117](https://linux-hardware.org/?probe=01900b8117) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [51d10ac11e](https://linux-hardware.org/?probe=51d10ac11e) | Jun 02, 2023 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [c64fbbcad9](https://linux-hardware.org/?probe=c64fbbcad9) | Jun 02, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [c46684adac](https://linux-hardware.org/?probe=c46684adac) | Jun 02, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [7070e55aa0](https://linux-hardware.org/?probe=7070e55aa0) | Jun 01, 2023 |
| Dell          | Latitude 5540               | Notebook    | [98ec8ec8bf](https://linux-hardware.org/?probe=98ec8ec8bf) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [4a2e70149f](https://linux-hardware.org/?probe=4a2e70149f) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [b8fb5e55bc](https://linux-hardware.org/?probe=b8fb5e55bc) | Jun 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [351ca28b27](https://linux-hardware.org/?probe=351ca28b27) | May 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | Notebook    | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| Dell          | Latitude E6510              | Notebook    | [9edaeb2ffa](https://linux-hardware.org/?probe=9edaeb2ffa) | May 25, 2023 |
| Sony          | SVE1513Q1ESI                | Notebook    | [422e8954f2](https://linux-hardware.org/?probe=422e8954f2) | May 24, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [ef088af2df](https://linux-hardware.org/?probe=ef088af2df) | May 23, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [28a8978593](https://linux-hardware.org/?probe=28a8978593) | May 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| Dell          | Latitude E6510              | Notebook    | [342b8d094e](https://linux-hardware.org/?probe=342b8d094e) | May 20, 2023 |
| Dell          | Latitude E6510              | Notebook    | [4d606396f8](https://linux-hardware.org/?probe=4d606396f8) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [5ae19394fc](https://linux-hardware.org/?probe=5ae19394fc) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [14548bc77a](https://linux-hardware.org/?probe=14548bc77a) | May 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e6746606b4](https://linux-hardware.org/?probe=e6746606b4) | May 19, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [5ca1acbf9b](https://linux-hardware.org/?probe=5ca1acbf9b) | May 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [58066198c4](https://linux-hardware.org/?probe=58066198c4) | May 18, 2023 |
| Dell          | Latitude 3190               | Notebook    | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [4c33c99aab](https://linux-hardware.org/?probe=4c33c99aab) | May 14, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [d3107c9603](https://linux-hardware.org/?probe=d3107c9603) | May 14, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3bc96663a8](https://linux-hardware.org/?probe=3bc96663a8) | May 14, 2023 |
| ASUSTek       | X202E                       | Notebook    | [d6b7617a17](https://linux-hardware.org/?probe=d6b7617a17) | May 14, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [08afd40365](https://linux-hardware.org/?probe=08afd40365) | May 13, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [ebd2a32ce2](https://linux-hardware.org/?probe=ebd2a32ce2) | May 12, 2023 |
| Acer          | Extensa 5220                | Notebook    | [935b52f12c](https://linux-hardware.org/?probe=935b52f12c) | May 12, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [352c0902e9](https://linux-hardware.org/?probe=352c0902e9) | May 11, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [81c255952d](https://linux-hardware.org/?probe=81c255952d) | May 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0GK0... | Notebook    | [177f30243c](https://linux-hardware.org/?probe=177f30243c) | May 08, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [f894b9a2c4](https://linux-hardware.org/?probe=f894b9a2c4) | May 07, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [af9c3172bc](https://linux-hardware.org/?probe=af9c3172bc) | May 05, 2023 |
| HP            | Pro Tablet 10 EE G1         | Notebook    | [6af53fb237](https://linux-hardware.org/?probe=6af53fb237) | May 05, 2023 |
| Lenovo        | ThinkPad T460s 20F9003GU... | Notebook    | [7a570efe74](https://linux-hardware.org/?probe=7a570efe74) | May 05, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [8349b363f4](https://linux-hardware.org/?probe=8349b363f4) | May 03, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [49971d9c29](https://linux-hardware.org/?probe=49971d9c29) | May 03, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [6d2d5b74d2](https://linux-hardware.org/?probe=6d2d5b74d2) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e8721751c6](https://linux-hardware.org/?probe=e8721751c6) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e426e8e40b](https://linux-hardware.org/?probe=e426e8e40b) | May 03, 2023 |
| Lenovo        | ThinkPad X260 20F5S89L02    | Notebook    | [4e2f57ccc3](https://linux-hardware.org/?probe=4e2f57ccc3) | May 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [a36c4e671d](https://linux-hardware.org/?probe=a36c4e671d) | May 02, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [f62abcbed6](https://linux-hardware.org/?probe=f62abcbed6) | May 02, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [2d1086090c](https://linux-hardware.org/?probe=2d1086090c) | May 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [e812a255a4](https://linux-hardware.org/?probe=e812a255a4) | May 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [539369db0e](https://linux-hardware.org/?probe=539369db0e) | Apr 28, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [4939e609de](https://linux-hardware.org/?probe=4939e609de) | Apr 24, 2023 |
| HP            | G42                         | Notebook    | [58b0a0981e](https://linux-hardware.org/?probe=58b0a0981e) | Apr 23, 2023 |
| HP            | 090Ch                       | Desktop     | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [acb9cde3d7](https://linux-hardware.org/?probe=acb9cde3d7) | Apr 23, 2023 |
| Gateway       | DX4860                      | Desktop     | [5583641f1b](https://linux-hardware.org/?probe=5583641f1b) | Apr 22, 2023 |
| Compal        | HEL81I                      | Notebook    | [426788b00c](https://linux-hardware.org/?probe=426788b00c) | Apr 22, 2023 |
| Google        | Akali 360                   | Notebook    | [2d18714bb2](https://linux-hardware.org/?probe=2d18714bb2) | Apr 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1B30... | Notebook    | [c0207e5f9a](https://linux-hardware.org/?probe=c0207e5f9a) | Apr 19, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [843dd1e105](https://linux-hardware.org/?probe=843dd1e105) | Apr 18, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [c271ba95b9](https://linux-hardware.org/?probe=c271ba95b9) | Apr 16, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [494fc3e648](https://linux-hardware.org/?probe=494fc3e648) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [3d53b9ee9e](https://linux-hardware.org/?probe=3d53b9ee9e) | Apr 12, 2023 |
| HP            | 3646h                       | Desktop     | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c2a70674ac](https://linux-hardware.org/?probe=c2a70674ac) | Apr 10, 2023 |
| Lenovo        | ThinkPad X220 4290WC7       | Notebook    | [07ed4faaa0](https://linux-hardware.org/?probe=07ed4faaa0) | Apr 10, 2023 |
| HP            | 18E5                        | Desktop     | [441d2678ff](https://linux-hardware.org/?probe=441d2678ff) | Apr 07, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [aea33c89a1](https://linux-hardware.org/?probe=aea33c89a1) | Apr 05, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [86d8d7f80f](https://linux-hardware.org/?probe=86d8d7f80f) | Apr 05, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a1fa664431](https://linux-hardware.org/?probe=a1fa664431) | Apr 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9a5c9ee256](https://linux-hardware.org/?probe=9a5c9ee256) | Apr 02, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [ef684c34bb](https://linux-hardware.org/?probe=ef684c34bb) | Mar 28, 2023 |
| HP            | 3029h                       | Desktop     | [153b913406](https://linux-hardware.org/?probe=153b913406) | Mar 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| Sony          | VPCCB32FD                   | Notebook    | [20d8516896](https://linux-hardware.org/?probe=20d8516896) | Mar 26, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [498bb39808](https://linux-hardware.org/?probe=498bb39808) | Mar 24, 2023 |
| Unknown       | GB01                        | Desktop     | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| HP            | 3048h                       | Desktop     | [cd326ce9fa](https://linux-hardware.org/?probe=cd326ce9fa) | Mar 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [978df2886a](https://linux-hardware.org/?probe=978df2886a) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ac5495bdb4](https://linux-hardware.org/?probe=ac5495bdb4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [45d6f54263](https://linux-hardware.org/?probe=45d6f54263) | Mar 19, 2023 |
| Samsung       | 950QDB                      | Convertible | [e16175f1c5](https://linux-hardware.org/?probe=e16175f1c5) | Mar 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [12e9972d5a](https://linux-hardware.org/?probe=12e9972d5a) | Mar 15, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [46cb84be25](https://linux-hardware.org/?probe=46cb84be25) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [9f3f315f73](https://linux-hardware.org/?probe=9f3f315f73) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [42653f8c2a](https://linux-hardware.org/?probe=42653f8c2a) | Mar 14, 2023 |
| MSI           | CSM-H87M-G43                | Desktop     | [9df13e200e](https://linux-hardware.org/?probe=9df13e200e) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [7ccc0f584e](https://linux-hardware.org/?probe=7ccc0f584e) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | Desktop     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| Dell          | Latitude 3190               | Notebook    | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fd0eabacbf](https://linux-hardware.org/?probe=fd0eabacbf) | Mar 08, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | Notebook    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [153652da71](https://linux-hardware.org/?probe=153652da71) | Mar 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| HP            | 255 G3                      | Notebook    | [9ccab85062](https://linux-hardware.org/?probe=9ccab85062) | Mar 04, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [a84948f124](https://linux-hardware.org/?probe=a84948f124) | Mar 04, 2023 |
| HP            | 8184 X4                     | Desktop     | [b42f6862c7](https://linux-hardware.org/?probe=b42f6862c7) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 620                         | Notebook    | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [5718d685e4](https://linux-hardware.org/?probe=5718d685e4) | Mar 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [5fe3c354ff](https://linux-hardware.org/?probe=5fe3c354ff) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [a15227fc75](https://linux-hardware.org/?probe=a15227fc75) | Mar 02, 2023 |
| Dell          | Latitude 3190               | Notebook    | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | 255 G3                      | Notebook    | [49dccf5753](https://linux-hardware.org/?probe=49dccf5753) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [73570a1c9a](https://linux-hardware.org/?probe=73570a1c9a) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [e82b3753f7](https://linux-hardware.org/?probe=e82b3753f7) | Feb 26, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [b6321ee5a4](https://linux-hardware.org/?probe=b6321ee5a4) | Feb 25, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [efc95d4697](https://linux-hardware.org/?probe=efc95d4697) | Feb 25, 2023 |
| Unknown       | 1.0                         | Desktop     | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [e386073c5d](https://linux-hardware.org/?probe=e386073c5d) | Feb 23, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [0e9172bdd5](https://linux-hardware.org/?probe=0e9172bdd5) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [adc356a0a8](https://linux-hardware.org/?probe=adc356a0a8) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d09dc2494a](https://linux-hardware.org/?probe=d09dc2494a) | Feb 21, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | ProBook 445 G1              | Notebook    | [bcd5c952f1](https://linux-hardware.org/?probe=bcd5c952f1) | Feb 18, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [351a527308](https://linux-hardware.org/?probe=351a527308) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [aba30bb2d8](https://linux-hardware.org/?probe=aba30bb2d8) | Feb 17, 2023 |
| RTD Embedd... | CMA34CR                     | Notebook    | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [db10d61562](https://linux-hardware.org/?probe=db10d61562) | Feb 16, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [9d060a9cc6](https://linux-hardware.org/?probe=9d060a9cc6) | Feb 15, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [0cbe95253a](https://linux-hardware.org/?probe=0cbe95253a) | Feb 15, 2023 |
| Linx          | LINX1010B                   | Notebook    | [5ca377461f](https://linux-hardware.org/?probe=5ca377461f) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [482c922bbc](https://linux-hardware.org/?probe=482c922bbc) | Feb 14, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dcb95dba09](https://linux-hardware.org/?probe=dcb95dba09) | Feb 12, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [86103b5293](https://linux-hardware.org/?probe=86103b5293) | Feb 12, 2023 |
| Medion        | P6634                       | Notebook    | [ec0002869f](https://linux-hardware.org/?probe=ec0002869f) | Feb 11, 2023 |
| Medion        | P6634                       | Notebook    | [15c3260ecf](https://linux-hardware.org/?probe=15c3260ecf) | Feb 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [13492935fd](https://linux-hardware.org/?probe=13492935fd) | Feb 09, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [d32909e1a4](https://linux-hardware.org/?probe=d32909e1a4) | Feb 09, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [700f0ded17](https://linux-hardware.org/?probe=700f0ded17) | Feb 08, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [b4c5f2e2de](https://linux-hardware.org/?probe=b4c5f2e2de) | Feb 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [11f3874a6f](https://linux-hardware.org/?probe=11f3874a6f) | Feb 07, 2023 |
| HP            | 450                         | Notebook    | [26d3505372](https://linux-hardware.org/?probe=26d3505372) | Feb 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [48f423dfae](https://linux-hardware.org/?probe=48f423dfae) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [7e94a2328d](https://linux-hardware.org/?probe=7e94a2328d) | Feb 05, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [42e242e6bf](https://linux-hardware.org/?probe=42e242e6bf) | Feb 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [793f52c99a](https://linux-hardware.org/?probe=793f52c99a) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| ECS           | P4M800PRO-M                 | Desktop     | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [dd017ac78a](https://linux-hardware.org/?probe=dd017ac78a) | Jan 31, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a32a9ba13a](https://linux-hardware.org/?probe=a32a9ba13a) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [1d28352c0f](https://linux-hardware.org/?probe=1d28352c0f) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| BESSTAR Te... | UM340                       | Desktop     | [77efbbb270](https://linux-hardware.org/?probe=77efbbb270) | Jan 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [e81c0bcfc4](https://linux-hardware.org/?probe=e81c0bcfc4) | Jan 22, 2023 |
| AMI           | Intel                       | Notebook    | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [7671c99c3c](https://linux-hardware.org/?probe=7671c99c3c) | Jan 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| HP            | 3396                        | Desktop     | [2085b91098](https://linux-hardware.org/?probe=2085b91098) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [4a07474fa4](https://linux-hardware.org/?probe=4a07474fa4) | Jan 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge 031925U       | Notebook    | [95feaf21b4](https://linux-hardware.org/?probe=95feaf21b4) | Jan 07, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Toshiba       | Satellite M70               | Notebook    | [616dbdfa63](https://linux-hardware.org/?probe=616dbdfa63) | Jan 05, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| Dell          | Latitude 3190               | Notebook    | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6c8ec40821](https://linux-hardware.org/?probe=6c8ec40821) | Dec 25, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c195f58592](https://linux-hardware.org/?probe=c195f58592) | Dec 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [148add29a4](https://linux-hardware.org/?probe=148add29a4) | Dec 24, 2022 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | Desktop     | [70e125f0d0](https://linux-hardware.org/?probe=70e125f0d0) | Dec 23, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | Notebook    | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [06e7a6dfe7](https://linux-hardware.org/?probe=06e7a6dfe7) | Dec 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [a583a55071](https://linux-hardware.org/?probe=a583a55071) | Dec 10, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [2e76f24d6a](https://linux-hardware.org/?probe=2e76f24d6a) | Dec 09, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [36b349ff7f](https://linux-hardware.org/?probe=36b349ff7f) | Dec 08, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6487bbd7b7](https://linux-hardware.org/?probe=6487bbd7b7) | Dec 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | Desktop     | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [057b0039b7](https://linux-hardware.org/?probe=057b0039b7) | Dec 01, 2022 |
| HP            | 304Ah                       | Desktop     | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b47217fa0c](https://linux-hardware.org/?probe=b47217fa0c) | Nov 25, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3f08c2fb11](https://linux-hardware.org/?probe=3f08c2fb11) | Nov 25, 2022 |
| Sony          | VGN-TZ3RXN_B                | Notebook    | [5986f007c8](https://linux-hardware.org/?probe=5986f007c8) | Nov 22, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| GEO           | GeoFlex 340                 | Convertible | [6e930633c0](https://linux-hardware.org/?probe=6e930633c0) | Nov 18, 2022 |
| Dell          | 0J051K A00                  | Server      | [cb579ef51b](https://linux-hardware.org/?probe=cb579ef51b) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [9884754d7b](https://linux-hardware.org/?probe=9884754d7b) | Nov 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [cb36e9d15c](https://linux-hardware.org/?probe=cb36e9d15c) | Nov 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [91d85f8376](https://linux-hardware.org/?probe=91d85f8376) | Nov 05, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [9c72952af7](https://linux-hardware.org/?probe=9c72952af7) | Nov 04, 2022 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [c165c40a7e](https://linux-hardware.org/?probe=c165c40a7e) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | Notebook    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Vulcan Ele... | Excursion XB                | Notebook    | [30ceac1216](https://linux-hardware.org/?probe=30ceac1216) | Oct 31, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [6383143b5b](https://linux-hardware.org/?probe=6383143b5b) | Oct 28, 2022 |
| Biostar       | H61MH                       | Desktop     | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [226e4471e1](https://linux-hardware.org/?probe=226e4471e1) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | Desktop     | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [59dabaff86](https://linux-hardware.org/?probe=59dabaff86) | Oct 23, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d34df28814](https://linux-hardware.org/?probe=d34df28814) | Oct 22, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [aa571dded9](https://linux-hardware.org/?probe=aa571dded9) | Oct 22, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [c389b44ab5](https://linux-hardware.org/?probe=c389b44ab5) | Oct 21, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [95ca32a110](https://linux-hardware.org/?probe=95ca32a110) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e33a95e0b0](https://linux-hardware.org/?probe=e33a95e0b0) | Oct 18, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [b6c2cf5b2e](https://linux-hardware.org/?probe=b6c2cf5b2e) | Oct 17, 2022 |
| Dell          | Latitude 3190               | Notebook    | [342d7acb67](https://linux-hardware.org/?probe=342d7acb67) | Oct 17, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [1f6ff0e213](https://linux-hardware.org/?probe=1f6ff0e213) | Oct 17, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [09af41cbf8](https://linux-hardware.org/?probe=09af41cbf8) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b3267ce847](https://linux-hardware.org/?probe=b3267ce847) | Oct 15, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [209d243342](https://linux-hardware.org/?probe=209d243342) | Oct 15, 2022 |
| Pegatron      | NARRA3                      | Desktop     | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Medion        | E7424 MD60750               | Notebook    | [7c9ea600ad](https://linux-hardware.org/?probe=7c9ea600ad) | Oct 11, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [f2c440fdf6](https://linux-hardware.org/?probe=f2c440fdf6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [8159009c50](https://linux-hardware.org/?probe=8159009c50) | Oct 05, 2022 |
| Google        | Setzer                      | Notebook    | [6bafaabd48](https://linux-hardware.org/?probe=6bafaabd48) | Oct 04, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f97d2b97ad](https://linux-hardware.org/?probe=f97d2b97ad) | Oct 01, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | Notebook    | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| HP            | 1632                        | Desktop     | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | Notebook    | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | Notebook    | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [83e026f682](https://linux-hardware.org/?probe=83e026f682) | Aug 12, 2022 |
| Dell          | System XPS 15Z              | Notebook    | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | Notebook    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | Notebook    | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| MP            | MS-7848                     | Desktop     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Dell          | 0DR845                      | Desktop     | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| Alienware     | 13 R2                       | Notebook    | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | Notebook    | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [77c632ea8e](https://linux-hardware.org/?probe=77c632ea8e) | Jul 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | Desktop     | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | Notebook    | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | Notebook    | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | Notebook    | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c21cd1f8f3](https://linux-hardware.org/?probe=c21cd1f8f3) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | Notebook    | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| AZW           | SER                         | Mini pc     | [9da3c6ca34](https://linux-hardware.org/?probe=9da3c6ca34) | May 18, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | Notebook    | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | Notebook    | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | Desktop     | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [7cc89d3cba](https://linux-hardware.org/?probe=7cc89d3cba) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [5cd6adf199](https://linux-hardware.org/?probe=5cd6adf199) | Apr 14, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [084e2350e9](https://linux-hardware.org/?probe=084e2350e9) | Apr 05, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| Sony          | SVE1513Q1ESI                | Notebook    | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/MX_21/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 6.0.0-6mx-amd64            | 42        | 9.31%   |
| 5.10.0-21-amd64            | 40        | 8.87%   |
| 5.10.0-23-amd64            | 25        | 5.54%   |
| 5.10.0-20-amd64            | 24        | 5.32%   |
| 5.10.0-18-amd64            | 21        | 4.66%   |
| 5.10.0-13-amd64            | 20        | 4.43%   |
| 5.14.0-4mx-amd64           | 19        | 4.21%   |
| 5.10.0-9-amd64             | 18        | 3.99%   |
| 5.10.0-19-amd64            | 18        | 3.99%   |
| 5.16.0-5mx-amd64           | 15        | 3.33%   |
| 5.10.0-16-amd64            | 13        | 2.88%   |
| 6.0.0-10.1-liquorix-amd64  | 10        | 2.22%   |
| 5.18.0-4mx-amd64           | 10        | 2.22%   |
| 5.10.0-28-amd64            | 8         | 1.77%   |
| 5.10.0-11-amd64            | 8         | 1.77%   |
| 5.10.0-22-amd64            | 7         | 1.55%   |
| 5.10.0-14-amd64            | 7         | 1.55%   |
| 5.19.0-2mx-amd64           | 6         | 1.33%   |
| 5.10.0-15-amd64            | 6         | 1.33%   |
| 6.0.0-4mx-amd64            | 5         | 1.11%   |
| 5.10.0-26-amd64            | 5         | 1.11%   |
| 5.10.0-17-amd64            | 4         | 0.89%   |
| 5.10.0-10-amd64            | 4         | 0.89%   |
| 6.1.0-9mx-ahs-amd64        | 3         | 0.67%   |
| 6.0.0-3mx-amd64            | 3         | 0.67%   |
| 5.16.0-6mx-amd64           | 3         | 0.67%   |
| 5.16.0-18.1-liquorix-amd64 | 3         | 0.67%   |
| 5.10.0-27-amd64            | 3         | 0.67%   |
| 5.10.0-25-amd64            | 3         | 0.67%   |
| 5.10.0-20-686-pae          | 3         | 0.67%   |
| 6.7.12-1-liquorix-amd64    | 2         | 0.44%   |
| 6.1.15-2-liquorix-amd64    | 2         | 0.44%   |
| 6.1.0-8mx-ahs-amd64        | 2         | 0.44%   |
| 6.1.0-4mx-amd64            | 2         | 0.44%   |
| 6.1.0-2mx-amd64            | 2         | 0.44%   |
| 5.19.0-17.2-liquorix-amd64 | 2         | 0.44%   |
| 5.17.0-3mx-amd64           | 2         | 0.44%   |
| 5.17.0-2mx-amd64           | 2         | 0.44%   |
| 5.16.0-4mx-amd64           | 2         | 0.44%   |
| 5.14.0-3mx-amd64           | 2         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 248       | 57.27%  |
| 6.0.0    | 63        | 14.55%  |
| 5.16.0   | 24        | 5.54%   |
| 5.14.0   | 22        | 5.08%   |
| 6.1.0    | 14        | 3.23%   |
| 5.19.0   | 12        | 2.77%   |
| 5.18.0   | 12        | 2.77%   |
| 5.17.0   | 7         | 1.62%   |
| 5.15.0   | 3         | 0.69%   |
| 6.7.12   | 2         | 0.46%   |
| 6.5.0    | 2         | 0.46%   |
| 6.4.0    | 2         | 0.46%   |
| 6.1.15   | 2         | 0.46%   |
| 4.19.0   | 2         | 0.46%   |
| 6.7.9    | 1         | 0.23%   |
| 6.6.0    | 1         | 0.23%   |
| 6.5.9    | 1         | 0.23%   |
| 6.4.3    | 1         | 0.23%   |
| 6.3.0    | 1         | 0.23%   |
| 6.2.7    | 1         | 0.23%   |
| 6.2.14   | 1         | 0.23%   |
| 6.11.2   | 1         | 0.23%   |
| 6.11.10  | 1         | 0.23%   |
| 6.1.12   | 1         | 0.23%   |
| 6.0.5    | 1         | 0.23%   |
| 5.13.0   | 1         | 0.23%   |
| 5.10.82  | 1         | 0.23%   |
| 5.10.52  | 1         | 0.23%   |
| 5.10.142 | 1         | 0.23%   |
| 5.10.113 | 1         | 0.23%   |
| 5.10.111 | 1         | 0.23%   |
| Unknown  | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 253       | 58.56%  |
| 6.0     | 64        | 14.81%  |
| 5.16    | 24        | 5.56%   |
| 5.14    | 22        | 5.09%   |
| 6.1     | 17        | 3.94%   |
| 5.19    | 12        | 2.78%   |
| 5.18    | 12        | 2.78%   |
| 5.17    | 7         | 1.62%   |
| 6.5     | 3         | 0.69%   |
| 6.4     | 3         | 0.69%   |
| 5.15    | 3         | 0.69%   |
| 6.7     | 2         | 0.46%   |
| 6.2     | 2         | 0.46%   |
| 6.11    | 2         | 0.46%   |
| 4.19    | 2         | 0.46%   |
| 6.6     | 1         | 0.23%   |
| 6.3     | 1         | 0.23%   |
| 5.13    | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 402       | 95.94%  |
| i686   | 17        | 4.06%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 311       | 73.18%  |
| KDE5             | 84        | 19.76%  |
| lightdm-xsession | 6         | 1.41%   |
| Unknown          | 5         | 1.18%   |
| GNOME            | 4         | 0.94%   |
| Budgie           | 4         | 0.94%   |
| i3               | 3         | 0.71%   |
| LXQt             | 2         | 0.47%   |
| fluxbox          | 2         | 0.47%   |
| X-Cinnamon       | 1         | 0.24%   |
| Trinity          | 1         | 0.24%   |
| MATE             | 1         | 0.24%   |
| GNOME Classic    | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 414       | 98.81%  |
| Tty     | 4         | 0.95%   |
| Wayland | 1         | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 331       | 78.62%  |
| SDDM    | 79        | 18.76%  |
| SLiM    | 7         | 1.66%   |
| Unknown | 2         | 0.48%   |
| GDM3    | 1         | 0.24%   |
| GDM     | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 198       | 47.03%  |
| de_DE   | 52        | 12.35%  |
| en_GB   | 24        | 5.7%    |
| it_IT   | 23        | 5.46%   |
| ru_RU   | 13        | 3.09%   |
| fr_FR   | 12        | 2.85%   |
| en_AU   | 11        | 2.61%   |
| es_ES   | 9         | 2.14%   |
| pl_PL   | 8         | 1.9%    |
| es_AR   | 8         | 1.9%    |
| de_CH   | 6         | 1.43%   |
| pt_BR   | 5         | 1.19%   |
| es_MX   | 4         | 0.95%   |
| en_NZ   | 4         | 0.95%   |
| Unknown | 4         | 0.95%   |
| tr_TR   | 3         | 0.71%   |
| sv_SE   | 3         | 0.71%   |
| nl_NL   | 3         | 0.71%   |
| hu_HU   | 3         | 0.71%   |
| fi_FI   | 3         | 0.71%   |
| es_VE   | 3         | 0.71%   |
| sk_SK   | 2         | 0.48%   |
| fr_CA   | 2         | 0.48%   |
| es_CO   | 2         | 0.48%   |
| en_CA   | 2         | 0.48%   |
| bg_BG   | 2         | 0.48%   |
| ro_RO   | 1         | 0.24%   |
| nl_BE   | 1         | 0.24%   |
| nb_NO   | 1         | 0.24%   |
| id_ID   | 1         | 0.24%   |
| hr_HR   | 1         | 0.24%   |
| fr_BE   | 1         | 0.24%   |
| eu_ES   | 1         | 0.24%   |
| es_UY   | 1         | 0.24%   |
| es_PE   | 1         | 0.24%   |
| en_IE   | 1         | 0.24%   |
| el_GR   | 1         | 0.24%   |
| da_DK   | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 264       | 63.01%  |
| BIOS | 155       | 36.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 362       | 85.78%  |
| Overlay  | 39        | 9.24%   |
| Btrfs    | 15        | 3.55%   |
| Xfs      | 2         | 0.47%   |
| Tmpfs    | 1         | 0.24%   |
| Reiserfs | 1         | 0.24%   |
| F2fs     | 1         | 0.24%   |
| Ext3     | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 294       | 70%     |
| MBR     | 124       | 29.52%  |
| Unknown | 2         | 0.48%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 306       | 72%     |
| Yes       | 119       | 28%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 236       | 56.06%  |
| Yes       | 185       | 43.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 63        | 15.04%  |
| Lenovo                               | 60        | 14.32%  |
| ASUSTek Computer                     | 60        | 14.32%  |
| Dell                                 | 45        | 10.74%  |
| Acer                                 | 27        | 6.44%   |
| Apple                                | 21        | 5.01%   |
| MSI                                  | 18        | 4.3%    |
| Gigabyte Technology                  | 17        | 4.06%   |
| ASRock                               | 13        | 3.1%    |
| Sony                                 | 8         | 1.91%   |
| Medion                               | 6         | 1.43%   |
| Intel                                | 6         | 1.43%   |
| Unknown                              | 6         | 1.43%   |
| Toshiba                              | 4         | 0.95%   |
| Samsung Electronics                  | 4         | 0.95%   |
| Fujitsu Siemens                      | 4         | 0.95%   |
| Alienware                            | 4         | 0.95%   |
| Fujitsu                              | 3         | 0.72%   |
| Foxconn                              | 3         | 0.72%   |
| ZOTAC                                | 2         | 0.48%   |
| TUXEDO                               | 2         | 0.48%   |
| Pegatron                             | 2         | 0.48%   |
| Notebook                             | 2         | 0.48%   |
| Microsoft                            | 2         | 0.48%   |
| Gateway                              | 2         | 0.48%   |
| Chuwi                                | 2         | 0.48%   |
| Biostar                              | 2         | 0.48%   |
| AZW                                  | 2         | 0.48%   |
| win element                          | 1         | 0.24%   |
| Vulcan Electronics                   | 1         | 0.24%   |
| Sun Microsystems                     | 1         | 0.24%   |
| SIRAGON                              | 1         | 0.24%   |
| Shenzhen Wangang Technology          | 1         | 0.24%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.24%   |
| SANTECH                              | 1         | 0.24%   |
| RTD Embedded Technologies            | 1         | 0.24%   |
| Razer                                | 1         | 0.24%   |
| OEM                                  | 1         | 0.24%   |
| MP                                   | 1         | 0.24%   |
| Linx                                 | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| ASUS All Series                              | 9         | 2.15%   |
| Unknown                                      | 8         | 1.91%   |
| MSI MS-7C91                                  | 2         | 0.48%   |
| HP ProBook 450 G1                            | 2         | 0.48%   |
| HP Pavilion Laptop 15-eh1xxx                 | 2         | 0.48%   |
| HP Laptop 17-ak0xx                           | 2         | 0.48%   |
| Gigabyte GA-MA785GM-US2H                     | 2         | 0.48%   |
| Dell OptiPlex 9020                           | 2         | 0.48%   |
| Dell OptiPlex 780                            | 2         | 0.48%   |
| Dell OptiPlex 755                            | 2         | 0.48%   |
| Dell Latitude E5570                          | 2         | 0.48%   |
| Chuwi GemiBook Pro                           | 2         | 0.48%   |
| AZW SER                                      | 2         | 0.48%   |
| ASUS X205TA                                  | 2         | 0.48%   |
| ASUS ROG Maximus XIII HERO                   | 2         | 0.48%   |
| Apple Macmini8,1                             | 2         | 0.48%   |
| Apple MacBookAir7,2                          | 2         | 0.48%   |
| Acer Nitro AN515-55                          | 2         | 0.48%   |
| ZOTAC ZBOX-ECM73070C/53060C                  | 1         | 0.24%   |
| win element MoreFine S500+                   | 1         | 0.24%   |
| Vulcan Excursion XB                          | 1         | 0.24%   |
| TUXEDO N7x0WU                                | 1         | 0.24%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)           | 1         | 0.24%   |
| Toshiba Satellite M70                        | 1         | 0.24%   |
| Toshiba Satellite L650                       | 1         | 0.24%   |
| Toshiba Satellite C845                       | 1         | 0.24%   |
| Toshiba PORTEGE Z30-C                        | 1         | 0.24%   |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 0.24%   |
| Sony VPCYB3V1E                               | 1         | 0.24%   |
| Sony VPCSB1V9R                               | 1         | 0.24%   |
| Sony VPCF119FX                               | 1         | 0.24%   |
| Sony VPCEH2N1E                               | 1         | 0.24%   |
| Sony VPCEC3S1E                               | 1         | 0.24%   |
| Sony VPCCB32FD                               | 1         | 0.24%   |
| Sony VGN-TZ3RXN_B                            | 1         | 0.24%   |
| Sony SVE1513Q1ESI                            | 1         | 0.24%   |
| SIRAGON AIO-5150                             | 1         | 0.24%   |
| Shenzhen Wangang AERO 2 Pro                  | 1         | 0.24%   |
| Shenzhen Meigao Electronic Equipment UM450   | 1         | 0.24%   |
| SANTECH X170KM-G                             | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 30        | 7.16%   |
| Acer Aspire              | 18        | 4.3%    |
| Dell Latitude            | 12        | 2.86%   |
| Dell Inspiron            | 10        | 2.39%   |
| Dell OptiPlex            | 9         | 2.15%   |
| ASUS All                 | 9         | 2.15%   |
| Lenovo IdeaPad           | 8         | 1.91%   |
| HP Laptop                | 8         | 1.91%   |
| HP EliteBook             | 8         | 1.91%   |
| HP Compaq                | 8         | 1.91%   |
| Unknown                  | 8         | 1.91%   |
| HP ProBook               | 7         | 1.67%   |
| ASUS VivoBook            | 6         | 1.43%   |
| ASUS ROG                 | 5         | 1.19%   |
| HP Pavilion              | 4         | 0.95%   |
| Dell Vostro              | 4         | 0.95%   |
| Dell Precision           | 4         | 0.95%   |
| ASUS TUF                 | 4         | 0.95%   |
| Toshiba Satellite        | 3         | 0.72%   |
| Lenovo ThinkBook         | 3         | 0.72%   |
| HP ZBook                 | 3         | 0.72%   |
| HP 250                   | 3         | 0.72%   |
| Dell System              | 3         | 0.72%   |
| ASUS PRIME               | 3         | 0.72%   |
| ASUS ASUS                | 3         | 0.72%   |
| Acer Swift               | 3         | 0.72%   |
| Acer Nitro               | 3         | 0.72%   |
| MSI MS-7C91              | 2         | 0.48%   |
| Microsoft Surface        | 2         | 0.48%   |
| Lenovo Yoga              | 2         | 0.48%   |
| Lenovo V17               | 2         | 0.48%   |
| Lenovo ThinkCentre       | 2         | 0.48%   |
| Lenovo Legion            | 2         | 0.48%   |
| Lenovo IdeaCentre        | 2         | 0.48%   |
| HP Spectre               | 2         | 0.48%   |
| HP ProLiant              | 2         | 0.48%   |
| HP ENVY                  | 2         | 0.48%   |
| HP 255                   | 2         | 0.48%   |
| Gigabyte GA-MA785GM-US2H | 2         | 0.48%   |
| Gigabyte B550M           | 2         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 56        | 13.37%  |
| 2019    | 32        | 7.64%   |
| 2020    | 30        | 7.16%   |
| 2013    | 30        | 7.16%   |
| 2022    | 29        | 6.92%   |
| 2011    | 29        | 6.92%   |
| 2012    | 27        | 6.44%   |
| 2016    | 26        | 6.21%   |
| 2018    | 25        | 5.97%   |
| 2010    | 25        | 5.97%   |
| 2015    | 22        | 5.25%   |
| 2014    | 21        | 5.01%   |
| 2008    | 16        | 3.82%   |
| 2007    | 15        | 3.58%   |
| 2017    | 12        | 2.86%   |
| 2009    | 11        | 2.63%   |
| 2023    | 4         | 0.95%   |
| 2006    | 4         | 0.95%   |
| 2005    | 3         | 0.72%   |
| 2004    | 1         | 0.24%   |
| Unknown | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 250       | 59.67%  |
| Desktop     | 130       | 31.03%  |
| Convertible | 11        | 2.63%   |
| Mini pc     | 11        | 2.63%   |
| All in one  | 9         | 2.15%   |
| Tablet      | 4         | 0.95%   |
| Server      | 4         | 0.95%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 416       | 99.28%  |
| Enabled  | 3         | 0.72%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 418       | 99.76%  |
| Yes  | 1         | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 119       | 28.27%  |
| 8.01-16.0   | 81        | 19.24%  |
| 16.01-24.0  | 66        | 15.68%  |
| 3.01-4.0    | 53        | 12.59%  |
| 32.01-64.0  | 47        | 11.16%  |
| 1.01-2.0    | 24        | 5.7%    |
| 64.01-256.0 | 10        | 2.38%   |
| 24.01-32.0  | 9         | 2.14%   |
| 2.01-3.0    | 8         | 1.9%    |
| 0.51-1.0    | 4         | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 156       | 35.62%  |
| 2.01-3.0   | 125       | 28.54%  |
| 3.01-4.0   | 62        | 14.16%  |
| 4.01-8.0   | 53        | 12.1%   |
| 0.51-1.0   | 25        | 5.71%   |
| 8.01-16.0  | 13        | 2.97%   |
| 16.01-24.0 | 2         | 0.46%   |
| 0.01-0.5   | 2         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 246       | 58.02%  |
| 2      | 104       | 24.53%  |
| 3      | 43        | 10.14%  |
| 4      | 17        | 4.01%   |
| 5      | 5         | 1.18%   |
| 8      | 4         | 0.94%   |
| 0      | 3         | 0.71%   |
| 9      | 1         | 0.24%   |
| 7      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 269       | 64.05%  |
| Yes       | 151       | 35.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 360       | 85.92%  |
| No        | 59        | 14.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 344       | 81.71%  |
| No        | 77        | 18.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 270       | 64.29%  |
| No        | 150       | 35.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 95        | 22.51%  |
| Germany      | 53        | 12.56%  |
| Italy        | 31        | 7.35%   |
| Canada       | 21        | 4.98%   |
| Russia       | 15        | 3.55%   |
| France       | 14        | 3.32%   |
| Australia    | 14        | 3.32%   |
| UK           | 12        | 2.84%   |
| Spain        | 12        | 2.84%   |
| Poland       | 11        | 2.61%   |
| India        | 10        | 2.37%   |
| Switzerland  | 7         | 1.66%   |
| Greece       | 7         | 1.66%   |
| Brazil       | 7         | 1.66%   |
| Argentina    | 7         | 1.66%   |
| Romania      | 6         | 1.42%   |
| Netherlands  | 6         | 1.42%   |
| Finland      | 6         | 1.42%   |
| Sweden       | 5         | 1.18%   |
| New Zealand  | 5         | 1.18%   |
| Belgium      | 5         | 1.18%   |
| Venezuela    | 4         | 0.95%   |
| Serbia       | 4         | 0.95%   |
| Indonesia    | 4         | 0.95%   |
| Hungary      | 4         | 0.95%   |
| Turkey       | 3         | 0.71%   |
| South Africa | 3         | 0.71%   |
| Mexico       | 3         | 0.71%   |
| Colombia     | 3         | 0.71%   |
| Ukraine      | 2         | 0.47%   |
| Slovakia     | 2         | 0.47%   |
| Singapore    | 2         | 0.47%   |
| Ireland      | 2         | 0.47%   |
| Estonia      | 2         | 0.47%   |
| Egypt        | 2         | 0.47%   |
| Denmark      | 2         | 0.47%   |
| Czechia      | 2         | 0.47%   |
| Croatia      | 2         | 0.47%   |
| Bulgaria     | 2         | 0.47%   |
| Bangladesh   | 2         | 0.47%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Berlin        | 8         | 1.83%   |
| Moscow        | 7         | 1.61%   |
| Sydney        | 6         | 1.38%   |
| Milan         | 5         | 1.15%   |
| St Petersburg | 4         | 0.92%   |
| Budapest      | 4         | 0.92%   |
| Warsaw        | 3         | 0.69%   |
| Rome          | 3         | 0.69%   |
| Mesquite      | 3         | 0.69%   |
| Melbourne     | 3         | 0.69%   |
| Cambridge     | 3         | 0.69%   |
| Bengaluru     | 3         | 0.69%   |
| Belgrade      | 3         | 0.69%   |
| Athens        | 3         | 0.69%   |
| Amsterdam     | 3         | 0.69%   |
| Walled Lake   | 2         | 0.46%   |
| Vienna        | 2         | 0.46%   |
| Vasco da Gama | 2         | 0.46%   |
| Toulouse      | 2         | 0.46%   |
| Toronto       | 2         | 0.46%   |
| Stockholm     | 2         | 0.46%   |
| Singapore     | 2         | 0.46%   |
| Seattle       | 2         | 0.46%   |
| Portland      | 2         | 0.46%   |
| Perth         | 2         | 0.46%   |
| Paris         | 2         | 0.46%   |
| Otwock        | 2         | 0.46%   |
| Orange        | 2         | 0.46%   |
| Oakland       | 2         | 0.46%   |
| New York      | 2         | 0.46%   |
| Munich        | 2         | 0.46%   |
| Montreal      | 2         | 0.46%   |
| Manises       | 2         | 0.46%   |
| Krakow        | 2         | 0.46%   |
| Johannesburg  | 2         | 0.46%   |
| Istanbul      | 2         | 0.46%   |
| Hyderabad     | 2         | 0.46%   |
| Houston       | 2         | 0.46%   |
| Helsinki      | 2         | 0.46%   |
| Hamburg       | 2         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 103       | 143    | 16.25%  |
| WDC                 | 87        | 100    | 13.72%  |
| Seagate             | 72        | 109    | 11.36%  |
| Kingston            | 42        | 46     | 6.62%   |
| Unknown             | 31        | 38     | 4.89%   |
| Crucial             | 30        | 48     | 4.73%   |
| SanDisk             | 29        | 32     | 4.57%   |
| Toshiba             | 27        | 28     | 4.26%   |
| SK hynix            | 24        | 25     | 3.79%   |
| Hitachi             | 16        | 20     | 2.52%   |
| Intel               | 15        | 20     | 2.37%   |
| China               | 12        | 13     | 1.89%   |
| Apple               | 11        | 16     | 1.74%   |
| Micron Technology   | 9         | 9      | 1.42%   |
| PNY                 | 8         | 9      | 1.26%   |
| SPCC                | 7         | 7      | 1.1%    |
| KIOXIA              | 7         | 9      | 1.1%    |
| HGST                | 7         | 7      | 1.1%    |
| LITEON              | 6         | 6      | 0.95%   |
| Transcend           | 5         | 5      | 0.79%   |
| Corsair             | 5         | 5      | 0.79%   |
| Team                | 4         | 4      | 0.63%   |
| Silicon Motion      | 4         | 4      | 0.63%   |
| Netac               | 4         | 4      | 0.63%   |
| Unknown             | 4         | 4      | 0.63%   |
| Phison              | 3         | 4      | 0.47%   |
| Patriot             | 3         | 4      | 0.47%   |
| OCZ                 | 3         | 3      | 0.47%   |
| Hewlett-Packard     | 3         | 4      | 0.47%   |
| Dogfish             | 3         | 3      | 0.47%   |
| Apacer              | 3         | 3      | 0.47%   |
| A-DATA Technology   | 3         | 3      | 0.47%   |
| Lexar               | 2         | 2      | 0.32%   |
| KingSpec            | 2         | 3      | 0.32%   |
| JMicron Technology  | 2         | 2      | 0.32%   |
| GOODRAM             | 2         | 2      | 0.32%   |
| Gigabyte Technology | 2         | 2      | 0.32%   |
| Fujitsu             | 2         | 2      | 0.32%   |
| EYOTA               | 2         | 2      | 0.32%   |
| External            | 2         | 2      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD        | 10        | 1.43%   |
| Samsung SSD 850 EVO 250GB              | 8         | 1.15%   |
| Samsung SSD 970 EVO Plus 1TB           | 7         | 1%      |
| Samsung SSD 860 EVO 500GB              | 7         | 1%      |
| Samsung SSD 980 PRO 1TB                | 6         | 0.86%   |
| Kingston SA400S37240G 240GB SSD        | 6         | 0.86%   |
| Seagate ST500LM021-1KJ152 500GB        | 5         | 0.72%   |
| Kingston SV300S37A240G 240GB SSD       | 5         | 0.72%   |
| Unknown SD/MMC/MS PRO 128GB            | 4         | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB         | 4         | 0.57%   |
| Seagate ST2000DM001-1ER164 2TB         | 4         | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB         | 4         | 0.57%   |
| Samsung SSD 850 EVO 1TB                | 4         | 0.57%   |
| Kingston SA400S37120G 120GB SSD        | 4         | 0.57%   |
| Crucial CT500MX500SSD1 500GB           | 4         | 0.57%   |
| Crucial CT480BX500SSD1 480GB           | 4         | 0.57%   |
| Crucial CT120BX500SSD1 120GB           | 4         | 0.57%   |
| Unknown                                | 4         | 0.57%   |
| Unknown SD32G  32GB                    | 3         | 0.43%   |
| SPCC Solid State Disk 1TB              | 3         | 0.43%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 0.43%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 3         | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB         | 3         | 0.43%   |
| Seagate ST3500413AS 500GB              | 3         | 0.43%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.43%   |
| SanDisk SDSSDA240G 240GB               | 3         | 0.43%   |
| SanDisk NVMe SSD Drive 1TB             | 3         | 0.43%   |
| Samsung SSD 970 PRO 512GB              | 3         | 0.43%   |
| Samsung SSD 870 EVO 500GB              | 3         | 0.43%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.43%   |
| Samsung SSD 840 Series 120GB           | 3         | 0.43%   |
| KIOXIA KBG40ZNV256G 256GB              | 3         | 0.43%   |
| Intel SSDPEKNU512GZ 512GB              | 3         | 0.43%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.43%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 0.43%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.29%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 2         | 0.29%   |
| WDC WDS100T1X0E-00AFY0 1TB             | 2         | 0.29%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.29%   |
| WDC WD3200AAKS-75B3A0 320GB            | 2         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 109    | 35.29%  |
| WDC                 | 65        | 77     | 31.86%  |
| Toshiba             | 21        | 22     | 10.29%  |
| Hitachi             | 16        | 20     | 7.84%   |
| Samsung Electronics | 9         | 11     | 4.41%   |
| HGST                | 7         | 7      | 3.43%   |
| Unknown             | 4         | 4      | 1.96%   |
| Hewlett-Packard     | 2         | 3      | 0.98%   |
| Fujitsu             | 2         | 2      | 0.98%   |
| External            | 2         | 2      | 0.98%   |
| Apple               | 2         | 2      | 0.98%   |
| SABRENT             | 1         | 1      | 0.49%   |
| Maxtor              | 1         | 1      | 0.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 55        | 69     | 22.82%  |
| Kingston            | 31        | 34     | 12.86%  |
| Crucial             | 25        | 41     | 10.37%  |
| SanDisk             | 19        | 21     | 7.88%   |
| China               | 12        | 13     | 4.98%   |
| WDC                 | 7         | 7      | 2.9%    |
| SPCC                | 7         | 7      | 2.9%    |
| PNY                 | 7         | 7      | 2.9%    |
| Apple               | 7         | 10     | 2.9%    |
| Transcend           | 5         | 5      | 2.07%   |
| SK hynix            | 5         | 5      | 2.07%   |
| LITEON              | 5         | 5      | 2.07%   |
| Intel               | 5         | 5      | 2.07%   |
| Netac               | 4         | 4      | 1.66%   |
| Team                | 3         | 3      | 1.24%   |
| OCZ                 | 3         | 3      | 1.24%   |
| Micron Technology   | 3         | 3      | 1.24%   |
| Dogfish             | 3         | 3      | 1.24%   |
| Toshiba             | 2         | 2      | 0.83%   |
| Patriot             | 2         | 2      | 0.83%   |
| KingSpec            | 2         | 3      | 0.83%   |
| GOODRAM             | 2         | 2      | 0.83%   |
| EYOTA               | 2         | 2      | 0.83%   |
| Apacer              | 2         | 2      | 0.83%   |
| A-DATA Technology   | 2         | 2      | 0.83%   |
| Unknown             | 2         | 2      | 0.83%   |
| WALRAM              | 1         | 1      | 0.41%   |
| Vaseky              | 1         | 1      | 0.41%   |
| Teclast             | 1         | 1      | 0.41%   |
| SWORDBILL           | 1         | 2      | 0.41%   |
| Rogueware           | 1         | 2      | 0.41%   |
| RENICE              | 1         | 1      | 0.41%   |
| Mushkin             | 1         | 1      | 0.41%   |
| MMY                 | 1         | 1      | 0.41%   |
| Lexar               | 1         | 1      | 0.41%   |
| Indilinx            | 1         | 1      | 0.41%   |
| Hewlett-Packard     | 1         | 1      | 0.41%   |
| Gigabyte Technology | 1         | 1      | 0.41%   |
| GeIL                | 1         | 1      | 0.41%   |
| CT500MX5            | 1         | 1      | 0.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 203       | 283    | 35.8%   |
| HDD     | 177       | 261    | 31.22%  |
| NVMe    | 154       | 194    | 27.16%  |
| MMC     | 27        | 34     | 4.76%   |
| Unknown | 6         | 10     | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 297       | 515    | 59.05%  |
| NVMe | 154       | 193    | 30.62%  |
| MMC  | 27        | 34     | 5.37%   |
| SAS  | 25        | 40     | 4.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 238       | 334    | 60.56%  |
| 0.51-1.0   | 102       | 131    | 25.95%  |
| 1.01-2.0   | 34        | 44     | 8.65%   |
| 3.01-4.0   | 8         | 9      | 2.04%   |
| 4.01-10.0  | 5         | 17     | 1.27%   |
| 2.01-3.0   | 4         | 5      | 1.02%   |
| 10.01-20.0 | 2         | 4      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 112       | 26.11%  |
| 251-500        | 96        | 22.38%  |
| 501-1000       | 58        | 13.52%  |
| 51-100         | 42        | 9.79%   |
| 21-50          | 40        | 9.32%   |
| 1001-2000      | 27        | 6.29%   |
| More than 3000 | 20        | 4.66%   |
| 1-20           | 18        | 4.2%    |
| 2001-3000      | 15        | 3.5%    |
| Unknown        | 1         | 0.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 166       | 37.9%   |
| 21-50          | 69        | 15.75%  |
| 101-250        | 58        | 13.24%  |
| 51-100         | 56        | 12.79%  |
| 251-500        | 32        | 7.31%   |
| 501-1000       | 23        | 5.25%   |
| 1001-2000      | 18        | 4.11%   |
| More than 3000 | 10        | 2.28%   |
| 2001-3000      | 5         | 1.14%   |
| Unknown        | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB          | 2         | 2      | 2.35%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 2.35%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 2.35%   |
| China SSD 512GB                       | 2         | 2      | 2.35%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 1      | 1.18%   |
| WDC WD5000AAKS-40V6A0 500GB           | 1         | 1      | 1.18%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 1.18%   |
| WDC WD3200BPVT-24JJ5T0 320GB          | 1         | 1      | 1.18%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 1      | 1.18%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1         | 1      | 1.18%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1         | 1      | 1.18%   |
| WDC WD3200AAJS-00B4A0 320GB           | 1         | 1      | 1.18%   |
| WDC WD2500AAJS-00B4A0 250GB           | 1         | 1      | 1.18%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 2      | 1.18%   |
| WDC WD20EARS-00J99B0 2TB              | 1         | 1      | 1.18%   |
| WDC WD10EZRZ-00HTKB0 1TB              | 1         | 1      | 1.18%   |
| WDC WD10EADS-98M2B0 1TB               | 1         | 1      | 1.18%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 1.18%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD  | 1         | 1      | 1.18%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.18%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.18%   |
| Toshiba MK5059GSXP 500GB              | 1         | 1      | 1.18%   |
| Toshiba MK1234GSX 120GB               | 1         | 1      | 1.18%   |
| SK hynix SC210 2.5 7MM 512GB SSD      | 1         | 1      | 1.18%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD | 1         | 1      | 1.18%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 1.18%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 1.18%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.18%   |
| Seagate ST9320421AS 320GB             | 1         | 1      | 1.18%   |
| Seagate ST9160821AS 160GB             | 1         | 1      | 1.18%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1         | 1      | 1.18%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.18%   |
| Seagate ST500LM000-1EJ162 500GB       | 1         | 1      | 1.18%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.18%   |
| Seagate ST380815AS 80GB               | 1         | 1      | 1.18%   |
| Seagate ST3500413AS 500GB             | 1         | 1      | 1.18%   |
| Seagate ST3360320AS 360GB             | 1         | 1      | 1.18%   |
| Seagate ST3320418AS 320GB             | 1         | 1      | 1.18%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 1.18%   |
| Seagate ST320LT012-1DG14C 320GB       | 1         | 2      | 1.18%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 27     | 25%     |
| WDC                 | 16        | 17     | 19.05%  |
| Samsung Electronics | 9         | 12     | 10.71%  |
| Hitachi             | 7         | 9      | 8.33%   |
| Toshiba             | 5         | 5      | 5.95%   |
| HGST                | 4         | 4      | 4.76%   |
| SK hynix            | 3         | 3      | 3.57%   |
| Intel               | 3         | 4      | 3.57%   |
| Kingston            | 2         | 2      | 2.38%   |
| China               | 2         | 2      | 2.38%   |
| SanDisk             | 1         | 1      | 1.19%   |
| RENICE              | 1         | 1      | 1.19%   |
| OCZ                 | 1         | 1      | 1.19%   |
| Micron Technology   | 1         | 1      | 1.19%   |
| Maxtor              | 1         | 1      | 1.19%   |
| Lexar               | 1         | 1      | 1.19%   |
| KingSpec            | 1         | 1      | 1.19%   |
| Indilinx            | 1         | 1      | 1.19%   |
| GOODRAM             | 1         | 1      | 1.19%   |
| Fujitsu             | 1         | 1      | 1.19%   |
| Crucial             | 1         | 6      | 1.19%   |
| Apple               | 1         | 1      | 1.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 27     | 37.5%   |
| WDC                 | 15        | 16     | 26.79%  |
| Hitachi             | 7         | 9      | 12.5%   |
| Toshiba             | 4         | 4      | 7.14%   |
| HGST                | 4         | 4      | 7.14%   |
| Samsung Electronics | 3         | 3      | 5.36%   |
| Maxtor              | 1         | 1      | 1.79%   |
| Fujitsu             | 1         | 1      | 1.79%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 54        | 65     | 66.67%  |
| SSD  | 23        | 32     | 28.4%   |
| NVMe | 4         | 5      | 4.94%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 348       | 589    | 70.73%  |
| Malfunc  | 81        | 102    | 16.46%  |
| Detected | 62        | 90     | 12.6%   |
| Fixed    | 1         | 1      | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 279       | 51.29%  |
| AMD                            | 69        | 12.68%  |
| Samsung Electronics            | 54        | 9.93%   |
| SanDisk                        | 22        | 4.04%   |
| SK hynix                       | 17        | 3.13%   |
| Phison Electronics             | 12        | 2.21%   |
| Kingston Technology Company    | 11        | 2.02%   |
| ASMedia Technology             | 11        | 2.02%   |
| KIOXIA                         | 9         | 1.65%   |
| Silicon Motion                 | 7         | 1.29%   |
| Nvidia                         | 7         | 1.29%   |
| Micron/Crucial Technology      | 7         | 1.29%   |
| Micron Technology              | 6         | 1.1%    |
| Marvell Technology Group       | 5         | 0.92%   |
| JMicron Technology             | 4         | 0.74%   |
| LSI Logic / Symbios Logic      | 3         | 0.55%   |
| VIA Technologies               | 2         | 0.37%   |
| Toshiba America Info Systems   | 2         | 0.37%   |
| Silicon Image                  | 2         | 0.37%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.37%   |
| Hewlett-Packard                | 2         | 0.37%   |
| Broadcom / LSI                 | 2         | 0.37%   |
| Apple                          | 2         | 0.37%   |
| ADATA Technology               | 2         | 0.37%   |
| Union Memory (Shenzhen)        | 1         | 0.18%   |
| ULi Electronics                | 1         | 0.18%   |
| Solid State Storage Technology | 1         | 0.18%   |
| Shenzhen Longsys Electronics   | 1         | 0.18%   |
| Lite-On Technology             | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 40        | 6.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 25        | 4.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 24        | 3.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 22        | 3.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 20        | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 2.29%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 13        | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 2.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 1.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 1.8%    |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 1.64%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 10        | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 1.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 9         | 1.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.31%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 8         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8         | 1.31%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 7         | 1.15%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 7         | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 1.15%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 1.15%   |
| SK hynix BC511 NVMe SSD                                                        | 6         | 0.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 0.98%   |
| Phison E12 NVMe Controller                                                     | 6         | 0.98%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 6         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 0.98%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 0.82%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 5         | 0.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 0.82%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 5         | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 0.82%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 5         | 0.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5         | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 308       | 56.1%   |
| NVMe | 152       | 27.69%  |
| IDE  | 53        | 9.65%   |
| RAID | 33        | 6.01%   |
| SCSI | 2         | 0.36%   |
| SAS  | 1         | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 326       | 77.8%   |
| AMD    | 93        | 22.2%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 8         | 1.91%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 7         | 1.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 6         | 1.43%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 6         | 1.43%   |
| Intel Atom CPU Z3735F @ 1.33GHz          | 6         | 1.43%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 6         | 1.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 4         | 0.95%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 4         | 0.95%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 4         | 0.95%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz     | 4         | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 3         | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 3         | 0.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 3         | 0.72%   |
| Intel Core i5-9600K CPU @ 3.70GHz        | 3         | 0.72%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 3         | 0.72%   |
| Intel Core i5-4300M CPU @ 2.60GHz        | 3         | 0.72%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 3         | 0.72%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 3         | 0.72%   |
| Intel Core i3-2350M CPU @ 2.30GHz        | 3         | 0.72%   |
| Intel Core i3-10110U CPU @ 2.10GHz       | 3         | 0.72%   |
| Intel Core 2 CPU T5500 @ 1.66GHz         | 3         | 0.72%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 3         | 0.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz        | 3         | 0.72%   |
| Intel 12th Gen Core i7-12700H            | 3         | 0.72%   |
| Intel 12th Gen Core i5-1235U             | 3         | 0.72%   |
| AMD Ryzen 7 5800H with Radeon Graphics   | 3         | 0.72%   |
| AMD Ryzen 5 5625U with Radeon Graphics   | 3         | 0.72%   |
| AMD Ryzen 5 5600H with Radeon Graphics   | 3         | 0.72%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 2         | 0.48%   |
| Intel Core i7-8700B CPU @ 3.20GHz        | 2         | 0.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 0.48%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 2         | 0.48%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 0.48%   |
| Intel Core i7-5820K CPU @ 3.30GHz        | 2         | 0.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 2         | 0.48%   |
| Intel Core i7-2640M CPU @ 2.80GHz        | 2         | 0.48%   |
| Intel Core i7-2600K CPU @ 3.40GHz        | 2         | 0.48%   |
| Intel Core i7-2600 CPU @ 3.40GHz         | 2         | 0.48%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 2         | 0.48%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 2         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 86        | 20.53%  |
| Intel Core i7           | 66        | 15.75%  |
| Other                   | 41        | 9.79%   |
| Intel Core i3           | 36        | 8.59%   |
| Intel Celeron           | 25        | 5.97%   |
| AMD Ryzen 5             | 25        | 5.97%   |
| AMD Ryzen 7             | 21        | 5.01%   |
| Intel Core 2 Duo        | 20        | 4.77%   |
| Intel Atom              | 13        | 3.1%    |
| Intel Xeon              | 9         | 2.15%   |
| AMD Ryzen 3             | 8         | 1.91%   |
| AMD Ryzen 9             | 6         | 1.43%   |
| Intel Pentium           | 5         | 1.19%   |
| Intel Pentium Dual-Core | 4         | 0.95%   |
| Intel Pentium Silver    | 3         | 0.72%   |
| Intel Pentium Dual      | 3         | 0.72%   |
| Intel Core 2            | 3         | 0.72%   |
| AMD Phenom II X4        | 3         | 0.72%   |
| AMD Athlon II X4        | 3         | 0.72%   |
| AMD A4                  | 3         | 0.72%   |
| Intel Pentium M         | 2         | 0.48%   |
| Intel Pentium Gold      | 2         | 0.48%   |
| Intel Pentium 4         | 2         | 0.48%   |
| Intel Genuine           | 2         | 0.48%   |
| Intel Core i9           | 2         | 0.48%   |
| AMD Ryzen Threadripper  | 2         | 0.48%   |
| AMD Phenom              | 2         | 0.48%   |
| AMD FX                  | 2         | 0.48%   |
| AMD E1                  | 2         | 0.48%   |
| AMD A8                  | 2         | 0.48%   |
| AMD A6                  | 2         | 0.48%   |
| Intel Pentium D         | 1         | 0.24%   |
| Intel Core M            | 1         | 0.24%   |
| Intel Celeron Dual-Core | 1         | 0.24%   |
| AMD Turion 64 X2 Mobile | 1         | 0.24%   |
| AMD Turion 64 Mobile    | 1         | 0.24%   |
| AMD Sempron             | 1         | 0.24%   |
| AMD Ryzen 5 PRO         | 1         | 0.24%   |
| AMD Phenom II X6        | 1         | 0.24%   |
| AMD Phenom II           | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 164       | 39.14%  |
| 4      | 145       | 34.61%  |
| 6      | 40        | 9.55%   |
| 8      | 34        | 8.11%   |
| 1      | 12        | 2.86%   |
| 12     | 11        | 2.63%   |
| 10     | 6         | 1.43%   |
| 14     | 3         | 0.72%   |
| 16     | 2         | 0.48%   |
| 5      | 1         | 0.24%   |
| 3      | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 414       | 98.81%  |
| 2      | 5         | 1.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 269       | 64.2%   |
| 1      | 150       | 35.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 414       | 98.81%  |
| 32-bit         | 5         | 1.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 12.03%  |
| 0x206a7    | 26        | 6.13%   |
| 0x306a9    | 23        | 5.42%   |
| 0x306c3    | 22        | 5.19%   |
| 0x806c1    | 15        | 3.54%   |
| 0x406e3    | 14        | 3.3%    |
| 0x1067a    | 14        | 3.3%    |
| 0x0a50000c | 12        | 2.83%   |
| 0x506e3    | 11        | 2.59%   |
| 0x30678    | 10        | 2.36%   |
| 0x20655    | 10        | 2.36%   |
| 0x806ec    | 9         | 2.12%   |
| 0x6fd      | 8         | 1.89%   |
| 0x08608103 | 8         | 1.89%   |
| 0x906ea    | 7         | 1.65%   |
| 0x806e9    | 7         | 1.65%   |
| 0x706a8    | 7         | 1.65%   |
| 0xa0652    | 6         | 1.42%   |
| 0x906a3    | 6         | 1.42%   |
| 0x806ea    | 6         | 1.42%   |
| 0x40651    | 6         | 1.42%   |
| 0x306d4    | 6         | 1.42%   |
| 0xa0653    | 5         | 1.18%   |
| 0x906ed    | 5         | 1.18%   |
| 0x906a4    | 5         | 1.18%   |
| 0x406c4    | 5         | 1.18%   |
| 0x106e5    | 5         | 1.18%   |
| 0x08108102 | 5         | 1.18%   |
| 0x906e9    | 4         | 0.94%   |
| 0x906c0    | 4         | 0.94%   |
| 0x706a1    | 4         | 0.94%   |
| 0x10676    | 4         | 0.94%   |
| 0x0a601203 | 4         | 0.94%   |
| 0x08108109 | 4         | 0.94%   |
| 0x0800820d | 4         | 0.94%   |
| 0xa0671    | 3         | 0.71%   |
| 0x0a50000d | 3         | 0.71%   |
| 0x08701021 | 3         | 0.71%   |
| 0x08600106 | 3         | 0.71%   |
| 0x010000db | 3         | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 43        | 10.24%  |
| Haswell          | 37        | 8.81%   |
| SandyBridge      | 30        | 7.14%   |
| Skylake          | 28        | 6.67%   |
| Unknown          | 27        | 6.43%   |
| IvyBridge        | 25        | 5.95%   |
| Zen 3            | 21        | 5%      |
| Penryn           | 21        | 5%      |
| TigerLake        | 19        | 4.52%   |
| Silvermont       | 16        | 3.81%   |
| Zen+             | 15        | 3.57%   |
| Westmere         | 14        | 3.33%   |
| Core             | 13        | 3.1%    |
| CometLake        | 12        | 2.86%   |
| Goldmont plus    | 11        | 2.62%   |
| K10              | 10        | 2.38%   |
| Icelake          | 10        | 2.38%   |
| Zen 2            | 9         | 2.14%   |
| Nehalem          | 7         | 1.67%   |
| Broadwell        | 7         | 1.67%   |
| Alderlake Hybrid | 7         | 1.67%   |
| Tremont          | 4         | 0.95%   |
| Excavator        | 4         | 0.95%   |
| Zen              | 3         | 0.71%   |
| Puma             | 3         | 0.71%   |
| Piledriver       | 3         | 0.71%   |
| P6               | 3         | 0.71%   |
| NetBurst         | 3         | 0.71%   |
| K8 Hammer        | 3         | 0.71%   |
| Goldmont         | 3         | 0.71%   |
| Bonnell          | 3         | 0.71%   |
| Bobcat           | 2         | 0.48%   |
| Steamroller      | 1         | 0.24%   |
| K8 & K10 hybrid  | 1         | 0.24%   |
| K10 Llano        | 1         | 0.24%   |
| Bulldozer        | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 263       | 53.24%  |
| Nvidia                     | 118       | 23.89%  |
| AMD                        | 112       | 22.67%  |
| Matrox Electronics Systems | 1         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 4.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 3.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 3.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 3.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 2.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 2.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 1.96%   |
| AMD Lucienne                                                                             | 10        | 1.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 1.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.57%   |
| Intel HD Graphics 530                                                                    | 8         | 1.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.17%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 0.98%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.98%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 5         | 0.98%   |
| Intel HD Graphics 620                                                                    | 5         | 0.98%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 0.98%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.98%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 0.98%   |
| AMD Raphael                                                                              | 5         | 0.98%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.78%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 0.78%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4         | 0.78%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 4         | 0.78%   |
| AMD Barcelo                                                                              | 4         | 0.78%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.59%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 199       | 47.38%  |
| 1 x AMD        | 85        | 20.24%  |
| 1 x Nvidia     | 63        | 15%     |
| Intel + Nvidia | 43        | 10.24%  |
| Intel + AMD    | 12        | 2.86%   |
| AMD + Nvidia   | 11        | 2.62%   |
| 2 x AMD        | 5         | 1.19%   |
| 2 x Intel      | 1         | 0.24%   |
| 1 x Matrox     | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 350       | 82.55%  |
| Proprietary | 52        | 12.26%  |
| Unknown     | 22        | 5.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 268       | 63.36%  |
| 0.01-0.5   | 50        | 11.82%  |
| 1.01-2.0   | 34        | 8.04%   |
| 3.01-4.0   | 22        | 5.2%    |
| 0.51-1.0   | 20        | 4.73%   |
| 7.01-8.0   | 18        | 4.26%   |
| 8.01-16.0  | 6         | 1.42%   |
| 2.01-3.0   | 3         | 0.71%   |
| 5.01-6.0   | 2         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 53        | 11.86%  |
| Chimei Innolux          | 50        | 11.19%  |
| Samsung Electronics     | 45        | 10.07%  |
| BOE                     | 36        | 8.05%   |
| LG Display              | 29        | 6.49%   |
| Dell                    | 22        | 4.92%   |
| Hewlett-Packard         | 18        | 4.03%   |
| Acer                    | 17        | 3.8%    |
| Apple                   | 15        | 3.36%   |
| Goldstar                | 14        | 3.13%   |
| AOC                     | 11        | 2.46%   |
| Sony                    | 10        | 2.24%   |
| Philips                 | 10        | 2.24%   |
| PANDA                   | 10        | 2.24%   |
| Lenovo                  | 10        | 2.24%   |
| Chi Mei Optoelectronics | 10        | 2.24%   |
| Ancor Communications    | 10        | 2.24%   |
| BenQ                    | 7         | 1.57%   |
| ViewSonic               | 4         | 0.89%   |
| Sharp                   | 4         | 0.89%   |
| MSI                     | 4         | 0.89%   |
| Fujitsu Siemens         | 4         | 0.89%   |
| Eizo                    | 4         | 0.89%   |
| ASUSTek Computer        | 4         | 0.89%   |
| Medion                  | 3         | 0.67%   |
| InfoVision              | 3         | 0.67%   |
| Iiyama                  | 3         | 0.67%   |
| HannStar                | 3         | 0.67%   |
| CPT                     | 3         | 0.67%   |
| Vestel Elektronik       | 2         | 0.45%   |
| Panasonic               | 2         | 0.45%   |
| NEC Computers           | 2         | 0.45%   |
| MiTAC                   | 2         | 0.45%   |
| Hitachi                 | 2         | 0.45%   |
| Xiaomi                  | 1         | 0.22%   |
| Vizio                   | 1         | 0.22%   |
| TMX                     | 1         | 0.22%   |
| Sunplus                 | 1         | 0.22%   |
| STA                     | 1         | 0.22%   |
| Sangyo                  | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 1.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.88%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 3         | 0.66%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.66%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch                | 2         | 0.44%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 2         | 0.44%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                       | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 2         | 0.44%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch        | 2         | 0.44%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 2         | 0.44%   |
| Philips 221P3LPY PHL08A3 1920x1080 477x268mm 21.5-inch                   | 2         | 0.44%   |
| MSI G27C4S2 MSI5CA9 1920x1080 597x336mm 27.0-inch                        | 2         | 0.44%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 0.44%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 2         | 0.44%   |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                 | 2         | 0.44%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.44%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 470x300mm 22.0-inch         | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.44%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO4100 1920x1200 216x136mm 10.0-inch           | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.44%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                     | 2         | 0.44%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                       | 2         | 0.44%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 2         | 0.44%   |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                       | 1         | 0.22%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                       | 1         | 0.22%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch                 | 1         | 0.22%   |
| ViewSonic VA2012wSERIES VSC6A1C 1680x1050 433x271mm 20.1-inch            | 1         | 0.22%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                    | 1         | 0.22%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.22%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 192       | 44.55%  |
| 1366x768 (WXGA)    | 79        | 18.33%  |
| 3840x2160 (4K)     | 35        | 8.12%   |
| 1680x1050 (WSXGA+) | 17        | 3.94%   |
| 2560x1440 (QHD)    | 15        | 3.48%   |
| 1600x900 (HD+)     | 13        | 3.02%   |
| 1280x800 (WXGA)    | 13        | 3.02%   |
| 1280x1024 (SXGA)   | 13        | 3.02%   |
| 1920x1200 (WUXGA)  | 8         | 1.86%   |
| 1440x900 (WXGA+)   | 8         | 1.86%   |
| 2560x1600          | 4         | 0.93%   |
| 1360x768           | 4         | 0.93%   |
| 1024x768 (XGA)     | 4         | 0.93%   |
| 2880x1800          | 3         | 0.7%    |
| 2560x1080          | 3         | 0.7%    |
| 2160x1440          | 3         | 0.7%    |
| 3440x1440          | 2         | 0.46%   |
| 2256x1504          | 2         | 0.46%   |
| 1280x720 (HD)      | 2         | 0.46%   |
| 1024x600           | 2         | 0.46%   |
| Unknown            | 2         | 0.46%   |
| 3840x2400          | 1         | 0.23%   |
| 3840x1080          | 1         | 0.23%   |
| 3200x2000          | 1         | 0.23%   |
| 3200x1800 (QHD+)   | 1         | 0.23%   |
| 2880x1920          | 1         | 0.23%   |
| 1920x1440          | 1         | 0.23%   |
| 1400x1050          | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 123       | 27.58%  |
| 13      | 39        | 8.74%   |
| 24      | 33        | 7.4%    |
| 23      | 31        | 6.95%   |
| 27      | 29        | 6.5%    |
| 17      | 28        | 6.28%   |
| 14      | 25        | 5.61%   |
| 21      | 21        | 4.71%   |
| 31      | 15        | 3.36%   |
| 11      | 15        | 3.36%   |
| 22      | 12        | 2.69%   |
| Unknown | 11        | 2.47%   |
| 19      | 10        | 2.24%   |
| 16      | 6         | 1.35%   |
| 84      | 5         | 1.12%   |
| 34      | 5         | 1.12%   |
| 18      | 5         | 1.12%   |
| 12      | 5         | 1.12%   |
| 10      | 5         | 1.12%   |
| 40      | 3         | 0.67%   |
| 26      | 3         | 0.67%   |
| 20      | 3         | 0.67%   |
| 54      | 2         | 0.45%   |
| 75      | 1         | 0.22%   |
| 72      | 1         | 0.22%   |
| 65      | 1         | 0.22%   |
| 61      | 1         | 0.22%   |
| 52      | 1         | 0.22%   |
| 46      | 1         | 0.22%   |
| 43      | 1         | 0.22%   |
| 42      | 1         | 0.22%   |
| 39      | 1         | 0.22%   |
| 36      | 1         | 0.22%   |
| 32      | 1         | 0.22%   |
| 25      | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 174       | 39.37%  |
| 501-600     | 90        | 20.36%  |
| 401-500     | 44        | 9.95%   |
| 201-300     | 43        | 9.73%   |
| 351-400     | 36        | 8.14%   |
| 601-700     | 18        | 4.07%   |
| Unknown     | 11        | 2.49%   |
| 701-800     | 7         | 1.58%   |
| 1501-2000   | 7         | 1.58%   |
| 1001-1500   | 6         | 1.36%   |
| 801-900     | 4         | 0.9%    |
| 901-1000    | 2         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 316       | 76.51%  |
| 16/10   | 59        | 14.29%  |
| 5/4     | 12        | 2.91%   |
| 4/3     | 8         | 1.94%   |
| Unknown | 7         | 1.69%   |
| 3/2     | 6         | 1.45%   |
| 21/9    | 5         | 1.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 121       | 27.31%  |
| 201-250        | 75        | 16.93%  |
| 81-90          | 52        | 11.74%  |
| 301-350        | 31        | 7%      |
| 151-200        | 25        | 5.64%   |
| 121-130        | 24        | 5.42%   |
| 351-500        | 21        | 4.74%   |
| 51-60          | 15        | 3.39%   |
| 251-300        | 13        | 2.93%   |
| More than 1000 | 12        | 2.71%   |
| 71-80          | 11        | 2.48%   |
| Unknown        | 11        | 2.48%   |
| 501-1000       | 8         | 1.81%   |
| 141-150        | 7         | 1.58%   |
| 61-70          | 5         | 1.13%   |
| 41-50          | 5         | 1.13%   |
| 111-120        | 4         | 0.9%    |
| 91-100         | 3         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 154       | 35.65%  |
| 121-160       | 130       | 30.09%  |
| 101-120       | 93        | 21.53%  |
| 161-240       | 24        | 5.56%   |
| Unknown       | 11        | 2.55%   |
| More than 240 | 10        | 2.31%   |
| 1-50          | 10        | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 344       | 80.94%  |
| 2     | 56        | 13.18%  |
| 0     | 20        | 4.71%   |
| 3     | 5         | 1.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 217       | 32.34%  |
| Intel                             | 208       | 31%     |
| Qualcomm Atheros                  | 65        | 9.69%   |
| Broadcom                          | 42        | 6.26%   |
| MediaTek                          | 21        | 3.13%   |
| Broadcom Limited                  | 16        | 2.38%   |
| TP-Link                           | 12        | 1.79%   |
| Ralink Technology                 | 9         | 1.34%   |
| Marvell Technology Group          | 9         | 1.34%   |
| Ralink                            | 7         | 1.04%   |
| ASIX Electronics                  | 7         | 1.04%   |
| Samsung Electronics               | 5         | 0.75%   |
| OPPO Electronics                  | 5         | 0.75%   |
| Nvidia                            | 5         | 0.75%   |
| Motorola PCS                      | 4         | 0.6%    |
| Microsoft                         | 4         | 0.6%    |
| Sierra Wireless                   | 3         | 0.45%   |
| Qualcomm Atheros Communications   | 3         | 0.45%   |
| AVM                               | 3         | 0.45%   |
| Xiaomi                            | 2         | 0.3%    |
| Linksys                           | 2         | 0.3%    |
| Lenovo                            | 2         | 0.3%    |
| D-Link                            | 2         | 0.3%    |
| VIA Technologies                  | 1         | 0.15%   |
| Sweex                             | 1         | 0.15%   |
| Qualcomm Technologies             | 1         | 0.15%   |
| NetGear                           | 1         | 0.15%   |
| Mercucys                          | 1         | 0.15%   |
| JMicron Technology                | 1         | 0.15%   |
| IMC Networks                      | 1         | 0.15%   |
| Foxconn / Hon Hai                 | 1         | 0.15%   |
| Fibocom                           | 1         | 0.15%   |
| Ericsson Business Mobile Networks | 1         | 0.15%   |
| Edimax Technology                 | 1         | 0.15%   |
| Dell                              | 1         | 0.15%   |
| D-Link System                     | 1         | 0.15%   |
| Attansic Technology               | 1         | 0.15%   |
| ASUSTek Computer                  | 1         | 0.15%   |
| Aquantia                          | 1         | 0.15%   |
| Apple                             | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 143       | 18.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 19        | 2.42%   |
| Intel Wi-Fi 6 AX200                                                    | 18        | 2.3%    |
| Intel Wi-Fi 6 AX201                                                    | 15        | 1.91%   |
| Intel Wireless 8260                                                    | 14        | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 1.53%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11        | 1.4%    |
| Intel Ethernet Controller I225-V                                       | 10        | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9         | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 9         | 1.15%   |
| Intel Wireless 8265 / 8275                                             | 9         | 1.15%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 1.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8         | 1.02%   |
| Intel Wireless 7265                                                    | 8         | 1.02%   |
| Intel Wireless 3165                                                    | 8         | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7         | 0.89%   |
| Intel Wireless 7260                                                    | 7         | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 7         | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 7         | 0.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 6         | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 6         | 0.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6         | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 6         | 0.77%   |
| Intel Ethernet Connection I219-LM                                      | 6         | 0.77%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 6         | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 0.77%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 5         | 0.64%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 5         | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 5         | 0.64%   |
| Ralink MT7601U Wireless Adapter                                        | 5         | 0.64%   |
| OPPO OnePlus Nord 4                                                    | 5         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 5         | 0.64%   |
| Intel I211 Gigabit Network Connection                                  | 5         | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 5         | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 5         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 4         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 160       | 41.99%  |
| Realtek Semiconductor           | 65        | 17.06%  |
| Qualcomm Atheros                | 47        | 12.34%  |
| Broadcom                        | 27        | 7.09%   |
| MediaTek                        | 20        | 5.25%   |
| TP-Link                         | 11        | 2.89%   |
| Broadcom Limited                | 10        | 2.62%   |
| Ralink Technology               | 9         | 2.36%   |
| Ralink                          | 7         | 1.84%   |
| Sierra Wireless                 | 3         | 0.79%   |
| Qualcomm Atheros Communications | 3         | 0.79%   |
| AVM                             | 3         | 0.79%   |
| Microsoft                       | 2         | 0.52%   |
| Linksys                         | 2         | 0.52%   |
| D-Link                          | 2         | 0.52%   |
| Sweex                           | 1         | 0.26%   |
| Qualcomm Technologies           | 1         | 0.26%   |
| NetGear                         | 1         | 0.26%   |
| Mercucys                        | 1         | 0.26%   |
| Marvell Technology Group        | 1         | 0.26%   |
| IMC Networks                    | 1         | 0.26%   |
| Fibocom                         | 1         | 0.26%   |
| Edimax Technology               | 1         | 0.26%   |
| D-Link System                   | 1         | 0.26%   |
| ASUSTek Computer                | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 18        | 4.71%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 3.93%   |
| Intel Wireless 8260                                                     | 14        | 3.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 2.36%   |
| Intel Wireless 8265 / 8275                                              | 9         | 2.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 2.09%   |
| Intel Wireless 7265                                                     | 8         | 2.09%   |
| Intel Wireless 3165                                                     | 8         | 2.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.83%   |
| Intel Wireless 7260                                                     | 7         | 1.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 1.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 6         | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 1.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 5         | 1.31%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 5         | 1.31%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 1.31%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.31%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 1.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 1.05%   |
| Intel Wireless 3160                                                     | 4         | 1.05%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 4         | 1.05%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 4         | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.05%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 4         | 1.05%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.79%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 187       | 48.32%  |
| Intel                    | 101       | 26.1%   |
| Broadcom                 | 24        | 6.2%    |
| Qualcomm Atheros         | 23        | 5.94%   |
| Marvell Technology Group | 8         | 2.07%   |
| ASIX Electronics         | 7         | 1.81%   |
| Broadcom Limited         | 6         | 1.55%   |
| OPPO Electronics         | 5         | 1.29%   |
| Nvidia                   | 5         | 1.29%   |
| Motorola PCS             | 4         | 1.03%   |
| Samsung Electronics      | 3         | 0.78%   |
| Xiaomi                   | 2         | 0.52%   |
| Microsoft                | 2         | 0.52%   |
| Lenovo                   | 2         | 0.52%   |
| VIA Technologies         | 1         | 0.26%   |
| TP-Link                  | 1         | 0.26%   |
| MediaTek                 | 1         | 0.26%   |
| JMicron Technology       | 1         | 0.26%   |
| Foxconn / Hon Hai        | 1         | 0.26%   |
| Attansic Technology      | 1         | 0.26%   |
| Aquantia                 | 1         | 0.26%   |
| Apple                    | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 143       | 36.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 19        | 4.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11        | 2.78%   |
| Intel Ethernet Controller I225-V                                       | 10        | 2.53%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 2.27%   |
| Intel Ethernet Connection I219-LM                                      | 6         | 1.52%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 6         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 1.52%   |
| OPPO OnePlus Nord 4                                                    | 5         | 1.26%   |
| Intel I211 Gigabit Network Connection                                  | 5         | 1.26%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 5         | 1.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 1.01%   |
| Intel Ethernet Connection I217-V                                       | 4         | 1.01%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.01%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 1.01%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 4         | 1.01%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 0.76%   |
| Motorola PCS moto g84 5G                                               | 3         | 0.76%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 3         | 0.76%   |
| Intel Ethernet Connection I219-V                                       | 3         | 0.76%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.76%   |
| Intel Ethernet Connection (2) I218-V                                   | 3         | 0.76%   |
| Intel Ethernet Connection (14) I219-V                                  | 3         | 0.76%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.51%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.51%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 2         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.51%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 0.51%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                      | 2         | 0.51%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.51%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2         | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 359       | 50.63%  |
| WiFi     | 344       | 48.52%  |
| Modem    | 6         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 264       | 61.54%  |
| Ethernet | 165       | 38.46%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 244       | 57.96%  |
| 1     | 155       | 36.82%  |
| 0     | 10        | 2.38%   |
| 3     | 9         | 2.14%   |
| 4     | 2         | 0.48%   |
| 8     | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 307       | 72.75%  |
| Yes  | 115       | 27.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 123       | 44.09%  |
| Realtek Semiconductor           | 27        | 9.68%   |
| Qualcomm Atheros Communications | 19        | 6.81%   |
| Apple                           | 18        | 6.45%   |
| Cambridge Silicon Radio         | 15        | 5.38%   |
| Foxconn / Hon Hai               | 14        | 5.02%   |
| Broadcom                        | 14        | 5.02%   |
| Lite-On Technology              | 12        | 4.3%    |
| IMC Networks                    | 9         | 3.23%   |
| MediaTek                        | 7         | 2.51%   |
| Hewlett-Packard                 | 5         | 1.79%   |
| Ralink                          | 4         | 1.43%   |
| Dell                            | 3         | 1.08%   |
| ASUSTek Computer                | 3         | 1.08%   |
| TP-Link                         | 2         | 0.72%   |
| Realtek                         | 1         | 0.36%   |
| Ralink Technology               | 1         | 0.36%   |
| Marvell Semiconductor           | 1         | 0.36%   |
| Alps Electric                   | 1         | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 47        | 16.85%  |
| Realtek Bluetooth Radio                                                             | 24        | 8.6%    |
| Intel AX201 Bluetooth                                                               | 24        | 8.6%    |
| Intel AX200 Bluetooth                                                               | 18        | 6.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 15        | 5.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 4.66%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 3.23%   |
| MediaTek Wireless_Device                                                            | 7         | 2.51%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 2.15%   |
| Apple Bluetooth Host Controller                                                     | 6         | 2.15%   |
| IMC Networks Wireless_Device                                                        | 5         | 1.79%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 5         | 1.79%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 1.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 1.43%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 1.43%   |
| Intel AX211 Bluetooth                                                               | 4         | 1.43%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 1.43%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.08%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.08%   |
| Lite-On Wireless_Device                                                             | 3         | 1.08%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.08%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.08%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.08%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.08%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.08%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 1.08%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 1.08%   |
| Apple Bluetooth HCI                                                                 | 3         | 1.08%   |
| TP-Link TP-Link Bluetooth USB Adapter                                               | 2         | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 0.72%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.72%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.72%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.72%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.72%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.36%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.36%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 306       | 53.68%  |
| AMD                        | 109       | 19.12%  |
| Nvidia                     | 93        | 16.32%  |
| C-Media Electronics        | 9         | 1.58%   |
| Creative Labs              | 5         | 0.88%   |
| VIA Technologies           | 3         | 0.53%   |
| Texas Instruments          | 3         | 0.53%   |
| JMTek                      | 3         | 0.53%   |
| Generalplus Technology     | 3         | 0.53%   |
| ROCCAT                     | 2         | 0.35%   |
| Realtek Semiconductor      | 2         | 0.35%   |
| Lenovo                     | 2         | 0.35%   |
| BEHRINGER International    | 2         | 0.35%   |
| Apple                      | 2         | 0.35%   |
| TerraTec Electronic        | 1         | 0.18%   |
| Tenx Technology            | 1         | 0.18%   |
| Shenzhen Riitek Technology | 1         | 0.18%   |
| Setek Elektronik           | 1         | 0.18%   |
| Schiit Audio               | 1         | 0.18%   |
| Razer USA                  | 1         | 0.18%   |
| Plantronics                | 1         | 0.18%   |
| Microsoft                  | 1         | 0.18%   |
| M-Audio                    | 1         | 0.18%   |
| Logitech                   | 1         | 0.18%   |
| LG Electronics             | 1         | 0.18%   |
| Kingston Technology        | 1         | 0.18%   |
| Jieli Technology           | 1         | 0.18%   |
| GYROCOM C&C                | 1         | 0.18%   |
| Guillemot                  | 1         | 0.18%   |
| GN Netcom                  | 1         | 0.18%   |
| Giga-Byte Technology       | 1         | 0.18%   |
| Focusrite-Novation         | 1         | 0.18%   |
| FIFINE 683 Microphone      | 1         | 0.18%   |
| Ensoniq                    | 1         | 0.18%   |
| Digidesign                 | 1         | 0.18%   |
| Dell                       | 1         | 0.18%   |
| Creative Technology        | 1         | 0.18%   |
| Conexant Systems           | 1         | 0.18%   |
| CMX Systems                | 1         | 0.18%   |
| Cambridge Silicon Radio    | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 50        | 7.44%   |
| Intel Sunrise Point-LP HD Audio                                            | 30        | 4.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 29        | 4.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 29        | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24        | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 23        | 3.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 19        | 2.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 2.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 17        | 2.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 2.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12        | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 11        | 1.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 11        | 1.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 1.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11        | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 1.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 1.19%   |
| AMD FCH Azalia Controller                                                  | 8         | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 1.04%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 1.04%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 1.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 0.89%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 0.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 0.89%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 0.89%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 0.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 0.89%   |
| Nvidia GA107 High Definition Audio Controller                              | 5         | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 0.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 0.74%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 5         | 0.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 103       | 20.98%  |
| SK hynix                       | 84        | 17.11%  |
| Unknown                        | 57        | 11.61%  |
| Kingston                       | 49        | 9.98%   |
| Micron Technology              | 38        | 7.74%   |
| Crucial                        | 34        | 6.92%   |
| Corsair                        | 23        | 4.68%   |
| G.Skill                        | 13        | 2.65%   |
| A-DATA Technology              | 12        | 2.44%   |
| Ramaxel Technology             | 11        | 2.24%   |
| Nanya Technology               | 10        | 2.04%   |
| Elpida                         | 10        | 2.04%   |
| Unknown (ABCD)                 | 8         | 1.63%   |
| Unknown                        | 8         | 1.63%   |
| Transcend                      | 5         | 1.02%   |
| Smart                          | 3         | 0.61%   |
| Unifosa                        | 2         | 0.41%   |
| Patriot                        | 2         | 0.41%   |
| Lexar Co Limited               | 2         | 0.41%   |
| CSX                            | 2         | 0.41%   |
| Avant                          | 2         | 0.41%   |
| Wilk                           | 1         | 0.2%    |
| Unknown (AB)                   | 1         | 0.2%    |
| Unknown (0x0E9D)               | 1         | 0.2%    |
| Team                           | 1         | 0.2%    |
| PNY                            | 1         | 0.2%    |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.2%    |
| Innodisk                       | 1         | 0.2%    |
| Hewlett-Packard                | 1         | 0.2%    |
| Golden Empire                  | 1         | 0.2%    |
| Essencore                      | 1         | 0.2%    |
| ASint Technology               | 1         | 0.2%    |
| Apacer                         | 1         | 0.2%    |
| 48spaces                       | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 1.53%   |
| Unknown                                                          | 8         | 1.53%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.15%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.15%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.96%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 5         | 0.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 5         | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.76%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.76%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 0.76%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4         | 0.76%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 3         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 3         | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.57%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.57%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.57%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 3         | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.57%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 0.57%   |
| Crucial RAM CT16G4SFRA32A.C16FR 16GB SODIMM DDR4 3200MT/s        | 3         | 0.57%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.38%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.38%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 2         | 0.38%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 2         | 0.38%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.38%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.38%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 2         | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.38%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.38%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.38%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM 1333MT/s                  | 2         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 182       | 42.62%  |
| DDR3    | 156       | 36.53%  |
| DDR2    | 26        | 6.09%   |
| LPDDR4  | 17        | 3.98%   |
| SDRAM   | 15        | 3.51%   |
| Unknown | 9         | 2.11%   |
| DDR5    | 7         | 1.64%   |
| LPDDR3  | 6         | 1.41%   |
| DDR     | 6         | 1.41%   |
| DRAM    | 2         | 0.47%   |
| LPDDR5  | 1         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 273       | 64.69%  |
| DIMM         | 122       | 28.91%  |
| Row Of Chips | 22        | 5.21%   |
| Chip         | 2         | 0.47%   |
| Unknown      | 2         | 0.47%   |
| FB-DIMM      | 1         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 153       | 33.48%  |
| 4096  | 130       | 28.45%  |
| 2048  | 68        | 14.88%  |
| 16384 | 67        | 14.66%  |
| 1024  | 22        | 4.81%   |
| 32768 | 15        | 3.28%   |
| 512   | 1         | 0.22%   |
| 256   | 1         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 87        | 19.21%  |
| 3200    | 82        | 18.1%   |
| 2667    | 51        | 11.26%  |
| 1333    | 42        | 9.27%   |
| 2400    | 29        | 6.4%    |
| 1334    | 17        | 3.75%   |
| 667     | 17        | 3.75%   |
| Unknown | 17        | 3.75%   |
| 3600    | 13        | 2.87%   |
| 2133    | 12        | 2.65%   |
| 1067    | 10        | 2.21%   |
| 800     | 7         | 1.55%   |
| 1867    | 5         | 1.1%    |
| 1800    | 5         | 1.1%    |
| 3733    | 4         | 0.88%   |
| 2933    | 4         | 0.88%   |
| 533     | 4         | 0.88%   |
| 6000    | 3         | 0.66%   |
| 4800    | 3         | 0.66%   |
| 4267    | 3         | 0.66%   |
| 4199    | 3         | 0.66%   |
| 3266    | 3         | 0.66%   |
| 3000    | 3         | 0.66%   |
| 2048    | 3         | 0.66%   |
| 1866    | 3         | 0.66%   |
| 975     | 3         | 0.66%   |
| 3800    | 2         | 0.44%   |
| 2666    | 2         | 0.44%   |
| 1066    | 2         | 0.44%   |
| 333     | 2         | 0.44%   |
| 8400    | 1         | 0.22%   |
| 5800    | 1         | 0.22%   |
| 5500    | 1         | 0.22%   |
| 4266    | 1         | 0.22%   |
| 4133    | 1         | 0.22%   |
| 3866    | 1         | 0.22%   |
| 3066    | 1         | 0.22%   |
| 2200    | 1         | 0.22%   |
| 2000    | 1         | 0.22%   |
| 1639    | 1         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 4         | 33.33%  |
| Canon              | 4         | 33.33%  |
| Brother Industries | 4         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon MF641C             | 2         | 16.67%  |
| HP LaserJet P2055 series | 1         | 8.33%   |
| HP LaserJet 1022         | 1         | 8.33%   |
| HP ENVY 4500 series      | 1         | 8.33%   |
| HP Deskjet 1510          | 1         | 8.33%   |
| Canon MG5700 series      | 1         | 8.33%   |
| Canon LiDE 400           | 1         | 8.33%   |
| Brother Printer          | 1         | 8.33%   |
| Brother MFC-7340         | 1         | 8.33%   |
| Brother HL-2150N series  | 1         | 8.33%   |
| Brother DCP-L2540DW      | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30      | 1         | 33.33%  |
| Canon CanoScan LiDE 210            | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 59        | 22.26%  |
| Microdia                               | 25        | 9.43%   |
| IMC Networks                           | 23        | 8.68%   |
| Realtek Semiconductor                  | 17        | 6.42%   |
| Quanta                                 | 15        | 5.66%   |
| Logitech                               | 14        | 5.28%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 5.28%   |
| Bison Electronics                      | 14        | 5.28%   |
| Sunplus Innovation Technology          | 12        | 4.53%   |
| Apple                                  | 12        | 4.53%   |
| Suyin                                  | 8         | 3.02%   |
| Luxvisions Innotech Limited            | 8         | 3.02%   |
| Lite-On Technology                     | 6         | 2.26%   |
| Acer                                   | 6         | 2.26%   |
| Ricoh                                  | 4         | 1.51%   |
| Microsoft                              | 4         | 1.51%   |
| Alcor Micro                            | 4         | 1.51%   |
| Silicon Motion                         | 3         | 1.13%   |
| Lenovo                                 | 3         | 1.13%   |
| Sonix Technology                       | 2         | 0.75%   |
| Hewlett-Packard                        | 2         | 0.75%   |
| Z-Star Microelectronics                | 1         | 0.38%   |
| Y Media                                | 1         | 0.38%   |
| Primax Electronics                     | 1         | 0.38%   |
| Pixart Imaging                         | 1         | 0.38%   |
| Novatek Microelectronics               | 1         | 0.38%   |
| LG Electronics                         | 1         | 0.38%   |
| Goodong Industry                       | 1         | 0.38%   |
| Generalplus Technology                 | 1         | 0.38%   |
| GEMBIRD                                | 1         | 0.38%   |
| Arkmicro Technologies                  | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 15        | 5.62%   |
| Microdia Integrated_Webcam_HD                        | 7         | 2.62%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 7         | 2.62%   |
| Realtek Integrated_Webcam_HD                         | 5         | 1.87%   |
| Quanta HD User Facing                                | 5         | 1.87%   |
| IMC Networks Integrated Camera                       | 5         | 1.87%   |
| Chicony HD WebCam                                    | 5         | 1.87%   |
| Bison Integrated Camera                              | 5         | 1.87%   |
| Apple FaceTime HD Camera (Built-in)                  | 5         | 1.87%   |
| Logitech Webcam C930e                                | 4         | 1.5%    |
| Logitech Webcam C270                                 | 4         | 1.5%    |
| Chicony HD User Facing                               | 4         | 1.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 4         | 1.5%    |
| Apple Built-in iSight                                | 4         | 1.5%    |
| Quanta HP TrueVision HD Camera                       | 3         | 1.12%   |
| Microdia USB 2.0 Camera                              | 3         | 1.12%   |
| IMC Networks HD Camera                               | 3         | 1.12%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 3         | 1.12%   |
| Acer BisonCam,NB Pro                                 | 3         | 1.12%   |
| Suyin HP TrueVision HD Integrated Webcam             | 2         | 0.75%   |
| Suyin Acer CrystalEye Webcam                         | 2         | 0.75%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 0.75%   |
| Sunplus Integrated_Webcam_FHD                        | 2         | 0.75%   |
| Sunplus HD WebCam                                    | 2         | 0.75%   |
| Sunplus HD 720P webcam                               | 2         | 0.75%   |
| Ricoh USB2.0 Camera                                  | 2         | 0.75%   |
| Realtek USB2.0 HD UVC WebCam                         | 2         | 0.75%   |
| Quanta HP HD Camera                                  | 2         | 0.75%   |
| Microsoft LifeCam HD-3000                            | 2         | 0.75%   |
| Microdia Webcam Vitade AF                            | 2         | 0.75%   |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 0.75%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 0.75%   |
| Lite-On HP HD Webcam                                 | 2         | 0.75%   |
| Lite-On HP HD Camera                                 | 2         | 0.75%   |
| Lenovo Integrated Webcam [R5U877]                    | 2         | 0.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 0.75%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 2         | 0.75%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 16        | 31.37%  |
| Synaptics                          | 11        | 21.57%  |
| Shenzhen Goodix Technology         | 7         | 13.73%  |
| AuthenTec                          | 6         | 11.76%  |
| Elan Microelectronics              | 4         | 7.84%   |
| Upek                               | 3         | 5.88%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.96%   |
| Microsoft                          | 1         | 1.96%   |
| LighTuning Technology              | 1         | 1.96%   |
| Focal-systems.Corp                 | 1         | 1.96%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 9.8%    |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 9.8%    |
| Validity Sensors VFS 5011 fingerprint sensor                    | 4         | 7.84%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 3         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 3         | 5.88%   |
| AuthenTec AES2810                                               | 3         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 2         | 3.92%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 3.92%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 3.92%   |
| Elan ELAN:Fingerprint                                           | 2         | 3.92%   |
| Elan ELAN:ARM-M4                                                | 2         | 3.92%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 2         | 3.92%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 1.96%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.96%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 1.96%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 1.96%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 1.96%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 1.96%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.96%   |
| Upek TCS5B Fingerprint sensor                                   | 1         | 1.96%   |
| Synaptics WBDI Fingerprint Reader USB 102                       | 1         | 1.96%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.96%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.96%   |
| Microsoft Fingerprint Reader                                    | 1         | 1.96%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 1.96%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                       | 1         | 1.96%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 1.96%   |
| Unknown                                                         | 1         | 1.96%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 7         | 41.18%  |
| Alcor Micro           | 7         | 41.18%  |
| Advanced Card Systems | 2         | 11.76%  |
| O2 Micro              | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 7         | 41.18%  |
| Broadcom 5880                                  | 5         | 29.41%  |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor | 1         | 5.88%   |
| Broadcom 58200                                 | 1         | 5.88%   |
| Advanced Card Systems ACR38 SmartCard Reader   | 1         | 5.88%   |
| Advanced Card Systems ACR122U                  | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 281       | 65.81%  |
| 1     | 106       | 24.82%  |
| 2     | 32        | 7.49%   |
| 3     | 8         | 1.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 79        | 43.17%  |
| Fingerprint reader       | 51        | 27.87%  |
| Chipcard                 | 14        | 7.65%   |
| Net/wireless             | 13        | 7.1%    |
| Communication controller | 6         | 3.28%   |
| Multimedia controller    | 5         | 2.73%   |
| Unassigned class         | 3         | 1.64%   |
| Camera                   | 3         | 1.64%   |
| Bluetooth                | 3         | 1.64%   |
| Net/ethernet             | 2         | 1.09%   |
| Sound                    | 1         | 0.55%   |
| Flash memory             | 1         | 0.55%   |
| Dvb card                 | 1         | 0.55%   |
| Card reader              | 1         | 0.55%   |

