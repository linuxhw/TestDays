Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ENVY Laptop 13-ah0xxx       | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | [ccb4dc3d9a](https://linux-hardware.org/?probe=ccb4dc3d9a) | Sep 09, 2021 |
| Toshiba       | Satellite C75D-B            | [0f52ac751b](https://linux-hardware.org/?probe=0f52ac751b) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [97b34f8c7f](https://linux-hardware.org/?probe=97b34f8c7f) | Sep 08, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 20RAS1Q800     | [a4d93ee5d2](https://linux-hardware.org/?probe=a4d93ee5d2) | Sep 08, 2021 |
| HP            | EliteBook 8560p             | [6bff88fb9e](https://linux-hardware.org/?probe=6bff88fb9e) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [3fc588a18d](https://linux-hardware.org/?probe=3fc588a18d) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [fd38e5bf9d](https://linux-hardware.org/?probe=fd38e5bf9d) | Sep 08, 2021 |
| HP            | EliteBook 840 G3            | [22d88098a9](https://linux-hardware.org/?probe=22d88098a9) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [be8d4bd453](https://linux-hardware.org/?probe=be8d4bd453) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [47317abce2](https://linux-hardware.org/?probe=47317abce2) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [98874d48b2](https://linux-hardware.org/?probe=98874d48b2) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f872b42a74](https://linux-hardware.org/?probe=f872b42a74) | Sep 07, 2021 |
| Acer          | V5-171                      | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| HP            | Notebook                    | [62a2618cde](https://linux-hardware.org/?probe=62a2618cde) | Sep 07, 2021 |
| Toshiba       | Satellite L755              | [92d22f65bf](https://linux-hardware.org/?probe=92d22f65bf) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Dell          | Precision 3520              | [15e6e2c91d](https://linux-hardware.org/?probe=15e6e2c91d) | Sep 07, 2021 |
| Dell          | Precision 5550              | [8ae36d685d](https://linux-hardware.org/?probe=8ae36d685d) | Sep 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | [368f488133](https://linux-hardware.org/?probe=368f488133) | Sep 07, 2021 |
| MSI           | GL62 7RDX                   | [be53fd4c86](https://linux-hardware.org/?probe=be53fd4c86) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| HP            | Pavilion dv5                | [27607d962e](https://linux-hardware.org/?probe=27607d962e) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | [46499caf7a](https://linux-hardware.org/?probe=46499caf7a) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Lenovo        | G505s 20255                 | [263eeefef0](https://linux-hardware.org/?probe=263eeefef0) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | [8cd745db58](https://linux-hardware.org/?probe=8cd745db58) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | 255 G3                      | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Acer          | Aspire A315-31              | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| HP            | EliteBook 840 G1            | [980716e0a8](https://linux-hardware.org/?probe=980716e0a8) | Sep 03, 2021 |
| ASUSTek       | GR8                         | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire E5-521G              | [d1aa71f003](https://linux-hardware.org/?probe=d1aa71f003) | Sep 02, 2021 |
| Acer          | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Acer          | Aspire E1-522               | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Toshiba       | Satellite C850D-11C         | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | ENVY 15                     | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Insyde        | i101c                       | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | Pavilion 15                 | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| Acer          | Aspire 5100                 | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Acer          | AO722                       | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| TianBei       | TB-H7                       | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| Acer          | Aspire 8940G                | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| HP            | ProBook 450 G2              | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| Acer          | Nitro AN515-55              | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Acer          | Swift SF114-34              | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| HP            | ProBook 450 G2              | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| Dell          | Inspiron 7537               | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Dell          | XPS L501X                   | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| Dell          | Inspiron 3582               | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| Dell          | XPS 13 9370                 | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| HP            | ProBook 650 G2              | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| HP            | Unknown                     | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| Razer         | Book 13 - RZ09-0357         | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Dell          | Vostro 5490                 | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-27-generic | 76        | 67.26%  |
| 5.11.0-34-generic | 8         | 7.08%   |
| 5.11.0-25-generic | 7         | 6.19%   |
| 5.8.0-53-generic  | 6         | 5.31%   |
| 5.8.0-59-generic  | 5         | 4.42%   |
| 5.8.0-55-generic  | 5         | 4.42%   |
| 5.8.0-50-generic  | 4         | 3.54%   |
| 5.8.0-63-generic  | 1         | 0.88%   |
| 5.10.0-1044-oem   | 1         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 89        | 80.18%  |
| 5.8.0   | 21        | 18.92%  |
| 5.10.0  | 1         | 0.9%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 89        | 80.18%  |
| 5.8     | 21        | 18.92%  |
| 5.10    | 1         | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 109       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 108       | 99.08%  |
| Unknown | 1         | 0.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 106       | 96.36%  |
| Wayland | 3         | 2.73%   |
| Unknown | 1         | 0.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 90        | 82.57%  |
| GDM     | 19        | 17.43%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 34        | 31.19%  |
| en_GB | 12        | 11.01%  |
| de_DE | 11        | 10.09%  |
| pt_BR | 10        | 9.17%   |
| es_ES | 7         | 6.42%   |
| en_IN | 7         | 6.42%   |
| es_MX | 4         | 3.67%   |
| en_CA | 3         | 2.75%   |
| nl_NL | 2         | 1.83%   |
| hu_HU | 2         | 1.83%   |
| en_NZ | 2         | 1.83%   |
| ru_UA | 1         | 0.92%   |
| pt_PT | 1         | 0.92%   |
| pl_PL | 1         | 0.92%   |
| ja_JP | 1         | 0.92%   |
| it_IT | 1         | 0.92%   |
| fr_FR | 1         | 0.92%   |
| fr_BE | 1         | 0.92%   |
| es_PE | 1         | 0.92%   |
| es_CL | 1         | 0.92%   |
| en_ZA | 1         | 0.92%   |
| en_PH | 1         | 0.92%   |
| de_CH | 1         | 0.92%   |
| de_AT | 1         | 0.92%   |
| cs_CZ | 1         | 0.92%   |
| bg_BG | 1         | 0.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 73        | 66.97%  |
| BIOS | 36        | 33.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 103       | 94.5%   |
| Zfs     | 3         | 2.75%   |
| Btrfs   | 2         | 1.83%   |
| Overlay | 1         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 90        | 82.57%  |
| GPT     | 19        | 17.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 108       | 99.08%  |
| Yes       | 1         | 0.92%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 87.16%  |
| Yes       | 14        | 12.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 22        | 20.18%  |
| Hewlett-Packard     | 20        | 18.35%  |
| Acer                | 18        | 16.51%  |
| Dell                | 17        | 15.6%   |
| ASUSTek Computer    | 10        | 9.17%   |
| Toshiba             | 4         | 3.67%   |
| Apple               | 4         | 3.67%   |
| LG Electronics      | 3         | 2.75%   |
| Sony                | 2         | 1.83%   |
| MSI                 | 2         | 1.83%   |
| TianBei             | 1         | 0.92%   |
| Samsung Electronics | 1         | 0.92%   |
| Razer               | 1         | 0.92%   |
| Packard Bell        | 1         | 0.92%   |
| Insyde              | 1         | 0.92%   |
| Fujitsu             | 1         | 0.92%   |
| Unknown             | 1         | 0.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Notebook                           | 2         | 1.83%   |
| HP ENVY Sleekbook 4 PC                | 2         | 1.83%   |
| Dell Inspiron 5566                    | 2         | 1.83%   |
| Unknown                               | 2         | 1.83%   |
| Toshiba Satellite S75Dt-A             | 1         | 0.92%   |
| Toshiba Satellite L755                | 1         | 0.92%   |
| Toshiba Satellite C850D-11C           | 1         | 0.92%   |
| Toshiba Satellite C75D-B              | 1         | 0.92%   |
| TianBei TB-H7                         | 1         | 0.92%   |
| Sony VPCS135FX                        | 1         | 0.92%   |
| Sony VGN-SR5                          | 1         | 0.92%   |
| Samsung 550P5C/550P7C                 | 1         | 0.92%   |
| Razer Book 13 - RZ09-0357             | 1         | 0.92%   |
| Packard Bell DOT S                    | 1         | 0.92%   |
| MSI GS75 Stealth 10SF                 | 1         | 0.92%   |
| MSI GL62 7RDX                         | 1         | 0.92%   |
| LG S460-G.BG31P1                      | 1         | 0.92%   |
| LG A410-K.BE47P1                      | 1         | 0.92%   |
| LG 17U70N-R.AAS7U1                    | 1         | 0.92%   |
| Lenovo Yoga 3 Pro-1370 80HE           | 1         | 0.92%   |
| Lenovo ThinkPad Yoga 11e 20DAS0SF00   | 1         | 0.92%   |
| Lenovo ThinkPad X131e 3371AL2         | 1         | 0.92%   |
| Lenovo ThinkPad W520 4284AW3          | 1         | 0.92%   |
| Lenovo ThinkPad T520 4242W4F          | 1         | 0.92%   |
| Lenovo ThinkPad T440p 20AWS1CH00      | 1         | 0.92%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW | 1         | 0.92%   |
| Lenovo ThinkPad E15 Gen 2 20TD000HZA  | 1         | 0.92%   |
| Lenovo ThinkPad E14 20RAS1Q800        | 1         | 0.92%   |
| Lenovo IdeaPad Z510 20287             | 1         | 0.92%   |
| Lenovo IdeaPad Y570 0862              | 1         | 0.92%   |
| Lenovo IdeaPad S540-14API 81NH        | 1         | 0.92%   |
| Lenovo IdeaPad 5 15ALC05 82LN         | 1         | 0.92%   |
| Lenovo IdeaPad 330-15IKB 81DE         | 1         | 0.92%   |
| Lenovo IdeaPad 310 Touch-15IKB 80TW   | 1         | 0.92%   |
| Lenovo IdeaPad 3 14ADA05 81W0         | 1         | 0.92%   |
| Lenovo IdeaPad 100-15IBD 80QQ         | 1         | 0.92%   |
| Lenovo G505s 20255                    | 1         | 0.92%   |
| Lenovo G50-70 20351                   | 1         | 0.92%   |
| Lenovo G50-30 80G0                    | 1         | 0.92%   |
| Lenovo B50-70 80EU                    | 1         | 0.92%   |
| Lenovo B50-30 20382                   | 1         | 0.92%   |
| Insyde i101c                          | 1         | 0.92%   |
| HP ProBook 650 G2                     | 1         | 0.92%   |
| HP ProBook 6450b                      | 1         | 0.92%   |
| HP ProBook 450 G2                     | 1         | 0.92%   |
| HP ProBook 430 G6                     | 1         | 0.92%   |
| HP Pavilion Gaming Laptop 15-ec0xxx   | 1         | 0.92%   |
| HP Pavilion dv5                       | 1         | 0.92%   |
| HP Pavilion 15                        | 1         | 0.92%   |
| HP ENVY Laptop 13-ah0xxx              | 1         | 0.92%   |
| HP ENVY 15                            | 1         | 0.92%   |
| HP ENVY 14                            | 1         | 0.92%   |
| HP EliteBook 8560p                    | 1         | 0.92%   |
| HP EliteBook 840 G3                   | 1         | 0.92%   |
| HP EliteBook 840 G1                   | 1         | 0.92%   |
| HP 255 G3                             | 1         | 0.92%   |
| HP 15                                 | 1         | 0.92%   |
| Fujitsu LIFEBOOK AH532                | 1         | 0.92%   |
| Dell XPS L501X                        | 1         | 0.92%   |
| Dell XPS 15 9560                      | 1         | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 13        | 11.93%  |
| Lenovo ThinkPad    | 8         | 7.34%   |
| Lenovo IdeaPad     | 8         | 7.34%   |
| Dell Inspiron      | 7         | 6.42%   |
| HP ENVY            | 5         | 4.59%   |
| Toshiba Satellite  | 4         | 3.67%   |
| HP ProBook         | 4         | 3.67%   |
| Dell XPS           | 4         | 3.67%   |
| HP Pavilion        | 3         | 2.75%   |
| HP EliteBook       | 3         | 2.75%   |
| Dell Precision     | 3         | 2.75%   |
| HP Notebook        | 2         | 1.83%   |
| ASUS ASUS          | 2         | 1.83%   |
| Apple MacBookPro11 | 2         | 1.83%   |
| Acer Swift         | 2         | 1.83%   |
| Unknown            | 2         | 1.83%   |
| TianBei TB-H7      | 1         | 0.92%   |
| Sony VPCS135FX     | 1         | 0.92%   |
| Sony VGN-SR5       | 1         | 0.92%   |
| Samsung 550P5C     | 1         | 0.92%   |
| Razer Book         | 1         | 0.92%   |
| Packard Bell DOT   | 1         | 0.92%   |
| MSI GS75           | 1         | 0.92%   |
| MSI GL62           | 1         | 0.92%   |
| LG S460-G.BG31P1   | 1         | 0.92%   |
| LG A410-K.BE47P1   | 1         | 0.92%   |
| LG 17U70N-R.AAS7U1 | 1         | 0.92%   |
| Lenovo Yoga        | 1         | 0.92%   |
| Lenovo G505s       | 1         | 0.92%   |
| Lenovo G50-70      | 1         | 0.92%   |
| Lenovo G50-30      | 1         | 0.92%   |
| Lenovo B50-70      | 1         | 0.92%   |
| Lenovo B50-30      | 1         | 0.92%   |
| Insyde i101c       | 1         | 0.92%   |
| HP 255             | 1         | 0.92%   |
| HP 15              | 1         | 0.92%   |
| Fujitsu LIFEBOOK   | 1         | 0.92%   |
| Dell Vostro        | 1         | 0.92%   |
| Dell Latitude      | 1         | 0.92%   |
| Dell G3            | 1         | 0.92%   |
| ASUS X550LD        | 1         | 0.92%   |
| ASUS X406UAR       | 1         | 0.92%   |
| ASUS X405UA        | 1         | 0.92%   |
| ASUS VivoBook      | 1         | 0.92%   |
| ASUS TUF           | 1         | 0.92%   |
| ASUS K73SV         | 1         | 0.92%   |
| ASUS K56CA         | 1         | 0.92%   |
| ASUS GR8           | 1         | 0.92%   |
| Apple MacBook4     | 1         | 0.92%   |
| Apple MacBook3     | 1         | 0.92%   |
| Acer V5-171        | 1         | 0.92%   |
| Acer Nitro         | 1         | 0.92%   |
| Acer AO722         | 1         | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 20        | 18.35%  |
| 2020 | 13        | 11.93%  |
| 2014 | 13        | 11.93%  |
| 2019 | 12        | 11.01%  |
| 2018 | 11        | 10.09%  |
| 2011 | 9         | 8.26%   |
| 2012 | 7         | 6.42%   |
| 2013 | 5         | 4.59%   |
| 2016 | 4         | 3.67%   |
| 2015 | 4         | 3.67%   |
| 2008 | 4         | 3.67%   |
| 2017 | 3         | 2.75%   |
| 2010 | 2         | 1.83%   |
| 2009 | 1         | 0.92%   |
| 2006 | 1         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 109       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 88        | 80.73%  |
| Enabled  | 21        | 19.27%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 109       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 36        | 33.03%  |
| 3.01-4.0   | 32        | 29.36%  |
| 8.01-16.0  | 18        | 16.51%  |
| 16.01-24.0 | 13        | 11.93%  |
| 32.01-64.0 | 7         | 6.42%   |
| 1.01-2.0   | 3         | 2.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 48        | 41.38%  |
| 2.01-3.0 | 40        | 34.48%  |
| 3.01-4.0 | 19        | 16.38%  |
| 4.01-8.0 | 7         | 6.03%   |
| 0.51-1.0 | 2         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 75.23%  |
| 2      | 24        | 22.02%  |
| 3      | 3         | 2.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 59.63%  |
| Yes       | 44        | 40.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 86.24%  |
| No        | 15        | 13.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 98.17%  |
| No        | 2         | 1.83%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 77.98%  |
| No        | 24        | 22.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 16        | 14.68%  |
| Germany      | 14        | 12.84%  |
| Brazil       | 13        | 11.93%  |
| UK           | 8         | 7.34%   |
| India        | 8         | 7.34%   |
| Spain        | 7         | 6.42%   |
| Mexico       | 5         | 4.59%   |
| Hungary      | 3         | 2.75%   |
| Canada       | 3         | 2.75%   |
| South Africa | 2         | 1.83%   |
| Romania      | 2         | 1.83%   |
| New Zealand  | 2         | 1.83%   |
| Netherlands  | 2         | 1.83%   |
| Italy        | 2         | 1.83%   |
| France       | 2         | 1.83%   |
| Austria      | 2         | 1.83%   |
| Vietnam      | 1         | 0.92%   |
| Ukraine      | 1         | 0.92%   |
| Turkey       | 1         | 0.92%   |
| Switzerland  | 1         | 0.92%   |
| Sweden       | 1         | 0.92%   |
| Poland       | 1         | 0.92%   |
| Philippines  | 1         | 0.92%   |
| Madagascar   | 1         | 0.92%   |
| Kenya        | 1         | 0.92%   |
| Japan        | 1         | 0.92%   |
| Indonesia    | 1         | 0.92%   |
| Greece       | 1         | 0.92%   |
| Czechia      | 1         | 0.92%   |
| Colombia     | 1         | 0.92%   |
| Chile        | 1         | 0.92%   |
| Bulgaria     | 1         | 0.92%   |
| Belgium      | 1         | 0.92%   |
| Angola       | 1         | 0.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| S??o Lu?­s               | 3         | 2.73%   |
| Vienna                   | 2         | 1.82%   |
| Taboao da Serra          | 2         | 1.82%   |
| Madrid                   | 2         | 1.82%   |
| London                   | 2         | 1.82%   |
| Hyderabad                | 2         | 1.82%   |
| Chennai                  | 2         | 1.82%   |
| Auckland                 | 2         | 1.82%   |
| Zurich                   | 1         | 0.91%   |
| Zaventem                 | 1         | 0.91%   |
| Zacatecas City           | 1         | 0.91%   |
| Zabrze                   | 1         | 0.91%   |
| Yokohama                 | 1         | 0.91%   |
| Veracruz                 | 1         | 0.91%   |
| Vancouver                | 1         | 0.91%   |
| Twinsburg                | 1         | 0.91%   |
| Sutton Coldfield         | 1         | 0.91%   |
| Stuttgart                | 1         | 0.91%   |
| Stockholm                | 1         | 0.91%   |
| Stadskanaal              | 1         | 0.91%   |
| Spremberg                | 1         | 0.91%   |
| Seville                  | 1         | 0.91%   |
| S??o Jo??o del Rei       | 1         | 0.91%   |
| Santa Cruz do Rio Pardo  | 1         | 0.91%   |
| Sant Carles de la Rapita | 1         | 0.91%   |
| San Francisco            | 1         | 0.91%   |
| Sainte-Marie             | 1         | 0.91%   |
| Rome                     | 1         | 0.91%   |
| Reus                     | 1         | 0.91%   |
| R??sselsheim am Main     | 1         | 0.91%   |
| Quezon City              | 1         | 0.91%   |
| Pretoria                 | 1         | 0.91%   |
| Pittsburgh               | 1         | 0.91%   |
| Philadelphia             | 1         | 0.91%   |
| Ohmbach                  | 1         | 0.91%   |
| Nyiregyhaza              | 1         | 0.91%   |
| Nottingham               | 1         | 0.91%   |
| Noblesville              | 1         | 0.91%   |
| New York                 | 1         | 0.91%   |
| New Haven                | 1         | 0.91%   |
| Naumburg                 | 1         | 0.91%   |
| Nairobi                  | 1         | 0.91%   |
| MÃ©rida                  | 1         | 0.91%   |
| Mumbai                   | 1         | 0.91%   |
| Most                     | 1         | 0.91%   |
| Morro do Chapeu          | 1         | 0.91%   |
| Mooresville              | 1         | 0.91%   |
| Montreal                 | 1         | 0.91%   |
| Montana                  | 1         | 0.91%   |
| Milan                    | 1         | 0.91%   |
| Mexico City              | 1         | 0.91%   |
| Manchester               | 1         | 0.91%   |
| Macei??                  | 1         | 0.91%   |
| Maca?©                   | 1         | 0.91%   |
| Luanda                   | 1         | 0.91%   |
| Lathen                   | 1         | 0.91%   |
| Landshut                 | 1         | 0.91%   |
| Kyiv                     | 1         | 0.91%   |
| Kolkata                  | 1         | 0.91%   |
| Knoxville                | 1         | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 21     | 15.63%  |
| Samsung Electronics | 18        | 22     | 14.06%  |
| Toshiba             | 13        | 13     | 10.16%  |
| WDC                 | 10        | 10     | 7.81%   |
| Sandisk             | 10        | 12     | 7.81%   |
| Hitachi             | 6         | 6      | 4.69%   |
| Crucial             | 6         | 6      | 4.69%   |
| Kingston            | 5         | 6      | 3.91%   |
| HGST                | 5         | 6      | 3.91%   |
| Unknown             | 4         | 5      | 3.13%   |
| A-DATA Technology   | 4         | 4      | 3.13%   |
| Fujitsu             | 3         | 4      | 2.34%   |
| SPCC                | 2         | 2      | 1.56%   |
| SK Hynix            | 2         | 3      | 1.56%   |
| LITEONIT            | 2         | 3      | 1.56%   |
| KIOXIA              | 2         | 2      | 1.56%   |
| Intenso             | 2         | 2      | 1.56%   |
| Intel               | 2         | 2      | 1.56%   |
| Apple               | 2         | 2      | 1.56%   |
| Vaseky              | 1         | 1      | 0.78%   |
| Team                | 1         | 1      | 0.78%   |
| SABRENT             | 1         | 1      | 0.78%   |
| PNY                 | 1         | 2      | 0.78%   |
| Phison              | 1         | 1      | 0.78%   |
| Patriot             | 1         | 1      | 0.78%   |
| Micron Technology   | 1         | 2      | 0.78%   |
| KingSpec            | 1         | 1      | 0.78%   |
| China               | 1         | 2      | 0.78%   |
| BUFFALO             | 1         | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 3.01%   |
| Toshiba MQ01ABF050 500GB                | 3         | 2.26%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 2.26%   |
| HGST HTS725050A7E630 500GB              | 3         | 2.26%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 1.5%    |
| Unknown SD/MMC/MS PRO 64GB              | 2         | 1.5%    |
| Toshiba MQ02ABD100H 1TB                 | 2         | 1.5%    |
| SK Hynix NVMe SSD Drive 512GB           | 2         | 1.5%    |
| Seagate ST9500325AS 500GB               | 2         | 1.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 1.5%    |
| SanDisk SSD PLUS 480GB                  | 2         | 1.5%    |
| Sandisk NVMe SSD Drive 256GB            | 2         | 1.5%    |
| Samsung NVMe SSD Drive 512GB            | 2         | 1.5%    |
| KIOXIA NVMe SSD Drive 512GB             | 2         | 1.5%    |
| Kingston SA400S37480G 480GB SSD         | 2         | 1.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.75%   |
| WDC WD5000LPVT-22G33T0 500GB            | 1         | 0.75%   |
| WDC WD5000BPVT-22HXZT3 500GB            | 1         | 0.75%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.75%   |
| WDC WD10JPVX-60JC3T1 1TB                | 1         | 0.75%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 0.75%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB    | 1         | 0.75%   |
| WDC PC SN520 NVMe 256GB                 | 1         | 0.75%   |
| Vaseky V820/256G 256GB                  | 1         | 0.75%   |
| Unknown NCard  32GB                     | 1         | 0.75%   |
| Unknown MMC Card  32GB                  | 1         | 0.75%   |
| Unknown MMC Card  128GB                 | 1         | 0.75%   |
| Toshiba THNSNJ128GCSU 128GB SSD         | 1         | 0.75%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 0.75%   |
| Toshiba MK5056GSY 500GB                 | 1         | 0.75%   |
| Toshiba MK3265GSX 320GB                 | 1         | 0.75%   |
| Toshiba MK3261GSYN 320GB                | 1         | 0.75%   |
| Toshiba KXG50ZNV1T02 NVMe 1024GB        | 1         | 0.75%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 1         | 0.75%   |
| Toshiba KBG40ZMT128G MEMORY 128GB       | 1         | 0.75%   |
| Team T253X1120G 120GB SSD               | 1         | 0.75%   |
| SPCC SPCCSolidStateDisk 256GB SSD       | 1         | 0.75%   |
| SPCC Solid State Disk 1TB               | 1         | 0.75%   |
| SK Hynix BC501 HFM512GDJTNG-8310A 512GB | 1         | 0.75%   |
| Seagate USB 120GB                       | 1         | 0.75%   |
| Seagate ST9750423AS 752GB               | 1         | 0.75%   |
| Seagate ST500LM034-2GH17A 500GB         | 1         | 0.75%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 0.75%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 0.75%   |
| Seagate ST320LM001 HN-M320MBB 320GB     | 1         | 0.75%   |
| Seagate ST2000LM007-1R8174 2TB          | 1         | 0.75%   |
| Seagate ST1000LM048-2E7172 1TB          | 1         | 0.75%   |
| Seagate ST1000LM014-1EJ1 1TB            | 1         | 0.75%   |
| SanDisk X400 M.2 2280 256GB SSD         | 1         | 0.75%   |
| SanDisk SSD PLUS 1000GB                 | 1         | 0.75%   |
| SanDisk SSD i100 24GB                   | 1         | 0.75%   |
| SanDisk SD8SN8U256G1002 256GB SSD       | 1         | 0.75%   |
| Sandisk NVMe SSD Drive 512GB            | 1         | 0.75%   |
| Sandisk NVMe SSD Drive 128GB            | 1         | 0.75%   |
| Samsung SSD SM841N mSATA 256GB SED      | 1         | 0.75%   |
| Samsung SSD PM830 2.5 7mm 128GB         | 1         | 0.75%   |
| Samsung SSD 970 EVO Plus 500GB          | 1         | 0.75%   |
| Samsung SSD 860 PRO 256GB               | 1         | 0.75%   |
| Samsung SSD 860 EVO 250GB               | 1         | 0.75%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 19     | 37.25%  |
| Toshiba             | 9         | 9      | 17.65%  |
| WDC                 | 6         | 6      | 11.76%  |
| Hitachi             | 6         | 6      | 11.76%  |
| HGST                | 5         | 6      | 9.8%    |
| Samsung Electronics | 3         | 3      | 5.88%   |
| Fujitsu             | 3         | 4      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 14.89%  |
| SanDisk             | 6         | 7      | 12.77%  |
| Crucial             | 6         | 6      | 12.77%  |
| Kingston            | 5         | 6      | 10.64%  |
| A-DATA Technology   | 3         | 3      | 6.38%   |
| Toshiba             | 2         | 2      | 4.26%   |
| SPCC                | 2         | 2      | 4.26%   |
| LITEONIT            | 2         | 3      | 4.26%   |
| Intenso             | 2         | 2      | 4.26%   |
| Apple               | 2         | 2      | 4.26%   |
| WDC                 | 1         | 1      | 2.13%   |
| Team                | 1         | 1      | 2.13%   |
| SABRENT             | 1         | 1      | 2.13%   |
| PNY                 | 1         | 2      | 2.13%   |
| Patriot             | 1         | 1      | 2.13%   |
| Micron Technology   | 1         | 2      | 2.13%   |
| KingSpec            | 1         | 1      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| China               | 1         | 2      | 2.13%   |
| BUFFALO             | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 51        | 53     | 41.8%   |
| SSD     | 42        | 54     | 34.43%  |
| NVMe    | 23        | 29     | 18.85%  |
| Unknown | 4         | 5      | 3.28%   |
| MMC     | 2         | 3      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 86        | 104    | 72.88%  |
| NVMe | 23        | 29     | 19.49%  |
| SAS  | 7         | 8      | 5.93%   |
| MMC  | 2         | 3      | 1.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 75     | 68.48%  |
| 0.51-1.0   | 27        | 30     | 29.35%  |
| 1.01-2.0   | 2         | 2      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 39        | 35.78%  |
| 101-250        | 29        | 26.61%  |
| 501-1000       | 18        | 16.51%  |
| 51-100         | 10        | 9.17%   |
| 1001-2000      | 5         | 4.59%   |
| 21-50          | 4         | 3.67%   |
| 1-20           | 2         | 1.83%   |
| More than 3000 | 1         | 0.92%   |
| Unknown        | 1         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 57        | 52.29%  |
| 21-50    | 28        | 25.69%  |
| 101-250  | 10        | 9.17%   |
| 51-100   | 7         | 6.42%   |
| 251-500  | 4         | 3.67%   |
| 501-1000 | 2         | 1.83%   |
| Unknown  | 1         | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB    | 2         | 2      | 50%     |
| WDC WD10JPVX-22JC3T0 1TB   | 1         | 1      | 25%     |
| HGST HTS725050A7E630 500GB | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 90        | 119    | 80.36%  |
| Works    | 17        | 20     | 15.18%  |
| Malfunc  | 4         | 4      | 3.57%   |
| Failed   | 1         | 1      | 0.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 77        | 64.17%  |
| AMD                              | 17        | 14.17%  |
| Samsung Electronics              | 11        | 9.17%   |
| Sandisk                          | 6         | 5%      |
| KIOXIA                           | 3         | 2.5%    |
| SK Hynix                         | 2         | 1.67%   |
| Toshiba America Info Systems     | 1         | 0.83%   |
| Silicon Integrated Systems [SiS] | 1         | 0.83%   |
| Phison Electronics               | 1         | 0.83%   |
| ADATA Technology                 | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 11.2%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 8.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 6.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 5.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 5.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 4.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 4%      |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 4         | 3.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 3.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 3.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 3.2%    |
| Samsung NVMe Controller                                                          | 3         | 2.4%    |
| KIOXIA Non-Volatile memory controller                                            | 3         | 2.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 2.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 2.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.4%    |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 1.6%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.6%    |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.6%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.6%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.8%    |
| SK Hynix BC511                                                                   | 1         | 0.8%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.8%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.8%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.8%    |
| Samsung Electronics SATA controller                                              | 1         | 0.8%    |
| Samsung Apple PCIe SSD                                                           | 1         | 0.8%    |
| Phison E12 NVMe Controller                                                       | 1         | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.8%    |
| Intel SSD 660P Series                                                            | 1         | 0.8%    |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.8%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.8%    |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 1         | 0.8%    |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile       | 1         | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.8%    |
| AMD IXP SB4x0 IDE Controller                                                     | 1         | 0.8%    |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 0.8%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 85        | 69.67%  |
| NVMe | 23        | 18.85%  |
| RAID | 8         | 6.56%   |
| IDE  | 6         | 4.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 88        | 80.73%  |
| AMD    | 21        | 19.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 4.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 3.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.83%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 1.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.83%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 1.83%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.83%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.83%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.83%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 1.83%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 1.83%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 2         | 1.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.83%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.83%   |
| AMD A10-5750M APU with Radeon HD Graphics     | 2         | 1.83%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.92%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.92%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.92%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.92%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.92%   |
| Intel Pentium CPU 3550M @ 2.30GHz             | 1         | 0.92%   |
| Intel Core i7-4940MX CPU @ 3.10GHz            | 1         | 0.92%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 1         | 0.92%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.92%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.92%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.92%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.92%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.92%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.92%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 0.92%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.92%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.92%   |
| Intel Core i5-7440HQ CPU @ 2.80GHz            | 1         | 0.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 0.92%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 0.92%   |
| Intel Core i5-4258U CPU @ 2.40GHz             | 1         | 0.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.92%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 0.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.92%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 0.92%   |
| Intel Core i5-10400H CPU @ 2.60GHz            | 1         | 0.92%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 0.92%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.92%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 0.92%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 0.92%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 0.92%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 0.92%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 0.92%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 0.92%   |
| Intel Core i3-2367M CPU @ 1.40GHz             | 1         | 0.92%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 0.92%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 0.92%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 0.92%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz          | 1         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 38        | 34.86%  |
| Intel Core i7           | 20        | 18.35%  |
| Intel Core i3           | 8         | 7.34%   |
| Intel Celeron           | 6         | 5.5%    |
| Intel Core 2 Duo        | 5         | 4.59%   |
| AMD Ryzen 5             | 5         | 4.59%   |
| Other                   | 4         | 3.67%   |
| Intel Pentium           | 3         | 2.75%   |
| Intel Atom              | 2         | 1.83%   |
| AMD E1                  | 2         | 1.83%   |
| AMD A6                  | 2         | 1.83%   |
| AMD A10                 | 2         | 1.83%   |
| Intel Pentium Silver    | 1         | 0.92%   |
| Intel Pentium Dual-Core | 1         | 0.92%   |
| AMD Turion 64 Mobile    | 1         | 0.92%   |
| AMD Ryzen 7 PRO         | 1         | 0.92%   |
| AMD Ryzen 7             | 1         | 0.92%   |
| AMD FX                  | 1         | 0.92%   |
| AMD E2                  | 1         | 0.92%   |
| AMD E                   | 1         | 0.92%   |
| AMD C-60                | 1         | 0.92%   |
| AMD Athlon              | 1         | 0.92%   |
| AMD A8                  | 1         | 0.92%   |
| AMD A4                  | 1         | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 60        | 55.05%  |
| 4      | 44        | 40.37%  |
| 8      | 2         | 1.83%   |
| 6      | 2         | 1.83%   |
| 1      | 1         | 0.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 109       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 80        | 73.39%  |
| 1      | 29        | 26.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 109       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 10%     |
| 0x306a9    | 10        | 9.09%   |
| 0x40651    | 9         | 8.18%   |
| 0x206a7    | 8         | 7.27%   |
| 0x806ea    | 7         | 6.36%   |
| 0x806ec    | 5         | 4.55%   |
| 0x306d4    | 4         | 3.64%   |
| 0x306c3    | 4         | 3.64%   |
| 0x30678    | 4         | 3.64%   |
| 0xa0652    | 3         | 2.73%   |
| 0x806c1    | 3         | 2.73%   |
| 0x20655    | 3         | 2.73%   |
| 0x08108109 | 3         | 2.73%   |
| 0x05000119 | 3         | 2.73%   |
| 0x806e9    | 2         | 1.82%   |
| 0x20652    | 2         | 1.82%   |
| 0x1067a    | 2         | 1.82%   |
| 0x07030106 | 2         | 1.82%   |
| 0x06001119 | 2         | 1.82%   |
| 0x906ea    | 1         | 0.91%   |
| 0x906e9    | 1         | 0.91%   |
| 0x906c0    | 1         | 0.91%   |
| 0x706a1    | 1         | 0.91%   |
| 0x6fd      | 1         | 0.91%   |
| 0x6fb      | 1         | 0.91%   |
| 0x6fa      | 1         | 0.91%   |
| 0x506c9    | 1         | 0.91%   |
| 0x406e3    | 1         | 0.91%   |
| 0x406c4    | 1         | 0.91%   |
| 0x40661    | 1         | 0.91%   |
| 0x30661    | 1         | 0.91%   |
| 0x106e5    | 1         | 0.91%   |
| 0x10676    | 1         | 0.91%   |
| 0x08608102 | 1         | 0.91%   |
| 0x08600106 | 1         | 0.91%   |
| 0x08600104 | 1         | 0.91%   |
| 0x08108102 | 1         | 0.91%   |
| 0x07030105 | 1         | 0.91%   |
| 0x07030104 | 1         | 0.91%   |
| 0x07000110 | 1         | 0.91%   |
| 0x0700010f | 1         | 0.91%   |
| 0x06003106 | 1         | 0.91%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 21        | 19.27%  |
| Haswell       | 14        | 12.84%  |
| IvyBridge     | 10        | 9.17%   |
| SandyBridge   | 8         | 7.34%   |
| Silvermont    | 6         | 5.5%    |
| Zen+          | 5         | 4.59%   |
| Westmere      | 5         | 4.59%   |
| Puma          | 4         | 3.67%   |
| Broadwell     | 4         | 3.67%   |
| TigerLake     | 3         | 2.75%   |
| Penryn        | 3         | 2.75%   |
| Core          | 3         | 2.75%   |
| CometLake     | 3         | 2.75%   |
| Bobcat        | 3         | 2.75%   |
| Zen 2         | 2         | 1.83%   |
| Skylake       | 2         | 1.83%   |
| Piledriver    | 2         | 1.83%   |
| Nehalem       | 2         | 1.83%   |
| Jaguar        | 2         | 1.83%   |
| Tremont       | 1         | 0.92%   |
| Steamroller   | 1         | 0.92%   |
| K8 Hammer     | 1         | 0.92%   |
| Goldmont plus | 1         | 0.92%   |
| Goldmont      | 1         | 0.92%   |
| Bonnell       | 1         | 0.92%   |
| Unknown       | 1         | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 78        | 58.21%  |
| AMD                              | 28        | 20.9%   |
| Nvidia                           | 27        | 20.15%  |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 7.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 6.47%   |
| Intel UHD Graphics 620                                                                   | 7         | 5.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 4.32%   |
| Intel HD Graphics 620                                                                    | 5         | 3.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 3.6%    |
| AMD Picasso                                                                              | 5         | 3.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 2.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.16%   |
| Intel HD Graphics 630                                                                    | 3         | 2.16%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.44%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.44%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.44%   |
| AMD Richland [Radeon HD 8650G]                                                           | 2         | 1.44%   |
| AMD Renoir                                                                               | 2         | 1.44%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.44%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.72%   |
| Nvidia TU117M                                                                            | 1         | 0.72%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.72%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.72%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.72%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.72%   |
| Nvidia GM107GLM [Quadro M620 Mobile]                                                     | 1         | 0.72%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.72%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.72%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.72%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.72%   |
| Nvidia GF108M [GeForce GT 555M]                                                          | 1         | 0.72%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.72%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.72%   |
| Nvidia GF108M [GeForce GT 435M]                                                          | 1         | 0.72%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.72%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                                | 1         | 0.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.72%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.72%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.72%   |
| Intel Haswell Integrated Graphics Controller                                             | 1         | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.72%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.72%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 0.72%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.72%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1         | 0.72%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 0.72%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 1         | 0.72%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 51.38%  |
| Intel + Nvidia | 18        | 16.51%  |
| 1 x AMD        | 18        | 16.51%  |
| 1 x Nvidia     | 6         | 5.5%    |
| Intel + AMD    | 4         | 3.67%   |
| 2 x AMD        | 3         | 2.75%   |
| AMD + Nvidia   | 3         | 2.75%   |
| 1 x SiS        | 1         | 0.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 90        | 82.57%  |
| Proprietary | 17        | 15.6%   |
| Unknown     | 2         | 1.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 60.55%  |
| 1.01-2.0   | 18        | 16.51%  |
| 0.01-0.5   | 10        | 9.17%   |
| 0.51-1.0   | 9         | 8.26%   |
| 3.01-4.0   | 5         | 4.59%   |
| 7.01-8.0   | 1         | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 22        | 18.64%  |
| LG Display              | 20        | 16.95%  |
| AU Optronics            | 20        | 16.95%  |
| Samsung Electronics     | 13        | 11.02%  |
| BOE                     | 10        | 8.47%   |
| Sharp                   | 6         | 5.08%   |
| Chi Mei Optoelectronics | 5         | 4.24%   |
| Apple                   | 4         | 3.39%   |
| Lenovo                  | 3         | 2.54%   |
| Dell                    | 3         | 2.54%   |
| PANDA                   | 2         | 1.69%   |
| Acer                    | 2         | 1.69%   |
| Vizio                   | 1         | 0.85%   |
| LGD                     | 1         | 0.85%   |
| LG Philips              | 1         | 0.85%   |
| Hewlett-Packard         | 1         | 0.85%   |
| HannStar                | 1         | 0.85%   |
| Goldstar                | 1         | 0.85%   |
| BenQ                    | 1         | 0.85%   |
| AOC                     | 1         | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch         | 3         | 2.52%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch             | 2         | 1.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.68%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch         | 2         | 1.68%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch         | 2         | 1.68%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch           | 2         | 1.68%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch          | 2         | 1.68%   |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch           | 2         | 1.68%   |
| Vizio E43u-D2 VIZ1018 3840x2160 953x543mm 43.2-inch                     | 1         | 0.84%   |
| Sharp LQ134R1JX48 SHP1528 3840x2400 288x180mm 13.4-inch                 | 1         | 0.84%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                 | 1         | 0.84%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                 | 1         | 0.84%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                 | 1         | 0.84%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                 | 1         | 0.84%   |
| Sharp HDMI SHP101E 1920x1080 820x460mm 37.0-inch                        | 1         | 0.84%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch       | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch    | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch    | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch    | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch    | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch    | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 256x144mm 11.6-inch    | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch    | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch    | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1         | 0.84%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.84%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                 | 1         | 0.84%   |
| LGD LCD Monitor 3840x1200                                               | 1         | 0.84%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch            | 1         | 0.84%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch            | 1         | 0.84%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 0.84%   |
| LG Display LCD Monitor LGD0597 1920x1080 294x165mm 13.3-inch            | 1         | 0.84%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch            | 1         | 0.84%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD0468 1366x768 340x190mm 15.3-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD02D1 1600x900 382x215mm 17.3-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD0293 1366x768 321x181mm 14.5-inch             | 1         | 0.84%   |
| LG Display LCD Monitor LGD028D 1366x768 310x174mm 14.0-inch             | 1         | 0.84%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.84%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 0.84%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                 | 1         | 0.84%   |
| Hewlett-Packard LCD Monitor E241i                                       | 1         | 0.84%   |
| HannStar HT231 HSD5173 1920x1080 509x286mm 23.0-inch                    | 1         | 0.84%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch               | 1         | 0.84%   |
| Dell U2414H DELA0B2 1920x1080 530x300mm 24.0-inch                       | 1         | 0.84%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 1         | 0.84%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                       | 1         | 0.84%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch         | 1         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 1         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 340x190mm 15.3-inch        | 1         | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 52        | 45.61%  |
| 1920x1080 (FHD)   | 36        | 31.58%  |
| 1600x900 (HD+)    | 6         | 5.26%   |
| 3840x2160 (4K)    | 5         | 4.39%   |
| 1280x800 (WXGA)   | 4         | 3.51%   |
| 3840x2400         | 2         | 1.75%   |
| 2560x1600         | 2         | 1.75%   |
| 3840x1200         | 1         | 0.88%   |
| 3200x1800 (QHD+)  | 1         | 0.88%   |
| 2880x1800         | 1         | 0.88%   |
| 2560x1440 (QHD)   | 1         | 0.88%   |
| 1920x1200 (WUXGA) | 1         | 0.88%   |
| 1024x600          | 1         | 0.88%   |
| Unknown           | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 57        | 48.72%  |
| 13      | 21        | 17.95%  |
| 14      | 11        | 9.4%    |
| 24      | 5         | 4.27%   |
| 17      | 5         | 4.27%   |
| 11      | 4         | 3.42%   |
| Unknown | 3         | 2.56%   |
| 23      | 2         | 1.71%   |
| 18      | 2         | 1.71%   |
| 84      | 1         | 0.85%   |
| 74      | 1         | 0.85%   |
| 37      | 1         | 0.85%   |
| 27      | 1         | 0.85%   |
| 25      | 1         | 0.85%   |
| 21      | 1         | 0.85%   |
| 10      | 1         | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 78        | 66.67%  |
| 201-300     | 16        | 13.68%  |
| 501-600     | 9         | 7.69%   |
| 351-400     | 5         | 4.27%   |
| 401-500     | 3         | 2.56%   |
| Unknown     | 3         | 2.56%   |
| 1501-2000   | 2         | 1.71%   |
| 801-900     | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 93        | 87.74%  |
| 16/10   | 10        | 9.43%   |
| Unknown | 3         | 2.83%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 57        | 48.31%  |
| 81-90          | 23        | 19.49%  |
| 71-80          | 9         | 7.63%   |
| 201-250        | 8         | 6.78%   |
| 121-130        | 5         | 4.24%   |
| 51-60          | 4         | 3.39%   |
| Unknown        | 3         | 2.54%   |
| More than 1000 | 2         | 1.69%   |
| 141-150        | 2         | 1.69%   |
| 41-50          | 1         | 0.85%   |
| 301-350        | 1         | 0.85%   |
| 251-300        | 1         | 0.85%   |
| 501-1000       | 1         | 0.85%   |
| 91-100         | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 56        | 48.7%   |
| 121-160       | 30        | 26.09%  |
| 51-100        | 15        | 13.04%  |
| 161-240       | 6         | 5.22%   |
| More than 240 | 5         | 4.35%   |
| Unknown       | 3         | 2.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 96        | 87.27%  |
| 2     | 12        | 10.91%  |
| 3     | 1         | 0.91%   |
| 0     | 1         | 0.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 62        | 33.88%  |
| Intel                            | 49        | 26.78%  |
| Qualcomm Atheros                 | 34        | 18.58%  |
| Broadcom                         | 15        | 8.2%    |
| Broadcom Limited                 | 5         | 2.73%   |
| Ralink                           | 3         | 1.64%   |
| Marvell Technology Group         | 3         | 1.64%   |
| DisplayLink                      | 2         | 1.09%   |
| T & A Mobile Phones              | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| Samsung Electronics              | 1         | 0.55%   |
| Qualcomm                         | 1         | 0.55%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.55%   |
| MediaTek                         | 1         | 0.55%   |
| ICS Advent                       | 1         | 0.55%   |
| Huawei Technologies              | 1         | 0.55%   |
| D-Link System                    | 1         | 0.55%   |
| ASIX Electronics                 | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 39        | 18.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 14        | 6.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 9         | 4.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 6         | 2.86%   |
| Intel Wireless 7260                                                           | 6         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 1.9%    |
| Intel WiFi Link 5100                                                          | 4         | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 1.9%    |
| Broadcom BCM43142 802.11b/g/n                                                 | 4         | 1.9%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 3         | 1.43%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 3         | 1.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3         | 1.43%   |
| Intel Wireless 3160                                                           | 3         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 3         | 1.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 1.43%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 3         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2         | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 2         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 0.95%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 0.95%   |
| Intel Wireless 8260                                                           | 2         | 0.95%   |
| Intel Wireless 7265                                                           | 2         | 0.95%   |
| Intel Wi-Fi 6 AX201                                                           | 2         | 0.95%   |
| Intel Ethernet Connection I219-V                                              | 2         | 0.95%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 0.95%   |
| Intel Centrino Wireless-N 2230                                                | 2         | 0.95%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 0.95%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 0.95%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 2         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 2         | 0.95%   |
| T & A Mobile Phones TCL T790S                                                 | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.48%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1         | 0.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.48%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 0.48%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1         | 0.48%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1         | 0.48%   |
| Realtek 802.11ac NIC                                                          | 1         | 0.48%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]                   | 1         | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.48%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.48%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.48%   |
| OnePlus (Shenzhen) IN2013                                                     | 1         | 0.48%   |
| MediaTek Titan                                                                | 1         | 0.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 41.82%  |
| Qualcomm Atheros      | 28        | 25.45%  |
| Realtek Semiconductor | 16        | 14.55%  |
| Broadcom              | 12        | 10.91%  |
| Ralink                | 3         | 2.73%   |
| Broadcom Limited      | 3         | 2.73%   |
| Qualcomm              | 1         | 0.91%   |
| D-Link System         | 1         | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 9         | 8.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 6         | 5.41%   |
| Intel Wireless 7260                                                           | 6         | 5.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 4.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 3.6%    |
| Intel WiFi Link 5100                                                          | 4         | 3.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 3.6%    |
| Broadcom BCM43142 802.11b/g/n                                                 | 4         | 3.6%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 3         | 2.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 3         | 2.7%    |
| Intel Wireless 3160                                                           | 3         | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 3         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 1.8%    |
| Intel Wireless 8260                                                           | 2         | 1.8%    |
| Intel Wireless 7265                                                           | 2         | 1.8%    |
| Intel Wi-Fi 6 AX201                                                           | 2         | 1.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 1.8%    |
| Intel Centrino Wireless-N 2230                                                | 2         | 1.8%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 1.8%    |
| Intel Centrino Advanced-N 6200                                                | 2         | 1.8%    |
| Broadcom BCM4321 802.11a/b/g/n                                                | 2         | 1.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 2         | 1.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.9%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.9%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 0.9%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1         | 0.9%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1         | 0.9%    |
| Realtek 802.11ac NIC                                                          | 1         | 0.9%    |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]                   | 1         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.9%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.9%    |
| Intel Wireless 8265 / 8275                                                    | 1         | 0.9%    |
| Intel Wireless 3165                                                           | 1         | 0.9%    |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.9%    |
| Intel Wi-Fi 6 AX200                                                           | 1         | 0.9%    |
| Intel Centrino Wireless-N 130                                                 | 1         | 0.9%    |
| Intel Centrino Wireless-N 105                                                 | 1         | 0.9%    |
| Intel Centrino Ultimate-N 6300                                                | 1         | 0.9%    |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1         | 0.9%    |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870]          | 1         | 0.9%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                    | 1         | 0.9%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                    | 1         | 0.9%    |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                   | 1         | 0.9%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 1         | 0.9%    |
| Broadcom BCM43225 802.11b/g/n                                                 | 1         | 0.9%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1         | 0.9%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 57        | 58.16%  |
| Intel                            | 13        | 13.27%  |
| Qualcomm Atheros                 | 10        | 10.2%   |
| Broadcom                         | 4         | 4.08%   |
| Marvell Technology Group         | 3         | 3.06%   |
| DisplayLink                      | 2         | 2.04%   |
| Broadcom Limited                 | 2         | 2.04%   |
| Silicon Integrated Systems [SiS] | 1         | 1.02%   |
| Samsung Electronics              | 1         | 1.02%   |
| OnePlus Technology (Shenzhen)    | 1         | 1.02%   |
| MediaTek                         | 1         | 1.02%   |
| ICS Advent                       | 1         | 1.02%   |
| Huawei Technologies              | 1         | 1.02%   |
| ASIX Electronics                 | 1         | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 39.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 14.29%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 3.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 3.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.04%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 2.04%   |
| Intel Ethernet Connection I219-V                                  | 2         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.04%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.02%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.02%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.02%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.02%   |
| OnePlus (Shenzhen) IN2013                                         | 1         | 1.02%   |
| MediaTek Titan                                                    | 1         | 1.02%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.02%   |
| Intel Ethernet controller                                         | 1         | 1.02%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.02%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.02%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.02%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 1.02%   |
| Huawei VOG-L09                                                    | 1         | 1.02%   |
| DisplayLink dynadock U3.0                                         | 1         | 1.02%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 1.02%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.02%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 1.02%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 1.02%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 107       | 52.97%  |
| Ethernet | 94        | 46.53%  |
| Unknown  | 1         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 100       | 54.95%  |
| Ethernet | 81        | 44.51%  |
| Unknown  | 1         | 0.55%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 85        | 77.98%  |
| 1     | 22        | 20.18%  |
| 3     | 1         | 0.92%   |
| 0     | 1         | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 75        | 68.18%  |
| Yes  | 35        | 31.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 36.47%  |
| Qualcomm Atheros Communications | 12        | 14.12%  |
| Foxconn / Hon Hai               | 7         | 8.24%   |
| Realtek Semiconductor           | 6         | 7.06%   |
| Lite-On Technology              | 6         | 7.06%   |
| IMC Networks                    | 6         | 7.06%   |
| Broadcom                        | 5         | 5.88%   |
| Apple                           | 4         | 4.71%   |
| Ralink                          | 3         | 3.53%   |
| Foxconn International           | 2         | 2.35%   |
| Toshiba                         | 1         | 1.18%   |
| Dell                            | 1         | 1.18%   |
| Alps Electric                   | 1         | 1.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 16        | 18.82%  |
| Intel Bluetooth wireless interface                                                  | 9         | 10.59%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 8.24%   |
| Realtek Bluetooth Radio                                                             | 5         | 5.88%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 3.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 3.53%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 3.53%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 3.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 2.35%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 2.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 2.35%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.35%   |
| IMC Networks Bluetooth Device                                                       | 2         | 2.35%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 2.35%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 2.35%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.35%   |
| Apple Bluetooth HCI                                                                 | 2         | 2.35%   |
| Toshiba BCM43142A0                                                                  | 1         | 1.18%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.18%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.18%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.18%   |
| Lite-On BCM43142A0                                                                  | 1         | 1.18%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.18%   |
| IMC Networks Bluetooth                                                              | 1         | 1.18%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1.18%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.18%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.18%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 1.18%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 1.18%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.18%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 1.18%   |
| Broadcom Bluetooth                                                                  | 1         | 1.18%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.18%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 86        | 68.25%  |
| AMD                              | 24        | 19.05%  |
| Nvidia                           | 15        | 11.9%   |
| Silicon Integrated Systems [SiS] | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 8.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 6.88%   |
| AMD FCH Azalia Controller                                                                         | 11        | 6.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 5.63%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 5.63%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 8         | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 4.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 4.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 3.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 3.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 2.5%    |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.88%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.88%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.88%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.25%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.25%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.63%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.63%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.63%   |
| Intel Jasper Lake HD Graphics SGPC                                                                | 1         | 0.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.63%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.63%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.63%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.63%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 1         | 0.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 26.67%  |
| SK Hynix            | 6         | 20%     |
| Micron Technology   | 6         | 20%     |
| Kingston            | 3         | 10%     |
| A-DATA Technology   | 3         | 10%     |
| Unknown             | 1         | 3.33%   |
| Strontium           | 1         | 3.33%   |
| Ramaxel Technology  | 1         | 3.33%   |
| Crucial             | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Kingston RAM ACR16D3LS1KFG/4G 4096MB SODIMM DDR3 1600MT/s           | 2         | 5.88%   |
| A-DATA RAM AE4S240038G17-BHYA 8192MB SODIMM DDR4 2400MT/s           | 2         | 5.88%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 2.94%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s                | 1         | 2.94%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.94%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.94%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.94%   |
| SK Hynix RAM HMT112S6BFR6C-G7 1024MB SODIMM DDR3 1067MT/s           | 1         | 2.94%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 2.94%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 2.94%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 2.94%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s       | 1         | 2.94%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 2.94%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s            | 1         | 2.94%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s            | 1         | 2.94%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 2.94%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 2.94%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 2.94%   |
| Samsung RAM M471B2873FHS-CH9 1024MB SODIMM DDR3 1334MT/s            | 1         | 2.94%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 2.94%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s      | 1         | 2.94%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s            | 1         | 2.94%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 2.94%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s   | 1         | 2.94%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 1         | 2.94%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 1         | 2.94%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 1         | 2.94%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s       | 1         | 2.94%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s           | 1         | 2.94%   |
| Kingston RAM K821PJ-MID 16384MB SODIMM DDR4 2400MT/s                | 1         | 2.94%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s              | 1         | 2.94%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4096MB SODIMM DDR4 2400MT/s             | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 46.43%  |
| DDR3   | 10        | 35.71%  |
| SDRAM  | 2         | 7.14%   |
| LPDDR3 | 2         | 7.14%   |
| LPDDR4 | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 81.48%  |
| Row Of Chips | 5         | 18.52%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 13        | 44.83%  |
| 8192  | 10        | 34.48%  |
| 2048  | 4         | 13.79%  |
| 16384 | 1         | 3.45%   |
| 1024  | 1         | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 9         | 29.03%  |
| 2667  | 5         | 16.13%  |
| 3200  | 4         | 12.9%   |
| 2400  | 4         | 12.9%   |
| 4199  | 2         | 6.45%   |
| 2133  | 2         | 6.45%   |
| 4267  | 1         | 3.23%   |
| 1867  | 1         | 3.23%   |
| 1334  | 1         | 3.23%   |
| 1333  | 1         | 3.23%   |
| 1067  | 1         | 3.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 17        | 17.89%  |
| IMC Networks                           | 12        | 12.63%  |
| Realtek Semiconductor                  | 11        | 11.58%  |
| Acer                                   | 10        | 10.53%  |
| Microdia                               | 8         | 8.42%   |
| Sunplus Innovation Technology          | 6         | 6.32%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 6.32%   |
| Suyin                                  | 4         | 4.21%   |
| Quanta                                 | 4         | 4.21%   |
| Lite-On Technology                     | 4         | 4.21%   |
| Syntek                                 | 2         | 2.11%   |
| Primax Electronics                     | 2         | 2.11%   |
| Silicon Motion                         | 1         | 1.05%   |
| Samsung Electronics                    | 1         | 1.05%   |
| Ricoh                                  | 1         | 1.05%   |
| Luxvisions Innotech Limited            | 1         | 1.05%   |
| Importek                               | 1         | 1.05%   |
| Generalplus Technology                 | 1         | 1.05%   |
| Apple                                  | 1         | 1.05%   |
| ALi                                    | 1         | 1.05%   |
| Alcor Micro                            | 1         | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                             | 5         | 5.26%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 4         | 4.21%   |
| Acer Lenovo EasyCamera                                                   | 4         | 4.21%   |
| Microdia Integrated_Webcam_HD                                            | 3         | 3.16%   |
| IMC Networks Integrated Camera                                           | 3         | 3.16%   |
| Chicony TOSHIBA Web Camera - HD                                          | 3         | 3.16%   |
| Chicony HD WebCam                                                        | 3         | 3.16%   |
| Sunplus Integrated_Webcam_HD                                             | 2         | 2.11%   |
| Sunplus HD WebCam                                                        | 2         | 2.11%   |
| Realtek USB Camera                                                       | 2         | 2.11%   |
| Quanta HD User Facing                                                    | 2         | 2.11%   |
| Microdia Integrated Webcam                                               | 2         | 2.11%   |
| Lite-On HP HD Camera                                                     | 2         | 2.11%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 2         | 2.11%   |
| Chicony Integrated Camera                                                | 2         | 2.11%   |
| Chicony HP Truevision HD                                                 | 2         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 2         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                         | 2         | 2.11%   |
| Acer Integrated Camera                                                   | 2         | 2.11%   |
| Syntek USB Camera Device                                                 | 1         | 1.05%   |
| Syntek Integrated Camera                                                 | 1         | 1.05%   |
| Suyin HP Truevision HD                                                   | 1         | 1.05%   |
| Suyin HD Video WebCam                                                    | 1         | 1.05%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 1         | 1.05%   |
| Suyin 1.3M HD WebCam                                                     | 1         | 1.05%   |
| Sunplus Integrated Webcam                                                | 1         | 1.05%   |
| Sunplus HD User Facing                                                   | 1         | 1.05%   |
| Silicon Motion WebCam SC-13HDL11939N                                     | 1         | 1.05%   |
| Samsung Galaxy A5 (MTP)                                                  | 1         | 1.05%   |
| Ricoh Visual Communication Camera VGP-VCC9 [R5U870]                      | 1         | 1.05%   |
| Realtek Lenovo EasyCamera                                                | 1         | 1.05%   |
| Realtek Integrated Webcam                                                | 1         | 1.05%   |
| Realtek HD Webcam - Realtek                                              | 1         | 1.05%   |
| Realtek HD WebCam                                                        | 1         | 1.05%   |
| Quanta VGA WebCam                                                        | 1         | 1.05%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                     | 1         | 1.05%   |
| Primax Villem                                                            | 1         | 1.05%   |
| Primax HP HD Webcam [Fixed]                                              | 1         | 1.05%   |
| Microdia Webcam Vitade AF                                                | 1         | 1.05%   |
| Microdia Lenovo EasyCamera                                               | 1         | 1.05%   |
| Microdia Integrated HD Webcam                                            | 1         | 1.05%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 1.05%   |
| Lite-On HP Wide Vision HD Camera                                         | 1         | 1.05%   |
| Lite-On HP HD Webcam                                                     | 1         | 1.05%   |
| Importek HP Webcam                                                       | 1         | 1.05%   |
| IMC Networks USB Camera                                                  | 1         | 1.05%   |
| IMC Networks Lenovo EasyCamera                                           | 1         | 1.05%   |
| IMC Networks EasyCamera                                                  | 1         | 1.05%   |
| Generalplus GENERAL WEBCAM                                               | 1         | 1.05%   |
| Chicony WebCam                                                           | 1         | 1.05%   |
| Chicony VGA Webcam                                                       | 1         | 1.05%   |
| Chicony LG HD WebCam                                                     | 1         | 1.05%   |
| Chicony HD WebCam (Acer)                                                 | 1         | 1.05%   |
| Chicony FJ Camera                                                        | 1         | 1.05%   |
| Chicony EasyCamera                                                       | 1         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 1         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.05%   |
| Apple Built-in iSight [Micron]                                           | 1         | 1.05%   |
| ALi Gateway Webcam                                                       | 1         | 1.05%   |
| Alcor Micro Asus Integrated Webcam                                       | 1         | 1.05%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 47.62%  |
| Shenzhen Goodix Technology | 4         | 19.05%  |
| Upek                       | 3         | 14.29%  |
| LighTuning Technology      | 2         | 9.52%   |
| Synaptics                  | 1         | 4.76%   |
| Focal-systems.Corp         | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 14.29%  |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 9.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 9.52%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 9.52%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 4.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.76%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 4.76%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 4.76%   |
| LighTuning Fingerprint Reader                                              | 1         | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 4.76%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Broadcom    | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 72        | 66.06%  |
| 1     | 28        | 25.69%  |
| 2     | 9         | 8.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 21        | 45.65%  |
| Graphics card         | 9         | 19.57%  |
| Net/wireless          | 6         | 13.04%  |
| Bluetooth             | 3         | 6.52%   |
| Multimedia controller | 2         | 4.35%   |
| Chipcard              | 2         | 4.35%   |
| Net/ethernet          | 1         | 2.17%   |
| Flash memory          | 1         | 2.17%   |
| Dvb card              | 1         | 2.17%   |

