Linux in Moldova - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Moldova.

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

Total: 273

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | Pavilion Laptop 15-eh3xx... | [48a2a9416d](https://linux-hardware.org/?probe=48a2a9416d) | Dec 23, 2025 |
| ASUSTek  | K52JU                       | [c8d6430be3](https://linux-hardware.org/?probe=c8d6430be3) | Dec 22, 2025 |
| Lenovo   | IdeaPad 3 15IIL05 81WE      | [b6198affc8](https://linux-hardware.org/?probe=b6198affc8) | Dec 22, 2025 |
| Lenovo   | IdeaPad Slim 5 16ABR8 82... | [ea0654048d](https://linux-hardware.org/?probe=ea0654048d) | Nov 30, 2025 |
| Lenovo   | ThinkPad T16 Gen 2 21HH0... | [82cdefdaa1](https://linux-hardware.org/?probe=82cdefdaa1) | Nov 25, 2025 |
| Lenovo   | IdeaPad 5 Pro 16ACH6 82L... | [f2f3a89e5e](https://linux-hardware.org/?probe=f2f3a89e5e) | Nov 22, 2025 |
| Lenovo   | IdeaPad 5 15ARE05 81YQ      | [db25ec21cd](https://linux-hardware.org/?probe=db25ec21cd) | Oct 30, 2025 |
| Acer     | Aspire A515-47              | [2ae4ca72e8](https://linux-hardware.org/?probe=2ae4ca72e8) | Oct 22, 2025 |
| HP       | EliteBook 855 G8 Noteboo... | [bb0f7a4588](https://linux-hardware.org/?probe=bb0f7a4588) | Oct 12, 2025 |
| ASUSTek  | ASUS TUF Gaming A15 FA50... | [1999801ddb](https://linux-hardware.org/?probe=1999801ddb) | Oct 06, 2025 |
| Lenovo   | ThinkPad E16 Gen 2 21M50... | [efe586e84f](https://linux-hardware.org/?probe=efe586e84f) | Sep 27, 2025 |
| Lenovo   | ThinkPad T60 200757U        | [9f86bc2772](https://linux-hardware.org/?probe=9f86bc2772) | Sep 03, 2025 |
| Lenovo   | Legion 5 15IMH6 82NL        | [b9b5f822b5](https://linux-hardware.org/?probe=b9b5f822b5) | Sep 02, 2025 |
| Lenovo   | ThinkPad T60 200757U        | [8b50dcd8eb](https://linux-hardware.org/?probe=8b50dcd8eb) | Aug 18, 2025 |
| ASUSTek  | X540NA                      | [a13048b57a](https://linux-hardware.org/?probe=a13048b57a) | Aug 12, 2025 |
| HP       | Laptop 15s-eq0xxx           | [fb1d1e0705](https://linux-hardware.org/?probe=fb1d1e0705) | Aug 11, 2025 |
| ASUSTek  | X540NA                      | [a865aa6c24](https://linux-hardware.org/?probe=a865aa6c24) | Aug 03, 2025 |
| Lenovo   | ThinkPad T14s Gen 1 20UH... | [9a9bce6a4c](https://linux-hardware.org/?probe=9a9bce6a4c) | Jul 14, 2025 |
| ASUSTek  | VivoBook_ASUSLaptop E510... | [99b401e450](https://linux-hardware.org/?probe=99b401e450) | Jun 12, 2025 |
| ASUSTek  | K52F                        | [fec6b00e98](https://linux-hardware.org/?probe=fec6b00e98) | May 28, 2025 |
| Lenovo   | ThinkPad T16 Gen 2 21HH0... | [e4a5285f99](https://linux-hardware.org/?probe=e4a5285f99) | May 25, 2025 |
| Acer     | Aspire A515-51G             | [9b70f780d8](https://linux-hardware.org/?probe=9b70f780d8) | Apr 21, 2025 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [82d1963fe3](https://linux-hardware.org/?probe=82d1963fe3) | Apr 06, 2025 |
| ASUSTek  | VivoBook_ASUSLaptop M650... | [3a287866bf](https://linux-hardware.org/?probe=3a287866bf) | Mar 18, 2025 |
| Lenovo   | IdeaPad 100-15IBD 80QQ      | [63bb1edec6](https://linux-hardware.org/?probe=63bb1edec6) | Mar 13, 2025 |
| Valve    | Galileo                     | [48126511b0](https://linux-hardware.org/?probe=48126511b0) | Feb 22, 2025 |
| Valve    | Galileo                     | [b783170749](https://linux-hardware.org/?probe=b783170749) | Feb 22, 2025 |
| ASUSTek  | ASUS Vivobook S 16 S5606... | [66b929637d](https://linux-hardware.org/?probe=66b929637d) | Jan 31, 2025 |
| Medion   | E15301                      | [6ed372ce0c](https://linux-hardware.org/?probe=6ed372ce0c) | Jan 29, 2025 |
| Samsung  | 300V3A/300V4A/300V5A/200... | [ffa58b22a6](https://linux-hardware.org/?probe=ffa58b22a6) | Dec 29, 2024 |
| Samsung  | 300V3A/300V4A/300V5A/200... | [c76825324c](https://linux-hardware.org/?probe=c76825324c) | Dec 28, 2024 |
| ASUSTek  | ASUS Vivobook S 16 M5606... | [87a62f7ab4](https://linux-hardware.org/?probe=87a62f7ab4) | Dec 12, 2024 |
| Lenovo   | Legion 5 15IMH05 82AU       | [79ab3bbc9e](https://linux-hardware.org/?probe=79ab3bbc9e) | Dec 06, 2024 |
| Lenovo   | IdeaPad 3 15ADA05 81W1      | [f9ad338bc2](https://linux-hardware.org/?probe=f9ad338bc2) | Nov 26, 2024 |
| ASUSTek  | X550CC                      | [9c9f50e48d](https://linux-hardware.org/?probe=9c9f50e48d) | Nov 11, 2024 |
| ASUSTek  | X550CC                      | [62c26e414e](https://linux-hardware.org/?probe=62c26e414e) | Nov 11, 2024 |
| ASUSTek  | ASUS Vivobook S 16 S5606... | [f375294d93](https://linux-hardware.org/?probe=f375294d93) | Oct 24, 2024 |
| ASUSTek  | ASUS Vivobook S 16 S5606... | [d137ac3a49](https://linux-hardware.org/?probe=d137ac3a49) | Oct 18, 2024 |
| HP       | ProBook 455 G1              | [fcc4357e92](https://linux-hardware.org/?probe=fcc4357e92) | Oct 17, 2024 |
| HP       | ProBook 455 G1              | [149a4ff02a](https://linux-hardware.org/?probe=149a4ff02a) | Oct 17, 2024 |
| HP       | EliteBook 8470w             | [a4891795bf](https://linux-hardware.org/?probe=a4891795bf) | Sep 12, 2024 |
| Acer     | Extensa 215-55              | [0ccc3d6915](https://linux-hardware.org/?probe=0ccc3d6915) | Aug 30, 2024 |
| Acer     | Extensa 215-55              | [a4a6cf7e93](https://linux-hardware.org/?probe=a4a6cf7e93) | Aug 30, 2024 |
| HP       | EliteBook 8470w             | [41ca7ce107](https://linux-hardware.org/?probe=41ca7ce107) | Aug 22, 2024 |
| HP       | EliteBook 8470w             | [42a6e42a14](https://linux-hardware.org/?probe=42a6e42a14) | Aug 22, 2024 |
| Timi     | A35S                        | [3f66d5ebac](https://linux-hardware.org/?probe=3f66d5ebac) | Aug 20, 2024 |
| XIAOMI   | Redmi Book Pro 15 2023      | [6bb19c46ab](https://linux-hardware.org/?probe=6bb19c46ab) | Aug 08, 2024 |
| XIAOMI   | Redmi Book Pro 15 2023      | [bac0c976f4](https://linux-hardware.org/?probe=bac0c976f4) | Aug 08, 2024 |
| Acer     | Aspire A315-23              | [d5fd4c88f2](https://linux-hardware.org/?probe=d5fd4c88f2) | Jul 20, 2024 |
| ASUSTek  | Vivobook Go E1404FA_E140... | [0aa3213f68](https://linux-hardware.org/?probe=0aa3213f68) | Jul 17, 2024 |
| ASUSTek  | VivoBook_ASUSLaptop M160... | [26b93db645](https://linux-hardware.org/?probe=26b93db645) | Jul 17, 2024 |
| Lenovo   | Legion 5 Pro 16ACH6H 82J... | [6de6fcd1fa](https://linux-hardware.org/?probe=6de6fcd1fa) | Jul 16, 2024 |
| MSI      | GE60 2PE                    | [b7a466ecc5](https://linux-hardware.org/?probe=b7a466ecc5) | Jun 29, 2024 |
| HP       | 250 15.6 inch G10 Notebo... | [0006f4096d](https://linux-hardware.org/?probe=0006f4096d) | Jun 03, 2024 |
| Lenovo   | IdeaPad 110-15IBR 80T7      | [f8379977a9](https://linux-hardware.org/?probe=f8379977a9) | May 27, 2024 |
| ASUSTek  | K50IJ                       | [6e78332749](https://linux-hardware.org/?probe=6e78332749) | May 20, 2024 |
| ASUSTek  | K50IJ                       | [ae43a3e7b5](https://linux-hardware.org/?probe=ae43a3e7b5) | May 20, 2024 |
| Dell     | Vostro 7620                 | [cf9fa662a8](https://linux-hardware.org/?probe=cf9fa662a8) | May 20, 2024 |
| Acer     | Extensa 215-55              | [491f2c8f23](https://linux-hardware.org/?probe=491f2c8f23) | May 15, 2024 |
| ASUSTek  | ROG Zephyrus G14 GA401IH... | [e19fea8a49](https://linux-hardware.org/?probe=e19fea8a49) | May 06, 2024 |
| HP       | 250 G4                      | [6c2d10b0b4](https://linux-hardware.org/?probe=6c2d10b0b4) | May 05, 2024 |
| Sony     | SVF1521C5E                  | [9a899f2e80](https://linux-hardware.org/?probe=9a899f2e80) | Apr 28, 2024 |
| Lenovo   | Yoga Pro 7 14APH8 82Y8      | [e36ba9916d](https://linux-hardware.org/?probe=e36ba9916d) | Apr 22, 2024 |
| Dell     | Inspiron 3593               | [e1b99394fb](https://linux-hardware.org/?probe=e1b99394fb) | Apr 13, 2024 |
| ASUSTek  | VivoBook_ASUSLaptop X150... | [92dd6dd367](https://linux-hardware.org/?probe=92dd6dd367) | Mar 31, 2024 |
| ASUSTek  | VivoBook_ASUSLaptop X415... | [cd86953989](https://linux-hardware.org/?probe=cd86953989) | Feb 18, 2024 |
| HP       | EliteBook 840 G5            | [bdd9d20df9](https://linux-hardware.org/?probe=bdd9d20df9) | Feb 04, 2024 |
| ASUSTek  | ROG Strix G713RW_G713RW     | [20827e6f82](https://linux-hardware.org/?probe=20827e6f82) | Jan 26, 2024 |
| ASUSTek  | VivoBook_ASUSLaptop X415... | [1427f84afd](https://linux-hardware.org/?probe=1427f84afd) | Jan 18, 2024 |
| Lenovo   | IdeaPad 5 Pro 14ACN6 82L... | [123bf2b824](https://linux-hardware.org/?probe=123bf2b824) | Jan 17, 2024 |
| Lenovo   | IdeaPad 310-15ISK 80SM      | [8494044b32](https://linux-hardware.org/?probe=8494044b32) | Jan 11, 2024 |
| Lenovo   | LOQ 15IRH8 82XV             | [494b496889](https://linux-hardware.org/?probe=494b496889) | Jan 01, 2024 |
| ASUSTek  | UX32VD                      | [e073ccab15](https://linux-hardware.org/?probe=e073ccab15) | Dec 13, 2023 |
| Lenovo   | Z51-70 80K6                 | [2894d2f78d](https://linux-hardware.org/?probe=2894d2f78d) | Dec 06, 2023 |
| Apple    | MacBookPro9,2               | [c120b25f0f](https://linux-hardware.org/?probe=c120b25f0f) | Nov 17, 2023 |
| HP       | 250 G8 Notebook PC          | [a6d12193c7](https://linux-hardware.org/?probe=a6d12193c7) | Nov 17, 2023 |
| HP       | ProBook 4320s               | [0da6b1026b](https://linux-hardware.org/?probe=0da6b1026b) | Nov 15, 2023 |
| ASUSTek  | ROG Strix G712LU_G712LU     | [50087ec971](https://linux-hardware.org/?probe=50087ec971) | Oct 08, 2023 |
| ASUSTek  | ROG Strix G712LU_G712LU     | [6f7b1474d0](https://linux-hardware.org/?probe=6f7b1474d0) | Oct 06, 2023 |
| Lenovo   | ThinkBook 15-IML 20RW       | [a8c067b868](https://linux-hardware.org/?probe=a8c067b868) | Sep 22, 2023 |
| Lenovo   | ThinkBook 15 G4 IAP 21DJ    | [367454b6bc](https://linux-hardware.org/?probe=367454b6bc) | Sep 16, 2023 |
| Dell     | Latitude 7490               | [c03e42edee](https://linux-hardware.org/?probe=c03e42edee) | Sep 05, 2023 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [ded378b5da](https://linux-hardware.org/?probe=ded378b5da) | Aug 30, 2023 |
| Timi     | A34R                        | [f2998bab84](https://linux-hardware.org/?probe=f2998bab84) | Aug 25, 2023 |
| Dell     | Latitude 7490               | [90685f1b4d](https://linux-hardware.org/?probe=90685f1b4d) | Aug 21, 2023 |
| Dell     | Inspiron 15 7000 Gaming     | [7da49ac1c3](https://linux-hardware.org/?probe=7da49ac1c3) | Aug 17, 2023 |
| Dell     | Latitude 7490               | [efb4abea09](https://linux-hardware.org/?probe=efb4abea09) | Aug 16, 2023 |
| ASUSTek  | ROG Strix G713RW_G713RW     | [91887235b2](https://linux-hardware.org/?probe=91887235b2) | Jul 31, 2023 |
| HP       | EliteBook 850 G1            | [3e08f1644a](https://linux-hardware.org/?probe=3e08f1644a) | Jun 24, 2023 |
| HP       | EliteBook 850 G1            | [574653afac](https://linux-hardware.org/?probe=574653afac) | Jun 24, 2023 |
| HP       | EliteBook 850 G1            | [fa6b09cc1d](https://linux-hardware.org/?probe=fa6b09cc1d) | Jun 23, 2023 |
| Dell     | Vostro 3525                 | [308ee62292](https://linux-hardware.org/?probe=308ee62292) | Jun 21, 2023 |
| Acer     | AOD257                      | [d3510be962](https://linux-hardware.org/?probe=d3510be962) | Jun 18, 2023 |
| Dell     | Vostro 3525                 | [fb399aebb6](https://linux-hardware.org/?probe=fb399aebb6) | Jun 11, 2023 |
| Dell     | Vostro 3525                 | [e4b62aaf28](https://linux-hardware.org/?probe=e4b62aaf28) | Jun 05, 2023 |
| Acer     | Aspire A515-54G             | [a6c2011fb0](https://linux-hardware.org/?probe=a6c2011fb0) | May 25, 2023 |
| Acer     | Aspire A515-54G             | [e58d4b4aee](https://linux-hardware.org/?probe=e58d4b4aee) | May 25, 2023 |
| Sony     | VPCF13WFX                   | [6500c354c7](https://linux-hardware.org/?probe=6500c354c7) | May 01, 2023 |
| Lenovo   | B50-30 80ES                 | [d84727b8e4](https://linux-hardware.org/?probe=d84727b8e4) | Apr 29, 2023 |
| Toshiba  | Satellite S50-B             | [e9d26a9e89](https://linux-hardware.org/?probe=e9d26a9e89) | Apr 12, 2023 |
| ASUSTek  | ZenBook UX425IA_UM425IA     | [3ac0a9cc94](https://linux-hardware.org/?probe=3ac0a9cc94) | Mar 31, 2023 |
| ASUSTek  | ROG Strix G533QM_G533QM     | [14f30effbe](https://linux-hardware.org/?probe=14f30effbe) | Mar 17, 2023 |
| ASUSTek  | X541NC                      | [d7e16d4472](https://linux-hardware.org/?probe=d7e16d4472) | Mar 11, 2023 |
| Apple    | MacBookPro8,1               | [60ab083fe9](https://linux-hardware.org/?probe=60ab083fe9) | Feb 25, 2023 |
| HP       | Pavilion Gaming Laptop 1... | [138e1ff0a8](https://linux-hardware.org/?probe=138e1ff0a8) | Feb 15, 2023 |
| ASUSTek  | K55A                        | [3faca30fb5](https://linux-hardware.org/?probe=3faca30fb5) | Feb 07, 2023 |
| Timi     | TM1701                      | [a474c92380](https://linux-hardware.org/?probe=a474c92380) | Jan 31, 2023 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [93fd2967ab](https://linux-hardware.org/?probe=93fd2967ab) | Jan 07, 2023 |
| Lenovo   | IdeaPad Gaming 3 15ACH6 ... | [0760eec7e2](https://linux-hardware.org/?probe=0760eec7e2) | Dec 28, 2022 |
| Valve    | Jupiter                     | [d008ed40fe](https://linux-hardware.org/?probe=d008ed40fe) | Nov 17, 2022 |
| Lenovo   | ThinkPad W520 4282BA9       | [4666660667](https://linux-hardware.org/?probe=4666660667) | Nov 12, 2022 |
| Unknown  | Unknown                     | [9247927a69](https://linux-hardware.org/?probe=9247927a69) | Nov 08, 2022 |
| Lenovo   | IdeaPad 330S-15ARR 81FB     | [8979e951e5](https://linux-hardware.org/?probe=8979e951e5) | Nov 07, 2022 |
| Google   | Droid                       | [c8e4007ce4](https://linux-hardware.org/?probe=c8e4007ce4) | Oct 26, 2022 |
| Lenovo   | IdeaPad 5 Pro 16ACH6 82L... | [71f188e90c](https://linux-hardware.org/?probe=71f188e90c) | Oct 19, 2022 |
| Acer     | Extensa 215-32              | [3e6ce67bb5](https://linux-hardware.org/?probe=3e6ce67bb5) | Oct 08, 2022 |
| Acer     | Extensa 215-32              | [366f0e7930](https://linux-hardware.org/?probe=366f0e7930) | Oct 08, 2022 |
| Acer     | Aspire A315-56              | [644bb082f4](https://linux-hardware.org/?probe=644bb082f4) | Sep 18, 2022 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | [3c214d75b2](https://linux-hardware.org/?probe=3c214d75b2) | Sep 10, 2022 |
| HP       | ProBook 450 G7              | [5fa4bf5fc8](https://linux-hardware.org/?probe=5fa4bf5fc8) | Aug 29, 2022 |
| Lenovo   | Legion 5 Pro 16ITH6H 82J... | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| Timi     | TM1701                      | [5b62dea22f](https://linux-hardware.org/?probe=5b62dea22f) | Aug 03, 2022 |
| Timi     | TM1701                      | [cddc7cb825](https://linux-hardware.org/?probe=cddc7cb825) | Aug 03, 2022 |
| Lenovo   | ThinkPad X1 Carbon 5th 2... | [d77ac14ae9](https://linux-hardware.org/?probe=d77ac14ae9) | Aug 01, 2022 |
| HP       | EliteBook 820 G3            | [a96c616d62](https://linux-hardware.org/?probe=a96c616d62) | Jul 28, 2022 |
| Dell     | Latitude 5480               | [151c4b8c85](https://linux-hardware.org/?probe=151c4b8c85) | Jul 21, 2022 |
| HP       | ProBook 450 G7              | [e011908e80](https://linux-hardware.org/?probe=e011908e80) | Jul 18, 2022 |
| HP       | ENVY 15                     | [9c0990eedf](https://linux-hardware.org/?probe=9c0990eedf) | Jul 18, 2022 |
| HP       | ProBook 450 G7              | [5d41d810e8](https://linux-hardware.org/?probe=5d41d810e8) | Jul 18, 2022 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | [1d5a0f6177](https://linux-hardware.org/?probe=1d5a0f6177) | Jul 12, 2022 |
| Lenovo   | IdeaPad Gaming 3 15ARH05... | [567077c28d](https://linux-hardware.org/?probe=567077c28d) | Jul 08, 2022 |
| Lenovo   | IdeaPad L340-15API 81LW     | [dda5fb9c20](https://linux-hardware.org/?probe=dda5fb9c20) | Jun 21, 2022 |
| ASUSTek  | X555LD                      | [d5d6eeb639](https://linux-hardware.org/?probe=d5d6eeb639) | Jun 11, 2022 |
| Lenovo   | Legion 5 15IMH05 82AU       | [cd7bc92bcd](https://linux-hardware.org/?probe=cd7bc92bcd) | Jun 06, 2022 |
| Lenovo   | IdeaPad 100-15IBY 80MJ      | [db944454c8](https://linux-hardware.org/?probe=db944454c8) | May 23, 2022 |
| Lenovo   | Legion Y530-15ICH 81FV      | [428509b262](https://linux-hardware.org/?probe=428509b262) | May 01, 2022 |
| ASUSTek  | X541NC                      | [d1dc342eb9](https://linux-hardware.org/?probe=d1dc342eb9) | Apr 17, 2022 |
| Lenovo   | ThinkPad X240 20AL0067RT    | [f246d643b4](https://linux-hardware.org/?probe=f246d643b4) | Feb 26, 2022 |
| Sony     | VPCEB1J8E                   | [b00a6a15b2](https://linux-hardware.org/?probe=b00a6a15b2) | Feb 20, 2022 |
| ASUSTek  | U32U                        | [f7b7d4d2db](https://linux-hardware.org/?probe=f7b7d4d2db) | Feb 20, 2022 |
| ASUSTek  | U32U                        | [1cb943e596](https://linux-hardware.org/?probe=1cb943e596) | Feb 20, 2022 |
| Acer     | Swift SF314-57              | [de92ca9fec](https://linux-hardware.org/?probe=de92ca9fec) | Feb 05, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | [4c95ae549f](https://linux-hardware.org/?probe=4c95ae549f) | Jan 21, 2022 |
| HP       | Unknown                     | [1fbb31af8d](https://linux-hardware.org/?probe=1fbb31af8d) | Jan 05, 2022 |
| Jumper   | EZbook                      | [6e9ee100f8](https://linux-hardware.org/?probe=6e9ee100f8) | Dec 22, 2021 |
| HP       | Pavilion Laptop 15-eh1xx... | [ab93ce9eb8](https://linux-hardware.org/?probe=ab93ce9eb8) | Dec 21, 2021 |
| Jumper   | EZbook                      | [992b2479e4](https://linux-hardware.org/?probe=992b2479e4) | Dec 21, 2021 |
| HP       | EliteBook 8470p             | [8ab831bf5f](https://linux-hardware.org/?probe=8ab831bf5f) | Dec 21, 2021 |
| Chuwi    | GemiBook Pro                | [493d55cb16](https://linux-hardware.org/?probe=493d55cb16) | Dec 11, 2021 |
| Dell     | Latitude 3520               | [8fb7494494](https://linux-hardware.org/?probe=8fb7494494) | Dec 06, 2021 |
| Acer     | Aspire 5253G                | [f7c885dedd](https://linux-hardware.org/?probe=f7c885dedd) | Nov 08, 2021 |
| Toshiba  | Satellite Pro S300L         | [93c5def444](https://linux-hardware.org/?probe=93c5def444) | Oct 06, 2021 |
| ASUSTek  | VivoBook S15 X510UF         | [336bbdae35](https://linux-hardware.org/?probe=336bbdae35) | Oct 02, 2021 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | [7820254b55](https://linux-hardware.org/?probe=7820254b55) | Sep 23, 2021 |
| Dell     | Latitude 5591               | [0235ac49c6](https://linux-hardware.org/?probe=0235ac49c6) | Sep 15, 2021 |
| Lenovo   | ThinkPad E15 Gen 3 20YG0... | [02666996c0](https://linux-hardware.org/?probe=02666996c0) | Sep 12, 2021 |
| Lenovo   | ThinkPad E15 Gen 3 20YG0... | [97b45da8a7](https://linux-hardware.org/?probe=97b45da8a7) | Sep 12, 2021 |
| HP       | Laptop 15-da1xxx            | [c6f3848c20](https://linux-hardware.org/?probe=c6f3848c20) | Sep 12, 2021 |
| HP       | Laptop 15-da1xxx            | [b73b5ecab7](https://linux-hardware.org/?probe=b73b5ecab7) | Sep 11, 2021 |
| HP       | ProBook 450 G6              | [227d87ab66](https://linux-hardware.org/?probe=227d87ab66) | Aug 20, 2021 |
| Toshiba  | TECRA Z40-B                 | [d353412a4f](https://linux-hardware.org/?probe=d353412a4f) | Jul 29, 2021 |
| Lenovo   | IdeaPad 5 15ARE05 81YQ      | [8430084f74](https://linux-hardware.org/?probe=8430084f74) | Jul 15, 2021 |
| System76 | Adder WS                    | [d128c1d16b](https://linux-hardware.org/?probe=d128c1d16b) | Jul 08, 2021 |
| Lenovo   | ThinkPad T440 20B7S1N809    | [b9ab49e917](https://linux-hardware.org/?probe=b9ab49e917) | Jul 07, 2021 |
| Dell     | Vostro 5590                 | [1cc0df9bfd](https://linux-hardware.org/?probe=1cc0df9bfd) | Jun 28, 2021 |
| Dell     | Vostro 5590                 | [0caade1304](https://linux-hardware.org/?probe=0caade1304) | Jun 28, 2021 |
| ASUSTek  | X555LJ                      | [aab7280bd9](https://linux-hardware.org/?probe=aab7280bd9) | Jun 20, 2021 |
| Timi     | A35S                        | [226823eb5b](https://linux-hardware.org/?probe=226823eb5b) | Jun 19, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | [79e70ff708](https://linux-hardware.org/?probe=79e70ff708) | Jun 17, 2021 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | [447e508593](https://linux-hardware.org/?probe=447e508593) | Jun 14, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | [47d894d771](https://linux-hardware.org/?probe=47d894d771) | Jun 12, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | [5c14296bc9](https://linux-hardware.org/?probe=5c14296bc9) | Jun 12, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | [73e1185f6e](https://linux-hardware.org/?probe=73e1185f6e) | Jun 12, 2021 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | [666ddeb09c](https://linux-hardware.org/?probe=666ddeb09c) | May 19, 2021 |
| Dell     | Inspiron 3541               | [88d0f731fd](https://linux-hardware.org/?probe=88d0f731fd) | Apr 29, 2021 |
| Dell     | Inspiron 3541               | [4267385ad8](https://linux-hardware.org/?probe=4267385ad8) | Apr 29, 2021 |
| Dell     | Inspiron 3593               | [5facbef10b](https://linux-hardware.org/?probe=5facbef10b) | Apr 24, 2021 |
| Dell     | Latitude E7440              | [c59d5358b3](https://linux-hardware.org/?probe=c59d5358b3) | Apr 04, 2021 |
| HP       | Pavilion dv7                | [b7756075fd](https://linux-hardware.org/?probe=b7756075fd) | Mar 15, 2021 |
| Lenovo   | Legion Y530-15ICH 81FV      | [bd5d97f7e7](https://linux-hardware.org/?probe=bd5d97f7e7) | Mar 07, 2021 |
| HP       | ZBook Fury 15 G7 Mobile ... | [c2435842e1](https://linux-hardware.org/?probe=c2435842e1) | Mar 04, 2021 |
| HP       | ZBook Fury 15 G7 Mobile ... | [5cc3d3f3ed](https://linux-hardware.org/?probe=5cc3d3f3ed) | Mar 04, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [16d0cd0b17](https://linux-hardware.org/?probe=16d0cd0b17) | Mar 04, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [7a3239606c](https://linux-hardware.org/?probe=7a3239606c) | Mar 04, 2021 |
| Lenovo   | Legion Y530-15ICH 81FV      | [88bab7f6e7](https://linux-hardware.org/?probe=88bab7f6e7) | Feb 22, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | [454ea43e4a](https://linux-hardware.org/?probe=454ea43e4a) | Feb 11, 2021 |
| HP       | ProBook 650 G2              | [043b7f867b](https://linux-hardware.org/?probe=043b7f867b) | Jan 23, 2021 |
| HP       | Laptop 15-dw0xxx            | [a69f5fa59f](https://linux-hardware.org/?probe=a69f5fa59f) | Jan 17, 2021 |
| Gateway  | NV55S                       | [8ed7215a68](https://linux-hardware.org/?probe=8ed7215a68) | Jan 17, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | [a2da0e78db](https://linux-hardware.org/?probe=a2da0e78db) | Jan 14, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | [84f50057c5](https://linux-hardware.org/?probe=84f50057c5) | Jan 14, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | [c3b5acb8ff](https://linux-hardware.org/?probe=c3b5acb8ff) | Jan 14, 2021 |
| Gateway  | NV55S                       | [149e658abf](https://linux-hardware.org/?probe=149e658abf) | Jan 10, 2021 |
| HP       | EliteBook 855 G7 Noteboo... | [9f70a6e397](https://linux-hardware.org/?probe=9f70a6e397) | Jan 06, 2021 |
| HP       | Pavilion 17                 | [ac1360247b](https://linux-hardware.org/?probe=ac1360247b) | Dec 22, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | [049fa926a1](https://linux-hardware.org/?probe=049fa926a1) | Dec 21, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | [69e21f1387](https://linux-hardware.org/?probe=69e21f1387) | Nov 09, 2020 |
| Lenovo   | ThinkPad Yoga 11e 3rd Ge... | [bc1158d1d3](https://linux-hardware.org/?probe=bc1158d1d3) | Nov 09, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | [8725886c61](https://linux-hardware.org/?probe=8725886c61) | Nov 06, 2020 |
| Dell     | Inspiron N5110              | [ee5fa15c46](https://linux-hardware.org/?probe=ee5fa15c46) | Nov 06, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [6e4daa0a3c](https://linux-hardware.org/?probe=6e4daa0a3c) | Nov 05, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [3a9f43c320](https://linux-hardware.org/?probe=3a9f43c320) | Nov 04, 2020 |
| HUAWEI   | NBLK-WAX9X                  | [4088a13026](https://linux-hardware.org/?probe=4088a13026) | Oct 09, 2020 |
| ASUSTek  | X200MA                      | [794220eee6](https://linux-hardware.org/?probe=794220eee6) | Sep 26, 2020 |
| Lenovo   | G710 20252                  | [c166b56839](https://linux-hardware.org/?probe=c166b56839) | Aug 26, 2020 |
| ASUSTek  | X541NA                      | [3f4978f463](https://linux-hardware.org/?probe=3f4978f463) | Aug 03, 2020 |
| HP       | ProBook 6465b               | [378cd77f66](https://linux-hardware.org/?probe=378cd77f66) | Jul 26, 2020 |
| ASUSTek  | VivoBook S15 X510UF         | [66a180cdab](https://linux-hardware.org/?probe=66a180cdab) | Jul 24, 2020 |
| ASUSTek  | VivoBook S15 X510UF         | [ed25557a01](https://linux-hardware.org/?probe=ed25557a01) | Jul 20, 2020 |
| HP       | Compaq Presario CQ60        | [8d24316f6b](https://linux-hardware.org/?probe=8d24316f6b) | Jul 15, 2020 |
| HP       | ProBook 450 G7              | [3638848f89](https://linux-hardware.org/?probe=3638848f89) | Jun 24, 2020 |
| Dell     | XPS 15 9570                 | [c14028664d](https://linux-hardware.org/?probe=c14028664d) | Jun 23, 2020 |
| ASUSTek  | X541NA                      | [6d3495ee91](https://linux-hardware.org/?probe=6d3495ee91) | Jun 14, 2020 |
| HP       | ProBook 470 G2              | [bce3965ebb](https://linux-hardware.org/?probe=bce3965ebb) | Jun 13, 2020 |
| Lenovo   | IdeaPad 130-15IKB 81H7      | [54b25b6a82](https://linux-hardware.org/?probe=54b25b6a82) | Apr 18, 2020 |
| HP       | EliteBook 850 G6            | [92d96a7e87](https://linux-hardware.org/?probe=92d96a7e87) | Apr 11, 2020 |
| Samsung  | RV413/RV513                 | [996451817e](https://linux-hardware.org/?probe=996451817e) | Mar 12, 2020 |
| Lenovo   | IdeaPad 330-15IGM 81D1      | [c0c091dee5](https://linux-hardware.org/?probe=c0c091dee5) | Feb 22, 2020 |
| Lenovo   | IdeaPad 330-15IGM 81D1      | [f1e8d4fb95](https://linux-hardware.org/?probe=f1e8d4fb95) | Feb 22, 2020 |
| ASUSTek  | X541NA                      | [3df0912982](https://linux-hardware.org/?probe=3df0912982) | Feb 15, 2020 |
| Lenovo   | G710 20252                  | [7df7fd3c10](https://linux-hardware.org/?probe=7df7fd3c10) | Feb 15, 2020 |
| Toshiba  | Satellite C55D-A            | [19713fa1aa](https://linux-hardware.org/?probe=19713fa1aa) | Feb 05, 2020 |
| Dell     | Inspiron 3582               | [6916c1087b](https://linux-hardware.org/?probe=6916c1087b) | Jan 21, 2020 |
| Dell     | Inspiron 3582               | [b873ab0117](https://linux-hardware.org/?probe=b873ab0117) | Jan 16, 2020 |
| Dell     | Inspiron 3582               | [cf3745ead4](https://linux-hardware.org/?probe=cf3745ead4) | Jan 16, 2020 |
| ASUSTek  | K54C                        | [42b284e62d](https://linux-hardware.org/?probe=42b284e62d) | Dec 17, 2019 |
| ASUSTek  | X542UR                      | [8c29a78852](https://linux-hardware.org/?probe=8c29a78852) | Dec 15, 2019 |
| ASUSTek  | X542UR                      | [106dcde5e2](https://linux-hardware.org/?probe=106dcde5e2) | Oct 24, 2019 |
| ASUSTek  | X542UR                      | [d5d9fe7ed0](https://linux-hardware.org/?probe=d5d9fe7ed0) | Oct 15, 2019 |
| ASUSTek  | X542UR                      | [f0e44b13bf](https://linux-hardware.org/?probe=f0e44b13bf) | Sep 15, 2019 |
| ASUSTek  | X541SA                      | [f4ec1608f1](https://linux-hardware.org/?probe=f4ec1608f1) | Aug 19, 2019 |
| Samsung  | RV413/RV513                 | [a569d1638b](https://linux-hardware.org/?probe=a569d1638b) | Aug 16, 2019 |
| HP       | Compaq 6910p                | [2b9b5142af](https://linux-hardware.org/?probe=2b9b5142af) | Jul 02, 2019 |
| Dell     | Inspiron 3521               | [5129fbc2b3](https://linux-hardware.org/?probe=5129fbc2b3) | Jun 13, 2019 |
| Dell     | Inspiron 3521               | [de72a9023b](https://linux-hardware.org/?probe=de72a9023b) | Jun 12, 2019 |
| Timi     | TM1701                      | [b2b217c7ba](https://linux-hardware.org/?probe=b2b217c7ba) | Jun 04, 2019 |
| Lenovo   | IdeaPad 330S-14IKB 81F4     | [1df14b9671](https://linux-hardware.org/?probe=1df14b9671) | May 31, 2019 |
| Acer     | Aspire E1-572G              | [d7c9cc59b9](https://linux-hardware.org/?probe=d7c9cc59b9) | May 17, 2019 |
| ASUSTek  | X550JX                      | [a268d267b1](https://linux-hardware.org/?probe=a268d267b1) | May 14, 2019 |
| Toshiba  | Satellite A210              | [b08d78a7fe](https://linux-hardware.org/?probe=b08d78a7fe) | May 12, 2019 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [adff6b4ec1](https://linux-hardware.org/?probe=adff6b4ec1) | May 08, 2019 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [1427bdb593](https://linux-hardware.org/?probe=1427bdb593) | May 08, 2019 |
| HP       | Compaq Presario CQ60        | [c4ee62ecc8](https://linux-hardware.org/?probe=c4ee62ecc8) | Mar 21, 2019 |
| Acer     | Aspire A515-51G             | [bc2c6a0308](https://linux-hardware.org/?probe=bc2c6a0308) | Jan 21, 2019 |
| Acer     | Aspire A515-51G             | [a4fa6be429](https://linux-hardware.org/?probe=a4fa6be429) | Jan 21, 2019 |
| Samsung  | 300E4C/300E5C/300E7C        | [761e996b51](https://linux-hardware.org/?probe=761e996b51) | Jan 13, 2019 |
| HP       | 635                         | [26ac239a00](https://linux-hardware.org/?probe=26ac239a00) | Jan 13, 2019 |
| HP       | 635                         | [88b6088e86](https://linux-hardware.org/?probe=88b6088e86) | Jan 13, 2019 |
| Dell     | Latitude E5420              | [58a37ca1d7](https://linux-hardware.org/?probe=58a37ca1d7) | Jan 08, 2019 |
| HP       | Compaq CQ58                 | [f930811937](https://linux-hardware.org/?probe=f930811937) | Dec 25, 2018 |
| HP       | Compaq CQ58                 | [092addb321](https://linux-hardware.org/?probe=092addb321) | Dec 25, 2018 |
| Samsung  | R517/R717                   | [cf1386553c](https://linux-hardware.org/?probe=cf1386553c) | Dec 11, 2018 |
| HP       | ENVY m6                     | [a2443c2500](https://linux-hardware.org/?probe=a2443c2500) | Nov 28, 2018 |
| Lenovo   | ThinkPad X131e 33711T0      | [d765880811](https://linux-hardware.org/?probe=d765880811) | Nov 20, 2018 |
| ASUSTek  | K56CM                       | [9801230a74](https://linux-hardware.org/?probe=9801230a74) | Oct 11, 2018 |
| Lenovo   | G710 20252                  | [67b5fc31a6](https://linux-hardware.org/?probe=67b5fc31a6) | Sep 03, 2018 |
| ASUSTek  | K50AB                       | [5309fc98bb](https://linux-hardware.org/?probe=5309fc98bb) | Jun 21, 2018 |
| Lenovo   | Y520-15IKBN 80WK            | [9c2fa220c0](https://linux-hardware.org/?probe=9c2fa220c0) | Jun 07, 2018 |
| Lenovo   | Y520-15IKBN 80WK            | [23cd9fcd79](https://linux-hardware.org/?probe=23cd9fcd79) | Jun 07, 2018 |
| ASUSTek  | K52N                        | [9b6027f7f9](https://linux-hardware.org/?probe=9b6027f7f9) | Mar 04, 2018 |
| ASUSTek  | K52N                        | [a31f696968](https://linux-hardware.org/?probe=a31f696968) | Jan 27, 2018 |
| ASUSTek  | E502SA                      | [f82780c45f](https://linux-hardware.org/?probe=f82780c45f) | Dec 22, 2017 |
| Samsung  | R517/R717                   | [88501ec4d2](https://linux-hardware.org/?probe=88501ec4d2) | Nov 23, 2017 |
| Acer     | Aspire E5-575               | [d7a774808d](https://linux-hardware.org/?probe=d7a774808d) | Nov 07, 2017 |
| Lenovo   | V580 20147                  | [7b4ec145fd](https://linux-hardware.org/?probe=7b4ec145fd) | Sep 05, 2017 |
| ASUSTek  | E502SA                      | [f80e3a3361](https://linux-hardware.org/?probe=f80e3a3361) | Jul 02, 2017 |
| Acer     | AO756                       | [750d61ea27](https://linux-hardware.org/?probe=750d61ea27) | Jun 28, 2017 |
| ASUSTek  | E502SA                      | [e638970390](https://linux-hardware.org/?probe=e638970390) | Jun 27, 2017 |
| Samsung  | R517/R717                   | [a037b05f1c](https://linux-hardware.org/?probe=a037b05f1c) | Jun 07, 2017 |
| Lenovo   | V580 20147                  | [e4a66b20cf](https://linux-hardware.org/?probe=e4a66b20cf) | May 09, 2017 |
| HP       | 550                         | [21d69ed69f](https://linux-hardware.org/?probe=21d69ed69f) | Feb 14, 2017 |
| Acer     | Aspire E1-531G              | [0481735487](https://linux-hardware.org/?probe=0481735487) | Dec 19, 2016 |
| MSI      | CR610                       | [fa269a3f05](https://linux-hardware.org/?probe=fa269a3f05) | Nov 20, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 18.04        | 12        | 5.63%   |
| Ubuntu 22.04        | 11        | 5.16%   |
| Ubuntu 20.04        | 11        | 5.16%   |
| Ubuntu 24.04        | 10        | 4.69%   |
| ROSA R10            | 9         | 4.23%   |
| ROSA R11            | 6         | 2.82%   |
| Linux Mint 20.1     | 5         | 2.35%   |
| Arch Rolling        | 5         | 2.35%   |
| Zorin 17            | 4         | 1.88%   |
| Linux Mint 21.1     | 4         | 1.88%   |
| KDE neon 20.04      | 4         | 1.88%   |
| Arch                | 4         | 1.88%   |
| ROSA R9             | 3         | 1.41%   |
| ROSA R8             | 3         | 1.41%   |
| ROSA R11.1          | 3         | 1.41%   |
| ROSA 12.5.1         | 3         | 1.41%   |
| Pop!_OS 22.04       | 3         | 1.41%   |
| Linux Mint 19.1     | 3         | 1.41%   |
| Fedora 42           | 3         | 1.41%   |
| Fedora 39           | 3         | 1.41%   |
| Fedora 36           | 3         | 1.41%   |
| Fedora 34           | 3         | 1.41%   |
| EndeavourOS Rolling | 3         | 1.41%   |
| Zorin 16            | 2         | 0.94%   |
| Ubuntu 22.10        | 2         | 0.94%   |
| Ubuntu 19.10        | 2         | 0.94%   |
| ROSA R8.1           | 2         | 0.94%   |
| ROSA 13.0           | 2         | 0.94%   |
| ROSA 12.2           | 2         | 0.94%   |
| Pop!_OS 21.04       | 2         | 0.94%   |
| OpenMandriva 4.3    | 2         | 0.94%   |
| OpenMandriva 23.08  | 2         | 0.94%   |
| Manjaro             | 2         | 0.94%   |
| Linux Mint 21.3     | 2         | 0.94%   |
| Linux Mint 21.2     | 2         | 0.94%   |
| Linux Mint 20.2     | 2         | 0.94%   |
| KDE neon 22.04      | 2         | 0.94%   |
| Fedora 40           | 2         | 0.94%   |
| BlackPanther 18.1   | 2         | 0.94%   |
| Ubuntu Budgie 23.04 | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 52        | 25.62%  |
| ROSA          | 32        | 15.76%  |
| Linux Mint    | 23        | 11.33%  |
| Fedora        | 19        | 9.36%   |
| OpenMandriva  | 9         | 4.43%   |
| Manjaro       | 9         | 4.43%   |
| Arch          | 9         | 4.43%   |
| Zorin         | 6         | 2.96%   |
| Pop!_OS       | 6         | 2.96%   |
| KDE neon      | 6         | 2.96%   |
| Kali          | 5         | 2.46%   |
| Debian        | 5         | 2.46%   |
| SteamOS       | 3         | 1.48%   |
| Kubuntu       | 3         | 1.48%   |
| Endless       | 3         | 1.48%   |
| EndeavourOS   | 3         | 1.48%   |
| BlackPanther  | 2         | 0.99%   |
| Ubuntu Budgie | 1         | 0.49%   |
| Solus         | 1         | 0.49%   |
| Elementary    | 1         | 0.49%   |
| Clear Linux   | 1         | 0.49%   |
| CachyOS       | 1         | 0.49%   |
| BuildRoot     | 1         | 0.49%   |
| ArcoLinux     | 1         | 0.49%   |
| ALT Linux     | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.15.0-41-generic                  | 4         | 1.79%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 4         | 1.79%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 4         | 1.79%   |
| 6.5.0-35-generic                   | 3         | 1.35%   |
| 5.8.0-33-generic                   | 3         | 1.35%   |
| 4.9.60-nrj-desktop-1rosa-i586      | 3         | 1.35%   |
| 6.9.3-76060903-generic             | 2         | 0.9%    |
| 6.8.0-41-generic                   | 2         | 0.9%    |
| 6.6.94-generic-1rosa2021.1-x86_64  | 2         | 0.9%    |
| 6.6.8-arch1-1                      | 2         | 0.9%    |
| 6.13.9-desktop-3omv2590            | 2         | 0.9%    |
| 5.4.0-37-generic                   | 2         | 0.9%    |
| 5.16.7-desktop-1omv4003            | 2         | 0.9%    |
| 5.15.0-88-generic                  | 2         | 0.9%    |
| 5.15.0-58-generic                  | 2         | 0.9%    |
| 5.11.0-7614-generic                | 2         | 0.9%    |
| 5.11.0-41-generic                  | 2         | 0.9%    |
| 5.11.0-34-generic                  | 2         | 0.9%    |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 0.9%    |
| 5.10.2-2-MANJARO                   | 2         | 0.9%    |
| 4.9.95-nrj-desktop-2rosa-x86_64    | 2         | 0.9%    |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 2         | 0.9%    |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 2         | 0.9%    |
| 4.15.0-desktop-68.5rosa-x86_64     | 2         | 0.9%    |
| 4.15.0-desktop-45.1rosa-x86_64     | 2         | 0.9%    |
| 6.9.8-200.fc40.x86_64              | 1         | 0.45%   |
| 6.8.9-200.fc39.x86_64              | 1         | 0.45%   |
| 6.8.6-200.fc39.x86_64              | 1         | 0.45%   |
| 6.8.4-arch1-1                      | 1         | 0.45%   |
| 6.8.1-060801-generic               | 1         | 0.45%   |
| 6.8.0-90-generic                   | 1         | 0.45%   |
| 6.8.0-79-generic                   | 1         | 0.45%   |
| 6.8.0-59-generic                   | 1         | 0.45%   |
| 6.8.0-55-generic                   | 1         | 0.45%   |
| 6.8.0-52-generic                   | 1         | 0.45%   |
| 6.8.0-48-generic                   | 1         | 0.45%   |
| 6.8.0-47-generic                   | 1         | 0.45%   |
| 6.8.0-39-generic                   | 1         | 0.45%   |
| 6.8.0-38-generic                   | 1         | 0.45%   |
| 6.8.0-31-generic                   | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 19        | 8.68%   |
| 4.15.0  | 15        | 6.85%   |
| 6.8.0   | 12        | 5.48%   |
| 5.4.0   | 12        | 5.48%   |
| 5.11.0  | 11        | 5.02%   |
| 6.5.0   | 7         | 3.2%    |
| 4.9.60  | 6         | 2.74%   |
| 5.8.0   | 5         | 2.28%   |
| 5.3.0   | 4         | 1.83%   |
| 4.9.20  | 4         | 1.83%   |
| 6.2.0   | 3         | 1.37%   |
| 6.14.0  | 3         | 1.37%   |
| 5.13.0  | 3         | 1.37%   |
| 5.0.0   | 3         | 1.37%   |
| 4.18.0  | 3         | 1.37%   |
| 6.9.3   | 2         | 0.91%   |
| 6.6.94  | 2         | 0.91%   |
| 6.6.8   | 2         | 0.91%   |
| 6.13.9  | 2         | 0.91%   |
| 6.11.0  | 2         | 0.91%   |
| 5.8.18  | 2         | 0.91%   |
| 5.19.0  | 2         | 0.91%   |
| 5.18.1  | 2         | 0.91%   |
| 5.16.7  | 2         | 0.91%   |
| 5.10.74 | 2         | 0.91%   |
| 5.10.2  | 2         | 0.91%   |
| 5.10.0  | 2         | 0.91%   |
| 4.9.95  | 2         | 0.91%   |
| 4.9.41  | 2         | 0.91%   |
| 4.9.155 | 2         | 0.91%   |
| 6.9.8   | 1         | 0.46%   |
| 6.8.9   | 1         | 0.46%   |
| 6.8.6   | 1         | 0.46%   |
| 6.8.4   | 1         | 0.46%   |
| 6.8.1   | 1         | 0.46%   |
| 6.7.0   | 1         | 0.46%   |
| 6.6.27  | 1         | 0.46%   |
| 6.6.21  | 1         | 0.46%   |
| 6.6.2   | 1         | 0.46%   |
| 6.6.14  | 1         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 25        | 11.74%  |
| 6.8     | 16        | 7.51%   |
| 4.9     | 15        | 7.04%   |
| 4.15    | 15        | 7.04%   |
| 5.4     | 14        | 6.57%   |
| 5.11    | 12        | 5.63%   |
| 5.10    | 9         | 4.23%   |
| 6.6     | 8         | 3.76%   |
| 6.5     | 8         | 3.76%   |
| 5.8     | 7         | 3.29%   |
| 6.2     | 6         | 2.82%   |
| 6.12    | 6         | 2.82%   |
| 5.18    | 6         | 2.82%   |
| 6.11    | 5         | 2.35%   |
| 6.4     | 4         | 1.88%   |
| 5.3     | 4         | 1.88%   |
| 5.19    | 4         | 1.88%   |
| 5.13    | 4         | 1.88%   |
| 5.0     | 4         | 1.88%   |
| 6.9     | 3         | 1.41%   |
| 6.17    | 3         | 1.41%   |
| 6.14    | 3         | 1.41%   |
| 6.1     | 3         | 1.41%   |
| 5.17    | 3         | 1.41%   |
| 5.16    | 3         | 1.41%   |
| 4.18    | 3         | 1.41%   |
| 4.1     | 3         | 1.41%   |
| 6.16    | 2         | 0.94%   |
| 6.13    | 2         | 0.94%   |
| 5.12    | 2         | 0.94%   |
| 6.7     | 1         | 0.47%   |
| 6.3     | 1         | 0.47%   |
| 6.15    | 1         | 0.47%   |
| 6.10    | 1         | 0.47%   |
| 5.9     | 1         | 0.47%   |
| 5.6     | 1         | 0.47%   |
| 5.14    | 1         | 0.47%   |
| 5.1     | 1         | 0.47%   |
| 4.19    | 1         | 0.47%   |
| 4.16    | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 197       | 96.57%  |
| i686   | 7         | 3.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 76        | 36.71%  |
| KDE5            | 43        | 20.77%  |
| KDE4            | 19        | 9.18%   |
| X-Cinnamon      | 17        | 8.21%   |
| Unknown         | 16        | 7.73%   |
| XFCE            | 12        | 5.8%    |
| KDE6            | 9         | 4.35%   |
| LXQt            | 3         | 1.45%   |
| Cinnamon        | 3         | 1.45%   |
| MATE            | 2         | 0.97%   |
| sway            | 1         | 0.48%   |
| Pantheon        | 1         | 0.48%   |
| KDE             | 1         | 0.48%   |
| i3              | 1         | 0.48%   |
| Hyprland        | 1         | 0.48%   |
| GNOME Flashback | 1         | 0.48%   |
| Budgie          | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 129       | 62.62%  |
| Wayland | 64        | 31.07%  |
| Unknown | 13        | 6.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 72        | 34.62%  |
| SDDM    | 35        | 16.83%  |
| GDM     | 31        | 14.9%   |
| GDM3    | 24        | 11.54%  |
| LightDM | 21        | 10.1%   |
| KDM     | 19        | 9.13%   |
| TDM     | 6         | 2.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 92        | 45.1%   |
| ru_RU   | 46        | 22.55%  |
| Unknown | 41        | 20.1%   |
| ro_RO   | 8         | 3.92%   |
| C       | 8         | 3.92%   |
| en_GB   | 3         | 1.47%   |
| uk_UA   | 1         | 0.49%   |
| ru_UA   | 1         | 0.49%   |
| nl_NL   | 1         | 0.49%   |
| it_IT   | 1         | 0.49%   |
| en_150  | 1         | 0.49%   |
| de_DE   | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 116       | 56.86%  |
| BIOS | 88        | 43.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 138       | 67.65%  |
| Btrfs   | 26        | 12.75%  |
| Unknown | 16        | 7.84%   |
| Overlay | 13        | 6.37%   |
| Tmpfs   | 9         | 4.41%   |
| Xfs     | 2         | 0.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 99        | 48.53%  |
| Unknown | 75        | 36.76%  |
| MBR     | 30        | 14.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 186       | 91.18%  |
| Yes       | 18        | 8.82%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 152       | 74.15%  |
| Yes       | 53        | 25.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 50        | 24.75%  |
| ASUSTek Computer    | 49        | 24.26%  |
| Hewlett-Packard     | 37        | 18.32%  |
| Dell                | 17        | 8.42%   |
| Acer                | 15        | 7.43%   |
| Timi                | 6         | 2.97%   |
| Toshiba             | 5         | 2.48%   |
| Samsung Electronics | 5         | 2.48%   |
| Sony                | 3         | 1.49%   |
| Valve               | 2         | 0.99%   |
| MSI                 | 2         | 0.99%   |
| Apple               | 2         | 0.99%   |
| XIAOMI              | 1         | 0.5%    |
| System76            | 1         | 0.5%    |
| Medion              | 1         | 0.5%    |
| Jumper              | 1         | 0.5%    |
| HUAWEI              | 1         | 0.5%    |
| Google              | 1         | 0.5%    |
| Gateway             | 1         | 0.5%    |
| Chuwi               | 1         | 0.5%    |
| Unknown             | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Timi TM1701                                 | 3         | 1.49%   |
| ASUS VivoBook_ASUSLaptop X521IA_D533IA      | 3         | 1.49%   |
| ASUS ASUS Vivobook S 16 S5606MA_S5606MA     | 3         | 1.49%   |
| Timi A35S                                   | 2         | 0.99%   |
| Samsung RV413/RV513                         | 2         | 0.99%   |
| Lenovo Legion Y530-15ICH 81FV               | 2         | 0.99%   |
| Lenovo Legion 5 15IMH05 82AU                | 2         | 0.99%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5            | 2         | 0.99%   |
| Lenovo IdeaPad 5 15ARE05 81YQ               | 2         | 0.99%   |
| Lenovo IdeaPad 330-15IKB 81DE               | 2         | 0.99%   |
| HP ProBook 450 G7                           | 2         | 0.99%   |
| HP Compaq Presario CQ60                     | 2         | 0.99%   |
| Dell Inspiron 3593                          | 2         | 0.99%   |
| ASUS VivoBook S15 X510UF                    | 2         | 0.99%   |
| Acer Aspire A515-51G                        | 2         | 0.99%   |
| Unknown                                     | 2         | 0.99%   |
| XIAOMI Redmi Book Pro 15 2023               | 1         | 0.5%    |
| Valve Jupiter                               | 1         | 0.5%    |
| Valve Galileo                               | 1         | 0.5%    |
| Toshiba TECRA Z40-B                         | 1         | 0.5%    |
| Toshiba Satellite S50-B                     | 1         | 0.5%    |
| Toshiba Satellite Pro S300L                 | 1         | 0.5%    |
| Toshiba Satellite C55D-A                    | 1         | 0.5%    |
| Toshiba Satellite A210                      | 1         | 0.5%    |
| Timi A34R                                   | 1         | 0.5%    |
| System76 Adder WS                           | 1         | 0.5%    |
| Sony VPCF13WFX                              | 1         | 0.5%    |
| Sony VPCEB1J8E                              | 1         | 0.5%    |
| Sony SVF1521C5E                             | 1         | 0.5%    |
| Samsung R517/R717                           | 1         | 0.5%    |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B  | 1         | 0.5%    |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.5%    |
| MSI GE60 2PE                                | 1         | 0.5%    |
| MSI CR610                                   | 1         | 0.5%    |
| Medion E15301                               | 1         | 0.5%    |
| Lenovo Z51-70 80K6                          | 1         | 0.5%    |
| Lenovo Yoga Pro 7 14APH8 82Y8               | 1         | 0.5%    |
| Lenovo Y520-15IKBN 80WK                     | 1         | 0.5%    |
| Lenovo V580 20147                           | 1         | 0.5%    |
| Lenovo ThinkPad Yoga 11e 3rd Gen 20G8S0MG00 | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 21        | 10.4%   |
| ASUS VivoBook     | 15        | 7.43%   |
| Lenovo ThinkPad   | 13        | 6.44%   |
| Acer Aspire       | 10        | 4.95%   |
| HP ProBook        | 8         | 3.96%   |
| HP EliteBook      | 8         | 3.96%   |
| Lenovo Legion     | 7         | 3.47%   |
| Dell Inspiron     | 7         | 3.47%   |
| Dell Latitude     | 6         | 2.97%   |
| HP Pavilion       | 5         | 2.48%   |
| ASUS ASUS         | 5         | 2.48%   |
| Toshiba Satellite | 4         | 1.98%   |
| HP Compaq         | 4         | 1.98%   |
| ASUS ROG          | 4         | 1.98%   |
| Timi TM1701       | 3         | 1.49%   |
| HP Laptop         | 3         | 1.49%   |
| HP 250            | 3         | 1.49%   |
| Dell Vostro       | 3         | 1.49%   |
| Timi A35S         | 2         | 0.99%   |
| Samsung RV413     | 2         | 0.99%   |
| Lenovo ThinkBook  | 2         | 0.99%   |
| HP ENVY           | 2         | 0.99%   |
| ASUS ZenBook      | 2         | 0.99%   |
| Acer Extensa      | 2         | 0.99%   |
| Unknown           | 2         | 0.99%   |
| XIAOMI Redmi      | 1         | 0.5%    |
| Valve Jupiter     | 1         | 0.5%    |
| Valve Galileo     | 1         | 0.5%    |
| Toshiba TECRA     | 1         | 0.5%    |
| Timi A34R         | 1         | 0.5%    |
| System76 Adder    | 1         | 0.5%    |
| Sony VPCF13WFX    | 1         | 0.5%    |
| Sony VPCEB1J8E    | 1         | 0.5%    |
| Sony SVF1521C5E   | 1         | 0.5%    |
| Samsung R517      | 1         | 0.5%    |
| Samsung 300V3A    | 1         | 0.5%    |
| Samsung 300E4C    | 1         | 0.5%    |
| MSI GE60          | 1         | 0.5%    |
| MSI CR610         | 1         | 0.5%    |
| Medion E15301     | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 24        | 11.88%  |
| 2019 | 21        | 10.4%   |
| 2018 | 18        | 8.91%   |
| 2020 | 17        | 8.42%   |
| 2017 | 15        | 7.43%   |
| 2011 | 15        | 7.43%   |
| 2012 | 12        | 5.94%   |
| 2013 | 11        | 5.45%   |
| 2022 | 10        | 4.95%   |
| 2023 | 9         | 4.46%   |
| 2015 | 9         | 4.46%   |
| 2016 | 8         | 3.96%   |
| 2014 | 8         | 3.96%   |
| 2024 | 6         | 2.97%   |
| 2010 | 6         | 2.97%   |
| 2009 | 6         | 2.97%   |
| 2008 | 4         | 1.98%   |
| 2007 | 2         | 0.99%   |
| 2006 | 1         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 202       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 186       | 92.08%  |
| Enabled  | 16        | 7.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 201       | 99.5%   |
| Yes  | 1         | 0.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 53        | 26.24%  |
| 8.01-16.0   | 47        | 23.27%  |
| 3.01-4.0    | 41        | 20.3%   |
| 16.01-24.0  | 27        | 13.37%  |
| 32.01-64.0  | 15        | 7.43%   |
| 1.01-2.0    | 7         | 3.47%   |
| 24.01-32.0  | 5         | 2.48%   |
| 2.01-3.0    | 5         | 2.48%   |
| 64.01-256.0 | 2         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 68        | 32.08%  |
| 2.01-3.0   | 41        | 19.34%  |
| 4.01-8.0   | 35        | 16.51%  |
| 3.01-4.0   | 29        | 13.68%  |
| 0.51-1.0   | 20        | 9.43%   |
| 8.01-16.0  | 13        | 6.13%   |
| 16.01-24.0 | 5         | 2.36%   |
| 24.01-32.0 | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 164       | 81.19%  |
| 2      | 32        | 15.84%  |
| 3      | 5         | 2.48%   |
| 0      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 154       | 76.24%  |
| Yes       | 48        | 23.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 75.37%  |
| No        | 50        | 24.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 200       | 99.01%  |
| No        | 2         | 0.99%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 81.77%  |
| No        | 37        | 18.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Moldova | 202       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Chisinau        | 132       | 64.39%  |
| Tiraspol        | 23        | 11.22%  |
| Bălţi         | 6         | 2.93%   |
| Straseni        | 3         | 1.46%   |
| Floresti        | 3         | 1.46%   |
| Tighina         | 2         | 0.98%   |
| Soroca          | 2         | 0.98%   |
| Orhei           | 2         | 0.98%   |
| Hincesti        | 2         | 0.98%   |
| Congaz          | 2         | 0.98%   |
| Ceadir-Lunga    | 2         | 0.98%   |
| Zaicana         | 1         | 0.49%   |
| Ungheni         | 1         | 0.49%   |
| Tvardița       | 1         | 0.49%   |
| Soldanesti      | 1         | 0.49%   |
| Sofia           | 1         | 0.49%   |
| Sarata-Galbena  | 1         | 0.49%   |
| Rautel          | 1         | 0.49%   |
| Prajila         | 1         | 0.49%   |
| Pociumbeni      | 1         | 0.49%   |
| Nisporeni       | 1         | 0.49%   |
| Mascauti        | 1         | 0.49%   |
| Leova           | 1         | 0.49%   |
| Ilenuta         | 1         | 0.49%   |
| Ialoveni        | 1         | 0.49%   |
| Gangura         | 1         | 0.49%   |
| Floreni         | 1         | 0.49%   |
| Donduseni       | 1         | 0.49%   |
| Criuleni        | 1         | 0.49%   |
| Cricova         | 1         | 0.49%   |
| Crasnoarmeiscoe | 1         | 0.49%   |
| Cosauti         | 1         | 0.49%   |
| Cenac           | 1         | 0.49%   |
| Căușeni       | 1         | 0.49%   |
| Carahasani      | 1         | 0.49%   |
| Cantemir        | 1         | 0.49%   |
| Cahul           | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 46        | 55     | 19.41%  |
| WDC                         | 21        | 23     | 8.86%   |
| Sandisk                     | 21        | 22     | 8.86%   |
| Toshiba                     | 20        | 24     | 8.44%   |
| Seagate                     | 19        | 23     | 8.02%   |
| Hitachi                     | 14        | 15     | 5.91%   |
| Micron Technology           | 13        | 17     | 5.49%   |
| Kingston                    | 12        | 15     | 5.06%   |
| SK hynix                    | 9         | 9      | 3.8%    |
| Unknown                     | 6         | 6      | 2.53%   |
| KIOXIA                      | 6         | 7      | 2.53%   |
| Transcend                   | 4         | 5      | 1.69%   |
| Intel                       | 4         | 6      | 1.69%   |
| Apacer                      | 4         | 4      | 1.69%   |
| Kingston Technology Company | 3         | 3      | 1.27%   |
| HGST                        | 3         | 3      | 1.27%   |
| A-DATA Technology           | 3         | 3      | 1.27%   |
| UMIS                        | 2         | 2      | 0.84%   |
| PNY                         | 2         | 2      | 0.84%   |
| Phison                      | 2         | 3      | 0.84%   |
| Patriot                     | 2         | 3      | 0.84%   |
| Netac                       | 2         | 2      | 0.84%   |
| Intenso                     | 2         | 2      | 0.84%   |
| GOODRAM                     | 2         | 2      | 0.84%   |
| Fujitsu                     | 2         | 2      | 0.84%   |
| ZOTAC                       | 1         | 3      | 0.42%   |
| StoreJet                    | 1         | 1      | 0.42%   |
| SPCC                        | 1         | 1      | 0.42%   |
| Solid State Storage         | 1         | 1      | 0.42%   |
| OCZ                         | 1         | 1      | 0.42%   |
| O2 Micro                    | 1         | 1      | 0.42%   |
| Micron/Crucial Technology   | 1         | 1      | 0.42%   |
| LITEONIT                    | 1         | 1      | 0.42%   |
| Lenovo                      | 1         | 1      | 0.42%   |
| Crucial                     | 1         | 1      | 0.42%   |
| China                       | 1         | 1      | 0.42%   |
| ASMT                        | 1         | 1      | 0.42%   |
| AMD                         | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB                      | 6         | 2.5%    |
| Seagate ST1000LM035-1RK172 1TB                    | 5         | 2.08%   |
| Toshiba MQ04ABF100 1TB                            | 4         | 1.67%   |
| Toshiba MQ01ABD100 1TB                            | 4         | 1.67%   |
| Kingston SHFS37A120G 120GB SSD                    | 4         | 1.67%   |
| Seagate ST500LT012-9WS142 500GB                   | 3         | 1.25%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB             | 3         | 1.25%   |
| SanDisk NVMe SSD Drive 512GB                      | 3         | 1.25%   |
| SanDisk NVMe SSD Drive 1TB                        | 3         | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 1.25%   |
| Samsung MZVLW256HEHP-00000 256GB                  | 3         | 1.25%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                     | 3         | 1.25%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD               | 3         | 1.25%   |
| Hitachi HTS543232A7A384 320GB                     | 3         | 1.25%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 2         | 0.83%   |
| Unknown MMC Card  64GB                            | 2         | 0.83%   |
| Unknown MMC Card  128GB                           | 2         | 0.83%   |
| Transcend TS120GMTS420S 120GB SSD                 | 2         | 0.83%   |
| Toshiba MQ01ACF032 320GB                          | 2         | 0.83%   |
| Toshiba MQ01ABF050 500GB                          | 2         | 0.83%   |
| SK hynix NVMe SSD Drive 256GB                     | 2         | 0.83%   |
| Seagate ST9500325AS 500GB                         | 2         | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 0.83%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB  | 2         | 0.83%   |
| Samsung SSD 980 500GB                             | 2         | 0.83%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 0.83%   |
| Samsung MZVL4512HBLU-00BTW 512GB                  | 2         | 0.83%   |
| Samsung MZALQ256HAJD-000L2 256GB                  | 2         | 0.83%   |
| Netac SSD 256GB                                   | 2         | 0.83%   |
| KIOXIA KBG40ZNV512G 512GB                         | 2         | 0.83%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB           | 2         | 0.83%   |
| Kingston SA400S37240G 240GB SSD                   | 2         | 0.83%   |
| Hitachi HTS547575A9E384 752GB                     | 2         | 0.83%   |
| Hitachi HTS547550A9E384 500GB                     | 2         | 0.83%   |
| Apacer AS340 240GB SSD                            | 2         | 0.83%   |
| ZOTAC ZTSSD-S11-240G-P 240GB                      | 1         | 0.42%   |
| WDC WDS512G1X0C-00ENX0 512GB                      | 1         | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 1         | 0.42%   |
| WDC WD5000LPVX-80V0TT0 500GB                      | 1         | 0.42%   |
| WDC WD5000LPVX-75V0TT0 500GB                      | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 21     | 24.68%  |
| Seagate             | 19        | 23     | 24.68%  |
| Toshiba             | 16        | 20     | 20.78%  |
| Hitachi             | 14        | 15     | 18.18%  |
| HGST                | 3         | 3      | 3.9%    |
| Fujitsu             | 2         | 2      | 2.6%    |
| Unknown             | 1         | 1      | 1.3%    |
| StoreJet            | 1         | 1      | 1.3%    |
| Samsung Electronics | 1         | 1      | 1.3%    |
| ASMT                | 1         | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 15     | 20.34%  |
| Kingston            | 9         | 12     | 15.25%  |
| SanDisk             | 5         | 5      | 8.47%   |
| Transcend           | 4         | 5      | 6.78%   |
| Apacer              | 4         | 4      | 6.78%   |
| Micron Technology   | 3         | 3      | 5.08%   |
| Toshiba             | 2         | 2      | 3.39%   |
| Patriot             | 2         | 3      | 3.39%   |
| Netac               | 2         | 2      | 3.39%   |
| Intenso             | 2         | 2      | 3.39%   |
| GOODRAM             | 2         | 2      | 3.39%   |
| ZOTAC               | 1         | 3      | 1.69%   |
| WDC                 | 1         | 1      | 1.69%   |
| SPCC                | 1         | 1      | 1.69%   |
| PNY                 | 1         | 1      | 1.69%   |
| Phison              | 1         | 1      | 1.69%   |
| OCZ                 | 1         | 1      | 1.69%   |
| LITEONIT            | 1         | 1      | 1.69%   |
| Intel               | 1         | 1      | 1.69%   |
| Crucial             | 1         | 1      | 1.69%   |
| China               | 1         | 1      | 1.69%   |
| AMD                 | 1         | 1      | 1.69%   |
| A-DATA Technology   | 1         | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 92        | 111    | 40.17%  |
| HDD  | 77        | 88     | 33.62%  |
| SSD  | 55        | 69     | 24.02%  |
| MMC  | 5         | 5      | 2.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 119       | 154    | 54.34%  |
| NVMe | 92        | 111    | 42.01%  |
| MMC  | 5         | 5      | 2.28%   |
| SAS  | 3         | 3      | 1.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 92        | 117    | 72.44%  |
| 0.51-1.0   | 32        | 37     | 25.2%   |
| 1.01-2.0   | 3         | 3      | 2.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 62        | 29.11%  |
| 251-500        | 60        | 28.17%  |
| 501-1000       | 34        | 15.96%  |
| 1-20           | 15        | 7.04%   |
| 51-100         | 14        | 6.57%   |
| 1001-2000      | 10        | 4.69%   |
| Unknown        | 10        | 4.69%   |
| 21-50          | 5         | 2.35%   |
| More than 3000 | 3         | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 85        | 39.35%  |
| 21-50     | 41        | 18.98%  |
| 51-100    | 28        | 12.96%  |
| 101-250   | 24        | 11.11%  |
| 251-500   | 16        | 7.41%   |
| 501-1000  | 10        | 4.63%   |
| Unknown   | 10        | 4.63%   |
| 1001-2000 | 2         | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB   | 3         | 3      | 15.79%  |
| Hitachi HTS547575A9E384 752GB     | 2         | 2      | 10.53%  |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 1         | 1      | 5.26%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 5.26%   |
| WDC WD1600BEVS-07RST0 160GB       | 1         | 1      | 5.26%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 5.26%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 5.26%   |
| Seagate ST9320325AS 320GB         | 1         | 1      | 5.26%   |
| Seagate ST500LM030-1RK17D 500GB   | 1         | 1      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 5.26%   |
| SanDisk SD7UB3Q256G1001 256GB SSD | 1         | 1      | 5.26%   |
| Kingston SHFS37A120G 120GB SSD    | 1         | 3      | 5.26%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 5.26%   |
| Fujitsu MHW2080BH PL 80GB         | 1         | 1      | 5.26%   |
| A-DATA Technology SX900 256GB SSD | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 7         | 7      | 36.84%  |
| WDC               | 4         | 4      | 21.05%  |
| Hitachi           | 3         | 3      | 15.79%  |
| Toshiba           | 1         | 1      | 5.26%   |
| SanDisk           | 1         | 1      | 5.26%   |
| Kingston          | 1         | 3      | 5.26%   |
| Fujitsu           | 1         | 1      | 5.26%   |
| A-DATA Technology | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 46.67%  |
| WDC     | 3         | 3      | 20%     |
| Hitachi | 3         | 3      | 20%     |
| Toshiba | 1         | 1      | 6.67%   |
| Fujitsu | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 78.95%  |
| SSD  | 4         | 6      | 21.05%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 100       | 137    | 47.62%  |
| Detected | 90        | 114    | 42.86%  |
| Malfunc  | 19        | 21     | 9.05%   |
| Failed   | 1         | 1      | 0.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 118       | 46.46%  |
| AMD                            | 41        | 16.14%  |
| Samsung Electronics            | 33        | 12.99%  |
| SanDisk                        | 17        | 6.69%   |
| Micron Technology              | 10        | 3.94%   |
| SK hynix                       | 9         | 3.54%   |
| KIOXIA                         | 6         | 2.36%   |
| Kingston Technology Company    | 6         | 2.36%   |
| Union Memory (Shenzhen)        | 2         | 0.79%   |
| Toshiba America Info Systems   | 2         | 0.79%   |
| Phison Electronics             | 2         | 0.79%   |
| Nvidia                         | 2         | 0.79%   |
| Solid State Storage Technology | 1         | 0.39%   |
| Realtek Semiconductor          | 1         | 0.39%   |
| O2 Micro                       | 1         | 0.39%   |
| Micron/Crucial Technology      | 1         | 0.39%   |
| Lenovo                         | 1         | 0.39%   |
| ADATA Technology               | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 32        | 11.9%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 16        | 5.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 5.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 4.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 2.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 2.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 2.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 2.23%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 5         | 1.86%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 1.86%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 1.86%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 4         | 1.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.49%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 1.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.49%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 1.49%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 1.12%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 3         | 1.12%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 3         | 1.12%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.12%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.74%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                     | 2         | 0.74%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 2         | 0.74%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                            | 2         | 0.74%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.74%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.74%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 2         | 0.74%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 2         | 0.74%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                       | 2         | 0.74%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.74%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 144       | 55.17%  |
| NVMe | 92        | 35.25%  |
| RAID | 14        | 5.36%   |
| IDE  | 11        | 4.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 136       | 67.33%  |
| AMD    | 66        | 32.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 2.48%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 2.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.98%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.98%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.98%   |
| Intel Core Ultra 9 185H                       | 3         | 1.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.49%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 1.49%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.49%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.49%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 3         | 1.49%   |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 1.49%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.99%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.99%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.99%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.99%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.99%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 0.99%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 0.99%   |
| Intel 12th Gen Core i5-1235U                  | 2         | 0.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.99%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.99%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.99%   |
| AMD Ryzen 5 7530U with Radeon Graphics        | 2         | 0.99%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 0.99%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.5%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.5%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.5%    |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.5%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.5%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.5%    |
| Intel Pentium CPU B980 @ 2.40GHz              | 1         | 0.5%    |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.5%    |
| Intel N100                                    | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 40        | 19.8%   |
| Intel Core i7                  | 27        | 13.37%  |
| Intel Core i3                  | 19        | 9.41%   |
| AMD Ryzen 7                    | 18        | 8.91%   |
| AMD Ryzen 5                    | 17        | 8.42%   |
| Other                          | 16        | 7.92%   |
| Intel Celeron                  | 16        | 7.92%   |
| Intel Pentium                  | 7         | 3.47%   |
| AMD E                          | 5         | 2.48%   |
| Intel Pentium Silver           | 3         | 1.49%   |
| Intel Core 2 Duo               | 3         | 1.49%   |
| Intel Core                     | 3         | 1.49%   |
| AMD E1                         | 3         | 1.49%   |
| AMD Athlon                     | 3         | 1.49%   |
| Intel Pentium Dual-Core        | 2         | 0.99%   |
| AMD Sempron                    | 2         | 0.99%   |
| AMD Ryzen 9                    | 2         | 0.99%   |
| AMD Ryzen 5 PRO                | 2         | 0.99%   |
| AMD A4                         | 2         | 0.99%   |
| AMD A10                        | 2         | 0.99%   |
| Intel Core i9                  | 1         | 0.5%    |
| Intel Core 2                   | 1         | 0.5%    |
| Intel Atom                     | 1         | 0.5%    |
| AMD V140                       | 1         | 0.5%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.5%    |
| AMD Ryzen 7 PRO                | 1         | 0.5%    |
| AMD Ryzen 3                    | 1         | 0.5%    |
| AMD Athlon 64 X2               | 1         | 0.5%    |
| AMD A8                         | 1         | 0.5%    |
| AMD A6                         | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 87        | 43.07%  |
| 4       | 61        | 30.2%   |
| 8       | 23        | 11.39%  |
| 6       | 20        | 9.9%    |
| 16      | 3         | 1.49%   |
| 10      | 3         | 1.49%   |
| 1       | 2         | 0.99%   |
| 14      | 1         | 0.5%    |
| 12      | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 202       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 141       | 69.8%   |
| 1       | 60        | 29.7%   |
| Unknown | 1         | 0.5%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 199       | 98.51%  |
| Unknown        | 3         | 1.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 42.93%  |
| 0x806ea    | 9         | 4.39%   |
| 0x206a7    | 8         | 3.9%    |
| 0x05000119 | 8         | 3.9%    |
| 0x806ec    | 7         | 3.41%   |
| 0x40651    | 5         | 2.44%   |
| 0x306a9    | 5         | 2.44%   |
| 0x906ea    | 4         | 1.95%   |
| 0x406e3    | 4         | 1.95%   |
| 0x306c3    | 4         | 1.95%   |
| 0x08600106 | 4         | 1.95%   |
| 0xa0652    | 3         | 1.46%   |
| 0x806e9    | 3         | 1.46%   |
| 0x706a1    | 3         | 1.46%   |
| 0x506c9    | 3         | 1.46%   |
| 0x406c4    | 3         | 1.46%   |
| 0x306d4    | 3         | 1.46%   |
| 0x0a50000c | 3         | 1.46%   |
| 0x806c1    | 2         | 0.98%   |
| 0x706e5    | 2         | 0.98%   |
| 0x30678    | 2         | 0.98%   |
| 0x08608103 | 2         | 0.98%   |
| 0x08108109 | 2         | 0.98%   |
| 0x08108102 | 2         | 0.98%   |
| 0x06001119 | 2         | 0.98%   |
| 0x03000027 | 2         | 0.98%   |
| 0x02000057 | 2         | 0.98%   |
| 0x906e9    | 1         | 0.49%   |
| 0x906a4    | 1         | 0.49%   |
| 0x806d1    | 1         | 0.49%   |
| 0x706a8    | 1         | 0.49%   |
| 0x6fd      | 1         | 0.49%   |
| 0x6fb      | 1         | 0.49%   |
| 0x406c3    | 1         | 0.49%   |
| 0x20655    | 1         | 0.49%   |
| 0x20652    | 1         | 0.49%   |
| 0x106e5    | 1         | 0.49%   |
| 0x106ca    | 1         | 0.49%   |
| 0x1067a    | 1         | 0.49%   |
| 0x0a50000d | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 35        | 17.24%  |
| Unknown           | 15        | 7.39%   |
| Zen 3             | 14        | 6.9%    |
| SandyBridge       | 12        | 5.91%   |
| Zen 2             | 11        | 5.42%   |
| Haswell           | 11        | 5.42%   |
| Zen+              | 9         | 4.43%   |
| Silvermont        | 8         | 3.94%   |
| IvyBridge         | 8         | 3.94%   |
| Bobcat            | 8         | 3.94%   |
| IceLake           | 7         | 3.45%   |
| Goldmont plus     | 7         | 3.45%   |
| Broadwell         | 6         | 2.96%   |
| TigerLake         | 5         | 2.46%   |
| Skylake           | 5         | 2.46%   |
| CometLake         | 5         | 2.46%   |
| Alderlake Hybrid  | 5         | 2.46%   |
| Westmere          | 4         | 1.97%   |
| Goldmont          | 4         | 1.97%   |
| Core              | 4         | 1.97%   |
| Piledriver        | 3         | 1.48%   |
| Meteorlake Hybrid | 3         | 1.48%   |
| K8 & K10 hybrid   | 3         | 1.48%   |
| Penryn            | 2         | 0.99%   |
| K10 Llano         | 2         | 0.99%   |
| K10               | 2         | 0.99%   |
| Zen               | 1         | 0.49%   |
| Puma              | 1         | 0.49%   |
| Nehalem           | 1         | 0.49%   |
| K8 Hammer         | 1         | 0.49%   |
| Bonnell           | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 130       | 50.78%  |
| AMD    | 71        | 27.73%  |
| Nvidia | 55        | 21.48%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 13        | 5.02%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 4.63%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 11        | 4.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 3.47%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 3.09%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 2.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 2.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.32%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 6         | 2.32%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 1.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.93%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 5         | 1.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.93%   |
| AMD Barcelo                                                                              | 5         | 1.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.54%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.54%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 4         | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.16%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                                 | 3         | 1.16%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.16%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.16%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 3         | 1.16%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 3         | 1.16%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 1.16%   |
| AMD Phoenix1                                                                             | 3         | 1.16%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.77%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.77%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.77%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 0.77%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                          | 2         | 0.77%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 2         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 84        | 41.58%  |
| 1 x AMD        | 55        | 27.23%  |
| Intel + Nvidia | 40        | 19.8%   |
| AMD + Nvidia   | 9         | 4.46%   |
| 1 x Nvidia     | 6         | 2.97%   |
| Intel + AMD    | 5         | 2.48%   |
| 2 x AMD        | 2         | 0.99%   |
| Other          | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 173       | 84.39%  |
| Proprietary | 20        | 9.76%   |
| Unknown     | 12        | 5.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 116       | 56.04%  |
| 0.01-0.5   | 40        | 19.32%  |
| 1.01-2.0   | 33        | 15.94%  |
| 3.01-4.0   | 11        | 5.31%   |
| 0.51-1.0   | 5         | 2.42%   |
| 7.01-8.0   | 1         | 0.48%   |
| 5.01-6.0   | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 19.56%  |
| Chimei Innolux          | 35        | 15.56%  |
| BOE                     | 32        | 14.22%  |
| LG Display              | 27        | 12%     |
| Samsung Electronics     | 23        | 10.22%  |
| Philips                 | 9         | 4%      |
| Dell                    | 8         | 3.56%   |
| Lenovo                  | 6         | 2.67%   |
| Chi Mei Optoelectronics | 6         | 2.67%   |
| PANDA                   | 5         | 2.22%   |
| InfoVision              | 4         | 1.78%   |
| CSO                     | 4         | 1.78%   |
| Sharp                   | 3         | 1.33%   |
| AOC                     | 3         | 1.33%   |
| Valve                   | 2         | 0.89%   |
| TMX                     | 2         | 0.89%   |
| Goldstar                | 2         | 0.89%   |
| Apple                   | 2         | 0.89%   |
| Sony                    | 1         | 0.44%   |
| Mi                      | 1         | 0.44%   |
| ITE                     | 1         | 0.44%   |
| GreenWood               | 1         | 0.44%   |
| CSOT                    | 1         | 0.44%   |
| CPT                     | 1         | 0.44%   |
| BenQ                    | 1         | 0.44%   |
| Acer                    | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 6         | 2.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 2.19%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4178 3200x2000 344x215mm 16.0-inch | 3         | 1.32%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 3         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 3         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.32%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 1.32%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 3         | 1.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch | 2         | 0.88%   |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                    | 2         | 0.88%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.88%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 0.88%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                     | 2         | 0.88%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 0.88%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                 | 2         | 0.88%   |
| BOE LCD Monitor BOE07F7 1920x1080 309x174mm 14.0-inch                 | 2         | 0.88%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 0.88%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 0.88%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                   | 1         | 0.44%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.44%   |
| TMX TL156MDMP31-0 TMX2005 3200x2000 336x210mm 15.6-inch               | 1         | 0.44%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.44%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                         | 1         | 0.44%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP13CF 1280x800 331x207mm 15.4-inch                | 1         | 0.44%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM0214 1680x1050 408x306mm 20.1-inch  | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.44%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch    | 1         | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.44%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch   | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 97        | 45.97%  |
| 1366x768 (WXGA)    | 58        | 27.49%  |
| 2560x1440 (QHD)    | 10        | 4.74%   |
| 1600x900 (HD+)     | 10        | 4.74%   |
| 2560x1600          | 6         | 2.84%   |
| 1920x1200 (WUXGA)  | 6         | 2.84%   |
| 1280x800 (WXGA)    | 5         | 2.37%   |
| 3200x2000          | 4         | 1.9%    |
| 3840x2160 (4K)     | 3         | 1.42%   |
| 800x1280           | 2         | 0.95%   |
| 3456x2160          | 2         | 0.95%   |
| 1680x1050 (WSXGA+) | 2         | 0.95%   |
| 2880x1800          | 1         | 0.47%   |
| 2880x1620          | 1         | 0.47%   |
| 2160x1440          | 1         | 0.47%   |
| 1280x1024 (SXGA)   | 1         | 0.47%   |
| 1024x768 (XGA)     | 1         | 0.47%   |
| 1024x600           | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 128       | 56.39%  |
| 14     | 21        | 9.25%   |
| 16     | 12        | 5.29%   |
| 13     | 12        | 5.29%   |
| 24     | 9         | 3.96%   |
| 17     | 9         | 3.96%   |
| 27     | 7         | 3.08%   |
| 23     | 7         | 3.08%   |
| 21     | 6         | 2.64%   |
| 11     | 4         | 1.76%   |
| 31     | 2         | 0.88%   |
| 12     | 2         | 0.88%   |
| 7      | 2         | 0.88%   |
| 72     | 1         | 0.44%   |
| 52     | 1         | 0.44%   |
| 22     | 1         | 0.44%   |
| 20     | 1         | 0.44%   |
| 19     | 1         | 0.44%   |
| 10     | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 166       | 73.78%  |
| 501-600     | 20        | 8.89%   |
| 201-300     | 13        | 5.78%   |
| 351-400     | 11        | 4.89%   |
| 401-500     | 8         | 3.56%   |
| 601-700     | 3         | 1.33%   |
| 1-100       | 2         | 0.89%   |
| 1501-2000   | 1         | 0.44%   |
| 1001-1500   | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 168       | 84.42%  |
| 16/10 | 25        | 12.56%  |
| 4/3   | 2         | 1.01%   |
| 5/4   | 1         | 0.5%    |
| 3/2   | 1         | 0.5%    |
| 0.67  | 1         | 0.5%    |
| 0.62  | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 128       | 56.39%  |
| 81-90          | 29        | 12.78%  |
| 201-250        | 19        | 8.37%   |
| 111-120        | 12        | 5.29%   |
| 301-350        | 7         | 3.08%   |
| 121-130        | 7         | 3.08%   |
| 51-60          | 4         | 1.76%   |
| 151-200        | 4         | 1.76%   |
| 71-80          | 3         | 1.32%   |
| More than 1000 | 2         | 0.88%   |
| 61-70          | 2         | 0.88%   |
| 351-500        | 2         | 0.88%   |
| 1-40           | 2         | 0.88%   |
| 251-300        | 2         | 0.88%   |
| 131-140        | 2         | 0.88%   |
| 41-50          | 1         | 0.44%   |
| 91-100         | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 103       | 46.4%   |
| 101-120       | 63        | 28.38%  |
| 51-100        | 30        | 13.51%  |
| 161-240       | 19        | 8.56%   |
| More than 240 | 5         | 2.25%   |
| 1-50          | 2         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 169       | 82.84%  |
| 2     | 29        | 14.22%  |
| 3     | 3         | 1.47%   |
| 0     | 3         | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 123       | 38.68%  |
| Intel                             | 76        | 23.9%   |
| Qualcomm Atheros                  | 51        | 16.04%  |
| Broadcom                          | 16        | 5.03%   |
| MediaTek                          | 15        | 4.72%   |
| Ralink                            | 5         | 1.57%   |
| ASIX Electronics                  | 4         | 1.26%   |
| Xiaomi                            | 3         | 0.94%   |
| JMicron Technology                | 3         | 0.94%   |
| Huawei Technologies               | 3         | 0.94%   |
| Broadcom Limited                  | 3         | 0.94%   |
| TP-Link                           | 2         | 0.63%   |
| Nvidia                            | 2         | 0.63%   |
| Marvell Technology Group          | 2         | 0.63%   |
| Wacom                             | 1         | 0.31%   |
| Sierra Wireless                   | 1         | 0.31%   |
| Shenzhen Goodix Technology        | 1         | 0.31%   |
| Ralink Technology                 | 1         | 0.31%   |
| Qualcomm                          | 1         | 0.31%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.31%   |
| ICS Advent                        | 1         | 0.31%   |
| Hewlett-Packard                   | 1         | 0.31%   |
| Ericsson Business Mobile Networks | 1         | 0.31%   |
| Unknown                           | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 77        | 20.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 24        | 6.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 3.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 2.69%   |
| Intel Wireless 8265 / 8275                                              | 10        | 2.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.15%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.61%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 6         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.34%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.34%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.34%   |
| Intel Wireless 7260                                                     | 4         | 1.08%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.08%   |
| Intel Ethernet Connection I218-LM                                       | 4         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                           | 4         | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 3         | 0.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.81%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 3         | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 3         | 0.81%   |
| Intel Wireless 3165                                                     | 3         | 0.81%   |
| Intel Wireless 3160                                                     | 3         | 0.81%   |
| Intel Meteor Lake PCH CNVi WiFi                                         | 3         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 0.81%   |
| Huawei E353/E3131                                                       | 3         | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 0.54%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 35.44%  |
| Qualcomm Atheros      | 48        | 23.3%   |
| Realtek Semiconductor | 45        | 21.84%  |
| MediaTek              | 14        | 6.8%    |
| Broadcom              | 13        | 6.31%   |
| Ralink                | 5         | 2.43%   |
| TP-Link               | 2         | 0.97%   |
| Wacom                 | 1         | 0.49%   |
| Sierra Wireless       | 1         | 0.49%   |
| Ralink Technology     | 1         | 0.49%   |
| Qualcomm              | 1         | 0.49%   |
| Broadcom Limited      | 1         | 0.49%   |
| Unknown               | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 6.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 6.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 4.85%   |
| Intel Wireless 8265 / 8275                                              | 10        | 4.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 4.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.88%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 3.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.91%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 6         | 2.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.43%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 2.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.43%   |
| Intel Wireless 7260                                                     | 4         | 1.94%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.94%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.46%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.46%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 3         | 1.46%   |
| Intel Wireless 3165                                                     | 3         | 1.46%   |
| Intel Wireless 3160                                                     | 3         | 1.46%   |
| Intel Meteor Lake PCH CNVi WiFi                                         | 3         | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.97%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.97%   |
| Intel Wireless 8260                                                     | 2         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.97%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.97%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.97%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 104       | 65.41%  |
| Intel                    | 23        | 14.47%  |
| Qualcomm Atheros         | 5         | 3.14%   |
| Broadcom                 | 5         | 3.14%   |
| ASIX Electronics         | 4         | 2.52%   |
| Xiaomi                   | 3         | 1.89%   |
| JMicron Technology       | 3         | 1.89%   |
| Huawei Technologies      | 3         | 1.89%   |
| Nvidia                   | 2         | 1.26%   |
| Marvell Technology Group | 2         | 1.26%   |
| Broadcom Limited         | 2         | 1.26%   |
| MediaTek                 | 1         | 0.63%   |
| ICS Advent               | 1         | 0.63%   |
| Hewlett-Packard          | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 77        | 47.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 24        | 14.72%  |
| Intel Ethernet Connection I218-LM                                              | 4         | 2.45%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 2.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 1.84%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 1.84%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.84%   |
| Huawei E353/E3131                                                              | 3         | 1.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.23%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 1.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.23%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.23%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                    | 1         | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.61%   |
| MediaTek Infinix HOT 50i                                                       | 1         | 0.61%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.61%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.61%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.61%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.61%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.61%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.61%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.61%   |
| Intel Ethernet Connection (23) I219-V                                          | 1         | 0.61%   |
| Intel Ethernet Connection (16) I219-V                                          | 1         | 0.61%   |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 0.61%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.61%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.61%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.61%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.61%   |
| HP HP lt4120 Snapdragon X5 LTE                                                 | 1         | 0.61%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.61%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 200       | 56.34%  |
| Ethernet | 152       | 42.82%  |
| Modem    | 2         | 0.56%   |
| Unknown  | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 161       | 77.4%   |
| Ethernet | 47        | 22.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 142       | 70.3%   |
| 1     | 60        | 29.7%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 191       | 94.55%  |
| Yes  | 11        | 5.45%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 36.75%  |
| Realtek Semiconductor           | 24        | 14.46%  |
| IMC Networks                    | 24        | 14.46%  |
| Qualcomm Atheros Communications | 18        | 10.84%  |
| Foxconn / Hon Hai               | 12        | 7.23%   |
| Lite-On Technology              | 7         | 4.22%   |
| Broadcom                        | 7         | 4.22%   |
| Ralink Technology               | 2         | 1.2%    |
| ASUSTek Computer                | 2         | 1.2%    |
| Apple                           | 2         | 1.2%    |
| Toshiba                         | 1         | 0.6%    |
| Realtek                         | 1         | 0.6%    |
| Ralink                          | 1         | 0.6%    |
| MediaTek                        | 1         | 0.6%    |
| Hewlett-Packard                 | 1         | 0.6%    |
| Dell                            | 1         | 0.6%    |
| Cambridge Silicon Radio         | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 21        | 12.65%  |
| Realtek Bluetooth Radio                           | 17        | 10.24%  |
| Intel AX201 Bluetooth                             | 13        | 7.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 10        | 6.02%   |
| IMC Networks Bluetooth Radio                      | 10        | 6.02%   |
| Qualcomm Atheros  Bluetooth Device                | 9         | 5.42%   |
| Intel AX200 Bluetooth                             | 7         | 4.22%   |
| Intel Bluetooth Device                            | 5         | 3.01%   |
| IMC Networks Wireless_Device                      | 5         | 3.01%   |
| IMC Networks Bluetooth Device                     | 5         | 3.01%   |
| Foxconn / Hon Hai Wireless_Device                 | 5         | 3.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 4         | 2.41%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter      | 4         | 2.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 3         | 1.81%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 3         | 1.81%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 2         | 1.2%    |
| Realtek RTL8723B Bluetooth                        | 2         | 1.2%    |
| Realtek  Bluetooth 4.2 Adapter                    | 2         | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 2         | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                 | 2         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth                  | 2         | 1.2%    |
| Broadcom HP Portable SoftSailing                  | 2         | 1.2%    |
| Broadcom BCM20702A0                               | 2         | 1.2%    |
| ASUS BT-270 Bluetooth Adapter                     | 2         | 1.2%    |
| Toshiba Integrated Bluetooth HCI                  | 1         | 0.6%    |
| Realtek RTL8821A Bluetooth                        | 1         | 0.6%    |
| Realtek Bluetooth Radio                           | 1         | 0.6%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 0.6%    |
| Ralink CSR BS8510                                 | 1         | 0.6%    |
| Ralink RT3290 Bluetooth                           | 1         | 0.6%    |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth                 | 1         | 0.6%    |
| MediaTek Wireless_Device                          | 1         | 0.6%    |
| Lite-On Bluetooth Radio                           | 1         | 0.6%    |
| Lite-On Bluetooth Device                          | 1         | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.6%    |
| Intel Centrino Bluetooth Wireless Transceiver     | 1         | 0.6%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.6%    |
| Intel AX210 Bluetooth                             | 1         | 0.6%    |
| IMC Networks Bluetooth Module                     | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 136       | 57.14%  |
| AMD                     | 66        | 27.73%  |
| Nvidia                  | 27        | 11.34%  |
| Plantronics             | 2         | 0.84%   |
| Logitech                | 2         | 0.84%   |
| Sony                    | 1         | 0.42%   |
| DSEA A/S                | 1         | 0.42%   |
| Creative Technology     | 1         | 0.42%   |
| BEHRINGER International | 1         | 0.42%   |
| ASUSTek Computer        | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 44        | 14.19%  |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 25        | 8.06%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 7.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 4.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 2.9%    |
| AMD FCH Azalia Controller                                                                         | 9         | 2.9%    |
| AMD Wrestler HDMI Audio                                                                           | 8         | 2.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.58%   |
| AMD Radeon High Definition Audio Controller                                                       | 8         | 2.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 2.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.94%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.94%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.61%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.61%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 1.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.29%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.97%   |
| Intel Meteor Lake-P HD Audio Controller                                                           | 3         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 0.97%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.65%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.65%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 2         | 0.65%   |
| Logitech H600 [Wireless Headset]                                                                  | 2         | 0.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 33.96%  |
| SK hynix            | 32        | 20.13%  |
| Micron Technology   | 17        | 10.69%  |
| Kingston            | 12        | 7.55%   |
| Unknown             | 9         | 5.66%   |
| Goodram             | 6         | 3.77%   |
| Transcend           | 5         | 3.14%   |
| Ramaxel Technology  | 3         | 1.89%   |
| Unknown             | 3         | 1.89%   |
| Unknown (ABCD)      | 2         | 1.26%   |
| Elpida              | 2         | 1.26%   |
| Crucial             | 2         | 1.26%   |
| ASint Technology    | 2         | 1.26%   |
| Apacer              | 2         | 1.26%   |
| A-DATA Technology   | 2         | 1.26%   |
| Wilk                | 1         | 0.63%   |
| Unifosa             | 1         | 0.63%   |
| Nanya Technology    | 1         | 0.63%   |
| Corsair             | 1         | 0.63%   |
| Axiom               | 1         | 0.63%   |
| Avant               | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.8%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.8%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.8%    |
| Samsung RAM K3KL8L80CM-MGCT 2GB Row Of Chips LPDDR5 7500MT/s     | 3         | 1.8%    |
| Unknown                                                          | 3         | 1.8%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 1.2%    |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 2         | 1.2%    |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                    | 2         | 1.2%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.2%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.2%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.2%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 1.2%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.2%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 2         | 1.2%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.2%    |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM 1067MT/s                 | 2         | 1.2%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.2%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.2%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.2%    |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s          | 2         | 1.2%    |
| Wilk RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s             | 1         | 0.6%    |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR2 400MT/s                    | 1         | 0.6%    |
| Unknown RAM Module 1GB SODIMM LPDDR4 2400MT/s                    | 1         | 0.6%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.6%    |
| Unifosa RAM GU672203EP0200 1GB SODIMM DDR3 1333MT/s              | 1         | 0.6%    |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s               | 1         | 0.6%    |
| Transcend RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 0.6%    |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 1         | 0.6%    |
| Transcend RAM JM3200HSE-16G 16GB SODIMM DDR4 3200MT/s            | 1         | 0.6%    |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 1         | 0.6%    |
| SK hynix RAM Module 32GB SODIMM DDR4 2667MT/s                    | 1         | 0.6%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 2048MT/s           | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 63        | 45.99%  |
| DDR3   | 46        | 33.58%  |
| LPDDR5 | 6         | 4.38%   |
| LPDDR4 | 6         | 4.38%   |
| SDRAM  | 4         | 2.92%   |
| DDR5   | 4         | 2.92%   |
| DDR2   | 4         | 2.92%   |
| LPDDR3 | 2         | 1.46%   |
| DRAM   | 2         | 1.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 116       | 87.22%  |
| Row Of Chips | 17        | 12.78%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 56        | 37.58%  |
| 4096  | 41        | 27.52%  |
| 2048  | 20        | 13.42%  |
| 16384 | 18        | 12.08%  |
| 1024  | 9         | 6.04%   |
| 32768 | 5         | 3.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 30        | 20.98%  |
| 3200    | 29        | 20.28%  |
| 2667    | 29        | 20.28%  |
| 2400    | 11        | 7.69%   |
| 1334    | 5         | 3.5%    |
| 1333    | 5         | 3.5%    |
| 7500    | 4         | 2.8%    |
| 4800    | 4         | 2.8%    |
| Unknown | 4         | 2.8%    |
| 667     | 3         | 2.1%    |
| 6400    | 2         | 1.4%    |
| 4199    | 2         | 1.4%    |
| 3266    | 2         | 1.4%    |
| 2133    | 2         | 1.4%    |
| 2048    | 2         | 1.4%    |
| 1067    | 2         | 1.4%    |
| 400     | 2         | 1.4%    |
| 8400    | 1         | 0.7%    |
| 5600    | 1         | 0.7%    |
| 1867    | 1         | 0.7%    |
| 1866    | 1         | 0.7%    |
| 975     | 1         | 0.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon iP7200 series | 1         | 100%    |

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
| Chicony Electronics                    | 38        | 20.77%  |
| IMC Networks                           | 31        | 16.94%  |
| Realtek Semiconductor                  | 17        | 9.29%   |
| Quanta                                 | 13        | 7.1%    |
| Syntek                                 | 10        | 5.46%   |
| Microdia                               | 10        | 5.46%   |
| Bison Electronics                      | 10        | 5.46%   |
| Shinetech                              | 7         | 3.83%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.83%   |
| Lite-On Technology                     | 5         | 2.73%   |
| Sunplus Innovation Technology          | 4         | 2.19%   |
| Sonix Technology                       | 4         | 2.19%   |
| Silicon Motion                         | 4         | 2.19%   |
| Luxvisions Innotech Limited            | 4         | 2.19%   |
| Suyin                                  | 3         | 1.64%   |
| Apple                                  | 3         | 1.64%   |
| Alcor Micro                            | 2         | 1.09%   |
| Z-Star Microelectronics                | 1         | 0.55%   |
| YGTek                                  | 1         | 0.55%   |
| Y Media                                | 1         | 0.55%   |
| SunplusIT                              | 1         | 0.55%   |
| Samsung Electronics                    | 1         | 0.55%   |
| Ricoh                                  | 1         | 0.55%   |
| Primax Electronics                     | 1         | 0.55%   |
| Logitech                               | 1         | 0.55%   |
| Importek                               | 1         | 0.55%   |
| ezcap                                  | 1         | 0.55%   |
| ALi                                    | 1         | 0.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 9         | 4.92%   |
| Syntek Integrated Camera                                     | 7         | 3.83%   |
| IMC Networks USB2.0 VGA UVC WebCam                           | 7         | 3.83%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 7         | 3.83%   |
| IMC Networks Integrated Camera                               | 5         | 2.73%   |
| Shinetech USB2.0 FHD UVC WebCam                              | 4         | 2.19%   |
| Realtek Integrated_Webcam_HD                                 | 4         | 2.19%   |
| Quanta HP TrueVision HD Camera                               | 4         | 2.19%   |
| Microdia Integrated_Webcam_HD                                | 4         | 2.19%   |
| Syntek Lenovo EasyCamera                                     | 3         | 1.64%   |
| Sonix USB2.0 HD UVC WebCam                                   | 3         | 1.64%   |
| ShineTech USB2.0 HD UVC WebCam                               | 3         | 1.64%   |
| Quanta HP HD Camera                                          | 3         | 1.64%   |
| Lite-On HP HD Webcam                                         | 3         | 1.64%   |
| IMC Networks Integrated Webcam                               | 3         | 1.64%   |
| Chicony HD WebCam                                            | 3         | 1.64%   |
| Chicony EasyCamera                                           | 3         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 3         | 1.64%   |
| Bison Integrated Camera                                      | 3         | 1.64%   |
| Silicon Motion WebCam SC-0311139N                            | 2         | 1.09%   |
| Realtek USB Camera                                           | 2         | 1.09%   |
| Realtek EasyCamera                                           | 2         | 1.09%   |
| Quanta HD Webcam                                             | 2         | 1.09%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 2         | 1.09%   |
| Lite-On HP HD Camera                                         | 2         | 1.09%   |
| IMC Networks XiaoMi Webcam                                   | 2         | 1.09%   |
| IMC Networks VGA UVC WebCam                                  | 2         | 1.09%   |
| Chicony VGA WebCam                                           | 2         | 1.09%   |
| Chicony USB2.0 VGA UVC WebCam                                | 2         | 1.09%   |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 1.09%   |
| Bison SunplusIT Integrated Camera                            | 2         | 1.09%   |
| Apple FaceTime HD Camera                                     | 2         | 1.09%   |
| Z-Star WebCam SCB-0320N                                      | 1         | 0.55%   |
| YGTek Webcam                                                 | 1         | 0.55%   |
| Y Media USB Camera                                           | 1         | 0.55%   |
| Suyin HP Webcam                                              | 1         | 0.55%   |
| Suyin HP Truevision HD                                       | 1         | 0.55%   |
| Suyin HD WebCam                                              | 1         | 0.55%   |
| SunplusIT XiaoMi USB 2.0 Webcam                              | 1         | 0.55%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 33.33%  |
| Synaptics                  | 9         | 27.27%  |
| Elan Microelectronics      | 5         | 15.15%  |
| Shenzhen Goodix Technology | 4         | 12.12%  |
| Upek                       | 2         | 6.06%   |
| LighTuning Technology      | 1         | 3.03%   |
| AuthenTec                  | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 4         | 12.12%  |
| Shenzhen Goodix  FingerPrint Device                       | 4         | 12.12%  |
| Validity Sensors VFS495 Fingerprint Reader                | 3         | 9.09%   |
| Elan ELAN:Fingerprint                                     | 3         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 2         | 6.06%   |
| Validity Sensors Fingerprint scanner                      | 2         | 6.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 6.06%   |
| Synaptics Fingerprint reader [HP G6]                      | 2         | 6.06%   |
| Elan ELAN:ARM-M4                                          | 2         | 6.06%   |
| Validity Sensors VFS491                                   | 1         | 3.03%   |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 3.03%   |
| Validity Sensors Synaptics WBDI                           | 1         | 3.03%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 3.03%   |
| Synaptics UWP WBDI Device                                 | 1         | 3.03%   |
| Synaptics TouchPad                                        | 1         | 3.03%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 1         | 3.03%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 33.33%  |
| O2 Micro              | 1         | 33.33%  |
| Broadcom              | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1         | 33.33%  |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 33.33%  |
| Broadcom 5880                                     | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 137       | 66.5%   |
| 1     | 56        | 27.18%  |
| 2     | 12        | 5.83%   |
| 3     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 33        | 43.42%  |
| Graphics card         | 23        | 30.26%  |
| Net/wireless          | 8         | 10.53%  |
| Multimedia controller | 3         | 3.95%   |
| Sound                 | 2         | 2.63%   |
| Chipcard              | 2         | 2.63%   |
| Camera                | 2         | 2.63%   |
| Storage               | 1         | 1.32%   |
| Card reader           | 1         | 1.32%   |
| Bluetooth             | 1         | 1.32%   |

