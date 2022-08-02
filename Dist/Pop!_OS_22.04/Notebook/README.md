Pop!_OS 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

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

Total: 569

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5520               | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [7b369e1cdf](https://linux-hardware.org/?probe=7b369e1cdf) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4e2361dd88](https://linux-hardware.org/?probe=4e2361dd88) | Aug 01, 2022 |
| GPU Compan... | GWTN141-10                  | [d73365fe3e](https://linux-hardware.org/?probe=d73365fe3e) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [bdc243bf9f](https://linux-hardware.org/?probe=bdc243bf9f) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [41a0eba80f](https://linux-hardware.org/?probe=41a0eba80f) | Jul 31, 2022 |
| HP            | Pavilion 17                 | [b2c0846cf5](https://linux-hardware.org/?probe=b2c0846cf5) | Jul 31, 2022 |
| Acer          | Swift SF314-51              | [f9a61fd8ad](https://linux-hardware.org/?probe=f9a61fd8ad) | Jul 31, 2022 |
| Acer          | Swift SF314-43              | [36659d2410](https://linux-hardware.org/?probe=36659d2410) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f4a9c3bc7f](https://linux-hardware.org/?probe=f4a9c3bc7f) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f017593574](https://linux-hardware.org/?probe=f017593574) | Jul 30, 2022 |
| Dell          | Vostro 15 3515              | [74b9e88d97](https://linux-hardware.org/?probe=74b9e88d97) | Jul 30, 2022 |
| Intel Clie... | LAPKC71F                    | [0783ac445f](https://linux-hardware.org/?probe=0783ac445f) | Jul 30, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [bf8e504209](https://linux-hardware.org/?probe=bf8e504209) | Jul 30, 2022 |
| PC Special... | NS50MU                      | [b5dd220296](https://linux-hardware.org/?probe=b5dd220296) | Jul 29, 2022 |
| Positivo      | C4128E-S                    | [a06c799159](https://linux-hardware.org/?probe=a06c799159) | Jul 29, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [cf54e60bf1](https://linux-hardware.org/?probe=cf54e60bf1) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [e392f0348d](https://linux-hardware.org/?probe=e392f0348d) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [dea75365be](https://linux-hardware.org/?probe=dea75365be) | Jul 29, 2022 |
| HP            | Pavilion 13 x360 PC         | [a5220ea2c0](https://linux-hardware.org/?probe=a5220ea2c0) | Jul 28, 2022 |
| Dell          | Inspiron 3542               | [d0ff2340b1](https://linux-hardware.org/?probe=d0ff2340b1) | Jul 28, 2022 |
| Sony          | VPCEG27FM                   | [b8c840d19a](https://linux-hardware.org/?probe=b8c840d19a) | Jul 28, 2022 |
| MSI           | Modern 15 A5M               | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | [7c25b2c2c7](https://linux-hardware.org/?probe=7c25b2c2c7) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | [97bbabec13](https://linux-hardware.org/?probe=97bbabec13) | Jul 28, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [c884d7548c](https://linux-hardware.org/?probe=c884d7548c) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| MSI           | Prestige 15 A10SC           | [0fe8633425](https://linux-hardware.org/?probe=0fe8633425) | Jul 27, 2022 |
| MSI           | Prestige 15 A10SC           | [36001f3112](https://linux-hardware.org/?probe=36001f3112) | Jul 27, 2022 |
| Dell          | Vostro 5470                 | [82192dcb1d](https://linux-hardware.org/?probe=82192dcb1d) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | [a33f728c24](https://linux-hardware.org/?probe=a33f728c24) | Jul 27, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [8e76bb6095](https://linux-hardware.org/?probe=8e76bb6095) | Jul 27, 2022 |
| HP            | Pavilion dv6                | [577c3ce56c](https://linux-hardware.org/?probe=577c3ce56c) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| MSI           | GF63 Thin 11UD              | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [04ae47501b](https://linux-hardware.org/?probe=04ae47501b) | Jul 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7005989783](https://linux-hardware.org/?probe=7005989783) | Jul 26, 2022 |
| Acer          | Ferrari One 200             | [023ff9a691](https://linux-hardware.org/?probe=023ff9a691) | Jul 25, 2022 |
| Acer          | Ferrari One 200             | [447f8a06ea](https://linux-hardware.org/?probe=447f8a06ea) | Jul 25, 2022 |
| System76      | Lemur Pro                   | [c6269208fe](https://linux-hardware.org/?probe=c6269208fe) | Jul 25, 2022 |
| Acer          | Nitro AN515-42              | [8c5e11fe0e](https://linux-hardware.org/?probe=8c5e11fe0e) | Jul 25, 2022 |
| Dynabook      | Satellite Pro C50D-B        | [bd7ef0af73](https://linux-hardware.org/?probe=bd7ef0af73) | Jul 25, 2022 |
| GPU Compan... | GWTC116-2                   | [ac0f2b51c0](https://linux-hardware.org/?probe=ac0f2b51c0) | Jul 25, 2022 |
| MSI           | GF63 Thin 11UD              | [03bb89eced](https://linux-hardware.org/?probe=03bb89eced) | Jul 24, 2022 |
| Lenovo        | E41-25 81FS                 | [51b984566a](https://linux-hardware.org/?probe=51b984566a) | Jul 24, 2022 |
| Acer          | Aspire V3-551G              | [970f226406](https://linux-hardware.org/?probe=970f226406) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | [d41e7515af](https://linux-hardware.org/?probe=d41e7515af) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | [fdada0c3a6](https://linux-hardware.org/?probe=fdada0c3a6) | Jul 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [c1515e724a](https://linux-hardware.org/?probe=c1515e724a) | Jul 24, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [147556bf0a](https://linux-hardware.org/?probe=147556bf0a) | Jul 23, 2022 |
| Apple         | MacBookPro12,1              | [752155f862](https://linux-hardware.org/?probe=752155f862) | Jul 23, 2022 |
| Apple         | MacBookPro8,2               | [e31685e3ae](https://linux-hardware.org/?probe=e31685e3ae) | Jul 23, 2022 |
| Apple         | MacBookAir7,2               | [a86b33bdc2](https://linux-hardware.org/?probe=a86b33bdc2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f9e9de55c0](https://linux-hardware.org/?probe=f9e9de55c0) | Jul 22, 2022 |
| Dell          | Vostro 5470                 | [95c9916b84](https://linux-hardware.org/?probe=95c9916b84) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| ASUSTek       | K93SM                       | [add292129b](https://linux-hardware.org/?probe=add292129b) | Jul 22, 2022 |
| Samsung       | 760XDA                      | [c3e04193b8](https://linux-hardware.org/?probe=c3e04193b8) | Jul 22, 2022 |
| GPU Compan... | GWTC116-2                   | [4763ba77ba](https://linux-hardware.org/?probe=4763ba77ba) | Jul 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [da25f9d9b4](https://linux-hardware.org/?probe=da25f9d9b4) | Jul 22, 2022 |
| HP            | ProBook 450 G3              | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [f965008c98](https://linux-hardware.org/?probe=f965008c98) | Jul 21, 2022 |
| Toshiba       | BLB                         | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Vostro 5470                 | [e73fa302e0](https://linux-hardware.org/?probe=e73fa302e0) | Jul 21, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [ed3f7b7f50](https://linux-hardware.org/?probe=ed3f7b7f50) | Jul 21, 2022 |
| Dell          | Vostro 5470                 | [c6dcb4ffa6](https://linux-hardware.org/?probe=c6dcb4ffa6) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Acer          | Aspire V3-551G              | [f5675c45dc](https://linux-hardware.org/?probe=f5675c45dc) | Jul 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | [48e2fa9544](https://linux-hardware.org/?probe=48e2fa9544) | Jul 19, 2022 |
| ASUSTek       | K52Dr                       | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| Apple         | MacBookPro5,1               | [8a81341ecd](https://linux-hardware.org/?probe=8a81341ecd) | Jul 18, 2022 |
| Dell          | Latitude D430               | [22c020a070](https://linux-hardware.org/?probe=22c020a070) | Jul 18, 2022 |
| HP            | Laptop 14-bw0xx             | [df814add04](https://linux-hardware.org/?probe=df814add04) | Jul 18, 2022 |
| Acer          | Aspire V3-551G              | [2baa51bbc9](https://linux-hardware.org/?probe=2baa51bbc9) | Jul 18, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [b903541b55](https://linux-hardware.org/?probe=b903541b55) | Jul 18, 2022 |
| ASUSTek       | X555LAB                     | [8ae373a79c](https://linux-hardware.org/?probe=8ae373a79c) | Jul 17, 2022 |
| Acer          | Aspire 5520                 | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| ASUSTek       | K53SJ                       | [515f269efc](https://linux-hardware.org/?probe=515f269efc) | Jul 17, 2022 |
| Gigabyte      | Blade Pro                   | [3c2576e897](https://linux-hardware.org/?probe=3c2576e897) | Jul 16, 2022 |
| MSI           | GS75 Stealth 9SG            | [8707f3e800](https://linux-hardware.org/?probe=8707f3e800) | Jul 16, 2022 |
| Alienware     | 15 R2                       | [8a6bd6054f](https://linux-hardware.org/?probe=8a6bd6054f) | Jul 16, 2022 |
| MSI           | Katana GF76 11UD            | [61b03607fa](https://linux-hardware.org/?probe=61b03607fa) | Jul 15, 2022 |
| Dell          | Precision M4600             | [96f8364d87](https://linux-hardware.org/?probe=96f8364d87) | Jul 15, 2022 |
| HUAWEI        | MACH-WX9                    | [76035ea427](https://linux-hardware.org/?probe=76035ea427) | Jul 15, 2022 |
| HP            | Laptop 17z-ca200            | [1159e9b888](https://linux-hardware.org/?probe=1159e9b888) | Jul 15, 2022 |
| System76      | Pangolin                    | [690b7b5984](https://linux-hardware.org/?probe=690b7b5984) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| ASUSTek       | X555LAB                     | [5c5b387f6c](https://linux-hardware.org/?probe=5c5b387f6c) | Jul 14, 2022 |
| Dell          | XPS 15 9520                 | [271277c36b](https://linux-hardware.org/?probe=271277c36b) | Jul 14, 2022 |
| Lenovo        | ThinkPad X230 2325YHU       | [4720a42a7f](https://linux-hardware.org/?probe=4720a42a7f) | Jul 14, 2022 |
| HP            | Laptop 14-fq0xxx            | [c21113bf90](https://linux-hardware.org/?probe=c21113bf90) | Jul 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [285e41f0aa](https://linux-hardware.org/?probe=285e41f0aa) | Jul 14, 2022 |
| Samsung       | 950XED                      | [b7f59889a0](https://linux-hardware.org/?probe=b7f59889a0) | Jul 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [27f79db974](https://linux-hardware.org/?probe=27f79db974) | Jul 13, 2022 |
| MSI           | GF63 Thin 11UD              | [b4cf81df26](https://linux-hardware.org/?probe=b4cf81df26) | Jul 13, 2022 |
| Lenovo        | Legion Y540-17IRH 81UJ      | [b70dfefc75](https://linux-hardware.org/?probe=b70dfefc75) | Jul 13, 2022 |
| MSI           | GF63 Thin 11UD              | [7107c7c2eb](https://linux-hardware.org/?probe=7107c7c2eb) | Jul 13, 2022 |
| Dell          | Latitude 3500               | [f42f32c17f](https://linux-hardware.org/?probe=f42f32c17f) | Jul 12, 2022 |
| HP            | EliteBook 8570w             | [495c5afa4b](https://linux-hardware.org/?probe=495c5afa4b) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [9cc1538196](https://linux-hardware.org/?probe=9cc1538196) | Jul 12, 2022 |
| ASUSTek       | K53SJ                       | [f3ead95b28](https://linux-hardware.org/?probe=f3ead95b28) | Jul 12, 2022 |
| GPU Compan... | GWTN141-10                  | [0ce04e7b03](https://linux-hardware.org/?probe=0ce04e7b03) | Jul 12, 2022 |
| Apple         | MacBookPro7,1               | [821459e114](https://linux-hardware.org/?probe=821459e114) | Jul 12, 2022 |
| Dell          | Vostro 5470                 | [aedb7a18da](https://linux-hardware.org/?probe=aedb7a18da) | Jul 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [34c2c24b3b](https://linux-hardware.org/?probe=34c2c24b3b) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ebbc4ebc1d](https://linux-hardware.org/?probe=ebbc4ebc1d) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [d200cc6f06](https://linux-hardware.org/?probe=d200cc6f06) | Jul 11, 2022 |
| Lenovo        | 14w 81MQ0013AU              | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| ASUSTek       | K53SJ                       | [1a9d6df3b5](https://linux-hardware.org/?probe=1a9d6df3b5) | Jul 11, 2022 |
| Dell          | Latitude E5440              | [2b94e70ac9](https://linux-hardware.org/?probe=2b94e70ac9) | Jul 11, 2022 |
| Dell          | Inspiron 1750               | [c39e03e656](https://linux-hardware.org/?probe=c39e03e656) | Jul 10, 2022 |
| MSI           | Katana GF76 11UG            | [8f152d3669](https://linux-hardware.org/?probe=8f152d3669) | Jul 10, 2022 |
| Dell          | Inspiron 1750               | [a885fd8b41](https://linux-hardware.org/?probe=a885fd8b41) | Jul 10, 2022 |
| Medion        | Erazer P6661 MD60303        | [35fbb2c055](https://linux-hardware.org/?probe=35fbb2c055) | Jul 10, 2022 |
| Apple         | MacBookPro11,3              | [9b65b57a57](https://linux-hardware.org/?probe=9b65b57a57) | Jul 10, 2022 |
| Acer          | Aspire A515-52              | [9dc5c32b9f](https://linux-hardware.org/?probe=9dc5c32b9f) | Jul 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2330... | [4718003bb5](https://linux-hardware.org/?probe=4718003bb5) | Jul 09, 2022 |
| Dell          | Latitude E7450              | [d0c3f69765](https://linux-hardware.org/?probe=d0c3f69765) | Jul 09, 2022 |
| MSI           | MS-16G4                     | [53f40f3420](https://linux-hardware.org/?probe=53f40f3420) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | [38e90a5b4d](https://linux-hardware.org/?probe=38e90a5b4d) | Jul 08, 2022 |
| Apple         | MacBookPro9,2               | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| ASUSTek       | G751JT                      | [92eb60a700](https://linux-hardware.org/?probe=92eb60a700) | Jul 08, 2022 |
| Panasonic     | CF-C2AQAZXLM                | [be9cf3127a](https://linux-hardware.org/?probe=be9cf3127a) | Jul 08, 2022 |
| ASUSTek       | K53SJ                       | [f9d5ea94ec](https://linux-hardware.org/?probe=f9d5ea94ec) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| ASUSTek       | X55CR                       | [9e40e3f8ad](https://linux-hardware.org/?probe=9e40e3f8ad) | Jul 08, 2022 |
| HUAWEI        | MACH-WX9                    | [486d051b71](https://linux-hardware.org/?probe=486d051b71) | Jul 08, 2022 |
| Dell          | Vostro 5625                 | [b2fde3bdef](https://linux-hardware.org/?probe=b2fde3bdef) | Jul 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [3b7528beab](https://linux-hardware.org/?probe=3b7528beab) | Jul 07, 2022 |
| System76      | Lemur Pro                   | [bdc2ddb608](https://linux-hardware.org/?probe=bdc2ddb608) | Jul 07, 2022 |
| Toshiba       | Satellite L650              | [76de8069a0](https://linux-hardware.org/?probe=76de8069a0) | Jul 07, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [861d7b3714](https://linux-hardware.org/?probe=861d7b3714) | Jul 07, 2022 |
| Acer          | Nitro AN515-53              | [d31c5d1c11](https://linux-hardware.org/?probe=d31c5d1c11) | Jul 06, 2022 |
| Acer          | Nitro AN515-53              | [0304267499](https://linux-hardware.org/?probe=0304267499) | Jul 06, 2022 |
| Pegatron      | H36FF                       | [87eac99d1b](https://linux-hardware.org/?probe=87eac99d1b) | Jul 06, 2022 |
| Acer          | Aspire E3-112M              | [6de763aad6](https://linux-hardware.org/?probe=6de763aad6) | Jul 06, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [a9d516466a](https://linux-hardware.org/?probe=a9d516466a) | Jul 06, 2022 |
| ASUSTek       | K50ID                       | [a194cebb73](https://linux-hardware.org/?probe=a194cebb73) | Jul 06, 2022 |
| ASUSTek       | K50ID                       | [90ccec43bf](https://linux-hardware.org/?probe=90ccec43bf) | Jul 06, 2022 |
| HP            | EliteBook 745 G2            | [21b712ca64](https://linux-hardware.org/?probe=21b712ca64) | Jul 05, 2022 |
| MSI           | Katana GF76 11UD            | [ece534d446](https://linux-hardware.org/?probe=ece534d446) | Jul 05, 2022 |
| MSI           | Katana GF76 11UD            | [1c52419886](https://linux-hardware.org/?probe=1c52419886) | Jul 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [b4732a4bda](https://linux-hardware.org/?probe=b4732a4bda) | Jul 05, 2022 |
| Dell          | Precision M4700             | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| Dell          | Latitude 7280               | [b7ed5b72a9](https://linux-hardware.org/?probe=b7ed5b72a9) | Jul 05, 2022 |
| HP            | ProBook 640 G1              | [2f88b6162e](https://linux-hardware.org/?probe=2f88b6162e) | Jul 05, 2022 |
| HP            | Pavilion 15                 | [abbd7fd848](https://linux-hardware.org/?probe=abbd7fd848) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a673b1557d](https://linux-hardware.org/?probe=a673b1557d) | Jul 05, 2022 |
| Toshiba       | Satellite C650D             | [23da2ae018](https://linux-hardware.org/?probe=23da2ae018) | Jul 04, 2022 |
| Apple         | MacBookPro10,2              | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| Acer          | Aspire E1-572G              | [6f24a453bf](https://linux-hardware.org/?probe=6f24a453bf) | Jul 04, 2022 |
| Lenovo        | ThinkPad T440p 20AN009CU... | [67d4a66421](https://linux-hardware.org/?probe=67d4a66421) | Jul 04, 2022 |
| ASUSTek       | X541UJ                      | [d3f8e6dee5](https://linux-hardware.org/?probe=d3f8e6dee5) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Notebook      | P65xHP                      | [2b81391bb4](https://linux-hardware.org/?probe=2b81391bb4) | Jul 03, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [80c5bb3483](https://linux-hardware.org/?probe=80c5bb3483) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| Acer          | Aspire E5-473G              | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8999ce3eca](https://linux-hardware.org/?probe=8999ce3eca) | Jul 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [6e6839a1d0](https://linux-hardware.org/?probe=6e6839a1d0) | Jul 03, 2022 |
| ASUSTek       | G751JT                      | [f437b1ee99](https://linux-hardware.org/?probe=f437b1ee99) | Jul 03, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [a8c5e48dc8](https://linux-hardware.org/?probe=a8c5e48dc8) | Jul 03, 2022 |
| Dell          | Latitude E6420              | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fdb841889e](https://linux-hardware.org/?probe=fdb841889e) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming FX705DD_FX705... | [048a900062](https://linux-hardware.org/?probe=048a900062) | Jul 02, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [516b60430c](https://linux-hardware.org/?probe=516b60430c) | Jul 02, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [c70a95cfc1](https://linux-hardware.org/?probe=c70a95cfc1) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| Dell          | Precision 7510              | [4831b50f9a](https://linux-hardware.org/?probe=4831b50f9a) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | [7847c0275c](https://linux-hardware.org/?probe=7847c0275c) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | [6b1e1133e4](https://linux-hardware.org/?probe=6b1e1133e4) | Jul 01, 2022 |
| Dell          | Precision M4600             | [ea07b9e45f](https://linux-hardware.org/?probe=ea07b9e45f) | Jul 01, 2022 |
| Dell          | Precision M4600             | [535d6029bc](https://linux-hardware.org/?probe=535d6029bc) | Jul 01, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| Samsung       | 930XED                      | [56a04fa69d](https://linux-hardware.org/?probe=56a04fa69d) | Jul 01, 2022 |
| ASUSTek       | S550CA                      | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| Dell          | Precision 5530              | [d6dc0ecd91](https://linux-hardware.org/?probe=d6dc0ecd91) | Jul 01, 2022 |
| Dell          | Precision 5550              | [0ddb8905e5](https://linux-hardware.org/?probe=0ddb8905e5) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | [63508059d3](https://linux-hardware.org/?probe=63508059d3) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | [b7aef43e9e](https://linux-hardware.org/?probe=b7aef43e9e) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | [325fec2ac6](https://linux-hardware.org/?probe=325fec2ac6) | Jul 01, 2022 |
| HP            | Pavilion 15                 | [e35e3b2e52](https://linux-hardware.org/?probe=e35e3b2e52) | Jul 01, 2022 |
| Dell          | Precision 7510              | [c82cc3cb0f](https://linux-hardware.org/?probe=c82cc3cb0f) | Jul 01, 2022 |
| Dell          | Inspiron 5547               | [c2a91cc81e](https://linux-hardware.org/?probe=c2a91cc81e) | Jul 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ccb50bd0f4](https://linux-hardware.org/?probe=ccb50bd0f4) | Jun 30, 2022 |
| Apple         | MacBookAir7,2               | [ab31abf1d5](https://linux-hardware.org/?probe=ab31abf1d5) | Jun 30, 2022 |
| HP            | Pavilion 15                 | [f76f8dff7a](https://linux-hardware.org/?probe=f76f8dff7a) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6095915fb5](https://linux-hardware.org/?probe=6095915fb5) | Jun 30, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1f66ba5535](https://linux-hardware.org/?probe=1f66ba5535) | Jun 30, 2022 |
| Notebook      | P7xxDM3(-G)                 | [6abdc9b40d](https://linux-hardware.org/?probe=6abdc9b40d) | Jun 29, 2022 |
| Dell          | Latitude E5470              | [2440e59a5a](https://linux-hardware.org/?probe=2440e59a5a) | Jun 29, 2022 |
| Dell          | Inspiron 7460               | [c5e8b7f098](https://linux-hardware.org/?probe=c5e8b7f098) | Jun 29, 2022 |
| Eluktronic... | MECH-15 G3                  | [d307b13800](https://linux-hardware.org/?probe=d307b13800) | Jun 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c14a32dd6b](https://linux-hardware.org/?probe=c14a32dd6b) | Jun 28, 2022 |
| ASUSTek       | S550CA                      | [93807824df](https://linux-hardware.org/?probe=93807824df) | Jun 28, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [843cbccc63](https://linux-hardware.org/?probe=843cbccc63) | Jun 27, 2022 |
| HP            | Pavilion Notebook           | [8e17cfd388](https://linux-hardware.org/?probe=8e17cfd388) | Jun 26, 2022 |
| HP            | EliteBook 820 G2            | [e568c96372](https://linux-hardware.org/?probe=e568c96372) | Jun 25, 2022 |
| Lenovo        | ThinkPad X230 23331R5       | [c6589e02c4](https://linux-hardware.org/?probe=c6589e02c4) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | [90c701411f](https://linux-hardware.org/?probe=90c701411f) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | [fb02c13e80](https://linux-hardware.org/?probe=fb02c13e80) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [490c1074fe](https://linux-hardware.org/?probe=490c1074fe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [51d3a22bf6](https://linux-hardware.org/?probe=51d3a22bf6) | Jun 25, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [289b09bf25](https://linux-hardware.org/?probe=289b09bf25) | Jun 24, 2022 |
| System76      | Darter Pro                  | [db7f217878](https://linux-hardware.org/?probe=db7f217878) | Jun 24, 2022 |
| HP            | EliteBook 745 G2            | [fe87d16f84](https://linux-hardware.org/?probe=fe87d16f84) | Jun 24, 2022 |
| Dell          | Latitude E7470              | [c2a22e5a3d](https://linux-hardware.org/?probe=c2a22e5a3d) | Jun 24, 2022 |
| Dell          | Latitude E7470              | [962571591a](https://linux-hardware.org/?probe=962571591a) | Jun 24, 2022 |
| Alienware     | 14                          | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Toshiba       | Satellite S50-A             | [c2e7c1b26d](https://linux-hardware.org/?probe=c2e7c1b26d) | Jun 24, 2022 |
| ASUSTek       | S550CA                      | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Acer          | Swift SF314-54              | [47420af7dc](https://linux-hardware.org/?probe=47420af7dc) | Jun 23, 2022 |
| Dell          | Vostro 5470                 | [592f0a2f63](https://linux-hardware.org/?probe=592f0a2f63) | Jun 23, 2022 |
| Dell          | Precision 5520              | [2216faa750](https://linux-hardware.org/?probe=2216faa750) | Jun 22, 2022 |
| Dell          | Inspiron 7560               | [a65b832b57](https://linux-hardware.org/?probe=a65b832b57) | Jun 22, 2022 |
| Lenovo        | V14-IIL 82C4                | [c288025720](https://linux-hardware.org/?probe=c288025720) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | [3086580cf5](https://linux-hardware.org/?probe=3086580cf5) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | [0bc7456f92](https://linux-hardware.org/?probe=0bc7456f92) | Jun 21, 2022 |
| Dell          | Latitude E7240              | [1c76f3cdf4](https://linux-hardware.org/?probe=1c76f3cdf4) | Jun 21, 2022 |
| Quanta        | TWC                         | [6a466d7eac](https://linux-hardware.org/?probe=6a466d7eac) | Jun 21, 2022 |
| Dell          | Latitude E7240              | [2974c5fa7c](https://linux-hardware.org/?probe=2974c5fa7c) | Jun 21, 2022 |
| Dell          | XPS 15 9570                 | [c6c4eda2cb](https://linux-hardware.org/?probe=c6c4eda2cb) | Jun 21, 2022 |
| System76      | Lemur Pro                   | [0350f8d8f7](https://linux-hardware.org/?probe=0350f8d8f7) | Jun 21, 2022 |
| HP            | ProBook 440 G7              | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| Acer          | Iconia                      | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [9bffffd652](https://linux-hardware.org/?probe=9bffffd652) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [a8d859700b](https://linux-hardware.org/?probe=a8d859700b) | Jun 20, 2022 |
| HP            | ZBook 15 G3                 | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| ASUSTek       | N550JV                      | [d1d647724c](https://linux-hardware.org/?probe=d1d647724c) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Dell          | Inspiron 5537               | [2b31dedd45](https://linux-hardware.org/?probe=2b31dedd45) | Jun 19, 2022 |
| HP            | 15 Notebook PC              | [b3efe3d4b5](https://linux-hardware.org/?probe=b3efe3d4b5) | Jun 19, 2022 |
| Apple         | MacBookPro11,5              | [b04866cc36](https://linux-hardware.org/?probe=b04866cc36) | Jun 19, 2022 |
| Apple         | MacBook5,1                  | [e601e834f2](https://linux-hardware.org/?probe=e601e834f2) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [47b7f42708](https://linux-hardware.org/?probe=47b7f42708) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | [41eb5a7de2](https://linux-hardware.org/?probe=41eb5a7de2) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cb268bf1ab](https://linux-hardware.org/?probe=cb268bf1ab) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ed83fdd673](https://linux-hardware.org/?probe=ed83fdd673) | Jun 18, 2022 |
| Lenovo        | ThinkPad T450 20BUS1110E    | [77dd393da8](https://linux-hardware.org/?probe=77dd393da8) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | [d542c2f694](https://linux-hardware.org/?probe=d542c2f694) | Jun 18, 2022 |
| Dell          | Latitude E7240              | [2ed64f08f3](https://linux-hardware.org/?probe=2ed64f08f3) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [31340542c2](https://linux-hardware.org/?probe=31340542c2) | Jun 17, 2022 |
| HP            | Unknown                     | [4c4cdf6526](https://linux-hardware.org/?probe=4c4cdf6526) | Jun 17, 2022 |
| Apple         | MacBookAir7,2               | [13d72fd6f0](https://linux-hardware.org/?probe=13d72fd6f0) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [08efb8dcc5](https://linux-hardware.org/?probe=08efb8dcc5) | Jun 17, 2022 |
| Schenker      | VIA 15 Pro                  | [1d1727713f](https://linux-hardware.org/?probe=1d1727713f) | Jun 17, 2022 |
| HP            | EliteBook 8560p             | [8f60c0fb25](https://linux-hardware.org/?probe=8f60c0fb25) | Jun 17, 2022 |
| Dell          | Precision 5540              | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| Acer          | Aspire E5-574G              | [23c2dd37fe](https://linux-hardware.org/?probe=23c2dd37fe) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [b6978a823c](https://linux-hardware.org/?probe=b6978a823c) | Jun 17, 2022 |
| Acer          | Aspire 4741                 | [9f25816784](https://linux-hardware.org/?probe=9f25816784) | Jun 16, 2022 |
| Dell          | Inspiron 3442               | [10304caa6b](https://linux-hardware.org/?probe=10304caa6b) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b136496151](https://linux-hardware.org/?probe=b136496151) | Jun 16, 2022 |
| System76      | Oryx Pro                    | [4daa6c7d77](https://linux-hardware.org/?probe=4daa6c7d77) | Jun 16, 2022 |
| Dell          | Latitude E6540              | [93f049609f](https://linux-hardware.org/?probe=93f049609f) | Jun 16, 2022 |
| System76      | Galago Pro                  | [440ba53ef9](https://linux-hardware.org/?probe=440ba53ef9) | Jun 16, 2022 |
| Apple         | MacBookPro8,1               | [145a1e77fc](https://linux-hardware.org/?probe=145a1e77fc) | Jun 16, 2022 |
| Dell          | Inspiron 7520               | [d6e4d7642d](https://linux-hardware.org/?probe=d6e4d7642d) | Jun 16, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [cc1947a21b](https://linux-hardware.org/?probe=cc1947a21b) | Jun 15, 2022 |
| Acer          | Aspire E5-575G              | [aa390f3eaa](https://linux-hardware.org/?probe=aa390f3eaa) | Jun 15, 2022 |
| Sony          | SVF15A1M2ES                 | [bdcd4a90fc](https://linux-hardware.org/?probe=bdcd4a90fc) | Jun 15, 2022 |
| Dell          | Latitude E6540              | [03fb6fa23c](https://linux-hardware.org/?probe=03fb6fa23c) | Jun 15, 2022 |
| Dell          | Precision 5550              | [f5f815ceed](https://linux-hardware.org/?probe=f5f815ceed) | Jun 14, 2022 |
| Acer          | Swift SF314-54              | [06bccc3696](https://linux-hardware.org/?probe=06bccc3696) | Jun 14, 2022 |
| Dell          | Precision 7720              | [8b4da2326e](https://linux-hardware.org/?probe=8b4da2326e) | Jun 14, 2022 |
| Dell          | Precision 7720              | [bf25929cec](https://linux-hardware.org/?probe=bf25929cec) | Jun 14, 2022 |
| Dell          | Latitude E6540              | [44b876534d](https://linux-hardware.org/?probe=44b876534d) | Jun 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [f4ef35b902](https://linux-hardware.org/?probe=f4ef35b902) | Jun 14, 2022 |
| Dell          | Inspiron 7737               | [6fa74e19b1](https://linux-hardware.org/?probe=6fa74e19b1) | Jun 13, 2022 |
| Notebook      | P65_P67SE                   | [590b7204da](https://linux-hardware.org/?probe=590b7204da) | Jun 13, 2022 |
| HP            | EliteBook 820 G2            | [45ca271974](https://linux-hardware.org/?probe=45ca271974) | Jun 13, 2022 |
| Lenovo        | B40-80 80F6                 | [7449f0f8d2](https://linux-hardware.org/?probe=7449f0f8d2) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | [2eb24f0195](https://linux-hardware.org/?probe=2eb24f0195) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | [110ff08266](https://linux-hardware.org/?probe=110ff08266) | Jun 13, 2022 |
| Apple         | MacBookPro11,1              | [7222fb776a](https://linux-hardware.org/?probe=7222fb776a) | Jun 13, 2022 |
| Dell          | Latitude E6540              | [91e07b8f2d](https://linux-hardware.org/?probe=91e07b8f2d) | Jun 12, 2022 |
| ASUSTek       | UX430UQ                     | [9754c7394d](https://linux-hardware.org/?probe=9754c7394d) | Jun 12, 2022 |
| Dell          | System XPS L702X            | [b79115e065](https://linux-hardware.org/?probe=b79115e065) | Jun 12, 2022 |
| MSI           | Alpha 17 A4DEK              | [42171e02bb](https://linux-hardware.org/?probe=42171e02bb) | Jun 11, 2022 |
| HP            | EliteBook 820 G2            | [0a0828f262](https://linux-hardware.org/?probe=0a0828f262) | Jun 11, 2022 |
| ASUSTek       | GL552VW                     | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| Dell          | Inspiron 7520               | [4916232f15](https://linux-hardware.org/?probe=4916232f15) | Jun 11, 2022 |
| Acer          | Aspire 4349                 | [7c8c3427a9](https://linux-hardware.org/?probe=7c8c3427a9) | Jun 11, 2022 |
| HP            | ProBook 455 G3              | [bac60198a3](https://linux-hardware.org/?probe=bac60198a3) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| Dell          | Latitude E7270              | [8d8f0db52c](https://linux-hardware.org/?probe=8d8f0db52c) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| ASUSTek       | Unknown                     | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| HP            | Elite x2 1012 G1            | [ad03ec2516](https://linux-hardware.org/?probe=ad03ec2516) | Jun 09, 2022 |
| Dell          | Inspiron 7520               | [ebbea30b2b](https://linux-hardware.org/?probe=ebbea30b2b) | Jun 09, 2022 |
| Dell          | G7 7790                     | [58cfc35862](https://linux-hardware.org/?probe=58cfc35862) | Jun 09, 2022 |
| Dell          | G7 7790                     | [495cfbb6f3](https://linux-hardware.org/?probe=495cfbb6f3) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | [c87c7a989a](https://linux-hardware.org/?probe=c87c7a989a) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| System76      | Oryx Pro                    | [bf9c9467d3](https://linux-hardware.org/?probe=bf9c9467d3) | Jun 08, 2022 |
| System76      | Oryx Pro                    | [2f96b6b08d](https://linux-hardware.org/?probe=2f96b6b08d) | Jun 08, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [5c2fedfca8](https://linux-hardware.org/?probe=5c2fedfca8) | Jun 08, 2022 |
| Dell          | Vostro 5402                 | [ebf8dce138](https://linux-hardware.org/?probe=ebf8dce138) | Jun 07, 2022 |
| Dell          | Inspiron 5537               | [7bb51064db](https://linux-hardware.org/?probe=7bb51064db) | Jun 07, 2022 |
| Dell          | Precision M4800             | [2607169dfe](https://linux-hardware.org/?probe=2607169dfe) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Framework     | Laptop                      | [ed8e682778](https://linux-hardware.org/?probe=ed8e682778) | Jun 06, 2022 |
| Samsung       | 760XDA                      | [46350b515c](https://linux-hardware.org/?probe=46350b515c) | Jun 06, 2022 |
| MSI           | GS75 Stealth 9SF            | [9d18e7094e](https://linux-hardware.org/?probe=9d18e7094e) | Jun 05, 2022 |
| ASUSTek       | X556URK                     | [d6da70c8bd](https://linux-hardware.org/?probe=d6da70c8bd) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [1485986503](https://linux-hardware.org/?probe=1485986503) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [2f60fd04bf](https://linux-hardware.org/?probe=2f60fd04bf) | Jun 05, 2022 |
| Acer          | Aspire A715-75G             | [d8a8c3c8b4](https://linux-hardware.org/?probe=d8a8c3c8b4) | Jun 05, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Dell          | Inspiron 3502               | [afa1c5cd74](https://linux-hardware.org/?probe=afa1c5cd74) | Jun 04, 2022 |
| Timi          | RedmiBook Pro 14S           | [f729442cad](https://linux-hardware.org/?probe=f729442cad) | Jun 04, 2022 |
| Dell          | Precision M4800             | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | G470 20078                  | [44e0643923](https://linux-hardware.org/?probe=44e0643923) | Jun 03, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [605cbc489f](https://linux-hardware.org/?probe=605cbc489f) | Jun 03, 2022 |
| Acer          | Aspire A515-43              | [a8c04eea72](https://linux-hardware.org/?probe=a8c04eea72) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [562348dd07](https://linux-hardware.org/?probe=562348dd07) | Jun 03, 2022 |
| Toshiba       | Satellite L850-1D5          | [c8a260ef80](https://linux-hardware.org/?probe=c8a260ef80) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [f1f4aec562](https://linux-hardware.org/?probe=f1f4aec562) | Jun 02, 2022 |
| ASUSTek       | N53SV                       | [d793b451f6](https://linux-hardware.org/?probe=d793b451f6) | Jun 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [9299688b01](https://linux-hardware.org/?probe=9299688b01) | Jun 02, 2022 |
| Dell          | Latitude E7470              | [f9a9090c54](https://linux-hardware.org/?probe=f9a9090c54) | Jun 02, 2022 |
| Dell          | Latitude 7390               | [0c7c9778aa](https://linux-hardware.org/?probe=0c7c9778aa) | Jun 02, 2022 |
| Dell          | Latitude E6540              | [de2e1727bc](https://linux-hardware.org/?probe=de2e1727bc) | Jun 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [491a4105d8](https://linux-hardware.org/?probe=491a4105d8) | Jun 01, 2022 |
| Dell          | Latitude E7240              | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Aspire ES1-572              | [6f6e6c038a](https://linux-hardware.org/?probe=6f6e6c038a) | Jun 01, 2022 |
| Lenovo        | ThinkPad T410 2537HN3       | [e373330c8b](https://linux-hardware.org/?probe=e373330c8b) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Dell          | Inspiron 13 5310            | [70eccb19d4](https://linux-hardware.org/?probe=70eccb19d4) | Jun 01, 2022 |
| Dell          | Inspiron 5537               | [506d3fb361](https://linux-hardware.org/?probe=506d3fb361) | Jun 01, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [d0dbd3d75e](https://linux-hardware.org/?probe=d0dbd3d75e) | Jun 01, 2022 |
| Dell          | G7 7700                     | [25e22bc243](https://linux-hardware.org/?probe=25e22bc243) | May 31, 2022 |
| Lenovo        | V14-IIL 82C4                | [871738fea2](https://linux-hardware.org/?probe=871738fea2) | May 31, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [ed28d49715](https://linux-hardware.org/?probe=ed28d49715) | May 30, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| HP            | Laptop 14-dq2xxx            | [14f581788f](https://linux-hardware.org/?probe=14f581788f) | May 30, 2022 |
| Acer          | Aspire A515-45              | [72b7fc79d4](https://linux-hardware.org/?probe=72b7fc79d4) | May 29, 2022 |
| Dell          | Vostro V130                 | [abefbba5b8](https://linux-hardware.org/?probe=abefbba5b8) | May 29, 2022 |
| Apple         | MacBookPro9,1               | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| MSI           | GF63 Thin 10SCXR            | [0d556408f3](https://linux-hardware.org/?probe=0d556408f3) | May 29, 2022 |
| HP            | OMEN by Laptop 15z-en100    | [35e3478a5d](https://linux-hardware.org/?probe=35e3478a5d) | May 28, 2022 |
| Medion        | X6816                       | [6d7996894c](https://linux-hardware.org/?probe=6d7996894c) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [7ae101b473](https://linux-hardware.org/?probe=7ae101b473) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [469ed3f68b](https://linux-hardware.org/?probe=469ed3f68b) | May 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [96bc0699c3](https://linux-hardware.org/?probe=96bc0699c3) | May 28, 2022 |
| Dell          | Inspiron 5566               | [88c420d481](https://linux-hardware.org/?probe=88c420d481) | May 28, 2022 |
| Toshiba       | IS 1413G                    | [c7a5f5eef3](https://linux-hardware.org/?probe=c7a5f5eef3) | May 28, 2022 |
| Acer          | Nitro AN515-42              | [a2f2dc2eee](https://linux-hardware.org/?probe=a2f2dc2eee) | May 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [65bccd9c04](https://linux-hardware.org/?probe=65bccd9c04) | May 27, 2022 |
| Dell          | Vostro 5402                 | [323fc36eb6](https://linux-hardware.org/?probe=323fc36eb6) | May 27, 2022 |
| Toshiba       | QOSMIO X770                 | [8f7d0ba9f9](https://linux-hardware.org/?probe=8f7d0ba9f9) | May 27, 2022 |
| Dell          | Precision 5530              | [2ecf3390bf](https://linux-hardware.org/?probe=2ecf3390bf) | May 27, 2022 |
| Acer          | Aspire A315-57G             | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [ab2cd65153](https://linux-hardware.org/?probe=ab2cd65153) | May 26, 2022 |
| Dell          | Inspiron 3721               | [d4af21adb8](https://linux-hardware.org/?probe=d4af21adb8) | May 25, 2022 |
| A-DATA Tec... | XENIA 15                    | [1d7941d921](https://linux-hardware.org/?probe=1d7941d921) | May 25, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [4c0d37687e](https://linux-hardware.org/?probe=4c0d37687e) | May 25, 2022 |
| Toshiba       | Satellite P850              | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| Apple         | MacBookPro14,3              | [ca090207b8](https://linux-hardware.org/?probe=ca090207b8) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | [647e502881](https://linux-hardware.org/?probe=647e502881) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | [0db0bd7aa8](https://linux-hardware.org/?probe=0db0bd7aa8) | May 25, 2022 |
| ASUSTek       | G551JM                      | [3db2e28ef2](https://linux-hardware.org/?probe=3db2e28ef2) | May 24, 2022 |
| Toshiba       | IS 1413G                    | [a34eaa3e4a](https://linux-hardware.org/?probe=a34eaa3e4a) | May 24, 2022 |
| Dell          | Precision 5550              | [6b17026494](https://linux-hardware.org/?probe=6b17026494) | May 24, 2022 |
| Toshiba       | IS 1413G                    | [e6e080d6e0](https://linux-hardware.org/?probe=e6e080d6e0) | May 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [a59234d081](https://linux-hardware.org/?probe=a59234d081) | May 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [bf692d5408](https://linux-hardware.org/?probe=bf692d5408) | May 23, 2022 |
| Acer          | Swift SF314-54              | [39f85b46d7](https://linux-hardware.org/?probe=39f85b46d7) | May 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f2e32c336d](https://linux-hardware.org/?probe=f2e32c336d) | May 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Apple         | MacBookPro11,1              | [1d4f3a60c0](https://linux-hardware.org/?probe=1d4f3a60c0) | May 23, 2022 |
| ASUSTek       | X505BA                      | [685c1f7378](https://linux-hardware.org/?probe=685c1f7378) | May 22, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| Dell          | G3 3500                     | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| Google        | Lulu                        | [e7a0842114](https://linux-hardware.org/?probe=e7a0842114) | May 21, 2022 |
| MSI           | Modern 14 A10M              | [97a0996658](https://linux-hardware.org/?probe=97a0996658) | May 21, 2022 |
| HP            | Pavilion Notebook           | [1cd571d585](https://linux-hardware.org/?probe=1cd571d585) | May 21, 2022 |
| ASUSTek       | X510UR                      | [40b1695a67](https://linux-hardware.org/?probe=40b1695a67) | May 21, 2022 |
| ASUSTek       | X510UR                      | [e7cea85f09](https://linux-hardware.org/?probe=e7cea85f09) | May 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| PC Special... | NP5x_NP6x_NP7xPNK_PNH_PN... | [e002072665](https://linux-hardware.org/?probe=e002072665) | May 21, 2022 |
| HP            | EliteBook 8570w             | [3f21c66d5c](https://linux-hardware.org/?probe=3f21c66d5c) | May 20, 2022 |
| Lenovo        | G40-30 80FY                 | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| System76      | Oryx Pro                    | [d705be052a](https://linux-hardware.org/?probe=d705be052a) | May 20, 2022 |
| Dell          | Inspiron 5555               | [35c2610913](https://linux-hardware.org/?probe=35c2610913) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Dell          | XPS 15 9570                 | [ba19473e18](https://linux-hardware.org/?probe=ba19473e18) | May 19, 2022 |
| Gigabyte      | AERO 15 KC                  | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c9a82e1be0](https://linux-hardware.org/?probe=c9a82e1be0) | May 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [8ef2235464](https://linux-hardware.org/?probe=8ef2235464) | May 17, 2022 |
| System76      | Oryx Pro                    | [b68edfe15c](https://linux-hardware.org/?probe=b68edfe15c) | May 17, 2022 |
| Samsung       | 550XCJ/550XCR               | [5bc959890b](https://linux-hardware.org/?probe=5bc959890b) | May 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e4bf8d23b8](https://linux-hardware.org/?probe=e4bf8d23b8) | May 17, 2022 |
| HUAWEI        | HN-WX9X                     | [f5ade437dc](https://linux-hardware.org/?probe=f5ade437dc) | May 17, 2022 |
| HP            | Laptop 14-dk1xxx            | [77a8cae8a0](https://linux-hardware.org/?probe=77a8cae8a0) | May 17, 2022 |
| ASUSTek       | G73Jh                       | [2d96e5ecba](https://linux-hardware.org/?probe=2d96e5ecba) | May 17, 2022 |
| Toshiba       | Satellite L50D-C            | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| Alienware     | 18                          | [7aa82b2786](https://linux-hardware.org/?probe=7aa82b2786) | May 17, 2022 |
| Acer          | Aspire 7560G                | [d3d9aa988f](https://linux-hardware.org/?probe=d3d9aa988f) | May 16, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [eb5345a5c6](https://linux-hardware.org/?probe=eb5345a5c6) | May 16, 2022 |
| Google        | Lulu                        | [c402204a03](https://linux-hardware.org/?probe=c402204a03) | May 16, 2022 |
| Fujitsu       | LIFEBOOK T5010              | [e0aab70a85](https://linux-hardware.org/?probe=e0aab70a85) | May 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [3a369eed6d](https://linux-hardware.org/?probe=3a369eed6d) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [3ecda9477c](https://linux-hardware.org/?probe=3ecda9477c) | May 16, 2022 |
| Apple         | MacBookPro14,1              | [2d4d81086f](https://linux-hardware.org/?probe=2d4d81086f) | May 15, 2022 |
| Acer          | TravelMate P249-G2-MG       | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| Dell          | Vostro 5471                 | [62e934492d](https://linux-hardware.org/?probe=62e934492d) | May 15, 2022 |
| Dell          | XPS 15 9510                 | [653725bdde](https://linux-hardware.org/?probe=653725bdde) | May 15, 2022 |
| Dell          | XPS 15 9560                 | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [7a2fd723d6](https://linux-hardware.org/?probe=7a2fd723d6) | May 14, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [98db0dde2a](https://linux-hardware.org/?probe=98db0dde2a) | May 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [66e43801f0](https://linux-hardware.org/?probe=66e43801f0) | May 13, 2022 |
| Google        | Lulu                        | [8d7f1657d0](https://linux-hardware.org/?probe=8d7f1657d0) | May 13, 2022 |
| Acer          | Swift SF314-54              | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [30bb58501e](https://linux-hardware.org/?probe=30bb58501e) | May 13, 2022 |
| Apple         | MacBookPro5,2               | [0a3017f333](https://linux-hardware.org/?probe=0a3017f333) | May 13, 2022 |
| Acer          | Nitro AN515-44              | [fe8e3837f4](https://linux-hardware.org/?probe=fe8e3837f4) | May 12, 2022 |
| System76      | Pangolin                    | [0f05fa93a8](https://linux-hardware.org/?probe=0f05fa93a8) | May 12, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Apple         | MacBookAir7,2               | [114ef2756f](https://linux-hardware.org/?probe=114ef2756f) | May 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
| Google        | Cyan                        | [cec3bd0a88](https://linux-hardware.org/?probe=cec3bd0a88) | May 11, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [4f25a82453](https://linux-hardware.org/?probe=4f25a82453) | May 11, 2022 |
| Apple         | MacBook5,2                  | [0913ac4c8e](https://linux-hardware.org/?probe=0913ac4c8e) | May 11, 2022 |
| System76      | Pangolin                    | [da80a33b86](https://linux-hardware.org/?probe=da80a33b86) | May 11, 2022 |
| Dell          | G15 5511                    | [17b75bcced](https://linux-hardware.org/?probe=17b75bcced) | May 10, 2022 |
| Dell          | XPS 13 9305                 | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| Dell          | XPS 13 9310                 | [cae0934838](https://linux-hardware.org/?probe=cae0934838) | May 10, 2022 |
| HP            | EliteBook 2730p             | [d4c5b7824d](https://linux-hardware.org/?probe=d4c5b7824d) | May 10, 2022 |
| HP            | 15 Notebook PC              | [d88f833b65](https://linux-hardware.org/?probe=d88f833b65) | May 10, 2022 |
| HP            | EliteBook 8570w             | [840087bbed](https://linux-hardware.org/?probe=840087bbed) | May 09, 2022 |
| HP            | EliteBook 8570w             | [d9779b1c50](https://linux-hardware.org/?probe=d9779b1c50) | May 09, 2022 |
| HP            | Laptop 15-dy1xxx            | [fd022c446e](https://linux-hardware.org/?probe=fd022c446e) | May 09, 2022 |
| TUXEDO        | Unknown                     | [20f46751c2](https://linux-hardware.org/?probe=20f46751c2) | May 08, 2022 |
| TUXEDO        | Unknown                     | [c1df33620d](https://linux-hardware.org/?probe=c1df33620d) | May 08, 2022 |
| MSI           | Modern 15 A10RAS            | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | [5eefaba8d3](https://linux-hardware.org/?probe=5eefaba8d3) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dcdc07525d](https://linux-hardware.org/?probe=dcdc07525d) | May 08, 2022 |
| Apple         | MacBookAir6,2               | [1e1f4caa54](https://linux-hardware.org/?probe=1e1f4caa54) | May 08, 2022 |
| Samsung       | 800G5M/800G5W               | [057ea02fdb](https://linux-hardware.org/?probe=057ea02fdb) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | [892d07e5cf](https://linux-hardware.org/?probe=892d07e5cf) | May 08, 2022 |
| Lenovo        | Legion 5 17ITH6H 82JM       | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| ASUSTek       | E200HA                      | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| MSI           | GS63 7RD                    | [eff12e3973](https://linux-hardware.org/?probe=eff12e3973) | May 08, 2022 |
| HP            | Pavilion 15                 | [a18593bb5b](https://linux-hardware.org/?probe=a18593bb5b) | May 07, 2022 |
| Google        | Lulu                        | [18ecc4a6e7](https://linux-hardware.org/?probe=18ecc4a6e7) | May 07, 2022 |
| Acer          | Aspire E1-570               | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| ASUSTek       | E200HA                      | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Google        | Peppy                       | [03dc670128](https://linux-hardware.org/?probe=03dc670128) | May 06, 2022 |
| HP            | ProBook 450 G4              | [1332984f5d](https://linux-hardware.org/?probe=1332984f5d) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | [710c086b29](https://linux-hardware.org/?probe=710c086b29) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | [76fb8bb966](https://linux-hardware.org/?probe=76fb8bb966) | May 06, 2022 |
| Dell          | XPS 13 9300                 | [080b4f2667](https://linux-hardware.org/?probe=080b4f2667) | May 06, 2022 |
| Lenovo        | G50-80 80E5                 | [8ecadc1bad](https://linux-hardware.org/?probe=8ecadc1bad) | May 05, 2022 |
| HP            | Pavilion Notebook           | [af36cfb1a8](https://linux-hardware.org/?probe=af36cfb1a8) | May 05, 2022 |
| Acer          | Aspire V5-431               | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [fa323515aa](https://linux-hardware.org/?probe=fa323515aa) | May 05, 2022 |
| Dell          | Inspiron 1750               | [1c70ba9e33](https://linux-hardware.org/?probe=1c70ba9e33) | May 05, 2022 |
| Dell          | Latitude E5440              | [a505dc0b3c](https://linux-hardware.org/?probe=a505dc0b3c) | May 05, 2022 |
| ASUSTek       | GL552VX                     | [d153ef27fa](https://linux-hardware.org/?probe=d153ef27fa) | May 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [a9f5b77476](https://linux-hardware.org/?probe=a9f5b77476) | May 04, 2022 |
| Acer          | Aspire A515-45              | [e5f3e5b086](https://linux-hardware.org/?probe=e5f3e5b086) | May 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [8bfd6ecc71](https://linux-hardware.org/?probe=8bfd6ecc71) | May 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5a8fc607c4](https://linux-hardware.org/?probe=5a8fc607c4) | May 04, 2022 |
| Dell          | Inspiron 3583               | [f5e954ea5e](https://linux-hardware.org/?probe=f5e954ea5e) | May 04, 2022 |
| HP            | Pavilion 13 x360 PC         | [5de9e1d61f](https://linux-hardware.org/?probe=5de9e1d61f) | May 04, 2022 |
| ASUSTek       | X540SAA                     | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| Acer          | Aspire F5-573G              | [2136362d58](https://linux-hardware.org/?probe=2136362d58) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | [373f22a70f](https://linux-hardware.org/?probe=373f22a70f) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | [91a367d874](https://linux-hardware.org/?probe=91a367d874) | May 03, 2022 |
| Apple         | MacBookAir6,2               | [0f8065fda6](https://linux-hardware.org/?probe=0f8065fda6) | May 03, 2022 |
| ASUSTek       | GL552JX                     | [c91f42212d](https://linux-hardware.org/?probe=c91f42212d) | May 03, 2022 |
| ASUSTek       | ROG Strix G713RC_G713RC     | [2ce25fb058](https://linux-hardware.org/?probe=2ce25fb058) | May 03, 2022 |
| Dell          | Inspiron 3583               | [c47758f125](https://linux-hardware.org/?probe=c47758f125) | May 03, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [4b44c67cde](https://linux-hardware.org/?probe=4b44c67cde) | May 02, 2022 |
| Toshiba       | PORTEGE R830                | [8daebf6110](https://linux-hardware.org/?probe=8daebf6110) | May 02, 2022 |
| Dell          | Latitude E6440              | [d2ab063048](https://linux-hardware.org/?probe=d2ab063048) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [58ff4a1984](https://linux-hardware.org/?probe=58ff4a1984) | May 02, 2022 |
| Toshiba       | Satellite L755              | [6c38249bc4](https://linux-hardware.org/?probe=6c38249bc4) | May 02, 2022 |
| Framework     | Laptop                      | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| Acer          | Aspire A515-45              | [8cf5364699](https://linux-hardware.org/?probe=8cf5364699) | May 02, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [02872ac9a8](https://linux-hardware.org/?probe=02872ac9a8) | May 02, 2022 |
| MSI           | GS65 Stealth 8SG            | [05f80b3e70](https://linux-hardware.org/?probe=05f80b3e70) | May 02, 2022 |
| System76      | Oryx Pro                    | [96251b761b](https://linux-hardware.org/?probe=96251b761b) | May 02, 2022 |
| Acer          | Aspire V5-573P              | [b64d1453d5](https://linux-hardware.org/?probe=b64d1453d5) | May 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [332445f774](https://linux-hardware.org/?probe=332445f774) | May 02, 2022 |
| MSI           | GP76 Leopard 11UG           | [dcea7cd8c0](https://linux-hardware.org/?probe=dcea7cd8c0) | May 02, 2022 |
| Dell          | Latitude E5570              | [372feb146c](https://linux-hardware.org/?probe=372feb146c) | May 02, 2022 |
| Apple         | MacBookPro12,1              | [5f68858e66](https://linux-hardware.org/?probe=5f68858e66) | May 01, 2022 |
| Acer          | Aspire 7750G                | [abd7ed0c5c](https://linux-hardware.org/?probe=abd7ed0c5c) | May 01, 2022 |
| LG Electro... | P430-G.BC41P1               | [527905ca3b](https://linux-hardware.org/?probe=527905ca3b) | May 01, 2022 |
| Apple         | MacBookPro4,1               | [be68c0201a](https://linux-hardware.org/?probe=be68c0201a) | May 01, 2022 |
| Apple         | MacBookPro7,1               | [ac3f2c5c61](https://linux-hardware.org/?probe=ac3f2c5c61) | May 01, 2022 |
| Apple         | MacBookPro4,1               | [83a8bbb313](https://linux-hardware.org/?probe=83a8bbb313) | May 01, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [48afcac3f0](https://linux-hardware.org/?probe=48afcac3f0) | May 01, 2022 |
| HP            | EliteBook 8440p             | [89a959efc4](https://linux-hardware.org/?probe=89a959efc4) | May 01, 2022 |
| HP            | ProBook 455 G7              | [88fcea9210](https://linux-hardware.org/?probe=88fcea9210) | Apr 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [48d3759522](https://linux-hardware.org/?probe=48d3759522) | Apr 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | [8383d306f3](https://linux-hardware.org/?probe=8383d306f3) | Apr 30, 2022 |
| Dell          | XPS 13 9343                 | [b48ccc106e](https://linux-hardware.org/?probe=b48ccc106e) | Apr 30, 2022 |
| Toshiba       | IS 1413G                    | [8074a86bc7](https://linux-hardware.org/?probe=8074a86bc7) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | [b92517268e](https://linux-hardware.org/?probe=b92517268e) | Apr 30, 2022 |
| ASUSTek       | G55VW                       | [6bd8a1b04a](https://linux-hardware.org/?probe=6bd8a1b04a) | Apr 29, 2022 |
| Dell          | Inspiron 3542               | [19f5e16bce](https://linux-hardware.org/?probe=19f5e16bce) | Apr 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [61bb949815](https://linux-hardware.org/?probe=61bb949815) | Apr 29, 2022 |
| Dell          | G5 5500                     | [c6064853ad](https://linux-hardware.org/?probe=c6064853ad) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [34015c4874](https://linux-hardware.org/?probe=34015c4874) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| System76      | Oryx Pro                    | [cf999d4581](https://linux-hardware.org/?probe=cf999d4581) | Apr 29, 2022 |
| Dell          | Inspiron 5547               | [a5d8e73a23](https://linux-hardware.org/?probe=a5d8e73a23) | Apr 28, 2022 |
| Dell          | Inspiron 5547               | [be4ab0fd27](https://linux-hardware.org/?probe=be4ab0fd27) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [995f77010e](https://linux-hardware.org/?probe=995f77010e) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [e2293170b3](https://linux-hardware.org/?probe=e2293170b3) | Apr 28, 2022 |
| Lenovo        | ThinkPad T431s 20ACS03P0... | [3c0878aee3](https://linux-hardware.org/?probe=3c0878aee3) | Apr 28, 2022 |
| System76      | Oryx Pro                    | [ae46ece731](https://linux-hardware.org/?probe=ae46ece731) | Apr 28, 2022 |
| HP            | Pavilion 15                 | [fee7e96d70](https://linux-hardware.org/?probe=fee7e96d70) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [a63dc69025](https://linux-hardware.org/?probe=a63dc69025) | Apr 28, 2022 |
| Apple         | MacBookPro10,2              | [2d79aab0aa](https://linux-hardware.org/?probe=2d79aab0aa) | Apr 28, 2022 |
| ASUSTek       | K40IN                       | [ab6a95da52](https://linux-hardware.org/?probe=ab6a95da52) | Apr 28, 2022 |
| HP            | Pavilion 13 x360 PC         | [d48ed77abc](https://linux-hardware.org/?probe=d48ed77abc) | Apr 28, 2022 |
| Dell          | Inspiron 5566               | [695d362d8f](https://linux-hardware.org/?probe=695d362d8f) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | [c227966510](https://linux-hardware.org/?probe=c227966510) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | [1275aa643d](https://linux-hardware.org/?probe=1275aa643d) | Apr 27, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Dell          | XPS 13 9310                 | [d394f4e0d9](https://linux-hardware.org/?probe=d394f4e0d9) | Apr 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [824ccc1317](https://linux-hardware.org/?probe=824ccc1317) | Apr 27, 2022 |
| HP            | Pavilion 13 x360 PC         | [3e5933fe0d](https://linux-hardware.org/?probe=3e5933fe0d) | Apr 27, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [e51ff27a5a](https://linux-hardware.org/?probe=e51ff27a5a) | Apr 27, 2022 |
| Dell          | Vostro 15 3515              | [7c99d7d4c5](https://linux-hardware.org/?probe=7c99d7d4c5) | Apr 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [863612cc05](https://linux-hardware.org/?probe=863612cc05) | Apr 27, 2022 |
| Purism        | Librem 15 v3                | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | [1fe2032839](https://linux-hardware.org/?probe=1fe2032839) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | [cabf0c7464](https://linux-hardware.org/?probe=cabf0c7464) | Apr 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [b7ac79ff8f](https://linux-hardware.org/?probe=b7ac79ff8f) | Apr 27, 2022 |
| MSI           | GS66 Stealth 10UG           | [77b699045a](https://linux-hardware.org/?probe=77b699045a) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| Acer          | Swift SF316-51              | [fe42983639](https://linux-hardware.org/?probe=fe42983639) | Apr 26, 2022 |
| Acer          | TravelMate P249-G2-MG       | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | [d4b7580074](https://linux-hardware.org/?probe=d4b7580074) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | [d994ff2a13](https://linux-hardware.org/?probe=d994ff2a13) | Apr 26, 2022 |
| Unknown       | Unknown                     | [885f468161](https://linux-hardware.org/?probe=885f468161) | Apr 26, 2022 |
| ASUSTek       | X555LF                      | [0aa3a88c0c](https://linux-hardware.org/?probe=0aa3a88c0c) | Apr 25, 2022 |
| Dell          | XPS 13 9360                 | [ffb9cf10be](https://linux-hardware.org/?probe=ffb9cf10be) | Apr 20, 2022 |
| Dell          | XPS 13 9360                 | [f174d4ced7](https://linux-hardware.org/?probe=f174d4ced7) | Apr 20, 2022 |
| Toshiba       | IS 1413G                    | [1b3267b605](https://linux-hardware.org/?probe=1b3267b605) | Apr 18, 2022 |
| Dell          | Latitude 5590               | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| Dell          | Latitude 5590               | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| Dell          | Latitude E7270              | [79cc908dcc](https://linux-hardware.org/?probe=79cc908dcc) | Apr 08, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.17.5-76051705-generic  | 217       | 49.89%  |
| 5.17.15-76051715-generic | 101       | 23.22%  |
| 5.16.19-76051619-generic | 70        | 16.09%  |
| 5.18.10-76051810-generic | 33        | 7.59%   |
| 5.17.5-051705-generic    | 2         | 0.46%   |
| 5.16.15-76051615-generic | 2         | 0.46%   |
| 5.19.0-rc1+              | 1         | 0.23%   |
| 5.18.6-xanmod1           | 1         | 0.23%   |
| 5.18.4-xanmod1           | 1         | 0.23%   |
| 5.18.0-051800rc1-generic | 1         | 0.23%   |
| 5.17.7-051707-generic    | 1         | 0.23%   |
| 5.17.6-051706-generic    | 1         | 0.23%   |
| 5.17.5-tkg-bmq           | 1         | 0.23%   |
| 5.17.2-xanmod1           | 1         | 0.23%   |
| 5.17.0-051700-generic    | 1         | 0.23%   |
| 5.16.11-76051611-generic | 1         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 220       | 50.57%  |
| 5.17.15 | 101       | 23.22%  |
| 5.16.19 | 70        | 16.09%  |
| 5.18.10 | 33        | 7.59%   |
| 5.16.15 | 2         | 0.46%   |
| 5.19.0  | 1         | 0.23%   |
| 5.18.6  | 1         | 0.23%   |
| 5.18.4  | 1         | 0.23%   |
| 5.18.0  | 1         | 0.23%   |
| 5.17.7  | 1         | 0.23%   |
| 5.17.6  | 1         | 0.23%   |
| 5.17.2  | 1         | 0.23%   |
| 5.17.0  | 1         | 0.23%   |
| 5.16.11 | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 319       | 74.36%  |
| 5.16    | 73        | 17.02%  |
| 5.18    | 36        | 8.39%   |
| 5.19    | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 422       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 412       | 97.4%   |
| KDE5            | 5         | 1.18%   |
| Unknown         | 3         | 0.71%   |
| XFCE            | 1         | 0.24%   |
| X-Cinnamon      | 1         | 0.24%   |
| GNOME Flashback | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 405       | 95.74%  |
| Wayland | 16        | 3.78%   |
| Unknown | 2         | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 337       | 79.67%  |
| GDM3    | 84        | 19.86%  |
| GDM     | 2         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 261       | 61.7%   |
| pt_BR   | 24        | 5.67%   |
| en_GB   | 24        | 5.67%   |
| de_DE   | 15        | 3.55%   |
| en_AU   | 13        | 3.07%   |
| fr_FR   | 12        | 2.84%   |
| it_IT   | 8         | 1.89%   |
| ru_RU   | 6         | 1.42%   |
| pl_PL   | 6         | 1.42%   |
| es_ES   | 6         | 1.42%   |
| C       | 5         | 1.18%   |
| sv_SE   | 4         | 0.95%   |
| en_CA   | 4         | 0.95%   |
| nb_NO   | 3         | 0.71%   |
| en_NZ   | 3         | 0.71%   |
| pt_PT   | 2         | 0.47%   |
| fr_CA   | 2         | 0.47%   |
| es_MX   | 2         | 0.47%   |
| es_CO   | 2         | 0.47%   |
| es_AR   | 2         | 0.47%   |
| en_ZA   | 2         | 0.47%   |
| en_IN   | 2         | 0.47%   |
| de_CH   | 2         | 0.47%   |
| Unknown | 2         | 0.47%   |
| ro_RO   | 1         | 0.24%   |
| hr_HR   | 1         | 0.24%   |
| fr_BE   | 1         | 0.24%   |
| fi_FI   | 1         | 0.24%   |
| es_UY   | 1         | 0.24%   |
| es_GT   | 1         | 0.24%   |
| es_CL   | 1         | 0.24%   |
| en_SG   | 1         | 0.24%   |
| en_PH   | 1         | 0.24%   |
| en_DK   | 1         | 0.24%   |
| de_AT   | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 341       | 80.61%  |
| EFI  | 82        | 19.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 409       | 96.92%  |
| Btrfs   | 10        | 2.37%   |
| Overlay | 2         | 0.47%   |
| Xfs     | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 335       | 79.01%  |
| GPT     | 82        | 19.34%  |
| MBR     | 7         | 1.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 411       | 97.39%  |
| Yes       | 11        | 2.61%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 397       | 93.85%  |
| Yes       | 26        | 6.15%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Dell                 | 81        | 19.19%  |
| Lenovo               | 71        | 16.82%  |
| ASUSTek Computer     | 52        | 12.32%  |
| Hewlett-Packard      | 50        | 11.85%  |
| Acer                 | 34        | 8.06%   |
| Apple                | 30        | 7.11%   |
| MSI                  | 20        | 4.74%   |
| Toshiba              | 13        | 3.08%   |
| System76             | 12        | 2.84%   |
| Samsung Electronics  | 8         | 1.9%    |
| HUAWEI               | 6         | 1.42%   |
| Notebook             | 4         | 0.95%   |
| GPU Company          | 4         | 0.95%   |
| Google               | 4         | 0.95%   |
| Sony                 | 3         | 0.71%   |
| Alienware            | 3         | 0.71%   |
| Timi                 | 2         | 0.47%   |
| PC Specialist        | 2         | 0.47%   |
| Medion               | 2         | 0.47%   |
| Gigabyte Technology  | 2         | 0.47%   |
| Fujitsu              | 2         | 0.47%   |
| Framework            | 2         | 0.47%   |
| TUXEDO               | 1         | 0.24%   |
| Semp Toshiba         | 1         | 0.24%   |
| Schenker             | 1         | 0.24%   |
| Razer                | 1         | 0.24%   |
| Quanta               | 1         | 0.24%   |
| Purism               | 1         | 0.24%   |
| Pegatron             | 1         | 0.24%   |
| Panasonic            | 1         | 0.24%   |
| Monster              | 1         | 0.24%   |
| LG Electronics       | 1         | 0.24%   |
| Intel Client Systems | 1         | 0.24%   |
| Eluktronics          | 1         | 0.24%   |
| Dynabook             | 1         | 0.24%   |
| A-DATA Technology    | 1         | 0.24%   |
| Unknown              | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| System76 Oryx Pro                     | 5         | 1.18%   |
| Apple MacBookAir7,2                   | 5         | 1.18%   |
| Unknown                               | 4         | 0.95%   |
| System76 Lemur Pro                    | 3         | 0.71%   |
| Lenovo IdeaPad S145-15API 81V7        | 3         | 0.71%   |
| HP Pavilion Notebook                  | 3         | 0.71%   |
| HP OMEN Laptop 15-en0xxx              | 3         | 0.71%   |
| Dell Latitude E7240                   | 3         | 0.71%   |
| Apple MacBookPro7,1                   | 3         | 0.71%   |
| System76 Pangolin                     | 2         | 0.47%   |
| Samsung 760XDA                        | 2         | 0.47%   |
| MSI Katana GF76 11UD                  | 2         | 0.47%   |
| MSI GF63 Thin 11UD                    | 2         | 0.47%   |
| Lenovo V14-IIL 82C4                   | 2         | 0.47%   |
| Lenovo ThinkPad E14 Gen 4 21ECS00000  | 2         | 0.47%   |
| Lenovo Legion 5 15IMH05H 81Y6         | 2         | 0.47%   |
| HP Pavilion 15                        | 2         | 0.47%   |
| HP Pavilion 13 x360 PC                | 2         | 0.47%   |
| HP EliteBook 855 G8 Notebook PC       | 2         | 0.47%   |
| HP EliteBook 745 G2                   | 2         | 0.47%   |
| HP 15 Notebook PC                     | 2         | 0.47%   |
| GPU Company GWTN141-10                | 2         | 0.47%   |
| GPU Company GWTC116-2                 | 2         | 0.47%   |
| Google Lulu                           | 2         | 0.47%   |
| Framework Laptop                      | 2         | 0.47%   |
| Dell XPS 15 9570                      | 2         | 0.47%   |
| Dell XPS 15 9510                      | 2         | 0.47%   |
| Dell XPS 13 9310                      | 2         | 0.47%   |
| Dell Vostro 5470                      | 2         | 0.47%   |
| Dell Vostro 5402                      | 2         | 0.47%   |
| Dell Vostro 15 3515                   | 2         | 0.47%   |
| Dell Precision M4800                  | 2         | 0.47%   |
| Dell Latitude E7470                   | 2         | 0.47%   |
| Dell Latitude E7270                   | 2         | 0.47%   |
| Dell Latitude E6540                   | 2         | 0.47%   |
| Dell Inspiron 5566                    | 2         | 0.47%   |
| Dell Inspiron 5547                    | 2         | 0.47%   |
| Dell Inspiron 3542                    | 2         | 0.47%   |
| Dell Inspiron 3442                    | 2         | 0.47%   |
| Dell Inspiron 1750                    | 2         | 0.47%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 2         | 0.47%   |
| Apple MacBookPro9,2                   | 2         | 0.47%   |
| Apple MacBookPro12,1                  | 2         | 0.47%   |
| Apple MacBookPro11,1                  | 2         | 0.47%   |
| Apple MacBookPro10,2                  | 2         | 0.47%   |
| Apple MacBookAir6,2                   | 2         | 0.47%   |
| Acer Nitro AN515-42                   | 2         | 0.47%   |
| Acer Aspire A515-45                   | 2         | 0.47%   |
| Toshiba Satellite S50-A               | 1         | 0.24%   |
| Toshiba Satellite P850                | 1         | 0.24%   |
| Toshiba Satellite L850-1D5            | 1         | 0.24%   |
| Toshiba Satellite L755                | 1         | 0.24%   |
| Toshiba Satellite L650                | 1         | 0.24%   |
| Toshiba Satellite L50D-C              | 1         | 0.24%   |
| Toshiba Satellite L10W-B-101          | 1         | 0.24%   |
| Toshiba Satellite C75D-C              | 1         | 0.24%   |
| Toshiba Satellite C650D               | 1         | 0.24%   |
| Toshiba Satellite C55t-C              | 1         | 0.24%   |
| Toshiba QOSMIO X770                   | 1         | 0.24%   |
| Toshiba PORTEGE R830                  | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 32        | 7.58%   |
| Acer Aspire            | 22        | 5.21%   |
| Dell Latitude          | 21        | 4.98%   |
| Dell Inspiron          | 21        | 4.98%   |
| Lenovo IdeaPad         | 15        | 3.55%   |
| Dell XPS               | 13        | 3.08%   |
| HP Pavilion            | 11        | 2.61%   |
| Toshiba Satellite      | 10        | 2.37%   |
| Lenovo Legion          | 10        | 2.37%   |
| Dell Vostro            | 10        | 2.37%   |
| Dell Precision         | 10        | 2.37%   |
| HP EliteBook           | 9         | 2.13%   |
| HP ProBook             | 8         | 1.9%    |
| ASUS ROG               | 8         | 1.9%    |
| HP Laptop              | 7         | 1.66%   |
| ASUS VivoBook          | 7         | 1.66%   |
| System76 Oryx          | 5         | 1.18%   |
| HP OMEN                | 5         | 1.18%   |
| Apple MacBookAir7      | 5         | 1.18%   |
| ASUS ZenBook           | 4         | 0.95%   |
| ASUS ASUS              | 4         | 0.95%   |
| Apple MacBookPro11     | 4         | 0.95%   |
| Acer Swift             | 4         | 0.95%   |
| Acer Nitro             | 4         | 0.95%   |
| Unknown                | 4         | 0.95%   |
| System76 Lemur         | 3         | 0.71%   |
| MSI Modern             | 3         | 0.71%   |
| MSI Katana             | 3         | 0.71%   |
| MSI GF63               | 3         | 0.71%   |
| Lenovo ThinkBook       | 3         | 0.71%   |
| HP ZBook               | 3         | 0.71%   |
| Apple MacBookPro9      | 3         | 0.71%   |
| Apple MacBookPro7      | 3         | 0.71%   |
| System76 Pangolin      | 2         | 0.47%   |
| Samsung 760XDA         | 2         | 0.47%   |
| MSI GS75               | 2         | 0.47%   |
| Lenovo Yoga            | 2         | 0.47%   |
| Lenovo V14-IIL         | 2         | 0.47%   |
| HP 15                  | 2         | 0.47%   |
| GPU Company GWTN141-10 | 2         | 0.47%   |
| GPU Company GWTC116-2  | 2         | 0.47%   |
| Google Lulu            | 2         | 0.47%   |
| Framework Laptop       | 2         | 0.47%   |
| Dell G7                | 2         | 0.47%   |
| Apple MacBookPro8      | 2         | 0.47%   |
| Apple MacBookPro14     | 2         | 0.47%   |
| Apple MacBookPro12     | 2         | 0.47%   |
| Apple MacBookPro10     | 2         | 0.47%   |
| Apple MacBookAir6      | 2         | 0.47%   |
| Apple MacBook5         | 2         | 0.47%   |
| Acer TravelMate        | 2         | 0.47%   |
| Toshiba QOSMIO         | 1         | 0.24%   |
| Toshiba PORTEGE        | 1         | 0.24%   |
| Toshiba BLB            | 1         | 0.24%   |
| Timi RedmiBook         | 1         | 0.24%   |
| Timi Redmi             | 1         | 0.24%   |
| System76 Galago        | 1         | 0.24%   |
| System76 Darter        | 1         | 0.24%   |
| Sony VPCF11M1E         | 1         | 0.24%   |
| Sony VPCEG27FM         | 1         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 72        | 17.06%  |
| 2020 | 57        | 13.51%  |
| 2019 | 35        | 8.29%   |
| 2013 | 32        | 7.58%   |
| 2018 | 31        | 7.35%   |
| 2016 | 30        | 7.11%   |
| 2015 | 30        | 7.11%   |
| 2014 | 23        | 5.45%   |
| 2012 | 21        | 4.98%   |
| 2017 | 20        | 4.74%   |
| 2011 | 20        | 4.74%   |
| 2022 | 18        | 4.27%   |
| 2010 | 15        | 3.55%   |
| 2009 | 14        | 3.32%   |
| 2008 | 2         | 0.47%   |
| 2007 | 2         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 422       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 422       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 409       | 96.92%  |
| Yes  | 13        | 3.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 119       | 28.2%   |
| 16.01-24.0  | 106       | 25.12%  |
| 8.01-16.0   | 89        | 21.09%  |
| 3.01-4.0    | 58        | 13.74%  |
| 32.01-64.0  | 36        | 8.53%   |
| 64.01-256.0 | 11        | 2.61%   |
| 1.01-2.0    | 2         | 0.47%   |
| 24.01-32.0  | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 164       | 37.7%   |
| 3.01-4.0   | 97        | 22.3%   |
| 4.01-8.0   | 85        | 19.54%  |
| 1.01-2.0   | 69        | 15.86%  |
| 8.01-16.0  | 17        | 3.91%   |
| 16.01-24.0 | 3         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 302       | 71.39%  |
| 2      | 106       | 25.06%  |
| 3      | 13        | 3.07%   |
| 7      | 1         | 0.24%   |
| 0      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 317       | 75.12%  |
| Yes       | 105       | 24.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 333       | 78.54%  |
| No        | 91        | 21.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 421       | 99.76%  |
| No        | 1         | 0.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 359       | 84.87%  |
| No        | 64        | 15.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| USA                   | 122       | 28.77%  |
| Brazil                | 40        | 9.43%   |
| Germany               | 30        | 7.08%   |
| India                 | 21        | 4.95%   |
| Australia             | 17        | 4.01%   |
| Canada                | 15        | 3.54%   |
| UK                    | 14        | 3.3%    |
| France                | 14        | 3.3%    |
| Italy                 | 10        | 2.36%   |
| Russia                | 9         | 2.12%   |
| Norway                | 9         | 2.12%   |
| Mexico                | 7         | 1.65%   |
| Sweden                | 6         | 1.42%   |
| Poland                | 6         | 1.42%   |
| New Zealand           | 5         | 1.18%   |
| Argentina             | 5         | 1.18%   |
| Turkey                | 4         | 0.94%   |
| Switzerland           | 4         | 0.94%   |
| Spain                 | 4         | 0.94%   |
| Romania               | 4         | 0.94%   |
| Greece                | 4         | 0.94%   |
| Finland               | 4         | 0.94%   |
| Colombia              | 4         | 0.94%   |
| Belgium               | 4         | 0.94%   |
| Philippines           | 3         | 0.71%   |
| Netherlands           | 3         | 0.71%   |
| Morocco               | 3         | 0.71%   |
| Venezuela             | 2         | 0.47%   |
| Thailand              | 2         | 0.47%   |
| South Africa          | 2         | 0.47%   |
| Singapore             | 2         | 0.47%   |
| Portugal              | 2         | 0.47%   |
| Peru                  | 2         | 0.47%   |
| Panama                | 2         | 0.47%   |
| Malaysia              | 2         | 0.47%   |
| Hungary               | 2         | 0.47%   |
| Hong Kong             | 2         | 0.47%   |
| Georgia               | 2         | 0.47%   |
| Egypt                 | 2         | 0.47%   |
| Croatia               | 2         | 0.47%   |
| Chile                 | 2         | 0.47%   |
| Bulgaria              | 2         | 0.47%   |
| Austria               | 2         | 0.47%   |
| Vietnam               | 1         | 0.24%   |
| Uzbekistan            | 1         | 0.24%   |
| Uruguay               | 1         | 0.24%   |
| Tunisia               | 1         | 0.24%   |
| Slovenia              | 1         | 0.24%   |
| Saudi Arabia          | 1         | 0.24%   |
| Republic of the Congo | 1         | 0.24%   |
| Pakistan              | 1         | 0.24%   |
| Maldives              | 1         | 0.24%   |
| Latvia                | 1         | 0.24%   |
| Kosovo                | 1         | 0.24%   |
| Japan                 | 1         | 0.24%   |
| Ireland               | 1         | 0.24%   |
| Iraq                  | 1         | 0.24%   |
| Iran                  | 1         | 0.24%   |
| Indonesia             | 1         | 0.24%   |
| Guatemala             | 1         | 0.24%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Oslo           | 6         | 1.4%    |
| Melbourne      | 5         | 1.16%   |
| Sydney         | 4         | 0.93%   |
| Munich         | 4         | 0.93%   |
| Mumbai         | 4         | 0.93%   |
| Brisbane       | 4         | 0.93%   |
| Zurich         | 3         | 0.7%    |
| Warsaw         | 3         | 0.7%    |
| Sao Paulo      | 3         | 0.7%    |
| Rio de Janeiro | 3         | 0.7%    |
| Mannheim       | 3         | 0.7%    |
| Istanbul       | 3         | 0.7%    |
| Helsinki       | 3         | 0.7%    |
| Durham         | 3         | 0.7%    |
| Berlin         | 3         | 0.7%    |
| Bengaluru      | 3         | 0.7%    |
| Auckland       | 3         | 0.7%    |
| Turin          | 2         | 0.47%   |
| Toronto        | 2         | 0.47%   |
| Tallahassee    | 2         | 0.47%   |
| Stockholm      | 2         | 0.47%   |
| Singapore      | 2         | 0.47%   |
| San Jose       | 2         | 0.47%   |
| Riverview      | 2         | 0.47%   |
| Quezon City    | 2         | 0.47%   |
| Portland       | 2         | 0.47%   |
| Paris          | 2         | 0.47%   |
| Panama City    | 2         | 0.47%   |
| Ottawa         | 2         | 0.47%   |
| Moscow         | 2         | 0.47%   |
| Minneapolis    | 2         | 0.47%   |
| Mendoza        | 2         | 0.47%   |
| Manaus         | 2         | 0.47%   |
| Lansing        | 2         | 0.47%   |
| Itatiba        | 2         | 0.47%   |
| Heraklion      | 2         | 0.47%   |
| Guwahati       | 2         | 0.47%   |
| Gatineau       | 2         | 0.47%   |
| Denver         | 2         | 0.47%   |
| Coimbatore     | 2         | 0.47%   |
| Catunda        | 2         | 0.47%   |
| Budapest       | 2         | 0.47%   |
| Bucharest      | 2         | 0.47%   |
| Boise          | 2         | 0.47%   |
| Birmingham     | 2         | 0.47%   |
| Bamberg        | 2         | 0.47%   |
| Zagreb         | 1         | 0.23%   |
| Zagazig        | 1         | 0.23%   |
| Yogyakarta     | 1         | 0.23%   |
| Wuppertal      | 1         | 0.23%   |
| Winnipeg       | 1         | 0.23%   |
| Windsor        | 1         | 0.23%   |
| Wilmington     | 1         | 0.23%   |
| Wesley Chapel  | 1         | 0.23%   |
| Waxhaw         | 1         | 0.23%   |
| Vitória       | 1         | 0.23%   |
| Visakhapatnam  | 1         | 0.23%   |
| Virginia Beach | 1         | 0.23%   |
| Viña del Mar  | 1         | 0.23%   |
| Vila Velha     | 1         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 99        | 114    | 18.47%  |
| SanDisk                        | 47        | 55     | 8.77%   |
| WDC                            | 45        | 49     | 8.4%    |
| Kingston                       | 39        | 43     | 7.28%   |
| Toshiba                        | 35        | 41     | 6.53%   |
| Seagate                        | 34        | 37     | 6.34%   |
| SK hynix                       | 29        | 30     | 5.41%   |
| Unknown                        | 17        | 19     | 3.17%   |
| HGST                           | 17        | 17     | 3.17%   |
| Crucial                        | 17        | 17     | 3.17%   |
| Apple                          | 16        | 18     | 2.99%   |
| Micron Technology              | 13        | 13     | 2.43%   |
| Phison                         | 12        | 13     | 2.24%   |
| Intel                          | 12        | 13     | 2.24%   |
| Hitachi                        | 8         | 9      | 1.49%   |
| PNY                            | 7         | 8      | 1.31%   |
| A-DATA Technology              | 7         | 8      | 1.31%   |
| LITEONIT                       | 5         | 5      | 0.93%   |
| KIOXIA                         | 5         | 5      | 0.93%   |
| Union Memory (Shenzhen)        | 4         | 5      | 0.75%   |
| Silicon Motion                 | 4         | 4      | 0.75%   |
| LITEON                         | 4         | 4      | 0.75%   |
| Intenso                        | 4         | 4      | 0.75%   |
| ADATA Technology               | 4         | 4      | 0.75%   |
| MyDigitalSSD                   | 3         | 3      | 0.56%   |
| KingSpec                       | 3         | 3      | 0.56%   |
| China                          | 3         | 3      | 0.56%   |
| W800S                          | 2         | 3      | 0.37%   |
| Team                           | 2         | 2      | 0.37%   |
| SSSTC                          | 2         | 2      | 0.37%   |
| SPCC                           | 2         | 2      | 0.37%   |
| Solid State Storage Technology | 2         | 2      | 0.37%   |
| Micron/Crucial Technology      | 2         | 2      | 0.37%   |
| MAXIO Technology (Hangzhou)    | 2         | 2      | 0.37%   |
| Lexar                          | 2         | 2      | 0.37%   |
| YMTC                           | 1         | 1      | 0.19%   |
| USB3.0                         | 1         | 1      | 0.19%   |
| TwinMOS                        | 1         | 1      | 0.19%   |
| T-FORCE                        | 1         | 1      | 0.19%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.19%   |
| SATAFIRM                       | 1         | 1      | 0.19%   |
| ROG                            | 1         | 1      | 0.19%   |
| Ramaxel Technology             | 1         | 1      | 0.19%   |
| Radeon                         | 1         | 1      | 0.19%   |
| PUSKILL                        | 1         | 1      | 0.19%   |
| PNY USB                        | 1         | 1      | 0.19%   |
| Patriot                        | 1         | 1      | 0.19%   |
| OWC                            | 1         | 1      | 0.19%   |
| OEM                            | 1         | 1      | 0.19%   |
| Netac                          | 1         | 1      | 0.19%   |
| Lite-On                        | 1         | 1      | 0.19%   |
| Leven                          | 1         | 1      | 0.19%   |
| KingFast                       | 1         | 2      | 0.19%   |
| KingDian                       | 1         | 1      | 0.19%   |
| KINGBANK                       | 1         | 1      | 0.19%   |
| Inland                         | 1         | 1      | 0.19%   |
| HGST HDN                       | 1         | 1      | 0.19%   |
| Fujitsu                        | 1         | 1      | 0.19%   |
| BHT                            | 1         | 1      | 0.19%   |
| Apacer                         | 1         | 3      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD              | 12        | 2.16%   |
| SK hynix NVMe SSD Drive 512GB                | 9         | 1.62%   |
| Samsung NVMe SSD Drive 512GB                 | 9         | 1.62%   |
| SanDisk NVMe SSD Drive 1TB                   | 8         | 1.44%   |
| SanDisk NVMe SSD Drive 512GB                 | 7         | 1.26%   |
| Samsung NVMe SSD Drive 1024GB                | 7         | 1.26%   |
| Kingston NVMe SSD Drive 512GB                | 7         | 1.26%   |
| HGST HTS721010A9E630 1TB                     | 7         | 1.26%   |
| SK hynix NVMe SSD Drive 1024GB               | 6         | 1.08%   |
| Samsung NVMe SSD Drive 500GB                 | 6         | 1.08%   |
| Samsung NVMe SSD Drive 2TB                   | 6         | 1.08%   |
| Kingston SA400S37120G 120GB SSD              | 6         | 1.08%   |
| Toshiba MQ04ABF100 1TB                       | 5         | 0.9%    |
| SanDisk NVMe SSD Drive 256GB                 | 5         | 0.9%    |
| Samsung NVMe SSD Drive 256GB                 | 5         | 0.9%    |
| Toshiba MQ01ACF050 500GB                     | 4         | 0.72%   |
| SK hynix NVMe SSD Drive 256GB                | 4         | 0.72%   |
| Seagate ST2000LM007-1R8174 2TB               | 4         | 0.72%   |
| Seagate ST1000LM049-2GH172 1TB               | 4         | 0.72%   |
| Samsung SSD 850 EVO 500GB                    | 4         | 0.72%   |
| Samsung NVMe SSD Drive 1TB                   | 4         | 0.72%   |
| Apple SSD SM0512G 500GB                      | 4         | 0.72%   |
| Apple SSD SM0128G 121GB                      | 4         | 0.72%   |
| ADATA NVMe SSD Drive 256GB                   | 4         | 0.72%   |
| WDC WD10SPZX-24Z10 1TB                       | 3         | 0.54%   |
| Unknown MMC Card  64GB                       | 3         | 0.54%   |
| Unknown MMC Card  32GB                       | 3         | 0.54%   |
| Unknown MMC Card  128GB                      | 3         | 0.54%   |
| Toshiba MQ01ABD100 1TB                       | 3         | 0.54%   |
| Toshiba MQ01ABD075 752GB                     | 3         | 0.54%   |
| Seagate ST9320325AS 320GB                    | 3         | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 3         | 0.54%   |
| SanDisk NVMe SSD Drive 500GB                 | 3         | 0.54%   |
| Samsung SSD 860 QVO 1TB                      | 3         | 0.54%   |
| PNY ELITE PSSD 480GB                         | 3         | 0.54%   |
| PNY CS900 240GB SSD                          | 3         | 0.54%   |
| Phison NVMe SSD Drive 256GB                  | 3         | 0.54%   |
| Micron NVMe SSD Drive 512GB                  | 3         | 0.54%   |
| Kingston SA400S37480G 480GB SSD              | 3         | 0.54%   |
| Intel NVMe SSD Drive 512GB                   | 3         | 0.54%   |
| Intel NVMe SSD Drive 256GB                   | 3         | 0.54%   |
| Intel NVMe SSD Drive 1024GB                  | 3         | 0.54%   |
| HGST HTS725050A7E630 500GB                   | 3         | 0.54%   |
| Crucial CT240BX500SSD1 240GB                 | 3         | 0.54%   |
| Crucial CT1000MX500SSD1 1TB                  | 3         | 0.54%   |
| WDC WD5000LPVX-75V0TT0 500GB                 | 2         | 0.36%   |
| WDC WD5000LPCX-60VHAT0 500GB                 | 2         | 0.36%   |
| WDC WD10SPZX-21Z10T0 1TB                     | 2         | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 2         | 0.36%   |
| W800S 512GB                                  | 2         | 0.36%   |
| Unknown MMC Card  16GB                       | 2         | 0.36%   |
| Union Memory (Shenzhen) NVMe SSD Drive 512GB | 2         | 0.36%   |
| Union Memory (Shenzhen) NVMe SSD Drive 256GB | 2         | 0.36%   |
| Toshiba NVMe SSD Drive 512GB                 | 2         | 0.36%   |
| SPCC Solid State Disk 512GB                  | 2         | 0.36%   |
| SK hynix NVMe SSD Drive 128GB                | 2         | 0.36%   |
| Seagate ST500LM030-2E717D 500GB              | 2         | 0.36%   |
| Seagate ST2000LX001-1RG174 2TB               | 2         | 0.36%   |
| Seagate ST1000LM048-2E7172 1TB               | 2         | 0.36%   |
| Seagate ST1000LM035-1RK172 1TB               | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 37     | 28.57%  |
| WDC                 | 28        | 32     | 23.53%  |
| Toshiba             | 25        | 29     | 21.01%  |
| HGST                | 17        | 17     | 14.29%  |
| Hitachi             | 8         | 9      | 6.72%   |
| Samsung Electronics | 2         | 2      | 1.68%   |
| SATAFIRM            | 1         | 1      | 0.84%   |
| Intenso             | 1         | 1      | 0.84%   |
| HGST HDN            | 1         | 1      | 0.84%   |
| Fujitsu             | 1         | 1      | 0.84%   |
| Apple               | 1         | 1      | 0.84%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 38     | 20.77%  |
| Kingston            | 28        | 29     | 15.3%   |
| SanDisk             | 23        | 25     | 12.57%  |
| Crucial             | 13        | 13     | 7.1%    |
| Apple               | 13        | 14     | 7.1%    |
| WDC                 | 7         | 7      | 3.83%   |
| PNY                 | 7         | 8      | 3.83%   |
| LITEONIT            | 5         | 5      | 2.73%   |
| LITEON              | 4         | 4      | 2.19%   |
| A-DATA Technology   | 4         | 5      | 2.19%   |
| MyDigitalSSD        | 3         | 3      | 1.64%   |
| Micron Technology   | 3         | 3      | 1.64%   |
| KingSpec            | 3         | 3      | 1.64%   |
| China               | 3         | 3      | 1.64%   |
| Toshiba             | 2         | 2      | 1.09%   |
| SPCC                | 2         | 2      | 1.09%   |
| SK hynix            | 2         | 2      | 1.09%   |
| Intenso             | 2         | 2      | 1.09%   |
| W800S               | 1         | 1      | 0.55%   |
| USB3.0              | 1         | 1      | 0.55%   |
| TwinMOS             | 1         | 1      | 0.55%   |
| Ramaxel Technology  | 1         | 1      | 0.55%   |
| Radeon              | 1         | 1      | 0.55%   |
| PUSKILL             | 1         | 1      | 0.55%   |
| PNY USB             | 1         | 1      | 0.55%   |
| Phison              | 1         | 1      | 0.55%   |
| Patriot             | 1         | 1      | 0.55%   |
| OWC                 | 1         | 1      | 0.55%   |
| Lexar               | 1         | 1      | 0.55%   |
| Leven               | 1         | 1      | 0.55%   |
| KingFast            | 1         | 1      | 0.55%   |
| KingDian            | 1         | 1      | 0.55%   |
| KINGBANK            | 1         | 1      | 0.55%   |
| Intel               | 1         | 1      | 0.55%   |
| Inland              | 1         | 1      | 0.55%   |
| BHT                 | 1         | 1      | 0.55%   |
| Apacer              | 1         | 3      | 0.55%   |
| AFOX                | 1         | 1      | 0.55%   |
| Aarvex              | 1         | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 195       | 243    | 38.84%  |
| SSD     | 169       | 191    | 33.67%  |
| HDD     | 115       | 131    | 22.91%  |
| MMC     | 16        | 18     | 3.19%   |
| Unknown | 7         | 8      | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 255       | 314    | 52.8%   |
| NVMe | 195       | 242    | 40.37%  |
| SAS  | 17        | 17     | 3.52%   |
| MMC  | 16        | 18     | 3.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 185       | 217    | 66.55%  |
| 0.51-1.0   | 80        | 91     | 28.78%  |
| 1.01-2.0   | 12        | 13     | 4.32%   |
| 4.01-10.0  | 1         | 1      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 151       | 35.61%  |
| 251-500        | 124       | 29.25%  |
| 501-1000       | 82        | 19.34%  |
| 1001-2000      | 23        | 5.42%   |
| 51-100         | 15        | 3.54%   |
| 21-50          | 13        | 3.07%   |
| 2001-3000      | 6         | 1.42%   |
| 1-20           | 5         | 1.18%   |
| More than 3000 | 3         | 0.71%   |
| Unknown        | 2         | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 150       | 34.72%  |
| 21-50     | 116       | 26.85%  |
| 101-250   | 63        | 14.58%  |
| 51-100    | 50        | 11.57%  |
| 251-500   | 30        | 6.94%   |
| 501-1000  | 16        | 3.7%    |
| 1001-2000 | 5         | 1.16%   |
| Unknown   | 2         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ACF050 500GB           | 1         | 1      | 9.09%   |
| SK hynix PC711 HFS001TDE9X073N 1TB | 1         | 1      | 9.09%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 9.09%   |
| Seagate ST500LM030-2E717D 500GB    | 1         | 1      | 9.09%   |
| Seagate ST1000LX015-1U7172 1TB     | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 9.09%   |
| Lexar 1TB SSD                      | 1         | 1      | 9.09%   |
| Leven JAJS600M256C 256GB SSD       | 1         | 1      | 9.09%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 2      | 9.09%   |
| HGST HTS725050A7E630 500GB         | 1         | 1      | 9.09%   |
| HGST HTS721010A9E630 1TB           | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 4      | 36.36%  |
| HGST     | 2         | 2      | 18.18%  |
| Toshiba  | 1         | 1      | 9.09%   |
| SK hynix | 1         | 1      | 9.09%   |
| Lexar    | 1         | 1      | 9.09%   |
| Leven    | 1         | 1      | 9.09%   |
| Hitachi  | 1         | 2      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| HGST    | 2         | 2      | 25%     |
| Toshiba | 1         | 1      | 12.5%   |
| Hitachi | 1         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 72.73%  |
| NVMe | 2         | 2      | 18.18%  |
| SSD  | 1         | 1      | 9.09%   |

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
| Detected | 341       | 465    | 76.8%   |
| Works    | 92        | 114    | 20.72%  |
| Malfunc  | 11        | 12     | 2.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 256       | 47.41%  |
| Samsung Electronics            | 71        | 13.15%  |
| AMD                            | 62        | 11.48%  |
| SanDisk                        | 32        | 5.93%   |
| SK hynix                       | 27        | 5%      |
| Phison Electronics             | 11        | 2.04%   |
| Micron Technology              | 10        | 1.85%   |
| Kingston Technology Company    | 10        | 1.85%   |
| Toshiba America Info Systems   | 9         | 1.67%   |
| Nvidia                         | 9         | 1.67%   |
| Micron/Crucial Technology      | 6         | 1.11%   |
| ADATA Technology               | 6         | 1.11%   |
| Silicon Motion                 | 5         | 0.93%   |
| KIOXIA                         | 5         | 0.93%   |
| Union Memory (Shenzhen)        | 4         | 0.74%   |
| Solid State Storage Technology | 4         | 0.74%   |
| Shenzhen Longsys Electronics   | 3         | 0.56%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.37%   |
| Marvell Technology Group       | 2         | 0.37%   |
| Apple                          | 2         | 0.37%   |
| Yangtze Memory Technologies    | 1         | 0.19%   |
| Unknown                        | 1         | 0.19%   |
| Realtek Semiconductor          | 1         | 0.19%   |
| Lite-On Technology             | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 58        | 10.3%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 34        | 6.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 26        | 4.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 25        | 4.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 24        | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 22        | 3.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 19        | 3.37%   |
| SK hynix Gold P31 SSD                                                            | 18        | 3.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 2.31%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 2.31%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 13        | 2.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 13        | 2.31%   |
| Samsung NVMe SSD Controller 980                                                  | 12        | 2.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 11        | 1.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 11        | 1.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 1.95%   |
| Micron Non-Volatile memory controller                                            | 10        | 1.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 10        | 1.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 8         | 1.42%   |
| Samsung Electronics SATA controller                                              | 8         | 1.42%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 1.24%   |
| Intel SSD 660P Series                                                            | 6         | 1.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 1.07%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 5         | 0.89%   |
| SK hynix Non-Volatile memory controller                                          | 5         | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 5         | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 0.89%   |
| Phison E12 NVMe Controller                                                       | 5         | 0.89%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 0.89%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 5         | 0.89%   |
| Kingston Company Company Non-Volatile memory controller                          | 5         | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 0.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 0.89%   |
| ADATA Non-Volatile memory controller                                             | 5         | 0.89%   |
| Solid State Storage Non-Volatile memory controller                               | 4         | 0.71%   |
| SanDisk Non-Volatile memory controller                                           | 4         | 0.71%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 4         | 0.71%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 0.71%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 4         | 0.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 0.71%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.71%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 3         | 0.53%   |
| Phison PS5013 E13 NVMe Controller                                                | 3         | 0.53%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 3         | 0.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.53%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.36%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                    | 2         | 0.36%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.36%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.36%   |
| SK hynix BC511                                                                   | 2         | 0.36%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.36%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                      | 2         | 0.36%   |
| SanDisk WD Blue SN570 NVMe SSD                                                   | 2         | 0.36%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.36%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 0.36%   |
| Samsung Apple PCIe SSD                                                           | 2         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 289       | 53.72%  |
| NVMe | 195       | 36.25%  |
| RAID | 40        | 7.43%   |
| IDE  | 14        | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 324       | 76.78%  |
| AMD    | 98        | 23.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 15        | 3.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 2.37%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 1.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 1.66%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 1.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.42%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 1.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.18%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 1.18%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.18%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 1.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.18%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 1.18%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.18%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.95%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 4         | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.95%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.95%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 0.95%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.95%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.95%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 0.95%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 0.95%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 4         | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.71%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 0.71%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.71%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.71%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 3         | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.71%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 0.71%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.71%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.71%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 3         | 0.71%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.71%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.71%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 3         | 0.71%   |
| AMD A6-7310 APU with AMD Radeon R4 Graphics   | 3         | 0.71%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.47%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.47%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.47%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.47%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.47%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.47%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.47%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 2         | 0.47%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.47%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.47%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.47%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.47%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.47%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 0.47%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 114       | 27.01%  |
| Intel Core i5           | 95        | 22.51%  |
| Other                   | 49        | 11.61%  |
| AMD Ryzen 7             | 28        | 6.64%   |
| Intel Core i3           | 27        | 6.4%    |
| AMD Ryzen 5             | 26        | 6.16%   |
| Intel Core 2 Duo        | 15        | 3.55%   |
| Intel Celeron           | 11        | 2.61%   |
| AMD Ryzen 9             | 7         | 1.66%   |
| Intel Pentium           | 6         | 1.42%   |
| AMD A8                  | 6         | 1.42%   |
| AMD A6                  | 6         | 1.42%   |
| AMD Ryzen 7 PRO         | 5         | 1.18%   |
| AMD A10                 | 5         | 1.18%   |
| Intel Core i9           | 4         | 0.95%   |
| AMD Ryzen 3             | 4         | 0.95%   |
| Intel Pentium Dual-Core | 2         | 0.47%   |
| AMD Ryzen 5 PRO         | 2         | 0.47%   |
| AMD Athlon              | 2         | 0.47%   |
| Intel Xeon              | 1         | 0.24%   |
| Intel Core m3           | 1         | 0.24%   |
| Intel Atom              | 1         | 0.24%   |
| AMD Turion 64 X2 Mobile | 1         | 0.24%   |
| AMD Phenom II           | 1         | 0.24%   |
| AMD E2                  | 1         | 0.24%   |
| AMD E                   | 1         | 0.24%   |
| AMD Athlon X2           | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 170       | 40.28%  |
| 4      | 139       | 32.94%  |
| 8      | 61        | 14.45%  |
| 6      | 44        | 10.43%  |
| 14     | 3         | 0.71%   |
| 12     | 3         | 0.71%   |
| 1      | 2         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 422       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 361       | 85.55%  |
| 1      | 61        | 14.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 422       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 322       | 76.12%  |
| 0x0a50000c | 10        | 2.36%   |
| 0x806d1    | 9         | 2.13%   |
| 0x806c1    | 7         | 1.65%   |
| 0x806ec    | 6         | 1.42%   |
| 0x306a9    | 5         | 1.18%   |
| 0x906ea    | 4         | 0.95%   |
| 0x406e3    | 4         | 0.95%   |
| 0x40651    | 4         | 0.95%   |
| 0x306c3    | 4         | 0.95%   |
| 0x08600106 | 4         | 0.95%   |
| 0xa0652    | 3         | 0.71%   |
| 0x806ea    | 3         | 0.71%   |
| 0x806e9    | 3         | 0.71%   |
| 0x706e5    | 3         | 0.71%   |
| 0x506e3    | 3         | 0.71%   |
| 0x08608103 | 3         | 0.71%   |
| 0x08108109 | 3         | 0.71%   |
| 0x906e9    | 2         | 0.47%   |
| 0x906a3    | 2         | 0.47%   |
| 0x806eb    | 2         | 0.47%   |
| 0x806c2    | 2         | 0.47%   |
| 0x306d4    | 2         | 0.47%   |
| 0x0a404101 | 2         | 0.47%   |
| 0x08600104 | 2         | 0.47%   |
| 0x08600103 | 2         | 0.47%   |
| 0x0810100b | 2         | 0.47%   |
| 0xa0660    | 1         | 0.24%   |
| 0x30678    | 1         | 0.24%   |
| 0x1067a    | 1         | 0.24%   |
| 0x07030105 | 1         | 0.24%   |
| 0x06006705 | 1         | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 73        | 17.3%   |
| Haswell          | 44        | 10.43%  |
| Unknown          | 31        | 7.35%   |
| SandyBridge      | 27        | 6.4%    |
| Zen 3            | 26        | 6.16%   |
| Skylake          | 25        | 5.92%   |
| IvyBridge        | 23        | 5.45%   |
| TigerLake        | 22        | 5.21%   |
| Broadwell        | 21        | 4.98%   |
| CometLake        | 19        | 4.5%    |
| Zen 2            | 16        | 3.79%   |
| Penryn           | 16        | 3.79%   |
| IceLake          | 15        | 3.55%   |
| Zen+             | 14        | 3.32%   |
| Westmere         | 9         | 2.13%   |
| Silvermont       | 7         | 1.66%   |
| Puma             | 7         | 1.66%   |
| Excavator        | 6         | 1.42%   |
| Zen              | 3         | 0.71%   |
| Piledriver       | 3         | 0.71%   |
| Goldmont plus    | 3         | 0.71%   |
| Steamroller      | 2         | 0.47%   |
| K8 Hammer        | 2         | 0.47%   |
| K10 Llano        | 2         | 0.47%   |
| Nehalem          | 1         | 0.24%   |
| K10              | 1         | 0.24%   |
| Goldmont         | 1         | 0.24%   |
| Core             | 1         | 0.24%   |
| Bobcat           | 1         | 0.24%   |
| Alderlake Hybrid | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 291       | 51.96%  |
| Nvidia | 157       | 28.04%  |
| AMD    | 112       | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 26        | 4.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 4.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 22        | 3.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 3.66%   |
| AMD Cezanne                                                                              | 21        | 3.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 16        | 2.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 2.79%   |
| AMD Renoir                                                                               | 16        | 2.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 2.62%   |
| Intel HD Graphics 5500                                                                   | 14        | 2.44%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 2.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 2.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 2.27%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 12        | 2.09%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 2.09%   |
| Intel UHD Graphics 620                                                                   | 12        | 2.09%   |
| Intel HD Graphics 620                                                                    | 12        | 2.09%   |
| AMD Lucienne                                                                             | 12        | 2.09%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 10        | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.57%   |
| Intel HD Graphics 630                                                                    | 8         | 1.4%    |
| Intel HD Graphics 530                                                                    | 8         | 1.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.22%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 1.22%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 1.05%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 1.05%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 6         | 1.05%   |
| Nvidia TU117M                                                                            | 5         | 0.87%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.87%   |
| Intel HD Graphics 6000                                                                   | 5         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.7%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.7%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.52%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 3         | 0.52%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 0.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.52%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.52%   |
| Nvidia GM108M [GeForce 940M]                                                             | 3         | 0.52%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.52%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 0.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.52%   |
| AMD Barcelo                                                                              | 3         | 0.52%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 0.52%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.35%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 0.35%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 2         | 0.35%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 2         | 0.35%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 2         | 0.35%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 2         | 0.35%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.35%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 2         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 177       | 41.84%  |
| Intel + Nvidia | 103       | 24.35%  |
| 1 x AMD        | 67        | 15.84%  |
| 1 x Nvidia     | 30        | 7.09%   |
| AMD + Nvidia   | 23        | 5.44%   |
| 2 x AMD        | 11        | 2.6%    |
| Intel + AMD    | 11        | 2.6%    |
| 2 x Nvidia     | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 290       | 68.4%   |
| Proprietary | 127       | 29.95%  |
| Unknown     | 7         | 1.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 357       | 83.8%   |
| 3.01-4.0   | 15        | 3.52%   |
| 1.01-2.0   | 14        | 3.29%   |
| 7.01-8.0   | 13        | 3.05%   |
| 0.01-0.5   | 12        | 2.82%   |
| 5.01-6.0   | 9         | 2.11%   |
| 0.51-1.0   | 3         | 0.7%    |
| 8.01-16.0  | 2         | 0.47%   |
| 2.01-3.0   | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 91        | 18.65%  |
| BOE                     | 81        | 16.6%   |
| LG Display              | 76        | 15.57%  |
| Chimei Innolux          | 66        | 13.52%  |
| Samsung Electronics     | 39        | 7.99%   |
| Apple                   | 26        | 5.33%   |
| Dell                    | 18        | 3.69%   |
| Sharp                   | 17        | 3.48%   |
| Goldstar                | 13        | 2.66%   |
| PANDA                   | 11        | 2.25%   |
| AOC                     | 5         | 1.02%   |
| Lenovo                  | 4         | 0.82%   |
| Philips                 | 3         | 0.61%   |
| InfoVision              | 3         | 0.61%   |
| CSO                     | 3         | 0.61%   |
| Chi Mei Optoelectronics | 3         | 0.61%   |
| ASUSTek Computer        | 3         | 0.61%   |
| Acer                    | 3         | 0.61%   |
| TMX                     | 2         | 0.41%   |
| JDI                     | 2         | 0.41%   |
| Iiyama                  | 2         | 0.41%   |
| Hewlett-Packard         | 2         | 0.41%   |
| Vizio                   | 1         | 0.2%    |
| ViewSonic               | 1         | 0.2%    |
| Toshiba                 | 1         | 0.2%    |
| TCL                     | 1         | 0.2%    |
| Sony                    | 1         | 0.2%    |
| SGT                     | 1         | 0.2%    |
| Sceptre Tech            | 1         | 0.2%    |
| ONN                     | 1         | 0.2%    |
| MSI                     | 1         | 0.2%    |
| LG Electronics          | 1         | 0.2%    |
| KDC                     | 1         | 0.2%    |
| JXC                     | 1         | 0.2%    |
| Hitachi                 | 1         | 0.2%    |
| Eizo                    | 1         | 0.2%    |
| Unknown                 | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 6         | 1.22%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 6         | 1.22%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                 | 4         | 0.81%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 4         | 0.81%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 4         | 0.81%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 4         | 0.81%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 4         | 0.81%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 3         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 3         | 0.61%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 3         | 0.61%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.61%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 3         | 0.61%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.61%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.61%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 2         | 0.41%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.41%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 293x165mm 13.2-inch | 2         | 0.41%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 2         | 0.41%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.41%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 2         | 0.41%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.41%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch           | 2         | 0.41%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 2         | 0.41%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 0.41%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14E3 1366x768 309x173mm 13.9-inch       | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 0.41%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                 | 2         | 0.41%   |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                 | 2         | 0.41%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 2         | 0.41%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 0.41%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                 | 2         | 0.41%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 0.41%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                 | 2         | 0.41%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                  | 2         | 0.41%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 0.41%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                  | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO4999 1920x1080 344x193mm 15.5-inch        | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch         | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO048E 1920x1080 344x193mm 15.5-inch        | 2         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 221       | 47.22%  |
| 1366x768 (WXGA)    | 115       | 24.57%  |
| 1600x900 (HD+)     | 25        | 5.34%   |
| 3840x2160 (4K)     | 16        | 3.42%   |
| 2560x1440 (QHD)    | 15        | 3.21%   |
| 1440x900 (WXGA+)   | 12        | 2.56%   |
| 2560x1600          | 11        | 2.35%   |
| 1920x1200 (WUXGA)  | 11        | 2.35%   |
| 1280x800 (WXGA)    | 9         | 1.92%   |
| 2880x1800          | 6         | 1.28%   |
| 3440x1440          | 5         | 1.07%   |
| 3840x2400          | 2         | 0.43%   |
| 3000x2000          | 2         | 0.43%   |
| 2560x1080          | 2         | 0.43%   |
| 2256x1504          | 2         | 0.43%   |
| 3840x1200          | 1         | 0.21%   |
| 3840x1100          | 1         | 0.21%   |
| 3840x1080          | 1         | 0.21%   |
| 3456x2160          | 1         | 0.21%   |
| 3200x2000          | 1         | 0.21%   |
| 3200x1800 (QHD+)   | 1         | 0.21%   |
| 2160x1440          | 1         | 0.21%   |
| 1920x1280          | 1         | 0.21%   |
| 1680x1050 (WSXGA+) | 1         | 0.21%   |
| 1360x768           | 1         | 0.21%   |
| 1280x720 (HD)      | 1         | 0.21%   |
| 1280x1080          | 1         | 0.21%   |
| 1280x1024 (SXGA)   | 1         | 0.21%   |
| Unknown            | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 199       | 40.95%  |
| 13      | 86        | 17.7%   |
| 14      | 55        | 11.32%  |
| 17      | 39        | 8.02%   |
| 12      | 16        | 3.29%   |
| 27      | 13        | 2.67%   |
| 24      | 13        | 2.67%   |
| 23      | 11        | 2.26%   |
| 31      | 9         | 1.85%   |
| 16      | 8         | 1.65%   |
| 11      | 8         | 1.65%   |
| 34      | 5         | 1.03%   |
| 21      | 5         | 1.03%   |
| 32      | 3         | 0.62%   |
| 18      | 3         | 0.62%   |
| 22      | 2         | 0.41%   |
| 20      | 2         | 0.41%   |
| 84      | 1         | 0.21%   |
| 72      | 1         | 0.21%   |
| 49      | 1         | 0.21%   |
| 48      | 1         | 0.21%   |
| 43      | 1         | 0.21%   |
| 35      | 1         | 0.21%   |
| 28      | 1         | 0.21%   |
| 19      | 1         | 0.21%   |
| Unknown | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 298       | 61.44%  |
| 201-300     | 67        | 13.81%  |
| 351-400     | 45        | 9.28%   |
| 501-600     | 34        | 7.01%   |
| 601-700     | 13        | 2.68%   |
| 401-500     | 13        | 2.68%   |
| 701-800     | 8         | 1.65%   |
| 1001-1500   | 3         | 0.62%   |
| 1501-2000   | 2         | 0.41%   |
| 801-900     | 1         | 0.21%   |
| Unknown     | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 365       | 82.95%  |
| 16/10   | 56        | 12.73%  |
| 3/2     | 7         | 1.59%   |
| 21/9    | 7         | 1.59%   |
| 5/4     | 1         | 0.23%   |
| 32/9    | 1         | 0.23%   |
| 3.40    | 1         | 0.23%   |
| 3.20    | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 202       | 41.65%  |
| 81-90          | 112       | 23.09%  |
| 121-130        | 39        | 8.04%   |
| 71-80          | 28        | 5.77%   |
| 201-250        | 25        | 5.15%   |
| 351-500        | 17        | 3.51%   |
| 61-70          | 15        | 3.09%   |
| 301-350        | 13        | 2.68%   |
| 51-60          | 9         | 1.86%   |
| 251-300        | 6         | 1.24%   |
| 151-200        | 5         | 1.03%   |
| 111-120        | 4         | 0.82%   |
| More than 1000 | 3         | 0.62%   |
| 141-150        | 3         | 0.62%   |
| 501-1000       | 2         | 0.41%   |
| 91-100         | 1         | 0.21%   |
| Unknown        | 1         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 231       | 48.02%  |
| 101-120       | 127       | 26.4%   |
| 51-100        | 60        | 12.47%  |
| 161-240       | 39        | 8.11%   |
| More than 240 | 19        | 3.95%   |
| 1-50          | 4         | 0.83%   |
| Unknown       | 1         | 0.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 343       | 80.52%  |
| 2     | 67        | 15.73%  |
| 0     | 9         | 2.11%   |
| 3     | 7         | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 234       | 34.56%  |
| Intel                                 | 207       | 30.58%  |
| Qualcomm Atheros                      | 103       | 15.21%  |
| Broadcom                              | 40        | 5.91%   |
| MediaTek                              | 20        | 2.95%   |
| Broadcom Limited                      | 20        | 2.95%   |
| TP-Link                               | 7         | 1.03%   |
| Samsung Electronics                   | 5         | 0.74%   |
| Dell                                  | 5         | 0.74%   |
| ASIX Electronics                      | 5         | 0.74%   |
| Ralink                                | 4         | 0.59%   |
| Nvidia                                | 4         | 0.59%   |
| Marvell Technology Group              | 4         | 0.59%   |
| DisplayLink                           | 3         | 0.44%   |
| Ralink Technology                     | 2         | 0.3%    |
| NetGear                               | 2         | 0.3%    |
| Hewlett-Packard                       | 2         | 0.3%    |
| ASUSTek Computer                      | 2         | 0.3%    |
| Xiaomi                                | 1         | 0.15%   |
| OPPO Electronics                      | 1         | 0.15%   |
| OnePlus Technology (Shenzhen)         | 1         | 0.15%   |
| Motorola PCS                          | 1         | 0.15%   |
| JMicron Technology                    | 1         | 0.15%   |
| Huawei Technologies                   | 1         | 0.15%   |
| Ericsson Business Mobile Networks     | 1         | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 156       | 19.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 3.5%    |
| Intel Wi-Fi 6 AX200                                               | 24        | 3%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 22        | 2.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17        | 2.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 17        | 2.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 17        | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 2%      |
| Intel Wireless 7260                                               | 16        | 2%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 15        | 1.87%   |
| Intel Wireless 8265 / 8275                                        | 15        | 1.87%   |
| Intel Wi-Fi 6 AX201                                               | 14        | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 14        | 1.75%   |
| Intel Wireless 7265                                               | 13        | 1.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 12        | 1.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 1.5%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 12        | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.37%   |
| Intel Wireless 8260                                               | 11        | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9         | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1%      |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 1%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 7         | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.87%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 7         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.75%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 6         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 5         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 5         | 0.62%   |
| Intel Wireless-AC 9260                                            | 5         | 0.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.62%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 0.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 0.62%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.62%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.5%    |
| Realtek Realtek Network controller                                | 4         | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.5%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 0.5%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 4         | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.37%   |
| Realtek 802.11n WLAN Adapter                                      | 3         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.37%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.37%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.37%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 199       | 44.72%  |
| Qualcomm Atheros                      | 88        | 19.78%  |
| Realtek Semiconductor                 | 63        | 14.16%  |
| Broadcom                              | 35        | 7.87%   |
| Broadcom Limited                      | 20        | 4.49%   |
| MediaTek                              | 19        | 4.27%   |
| TP-Link                               | 6         | 1.35%   |
| Dell                                  | 5         | 1.12%   |
| Ralink                                | 4         | 0.9%    |
| Ralink Technology                     | 2         | 0.45%   |
| NetGear                               | 2         | 0.45%   |
| ASUSTek Computer                      | 1         | 0.22%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 24        | 5.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 22        | 4.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 17        | 3.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 17        | 3.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 16        | 3.56%   |
| Intel Wireless 7260                                            | 16        | 3.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 15        | 3.33%   |
| Intel Wireless 8265 / 8275                                     | 15        | 3.33%   |
| Intel Wi-Fi 6 AX201                                            | 14        | 3.11%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 14        | 3.11%   |
| Intel Wireless 7265                                            | 13        | 2.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 12        | 2.67%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 12        | 2.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 2.44%   |
| Intel Wireless 8260                                            | 11        | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 1.78%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 1.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 7         | 1.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 7         | 1.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.33%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 6         | 1.33%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 5         | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 5         | 1.11%   |
| Intel Wireless-AC 9260                                         | 5         | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 1.11%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 1.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 1.11%   |
| Realtek Realtek Network controller                             | 4         | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 0.89%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 0.67%   |
| Realtek 802.11n WLAN Adapter                                   | 3         | 0.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.67%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 0.67%   |
| Dell Hub of E-Port Replicator                                  | 3         | 0.67%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 3         | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.44%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 0.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.44%   |
| MediaTek WLAN controller                                       | 2         | 0.44%   |
| Intel Wireless 3165                                            | 2         | 0.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.44%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 0.44%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.44%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 2         | 0.44%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                        | 2         | 0.44%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 0.44%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.22%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 209       | 60.58%  |
| Intel                         | 62        | 17.97%  |
| Qualcomm Atheros              | 28        | 8.12%   |
| Broadcom                      | 16        | 4.64%   |
| Samsung Electronics           | 5         | 1.45%   |
| ASIX Electronics              | 5         | 1.45%   |
| Nvidia                        | 4         | 1.16%   |
| Marvell Technology Group      | 4         | 1.16%   |
| DisplayLink                   | 3         | 0.87%   |
| Xiaomi                        | 1         | 0.29%   |
| TP-Link                       | 1         | 0.29%   |
| OPPO Electronics              | 1         | 0.29%   |
| OnePlus Technology (Shenzhen) | 1         | 0.29%   |
| Motorola PCS                  | 1         | 0.29%   |
| JMicron Technology            | 1         | 0.29%   |
| Huawei Technologies           | 1         | 0.29%   |
| Hewlett-Packard               | 1         | 0.29%   |
| ASUSTek Computer              | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 156       | 44.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 8.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17        | 4.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 3.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 2.01%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 2.01%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 2.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 1.72%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4         | 1.15%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.15%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 1.15%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.15%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.86%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.86%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.86%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.86%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.86%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.57%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.57%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.57%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.57%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.57%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.57%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.29%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.29%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.29%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.29%   |
| OPPO SDM720G-IDP _SN:B922E265                                     | 1         | 0.29%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.29%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.29%   |
| Motorola PCS moto g(9) play                                       | 1         | 0.29%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.29%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.29%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.29%   |
| Intel Ethernet controller                                         | 1         | 0.29%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.29%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.29%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.29%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.29%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.29%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.29%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.29%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 1         | 0.29%   |
| Huawei LYA-L09                                                    | 1         | 0.29%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 422       | 55.82%  |
| Ethernet | 331       | 43.78%  |
| Modem    | 3         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 350       | 79.55%  |
| Ethernet | 90        | 20.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 303       | 71.8%   |
| 1     | 114       | 27.01%  |
| 0     | 3         | 0.71%   |
| 3     | 2         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 295       | 69.74%  |
| Yes  | 128       | 30.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 170       | 47.35%  |
| Qualcomm Atheros Communications | 39        | 10.86%  |
| Apple                           | 30        | 8.36%   |
| Realtek Semiconductor           | 27        | 7.52%   |
| IMC Networks                    | 26        | 7.24%   |
| Broadcom                        | 17        | 4.74%   |
| Lite-On Technology              | 16        | 4.46%   |
| Foxconn / Hon Hai               | 15        | 4.18%   |
| Toshiba                         | 4         | 1.11%   |
| Hewlett-Packard                 | 3         | 0.84%   |
| Dell                            | 3         | 0.84%   |
| Realtek                         | 2         | 0.56%   |
| Opticis                         | 2         | 0.56%   |
| Ralink Technology               | 1         | 0.28%   |
| Ralink                          | 1         | 0.28%   |
| Foxconn International           | 1         | 0.28%   |
| Cambridge Silicon Radio         | 1         | 0.28%   |
| ASUSTek Computer                | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 54        | 15.04%  |
| Intel AX201 Bluetooth                                                               | 48        | 13.37%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 27        | 7.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 26        | 7.24%   |
| Intel AX200 Bluetooth                                                               | 22        | 6.13%   |
| Realtek Bluetooth Radio                                                             | 20        | 5.57%   |
| Apple Bluetooth USB Host Controller                                                 | 14        | 3.9%    |
| Apple Bluetooth Host Controller                                                     | 14        | 3.9%    |
| IMC Networks Wireless_Device                                                        | 10        | 2.79%   |
| Intel Bluetooth Device                                                              | 9         | 2.51%   |
| IMC Networks Bluetooth Device                                                       | 9         | 2.51%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 1.67%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 6         | 1.67%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.67%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 5         | 1.39%   |
| Intel AX210 Bluetooth                                                               | 5         | 1.39%   |
| Lite-On Bluetooth Device                                                            | 4         | 1.11%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.11%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.11%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.84%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 0.84%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.84%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 0.84%   |
| Broadcom BCM20702A0                                                                 | 3         | 0.84%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.56%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.56%   |
| Opticis Bluetooth Radio                                                             | 2         | 0.56%   |
| Lite-On Wireless_Device                                                             | 2         | 0.56%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 2         | 0.56%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.56%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.56%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 2         | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.56%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.28%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.28%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.28%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.28%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.28%   |
| Ralink CSR BS8510                                                                   | 1         | 0.28%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.28%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.28%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.28%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.28%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.28%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.28%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.28%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.28%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.28%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.28%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.28%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.28%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.28%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.28%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.28%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.28%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.28%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 315       | 57.27%  |
| AMD                                  | 104       | 18.91%  |
| Nvidia                               | 98        | 17.82%  |
| C-Media Electronics                  | 4         | 0.73%   |
| Sony                                 | 3         | 0.55%   |
| GN Netcom                            | 3         | 0.55%   |
| Texas Instruments                    | 2         | 0.36%   |
| SteelSeries ApS                      | 2         | 0.36%   |
| Lenovo                               | 2         | 0.36%   |
| Kingston Technology                  | 2         | 0.36%   |
| Hewlett-Packard                      | 2         | 0.36%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.18%   |
| TerraTec Electronic                  | 1         | 0.18%   |
| Sennheiser Communications            | 1         | 0.18%   |
| Realtek Semiconductor                | 1         | 0.18%   |
| Razer USA                            | 1         | 0.18%   |
| Plantronics                          | 1         | 0.18%   |
| Logitech                             | 1         | 0.18%   |
| JMTek                                | 1         | 0.18%   |
| iConnectivity                        | 1         | 0.18%   |
| Generalplus Technology               | 1         | 0.18%   |
| Focusrite-Novation                   | 1         | 0.18%   |
| Apple                                | 1         | 0.18%   |
| Antlion Audio                        | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 72        | 10.43%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 42        | 6.09%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 40        | 5.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 3.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 26        | 3.77%   |
| Intel 8 Series HD Audio Controller                                                                | 25        | 3.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 3.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 22        | 3.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 3.04%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 3.04%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 19        | 2.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 2.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                                        | 17        | 2.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 16        | 2.32%   |
| AMD FCH Azalia Controller                                                                         | 14        | 2.03%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 13        | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 1.88%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 12        | 1.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 1.59%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 1.59%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 10        | 1.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 1.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 1.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.87%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.87%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.72%   |
| Nvidia TU104 HD Audio Controller                                                                  | 5         | 0.72%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 0.72%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.58%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.58%   |
| Nvidia MCP89 High Definition Audio                                                                | 3         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.43%   |
| Nvidia Audio device                                                                               | 3         | 0.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.43%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3         | 0.43%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.43%   |
| Sony DualSense wireless controller (PS5)                                                          | 2         | 0.29%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.29%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.29%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.29%   |
| Hewlett-Packard USB Audio                                                                         | 2         | 0.29%   |
| GN Netcom Jabra Link 380                                                                          | 2         | 0.29%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 0.29%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 0.29%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 2         | 0.29%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.29%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.29%   |
| Thesycon Systemsoftware & Consulting DX3 Pro                                                      | 1         | 0.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 31.15%  |
| SK hynix            | 33        | 27.05%  |
| Micron Technology   | 14        | 11.48%  |
| Kingston            | 5         | 4.1%    |
| Smart               | 4         | 3.28%   |
| Crucial             | 4         | 3.28%   |
| Unknown             | 3         | 2.46%   |
| Neo Forza           | 3         | 2.46%   |
| Unknown             | 3         | 2.46%   |
| PNY                 | 2         | 1.64%   |
| A-DATA Technology   | 2         | 1.64%   |
| Unknown (8A02)      | 1         | 0.82%   |
| Timetec             | 1         | 0.82%   |
| Teikon              | 1         | 0.82%   |
| Smart Brazil        | 1         | 0.82%   |
| Ramaxel Technology  | 1         | 0.82%   |
| GSkill              | 1         | 0.82%   |
| Goldkey             | 1         | 0.82%   |
| Gold Key            | 1         | 0.82%   |
| Elpida              | 1         | 0.82%   |
| Corsair             | 1         | 0.82%   |
| Avant               | 1         | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 5         | 3.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 3.15%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 4         | 3.15%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 4         | 3.15%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 4         | 3.15%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 2.36%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 2.36%   |
| Unknown                                                             | 3         | 2.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 2         | 1.57%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 1.57%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 1.57%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 2         | 1.57%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 1.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.57%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 2         | 1.57%   |
| Neo Forza RAM NMSO416E82-3200E 16GB SODIMM DDR4 3200MT/s            | 2         | 1.57%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.79%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.79%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s                | 1         | 0.79%   |
| Unknown (8A02) RAM 8G2400MHz 8GB SODIMM DDR4 2667MT/s               | 1         | 0.79%   |
| Timetec RAM 32NUS2R8-32G 32GB SODIMM DDR4 3200MT/s                  | 1         | 0.79%   |
| Teikon RAM TMT251S6CFR8C-PBHC 4GB SODIMM DDR3 1600MT/s              | 1         | 0.79%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s               | 1         | 0.79%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s               | 1         | 0.79%   |
| Smart RAM SG564568FG8NWKFSQR 2GB SODIMM DDR2 800MT/s                | 1         | 0.79%   |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s               | 1         | 0.79%   |
| Smart Brazil RAM SMS4WEC3C0K0446SCG 4GB SODIMM DDR4 3200MT/s        | 1         | 0.79%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 3200MT/s              | 1         | 0.79%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.79%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 1         | 0.79%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 1         | 0.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.79%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.79%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.79%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.79%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 1         | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s           | 1         | 0.79%   |
| SK hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.79%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s    | 1         | 0.79%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 0.79%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                 | 1         | 0.79%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 2133MT/s                       | 1         | 0.79%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 0.79%   |
| Samsung RAM M471B5674BH0-YH9 2GB Chip DDR3 1333MT/s                 | 1         | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.79%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 0.79%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s      | 1         | 0.79%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 0.79%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s           | 1         | 0.79%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 0.79%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 0.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 1         | 0.79%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s               | 1         | 0.79%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s                  | 1         | 0.79%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM 4800MT/s                  | 1         | 0.79%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s           | 1         | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 71        | 68.27%  |
| DDR3    | 17        | 16.35%  |
| LPDDR4  | 7         | 6.73%   |
| LPDDR3  | 5         | 4.81%   |
| SDRAM   | 1         | 0.96%   |
| LPDDR5  | 1         | 0.96%   |
| DDR2    | 1         | 0.96%   |
| Unknown | 1         | 0.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 81.31%  |
| Row Of Chips | 19        | 17.76%  |
| Chip         | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 58        | 52.73%  |
| 4096  | 22        | 20%     |
| 16384 | 19        | 17.27%  |
| 32768 | 6         | 5.45%   |
| 2048  | 5         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 42        | 37.84%  |
| 2667  | 23        | 20.72%  |
| 1600  | 14        | 12.61%  |
| 2133  | 8         | 7.21%   |
| 8400  | 4         | 3.6%    |
| 4267  | 4         | 3.6%    |
| 2400  | 4         | 3.6%    |
| 1333  | 3         | 2.7%    |
| 1867  | 2         | 1.8%    |
| 6400  | 1         | 0.9%    |
| 4800  | 1         | 0.9%    |
| 4266  | 1         | 0.9%    |
| 3733  | 1         | 0.9%    |
| 3266  | 1         | 0.9%    |
| 2048  | 1         | 0.9%    |
| 800   | 1         | 0.9%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP Ink Tank Wireless 410 series | 1         | 100%    |

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
| Chicony Electronics                    | 93        | 23.97%  |
| Acer                                   | 48        | 12.37%  |
| Microdia                               | 43        | 11.08%  |
| Realtek Semiconductor                  | 38        | 9.79%   |
| IMC Networks                           | 36        | 9.28%   |
| Sunplus Innovation Technology          | 21        | 5.41%   |
| Apple                                  | 19        | 4.9%    |
| Quanta                                 | 17        | 4.38%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 3.61%   |
| Suyin                                  | 12        | 3.09%   |
| Syntek                                 | 6         | 1.55%   |
| SunplusIT                              | 6         | 1.55%   |
| Silicon Motion                         | 5         | 1.29%   |
| Samsung Electronics                    | 4         | 1.03%   |
| Luxvisions Innotech Limited            | 4         | 1.03%   |
| Lite-On Technology                     | 4         | 1.03%   |
| Sonix Technology                       | 3         | 0.77%   |
| Alcor Micro                            | 3         | 0.77%   |
| Microsoft                              | 2         | 0.52%   |
| Logitech                               | 2         | 0.52%   |
| Generalplus Technology                 | 2         | 0.52%   |
| Z-Star Microelectronics                | 1         | 0.26%   |
| SJ-180517-N                            | 1         | 0.26%   |
| Ricoh                                  | 1         | 0.26%   |
| Primax Electronics                     | 1         | 0.26%   |
| LG Electronics                         | 1         | 0.26%   |
| Importek                               | 1         | 0.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 18        | 4.62%   |
| Microdia Integrated_Webcam_HD                    | 18        | 4.62%   |
| Chicony Integrated Camera                        | 17        | 4.36%   |
| IMC Networks USB2.0 HD UVC WebCam                | 12        | 3.08%   |
| Chicony HD WebCam                                | 12        | 3.08%   |
| Acer Integrated Camera                           | 10        | 2.56%   |
| Acer HD Webcam                                   | 10        | 2.56%   |
| Acer BisonCam,NB Pro                             | 9         | 2.31%   |
| IMC Networks Integrated Camera                   | 8         | 2.05%   |
| Syntek Integrated Camera                         | 6         | 1.54%   |
| Sunplus Integrated_Webcam_HD                     | 6         | 1.54%   |
| Microdia Integrated Webcam                       | 6         | 1.54%   |
| Apple iPhone 5/5C/5S/6/SE                        | 6         | 1.54%   |
| Apple Built-in iSight                            | 6         | 1.54%   |
| Quanta HP HD Camera                              | 5         | 1.28%   |
| Chicony USB2.0 VGA UVC WebCam                    | 5         | 1.28%   |
| Chicony USB2.0 Camera                            | 5         | 1.28%   |
| Chicony TOSHIBA Web Camera - HD                  | 5         | 1.28%   |
| Apple FaceTime HD Camera                         | 5         | 1.28%   |
| Suyin HP Truevision HD                           | 4         | 1.03%   |
| Samsung Galaxy A5 (MTP)                          | 4         | 1.03%   |
| Quanta HD User Facing                            | 4         | 1.03%   |
| Microdia Integrated Webcam HD                    | 4         | 1.03%   |
| Chicony Integrated Camera (1280x720@30)          | 4         | 1.03%   |
| Sonix USB2.0 HD UVC WebCam                       | 3         | 0.77%   |
| Quanta HD Webcam                                 | 3         | 0.77%   |
| IMC Networks USB2.0 UVC HD Webcam                | 3         | 0.77%   |
| Chicony USB2.0 HD UVC WebCam                     | 3         | 0.77%   |
| Chicony USB 2.0 Camera                           | 3         | 0.77%   |
| Chicony HP Wide Vision HD Camera                 | 3         | 0.77%   |
| Chicony HP HD Webcam                             | 3         | 0.77%   |
| Chicony HP HD Camera                             | 3         | 0.77%   |
| Chicony HD User Facing                           | 3         | 0.77%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 3         | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 3         | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 3         | 0.77%   |
| Acer EasyCamera                                  | 3         | 0.77%   |
| Suyin Integrated_Webcam_HD                       | 2         | 0.51%   |
| Suyin 1.3M HD WebCam                             | 2         | 0.51%   |
| SunplusIT 720p HD Camera                         | 2         | 0.51%   |
| SunplusIT 1080p FHD Camera                       | 2         | 0.51%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 2         | 0.51%   |
| Sunplus Laptop Integrated Webcam FHD             | 2         | 0.51%   |
| Sunplus HD WebCam                                | 2         | 0.51%   |
| Sunplus 1.3M HD WebCam                           | 2         | 0.51%   |
| Silicon Motion Web Camera                        | 2         | 0.51%   |
| Realtek USB2.0 HD UVC WebCam                     | 2         | 0.51%   |
| Realtek USB Camera                               | 2         | 0.51%   |
| Realtek MTD camera                               | 2         | 0.51%   |
| Realtek Integrated Webcam HD                     | 2         | 0.51%   |
| Realtek Integrated Webcam                        | 2         | 0.51%   |
| Realtek HD WebCam                                | 2         | 0.51%   |
| Microdia Laptop_Integrated_Webcam_HD             | 2         | 0.51%   |
| Microdia HDP Webcam USB                          | 2         | 0.51%   |
| Microdia Dell Integrated HD Webcam               | 2         | 0.51%   |
| Luxvisions Innotech Limited HP HD Camera         | 2         | 0.51%   |
| Lite-On Integrated Camera                        | 2         | 0.51%   |
| IMC Networks VGA UVC WebCam                      | 2         | 0.51%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 0.51%   |
| Generalplus WEB CAM                              | 2         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 24        | 36.92%  |
| Validity Sensors           | 16        | 24.62%  |
| Shenzhen Goodix Technology | 13        | 20%     |
| LighTuning Technology      | 4         | 6.15%   |
| Upek                       | 2         | 3.08%   |
| HOLTEK                     | 2         | 3.08%   |
| Elan Microelectronics      | 2         | 3.08%   |
| AuthenTec                  | 2         | 3.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 8         | 12.31%  |
| Shenzhen Goodix  FingerPrint Device                       | 6         | 9.23%   |
| Unknown                                                   | 6         | 9.23%   |
| Validity Sensors VFS495 Fingerprint Reader                | 5         | 7.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 4         | 6.15%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 4         | 6.15%   |
| Shenzhen Goodix FingerPrint                               | 4         | 6.15%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 3         | 4.62%   |
| Shenzhen Goodix Fingerprint Reader                        | 3         | 4.62%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 2         | 3.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 3.08%   |
| Synaptics WBDI Device                                     | 2         | 3.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 2         | 3.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 2         | 3.08%   |
| HOLTEK FocalTech Fingerprint Device                       | 2         | 3.08%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 1.54%   |
| Validity Sensors VFS491                                   | 1         | 1.54%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 1.54%   |
| Validity Sensors Synaptics WBDI                           | 1         | 1.54%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 1.54%   |
| Validity Sensors Fingerprint scanner                      | 1         | 1.54%   |
| Elan ELAN:Fingerprint                                     | 1         | 1.54%   |
| Elan ELAN:ARM-M4                                          | 1         | 1.54%   |
| AuthenTec AES2810                                         | 1         | 1.54%   |
| AuthenTec AES2550 Fingerprint Sensor                      | 1         | 1.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 17        | 60.71%  |
| Alcor Micro | 5         | 17.86%  |
| O2 Micro    | 3         | 10.71%  |
| Upek        | 2         | 7.14%   |
| Lenovo      | 1         | 3.57%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 7         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 21.43%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 17.86%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 10.71%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 7.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 7.14%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.57%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.57%   |
| Broadcom 58200                                                               | 1         | 3.57%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 249       | 58.31%  |
| 1     | 144       | 33.72%  |
| 2     | 28        | 6.56%   |
| 3     | 5         | 1.17%   |
| 4     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 62        | 29.38%  |
| Multimedia controller    | 39        | 18.48%  |
| Net/wireless             | 27        | 12.8%   |
| Chipcard                 | 27        | 12.8%   |
| Bluetooth                | 24        | 11.37%  |
| Graphics card            | 16        | 7.58%   |
| Net/ethernet             | 3         | 1.42%   |
| Storage/ide              | 2         | 0.95%   |
| Storage                  | 2         | 0.95%   |
| Modem                    | 2         | 0.95%   |
| Communication controller | 2         | 0.95%   |
| Card reader              | 2         | 0.95%   |
| Sound                    | 1         | 0.47%   |
| Network                  | 1         | 0.47%   |
| Camera                   | 1         | 0.47%   |

