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

Total: 227

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 19        | 10.98%  |
| Ubuntu 18.04       | 14        | 8.09%   |
| Ubuntu 22.04       | 12        | 6.94%   |
| Arch               | 7         | 4.05%   |
| Ubuntu 19.04       | 6         | 3.47%   |
| ArcoLinux Rolling  | 6         | 3.47%   |
| Linux Mint 20.1    | 5         | 2.89%   |
| Kubuntu 22.04      | 4         | 2.31%   |
| Fedora 34          | 4         | 2.31%   |
| ROSA R9            | 3         | 1.73%   |
| ROSA R8.1          | 3         | 1.73%   |
| ROSA R11           | 3         | 1.73%   |
| Pop!_OS 20.04      | 3         | 1.73%   |
| OpenMandriva 4.2   | 3         | 1.73%   |
| Kubuntu 20.04      | 3         | 1.73%   |
| Fedora 36          | 3         | 1.73%   |
| Arch Rolling       | 3         | 1.73%   |
| Zorin 16           | 2         | 1.16%   |
| Xubuntu 20.04      | 2         | 1.16%   |
| Ubuntu MATE 22.04  | 2         | 1.16%   |
| Ubuntu 20.10       | 2         | 1.16%   |
| Ubuntu 19.10       | 2         | 1.16%   |
| ROSA 12.2          | 2         | 1.16%   |
| Reborn OS          | 2         | 1.16%   |
| Manjaro 20.1       | 2         | 1.16%   |
| Manjaro            | 2         | 1.16%   |
| Linux Mint 20.3    | 2         | 1.16%   |
| Linux Mint 20.2    | 2         | 1.16%   |
| Linux Mint 19.3    | 2         | 1.16%   |
| Linux Mint 18.3    | 2         | 1.16%   |
| KDE neon 20.04     | 2         | 1.16%   |
| Kali 2023.1        | 2         | 1.16%   |
| Elementary 6.1     | 2         | 1.16%   |
| Debian 11          | 2         | 1.16%   |
| Zorin 15           | 1         | 0.58%   |
| Xubuntu 22.10      | 1         | 0.58%   |
| Xubuntu 18.04      | 1         | 0.58%   |
| Ubuntu Unity 16.04 | 1         | 0.58%   |
| Ubuntu MATE 20.04  | 1         | 0.58%   |
| Ubuntu 21.04       | 1         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 56        | 32.94%  |
| ROSA         | 14        | 8.24%   |
| Linux Mint   | 14        | 8.24%   |
| Fedora       | 10        | 5.88%   |
| Arch         | 10        | 5.88%   |
| Manjaro      | 8         | 4.71%   |
| Pop!_OS      | 6         | 3.53%   |
| Kubuntu      | 6         | 3.53%   |
| ArcoLinux    | 6         | 3.53%   |
| OpenMandriva | 5         | 2.94%   |
| Xubuntu      | 4         | 2.35%   |
| Endless      | 4         | 2.35%   |
| Zorin        | 3         | 1.76%   |
| Ubuntu MATE  | 3         | 1.76%   |
| KDE neon     | 3         | 1.76%   |
| Elementary   | 3         | 1.76%   |
| Debian       | 3         | 1.76%   |
| SteamOS      | 2         | 1.18%   |
| Reborn OS    | 2         | 1.18%   |
| Kali         | 2         | 1.18%   |
| Clear Linux  | 2         | 1.18%   |
| Ubuntu Unity | 1         | 0.59%   |
| Lubuntu      | 1         | 0.59%   |
| LMDE         | 1         | 0.59%   |
| EndeavourOS  | 1         | 0.59%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 6         | 3.21%   |
| 5.15.0-52-generic                  | 4         | 2.14%   |
| 5.4.0-47-generic                   | 3         | 1.6%    |
| 5.4.0-28-generic                   | 3         | 1.6%    |
| 5.15.0-53-generic                  | 3         | 1.6%    |
| 5.10.14-desktop-1omv4002           | 3         | 1.6%    |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 1.6%    |
| 6.1.0-kali7-amd64                  | 2         | 1.07%   |
| 5.8.0-53-generic                   | 2         | 1.07%   |
| 5.4.0-88-generic                   | 2         | 1.07%   |
| 5.4.0-65-generic                   | 2         | 1.07%   |
| 5.15.2-arch1-1                     | 2         | 1.07%   |
| 5.15.0-56-generic                  | 2         | 1.07%   |
| 5.13.0-39-generic                  | 2         | 1.07%   |
| 5.11.0-27-generic                  | 2         | 1.07%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 1.07%   |
| 5.0.0-23-generic                   | 2         | 1.07%   |
| 4.18.0-15-generic                  | 2         | 1.07%   |
| 4.15.0-45-generic                  | 2         | 1.07%   |
| 6.3.1-arch1-1                      | 1         | 0.53%   |
| 6.2.7-arch1-1                      | 1         | 0.53%   |
| 6.2.6-76060206-generic             | 1         | 0.53%   |
| 6.1.5-arch2-1                      | 1         | 0.53%   |
| 6.1.1-desktop-1omv2290             | 1         | 0.53%   |
| 6.0.9-arch1-1                      | 1         | 0.53%   |
| 6.0.9-300.fc37.x86_64              | 1         | 0.53%   |
| 6.0.8-1-MANJARO                    | 1         | 0.53%   |
| 6.0.5-200.fc36.x86_64              | 1         | 0.53%   |
| 6.0.2-2-MANJARO                    | 1         | 0.53%   |
| 5.9.16-1-MANJARO                   | 1         | 0.53%   |
| 5.9.13-200.fc33.x86_64             | 1         | 0.53%   |
| 5.9.10-zen1-1-zen                  | 1         | 0.53%   |
| 5.9.0-050900rc5-lowlatency         | 1         | 0.53%   |
| 5.8.6-1-MANJARO                    | 1         | 0.53%   |
| 5.8.0-7630-generic                 | 1         | 0.53%   |
| 5.8.0-63-generic                   | 1         | 0.53%   |
| 5.8.0-59-generic                   | 1         | 0.53%   |
| 5.8.0-54-generic                   | 1         | 0.53%   |
| 5.8.0-50-generic                   | 1         | 0.53%   |
| 5.8.0-45-generic                   | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 32        | 17.68%  |
| 5.15.0  | 17        | 9.39%   |
| 4.15.0  | 13        | 7.18%   |
| 5.8.0   | 9         | 4.97%   |
| 5.11.0  | 8         | 4.42%   |
| 5.13.0  | 7         | 3.87%   |
| 5.0.0   | 7         | 3.87%   |
| 4.18.0  | 5         | 2.76%   |
| 4.9.20  | 4         | 2.21%   |
| 5.3.0   | 3         | 1.66%   |
| 5.19.0  | 3         | 1.66%   |
| 5.10.14 | 3         | 1.66%   |
| 6.1.0   | 2         | 1.1%    |
| 6.0.9   | 2         | 1.1%    |
| 5.17.1  | 2         | 1.1%    |
| 5.15.2  | 2         | 1.1%    |
| 5.13.13 | 2         | 1.1%    |
| 5.13.12 | 2         | 1.1%    |
| 5.11.12 | 2         | 1.1%    |
| 5.10.74 | 2         | 1.1%    |
| 6.3.1   | 1         | 0.55%   |
| 6.2.7   | 1         | 0.55%   |
| 6.2.6   | 1         | 0.55%   |
| 6.1.5   | 1         | 0.55%   |
| 6.1.1   | 1         | 0.55%   |
| 6.0.8   | 1         | 0.55%   |
| 6.0.5   | 1         | 0.55%   |
| 6.0.2   | 1         | 0.55%   |
| 5.9.16  | 1         | 0.55%   |
| 5.9.13  | 1         | 0.55%   |
| 5.9.10  | 1         | 0.55%   |
| 5.9.0   | 1         | 0.55%   |
| 5.8.6   | 1         | 0.55%   |
| 5.6.13  | 1         | 0.55%   |
| 5.5.6   | 1         | 0.55%   |
| 5.4.64  | 1         | 0.55%   |
| 5.19.8  | 1         | 0.55%   |
| 5.17.6  | 1         | 0.55%   |
| 5.17.4  | 1         | 0.55%   |
| 5.16.9  | 1         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 33        | 18.23%  |
| 5.15    | 22        | 12.15%  |
| 5.13    | 16        | 8.84%   |
| 4.15    | 13        | 7.18%   |
| 5.11    | 11        | 6.08%   |
| 5.10    | 11        | 6.08%   |
| 5.8     | 10        | 5.52%   |
| 5.0     | 8         | 4.42%   |
| 4.9     | 7         | 3.87%   |
| 6.0     | 5         | 2.76%   |
| 4.18    | 5         | 2.76%   |
| 6.1     | 4         | 2.21%   |
| 5.9     | 4         | 2.21%   |
| 5.19    | 4         | 2.21%   |
| 5.17    | 4         | 2.21%   |
| 5.16    | 4         | 2.21%   |
| 5.3     | 3         | 1.66%   |
| 5.14    | 3         | 1.66%   |
| 5.12    | 3         | 1.66%   |
| 6.2     | 2         | 1.1%    |
| 4.19    | 2         | 1.1%    |
| 6.3     | 1         | 0.55%   |
| 5.6     | 1         | 0.55%   |
| 5.5     | 1         | 0.55%   |
| 4.4     | 1         | 0.55%   |
| 4.10    | 1         | 0.55%   |
| 4.1     | 1         | 0.55%   |
| 3.16    | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 162       | 97.01%  |
| i686   | 5         | 2.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 62        | 36.47%  |
| Unknown    | 26        | 15.29%  |
| KDE5       | 23        | 13.53%  |
| XFCE       | 14        | 8.24%   |
| X-Cinnamon | 10        | 5.88%   |
| KDE4       | 8         | 4.71%   |
| MATE       | 7         | 4.12%   |
| Pantheon   | 3         | 1.76%   |
| KDE        | 3         | 1.76%   |
| i3         | 3         | 1.76%   |
| Unity      | 2         | 1.18%   |
| LXQt       | 2         | 1.18%   |
| LXDE       | 2         | 1.18%   |
| awesome    | 2         | 1.18%   |
| openbox    | 1         | 0.59%   |
| Cinnamon   | 1         | 0.59%   |
| Budgie     | 1         | 0.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 130       | 77.84%  |
| Wayland | 26        | 15.57%  |
| Unknown | 10        | 5.99%   |
| Tty     | 1         | 0.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 82        | 48.24%  |
| SDDM    | 25        | 14.71%  |
| GDM     | 19        | 11.18%  |
| GDM3    | 17        | 10%     |
| LightDM | 10        | 5.88%   |
| TDM     | 9         | 5.29%   |
| KDM     | 8         | 4.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 82        | 48.52%  |
| Unknown         | 33        | 19.53%  |
| et_EE           | 27        | 15.98%  |
| ru_RU           | 13        | 7.69%   |
| en_GB           | 6         | 3.55%   |
| de_DE           | 2         | 1.18%   |
| uk_UA           | 1         | 0.59%   |
| ru_UA           | 1         | 0.59%   |
| fr_FR           | 1         | 0.59%   |
| en_US.iso885915 | 1         | 0.59%   |
| en_DK           | 1         | 0.59%   |
| C               | 1         | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 87        | 50.88%  |
| EFI  | 84        | 49.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 127       | 76.05%  |
| Btrfs   | 18        | 10.78%  |
| Unknown | 12        | 7.19%   |
| Overlay | 6         | 3.59%   |
| Xfs     | 2         | 1.2%    |
| Zfs     | 1         | 0.6%    |
| Ext3    | 1         | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 88        | 52.38%  |
| GPT     | 61        | 36.31%  |
| MBR     | 19        | 11.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 154       | 91.12%  |
| Yes       | 15        | 8.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 71.18%  |
| Yes       | 49        | 28.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 50        | 29.94%  |
| Hewlett-Packard     | 30        | 17.96%  |
| Dell                | 21        | 12.57%  |
| ASUSTek Computer    | 20        | 11.98%  |
| Samsung Electronics | 7         | 4.19%   |
| Acer                | 6         | 3.59%   |
| MSI                 | 5         | 2.99%   |
| Apple               | 4         | 2.4%    |
| Fujitsu             | 3         | 1.8%    |
| Valve               | 2         | 1.2%    |
| Timi                | 2         | 1.2%    |
| Quanta              | 2         | 1.2%    |
| Notebook            | 2         | 1.2%    |
| Alienware           | 2         | 1.2%    |
| TUXEDO              | 1         | 0.6%    |
| Toshiba             | 1         | 0.6%    |
| Packard Bell        | 1         | 0.6%    |
| mPTech              | 1         | 0.6%    |
| HUAWEI              | 1         | 0.6%    |
| GPD                 | 1         | 0.6%    |
| Gigabyte Technology | 1         | 0.6%    |
| Getac               | 1         | 0.6%    |
| Fujitsu Siemens     | 1         | 0.6%    |
| Framework           | 1         | 0.6%    |
| Chuwi               | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 2         | 1.2%    |
| Quanta TWH                                            | 2         | 1.2%    |
| Lenovo Y50-70 20378                                   | 2         | 1.2%    |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 1.2%    |
| HP Pavilion dv7                                       | 2         | 1.2%    |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 1.2%    |
| HP EliteBook 8470p                                    | 2         | 1.2%    |
| HP EliteBook 8460p                                    | 2         | 1.2%    |
| HP EliteBook 840 G2                                   | 2         | 1.2%    |
| Dell Inspiron N5110                                   | 2         | 1.2%    |
| Alienware 17                                          | 2         | 1.2%    |
| TUXEDO Book BA1510                                    | 1         | 0.6%    |
| Toshiba Satellite L855                                | 1         | 0.6%    |
| Timi RedmiBook 16                                     | 1         | 0.6%    |
| Timi RedmiBook 14 II                                  | 1         | 0.6%    |
| Samsung R410                                          | 1         | 0.6%    |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.6%    |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.6%    |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.6%    |
| Samsung 535U3C                                        | 1         | 0.6%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.6%    |
| Samsung 275E4E/275E5E                                 | 1         | 0.6%    |
| Packard Bell EasyNote TK87                            | 1         | 0.6%    |
| Notebook W35xSS_370SS                                 | 1         | 0.6%    |
| Notebook N150SD/N155SD                                | 1         | 0.6%    |
| MSI GT70 2OC/2OD                                      | 1         | 0.6%    |
| MSI GS75 Stealth 8SE                                  | 1         | 0.6%    |
| MSI GP62M 7RDX                                        | 1         | 0.6%    |
| MSI GL72 6QD                                          | 1         | 0.6%    |
| MSI GF63 Thin 10SCXR                                  | 1         | 0.6%    |
| mPTech ARC 11.6 128GB HD                              | 1         | 0.6%    |
| Lenovo Y720-15IKB 80VR                                | 1         | 0.6%    |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.6%    |
| Lenovo V110-15ISK 80TL                                | 1         | 0.6%    |
| Lenovo ThinkPad X260 20F5S84400                       | 1         | 0.6%    |
| Lenovo ThinkPad X240 20AMA0W706                       | 1         | 0.6%    |
| Lenovo ThinkPad X220 4291R30                          | 1         | 0.6%    |
| Lenovo ThinkPad X220 429136G                          | 1         | 0.6%    |
| Lenovo ThinkPad X201 3680CG7                          | 1         | 0.6%    |
| Lenovo ThinkPad X13 Gen 1 20UF0020MX                  | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 38        | 22.75%  |
| HP EliteBook          | 12        | 7.19%   |
| HP Pavilion           | 7         | 4.19%   |
| Dell Inspiron         | 6         | 3.59%   |
| Dell Latitude         | 5         | 2.99%   |
| Dell Precision        | 4         | 2.4%    |
| ASUS VivoBook         | 4         | 2.4%    |
| Acer Aspire           | 4         | 2.4%    |
| Lenovo IdeaPad        | 3         | 1.8%    |
| Fujitsu LIFEBOOK      | 3         | 1.8%    |
| Dell XPS              | 3         | 1.8%    |
| Valve Jupiter         | 2         | 1.2%    |
| Timi RedmiBook        | 2         | 1.2%    |
| Samsung 900X3C        | 2         | 1.2%    |
| Quanta TWH            | 2         | 1.2%    |
| Lenovo Y50-70         | 2         | 1.2%    |
| Lenovo Legion         | 2         | 1.2%    |
| HP Presario           | 2         | 1.2%    |
| HP OMEN               | 2         | 1.2%    |
| HP ENVY               | 2         | 1.2%    |
| HP Compaq             | 2         | 1.2%    |
| ASUS ZenBook          | 2         | 1.2%    |
| Alienware 17          | 2         | 1.2%    |
| TUXEDO Book           | 1         | 0.6%    |
| Toshiba Satellite     | 1         | 0.6%    |
| Samsung R410          | 1         | 0.6%    |
| Samsung 770Z5E        | 1         | 0.6%    |
| Samsung 535U3C        | 1         | 0.6%    |
| Samsung 300E5EV       | 1         | 0.6%    |
| Samsung 275E4E        | 1         | 0.6%    |
| Packard Bell EasyNote | 1         | 0.6%    |
| Notebook W35xSS       | 1         | 0.6%    |
| Notebook N150SD       | 1         | 0.6%    |
| MSI GT70              | 1         | 0.6%    |
| MSI GS75              | 1         | 0.6%    |
| MSI GP62M             | 1         | 0.6%    |
| MSI GL72              | 1         | 0.6%    |
| MSI GF63              | 1         | 0.6%    |
| mPTech ARC            | 1         | 0.6%    |
| Lenovo Y720-15IKB     | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 20        | 11.98%  |
| 2013 | 18        | 10.78%  |
| 2011 | 17        | 10.18%  |
| 2018 | 15        | 8.98%   |
| 2019 | 13        | 7.78%   |
| 2014 | 13        | 7.78%   |
| 2015 | 11        | 6.59%   |
| 2012 | 11        | 6.59%   |
| 2017 | 9         | 5.39%   |
| 2008 | 7         | 4.19%   |
| 2007 | 7         | 4.19%   |
| 2022 | 6         | 3.59%   |
| 2021 | 6         | 3.59%   |
| 2010 | 6         | 3.59%   |
| 2016 | 5         | 2.99%   |
| 2009 | 2         | 1.2%    |
| 2006 | 1         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 167       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 152       | 90.48%  |
| Enabled  | 16        | 9.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 167       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 41        | 24.26%  |
| 4.01-8.0    | 39        | 23.08%  |
| 3.01-4.0    | 30        | 17.75%  |
| 16.01-24.0  | 30        | 17.75%  |
| 32.01-64.0  | 9         | 5.33%   |
| 24.01-32.0  | 7         | 4.14%   |
| 2.01-3.0    | 7         | 4.14%   |
| 1.01-2.0    | 5         | 2.96%   |
| 64.01-256.0 | 1         | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 62        | 34.83%  |
| 2.01-3.0   | 42        | 23.6%   |
| 4.01-8.0   | 33        | 18.54%  |
| 3.01-4.0   | 20        | 11.24%  |
| 8.01-16.0  | 10        | 5.62%   |
| 0.51-1.0   | 9         | 5.06%   |
| 24.01-32.0 | 1         | 0.56%   |
| 16.01-24.0 | 1         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 129       | 75.44%  |
| 2      | 34        | 19.88%  |
| 3      | 6         | 3.51%   |
| 5      | 1         | 0.58%   |
| 4      | 1         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 110       | 64.71%  |
| Yes       | 60        | 35.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 85.12%  |
| No        | 25        | 14.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 99.4%   |
| No        | 1         | 0.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 78.57%  |
| No        | 36        | 21.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Estonia | 167       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Tallinn           | 111       | 65.68%  |
| Tartu             | 15        | 8.88%   |
| Pärnu            | 7         | 4.14%   |
| Rapla             | 4         | 2.37%   |
| Narva             | 4         | 2.37%   |
| Rakvere           | 3         | 1.78%   |
| Vinni             | 2         | 1.18%   |
| Saku              | 2         | 1.18%   |
| Otepaeae          | 2         | 1.18%   |
| Maardu            | 2         | 1.18%   |
| Keila             | 2         | 1.18%   |
| Viljandi          | 1         | 0.59%   |
| Vatla             | 1         | 0.59%   |
| Tabasalu          | 1         | 0.59%   |
| Sillamäe         | 1         | 0.59%   |
| Sauga             | 1         | 0.59%   |
| Rae Parish        | 1         | 0.59%   |
| Põlva            | 1         | 0.59%   |
| Pohja-Sakala vald | 1         | 0.59%   |
| Laagri            | 1         | 0.59%   |
| Kärdla           | 1         | 0.59%   |
| Kaeina            | 1         | 0.59%   |
| Jüri             | 1         | 0.59%   |
| Jõhvi            | 1         | 0.59%   |
| Jõgeva           | 1         | 0.59%   |
| AEaesmaee         | 1         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 44        | 52     | 21.15%  |
| Seagate                     | 28        | 31     | 13.46%  |
| Toshiba                     | 17        | 17     | 8.17%   |
| WDC                         | 14        | 16     | 6.73%   |
| Kingston                    | 14        | 15     | 6.73%   |
| SK hynix                    | 13        | 17     | 6.25%   |
| Intel                       | 8         | 9      | 3.85%   |
| Sandisk                     | 7         | 9      | 3.37%   |
| HGST                        | 7         | 8      | 3.37%   |
| Unknown                     | 6         | 6      | 2.88%   |
| Hitachi                     | 5         | 5      | 2.4%    |
| Patriot                     | 3         | 4      | 1.44%   |
| Micron Technology           | 3         | 3      | 1.44%   |
| Lenovo                      | 3         | 3      | 1.44%   |
| Crucial                     | 3         | 3      | 1.44%   |
| A-DATA Technology           | 3         | 3      | 1.44%   |
| Transcend                   | 2         | 5      | 0.96%   |
| Phison Electronics          | 2         | 2      | 0.96%   |
| LITEONIT                    | 2         | 2      | 0.96%   |
| KingSpec                    | 2         | 3      | 0.96%   |
| Gigabyte Technology         | 2         | 3      | 0.96%   |
| Fujitsu                     | 2         | 2      | 0.96%   |
| China                       | 2         | 2      | 0.96%   |
| Apacer                      | 2         | 2      | 0.96%   |
| SPCC                        | 1         | 1      | 0.48%   |
| PNY                         | 1         | 1      | 0.48%   |
| Phison                      | 1         | 1      | 0.48%   |
| Netac                       | 1         | 1      | 0.48%   |
| Lexar                       | 1         | 1      | 0.48%   |
| KIOXIA                      | 1         | 2      | 0.48%   |
| Kingston Technology Company | 1         | 1      | 0.48%   |
| Intenso                     | 1         | 1      | 0.48%   |
| HUAWEI                      | 1         | 1      | 0.48%   |
| External                    | 1         | 1      | 0.48%   |
| ASMT109x                    | 1         | 2      | 0.48%   |
| Apple                       | 1         | 1      | 0.48%   |
| ADATA Technology            | 1         | 1      | 0.48%   |
| Unknown                     | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 1.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 1.4%    |
| HGST HTS721010A9E630 1TB                            | 3         | 1.4%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 2         | 0.93%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB                | 2         | 0.93%   |
| Unknown MMC Card  16GB                              | 2         | 0.93%   |
| Toshiba NVMe SSD Drive 512GB                        | 2         | 0.93%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.93%   |
| SK hynix NVMe SSD Drive 512GB                       | 2         | 0.93%   |
| SK hynix NVMe SSD Drive 256GB                       | 2         | 0.93%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.93%   |
| Seagate BUP Portable 5TB                            | 2         | 0.93%   |
| SanDisk SD8SBAT256G1122 256GB SSD                   | 2         | 0.93%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2         | 0.93%   |
| Samsung SSD 850 EVO M.2 500GB                       | 2         | 0.93%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.93%   |
| Samsung NVMe SSD Drive 512GB                        | 2         | 0.93%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 0.93%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 0.93%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 2         | 0.93%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD                | 2         | 0.93%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                 | 2         | 0.93%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.93%   |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.93%   |
| Intel SSDPEKKF256G8L 256GB                          | 2         | 0.93%   |
| HGST HTS541010A9E680 1TB                            | 2         | 0.93%   |
| WDC WDS500G2B0B 500GB SSD                           | 1         | 0.47%   |
| WDC WDS500G1X0E-00AFY0 500GB                        | 1         | 0.47%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                    | 1         | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.47%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 0.47%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 0.47%   |
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 0.47%   |
| WDC WD1200BEVS-08RST2 120GB                         | 1         | 0.47%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                  | 1         | 0.47%   |
| WDC PC SN730 NVMe 512GB                             | 1         | 0.47%   |
| Unknown MMC128  128GB                               | 1         | 0.47%   |
| Unknown MMC Card  7GB                               | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 27        | 30     | 50%     |
| Toshiba  | 8         | 8      | 14.81%  |
| HGST     | 7         | 8      | 12.96%  |
| Hitachi  | 5         | 5      | 9.26%   |
| WDC      | 4         | 5      | 7.41%   |
| Fujitsu  | 2         | 2      | 3.7%    |
| External | 1         | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 29     | 30.86%  |
| Kingston            | 12        | 13     | 14.81%  |
| SanDisk             | 5         | 7      | 6.17%   |
| SK hynix            | 4         | 4      | 4.94%   |
| WDC                 | 3         | 4      | 3.7%    |
| Patriot             | 3         | 4      | 3.7%    |
| Micron Technology   | 3         | 3      | 3.7%    |
| Crucial             | 3         | 3      | 3.7%    |
| A-DATA Technology   | 3         | 3      | 3.7%    |
| Transcend           | 2         | 5      | 2.47%   |
| Toshiba             | 2         | 2      | 2.47%   |
| LITEONIT            | 2         | 2      | 2.47%   |
| KingSpec            | 2         | 3      | 2.47%   |
| Intel               | 2         | 3      | 2.47%   |
| China               | 2         | 2      | 2.47%   |
| Apacer              | 2         | 2      | 2.47%   |
| SPCC                | 1         | 1      | 1.23%   |
| Netac               | 1         | 1      | 1.23%   |
| Lexar               | 1         | 1      | 1.23%   |
| Intenso             | 1         | 1      | 1.23%   |
| Gigabyte Technology | 1         | 2      | 1.23%   |
| Apple               | 1         | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 71        | 96     | 37.57%  |
| NVMe    | 56        | 72     | 29.63%  |
| HDD     | 52        | 59     | 27.51%  |
| MMC     | 7         | 7      | 3.7%    |
| Unknown | 3         | 4      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 112       | 150    | 60.87%  |
| NVMe | 56        | 72     | 30.43%  |
| SAS  | 9         | 9      | 4.89%   |
| MMC  | 7         | 7      | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 88        | 108    | 68.22%  |
| 0.51-1.0   | 35        | 41     | 27.13%  |
| 1.01-2.0   | 3         | 3      | 2.33%   |
| 4.01-10.0  | 2         | 2      | 1.55%   |
| 3.01-4.0   | 1         | 1      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 59        | 34.1%   |
| 251-500        | 36        | 20.81%  |
| 501-1000       | 24        | 13.87%  |
| 1-20           | 15        | 8.67%   |
| 51-100         | 13        | 7.51%   |
| 1001-2000      | 9         | 5.2%    |
| Unknown        | 6         | 3.47%   |
| More than 3000 | 5         | 2.89%   |
| 21-50          | 5         | 2.89%   |
| 2001-3000      | 1         | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 73        | 41.01%  |
| 21-50          | 28        | 15.73%  |
| 101-250        | 23        | 12.92%  |
| 51-100         | 22        | 12.36%  |
| 251-500        | 15        | 8.43%   |
| 501-1000       | 7         | 3.93%   |
| Unknown        | 6         | 3.37%   |
| More than 3000 | 2         | 1.12%   |
| 2001-3000      | 1         | 0.56%   |
| 1001-2000      | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 6.67%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 6.67%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 6.67%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 6.67%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 6.67%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 6.67%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 6.67%   |
| Netac SSD 720GB                                     | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 6.67%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 6.67%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 6.67%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 6.67%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 6.67%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 7         | 7      | 46.67%  |
| WDC               | 1         | 1      | 6.67%   |
| Netac             | 1         | 1      | 6.67%   |
| Micron Technology | 1         | 1      | 6.67%   |
| Kingston          | 1         | 1      | 6.67%   |
| Hitachi           | 1         | 1      | 6.67%   |
| HGST              | 1         | 1      | 6.67%   |
| Fujitsu           | 1         | 1      | 6.67%   |
| Crucial           | 1         | 1      | 6.67%   |

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
| HDD  | 11        | 11     | 73.33%  |
| SSD  | 4         | 4      | 26.67%  |

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
| Detected | 98        | 147    | 56.32%  |
| Works    | 62        | 76     | 35.63%  |
| Malfunc  | 14        | 15     | 8.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 121       | 61.11%  |
| Samsung Electronics          | 20        | 10.1%   |
| AMD                          | 18        | 9.09%   |
| SK hynix                     | 9         | 4.55%   |
| SanDisk                      | 8         | 4.04%   |
| Toshiba America Info Systems | 6         | 3.03%   |
| Phison Electronics           | 4         | 2.02%   |
| Lenovo                       | 3         | 1.52%   |
| Kingston Technology Company  | 3         | 1.52%   |
| KIOXIA                       | 2         | 1.01%   |
| VIA Technologies             | 1         | 0.51%   |
| Nvidia                       | 1         | 0.51%   |
| Marvell Technology Group     | 1         | 0.51%   |
| ADATA Technology             | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 7.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 6.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 6.54%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 6.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 6.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 4.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 3.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 3.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 3.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 2.8%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 2.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 2.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.87%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.4%    |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 3         | 1.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.4%    |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.93%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.93%   |
| SanDisk NVMe Controller                                                        | 2         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.93%   |
| Lenovo Non-Volatile memory controller                                          | 2         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 0.93%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 0.93%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.93%   |
| Intel SSD 660P Series                                                          | 2         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.93%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 2         | 0.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 0.93%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.47%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 127       | 61.95%  |
| NVMe | 57        | 27.8%   |
| IDE  | 14        | 6.83%   |
| RAID | 7         | 3.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 136       | 81.44%  |
| AMD    | 31        | 18.56%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 4.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.4%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.8%    |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 3         | 1.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.8%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.2%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.2%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 1.2%    |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 1.2%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 1.2%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.2%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.2%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.2%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.2%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.2%    |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 1.2%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.2%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.2%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.2%    |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.2%    |
| Intel Celeron CPU 1000M @ 1.80GHz             | 2         | 1.2%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.2%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.2%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.2%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.2%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.2%    |
| AMD Custom APU 0405                           | 2         | 1.2%    |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.6%    |
| Intel Pentium M processor 2.13GHz             | 1         | 0.6%    |
| Intel Pentium M processor 1.50GHz             | 1         | 0.6%    |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.6%    |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 49        | 29.34%  |
| Intel Core i5                  | 44        | 26.35%  |
| AMD Ryzen 5                    | 9         | 5.39%   |
| Other                          | 8         | 4.79%   |
| Intel Core i3                  | 8         | 4.79%   |
| Intel Core 2 Duo               | 8         | 4.79%   |
| Intel Celeron                  | 8         | 4.79%   |
| AMD Ryzen 7                    | 6         | 3.59%   |
| Intel Pentium                  | 3         | 1.8%    |
| AMD Ryzen 7 PRO                | 3         | 1.8%    |
| Intel Pentium M                | 2         | 1.2%    |
| Intel Celeron Dual-Core        | 2         | 1.2%    |
| Intel Pentium Silver           | 1         | 0.6%    |
| Intel Pentium Dual             | 1         | 0.6%    |
| Intel Core i9                  | 1         | 0.6%    |
| Intel Core 2                   | 1         | 0.6%    |
| Intel Celeron M                | 1         | 0.6%    |
| Intel Atom                     | 1         | 0.6%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.6%    |
| AMD Ryzen 5 PRO                | 1         | 0.6%    |
| AMD Ryzen 3 PRO                | 1         | 0.6%    |
| AMD E2                         | 1         | 0.6%    |
| AMD E                          | 1         | 0.6%    |
| AMD C-60                       | 1         | 0.6%    |
| AMD Athlon II Dual-Core        | 1         | 0.6%    |
| AMD Athlon 64 X2               | 1         | 0.6%    |
| AMD A8                         | 1         | 0.6%    |
| AMD A6                         | 1         | 0.6%    |
| AMD A4                         | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 79        | 47.31%  |
| 4       | 56        | 33.53%  |
| 6       | 17        | 10.18%  |
| 8       | 8         | 4.79%   |
| 1       | 5         | 2.99%   |
| Unknown | 2         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 167       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 125       | 74.4%   |
| 1       | 41        | 24.4%   |
| Unknown | 2         | 1.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 164       | 98.2%   |
| 32-bit         | 2         | 1.2%    |
| Unknown        | 1         | 0.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 21.64%  |
| 0x306a9    | 13        | 7.6%    |
| 0x206a7    | 12        | 7.02%   |
| 0x306c3    | 11        | 6.43%   |
| 0x806ea    | 8         | 4.68%   |
| 0x40651    | 7         | 4.09%   |
| 0x08600106 | 7         | 4.09%   |
| 0x306d4    | 6         | 3.51%   |
| 0x906e9    | 5         | 2.92%   |
| 0xa0652    | 4         | 2.34%   |
| 0x806ec    | 4         | 2.34%   |
| 0x806c1    | 4         | 2.34%   |
| 0x6fb      | 4         | 2.34%   |
| 0x20655    | 4         | 2.34%   |
| 0x1067a    | 4         | 2.34%   |
| 0x906ea    | 3         | 1.75%   |
| 0x6fd      | 3         | 1.75%   |
| 0x506e3    | 3         | 1.75%   |
| 0x406e3    | 3         | 1.75%   |
| 0x05000119 | 3         | 1.75%   |
| 0x806e9    | 2         | 1.17%   |
| 0x706a1    | 2         | 1.17%   |
| 0x6d8      | 2         | 1.17%   |
| 0x30678    | 2         | 1.17%   |
| 0x0a50000c | 2         | 1.17%   |
| 0x08108102 | 2         | 1.17%   |
| 0x906ed    | 1         | 0.58%   |
| 0x806eb    | 1         | 0.58%   |
| 0x806d1    | 1         | 0.58%   |
| 0x706a8    | 1         | 0.58%   |
| 0x6fa      | 1         | 0.58%   |
| 0x6f6      | 1         | 0.58%   |
| 0x30661    | 1         | 0.58%   |
| 0x0a404102 | 1         | 0.58%   |
| 0x08608103 | 1         | 0.58%   |
| 0x08600103 | 1         | 0.58%   |
| 0x0810100b | 1         | 0.58%   |
| 0x06001119 | 1         | 0.58%   |
| 0x02000032 | 1         | 0.58%   |
| 0x01000098 | 1         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 30        | 17.96%  |
| Haswell         | 24        | 14.37%  |
| IvyBridge       | 15        | 8.98%   |
| SandyBridge     | 14        | 8.38%   |
| Zen 2           | 10        | 5.99%   |
| Core            | 9         | 5.39%   |
| Skylake         | 7         | 4.19%   |
| Broadwell       | 7         | 4.19%   |
| Unknown         | 7         | 4.19%   |
| Westmere        | 6         | 3.59%   |
| TigerLake       | 5         | 2.99%   |
| Penryn          | 4         | 2.4%    |
| CometLake       | 4         | 2.4%    |
| Goldmont plus   | 3         | 1.8%    |
| Bobcat          | 3         | 1.8%    |
| Zen+            | 2         | 1.2%    |
| Zen 3           | 2         | 1.2%    |
| Zen             | 2         | 1.2%    |
| Silvermont      | 2         | 1.2%    |
| P6              | 2         | 1.2%    |
| Steamroller     | 1         | 0.6%    |
| Piledriver      | 1         | 0.6%    |
| K8 Hammer       | 1         | 0.6%    |
| K8 & K10 hybrid | 1         | 0.6%    |
| K10             | 1         | 0.6%    |
| Icelake         | 1         | 0.6%    |
| Goldmont        | 1         | 0.6%    |
| Excavator       | 1         | 0.6%    |
| Bonnell         | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 126       | 55.26%  |
| Nvidia           | 63        | 27.63%  |
| AMD              | 38        | 16.67%  |
| VIA Technologies | 1         | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 14        | 5.93%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 5.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 12        | 5.08%   |
| Intel UHD Graphics 620                                                        | 11        | 4.66%   |
| AMD Renoir                                                                    | 10        | 4.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 3.81%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 2.54%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 2.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 2.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 2.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 5         | 2.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 5         | 2.12%   |
| Intel HD Graphics 630                                                         | 5         | 2.12%   |
| Intel HD Graphics 5500                                                        | 5         | 2.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 2.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 4         | 1.69%   |
| Intel HD Graphics 530                                                         | 4         | 1.69%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.69%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 1.27%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 1.27%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.85%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 2         | 0.85%   |
| Nvidia GP108GLM [Quadro P520]                                                 | 2         | 0.85%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 0.85%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 2         | 0.85%   |
| Nvidia GK208M [GeForce GT 730M]                                               | 2         | 0.85%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 2         | 0.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 0.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 0.85%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 0.85%   |
| Intel HD Graphics 620                                                         | 2         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 0.85%   |
| AMD VanGogh [AMD Custom GPU 0405]                                             | 2         | 0.85%   |
| AMD Rembrandt [Radeon 680M]                                                   | 2         | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 68        | 40.72%  |
| Intel + Nvidia | 53        | 31.74%  |
| 1 x AMD        | 29        | 17.37%  |
| 1 x Nvidia     | 6         | 3.59%   |
| Intel + AMD    | 5         | 2.99%   |
| AMD + Nvidia   | 3         | 1.8%    |
| 2 x Nvidia     | 1         | 0.6%    |
| 2 x AMD        | 1         | 0.6%    |
| 1 x VIA        | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 128       | 75.29%  |
| Proprietary | 40        | 23.53%  |
| Unknown     | 2         | 1.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 52.38%  |
| 1.01-2.0   | 34        | 20.24%  |
| 0.01-0.5   | 20        | 11.9%   |
| 3.01-4.0   | 11        | 6.55%   |
| 0.51-1.0   | 10        | 5.95%   |
| 5.01-6.0   | 3         | 1.79%   |
| 2.01-3.0   | 1         | 0.6%    |
| 8.01-16.0  | 1         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 34        | 16.83%  |
| Chimei Innolux          | 30        | 14.85%  |
| LG Display              | 22        | 10.89%  |
| BOE                     | 21        | 10.4%   |
| Samsung Electronics     | 19        | 9.41%   |
| Dell                    | 18        | 8.91%   |
| Chi Mei Optoelectronics | 11        | 5.45%   |
| Sharp                   | 6         | 2.97%   |
| Lenovo                  | 5         | 2.48%   |
| Hewlett-Packard         | 4         | 1.98%   |
| Goldstar                | 4         | 1.98%   |
| Apple                   | 4         | 1.98%   |
| Sony                    | 3         | 1.49%   |
| PANDA                   | 3         | 1.49%   |
| LG Philips              | 3         | 1.49%   |
| ViewSonic               | 1         | 0.5%    |
| Toshiba                 | 1         | 0.5%    |
| Seiko/Epson             | 1         | 0.5%    |
| Philips                 | 1         | 0.5%    |
| Panasonic               | 1         | 0.5%    |
| Lenovo Group Limited    | 1         | 0.5%    |
| KDB                     | 1         | 0.5%    |
| JDI                     | 1         | 0.5%    |
| InfoVision              | 1         | 0.5%    |
| CSO                     | 1         | 0.5%    |
| CPT                     | 1         | 0.5%    |
| ASUSTek Computer        | 1         | 0.5%    |
| AOC                     | 1         | 0.5%    |
| Analogix                | 1         | 0.5%    |
| Acer                    | 1         | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 4         | 1.91%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 1.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 1.44%   |
| Sony TV SNYDB01 1920x1080                                                 | 2         | 0.96%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 0.96%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.96%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 2         | 0.96%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 2         | 0.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 0.96%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 0.96%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 2         | 0.96%   |
| ViewSonic VP2030 SERIES VSC131C 1600x1200 408x306mm 20.1-inch             | 1         | 0.48%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                     | 1         | 0.48%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.48%   |
| Sharp LQ133M1JW40 SHP10CD 1920x1080 294x165mm 13.3-inch                   | 1         | 0.48%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 0.48%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 1         | 0.48%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                   | 1         | 0.48%   |
| Seiko/Epson LCD Monitor 1920x1080                                         | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch      | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM030E 1680x1050 474x296mm 22.0-inch      | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch      | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch      | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 83        | 43.46%  |
| 1366x768 (WXGA)    | 43        | 22.51%  |
| 1600x900 (HD+)     | 12        | 6.28%   |
| 1280x800 (WXGA)    | 11        | 5.76%   |
| 3840x2160 (4K)     | 10        | 5.24%   |
| 1920x1200 (WUXGA)  | 6         | 3.14%   |
| 2560x1600          | 5         | 2.62%   |
| 1680x1050 (WSXGA+) | 5         | 2.62%   |
| 2560x1440 (QHD)    | 4         | 2.09%   |
| 1280x1024 (SXGA)   | 3         | 1.57%   |
| 3440x1440          | 2         | 1.05%   |
| 1440x900 (WXGA+)   | 2         | 1.05%   |
| 800x1280           | 1         | 0.52%   |
| 3840x2400          | 1         | 0.52%   |
| 2560x1080          | 1         | 0.52%   |
| 2256x1504          | 1         | 0.52%   |
| 1600x1200          | 1         | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 79        | 38.54%  |
| 14      | 28        | 13.66%  |
| 13      | 22        | 10.73%  |
| 17      | 14        | 6.83%   |
| 24      | 12        | 5.85%   |
| 12      | 8         | 3.9%    |
| 27      | 6         | 2.93%   |
| 16      | 4         | 1.95%   |
| Unknown | 4         | 1.95%   |
| 72      | 3         | 1.46%   |
| 34      | 3         | 1.46%   |
| 23      | 3         | 1.46%   |
| 22      | 3         | 1.46%   |
| 40      | 2         | 0.98%   |
| 84      | 1         | 0.49%   |
| 65      | 1         | 0.49%   |
| 54      | 1         | 0.49%   |
| 43      | 1         | 0.49%   |
| 38      | 1         | 0.49%   |
| 31      | 1         | 0.49%   |
| 29      | 1         | 0.49%   |
| 26      | 1         | 0.49%   |
| 21      | 1         | 0.49%   |
| 20      | 1         | 0.49%   |
| 19      | 1         | 0.49%   |
| 11      | 1         | 0.49%   |
| 10      | 1         | 0.49%   |
| 3       | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 116       | 57.14%  |
| 201-300     | 24        | 11.82%  |
| 501-600     | 21        | 10.34%  |
| 351-400     | 16        | 7.88%   |
| 401-500     | 5         | 2.46%   |
| 1501-2000   | 4         | 1.97%   |
| Unknown     | 4         | 1.97%   |
| 801-900     | 3         | 1.48%   |
| 701-800     | 3         | 1.48%   |
| 601-700     | 3         | 1.48%   |
| 1001-1500   | 2         | 0.99%   |
| 901-1000    | 1         | 0.49%   |
| 1-100       | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 140       | 77.78%  |
| 16/10   | 27        | 15%     |
| 21/9    | 3         | 1.67%   |
| Unknown | 3         | 1.67%   |
| 5/4     | 2         | 1.11%   |
| 4/3     | 2         | 1.11%   |
| 3/2     | 2         | 1.11%   |
| 6/5     | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 77        | 37.75%  |
| 81-90          | 38        | 18.63%  |
| 201-250        | 15        | 7.35%   |
| 71-80          | 12        | 5.88%   |
| 121-130        | 12        | 5.88%   |
| 61-70          | 8         | 3.92%   |
| 301-350        | 7         | 3.43%   |
| More than 1000 | 6         | 2.94%   |
| 111-120        | 6         | 2.94%   |
| 351-500        | 5         | 2.45%   |
| 501-1000       | 4         | 1.96%   |
| Unknown        | 4         | 1.96%   |
| 251-300        | 3         | 1.47%   |
| 151-200        | 2         | 0.98%   |
| 51-60          | 1         | 0.49%   |
| 41-50          | 1         | 0.49%   |
| 1-40           | 1         | 0.49%   |
| 141-150        | 1         | 0.49%   |
| 131-140        | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 83        | 41.29%  |
| 101-120       | 48        | 23.88%  |
| 51-100        | 38        | 18.91%  |
| 161-240       | 16        | 7.96%   |
| More than 240 | 7         | 3.48%   |
| 1-50          | 5         | 2.49%   |
| Unknown       | 4         | 1.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 127       | 74.27%  |
| 2     | 36        | 21.05%  |
| 3     | 7         | 4.09%   |
| 0     | 1         | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 100       | 37.31%  |
| Realtek Semiconductor             | 77        | 28.73%  |
| Qualcomm Atheros                  | 36        | 13.43%  |
| Broadcom                          | 14        | 5.22%   |
| Ralink                            | 4         | 1.49%   |
| MediaTek                          | 4         | 1.49%   |
| Lenovo                            | 4         | 1.49%   |
| Ericsson Business Mobile Networks | 4         | 1.49%   |
| TP-Link                           | 3         | 1.12%   |
| Fibocom                           | 3         | 1.12%   |
| Broadcom Limited                  | 3         | 1.12%   |
| Sierra Wireless                   | 2         | 0.75%   |
| Huawei Technologies               | 2         | 0.75%   |
| Hewlett-Packard                   | 2         | 0.75%   |
| ASIX Electronics                  | 2         | 0.75%   |
| VIA Technologies                  | 1         | 0.37%   |
| Van Ooijen Technische Informatica | 1         | 0.37%   |
| OPPO Electronics                  | 1         | 0.37%   |
| Nvidia                            | 1         | 0.37%   |
| Marvell Technology Group          | 1         | 0.37%   |
| JMicron Technology                | 1         | 0.37%   |
| DisplayLink                       | 1         | 0.37%   |
| ASUSTek Computer                  | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 11.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 5.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 3.27%   |
| Intel Wireless 8265 / 8275                                        | 10        | 2.98%   |
| Intel Wireless 7260                                               | 10        | 2.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.38%   |
| Intel Wireless 7265                                               | 8         | 2.38%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.49%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.19%   |
| Intel Wireless 8260                                               | 4         | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.19%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.89%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.89%   |
| Intel Wireless 3160                                               | 3         | 0.89%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.89%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.89%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.89%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.89%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.89%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 3         | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 98        | 56%     |
| Qualcomm Atheros      | 26        | 14.86%  |
| Realtek Semiconductor | 22        | 12.57%  |
| Broadcom              | 11        | 6.29%   |
| Ralink                | 4         | 2.29%   |
| MediaTek              | 4         | 2.29%   |
| Fibocom               | 3         | 1.71%   |
| TP-Link               | 2         | 1.14%   |
| Sierra Wireless       | 2         | 1.14%   |
| Broadcom Limited      | 2         | 1.14%   |
| Hewlett-Packard       | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 6.29%   |
| Intel Wireless 8265 / 8275                                              | 10        | 5.71%   |
| Intel Wireless 7260                                                     | 10        | 5.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.57%   |
| Intel Wireless 7265                                                     | 8         | 4.57%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 4.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.29%   |
| Intel Wireless 8260                                                     | 4         | 2.29%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 2.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.71%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.71%   |
| Intel Wireless 3160                                                     | 3         | 1.71%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.71%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.71%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 1.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.14%   |
| Intel Wireless 3165                                                     | 2         | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.14%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.14%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.14%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.14%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.14%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 1         | 0.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 65        | 43.33%  |
| Intel                    | 48        | 32%     |
| Qualcomm Atheros         | 17        | 11.33%  |
| Broadcom                 | 6         | 4%      |
| Lenovo                   | 3         | 2%      |
| ASIX Electronics         | 2         | 1.33%   |
| VIA Technologies         | 1         | 0.67%   |
| TP-Link                  | 1         | 0.67%   |
| OPPO Electronics         | 1         | 0.67%   |
| Nvidia                   | 1         | 0.67%   |
| Marvell Technology Group | 1         | 0.67%   |
| JMicron Technology       | 1         | 0.67%   |
| DisplayLink              | 1         | 0.67%   |
| Broadcom Limited         | 1         | 0.67%   |
| ASUSTek Computer         | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 26.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 11.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 6%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 4%      |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.33%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 3.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 3.33%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 2.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 2%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 2%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2%      |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2%      |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.33%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 1.33%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.67%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.67%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 1         | 0.67%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.67%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.67%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.67%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.67%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.67%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.67%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 166       | 51.88%  |
| Ethernet | 143       | 44.69%  |
| Modem    | 11        | 3.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 137       | 76.97%  |
| Ethernet | 41        | 23.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 132       | 79.04%  |
| 1     | 32        | 19.16%  |
| 0     | 2         | 1.2%    |
| 3     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 147       | 86.47%  |
| Yes  | 23        | 13.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 69        | 51.88%  |
| Broadcom                        | 11        | 8.27%   |
| Qualcomm Atheros Communications | 10        | 7.52%   |
| IMC Networks                    | 10        | 7.52%   |
| Realtek Semiconductor           | 9         | 6.77%   |
| Realtek                         | 4         | 3.01%   |
| Hewlett-Packard                 | 4         | 3.01%   |
| Cambridge Silicon Radio         | 4         | 3.01%   |
| Apple                           | 4         | 3.01%   |
| Foxconn / Hon Hai               | 3         | 2.26%   |
| Toshiba                         | 1         | 0.75%   |
| Ralink                          | 1         | 0.75%   |
| Lite-On Technology              | 1         | 0.75%   |
| Dell                            | 1         | 0.75%   |
| Askey Computer                  | 1         | 0.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 36        | 27.07%  |
| Intel AX201 Bluetooth                               | 11        | 8.27%   |
| Intel AX200 Bluetooth                               | 7         | 5.26%   |
| Realtek Bluetooth Radio                             | 6         | 4.51%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 4.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 3.76%   |
| IMC Networks Bluetooth Device                       | 5         | 3.76%   |
| Realtek Bluetooth Radio                             | 4         | 3.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 3.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 2.26%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.26%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 2.26%   |
| Apple Bluetooth Host Controller                     | 3         | 2.26%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.5%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.5%    |
| Intel Bluetooth Device                              | 2         | 1.5%    |
| Intel AX210 Bluetooth                               | 2         | 1.5%    |
| IMC Networks Bluetooth Radio                        | 2         | 1.5%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.5%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.5%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.5%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.5%    |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.75%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.75%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.75%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.75%   |
| Lite-On Bluetooth Device                            | 1         | 0.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.75%   |
| IMC Networks Wireless_Device                        | 1         | 0.75%   |
| IMC Networks BCM20702A0                             | 1         | 0.75%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.75%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.75%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.75%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.75%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.75%   |
| Askey Bluetooth Device                              | 1         | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 134       | 66.34%  |
| AMD                   | 34        | 16.83%  |
| Nvidia                | 19        | 9.41%   |
| Lenovo                | 4         | 1.98%   |
| Realtek Semiconductor | 2         | 0.99%   |
| VIA Technologies      | 1         | 0.5%    |
| Texas Instruments     | 1         | 0.5%    |
| TerraTec Electronic   | 1         | 0.5%    |
| Roland                | 1         | 0.5%    |
| Micronas              | 1         | 0.5%    |
| Mark of the Unicorn   | 1         | 0.5%    |
| Logitech              | 1         | 0.5%    |
| JMTek                 | 1         | 0.5%    |
| C-Media Electronics   | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 7.54%   |
| Intel Sunrise Point-LP HD Audio                                            | 16        | 6.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 5.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 5.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 4.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 3.97%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 3.57%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 3.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 2.78%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 2.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 1.98%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.98%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 1.98%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.59%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.59%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.59%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.19%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.79%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 2         | 0.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.79%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 0.79%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.79%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.4%    |
| Texas Instruments Sabaj A4 AMP                                             | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 31.53%  |
| SK hynix            | 25        | 22.52%  |
| Micron Technology   | 18        | 16.22%  |
| Kingston            | 9         | 8.11%   |
| Crucial             | 6         | 5.41%   |
| Unknown             | 3         | 2.7%    |
| Ramaxel Technology  | 3         | 2.7%    |
| Unknown (ABCD)      | 2         | 1.8%    |
| Nanya Technology    | 2         | 1.8%    |
| ASint Technology    | 2         | 1.8%    |
| A-DATA Technology   | 2         | 1.8%    |
| Unifosa             | 1         | 0.9%    |
| Qimonda             | 1         | 0.9%    |
| G.Skill             | 1         | 0.9%    |
| Elpida              | 1         | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 3.36%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 2.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.68%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 1.68%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.68%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.68%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.68%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.68%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.68%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.68%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 1.68%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.68%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.84%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.84%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.84%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.84%   |
| Unifosa RAM GU332G0AJEPR8H2L.. 2GB SODIMM DDR2 667MT/s           | 1         | 0.84%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 0.84%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s             | 1         | 0.84%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.84%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.84%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.84%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.84%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 0.84%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.84%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.84%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.84%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 0.84%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.84%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.84%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.84%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.84%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.84%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.84%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.84%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB DIMM LPDDR5 6400MT/s         | 1         | 0.84%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 39        | 43.82%  |
| DDR3   | 36        | 40.45%  |
| DDR2   | 6         | 6.74%   |
| LPDDR4 | 4         | 4.49%   |
| SDRAM  | 1         | 1.12%   |
| LPDDR5 | 1         | 1.12%   |
| LPDDR3 | 1         | 1.12%   |
| DDR    | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 84        | 95.45%  |
| Row Of Chips | 3         | 3.41%   |
| DIMM         | 1         | 1.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 41        | 41.84%  |
| 4096  | 30        | 30.61%  |
| 16384 | 11        | 11.22%  |
| 2048  | 9         | 9.18%   |
| 1024  | 4         | 4.08%   |
| 32768 | 2         | 2.04%   |
| 512   | 1         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 25        | 24.51%  |
| 2667    | 24        | 23.53%  |
| 3200    | 14        | 13.73%  |
| 1333    | 8         | 7.84%   |
| 1334    | 7         | 6.86%   |
| 2400    | 6         | 5.88%   |
| 2133    | 3         | 2.94%   |
| 1067    | 3         | 2.94%   |
| 667     | 3         | 2.94%   |
| 4267    | 2         | 1.96%   |
| 6400    | 1         | 0.98%   |
| 4199    | 1         | 0.98%   |
| 3266    | 1         | 0.98%   |
| 975     | 1         | 0.98%   |
| 800     | 1         | 0.98%   |
| 400     | 1         | 0.98%   |
| Unknown | 1         | 0.98%   |

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
| Chicony Electronics                    | 35        | 24.31%  |
| IMC Networks                           | 15        | 10.42%  |
| Microdia                               | 14        | 9.72%   |
| Realtek Semiconductor                  | 12        | 8.33%   |
| Sunplus Innovation Technology          | 11        | 7.64%   |
| Bison Electronics                      | 10        | 6.94%   |
| Lite-On Technology                     | 7         | 4.86%   |
| Silicon Motion                         | 5         | 3.47%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.47%   |
| Acer                                   | 5         | 3.47%   |
| Suyin                                  | 4         | 2.78%   |
| Luxvisions Innotech Limited            | 4         | 2.78%   |
| Apple                                  | 3         | 2.08%   |
| Syntek                                 | 2         | 1.39%   |
| Quanta                                 | 2         | 1.39%   |
| Logitech                               | 2         | 1.39%   |
| Xiaomi                                 | 1         | 0.69%   |
| Tripath Technology                     | 1         | 0.69%   |
| Sonix Technology                       | 1         | 0.69%   |
| LG Electronics                         | 1         | 0.69%   |
| Lenovo                                 | 1         | 0.69%   |
| Importek                               | 1         | 0.69%   |
| Huddly                                 | 1         | 0.69%   |
| Alcor Micro                            | 1         | 0.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 6.21%   |
| Lite-On Integrated Camera                               | 6         | 4.14%   |
| Chicony Integrated Camera                               | 6         | 4.14%   |
| Realtek USB Camera                                      | 4         | 2.76%   |
| IMC Networks Integrated Camera                          | 4         | 2.76%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 2.07%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 2.07%   |
| Chicony Integrated HP HD Webcam                         | 3         | 2.07%   |
| Chicony FJ Camera                                       | 3         | 2.07%   |
| Bison Integrated Camera                                 | 3         | 2.07%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.38%   |
| Sunplus Asus Webcam                                     | 2         | 1.38%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.38%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.38%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.38%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.38%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.38%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.38%   |
| Chicony ThinkPad T490 Webcam                            | 2         | 1.38%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.38%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.38%   |
| Chicony HP HD Webcam                                    | 2         | 1.38%   |
| Apple FaceTime HD Camera                                | 2         | 1.38%   |
| Xiaomi Mi 9 Lite                                        | 1         | 0.69%   |
| Tripath USB Camera                                      | 1         | 0.69%   |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.69%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.69%   |
| Suyin USB Webcam                                        | 1         | 0.69%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.69%   |
| Suyin HD WebCam                                         | 1         | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.69%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.69%   |
| Sunplus Laptop Integrated Webcam FHD                    | 1         | 0.69%   |
| Sunplus HP Wide Vision HD                               | 1         | 0.69%   |
| Sunplus HP Universal Camera                             | 1         | 0.69%   |
| Sunplus HD WebCam                                       | 1         | 0.69%   |
| Sunplus Dell HD Webcam                                  | 1         | 0.69%   |
| Sunplus 1.3M HD WebCam                                  | 1         | 0.69%   |
| Sonix USB2.0 FHD UVC WebCam                             | 1         | 0.69%   |
| Silicon Motion WebCam SC-13HDL11431N                    | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 18        | 40.91%  |
| Synaptics                          | 10        | 22.73%  |
| Upek                               | 4         | 9.09%   |
| STMicroelectronics                 | 4         | 9.09%   |
| Shenzhen Goodix Technology         | 4         | 9.09%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.27%   |
| LighTuning Technology              | 1         | 2.27%   |
| Elan Microelectronics              | 1         | 2.27%   |
| AuthenTec                          | 1         | 2.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 11.36%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 11.36%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 5         | 11.36%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 4         | 9.09%   |
| STMicroelectronics Fingerprint Reader                           | 4         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 6.82%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 4.55%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 4.55%   |
| Shenzhen Goodix FingerPrint                                     | 2         | 4.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 2.27%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 2.27%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.27%   |
| Synaptics WBDI                                                  | 1         | 2.27%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 2.27%   |
| Elan ELAN:Fingerprint                                           | 1         | 2.27%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 2.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 21        | 56.76%  |
| OmniKey               | 6         | 16.22%  |
| Lenovo                | 3         | 8.11%   |
| Gemalto (was Gemplus) | 3         | 8.11%   |
| Broadcom              | 3         | 8.11%   |
| O2 Micro              | 1         | 2.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 21        | 56.76%  |
| OmniKey CardMan 4321                                   | 3         | 8.11%   |
| OmniKey CardMan 1021                                   | 3         | 8.11%   |
| Lenovo Integrated Smart Card Reader                    | 3         | 8.11%   |
| Broadcom 58200                                         | 3         | 8.11%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 2         | 5.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 2.7%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 2.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 94        | 55.62%  |
| 1     | 53        | 31.36%  |
| 2     | 19        | 11.24%  |
| 3     | 3         | 1.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 44        | 44.9%   |
| Graphics card            | 21        | 21.43%  |
| Chipcard                 | 19        | 19.39%  |
| Net/wireless             | 4         | 4.08%   |
| Camera                   | 3         | 3.06%   |
| Card reader              | 2         | 2.04%   |
| Net/ethernet             | 1         | 1.02%   |
| Multimedia controller    | 1         | 1.02%   |
| Modem                    | 1         | 1.02%   |
| Communication controller | 1         | 1.02%   |
| Bluetooth                | 1         | 1.02%   |

