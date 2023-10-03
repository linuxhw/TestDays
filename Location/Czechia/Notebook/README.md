Linux in Czechia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

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

Total: 1829

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6420              | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [4575deef12](https://linux-hardware.org/?probe=4575deef12) | Sep 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S1K400    | [fd03530876](https://linux-hardware.org/?probe=fd03530876) | Sep 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [2d1ada9dbe](https://linux-hardware.org/?probe=2d1ada9dbe) | Sep 30, 2023 |
| Sony          | VPCEB4J0E                   | [05864978df](https://linux-hardware.org/?probe=05864978df) | Sep 29, 2023 |
| ASUSTek       | UX31E                       | [1b6440f722](https://linux-hardware.org/?probe=1b6440f722) | Sep 29, 2023 |
| Dell          | Precision 7710              | [89731f9b0e](https://linux-hardware.org/?probe=89731f9b0e) | Sep 29, 2023 |
| Dell          | Inspiron 5515               | [5889ba673d](https://linux-hardware.org/?probe=5889ba673d) | Sep 27, 2023 |
| Sony          | VPCEB4J0E                   | [354e2be55e](https://linux-hardware.org/?probe=354e2be55e) | Sep 27, 2023 |
| HP            | EliteBook 8470p             | [a1fa543905](https://linux-hardware.org/?probe=a1fa543905) | Sep 27, 2023 |
| Acer          | Swift SF14-71T              | [10b657bd75](https://linux-hardware.org/?probe=10b657bd75) | Sep 25, 2023 |
| Dell          | Precision 7720              | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [336d5fe8c8](https://linux-hardware.org/?probe=336d5fe8c8) | Sep 25, 2023 |
| Dell          | Latitude 7400               | [f537b79d15](https://linux-hardware.org/?probe=f537b79d15) | Sep 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a6ff891fa1](https://linux-hardware.org/?probe=a6ff891fa1) | Sep 23, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [4bb581fb16](https://linux-hardware.org/?probe=4bb581fb16) | Sep 19, 2023 |
| Acer          | Aspire ES1-420              | [db308e1798](https://linux-hardware.org/?probe=db308e1798) | Sep 19, 2023 |
| Lenovo        | ThinkPad T480 20L6SCYF0P    | [c406bf7b56](https://linux-hardware.org/?probe=c406bf7b56) | Sep 18, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [bc597f4c0c](https://linux-hardware.org/?probe=bc597f4c0c) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| Dell          | G3 3500                     | [293bbfe2d6](https://linux-hardware.org/?probe=293bbfe2d6) | Sep 12, 2023 |
| Acer          | Aspire E5-575G              | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| HP            | 240 G8 Notebook PC          | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| Dell          | Latitude 7400               | [e1ea4eb614](https://linux-hardware.org/?probe=e1ea4eb614) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | [30bf3f1f45](https://linux-hardware.org/?probe=30bf3f1f45) | Sep 05, 2023 |
| UMAX          | 13Wr                        | [574937c731](https://linux-hardware.org/?probe=574937c731) | Sep 02, 2023 |
| HP            | Unknown                     | [3809d7ad85](https://linux-hardware.org/?probe=3809d7ad85) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | [864a10779f](https://linux-hardware.org/?probe=864a10779f) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [e5a1a106cb](https://linux-hardware.org/?probe=e5a1a106cb) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS0LR00    | [a85743e60e](https://linux-hardware.org/?probe=a85743e60e) | Aug 31, 2023 |
| Acer          | Swift SF314-42              | [80bebab849](https://linux-hardware.org/?probe=80bebab849) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d6bca74de6](https://linux-hardware.org/?probe=d6bca74de6) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | K53E                        | [fa5eab9e81](https://linux-hardware.org/?probe=fa5eab9e81) | Aug 28, 2023 |
| Acer          | Aspire E1-532               | [037143c4fd](https://linux-hardware.org/?probe=037143c4fd) | Aug 27, 2023 |
| ASUSTek       | UX31E                       | [0557e95830](https://linux-hardware.org/?probe=0557e95830) | Aug 27, 2023 |
| Google        | Robo                        | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [c288ff6b78](https://linux-hardware.org/?probe=c288ff6b78) | Aug 25, 2023 |
| HP            | ZBook 14 G2                 | [7fcd619af1](https://linux-hardware.org/?probe=7fcd619af1) | Aug 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| Lenovo        | IdeaPad Z580                | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | [fcbebfc95a](https://linux-hardware.org/?probe=fcbebfc95a) | Aug 23, 2023 |
| Valve         | Jupiter                     | [904e60e2d7](https://linux-hardware.org/?probe=904e60e2d7) | Aug 23, 2023 |
| Dell          | XPS 15 9560                 | [e751db6fd4](https://linux-hardware.org/?probe=e751db6fd4) | Aug 22, 2023 |
| Valve         | Jupiter                     | [57038f50cd](https://linux-hardware.org/?probe=57038f50cd) | Aug 20, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [681310709d](https://linux-hardware.org/?probe=681310709d) | Aug 19, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b8e5fd59d3](https://linux-hardware.org/?probe=b8e5fd59d3) | Aug 18, 2023 |
| Dell          | Latitude 7440               | [aef57d5421](https://linux-hardware.org/?probe=aef57d5421) | Aug 17, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [1fcc89106f](https://linux-hardware.org/?probe=1fcc89106f) | Aug 15, 2023 |
| HP            | Laptop 17-cp0xxx            | [620d12291b](https://linux-hardware.org/?probe=620d12291b) | Aug 15, 2023 |
| Lenovo        | ThinkPad X250 20CM001RMC    | [618a7e3e29](https://linux-hardware.org/?probe=618a7e3e29) | Aug 14, 2023 |
| Dell          | XPS 13 7390                 | [f4e6886bd8](https://linux-hardware.org/?probe=f4e6886bd8) | Aug 13, 2023 |
| HP            | ZBook 17 G3                 | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| HP            | 250 G3                      | [6ba303bc6b](https://linux-hardware.org/?probe=6ba303bc6b) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ffa9b97bf7](https://linux-hardware.org/?probe=ffa9b97bf7) | Aug 10, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [82dde7d058](https://linux-hardware.org/?probe=82dde7d058) | Aug 10, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [e1462f1e3a](https://linux-hardware.org/?probe=e1462f1e3a) | Aug 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 455 G7              | [bd9f67ee72](https://linux-hardware.org/?probe=bd9f67ee72) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | [30d8fefda4](https://linux-hardware.org/?probe=30d8fefda4) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | [f1cef350fb](https://linux-hardware.org/?probe=f1cef350fb) | Aug 07, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [b69ff09aa4](https://linux-hardware.org/?probe=b69ff09aa4) | Aug 05, 2023 |
| Dell          | Latitude E6420              | [3636e69adb](https://linux-hardware.org/?probe=3636e69adb) | Aug 05, 2023 |
| Acer          | Aspire E5-572G              | [846dce7b1b](https://linux-hardware.org/?probe=846dce7b1b) | Aug 05, 2023 |
| Dell          | Latitude E5500              | [95ddcb321c](https://linux-hardware.org/?probe=95ddcb321c) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | [12ee4ed8f6](https://linux-hardware.org/?probe=12ee4ed8f6) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | [5a2ed78e49](https://linux-hardware.org/?probe=5a2ed78e49) | Aug 05, 2023 |
| Dell          | Latitude 7400               | [48e2858e56](https://linux-hardware.org/?probe=48e2858e56) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [195716ccf3](https://linux-hardware.org/?probe=195716ccf3) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [5a9a057759](https://linux-hardware.org/?probe=5a9a057759) | Aug 04, 2023 |
| Dell          | Latitude 7440               | [367f14eae6](https://linux-hardware.org/?probe=367f14eae6) | Aug 04, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [e5be227d11](https://linux-hardware.org/?probe=e5be227d11) | Aug 03, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [589f0a8599](https://linux-hardware.org/?probe=589f0a8599) | Aug 01, 2023 |
| Acer          | Aspire 1810TZ               | [8cbec4eb45](https://linux-hardware.org/?probe=8cbec4eb45) | Jul 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [5ce91f2c11](https://linux-hardware.org/?probe=5ce91f2c11) | Jul 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [6ec734b217](https://linux-hardware.org/?probe=6ec734b217) | Jul 30, 2023 |
| Acer          | Aspire 5742                 | [37be5a1c80](https://linux-hardware.org/?probe=37be5a1c80) | Jul 30, 2023 |
| ASUSTek       | UX31E                       | [a7b390cdf4](https://linux-hardware.org/?probe=a7b390cdf4) | Jul 29, 2023 |
| Google        | Edgar                       | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5497a92cf](https://linux-hardware.org/?probe=f5497a92cf) | Jul 28, 2023 |
| Acer          | Aspire A315-24P             | [6799c4be4a](https://linux-hardware.org/?probe=6799c4be4a) | Jul 27, 2023 |
| Toshiba       | Satellite A135              | [91f5602ed7](https://linux-hardware.org/?probe=91f5602ed7) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [74adf4cb3d](https://linux-hardware.org/?probe=74adf4cb3d) | Jul 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [9f384d336d](https://linux-hardware.org/?probe=9f384d336d) | Jul 23, 2023 |
| Dell          | Latitude E7440              | [ffa2aad2b5](https://linux-hardware.org/?probe=ffa2aad2b5) | Jul 21, 2023 |
| Dell          | Latitude E5530 non-vPro     | [2c2c4bdcf2](https://linux-hardware.org/?probe=2c2c4bdcf2) | Jul 21, 2023 |
| Lenovo        | B5400 80B6QB0               | [7108435241](https://linux-hardware.org/?probe=7108435241) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [cf9bdab1ee](https://linux-hardware.org/?probe=cf9bdab1ee) | Jul 13, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [f742573138](https://linux-hardware.org/?probe=f742573138) | Jul 12, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [d09af80a65](https://linux-hardware.org/?probe=d09af80a65) | Jul 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Lenovo        | ThinkPad E570 20H50074MC    | [029e84bf8a](https://linux-hardware.org/?probe=029e84bf8a) | Jul 06, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [bedadd4478](https://linux-hardware.org/?probe=bedadd4478) | Jul 05, 2023 |
| HP            | EliteBook 8770w             | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [73e054c849](https://linux-hardware.org/?probe=73e054c849) | Jul 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [5d2bd9c3ce](https://linux-hardware.org/?probe=5d2bd9c3ce) | Jul 04, 2023 |
| AMI           | Intel                       | [65aafdb0b0](https://linux-hardware.org/?probe=65aafdb0b0) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [05394ee8a5](https://linux-hardware.org/?probe=05394ee8a5) | Jul 02, 2023 |
| ASUSTek       | UX31E                       | [37a73c8939](https://linux-hardware.org/?probe=37a73c8939) | Jul 01, 2023 |
| Acer          | Swift SF314-42              | [c5820f8068](https://linux-hardware.org/?probe=c5820f8068) | Jul 01, 2023 |
| UMAX          | VisionBook-N12R             | [6144190349](https://linux-hardware.org/?probe=6144190349) | Jun 30, 2023 |
| Acer          | NC-A515-51G-59DM            | [a521f2cc60](https://linux-hardware.org/?probe=a521f2cc60) | Jun 29, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [223911e8f0](https://linux-hardware.org/?probe=223911e8f0) | Jun 25, 2023 |
| HP            | EliteBook 840 G3            | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Lenovo        | G570 20079                  | [5879c3e9ad](https://linux-hardware.org/?probe=5879c3e9ad) | Jun 22, 2023 |
| ASUSTek       | GL552VX                     | [348e36123f](https://linux-hardware.org/?probe=348e36123f) | Jun 22, 2023 |
| ASUSTek       | UX31E                       | [51b4c8d9ef](https://linux-hardware.org/?probe=51b4c8d9ef) | Jun 22, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [61ba243843](https://linux-hardware.org/?probe=61ba243843) | Jun 21, 2023 |
| Acer          | Aspire ES1-420              | [76aab864d4](https://linux-hardware.org/?probe=76aab864d4) | Jun 19, 2023 |
| Dell          | Latitude E6540              | [3721b0046f](https://linux-hardware.org/?probe=3721b0046f) | Jun 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [0806a6be0a](https://linux-hardware.org/?probe=0806a6be0a) | Jun 19, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| Dell          | Latitude 5420               | [d3327c76f1](https://linux-hardware.org/?probe=d3327c76f1) | Jun 15, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| Acer          | Aspire ES1-420              | [5c3a2078ca](https://linux-hardware.org/?probe=5c3a2078ca) | Jun 14, 2023 |
| Dell          | XPS 15 9500                 | [77ce1af9f8](https://linux-hardware.org/?probe=77ce1af9f8) | Jun 13, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [edf817eef9](https://linux-hardware.org/?probe=edf817eef9) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [5c98700539](https://linux-hardware.org/?probe=5c98700539) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f6e70e460f](https://linux-hardware.org/?probe=f6e70e460f) | Jun 11, 2023 |
| Dell          | Latitude 5420               | [956a995580](https://linux-hardware.org/?probe=956a995580) | Jun 09, 2023 |
| HP            | Laptop 15s-fq2xxx           | [09ba95bf3b](https://linux-hardware.org/?probe=09ba95bf3b) | Jun 08, 2023 |
| HP            | Laptop 15s-fq2xxx           | [9d0aa12b81](https://linux-hardware.org/?probe=9d0aa12b81) | Jun 06, 2023 |
| ASUSTek       | UX31E                       | [92d0de412b](https://linux-hardware.org/?probe=92d0de412b) | Jun 06, 2023 |
| Dell          | Latitude 7400               | [9968377d89](https://linux-hardware.org/?probe=9968377d89) | Jun 06, 2023 |
| Acer          | Nitro AN515-44              | [d7a2c59432](https://linux-hardware.org/?probe=d7a2c59432) | Jun 05, 2023 |
| Lenovo        | ThinkPad T420 4236WQD       | [69a63f31e1](https://linux-hardware.org/?probe=69a63f31e1) | Jun 03, 2023 |
| Timi          | A35S                        | [c9ce47a446](https://linux-hardware.org/?probe=c9ce47a446) | Jun 01, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [643710864a](https://linux-hardware.org/?probe=643710864a) | May 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | [ea6330526c](https://linux-hardware.org/?probe=ea6330526c) | May 29, 2023 |
| Acer          | Aspire 7540                 | [82fcb3124c](https://linux-hardware.org/?probe=82fcb3124c) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [56fca4583d](https://linux-hardware.org/?probe=56fca4583d) | May 28, 2023 |
| Lenovo        | ThinkPad P51 20HJS01Q04     | [520eb0074c](https://linux-hardware.org/?probe=520eb0074c) | May 26, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DQ02    | [bb00a96df8](https://linux-hardware.org/?probe=bb00a96df8) | May 25, 2023 |
| Unknown       | Unknown                     | [cfaffcaa0a](https://linux-hardware.org/?probe=cfaffcaa0a) | May 25, 2023 |
| Dell          | G15 5511                    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| Dell          | G5 5587                     | [18faf1497f](https://linux-hardware.org/?probe=18faf1497f) | May 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [2fffd70abb](https://linux-hardware.org/?probe=2fffd70abb) | May 23, 2023 |
| Dell          | Vostro 5620                 | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Dell          | G15 5511                    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f8329fecb](https://linux-hardware.org/?probe=0f8329fecb) | May 20, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| HP            | ProBook 4540s               | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| Dell          | Latitude 5521               | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [b4e8e5504e](https://linux-hardware.org/?probe=b4e8e5504e) | May 15, 2023 |
| HP            | 250 G8 Notebook PC          | [14aeaeafe8](https://linux-hardware.org/?probe=14aeaeafe8) | May 15, 2023 |
| ASUSTek       | UX31E                       | [53f535546a](https://linux-hardware.org/?probe=53f535546a) | May 12, 2023 |
| Dell          | Latitude 7400               | [14de9baf53](https://linux-hardware.org/?probe=14de9baf53) | May 12, 2023 |
| Dell          | Vostro 5620                 | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| eMachines     | E620                        | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| HP            | EliteBook 8470p             | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Dell          | Latitude E7450              | [0eff8f87c6](https://linux-hardware.org/?probe=0eff8f87c6) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| Valve         | Jupiter                     | [1f41754528](https://linux-hardware.org/?probe=1f41754528) | May 03, 2023 |
| Apple         | MacBookAir3,1               | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| ASUSTek       | UX31E                       | [1fb0ca13ff](https://linux-hardware.org/?probe=1fb0ca13ff) | May 01, 2023 |
| Acer          | Extensa 5620                | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| ASUSTek       | UX31E                       | [e2c8068a7d](https://linux-hardware.org/?probe=e2c8068a7d) | Apr 28, 2023 |
| Acer          | Aspire E1-572G              | [6c35501215](https://linux-hardware.org/?probe=6c35501215) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | [fa228f68e4](https://linux-hardware.org/?probe=fa228f68e4) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | [33bc801258](https://linux-hardware.org/?probe=33bc801258) | Apr 26, 2023 |
| HP            | ProBook 4540s               | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Valve         | Jupiter                     | [9b44e9bc2c](https://linux-hardware.org/?probe=9b44e9bc2c) | Apr 25, 2023 |
| Valve         | Jupiter                     | [7c7421ffeb](https://linux-hardware.org/?probe=7c7421ffeb) | Apr 25, 2023 |
| Dell          | System XPS L502X            | [4fd4992d0f](https://linux-hardware.org/?probe=4fd4992d0f) | Apr 24, 2023 |
| HP            | ProBook 4540s               | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [db069c8b89](https://linux-hardware.org/?probe=db069c8b89) | Apr 21, 2023 |
| Acer          | Nitro AN515-45              | [91f538e2ab](https://linux-hardware.org/?probe=91f538e2ab) | Apr 21, 2023 |
| UMAX          | VisionBook 14Wa Pro         | [525241657b](https://linux-hardware.org/?probe=525241657b) | Apr 20, 2023 |
| UMAX          | VisionBook 14Wa Pro         | [07e2728dfe](https://linux-hardware.org/?probe=07e2728dfe) | Apr 20, 2023 |
| Lenovo        | ThinkPad P52 20MAS5KM00     | [06ab19cc37](https://linux-hardware.org/?probe=06ab19cc37) | Apr 20, 2023 |
| HP            | Laptop 15-db1xxx            | [f158ac4161](https://linux-hardware.org/?probe=f158ac4161) | Apr 17, 2023 |
| Acer          | Aspire ES1-731G             | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [59d15de09e](https://linux-hardware.org/?probe=59d15de09e) | Apr 15, 2023 |
| ASUSTek       | UX31E                       | [429e68a4ac](https://linux-hardware.org/?probe=429e68a4ac) | Apr 14, 2023 |
| HP            | ProBook 450 G6              | [3364cf411c](https://linux-hardware.org/?probe=3364cf411c) | Apr 13, 2023 |
| Acer          | Aspire one                  | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [9a592d3392](https://linux-hardware.org/?probe=9a592d3392) | Apr 11, 2023 |
| Acer          | Aspire A515-47              | [8a78c5b08f](https://linux-hardware.org/?probe=8a78c5b08f) | Apr 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [2652354b7a](https://linux-hardware.org/?probe=2652354b7a) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [e5393f2dd6](https://linux-hardware.org/?probe=e5393f2dd6) | Apr 07, 2023 |
| ASUSTek       | UX31E                       | [3a1b0cca6b](https://linux-hardware.org/?probe=3a1b0cca6b) | Apr 04, 2023 |
| Apple         | MacBookPro12,1              | [b1168b92c0](https://linux-hardware.org/?probe=b1168b92c0) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Notebook      | NJ50GU                      | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e3078a63c3](https://linux-hardware.org/?probe=e3078a63c3) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1c8c26f5c0](https://linux-hardware.org/?probe=1c8c26f5c0) | Apr 02, 2023 |
| HP            | 250 G3                      | [2030ba57b9](https://linux-hardware.org/?probe=2030ba57b9) | Apr 02, 2023 |
| Dell          | Latitude 5511               | [86b4fcff61](https://linux-hardware.org/?probe=86b4fcff61) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420s 4173R44      | [84e9a5f3d9](https://linux-hardware.org/?probe=84e9a5f3d9) | Apr 01, 2023 |
| UMAX          | VisionBook 14Wa Plus        | [ea8016c4a5](https://linux-hardware.org/?probe=ea8016c4a5) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0014e52bf3](https://linux-hardware.org/?probe=0014e52bf3) | Mar 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0ffc78eac6](https://linux-hardware.org/?probe=0ffc78eac6) | Mar 30, 2023 |
| ASUSTek       | F7L                         | [8d6f90f843](https://linux-hardware.org/?probe=8d6f90f843) | Mar 29, 2023 |
| ASUSTek       | F7L                         | [cdc5ab3b8a](https://linux-hardware.org/?probe=cdc5ab3b8a) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | [6599d32d74](https://linux-hardware.org/?probe=6599d32d74) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | [64bef0aff5](https://linux-hardware.org/?probe=64bef0aff5) | Mar 29, 2023 |
| Lenovo        | ThinkPad T580 20LAS4L216    | [9c3464baf9](https://linux-hardware.org/?probe=9c3464baf9) | Mar 27, 2023 |
| HP            | 250 G6 Notebook PC          | [eb82e949b2](https://linux-hardware.org/?probe=eb82e949b2) | Mar 27, 2023 |
| Lenovo        | G780                        | [1ad87e5add](https://linux-hardware.org/?probe=1ad87e5add) | Mar 23, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [aa102c68bf](https://linux-hardware.org/?probe=aa102c68bf) | Mar 23, 2023 |
| HP            | ProBook 450 G2              | [47992266f4](https://linux-hardware.org/?probe=47992266f4) | Mar 22, 2023 |
| HP            | ProBook 450 G2              | [dc56e35adc](https://linux-hardware.org/?probe=dc56e35adc) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Dell          | Latitude 5590               | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Acer          | TravelMate 2490             | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| ASUSTek       | UX31E                       | [b637fa75c8](https://linux-hardware.org/?probe=b637fa75c8) | Mar 18, 2023 |
| Acer          | TravelMate 7750ZG           | [5108cfe57c](https://linux-hardware.org/?probe=5108cfe57c) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| Dell          | Inspiron 5767               | [b7c8484508](https://linux-hardware.org/?probe=b7c8484508) | Mar 14, 2023 |
| ASUSTek       | UX31E                       | [7f3525f6ef](https://linux-hardware.org/?probe=7f3525f6ef) | Mar 12, 2023 |
| Dell          | Inspiron 5748               | [ef020a54d0](https://linux-hardware.org/?probe=ef020a54d0) | Mar 12, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| ASUSTek       | K54LY                       | [a846675d7f](https://linux-hardware.org/?probe=a846675d7f) | Mar 09, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | [fda0cb7297](https://linux-hardware.org/?probe=fda0cb7297) | Mar 08, 2023 |
| Dell          | Latitude E6420              | [c3384b7787](https://linux-hardware.org/?probe=c3384b7787) | Mar 07, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | [707155405b](https://linux-hardware.org/?probe=707155405b) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| ASUSTek       | UX31E                       | [ba97297cf9](https://linux-hardware.org/?probe=ba97297cf9) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G531GT            | [810e15295b](https://linux-hardware.org/?probe=810e15295b) | Mar 03, 2023 |
| Dell          | Latitude 5421               | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| ASUSTek       | X555LA                      | [5dbbffb04e](https://linux-hardware.org/?probe=5dbbffb04e) | Mar 02, 2023 |
| UMAX          | VisionBook-N12R             | [2477ae9a0e](https://linux-hardware.org/?probe=2477ae9a0e) | Feb 27, 2023 |
| Standard      | Unknown                     | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [f0fa613cd2](https://linux-hardware.org/?probe=f0fa613cd2) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude 5420               | [231c7534d3](https://linux-hardware.org/?probe=231c7534d3) | Feb 21, 2023 |
| HP            | Laptop 15-rb0xx             | [3dd7359a43](https://linux-hardware.org/?probe=3dd7359a43) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | [53ef54922c](https://linux-hardware.org/?probe=53ef54922c) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| Toshiba       | Satellite L50D-B            | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| Dell          | Vostro1710                  | [91b1af7ed6](https://linux-hardware.org/?probe=91b1af7ed6) | Feb 19, 2023 |
| Standard      | Unknown                     | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | UX31E                       | [4c3c50a992](https://linux-hardware.org/?probe=4c3c50a992) | Feb 18, 2023 |
| ASUSTek       | UX31E                       | [e6391763b2](https://linux-hardware.org/?probe=e6391763b2) | Feb 17, 2023 |
| HP            | Laptop 17-cn0xxx            | [0e2199617b](https://linux-hardware.org/?probe=0e2199617b) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [6c8bdf1f73](https://linux-hardware.org/?probe=6c8bdf1f73) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [89f9d45c66](https://linux-hardware.org/?probe=89f9d45c66) | Feb 17, 2023 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [f546833d76](https://linux-hardware.org/?probe=f546833d76) | Feb 17, 2023 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [1026c10fa9](https://linux-hardware.org/?probe=1026c10fa9) | Feb 16, 2023 |
| ASUSTek       | UX31E                       | [0255141f61](https://linux-hardware.org/?probe=0255141f61) | Feb 15, 2023 |
| HP            | ProBook 470 G4              | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Pavilion g6                 | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| HP            | OMEN by Laptop              | [849a50c7fd](https://linux-hardware.org/?probe=849a50c7fd) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| Acer          | Swift SF314-42              | [938edcc32a](https://linux-hardware.org/?probe=938edcc32a) | Feb 15, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| MSI           | GX700                       | [11154709fd](https://linux-hardware.org/?probe=11154709fd) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| ASUSTek       | UX31E                       | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [16d6cdad97](https://linux-hardware.org/?probe=16d6cdad97) | Feb 09, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| HP            | Laptop 15-db0xxx            | [8cb1801046](https://linux-hardware.org/?probe=8cb1801046) | Feb 07, 2023 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [e9082b6ebf](https://linux-hardware.org/?probe=e9082b6ebf) | Feb 04, 2023 |
| HP            | OMEN by Laptop              | [330da24dc9](https://linux-hardware.org/?probe=330da24dc9) | Feb 04, 2023 |
| HP            | ProBook 4530s               | [9ff88cbe9a](https://linux-hardware.org/?probe=9ff88cbe9a) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | [922ee5ede0](https://linux-hardware.org/?probe=922ee5ede0) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| HP            | Stream Notebook PC 14       | [69628da41b](https://linux-hardware.org/?probe=69628da41b) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | [3bcca39276](https://linux-hardware.org/?probe=3bcca39276) | Feb 02, 2023 |
| HP            | OMEN by Laptop              | [1651e1e5af](https://linux-hardware.org/?probe=1651e1e5af) | Feb 02, 2023 |
| ASUSTek       | GL702VT                     | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| Lenovo        | ThinkPad E520 1143JYG       | [87735dd3b0](https://linux-hardware.org/?probe=87735dd3b0) | Feb 01, 2023 |
| HP            | Laptop 15-bw0xx             | [b7fce61d74](https://linux-hardware.org/?probe=b7fce61d74) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
| HP            | Compaq CQ58                 | [63dfd6ca48](https://linux-hardware.org/?probe=63dfd6ca48) | Jan 30, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| ASUSTek       | X200MA                      | [1c1f2d4d5b](https://linux-hardware.org/?probe=1c1f2d4d5b) | Jan 28, 2023 |
| Timi          | A35S                        | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| ASUSTek       | UX31E                       | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| HP            | EliteBook 8460p             | [bb83f545f7](https://linux-hardware.org/?probe=bb83f545f7) | Jan 24, 2023 |
| Dell          | Latitude 5530               | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Dell          | Precision 3530              | [f0fa541c85](https://linux-hardware.org/?probe=f0fa541c85) | Jan 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| ASUSTek       | UX303LN                     | [60f8946cdf](https://linux-hardware.org/?probe=60f8946cdf) | Jan 21, 2023 |
| Lenovo        | Yoga 700-14ISK 80QD         | [4e07ace043](https://linux-hardware.org/?probe=4e07ace043) | Jan 21, 2023 |
| ASUSTek       | UX303LN                     | [846e3df466](https://linux-hardware.org/?probe=846e3df466) | Jan 21, 2023 |
| HP            | EliteBook 8570p             | [66c806fbfe](https://linux-hardware.org/?probe=66c806fbfe) | Jan 21, 2023 |
| ASUSTek       | X555LF                      | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f7fcfb7b18](https://linux-hardware.org/?probe=f7fcfb7b18) | Jan 19, 2023 |
| ASUSTek       | 1011PX                      | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad E550 20DF0081MC    | [1b7e734f36](https://linux-hardware.org/?probe=1b7e734f36) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [5b0e671bb8](https://linux-hardware.org/?probe=5b0e671bb8) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [395a44652b](https://linux-hardware.org/?probe=395a44652b) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [fa4fd9061f](https://linux-hardware.org/?probe=fa4fd9061f) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [6841633faf](https://linux-hardware.org/?probe=6841633faf) | Jan 16, 2023 |
| HP            | Pavilion dv6500             | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| HP            | 250 G3                      | [717fbc7972](https://linux-hardware.org/?probe=717fbc7972) | Jan 15, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [32f2651aa1](https://linux-hardware.org/?probe=32f2651aa1) | Jan 14, 2023 |
| HP            | ProBook 6560b               | [a9eba68b79](https://linux-hardware.org/?probe=a9eba68b79) | Jan 14, 2023 |
| ASUSTek       | UX31E                       | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Lenovo        | ThinkPad T450 20BUA0UG00    | [b0854ecbf8](https://linux-hardware.org/?probe=b0854ecbf8) | Jan 12, 2023 |
| Acer          | Extensa 2519                | [c044faaa05](https://linux-hardware.org/?probe=c044faaa05) | Jan 11, 2023 |
| Dell          | Precision 7710              | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| HP            | Laptop 15-rb0xx             | [fd8d969adb](https://linux-hardware.org/?probe=fd8d969adb) | Jan 11, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [e4c19089b5](https://linux-hardware.org/?probe=e4c19089b5) | Jan 11, 2023 |
| Dell          | Precision 5510              | [22a344ddad](https://linux-hardware.org/?probe=22a344ddad) | Jan 09, 2023 |
| HP            | EliteBook 840 G1            | [42f10f6d45](https://linux-hardware.org/?probe=42f10f6d45) | Jan 09, 2023 |
| Dell          | Precision 7710              | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| Lenovo        | ThinkPad X230 2320JNG       | [29d3023af5](https://linux-hardware.org/?probe=29d3023af5) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| UMAX          | VisionBook N14G Plus        | [412180b4de](https://linux-hardware.org/?probe=412180b4de) | Jan 06, 2023 |
| Acer          | TravelMate B115-M           | [c39cf71ff8](https://linux-hardware.org/?probe=c39cf71ff8) | Jan 05, 2023 |
| ASUSTek       | X405UA                      | [c56206ea8a](https://linux-hardware.org/?probe=c56206ea8a) | Jan 05, 2023 |
| Acer          | Aspire E1-531G              | [9b5a0200df](https://linux-hardware.org/?probe=9b5a0200df) | Jan 04, 2023 |
| Acer          | Aspire E1-531G              | [47813fa627](https://linux-hardware.org/?probe=47813fa627) | Jan 03, 2023 |
| HP            | ProBook 635 Aero G8         | [f710248f3c](https://linux-hardware.org/?probe=f710248f3c) | Jan 02, 2023 |
| Google        | Chell                       | [02a0ae3bea](https://linux-hardware.org/?probe=02a0ae3bea) | Jan 02, 2023 |
| Valve         | Jupiter                     | [dc3612b4e1](https://linux-hardware.org/?probe=dc3612b4e1) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Acer          | Aspire A515-47              | [aaf0830ffc](https://linux-hardware.org/?probe=aaf0830ffc) | Jan 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [bd53b75b7b](https://linux-hardware.org/?probe=bd53b75b7b) | Dec 30, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [2b646304f0](https://linux-hardware.org/?probe=2b646304f0) | Dec 29, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [74f8dcfbb4](https://linux-hardware.org/?probe=74f8dcfbb4) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK E736               | [8d54484965](https://linux-hardware.org/?probe=8d54484965) | Dec 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| UMAX          | VisionBook 14Wa Pro         | [7eb49ce0ab](https://linux-hardware.org/?probe=7eb49ce0ab) | Dec 24, 2022 |
| UMAX          | VisionBook 14Wa Pro         | [4123115ef0](https://linux-hardware.org/?probe=4123115ef0) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2b25ab8790](https://linux-hardware.org/?probe=2b25ab8790) | Dec 22, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c20be92503](https://linux-hardware.org/?probe=c20be92503) | Dec 19, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [3fe5be03b1](https://linux-hardware.org/?probe=3fe5be03b1) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b34d0f3a2c](https://linux-hardware.org/?probe=b34d0f3a2c) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| HP            | Pavilion TS 11              | [db2a3e8ebb](https://linux-hardware.org/?probe=db2a3e8ebb) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | [b5d4116615](https://linux-hardware.org/?probe=b5d4116615) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | [144f698515](https://linux-hardware.org/?probe=144f698515) | Dec 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [6e2cf6514a](https://linux-hardware.org/?probe=6e2cf6514a) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [b9ea8b5b2b](https://linux-hardware.org/?probe=b9ea8b5b2b) | Dec 08, 2022 |
| ASUSTek       | X55A                        | [283ef64c76](https://linux-hardware.org/?probe=283ef64c76) | Dec 08, 2022 |
| ASUSTek       | UX31E                       | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| MSI           | Prestige 14 A11SCX          | [2b5a2c145c](https://linux-hardware.org/?probe=2b5a2c145c) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS2291X    | [312119ddbd](https://linux-hardware.org/?probe=312119ddbd) | Dec 06, 2022 |
| MSI           | Prestige 14 A11SCX          | [ca5bc5dfe6](https://linux-hardware.org/?probe=ca5bc5dfe6) | Dec 05, 2022 |
| ASUSTek       | UX31E                       | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [e44ba4a41b](https://linux-hardware.org/?probe=e44ba4a41b) | Dec 03, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [2b1a977b21](https://linux-hardware.org/?probe=2b1a977b21) | Dec 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5955142015](https://linux-hardware.org/?probe=5955142015) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ea8b9066f6](https://linux-hardware.org/?probe=ea8b9066f6) | Nov 30, 2022 |
| HP            | 620                         | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| Fujitsu       | LIFEBOOK E756               | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [53b311f78c](https://linux-hardware.org/?probe=53b311f78c) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| HP            | 620                         | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| MSI           | Modern 14 B5M               | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| ASUSTek       | N73SV                       | [10840bac50](https://linux-hardware.org/?probe=10840bac50) | Nov 20, 2022 |
| ASUSTek       | K50IJ                       | [c57a9ae3d5](https://linux-hardware.org/?probe=c57a9ae3d5) | Nov 19, 2022 |
| ASUSTek       | K50IJ                       | [99ed91b58d](https://linux-hardware.org/?probe=99ed91b58d) | Nov 19, 2022 |
| Dell          | Precision 5510              | [a9467ec69d](https://linux-hardware.org/?probe=a9467ec69d) | Nov 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| ASUSTek       | K50IJ                       | [c7ac1636bc](https://linux-hardware.org/?probe=c7ac1636bc) | Nov 15, 2022 |
| ASUSTek       | N61Jv                       | [c8c143ccdd](https://linux-hardware.org/?probe=c8c143ccdd) | Nov 14, 2022 |
| ASUSTek       | N61Jv                       | [bc9518dbad](https://linux-hardware.org/?probe=bc9518dbad) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | [a7e35fd231](https://linux-hardware.org/?probe=a7e35fd231) | Nov 12, 2022 |
| Dell          | Latitude 7480               | [62d1e401a4](https://linux-hardware.org/?probe=62d1e401a4) | Nov 12, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| Dell          | Latitude 7480               | [350e3f7ee2](https://linux-hardware.org/?probe=350e3f7ee2) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| HP            | Pavilion dv7                | [5b01559647](https://linux-hardware.org/?probe=5b01559647) | Nov 11, 2022 |
| ASUSTek       | K54LY                       | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| ASUSTek       | X550VXK                     | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Packard Be... | EasyNote TK85               | [8a4f5a2c29](https://linux-hardware.org/?probe=8a4f5a2c29) | Nov 07, 2022 |
| HP            | ProBook 4530s               | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| Dell          | Inspiron 5515               | [fcb59bae39](https://linux-hardware.org/?probe=fcb59bae39) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | [001308a248](https://linux-hardware.org/?probe=001308a248) | Nov 06, 2022 |
| HP            | Pavilion g6                 | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| HP            | Pavilion g6                 | [38b8d5a898](https://linux-hardware.org/?probe=38b8d5a898) | Nov 04, 2022 |
| Acer          | Aspire 5738                 | [f5ac63680f](https://linux-hardware.org/?probe=f5ac63680f) | Nov 04, 2022 |
| SLIMBOOK      | Executive                   | [cff86cc921](https://linux-hardware.org/?probe=cff86cc921) | Nov 04, 2022 |
| Sony          | VPCYB1S1E                   | [54d0a26de9](https://linux-hardware.org/?probe=54d0a26de9) | Nov 03, 2022 |
| UMAX          | VisionBook N15G Plus        | [eba9cd6286](https://linux-hardware.org/?probe=eba9cd6286) | Nov 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [e4f3828910](https://linux-hardware.org/?probe=e4f3828910) | Nov 01, 2022 |
| ASUSTek       | UX31E                       | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| UMAX          | VisionBook 12Wi 64G         | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| Lenovo        | B590 20206                  | [8a8967999b](https://linux-hardware.org/?probe=8a8967999b) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [307356784a](https://linux-hardware.org/?probe=307356784a) | Oct 26, 2022 |
| Apple         | MacBookPro10,1              | [212ce8900d](https://linux-hardware.org/?probe=212ce8900d) | Oct 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| HP            | Pavilion dv7                | [4c6edfec3e](https://linux-hardware.org/?probe=4c6edfec3e) | Oct 18, 2022 |
| HP            | Pavilion dv7                | [22031176a8](https://linux-hardware.org/?probe=22031176a8) | Oct 18, 2022 |
| ASUSTek       | UX31E                       | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| Dell          | XPS 15 9550                 | [00d5f7c4b1](https://linux-hardware.org/?probe=00d5f7c4b1) | Oct 13, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| SmbiosType... | SmbiosType1_SystemProduc... | [d105b4c1f7](https://linux-hardware.org/?probe=d105b4c1f7) | Oct 11, 2022 |
| ASUSTek       | UX31E                       | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| Dell          | Latitude E7250              | [5ecb7bbb6c](https://linux-hardware.org/?probe=5ecb7bbb6c) | Oct 07, 2022 |
| ASUSTek       | 1001PXD                     | [524e4ab046](https://linux-hardware.org/?probe=524e4ab046) | Oct 06, 2022 |
| HP            | EliteBook 1040 G4           | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| Timi          | A35S                        | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | [7c19c1f557](https://linux-hardware.org/?probe=7c19c1f557) | Oct 02, 2022 |
| Acer          | Aspire 7540                 | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| ASUSTek       | K54LY                       | [98197c818f](https://linux-hardware.org/?probe=98197c818f) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [92f9efe077](https://linux-hardware.org/?probe=92f9efe077) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [9377d23abd](https://linux-hardware.org/?probe=9377d23abd) | Sep 28, 2022 |
| Timi          | A35S                        | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | K53SV                       | [d2801f9560](https://linux-hardware.org/?probe=d2801f9560) | Sep 26, 2022 |
| Lenovo        | 3000 V100 076346G           | [0575c1ea4f](https://linux-hardware.org/?probe=0575c1ea4f) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| Timi          | RedmiBook 16                | [0a65bab615](https://linux-hardware.org/?probe=0a65bab615) | Sep 25, 2022 |
| Acer          | Aspire VN7-592G             | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| HP            | ProBook 450 G5              | [262ff53f6a](https://linux-hardware.org/?probe=262ff53f6a) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [d1ed6b20cf](https://linux-hardware.org/?probe=d1ed6b20cf) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [9e04fb330b](https://linux-hardware.org/?probe=9e04fb330b) | Sep 24, 2022 |
| Timi          | A35S                        | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Valve         | Jupiter                     | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Acer          | Nitro AN515-57              | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| Lenovo        | IdeaPad Y570 20091          | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Dell          | Latitude 5430               | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| Lenovo        | ThinkPad T540p 20BF002CM... | [3343da6005](https://linux-hardware.org/?probe=3343da6005) | Sep 12, 2022 |
| ASUSTek       | UX31E                       | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| UMAX          | VisionBook N15G Plus        | [d17fb4f8f9](https://linux-hardware.org/?probe=d17fb4f8f9) | Sep 11, 2022 |
| Dell          | Latitude 5531               | [66eac260ef](https://linux-hardware.org/?probe=66eac260ef) | Sep 09, 2022 |
| Dell          | Precision 3551              | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
| Lenovo        | B71-80 80RJ                 | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Dell          | Latitude 5531               | [dff44a5e24](https://linux-hardware.org/?probe=dff44a5e24) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Google        | Coral                       | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| ASUSTek       | UX31E                       | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [60b4add0a0](https://linux-hardware.org/?probe=60b4add0a0) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [2a3eb4b772](https://linux-hardware.org/?probe=2a3eb4b772) | Sep 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cc30fbdce2](https://linux-hardware.org/?probe=cc30fbdce2) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| HP            | EliteBook 650 15.6 inch ... | [918418e0fc](https://linux-hardware.org/?probe=918418e0fc) | Aug 29, 2022 |
| ASUSTek       | X553MA                      | [108e0c7803](https://linux-hardware.org/?probe=108e0c7803) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [bddbedffed](https://linux-hardware.org/?probe=bddbedffed) | Aug 29, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Valve         | Jupiter                     | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| MSI           | GS73VR 6RF                  | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| Dell          | Latitude 5490               | [a37eabe03f](https://linux-hardware.org/?probe=a37eabe03f) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2e77015116](https://linux-hardware.org/?probe=2e77015116) | Aug 21, 2022 |
| ASUSTek       | UX31E                       | [84ed4c9d73](https://linux-hardware.org/?probe=84ed4c9d73) | Aug 20, 2022 |
| HP            | ElitePad 1000 G2            | [ed06ba603c](https://linux-hardware.org/?probe=ed06ba603c) | Aug 19, 2022 |
| Lenovo        | ThinkPad Edge E431 62774... | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| HP            | ZBook 15 G3                 | [f89a185aa6](https://linux-hardware.org/?probe=f89a185aa6) | Aug 17, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Acer          | Aspire 3100                 | [8ea61dbd3c](https://linux-hardware.org/?probe=8ea61dbd3c) | Aug 14, 2022 |
| Acer          | Aspire A515-56              | [e93f8de88b](https://linux-hardware.org/?probe=e93f8de88b) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | [e429237c05](https://linux-hardware.org/?probe=e429237c05) | Aug 13, 2022 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [0f367345a0](https://linux-hardware.org/?probe=0f367345a0) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad E590 20NB0029MC    | [233b3cdd54](https://linux-hardware.org/?probe=233b3cdd54) | Aug 11, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [8b0ede5e40](https://linux-hardware.org/?probe=8b0ede5e40) | Aug 10, 2022 |
| HUAWEI        | BOHB-WAX9                   | [9d55b54de7](https://linux-hardware.org/?probe=9d55b54de7) | Aug 10, 2022 |
| Dell          | Latitude 5421               | [b088f6b599](https://linux-hardware.org/?probe=b088f6b599) | Aug 10, 2022 |
| Dell          | Latitude 5531               | [64998a7d5a](https://linux-hardware.org/?probe=64998a7d5a) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [9c945add4e](https://linux-hardware.org/?probe=9c945add4e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [d1ab7d1d36](https://linux-hardware.org/?probe=d1ab7d1d36) | Aug 06, 2022 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [2577ffae50](https://linux-hardware.org/?probe=2577ffae50) | Aug 06, 2022 |
| Dell          | Inspiron 5558               | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| HP            | 250 G5 Notebook PC          | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [45e79d015c](https://linux-hardware.org/?probe=45e79d015c) | Jul 23, 2022 |
| ASUSTek       | UX31E                       | [1ae28afad9](https://linux-hardware.org/?probe=1ae28afad9) | Jul 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c000bcc566](https://linux-hardware.org/?probe=c000bcc566) | Jul 20, 2022 |
| HP            | ProBook 450 G5              | [47c85dbefd](https://linux-hardware.org/?probe=47c85dbefd) | Jul 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [179267a713](https://linux-hardware.org/?probe=179267a713) | Jul 15, 2022 |
| Dell          | G3 3590                     | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | K54LY                       | [9b66e8ad0e](https://linux-hardware.org/?probe=9b66e8ad0e) | Jul 14, 2022 |
| ASUSTek       | UX31E                       | [004f74eaf4](https://linux-hardware.org/?probe=004f74eaf4) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| HP            | ProBook 450 G5              | [e3962f34e4](https://linux-hardware.org/?probe=e3962f34e4) | Jul 11, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | ProBook 450 G5              | [90f45f2ebc](https://linux-hardware.org/?probe=90f45f2ebc) | Jul 08, 2022 |
| Dell          | XPS 15 9510                 | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6a78826e86](https://linux-hardware.org/?probe=6a78826e86) | Jul 07, 2022 |
| ASUSTek       | X542UQR                     | [04cc10b779](https://linux-hardware.org/?probe=04cc10b779) | Jul 07, 2022 |
| Dell          | Inspiron 3542               | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| HP            | ProBook 4530s               | [db207530bc](https://linux-hardware.org/?probe=db207530bc) | Jul 06, 2022 |
| HP            | Notebook                    | [9b87d6ee2d](https://linux-hardware.org/?probe=9b87d6ee2d) | Jul 06, 2022 |
| Dell          | Latitude 7520               | [531ccedcf2](https://linux-hardware.org/?probe=531ccedcf2) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| HP            | 625                         | [0acc5581d4](https://linux-hardware.org/?probe=0acc5581d4) | Jul 03, 2022 |
| ASUSTek       | UX31E                       | [7504f06baa](https://linux-hardware.org/?probe=7504f06baa) | Jul 02, 2022 |
| Lenovo        | Z70-80 80FG                 | [eaf34443c7](https://linux-hardware.org/?probe=eaf34443c7) | Jul 01, 2022 |
| ASUSTek       | UX31E                       | [d3f27ab291](https://linux-hardware.org/?probe=d3f27ab291) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [bef849e3d1](https://linux-hardware.org/?probe=bef849e3d1) | Jun 29, 2022 |
| Lenovo        | ThinkPad S5-S540 20B3001... | [d5be9c4fca](https://linux-hardware.org/?probe=d5be9c4fca) | Jun 29, 2022 |
| Valve         | Jupiter                     | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| ASUSTek       | UX31E                       | [a346ece8f5](https://linux-hardware.org/?probe=a346ece8f5) | Jun 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| Dell          | Precision 5550              | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| Dell          | Precision 5550              | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [6ed235813a](https://linux-hardware.org/?probe=6ed235813a) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [af51b1d9da](https://linux-hardware.org/?probe=af51b1d9da) | Jun 19, 2022 |
| Dell          | Latitude E5470              | [e18ba2b5d7](https://linux-hardware.org/?probe=e18ba2b5d7) | Jun 18, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [4a8b021e76](https://linux-hardware.org/?probe=4a8b021e76) | Jun 11, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| Lenovo        | ThinkPad T460s 20FA003JM... | [417d162cab](https://linux-hardware.org/?probe=417d162cab) | Jun 09, 2022 |
| ASUSTek       | UX31E                       | [4abfa2a1d0](https://linux-hardware.org/?probe=4abfa2a1d0) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [81335c6978](https://linux-hardware.org/?probe=81335c6978) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | [62d39f4677](https://linux-hardware.org/?probe=62d39f4677) | Jun 08, 2022 |
| ASUSTek       | K54LY                       | [39ad69783e](https://linux-hardware.org/?probe=39ad69783e) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [77b282aaaa](https://linux-hardware.org/?probe=77b282aaaa) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [b320ea6050](https://linux-hardware.org/?probe=b320ea6050) | Jun 05, 2022 |
| MSI           | GP72 7QF                    | [ad0e85dbf9](https://linux-hardware.org/?probe=ad0e85dbf9) | Jun 05, 2022 |
| ASUSTek       | UX31E                       | [250825e17e](https://linux-hardware.org/?probe=250825e17e) | Jun 03, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [ac88b5f927](https://linux-hardware.org/?probe=ac88b5f927) | Jun 03, 2022 |
| HP            | ProBook 450 G7              | [010b492184](https://linux-hardware.org/?probe=010b492184) | May 31, 2022 |
| ASUSTek       | UX31E                       | [201add5732](https://linux-hardware.org/?probe=201add5732) | May 29, 2022 |
| HP            | Pavilion dv6                | [3623a980f8](https://linux-hardware.org/?probe=3623a980f8) | May 28, 2022 |
| HP            | EliteBook 8760w             | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| ASUSTek       | UX31E                       | [3905de150e](https://linux-hardware.org/?probe=3905de150e) | May 24, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [9f202f07cd](https://linux-hardware.org/?probe=9f202f07cd) | May 24, 2022 |
| Lenovo        | ThinkPad T420 42362L0       | [3aa17b879d](https://linux-hardware.org/?probe=3aa17b879d) | May 22, 2022 |
| Toshiba       | Satellite L10W-C            | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| ASUSTek       | UX31E                       | [12407852be](https://linux-hardware.org/?probe=12407852be) | May 21, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Acer          | Swift SF314-52              | [4c199417ea](https://linux-hardware.org/?probe=4c199417ea) | May 19, 2022 |
| Acer          | Aspire 3100                 | [47e42883f4](https://linux-hardware.org/?probe=47e42883f4) | May 18, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| Acer          | Swift SF314-52              | [a532101bbf](https://linux-hardware.org/?probe=a532101bbf) | May 17, 2022 |
| HP            | ProBook 455 G7              | [95daa19596](https://linux-hardware.org/?probe=95daa19596) | May 17, 2022 |
| HP            | ProBook 455 G7              | [a96c7163a5](https://linux-hardware.org/?probe=a96c7163a5) | May 17, 2022 |
| Dell          | Vostro 5568                 | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| ASUSTek       | X101CH                      | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| ASUSTek       | X555LB                      | [2c2e8fcf67](https://linux-hardware.org/?probe=2c2e8fcf67) | May 15, 2022 |
| ASUSTek       | UX31E                       | [85613b8729](https://linux-hardware.org/?probe=85613b8729) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek       | UX31E                       | [b83f4f894e](https://linux-hardware.org/?probe=b83f4f894e) | May 13, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Chuwi         | MiniBook X                  | [541609a32e](https://linux-hardware.org/?probe=541609a32e) | May 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [52fa4973d5](https://linux-hardware.org/?probe=52fa4973d5) | May 10, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | [a70f694f0b](https://linux-hardware.org/?probe=a70f694f0b) | May 09, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [badd8c8562](https://linux-hardware.org/?probe=badd8c8562) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | [73714bdb43](https://linux-hardware.org/?probe=73714bdb43) | May 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| ASUSTek       | UX31E                       | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Dell          | Latitude 3330               | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| ASUSTek       | UX31E                       | [8f165f54aa](https://linux-hardware.org/?probe=8f165f54aa) | Apr 29, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-45              | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| ASUSTek       | UX31E                       | [ef86b0396a](https://linux-hardware.org/?probe=ef86b0396a) | Apr 27, 2022 |
| Acer          | Aspire 5742G                | [313e7bcf23](https://linux-hardware.org/?probe=313e7bcf23) | Apr 27, 2022 |
| HP            | ZBook 17 G3                 | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Dell          | Latitude 7390 2-in-1        | [8391ca514e](https://linux-hardware.org/?probe=8391ca514e) | Apr 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| Lenovo        | ThinkPad E15 20RD001EMC     | [d98ca42427](https://linux-hardware.org/?probe=d98ca42427) | Apr 20, 2022 |
| Dell          | Latitude 5480               | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| Lenovo        | B50-80 80EW                 | [2d1471986b](https://linux-hardware.org/?probe=2d1471986b) | Apr 19, 2022 |
| Acer          | Aspire V3-112P              | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| ASUSTek       | UX31E                       | [fa535559e0](https://linux-hardware.org/?probe=fa535559e0) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [fccfb454e4](https://linux-hardware.org/?probe=fccfb454e4) | Apr 16, 2022 |
| Lenovo        | ThinkPad T400 6474AH2       | [f5e7108c33](https://linux-hardware.org/?probe=f5e7108c33) | Apr 15, 2022 |
| Lenovo        | E31-80 80MX                 | [ea96e85c49](https://linux-hardware.org/?probe=ea96e85c49) | Apr 14, 2022 |
| Lenovo        | B50-80 80EW                 | [d180d3831a](https://linux-hardware.org/?probe=d180d3831a) | Apr 10, 2022 |
| Acer          | TravelMate 4670             | [f5067e581b](https://linux-hardware.org/?probe=f5067e581b) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7f4e9c9158](https://linux-hardware.org/?probe=7f4e9c9158) | Apr 09, 2022 |
| ASUSTek       | UX31E                       | [7249da837c](https://linux-hardware.org/?probe=7249da837c) | Apr 06, 2022 |
| Acer          | Extensa 5630                | [7ff131392d](https://linux-hardware.org/?probe=7ff131392d) | Apr 05, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [59eedbbc1b](https://linux-hardware.org/?probe=59eedbbc1b) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Dell          | XPS 15 9550                 | [487aa8af18](https://linux-hardware.org/?probe=487aa8af18) | Apr 03, 2022 |
| Acer          | Extensa 5630                | [4c6f7067bc](https://linux-hardware.org/?probe=4c6f7067bc) | Apr 02, 2022 |
| ASUSTek       | UX31E                       | [beb645df2c](https://linux-hardware.org/?probe=beb645df2c) | Apr 02, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [96e4eca691](https://linux-hardware.org/?probe=96e4eca691) | Apr 01, 2022 |
| ASUSTek       | UX31E                       | [54717b42d3](https://linux-hardware.org/?probe=54717b42d3) | Mar 31, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [e69dbda259](https://linux-hardware.org/?probe=e69dbda259) | Mar 31, 2022 |
| Acer          | Aspire E5-573G              | [39d3a3ac9d](https://linux-hardware.org/?probe=39d3a3ac9d) | Mar 30, 2022 |
| Acer          | Aspire P3-171               | [972861cbcc](https://linux-hardware.org/?probe=972861cbcc) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AWA07B0... | [4e67f54e53](https://linux-hardware.org/?probe=4e67f54e53) | Mar 29, 2022 |
| ASUSTek       | UX31E                       | [d83c6588f2](https://linux-hardware.org/?probe=d83c6588f2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [649bc1b13a](https://linux-hardware.org/?probe=649bc1b13a) | Mar 28, 2022 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | [d1638977bc](https://linux-hardware.org/?probe=d1638977bc) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [67c079dd83](https://linux-hardware.org/?probe=67c079dd83) | Mar 28, 2022 |
| HP            | Compaq 615                  | [77439caf8f](https://linux-hardware.org/?probe=77439caf8f) | Mar 28, 2022 |
| ASUSTek       | UX31E                       | [582d76d560](https://linux-hardware.org/?probe=582d76d560) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Acer          | Aspire 3000                 | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | [6df7f8330c](https://linux-hardware.org/?probe=6df7f8330c) | Mar 25, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [c6ed527183](https://linux-hardware.org/?probe=c6ed527183) | Mar 25, 2022 |
| Lenovo        | ThinkPad X61s 7667CB5       | [05a3f6eba9](https://linux-hardware.org/?probe=05a3f6eba9) | Mar 25, 2022 |
| ASUSTek       | UX31E                       | [ad8feeb6a4](https://linux-hardware.org/?probe=ad8feeb6a4) | Mar 24, 2022 |
| HP            | Compaq 615                  | [c61f5e75c7](https://linux-hardware.org/?probe=c61f5e75c7) | Mar 24, 2022 |
| Dell          | Latitude E6430s             | [8ac18b3ae9](https://linux-hardware.org/?probe=8ac18b3ae9) | Mar 24, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [26443633b7](https://linux-hardware.org/?probe=26443633b7) | Mar 23, 2022 |
| ASUSTek       | UX31E                       | [3f268da44f](https://linux-hardware.org/?probe=3f268da44f) | Mar 22, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [9fb46d3913](https://linux-hardware.org/?probe=9fb46d3913) | Mar 22, 2022 |
| HP            | ProBook 450 G6              | [e8072f850f](https://linux-hardware.org/?probe=e8072f850f) | Mar 22, 2022 |
| ASUSTek       | UX31E                       | [86242fab56](https://linux-hardware.org/?probe=86242fab56) | Mar 21, 2022 |
| Acer          | Aspire E5-521               | [ad4ffeb6d5](https://linux-hardware.org/?probe=ad4ffeb6d5) | Mar 20, 2022 |
| Acer          | Aspire E5-521               | [7f37d7148d](https://linux-hardware.org/?probe=7f37d7148d) | Mar 20, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [4824a016cc](https://linux-hardware.org/?probe=4824a016cc) | Mar 18, 2022 |
| HP            | Pavilion Notebook 15-dp0... | [847871aa63](https://linux-hardware.org/?probe=847871aa63) | Mar 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [12249482c6](https://linux-hardware.org/?probe=12249482c6) | Mar 17, 2022 |
| Dell          | Latitude E4200              | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| ASUSTek       | X550VXK                     | [9d51869d37](https://linux-hardware.org/?probe=9d51869d37) | Mar 15, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [d627d6a6a0](https://linux-hardware.org/?probe=d627d6a6a0) | Mar 14, 2022 |
| ASUSTek       | UX31E                       | [620772c443](https://linux-hardware.org/?probe=620772c443) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| Acer          | Aspire 3100                 | [0429db8c01](https://linux-hardware.org/?probe=0429db8c01) | Mar 11, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Toshiba       | Satellite L750D             | [84ccdf8375](https://linux-hardware.org/?probe=84ccdf8375) | Mar 10, 2022 |
| ASUSTek       | UX31E                       | [62f3b41d12](https://linux-hardware.org/?probe=62f3b41d12) | Mar 09, 2022 |
| Acer          | TP-SW5-012-16UW             | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Toshiba       | Satellite L750D             | [71d5919c2d](https://linux-hardware.org/?probe=71d5919c2d) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| Acer          | Aspire 5349                 | [cd3380a8b4](https://linux-hardware.org/?probe=cd3380a8b4) | Mar 07, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [3667f5b9e9](https://linux-hardware.org/?probe=3667f5b9e9) | Mar 07, 2022 |
| Acer          | Extensa 5620                | [3104016080](https://linux-hardware.org/?probe=3104016080) | Mar 06, 2022 |
| ASUSTek       | UX31E                       | [885cc74a20](https://linux-hardware.org/?probe=885cc74a20) | Mar 05, 2022 |
| HP            | ProBook 455 G7              | [311c6da8e0](https://linux-hardware.org/?probe=311c6da8e0) | Mar 05, 2022 |
| Dell          | Latitude E5470              | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [3333e54277](https://linux-hardware.org/?probe=3333e54277) | Mar 04, 2022 |
| Dell          | Latitude 7520               | [023fba74f0](https://linux-hardware.org/?probe=023fba74f0) | Mar 04, 2022 |
| ASUSTek       | UX31E                       | [c4106a59b1](https://linux-hardware.org/?probe=c4106a59b1) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [6d96f7e645](https://linux-hardware.org/?probe=6d96f7e645) | Mar 02, 2022 |
| Lenovo        | ThinkPad X250 20CM001XMC    | [66cdff8786](https://linux-hardware.org/?probe=66cdff8786) | Mar 02, 2022 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [21b4f724b8](https://linux-hardware.org/?probe=21b4f724b8) | Mar 02, 2022 |
| Dell          | Latitude 7520               | [d31adbbcad](https://linux-hardware.org/?probe=d31adbbcad) | Mar 02, 2022 |
| ASUSTek       | UX31E                       | [36ea5044b6](https://linux-hardware.org/?probe=36ea5044b6) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [cab4f22396](https://linux-hardware.org/?probe=cab4f22396) | Feb 28, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [55773feeee](https://linux-hardware.org/?probe=55773feeee) | Feb 27, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [9ffeec636e](https://linux-hardware.org/?probe=9ffeec636e) | Feb 26, 2022 |
| ASUSTek       | UX31E                       | [477b323b68](https://linux-hardware.org/?probe=477b323b68) | Feb 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [4cb3686ee5](https://linux-hardware.org/?probe=4cb3686ee5) | Feb 24, 2022 |
| ASUSTek       | UX31E                       | [a6dae44349](https://linux-hardware.org/?probe=a6dae44349) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [245600d3fd](https://linux-hardware.org/?probe=245600d3fd) | Feb 23, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [bedd29ee73](https://linux-hardware.org/?probe=bedd29ee73) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56496468de](https://linux-hardware.org/?probe=56496468de) | Feb 21, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [6cb1c24dd7](https://linux-hardware.org/?probe=6cb1c24dd7) | Feb 20, 2022 |
| ASUSTek       | X75A1                       | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| ASUSTek       | UX31E                       | [5651fbf2c8](https://linux-hardware.org/?probe=5651fbf2c8) | Feb 18, 2022 |
| Google        | Chell                       | [46b95ce3a4](https://linux-hardware.org/?probe=46b95ce3a4) | Feb 17, 2022 |
| Acer          | Aspire E5-573G              | [e162c17653](https://linux-hardware.org/?probe=e162c17653) | Feb 17, 2022 |
| Lenovo        | IdeaPad Z580                | [26e55e169b](https://linux-hardware.org/?probe=26e55e169b) | Feb 16, 2022 |
| Gigabyte      | GB-BSi7A-6500               | [9cfc09f66c](https://linux-hardware.org/?probe=9cfc09f66c) | Feb 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5JW0... | [df9633e08e](https://linux-hardware.org/?probe=df9633e08e) | Feb 13, 2022 |
| ASUSTek       | UX31E                       | [7b2a1e633f](https://linux-hardware.org/?probe=7b2a1e633f) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | [b78e30f502](https://linux-hardware.org/?probe=b78e30f502) | Feb 11, 2022 |
| Dell          | Latitude 5480               | [eddd68780f](https://linux-hardware.org/?probe=eddd68780f) | Feb 09, 2022 |
| ASUSTek       | UX31E                       | [f70763fe0a](https://linux-hardware.org/?probe=f70763fe0a) | Feb 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [3fa68165ea](https://linux-hardware.org/?probe=3fa68165ea) | Feb 07, 2022 |
| ASUSTek       | UX31E                       | [4346690bc8](https://linux-hardware.org/?probe=4346690bc8) | Feb 06, 2022 |
| Acer          | Aspire SW3-016              | [6375ec93db](https://linux-hardware.org/?probe=6375ec93db) | Feb 05, 2022 |
| ASUSTek       | UX31E                       | [1eceff18e2](https://linux-hardware.org/?probe=1eceff18e2) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| Lenovo        | G710 20252                  | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| ASUSTek       | F5RL                        | [09497d2017](https://linux-hardware.org/?probe=09497d2017) | Feb 02, 2022 |
| ASUSTek       | F5RL                        | [77baf7aac1](https://linux-hardware.org/?probe=77baf7aac1) | Feb 02, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Lenovo        | ThinkPad W530 2441B88       | [9c15c47f51](https://linux-hardware.org/?probe=9c15c47f51) | Feb 01, 2022 |
| Dell          | Latitude 7490               | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cd876e95b9](https://linux-hardware.org/?probe=cd876e95b9) | Jan 29, 2022 |
| ASUSTek       | X556UQ                      | [b9589b97a3](https://linux-hardware.org/?probe=b9589b97a3) | Jan 28, 2022 |
| HP            | ProBook 445 G7              | [a386252eaa](https://linux-hardware.org/?probe=a386252eaa) | Jan 28, 2022 |
| Unknown       | Unknown                     | [a6e928b122](https://linux-hardware.org/?probe=a6e928b122) | Jan 28, 2022 |
| Dell          | XPS 15 9560                 | [ee50dc0bb1](https://linux-hardware.org/?probe=ee50dc0bb1) | Jan 27, 2022 |
| ASUSTek       | K50ID                       | [fed48cd01d](https://linux-hardware.org/?probe=fed48cd01d) | Jan 27, 2022 |
| ASUSTek       | UX31E                       | [d6d51a7ce7](https://linux-hardware.org/?probe=d6d51a7ce7) | Jan 26, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S7D300    | [3fcdce23b5](https://linux-hardware.org/?probe=3fcdce23b5) | Jan 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [ab4eb272cb](https://linux-hardware.org/?probe=ab4eb272cb) | Jan 24, 2022 |
| Acer          | NC-E1-572-54208G            | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| ASUSTek       | UX31E                       | [c64e8bdde9](https://linux-hardware.org/?probe=c64e8bdde9) | Jan 22, 2022 |
| Lenovo        | ThinkPad X395 20NL000HMC    | [6c07e3f92a](https://linux-hardware.org/?probe=6c07e3f92a) | Jan 21, 2022 |
| ASUSTek       | UX31E                       | [08320d55cd](https://linux-hardware.org/?probe=08320d55cd) | Jan 21, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [e5d8911653](https://linux-hardware.org/?probe=e5d8911653) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | [3f0a902b2e](https://linux-hardware.org/?probe=3f0a902b2e) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | [0b31274785](https://linux-hardware.org/?probe=0b31274785) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c76a20872b](https://linux-hardware.org/?probe=c76a20872b) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [11d1f56125](https://linux-hardware.org/?probe=11d1f56125) | Jan 18, 2022 |
| Dell          | Latitude 5420               | [dd45d8465d](https://linux-hardware.org/?probe=dd45d8465d) | Jan 17, 2022 |
| HP            | EliteBook 840 G6            | [c6b20915de](https://linux-hardware.org/?probe=c6b20915de) | Jan 17, 2022 |
| Notebook      | NS50MU                      | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| ASUSTek       | UX31E                       | [77c7eedd86](https://linux-hardware.org/?probe=77c7eedd86) | Jan 15, 2022 |
| Toshiba       | Satellite C55-A-19N         | [b53c0c9b39](https://linux-hardware.org/?probe=b53c0c9b39) | Jan 14, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ba41989095](https://linux-hardware.org/?probe=ba41989095) | Jan 14, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [9111c65725](https://linux-hardware.org/?probe=9111c65725) | Jan 12, 2022 |
| HP            | ZBook 17 G2                 | [232d1f1cb4](https://linux-hardware.org/?probe=232d1f1cb4) | Jan 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | [94d85b9f5b](https://linux-hardware.org/?probe=94d85b9f5b) | Jan 12, 2022 |
| Dell          | Inspiron 13 5310            | [f45f45197a](https://linux-hardware.org/?probe=f45f45197a) | Jan 11, 2022 |
| HP            | ProBook 6450b               | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Lenovo        | ThinkPad E590 20NB001WMC    | [f114fe6200](https://linux-hardware.org/?probe=f114fe6200) | Jan 08, 2022 |
| Toshiba       | Satellite C55-A-1NU         | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| HP            | EliteBook 8540p             | [20b9948e89](https://linux-hardware.org/?probe=20b9948e89) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [13c6bafd04](https://linux-hardware.org/?probe=13c6bafd04) | Jan 08, 2022 |
| ASUSTek       | UX31E                       | [b976b5921e](https://linux-hardware.org/?probe=b976b5921e) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e50bae67a6](https://linux-hardware.org/?probe=e50bae67a6) | Jan 08, 2022 |
| Lenovo        | Yoga 2 13 20344             | [581a4abb8e](https://linux-hardware.org/?probe=581a4abb8e) | Jan 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| HP            | ProBook 4510s               | [50904e6b69](https://linux-hardware.org/?probe=50904e6b69) | Jan 06, 2022 |
| HP            | ProBook 4510s               | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Precision M4500             | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| Dell          | Latitude 3470               | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d774f42123](https://linux-hardware.org/?probe=d774f42123) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| Dell          | Inspiron 5570               | [3e6d1befd6](https://linux-hardware.org/?probe=3e6d1befd6) | Jan 03, 2022 |
| Dell          | Latitude 7480               | [24244e5717](https://linux-hardware.org/?probe=24244e5717) | Jan 02, 2022 |
| Acer          | Swift SF114-34              | [94b665863b](https://linux-hardware.org/?probe=94b665863b) | Jan 02, 2022 |
| ASUSTek       | UX31E                       | [926c4f82d1](https://linux-hardware.org/?probe=926c4f82d1) | Jan 01, 2022 |
| HP            | EliteBook 820 G1            | [90deec9056](https://linux-hardware.org/?probe=90deec9056) | Dec 30, 2021 |
| Dell          | Inspiron 7559               | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [20af449f2a](https://linux-hardware.org/?probe=20af449f2a) | Dec 29, 2021 |
| HP            | ProBook 4540s               | [99fb3303bb](https://linux-hardware.org/?probe=99fb3303bb) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| ASUSTek       | UX31E                       | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| HP            | Laptop 17-cp0xxx            | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| HUAWEI        | HVY-WXX9                    | [2c33c2931e](https://linux-hardware.org/?probe=2c33c2931e) | Dec 26, 2021 |
| Lenovo        | G710 20252                  | [961341534c](https://linux-hardware.org/?probe=961341534c) | Dec 26, 2021 |
| Acer          | Swift SF315-41              | [92f264978e](https://linux-hardware.org/?probe=92f264978e) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | [d94d38f29b](https://linux-hardware.org/?probe=d94d38f29b) | Dec 25, 2021 |
| ASUSTek       | X705NC                      | [c3cdc81bd8](https://linux-hardware.org/?probe=c3cdc81bd8) | Dec 25, 2021 |
| ASUSTek       | UX31E                       | [62488dea12](https://linux-hardware.org/?probe=62488dea12) | Dec 25, 2021 |
| Dell          | Latitude 5400               | [692bc521a6](https://linux-hardware.org/?probe=692bc521a6) | Dec 20, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| HP            | EliteBook 850 G6            | [0f1c42ef5d](https://linux-hardware.org/?probe=0f1c42ef5d) | Dec 18, 2021 |
| ASUSTek       | UX31E                       | [8c6db8aa19](https://linux-hardware.org/?probe=8c6db8aa19) | Dec 17, 2021 |
| Acer          | Aspire A515-56              | [a50b285530](https://linux-hardware.org/?probe=a50b285530) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440 20B7S1MW07    | [21baa9b1cc](https://linux-hardware.org/?probe=21baa9b1cc) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [a0ec890791](https://linux-hardware.org/?probe=a0ec890791) | Dec 15, 2021 |
| ASUSTek       | X751LN                      | [f7489ee0ae](https://linux-hardware.org/?probe=f7489ee0ae) | Dec 15, 2021 |
| ASUSTek       | UX31E                       | [f5d5138937](https://linux-hardware.org/?probe=f5d5138937) | Dec 13, 2021 |
| HP            | EliteBook 840 G6            | [a20ecb525c](https://linux-hardware.org/?probe=a20ecb525c) | Dec 13, 2021 |
| Acer          | Aspire E5-721               | [53ab8f6179](https://linux-hardware.org/?probe=53ab8f6179) | Dec 12, 2021 |
| HP            | Laptop 14-cf0xxx            | [2f4ec869f9](https://linux-hardware.org/?probe=2f4ec869f9) | Dec 12, 2021 |
| ASUSTek       | UX31E                       | [d48bfc96ce](https://linux-hardware.org/?probe=d48bfc96ce) | Dec 12, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Dell          | Latitude E4300              | [3dd32ae25d](https://linux-hardware.org/?probe=3dd32ae25d) | Dec 10, 2021 |
| Acer          | Extensa 5220                | [2572d3336d](https://linux-hardware.org/?probe=2572d3336d) | Dec 09, 2021 |
| Acer          | Extensa 5220                | [524256971b](https://linux-hardware.org/?probe=524256971b) | Dec 09, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [2694c27280](https://linux-hardware.org/?probe=2694c27280) | Dec 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| ASUSTek       | UX31E                       | [04c3a4b6c7](https://linux-hardware.org/?probe=04c3a4b6c7) | Dec 03, 2021 |
| Lenovo        | G770 20089                  | [6a4de555a2](https://linux-hardware.org/?probe=6a4de555a2) | Dec 03, 2021 |
| UMAX          | VisionBook N15G Plus        | [4b16e8ea9d](https://linux-hardware.org/?probe=4b16e8ea9d) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| Google        | Akemi                       | [0867d0658c](https://linux-hardware.org/?probe=0867d0658c) | Dec 01, 2021 |
| Google        | Akemi                       | [2344df2c6b](https://linux-hardware.org/?probe=2344df2c6b) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ae6614d6fb](https://linux-hardware.org/?probe=ae6614d6fb) | Nov 29, 2021 |
| ASUSTek       | UX31E                       | [0af8133ca3](https://linux-hardware.org/?probe=0af8133ca3) | Nov 29, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [9dd7b3ad9b](https://linux-hardware.org/?probe=9dd7b3ad9b) | Nov 29, 2021 |
| Acer          | P4LJ0                       | [0f57f6b606](https://linux-hardware.org/?probe=0f57f6b606) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [f047b9db0a](https://linux-hardware.org/?probe=f047b9db0a) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [d8d17c1820](https://linux-hardware.org/?probe=d8d17c1820) | Nov 27, 2021 |
| Lenovo        | G780                        | [ffeaa607f9](https://linux-hardware.org/?probe=ffeaa607f9) | Nov 27, 2021 |
| Lenovo        | G780                        | [26ea5410e6](https://linux-hardware.org/?probe=26ea5410e6) | Nov 27, 2021 |
| Fujitsu       | LIFEBOOK T901               | [d9b8b1c304](https://linux-hardware.org/?probe=d9b8b1c304) | Nov 27, 2021 |
| ASUSTek       | X751LN                      | [2c8e1bfecd](https://linux-hardware.org/?probe=2c8e1bfecd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| ASUSTek       | X751LN                      | [50d304e970](https://linux-hardware.org/?probe=50d304e970) | Nov 22, 2021 |
| Unknown       | Unknown                     | [81e2289408](https://linux-hardware.org/?probe=81e2289408) | Nov 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6b2b37cfc2](https://linux-hardware.org/?probe=6b2b37cfc2) | Nov 20, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [c174aa242d](https://linux-hardware.org/?probe=c174aa242d) | Nov 20, 2021 |
| HP            | OMEN by Laptop              | [0b8f3a5da9](https://linux-hardware.org/?probe=0b8f3a5da9) | Nov 19, 2021 |
| ASUSTek       | UX31E                       | [27fde62ce2](https://linux-hardware.org/?probe=27fde62ce2) | Nov 18, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [f3bf7b971f](https://linux-hardware.org/?probe=f3bf7b971f) | Nov 18, 2021 |
| HP            | ProBook 4510s               | [46c61312c4](https://linux-hardware.org/?probe=46c61312c4) | Nov 18, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [66fd774069](https://linux-hardware.org/?probe=66fd774069) | Nov 17, 2021 |
| HP            | ProBook 4510s               | [cf53b2e2db](https://linux-hardware.org/?probe=cf53b2e2db) | Nov 17, 2021 |
| Fujitsu       | LIFEBOOK E754               | [9569f15e49](https://linux-hardware.org/?probe=9569f15e49) | Nov 16, 2021 |
| Dell          | Latitude E6420              | [71905152a8](https://linux-hardware.org/?probe=71905152a8) | Nov 14, 2021 |
| HP            | ProBook 455 G6              | [2a37f0ed64](https://linux-hardware.org/?probe=2a37f0ed64) | Nov 14, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [bf655cd438](https://linux-hardware.org/?probe=bf655cd438) | Nov 13, 2021 |
| HUAWEI        | HN-WX9X                     | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [1fe63ecbee](https://linux-hardware.org/?probe=1fe63ecbee) | Nov 13, 2021 |
| HP            | ProBook 640 G1              | [72d5b9727b](https://linux-hardware.org/?probe=72d5b9727b) | Nov 12, 2021 |
| HP            | OMEN by Laptop              | [207d9a7985](https://linux-hardware.org/?probe=207d9a7985) | Nov 12, 2021 |
| HP            | Pavilion g6                 | [0332d112e9](https://linux-hardware.org/?probe=0332d112e9) | Nov 12, 2021 |
| HP            | ProBook 455 G6              | [6045aa2b3a](https://linux-hardware.org/?probe=6045aa2b3a) | Nov 12, 2021 |
| Dell          | Latitude E5440              | [310f365903](https://linux-hardware.org/?probe=310f365903) | Nov 10, 2021 |
| Timi          | A35                         | [f8818e4273](https://linux-hardware.org/?probe=f8818e4273) | Nov 10, 2021 |
| Lenovo        | ThinkPad Edge E431 62774... | [2af76d7459](https://linux-hardware.org/?probe=2af76d7459) | Nov 09, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [a67ec35b48](https://linux-hardware.org/?probe=a67ec35b48) | Nov 08, 2021 |
| HP            | Pavilion dv6                | [12800ce664](https://linux-hardware.org/?probe=12800ce664) | Nov 06, 2021 |
| HP            | Pavilion dv6                | [9b00744856](https://linux-hardware.org/?probe=9b00744856) | Nov 06, 2021 |
| Dell          | XPS 15 9550                 | [1ae65e25ca](https://linux-hardware.org/?probe=1ae65e25ca) | Nov 06, 2021 |
| HP            | Compaq nc6320 (RH374EA#A... | [91c9beef79](https://linux-hardware.org/?probe=91c9beef79) | Nov 05, 2021 |
| Dell          | XPS 15 9550                 | [3cea241e9d](https://linux-hardware.org/?probe=3cea241e9d) | Nov 04, 2021 |
| ASUSTek       | X555BA                      | [99ef7179aa](https://linux-hardware.org/?probe=99ef7179aa) | Nov 04, 2021 |
| HP            | ProBook 650 G2              | [510bf1ba13](https://linux-hardware.org/?probe=510bf1ba13) | Nov 03, 2021 |
| HP            | OMEN by Laptop              | [d5eda0a4df](https://linux-hardware.org/?probe=d5eda0a4df) | Nov 01, 2021 |
| MSI           | GE76 Raider 11UG            | [cbbe604f22](https://linux-hardware.org/?probe=cbbe604f22) | Nov 01, 2021 |
| ASUSTek       | UX31E                       | [b089d44dc0](https://linux-hardware.org/?probe=b089d44dc0) | Nov 01, 2021 |
| Purism        | librem_15v4                 | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [d55ac505b9](https://linux-hardware.org/?probe=d55ac505b9) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [65a70acf15](https://linux-hardware.org/?probe=65a70acf15) | Oct 31, 2021 |
| ASUSTek       | F5RL                        | [7a2e7c66e9](https://linux-hardware.org/?probe=7a2e7c66e9) | Oct 31, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [3802a77d98](https://linux-hardware.org/?probe=3802a77d98) | Oct 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [eadbbabab0](https://linux-hardware.org/?probe=eadbbabab0) | Oct 29, 2021 |
| Dell          | Latitude E7240              | [18213a2e29](https://linux-hardware.org/?probe=18213a2e29) | Oct 28, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | [3678e02e46](https://linux-hardware.org/?probe=3678e02e46) | Oct 27, 2021 |
| Lenovo        | ThinkPad E590 20NB0018MC    | [5a44640ff8](https://linux-hardware.org/?probe=5a44640ff8) | Oct 27, 2021 |
| Lenovo        | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Sony          | VPCZ13M9E                   | [2d1739dc58](https://linux-hardware.org/?probe=2d1739dc58) | Oct 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| ASUSTek       | UX31E                       | [62ce68edef](https://linux-hardware.org/?probe=62ce68edef) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Alienware     | 15                          | [5a84b0e8e8](https://linux-hardware.org/?probe=5a84b0e8e8) | Oct 25, 2021 |
| ASUSTek       | UX31E                       | [3783b25b2a](https://linux-hardware.org/?probe=3783b25b2a) | Oct 24, 2021 |
| Acer          | Aspire E5-721               | [0b2ec748f2](https://linux-hardware.org/?probe=0b2ec748f2) | Oct 23, 2021 |
| Acer          | Aspire E5-721               | [46ae1c3c30](https://linux-hardware.org/?probe=46ae1c3c30) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | [d727cf6e00](https://linux-hardware.org/?probe=d727cf6e00) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Sony          | VPCZ13M9E                   | [6ccc652e28](https://linux-hardware.org/?probe=6ccc652e28) | Oct 22, 2021 |
| Alienware     | 15                          | [8c4eaaa333](https://linux-hardware.org/?probe=8c4eaaa333) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Dell          | Latitude 5400               | [8a880e6565](https://linux-hardware.org/?probe=8a880e6565) | Oct 19, 2021 |
| Dell          | Latitude 5400               | [0a94130eb2](https://linux-hardware.org/?probe=0a94130eb2) | Oct 19, 2021 |
| HP            | Laptop 15-bw0xx             | [f60949a3cc](https://linux-hardware.org/?probe=f60949a3cc) | Oct 18, 2021 |
| Sony          | VPCEB1E1E                   | [1473b3d2ca](https://linux-hardware.org/?probe=1473b3d2ca) | Oct 18, 2021 |
| Acer          | Aspire A515-51G             | [43bfef3bcd](https://linux-hardware.org/?probe=43bfef3bcd) | Oct 17, 2021 |
| Dell          | Latitude E5420              | [a1027f938f](https://linux-hardware.org/?probe=a1027f938f) | Oct 16, 2021 |
| Medion        | E7218                       | [cca261a107](https://linux-hardware.org/?probe=cca261a107) | Oct 16, 2021 |
| Dell          | XPS 13 9310                 | [f04cc5e7a8](https://linux-hardware.org/?probe=f04cc5e7a8) | Oct 15, 2021 |
| Dell          | XPS 13 9300                 | [22029905ac](https://linux-hardware.org/?probe=22029905ac) | Oct 15, 2021 |
| ASUSTek       | UX31E                       | [a20549b1ee](https://linux-hardware.org/?probe=a20549b1ee) | Oct 14, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fb676e6e3f](https://linux-hardware.org/?probe=fb676e6e3f) | Oct 14, 2021 |
| Dell          | XPS 15 9550                 | [2269836aab](https://linux-hardware.org/?probe=2269836aab) | Oct 13, 2021 |
| HP            | EliteBook 8570w             | [b703149715](https://linux-hardware.org/?probe=b703149715) | Oct 13, 2021 |
| ASUSTek       | UX31E                       | [33cb7873b3](https://linux-hardware.org/?probe=33cb7873b3) | Oct 11, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| Lenovo        | ThinkPad T570 20H90000MC    | [51c709d90c](https://linux-hardware.org/?probe=51c709d90c) | Oct 09, 2021 |
| HP            | Compaq 6530b (GW688AV)      | [13444fc399](https://linux-hardware.org/?probe=13444fc399) | Oct 08, 2021 |
| ASUSTek       | E502SA                      | [7034e6708d](https://linux-hardware.org/?probe=7034e6708d) | Oct 07, 2021 |
| MSI           | GL63 8RD                    | [9f55f25caf](https://linux-hardware.org/?probe=9f55f25caf) | Oct 07, 2021 |
| ASUSTek       | UX31E                       | [3d656a59f6](https://linux-hardware.org/?probe=3d656a59f6) | Oct 06, 2021 |
| ASUSTek       | UX31E                       | [b24ee374eb](https://linux-hardware.org/?probe=b24ee374eb) | Oct 04, 2021 |
| HP            | ProBook 455 G1              | [43115b1585](https://linux-hardware.org/?probe=43115b1585) | Oct 04, 2021 |
| Acer          | Aspire A114-32              | [153c60004b](https://linux-hardware.org/?probe=153c60004b) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | [0c7f8d9bc1](https://linux-hardware.org/?probe=0c7f8d9bc1) | Oct 03, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [c3f376b088](https://linux-hardware.org/?probe=c3f376b088) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | [634508203a](https://linux-hardware.org/?probe=634508203a) | Oct 01, 2021 |
| ASUSTek       | UX31E                       | [ae53a22db8](https://linux-hardware.org/?probe=ae53a22db8) | Sep 30, 2021 |
| ASUSTek       | E502SA                      | [7f17ddd3af](https://linux-hardware.org/?probe=7f17ddd3af) | Sep 30, 2021 |
| Acer          | Extensa 5235                | [aadc334520](https://linux-hardware.org/?probe=aadc334520) | Sep 29, 2021 |
| MSI           | GL72 6QD                    | [4a25280ba6](https://linux-hardware.org/?probe=4a25280ba6) | Sep 28, 2021 |
| ASUSTek       | UX31E                       | [1ce98669cc](https://linux-hardware.org/?probe=1ce98669cc) | Sep 27, 2021 |
| ASUSTek       | UX31E                       | [65594b31db](https://linux-hardware.org/?probe=65594b31db) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| ASUSTek       | UX31E                       | [61a05f66ef](https://linux-hardware.org/?probe=61a05f66ef) | Sep 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [534a4c683f](https://linux-hardware.org/?probe=534a4c683f) | Sep 24, 2021 |
| ASUSTek       | 1015BXO                     | [0f2bd07e92](https://linux-hardware.org/?probe=0f2bd07e92) | Sep 23, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [28cec81520](https://linux-hardware.org/?probe=28cec81520) | Sep 22, 2021 |
| Dell          | XPS 15 7590                 | [7e0c5640af](https://linux-hardware.org/?probe=7e0c5640af) | Sep 21, 2021 |
| HP            | 255 G4                      | [3385bd5e87](https://linux-hardware.org/?probe=3385bd5e87) | Sep 20, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [3c54753690](https://linux-hardware.org/?probe=3c54753690) | Sep 20, 2021 |
| ASUSTek       | UX31E                       | [02b242903b](https://linux-hardware.org/?probe=02b242903b) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| Toshiba       | Satellite C850-19P          | [be0e0fc39c](https://linux-hardware.org/?probe=be0e0fc39c) | Sep 19, 2021 |
| ASUSTek       | N73SV                       | [4dae78bc6e](https://linux-hardware.org/?probe=4dae78bc6e) | Sep 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [caa2e90160](https://linux-hardware.org/?probe=caa2e90160) | Sep 18, 2021 |
| Lenovo        | B50-80 80EW                 | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | [6d3c0cb595](https://linux-hardware.org/?probe=6d3c0cb595) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | [4771fb2aab](https://linux-hardware.org/?probe=4771fb2aab) | Sep 17, 2021 |
| Lenovo        | B51-80 80LM                 | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| ASUSTek       | UX31E                       | [6c54ed5e3e](https://linux-hardware.org/?probe=6c54ed5e3e) | Sep 16, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [10c9991f0b](https://linux-hardware.org/?probe=10c9991f0b) | Sep 16, 2021 |
| ASUSTek       | UX31E                       | [aa60d02a7b](https://linux-hardware.org/?probe=aa60d02a7b) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | [8bd0f5b675](https://linux-hardware.org/?probe=8bd0f5b675) | Sep 15, 2021 |
| Dell          | Vostro 14 5410              | [e044b5770b](https://linux-hardware.org/?probe=e044b5770b) | Sep 15, 2021 |
| HP            | ProBook 455 G6              | [8c5aa4304c](https://linux-hardware.org/?probe=8c5aa4304c) | Sep 14, 2021 |
| HP            | ProBook 455 G6              | [49a26a21af](https://linux-hardware.org/?probe=49a26a21af) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |
| ASUSTek       | UX31E                       | [e1b27b035e](https://linux-hardware.org/?probe=e1b27b035e) | Sep 13, 2021 |
| Dell          | Latitude 5400               | [1fed0bdd29](https://linux-hardware.org/?probe=1fed0bdd29) | Sep 13, 2021 |
| ASUSTek       | UX303LA                     | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| Dell          | XPS 15 9550                 | [5ef10e99fc](https://linux-hardware.org/?probe=5ef10e99fc) | Sep 11, 2021 |
| Unknown       | Unknown                     | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | [d137a3a584](https://linux-hardware.org/?probe=d137a3a584) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | [4b97784aeb](https://linux-hardware.org/?probe=4b97784aeb) | Sep 08, 2021 |
| Dell          | Latitude 5511               | [75e4394ca1](https://linux-hardware.org/?probe=75e4394ca1) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [7d28c4a737](https://linux-hardware.org/?probe=7d28c4a737) | Sep 07, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [c33f77f320](https://linux-hardware.org/?probe=c33f77f320) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| ASUSTek       | UX31E                       | [e0160c202c](https://linux-hardware.org/?probe=e0160c202c) | Sep 06, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [96642dc49d](https://linux-hardware.org/?probe=96642dc49d) | Sep 02, 2021 |
| HP            | Pavilion g6                 | [7f23204904](https://linux-hardware.org/?probe=7f23204904) | Sep 02, 2021 |
| ASUSTek       | UX31E                       | [36e2960d9e](https://linux-hardware.org/?probe=36e2960d9e) | Sep 01, 2021 |
| MSI           | GP72MVR 7RFX                | [8bf96cd534](https://linux-hardware.org/?probe=8bf96cd534) | Sep 01, 2021 |
| ASUSTek       | UX31E                       | [f8455be078](https://linux-hardware.org/?probe=f8455be078) | Aug 31, 2021 |
| ASUSTek       | UX31E                       | [715882de9a](https://linux-hardware.org/?probe=715882de9a) | Aug 30, 2021 |
| Dell          | Inspiron 14 5410            | [9ac57ec075](https://linux-hardware.org/?probe=9ac57ec075) | Aug 29, 2021 |
| Dell          | Inspiron 5570               | [47c81ea7a3](https://linux-hardware.org/?probe=47c81ea7a3) | Aug 28, 2021 |
| HP            | ProBook 450 G2              | [8228226f9b](https://linux-hardware.org/?probe=8228226f9b) | Aug 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| ASUSTek       | UX31E                       | [a626915a9b](https://linux-hardware.org/?probe=a626915a9b) | Aug 27, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [b3185cd80d](https://linux-hardware.org/?probe=b3185cd80d) | Aug 26, 2021 |
| ASUSTek       | UX31E                       | [48a1496d43](https://linux-hardware.org/?probe=48a1496d43) | Aug 26, 2021 |
| HP            | Pavilion dv7                | [89e7202467](https://linux-hardware.org/?probe=89e7202467) | Aug 25, 2021 |
| HP            | ProBook 455 G7              | [56da4a55e4](https://linux-hardware.org/?probe=56da4a55e4) | Aug 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [42c87d7154](https://linux-hardware.org/?probe=42c87d7154) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b773fc8716](https://linux-hardware.org/?probe=b773fc8716) | Aug 23, 2021 |
| HP            | 250 G6 Notebook PC          | [d0d5aa4d58](https://linux-hardware.org/?probe=d0d5aa4d58) | Aug 23, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7e6371d41f](https://linux-hardware.org/?probe=7e6371d41f) | Aug 22, 2021 |
| ASUSTek       | UX31E                       | [f11d89cc89](https://linux-hardware.org/?probe=f11d89cc89) | Aug 21, 2021 |
| ASUSTek       | UX31E                       | [36beb5b173](https://linux-hardware.org/?probe=36beb5b173) | Aug 19, 2021 |
| Dell          | Latitude 7320               | [33536a85d3](https://linux-hardware.org/?probe=33536a85d3) | Aug 19, 2021 |
| ASUSTek       | X556UQK                     | [7306b98101](https://linux-hardware.org/?probe=7306b98101) | Aug 18, 2021 |
| ASUSTek       | UX31E                       | [0816a877bd](https://linux-hardware.org/?probe=0816a877bd) | Aug 18, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [4f0fc1bae7](https://linux-hardware.org/?probe=4f0fc1bae7) | Aug 18, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 159       | 11.51%  |
| Ubuntu 18.04                 | 83        | 6.01%   |
| OpenMandriva 4.2             | 75        | 5.43%   |
| Ubuntu 22.04                 | 64        | 4.63%   |
| OpenMandriva 4.50            | 58        | 4.2%    |
| OpenMandriva 4.3             | 39        | 2.82%   |
| Ubuntu 21.10                 | 28        | 2.03%   |
| Ubuntu 19.10                 | 22        | 1.59%   |
| Fedora 38                    | 22        | 1.59%   |
| Fedora 34                    | 22        | 1.59%   |
| Ubuntu 20.10                 | 21        | 1.52%   |
| OpenMandriva 23.01           | 21        | 1.52%   |
| Zorin 16                     | 20        | 1.45%   |
| Zorin 15                     | 20        | 1.45%   |
| Pop!_OS 22.04                | 19        | 1.37%   |
| Debian 11                    | 19        | 1.37%   |
| Ubuntu 21.04                 | 18        | 1.3%    |
| Linux Mint 21.1              | 18        | 1.3%    |
| Linux Mint 20                | 17        | 1.23%   |
| Arch                         | 17        | 1.23%   |
| openSUSE Tumbleweed-XXXXXXXX | 16        | 1.16%   |
| Linux Mint 20.2              | 16        | 1.16%   |
| Linux Mint 19.3              | 16        | 1.16%   |
| Arch Rolling                 | 16        | 1.16%   |
| Linux Mint 20.3              | 15        | 1.09%   |
| OpenMandriva 23.03           | 14        | 1.01%   |
| Fedora 35                    | 14        | 1.01%   |
| Fedora 33                    | 14        | 1.01%   |
| Manjaro                      | 13        | 0.94%   |
| Linux Mint 21                | 13        | 0.94%   |
| Linux Mint 20.1              | 13        | 0.94%   |
| Fedora 32                    | 13        | 0.94%   |
| Fedora 31                    | 13        | 0.94%   |
| Xubuntu 20.04                | 12        | 0.87%   |
| Ubuntu 19.04                 | 12        | 0.87%   |
| Fedora 37                    | 12        | 0.87%   |
| Fedora 36                    | 12        | 0.87%   |
| Kubuntu 22.04                | 11        | 0.8%    |
| Kubuntu 20.04                | 11        | 0.8%    |
| Xubuntu 18.04                | 10        | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 400       | 30.79%  |
| OpenMandriva  | 210       | 16.17%  |
| Fedora        | 124       | 9.55%   |
| Linux Mint    | 119       | 9.16%   |
| Zorin         | 41        | 3.16%   |
| Debian        | 41        | 3.16%   |
| Xubuntu       | 36        | 2.77%   |
| Manjaro       | 35        | 2.69%   |
| Pop!_OS       | 34        | 2.62%   |
| Arch          | 33        | 2.54%   |
| Kubuntu       | 30        | 2.31%   |
| openSUSE      | 22        | 1.69%   |
| Gentoo        | 22        | 1.69%   |
| ROSA          | 19        | 1.46%   |
| Lubuntu       | 13        | 1%      |
| KDE neon      | 13        | 1%      |
| Kali          | 12        | 0.92%   |
| ArcoLinux     | 10        | 0.77%   |
| Endless       | 8         | 0.62%   |
| Elementary    | 8         | 0.62%   |
| Ubuntu MATE   | 7         | 0.54%   |
| SteamOS       | 6         | 0.46%   |
| RHEL          | 6         | 0.46%   |
| Ubuntu Unity  | 5         | 0.38%   |
| Parrot        | 4         | 0.31%   |
| MX            | 4         | 0.31%   |
| EndeavourOS   | 3         | 0.23%   |
| BlackPanther  | 3         | 0.23%   |
| Ubuntu Budgie | 2         | 0.15%   |
| Rocky Linux   | 2         | 0.15%   |
| NixOS         | 2         | 0.15%   |
| LMDE          | 2         | 0.15%   |
| LinuxFX       | 2         | 0.15%   |
| Artix         | 2         | 0.15%   |
| Void Linux    | 1         | 0.08%   |
| TUXEDO OS     | 1         | 0.08%   |
| SystemRescue  | 1         | 0.08%   |
| Solus         | 1         | 0.08%   |
| Sabayon       | 1         | 0.08%   |
| Reborn OS     | 1         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 74        | 4.95%   |
| 5.14.7-desktop-1omv4050  | 55        | 3.68%   |
| 5.16.7-desktop-1omv4003  | 38        | 2.54%   |
| 5.4.0-42-generic         | 23        | 1.54%   |
| 6.1.1-desktop-1omv2290   | 20        | 1.34%   |
| 5.4.0-52-generic         | 15        | 1%      |
| 5.15.0-46-generic        | 15        | 1%      |
| 6.2.6-desktop-1omv2390   | 13        | 0.87%   |
| 5.4.0-26-generic         | 13        | 0.87%   |
| 5.15.0-56-generic        | 13        | 0.87%   |
| 5.4.0-58-generic         | 12        | 0.8%    |
| 5.3.0-40-generic         | 11        | 0.74%   |
| 5.15.0-58-generic        | 10        | 0.67%   |
| 5.4.0-65-generic         | 9         | 0.6%    |
| 5.15.0-48-generic        | 9         | 0.6%    |
| 5.0.0-37-generic         | 9         | 0.6%    |
| 6.2.0-26-generic         | 8         | 0.54%   |
| 5.8.0-59-generic         | 8         | 0.54%   |
| 5.4.0-48-generic         | 8         | 0.54%   |
| 5.4.0-40-generic         | 8         | 0.54%   |
| 5.15.0-78-generic        | 8         | 0.54%   |
| 5.15.0-52-generic        | 8         | 0.54%   |
| 5.13.0-21-generic        | 8         | 0.54%   |
| 6.2.6-76060206-generic   | 7         | 0.47%   |
| 5.4.0-91-generic         | 7         | 0.47%   |
| 5.19.0-32-generic        | 7         | 0.47%   |
| 5.11.0-27-generic        | 7         | 0.47%   |
| 5.8.0-53-generic         | 6         | 0.4%    |
| 5.4.0-70-generic         | 6         | 0.4%    |
| 5.4.0-56-generic         | 6         | 0.4%    |
| 5.4.0-37-generic         | 6         | 0.4%    |
| 5.4.0-29-generic         | 6         | 0.4%    |
| 5.3.0-46-generic         | 6         | 0.4%    |
| 5.3.0-42-generic         | 6         | 0.4%    |
| 5.3.0-28-generic         | 6         | 0.4%    |
| 5.13.0-30-generic        | 6         | 0.4%    |
| 5.13.0-22-generic        | 6         | 0.4%    |
| 5.11.0-34-generic        | 6         | 0.4%    |
| 5.11.0-25-generic        | 6         | 0.4%    |
| 5.11.0-22-generic        | 6         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 195       | 13.83%  |
| 5.15.0  | 111       | 7.87%   |
| 5.10.14 | 74        | 5.25%   |
| 5.3.0   | 68        | 4.82%   |
| 5.13.0  | 66        | 4.68%   |
| 5.11.0  | 63        | 4.47%   |
| 5.8.0   | 58        | 4.11%   |
| 4.15.0  | 58        | 4.11%   |
| 5.14.7  | 56        | 3.97%   |
| 5.0.0   | 44        | 3.12%   |
| 5.16.7  | 39        | 2.77%   |
| 5.19.0  | 38        | 2.7%    |
| 5.10.0  | 28        | 1.99%   |
| 4.18.0  | 26        | 1.84%   |
| 6.1.1   | 23        | 1.63%   |
| 6.2.6   | 20        | 1.42%   |
| 6.2.0   | 20        | 1.42%   |
| 6.1.0   | 14        | 0.99%   |
| 4.19.0  | 8         | 0.57%   |
| 6.2.9   | 6         | 0.43%   |
| 6.0.0   | 6         | 0.43%   |
| 6.2.15  | 5         | 0.35%   |
| 5.15.12 | 5         | 0.35%   |
| 5.14.0  | 5         | 0.35%   |
| 4.13.0  | 5         | 0.35%   |
| 6.4.6   | 4         | 0.28%   |
| 6.3.8   | 4         | 0.28%   |
| 5.9.0   | 4         | 0.28%   |
| 5.6.16  | 4         | 0.28%   |
| 5.3.18  | 4         | 0.28%   |
| 5.17.0  | 4         | 0.28%   |
| 5.16.11 | 4         | 0.28%   |
| 5.11.12 | 4         | 0.28%   |
| 5.10.74 | 4         | 0.28%   |
| 4.4.0   | 4         | 0.28%   |
| 6.4.7   | 3         | 0.21%   |
| 6.2.11  | 3         | 0.21%   |
| 6.2.10  | 3         | 0.21%   |
| 6.1.7   | 3         | 0.21%   |
| 6.0.2   | 3         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 211       | 15.07%  |
| 5.15    | 141       | 10.07%  |
| 5.10    | 129       | 9.21%   |
| 5.11    | 84        | 6%      |
| 5.13    | 79        | 5.64%   |
| 5.3     | 76        | 5.43%   |
| 5.8     | 74        | 5.29%   |
| 5.14    | 74        | 5.29%   |
| 6.2     | 62        | 4.43%   |
| 4.15    | 60        | 4.29%   |
| 6.1     | 56        | 4%      |
| 5.16    | 56        | 4%      |
| 5.19    | 53        | 3.79%   |
| 5.0     | 46        | 3.29%   |
| 4.18    | 28        | 2%      |
| 6.0     | 23        | 1.64%   |
| 5.17    | 20        | 1.43%   |
| 6.4     | 18        | 1.29%   |
| 5.9     | 15        | 1.07%   |
| 5.6     | 15        | 1.07%   |
| 5.18    | 15        | 1.07%   |
| 4.19    | 12        | 0.86%   |
| 6.3     | 7         | 0.5%    |
| 5.12    | 7         | 0.5%    |
| 4.9     | 7         | 0.5%    |
| 5.7     | 6         | 0.43%   |
| 5.5     | 6         | 0.43%   |
| 6.5     | 5         | 0.36%   |
| 4.13    | 5         | 0.36%   |
| 4.4     | 4         | 0.29%   |
| 5.1     | 2         | 0.14%   |
| 4.8     | 1         | 0.07%   |
| 4.17    | 1         | 0.07%   |
| 4.14    | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1235      | 96.79%  |
| i686   | 41        | 3.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 528       | 40.06%  |
| KDE5            | 327       | 24.81%  |
| Unknown         | 139       | 10.55%  |
| XFCE            | 109       | 8.27%   |
| X-Cinnamon      | 68        | 5.16%   |
| MATE            | 35        | 2.66%   |
| KDE             | 23        | 1.75%   |
| Cinnamon        | 18        | 1.37%   |
| LXQt            | 15        | 1.14%   |
| Pantheon        | 8         | 0.61%   |
| Unity           | 6         | 0.46%   |
| LXDE            | 6         | 0.46%   |
| KDE4            | 6         | 0.46%   |
| GNOME Flashback | 6         | 0.46%   |
| awesome         | 4         | 0.3%    |
| i3              | 3         | 0.23%   |
| Budgie          | 3         | 0.23%   |
| sway            | 2         | 0.15%   |
| qtile           | 2         | 0.15%   |
| openbox         | 2         | 0.15%   |
| XSession        | 1         | 0.08%   |
| xinitrc         | 1         | 0.08%   |
| xinit-compat    | 1         | 0.08%   |
| Hyprland        | 1         | 0.08%   |
| GNUstep         | 1         | 0.08%   |
| Enlightenment   | 1         | 0.08%   |
| DWM             | 1         | 0.08%   |
| custom          | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 987       | 75.34%  |
| Wayland | 228       | 17.4%   |
| Unknown | 82        | 6.26%   |
| Tty     | 13        | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 554       | 42.03%  |
| SDDM    | 317       | 24.05%  |
| GDM     | 139       | 10.55%  |
| GDM3    | 129       | 9.79%   |
| LightDM | 122       | 9.26%   |
| TDM     | 39        | 2.96%   |
| KDM     | 5         | 0.38%   |
| XDM     | 4         | 0.3%    |
| SLiM    | 4         | 0.3%    |
| LXDM    | 3         | 0.23%   |
| Ly      | 1         | 0.08%   |
| GREETD  | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| cs_CZ   | 692       | 53.31%  |
| en_US   | 390       | 30.05%  |
| Unknown | 123       | 9.48%   |
| en_GB   | 27        | 2.08%   |
| C       | 22        | 1.69%   |
| ru_RU   | 17        | 1.31%   |
| sk_SK   | 4         | 0.31%   |
| pl_PL   | 4         | 0.31%   |
| POSIX   | 3         | 0.23%   |
| de_DE   | 3         | 0.23%   |
| uk_UA   | 2         | 0.15%   |
| it_IT   | 2         | 0.15%   |
| fr_FR   | 2         | 0.15%   |
| ro_RO   | 1         | 0.08%   |
| es_ES   | 1         | 0.08%   |
| en_NG   | 1         | 0.08%   |
| en_CA   | 1         | 0.08%   |
| en_150  | 1         | 0.08%   |
| el_GR   | 1         | 0.08%   |
| bg_BG   | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 657       | 50.23%  |
| EFI  | 651       | 49.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 863       | 66.38%  |
| Overlay  | 221       | 17%     |
| Btrfs    | 123       | 9.46%   |
| Unknown  | 33        | 2.54%   |
| Xfs      | 27        | 2.08%   |
| Tmpfs    | 17        | 1.31%   |
| Zfs      | 7         | 0.54%   |
| Ext3     | 3         | 0.23%   |
| Ext2     | 2         | 0.15%   |
| Aufs     | 2         | 0.15%   |
| Reiserfs | 1         | 0.08%   |
| F2fs     | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 586       | 45.22%  |
| GPT     | 478       | 36.88%  |
| MBR     | 232       | 17.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1167      | 90.82%  |
| Yes       | 118       | 9.18%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 840       | 64.57%  |
| Yes       | 461       | 35.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 330       | 25.86%  |
| ASUSTek Computer               | 259       | 20.3%   |
| Hewlett-Packard                | 233       | 18.26%  |
| Dell                           | 176       | 13.79%  |
| Acer                           | 123       | 9.64%   |
| UMAX                           | 19        | 1.49%   |
| MSI                            | 18        | 1.41%   |
| Toshiba                        | 17        | 1.33%   |
| Sony                           | 15        | 1.18%   |
| Fujitsu                        | 10        | 0.78%   |
| HUAWEI                         | 7         | 0.55%   |
| Apple                          | 7         | 0.55%   |
| Valve                          | 6         | 0.47%   |
| Unknown                        | 6         | 0.47%   |
| Google                         | 5         | 0.39%   |
| TUXEDO                         | 4         | 0.31%   |
| Timi                           | 4         | 0.31%   |
| Fujitsu Siemens                | 4         | 0.31%   |
| Packard Bell                   | 3         | 0.24%   |
| Notebook                       | 3         | 0.24%   |
| Insyde                         | 2         | 0.16%   |
| Chuwi                          | 2         | 0.16%   |
| Alienware                      | 2         | 0.16%   |
| Standard                       | 1         | 0.08%   |
| SmbiosType1_SystemManufacturer | 1         | 0.08%   |
| SLIMBOOK                       | 1         | 0.08%   |
| Samsung Electronics            | 1         | 0.08%   |
| Purism                         | 1         | 0.08%   |
| Prestigio                      | 1         | 0.08%   |
| Panasonic                      | 1         | 0.08%   |
| Medion                         | 1         | 0.08%   |
| Jumper                         | 1         | 0.08%   |
| Intel                          | 1         | 0.08%   |
| INET                           | 1         | 0.08%   |
| In-Sing                        | 1         | 0.08%   |
| IBM                            | 1         | 0.08%   |
| Gigabyte Technology            | 1         | 0.08%   |
| EUROCOM                        | 1         | 0.08%   |
| eMachines                      | 1         | 0.08%   |
| Dynabook                       | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ASUS UX31E                            | 127       | 9.95%   |
| Unknown                               | 9         | 0.71%   |
| HP ProBook 455 G7                     | 7         | 0.55%   |
| Valve Jupiter                         | 6         | 0.47%   |
| Dell Latitude E6420                   | 6         | 0.47%   |
| Lenovo ThinkPad E14 20RA001LMC        | 5         | 0.39%   |
| HP ProBook 4540s                      | 5         | 0.39%   |
| HP ProBook 4530s                      | 5         | 0.39%   |
| HP ProBook 450 G5                     | 5         | 0.39%   |
| HP EliteBook 845 G8 Notebook PC       | 5         | 0.39%   |
| HP EliteBook 840 G3                   | 5         | 0.39%   |
| Dell Latitude E6400                   | 5         | 0.39%   |
| Dell Latitude 5401                    | 5         | 0.39%   |
| Lenovo IdeaPad S145-15AST 81N3        | 4         | 0.31%   |
| HP Pavilion dv7                       | 4         | 0.31%   |
| HP Notebook                           | 4         | 0.31%   |
| HP EliteBook 840 G6                   | 4         | 0.31%   |
| HP 250 G6 Notebook PC                 | 4         | 0.31%   |
| Dell XPS 15 9560                      | 4         | 0.31%   |
| Dell XPS 15 7590                      | 4         | 0.31%   |
| Dell Precision M6500                  | 4         | 0.31%   |
| Acer Extensa 5620                     | 4         | 0.31%   |
| UMAX VisionBook 15Wg Plus             | 3         | 0.24%   |
| Lenovo Z50-75 80EC                    | 3         | 0.24%   |
| Lenovo ThinkPad T14 Gen 1 20UES2WA00  | 3         | 0.24%   |
| Lenovo IdeaPad Z580                   | 3         | 0.24%   |
| Lenovo IdeaPad S130-11IGM 81J1        | 3         | 0.24%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL | 3         | 0.24%   |
| Lenovo IdeaPad 5 14ARE05 81YM         | 3         | 0.24%   |
| Lenovo IdeaPad 5 14ALC05 82LM         | 3         | 0.24%   |
| Lenovo IdeaPad 3 15ARE05 81W4         | 3         | 0.24%   |
| HP ProBook 4510s                      | 3         | 0.24%   |
| HP Pavilion dv6                       | 3         | 0.24%   |
| HP Laptop 15-bw0xx                    | 3         | 0.24%   |
| HP EliteBook 855 G7 Notebook PC       | 3         | 0.24%   |
| HP EliteBook 850 G6                   | 3         | 0.24%   |
| HP EliteBook 8470p                    | 3         | 0.24%   |
| Dell XPS 13 9360                      | 3         | 0.24%   |
| Dell Precision 5510                   | 3         | 0.24%   |
| Dell Latitude E7440                   | 3         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 177       | 13.87%  |
| ASUS UX31E            | 127       | 9.95%   |
| Dell Latitude         | 91        | 7.13%   |
| Acer Aspire           | 73        | 5.72%   |
| Lenovo IdeaPad        | 72        | 5.64%   |
| HP ProBook            | 63        | 4.94%   |
| HP EliteBook          | 62        | 4.86%   |
| HP Pavilion           | 25        | 1.96%   |
| Dell XPS              | 25        | 1.96%   |
| Dell Inspiron         | 21        | 1.65%   |
| Dell Precision        | 19        | 1.49%   |
| Toshiba Satellite     | 16        | 1.25%   |
| ASUS VivoBook         | 16        | 1.25%   |
| HP Laptop             | 15        | 1.18%   |
| ASUS ZenBook          | 15        | 1.18%   |
| UMAX VisionBook       | 14        | 1.1%    |
| Lenovo Yoga           | 14        | 1.1%    |
| HP ZBook              | 14        | 1.1%    |
| HP Compaq             | 14        | 1.1%    |
| Acer Extensa          | 14        | 1.1%    |
| Lenovo Legion         | 13        | 1.02%   |
| Acer TravelMate       | 12        | 0.94%   |
| Acer Swift            | 12        | 0.94%   |
| Lenovo ThinkBook      | 10        | 0.78%   |
| HP 250                | 10        | 0.78%   |
| Fujitsu LIFEBOOK      | 10        | 0.78%   |
| Unknown               | 9         | 0.71%   |
| Dell Vostro           | 8         | 0.63%   |
| ASUS ROG              | 7         | 0.55%   |
| Valve Jupiter         | 6         | 0.47%   |
| ASUS ASUS             | 6         | 0.47%   |
| Acer Nitro            | 5         | 0.39%   |
| HP Notebook           | 4         | 0.31%   |
| Dell G5               | 4         | 0.31%   |
| Packard Bell EasyNote | 3         | 0.24%   |
| Lenovo Z50-75         | 3         | 0.24%   |
| Lenovo G780           | 3         | 0.24%   |
| HP Victus             | 3         | 0.24%   |
| HP OMEN               | 3         | 0.24%   |
| Fujitsu Siemens AMILO | 3         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 204       | 15.99%  |
| 2020    | 122       | 9.56%   |
| 2021    | 112       | 8.78%   |
| 2019    | 111       | 8.7%    |
| 2018    | 90        | 7.05%   |
| 2012    | 78        | 6.11%   |
| 2015    | 69        | 5.41%   |
| 2014    | 69        | 5.41%   |
| 2017    | 66        | 5.17%   |
| 2013    | 65        | 5.09%   |
| 2008    | 59        | 4.62%   |
| 2016    | 58        | 4.55%   |
| 2010    | 47        | 3.68%   |
| 2022    | 41        | 3.21%   |
| 2007    | 31        | 2.43%   |
| 2009    | 27        | 2.12%   |
| 2006    | 13        | 1.02%   |
| 2023    | 7         | 0.55%   |
| 2005    | 3         | 0.24%   |
| 2004    | 2         | 0.16%   |
| Unknown | 2         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1276      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1124      | 86.93%  |
| Enabled  | 169       | 13.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1270      | 99.53%  |
| Yes  | 6         | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 366       | 28.31%  |
| 4.01-8.0    | 278       | 21.5%   |
| 8.01-16.0   | 219       | 16.94%  |
| 16.01-24.0  | 183       | 14.15%  |
| 32.01-64.0  | 107       | 8.28%   |
| 1.01-2.0    | 67        | 5.18%   |
| 2.01-3.0    | 25        | 1.93%   |
| 24.01-32.0  | 21        | 1.62%   |
| 0.51-1.0    | 14        | 1.08%   |
| 64.01-256.0 | 12        | 0.93%   |
| 0.01-0.5    | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 519       | 36.99%  |
| 2.01-3.0   | 304       | 21.67%  |
| 4.01-8.0   | 211       | 15.04%  |
| 3.01-4.0   | 174       | 12.4%   |
| 0.51-1.0   | 80        | 5.7%    |
| 8.01-16.0  | 78        | 5.56%   |
| 0.01-0.5   | 18        | 1.28%   |
| 16.01-24.0 | 15        | 1.07%   |
| 32.01-64.0 | 2         | 0.14%   |
| 24.01-32.0 | 2         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1029      | 78.91%  |
| 2      | 228       | 17.48%  |
| 3      | 31        | 2.38%   |
| 0      | 13        | 1%      |
| 4      | 2         | 0.15%   |
| 7      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 901       | 70.28%  |
| Yes       | 381       | 29.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1066      | 82.96%  |
| No        | 219       | 17.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1253      | 98.12%  |
| No        | 24        | 1.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 936       | 72.45%  |
| No        | 356       | 27.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Czechia | 1276      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Prague               | 544       | 40.9%   |
| Brno                 | 112       | 8.42%   |
| Ostrava              | 39        | 2.93%   |
| Pilsen               | 26        | 1.95%   |
| Olomouc              | 21        | 1.58%   |
| Pardubice            | 18        | 1.35%   |
| Liberec              | 16        | 1.2%    |
| Hradec Králové     | 13        | 0.98%   |
| České Budějovice  | 13        | 0.98%   |
| Most                 | 10        | 0.75%   |
| Havířov            | 10        | 0.75%   |
| Chomutov             | 10        | 0.75%   |
| Jihlava              | 8         | 0.6%    |
| Brdo                 | 8         | 0.6%    |
| Znojmo               | 7         | 0.53%   |
| Zlín                | 7         | 0.53%   |
| Karlovy Vary         | 7         | 0.53%   |
| Ústí nad Labem     | 6         | 0.45%   |
| Tábor               | 6         | 0.45%   |
| Kladno               | 6         | 0.45%   |
| Roznov pod Radhostem | 5         | 0.38%   |
| Příbram            | 5         | 0.38%   |
| Přerov              | 5         | 0.38%   |
| Opava                | 5         | 0.38%   |
| Mariánské Lázně  | 5         | 0.38%   |
| Ceska Kamenice       | 5         | 0.38%   |
| Třebíč            | 4         | 0.3%    |
| Teplice              | 4         | 0.3%    |
| Slavkov u Brna       | 4         | 0.3%    |
| Prelouc              | 4         | 0.3%    |
| Mladá Boleslav      | 4         | 0.3%    |
| Milovice             | 4         | 0.3%    |
| Jedovnice            | 4         | 0.3%    |
| Frýdek-Místek      | 4         | 0.3%    |
| Česká Lípa        | 4         | 0.3%    |
| Vitkov               | 3         | 0.23%   |
| Uvaly                | 3         | 0.23%   |
| Uhlirske Janovice    | 3         | 0.23%   |
| Šlapanice           | 3         | 0.23%   |
| Semily               | 3         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 260       | 338    | 17.08%  |
| SanDisk                        | 201       | 214    | 13.21%  |
| WDC                            | 151       | 180    | 9.92%   |
| Seagate                        | 145       | 197    | 9.53%   |
| Toshiba                        | 114       | 137    | 7.49%   |
| Kingston                       | 82        | 89     | 5.39%   |
| Unknown                        | 73        | 102    | 4.8%    |
| SK hynix                       | 71        | 86     | 4.66%   |
| Hitachi                        | 51        | 59     | 3.35%   |
| Micron Technology              | 47        | 59     | 3.09%   |
| Intel                          | 47        | 55     | 3.09%   |
| HGST                           | 41        | 51     | 2.69%   |
| A-DATA Technology              | 27        | 30     | 1.77%   |
| Crucial                        | 23        | 33     | 1.51%   |
| Patriot                        | 22        | 27     | 1.45%   |
| KIOXIA                         | 19        | 32     | 1.25%   |
| Unknown                        | 12        | 13     | 0.79%   |
| Apacer                         | 10        | 15     | 0.66%   |
| Transcend                      | 9         | 10     | 0.59%   |
| LITEONIT                       | 8         | 10     | 0.53%   |
| Fujitsu                        | 7         | 7      | 0.46%   |
| China                          | 7         | 8      | 0.46%   |
| Phison                         | 6         | 13     | 0.39%   |
| LITEON                         | 6         | 6      | 0.39%   |
| Apple                          | 6         | 6      | 0.39%   |
| Verbatim                       | 5         | 5      | 0.33%   |
| Silicon Motion                 | 5         | 5      | 0.33%   |
| UMAX                           | 4         | 4      | 0.26%   |
| Phison Electronics             | 4         | 4      | 0.26%   |
| JMicron Technology             | 4         | 4      | 0.26%   |
| Gigabyte Technology            | 4         | 9      | 0.26%   |
| ASMedia                        | 4         | 6      | 0.26%   |
| Team                           | 3         | 3      | 0.2%    |
| Solid State Storage Technology | 3         | 3      | 0.2%    |
| Lenovo                         | 3         | 4      | 0.2%    |
| GOODRAM                        | 3         | 4      | 0.2%    |
| UMIS                           | 2         | 2      | 0.13%   |
| Realtek Semiconductor          | 2         | 3      | 0.13%   |
| Micron/Crucial Technology      | 2         | 2      | 0.13%   |
| Lite-On                        | 2         | 4      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB                              | 126       | 7.94%   |
| Samsung NVMe SSD Drive 512GB                        | 17        | 1.07%   |
| HGST HTS721010A9E630 1TB                            | 16        | 1.01%   |
| Seagate ST1000LM035-1RK172 1TB                      | 15        | 0.95%   |
| Unknown MMC Card  32GB                              | 14        | 0.88%   |
| Samsung SSD 860 EVO 500GB                           | 13        | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 13        | 0.82%   |
| Kingston SA400S37480G 480GB SSD                     | 12        | 0.76%   |
| Unknown                                             | 12        | 0.76%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                      | 11        | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 10        | 0.63%   |
| SanDisk NVMe SSD Drive 512GB                        | 10        | 0.63%   |
| Toshiba MQ01ABD100 1TB                              | 9         | 0.57%   |
| Kingston SA400S37240G 240GB SSD                     | 9         | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 8         | 0.5%    |
| Unknown MMC Card  64GB                              | 8         | 0.5%    |
| Unknown MMC Card  16GB                              | 8         | 0.5%    |
| Toshiba MQ01ABF050 500GB                            | 8         | 0.5%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD                 | 8         | 0.5%    |
| SK hynix NVMe SSD Drive 512GB                       | 8         | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                     | 8         | 0.5%    |
| Samsung SSD 850 EVO 250GB                           | 8         | 0.5%    |
| HGST HTS725050A7E630 500GB                          | 8         | 0.5%    |
| Toshiba MQ04ABF100 1TB                              | 7         | 0.44%   |
| Seagate ST9500420AS 500GB                           | 7         | 0.44%   |
| SanDisk NVMe SSD Drive 1024GB                       | 7         | 0.44%   |
| Patriot Burst 480GB SSD                             | 7         | 0.44%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 7         | 0.44%   |
| Kingston SA400S37120G 120GB SSD                     | 7         | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 6         | 0.38%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 6         | 0.38%   |
| Unknown MMC Card  128GB                             | 6         | 0.38%   |
| Toshiba NVMe SSD Drive 512GB                        | 6         | 0.38%   |
| Seagate ST500LM000-1EJ162 500GB                     | 6         | 0.38%   |
| Seagate ST2000LM007-1R8174 2TB                      | 6         | 0.38%   |
| SanDisk DF4032  32GB                                | 6         | 0.38%   |
| Samsung SSD 970 EVO 1TB                             | 6         | 0.38%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 6         | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 6         | 0.38%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 6         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 143       | 195    | 35.57%  |
| WDC                 | 88        | 104    | 21.89%  |
| Toshiba             | 66        | 74     | 16.42%  |
| Hitachi             | 51        | 59     | 12.69%  |
| HGST                | 41        | 51     | 10.2%   |
| Fujitsu             | 7         | 7      | 1.74%   |
| Samsung Electronics | 2         | 2      | 0.5%    |
| USB3.0              | 1         | 1      | 0.25%   |
| Unknown             | 1         | 1      | 0.25%   |
| SABRENT             | 1         | 1      | 0.25%   |
| IBM/Hitachi         | 1         | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 158       | 162    | 28.42%  |
| Samsung Electronics | 110       | 135    | 19.78%  |
| Kingston            | 61        | 67     | 10.97%  |
| WDC                 | 27        | 38     | 4.86%   |
| A-DATA Technology   | 25        | 28     | 4.5%    |
| Patriot             | 22        | 27     | 3.96%   |
| Crucial             | 21        | 31     | 3.78%   |
| Intel               | 17        | 19     | 3.06%   |
| Micron Technology   | 15        | 20     | 2.7%    |
| SK hynix            | 13        | 14     | 2.34%   |
| Toshiba             | 10        | 12     | 1.8%    |
| Apacer              | 10        | 15     | 1.8%    |
| Transcend           | 9         | 10     | 1.62%   |
| LITEONIT            | 8         | 10     | 1.44%   |
| China               | 7         | 8      | 1.26%   |
| Verbatim            | 5         | 5      | 0.9%    |
| Apple               | 5         | 5      | 0.9%    |
| UMAX                | 4         | 4      | 0.72%   |
| LITEON              | 4         | 4      | 0.72%   |
| Gigabyte Technology | 3         | 7      | 0.54%   |
| ASMedia             | 3         | 4      | 0.54%   |
| Team                | 2         | 2      | 0.36%   |
| JMicron Technology  | 2         | 2      | 0.36%   |
| GOODRAM             | 2         | 3      | 0.36%   |
| ASMT                | 2         | 2      | 0.36%   |
| UMIS                | 1         | 1      | 0.18%   |
| TO Exter            | 1         | 2      | 0.18%   |
| ShanDianZhe         | 1         | 1      | 0.18%   |
| Seagate             | 1         | 1      | 0.18%   |
| OCZ                 | 1         | 4      | 0.18%   |
| Netac               | 1         | 1      | 0.18%   |
| Mushkin             | 1         | 1      | 0.18%   |
| HPE                 | 1         | 1      | 0.18%   |
| Hewlett-Packard     | 1         | 1      | 0.18%   |
| CT500MX5            | 1         | 1      | 0.18%   |
| ADATA SU            | 1         | 1      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 534       | 649    | 36.38%  |
| NVMe    | 444       | 594    | 30.25%  |
| HDD     | 390       | 496    | 26.57%  |
| MMC     | 90        | 120    | 6.13%   |
| Unknown | 10        | 13     | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 840       | 1106   | 59.41%  |
| NVMe | 443       | 593    | 31.33%  |
| MMC  | 90        | 120    | 6.36%   |
| SAS  | 41        | 53     | 2.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 677       | 835    | 74.64%  |
| 0.51-1.0   | 211       | 281    | 23.26%  |
| 1.01-2.0   | 17        | 26     | 1.87%   |
| 3.01-4.0   | 1         | 2      | 0.11%   |
| 10.01-20.0 | 1         | 1      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 320       | 24.06%  |
| 251-500        | 313       | 23.53%  |
| 1-20           | 230       | 17.29%  |
| 501-1000       | 182       | 13.68%  |
| 51-100         | 90        | 6.77%   |
| 1001-2000      | 66        | 4.96%   |
| 21-50          | 52        | 3.91%   |
| Unknown        | 47        | 3.53%   |
| More than 3000 | 21        | 1.58%   |
| 2001-3000      | 9         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 629       | 45.58%  |
| 21-50          | 186       | 13.48%  |
| 101-250        | 172       | 12.46%  |
| 51-100         | 150       | 10.87%  |
| 251-500        | 114       | 8.26%   |
| 501-1000       | 50        | 3.62%   |
| Unknown        | 47        | 3.41%   |
| 1001-2000      | 21        | 1.52%   |
| More than 3000 | 6         | 0.43%   |
| 2001-3000      | 5         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                     | 126       | 127    | 62.38%  |
| HGST HTS725050A7E630 500GB                 | 4         | 4      | 1.98%   |
| SK hynix BC711 HFM512GD3JX013N 512GB       | 3         | 4      | 1.49%   |
| Toshiba MQ01ABD075 752GB                   | 2         | 2      | 0.99%   |
| Toshiba MK1234GSX 120GB                    | 2         | 2      | 0.99%   |
| Seagate ST9500420AS 500GB                  | 2         | 3      | 0.99%   |
| Seagate ST1000LX015-1U7172 1TB             | 2         | 2      | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB         | 2         | 2      | 0.99%   |
| Hitachi HTS541610J9SA00 100GB              | 2         | 2      | 0.99%   |
| HGST HTS721010A9E630 1TB                   | 2         | 2      | 0.99%   |
| WDC WDS240G2G0A-00JH30 240GB SSD           | 1         | 1      | 0.5%    |
| WDC WD7500BPVT-22HXZT3 752GB               | 1         | 1      | 0.5%    |
| WDC WD6400BPVT-60HXZT1 640GB               | 1         | 1      | 0.5%    |
| WDC WD3200BEVT-60ZCT1 320GB                | 1         | 1      | 0.5%    |
| Toshiba MQ01ABD100 1TB                     | 1         | 1      | 0.5%    |
| Toshiba MK8037GSX 80GB                     | 1         | 1      | 0.5%    |
| Toshiba MK7559GSXP 752GB                   | 1         | 1      | 0.5%    |
| Toshiba MK6465GSXN 640GB                   | 1         | 1      | 0.5%    |
| Toshiba MK5056GSY 500GB                    | 1         | 1      | 0.5%    |
| Toshiba MK2552GSX 250GB                    | 1         | 1      | 0.5%    |
| SK hynix PC711 HFS512GDE9X073N 512GB       | 1         | 1      | 0.5%    |
| SK hynix HFS256G3BTND-N210A 256GB SSD      | 1         | 1      | 0.5%    |
| SK hynix HFS128G39TND-N210A 128GB SSD      | 1         | 1      | 0.5%    |
| Seagate ST980811AS 80GB                    | 1         | 1      | 0.5%    |
| Seagate ST9750420AS 752GB                  | 1         | 1      | 0.5%    |
| Seagate ST9500420ASG 500GB                 | 1         | 1      | 0.5%    |
| Seagate ST9320423AS 320GB                  | 1         | 1      | 0.5%    |
| Seagate ST9250827AS 250GB                  | 1         | 1      | 0.5%    |
| Seagate ST9250410ASG 250GB                 | 1         | 1      | 0.5%    |
| Seagate ST9250315AS 250GB                  | 1         | 1      | 0.5%    |
| Seagate ST9200420ASG 200GB                 | 1         | 1      | 0.5%    |
| Seagate ST500LM000-SSHD-8GB                | 1         | 1      | 0.5%    |
| Seagate ST320LT007-9ZV142 320GB            | 1         | 1      | 0.5%    |
| Seagate ST2000LM007-1R8174 2TB             | 1         | 1      | 0.5%    |
| SanDisk SD8SBAT-032G-1006 32GB SSD         | 1         | 1      | 0.5%    |
| SanDisk SD7SB3Q256G1002 256GB SSD          | 1         | 1      | 0.5%    |
| Samsung Electronics SSD 870 EVO 500GB      | 1         | 1      | 0.5%    |
| Samsung Electronics SSD 870 EVO 1TB        | 1         | 1      | 0.5%    |
| Samsung Electronics SSD 850 EVO 1TB        | 1         | 1      | 0.5%    |
| Samsung Electronics MZVLB1T0HALR-000L2 1TB | 1         | 1      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 128       | 129    | 63.37%  |
| Seagate             | 17        | 18     | 8.42%   |
| Hitachi             | 13        | 13     | 6.44%   |
| Toshiba             | 10        | 10     | 4.95%   |
| HGST                | 8         | 8      | 3.96%   |
| SK hynix            | 6         | 7      | 2.97%   |
| Samsung Electronics | 6         | 6      | 2.97%   |
| WDC                 | 4         | 4      | 1.98%   |
| Intel               | 2         | 2      | 0.99%   |
| A-DATA Technology   | 2         | 3      | 0.99%   |
| Micron Technology   | 1         | 1      | 0.5%    |
| LITEONIT            | 1         | 1      | 0.5%    |
| Kingston            | 1         | 1      | 0.5%    |
| IBM/Hitachi         | 1         | 1      | 0.5%    |
| Fujitsu             | 1         | 1      | 0.5%    |
| Crucial             | 1         | 1      | 0.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 17        | 18     | 32.08%  |
| Hitachi     | 13        | 13     | 24.53%  |
| Toshiba     | 10        | 10     | 18.87%  |
| HGST        | 8         | 8      | 15.09%  |
| WDC         | 3         | 3      | 5.66%   |
| IBM/Hitachi | 1         | 1      | 1.89%   |
| Fujitsu     | 1         | 1      | 1.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 143       | 145    | 71.14%  |
| HDD  | 52        | 54     | 25.87%  |
| NVMe | 6         | 7      | 2.99%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 679       | 1082   | 50.79%  |
| Works    | 458       | 584    | 34.26%  |
| Malfunc  | 200       | 206    | 14.96%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 884       | 59.53%  |
| Samsung Electronics              | 156       | 10.51%  |
| AMD                              | 145       | 9.76%   |
| SanDisk                          | 70        | 4.71%   |
| SK hynix                         | 55        | 3.7%    |
| Toshiba America Info Systems     | 37        | 2.49%   |
| Micron Technology                | 32        | 2.15%   |
| KIOXIA                           | 22        | 1.48%   |
| Kingston Technology Company      | 22        | 1.48%   |
| Phison Electronics               | 14        | 0.94%   |
| Silicon Motion                   | 7         | 0.47%   |
| Union Memory (Shenzhen)          | 5         | 0.34%   |
| Micron/Crucial Technology        | 4         | 0.27%   |
| Lite-On Technology               | 4         | 0.27%   |
| ADATA Technology                 | 4         | 0.27%   |
| Solid State Storage Technology   | 3         | 0.2%    |
| Silicon Integrated Systems [SiS] | 3         | 0.2%    |
| Nvidia                           | 3         | 0.2%    |
| Lenovo                           | 3         | 0.2%    |
| Realtek Semiconductor            | 2         | 0.13%   |
| JMicron Technology               | 2         | 0.13%   |
| ASMedia Technology               | 2         | 0.13%   |
| VIA Technologies                 | 1         | 0.07%   |
| O2 Micro                         | 1         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.07%   |
| Marvell Technology Group         | 1         | 0.07%   |
| Biwin Storage Technology         | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 190       | 11.9%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 120       | 7.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 80        | 5.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 71        | 4.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 67        | 4.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 58        | 3.63%   |
| Samsung NVMe SSD Controller 980                                                  | 49        | 3.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 47        | 2.94%   |
| Intel Volume Management Device NVMe RAID Controller                              | 40        | 2.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 37        | 2.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 36        | 2.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 32        | 2.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 31        | 1.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 28        | 1.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 26        | 1.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 24        | 1.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 22        | 1.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 22        | 1.38%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 21        | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 21        | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 19        | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 19        | 1.19%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 18        | 1.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 16        | 1%      |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 15        | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 15        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                            | 15        | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 15        | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 13        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 12        | 0.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 0.75%   |
| Intel Tiger Lake-LP SATA Controller                                              | 11        | 0.69%   |
| Intel SSD 660P Series                                                            | 11        | 0.69%   |
| SK hynix BC511 NVMe SSD                                                          | 10        | 0.63%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 10        | 0.63%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 10        | 0.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 10        | 0.63%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 9         | 0.56%   |
| Phison PS5013 E13 NVMe Controller                                                | 9         | 0.56%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 9         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 897       | 58.47%  |
| NVMe | 446       | 29.07%  |
| RAID | 104       | 6.78%   |
| IDE  | 87        | 5.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1041      | 81.58%  |
| AMD    | 235       | 18.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 127       | 9.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 20        | 1.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 19        | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 15        | 1.17%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 15        | 1.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 1.02%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.94%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 12        | 0.94%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 12        | 0.94%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 11        | 0.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 11        | 0.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 0.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 0.78%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 0.78%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 10        | 0.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 0.78%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 9         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.63%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 8         | 0.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 8         | 0.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 0.63%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 0.63%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 8         | 0.63%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 7         | 0.55%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 7         | 0.55%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 0.55%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 6         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 388       | 30.38%  |
| Intel Core i5           | 245       | 19.19%  |
| Other                   | 95        | 7.44%   |
| Intel Celeron           | 78        | 6.11%   |
| Intel Core 2 Duo        | 75        | 5.87%   |
| Intel Core i3           | 68        | 5.32%   |
| AMD Ryzen 5             | 61        | 4.78%   |
| AMD Ryzen 7             | 49        | 3.84%   |
| Intel Pentium           | 32        | 2.51%   |
| Intel Atom              | 24        | 1.88%   |
| AMD Ryzen 7 PRO         | 23        | 1.8%    |
| AMD A6                  | 13        | 1.02%   |
| AMD A4                  | 11        | 0.86%   |
| AMD Ryzen 5 PRO         | 9         | 0.7%    |
| AMD A8                  | 8         | 0.63%   |
| Intel Celeron M         | 7         | 0.55%   |
| Intel Pentium Dual-Core | 6         | 0.47%   |
| Intel Core 2            | 6         | 0.47%   |
| AMD Ryzen 3             | 6         | 0.47%   |
| Intel Pentium Silver    | 5         | 0.39%   |
| Intel Celeron Dual-Core | 5         | 0.39%   |
| AMD E1                  | 5         | 0.39%   |
| Intel Pentium M         | 4         | 0.31%   |
| Intel Pentium Dual      | 4         | 0.31%   |
| Intel Genuine           | 4         | 0.31%   |
| AMD Turion II           | 4         | 0.31%   |
| AMD Ryzen 9             | 4         | 0.31%   |
| AMD E                   | 4         | 0.31%   |
| Intel Xeon              | 3         | 0.23%   |
| Intel Core i9           | 3         | 0.23%   |
| AMD Turion 64 X2 Mobile | 3         | 0.23%   |
| AMD Mobile Sempron      | 3         | 0.23%   |
| AMD FX                  | 3         | 0.23%   |
| AMD E2                  | 3         | 0.23%   |
| AMD A10                 | 3         | 0.23%   |
| AMD Athlon X2           | 2         | 0.16%   |
| AMD Athlon II Dual-Core | 2         | 0.16%   |
| AMD A12                 | 2         | 0.16%   |
| Intel Core m5           | 1         | 0.08%   |
| Intel Core Duo          | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 662       | 51.84%  |
| 4       | 367       | 28.74%  |
| 6       | 110       | 8.61%   |
| 8       | 80        | 6.26%   |
| 1       | 32        | 2.51%   |
| 14      | 9         | 0.7%    |
| 12      | 7         | 0.55%   |
| 10      | 7         | 0.55%   |
| 24      | 1         | 0.08%   |
| 16      | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1276      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 937       | 73.38%  |
| 1       | 339       | 26.55%  |
| Unknown | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1242      | 97.03%  |
| 32-bit         | 20        | 1.56%   |
| Unknown        | 17        | 1.33%   |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 288       | 21.8%   |
| 0x206a7    | 183       | 13.85%  |
| 0x306a9    | 49        | 3.71%   |
| 0x806ec    | 42        | 3.18%   |
| 0x806ea    | 41        | 3.1%    |
| 0x406e3    | 37        | 2.8%    |
| 0x1067a    | 37        | 2.8%    |
| 0x806c1    | 32        | 2.42%   |
| 0x40651    | 31        | 2.35%   |
| 0x906ea    | 30        | 2.27%   |
| 0x08600106 | 29        | 2.2%    |
| 0x306c3    | 28        | 2.12%   |
| 0x806e9    | 26        | 1.97%   |
| 0x0a50000c | 26        | 1.97%   |
| 0x306d4    | 25        | 1.89%   |
| 0x6fd      | 21        | 1.59%   |
| 0x30678    | 19        | 1.44%   |
| 0xa0652    | 16        | 1.21%   |
| 0x506e3    | 15        | 1.14%   |
| 0x20655    | 15        | 1.14%   |
| 0x706a1    | 14        | 1.06%   |
| 0x08608103 | 14        | 1.06%   |
| 0x906e9    | 13        | 0.98%   |
| 0x10676    | 13        | 0.98%   |
| 0x706e5    | 12        | 0.91%   |
| 0x406c3    | 12        | 0.91%   |
| 0x08108102 | 12        | 0.91%   |
| 0x406c4    | 11        | 0.83%   |
| 0x06006705 | 11        | 0.83%   |
| 0x906ed    | 10        | 0.76%   |
| 0x08600104 | 10        | 0.76%   |
| 0x906a3    | 9         | 0.68%   |
| 0x506c9    | 8         | 0.61%   |
| 0x08600103 | 8         | 0.61%   |
| 0x07030105 | 8         | 0.61%   |
| 0x806eb    | 7         | 0.53%   |
| 0x6e8      | 7         | 0.53%   |
| 0x20652    | 7         | 0.53%   |
| 0x106e5    | 7         | 0.53%   |
| 0x10661    | 7         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 212       | 16.61%  |
| SandyBridge      | 208       | 16.3%   |
| Haswell          | 81        | 6.35%   |
| IvyBridge        | 66        | 5.17%   |
| Skylake          | 63        | 4.94%   |
| Penryn           | 62        | 4.86%   |
| Zen 2            | 60        | 4.7%    |
| Silvermont       | 52        | 4.08%   |
| Zen 3            | 45        | 3.53%   |
| TigerLake        | 45        | 3.53%   |
| Core             | 43        | 3.37%   |
| Unknown          | 38        | 2.98%   |
| Broadwell        | 33        | 2.59%   |
| Westmere         | 31        | 2.43%   |
| Goldmont plus    | 25        | 1.96%   |
| Alderlake Hybrid | 23        | 1.8%    |
| CometLake        | 22        | 1.72%   |
| Icelake          | 20        | 1.57%   |
| Excavator        | 20        | 1.57%   |
| Zen+             | 19        | 1.49%   |
| P6               | 12        | 0.94%   |
| Puma             | 11        | 0.86%   |
| Goldmont         | 11        | 0.86%   |
| Bonnell          | 11        | 0.86%   |
| Nehalem          | 9         | 0.71%   |
| Piledriver       | 8         | 0.63%   |
| Bobcat           | 8         | 0.63%   |
| K8 Hammer        | 7         | 0.55%   |
| K10              | 7         | 0.55%   |
| Steamroller      | 6         | 0.47%   |
| Zen              | 5         | 0.39%   |
| Jaguar           | 5         | 0.39%   |
| Tremont          | 4         | 0.31%   |
| K8 & K10 hybrid  | 3         | 0.24%   |
| K10 Llano        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 945       | 59.66%  |
| Nvidia                           | 318       | 20.08%  |
| AMD                              | 317       | 20.01%  |
| Silicon Integrated Systems [SiS] | 2         | 0.13%   |
| VIA Technologies                 | 1         | 0.06%   |
| ATI Technologies                 | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 199       | 12.08%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 61        | 3.7%    |
| AMD Renoir                                                                               | 59        | 3.58%   |
| Intel UHD Graphics 620                                                                   | 52        | 3.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 44        | 2.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 2.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 2.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 37        | 2.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 37        | 2.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 36        | 2.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 33        | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 32        | 1.94%   |
| Intel HD Graphics 620                                                                    | 29        | 1.76%   |
| Intel HD Graphics 5500                                                                   | 29        | 1.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 27        | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 21        | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 21        | 1.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 21        | 1.27%   |
| AMD Lucienne                                                                             | 20        | 1.21%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 1.15%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 19        | 1.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 1.15%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 18        | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 1.03%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 17        | 1.03%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 15        | 0.91%   |
| Intel HD Graphics 630                                                                    | 15        | 0.91%   |
| Intel HD Graphics 530                                                                    | 15        | 0.91%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 14        | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 13        | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 13        | 0.79%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 12        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.67%   |
| Intel HD Graphics 500                                                                    | 11        | 0.67%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 10        | 0.61%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.55%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 9         | 0.55%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 659       | 51.65%  |
| Intel + Nvidia | 229       | 17.95%  |
| 1 x AMD        | 214       | 16.77%  |
| 1 x Nvidia     | 63        | 4.94%   |
| Intel + AMD    | 53        | 4.15%   |
| AMD + Nvidia   | 26        | 2.04%   |
| 2 x AMD        | 25        | 1.96%   |
| 2 x Intel      | 3         | 0.24%   |
| 1 x SiS        | 2         | 0.16%   |
| Other          | 1         | 0.08%   |
| 1 x VIA        | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1108      | 86.29%  |
| Proprietary | 144       | 11.21%  |
| Unknown     | 32        | 2.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 866       | 66.21%  |
| 0.01-0.5   | 161       | 12.31%  |
| 1.01-2.0   | 144       | 11.01%  |
| 0.51-1.0   | 62        | 4.74%   |
| 3.01-4.0   | 49        | 3.75%   |
| 5.01-6.0   | 16        | 1.22%   |
| 7.01-8.0   | 5         | 0.38%   |
| 2.01-3.0   | 4         | 0.31%   |
| 8.01-16.0  | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 276       | 17.92%  |
| LG Display              | 194       | 12.6%   |
| Chimei Innolux          | 153       | 9.94%   |
| BOE                     | 153       | 9.94%   |
| Samsung Electronics     | 139       | 9.03%   |
| CPT                     | 129       | 8.38%   |
| Dell                    | 64        | 4.16%   |
| Eizo                    | 61        | 3.96%   |
| Sharp                   | 40        | 2.6%    |
| Lenovo                  | 36        | 2.34%   |
| Chi Mei Optoelectronics | 31        | 2.01%   |
| PANDA                   | 30        | 1.95%   |
| Hewlett-Packard         | 29        | 1.88%   |
| Philips                 | 22        | 1.43%   |
| Goldstar                | 19        | 1.23%   |
| BenQ                    | 18        | 1.17%   |
| LG Philips              | 17        | 1.1%    |
| AOC                     | 16        | 1.04%   |
| Acer                    | 12        | 0.78%   |
| CSO                     | 10        | 0.65%   |
| InfoVision              | 9         | 0.58%   |
| Apple                   | 7         | 0.45%   |
| Sony                    | 6         | 0.39%   |
| Quanta Display          | 6         | 0.39%   |
| Iiyama                  | 6         | 0.39%   |
| Ancor Communications    | 6         | 0.39%   |
| Panasonic               | 5         | 0.32%   |
| HannStar                | 5         | 0.32%   |
| Toshiba                 | 4         | 0.26%   |
| Valve                   | 3         | 0.19%   |
| NEC Computers           | 3         | 0.19%   |
| ASUSTek Computer        | 3         | 0.19%   |
| Vestel Elektronik       | 2         | 0.13%   |
| Unknown                 | 2         | 0.13%   |
| OEM                     | 2         | 0.13%   |
| JDI                     | 2         | 0.13%   |
| Hitachi                 | 2         | 0.13%   |
| Fujitsu Siemens         | 2         | 0.13%   |
| DENON                   | 2         | 0.13%   |
| ViewSonic               | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                      | 127       | 8.06%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                         | 57        | 3.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 14        | 0.89%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 11        | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 11        | 0.7%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 10        | 0.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.57%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 7         | 0.44%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 7         | 0.44%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 7         | 0.44%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 7         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 7         | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 6         | 0.38%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 6         | 0.38%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch               | 6         | 0.38%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 6         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 6         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 6         | 0.38%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 6         | 0.38%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 6         | 0.38%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 6         | 0.38%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 6         | 0.38%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 5         | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 5         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 5         | 0.32%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 5         | 0.32%   |
| Hewlett-Packard Z24n HWP320E 1920x1200 518x324mm 24.1-inch                | 5         | 0.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 5         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 5         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 5         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1520 1680x1050 331x207mm 15.4-inch | 5         | 0.32%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                     | 5         | 0.32%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 5         | 0.32%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 5         | 0.32%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 5         | 0.32%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 5         | 0.32%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 5         | 0.32%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 5         | 0.32%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch      | 4         | 0.25%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch      | 4         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 609       | 42.35%  |
| 1366x768 (WXGA)    | 260       | 18.08%  |
| 1600x900 (HD+)     | 198       | 13.77%  |
| 3840x2160 (4K)     | 103       | 7.16%   |
| 1280x800 (WXGA)    | 63        | 4.38%   |
| 2560x1440 (QHD)    | 48        | 3.34%   |
| 1920x1200 (WUXGA)  | 36        | 2.5%    |
| 1680x1050 (WSXGA+) | 17        | 1.18%   |
| 1440x900 (WXGA+)   | 16        | 1.11%   |
| 2560x1600          | 15        | 1.04%   |
| 1280x1024 (SXGA)   | 8         | 0.56%   |
| 1024x600           | 8         | 0.56%   |
| 2880x1800          | 5         | 0.35%   |
| 1024x768 (XGA)     | 5         | 0.35%   |
| 3840x2400          | 4         | 0.28%   |
| 1360x768           | 4         | 0.28%   |
| 800x1280           | 3         | 0.21%   |
| 3456x2160          | 3         | 0.21%   |
| 3440x1440          | 3         | 0.21%   |
| 3000x2000          | 3         | 0.21%   |
| 2160x1440          | 3         | 0.21%   |
| 1920x540           | 3         | 0.21%   |
| Unknown            | 3         | 0.21%   |
| 3840x1200          | 2         | 0.14%   |
| 3200x1800 (QHD+)   | 2         | 0.14%   |
| 2160x1350          | 2         | 0.14%   |
| 1400x1050          | 2         | 0.14%   |
| 8320x2160          | 1         | 0.07%   |
| 5760x2160          | 1         | 0.07%   |
| 3840x1080          | 1         | 0.07%   |
| 3072x1920          | 1         | 0.07%   |
| 2880x1620          | 1         | 0.07%   |
| 2560x1080          | 1         | 0.07%   |
| 2288x1287          | 1         | 0.07%   |
| 2256x1504          | 1         | 0.07%   |
| 2240x1400          | 1         | 0.07%   |
| 1920x515           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 529       | 34.22%  |
| 13      | 287       | 18.56%  |
| 14      | 183       | 11.84%  |
| 17      | 91        | 5.89%   |
| 24      | 83        | 5.37%   |
| 31      | 72        | 4.66%   |
| 27      | 58        | 3.75%   |
| 23      | 42        | 2.72%   |
| 11      | 30        | 1.94%   |
| 12      | 29        | 1.88%   |
| 21      | 24        | 1.55%   |
| 16      | 18        | 1.16%   |
| Unknown | 14        | 0.91%   |
| 22      | 10        | 0.65%   |
| 10      | 10        | 0.65%   |
| 84      | 7         | 0.45%   |
| 18      | 7         | 0.45%   |
| 20      | 6         | 0.39%   |
| 19      | 5         | 0.32%   |
| 40      | 4         | 0.26%   |
| 34      | 4         | 0.26%   |
| 33      | 4         | 0.26%   |
| 32      | 4         | 0.26%   |
| 25      | 4         | 0.26%   |
| 54      | 3         | 0.19%   |
| 26      | 3         | 0.19%   |
| 7       | 3         | 0.19%   |
| 72      | 2         | 0.13%   |
| 49      | 2         | 0.13%   |
| 43      | 2         | 0.13%   |
| 142     | 1         | 0.06%   |
| 60      | 1         | 0.06%   |
| 52      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 38      | 1         | 0.06%   |
| 29      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 799       | 52.46%  |
| 201-300        | 269       | 17.66%  |
| 501-600        | 166       | 10.9%   |
| 351-400        | 108       | 7.09%   |
| 601-700        | 80        | 5.25%   |
| 401-500        | 47        | 3.09%   |
| Unknown        | 14        | 0.92%   |
| 701-800        | 12        | 0.79%   |
| 1001-1500      | 10        | 0.66%   |
| 1501-2000      | 9         | 0.59%   |
| 801-900        | 5         | 0.33%   |
| 1-100          | 3         | 0.2%    |
| More than 2000 | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1072      | 83.1%   |
| 16/10   | 172       | 13.33%  |
| 3/2     | 10        | 0.78%   |
| Unknown | 10        | 0.78%   |
| 5/4     | 8         | 0.62%   |
| 4/3     | 7         | 0.54%   |
| 21/9    | 4         | 0.31%   |
| 0.67    | 3         | 0.23%   |
| 3.20    | 2         | 0.16%   |
| 3.73    | 1         | 0.08%   |
| 1.00    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 523       | 33.98%  |
| 81-90          | 277       | 18%     |
| 71-80          | 190       | 12.35%  |
| 201-250        | 119       | 7.73%   |
| 351-500        | 85        | 5.52%   |
| 121-130        | 72        | 4.68%   |
| 301-350        | 61        | 3.96%   |
| 251-300        | 33        | 2.14%   |
| 51-60          | 30        | 1.95%   |
| 61-70          | 29        | 1.88%   |
| 111-120        | 19        | 1.23%   |
| 151-200        | 17        | 1.1%    |
| More than 1000 | 16        | 1.04%   |
| 131-140        | 15        | 0.97%   |
| Unknown        | 14        | 0.91%   |
| 41-50          | 10        | 0.65%   |
| 141-150        | 10        | 0.65%   |
| 501-1000       | 8         | 0.52%   |
| 91-100         | 8         | 0.52%   |
| 1-40           | 3         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 724       | 49.9%   |
| 101-120       | 303       | 20.88%  |
| 51-100        | 272       | 18.75%  |
| 161-240       | 96        | 6.62%   |
| More than 240 | 30        | 2.07%   |
| Unknown       | 14        | 0.96%   |
| 1-50          | 12        | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 957       | 72.55%  |
| 2     | 285       | 21.61%  |
| 3     | 40        | 3.03%   |
| 0     | 36        | 2.73%   |
| 4     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 671       | 32.23%  |
| Realtek Semiconductor                  | 537       | 25.79%  |
| Qualcomm Atheros                       | 376       | 18.06%  |
| Samsung Electronics                    | 130       | 6.24%   |
| Broadcom                               | 113       | 5.43%   |
| Broadcom Limited                       | 46        | 2.21%   |
| MediaTek                               | 36        | 1.73%   |
| Lenovo                                 | 22        | 1.06%   |
| Marvell Technology Group               | 21        | 1.01%   |
| Dell                                   | 17        | 0.82%   |
| ASIX Electronics                       | 13        | 0.62%   |
| Sierra Wireless                        | 11        | 0.53%   |
| Ralink                                 | 11        | 0.53%   |
| DisplayLink                            | 11        | 0.53%   |
| Ralink Technology                      | 10        | 0.48%   |
| TP-Link                                | 9         | 0.43%   |
| Qualcomm Atheros Communications        | 8         | 0.38%   |
| Qualcomm                               | 5         | 0.24%   |
| Ericsson Business Mobile Networks      | 5         | 0.24%   |
| Attansic Technology                    | 5         | 0.24%   |
| Hewlett-Packard                        | 4         | 0.19%   |
| Xiaomi                                 | 3         | 0.14%   |
| Spreadtrum Communications              | 2         | 0.1%    |
| Silicon Integrated Systems [SiS]       | 2         | 0.1%    |
| Huawei Technologies                    | 2         | 0.1%    |
| Fibocom                                | 2         | 0.1%    |
| D-Link                                 | 2         | 0.1%    |
| VIA Technologies                       | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| ICS Advent                             | 1         | 0.05%   |
| Fujitsu Siemens Computers              | 1         | 0.05%   |
| Foxconn / Hon Hai                      | 1         | 0.05%   |
| ASUSTek Computer                       | 1         | 0.05%   |
| Arduino SA                             | 1         | 0.05%   |
| AMD                                    | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 337       | 13.56%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 151       | 6.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 127       | 5.11%   |
| Intel Wi-Fi 6 AX200                                               | 81        | 3.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 75        | 3.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 62        | 2.49%   |
| Intel Wireless 8265 / 8275                                        | 55        | 2.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 2.05%   |
| Intel Wireless 7260                                               | 47        | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 40        | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 40        | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 38        | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 36        | 1.45%   |
| Intel Wireless 8260                                               | 34        | 1.37%   |
| Intel Wi-Fi 6 AX201                                               | 33        | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 29        | 1.17%   |
| Intel Wireless 7265                                               | 27        | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 26        | 1.05%   |
| Intel Wireless 3165                                               | 26        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 26        | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 25        | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 24        | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 22        | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 22        | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 18        | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 18        | 0.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 18        | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 17        | 0.68%   |
| Intel WiFi Link 5100                                              | 17        | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 16        | 0.64%   |
| Intel Wireless 3160                                               | 15        | 0.6%    |
| Intel Ethernet Connection I217-LM                                 | 15        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 15        | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                     | 15        | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 651       | 49.58%  |
| Qualcomm Atheros                | 333       | 25.36%  |
| Realtek Semiconductor           | 130       | 9.9%    |
| Broadcom                        | 71        | 5.41%   |
| MediaTek                        | 33        | 2.51%   |
| Broadcom Limited                | 25        | 1.9%    |
| Sierra Wireless                 | 11        | 0.84%   |
| Ralink                          | 11        | 0.84%   |
| Dell                            | 11        | 0.84%   |
| Ralink Technology               | 10        | 0.76%   |
| TP-Link                         | 8         | 0.61%   |
| Qualcomm Atheros Communications | 8         | 0.61%   |
| Qualcomm                        | 4         | 0.3%    |
| Hewlett-Packard                 | 2         | 0.15%   |
| Fibocom                         | 2         | 0.15%   |
| Fujitsu Siemens Computers       | 1         | 0.08%   |
| D-Link                          | 1         | 0.08%   |
| ASUSTek Computer                | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 151       | 11.47%  |
| Intel Wi-Fi 6 AX200                                                     | 81        | 6.15%   |
| Intel Wireless 8265 / 8275                                              | 55        | 4.18%   |
| Intel Wireless 7260                                                     | 47        | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 40        | 3.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 40        | 3.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 38        | 2.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 36        | 2.73%   |
| Intel Wireless 8260                                                     | 34        | 2.58%   |
| Intel Wi-Fi 6 AX201                                                     | 33        | 2.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 31        | 2.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 29        | 2.2%    |
| Intel Wireless 7265                                                     | 27        | 2.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 26        | 1.97%   |
| Intel Wireless 3165                                                     | 26        | 1.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 26        | 1.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 24        | 1.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 22        | 1.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 22        | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 18        | 1.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 18        | 1.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 17        | 1.29%   |
| Intel WiFi Link 5100                                                    | 17        | 1.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 17        | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 16        | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 1.21%   |
| Intel Wireless 3160                                                     | 15        | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 15        | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                           | 15        | 1.14%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 11        | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 0.76%   |
| Intel Ultimate N WiFi Link 5300                                         | 10        | 0.76%   |
| Intel Centrino Wireless-N 2230                                          | 10        | 0.76%   |
| Realtek 802.11n WLAN Adapter                                            | 9         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 9         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 0.68%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 9         | 0.68%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 9         | 0.68%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 478       | 42.41%  |
| Intel                            | 277       | 24.58%  |
| Samsung Electronics              | 130       | 11.54%  |
| Qualcomm Atheros                 | 82        | 7.28%   |
| Broadcom                         | 49        | 4.35%   |
| Lenovo                           | 22        | 1.95%   |
| Marvell Technology Group         | 21        | 1.86%   |
| Broadcom Limited                 | 21        | 1.86%   |
| ASIX Electronics                 | 13        | 1.15%   |
| DisplayLink                      | 11        | 0.98%   |
| Attansic Technology              | 5         | 0.44%   |
| Xiaomi                           | 3         | 0.27%   |
| MediaTek                         | 3         | 0.27%   |
| Spreadtrum Communications        | 2         | 0.18%   |
| Silicon Integrated Systems [SiS] | 2         | 0.18%   |
| VIA Technologies                 | 1         | 0.09%   |
| TP-Link                          | 1         | 0.09%   |
| Qualcomm                         | 1         | 0.09%   |
| ICS Advent                       | 1         | 0.09%   |
| Huawei Technologies              | 1         | 0.09%   |
| Hewlett-Packard                  | 1         | 0.09%   |
| Foxconn / Hon Hai                | 1         | 0.09%   |
| D-Link                           | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 337       | 29.38%  |
| Samsung Galaxy series, misc. (tethering mode)                                  | 127       | 11.07%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 75        | 6.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 62        | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 51        | 4.45%   |
| Intel Ethernet Connection (4) I219-LM                                          | 25        | 2.18%   |
| Intel 82567LM Gigabit Network Connection                                       | 18        | 1.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 16        | 1.39%   |
| Intel Ethernet Connection I218-LM                                              | 16        | 1.39%   |
| Intel Ethernet Connection I217-LM                                              | 15        | 1.31%   |
| Intel Ethernet Connection I219-LM                                              | 14        | 1.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 13        | 1.13%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 13        | 1.13%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 12        | 1.05%   |
| Intel Ethernet Connection (4) I219-V                                           | 12        | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 12        | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                                          | 11        | 0.96%   |
| Intel Ethernet Connection (6) I219-V                                           | 11        | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 0.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 8         | 0.7%    |
| Intel Ethernet Connection (6) I219-LM                                          | 8         | 0.7%    |
| Intel Ethernet Connection (10) I219-LM                                         | 8         | 0.7%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 8         | 0.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 0.61%   |
| Intel Ethernet Connection I219-V                                               | 7         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 6         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6         | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 6         | 0.52%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 6         | 0.52%   |
| Intel Ethernet Connection (11) I219-LM                                         | 6         | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 6         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 5         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 5         | 0.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 5         | 0.44%   |
| Intel Ethernet Connection I217-V                                               | 5         | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 0.44%   |
| Intel Ethernet Connection (16) I219-LM                                         | 5         | 0.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 5         | 0.44%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 5         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1253      | 53.64%  |
| Ethernet | 1062      | 45.46%  |
| Modem    | 20        | 0.86%   |
| Unknown  | 1         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 929       | 69.02%  |
| Ethernet | 417       | 30.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 848       | 66.35%  |
| 1     | 394       | 30.83%  |
| 0     | 23        | 1.8%    |
| 3     | 13        | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1102      | 85.1%   |
| Yes  | 193       | 14.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 469       | 49.84%  |
| Realtek Semiconductor           | 88        | 9.35%   |
| Qualcomm Atheros Communications | 72        | 7.65%   |
| IMC Networks                    | 68        | 7.23%   |
| Broadcom                        | 54        | 5.74%   |
| Foxconn / Hon Hai               | 46        | 4.89%   |
| Lite-On Technology              | 43        | 4.57%   |
| Hewlett-Packard                 | 26        | 2.76%   |
| Dell                            | 17        | 1.81%   |
| ASUSTek Computer                | 15        | 1.59%   |
| Ralink                          | 8         | 0.85%   |
| Apple                           | 6         | 0.64%   |
| MediaTek                        | 5         | 0.53%   |
| Cambridge Silicon Radio         | 5         | 0.53%   |
| Alps Electric                   | 5         | 0.53%   |
| Toshiba                         | 4         | 0.43%   |
| Realtek                         | 4         | 0.43%   |
| Ralink Technology               | 2         | 0.21%   |
| Micro Star International        | 1         | 0.11%   |
| Fujitsu Siemens Computers       | 1         | 0.11%   |
| Foxconn International           | 1         | 0.11%   |
| Askey Computer                  | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 192       | 20.4%   |
| Intel AX200 Bluetooth                                                               | 81        | 8.61%   |
| Intel AX201 Bluetooth                                                               | 80        | 8.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 60        | 6.38%   |
| Realtek Bluetooth Radio                                                             | 58        | 6.16%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 28        | 2.98%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 23        | 2.44%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 18        | 1.91%   |
| Intel Bluetooth Device                                                              | 17        | 1.81%   |
| IMC Networks Bluetooth Device                                                       | 16        | 1.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 15        | 1.59%   |
| IMC Networks Bluetooth Radio                                                        | 15        | 1.59%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 14        | 1.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 14        | 1.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 1.28%   |
| IMC Networks Wireless_Device                                                        | 12        | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 12        | 1.28%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 11        | 1.17%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 11        | 1.17%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 10        | 1.06%   |
| Broadcom BCM2045 Bluetooth                                                          | 10        | 1.06%   |
| Dell DW375 Bluetooth Module                                                         | 9         | 0.96%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 9         | 0.96%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 0.85%   |
| Broadcom HP Portable SoftSailing                                                    | 8         | 0.85%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 8         | 0.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 7         | 0.74%   |
| Qualcomm Atheros Bluetooth                                                          | 6         | 0.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.64%   |
| Intel AX210 Bluetooth                                                               | 6         | 0.64%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 6         | 0.64%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 5         | 0.53%   |
| Lite-On Bluetooth Device                                                            | 5         | 0.53%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 0.53%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.43%   |
| Realtek Bluetooth Radio                                                             | 4         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1019      | 64.62%  |
| AMD                                  | 266       | 16.87%  |
| Nvidia                               | 150       | 9.51%   |
| Lenovo                               | 29        | 1.84%   |
| C-Media Electronics                  | 19        | 1.2%    |
| Realtek Semiconductor                | 17        | 1.08%   |
| GN Netcom                            | 13        | 0.82%   |
| Hewlett-Packard                      | 7         | 0.44%   |
| Logitech                             | 6         | 0.38%   |
| JMTek                                | 5         | 0.32%   |
| Plantronics                          | 4         | 0.25%   |
| Creative Technology                  | 4         | 0.25%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.19%   |
| Kingston Technology                  | 3         | 0.19%   |
| RODE Microphones                     | 2         | 0.13%   |
| Harman                               | 2         | 0.13%   |
| GYROCOM C&C                          | 2         | 0.13%   |
| DSEA A/S                             | 2         | 0.13%   |
| Dell                                 | 2         | 0.13%   |
| BEHRINGER International              | 2         | 0.13%   |
| Yealink Network Technology           | 1         | 0.06%   |
| Yamaha                               | 1         | 0.06%   |
| VIA Technologies                     | 1         | 0.06%   |
| Trust                                | 1         | 0.06%   |
| Toshiba                              | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| Syntek                               | 1         | 0.06%   |
| Sennheiser Communications            | 1         | 0.06%   |
| Samson Technologies                  | 1         | 0.06%   |
| Razer USA                            | 1         | 0.06%   |
| Orbbec 3D Technology International   | 1         | 0.06%   |
| M-Audio                              | 1         | 0.06%   |
| Generalplus Technology               | 1         | 0.06%   |
| Focusrite-Novation                   | 1         | 0.06%   |
| ELMCU                                | 1         | 0.06%   |
| DigiTech                             | 1         | 0.06%   |
| Datelink Technology                  | 1         | 0.06%   |
| Conexant Systems                     | 1         | 0.06%   |
| AudioQuest                           | 1         | 0.06%   |
| Apple                                | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 196       | 10.4%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 150       | 7.96%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 126       | 6.68%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 102       | 5.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 77        | 4.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 56        | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 46        | 2.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 45        | 2.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 44        | 2.33%   |
| Intel 8 Series HD Audio Controller                                                                | 44        | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 40        | 2.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 38        | 2.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 37        | 1.96%   |
| AMD FCH Azalia Controller                                                                         | 35        | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 33        | 1.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 33        | 1.75%   |
| Intel Broadwell-U Audio Controller                                                                | 33        | 1.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 33        | 1.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 31        | 1.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 27        | 1.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 25        | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 24        | 1.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 23        | 1.22%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 22        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 20        | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 20        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 19        | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19        | 1.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 19        | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                                          | 18        | 0.95%   |
| AMD High Definition Audio Controller                                                              | 18        | 0.95%   |
| Realtek Semiconductor USB Audio                                                                   | 17        | 0.9%    |
| Intel CM238 HD Audio Controller                                                                   | 17        | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 15        | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 15        | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 0.69%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 12        | 0.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 11        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 211       | 24.2%   |
| SK hynix             | 177       | 20.3%   |
| Elpida               | 142       | 16.28%  |
| Micron Technology    | 111       | 12.73%  |
| Kingston             | 88        | 10.09%  |
| Unknown              | 39        | 4.47%   |
| Crucial              | 26        | 2.98%   |
| Ramaxel Technology   | 21        | 2.41%   |
| Unknown (ABCD)       | 14        | 1.61%   |
| Corsair              | 11        | 1.26%   |
| A-DATA Technology    | 10        | 1.15%   |
| Nanya Technology     | 7         | 0.8%    |
| Patriot              | 4         | 0.46%   |
| Transcend            | 2         | 0.23%   |
| Unknown (AB)         | 1         | 0.11%   |
| ProMos/Mosel Vitelic | 1         | 0.11%   |
| OnBoard              | 1         | 0.11%   |
| Nayna                | 1         | 0.11%   |
| Golden Empire        | 1         | 0.11%   |
| G.Skill              | 1         | 0.11%   |
| fef5                 | 1         | 0.11%   |
| ASint Technology     | 1         | 0.11%   |
| Unknown              | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 126       | 13.83%  |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 1.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 1.43%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 12        | 1.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 1.21%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 10        | 1.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.99%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.99%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.88%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 7         | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.77%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.77%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.77%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.66%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.66%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 6         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.55%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 5         | 0.55%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.55%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.55%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.55%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.55%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.44%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.44%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 4         | 0.44%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 4         | 0.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.44%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.44%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 4         | 0.44%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.44%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.44%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 4         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 327       | 43.25%  |
| DDR3    | 306       | 40.48%  |
| LPDDR4  | 50        | 6.61%   |
| DDR2    | 27        | 3.57%   |
| LPDDR3  | 19        | 2.51%   |
| SDRAM   | 11        | 1.46%   |
| LPDDR5  | 7         | 0.93%   |
| DDR     | 4         | 0.53%   |
| Unknown | 3         | 0.4%    |
| DDR5    | 2         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 682       | 89.5%   |
| Row Of Chips | 66        | 8.66%   |
| Chip         | 10        | 1.31%   |
| DIMM         | 2         | 0.26%   |
| Unknown      | 2         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 281       | 34.48%  |
| 2048  | 196       | 24.05%  |
| 4096  | 165       | 20.25%  |
| 16384 | 129       | 15.83%  |
| 32768 | 21        | 2.58%   |
| 1024  | 18        | 2.21%   |
| 512   | 2         | 0.25%   |
| 6144  | 1         | 0.12%   |
| 3072  | 1         | 0.12%   |
| 256   | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 156       | 19.55%  |
| 1333    | 145       | 18.17%  |
| 1600    | 123       | 15.41%  |
| 2667    | 121       | 15.16%  |
| 2400    | 61        | 7.64%   |
| 2133    | 34        | 4.26%   |
| 1334    | 32        | 4.01%   |
| 4267    | 18        | 2.26%   |
| Unknown | 13        | 1.63%   |
| 667     | 12        | 1.5%    |
| 1867    | 11        | 1.38%   |
| 3266    | 10        | 1.25%   |
| 1067    | 10        | 1.25%   |
| 6400    | 7         | 0.88%   |
| 800     | 6         | 0.75%   |
| 4266    | 5         | 0.63%   |
| 4199    | 5         | 0.63%   |
| 975     | 5         | 0.63%   |
| 533     | 5         | 0.63%   |
| 2048    | 4         | 0.5%    |
| 1066    | 4         | 0.5%    |
| 4800    | 3         | 0.38%   |
| 3733    | 3         | 0.38%   |
| 8400    | 2         | 0.25%   |
| 2933    | 1         | 0.13%   |
| 1639    | 1         | 0.13%   |
| 1400    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Xerox               | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Prolific Technology | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Xerox Phaser 3260                | 1         | 20%     |
| Samsung M2070 Series             | 1         | 20%     |
| Prolific PL2305 Parallel Port    | 1         | 20%     |
| HP LaserJet Professional P 1102w | 1         | 20%     |
| Canon LBP3010/LBP3018/LBP3050    | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 270       | 26.63%  |
| Realtek Semiconductor                  | 105       | 10.36%  |
| IMC Networks                           | 100       | 9.86%   |
| Microdia                               | 79        | 7.79%   |
| Bison Electronics                      | 71        | 7%      |
| Sunplus Innovation Technology          | 66        | 6.51%   |
| Quanta                                 | 45        | 4.44%   |
| Lite-On Technology                     | 43        | 4.24%   |
| Cheng Uei Precision Industry (Foxlink) | 38        | 3.75%   |
| Suyin                                  | 35        | 3.45%   |
| Acer                                   | 33        | 3.25%   |
| Syntek                                 | 26        | 2.56%   |
| Luxvisions Innotech Limited            | 12        | 1.18%   |
| Apple                                  | 12        | 1.18%   |
| Alcor Micro                            | 11        | 1.08%   |
| Ricoh                                  | 10        | 0.99%   |
| Lenovo                                 | 10        | 0.99%   |
| Logitech                               | 8         | 0.79%   |
| Samsung Electronics                    | 6         | 0.59%   |
| Sonix Technology                       | 4         | 0.39%   |
| Primax Electronics                     | 3         | 0.3%    |
| icSpring                               | 3         | 0.3%    |
| Intel                                  | 2         | 0.2%    |
| Colorado                               | 2         | 0.2%    |
| Z-Star Microelectronics                | 1         | 0.1%    |
| Sunplus Technology                     | 1         | 0.1%    |
| Silicon Motion                         | 1         | 0.1%    |
| Ruision                                | 1         | 0.1%    |
| Pixart Imaging                         | 1         | 0.1%    |
| Orbbec 3D Technology International     | 1         | 0.1%    |
| OPPO Electronics                       | 1         | 0.1%    |
| Microsoft                              | 1         | 0.1%    |
| lihappe8                               | 1         | 0.1%    |
| KYE Systems (Mouse Systems)            | 1         | 0.1%    |
| Hopewin Electronic Material            | 1         | 0.1%    |
| Goodong Industry                       | 1         | 0.1%    |
| Genesys Logic                          | 1         | 0.1%    |
| GEMBIRD                                | 1         | 0.1%    |
| eMPIA Technology                       | 1         | 0.1%    |
| Elecom                                 | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 72        | 7.07%   |
| IMC Networks Integrated Camera                | 45        | 4.42%   |
| Microdia Integrated_Webcam_HD                 | 37        | 3.63%   |
| Realtek Integrated_Webcam_HD                  | 33        | 3.24%   |
| Chicony HP HD Camera                          | 27        | 2.65%   |
| Chicony HD WebCam                             | 24        | 2.36%   |
| IMC Networks USB2.0 HD UVC WebCam             | 21        | 2.06%   |
| Bison Integrated Camera                       | 21        | 2.06%   |
| Lite-On HP HD Camera                          | 18        | 1.77%   |
| Sunplus Integrated_Webcam_HD                  | 16        | 1.57%   |
| Chicony Integrated Camera (1280x720@30)       | 14        | 1.37%   |
| Syntek Integrated Camera                      | 13        | 1.28%   |
| Lite-On Integrated Camera                     | 12        | 1.18%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 12        | 1.18%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 11        | 1.08%   |
| Quanta HP HD Camera                           | 11        | 1.08%   |
| Bison SunplusIT Integrated Camera             | 11        | 1.08%   |
| Sunplus HD WebCam                             | 10        | 0.98%   |
| Microdia Integrated Webcam                    | 10        | 0.98%   |
| Chicony USB2.0 VGA UVC WebCam                 | 10        | 0.98%   |
| Acer Lenovo EasyCamera                        | 10        | 0.98%   |
| Acer Integrated Camera                        | 10        | 0.98%   |
| Quanta HD User Facing                         | 9         | 0.88%   |
| Bison Lenovo Integrated Webcam                | 9         | 0.88%   |
| Bison Lenovo EasyCamera                       | 9         | 0.88%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR            | 9         | 0.88%   |
| Realtek USB2.0 camera                         | 8         | 0.79%   |
| Realtek Integrated Webcam HD                  | 8         | 0.79%   |
| Chicony Lenovo EasyCamera                     | 8         | 0.79%   |
| Chicony HP HD Webcam                          | 8         | 0.79%   |
| Syntek Lenovo EasyCamera                      | 7         | 0.69%   |
| Sunplus Asus Webcam                           | 7         | 0.69%   |
| Lenovo Integrated Webcam                      | 7         | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 7         | 0.69%   |
| Sunplus HP HD Webcam [Fixed]                  | 6         | 0.59%   |
| Samsung Galaxy series, misc. (MTP mode)       | 6         | 0.59%   |
| Realtek USB2.0 VGA UVC WebCam                 | 6         | 0.59%   |
| Realtek USB2.0 HD UVC WebCam                  | 6         | 0.59%   |
| Realtek USB Camera                            | 6         | 0.59%   |
| Realtek Acer 640 x 480 laptop camera          | 6         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 99        | 34.62%  |
| Validity Sensors                   | 94        | 32.87%  |
| Shenzhen Goodix Technology         | 33        | 11.54%  |
| AuthenTec                          | 28        | 9.79%   |
| Upek                               | 13        | 4.55%   |
| Elan Microelectronics              | 9         | 3.15%   |
| LighTuning Technology              | 7         | 2.45%   |
| STMicroelectronics                 | 1         | 0.35%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.35%   |
| Microsoft                          | 1         | 0.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 30        | 10.49%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 9.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 19        | 6.64%   |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 6.29%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 5.24%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 4.55%   |
| Synaptics Fingerprint reader [HP G6]                                       | 12        | 4.2%    |
| Validity Sensors VFS491                                                    | 11        | 3.85%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 3.85%   |
| AuthenTec AES2810                                                          | 11        | 3.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 3.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 3.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.15%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 3.15%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.45%   |
| AuthenTec AES1600                                                          | 7         | 2.45%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 2.1%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 2.1%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.75%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.75%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.4%    |
| Elan ELAN:ARM-M4                                                           | 4         | 1.4%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.05%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.05%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.05%   |
| Synaptics  WBDI                                                            | 3         | 1.05%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.7%    |
| Synaptics WBDI                                                             | 2         | 0.7%    |
| Synaptics UWP WBDI Device                                                  | 2         | 0.7%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.35%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.35%   |
| Synaptics WBDI Device                                                      | 1         | 0.35%   |
| Synaptics UWP WBDI                                                         | 1         | 0.35%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.35%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.35%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.35%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 66        | 53.66%  |
| Alcor Micro               | 37        | 30.08%  |
| O2 Micro                  | 9         | 7.32%   |
| Lenovo                    | 5         | 4.07%   |
| Upek                      | 2         | 1.63%   |
| SCM Microsystems          | 2         | 1.63%   |
| Purism, SPC               | 1         | 0.81%   |
| Aladdin Knowledge Systems | 1         | 0.81%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 37        | 30.08%  |
| Broadcom 58200                                                               | 22        | 17.89%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 13.01%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 11.38%  |
| Broadcom 5880                                                                | 14        | 11.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 6.5%    |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.07%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.63%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.63%   |
| Purism, SPC Librem Key                                                       | 1         | 0.81%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.81%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.81%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 744       | 57.32%  |
| 1     | 409       | 31.51%  |
| 2     | 119       | 9.17%   |
| 3     | 20        | 1.54%   |
| 5     | 3         | 0.23%   |
| 4     | 3         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 281       | 39.41%  |
| Graphics card            | 137       | 19.21%  |
| Chipcard                 | 107       | 15.01%  |
| Net/wireless             | 47        | 6.59%   |
| Multimedia controller    | 31        | 4.35%   |
| Storage                  | 22        | 3.09%   |
| Camera                   | 22        | 3.09%   |
| Bluetooth                | 20        | 2.81%   |
| Communication controller | 12        | 1.68%   |
| Card reader              | 11        | 1.54%   |
| Flash memory             | 7         | 0.98%   |
| Net/ethernet             | 5         | 0.7%    |
| Modem                    | 5         | 0.7%    |
| Sound                    | 4         | 0.56%   |
| Storage/ata              | 1         | 0.14%   |
| Network                  | 1         | 0.14%   |

