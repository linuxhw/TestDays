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

Total: 196

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 19        | 12.75%  |
| Ubuntu 18.04       | 14        | 9.4%    |
| Arch               | 7         | 4.7%    |
| Ubuntu 19.04       | 6         | 4.03%   |
| Linux Mint 20.1    | 5         | 3.36%   |
| ArcoLinux Rolling  | 5         | 3.36%   |
| Ubuntu 22.04       | 4         | 2.68%   |
| Kubuntu 22.04      | 4         | 2.68%   |
| Fedora 34          | 4         | 2.68%   |
| ROSA R9            | 3         | 2.01%   |
| ROSA R8.1          | 3         | 2.01%   |
| ROSA R11           | 3         | 2.01%   |
| Pop!_OS 20.04      | 3         | 2.01%   |
| OpenMandriva 4.2   | 3         | 2.01%   |
| Kubuntu 20.04      | 3         | 2.01%   |
| Zorin 16           | 2         | 1.34%   |
| Xubuntu 20.04      | 2         | 1.34%   |
| Ubuntu 20.10       | 2         | 1.34%   |
| Ubuntu 19.10       | 2         | 1.34%   |
| ROSA 12.2          | 2         | 1.34%   |
| Reborn OS          | 2         | 1.34%   |
| Manjaro 20.1       | 2         | 1.34%   |
| Manjaro            | 2         | 1.34%   |
| Linux Mint 20.2    | 2         | 1.34%   |
| Linux Mint 19.3    | 2         | 1.34%   |
| Linux Mint 18.3    | 2         | 1.34%   |
| KDE neon 20.04     | 2         | 1.34%   |
| Fedora 36          | 2         | 1.34%   |
| Elementary 6.1     | 2         | 1.34%   |
| Debian 11          | 2         | 1.34%   |
| Arch Rolling       | 2         | 1.34%   |
| Zorin 15           | 1         | 0.67%   |
| Xubuntu 18.04      | 1         | 0.67%   |
| Ubuntu Unity 16.04 | 1         | 0.67%   |
| Ubuntu MATE 22.04  | 1         | 0.67%   |
| Ubuntu MATE 20.04  | 1         | 0.67%   |
| Ubuntu 21.04       | 1         | 0.67%   |
| SteamOS 3.3        | 1         | 0.67%   |
| ROSA R8            | 1         | 0.67%   |
| ROSA R10           | 1         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 48        | 32.88%  |
| ROSA         | 13        | 8.9%    |
| Linux Mint   | 13        | 8.9%    |
| Arch         | 9         | 6.16%   |
| Manjaro      | 8         | 5.48%   |
| Fedora       | 8         | 5.48%   |
| Kubuntu      | 6         | 4.11%   |
| Pop!_OS      | 5         | 3.42%   |
| ArcoLinux    | 5         | 3.42%   |
| OpenMandriva | 4         | 2.74%   |
| Zorin        | 3         | 2.05%   |
| Xubuntu      | 3         | 2.05%   |
| Endless      | 3         | 2.05%   |
| Elementary   | 3         | 2.05%   |
| Debian       | 3         | 2.05%   |
| Ubuntu MATE  | 2         | 1.37%   |
| Reborn OS    | 2         | 1.37%   |
| KDE neon     | 2         | 1.37%   |
| Clear Linux  | 2         | 1.37%   |
| Ubuntu Unity | 1         | 0.68%   |
| SteamOS      | 1         | 0.68%   |
| Lubuntu      | 1         | 0.68%   |
| LMDE         | 1         | 0.68%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 6         | 3.75%   |
| 5.4.0-47-generic                   | 3         | 1.88%   |
| 5.4.0-28-generic                   | 3         | 1.88%   |
| 5.15.0-52-generic                  | 3         | 1.88%   |
| 5.10.14-desktop-1omv4002           | 3         | 1.88%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 1.88%   |
| 5.8.0-53-generic                   | 2         | 1.25%   |
| 5.4.0-88-generic                   | 2         | 1.25%   |
| 5.4.0-65-generic                   | 2         | 1.25%   |
| 5.15.2-arch1-1                     | 2         | 1.25%   |
| 5.13.0-39-generic                  | 2         | 1.25%   |
| 5.11.0-27-generic                  | 2         | 1.25%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 1.25%   |
| 5.0.0-23-generic                   | 2         | 1.25%   |
| 4.18.0-15-generic                  | 2         | 1.25%   |
| 4.15.0-45-generic                  | 2         | 1.25%   |
| 6.0.2-2-MANJARO                    | 1         | 0.63%   |
| 5.9.16-1-MANJARO                   | 1         | 0.63%   |
| 5.9.13-200.fc33.x86_64             | 1         | 0.63%   |
| 5.9.10-zen1-1-zen                  | 1         | 0.63%   |
| 5.9.0-050900rc5-lowlatency         | 1         | 0.63%   |
| 5.8.6-1-MANJARO                    | 1         | 0.63%   |
| 5.8.0-7630-generic                 | 1         | 0.63%   |
| 5.8.0-63-generic                   | 1         | 0.63%   |
| 5.8.0-59-generic                   | 1         | 0.63%   |
| 5.8.0-54-generic                   | 1         | 0.63%   |
| 5.8.0-50-generic                   | 1         | 0.63%   |
| 5.8.0-45-generic                   | 1         | 0.63%   |
| 5.8.0-44-generic                   | 1         | 0.63%   |
| 5.8.0-38-generic                   | 1         | 0.63%   |
| 5.8.0-29-generic                   | 1         | 0.63%   |
| 5.8.0-14-generic                   | 1         | 0.63%   |
| 5.6.13-100.fc30.x86_64             | 1         | 0.63%   |
| 5.5.6-1-MANJARO                    | 1         | 0.63%   |
| 5.4.64-1-MANJARO                   | 1         | 0.63%   |
| 5.4.0-7642-generic                 | 1         | 0.63%   |
| 5.4.0-7634-generic                 | 1         | 0.63%   |
| 5.4.0-72-generic                   | 1         | 0.63%   |
| 5.4.0-70-generic                   | 1         | 0.63%   |
| 5.4.0-66-generic                   | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 31        | 20.13%  |
| 4.15.0  | 13        | 8.44%   |
| 5.15.0  | 10        | 6.49%   |
| 5.8.0   | 9         | 5.84%   |
| 5.11.0  | 7         | 4.55%   |
| 5.0.0   | 7         | 4.55%   |
| 5.13.0  | 6         | 3.9%    |
| 4.18.0  | 5         | 3.25%   |
| 4.9.20  | 4         | 2.6%    |
| 5.3.0   | 3         | 1.95%   |
| 5.10.14 | 3         | 1.95%   |
| 5.17.1  | 2         | 1.3%    |
| 5.15.2  | 2         | 1.3%    |
| 5.13.13 | 2         | 1.3%    |
| 5.13.12 | 2         | 1.3%    |
| 5.11.12 | 2         | 1.3%    |
| 5.10.74 | 2         | 1.3%    |
| 6.0.2   | 1         | 0.65%   |
| 5.9.16  | 1         | 0.65%   |
| 5.9.13  | 1         | 0.65%   |
| 5.9.10  | 1         | 0.65%   |
| 5.9.0   | 1         | 0.65%   |
| 5.8.6   | 1         | 0.65%   |
| 5.6.13  | 1         | 0.65%   |
| 5.5.6   | 1         | 0.65%   |
| 5.4.64  | 1         | 0.65%   |
| 5.19.8  | 1         | 0.65%   |
| 5.17.6  | 1         | 0.65%   |
| 5.17.4  | 1         | 0.65%   |
| 5.16.9  | 1         | 0.65%   |
| 5.16.7  | 1         | 0.65%   |
| 5.16.5  | 1         | 0.65%   |
| 5.16.15 | 1         | 0.65%   |
| 5.15.5  | 1         | 0.65%   |
| 5.15.15 | 1         | 0.65%   |
| 5.14.21 | 1         | 0.65%   |
| 5.14.2  | 1         | 0.65%   |
| 5.13.9  | 1         | 0.65%   |
| 5.13.8  | 1         | 0.65%   |
| 5.13.7  | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 32        | 20.78%  |
| 5.15    | 14        | 9.09%   |
| 5.13    | 14        | 9.09%   |
| 4.15    | 13        | 8.44%   |
| 5.10    | 11        | 7.14%   |
| 5.8     | 10        | 6.49%   |
| 5.11    | 10        | 6.49%   |
| 5.0     | 8         | 5.19%   |
| 4.9     | 7         | 4.55%   |
| 4.18    | 5         | 3.25%   |
| 5.9     | 4         | 2.6%    |
| 5.17    | 4         | 2.6%    |
| 5.16    | 4         | 2.6%    |
| 5.3     | 3         | 1.95%   |
| 5.12    | 3         | 1.95%   |
| 5.14    | 2         | 1.3%    |
| 4.19    | 2         | 1.3%    |
| 6.0     | 1         | 0.65%   |
| 5.6     | 1         | 0.65%   |
| 5.5     | 1         | 0.65%   |
| 5.19    | 1         | 0.65%   |
| 4.4     | 1         | 0.65%   |
| 4.10    | 1         | 0.65%   |
| 4.1     | 1         | 0.65%   |
| 3.16    | 1         | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 138       | 96.5%   |
| i686   | 5         | 3.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 49        | 33.79%  |
| Unknown    | 25        | 17.24%  |
| KDE5       | 19        | 13.1%   |
| XFCE       | 11        | 7.59%   |
| X-Cinnamon | 9         | 6.21%   |
| KDE4       | 8         | 5.52%   |
| MATE       | 6         | 4.14%   |
| Pantheon   | 3         | 2.07%   |
| KDE        | 3         | 2.07%   |
| Unity      | 2         | 1.38%   |
| LXQt       | 2         | 1.38%   |
| i3         | 2         | 1.38%   |
| awesome    | 2         | 1.38%   |
| openbox    | 1         | 0.69%   |
| LXDE       | 1         | 0.69%   |
| Cinnamon   | 1         | 0.69%   |
| Budgie     | 1         | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 114       | 79.72%  |
| Wayland | 18        | 12.59%  |
| Unknown | 10        | 6.99%   |
| Tty     | 1         | 0.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 76        | 52.41%  |
| SDDM    | 22        | 15.17%  |
| GDM     | 18        | 12.41%  |
| TDM     | 9         | 6.21%   |
| KDM     | 8         | 5.52%   |
| LightDM | 6         | 4.14%   |
| GDM3    | 6         | 4.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 67        | 46.21%  |
| Unknown         | 32        | 22.07%  |
| et_EE           | 22        | 15.17%  |
| ru_RU           | 11        | 7.59%   |
| en_GB           | 5         | 3.45%   |
| de_DE           | 2         | 1.38%   |
| uk_UA           | 1         | 0.69%   |
| ru_UA           | 1         | 0.69%   |
| fr_FR           | 1         | 0.69%   |
| en_US.iso885915 | 1         | 0.69%   |
| en_DK           | 1         | 0.69%   |
| C               | 1         | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 77        | 52.38%  |
| EFI  | 70        | 47.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 108       | 75.52%  |
| Btrfs   | 14        | 9.79%   |
| Unknown | 12        | 8.39%   |
| Overlay | 5         | 3.5%    |
| Xfs     | 2         | 1.4%    |
| Zfs     | 1         | 0.7%    |
| Ext3    | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 83        | 57.64%  |
| GPT     | 43        | 29.86%  |
| MBR     | 18        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 132       | 91.67%  |
| Yes       | 12        | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 107       | 73.29%  |
| Yes       | 39        | 26.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 41        | 28.67%  |
| Hewlett-Packard     | 29        | 20.28%  |
| Dell                | 21        | 14.69%  |
| ASUSTek Computer    | 17        | 11.89%  |
| Samsung Electronics | 7         | 4.9%    |
| Acer                | 5         | 3.5%    |
| MSI                 | 4         | 2.8%    |
| Timi                | 2         | 1.4%    |
| Quanta              | 2         | 1.4%    |
| Fujitsu             | 2         | 1.4%    |
| Apple               | 2         | 1.4%    |
| Valve               | 1         | 0.7%    |
| TUXEDO              | 1         | 0.7%    |
| Toshiba             | 1         | 0.7%    |
| Notebook            | 1         | 0.7%    |
| mPTech              | 1         | 0.7%    |
| HUAWEI              | 1         | 0.7%    |
| Getac               | 1         | 0.7%    |
| Fujitsu Siemens     | 1         | 0.7%    |
| Framework           | 1         | 0.7%    |
| Chuwi               | 1         | 0.7%    |
| Alienware           | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Quanta TWH                                            | 2         | 1.4%    |
| Lenovo Y50-70 20378                                   | 2         | 1.4%    |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 1.4%    |
| HP Pavilion dv7                                       | 2         | 1.4%    |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 1.4%    |
| HP EliteBook 8470p                                    | 2         | 1.4%    |
| HP EliteBook 8460p                                    | 2         | 1.4%    |
| HP EliteBook 840 G2                                   | 2         | 1.4%    |
| Dell Inspiron N5110                                   | 2         | 1.4%    |
| Valve Jupiter                                         | 1         | 0.7%    |
| TUXEDO Book BA1510                                    | 1         | 0.7%    |
| Toshiba Satellite L855                                | 1         | 0.7%    |
| Timi RedmiBook 16                                     | 1         | 0.7%    |
| Timi RedmiBook 14 II                                  | 1         | 0.7%    |
| Samsung R410                                          | 1         | 0.7%    |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.7%    |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.7%    |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.7%    |
| Samsung 535U3C                                        | 1         | 0.7%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.7%    |
| Samsung 275E4E/275E5E                                 | 1         | 0.7%    |
| Notebook W35xSS_370SS                                 | 1         | 0.7%    |
| MSI GT70 2OC/2OD                                      | 1         | 0.7%    |
| MSI GS75 Stealth 8SE                                  | 1         | 0.7%    |
| MSI GP62M 7RDX                                        | 1         | 0.7%    |
| MSI GL72 6QD                                          | 1         | 0.7%    |
| mPTech ARC 11.6 128GB HD                              | 1         | 0.7%    |
| Lenovo Y720-15IKB 80VR                                | 1         | 0.7%    |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.7%    |
| Lenovo V110-15ISK 80TL                                | 1         | 0.7%    |
| Lenovo ThinkPad X260 20F5S84400                       | 1         | 0.7%    |
| Lenovo ThinkPad X220 4291R30                          | 1         | 0.7%    |
| Lenovo ThinkPad X220 429136G                          | 1         | 0.7%    |
| Lenovo ThinkPad X201 3680CG7                          | 1         | 0.7%    |
| Lenovo ThinkPad W541 20EF001TMS                       | 1         | 0.7%    |
| Lenovo ThinkPad T61 76641FG                           | 1         | 0.7%    |
| Lenovo ThinkPad T61 766112G                           | 1         | 0.7%    |
| Lenovo ThinkPad T61 765912G                           | 1         | 0.7%    |
| Lenovo ThinkPad T61 64665DG                           | 1         | 0.7%    |
| Lenovo ThinkPad T580 20L90026MX                       | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 30        | 20.98%  |
| HP EliteBook       | 12        | 8.39%   |
| HP Pavilion        | 7         | 4.9%    |
| Dell Inspiron      | 6         | 4.2%    |
| Dell Latitude      | 5         | 3.5%    |
| Dell Precision     | 4         | 2.8%    |
| Acer Aspire        | 4         | 2.8%    |
| Lenovo IdeaPad     | 3         | 2.1%    |
| Dell XPS           | 3         | 2.1%    |
| ASUS VivoBook      | 3         | 2.1%    |
| Timi RedmiBook     | 2         | 1.4%    |
| Samsung 900X3C     | 2         | 1.4%    |
| Quanta TWH         | 2         | 1.4%    |
| Lenovo Y50-70      | 2         | 1.4%    |
| HP Presario        | 2         | 1.4%    |
| HP OMEN            | 2         | 1.4%    |
| HP ENVY            | 2         | 1.4%    |
| HP Compaq          | 2         | 1.4%    |
| Fujitsu LIFEBOOK   | 2         | 1.4%    |
| ASUS ZenBook       | 2         | 1.4%    |
| Valve Jupiter      | 1         | 0.7%    |
| TUXEDO Book        | 1         | 0.7%    |
| Toshiba Satellite  | 1         | 0.7%    |
| Samsung R410       | 1         | 0.7%    |
| Samsung 770Z5E     | 1         | 0.7%    |
| Samsung 535U3C     | 1         | 0.7%    |
| Samsung 300E5EV    | 1         | 0.7%    |
| Samsung 275E4E     | 1         | 0.7%    |
| Notebook W35xSS    | 1         | 0.7%    |
| MSI GT70           | 1         | 0.7%    |
| MSI GS75           | 1         | 0.7%    |
| MSI GP62M          | 1         | 0.7%    |
| MSI GL72           | 1         | 0.7%    |
| mPTech ARC         | 1         | 0.7%    |
| Lenovo Y720-15IKB  | 1         | 0.7%    |
| Lenovo Y520-15IKBN | 1         | 0.7%    |
| Lenovo V110-15ISK  | 1         | 0.7%    |
| Lenovo Legion      | 1         | 0.7%    |
| Lenovo IdeaPadFlex | 1         | 0.7%    |
| Lenovo G50-70      | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 16        | 11.19%  |
| 2011 | 16        | 11.19%  |
| 2018 | 14        | 9.79%   |
| 2019 | 13        | 9.09%   |
| 2013 | 13        | 9.09%   |
| 2014 | 12        | 8.39%   |
| 2015 | 10        | 6.99%   |
| 2017 | 9         | 6.29%   |
| 2012 | 9         | 6.29%   |
| 2008 | 6         | 4.2%    |
| 2007 | 6         | 4.2%    |
| 2016 | 5         | 3.5%    |
| 2010 | 5         | 3.5%    |
| 2021 | 4         | 2.8%    |
| 2009 | 3         | 2.1%    |
| 2022 | 1         | 0.7%    |
| 2006 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 143       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 129       | 89.58%  |
| Enabled  | 15        | 10.42%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 143       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 36        | 24.83%  |
| 4.01-8.0    | 34        | 23.45%  |
| 3.01-4.0    | 26        | 17.93%  |
| 16.01-24.0  | 24        | 16.55%  |
| 32.01-64.0  | 7         | 4.83%   |
| 24.01-32.0  | 6         | 4.14%   |
| 2.01-3.0    | 6         | 4.14%   |
| 1.01-2.0    | 5         | 3.45%   |
| 64.01-256.0 | 1         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 57        | 37.5%   |
| 2.01-3.0   | 35        | 23.03%  |
| 4.01-8.0   | 27        | 17.76%  |
| 3.01-4.0   | 14        | 9.21%   |
| 8.01-16.0  | 9         | 5.92%   |
| 0.51-1.0   | 9         | 5.92%   |
| 24.01-32.0 | 1         | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 112       | 76.71%  |
| 2      | 29        | 19.86%  |
| 3      | 3         | 2.05%   |
| 5      | 1         | 0.68%   |
| 4      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 62.76%  |
| Yes       | 54        | 37.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 85.42%  |
| No        | 21        | 14.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 77.08%  |
| No        | 33        | 22.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Estonia | 143       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Tallinn           | 94        | 64.83%  |
| Tartu             | 12        | 8.28%   |
| Pärnu            | 6         | 4.14%   |
| Rapla             | 4         | 2.76%   |
| Narva             | 4         | 2.76%   |
| Rakvere           | 3         | 2.07%   |
| Vinni             | 2         | 1.38%   |
| Otepaeae          | 2         | 1.38%   |
| Maardu            | 2         | 1.38%   |
| Keila             | 2         | 1.38%   |
| Viljandi          | 1         | 0.69%   |
| Vatla             | 1         | 0.69%   |
| Tabasalu          | 1         | 0.69%   |
| Sauga             | 1         | 0.69%   |
| Saku              | 1         | 0.69%   |
| Rae Parish        | 1         | 0.69%   |
| Põlva            | 1         | 0.69%   |
| Pohja-Sakala vald | 1         | 0.69%   |
| Laagri            | 1         | 0.69%   |
| Kärdla           | 1         | 0.69%   |
| Kaeina            | 1         | 0.69%   |
| Jõhvi            | 1         | 0.69%   |
| Jõgeva           | 1         | 0.69%   |
| AEaesmaee         | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 42     | 19.89%  |
| Seagate             | 26        | 29     | 14.77%  |
| Toshiba             | 14        | 14     | 7.95%   |
| SK hynix            | 13        | 17     | 7.39%   |
| WDC                 | 11        | 13     | 6.25%   |
| Kingston            | 11        | 12     | 6.25%   |
| Intel               | 7         | 8      | 3.98%   |
| HGST                | 7         | 8      | 3.98%   |
| SanDisk             | 6         | 8      | 3.41%   |
| Unknown             | 5         | 5      | 2.84%   |
| Hitachi             | 5         | 5      | 2.84%   |
| Micron Technology   | 3         | 3      | 1.7%    |
| Crucial             | 3         | 3      | 1.7%    |
| A-DATA Technology   | 3         | 3      | 1.7%    |
| Transcend           | 2         | 4      | 1.14%   |
| Patriot             | 2         | 2      | 1.14%   |
| Lenovo              | 2         | 2      | 1.14%   |
| KingSpec            | 2         | 2      | 1.14%   |
| Gigabyte Technology | 2         | 3      | 1.14%   |
| Fujitsu             | 2         | 2      | 1.14%   |
| China               | 2         | 2      | 1.14%   |
| Apacer              | 2         | 2      | 1.14%   |
| PNY                 | 1         | 1      | 0.57%   |
| Phison Electronics  | 1         | 1      | 0.57%   |
| Phison              | 1         | 1      | 0.57%   |
| LITEONIT            | 1         | 1      | 0.57%   |
| Lexar               | 1         | 1      | 0.57%   |
| KIOXIA              | 1         | 2      | 0.57%   |
| Intenso             | 1         | 1      | 0.57%   |
| HUAWEI              | 1         | 1      | 0.57%   |
| ASMT109x            | 1         | 2      | 0.57%   |
| Apple               | 1         | 1      | 0.57%   |
| Unknown             | 1         | 1      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST500LM021-1KJ152 500GB       | 3         | 1.66%   |
| HGST HTS721010A9E630 1TB              | 3         | 1.66%   |
| Unknown MMC Card  16GB                | 2         | 1.1%    |
| Toshiba NVMe SSD Drive 512GB          | 2         | 1.1%    |
| SK hynix NVMe SSD Drive 512GB         | 2         | 1.1%    |
| SK hynix NVMe SSD Drive 256GB         | 2         | 1.1%    |
| Seagate ST500LT012-1DG142 500GB       | 2         | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 1.1%    |
| SanDisk SD8SBAT256G1122 256GB SSD     | 2         | 1.1%    |
| Samsung SSD 970 EVO Plus 1TB          | 2         | 1.1%    |
| Samsung SSD 850 EVO M.2 500GB         | 2         | 1.1%    |
| Samsung SSD 850 EVO 500GB             | 2         | 1.1%    |
| Samsung NVMe SSD Drive 512GB          | 2         | 1.1%    |
| Samsung NVMe SSD Drive 1TB            | 2         | 1.1%    |
| Samsung NVMe SSD Drive 1024GB         | 2         | 1.1%    |
| Samsung MZVLB512HBJQ-000L7 512GB      | 2         | 1.1%    |
| Samsung MZ7LN256HCHP-000L7 256GB SSD  | 2         | 1.1%    |
| Micron 1100_MTFDDAV512TBN 512GB SSD   | 2         | 1.1%    |
| Kingston SV300S37A120G 120GB SSD      | 2         | 1.1%    |
| Kingston SA400S37960G 960GB SSD       | 2         | 1.1%    |
| Intel SSDPEKKF256G8L 256GB            | 2         | 1.1%    |
| HGST HTS541010A9E680 1TB              | 2         | 1.1%    |
| WDC WDS500G2B0B 500GB SSD             | 1         | 0.55%   |
| WDC WDS500G1X0E-00AFY0 500GB          | 1         | 0.55%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD      | 1         | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 0.55%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 1         | 0.55%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 0.55%   |
| WDC WD1200BEVS-08RST2 120GB           | 1         | 0.55%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 1         | 0.55%   |
| WDC PC SN730 NVMe 512GB               | 1         | 0.55%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB  | 1         | 0.55%   |
| Unknown MMC128  128GB                 | 1         | 0.55%   |
| Unknown MMC Card  7GB                 | 1         | 0.55%   |
| Unknown MMC Card  128GB               | 1         | 0.55%   |
| Transcend TS1TSSD230S 1TB             | 1         | 0.55%   |
| Transcend TS120GMTS420S 120GB SSD     | 1         | 0.55%   |
| Toshiba XG6 NVMe SSD Controller 512GB | 1         | 0.55%   |
| Toshiba TR200 480GB SSD               | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 25        | 28     | 51.02%  |
| HGST    | 7         | 8      | 14.29%  |
| Toshiba | 6         | 6      | 12.24%  |
| Hitachi | 5         | 5      | 10.2%   |
| WDC     | 4         | 5      | 8.16%   |
| Fujitsu | 2         | 2      | 4.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 24     | 29.58%  |
| Kingston            | 10        | 11     | 14.08%  |
| SanDisk             | 5         | 7      | 7.04%   |
| SK hynix            | 4         | 4      | 5.63%   |
| WDC                 | 3         | 4      | 4.23%   |
| Micron Technology   | 3         | 3      | 4.23%   |
| Crucial             | 3         | 3      | 4.23%   |
| A-DATA Technology   | 3         | 3      | 4.23%   |
| Transcend           | 2         | 4      | 2.82%   |
| Toshiba             | 2         | 2      | 2.82%   |
| Patriot             | 2         | 2      | 2.82%   |
| KingSpec            | 2         | 2      | 2.82%   |
| Intel               | 2         | 3      | 2.82%   |
| China               | 2         | 2      | 2.82%   |
| Apacer              | 2         | 2      | 2.82%   |
| LITEONIT            | 1         | 1      | 1.41%   |
| Lexar               | 1         | 1      | 1.41%   |
| Intenso             | 1         | 1      | 1.41%   |
| Gigabyte Technology | 1         | 2      | 1.41%   |
| Apple               | 1         | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 62        | 82     | 38.27%  |
| HDD     | 48        | 54     | 29.63%  |
| NVMe    | 43        | 56     | 26.54%  |
| MMC     | 6         | 6      | 3.7%    |
| Unknown | 3         | 4      | 1.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 133    | 64.33%  |
| NVMe | 43        | 56     | 27.39%  |
| SAS  | 7         | 7      | 4.46%   |
| MMC  | 6         | 6      | 3.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 98     | 70.18%  |
| 0.51-1.0   | 30        | 34     | 26.32%  |
| 1.01-2.0   | 3         | 3      | 2.63%   |
| 3.01-4.0   | 1         | 1      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 53        | 35.81%  |
| 251-500        | 32        | 21.62%  |
| 501-1000       | 20        | 13.51%  |
| 1-20           | 13        | 8.78%   |
| 51-100         | 10        | 6.76%   |
| 1001-2000      | 7         | 4.73%   |
| 21-50          | 5         | 3.38%   |
| Unknown        | 4         | 2.7%    |
| More than 3000 | 3         | 2.03%   |
| 2001-3000      | 1         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 64        | 42.11%  |
| 21-50          | 24        | 15.79%  |
| 51-100         | 21        | 13.82%  |
| 101-250        | 20        | 13.16%  |
| 251-500        | 11        | 7.24%   |
| 501-1000       | 5         | 3.29%   |
| Unknown        | 4         | 2.63%   |
| More than 3000 | 2         | 1.32%   |
| 1001-2000      | 1         | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 7.69%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 7.69%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 7.69%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 7.69%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 7.69%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 7.69%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 7.69%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 7.69%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 7.69%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 7.69%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 7.69%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 7.69%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 46.15%  |
| WDC               | 1         | 1      | 7.69%   |
| Micron Technology | 1         | 1      | 7.69%   |
| Kingston          | 1         | 1      | 7.69%   |
| Hitachi           | 1         | 1      | 7.69%   |
| HGST              | 1         | 1      | 7.69%   |
| Fujitsu           | 1         | 1      | 7.69%   |
| Crucial           | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 60%     |
| WDC     | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |
| HGST    | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 76.92%  |
| SSD  | 3         | 3      | 23.08%  |

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
| Detected | 88        | 131    | 59.06%  |
| Works    | 49        | 58     | 32.89%  |
| Malfunc  | 12        | 13     | 8.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 108       | 63.53%  |
| AMD                          | 18        | 10.59%  |
| Samsung Electronics          | 15        | 8.82%   |
| SK hynix                     | 9         | 5.29%   |
| Toshiba America Info Systems | 5         | 2.94%   |
| SanDisk                      | 5         | 2.94%   |
| Phison Electronics           | 3         | 1.76%   |
| Lenovo                       | 2         | 1.18%   |
| KIOXIA                       | 2         | 1.18%   |
| VIA Technologies             | 1         | 0.59%   |
| Marvell Technology Group     | 1         | 0.59%   |
| Kingston Technology Company  | 1         | 0.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 7.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 7.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 6.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 6.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 5.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 4.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 3.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 3.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 3.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 2.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 2.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 2.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.16%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 1.62%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 3         | 1.62%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 1.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.62%   |
| SK hynix Non-Volatile memory controller                                          | 2         | 1.08%   |
| SK hynix Gold P31 SSD                                                            | 2         | 1.08%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.08%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 1.08%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.08%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 1.08%   |
| Intel SSD 660P Series                                                            | 2         | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.08%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 2         | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 1.08%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.54%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.54%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.54%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 0.54%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.54%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.54%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.54%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 115       | 64.61%  |
| NVMe | 44        | 24.72%  |
| IDE  | 13        | 7.3%    |
| RAID | 6         | 3.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 120       | 83.92%  |
| AMD    | 23        | 16.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 4.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 2.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.1%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.4%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.4%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 1.4%    |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 1.4%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.4%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.4%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.4%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.4%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.4%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 1.4%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.4%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.4%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.4%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.4%    |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.4%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.4%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.4%    |
| Intel Pentium M processor 2.13GHz             | 1         | 0.7%    |
| Intel Pentium M processor 1.50GHz             | 1         | 0.7%    |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.7%    |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.7%    |
| Intel Pentium CPU 2127U @ 1.90GHz             | 1         | 0.7%    |
| Intel Pentium 3805U @ 1.90GHz                 | 1         | 0.7%    |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.7%    |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.7%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.7%    |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.7%    |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 0.7%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 44        | 30.77%  |
| Intel Core i5                  | 40        | 27.97%  |
| Intel Core i3                  | 7         | 4.9%    |
| Intel Core 2 Duo               | 7         | 4.9%    |
| Intel Celeron                  | 7         | 4.9%    |
| AMD Ryzen 5                    | 7         | 4.9%    |
| Other                          | 5         | 3.5%    |
| Intel Pentium                  | 3         | 2.1%    |
| AMD Ryzen 7                    | 3         | 2.1%    |
| Intel Pentium M                | 2         | 1.4%    |
| Intel Celeron Dual-Core        | 2         | 1.4%    |
| AMD Ryzen 7 PRO                | 2         | 1.4%    |
| Intel Pentium Dual             | 1         | 0.7%    |
| Intel Core i9                  | 1         | 0.7%    |
| Intel Core 2                   | 1         | 0.7%    |
| Intel Atom                     | 1         | 0.7%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.7%    |
| AMD Ryzen 3 PRO                | 1         | 0.7%    |
| AMD E2                         | 1         | 0.7%    |
| AMD E                          | 1         | 0.7%    |
| AMD C-60                       | 1         | 0.7%    |
| AMD Athlon II Dual-Core        | 1         | 0.7%    |
| AMD Athlon 64 X2               | 1         | 0.7%    |
| AMD A8                         | 1         | 0.7%    |
| AMD A6                         | 1         | 0.7%    |
| AMD A4                         | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 73        | 51.05%  |
| 4       | 48        | 33.57%  |
| 6       | 12        | 8.39%   |
| 8       | 4         | 2.8%    |
| 1       | 4         | 2.8%    |
| Unknown | 2         | 1.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 143       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 106       | 73.61%  |
| 1       | 36        | 25%     |
| Unknown | 2         | 1.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 140       | 97.9%   |
| 32-bit         | 2         | 1.4%    |
| Unknown        | 1         | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 19.73%  |
| 0x306a9    | 12        | 8.16%   |
| 0x206a7    | 12        | 8.16%   |
| 0x306c3    | 10        | 6.8%    |
| 0x806ea    | 7         | 4.76%   |
| 0x40651    | 6         | 4.08%   |
| 0x306d4    | 6         | 4.08%   |
| 0x906e9    | 5         | 3.4%    |
| 0x08600106 | 5         | 3.4%    |
| 0x806ec    | 4         | 2.72%   |
| 0x6fb      | 4         | 2.72%   |
| 0xa0652    | 3         | 2.04%   |
| 0x906ea    | 3         | 2.04%   |
| 0x806c1    | 3         | 2.04%   |
| 0x6fd      | 3         | 2.04%   |
| 0x506e3    | 3         | 2.04%   |
| 0x406e3    | 3         | 2.04%   |
| 0x1067a    | 3         | 2.04%   |
| 0x05000119 | 3         | 2.04%   |
| 0x806e9    | 2         | 1.36%   |
| 0x706a1    | 2         | 1.36%   |
| 0x6d8      | 2         | 1.36%   |
| 0x30678    | 2         | 1.36%   |
| 0x20655    | 2         | 1.36%   |
| 0x08108102 | 2         | 1.36%   |
| 0x906ed    | 1         | 0.68%   |
| 0x806eb    | 1         | 0.68%   |
| 0x706a8    | 1         | 0.68%   |
| 0x6f6      | 1         | 0.68%   |
| 0x30661    | 1         | 0.68%   |
| 0x0a50000c | 1         | 0.68%   |
| 0x08600103 | 1         | 0.68%   |
| 0x0810100b | 1         | 0.68%   |
| 0x06001119 | 1         | 0.68%   |
| 0x02000032 | 1         | 0.68%   |
| 0x01000098 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 29        | 20.28%  |
| Haswell         | 19        | 13.29%  |
| SandyBridge     | 14        | 9.79%   |
| IvyBridge       | 13        | 9.09%   |
| Core            | 8         | 5.59%   |
| Zen 2           | 7         | 4.9%    |
| Skylake         | 7         | 4.9%    |
| Broadwell       | 7         | 4.9%    |
| Westmere        | 4         | 2.8%    |
| TigerLake       | 4         | 2.8%    |
| Penryn          | 3         | 2.1%    |
| Goldmont plus   | 3         | 2.1%    |
| CometLake       | 3         | 2.1%    |
| Bobcat          | 3         | 2.1%    |
| Zen+            | 2         | 1.4%    |
| Zen             | 2         | 1.4%    |
| Silvermont      | 2         | 1.4%    |
| P6              | 2         | 1.4%    |
| Unknown         | 2         | 1.4%    |
| Zen 3           | 1         | 0.7%    |
| Steamroller     | 1         | 0.7%    |
| Piledriver      | 1         | 0.7%    |
| K8 Hammer       | 1         | 0.7%    |
| K8 & K10 hybrid | 1         | 0.7%    |
| K10             | 1         | 0.7%    |
| Goldmont        | 1         | 0.7%    |
| Excavator       | 1         | 0.7%    |
| Bonnell         | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 112       | 56.85%  |
| Nvidia           | 55        | 27.92%  |
| AMD              | 29        | 14.72%  |
| VIA Technologies | 1         | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 6.44%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 12        | 5.94%   |
| Intel UHD Graphics 620                                                        | 10        | 4.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 9         | 4.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 8         | 3.96%   |
| AMD Renoir                                                                    | 7         | 3.47%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 2.48%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 2.48%   |
| Intel HD Graphics 630                                                         | 5         | 2.48%   |
| Intel HD Graphics 5500                                                        | 5         | 2.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 2.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 4         | 1.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 1.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 4         | 1.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 4         | 1.98%   |
| Intel HD Graphics 530                                                         | 4         | 1.98%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 1.98%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 1.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 1.49%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.99%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 0.99%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 2         | 0.99%   |
| Nvidia GP108GLM [Quadro P520]                                                 | 2         | 0.99%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 2         | 0.99%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 2         | 0.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 0.99%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 0.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 0.99%   |
| Intel HD Graphics 620                                                         | 2         | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 0.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 0.99%   |
| VIA Technologies K8M890CE/K8N890CE [Chrome 9]                                 | 1         | 0.5%    |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 0.5%    |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 0.5%    |
| Nvidia GP107M [GeForce MX150]                                                 | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 61        | 42.66%  |
| Intel + Nvidia | 46        | 32.17%  |
| 1 x AMD        | 21        | 14.69%  |
| 1 x Nvidia     | 6         | 4.2%    |
| Intel + AMD    | 5         | 3.5%    |
| AMD + Nvidia   | 3         | 2.1%    |
| 1 x VIA        | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 109       | 74.66%  |
| Proprietary | 35        | 23.97%  |
| Unknown     | 2         | 1.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 51.39%  |
| 1.01-2.0   | 33        | 22.92%  |
| 0.01-0.5   | 16        | 11.11%  |
| 3.01-4.0   | 11        | 7.64%   |
| 0.51-1.0   | 6         | 4.17%   |
| 5.01-6.0   | 3         | 2.08%   |
| 2.01-3.0   | 1         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 29        | 16.96%  |
| AU Optronics            | 28        | 16.37%  |
| LG Display              | 18        | 10.53%  |
| BOE                     | 18        | 10.53%  |
| Dell                    | 16        | 9.36%   |
| Samsung Electronics     | 12        | 7.02%   |
| Chi Mei Optoelectronics | 10        | 5.85%   |
| Sharp                   | 6         | 3.51%   |
| Lenovo                  | 5         | 2.92%   |
| Sony                    | 3         | 1.75%   |
| LG Philips              | 3         | 1.75%   |
| Hewlett-Packard         | 3         | 1.75%   |
| PANDA                   | 2         | 1.17%   |
| Goldstar                | 2         | 1.17%   |
| Apple                   | 2         | 1.17%   |
| ViewSonic               | 1         | 0.58%   |
| Toshiba                 | 1         | 0.58%   |
| Seiko/Epson             | 1         | 0.58%   |
| Philips                 | 1         | 0.58%   |
| Lenovo Group Limited    | 1         | 0.58%   |
| KDB                     | 1         | 0.58%   |
| InfoVision              | 1         | 0.58%   |
| CSO                     | 1         | 0.58%   |
| CPT                     | 1         | 0.58%   |
| ASUSTek Computer        | 1         | 0.58%   |
| AOC                     | 1         | 0.58%   |
| ANX                     | 1         | 0.58%   |
| Ancor Communications    | 1         | 0.58%   |
| Acer                    | 1         | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 1.69%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 3         | 1.69%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 1.69%   |
| Sony TV SNYDB01 1920x1080 1600x900mm 72.3-inch                            | 2         | 1.13%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 1.13%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 1.13%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 1.13%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 2         | 1.13%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 1.13%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 1.13%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 1.13%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 1.13%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 1.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 1.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 1.13%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 1.13%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 2         | 1.13%   |
| ViewSonic VP2030 SERIES VSC131C 1600x1200 408x306mm 20.1-inch             | 1         | 0.56%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                     | 1         | 0.56%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.56%   |
| Sharp LQ133M1JW40 SHP10CD 1920x1080 294x165mm 13.3-inch                   | 1         | 0.56%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 0.56%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 1         | 0.56%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                   | 1         | 0.56%   |
| Seiko/Epson LCD Monitor 1920x1080                                         | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch      | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM030E 1680x1050 474x296mm 22.0-inch      | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch      | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch      | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch      | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 70        | 43.48%  |
| 1366x768 (WXGA)    | 39        | 24.22%  |
| 1600x900 (HD+)     | 11        | 6.83%   |
| 1280x800 (WXGA)    | 9         | 5.59%   |
| 3840x2160 (4K)     | 7         | 4.35%   |
| 1920x1200 (WUXGA)  | 5         | 3.11%   |
| 2560x1440 (QHD)    | 4         | 2.48%   |
| 1680x1050 (WSXGA+) | 4         | 2.48%   |
| 2560x1600          | 3         | 1.86%   |
| 1280x1024 (SXGA)   | 3         | 1.86%   |
| 800x1280           | 1         | 0.62%   |
| 3440x1440          | 1         | 0.62%   |
| 2560x1080          | 1         | 0.62%   |
| 2256x1504          | 1         | 0.62%   |
| 1600x1200          | 1         | 0.62%   |
| 1440x900 (WXGA+)   | 1         | 0.62%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 69        | 39.88%  |
| 14      | 23        | 13.29%  |
| 13      | 20        | 11.56%  |
| 17      | 12        | 6.94%   |
| 24      | 8         | 4.62%   |
| 27      | 7         | 4.05%   |
| 12      | 7         | 4.05%   |
| 23      | 4         | 2.31%   |
| 72      | 3         | 1.73%   |
| 22      | 3         | 1.73%   |
| Unknown | 3         | 1.73%   |
| 34      | 2         | 1.16%   |
| 16      | 2         | 1.16%   |
| 65      | 1         | 0.58%   |
| 40      | 1         | 0.58%   |
| 31      | 1         | 0.58%   |
| 29      | 1         | 0.58%   |
| 26      | 1         | 0.58%   |
| 21      | 1         | 0.58%   |
| 20      | 1         | 0.58%   |
| 19      | 1         | 0.58%   |
| 11      | 1         | 0.58%   |
| 10      | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 99        | 57.89%  |
| 201-300     | 21        | 12.28%  |
| 501-600     | 18        | 10.53%  |
| 351-400     | 14        | 8.19%   |
| 401-500     | 5         | 2.92%   |
| 601-700     | 4         | 2.34%   |
| 1501-2000   | 3         | 1.75%   |
| Unknown     | 3         | 1.75%   |
| 701-800     | 2         | 1.17%   |
| 801-900     | 1         | 0.58%   |
| 1001-1500   | 1         | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 120       | 78.95%  |
| 16/10   | 21        | 13.82%  |
| 5/4     | 2         | 1.32%   |
| 4/3     | 2         | 1.32%   |
| 3/2     | 2         | 1.32%   |
| 21/9    | 2         | 1.32%   |
| Unknown | 2         | 1.32%   |
| 0.62    | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 69        | 40.12%  |
| 81-90          | 33        | 19.19%  |
| 201-250        | 12        | 6.98%   |
| 71-80          | 10        | 5.81%   |
| 121-130        | 10        | 5.81%   |
| 301-350        | 8         | 4.65%   |
| 61-70          | 7         | 4.07%   |
| More than 1000 | 4         | 2.33%   |
| 351-500        | 4         | 2.33%   |
| 251-300        | 3         | 1.74%   |
| Unknown        | 3         | 1.74%   |
| 151-200        | 2         | 1.16%   |
| 111-120        | 2         | 1.16%   |
| 51-60          | 1         | 0.58%   |
| 41-50          | 1         | 0.58%   |
| 141-150        | 1         | 0.58%   |
| 131-140        | 1         | 0.58%   |
| 501-1000       | 1         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 71        | 42.01%  |
| 101-120       | 43        | 25.44%  |
| 51-100        | 31        | 18.34%  |
| 161-240       | 13        | 7.69%   |
| More than 240 | 4         | 2.37%   |
| 1-50          | 4         | 2.37%   |
| Unknown       | 3         | 1.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 112       | 76.19%  |
| 2     | 28        | 19.05%  |
| 3     | 6         | 4.08%   |
| 0     | 1         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 86        | 37.89%  |
| Realtek Semiconductor             | 65        | 28.63%  |
| Qualcomm Atheros                  | 34        | 14.98%  |
| Broadcom                          | 11        | 4.85%   |
| Ralink                            | 4         | 1.76%   |
| TP-Link                           | 3         | 1.32%   |
| FIBOCOM                           | 3         | 1.32%   |
| Ericsson Business Mobile Networks | 3         | 1.32%   |
| Sierra Wireless                   | 2         | 0.88%   |
| Lenovo                            | 2         | 0.88%   |
| Huawei Technologies               | 2         | 0.88%   |
| Hewlett-Packard                   | 2         | 0.88%   |
| Broadcom Limited                  | 2         | 0.88%   |
| VIA Technologies                  | 1         | 0.44%   |
| Van Ooijen Technische Informatica | 1         | 0.44%   |
| MediaTek                          | 1         | 0.44%   |
| Marvell Technology Group          | 1         | 0.44%   |
| JMicron Technology                | 1         | 0.44%   |
| DisplayLink                       | 1         | 0.44%   |
| ASUSTek Computer                  | 1         | 0.44%   |
| ASIX Electronics                  | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 32        | 11.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 5.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 3.82%   |
| Intel Wireless 8265 / 8275                                              | 9         | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.43%   |
| Intel Wireless 7265                                                     | 7         | 2.43%   |
| Intel Wireless 7260                                                     | 7         | 2.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.08%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.74%   |
| Intel Ethernet Connection (3) I218-LM                                   | 5         | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.39%   |
| Intel Wireless 8260                                                     | 4         | 1.39%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 1.39%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.39%   |
| Intel 82566MM Gigabit Network Connection                                | 4         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.04%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 1.04%   |
| Intel Wireless 3160                                                     | 3         | 1.04%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                                    | 3         | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.04%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 1.04%   |
| FIBOCOM L830-EB                                                         | 3         | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 2         | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 85        | 56.29%  |
| Qualcomm Atheros      | 25        | 16.56%  |
| Realtek Semiconductor | 18        | 11.92%  |
| Broadcom              | 8         | 5.3%    |
| Ralink                | 4         | 2.65%   |
| FIBOCOM               | 3         | 1.99%   |
| TP-Link               | 2         | 1.32%   |
| Sierra Wireless       | 2         | 1.32%   |
| Broadcom Limited      | 2         | 1.32%   |
| MediaTek              | 1         | 0.66%   |
| Hewlett-Packard       | 1         | 0.66%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 7.28%   |
| Intel Wireless 8265 / 8275                                              | 9         | 5.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.64%   |
| Intel Wireless 7265                                                     | 7         | 4.64%   |
| Intel Wireless 7260                                                     | 7         | 4.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.97%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 3.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 3.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 3.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.65%   |
| Intel Wireless 8260                                                     | 4         | 2.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.99%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.99%   |
| Intel Wireless 3160                                                     | 3         | 1.99%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.99%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.99%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.99%   |
| FIBOCOM L830-EB                                                         | 3         | 1.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.32%   |
| Intel Wireless 3165                                                     | 2         | 1.32%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.32%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.32%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.32%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.32%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.66%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.66%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.66%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.66%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 56        | 43.75%  |
| Intel                    | 43        | 33.59%  |
| Qualcomm Atheros         | 15        | 11.72%  |
| Broadcom                 | 5         | 3.91%   |
| Lenovo                   | 2         | 1.56%   |
| VIA Technologies         | 1         | 0.78%   |
| TP-Link                  | 1         | 0.78%   |
| Marvell Technology Group | 1         | 0.78%   |
| JMicron Technology       | 1         | 0.78%   |
| DisplayLink              | 1         | 0.78%   |
| ASUSTek Computer         | 1         | 0.78%   |
| ASIX Electronics         | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 25%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 13.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 7.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 4.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 3.91%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.13%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 3.13%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 3.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 2.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2.34%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2.34%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.56%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 1.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.56%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.78%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.78%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.78%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.78%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.78%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.78%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.78%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.78%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.78%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.78%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.78%   |
| Broadcom NetXtreme BCM5705M_2 Gigabit Ethernet                    | 1         | 0.78%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.78%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 143       | 52%     |
| Ethernet | 123       | 44.73%  |
| Modem    | 9         | 3.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 117       | 78%     |
| Ethernet | 33        | 22%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 114       | 79.72%  |
| 1     | 26        | 18.18%  |
| 0     | 2         | 1.4%    |
| 3     | 1         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 130       | 89.66%  |
| Yes  | 15        | 10.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 50.45%  |
| Broadcom                        | 11        | 9.91%   |
| Qualcomm Atheros Communications | 10        | 9.01%   |
| Realtek Semiconductor           | 8         | 7.21%   |
| IMC Networks                    | 8         | 7.21%   |
| Hewlett-Packard                 | 4         | 3.6%    |
| Realtek                         | 3         | 2.7%    |
| Cambridge Silicon Radio         | 3         | 2.7%    |
| Apple                           | 2         | 1.8%    |
| Toshiba                         | 1         | 0.9%    |
| Ralink                          | 1         | 0.9%    |
| Lite-On Technology              | 1         | 0.9%    |
| Foxconn / Hon Hai               | 1         | 0.9%    |
| Dell                            | 1         | 0.9%    |
| Askey Computer                  | 1         | 0.9%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 31        | 27.93%  |
| Intel AX201 Bluetooth                               | 7         | 6.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 5.41%   |
| Realtek Bluetooth Radio                             | 5         | 4.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 4.5%    |
| Intel AX200 Bluetooth                               | 5         | 4.5%    |
| IMC Networks Bluetooth Device                       | 5         | 4.5%    |
| Realtek Bluetooth Radio                             | 3         | 2.7%    |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.7%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 2.7%    |
| Realtek RTL8723B Bluetooth                          | 2         | 1.8%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.8%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.8%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.8%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.8%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.8%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.8%    |
| Apple Bluetooth Host Controller                     | 2         | 1.8%    |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.9%    |
| Ralink RT3290 Bluetooth                             | 1         | 0.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.9%    |
| Lite-On Bluetooth Device                            | 1         | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.9%    |
| Intel AX210 Bluetooth                               | 1         | 0.9%    |
| IMC Networks Bluetooth Radio                        | 1         | 0.9%    |
| IMC Networks BCM20702A0                             | 1         | 0.9%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.9%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.9%    |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.9%    |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.9%    |
| Broadcom HP Portable SoftSailing                    | 1         | 0.9%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.9%    |
| Askey Bluetooth Device                              | 1         | 0.9%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 119       | 68.39%  |
| AMD                   | 25        | 14.37%  |
| Nvidia                | 16        | 9.2%    |
| Lenovo                | 3         | 1.72%   |
| Realtek Semiconductor | 2         | 1.15%   |
| VIA Technologies      | 1         | 0.57%   |
| Texas Instruments     | 1         | 0.57%   |
| TerraTec Electronic   | 1         | 0.57%   |
| Roland                | 1         | 0.57%   |
| Micronas              | 1         | 0.57%   |
| Mark of the Unicorn   | 1         | 0.57%   |
| Logitech              | 1         | 0.57%   |
| JMTek                 | 1         | 0.57%   |
| C-Media Electronics   | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 7.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 6.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 6.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 5.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 5.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 3.77%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 3.77%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 3.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 3.3%    |
| Intel Broadwell-U Audio Controller                                         | 7         | 3.3%    |
| Intel CM238 HD Audio Controller                                            | 5         | 2.36%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.36%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 2.36%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 2.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.89%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.89%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.42%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.42%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.94%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.94%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.94%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 2         | 0.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.94%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 0.94%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.94%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.47%   |
| Texas Instruments SMSL M-3 Desktop DAC                                     | 1         | 0.47%   |
| TerraTec Electronic Aureon Dual USB                                        | 1         | 0.47%   |
| Roland DUO-CAPTURE                                                         | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 30.77%  |
| SK hynix            | 21        | 23.08%  |
| Micron Technology   | 15        | 16.48%  |
| Kingston            | 8         | 8.79%   |
| Crucial             | 5         | 5.49%   |
| Ramaxel Technology  | 3         | 3.3%    |
| Unknown (ABCD)      | 2         | 2.2%    |
| Unknown             | 2         | 2.2%    |
| A-DATA Technology   | 2         | 2.2%    |
| Unifosa             | 1         | 1.1%    |
| Nanya Technology    | 1         | 1.1%    |
| G.Skill             | 1         | 1.1%    |
| Elpida              | 1         | 1.1%    |
| ASint Technology    | 1         | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 3         | 3.06%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s             | 2         | 2.04%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                        | 2         | 2.04%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 2         | 2.04%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                        | 2         | 2.04%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                       | 2         | 2.04%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s                        | 2         | 2.04%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s                        | 2         | 2.04%   |
| Unknown RAM Module 512MB SODIMM DDR2                                         | 1         | 1.02%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                                | 1         | 1.02%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                        | 1         | 1.02%   |
| Unifosa RAM GU332G0AJEPR8H2L 2048MB SODIMM DDR2 667MT/s                      | 1         | 1.02%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                              | 1         | 1.02%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s                        | 1         | 1.02%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s                        | 1         | 1.02%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s                    | 1         | 1.02%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s                      | 1         | 1.02%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s                      | 1         | 1.02%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s                      | 1         | 1.02%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                       | 1         | 1.02%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s                    | 1         | 1.02%   |
| SK hynix RAM 5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A 4096MB SODIMM DDR2 800MT/s | 1         | 1.02%   |
| SK hynix RAM 262626262626262626262626262626262626 4096MB SODIMM DDR2 800MT/s | 1         | 1.02%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2400MT/s                              | 1         | 1.02%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                        | 1         | 1.02%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.02%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.02%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                        | 1         | 1.02%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s                        | 1         | 1.02%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 45.21%  |
| DDR3   | 29        | 39.73%  |
| DDR2   | 5         | 6.85%   |
| LPDDR4 | 3         | 4.11%   |
| SDRAM  | 1         | 1.37%   |
| LPDDR3 | 1         | 1.37%   |
| DDR    | 1         | 1.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 70        | 97.22%  |
| Row Of Chips | 2         | 2.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 29        | 35.8%   |
| 4096  | 29        | 35.8%   |
| 16384 | 10        | 12.35%  |
| 2048  | 7         | 8.64%   |
| 1024  | 3         | 3.7%    |
| 32768 | 2         | 2.47%   |
| 512   | 1         | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 21        | 25.3%   |
| 1600    | 19        | 22.89%  |
| 3200    | 10        | 12.05%  |
| 2400    | 6         | 7.23%   |
| 1334    | 6         | 7.23%   |
| 1333    | 6         | 7.23%   |
| 2133    | 3         | 3.61%   |
| 1067    | 3         | 3.61%   |
| 667     | 2         | 2.41%   |
| 4267    | 1         | 1.2%    |
| 4199    | 1         | 1.2%    |
| 3266    | 1         | 1.2%    |
| 975     | 1         | 1.2%    |
| 800     | 1         | 1.2%    |
| 400     | 1         | 1.2%    |
| Unknown | 1         | 1.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| cab Produkttechnik GmbH & Co KG | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 100%    |

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
| Chicony Electronics                    | 29        | 23.97%  |
| Microdia                               | 14        | 11.57%  |
| Realtek Semiconductor                  | 12        | 9.92%   |
| IMC Networks                           | 12        | 9.92%   |
| Acer                                   | 12        | 9.92%   |
| Sunplus Innovation Technology          | 10        | 8.26%   |
| Silicon Motion                         | 5         | 4.13%   |
| Lite-On Technology                     | 5         | 4.13%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.13%   |
| Suyin                                  | 4         | 3.31%   |
| Luxvisions Innotech Limited            | 3         | 2.48%   |
| Syntek                                 | 2         | 1.65%   |
| Quanta                                 | 2         | 1.65%   |
| Logitech                               | 2         | 1.65%   |
| Lenovo                                 | 1         | 0.83%   |
| Importek                               | 1         | 0.83%   |
| Huddly                                 | 1         | 0.83%   |
| Apple                                  | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 7.32%   |
| Realtek USB Camera                                      | 4         | 3.25%   |
| Lite-On Integrated Camera                               | 4         | 3.25%   |
| Chicony Integrated Camera                               | 4         | 3.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 2.44%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 2.44%   |
| Chicony Integrated HP HD Webcam                         | 3         | 2.44%   |
| Acer Integrated Camera                                  | 3         | 2.44%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.63%   |
| Sunplus Asus Webcam                                     | 2         | 1.63%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.63%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.63%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.63%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.63%   |
| IMC Networks Integrated Camera                          | 2         | 1.63%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.63%   |
| Chicony ThinkPad T490 Webcam                            | 2         | 1.63%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.63%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.63%   |
| Chicony HP HD Webcam                                    | 2         | 1.63%   |
| Chicony FJ Camera                                       | 2         | 1.63%   |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.81%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.81%   |
| Suyin USB Webcam                                        | 1         | 0.81%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.81%   |
| Suyin HD WebCam                                         | 1         | 0.81%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.81%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.81%   |
| Sunplus Integrated Webcam                               | 1         | 0.81%   |
| Sunplus HP Wide Vision HD                               | 1         | 0.81%   |
| Sunplus HP Universal Camera                             | 1         | 0.81%   |
| Sunplus HD WebCam                                       | 1         | 0.81%   |
| Sunplus Dell HD Webcam                                  | 1         | 0.81%   |
| Silicon Motion WebCam SC-13HDL11431N                    | 1         | 0.81%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 1         | 0.81%   |
| Silicon Motion WebCam SC-10HDD12636N                    | 1         | 0.81%   |
| Realtek USB2.0 HD UVC WebCam                            | 1         | 0.81%   |
| Realtek TOSHIBA Web Camera                              | 1         | 0.81%   |
| Realtek Lenovo EasyCamrea                               | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 44.44%  |
| Synaptics                  | 7         | 19.44%  |
| Upek                       | 4         | 11.11%  |
| STMicroelectronics         | 4         | 11.11%  |
| Shenzhen Goodix Technology | 3         | 8.33%   |
| Elan Microelectronics      | 1         | 2.78%   |
| AuthenTec                  | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 13.89%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 11.11%  |
| STMicroelectronics Fingerprint Reader                  | 4         | 11.11%  |
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 3         | 8.33%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 5.56%   |
| Shenzhen Goodix FingerPrint                            | 2         | 5.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.78%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 2.78%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.78%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 2.78%   |
| Elan ELAN:Fingerprint                                  | 1         | 2.78%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1         | 2.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 16        | 53.33%  |
| OmniKey               | 6         | 20%     |
| Lenovo                | 3         | 10%     |
| Broadcom              | 3         | 10%     |
| O2 Micro              | 1         | 3.33%   |
| Gemalto (was Gemplus) | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 16        | 53.33%  |
| OmniKey CardMan 4321                                   | 3         | 10%     |
| OmniKey CardMan 1021                                   | 3         | 10%     |
| Lenovo Integrated Smart Card Reader                    | 3         | 10%     |
| Broadcom 58200                                         | 3         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 3.33%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 80        | 55.17%  |
| 1     | 48        | 33.1%   |
| 2     | 16        | 11.03%  |
| 3     | 1         | 0.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 36        | 44.44%  |
| Graphics card            | 17        | 20.99%  |
| Chipcard                 | 16        | 19.75%  |
| Net/wireless             | 4         | 4.94%   |
| Camera                   | 2         | 2.47%   |
| Net/ethernet             | 1         | 1.23%   |
| Multimedia controller    | 1         | 1.23%   |
| Modem                    | 1         | 1.23%   |
| Communication controller | 1         | 1.23%   |
| Card reader              | 1         | 1.23%   |
| Bluetooth                | 1         | 1.23%   |

