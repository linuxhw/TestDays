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

Total: 223

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 19        | 11.24%  |
| Ubuntu 18.04       | 14        | 8.28%   |
| Ubuntu 22.04       | 11        | 6.51%   |
| Arch               | 7         | 4.14%   |
| Ubuntu 19.04       | 6         | 3.55%   |
| ArcoLinux Rolling  | 6         | 3.55%   |
| Linux Mint 20.1    | 5         | 2.96%   |
| Kubuntu 22.04      | 4         | 2.37%   |
| Fedora 34          | 4         | 2.37%   |
| ROSA R9            | 3         | 1.78%   |
| ROSA R8.1          | 3         | 1.78%   |
| ROSA R11           | 3         | 1.78%   |
| Pop!_OS 20.04      | 3         | 1.78%   |
| OpenMandriva 4.2   | 3         | 1.78%   |
| Kubuntu 20.04      | 3         | 1.78%   |
| Fedora 36          | 3         | 1.78%   |
| Zorin 16           | 2         | 1.18%   |
| Xubuntu 20.04      | 2         | 1.18%   |
| Ubuntu MATE 22.04  | 2         | 1.18%   |
| Ubuntu 20.10       | 2         | 1.18%   |
| Ubuntu 19.10       | 2         | 1.18%   |
| ROSA 12.2          | 2         | 1.18%   |
| Reborn OS          | 2         | 1.18%   |
| Manjaro 20.1       | 2         | 1.18%   |
| Manjaro            | 2         | 1.18%   |
| Linux Mint 20.3    | 2         | 1.18%   |
| Linux Mint 20.2    | 2         | 1.18%   |
| Linux Mint 19.3    | 2         | 1.18%   |
| Linux Mint 18.3    | 2         | 1.18%   |
| KDE neon 20.04     | 2         | 1.18%   |
| Elementary 6.1     | 2         | 1.18%   |
| Debian 11          | 2         | 1.18%   |
| Arch Rolling       | 2         | 1.18%   |
| Zorin 15           | 1         | 0.59%   |
| Xubuntu 22.10      | 1         | 0.59%   |
| Xubuntu 18.04      | 1         | 0.59%   |
| Ubuntu Unity 16.04 | 1         | 0.59%   |
| Ubuntu MATE 20.04  | 1         | 0.59%   |
| Ubuntu 21.04       | 1         | 0.59%   |
| SteamOS 3.3.2      | 1         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 55        | 33.13%  |
| ROSA         | 14        | 8.43%   |
| Linux Mint   | 14        | 8.43%   |
| Fedora       | 10        | 6.02%   |
| Arch         | 9         | 5.42%   |
| Manjaro      | 8         | 4.82%   |
| Kubuntu      | 6         | 3.61%   |
| ArcoLinux    | 6         | 3.61%   |
| Pop!_OS      | 5         | 3.01%   |
| OpenMandriva | 5         | 3.01%   |
| Xubuntu      | 4         | 2.41%   |
| Endless      | 4         | 2.41%   |
| Zorin        | 3         | 1.81%   |
| Ubuntu MATE  | 3         | 1.81%   |
| KDE neon     | 3         | 1.81%   |
| Elementary   | 3         | 1.81%   |
| Debian       | 3         | 1.81%   |
| SteamOS      | 2         | 1.2%    |
| Reborn OS    | 2         | 1.2%    |
| Clear Linux  | 2         | 1.2%    |
| Ubuntu Unity | 1         | 0.6%    |
| Lubuntu      | 1         | 0.6%    |
| LMDE         | 1         | 0.6%    |
| Kali         | 1         | 0.6%    |
| EndeavourOS  | 1         | 0.6%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 6         | 3.28%   |
| 5.15.0-52-generic                  | 4         | 2.19%   |
| 5.4.0-47-generic                   | 3         | 1.64%   |
| 5.4.0-28-generic                   | 3         | 1.64%   |
| 5.15.0-53-generic                  | 3         | 1.64%   |
| 5.10.14-desktop-1omv4002           | 3         | 1.64%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 1.64%   |
| 5.8.0-53-generic                   | 2         | 1.09%   |
| 5.4.0-88-generic                   | 2         | 1.09%   |
| 5.4.0-65-generic                   | 2         | 1.09%   |
| 5.15.2-arch1-1                     | 2         | 1.09%   |
| 5.15.0-56-generic                  | 2         | 1.09%   |
| 5.13.0-39-generic                  | 2         | 1.09%   |
| 5.11.0-27-generic                  | 2         | 1.09%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 1.09%   |
| 5.0.0-23-generic                   | 2         | 1.09%   |
| 4.18.0-15-generic                  | 2         | 1.09%   |
| 4.15.0-45-generic                  | 2         | 1.09%   |
| 6.2.7-arch1-1                      | 1         | 0.55%   |
| 6.1.5-arch2-1                      | 1         | 0.55%   |
| 6.1.1-desktop-1omv2290             | 1         | 0.55%   |
| 6.1.0-kali7-amd64                  | 1         | 0.55%   |
| 6.0.9-arch1-1                      | 1         | 0.55%   |
| 6.0.9-300.fc37.x86_64              | 1         | 0.55%   |
| 6.0.8-1-MANJARO                    | 1         | 0.55%   |
| 6.0.5-200.fc36.x86_64              | 1         | 0.55%   |
| 6.0.2-2-MANJARO                    | 1         | 0.55%   |
| 5.9.16-1-MANJARO                   | 1         | 0.55%   |
| 5.9.13-200.fc33.x86_64             | 1         | 0.55%   |
| 5.9.10-zen1-1-zen                  | 1         | 0.55%   |
| 5.9.0-050900rc5-lowlatency         | 1         | 0.55%   |
| 5.8.6-1-MANJARO                    | 1         | 0.55%   |
| 5.8.0-7630-generic                 | 1         | 0.55%   |
| 5.8.0-63-generic                   | 1         | 0.55%   |
| 5.8.0-59-generic                   | 1         | 0.55%   |
| 5.8.0-54-generic                   | 1         | 0.55%   |
| 5.8.0-50-generic                   | 1         | 0.55%   |
| 5.8.0-45-generic                   | 1         | 0.55%   |
| 5.8.0-44-generic                   | 1         | 0.55%   |
| 5.8.0-38-generic                   | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 32        | 18.08%  |
| 5.15.0  | 17        | 9.6%    |
| 4.15.0  | 13        | 7.34%   |
| 5.8.0   | 9         | 5.08%   |
| 5.11.0  | 8         | 4.52%   |
| 5.13.0  | 7         | 3.95%   |
| 5.0.0   | 7         | 3.95%   |
| 4.18.0  | 5         | 2.82%   |
| 4.9.20  | 4         | 2.26%   |
| 5.3.0   | 3         | 1.69%   |
| 5.10.14 | 3         | 1.69%   |
| 6.0.9   | 2         | 1.13%   |
| 5.19.0  | 2         | 1.13%   |
| 5.17.1  | 2         | 1.13%   |
| 5.15.2  | 2         | 1.13%   |
| 5.13.13 | 2         | 1.13%   |
| 5.13.12 | 2         | 1.13%   |
| 5.11.12 | 2         | 1.13%   |
| 5.10.74 | 2         | 1.13%   |
| 6.2.7   | 1         | 0.56%   |
| 6.1.5   | 1         | 0.56%   |
| 6.1.1   | 1         | 0.56%   |
| 6.1.0   | 1         | 0.56%   |
| 6.0.8   | 1         | 0.56%   |
| 6.0.5   | 1         | 0.56%   |
| 6.0.2   | 1         | 0.56%   |
| 5.9.16  | 1         | 0.56%   |
| 5.9.13  | 1         | 0.56%   |
| 5.9.10  | 1         | 0.56%   |
| 5.9.0   | 1         | 0.56%   |
| 5.8.6   | 1         | 0.56%   |
| 5.6.13  | 1         | 0.56%   |
| 5.5.6   | 1         | 0.56%   |
| 5.4.64  | 1         | 0.56%   |
| 5.19.8  | 1         | 0.56%   |
| 5.17.6  | 1         | 0.56%   |
| 5.17.4  | 1         | 0.56%   |
| 5.16.9  | 1         | 0.56%   |
| 5.16.7  | 1         | 0.56%   |
| 5.16.5  | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 33        | 18.64%  |
| 5.15    | 22        | 12.43%  |
| 5.13    | 16        | 9.04%   |
| 4.15    | 13        | 7.34%   |
| 5.11    | 11        | 6.21%   |
| 5.10    | 11        | 6.21%   |
| 5.8     | 10        | 5.65%   |
| 5.0     | 8         | 4.52%   |
| 4.9     | 7         | 3.95%   |
| 6.0     | 5         | 2.82%   |
| 4.18    | 5         | 2.82%   |
| 5.9     | 4         | 2.26%   |
| 5.17    | 4         | 2.26%   |
| 5.16    | 4         | 2.26%   |
| 6.1     | 3         | 1.69%   |
| 5.3     | 3         | 1.69%   |
| 5.19    | 3         | 1.69%   |
| 5.14    | 3         | 1.69%   |
| 5.12    | 3         | 1.69%   |
| 4.19    | 2         | 1.13%   |
| 6.2     | 1         | 0.56%   |
| 5.6     | 1         | 0.56%   |
| 5.5     | 1         | 0.56%   |
| 4.4     | 1         | 0.56%   |
| 4.10    | 1         | 0.56%   |
| 4.1     | 1         | 0.56%   |
| 3.16    | 1         | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 158       | 96.93%  |
| i686   | 5         | 3.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 59        | 35.54%  |
| Unknown    | 25        | 15.06%  |
| KDE5       | 23        | 13.86%  |
| XFCE       | 14        | 8.43%   |
| X-Cinnamon | 10        | 6.02%   |
| KDE4       | 8         | 4.82%   |
| MATE       | 7         | 4.22%   |
| Pantheon   | 3         | 1.81%   |
| KDE        | 3         | 1.81%   |
| i3         | 3         | 1.81%   |
| Unity      | 2         | 1.2%    |
| LXQt       | 2         | 1.2%    |
| LXDE       | 2         | 1.2%    |
| awesome    | 2         | 1.2%    |
| openbox    | 1         | 0.6%    |
| Cinnamon   | 1         | 0.6%    |
| Budgie     | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 128       | 78.53%  |
| Wayland | 24        | 14.72%  |
| Unknown | 10        | 6.13%   |
| Tty     | 1         | 0.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 81        | 48.8%   |
| SDDM    | 25        | 15.06%  |
| GDM     | 19        | 11.45%  |
| GDM3    | 14        | 8.43%   |
| LightDM | 10        | 6.02%   |
| TDM     | 9         | 5.42%   |
| KDM     | 8         | 4.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 80        | 48.48%  |
| Unknown         | 32        | 19.39%  |
| et_EE           | 26        | 15.76%  |
| ru_RU           | 13        | 7.88%   |
| en_GB           | 6         | 3.64%   |
| de_DE           | 2         | 1.21%   |
| uk_UA           | 1         | 0.61%   |
| ru_UA           | 1         | 0.61%   |
| fr_FR           | 1         | 0.61%   |
| en_US.iso885915 | 1         | 0.61%   |
| en_DK           | 1         | 0.61%   |
| C               | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 87        | 52.1%   |
| EFI  | 80        | 47.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 124       | 76.07%  |
| Btrfs   | 17        | 10.43%  |
| Unknown | 12        | 7.36%   |
| Overlay | 6         | 3.68%   |
| Xfs     | 2         | 1.23%   |
| Zfs     | 1         | 0.61%   |
| Ext3    | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 88        | 53.66%  |
| GPT     | 57        | 34.76%  |
| MBR     | 19        | 11.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 150       | 90.91%  |
| Yes       | 15        | 9.09%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 120       | 72.29%  |
| Yes       | 46        | 27.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 48        | 29.45%  |
| Hewlett-Packard     | 30        | 18.4%   |
| Dell                | 21        | 12.88%  |
| ASUSTek Computer    | 19        | 11.66%  |
| Samsung Electronics | 7         | 4.29%   |
| Acer                | 6         | 3.68%   |
| MSI                 | 5         | 3.07%   |
| Apple               | 4         | 2.45%   |
| Fujitsu             | 3         | 1.84%   |
| Valve               | 2         | 1.23%   |
| Timi                | 2         | 1.23%   |
| Quanta              | 2         | 1.23%   |
| Alienware           | 2         | 1.23%   |
| TUXEDO              | 1         | 0.61%   |
| Toshiba             | 1         | 0.61%   |
| Packard Bell        | 1         | 0.61%   |
| Notebook            | 1         | 0.61%   |
| mPTech              | 1         | 0.61%   |
| HUAWEI              | 1         | 0.61%   |
| GPD                 | 1         | 0.61%   |
| Gigabyte Technology | 1         | 0.61%   |
| Getac               | 1         | 0.61%   |
| Fujitsu Siemens     | 1         | 0.61%   |
| Framework           | 1         | 0.61%   |
| Chuwi               | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 2         | 1.23%   |
| Quanta TWH                                            | 2         | 1.23%   |
| Lenovo Y50-70 20378                                   | 2         | 1.23%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 1.23%   |
| HP Pavilion dv7                                       | 2         | 1.23%   |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 1.23%   |
| HP EliteBook 8470p                                    | 2         | 1.23%   |
| HP EliteBook 8460p                                    | 2         | 1.23%   |
| HP EliteBook 840 G2                                   | 2         | 1.23%   |
| Dell Inspiron N5110                                   | 2         | 1.23%   |
| Alienware 17                                          | 2         | 1.23%   |
| TUXEDO Book BA1510                                    | 1         | 0.61%   |
| Toshiba Satellite L855                                | 1         | 0.61%   |
| Timi RedmiBook 16                                     | 1         | 0.61%   |
| Timi RedmiBook 14 II                                  | 1         | 0.61%   |
| Samsung R410                                          | 1         | 0.61%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.61%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.61%   |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.61%   |
| Samsung 535U3C                                        | 1         | 0.61%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.61%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.61%   |
| Packard Bell EasyNote TK87                            | 1         | 0.61%   |
| Notebook W35xSS_370SS                                 | 1         | 0.61%   |
| MSI GT70 2OC/2OD                                      | 1         | 0.61%   |
| MSI GS75 Stealth 8SE                                  | 1         | 0.61%   |
| MSI GP62M 7RDX                                        | 1         | 0.61%   |
| MSI GL72 6QD                                          | 1         | 0.61%   |
| MSI GF63 Thin 10SCXR                                  | 1         | 0.61%   |
| mPTech ARC 11.6 128GB HD                              | 1         | 0.61%   |
| Lenovo Y720-15IKB 80VR                                | 1         | 0.61%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.61%   |
| Lenovo V110-15ISK 80TL                                | 1         | 0.61%   |
| Lenovo ThinkPad X260 20F5S84400                       | 1         | 0.61%   |
| Lenovo ThinkPad X240 20AMA0W706                       | 1         | 0.61%   |
| Lenovo ThinkPad X220 4291R30                          | 1         | 0.61%   |
| Lenovo ThinkPad X220 429136G                          | 1         | 0.61%   |
| Lenovo ThinkPad X201 3680CG7                          | 1         | 0.61%   |
| Lenovo ThinkPad X13 Gen 1 20UF0020MX                  | 1         | 0.61%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW005PMX            | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 36        | 22.09%  |
| HP EliteBook          | 12        | 7.36%   |
| HP Pavilion           | 7         | 4.29%   |
| Dell Inspiron         | 6         | 3.68%   |
| Dell Latitude         | 5         | 3.07%   |
| Dell Precision        | 4         | 2.45%   |
| ASUS VivoBook         | 4         | 2.45%   |
| Acer Aspire           | 4         | 2.45%   |
| Lenovo IdeaPad        | 3         | 1.84%   |
| Fujitsu LIFEBOOK      | 3         | 1.84%   |
| Dell XPS              | 3         | 1.84%   |
| Valve Jupiter         | 2         | 1.23%   |
| Timi RedmiBook        | 2         | 1.23%   |
| Samsung 900X3C        | 2         | 1.23%   |
| Quanta TWH            | 2         | 1.23%   |
| Lenovo Y50-70         | 2         | 1.23%   |
| Lenovo Legion         | 2         | 1.23%   |
| HP Presario           | 2         | 1.23%   |
| HP OMEN               | 2         | 1.23%   |
| HP ENVY               | 2         | 1.23%   |
| HP Compaq             | 2         | 1.23%   |
| ASUS ZenBook          | 2         | 1.23%   |
| Alienware 17          | 2         | 1.23%   |
| TUXEDO Book           | 1         | 0.61%   |
| Toshiba Satellite     | 1         | 0.61%   |
| Samsung R410          | 1         | 0.61%   |
| Samsung 770Z5E        | 1         | 0.61%   |
| Samsung 535U3C        | 1         | 0.61%   |
| Samsung 300E5EV       | 1         | 0.61%   |
| Samsung 275E4E        | 1         | 0.61%   |
| Packard Bell EasyNote | 1         | 0.61%   |
| Notebook W35xSS       | 1         | 0.61%   |
| MSI GT70              | 1         | 0.61%   |
| MSI GS75              | 1         | 0.61%   |
| MSI GP62M             | 1         | 0.61%   |
| MSI GL72              | 1         | 0.61%   |
| MSI GF63              | 1         | 0.61%   |
| mPTech ARC            | 1         | 0.61%   |
| Lenovo Y720-15IKB     | 1         | 0.61%   |
| Lenovo Y520-15IKBN    | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 19        | 11.66%  |
| 2013 | 18        | 11.04%  |
| 2011 | 17        | 10.43%  |
| 2018 | 14        | 8.59%   |
| 2019 | 13        | 7.98%   |
| 2014 | 12        | 7.36%   |
| 2012 | 11        | 6.75%   |
| 2015 | 10        | 6.13%   |
| 2017 | 9         | 5.52%   |
| 2008 | 7         | 4.29%   |
| 2007 | 7         | 4.29%   |
| 2022 | 6         | 3.68%   |
| 2021 | 6         | 3.68%   |
| 2010 | 6         | 3.68%   |
| 2016 | 5         | 3.07%   |
| 2009 | 2         | 1.23%   |
| 2006 | 1         | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 163       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 148       | 90.24%  |
| Enabled  | 16        | 9.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 163       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 41        | 24.85%  |
| 4.01-8.0    | 38        | 23.03%  |
| 3.01-4.0    | 30        | 18.18%  |
| 16.01-24.0  | 28        | 16.97%  |
| 32.01-64.0  | 8         | 4.85%   |
| 24.01-32.0  | 7         | 4.24%   |
| 2.01-3.0    | 7         | 4.24%   |
| 1.01-2.0    | 5         | 3.03%   |
| 64.01-256.0 | 1         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 62        | 35.63%  |
| 2.01-3.0   | 42        | 24.14%  |
| 4.01-8.0   | 32        | 18.39%  |
| 3.01-4.0   | 18        | 10.34%  |
| 8.01-16.0  | 10        | 5.75%   |
| 0.51-1.0   | 9         | 5.17%   |
| 24.01-32.0 | 1         | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 126       | 75.45%  |
| 2      | 33        | 19.76%  |
| 3      | 6         | 3.59%   |
| 5      | 1         | 0.6%    |
| 4      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 107       | 64.46%  |
| Yes       | 59        | 35.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 84.76%  |
| No        | 25        | 15.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 129       | 78.66%  |
| No        | 35        | 21.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Estonia | 163       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Tallinn           | 108       | 65.45%  |
| Tartu             | 15        | 9.09%   |
| Pärnu            | 7         | 4.24%   |
| Rapla             | 4         | 2.42%   |
| Narva             | 4         | 2.42%   |
| Rakvere           | 3         | 1.82%   |
| Vinni             | 2         | 1.21%   |
| Saku              | 2         | 1.21%   |
| Otepaeae          | 2         | 1.21%   |
| Maardu            | 2         | 1.21%   |
| Keila             | 2         | 1.21%   |
| Viljandi          | 1         | 0.61%   |
| Vatla             | 1         | 0.61%   |
| Tabasalu          | 1         | 0.61%   |
| Sillamäe         | 1         | 0.61%   |
| Sauga             | 1         | 0.61%   |
| Rae Parish        | 1         | 0.61%   |
| Põlva            | 1         | 0.61%   |
| Pohja-Sakala vald | 1         | 0.61%   |
| Laagri            | 1         | 0.61%   |
| Kärdla           | 1         | 0.61%   |
| Kaeina            | 1         | 0.61%   |
| Jõhvi            | 1         | 0.61%   |
| Jõgeva           | 1         | 0.61%   |
| AEaesmaee         | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 42        | 49     | 20.59%  |
| Seagate                     | 28        | 31     | 13.73%  |
| Toshiba                     | 17        | 17     | 8.33%   |
| Kingston                    | 14        | 15     | 6.86%   |
| WDC                         | 13        | 15     | 6.37%   |
| SK hynix                    | 13        | 17     | 6.37%   |
| Intel                       | 8         | 9      | 3.92%   |
| SanDisk                     | 7         | 9      | 3.43%   |
| HGST                        | 7         | 8      | 3.43%   |
| Unknown                     | 6         | 6      | 2.94%   |
| Hitachi                     | 5         | 5      | 2.45%   |
| Patriot                     | 3         | 4      | 1.47%   |
| Micron Technology           | 3         | 3      | 1.47%   |
| Crucial                     | 3         | 3      | 1.47%   |
| A-DATA Technology           | 3         | 3      | 1.47%   |
| Transcend                   | 2         | 5      | 0.98%   |
| Phison Electronics          | 2         | 2      | 0.98%   |
| LITEONIT                    | 2         | 2      | 0.98%   |
| Lenovo                      | 2         | 2      | 0.98%   |
| KingSpec                    | 2         | 3      | 0.98%   |
| Gigabyte Technology         | 2         | 3      | 0.98%   |
| Fujitsu                     | 2         | 2      | 0.98%   |
| China                       | 2         | 2      | 0.98%   |
| Apacer                      | 2         | 2      | 0.98%   |
| SPCC                        | 1         | 1      | 0.49%   |
| PNY                         | 1         | 1      | 0.49%   |
| Phison                      | 1         | 1      | 0.49%   |
| Netac                       | 1         | 1      | 0.49%   |
| Lexar                       | 1         | 1      | 0.49%   |
| KIOXIA                      | 1         | 2      | 0.49%   |
| Kingston Technology Company | 1         | 1      | 0.49%   |
| Intenso                     | 1         | 1      | 0.49%   |
| HUAWEI                      | 1         | 1      | 0.49%   |
| External                    | 1         | 1      | 0.49%   |
| ASMT109x                    | 1         | 2      | 0.49%   |
| Apple                       | 1         | 1      | 0.49%   |
| ADATA Technology            | 1         | 1      | 0.49%   |
| Unknown                     | 1         | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST500LM021-1KJ152 500GB                    | 3         | 1.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 3         | 1.43%   |
| HGST HTS721010A9E630 1TB                           | 3         | 1.43%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 2         | 0.95%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB               | 2         | 0.95%   |
| Unknown MMC Card  16GB                             | 2         | 0.95%   |
| Toshiba NVMe SSD Drive 512GB                       | 2         | 0.95%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 0.95%   |
| SK hynix NVMe SSD Drive 512GB                      | 2         | 0.95%   |
| SK hynix NVMe SSD Drive 256GB                      | 2         | 0.95%   |
| Seagate ST500LT012-1DG142 500GB                    | 2         | 0.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 0.95%   |
| Seagate BUP Portable 5TB                           | 2         | 0.95%   |
| SanDisk SD8SBAT256G1122 256GB SSD                  | 2         | 0.95%   |
| Samsung SSD 970 EVO Plus 1TB                       | 2         | 0.95%   |
| Samsung SSD 850 EVO M.2 500GB                      | 2         | 0.95%   |
| Samsung SSD 850 EVO 500GB                          | 2         | 0.95%   |
| Samsung NVMe SSD Drive 512GB                       | 2         | 0.95%   |
| Samsung NVMe SSD Drive 1TB                         | 2         | 0.95%   |
| Samsung NVMe SSD Drive 1024GB                      | 2         | 0.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2         | 0.95%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 0.95%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD               | 2         | 0.95%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                | 2         | 0.95%   |
| Kingston SV300S37A120G 120GB SSD                   | 2         | 0.95%   |
| Kingston SA400S37960G 960GB SSD                    | 2         | 0.95%   |
| Intel SSDPEKKF256G8L 256GB                         | 2         | 0.95%   |
| HGST HTS541010A9E680 1TB                           | 2         | 0.95%   |
| WDC WDS500G2B0B 500GB SSD                          | 1         | 0.48%   |
| WDC WDS500G1X0E-00AFY0 500GB                       | 1         | 0.48%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                   | 1         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB                       | 1         | 0.48%   |
| WDC WD5000LPCX-24VHAT0 500GB                       | 1         | 0.48%   |
| WDC WD2500BEVT-80A23T0 250GB                       | 1         | 0.48%   |
| WDC WD1200BEVS-08RST2 120GB                        | 1         | 0.48%   |
| WDC PC SN730 NVMe 512GB                            | 1         | 0.48%   |
| Unknown MMC128  128GB                              | 1         | 0.48%   |
| Unknown MMC Card  7GB                              | 1         | 0.48%   |
| Unknown MMC Card  512GB                            | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 27        | 30     | 50.94%  |
| Toshiba | 8         | 8      | 15.09%  |
| HGST    | 7         | 8      | 13.21%  |
| Hitachi | 5         | 5      | 9.43%   |
| WDC     | 4         | 5      | 7.55%   |
| Fujitsu | 2         | 2      | 3.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 26     | 28.75%  |
| Kingston            | 12        | 13     | 15%     |
| SanDisk             | 5         | 7      | 6.25%   |
| SK hynix            | 4         | 4      | 5%      |
| WDC                 | 3         | 4      | 3.75%   |
| Patriot             | 3         | 4      | 3.75%   |
| Micron Technology   | 3         | 3      | 3.75%   |
| Crucial             | 3         | 3      | 3.75%   |
| A-DATA Technology   | 3         | 3      | 3.75%   |
| Transcend           | 2         | 5      | 2.5%    |
| Toshiba             | 2         | 2      | 2.5%    |
| LITEONIT            | 2         | 2      | 2.5%    |
| KingSpec            | 2         | 3      | 2.5%    |
| Intel               | 2         | 3      | 2.5%    |
| China               | 2         | 2      | 2.5%    |
| Apacer              | 2         | 2      | 2.5%    |
| SPCC                | 1         | 1      | 1.25%   |
| Netac               | 1         | 1      | 1.25%   |
| Lexar               | 1         | 1      | 1.25%   |
| Intenso             | 1         | 1      | 1.25%   |
| Gigabyte Technology | 1         | 2      | 1.25%   |
| External            | 1         | 1      | 1.25%   |
| Apple               | 1         | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 69        | 94     | 37.5%   |
| NVMe    | 54        | 70     | 29.35%  |
| HDD     | 51        | 58     | 27.72%  |
| MMC     | 7         | 7      | 3.8%    |
| Unknown | 3         | 4      | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 110       | 147    | 61.11%  |
| NVMe | 54        | 70     | 30%     |
| SAS  | 9         | 9      | 5%      |
| MMC  | 7         | 7      | 3.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 88        | 109    | 70.4%   |
| 0.51-1.0   | 33        | 39     | 26.4%   |
| 1.01-2.0   | 2         | 2      | 1.6%    |
| 4.01-10.0  | 2         | 2      | 1.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 59        | 34.91%  |
| 251-500        | 36        | 21.3%   |
| 501-1000       | 23        | 13.61%  |
| 1-20           | 15        | 8.88%   |
| 51-100         | 12        | 7.1%    |
| 1001-2000      | 8         | 4.73%   |
| More than 3000 | 5         | 2.96%   |
| 21-50          | 5         | 2.96%   |
| Unknown        | 5         | 2.96%   |
| 2001-3000      | 1         | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 73        | 41.95%  |
| 21-50          | 27        | 15.52%  |
| 101-250        | 23        | 13.22%  |
| 51-100         | 22        | 12.64%  |
| 251-500        | 13        | 7.47%   |
| 501-1000       | 7         | 4.02%   |
| Unknown        | 5         | 2.87%   |
| More than 3000 | 2         | 1.15%   |
| 2001-3000      | 1         | 0.57%   |
| 1001-2000      | 1         | 0.57%   |

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
| Seagate ST1000LM035-1RK172 970GB                    | 1         | 1      | 6.67%   |
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
| Detected | 98        | 147    | 57.65%  |
| Works    | 58        | 71     | 34.12%  |
| Malfunc  | 14        | 15     | 8.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 119       | 61.34%  |
| Samsung Electronics          | 20        | 10.31%  |
| AMD                          | 18        | 9.28%   |
| SK hynix                     | 9         | 4.64%   |
| SanDisk                      | 7         | 3.61%   |
| Toshiba America Info Systems | 6         | 3.09%   |
| Phison Electronics           | 4         | 2.06%   |
| Kingston Technology Company  | 3         | 1.55%   |
| Lenovo                       | 2         | 1.03%   |
| KIOXIA                       | 2         | 1.03%   |
| VIA Technologies             | 1         | 0.52%   |
| Nvidia                       | 1         | 0.52%   |
| Marvell Technology Group     | 1         | 0.52%   |
| ADATA Technology             | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 6.67%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 6.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 5.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 4.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 3.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 3.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 2.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 2.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.43%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 3         | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.43%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.95%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 0.95%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.95%   |
| SanDisk NVMe Controller                                                        | 2         | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.95%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.95%   |
| Lenovo Non-Volatile memory controller                                          | 2         | 0.95%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 0.95%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.95%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 0.95%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.95%   |
| Intel SSD 660P Series                                                          | 2         | 0.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.95%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.95%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 2         | 0.95%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 0.95%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.48%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 125       | 62.19%  |
| NVMe | 55        | 27.36%  |
| IDE  | 14        | 6.97%   |
| RAID | 7         | 3.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 133       | 81.6%   |
| AMD    | 30        | 18.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 3.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.84%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.84%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.84%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 3         | 1.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.84%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.23%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.23%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 1.23%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 1.23%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.23%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.23%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.23%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 1.23%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.23%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.23%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 1.23%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.23%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.23%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.23%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.23%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 2         | 1.23%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.23%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.23%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.23%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.23%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.23%   |
| AMD Custom APU 0405                           | 2         | 1.23%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.61%   |
| Intel Pentium M processor 2.13GHz             | 1         | 0.61%   |
| Intel Pentium M processor 1.50GHz             | 1         | 0.61%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.61%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.61%   |
| Intel Pentium CPU 2127U @ 1.90GHz             | 1         | 0.61%   |
| Intel Pentium 3805U @ 1.90GHz                 | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 47        | 28.83%  |
| Intel Core i5                  | 43        | 26.38%  |
| AMD Ryzen 5                    | 9         | 5.52%   |
| Other                          | 8         | 4.91%   |
| Intel Core i3                  | 8         | 4.91%   |
| Intel Core 2 Duo               | 8         | 4.91%   |
| Intel Celeron                  | 8         | 4.91%   |
| AMD Ryzen 7                    | 6         | 3.68%   |
| Intel Pentium                  | 3         | 1.84%   |
| Intel Pentium M                | 2         | 1.23%   |
| Intel Celeron Dual-Core        | 2         | 1.23%   |
| AMD Ryzen 7 PRO                | 2         | 1.23%   |
| Intel Pentium Silver           | 1         | 0.61%   |
| Intel Pentium Dual             | 1         | 0.61%   |
| Intel Core i9                  | 1         | 0.61%   |
| Intel Core 2                   | 1         | 0.61%   |
| Intel Celeron M                | 1         | 0.61%   |
| Intel Atom                     | 1         | 0.61%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.61%   |
| AMD Ryzen 5 PRO                | 1         | 0.61%   |
| AMD Ryzen 3 PRO                | 1         | 0.61%   |
| AMD E2                         | 1         | 0.61%   |
| AMD E                          | 1         | 0.61%   |
| AMD C-60                       | 1         | 0.61%   |
| AMD Athlon II Dual-Core        | 1         | 0.61%   |
| AMD Athlon 64 X2               | 1         | 0.61%   |
| AMD A8                         | 1         | 0.61%   |
| AMD A6                         | 1         | 0.61%   |
| AMD A4                         | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 79        | 48.47%  |
| 4       | 53        | 32.52%  |
| 6       | 17        | 10.43%  |
| 8       | 7         | 4.29%   |
| 1       | 5         | 3.07%   |
| Unknown | 2         | 1.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 163       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 121       | 73.78%  |
| 1       | 41        | 25%     |
| Unknown | 2         | 1.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 160       | 98.16%  |
| 32-bit         | 2         | 1.23%   |
| Unknown        | 1         | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 21.56%  |
| 0x306a9    | 13        | 7.78%   |
| 0x206a7    | 12        | 7.19%   |
| 0x306c3    | 10        | 5.99%   |
| 0x806ea    | 7         | 4.19%   |
| 0x40651    | 7         | 4.19%   |
| 0x306d4    | 6         | 3.59%   |
| 0x08600106 | 6         | 3.59%   |
| 0x906e9    | 5         | 2.99%   |
| 0xa0652    | 4         | 2.4%    |
| 0x806ec    | 4         | 2.4%    |
| 0x806c1    | 4         | 2.4%    |
| 0x6fb      | 4         | 2.4%    |
| 0x20655    | 4         | 2.4%    |
| 0x1067a    | 4         | 2.4%    |
| 0x906ea    | 3         | 1.8%    |
| 0x6fd      | 3         | 1.8%    |
| 0x506e3    | 3         | 1.8%    |
| 0x406e3    | 3         | 1.8%    |
| 0x05000119 | 3         | 1.8%    |
| 0x806e9    | 2         | 1.2%    |
| 0x706a1    | 2         | 1.2%    |
| 0x6d8      | 2         | 1.2%    |
| 0x30678    | 2         | 1.2%    |
| 0x0a50000c | 2         | 1.2%    |
| 0x08108102 | 2         | 1.2%    |
| 0x906ed    | 1         | 0.6%    |
| 0x806eb    | 1         | 0.6%    |
| 0x806d1    | 1         | 0.6%    |
| 0x706a8    | 1         | 0.6%    |
| 0x6fa      | 1         | 0.6%    |
| 0x6f6      | 1         | 0.6%    |
| 0x30661    | 1         | 0.6%    |
| 0x0a404102 | 1         | 0.6%    |
| 0x08608103 | 1         | 0.6%    |
| 0x08600103 | 1         | 0.6%    |
| 0x0810100b | 1         | 0.6%    |
| 0x06001119 | 1         | 0.6%    |
| 0x02000032 | 1         | 0.6%    |
| 0x01000098 | 1         | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 29        | 17.79%  |
| Haswell         | 22        | 13.5%   |
| IvyBridge       | 15        | 9.2%    |
| SandyBridge     | 14        | 8.59%   |
| Zen 2           | 9         | 5.52%   |
| Core            | 9         | 5.52%   |
| Skylake         | 7         | 4.29%   |
| Broadwell       | 7         | 4.29%   |
| Unknown         | 7         | 4.29%   |
| Westmere        | 6         | 3.68%   |
| TigerLake       | 5         | 3.07%   |
| Penryn          | 4         | 2.45%   |
| CometLake       | 4         | 2.45%   |
| Goldmont plus   | 3         | 1.84%   |
| Bobcat          | 3         | 1.84%   |
| Zen+            | 2         | 1.23%   |
| Zen 3           | 2         | 1.23%   |
| Zen             | 2         | 1.23%   |
| Silvermont      | 2         | 1.23%   |
| P6              | 2         | 1.23%   |
| Steamroller     | 1         | 0.61%   |
| Piledriver      | 1         | 0.61%   |
| K8 Hammer       | 1         | 0.61%   |
| K8 & K10 hybrid | 1         | 0.61%   |
| K10             | 1         | 0.61%   |
| Icelake         | 1         | 0.61%   |
| Goldmont        | 1         | 0.61%   |
| Excavator       | 1         | 0.61%   |
| Bonnell         | 1         | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 123       | 55.41%  |
| Nvidia           | 61        | 27.48%  |
| AMD              | 37        | 16.67%  |
| VIA Technologies | 1         | 0.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 14        | 6.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 5.65%   |
| Intel UHD Graphics 620                                                        | 10        | 4.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 10        | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 3.91%   |
| AMD Renoir                                                                    | 9         | 3.91%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 2.61%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 2.17%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 2.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 2.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 5         | 2.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 5         | 2.17%   |
| Intel HD Graphics 630                                                         | 5         | 2.17%   |
| Intel HD Graphics 5500                                                        | 5         | 2.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 2.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 4         | 1.74%   |
| Intel HD Graphics 530                                                         | 4         | 1.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.74%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 1.3%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.87%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 0.87%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 2         | 0.87%   |
| Nvidia GP108GLM [Quadro P520]                                                 | 2         | 0.87%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 2         | 0.87%   |
| Nvidia GK208M [GeForce GT 730M]                                               | 2         | 0.87%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 2         | 0.87%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 0.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 0.87%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 0.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 0.87%   |
| Intel HD Graphics 620                                                         | 2         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 0.87%   |
| AMD VanGogh [AMD Custom GPU 0405]                                             | 2         | 0.87%   |
| AMD Rembrandt [Radeon 680M]                                                   | 2         | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 0.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 67        | 41.1%   |
| Intel + Nvidia | 51        | 31.29%  |
| 1 x AMD        | 28        | 17.18%  |
| 1 x Nvidia     | 6         | 3.68%   |
| Intel + AMD    | 5         | 3.07%   |
| AMD + Nvidia   | 3         | 1.84%   |
| 2 x Nvidia     | 1         | 0.61%   |
| 2 x AMD        | 1         | 0.61%   |
| 1 x VIA        | 1         | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 125       | 75.3%   |
| Proprietary | 39        | 23.49%  |
| Unknown     | 2         | 1.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 86        | 52.44%  |
| 1.01-2.0   | 33        | 20.12%  |
| 0.01-0.5   | 19        | 11.59%  |
| 3.01-4.0   | 11        | 6.71%   |
| 0.51-1.0   | 10        | 6.1%    |
| 5.01-6.0   | 3         | 1.83%   |
| 2.01-3.0   | 1         | 0.61%   |
| 8.01-16.0  | 1         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 31        | 15.82%  |
| Chimei Innolux          | 30        | 15.31%  |
| LG Display              | 21        | 10.71%  |
| BOE                     | 21        | 10.71%  |
| Samsung Electronics     | 18        | 9.18%   |
| Dell                    | 17        | 8.67%   |
| Chi Mei Optoelectronics | 11        | 5.61%   |
| Sharp                   | 6         | 3.06%   |
| Lenovo                  | 5         | 2.55%   |
| Hewlett-Packard         | 4         | 2.04%   |
| Goldstar                | 4         | 2.04%   |
| Apple                   | 4         | 2.04%   |
| Sony                    | 3         | 1.53%   |
| PANDA                   | 3         | 1.53%   |
| LG Philips              | 3         | 1.53%   |
| ViewSonic               | 1         | 0.51%   |
| Toshiba                 | 1         | 0.51%   |
| Seiko/Epson             | 1         | 0.51%   |
| Philips                 | 1         | 0.51%   |
| Panasonic               | 1         | 0.51%   |
| Lenovo Group Limited    | 1         | 0.51%   |
| KDB                     | 1         | 0.51%   |
| JDI                     | 1         | 0.51%   |
| InfoVision              | 1         | 0.51%   |
| CSO                     | 1         | 0.51%   |
| CPT                     | 1         | 0.51%   |
| ASUSTek Computer        | 1         | 0.51%   |
| AOC                     | 1         | 0.51%   |
| Analogix                | 1         | 0.51%   |
| Acer                    | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 1.48%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 3         | 1.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 1.48%   |
| Sony TV SNYDB01 1920x1080                                                 | 2         | 0.99%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.99%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 0.99%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.99%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 2         | 0.99%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.99%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.99%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.99%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.99%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 2         | 0.99%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 0.99%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 0.99%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 2         | 0.99%   |
| ViewSonic VP2030 SERIES VSC131C 1600x1200 408x306mm 20.1-inch             | 1         | 0.49%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                     | 1         | 0.49%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.49%   |
| Sharp LQ133M1JW40 SHP10CD 1920x1080 294x165mm 13.3-inch                   | 1         | 0.49%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 0.49%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 1         | 0.49%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                   | 1         | 0.49%   |
| Seiko/Epson LCD Monitor 1920x1080                                         | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch      | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM030E 1680x1050 474x296mm 22.0-inch      | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch      | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch      | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 79        | 42.47%  |
| 1366x768 (WXGA)    | 43        | 23.12%  |
| 1600x900 (HD+)     | 12        | 6.45%   |
| 1280x800 (WXGA)    | 11        | 5.91%   |
| 3840x2160 (4K)     | 9         | 4.84%   |
| 1920x1200 (WUXGA)  | 6         | 3.23%   |
| 2560x1600          | 5         | 2.69%   |
| 1680x1050 (WSXGA+) | 5         | 2.69%   |
| 2560x1440 (QHD)    | 4         | 2.15%   |
| 1280x1024 (SXGA)   | 3         | 1.61%   |
| 3440x1440          | 2         | 1.08%   |
| 1440x900 (WXGA+)   | 2         | 1.08%   |
| 800x1280           | 1         | 0.54%   |
| 3840x2400          | 1         | 0.54%   |
| 2560x1080          | 1         | 0.54%   |
| 2256x1504          | 1         | 0.54%   |
| 1600x1200          | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 77        | 38.69%  |
| 14      | 26        | 13.07%  |
| 13      | 22        | 11.06%  |
| 17      | 14        | 7.04%   |
| 24      | 11        | 5.53%   |
| 12      | 8         | 4.02%   |
| 27      | 6         | 3.02%   |
| Unknown | 5         | 2.51%   |
| 16      | 4         | 2.01%   |
| 72      | 3         | 1.51%   |
| 34      | 3         | 1.51%   |
| 23      | 3         | 1.51%   |
| 22      | 3         | 1.51%   |
| 40      | 2         | 1.01%   |
| 65      | 1         | 0.5%    |
| 54      | 1         | 0.5%    |
| 43      | 1         | 0.5%    |
| 38      | 1         | 0.5%    |
| 31      | 1         | 0.5%    |
| 29      | 1         | 0.5%    |
| 26      | 1         | 0.5%    |
| 21      | 1         | 0.5%    |
| 20      | 1         | 0.5%    |
| 19      | 1         | 0.5%    |
| 11      | 1         | 0.5%    |
| 10      | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 112       | 56.85%  |
| 201-300     | 24        | 12.18%  |
| 501-600     | 20        | 10.15%  |
| 351-400     | 16        | 8.12%   |
| 401-500     | 5         | 2.54%   |
| Unknown     | 5         | 2.54%   |
| 801-900     | 3         | 1.52%   |
| 701-800     | 3         | 1.52%   |
| 601-700     | 3         | 1.52%   |
| 1501-2000   | 3         | 1.52%   |
| 1001-1500   | 2         | 1.02%   |
| 901-1000    | 1         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 136       | 77.27%  |
| 16/10   | 27        | 15.34%  |
| 21/9    | 3         | 1.7%    |
| Unknown | 3         | 1.7%    |
| 5/4     | 2         | 1.14%   |
| 4/3     | 2         | 1.14%   |
| 3/2     | 2         | 1.14%   |
| 0.62    | 1         | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 77        | 38.89%  |
| 81-90          | 36        | 18.18%  |
| 201-250        | 14        | 7.07%   |
| 71-80          | 12        | 6.06%   |
| 121-130        | 12        | 6.06%   |
| 61-70          | 8         | 4.04%   |
| 301-350        | 7         | 3.54%   |
| More than 1000 | 5         | 2.53%   |
| 351-500        | 5         | 2.53%   |
| Unknown        | 5         | 2.53%   |
| 111-120        | 4         | 2.02%   |
| 501-1000       | 4         | 2.02%   |
| 251-300        | 3         | 1.52%   |
| 151-200        | 2         | 1.01%   |
| 51-60          | 1         | 0.51%   |
| 41-50          | 1         | 0.51%   |
| 141-150        | 1         | 0.51%   |
| 131-140        | 1         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 79        | 40.51%  |
| 101-120       | 48        | 24.62%  |
| 51-100        | 36        | 18.46%  |
| 161-240       | 16        | 8.21%   |
| More than 240 | 6         | 3.08%   |
| 1-50          | 5         | 2.56%   |
| Unknown       | 5         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 126       | 75.45%  |
| 2     | 33        | 19.76%  |
| 3     | 7         | 4.19%   |
| 0     | 1         | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 98        | 37.4%   |
| Realtek Semiconductor             | 74        | 28.24%  |
| Qualcomm Atheros                  | 36        | 13.74%  |
| Broadcom                          | 14        | 5.34%   |
| Ralink                            | 4         | 1.53%   |
| Lenovo                            | 4         | 1.53%   |
| Ericsson Business Mobile Networks | 4         | 1.53%   |
| TP-Link                           | 3         | 1.15%   |
| MediaTek                          | 3         | 1.15%   |
| Fibocom                           | 3         | 1.15%   |
| Broadcom Limited                  | 3         | 1.15%   |
| Sierra Wireless                   | 2         | 0.76%   |
| Huawei Technologies               | 2         | 0.76%   |
| Hewlett-Packard                   | 2         | 0.76%   |
| ASIX Electronics                  | 2         | 0.76%   |
| VIA Technologies                  | 1         | 0.38%   |
| Van Ooijen Technische Informatica | 1         | 0.38%   |
| OPPO Electronics                  | 1         | 0.38%   |
| Nvidia                            | 1         | 0.38%   |
| Marvell Technology Group          | 1         | 0.38%   |
| JMicron Technology                | 1         | 0.38%   |
| DisplayLink                       | 1         | 0.38%   |
| ASUSTek Computer                  | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 11.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 5.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 3.34%   |
| Intel Wireless 7260                                               | 10        | 3.04%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.43%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 2.43%   |
| Intel Wireless 7265                                               | 7         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 1.52%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.22%   |
| Intel Wireless 8260                                               | 4         | 1.22%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.22%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.91%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.91%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.91%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.91%   |
| Intel Wireless 3160                                               | 3         | 0.91%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.91%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.91%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.91%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 3         | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 96        | 56.14%  |
| Qualcomm Atheros      | 26        | 15.2%   |
| Realtek Semiconductor | 22        | 12.87%  |
| Broadcom              | 11        | 6.43%   |
| Ralink                | 4         | 2.34%   |
| MediaTek              | 3         | 1.75%   |
| Fibocom               | 3         | 1.75%   |
| TP-Link               | 2         | 1.17%   |
| Broadcom Limited      | 2         | 1.17%   |
| Sierra Wireless       | 1         | 0.58%   |
| Hewlett-Packard       | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 6.43%   |
| Intel Wireless 7260                                                     | 10        | 5.85%   |
| Intel Wireless 8265 / 8275                                              | 9         | 5.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.68%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 4.68%   |
| Intel Wireless 7265                                                     | 7         | 4.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 2.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.34%   |
| Intel Wireless 8260                                                     | 4         | 2.34%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 2.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.75%   |
| Intel Wireless 3160                                                     | 3         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.75%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.75%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 1.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.17%   |
| Intel Wireless 3165                                                     | 2         | 1.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.17%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.17%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.17%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.17%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 62        | 42.18%  |
| Intel                    | 47        | 31.97%  |
| Qualcomm Atheros         | 17        | 11.56%  |
| Broadcom                 | 6         | 4.08%   |
| Lenovo                   | 3         | 2.04%   |
| ASIX Electronics         | 2         | 1.36%   |
| VIA Technologies         | 1         | 0.68%   |
| TP-Link                  | 1         | 0.68%   |
| Sierra Wireless          | 1         | 0.68%   |
| OPPO Electronics         | 1         | 0.68%   |
| Nvidia                   | 1         | 0.68%   |
| Marvell Technology Group | 1         | 0.68%   |
| JMicron Technology       | 1         | 0.68%   |
| DisplayLink              | 1         | 0.68%   |
| Broadcom Limited         | 1         | 0.68%   |
| ASUSTek Computer         | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 25.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 11.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 6.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 4.08%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.4%    |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 3.4%    |
| Intel Ethernet Connection (4) I219-V                              | 4         | 2.72%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 2.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 2.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 2.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2.04%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2.04%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.04%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.36%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 1.36%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.36%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.36%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.36%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.68%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.68%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.68%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 1         | 0.68%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.68%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.68%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.68%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 163       | 52.08%  |
| Ethernet | 139       | 44.41%  |
| Modem    | 11        | 3.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 77.59%  |
| Ethernet | 39        | 22.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 129       | 79.14%  |
| 1     | 31        | 19.02%  |
| 0     | 2         | 1.23%   |
| 3     | 1         | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 143       | 86.14%  |
| Yes  | 23        | 13.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 51.94%  |
| Broadcom                        | 11        | 8.53%   |
| Qualcomm Atheros Communications | 10        | 7.75%   |
| IMC Networks                    | 10        | 7.75%   |
| Realtek Semiconductor           | 9         | 6.98%   |
| Hewlett-Packard                 | 4         | 3.1%    |
| Cambridge Silicon Radio         | 4         | 3.1%    |
| Apple                           | 4         | 3.1%    |
| Realtek                         | 3         | 2.33%   |
| Foxconn / Hon Hai               | 2         | 1.55%   |
| Toshiba                         | 1         | 0.78%   |
| Ralink                          | 1         | 0.78%   |
| Lite-On Technology              | 1         | 0.78%   |
| Dell                            | 1         | 0.78%   |
| Askey Computer                  | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 34        | 26.36%  |
| Intel AX201 Bluetooth                               | 11        | 8.53%   |
| Intel AX200 Bluetooth                               | 7         | 5.43%   |
| Realtek Bluetooth Radio                             | 6         | 4.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 4.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 3.88%   |
| IMC Networks Bluetooth Device                       | 5         | 3.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 3.1%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 2.33%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.33%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 2.33%   |
| Apple Bluetooth Host Controller                     | 3         | 2.33%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.55%   |
| Realtek Bluetooth Radio                             | 2         | 1.55%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.55%   |
| Intel AX210 Bluetooth                               | 2         | 1.55%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.55%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.55%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.55%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.55%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.78%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.78%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.78%   |
| Lite-On Bluetooth Device                            | 1         | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.78%   |
| IMC Networks Wireless_Device                        | 1         | 0.78%   |
| IMC Networks BCM20702A0                             | 1         | 0.78%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.78%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.78%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.78%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.78%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.78%   |
| Askey Bluetooth Device                              | 1         | 0.78%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 131       | 66.16%  |
| AMD                   | 33        | 16.67%  |
| Nvidia                | 19        | 9.6%    |
| Lenovo                | 4         | 2.02%   |
| Realtek Semiconductor | 2         | 1.01%   |
| VIA Technologies      | 1         | 0.51%   |
| Texas Instruments     | 1         | 0.51%   |
| TerraTec Electronic   | 1         | 0.51%   |
| Roland                | 1         | 0.51%   |
| Micronas              | 1         | 0.51%   |
| Mark of the Unicorn   | 1         | 0.51%   |
| Logitech              | 1         | 0.51%   |
| JMTek                 | 1         | 0.51%   |
| C-Media Electronics   | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 18        | 7.35%   |
| Intel Sunrise Point-LP HD Audio                                            | 15        | 6.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 5.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 5.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 3.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 3.67%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 3.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 3.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 2.86%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 2.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 2.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 2.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.04%   |
| Intel CM238 HD Audio Controller                                            | 5         | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.04%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.63%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.63%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.63%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.63%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.22%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.82%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.82%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.82%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 2         | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.82%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 0.82%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.82%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.41%   |
| Texas Instruments Sabaj A4 AMP                                             | 1         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 30.19%  |
| SK hynix            | 25        | 23.58%  |
| Micron Technology   | 17        | 16.04%  |
| Kingston            | 9         | 8.49%   |
| Crucial             | 5         | 4.72%   |
| Unknown             | 3         | 2.83%   |
| Ramaxel Technology  | 3         | 2.83%   |
| Unknown (ABCD)      | 2         | 1.89%   |
| Nanya Technology    | 2         | 1.89%   |
| ASint Technology    | 2         | 1.89%   |
| A-DATA Technology   | 2         | 1.89%   |
| Unifosa             | 1         | 0.94%   |
| Qimonda             | 1         | 0.94%   |
| G.Skill             | 1         | 0.94%   |
| Elpida              | 1         | 0.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 4         | 3.51%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s             | 2         | 1.75%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 2         | 1.75%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                        | 2         | 1.75%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 2         | 1.75%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                        | 2         | 1.75%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                        | 2         | 1.75%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                       | 2         | 1.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                        | 2         | 1.75%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s                        | 2         | 1.75%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s                        | 2         | 1.75%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s                         | 2         | 1.75%   |
| Unknown RAM Module 512MB SODIMM DDR2                                         | 1         | 0.88%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                                  | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                                | 1         | 0.88%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                        | 1         | 0.88%   |
| Unifosa RAM GU332G0AJEPR8H2L.. 2GB SODIMM DDR2 667MT/s                       | 1         | 0.88%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                              | 1         | 0.88%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s                         | 1         | 0.88%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s                         | 1         | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s                    | 1         | 0.88%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s                      | 1         | 0.88%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s                      | 1         | 0.88%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s                      | 1         | 0.88%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.88%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.88%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s               | 1         | 0.88%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB DIMM LPDDR5 6400MT/s                     | 1         | 0.88%   |
| SK hynix RAM 5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A 4096MB SODIMM DDR2 800MT/s | 1         | 0.88%   |
| SK hynix RAM 262626262626262626262626262626262626 4096MB SODIMM DDR2 800MT/s | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 37        | 43.53%  |
| DDR3   | 34        | 40%     |
| DDR2   | 6         | 7.06%   |
| LPDDR4 | 4         | 4.71%   |
| SDRAM  | 1         | 1.18%   |
| LPDDR5 | 1         | 1.18%   |
| LPDDR3 | 1         | 1.18%   |
| DDR    | 1         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 80        | 95.24%  |
| Row Of Chips | 3         | 3.57%   |
| DIMM         | 1         | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 38        | 40.43%  |
| 4096  | 30        | 31.91%  |
| 16384 | 10        | 10.64%  |
| 2048  | 9         | 9.57%   |
| 1024  | 4         | 4.26%   |
| 32768 | 2         | 2.13%   |
| 512   | 1         | 1.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 23        | 23.71%  |
| 2667    | 22        | 22.68%  |
| 3200    | 13        | 13.4%   |
| 1333    | 8         | 8.25%   |
| 1334    | 7         | 7.22%   |
| 2400    | 6         | 6.19%   |
| 2133    | 3         | 3.09%   |
| 1067    | 3         | 3.09%   |
| 667     | 3         | 3.09%   |
| 4267    | 2         | 2.06%   |
| 6400    | 1         | 1.03%   |
| 4199    | 1         | 1.03%   |
| 3266    | 1         | 1.03%   |
| 975     | 1         | 1.03%   |
| 800     | 1         | 1.03%   |
| 400     | 1         | 1.03%   |
| Unknown | 1         | 1.03%   |

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
| Chicony Electronics                    | 34        | 24.29%  |
| Microdia                               | 14        | 10%     |
| IMC Networks                           | 14        | 10%     |
| Realtek Semiconductor                  | 12        | 8.57%   |
| Sunplus Innovation Technology          | 11        | 7.86%   |
| Acer                                   | 8         | 5.71%   |
| Lite-On Technology                     | 6         | 4.29%   |
| Bison Electronics                      | 6         | 4.29%   |
| Silicon Motion                         | 5         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.57%   |
| Suyin                                  | 4         | 2.86%   |
| Luxvisions Innotech Limited            | 4         | 2.86%   |
| Apple                                  | 3         | 2.14%   |
| Syntek                                 | 2         | 1.43%   |
| Quanta                                 | 2         | 1.43%   |
| Logitech                               | 2         | 1.43%   |
| Xiaomi                                 | 1         | 0.71%   |
| Tripath Technology                     | 1         | 0.71%   |
| Sonix Technology                       | 1         | 0.71%   |
| LG Electronics                         | 1         | 0.71%   |
| Lenovo                                 | 1         | 0.71%   |
| Importek                               | 1         | 0.71%   |
| Huddly                                 | 1         | 0.71%   |
| Alcor Micro                            | 1         | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 6.38%   |
| Chicony Integrated Camera                               | 6         | 4.26%   |
| Lite-On Integrated Camera                               | 5         | 3.55%   |
| Realtek USB Camera                                      | 4         | 2.84%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 2.13%   |
| IMC Networks Integrated Camera                          | 3         | 2.13%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 2.13%   |
| Chicony Integrated HP HD Webcam                         | 3         | 2.13%   |
| Chicony FJ Camera                                       | 3         | 2.13%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.42%   |
| Sunplus Asus Webcam                                     | 2         | 1.42%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.42%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.42%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.42%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.42%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.42%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.42%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.42%   |
| Chicony ThinkPad T490 Webcam                            | 2         | 1.42%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.42%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.42%   |
| Chicony HP HD Webcam                                    | 2         | 1.42%   |
| Bison Integrated Camera                                 | 2         | 1.42%   |
| Apple FaceTime HD Camera                                | 2         | 1.42%   |
| Acer Integrated Camera                                  | 2         | 1.42%   |
| Xiaomi Mi 9 Lite                                        | 1         | 0.71%   |
| Tripath USB Camera                                      | 1         | 0.71%   |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.71%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.71%   |
| Suyin USB Webcam                                        | 1         | 0.71%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.71%   |
| Suyin HD WebCam                                         | 1         | 0.71%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.71%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.71%   |
| Sunplus Laptop Integrated Webcam FHD                    | 1         | 0.71%   |
| Sunplus Integrated Webcam                               | 1         | 0.71%   |
| Sunplus HP Wide Vision HD                               | 1         | 0.71%   |
| Sunplus HP Universal Camera                             | 1         | 0.71%   |
| Sunplus HD Webcam                                       | 1         | 0.71%   |
| Sunplus Dell HD Webcam                                  | 1         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 18        | 43.9%   |
| Synaptics                          | 8         | 19.51%  |
| Upek                               | 4         | 9.76%   |
| STMicroelectronics                 | 4         | 9.76%   |
| Shenzhen Goodix Technology         | 4         | 9.76%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.44%   |
| Elan Microelectronics              | 1         | 2.44%   |
| AuthenTec                          | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 12.2%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 12.2%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 9.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 4         | 9.76%   |
| STMicroelectronics Fingerprint Reader                           | 4         | 9.76%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 7.32%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 3         | 7.32%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 4.88%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 4.88%   |
| Shenzhen Goodix FingerPrint                                     | 2         | 4.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 2.44%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 2.44%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.44%   |
| Synaptics WBDI                                                  | 1         | 2.44%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.44%   |
| Elan ELAN:Fingerprint                                           | 1         | 2.44%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 20        | 55.56%  |
| OmniKey               | 6         | 16.67%  |
| Lenovo                | 3         | 8.33%   |
| Gemalto (was Gemplus) | 3         | 8.33%   |
| Broadcom              | 3         | 8.33%   |
| O2 Micro              | 1         | 2.78%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 20        | 55.56%  |
| OmniKey CardMan 4321                                   | 3         | 8.33%   |
| OmniKey CardMan 1021                                   | 3         | 8.33%   |
| Lenovo Integrated Smart Card Reader                    | 3         | 8.33%   |
| Broadcom 58200                                         | 3         | 8.33%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 2         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 2.78%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 2.78%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 93        | 56.36%  |
| 1     | 49        | 29.7%   |
| 2     | 20        | 12.12%  |
| 3     | 3         | 1.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 41        | 42.71%  |
| Graphics card            | 22        | 22.92%  |
| Chipcard                 | 19        | 19.79%  |
| Net/wireless             | 4         | 4.17%   |
| Camera                   | 3         | 3.13%   |
| Card reader              | 2         | 2.08%   |
| Net/ethernet             | 1         | 1.04%   |
| Multimedia controller    | 1         | 1.04%   |
| Modem                    | 1         | 1.04%   |
| Communication controller | 1         | 1.04%   |
| Bluetooth                | 1         | 1.04%   |

