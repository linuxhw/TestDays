Elementary 6.1 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

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

Total: 390

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6320              | [34270898c6](https://linux-hardware.org/?probe=34270898c6) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | [04487d99ff](https://linux-hardware.org/?probe=04487d99ff) | Jul 30, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| Dell          | Latitude D630               | [37250474ae](https://linux-hardware.org/?probe=37250474ae) | Jul 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [af8fd9ae70](https://linux-hardware.org/?probe=af8fd9ae70) | Jul 29, 2022 |
| ASUSTek       | K43E                        | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| Dell          | Latitude D630               | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | Latitude E6320              | [a5b77aa0e9](https://linux-hardware.org/?probe=a5b77aa0e9) | Jul 28, 2022 |
| Dell          | Latitude 3190               | [36027c80d2](https://linux-hardware.org/?probe=36027c80d2) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [d9a5e0b7e6](https://linux-hardware.org/?probe=d9a5e0b7e6) | Jul 27, 2022 |
| HP            | Pavilion g4                 | [c9aa5e235c](https://linux-hardware.org/?probe=c9aa5e235c) | Jul 27, 2022 |
| HP            | 255 G7 Notebook PC          | [8173942fbb](https://linux-hardware.org/?probe=8173942fbb) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | [f4026901c2](https://linux-hardware.org/?probe=f4026901c2) | Jul 25, 2022 |
| HP            | Pavilion g6                 | [73061b2ed5](https://linux-hardware.org/?probe=73061b2ed5) | Jul 23, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [810b379dac](https://linux-hardware.org/?probe=810b379dac) | Jul 19, 2022 |
| HUAWEI        | HLYL-WXX9                   | [3831dd717e](https://linux-hardware.org/?probe=3831dd717e) | Jul 19, 2022 |
| Apple         | MacBookPro8,1               | [d5b50db42e](https://linux-hardware.org/?probe=d5b50db42e) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [54152fdf16](https://linux-hardware.org/?probe=54152fdf16) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Apple         | MacBookPro8,1               | [21c49763f5](https://linux-hardware.org/?probe=21c49763f5) | Jul 17, 2022 |
| HP            | EliteBook 8460p             | [b1c5cb2096](https://linux-hardware.org/?probe=b1c5cb2096) | Jul 12, 2022 |
| HP            | Notebook                    | [afaaed48c7](https://linux-hardware.org/?probe=afaaed48c7) | Jul 10, 2022 |
| Acer          | Aspire 1830T                | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| Acer          | Aspire AV15-51              | [1a880a89af](https://linux-hardware.org/?probe=1a880a89af) | Jul 09, 2022 |
| Acer          | Aspire V3-771               | [e8488fb0e2](https://linux-hardware.org/?probe=e8488fb0e2) | Jul 07, 2022 |
| HP            | Notebook                    | [2bf65688ab](https://linux-hardware.org/?probe=2bf65688ab) | Jul 05, 2022 |
| Dell          | Inspiron 3593               | [d34d56c473](https://linux-hardware.org/?probe=d34d56c473) | Jul 05, 2022 |
| HP            | Laptop 15-dy1xxx            | [3fcdd6c039](https://linux-hardware.org/?probe=3fcdd6c039) | Jul 03, 2022 |
| Dell          | XPS 15 9500                 | [7df8533350](https://linux-hardware.org/?probe=7df8533350) | Jul 03, 2022 |
| ASUSTek       | N56VB                       | [88d34c06f3](https://linux-hardware.org/?probe=88d34c06f3) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e13cada6ae](https://linux-hardware.org/?probe=e13cada6ae) | Jul 02, 2022 |
| ASUSTek       | X553MA                      | [804bbd8147](https://linux-hardware.org/?probe=804bbd8147) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | [9fe936cec8](https://linux-hardware.org/?probe=9fe936cec8) | Jun 30, 2022 |
| Dell          | Inspiron 5537               | [9758b4dcff](https://linux-hardware.org/?probe=9758b4dcff) | Jun 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| Apple         | MacBookPro14,2              | [7fe621e5a7](https://linux-hardware.org/?probe=7fe621e5a7) | Jun 27, 2022 |
| Compaq        | Presario CQ-23              | [f55fd14f61](https://linux-hardware.org/?probe=f55fd14f61) | Jun 26, 2022 |
| ASUSTek       | UX303LAB                    | [ae3becae01](https://linux-hardware.org/?probe=ae3becae01) | Jun 24, 2022 |
| HP            | Pavilion g4                 | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Alienware     | m17 R3                      | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| Dell          | Latitude E5510              | [1f6cc92f98](https://linux-hardware.org/?probe=1f6cc92f98) | Jun 18, 2022 |
| HP            | EliteBook 2170p             | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| HP            | ProBook 455R G6             | [31b94c71c7](https://linux-hardware.org/?probe=31b94c71c7) | Jun 16, 2022 |
| HP            | ProBook 455R G6             | [39d04d1188](https://linux-hardware.org/?probe=39d04d1188) | Jun 16, 2022 |
| Samsung       | Lumpy                       | [50dad22fb3](https://linux-hardware.org/?probe=50dad22fb3) | Jun 15, 2022 |
| ASUSTek       | GR8                         | [3cdc341eda](https://linux-hardware.org/?probe=3cdc341eda) | Jun 15, 2022 |
| Samsung       | Lumpy                       | [4137bf9757](https://linux-hardware.org/?probe=4137bf9757) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Apple         | MacBook4,1                  | [83cac56441](https://linux-hardware.org/?probe=83cac56441) | Jun 13, 2022 |
| HP            | ProBook 4540s               | [6688afd4f5](https://linux-hardware.org/?probe=6688afd4f5) | Jun 11, 2022 |
| Acer          | Aspire A315-21              | [9840a70112](https://linux-hardware.org/?probe=9840a70112) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [0ec841e188](https://linux-hardware.org/?probe=0ec841e188) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [5768dfe23f](https://linux-hardware.org/?probe=5768dfe23f) | Jun 11, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c76f63fb68](https://linux-hardware.org/?probe=c76f63fb68) | Jun 10, 2022 |
| HP            | ProBook 4540s               | [d0a6dcaa92](https://linux-hardware.org/?probe=d0a6dcaa92) | Jun 09, 2022 |
| Acer          | Aspire A315-21              | [224023dfd2](https://linux-hardware.org/?probe=224023dfd2) | Jun 08, 2022 |
| HP            | Notebook                    | [f07183fab5](https://linux-hardware.org/?probe=f07183fab5) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| HP            | ProBook 4540s               | [b74c4304e9](https://linux-hardware.org/?probe=b74c4304e9) | Jun 05, 2022 |
| Apple         | MacBookAir7,2               | [9de74ba486](https://linux-hardware.org/?probe=9de74ba486) | Jun 04, 2022 |
| Apple         | MacBookAir7,2               | [eb704f99ee](https://linux-hardware.org/?probe=eb704f99ee) | Jun 04, 2022 |
| Apple         | MacBookAir4,2               | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| HP            | ProBook 4540s               | [da53c77e1a](https://linux-hardware.org/?probe=da53c77e1a) | Jun 02, 2022 |
| Samsung       | 300E5M/300E5L               | [baa12d722c](https://linux-hardware.org/?probe=baa12d722c) | Jun 01, 2022 |
| Dell          | XPS 13 9343                 | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| HUAWEI        | MACHD-WXX9                  | [6cc36ec0ae](https://linux-hardware.org/?probe=6cc36ec0ae) | May 27, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [50f70bc9af](https://linux-hardware.org/?probe=50f70bc9af) | May 27, 2022 |
| ASUSTek       | X550CA                      | [6789d8dad5](https://linux-hardware.org/?probe=6789d8dad5) | May 26, 2022 |
| AMI           | Intel                       | [ee3b1abf63](https://linux-hardware.org/?probe=ee3b1abf63) | May 25, 2022 |
| Acer          | Swift SF114-32              | [601f82b2dd](https://linux-hardware.org/?probe=601f82b2dd) | May 23, 2022 |
| Apple         | MacBook4,1                  | [27f751618e](https://linux-hardware.org/?probe=27f751618e) | May 22, 2022 |
| HP            | ProBook 6550b               | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| AMI           | Intel                       | [6c571e79d0](https://linux-hardware.org/?probe=6c571e79d0) | May 21, 2022 |
| eMachines     | E525                        | [ca296b06c9](https://linux-hardware.org/?probe=ca296b06c9) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| Sony          | VPCEB23FM                   | [4d73e73cf8](https://linux-hardware.org/?probe=4d73e73cf8) | May 17, 2022 |
| Sony          | VPCEB23FM                   | [07d2cadefb](https://linux-hardware.org/?probe=07d2cadefb) | May 17, 2022 |
| Samsung       | Lumpy                       | [84a78226dd](https://linux-hardware.org/?probe=84a78226dd) | May 16, 2022 |
| HP            | ENVY 14                     | [9fe635b800](https://linux-hardware.org/?probe=9fe635b800) | May 15, 2022 |
| ASUSTek       | K55A                        | [3391d004a7](https://linux-hardware.org/?probe=3391d004a7) | May 15, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c0e150d349](https://linux-hardware.org/?probe=c0e150d349) | May 13, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [919200b122](https://linux-hardware.org/?probe=919200b122) | May 13, 2022 |
| ASUSTek       | UX310UQK                    | [1af1efeb46](https://linux-hardware.org/?probe=1af1efeb46) | May 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [d5df500fa3](https://linux-hardware.org/?probe=d5df500fa3) | May 10, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | ProBook 4510s               | [1464ea43d3](https://linux-hardware.org/?probe=1464ea43d3) | May 09, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [b726ded078](https://linux-hardware.org/?probe=b726ded078) | May 08, 2022 |
| Apple         | MacBookPro8,2               | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| eMachines     | E525                        | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Dell          | Inspiron 7720               | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| HP            | Pavilion 17                 | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X202E                       | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| Acer          | Aspire E5-411G              | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| Avell High... | B.ON                        | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| HP            | Pavilion 17                 | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [c12f5ae663](https://linux-hardware.org/?probe=c12f5ae663) | Apr 28, 2022 |
| HP            | EliteBook 840 G1            | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| Lenovo        | ThinkPad T420 41786VU       | [e2b4c2327b](https://linux-hardware.org/?probe=e2b4c2327b) | Apr 25, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| Dell          | Latitude 3120               | [78f0703e75](https://linux-hardware.org/?probe=78f0703e75) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [2f497982cd](https://linux-hardware.org/?probe=2f497982cd) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HP            | Pavilion g6                 | [63f6b73d50](https://linux-hardware.org/?probe=63f6b73d50) | Apr 21, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [d3d2e2fe8a](https://linux-hardware.org/?probe=d3d2e2fe8a) | Apr 18, 2022 |
| HP            | ProBook 6440b               | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Lenovo        | ThinkPad W541 20EGS0UB03    | [f566cb7f4c](https://linux-hardware.org/?probe=f566cb7f4c) | Apr 14, 2022 |
| HP            | ProBook 440 G7              | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| Acer          | Aspire E5-575G              | [07bdcd6978](https://linux-hardware.org/?probe=07bdcd6978) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [379db407c7](https://linux-hardware.org/?probe=379db407c7) | Apr 10, 2022 |
| HP            | Pavilion 13 x360 PC         | [3abf9847e4](https://linux-hardware.org/?probe=3abf9847e4) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| Apple         | MacBookAir6,2               | [84c694e881](https://linux-hardware.org/?probe=84c694e881) | Apr 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [fd62bf7f91](https://linux-hardware.org/?probe=fd62bf7f91) | Apr 05, 2022 |
| Dell          | Latitude 5410               | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| Apple         | MacBookAir6,2               | [656e7d1b73](https://linux-hardware.org/?probe=656e7d1b73) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| HP            | Notebook                    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Apple         | MacBookAir4,2               | [7fc2cd808d](https://linux-hardware.org/?probe=7fc2cd808d) | Apr 02, 2022 |
| Dell          | Vostro A860                 | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [9375dd090a](https://linux-hardware.org/?probe=9375dd090a) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [ab016f94d5](https://linux-hardware.org/?probe=ab016f94d5) | Apr 01, 2022 |
| HP            | EliteBook 8730w             | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| ASUSTek       | UL80VT                      | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Acer          | Aspire ES1-531              | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Toshiba       | Satellite C70D-A            | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| Toshiba       | Satellite L50D-C            | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Dell          | Inspiron MM061              | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| Sony          | SVP1321B4E                  | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Apple         | MacBookAir7,1               | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| Acer          | Aspire A315-21G             | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [7f9721781e](https://linux-hardware.org/?probe=7f9721781e) | Mar 12, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [bc5d95b759](https://linux-hardware.org/?probe=bc5d95b759) | Mar 12, 2022 |
| Teclast       | F15S                        | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASUSTek       | X200CA                      | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [c3e1baf45a](https://linux-hardware.org/?probe=c3e1baf45a) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [caa5c3eef1](https://linux-hardware.org/?probe=caa5c3eef1) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| Lenovo        | IdeaPad Y580                | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| Acer          | Nitro AN517-52              | [4576110ce4](https://linux-hardware.org/?probe=4576110ce4) | Mar 05, 2022 |
| HUAWEI        | MACHD-WXX9                  | [707b59278e](https://linux-hardware.org/?probe=707b59278e) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| HP            | ProBook 450 G7              | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | GL753VE                     | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| Packard Be... | EasyNote LS11HR             | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | X540SA                      | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| Dell          | Precision 7720              | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Google        | Lulu                        | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Sony          | SVE15115EN                  | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| Apple         | MacBookAir4,2               | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| Timi          | TM1613                      | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Apple         | MacBookPro6,2               | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| Dell          | Inspiron 15-3567            | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| ASUSTek       | K95VJ                       | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Razer         | Blade Stealth               | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| ASUSTek       | X555LN                      | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| Lenovo        | G550 20023                  | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| HP            | ProBook 4540s               | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Apple         | MacBookPro8,2               | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| Dell          | Latitude E5400              | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Star Labs     | StarBook                    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| MSI           | GF63 Thin 9SCSR             | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Timi          | TM1613                      | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| ASUSTek       | E202SA                      | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| Wortmann      | 1220729_1470271             | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| Dell          | Latitude 3580               | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| Dell          | Inspiron 5555               | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Lenovo        | V14-ADA 82C6                | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.11.0-43-generic          | 69        | 22.04%  |
| 5.13.0-28-generic          | 32        | 10.22%  |
| 5.13.0-30-generic          | 28        | 8.95%   |
| 5.13.0-27-generic          | 24        | 7.67%   |
| 5.15.0-41-generic          | 17        | 5.43%   |
| 5.13.0-39-generic          | 16        | 5.11%   |
| 5.13.0-40-generic          | 15        | 4.79%   |
| 5.13.0-35-generic          | 13        | 4.15%   |
| 5.11.0-44-generic          | 13        | 4.15%   |
| 5.13.0-37-generic          | 12        | 3.83%   |
| 5.13.0-52-generic          | 10        | 3.19%   |
| 5.13.0-41-generic          | 10        | 3.19%   |
| 5.11.0-46-generic          | 10        | 3.19%   |
| 5.13.0-51-generic          | 8         | 2.56%   |
| 5.13.0-44-generic          | 7         | 2.24%   |
| 5.13.0-48-generic          | 6         | 1.92%   |
| 5.11.0-41-generic          | 4         | 1.28%   |
| 5.13.0-25-generic          | 2         | 0.64%   |
| 5.11.0-40-generic          | 2         | 0.64%   |
| 5.8.0-50-generic           | 1         | 0.32%   |
| 5.4.0-122-generic          | 1         | 0.32%   |
| 5.18.3-051803-generic      | 1         | 0.32%   |
| 5.16.16-051616-generic     | 1         | 0.32%   |
| 5.16.10-051610-generic     | 1         | 0.32%   |
| 5.16.0-13.4-liquorix-amd64 | 1         | 0.32%   |
| 5.15.36-xanmod1            | 1         | 0.32%   |
| 5.15.3-xanmod1             | 1         | 0.32%   |
| 5.15.21-051521-generic     | 1         | 0.32%   |
| 5.15.13-xanmod1            | 1         | 0.32%   |
| 5.15.12-xanmod1-tt         | 1         | 0.32%   |
| 5.15.11-t2-big-sur         | 1         | 0.32%   |
| 5.14.10-051410-generic     | 1         | 0.32%   |
| 5.14.0-1029-oem            | 1         | 0.32%   |
| 5.14.0-1011-oem            | 1         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.0  | 172       | 56.95%  |
| 5.11.0  | 98        | 32.45%  |
| 5.15.0  | 17        | 5.63%   |
| 5.14.0  | 2         | 0.66%   |
| 5.8.0   | 1         | 0.33%   |
| 5.4.0   | 1         | 0.33%   |
| 5.18.3  | 1         | 0.33%   |
| 5.16.16 | 1         | 0.33%   |
| 5.16.10 | 1         | 0.33%   |
| 5.16.0  | 1         | 0.33%   |
| 5.15.36 | 1         | 0.33%   |
| 5.15.3  | 1         | 0.33%   |
| 5.15.21 | 1         | 0.33%   |
| 5.15.13 | 1         | 0.33%   |
| 5.15.12 | 1         | 0.33%   |
| 5.15.11 | 1         | 0.33%   |
| 5.14.10 | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13    | 172       | 57.14%  |
| 5.11    | 98        | 32.56%  |
| 5.15    | 23        | 7.64%   |
| 5.14    | 3         | 1%      |
| 5.16    | 2         | 0.66%   |
| 5.8     | 1         | 0.33%   |
| 5.4     | 1         | 0.33%   |
| 5.18    | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 298       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 297       | 99.66%  |
| Unknown  | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 298       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 239       | 79.93%  |
| LightDM | 59        | 19.73%  |
| GDM     | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 136       | 45.64%  |
| de_DE   | 39        | 13.09%  |
| es_ES   | 21        | 7.05%   |
| ru_RU   | 15        | 5.03%   |
| pt_BR   | 14        | 4.7%    |
| en_GB   | 13        | 4.36%   |
| it_IT   | 11        | 3.69%   |
| fr_FR   | 11        | 3.69%   |
| pl_PL   | 6         | 2.01%   |
| nl_NL   | 5         | 1.68%   |
| pt_PT   | 4         | 1.34%   |
| en_AU   | 4         | 1.34%   |
| tr_TR   | 3         | 1.01%   |
| en_CA   | 3         | 1.01%   |
| nb_NO   | 2         | 0.67%   |
| hu_HU   | 2         | 0.67%   |
| zh_CN   | 1         | 0.34%   |
| uk_UA   | 1         | 0.34%   |
| sv_SE   | 1         | 0.34%   |
| et_EE   | 1         | 0.34%   |
| de_CH   | 1         | 0.34%   |
| cs_CZ   | 1         | 0.34%   |
| C       | 1         | 0.34%   |
| bg_BG   | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 207       | 69.46%  |
| BIOS | 91        | 30.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 289       | 96.98%  |
| Btrfs   | 6         | 2.01%   |
| Overlay | 3         | 1.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 254       | 84.95%  |
| GPT     | 40        | 13.38%  |
| MBR     | 5         | 1.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 289       | 96.98%  |
| Yes       | 9         | 3.02%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 277       | 92.95%  |
| Yes       | 21        | 7.05%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 58        | 19.46%  |
| Hewlett-Packard        | 47        | 15.77%  |
| ASUSTek Computer       | 40        | 13.42%  |
| Apple                  | 36        | 12.08%  |
| Dell                   | 32        | 10.74%  |
| Acer                   | 25        | 8.39%   |
| HUAWEI                 | 9         | 3.02%   |
| Sony                   | 8         | 2.68%   |
| Samsung Electronics    | 7         | 2.35%   |
| MSI                    | 6         | 2.01%   |
| Toshiba                | 5         | 1.68%   |
| Timi                   | 2         | 0.67%   |
| Teclast                | 2         | 0.67%   |
| Star Labs              | 2         | 0.67%   |
| Notebook               | 2         | 0.67%   |
| Monster                | 2         | 0.67%   |
| LG Electronics         | 2         | 0.67%   |
| Wortmann AG            | 1         | 0.34%   |
| Razer                  | 1         | 0.34%   |
| PIPO                   | 1         | 0.34%   |
| Packard Bell           | 1         | 0.34%   |
| iOTA                   | 1         | 0.34%   |
| Google                 | 1         | 0.34%   |
| Fujitsu                | 1         | 0.34%   |
| eMachines              | 1         | 0.34%   |
| Compaq                 | 1         | 0.34%   |
| Casper                 | 1         | 0.34%   |
| Avell High Performance | 1         | 0.34%   |
| AMI                    | 1         | 0.34%   |
| Alienware              | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Apple MacBook5,1                                  | 4         | 1.34%   |
| HUAWEI MACHD-WXX9                                 | 3         | 1.01%   |
| HP Notebook                                       | 3         | 1.01%   |
| ASUS ZenBook UX425EA_UX425EA                      | 3         | 1.01%   |
| ASUS X550CA                                       | 3         | 1.01%   |
| Apple MacBookPro8,2                               | 3         | 1.01%   |
| Apple MacBookAir4,2                               | 3         | 1.01%   |
| Apple MacBook4,1                                  | 3         | 1.01%   |
| Timi TM1613                                       | 2         | 0.67%   |
| MSI Prestige 15 A11UC                             | 2         | 0.67%   |
| Lenovo IdeaPad 310-15IKB 80TV                     | 2         | 0.67%   |
| HUAWEI NBLK-WAX9X                                 | 2         | 0.67%   |
| HP ProBook 4540s                                  | 2         | 0.67%   |
| HP Pavilion g6                                    | 2         | 0.67%   |
| HP Pavilion g4                                    | 2         | 0.67%   |
| HP EliteBook 8460p                                | 2         | 0.67%   |
| HP EliteBook 840 G1                               | 2         | 0.67%   |
| Dell XPS 13 9343                                  | 2         | 0.67%   |
| Dell Inspiron N5050                               | 2         | 0.67%   |
| Dell Inspiron 15-3567                             | 2         | 0.67%   |
| Apple MacBookPro6,2                               | 2         | 0.67%   |
| Apple MacBookPro5,5                               | 2         | 0.67%   |
| Apple MacBookPro11,5                              | 2         | 0.67%   |
| Apple MacBookAir7,2                               | 2         | 0.67%   |
| Apple MacBookAir7,1                               | 2         | 0.67%   |
| Acer Swift SF114-32                               | 2         | 0.67%   |
| Wortmann AG 1220729_1470271                       | 1         | 0.34%   |
| Toshiba Satellite T130                            | 1         | 0.34%   |
| Toshiba Satellite L850D-BJS                       | 1         | 0.34%   |
| Toshiba Satellite L50D-C                          | 1         | 0.34%   |
| Toshiba Satellite C70D-A                          | 1         | 0.34%   |
| Toshiba PORTEGE Z830                              | 1         | 0.34%   |
| Teclast F7                                        | 1         | 0.34%   |
| Teclast F15S                                      | 1         | 0.34%   |
| Star Labs StarBook                                | 1         | 0.34%   |
| Star Labs LabTop                                  | 1         | 0.34%   |
| Sony VPCYB20AL                                    | 1         | 0.34%   |
| Sony VPCEB23FM                                    | 1         | 0.34%   |
| Sony VPCEA3S1E                                    | 1         | 0.34%   |
| Sony VPCCA4E1E                                    | 1         | 0.34%   |
| Sony SVP1321B4E                                   | 1         | 0.34%   |
| Sony SVF1521F6EW                                  | 1         | 0.34%   |
| Sony SVE15115EN                                   | 1         | 0.34%   |
| Sony SVE14A390X                                   | 1         | 0.34%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411       | 1         | 0.34%   |
| Samsung Lumpy                                     | 1         | 0.34%   |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.34%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D        | 1         | 0.34%   |
| Samsung 870Z5E/880Z5E/680Z5E                      | 1         | 0.34%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.34%   |
| Samsung 300E5M/300E5L                             | 1         | 0.34%   |
| Razer Blade Stealth                               | 1         | 0.34%   |
| PIPO W9                                           | 1         | 0.34%   |
| Packard Bell EasyNote LS11HR                      | 1         | 0.34%   |
| Notebook W65_67SJ                                 | 1         | 0.34%   |
| Notebook P65xHP                                   | 1         | 0.34%   |
| MSI PS63 Modern 8RD                               | 1         | 0.34%   |
| MSI Modern 14 B4MW                                | 1         | 0.34%   |
| MSI Modern 14 B10MW                               | 1         | 0.34%   |
| MSI GF63 Thin 9SCSR                               | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 30        | 10.07%  |
| Lenovo IdeaPad      | 19        | 6.38%   |
| Acer Aspire         | 17        | 5.7%    |
| Dell Inspiron       | 12        | 4.03%   |
| HP Pavilion         | 11        | 3.69%   |
| HP ProBook          | 10        | 3.36%   |
| HP EliteBook        | 10        | 3.36%   |
| Dell Latitude       | 9         | 3.02%   |
| ASUS VivoBook       | 8         | 2.68%   |
| ASUS ZenBook        | 6         | 2.01%   |
| HP Laptop           | 5         | 1.68%   |
| Apple MacBookPro8   | 5         | 1.68%   |
| Apple MacBook5      | 5         | 1.68%   |
| Acer Swift          | 5         | 1.68%   |
| Toshiba Satellite   | 4         | 1.34%   |
| Dell XPS            | 4         | 1.34%   |
| Dell Precision      | 4         | 1.34%   |
| Apple MacBookAir7   | 4         | 1.34%   |
| HUAWEI MACHD-WXX9   | 3         | 1.01%   |
| HP Notebook         | 3         | 1.01%   |
| Dell Vostro         | 3         | 1.01%   |
| ASUS X550CA         | 3         | 1.01%   |
| Apple MacBookPro5   | 3         | 1.01%   |
| Apple MacBookAir4   | 3         | 1.01%   |
| Apple MacBook4      | 3         | 1.01%   |
| Timi TM1613         | 2         | 0.67%   |
| MSI Prestige        | 2         | 0.67%   |
| MSI Modern          | 2         | 0.67%   |
| Lenovo Legion       | 2         | 0.67%   |
| Lenovo G550         | 2         | 0.67%   |
| HUAWEI NBLK-WAX9X   | 2         | 0.67%   |
| HP Stream           | 2         | 0.67%   |
| HP 255              | 2         | 0.67%   |
| Apple MacBookPro9   | 2         | 0.67%   |
| Apple MacBookPro6   | 2         | 0.67%   |
| Apple MacBookPro11  | 2         | 0.67%   |
| Apple MacBookAir6   | 2         | 0.67%   |
| Acer Nitro          | 2         | 0.67%   |
| Wortmann AG 1220729 | 1         | 0.34%   |
| Toshiba PORTEGE     | 1         | 0.34%   |
| Teclast F7          | 1         | 0.34%   |
| Teclast F15S        | 1         | 0.34%   |
| Star Labs StarBook  | 1         | 0.34%   |
| Star Labs LabTop    | 1         | 0.34%   |
| Sony VPCYB20AL      | 1         | 0.34%   |
| Sony VPCEB23FM      | 1         | 0.34%   |
| Sony VPCEA3S1E      | 1         | 0.34%   |
| Sony VPCCA4E1E      | 1         | 0.34%   |
| Sony SVP1321B4E     | 1         | 0.34%   |
| Sony SVF1521F6EW    | 1         | 0.34%   |
| Sony SVE15115EN     | 1         | 0.34%   |
| Sony SVE14A390X     | 1         | 0.34%   |
| Samsung RV411       | 1         | 0.34%   |
| Samsung Lumpy       | 1         | 0.34%   |
| Samsung 950XDB      | 1         | 0.34%   |
| Samsung 900X3C      | 1         | 0.34%   |
| Samsung 870Z5E      | 1         | 0.34%   |
| Samsung 500R4K      | 1         | 0.34%   |
| Samsung 300E5M      | 1         | 0.34%   |
| Razer Blade         | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 37        | 12.42%  |
| 2021 | 27        | 9.06%   |
| 2018 | 27        | 9.06%   |
| 2012 | 25        | 8.39%   |
| 2019 | 23        | 7.72%   |
| 2015 | 23        | 7.72%   |
| 2016 | 22        | 7.38%   |
| 2011 | 22        | 7.38%   |
| 2013 | 20        | 6.71%   |
| 2010 | 16        | 5.37%   |
| 2017 | 15        | 5.03%   |
| 2009 | 15        | 5.03%   |
| 2014 | 14        | 4.7%    |
| 2008 | 9         | 3.02%   |
| 2022 | 1         | 0.34%   |
| 2007 | 1         | 0.34%   |
| 2006 | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 298       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 247       | 82.61%  |
| Enabled  | 52        | 17.39%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 294       | 98.66%  |
| Yes  | 4         | 1.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 106       | 35.45%  |
| 3.01-4.0    | 76        | 25.42%  |
| 16.01-24.0  | 49        | 16.39%  |
| 8.01-16.0   | 43        | 14.38%  |
| 32.01-64.0  | 11        | 3.68%   |
| 1.01-2.0    | 10        | 3.34%   |
| 2.01-3.0    | 2         | 0.67%   |
| 24.01-32.0  | 1         | 0.33%   |
| 64.01-256.0 | 1         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 119       | 38.39%  |
| 2.01-3.0   | 104       | 33.55%  |
| 3.01-4.0   | 39        | 12.58%  |
| 4.01-8.0   | 26        | 8.39%   |
| 0.51-1.0   | 13        | 4.19%   |
| 8.01-16.0  | 7         | 2.26%   |
| 24.01-32.0 | 1         | 0.32%   |
| 16.01-24.0 | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 222       | 74%     |
| 2      | 73        | 24.33%  |
| 3      | 4         | 1.33%   |
| 5      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 204       | 67.77%  |
| Yes       | 97        | 32.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 71.48%  |
| No        | 85        | 28.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 296       | 99%     |
| No        | 3         | 1%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 268       | 89.04%  |
| No        | 33        | 10.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 43        | 14.43%  |
| Germany      | 35        | 11.74%  |
| Russia       | 19        | 6.38%   |
| Brazil       | 19        | 6.38%   |
| India        | 15        | 5.03%   |
| Italy        | 14        | 4.7%    |
| UK           | 12        | 4.03%   |
| Turkey       | 9         | 3.02%   |
| Poland       | 8         | 2.68%   |
| France       | 8         | 2.68%   |
| Australia    | 8         | 2.68%   |
| Mexico       | 7         | 2.35%   |
| Indonesia    | 7         | 2.35%   |
| Spain        | 6         | 2.01%   |
| Netherlands  | 6         | 2.01%   |
| Canada       | 6         | 2.01%   |
| Portugal     | 5         | 1.68%   |
| Belgium      | 5         | 1.68%   |
| Argentina    | 5         | 1.68%   |
| Switzerland  | 4         | 1.34%   |
| Chile        | 4         | 1.34%   |
| Austria      | 4         | 1.34%   |
| New Zealand  | 3         | 1.01%   |
| Hungary      | 3         | 1.01%   |
| Czechia      | 3         | 1.01%   |
| Ukraine      | 2         | 0.67%   |
| South Africa | 2         | 0.67%   |
| Romania      | 2         | 0.67%   |
| Pakistan     | 2         | 0.67%   |
| Norway       | 2         | 0.67%   |
| Estonia      | 2         | 0.67%   |
| Colombia     | 2         | 0.67%   |
| Bulgaria     | 2         | 0.67%   |
| Belarus      | 2         | 0.67%   |
| Zambia       | 1         | 0.34%   |
| Taiwan       | 1         | 0.34%   |
| Sweden       | 1         | 0.34%   |
| Sri Lanka    | 1         | 0.34%   |
| Serbia       | 1         | 0.34%   |
| Senegal      | 1         | 0.34%   |
| Peru         | 1         | 0.34%   |
| Nicaragua    | 1         | 0.34%   |
| Mozambique   | 1         | 0.34%   |
| Luxembourg   | 1         | 0.34%   |
| Lithuania    | 1         | 0.34%   |
| Latvia       | 1         | 0.34%   |
| Kenya        | 1         | 0.34%   |
| Japan        | 1         | 0.34%   |
| Ireland      | 1         | 0.34%   |
| Iran         | 1         | 0.34%   |
| Iceland      | 1         | 0.34%   |
| Guyana       | 1         | 0.34%   |
| Greece       | 1         | 0.34%   |
| Finland      | 1         | 0.34%   |
| Croatia      | 1         | 0.34%   |
| China        | 1         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Sydney                 | 7         | 2.3%    |
| Moscow                 | 6         | 1.97%   |
| St Petersburg          | 4         | 1.32%   |
| The Hague              | 3         | 0.99%   |
| Munich                 | 3         | 0.99%   |
| Istanbul               | 3         | 0.99%   |
| Hamburg                | 3         | 0.99%   |
| Warsaw                 | 2         | 0.66%   |
| Vienna                 | 2         | 0.66%   |
| Tucson                 | 2         | 0.66%   |
| Sao Paulo              | 2         | 0.66%   |
| Santo André           | 2         | 0.66%   |
| Rome                   | 2         | 0.66%   |
| Porto                  | 2         | 0.66%   |
| Mumbai                 | 2         | 0.66%   |
| Monza                  | 2         | 0.66%   |
| Montornès del Vallès | 2         | 0.66%   |
| Minsk                  | 2         | 0.66%   |
| Madrid                 | 2         | 0.66%   |
| Jakarta                | 2         | 0.66%   |
| Islamabad              | 2         | 0.66%   |
| Cologne                | 2         | 0.66%   |
| Chelyabinsk            | 2         | 0.66%   |
| Cankaya                | 2         | 0.66%   |
| Bogor                  | 2         | 0.66%   |
| Bern                   | 2         | 0.66%   |
| Belo Horizonte         | 2         | 0.66%   |
| Antalya                | 2         | 0.66%   |
| Ankara                 | 2         | 0.66%   |
| Zagreb                 | 1         | 0.33%   |
| Ypres                  | 1         | 0.33%   |
| Wuhan                  | 1         | 0.33%   |
| Wroclaw                | 1         | 0.33%   |
| Wonosari               | 1         | 0.33%   |
| Wolgast                | 1         | 0.33%   |
| Witbank                | 1         | 0.33%   |
| West Bromwich          | 1         | 0.33%   |
| Wellington             | 1         | 0.33%   |
| Warrenton              | 1         | 0.33%   |
| Wallerfangen           | 1         | 0.33%   |
| Voerde                 | 1         | 0.33%   |
| Vladivostok            | 1         | 0.33%   |
| Vitória da Conquista  | 1         | 0.33%   |
| Vilnius                | 1         | 0.33%   |
| Villa Bosch            | 1         | 0.33%   |
| Vila Nova de Gaia      | 1         | 0.33%   |
| Vigodarzere            | 1         | 0.33%   |
| Vernouillet            | 1         | 0.33%   |
| Vear                   | 1         | 0.33%   |
| Vantaa                 | 1         | 0.33%   |
| Valencia               | 1         | 0.33%   |
| Ulyanovsk              | 1         | 0.33%   |
| Uden                   | 1         | 0.33%   |
| Ubstadt-Weiher         | 1         | 0.33%   |
| Tromsø                | 1         | 0.33%   |
| Trieste                | 1         | 0.33%   |
| Treviso                | 1         | 0.33%   |
| Traben-Trarbach        | 1         | 0.33%   |
| Toronto                | 1         | 0.33%   |
| Tomsk                  | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 56        | 67     | 15.05%  |
| Seagate                   | 38        | 38     | 10.22%  |
| WDC                       | 34        | 39     | 9.14%   |
| Toshiba                   | 27        | 27     | 7.26%   |
| SanDisk                   | 26        | 27     | 6.99%   |
| Kingston                  | 22        | 25     | 5.91%   |
| Unknown                   | 17        | 20     | 4.57%   |
| HGST                      | 15        | 16     | 4.03%   |
| Apple                     | 15        | 16     | 4.03%   |
| SK hynix                  | 13        | 14     | 3.49%   |
| Crucial                   | 13        | 14     | 3.49%   |
| Intel                     | 9         | 10     | 2.42%   |
| Hitachi                   | 7         | 7      | 1.88%   |
| KIOXIA                    | 6         | 6      | 1.61%   |
| A-DATA Technology         | 6         | 6      | 1.61%   |
| Micron Technology         | 5         | 6      | 1.34%   |
| Phison                    | 4         | 4      | 1.08%   |
| China                     | 4         | 4      | 1.08%   |
| Silicon Motion            | 3         | 3      | 0.81%   |
| Fujitsu                   | 3         | 3      | 0.81%   |
| Unknown                   | 3         | 3      | 0.81%   |
| Transcend                 | 2         | 2      | 0.54%   |
| TO Exter                  | 2         | 2      | 0.54%   |
| OCZ                       | 2         | 3      | 0.54%   |
| LITEON                    | 2         | 2      | 0.54%   |
| KingDian                  | 2         | 2      | 0.54%   |
| JMicron Technology        | 2         | 2      | 0.54%   |
| ZTE                       | 1         | 1      | 0.27%   |
| V-GeN                     | 1         | 1      | 0.27%   |
| UMIS                      | 1         | 1      | 0.27%   |
| Teclast                   | 1         | 1      | 0.27%   |
| Team                      | 1         | 1      | 0.27%   |
| Star Drive                | 1         | 1      | 0.27%   |
| Star                      | 1         | 1      | 0.27%   |
| SSSTC                     | 1         | 1      | 0.27%   |
| SSK                       | 1         | 1      | 0.27%   |
| SSDPR-CX                  | 1         | 1      | 0.27%   |
| SPCC                      | 1         | 1      | 0.27%   |
| Smartbuy                  | 1         | 1      | 0.27%   |
| SABRENT                   | 1         | 1      | 0.27%   |
| PNY                       | 1         | 2      | 0.27%   |
| Pichau                    | 1         | 1      | 0.27%   |
| Patriot                   | 1         | 2      | 0.27%   |
| OSCOO                     | 1         | 1      | 0.27%   |
| NGFF                      | 1         | 1      | 0.27%   |
| Netac                     | 1         | 1      | 0.27%   |
| Micron/Crucial Technology | 1         | 1      | 0.27%   |
| MENGMI                    | 1         | 1      | 0.27%   |
| Lexar                     | 1         | 1      | 0.27%   |
| Leven                     | 1         | 1      | 0.27%   |
| KingSpec                  | 1         | 1      | 0.27%   |
| Kingchuxing               | 1         | 2      | 0.27%   |
| GOODRAM                   | 1         | 1      | 0.27%   |
| FORESEE                   | 1         | 1      | 0.27%   |
| faspeed                   | 1         | 1      | 0.27%   |
| EYOTA                     | 1         | 1      | 0.27%   |
| EVM                       | 1         | 1      | 0.27%   |
| Dogfish                   | 1         | 1      | 0.27%   |
| Colorful                  | 1         | 1      | 0.27%   |
| ASMedia                   | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB         | 9         | 2.36%   |
| Seagate ST1000LM035-1RK172 1TB       | 8         | 2.09%   |
| Toshiba MQ01ABD100 1TB               | 6         | 1.57%   |
| SanDisk NVMe SSD Drive 512GB         | 6         | 1.57%   |
| Samsung NVMe SSD Drive 256GB         | 6         | 1.57%   |
| Kingston SA400S37240G 240GB SSD      | 6         | 1.57%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 1.31%   |
| Unknown MMC Card  32GB               | 4         | 1.05%   |
| Toshiba MQ01ABF050 500GB             | 4         | 1.05%   |
| SK hynix NVMe SSD Drive 256GB        | 4         | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 1.05%   |
| Samsung NVMe SSD Drive 1024GB        | 4         | 1.05%   |
| Intel NVMe SSD Drive 512GB           | 4         | 1.05%   |
| HGST HTS541010B7E610 1TB             | 4         | 1.05%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3         | 0.79%   |
| Unknown MMC Card  64GB               | 3         | 0.79%   |
| Unknown MMC Card  128GB              | 3         | 0.79%   |
| Toshiba NVMe SSD Drive 512GB         | 3         | 0.79%   |
| Toshiba NVMe SSD Drive 256GB         | 3         | 0.79%   |
| Toshiba MQ04ABF100 1TB               | 3         | 0.79%   |
| SK hynix NVMe SSD Drive 512GB        | 3         | 0.79%   |
| SanDisk NVMe SSD Drive 1024GB        | 3         | 0.79%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.79%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.79%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 3         | 0.79%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.79%   |
| HGST HTS545050A7E680 500GB           | 3         | 0.79%   |
| Unknown                              | 3         | 0.79%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 0.52%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.52%   |
| TO Exter nal USB 3.0 1TB             | 2         | 0.52%   |
| Seagate ST980811AS 80GB              | 2         | 0.52%   |
| Seagate ST9750420AS 752GB            | 2         | 0.52%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.52%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD  | 2         | 0.52%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD  | 2         | 0.52%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.52%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.52%   |
| Samsung SSD 850 EVO 120GB            | 2         | 0.52%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD | 2         | 0.52%   |
| Phison NVMe SSD Drive 512GB          | 2         | 0.52%   |
| Phison NVMe SSD Drive 1TB            | 2         | 0.52%   |
| OCZ VERTEX3 120GB SSD                | 2         | 0.52%   |
| KIOXIA NVMe SSD Drive 256GB          | 2         | 0.52%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.52%   |
| Kingston NVMe SSD Drive 512GB        | 2         | 0.52%   |
| Kingston NVMe SSD Drive 500GB        | 2         | 0.52%   |
| Intel NVMe SSD Drive 1024GB          | 2         | 0.52%   |
| HGST HTS545050A7E380 500GB           | 2         | 0.52%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 0.52%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 0.52%   |
| Apple SSD SM256C 256GB               | 2         | 0.52%   |
| Apple SSD SM0512G 500GB              | 2         | 0.52%   |
| Apple SSD SM0128G 121GB              | 2         | 0.52%   |
| A-DATA SU650 120GB SSD               | 2         | 0.52%   |
| ZTE MMC Storage 942MB                | 1         | 0.26%   |
| WDC WDS500G2B0B 500GB SSD            | 1         | 0.26%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.26%   |
| WDC WDS200T2B0A-00SM50 2TB SSD       | 1         | 0.26%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 38        | 38     | 34.86%  |
| WDC     | 24        | 28     | 22.02%  |
| Toshiba | 19        | 19     | 17.43%  |
| HGST    | 15        | 16     | 13.76%  |
| Hitachi | 7         | 7      | 6.42%   |
| Fujitsu | 3         | 3      | 2.75%   |
| Unknown | 1         | 1      | 0.92%   |
| SABRENT | 1         | 1      | 0.92%   |
| Apple   | 1         | 1      | 0.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 35     | 22.63%  |
| Kingston            | 14        | 14     | 10.22%  |
| SanDisk             | 13        | 14     | 9.49%   |
| Crucial             | 13        | 14     | 9.49%   |
| Apple               | 12        | 12     | 8.76%   |
| WDC                 | 7         | 7      | 5.11%   |
| A-DATA Technology   | 5         | 5      | 3.65%   |
| Micron Technology   | 4         | 5      | 2.92%   |
| China               | 4         | 4      | 2.92%   |
| Transcend           | 2         | 2      | 1.46%   |
| Toshiba             | 2         | 2      | 1.46%   |
| TO Exter            | 2         | 2      | 1.46%   |
| OCZ                 | 2         | 3      | 1.46%   |
| LITEON              | 2         | 2      | 1.46%   |
| Intel               | 2         | 2      | 1.46%   |
| Teclast             | 1         | 1      | 0.73%   |
| Team                | 1         | 1      | 0.73%   |
| Star                | 1         | 1      | 0.73%   |
| SPCC                | 1         | 1      | 0.73%   |
| Smartbuy            | 1         | 1      | 0.73%   |
| SK hynix            | 1         | 1      | 0.73%   |
| PNY                 | 1         | 2      | 0.73%   |
| Pichau              | 1         | 1      | 0.73%   |
| Patriot             | 1         | 2      | 0.73%   |
| NGFF                | 1         | 1      | 0.73%   |
| Netac               | 1         | 1      | 0.73%   |
| MENGMI              | 1         | 1      | 0.73%   |
| Lexar               | 1         | 1      | 0.73%   |
| KingSpec            | 1         | 1      | 0.73%   |
| KingDian            | 1         | 1      | 0.73%   |
| GOODRAM             | 1         | 1      | 0.73%   |
| FORESEE             | 1         | 1      | 0.73%   |
| EVM                 | 1         | 1      | 0.73%   |
| Dogfish             | 1         | 1      | 0.73%   |
| Colorful            | 1         | 1      | 0.73%   |
| Apacer              | 1         | 1      | 0.73%   |
| Unknown             | 1         | 1      | 0.73%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 131       | 147    | 36.39%  |
| HDD     | 107       | 114    | 29.72%  |
| NVMe    | 91        | 110    | 25.28%  |
| MMC     | 18        | 20     | 5%      |
| Unknown | 13        | 14     | 3.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 218       | 260    | 63.74%  |
| NVMe | 91        | 109    | 26.61%  |
| MMC  | 18        | 20     | 5.26%   |
| SAS  | 15        | 16     | 4.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 170       | 193    | 73.28%  |
| 0.51-1.0   | 55        | 59     | 23.71%  |
| 1.01-2.0   | 6         | 8      | 2.59%   |
| 3.01-4.0   | 1         | 1      | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 125       | 41.95%  |
| 251-500        | 78        | 26.17%  |
| 501-1000       | 41        | 13.76%  |
| 51-100         | 25        | 8.39%   |
| 1001-2000      | 13        | 4.36%   |
| 21-50          | 12        | 4.03%   |
| More than 3000 | 1         | 0.34%   |
| 2001-3000      | 1         | 0.34%   |
| 1-20           | 1         | 0.34%   |
| Unknown        | 1         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 145       | 47.39%  |
| 21-50     | 80        | 26.14%  |
| 51-100    | 34        | 11.11%  |
| 101-250   | 25        | 8.17%   |
| 251-500   | 10        | 3.27%   |
| 501-1000  | 8         | 2.61%   |
| 1001-2000 | 2         | 0.65%   |
| 2001-3000 | 1         | 0.33%   |
| Unknown   | 1         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB           | 1         | 1      | 20%     |
| Seagate ST500LM030-2E717D 500GB  | 1         | 1      | 20%     |
| Kingston SV300S37A240G 240GB SSD | 1         | 1      | 20%     |
| Crucial CT512M550SSD3 512GB      | 1         | 1      | 20%     |
| Apple SSD SM256C 256GB           | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 20%     |
| Seagate  | 1         | 1      | 20%     |
| Kingston | 1         | 1      | 20%     |
| Crucial  | 1         | 1      | 20%     |
| Apple    | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 60%     |
| HDD  | 2         | 2      | 40%     |

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
| Detected | 266       | 345    | 84.44%  |
| Works    | 44        | 55     | 13.97%  |
| Malfunc  | 5         | 5      | 1.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 205       | 60.47%  |
| AMD                            | 32        | 9.44%   |
| Samsung Electronics            | 31        | 9.14%   |
| SanDisk                        | 15        | 4.42%   |
| SK hynix                       | 12        | 3.54%   |
| Nvidia                         | 9         | 2.65%   |
| Kingston Technology Company    | 9         | 2.65%   |
| Toshiba America Info Systems   | 6         | 1.77%   |
| Phison Electronics             | 5         | 1.47%   |
| KIOXIA                         | 4         | 1.18%   |
| Silicon Motion                 | 3         | 0.88%   |
| Apple                          | 2         | 0.59%   |
| Union Memory (Shenzhen)        | 1         | 0.29%   |
| Solid State Storage Technology | 1         | 0.29%   |
| Micron/Crucial Technology      | 1         | 0.29%   |
| Micron Technology              | 1         | 0.29%   |
| Marvell Technology Group       | 1         | 0.29%   |
| ADATA Technology               | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 31        | 8.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 28        | 7.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 24        | 6.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 23        | 6.42%   |
| Samsung NVMe SSD Controller 980                                                        | 12        | 3.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 12        | 3.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 11        | 3.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 11        | 3.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 2.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 8         | 2.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 8         | 2.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 8         | 2.23%   |
| Nvidia MCP79 AHCI Controller                                                           | 7         | 1.96%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 7         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 7         | 1.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 6         | 1.68%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 6         | 1.68%   |
| Intel SSD 660P Series                                                                  | 6         | 1.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 6         | 1.68%   |
| Samsung Electronics SATA controller                                                    | 5         | 1.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 1.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 5         | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 5         | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 5         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 1.4%    |
| SK hynix Gold P31 SSD                                                                  | 4         | 1.12%   |
| SK hynix BC511                                                                         | 4         | 1.12%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 1.12%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 4         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 4         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 4         | 1.12%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 0.84%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 3         | 0.84%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 3         | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 0.84%   |
| Phison E12 NVMe Controller                                                             | 3         | 0.84%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 3         | 0.84%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 0.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 3         | 0.84%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 0.56%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 2         | 0.56%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 2         | 0.56%   |
| Kingston Company KC2000 NVMe SSD                                                       | 2         | 0.56%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 2         | 0.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.56%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 0.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.56%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.28%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                   | 1         | 0.28%   |
| Solid State Storage Non-Volatile memory controller                                     | 1         | 0.28%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 0.28%   |
| Silicon Motion Non-Volatile memory controller                                          | 1         | 0.28%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.28%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.28%   |
| SanDisk Non-Volatile memory controller                                                 | 1         | 0.28%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 0.28%   |
| Phison NVMe Storage Controller                                                         | 1         | 0.28%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 227       | 65.61%  |
| NVMe | 89        | 25.72%  |
| RAID | 15        | 4.34%   |
| IDE  | 15        | 4.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 249       | 83.56%  |
| AMD    | 49        | 16.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 10        | 3.36%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 2.35%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 2.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.68%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 1.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.68%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 1.34%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.34%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 1.34%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.34%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 1.34%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 1.34%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.01%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.01%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.01%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.01%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 1.01%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 1.01%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 1.01%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 3         | 1.01%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.01%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz       | 3         | 1.01%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 1.01%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.67%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 2         | 0.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.67%   |
| Intel Core i7-5650U CPU @ 2.20GHz             | 2         | 0.67%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 2         | 0.67%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.67%   |
| Intel Core i7-3635QM CPU @ 2.40GHz            | 2         | 0.67%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.67%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.67%   |
| Intel Core i7-2677M CPU @ 1.80GHz             | 2         | 0.67%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 2         | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.67%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 0.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.67%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 0.67%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 2         | 0.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.67%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.67%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.67%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.67%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.67%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 0.67%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 2         | 0.67%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.67%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.67%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.67%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 0.67%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.67%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 0.67%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 2         | 0.67%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.67%   |
| Intel Celeron N4120 CPU @ 1.10GHz             | 2         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 73        | 24.5%   |
| Intel Core i7           | 65        | 21.81%  |
| Intel Core i3           | 31        | 10.4%   |
| Intel Celeron           | 24        | 8.05%   |
| Other                   | 22        | 7.38%   |
| Intel Core 2 Duo        | 18        | 6.04%   |
| AMD Ryzen 5             | 17        | 5.7%    |
| AMD Ryzen 7             | 6         | 2.01%   |
| Intel Pentium           | 5         | 1.68%   |
| AMD A6                  | 4         | 1.34%   |
| Intel Pentium Silver    | 3         | 1.01%   |
| AMD Ryzen 7 PRO         | 3         | 1.01%   |
| AMD Ryzen 3             | 3         | 1.01%   |
| AMD A12                 | 3         | 1.01%   |
| Intel Pentium Dual-Core | 2         | 0.67%   |
| Intel Genuine           | 2         | 0.67%   |
| Intel Celeron Dual-Core | 2         | 0.67%   |
| AMD A8                  | 2         | 0.67%   |
| AMD A4                  | 2         | 0.67%   |
| AMD A10                 | 2         | 0.67%   |
| Intel Pentium Dual      | 1         | 0.34%   |
| Intel Core m5           | 1         | 0.34%   |
| Intel Core 2 Quad       | 1         | 0.34%   |
| Intel Core 2            | 1         | 0.34%   |
| Intel Atom              | 1         | 0.34%   |
| AMD Ryzen 9             | 1         | 0.34%   |
| AMD Ryzen 5 PRO         | 1         | 0.34%   |
| AMD E1                  | 1         | 0.34%   |
| AMD E                   | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 168       | 56.38%  |
| 4      | 102       | 34.23%  |
| 6      | 16        | 5.37%   |
| 8      | 10        | 3.36%   |
| 1      | 2         | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 298       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 219       | 73.49%  |
| 1      | 79        | 26.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 298       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 27        | 9%      |
| 0x306a9    | 25        | 8.33%   |
| Unknown    | 20        | 6.67%   |
| 0x806c1    | 15        | 5%      |
| 0x306d4    | 15        | 5%      |
| 0x1067a    | 14        | 4.67%   |
| 0x40651    | 12        | 4%      |
| 0x406e3    | 11        | 3.67%   |
| 0x20655    | 11        | 3.67%   |
| 0x806ec    | 10        | 3.33%   |
| 0x806e9    | 10        | 3.33%   |
| 0x10676    | 8         | 2.67%   |
| 0x806ea    | 7         | 2.33%   |
| 0x706a8    | 7         | 2.33%   |
| 0x406c3    | 6         | 2%      |
| 0x08600106 | 6         | 2%      |
| 0x08108109 | 6         | 2%      |
| 0xa0652    | 5         | 1.67%   |
| 0x706e5    | 5         | 1.67%   |
| 0x506c9    | 5         | 1.67%   |
| 0x306c3    | 5         | 1.67%   |
| 0x20652    | 5         | 1.67%   |
| 0x06006705 | 5         | 1.67%   |
| 0x806eb    | 4         | 1.33%   |
| 0x6fd      | 4         | 1.33%   |
| 0x08608103 | 4         | 1.33%   |
| 0x906ea    | 3         | 1%      |
| 0x806c2    | 3         | 1%      |
| 0x706a1    | 3         | 1%      |
| 0x30678    | 3         | 1%      |
| 0x0a50000c | 3         | 1%      |
| 0x08108102 | 3         | 1%      |
| 0x906e9    | 2         | 0.67%   |
| 0x506e3    | 2         | 0.67%   |
| 0x40661    | 2         | 0.67%   |
| 0x0810100b | 2         | 0.67%   |
| 0x08101007 | 2         | 0.67%   |
| 0x0700010f | 2         | 0.67%   |
| 0x0600611a | 2         | 0.67%   |
| 0x06001119 | 2         | 0.67%   |
| 0xa0660    | 1         | 0.33%   |
| 0x906ed    | 1         | 0.33%   |
| 0x906c0    | 1         | 0.33%   |
| 0x6fb      | 1         | 0.33%   |
| 0x6f2      | 1         | 0.33%   |
| 0x406c4    | 1         | 0.33%   |
| 0x106e5    | 1         | 0.33%   |
| 0x08600104 | 1         | 0.33%   |
| 0x07030105 | 1         | 0.33%   |
| 0x07030104 | 1         | 0.33%   |
| 0x06006704 | 1         | 0.33%   |
| 0x06006110 | 1         | 0.33%   |
| 0x05000029 | 1         | 0.33%   |
| 0x03000027 | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 43        | 14.43%  |
| SandyBridge   | 28        | 9.4%    |
| IvyBridge     | 26        | 8.72%   |
| Penryn        | 22        | 7.38%   |
| Haswell       | 21        | 7.05%   |
| TigerLake     | 19        | 6.38%   |
| Westmere      | 16        | 5.37%   |
| Broadwell     | 15        | 5.03%   |
| Skylake       | 14        | 4.7%    |
| Silvermont    | 11        | 3.69%   |
| Zen 2         | 10        | 3.36%   |
| Goldmont plus | 10        | 3.36%   |
| Excavator     | 10        | 3.36%   |
| Zen+          | 9         | 3.02%   |
| Core          | 6         | 2.01%   |
| CometLake     | 6         | 2.01%   |
| IceLake       | 5         | 1.68%   |
| Goldmont      | 5         | 1.68%   |
| Unknown       | 5         | 1.68%   |
| Zen           | 4         | 1.34%   |
| Zen 3         | 3         | 1.01%   |
| Puma          | 2         | 0.67%   |
| Piledriver    | 2         | 0.67%   |
| Jaguar        | 2         | 0.67%   |
| Tremont       | 1         | 0.34%   |
| Nehalem       | 1         | 0.34%   |
| K10 Llano     | 1         | 0.34%   |
| Bobcat        | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 229       | 61.56%  |
| Nvidia | 72        | 19.35%  |
| AMD    | 71        | 19.09%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 6.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 6.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 4.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 3.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 3.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 2.86%   |
| Intel HD Graphics 5500                                                                   | 11        | 2.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 2.6%    |
| AMD Renoir                                                                               | 10        | 2.6%    |
| Intel HD Graphics 620                                                                    | 9         | 2.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.34%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.08%   |
| Nvidia C79 [GeForce 9400M]                                                               | 7         | 1.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.3%    |
| AMD Lucienne                                                                             | 5         | 1.3%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.04%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.04%   |
| Intel HD Graphics 6000                                                                   | 4         | 1.04%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 1.04%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.78%   |
| Intel HD Graphics 500                                                                    | 3         | 0.78%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.78%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 0.78%   |
| AMD Cezanne                                                                              | 3         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.52%   |
| Nvidia TU117M                                                                            | 2         | 0.52%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.52%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.52%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.52%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.52%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.52%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 2         | 0.52%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 0.52%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.52%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.52%   |
| Intel HD Graphics 630                                                                    | 2         | 0.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 2         | 0.52%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 2         | 0.52%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.52%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.52%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 2         | 0.52%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 2         | 0.52%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.26%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 158       | 53.02%  |
| Intel + Nvidia | 55        | 18.46%  |
| 1 x AMD        | 46        | 15.44%  |
| Intel + AMD    | 16        | 5.37%   |
| 1 x Nvidia     | 13        | 4.36%   |
| 2 x AMD        | 6         | 2.01%   |
| AMD + Nvidia   | 3         | 1.01%   |
| 2 x Nvidia     | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 266       | 89.26%  |
| Proprietary | 30        | 10.07%  |
| Unknown     | 2         | 0.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 183       | 61.41%  |
| 0.01-0.5   | 42        | 14.09%  |
| 1.01-2.0   | 37        | 12.42%  |
| 0.51-1.0   | 23        | 7.72%   |
| 3.01-4.0   | 11        | 3.69%   |
| 5.01-6.0   | 2         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 61        | 17.89%  |
| LG Display              | 51        | 14.96%  |
| Chimei Innolux          | 45        | 13.2%   |
| Apple                   | 36        | 10.56%  |
| BOE                     | 34        | 9.97%   |
| Samsung Electronics     | 33        | 9.68%   |
| Sharp                   | 9         | 2.64%   |
| Lenovo                  | 8         | 2.35%   |
| Chi Mei Optoelectronics | 8         | 2.35%   |
| Dell                    | 7         | 2.05%   |
| PANDA                   | 6         | 1.76%   |
| Hewlett-Packard         | 6         | 1.76%   |
| Goldstar                | 6         | 1.76%   |
| CSO                     | 4         | 1.17%   |
| Sony                    | 3         | 0.88%   |
| InfoVision              | 3         | 0.88%   |
| AOC                     | 2         | 0.59%   |
| Acer                    | 2         | 0.59%   |
| ViewSonic               | 1         | 0.29%   |
| Toshiba                 | 1         | 0.29%   |
| TMX                     | 1         | 0.29%   |
| SANYO                   | 1         | 0.29%   |
| Plain Tree Systems      | 1         | 0.29%   |
| Philips                 | 1         | 0.29%   |
| Panasonic               | 1         | 0.29%   |
| Packard Bell            | 1         | 0.29%   |
| Konka                   | 1         | 0.29%   |
| JDI                     | 1         | 0.29%   |
| HUAWEI                  | 1         | 0.29%   |
| HJC                     | 1         | 0.29%   |
| EXP                     | 1         | 0.29%   |
| DPL                     | 1         | 0.29%   |
| CPT                     | 1         | 0.29%   |
| BenQ                    | 1         | 0.29%   |
| Ancor Communications    | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 1.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 1.15%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 4         | 1.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 0.86%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 3         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.86%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.86%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.86%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 3         | 0.86%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 3         | 0.86%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.57%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.57%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.57%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 2         | 0.57%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.57%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 2         | 0.57%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 0.57%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 2         | 0.57%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch               | 2         | 0.57%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN152D 1920x1080 344x193mm 15.5-inch      | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.57%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.57%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 2         | 0.57%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 2         | 0.57%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 2         | 0.57%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 2         | 0.57%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                 | 2         | 0.57%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 2         | 0.57%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 2         | 0.57%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 2         | 0.57%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 2         | 0.57%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1         | 0.29%   |
| Toshiba TV TSB2019 3840x2160                                          | 1         | 0.29%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.29%   |
| Sony TV SNYA401 1920x1080                                             | 1         | 0.29%   |
| Sony TV SNY9600 1920x540 735x420mm 33.3-inch                          | 1         | 0.29%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.29%   |
| Sharp PN-K321 SHP21DD 3840x2160                                       | 1         | 0.29%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP1420 1920x1080 294x165mm 13.3-inch               | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 127       | 38.96%  |
| 1366x768 (WXGA)    | 105       | 32.21%  |
| 1280x800 (WXGA)    | 16        | 4.91%   |
| 1600x900 (HD+)     | 15        | 4.6%    |
| 1440x900 (WXGA+)   | 15        | 4.6%    |
| 3840x2160 (4K)     | 12        | 3.68%   |
| 2560x1440 (QHD)    | 10        | 3.07%   |
| 3000x2000          | 4         | 1.23%   |
| 2880x1800          | 4         | 1.23%   |
| 1920x1200 (WUXGA)  | 3         | 0.92%   |
| 3200x1800 (QHD+)   | 2         | 0.61%   |
| 2560x1600          | 2         | 0.61%   |
| 2560x1080          | 2         | 0.61%   |
| 1680x1050 (WSXGA+) | 2         | 0.61%   |
| 3840x2400          | 1         | 0.31%   |
| 3072x1920          | 1         | 0.31%   |
| 1920x540           | 1         | 0.31%   |
| 1920x1280          | 1         | 0.31%   |
| 1400x1050          | 1         | 0.31%   |
| 1280x720 (HD)      | 1         | 0.31%   |
| 1280x1024 (SXGA)   | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 129       | 37.5%   |
| 13      | 71        | 20.64%  |
| 14      | 49        | 14.24%  |
| 17      | 20        | 5.81%   |
| 11      | 13        | 3.78%   |
| 27      | 10        | 2.91%   |
| 23      | 10        | 2.91%   |
| 24      | 8         | 2.33%   |
| 12      | 6         | 1.74%   |
| 31      | 3         | 0.87%   |
| 16      | 3         | 0.87%   |
| 84      | 2         | 0.58%   |
| 72      | 2         | 0.58%   |
| 52      | 2         | 0.58%   |
| 34      | 2         | 0.58%   |
| 25      | 2         | 0.58%   |
| 21      | 2         | 0.58%   |
| 18      | 2         | 0.58%   |
| Unknown | 2         | 0.58%   |
| 47      | 1         | 0.29%   |
| 43      | 1         | 0.29%   |
| 33      | 1         | 0.29%   |
| 26      | 1         | 0.29%   |
| 22      | 1         | 0.29%   |
| 20      | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 204       | 60%     |
| 201-300     | 61        | 17.94%  |
| 501-600     | 28        | 8.24%   |
| 351-400     | 25        | 7.35%   |
| 401-500     | 6         | 1.76%   |
| 1501-2000   | 4         | 1.18%   |
| 701-800     | 3         | 0.88%   |
| 601-700     | 3         | 0.88%   |
| 1001-1500   | 3         | 0.88%   |
| Unknown     | 2         | 0.59%   |
| 901-1000    | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 251       | 82.03%  |
| 16/10   | 43        | 14.05%  |
| 3/2     | 7         | 2.29%   |
| 21/9    | 2         | 0.65%   |
| 5/4     | 1         | 0.33%   |
| 4/3     | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 128       | 37.54%  |
| 81-90          | 94        | 27.57%  |
| 71-80          | 26        | 7.62%   |
| 201-250        | 16        | 4.69%   |
| 121-130        | 16        | 4.69%   |
| 51-60          | 13        | 3.81%   |
| 301-350        | 10        | 2.93%   |
| More than 1000 | 6         | 1.76%   |
| 61-70          | 6         | 1.76%   |
| 351-500        | 6         | 1.76%   |
| 251-300        | 5         | 1.47%   |
| 141-150        | 3         | 0.88%   |
| 131-140        | 3         | 0.88%   |
| 111-120        | 3         | 0.88%   |
| 501-1000       | 2         | 0.59%   |
| Unknown        | 2         | 0.59%   |
| 151-200        | 1         | 0.29%   |
| 91-100         | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 140       | 41.54%  |
| 101-120       | 115       | 34.12%  |
| 51-100        | 42        | 12.46%  |
| 161-240       | 21        | 6.23%   |
| More than 240 | 13        | 3.86%   |
| 1-50          | 4         | 1.19%   |
| Unknown       | 2         | 0.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 255       | 85%     |
| 2     | 37        | 12.33%  |
| 3     | 6         | 2%      |
| 4     | 1         | 0.33%   |
| 0     | 1         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 138       | 30.73%  |
| Realtek Semiconductor             | 134       | 29.84%  |
| Qualcomm Atheros                  | 64        | 14.25%  |
| Broadcom                          | 51        | 11.36%  |
| Broadcom Limited                  | 11        | 2.45%   |
| Nvidia                            | 8         | 1.78%   |
| Marvell Technology Group          | 8         | 1.78%   |
| TP-Link                           | 5         | 1.11%   |
| Ralink                            | 5         | 1.11%   |
| Ralink Technology                 | 3         | 0.67%   |
| Xiaomi                            | 2         | 0.45%   |
| MediaTek                          | 2         | 0.45%   |
| Lenovo                            | 2         | 0.45%   |
| Google                            | 2         | 0.45%   |
| ASIX Electronics                  | 2         | 0.45%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.22%   |
| TRENDnet                          | 1         | 0.22%   |
| Sitecom Europe                    | 1         | 0.22%   |
| Sierra Wireless                   | 1         | 0.22%   |
| Qualcomm                          | 1         | 0.22%   |
| OPPO Electronics                  | 1         | 0.22%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.22%   |
| Huawei Technologies               | 1         | 0.22%   |
| Hewlett-Packard                   | 1         | 0.22%   |
| Ericsson Business Mobile Networks | 1         | 0.22%   |
| D-Link                            | 1         | 0.22%   |
| Apple                             | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 74        | 13.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 5.75%   |
| Intel Wi-Fi 6 AX201                                               | 16        | 2.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 2.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 2.23%   |
| Intel Wireless 8260                                               | 12        | 2.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 2.04%   |
| Intel Wireless 8265 / 8275                                        | 10        | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 1.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.48%   |
| Nvidia MCP79 Ethernet                                             | 8         | 1.48%   |
| Intel Wireless 7265                                               | 8         | 1.48%   |
| Intel Wireless 7260                                               | 8         | 1.48%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 1.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.48%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 8         | 1.48%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 8         | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 1.3%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 1.3%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 7         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.11%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 6         | 1.11%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.93%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 5         | 0.93%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.93%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 5         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.74%   |
| Intel Wireless 3165                                               | 4         | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.74%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 4         | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.56%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.56%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.56%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.56%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 3         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.37%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 133       | 42.63%  |
| Qualcomm Atheros      | 56        | 17.95%  |
| Broadcom              | 49        | 15.71%  |
| Realtek Semiconductor | 44        | 14.1%   |
| Broadcom Limited      | 10        | 3.21%   |
| TP-Link               | 5         | 1.6%    |
| Ralink                | 5         | 1.6%    |
| Ralink Technology     | 3         | 0.96%   |
| MediaTek              | 2         | 0.64%   |
| TRENDnet              | 1         | 0.32%   |
| Sitecom Europe        | 1         | 0.32%   |
| Sierra Wireless       | 1         | 0.32%   |
| Qualcomm              | 1         | 0.32%   |
| D-Link                | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                                   | 16        | 5.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 14        | 4.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 13        | 4.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 12        | 3.82%   |
| Intel Wireless 8260                                                                   | 12        | 3.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 11        | 3.5%    |
| Intel Wireless 8265 / 8275                                                            | 10        | 3.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 10        | 3.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 8         | 2.55%   |
| Intel Wireless 7265                                                                   | 8         | 2.55%   |
| Intel Wireless 7260                                                                   | 8         | 2.55%   |
| Intel Wi-Fi 6 AX200                                                                   | 8         | 2.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 8         | 2.55%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 8         | 2.55%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 8         | 2.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 7         | 2.23%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 7         | 2.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 6         | 1.91%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 6         | 1.91%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 6         | 1.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 5         | 1.59%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 5         | 1.59%   |
| Intel Centrino Advanced-N 6200                                                        | 5         | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 5         | 1.59%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 5         | 1.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 4         | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 4         | 1.27%   |
| Intel Wireless 3165                                                                   | 4         | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 4         | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 4         | 1.27%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 4         | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 4         | 1.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 3         | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 3         | 0.96%   |
| Intel Centrino Advanced-N 6235                                                        | 3         | 0.96%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 3         | 0.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 2         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 0.64%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2         | 0.64%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 2         | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 2         | 0.64%   |
| Intel Wireless-AC 9260                                                                | 2         | 0.64%   |
| Intel Wireless 3160                                                                   | 2         | 0.64%   |
| Intel Ultimate N WiFi Link 5300                                                       | 2         | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 0.64%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 0.64%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                             | 2         | 0.64%   |
| Broadcom BCM43227 802.11b/g/n                                                         | 2         | 0.64%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]            | 1         | 0.32%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                   | 1         | 0.32%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.32%   |
| TP-Link 802.11n NIC                                                                   | 1         | 0.32%   |
| Sitecom Europe WL-329 Wireless Dualband USB adapter 300N                              | 1         | 0.32%   |
| Sierra Wireless EM7455                                                                | 1         | 0.32%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 0.32%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.32%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                                | 1         | 0.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 116       | 52.73%  |
| Intel                      | 41        | 18.64%  |
| Qualcomm Atheros           | 18        | 8.18%   |
| Broadcom                   | 15        | 6.82%   |
| Nvidia                     | 8         | 3.64%   |
| Marvell Technology Group   | 8         | 3.64%   |
| Xiaomi                     | 2         | 0.91%   |
| Lenovo                     | 2         | 0.91%   |
| Google                     | 2         | 0.91%   |
| Broadcom Limited           | 2         | 0.91%   |
| ASIX Electronics           | 2         | 0.91%   |
| ZTE WCDMA Technologies MSM | 1         | 0.45%   |
| OPPO Electronics           | 1         | 0.45%   |
| Hewlett-Packard            | 1         | 0.45%   |
| Apple                      | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 74        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 31        | 13.96%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 4.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 3.6%    |
| Nvidia MCP79 Ethernet                                                          | 8         | 3.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 3.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 7         | 3.15%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 3         | 1.35%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.35%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.35%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.35%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.35%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.9%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.9%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.9%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.9%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.9%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.9%    |
| Lenovo ThinkPad Lan                                                            | 2         | 0.9%    |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.9%    |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.9%    |
| Google Nexus/Pixel Device (tether)                                             | 2         | 0.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.9%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 0.9%    |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.9%    |
| ZTE WCDMA MSM ZTE MSM                                                          | 1         | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.45%   |
| OPPO SDM720G-IDP _SN:B922E265                                                  | 1         | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.45%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.45%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.45%   |
| Intel Ethernet Connection I218-V                                               | 1         | 0.45%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.45%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.45%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.45%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.45%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.45%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.45%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.45%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.45%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 0.45%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.45%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.45%   |
| Apple iBridge                                                                  | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 297       | 58.12%  |
| Ethernet | 211       | 41.29%  |
| Modem    | 2         | 0.39%   |
| Unknown  | 1         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 252       | 82.89%  |
| Ethernet | 52        | 17.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 195       | 65.22%  |
| 1     | 100       | 33.44%  |
| 3     | 2         | 0.67%   |
| 0     | 2         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 204       | 68%     |
| Yes  | 96        | 32%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 111       | 40.81%  |
| Apple                           | 35        | 12.87%  |
| Realtek Semiconductor           | 28        | 10.29%  |
| Qualcomm Atheros Communications | 18        | 6.62%   |
| Broadcom                        | 16        | 5.88%   |
| Lite-On Technology              | 15        | 5.51%   |
| IMC Networks                    | 12        | 4.41%   |
| Foxconn / Hon Hai               | 10        | 3.68%   |
| Hewlett-Packard                 | 6         | 2.21%   |
| Cambridge Silicon Radio         | 5         | 1.84%   |
| Toshiba                         | 4         | 1.47%   |
| Ralink                          | 4         | 1.47%   |
| Realtek                         | 3         | 1.1%    |
| Dell                            | 3         | 1.1%    |
| ASUSTek Computer                | 2         | 0.74%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 47        | 17.28%  |
| Intel AX201 Bluetooth                                                               | 25        | 9.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 20        | 7.35%   |
| Apple Bluetooth Host Controller                                                     | 17        | 6.25%   |
| Realtek Bluetooth Radio                                                             | 16        | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 12        | 4.41%   |
| Apple Bluetooth USB Host Controller                                                 | 10        | 3.68%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 2.94%   |
| Intel AX200 Bluetooth                                                               | 8         | 2.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.84%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 1.84%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.47%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.47%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 1.47%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 4         | 1.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 1.47%   |
| Apple Bluetooth HCI                                                                 | 4         | 1.47%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.1%    |
| Lite-On Bluetooth Device                                                            | 3         | 1.1%    |
| Intel AX210 Bluetooth                                                               | 3         | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.1%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 1.1%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.1%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.74%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.74%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.74%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.74%   |
| Intel Bluetooth Device                                                              | 2         | 0.74%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.74%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.74%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.74%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.74%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.37%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.37%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.37%   |
| Toshiba Askey for                                                                   | 1         | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.37%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.37%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.37%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.37%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.37%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.37%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.37%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.37%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.37%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.37%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.37%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.37%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.37%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 238       | 68.79%  |
| AMD                     | 60        | 17.34%  |
| Nvidia                  | 35        | 10.12%  |
| Logitech                | 2         | 0.58%   |
| ESS Technology          | 2         | 0.58%   |
| Texas Instruments       | 1         | 0.29%   |
| SteelSeries ApS         | 1         | 0.29%   |
| Realtek Semiconductor   | 1         | 0.29%   |
| No brand                | 1         | 0.29%   |
| Generalplus Technology  | 1         | 0.29%   |
| Dell                    | 1         | 0.29%   |
| C-Media Electronics     | 1         | 0.29%   |
| BEHRINGER International | 1         | 0.29%   |
| Apple                   | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 31        | 7.24%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 7.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 29        | 6.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 5.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 4.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 17        | 3.97%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 3.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 3.5%    |
| Intel Broadwell-U Audio Controller                                                                | 15        | 3.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 3.04%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 3.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 3.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 2.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 2.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 2.34%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 2.34%   |
| Nvidia MCP79 High Definition Audio                                                                | 8         | 1.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 1.87%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.64%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.4%    |
| AMD High Definition Audio Controller                                                              | 6         | 1.4%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.17%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.17%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.17%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.7%    |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.7%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.7%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.47%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.47%   |
| ESS Technology Asus USB DAC                                                                       | 2         | 0.47%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.47%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.47%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.23%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                                                     | 1         | 0.23%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.23%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.23%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.23%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.23%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.23%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.23%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.23%   |
| No brand CalDigit Thunderbolt 3 Audio                                                             | 1         | 0.23%   |
| Logitech G430 Surround Sound Gaming Headset                                                       | 1         | 0.23%   |
| Logitech 960 Headset                                                                              | 1         | 0.23%   |
| Intel UNA USB audio                                                                               | 1         | 0.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.23%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 37.93%  |
| SK hynix            | 12        | 20.69%  |
| Micron Technology   | 11        | 18.97%  |
| Unknown             | 2         | 3.45%   |
| G.Skill             | 2         | 3.45%   |
| Crucial             | 2         | 3.45%   |
| Transcend           | 1         | 1.72%   |
| SHARETRONIC         | 1         | 1.72%   |
| Ramaxel Technology  | 1         | 1.72%   |
| Kingston            | 1         | 1.72%   |
| GSkill              | 1         | 1.72%   |
| Elpida              | 1         | 1.72%   |
| A-DATA Technology   | 1         | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 3         | 4.55%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 3.03%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s     | 2         | 3.03%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 2         | 3.03%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 3.03%   |
| Unknown RAM Module 8192MB SODIMM DDR3                        | 1         | 1.52%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 1.52%   |
| Transcend RAM JM3200HSE-16G 16384MB SODIMM DDR4 3200MT/s     | 1         | 1.52%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 1.52%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s            | 1         | 1.52%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.52%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1333MT/s              | 1         | 1.52%   |
| SK hynix RAM HMT851S6AMR6R-PB 4096MB Chip DDR3 1600MT/s      | 1         | 1.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s    | 1         | 1.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.52%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 1.52%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 1.52%   |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s       | 1         | 1.52%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s   | 1         | 1.52%   |
| SHARETRONIC RAM Module 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.52%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.52%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s               | 1         | 1.52%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s               | 1         | 1.52%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.52%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s        | 1         | 1.52%   |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s        | 1         | 1.52%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s | 1         | 1.52%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 1         | 1.52%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s        | 1         | 1.52%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.52%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s    | 1         | 1.52%   |
| Micron RAM MT40A1G16KD-062E:E 8192MB SODIMM DDR4 2667MT/s    | 1         | 1.52%   |
| Micron RAM Module 8192MB SODIMM DDR3 1600MT/s                | 1         | 1.52%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                | 1         | 1.52%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 1         | 1.52%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.52%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.52%   |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 1         | 1.52%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s        | 1         | 1.52%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s        | 1         | 1.52%   |
| Kingston RAM KHYXPX-HYJ 8GB SODIMM DDR4 2667MT/s             | 1         | 1.52%   |
| GSkill RAM F4-3200C22-8GRS 8192MB SODIMM DDR4 3200MT/s       | 1         | 1.52%   |
| G.Skill RAM F4-2666C18-16GRS 16GB SODIMM DDR4 2667MT/s       | 1         | 1.52%   |
| G.Skill RAM F3-1600C11-8GSQ 8192MB SODIMM DDR3 1600MT/s      | 1         | 1.52%   |
| G.Skill RAM F3-1600C11-8GSL 8192MB SODIMM DDR3 1600MT/s      | 1         | 1.52%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s        | 1         | 1.52%   |
| Crucial RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 1.52%   |
| Crucial RAM CB8GS2400.C8D 8GB SODIMM DDR4 2400MT/s           | 1         | 1.52%   |
| A-DATA RAM AM1U16BC4P2-B19N 4GB SODIMM DDR3 1600MT/s         | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 27        | 50%     |
| DDR3   | 18        | 33.33%  |
| LPDDR4 | 6         | 11.11%  |
| LPDDR3 | 2         | 3.7%    |
| DDR2   | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 87.04%  |
| Row Of Chips | 6         | 11.11%  |
| Chip         | 1         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 28        | 45.9%   |
| 4096  | 19        | 31.15%  |
| 2048  | 9         | 14.75%  |
| 16384 | 5         | 8.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 14        | 24.14%  |
| 3200    | 11        | 18.97%  |
| 2667    | 10        | 17.24%  |
| 4267    | 4         | 6.9%    |
| 2400    | 4         | 6.9%    |
| 2133    | 3         | 5.17%   |
| 8400    | 2         | 3.45%   |
| 3266    | 2         | 3.45%   |
| 1334    | 2         | 3.45%   |
| 1333    | 2         | 3.45%   |
| 4266    | 1         | 1.72%   |
| 1867    | 1         | 1.72%   |
| 667     | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Canon                           | 2         | 50%     |
| Samsung Electronics             | 1         | 25%     |
| cab Produkttechnik GmbH & Co KG | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung M2020 Series                     | 1         | 25%     |
| Canon PIXMA MG2500 Series                | 1         | 25%     |
| Canon G3000 series                       | 1         | 25%     |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 25%     |

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
| Chicony Electronics                    | 58        | 20.79%  |
| IMC Networks                           | 34        | 12.19%  |
| Apple                                  | 27        | 9.68%   |
| Realtek Semiconductor                  | 25        | 8.96%   |
| Acer                                   | 20        | 7.17%   |
| Quanta                                 | 19        | 6.81%   |
| Microdia                               | 14        | 5.02%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 5.02%   |
| Sunplus Innovation Technology          | 13        | 4.66%   |
| Suyin                                  | 11        | 3.94%   |
| Syntek                                 | 7         | 2.51%   |
| Alcor Micro                            | 7         | 2.51%   |
| Silicon Motion                         | 6         | 2.15%   |
| Luxvisions Innotech Limited            | 4         | 1.43%   |
| Lenovo                                 | 4         | 1.43%   |
| Ricoh                                  | 2         | 0.72%   |
| Logitech                               | 2         | 0.72%   |
| KYE Systems (Mouse Systems)            | 2         | 0.72%   |
| Y Media                                | 1         | 0.36%   |
| Unknown                                | 1         | 0.36%   |
| Sony                                   | 1         | 0.36%   |
| Samsung Electronics                    | 1         | 0.36%   |
| Primax Electronics                     | 1         | 0.36%   |
| Lite-On Technology                     | 1         | 0.36%   |
| kingcome                               | 1         | 0.36%   |
| Importek                               | 1         | 0.36%   |
| Google                                 | 1         | 0.36%   |
| Foxconn / Hon Hai                      | 1         | 0.36%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 13        | 4.63%   |
| IMC Networks Integrated Camera                                             | 11        | 3.91%   |
| Apple Built-in iSight                                                      | 10        | 3.56%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 3.2%    |
| Syntek Integrated Camera                                                   | 7         | 2.49%   |
| Chicony HD WebCam                                                          | 7         | 2.49%   |
| Apple FaceTime HD Camera                                                   | 7         | 2.49%   |
| Realtek Integrated_Webcam_HD                                               | 6         | 2.14%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 1.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 5         | 1.78%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.42%   |
| Realtek USB2.0 HD UVC WebCam                                               | 4         | 1.42%   |
| Quanta VGA WebCam                                                          | 4         | 1.42%   |
| Quanta HP TrueVision HD Camera                                             | 4         | 1.42%   |
| Quanta HD User Facing                                                      | 4         | 1.42%   |
| Chicony USB 2.0 Camera                                                     | 4         | 1.42%   |
| Apple FaceTime Camera                                                      | 4         | 1.42%   |
| Acer Lenovo EasyCamera                                                     | 4         | 1.42%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 3         | 1.07%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 3         | 1.07%   |
| Chicony HP HD Webcam [Fixed]                                               | 3         | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 3         | 1.07%   |
| Alcor Micro USB 2.0 PC cam                                                 | 3         | 1.07%   |
| Acer HD Webcam                                                             | 3         | 1.07%   |
| Acer EasyCamera                                                            | 3         | 1.07%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 2         | 0.71%   |
| Sunplus ASUS USB2.0 Webcam                                                 | 2         | 0.71%   |
| Realtek USB Camera                                                         | 2         | 0.71%   |
| Realtek Integrated Webcam                                                  | 2         | 0.71%   |
| Realtek Acer 640 x 480 laptop camera                                       | 2         | 0.71%   |
| Quanta HP Webcam                                                           | 2         | 0.71%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.71%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 0.71%   |
| Lenovo Integrated Webcam                                                   | 2         | 0.71%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera                           | 2         | 0.71%   |
| IMC Networks ov9734_azurewave_camera                                       | 2         | 0.71%   |
| IMC Networks EasyCamera                                                    | 2         | 0.71%   |
| Chicony VGA WebCam                                                         | 2         | 0.71%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 0.71%   |
| Chicony Sony Visual Communication Camera                                   | 2         | 0.71%   |
| Chicony Lenovo EasyCamera                                                  | 2         | 0.71%   |
| Chicony HP TrueVision HD                                                   | 2         | 0.71%   |
| Chicony HP HD Camera                                                       | 2         | 0.71%   |
| Chicony EasyCamera                                                         | 2         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 2         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 2         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 2         | 0.71%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 0.71%   |
| Apple Built-in iSight [Micron]                                             | 2         | 0.71%   |
| Alcor Micro Acer Integrated Webcam                                         | 2         | 0.71%   |
| Acer Integrated Camera                                                     | 2         | 0.71%   |
| Acer HD Camera                                                             | 2         | 0.71%   |
| Y Media USB Camera                                                         | 1         | 0.36%   |
| Unknown 720p HD Camera                                                     | 1         | 0.36%   |
| Suyin UVC HD Webcam                                                        | 1         | 0.36%   |
| Suyin USB 2.0 Camera                                                       | 1         | 0.36%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 0.36%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 0.36%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 15        | 33.33%  |
| Validity Sensors           | 12        | 26.67%  |
| LighTuning Technology      | 6         | 13.33%  |
| Upek                       | 5         | 11.11%  |
| Shenzhen Goodix Technology | 5         | 11.11%  |
| Elan Microelectronics      | 2         | 4.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 4         | 8.89%   |
| Shenzhen Goodix  FingerPrint Device                        | 4         | 8.89%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 4         | 8.89%   |
| Unknown                                                    | 4         | 8.89%   |
| Validity Sensors VFS491                                    | 3         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 3         | 6.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 3         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 4.44%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 4.44%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 4.44%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.22%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2.22%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.22%   |
| Shenzhen Goodix FingerPrint                                | 1         | 2.22%   |
| Elan ELAN:Fingerprint                                      | 1         | 2.22%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 40%     |
| Alcor Micro           | 5         | 33.33%  |
| Lenovo                | 2         | 13.33%  |
| O2 Micro              | 1         | 6.67%   |
| Gemalto (was Gemplus) | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 5         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor         | 3         | 20%     |
| Lenovo Integrated Smart Card Reader                    | 2         | 13.33%  |
| Broadcom 58200                                         | 2         | 13.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 6.67%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 6.67%   |
| Broadcom 5880                                          | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 208       | 69.33%  |
| 1     | 69        | 23%     |
| 2     | 22        | 7.33%   |
| 3     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 45        | 39.47%  |
| Net/wireless          | 16        | 14.04%  |
| Multimedia controller | 15        | 13.16%  |
| Chipcard              | 15        | 13.16%  |
| Graphics card         | 9         | 7.89%   |
| Camera                | 4         | 3.51%   |
| Bluetooth             | 4         | 3.51%   |
| Card reader           | 3         | 2.63%   |
| Net/ethernet          | 2         | 1.75%   |
| Storage               | 1         | 0.88%   |

