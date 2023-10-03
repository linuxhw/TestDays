Linux in Estonia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Estonia.

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

Total: 239

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T440p 20AWS49Q0... | [65fa77246e](https://linux-hardware.org/?probe=65fa77246e) | Sep 21, 2023 |
| Dell          | Latitude E5550              | [9044f3b345](https://linux-hardware.org/?probe=9044f3b345) | Sep 12, 2023 |
| HP            | 250 G5 Notebook PC          | [773143cf61](https://linux-hardware.org/?probe=773143cf61) | Sep 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | [3d7ba31c2a](https://linux-hardware.org/?probe=3d7ba31c2a) | Aug 24, 2023 |
| Lenovo        | ThinkPad P50 20EQS4XN00     | [a517cc57b8](https://linux-hardware.org/?probe=a517cc57b8) | Aug 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | [cb5346a558](https://linux-hardware.org/?probe=cb5346a558) | Aug 17, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | [4bfb2c68ca](https://linux-hardware.org/?probe=4bfb2c68ca) | Aug 17, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| Dell          | Vostro 3700                 | [96e4579b7b](https://linux-hardware.org/?probe=96e4579b7b) | Aug 01, 2023 |
| Intel         | powered classmate PC        | [ccbb0cb45a](https://linux-hardware.org/?probe=ccbb0cb45a) | Jul 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00bda81c25](https://linux-hardware.org/?probe=00bda81c25) | Jul 19, 2023 |
| HP            | ProBook 640 G1              | [8c2fd03132](https://linux-hardware.org/?probe=8c2fd03132) | Jul 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| Lenovo        | ThinkPad L480 20LTSAK70R    | [551d238ad3](https://linux-hardware.org/?probe=551d238ad3) | May 16, 2023 |
| Notebook      | N150SD/N155SD               | [55f219bc3f](https://linux-hardware.org/?probe=55f219bc3f) | May 11, 2023 |
| ASUSTek       | N550JK                      | [a799667521](https://linux-hardware.org/?probe=a799667521) | May 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [fdaef83d1e](https://linux-hardware.org/?probe=fdaef83d1e) | Apr 23, 2023 |
| MSI           | GF63 Thin 10SCXR            | [33e5d369a7](https://linux-hardware.org/?probe=33e5d369a7) | Apr 04, 2023 |
| Apple         | MacBookPro5,1               | [b06257fd9c](https://linux-hardware.org/?probe=b06257fd9c) | Mar 28, 2023 |
| Apple         | MacBookPro5,1               | [3a0d77d195](https://linux-hardware.org/?probe=3a0d77d195) | Mar 28, 2023 |
| Gigabyte      | G5 KD                       | [32afc6a4cf](https://linux-hardware.org/?probe=32afc6a4cf) | Mar 23, 2023 |
| Apple         | MacBookPro9,2               | [4efbf8be88](https://linux-hardware.org/?probe=4efbf8be88) | Mar 23, 2023 |
| GPD           | G1619-04                    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [c87313bdd4](https://linux-hardware.org/?probe=c87313bdd4) | Mar 20, 2023 |
| Lenovo        | ThinkPad T540p 20BFS3BR0... | [6218acf76f](https://linux-hardware.org/?probe=6218acf76f) | Mar 12, 2023 |
| Packard Be... | EasyNote TK87               | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| Packard Be... | EasyNote TK87               | [f1c4c8b89e](https://linux-hardware.org/?probe=f1c4c8b89e) | Jan 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [ff12fe840d](https://linux-hardware.org/?probe=ff12fe840d) | Jan 12, 2023 |
| HP            | EliteBook 840 G2            | [4a85ebbc33](https://linux-hardware.org/?probe=4a85ebbc33) | Dec 26, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [d8b614d1ca](https://linux-hardware.org/?probe=d8b614d1ca) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1f904e68af](https://linux-hardware.org/?probe=1f904e68af) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| ASUSTek       | N53Jf                       | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [b792955af6](https://linux-hardware.org/?probe=b792955af6) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | [033e206fab](https://linux-hardware.org/?probe=033e206fab) | Nov 25, 2022 |
| Valve         | Jupiter                     | [0e77de9dba](https://linux-hardware.org/?probe=0e77de9dba) | Nov 20, 2022 |
| Acer          | Swift SF114-34              | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Alienware     | 17                          | [91358a0bec](https://linux-hardware.org/?probe=91358a0bec) | Nov 09, 2022 |
| Fujitsu       | LIFEBOOK A512               | [c479fc2cea](https://linux-hardware.org/?probe=c479fc2cea) | Nov 06, 2022 |
| HP            | Unknown                     | [aa28b92716](https://linux-hardware.org/?probe=aa28b92716) | Nov 06, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [36d7199821](https://linux-hardware.org/?probe=36d7199821) | Nov 01, 2022 |
| MSI           | GL72 6QD                    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| HUAWEI        | BOM-WXX9                    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Dell          | Latitude 7390               | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| Chuwi         | HeroBook Pro                | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| ASUSTek       | 1225C                       | [91f049c977](https://linux-hardware.org/?probe=91f049c977) | Sep 09, 2022 |
| Fujitsu       | LIFEBOOK S760               | [d805aa67b2](https://linux-hardware.org/?probe=d805aa67b2) | Sep 09, 2022 |
| Apple         | MacBookPro11,1              | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Valve         | Jupiter                     | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| ASUSTek       | E502NA                      | [d65dd8fc52](https://linux-hardware.org/?probe=d65dd8fc52) | Jun 09, 2022 |
| ASUSTek       | E502NA                      | [d3d64dcb5b](https://linux-hardware.org/?probe=d3d64dcb5b) | Jun 09, 2022 |
| HP            | Presario CQ57               | [9f87592293](https://linux-hardware.org/?probe=9f87592293) | Jun 02, 2022 |
| Dell          | Latitude 5520               | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| HP            | EliteBook 8470p             | [0773b6244e](https://linux-hardware.org/?probe=0773b6244e) | May 11, 2022 |
| Lenovo        | ThinkPad T490s 20NX000AM... | [f07b38c5f9](https://linux-hardware.org/?probe=f07b38c5f9) | May 10, 2022 |
| Apple         | MacBookPro8,1               | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| mPTech        | ARC 11.6 128GB HD           | [aafa7cb1cb](https://linux-hardware.org/?probe=aafa7cb1cb) | May 07, 2022 |
| Dell          | Precision 7540              | [8b1b7dd8da](https://linux-hardware.org/?probe=8b1b7dd8da) | Apr 30, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | [a10fb9fe10](https://linux-hardware.org/?probe=a10fb9fe10) | Apr 23, 2022 |
| HP            | EliteBook 840 G2            | [b963507390](https://linux-hardware.org/?probe=b963507390) | Apr 19, 2022 |
| HP            | EliteBook 840 G2            | [fff8ad361e](https://linux-hardware.org/?probe=fff8ad361e) | Apr 19, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | [d948d987b4](https://linux-hardware.org/?probe=d948d987b4) | Apr 18, 2022 |
| Framework     | Laptop                      | [d4a02dfec9](https://linux-hardware.org/?probe=d4a02dfec9) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Dell          | Latitude 5520               | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | [7fb04e6c7d](https://linux-hardware.org/?probe=7fb04e6c7d) | Mar 03, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | [0f27bdf5a8](https://linux-hardware.org/?probe=0f27bdf5a8) | Mar 02, 2022 |
| Lenovo        | ThinkPad X220 429136G       | [324d66c0fc](https://linux-hardware.org/?probe=324d66c0fc) | Feb 23, 2022 |
| HP            | EliteBook Folio 1040 G2     | [5f3cd9e8d5](https://linux-hardware.org/?probe=5f3cd9e8d5) | Feb 16, 2022 |
| Dell          | XPS 15 7590                 | [96f97ed2d6](https://linux-hardware.org/?probe=96f97ed2d6) | Jan 23, 2022 |
| HP            | EliteBook 8460p             | [ca26ae6ff8](https://linux-hardware.org/?probe=ca26ae6ff8) | Dec 22, 2021 |
| ASUSTek       | K52Jc                       | [f6789bc7ac](https://linux-hardware.org/?probe=f6789bc7ac) | Dec 18, 2021 |
| HP            | EliteBook 820 G1            | [dbbe56da66](https://linux-hardware.org/?probe=dbbe56da66) | Dec 01, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [dc981a1604](https://linux-hardware.org/?probe=dc981a1604) | Nov 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [362a840c47](https://linux-hardware.org/?probe=362a840c47) | Nov 20, 2021 |
| Alienware     | 17                          | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Dell          | Precision 5550              | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Getac         | B300G4                      | [78b2fab1e0](https://linux-hardware.org/?probe=78b2fab1e0) | Oct 17, 2021 |
| HP            | Pavilion dv7                | [6c14033e55](https://linux-hardware.org/?probe=6c14033e55) | Oct 16, 2021 |
| HP            | Pavilion dv7                | [f93789f29a](https://linux-hardware.org/?probe=f93789f29a) | Oct 16, 2021 |
| Acer          | Extensa 5620                | [5cae4fe0fa](https://linux-hardware.org/?probe=5cae4fe0fa) | Oct 11, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Alienware     | 17                          | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4f393c5347](https://linux-hardware.org/?probe=4f393c5347) | Sep 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| ASUSTek       | UX530UX                     | [c713dcf9e2](https://linux-hardware.org/?probe=c713dcf9e2) | Sep 08, 2021 |
| ASUSTek       | X510UA                      | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| ASUSTek       | X550ZA                      | [210ca88228](https://linux-hardware.org/?probe=210ca88228) | Aug 30, 2021 |
| Lenovo        | ThinkPad X201 3680CG7       | [9565bae9c3](https://linux-hardware.org/?probe=9565bae9c3) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [75619baa6e](https://linux-hardware.org/?probe=75619baa6e) | Aug 29, 2021 |
| ASUSTek       | X550ZA                      | [0a21d3b326](https://linux-hardware.org/?probe=0a21d3b326) | Aug 27, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Dell          | XPS 15 9500                 | [f21459caa1](https://linux-hardware.org/?probe=f21459caa1) | Aug 19, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [5f9d1cd1a6](https://linux-hardware.org/?probe=5f9d1cd1a6) | Aug 18, 2021 |
| HP            | EliteBook 8460p             | [0ce69e02fa](https://linux-hardware.org/?probe=0ce69e02fa) | Aug 17, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [fcd91a58e2](https://linux-hardware.org/?probe=fcd91a58e2) | Aug 13, 2021 |
| HP            | Pavilion dv7                | [a56935a751](https://linux-hardware.org/?probe=a56935a751) | Aug 09, 2021 |
| MSI           | GP62M 7RDX                  | [f02c96473f](https://linux-hardware.org/?probe=f02c96473f) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | [7207e6aa0f](https://linux-hardware.org/?probe=7207e6aa0f) | Jul 08, 2021 |
| Dell          | XPS 15 9500                 | [a47fb764b4](https://linux-hardware.org/?probe=a47fb764b4) | Jul 01, 2021 |
| Lenovo        | IdeaPadFlex 10 20324        | [d96aea9f90](https://linux-hardware.org/?probe=d96aea9f90) | Jun 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [cb4242a344](https://linux-hardware.org/?probe=cb4242a344) | Jun 15, 2021 |
| HP            | EliteBook 8460p             | [7bf0e678ea](https://linux-hardware.org/?probe=7bf0e678ea) | Jun 13, 2021 |
| Lenovo        | ThinkPad T450s 20BWS1RG0... | [79d386a567](https://linux-hardware.org/?probe=79d386a567) | Jun 08, 2021 |
| Dell          | Latitude 5511               | [933fb253d4](https://linux-hardware.org/?probe=933fb253d4) | Jun 07, 2021 |
| Dell          | Latitude 5511               | [7b5e6276c0](https://linux-hardware.org/?probe=7b5e6276c0) | Jun 07, 2021 |
| HP            | EliteBook 8460p             | [6a7fe6469a](https://linux-hardware.org/?probe=6a7fe6469a) | Jun 06, 2021 |
| Timi          | RedmiBook 14 II             | [8700a7eaed](https://linux-hardware.org/?probe=8700a7eaed) | May 31, 2021 |
| Dell          | XPS 15 9500                 | [1ba665b0b3](https://linux-hardware.org/?probe=1ba665b0b3) | May 24, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [3ae2f83c9f](https://linux-hardware.org/?probe=3ae2f83c9f) | May 23, 2021 |
| Dell          | G5 5587                     | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| Dell          | Precision 5530              | [aa0aa77e62](https://linux-hardware.org/?probe=aa0aa77e62) | May 16, 2021 |
| HP            | EliteBook 8460p             | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| Dell          | Vostro V131                 | [43fe3f190f](https://linux-hardware.org/?probe=43fe3f190f) | May 14, 2021 |
| HP            | EliteBook 8460p             | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Lenovo        | Y50-70 20378                | [fe95dd9355](https://linux-hardware.org/?probe=fe95dd9355) | May 11, 2021 |
| Dell          | System Inspiron N7110       | [f5f418c337](https://linux-hardware.org/?probe=f5f418c337) | May 02, 2021 |
| Dell          | XPS 15 9500                 | [1bbe4079c5](https://linux-hardware.org/?probe=1bbe4079c5) | Apr 27, 2021 |
| HP            | Compaq nx6120 (PV170PA#U... | [5f105dda68](https://linux-hardware.org/?probe=5f105dda68) | Apr 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f84cf26650](https://linux-hardware.org/?probe=f84cf26650) | Apr 10, 2021 |
| Dell          | Inspiron N5110              | [a677fe0972](https://linux-hardware.org/?probe=a677fe0972) | Apr 08, 2021 |
| Dell          | Latitude E5430 non-vPro     | [ed6b3b5754](https://linux-hardware.org/?probe=ed6b3b5754) | Apr 04, 2021 |
| Dell          | Latitude E5430 non-vPro     | [218092e59f](https://linux-hardware.org/?probe=218092e59f) | Apr 03, 2021 |
| Lenovo        | Y50-70 20378                | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Dell          | XPS 15 7590                 | [6e6dc77b21](https://linux-hardware.org/?probe=6e6dc77b21) | Mar 29, 2021 |
| Samsung       | R410                        | [331d909654](https://linux-hardware.org/?probe=331d909654) | Mar 27, 2021 |
| Samsung       | R410                        | [5aa6fee818](https://linux-hardware.org/?probe=5aa6fee818) | Mar 25, 2021 |
| Samsung       | R410                        | [d3f94bcc8c](https://linux-hardware.org/?probe=d3f94bcc8c) | Mar 24, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [fb33c2e9b9](https://linux-hardware.org/?probe=fb33c2e9b9) | Mar 17, 2021 |
| Notebook      | W35xSS_370SS                | [0e98472f08](https://linux-hardware.org/?probe=0e98472f08) | Mar 02, 2021 |
| Lenovo        | ThinkPad T61 766112G        | [04ec7d5efd](https://linux-hardware.org/?probe=04ec7d5efd) | Feb 25, 2021 |
| Acer          | Aspire V5-572P              | [61834c786c](https://linux-hardware.org/?probe=61834c786c) | Feb 24, 2021 |
| HP            | EliteBook 850 G2            | [4c935ce981](https://linux-hardware.org/?probe=4c935ce981) | Feb 18, 2021 |
| HP            | EliteBook 850 G2            | [69090d5f4c](https://linux-hardware.org/?probe=69090d5f4c) | Feb 17, 2021 |
| Dell          | XPS 15 9500                 | [8652b51903](https://linux-hardware.org/?probe=8652b51903) | Jan 20, 2021 |
| Dell          | XPS 15 9500                 | [77be7c1164](https://linux-hardware.org/?probe=77be7c1164) | Jan 18, 2021 |
| HP            | EliteBook 840 G5            | [59aaeda6a9](https://linux-hardware.org/?probe=59aaeda6a9) | Dec 28, 2020 |
| Fujitsu       | LIFEBOOK E744               | [81daeffb49](https://linux-hardware.org/?probe=81daeffb49) | Dec 28, 2020 |
| Timi          | RedmiBook 16                | [34bc3ceb48](https://linux-hardware.org/?probe=34bc3ceb48) | Dec 24, 2020 |
| MSI           | GT70 2OC/2OD                | [e52bbc40aa](https://linux-hardware.org/?probe=e52bbc40aa) | Dec 19, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | [95355fcff6](https://linux-hardware.org/?probe=95355fcff6) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | [3ee030e6ac](https://linux-hardware.org/?probe=3ee030e6ac) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 765912G        | [9651814a46](https://linux-hardware.org/?probe=9651814a46) | Dec 08, 2020 |
| Lenovo        | Y50-70 20378                | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [4defcea6f8](https://linux-hardware.org/?probe=4defcea6f8) | Nov 24, 2020 |
| Notebook      | W35xSS_370SS                | [ed0e6634d4](https://linux-hardware.org/?probe=ed0e6634d4) | Sep 29, 2020 |
| HP            | EliteBook 745 G5            | [e9d2889a6d](https://linux-hardware.org/?probe=e9d2889a6d) | Sep 28, 2020 |
| Dell          | Latitude 7490               | [cfd6c8dcc4](https://linux-hardware.org/?probe=cfd6c8dcc4) | Sep 28, 2020 |
| TUXEDO        | Book BA1510                 | [d89436074e](https://linux-hardware.org/?probe=d89436074e) | Sep 23, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [3399940dd9](https://linux-hardware.org/?probe=3399940dd9) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [5bd6ca5aba](https://linux-hardware.org/?probe=5bd6ca5aba) | Sep 15, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [83263681eb](https://linux-hardware.org/?probe=83263681eb) | Sep 15, 2020 |
| Notebook      | W35xSS_370SS                | [5b35813fca](https://linux-hardware.org/?probe=5b35813fca) | Sep 10, 2020 |
| HP            | ZBook 17                    | [605dfd3279](https://linux-hardware.org/?probe=605dfd3279) | Sep 08, 2020 |
| HP            | ZBook 17                    | [09e5bd8eb6](https://linux-hardware.org/?probe=09e5bd8eb6) | Sep 08, 2020 |
| ASUSTek       | X542UQR                     | [7782f01f3c](https://linux-hardware.org/?probe=7782f01f3c) | Sep 04, 2020 |
| ASUSTek       | E502MA                      | [1eb9e7db73](https://linux-hardware.org/?probe=1eb9e7db73) | Sep 01, 2020 |
| ASUSTek       | X501U                       | [006dc7a8d6](https://linux-hardware.org/?probe=006dc7a8d6) | Aug 15, 2020 |
| Lenovo        | ThinkPad X220 4291R30       | [bdf2c40591](https://linux-hardware.org/?probe=bdf2c40591) | Aug 06, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Acer          | Extensa 5620                | [dba48971a3](https://linux-hardware.org/?probe=dba48971a3) | Jul 24, 2020 |
| Lenovo        | ThinkPad T480s 20L7001VU... | [03bcc8865c](https://linux-hardware.org/?probe=03bcc8865c) | Jul 23, 2020 |
| HP            | Presario CQ56               | [f668bc59f5](https://linux-hardware.org/?probe=f668bc59f5) | Jun 23, 2020 |
| HP            | Presario CQ56               | [b8db4c3694](https://linux-hardware.org/?probe=b8db4c3694) | Jun 23, 2020 |
| Dell          | XPS 15 9560                 | [867ca870fd](https://linux-hardware.org/?probe=867ca870fd) | Jun 14, 2020 |
| Samsung       | 535U3C                      | [e7bc13b354](https://linux-hardware.org/?probe=e7bc13b354) | May 30, 2020 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | [26c8949a0a](https://linux-hardware.org/?probe=26c8949a0a) | May 29, 2020 |
| Lenovo        | ThinkPad T540p 20BFS4510... | [6c5bf8bfbe](https://linux-hardware.org/?probe=6c5bf8bfbe) | May 05, 2020 |
| HP            | EliteBook 840 G2            | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [a1a1ce6e00](https://linux-hardware.org/?probe=a1a1ce6e00) | May 02, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [e3321de949](https://linux-hardware.org/?probe=e3321de949) | May 02, 2020 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [35b95432ac](https://linux-hardware.org/?probe=35b95432ac) | Apr 30, 2020 |
| Dell          | XPS 15 9560                 | [eea0fa4941](https://linux-hardware.org/?probe=eea0fa4941) | Apr 25, 2020 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [91770bcd78](https://linux-hardware.org/?probe=91770bcd78) | Apr 22, 2020 |
| MSI           | GS75 Stealth 8SE            | [1c50333136](https://linux-hardware.org/?probe=1c50333136) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | [cdca82a043](https://linux-hardware.org/?probe=cdca82a043) | Apr 05, 2020 |
| Samsung       | 275E4E/275E5E               | [6b624f1079](https://linux-hardware.org/?probe=6b624f1079) | Mar 12, 2020 |
| Lenovo        | ThinkPad A285 20MXS0BG00    | [4dabcb8d3f](https://linux-hardware.org/?probe=4dabcb8d3f) | Mar 11, 2020 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [c71def9148](https://linux-hardware.org/?probe=c71def9148) | Feb 18, 2020 |
| HP            | EliteBook 8470p             | [ed5efcdf48](https://linux-hardware.org/?probe=ed5efcdf48) | Feb 03, 2020 |
| Dell          | Precision 5510              | [68c56e0ab4](https://linux-hardware.org/?probe=68c56e0ab4) | Dec 02, 2019 |
| HP            | Pavilion Gaming Notebook    | [c4917de06e](https://linux-hardware.org/?probe=c4917de06e) | Oct 17, 2019 |
| HP            | Pavilion Gaming Notebook    | [9f867b307a](https://linux-hardware.org/?probe=9f867b307a) | Oct 12, 2019 |
| HP            | Pavilion Gaming Notebook    | [f3f1a208c1](https://linux-hardware.org/?probe=f3f1a208c1) | Sep 26, 2019 |
| HP            | Pavilion Gaming Notebook    | [0639ef182a](https://linux-hardware.org/?probe=0639ef182a) | Sep 20, 2019 |
| HP            | Pavilion Gaming Notebook    | [3b99dff2c2](https://linux-hardware.org/?probe=3b99dff2c2) | Sep 19, 2019 |
| Dell          | Inspiron 5748               | [75647e5457](https://linux-hardware.org/?probe=75647e5457) | Sep 03, 2019 |
| Acer          | Aspire V3-771               | [335c3fea78](https://linux-hardware.org/?probe=335c3fea78) | Aug 10, 2019 |
| Quanta        | TWH                         | [b6c3554305](https://linux-hardware.org/?probe=b6c3554305) | Aug 05, 2019 |
| Quanta        | TWH                         | [243be58298](https://linux-hardware.org/?probe=243be58298) | Aug 05, 2019 |
| HP            | OMEN by Laptop              | [4a247c1234](https://linux-hardware.org/?probe=4a247c1234) | Aug 03, 2019 |
| Lenovo        | V110-15ISK 80TL             | [15bfdc0f25](https://linux-hardware.org/?probe=15bfdc0f25) | Aug 03, 2019 |
| HP            | OMEN by Laptop              | [cd37f24ff8](https://linux-hardware.org/?probe=cd37f24ff8) | Aug 01, 2019 |
| Dell          | Inspiron 5558               | [f26b9a5e36](https://linux-hardware.org/?probe=f26b9a5e36) | Jun 29, 2019 |
| ASUSTek       | N56VZ                       | [02928f6b1e](https://linux-hardware.org/?probe=02928f6b1e) | Jun 25, 2019 |
| Lenovo        | IdeaPad U330p 20267         | [1edb7b5f96](https://linux-hardware.org/?probe=1edb7b5f96) | May 25, 2019 |
| HP            | Pavilion dv4000 (EK980EA... | [837230178b](https://linux-hardware.org/?probe=837230178b) | May 23, 2019 |
| Lenovo        | G50-70 20351                | [84c3544bb2](https://linux-hardware.org/?probe=84c3544bb2) | May 20, 2019 |
| Samsung       | 275E4E/275E5E               | [60cb87eeb6](https://linux-hardware.org/?probe=60cb87eeb6) | May 11, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | [cfcb3e3b82](https://linux-hardware.org/?probe=cfcb3e3b82) | May 02, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | [c577dfbf17](https://linux-hardware.org/?probe=c577dfbf17) | May 02, 2019 |
| Samsung       | 770Z5E/780Z5E               | [e07529a7fc](https://linux-hardware.org/?probe=e07529a7fc) | Apr 14, 2019 |
| Fujitsu Si... | AMILO La1703                | [4530891733](https://linux-hardware.org/?probe=4530891733) | Apr 01, 2019 |
| Dell          | Inspiron 3543               | [e411551975](https://linux-hardware.org/?probe=e411551975) | Mar 21, 2019 |
| Dell          | Inspiron 3543               | [f85fec55bb](https://linux-hardware.org/?probe=f85fec55bb) | Mar 19, 2019 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [bee48cd1c5](https://linux-hardware.org/?probe=bee48cd1c5) | Mar 09, 2019 |
| Lenovo        | ThinkPad T580 20L90026MX    | [14afd9ea12](https://linux-hardware.org/?probe=14afd9ea12) | Feb 27, 2019 |
| HP            | ProBook 470 G1              | [268414d1b5](https://linux-hardware.org/?probe=268414d1b5) | Feb 07, 2019 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [5357d8ad3a](https://linux-hardware.org/?probe=5357d8ad3a) | Dec 04, 2018 |
| Lenovo        | Y520-15IKBN 80WK            | [a075fc73d3](https://linux-hardware.org/?probe=a075fc73d3) | Oct 09, 2018 |
| ASUSTek       | X55A                        | [403b1aa1d7](https://linux-hardware.org/?probe=403b1aa1d7) | May 08, 2018 |
| ASUSTek       | K40IJ                       | [24366329c2](https://linux-hardware.org/?probe=24366329c2) | May 07, 2018 |
| Dell          | Inspiron N5110              | [d7b2f7f719](https://linux-hardware.org/?probe=d7b2f7f719) | Oct 05, 2017 |
| Acer          | Aspire 6530G                | [2f88dba791](https://linux-hardware.org/?probe=2f88dba791) | Aug 13, 2017 |
| HP            | Compaq nx7400 (RH387EA#A... | [116c8bc9de](https://linux-hardware.org/?probe=116c8bc9de) | Jun 03, 2017 |
| Toshiba       | Satellite L855              | [de2e163003](https://linux-hardware.org/?probe=de2e163003) | May 17, 2017 |
| HP            | Pavilion dv5                | [3191678465](https://linux-hardware.org/?probe=3191678465) | May 04, 2017 |
| HP            | Pavilion dv5                | [1f21f421ed](https://linux-hardware.org/?probe=1f21f421ed) | May 02, 2017 |
| Quanta        | TWH                         | [4807bd6702](https://linux-hardware.org/?probe=4807bd6702) | Apr 28, 2017 |
| Quanta        | TWH                         | [0105619fb7](https://linux-hardware.org/?probe=0105619fb7) | Apr 27, 2017 |
| Acer          | Aspire 5541                 | [efa45ad21c](https://linux-hardware.org/?probe=efa45ad21c) | Nov 14, 2016 |
| Acer          | Aspire 5541                 | [b61eb7bcb0](https://linux-hardware.org/?probe=b61eb7bcb0) | Nov 13, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 19        | 10.33%  |
| Ubuntu 22.04       | 14        | 7.61%   |
| Ubuntu 18.04       | 14        | 7.61%   |
| ArcoLinux Rolling  | 7         | 3.8%    |
| Arch               | 7         | 3.8%    |
| Ubuntu 19.04       | 6         | 3.26%   |
| Linux Mint 20.1    | 5         | 2.72%   |
| Kubuntu 22.04      | 4         | 2.17%   |
| Fedora 34          | 4         | 2.17%   |
| Arch Rolling       | 4         | 2.17%   |
| ROSA R9            | 3         | 1.63%   |
| ROSA R8.1          | 3         | 1.63%   |
| ROSA R11           | 3         | 1.63%   |
| Pop!_OS 20.04      | 3         | 1.63%   |
| OpenMandriva 4.3   | 3         | 1.63%   |
| OpenMandriva 4.2   | 3         | 1.63%   |
| Kubuntu 20.04      | 3         | 1.63%   |
| Fedora 36          | 3         | 1.63%   |
| Zorin 16           | 2         | 1.09%   |
| Xubuntu 20.04      | 2         | 1.09%   |
| Ubuntu MATE 22.04  | 2         | 1.09%   |
| Ubuntu 20.10       | 2         | 1.09%   |
| Ubuntu 19.10       | 2         | 1.09%   |
| ROSA 12.2          | 2         | 1.09%   |
| Reborn OS          | 2         | 1.09%   |
| Manjaro 20.1       | 2         | 1.09%   |
| Manjaro            | 2         | 1.09%   |
| Linux Mint 20.3    | 2         | 1.09%   |
| Linux Mint 20.2    | 2         | 1.09%   |
| Linux Mint 19.3    | 2         | 1.09%   |
| Linux Mint 18.3    | 2         | 1.09%   |
| KDE neon 20.04     | 2         | 1.09%   |
| Kali 2023.1        | 2         | 1.09%   |
| Elementary 6.1     | 2         | 1.09%   |
| Debian 11          | 2         | 1.09%   |
| Zorin 15           | 1         | 0.54%   |
| Xubuntu 22.10      | 1         | 0.54%   |
| Xubuntu 18.04      | 1         | 0.54%   |
| Xero Rolling       | 1         | 0.54%   |
| Ubuntu Unity 16.04 | 1         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 58        | 32.04%  |
| Linux Mint   | 15        | 8.29%   |
| ROSA         | 14        | 7.73%   |
| Arch         | 11        | 6.08%   |
| Fedora       | 10        | 5.52%   |
| Manjaro      | 8         | 4.42%   |
| OpenMandriva | 7         | 3.87%   |
| ArcoLinux    | 7         | 3.87%   |
| Pop!_OS      | 6         | 3.31%   |
| Kubuntu      | 6         | 3.31%   |
| Xubuntu      | 4         | 2.21%   |
| Endless      | 4         | 2.21%   |
| Zorin        | 3         | 1.66%   |
| Ubuntu MATE  | 3         | 1.66%   |
| KDE neon     | 3         | 1.66%   |
| Elementary   | 3         | 1.66%   |
| Debian       | 3         | 1.66%   |
| SteamOS      | 2         | 1.1%    |
| Reborn OS    | 2         | 1.1%    |
| Kali         | 2         | 1.1%    |
| Clear Linux  | 2         | 1.1%    |
| Xero         | 1         | 0.55%   |
| Ubuntu Unity | 1         | 0.55%   |
| Nobara       | 1         | 0.55%   |
| MX           | 1         | 0.55%   |
| Lubuntu      | 1         | 0.55%   |
| LMDE         | 1         | 0.55%   |
| EndeavourOS  | 1         | 0.55%   |
| ALT Linux    | 1         | 0.55%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 6         | 3.03%   |
| 5.15.0-52-generic                  | 4         | 2.02%   |
| 5.4.0-47-generic                   | 3         | 1.52%   |
| 5.4.0-28-generic                   | 3         | 1.52%   |
| 5.16.7-desktop-1omv4003            | 3         | 1.52%   |
| 5.15.0-53-generic                  | 3         | 1.52%   |
| 5.10.14-desktop-1omv4002           | 3         | 1.52%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 1.52%   |
| 6.2.0-26-generic                   | 2         | 1.01%   |
| 6.1.0-kali7-amd64                  | 2         | 1.01%   |
| 5.8.0-53-generic                   | 2         | 1.01%   |
| 5.4.0-88-generic                   | 2         | 1.01%   |
| 5.4.0-65-generic                   | 2         | 1.01%   |
| 5.15.2-arch1-1                     | 2         | 1.01%   |
| 5.15.0-56-generic                  | 2         | 1.01%   |
| 5.13.0-39-generic                  | 2         | 1.01%   |
| 5.11.0-27-generic                  | 2         | 1.01%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 1.01%   |
| 5.0.0-23-generic                   | 2         | 1.01%   |
| 4.18.0-15-generic                  | 2         | 1.01%   |
| 4.15.0-45-generic                  | 2         | 1.01%   |
| 6.4.12-zen1-1-zen                  | 1         | 0.51%   |
| 6.3.12-204.fsync.fc37.x86_64       | 1         | 0.51%   |
| 6.3.1-arch1-1                      | 1         | 0.51%   |
| 6.2.7-arch1-1                      | 1         | 0.51%   |
| 6.2.6-76060206-generic             | 1         | 0.51%   |
| 6.2.0-32-generic                   | 1         | 0.51%   |
| 6.1.54-1-lts                       | 1         | 0.51%   |
| 6.1.5-arch2-1                      | 1         | 0.51%   |
| 6.1.46-1-lts                       | 1         | 0.51%   |
| 6.1.37-un-def-alt1                 | 1         | 0.51%   |
| 6.1.1-desktop-1omv2290             | 1         | 0.51%   |
| 6.0.9-arch1-1                      | 1         | 0.51%   |
| 6.0.9-300.fc37.x86_64              | 1         | 0.51%   |
| 6.0.8-1-MANJARO                    | 1         | 0.51%   |
| 6.0.5-200.fc36.x86_64              | 1         | 0.51%   |
| 6.0.2-2-MANJARO                    | 1         | 0.51%   |
| 5.9.16-1-MANJARO                   | 1         | 0.51%   |
| 5.9.13-200.fc33.x86_64             | 1         | 0.51%   |
| 5.9.10-zen1-1-zen                  | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 32        | 16.67%  |
| 5.15.0  | 17        | 8.85%   |
| 4.15.0  | 13        | 6.77%   |
| 5.8.0   | 9         | 4.69%   |
| 5.11.0  | 8         | 4.17%   |
| 5.13.0  | 7         | 3.65%   |
| 5.0.0   | 7         | 3.65%   |
| 4.18.0  | 5         | 2.6%    |
| 4.9.20  | 4         | 2.08%   |
| 6.2.0   | 3         | 1.56%   |
| 5.3.0   | 3         | 1.56%   |
| 5.19.0  | 3         | 1.56%   |
| 5.16.7  | 3         | 1.56%   |
| 5.10.14 | 3         | 1.56%   |
| 6.1.0   | 2         | 1.04%   |
| 6.0.9   | 2         | 1.04%   |
| 5.17.1  | 2         | 1.04%   |
| 5.15.2  | 2         | 1.04%   |
| 5.13.13 | 2         | 1.04%   |
| 5.13.12 | 2         | 1.04%   |
| 5.11.12 | 2         | 1.04%   |
| 5.10.74 | 2         | 1.04%   |
| 5.10.0  | 2         | 1.04%   |
| 6.4.12  | 1         | 0.52%   |
| 6.3.12  | 1         | 0.52%   |
| 6.3.1   | 1         | 0.52%   |
| 6.2.7   | 1         | 0.52%   |
| 6.2.6   | 1         | 0.52%   |
| 6.1.54  | 1         | 0.52%   |
| 6.1.5   | 1         | 0.52%   |
| 6.1.46  | 1         | 0.52%   |
| 6.1.37  | 1         | 0.52%   |
| 6.1.1   | 1         | 0.52%   |
| 6.0.8   | 1         | 0.52%   |
| 6.0.5   | 1         | 0.52%   |
| 6.0.2   | 1         | 0.52%   |
| 5.9.16  | 1         | 0.52%   |
| 5.9.13  | 1         | 0.52%   |
| 5.9.10  | 1         | 0.52%   |
| 5.9.0   | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 33        | 17.19%  |
| 5.15    | 22        | 11.46%  |
| 5.13    | 16        | 8.33%   |
| 4.15    | 13        | 6.77%   |
| 5.10    | 12        | 6.25%   |
| 5.11    | 11        | 5.73%   |
| 5.8     | 10        | 5.21%   |
| 5.0     | 8         | 4.17%   |
| 6.1     | 7         | 3.65%   |
| 4.9     | 7         | 3.65%   |
| 5.16    | 6         | 3.13%   |
| 6.2     | 5         | 2.6%    |
| 6.0     | 5         | 2.6%    |
| 4.18    | 5         | 2.6%    |
| 5.9     | 4         | 2.08%   |
| 5.19    | 4         | 2.08%   |
| 5.17    | 4         | 2.08%   |
| 5.3     | 3         | 1.56%   |
| 5.14    | 3         | 1.56%   |
| 5.12    | 3         | 1.56%   |
| 6.3     | 2         | 1.04%   |
| 4.19    | 2         | 1.04%   |
| 6.4     | 1         | 0.52%   |
| 5.6     | 1         | 0.52%   |
| 5.5     | 1         | 0.52%   |
| 4.4     | 1         | 0.52%   |
| 4.10    | 1         | 0.52%   |
| 4.1     | 1         | 0.52%   |
| 3.16    | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 173       | 97.19%  |
| i686   | 5         | 2.81%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 64        | 35.36%  |
| KDE5       | 28        | 15.47%  |
| Unknown    | 26        | 14.36%  |
| XFCE       | 17        | 9.39%   |
| X-Cinnamon | 11        | 6.08%   |
| KDE4       | 8         | 4.42%   |
| MATE       | 7         | 3.87%   |
| Pantheon   | 3         | 1.66%   |
| KDE        | 3         | 1.66%   |
| i3         | 3         | 1.66%   |
| Unity      | 2         | 1.1%    |
| LXQt       | 2         | 1.1%    |
| LXDE       | 2         | 1.1%    |
| awesome    | 2         | 1.1%    |
| openbox    | 1         | 0.55%   |
| Cinnamon   | 1         | 0.55%   |
| Budgie     | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 141       | 79.21%  |
| Wayland | 26        | 14.61%  |
| Unknown | 10        | 5.62%   |
| Tty     | 1         | 0.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 84        | 46.41%  |
| SDDM    | 30        | 16.57%  |
| GDM3    | 19        | 10.5%   |
| GDM     | 19        | 10.5%   |
| LightDM | 12        | 6.63%   |
| TDM     | 9         | 4.97%   |
| KDM     | 8         | 4.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 88        | 48.89%  |
| Unknown         | 33        | 18.33%  |
| et_EE           | 27        | 15%     |
| ru_RU           | 17        | 9.44%   |
| en_GB           | 6         | 3.33%   |
| de_DE           | 2         | 1.11%   |
| uk_UA           | 1         | 0.56%   |
| ru_UA           | 1         | 0.56%   |
| fr_FR           | 1         | 0.56%   |
| es_MX           | 1         | 0.56%   |
| en_US.iso885915 | 1         | 0.56%   |
| en_DK           | 1         | 0.56%   |
| C               | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 92        | 50.55%  |
| BIOS | 90        | 49.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 134       | 75.28%  |
| Btrfs   | 20        | 11.24%  |
| Unknown | 12        | 6.74%   |
| Overlay | 7         | 3.93%   |
| Xfs     | 3         | 1.69%   |
| Zfs     | 1         | 0.56%   |
| Ext3    | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 90        | 50.28%  |
| GPT     | 68        | 37.99%  |
| MBR     | 21        | 11.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 164       | 91.11%  |
| Yes       | 16        | 8.89%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 128       | 70.72%  |
| Yes       | 53        | 29.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 56        | 31.46%  |
| Hewlett-Packard     | 32        | 17.98%  |
| Dell                | 23        | 12.92%  |
| ASUSTek Computer    | 20        | 11.24%  |
| Samsung Electronics | 7         | 3.93%   |
| Acer                | 6         | 3.37%   |
| MSI                 | 5         | 2.81%   |
| Apple               | 4         | 2.25%   |
| Fujitsu             | 3         | 1.69%   |
| Valve               | 2         | 1.12%   |
| Timi                | 2         | 1.12%   |
| Quanta              | 2         | 1.12%   |
| Notebook            | 2         | 1.12%   |
| Alienware           | 2         | 1.12%   |
| TUXEDO              | 1         | 0.56%   |
| Toshiba             | 1         | 0.56%   |
| Packard Bell        | 1         | 0.56%   |
| mPTech              | 1         | 0.56%   |
| Intel               | 1         | 0.56%   |
| HUAWEI              | 1         | 0.56%   |
| GPD                 | 1         | 0.56%   |
| Gigabyte Technology | 1         | 0.56%   |
| Getac               | 1         | 0.56%   |
| Fujitsu Siemens     | 1         | 0.56%   |
| Framework           | 1         | 0.56%   |
| Chuwi               | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 2         | 1.12%   |
| Quanta TWH                                            | 2         | 1.12%   |
| Lenovo Y50-70 20378                                   | 2         | 1.12%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 1.12%   |
| HP Pavilion dv7                                       | 2         | 1.12%   |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 1.12%   |
| HP EliteBook 8470p                                    | 2         | 1.12%   |
| HP EliteBook 8460p                                    | 2         | 1.12%   |
| HP EliteBook 840 G2                                   | 2         | 1.12%   |
| Dell Inspiron N5110                                   | 2         | 1.12%   |
| Alienware 17                                          | 2         | 1.12%   |
| TUXEDO Book BA1510                                    | 1         | 0.56%   |
| Toshiba Satellite L855                                | 1         | 0.56%   |
| Timi RedmiBook 16                                     | 1         | 0.56%   |
| Timi RedmiBook 14 II                                  | 1         | 0.56%   |
| Samsung R410                                          | 1         | 0.56%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.56%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.56%   |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.56%   |
| Samsung 535U3C                                        | 1         | 0.56%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.56%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.56%   |
| Packard Bell EasyNote TK87                            | 1         | 0.56%   |
| Notebook W35xSS_370SS                                 | 1         | 0.56%   |
| Notebook N150SD/N155SD                                | 1         | 0.56%   |
| MSI GT70 2OC/2OD                                      | 1         | 0.56%   |
| MSI GS75 Stealth 8SE                                  | 1         | 0.56%   |
| MSI GP62M 7RDX                                        | 1         | 0.56%   |
| MSI GL72 6QD                                          | 1         | 0.56%   |
| MSI GF63 Thin 10SCXR                                  | 1         | 0.56%   |
| mPTech ARC 11.6 128GB HD                              | 1         | 0.56%   |
| Lenovo Y720-15IKB 80VR                                | 1         | 0.56%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.56%   |
| Lenovo V110-15ISK 80TL                                | 1         | 0.56%   |
| Lenovo ThinkPad X260 20F5S84400                       | 1         | 0.56%   |
| Lenovo ThinkPad X240 20AMA0W706                       | 1         | 0.56%   |
| Lenovo ThinkPad X220 4291R30                          | 1         | 0.56%   |
| Lenovo ThinkPad X220 429136G                          | 1         | 0.56%   |
| Lenovo ThinkPad X201 3680CG7                          | 1         | 0.56%   |
| Lenovo ThinkPad X13 Gen 1 20UF0020MX                  | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 42        | 23.6%   |
| HP EliteBook          | 12        | 6.74%   |
| HP Pavilion           | 7         | 3.93%   |
| Dell Latitude         | 6         | 3.37%   |
| Dell Inspiron         | 6         | 3.37%   |
| Lenovo IdeaPad        | 4         | 2.25%   |
| Dell Precision        | 4         | 2.25%   |
| ASUS VivoBook         | 4         | 2.25%   |
| Acer Aspire           | 4         | 2.25%   |
| Lenovo Legion         | 3         | 1.69%   |
| Fujitsu LIFEBOOK      | 3         | 1.69%   |
| Dell XPS              | 3         | 1.69%   |
| Valve Jupiter         | 2         | 1.12%   |
| Timi RedmiBook        | 2         | 1.12%   |
| Samsung 900X3C        | 2         | 1.12%   |
| Quanta TWH            | 2         | 1.12%   |
| Lenovo Y50-70         | 2         | 1.12%   |
| HP ProBook            | 2         | 1.12%   |
| HP Presario           | 2         | 1.12%   |
| HP OMEN               | 2         | 1.12%   |
| HP ENVY               | 2         | 1.12%   |
| HP Compaq             | 2         | 1.12%   |
| Dell Vostro           | 2         | 1.12%   |
| ASUS ZenBook          | 2         | 1.12%   |
| Alienware 17          | 2         | 1.12%   |
| TUXEDO Book           | 1         | 0.56%   |
| Toshiba Satellite     | 1         | 0.56%   |
| Samsung R410          | 1         | 0.56%   |
| Samsung 770Z5E        | 1         | 0.56%   |
| Samsung 535U3C        | 1         | 0.56%   |
| Samsung 300E5EV       | 1         | 0.56%   |
| Samsung 275E4E        | 1         | 0.56%   |
| Packard Bell EasyNote | 1         | 0.56%   |
| Notebook W35xSS       | 1         | 0.56%   |
| Notebook N150SD       | 1         | 0.56%   |
| MSI GT70              | 1         | 0.56%   |
| MSI GS75              | 1         | 0.56%   |
| MSI GP62M             | 1         | 0.56%   |
| MSI GL72              | 1         | 0.56%   |
| MSI GF63              | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 21        | 11.8%   |
| 2013 | 21        | 11.8%   |
| 2011 | 18        | 10.11%  |
| 2019 | 15        | 8.43%   |
| 2018 | 15        | 8.43%   |
| 2014 | 13        | 7.3%    |
| 2015 | 12        | 6.74%   |
| 2012 | 11        | 6.18%   |
| 2017 | 9         | 5.06%   |
| 2022 | 7         | 3.93%   |
| 2010 | 7         | 3.93%   |
| 2008 | 7         | 3.93%   |
| 2007 | 7         | 3.93%   |
| 2021 | 6         | 3.37%   |
| 2016 | 6         | 3.37%   |
| 2009 | 2         | 1.12%   |
| 2006 | 1         | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 178       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 163       | 91.06%  |
| Enabled  | 16        | 8.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 178       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 41        | 22.78%  |
| 4.01-8.0    | 40        | 22.22%  |
| 16.01-24.0  | 33        | 18.33%  |
| 3.01-4.0    | 32        | 17.78%  |
| 32.01-64.0  | 10        | 5.56%   |
| 24.01-32.0  | 8         | 4.44%   |
| 2.01-3.0    | 8         | 4.44%   |
| 1.01-2.0    | 6         | 3.33%   |
| 64.01-256.0 | 2         | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 64        | 33.86%  |
| 2.01-3.0   | 44        | 23.28%  |
| 4.01-8.0   | 36        | 19.05%  |
| 3.01-4.0   | 23        | 12.17%  |
| 8.01-16.0  | 10        | 5.29%   |
| 0.51-1.0   | 10        | 5.29%   |
| 24.01-32.0 | 1         | 0.53%   |
| 16.01-24.0 | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 139       | 76.37%  |
| 2      | 35        | 19.23%  |
| 3      | 6         | 3.3%    |
| 5      | 1         | 0.55%   |
| 4      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 118       | 65.19%  |
| Yes       | 63        | 34.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 85.47%  |
| No        | 26        | 14.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 177       | 99.44%  |
| No        | 1         | 0.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 78.77%  |
| No        | 38        | 21.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Estonia | 178       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Tallinn           | 115       | 63.89%  |
| Tartu             | 17        | 9.44%   |
| Pärnu            | 8         | 4.44%   |
| Narva             | 6         | 3.33%   |
| Rapla             | 4         | 2.22%   |
| Rakvere           | 3         | 1.67%   |
| Vinni             | 2         | 1.11%   |
| Saku              | 2         | 1.11%   |
| Otepaeae          | 2         | 1.11%   |
| Maardu            | 2         | 1.11%   |
| Keila             | 2         | 1.11%   |
| Viljandi          | 1         | 0.56%   |
| Viimsi            | 1         | 0.56%   |
| Vatla             | 1         | 0.56%   |
| Tabasalu          | 1         | 0.56%   |
| Sillamäe         | 1         | 0.56%   |
| Sauga             | 1         | 0.56%   |
| Rae Parish        | 1         | 0.56%   |
| Põlva            | 1         | 0.56%   |
| Pohja-Sakala vald | 1         | 0.56%   |
| Palamuse          | 1         | 0.56%   |
| Laagri            | 1         | 0.56%   |
| Kärdla           | 1         | 0.56%   |
| Kaeina            | 1         | 0.56%   |
| Jüri             | 1         | 0.56%   |
| Jõhvi            | 1         | 0.56%   |
| Jõgeva           | 1         | 0.56%   |
| AEaesmaee         | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 50        | 58     | 22.73%  |
| Seagate                     | 28        | 31     | 12.73%  |
| Toshiba                     | 17        | 17     | 7.73%   |
| WDC                         | 15        | 17     | 6.82%   |
| Kingston                    | 14        | 15     | 6.36%   |
| SK hynix                    | 13        | 17     | 5.91%   |
| Intel                       | 8         | 9      | 3.64%   |
| Unknown                     | 7         | 7      | 3.18%   |
| SanDisk                     | 7         | 9      | 3.18%   |
| HGST                        | 7         | 8      | 3.18%   |
| Hitachi                     | 5         | 5      | 2.27%   |
| Patriot                     | 4         | 5      | 1.82%   |
| Micron Technology           | 4         | 4      | 1.82%   |
| Lenovo                      | 3         | 3      | 1.36%   |
| Crucial                     | 3         | 3      | 1.36%   |
| A-DATA Technology           | 3         | 3      | 1.36%   |
| Transcend                   | 2         | 5      | 0.91%   |
| Phison Electronics          | 2         | 2      | 0.91%   |
| LITEONIT                    | 2         | 2      | 0.91%   |
| KIOXIA                      | 2         | 3      | 0.91%   |
| KingSpec                    | 2         | 3      | 0.91%   |
| Gigabyte Technology         | 2         | 3      | 0.91%   |
| Fujitsu                     | 2         | 2      | 0.91%   |
| China                       | 2         | 2      | 0.91%   |
| Apacer                      | 2         | 2      | 0.91%   |
| Team                        | 1         | 1      | 0.45%   |
| SPCC                        | 1         | 1      | 0.45%   |
| PNY                         | 1         | 1      | 0.45%   |
| Phison                      | 1         | 1      | 0.45%   |
| Netac                       | 1         | 1      | 0.45%   |
| Lexar                       | 1         | 1      | 0.45%   |
| Kingston Technology Company | 1         | 1      | 0.45%   |
| Intenso                     | 1         | 1      | 0.45%   |
| HUAWEI                      | 1         | 1      | 0.45%   |
| External                    | 1         | 1      | 0.45%   |
| ASMT109x                    | 1         | 2      | 0.45%   |
| Apple                       | 1         | 1      | 0.45%   |
| ADATA Technology            | 1         | 1      | 0.45%   |
| Unknown                     | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 1.32%   |
| Samsung SSD 850 EVO 500GB                           | 3         | 1.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 1.32%   |
| HGST HTS721010A9E630 1TB                            | 3         | 1.32%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 2         | 0.88%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB                | 2         | 0.88%   |
| Unknown MMC Card  16GB                              | 2         | 0.88%   |
| Toshiba NVMe SSD Drive 512GB                        | 2         | 0.88%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.88%   |
| SK hynix NVMe SSD Drive 512GB                       | 2         | 0.88%   |
| SK hynix NVMe SSD Drive 256GB                       | 2         | 0.88%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 0.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.88%   |
| Seagate BUP Portable 5TB                            | 2         | 0.88%   |
| SanDisk SD8SBAT256G1122 256GB SSD                   | 2         | 0.88%   |
| Samsung SSD 970 EVO Plus 500GB                      | 2         | 0.88%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2         | 0.88%   |
| Samsung SSD 850 EVO M.2 500GB                       | 2         | 0.88%   |
| Samsung NVMe SSD Drive 512GB                        | 2         | 0.88%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 0.88%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 0.88%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 2         | 0.88%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD                | 2         | 0.88%   |
| Patriot Burst 240GB SSD                             | 2         | 0.88%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                 | 2         | 0.88%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.88%   |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.88%   |
| Intel SSDPEKKF256G8L 256GB                          | 2         | 0.88%   |
| HGST HTS541010A9E680 1TB                            | 2         | 0.88%   |
| WDC WDS500G2B0B 500GB SSD                           | 1         | 0.44%   |
| WDC WDS500G1X0E-00AFY0 500GB                        | 1         | 0.44%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                    | 1         | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.44%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 0.44%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 0.44%   |
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 0.44%   |
| WDC WD1200BEVS-08RST2 120GB                         | 1         | 0.44%   |
| WDC WD10SPZX-00Z10T0 1TB                            | 1         | 0.44%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                  | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 27        | 30     | 49.09%  |
| Toshiba  | 8         | 8      | 14.55%  |
| HGST     | 7         | 8      | 12.73%  |
| WDC      | 5         | 6      | 9.09%   |
| Hitachi  | 5         | 5      | 9.09%   |
| Fujitsu  | 2         | 2      | 3.64%   |
| External | 1         | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 32     | 32.18%  |
| Kingston            | 12        | 13     | 13.79%  |
| SanDisk             | 5         | 7      | 5.75%   |
| SK hynix            | 4         | 4      | 4.6%    |
| Patriot             | 4         | 5      | 4.6%    |
| Micron Technology   | 4         | 4      | 4.6%    |
| WDC                 | 3         | 4      | 3.45%   |
| Crucial             | 3         | 3      | 3.45%   |
| A-DATA Technology   | 3         | 3      | 3.45%   |
| Transcend           | 2         | 5      | 2.3%    |
| Toshiba             | 2         | 2      | 2.3%    |
| LITEONIT            | 2         | 2      | 2.3%    |
| KingSpec            | 2         | 3      | 2.3%    |
| Intel               | 2         | 3      | 2.3%    |
| China               | 2         | 2      | 2.3%    |
| Apacer              | 2         | 2      | 2.3%    |
| Team                | 1         | 1      | 1.15%   |
| SPCC                | 1         | 1      | 1.15%   |
| Netac               | 1         | 1      | 1.15%   |
| Lexar               | 1         | 1      | 1.15%   |
| Intenso             | 1         | 1      | 1.15%   |
| Gigabyte Technology | 1         | 2      | 1.15%   |
| Apple               | 1         | 1      | 1.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 77        | 102    | 38.31%  |
| NVMe    | 60        | 76     | 29.85%  |
| HDD     | 53        | 60     | 26.37%  |
| MMC     | 8         | 8      | 3.98%   |
| Unknown | 3         | 4      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 119       | 157    | 60.71%  |
| NVMe | 60        | 76     | 30.61%  |
| SAS  | 9         | 9      | 4.59%   |
| MMC  | 8         | 8      | 4.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 94        | 115    | 69.63%  |
| 0.51-1.0   | 35        | 41     | 25.93%  |
| 1.01-2.0   | 3         | 3      | 2.22%   |
| 4.01-10.0  | 2         | 2      | 1.48%   |
| 3.01-4.0   | 1         | 1      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 65        | 35.33%  |
| 251-500        | 39        | 21.2%   |
| 501-1000       | 25        | 13.59%  |
| 1-20           | 16        | 8.7%    |
| 51-100         | 13        | 7.07%   |
| 1001-2000      | 9         | 4.89%   |
| Unknown        | 6         | 3.26%   |
| More than 3000 | 5         | 2.72%   |
| 21-50          | 5         | 2.72%   |
| 2001-3000      | 1         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 78        | 41.27%  |
| 21-50          | 30        | 15.87%  |
| 101-250        | 26        | 13.76%  |
| 51-100         | 22        | 11.64%  |
| 251-500        | 16        | 8.47%   |
| 501-1000       | 7         | 3.7%    |
| Unknown        | 6         | 3.17%   |
| More than 3000 | 2         | 1.06%   |
| 2001-3000      | 1         | 0.53%   |
| 1001-2000      | 1         | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 6.25%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 6.25%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 6.25%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 6.25%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 6.25%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 6.25%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 6.25%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 6.25%   |
| Netac SSD 720GB                                     | 1         | 1      | 6.25%   |
| Micron Technology MTFDDAK256TDL-1AW15ABHA 256GB SSD | 1         | 1      | 6.25%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 6.25%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 6.25%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 6.25%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 6.25%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 6.25%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 7         | 7      | 43.75%  |
| Micron Technology | 2         | 2      | 12.5%   |
| WDC               | 1         | 1      | 6.25%   |
| Netac             | 1         | 1      | 6.25%   |
| Kingston          | 1         | 1      | 6.25%   |
| Hitachi           | 1         | 1      | 6.25%   |
| HGST              | 1         | 1      | 6.25%   |
| Fujitsu           | 1         | 1      | 6.25%   |
| Crucial           | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 63.64%  |
| WDC     | 1         | 1      | 9.09%   |
| Hitachi | 1         | 1      | 9.09%   |
| HGST    | 1         | 1      | 9.09%   |
| Fujitsu | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 68.75%  |
| SSD  | 5         | 5      | 31.25%  |

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
| Detected | 101       | 150    | 54.3%   |
| Works    | 70        | 84     | 37.63%  |
| Malfunc  | 15        | 16     | 8.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 128       | 60.66%  |
| Samsung Electronics          | 23        | 10.9%   |
| AMD                          | 20        | 9.48%   |
| SK hynix                     | 9         | 4.27%   |
| SanDisk                      | 8         | 3.79%   |
| Toshiba America Info Systems | 6         | 2.84%   |
| Phison Electronics           | 4         | 1.9%    |
| Lenovo                       | 3         | 1.42%   |
| KIOXIA                       | 3         | 1.42%   |
| Kingston Technology Company  | 3         | 1.42%   |
| VIA Technologies             | 1         | 0.47%   |
| Nvidia                       | 1         | 0.47%   |
| Marvell Technology Group     | 1         | 0.47%   |
| ADATA Technology             | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16        | 7.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 7.05%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 7.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 6.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 5.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 3.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 3.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 3.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 3.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 2.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 2.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 2.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.32%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 3         | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.32%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.32%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.88%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.88%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.88%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.88%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 0.88%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 0.88%   |
| Intel SSD 660P Series                                                          | 2         | 0.88%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 0.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.88%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 2         | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 0.88%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.44%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 0.44%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 136       | 62.39%  |
| NVMe | 61        | 27.98%  |
| IDE  | 14        | 6.42%   |
| RAID | 7         | 3.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 145       | 81.46%  |
| AMD    | 33        | 18.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 3.93%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.25%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.69%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 1.69%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 3         | 1.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.69%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 3         | 1.69%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.12%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.12%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 1.12%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 1.12%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.12%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.12%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.12%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 1.12%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.12%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.12%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.12%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.12%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.12%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.12%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.12%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 2         | 1.12%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.12%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.12%   |
| AMD Custom APU 0405                           | 2         | 1.12%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.56%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.56%   |
| Intel Pentium M processor 2.13GHz             | 1         | 0.56%   |
| Intel Pentium M processor 1.50GHz             | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 50        | 28.09%  |
| Intel Core i5                  | 48        | 26.97%  |
| Other                          | 9         | 5.06%   |
| Intel Core i3                  | 9         | 5.06%   |
| AMD Ryzen 5                    | 9         | 5.06%   |
| Intel Core 2 Duo               | 8         | 4.49%   |
| Intel Celeron                  | 8         | 4.49%   |
| AMD Ryzen 7                    | 7         | 3.93%   |
| Intel Pentium                  | 3         | 1.69%   |
| AMD Ryzen 7 PRO                | 3         | 1.69%   |
| Intel Pentium M                | 2         | 1.12%   |
| Intel Celeron Dual-Core        | 2         | 1.12%   |
| Intel Atom                     | 2         | 1.12%   |
| Intel Xeon                     | 1         | 0.56%   |
| Intel Pentium Silver           | 1         | 0.56%   |
| Intel Pentium Dual             | 1         | 0.56%   |
| Intel Core i9                  | 1         | 0.56%   |
| Intel Core 2                   | 1         | 0.56%   |
| Intel Celeron M                | 1         | 0.56%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.56%   |
| AMD Ryzen 5 PRO                | 1         | 0.56%   |
| AMD Ryzen 3 PRO                | 1         | 0.56%   |
| AMD Ryzen 3                    | 1         | 0.56%   |
| AMD E2                         | 1         | 0.56%   |
| AMD E                          | 1         | 0.56%   |
| AMD C-60                       | 1         | 0.56%   |
| AMD Athlon II Dual-Core        | 1         | 0.56%   |
| AMD Athlon 64 X2               | 1         | 0.56%   |
| AMD A8                         | 1         | 0.56%   |
| AMD A6                         | 1         | 0.56%   |
| AMD A4                         | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 85        | 47.75%  |
| 4       | 57        | 32.02%  |
| 6       | 17        | 9.55%   |
| 8       | 9         | 5.06%   |
| 1       | 7         | 3.93%   |
| Unknown | 2         | 1.12%   |
| 12      | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 178       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 135       | 75.42%  |
| 1       | 42        | 23.46%  |
| Unknown | 2         | 1.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 175       | 98.31%  |
| 32-bit         | 2         | 1.12%   |
| Unknown        | 1         | 0.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 22.53%  |
| 0x306a9    | 13        | 7.14%   |
| 0x306c3    | 12        | 6.59%   |
| 0x206a7    | 12        | 6.59%   |
| 0x806ea    | 8         | 4.4%    |
| 0x40651    | 7         | 3.85%   |
| 0x08600106 | 7         | 3.85%   |
| 0x306d4    | 6         | 3.3%    |
| 0x906e9    | 5         | 2.75%   |
| 0x806ec    | 5         | 2.75%   |
| 0x20655    | 5         | 2.75%   |
| 0xa0652    | 4         | 2.2%    |
| 0x806c1    | 4         | 2.2%    |
| 0x6fb      | 4         | 2.2%    |
| 0x506e3    | 4         | 2.2%    |
| 0x1067a    | 4         | 2.2%    |
| 0x906ea    | 3         | 1.65%   |
| 0x6fd      | 3         | 1.65%   |
| 0x406e3    | 3         | 1.65%   |
| 0x08108102 | 3         | 1.65%   |
| 0x05000119 | 3         | 1.65%   |
| 0x806e9    | 2         | 1.1%    |
| 0x706a1    | 2         | 1.1%    |
| 0x6d8      | 2         | 1.1%    |
| 0x30678    | 2         | 1.1%    |
| 0x0a50000c | 2         | 1.1%    |
| 0x906ed    | 1         | 0.55%   |
| 0x806eb    | 1         | 0.55%   |
| 0x806d1    | 1         | 0.55%   |
| 0x706a8    | 1         | 0.55%   |
| 0x6fa      | 1         | 0.55%   |
| 0x6f6      | 1         | 0.55%   |
| 0x30661    | 1         | 0.55%   |
| 0x106ca    | 1         | 0.55%   |
| 0x0a404102 | 1         | 0.55%   |
| 0x08608103 | 1         | 0.55%   |
| 0x08600104 | 1         | 0.55%   |
| 0x08600103 | 1         | 0.55%   |
| 0x0810100b | 1         | 0.55%   |
| 0x06001119 | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 17.42%  |
| Haswell          | 26        | 14.61%  |
| IvyBridge        | 15        | 8.43%   |
| SandyBridge      | 14        | 7.87%   |
| Zen 2            | 11        | 6.18%   |
| Core             | 9         | 5.06%   |
| Broadwell        | 9         | 5.06%   |
| Skylake          | 8         | 4.49%   |
| Westmere         | 7         | 3.93%   |
| Unknown          | 7         | 3.93%   |
| TigerLake        | 5         | 2.81%   |
| Penryn           | 4         | 2.25%   |
| CometLake        | 4         | 2.25%   |
| Zen+             | 3         | 1.69%   |
| Goldmont plus    | 3         | 1.69%   |
| Bobcat           | 3         | 1.69%   |
| Zen 3            | 2         | 1.12%   |
| Zen              | 2         | 1.12%   |
| Silvermont       | 2         | 1.12%   |
| P6               | 2         | 1.12%   |
| Bonnell          | 2         | 1.12%   |
| Steamroller      | 1         | 0.56%   |
| Piledriver       | 1         | 0.56%   |
| K8 Hammer        | 1         | 0.56%   |
| K8 & K10 hybrid  | 1         | 0.56%   |
| K10              | 1         | 0.56%   |
| Icelake          | 1         | 0.56%   |
| Goldmont         | 1         | 0.56%   |
| Excavator        | 1         | 0.56%   |
| Alderlake Hybrid | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 135       | 55.56%  |
| Nvidia           | 68        | 27.98%  |
| AMD              | 39        | 16.05%  |
| VIA Technologies | 1         | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 14        | 5.58%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 14        | 5.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 5.18%   |
| Intel UHD Graphics 620                                                        | 11        | 4.38%   |
| AMD Renoir                                                                    | 10        | 3.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 3.59%   |
| Intel HD Graphics 5500                                                        | 7         | 2.79%   |
| Intel Core Processor Integrated Graphics Controller                           | 7         | 2.79%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 1.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 1.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 5         | 1.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 1.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 5         | 1.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 5         | 1.99%   |
| Intel HD Graphics 630                                                         | 5         | 1.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 1.99%   |
| Intel HD Graphics 530                                                         | 4         | 1.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.59%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 3         | 1.2%    |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 1.2%    |
| Nvidia GK208M [GeForce GT 730M]                                               | 3         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 1.2%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.8%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 0.8%    |
| Nvidia GP108GLM [Quadro P520]                                                 | 2         | 0.8%    |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 0.8%    |
| Nvidia GM107M [GeForce GTX 860M]                                              | 2         | 0.8%    |
| Nvidia GM107GLM [Quadro M2000M]                                               | 2         | 0.8%    |
| Nvidia GF108M [GeForce GT 525M]                                               | 2         | 0.8%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 0.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 0.8%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 0.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 0.8%    |
| Intel HD Graphics 620                                                         | 2         | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 0.8%    |
| AMD VanGogh [AMD Custom GPU 0405]                                             | 2         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 73        | 41.01%  |
| Intel + Nvidia | 57        | 32.02%  |
| 1 x AMD        | 30        | 16.85%  |
| 1 x Nvidia     | 7         | 3.93%   |
| Intel + AMD    | 5         | 2.81%   |
| AMD + Nvidia   | 3         | 1.69%   |
| 2 x Nvidia     | 1         | 0.56%   |
| 2 x AMD        | 1         | 0.56%   |
| 1 x VIA        | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 136       | 75.14%  |
| Proprietary | 41        | 22.65%  |
| Unknown     | 4         | 2.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 52.51%  |
| 1.01-2.0   | 34        | 18.99%  |
| 0.01-0.5   | 21        | 11.73%  |
| 3.01-4.0   | 12        | 6.7%    |
| 0.51-1.0   | 12        | 6.7%    |
| 5.01-6.0   | 4         | 2.23%   |
| 2.01-3.0   | 1         | 0.56%   |
| 8.01-16.0  | 1         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 36        | 16.67%  |
| Chimei Innolux          | 33        | 15.28%  |
| LG Display              | 25        | 11.57%  |
| BOE                     | 22        | 10.19%  |
| Dell                    | 20        | 9.26%   |
| Samsung Electronics     | 19        | 8.8%    |
| Chi Mei Optoelectronics | 11        | 5.09%   |
| Sharp                   | 7         | 3.24%   |
| Lenovo                  | 5         | 2.31%   |
| Goldstar                | 5         | 2.31%   |
| Hewlett-Packard         | 4         | 1.85%   |
| Apple                   | 4         | 1.85%   |
| Sony                    | 3         | 1.39%   |
| PANDA                   | 3         | 1.39%   |
| LG Philips              | 3         | 1.39%   |
| CPT                     | 2         | 0.93%   |
| ViewSonic               | 1         | 0.46%   |
| Toshiba                 | 1         | 0.46%   |
| Seiko/Epson             | 1         | 0.46%   |
| Philips                 | 1         | 0.46%   |
| Panasonic               | 1         | 0.46%   |
| Lenovo Group Limited    | 1         | 0.46%   |
| KDB                     | 1         | 0.46%   |
| JDI                     | 1         | 0.46%   |
| InfoVision              | 1         | 0.46%   |
| CSO                     | 1         | 0.46%   |
| ASUSTek Computer        | 1         | 0.46%   |
| AOC                     | 1         | 0.46%   |
| Analogix                | 1         | 0.46%   |
| Acer                    | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 5         | 2.24%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 4         | 1.79%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 3         | 1.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 1.35%   |
| Sony TV SNYDB01 1920x1080                                                 | 2         | 0.9%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.9%    |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 0.9%    |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.9%    |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 2         | 0.9%    |
| Dell P3421W DELA1A8 3440x1440 800x335mm 34.1-inch                         | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.9%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 2         | 0.9%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.9%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 2         | 0.9%    |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 0.9%    |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 0.9%    |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 2         | 0.9%    |
| ViewSonic VP2030 SERIES VSC131C 1600x1200 408x306mm 20.1-inch             | 1         | 0.45%   |
| Toshiba no-audio-HD TSB8888 1080x1920 1080x1920mm 86.7-inch               | 1         | 0.45%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.45%   |
| Sharp LQ133M1JW40 SHP10CD 1920x1080 294x165mm 13.3-inch                   | 1         | 0.45%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 0.45%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 1         | 0.45%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                   | 1         | 0.45%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                   | 1         | 0.45%   |
| Seiko/Epson LCD Monitor 1920x1080                                         | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch      | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM030E 1680x1050 474x296mm 22.0-inch      | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch      | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 87        | 42.86%  |
| 1366x768 (WXGA)    | 45        | 22.17%  |
| 1600x900 (HD+)     | 15        | 7.39%   |
| 3840x2160 (4K)     | 12        | 5.91%   |
| 1280x800 (WXGA)    | 11        | 5.42%   |
| 1920x1200 (WUXGA)  | 7         | 3.45%   |
| 2560x1600          | 6         | 2.96%   |
| 1680x1050 (WSXGA+) | 5         | 2.46%   |
| 3440x1440          | 3         | 1.48%   |
| 2560x1440 (QHD)    | 3         | 1.48%   |
| 1440x900 (WXGA+)   | 2         | 0.99%   |
| 1280x1024 (SXGA)   | 2         | 0.99%   |
| 800x1280           | 1         | 0.49%   |
| 3840x2400          | 1         | 0.49%   |
| 2560x1080          | 1         | 0.49%   |
| 2256x1504          | 1         | 0.49%   |
| 1600x1200          | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 84        | 38.36%  |
| 14      | 30        | 13.7%   |
| 13      | 24        | 10.96%  |
| 17      | 15        | 6.85%   |
| 24      | 13        | 5.94%   |
| 12      | 8         | 3.65%   |
| 27      | 7         | 3.2%    |
| 34      | 4         | 1.83%   |
| 16      | 4         | 1.83%   |
| Unknown | 4         | 1.83%   |
| 72      | 3         | 1.37%   |
| 23      | 3         | 1.37%   |
| 22      | 3         | 1.37%   |
| 40      | 2         | 0.91%   |
| 86      | 1         | 0.46%   |
| 84      | 1         | 0.46%   |
| 65      | 1         | 0.46%   |
| 54      | 1         | 0.46%   |
| 43      | 1         | 0.46%   |
| 38      | 1         | 0.46%   |
| 31      | 1         | 0.46%   |
| 29      | 1         | 0.46%   |
| 21      | 1         | 0.46%   |
| 20      | 1         | 0.46%   |
| 19      | 1         | 0.46%   |
| 11      | 1         | 0.46%   |
| 10      | 1         | 0.46%   |
| 9       | 1         | 0.46%   |
| 3       | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 125       | 57.6%   |
| 201-300     | 25        | 11.52%  |
| 501-600     | 22        | 10.14%  |
| 351-400     | 17        | 7.83%   |
| 401-500     | 5         | 2.3%    |
| 701-800     | 4         | 1.84%   |
| 1501-2000   | 4         | 1.84%   |
| Unknown     | 4         | 1.84%   |
| 801-900     | 3         | 1.38%   |
| 601-700     | 3         | 1.38%   |
| 1001-1500   | 3         | 1.38%   |
| 901-1000    | 1         | 0.46%   |
| 1-100       | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 150       | 77.72%  |
| 16/10   | 28        | 14.51%  |
| 21/9    | 4         | 2.07%   |
| 3/2     | 3         | 1.55%   |
| Unknown | 3         | 1.55%   |
| 5/4     | 2         | 1.04%   |
| 6/5     | 1         | 0.52%   |
| 4/3     | 1         | 0.52%   |
| 0.56    | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 81        | 37.16%  |
| 81-90          | 42        | 19.27%  |
| 201-250        | 15        | 6.88%   |
| 121-130        | 13        | 5.96%   |
| 71-80          | 12        | 5.5%    |
| 61-70          | 8         | 3.67%   |
| More than 1000 | 7         | 3.21%   |
| 301-350        | 7         | 3.21%   |
| 111-120        | 7         | 3.21%   |
| 351-500        | 6         | 2.75%   |
| 251-300        | 4         | 1.83%   |
| 501-1000       | 4         | 1.83%   |
| Unknown        | 4         | 1.83%   |
| 41-50          | 2         | 0.92%   |
| 151-200        | 2         | 0.92%   |
| 51-60          | 1         | 0.46%   |
| 1-40           | 1         | 0.46%   |
| 141-150        | 1         | 0.46%   |
| 131-140        | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 90        | 41.86%  |
| 101-120       | 51        | 23.72%  |
| 51-100        | 39        | 18.14%  |
| 161-240       | 17        | 7.91%   |
| More than 240 | 8         | 3.72%   |
| 1-50          | 6         | 2.79%   |
| Unknown       | 4         | 1.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 135       | 74.18%  |
| 2     | 39        | 21.43%  |
| 3     | 7         | 3.85%   |
| 0     | 1         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 108       | 37.89%  |
| Realtek Semiconductor             | 80        | 28.07%  |
| Qualcomm Atheros                  | 38        | 13.33%  |
| Broadcom                          | 16        | 5.61%   |
| Ralink                            | 4         | 1.4%    |
| MediaTek                          | 4         | 1.4%    |
| Lenovo                            | 4         | 1.4%    |
| Ericsson Business Mobile Networks | 4         | 1.4%    |
| TP-Link                           | 3         | 1.05%   |
| Sierra Wireless                   | 3         | 1.05%   |
| Fibocom                           | 3         | 1.05%   |
| Broadcom Limited                  | 3         | 1.05%   |
| JMicron Technology                | 2         | 0.7%    |
| Huawei Technologies               | 2         | 0.7%    |
| Hewlett-Packard                   | 2         | 0.7%    |
| ASIX Electronics                  | 2         | 0.7%    |
| VIA Technologies                  | 1         | 0.35%   |
| Van Ooijen Technische Informatica | 1         | 0.35%   |
| OPPO Electronics                  | 1         | 0.35%   |
| Nvidia                            | 1         | 0.35%   |
| Marvell Technology Group          | 1         | 0.35%   |
| DisplayLink                       | 1         | 0.35%   |
| ASUSTek Computer                  | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 12.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 4.75%   |
| Intel Wireless 7260                                               | 11        | 3.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 3.07%   |
| Intel Wireless 8265 / 8275                                        | 10        | 2.79%   |
| Intel Wireless 7265                                               | 9         | 2.51%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 2.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 1.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 1.4%    |
| Intel Wireless 8260                                               | 5         | 1.4%    |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 1.12%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.84%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.84%   |
| Intel Wireless 3165                                               | 3         | 0.84%   |
| Intel Wireless 3160                                               | 3         | 0.84%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.84%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.84%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 3         | 0.84%   |
| Sierra Wireless EM7345 4G LTE                                     | 2         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 105       | 56.15%  |
| Qualcomm Atheros      | 28        | 14.97%  |
| Realtek Semiconductor | 22        | 11.76%  |
| Broadcom              | 13        | 6.95%   |
| Ralink                | 4         | 2.14%   |
| MediaTek              | 4         | 2.14%   |
| Sierra Wireless       | 3         | 1.6%    |
| Fibocom               | 3         | 1.6%    |
| TP-Link               | 2         | 1.07%   |
| Broadcom Limited      | 2         | 1.07%   |
| Hewlett-Packard       | 1         | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                     | 11        | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 5.88%   |
| Intel Wireless 8265 / 8275                                              | 10        | 5.35%   |
| Intel Wireless 7265                                                     | 9         | 4.81%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 4.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.21%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 2.67%   |
| Intel Wireless 8260                                                     | 5         | 2.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 2.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.6%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.6%    |
| Intel Wireless 3165                                                     | 3         | 1.6%    |
| Intel Wireless 3160                                                     | 3         | 1.6%    |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.6%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.6%    |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 1.6%    |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 1.07%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.07%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.07%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.07%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.07%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.07%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.07%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.07%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 68        | 42.5%   |
| Intel                    | 54        | 33.75%  |
| Qualcomm Atheros         | 17        | 10.63%  |
| Broadcom                 | 6         | 3.75%   |
| Lenovo                   | 3         | 1.88%   |
| JMicron Technology       | 2         | 1.25%   |
| ASIX Electronics         | 2         | 1.25%   |
| VIA Technologies         | 1         | 0.63%   |
| TP-Link                  | 1         | 0.63%   |
| OPPO Electronics         | 1         | 0.63%   |
| Nvidia                   | 1         | 0.63%   |
| Marvell Technology Group | 1         | 0.63%   |
| DisplayLink              | 1         | 0.63%   |
| Broadcom Limited         | 1         | 0.63%   |
| ASUSTek Computer         | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 26.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 10.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 5.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.75%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 3.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 3.75%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 3.13%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 2.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 1.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.88%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.88%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.25%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.25%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 1.25%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.25%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.25%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.63%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.63%   |
| OPPO 8                                                            | 1         | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.63%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.63%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.63%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.63%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 177       | 51.91%  |
| Ethernet | 153       | 44.87%  |
| Modem    | 11        | 3.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 145       | 76.32%  |
| Ethernet | 45        | 23.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 142       | 79.78%  |
| 1     | 33        | 18.54%  |
| 0     | 2         | 1.12%   |
| 3     | 1         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 154       | 85.08%  |
| Yes  | 27        | 14.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 52.82%  |
| Broadcom                        | 12        | 8.45%   |
| Qualcomm Atheros Communications | 11        | 7.75%   |
| IMC Networks                    | 10        | 7.04%   |
| Realtek Semiconductor           | 9         | 6.34%   |
| Cambridge Silicon Radio         | 5         | 3.52%   |
| Realtek                         | 4         | 2.82%   |
| Hewlett-Packard                 | 4         | 2.82%   |
| Apple                           | 4         | 2.82%   |
| Foxconn / Hon Hai               | 3         | 2.11%   |
| Toshiba                         | 1         | 0.7%    |
| Ralink                          | 1         | 0.7%    |
| Lite-On Technology              | 1         | 0.7%    |
| Dell                            | 1         | 0.7%    |
| Askey Computer                  | 1         | 0.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 27.46%  |
| Intel AX201 Bluetooth                               | 11        | 7.75%   |
| Intel AX200 Bluetooth                               | 8         | 5.63%   |
| Realtek Bluetooth Radio                             | 6         | 4.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 4.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 4.23%   |
| IMC Networks Bluetooth Device                       | 5         | 3.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 3.52%   |
| Realtek Bluetooth Radio                             | 4         | 2.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 2.11%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.11%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 2.11%   |
| Apple Bluetooth Host Controller                     | 3         | 2.11%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.41%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.41%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.41%   |
| Intel AX210 Bluetooth                               | 2         | 1.41%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.41%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.41%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.41%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.41%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.41%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.7%    |
| Ralink RT3290 Bluetooth                             | 1         | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.7%    |
| Lite-On Bluetooth Device                            | 1         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.7%    |
| Intel Bluetooth Device                              | 1         | 0.7%    |
| IMC Networks Wireless_Device                        | 1         | 0.7%    |
| IMC Networks BCM20702A0                             | 1         | 0.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.7%    |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.7%    |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.7%    |
| Broadcom HP Portable SoftSailing                    | 1         | 0.7%    |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.7%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 143       | 66.2%   |
| AMD                   | 36        | 16.67%  |
| Nvidia                | 22        | 10.19%  |
| Lenovo                | 4         | 1.85%   |
| Realtek Semiconductor | 2         | 0.93%   |
| VIA Technologies      | 1         | 0.46%   |
| Texas Instruments     | 1         | 0.46%   |
| TerraTec Electronic   | 1         | 0.46%   |
| Roland                | 1         | 0.46%   |
| Micronas              | 1         | 0.46%   |
| Mark of the Unicorn   | 1         | 0.46%   |
| Logitech              | 1         | 0.46%   |
| JMTek                 | 1         | 0.46%   |
| C-Media Electronics   | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 7.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 6.27%   |
| Intel Sunrise Point-LP HD Audio                                            | 16        | 5.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 5.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 5.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 4.8%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 3.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 3.32%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 3.32%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 3.32%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 3.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 2.58%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 2.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 1.85%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.85%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.48%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.48%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 1.48%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.48%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.11%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.11%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.74%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 2         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.74%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 0.74%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.74%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.37%   |
| Texas Instruments SMSL AD18 AMP                                            | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 32%     |
| SK hynix            | 29        | 23.2%   |
| Micron Technology   | 19        | 15.2%   |
| Kingston            | 10        | 8%      |
| Crucial             | 6         | 4.8%    |
| Unknown             | 4         | 3.2%    |
| Ramaxel Technology  | 3         | 2.4%    |
| Nanya Technology    | 3         | 2.4%    |
| Unknown (ABCD)      | 2         | 1.6%    |
| G.Skill             | 2         | 1.6%    |
| ASint Technology    | 2         | 1.6%    |
| A-DATA Technology   | 2         | 1.6%    |
| Unifosa             | 1         | 0.8%    |
| Qimonda             | 1         | 0.8%    |
| Elpida              | 1         | 0.8%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 3.01%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 3.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.26%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 2.26%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 1.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.5%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 1.5%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 1.5%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.5%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.5%    |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 1.5%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.5%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.5%    |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 1.5%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.5%    |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.75%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.75%   |
| Unifosa RAM GU332G0AJEPR8H2L.. 2GB SODIMM DDR2 667MT/s           | 1         | 0.75%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 0.75%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s             | 1         | 0.75%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.75%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1333MT/s           | 1         | 0.75%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.75%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 0.75%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.75%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 43        | 43.88%  |
| DDR3   | 40        | 40.82%  |
| DDR2   | 7         | 7.14%   |
| LPDDR4 | 4         | 4.08%   |
| SDRAM  | 1         | 1.02%   |
| LPDDR5 | 1         | 1.02%   |
| LPDDR3 | 1         | 1.02%   |
| DDR    | 1         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 93        | 95.88%  |
| Row Of Chips | 3         | 3.09%   |
| DIMM         | 1         | 1.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 43        | 39.45%  |
| 4096  | 33        | 30.28%  |
| 16384 | 14        | 12.84%  |
| 2048  | 11        | 10.09%  |
| 1024  | 5         | 4.59%   |
| 32768 | 2         | 1.83%   |
| 512   | 1         | 0.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 27        | 23.68%  |
| 2667    | 26        | 22.81%  |
| 3200    | 16        | 14.04%  |
| 1333    | 10        | 8.77%   |
| 1334    | 8         | 7.02%   |
| 2400    | 6         | 5.26%   |
| 2133    | 4         | 3.51%   |
| 667     | 4         | 3.51%   |
| 1067    | 3         | 2.63%   |
| 4267    | 2         | 1.75%   |
| 3266    | 2         | 1.75%   |
| 6400    | 1         | 0.88%   |
| 4199    | 1         | 0.88%   |
| 975     | 1         | 0.88%   |
| 800     | 1         | 0.88%   |
| 400     | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| QinHeng Electronics             | 1         | 33.33%  |
| cab Produkttechnik GmbH & Co KG | 1         | 33.33%  |
| Brother Industries              | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| QinHeng CH340S                           | 1         | 33.33%  |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 33.33%  |
| Brother DCP-L2510D series                | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 40        | 25.81%  |
| Microdia                               | 15        | 9.68%   |
| IMC Networks                           | 15        | 9.68%   |
| Realtek Semiconductor                  | 13        | 8.39%   |
| Sunplus Innovation Technology          | 12        | 7.74%   |
| Bison Electronics                      | 12        | 7.74%   |
| Lite-On Technology                     | 7         | 4.52%   |
| Suyin                                  | 5         | 3.23%   |
| Silicon Motion                         | 5         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.23%   |
| Syntek                                 | 4         | 2.58%   |
| Luxvisions Innotech Limited            | 4         | 2.58%   |
| Apple                                  | 3         | 1.94%   |
| Acer                                   | 3         | 1.94%   |
| Quanta                                 | 2         | 1.29%   |
| Logitech                               | 2         | 1.29%   |
| Xiaomi                                 | 1         | 0.65%   |
| Tripath Technology                     | 1         | 0.65%   |
| Sonix Technology                       | 1         | 0.65%   |
| LG Electronics                         | 1         | 0.65%   |
| Lenovo                                 | 1         | 0.65%   |
| Importek                               | 1         | 0.65%   |
| Huddly                                 | 1         | 0.65%   |
| Alcor Micro                            | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 5.73%   |
| Chicony Integrated Camera                               | 8         | 5.1%    |
| Lite-On Integrated Camera                               | 6         | 3.82%   |
| Realtek USB Camera                                      | 4         | 2.55%   |
| IMC Networks Integrated Camera                          | 4         | 2.55%   |
| Sunplus Integrated_Webcam_HD                            | 3         | 1.91%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.91%   |
| Chicony ThinkPad T490 Webcam                            | 3         | 1.91%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 1.91%   |
| Chicony Integrated HP HD Webcam                         | 3         | 1.91%   |
| Chicony HP HD Webcam                                    | 3         | 1.91%   |
| Chicony FJ Camera                                       | 3         | 1.91%   |
| Bison Integrated Camera                                 | 3         | 1.91%   |
| Syntek Integrated Camera                                | 2         | 1.27%   |
| Sunplus Asus Webcam                                     | 2         | 1.27%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.27%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.27%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.27%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.27%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.27%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.27%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.27%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.27%   |
| Bison SunplusIT INC. Integrated Camera                  | 2         | 1.27%   |
| Apple FaceTime HD Camera                                | 2         | 1.27%   |
| Xiaomi POCO X3 Pro                                      | 1         | 0.64%   |
| Tripath PC Camera                                       | 1         | 0.64%   |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.64%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.64%   |
| Suyin USB Webcam                                        | 1         | 0.64%   |
| Suyin Intel Webcam                                      | 1         | 0.64%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.64%   |
| Suyin HD WebCam                                         | 1         | 0.64%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.64%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.64%   |
| Sunplus Laptop Integrated Webcam FHD                    | 1         | 0.64%   |
| Sunplus HP Wide Vision HD                               | 1         | 0.64%   |
| Sunplus HP Universal Camera                             | 1         | 0.64%   |
| Sunplus HD WebCam                                       | 1         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 21        | 43.75%  |
| Synaptics                          | 11        | 22.92%  |
| Upek                               | 4         | 8.33%   |
| STMicroelectronics                 | 4         | 8.33%   |
| Shenzhen Goodix Technology         | 4         | 8.33%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.08%   |
| LighTuning Technology              | 1         | 2.08%   |
| Elan Microelectronics              | 1         | 2.08%   |
| AuthenTec                          | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 6         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 10.42%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 4         | 8.33%   |
| STMicroelectronics Fingerprint Reader                           | 4         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 6.25%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 4.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 4.17%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 4.17%   |
| Shenzhen Goodix FingerPrint                                     | 2         | 4.17%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 2.08%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 2.08%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.08%   |
| Synaptics WBDI                                                  | 1         | 2.08%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 2.08%   |
| Elan ELAN:Fingerprint                                           | 1         | 2.08%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 2.08%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 23        | 57.5%   |
| OmniKey               | 6         | 15%     |
| Broadcom              | 4         | 10%     |
| Lenovo                | 3         | 7.5%    |
| Gemalto (was Gemplus) | 3         | 7.5%    |
| O2 Micro              | 1         | 2.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 57.5%   |
| OmniKey CardMan 4321                                                         | 3         | 7.5%    |
| OmniKey CardMan 1021                                                         | 3         | 7.5%    |
| Lenovo Integrated Smart Card Reader                                          | 3         | 7.5%    |
| Broadcom 58200                                                               | 3         | 7.5%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 5%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.5%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 97        | 53.89%  |
| 1     | 59        | 32.78%  |
| 2     | 20        | 11.11%  |
| 3     | 3         | 1.67%   |
| 4     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 48        | 44.04%  |
| Graphics card            | 24        | 22.02%  |
| Chipcard                 | 21        | 19.27%  |
| Net/wireless             | 4         | 3.67%   |
| Camera                   | 4         | 3.67%   |
| Multimedia controller    | 2         | 1.83%   |
| Card reader              | 2         | 1.83%   |
| Net/ethernet             | 1         | 0.92%   |
| Modem                    | 1         | 0.92%   |
| Communication controller | 1         | 0.92%   |
| Bluetooth                | 1         | 0.92%   |

