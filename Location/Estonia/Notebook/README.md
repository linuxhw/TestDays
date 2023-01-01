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

Total: 210

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 19        | 11.95%  |
| Ubuntu 18.04       | 14        | 8.81%   |
| Ubuntu 22.04       | 8         | 5.03%   |
| Arch               | 7         | 4.4%    |
| Ubuntu 19.04       | 6         | 3.77%   |
| ArcoLinux Rolling  | 6         | 3.77%   |
| Linux Mint 20.1    | 5         | 3.14%   |
| Kubuntu 22.04      | 4         | 2.52%   |
| Fedora 34          | 4         | 2.52%   |
| ROSA R9            | 3         | 1.89%   |
| ROSA R8.1          | 3         | 1.89%   |
| ROSA R11           | 3         | 1.89%   |
| Pop!_OS 20.04      | 3         | 1.89%   |
| OpenMandriva 4.2   | 3         | 1.89%   |
| Kubuntu 20.04      | 3         | 1.89%   |
| Fedora 36          | 3         | 1.89%   |
| Zorin 16           | 2         | 1.26%   |
| Xubuntu 20.04      | 2         | 1.26%   |
| Ubuntu MATE 22.04  | 2         | 1.26%   |
| Ubuntu 20.10       | 2         | 1.26%   |
| Ubuntu 19.10       | 2         | 1.26%   |
| ROSA 12.2          | 2         | 1.26%   |
| Reborn OS          | 2         | 1.26%   |
| Manjaro 20.1       | 2         | 1.26%   |
| Manjaro            | 2         | 1.26%   |
| Linux Mint 20.2    | 2         | 1.26%   |
| Linux Mint 19.3    | 2         | 1.26%   |
| Linux Mint 18.3    | 2         | 1.26%   |
| KDE neon 20.04     | 2         | 1.26%   |
| Elementary 6.1     | 2         | 1.26%   |
| Debian 11          | 2         | 1.26%   |
| Arch Rolling       | 2         | 1.26%   |
| Zorin 15           | 1         | 0.63%   |
| Xubuntu 18.04      | 1         | 0.63%   |
| Ubuntu Unity 16.04 | 1         | 0.63%   |
| Ubuntu MATE 20.04  | 1         | 0.63%   |
| Ubuntu 21.04       | 1         | 0.63%   |
| SteamOS 3.3.2      | 1         | 0.63%   |
| SteamOS 3.3        | 1         | 0.63%   |
| ROSA R8            | 1         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 52        | 33.33%  |
| ROSA         | 13        | 8.33%   |
| Linux Mint   | 13        | 8.33%   |
| Fedora       | 10        | 6.41%   |
| Arch         | 9         | 5.77%   |
| Manjaro      | 8         | 5.13%   |
| Kubuntu      | 6         | 3.85%   |
| ArcoLinux    | 6         | 3.85%   |
| Pop!_OS      | 5         | 3.21%   |
| OpenMandriva | 4         | 2.56%   |
| Zorin        | 3         | 1.92%   |
| Xubuntu      | 3         | 1.92%   |
| Ubuntu MATE  | 3         | 1.92%   |
| KDE neon     | 3         | 1.92%   |
| Endless      | 3         | 1.92%   |
| Elementary   | 3         | 1.92%   |
| Debian       | 3         | 1.92%   |
| SteamOS      | 2         | 1.28%   |
| Reborn OS    | 2         | 1.28%   |
| Clear Linux  | 2         | 1.28%   |
| Ubuntu Unity | 1         | 0.64%   |
| Lubuntu      | 1         | 0.64%   |
| LMDE         | 1         | 0.64%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 6         | 3.49%   |
| 5.15.0-52-generic                  | 4         | 2.33%   |
| 5.4.0-47-generic                   | 3         | 1.74%   |
| 5.4.0-28-generic                   | 3         | 1.74%   |
| 5.15.0-53-generic                  | 3         | 1.74%   |
| 5.10.14-desktop-1omv4002           | 3         | 1.74%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 1.74%   |
| 5.8.0-53-generic                   | 2         | 1.16%   |
| 5.4.0-88-generic                   | 2         | 1.16%   |
| 5.4.0-65-generic                   | 2         | 1.16%   |
| 5.15.2-arch1-1                     | 2         | 1.16%   |
| 5.15.0-56-generic                  | 2         | 1.16%   |
| 5.13.0-39-generic                  | 2         | 1.16%   |
| 5.11.0-27-generic                  | 2         | 1.16%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 1.16%   |
| 5.0.0-23-generic                   | 2         | 1.16%   |
| 4.18.0-15-generic                  | 2         | 1.16%   |
| 4.15.0-45-generic                  | 2         | 1.16%   |
| 6.0.9-arch1-1                      | 1         | 0.58%   |
| 6.0.9-300.fc37.x86_64              | 1         | 0.58%   |
| 6.0.8-1-MANJARO                    | 1         | 0.58%   |
| 6.0.5-200.fc36.x86_64              | 1         | 0.58%   |
| 6.0.2-2-MANJARO                    | 1         | 0.58%   |
| 5.9.16-1-MANJARO                   | 1         | 0.58%   |
| 5.9.13-200.fc33.x86_64             | 1         | 0.58%   |
| 5.9.10-zen1-1-zen                  | 1         | 0.58%   |
| 5.9.0-050900rc5-lowlatency         | 1         | 0.58%   |
| 5.8.6-1-MANJARO                    | 1         | 0.58%   |
| 5.8.0-7630-generic                 | 1         | 0.58%   |
| 5.8.0-63-generic                   | 1         | 0.58%   |
| 5.8.0-59-generic                   | 1         | 0.58%   |
| 5.8.0-54-generic                   | 1         | 0.58%   |
| 5.8.0-50-generic                   | 1         | 0.58%   |
| 5.8.0-45-generic                   | 1         | 0.58%   |
| 5.8.0-44-generic                   | 1         | 0.58%   |
| 5.8.0-38-generic                   | 1         | 0.58%   |
| 5.8.0-29-generic                   | 1         | 0.58%   |
| 5.8.0-14-generic                   | 1         | 0.58%   |
| 5.6.13-100.fc30.x86_64             | 1         | 0.58%   |
| 5.5.6-1-MANJARO                    | 1         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 31        | 18.67%  |
| 5.15.0  | 16        | 9.64%   |
| 4.15.0  | 13        | 7.83%   |
| 5.8.0   | 9         | 5.42%   |
| 5.13.0  | 7         | 4.22%   |
| 5.11.0  | 7         | 4.22%   |
| 5.0.0   | 7         | 4.22%   |
| 4.18.0  | 5         | 3.01%   |
| 4.9.20  | 4         | 2.41%   |
| 5.3.0   | 3         | 1.81%   |
| 5.10.14 | 3         | 1.81%   |
| 6.0.9   | 2         | 1.2%    |
| 5.17.1  | 2         | 1.2%    |
| 5.15.2  | 2         | 1.2%    |
| 5.13.13 | 2         | 1.2%    |
| 5.13.12 | 2         | 1.2%    |
| 5.11.12 | 2         | 1.2%    |
| 5.10.74 | 2         | 1.2%    |
| 6.0.8   | 1         | 0.6%    |
| 6.0.5   | 1         | 0.6%    |
| 6.0.2   | 1         | 0.6%    |
| 5.9.16  | 1         | 0.6%    |
| 5.9.13  | 1         | 0.6%    |
| 5.9.10  | 1         | 0.6%    |
| 5.9.0   | 1         | 0.6%    |
| 5.8.6   | 1         | 0.6%    |
| 5.6.13  | 1         | 0.6%    |
| 5.5.6   | 1         | 0.6%    |
| 5.4.64  | 1         | 0.6%    |
| 5.19.8  | 1         | 0.6%    |
| 5.17.6  | 1         | 0.6%    |
| 5.17.4  | 1         | 0.6%    |
| 5.16.9  | 1         | 0.6%    |
| 5.16.7  | 1         | 0.6%    |
| 5.16.5  | 1         | 0.6%    |
| 5.16.15 | 1         | 0.6%    |
| 5.15.5  | 1         | 0.6%    |
| 5.15.15 | 1         | 0.6%    |
| 5.14.21 | 1         | 0.6%    |
| 5.14.2  | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 32        | 19.28%  |
| 5.15    | 20        | 12.05%  |
| 5.13    | 15        | 9.04%   |
| 4.15    | 13        | 7.83%   |
| 5.10    | 11        | 6.63%   |
| 5.8     | 10        | 6.02%   |
| 5.11    | 10        | 6.02%   |
| 5.0     | 8         | 4.82%   |
| 4.9     | 7         | 4.22%   |
| 6.0     | 5         | 3.01%   |
| 4.18    | 5         | 3.01%   |
| 5.9     | 4         | 2.41%   |
| 5.17    | 4         | 2.41%   |
| 5.16    | 4         | 2.41%   |
| 5.3     | 3         | 1.81%   |
| 5.14    | 3         | 1.81%   |
| 5.12    | 3         | 1.81%   |
| 4.19    | 2         | 1.2%    |
| 5.6     | 1         | 0.6%    |
| 5.5     | 1         | 0.6%    |
| 5.19    | 1         | 0.6%    |
| 4.4     | 1         | 0.6%    |
| 4.10    | 1         | 0.6%    |
| 4.1     | 1         | 0.6%    |
| 3.16    | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 148       | 96.73%  |
| i686   | 5         | 3.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 54        | 34.84%  |
| Unknown    | 25        | 16.13%  |
| KDE5       | 21        | 13.55%  |
| XFCE       | 12        | 7.74%   |
| X-Cinnamon | 9         | 5.81%   |
| KDE4       | 8         | 5.16%   |
| MATE       | 7         | 4.52%   |
| Pantheon   | 3         | 1.94%   |
| KDE        | 3         | 1.94%   |
| Unity      | 2         | 1.29%   |
| LXQt       | 2         | 1.29%   |
| LXDE       | 2         | 1.29%   |
| i3         | 2         | 1.29%   |
| awesome    | 2         | 1.29%   |
| openbox    | 1         | 0.65%   |
| Cinnamon   | 1         | 0.65%   |
| Budgie     | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 119       | 77.78%  |
| Wayland | 23        | 15.03%  |
| Unknown | 10        | 6.54%   |
| Tty     | 1         | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 79        | 50.97%  |
| SDDM    | 23        | 14.84%  |
| GDM     | 19        | 12.26%  |
| GDM3    | 10        | 6.45%   |
| TDM     | 9         | 5.81%   |
| KDM     | 8         | 5.16%   |
| LightDM | 7         | 4.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 73        | 47.1%   |
| Unknown         | 32        | 20.65%  |
| et_EE           | 24        | 15.48%  |
| ru_RU           | 12        | 7.74%   |
| en_GB           | 6         | 3.87%   |
| de_DE           | 2         | 1.29%   |
| uk_UA           | 1         | 0.65%   |
| ru_UA           | 1         | 0.65%   |
| fr_FR           | 1         | 0.65%   |
| en_US.iso885915 | 1         | 0.65%   |
| en_DK           | 1         | 0.65%   |
| C               | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 84        | 53.5%   |
| EFI  | 73        | 46.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 115       | 75.16%  |
| Btrfs   | 17        | 11.11%  |
| Unknown | 12        | 7.84%   |
| Overlay | 5         | 3.27%   |
| Xfs     | 2         | 1.31%   |
| Zfs     | 1         | 0.65%   |
| Ext3    | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 86        | 55.84%  |
| GPT     | 50        | 32.47%  |
| MBR     | 18        | 11.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 142       | 92.21%  |
| Yes       | 12        | 7.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 115       | 73.72%  |
| Yes       | 41        | 26.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 45        | 29.41%  |
| Hewlett-Packard     | 30        | 19.61%  |
| Dell                | 21        | 13.73%  |
| ASUSTek Computer    | 18        | 11.76%  |
| Samsung Electronics | 7         | 4.58%   |
| Acer                | 6         | 3.92%   |
| MSI                 | 4         | 2.61%   |
| Fujitsu             | 3         | 1.96%   |
| Valve               | 2         | 1.31%   |
| Timi                | 2         | 1.31%   |
| Quanta              | 2         | 1.31%   |
| Apple               | 2         | 1.31%   |
| Alienware           | 2         | 1.31%   |
| TUXEDO              | 1         | 0.65%   |
| Toshiba             | 1         | 0.65%   |
| Notebook            | 1         | 0.65%   |
| mPTech              | 1         | 0.65%   |
| HUAWEI              | 1         | 0.65%   |
| Getac               | 1         | 0.65%   |
| Fujitsu Siemens     | 1         | 0.65%   |
| Framework           | 1         | 0.65%   |
| Chuwi               | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 2         | 1.31%   |
| Quanta TWH                                            | 2         | 1.31%   |
| Lenovo Y50-70 20378                                   | 2         | 1.31%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 1.31%   |
| HP Pavilion dv7                                       | 2         | 1.31%   |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 1.31%   |
| HP EliteBook 8470p                                    | 2         | 1.31%   |
| HP EliteBook 8460p                                    | 2         | 1.31%   |
| HP EliteBook 840 G2                                   | 2         | 1.31%   |
| Dell Inspiron N5110                                   | 2         | 1.31%   |
| Alienware 17                                          | 2         | 1.31%   |
| TUXEDO Book BA1510                                    | 1         | 0.65%   |
| Toshiba Satellite L855                                | 1         | 0.65%   |
| Timi RedmiBook 16                                     | 1         | 0.65%   |
| Timi RedmiBook 14 II                                  | 1         | 0.65%   |
| Samsung R410                                          | 1         | 0.65%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.65%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.65%   |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.65%   |
| Samsung 535U3C                                        | 1         | 0.65%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.65%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.65%   |
| Notebook W35xSS_370SS                                 | 1         | 0.65%   |
| MSI GT70 2OC/2OD                                      | 1         | 0.65%   |
| MSI GS75 Stealth 8SE                                  | 1         | 0.65%   |
| MSI GP62M 7RDX                                        | 1         | 0.65%   |
| MSI GL72 6QD                                          | 1         | 0.65%   |
| mPTech ARC 11.6 128GB HD                              | 1         | 0.65%   |
| Lenovo Y720-15IKB 80VR                                | 1         | 0.65%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.65%   |
| Lenovo V110-15ISK 80TL                                | 1         | 0.65%   |
| Lenovo ThinkPad X260 20F5S84400                       | 1         | 0.65%   |
| Lenovo ThinkPad X240 20AMA0W706                       | 1         | 0.65%   |
| Lenovo ThinkPad X220 4291R30                          | 1         | 0.65%   |
| Lenovo ThinkPad X220 429136G                          | 1         | 0.65%   |
| Lenovo ThinkPad X201 3680CG7                          | 1         | 0.65%   |
| Lenovo ThinkPad X13 Gen 1 20UF0020MX                  | 1         | 0.65%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW005PMX            | 1         | 0.65%   |
| Lenovo ThinkPad W541 20EF001TMS                       | 1         | 0.65%   |
| Lenovo ThinkPad T61 76641FG                           | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 33        | 21.57%  |
| HP EliteBook       | 12        | 7.84%   |
| HP Pavilion        | 7         | 4.58%   |
| Dell Inspiron      | 6         | 3.92%   |
| Dell Latitude      | 5         | 3.27%   |
| Dell Precision     | 4         | 2.61%   |
| Acer Aspire        | 4         | 2.61%   |
| Lenovo IdeaPad     | 3         | 1.96%   |
| Fujitsu LIFEBOOK   | 3         | 1.96%   |
| Dell XPS           | 3         | 1.96%   |
| ASUS VivoBook      | 3         | 1.96%   |
| Valve Jupiter      | 2         | 1.31%   |
| Timi RedmiBook     | 2         | 1.31%   |
| Samsung 900X3C     | 2         | 1.31%   |
| Quanta TWH         | 2         | 1.31%   |
| Lenovo Y50-70      | 2         | 1.31%   |
| Lenovo Legion      | 2         | 1.31%   |
| HP Presario        | 2         | 1.31%   |
| HP OMEN            | 2         | 1.31%   |
| HP ENVY            | 2         | 1.31%   |
| HP Compaq          | 2         | 1.31%   |
| ASUS ZenBook       | 2         | 1.31%   |
| Alienware 17       | 2         | 1.31%   |
| TUXEDO Book        | 1         | 0.65%   |
| Toshiba Satellite  | 1         | 0.65%   |
| Samsung R410       | 1         | 0.65%   |
| Samsung 770Z5E     | 1         | 0.65%   |
| Samsung 535U3C     | 1         | 0.65%   |
| Samsung 300E5EV    | 1         | 0.65%   |
| Samsung 275E4E     | 1         | 0.65%   |
| Notebook W35xSS    | 1         | 0.65%   |
| MSI GT70           | 1         | 0.65%   |
| MSI GS75           | 1         | 0.65%   |
| MSI GP62M          | 1         | 0.65%   |
| MSI GL72           | 1         | 0.65%   |
| mPTech ARC         | 1         | 0.65%   |
| Lenovo Y720-15IKB  | 1         | 0.65%   |
| Lenovo Y520-15IKBN | 1         | 0.65%   |
| Lenovo V110-15ISK  | 1         | 0.65%   |
| Lenovo IdeaPadFlex | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 17        | 11.11%  |
| 2013 | 17        | 11.11%  |
| 2011 | 16        | 10.46%  |
| 2018 | 14        | 9.15%   |
| 2019 | 13        | 8.5%    |
| 2014 | 12        | 7.84%   |
| 2015 | 10        | 6.54%   |
| 2017 | 9         | 5.88%   |
| 2012 | 9         | 5.88%   |
| 2008 | 7         | 4.58%   |
| 2007 | 7         | 4.58%   |
| 2010 | 6         | 3.92%   |
| 2021 | 5         | 3.27%   |
| 2016 | 5         | 3.27%   |
| 2022 | 3         | 1.96%   |
| 2009 | 2         | 1.31%   |
| 2006 | 1         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 153       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 139       | 90.26%  |
| Enabled  | 15        | 9.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 153       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 39        | 25.16%  |
| 4.01-8.0    | 35        | 22.58%  |
| 3.01-4.0    | 29        | 18.71%  |
| 16.01-24.0  | 25        | 16.13%  |
| 32.01-64.0  | 8         | 5.16%   |
| 2.01-3.0    | 7         | 4.52%   |
| 24.01-32.0  | 6         | 3.87%   |
| 1.01-2.0    | 5         | 3.23%   |
| 64.01-256.0 | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 60        | 36.81%  |
| 2.01-3.0   | 38        | 23.31%  |
| 4.01-8.0   | 30        | 18.4%   |
| 3.01-4.0   | 16        | 9.82%   |
| 8.01-16.0  | 9         | 5.52%   |
| 0.51-1.0   | 9         | 5.52%   |
| 24.01-32.0 | 1         | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 118       | 75.64%  |
| 2      | 31        | 19.87%  |
| 3      | 5         | 3.21%   |
| 5      | 1         | 0.64%   |
| 4      | 1         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 63.46%  |
| Yes       | 57        | 36.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 85.06%  |
| No        | 23        | 14.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 77.27%  |
| No        | 35        | 22.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Estonia | 153       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Tallinn           | 99        | 63.87%  |
| Tartu             | 15        | 9.68%   |
| Pärnu            | 7         | 4.52%   |
| Rapla             | 4         | 2.58%   |
| Narva             | 4         | 2.58%   |
| Rakvere           | 3         | 1.94%   |
| Vinni             | 2         | 1.29%   |
| Saku              | 2         | 1.29%   |
| Otepaeae          | 2         | 1.29%   |
| Maardu            | 2         | 1.29%   |
| Keila             | 2         | 1.29%   |
| Viljandi          | 1         | 0.65%   |
| Vatla             | 1         | 0.65%   |
| Tabasalu          | 1         | 0.65%   |
| Sauga             | 1         | 0.65%   |
| Rae Parish        | 1         | 0.65%   |
| Põlva            | 1         | 0.65%   |
| Pohja-Sakala vald | 1         | 0.65%   |
| Laagri            | 1         | 0.65%   |
| Kärdla           | 1         | 0.65%   |
| Kaeina            | 1         | 0.65%   |
| Jõhvi            | 1         | 0.65%   |
| Jõgeva           | 1         | 0.65%   |
| AEaesmaee         | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 39        | 46     | 20.42%  |
| Seagate                     | 28        | 31     | 14.66%  |
| Toshiba                     | 16        | 16     | 8.38%   |
| SK hynix                    | 13        | 17     | 6.81%   |
| Kingston                    | 13        | 14     | 6.81%   |
| WDC                         | 11        | 13     | 5.76%   |
| Intel                       | 7         | 8      | 3.66%   |
| HGST                        | 7         | 8      | 3.66%   |
| Unknown                     | 6         | 6      | 3.14%   |
| SanDisk                     | 6         | 8      | 3.14%   |
| Hitachi                     | 5         | 5      | 2.62%   |
| Micron Technology           | 3         | 3      | 1.57%   |
| Crucial                     | 3         | 3      | 1.57%   |
| A-DATA Technology           | 3         | 3      | 1.57%   |
| Transcend                   | 2         | 5      | 1.05%   |
| Patriot                     | 2         | 2      | 1.05%   |
| LITEONIT                    | 2         | 2      | 1.05%   |
| Lenovo                      | 2         | 2      | 1.05%   |
| KingSpec                    | 2         | 3      | 1.05%   |
| Gigabyte Technology         | 2         | 3      | 1.05%   |
| Fujitsu                     | 2         | 2      | 1.05%   |
| China                       | 2         | 2      | 1.05%   |
| Apacer                      | 2         | 2      | 1.05%   |
| SPCC                        | 1         | 1      | 0.52%   |
| PNY                         | 1         | 1      | 0.52%   |
| Phison Electronics          | 1         | 1      | 0.52%   |
| Phison                      | 1         | 1      | 0.52%   |
| Lexar                       | 1         | 1      | 0.52%   |
| KIOXIA                      | 1         | 2      | 0.52%   |
| Kingston Technology Company | 1         | 1      | 0.52%   |
| Intenso                     | 1         | 1      | 0.52%   |
| HUAWEI                      | 1         | 1      | 0.52%   |
| ASMT109x                    | 1         | 2      | 0.52%   |
| Apple                       | 1         | 1      | 0.52%   |
| ADATA Technology            | 1         | 1      | 0.52%   |
| Unknown                     | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST500LM021-1KJ152 500GB                    | 3         | 1.53%   |
| HGST HTS721010A9E630 1TB                           | 3         | 1.53%   |
| Unknown MMC Card  16GB                             | 2         | 1.02%   |
| Toshiba NVMe SSD Drive 512GB                       | 2         | 1.02%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 1.02%   |
| SK hynix NVMe SSD Drive 512GB                      | 2         | 1.02%   |
| SK hynix NVMe SSD Drive 256GB                      | 2         | 1.02%   |
| Seagate ST500LT012-1DG142 500GB                    | 2         | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 1.02%   |
| Seagate BUP Portable 4TB                           | 2         | 1.02%   |
| SanDisk SD8SBAT256G1122 256GB SSD                  | 2         | 1.02%   |
| Samsung SSD 970 EVO Plus 1TB                       | 2         | 1.02%   |
| Samsung SSD 850 EVO M.2 500GB                      | 2         | 1.02%   |
| Samsung SSD 850 EVO 500GB                          | 2         | 1.02%   |
| Samsung NVMe SSD Drive 512GB                       | 2         | 1.02%   |
| Samsung NVMe SSD Drive 1TB                         | 2         | 1.02%   |
| Samsung NVMe SSD Drive 1024GB                      | 2         | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2         | 1.02%   |
| Samsung MZVLB512HBJQ-000L7 512GB                   | 2         | 1.02%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD               | 2         | 1.02%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                | 2         | 1.02%   |
| Kingston SV300S37A120G 120GB SSD                   | 2         | 1.02%   |
| Kingston SA400S37960G 960GB SSD                    | 2         | 1.02%   |
| Intel SSDPEKKF256G8L 256GB                         | 2         | 1.02%   |
| HGST HTS541010A9E680 1TB                           | 2         | 1.02%   |
| WDC WDS500G2B0B 500GB SSD                          | 1         | 0.51%   |
| WDC WDS500G1X0E-00AFY0 500GB                       | 1         | 0.51%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                   | 1         | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.51%   |
| WDC WD5000LPVX-22V0TT0 500GB                       | 1         | 0.51%   |
| WDC WD5000LPCX-24VHAT0 500GB                       | 1         | 0.51%   |
| WDC WD2500BEVT-80A23T0 250GB                       | 1         | 0.51%   |
| WDC WD1200BEVS-08RST2 120GB                        | 1         | 0.51%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 0.51%   |
| WDC PC SN730 NVMe 512GB                            | 1         | 0.51%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB               | 1         | 0.51%   |
| Unknown MMC128  128GB                              | 1         | 0.51%   |
| Unknown MMC Card  7GB                              | 1         | 0.51%   |
| Unknown MMC Card  512GB                            | 1         | 0.51%   |
| Unknown MMC Card  128GB                            | 1         | 0.51%   |

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
| Samsung Electronics | 22        | 25     | 29.33%  |
| Kingston            | 11        | 12     | 14.67%  |
| SanDisk             | 5         | 7      | 6.67%   |
| SK hynix            | 4         | 4      | 5.33%   |
| WDC                 | 3         | 4      | 4%      |
| Micron Technology   | 3         | 3      | 4%      |
| Crucial             | 3         | 3      | 4%      |
| A-DATA Technology   | 3         | 3      | 4%      |
| Transcend           | 2         | 5      | 2.67%   |
| Toshiba             | 2         | 2      | 2.67%   |
| Patriot             | 2         | 2      | 2.67%   |
| LITEONIT            | 2         | 2      | 2.67%   |
| KingSpec            | 2         | 3      | 2.67%   |
| Intel               | 2         | 3      | 2.67%   |
| China               | 2         | 2      | 2.67%   |
| Apacer              | 2         | 2      | 2.67%   |
| SPCC                | 1         | 1      | 1.33%   |
| Lexar               | 1         | 1      | 1.33%   |
| Intenso             | 1         | 1      | 1.33%   |
| Gigabyte Technology | 1         | 2      | 1.33%   |
| Apple               | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 65        | 88     | 37.36%  |
| HDD     | 51        | 58     | 29.31%  |
| NVMe    | 48        | 62     | 27.59%  |
| MMC     | 7         | 7      | 4.02%   |
| Unknown | 3         | 4      | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 106       | 142    | 62.72%  |
| NVMe | 48        | 62     | 28.4%   |
| SAS  | 8         | 8      | 4.73%   |
| MMC  | 7         | 7      | 4.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 85        | 104    | 70.25%  |
| 0.51-1.0   | 30        | 33     | 24.79%  |
| 1.01-2.0   | 4         | 7      | 3.31%   |
| 3.01-4.0   | 2         | 2      | 1.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 56        | 35.44%  |
| 251-500        | 33        | 20.89%  |
| 501-1000       | 22        | 13.92%  |
| 1-20           | 13        | 8.23%   |
| 51-100         | 10        | 6.33%   |
| 1001-2000      | 8         | 5.06%   |
| More than 3000 | 5         | 3.16%   |
| 21-50          | 5         | 3.16%   |
| Unknown        | 5         | 3.16%   |
| 2001-3000      | 1         | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 68        | 41.72%  |
| 21-50          | 25        | 15.34%  |
| 101-250        | 22        | 13.5%   |
| 51-100         | 21        | 12.88%  |
| 251-500        | 11        | 6.75%   |
| 501-1000       | 7         | 4.29%   |
| Unknown        | 5         | 3.07%   |
| More than 3000 | 2         | 1.23%   |
| 2001-3000      | 1         | 0.61%   |
| 1001-2000      | 1         | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 7.14%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 7.14%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 7.14%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 7.14%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 7.14%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 7.14%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 7.14%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 7.14%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 7.14%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 7.14%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 7.14%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 7.14%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 7         | 7      | 50%     |
| WDC               | 1         | 1      | 7.14%   |
| Micron Technology | 1         | 1      | 7.14%   |
| Kingston          | 1         | 1      | 7.14%   |
| Hitachi           | 1         | 1      | 7.14%   |
| HGST              | 1         | 1      | 7.14%   |
| Fujitsu           | 1         | 1      | 7.14%   |
| Crucial           | 1         | 1      | 7.14%   |

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
| HDD  | 11        | 11     | 78.57%  |
| SSD  | 3         | 3      | 21.43%  |

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
| Detected | 95        | 144    | 59.75%  |
| Works    | 51        | 61     | 32.08%  |
| Malfunc  | 13        | 14     | 8.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 113       | 62.43%  |
| Samsung Electronics          | 18        | 9.94%   |
| AMD                          | 18        | 9.94%   |
| SK hynix                     | 9         | 4.97%   |
| Toshiba America Info Systems | 5         | 2.76%   |
| SanDisk                      | 5         | 2.76%   |
| Phison Electronics           | 3         | 1.66%   |
| Kingston Technology Company  | 3         | 1.66%   |
| Lenovo                       | 2         | 1.1%    |
| KIOXIA                       | 2         | 1.1%    |
| VIA Technologies             | 1         | 0.55%   |
| Marvell Technology Group     | 1         | 0.55%   |
| ADATA Technology             | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 7.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 6.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 6.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 6.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 5.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 4.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 4.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 3.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 3.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 3.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 2.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 2.03%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.52%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 3         | 1.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.52%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 1.02%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 1.02%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.02%   |
| Lenovo Non-Volatile memory controller                                          | 2         | 1.02%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.02%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.02%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.02%   |
| Intel SSD 660P Series                                                          | 2         | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.02%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 2         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 1.02%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.51%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 0.51%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.51%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 0.51%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 119       | 62.96%  |
| NVMe | 49        | 25.93%  |
| IDE  | 14        | 7.41%   |
| RAID | 7         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 127       | 83.01%  |
| AMD    | 26        | 16.99%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 3.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.61%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.96%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.31%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.31%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 1.31%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 1.31%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 2         | 1.31%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.31%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.31%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.31%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.31%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.31%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 1.31%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.31%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.31%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.31%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 1.31%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.31%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.31%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.31%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 2         | 1.31%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.31%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.31%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.31%   |
| AMD Custom APU 0405                           | 2         | 1.31%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.65%   |
| Intel Pentium M processor 2.13GHz             | 1         | 0.65%   |
| Intel Pentium M processor 1.50GHz             | 1         | 0.65%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.65%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.65%   |
| Intel Pentium CPU 2127U @ 1.90GHz             | 1         | 0.65%   |
| Intel Pentium 3805U @ 1.90GHz                 | 1         | 0.65%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.65%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.65%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 45        | 29.41%  |
| Intel Core i5                  | 42        | 27.45%  |
| Intel Celeron                  | 8         | 5.23%   |
| Other                          | 7         | 4.58%   |
| Intel Core i3                  | 7         | 4.58%   |
| Intel Core 2 Duo               | 7         | 4.58%   |
| AMD Ryzen 5                    | 7         | 4.58%   |
| AMD Ryzen 7                    | 4         | 2.61%   |
| Intel Pentium                  | 3         | 1.96%   |
| Intel Pentium M                | 2         | 1.31%   |
| Intel Celeron Dual-Core        | 2         | 1.31%   |
| AMD Ryzen 7 PRO                | 2         | 1.31%   |
| Intel Pentium Silver           | 1         | 0.65%   |
| Intel Pentium Dual             | 1         | 0.65%   |
| Intel Core i9                  | 1         | 0.65%   |
| Intel Core 2                   | 1         | 0.65%   |
| Intel Celeron M                | 1         | 0.65%   |
| Intel Atom                     | 1         | 0.65%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.65%   |
| AMD Ryzen 5 PRO                | 1         | 0.65%   |
| AMD Ryzen 3 PRO                | 1         | 0.65%   |
| AMD E2                         | 1         | 0.65%   |
| AMD E                          | 1         | 0.65%   |
| AMD C-60                       | 1         | 0.65%   |
| AMD Athlon II Dual-Core        | 1         | 0.65%   |
| AMD Athlon 64 X2               | 1         | 0.65%   |
| AMD A8                         | 1         | 0.65%   |
| AMD A6                         | 1         | 0.65%   |
| AMD A4                         | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 76        | 49.67%  |
| 4       | 52        | 33.99%  |
| 6       | 13        | 8.5%    |
| 8       | 5         | 3.27%   |
| 1       | 5         | 3.27%   |
| Unknown | 2         | 1.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 153       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 113       | 73.38%  |
| 1       | 39        | 25.32%  |
| Unknown | 2         | 1.3%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 150       | 98.04%  |
| 32-bit         | 2         | 1.31%   |
| Unknown        | 1         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 21.66%  |
| 0x306a9    | 12        | 7.64%   |
| 0x206a7    | 12        | 7.64%   |
| 0x306c3    | 10        | 6.37%   |
| 0x806ea    | 7         | 4.46%   |
| 0x40651    | 7         | 4.46%   |
| 0x306d4    | 6         | 3.82%   |
| 0x906e9    | 5         | 3.18%   |
| 0x08600106 | 5         | 3.18%   |
| 0x806ec    | 4         | 2.55%   |
| 0x806c1    | 4         | 2.55%   |
| 0x6fb      | 4         | 2.55%   |
| 0xa0652    | 3         | 1.91%   |
| 0x906ea    | 3         | 1.91%   |
| 0x6fd      | 3         | 1.91%   |
| 0x506e3    | 3         | 1.91%   |
| 0x406e3    | 3         | 1.91%   |
| 0x20655    | 3         | 1.91%   |
| 0x1067a    | 3         | 1.91%   |
| 0x05000119 | 3         | 1.91%   |
| 0x806e9    | 2         | 1.27%   |
| 0x706a1    | 2         | 1.27%   |
| 0x6d8      | 2         | 1.27%   |
| 0x30678    | 2         | 1.27%   |
| 0x08108102 | 2         | 1.27%   |
| 0x906ed    | 1         | 0.64%   |
| 0x806eb    | 1         | 0.64%   |
| 0x706a8    | 1         | 0.64%   |
| 0x6fa      | 1         | 0.64%   |
| 0x6f6      | 1         | 0.64%   |
| 0x30661    | 1         | 0.64%   |
| 0x0a50000c | 1         | 0.64%   |
| 0x0a404102 | 1         | 0.64%   |
| 0x08600103 | 1         | 0.64%   |
| 0x0810100b | 1         | 0.64%   |
| 0x06001119 | 1         | 0.64%   |
| 0x02000032 | 1         | 0.64%   |
| 0x01000098 | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 29        | 18.95%  |
| Haswell         | 21        | 13.73%  |
| SandyBridge     | 14        | 9.15%   |
| IvyBridge       | 14        | 9.15%   |
| Core            | 9         | 5.88%   |
| Zen 2           | 8         | 5.23%   |
| Skylake         | 7         | 4.58%   |
| Broadwell       | 7         | 4.58%   |
| Westmere        | 5         | 3.27%   |
| TigerLake       | 5         | 3.27%   |
| Unknown         | 5         | 3.27%   |
| Penryn          | 3         | 1.96%   |
| Goldmont plus   | 3         | 1.96%   |
| CometLake       | 3         | 1.96%   |
| Bobcat          | 3         | 1.96%   |
| Zen+            | 2         | 1.31%   |
| Zen             | 2         | 1.31%   |
| Silvermont      | 2         | 1.31%   |
| P6              | 2         | 1.31%   |
| Zen 3           | 1         | 0.65%   |
| Steamroller     | 1         | 0.65%   |
| Piledriver      | 1         | 0.65%   |
| K8 Hammer       | 1         | 0.65%   |
| K8 & K10 hybrid | 1         | 0.65%   |
| K10             | 1         | 0.65%   |
| Goldmont        | 1         | 0.65%   |
| Excavator       | 1         | 0.65%   |
| Bonnell         | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 118       | 56.73%  |
| Nvidia           | 56        | 26.92%  |
| AMD              | 33        | 15.87%  |
| VIA Technologies | 1         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 13        | 6.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 6.05%   |
| Intel UHD Graphics 620                                                        | 10        | 4.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 4.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 9         | 4.19%   |
| AMD Renoir                                                                    | 8         | 3.72%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 2.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 5         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 5         | 2.33%   |
| Intel HD Graphics 630                                                         | 5         | 2.33%   |
| Intel HD Graphics 5500                                                        | 5         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                           | 5         | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 2.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 4         | 1.86%   |
| Intel HD Graphics 530                                                         | 4         | 1.86%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 1.4%    |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 1.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 1.4%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.93%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 2         | 0.93%   |
| Nvidia GP108GLM [Quadro P520]                                                 | 2         | 0.93%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 2         | 0.93%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 2         | 0.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 0.93%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 0.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 0.93%   |
| Intel HD Graphics 620                                                         | 2         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 0.93%   |
| AMD VanGogh [AMD Custom GPU 0405]                                             | 2         | 0.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 0.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 0.93%   |
| VIA Technologies K8M890CE/K8N890CE [Chrome 9]                                 | 1         | 0.47%   |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 0.47%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 66        | 43.14%  |
| Intel + Nvidia | 47        | 30.72%  |
| 1 x AMD        | 24        | 15.69%  |
| 1 x Nvidia     | 6         | 3.92%   |
| Intel + AMD    | 5         | 3.27%   |
| AMD + Nvidia   | 3         | 1.96%   |
| 2 x AMD        | 1         | 0.65%   |
| 1 x VIA        | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 119       | 76.28%  |
| Proprietary | 35        | 22.44%  |
| Unknown     | 2         | 1.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 53.25%  |
| 1.01-2.0   | 33        | 21.43%  |
| 0.01-0.5   | 16        | 10.39%  |
| 3.01-4.0   | 11        | 7.14%   |
| 0.51-1.0   | 7         | 4.55%   |
| 5.01-6.0   | 3         | 1.95%   |
| 2.01-3.0   | 1         | 0.65%   |
| 8.01-16.0  | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 29        | 15.59%  |
| AU Optronics            | 29        | 15.59%  |
| LG Display              | 21        | 11.29%  |
| BOE                     | 21        | 11.29%  |
| Dell                    | 17        | 9.14%   |
| Samsung Electronics     | 16        | 8.6%    |
| Chi Mei Optoelectronics | 10        | 5.38%   |
| Sharp                   | 6         | 3.23%   |
| Lenovo                  | 5         | 2.69%   |
| Goldstar                | 4         | 2.15%   |
| Sony                    | 3         | 1.61%   |
| LG Philips              | 3         | 1.61%   |
| Hewlett-Packard         | 3         | 1.61%   |
| PANDA                   | 2         | 1.08%   |
| Apple                   | 2         | 1.08%   |
| ViewSonic               | 1         | 0.54%   |
| Toshiba                 | 1         | 0.54%   |
| Seiko/Epson             | 1         | 0.54%   |
| Philips                 | 1         | 0.54%   |
| Lenovo Group Limited    | 1         | 0.54%   |
| KDB                     | 1         | 0.54%   |
| InfoVision              | 1         | 0.54%   |
| CSO                     | 1         | 0.54%   |
| CPT                     | 1         | 0.54%   |
| ASUSTek Computer        | 1         | 0.54%   |
| AOC                     | 1         | 0.54%   |
| ANX                     | 1         | 0.54%   |
| Ancor Communications    | 1         | 0.54%   |
| Analogix                | 1         | 0.54%   |
| Acer                    | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 1.55%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 3         | 1.55%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 1.55%   |
| Sony TV SNYDB01 1920x1080 1600x900mm 72.3-inch                            | 2         | 1.04%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 1.04%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 1.04%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 1.04%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 2         | 1.04%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 1.04%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 1.04%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 1.04%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 1.04%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 1.04%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.04%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 1.04%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 1.04%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 1.04%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 2         | 1.04%   |
| ViewSonic VP2030 SERIES VSC131C 1600x1200 408x306mm 20.1-inch             | 1         | 0.52%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                     | 1         | 0.52%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.52%   |
| Sharp LQ133M1JW40 SHP10CD 1920x1080 294x165mm 13.3-inch                   | 1         | 0.52%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 0.52%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 1         | 0.52%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                   | 1         | 0.52%   |
| Seiko/Epson LCD Monitor 1920x1080                                         | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch      | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM030E 1680x1050 474x296mm 22.0-inch      | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch      | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch      | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch      | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 74        | 42.29%  |
| 1366x768 (WXGA)    | 42        | 24%     |
| 1600x900 (HD+)     | 12        | 6.86%   |
| 1280x800 (WXGA)    | 10        | 5.71%   |
| 3840x2160 (4K)     | 8         | 4.57%   |
| 1920x1200 (WUXGA)  | 6         | 3.43%   |
| 2560x1600          | 4         | 2.29%   |
| 2560x1440 (QHD)    | 4         | 2.29%   |
| 1680x1050 (WSXGA+) | 4         | 2.29%   |
| 1280x1024 (SXGA)   | 3         | 1.71%   |
| 800x1280           | 2         | 1.14%   |
| 3440x1440          | 2         | 1.14%   |
| 2560x1080          | 1         | 0.57%   |
| 2256x1504          | 1         | 0.57%   |
| 1600x1200          | 1         | 0.57%   |
| 1440x900 (WXGA+)   | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 72        | 38.3%   |
| 14      | 26        | 13.83%  |
| 13      | 21        | 11.17%  |
| 17      | 13        | 6.91%   |
| 24      | 10        | 5.32%   |
| 12      | 8         | 4.26%   |
| 27      | 6         | 3.19%   |
| 23      | 4         | 2.13%   |
| Unknown | 4         | 2.13%   |
| 72      | 3         | 1.6%    |
| 34      | 3         | 1.6%    |
| 22      | 3         | 1.6%    |
| 16      | 3         | 1.6%    |
| 65      | 1         | 0.53%   |
| 43      | 1         | 0.53%   |
| 40      | 1         | 0.53%   |
| 38      | 1         | 0.53%   |
| 31      | 1         | 0.53%   |
| 29      | 1         | 0.53%   |
| 26      | 1         | 0.53%   |
| 21      | 1         | 0.53%   |
| 20      | 1         | 0.53%   |
| 19      | 1         | 0.53%   |
| 11      | 1         | 0.53%   |
| 10      | 1         | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 106       | 56.99%  |
| 201-300     | 23        | 12.37%  |
| 501-600     | 20        | 10.75%  |
| 351-400     | 15        | 8.06%   |
| 401-500     | 5         | 2.69%   |
| Unknown     | 4         | 2.15%   |
| 701-800     | 3         | 1.61%   |
| 601-700     | 3         | 1.61%   |
| 1501-2000   | 3         | 1.61%   |
| 801-900     | 2         | 1.08%   |
| 1001-1500   | 1         | 0.54%   |
| 901-1000    | 1         | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 129       | 77.71%  |
| 16/10   | 24        | 14.46%  |
| 21/9    | 3         | 1.81%   |
| 5/4     | 2         | 1.2%    |
| 4/3     | 2         | 1.2%    |
| 3/2     | 2         | 1.2%    |
| 0.62    | 2         | 1.2%    |
| Unknown | 2         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 72        | 38.5%   |
| 81-90          | 36        | 19.25%  |
| 201-250        | 14        | 7.49%   |
| 71-80          | 11        | 5.88%   |
| 121-130        | 11        | 5.88%   |
| 61-70          | 8         | 4.28%   |
| 301-350        | 7         | 3.74%   |
| 351-500        | 5         | 2.67%   |
| More than 1000 | 4         | 2.14%   |
| Unknown        | 4         | 2.14%   |
| 251-300        | 3         | 1.6%    |
| 111-120        | 3         | 1.6%    |
| 501-1000       | 3         | 1.6%    |
| 151-200        | 2         | 1.07%   |
| 51-60          | 1         | 0.53%   |
| 41-50          | 1         | 0.53%   |
| 141-150        | 1         | 0.53%   |
| 131-140        | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 75        | 40.76%  |
| 101-120       | 47        | 25.54%  |
| 51-100        | 34        | 18.48%  |
| 161-240       | 16        | 8.7%    |
| More than 240 | 4         | 2.17%   |
| 1-50          | 4         | 2.17%   |
| Unknown       | 4         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 118       | 75.16%  |
| 2     | 31        | 19.75%  |
| 3     | 7         | 4.46%   |
| 0     | 1         | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 93        | 37.65%  |
| Realtek Semiconductor             | 70        | 28.34%  |
| Qualcomm Atheros                  | 36        | 14.57%  |
| Broadcom                          | 12        | 4.86%   |
| Ralink                            | 4         | 1.62%   |
| Lenovo                            | 4         | 1.62%   |
| Ericsson Business Mobile Networks | 4         | 1.62%   |
| TP-Link                           | 3         | 1.21%   |
| Fibocom                           | 3         | 1.21%   |
| Sierra Wireless                   | 2         | 0.81%   |
| MediaTek                          | 2         | 0.81%   |
| Huawei Technologies               | 2         | 0.81%   |
| Hewlett-Packard                   | 2         | 0.81%   |
| Broadcom Limited                  | 2         | 0.81%   |
| ASIX Electronics                  | 2         | 0.81%   |
| VIA Technologies                  | 1         | 0.4%    |
| Van Ooijen Technische Informatica | 1         | 0.4%    |
| Marvell Technology Group          | 1         | 0.4%    |
| JMicron Technology                | 1         | 0.4%    |
| DisplayLink                       | 1         | 0.4%    |
| ASUSTek Computer                  | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 10.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 5.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 3.55%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.9%    |
| Intel Wireless 7260                                               | 9         | 2.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.58%   |
| Intel Wireless 7265                                               | 7         | 2.26%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 1.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.29%   |
| Intel Wireless 8260                                               | 4         | 1.29%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.29%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.29%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.97%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.97%   |
| Intel Wireless 3160                                               | 3         | 0.97%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.97%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.97%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.97%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 3         | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.65%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 91        | 56.17%  |
| Qualcomm Atheros      | 26        | 16.05%  |
| Realtek Semiconductor | 20        | 12.35%  |
| Broadcom              | 9         | 5.56%   |
| Ralink                | 4         | 2.47%   |
| Fibocom               | 3         | 1.85%   |
| TP-Link               | 2         | 1.23%   |
| Sierra Wireless       | 2         | 1.23%   |
| MediaTek              | 2         | 1.23%   |
| Broadcom Limited      | 2         | 1.23%   |
| Hewlett-Packard       | 1         | 0.62%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 6.79%   |
| Intel Wireless 8265 / 8275                                              | 9         | 5.56%   |
| Intel Wireless 7260                                                     | 9         | 5.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.94%   |
| Intel Wireless 7265                                                     | 7         | 4.32%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 4.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 3.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.47%   |
| Intel Wireless 8260                                                     | 4         | 2.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.85%   |
| Intel Wireless 3160                                                     | 3         | 1.85%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.85%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.85%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 1.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.23%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.23%   |
| Intel Wireless 3165                                                     | 2         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.23%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.23%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.23%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.23%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.62%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.62%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.62%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 59        | 43.07%  |
| Intel                    | 45        | 32.85%  |
| Qualcomm Atheros         | 17        | 12.41%  |
| Broadcom                 | 5         | 3.65%   |
| Lenovo                   | 3         | 2.19%   |
| ASIX Electronics         | 2         | 1.46%   |
| VIA Technologies         | 1         | 0.73%   |
| TP-Link                  | 1         | 0.73%   |
| Marvell Technology Group | 1         | 0.73%   |
| JMicron Technology       | 1         | 0.73%   |
| DisplayLink              | 1         | 0.73%   |
| ASUSTek Computer         | 1         | 0.73%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 24.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 12.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 6.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 4.38%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 3.65%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.92%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 2.92%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 2.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 2.19%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 2.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2.19%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2.19%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.19%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.46%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 1.46%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.46%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.46%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.73%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.73%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.73%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.73%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.73%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.73%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.73%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.73%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.73%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.73%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.73%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.73%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.73%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.73%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 153       | 51.86%  |
| Ethernet | 131       | 44.41%  |
| Modem    | 11        | 3.73%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 127       | 77.91%  |
| Ethernet | 36        | 22.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 121       | 79.08%  |
| 1     | 29        | 18.95%  |
| 0     | 2         | 1.31%   |
| 3     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 136       | 87.18%  |
| Yes  | 20        | 12.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 52.1%   |
| Broadcom                        | 11        | 9.24%   |
| Qualcomm Atheros Communications | 10        | 8.4%    |
| IMC Networks                    | 9         | 7.56%   |
| Realtek Semiconductor           | 8         | 6.72%   |
| Hewlett-Packard                 | 4         | 3.36%   |
| Realtek                         | 3         | 2.52%   |
| Cambridge Silicon Radio         | 3         | 2.52%   |
| Foxconn / Hon Hai               | 2         | 1.68%   |
| Apple                           | 2         | 1.68%   |
| Toshiba                         | 1         | 0.84%   |
| Ralink                          | 1         | 0.84%   |
| Lite-On Technology              | 1         | 0.84%   |
| Dell                            | 1         | 0.84%   |
| Askey Computer                  | 1         | 0.84%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 33        | 27.73%  |
| Intel AX201 Bluetooth                               | 9         | 7.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 5.04%   |
| Intel AX200 Bluetooth                               | 6         | 5.04%   |
| Realtek Bluetooth Radio                             | 5         | 4.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 4.2%    |
| IMC Networks Bluetooth Device                       | 5         | 4.2%    |
| Realtek Bluetooth Radio                             | 3         | 2.52%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 2.52%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.52%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 2.52%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.68%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.68%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.68%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.68%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.68%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.68%   |
| Apple Bluetooth Host Controller                     | 2         | 1.68%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.84%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.84%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.84%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.84%   |
| Lite-On Bluetooth Device                            | 1         | 0.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.84%   |
| Intel AX210 Bluetooth                               | 1         | 0.84%   |
| IMC Networks BCM20702A0                             | 1         | 0.84%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.84%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.84%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.84%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.84%   |
| Askey Bluetooth Device                              | 1         | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 126       | 67.38%  |
| AMD                   | 29        | 15.51%  |
| Nvidia                | 17        | 9.09%   |
| Lenovo                | 4         | 2.14%   |
| Realtek Semiconductor | 2         | 1.07%   |
| VIA Technologies      | 1         | 0.53%   |
| Texas Instruments     | 1         | 0.53%   |
| TerraTec Electronic   | 1         | 0.53%   |
| Roland                | 1         | 0.53%   |
| Micronas              | 1         | 0.53%   |
| Mark of the Unicorn   | 1         | 0.53%   |
| Logitech              | 1         | 0.53%   |
| JMTek                 | 1         | 0.53%   |
| C-Media Electronics   | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 6.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14        | 6.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 6.11%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 6.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 5.24%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 3.93%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 3.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 3.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 3.06%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 3.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 2.62%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 2.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.18%   |
| Intel CM238 HD Audio Controller                                            | 5         | 2.18%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.75%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.31%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.31%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.31%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 1.31%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.87%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.87%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 2         | 0.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.87%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 0.87%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.87%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.44%   |
| Texas Instruments SMSL AD18 AMP                                            | 1         | 0.44%   |
| TerraTec Electronic Aureon Dual USB                                        | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 30.21%  |
| SK hynix            | 22        | 22.92%  |
| Micron Technology   | 15        | 15.63%  |
| Kingston            | 9         | 9.38%   |
| Crucial             | 5         | 5.21%   |
| Ramaxel Technology  | 3         | 3.13%   |
| Unknown (ABCD)      | 2         | 2.08%   |
| Unknown             | 2         | 2.08%   |
| ASint Technology    | 2         | 2.08%   |
| A-DATA Technology   | 2         | 2.08%   |
| Unifosa             | 1         | 1.04%   |
| Qimonda             | 1         | 1.04%   |
| Nanya Technology    | 1         | 1.04%   |
| G.Skill             | 1         | 1.04%   |
| Elpida              | 1         | 1.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 4         | 3.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s             | 2         | 1.92%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                        | 2         | 1.92%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 2         | 1.92%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s                     | 2         | 1.92%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                        | 2         | 1.92%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                       | 2         | 1.92%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s                        | 2         | 1.92%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s                        | 2         | 1.92%   |
| Unknown RAM Module 512MB SODIMM DDR2                                         | 1         | 0.96%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                                | 1         | 0.96%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                        | 1         | 0.96%   |
| Unifosa RAM GU332G0AJEPR8H2L.. 2GB SODIMM DDR2 667MT/s                       | 1         | 0.96%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                              | 1         | 0.96%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s                        | 1         | 0.96%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s                        | 1         | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s                      | 1         | 0.96%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s                      | 1         | 0.96%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s                      | 1         | 0.96%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.96%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.96%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s               | 1         | 0.96%   |
| SK hynix RAM 5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A 4096MB SODIMM DDR2 800MT/s | 1         | 0.96%   |
| SK hynix RAM 262626262626262626262626262626262626 4096MB SODIMM DDR2 800MT/s | 1         | 0.96%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2400MT/s                              | 1         | 0.96%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                        | 1         | 0.96%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 42.86%  |
| DDR3   | 31        | 40.26%  |
| DDR2   | 6         | 7.79%   |
| LPDDR4 | 4         | 5.19%   |
| SDRAM  | 1         | 1.3%    |
| LPDDR3 | 1         | 1.3%    |
| DDR    | 1         | 1.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 96.05%  |
| Row Of Chips | 3         | 3.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 32        | 37.21%  |
| 4096  | 28        | 32.56%  |
| 16384 | 10        | 11.63%  |
| 2048  | 9         | 10.47%  |
| 1024  | 4         | 4.65%   |
| 32768 | 2         | 2.33%   |
| 512   | 1         | 1.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 21        | 24.14%  |
| 1600    | 20        | 22.99%  |
| 3200    | 10        | 11.49%  |
| 1333    | 7         | 8.05%   |
| 2400    | 6         | 6.9%    |
| 1334    | 6         | 6.9%    |
| 2133    | 3         | 3.45%   |
| 1067    | 3         | 3.45%   |
| 667     | 3         | 3.45%   |
| 4267    | 2         | 2.3%    |
| 4199    | 1         | 1.15%   |
| 3266    | 1         | 1.15%   |
| 975     | 1         | 1.15%   |
| 800     | 1         | 1.15%   |
| 400     | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

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
| Chicony Electronics                    | 32        | 24.81%  |
| Microdia                               | 14        | 10.85%  |
| IMC Networks                           | 13        | 10.08%  |
| Realtek Semiconductor                  | 12        | 9.3%    |
| Acer                                   | 12        | 9.3%    |
| Sunplus Innovation Technology          | 11        | 8.53%   |
| Lite-On Technology                     | 6         | 4.65%   |
| Silicon Motion                         | 5         | 3.88%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.88%   |
| Suyin                                  | 4         | 3.1%    |
| Luxvisions Innotech Limited            | 4         | 3.1%    |
| Syntek                                 | 2         | 1.55%   |
| Quanta                                 | 2         | 1.55%   |
| Logitech                               | 2         | 1.55%   |
| LG Electronics                         | 1         | 0.78%   |
| Lenovo                                 | 1         | 0.78%   |
| Importek                               | 1         | 0.78%   |
| Huddly                                 | 1         | 0.78%   |
| Apple                                  | 1         | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 6.87%   |
| Lite-On Integrated Camera                               | 5         | 3.82%   |
| Chicony Integrated Camera                               | 5         | 3.82%   |
| Realtek USB Camera                                      | 4         | 3.05%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 2.29%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 2.29%   |
| Chicony Integrated HP HD Webcam                         | 3         | 2.29%   |
| Chicony FJ Camera                                       | 3         | 2.29%   |
| Acer Integrated Camera                                  | 3         | 2.29%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.53%   |
| Sunplus Asus Webcam                                     | 2         | 1.53%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.53%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.53%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.53%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.53%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.53%   |
| IMC Networks Integrated Camera                          | 2         | 1.53%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.53%   |
| Chicony ThinkPad T490 Webcam                            | 2         | 1.53%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.53%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.53%   |
| Chicony HP HD Webcam                                    | 2         | 1.53%   |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.76%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.76%   |
| Suyin USB Webcam                                        | 1         | 0.76%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.76%   |
| Suyin HD WebCam                                         | 1         | 0.76%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.76%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.76%   |
| Sunplus Laptop Integrated Webcam FHD                    | 1         | 0.76%   |
| Sunplus Integrated Webcam                               | 1         | 0.76%   |
| Sunplus HP Wide Vision HD                               | 1         | 0.76%   |
| Sunplus HP Universal Camera                             | 1         | 0.76%   |
| Sunplus HD WebCam                                       | 1         | 0.76%   |
| Sunplus Dell HD Webcam                                  | 1         | 0.76%   |
| Silicon Motion WebCam SC-13HDL11431N                    | 1         | 0.76%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 1         | 0.76%   |
| Silicon Motion WebCam SC-10HDD12636N                    | 1         | 0.76%   |
| Realtek USB2.0 HD UVC WebCam                            | 1         | 0.76%   |
| Realtek Lenovo EasyCamrea                               | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 45.95%  |
| Synaptics                  | 7         | 18.92%  |
| Upek                       | 4         | 10.81%  |
| STMicroelectronics         | 4         | 10.81%  |
| Shenzhen Goodix Technology | 3         | 8.11%   |
| Elan Microelectronics      | 1         | 2.7%    |
| AuthenTec                  | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 13.51%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 4         | 10.81%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 10.81%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 10.81%  |
| STMicroelectronics Fingerprint Reader                  | 4         | 10.81%  |
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 8.11%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 3         | 8.11%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 5.41%   |
| Shenzhen Goodix FingerPrint                            | 2         | 5.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.7%    |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 2.7%    |
| Validity Sensors Fingerprint scanner                   | 1         | 2.7%    |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 2.7%    |
| Elan ELAN:Fingerprint                                  | 1         | 2.7%    |
| AuthenTec AES2550 Fingerprint Sensor                   | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 18        | 52.94%  |
| OmniKey               | 6         | 17.65%  |
| Lenovo                | 3         | 8.82%   |
| Gemalto (was Gemplus) | 3         | 8.82%   |
| Broadcom              | 3         | 8.82%   |
| O2 Micro              | 1         | 2.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 18        | 52.94%  |
| OmniKey CardMan 4321                                   | 3         | 8.82%   |
| OmniKey CardMan 1021                                   | 3         | 8.82%   |
| Lenovo Integrated Smart Card Reader                    | 3         | 8.82%   |
| Broadcom 58200                                         | 3         | 8.82%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 2         | 5.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 2.94%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 2.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 88        | 56.77%  |
| 1     | 48        | 30.97%  |
| 2     | 18        | 11.61%  |
| 3     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 37        | 43.53%  |
| Chipcard                 | 18        | 21.18%  |
| Graphics card            | 17        | 20%     |
| Net/wireless             | 4         | 4.71%   |
| Card reader              | 2         | 2.35%   |
| Camera                   | 2         | 2.35%   |
| Net/ethernet             | 1         | 1.18%   |
| Multimedia controller    | 1         | 1.18%   |
| Modem                    | 1         | 1.18%   |
| Communication controller | 1         | 1.18%   |
| Bluetooth                | 1         | 1.18%   |

