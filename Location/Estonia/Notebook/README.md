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

Total: 184

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04      | 19        | 13.77%  |
| Ubuntu 18.04      | 14        | 10.14%  |
| Ubuntu 19.04      | 6         | 4.35%   |
| Arch              | 6         | 4.35%   |
| Linux Mint 20.1   | 5         | 3.62%   |
| ArcoLinux Rolling | 5         | 3.62%   |
| Fedora 34         | 4         | 2.9%    |
| ROSA R9           | 3         | 2.17%   |
| ROSA R8.1         | 3         | 2.17%   |
| ROSA R11          | 3         | 2.17%   |
| Pop!_OS 20.04     | 3         | 2.17%   |
| OpenMandriva 4.2  | 3         | 2.17%   |
| Kubuntu 20.04     | 3         | 2.17%   |
| Xubuntu 20.04     | 2         | 1.45%   |
| Ubuntu 22.04      | 2         | 1.45%   |
| Ubuntu 20.10      | 2         | 1.45%   |
| Ubuntu 19.10      | 2         | 1.45%   |
| Reborn OS         | 2         | 1.45%   |
| Manjaro 20.1      | 2         | 1.45%   |
| Manjaro           | 2         | 1.45%   |
| Linux Mint 20.2   | 2         | 1.45%   |
| Linux Mint 19.3   | 2         | 1.45%   |
| Linux Mint 18.3   | 2         | 1.45%   |
| KDE neon 20.04    | 2         | 1.45%   |
| Fedora 36         | 2         | 1.45%   |
| Elementary 6.1    | 2         | 1.45%   |
| Debian 11         | 2         | 1.45%   |
| Arch Rolling      | 2         | 1.45%   |
| Zorin 16          | 1         | 0.72%   |
| Zorin 15          | 1         | 0.72%   |
| Xubuntu 18.04     | 1         | 0.72%   |
| Ubuntu MATE 22.04 | 1         | 0.72%   |
| Ubuntu MATE 20.04 | 1         | 0.72%   |
| Ubuntu 21.04      | 1         | 0.72%   |
| Ubuntu 16.04      | 1         | 0.72%   |
| ROSA R8           | 1         | 0.72%   |
| ROSA R10          | 1         | 0.72%   |
| ROSA 12.2         | 1         | 0.72%   |
| Pop!_OS 21.10     | 1         | 0.72%   |
| Pop!_OS 20.10     | 1         | 0.72%   |
| Manjaro 21.2.3    | 1         | 0.72%   |
| Manjaro 21.0.7    | 1         | 0.72%   |
| Manjaro 18.1.5    | 1         | 0.72%   |
| Lubuntu 18.04     | 1         | 0.72%   |
| LMDE 4            | 1         | 0.72%   |
| Linux Mint 20.3   | 1         | 0.72%   |
| Linux Mint 20     | 1         | 0.72%   |
| Kubuntu 22.04     | 1         | 0.72%   |
| Fedora 35         | 1         | 0.72%   |
| Fedora 33         | 1         | 0.72%   |
| Fedora 30         | 1         | 0.72%   |
| Endless 3.9.5     | 1         | 0.72%   |
| Endless 3.8.6     | 1         | 0.72%   |
| Endless 3.7.8     | 1         | 0.72%   |
| Elementary 6      | 1         | 0.72%   |
| Debian Testing    | 1         | 0.72%   |
| Debian 8          | 1         | 0.72%   |
| Clear Linux 34220 | 1         | 0.72%   |
| Clear Linux 29480 | 1         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 47        | 34.56%  |
| Linux Mint   | 13        | 9.56%   |
| ROSA         | 12        | 8.82%   |
| Fedora       | 8         | 5.88%   |
| Arch         | 8         | 5.88%   |
| Manjaro      | 7         | 5.15%   |
| Pop!_OS      | 5         | 3.68%   |
| ArcoLinux    | 5         | 3.68%   |
| Kubuntu      | 4         | 2.94%   |
| Xubuntu      | 3         | 2.21%   |
| OpenMandriva | 3         | 2.21%   |
| Endless      | 3         | 2.21%   |
| Elementary   | 3         | 2.21%   |
| Debian       | 3         | 2.21%   |
| Zorin        | 2         | 1.47%   |
| Ubuntu MATE  | 2         | 1.47%   |
| Reborn OS    | 2         | 1.47%   |
| KDE neon     | 2         | 1.47%   |
| Clear Linux  | 2         | 1.47%   |
| Lubuntu      | 1         | 0.74%   |
| LMDE         | 1         | 0.74%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 6         | 4.03%   |
| 5.4.0-47-generic                | 3         | 2.01%   |
| 5.4.0-28-generic                | 3         | 2.01%   |
| 5.10.14-desktop-1omv4002        | 3         | 2.01%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 3         | 2.01%   |
| 5.8.0-53-generic                | 2         | 1.34%   |
| 5.4.0-88-generic                | 2         | 1.34%   |
| 5.4.0-65-generic                | 2         | 1.34%   |
| 5.15.2-arch1-1                  | 2         | 1.34%   |
| 5.13.0-39-generic               | 2         | 1.34%   |
| 5.11.0-27-generic               | 2         | 1.34%   |
| 5.0.0-23-generic                | 2         | 1.34%   |
| 4.18.0-15-generic               | 2         | 1.34%   |
| 4.15.0-45-generic               | 2         | 1.34%   |
| 5.9.16-1-MANJARO                | 1         | 0.67%   |
| 5.9.13-200.fc33.x86_64          | 1         | 0.67%   |
| 5.9.10-zen1-1-zen               | 1         | 0.67%   |
| 5.9.0-050900rc5-lowlatency      | 1         | 0.67%   |
| 5.8.6-1-MANJARO                 | 1         | 0.67%   |
| 5.8.0-7630-generic              | 1         | 0.67%   |
| 5.8.0-63-generic                | 1         | 0.67%   |
| 5.8.0-59-generic                | 1         | 0.67%   |
| 5.8.0-54-generic                | 1         | 0.67%   |
| 5.8.0-50-generic                | 1         | 0.67%   |
| 5.8.0-45-generic                | 1         | 0.67%   |
| 5.8.0-44-generic                | 1         | 0.67%   |
| 5.8.0-38-generic                | 1         | 0.67%   |
| 5.8.0-29-generic                | 1         | 0.67%   |
| 5.8.0-14-generic                | 1         | 0.67%   |
| 5.6.13-100.fc30.x86_64          | 1         | 0.67%   |
| 5.5.6-1-MANJARO                 | 1         | 0.67%   |
| 5.4.64-1-MANJARO                | 1         | 0.67%   |
| 5.4.0-7642-generic              | 1         | 0.67%   |
| 5.4.0-7634-generic              | 1         | 0.67%   |
| 5.4.0-72-generic                | 1         | 0.67%   |
| 5.4.0-70-generic                | 1         | 0.67%   |
| 5.4.0-66-generic                | 1         | 0.67%   |
| 5.4.0-58-generic                | 1         | 0.67%   |
| 5.4.0-56-generic                | 1         | 0.67%   |
| 5.4.0-45-generic                | 1         | 0.67%   |
| 5.4.0-38-generic                | 1         | 0.67%   |
| 5.4.0-37-generic                | 1         | 0.67%   |
| 5.4.0-33-generic                | 1         | 0.67%   |
| 5.4.0-29-generic                | 1         | 0.67%   |
| 5.4.0-14-generic                | 1         | 0.67%   |
| 5.4.0-113-generic               | 1         | 0.67%   |
| 5.4.0-050400-generic            | 1         | 0.67%   |
| 5.3.0-45-generic                | 1         | 0.67%   |
| 5.3.0-28-generic                | 1         | 0.67%   |
| 5.3.0-050300rc2-generic         | 1         | 0.67%   |
| 5.17.6-300.fc36.x86_64          | 1         | 0.67%   |
| 5.17.4-arch1-1                  | 1         | 0.67%   |
| 5.17.1-zen1-1-zen               | 1         | 0.67%   |
| 5.17.1-300.fc36.x86_64          | 1         | 0.67%   |
| 5.16.9-2-MANJARO                | 1         | 0.67%   |
| 5.16.5-arch1-1                  | 1         | 0.67%   |
| 5.16.15-201.fc35.x86_64         | 1         | 0.67%   |
| 5.15.5-76051505-generic         | 1         | 0.67%   |
| 5.15.15-76051515-generic        | 1         | 0.67%   |
| 5.15.0-41-generic               | 1         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 31        | 21.68%  |
| 4.15.0  | 13        | 9.09%   |
| 5.8.0   | 9         | 6.29%   |
| 5.11.0  | 7         | 4.9%    |
| 5.0.0   | 7         | 4.9%    |
| 5.13.0  | 5         | 3.5%    |
| 4.18.0  | 5         | 3.5%    |
| 5.15.0  | 4         | 2.8%    |
| 4.9.20  | 4         | 2.8%    |
| 5.3.0   | 3         | 2.1%    |
| 5.10.14 | 3         | 2.1%    |
| 5.17.1  | 2         | 1.4%    |
| 5.15.2  | 2         | 1.4%    |
| 5.13.13 | 2         | 1.4%    |
| 5.13.12 | 2         | 1.4%    |
| 5.11.12 | 2         | 1.4%    |
| 5.9.16  | 1         | 0.7%    |
| 5.9.13  | 1         | 0.7%    |
| 5.9.10  | 1         | 0.7%    |
| 5.9.0   | 1         | 0.7%    |
| 5.8.6   | 1         | 0.7%    |
| 5.6.13  | 1         | 0.7%    |
| 5.5.6   | 1         | 0.7%    |
| 5.4.64  | 1         | 0.7%    |
| 5.17.6  | 1         | 0.7%    |
| 5.17.4  | 1         | 0.7%    |
| 5.16.9  | 1         | 0.7%    |
| 5.16.5  | 1         | 0.7%    |
| 5.16.15 | 1         | 0.7%    |
| 5.15.5  | 1         | 0.7%    |
| 5.15.15 | 1         | 0.7%    |
| 5.14.21 | 1         | 0.7%    |
| 5.14.2  | 1         | 0.7%    |
| 5.13.9  | 1         | 0.7%    |
| 5.13.8  | 1         | 0.7%    |
| 5.13.7  | 1         | 0.7%    |
| 5.13.10 | 1         | 0.7%    |
| 5.12.7  | 1         | 0.7%    |
| 5.12.3  | 1         | 0.7%    |
| 5.12.14 | 1         | 0.7%    |
| 5.11.11 | 1         | 0.7%    |
| 5.10.74 | 1         | 0.7%    |
| 5.10.62 | 1         | 0.7%    |
| 5.10.35 | 1         | 0.7%    |
| 5.10.2  | 1         | 0.7%    |
| 5.10.12 | 1         | 0.7%    |
| 5.10.10 | 1         | 0.7%    |
| 5.10.0  | 1         | 0.7%    |
| 5.0.17  | 1         | 0.7%    |
| 4.9.9   | 1         | 0.7%    |
| 4.9.60  | 1         | 0.7%    |
| 4.9.34  | 1         | 0.7%    |
| 4.4.0   | 1         | 0.7%    |
| 4.19.99 | 1         | 0.7%    |
| 4.19.0  | 1         | 0.7%    |
| 4.10.0  | 1         | 0.7%    |
| 4.1.25  | 1         | 0.7%    |
| 3.16.0  | 1         | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 32        | 22.38%  |
| 5.13    | 13        | 9.09%   |
| 4.15    | 13        | 9.09%   |
| 5.8     | 10        | 6.99%   |
| 5.11    | 10        | 6.99%   |
| 5.10    | 10        | 6.99%   |
| 5.15    | 8         | 5.59%   |
| 5.0     | 8         | 5.59%   |
| 4.9     | 7         | 4.9%    |
| 4.18    | 5         | 3.5%    |
| 5.9     | 4         | 2.8%    |
| 5.17    | 4         | 2.8%    |
| 5.3     | 3         | 2.1%    |
| 5.16    | 3         | 2.1%    |
| 5.12    | 3         | 2.1%    |
| 5.14    | 2         | 1.4%    |
| 4.19    | 2         | 1.4%    |
| 5.6     | 1         | 0.7%    |
| 5.5     | 1         | 0.7%    |
| 4.4     | 1         | 0.7%    |
| 4.10    | 1         | 0.7%    |
| 4.1     | 1         | 0.7%    |
| 3.16    | 1         | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 128       | 96.24%  |
| i686   | 5         | 3.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 45        | 33.58%  |
| Unknown    | 25        | 18.66%  |
| KDE5       | 14        | 10.45%  |
| XFCE       | 11        | 8.21%   |
| X-Cinnamon | 8         | 5.97%   |
| KDE4       | 8         | 5.97%   |
| MATE       | 6         | 4.48%   |
| Pantheon   | 3         | 2.24%   |
| KDE        | 3         | 2.24%   |
| Unity      | 2         | 1.49%   |
| i3         | 2         | 1.49%   |
| awesome    | 2         | 1.49%   |
| openbox    | 1         | 0.75%   |
| LXQt       | 1         | 0.75%   |
| LXDE       | 1         | 0.75%   |
| Cinnamon   | 1         | 0.75%   |
| Budgie     | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 108       | 81.2%   |
| Wayland | 14        | 10.53%  |
| Unknown | 10        | 7.52%   |
| Tty     | 1         | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 73        | 54.48%  |
| SDDM    | 19        | 14.18%  |
| GDM     | 16        | 11.94%  |
| TDM     | 9         | 6.72%   |
| KDM     | 8         | 5.97%   |
| LightDM | 5         | 3.73%   |
| GDM3    | 4         | 2.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 63        | 46.67%  |
| Unknown         | 32        | 23.7%   |
| et_EE           | 19        | 14.07%  |
| ru_RU           | 11        | 8.15%   |
| en_GB           | 3         | 2.22%   |
| de_DE           | 2         | 1.48%   |
| uk_UA           | 1         | 0.74%   |
| ru_UA           | 1         | 0.74%   |
| en_US.iso885915 | 1         | 0.74%   |
| en_DK           | 1         | 0.74%   |
| C               | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 70        | 51.09%  |
| EFI  | 67        | 48.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 102       | 76.69%  |
| Btrfs   | 12        | 9.02%   |
| Unknown | 12        | 9.02%   |
| Overlay | 3         | 2.26%   |
| Xfs     | 2         | 1.5%    |
| Zfs     | 1         | 0.75%   |
| Ext3    | 1         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 79        | 59.4%   |
| GPT     | 37        | 27.82%  |
| MBR     | 17        | 12.78%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 123       | 91.79%  |
| Yes       | 11        | 8.21%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 72.79%  |
| Yes       | 37        | 27.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 39        | 29.32%  |
| Hewlett-Packard     | 29        | 21.8%   |
| Dell                | 20        | 15.04%  |
| ASUSTek Computer    | 16        | 12.03%  |
| Samsung Electronics | 7         | 5.26%   |
| Acer                | 5         | 3.76%   |
| MSI                 | 3         | 2.26%   |
| Timi                | 2         | 1.5%    |
| Quanta              | 2         | 1.5%    |
| TUXEDO              | 1         | 0.75%   |
| Toshiba             | 1         | 0.75%   |
| Notebook            | 1         | 0.75%   |
| mPTech              | 1         | 0.75%   |
| Getac               | 1         | 0.75%   |
| Fujitsu Siemens     | 1         | 0.75%   |
| Fujitsu             | 1         | 0.75%   |
| Framework           | 1         | 0.75%   |
| Apple               | 1         | 0.75%   |
| Alienware           | 1         | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Quanta TWH                                            | 2         | 1.5%    |
| Lenovo Y50-70 20378                                   | 2         | 1.5%    |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 1.5%    |
| HP Pavilion dv7                                       | 2         | 1.5%    |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 1.5%    |
| HP EliteBook 8470p                                    | 2         | 1.5%    |
| HP EliteBook 8460p                                    | 2         | 1.5%    |
| HP EliteBook 840 G2                                   | 2         | 1.5%    |
| Dell Inspiron N5110                                   | 2         | 1.5%    |
| TUXEDO Book BA1510                                    | 1         | 0.75%   |
| Toshiba Satellite L855                                | 1         | 0.75%   |
| Timi RedmiBook 16                                     | 1         | 0.75%   |
| Timi RedmiBook 14 II                                  | 1         | 0.75%   |
| Samsung R410                                          | 1         | 0.75%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.75%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.75%   |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.75%   |
| Samsung 535U3C                                        | 1         | 0.75%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.75%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.75%   |
| Notebook W35xSS_370SS                                 | 1         | 0.75%   |
| MSI GT70 2OC/2OD                                      | 1         | 0.75%   |
| MSI GS75 Stealth 8SE                                  | 1         | 0.75%   |
| MSI GP62M 7RDX                                        | 1         | 0.75%   |
| mPTech ARC 11.6 128GB HD                              | 1         | 0.75%   |
| Lenovo Y720-15IKB 80VR                                | 1         | 0.75%   |
| Lenovo Y520-15IKBN 80WK                               | 1         | 0.75%   |
| Lenovo V110-15ISK 80TL                                | 1         | 0.75%   |
| Lenovo ThinkPad X260 20F5S84400                       | 1         | 0.75%   |
| Lenovo ThinkPad X220 4291R30                          | 1         | 0.75%   |
| Lenovo ThinkPad X220 429136G                          | 1         | 0.75%   |
| Lenovo ThinkPad X201 3680CG7                          | 1         | 0.75%   |
| Lenovo ThinkPad W541 20EF001TMS                       | 1         | 0.75%   |
| Lenovo ThinkPad T61 76641FG                           | 1         | 0.75%   |
| Lenovo ThinkPad T61 766112G                           | 1         | 0.75%   |
| Lenovo ThinkPad T61 765912G                           | 1         | 0.75%   |
| Lenovo ThinkPad T61 64665DG                           | 1         | 0.75%   |
| Lenovo ThinkPad T580 20L90026MX                       | 1         | 0.75%   |
| Lenovo ThinkPad T540p 20BFS45100                      | 1         | 0.75%   |
| Lenovo ThinkPad T520 4243RT9                          | 1         | 0.75%   |
| Lenovo ThinkPad T510 4384GFG                          | 1         | 0.75%   |
| Lenovo ThinkPad T490s 20NX000AMX                      | 1         | 0.75%   |
| Lenovo ThinkPad T490 20N2000NMX                       | 1         | 0.75%   |
| Lenovo ThinkPad T480s 20L7001VUK                      | 1         | 0.75%   |
| Lenovo ThinkPad T480 20L5000BMX                       | 1         | 0.75%   |
| Lenovo ThinkPad T450s 20BWS1RG01                      | 1         | 0.75%   |
| Lenovo ThinkPad T440 20B60061MD                       | 1         | 0.75%   |
| Lenovo ThinkPad T14 Gen 1 20UDCTO1WW                  | 1         | 0.75%   |
| Lenovo ThinkPad P50 20EN0006MS                        | 1         | 0.75%   |
| Lenovo ThinkPad P43s 20RH0021MX                       | 1         | 0.75%   |
| Lenovo ThinkPad P14s Gen 1 20S4004AMH                 | 1         | 0.75%   |
| Lenovo ThinkPad E495 20NE001GMX                       | 1         | 0.75%   |
| Lenovo ThinkPad E14 Gen 2 20T6000KMX                  | 1         | 0.75%   |
| Lenovo ThinkPad E14 20RA0036MX                        | 1         | 0.75%   |
| Lenovo ThinkPad A285 20MXS0BG00                       | 1         | 0.75%   |
| Lenovo ThinkPad 20AY001DMH                            | 1         | 0.75%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                      | 1         | 0.75%   |
| Lenovo IdeaPadFlex 10 20324                           | 1         | 0.75%   |
| Lenovo IdeaPad U330p 20267                            | 1         | 0.75%   |
| Lenovo IdeaPad 320S-13IKB 81AK                        | 1         | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 28        | 21.05%  |
| HP EliteBook          | 12        | 9.02%   |
| HP Pavilion           | 7         | 5.26%   |
| Dell Inspiron         | 6         | 4.51%   |
| Dell Precision        | 4         | 3.01%   |
| Dell Latitude         | 4         | 3.01%   |
| Acer Aspire           | 4         | 3.01%   |
| Lenovo IdeaPad        | 3         | 2.26%   |
| Dell XPS              | 3         | 2.26%   |
| ASUS VivoBook         | 3         | 2.26%   |
| Timi RedmiBook        | 2         | 1.5%    |
| Samsung 900X3C        | 2         | 1.5%    |
| Quanta TWH            | 2         | 1.5%    |
| Lenovo Y50-70         | 2         | 1.5%    |
| HP Presario           | 2         | 1.5%    |
| HP OMEN               | 2         | 1.5%    |
| HP ENVY               | 2         | 1.5%    |
| HP Compaq             | 2         | 1.5%    |
| ASUS ZenBook          | 2         | 1.5%    |
| TUXEDO Book           | 1         | 0.75%   |
| Toshiba Satellite     | 1         | 0.75%   |
| Samsung R410          | 1         | 0.75%   |
| Samsung 770Z5E        | 1         | 0.75%   |
| Samsung 535U3C        | 1         | 0.75%   |
| Samsung 300E5EV       | 1         | 0.75%   |
| Samsung 275E4E        | 1         | 0.75%   |
| Notebook W35xSS       | 1         | 0.75%   |
| MSI GT70              | 1         | 0.75%   |
| MSI GS75              | 1         | 0.75%   |
| MSI GP62M             | 1         | 0.75%   |
| mPTech ARC            | 1         | 0.75%   |
| Lenovo Y720-15IKB     | 1         | 0.75%   |
| Lenovo Y520-15IKBN    | 1         | 0.75%   |
| Lenovo V110-15ISK     | 1         | 0.75%   |
| Lenovo Legion         | 1         | 0.75%   |
| Lenovo IdeaPadFlex    | 1         | 0.75%   |
| Lenovo G50-70         | 1         | 0.75%   |
| HP ZBook              | 1         | 0.75%   |
| HP ProBook            | 1         | 0.75%   |
| Getac B300G4          | 1         | 0.75%   |
| Fujitsu Siemens AMILO | 1         | 0.75%   |
| Fujitsu LIFEBOOK      | 1         | 0.75%   |
| Framework Laptop      | 1         | 0.75%   |
| Dell Vostro           | 1         | 0.75%   |
| Dell System           | 1         | 0.75%   |
| Dell G5               | 1         | 0.75%   |
| ASUS X55A             | 1         | 0.75%   |
| ASUS X550ZA           | 1         | 0.75%   |
| ASUS X542UQR          | 1         | 0.75%   |
| ASUS X510UA           | 1         | 0.75%   |
| ASUS X501U            | 1         | 0.75%   |
| ASUS UX530UX          | 1         | 0.75%   |
| ASUS N56VZ            | 1         | 0.75%   |
| ASUS K52Jc            | 1         | 0.75%   |
| ASUS K40IJ            | 1         | 0.75%   |
| ASUS E502NA           | 1         | 0.75%   |
| ASUS E502MA           | 1         | 0.75%   |
| Apple MacBookPro8     | 1         | 0.75%   |
| Alienware 17          | 1         | 0.75%   |
| Acer Extensa          | 1         | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 16        | 12.03%  |
| 2020 | 15        | 11.28%  |
| 2018 | 13        | 9.77%   |
| 2013 | 13        | 9.77%   |
| 2019 | 11        | 8.27%   |
| 2014 | 11        | 8.27%   |
| 2015 | 10        | 7.52%   |
| 2017 | 9         | 6.77%   |
| 2012 | 8         | 6.02%   |
| 2008 | 6         | 4.51%   |
| 2007 | 6         | 4.51%   |
| 2016 | 4         | 3.01%   |
| 2010 | 4         | 3.01%   |
| 2021 | 3         | 2.26%   |
| 2009 | 3         | 2.26%   |
| 2006 | 1         | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 133       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 120       | 89.55%  |
| Enabled  | 14        | 10.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 133       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 33        | 24.44%  |
| 4.01-8.0    | 30        | 22.22%  |
| 3.01-4.0    | 26        | 19.26%  |
| 16.01-24.0  | 22        | 16.3%   |
| 32.01-64.0  | 7         | 5.19%   |
| 24.01-32.0  | 6         | 4.44%   |
| 2.01-3.0    | 6         | 4.44%   |
| 1.01-2.0    | 4         | 2.96%   |
| 64.01-256.0 | 1         | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 54        | 38.03%  |
| 2.01-3.0   | 34        | 23.94%  |
| 4.01-8.0   | 23        | 16.2%   |
| 3.01-4.0   | 14        | 9.86%   |
| 8.01-16.0  | 8         | 5.63%   |
| 0.51-1.0   | 8         | 5.63%   |
| 24.01-32.0 | 1         | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 105       | 77.21%  |
| 2      | 27        | 19.85%  |
| 3      | 2         | 1.47%   |
| 5      | 1         | 0.74%   |
| 4      | 1         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 60.74%  |
| Yes       | 53        | 39.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 86.57%  |
| No        | 18        | 13.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 77.61%  |
| No        | 30        | 22.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Estonia | 133       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Tallinn           | 87        | 64.93%  |
| Tartu             | 12        | 8.96%   |
| Rapla             | 4         | 2.99%   |
| Pärnu            | 4         | 2.99%   |
| Rakvere           | 3         | 2.24%   |
| Narva             | 3         | 2.24%   |
| Vinni             | 2         | 1.49%   |
| Otepaeae          | 2         | 1.49%   |
| Maardu            | 2         | 1.49%   |
| Keila             | 2         | 1.49%   |
| Viljandi          | 1         | 0.75%   |
| Vatla             | 1         | 0.75%   |
| Tabasalu          | 1         | 0.75%   |
| Sauga             | 1         | 0.75%   |
| Saku              | 1         | 0.75%   |
| Rae Parish        | 1         | 0.75%   |
| Põlva            | 1         | 0.75%   |
| Pohja-Sakala vald | 1         | 0.75%   |
| Laagri            | 1         | 0.75%   |
| Kärdla           | 1         | 0.75%   |
| Kaeina            | 1         | 0.75%   |
| Jõhvi            | 1         | 0.75%   |
| Jõgeva           | 1         | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 41     | 21.6%   |
| Seagate             | 25        | 28     | 15.43%  |
| SK hynix            | 13        | 17     | 8.02%   |
| Toshiba             | 12        | 12     | 7.41%   |
| WDC                 | 11        | 13     | 6.79%   |
| Kingston            | 8         | 9      | 4.94%   |
| Intel               | 7         | 8      | 4.32%   |
| SanDisk             | 6         | 8      | 3.7%    |
| HGST                | 6         | 7      | 3.7%    |
| Unknown             | 5         | 5      | 3.09%   |
| Hitachi             | 5         | 5      | 3.09%   |
| Micron Technology   | 3         | 3      | 1.85%   |
| Crucial             | 3         | 3      | 1.85%   |
| Transcend           | 2         | 4      | 1.23%   |
| Lenovo              | 2         | 2      | 1.23%   |
| KingSpec            | 2         | 2      | 1.23%   |
| Gigabyte Technology | 2         | 3      | 1.23%   |
| Fujitsu             | 2         | 2      | 1.23%   |
| Apacer              | 2         | 2      | 1.23%   |
| A-DATA Technology   | 2         | 2      | 1.23%   |
| Phison              | 1         | 1      | 0.62%   |
| Patriot             | 1         | 1      | 0.62%   |
| LITEONIT            | 1         | 1      | 0.62%   |
| Lexar               | 1         | 1      | 0.62%   |
| KIOXIA              | 1         | 2      | 0.62%   |
| Intenso             | 1         | 1      | 0.62%   |
| HUAWEI              | 1         | 1      | 0.62%   |
| China               | 1         | 1      | 0.62%   |
| ASMT109x            | 1         | 2      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB               | 3         | 1.81%   |
| Unknown MMC Card  16GB                 | 2         | 1.2%    |
| Toshiba NVMe SSD Drive 512GB           | 2         | 1.2%    |
| SK hynix NVMe SSD Drive 512GB          | 2         | 1.2%    |
| SK hynix NVMe SSD Drive 256GB          | 2         | 1.2%    |
| Seagate ST500LT012-1DG142 500GB        | 2         | 1.2%    |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 1.2%    |
| SanDisk SD8SBAT256G1122 256GB SSD      | 2         | 1.2%    |
| Samsung SSD 970 EVO Plus 1TB           | 2         | 1.2%    |
| Samsung SSD 850 EVO M.2 500GB          | 2         | 1.2%    |
| Samsung SSD 850 EVO 500GB              | 2         | 1.2%    |
| Samsung NVMe SSD Drive 512GB           | 2         | 1.2%    |
| Samsung NVMe SSD Drive 1TB             | 2         | 1.2%    |
| Samsung NVMe SSD Drive 1024GB          | 2         | 1.2%    |
| Samsung MZVLB512HBJQ-000L7 512GB       | 2         | 1.2%    |
| Samsung MZ7LN256HCHP-000L7 256GB SSD   | 2         | 1.2%    |
| Micron 1100_MTFDDAV512TBN 512GB SSD    | 2         | 1.2%    |
| Kingston SV300S37A120G 120GB SSD       | 2         | 1.2%    |
| Kingston SA400S37960G 960GB SSD        | 2         | 1.2%    |
| Intel SSDPEKKF256G8L 256GB             | 2         | 1.2%    |
| WDC WDS500G2B0B 500GB SSD              | 1         | 0.6%    |
| WDC WDS500G1X0E-00AFY0 500GB           | 1         | 0.6%    |
| WDC WDS250G1B0A-00H9H0 250GB SSD       | 1         | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.6%    |
| WDC WD5000LPCX-24VHAT0 500GB           | 1         | 0.6%    |
| WDC WD2500BEVT-80A23T0 250GB           | 1         | 0.6%    |
| WDC WD1200BEVS-08RST2 120GB            | 1         | 0.6%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 1         | 0.6%    |
| WDC PC SN730 NVMe 512GB                | 1         | 0.6%    |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB   | 1         | 0.6%    |
| Unknown MMC128  128GB                  | 1         | 0.6%    |
| Unknown MMC Card  7GB                  | 1         | 0.6%    |
| Unknown MMC Card  128GB                | 1         | 0.6%    |
| Transcend TS1TSSD230S 1024GB           | 1         | 0.6%    |
| Transcend TS120GMTS420S 120GB SSD      | 1         | 0.6%    |
| Toshiba TR200 480GB SSD                | 1         | 0.6%    |
| Toshiba THNSNK128GVN8 128GB SSD        | 1         | 0.6%    |
| Toshiba NVMe SSD Drive 256GB           | 1         | 0.6%    |
| Toshiba MQ02ABF100 1TB                 | 1         | 0.6%    |
| Toshiba MQ01ABF050 500GB               | 1         | 0.6%    |
| Toshiba MQ01ABD100 1TB                 | 1         | 0.6%    |
| Toshiba MQ01ABD075 752GB               | 1         | 0.6%    |
| Toshiba MK6025GAS 64GB                 | 1         | 0.6%    |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 1         | 0.6%    |
| Toshiba HDWL120 2TB                    | 1         | 0.6%    |
| SK hynix SKHynix_HFS512GDE9X084N 512GB | 1         | 0.6%    |
| SK hynix SC311 SATA 512GB SSD          | 1         | 0.6%    |
| SK hynix SC311 SATA 256GB SSD          | 1         | 0.6%    |
| SK hynix PC711 NVMe 512GB              | 1         | 0.6%    |
| SK hynix PC601 NVMe 512GB              | 1         | 0.6%    |
| SK hynix HFS256GD9TNG-62A0A 256GB      | 1         | 0.6%    |
| SK hynix HFS128G3BMND-3210A 128GB SSD  | 1         | 0.6%    |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 1         | 0.6%    |
| SK hynix HFM512GDHTNG-8710B 512GB      | 1         | 0.6%    |
| Seagate ST98823AS 80GB                 | 1         | 0.6%    |
| Seagate ST9500420AS 500GB              | 1         | 0.6%    |
| Seagate ST9500325AS 500GB              | 1         | 0.6%    |
| Seagate ST9250410AS 250GB              | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 24        | 27     | 51.06%  |
| Toshiba | 6         | 6      | 12.77%  |
| HGST    | 6         | 7      | 12.77%  |
| Hitachi | 5         | 5      | 10.64%  |
| WDC     | 4         | 5      | 8.51%   |
| Fujitsu | 2         | 2      | 4.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 24     | 32.31%  |
| Kingston            | 8         | 9      | 12.31%  |
| SanDisk             | 5         | 7      | 7.69%   |
| SK hynix            | 4         | 4      | 6.15%   |
| WDC                 | 3         | 4      | 4.62%   |
| Micron Technology   | 3         | 3      | 4.62%   |
| Crucial             | 3         | 3      | 4.62%   |
| Transcend           | 2         | 4      | 3.08%   |
| Toshiba             | 2         | 2      | 3.08%   |
| KingSpec            | 2         | 2      | 3.08%   |
| Intel               | 2         | 3      | 3.08%   |
| Apacer              | 2         | 2      | 3.08%   |
| A-DATA Technology   | 2         | 2      | 3.08%   |
| Patriot             | 1         | 1      | 1.54%   |
| LITEONIT            | 1         | 1      | 1.54%   |
| Lexar               | 1         | 1      | 1.54%   |
| Intenso             | 1         | 1      | 1.54%   |
| Gigabyte Technology | 1         | 2      | 1.54%   |
| China               | 1         | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 56        | 76     | 37.33%  |
| HDD     | 47        | 52     | 31.33%  |
| NVMe    | 39        | 50     | 26%     |
| MMC     | 5         | 5      | 3.33%   |
| Unknown | 3         | 4      | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 95        | 125    | 65.07%  |
| NVMe | 39        | 50     | 26.71%  |
| SAS  | 7         | 7      | 4.79%   |
| MMC  | 5         | 5      | 3.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 92     | 70.09%  |
| 0.51-1.0   | 27        | 29     | 25.23%  |
| 1.01-2.0   | 4         | 6      | 3.74%   |
| 4.01-10.0  | 1         | 1      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 49        | 35.51%  |
| 251-500        | 31        | 22.46%  |
| 501-1000       | 19        | 13.77%  |
| 1-20           | 11        | 7.97%   |
| 51-100         | 9         | 6.52%   |
| 1001-2000      | 6         | 4.35%   |
| 21-50          | 5         | 3.62%   |
| Unknown        | 4         | 2.9%    |
| More than 3000 | 3         | 2.17%   |
| 2001-3000      | 1         | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 60        | 42.55%  |
| 21-50          | 22        | 15.6%   |
| 101-250        | 20        | 14.18%  |
| 51-100         | 19        | 13.48%  |
| 251-500        | 10        | 7.09%   |
| Unknown        | 4         | 2.84%   |
| 501-1000       | 3         | 2.13%   |
| More than 3000 | 2         | 1.42%   |
| 1001-2000      | 1         | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 9.09%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 9.09%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 9.09%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 9.09%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 9.09%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 9.09%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 9.09%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 9.09%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 9.09%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 54.55%  |
| WDC               | 1         | 1      | 9.09%   |
| Micron Technology | 1         | 1      | 9.09%   |
| Hitachi           | 1         | 1      | 9.09%   |
| Fujitsu           | 1         | 1      | 9.09%   |
| Crucial           | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 66.67%  |
| WDC     | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |
| Fujitsu | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 81.82%  |
| SSD  | 2         | 2      | 18.18%  |

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
| Detected | 83        | 125    | 60.58%  |
| Works    | 43        | 51     | 31.39%  |
| Malfunc  | 11        | 11     | 8.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 103       | 64.38%  |
| AMD                          | 18        | 11.25%  |
| Samsung Electronics          | 15        | 9.38%   |
| SK hynix                     | 9         | 5.63%   |
| SanDisk                      | 5         | 3.13%   |
| Toshiba America Info Systems | 3         | 1.88%   |
| Phison Electronics           | 2         | 1.25%   |
| Lenovo                       | 2         | 1.25%   |
| KIOXIA                       | 2         | 1.25%   |
| VIA Technologies             | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 14        | 8%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 13        | 7.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 12        | 6.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 12        | 6.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 10        | 5.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 9         | 5.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 7         | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 7         | 4%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 6         | 3.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 5         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 5         | 2.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 2.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 4         | 2.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 4         | 2.29%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 3         | 1.71%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.71%   |
| SK hynix Non-Volatile memory controller                                                | 2         | 1.14%   |
| SK hynix Gold P31 SSD                                                                  | 2         | 1.14%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 1.14%   |
| Lenovo Non-Volatile memory controller                                                  | 2         | 1.14%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 2         | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 1.14%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 2         | 1.14%   |
| Intel SSD 660P Series                                                                  | 2         | 1.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 1.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.14%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 2         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 2         | 1.14%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 1         | 0.57%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 1         | 0.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.57%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 1         | 0.57%   |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 0.57%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                             | 1         | 0.57%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 0.57%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 0.57%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 1         | 0.57%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.57%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 0.57%   |
| Intel PROSet/Wireless WiFi Software extension                                          | 1         | 0.57%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                            | 1         | 0.57%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 0.57%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.57%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 1         | 0.57%   |
| AMD SB600 IDE                                                                          | 1         | 0.57%   |
| AMD FCH IDE Controller                                                                 | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 109       | 64.88%  |
| NVMe | 40        | 23.81%  |
| IDE  | 13        | 7.74%   |
| RAID | 6         | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 112       | 84.21%  |
| AMD    | 21        | 15.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 3.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 3.01%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.26%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 2.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.26%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.5%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 1.5%    |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 1.5%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.5%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.5%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 1.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.5%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.5%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.5%    |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 1.5%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.5%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.5%    |
| Intel Pentium M processor 2.13GHz             | 1         | 0.75%   |
| Intel Pentium M processor 1.50GHz             | 1         | 0.75%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.75%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.75%   |
| Intel Pentium CPU 2127U @ 1.90GHz             | 1         | 0.75%   |
| Intel Pentium 3805U @ 1.90GHz                 | 1         | 0.75%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.75%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.75%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.75%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.75%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 0.75%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.75%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.75%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.75%   |
| Intel Core i7-3635QM CPU @ 2.40GHz            | 1         | 0.75%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.75%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.75%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 0.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.75%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.75%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.75%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 0.75%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.75%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 0.75%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 0.75%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 0.75%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.75%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i5-4288U CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 0.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 42        | 31.58%  |
| Intel Core i5                  | 37        | 27.82%  |
| Intel Core i3                  | 7         | 5.26%   |
| Intel Core 2 Duo               | 7         | 5.26%   |
| Intel Celeron                  | 6         | 4.51%   |
| AMD Ryzen 5                    | 6         | 4.51%   |
| Other                          | 3         | 2.26%   |
| Intel Pentium                  | 3         | 2.26%   |
| AMD Ryzen 7                    | 3         | 2.26%   |
| Intel Pentium M                | 2         | 1.5%    |
| Intel Celeron Dual-Core        | 2         | 1.5%    |
| AMD Ryzen 7 PRO                | 2         | 1.5%    |
| Intel Pentium Dual             | 1         | 0.75%   |
| Intel Core i9                  | 1         | 0.75%   |
| Intel Core 2                   | 1         | 0.75%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.75%   |
| AMD Ryzen 3 PRO                | 1         | 0.75%   |
| AMD E2                         | 1         | 0.75%   |
| AMD E                          | 1         | 0.75%   |
| AMD C-60                       | 1         | 0.75%   |
| AMD Athlon II Dual-Core        | 1         | 0.75%   |
| AMD Athlon 64 X2               | 1         | 0.75%   |
| AMD A8                         | 1         | 0.75%   |
| AMD A6                         | 1         | 0.75%   |
| AMD A4                         | 1         | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 69        | 51.88%  |
| 4       | 43        | 32.33%  |
| 6       | 11        | 8.27%   |
| 8       | 4         | 3.01%   |
| 1       | 4         | 3.01%   |
| Unknown | 2         | 1.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 133       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 97        | 72.39%  |
| 1       | 35        | 26.12%  |
| Unknown | 2         | 1.49%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 130       | 97.74%  |
| 32-bit         | 2         | 1.5%    |
| Unknown        | 1         | 0.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 16.06%  |
| 0x306a9    | 12        | 8.76%   |
| 0x206a7    | 12        | 8.76%   |
| 0x306c3    | 9         | 6.57%   |
| 0x806ea    | 7         | 5.11%   |
| 0x40651    | 6         | 4.38%   |
| 0x306d4    | 6         | 4.38%   |
| 0x906e9    | 5         | 3.65%   |
| 0x08600106 | 5         | 3.65%   |
| 0x806ec    | 4         | 2.92%   |
| 0x6fb      | 4         | 2.92%   |
| 0xa0652    | 3         | 2.19%   |
| 0x906ea    | 3         | 2.19%   |
| 0x806c1    | 3         | 2.19%   |
| 0x6fd      | 3         | 2.19%   |
| 0x506e3    | 3         | 2.19%   |
| 0x406e3    | 3         | 2.19%   |
| 0x1067a    | 3         | 2.19%   |
| 0x05000119 | 3         | 2.19%   |
| 0x806e9    | 2         | 1.46%   |
| 0x6d8      | 2         | 1.46%   |
| 0x30678    | 2         | 1.46%   |
| 0x20655    | 2         | 1.46%   |
| 0x08108102 | 2         | 1.46%   |
| 0x906ed    | 1         | 0.73%   |
| 0x806eb    | 1         | 0.73%   |
| 0x706a8    | 1         | 0.73%   |
| 0x706a1    | 1         | 0.73%   |
| 0x6f6      | 1         | 0.73%   |
| 0x0a50000c | 1         | 0.73%   |
| 0x08600103 | 1         | 0.73%   |
| 0x0810100b | 1         | 0.73%   |
| 0x06001119 | 1         | 0.73%   |
| 0x02000032 | 1         | 0.73%   |
| 0x01000098 | 1         | 0.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 28        | 21.05%  |
| Haswell         | 17        | 12.78%  |
| SandyBridge     | 14        | 10.53%  |
| IvyBridge       | 13        | 9.77%   |
| Core            | 8         | 6.02%   |
| Zen 2           | 7         | 5.26%   |
| Broadwell       | 7         | 5.26%   |
| Skylake         | 6         | 4.51%   |
| Westmere        | 3         | 2.26%   |
| TigerLake       | 3         | 2.26%   |
| Penryn          | 3         | 2.26%   |
| CometLake       | 3         | 2.26%   |
| Bobcat          | 3         | 2.26%   |
| Zen+            | 2         | 1.5%    |
| Zen             | 2         | 1.5%    |
| Silvermont      | 2         | 1.5%    |
| P6              | 2         | 1.5%    |
| Goldmont plus   | 2         | 1.5%    |
| Zen 3           | 1         | 0.75%   |
| Steamroller     | 1         | 0.75%   |
| Piledriver      | 1         | 0.75%   |
| K8 Hammer       | 1         | 0.75%   |
| K8 & K10 hybrid | 1         | 0.75%   |
| K10             | 1         | 0.75%   |
| Goldmont        | 1         | 0.75%   |
| Excavator       | 1         | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 104       | 56.22%  |
| Nvidia           | 53        | 28.65%  |
| AMD              | 27        | 14.59%  |
| VIA Technologies | 1         | 0.54%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 6.84%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 12        | 6.32%   |
| Intel UHD Graphics 620                                                        | 9         | 4.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 8         | 4.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 3.68%   |
| AMD Renoir                                                                    | 7         | 3.68%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 2.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 2.63%   |
| Intel HD Graphics 630                                                         | 5         | 2.63%   |
| Intel HD Graphics 5500                                                        | 5         | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 2.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 4         | 2.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 4         | 2.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 4         | 2.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 1.58%   |
| Intel HD Graphics 530                                                         | 3         | 1.58%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 1.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 1.58%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 1.58%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 1.58%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 1.05%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 1.05%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 2         | 1.05%   |
| Nvidia GP108GLM [Quadro P520]                                                 | 2         | 1.05%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 2         | 1.05%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 2         | 1.05%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 2         | 1.05%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 1.05%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 1.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 1.05%   |
| Intel HD Graphics 620                                                         | 2         | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.05%   |
| VIA Technologies K8M890CE/K8N890CE [Chrome 9]                                 | 1         | 0.53%   |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 0.53%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 0.53%   |
| Nvidia GP107M [GeForce MX150]                                                 | 1         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                   | 1         | 0.53%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 0.53%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.53%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.53%   |
| Nvidia GM108M [GeForce 920MX]                                                 | 1         | 0.53%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 0.53%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 1         | 0.53%   |
| Nvidia GM107GLM [Quadro M2000M]                                               | 1         | 0.53%   |
| Nvidia GM107GLM [Quadro M1000M]                                               | 1         | 0.53%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.53%   |
| Nvidia GK107M [GeForce GT 740M]                                               | 1         | 0.53%   |
| Nvidia GK107M [GeForce GT 650M]                                               | 1         | 0.53%   |
| Nvidia GK107GLM [Quadro K1100M]                                               | 1         | 0.53%   |
| Nvidia GK106M [GeForce GTX 770M]                                              | 1         | 0.53%   |
| Nvidia GK104M [GeForce GTX 780M]                                              | 1         | 0.53%   |
| Nvidia GK104GLM [Quadro K3100M]                                               | 1         | 0.53%   |
| Nvidia GF119M [Quadro NVS 4200M]                                              | 1         | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.53%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 41.35%  |
| Intel + Nvidia | 44        | 33.08%  |
| 1 x AMD        | 19        | 14.29%  |
| 1 x Nvidia     | 6         | 4.51%   |
| Intel + AMD    | 5         | 3.76%   |
| AMD + Nvidia   | 3         | 2.26%   |
| 1 x VIA        | 1         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 101       | 74.26%  |
| Proprietary | 33        | 24.26%  |
| Unknown     | 2         | 1.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 47.76%  |
| 1.01-2.0   | 33        | 24.63%  |
| 0.01-0.5   | 16        | 11.94%  |
| 3.01-4.0   | 11        | 8.21%   |
| 0.51-1.0   | 6         | 4.48%   |
| 5.01-6.0   | 3         | 2.24%   |
| 2.01-3.0   | 1         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 17.72%  |
| Chimei Innolux          | 26        | 16.46%  |
| LG Display              | 16        | 10.13%  |
| BOE                     | 16        | 10.13%  |
| Dell                    | 15        | 9.49%   |
| Samsung Electronics     | 12        | 7.59%   |
| Chi Mei Optoelectronics | 10        | 6.33%   |
| Sharp                   | 6         | 3.8%    |
| Lenovo                  | 5         | 3.16%   |
| Sony                    | 3         | 1.9%    |
| LG Philips              | 3         | 1.9%    |
| PANDA                   | 2         | 1.27%   |
| Hewlett-Packard         | 2         | 1.27%   |
| Goldstar                | 2         | 1.27%   |
| ViewSonic               | 1         | 0.63%   |
| Toshiba                 | 1         | 0.63%   |
| Seiko/Epson             | 1         | 0.63%   |
| Philips                 | 1         | 0.63%   |
| Lenovo Group Limited    | 1         | 0.63%   |
| KDB                     | 1         | 0.63%   |
| CSO                     | 1         | 0.63%   |
| CPT                     | 1         | 0.63%   |
| ASUSTek Computer        | 1         | 0.63%   |
| Apple                   | 1         | 0.63%   |
| Ancor Communications    | 1         | 0.63%   |
| Acer                    | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 3         | 1.83%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 1.83%   |
| Sony TV SNYDB01 1920x1080 1600x900mm 72.3-inch                            | 2         | 1.22%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 1.22%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 340x190mm 15.3-inch      | 2         | 1.22%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 1.22%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 2         | 1.22%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 1.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch  | 2         | 1.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 1.22%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 1.22%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 2         | 1.22%   |
| ViewSonic VP2030 SERIES VSC131C 1600x1200 408x306mm 20.1-inch             | 1         | 0.61%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                     | 1         | 0.61%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.61%   |
| Sharp LQ133M1JW40 SHP10CD 1920x1080 294x165mm 13.3-inch                   | 1         | 0.61%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 0.61%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                   | 1         | 0.61%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                   | 1         | 0.61%   |
| Seiko/Epson LCD Monitor 1920x1080                                         | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch      | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM030E 1680x1050 474x296mm 22.0-inch      | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch      | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch      | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch      | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3246 1366x768 293x165mm 13.2-inch      | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch      | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 1         | 0.61%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                        | 1         | 0.61%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch                   | 1         | 0.61%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                   | 1         | 0.61%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch               | 1         | 0.61%   |
| LG Philips LCD Monitor LPLB900 1280x800 330x210mm 15.4-inch               | 1         | 0.61%   |
| LG Philips LCD Monitor LPL0133 1280x800 304x190mm 14.1-inch               | 1         | 0.61%   |
| LG Display LCD Monitor LGD05E6 1920x1080 344x194mm 15.5-inch              | 1         | 0.61%   |
| LG Display LCD Monitor LGD05A2 1920x1080 309x174mm 14.0-inch              | 1         | 0.61%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 0.61%   |
| LG Display LCD Monitor LGD058B 2560x1440 309x174mm 14.0-inch              | 1         | 0.61%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 1         | 0.61%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 1         | 0.61%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch              | 1         | 0.61%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 1         | 0.61%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 1         | 0.61%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch               | 1         | 0.61%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 1         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 64        | 42.38%  |
| 1366x768 (WXGA)    | 38        | 25.17%  |
| 1600x900 (HD+)     | 11        | 7.28%   |
| 1280x800 (WXGA)    | 9         | 5.96%   |
| 3840x2160 (4K)     | 7         | 4.64%   |
| 1920x1200 (WUXGA)  | 5         | 3.31%   |
| 2560x1440 (QHD)    | 4         | 2.65%   |
| 1680x1050 (WSXGA+) | 3         | 1.99%   |
| 1280x1024 (SXGA)   | 3         | 1.99%   |
| 2560x1600          | 2         | 1.32%   |
| 3440x1440          | 1         | 0.66%   |
| 2560x1080          | 1         | 0.66%   |
| 2256x1504          | 1         | 0.66%   |
| 1600x1200          | 1         | 0.66%   |
| 1440x900 (WXGA+)   | 1         | 0.66%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 66        | 41.25%  |
| 14      | 21        | 13.13%  |
| 13      | 17        | 10.63%  |
| 17      | 11        | 6.88%   |
| 24      | 8         | 5%      |
| 12      | 7         | 4.38%   |
| 27      | 5         | 3.13%   |
| 72      | 3         | 1.88%   |
| 23      | 3         | 1.88%   |
| 22      | 3         | 1.88%   |
| 34      | 2         | 1.25%   |
| 16      | 2         | 1.25%   |
| Unknown | 2         | 1.25%   |
| 65      | 1         | 0.63%   |
| 40      | 1         | 0.63%   |
| 31      | 1         | 0.63%   |
| 29      | 1         | 0.63%   |
| 26      | 1         | 0.63%   |
| 21      | 1         | 0.63%   |
| 20      | 1         | 0.63%   |
| 19      | 1         | 0.63%   |
| 11      | 1         | 0.63%   |
| 10      | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 93        | 58.86%  |
| 201-300     | 19        | 12.03%  |
| 501-600     | 15        | 9.49%   |
| 351-400     | 13        | 8.23%   |
| 401-500     | 5         | 3.16%   |
| 601-700     | 4         | 2.53%   |
| 1501-2000   | 3         | 1.9%    |
| 701-800     | 2         | 1.27%   |
| Unknown     | 2         | 1.27%   |
| 801-900     | 1         | 0.63%   |
| 1001-1500   | 1         | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 113       | 79.58%  |
| 16/10   | 19        | 13.38%  |
| 5/4     | 2         | 1.41%   |
| 4/3     | 2         | 1.41%   |
| 3/2     | 2         | 1.41%   |
| 21/9    | 2         | 1.41%   |
| Unknown | 2         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 66        | 41.51%  |
| 81-90          | 30        | 18.87%  |
| 201-250        | 11        | 6.92%   |
| 121-130        | 9         | 5.66%   |
| 71-80          | 8         | 5.03%   |
| 61-70          | 7         | 4.4%    |
| 301-350        | 6         | 3.77%   |
| More than 1000 | 4         | 2.52%   |
| 351-500        | 4         | 2.52%   |
| 251-300        | 3         | 1.89%   |
| 151-200        | 2         | 1.26%   |
| 111-120        | 2         | 1.26%   |
| Unknown        | 2         | 1.26%   |
| 51-60          | 1         | 0.63%   |
| 41-50          | 1         | 0.63%   |
| 141-150        | 1         | 0.63%   |
| 131-140        | 1         | 0.63%   |
| 501-1000       | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 65        | 41.67%  |
| 101-120       | 42        | 26.92%  |
| 51-100        | 28        | 17.95%  |
| 161-240       | 11        | 7.05%   |
| More than 240 | 4         | 2.56%   |
| 1-50          | 4         | 2.56%   |
| Unknown       | 2         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 104       | 76.47%  |
| 2     | 25        | 18.38%  |
| 3     | 6         | 4.41%   |
| 0     | 1         | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 82        | 38.5%   |
| Realtek Semiconductor             | 60        | 28.17%  |
| Qualcomm Atheros                  | 32        | 15.02%  |
| Broadcom                          | 11        | 5.16%   |
| Ralink                            | 4         | 1.88%   |
| Fibocom                           | 3         | 1.41%   |
| TP-Link                           | 2         | 0.94%   |
| Sierra Wireless                   | 2         | 0.94%   |
| Lenovo                            | 2         | 0.94%   |
| Huawei Technologies               | 2         | 0.94%   |
| Hewlett-Packard                   | 2         | 0.94%   |
| Ericsson Business Mobile Networks | 2         | 0.94%   |
| VIA Technologies                  | 1         | 0.47%   |
| Van Ooijen Technische Informatica | 1         | 0.47%   |
| MediaTek                          | 1         | 0.47%   |
| Marvell Technology Group          | 1         | 0.47%   |
| JMicron Technology                | 1         | 0.47%   |
| DisplayLink                       | 1         | 0.47%   |
| Broadcom Limited                  | 1         | 0.47%   |
| ASUSTek Computer                  | 1         | 0.47%   |
| ASIX Electronics                  | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 32        | 11.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 16        | 5.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 4.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 3.33%   |
| Intel Wireless 8265 / 8275                                              | 8         | 2.96%   |
| Intel Wireless 7265                                                     | 7         | 2.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.22%   |
| Intel Wireless 7260                                                     | 6         | 2.22%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                                   | 5         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.48%   |
| Intel Wireless 8260                                                     | 4         | 1.48%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.48%   |
| Intel 82566MM Gigabit Network Connection                                | 4         | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.11%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 1.11%   |
| Intel Wireless 3160                                                     | 3         | 1.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.11%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 1.11%   |
| Intel Ethernet Connection (6) I219-V                                    | 3         | 1.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.11%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.11%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.74%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 2         | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.74%   |
| Lenovo ThinkPad TBT3 LAN                                                | 2         | 0.74%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.74%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.74%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 2         | 0.74%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.74%   |
| Ericsson Business Mobile Networks F5521gw                               | 2         | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 1         | 0.37%   |
| Van Ooijen Technische Informatica CDC-ACM class devices (modems)        | 1         | 0.37%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.37%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.37%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.37%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.37%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 81        | 57.45%  |
| Qualcomm Atheros      | 24        | 17.02%  |
| Realtek Semiconductor | 14        | 9.93%   |
| Broadcom              | 8         | 5.67%   |
| Ralink                | 4         | 2.84%   |
| Fibocom               | 3         | 2.13%   |
| TP-Link               | 2         | 1.42%   |
| Sierra Wireless       | 2         | 1.42%   |
| MediaTek              | 1         | 0.71%   |
| Hewlett-Packard       | 1         | 0.71%   |
| Broadcom Limited      | 1         | 0.71%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 7.8%    |
| Intel Wireless 8265 / 8275                                              | 8         | 5.67%   |
| Intel Wireless 7265                                                     | 7         | 4.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 4.26%   |
| Intel Wireless 7260                                                     | 6         | 4.26%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 4.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 3.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.84%   |
| Intel Wireless 8260                                                     | 4         | 2.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.13%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.13%   |
| Intel Wireless 3160                                                     | 3         | 2.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 2.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 2.13%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 2.13%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 2.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.42%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.42%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.42%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.42%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.42%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.71%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.71%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.71%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.71%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.71%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.71%   |
| Intel Wireless 3165                                                     | 1         | 0.71%   |
| Intel WiFi Link 5100                                                    | 1         | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.71%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.71%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.71%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.71%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 0.71%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 0.71%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 0.71%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 0.71%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 1         | 0.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 0.71%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.71%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 54        | 44.63%  |
| Intel                    | 40        | 33.06%  |
| Qualcomm Atheros         | 14        | 11.57%  |
| Broadcom                 | 5         | 4.13%   |
| Lenovo                   | 2         | 1.65%   |
| VIA Technologies         | 1         | 0.83%   |
| Marvell Technology Group | 1         | 0.83%   |
| JMicron Technology       | 1         | 0.83%   |
| DisplayLink              | 1         | 0.83%   |
| ASUSTek Computer         | 1         | 0.83%   |
| ASIX Electronics         | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 26.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 13.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 7.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 4.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 4.13%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 3.31%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 3.31%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 2.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2.48%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.48%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.65%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 1.65%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.65%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.83%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.83%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.83%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.83%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.83%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.83%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.83%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.83%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.83%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.83%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.83%   |
| Broadcom NetXtreme BCM5705M_2 Gigabit Ethernet                    | 1         | 0.83%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.83%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.83%   |
| ASUS Android                                                      | 1         | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 133       | 51.75%  |
| Ethernet | 116       | 45.14%  |
| Modem    | 8         | 3.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 109       | 77.86%  |
| Ethernet | 31        | 22.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 109       | 81.95%  |
| 1     | 22        | 16.54%  |
| 3     | 1         | 0.75%   |
| 0     | 1         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 123       | 91.11%  |
| Yes  | 12        | 8.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 51.92%  |
| Broadcom                        | 11        | 10.58%  |
| Qualcomm Atheros Communications | 10        | 9.62%   |
| Realtek Semiconductor           | 7         | 6.73%   |
| IMC Networks                    | 7         | 6.73%   |
| Hewlett-Packard                 | 4         | 3.85%   |
| Cambridge Silicon Radio         | 3         | 2.88%   |
| Realtek                         | 2         | 1.92%   |
| Toshiba                         | 1         | 0.96%   |
| Ralink                          | 1         | 0.96%   |
| Lite-On Technology              | 1         | 0.96%   |
| Foxconn / Hon Hai               | 1         | 0.96%   |
| Dell                            | 1         | 0.96%   |
| Apple                           | 1         | 0.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 29        | 27.88%  |
| Intel AX201 Bluetooth                               | 7         | 6.73%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 5.77%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 4.81%   |
| Intel AX200 Bluetooth                               | 5         | 4.81%   |
| IMC Networks Bluetooth Device                       | 5         | 4.81%   |
| Realtek Bluetooth Radio                             | 4         | 3.85%   |
| Intel Bluetooth Device                              | 3         | 2.88%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.88%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 2.88%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.92%   |
| Realtek Bluetooth Radio                             | 2         | 1.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.92%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.92%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 1.92%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.92%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.92%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.96%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.96%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.96%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.96%   |
| Lite-On Bluetooth Device                            | 1         | 0.96%   |
| Intel AX210 Bluetooth                               | 1         | 0.96%   |
| IMC Networks BCM20702A0                             | 1         | 0.96%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.96%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.96%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.96%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.96%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.96%   |
| Apple Bluetooth Host Controller                     | 1         | 0.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 111       | 68.1%   |
| AMD                   | 23        | 14.11%  |
| Nvidia                | 16        | 9.82%   |
| Lenovo                | 3         | 1.84%   |
| Realtek Semiconductor | 2         | 1.23%   |
| VIA Technologies      | 1         | 0.61%   |
| Texas Instruments     | 1         | 0.61%   |
| Roland                | 1         | 0.61%   |
| Micronas              | 1         | 0.61%   |
| Mark of the Unicorn   | 1         | 0.61%   |
| Logitech              | 1         | 0.61%   |
| JMTek                 | 1         | 0.61%   |
| C-Media Electronics   | 1         | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 14        | 7.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 7.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 6.53%   |
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 6.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 5.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 3.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 3.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 3.52%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 3.52%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 3.52%   |
| Intel CM238 HD Audio Controller                                            | 5         | 2.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 2.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.01%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 2.01%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 2.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.01%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.51%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.51%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.51%   |
| Realtek Semiconductor USB Audio                                            | 2         | 1.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.01%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.01%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.01%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 2         | 1.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.01%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2         | 1.01%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.01%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.5%    |
| Texas Instruments SMSL AD18 AMP                                            | 1         | 0.5%    |
| Roland DUO-CAPTURE                                                         | 1         | 0.5%    |
| Nvidia stereo controller                                                   | 1         | 0.5%    |
| Nvidia High Definition Audio Controller                                    | 1         | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.5%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.5%    |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.5%    |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.5%    |
| Micronas BLUE USB Audio 2.0                                                | 1         | 0.5%    |
| Mark of the Unicorn M Series                                               | 1         | 0.5%    |
| Logitech Headset H390                                                      | 1         | 0.5%    |
| Lenovo ThinkPad Dock USB Audio                                             | 1         | 0.5%    |
| JMTek USB PnP Audio Device                                                 | 1         | 0.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.5%    |
| C-Media Electronics USB Audio Device                                       | 1         | 0.5%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.5%    |
| AMD Trinity HDMI Audio Controller                                          | 1         | 0.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 0.5%    |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                            | 1         | 0.5%    |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 0.5%    |
| AMD High Definition Audio Controller                                       | 1         | 0.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 31.4%   |
| SK hynix            | 19        | 22.09%  |
| Micron Technology   | 14        | 16.28%  |
| Kingston            | 8         | 9.3%    |
| Crucial             | 5         | 5.81%   |
| Ramaxel Technology  | 3         | 3.49%   |
| Unknown             | 2         | 2.33%   |
| A-DATA Technology   | 2         | 2.33%   |
| Unknown (ABCD)      | 1         | 1.16%   |
| Unifosa             | 1         | 1.16%   |
| Nanya Technology    | 1         | 1.16%   |
| G.Skill             | 1         | 1.16%   |
| Elpida              | 1         | 1.16%   |
| ASint Technology    | 1         | 1.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 3         | 3.23%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                        | 2         | 2.15%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 2         | 2.15%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                        | 2         | 2.15%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                       | 2         | 2.15%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s                     | 2         | 2.15%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s                        | 2         | 2.15%   |
| Unknown RAM Module 512MB SODIMM DDR2                                         | 1         | 1.08%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                                | 1         | 1.08%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                        | 1         | 1.08%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s             | 1         | 1.08%   |
| Unifosa RAM GU332G0AJEPR8H2L 2048MB SODIMM DDR2 667MT/s                      | 1         | 1.08%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                              | 1         | 1.08%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s                        | 1         | 1.08%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s                         | 1         | 1.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.08%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s                    | 1         | 1.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                       | 1         | 1.08%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s                    | 1         | 1.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.08%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 1         | 1.08%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s                    | 1         | 1.08%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                       | 1         | 1.08%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 1         | 1.08%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s                      | 1         | 1.08%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s                      | 1         | 1.08%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 1.08%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                       | 1         | 1.08%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 1.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                       | 1         | 1.08%   |
| SK hynix RAM 5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A5A 4096MB SODIMM DDR2 800MT/s | 1         | 1.08%   |
| SK hynix RAM 262626262626262626262626262626262626 4096MB SODIMM DDR2 800MT/s | 1         | 1.08%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2400MT/s                              | 1         | 1.08%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                        | 1         | 1.08%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.08%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                        | 1         | 1.08%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s                        | 1         | 1.08%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s                     | 1         | 1.08%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                        | 1         | 1.08%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s                       | 1         | 1.08%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s                    | 1         | 1.08%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s                       | 1         | 1.08%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                        | 1         | 1.08%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                        | 1         | 1.08%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                        | 1         | 1.08%   |
| Samsung RAM M471A1K43BB1-CPB 8GB SODIMM DDR4 2133MT/s                        | 1         | 1.08%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s                     | 1         | 1.08%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.08%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                   | 1         | 1.08%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.08%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4096MB SODIMM DDR3 1334MT/s                      | 1         | 1.08%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s               | 1         | 1.08%   |
| Micron RAM Module 8192MB SODIMM DDR3 1600MT/s                                | 1         | 1.08%   |
| Micron RAM Module 16384MB SODIMM DDR4 2400MT/s                               | 1         | 1.08%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.08%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                         | 1         | 1.08%   |
| Micron RAM 8ATF1G64HZ-2G6J1 8GB SODIMM DDR4 2667MT/s                         | 1         | 1.08%   |
| Micron RAM 8ATF1G64HZ-2G6D1 8GB SODIMM DDR4 2667MT/s                         | 1         | 1.08%   |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s                | 1         | 1.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 31        | 44.93%  |
| DDR3   | 28        | 40.58%  |
| DDR2   | 5         | 7.25%   |
| LPDDR4 | 2         | 2.9%    |
| SDRAM  | 1         | 1.45%   |
| LPDDR3 | 1         | 1.45%   |
| DDR    | 1         | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 66        | 97.06%  |
| Row Of Chips | 2         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 28        | 36.36%  |
| 4096  | 27        | 35.06%  |
| 16384 | 9         | 11.69%  |
| 2048  | 7         | 9.09%   |
| 1024  | 3         | 3.9%    |
| 32768 | 2         | 2.6%    |
| 512   | 1         | 1.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 20        | 25.64%  |
| 1600    | 18        | 23.08%  |
| 3200    | 9         | 11.54%  |
| 1334    | 6         | 7.69%   |
| 1333    | 6         | 7.69%   |
| 2400    | 4         | 5.13%   |
| 2133    | 3         | 3.85%   |
| 1067    | 3         | 3.85%   |
| 667     | 2         | 2.56%   |
| 4267    | 1         | 1.28%   |
| 4199    | 1         | 1.28%   |
| 3266    | 1         | 1.28%   |
| 975     | 1         | 1.28%   |
| 800     | 1         | 1.28%   |
| 400     | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

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
| Chicony Electronics                    | 28        | 24.35%  |
| Microdia                               | 14        | 12.17%  |
| Realtek Semiconductor                  | 11        | 9.57%   |
| Acer                                   | 11        | 9.57%   |
| Sunplus Innovation Technology          | 10        | 8.7%    |
| IMC Networks                           | 10        | 8.7%    |
| Silicon Motion                         | 5         | 4.35%   |
| Lite-On Technology                     | 5         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.35%   |
| Suyin                                  | 4         | 3.48%   |
| Syntek                                 | 2         | 1.74%   |
| Quanta                                 | 2         | 1.74%   |
| Luxvisions Innotech Limited            | 2         | 1.74%   |
| Logitech                               | 2         | 1.74%   |
| Lenovo                                 | 1         | 0.87%   |
| Importek                               | 1         | 0.87%   |
| Huddly                                 | 1         | 0.87%   |
| Apple                                  | 1         | 0.87%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 7.69%   |
| Lite-On Integrated Camera                               | 4         | 3.42%   |
| Chicony Integrated Camera                               | 4         | 3.42%   |
| Realtek USB Camera                                      | 3         | 2.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 2.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 2.56%   |
| Chicony Integrated HP HD Webcam                         | 3         | 2.56%   |
| Acer Integrated Camera                                  | 3         | 2.56%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.71%   |
| Sunplus ASUS USB2.0 Webcam                              | 2         | 1.71%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.71%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.71%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.71%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.71%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.71%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.71%   |
| IMC Networks Integrated Camera                          | 2         | 1.71%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.71%   |
| Chicony ThinkPad T490 Webcam                            | 2         | 1.71%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.71%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.71%   |
| Chicony HP HD Webcam                                    | 2         | 1.71%   |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.85%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.85%   |
| Suyin USB Webcam                                        | 1         | 0.85%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.85%   |
| Suyin HD WebCam                                         | 1         | 0.85%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.85%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.85%   |
| Sunplus Integrated Webcam                               | 1         | 0.85%   |
| Sunplus HP Wide Vision HD                               | 1         | 0.85%   |
| Sunplus HP Universal Camera                             | 1         | 0.85%   |
| Sunplus HD Webcam                                       | 1         | 0.85%   |
| Sunplus Dell HD Webcam                                  | 1         | 0.85%   |
| Silicon Motion WebCam SC-13HDL11431N                    | 1         | 0.85%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 1         | 0.85%   |
| Silicon Motion WebCam SC-10HDD12636N                    | 1         | 0.85%   |
| Realtek Integrated Camera                               | 1         | 0.85%   |
| Realtek EasyCamera                                      | 1         | 0.85%   |
| Quanta HP Webcam                                        | 1         | 0.85%   |
| Quanta HP HD Camera                                     | 1         | 0.85%   |
| Microdia Webcam SC-10HDD12636P                          | 1         | 0.85%   |
| Microdia Sonix USB 2.0 Camera                           | 1         | 0.85%   |
| Microdia Laptop_Integrated_Webcam_FHD                   | 1         | 0.85%   |
| Logitech Webcam C270                                    | 1         | 0.85%   |
| Logitech HD Pro Webcam C920                             | 1         | 0.85%   |
| Lite-On HP HD Webcam                                    | 1         | 0.85%   |
| Lenovo Integrated Webcam [R5U877]                       | 1         | 0.85%   |
| Importek TOSHIBA Web Camera - HD                        | 1         | 0.85%   |
| IMC Networks VGA UVC WebCam                             | 1         | 0.85%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 1         | 0.85%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 1         | 0.85%   |
| IMC Networks Lenovo EasyCamera                          | 1         | 0.85%   |
| IMC Networks EasyCamera                                 | 1         | 0.85%   |
| Huddly GO                                               | 1         | 0.85%   |
| Chicony USB2.0 0.3M UVC WebCam                          | 1         | 0.85%   |
| Chicony USB 2.0 Webcam Device                           | 1         | 0.85%   |
| Chicony Lenovo EasyCamera                               | 1         | 0.85%   |
| Chicony Integrated IR Camera                            | 1         | 0.85%   |
| Chicony HP Integrated Webcam                            | 1         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 44.12%  |
| Synaptics                  | 7         | 20.59%  |
| Upek                       | 4         | 11.76%  |
| STMicroelectronics         | 4         | 11.76%  |
| Shenzhen Goodix Technology | 2         | 5.88%   |
| Elan Microelectronics      | 1         | 2.94%   |
| AuthenTec                  | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 14.71%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 11.76%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 11.76%  |
| STMicroelectronics Fingerprint Reader                  | 4         | 11.76%  |
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 8.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 3         | 8.82%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 5.88%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 5.88%   |
| Shenzhen Goodix FingerPrint                            | 2         | 5.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.94%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 2.94%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.94%   |
| Elan ELAN:Fingerprint                                  | 1         | 2.94%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1         | 2.94%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 14        | 51.85%  |
| OmniKey     | 6         | 22.22%  |
| Lenovo      | 3         | 11.11%  |
| Broadcom    | 3         | 11.11%  |
| O2 Micro    | 1         | 3.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader  | 14        | 51.85%  |
| OmniKey CardMan 4321                 | 3         | 11.11%  |
| OmniKey CardMan 1021                 | 3         | 11.11%  |
| Lenovo Integrated Smart Card Reader  | 3         | 11.11%  |
| Broadcom 58200                       | 3         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 3.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 76        | 56.3%   |
| 1     | 42        | 31.11%  |
| 2     | 17        | 12.59%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 34        | 45.33%  |
| Graphics card            | 16        | 21.33%  |
| Chipcard                 | 15        | 20%     |
| Net/wireless             | 4         | 5.33%   |
| Camera                   | 2         | 2.67%   |
| Net/ethernet             | 1         | 1.33%   |
| Modem                    | 1         | 1.33%   |
| Communication controller | 1         | 1.33%   |
| Bluetooth                | 1         | 1.33%   |

