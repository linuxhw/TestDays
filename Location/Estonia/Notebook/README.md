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

Total: 257

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | [ff59f7877a](https://linux-hardware.org/?probe=ff59f7877a) | Feb 02, 2024 |
| Dell          | Latitude 7490               | [d2085f3674](https://linux-hardware.org/?probe=d2085f3674) | Jan 24, 2024 |
| Dell          | Inspiron N5010              | [ab07a9741b](https://linux-hardware.org/?probe=ab07a9741b) | Jan 13, 2024 |
| MSI           | Pulse GL66 11UDK            | [fdb748bed5](https://linux-hardware.org/?probe=fdb748bed5) | Jan 13, 2024 |
| Dell          | Inspiron N5010              | [8991ffeadc](https://linux-hardware.org/?probe=8991ffeadc) | Jan 04, 2024 |
| Acer          | Nitro AN517-55              | [f3e3de235b](https://linux-hardware.org/?probe=f3e3de235b) | Dec 23, 2023 |
| HP            | ProBook 6570b               | [7dbd0f9be1](https://linux-hardware.org/?probe=7dbd0f9be1) | Dec 21, 2023 |
| HP            | ProBook 6570b               | [7a4a6018b6](https://linux-hardware.org/?probe=7a4a6018b6) | Dec 21, 2023 |
| TUXEDO        | Polaris AMD Gen5            | [84a93dbb91](https://linux-hardware.org/?probe=84a93dbb91) | Dec 19, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [646c403e2f](https://linux-hardware.org/?probe=646c403e2f) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [7fc71d8954](https://linux-hardware.org/?probe=7fc71d8954) | Dec 16, 2023 |
| Apple         | MacBookAir6,2               | [62734db5de](https://linux-hardware.org/?probe=62734db5de) | Dec 10, 2023 |
| HP            | ProBook 4530s               | [5743a3e441](https://linux-hardware.org/?probe=5743a3e441) | Nov 28, 2023 |
| Dell          | Precision M4600             | [864f0c5cfe](https://linux-hardware.org/?probe=864f0c5cfe) | Nov 22, 2023 |
| Dell          | Precision M4600             | [af124219eb](https://linux-hardware.org/?probe=af124219eb) | Nov 18, 2023 |
| Acer          | Predator PH317-53           | [84650e7d6f](https://linux-hardware.org/?probe=84650e7d6f) | Nov 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [0d9316dbcf](https://linux-hardware.org/?probe=0d9316dbcf) | Oct 31, 2023 |
| HP            | 250 G5 Notebook PC          | [bc710e10c6](https://linux-hardware.org/?probe=bc710e10c6) | Oct 27, 2023 |
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


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 19        | 9.64%   |
| Ubuntu 22.04      | 18        | 9.14%   |
| Ubuntu 18.04      | 14        | 7.11%   |
| ArcoLinux Rolling | 7         | 3.55%   |
| Arch              | 7         | 3.55%   |
| Ubuntu 19.04      | 6         | 3.05%   |
| Linux Mint 20.1   | 5         | 2.54%   |
| Arch Rolling      | 5         | 2.54%   |
| Kubuntu 22.04     | 4         | 2.03%   |
| Fedora 34         | 4         | 2.03%   |
| ROSA R9           | 3         | 1.52%   |
| ROSA R8.1         | 3         | 1.52%   |
| ROSA R11          | 3         | 1.52%   |
| Pop!_OS 20.04     | 3         | 1.52%   |
| OpenMandriva 4.3  | 3         | 1.52%   |
| OpenMandriva 4.2  | 3         | 1.52%   |
| Linux Mint 21.2   | 3         | 1.52%   |
| Kubuntu 20.04     | 3         | 1.52%   |
| Fedora 36         | 3         | 1.52%   |
| Zorin 16          | 2         | 1.02%   |
| Xubuntu 20.04     | 2         | 1.02%   |
| Ubuntu MATE 22.04 | 2         | 1.02%   |
| Ubuntu 20.10      | 2         | 1.02%   |
| Ubuntu 19.10      | 2         | 1.02%   |
| ROSA 12.2         | 2         | 1.02%   |
| Reborn OS         | 2         | 1.02%   |
| Manjaro 20.1      | 2         | 1.02%   |
| Manjaro           | 2         | 1.02%   |
| Linux Mint 20.3   | 2         | 1.02%   |
| Linux Mint 20.2   | 2         | 1.02%   |
| Linux Mint 19.3   | 2         | 1.02%   |
| Linux Mint 18.3   | 2         | 1.02%   |
| KDE neon 20.04    | 2         | 1.02%   |
| Kali 2023.1       | 2         | 1.02%   |
| Elementary 6.1    | 2         | 1.02%   |
| Debian 11         | 2         | 1.02%   |
| Zorin 17          | 1         | 0.51%   |
| Zorin 15          | 1         | 0.51%   |
| Xubuntu 22.10     | 1         | 0.51%   |
| Xubuntu 18.04     | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 62        | 31.96%  |
| Linux Mint   | 17        | 8.76%   |
| ROSA         | 14        | 7.22%   |
| Arch         | 12        | 6.19%   |
| Fedora       | 11        | 5.67%   |
| Manjaro      | 8         | 4.12%   |
| OpenMandriva | 7         | 3.61%   |
| ArcoLinux    | 7         | 3.61%   |
| Pop!_OS      | 6         | 3.09%   |
| Kubuntu      | 6         | 3.09%   |
| Zorin        | 4         | 2.06%   |
| Xubuntu      | 4         | 2.06%   |
| Endless      | 4         | 2.06%   |
| Debian       | 4         | 2.06%   |
| Ubuntu MATE  | 3         | 1.55%   |
| SteamOS      | 3         | 1.55%   |
| KDE neon     | 3         | 1.55%   |
| Kali         | 3         | 1.55%   |
| Elementary   | 3         | 1.55%   |
| Reborn OS    | 2         | 1.03%   |
| Clear Linux  | 2         | 1.03%   |
| Xero         | 1         | 0.52%   |
| Ubuntu Unity | 1         | 0.52%   |
| TUXEDO OS    | 1         | 0.52%   |
| Nobara       | 1         | 0.52%   |
| MX           | 1         | 0.52%   |
| Lubuntu      | 1         | 0.52%   |
| LMDE         | 1         | 0.52%   |
| EndeavourOS  | 1         | 0.52%   |
| ALT Linux    | 1         | 0.52%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 6         | 2.83%   |
| 5.15.0-52-generic                  | 4         | 1.89%   |
| 6.2.0-26-generic                   | 3         | 1.42%   |
| 5.4.0-47-generic                   | 3         | 1.42%   |
| 5.4.0-28-generic                   | 3         | 1.42%   |
| 5.16.7-desktop-1omv4003            | 3         | 1.42%   |
| 5.15.0-53-generic                  | 3         | 1.42%   |
| 5.10.14-desktop-1omv4002           | 3         | 1.42%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 1.42%   |
| 6.2.0-39-generic                   | 2         | 0.94%   |
| 6.1.0-kali7-amd64                  | 2         | 0.94%   |
| 5.8.0-53-generic                   | 2         | 0.94%   |
| 5.4.0-88-generic                   | 2         | 0.94%   |
| 5.4.0-65-generic                   | 2         | 0.94%   |
| 5.15.2-arch1-1                     | 2         | 0.94%   |
| 5.15.0-56-generic                  | 2         | 0.94%   |
| 5.13.0-39-generic                  | 2         | 0.94%   |
| 5.11.0-27-generic                  | 2         | 0.94%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 0.94%   |
| 5.0.0-23-generic                   | 2         | 0.94%   |
| 4.18.0-15-generic                  | 2         | 0.94%   |
| 4.15.0-45-generic                  | 2         | 0.94%   |
| 6.6.7-arch1-1                      | 1         | 0.47%   |
| 6.5.7-200.fc38.x86_64              | 1         | 0.47%   |
| 6.5.6-zen2-1-zen                   | 1         | 0.47%   |
| 6.5.0-kali3-amd64                  | 1         | 0.47%   |
| 6.5.0-14-generic                   | 1         | 0.47%   |
| 6.5.0-10010-tuxedo                 | 1         | 0.47%   |
| 6.4.12-zen1-1-zen                  | 1         | 0.47%   |
| 6.3.12-204.fsync.fc37.x86_64       | 1         | 0.47%   |
| 6.3.1-arch1-1                      | 1         | 0.47%   |
| 6.2.7-arch1-1                      | 1         | 0.47%   |
| 6.2.6-76060206-generic             | 1         | 0.47%   |
| 6.2.0-37-generic                   | 1         | 0.47%   |
| 6.2.0-32-generic                   | 1         | 0.47%   |
| 6.1.54-1-lts                       | 1         | 0.47%   |
| 6.1.52-valve9-1-neptune-61         | 1         | 0.47%   |
| 6.1.5-arch2-1                      | 1         | 0.47%   |
| 6.1.46-1-lts                       | 1         | 0.47%   |
| 6.1.37-un-def-alt1                 | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 32        | 15.53%  |
| 5.15.0  | 19        | 9.22%   |
| 4.15.0  | 13        | 6.31%   |
| 5.8.0   | 9         | 4.37%   |
| 5.11.0  | 8         | 3.88%   |
| 6.2.0   | 7         | 3.4%    |
| 5.13.0  | 7         | 3.4%    |
| 5.0.0   | 7         | 3.4%    |
| 4.18.0  | 5         | 2.43%   |
| 4.9.20  | 4         | 1.94%   |
| 6.5.0   | 3         | 1.46%   |
| 6.1.0   | 3         | 1.46%   |
| 5.3.0   | 3         | 1.46%   |
| 5.19.0  | 3         | 1.46%   |
| 5.16.7  | 3         | 1.46%   |
| 5.10.14 | 3         | 1.46%   |
| 6.0.9   | 2         | 0.97%   |
| 5.17.1  | 2         | 0.97%   |
| 5.15.2  | 2         | 0.97%   |
| 5.13.13 | 2         | 0.97%   |
| 5.13.12 | 2         | 0.97%   |
| 5.11.12 | 2         | 0.97%   |
| 5.10.74 | 2         | 0.97%   |
| 5.10.0  | 2         | 0.97%   |
| 6.6.7   | 1         | 0.49%   |
| 6.5.7   | 1         | 0.49%   |
| 6.5.6   | 1         | 0.49%   |
| 6.4.12  | 1         | 0.49%   |
| 6.3.12  | 1         | 0.49%   |
| 6.3.1   | 1         | 0.49%   |
| 6.2.7   | 1         | 0.49%   |
| 6.2.6   | 1         | 0.49%   |
| 6.1.54  | 1         | 0.49%   |
| 6.1.52  | 1         | 0.49%   |
| 6.1.5   | 1         | 0.49%   |
| 6.1.46  | 1         | 0.49%   |
| 6.1.37  | 1         | 0.49%   |
| 6.1.1   | 1         | 0.49%   |
| 6.0.8   | 1         | 0.49%   |
| 6.0.5   | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 33        | 16.02%  |
| 5.15    | 24        | 11.65%  |
| 5.13    | 16        | 7.77%   |
| 4.15    | 13        | 6.31%   |
| 5.10    | 12        | 5.83%   |
| 5.11    | 11        | 5.34%   |
| 5.8     | 10        | 4.85%   |
| 6.2     | 9         | 4.37%   |
| 6.1     | 9         | 4.37%   |
| 5.0     | 8         | 3.88%   |
| 4.9     | 7         | 3.4%    |
| 5.16    | 6         | 2.91%   |
| 6.5     | 5         | 2.43%   |
| 6.0     | 5         | 2.43%   |
| 4.18    | 5         | 2.43%   |
| 5.9     | 4         | 1.94%   |
| 5.19    | 4         | 1.94%   |
| 5.17    | 4         | 1.94%   |
| 5.3     | 3         | 1.46%   |
| 5.14    | 3         | 1.46%   |
| 5.12    | 3         | 1.46%   |
| 6.3     | 2         | 0.97%   |
| 4.19    | 2         | 0.97%   |
| 6.6     | 1         | 0.49%   |
| 6.4     | 1         | 0.49%   |
| 5.6     | 1         | 0.49%   |
| 5.5     | 1         | 0.49%   |
| 4.4     | 1         | 0.49%   |
| 4.10    | 1         | 0.49%   |
| 4.1     | 1         | 0.49%   |
| 3.16    | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 186       | 97.38%  |
| i686   | 5         | 2.62%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 70        | 36.08%  |
| KDE5       | 32        | 16.49%  |
| Unknown    | 26        | 13.4%   |
| XFCE       | 17        | 8.76%   |
| X-Cinnamon | 13        | 6.7%    |
| KDE4       | 8         | 4.12%   |
| MATE       | 7         | 3.61%   |
| Pantheon   | 3         | 1.55%   |
| KDE        | 3         | 1.55%   |
| i3         | 3         | 1.55%   |
| Unity      | 2         | 1.03%   |
| LXQt       | 2         | 1.03%   |
| LXDE       | 2         | 1.03%   |
| Budgie     | 2         | 1.03%   |
| awesome    | 2         | 1.03%   |
| openbox    | 1         | 0.52%   |
| Cinnamon   | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 149       | 78.01%  |
| Wayland | 31        | 16.23%  |
| Unknown | 10        | 5.24%   |
| Tty     | 1         | 0.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 88        | 45.36%  |
| SDDM    | 32        | 16.49%  |
| GDM3    | 23        | 11.86%  |
| GDM     | 20        | 10.31%  |
| LightDM | 14        | 7.22%   |
| TDM     | 9         | 4.64%   |
| KDM     | 8         | 4.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 95        | 49.22%  |
| Unknown         | 33        | 17.1%   |
| et_EE           | 31        | 16.06%  |
| ru_RU           | 18        | 9.33%   |
| en_GB           | 6         | 3.11%   |
| de_DE           | 3         | 1.55%   |
| uk_UA           | 1         | 0.52%   |
| ru_UA           | 1         | 0.52%   |
| fr_FR           | 1         | 0.52%   |
| es_MX           | 1         | 0.52%   |
| en_US.iso885915 | 1         | 0.52%   |
| en_DK           | 1         | 0.52%   |
| C               | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 100       | 51.02%  |
| EFI  | 96        | 48.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 139       | 72.77%  |
| Btrfs   | 23        | 12.04%  |
| Unknown | 12        | 6.28%   |
| Overlay | 7         | 3.66%   |
| Tmpfs   | 5         | 2.62%   |
| Xfs     | 3         | 1.57%   |
| Zfs     | 1         | 0.52%   |
| Ext3    | 1         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 94        | 48.7%   |
| GPT     | 77        | 39.9%   |
| MBR     | 22        | 11.4%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 176       | 91.19%  |
| Yes       | 17        | 8.81%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 139       | 71.28%  |
| Yes       | 56        | 28.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 57        | 29.84%  |
| Hewlett-Packard     | 34        | 17.8%   |
| Dell                | 26        | 13.61%  |
| ASUSTek Computer    | 21        | 10.99%  |
| Acer                | 8         | 4.19%   |
| Samsung Electronics | 7         | 3.66%   |
| MSI                 | 6         | 3.14%   |
| Apple               | 5         | 2.62%   |
| Valve               | 3         | 1.57%   |
| Fujitsu             | 3         | 1.57%   |
| TUXEDO              | 2         | 1.05%   |
| Timi                | 2         | 1.05%   |
| Quanta              | 2         | 1.05%   |
| Notebook            | 2         | 1.05%   |
| Alienware           | 2         | 1.05%   |
| Toshiba             | 1         | 0.52%   |
| Packard Bell        | 1         | 0.52%   |
| mPTech              | 1         | 0.52%   |
| Intel               | 1         | 0.52%   |
| HUAWEI              | 1         | 0.52%   |
| GPD                 | 1         | 0.52%   |
| Gigabyte Technology | 1         | 0.52%   |
| Getac               | 1         | 0.52%   |
| Fujitsu Siemens     | 1         | 0.52%   |
| Framework           | 1         | 0.52%   |
| Chuwi               | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 3         | 1.57%   |
| Quanta TWH                                            | 2         | 1.05%   |
| Lenovo Y50-70 20378                                   | 2         | 1.05%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 1.05%   |
| HP Pavilion dv7                                       | 2         | 1.05%   |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 1.05%   |
| HP EliteBook 8470p                                    | 2         | 1.05%   |
| HP EliteBook 8460p                                    | 2         | 1.05%   |
| HP EliteBook 840 G2                                   | 2         | 1.05%   |
| Dell Latitude 7490                                    | 2         | 1.05%   |
| Dell Inspiron N5110                                   | 2         | 1.05%   |
| Alienware 17                                          | 2         | 1.05%   |
| TUXEDO Polaris AMD Gen5                               | 1         | 0.52%   |
| TUXEDO Book BA1510                                    | 1         | 0.52%   |
| Toshiba Satellite L855                                | 1         | 0.52%   |
| Timi RedmiBook 16                                     | 1         | 0.52%   |
| Timi RedmiBook 14 II                                  | 1         | 0.52%   |
| Samsung R410                                          | 1         | 0.52%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.52%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.52%   |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.52%   |
| Samsung 535U3C                                        | 1         | 0.52%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.52%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.52%   |
| Packard Bell EasyNote TK87                            | 1         | 0.52%   |
| Notebook W35xSS_370SS                                 | 1         | 0.52%   |
| Notebook N150SD/N155SD                                | 1         | 0.52%   |
| MSI Pulse GL66 11UDK                                  | 1         | 0.52%   |
| MSI GT70 2OC/2OD                                      | 1         | 0.52%   |
| MSI GS75 Stealth 8SE                                  | 1         | 0.52%   |
| MSI GP62M 7RDX                                        | 1         | 0.52%   |
| MSI GL72 6QD                                          | 1         | 0.52%   |
| MSI GF63 Thin 10SCXR                                  | 1         | 0.52%   |
| mPTech ARC 11.6 128GB HD                              | 1         | 0.52%   |
| Lenovo Y720-15IKB 80VR                                | 1         | 0.52%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.52%   |
| Lenovo V110-15ISK 80TL                                | 1         | 0.52%   |
| Lenovo ThinkPad X260 20F5S84400                       | 1         | 0.52%   |
| Lenovo ThinkPad X240 20AMA0W706                       | 1         | 0.52%   |
| Lenovo ThinkPad X220 4291R30                          | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 43        | 22.51%  |
| HP EliteBook          | 12        | 6.28%   |
| HP Pavilion           | 7         | 3.66%   |
| Dell Latitude         | 7         | 3.66%   |
| Dell Inspiron         | 7         | 3.66%   |
| Dell Precision        | 5         | 2.62%   |
| Lenovo IdeaPad        | 4         | 2.09%   |
| HP ProBook            | 4         | 2.09%   |
| ASUS VivoBook         | 4         | 2.09%   |
| Acer Aspire           | 4         | 2.09%   |
| Valve Jupiter         | 3         | 1.57%   |
| Lenovo Legion         | 3         | 1.57%   |
| Fujitsu LIFEBOOK      | 3         | 1.57%   |
| Dell XPS              | 3         | 1.57%   |
| ASUS Zenbook          | 3         | 1.57%   |
| Timi RedmiBook        | 2         | 1.05%   |
| Samsung 900X3C        | 2         | 1.05%   |
| Quanta TWH            | 2         | 1.05%   |
| Lenovo Y50-70         | 2         | 1.05%   |
| HP Presario           | 2         | 1.05%   |
| HP OMEN               | 2         | 1.05%   |
| HP ENVY               | 2         | 1.05%   |
| HP Compaq             | 2         | 1.05%   |
| Dell Vostro           | 2         | 1.05%   |
| Alienware 17          | 2         | 1.05%   |
| TUXEDO Polaris        | 1         | 0.52%   |
| TUXEDO Book           | 1         | 0.52%   |
| Toshiba Satellite     | 1         | 0.52%   |
| Samsung R410          | 1         | 0.52%   |
| Samsung 770Z5E        | 1         | 0.52%   |
| Samsung 535U3C        | 1         | 0.52%   |
| Samsung 300E5EV       | 1         | 0.52%   |
| Samsung 275E4E        | 1         | 0.52%   |
| Packard Bell EasyNote | 1         | 0.52%   |
| Notebook W35xSS       | 1         | 0.52%   |
| Notebook N150SD       | 1         | 0.52%   |
| MSI Pulse             | 1         | 0.52%   |
| MSI GT70              | 1         | 0.52%   |
| MSI GS75              | 1         | 0.52%   |
| MSI GP62M             | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 22        | 11.52%  |
| 2020 | 21        | 10.99%  |
| 2011 | 19        | 9.95%   |
| 2019 | 16        | 8.38%   |
| 2018 | 16        | 8.38%   |
| 2014 | 13        | 6.81%   |
| 2015 | 12        | 6.28%   |
| 2012 | 12        | 6.28%   |
| 2022 | 9         | 4.71%   |
| 2017 | 9         | 4.71%   |
| 2010 | 9         | 4.71%   |
| 2021 | 7         | 3.66%   |
| 2008 | 7         | 3.66%   |
| 2007 | 7         | 3.66%   |
| 2016 | 6         | 3.14%   |
| 2023 | 3         | 1.57%   |
| 2009 | 2         | 1.05%   |
| 2006 | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 191       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 176       | 91.67%  |
| Enabled  | 16        | 8.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 191       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 47        | 24.35%  |
| 4.01-8.0    | 41        | 21.24%  |
| 16.01-24.0  | 37        | 19.17%  |
| 3.01-4.0    | 34        | 17.62%  |
| 32.01-64.0  | 10        | 5.18%   |
| 24.01-32.0  | 8         | 4.15%   |
| 2.01-3.0    | 8         | 4.15%   |
| 1.01-2.0    | 6         | 3.11%   |
| 64.01-256.0 | 2         | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 68        | 33.5%   |
| 2.01-3.0   | 48        | 23.65%  |
| 4.01-8.0   | 39        | 19.21%  |
| 3.01-4.0   | 25        | 12.32%  |
| 8.01-16.0  | 11        | 5.42%   |
| 0.51-1.0   | 10        | 4.93%   |
| 24.01-32.0 | 1         | 0.49%   |
| 16.01-24.0 | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 147       | 75.38%  |
| 2      | 40        | 20.51%  |
| 3      | 6         | 3.08%   |
| 5      | 1         | 0.51%   |
| 4      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 127       | 65.46%  |
| Yes       | 67        | 34.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 84.9%   |
| No        | 29        | 15.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 190       | 99.48%  |
| No        | 1         | 0.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 78.13%  |
| No        | 42        | 21.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Estonia | 191       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Tallinn           | 126       | 64.95%  |
| Tartu             | 17        | 8.76%   |
| Pärnu            | 8         | 4.12%   |
| Narva             | 6         | 3.09%   |
| Rapla             | 4         | 2.06%   |
| Rakvere           | 4         | 2.06%   |
| Vinni             | 2         | 1.03%   |
| Saku              | 2         | 1.03%   |
| Otepaeae          | 2         | 1.03%   |
| Maardu            | 2         | 1.03%   |
| Keila             | 2         | 1.03%   |
| Võru             | 1         | 0.52%   |
| Viljandi          | 1         | 0.52%   |
| Viimsi            | 1         | 0.52%   |
| Vatla             | 1         | 0.52%   |
| Valga             | 1         | 0.52%   |
| Tabasalu          | 1         | 0.52%   |
| Sillamäe         | 1         | 0.52%   |
| Sauga             | 1         | 0.52%   |
| Rae Parish        | 1         | 0.52%   |
| Põlva            | 1         | 0.52%   |
| Pohja-Sakala vald | 1         | 0.52%   |
| Palamuse          | 1         | 0.52%   |
| Laagri            | 1         | 0.52%   |
| Kärdla           | 1         | 0.52%   |
| Kaeina            | 1         | 0.52%   |
| Jüri             | 1         | 0.52%   |
| Jõhvi            | 1         | 0.52%   |
| Jõgeva           | 1         | 0.52%   |
| AEaesmaee         | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 54        | 63     | 22.69%  |
| Seagate                     | 31        | 34     | 13.03%  |
| Toshiba                     | 17        | 17     | 7.14%   |
| Kingston                    | 16        | 17     | 6.72%   |
| WDC                         | 15        | 17     | 6.3%    |
| SK hynix                    | 13        | 17     | 5.46%   |
| Sandisk                     | 10        | 12     | 4.2%    |
| Unknown                     | 8         | 8      | 3.36%   |
| Intel                       | 8         | 9      | 3.36%   |
| HGST                        | 7         | 8      | 2.94%   |
| Patriot                     | 5         | 6      | 2.1%    |
| Hitachi                     | 5         | 5      | 2.1%    |
| Micron Technology           | 4         | 4      | 1.68%   |
| Lenovo                      | 3         | 3      | 1.26%   |
| Crucial                     | 3         | 3      | 1.26%   |
| China                       | 3         | 3      | 1.26%   |
| Apacer                      | 3         | 3      | 1.26%   |
| A-DATA Technology           | 3         | 3      | 1.26%   |
| Transcend                   | 2         | 5      | 0.84%   |
| Phison Electronics          | 2         | 2      | 0.84%   |
| LITEONIT                    | 2         | 2      | 0.84%   |
| KIOXIA                      | 2         | 3      | 0.84%   |
| Kingston Technology Company | 2         | 2      | 0.84%   |
| KingSpec                    | 2         | 3      | 0.84%   |
| Gigabyte Technology         | 2         | 3      | 0.84%   |
| Fujitsu                     | 2         | 2      | 0.84%   |
| Apple                       | 2         | 2      | 0.84%   |
| Team                        | 1         | 1      | 0.42%   |
| SPCC                        | 1         | 1      | 0.42%   |
| PNY                         | 1         | 1      | 0.42%   |
| Phison                      | 1         | 1      | 0.42%   |
| Netac                       | 1         | 1      | 0.42%   |
| Lexar                       | 1         | 1      | 0.42%   |
| Intenso                     | 1         | 1      | 0.42%   |
| HUAWEI                      | 1         | 1      | 0.42%   |
| External                    | 1         | 1      | 0.42%   |
| ASMT109x                    | 1         | 2      | 0.42%   |
| ADATA Technology            | 1         | 1      | 0.42%   |
| Unknown                     | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST500LM021-1KJ152 500GB                    | 3         | 1.22%   |
| Samsung SSD 850 EVO 500GB                          | 3         | 1.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 3         | 1.22%   |
| Kingston SA400S37960G 960GB SSD                    | 3         | 1.22%   |
| HGST HTS721010A9E630 1TB                           | 3         | 1.22%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 2         | 0.82%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB               | 2         | 0.82%   |
| Unknown MMC Card  512GB                            | 2         | 0.82%   |
| Unknown MMC Card  16GB                             | 2         | 0.82%   |
| Toshiba NVMe SSD Drive 512GB                       | 2         | 0.82%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 0.82%   |
| SK hynix NVMe SSD Drive 512GB                      | 2         | 0.82%   |
| SK hynix NVMe SSD Drive 256GB                      | 2         | 0.82%   |
| Seagate ST500LT012-1DG142 500GB                    | 2         | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 0.82%   |
| Seagate BUP Portable 512GB                         | 2         | 0.82%   |
| SanDisk SD8SBAT256G1122 256GB SSD                  | 2         | 0.82%   |
| Samsung SSD 970 EVO Plus 500GB                     | 2         | 0.82%   |
| Samsung SSD 970 EVO Plus 1TB                       | 2         | 0.82%   |
| Samsung SSD 850 EVO M.2 500GB                      | 2         | 0.82%   |
| Samsung NVMe SSD Drive 512GB                       | 2         | 0.82%   |
| Samsung NVMe SSD Drive 1TB                         | 2         | 0.82%   |
| Samsung NVMe SSD Drive 1024GB                      | 2         | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2         | 0.82%   |
| Samsung MZVLQ256HAJD-000H1 256GB                   | 2         | 0.82%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 0.82%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD               | 2         | 0.82%   |
| Patriot Burst 240GB SSD                            | 2         | 0.82%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                | 2         | 0.82%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB            | 2         | 0.82%   |
| Kingston SV300S37A120G 120GB SSD                   | 2         | 0.82%   |
| Kingston SA400S37240G 240GB SSD                    | 2         | 0.82%   |
| Intel SSDPEKKF256G8L 256GB                         | 2         | 0.82%   |
| HGST HTS541010A9E680 1TB                           | 2         | 0.82%   |
| WDC WDS500G2B0B 500GB SSD                          | 1         | 0.41%   |
| WDC WDS500G1X0E-00AFY0 500GB                       | 1         | 0.41%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                   | 1         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB                       | 1         | 0.41%   |
| WDC WD5000LPCX-24VHAT0 500GB                       | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 30        | 33     | 51.72%  |
| Toshiba  | 8         | 8      | 13.79%  |
| HGST     | 7         | 8      | 12.07%  |
| WDC      | 5         | 6      | 8.62%   |
| Hitachi  | 5         | 5      | 8.62%   |
| Fujitsu  | 2         | 2      | 3.45%   |
| External | 1         | 1      | 1.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 34     | 31.52%  |
| Kingston            | 13        | 14     | 14.13%  |
| SanDisk             | 5         | 7      | 5.43%   |
| SK hynix            | 4         | 4      | 4.35%   |
| Patriot             | 4         | 5      | 4.35%   |
| Micron Technology   | 4         | 4      | 4.35%   |
| WDC                 | 3         | 4      | 3.26%   |
| Crucial             | 3         | 3      | 3.26%   |
| China               | 3         | 3      | 3.26%   |
| Apacer              | 3         | 3      | 3.26%   |
| A-DATA Technology   | 3         | 3      | 3.26%   |
| Transcend           | 2         | 5      | 2.17%   |
| Toshiba             | 2         | 2      | 2.17%   |
| LITEONIT            | 2         | 2      | 2.17%   |
| KingSpec            | 2         | 3      | 2.17%   |
| Intel               | 2         | 3      | 2.17%   |
| Apple               | 2         | 2      | 2.17%   |
| Team                | 1         | 1      | 1.09%   |
| SPCC                | 1         | 1      | 1.09%   |
| Netac               | 1         | 1      | 1.09%   |
| Lexar               | 1         | 1      | 1.09%   |
| Intenso             | 1         | 1      | 1.09%   |
| Gigabyte Technology | 1         | 2      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 82        | 108    | 37.79%  |
| NVMe    | 67        | 85     | 30.88%  |
| HDD     | 56        | 63     | 25.81%  |
| MMC     | 9         | 9      | 4.15%   |
| Unknown | 3         | 4      | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 126       | 167    | 59.72%  |
| NVMe | 67        | 84     | 31.75%  |
| SAS  | 9         | 9      | 4.27%   |
| MMC  | 9         | 9      | 4.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 98        | 119    | 68.06%  |
| 0.51-1.0   | 41        | 47     | 28.47%  |
| 1.01-2.0   | 4         | 4      | 2.78%   |
| 3.01-4.0   | 1         | 1      | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 71        | 36.04%  |
| 251-500        | 42        | 21.32%  |
| 501-1000       | 27        | 13.71%  |
| 1-20           | 16        | 8.12%   |
| 51-100         | 14        | 7.11%   |
| 1001-2000      | 9         | 4.57%   |
| More than 3000 | 6         | 3.05%   |
| Unknown        | 6         | 3.05%   |
| 21-50          | 5         | 2.54%   |
| 2001-3000      | 1         | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 82        | 40.39%  |
| 21-50          | 32        | 15.76%  |
| 101-250        | 31        | 15.27%  |
| 51-100         | 24        | 11.82%  |
| 251-500        | 16        | 7.88%   |
| 501-1000       | 8         | 3.94%   |
| Unknown        | 6         | 2.96%   |
| More than 3000 | 2         | 0.99%   |
| 2001-3000      | 1         | 0.49%   |
| 1001-2000      | 1         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 5.88%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 5.88%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 5.88%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 5.88%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 5.88%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 5.88%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 5.88%   |
| Netac SSD 720GB                                     | 1         | 1      | 5.88%   |
| Micron Technology MTFDDAK256TDL-1AW15ABHA 256GB SSD | 1         | 1      | 5.88%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 5.88%   |
| Kingston SA400S37960G 960GB SSD                     | 1         | 1      | 5.88%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 5.88%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 5.88%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 5.88%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 5.88%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 7         | 7      | 41.18%  |
| Micron Technology | 2         | 2      | 11.76%  |
| Kingston          | 2         | 2      | 11.76%  |
| WDC               | 1         | 1      | 5.88%   |
| Netac             | 1         | 1      | 5.88%   |
| Hitachi           | 1         | 1      | 5.88%   |
| HGST              | 1         | 1      | 5.88%   |
| Fujitsu           | 1         | 1      | 5.88%   |
| Crucial           | 1         | 1      | 5.88%   |

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
| HDD  | 11        | 11     | 64.71%  |
| SSD  | 6         | 6      | 35.29%  |

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
| Detected | 110       | 164    | 55.28%  |
| Works    | 73        | 88     | 36.68%  |
| Malfunc  | 16        | 17     | 8.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 135       | 59.47%  |
| Samsung Electronics          | 26        | 11.45%  |
| AMD                          | 20        | 8.81%   |
| SanDisk                      | 11        | 4.85%   |
| SK hynix                     | 9         | 3.96%   |
| Toshiba America Info Systems | 6         | 2.64%   |
| Phison Electronics           | 4         | 1.76%   |
| Kingston Technology Company  | 4         | 1.76%   |
| Lenovo                       | 3         | 1.32%   |
| KIOXIA                       | 3         | 1.32%   |
| Marvell Technology Group     | 2         | 0.88%   |
| VIA Technologies             | 1         | 0.44%   |
| Nvidia                       | 1         | 0.44%   |
| Hosin Global Electronics     | 1         | 0.44%   |
| ADATA Technology             | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16        | 6.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 6.56%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 6.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 5.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 3.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 3.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 3.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 2.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 2.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 2.46%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 2.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 2.05%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.64%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.23%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 3         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.23%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 1.23%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 3         | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.23%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.82%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.82%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.82%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.82%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 2         | 0.82%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.82%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 0.82%   |
| Intel SSD 660P Series                                                          | 2         | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.82%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 2         | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 142       | 60.68%  |
| NVMe | 68        | 29.06%  |
| IDE  | 14        | 5.98%   |
| RAID | 10        | 4.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 155       | 81.15%  |
| AMD    | 36        | 18.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 3.66%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.57%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 1.57%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 3         | 1.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.57%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 3         | 1.57%   |
| AMD Custom APU 0405                           | 3         | 1.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.05%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 1.05%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.05%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 1.05%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 1.05%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.05%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.05%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.05%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.05%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.05%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.05%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.05%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.05%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.05%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.05%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 2         | 1.05%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.05%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.05%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.05%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.05%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.05%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.05%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.05%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 52        | 27.23%  |
| Intel Core i5                  | 52        | 27.23%  |
| Other                          | 13        | 6.81%   |
| Intel Core i3                  | 10        | 5.24%   |
| AMD Ryzen 7                    | 9         | 4.71%   |
| AMD Ryzen 5                    | 9         | 4.71%   |
| Intel Core 2 Duo               | 8         | 4.19%   |
| Intel Celeron                  | 8         | 4.19%   |
| Intel Pentium                  | 3         | 1.57%   |
| AMD Ryzen 7 PRO                | 3         | 1.57%   |
| Intel Pentium M                | 2         | 1.05%   |
| Intel Celeron Dual-Core        | 2         | 1.05%   |
| Intel Atom                     | 2         | 1.05%   |
| Intel Xeon                     | 1         | 0.52%   |
| Intel Pentium Silver           | 1         | 0.52%   |
| Intel Pentium Dual             | 1         | 0.52%   |
| Intel Core i9                  | 1         | 0.52%   |
| Intel Core 2                   | 1         | 0.52%   |
| Intel Celeron M                | 1         | 0.52%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.52%   |
| AMD Ryzen 5 PRO                | 1         | 0.52%   |
| AMD Ryzen 3 PRO                | 1         | 0.52%   |
| AMD Ryzen 3                    | 1         | 0.52%   |
| AMD E2                         | 1         | 0.52%   |
| AMD E                          | 1         | 0.52%   |
| AMD C-60                       | 1         | 0.52%   |
| AMD Athlon II Dual-Core        | 1         | 0.52%   |
| AMD Athlon 64 X2               | 1         | 0.52%   |
| AMD A8                         | 1         | 0.52%   |
| AMD A6                         | 1         | 0.52%   |
| AMD A4                         | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 90        | 47.12%  |
| 4       | 59        | 30.89%  |
| 6       | 18        | 9.42%   |
| 8       | 12        | 6.28%   |
| 1       | 7         | 3.66%   |
| Unknown | 2         | 1.05%   |
| 14      | 1         | 0.52%   |
| 12      | 1         | 0.52%   |
| 10      | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 191       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 148       | 77.08%  |
| 1       | 42        | 21.88%  |
| Unknown | 2         | 1.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 188       | 98.43%  |
| 32-bit         | 2         | 1.05%   |
| Unknown        | 1         | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 25.64%  |
| 0x306a9    | 13        | 6.67%   |
| 0x206a7    | 13        | 6.67%   |
| 0x306c3    | 12        | 6.15%   |
| 0x806ea    | 8         | 4.1%    |
| 0x40651    | 8         | 4.1%    |
| 0x08600106 | 7         | 3.59%   |
| 0x306d4    | 6         | 3.08%   |
| 0x906e9    | 5         | 2.56%   |
| 0x806ec    | 5         | 2.56%   |
| 0x20655    | 5         | 2.56%   |
| 0xa0652    | 4         | 2.05%   |
| 0x806c1    | 4         | 2.05%   |
| 0x6fb      | 4         | 2.05%   |
| 0x506e3    | 4         | 2.05%   |
| 0x1067a    | 4         | 2.05%   |
| 0x906ea    | 3         | 1.54%   |
| 0x6fd      | 3         | 1.54%   |
| 0x406e3    | 3         | 1.54%   |
| 0x08108102 | 3         | 1.54%   |
| 0x05000119 | 3         | 1.54%   |
| 0x806e9    | 2         | 1.03%   |
| 0x706a1    | 2         | 1.03%   |
| 0x6d8      | 2         | 1.03%   |
| 0x30678    | 2         | 1.03%   |
| 0x0a50000c | 2         | 1.03%   |
| 0x906ed    | 1         | 0.51%   |
| 0x806eb    | 1         | 0.51%   |
| 0x806d1    | 1         | 0.51%   |
| 0x706a8    | 1         | 0.51%   |
| 0x6fa      | 1         | 0.51%   |
| 0x6f6      | 1         | 0.51%   |
| 0x30661    | 1         | 0.51%   |
| 0x106ca    | 1         | 0.51%   |
| 0x0a704103 | 1         | 0.51%   |
| 0x0a50000d | 1         | 0.51%   |
| 0x0a404102 | 1         | 0.51%   |
| 0x08608103 | 1         | 0.51%   |
| 0x08600104 | 1         | 0.51%   |
| 0x08600103 | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 33        | 17.28%  |
| Haswell          | 27        | 14.14%  |
| SandyBridge      | 16        | 8.38%   |
| IvyBridge        | 16        | 8.38%   |
| Zen 2            | 11        | 5.76%   |
| Unknown          | 11        | 5.76%   |
| Core             | 9         | 4.71%   |
| Broadwell        | 9         | 4.71%   |
| Westmere         | 8         | 4.19%   |
| Skylake          | 8         | 4.19%   |
| TigerLake        | 5         | 2.62%   |
| Penryn           | 4         | 2.09%   |
| CometLake        | 4         | 2.09%   |
| Zen+             | 3         | 1.57%   |
| Zen 3            | 3         | 1.57%   |
| Goldmont plus    | 3         | 1.57%   |
| Bobcat           | 3         | 1.57%   |
| Zen              | 2         | 1.05%   |
| Silvermont       | 2         | 1.05%   |
| P6               | 2         | 1.05%   |
| Bonnell          | 2         | 1.05%   |
| Alderlake Hybrid | 2         | 1.05%   |
| Steamroller      | 1         | 0.52%   |
| Piledriver       | 1         | 0.52%   |
| K8 Hammer        | 1         | 0.52%   |
| K8 & K10 hybrid  | 1         | 0.52%   |
| K10              | 1         | 0.52%   |
| Icelake          | 1         | 0.52%   |
| Goldmont         | 1         | 0.52%   |
| Excavator        | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 144       | 55.38%  |
| Nvidia           | 73        | 28.08%  |
| AMD              | 42        | 16.15%  |
| VIA Technologies | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 15        | 5.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 14        | 5.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 14        | 5.22%   |
| Intel UHD Graphics 620                                                        | 12        | 4.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 10        | 3.73%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 10        | 3.73%   |
| Intel Core Processor Integrated Graphics Controller                           | 8         | 2.99%   |
| Intel HD Graphics 5500                                                        | 7         | 2.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 6         | 2.24%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 1.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 1.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 5         | 1.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 1.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 5         | 1.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 5         | 1.87%   |
| Intel HD Graphics 630                                                         | 5         | 1.87%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 4         | 1.49%   |
| Intel HD Graphics 530                                                         | 4         | 1.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 1.12%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 1.12%   |
| Nvidia GK208M [GeForce GT 730M]                                               | 3         | 1.12%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 3         | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 1.12%   |
| AMD VanGogh [AMD Custom GPU 0405]                                             | 3         | 1.12%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.75%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 0.75%   |
| Nvidia GP108GLM [Quadro P520]                                                 | 2         | 0.75%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 0.75%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 2         | 0.75%   |
| Nvidia GM107GLM [Quadro M2000M]                                               | 2         | 0.75%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 2         | 0.75%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 0.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 0.75%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 0.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 0.75%   |
| Intel HD Graphics 620                                                         | 2         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 79        | 41.36%  |
| Intel + Nvidia | 60        | 31.41%  |
| 1 x AMD        | 32        | 16.75%  |
| 1 x Nvidia     | 8         | 4.19%   |
| Intel + AMD    | 5         | 2.62%   |
| AMD + Nvidia   | 4         | 2.09%   |
| 2 x Nvidia     | 1         | 0.52%   |
| 2 x AMD        | 1         | 0.52%   |
| 1 x VIA        | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 144       | 74.23%  |
| Proprietary | 46        | 23.71%  |
| Unknown     | 4         | 2.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 106       | 55.21%  |
| 1.01-2.0   | 34        | 17.71%  |
| 0.01-0.5   | 21        | 10.94%  |
| 3.01-4.0   | 12        | 6.25%   |
| 0.51-1.0   | 12        | 6.25%   |
| 5.01-6.0   | 4         | 2.08%   |
| 7.01-8.0   | 1         | 0.52%   |
| 2.01-3.0   | 1         | 0.52%   |
| 8.01-16.0  | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 37        | 16.02%  |
| Chimei Innolux          | 36        | 15.58%  |
| LG Display              | 26        | 11.26%  |
| BOE                     | 24        | 10.39%  |
| Samsung Electronics     | 23        | 9.96%   |
| Dell                    | 20        | 8.66%   |
| Chi Mei Optoelectronics | 11        | 4.76%   |
| Sharp                   | 7         | 3.03%   |
| Lenovo                  | 5         | 2.16%   |
| Hewlett-Packard         | 5         | 2.16%   |
| Goldstar                | 5         | 2.16%   |
| Apple                   | 5         | 2.16%   |
| Sony                    | 3         | 1.3%    |
| PANDA                   | 3         | 1.3%    |
| LG Philips              | 3         | 1.3%    |
| CPT                     | 2         | 0.87%   |
| AOC                     | 2         | 0.87%   |
| ViewSonic               | 1         | 0.43%   |
| Valve                   | 1         | 0.43%   |
| Toshiba                 | 1         | 0.43%   |
| Seiko/Epson             | 1         | 0.43%   |
| Philips                 | 1         | 0.43%   |
| Panasonic               | 1         | 0.43%   |
| Lenovo Group Limited    | 1         | 0.43%   |
| KDB                     | 1         | 0.43%   |
| JDI                     | 1         | 0.43%   |
| InfoVision              | 1         | 0.43%   |
| CSO                     | 1         | 0.43%   |
| ASUSTek Computer        | 1         | 0.43%   |
| Analogix                | 1         | 0.43%   |
| Acer                    | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 5         | 2.1%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 4         | 1.68%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 3         | 1.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 1.26%   |
| Sony TV SNYDB01 1920x1080                                                 | 2         | 0.84%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.84%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 0.84%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.84%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 2         | 0.84%   |
| Dell P3421W DELA1A8 3440x1440 800x335mm 34.1-inch                         | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch          | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.84%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.84%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.84%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 2         | 0.84%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 0.84%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 0.84%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 2         | 0.84%   |
| ViewSonic VP2030 SERIES VSC131C 1600x1200 408x306mm 20.1-inch             | 1         | 0.42%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 1         | 0.42%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                     | 1         | 0.42%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.42%   |
| Sharp LQ133M1JW40 SHP10CD 1920x1080 294x165mm 13.3-inch                   | 1         | 0.42%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 0.42%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 1         | 0.42%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                   | 1         | 0.42%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                   | 1         | 0.42%   |
| Seiko/Epson LCD Monitor 1920x1080                                         | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch      | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM030E 1680x1050 474x296mm 22.0-inch      | 1         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 92        | 42.2%   |
| 1366x768 (WXGA)    | 47        | 21.56%  |
| 1600x900 (HD+)     | 16        | 7.34%   |
| 3840x2160 (4K)     | 12        | 5.5%    |
| 1280x800 (WXGA)    | 11        | 5.05%   |
| 1920x1200 (WUXGA)  | 9         | 4.13%   |
| 2560x1600          | 6         | 2.75%   |
| 2560x1440 (QHD)    | 5         | 2.29%   |
| 1680x1050 (WSXGA+) | 5         | 2.29%   |
| 3440x1440          | 3         | 1.38%   |
| 1440x900 (WXGA+)   | 3         | 1.38%   |
| 800x1280           | 2         | 0.92%   |
| 1280x1024 (SXGA)   | 2         | 0.92%   |
| 3840x2400          | 1         | 0.46%   |
| 2880x1800          | 1         | 0.46%   |
| 2560x1080          | 1         | 0.46%   |
| 2256x1504          | 1         | 0.46%   |
| 1600x1200          | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 89        | 38.03%  |
| 14      | 32        | 13.68%  |
| 13      | 26        | 11.11%  |
| 17      | 17        | 7.26%   |
| 24      | 15        | 6.41%   |
| 12      | 8         | 3.42%   |
| 27      | 7         | 2.99%   |
| 34      | 4         | 1.71%   |
| 16      | 4         | 1.71%   |
| Unknown | 4         | 1.71%   |
| 72      | 3         | 1.28%   |
| 23      | 3         | 1.28%   |
| 22      | 3         | 1.28%   |
| 40      | 2         | 0.85%   |
| 86      | 1         | 0.43%   |
| 84      | 1         | 0.43%   |
| 65      | 1         | 0.43%   |
| 54      | 1         | 0.43%   |
| 43      | 1         | 0.43%   |
| 38      | 1         | 0.43%   |
| 31      | 1         | 0.43%   |
| 29      | 1         | 0.43%   |
| 21      | 1         | 0.43%   |
| 20      | 1         | 0.43%   |
| 19      | 1         | 0.43%   |
| 18      | 1         | 0.43%   |
| 11      | 1         | 0.43%   |
| 10      | 1         | 0.43%   |
| 9       | 1         | 0.43%   |
| 7       | 1         | 0.43%   |
| 3       | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 133       | 57.33%  |
| 201-300     | 26        | 11.21%  |
| 501-600     | 24        | 10.34%  |
| 351-400     | 19        | 8.19%   |
| 401-500     | 6         | 2.59%   |
| 701-800     | 4         | 1.72%   |
| 1501-2000   | 4         | 1.72%   |
| Unknown     | 4         | 1.72%   |
| 801-900     | 3         | 1.29%   |
| 601-700     | 3         | 1.29%   |
| 1001-1500   | 3         | 1.29%   |
| 1-100       | 2         | 0.86%   |
| 901-1000    | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 159       | 76.44%  |
| 16/10   | 33        | 15.87%  |
| 21/9    | 4         | 1.92%   |
| 3/2     | 3         | 1.44%   |
| Unknown | 3         | 1.44%   |
| 5/4     | 2         | 0.96%   |
| 6/5     | 1         | 0.48%   |
| 4/3     | 1         | 0.48%   |
| 0.67    | 1         | 0.48%   |
| 0.56    | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 86        | 36.91%  |
| 81-90          | 46        | 19.74%  |
| 201-250        | 15        | 6.44%   |
| 121-130        | 15        | 6.44%   |
| 71-80          | 12        | 5.15%   |
| 61-70          | 8         | 3.43%   |
| More than 1000 | 7         | 3%      |
| 301-350        | 7         | 3%      |
| 111-120        | 7         | 3%      |
| 351-500        | 6         | 2.58%   |
| 251-300        | 6         | 2.58%   |
| 501-1000       | 4         | 1.72%   |
| Unknown        | 4         | 1.72%   |
| 41-50          | 2         | 0.86%   |
| 1-40           | 2         | 0.86%   |
| 151-200        | 2         | 0.86%   |
| 141-150        | 2         | 0.86%   |
| 51-60          | 1         | 0.43%   |
| 131-140        | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 95        | 41.3%   |
| 101-120       | 55        | 23.91%  |
| 51-100        | 41        | 17.83%  |
| 161-240       | 20        | 8.7%    |
| More than 240 | 9         | 3.91%   |
| 1-50          | 6         | 2.61%   |
| Unknown       | 4         | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 145       | 74.36%  |
| 2     | 42        | 21.54%  |
| 3     | 7         | 3.59%   |
| 0     | 1         | 0.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 115       | 37.46%  |
| Realtek Semiconductor             | 86        | 28.01%  |
| Qualcomm Atheros                  | 40        | 13.03%  |
| Broadcom                          | 19        | 6.19%   |
| MediaTek                          | 6         | 1.95%   |
| Ralink                            | 4         | 1.3%    |
| Lenovo                            | 4         | 1.3%    |
| Ericsson Business Mobile Networks | 4         | 1.3%    |
| Broadcom Limited                  | 4         | 1.3%    |
| TP-Link                           | 3         | 0.98%   |
| Sierra Wireless                   | 3         | 0.98%   |
| Fibocom                           | 3         | 0.98%   |
| ASIX Electronics                  | 3         | 0.98%   |
| JMicron Technology                | 2         | 0.65%   |
| Huawei Technologies               | 2         | 0.65%   |
| Hewlett-Packard                   | 2         | 0.65%   |
| VIA Technologies                  | 1         | 0.33%   |
| Van Ooijen Technische Informatica | 1         | 0.33%   |
| OPPO Electronics                  | 1         | 0.33%   |
| Nvidia                            | 1         | 0.33%   |
| Marvell Technology Group          | 1         | 0.33%   |
| DisplayLink                       | 1         | 0.33%   |
| ASUSTek Computer                  | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 46        | 12.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 4.71%   |
| Intel Wireless 8265 / 8275                                             | 11        | 2.88%   |
| Intel Wireless 7260                                                    | 11        | 2.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 11        | 2.88%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 2.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 2.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 9         | 2.36%   |
| Intel Wireless 7265                                                    | 9         | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 1.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 1.57%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.57%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 1.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 5         | 1.31%   |
| Intel Wireless 8260                                                    | 5         | 1.31%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 1.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 1.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 1.05%   |
| Intel 82566MM Gigabit Network Connection                               | 4         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 0.79%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.79%   |
| Intel Wireless 3165                                                    | 3         | 0.79%   |
| Intel Wireless 3160                                                    | 3         | 0.79%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 0.79%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 3         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 3         | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 0.79%   |
| Intel Centrino Advanced-N 6235                                         | 3         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.79%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                      | 3         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 110       | 54.46%  |
| Qualcomm Atheros                  | 29        | 14.36%  |
| Realtek Semiconductor             | 23        | 11.39%  |
| Broadcom                          | 16        | 7.92%   |
| MediaTek                          | 6         | 2.97%   |
| Ralink                            | 4         | 1.98%   |
| Sierra Wireless                   | 3         | 1.49%   |
| Fibocom                           | 3         | 1.49%   |
| Broadcom Limited                  | 3         | 1.49%   |
| TP-Link                           | 2         | 0.99%   |
| Ericsson Business Mobile Networks | 2         | 0.99%   |
| Hewlett-Packard                   | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 11        | 5.45%   |
| Intel Wireless 7260                                                     | 11        | 5.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 5.45%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 4.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 4.46%   |
| Intel Wireless 7265                                                     | 9         | 4.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 2.48%   |
| Intel Wireless 8260                                                     | 5         | 2.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.49%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.49%   |
| Intel Wireless 3165                                                     | 3         | 1.49%   |
| Intel Wireless 3160                                                     | 3         | 1.49%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.49%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.49%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.49%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 1.49%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.99%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.99%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.99%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 73        | 42.69%  |
| Intel                    | 58        | 33.92%  |
| Qualcomm Atheros         | 18        | 10.53%  |
| Broadcom                 | 6         | 3.51%   |
| Lenovo                   | 3         | 1.75%   |
| ASIX Electronics         | 3         | 1.75%   |
| JMicron Technology       | 2         | 1.17%   |
| VIA Technologies         | 1         | 0.58%   |
| TP-Link                  | 1         | 0.58%   |
| OPPO Electronics         | 1         | 0.58%   |
| Nvidia                   | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| DisplayLink              | 1         | 0.58%   |
| Broadcom Limited         | 1         | 0.58%   |
| ASUSTek Computer         | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 46        | 26.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 10.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 5.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 3.51%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 3.51%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 3.51%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 2.92%   |
| Intel 82566MM Gigabit Network Connection                               | 4         | 2.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 1.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 1.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.75%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 1.75%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.75%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 1.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 1.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 1.17%   |
| Lenovo ThinkPad TBT3 LAN                                               | 2         | 1.17%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.17%   |
| Intel Ethernet Connection I217-V                                       | 2         | 1.17%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.17%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.17%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.17%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.58%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.58%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.58%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 1         | 0.58%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.58%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.58%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 0.58%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 1         | 0.58%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.58%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.58%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 190       | 52.49%  |
| Ethernet | 163       | 45.03%  |
| Modem    | 9         | 2.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 155       | 75.98%  |
| Ethernet | 49        | 24.02%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 152       | 79.58%  |
| 1     | 36        | 18.85%  |
| 0     | 2         | 1.05%   |
| 3     | 1         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 166       | 85.13%  |
| Yes  | 29        | 14.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 51.66%  |
| Broadcom                        | 13        | 8.61%   |
| Qualcomm Atheros Communications | 12        | 7.95%   |
| IMC Networks                    | 11        | 7.28%   |
| Realtek Semiconductor           | 9         | 5.96%   |
| Cambridge Silicon Radio         | 5         | 3.31%   |
| Apple                           | 5         | 3.31%   |
| Realtek                         | 4         | 2.65%   |
| Hewlett-Packard                 | 4         | 2.65%   |
| Foxconn / Hon Hai               | 3         | 1.99%   |
| Dell                            | 2         | 1.32%   |
| Toshiba                         | 1         | 0.66%   |
| Ralink                          | 1         | 0.66%   |
| MediaTek                        | 1         | 0.66%   |
| Lite-On Technology              | 1         | 0.66%   |
| Askey Computer                  | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 25.83%  |
| Intel AX201 Bluetooth                               | 13        | 8.61%   |
| Intel AX200 Bluetooth                               | 8         | 5.3%    |
| Realtek Bluetooth Radio                             | 6         | 3.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 3.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 3.97%   |
| IMC Networks Bluetooth Device                       | 5         | 3.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 3.31%   |
| Realtek Bluetooth Radio                             | 4         | 2.65%   |
| Intel Bluetooth Device                              | 4         | 2.65%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.99%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.99%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.99%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.99%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.99%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 1.99%   |
| Apple Bluetooth Host Controller                     | 3         | 1.99%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.32%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.32%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.32%   |
| Intel AX210 Bluetooth                               | 2         | 1.32%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.32%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.32%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.32%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.32%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.32%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.66%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.66%   |
| MediaTek Wireless_Device                            | 1         | 0.66%   |
| Lite-On Bluetooth Device                            | 1         | 0.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.66%   |
| IMC Networks Wireless_Device                        | 1         | 0.66%   |
| IMC Networks BCM20702A0                             | 1         | 0.66%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.66%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.66%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.66%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 153       | 65.38%  |
| AMD                   | 39        | 16.67%  |
| Nvidia                | 26        | 11.11%  |
| Lenovo                | 4         | 1.71%   |
| Realtek Semiconductor | 2         | 0.85%   |
| Logitech              | 2         | 0.85%   |
| VIA Technologies      | 1         | 0.43%   |
| Texas Instruments     | 1         | 0.43%   |
| TerraTec Electronic   | 1         | 0.43%   |
| Roland                | 1         | 0.43%   |
| Micronas              | 1         | 0.43%   |
| Mark of the Unicorn   | 1         | 0.43%   |
| JMTek                 | 1         | 0.43%   |
| C-Media Electronics   | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 7.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 17        | 5.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 5.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 5.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 5.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 4.47%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 3.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 3.44%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 3.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 3.09%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 3.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 2.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 1.72%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.72%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.72%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.37%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.37%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.03%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.03%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.03%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.69%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.69%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 2         | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 0.69%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 0.69%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 43        | 32.82%  |
| SK hynix            | 31        | 23.66%  |
| Micron Technology   | 19        | 14.5%   |
| Kingston            | 11        | 8.4%    |
| Crucial             | 6         | 4.58%   |
| Unknown             | 4         | 3.05%   |
| Ramaxel Technology  | 3         | 2.29%   |
| Nanya Technology    | 3         | 2.29%   |
| Unknown (ABCD)      | 2         | 1.53%   |
| G.Skill             | 2         | 1.53%   |
| ASint Technology    | 2         | 1.53%   |
| A-DATA Technology   | 2         | 1.53%   |
| Unifosa             | 1         | 0.76%   |
| Qimonda             | 1         | 0.76%   |
| Elpida              | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 5         | 3.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 2.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 2.14%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 2.14%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.43%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 2         | 1.43%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 2         | 1.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.43%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.43%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 1.43%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 1.43%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 1.43%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.43%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.43%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s                | 2         | 1.43%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 2         | 1.43%   |
| Unknown RAM Module 512MB SODIMM DDR2                                | 1         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 1         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.71%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.71%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 1         | 0.71%   |
| Unifosa RAM GU332G0AJEPR8H2L.. 2GB SODIMM DDR2 667MT/s              | 1         | 0.71%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                     | 1         | 0.71%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 1         | 0.71%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s                | 1         | 0.71%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s             | 1         | 0.71%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.71%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.71%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.71%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.71%   |
| SK hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1333MT/s              | 1         | 0.71%   |
| SK hynix RAM HMCG66AGBSA095N 8GB SODIMM DDR5 5600MT/s               | 1         | 0.71%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.71%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s             | 1         | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 44        | 42.31%  |
| DDR3   | 42        | 40.38%  |
| DDR2   | 7         | 6.73%   |
| LPDDR4 | 5         | 4.81%   |
| DDR5   | 2         | 1.92%   |
| SDRAM  | 1         | 0.96%   |
| LPDDR5 | 1         | 0.96%   |
| LPDDR3 | 1         | 0.96%   |
| DDR    | 1         | 0.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 99        | 96.12%  |
| Row Of Chips | 3         | 2.91%   |
| DIMM         | 1         | 0.97%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 46        | 39.66%  |
| 4096  | 34        | 29.31%  |
| 16384 | 16        | 13.79%  |
| 2048  | 12        | 10.34%  |
| 1024  | 5         | 4.31%   |
| 32768 | 2         | 1.72%   |
| 512   | 1         | 0.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 29        | 24.17%  |
| 2667    | 27        | 22.5%   |
| 3200    | 16        | 13.33%  |
| 1333    | 10        | 8.33%   |
| 1334    | 8         | 6.67%   |
| 2400    | 6         | 5%      |
| 2133    | 4         | 3.33%   |
| 667     | 4         | 3.33%   |
| 1067    | 3         | 2.5%    |
| 5600    | 2         | 1.67%   |
| 4267    | 2         | 1.67%   |
| 3266    | 2         | 1.67%   |
| 6400    | 1         | 0.83%   |
| 4266    | 1         | 0.83%   |
| 4199    | 1         | 0.83%   |
| 975     | 1         | 0.83%   |
| 800     | 1         | 0.83%   |
| 400     | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

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
| Chicony Electronics                    | 43        | 25.9%   |
| Microdia                               | 16        | 9.64%   |
| IMC Networks                           | 15        | 9.04%   |
| Sunplus Innovation Technology          | 14        | 8.43%   |
| Realtek Semiconductor                  | 14        | 8.43%   |
| Bison Electronics                      | 12        | 7.23%   |
| Lite-On Technology                     | 7         | 4.22%   |
| Suyin                                  | 5         | 3.01%   |
| Silicon Motion                         | 5         | 3.01%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.01%   |
| Acer                                   | 5         | 3.01%   |
| Syntek                                 | 4         | 2.41%   |
| Quanta                                 | 3         | 1.81%   |
| Luxvisions Innotech Limited            | 3         | 1.81%   |
| Apple                                  | 3         | 1.81%   |
| Sonix Technology                       | 2         | 1.2%    |
| Logitech                               | 2         | 1.2%    |
| Xiaomi                                 | 1         | 0.6%    |
| Tripath Technology                     | 1         | 0.6%    |
| LG Electronics                         | 1         | 0.6%    |
| Lenovo                                 | 1         | 0.6%    |
| Importek                               | 1         | 0.6%    |
| Huddly                                 | 1         | 0.6%    |
| Alcor Micro                            | 1         | 0.6%    |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 5.39%   |
| Chicony Integrated Camera                               | 8         | 4.79%   |
| Lite-On Integrated Camera                               | 6         | 3.59%   |
| Bison Integrated Camera                                 | 5         | 2.99%   |
| Realtek USB Camera                                      | 4         | 2.4%    |
| IMC Networks Integrated Camera                          | 4         | 2.4%    |
| Sunplus Integrated_Webcam_HD                            | 3         | 1.8%    |
| Realtek Integrated_Webcam_HD                            | 3         | 1.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.8%    |
| Chicony ThinkPad T490 Webcam                            | 3         | 1.8%    |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 1.8%    |
| Chicony Integrated HP HD Webcam                         | 3         | 1.8%    |
| Chicony HP HD Webcam                                    | 3         | 1.8%    |
| Chicony FJ Camera                                       | 3         | 1.8%    |
| Syntek Integrated Camera                                | 2         | 1.2%    |
| Sunplus Asus Webcam                                     | 2         | 1.2%    |
| Sonix USB2.0 FHD UVC WebCam                             | 2         | 1.2%    |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.2%    |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.2%    |
| Realtek Lenovo EasyCamera                               | 2         | 1.2%    |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.2%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.2%    |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.2%    |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.2%    |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.2%    |
| Chicony HD Webcam                                       | 2         | 1.2%    |
| Chicony HD User Facing                                  | 2         | 1.2%    |
| Bison SunplusIT INC. Integrated Camera                  | 2         | 1.2%    |
| Apple FaceTime HD Camera                                | 2         | 1.2%    |
| Xiaomi Mi 11 Lite                                       | 1         | 0.6%    |
| Tripath USB Camera                                      | 1         | 0.6%    |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.6%    |
| Syntek Lenovo EasyCamera                                | 1         | 0.6%    |
| Suyin USB Webcam                                        | 1         | 0.6%    |
| Suyin Intel Webcam                                      | 1         | 0.6%    |
| Suyin Integrated_Webcam_HD                              | 1         | 0.6%    |
| Suyin HD WebCam                                         | 1         | 0.6%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.6%    |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.6%    |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 22        | 44.9%   |
| Synaptics                          | 11        | 22.45%  |
| Upek                               | 4         | 8.16%   |
| STMicroelectronics                 | 4         | 8.16%   |
| Shenzhen Goodix Technology         | 4         | 8.16%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.04%   |
| LighTuning Technology              | 1         | 2.04%   |
| Elan Microelectronics              | 1         | 2.04%   |
| AuthenTec                          | 1         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 12.24%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 6         | 12.24%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 10.2%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 8.16%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 4         | 8.16%   |
| STMicroelectronics Fingerprint Reader                           | 4         | 8.16%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 6.12%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 4.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 4.08%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 4.08%   |
| Shenzhen Goodix FingerPrint                                     | 2         | 4.08%   |
| Validity Sensors VFS491                                         | 1         | 2.04%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 2.04%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 2.04%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.04%   |
| Synaptics WBDI                                                  | 1         | 2.04%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 2.04%   |
| Elan ELAN:Fingerprint                                           | 1         | 2.04%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 23        | 56.1%   |
| OmniKey               | 6         | 14.63%  |
| Broadcom              | 5         | 12.2%   |
| Lenovo                | 3         | 7.32%   |
| Gemalto (was Gemplus) | 3         | 7.32%   |
| O2 Micro              | 1         | 2.44%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 56.1%   |
| OmniKey CardMan 4321                                                         | 3         | 7.32%   |
| OmniKey CardMan 1021                                                         | 3         | 7.32%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 7.32%   |
| Broadcom 58200                                                               | 3         | 7.32%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 4.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 4.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.44%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2.44%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 107       | 55.44%  |
| 1     | 62        | 32.12%  |
| 2     | 22        | 11.4%   |
| 4     | 1         | 0.52%   |
| 3     | 1         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 49        | 44.55%  |
| Chipcard                 | 22        | 20%     |
| Graphics card            | 20        | 18.18%  |
| Camera                   | 5         | 4.55%   |
| Net/wireless             | 4         | 3.64%   |
| Multimedia controller    | 3         | 2.73%   |
| Card reader              | 2         | 1.82%   |
| Storage                  | 1         | 0.91%   |
| Net/ethernet             | 1         | 0.91%   |
| Modem                    | 1         | 0.91%   |
| Communication controller | 1         | 0.91%   |
| Bluetooth                | 1         | 0.91%   |

