Endless - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Endless.

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

Total: 4619

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A315-53              | [e21cdc2b24](https://linux-hardware.org/?probe=e21cdc2b24) | Dec 16, 2025 |
| Toshiba       | Satellite C50-C             | [774214cc4c](https://linux-hardware.org/?probe=774214cc4c) | Dec 14, 2025 |
| Toshiba       | Satellite C50-C             | [fdd9560c98](https://linux-hardware.org/?probe=fdd9560c98) | Dec 14, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a585a186ce](https://linux-hardware.org/?probe=a585a186ce) | Dec 09, 2025 |
| Microtech     | CoreBook                    | [a1477e9883](https://linux-hardware.org/?probe=a1477e9883) | Nov 22, 2025 |
| Acer          | Extensa 5230                | [2d0ffe0b6f](https://linux-hardware.org/?probe=2d0ffe0b6f) | Nov 16, 2025 |
| Acer          | Aspire ES1-132              | [5439048149](https://linux-hardware.org/?probe=5439048149) | Nov 16, 2025 |
| Dell          | Latitude E4310              | [ae4341575b](https://linux-hardware.org/?probe=ae4341575b) | Nov 13, 2025 |
| Dell          | Latitude E4310              | [d7948e3eac](https://linux-hardware.org/?probe=d7948e3eac) | Nov 12, 2025 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [2fd54bdb64](https://linux-hardware.org/?probe=2fd54bdb64) | Oct 20, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d5ade82cec](https://linux-hardware.org/?probe=d5ade82cec) | Oct 01, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ad99fec91d](https://linux-hardware.org/?probe=ad99fec91d) | Sep 14, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [21045a1580](https://linux-hardware.org/?probe=21045a1580) | Aug 29, 2025 |
| ASUSTek       | X540NA                      | [e4974dee02](https://linux-hardware.org/?probe=e4974dee02) | Aug 27, 2025 |
| ASUSTek       | X540NA                      | [b8f786f6f1](https://linux-hardware.org/?probe=b8f786f6f1) | Aug 27, 2025 |
| Acer          | Aspire 5732Z                | [3e5ea8b92f](https://linux-hardware.org/?probe=3e5ea8b92f) | Aug 15, 2025 |
| Toshiba       | Satellite L355D             | [af4d0b5710](https://linux-hardware.org/?probe=af4d0b5710) | Aug 05, 2025 |
| ASUSTek       | X541UAK                     | [df0053f97f](https://linux-hardware.org/?probe=df0053f97f) | Aug 02, 2025 |
| ASUSTek       | X541UAK                     | [eb9a6b1027](https://linux-hardware.org/?probe=eb9a6b1027) | Aug 02, 2025 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f8ad33d302](https://linux-hardware.org/?probe=f8ad33d302) | Jul 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [250f8b9bb4](https://linux-hardware.org/?probe=250f8b9bb4) | Jul 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b4d9280c15](https://linux-hardware.org/?probe=b4d9280c15) | Jul 03, 2025 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [0598cec32f](https://linux-hardware.org/?probe=0598cec32f) | Jun 30, 2025 |
| Notebook      | N150SD/N155SD               | [c0fb6166f0](https://linux-hardware.org/?probe=c0fb6166f0) | Jun 21, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6d50762c78](https://linux-hardware.org/?probe=6d50762c78) | Jun 15, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7a28822b71](https://linux-hardware.org/?probe=7a28822b71) | Jun 15, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [68668100e3](https://linux-hardware.org/?probe=68668100e3) | Jun 11, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [11a30aeac3](https://linux-hardware.org/?probe=11a30aeac3) | Jun 02, 2025 |
| Acer          | Aspire A515-54G             | [9df7c25df1](https://linux-hardware.org/?probe=9df7c25df1) | May 20, 2025 |
| Positivo      | CHT14B                      | [54eb009f20](https://linux-hardware.org/?probe=54eb009f20) | May 20, 2025 |
| Positivo      | CHT14B                      | [dd56acbb8c](https://linux-hardware.org/?probe=dd56acbb8c) | May 20, 2025 |
| Positivo      | Master N130i                | [fb88e448cc](https://linux-hardware.org/?probe=fb88e448cc) | May 12, 2025 |
| ASUSTek       | X455LD                      | [f894a1beb5](https://linux-hardware.org/?probe=f894a1beb5) | May 10, 2025 |
| Acer          | Aspire ES1-111M             | [d12ec9a3ac](https://linux-hardware.org/?probe=d12ec9a3ac) | May 10, 2025 |
| HP            | 255 15.6 inch G10 Notebo... | [a04bfa844a](https://linux-hardware.org/?probe=a04bfa844a) | May 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [22eb421620](https://linux-hardware.org/?probe=22eb421620) | Apr 26, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3c8a62739b](https://linux-hardware.org/?probe=3c8a62739b) | Apr 26, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e1e9f5250d](https://linux-hardware.org/?probe=e1e9f5250d) | Apr 26, 2025 |
| HP            | 255 15.6 inch G10 Notebo... | [ce6717c7ea](https://linux-hardware.org/?probe=ce6717c7ea) | Apr 25, 2025 |
| HP            | 255 15.6 inch G10 Notebo... | [aaeb216ee2](https://linux-hardware.org/?probe=aaeb216ee2) | Apr 25, 2025 |
| HP            | Pavilion dv6                | [38dc311890](https://linux-hardware.org/?probe=38dc311890) | Apr 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4cc81cd409](https://linux-hardware.org/?probe=4cc81cd409) | Apr 13, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0f40c1c922](https://linux-hardware.org/?probe=0f40c1c922) | Apr 12, 2025 |
| Acer          | Aspire ES1-732              | [c0fb610863](https://linux-hardware.org/?probe=c0fb610863) | Apr 05, 2025 |
| Compaq        | Presario CQ-31              | [0f122c9159](https://linux-hardware.org/?probe=0f122c9159) | Apr 04, 2025 |
| Lenovo        | ThinkPad E520 1143KDG       | [2d851e190c](https://linux-hardware.org/?probe=2d851e190c) | Apr 03, 2025 |
| Lenovo        | ThinkPad E520 1143KDG       | [1472ec0d73](https://linux-hardware.org/?probe=1472ec0d73) | Apr 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4d2791516a](https://linux-hardware.org/?probe=4d2791516a) | Apr 01, 2025 |
| Dell          | XPS 15 9570                 | [9cf10a17a2](https://linux-hardware.org/?probe=9cf10a17a2) | Mar 27, 2025 |
| Lenovo        | Yoga 2 11 20332             | [d1fbb31a2a](https://linux-hardware.org/?probe=d1fbb31a2a) | Mar 22, 2025 |
| Lenovo        | Yoga 2 11 20332             | [151a2927f1](https://linux-hardware.org/?probe=151a2927f1) | Mar 22, 2025 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [1efda9aabf](https://linux-hardware.org/?probe=1efda9aabf) | Mar 18, 2025 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [3ad5d28cab](https://linux-hardware.org/?probe=3ad5d28cab) | Mar 18, 2025 |
| Microtech     | CoreBook                    | [6c4dfb0dc2](https://linux-hardware.org/?probe=6c4dfb0dc2) | Mar 16, 2025 |
| Dell          | Precision 3530              | [91c23372a4](https://linux-hardware.org/?probe=91c23372a4) | Mar 15, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d139fa0e2b](https://linux-hardware.org/?probe=d139fa0e2b) | Mar 15, 2025 |
| Dell          | Latitude E6530              | [50ed736590](https://linux-hardware.org/?probe=50ed736590) | Mar 09, 2025 |
| Acer          | Aspire A515-54              | [3c953f2d72](https://linux-hardware.org/?probe=3c953f2d72) | Mar 09, 2025 |
| Acer          | TravelMate B118-M           | [0bd269c39b](https://linux-hardware.org/?probe=0bd269c39b) | Feb 25, 2025 |
| Acer          | Nitro AN515-54              | [e2023f56ca](https://linux-hardware.org/?probe=e2023f56ca) | Feb 24, 2025 |
| ASUSTek       | X541UVK                     | [d19dd1844f](https://linux-hardware.org/?probe=d19dd1844f) | Feb 23, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6e65ad4bd6](https://linux-hardware.org/?probe=6e65ad4bd6) | Feb 20, 2025 |
| HP            | Laptop 15-bw0xx             | [90da992c8f](https://linux-hardware.org/?probe=90da992c8f) | Feb 16, 2025 |
| HP            | Laptop 15-bw0xx             | [b148b97371](https://linux-hardware.org/?probe=b148b97371) | Feb 15, 2025 |
| Lenovo        | 3000 N500 423346G           | [a419d328d2](https://linux-hardware.org/?probe=a419d328d2) | Feb 14, 2025 |
| Acer          | Nitro AN517-54              | [9425e1b40d](https://linux-hardware.org/?probe=9425e1b40d) | Feb 11, 2025 |
| HP            | Laptop 15-db0xxx            | [d346ae8874](https://linux-hardware.org/?probe=d346ae8874) | Feb 07, 2025 |
| Lenovo        | ThinkPad T430 2349L29       | [f67f6be3c3](https://linux-hardware.org/?probe=f67f6be3c3) | Feb 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5db5c40620](https://linux-hardware.org/?probe=5db5c40620) | Feb 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [183f99a22b](https://linux-hardware.org/?probe=183f99a22b) | Feb 03, 2025 |
| Acer          | Aspire A115-32              | [a33977d70a](https://linux-hardware.org/?probe=a33977d70a) | Jan 29, 2025 |
| Acer          | Nitro AN515-54              | [43a30aeafd](https://linux-hardware.org/?probe=43a30aeafd) | Jan 28, 2025 |
| Lenovo        | G50-70 20351                | [0aab701d35](https://linux-hardware.org/?probe=0aab701d35) | Jan 25, 2025 |
| Acer          | Aspire A315-53              | [063842130a](https://linux-hardware.org/?probe=063842130a) | Jan 15, 2025 |
| Acer          | Predator PHN16-72           | [90c78ec2cc](https://linux-hardware.org/?probe=90c78ec2cc) | Jan 09, 2025 |
| HP            | Laptop 15-db0xxx            | [df331d8cb3](https://linux-hardware.org/?probe=df331d8cb3) | Jan 05, 2025 |
| ASUSTek       | X541UVK                     | [84cde5a12c](https://linux-hardware.org/?probe=84cde5a12c) | Dec 30, 2024 |
| HP            | 250 G8 Notebook PC          | [2163561381](https://linux-hardware.org/?probe=2163561381) | Dec 27, 2024 |
| Acer          | Aspire A517-51G             | [4c16c27b7b](https://linux-hardware.org/?probe=4c16c27b7b) | Dec 25, 2024 |
| HP            | ProBook 645 G2              | [fdd8177594](https://linux-hardware.org/?probe=fdd8177594) | Dec 23, 2024 |
| HP            | ProBook 645 G2              | [6042ac6425](https://linux-hardware.org/?probe=6042ac6425) | Dec 23, 2024 |
| ASUSTek       | X541UAK                     | [3b5b163084](https://linux-hardware.org/?probe=3b5b163084) | Dec 14, 2024 |
| ASUSTek       | X541UAK                     | [b0c9088b05](https://linux-hardware.org/?probe=b0c9088b05) | Dec 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [183432796c](https://linux-hardware.org/?probe=183432796c) | Dec 08, 2024 |
| ASUSTek       | X441NA                      | [a093d05841](https://linux-hardware.org/?probe=a093d05841) | Dec 08, 2024 |
| Acer          | Swift SF113-31              | [2e080ea3c1](https://linux-hardware.org/?probe=2e080ea3c1) | Dec 06, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8a76df0398](https://linux-hardware.org/?probe=8a76df0398) | Dec 04, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [59d4f74fbf](https://linux-hardware.org/?probe=59d4f74fbf) | Dec 03, 2024 |
| ASUSTek       | X541UAK                     | [f1806e93b3](https://linux-hardware.org/?probe=f1806e93b3) | Nov 30, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [49f7b2645e](https://linux-hardware.org/?probe=49f7b2645e) | Nov 28, 2024 |
| HP            | Laptop 15-db0xxx            | [f8201ecab7](https://linux-hardware.org/?probe=f8201ecab7) | Nov 24, 2024 |
| HP            | Notebook                    | [a9643205fd](https://linux-hardware.org/?probe=a9643205fd) | Nov 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [32b8993767](https://linux-hardware.org/?probe=32b8993767) | Nov 15, 2024 |
| Dell          | Latitude E5550              | [3ba03e0a00](https://linux-hardware.org/?probe=3ba03e0a00) | Nov 14, 2024 |
| Acer          | Aspire A515-52G             | [9493eace9d](https://linux-hardware.org/?probe=9493eace9d) | Nov 11, 2024 |
| Toshiba       | Satellite L305              | [5cf5602102](https://linux-hardware.org/?probe=5cf5602102) | Nov 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4c355fc31c](https://linux-hardware.org/?probe=4c355fc31c) | Nov 02, 2024 |
| ASUSTek       | X541UVK                     | [1bec944a0f](https://linux-hardware.org/?probe=1bec944a0f) | Oct 29, 2024 |
| ASUSTek       | X541UVK                     | [308efea806](https://linux-hardware.org/?probe=308efea806) | Oct 29, 2024 |
| Unknown       | 10-WLAN-1                   | [3a578a0d19](https://linux-hardware.org/?probe=3a578a0d19) | Oct 24, 2024 |
| HP            | EliteBook 830 G5            | [bab49b9805](https://linux-hardware.org/?probe=bab49b9805) | Oct 14, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [ce6934ccc8](https://linux-hardware.org/?probe=ce6934ccc8) | Oct 11, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [56346796f8](https://linux-hardware.org/?probe=56346796f8) | Oct 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f53a768cc3](https://linux-hardware.org/?probe=f53a768cc3) | Oct 09, 2024 |
| ASUSTek       | X541UVK                     | [b5ad97117b](https://linux-hardware.org/?probe=b5ad97117b) | Oct 07, 2024 |
| Acer          | Aspire 5520                 | [b16f7a6aba](https://linux-hardware.org/?probe=b16f7a6aba) | Oct 06, 2024 |
| HP            | 250 G5 Notebook PC          | [7eb76fb226](https://linux-hardware.org/?probe=7eb76fb226) | Oct 05, 2024 |
| ASUSTek       | X541UAK                     | [c8b9cbde59](https://linux-hardware.org/?probe=c8b9cbde59) | Sep 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c504205882](https://linux-hardware.org/?probe=c504205882) | Sep 21, 2024 |
| Dell          | Inspiron 3558               | [5bf9d94642](https://linux-hardware.org/?probe=5bf9d94642) | Sep 19, 2024 |
| Acer          | Aspire A315-34              | [a199f003d9](https://linux-hardware.org/?probe=a199f003d9) | Sep 15, 2024 |
| Dell          | Precision M6500             | [f33e0f389f](https://linux-hardware.org/?probe=f33e0f389f) | Sep 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [27d62581b6](https://linux-hardware.org/?probe=27d62581b6) | Sep 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [264b39ca1e](https://linux-hardware.org/?probe=264b39ca1e) | Sep 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f46290e3ed](https://linux-hardware.org/?probe=f46290e3ed) | Aug 28, 2024 |
| Acer          | Aspire E5-551G              | [c28309e2cf](https://linux-hardware.org/?probe=c28309e2cf) | Aug 27, 2024 |
| HP            | Pavilion Notebook           | [d1075026d7](https://linux-hardware.org/?probe=d1075026d7) | Aug 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f922356011](https://linux-hardware.org/?probe=f922356011) | Aug 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c3bc0d70a0](https://linux-hardware.org/?probe=c3bc0d70a0) | Aug 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [2942fe4c28](https://linux-hardware.org/?probe=2942fe4c28) | Aug 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [00ff3f6969](https://linux-hardware.org/?probe=00ff3f6969) | Aug 13, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9cd2d183ac](https://linux-hardware.org/?probe=9cd2d183ac) | Aug 11, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0cd104e585](https://linux-hardware.org/?probe=0cd104e585) | Aug 09, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2e6a748862](https://linux-hardware.org/?probe=2e6a748862) | Aug 08, 2024 |
| ASUSTek       | ZenBook UX431DA_UX431DA     | [118fd7e8da](https://linux-hardware.org/?probe=118fd7e8da) | Jul 31, 2024 |
| Acer          | Aspire A315-53              | [c63f2333ce](https://linux-hardware.org/?probe=c63f2333ce) | Jul 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [5c1d1b5170](https://linux-hardware.org/?probe=5c1d1b5170) | Jul 29, 2024 |
| HP            | Notebook                    | [566987604c](https://linux-hardware.org/?probe=566987604c) | Jul 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1b26a5bcd4](https://linux-hardware.org/?probe=1b26a5bcd4) | Jul 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [ba66d077e7](https://linux-hardware.org/?probe=ba66d077e7) | Jul 26, 2024 |
| Acer          | Nitro AN515-44              | [9e1fa0814a](https://linux-hardware.org/?probe=9e1fa0814a) | Jul 22, 2024 |
| Dell          | Inspiron 3521               | [f95de50c5b](https://linux-hardware.org/?probe=f95de50c5b) | Jul 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b450d3ac07](https://linux-hardware.org/?probe=b450d3ac07) | Jul 19, 2024 |
| Dell          | Latitude E4300              | [8a938d1b3a](https://linux-hardware.org/?probe=8a938d1b3a) | Jul 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [20cf6445c3](https://linux-hardware.org/?probe=20cf6445c3) | Jul 17, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [40f76af578](https://linux-hardware.org/?probe=40f76af578) | Jul 13, 2024 |
| HP            | Pavilion dm4                | [9dedf9e182](https://linux-hardware.org/?probe=9dedf9e182) | Jun 27, 2024 |
| HP            | Pavilion dm4                | [1cf90c63d0](https://linux-hardware.org/?probe=1cf90c63d0) | Jun 27, 2024 |
| Google        | Volet                       | [d6110ef2f0](https://linux-hardware.org/?probe=d6110ef2f0) | Jun 22, 2024 |
| Google        | Volet                       | [532f047a12](https://linux-hardware.org/?probe=532f047a12) | Jun 22, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f0905083d1](https://linux-hardware.org/?probe=f0905083d1) | Jun 22, 2024 |
| HP            | Pavilion 15                 | [7db8fc91af](https://linux-hardware.org/?probe=7db8fc91af) | Jun 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c4c7ed4510](https://linux-hardware.org/?probe=c4c7ed4510) | Jun 21, 2024 |
| ASUSTek       | X555LB                      | [9c9451d483](https://linux-hardware.org/?probe=9c9451d483) | Jun 04, 2024 |
| ASUSTek       | X555LB                      | [5212c48bcc](https://linux-hardware.org/?probe=5212c48bcc) | Jun 04, 2024 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [d615511255](https://linux-hardware.org/?probe=d615511255) | Jun 03, 2024 |
| ASUSTek       | X541UAK                     | [1acb106c74](https://linux-hardware.org/?probe=1acb106c74) | Jun 02, 2024 |
| HP            | 250 G5 Notebook PC          | [c1d79d8650](https://linux-hardware.org/?probe=c1d79d8650) | May 31, 2024 |
| Acer          | Swift SF713-51              | [b0f444cfe8](https://linux-hardware.org/?probe=b0f444cfe8) | May 25, 2024 |
| Positivo      | H14BT58                     | [29a953f416](https://linux-hardware.org/?probe=29a953f416) | May 23, 2024 |
| Acer          | Aspire A315-33              | [e8d32de86b](https://linux-hardware.org/?probe=e8d32de86b) | May 23, 2024 |
| Positivo      | H14BT58                     | [10028d0bfb](https://linux-hardware.org/?probe=10028d0bfb) | May 22, 2024 |
| Acer          | Aspire A315-33              | [e8369b1866](https://linux-hardware.org/?probe=e8369b1866) | May 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [deea96eb1c](https://linux-hardware.org/?probe=deea96eb1c) | May 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3b2d3440fb](https://linux-hardware.org/?probe=3b2d3440fb) | May 18, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [35fbf44c91](https://linux-hardware.org/?probe=35fbf44c91) | May 11, 2024 |
| Acer          | Aspire A315-33              | [5f7edad747](https://linux-hardware.org/?probe=5f7edad747) | Apr 25, 2024 |
| Acer          | Aspire A315-33              | [8f762b36cd](https://linux-hardware.org/?probe=8f762b36cd) | Apr 25, 2024 |
| Acer          | Aspire 5720                 | [015bf8aebc](https://linux-hardware.org/?probe=015bf8aebc) | Apr 13, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5b6ccc400c](https://linux-hardware.org/?probe=5b6ccc400c) | Apr 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8cc539a26d](https://linux-hardware.org/?probe=8cc539a26d) | Apr 05, 2024 |
| Lenovo        | ThinkPad Twist 33474HU      | [3cab864002](https://linux-hardware.org/?probe=3cab864002) | Apr 04, 2024 |
| Lenovo        | Flex 2-15 20405             | [d3439cdb4e](https://linux-hardware.org/?probe=d3439cdb4e) | Mar 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4f333791ed](https://linux-hardware.org/?probe=4f333791ed) | Mar 23, 2024 |
| ASUSTek       | X541NA                      | [032929e502](https://linux-hardware.org/?probe=032929e502) | Mar 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [90adc9f40e](https://linux-hardware.org/?probe=90adc9f40e) | Mar 20, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [2e420dae7e](https://linux-hardware.org/?probe=2e420dae7e) | Mar 09, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [321f40d2d0](https://linux-hardware.org/?probe=321f40d2d0) | Mar 08, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [84de25fe23](https://linux-hardware.org/?probe=84de25fe23) | Mar 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5af612903d](https://linux-hardware.org/?probe=5af612903d) | Mar 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bebd4ae82b](https://linux-hardware.org/?probe=bebd4ae82b) | Mar 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [907e9cecbc](https://linux-hardware.org/?probe=907e9cecbc) | Feb 29, 2024 |
| HP            | 250 G5 Notebook PC          | [6ed95e8c32](https://linux-hardware.org/?probe=6ed95e8c32) | Feb 26, 2024 |
| ASUSTek       | ZenBook UX431FA_UX431FA     | [0f8823b5f0](https://linux-hardware.org/?probe=0f8823b5f0) | Feb 22, 2024 |
| Acer          | Nitro AN515-44              | [f0d7ba3ff2](https://linux-hardware.org/?probe=f0d7ba3ff2) | Feb 21, 2024 |
| Acer          | Aspire A315-56              | [a7f440e11c](https://linux-hardware.org/?probe=a7f440e11c) | Feb 20, 2024 |
| Acer          | Aspire A315-56              | [57497aae34](https://linux-hardware.org/?probe=57497aae34) | Feb 20, 2024 |
| HP            | 255 G4                      | [0a2efa88c9](https://linux-hardware.org/?probe=0a2efa88c9) | Feb 17, 2024 |
| Acer          | Aspire A515-54              | [1727f6552e](https://linux-hardware.org/?probe=1727f6552e) | Feb 13, 2024 |
| Toshiba       | Satellite C855              | [a4d195a4f4](https://linux-hardware.org/?probe=a4d195a4f4) | Feb 13, 2024 |
| Lenovo        | ThinkPad X250 20CLS78300    | [a930329831](https://linux-hardware.org/?probe=a930329831) | Feb 10, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [d535f3f49d](https://linux-hardware.org/?probe=d535f3f49d) | Feb 06, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [67cec052d1](https://linux-hardware.org/?probe=67cec052d1) | Feb 06, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [40fbd1acd6](https://linux-hardware.org/?probe=40fbd1acd6) | Feb 06, 2024 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [51c4f07d2f](https://linux-hardware.org/?probe=51c4f07d2f) | Feb 04, 2024 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [ba4fdf1b5b](https://linux-hardware.org/?probe=ba4fdf1b5b) | Feb 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e5bbf9598f](https://linux-hardware.org/?probe=e5bbf9598f) | Feb 01, 2024 |
| Infinix       | INBOOK X1 NEO               | [aca7de6cf8](https://linux-hardware.org/?probe=aca7de6cf8) | Jan 31, 2024 |
| Acer          | Nitro AN515-44              | [05ec6529d7](https://linux-hardware.org/?probe=05ec6529d7) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7dd8607755](https://linux-hardware.org/?probe=7dd8607755) | Jan 26, 2024 |
| Acer          | Aspire A315-35              | [40bb0f1f4d](https://linux-hardware.org/?probe=40bb0f1f4d) | Jan 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2e2349c377](https://linux-hardware.org/?probe=2e2349c377) | Jan 24, 2024 |
| Acer          | Aspire A315-54              | [83570af6ad](https://linux-hardware.org/?probe=83570af6ad) | Jan 23, 2024 |
| Samsung       | RV415/RV515                 | [5002fd9959](https://linux-hardware.org/?probe=5002fd9959) | Jan 19, 2024 |
| Samsung       | RV415/RV515                 | [282ae0ae50](https://linux-hardware.org/?probe=282ae0ae50) | Jan 18, 2024 |
| ASUSTek       | X541UJ                      | [106a1e0cd4](https://linux-hardware.org/?probe=106a1e0cd4) | Jan 17, 2024 |
| ASUSTek       | X540NA                      | [1f6d0e42df](https://linux-hardware.org/?probe=1f6d0e42df) | Jan 10, 2024 |
| HP            | 255 G4                      | [ad9ff6e782](https://linux-hardware.org/?probe=ad9ff6e782) | Jan 04, 2024 |
| HP            | 255 G4                      | [8afdfb35cc](https://linux-hardware.org/?probe=8afdfb35cc) | Jan 04, 2024 |
| Acer          | Nitro AN515-44              | [9ac5286530](https://linux-hardware.org/?probe=9ac5286530) | Jan 02, 2024 |
| Dell          | Latitude 5511               | [3b186725e3](https://linux-hardware.org/?probe=3b186725e3) | Jan 01, 2024 |
| Acer          | Aspire A315-54K             | [d0fa49f90a](https://linux-hardware.org/?probe=d0fa49f90a) | Jan 01, 2024 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [156c23e1d0](https://linux-hardware.org/?probe=156c23e1d0) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [09d63b8472](https://linux-hardware.org/?probe=09d63b8472) | Dec 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [971e3fe3eb](https://linux-hardware.org/?probe=971e3fe3eb) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7d873eb94f](https://linux-hardware.org/?probe=7d873eb94f) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [850fedd929](https://linux-hardware.org/?probe=850fedd929) | Dec 25, 2023 |
| Acer          | Nitro AN515-57              | [1bd5e5e36f](https://linux-hardware.org/?probe=1bd5e5e36f) | Dec 18, 2023 |
| ASUSTek       | X541UJ                      | [4aeb75b734](https://linux-hardware.org/?probe=4aeb75b734) | Dec 17, 2023 |
| ASUSTek       | X705UAR                     | [0ab56df890](https://linux-hardware.org/?probe=0ab56df890) | Dec 15, 2023 |
| ASUSTek       | X705UAR                     | [9f0e2069b1](https://linux-hardware.org/?probe=9f0e2069b1) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c839de638b](https://linux-hardware.org/?probe=c839de638b) | Dec 15, 2023 |
| Acer          | Aspire A315-35              | [f7b0d4b746](https://linux-hardware.org/?probe=f7b0d4b746) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9f878d8d30](https://linux-hardware.org/?probe=9f878d8d30) | Dec 08, 2023 |
| Dell          | Vostro 1520                 | [ac1c78d3a4](https://linux-hardware.org/?probe=ac1c78d3a4) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [88ed0c98a0](https://linux-hardware.org/?probe=88ed0c98a0) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [199f9814a0](https://linux-hardware.org/?probe=199f9814a0) | Nov 24, 2023 |
| HP            | 430                         | [a5ad87647a](https://linux-hardware.org/?probe=a5ad87647a) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0a82a8edc6](https://linux-hardware.org/?probe=0a82a8edc6) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f30de31399](https://linux-hardware.org/?probe=f30de31399) | Nov 22, 2023 |
| Positivo      | S14CT01                     | [dab6f65392](https://linux-hardware.org/?probe=dab6f65392) | Nov 22, 2023 |
| Positivo      | S14CT01                     | [b92cdc7457](https://linux-hardware.org/?probe=b92cdc7457) | Nov 22, 2023 |
| HP            | 430                         | [65a26f2a32](https://linux-hardware.org/?probe=65a26f2a32) | Nov 21, 2023 |
| Acer          | Nitro AN517-54              | [b93c6fb412](https://linux-hardware.org/?probe=b93c6fb412) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e26c4bc5ff](https://linux-hardware.org/?probe=e26c4bc5ff) | Nov 19, 2023 |
| Acer          | Nitro AN515-52              | [a9b37fa8a9](https://linux-hardware.org/?probe=a9b37fa8a9) | Nov 19, 2023 |
| Acer          | Nitro AN515-52              | [0e1fa61401](https://linux-hardware.org/?probe=0e1fa61401) | Nov 19, 2023 |
| Acer          | Nitro AN515-54              | [0ab66fd189](https://linux-hardware.org/?probe=0ab66fd189) | Nov 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1fa32b3cb7](https://linux-hardware.org/?probe=1fa32b3cb7) | Nov 15, 2023 |
| ADVAN         | 1405                        | [55a639a506](https://linux-hardware.org/?probe=55a639a506) | Nov 14, 2023 |
| Acer          | Nitro AN517-54              | [37423cedf9](https://linux-hardware.org/?probe=37423cedf9) | Nov 13, 2023 |
| Unknown       | Unknown                     | [be77c5477d](https://linux-hardware.org/?probe=be77c5477d) | Nov 12, 2023 |
| Unknown       | Unknown                     | [d93ab747bb](https://linux-hardware.org/?probe=d93ab747bb) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [193098a1ea](https://linux-hardware.org/?probe=193098a1ea) | Nov 08, 2023 |
| Fujitsu       | LIFEBOOK AH544              | [31fbaa3897](https://linux-hardware.org/?probe=31fbaa3897) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [931f0ed896](https://linux-hardware.org/?probe=931f0ed896) | Oct 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d443352482](https://linux-hardware.org/?probe=d443352482) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c9e8482167](https://linux-hardware.org/?probe=c9e8482167) | Oct 26, 2023 |
| Acer          | Nitro AN515-54              | [877ec2dd85](https://linux-hardware.org/?probe=877ec2dd85) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [33a143a23d](https://linux-hardware.org/?probe=33a143a23d) | Oct 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [20b1614237](https://linux-hardware.org/?probe=20b1614237) | Oct 12, 2023 |
| HP            | Unknown                     | [c64a37f28f](https://linux-hardware.org/?probe=c64a37f28f) | Oct 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [508c438c6a](https://linux-hardware.org/?probe=508c438c6a) | Oct 09, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3cfe6c7d0c](https://linux-hardware.org/?probe=3cfe6c7d0c) | Oct 08, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [60d5b8f4c0](https://linux-hardware.org/?probe=60d5b8f4c0) | Oct 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [99f8282319](https://linux-hardware.org/?probe=99f8282319) | Oct 06, 2023 |
| Acer          | Aspire 5720                 | [6009fced37](https://linux-hardware.org/?probe=6009fced37) | Oct 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a0e4942d9f](https://linux-hardware.org/?probe=a0e4942d9f) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [772e866a05](https://linux-hardware.org/?probe=772e866a05) | Sep 29, 2023 |
| ASUSTek       | X441NA                      | [e44f45e8d6](https://linux-hardware.org/?probe=e44f45e8d6) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d71e760b5c](https://linux-hardware.org/?probe=d71e760b5c) | Sep 24, 2023 |
| Endless       | EF20EA                      | [492a9e4f5e](https://linux-hardware.org/?probe=492a9e4f5e) | Sep 23, 2023 |
| Acer          | Aspire A517-51              | [fdeb61b7c3](https://linux-hardware.org/?probe=fdeb61b7c3) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0b036a6058](https://linux-hardware.org/?probe=0b036a6058) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [47e95a92cc](https://linux-hardware.org/?probe=47e95a92cc) | Sep 17, 2023 |
| Acer          | Aspire 5720                 | [9bfcaaa71a](https://linux-hardware.org/?probe=9bfcaaa71a) | Sep 16, 2023 |
| Acer          | Aspire 5720                 | [bad46323d7](https://linux-hardware.org/?probe=bad46323d7) | Sep 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9915642af4](https://linux-hardware.org/?probe=9915642af4) | Sep 16, 2023 |
| Acer          | Aspire A315-35              | [356d6d3e13](https://linux-hardware.org/?probe=356d6d3e13) | Sep 15, 2023 |
| Acer          | Aspire A315-35              | [7ae470ffa8](https://linux-hardware.org/?probe=7ae470ffa8) | Sep 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [27b430aa3f](https://linux-hardware.org/?probe=27b430aa3f) | Sep 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ee89a78be0](https://linux-hardware.org/?probe=ee89a78be0) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [29f1d7759a](https://linux-hardware.org/?probe=29f1d7759a) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [344a00d524](https://linux-hardware.org/?probe=344a00d524) | Sep 06, 2023 |
| Acer          | Predator G3-571             | [972f320a9d](https://linux-hardware.org/?probe=972f320a9d) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [aeebc4664f](https://linux-hardware.org/?probe=aeebc4664f) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [76b9023610](https://linux-hardware.org/?probe=76b9023610) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f5f8737b58](https://linux-hardware.org/?probe=f5f8737b58) | Sep 02, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [5e95785b8e](https://linux-hardware.org/?probe=5e95785b8e) | Sep 01, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4bc3ed94ce](https://linux-hardware.org/?probe=4bc3ed94ce) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [30006f030a](https://linux-hardware.org/?probe=30006f030a) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [73855ebfdf](https://linux-hardware.org/?probe=73855ebfdf) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6fe5efa24c](https://linux-hardware.org/?probe=6fe5efa24c) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [878476c63f](https://linux-hardware.org/?probe=878476c63f) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f2d55c9619](https://linux-hardware.org/?probe=f2d55c9619) | Aug 22, 2023 |
| Lenovo        | B590 20206                  | [d3b3052832](https://linux-hardware.org/?probe=d3b3052832) | Aug 22, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b3f1d927a1](https://linux-hardware.org/?probe=b3f1d927a1) | Aug 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d7b6d2a997](https://linux-hardware.org/?probe=d7b6d2a997) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b86411b8b0](https://linux-hardware.org/?probe=b86411b8b0) | Aug 21, 2023 |
| Samsung       | 550XBE/350XBE               | [1d08f612ba](https://linux-hardware.org/?probe=1d08f612ba) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f44bc6c057](https://linux-hardware.org/?probe=f44bc6c057) | Aug 19, 2023 |
| Toshiba       | Satellite L550              | [4c331017e2](https://linux-hardware.org/?probe=4c331017e2) | Aug 18, 2023 |
| Lenovo        | S10-3                       | [d1c8fb66ec](https://linux-hardware.org/?probe=d1c8fb66ec) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [35b8929f7f](https://linux-hardware.org/?probe=35b8929f7f) | Aug 17, 2023 |
| Acer          | Nitro AN515-52              | [30748e95eb](https://linux-hardware.org/?probe=30748e95eb) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [dd127ca2df](https://linux-hardware.org/?probe=dd127ca2df) | Aug 08, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [ae5361d56f](https://linux-hardware.org/?probe=ae5361d56f) | Aug 05, 2023 |
| Acer          | Aspire VN7-793G             | [c7e996a3c2](https://linux-hardware.org/?probe=c7e996a3c2) | Aug 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ee147b0313](https://linux-hardware.org/?probe=ee147b0313) | Aug 03, 2023 |
| HP            | ProBook 445 G7              | [96e95e4bd2](https://linux-hardware.org/?probe=96e95e4bd2) | Jul 31, 2023 |
| Acer          | Nitro AN515-52              | [393c4b7fd3](https://linux-hardware.org/?probe=393c4b7fd3) | Jul 29, 2023 |
| HP            | 250 G5 Notebook PC          | [572537c287](https://linux-hardware.org/?probe=572537c287) | Jul 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [501969ed00](https://linux-hardware.org/?probe=501969ed00) | Jul 15, 2023 |
| Dell          | XPS 13 9380                 | [ad75f0a6e0](https://linux-hardware.org/?probe=ad75f0a6e0) | Jul 12, 2023 |
| Acer          | Aspire A515-54              | [64e1f03cea](https://linux-hardware.org/?probe=64e1f03cea) | Jul 12, 2023 |
| Acer          | Aspire A315-53              | [488366cee5](https://linux-hardware.org/?probe=488366cee5) | Jul 08, 2023 |
| Acer          | Nitro AN515-44              | [d695952680](https://linux-hardware.org/?probe=d695952680) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7991ee84b](https://linux-hardware.org/?probe=f7991ee84b) | Jul 06, 2023 |
| Acer          | Nitro AN517-54              | [2943ff2787](https://linux-hardware.org/?probe=2943ff2787) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [708fb65c2c](https://linux-hardware.org/?probe=708fb65c2c) | Jul 05, 2023 |
| Acer          | Aspire ES1-411              | [898ea84872](https://linux-hardware.org/?probe=898ea84872) | Jul 04, 2023 |
| Toshiba       | Satellite L550              | [321ec36f85](https://linux-hardware.org/?probe=321ec36f85) | Jun 25, 2023 |
| Acer          | Aspire A517-51              | [7f4ad14efb](https://linux-hardware.org/?probe=7f4ad14efb) | Jun 25, 2023 |
| Acer          | Aspire A517-51G             | [dc2aebbc48](https://linux-hardware.org/?probe=dc2aebbc48) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | [a8a9689ea6](https://linux-hardware.org/?probe=a8a9689ea6) | Jun 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [84239b2594](https://linux-hardware.org/?probe=84239b2594) | Jun 23, 2023 |
| Acer          | Nitro AN515-44              | [d43ff293c1](https://linux-hardware.org/?probe=d43ff293c1) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [817361caf5](https://linux-hardware.org/?probe=817361caf5) | Jun 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c0dc86bdc1](https://linux-hardware.org/?probe=c0dc86bdc1) | Jun 19, 2023 |
| Lenovo        | G550 20023                  | [a1eac5da7c](https://linux-hardware.org/?probe=a1eac5da7c) | Jun 18, 2023 |
| HP            | ProBook 445 G7              | [71c3b52599](https://linux-hardware.org/?probe=71c3b52599) | Jun 17, 2023 |
| ASUSTek       | GL552VW                     | [f3b0b03ace](https://linux-hardware.org/?probe=f3b0b03ace) | Jun 12, 2023 |
| Acer          | Aspire A517-51              | [01cfb1c93f](https://linux-hardware.org/?probe=01cfb1c93f) | Jun 10, 2023 |
| Acer          | Nitro AN515-44              | [b3531502a8](https://linux-hardware.org/?probe=b3531502a8) | Jun 10, 2023 |
| Dell          | Vostro 1310                 | [05fc6f167c](https://linux-hardware.org/?probe=05fc6f167c) | Jun 09, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [5c63c42a5c](https://linux-hardware.org/?probe=5c63c42a5c) | Jun 04, 2023 |
| Acer          | Aspire A517-51G             | [dc0e29f0bb](https://linux-hardware.org/?probe=dc0e29f0bb) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | [693005f5b4](https://linux-hardware.org/?probe=693005f5b4) | Jun 02, 2023 |
| Acer          | AO756                       | [e135dbe37e](https://linux-hardware.org/?probe=e135dbe37e) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [86666c3371](https://linux-hardware.org/?probe=86666c3371) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8fb981666f](https://linux-hardware.org/?probe=8fb981666f) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [84717aefdf](https://linux-hardware.org/?probe=84717aefdf) | May 22, 2023 |
| HP            | 2000                        | [f0abebdc1e](https://linux-hardware.org/?probe=f0abebdc1e) | May 18, 2023 |
| Sony          | VPCF11M1E                   | [b42c56ac73](https://linux-hardware.org/?probe=b42c56ac73) | May 14, 2023 |
| Lenovo        | G550 20023                  | [33cc483e77](https://linux-hardware.org/?probe=33cc483e77) | May 09, 2023 |
| MSI           | GE75 Raider 10SF            | [e10ccc96bd](https://linux-hardware.org/?probe=e10ccc96bd) | May 07, 2023 |
| MSI           | GE75 Raider 10SF            | [edcaaeed46](https://linux-hardware.org/?probe=edcaaeed46) | May 07, 2023 |
| HP            | Pavilion g6                 | [26830f860f](https://linux-hardware.org/?probe=26830f860f) | May 06, 2023 |
| HP            | Pavilion g6                 | [a78e3941f5](https://linux-hardware.org/?probe=a78e3941f5) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f2c390eb7e](https://linux-hardware.org/?probe=f2c390eb7e) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7046c6c99](https://linux-hardware.org/?probe=f7046c6c99) | May 05, 2023 |
| Acer          | Aspire E1-421               | [45bca26278](https://linux-hardware.org/?probe=45bca26278) | May 05, 2023 |
| HP            | 255 G8 Notebook PC          | [b1429990db](https://linux-hardware.org/?probe=b1429990db) | May 01, 2023 |
| HP            | 255 G8 Notebook PC          | [6d1a7c83c5](https://linux-hardware.org/?probe=6d1a7c83c5) | May 01, 2023 |
| Acer          | Aspire A515-51G             | [388b693b6d](https://linux-hardware.org/?probe=388b693b6d) | May 01, 2023 |
| Sony          | VPCF11M1E                   | [16772fe220](https://linux-hardware.org/?probe=16772fe220) | Apr 29, 2023 |
| Acer          | Nitro AN515-44              | [12ca37afd3](https://linux-hardware.org/?probe=12ca37afd3) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cd6431fbf5](https://linux-hardware.org/?probe=cd6431fbf5) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8a7681ab18](https://linux-hardware.org/?probe=8a7681ab18) | Apr 03, 2023 |
| Acer          | Aspire A515-51G             | [efc8399ce9](https://linux-hardware.org/?probe=efc8399ce9) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7597a96654](https://linux-hardware.org/?probe=7597a96654) | Mar 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2df4a612b4](https://linux-hardware.org/?probe=2df4a612b4) | Mar 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [27ff485a92](https://linux-hardware.org/?probe=27ff485a92) | Mar 25, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [117d507724](https://linux-hardware.org/?probe=117d507724) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a9ffd21a7f](https://linux-hardware.org/?probe=a9ffd21a7f) | Mar 24, 2023 |
| Gigabyte      | G5 KD                       | [32afc6a4cf](https://linux-hardware.org/?probe=32afc6a4cf) | Mar 23, 2023 |
| HP            | EliteBook 840 G3            | [35e1ff95a5](https://linux-hardware.org/?probe=35e1ff95a5) | Mar 23, 2023 |
| HP            | EliteBook 840 G3            | [1a75f9d839](https://linux-hardware.org/?probe=1a75f9d839) | Mar 23, 2023 |
| Acer          | Nitro AN515-44              | [fca39bd9eb](https://linux-hardware.org/?probe=fca39bd9eb) | Mar 22, 2023 |
| Acer          | Nitro AN515-44              | [e07e3320b1](https://linux-hardware.org/?probe=e07e3320b1) | Mar 22, 2023 |
| HP            | Pavilion 17                 | [cb6b6bc8d2](https://linux-hardware.org/?probe=cb6b6bc8d2) | Mar 22, 2023 |
| Lenovo        | S20-30 20421                | [3c1dd3564d](https://linux-hardware.org/?probe=3c1dd3564d) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1292539ef0](https://linux-hardware.org/?probe=1292539ef0) | Mar 19, 2023 |
| Lenovo        | G550 20023                  | [6296457407](https://linux-hardware.org/?probe=6296457407) | Mar 18, 2023 |
| Lenovo        | G550 20023                  | [f5bd764775](https://linux-hardware.org/?probe=f5bd764775) | Mar 18, 2023 |
| Acer          | Nitro AN515-44              | [dd12b2101e](https://linux-hardware.org/?probe=dd12b2101e) | Mar 17, 2023 |
| Lenovo        | G550 20023                  | [c356d98a54](https://linux-hardware.org/?probe=c356d98a54) | Mar 17, 2023 |
| Acer          | Aspire A315-34              | [63676e7012](https://linux-hardware.org/?probe=63676e7012) | Mar 16, 2023 |
| Acer          | Aspire A515-51              | [6e1d22df26](https://linux-hardware.org/?probe=6e1d22df26) | Mar 15, 2023 |
| Acer          | Aspire A315-34              | [bbb4128793](https://linux-hardware.org/?probe=bbb4128793) | Mar 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [1169593829](https://linux-hardware.org/?probe=1169593829) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [76e4cc71f5](https://linux-hardware.org/?probe=76e4cc71f5) | Mar 12, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [8e12f88524](https://linux-hardware.org/?probe=8e12f88524) | Mar 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [06814e6afa](https://linux-hardware.org/?probe=06814e6afa) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [15dd4409fc](https://linux-hardware.org/?probe=15dd4409fc) | Mar 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [3f007adfc7](https://linux-hardware.org/?probe=3f007adfc7) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6ae7081970](https://linux-hardware.org/?probe=6ae7081970) | Mar 10, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e7429f9be3](https://linux-hardware.org/?probe=e7429f9be3) | Mar 09, 2023 |
| ASUSTek       | X541SA                      | [4adcb5ab0f](https://linux-hardware.org/?probe=4adcb5ab0f) | Mar 08, 2023 |
| VTEX          | NOTEBOOK                    | [0b91c54846](https://linux-hardware.org/?probe=0b91c54846) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | [4687219ca3](https://linux-hardware.org/?probe=4687219ca3) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | [687328ccb0](https://linux-hardware.org/?probe=687328ccb0) | Mar 06, 2023 |
| VTEX          | NOTEBOOK                    | [b12a53ec1e](https://linux-hardware.org/?probe=b12a53ec1e) | Mar 06, 2023 |
| HP            | EliteBook 2560p             | [e7040c89e1](https://linux-hardware.org/?probe=e7040c89e1) | Mar 06, 2023 |
| Dell          | Inspiron 5523               | [495dfc19dc](https://linux-hardware.org/?probe=495dfc19dc) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2e4f2069e8](https://linux-hardware.org/?probe=2e4f2069e8) | Mar 06, 2023 |
| Acer          | Aspire A515-54              | [a544ef69d8](https://linux-hardware.org/?probe=a544ef69d8) | Mar 05, 2023 |
| Acer          | Aspire A515-54              | [6c190c594b](https://linux-hardware.org/?probe=6c190c594b) | Mar 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [4cb7f38354](https://linux-hardware.org/?probe=4cb7f38354) | Mar 05, 2023 |
| Acer          | Nitro AN515-54              | [463de722cd](https://linux-hardware.org/?probe=463de722cd) | Mar 04, 2023 |
| Acer          | Aspire A315-53              | [d16e7dcded](https://linux-hardware.org/?probe=d16e7dcded) | Mar 03, 2023 |
| Dell          | Inspiron 5523               | [09ccf58a6b](https://linux-hardware.org/?probe=09ccf58a6b) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [86fac430ca](https://linux-hardware.org/?probe=86fac430ca) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5c3d39f884](https://linux-hardware.org/?probe=5c3d39f884) | Feb 25, 2023 |
| Dell          | Latitude E6440              | [003611b4c7](https://linux-hardware.org/?probe=003611b4c7) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6dd01c6a20](https://linux-hardware.org/?probe=6dd01c6a20) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1b5b668cea](https://linux-hardware.org/?probe=1b5b668cea) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [39f48414bc](https://linux-hardware.org/?probe=39f48414bc) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fe9944c457](https://linux-hardware.org/?probe=fe9944c457) | Feb 23, 2023 |
| Dell          | Vostro 3446                 | [c6df0f1b65](https://linux-hardware.org/?probe=c6df0f1b65) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c99d1595ec](https://linux-hardware.org/?probe=c99d1595ec) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [caccb434d2](https://linux-hardware.org/?probe=caccb434d2) | Feb 21, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6c02ec2d87](https://linux-hardware.org/?probe=6c02ec2d87) | Feb 19, 2023 |
| HP            | 250 G5 Notebook PC          | [ca676dc566](https://linux-hardware.org/?probe=ca676dc566) | Feb 19, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [2953555c08](https://linux-hardware.org/?probe=2953555c08) | Feb 19, 2023 |
| Acer          | Aspire A315-21              | [fe42379585](https://linux-hardware.org/?probe=fe42379585) | Feb 18, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [f53b1c8aeb](https://linux-hardware.org/?probe=f53b1c8aeb) | Feb 18, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [6d7740ca9d](https://linux-hardware.org/?probe=6d7740ca9d) | Feb 17, 2023 |
| Acer          | Nitro AN515-54              | [4e0f0e0310](https://linux-hardware.org/?probe=4e0f0e0310) | Feb 15, 2023 |
| ASUSTek       | X200MA                      | [b01624da44](https://linux-hardware.org/?probe=b01624da44) | Feb 15, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [d177dc7b4d](https://linux-hardware.org/?probe=d177dc7b4d) | Feb 15, 2023 |
| ASUSTek       | X540NA                      | [706e39729c](https://linux-hardware.org/?probe=706e39729c) | Feb 14, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [76621da580](https://linux-hardware.org/?probe=76621da580) | Feb 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [03f90da8d3](https://linux-hardware.org/?probe=03f90da8d3) | Feb 14, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [a8a5ef19de](https://linux-hardware.org/?probe=a8a5ef19de) | Feb 13, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [608ce76690](https://linux-hardware.org/?probe=608ce76690) | Feb 13, 2023 |
| Acer          | Aspire ES1-572              | [24c1c37b05](https://linux-hardware.org/?probe=24c1c37b05) | Feb 13, 2023 |
| ASUSTek       | X541UAK                     | [e27e733bc0](https://linux-hardware.org/?probe=e27e733bc0) | Feb 12, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | [682be07637](https://linux-hardware.org/?probe=682be07637) | Feb 11, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [f8f0fb1a21](https://linux-hardware.org/?probe=f8f0fb1a21) | Feb 11, 2023 |
| HP            | 250 G5 Notebook PC          | [72b0ba099a](https://linux-hardware.org/?probe=72b0ba099a) | Feb 11, 2023 |
| Toshiba       | Satellite L450              | [5a16ded274](https://linux-hardware.org/?probe=5a16ded274) | Feb 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [87b269febc](https://linux-hardware.org/?probe=87b269febc) | Feb 08, 2023 |
| Acer          | Aspire A517-51              | [ab27353a60](https://linux-hardware.org/?probe=ab27353a60) | Feb 08, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [06ffbacba3](https://linux-hardware.org/?probe=06ffbacba3) | Feb 08, 2023 |
| HP            | Notebook                    | [eb0699bb89](https://linux-hardware.org/?probe=eb0699bb89) | Feb 07, 2023 |
| ASUSTek       | X541UAK                     | [62acbef04d](https://linux-hardware.org/?probe=62acbef04d) | Feb 07, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [6fcc29607c](https://linux-hardware.org/?probe=6fcc29607c) | Feb 06, 2023 |
| Acer          | Aspire E5-476G              | [3b8e69dd3a](https://linux-hardware.org/?probe=3b8e69dd3a) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [cfc187a64c](https://linux-hardware.org/?probe=cfc187a64c) | Feb 05, 2023 |
| Acer          | Aspire A515-51G             | [2b37c84303](https://linux-hardware.org/?probe=2b37c84303) | Feb 04, 2023 |
| Microtech     | CoreBook                    | [2ee0649a6e](https://linux-hardware.org/?probe=2ee0649a6e) | Feb 03, 2023 |
| HP            | Stream Notebook PC 14       | [69628da41b](https://linux-hardware.org/?probe=69628da41b) | Feb 03, 2023 |
| HP            | 250 G5 Notebook PC          | [687b1ec2d7](https://linux-hardware.org/?probe=687b1ec2d7) | Feb 02, 2023 |
| Acer          | Nitro AN515-54              | [9aee0a798c](https://linux-hardware.org/?probe=9aee0a798c) | Feb 01, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [4febaa325b](https://linux-hardware.org/?probe=4febaa325b) | Jan 31, 2023 |
| Acer          | Aspire A517-51              | [cb65ba4ce5](https://linux-hardware.org/?probe=cb65ba4ce5) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f1f5def619](https://linux-hardware.org/?probe=f1f5def619) | Jan 28, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [5a32be51f4](https://linux-hardware.org/?probe=5a32be51f4) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [3b41afb262](https://linux-hardware.org/?probe=3b41afb262) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [5d58c53672](https://linux-hardware.org/?probe=5d58c53672) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [b352f0af44](https://linux-hardware.org/?probe=b352f0af44) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [acf75dbe88](https://linux-hardware.org/?probe=acf75dbe88) | Jan 26, 2023 |
| ASUSTek       | Z550SA                      | [f5ac147c1e](https://linux-hardware.org/?probe=f5ac147c1e) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [364a07a435](https://linux-hardware.org/?probe=364a07a435) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [546a896e7f](https://linux-hardware.org/?probe=546a896e7f) | Jan 22, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [53fb561c53](https://linux-hardware.org/?probe=53fb561c53) | Jan 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ed9d60d9b7](https://linux-hardware.org/?probe=ed9d60d9b7) | Jan 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [183de4d0f6](https://linux-hardware.org/?probe=183de4d0f6) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62aa341472](https://linux-hardware.org/?probe=62aa341472) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [22d07dfddf](https://linux-hardware.org/?probe=22d07dfddf) | Jan 18, 2023 |
| Dell          | XPS 13 9360                 | [7302e1ecb2](https://linux-hardware.org/?probe=7302e1ecb2) | Jan 17, 2023 |
| Lenovo        | G450 2949                   | [f9141ba069](https://linux-hardware.org/?probe=f9141ba069) | Jan 17, 2023 |
| Lenovo        | G450 2949                   | [923765c4aa](https://linux-hardware.org/?probe=923765c4aa) | Jan 17, 2023 |
| Acer          | Aspire A315-21              | [b035fd60cd](https://linux-hardware.org/?probe=b035fd60cd) | Jan 15, 2023 |
| Packard Be... | EasyNote ML65               | [e3599cb723](https://linux-hardware.org/?probe=e3599cb723) | Jan 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [f32463429a](https://linux-hardware.org/?probe=f32463429a) | Jan 14, 2023 |
| Acer          | Nitro AN515-44              | [66d71f6da1](https://linux-hardware.org/?probe=66d71f6da1) | Jan 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a33cdf7213](https://linux-hardware.org/?probe=a33cdf7213) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [83f2f14d5c](https://linux-hardware.org/?probe=83f2f14d5c) | Jan 10, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ef10fbe492](https://linux-hardware.org/?probe=ef10fbe492) | Jan 09, 2023 |
| ASUSTek       | S301LA                      | [9745e5ae33](https://linux-hardware.org/?probe=9745e5ae33) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [313f5897bd](https://linux-hardware.org/?probe=313f5897bd) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [79c60c460a](https://linux-hardware.org/?probe=79c60c460a) | Jan 07, 2023 |
| Acer          | Nitro AN515-44              | [1e24b872bd](https://linux-hardware.org/?probe=1e24b872bd) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | [758acf54ff](https://linux-hardware.org/?probe=758acf54ff) | Jan 06, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6e3d10ba74](https://linux-hardware.org/?probe=6e3d10ba74) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | [caa3df2f1c](https://linux-hardware.org/?probe=caa3df2f1c) | Jan 05, 2023 |
| Acer          | Nitro AN515-44              | [c1375455dc](https://linux-hardware.org/?probe=c1375455dc) | Jan 05, 2023 |
| Acer          | Aspire A315-54              | [22b6517ed2](https://linux-hardware.org/?probe=22b6517ed2) | Jan 05, 2023 |
| Acer          | Nitro AN515-54              | [26165b2acb](https://linux-hardware.org/?probe=26165b2acb) | Jan 04, 2023 |
| Acer          | Nitro AN515-54              | [1fd86a44c5](https://linux-hardware.org/?probe=1fd86a44c5) | Jan 04, 2023 |
| ASUSTek       | X510UNR                     | [5ac1da09ba](https://linux-hardware.org/?probe=5ac1da09ba) | Jan 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [37cbf7c1a4](https://linux-hardware.org/?probe=37cbf7c1a4) | Jan 03, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d44828a455](https://linux-hardware.org/?probe=d44828a455) | Dec 30, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [8db34630c3](https://linux-hardware.org/?probe=8db34630c3) | Dec 29, 2022 |
| HP            | Pavilion 17                 | [03976dea5a](https://linux-hardware.org/?probe=03976dea5a) | Dec 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [942fbb1ccb](https://linux-hardware.org/?probe=942fbb1ccb) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d702a6b606](https://linux-hardware.org/?probe=d702a6b606) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [28b89e2321](https://linux-hardware.org/?probe=28b89e2321) | Dec 24, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [81f7e4d804](https://linux-hardware.org/?probe=81f7e4d804) | Dec 22, 2022 |
| Acer          | Aspire 5735                 | [d2850b2e08](https://linux-hardware.org/?probe=d2850b2e08) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [751834957d](https://linux-hardware.org/?probe=751834957d) | Dec 20, 2022 |
| Acer          | Nitro AN515-54              | [5254697dbb](https://linux-hardware.org/?probe=5254697dbb) | Dec 19, 2022 |
| ASUSTek       | X451CAP                     | [358fa50e0c](https://linux-hardware.org/?probe=358fa50e0c) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7b1655d054](https://linux-hardware.org/?probe=7b1655d054) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [07ae580adc](https://linux-hardware.org/?probe=07ae580adc) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5c0150b6ae](https://linux-hardware.org/?probe=5c0150b6ae) | Dec 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7bcd1aa991](https://linux-hardware.org/?probe=7bcd1aa991) | Dec 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [711364b4dd](https://linux-hardware.org/?probe=711364b4dd) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0da6ba8094](https://linux-hardware.org/?probe=0da6ba8094) | Dec 15, 2022 |
| ASUSTek       | N71Vn                       | [579adf052e](https://linux-hardware.org/?probe=579adf052e) | Dec 15, 2022 |
| Acer          | Nitro AN517-51              | [a621dbb00e](https://linux-hardware.org/?probe=a621dbb00e) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [a1f1288337](https://linux-hardware.org/?probe=a1f1288337) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [726380956e](https://linux-hardware.org/?probe=726380956e) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [d262eae22d](https://linux-hardware.org/?probe=d262eae22d) | Dec 12, 2022 |
| Dell          | Inspiron 3542               | [eb1d437253](https://linux-hardware.org/?probe=eb1d437253) | Dec 10, 2022 |
| Dell          | Latitude E6520              | [ec32b72261](https://linux-hardware.org/?probe=ec32b72261) | Dec 09, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [660fe07867](https://linux-hardware.org/?probe=660fe07867) | Dec 07, 2022 |
| Acer          | Aspire A515-54G             | [0bcc1e2664](https://linux-hardware.org/?probe=0bcc1e2664) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2bde4950e9](https://linux-hardware.org/?probe=2bde4950e9) | Dec 02, 2022 |
| Dell          | Latitude E6530              | [c90145516a](https://linux-hardware.org/?probe=c90145516a) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | [81eca2f60e](https://linux-hardware.org/?probe=81eca2f60e) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | [5841aa11f1](https://linux-hardware.org/?probe=5841aa11f1) | Nov 30, 2022 |
| HP            | Pavilion g6                 | [c552ca011c](https://linux-hardware.org/?probe=c552ca011c) | Nov 30, 2022 |
| Acer          | Aspire 5738                 | [a9697f1e7a](https://linux-hardware.org/?probe=a9697f1e7a) | Nov 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c3e10b2149](https://linux-hardware.org/?probe=c3e10b2149) | Nov 26, 2022 |
| Dell          | Latitude E6530              | [9f1bcb6f10](https://linux-hardware.org/?probe=9f1bcb6f10) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9836f71cb7](https://linux-hardware.org/?probe=9836f71cb7) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9b9a13f34f](https://linux-hardware.org/?probe=9b9a13f34f) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [47116ddd3e](https://linux-hardware.org/?probe=47116ddd3e) | Nov 24, 2022 |
| Medion        | Akoya P2214T                | [eb9e0cfbf8](https://linux-hardware.org/?probe=eb9e0cfbf8) | Nov 20, 2022 |
| ASUSTek       | X541UAK                     | [75af06e026](https://linux-hardware.org/?probe=75af06e026) | Nov 20, 2022 |
| Acer          | Nitro AN515-44              | [c6b85f956a](https://linux-hardware.org/?probe=c6b85f956a) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e777561ba5](https://linux-hardware.org/?probe=e777561ba5) | Nov 19, 2022 |
| HP            | 255 G8 Notebook PC          | [218b12df90](https://linux-hardware.org/?probe=218b12df90) | Nov 19, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [5605c0fd97](https://linux-hardware.org/?probe=5605c0fd97) | Nov 19, 2022 |
| HP            | Laptop 15-dy2xxx            | [a49a9f72c4](https://linux-hardware.org/?probe=a49a9f72c4) | Nov 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61bcea3891](https://linux-hardware.org/?probe=61bcea3891) | Nov 13, 2022 |
| Acer          | Aspire 5720Z                | [264c30fac3](https://linux-hardware.org/?probe=264c30fac3) | Nov 13, 2022 |
| Acer          | Aspire 5720Z                | [6e596d88da](https://linux-hardware.org/?probe=6e596d88da) | Nov 12, 2022 |
| Google        | Volet                       | [ad7d4384bc](https://linux-hardware.org/?probe=ad7d4384bc) | Nov 11, 2022 |
| Acer          | Nitro AN515-44              | [91851e068d](https://linux-hardware.org/?probe=91851e068d) | Nov 06, 2022 |
| Intel         | powered classmate PC        | [5e9392864a](https://linux-hardware.org/?probe=5e9392864a) | Nov 03, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c83f37c114](https://linux-hardware.org/?probe=c83f37c114) | Nov 01, 2022 |
| Dell          | Latitude E6530              | [5f82f9b682](https://linux-hardware.org/?probe=5f82f9b682) | Oct 31, 2022 |
| Acer          | Predator G3-571             | [a5c2027983](https://linux-hardware.org/?probe=a5c2027983) | Oct 28, 2022 |
| Acer          | Nitro AN515-44              | [189ac65e5b](https://linux-hardware.org/?probe=189ac65e5b) | Oct 27, 2022 |
| HP            | G71                         | [3223e2fcc8](https://linux-hardware.org/?probe=3223e2fcc8) | Oct 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7daabab955](https://linux-hardware.org/?probe=7daabab955) | Oct 27, 2022 |
| Lenovo        | G500 20236                  | [b5508a855e](https://linux-hardware.org/?probe=b5508a855e) | Oct 26, 2022 |
| Toshiba       | NB300                       | [c5aa7d3c5f](https://linux-hardware.org/?probe=c5aa7d3c5f) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [7274eca48b](https://linux-hardware.org/?probe=7274eca48b) | Oct 23, 2022 |
| ASUSTek       | X540NA                      | [73799d57b3](https://linux-hardware.org/?probe=73799d57b3) | Oct 22, 2022 |
| ASUSTek       | X540NA                      | [bef64e98af](https://linux-hardware.org/?probe=bef64e98af) | Oct 21, 2022 |
| HP            | G71                         | [46b6033e1e](https://linux-hardware.org/?probe=46b6033e1e) | Oct 17, 2022 |
| Acer          | Aspire 5750                 | [4e90ad293c](https://linux-hardware.org/?probe=4e90ad293c) | Oct 17, 2022 |
| Acer          | Nitro AN515-44              | [7293f219d8](https://linux-hardware.org/?probe=7293f219d8) | Oct 16, 2022 |
| Dell          | Latitude E6530              | [174d5aa79f](https://linux-hardware.org/?probe=174d5aa79f) | Oct 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a2e0ee2043](https://linux-hardware.org/?probe=a2e0ee2043) | Oct 15, 2022 |
| Acer          | Aspire A315-34              | [a95d9e55ba](https://linux-hardware.org/?probe=a95d9e55ba) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [62dbb6973e](https://linux-hardware.org/?probe=62dbb6973e) | Oct 11, 2022 |
| Acer          | Aspire A317-52              | [af63fa24cb](https://linux-hardware.org/?probe=af63fa24cb) | Oct 09, 2022 |
| Acer          | Swift SF314-511             | [6270245e93](https://linux-hardware.org/?probe=6270245e93) | Oct 08, 2022 |
| ASUSTek       | X505BP                      | [3ebba89d5e](https://linux-hardware.org/?probe=3ebba89d5e) | Oct 07, 2022 |
| Dell          | Inspiron 3542               | [f8d7d79e14](https://linux-hardware.org/?probe=f8d7d79e14) | Oct 07, 2022 |
| Acer          | Aspire A317-52              | [9e6708de22](https://linux-hardware.org/?probe=9e6708de22) | Oct 06, 2022 |
| Acer          | Swift SF113-31              | [be00c7fd40](https://linux-hardware.org/?probe=be00c7fd40) | Oct 06, 2022 |
| Acer          | Swift SF113-31              | [6821710730](https://linux-hardware.org/?probe=6821710730) | Oct 06, 2022 |
| Dell          | XPS 13 9360                 | [1454b8225c](https://linux-hardware.org/?probe=1454b8225c) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | [10fec0d039](https://linux-hardware.org/?probe=10fec0d039) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | [f30bf7e978](https://linux-hardware.org/?probe=f30bf7e978) | Oct 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c277d88bb6](https://linux-hardware.org/?probe=c277d88bb6) | Oct 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [bec157dc7a](https://linux-hardware.org/?probe=bec157dc7a) | Oct 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [d209f29b89](https://linux-hardware.org/?probe=d209f29b89) | Oct 03, 2022 |
| Acer          | Aspire A317-52              | [c59c599497](https://linux-hardware.org/?probe=c59c599497) | Oct 02, 2022 |
| Acer          | TravelMate 8572T            | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Acer          | Nitro AN515-44              | [149337514c](https://linux-hardware.org/?probe=149337514c) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [fa00f3d0ca](https://linux-hardware.org/?probe=fa00f3d0ca) | Sep 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [05927ed93f](https://linux-hardware.org/?probe=05927ed93f) | Sep 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [53cedccf43](https://linux-hardware.org/?probe=53cedccf43) | Sep 28, 2022 |
| Acer          | Aspire A317-52              | [6cc6160f7c](https://linux-hardware.org/?probe=6cc6160f7c) | Sep 27, 2022 |
| Positivo      | S14CT01                     | [2191cd2dd1](https://linux-hardware.org/?probe=2191cd2dd1) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [de8412e05c](https://linux-hardware.org/?probe=de8412e05c) | Sep 25, 2022 |
| Dell          | Latitude E7240              | [75501a47b5](https://linux-hardware.org/?probe=75501a47b5) | Sep 24, 2022 |
| Acer          | Nitro AN515-44              | [b02d161acb](https://linux-hardware.org/?probe=b02d161acb) | Sep 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b73b2224d1](https://linux-hardware.org/?probe=b73b2224d1) | Sep 23, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [65d258e56a](https://linux-hardware.org/?probe=65d258e56a) | Sep 21, 2022 |
| ASUSTek       | X541UAK                     | [b5a6e3ca5e](https://linux-hardware.org/?probe=b5a6e3ca5e) | Sep 20, 2022 |
| Dell          | XPS 13 9360                 | [2b0c376f77](https://linux-hardware.org/?probe=2b0c376f77) | Sep 20, 2022 |
| ASUSTek       | X441NA                      | [282f984233](https://linux-hardware.org/?probe=282f984233) | Sep 19, 2022 |
| Dell          | XPS 13 9360                 | [01aee97dbd](https://linux-hardware.org/?probe=01aee97dbd) | Sep 15, 2022 |
| HP            | 255 G8 Notebook PC          | [37effb8b3c](https://linux-hardware.org/?probe=37effb8b3c) | Sep 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e2c85682b5](https://linux-hardware.org/?probe=e2c85682b5) | Sep 13, 2022 |
| Sony          | SVE1712L1EW                 | [18400c7a0d](https://linux-hardware.org/?probe=18400c7a0d) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [16cf967fc8](https://linux-hardware.org/?probe=16cf967fc8) | Sep 13, 2022 |
| Sony          | SVE1712L1EW                 | [6a797dc1cf](https://linux-hardware.org/?probe=6a797dc1cf) | Sep 12, 2022 |
| Acer          | Nitro AN515-44              | [9f5bc258b6](https://linux-hardware.org/?probe=9f5bc258b6) | Sep 10, 2022 |
| Acer          | TravelMate P449-G3-MG       | [25d82e82b7](https://linux-hardware.org/?probe=25d82e82b7) | Sep 09, 2022 |
| Acer          | Aspire A515-54              | [745c098d8a](https://linux-hardware.org/?probe=745c098d8a) | Sep 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cc0a825c8e](https://linux-hardware.org/?probe=cc0a825c8e) | Sep 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2959121934](https://linux-hardware.org/?probe=2959121934) | Sep 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0356a8d7a1](https://linux-hardware.org/?probe=0356a8d7a1) | Sep 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f3dcbfead7](https://linux-hardware.org/?probe=f3dcbfead7) | Sep 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [93980a32fc](https://linux-hardware.org/?probe=93980a32fc) | Sep 02, 2022 |
| Dell          | Inspiron 1545               | [6cd44f1137](https://linux-hardware.org/?probe=6cd44f1137) | Sep 02, 2022 |
| Acer          | Nitro AN515-54              | [211edd7b18](https://linux-hardware.org/?probe=211edd7b18) | Aug 28, 2022 |
| Acer          | Aspire A315-53              | [6ba36ee616](https://linux-hardware.org/?probe=6ba36ee616) | Aug 28, 2022 |
| Dell          | Inspiron 1545               | [ff02214b7f](https://linux-hardware.org/?probe=ff02214b7f) | Aug 28, 2022 |
| Acer          | Nitro AN515-44              | [7d3e13cfa9](https://linux-hardware.org/?probe=7d3e13cfa9) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0cadff108e](https://linux-hardware.org/?probe=0cadff108e) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [cc7a3508d4](https://linux-hardware.org/?probe=cc7a3508d4) | Aug 27, 2022 |
| Acer          | Nitro AN515-44              | [b456a14fe0](https://linux-hardware.org/?probe=b456a14fe0) | Aug 24, 2022 |
| Acer          | Nitro AN515-44              | [092dcdf5b7](https://linux-hardware.org/?probe=092dcdf5b7) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d64f8a64fa](https://linux-hardware.org/?probe=d64f8a64fa) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [bb928725a6](https://linux-hardware.org/?probe=bb928725a6) | Aug 23, 2022 |
| Dell          | Latitude E6530              | [2dc6598431](https://linux-hardware.org/?probe=2dc6598431) | Aug 21, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | [ce5ed849b0](https://linux-hardware.org/?probe=ce5ed849b0) | Aug 21, 2022 |
| Acer          | Aspire 7750ZG               | [e0d514dd08](https://linux-hardware.org/?probe=e0d514dd08) | Aug 21, 2022 |
| Acer          | Aspire A517-51              | [0cff943f6b](https://linux-hardware.org/?probe=0cff943f6b) | Aug 20, 2022 |
| Lenovo        | G50-45 80E3                 | [0ed8a39444](https://linux-hardware.org/?probe=0ed8a39444) | Aug 19, 2022 |
| Acer          | Nitro AN515-44              | [aa18fee893](https://linux-hardware.org/?probe=aa18fee893) | Aug 18, 2022 |
| Positivo      | S14CT01                     | [22d8d4f3a2](https://linux-hardware.org/?probe=22d8d4f3a2) | Aug 17, 2022 |
| Positivo      | S14CT01                     | [2b561def97](https://linux-hardware.org/?probe=2b561def97) | Aug 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [837e6e891d](https://linux-hardware.org/?probe=837e6e891d) | Aug 13, 2022 |
| Acer          | Aspire V3-571G              | [f45a97ca40](https://linux-hardware.org/?probe=f45a97ca40) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [074b25e3a3](https://linux-hardware.org/?probe=074b25e3a3) | Aug 12, 2022 |
| Positivo      | C14CR21                     | [6e7b0da365](https://linux-hardware.org/?probe=6e7b0da365) | Aug 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e97781a7cc](https://linux-hardware.org/?probe=e97781a7cc) | Aug 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [19c10fbafb](https://linux-hardware.org/?probe=19c10fbafb) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d34fcfc4f7](https://linux-hardware.org/?probe=d34fcfc4f7) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [350a6d8583](https://linux-hardware.org/?probe=350a6d8583) | Aug 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [abe7afa30f](https://linux-hardware.org/?probe=abe7afa30f) | Aug 09, 2022 |
| Acer          | Nitro AN515-54              | [221d7636db](https://linux-hardware.org/?probe=221d7636db) | Aug 08, 2022 |
| Lenovo        | ThinkPad Edge 0578A25       | [ef0500a1f2](https://linux-hardware.org/?probe=ef0500a1f2) | Aug 04, 2022 |
| Lenovo        | ThinkPad Edge 0578A25       | [b7bd71930c](https://linux-hardware.org/?probe=b7bd71930c) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [03770f280e](https://linux-hardware.org/?probe=03770f280e) | Aug 02, 2022 |
| Sony          | VPCEG33FL                   | [6d371d6c32](https://linux-hardware.org/?probe=6d371d6c32) | Jul 31, 2022 |
| Acer          | Nitro AN515-44              | [1c907403d4](https://linux-hardware.org/?probe=1c907403d4) | Jul 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8b3fd99e18](https://linux-hardware.org/?probe=8b3fd99e18) | Jul 27, 2022 |
| Sony          | VPCEG33FL                   | [886dfc7777](https://linux-hardware.org/?probe=886dfc7777) | Jul 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4ee4fc0689](https://linux-hardware.org/?probe=4ee4fc0689) | Jul 26, 2022 |
| Sony          | VPCEG33FL                   | [8767e87e9e](https://linux-hardware.org/?probe=8767e87e9e) | Jul 24, 2022 |
| Acer          | TravelMate 8572T            | [54e7b50fc7](https://linux-hardware.org/?probe=54e7b50fc7) | Jul 18, 2022 |
| Acer          | Aspire A515-54              | [bffac60888](https://linux-hardware.org/?probe=bffac60888) | Jul 16, 2022 |
| Acer          | Aspire A515-54              | [d52eabbac8](https://linux-hardware.org/?probe=d52eabbac8) | Jul 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [046794ca90](https://linux-hardware.org/?probe=046794ca90) | Jul 15, 2022 |
| Chuwi         | LarkBook                    | [501967d2e1](https://linux-hardware.org/?probe=501967d2e1) | Jul 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [55efce6cdc](https://linux-hardware.org/?probe=55efce6cdc) | Jul 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6231802178](https://linux-hardware.org/?probe=6231802178) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1b31625c12](https://linux-hardware.org/?probe=1b31625c12) | Jul 12, 2022 |
| AMI           | Cherry Trail CR             | [b89687ff8f](https://linux-hardware.org/?probe=b89687ff8f) | Jul 12, 2022 |
| Sony          | VPCEA26FG                   | [c5432e157a](https://linux-hardware.org/?probe=c5432e157a) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [d25b4ecc69](https://linux-hardware.org/?probe=d25b4ecc69) | Jul 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1f42376321](https://linux-hardware.org/?probe=1f42376321) | Jul 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a5c61fc1cf](https://linux-hardware.org/?probe=a5c61fc1cf) | Jul 08, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [41840a0102](https://linux-hardware.org/?probe=41840a0102) | Jul 08, 2022 |
| Acer          | Nitro AN515-44              | [d52a3dc4ed](https://linux-hardware.org/?probe=d52a3dc4ed) | Jul 06, 2022 |
| Acer          | Aspire F5-573G              | [c1978d81c7](https://linux-hardware.org/?probe=c1978d81c7) | Jul 05, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bc1f4a78a2](https://linux-hardware.org/?probe=bc1f4a78a2) | Jul 04, 2022 |
| Sony          | VPCEA26FG                   | [2075c04c4c](https://linux-hardware.org/?probe=2075c04c4c) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [81fff806a4](https://linux-hardware.org/?probe=81fff806a4) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [294f501cdd](https://linux-hardware.org/?probe=294f501cdd) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [af946ca10b](https://linux-hardware.org/?probe=af946ca10b) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d68cd17ca2](https://linux-hardware.org/?probe=d68cd17ca2) | Jun 30, 2022 |
| Dell          | Inspiron 1525               | [8f507b2e8c](https://linux-hardware.org/?probe=8f507b2e8c) | Jun 29, 2022 |
| HP            | Pavilion dv7                | [6338462156](https://linux-hardware.org/?probe=6338462156) | Jun 27, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b56f69ff9c](https://linux-hardware.org/?probe=b56f69ff9c) | Jun 26, 2022 |
| Acer          | Nitro AN515-44              | [694f0baf86](https://linux-hardware.org/?probe=694f0baf86) | Jun 26, 2022 |
| AMI           | Cherry Trail CR             | [0ea2a1f20a](https://linux-hardware.org/?probe=0ea2a1f20a) | Jun 26, 2022 |
| ASUSTek       | X542UN                      | [56e348118b](https://linux-hardware.org/?probe=56e348118b) | Jun 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [87f6da99c4](https://linux-hardware.org/?probe=87f6da99c4) | Jun 25, 2022 |
| Acer          | Nitro AN515-54              | [7559b1f8fa](https://linux-hardware.org/?probe=7559b1f8fa) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | [eb8dbfaa92](https://linux-hardware.org/?probe=eb8dbfaa92) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5eaea4e568](https://linux-hardware.org/?probe=5eaea4e568) | Jun 22, 2022 |
| Dell          | Latitude E6530              | [d456333df9](https://linux-hardware.org/?probe=d456333df9) | Jun 21, 2022 |
| Packard Be... | EasyNote MH36               | [ecd7a50e8e](https://linux-hardware.org/?probe=ecd7a50e8e) | Jun 20, 2022 |
| ASUSTek       | X542UN                      | [83a04b4dc4](https://linux-hardware.org/?probe=83a04b4dc4) | Jun 17, 2022 |
| Acer          | Nitro AN515-44              | [5b70211c3a](https://linux-hardware.org/?probe=5b70211c3a) | Jun 16, 2022 |
| Acer          | Nitro AN515-44              | [edf78ac5ae](https://linux-hardware.org/?probe=edf78ac5ae) | Jun 15, 2022 |
| Acer          | Nitro AN515-44              | [ce3588c536](https://linux-hardware.org/?probe=ce3588c536) | Jun 15, 2022 |
| ASUSTek       | Z550SA                      | [c1c96fa0a4](https://linux-hardware.org/?probe=c1c96fa0a4) | Jun 14, 2022 |
| Acer          | Aspire E1-421               | [7cbe6cfc8f](https://linux-hardware.org/?probe=7cbe6cfc8f) | Jun 13, 2022 |
| Acer          | Aspire E1-421               | [8ac8a79ce1](https://linux-hardware.org/?probe=8ac8a79ce1) | Jun 13, 2022 |
| Acer          | Aspire A514-54G             | [a74cd897c5](https://linux-hardware.org/?probe=a74cd897c5) | Jun 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [35dc89f7ff](https://linux-hardware.org/?probe=35dc89f7ff) | Jun 09, 2022 |
| ASUSTek       | X541UAK                     | [92a20ee191](https://linux-hardware.org/?probe=92a20ee191) | Jun 08, 2022 |
| Positivo      | J14GL11                     | [62ab2ad5f4](https://linux-hardware.org/?probe=62ab2ad5f4) | Jun 08, 2022 |
| Dell          | Latitude E6530              | [f155f4f9a3](https://linux-hardware.org/?probe=f155f4f9a3) | Jun 08, 2022 |
| HP            | Laptop 17z-ca100            | [700d19ab97](https://linux-hardware.org/?probe=700d19ab97) | Jun 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9801d8d5c3](https://linux-hardware.org/?probe=9801d8d5c3) | Jun 05, 2022 |
| Dell          | Latitude E6330              | [775f5f5b15](https://linux-hardware.org/?probe=775f5f5b15) | Jun 03, 2022 |
| Dell          | Latitude E6330              | [e471e0e49d](https://linux-hardware.org/?probe=e471e0e49d) | Jun 03, 2022 |
| Acer          | Aspire A514-54G             | [1019de0d68](https://linux-hardware.org/?probe=1019de0d68) | Jun 01, 2022 |
| Dell          | Inspiron 1525               | [246387e9bc](https://linux-hardware.org/?probe=246387e9bc) | Jun 01, 2022 |
| Dell          | Inspiron 1525               | [1b82b95b9a](https://linux-hardware.org/?probe=1b82b95b9a) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ce70b34b9e](https://linux-hardware.org/?probe=ce70b34b9e) | May 31, 2022 |
| Acer          | Aspire A315-34              | [8b9190338e](https://linux-hardware.org/?probe=8b9190338e) | May 31, 2022 |
| Acer          | Nitro AN515-44              | [c3c66e49ab](https://linux-hardware.org/?probe=c3c66e49ab) | May 30, 2022 |
| Acer          | Aspire A315-51              | [083e3a354a](https://linux-hardware.org/?probe=083e3a354a) | May 29, 2022 |
| Acer          | Nitro AN515-44              | [2383d77ab9](https://linux-hardware.org/?probe=2383d77ab9) | May 29, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [ad2442631e](https://linux-hardware.org/?probe=ad2442631e) | May 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [21c0d575b0](https://linux-hardware.org/?probe=21c0d575b0) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [26d3a29dc1](https://linux-hardware.org/?probe=26d3a29dc1) | May 23, 2022 |
| Acer          | Nitro AN515-54              | [5408aee890](https://linux-hardware.org/?probe=5408aee890) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [d972595598](https://linux-hardware.org/?probe=d972595598) | May 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8f9ca8d66b](https://linux-hardware.org/?probe=8f9ca8d66b) | May 20, 2022 |
| Acer          | Nitro AN515-44              | [82a239d311](https://linux-hardware.org/?probe=82a239d311) | May 18, 2022 |
| Acer          | Nitro AN515-44              | [d93d2fe653](https://linux-hardware.org/?probe=d93d2fe653) | May 17, 2022 |
| Acer          | Nitro AN515-44              | [1752fe60cc](https://linux-hardware.org/?probe=1752fe60cc) | May 17, 2022 |
| Acer          | Nitro AN515-44              | [a9e249f407](https://linux-hardware.org/?probe=a9e249f407) | May 16, 2022 |
| Acer          | Nitro AN515-44              | [412fd25cbf](https://linux-hardware.org/?probe=412fd25cbf) | May 15, 2022 |
| Acer          | Swift SF314-54              | [1624fff74b](https://linux-hardware.org/?probe=1624fff74b) | May 15, 2022 |
| Lenovo        | S10-3                       | [b2eb29a65e](https://linux-hardware.org/?probe=b2eb29a65e) | May 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e7fcde8001](https://linux-hardware.org/?probe=e7fcde8001) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [e633129a51](https://linux-hardware.org/?probe=e633129a51) | May 13, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e90b6752ba](https://linux-hardware.org/?probe=e90b6752ba) | May 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [47e5498b35](https://linux-hardware.org/?probe=47e5498b35) | May 12, 2022 |
| Acer          | Nitro AN515-44              | [e3b90bb036](https://linux-hardware.org/?probe=e3b90bb036) | May 11, 2022 |
| Acer          | Nitro AN515-44              | [241c777ac9](https://linux-hardware.org/?probe=241c777ac9) | May 11, 2022 |
| ASUSTek       | X541UAK                     | [50747765ef](https://linux-hardware.org/?probe=50747765ef) | May 10, 2022 |
| ASUSTek       | X541UAK                     | [c1c837e821](https://linux-hardware.org/?probe=c1c837e821) | May 10, 2022 |
| Lenovo        | V14-IGL 82C2                | [0d1e1d71ee](https://linux-hardware.org/?probe=0d1e1d71ee) | May 08, 2022 |
| Acer          | Aspire A514-54G             | [ec1fa8e360](https://linux-hardware.org/?probe=ec1fa8e360) | May 08, 2022 |
| Lenovo        | V14-IGL 82C2                | [3ad9fd00c2](https://linux-hardware.org/?probe=3ad9fd00c2) | May 08, 2022 |
| Lenovo        | ThinkPad X131e 33691J6      | [1f492cb261](https://linux-hardware.org/?probe=1f492cb261) | May 08, 2022 |
| Acer          | Aspire A514-54G             | [b4b52aad69](https://linux-hardware.org/?probe=b4b52aad69) | May 07, 2022 |
| Dell          | Inspiron 5558               | [3cab561b32](https://linux-hardware.org/?probe=3cab561b32) | May 04, 2022 |
| Dell          | Latitude E6420              | [77d218efc8](https://linux-hardware.org/?probe=77d218efc8) | May 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4516542417](https://linux-hardware.org/?probe=4516542417) | May 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| HP            | 250 G5 Notebook PC          | [0e6717d54b](https://linux-hardware.org/?probe=0e6717d54b) | May 02, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [112d0557c3](https://linux-hardware.org/?probe=112d0557c3) | May 01, 2022 |
| ASUSTek       | X540UA                      | [af0ed39935](https://linux-hardware.org/?probe=af0ed39935) | May 01, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [633bddd44b](https://linux-hardware.org/?probe=633bddd44b) | Apr 30, 2022 |
| Google        | Fleex                       | [212ff0673f](https://linux-hardware.org/?probe=212ff0673f) | Apr 30, 2022 |
| Lenovo        | S10-3                       | [712c2dced9](https://linux-hardware.org/?probe=712c2dced9) | Apr 30, 2022 |
| ASUSTek       | X541UAK                     | [7bac9962d9](https://linux-hardware.org/?probe=7bac9962d9) | Apr 29, 2022 |
| HP            | Pavilion 14                 | [84bde5e223](https://linux-hardware.org/?probe=84bde5e223) | Apr 29, 2022 |
| HP            | Pavilion dv7                | [fd2d8cc4f6](https://linux-hardware.org/?probe=fd2d8cc4f6) | Apr 29, 2022 |
| Acer          | Nitro AN515-44              | [11b568f82d](https://linux-hardware.org/?probe=11b568f82d) | Apr 28, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [58076aa8e9](https://linux-hardware.org/?probe=58076aa8e9) | Apr 28, 2022 |
| Acer          | Aspire A315-34              | [a49e25f2b8](https://linux-hardware.org/?probe=a49e25f2b8) | Apr 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcc0c7612d](https://linux-hardware.org/?probe=bcc0c7612d) | Apr 26, 2022 |
| Acer          | Nitro AN515-44              | [319cbc94dd](https://linux-hardware.org/?probe=319cbc94dd) | Apr 25, 2022 |
| HP            | Notebook                    | [4772a69956](https://linux-hardware.org/?probe=4772a69956) | Apr 23, 2022 |
| Acer          | Nitro AN515-44              | [6e05fa6a88](https://linux-hardware.org/?probe=6e05fa6a88) | Apr 23, 2022 |
| ASUSTek       | X450CP                      | [2518b6daad](https://linux-hardware.org/?probe=2518b6daad) | Apr 22, 2022 |
| ASUSTek       | X450CP                      | [17d51c502f](https://linux-hardware.org/?probe=17d51c502f) | Apr 22, 2022 |
| Dell          | Inspiron 1525               | [b5dbaddd84](https://linux-hardware.org/?probe=b5dbaddd84) | Apr 22, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [b53c2836e9](https://linux-hardware.org/?probe=b53c2836e9) | Apr 21, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [cb2bc8f53e](https://linux-hardware.org/?probe=cb2bc8f53e) | Apr 21, 2022 |
| ASUSTek       | X541UAK                     | [8b54af493a](https://linux-hardware.org/?probe=8b54af493a) | Apr 19, 2022 |
| HP            | 250 G5 Notebook PC          | [5cb8325ed4](https://linux-hardware.org/?probe=5cb8325ed4) | Apr 18, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [7855e19861](https://linux-hardware.org/?probe=7855e19861) | Apr 17, 2022 |
| ASUSTek       | X541UAK                     | [811e032c61](https://linux-hardware.org/?probe=811e032c61) | Apr 16, 2022 |
| Acer          | Aspire E1-572               | [27d5f97167](https://linux-hardware.org/?probe=27d5f97167) | Apr 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [ce5b3c38ab](https://linux-hardware.org/?probe=ce5b3c38ab) | Apr 13, 2022 |
| Fujitsu       | LIFEBOOK A512               | [a477479700](https://linux-hardware.org/?probe=a477479700) | Apr 12, 2022 |
| ASUSTek       | X451CA                      | [865aec543f](https://linux-hardware.org/?probe=865aec543f) | Apr 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [dcd1291b92](https://linux-hardware.org/?probe=dcd1291b92) | Apr 11, 2022 |
| Acer          | Nitro AN515-44              | [6748a96716](https://linux-hardware.org/?probe=6748a96716) | Apr 11, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [e6adfda5ec](https://linux-hardware.org/?probe=e6adfda5ec) | Apr 11, 2022 |
| ASUSTek       | X541UAK                     | [ffb5635168](https://linux-hardware.org/?probe=ffb5635168) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ab7173f335](https://linux-hardware.org/?probe=ab7173f335) | Apr 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b86cec3f38](https://linux-hardware.org/?probe=b86cec3f38) | Apr 10, 2022 |
| ASUSTek       | X540LJ                      | [2eb11881fa](https://linux-hardware.org/?probe=2eb11881fa) | Apr 09, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [4c367d8a9c](https://linux-hardware.org/?probe=4c367d8a9c) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [54bc7d6864](https://linux-hardware.org/?probe=54bc7d6864) | Apr 07, 2022 |
| Acer          | Nitro AN515-44              | [8c8679b57b](https://linux-hardware.org/?probe=8c8679b57b) | Apr 06, 2022 |
| ASUSTek       | 1015PE                      | [0643abbf5b](https://linux-hardware.org/?probe=0643abbf5b) | Apr 05, 2022 |
| Acer          | Nitro AN515-44              | [e007605c2c](https://linux-hardware.org/?probe=e007605c2c) | Apr 05, 2022 |
| Acer          | Nitro AN515-44              | [ab77f43b05](https://linux-hardware.org/?probe=ab77f43b05) | Apr 03, 2022 |
| Acer          | Nitro AN515-44              | [53c0c6467d](https://linux-hardware.org/?probe=53c0c6467d) | Apr 01, 2022 |
| Acer          | Nitro AN515-44              | [6a7bc096c0](https://linux-hardware.org/?probe=6a7bc096c0) | Apr 01, 2022 |
| Multilaser    | PC13X                       | [d62e1676c3](https://linux-hardware.org/?probe=d62e1676c3) | Apr 01, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [21a9f5c811](https://linux-hardware.org/?probe=21a9f5c811) | Apr 01, 2022 |
| Dell          | Latitude E5430 non-vPro     | [28ddf22c68](https://linux-hardware.org/?probe=28ddf22c68) | Mar 31, 2022 |
| Multilaser    | PC13X                       | [e0e93fcf81](https://linux-hardware.org/?probe=e0e93fcf81) | Mar 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2d741207c5](https://linux-hardware.org/?probe=2d741207c5) | Mar 30, 2022 |
| Acer          | Aspire A515-54G             | [b4864a1611](https://linux-hardware.org/?probe=b4864a1611) | Mar 27, 2022 |
| Acer          | Nitro AN515-44              | [29d034d804](https://linux-hardware.org/?probe=29d034d804) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | [d2733b3c95](https://linux-hardware.org/?probe=d2733b3c95) | Mar 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8d1c371df2](https://linux-hardware.org/?probe=8d1c371df2) | Mar 21, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [99dc5cde41](https://linux-hardware.org/?probe=99dc5cde41) | Mar 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d74cd69ff9](https://linux-hardware.org/?probe=d74cd69ff9) | Mar 20, 2022 |
| Acer          | Nitro AN515-44              | [519b33398d](https://linux-hardware.org/?probe=519b33398d) | Mar 20, 2022 |
| Compal        | NCL60/61                    | [39c9e97e85](https://linux-hardware.org/?probe=39c9e97e85) | Mar 19, 2022 |
| HP            | Laptop 17z-ca100            | [048eff2daf](https://linux-hardware.org/?probe=048eff2daf) | Mar 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [591f5cdcc0](https://linux-hardware.org/?probe=591f5cdcc0) | Mar 18, 2022 |
| Philco        | 14I                         | [ceefb7fc2f](https://linux-hardware.org/?probe=ceefb7fc2f) | Mar 18, 2022 |
| Acer          | Nitro AN515-44              | [be2d436df6](https://linux-hardware.org/?probe=be2d436df6) | Mar 17, 2022 |
| Acer          | Nitro AN515-44              | [05d071af74](https://linux-hardware.org/?probe=05d071af74) | Mar 16, 2022 |
| Acer          | Nitro AN515-44              | [83d37bb724](https://linux-hardware.org/?probe=83d37bb724) | Mar 16, 2022 |
| Acer          | Nitro AN515-44              | [e5d7cda06b](https://linux-hardware.org/?probe=e5d7cda06b) | Mar 16, 2022 |
| Intel         | powered classmate PC        | [6938945c70](https://linux-hardware.org/?probe=6938945c70) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [373fa69bd1](https://linux-hardware.org/?probe=373fa69bd1) | Mar 14, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [5ee92a3245](https://linux-hardware.org/?probe=5ee92a3245) | Mar 13, 2022 |
| HP            | 250 G5 Notebook PC          | [3e67ab27db](https://linux-hardware.org/?probe=3e67ab27db) | Mar 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [770f279722](https://linux-hardware.org/?probe=770f279722) | Mar 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [21dfbc138d](https://linux-hardware.org/?probe=21dfbc138d) | Mar 13, 2022 |
| Positivo      | S14CT01                     | [198fc329a3](https://linux-hardware.org/?probe=198fc329a3) | Mar 12, 2022 |
| Acer          | Aspire A114-31              | [aa9bcbb679](https://linux-hardware.org/?probe=aa9bcbb679) | Mar 11, 2022 |
| Acer          | Nitro AN515-54              | [cca64bfd46](https://linux-hardware.org/?probe=cca64bfd46) | Mar 10, 2022 |
| Acer          | Aspire A315-56              | [dbc222289c](https://linux-hardware.org/?probe=dbc222289c) | Mar 10, 2022 |
| Acer          | Aspire 4745Z                | [a3021ea674](https://linux-hardware.org/?probe=a3021ea674) | Mar 06, 2022 |
| Toshiba       | Satellite L755              | [1bb7472f87](https://linux-hardware.org/?probe=1bb7472f87) | Mar 06, 2022 |
| HP            | Laptop 17z-ca100            | [a646411afd](https://linux-hardware.org/?probe=a646411afd) | Mar 06, 2022 |
| Acer          | Aspire A515-54              | [5119ee3a39](https://linux-hardware.org/?probe=5119ee3a39) | Mar 05, 2022 |
| Acer          | Aspire A515-51              | [77e4345afe](https://linux-hardware.org/?probe=77e4345afe) | Mar 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [95296f29bb](https://linux-hardware.org/?probe=95296f29bb) | Mar 02, 2022 |
| ASUSTek       | X451CAP                     | [733cc22d43](https://linux-hardware.org/?probe=733cc22d43) | Feb 26, 2022 |
| Acer          | Nitro AN515-44              | [8340571f28](https://linux-hardware.org/?probe=8340571f28) | Feb 25, 2022 |
| Acer          | Aspire A315-53              | [903ce0415a](https://linux-hardware.org/?probe=903ce0415a) | Feb 25, 2022 |
| HP            | Pavilion dv7                | [46280b758c](https://linux-hardware.org/?probe=46280b758c) | Feb 25, 2022 |
| Acer          | Aspire A315-34              | [d02db54216](https://linux-hardware.org/?probe=d02db54216) | Feb 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [baa1d24da5](https://linux-hardware.org/?probe=baa1d24da5) | Feb 24, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [34efccbe97](https://linux-hardware.org/?probe=34efccbe97) | Feb 22, 2022 |
| Toshiba       | Satellite C50-A-19T         | [c0735b93a0](https://linux-hardware.org/?probe=c0735b93a0) | Feb 22, 2022 |
| Toshiba       | Satellite C50-A-19T         | [c307c3abc8](https://linux-hardware.org/?probe=c307c3abc8) | Feb 22, 2022 |
| Acer          | Aspire A315-54              | [1a5f1021df](https://linux-hardware.org/?probe=1a5f1021df) | Feb 21, 2022 |
| HP            | Pavilion dv7                | [fd1bbe1769](https://linux-hardware.org/?probe=fd1bbe1769) | Feb 21, 2022 |
| HP            | Pavilion dv7                | [da9449422c](https://linux-hardware.org/?probe=da9449422c) | Feb 21, 2022 |
| DEXP          | NH5BT15                     | [c6ef26c1ae](https://linux-hardware.org/?probe=c6ef26c1ae) | Feb 20, 2022 |
| Acer          | Aspire A315-34              | [642e1f0705](https://linux-hardware.org/?probe=642e1f0705) | Feb 20, 2022 |
| Acer          | Aspire A315-34              | [8c976c5259](https://linux-hardware.org/?probe=8c976c5259) | Feb 20, 2022 |
| Acer          | Nitro AN515-44              | [198452fc15](https://linux-hardware.org/?probe=198452fc15) | Feb 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [86af1dc736](https://linux-hardware.org/?probe=86af1dc736) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [823e19e6d3](https://linux-hardware.org/?probe=823e19e6d3) | Feb 19, 2022 |
| Acer          | Nitro AN515-44              | [cce1f45d54](https://linux-hardware.org/?probe=cce1f45d54) | Feb 19, 2022 |
| Lenovo        | G700 20251                  | [2e68ddfdd3](https://linux-hardware.org/?probe=2e68ddfdd3) | Feb 18, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [489854bd7b](https://linux-hardware.org/?probe=489854bd7b) | Feb 18, 2022 |
| ASUSTek       | T100TA                      | [9f0a454d8b](https://linux-hardware.org/?probe=9f0a454d8b) | Feb 18, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1582806778](https://linux-hardware.org/?probe=1582806778) | Feb 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ed75c609e4](https://linux-hardware.org/?probe=ed75c609e4) | Feb 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [470a550d41](https://linux-hardware.org/?probe=470a550d41) | Feb 16, 2022 |
| Acer          | Nitro AN515-44              | [21d0529167](https://linux-hardware.org/?probe=21d0529167) | Feb 16, 2022 |
| HP            | Laptop 15s-gr0xxx           | [db6e83a4b8](https://linux-hardware.org/?probe=db6e83a4b8) | Feb 14, 2022 |
| Acer          | Aspire A315-53              | [2a2ca89607](https://linux-hardware.org/?probe=2a2ca89607) | Feb 13, 2022 |
| Acer          | Nitro AN515-44              | [dbacdb1c14](https://linux-hardware.org/?probe=dbacdb1c14) | Feb 11, 2022 |
| Acer          | Nitro AN515-44              | [f886f43d19](https://linux-hardware.org/?probe=f886f43d19) | Feb 11, 2022 |
| Acer          | Nitro AN515-54              | [3f2bbe863b](https://linux-hardware.org/?probe=3f2bbe863b) | Feb 09, 2022 |
| Acer          | Nitro AN515-44              | [74eb28f4a3](https://linux-hardware.org/?probe=74eb28f4a3) | Feb 08, 2022 |
| Acer          | Aspire A315-53              | [345a864747](https://linux-hardware.org/?probe=345a864747) | Feb 06, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [14cfb63e15](https://linux-hardware.org/?probe=14cfb63e15) | Feb 06, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [310e0596c7](https://linux-hardware.org/?probe=310e0596c7) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eed6d95df2](https://linux-hardware.org/?probe=eed6d95df2) | Feb 03, 2022 |
| Dell          | Vostro 2520                 | [a78ce3401f](https://linux-hardware.org/?probe=a78ce3401f) | Jan 31, 2022 |
| Acer          | Nitro AN515-44              | [313d4824d2](https://linux-hardware.org/?probe=313d4824d2) | Jan 29, 2022 |
| Acer          | Aspire A315-53              | [e0b0cbe190](https://linux-hardware.org/?probe=e0b0cbe190) | Jan 29, 2022 |
| Dell          | Inspiron 1525               | [cf0c5309ad](https://linux-hardware.org/?probe=cf0c5309ad) | Jan 29, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6ba91410f8](https://linux-hardware.org/?probe=6ba91410f8) | Jan 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [48ad956cc2](https://linux-hardware.org/?probe=48ad956cc2) | Jan 28, 2022 |
| Acer          | Aspire A517-51              | [62a28ff4d9](https://linux-hardware.org/?probe=62a28ff4d9) | Jan 23, 2022 |
| Acer          | Aspire A315-34              | [8a843419b7](https://linux-hardware.org/?probe=8a843419b7) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c77e8f334](https://linux-hardware.org/?probe=4c77e8f334) | Jan 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f5e870f95b](https://linux-hardware.org/?probe=f5e870f95b) | Jan 21, 2022 |
| ASUSTek       | N55SF                       | [e800e249d1](https://linux-hardware.org/?probe=e800e249d1) | Jan 19, 2022 |
| ASUSTek       | X541UAK                     | [2f55e0a142](https://linux-hardware.org/?probe=2f55e0a142) | Jan 19, 2022 |
| ASUSTek       | N55SF                       | [104263a808](https://linux-hardware.org/?probe=104263a808) | Jan 19, 2022 |
| Acer          | Nitro AN517-51              | [fbcf7fffa8](https://linux-hardware.org/?probe=fbcf7fffa8) | Jan 19, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [1d9c3b162d](https://linux-hardware.org/?probe=1d9c3b162d) | Jan 18, 2022 |
| Acer          | Nitro AN515-54              | [b6d4b36704](https://linux-hardware.org/?probe=b6d4b36704) | Jan 18, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [a84625d725](https://linux-hardware.org/?probe=a84625d725) | Jan 18, 2022 |
| eMachines     | G640                        | [3d750908c7](https://linux-hardware.org/?probe=3d750908c7) | Jan 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3f953ad7f3](https://linux-hardware.org/?probe=3f953ad7f3) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [eecedd12b2](https://linux-hardware.org/?probe=eecedd12b2) | Jan 14, 2022 |
| Acer          | Aspire A515-54              | [3ea50d80ec](https://linux-hardware.org/?probe=3ea50d80ec) | Jan 14, 2022 |
| ASUSTek       | Z550SA                      | [322fa160ae](https://linux-hardware.org/?probe=322fa160ae) | Jan 11, 2022 |
| Acer          | Aspire A315-34              | [52197b0dea](https://linux-hardware.org/?probe=52197b0dea) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [04cd3cf175](https://linux-hardware.org/?probe=04cd3cf175) | Jan 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e23725a744](https://linux-hardware.org/?probe=e23725a744) | Jan 10, 2022 |
| Acer          | Aspire A315-34              | [609662084d](https://linux-hardware.org/?probe=609662084d) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [56d6ea164b](https://linux-hardware.org/?probe=56d6ea164b) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d9bd1bab23](https://linux-hardware.org/?probe=d9bd1bab23) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0ca0e6ddd6](https://linux-hardware.org/?probe=0ca0e6ddd6) | Jan 08, 2022 |
| ASUSTek       | X541UAK                     | [353534e82a](https://linux-hardware.org/?probe=353534e82a) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [bdfe615a8e](https://linux-hardware.org/?probe=bdfe615a8e) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [ca2b9fac6f](https://linux-hardware.org/?probe=ca2b9fac6f) | Jan 07, 2022 |
| HP            | EliteBook 1040 G2           | [ca6f52fbeb](https://linux-hardware.org/?probe=ca6f52fbeb) | Jan 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d453a69dad](https://linux-hardware.org/?probe=d453a69dad) | Jan 06, 2022 |
| Acer          | Aspire A315-51              | [4f31432ca6](https://linux-hardware.org/?probe=4f31432ca6) | Jan 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a43e15b7ad](https://linux-hardware.org/?probe=a43e15b7ad) | Jan 06, 2022 |
| Acer          | Aspire A315-21              | [91548d30f5](https://linux-hardware.org/?probe=91548d30f5) | Jan 06, 2022 |
| HP            | Compaq Mini CQ10-400        | [643f4e101f](https://linux-hardware.org/?probe=643f4e101f) | Jan 05, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [1533754d35](https://linux-hardware.org/?probe=1533754d35) | Jan 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcc46e9fcb](https://linux-hardware.org/?probe=bcc46e9fcb) | Jan 05, 2022 |
| HP            | Compaq Mini CQ10-400        | [ca3df238bc](https://linux-hardware.org/?probe=ca3df238bc) | Jan 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [762281ace3](https://linux-hardware.org/?probe=762281ace3) | Jan 04, 2022 |
| ASUSTek       | X541UAK                     | [bd5145c8b1](https://linux-hardware.org/?probe=bd5145c8b1) | Jan 03, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [4e5ce73412](https://linux-hardware.org/?probe=4e5ce73412) | Jan 02, 2022 |
| Acer          | Swift SF113-31              | [7122c86d4f](https://linux-hardware.org/?probe=7122c86d4f) | Jan 02, 2022 |
| Acer          | Nitro AN515-44              | [be76922082](https://linux-hardware.org/?probe=be76922082) | Jan 02, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [86160c79c7](https://linux-hardware.org/?probe=86160c79c7) | Jan 01, 2022 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | [46498e6c58](https://linux-hardware.org/?probe=46498e6c58) | Dec 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0b4b86fd4d](https://linux-hardware.org/?probe=0b4b86fd4d) | Dec 30, 2021 |
| Sony          | SVF1521A7EB                 | [5d72995b21](https://linux-hardware.org/?probe=5d72995b21) | Dec 30, 2021 |
| Sony          | SVF1521A7EB                 | [7bb54a83fc](https://linux-hardware.org/?probe=7bb54a83fc) | Dec 30, 2021 |
| Acer          | Nitro AN515-54              | [deb4e10a41](https://linux-hardware.org/?probe=deb4e10a41) | Dec 29, 2021 |
| Acer          | Nitro AN515-44              | [0ba9ee7a74](https://linux-hardware.org/?probe=0ba9ee7a74) | Dec 29, 2021 |
| Acer          | Aspire A315-34              | [93ddeaab25](https://linux-hardware.org/?probe=93ddeaab25) | Dec 29, 2021 |
| Acer          | Aspire A315-54K             | [b662c9c046](https://linux-hardware.org/?probe=b662c9c046) | Dec 28, 2021 |
| Acer          | Aspire A315-34              | [af582ea780](https://linux-hardware.org/?probe=af582ea780) | Dec 28, 2021 |
| ASUSTek       | G74Sx                       | [7ae1568f36](https://linux-hardware.org/?probe=7ae1568f36) | Dec 27, 2021 |
| Positivo      | V142N_4G                    | [fb167e6518](https://linux-hardware.org/?probe=fb167e6518) | Dec 27, 2021 |
| Acer          | Nitro AN515-44              | [d0bf339bdf](https://linux-hardware.org/?probe=d0bf339bdf) | Dec 26, 2021 |
| Dell          | System Vostro 3450          | [9499015c46](https://linux-hardware.org/?probe=9499015c46) | Dec 23, 2021 |
| Acer          | Nitro AN515-54              | [3a101db74b](https://linux-hardware.org/?probe=3a101db74b) | Dec 23, 2021 |
| Acer          | Aspire A315-34              | [40e8ac4ece](https://linux-hardware.org/?probe=40e8ac4ece) | Dec 23, 2021 |
| Positivo      | CHT14B                      | [ae9f7801cf](https://linux-hardware.org/?probe=ae9f7801cf) | Dec 23, 2021 |
| Positivo      | CHT14B                      | [3efc353498](https://linux-hardware.org/?probe=3efc353498) | Dec 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [492fc37142](https://linux-hardware.org/?probe=492fc37142) | Dec 22, 2021 |
| ASUSTek       | G74Sx                       | [ac5f615cbd](https://linux-hardware.org/?probe=ac5f615cbd) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [da08b0d873](https://linux-hardware.org/?probe=da08b0d873) | Dec 22, 2021 |
| ASUSTek       | X540UA                      | [4d399918f0](https://linux-hardware.org/?probe=4d399918f0) | Dec 20, 2021 |
| HP            | Notebook                    | [f83e86b312](https://linux-hardware.org/?probe=f83e86b312) | Dec 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e8a4a4a5f4](https://linux-hardware.org/?probe=e8a4a4a5f4) | Dec 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0642db16f6](https://linux-hardware.org/?probe=0642db16f6) | Dec 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ce1a1eb460](https://linux-hardware.org/?probe=ce1a1eb460) | Dec 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bfdb06c0ae](https://linux-hardware.org/?probe=bfdb06c0ae) | Dec 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [75183b17a9](https://linux-hardware.org/?probe=75183b17a9) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d3de4858ff](https://linux-hardware.org/?probe=d3de4858ff) | Dec 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ecf858d3fa](https://linux-hardware.org/?probe=ecf858d3fa) | Dec 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [baac720c6c](https://linux-hardware.org/?probe=baac720c6c) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ac40d89d27](https://linux-hardware.org/?probe=ac40d89d27) | Dec 16, 2021 |
| Acer          | Aspire A315-34              | [c76d68c4fd](https://linux-hardware.org/?probe=c76d68c4fd) | Dec 15, 2021 |
| Acer          | Nitro AN515-44              | [4a44000cf0](https://linux-hardware.org/?probe=4a44000cf0) | Dec 14, 2021 |
| Acer          | Nitro AN515-44              | [44d2be94f6](https://linux-hardware.org/?probe=44d2be94f6) | Dec 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e40a285a7e](https://linux-hardware.org/?probe=e40a285a7e) | Dec 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b2dc5e9741](https://linux-hardware.org/?probe=b2dc5e9741) | Dec 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [74591e1700](https://linux-hardware.org/?probe=74591e1700) | Dec 12, 2021 |
| Acer          | Nitro AN515-44              | [f5ae8cd0ac](https://linux-hardware.org/?probe=f5ae8cd0ac) | Dec 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b328ed77b4](https://linux-hardware.org/?probe=b328ed77b4) | Dec 11, 2021 |
| Dell          | Inspiron 3180               | [0a4edcaa69](https://linux-hardware.org/?probe=0a4edcaa69) | Dec 11, 2021 |
| Toshiba       | Satellite P75-A             | [a225156d55](https://linux-hardware.org/?probe=a225156d55) | Dec 11, 2021 |
| ASUSTek       | X705UAR                     | [74b8b78444](https://linux-hardware.org/?probe=74b8b78444) | Dec 11, 2021 |
| Acer          | Nitro AN515-44              | [1acc5eb194](https://linux-hardware.org/?probe=1acc5eb194) | Dec 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [191c3b9c7e](https://linux-hardware.org/?probe=191c3b9c7e) | Dec 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c7efd05b73](https://linux-hardware.org/?probe=c7efd05b73) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [18e35161ad](https://linux-hardware.org/?probe=18e35161ad) | Dec 10, 2021 |
| Acer          | Aspire A315-34              | [862ca9280c](https://linux-hardware.org/?probe=862ca9280c) | Dec 10, 2021 |
| Chuwi         | HeroBook Air                | [dd5567d4dc](https://linux-hardware.org/?probe=dd5567d4dc) | Dec 08, 2021 |
| Toshiba       | Satellite L300              | [a676b11b67](https://linux-hardware.org/?probe=a676b11b67) | Dec 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2ac4810e93](https://linux-hardware.org/?probe=2ac4810e93) | Dec 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5f9f761ed0](https://linux-hardware.org/?probe=5f9f761ed0) | Dec 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [669a87825e](https://linux-hardware.org/?probe=669a87825e) | Dec 08, 2021 |
| HP            | Unknown                     | [33ca2db025](https://linux-hardware.org/?probe=33ca2db025) | Dec 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [db73d74107](https://linux-hardware.org/?probe=db73d74107) | Dec 07, 2021 |
| Acer          | Aspire A315-34              | [7fe252c0cd](https://linux-hardware.org/?probe=7fe252c0cd) | Dec 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8ef0bff5e1](https://linux-hardware.org/?probe=8ef0bff5e1) | Dec 07, 2021 |
| Acer          | Nitro AN515-44              | [88d9ee29b4](https://linux-hardware.org/?probe=88d9ee29b4) | Dec 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [059c42fd1a](https://linux-hardware.org/?probe=059c42fd1a) | Dec 06, 2021 |
| Acer          | Nitro AN515-54              | [7763d72707](https://linux-hardware.org/?probe=7763d72707) | Dec 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a838b63586](https://linux-hardware.org/?probe=a838b63586) | Dec 05, 2021 |
| Acer          | Aspire E1-572               | [a3524e5c56](https://linux-hardware.org/?probe=a3524e5c56) | Dec 05, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [aa4d4e3b08](https://linux-hardware.org/?probe=aa4d4e3b08) | Dec 04, 2021 |
| Acer          | Nitro AN515-44              | [a824747d21](https://linux-hardware.org/?probe=a824747d21) | Dec 02, 2021 |
| Acer          | Aspire A315-34              | [9bbfd01bca](https://linux-hardware.org/?probe=9bbfd01bca) | Dec 01, 2021 |
| Acer          | Aspire A315-53              | [18d91295e1](https://linux-hardware.org/?probe=18d91295e1) | Dec 01, 2021 |
| Acer          | Nitro AN515-54              | [991967c2ff](https://linux-hardware.org/?probe=991967c2ff) | Nov 30, 2021 |
| Acer          | Nitro AN515-44              | [7edf9fe1b5](https://linux-hardware.org/?probe=7edf9fe1b5) | Nov 30, 2021 |
| Acer          | Nitro AN517-51              | [e7af37db76](https://linux-hardware.org/?probe=e7af37db76) | Nov 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ea985c61da](https://linux-hardware.org/?probe=ea985c61da) | Nov 29, 2021 |
| Acer          | TravelMate P253             | [cc535c766a](https://linux-hardware.org/?probe=cc535c766a) | Nov 29, 2021 |
| Acer          | Nitro AN515-44              | [71e47d66a9](https://linux-hardware.org/?probe=71e47d66a9) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | [7add4c45f0](https://linux-hardware.org/?probe=7add4c45f0) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | [c3ac874c98](https://linux-hardware.org/?probe=c3ac874c98) | Nov 28, 2021 |
| Acer          | Nitro AN515-44              | [02b7a680cd](https://linux-hardware.org/?probe=02b7a680cd) | Nov 28, 2021 |
| ASUSTek       | X541UAK                     | [bb138385d2](https://linux-hardware.org/?probe=bb138385d2) | Nov 27, 2021 |
| Acer          | Nitro AN515-54              | [b63d468197](https://linux-hardware.org/?probe=b63d468197) | Nov 27, 2021 |
| Sony          | VPCCB35FG                   | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [d6acd43784](https://linux-hardware.org/?probe=d6acd43784) | Nov 25, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [e820cb3456](https://linux-hardware.org/?probe=e820cb3456) | Nov 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [c420169ce7](https://linux-hardware.org/?probe=c420169ce7) | Nov 25, 2021 |
| Acer          | Nitro AN515-54              | [4766af9ef7](https://linux-hardware.org/?probe=4766af9ef7) | Nov 25, 2021 |
| Acer          | Aspire A315-53              | [9dcd5129ea](https://linux-hardware.org/?probe=9dcd5129ea) | Nov 24, 2021 |
| Dell          | Inspiron N5110              | [ea27790fc4](https://linux-hardware.org/?probe=ea27790fc4) | Nov 23, 2021 |
| Acer          | Nitro AN515-44              | [9fd987e7d8](https://linux-hardware.org/?probe=9fd987e7d8) | Nov 23, 2021 |
| Acer          | Nitro AN515-43              | [457a2ff293](https://linux-hardware.org/?probe=457a2ff293) | Nov 23, 2021 |
| Toshiba       | Satellite Pro C850-1D5      | [22ed560714](https://linux-hardware.org/?probe=22ed560714) | Nov 21, 2021 |
| ASUSTek       | X450CP                      | [7228a5157c](https://linux-hardware.org/?probe=7228a5157c) | Nov 20, 2021 |
| Toshiba       | IS 1462B                    | [682a8f788c](https://linux-hardware.org/?probe=682a8f788c) | Nov 20, 2021 |
| Acer          | Aspire 4745                 | [9edc4a1dd4](https://linux-hardware.org/?probe=9edc4a1dd4) | Nov 19, 2021 |
| HP            | ENVY 15                     | [31e0758aad](https://linux-hardware.org/?probe=31e0758aad) | Nov 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1784f93056](https://linux-hardware.org/?probe=1784f93056) | Nov 18, 2021 |
| Acer          | Nitro AN515-44              | [d71fa6378d](https://linux-hardware.org/?probe=d71fa6378d) | Nov 17, 2021 |
| MSI           | VR610                       | [9dd3927cf1](https://linux-hardware.org/?probe=9dd3927cf1) | Nov 15, 2021 |
| MSI           | VR610                       | [fa0f1da6d7](https://linux-hardware.org/?probe=fa0f1da6d7) | Nov 15, 2021 |
| Acer          | Nitro AN515-44              | [328668f616](https://linux-hardware.org/?probe=328668f616) | Nov 14, 2021 |
| Acer          | Aspire A515-54              | [7f5b5d0c7a](https://linux-hardware.org/?probe=7f5b5d0c7a) | Nov 13, 2021 |
| Acer          | Aspire A315-34              | [e9840b2a27](https://linux-hardware.org/?probe=e9840b2a27) | Nov 13, 2021 |
| Acer          | Nitro AN515-54              | [2a98c5ad7b](https://linux-hardware.org/?probe=2a98c5ad7b) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [e0c343709d](https://linux-hardware.org/?probe=e0c343709d) | Nov 12, 2021 |
| ASUSTek       | X540NA                      | [86bce5bb0d](https://linux-hardware.org/?probe=86bce5bb0d) | Nov 12, 2021 |
| Packard Be... | EasyNote TN36               | [17ebc64721](https://linux-hardware.org/?probe=17ebc64721) | Nov 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [b79aef683b](https://linux-hardware.org/?probe=b79aef683b) | Nov 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b2e5c211fc](https://linux-hardware.org/?probe=b2e5c211fc) | Nov 10, 2021 |
| HP            | Pavilion dv7                | [3c3e5bc872](https://linux-hardware.org/?probe=3c3e5bc872) | Nov 08, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | [4bc0687791](https://linux-hardware.org/?probe=4bc0687791) | Nov 08, 2021 |
| HP            | 255 G8 Notebook PC          | [8b35cac0f6](https://linux-hardware.org/?probe=8b35cac0f6) | Nov 07, 2021 |
| HP            | 255 G8 Notebook PC          | [fd582fb82b](https://linux-hardware.org/?probe=fd582fb82b) | Nov 07, 2021 |
| Dell          | Latitude E7440              | [816aaeac91](https://linux-hardware.org/?probe=816aaeac91) | Nov 06, 2021 |
| Dell          | Latitude E7440              | [bdd82f1a23](https://linux-hardware.org/?probe=bdd82f1a23) | Nov 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [81d7a98b1a](https://linux-hardware.org/?probe=81d7a98b1a) | Nov 05, 2021 |
| Acer          | Aspire ES1-533              | [14a4c57e27](https://linux-hardware.org/?probe=14a4c57e27) | Nov 05, 2021 |
| Toshiba       | IS 1462B                    | [a5538db795](https://linux-hardware.org/?probe=a5538db795) | Nov 04, 2021 |
| ASUSTek       | X442UAR                     | [0db140fa3d](https://linux-hardware.org/?probe=0db140fa3d) | Nov 03, 2021 |
| Sony          | VPCYB1S1E                   | [bbe04676c1](https://linux-hardware.org/?probe=bbe04676c1) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | [09eba8bb5f](https://linux-hardware.org/?probe=09eba8bb5f) | Nov 02, 2021 |
| Acer          | Nitro AN515-44              | [754d944557](https://linux-hardware.org/?probe=754d944557) | Nov 01, 2021 |
| Acer          | Aspire A315-53              | [4faa88a423](https://linux-hardware.org/?probe=4faa88a423) | Nov 01, 2021 |
| Acer          | Aspire A515-54G             | [807a8b23ce](https://linux-hardware.org/?probe=807a8b23ce) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8cdb34dbc8](https://linux-hardware.org/?probe=8cdb34dbc8) | Nov 01, 2021 |
| Standard      | AHV                         | [a960753588](https://linux-hardware.org/?probe=a960753588) | Oct 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [67a9ba5988](https://linux-hardware.org/?probe=67a9ba5988) | Oct 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9145964032](https://linux-hardware.org/?probe=9145964032) | Oct 30, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [34f2870a95](https://linux-hardware.org/?probe=34f2870a95) | Oct 30, 2021 |
| Acer          | Nitro AN515-54              | [bc9dc107d1](https://linux-hardware.org/?probe=bc9dc107d1) | Oct 30, 2021 |
| Acer          | Aspire A515-54G             | [7463facb20](https://linux-hardware.org/?probe=7463facb20) | Oct 29, 2021 |
| Acer          | Aspire A515-54G             | [270d4c1d21](https://linux-hardware.org/?probe=270d4c1d21) | Oct 28, 2021 |
| Dell          | Latitude E7240              | [18213a2e29](https://linux-hardware.org/?probe=18213a2e29) | Oct 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c4ffe3d08b](https://linux-hardware.org/?probe=c4ffe3d08b) | Oct 28, 2021 |
| Chuwi         | GemiBook                    | [f40d5fd5a7](https://linux-hardware.org/?probe=f40d5fd5a7) | Oct 27, 2021 |
| Acer          | Nitro AN515-55              | [2b3ef0e291](https://linux-hardware.org/?probe=2b3ef0e291) | Oct 26, 2021 |
| ASUSTek       | X540LA                      | [c947e5b1ea](https://linux-hardware.org/?probe=c947e5b1ea) | Oct 26, 2021 |
| Acer          | Nitro AN515-55              | [2d7ac3338d](https://linux-hardware.org/?probe=2d7ac3338d) | Oct 26, 2021 |
| Acer          | Aspire A315-53              | [e348a818bd](https://linux-hardware.org/?probe=e348a818bd) | Oct 26, 2021 |
| Acer          | Nitro AN515-43              | [1e8a2612aa](https://linux-hardware.org/?probe=1e8a2612aa) | Oct 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [905ef359d4](https://linux-hardware.org/?probe=905ef359d4) | Oct 24, 2021 |
| HP            | 650                         | [22e5d1948a](https://linux-hardware.org/?probe=22e5d1948a) | Oct 24, 2021 |
| Acer          | Aspire A315-34              | [f901b7640e](https://linux-hardware.org/?probe=f901b7640e) | Oct 24, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Endless/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Endless 3.7.8          | 257       | 7.78%   |
| Endless 3.9.5          | 149       | 4.51%   |
| Endless 3.9.1          | 125       | 3.78%   |
| Endless 3.8.7          | 113       | 3.42%   |
| Endless 3.8.6          | 111       | 3.36%   |
| Endless 3.8.0          | 111       | 3.36%   |
| Endless 3.8.4          | 106       | 3.21%   |
| Endless 3.9.4          | 105       | 3.18%   |
| Endless 3.9.3          | 104       | 3.15%   |
| Endless 3.8.3          | 82        | 2.48%   |
| Endless 3.9.0          | 81        | 2.45%   |
| Endless 3.5.8          | 66        | 2%      |
| Endless 3.7.4          | 65        | 1.97%   |
| Endless 3.7.5          | 64        | 1.94%   |
| Endless 3.8.1          | 62        | 1.88%   |
| Endless 3.8.5          | 61        | 1.85%   |
| Endless 3.7.6          | 59        | 1.79%   |
| Endless 3.7.7          | 58        | 1.75%   |
| Endless 4.0.2          | 56        | 1.69%   |
| Endless 3.9.7          | 53        | 1.6%    |
| Endless 3.3.19         | 53        | 1.6%    |
| Endless 3.9.2          | 51        | 1.54%   |
| Endless 3.6.2          | 47        | 1.42%   |
| Endless 3.9.3-nexthw1  | 46        | 1.39%   |
| Endless 3.6.4          | 46        | 1.39%   |
| Endless 3.3.19-nexthw1 | 44        | 1.33%   |
| Endless 3.5.7          | 43        | 1.3%    |
| Endless 4.0.13         | 40        | 1.21%   |
| Endless 3.7.3          | 40        | 1.21%   |
| Endless 3.6.1          | 39        | 1.18%   |
| Endless 3.6.0          | 38        | 1.15%   |
| Endless 4.0.6          | 34        | 1.03%   |
| Endless 3.6.3          | 34        | 1.03%   |
| Endless 3.3.20-nexthw1 | 32        | 0.97%   |
| Endless 4.0.14         | 31        | 0.94%   |
| Endless 3.5.4          | 31        | 0.94%   |
| Endless 3.4.2-nexthw1  | 31        | 0.94%   |
| Endless 6.0.5          | 28        | 0.85%   |
| Endless 4.0.0          | 28        | 0.85%   |
| Endless 3.9.6          | 28        | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Endless | 2796      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.8.0-14-generic  | 632       | 20.15%  |
| 5.4.0-19-generic  | 342       | 10.9%   |
| 5.3.0-28-generic  | 310       | 9.88%   |
| 5.11.0-35-generic | 289       | 9.21%   |
| 5.4.0-42-generic  | 220       | 7.01%   |
| 5.3.0-23-generic  | 126       | 4.02%   |
| 4.18.0-15-generic | 124       | 3.95%   |
| 6.5.0-10-generic  | 94        | 3%      |
| 4.15.0-15-generic | 81        | 2.58%   |
| 4.13.0-32-generic | 80        | 2.55%   |
| 5.0.0-25-generic  | 78        | 2.49%   |
| 5.15.0-47-generic | 77        | 2.45%   |
| 5.3.0-19-generic  | 65        | 2.07%   |
| 5.4.0-39-generic  | 61        | 1.94%   |
| 4.18.0-12-generic | 58        | 1.85%   |
| 5.3.0-12-generic  | 54        | 1.72%   |
| 4.16.0-4-generic  | 48        | 1.53%   |
| 5.0.0-20-generic  | 47        | 1.5%    |
| 5.11.0-12-generic | 46        | 1.47%   |
| 4.18.0-10-generic | 40        | 1.28%   |
| 5.0.0-17-generic  | 39        | 1.24%   |
| 5.0.0-15-generic  | 38        | 1.21%   |
| 4.18.0-11-generic | 36        | 1.15%   |
| 4.15.0-34-generic | 24        | 0.77%   |
| 5.1.0-2-generic   | 20        | 0.64%   |
| 4.15.0-12-generic | 18        | 0.57%   |
| 6.14.0-17-generic | 16        | 0.51%   |
| 5.4.0-7-generic   | 11        | 0.35%   |
| 5.10.0-10-generic | 10        | 0.32%   |
| 5.6.0-7-generic   | 9         | 0.29%   |
| 5.0.0-7-generic   | 9         | 0.29%   |
| 4.18.0-7-generic  | 8         | 0.26%   |
| 4.17.0-4-generic  | 8         | 0.26%   |
| 4.15.0-23-generic | 6         | 0.19%   |
| 4.13.0-19-generic | 4         | 0.13%   |
| 6.1.0-14-generic  | 2         | 0.06%   |
| 5.0.0-8-generic   | 2         | 0.06%   |
| 4.15.0-22-generic | 2         | 0.06%   |
| 4.15.0-33-generic | 1         | 0.03%   |
| 4.14.0-16-generic | 1         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.8.0   | 632       | 20.65%  |
| 5.4.0   | 602       | 19.67%  |
| 5.3.0   | 537       | 17.54%  |
| 5.11.0  | 335       | 10.94%  |
| 4.18.0  | 248       | 8.1%    |
| 5.0.0   | 205       | 6.7%    |
| 4.15.0  | 132       | 4.31%   |
| 6.5.0   | 94        | 3.07%   |
| 4.13.0  | 84        | 2.74%   |
| 5.15.0  | 77        | 2.52%   |
| 4.16.0  | 48        | 1.57%   |
| 5.1.0   | 20        | 0.65%   |
| 6.14.0  | 16        | 0.52%   |
| 5.10.0  | 10        | 0.33%   |
| 5.6.0   | 9         | 0.29%   |
| 4.17.0  | 8         | 0.26%   |
| 6.1.0   | 2         | 0.07%   |
| 4.14.0  | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.8     | 632       | 20.65%  |
| 5.4     | 602       | 19.67%  |
| 5.3     | 537       | 17.54%  |
| 5.11    | 335       | 10.94%  |
| 4.18    | 248       | 8.1%    |
| 5.0     | 205       | 6.7%    |
| 4.15    | 132       | 4.31%   |
| 6.5     | 94        | 3.07%   |
| 4.13    | 84        | 2.74%   |
| 5.15    | 77        | 2.52%   |
| 4.16    | 48        | 1.57%   |
| 5.1     | 20        | 0.65%   |
| 6.14    | 16        | 0.52%   |
| 5.10    | 10        | 0.33%   |
| 5.6     | 9         | 0.29%   |
| 4.17    | 8         | 0.26%   |
| 6.1     | 2         | 0.07%   |
| 4.14    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2796      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 2170      | 75.82%  |
| Unknown       | 567       | 19.81%  |
| Endless:GNOME | 125       | 4.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2126      | 74%     |
| Unknown | 569       | 19.81%  |
| Wayland | 178       | 6.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2795      | 99.96%  |
| GDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| pt_BR       | 862       | 30.22%  |
| Unknown     | 569       | 19.95%  |
| en_US       | 515       | 18.06%  |
| ru_RU       | 149       | 5.22%   |
| ro_RO       | 79        | 2.77%   |
| es_ES       | 72        | 2.52%   |
| de_DE       | 67        | 2.35%   |
| hu_HU       | 56        | 1.96%   |
| fr_FR       | 45        | 1.58%   |
| es_MX       | 40        | 1.4%    |
| it_IT       | 37        | 1.3%    |
| ru_UA       | 35        | 1.23%   |
| ru_RU.UTF_8 | 35        | 1.23%   |
| es_CO       | 33        | 1.16%   |
| en_GB       | 30        | 1.05%   |
| es_AR       | 25        | 0.88%   |
| pt_PT       | 18        | 0.63%   |
| uk_UA       | 16        | 0.56%   |
| tr_TR       | 16        | 0.56%   |
| pl_PL       | 16        | 0.56%   |
| bg_BG       | 13        | 0.46%   |
| sr_RS@latin | 10        | 0.35%   |
| sl_SI       | 7         | 0.25%   |
| hr_HR       | 7         | 0.25%   |
| el_GR       | 7         | 0.25%   |
| nl_NL       | 6         | 0.21%   |
| de_AT       | 6         | 0.21%   |
| id_ID       | 5         | 0.18%   |
| cs_CZ       | 5         | 0.18%   |
| sv_SE       | 4         | 0.14%   |
| en_IN       | 4         | 0.14%   |
| ca_ES       | 4         | 0.14%   |
| vi_VN       | 3         | 0.11%   |
| sk_SK       | 3         | 0.11%   |
| nl_BE       | 3         | 0.11%   |
| lt_LT       | 3         | 0.11%   |
| fi_FI       | 3         | 0.11%   |
| es_CL       | 3         | 0.11%   |
| en_CA       | 3         | 0.11%   |
| zh_TW       | 2         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2022      | 70.48%  |
| BIOS | 847       | 29.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2175      | 76.58%  |
| Unknown | 603       | 21.23%  |
| Tmpfs   | 61        | 2.15%   |
| Overlay | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2787      | 99.64%  |
| GPT     | 10        | 0.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2795      | 99.96%  |
| Yes       | 1         | 0.04%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2791      | 99.82%  |
| Yes       | 5         | 0.18%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| ASUSTek Computer      | 1078      | 38.56%  |
| Acer                  | 891       | 31.87%  |
| Hewlett-Packard       | 196       | 7.01%   |
| Lenovo                | 172       | 6.15%   |
| Dell                  | 138       | 4.94%   |
| Toshiba               | 56        | 2%      |
| Positivo              | 52        | 1.86%   |
| Samsung Electronics   | 34        | 1.22%   |
| Sony                  | 21        | 0.75%   |
| Apple                 | 11        | 0.39%   |
| Packard Bell          | 10        | 0.36%   |
| Intel                 | 9         | 0.32%   |
| LG Electronics        | 8         | 0.29%   |
| Digibras              | 8         | 0.29%   |
| Itautec               | 7         | 0.25%   |
| Unknown               | 6         | 0.21%   |
| MSI                   | 5         | 0.18%   |
| Google                | 5         | 0.18%   |
| Fujitsu Siemens       | 5         | 0.18%   |
| Semp Toshiba          | 4         | 0.14%   |
| Philco                | 4         | 0.14%   |
| Notebook              | 4         | 0.14%   |
| Medion                | 4         | 0.14%   |
| Gateway               | 4         | 0.14%   |
| eMachines             | 4         | 0.14%   |
| Chuwi                 | 4         | 0.14%   |
| Fujitsu               | 3         | 0.11%   |
| AMI                   | 3         | 0.11%   |
| OEM                   | 2         | 0.07%   |
| Multilaser            | 2         | 0.07%   |
| MODECOM               | 2         | 0.07%   |
| HUAWEI                | 2         | 0.07%   |
| Endless               | 2         | 0.07%   |
| Compal                | 2         | 0.07%   |
| Clevo                 | 2         | 0.07%   |
| VTEX                  | 1         | 0.04%   |
| TPVAOC                | 1         | 0.04%   |
| Standard              | 1         | 0.04%   |
| Positivo Bahia - VAIO | 1         | 0.04%   |
| Phoenix/SiS           | 1         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer Nitro AN515-54                        | 126       | 4.51%   |
| Acer Nitro AN515-44                        | 77        | 2.75%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 63        | 2.25%   |
| Acer Aspire A315-53                        | 56        | 2%      |
| Acer Aspire A315-34                        | 50        | 1.79%   |
| Acer Nitro AN517-51                        | 49        | 1.75%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 45        | 1.61%   |
| ASUS X541NA                                | 44        | 1.57%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 41        | 1.47%   |
| Acer Nitro AN515-43                        | 40        | 1.43%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 37        | 1.32%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA     | 34        | 1.22%   |
| ASUS VivoBook_ASUSLaptop X515JA_X515JA     | 30        | 1.07%   |
| ASUS X540NA                                | 28        | 1%      |
| Acer Nitro AN515-52                        | 28        | 1%      |
| ASUS ZenBook UX431DA_UM431DA               | 26        | 0.93%   |
| ASUS VivoBook_ASUSLaptop X515DA_X515DA     | 25        | 0.89%   |
| Acer Aspire A315-21                        | 22        | 0.79%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR       | 20        | 0.72%   |
| Acer Aspire A315-51                        | 20        | 0.72%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA     | 19        | 0.68%   |
| Acer Aspire A515-54G                       | 19        | 0.68%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 17        | 0.61%   |
| Acer Aspire A515-51G                       | 17        | 0.61%   |
| Acer Aspire A315-31                        | 17        | 0.61%   |
| HP Notebook                                | 16        | 0.57%   |
| Acer Aspire A315-54                        | 16        | 0.57%   |
| ASUS X541UAK                               | 15        | 0.54%   |
| Acer Aspire A315-54K                       | 15        | 0.54%   |
| Unknown                                    | 15        | 0.54%   |
| Positivo S14CT01                           | 14        | 0.5%    |
| ASUS VivoBook_ASUSLaptop X570ZD_X570ZD     | 14        | 0.5%    |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA    | 14        | 0.5%    |
| Acer Aspire A517-51G                       | 13        | 0.46%   |
| Acer Aspire A515-51                        | 13        | 0.46%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA     | 12        | 0.43%   |
| ASUS VivoBook 15_ASUS Laptop X507MA_X507MA | 12        | 0.43%   |
| ASUS VivoBook_ASUSLaptop X513EAN_X513EAN   | 11        | 0.39%   |
| Acer Nitro AN515-51                        | 11        | 0.39%   |
| Acer Extensa 2540                          | 11        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| ASUS VivoBook         | 706       | 25.25%  |
| Acer Aspire           | 456       | 16.31%  |
| Acer Nitro            | 340       | 12.16%  |
| Lenovo IdeaPad        | 68        | 2.43%   |
| Dell Inspiron         | 65        | 2.32%   |
| HP Pavilion           | 51        | 1.82%   |
| Toshiba Satellite     | 49        | 1.75%   |
| Dell Latitude         | 49        | 1.75%   |
| Lenovo ThinkPad       | 47        | 1.68%   |
| ASUS X541NA           | 44        | 1.57%   |
| ASUS ZenBook          | 38        | 1.36%   |
| ASUS X540NA           | 28        | 1%      |
| Acer TravelMate       | 28        | 1%      |
| HP ProBook            | 23        | 0.82%   |
| Acer Swift            | 22        | 0.79%   |
| HP Laptop             | 21        | 0.75%   |
| Acer Extensa          | 18        | 0.64%   |
| Acer Predator         | 17        | 0.61%   |
| HP Notebook           | 16        | 0.57%   |
| HP EliteBook          | 15        | 0.54%   |
| ASUS X541UAK          | 15        | 0.54%   |
| Unknown               | 15        | 0.54%   |
| Positivo S14CT01      | 14        | 0.5%    |
| Dell Vostro           | 14        | 0.5%    |
| ASUS ASUS             | 12        | 0.43%   |
| Positivo Mobile       | 10        | 0.36%   |
| Packard Bell EasyNote | 10        | 0.36%   |
| ASUS X540LA           | 10        | 0.36%   |
| ASUS ASUSPRO          | 10        | 0.36%   |
| HP 255                | 9         | 0.32%   |
| HP Compaq             | 8         | 0.29%   |
| Itautec Infoway       | 7         | 0.25%   |
| HP 250                | 7         | 0.25%   |
| HP 2000               | 7         | 0.25%   |
| ASUS Z550SA           | 7         | 0.25%   |
| ASUS X542UN           | 7         | 0.25%   |
| ASUS X540NV           | 7         | 0.25%   |
| ASUS TUF              | 7         | 0.25%   |
| Lenovo Yoga           | 6         | 0.21%   |
| Digibras NH4CU53      | 6         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 592       | 21.17%  |
| 2018    | 542       | 19.38%  |
| 2017    | 382       | 13.66%  |
| 2020    | 203       | 7.26%   |
| 2016    | 146       | 5.22%   |
| 2021    | 136       | 4.86%   |
| 2011    | 126       | 4.51%   |
| 2013    | 106       | 3.79%   |
| 2012    | 97        | 3.47%   |
| 2015    | 94        | 3.36%   |
| 2010    | 91        | 3.25%   |
| 2014    | 82        | 2.93%   |
| 2008    | 79        | 2.83%   |
| 2009    | 69        | 2.47%   |
| 2007    | 32        | 1.14%   |
| 2022    | 8         | 0.29%   |
| 2006    | 7         | 0.25%   |
| 2024    | 1         | 0.04%   |
| 2023    | 1         | 0.04%   |
| 2004    | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2796      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2032      | 71.9%   |
| Enabled  | 794       | 28.1%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2791      | 99.82%  |
| Yes  | 5         | 0.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 1158      | 41.21%  |
| 4.01-8.0    | 1092      | 38.86%  |
| 8.01-16.0   | 207       | 7.37%   |
| 1.01-2.0    | 182       | 6.48%   |
| 16.01-24.0  | 115       | 4.09%   |
| 2.01-3.0    | 33        | 1.17%   |
| 0.51-1.0    | 8         | 0.28%   |
| 24.01-32.0  | 7         | 0.25%   |
| 32.01-64.0  | 6         | 0.21%   |
| 64.01-256.0 | 1         | 0.04%   |
| Unknown     | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 1545      | 49.58%  |
| 2.01-3.0  | 771       | 24.74%  |
| 0.51-1.0  | 446       | 14.31%  |
| 3.01-4.0  | 226       | 7.25%   |
| 4.01-8.0  | 122       | 3.92%   |
| 8.01-16.0 | 3         | 0.1%    |
| 0.01-0.5  | 2         | 0.06%   |
| Unknown   | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2245      | 79.3%   |
| 2      | 561       | 19.82%  |
| 3      | 19        | 0.67%   |
| 0      | 6         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1994      | 71.16%  |
| Yes       | 808       | 28.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1928      | 68.71%  |
| No        | 878       | 31.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2730      | 97.57%  |
| No        | 68        | 2.43%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2345      | 83.36%  |
| No        | 468       | 16.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| Brazil          | 950       | 33.78%  |
| Russia          | 220       | 7.82%   |
| Romania         | 213       | 7.57%   |
| USA             | 174       | 6.19%   |
| Germany         | 110       | 3.91%   |
| Spain           | 107       | 3.81%   |
| Ukraine         | 99        | 3.52%   |
| Hungary         | 77        | 2.74%   |
| Colombia        | 68        | 2.42%   |
| France          | 45        | 1.6%    |
| Italy           | 43        | 1.53%   |
| India           | 37        | 1.32%   |
| Argentina       | 37        | 1.32%   |
| Belarus         | 36        | 1.28%   |
| Portugal        | 34        | 1.21%   |
| UK              | 31        | 1.1%    |
| Serbia          | 31        | 1.1%    |
| Poland          | 25        | 0.89%   |
| Bulgaria        | 25        | 0.89%   |
| Indonesia       | 22        | 0.78%   |
| Croatia         | 22        | 0.78%   |
| Canada          | 20        | 0.71%   |
| Turkey          | 18        | 0.64%   |
| Kazakhstan      | 18        | 0.64%   |
| Philippines     | 17        | 0.6%    |
| Iran            | 15        | 0.53%   |
| Greece          | 15        | 0.53%   |
| Georgia         | 14        | 0.5%    |
| Saudi Arabia    | 13        | 0.46%   |
| Australia       | 13        | 0.46%   |
| Mexico          | 12        | 0.43%   |
| Sweden          | 11        | 0.39%   |
| Slovenia        | 11        | 0.39%   |
| Kenya           | 10        | 0.36%   |
| South Africa    | 9         | 0.32%   |
| Netherlands     | 9         | 0.32%   |
| Egypt           | 9         | 0.32%   |
| Austria         | 9         | 0.32%   |
| North Macedonia | 8         | 0.28%   |
| Israel          | 8         | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Sao Paulo        | 114       | 3.76%   |
| Moscow           | 73        | 2.41%   |
| Bucharest        | 72        | 2.38%   |
| Rio de Janeiro   | 52        | 1.72%   |
| Budapest         | 36        | 1.19%   |
| Brasília        | 34        | 1.12%   |
| Kyiv             | 33        | 1.09%   |
| Bogotá          | 27        | 0.89%   |
| Curitiba         | 26        | 0.86%   |
| St Petersburg    | 24        | 0.79%   |
| Belgrade         | 22        | 0.73%   |
| Cluj-Napoca      | 21        | 0.69%   |
| Fortaleza        | 20        | 0.66%   |
| Belo Horizonte   | 20        | 0.66%   |
| Salvador         | 19        | 0.63%   |
| Porto Alegre     | 19        | 0.63%   |
| Minsk            | 14        | 0.46%   |
| Sofia            | 13        | 0.43%   |
| Recife           | 12        | 0.4%    |
| Niterói         | 12        | 0.4%    |
| Iasi             | 12        | 0.4%    |
| Campinas         | 12        | 0.4%    |
| Santo André     | 11        | 0.36%   |
| Osasco           | 11        | 0.36%   |
| Madrid           | 11        | 0.36%   |
| Barcelona        | 11        | 0.36%   |
| Warsaw           | 10        | 0.33%   |
| Tehran           | 10        | 0.33%   |
| Popesti-Leordeni | 10        | 0.33%   |
| Paris            | 10        | 0.33%   |
| Guarulhos        | 10        | 0.33%   |
| Nairobi          | 9         | 0.3%    |
| Medellín        | 9         | 0.3%    |
| Lisbon           | 9         | 0.3%    |
| Jakarta          | 9         | 0.3%    |
| Campo Grande     | 9         | 0.3%    |
| Buenos Aires     | 9         | 0.3%    |
| Sao Carlos       | 8         | 0.26%   |
| Ploieşti        | 8         | 0.26%   |
| Maringá         | 8         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 619       | 749    | 18.64%  |
| Seagate                     | 458       | 588    | 13.8%   |
| Toshiba                     | 355       | 451    | 10.69%  |
| Intel                       | 298       | 365    | 8.98%   |
| SanDisk                     | 283       | 334    | 8.52%   |
| Kingston                    | 223       | 292    | 6.72%   |
| Unknown                     | 189       | 233    | 5.69%   |
| Samsung Electronics         | 137       | 168    | 4.13%   |
| SK hynix                    | 125       | 156    | 3.77%   |
| ADATA Technology            | 99        | 107    | 2.98%   |
| HGST                        | 92        | 115    | 2.77%   |
| A-DATA Technology           | 89        | 101    | 2.68%   |
| Micron Technology           | 58        | 83     | 1.75%   |
| Hitachi                     | 58        | 64     | 1.75%   |
| Crucial                     | 25        | 27     | 0.75%   |
| China                       | 22        | 25     | 0.66%   |
| Silicon Motion              | 13        | 13     | 0.39%   |
| Fujitsu                     | 13        | 13     | 0.39%   |
| LITEON                      | 10        | 11     | 0.3%    |
| Phison                      | 9         | 9      | 0.27%   |
| Apple                       | 9         | 9      | 0.27%   |
| OCZ                         | 7         | 7      | 0.21%   |
| Kingston Technology Company | 6         | 7      | 0.18%   |
| Transcend                   | 5         | 7      | 0.15%   |
| PNY                         | 5         | 6      | 0.15%   |
| Phison Electronics          | 5         | 5      | 0.15%   |
| SPCC                        | 4         | 5      | 0.12%   |
| Realtek Semiconductor       | 4         | 5      | 0.12%   |
| Patriot                     | 4         | 4      | 0.12%   |
| Netac                       | 4         | 4      | 0.12%   |
| LITEONIT                    | 4         | 5      | 0.12%   |
| Intenso                     | 4         | 4      | 0.12%   |
| Win Memory                  | 3         | 4      | 0.09%   |
| KIOXIA                      | 3         | 4      | 0.09%   |
| KingFast                    | 3         | 5      | 0.09%   |
| JMicron Technology          | 3         | 3      | 0.09%   |
| Hewlett-Packard             | 3         | 13     | 0.09%   |
| GOODRAM                     | 3         | 3      | 0.09%   |
| Verbatim                    | 2         | 2      | 0.06%   |
| Union Memory                | 2         | 2      | 0.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB              | 371       | 11.06%  |
| Seagate ST1000LM035-1RK172 1TB        | 184       | 5.49%   |
| Toshiba MQ01ABF050 500GB              | 135       | 4.03%   |
| Intel NVMe SSD Drive 512GB            | 122       | 3.64%   |
| Toshiba MQ04ABF100 1TB                | 114       | 3.4%    |
| Unknown MMC Card  32GB                | 80        | 2.39%   |
| Intel NVMe SSD Drive 256GB            | 74        | 2.21%   |
| SanDisk NVMe SSD Drive 512GB          | 70        | 2.09%   |
| A-DATA IM2S3338-128GD2 128GB SSD      | 70        | 2.09%   |
| Kingston RBUSC180DS37256GJ 256GB SSD  | 69        | 2.06%   |
| Intel SSDPEKKW256G7 256GB             | 69        | 2.06%   |
| ADATA SM2P32A8-256GC1 256GB           | 60        | 1.79%   |
| Seagate ST500LT012-1DG142 500GB       | 49        | 1.46%   |
| Unknown MMC Card  64GB                | 40        | 1.19%   |
| Toshiba MQ01ABD100 1TB                | 32        | 0.95%   |
| WDC WD5000LPCX-21VHAT0 500GB          | 31        | 0.92%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB | 31        | 0.92%   |
| Seagate ST500LM030-1RK17D 500GB       | 30        | 0.89%   |
| SanDisk NVMe SSD Drive 256GB          | 29        | 0.86%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD   | 28        | 0.83%   |
| SK hynix NVMe SSD Drive 256GB         | 27        | 0.81%   |
| SanDisk SD9SB8W256G1002 256GB SSD     | 27        | 0.81%   |
| Kingston NVMe SSD Drive 256GB         | 26        | 0.78%   |
| Kingston SA400S37240G 240GB SSD       | 24        | 0.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 23        | 0.69%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 22        | 0.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 22        | 0.66%   |
| SK hynix NVMe SSD Drive 512GB         | 21        | 0.63%   |
| ADATA NVMe SSD Drive 128GB            | 21        | 0.63%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 20        | 0.6%    |
| HGST HTS545050B7E660 500GB            | 20        | 0.6%    |
| Unknown MMC Card  16GB                | 17        | 0.51%   |
| Samsung NVMe SSD Drive 256GB          | 17        | 0.51%   |
| HGST HTS541010B7E610 1TB              | 17        | 0.51%   |
| SanDisk SD9SN8W256G1102 256GB SSD     | 16        | 0.48%   |
| WDC WD5000LPCX-80VHAT1 500GB          | 15        | 0.45%   |
| ADATA NVMe SSD Drive 256GB            | 15        | 0.45%   |
| Kingston RBUSNS8180DS3256GJ 256GB SSD | 14        | 0.42%   |
| Seagate ST9500325AS 500GB             | 13        | 0.39%   |
| Seagate ST2000LM007-1R8174 2TB        | 12        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 597       | 710    | 36.97%  |
| Seagate             | 457       | 586    | 28.3%   |
| Toshiba             | 344       | 438    | 21.3%   |
| HGST                | 92        | 115    | 5.7%    |
| Hitachi             | 58        | 64     | 3.59%   |
| Samsung Electronics | 33        | 37     | 2.04%   |
| Fujitsu             | 13        | 13     | 0.8%    |
| Unknown             | 9         | 10     | 0.56%   |
| Intenso             | 3         | 3      | 0.19%   |
| Apple               | 3         | 3      | 0.19%   |
| JMicron Technology  | 2         | 2      | 0.12%   |
| USB3.0              | 1         | 1      | 0.06%   |
| TO Exter            | 1         | 3      | 0.06%   |
| StoreJet            | 1         | 2      | 0.06%   |
| HGST HTS            | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 185       | 248    | 23.75%  |
| SanDisk             | 146       | 191    | 18.74%  |
| A-DATA Technology   | 89        | 101    | 11.42%  |
| Samsung Electronics | 61        | 78     | 7.83%   |
| SK hynix            | 56        | 79     | 7.19%   |
| Micron Technology   | 47        | 72     | 6.03%   |
| Crucial             | 25        | 27     | 3.21%   |
| WDC                 | 22        | 35     | 2.82%   |
| China               | 22        | 25     | 2.82%   |
| LITEON              | 10        | 11     | 1.28%   |
| Intel               | 9         | 17     | 1.16%   |
| Toshiba             | 7         | 7      | 0.9%    |
| OCZ                 | 7         | 7      | 0.9%    |
| Unknown             | 6         | 7      | 0.77%   |
| Apple               | 6         | 6      | 0.77%   |
| Transcend           | 5         | 7      | 0.64%   |
| PNY                 | 5         | 6      | 0.64%   |
| SPCC                | 4         | 5      | 0.51%   |
| Patriot             | 4         | 4      | 0.51%   |
| Netac               | 4         | 4      | 0.51%   |
| LITEONIT            | 4         | 5      | 0.51%   |
| Win Memory          | 3         | 4      | 0.39%   |
| Hewlett-Packard     | 3         | 13     | 0.39%   |
| GOODRAM             | 3         | 3      | 0.39%   |
| Verbatim            | 2         | 2      | 0.26%   |
| Team                | 2         | 2      | 0.26%   |
| KingSpec            | 2         | 2      | 0.26%   |
| Kingmax             | 2         | 2      | 0.26%   |
| KingDian            | 2         | 3      | 0.26%   |
| FORESEE             | 2         | 3      | 0.26%   |
| Dell                | 2         | 2      | 0.26%   |
| Corsair             | 2         | 2      | 0.26%   |
| Zheino              | 1         | 1      | 0.13%   |
| XrayDisk            | 1         | 1      | 0.13%   |
| Wellcomm            | 1         | 1      | 0.13%   |
| V7                  | 1         | 1      | 0.13%   |
| Union Memory        | 1         | 1      | 0.13%   |
| Timetec             | 1         | 2      | 0.13%   |
| Teclast             | 1         | 1      | 0.13%   |
| StoreJet            | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1597      | 1988   | 48.79%  |
| SSD     | 754       | 1020   | 23.04%  |
| NVMe    | 742       | 851    | 22.67%  |
| MMC     | 165       | 206    | 5.04%   |
| Unknown | 15        | 21     | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2139      | 2979   | 69.22%  |
| NVMe | 741       | 849    | 23.98%  |
| MMC  | 165       | 206    | 5.34%   |
| SAS  | 45        | 52     | 1.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1393      | 1863   | 59.94%  |
| 0.51-1.0   | 891       | 1089   | 38.34%  |
| 1.01-2.0   | 37        | 53     | 1.59%   |
| 3.01-4.0   | 2         | 2      | 0.09%   |
| 4.01-10.0  | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 868       | 30.36%  |
| 251-500        | 771       | 26.97%  |
| 501-1000       | 681       | 23.82%  |
| 21-50          | 192       | 6.72%   |
| 51-100         | 131       | 4.58%   |
| 1-20           | 114       | 3.99%   |
| 1001-2000      | 61        | 2.13%   |
| 2001-3000      | 23        | 0.8%    |
| Unknown        | 15        | 0.52%   |
| More than 3000 | 3         | 0.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 1503      | 50.33%  |
| 1-20           | 643       | 21.53%  |
| 51-100         | 452       | 15.14%  |
| 101-250        | 224       | 7.5%    |
| 251-500        | 87        | 2.91%   |
| 501-1000       | 38        | 1.27%   |
| 1001-2000      | 19        | 0.64%   |
| Unknown        | 15        | 0.5%    |
| 2001-3000      | 4         | 0.13%   |
| More than 3000 | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZVPW128HEGM-00000 128GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 100%    |

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
| Detected | 2787      | 4073   | 99.57%  |
| Works    | 11        | 12     | 0.39%   |
| Malfunc  | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2178      | 69.1%   |
| AMD                              | 487       | 15.45%  |
| SanDisk                          | 138       | 4.38%   |
| ADATA Technology                 | 107       | 3.39%   |
| SK hynix                         | 69        | 2.19%   |
| Samsung Electronics              | 48        | 1.52%   |
| Kingston Technology Company      | 43        | 1.36%   |
| Phison Electronics               | 14        | 0.44%   |
| Silicon Motion                   | 13        | 0.41%   |
| Micron Technology                | 11        | 0.35%   |
| Silicon Integrated Systems [SiS] | 10        | 0.32%   |
| Nvidia                           | 9         | 0.29%   |
| Toshiba America Info Systems     | 6         | 0.19%   |
| Realtek Semiconductor            | 5         | 0.16%   |
| KIOXIA                           | 3         | 0.1%    |
| VIA Technologies                 | 2         | 0.06%   |
| Union Memory (Shenzhen)          | 2         | 0.06%   |
| Lite-On Technology               | 2         | 0.06%   |
| Solid State Storage Technology   | 1         | 0.03%   |
| Silicon Image                    | 1         | 0.03%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Marvell Technology Group         | 1         | 0.03%   |
| JMicron Technology               | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 479       | 13.25%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 444       | 12.28%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 425       | 11.76%  |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 264       | 7.3%    |
| Intel PROSet/Wireless WiFi Software extension                                    | 257       | 7.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 154       | 4.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 116       | 3.21%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 102       | 2.82%   |
| Intel Volume Management Device NVMe RAID Controller                              | 90        | 2.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 90        | 2.49%   |
| Intel Tiger Lake-LP SATA Controller                                              | 89        | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 78        | 2.16%   |
| ADATA SM2P32A8 NVMe SSD (DRAM-less)                                              | 64        | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 51        | 1.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 46        | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 46        | 1.27%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 43        | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 40        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 40        | 1.11%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                       | 40        | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 39        | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 34        | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 32        | 0.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 30        | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 29        | 0.8%    |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 28        | 0.77%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD [E8]                              | 27        | 0.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 23        | 0.64%   |
| Intel SSD 660P Series                                                            | 23        | 0.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 21        | 0.58%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 20        | 0.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 19        | 0.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 15        | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 13        | 0.36%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 13        | 0.36%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 0.36%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                | 12        | 0.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 0.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 11        | 0.3%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 10        | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2141      | 59.96%  |
| NVMe | 742       | 20.78%  |
| RAID | 572       | 16.02%  |
| IDE  | 116       | 3.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2286      | 81.76%  |
| AMD    | 510       | 18.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 138       | 4.94%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 127       | 4.54%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 94        | 3.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 90        | 3.22%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 81        | 2.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 72        | 2.58%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 65        | 2.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 61        | 2.18%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 58        | 2.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 57        | 2.04%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 46        | 1.65%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 44        | 1.57%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 42        | 1.5%    |
| Intel Core i3-8130U CPU @ 2.20GHz             | 42        | 1.5%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 41        | 1.47%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 36        | 1.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 35        | 1.25%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 35        | 1.25%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 33        | 1.18%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 31        | 1.11%   |
| Intel Pentium CPU 4417U @ 2.30GHz             | 29        | 1.04%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 29        | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 29        | 1.04%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 29        | 1.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 28        | 1%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 28        | 1%      |
| Intel Celeron CPU N3060 @ 1.60GHz             | 26        | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 25        | 0.89%   |
| Intel Celeron N4000C CPU @ 1.10GHz            | 25        | 0.89%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 24        | 0.86%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 23        | 0.82%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 23        | 0.82%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 23        | 0.82%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 22        | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 22        | 0.79%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 21        | 0.75%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 20        | 0.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 19        | 0.68%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 19        | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 18        | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 583       | 20.85%  |
| Intel Celeron                        | 461       | 16.49%  |
| Intel Core i3                        | 443       | 15.84%  |
| Intel Core i7                        | 279       | 9.98%   |
| AMD Ryzen 5                          | 137       | 4.9%    |
| Other                                | 132       | 4.72%   |
| Intel Pentium                        | 124       | 4.43%   |
| AMD Ryzen 7                          | 112       | 4.01%   |
| Intel Core 2 Duo                     | 91        | 3.25%   |
| Intel Atom                           | 87        | 3.11%   |
| Intel Pentium Silver                 | 46        | 1.65%   |
| AMD A6                               | 42        | 1.5%    |
| AMD Ryzen 3                          | 35        | 1.25%   |
| Intel Pentium Dual-Core              | 31        | 1.11%   |
| AMD A4                               | 24        | 0.86%   |
| AMD E                                | 19        | 0.68%   |
| AMD E2                               | 18        | 0.64%   |
| Intel Pentium Dual                   | 15        | 0.54%   |
| AMD E1                               | 13        | 0.46%   |
| AMD A8                               | 12        | 0.43%   |
| Intel Genuine                        | 10        | 0.36%   |
| AMD Athlon                           | 8         | 0.29%   |
| AMD C-70                             | 6         | 0.21%   |
| AMD A12                              | 6         | 0.21%   |
| AMD Turion 64 X2 Mobile              | 5         | 0.18%   |
| AMD A10                              | 5         | 0.18%   |
| Intel Core 2                         | 4         | 0.14%   |
| AMD Mobile Sempron                   | 4         | 0.14%   |
| AMD FX                               | 4         | 0.14%   |
| Intel Celeron Dual-Core              | 3         | 0.11%   |
| AMD V120                             | 3         | 0.11%   |
| Intel Pentium Gold                   | 2         | 0.07%   |
| Intel Core M                         | 2         | 0.07%   |
| AMD Turion X2 Dual-Core Mobile       | 2         | 0.07%   |
| AMD Turion II Ultra Dual-Core Mobile | 2         | 0.07%   |
| AMD Phenom II                        | 2         | 0.07%   |
| AMD C-50                             | 2         | 0.07%   |
| AMD Athlon II Dual-Core              | 2         | 0.07%   |
| AMD Athlon II                        | 2         | 0.07%   |
| AMD Athlon 64 X2                     | 2         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1588      | 56.8%   |
| 4      | 979       | 35.01%  |
| 6      | 114       | 4.08%   |
| 8      | 65        | 2.32%   |
| 1      | 47        | 1.68%   |
| 10     | 2         | 0.07%   |
| 3      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2796      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1753      | 62.7%   |
| 1      | 1043      | 37.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2277      | 80.18%  |
| Unknown        | 563       | 19.82%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 374       | 13.06%  |
| 0x706a1    | 187       | 6.53%   |
| 0x906ea    | 186       | 6.49%   |
| 0x806ea    | 180       | 6.28%   |
| 0x806e9    | 147       | 5.13%   |
| 0x506c9    | 129       | 4.5%    |
| 0x406e3    | 109       | 3.81%   |
| 0x206a7    | 108       | 3.77%   |
| 0x806ec    | 104       | 3.63%   |
| 0x08108109 | 96        | 3.35%   |
| 0x806c1    | 89        | 3.11%   |
| 0x306a9    | 84        | 2.93%   |
| 0x08600103 | 78        | 2.72%   |
| 0x706e5    | 76        | 2.65%   |
| 0x406c4    | 66        | 2.3%    |
| 0x1067a    | 66        | 2.3%    |
| 0x06006705 | 63        | 2.2%    |
| 0x08108102 | 49        | 1.71%   |
| 0x706a8    | 47        | 1.64%   |
| 0x906ed    | 46        | 1.61%   |
| 0x30678    | 44        | 1.54%   |
| 0x906e9    | 42        | 1.47%   |
| 0x40651    | 42        | 1.47%   |
| 0x306d4    | 37        | 1.29%   |
| 0x20655    | 36        | 1.26%   |
| 0x6fd      | 35        | 1.22%   |
| 0x806eb    | 34        | 1.19%   |
| 0x406c3    | 31        | 1.08%   |
| 0x0810100b | 26        | 0.91%   |
| 0x05000119 | 26        | 0.91%   |
| 0x306c3    | 21        | 0.73%   |
| 0x08101007 | 21        | 0.73%   |
| 0x06006704 | 19        | 0.66%   |
| 0x106ca    | 18        | 0.63%   |
| 0x10676    | 14        | 0.49%   |
| 0x07030105 | 13        | 0.45%   |
| 0x20652    | 12        | 0.42%   |
| 0x6fb      | 9         | 0.31%   |
| 0x010000c8 | 8         | 0.28%   |
| 0xa0652    | 7         | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 784       | 28.04%  |
| Goldmont plus    | 268       | 9.59%   |
| Silvermont       | 158       | 5.65%   |
| Zen+             | 155       | 5.54%   |
| Goldmont         | 154       | 5.51%   |
| SandyBridge      | 128       | 4.58%   |
| Skylake          | 127       | 4.54%   |
| Penryn           | 105       | 3.76%   |
| Excavator        | 103       | 3.68%   |
| TigerLake        | 94        | 3.36%   |
| IceLake          | 93        | 3.33%   |
| IvyBridge        | 92        | 3.29%   |
| Zen 2            | 85        | 3.04%   |
| Haswell          | 75        | 2.68%   |
| Core             | 62        | 2.22%   |
| Westmere         | 58        | 2.07%   |
| Zen              | 48        | 1.72%   |
| Broadwell        | 45        | 1.61%   |
| Bobcat           | 36        | 1.29%   |
| Bonnell          | 23        | 0.82%   |
| Puma             | 20        | 0.72%   |
| K8 Hammer        | 15        | 0.54%   |
| K10              | 15        | 0.54%   |
| Jaguar           | 10        | 0.36%   |
| Piledriver       | 9         | 0.32%   |
| CometLake        | 9         | 0.32%   |
| Unknown          | 6         | 0.21%   |
| Nehalem          | 5         | 0.18%   |
| Steamroller      | 3         | 0.11%   |
| K8 & K10 hybrid  | 3         | 0.11%   |
| K10 Llano        | 3         | 0.11%   |
| Alderlake Hybrid | 3         | 0.11%   |
| Zen 3            | 1         | 0.04%   |
| Tremont          | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2199      | 60.98%  |
| Nvidia                           | 826       | 22.91%  |
| AMD                              | 569       | 15.78%  |
| Silicon Integrated Systems [SiS] | 10        | 0.28%   |
| VIA Technologies                 | 2         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 296       | 8.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 234       | 6.35%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 222       | 6.02%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 157       | 4.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 156       | 4.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 121       | 3.28%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 119       | 3.23%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 117       | 3.17%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 114       | 3.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 103       | 2.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 90        | 2.44%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 90        | 2.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 89        | 2.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 85        | 2.31%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 84        | 2.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 79        | 2.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 76        | 2.06%   |
| Nvidia GM108M [GeForce MX110]                                                            | 74        | 2.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 63        | 1.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 57        | 1.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 55        | 1.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 51        | 1.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 48        | 1.3%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 47        | 1.28%   |
| Nvidia GP108M [GeForce MX150]                                                            | 46        | 1.25%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 46        | 1.25%   |
| Intel HD Graphics 620                                                                    | 44        | 1.19%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 42        | 1.14%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 39        | 1.06%   |
| Nvidia GM108M [GeForce MX130]                                                            | 38        | 1.03%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 37        | 1%      |
| Intel Apollo Lake [HD Graphics 505]                                                      | 37        | 1%      |
| Intel Kaby Lake-U GT1 [HD Graphics 610]                                                  | 32        | 0.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 30        | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 30        | 0.81%   |
| Nvidia GP108M [GeForce MX250]                                                            | 24        | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 21        | 0.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 0.57%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 19        | 0.52%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 19        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1534      | 54.86%  |
| Intel + Nvidia | 627       | 22.42%  |
| 1 x AMD        | 340       | 12.16%  |
| AMD + Nvidia   | 145       | 5.19%   |
| 1 x Nvidia     | 53        | 1.9%    |
| 2 x AMD        | 47        | 1.68%   |
| Intel + AMD    | 37        | 1.32%   |
| 1 x SiS        | 10        | 0.36%   |
| 1 x VIA        | 2         | 0.07%   |
| Other          | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2270      | 81.01%  |
| Proprietary | 518       | 18.49%  |
| Unknown     | 14        | 0.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2025      | 71.5%   |
| 0.01-0.5   | 302       | 10.66%  |
| 1.01-2.0   | 220       | 7.77%   |
| 3.01-4.0   | 183       | 6.46%   |
| 0.51-1.0   | 102       | 3.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 705       | 25.55%  |
| Chimei Innolux          | 595       | 21.57%  |
| AU Optronics            | 577       | 20.91%  |
| LG Display              | 322       | 11.67%  |
| Samsung Electronics     | 169       | 6.13%   |
| PANDA                   | 127       | 4.6%    |
| Chi Mei Optoelectronics | 45        | 1.63%   |
| LG Philips              | 25        | 0.91%   |
| Goldstar                | 20        | 0.72%   |
| InfoVision              | 18        | 0.65%   |
| Lenovo                  | 15        | 0.54%   |
| Dell                    | 13        | 0.47%   |
| Apple                   | 11        | 0.4%    |
| Sony                    | 10        | 0.36%   |
| Philips                 | 8         | 0.29%   |
| KDC                     | 8         | 0.29%   |
| HannStar                | 8         | 0.29%   |
| CPT                     | 7         | 0.25%   |
| AOC                     | 6         | 0.22%   |
| Acer                    | 6         | 0.22%   |
| InnoLux Display         | 5         | 0.18%   |
| Sharp                   | 4         | 0.14%   |
| BenQ                    | 4         | 0.14%   |
| Ancor Communications    | 4         | 0.14%   |
| Vestel Elektronik       | 3         | 0.11%   |
| Toshiba                 | 3         | 0.11%   |
| SLD                     | 3         | 0.11%   |
| RTK                     | 3         | 0.11%   |
| Panasonic               | 3         | 0.11%   |
| Hewlett-Packard         | 3         | 0.11%   |
| STA                     | 2         | 0.07%   |
| SKY                     | 2         | 0.07%   |
| MTD                     | 2         | 0.07%   |
| Hitachi                 | 2         | 0.07%   |
| Vizio                   | 1         | 0.04%   |
| Unknown                 | 1         | 0.04%   |
| Seiki                   | 1         | 0.04%   |
| RKS                     | 1         | 0.04%   |
| Optoma                  | 1         | 0.04%   |
| OEM                     | 1         | 0.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 107       | 3.87%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 105       | 3.8%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 105       | 3.8%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 91        | 3.29%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 87        | 3.15%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 78        | 2.82%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 72        | 2.61%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 59        | 2.14%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 53        | 1.92%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 50        | 1.81%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 49        | 1.77%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 46        | 1.66%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 45        | 1.63%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 43        | 1.56%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 43        | 1.56%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 42        | 1.52%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                 | 41        | 1.48%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 40        | 1.45%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 33        | 1.19%   |
| BOE LCD Monitor BOE0839 1920x1080 382x215mm 17.3-inch                | 32        | 1.16%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch              | 29        | 1.05%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 29        | 1.05%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                | 26        | 0.94%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch              | 23        | 0.83%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 23        | 0.83%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 22        | 0.8%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 19        | 0.69%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch         | 17        | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 17        | 0.62%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 17        | 0.62%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch         | 14        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 14        | 0.51%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 14        | 0.51%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 13        | 0.47%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 12        | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 12        | 0.43%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 12        | 0.43%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch              | 11        | 0.4%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 10        | 0.36%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch      | 9         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1299      | 47.6%   |
| 1920x1080 (FHD)    | 1152      | 42.21%  |
| 1280x800 (WXGA)    | 81        | 2.97%   |
| 1600x900 (HD+)     | 78        | 2.86%   |
| 3840x2160 (4K)     | 19        | 0.7%    |
| 1440x900 (WXGA+)   | 19        | 0.7%    |
| 1920x1200 (WUXGA)  | 17        | 0.62%   |
| 1024x600           | 11        | 0.4%    |
| 1920x540           | 8         | 0.29%   |
| 1360x768           | 8         | 0.29%   |
| 1280x1024 (SXGA)   | 6         | 0.22%   |
| 3200x1800 (QHD+)   | 5         | 0.18%   |
| 2560x1080          | 5         | 0.18%   |
| 1680x1050 (WSXGA+) | 5         | 0.18%   |
| 2560x1440 (QHD)    | 4         | 0.15%   |
| 2160x1440          | 2         | 0.07%   |
| 1280x720 (HD)      | 2         | 0.07%   |
| 1024x768 (XGA)     | 2         | 0.07%   |
| 3456x2160          | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2880x1800          | 1         | 0.04%   |
| 2288x1287          | 1         | 0.04%   |
| 1680x945           | 1         | 0.04%   |
| 1400x1050          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1843      | 66.78%  |
| 13      | 250       | 9.06%   |
| 14      | 224       | 8.12%   |
| 17      | 191       | 6.92%   |
| 11      | 72        | 2.61%   |
| 23      | 22        | 0.8%    |
| 12      | 22        | 0.8%    |
| 24      | 15        | 0.54%   |
| 21      | 15        | 0.54%   |
| 10      | 14        | 0.51%   |
| 84      | 12        | 0.43%   |
| 31      | 10        | 0.36%   |
| 54      | 6         | 0.22%   |
| 40      | 6         | 0.22%   |
| 27      | 6         | 0.22%   |
| 18      | 6         | 0.22%   |
| 72      | 5         | 0.18%   |
| 32      | 5         | 0.18%   |
| 34      | 4         | 0.14%   |
| 19      | 4         | 0.14%   |
| 16      | 4         | 0.14%   |
| Unknown | 4         | 0.14%   |
| 52      | 3         | 0.11%   |
| 37      | 3         | 0.11%   |
| 22      | 3         | 0.11%   |
| 46      | 2         | 0.07%   |
| 86      | 1         | 0.04%   |
| 65      | 1         | 0.04%   |
| 63      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 33      | 1         | 0.04%   |
| 29      | 1         | 0.04%   |
| 25      | 1         | 0.04%   |
| 20      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2230      | 80.94%  |
| 351-400     | 216       | 7.84%   |
| 201-300     | 171       | 6.21%   |
| 501-600     | 43        | 1.56%   |
| 401-500     | 27        | 0.98%   |
| 1501-2000   | 17        | 0.62%   |
| 1001-1500   | 16        | 0.58%   |
| 601-700     | 12        | 0.44%   |
| 701-800     | 10        | 0.36%   |
| 801-900     | 9         | 0.33%   |
| Unknown     | 4         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 2524      | 94.89%  |
| 16/10 | 116       | 4.36%   |
| 5/4   | 6         | 0.23%   |
| 3/2   | 5         | 0.19%   |
| 21/9  | 5         | 0.19%   |
| 4/3   | 3         | 0.11%   |
| 0.56  | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1842      | 66.76%  |
| 81-90          | 421       | 15.26%  |
| 121-130        | 175       | 6.34%   |
| 51-60          | 72        | 2.61%   |
| 71-80          | 52        | 1.88%   |
| 201-250        | 51        | 1.85%   |
| More than 1000 | 31        | 1.12%   |
| 61-70          | 22        | 0.8%    |
| 351-500        | 21        | 0.76%   |
| 41-50          | 14        | 0.51%   |
| 131-140        | 13        | 0.47%   |
| 501-1000       | 11        | 0.4%    |
| 151-200        | 8         | 0.29%   |
| 141-150        | 8         | 0.29%   |
| 301-350        | 6         | 0.22%   |
| 91-100         | 4         | 0.14%   |
| Unknown        | 4         | 0.14%   |
| 251-300        | 2         | 0.07%   |
| 111-120        | 2         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1290      | 46.88%  |
| 121-160       | 1191      | 43.28%  |
| 51-100        | 201       | 7.3%    |
| 1-50          | 32        | 1.16%   |
| 161-240       | 25        | 0.91%   |
| More than 240 | 9         | 0.33%   |
| Unknown       | 4         | 0.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2628      | 93.19%  |
| 2     | 136       | 4.82%   |
| 0     | 53        | 1.88%   |
| 3     | 3         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1911      | 43.73%  |
| Intel                             | 1073      | 24.55%  |
| Qualcomm Atheros                  | 919       | 21.03%  |
| Broadcom                          | 177       | 4.05%   |
| Broadcom Limited                  | 46        | 1.05%   |
| Marvell Technology Group          | 38        | 0.87%   |
| Ralink                            | 26        | 0.59%   |
| Ralink Technology                 | 23        | 0.53%   |
| JMicron Technology                | 17        | 0.39%   |
| MediaTek                          | 13        | 0.3%    |
| TP-Link                           | 12        | 0.27%   |
| Samsung Electronics               | 11        | 0.25%   |
| Xiaomi                            | 10        | 0.23%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.21%   |
| Nvidia                            | 8         | 0.18%   |
| ASIX Electronics                  | 8         | 0.18%   |
| Qualcomm Atheros Communications   | 7         | 0.16%   |
| Ericsson Business Mobile Networks | 7         | 0.16%   |
| Dell                              | 7         | 0.16%   |
| Huawei Technologies               | 6         | 0.14%   |
| NetGear                           | 4         | 0.09%   |
| Hewlett-Packard                   | 4         | 0.09%   |
| D-Link                            | 4         | 0.09%   |
| Motorola PCS                      | 3         | 0.07%   |
| VIA Technologies                  | 2         | 0.05%   |
| OPPO Electronics                  | 2         | 0.05%   |
| ICS Advent                        | 2         | 0.05%   |
| ASUSTek Computer                  | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.02%   |
| U.S. Robotics                     | 1         | 0.02%   |
| Texas Instruments                 | 1         | 0.02%   |
| T & A Mobile Phones               | 1         | 0.02%   |
| Sierra Wireless                   | 1         | 0.02%   |
| Shenzhen Goodix Technology        | 1         | 0.02%   |
| Qualcomm                          | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.02%   |
| Micro Star International          | 1         | 0.02%   |
| Linksys                           | 1         | 0.02%   |
| LG Electronics                    | 1         | 0.02%   |
| Lenovo                            | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 1102      | 23.02%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 458       | 9.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 313       | 6.54%   |
| Intel Wi-Fi 6 AX200                                                     | 259       | 5.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 248       | 5.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 166       | 3.47%   |
| Intel Wireless 8265 / 8275                                              | 159       | 3.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 113       | 2.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 88        | 1.84%   |
| Intel Wi-Fi 6 AX201                                                     | 85        | 1.78%   |
| Realtek Killer E2600 GbE Controller                                     | 83        | 1.73%   |
| Intel Wireless 7265                                                     | 76        | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 61        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 58        | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 55        | 1.15%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 52        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 50        | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                           | 46        | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 41        | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 40        | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 39        | 0.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 39        | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 0.58%   |
| Intel Wireless 7260                                                     | 27        | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 23        | 0.48%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 20        | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 19        | 0.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 19        | 0.4%    |
| Intel Wireless 8260                                                     | 18        | 0.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 18        | 0.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 16        | 0.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 16        | 0.33%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 15        | 0.31%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 15        | 0.31%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 15        | 0.31%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 14        | 0.29%   |
| Intel WiFi Link 5100                                                    | 14        | 0.29%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 13        | 0.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1052      | 37.48%  |
| Qualcomm Atheros                      | 860       | 30.64%  |
| Realtek Semiconductor                 | 636       | 22.66%  |
| Broadcom                              | 137       | 4.88%   |
| Ralink                                | 26        | 0.93%   |
| Broadcom Limited                      | 25        | 0.89%   |
| Ralink Technology                     | 23        | 0.82%   |
| MediaTek                              | 11        | 0.39%   |
| TP-Link                               | 7         | 0.25%   |
| Qualcomm Atheros Communications       | 7         | 0.25%   |
| Dell                                  | 5         | 0.18%   |
| NetGear                               | 3         | 0.11%   |
| D-Link                                | 3         | 0.11%   |
| Hewlett-Packard                       | 2         | 0.07%   |
| ASUSTek Computer                      | 2         | 0.07%   |
| U.S. Robotics                         | 1         | 0.04%   |
| Sierra Wireless                       | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| Linksys                               | 1         | 0.04%   |
| Edimax Technology                     | 1         | 0.04%   |
| AirTies Wireless Networks             | 1         | 0.04%   |
| Accton Technology                     | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 458       | 16.26%  |
| Intel Wi-Fi 6 AX200                                                     | 259       | 9.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 248       | 8.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 166       | 5.89%   |
| Intel Wireless 8265 / 8275                                              | 159       | 5.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 113       | 4.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 88        | 3.13%   |
| Intel Wi-Fi 6 AX201                                                     | 85        | 3.02%   |
| Intel Wireless 7265                                                     | 76        | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 2.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 61        | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 58        | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 55        | 1.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 52        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 50        | 1.78%   |
| Broadcom BCM43142 802.11b/g/n                                           | 46        | 1.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 41        | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 40        | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 39        | 1.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 0.99%   |
| Intel Wireless 7260                                                     | 27        | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 23        | 0.82%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 20        | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 19        | 0.67%   |
| Intel Wireless 8260                                                     | 18        | 0.64%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 18        | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 16        | 0.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 16        | 0.57%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 15        | 0.53%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 15        | 0.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 14        | 0.5%    |
| Intel WiFi Link 5100                                                    | 14        | 0.5%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 13        | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 13        | 0.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 0.43%   |
| Intel Wireless 3165                                                     | 12        | 0.43%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 12        | 0.43%   |
| Intel Centrino Ultimate-N 6300                                          | 12        | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1519      | 77.82%  |
| Intel                            | 128       | 6.56%   |
| Qualcomm Atheros                 | 104       | 5.33%   |
| Broadcom                         | 49        | 2.51%   |
| Marvell Technology Group         | 38        | 1.95%   |
| Broadcom Limited                 | 22        | 1.13%   |
| JMicron Technology               | 17        | 0.87%   |
| Xiaomi                           | 10        | 0.51%   |
| Samsung Electronics              | 10        | 0.51%   |
| Silicon Integrated Systems [SiS] | 9         | 0.46%   |
| Nvidia                           | 8         | 0.41%   |
| ASIX Electronics                 | 8         | 0.41%   |
| TP-Link                          | 5         | 0.26%   |
| Huawei Technologies              | 4         | 0.2%    |
| VIA Technologies                 | 2         | 0.1%    |
| OPPO Electronics                 | 2         | 0.1%    |
| Motorola PCS                     | 2         | 0.1%    |
| MediaTek                         | 2         | 0.1%    |
| ICS Advent                       | 2         | 0.1%    |
| T & A Mobile Phones              | 1         | 0.05%   |
| Qualcomm                         | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.05%   |
| NetGear                          | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Google                           | 1         | 0.05%   |
| Digitech Systems                 | 1         | 0.05%   |
| D-Link                           | 1         | 0.05%   |
| Attansic Technology              | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1102      | 56.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 313       | 16.02%  |
| Realtek Killer E2600 GbE Controller                                    | 83        | 4.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 39        | 2%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 19        | 0.97%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 15        | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 13        | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 12        | 0.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 12        | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 11        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 11        | 0.56%   |
| Intel Ethernet Connection (13) I219-V                                  | 11        | 0.56%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 10        | 0.51%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 10        | 0.51%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 9         | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 9         | 0.46%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 0.46%   |
| Intel 82567LM Gigabit Network Connection                               | 9         | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 8         | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 8         | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7         | 0.36%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 7         | 0.36%   |
| Intel Ethernet Connection I218-LM                                      | 7         | 0.36%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 0.36%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 7         | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 6         | 0.31%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 6         | 0.31%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 6         | 0.31%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 5         | 0.26%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 5         | 0.26%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 5         | 0.26%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.26%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 5         | 0.26%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 0.2%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 4         | 0.2%    |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2730      | 58.5%   |
| Ethernet | 1920      | 41.14%  |
| Modem    | 17        | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2528      | 89.01%  |
| Ethernet | 312       | 10.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1839      | 65.66%  |
| 1     | 886       | 31.63%  |
| 0     | 73        | 2.61%   |
| 3     | 3         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2473      | 86.92%  |
| Yes  | 372       | 13.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 896       | 38.16%  |
| IMC Networks                    | 486       | 20.7%   |
| Lite-On Technology              | 482       | 20.53%  |
| Realtek Semiconductor           | 174       | 7.41%   |
| Qualcomm Atheros Communications | 95        | 4.05%   |
| Broadcom                        | 64        | 2.73%   |
| Foxconn / Hon Hai               | 26        | 1.11%   |
| Dell                            | 25        | 1.06%   |
| Hewlett-Packard                 | 20        | 0.85%   |
| Cambridge Silicon Radio         | 20        | 0.85%   |
| Toshiba                         | 16        | 0.68%   |
| Apple                           | 12        | 0.51%   |
| Ralink                          | 10        | 0.43%   |
| Foxconn International           | 8         | 0.34%   |
| ASUSTek Computer                | 3         | 0.13%   |
| Alps Electric                   | 3         | 0.13%   |
| Qcom                            | 2         | 0.09%   |
| Smart Modular Technologies      | 1         | 0.04%   |
| Realtek                         | 1         | 0.04%   |
| Ralink Technology               | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 318       | 13.54%  |
| IMC Networks Bluetooth Radio                                                        | 318       | 13.54%  |
| Intel Bluetooth wireless interface                                                  | 299       | 12.73%  |
| Intel AX200 Bluetooth                                                               | 258       | 10.99%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 219       | 9.33%   |
| IMC Networks Bluetooth Device                                                       | 150       | 6.39%   |
| Realtek Bluetooth Radio                                                             | 128       | 5.45%   |
| Lite-On Bluetooth Device                                                            | 128       | 5.45%   |
| Intel AX201 Bluetooth                                                               | 51        | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 48        | 2.04%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 40        | 1.7%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 27        | 1.15%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 22        | 0.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 20        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 18        | 0.77%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 15        | 0.64%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 0.55%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 11        | 0.47%   |
| Ralink RT3290 Bluetooth                                                             | 10        | 0.43%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 0.43%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 9         | 0.38%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 8         | 0.34%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 8         | 0.34%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 7         | 0.3%    |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 7         | 0.3%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 0.3%    |
| IMC Networks Wireless_Device                                                        | 7         | 0.3%    |
| Dell DW375 Bluetooth Module                                                         | 7         | 0.3%    |
| Toshiba BCM43142A0                                                                  | 6         | 0.26%   |
| Realtek RTL8821A Bluetooth                                                          | 6         | 0.26%   |
| Realtek RTL8723B Bluetooth                                                          | 6         | 0.26%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 0.26%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.21%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 0.21%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 5         | 0.21%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 0.21%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 5         | 0.21%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 5         | 0.21%   |
| Toshiba Bluetooth Device                                                            | 4         | 0.17%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 4         | 0.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 2210      | 69.11%  |
| AMD                                             | 532       | 16.64%  |
| Nvidia                                          | 401       | 12.54%  |
| Silicon Integrated Systems [SiS]                | 10        | 0.31%   |
| Logitech                                        | 5         | 0.16%   |
| Generalplus Technology                          | 5         | 0.16%   |
| Plantronics                                     | 3         | 0.09%   |
| JMTek                                           | 3         | 0.09%   |
| C-Media Electronics                             | 3         | 0.09%   |
| ASUSTek Computer                                | 3         | 0.09%   |
| VIA Technologies                                | 2         | 0.06%   |
| Texas Instruments                               | 2         | 0.06%   |
| Corsair                                         | 2         | 0.06%   |
| Walmart                                         | 1         | 0.03%   |
| Tdlasunnic                                      | 1         | 0.03%   |
| Sony                                            | 1         | 0.03%   |
| Samsung Electronics                             | 1         | 0.03%   |
| Realtek Semiconductor                           | 1         | 0.03%   |
| Pioneer DJ                                      | 1         | 0.03%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.03%   |
| Lenovo                                          | 1         | 0.03%   |
| Kingston Technology                             | 1         | 0.03%   |
| Google                                          | 1         | 0.03%   |
| FiiO Electronics Technology                     | 1         | 0.03%   |
| Edifier Technology                              | 1         | 0.03%   |
| EasyPass Industrial                             | 1         | 0.03%   |
| DSEA A/S                                        | 1         | 0.03%   |
| Dell                                            | 1         | 0.03%   |
| Creative Technology                             | 1         | 0.03%   |
| Blue Microphones                                | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 474       | 12.74%  |
| AMD Ryzen HD Audio Controller                                                                     | 292       | 7.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 268       | 7.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 260       | 6.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 237       | 6.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 198       | 5.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 154       | 4.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 127       | 3.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 104       | 2.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 103       | 2.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 94        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 93        | 2.5%    |
| AMD High Definition Audio Controller                                                              | 90        | 2.42%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 87        | 2.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 85        | 2.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 66        | 1.77%   |
| AMD FCH Azalia Controller                                                                         | 66        | 1.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 63        | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 62        | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 51        | 1.37%   |
| Intel 8 Series HD Audio Controller                                                                | 51        | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 49        | 1.32%   |
| Intel Broadwell-U Audio Controller                                                                | 45        | 1.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 45        | 1.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 44        | 1.18%   |
| Intel CM238 HD Audio Controller                                                                   | 43        | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                                          | 43        | 1.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 42        | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 35        | 0.94%   |
| AMD Wrestler HDMI Audio                                                                           | 32        | 0.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 26        | 0.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24        | 0.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 21        | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 0.4%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 11        | 0.3%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 11        | 0.3%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 11        | 0.3%    |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 11        | 0.3%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 10        | 0.27%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 10        | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown (ABCD)      | 2         | 15.38%  |
| Samsung Electronics | 2         | 15.38%  |
| Micron Technology   | 2         | 15.38%  |
| Elpida              | 2         | 15.38%  |
| Unknown             | 1         | 7.69%   |
| SK hynix            | 1         | 7.69%   |
| Patriot             | 1         | 7.69%   |
| Kingston            | 1         | 7.69%   |
| Apacer              | 1         | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 15.38%  |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 7.69%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 7.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 7.69%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 7.69%   |
| Patriot RAM PSD38G1600L2S 8GB SODIMM DDR3 1600MT/s               | 1         | 7.69%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 7.69%   |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s    | 1         | 7.69%   |
| Kingston RAM 99U5428-073.A00G 8GB SODIMM DDR3 1600MT/s           | 1         | 7.69%   |
| Elpida RAM Module 4096MB SODIMM LPDDR3 1600MT/s                  | 1         | 7.69%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 7.69%   |
| Apacer RAM 76.D305G.D390B 16GB SODIMM DDR4 2400MT/s              | 1         | 7.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 4         | 30.77%  |
| DDR3   | 4         | 30.77%  |
| LPDDR4 | 3         | 23.08%  |
| LPDDR3 | 2         | 15.38%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 84.62%  |
| Row Of Chips | 2         | 15.38%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 7         | 53.85%  |
| 8192  | 4         | 30.77%  |
| 16384 | 2         | 15.38%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 5         | 38.46%  |
| 2400  | 4         | 30.77%  |
| 4267  | 1         | 7.69%   |
| 3266  | 1         | 7.69%   |
| 3200  | 1         | 7.69%   |
| 2133  | 1         | 7.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 27        | 33.33%  |
| Seiko Epson            | 19        | 23.46%  |
| Canon                  | 14        | 17.28%  |
| Brother Industries     | 10        | 12.35%  |
| Samsung Electronics    | 5         | 6.17%   |
| Xerox                  | 2         | 2.47%   |
| Pantum                 | 2         | 2.47%   |
| Ricoh                  | 1         | 1.23%   |
| Panasonic (Matsushita) | 1         | 1.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                    | 4         | 4.94%   |
| HP LaserJet 1020                              | 3         | 3.7%    |
| HP LaserJet 1018                              | 3         | 3.7%    |
| Xerox Phaser 3020                             | 2         | 2.47%   |
| Seiko Epson L3210 Series                      | 2         | 2.47%   |
| Seiko Epson L3050 Series                      | 2         | 2.47%   |
| Samsung M2020 Series                          | 2         | 2.47%   |
| HP DeskJet F4200 series                       | 2         | 2.47%   |
| HP DeskJet 2130 series                        | 2         | 2.47%   |
| HP Deskjet 1510                               | 2         | 2.47%   |
| HP Color Laser 150nw                          | 2         | 2.47%   |
| Brother DCP-T310                              | 2         | 2.47%   |
| Seiko Epson ME-100 Series                     | 1         | 1.23%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.23%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]  | 1         | 1.23%   |
| Seiko Epson L380 Series                       | 1         | 1.23%   |
| Seiko Epson L365 Series                       | 1         | 1.23%   |
| Seiko Epson L355 Series                       | 1         | 1.23%   |
| Seiko Epson L3110 Series                      | 1         | 1.23%   |
| Seiko Epson L210 Series                       | 1         | 1.23%   |
| Seiko Epson L120 Series                       | 1         | 1.23%   |
| Seiko Epson EPSON L220 Series                 | 1         | 1.23%   |
| Seiko Epson AcuLaser C1700                    | 1         | 1.23%   |
| Samsung M332x 382x 402x Series                | 1         | 1.23%   |
| Samsung M2070 Series                          | 1         | 1.23%   |
| Samsung Composite Device                      | 1         | 1.23%   |
| Ricoh SP 150SUw                               | 1         | 1.23%   |
| Pantum PMF22 series                           | 1         | 1.23%   |
| Pantum M6500W series                          | 1         | 1.23%   |
| Panasonic (Matsushita) KX-MB1500RU            | 1         | 1.23%   |
| HP OfficeJet 4650 series                      | 1         | 1.23%   |
| HP Officejet 4620 series                      | 1         | 1.23%   |
| HP LaserJet Professional P1102w               | 1         | 1.23%   |
| HP LaserJet Pro M148f-M149f                   | 1         | 1.23%   |
| HP HP Laser 107w                              | 1         | 1.23%   |
| HP ENVY Pro 6400 series                       | 1         | 1.23%   |
| HP DeskJet F300 series                        | 1         | 1.23%   |
| HP DeskJet 3630 series                        | 1         | 1.23%   |
| HP Deskjet 3050 J610 series                   | 1         | 1.23%   |
| HP DeskJet 2700 series                        | 1         | 1.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Seiko Epson                 | 1         | 33.33%  |
| Mustek Systems              | 1         | 33.33%  |
| Acer Peripherals (now BenQ) | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-F670 [Perfection V200 Photo] | 1         | 33.33%  |
| Mustek Systems BearPaw 2448 TA Plus         | 1         | 33.33%  |
| Acer Peripherals (now BenQ) Benq 5000       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 836       | 31.28%  |
| Chicony Electronics                    | 633       | 23.68%  |
| Quanta                                 | 488       | 18.26%  |
| Realtek Semiconductor                  | 109       | 4.08%   |
| Microdia                               | 79        | 2.96%   |
| Sonix Technology                       | 71        | 2.66%   |
| Suyin                                  | 67        | 2.51%   |
| Bison Electronics                      | 65        | 2.43%   |
| Sunplus Innovation Technology          | 56        | 2.1%    |
| Silicon Motion                         | 34        | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 1.2%    |
| Alcor Micro                            | 25        | 0.94%   |
| Syntek                                 | 20        | 0.75%   |
| Samsung Electronics                    | 17        | 0.64%   |
| Apple                                  | 16        | 0.6%    |
| Lite-On Technology                     | 15        | 0.56%   |
| Ricoh                                  | 11        | 0.41%   |
| OmniVision Technologies                | 10        | 0.37%   |
| Luxvisions Innotech Limited            | 10        | 0.37%   |
| ALi                                    | 10        | 0.37%   |
| Acer                                   | 10        | 0.37%   |
| Logitech                               | 7         | 0.26%   |
| Lenovo                                 | 7         | 0.26%   |
| Importek                               | 7         | 0.26%   |
| Primax Electronics                     | 5         | 0.19%   |
| Z-Star Microelectronics                | 3         | 0.11%   |
| Unknown                                | 3         | 0.11%   |
| Microsoft                              | 3         | 0.11%   |
| Motorola PCS                           | 2         | 0.07%   |
| GEMBIRD                                | 2         | 0.07%   |
| vivo                                   | 1         | 0.04%   |
| Sunplus Technology                     | 1         | 0.04%   |
| Sony                                   | 1         | 0.04%   |
| ShineTech                              | 1         | 0.04%   |
| Pixart Imaging                         | 1         | 0.04%   |
| Philips (or NXP)                       | 1         | 0.04%   |
| Novatek Microelectronics               | 1         | 0.04%   |
| Nebraska Furniture Mart                | 1         | 0.04%   |
| LG Electronics                         | 1         | 0.04%   |
| JMicron Technology                     | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                      | 589       | 22.03%  |
| Quanta HD User Facing                                   | 192       | 7.18%   |
| Chicony HD User Facing                                  | 180       | 6.73%   |
| Quanta VGA WebCam                                       | 163       | 6.1%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 162       | 6.06%   |
| Chicony USB2.0 VGA UVC WebCam                           | 94        | 3.52%   |
| Chicony VGA WebCam                                      | 90        | 3.37%   |
| Quanta HD Webcam                                        | 86        | 3.22%   |
| Sonix USB2.0 HD UVC WebCam                              | 68        | 2.54%   |
| Chicony HD WebCam                                       | 66        | 2.47%   |
| IMC Networks VGA UVC WebCam                             | 21        | 0.79%   |
| Chicony Integrated Camera                               | 20        | 0.75%   |
| Realtek Acer 640 x 480 laptop camera                    | 18        | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 17        | 0.64%   |
| Quanta USB2.0 HD UVC WebCam                             | 17        | 0.64%   |
| Microdia Integrated_Webcam_HD                           | 17        | 0.64%   |
| Chicony USB2.0 HD UVC WebCam                            | 17        | 0.64%   |
| Realtek HD WebCam                                       | 14        | 0.52%   |
| IMC Networks Integrated Camera                          | 14        | 0.52%   |
| Alcor Micro USB 2.0 Camera                              | 14        | 0.52%   |
| Sunplus HD WebCam                                       | 13        | 0.49%   |
| Realtek USB2.0 HD UVC WebCam                            | 12        | 0.45%   |
| Bison VGA WebCam                                        | 12        | 0.45%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 12        | 0.45%   |
| Quanta USB2.0 VGA UVC WebCam                            | 11        | 0.41%   |
| Microdia Integrated Webcam                              | 11        | 0.41%   |
| Chicony HP TrueVision HD                                | 11        | 0.41%   |
| Bison Lenovo EasyCamera                                 | 11        | 0.41%   |
| Sunplus Integrated_Webcam_HD                            | 10        | 0.37%   |
| Realtek Integrated_Webcam_HD                            | 10        | 0.37%   |
| OmniVision OV2640 Webcam                                | 10        | 0.37%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 10        | 0.37%   |
| Chicony USB 2.0 Camera                                  | 10        | 0.37%   |
| Chicony TOSHIBA Web Camera - HD                         | 10        | 0.37%   |
| Chicony HP Truevision HD camera                         | 10        | 0.37%   |
| Realtek USB Camera                                      | 9         | 0.34%   |
| Quanta HP Webcam                                        | 9         | 0.34%   |
| IMC Networks Lenovo EasyCamera                          | 9         | 0.34%   |
| Chicony Lenovo EasyCamera                               | 9         | 0.34%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 9         | 0.34%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 43        | 31.16%  |
| Elan Microelectronics      | 33        | 23.91%  |
| LighTuning Technology      | 28        | 20.29%  |
| AuthenTec                  | 13        | 9.42%   |
| Upek                       | 11        | 7.97%   |
| Synaptics                  | 4         | 2.9%    |
| STMicroelectronics         | 4         | 2.9%    |
| Shenzhen Goodix Technology | 2         | 1.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 32        | 23.19%  |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 22        | 15.94%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 6.52%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 5.07%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 4.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 3.62%   |
| Validity Sensors VFS491                                                    | 4         | 2.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 2.9%    |
| STMicroelectronics Fingerprint Reader                                      | 4         | 2.9%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 2.9%    |
| AuthenTec Fingerprint Sensor                                               | 4         | 2.9%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 2.17%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 2.17%   |
| AuthenTec AES2810                                                          | 3         | 2.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 2.17%   |
| AuthenTec AES1600                                                          | 3         | 2.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.45%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.45%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.45%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 1.45%   |
| Synaptics  WBDI                                                            | 2         | 1.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.45%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.72%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.72%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.72%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.72%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.72%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 0.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 0.72%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 33        | 64.71%  |
| O2 Micro              | 8         | 15.69%  |
| Alcor Micro           | 6         | 11.76%  |
| Lenovo                | 3         | 5.88%   |
| Advanced Card Systems | 1         | 1.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 43.14%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 13.73%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 13.73%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 11.76%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.88%   |
| Broadcom 5880                                                                | 3         | 5.88%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.96%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 1         | 1.96%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2245      | 79.95%  |
| 1     | 489       | 17.41%  |
| 2     | 70        | 2.49%   |
| 4     | 2         | 0.07%   |
| 5     | 1         | 0.04%   |
| 3     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Multimedia controller    | 199       | 30.85%  |
| Fingerprint reader       | 138       | 21.4%   |
| Graphics card            | 97        | 15.04%  |
| Net/wireless             | 84        | 13.02%  |
| Chipcard                 | 51        | 7.91%   |
| Storage                  | 21        | 3.26%   |
| Communication controller | 18        | 2.79%   |
| Bluetooth                | 14        | 2.17%   |
| Camera                   | 10        | 1.55%   |
| Net/ethernet             | 3         | 0.47%   |
| Storage/nvme             | 2         | 0.31%   |
| Storage/ide              | 2         | 0.31%   |
| Sound                    | 2         | 0.31%   |
| Modem                    | 2         | 0.31%   |
| Network                  | 1         | 0.16%   |
| Flash memory             | 1         | 0.16%   |

