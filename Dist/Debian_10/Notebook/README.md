Debian 10 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 10.

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

Total: 1295

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | SATE                        | [051e444724](https://linux-hardware.org/?probe=051e444724) | Dec 04, 2025 |
| Sony          | SVE1511A1EW                 | [b3f7144ad3](https://linux-hardware.org/?probe=b3f7144ad3) | Nov 22, 2025 |
| Sony          | SVE1511A1EW                 | [8b078f1b51](https://linux-hardware.org/?probe=8b078f1b51) | Nov 22, 2025 |
| Toshiba       | Satellite A215              | [734669d678](https://linux-hardware.org/?probe=734669d678) | Aug 30, 2025 |
| Acer          | AOD257                      | [06fd17894b](https://linux-hardware.org/?probe=06fd17894b) | Jul 27, 2025 |
| Dell          | Latitude E4310              | [0726bf9666](https://linux-hardware.org/?probe=0726bf9666) | Jun 19, 2025 |
| TrekStor      | MiniPC W3                   | [1977c91c5b](https://linux-hardware.org/?probe=1977c91c5b) | Mar 27, 2025 |
| Gateway       | M675PRR                     | [8aacba1dc6](https://linux-hardware.org/?probe=8aacba1dc6) | Mar 23, 2025 |
| HP            | Pavilion 11 x360 PC         | [a244ea9f8b](https://linux-hardware.org/?probe=a244ea9f8b) | Mar 23, 2025 |
| HP            | Pavilion Sleekbook 14 PC    | [49fa15d74f](https://linux-hardware.org/?probe=49fa15d74f) | Mar 23, 2025 |
| HP            | Pavilion dv6000 (GA378UA... | [5c80bc4f89](https://linux-hardware.org/?probe=5c80bc4f89) | Mar 08, 2025 |
| HP            | Pavilion dv6000 (GA378UA... | [2b3d9f3c42](https://linux-hardware.org/?probe=2b3d9f3c42) | Mar 08, 2025 |
| ASUSTek       | K53SC                       | [459b2b79f2](https://linux-hardware.org/?probe=459b2b79f2) | Feb 15, 2025 |
| Acer          | Aspire 4745Z                | [56367d760b](https://linux-hardware.org/?probe=56367d760b) | Feb 06, 2025 |
| Lenovo        | G505s 20255                 | [d9bacf1c6e](https://linux-hardware.org/?probe=d9bacf1c6e) | Jan 22, 2025 |
| ASUSTek       | K53SC                       | [60a52cbc6f](https://linux-hardware.org/?probe=60a52cbc6f) | Dec 01, 2024 |
| Polaroid      | MP1464PR001                 | [3abfe5c9f6](https://linux-hardware.org/?probe=3abfe5c9f6) | Oct 07, 2024 |
| Polaroid      | MP1464PR001                 | [10cbba3b2d](https://linux-hardware.org/?probe=10cbba3b2d) | Sep 27, 2024 |
| Packard Be... | EasyNote LJ65               | [89b681de9c](https://linux-hardware.org/?probe=89b681de9c) | Sep 15, 2024 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [797d319058](https://linux-hardware.org/?probe=797d319058) | Sep 14, 2024 |
| ASUSTek       | K53SC                       | [e6267e83c6](https://linux-hardware.org/?probe=e6267e83c6) | Sep 11, 2024 |
| Packard Be... | EasyNote SB87               | [42bd3d165c](https://linux-hardware.org/?probe=42bd3d165c) | Aug 28, 2024 |
| Packard Be... | EasyNote SB87               | [e43949aaa9](https://linux-hardware.org/?probe=e43949aaa9) | Aug 28, 2024 |
| Lenovo        | G700 20251                  | [171cf04034](https://linux-hardware.org/?probe=171cf04034) | Aug 21, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | [5054565b58](https://linux-hardware.org/?probe=5054565b58) | Aug 03, 2024 |
| Alienware     | M11x R2                     | [e788979614](https://linux-hardware.org/?probe=e788979614) | Jul 05, 2024 |
| Lenovo        | ThinkPad W500 4063CTO       | [0e997531b5](https://linux-hardware.org/?probe=0e997531b5) | Jun 19, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [a2291158ce](https://linux-hardware.org/?probe=a2291158ce) | Jun 02, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [3c7d1c84a3](https://linux-hardware.org/?probe=3c7d1c84a3) | May 31, 2024 |
| Panasonic     | CF-C1BTCREFF                | [bb492a4906](https://linux-hardware.org/?probe=bb492a4906) | Apr 01, 2024 |
| Samsung       | SQ1US                       | [96fc573e2f](https://linux-hardware.org/?probe=96fc573e2f) | Feb 21, 2024 |
| Acer          | AOD255E                     | [fd8a88ea1a](https://linux-hardware.org/?probe=fd8a88ea1a) | Feb 09, 2024 |
| Acer          | AOD255E                     | [379ad2d74c](https://linux-hardware.org/?probe=379ad2d74c) | Jan 20, 2024 |
| Lenovo        | ThinkPad L540 20AUS00N00    | [a8aee3f386](https://linux-hardware.org/?probe=a8aee3f386) | Sep 26, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [eb05baece5](https://linux-hardware.org/?probe=eb05baece5) | Sep 05, 2023 |
| MSI           | GF63 Thin 11UC              | [f4fc84ba4b](https://linux-hardware.org/?probe=f4fc84ba4b) | Jul 17, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [c20dd8572a](https://linux-hardware.org/?probe=c20dd8572a) | Jun 05, 2023 |
| Lenovo        | B590 20206                  | [70b604bc30](https://linux-hardware.org/?probe=70b604bc30) | May 14, 2023 |
| Dell          | Latitude D630               | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| Dell          | Latitude D630               | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| Dell          | Inspiron 15-3567            | [23c158b19b](https://linux-hardware.org/?probe=23c158b19b) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d9d4f5649a](https://linux-hardware.org/?probe=d9d4f5649a) | Mar 14, 2023 |
| Dell          | Latitude E6440              | [b00f44cd46](https://linux-hardware.org/?probe=b00f44cd46) | Mar 09, 2023 |
| Dell          | Latitude E6440              | [3b9229e07a](https://linux-hardware.org/?probe=3b9229e07a) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [7ecc4d20c3](https://linux-hardware.org/?probe=7ecc4d20c3) | Jan 19, 2023 |
| Dell          | Inspiron 11 - 3147          | [7193100d05](https://linux-hardware.org/?probe=7193100d05) | Jan 14, 2023 |
| Gateway       | M-6854m                     | [76f293b62b](https://linux-hardware.org/?probe=76f293b62b) | Jan 12, 2023 |
| HP            | ProBook 430 G5              | [6403930d67](https://linux-hardware.org/?probe=6403930d67) | Jan 11, 2023 |
| ASUSTek       | X441NA                      | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Lenovo        | V330-15IKB 81AX             | [becc2328fd](https://linux-hardware.org/?probe=becc2328fd) | Dec 01, 2022 |
| Notebook      | RIM2520                     | [5f66abbb8b](https://linux-hardware.org/?probe=5f66abbb8b) | Nov 30, 2022 |
| HP            | 255 G6 Notebook PC          | [149cee1720](https://linux-hardware.org/?probe=149cee1720) | Nov 22, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [c6e254c4ed](https://linux-hardware.org/?probe=c6e254c4ed) | Nov 14, 2022 |
| HP            | Pavilion g7                 | [47c2e96181](https://linux-hardware.org/?probe=47c2e96181) | Nov 08, 2022 |
| Juana Mans... | SF20GM7                     | [8e8c4f52f4](https://linux-hardware.org/?probe=8e8c4f52f4) | Nov 04, 2022 |
| HP            | Pavilion g6                 | [353259fad4](https://linux-hardware.org/?probe=353259fad4) | Oct 26, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [45d7e6a1aa](https://linux-hardware.org/?probe=45d7e6a1aa) | Oct 21, 2022 |
| Lenovo        | ThinkPad X220 4291G26       | [33654dfbfa](https://linux-hardware.org/?probe=33654dfbfa) | Sep 22, 2022 |
| Acer          | Aspire 5742                 | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Lenovo        | ThinkPad X260 20F5A050IG    | [33b5154a7a](https://linux-hardware.org/?probe=33b5154a7a) | Aug 27, 2022 |
| Lenovo        | ThinkPad Edge E431 62774... | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T490 20N2000FIX    | [a68ebe9c0c](https://linux-hardware.org/?probe=a68ebe9c0c) | Jul 21, 2022 |
| Fujitsu       | FMVNP7HER                   | [e87161bce7](https://linux-hardware.org/?probe=e87161bce7) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [0fab4a4228](https://linux-hardware.org/?probe=0fab4a4228) | Jun 21, 2022 |
| Notebook      | NL40_50CU                   | [b0b1068b47](https://linux-hardware.org/?probe=b0b1068b47) | Jun 20, 2022 |
| TUXEDO        | Aura 15 Gen1                | [cc3a77a798](https://linux-hardware.org/?probe=cc3a77a798) | Jun 16, 2022 |
| Dell          | Latitude E5470              | [a4533cfbc7](https://linux-hardware.org/?probe=a4533cfbc7) | Jun 14, 2022 |
| Toshiba       | Satellite A300              | [3bfbcd1181](https://linux-hardware.org/?probe=3bfbcd1181) | Jun 12, 2022 |
| HP            | 250 G7 Notebook PC          | [e6fc1445a0](https://linux-hardware.org/?probe=e6fc1445a0) | Jun 03, 2022 |
| Dell          | Inspiron 5749               | [408e42beb8](https://linux-hardware.org/?probe=408e42beb8) | Jun 01, 2022 |
| ASUSTek       | K52F                        | [601b1c4857](https://linux-hardware.org/?probe=601b1c4857) | May 25, 2022 |
| Dell          | XPS 13 9360                 | [41f966f459](https://linux-hardware.org/?probe=41f966f459) | May 24, 2022 |
| Dell          | Latitude E5570              | [310aadd79a](https://linux-hardware.org/?probe=310aadd79a) | May 24, 2022 |
| ASUSTek       | F50SL                       | [7d588b102d](https://linux-hardware.org/?probe=7d588b102d) | May 23, 2022 |
| Dell          | Precision M4400             | [d0d09df553](https://linux-hardware.org/?probe=d0d09df553) | May 15, 2022 |
| Dell          | Precision M4400             | [96af5a9104](https://linux-hardware.org/?probe=96af5a9104) | May 15, 2022 |
| Dell          | MXG061                      | [36b09ae01e](https://linux-hardware.org/?probe=36b09ae01e) | May 14, 2022 |
| Lenovo        | ThinkPad L470 20J4003WGE    | [79bb6b88d3](https://linux-hardware.org/?probe=79bb6b88d3) | May 06, 2022 |
| Panasonic     | CF-31-5                     | [d17d17b778](https://linux-hardware.org/?probe=d17d17b778) | May 02, 2022 |
| Dell          | Vostro 5470                 | [8fbdd05b2a](https://linux-hardware.org/?probe=8fbdd05b2a) | May 02, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9e7c77d251](https://linux-hardware.org/?probe=9e7c77d251) | Apr 27, 2022 |
| Timi          | TM1612                      | [9e6b6f4737](https://linux-hardware.org/?probe=9e6b6f4737) | Apr 24, 2022 |
| Lenovo        | ThinkPad P53 20QN000ESP     | [16b3189bd8](https://linux-hardware.org/?probe=16b3189bd8) | Apr 22, 2022 |
| Dell          | Inspiron 5577               | [d82fa1bfc9](https://linux-hardware.org/?probe=d82fa1bfc9) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4ca643452e](https://linux-hardware.org/?probe=4ca643452e) | Apr 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6QV00    | [315f7326a1](https://linux-hardware.org/?probe=315f7326a1) | Apr 10, 2022 |
| Samsung       | 270E5J/2570EJ               | [0887c85f98](https://linux-hardware.org/?probe=0887c85f98) | Apr 06, 2022 |
| Intel         | powered classmate PC        | [8ce4fa1757](https://linux-hardware.org/?probe=8ce4fa1757) | Apr 01, 2022 |
| Lenovo        | ThinkPad X230 23259S9       | [a461555ba9](https://linux-hardware.org/?probe=a461555ba9) | Mar 30, 2022 |
| HP            | Compaq 615                  | [906354c0ce](https://linux-hardware.org/?probe=906354c0ce) | Mar 27, 2022 |
| HP            | Compaq 615                  | [28368f4366](https://linux-hardware.org/?probe=28368f4366) | Mar 25, 2022 |
| Dell          | XPS 15 9570                 | [d4b19324b2](https://linux-hardware.org/?probe=d4b19324b2) | Mar 22, 2022 |
| Lenovo        | ThinkPad L470 20J4003WGE    | [62b1219002](https://linux-hardware.org/?probe=62b1219002) | Mar 21, 2022 |
| Lenovo        | ThinkPad X220 4291G26       | [c2f45496d1](https://linux-hardware.org/?probe=c2f45496d1) | Mar 21, 2022 |
| Dell          | MXG071                      | [62a45db2eb](https://linux-hardware.org/?probe=62a45db2eb) | Mar 06, 2022 |
| ASUSTek       | 1015BX                      | [9b3fb4a52b](https://linux-hardware.org/?probe=9b3fb4a52b) | Feb 20, 2022 |
| ASUSTek       | X55C                        | [ae05784a4a](https://linux-hardware.org/?probe=ae05784a4a) | Feb 19, 2022 |
| Samsung       | N230                        | [f16e2ce417](https://linux-hardware.org/?probe=f16e2ce417) | Feb 16, 2022 |
| Samsung       | N230                        | [10be19ecbf](https://linux-hardware.org/?probe=10be19ecbf) | Feb 16, 2022 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [9e3040619f](https://linux-hardware.org/?probe=9e3040619f) | Jan 30, 2022 |
| ASUSTek       | X555BA                      | [526e03cf05](https://linux-hardware.org/?probe=526e03cf05) | Jan 28, 2022 |
| Dell          | Vostro 5470                 | [1e97f26a27](https://linux-hardware.org/?probe=1e97f26a27) | Jan 15, 2022 |
| HP            | EliteBook 8440p             | [c15f816857](https://linux-hardware.org/?probe=c15f816857) | Jan 11, 2022 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [c7f2471bdf](https://linux-hardware.org/?probe=c7f2471bdf) | Jan 04, 2022 |
| HP            | Unknown                     | [e1eb3d8838](https://linux-hardware.org/?probe=e1eb3d8838) | Dec 30, 2021 |
| HP            | Pavilion dv3                | [3f3defcf69](https://linux-hardware.org/?probe=3f3defcf69) | Dec 28, 2021 |
| HP            | Pavilion dv3                | [750225c8c8](https://linux-hardware.org/?probe=750225c8c8) | Dec 28, 2021 |
| HP            | Compaq 6710b (RM405UT#AB... | [e4789d000a](https://linux-hardware.org/?probe=e4789d000a) | Dec 28, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9a6b436bcb](https://linux-hardware.org/?probe=9a6b436bcb) | Dec 26, 2021 |
| HP            | EliteBook 8470w             | [87c1cb1da7](https://linux-hardware.org/?probe=87c1cb1da7) | Dec 23, 2021 |
| Acer          | Aspire 5250                 | [856d94d47a](https://linux-hardware.org/?probe=856d94d47a) | Dec 21, 2021 |
| Dell          | Latitude E7440              | [bb71f679cf](https://linux-hardware.org/?probe=bb71f679cf) | Dec 06, 2021 |
| Philco        | OEM                         | [3d13f6a539](https://linux-hardware.org/?probe=3d13f6a539) | Nov 28, 2021 |
| HP            | Pavilion Notebook           | [78bddf398e](https://linux-hardware.org/?probe=78bddf398e) | Nov 25, 2021 |
| Lenovo        | B40-70 20392                | [4f4458d61a](https://linux-hardware.org/?probe=4f4458d61a) | Nov 23, 2021 |
| ASUSTek       | K53U                        | [8b542e61d9](https://linux-hardware.org/?probe=8b542e61d9) | Nov 18, 2021 |
| Dell          | 0NY667                      | [d0c838dff6](https://linux-hardware.org/?probe=d0c838dff6) | Nov 17, 2021 |
| Acer          | Aspire V3-772G              | [1e66881588](https://linux-hardware.org/?probe=1e66881588) | Nov 16, 2021 |
| AXDIA Inte... | Wintab 10                   | [0cf33496ad](https://linux-hardware.org/?probe=0cf33496ad) | Nov 14, 2021 |
| Dell          | Precision 7520              | [55077aa291](https://linux-hardware.org/?probe=55077aa291) | Nov 13, 2021 |
| Dell          | Inspiron 7447               | [4ca16063da](https://linux-hardware.org/?probe=4ca16063da) | Nov 12, 2021 |
| HP            | Stream Laptop 11-y0XX       | [1bd1ac9ae2](https://linux-hardware.org/?probe=1bd1ac9ae2) | Nov 08, 2021 |
| Dell          | Latitude E6420              | [66cfc6d85b](https://linux-hardware.org/?probe=66cfc6d85b) | Nov 07, 2021 |
| ASUSTek       | K52F                        | [f90cbb4d26](https://linux-hardware.org/?probe=f90cbb4d26) | Nov 04, 2021 |
| ASUSTek       | X555BA                      | [99ef7179aa](https://linux-hardware.org/?probe=99ef7179aa) | Nov 04, 2021 |
| Dell          | Latitude D600               | [024dd9fbc7](https://linux-hardware.org/?probe=024dd9fbc7) | Nov 02, 2021 |
| ASUSTek       | N10Jh                       | [9d10643a15](https://linux-hardware.org/?probe=9d10643a15) | Oct 30, 2021 |
| Lenovo        | G570 4334                   | [d1d57448c4](https://linux-hardware.org/?probe=d1d57448c4) | Oct 29, 2021 |
| Lenovo        | G570 4334                   | [f5112dbf47](https://linux-hardware.org/?probe=f5112dbf47) | Oct 29, 2021 |
| HP            | Compaq Presario CQ60        | [b9b0c35db8](https://linux-hardware.org/?probe=b9b0c35db8) | Oct 28, 2021 |
| Lenovo        | ThinkPad T480s 20L7002AU... | [dda6d4cdcb](https://linux-hardware.org/?probe=dda6d4cdcb) | Oct 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [67ab68b5f3](https://linux-hardware.org/?probe=67ab68b5f3) | Oct 26, 2021 |
| Dell          | Inspiron 5570               | [c01fa4b013](https://linux-hardware.org/?probe=c01fa4b013) | Oct 26, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | [8f6efb8dbe](https://linux-hardware.org/?probe=8f6efb8dbe) | Oct 24, 2021 |
| Acer          | Nitro AN515-42              | [2ff605bdb0](https://linux-hardware.org/?probe=2ff605bdb0) | Oct 20, 2021 |
| ASUSTek       | N551JW                      | [a6c41c9d3e](https://linux-hardware.org/?probe=a6c41c9d3e) | Oct 19, 2021 |
| Dell          | Inspiron 1545               | [4852d91477](https://linux-hardware.org/?probe=4852d91477) | Oct 17, 2021 |
| Dell          | Inspiron 1545               | [249e85b27d](https://linux-hardware.org/?probe=249e85b27d) | Oct 17, 2021 |
| Dell          | Inspiron 1440               | [9e9967a3fa](https://linux-hardware.org/?probe=9e9967a3fa) | Oct 17, 2021 |
| Dell          | Latitude D600               | [c4a1e26625](https://linux-hardware.org/?probe=c4a1e26625) | Oct 15, 2021 |
| Dell          | Latitude D600               | [994b244534](https://linux-hardware.org/?probe=994b244534) | Oct 15, 2021 |
| HP            | EliteBook 745 G6            | [295112838e](https://linux-hardware.org/?probe=295112838e) | Oct 14, 2021 |
| Dell          | MXG071                      | [5006aa0f75](https://linux-hardware.org/?probe=5006aa0f75) | Oct 12, 2021 |
| Unknown       | Pyra-Handheld-V5.3          | [3e61c199d6](https://linux-hardware.org/?probe=3e61c199d6) | Oct 12, 2021 |
| Toshiba       | Satellite A215              | [06c3b56836](https://linux-hardware.org/?probe=06c3b56836) | Oct 11, 2021 |
| Dell          | System Inspiron 7720        | [6728cba5a1](https://linux-hardware.org/?probe=6728cba5a1) | Oct 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [04d8d207df](https://linux-hardware.org/?probe=04d8d207df) | Oct 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d0d578ae42](https://linux-hardware.org/?probe=d0d578ae42) | Oct 08, 2021 |
| Lenovo        | ThinkPad T440 20B7S1X108    | [0ad6768049](https://linux-hardware.org/?probe=0ad6768049) | Oct 02, 2021 |
| Toshiba       | Satellite L500              | [07116867d0](https://linux-hardware.org/?probe=07116867d0) | Sep 30, 2021 |
| Dell          | Latitude 5411               | [b1b898bf2b](https://linux-hardware.org/?probe=b1b898bf2b) | Sep 30, 2021 |
| Acer          | Aspire A515-43              | [5edddc1e2c](https://linux-hardware.org/?probe=5edddc1e2c) | Sep 29, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [3095cda8c3](https://linux-hardware.org/?probe=3095cda8c3) | Sep 27, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [299d4edf8d](https://linux-hardware.org/?probe=299d4edf8d) | Sep 27, 2021 |
| ASUSTek       | X540YA                      | [c0b5da7979](https://linux-hardware.org/?probe=c0b5da7979) | Sep 19, 2021 |
| Acer          | Aspire 5542                 | [dfa471a829](https://linux-hardware.org/?probe=dfa471a829) | Sep 17, 2021 |
| Acer          | Aspire 5542                 | [d862c4ce39](https://linux-hardware.org/?probe=d862c4ce39) | Sep 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [232a307a5b](https://linux-hardware.org/?probe=232a307a5b) | Sep 14, 2021 |
| Lenovo        | ThinkPad T590 20N4000BFR    | [834ddc5e6a](https://linux-hardware.org/?probe=834ddc5e6a) | Sep 13, 2021 |
| Intel         | powered classmate PC        | [15cb9c7764](https://linux-hardware.org/?probe=15cb9c7764) | Sep 12, 2021 |
| Dell          | Inspiron 5420               | [bc80b42442](https://linux-hardware.org/?probe=bc80b42442) | Sep 12, 2021 |
| Lenovo        | QIWY3                       | [9da123bf89](https://linux-hardware.org/?probe=9da123bf89) | Sep 09, 2021 |
| Lenovo        | QIWY3                       | [552b695b27](https://linux-hardware.org/?probe=552b695b27) | Sep 09, 2021 |
| GTZS          | Unknown                     | [e5d931aaf8](https://linux-hardware.org/?probe=e5d931aaf8) | Sep 06, 2021 |
| HP            | ProBook 6460b               | [7d379f011c](https://linux-hardware.org/?probe=7d379f011c) | Sep 04, 2021 |
| Lenovo        | ThinkPad R60 9462A45        | [5850a811e3](https://linux-hardware.org/?probe=5850a811e3) | Sep 01, 2021 |
| HP            | 250 G4 Notebook PC          | [2cf6464047](https://linux-hardware.org/?probe=2cf6464047) | Aug 31, 2021 |
| HP            | EliteBook 850 G5            | [68149f9864](https://linux-hardware.org/?probe=68149f9864) | Aug 30, 2021 |
| Dell          | Studio XPS 1640             | [f0765cb8c8](https://linux-hardware.org/?probe=f0765cb8c8) | Aug 28, 2021 |
| Dell          | Studio XPS 1640             | [1e772e0237](https://linux-hardware.org/?probe=1e772e0237) | Aug 28, 2021 |
| Lenovo        | ThinkPad X220 429044C       | [20057996af](https://linux-hardware.org/?probe=20057996af) | Aug 27, 2021 |
| Acer          | TravelMate 7750G            | [8d3d35021f](https://linux-hardware.org/?probe=8d3d35021f) | Aug 27, 2021 |
| Itautec       | Infoway w7535               | [f7d8a66820](https://linux-hardware.org/?probe=f7d8a66820) | Aug 27, 2021 |
| Lenovo        | ThinkPad X260 20F5S3J00D    | [eeb6586c28](https://linux-hardware.org/?probe=eeb6586c28) | Aug 26, 2021 |
| ASUSTek       | P751JA                      | [0ba110ae45](https://linux-hardware.org/?probe=0ba110ae45) | Aug 25, 2021 |
| TQ-Group      | TQMxE39S                    | [69363368e2](https://linux-hardware.org/?probe=69363368e2) | Aug 23, 2021 |
| ASUSTek       | M51Sn                       | [4a85a76b94](https://linux-hardware.org/?probe=4a85a76b94) | Aug 21, 2021 |
| Toshiba       | Satellite C55D-B            | [3aa4e38d51](https://linux-hardware.org/?probe=3aa4e38d51) | Aug 21, 2021 |
| Itautec       | Infoway w7535               | [ea3f721976](https://linux-hardware.org/?probe=ea3f721976) | Aug 21, 2021 |
| Acer          | Aspire S5-371               | [5e3fcc0daa](https://linux-hardware.org/?probe=5e3fcc0daa) | Aug 21, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e4ab15ad86](https://linux-hardware.org/?probe=e4ab15ad86) | Aug 16, 2021 |
| ASUSTek       | N550JV                      | [631e697061](https://linux-hardware.org/?probe=631e697061) | Aug 13, 2021 |
| ASUSTek       | N550JV                      | [191ce05579](https://linux-hardware.org/?probe=191ce05579) | Aug 13, 2021 |
| Apple         | MacBookPro9,2               | [10a9ce514b](https://linux-hardware.org/?probe=10a9ce514b) | Aug 11, 2021 |
| Apple         | MacBookPro9,2               | [4a08b4bc9c](https://linux-hardware.org/?probe=4a08b4bc9c) | Aug 11, 2021 |
| Google        | Careena                     | [a715f6f37f](https://linux-hardware.org/?probe=a715f6f37f) | Aug 10, 2021 |
| HP            | Pavilion Notebook           | [f8742367c3](https://linux-hardware.org/?probe=f8742367c3) | Aug 10, 2021 |
| HP            | Pavilion Notebook           | [7401df03e4](https://linux-hardware.org/?probe=7401df03e4) | Aug 09, 2021 |
| Gateway       | MD7811U                     | [fdd99ed1fe](https://linux-hardware.org/?probe=fdd99ed1fe) | Aug 09, 2021 |
| Gateway       | MD7811U                     | [07d8dcb0ff](https://linux-hardware.org/?probe=07d8dcb0ff) | Aug 08, 2021 |
| DNS           | 101                         | [83fc7e7928](https://linux-hardware.org/?probe=83fc7e7928) | Aug 08, 2021 |
| Lenovo        | ThinkPad T480s 20L7002AU... | [d19a600e79](https://linux-hardware.org/?probe=d19a600e79) | Aug 07, 2021 |
| ASUSTek       | N56VZ                       | [4080b39f00](https://linux-hardware.org/?probe=4080b39f00) | Aug 07, 2021 |
| Sony          | VPCS110FL                   | [2227fd7ae7](https://linux-hardware.org/?probe=2227fd7ae7) | Aug 07, 2021 |
| Sony          | VPCS110FL                   | [1741c7d3db](https://linux-hardware.org/?probe=1741c7d3db) | Aug 07, 2021 |
| Apple         | MacBookPro9,2               | [f4e31f03fb](https://linux-hardware.org/?probe=f4e31f03fb) | Aug 07, 2021 |
| Dell          | G3 3590                     | [16bdb588e1](https://linux-hardware.org/?probe=16bdb588e1) | Aug 05, 2021 |
| Dell          | G3 3590                     | [01a9560f9c](https://linux-hardware.org/?probe=01a9560f9c) | Aug 05, 2021 |
| Dell          | Precision 3530              | [f2fb6b98ea](https://linux-hardware.org/?probe=f2fb6b98ea) | Aug 03, 2021 |
| Lenovo        | ThinkPad T490 20N2002AUS    | [557f9a87fa](https://linux-hardware.org/?probe=557f9a87fa) | Jul 30, 2021 |
| MSI           | U210/U210 Light             | [98d5949e01](https://linux-hardware.org/?probe=98d5949e01) | Jul 29, 2021 |
| ASUSTek       | X205TA                      | [37efd6fc5e](https://linux-hardware.org/?probe=37efd6fc5e) | Jul 26, 2021 |
| Lenovo        | B51-35 80LH                 | [662fffc9d2](https://linux-hardware.org/?probe=662fffc9d2) | Jul 25, 2021 |
| Lenovo        | B51-35 80LH                 | [bdaceebba4](https://linux-hardware.org/?probe=bdaceebba4) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [7330b29e94](https://linux-hardware.org/?probe=7330b29e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [1a104c4440](https://linux-hardware.org/?probe=1a104c4440) | Jul 25, 2021 |
| Acer          | AO725                       | [4e27f519f7](https://linux-hardware.org/?probe=4e27f519f7) | Jul 25, 2021 |
| Dell          | Vostro 1500                 | [f78b977663](https://linux-hardware.org/?probe=f78b977663) | Jul 25, 2021 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [0d77ee3e3d](https://linux-hardware.org/?probe=0d77ee3e3d) | Jul 22, 2021 |
| Acer          | Aspire A715-72G             | [d977beba9e](https://linux-hardware.org/?probe=d977beba9e) | Jul 22, 2021 |
| Toshiba       | Satellite M70               | [ffe4b92da3](https://linux-hardware.org/?probe=ffe4b92da3) | Jul 21, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | [a347415235](https://linux-hardware.org/?probe=a347415235) | Jul 19, 2021 |
| Dell          | XPS M1330                   | [69cc932202](https://linux-hardware.org/?probe=69cc932202) | Jul 17, 2021 |
| MSI           | GF65 Thin 10UE              | [0a875bd8bb](https://linux-hardware.org/?probe=0a875bd8bb) | Jul 15, 2021 |
| Dell          | Latitude E6420              | [e2e96ce9d8](https://linux-hardware.org/?probe=e2e96ce9d8) | Jul 14, 2021 |
| Dell          | Latitude E6420              | [eb1224a5ff](https://linux-hardware.org/?probe=eb1224a5ff) | Jul 14, 2021 |
| Acer          | Swift SF114-33              | [7aa338a8dc](https://linux-hardware.org/?probe=7aa338a8dc) | Jul 12, 2021 |
| One Educat... | Infinity:One                | [2f6016cb80](https://linux-hardware.org/?probe=2f6016cb80) | Jul 12, 2021 |
| HP            | ProBook 6460b               | [094d8f1435](https://linux-hardware.org/?probe=094d8f1435) | Jul 10, 2021 |
| ASUSTek       | K56CB                       | [112f34cf11](https://linux-hardware.org/?probe=112f34cf11) | Jul 09, 2021 |
| HP            | Spectre Laptop 13-af0xx     | [bfef4cded0](https://linux-hardware.org/?probe=bfef4cded0) | Jul 09, 2021 |
| Acer          | E1-510                      | [b1b6133207](https://linux-hardware.org/?probe=b1b6133207) | Jul 08, 2021 |
| Lenovo        | ThinkPad R60 9462A45        | [541bb57585](https://linux-hardware.org/?probe=541bb57585) | Jul 07, 2021 |
| ASUSTek       | VivoBook S14 X411UF         | [f5a3e8f307](https://linux-hardware.org/?probe=f5a3e8f307) | Jul 06, 2021 |
| Lenovo        | ThinkPad L590 20Q7CTO1WW    | [ec305ddc45](https://linux-hardware.org/?probe=ec305ddc45) | Jul 05, 2021 |
| Lenovo        | B50-10 80QR                 | [56044931dc](https://linux-hardware.org/?probe=56044931dc) | Jul 04, 2021 |
| Dell          | Latitude E6430              | [0c6585a784](https://linux-hardware.org/?probe=0c6585a784) | Jun 30, 2021 |
| Dell          | Inspiron 3421               | [1900fb77ec](https://linux-hardware.org/?probe=1900fb77ec) | Jun 29, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [d4a28fa40a](https://linux-hardware.org/?probe=d4a28fa40a) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [fc58981ecd](https://linux-hardware.org/?probe=fc58981ecd) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [bce9c74edb](https://linux-hardware.org/?probe=bce9c74edb) | Jun 27, 2021 |
| SAELITE       | ES1AU11                     | [25dc027ef1](https://linux-hardware.org/?probe=25dc027ef1) | Jun 26, 2021 |
| Lenovo        | ThinkPad X230 23252EG       | [77c68fb077](https://linux-hardware.org/?probe=77c68fb077) | Jun 23, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [0240acc863](https://linux-hardware.org/?probe=0240acc863) | Jun 22, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [f64428c049](https://linux-hardware.org/?probe=f64428c049) | Jun 22, 2021 |
| Dell          | Latitude 7480               | [28d1d17f13](https://linux-hardware.org/?probe=28d1d17f13) | Jun 22, 2021 |
| Dell          | Latitude E6430              | [f0afba2500](https://linux-hardware.org/?probe=f0afba2500) | Jun 21, 2021 |
| Timi          | TM1612                      | [c4fb55cbfd](https://linux-hardware.org/?probe=c4fb55cbfd) | Jun 21, 2021 |
| Lenovo        | B50-10 80QR                 | [847e763107](https://linux-hardware.org/?probe=847e763107) | Jun 20, 2021 |
| Timi          | TM1612                      | [dcb999a722](https://linux-hardware.org/?probe=dcb999a722) | Jun 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [3518f65e84](https://linux-hardware.org/?probe=3518f65e84) | Jun 18, 2021 |
| Dell          | Latitude 5420               | [1356be4391](https://linux-hardware.org/?probe=1356be4391) | Jun 18, 2021 |
| VIT           | P2400                       | [295d4d5a47](https://linux-hardware.org/?probe=295d4d5a47) | Jun 17, 2021 |
| Fujitsu       | LIFEBOOK BH531              | [688d9f583e](https://linux-hardware.org/?probe=688d9f583e) | Jun 16, 2021 |
| Sony          | VGN-FW21L                   | [fe6647a4b1](https://linux-hardware.org/?probe=fe6647a4b1) | Jun 15, 2021 |
| Sony          | VGN-FW21E                   | [f46b41cd2f](https://linux-hardware.org/?probe=f46b41cd2f) | Jun 15, 2021 |
| Dell          | XPS 13 9310                 | [278fd058ed](https://linux-hardware.org/?probe=278fd058ed) | Jun 14, 2021 |
| HP            | Laptop 15s-fq2xxx           | [b592b452fe](https://linux-hardware.org/?probe=b592b452fe) | Jun 12, 2021 |
| IBM           | ThinkPad T42 23736YG        | [fbf7c66f92](https://linux-hardware.org/?probe=fbf7c66f92) | Jun 12, 2021 |
| HP            | Compaq Presario CQ71        | [37a87224fb](https://linux-hardware.org/?probe=37a87224fb) | Jun 12, 2021 |
| Dell          | Latitude E7440              | [3f4df169bd](https://linux-hardware.org/?probe=3f4df169bd) | Jun 11, 2021 |
| Dell          | Inspiron 1525               | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| HP            | ProBook 450 G6              | [e081b13666](https://linux-hardware.org/?probe=e081b13666) | Jun 09, 2021 |
| HP            | ProBook 450 G6              | [e3efe71b23](https://linux-hardware.org/?probe=e3efe71b23) | Jun 09, 2021 |
| HP            | Laptop 15-dw0xxx            | [95fdac8e1c](https://linux-hardware.org/?probe=95fdac8e1c) | Jun 08, 2021 |
| Lenovo        | ThinkPad E590 20NB001AGE    | [21cab94898](https://linux-hardware.org/?probe=21cab94898) | Jun 08, 2021 |
| HP            | EliteBook 820 G1            | [6fbdebda43](https://linux-hardware.org/?probe=6fbdebda43) | Jun 06, 2021 |
| Acer          | Aspire 5750G                | [45b5e8d8ae](https://linux-hardware.org/?probe=45b5e8d8ae) | Jun 06, 2021 |
| Dell          | Inspiron 5577               | [188fcc64df](https://linux-hardware.org/?probe=188fcc64df) | Jun 06, 2021 |
| Dell          | Latitude C810               | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Latitude E5470              | [5b65572d25](https://linux-hardware.org/?probe=5b65572d25) | Jun 05, 2021 |
| Timi          | TM1612                      | [40318f2d95](https://linux-hardware.org/?probe=40318f2d95) | Jun 05, 2021 |
| Dell          | Latitude C810               | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Dell          | Inspiron 3501               | [3e23b17d66](https://linux-hardware.org/?probe=3e23b17d66) | Jun 01, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [1505924642](https://linux-hardware.org/?probe=1505924642) | Jun 01, 2021 |
| Lenovo        | ThinkPad T430s 2356GBG      | [e67f4b0fd4](https://linux-hardware.org/?probe=e67f4b0fd4) | May 31, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [b7ec4606a3](https://linux-hardware.org/?probe=b7ec4606a3) | May 31, 2021 |
| HP            | 250 G7 Notebook PC          | [035b3cdc60](https://linux-hardware.org/?probe=035b3cdc60) | May 31, 2021 |
| HP            | 250 G7 Notebook PC          | [e9148788a7](https://linux-hardware.org/?probe=e9148788a7) | May 30, 2021 |
| HP            | 250 G7 Notebook PC          | [0dbfbd4c06](https://linux-hardware.org/?probe=0dbfbd4c06) | May 27, 2021 |
| ASUSTek       | X450LN                      | [9157df68c1](https://linux-hardware.org/?probe=9157df68c1) | May 27, 2021 |
| HP            | Laptop 15s-fq2xxx           | [72287f1bb4](https://linux-hardware.org/?probe=72287f1bb4) | May 25, 2021 |
| HP            | Laptop 15s-fq2xxx           | [f4713dbdb0](https://linux-hardware.org/?probe=f4713dbdb0) | May 25, 2021 |
| ASUSTek       | X450LN                      | [aa8e32e484](https://linux-hardware.org/?probe=aa8e32e484) | May 25, 2021 |
| ASUSTek       | K52F                        | [92db46133f](https://linux-hardware.org/?probe=92db46133f) | May 24, 2021 |
| ASUSTek       | X553SA                      | [c470382d2a](https://linux-hardware.org/?probe=c470382d2a) | May 24, 2021 |
| ASUSTek       | X553SA                      | [31d6a914fd](https://linux-hardware.org/?probe=31d6a914fd) | May 24, 2021 |
| Acer          | Aspire 5750G                | [b420f25ed4](https://linux-hardware.org/?probe=b420f25ed4) | May 23, 2021 |
| Apple         | MacBook5,2                  | [cc0fa80e46](https://linux-hardware.org/?probe=cc0fa80e46) | May 21, 2021 |
| Dell          | Inspiron 7460               | [b766b75906](https://linux-hardware.org/?probe=b766b75906) | May 21, 2021 |
| Toshiba       | Satellite C660              | [60eb674c8f](https://linux-hardware.org/?probe=60eb674c8f) | May 19, 2021 |
| HP            | ProBook 6460b               | [06bc21db81](https://linux-hardware.org/?probe=06bc21db81) | May 18, 2021 |
| LG Electro... | A410-K.BE43P1               | [48978860b6](https://linux-hardware.org/?probe=48978860b6) | May 15, 2021 |
| Acer          | Swift SF114-33              | [e2d8f58e1e](https://linux-hardware.org/?probe=e2d8f58e1e) | May 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [2196430972](https://linux-hardware.org/?probe=2196430972) | May 09, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [5a99a3a590](https://linux-hardware.org/?probe=5a99a3a590) | May 08, 2021 |
| Acer          | Swift SF114-33              | [a6ed80ed47](https://linux-hardware.org/?probe=a6ed80ed47) | May 08, 2021 |
| Lenovo        | G50-80 80E5                 | [d4b9ffef0a](https://linux-hardware.org/?probe=d4b9ffef0a) | May 06, 2021 |
| Lenovo        | G570 4334                   | [f16304ca03](https://linux-hardware.org/?probe=f16304ca03) | May 04, 2021 |
| Lenovo        | G570 4334                   | [8eca6b6f79](https://linux-hardware.org/?probe=8eca6b6f79) | May 04, 2021 |
| ASUSTek       | N56VM                       | [b08edb12bf](https://linux-hardware.org/?probe=b08edb12bf) | May 04, 2021 |
| ASUSTek       | N56VM                       | [c387fd3d02](https://linux-hardware.org/?probe=c387fd3d02) | May 04, 2021 |
| HP            | Laptop 15-bs0xx             | [57540cdfa4](https://linux-hardware.org/?probe=57540cdfa4) | May 03, 2021 |
| HP            | 2133                        | [e81cac058d](https://linux-hardware.org/?probe=e81cac058d) | May 03, 2021 |
| Lenovo        | G570 4334                   | [bef0f33897](https://linux-hardware.org/?probe=bef0f33897) | May 02, 2021 |
| LG Electro... | 15ND530-GX30K               | [9d700ce0b6](https://linux-hardware.org/?probe=9d700ce0b6) | Apr 30, 2021 |
| HP            | EliteBook Folio 1040 G1     | [81557b6c6c](https://linux-hardware.org/?probe=81557b6c6c) | Apr 29, 2021 |
| Dell          | Latitude E5270              | [7344ffb994](https://linux-hardware.org/?probe=7344ffb994) | Apr 29, 2021 |
| HP            | 2133                        | [fd8d7a6a94](https://linux-hardware.org/?probe=fd8d7a6a94) | Apr 29, 2021 |
| Toshiba       | Satellite C50-A-K9K         | [f31812125b](https://linux-hardware.org/?probe=f31812125b) | Apr 28, 2021 |
| Dell          | Precision M4400             | [f7616a8e34](https://linux-hardware.org/?probe=f7616a8e34) | Apr 28, 2021 |
| Dell          | Latitude 2120               | [5bfebbf71d](https://linux-hardware.org/?probe=5bfebbf71d) | Apr 28, 2021 |
| Dell          | Latitude D830               | [ddc172ef71](https://linux-hardware.org/?probe=ddc172ef71) | Apr 28, 2021 |
| Toshiba       | Satellite L505D             | [db2deee6fc](https://linux-hardware.org/?probe=db2deee6fc) | Apr 28, 2021 |
| Dell          | Precision M4600             | [f11bc44848](https://linux-hardware.org/?probe=f11bc44848) | Apr 28, 2021 |
| Toshiba       | Satellite Click W35Dt-A     | [7f18f2f6e4](https://linux-hardware.org/?probe=7f18f2f6e4) | Apr 28, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [004380d8f4](https://linux-hardware.org/?probe=004380d8f4) | Apr 27, 2021 |
| Acer          | Aspire A515-51G             | [bbd69fd1b9](https://linux-hardware.org/?probe=bbd69fd1b9) | Apr 27, 2021 |
| Dell          | Latitude E6420              | [7dbd1d34b7](https://linux-hardware.org/?probe=7dbd1d34b7) | Apr 27, 2021 |
| HP            | ProBook 6460b               | [ee71283e78](https://linux-hardware.org/?probe=ee71283e78) | Apr 27, 2021 |
| TQ-Group      | TQMxE39S                    | [f70e13fdba](https://linux-hardware.org/?probe=f70e13fdba) | Apr 26, 2021 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [4dfa28cef5](https://linux-hardware.org/?probe=4dfa28cef5) | Apr 25, 2021 |
| HP            | ENVY TS 15                  | [7ee12f0f12](https://linux-hardware.org/?probe=7ee12f0f12) | Apr 24, 2021 |
| HP            | ENVY TS 15                  | [1e93ee4ada](https://linux-hardware.org/?probe=1e93ee4ada) | Apr 23, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [eb3e5cf436](https://linux-hardware.org/?probe=eb3e5cf436) | Apr 22, 2021 |
| TQ-Group      | TQMxE39S                    | [0d550b5fcf](https://linux-hardware.org/?probe=0d550b5fcf) | Apr 21, 2021 |
| HP            | Compaq CQ58                 | [cf2de362ba](https://linux-hardware.org/?probe=cf2de362ba) | Apr 20, 2021 |
| ASUSTek       | N501VW                      | [3a70b17a13](https://linux-hardware.org/?probe=3a70b17a13) | Apr 19, 2021 |
| ASUSTek       | N501VW                      | [58b2490001](https://linux-hardware.org/?probe=58b2490001) | Apr 19, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [f8a3bc6b1d](https://linux-hardware.org/?probe=f8a3bc6b1d) | Apr 19, 2021 |
| Fujitsu       | LIFEBOOK BH531              | [2fa4c2d1ef](https://linux-hardware.org/?probe=2fa4c2d1ef) | Apr 18, 2021 |
| Apple         | MacBook4,1                  | [c81b5705ce](https://linux-hardware.org/?probe=c81b5705ce) | Apr 17, 2021 |
| Sony          | VPCM120AL                   | [e15b3dcfa3](https://linux-hardware.org/?probe=e15b3dcfa3) | Apr 16, 2021 |
| Fujitsu       | LIFEBOOK S761               | [0115b1d779](https://linux-hardware.org/?probe=0115b1d779) | Apr 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [66de8410b3](https://linux-hardware.org/?probe=66de8410b3) | Apr 16, 2021 |
| Acer          | Aspire F5-573               | [82de91c65b](https://linux-hardware.org/?probe=82de91c65b) | Apr 15, 2021 |
| HP            | Stream Notebook PC 13       | [0bf3f6f761](https://linux-hardware.org/?probe=0bf3f6f761) | Apr 15, 2021 |
| Google        | Chell                       | [a570a864bb](https://linux-hardware.org/?probe=a570a864bb) | Apr 14, 2021 |
| Google        | Chell                       | [ef62c9f5d3](https://linux-hardware.org/?probe=ef62c9f5d3) | Apr 14, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | [127928c404](https://linux-hardware.org/?probe=127928c404) | Apr 13, 2021 |
| Dell          | Inspiron 5566               | [3f063b636f](https://linux-hardware.org/?probe=3f063b636f) | Apr 13, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [80eb7bbfd6](https://linux-hardware.org/?probe=80eb7bbfd6) | Apr 12, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [a6f88dd316](https://linux-hardware.org/?probe=a6f88dd316) | Apr 11, 2021 |
| Acer          | Aspire V3-771               | [e6c39f5551](https://linux-hardware.org/?probe=e6c39f5551) | Apr 11, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c9da6a52cb](https://linux-hardware.org/?probe=c9da6a52cb) | Apr 11, 2021 |
| Dell          | Latitude E7440              | [f5329e62a2](https://linux-hardware.org/?probe=f5329e62a2) | Apr 10, 2021 |
| Sony          | VGN-FW31ZJ                  | [b1bc398f58](https://linux-hardware.org/?probe=b1bc398f58) | Apr 10, 2021 |
| Acer          | Nitro AN515-42              | [4c7acbbbc1](https://linux-hardware.org/?probe=4c7acbbbc1) | Apr 10, 2021 |
| Acer          | Aspire V5-571G              | [bc54b9763a](https://linux-hardware.org/?probe=bc54b9763a) | Apr 08, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [adb7fbfc0d](https://linux-hardware.org/?probe=adb7fbfc0d) | Apr 08, 2021 |
| Toshiba       | Satellite M505D             | [2711ae5eca](https://linux-hardware.org/?probe=2711ae5eca) | Apr 07, 2021 |
| HP            | ENVY Notebook               | [83a0078309](https://linux-hardware.org/?probe=83a0078309) | Apr 06, 2021 |
| Lenovo        | ThinkPad T460 20FMS0X022    | [02ce254082](https://linux-hardware.org/?probe=02ce254082) | Apr 06, 2021 |
| Sony          | VGN-FW31ZJ                  | [9de66e685f](https://linux-hardware.org/?probe=9de66e685f) | Apr 05, 2021 |
| HP            | EliteBook 2170p             | [c45b758d6c](https://linux-hardware.org/?probe=c45b758d6c) | Apr 04, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [8e270876a9](https://linux-hardware.org/?probe=8e270876a9) | Apr 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [11a0cd56e5](https://linux-hardware.org/?probe=11a0cd56e5) | Apr 02, 2021 |
| ASUSTek       | U32U                        | [2842f61fc9](https://linux-hardware.org/?probe=2842f61fc9) | Apr 02, 2021 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [09ae9c9787](https://linux-hardware.org/?probe=09ae9c9787) | Mar 31, 2021 |
| Apple         | MacBook4,1                  | [74bbc27867](https://linux-hardware.org/?probe=74bbc27867) | Mar 31, 2021 |
| Acer          | Aspire A315-53              | [4e040e7a0e](https://linux-hardware.org/?probe=4e040e7a0e) | Mar 30, 2021 |
| Medion        | Akoya P7818                 | [137cba154e](https://linux-hardware.org/?probe=137cba154e) | Mar 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3c1d98dce9](https://linux-hardware.org/?probe=3c1d98dce9) | Mar 29, 2021 |
| Dell          | Latitude 3400               | [e1cab5dc75](https://linux-hardware.org/?probe=e1cab5dc75) | Mar 29, 2021 |
| ASUSTek       | X550VX                      | [8ca6d8ba59](https://linux-hardware.org/?probe=8ca6d8ba59) | Mar 28, 2021 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [4d0b64cd52](https://linux-hardware.org/?probe=4d0b64cd52) | Mar 27, 2021 |
| Acer          | AOD255                      | [8b63787da8](https://linux-hardware.org/?probe=8b63787da8) | Mar 27, 2021 |
| Acer          | AOD255                      | [0bf011c9bf](https://linux-hardware.org/?probe=0bf011c9bf) | Mar 27, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6dccadd611](https://linux-hardware.org/?probe=6dccadd611) | Mar 26, 2021 |
| Positivo      | Sinatra                     | [6bc774a94f](https://linux-hardware.org/?probe=6bc774a94f) | Mar 25, 2021 |
| Positivo      | Sinatra                     | [a9045ef086](https://linux-hardware.org/?probe=a9045ef086) | Mar 25, 2021 |
| HP            | ProBook 4520s               | [d94784890e](https://linux-hardware.org/?probe=d94784890e) | Mar 22, 2021 |
| HP            | EliteBook 8460p             | [991778f7f8](https://linux-hardware.org/?probe=991778f7f8) | Mar 22, 2021 |
| Unknown       | MS-N034                     | [cdae6abd0c](https://linux-hardware.org/?probe=cdae6abd0c) | Mar 21, 2021 |
| Sony          | VPCEH2F1E                   | [bebb08c44b](https://linux-hardware.org/?probe=bebb08c44b) | Mar 21, 2021 |
| Acer          | Aspire 5750G                | [82fb28dfec](https://linux-hardware.org/?probe=82fb28dfec) | Mar 19, 2021 |
| HP            | Pavilion g6                 | [997f939dc8](https://linux-hardware.org/?probe=997f939dc8) | Mar 18, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [b379414d3c](https://linux-hardware.org/?probe=b379414d3c) | Mar 18, 2021 |
| Dell          | Inspiron 5770               | [5ff61b6654](https://linux-hardware.org/?probe=5ff61b6654) | Mar 18, 2021 |
| DNS           | DNSNB                       | [52e82c78c3](https://linux-hardware.org/?probe=52e82c78c3) | Mar 18, 2021 |
| Lenovo        | G580 20150                  | [5732d94a88](https://linux-hardware.org/?probe=5732d94a88) | Mar 17, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [1f6ee03f00](https://linux-hardware.org/?probe=1f6ee03f00) | Mar 17, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [abfe8f3adb](https://linux-hardware.org/?probe=abfe8f3adb) | Mar 17, 2021 |
| Toshiba       | PORTEGE Z930                | [c0444e41ce](https://linux-hardware.org/?probe=c0444e41ce) | Mar 17, 2021 |
| Dell          | Inspiron 5558               | [437ce713e9](https://linux-hardware.org/?probe=437ce713e9) | Mar 16, 2021 |
| Dell          | Inspiron 5558               | [5af2be25f4](https://linux-hardware.org/?probe=5af2be25f4) | Mar 16, 2021 |
| Acer          | Extensa 5635                | [5bf0144cd3](https://linux-hardware.org/?probe=5bf0144cd3) | Mar 15, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00     | [85555153ea](https://linux-hardware.org/?probe=85555153ea) | Mar 15, 2021 |
| Fujitsu       | FMVA05007                   | [707f6a3ea5](https://linux-hardware.org/?probe=707f6a3ea5) | Mar 14, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [5461951b34](https://linux-hardware.org/?probe=5461951b34) | Mar 14, 2021 |
| HP            | EliteBook 820 G1            | [0cfc5a07d2](https://linux-hardware.org/?probe=0cfc5a07d2) | Mar 09, 2021 |
| Lenovo        | ThinkPad T400 2768BM2       | [b9aea0e95e](https://linux-hardware.org/?probe=b9aea0e95e) | Mar 08, 2021 |
| Lenovo        | ThinkPad T400 2768BM2       | [906ea1b277](https://linux-hardware.org/?probe=906ea1b277) | Mar 08, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [09ff2814ff](https://linux-hardware.org/?probe=09ff2814ff) | Mar 08, 2021 |
| Medion        | P861X                       | [f163e14733](https://linux-hardware.org/?probe=f163e14733) | Mar 07, 2021 |
| Dell          | Vostro 5481                 | [f914e0d1b3](https://linux-hardware.org/?probe=f914e0d1b3) | Mar 07, 2021 |
| HP            | Notebook                    | [a12fa51807](https://linux-hardware.org/?probe=a12fa51807) | Mar 05, 2021 |
| HP            | ProBook 430 G6              | [5ed6cc994b](https://linux-hardware.org/?probe=5ed6cc994b) | Mar 05, 2021 |
| Dell          | Inspiron 1525               | [92c198acb8](https://linux-hardware.org/?probe=92c198acb8) | Mar 05, 2021 |
| Sony          | VPCEG15FB                   | [c23aee4449](https://linux-hardware.org/?probe=c23aee4449) | Mar 05, 2021 |
| Packard Be... | EasyNote TE11HC             | [53a440907b](https://linux-hardware.org/?probe=53a440907b) | Mar 04, 2021 |
| Medion        | P861X                       | [6b6562c621](https://linux-hardware.org/?probe=6b6562c621) | Mar 04, 2021 |
| HP            | ProBook 450 G5              | [ea8530ffe4](https://linux-hardware.org/?probe=ea8530ffe4) | Mar 03, 2021 |
| MSI           | P65 Creator 9SD             | [8cabd1eaa2](https://linux-hardware.org/?probe=8cabd1eaa2) | Mar 03, 2021 |
| MSI           | P65 Creator 9SD             | [217f63acba](https://linux-hardware.org/?probe=217f63acba) | Mar 03, 2021 |
| Sony          | VPCEG15FB                   | [6d895891b9](https://linux-hardware.org/?probe=6d895891b9) | Mar 01, 2021 |
| Sony          | VPCEG15FB                   | [45318e0495](https://linux-hardware.org/?probe=45318e0495) | Feb 28, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [d589c2b2c9](https://linux-hardware.org/?probe=d589c2b2c9) | Feb 27, 2021 |
| Dell          | Latitude E7250              | [3900450df8](https://linux-hardware.org/?probe=3900450df8) | Feb 27, 2021 |
| Medion        | P861X                       | [b2b7b32fe1](https://linux-hardware.org/?probe=b2b7b32fe1) | Feb 26, 2021 |
| Medion        | P861X                       | [ef45a1774d](https://linux-hardware.org/?probe=ef45a1774d) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [9ab78f21ad](https://linux-hardware.org/?probe=9ab78f21ad) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [dd4d88de48](https://linux-hardware.org/?probe=dd4d88de48) | Feb 26, 2021 |
| HP            | ProBook 450 G5              | [cf1f5f9e74](https://linux-hardware.org/?probe=cf1f5f9e74) | Feb 25, 2021 |
| Samsung       | 450R4E/450R5E/450R4V/450... | [15dbf9fad6](https://linux-hardware.org/?probe=15dbf9fad6) | Feb 23, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9924631e4c](https://linux-hardware.org/?probe=9924631e4c) | Feb 23, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [fb1f894d4f](https://linux-hardware.org/?probe=fb1f894d4f) | Feb 22, 2021 |
| ASUSTek       | X502CA                      | [6d275cd9c1](https://linux-hardware.org/?probe=6d275cd9c1) | Feb 22, 2021 |
| Toshiba       | PORTEGE Z30-A               | [a882768f72](https://linux-hardware.org/?probe=a882768f72) | Feb 21, 2021 |
| Sony          | VGN-NW270F                  | [87b755412e](https://linux-hardware.org/?probe=87b755412e) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | [8d0bcb0740](https://linux-hardware.org/?probe=8d0bcb0740) | Feb 19, 2021 |
| ASUSTek       | X550CA                      | [6989572274](https://linux-hardware.org/?probe=6989572274) | Feb 18, 2021 |
| Dell          | Precision 7530              | [0abb5fcc9e](https://linux-hardware.org/?probe=0abb5fcc9e) | Feb 18, 2021 |
| AWOW          | AK41                        | [4b7c8d520f](https://linux-hardware.org/?probe=4b7c8d520f) | Feb 18, 2021 |
| ASUSTek       | M3N                         | [473966e549](https://linux-hardware.org/?probe=473966e549) | Feb 17, 2021 |
| Dell          | Latitude 3400               | [38dbd98cd4](https://linux-hardware.org/?probe=38dbd98cd4) | Feb 15, 2021 |
| Dell          | Inspiron 1545               | [d753427b09](https://linux-hardware.org/?probe=d753427b09) | Feb 15, 2021 |
| Dell          | Latitude 7410               | [ff54e08073](https://linux-hardware.org/?probe=ff54e08073) | Feb 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [f21b611e4c](https://linux-hardware.org/?probe=f21b611e4c) | Feb 14, 2021 |
| Samsung       | R540/R580/R780/SA41/E452    | [2fbfd3fb39](https://linux-hardware.org/?probe=2fbfd3fb39) | Feb 13, 2021 |
| ASUSTek       | X540LJ                      | [a175c9e1fa](https://linux-hardware.org/?probe=a175c9e1fa) | Feb 12, 2021 |
| Compaq        | Presario CQ-31              | [1f32780fe6](https://linux-hardware.org/?probe=1f32780fe6) | Feb 10, 2021 |
| ASUSTek       | X502CA                      | [d180e4c8a5](https://linux-hardware.org/?probe=d180e4c8a5) | Feb 10, 2021 |
| Notebook      | WID2010                     | [ab37cb3ea9](https://linux-hardware.org/?probe=ab37cb3ea9) | Feb 10, 2021 |
| Apple         | MacBookAir4,2               | [1f79c0af85](https://linux-hardware.org/?probe=1f79c0af85) | Feb 09, 2021 |
| NEC Comput... | PC-VY12FBHEW                | [e507fdbcf5](https://linux-hardware.org/?probe=e507fdbcf5) | Feb 08, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [f58cfe253f](https://linux-hardware.org/?probe=f58cfe253f) | Feb 07, 2021 |
| HP            | ProBook 6460b               | [1591c890ac](https://linux-hardware.org/?probe=1591c890ac) | Feb 07, 2021 |
| Lenovo        | ThinkPad W510 4389W1B       | [ec27151293](https://linux-hardware.org/?probe=ec27151293) | Feb 06, 2021 |
| Lenovo        | ThinkPad W540 20BG0011US    | [8c37963ac0](https://linux-hardware.org/?probe=8c37963ac0) | Feb 06, 2021 |
| Acer          | AO722                       | [24cb20b715](https://linux-hardware.org/?probe=24cb20b715) | Feb 04, 2021 |
| Lenovo        | ThinkPad L470 20J4003WGE    | [6738439de9](https://linux-hardware.org/?probe=6738439de9) | Feb 04, 2021 |
| Acer          | Swift SF313-52G             | [2967386924](https://linux-hardware.org/?probe=2967386924) | Feb 03, 2021 |
| HP            | EliteBook 8560p             | [758cca4c76](https://linux-hardware.org/?probe=758cca4c76) | Feb 03, 2021 |
| TQ-Group      | TQMxE39S                    | [29e62e5a47](https://linux-hardware.org/?probe=29e62e5a47) | Feb 02, 2021 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [b877012ac5](https://linux-hardware.org/?probe=b877012ac5) | Feb 02, 2021 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [a147d69ec6](https://linux-hardware.org/?probe=a147d69ec6) | Feb 02, 2021 |
| Toshiba       | Satellite L745              | [01a4eafbb6](https://linux-hardware.org/?probe=01a4eafbb6) | Feb 02, 2021 |
| Toshiba       | Satellite L745              | [9cc5c245d0](https://linux-hardware.org/?probe=9cc5c245d0) | Feb 02, 2021 |
| TQ-Group      | TQMxE39S                    | [3ba32b937a](https://linux-hardware.org/?probe=3ba32b937a) | Feb 01, 2021 |
| Dell          | Inspiron 3476               | [29d2ce51a0](https://linux-hardware.org/?probe=29d2ce51a0) | Feb 01, 2021 |
| Dell          | Inspiron 3476               | [6571492610](https://linux-hardware.org/?probe=6571492610) | Jan 31, 2021 |
| HP            | ZBook 15 G2                 | [cebba8a2a8](https://linux-hardware.org/?probe=cebba8a2a8) | Jan 30, 2021 |
| Toshiba       | PORTEGE Z30-E               | [34fed11e38](https://linux-hardware.org/?probe=34fed11e38) | Jan 29, 2021 |
| Lenovo        | ThinkPad T430 2349W2P       | [58c2f66dd6](https://linux-hardware.org/?probe=58c2f66dd6) | Jan 26, 2021 |
| Samsung       | 530XBB                      | [d26d07411e](https://linux-hardware.org/?probe=d26d07411e) | Jan 26, 2021 |
| Samsung       | 530XBB                      | [cfe518bb71](https://linux-hardware.org/?probe=cfe518bb71) | Jan 26, 2021 |
| Dell          | Inspiron 5759               | [9e0d8f1e09](https://linux-hardware.org/?probe=9e0d8f1e09) | Jan 25, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [ea06fcd265](https://linux-hardware.org/?probe=ea06fcd265) | Jan 23, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [8730d258c7](https://linux-hardware.org/?probe=8730d258c7) | Jan 23, 2021 |
| Dell          | Latitude 5590               | [14a9a52de5](https://linux-hardware.org/?probe=14a9a52de5) | Jan 23, 2021 |
| Dell          | System XPS L321X            | [3473b7b95b](https://linux-hardware.org/?probe=3473b7b95b) | Jan 23, 2021 |
| Dell          | Latitude 5500               | [4334424504](https://linux-hardware.org/?probe=4334424504) | Jan 22, 2021 |
| HP            | 14                          | [7c1ff6f4a8](https://linux-hardware.org/?probe=7c1ff6f4a8) | Jan 22, 2021 |
| Dell          | Inspiron 5759               | [6e8ab4a0a6](https://linux-hardware.org/?probe=6e8ab4a0a6) | Jan 22, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [fa99318483](https://linux-hardware.org/?probe=fa99318483) | Jan 21, 2021 |
| Fujitsu       | LIFEBOOK T936               | [50c2127f6c](https://linux-hardware.org/?probe=50c2127f6c) | Jan 20, 2021 |
| Dell          | Latitude E7250              | [d42f7cb3fa](https://linux-hardware.org/?probe=d42f7cb3fa) | Jan 20, 2021 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [784b99a6ce](https://linux-hardware.org/?probe=784b99a6ce) | Jan 20, 2021 |
| HP            | ProBook 4430s               | [3257de56a2](https://linux-hardware.org/?probe=3257de56a2) | Jan 19, 2021 |
| HP            | 2000                        | [2519b222b7](https://linux-hardware.org/?probe=2519b222b7) | Jan 19, 2021 |
| Acer          | Nitro AN515-42              | [2e43134d4d](https://linux-hardware.org/?probe=2e43134d4d) | Jan 18, 2021 |
| HP            | ProBook 4430s               | [7d8c32fade](https://linux-hardware.org/?probe=7d8c32fade) | Jan 18, 2021 |
| HP            | ProBook 4430s               | [d04aa71783](https://linux-hardware.org/?probe=d04aa71783) | Jan 18, 2021 |
| Dell          | Inspiron 5758               | [4f86ee832f](https://linux-hardware.org/?probe=4f86ee832f) | Jan 17, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c5676ad337](https://linux-hardware.org/?probe=c5676ad337) | Jan 17, 2021 |
| HP            | Pavilion g4                 | [daf6ec798d](https://linux-hardware.org/?probe=daf6ec798d) | Jan 16, 2021 |
| Acer          | Aspire E1-571G              | [051b3d5b1b](https://linux-hardware.org/?probe=051b3d5b1b) | Jan 16, 2021 |
| Dell          | Vostro 5581                 | [b706435c71](https://linux-hardware.org/?probe=b706435c71) | Jan 15, 2021 |
| HP            | Pavilion g4                 | [e25bba2671](https://linux-hardware.org/?probe=e25bba2671) | Jan 15, 2021 |
| Dell          | XPS 13 9370                 | [c473e50c22](https://linux-hardware.org/?probe=c473e50c22) | Jan 15, 2021 |
| HP            | Pavilion g4                 | [8a3ec7530f](https://linux-hardware.org/?probe=8a3ec7530f) | Jan 15, 2021 |
| Acer          | AOD260                      | [2e870327a5](https://linux-hardware.org/?probe=2e870327a5) | Jan 14, 2021 |
| OEM           | I42IL1                      | [5bcf596d04](https://linux-hardware.org/?probe=5bcf596d04) | Jan 13, 2021 |
| OEM           | I42IL1                      | [eec557e8a3](https://linux-hardware.org/?probe=eec557e8a3) | Jan 13, 2021 |
| Acer          | Aspire 5733                 | [f8a533c52e](https://linux-hardware.org/?probe=f8a533c52e) | Jan 13, 2021 |
| Acer          | Aspire 5500                 | [0c32c44824](https://linux-hardware.org/?probe=0c32c44824) | Jan 13, 2021 |
| Lenovo        | Y50-70 20378                | [bd8a498830](https://linux-hardware.org/?probe=bd8a498830) | Jan 13, 2021 |
| HP            | Pavilion g4                 | [ca2648fcd9](https://linux-hardware.org/?probe=ca2648fcd9) | Jan 13, 2021 |
| HP            | EliteBook 840 G4            | [2e35accad4](https://linux-hardware.org/?probe=2e35accad4) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [d033697e79](https://linux-hardware.org/?probe=d033697e79) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [6173e9c6e9](https://linux-hardware.org/?probe=6173e9c6e9) | Jan 12, 2021 |
| HP            | Compaq Presario CQ40        | [e2f6812ec3](https://linux-hardware.org/?probe=e2f6812ec3) | Jan 12, 2021 |
| ASUSTek       | 1005HA                      | [fad7f0bc8b](https://linux-hardware.org/?probe=fad7f0bc8b) | Jan 11, 2021 |
| Lenovo        | IdeaPad 5-14ARE05 81YH      | [49eb50f6ed](https://linux-hardware.org/?probe=49eb50f6ed) | Jan 10, 2021 |
| Dell          | Inspiron MM061              | [3e50fa5e32](https://linux-hardware.org/?probe=3e50fa5e32) | Jan 09, 2021 |
| HP            | ProBook 450 G5              | [64d6bacec9](https://linux-hardware.org/?probe=64d6bacec9) | Jan 08, 2021 |
| Dell          | Inspiron 5759               | [0aa13edd6e](https://linux-hardware.org/?probe=0aa13edd6e) | Jan 08, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [ffeb181a7f](https://linux-hardware.org/?probe=ffeb181a7f) | Jan 08, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [5b2eb10b23](https://linux-hardware.org/?probe=5b2eb10b23) | Jan 08, 2021 |
| Dell          | Inspiron 15-3567            | [b04793329d](https://linux-hardware.org/?probe=b04793329d) | Jan 08, 2021 |
| Acer          | AOD270                      | [87022fc325](https://linux-hardware.org/?probe=87022fc325) | Jan 08, 2021 |
| HP            | ProBook 450 G5              | [1d06bfe495](https://linux-hardware.org/?probe=1d06bfe495) | Jan 07, 2021 |
| Dell          | Inspiron 15-3567            | [c7858d53bd](https://linux-hardware.org/?probe=c7858d53bd) | Jan 07, 2021 |
| Dell          | XPS 13 9310                 | [30421146e3](https://linux-hardware.org/?probe=30421146e3) | Jan 06, 2021 |
| ASUSTek       | K72Dr                       | [a19348d5c3](https://linux-hardware.org/?probe=a19348d5c3) | Jan 06, 2021 |
| Dell          | Vostro 5568                 | [0aafa8d5ad](https://linux-hardware.org/?probe=0aafa8d5ad) | Jan 04, 2021 |
| Dell          | Latitude E7250              | [dd8a0c1b99](https://linux-hardware.org/?probe=dd8a0c1b99) | Jan 04, 2021 |
| Dell          | Vostro 5568                 | [24a223a939](https://linux-hardware.org/?probe=24a223a939) | Jan 04, 2021 |
| Lenovo        | G470 4328                   | [1e6d2c2fa7](https://linux-hardware.org/?probe=1e6d2c2fa7) | Jan 03, 2021 |
| Lenovo        | ThinkPad X220 4291G26       | [d4a21bf0b4](https://linux-hardware.org/?probe=d4a21bf0b4) | Jan 03, 2021 |
| HP            | Laptop 15-bs0xx             | [96280026fb](https://linux-hardware.org/?probe=96280026fb) | Jan 03, 2021 |
| MSI           | GE60 2PL                    | [b8ce59aa6d](https://linux-hardware.org/?probe=b8ce59aa6d) | Jan 02, 2021 |
| Lenovo        | ThinkPad T400 6475WJE       | [3a031a442a](https://linux-hardware.org/?probe=3a031a442a) | Dec 30, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [70d4988c38](https://linux-hardware.org/?probe=70d4988c38) | Dec 30, 2020 |
| HP            | 15 Notebook PC              | [1516d5001c](https://linux-hardware.org/?probe=1516d5001c) | Dec 30, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [84d1c38593](https://linux-hardware.org/?probe=84d1c38593) | Dec 29, 2020 |
| Lenovo        | ThinkPad T510 4384GEG       | [c474fe92ae](https://linux-hardware.org/?probe=c474fe92ae) | Dec 28, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0130... | [0d147e3e19](https://linux-hardware.org/?probe=0d147e3e19) | Dec 28, 2020 |
| Acer          | Aspire E5-575G              | [0ecf1d8c7a](https://linux-hardware.org/?probe=0ecf1d8c7a) | Dec 27, 2020 |
| Lenovo        | ThinkPad T510 4384GEG       | [8131aa0117](https://linux-hardware.org/?probe=8131aa0117) | Dec 27, 2020 |
| Lenovo        | G470 4328                   | [e146dc2fa6](https://linux-hardware.org/?probe=e146dc2fa6) | Dec 27, 2020 |
| Lenovo        | G470 4328                   | [a590a273ae](https://linux-hardware.org/?probe=a590a273ae) | Dec 27, 2020 |
| HP            | EliteBook 2530p             | [a86252d9a4](https://linux-hardware.org/?probe=a86252d9a4) | Dec 26, 2020 |
| Toshiba       | QOSMIO X500                 | [721a4df615](https://linux-hardware.org/?probe=721a4df615) | Dec 25, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [1d66647923](https://linux-hardware.org/?probe=1d66647923) | Dec 25, 2020 |
| Toshiba       | QOSMIO X500                 | [97da5221b4](https://linux-hardware.org/?probe=97da5221b4) | Dec 25, 2020 |
| Lenovo        | ThinkPad T460 20FMS08Q1B    | [97f9380c82](https://linux-hardware.org/?probe=97f9380c82) | Dec 24, 2020 |
| Samsung       | 700T1C                      | [0f8a8671f2](https://linux-hardware.org/?probe=0f8a8671f2) | Dec 24, 2020 |
| Acer          | Aspire E1-522               | [f6e709b997](https://linux-hardware.org/?probe=f6e709b997) | Dec 24, 2020 |
| HP            | Laptop 15-bs0xx             | [ec5fac5f1d](https://linux-hardware.org/?probe=ec5fac5f1d) | Dec 24, 2020 |
| Razer         | Blade Stealth               | [95a291be2f](https://linux-hardware.org/?probe=95a291be2f) | Dec 24, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [41f994ec7a](https://linux-hardware.org/?probe=41f994ec7a) | Dec 23, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [f6164f5e30](https://linux-hardware.org/?probe=f6164f5e30) | Dec 23, 2020 |
| HP            | 15                          | [fb0dc2a746](https://linux-hardware.org/?probe=fb0dc2a746) | Dec 22, 2020 |
| Unknown       | Unknown                     | [fede086cb3](https://linux-hardware.org/?probe=fede086cb3) | Dec 21, 2020 |
| HP            | EliteBook 2530p             | [1b75d84b36](https://linux-hardware.org/?probe=1b75d84b36) | Dec 21, 2020 |
| Unknown       | Unknown                     | [c595a3f1df](https://linux-hardware.org/?probe=c595a3f1df) | Dec 20, 2020 |
| Lenovo        | ThinkPad T490s 20NX001PM... | [af7d2d4eb5](https://linux-hardware.org/?probe=af7d2d4eb5) | Dec 20, 2020 |
| Dell          | Vostro 3500                 | [087f314510](https://linux-hardware.org/?probe=087f314510) | Dec 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7877a13441](https://linux-hardware.org/?probe=7877a13441) | Dec 20, 2020 |
| LG Electro... | 17Z990-R.AAS8U1             | [2041c116d0](https://linux-hardware.org/?probe=2041c116d0) | Dec 19, 2020 |
| ASUSTek       | U47A                        | [aedbc963d2](https://linux-hardware.org/?probe=aedbc963d2) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | [c5c8b0a320](https://linux-hardware.org/?probe=c5c8b0a320) | Dec 19, 2020 |
| Lenovo        | G50-80 80E5                 | [8cbf5e0e76](https://linux-hardware.org/?probe=8cbf5e0e76) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | [1a68fc4e19](https://linux-hardware.org/?probe=1a68fc4e19) | Dec 19, 2020 |
| Dell          | Latitude 5410               | [b53a7b8fb2](https://linux-hardware.org/?probe=b53a7b8fb2) | Dec 18, 2020 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [d33dee579a](https://linux-hardware.org/?probe=d33dee579a) | Dec 18, 2020 |
| Dell          | Latitude 5410               | [916db21f7f](https://linux-hardware.org/?probe=916db21f7f) | Dec 18, 2020 |
| Lenovo        | Y50-70 20378                | [5774f5c238](https://linux-hardware.org/?probe=5774f5c238) | Dec 16, 2020 |
| Toshiba       | TECRA R840                  | [731c5ca5c0](https://linux-hardware.org/?probe=731c5ca5c0) | Dec 16, 2020 |
| HKC           | N14DC                       | [9d7b0e9f25](https://linux-hardware.org/?probe=9d7b0e9f25) | Dec 16, 2020 |
| HKC           | N14DC                       | [13773e90fb](https://linux-hardware.org/?probe=13773e90fb) | Dec 16, 2020 |
| HASEE Comp... | PF4WN2F                     | [9855617493](https://linux-hardware.org/?probe=9855617493) | Dec 15, 2020 |
| Lenovo        | ThinkPad T460s 20FAS3KA0... | [df948532a2](https://linux-hardware.org/?probe=df948532a2) | Dec 14, 2020 |
| Lenovo        | G50-80 80E5                 | [6c2a460153](https://linux-hardware.org/?probe=6c2a460153) | Dec 13, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [d89c8f909d](https://linux-hardware.org/?probe=d89c8f909d) | Dec 12, 2020 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [372fdf9c03](https://linux-hardware.org/?probe=372fdf9c03) | Dec 12, 2020 |
| HP            | Laptop 17-by0xxx            | [0d9769c8f9](https://linux-hardware.org/?probe=0d9769c8f9) | Dec 11, 2020 |
| HP            | Laptop 17-by0xxx            | [7ebb00e08b](https://linux-hardware.org/?probe=7ebb00e08b) | Dec 10, 2020 |
| Acer          | Aspire SW5-011              | [612ef7c91d](https://linux-hardware.org/?probe=612ef7c91d) | Dec 09, 2020 |
| Acer          | Aspire E5-575G              | [7c88c8eb8e](https://linux-hardware.org/?probe=7c88c8eb8e) | Dec 09, 2020 |
| Dell          | Inspiron 5468               | [abc26c7422](https://linux-hardware.org/?probe=abc26c7422) | Dec 09, 2020 |
| Acer          | Aspire E1-571G              | [561c205338](https://linux-hardware.org/?probe=561c205338) | Dec 08, 2020 |
| ASUSTek       | U36SD                       | [6c4da274f4](https://linux-hardware.org/?probe=6c4da274f4) | Dec 08, 2020 |
| ASUSTek       | U36SD                       | [8044a5aefc](https://linux-hardware.org/?probe=8044a5aefc) | Dec 08, 2020 |
| TUXEDO        | BC1510 1710                 | [62db77e43b](https://linux-hardware.org/?probe=62db77e43b) | Dec 08, 2020 |
| Lenovo        | ThinkPad T490 20N2000FIX    | [ddb7050747](https://linux-hardware.org/?probe=ddb7050747) | Dec 08, 2020 |
| Dell          | Latitude 3450               | [a3b5d0a699](https://linux-hardware.org/?probe=a3b5d0a699) | Dec 07, 2020 |
| ASUSTek       | X550CA                      | [b9335cdc7d](https://linux-hardware.org/?probe=b9335cdc7d) | Dec 06, 2020 |
| HP            | ProBook 4330s               | [22a64b85be](https://linux-hardware.org/?probe=22a64b85be) | Dec 06, 2020 |
| ASUSTek       | X555UJ                      | [188414bc01](https://linux-hardware.org/?probe=188414bc01) | Dec 05, 2020 |
| Acer          | Nitro AN515-51              | [018f6ee8e7](https://linux-hardware.org/?probe=018f6ee8e7) | Dec 04, 2020 |
| Dell          | Latitude E7470              | [a508e0ea38](https://linux-hardware.org/?probe=a508e0ea38) | Dec 04, 2020 |
| Dell          | Latitude E7470              | [22f9cd851d](https://linux-hardware.org/?probe=22f9cd851d) | Dec 04, 2020 |
| Lenovo        | IdeaPad Z400 20201          | [9f4318e1fa](https://linux-hardware.org/?probe=9f4318e1fa) | Dec 03, 2020 |
| Lenovo        | K2450 20243                 | [33409ba105](https://linux-hardware.org/?probe=33409ba105) | Dec 03, 2020 |
| HP            | ProBook 4330s               | [d7d25ffae4](https://linux-hardware.org/?probe=d7d25ffae4) | Dec 03, 2020 |
| ASUSTek       | X540LJ                      | [b3a5455685](https://linux-hardware.org/?probe=b3a5455685) | Dec 02, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [483fc6afa3](https://linux-hardware.org/?probe=483fc6afa3) | Dec 02, 2020 |
| HP            | 2000                        | [27fed77b24](https://linux-hardware.org/?probe=27fed77b24) | Dec 02, 2020 |
| HP            | Laptop 15-ra0xx             | [b4b9f9d397](https://linux-hardware.org/?probe=b4b9f9d397) | Dec 02, 2020 |
| HP            | Laptop 15-ra0xx             | [4a0f3ebf74](https://linux-hardware.org/?probe=4a0f3ebf74) | Dec 02, 2020 |
| Acer          | Aspire SW5-014              | [c5a45fdd73](https://linux-hardware.org/?probe=c5a45fdd73) | Dec 01, 2020 |
| HP            | Compaq nc4400 (EY605EA)     | [24cb6d0d7d](https://linux-hardware.org/?probe=24cb6d0d7d) | Nov 30, 2020 |
| Acer          | Predator G5-793             | [ae170a3127](https://linux-hardware.org/?probe=ae170a3127) | Nov 30, 2020 |
| Lenovo        | ThinkPad T420 4236S3C       | [7a61b58c47](https://linux-hardware.org/?probe=7a61b58c47) | Nov 29, 2020 |
| HP            | Pavilion Notebook           | [4b3484d5dc](https://linux-hardware.org/?probe=4b3484d5dc) | Nov 29, 2020 |
| Dell          | Vostro 5490                 | [24dae188aa](https://linux-hardware.org/?probe=24dae188aa) | Nov 29, 2020 |
| ASUSTek       | S551LN                      | [0ecda2cfde](https://linux-hardware.org/?probe=0ecda2cfde) | Nov 28, 2020 |
| Dell          | Precision M6800             | [44d8478dde](https://linux-hardware.org/?probe=44d8478dde) | Nov 28, 2020 |
| Dell          | Inspiron 5575               | [269f2e1ac1](https://linux-hardware.org/?probe=269f2e1ac1) | Nov 27, 2020 |
| Lenovo        | ThinkPad T470 20HE0055IT    | [8b24f7ba55](https://linux-hardware.org/?probe=8b24f7ba55) | Nov 27, 2020 |
| ASUSTek       | P751JA                      | [0ed58c84dc](https://linux-hardware.org/?probe=0ed58c84dc) | Nov 27, 2020 |
| Dell          | XPS 13 9360                 | [3f73c1ef56](https://linux-hardware.org/?probe=3f73c1ef56) | Nov 27, 2020 |
| Lenovo        | ThinkPad T420 4180AG3       | [9755a34429](https://linux-hardware.org/?probe=9755a34429) | Nov 27, 2020 |
| Acer          | AO722                       | [c94a10cc9f](https://linux-hardware.org/?probe=c94a10cc9f) | Nov 26, 2020 |
| Acer          | AO722                       | [2cd94435a2](https://linux-hardware.org/?probe=2cd94435a2) | Nov 26, 2020 |
| Lenovo        | ThinkPad T420 4180AG3       | [8661dfb757](https://linux-hardware.org/?probe=8661dfb757) | Nov 26, 2020 |
| HP            | ENVY 14 SPECTRE             | [d2fdd9e4a1](https://linux-hardware.org/?probe=d2fdd9e4a1) | Nov 25, 2020 |
| Acer          | Aspire SW5-011              | [1a272e1a91](https://linux-hardware.org/?probe=1a272e1a91) | Nov 24, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [814797bb7b](https://linux-hardware.org/?probe=814797bb7b) | Nov 24, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [a45fc859a5](https://linux-hardware.org/?probe=a45fc859a5) | Nov 24, 2020 |
| Dell          | Studio 1737                 | [d2d9b5de2c](https://linux-hardware.org/?probe=d2d9b5de2c) | Nov 24, 2020 |
| Dell          | Studio 1737                 | [c5e6461593](https://linux-hardware.org/?probe=c5e6461593) | Nov 23, 2020 |
| Lenovo        | IdeaPad Y470 0855           | [76c42f7133](https://linux-hardware.org/?probe=76c42f7133) | Nov 22, 2020 |
| Lenovo        | ThinkPad X240 20AM0012UK    | [36ef2f5173](https://linux-hardware.org/?probe=36ef2f5173) | Nov 22, 2020 |
| Dell          | Inspiron 1750               | [612608a41f](https://linux-hardware.org/?probe=612608a41f) | Nov 21, 2020 |
| Dell          | Latitude E7450              | [d1a21c867e](https://linux-hardware.org/?probe=d1a21c867e) | Nov 20, 2020 |
| HP            | ProBook 440 G6              | [3bf08d722f](https://linux-hardware.org/?probe=3bf08d722f) | Nov 20, 2020 |
| HP            | ProBook 440 G6              | [ce48688759](https://linux-hardware.org/?probe=ce48688759) | Nov 20, 2020 |
| Acer          | TMP453-MG                   | [78f12b69b1](https://linux-hardware.org/?probe=78f12b69b1) | Nov 20, 2020 |
| Lenovo        | ThinkPad T430 2349V4B       | [989a5dd973](https://linux-hardware.org/?probe=989a5dd973) | Nov 20, 2020 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [3f0b7e56fd](https://linux-hardware.org/?probe=3f0b7e56fd) | Nov 19, 2020 |
| Acer          | Aspire E5-573G              | [4349229de0](https://linux-hardware.org/?probe=4349229de0) | Nov 19, 2020 |
| MSI           | GS43VR 7RE                  | [8747674074](https://linux-hardware.org/?probe=8747674074) | Nov 19, 2020 |
| Lenovo        | ThinkPad X240 20AM0012UK    | [cdde05e888](https://linux-hardware.org/?probe=cdde05e888) | Nov 19, 2020 |
| AMI           | Intel                       | [9c441fe3fe](https://linux-hardware.org/?probe=9c441fe3fe) | Nov 19, 2020 |
| ASUSTek       | X405UA                      | [e27b62e8d8](https://linux-hardware.org/?probe=e27b62e8d8) | Nov 19, 2020 |
| HP            | Laptop 15-bs0xx             | [1119089279](https://linux-hardware.org/?probe=1119089279) | Nov 19, 2020 |
| Lenovo        | K2450 20243                 | [4d44042257](https://linux-hardware.org/?probe=4d44042257) | Nov 19, 2020 |
| HP            | ENVY 17                     | [bf909911a4](https://linux-hardware.org/?probe=bf909911a4) | Nov 18, 2020 |
| HP            | Spectre 13 Ultrabook        | [a86f00c084](https://linux-hardware.org/?probe=a86f00c084) | Nov 18, 2020 |
| Dell          | Inspiron 5458               | [b3dfa8268c](https://linux-hardware.org/?probe=b3dfa8268c) | Nov 17, 2020 |
| Lenovo        | ThinkPad E14 20RAS0D800     | [917538201a](https://linux-hardware.org/?probe=917538201a) | Nov 16, 2020 |
| Lenovo        | ThinkPad T420 4236S3C       | [19f2fc978a](https://linux-hardware.org/?probe=19f2fc978a) | Nov 15, 2020 |
| HP            | Pavilion dv5                | [5f998846eb](https://linux-hardware.org/?probe=5f998846eb) | Nov 15, 2020 |
| Acer          | Aspire V5-132               | [166921ade6](https://linux-hardware.org/?probe=166921ade6) | Nov 13, 2020 |
| HP            | EliteBook 820 G1            | [6f2db7955a](https://linux-hardware.org/?probe=6f2db7955a) | Nov 12, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [b2a9b6016f](https://linux-hardware.org/?probe=b2a9b6016f) | Nov 12, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [bff1d5b08f](https://linux-hardware.org/?probe=bff1d5b08f) | Nov 12, 2020 |
| HP            | Laptop 15s-fq0xxx           | [7c89e8677b](https://linux-hardware.org/?probe=7c89e8677b) | Nov 12, 2020 |
| HP            | Laptop 15s-fq0xxx           | [e996126e7f](https://linux-hardware.org/?probe=e996126e7f) | Nov 12, 2020 |
| Alienware     | M14xR1                      | [b09cb4d7f0](https://linux-hardware.org/?probe=b09cb4d7f0) | Nov 12, 2020 |
| ASUSTek       | X555YI                      | [2092b326b1](https://linux-hardware.org/?probe=2092b326b1) | Nov 11, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | [2e00b39df5](https://linux-hardware.org/?probe=2e00b39df5) | Nov 11, 2020 |
| Dell          | Inspiron 5593               | [56bad4dbd3](https://linux-hardware.org/?probe=56bad4dbd3) | Nov 10, 2020 |
| Unknown       | Unknown                     | [f69e448774](https://linux-hardware.org/?probe=f69e448774) | Nov 10, 2020 |
| Toshiba       | Satellite C55-C             | [7e51e0b053](https://linux-hardware.org/?probe=7e51e0b053) | Nov 09, 2020 |
| HP            | EliteBook Folio 1040 G1     | [fbe8776f75](https://linux-hardware.org/?probe=fbe8776f75) | Nov 08, 2020 |
| HP            | EliteBook Folio 1040 G1     | [d8a6f3824f](https://linux-hardware.org/?probe=d8a6f3824f) | Nov 08, 2020 |
| Apple         | MacBookPro10,1              | [de48058cc4](https://linux-hardware.org/?probe=de48058cc4) | Nov 07, 2020 |
| Dell          | Inspiron 5370               | [a7ffc4fdf0](https://linux-hardware.org/?probe=a7ffc4fdf0) | Nov 07, 2020 |
| Acer          | TMP453-MG                   | [1d55620e4d](https://linux-hardware.org/?probe=1d55620e4d) | Nov 05, 2020 |
| Dell          | Latitude E6530              | [46ebf29e8a](https://linux-hardware.org/?probe=46ebf29e8a) | Nov 03, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [4b34114e72](https://linux-hardware.org/?probe=4b34114e72) | Nov 03, 2020 |
| DataLogic     | U50SI                       | [d49f5970f4](https://linux-hardware.org/?probe=d49f5970f4) | Nov 02, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [54079a5e32](https://linux-hardware.org/?probe=54079a5e32) | Nov 02, 2020 |
| Samsung       | 940Z5L                      | [82a5d79b0f](https://linux-hardware.org/?probe=82a5d79b0f) | Nov 01, 2020 |
| Unknown       | Unknown                     | [a98cf1ca14](https://linux-hardware.org/?probe=a98cf1ca14) | Oct 31, 2020 |
| Dell          | Latitude E6530              | [620044198e](https://linux-hardware.org/?probe=620044198e) | Oct 31, 2020 |
| Packard Be... | EasyNote TE11HC             | [ed0818d3b2](https://linux-hardware.org/?probe=ed0818d3b2) | Oct 30, 2020 |
| Dell          | Inspiron 7520               | [a91074b57a](https://linux-hardware.org/?probe=a91074b57a) | Oct 29, 2020 |
| Lenovo        | E31-80 80MX                 | [d56dacea36](https://linux-hardware.org/?probe=d56dacea36) | Oct 29, 2020 |
| Chuwi         | LapBook Pro                 | [1c33f10570](https://linux-hardware.org/?probe=1c33f10570) | Oct 28, 2020 |
| Positivo B... | VJFE42F11X-XXXXXX           | [6febf84141](https://linux-hardware.org/?probe=6febf84141) | Oct 28, 2020 |
| Dell          | Inspiron N5110              | [a74340225d](https://linux-hardware.org/?probe=a74340225d) | Oct 27, 2020 |
| HP            | ProBook 450 G7              | [d0857726ae](https://linux-hardware.org/?probe=d0857726ae) | Oct 27, 2020 |
| Sony          | SVE14122CXW                 | [c399c9b6e1](https://linux-hardware.org/?probe=c399c9b6e1) | Oct 27, 2020 |
| Acer          | Aspire 5250                 | [6cf22de87a](https://linux-hardware.org/?probe=6cf22de87a) | Oct 26, 2020 |
| Samsung       | 300V3Z/300V4Z/300V5Z/200... | [e9ff5b55dc](https://linux-hardware.org/?probe=e9ff5b55dc) | Oct 25, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [ac21cb55bf](https://linux-hardware.org/?probe=ac21cb55bf) | Oct 23, 2020 |
| Lenovo        | B50-50 80S2                 | [098d0c417d](https://linux-hardware.org/?probe=098d0c417d) | Oct 23, 2020 |
| Apple         | MacBookAir7,2               | [5b033684f7](https://linux-hardware.org/?probe=5b033684f7) | Oct 22, 2020 |
| Dell          | Latitude E5520              | [2a250b5803](https://linux-hardware.org/?probe=2a250b5803) | Oct 22, 2020 |
| ASUSTek       | X45C                        | [20cb6e4a37](https://linux-hardware.org/?probe=20cb6e4a37) | Oct 22, 2020 |
| Dell          | Latitude 7400               | [fbe3992713](https://linux-hardware.org/?probe=fbe3992713) | Oct 22, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | [982e283d23](https://linux-hardware.org/?probe=982e283d23) | Oct 22, 2020 |
| Apple         | MacBookAir7,2               | [9569430cd1](https://linux-hardware.org/?probe=9569430cd1) | Oct 22, 2020 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [a45cbea600](https://linux-hardware.org/?probe=a45cbea600) | Oct 21, 2020 |
| HP            | OMEN by Laptop              | [6bba0d34d9](https://linux-hardware.org/?probe=6bba0d34d9) | Oct 21, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8b528f1d9d](https://linux-hardware.org/?probe=8b528f1d9d) | Oct 21, 2020 |
| Dell          | XPS 13 9360                 | [f5425945c2](https://linux-hardware.org/?probe=f5425945c2) | Oct 21, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [71e64e6440](https://linux-hardware.org/?probe=71e64e6440) | Oct 20, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [1ebdcf1f2f](https://linux-hardware.org/?probe=1ebdcf1f2f) | Oct 20, 2020 |
| Apple         | MacBookAir7,2               | [4fcbaab79c](https://linux-hardware.org/?probe=4fcbaab79c) | Oct 20, 2020 |
| HP            | EliteBook 6930p             | [b5fbfcf0a5](https://linux-hardware.org/?probe=b5fbfcf0a5) | Oct 19, 2020 |
| HP            | EliteBook 6930p             | [fe166def1e](https://linux-hardware.org/?probe=fe166def1e) | Oct 19, 2020 |
| Dell          | Inspiron 5570               | [225dbd1e07](https://linux-hardware.org/?probe=225dbd1e07) | Oct 19, 2020 |
| HP            | Mini 210-2000               | [0a83b3e845](https://linux-hardware.org/?probe=0a83b3e845) | Oct 18, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [341bd94c9a](https://linux-hardware.org/?probe=341bd94c9a) | Oct 17, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [816b92a100](https://linux-hardware.org/?probe=816b92a100) | Oct 16, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [06fba260a1](https://linux-hardware.org/?probe=06fba260a1) | Oct 16, 2020 |
| Dell          | Inspiron 5505               | [5dac15d30a](https://linux-hardware.org/?probe=5dac15d30a) | Oct 16, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [83acd207c5](https://linux-hardware.org/?probe=83acd207c5) | Oct 16, 2020 |
| Samsung       | RV409/RV509/RV709           | [81c0bf9823](https://linux-hardware.org/?probe=81c0bf9823) | Oct 15, 2020 |
| Alienware     | 17 R4                       | [2fe13da62c](https://linux-hardware.org/?probe=2fe13da62c) | Oct 15, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| HP            | EliteBook 2540p             | [7768f6fe36](https://linux-hardware.org/?probe=7768f6fe36) | Oct 14, 2020 |
| Dell          | Inspiron N5110              | [d95238f805](https://linux-hardware.org/?probe=d95238f805) | Oct 14, 2020 |
| Alienware     | 17 R4                       | [9b2f19cc3c](https://linux-hardware.org/?probe=9b2f19cc3c) | Oct 14, 2020 |
| Samsung       | N248P                       | [74486c5431](https://linux-hardware.org/?probe=74486c5431) | Oct 14, 2020 |
| Lenovo        | ThinkPad T520 4243GE9       | [d4a560f987](https://linux-hardware.org/?probe=d4a560f987) | Oct 14, 2020 |
| HP            | ProBook 640 G1              | [e9b2b31708](https://linux-hardware.org/?probe=e9b2b31708) | Oct 13, 2020 |
| Lenovo        | ThinkPad X220 4291B66       | [0428020229](https://linux-hardware.org/?probe=0428020229) | Oct 11, 2020 |
| HP            | Pavilion Notebook           | [6cfa593625](https://linux-hardware.org/?probe=6cfa593625) | Oct 11, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9bf6f0ba43](https://linux-hardware.org/?probe=9bf6f0ba43) | Oct 09, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [65ead373b6](https://linux-hardware.org/?probe=65ead373b6) | Oct 07, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [318f21861c](https://linux-hardware.org/?probe=318f21861c) | Oct 06, 2020 |
| Dell          | XPS 13 9350                 | [706d160916](https://linux-hardware.org/?probe=706d160916) | Oct 06, 2020 |
| Dell          | Latitude 7490               | [f4d8a0e5e9](https://linux-hardware.org/?probe=f4d8a0e5e9) | Oct 06, 2020 |
| Dell          | Latitude E5530 non-vPro     | [86aa78e5af](https://linux-hardware.org/?probe=86aa78e5af) | Oct 05, 2020 |
| Dell          | Latitude E5530 non-vPro     | [c535d537e1](https://linux-hardware.org/?probe=c535d537e1) | Oct 05, 2020 |
| Dell          | Inspiron 5547               | [14ee547f91](https://linux-hardware.org/?probe=14ee547f91) | Oct 04, 2020 |
| Sony          | VPCYB3V1E                   | [f116097e48](https://linux-hardware.org/?probe=f116097e48) | Oct 02, 2020 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [ceb25a15f1](https://linux-hardware.org/?probe=ceb25a15f1) | Oct 02, 2020 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [e5c4b71e07](https://linux-hardware.org/?probe=e5c4b71e07) | Oct 01, 2020 |
| PC Special... | N150CU                      | [d6855993c3](https://linux-hardware.org/?probe=d6855993c3) | Oct 01, 2020 |
| Dell          | XPS 13 9350                 | [fbaa514a8e](https://linux-hardware.org/?probe=fbaa514a8e) | Sep 29, 2020 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [d5cec6d5ee](https://linux-hardware.org/?probe=d5cec6d5ee) | Sep 29, 2020 |
| Lenovo        | ThinkPad X60s 1703Y1F       | [556ce7876f](https://linux-hardware.org/?probe=556ce7876f) | Sep 28, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c4d11b04b5](https://linux-hardware.org/?probe=c4d11b04b5) | Sep 28, 2020 |
| ASUSTek       | N551JW                      | [bbe5800595](https://linux-hardware.org/?probe=bbe5800595) | Sep 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [eb4f96855e](https://linux-hardware.org/?probe=eb4f96855e) | Sep 27, 2020 |
| HP            | Stream Notebook PC 13       | [de7c2cac49](https://linux-hardware.org/?probe=de7c2cac49) | Sep 26, 2020 |
| RM            | NOTEBOOK 310                | [eaeb27c7f2](https://linux-hardware.org/?probe=eaeb27c7f2) | Sep 26, 2020 |
| Lenovo        | ThinkPad X250 20CLS3KU00    | [249a4394d3](https://linux-hardware.org/?probe=249a4394d3) | Sep 25, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [e0efe47cb6](https://linux-hardware.org/?probe=e0efe47cb6) | Sep 25, 2020 |
| HP            | EliteBook 850 G5            | [86422636a2](https://linux-hardware.org/?probe=86422636a2) | Sep 25, 2020 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [ce767919ed](https://linux-hardware.org/?probe=ce767919ed) | Sep 24, 2020 |
| ASUSTek       | S551LN                      | [422ea2594e](https://linux-hardware.org/?probe=422ea2594e) | Sep 23, 2020 |
| HP            | Compaq 6730b (KE717AV)      | [ed83dc94c7](https://linux-hardware.org/?probe=ed83dc94c7) | Sep 22, 2020 |
| Lenovo        | G570 20079                  | [66c60e019d](https://linux-hardware.org/?probe=66c60e019d) | Sep 20, 2020 |
| Lenovo        | ThinkPad T420 4236PRG       | [642718e912](https://linux-hardware.org/?probe=642718e912) | Sep 20, 2020 |
| HP            | Laptop 15-bs1xx             | [711a85f008](https://linux-hardware.org/?probe=711a85f008) | Sep 19, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e1ee591923](https://linux-hardware.org/?probe=e1ee591923) | Sep 18, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e416b806d6](https://linux-hardware.org/?probe=e416b806d6) | Sep 18, 2020 |
| Dell          | Inspiron 5520               | [bfcd20dbac](https://linux-hardware.org/?probe=bfcd20dbac) | Sep 18, 2020 |
| Dell          | Inspiron 5520               | [422e9fa4b7](https://linux-hardware.org/?probe=422e9fa4b7) | Sep 18, 2020 |
| Dell          | Vostro 5490                 | [7eb157ff10](https://linux-hardware.org/?probe=7eb157ff10) | Sep 16, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [1fa7cd3dc7](https://linux-hardware.org/?probe=1fa7cd3dc7) | Sep 16, 2020 |
| Dell          | Latitude 5400               | [623e6b93ad](https://linux-hardware.org/?probe=623e6b93ad) | Sep 15, 2020 |
| Acer          | Swift SF514-53T             | [faed7578a5](https://linux-hardware.org/?probe=faed7578a5) | Sep 13, 2020 |
| Dell          | Inspiron 15-3552            | [9bdc5d239e](https://linux-hardware.org/?probe=9bdc5d239e) | Sep 13, 2020 |
| HP            | G70                         | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| Dell          | Vostro 3560                 | [f94ad2f27d](https://linux-hardware.org/?probe=f94ad2f27d) | Sep 12, 2020 |
| Dell          | Latitude E5410              | [49fba5e9d5](https://linux-hardware.org/?probe=49fba5e9d5) | Sep 11, 2020 |
| HP            | ProBook 4540s               | [c11c25601e](https://linux-hardware.org/?probe=c11c25601e) | Sep 09, 2020 |
| Acer          | AOA110                      | [25dbe990da](https://linux-hardware.org/?probe=25dbe990da) | Sep 09, 2020 |
| Dell          | Inspiron 7559               | [b7918f8374](https://linux-hardware.org/?probe=b7918f8374) | Sep 09, 2020 |
| Acer          | Aspire E5-575               | [31e588485d](https://linux-hardware.org/?probe=31e588485d) | Sep 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [cab06cdbd7](https://linux-hardware.org/?probe=cab06cdbd7) | Sep 07, 2020 |
| Toshiba       | Satellite Pro C650          | [61966b1615](https://linux-hardware.org/?probe=61966b1615) | Sep 07, 2020 |
| Dell          | Latitude E6430              | [ce95e87e90](https://linux-hardware.org/?probe=ce95e87e90) | Sep 06, 2020 |
| HP            | ProBook 455 G2              | [cf202aa137](https://linux-hardware.org/?probe=cf202aa137) | Sep 06, 2020 |
| Apple         | MacBookPro11,3              | [db5ed9c7cc](https://linux-hardware.org/?probe=db5ed9c7cc) | Sep 06, 2020 |
| Apple         | MacBookPro11,3              | [2301ba312c](https://linux-hardware.org/?probe=2301ba312c) | Sep 06, 2020 |
| Acer          | Aspire E5-575G              | [71698fa8ea](https://linux-hardware.org/?probe=71698fa8ea) | Sep 05, 2020 |
| Lenovo        | G50-45 80E3                 | [7ab663d793](https://linux-hardware.org/?probe=7ab663d793) | Sep 05, 2020 |
| Dell          | Latitude E7440              | [0db3907088](https://linux-hardware.org/?probe=0db3907088) | Sep 05, 2020 |
| Dell          | Latitude 3400               | [e1a6c8dd9b](https://linux-hardware.org/?probe=e1a6c8dd9b) | Sep 04, 2020 |
| LG Electro... | 15ND530-GX30K               | [8f8a5ce10c](https://linux-hardware.org/?probe=8f8a5ce10c) | Sep 04, 2020 |
| Acer          | Aspire ES1-523              | [e335200dd8](https://linux-hardware.org/?probe=e335200dd8) | Sep 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a06e93e3e9](https://linux-hardware.org/?probe=a06e93e3e9) | Sep 04, 2020 |
| ASUSTek       | K46CB                       | [480238b24f](https://linux-hardware.org/?probe=480238b24f) | Sep 04, 2020 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [4ba6b10a45](https://linux-hardware.org/?probe=4ba6b10a45) | Sep 03, 2020 |
| Dell          | Latitude E5410              | [1b695e8489](https://linux-hardware.org/?probe=1b695e8489) | Sep 03, 2020 |
| Dell          | XPS 13 9360                 | [9c3c496bce](https://linux-hardware.org/?probe=9c3c496bce) | Sep 03, 2020 |
| Dell          | XPS 13 9360                 | [db1c5c4a5a](https://linux-hardware.org/?probe=db1c5c4a5a) | Sep 03, 2020 |
| Acer          | Aspire V5-123               | [1f3a3c5de7](https://linux-hardware.org/?probe=1f3a3c5de7) | Sep 03, 2020 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [141b121f2b](https://linux-hardware.org/?probe=141b121f2b) | Sep 02, 2020 |
| Dell          | Latitude E6220              | [4dbb344e4e](https://linux-hardware.org/?probe=4dbb344e4e) | Sep 02, 2020 |
| Dell          | Latitude E6220              | [4a7fb29d5b](https://linux-hardware.org/?probe=4a7fb29d5b) | Sep 02, 2020 |
| Notebook      | NJ50_70CU                   | [a724f1dd51](https://linux-hardware.org/?probe=a724f1dd51) | Sep 01, 2020 |
| HP            | Pavilion g4                 | [cf281b97df](https://linux-hardware.org/?probe=cf281b97df) | Aug 31, 2020 |
| HP            | Laptop 15s-fq1xxx           | [5e853f5521](https://linux-hardware.org/?probe=5e853f5521) | Aug 31, 2020 |
| Toshiba       | Satellite L50-C             | [fe2976451d](https://linux-hardware.org/?probe=fe2976451d) | Aug 31, 2020 |
| HP            | Pavilion g4                 | [4ae31fc59f](https://linux-hardware.org/?probe=4ae31fc59f) | Aug 30, 2020 |
| HP            | EliteBook 6930p             | [65a2b8d0f8](https://linux-hardware.org/?probe=65a2b8d0f8) | Aug 28, 2020 |
| Purism        | Librem 13 v2                | [23cd34d2f6](https://linux-hardware.org/?probe=23cd34d2f6) | Aug 27, 2020 |
| Acer          | Aspire E5-576G              | [ed12456986](https://linux-hardware.org/?probe=ed12456986) | Aug 27, 2020 |
| Dell          | Inspiron 1501               | [05a7b7bd45](https://linux-hardware.org/?probe=05a7b7bd45) | Aug 26, 2020 |
| Positivo      | Mobile                      | [e663178667](https://linux-hardware.org/?probe=e663178667) | Aug 26, 2020 |
| HP            | Laptop 15s-fq1xxx           | [f58e055469](https://linux-hardware.org/?probe=f58e055469) | Aug 25, 2020 |
| HP            | Laptop 15s-fq1xxx           | [d19c11c74a](https://linux-hardware.org/?probe=d19c11c74a) | Aug 25, 2020 |
| Acer          | Aspire M5-481T              | [90f4c78581](https://linux-hardware.org/?probe=90f4c78581) | Aug 24, 2020 |
| HP            | 255 G5 Notebook PC          | [ed158ae1be](https://linux-hardware.org/?probe=ed158ae1be) | Aug 24, 2020 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [09fa3f2ed9](https://linux-hardware.org/?probe=09fa3f2ed9) | Aug 23, 2020 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [2febbb27a0](https://linux-hardware.org/?probe=2febbb27a0) | Aug 23, 2020 |
| Lenovo        | ThinkPad X230 23252S4       | [5fe0becd60](https://linux-hardware.org/?probe=5fe0becd60) | Aug 22, 2020 |
| Dell          | Inspiron 5468               | [34784a5c7f](https://linux-hardware.org/?probe=34784a5c7f) | Aug 22, 2020 |
| HP            | Pavilion Laptop 14-bf0xx    | [7ac7953d76](https://linux-hardware.org/?probe=7ac7953d76) | Aug 22, 2020 |
| Positivo      | WCBT1013                    | [444b588762](https://linux-hardware.org/?probe=444b588762) | Aug 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7b4fcb3693](https://linux-hardware.org/?probe=7b4fcb3693) | Aug 21, 2020 |
| Acer          | Aspire 2920                 | [a6e4cf0707](https://linux-hardware.org/?probe=a6e4cf0707) | Aug 20, 2020 |
| HP            | ENVY 17                     | [e7362b7565](https://linux-hardware.org/?probe=e7362b7565) | Aug 19, 2020 |
| HP            | ENVY 17                     | [73738aea3d](https://linux-hardware.org/?probe=73738aea3d) | Aug 19, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f08d3d413f](https://linux-hardware.org/?probe=f08d3d413f) | Aug 18, 2020 |
| HP            | Laptop 15s-fq1xxx           | [3f770a739d](https://linux-hardware.org/?probe=3f770a739d) | Aug 18, 2020 |
| HP            | Laptop 15s-fq1xxx           | [19d3840414](https://linux-hardware.org/?probe=19d3840414) | Aug 17, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a0a3771b15](https://linux-hardware.org/?probe=a0a3771b15) | Aug 17, 2020 |
| HP            | EliteBook 2570p             | [68b54a8e19](https://linux-hardware.org/?probe=68b54a8e19) | Aug 16, 2020 |
| Alienware     | 17 R4                       | [c1a871b29b](https://linux-hardware.org/?probe=c1a871b29b) | Aug 14, 2020 |
| Acer          | Nitro AN515-54              | [a16386e839](https://linux-hardware.org/?probe=a16386e839) | Aug 14, 2020 |
| Acer          | Aspire A315-21              | [7f105e6362](https://linux-hardware.org/?probe=7f105e6362) | Aug 13, 2020 |
| HP            | Pavilion dm1                | [60fa55c570](https://linux-hardware.org/?probe=60fa55c570) | Aug 12, 2020 |
| Dell          | Vostro 3460                 | [0aae36acb0](https://linux-hardware.org/?probe=0aae36acb0) | Aug 12, 2020 |
| Acer          | Aspire A315-21              | [783c39539a](https://linux-hardware.org/?probe=783c39539a) | Aug 12, 2020 |
| Lenovo        | ThinkPad X280 20KES30A00    | [c471cf1073](https://linux-hardware.org/?probe=c471cf1073) | Aug 12, 2020 |
| ASUSTek       | X102BA                      | [e0a50dc1dc](https://linux-hardware.org/?probe=e0a50dc1dc) | Aug 11, 2020 |
| ASUSTek       | X102BA                      | [54626aa013](https://linux-hardware.org/?probe=54626aa013) | Aug 11, 2020 |
| Dell          | Inspiron 5468               | [2132db1417](https://linux-hardware.org/?probe=2132db1417) | Aug 10, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | [d4e7055335](https://linux-hardware.org/?probe=d4e7055335) | Aug 09, 2020 |
| Dell          | Vostro 5490                 | [7a1a00cd34](https://linux-hardware.org/?probe=7a1a00cd34) | Aug 09, 2020 |
| Dell          | Vostro 5490                 | [f06297f752](https://linux-hardware.org/?probe=f06297f752) | Aug 09, 2020 |
| Dell          | Latitude 3500               | [09838e5e6d](https://linux-hardware.org/?probe=09838e5e6d) | Aug 08, 2020 |
| Dell          | Latitude 5400               | [a38ed67ed8](https://linux-hardware.org/?probe=a38ed67ed8) | Aug 06, 2020 |
| HP            | Presario CQ57               | [0e5ac44846](https://linux-hardware.org/?probe=0e5ac44846) | Aug 05, 2020 |
| HP            | Notebook                    | [daf982706c](https://linux-hardware.org/?probe=daf982706c) | Aug 02, 2020 |
| HP            | Notebook                    | [1b3e005f48](https://linux-hardware.org/?probe=1b3e005f48) | Aug 02, 2020 |
| Acer          | Swift SF314-51              | [ff4068d40b](https://linux-hardware.org/?probe=ff4068d40b) | Jul 31, 2020 |
| Dell          | Inspiron 1545               | [0bf0dfa454](https://linux-hardware.org/?probe=0bf0dfa454) | Jul 30, 2020 |
| ASUSTek       | G60JX                       | [a79df141d9](https://linux-hardware.org/?probe=a79df141d9) | Jul 30, 2020 |
| ASUSTek       | N46VM                       | [d5866f9f0f](https://linux-hardware.org/?probe=d5866f9f0f) | Jul 30, 2020 |
| Sony          | VPCEH40EB                   | [34776d5a70](https://linux-hardware.org/?probe=34776d5a70) | Jul 28, 2020 |
| Dell          | System XPS L502X            | [2d4d18566a](https://linux-hardware.org/?probe=2d4d18566a) | Jul 28, 2020 |
| Dell          | System XPS L502X            | [8bb4b95768](https://linux-hardware.org/?probe=8bb4b95768) | Jul 28, 2020 |
| Notebook      | P95_96_97Ex,Rx              | [4a873d937e](https://linux-hardware.org/?probe=4a873d937e) | Jul 28, 2020 |
| Notebook      | P95_96_97Ex,Rx              | [856a372491](https://linux-hardware.org/?probe=856a372491) | Jul 28, 2020 |
| ASUSTek       | N46VM                       | [b9abcbb0ca](https://linux-hardware.org/?probe=b9abcbb0ca) | Jul 27, 2020 |
| ASUSTek       | N46VM                       | [864b3c0808](https://linux-hardware.org/?probe=864b3c0808) | Jul 27, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3c7f1069f2](https://linux-hardware.org/?probe=3c7f1069f2) | Jul 27, 2020 |
| Positivo      | Mobile                      | [c1befdddd7](https://linux-hardware.org/?probe=c1befdddd7) | Jul 27, 2020 |
| Positivo      | Mobile                      | [005647bf65](https://linux-hardware.org/?probe=005647bf65) | Jul 27, 2020 |
| HP            | Pavilion dm1                | [db3461a440](https://linux-hardware.org/?probe=db3461a440) | Jul 25, 2020 |
| Dell          | Inspiron 5448               | [2fe1b79c13](https://linux-hardware.org/?probe=2fe1b79c13) | Jul 25, 2020 |
| Dell          | Inspiron 5448               | [288a68e67a](https://linux-hardware.org/?probe=288a68e67a) | Jul 25, 2020 |
| Acer          | Aspire A515-51G             | [9742c8d37b](https://linux-hardware.org/?probe=9742c8d37b) | Jul 25, 2020 |
| ASUSTek       | X550LB                      | [21f4f262c0](https://linux-hardware.org/?probe=21f4f262c0) | Jul 25, 2020 |
| Dell          | Inspiron 5468               | [5c465b448e](https://linux-hardware.org/?probe=5c465b448e) | Jul 24, 2020 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [d123128722](https://linux-hardware.org/?probe=d123128722) | Jul 24, 2020 |
| Acer          | Aspire A515-51              | [11869b0f59](https://linux-hardware.org/?probe=11869b0f59) | Jul 24, 2020 |
| ASUSTek       | X45C                        | [4f6a928ff4](https://linux-hardware.org/?probe=4f6a928ff4) | Jul 24, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [2617c14fa9](https://linux-hardware.org/?probe=2617c14fa9) | Jul 24, 2020 |
| Dell          | Inspiron 3576               | [1ba8aea989](https://linux-hardware.org/?probe=1ba8aea989) | Jul 24, 2020 |
| Acer          | Aspire E5-571               | [725d9e6ae5](https://linux-hardware.org/?probe=725d9e6ae5) | Jul 24, 2020 |
| Lenovo        | G50-80 80R0                 | [6982206a08](https://linux-hardware.org/?probe=6982206a08) | Jul 24, 2020 |
| Positivo      | Master N130i                | [7eba72f41a](https://linux-hardware.org/?probe=7eba72f41a) | Jul 24, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [16ae7ff56d](https://linux-hardware.org/?probe=16ae7ff56d) | Jul 23, 2020 |
| Toshiba       | Satellite L300              | [c298ec6fd5](https://linux-hardware.org/?probe=c298ec6fd5) | Jul 23, 2020 |
| Toshiba       | PORTEGE Z30-E               | [a388a3c3af](https://linux-hardware.org/?probe=a388a3c3af) | Jul 23, 2020 |
| HP            | EliteBook 840 G3            | [8b28c1e0d0](https://linux-hardware.org/?probe=8b28c1e0d0) | Jul 23, 2020 |
| Dell          | Vostro 3350                 | [9e18467afc](https://linux-hardware.org/?probe=9e18467afc) | Jul 23, 2020 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [30350cb1a7](https://linux-hardware.org/?probe=30350cb1a7) | Jul 21, 2020 |
| Toshiba       | Satellite L300              | [1aae41a0a1](https://linux-hardware.org/?probe=1aae41a0a1) | Jul 21, 2020 |
| Dell          | Vostro 5490                 | [6c43634839](https://linux-hardware.org/?probe=6c43634839) | Jul 20, 2020 |
| Dell          | Vostro 5490                 | [c52426ce99](https://linux-hardware.org/?probe=c52426ce99) | Jul 19, 2020 |
| HP            | Pavilion dm1                | [84fc871f29](https://linux-hardware.org/?probe=84fc871f29) | Jul 18, 2020 |
| HP            | Pavilion dm1                | [ccc4a944e8](https://linux-hardware.org/?probe=ccc4a944e8) | Jul 18, 2020 |
| Dell          | Latitude 5501               | [c53b828170](https://linux-hardware.org/?probe=c53b828170) | Jul 17, 2020 |
| Dell          | Latitude 5501               | [4b7b954a2a](https://linux-hardware.org/?probe=4b7b954a2a) | Jul 16, 2020 |
| Dell          | Latitude 5501               | [8ed8b8225c](https://linux-hardware.org/?probe=8ed8b8225c) | Jul 16, 2020 |
| ASUSTek       | N56JN                       | [43c91be0b3](https://linux-hardware.org/?probe=43c91be0b3) | Jul 16, 2020 |
| Dell          | Inspiron 7570               | [c9ee97997e](https://linux-hardware.org/?probe=c9ee97997e) | Jul 15, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [498a1fee5c](https://linux-hardware.org/?probe=498a1fee5c) | Jul 14, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f545576ae9](https://linux-hardware.org/?probe=f545576ae9) | Jul 14, 2020 |
| Lenovo        | V340-17IWL 81RG             | [49816db41b](https://linux-hardware.org/?probe=49816db41b) | Jul 13, 2020 |
| HP            | 255 G5 Notebook PC          | [61f3040321](https://linux-hardware.org/?probe=61f3040321) | Jul 13, 2020 |
| Intel         | powered classmate PC        | [1ffa275c8b](https://linux-hardware.org/?probe=1ffa275c8b) | Jul 12, 2020 |
| Intel         | Skylake Platform            | [e9db11a33a](https://linux-hardware.org/?probe=e9db11a33a) | Jul 11, 2020 |
| HP            | Mini 110-3100               | [2bb9ccfa16](https://linux-hardware.org/?probe=2bb9ccfa16) | Jul 11, 2020 |
| Intel         | powered classmate PC        | [49442bdbca](https://linux-hardware.org/?probe=49442bdbca) | Jul 11, 2020 |
| Dell          | Latitude 3500               | [6f040bffc3](https://linux-hardware.org/?probe=6f040bffc3) | Jul 11, 2020 |
| MSI           | GE62 7RE                    | [40d868800a](https://linux-hardware.org/?probe=40d868800a) | Jul 09, 2020 |
| Dell          | Inspiron 1545               | [9642ef551e](https://linux-hardware.org/?probe=9642ef551e) | Jul 08, 2020 |
| Panasonic     | CF-52PGNBX2M                | [b9dadcb0e0](https://linux-hardware.org/?probe=b9dadcb0e0) | Jul 08, 2020 |
| Panasonic     | CF-52PGNBX2M                | [3b388e6d69](https://linux-hardware.org/?probe=3b388e6d69) | Jul 08, 2020 |
| Dell          | Latitude E5520              | [ab997ac1d8](https://linux-hardware.org/?probe=ab997ac1d8) | Jul 06, 2020 |
| Apple         | MacBookPro11,3              | [c4b1d78638](https://linux-hardware.org/?probe=c4b1d78638) | Jul 06, 2020 |
| Lenovo        | ThinkPad X395 20NL000YCD    | [8ce881d65e](https://linux-hardware.org/?probe=8ce881d65e) | Jul 06, 2020 |
| Acer          | Aspire 7520                 | [d2d6a3d4e6](https://linux-hardware.org/?probe=d2d6a3d4e6) | Jul 06, 2020 |
| PC Special... | N150CU                      | [940e89b2ae](https://linux-hardware.org/?probe=940e89b2ae) | Jul 05, 2020 |
| HP            | 250 G6 Notebook PC          | [4e7c532c73](https://linux-hardware.org/?probe=4e7c532c73) | Jul 04, 2020 |
| HP            | 250 G6 Notebook PC          | [b7b5367edf](https://linux-hardware.org/?probe=b7b5367edf) | Jul 04, 2020 |
| PC Special... | N150CU                      | [6f7e0f4a22](https://linux-hardware.org/?probe=6f7e0f4a22) | Jul 04, 2020 |
| Dell          | Latitude 5490               | [43f9885380](https://linux-hardware.org/?probe=43f9885380) | Jul 04, 2020 |
| Dell          | Latitude 5490               | [71db2718e5](https://linux-hardware.org/?probe=71db2718e5) | Jul 04, 2020 |
| Lenovo        | ThinkPad T400 6474D88       | [8af87c450e](https://linux-hardware.org/?probe=8af87c450e) | Jul 03, 2020 |
| Fujitsu       | LIFEBOOK BH531              | [2484e68205](https://linux-hardware.org/?probe=2484e68205) | Jul 03, 2020 |
| Lenovo        | ThinkPad T450 20BUS3V100    | [b7c6aa8db3](https://linux-hardware.org/?probe=b7c6aa8db3) | Jul 01, 2020 |
| Lenovo        | ThinkPad T450 20BUS3V100    | [f77bec6055](https://linux-hardware.org/?probe=f77bec6055) | Jul 01, 2020 |
| ASUSTek       | G752VS                      | [c65813bd9f](https://linux-hardware.org/?probe=c65813bd9f) | Jul 01, 2020 |
| HP            | Pavilion Laptop 14-bf0xx    | [b303c4d3e2](https://linux-hardware.org/?probe=b303c4d3e2) | Jun 30, 2020 |
| HP            | EliteBook 840 G1            | [75a2e58b47](https://linux-hardware.org/?probe=75a2e58b47) | Jun 30, 2020 |
| Lenovo        | G40-30 80FY                 | [2e7c3657fb](https://linux-hardware.org/?probe=2e7c3657fb) | Jun 30, 2020 |
| Dell          | Inspiron N5050              | [d2e2ff8989](https://linux-hardware.org/?probe=d2e2ff8989) | Jun 29, 2020 |
| Compal        | PBL20                       | [7fe621b0fd](https://linux-hardware.org/?probe=7fe621b0fd) | Jun 29, 2020 |
| Lenovo        | ThinkPad L390 20NR001FRT    | [b9cca93b51](https://linux-hardware.org/?probe=b9cca93b51) | Jun 29, 2020 |
| Acer          | TravelMate P2410-G2-M       | [00677918db](https://linux-hardware.org/?probe=00677918db) | Jun 29, 2020 |
| ASUSTek       | G752VS                      | [9e1c907a01](https://linux-hardware.org/?probe=9e1c907a01) | Jun 28, 2020 |
| Lenovo        | G40-30 80FY                 | [5cfcbbb4a4](https://linux-hardware.org/?probe=5cfcbbb4a4) | Jun 28, 2020 |
| ASUSTek       | X540LA                      | [df995fd6b3](https://linux-hardware.org/?probe=df995fd6b3) | Jun 27, 2020 |
| Corporativ... | LX4SI                       | [3a15f8865d](https://linux-hardware.org/?probe=3a15f8865d) | Jun 26, 2020 |
| Lenovo        | Y50-70 20378                | [f01e0dbd89](https://linux-hardware.org/?probe=f01e0dbd89) | Jun 26, 2020 |
| MSI           | MS-7A37                     | [a2ad72232d](https://linux-hardware.org/?probe=a2ad72232d) | Jun 25, 2020 |
| HP            | ZBook 15                    | [ac608e1d37](https://linux-hardware.org/?probe=ac608e1d37) | Jun 25, 2020 |
| Lenovo        | IdeaPad Z500 20202          | [dc66cb5caf](https://linux-hardware.org/?probe=dc66cb5caf) | Jun 25, 2020 |
| Corporativ... | LX4SI                       | [f9e67e8a5f](https://linux-hardware.org/?probe=f9e67e8a5f) | Jun 25, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [97f55dc573](https://linux-hardware.org/?probe=97f55dc573) | Jun 24, 2020 |
| Dell          | Inspiron 5481               | [1075dca72a](https://linux-hardware.org/?probe=1075dca72a) | Jun 24, 2020 |
| Lenovo        | ThinkPad T410 2522K4U       | [b9a9a86df6](https://linux-hardware.org/?probe=b9a9a86df6) | Jun 23, 2020 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [f48bfbd65a](https://linux-hardware.org/?probe=f48bfbd65a) | Jun 22, 2020 |
| Dell          | Latitude 3500               | [85c2c3879c](https://linux-hardware.org/?probe=85c2c3879c) | Jun 22, 2020 |
| Acer          | AOD255E                     | [1ff694ea71](https://linux-hardware.org/?probe=1ff694ea71) | Jun 20, 2020 |
| Lenovo        | B320-14IKB 81CC             | [1d4b7aa7e6](https://linux-hardware.org/?probe=1d4b7aa7e6) | Jun 19, 2020 |
| Dell          | Vostro 3550                 | [1eff0f87ed](https://linux-hardware.org/?probe=1eff0f87ed) | Jun 19, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | [9a6aa97f03](https://linux-hardware.org/?probe=9a6aa97f03) | Jun 17, 2020 |
| Dell          | Vostro 3550                 | [093e631bfb](https://linux-hardware.org/?probe=093e631bfb) | Jun 17, 2020 |
| Dell          | Vostro 3550                 | [2e79d90fcf](https://linux-hardware.org/?probe=2e79d90fcf) | Jun 17, 2020 |
| Lenovo        | B320-14IKB 81CC             | [52bf2d5f61](https://linux-hardware.org/?probe=52bf2d5f61) | Jun 16, 2020 |
| HP            | G62                         | [ee5b5b6cd3](https://linux-hardware.org/?probe=ee5b5b6cd3) | Jun 15, 2020 |
| Sony          | PCG-GRZ10(I)                | [185fd8341c](https://linux-hardware.org/?probe=185fd8341c) | Jun 14, 2020 |
| Dell          | Latitude E6430              | [97304444b6](https://linux-hardware.org/?probe=97304444b6) | Jun 14, 2020 |
| ASUSTek       | N56JN                       | [3f30010f53](https://linux-hardware.org/?probe=3f30010f53) | Jun 14, 2020 |
| eMachines     | E725                        | [e619c97412](https://linux-hardware.org/?probe=e619c97412) | Jun 13, 2020 |
| HP            | Stream Notebook PC 13       | [9dce53774f](https://linux-hardware.org/?probe=9dce53774f) | Jun 13, 2020 |
| Acer          | Aspire E5-575G              | [80eaa52f0f](https://linux-hardware.org/?probe=80eaa52f0f) | Jun 10, 2020 |
| Dell          | Inspiron 7559               | [1e7f6e42a3](https://linux-hardware.org/?probe=1e7f6e42a3) | Jun 10, 2020 |
| Lenovo        | ThinkPad T410 2537G98       | [50bf756f5e](https://linux-hardware.org/?probe=50bf756f5e) | Jun 10, 2020 |
| Dell          | Latitude 7490               | [6bf81ba8f3](https://linux-hardware.org/?probe=6bf81ba8f3) | Jun 10, 2020 |
| HP            | EliteBook 8470p             | [df84bbbc37](https://linux-hardware.org/?probe=df84bbbc37) | Jun 09, 2020 |
| HP            | Pavilion Laptop 15-ck0xx    | [b9e284df2c](https://linux-hardware.org/?probe=b9e284df2c) | Jun 09, 2020 |
| HP            | Pavilion Laptop 15-ck0xx    | [2b1b019bdd](https://linux-hardware.org/?probe=2b1b019bdd) | Jun 09, 2020 |
| Acer          | Aspire E5-573G              | [c2f8aca460](https://linux-hardware.org/?probe=c2f8aca460) | Jun 06, 2020 |
| HP            | ProBook 4540s               | [b28f2f3b8a](https://linux-hardware.org/?probe=b28f2f3b8a) | Jun 05, 2020 |
| HP            | Presario CQ56               | [4eed3fc6f6](https://linux-hardware.org/?probe=4eed3fc6f6) | Jun 05, 2020 |
| Dell          | Precision M6700             | [0934059263](https://linux-hardware.org/?probe=0934059263) | Jun 04, 2020 |
| Dell          | Latitude E6400              | [5e1e738d70](https://linux-hardware.org/?probe=5e1e738d70) | Jun 04, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [e276372880](https://linux-hardware.org/?probe=e276372880) | Jun 03, 2020 |
| HP            | Presario CQ43               | [30478f743c](https://linux-hardware.org/?probe=30478f743c) | Jun 03, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [1431224dcf](https://linux-hardware.org/?probe=1431224dcf) | Jun 03, 2020 |
| ASUSTek       | K55VD                       | [6976a25d72](https://linux-hardware.org/?probe=6976a25d72) | Jun 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS70D00    | [02e0881f6f](https://linux-hardware.org/?probe=02e0881f6f) | Jun 01, 2020 |
| Lenovo        | Z50-70 20354                | [474b3dc645](https://linux-hardware.org/?probe=474b3dc645) | Jun 01, 2020 |
| HDC High D... | CB14T332                    | [1d7a164cca](https://linux-hardware.org/?probe=1d7a164cca) | May 30, 2020 |
| HP            | EliteBook 1050 G1           | [0c3a677cbd](https://linux-hardware.org/?probe=0c3a677cbd) | May 29, 2020 |
| HP            | EliteBook 1050 G1           | [c0f352e66c](https://linux-hardware.org/?probe=c0f352e66c) | May 29, 2020 |
| Dell          | Inspiron N5050              | [50d2e1431b](https://linux-hardware.org/?probe=50d2e1431b) | May 29, 2020 |
| Dell          | Inspiron N5050              | [a0ad1f624b](https://linux-hardware.org/?probe=a0ad1f624b) | May 29, 2020 |
| Dell          | Latitude E7240              | [6289a0fd13](https://linux-hardware.org/?probe=6289a0fd13) | May 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [9a867c7a5b](https://linux-hardware.org/?probe=9a867c7a5b) | May 28, 2020 |
| Dell          | Latitude E7450              | [c3eab25bca](https://linux-hardware.org/?probe=c3eab25bca) | May 28, 2020 |
| Lenovo        | ThinkPad X200 74598Y7       | [4552172a72](https://linux-hardware.org/?probe=4552172a72) | May 28, 2020 |
| Acer          | Swift SF315-52              | [e86fd64c2e](https://linux-hardware.org/?probe=e86fd64c2e) | May 28, 2020 |
| Samsung       | N150P/N210P/N220P           | [2a2f1b6680](https://linux-hardware.org/?probe=2a2f1b6680) | May 27, 2020 |
| HP            | Laptop 17-ca0xxx            | [beffbd7414](https://linux-hardware.org/?probe=beffbd7414) | May 27, 2020 |
| Lenovo        | ThinkPad T400 6475VYS       | [9cb845c34a](https://linux-hardware.org/?probe=9cb845c34a) | May 26, 2020 |
| Samsung       | RF510/RF410/RF710           | [1dbe669cde](https://linux-hardware.org/?probe=1dbe669cde) | May 26, 2020 |
| HP            | Laptop 17-ca0xxx            | [5260e229e1](https://linux-hardware.org/?probe=5260e229e1) | May 26, 2020 |
| HP            | Pavilion g6                 | [7b98176319](https://linux-hardware.org/?probe=7b98176319) | May 25, 2020 |
| Lenovo        | ThinkPad X240 20AMS3AE04    | [9db223bd10](https://linux-hardware.org/?probe=9db223bd10) | May 25, 2020 |
| Lenovo        | ThinkPad X220 4290LE6       | [1cf252b77b](https://linux-hardware.org/?probe=1cf252b77b) | May 25, 2020 |
| Dell          | Precision 3540              | [ea309d9030](https://linux-hardware.org/?probe=ea309d9030) | May 25, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | [e63080ca59](https://linux-hardware.org/?probe=e63080ca59) | May 25, 2020 |
| ASUSTek       | U47A                        | [37e6fd89f0](https://linux-hardware.org/?probe=37e6fd89f0) | May 25, 2020 |
| Toshiba       | Satellite S55-B             | [35990b670d](https://linux-hardware.org/?probe=35990b670d) | May 25, 2020 |
| Dell          | Inspiron 7559               | [f3bc867078](https://linux-hardware.org/?probe=f3bc867078) | May 24, 2020 |
| Dell          | Latitude E4310              | [584a3a44b6](https://linux-hardware.org/?probe=584a3a44b6) | May 23, 2020 |
| ASUSTek       | UX550VE                     | [f872407ca5](https://linux-hardware.org/?probe=f872407ca5) | May 23, 2020 |
| Apple         | MacBookPro11,3              | [73c797ec11](https://linux-hardware.org/?probe=73c797ec11) | May 22, 2020 |
| Dell          | Inspiron 3458               | [47147cf457](https://linux-hardware.org/?probe=47147cf457) | May 22, 2020 |
| Lenovo        | ThinkPad E470 20H1A029SG    | [6afaed7f7f](https://linux-hardware.org/?probe=6afaed7f7f) | May 21, 2020 |
| Acer          | Aspire one                  | [7b19bc975f](https://linux-hardware.org/?probe=7b19bc975f) | May 20, 2020 |
| Dell          | Latitude E6410              | [4e98eb67c5](https://linux-hardware.org/?probe=4e98eb67c5) | May 19, 2020 |
| HP            | Stream Notebook PC 13       | [9179ef8e4a](https://linux-hardware.org/?probe=9179ef8e4a) | May 16, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [bccec7c3d1](https://linux-hardware.org/?probe=bccec7c3d1) | May 16, 2020 |
| HP            | EliteBook 830 G5            | [5570800f48](https://linux-hardware.org/?probe=5570800f48) | May 16, 2020 |
| Lenovo        | ThinkPad T520 424329U       | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| Lenovo        | V340-17IWL 81RG             | [44587fea11](https://linux-hardware.org/?probe=44587fea11) | May 15, 2020 |
| HP            | Stream Notebook PC 13       | [24159d4d0e](https://linux-hardware.org/?probe=24159d4d0e) | May 12, 2020 |
| HP            | Stream Notebook PC 13       | [de358d97e6](https://linux-hardware.org/?probe=de358d97e6) | May 12, 2020 |
| Dell          | Latitude E5500              | [dab666e1a8](https://linux-hardware.org/?probe=dab666e1a8) | May 12, 2020 |
| Lenovo        | ThinkPad E480 20KN003WUS    | [eed9f07004](https://linux-hardware.org/?probe=eed9f07004) | May 09, 2020 |
| Dell          | Inspiron 7559               | [14935c4a3b](https://linux-hardware.org/?probe=14935c4a3b) | May 08, 2020 |
| Dell          | Precision M4600             | [7060267281](https://linux-hardware.org/?probe=7060267281) | May 08, 2020 |
| Dell          | XPS 13 9360                 | [a82e794c17](https://linux-hardware.org/?probe=a82e794c17) | May 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [25d620d966](https://linux-hardware.org/?probe=25d620d966) | May 07, 2020 |
| Medion        | Unknown                     | [5bf3f2a081](https://linux-hardware.org/?probe=5bf3f2a081) | May 07, 2020 |
| Medion        | Unknown                     | [052c842aeb](https://linux-hardware.org/?probe=052c842aeb) | May 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Notebook      | N130BU                      | [a82966c663](https://linux-hardware.org/?probe=a82966c663) | May 05, 2020 |
| Dell          | XPS 13 9360                 | [e7abeaa740](https://linux-hardware.org/?probe=e7abeaa740) | May 05, 2020 |
| Dell          | Precision M6700             | [83ca19b998](https://linux-hardware.org/?probe=83ca19b998) | May 02, 2020 |
| Lenovo        | ThinkPad T420 4180M8P       | [572c07437c](https://linux-hardware.org/?probe=572c07437c) | May 02, 2020 |
| Lenovo        | ThinkPad T420 4180M8P       | [c0c3c80557](https://linux-hardware.org/?probe=c0c3c80557) | May 01, 2020 |
| HP            | EliteBook 830 G5            | [60aac7debe](https://linux-hardware.org/?probe=60aac7debe) | May 01, 2020 |
| Lenovo        | ThinkPad T495s 20QKS01E0... | [00c41547c3](https://linux-hardware.org/?probe=00c41547c3) | May 01, 2020 |
| Lenovo        | ThinkPad T420 4180M8P       | [4c718b0f7f](https://linux-hardware.org/?probe=4c718b0f7f) | May 01, 2020 |
| Lenovo        | ThinkPad T420 4180M8P       | [15b0f60139](https://linux-hardware.org/?probe=15b0f60139) | May 01, 2020 |
| Acer          | Aspire A717-72G             | [c1d0901a2d](https://linux-hardware.org/?probe=c1d0901a2d) | May 01, 2020 |
| Acer          | Aspire A717-72G             | [d99f776939](https://linux-hardware.org/?probe=d99f776939) | May 01, 2020 |
| Dell          | Inspiron 3542               | [341f819d57](https://linux-hardware.org/?probe=341f819d57) | Apr 30, 2020 |
| Dell          | Inspiron 3542               | [f7fbef2f76](https://linux-hardware.org/?probe=f7fbef2f76) | Apr 30, 2020 |
| Dell          | Precision 5520              | [af304cccc5](https://linux-hardware.org/?probe=af304cccc5) | Apr 30, 2020 |
| Dell          | Precision 5520              | [38b67c7277](https://linux-hardware.org/?probe=38b67c7277) | Apr 30, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [689865b9bf](https://linux-hardware.org/?probe=689865b9bf) | Apr 30, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a6ae1c89e0](https://linux-hardware.org/?probe=a6ae1c89e0) | Apr 29, 2020 |
| Dell          | XPS 13 9360                 | [3a9685af82](https://linux-hardware.org/?probe=3a9685af82) | Apr 28, 2020 |
| Toshiba       | Satellite L515              | [c411228b1a](https://linux-hardware.org/?probe=c411228b1a) | Apr 28, 2020 |
| Samsung       | RF510/RF410/RF710           | [6cb8f7029e](https://linux-hardware.org/?probe=6cb8f7029e) | Apr 28, 2020 |
| Samsung       | RF510/RF410/RF710           | [a59c2a0386](https://linux-hardware.org/?probe=a59c2a0386) | Apr 28, 2020 |
| HP            | EliteBook 840 G1            | [b77a2c1bdc](https://linux-hardware.org/?probe=b77a2c1bdc) | Apr 27, 2020 |
| Dell          | Vostro 3360                 | [aea41bbbc1](https://linux-hardware.org/?probe=aea41bbbc1) | Apr 27, 2020 |
| Dell          | Vostro 3360                 | [204c6dc56b](https://linux-hardware.org/?probe=204c6dc56b) | Apr 27, 2020 |
| ASUSTek       | M3N                         | [59b41381ed](https://linux-hardware.org/?probe=59b41381ed) | Apr 27, 2020 |
| Dell          | Precision M6600             | [832a43b8f0](https://linux-hardware.org/?probe=832a43b8f0) | Apr 27, 2020 |
| Dell          | Latitude E6410              | [125cc5d7fd](https://linux-hardware.org/?probe=125cc5d7fd) | Apr 26, 2020 |
| Fujitsu Si... | AMILO Pa 2510               | [2babee9700](https://linux-hardware.org/?probe=2babee9700) | Apr 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_10/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 4.19.0-9-amd64       | 84        | 8.67%   |
| 4.19.0-6-amd64       | 80        | 8.26%   |
| 4.19.0-8-amd64       | 68        | 7.02%   |
| 4.19.0-13-amd64      | 68        | 7.02%   |
| 4.19.0-16-amd64      | 51        | 5.26%   |
| 4.19.0-10-amd64      | 51        | 5.26%   |
| 4.19.0-12-amd64      | 47        | 4.85%   |
| 4.19.0-17-amd64      | 41        | 4.23%   |
| 4.19.0-14-amd64      | 40        | 4.13%   |
| 4.19.0-11-amd64      | 22        | 2.27%   |
| 4.19.0-18-amd64      | 20        | 2.06%   |
| 4.19.0-5-amd64       | 17        | 1.75%   |
| 5.8.0-0.bpo.2-amd64  | 13        | 1.34%   |
| 5.10.0-0.bpo.3-amd64 | 11        | 1.14%   |
| 5.7.0-0.bpo.2-amd64  | 9         | 0.93%   |
| 5.4.0-4-amd64        | 9         | 0.93%   |
| 5.8.0-3-amd64        | 8         | 0.83%   |
| 5.6.0-0.bpo.2-amd64  | 8         | 0.83%   |
| 4.19.0-20-amd64      | 8         | 0.83%   |
| 5.6.0-2-amd64        | 7         | 0.72%   |
| 5.10.0-5mx-amd64     | 7         | 0.72%   |
| 5.10.0-0.bpo.7-amd64 | 7         | 0.72%   |
| 5.10.0-0.bpo.5-amd64 | 7         | 0.72%   |
| 5.9.0-0.bpo.5-amd64  | 6         | 0.62%   |
| 5.7.0-1-amd64        | 6         | 0.62%   |
| 5.4.0-0.bpo.2-amd64  | 6         | 0.62%   |
| 5.10.0-0.bpo.8-amd64 | 6         | 0.62%   |
| 4.19.0-6-686-pae     | 6         | 0.62%   |
| 4.19.0-16-686-pae    | 6         | 0.62%   |
| 5.9.0-4-amd64        | 5         | 0.52%   |
| 5.9.0-0.bpo.2-amd64  | 5         | 0.52%   |
| 5.8.0-2-amd64        | 5         | 0.52%   |
| 5.5.0-0.bpo.2-amd64  | 5         | 0.52%   |
| 5.4.0-3-amd64        | 5         | 0.52%   |
| 4.19.0-8-686         | 5         | 0.52%   |
| 4.19.0-4-amd64       | 5         | 0.52%   |
| 4.19.0-22-amd64      | 5         | 0.52%   |
| 4.19.0-19-amd64      | 5         | 0.52%   |
| 4.19.0-13-686-pae    | 5         | 0.52%   |
| 5.9.0-1-amd64        | 4         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19.0  | 641       | 70.36%  |
| 5.10.0  | 51        | 5.6%    |
| 5.4.0   | 33        | 3.62%   |
| 5.8.0   | 31        | 3.4%    |
| 5.9.0   | 25        | 2.74%   |
| 5.7.0   | 20        | 2.2%    |
| 5.6.0   | 17        | 1.87%   |
| 5.5.0   | 10        | 1.1%    |
| 5.2.0   | 9         | 0.99%   |
| 5.3.0   | 8         | 0.88%   |
| 5.3.5   | 3         | 0.33%   |
| 4.9.0   | 3         | 0.33%   |
| 6.1.94  | 2         | 0.22%   |
| 6.1.76  | 2         | 0.22%   |
| 6.1.124 | 2         | 0.22%   |
| 5.2.5   | 2         | 0.22%   |
| 5.0.0   | 2         | 0.22%   |
| 6.1.38  | 1         | 0.11%   |
| 6.1.3   | 1         | 0.11%   |
| 6.1.148 | 1         | 0.11%   |
| 6.1.135 | 1         | 0.11%   |
| 6.1.119 | 1         | 0.11%   |
| 6.1.112 | 1         | 0.11%   |
| 6.1.106 | 1         | 0.11%   |
| 5.9.14  | 1         | 0.11%   |
| 5.9.11  | 1         | 0.11%   |
| 5.8.2   | 1         | 0.11%   |
| 5.8.16  | 1         | 0.11%   |
| 5.7.13  | 1         | 0.11%   |
| 5.6.8   | 1         | 0.11%   |
| 5.6.2   | 1         | 0.11%   |
| 5.6.19  | 1         | 0.11%   |
| 5.6.17  | 1         | 0.11%   |
| 5.6.10  | 1         | 0.11%   |
| 5.5.19  | 1         | 0.11%   |
| 5.5.13  | 1         | 0.11%   |
| 5.4.75  | 1         | 0.11%   |
| 5.4.65  | 1         | 0.11%   |
| 5.4.35  | 1         | 0.11%   |
| 5.4.28  | 1         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 643       | 70.89%  |
| 5.10    | 51        | 5.62%   |
| 5.4     | 42        | 4.63%   |
| 5.8     | 33        | 3.64%   |
| 5.9     | 27        | 2.98%   |
| 5.7     | 21        | 2.32%   |
| 5.6     | 21        | 2.32%   |
| 5.2     | 15        | 1.65%   |
| 6.1     | 13        | 1.43%   |
| 5.5     | 12        | 1.32%   |
| 5.3     | 12        | 1.32%   |
| 4.9     | 5         | 0.55%   |
| 5.0     | 2         | 0.22%   |
| 3.10    | 2         | 0.22%   |
| 5.4.104 | 1         | 0.11%   |
| 5.18    | 1         | 0.11%   |
| 5.17    | 1         | 0.11%   |
| 5.16    | 1         | 0.11%   |
| 5.13    | 1         | 0.11%   |
| 5.12    | 1         | 0.11%   |
| 5.1     | 1         | 0.11%   |
| 4.20    | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 822       | 93.52%  |
| i686    | 53        | 6.03%   |
| armv7l  | 3         | 0.34%   |
| aarch64 | 1         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 243       | 26.94%  |
| XFCE             | 171       | 18.96%  |
| Unknown          | 124       | 13.75%  |
| KDE5             | 82        | 9.09%   |
| KDE              | 77        | 8.54%   |
| MATE             | 56        | 6.21%   |
| LXDE             | 36        | 3.99%   |
| X-Cinnamon       | 31        | 3.44%   |
| Cinnamon         | 30        | 3.33%   |
| i3               | 15        | 1.66%   |
| LXQt             | 10        | 1.11%   |
| Budgie           | 6         | 0.67%   |
| trinity          | 4         | 0.44%   |
| lightdm-xsession | 4         | 0.44%   |
| GNOME Classic    | 3         | 0.33%   |
| Unity            | 1         | 0.11%   |
| openbox          | 1         | 0.11%   |
| ICEWM            | 1         | 0.11%   |
| i3-gaps          | 1         | 0.11%   |
| GNOME Flashback  | 1         | 0.11%   |
| fluxbox          | 1         | 0.11%   |
| Enlightenment    | 1         | 0.11%   |
| DWM              | 1         | 0.11%   |
| default          | 1         | 0.11%   |
| awesome          | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 690       | 77.01%  |
| Wayland | 135       | 15.07%  |
| Tty     | 43        | 4.8%    |
| Unknown | 28        | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 423       | 47.1%   |
| GDM     | 148       | 16.48%  |
| TDM     | 137       | 15.26%  |
| SDDM    | 93        | 10.36%  |
| LightDM | 67        | 7.46%   |
| GDM3    | 15        | 1.67%   |
| XDM     | 5         | 0.56%   |
| NODM    | 5         | 0.56%   |
| SLiM    | 3         | 0.33%   |
| WDM     | 1         | 0.11%   |
| KDM     | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 277       | 31.02%  |
| Unknown | 116       | 12.99%  |
| pt_BR   | 65        | 7.28%   |
| de_DE   | 59        | 6.61%   |
| fr_FR   | 52        | 5.82%   |
| ru_RU   | 39        | 4.37%   |
| it_IT   | 29        | 3.25%   |
| en_GB   | 28        | 3.14%   |
| es_ES   | 23        | 2.58%   |
| pl_PL   | 17        | 1.9%    |
| es_MX   | 15        | 1.68%   |
| es_CL   | 12        | 1.34%   |
| en_CA   | 12        | 1.34%   |
| C       | 11        | 1.23%   |
| pt_PT   | 10        | 1.12%   |
| es_AR   | 9         | 1.01%   |
| en_IN   | 9         | 1.01%   |
| de_CH   | 7         | 0.78%   |
| zh_CN   | 6         | 0.67%   |
| ru_UA   | 6         | 0.67%   |
| en_IE   | 6         | 0.67%   |
| cs_CZ   | 6         | 0.67%   |
| es_VE   | 5         | 0.56%   |
| en_AU   | 5         | 0.56%   |
| da_DK   | 5         | 0.56%   |
| fr_CH   | 4         | 0.45%   |
| fi_FI   | 4         | 0.45%   |
| es_CO   | 4         | 0.45%   |
| en_ZA   | 4         | 0.45%   |
| en_NZ   | 4         | 0.45%   |
| sk_SK   | 3         | 0.34%   |
| ko_KR   | 3         | 0.34%   |
| hu_HU   | 3         | 0.34%   |
| es_CR   | 3         | 0.34%   |
| sv_SE   | 2         | 0.22%   |
| nl_NL   | 2         | 0.22%   |
| nl_BE   | 2         | 0.22%   |
| ja_JP   | 2         | 0.22%   |
| el_GR   | 2         | 0.22%   |
| de_AT   | 2         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 582       | 65.61%  |
| EFI  | 305       | 34.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 792       | 89.69%  |
| Unknown | 25        | 2.83%   |
| Overlay | 19        | 2.15%   |
| Btrfs   | 18        | 2.04%   |
| Tmpfs   | 7         | 0.79%   |
| Ext2    | 7         | 0.79%   |
| Xfs     | 5         | 0.57%   |
| Rootfs  | 5         | 0.57%   |
| Ext3    | 3         | 0.34%   |
| Zfs     | 1         | 0.11%   |
| F2fs    | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 408       | 45.84%  |
| GPT     | 292       | 32.81%  |
| MBR     | 190       | 21.35%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 775       | 87.27%  |
| Yes       | 113       | 12.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 671       | 75.99%  |
| Yes       | 212       | 24.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 204       | 23.21%  |
| Dell                  | 173       | 19.68%  |
| Hewlett-Packard       | 146       | 16.61%  |
| Acer                  | 85        | 9.67%   |
| ASUSTek Computer      | 84        | 9.56%   |
| Toshiba               | 28        | 3.19%   |
| Samsung Electronics   | 22        | 2.5%    |
| Sony                  | 17        | 1.93%   |
| Apple                 | 12        | 1.37%   |
| MSI                   | 10        | 1.14%   |
| Notebook              | 8         | 0.91%   |
| Unknown               | 8         | 0.91%   |
| Positivo              | 5         | 0.57%   |
| Intel                 | 5         | 0.57%   |
| Fujitsu               | 5         | 0.57%   |
| Alienware             | 5         | 0.57%   |
| Medion                | 4         | 0.46%   |
| Timi                  | 3         | 0.34%   |
| Panasonic             | 3         | 0.34%   |
| Packard Bell          | 3         | 0.34%   |
| LG Electronics        | 3         | 0.34%   |
| Gateway               | 3         | 0.34%   |
| TUXEDO                | 2         | 0.23%   |
| TQ-Group              | 2         | 0.23%   |
| Purism                | 2         | 0.23%   |
| IBM                   | 2         | 0.23%   |
| Google                | 2         | 0.23%   |
| Fujitsu Siemens       | 2         | 0.23%   |
| DNS                   | 2         | 0.23%   |
| VIT                   | 1         | 0.11%   |
| ViewSonic             | 1         | 0.11%   |
| TrekStor              | 1         | 0.11%   |
| SLIMBOOK              | 1         | 0.11%   |
| RM                    | 1         | 0.11%   |
| Razer                 | 1         | 0.11%   |
| Positivo Bahia - VAIO | 1         | 0.11%   |
| Polaroid              | 1         | 0.11%   |
| Pine Microsystems     | 1         | 0.11%   |
| Philco                | 1         | 0.11%   |
| PC Specialist         | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 12        | 1.37%   |
| Dell XPS 13 9360                         | 5         | 0.57%   |
| HP Pavilion Notebook                     | 4         | 0.46%   |
| Dell Inspiron 1545                       | 4         | 0.46%   |
| Lenovo ThinkPad E480 20KN003WUS          | 3         | 0.34%   |
| Lenovo IdeaPad 330-15IKB 81FE            | 3         | 0.34%   |
| Lenovo IdeaPad 110-15IBR 80T7            | 3         | 0.34%   |
| Intel powered classmate PC               | 3         | 0.34%   |
| HP Stream Notebook PC 13                 | 3         | 0.34%   |
| HP ProBook 4540s                         | 3         | 0.34%   |
| HP Pavilion g6                           | 3         | 0.34%   |
| HP Pavilion g4                           | 3         | 0.34%   |
| HP Notebook                              | 3         | 0.34%   |
| HP EliteBook 850 G5                      | 3         | 0.34%   |
| HP 2000                                  | 3         | 0.34%   |
| Dell Precision 5530                      | 3         | 0.34%   |
| Dell Latitude E7450                      | 3         | 0.34%   |
| Dell Latitude E6430                      | 3         | 0.34%   |
| Dell Latitude E6420                      | 3         | 0.34%   |
| Dell Latitude E5520                      | 3         | 0.34%   |
| Dell Latitude 5500                       | 3         | 0.34%   |
| Dell Inspiron 5570                       | 3         | 0.34%   |
| Dell Inspiron 15-3567                    | 3         | 0.34%   |
| ASUS K52F                                | 3         | 0.34%   |
| Apple MacBookPro11,3                     | 3         | 0.34%   |
| Acer Aspire E5-575G                      | 3         | 0.34%   |
| TQ-Group TQMxE39S                        | 2         | 0.23%   |
| Toshiba Satellite A215                   | 2         | 0.23%   |
| Timi TM1701                              | 2         | 0.23%   |
| Samsung 305E4A/305E5A/305E7A             | 2         | 0.23%   |
| Positivo Mobile                          | 2         | 0.23%   |
| Lenovo Y50-70 20378                      | 2         | 0.23%   |
| Lenovo V340-17IWL 81RG                   | 2         | 0.23%   |
| Lenovo V330-15IKB 81AX                   | 2         | 0.23%   |
| Lenovo ThinkPad X230 23252EG             | 2         | 0.23%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 2         | 0.23%   |
| Lenovo Legion Y530-15ICH-1060 81LB       | 2         | 0.23%   |
| Lenovo Legion Y530-15ICH 81FV            | 2         | 0.23%   |
| Lenovo IdeaPad 330S-15IKB 81F5           | 2         | 0.23%   |
| Lenovo IdeaPad 120S-14IAP 81A5           | 2         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 123       | 13.99%  |
| Dell Latitude         | 64        | 7.28%   |
| Dell Inspiron         | 62        | 7.05%   |
| Acer Aspire           | 56        | 6.37%   |
| Lenovo IdeaPad        | 43        | 4.89%   |
| HP EliteBook          | 29        | 3.3%    |
| HP ProBook            | 26        | 2.96%   |
| HP Pavilion           | 25        | 2.84%   |
| Toshiba Satellite     | 21        | 2.39%   |
| Dell Precision        | 15        | 1.71%   |
| Dell Vostro           | 14        | 1.59%   |
| HP Laptop             | 12        | 1.37%   |
| Unknown               | 12        | 1.37%   |
| Dell XPS              | 10        | 1.14%   |
| HP Compaq             | 9         | 1.02%   |
| ASUS VivoBook         | 9         | 1.02%   |
| Acer Swift            | 6         | 0.68%   |
| Lenovo Legion         | 5         | 0.57%   |
| HP ZBook              | 4         | 0.46%   |
| HP Stream             | 4         | 0.46%   |
| HP Presario           | 4         | 0.46%   |
| HP ENVY               | 4         | 0.46%   |
| HP 250                | 4         | 0.46%   |
| Acer Nitro            | 4         | 0.46%   |
| Acer Extensa          | 4         | 0.46%   |
| Toshiba PORTEGE       | 3         | 0.34%   |
| Packard Bell EasyNote | 3         | 0.34%   |
| Intel powered         | 3         | 0.34%   |
| HP Notebook           | 3         | 0.34%   |
| HP 2000               | 3         | 0.34%   |
| HP 15                 | 3         | 0.34%   |
| Fujitsu LIFEBOOK      | 3         | 0.34%   |
| Dell System           | 3         | 0.34%   |
| ASUS K52F             | 3         | 0.34%   |
| Apple MacBookPro11    | 3         | 0.34%   |
| Alienware 17          | 3         | 0.34%   |
| TQ-Group TQMxE39S     | 2         | 0.23%   |
| Toshiba TECRA         | 2         | 0.23%   |
| Timi TM1701           | 2         | 0.23%   |
| Samsung 305E4A        | 2         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 92        | 10.47%  |
| 2019    | 89        | 10.13%  |
| 2017    | 77        | 8.76%   |
| 2018    | 76        | 8.65%   |
| 2012    | 74        | 8.42%   |
| 2016    | 63        | 7.17%   |
| 2013    | 62        | 7.05%   |
| 2014    | 61        | 6.94%   |
| 2008    | 55        | 6.26%   |
| 2010    | 54        | 6.14%   |
| 2015    | 51        | 5.8%    |
| 2009    | 44        | 5.01%   |
| 2020    | 35        | 3.98%   |
| 2007    | 17        | 1.93%   |
| 2006    | 7         | 0.8%    |
| Unknown | 6         | 0.68%   |
| 2021    | 5         | 0.57%   |
| 2004    | 5         | 0.57%   |
| 2005    | 3         | 0.34%   |
| 2022    | 1         | 0.11%   |
| 2003    | 1         | 0.11%   |
| 2002    | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 879       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 843       | 95.8%   |
| Enabled  | 37        | 4.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 873       | 99.32%  |
| Yes  | 6         | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 212       | 23.9%   |
| 3.01-4.0    | 200       | 22.55%  |
| 8.01-16.0   | 174       | 19.62%  |
| 16.01-24.0  | 147       | 16.57%  |
| 1.01-2.0    | 62        | 6.99%   |
| 32.01-64.0  | 40        | 4.51%   |
| 2.01-3.0    | 23        | 2.59%   |
| 0.51-1.0    | 16        | 1.8%    |
| 24.01-32.0  | 6         | 0.68%   |
| 0.01-0.5    | 5         | 0.56%   |
| 64.01-256.0 | 1         | 0.11%   |
| Unknown     | 1         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 322       | 34%     |
| 2.01-3.0   | 222       | 23.44%  |
| 4.01-8.0   | 133       | 14.04%  |
| 3.01-4.0   | 114       | 12.04%  |
| 0.51-1.0   | 90        | 9.5%    |
| 8.01-16.0  | 34        | 3.59%   |
| 0.01-0.5   | 25        | 2.64%   |
| 16.01-24.0 | 4         | 0.42%   |
| Unknown    | 3         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 636       | 71.14%  |
| 2      | 214       | 23.94%  |
| 3      | 32        | 3.58%   |
| 0      | 7         | 0.78%   |
| 5      | 2         | 0.22%   |
| 4      | 2         | 0.22%   |
| 7      | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 535       | 60.66%  |
| Yes       | 347       | 39.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 782       | 88.96%  |
| No        | 97        | 11.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 858       | 97.5%   |
| No        | 22        | 2.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 630       | 71.19%  |
| No        | 255       | 28.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 109       | 12.33%  |
| Brazil       | 86        | 9.73%   |
| Germany      | 82        | 9.28%   |
| France       | 72        | 8.14%   |
| Russia       | 60        | 6.79%   |
| Italy        | 48        | 5.43%   |
| Spain        | 36        | 4.07%   |
| Switzerland  | 25        | 2.83%   |
| Poland       | 24        | 2.71%   |
| Ukraine      | 19        | 2.15%   |
| Mexico       | 18        | 2.04%   |
| Portugal     | 17        | 1.92%   |
| UK           | 16        | 1.81%   |
| Chile        | 15        | 1.7%    |
| India        | 14        | 1.58%   |
| Canada       | 14        | 1.58%   |
| China        | 12        | 1.36%   |
| Argentina    | 12        | 1.36%   |
| Netherlands  | 10        | 1.13%   |
| Greece       | 10        | 1.13%   |
| Hungary      | 9         | 1.02%   |
| Czechia      | 9         | 1.02%   |
| Indonesia    | 8         | 0.9%    |
| Romania      | 7         | 0.79%   |
| Ireland      | 7         | 0.79%   |
| Denmark      | 7         | 0.79%   |
| Belgium      | 7         | 0.79%   |
| Venezuela    | 6         | 0.68%   |
| Turkey       | 6         | 0.68%   |
| Norway       | 6         | 0.68%   |
| New Zealand  | 6         | 0.68%   |
| Finland      | 6         | 0.68%   |
| Colombia     | 6         | 0.68%   |
| Australia    | 6         | 0.68%   |
| Vietnam      | 5         | 0.57%   |
| Thailand     | 5         | 0.57%   |
| Sweden       | 5         | 0.57%   |
| Tunisia      | 4         | 0.45%   |
| South Africa | 4         | 0.45%   |
| Slovakia     | 4         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Moscow         | 18        | 1.94%   |
| Sao Paulo      | 17        | 1.83%   |
| St Petersburg  | 16        | 1.72%   |
| Zurich         | 12        | 1.29%   |
| Paris          | 8         | 0.86%   |
| Madrid         | 8         | 0.86%   |
| Berlin         | 8         | 0.86%   |
| Hamburg        | 7         | 0.75%   |
| Wooster        | 6         | 0.65%   |
| Warsaw         | 6         | 0.65%   |
| New York       | 6         | 0.65%   |
| Milan          | 6         | 0.65%   |
| Mexico City    | 6         | 0.65%   |
| Prague         | 5         | 0.54%   |
| Lisbon         | 5         | 0.54%   |
| Helsinki       | 5         | 0.54%   |
| Budapest       | 5         | 0.54%   |
| Belo Horizonte | 5         | 0.54%   |
| Athens         | 5         | 0.54%   |
| Thessaloniki   | 4         | 0.43%   |
| Sofia          | 4         | 0.43%   |
| Rio de Janeiro | 4         | 0.43%   |
| Poznan         | 4         | 0.43%   |
| Florence       | 4         | 0.43%   |
| Cologne        | 4         | 0.43%   |
| Brasília      | 4         | 0.43%   |
| Violes         | 3         | 0.32%   |
| Vienna         | 3         | 0.32%   |
| Valencia       | 3         | 0.32%   |
| Santiago       | 3         | 0.32%   |
| Salvador       | 3         | 0.32%   |
| Rome           | 3         | 0.32%   |
| Porto Alegre   | 3         | 0.32%   |
| Porto          | 3         | 0.32%   |
| Phoenix        | 3         | 0.32%   |
| Perm           | 3         | 0.32%   |
| Naas           | 3         | 0.32%   |
| Munich         | 3         | 0.32%   |
| Kyiv           | 3         | 0.32%   |
| Hanoi          | 3         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 159       | 191    | 14.32%  |
| WDC                       | 157       | 177    | 14.14%  |
| Seagate                   | 145       | 178    | 13.06%  |
| Toshiba                   | 94        | 112    | 8.47%   |
| Unknown                   | 68        | 90     | 6.13%   |
| SanDisk                   | 62        | 71     | 5.59%   |
| Kingston                  | 59        | 69     | 5.32%   |
| Crucial                   | 50        | 59     | 4.5%    |
| Hitachi                   | 44        | 49     | 3.96%   |
| SK hynix                  | 31        | 42     | 2.79%   |
| HGST                      | 30        | 34     | 2.7%    |
| A-DATA Technology         | 20        | 23     | 1.8%    |
| Intel                     | 18        | 21     | 1.62%   |
| Micron Technology         | 14        | 15     | 1.26%   |
| Fujitsu                   | 10        | 11     | 0.9%    |
| Transcend                 | 6         | 6      | 0.54%   |
| PNY                       | 6         | 8      | 0.54%   |
| Patriot                   | 6         | 8      | 0.54%   |
| OCZ                       | 6         | 7      | 0.54%   |
| Micron/Crucial Technology | 6         | 6      | 0.54%   |
| LITEON                    | 6         | 7      | 0.54%   |
| LDLC                      | 6         | 6      | 0.54%   |
| Intenso                   | 6         | 9      | 0.54%   |
| China                     | 6         | 6      | 0.54%   |
| Team                      | 5         | 7      | 0.45%   |
| Silicon Motion            | 5         | 5      | 0.45%   |
| Apple                     | 5         | 5      | 0.45%   |
| Phison                    | 4         | 6      | 0.36%   |
| JMicron Technology        | 4         | 5      | 0.36%   |
| KingSpec                  | 3         | 3      | 0.27%   |
| KingDian                  | 3         | 3      | 0.27%   |
| Hewlett-Packard           | 3         | 3      | 0.27%   |
| GOODRAM                   | 3         | 3      | 0.27%   |
| Gigabyte Technology       | 3         | 3      | 0.27%   |
| Unknown                   | 3         | 4      | 0.27%   |
| Super Talent              | 2         | 3      | 0.18%   |
| SPCC                      | 2         | 3      | 0.18%   |
| ORICO                     | 2         | 2      | 0.18%   |
| LITEONIT                  | 2         | 2      | 0.18%   |
| KIOXIA                    | 2         | 2      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 18        | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 18        | 1.59%   |
| Kingston SA400S37240G 240GB SSD       | 18        | 1.59%   |
| Toshiba MQ01ABD100 1TB                | 16        | 1.41%   |
| HGST HTS721010A9E630 1TB              | 15        | 1.32%   |
| Unknown MMC Card  32GB                | 14        | 1.24%   |
| Seagate ST500LT012-1DG142 500GB       | 11        | 0.97%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 11        | 0.97%   |
| Samsung SSD 850 EVO 250GB             | 11        | 0.97%   |
| Crucial CT500MX500SSD1 500GB          | 11        | 0.97%   |
| Kingston SA400S37120G 120GB SSD       | 10        | 0.88%   |
| Unknown MMC Card  64GB                | 9         | 0.79%   |
| WDC WD10SPZX-21Z10T0 1TB              | 8         | 0.71%   |
| Crucial CT240BX500SSD1 240GB          | 8         | 0.71%   |
| Toshiba MQ04ABF100 1TB                | 7         | 0.62%   |
| Toshiba MQ01ABF050 500GB              | 7         | 0.62%   |
| Seagate ST9500325AS 500GB             | 7         | 0.62%   |
| Hitachi HTS547550A9E384 500GB         | 7         | 0.62%   |
| WDC WD10SPZX-24Z10 1TB                | 6         | 0.53%   |
| Toshiba NVMe SSD Drive 256GB          | 6         | 0.53%   |
| SanDisk SSD PLUS 240GB                | 6         | 0.53%   |
| Samsung SSD 860 EVO 500GB             | 6         | 0.53%   |
| Samsung SSD 860 EVO 250GB             | 6         | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 5         | 0.44%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 5         | 0.44%   |
| Seagate ST2000LM015-2E8174 2TB        | 5         | 0.44%   |
| Seagate ST1000LM049-2GH172 1TB        | 5         | 0.44%   |
| Seagate ST1000LM048-2E7172 1TB        | 5         | 0.44%   |
| Samsung NVMe SSD Drive 512GB          | 5         | 0.44%   |
| Samsung NVMe SSD Drive 256GB          | 5         | 0.44%   |
| Samsung MZVLB512HBJQ-000L7 512GB      | 5         | 0.44%   |
| Patriot Burst 240GB SSD               | 5         | 0.44%   |
| Micron/Crucial NVMe SSD Drive 500GB   | 5         | 0.44%   |
| Kingston SA400S37480G 480GB SSD       | 5         | 0.44%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 4         | 0.35%   |
| WDC WD5000LPCX-21VHAT0 500GB          | 4         | 0.35%   |
| WDC WD10JPVX-22JC3T0 1TB              | 4         | 0.35%   |
| WDC WD10JPCX-24UE4T0 1TB              | 4         | 0.35%   |
| Toshiba MQ01ABD050 500GB              | 4         | 0.35%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 4         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 141       | 173    | 33.1%   |
| WDC                 | 108       | 119    | 25.35%  |
| Toshiba             | 65        | 73     | 15.26%  |
| Hitachi             | 44        | 49     | 10.33%  |
| HGST                | 30        | 34     | 7.04%   |
| Samsung Electronics | 13        | 13     | 3.05%   |
| Fujitsu             | 10        | 11     | 2.35%   |
| Intenso             | 3         | 5      | 0.7%    |
| Unknown             | 2         | 2      | 0.47%   |
| JMicron Technology  | 2         | 2      | 0.47%   |
| TO Exter            | 1         | 1      | 0.23%   |
| SILICONMOTION       | 1         | 1      | 0.23%   |
| QNAP                | 1         | 2      | 0.23%   |
| LaCie               | 1         | 1      | 0.23%   |
| IBM/Hitachi         | 1         | 2      | 0.23%   |
| Hewlett-Packard     | 1         | 1      | 0.23%   |
| ASMT                | 1         | 5      | 0.23%   |
| Apple               | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 97        | 112    | 22.88%  |
| Kingston            | 52        | 61     | 12.26%  |
| Crucial             | 49        | 58     | 11.56%  |
| SanDisk             | 47        | 54     | 11.08%  |
| WDC                 | 26        | 30     | 6.13%   |
| A-DATA Technology   | 17        | 20     | 4.01%   |
| SK hynix            | 11        | 14     | 2.59%   |
| Micron Technology   | 11        | 12     | 2.59%   |
| Intel               | 9         | 10     | 2.12%   |
| Toshiba             | 6         | 7      | 1.42%   |
| Patriot             | 6         | 8      | 1.42%   |
| OCZ                 | 6         | 7      | 1.42%   |
| LITEON              | 6         | 7      | 1.42%   |
| China               | 6         | 6      | 1.42%   |
| Transcend           | 5         | 5      | 1.18%   |
| Team                | 5         | 7      | 1.18%   |
| PNY                 | 5         | 7      | 1.18%   |
| LDLC                | 5         | 5      | 1.18%   |
| Apple               | 4         | 4      | 0.94%   |
| KingSpec            | 3         | 3      | 0.71%   |
| KingDian            | 3         | 3      | 0.71%   |
| Intenso             | 3         | 4      | 0.71%   |
| GOODRAM             | 3         | 3      | 0.71%   |
| Gigabyte Technology | 3         | 3      | 0.71%   |
| Super Talent        | 2         | 3      | 0.47%   |
| SPCC                | 2         | 3      | 0.47%   |
| Seagate             | 2         | 2      | 0.47%   |
| LITEONIT            | 2         | 2      | 0.47%   |
| Hewlett-Packard     | 2         | 2      | 0.47%   |
| BIWIN               | 2         | 2      | 0.47%   |
| AMD                 | 2         | 2      | 0.47%   |
| TurXun              | 1         | 1      | 0.24%   |
| TOPMORE             | 1         | 1      | 0.24%   |
| TCSUNBOW            | 1         | 1      | 0.24%   |
| TAMMUZ              | 1         | 2      | 0.24%   |
| SNR-ML              | 1         | 1      | 0.24%   |
| Smartbuy            | 1         | 1      | 0.24%   |
| Qumo                | 1         | 1      | 0.24%   |
| Plextor             | 1         | 1      | 0.24%   |
| PHD 3.0             | 1         | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 411       | 495    | 38.66%  |
| SSD     | 398       | 490    | 37.44%  |
| NVMe    | 165       | 217    | 15.52%  |
| MMC     | 74        | 98     | 6.96%   |
| Unknown | 15        | 18     | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 718       | 953    | 72.31%  |
| NVMe | 165       | 215    | 16.62%  |
| MMC  | 74        | 98     | 7.45%   |
| SAS  | 36        | 52     | 3.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 544       | 681    | 68.77%  |
| 0.51-1.0   | 215       | 263    | 27.18%  |
| 1.01-2.0   | 25        | 31     | 3.16%   |
| 4.01-10.0  | 4         | 5      | 0.51%   |
| 3.01-4.0   | 2         | 3      | 0.25%   |
| 2.01-3.0   | 1         | 2      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 303       | 33.55%  |
| 251-500        | 210       | 23.26%  |
| 501-1000       | 131       | 14.51%  |
| 51-100         | 80        | 8.86%   |
| 1001-2000      | 49        | 5.43%   |
| Unknown        | 44        | 4.87%   |
| 21-50          | 40        | 4.43%   |
| 1-20           | 20        | 2.21%   |
| 2001-3000      | 15        | 1.66%   |
| More than 3000 | 11        | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 293       | 30.97%  |
| 21-50          | 172       | 18.18%  |
| 101-250        | 170       | 17.97%  |
| 51-100         | 119       | 12.58%  |
| 251-500        | 78        | 8.25%   |
| 501-1000       | 44        | 4.65%   |
| Unknown        | 44        | 4.65%   |
| 1001-2000      | 17        | 1.8%    |
| 2001-3000      | 5         | 0.53%   |
| More than 3000 | 3         | 0.32%   |
| 0              | 1         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                | 3         | 3      | 3.16%   |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 3.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 4      | 3.16%   |
| Toshiba MQ01ACF050 500GB              | 2         | 2      | 2.11%   |
| Seagate ST9250315AS 250GB             | 2         | 2      | 2.11%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 2.11%   |
| Hitachi HTS547550A9E384 500GB         | 2         | 2      | 2.11%   |
| A-DATA Technology SX900 256GB SSD     | 2         | 2      | 2.11%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 1.05%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 1         | 1      | 1.05%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 1.05%   |
| WDC WD3200BPVT-00JJ5T0 320GB          | 1         | 1      | 1.05%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 1      | 1.05%   |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 1.05%   |
| WDC WD2500BPVT-22ZEST0 250GB          | 1         | 1      | 1.05%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 1.05%   |
| WDC WD10JUCT-63CYNY0 1TB              | 1         | 1      | 1.05%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 1.05%   |
| Toshiba MQ01ABF050H 500GB             | 1         | 1      | 1.05%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.05%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 1.05%   |
| Toshiba MK2555GSXF 250GB              | 1         | 1      | 1.05%   |
| Toshiba MK2546GSX 250GB               | 1         | 1      | 1.05%   |
| Toshiba MK2035GSS 200GB               | 1         | 1      | 1.05%   |
| Toshiba MK1637GSX 160GB               | 1         | 1      | 1.05%   |
| Team L5 LITE SSD 60GB                 | 1         | 1      | 1.05%   |
| SK hynix SC311 SATA 256GB             | 1         | 1      | 1.05%   |
| SK hynix HFS256G39MND-2300A 256GB SSD | 1         | 1      | 1.05%   |
| SK hynix HFS060G32MNB-2000A 64GB SSD  | 1         | 2      | 1.05%   |
| Seagate ST9808210A 80GB               | 1         | 1      | 1.05%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.05%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.05%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 1.05%   |
| Seagate ST9160412AS 160GB             | 1         | 1      | 1.05%   |
| Seagate ST9120822AS 120GB             | 1         | 1      | 1.05%   |
| Seagate ST750LM028-1KK162 752GB       | 1         | 1      | 1.05%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.05%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 1      | 1.05%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 1.05%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 3      | 1.05%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 24     | 22.11%  |
| Hitachi             | 16        | 16     | 16.84%  |
| Toshiba             | 13        | 13     | 13.68%  |
| WDC                 | 9         | 9      | 9.47%   |
| Samsung Electronics | 7         | 7      | 7.37%   |
| SanDisk             | 5         | 5      | 5.26%   |
| A-DATA Technology   | 5         | 5      | 5.26%   |
| Fujitsu             | 4         | 4      | 4.21%   |
| SK hynix            | 3         | 4      | 3.16%   |
| Kingston            | 2         | 3      | 2.11%   |
| Intel               | 2         | 2      | 2.11%   |
| HGST                | 2         | 2      | 2.11%   |
| Team                | 1         | 1      | 1.05%   |
| Micron Technology   | 1         | 1      | 1.05%   |
| KingSpec            | 1         | 1      | 1.05%   |
| KingDian            | 1         | 1      | 1.05%   |
| Crucial             | 1         | 1      | 1.05%   |
| Apple               | 1         | 1      | 1.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 24     | 30.43%  |
| Hitachi             | 16        | 16     | 23.19%  |
| Toshiba             | 13        | 13     | 18.84%  |
| WDC                 | 8         | 8      | 11.59%  |
| Samsung Electronics | 5         | 5      | 7.25%   |
| Fujitsu             | 4         | 4      | 5.8%    |
| HGST                | 2         | 2      | 2.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 67        | 72     | 72.04%  |
| SSD  | 26        | 28     | 27.96%  |

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
| Detected | 476       | 733    | 49.64%  |
| Works    | 390       | 485    | 40.67%  |
| Malfunc  | 93        | 100    | 9.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 691       | 72.97%  |
| AMD                              | 75        | 7.92%   |
| Samsung Electronics              | 57        | 6.02%   |
| SanDisk                          | 32        | 3.38%   |
| Toshiba America Info Systems     | 24        | 2.53%   |
| SK hynix                         | 14        | 1.48%   |
| Micron/Crucial Technology        | 7         | 0.74%   |
| Kingston Technology Company      | 7         | 0.74%   |
| Silicon Motion                   | 6         | 0.63%   |
| Phison Electronics               | 6         | 0.63%   |
| Nvidia                           | 6         | 0.63%   |
| ADATA Technology                 | 5         | 0.53%   |
| Silicon Integrated Systems [SiS] | 4         | 0.42%   |
| Micron Technology                | 3         | 0.32%   |
| KIOXIA                           | 3         | 0.32%   |
| Union Memory (Shenzhen)          | 2         | 0.21%   |
| VIA Technologies                 | 1         | 0.11%   |
| Silicon Image                    | 1         | 0.11%   |
| Shenzhen Longsys Electronics     | 1         | 0.11%   |
| JMicron Technology               | 1         | 0.11%   |
| Adaptec                          | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 110       | 10.91%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 82        | 8.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 63        | 6.25%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 55        | 5.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 52        | 5.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 47        | 4.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 37        | 3.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 35        | 3.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 31        | 3.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 26        | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 25        | 2.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 21        | 2.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 17        | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 17        | 1.69%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 16        | 1.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 16        | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 16        | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 15        | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 14        | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 13        | 1.29%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 11        | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                            | 11        | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 0.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 0.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 8         | 0.79%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 8         | 0.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 7         | 0.69%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 7         | 0.69%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 7         | 0.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 0.69%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 6         | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 0.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 0.6%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 6         | 0.6%    |
| AMD SB600 Non-Raid-5 SATA                                                        | 6         | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 0.5%    |
| Phison E12 NVMe Controller                                                       | 5         | 0.5%    |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                        | 5         | 0.5%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 5         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 678       | 69.04%  |
| NVMe | 168       | 17.11%  |
| IDE  | 81        | 8.25%   |
| RAID | 54        | 5.5%    |
| SCSI | 1         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 784       | 89.19%  |
| AMD          | 89        | 10.13%  |
| ARM          | 4         | 0.46%   |
| CentaurHauls | 1         | 0.11%   |
| Unknown      | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz           | 30        | 3.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 27        | 3.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 22        | 2.5%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 20        | 2.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 15        | 1.71%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 15        | 1.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 14        | 1.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 13        | 1.48%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 13        | 1.48%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 11        | 1.25%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 10        | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 9         | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 8         | 0.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 8         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 8         | 0.91%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 8         | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 8         | 0.91%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 8         | 0.91%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 8         | 0.91%   |
| Intel Atom CPU N455 @ 1.66GHz               | 8         | 0.91%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 7         | 0.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz           | 7         | 0.8%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 7         | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz           | 7         | 0.8%    |
| Intel Core i7-5600U CPU @ 2.60GHz           | 6         | 0.68%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 6         | 0.68%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 6         | 0.68%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 6         | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 6         | 0.68%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 6         | 0.68%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 5         | 0.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 5         | 0.57%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 5         | 0.57%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 5         | 0.57%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 5         | 0.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 5         | 0.57%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 5         | 0.57%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 5         | 0.57%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 5         | 0.57%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 5         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 248       | 28.21%  |
| Intel Core i7                  | 231       | 26.28%  |
| Intel Core i3                  | 83        | 9.44%   |
| Intel Core 2 Duo               | 49        | 5.57%   |
| Intel Celeron                  | 47        | 5.35%   |
| Intel Atom                     | 38        | 4.32%   |
| Intel Pentium                  | 24        | 2.73%   |
| Other                          | 13        | 1.48%   |
| Intel Pentium Dual-Core        | 12        | 1.37%   |
| Intel Pentium Dual             | 10        | 1.14%   |
| AMD Ryzen 5                    | 10        | 1.14%   |
| Intel Pentium M                | 9         | 1.02%   |
| AMD A8                         | 9         | 1.02%   |
| AMD A4                         | 8         | 0.91%   |
| AMD Ryzen 7 PRO                | 7         | 0.8%    |
| AMD Ryzen 3                    | 7         | 0.8%    |
| AMD E                          | 7         | 0.8%    |
| Intel Core 2                   | 6         | 0.68%   |
| AMD A6                         | 6         | 0.68%   |
| AMD Turion 64 X2 Mobile        | 5         | 0.57%   |
| Intel Celeron Dual-Core        | 4         | 0.46%   |
| AMD Ryzen 7                    | 4         | 0.46%   |
| AMD E1                         | 4         | 0.46%   |
| Intel Genuine                  | 3         | 0.34%   |
| AMD E2                         | 3         | 0.34%   |
| Intel Pentium Silver           | 2         | 0.23%   |
| Intel Pentium 4                | 2         | 0.23%   |
| Intel Core i9                  | 2         | 0.23%   |
| Intel Core Duo                 | 2         | 0.23%   |
| Intel Celeron M                | 2         | 0.23%   |
| ARM ARMv7                      | 2         | 0.23%   |
| AMD Ryzen 5 PRO                | 2         | 0.23%   |
| AMD C-60                       | 2         | 0.23%   |
| Intel Pentium III              | 1         | 0.11%   |
| Intel Core m7                  | 1         | 0.11%   |
| Intel Core m3                  | 1         | 0.11%   |
| CentaurHauls VIA C7            | 1         | 0.11%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.11%   |
| AMD Turion II Dual-Core        | 1         | 0.11%   |
| AMD Phenom II                  | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 524       | 59.61%  |
| 4      | 280       | 31.85%  |
| 1      | 40        | 4.55%   |
| 6      | 26        | 2.96%   |
| 8      | 7         | 0.8%    |
| 12     | 1         | 0.11%   |
| 3      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 878       | 99.89%  |
| 2      | 1         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 621       | 70.57%  |
| 1      | 259       | 29.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 831       | 94.43%  |
| 32-bit         | 26        | 2.95%   |
| Unknown        | 22        | 2.5%    |
| 64-bit         | 1         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 341       | 37.72%  |
| 0x206a7    | 55        | 6.08%   |
| 0x306a9    | 43        | 4.76%   |
| 0x806ec    | 39        | 4.31%   |
| 0x1067a    | 35        | 3.87%   |
| 0x806ea    | 31        | 3.43%   |
| 0x40651    | 24        | 2.65%   |
| 0x306d4    | 24        | 2.65%   |
| 0x306c3    | 21        | 2.32%   |
| 0x806e9    | 20        | 2.21%   |
| 0x20655    | 19        | 2.1%    |
| 0x406e3    | 18        | 1.99%   |
| 0x906ea    | 15        | 1.66%   |
| 0x6fd      | 14        | 1.55%   |
| 0x30678    | 13        | 1.44%   |
| 0x106ca    | 13        | 1.44%   |
| 0x20652    | 10        | 1.11%   |
| 0x806eb    | 9         | 1%      |
| 0x406c4    | 9         | 1%      |
| 0x406c3    | 9         | 1%      |
| 0x08108102 | 9         | 1%      |
| 0x906e9    | 8         | 0.88%   |
| 0x05000119 | 8         | 0.88%   |
| 0x706e5    | 7         | 0.77%   |
| 0x6d8      | 6         | 0.66%   |
| 0x506e3    | 6         | 0.66%   |
| 0x10676    | 6         | 0.66%   |
| 0x706a1    | 5         | 0.55%   |
| 0x07030105 | 5         | 0.55%   |
| 0x906ed    | 4         | 0.44%   |
| 0x6f6      | 4         | 0.44%   |
| 0x506c9    | 4         | 0.44%   |
| 0x106c2    | 4         | 0.44%   |
| 0x03000027 | 4         | 0.44%   |
| 0x806c1    | 3         | 0.33%   |
| 0x6d6      | 3         | 0.33%   |
| 0x506ca    | 3         | 0.33%   |
| 0x106e5    | 3         | 0.33%   |
| 0x08600106 | 3         | 0.33%   |
| 0x0810100b | 3         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 220       | 25.03%  |
| SandyBridge      | 85        | 9.67%   |
| IvyBridge        | 76        | 8.65%   |
| Haswell          | 72        | 8.19%   |
| Penryn           | 57        | 6.48%   |
| Skylake          | 49        | 5.57%   |
| Silvermont       | 41        | 4.66%   |
| Westmere         | 38        | 4.32%   |
| Broadwell        | 34        | 3.87%   |
| Core             | 25        | 2.84%   |
| Bonnell          | 25        | 2.84%   |
| P6               | 17        | 1.93%   |
| Zen+             | 14        | 1.59%   |
| Bobcat           | 14        | 1.59%   |
| Puma             | 10        | 1.14%   |
| Goldmont plus    | 10        | 1.14%   |
| Zen              | 9         | 1.02%   |
| Goldmont         | 9         | 1.02%   |
| IceLake          | 8         | 0.91%   |
| K8 Hammer        | 7         | 0.8%    |
| Excavator        | 6         | 0.68%   |
| CometLake        | 6         | 0.68%   |
| Unknown          | 6         | 0.68%   |
| Zen 2            | 5         | 0.57%   |
| TigerLake        | 5         | 0.57%   |
| Nehalem          | 5         | 0.57%   |
| K10 Llano        | 5         | 0.57%   |
| Jaguar           | 5         | 0.57%   |
| Steamroller      | 3         | 0.34%   |
| Piledriver       | 3         | 0.34%   |
| K8 & K10 hybrid  | 3         | 0.34%   |
| K10              | 3         | 0.34%   |
| NetBurst         | 2         | 0.23%   |
| Zen 3            | 1         | 0.11%   |
| Alderlake Hybrid | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 707       | 64.45%  |
| Nvidia                           | 216       | 19.69%  |
| AMD                              | 170       | 15.5%   |
| Silicon Integrated Systems [SiS] | 3         | 0.27%   |
| VIA Technologies                 | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 78        | 6.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 72        | 6.36%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 66        | 5.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 45        | 3.98%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 40        | 3.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 40        | 3.53%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 38        | 3.36%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 37        | 3.27%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 31        | 2.74%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 2.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 26        | 2.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 24        | 2.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 2.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 1.77%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 18        | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 1.5%    |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 15        | 1.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 1.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 1.15%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 13        | 1.15%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 11        | 0.97%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 0.88%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 9         | 0.8%    |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.71%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 0.71%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 8         | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.71%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 8         | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 0.71%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 8         | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.62%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.62%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 7         | 0.62%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 7         | 0.62%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.62%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 0.62%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7         | 0.62%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 6         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 485       | 54.93%  |
| Intel + Nvidia     | 163       | 18.46%  |
| 1 x AMD            | 108       | 12.23%  |
| Intel + AMD        | 54        | 6.12%   |
| 1 x Nvidia         | 51        | 5.78%   |
| 2 x AMD            | 8         | 0.91%   |
| Other              | 6         | 0.68%   |
| 1 x SiS            | 3         | 0.34%   |
| Intel + 2 x Nvidia | 2         | 0.23%   |
| 2 x Nvidia         | 1         | 0.11%   |
| 2 x Intel          | 1         | 0.11%   |
| 1 x VIA            | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 793       | 89.3%   |
| Proprietary | 71        | 8%      |
| Unknown     | 24        | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 720       | 80.99%  |
| 0.01-0.5   | 65        | 7.31%   |
| 1.01-2.0   | 51        | 5.74%   |
| 0.51-1.0   | 28        | 3.15%   |
| 3.01-4.0   | 16        | 1.8%    |
| 7.01-8.0   | 4         | 0.45%   |
| 5.01-6.0   | 4         | 0.45%   |
| 2.01-3.0   | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 209       | 20.88%  |
| LG Display              | 160       | 15.98%  |
| Samsung Electronics     | 117       | 11.69%  |
| BOE                     | 117       | 11.69%  |
| Chimei Innolux          | 106       | 10.59%  |
| Dell                    | 35        | 3.5%    |
| Lenovo                  | 27        | 2.7%    |
| Goldstar                | 23        | 2.3%    |
| Chi Mei Optoelectronics | 23        | 2.3%    |
| Sharp                   | 16        | 1.6%    |
| Hewlett-Packard         | 14        | 1.4%    |
| InfoVision              | 13        | 1.3%    |
| Iiyama                  | 12        | 1.2%    |
| Apple                   | 12        | 1.2%    |
| Philips                 | 10        | 1%      |
| Ancor Communications    | 9         | 0.9%    |
| PANDA                   | 8         | 0.8%    |
| LG Philips              | 8         | 0.8%    |
| AOC                     | 8         | 0.8%    |
| Sony                    | 6         | 0.6%    |
| HannStar                | 6         | 0.6%    |
| CPT                     | 6         | 0.6%    |
| Acer                    | 6         | 0.6%    |
| BenQ                    | 5         | 0.5%    |
| LGD                     | 3         | 0.3%    |
| CSO                     | 3         | 0.3%    |
| ViewSonic               | 2         | 0.2%    |
| Quanta Display          | 2         | 0.2%    |
| Panasonic               | 2         | 0.2%    |
| InnoLux Display         | 2         | 0.2%    |
| Eizo                    | 2         | 0.2%    |
| ASUSTek Computer        | 2         | 0.2%    |
| Xiaomi                  | 1         | 0.1%    |
| Wacom                   | 1         | 0.1%    |
| Vizio                   | 1         | 0.1%    |
| Unknown (XXX)           | 1         | 0.1%    |
| Unknown                 | 1         | 0.1%    |
| SKY                     | 1         | 0.1%    |
| Seiko/Epson             | 1         | 0.1%    |
| RTK                     | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 11        | 1.08%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 10        | 0.99%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 8         | 0.79%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 8         | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.79%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 6         | 0.59%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.59%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 6         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 6         | 0.59%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 6         | 0.59%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 6         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.49%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 5         | 0.49%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 5         | 0.49%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 4         | 0.39%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 4         | 0.39%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 4         | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 4         | 0.39%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 4         | 0.39%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 4         | 0.39%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch          | 4         | 0.39%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x174mm 14.0-inch       | 4         | 0.39%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch         | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch         | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch        | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 4         | 0.39%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 3         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch  | 3         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 3         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 3         | 0.3%    |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 3         | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3         | 0.3%    |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 3         | 0.3%    |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 3         | 0.3%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 343       | 36.41%  |
| 1920x1080 (FHD)    | 340       | 36.09%  |
| 1600x900 (HD+)     | 50        | 5.31%   |
| 1280x800 (WXGA)    | 39        | 4.14%   |
| 3840x2160 (4K)     | 24        | 2.55%   |
| 1920x1200 (WUXGA)  | 23        | 2.44%   |
| 2560x1440 (QHD)    | 18        | 1.91%   |
| 1024x600           | 18        | 1.91%   |
| 1440x900 (WXGA+)   | 17        | 1.8%    |
| 1280x1024 (SXGA)   | 11        | 1.17%   |
| 1680x1050 (WSXGA+) | 10        | 1.06%   |
| 2560x1080          | 9         | 0.96%   |
| 1360x768           | 9         | 0.96%   |
| 3200x1800 (QHD+)   | 5         | 0.53%   |
| 2880x1800          | 4         | 0.42%   |
| 3840x2400          | 3         | 0.32%   |
| 3440x1440          | 3         | 0.32%   |
| 1600x1200          | 2         | 0.21%   |
| 1024x768 (XGA)     | 2         | 0.21%   |
| Unknown            | 2         | 0.21%   |
| 7680x2160          | 1         | 0.11%   |
| 640x480            | 1         | 0.11%   |
| 3840x1100          | 1         | 0.11%   |
| 2880x1920          | 1         | 0.11%   |
| 2560x1600          | 1         | 0.11%   |
| 2256x1504          | 1         | 0.11%   |
| 1800x1440          | 1         | 0.11%   |
| 1680x945           | 1         | 0.11%   |
| 1280x768           | 1         | 0.11%   |
| 1280x720 (HD)      | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 375       | 37.58%  |
| 14      | 138       | 13.83%  |
| 13      | 137       | 13.73%  |
| 17      | 61        | 6.11%   |
| 12      | 46        | 4.61%   |
| 24      | 37        | 3.71%   |
| 23      | 27        | 2.71%   |
| 27      | 26        | 2.61%   |
| 21      | 21        | 2.1%    |
| 11      | 19        | 1.9%    |
| Unknown | 18        | 1.8%    |
| 10      | 17        | 1.7%    |
| 18      | 11        | 1.1%    |
| 34      | 10        | 1%      |
| 19      | 8         | 0.8%    |
| 31      | 7         | 0.7%    |
| 40      | 5         | 0.5%    |
| 22      | 5         | 0.5%    |
| 25      | 4         | 0.4%    |
| 16      | 4         | 0.4%    |
| 72      | 3         | 0.3%    |
| 20      | 3         | 0.3%    |
| 63      | 2         | 0.2%    |
| 54      | 2         | 0.2%    |
| 32      | 2         | 0.2%    |
| 8       | 2         | 0.2%    |
| 84      | 1         | 0.1%    |
| 65      | 1         | 0.1%    |
| 49      | 1         | 0.1%    |
| 39      | 1         | 0.1%    |
| 29      | 1         | 0.1%    |
| 28      | 1         | 0.1%    |
| 26      | 1         | 0.1%    |
| 9       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 580       | 58.7%   |
| 201-300     | 142       | 14.37%  |
| 501-600     | 88        | 8.91%   |
| 351-400     | 75        | 7.59%   |
| 401-500     | 42        | 4.25%   |
| Unknown     | 18        | 1.82%   |
| 701-800     | 12        | 1.21%   |
| 601-700     | 12        | 1.21%   |
| 801-900     | 6         | 0.61%   |
| 1001-1500   | 6         | 0.61%   |
| 1501-2000   | 4         | 0.4%    |
| 101-200     | 3         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 749       | 85.21%  |
| 16/10   | 81        | 9.22%   |
| Unknown | 13        | 1.48%   |
| 5/4     | 11        | 1.25%   |
| 21/9    | 10        | 1.14%   |
| 4/3     | 7         | 0.8%    |
| 3/2     | 7         | 0.8%    |
| 3.40    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 371       | 37.21%  |
| 81-90          | 221       | 22.17%  |
| 201-250        | 71        | 7.12%   |
| 71-80          | 55        | 5.52%   |
| 121-130        | 46        | 4.61%   |
| 61-70          | 45        | 4.51%   |
| 301-350        | 27        | 2.71%   |
| 351-500        | 21        | 2.11%   |
| 51-60          | 20        | 2.01%   |
| 151-200        | 20        | 2.01%   |
| Unknown        | 18        | 1.81%   |
| 41-50          | 17        | 1.71%   |
| 141-150        | 16        | 1.6%    |
| 251-300        | 13        | 1.3%    |
| More than 1000 | 10        | 1%      |
| 131-140        | 10        | 1%      |
| 501-1000       | 6         | 0.6%    |
| 91-100         | 5         | 0.5%    |
| 1-40           | 3         | 0.3%    |
| 111-120        | 2         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 360       | 36.89%  |
| 121-160       | 342       | 35.04%  |
| 51-100        | 178       | 18.24%  |
| 161-240       | 49        | 5.02%   |
| Unknown       | 18        | 1.84%   |
| More than 240 | 17        | 1.74%   |
| 1-50          | 12        | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 715       | 79.53%  |
| 2     | 151       | 16.8%   |
| 3     | 20        | 2.22%   |
| 0     | 13        | 1.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 451       | 31.19%  |
| Realtek Semiconductor             | 423       | 29.25%  |
| Qualcomm Atheros                  | 278       | 19.23%  |
| Broadcom                          | 89        | 6.15%   |
| Marvell Technology Group          | 31        | 2.14%   |
| Broadcom Limited                  | 25        | 1.73%   |
| Ralink                            | 18        | 1.24%   |
| JMicron Technology                | 13        | 0.9%    |
| TP-Link                           | 9         | 0.62%   |
| Dell                              | 9         | 0.62%   |
| Lenovo                            | 7         | 0.48%   |
| Huawei Technologies               | 7         | 0.48%   |
| Sierra Wireless                   | 6         | 0.41%   |
| Qualcomm Atheros Communications   | 6         | 0.41%   |
| Ericsson Business Mobile Networks | 6         | 0.41%   |
| ASIX Electronics                  | 6         | 0.41%   |
| Samsung Electronics               | 5         | 0.35%   |
| Ralink Technology                 | 5         | 0.35%   |
| Nvidia                            | 5         | 0.35%   |
| Xiaomi                            | 4         | 0.28%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.28%   |
| Fibocom                           | 4         | 0.28%   |
| DisplayLink                       | 4         | 0.28%   |
| Hewlett-Packard                   | 3         | 0.21%   |
| Toshiba                           | 2         | 0.14%   |
| Shenzhen Goodix Technology        | 2         | 0.14%   |
| Qualcomm                          | 2         | 0.14%   |
| Edimax Technology                 | 2         | 0.14%   |
| D-Link System                     | 2         | 0.14%   |
| Cypress Semiconductor             | 2         | 0.14%   |
| ZyXEL Communications              | 1         | 0.07%   |
| Spreadtrum Communications         | 1         | 0.07%   |
| Senao                             | 1         | 0.07%   |
| Quectel Wireless Solutions        | 1         | 0.07%   |
| NetGear                           | 1         | 0.07%   |
| Motorola PCS                      | 1         | 0.07%   |
| Microsoft                         | 1         | 0.07%   |
| MediaTek                          | 1         | 0.07%   |
| LSI                               | 1         | 0.07%   |
| LG Electronics                    | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 249       | 14.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 113       | 6.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 48        | 2.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 48        | 2.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 46        | 2.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 45        | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 41        | 2.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 37        | 2.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 2.03%   |
| Intel Wireless 8265 / 8275                                              | 35        | 1.97%   |
| Intel Wireless 7260                                                     | 33        | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 32        | 1.8%    |
| Intel Wireless 7265                                                     | 30        | 1.69%   |
| Intel Wi-Fi 6 AX200                                                     | 25        | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 19        | 1.07%   |
| Intel Wireless 8260                                                     | 19        | 1.07%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 19        | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 19        | 1.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 0.96%   |
| Intel Wireless 3165                                                     | 16        | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                                   | 15        | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                                | 14        | 0.79%   |
| Intel 82567LM Gigabit Network Connection                                | 14        | 0.79%   |
| Intel Wireless 3160                                                     | 13        | 0.73%   |
| Intel WiFi Link 5100                                                    | 13        | 0.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 0.73%   |
| Intel Ethernet Connection I219-LM                                       | 13        | 0.73%   |
| Intel Ethernet Connection I218-LM                                       | 13        | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 13        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                    | 12        | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                                   | 12        | 0.68%   |
| Intel Centrino Ultimate-N 6300                                          | 12        | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 11        | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 11        | 0.62%   |
| Intel Ethernet Connection I217-LM                                       | 9         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 424       | 46.8%   |
| Qualcomm Atheros                | 246       | 27.15%  |
| Realtek Semiconductor           | 95        | 10.49%  |
| Broadcom                        | 64        | 7.06%   |
| Ralink                          | 18        | 1.99%   |
| Broadcom Limited                | 13        | 1.43%   |
| TP-Link                         | 7         | 0.77%   |
| Sierra Wireless                 | 6         | 0.66%   |
| Qualcomm Atheros Communications | 6         | 0.66%   |
| Dell                            | 6         | 0.66%   |
| Ralink Technology               | 5         | 0.55%   |
| Fibocom                         | 4         | 0.44%   |
| Edimax Technology               | 2         | 0.22%   |
| ZyXEL Communications            | 1         | 0.11%   |
| Senao                           | 1         | 0.11%   |
| Quectel Wireless Solutions      | 1         | 0.11%   |
| Qualcomm                        | 1         | 0.11%   |
| NetGear                         | 1         | 0.11%   |
| Microsoft                       | 1         | 0.11%   |
| MediaTek                        | 1         | 0.11%   |
| Hewlett-Packard                 | 1         | 0.11%   |
| D-Link System                   | 1         | 0.11%   |
| Cinterion                       | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 48        | 5.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 48        | 5.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 45        | 4.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 41        | 4.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 3.95%   |
| Intel Wireless 8265 / 8275                                              | 35        | 3.84%   |
| Intel Wireless 7260                                                     | 33        | 3.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 32        | 3.51%   |
| Intel Wireless 7265                                                     | 30        | 3.29%   |
| Intel Wi-Fi 6 AX200                                                     | 25        | 2.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 2.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 19        | 2.09%   |
| Intel Wireless 8260                                                     | 19        | 2.09%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 19        | 2.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 19        | 2.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 1.87%   |
| Intel Wireless 3165                                                     | 16        | 1.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.54%   |
| Intel Wireless 3160                                                     | 13        | 1.43%   |
| Intel WiFi Link 5100                                                    | 13        | 1.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 1.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 13        | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 1.32%   |
| Intel Centrino Ultimate-N 6300                                          | 12        | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.99%   |
| Intel Centrino Advanced-N 6200                                          | 9         | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 0.99%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 9         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 0.88%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 8         | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.88%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 8         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.77%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.77%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 396       | 48.41%  |
| Intel                            | 209       | 25.55%  |
| Qualcomm Atheros                 | 69        | 8.44%   |
| Broadcom                         | 36        | 4.4%    |
| Marvell Technology Group         | 31        | 3.79%   |
| JMicron Technology               | 13        | 1.59%   |
| Broadcom Limited                 | 12        | 1.47%   |
| Lenovo                           | 7         | 0.86%   |
| ASIX Electronics                 | 6         | 0.73%   |
| Samsung Electronics              | 5         | 0.61%   |
| Nvidia                           | 5         | 0.61%   |
| Xiaomi                           | 4         | 0.49%   |
| Silicon Integrated Systems [SiS] | 4         | 0.49%   |
| Huawei Technologies              | 4         | 0.49%   |
| DisplayLink                      | 4         | 0.49%   |
| TP-Link                          | 2         | 0.24%   |
| Cypress Semiconductor            | 2         | 0.24%   |
| Spreadtrum Communications        | 1         | 0.12%   |
| Motorola PCS                     | 1         | 0.12%   |
| LG Electronics                   | 1         | 0.12%   |
| HTC (High Tech Computer)         | 1         | 0.12%   |
| Hewlett-Packard                  | 1         | 0.12%   |
| Foxconn / Hon Hai                | 1         | 0.12%   |
| D-Link System                    | 1         | 0.12%   |
| Attansic Technology              | 1         | 0.12%   |
| 3Com                             | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 249       | 29.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 113       | 13.58%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 46        | 5.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 37        | 4.45%   |
| Intel Ethernet Connection (3) I218-LM                                          | 15        | 1.8%    |
| Intel 82577LM Gigabit Network Connection                                       | 14        | 1.68%   |
| Intel 82567LM Gigabit Network Connection                                       | 14        | 1.68%   |
| Intel Ethernet Connection I219-LM                                              | 13        | 1.56%   |
| Intel Ethernet Connection I218-LM                                              | 13        | 1.56%   |
| Intel Ethernet Connection (6) I219-V                                           | 12        | 1.44%   |
| Intel Ethernet Connection (4) I219-LM                                          | 12        | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 11        | 1.32%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 11        | 1.32%   |
| Intel Ethernet Connection I217-LM                                              | 9         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 8         | 0.96%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 8         | 0.96%   |
| Intel Ethernet Connection (6) I219-LM                                          | 8         | 0.96%   |
| Intel Ethernet Connection (4) I219-V                                           | 8         | 0.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 7         | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 7         | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 7         | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 6         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 0.72%   |
| Intel 82579V Gigabit Network Connection                                        | 6         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 0.6%    |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 5         | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 5         | 0.6%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 4         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 4         | 0.48%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 0.48%   |
| Intel Ethernet Connection I219-V                                               | 4         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4         | 0.48%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 0.48%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 4         | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 4         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.36%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.36%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 858       | 51.35%  |
| Ethernet | 782       | 46.8%   |
| Modem    | 30        | 1.8%    |
| Unknown  | 1         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 654       | 70.7%   |
| Ethernet | 271       | 29.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 720       | 81.73%  |
| 1     | 135       | 15.32%  |
| 0     | 17        | 1.93%   |
| 3     | 8         | 0.91%   |
| 5     | 1         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 817       | 92.11%  |
| Yes  | 70        | 7.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 279       | 43.94%  |
| Qualcomm Atheros Communications | 96        | 15.12%  |
| Realtek Semiconductor           | 49        | 7.72%   |
| Broadcom                        | 48        | 7.56%   |
| Lite-On Technology              | 33        | 5.2%    |
| IMC Networks                    | 22        | 3.46%   |
| Dell                            | 21        | 3.31%   |
| Foxconn / Hon Hai               | 19        | 2.99%   |
| Hewlett-Packard                 | 15        | 2.36%   |
| Apple                           | 12        | 1.89%   |
| Toshiba                         | 10        | 1.57%   |
| ASUSTek Computer                | 7         | 1.1%    |
| Cambridge Silicon Radio         | 6         | 0.94%   |
| Ralink                          | 5         | 0.79%   |
| Foxconn International           | 3         | 0.47%   |
| Alps Electric                   | 3         | 0.47%   |
| Unknown                         | 1         | 0.16%   |
| Smart Modular Technologies      | 1         | 0.16%   |
| Realtek                         | 1         | 0.16%   |
| Ralink Technology               | 1         | 0.16%   |
| Fujitsu                         | 1         | 0.16%   |
| Chicony Electronics             | 1         | 0.16%   |
| Askey Computer                  | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 136       | 21.35%  |
| Qualcomm Atheros  Bluetooth Device                  | 51        | 8.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 47        | 7.38%   |
| Intel AX201 Bluetooth                               | 27        | 4.24%   |
| Realtek Bluetooth Radio                             | 26        | 4.08%   |
| Intel AX200 Bluetooth                               | 21        | 3.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 17        | 2.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 15        | 2.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 14        | 2.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 2.04%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 1.88%   |
| Broadcom BCM2045B (BDC-2.1)                         | 12        | 1.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 1.73%   |
| IMC Networks Bluetooth Device                       | 11        | 1.73%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 1.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 1.41%   |
| Foxconn / Hon Hai Bluetooth Device                  | 9         | 1.41%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 1.26%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 1.26%   |
| Dell DW375 Bluetooth Module                         | 8         | 1.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 1.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 1.1%    |
| Qualcomm Atheros Bluetooth USB Host Controller      | 7         | 1.1%    |
| IMC Networks Bluetooth Radio                        | 6         | 0.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 0.94%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 6         | 0.94%   |
| Apple Bluetooth Host Controller                     | 6         | 0.94%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.78%   |
| Qualcomm Atheros Bluetooth                          | 5         | 0.78%   |
| Lite-On Bluetooth Device                            | 5         | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 0.78%   |
| Dell Wireless 365 Bluetooth                         | 5         | 0.78%   |
| Broadcom BCM2045 Bluetooth                          | 5         | 0.78%   |
| Toshiba Bluetooth Device                            | 4         | 0.63%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.63%   |
| Dell Wireless 355 Bluetooth                         | 4         | 0.63%   |
| Broadcom BCM2070 Bluetooth Device                   | 4         | 0.63%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.47%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 764       | 73.46%  |
| AMD                              | 113       | 10.87%  |
| Nvidia                           | 89        | 8.56%   |
| C-Media Electronics              | 12        | 1.15%   |
| Realtek Semiconductor            | 7         | 0.67%   |
| Logitech                         | 7         | 0.67%   |
| Lenovo                           | 7         | 0.67%   |
| Texas Instruments                | 5         | 0.48%   |
| Silicon Integrated Systems [SiS] | 4         | 0.38%   |
| GN Netcom                        | 3         | 0.29%   |
| Razer USA                        | 2         | 0.19%   |
| JMTek                            | 2         | 0.19%   |
| Hewlett-Packard                  | 2         | 0.19%   |
| Focusrite-Novation               | 2         | 0.19%   |
| XMOS                             | 1         | 0.1%    |
| VIA Technologies                 | 1         | 0.1%    |
| Veho                             | 1         | 0.1%    |
| SmartlinkTechnology              | 1         | 0.1%    |
| QinHeng Electronics              | 1         | 0.1%    |
| Native Instruments               | 1         | 0.1%    |
| Microsoft                        | 1         | 0.1%    |
| M-Audio                          | 1         | 0.1%    |
| Ketron                           | 1         | 0.1%    |
| Huawei Technologies              | 1         | 0.1%    |
| Guillemot                        | 1         | 0.1%    |
| ESS Technology                   | 1         | 0.1%    |
| Earth Computer Technologies      | 1         | 0.1%    |
| Dell                             | 1         | 0.1%    |
| Creative Technology              | 1         | 0.1%    |
| Conrad Electronic SE             | 1         | 0.1%    |
| Blue Microphones                 | 1         | 0.1%    |
| BEHRINGER International          | 1         | 0.1%    |
| ASUSTek Computer                 | 1         | 0.1%    |
| Arturia                          | 1         | 0.1%    |
| AKAI Professional M.I.           | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 148       | 12.15%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 90        | 7.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 71        | 5.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 53        | 4.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 47        | 3.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 43        | 3.53%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 41        | 3.37%   |
| Intel 8 Series HD Audio Controller                                                                | 41        | 3.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 34        | 2.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 34        | 2.79%   |
| Intel Broadwell-U Audio Controller                                                                | 34        | 2.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 31        | 2.55%   |
| AMD FCH Azalia Controller                                                                         | 31        | 2.55%   |
| AMD Ryzen HD Audio Controller                                                                     | 29        | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 28        | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 25        | 2.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 1.81%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 20        | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 18        | 1.48%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 1.4%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 16        | 1.31%   |
| Intel CM238 HD Audio Controller                                                                   | 16        | 1.31%   |
| AMD Kabini HDMI/DP Audio                                                                          | 15        | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 0.9%    |
| AMD Wrestler HDMI Audio                                                                           | 11        | 0.9%    |
| Nvidia High Definition Audio Controller                                                           | 10        | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 10        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 0.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 0.66%   |
| Realtek Semiconductor USB Audio                                                                   | 7         | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 0.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 0.49%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 6         | 0.49%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 6         | 0.49%   |
| AMD High Definition Audio Controller                                                              | 6         | 0.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.41%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 160       | 24.92%  |
| SK hynix            | 154       | 23.99%  |
| Micron Technology   | 73        | 11.37%  |
| Unknown             | 64        | 9.97%   |
| Kingston            | 56        | 8.72%   |
| Ramaxel Technology  | 20        | 3.12%   |
| Crucial             | 19        | 2.96%   |
| Elpida              | 18        | 2.8%    |
| A-DATA Technology   | 15        | 2.34%   |
| Smart               | 12        | 1.87%   |
| Nanya Technology    | 10        | 1.56%   |
| Teikon              | 6         | 0.93%   |
| Corsair             | 6         | 0.93%   |
| Unknown (ABCD)      | 4         | 0.62%   |
| Transcend           | 3         | 0.47%   |
| G.Skill             | 3         | 0.47%   |
| Apacer              | 3         | 0.47%   |
| 48spaces            | 3         | 0.47%   |
| Silicon Power       | 2         | 0.31%   |
| TEXTORM             | 1         | 0.16%   |
| Smart Brazil        | 1         | 0.16%   |
| Qimonda             | 1         | 0.16%   |
| PNY                 | 1         | 0.16%   |
| Patriot             | 1         | 0.16%   |
| HT Micron           | 1         | 0.16%   |
| GOODRAM             | 1         | 0.16%   |
| Avant               | 1         | 0.16%   |
| Atermiter           | 1         | 0.16%   |
| ASint Technology    | 1         | 0.16%   |
| AMD                 | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 1.45%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 10        | 1.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 10        | 1.45%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 1.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.3%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 6         | 0.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.87%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.87%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.87%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.87%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.87%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.72%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 5         | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 5         | 0.72%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 4         | 0.58%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 4         | 0.58%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 4         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.58%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 4         | 0.58%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s          | 4         | 0.58%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.58%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.58%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.58%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 4         | 0.58%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.58%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 3         | 0.43%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 3         | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.43%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.43%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.43%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 3         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 234       | 43.25%  |
| DDR4    | 193       | 35.67%  |
| DDR2    | 50        | 9.24%   |
| LPDDR4  | 18        | 3.33%   |
| SDRAM   | 17        | 3.14%   |
| LPDDR3  | 13        | 2.4%    |
| DDR     | 5         | 0.92%   |
| DRAM    | 4         | 0.74%   |
| Unknown | 4         | 0.74%   |
| LPDDR5  | 2         | 0.37%   |
| RAM     | 1         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 511       | 95.34%  |
| Row Of Chips | 19        | 3.54%   |
| Unknown      | 4         | 0.75%   |
| Chip         | 2         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 198       | 32.41%  |
| 4096  | 184       | 30.11%  |
| 2048  | 102       | 16.69%  |
| 16384 | 64        | 10.47%  |
| 1024  | 40        | 6.55%   |
| 512   | 10        | 1.64%   |
| 32768 | 9         | 1.47%   |
| 256   | 3         | 0.49%   |
| 128   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 162       | 27.18%  |
| 2667    | 128       | 21.48%  |
| 2400    | 43        | 7.21%   |
| 3200    | 37        | 6.21%   |
| 2133    | 35        | 5.87%   |
| 1334    | 30        | 5.03%   |
| Unknown | 26        | 4.36%   |
| 667     | 23        | 3.86%   |
| 1333    | 22        | 3.69%   |
| 800     | 13        | 2.18%   |
| 1067    | 12        | 2.01%   |
| 975     | 9         | 1.51%   |
| 8400    | 7         | 1.17%   |
| 533     | 7         | 1.17%   |
| 4199    | 6         | 1.01%   |
| 2048    | 6         | 1.01%   |
| 1867    | 5         | 0.84%   |
| 1066    | 5         | 0.84%   |
| 3266    | 4         | 0.67%   |
| 400     | 4         | 0.67%   |
| 6400    | 2         | 0.34%   |
| 4267    | 2         | 0.34%   |
| 1776    | 2         | 0.34%   |
| 333     | 2         | 0.34%   |
| 2267    | 1         | 0.17%   |
| 1866    | 1         | 0.17%   |
| 933     | 1         | 0.17%   |
| 266     | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 50%     |
| STMicroelectronics  | 1         | 12.5%   |
| Samsung Electronics | 1         | 12.5%   |
| Pantum              | 1         | 12.5%   |
| Kyocera             | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 11.11%  |
| Samsung CLX-3300 Series                                   | 1         | 11.11%  |
| Pantum P2500W series                                      | 1         | 11.11%  |
| Kyocera ECOSYS P2335d                                     | 1         | 11.11%  |
| HP OfficeJet 3830 series                                  | 1         | 11.11%  |
| HP LaserJet P1102                                         | 1         | 11.11%  |
| HP LaserJet 1020                                          | 1         | 11.11%  |
| HP EWS UPD                                                | 1         | 11.11%  |
| HP Deskjet 2540 series                                    | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 50%     |
| Canon          | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22 | 1         | 50%     |
| Canon CanoScan LiDE 110     | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 191       | 25%     |
| Realtek Semiconductor                  | 80        | 10.47%  |
| Microdia                               | 71        | 9.29%   |
| Sunplus Innovation Technology          | 69        | 9.03%   |
| Bison Electronics                      | 64        | 8.38%   |
| IMC Networks                           | 58        | 7.59%   |
| Suyin                                  | 33        | 4.32%   |
| Quanta                                 | 20        | 2.62%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 2.62%   |
| Silicon Motion                         | 19        | 2.49%   |
| Lite-On Technology                     | 19        | 2.49%   |
| Syntek                                 | 13        | 1.7%    |
| Ricoh                                  | 13        | 1.7%    |
| Lenovo                                 | 11        | 1.44%   |
| Alcor Micro                            | 11        | 1.44%   |
| Apple                                  | 10        | 1.31%   |
| Logitech                               | 9         | 1.18%   |
| ALi                                    | 7         | 0.92%   |
| Acer                                   | 7         | 0.92%   |
| Primax Electronics                     | 6         | 0.79%   |
| Samsung Electronics                    | 5         | 0.65%   |
| Z-Star Microelectronics                | 4         | 0.52%   |
| Tobii Technology AB                    | 2         | 0.26%   |
| OmniVision Technologies                | 2         | 0.26%   |
| Luxvisions Innotech Limited            | 2         | 0.26%   |
| Importek                               | 2         | 0.26%   |
| Genesys Logic                          | 2         | 0.26%   |
| GEMBIRD                                | 2         | 0.26%   |
| Xiongmai                               | 1         | 0.13%   |
| SunplusIT                              | 1         | 0.13%   |
| Sunplus Technology                     | 1         | 0.13%   |
| Spreadtrum Communications              | 1         | 0.13%   |
| Microsoft                              | 1         | 0.13%   |
| icSpring                               | 1         | 0.13%   |
| GenesysLogic Technology                | 1         | 0.13%   |
| Generalplus Technology                 | 1         | 0.13%   |
| Fitipower Integrated Technology        | 1         | 0.13%   |
| eMPIA Technology                       | 1         | 0.13%   |
| DigiTech                               | 1         | 0.13%   |
| Aveo Technology                        | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                  | 35        | 4.55%   |
| Chicony Integrated Camera                     | 26        | 3.38%   |
| Sunplus Integrated_Webcam_HD                  | 22        | 2.86%   |
| IMC Networks Integrated Camera                | 21        | 2.73%   |
| Chicony HD WebCam                             | 21        | 2.73%   |
| Microdia Integrated_Webcam_HD                 | 16        | 2.08%   |
| Bison Lenovo EasyCamera                       | 14        | 1.82%   |
| Sunplus HD WebCam                             | 11        | 1.43%   |
| Lite-On Integrated Camera                     | 11        | 1.43%   |
| IMC Networks USB2.0 HD UVC WebCam             | 11        | 1.43%   |
| Bison SunplusIT Integrated Camera             | 11        | 1.43%   |
| Microdia Integrated Webcam                    | 10        | 1.3%    |
| Chicony HP HD Camera                          | 9         | 1.17%   |
| Microdia Laptop_Integrated_Webcam_HD          | 8         | 1.04%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 8         | 1.04%   |
| Chicony EasyCamera                            | 8         | 1.04%   |
| Bison Integrated Camera                       | 8         | 1.04%   |
| Chicony Integrated Camera (1280x720@30)       | 7         | 0.91%   |
| Sunplus Asus Webcam                           | 6         | 0.78%   |
| Realtek USB2.0 HD UVC WebCam                  | 6         | 0.78%   |
| Realtek Integrated Webcam                     | 6         | 0.78%   |
| Quanta HP HD Camera                           | 6         | 0.78%   |
| Lenovo Integrated Webcam [R5U877]             | 6         | 0.78%   |
| Chicony USB 2.0 Camera                        | 6         | 0.78%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 5         | 0.65%   |
| Sunplus Laptop Integrated Webcam HD           | 5         | 0.65%   |
| Samsung Galaxy series, misc. (MTP mode)       | 5         | 0.65%   |
| Realtek USB2.0 VGA UVC WebCam                 | 5         | 0.65%   |
| Realtek HD WebCam                             | 5         | 0.65%   |
| Lite-On HP HD Camera                          | 5         | 0.65%   |
| Chicony USB2.0 HD UVC WebCam                  | 5         | 0.65%   |
| Chicony USB2.0 Camera                         | 5         | 0.65%   |
| Chicony HP TrueVision HD Camera               | 5         | 0.65%   |
| Chicony HP Truevision HD                      | 5         | 0.65%   |
| Chicony HP HD Webcam                          | 5         | 0.65%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 5         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 5         | 0.65%   |
| Bison ThinkPad Integrated Camera              | 5         | 0.65%   |
| Bison SunplusIT INC. Integrated Camera        | 5         | 0.65%   |
| Bison EasyCamera                              | 5         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 59        | 35.54%  |
| Synaptics                  | 49        | 29.52%  |
| AuthenTec                  | 19        | 11.45%  |
| Upek                       | 12        | 7.23%   |
| Shenzhen Goodix Technology | 10        | 6.02%   |
| Elan Microelectronics      | 10        | 6.02%   |
| LighTuning Technology      | 4         | 2.41%   |
| STMicroelectronics         | 1         | 0.6%    |
| Samsung Electronics        | 1         | 0.6%    |
| Microsoft                  | 1         | 0.6%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 12.65%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 7.83%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 7.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 6.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 6.63%   |
| AuthenTec AES2810                                                          | 11        | 6.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 5.42%   |
| Elan ELAN:Fingerprint                                                      | 7         | 4.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 3.61%   |
| Synaptics  WBDI                                                            | 5         | 3.01%   |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 3.01%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.41%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 2.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 2.41%   |
| Validity Sensors VFS491                                                    | 3         | 1.81%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.81%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.81%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.81%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.2%    |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.2%    |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 1.2%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 1.2%    |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.2%    |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.6%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.6%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.6%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.6%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.6%    |
| Synaptics WBDI Device                                                      | 1         | 0.6%    |
| Synaptics TouchPad                                                         | 1         | 0.6%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.6%    |
| Samsung Fingerprint Device                                                 | 1         | 0.6%    |
| Microsoft Fingerprint Reader                                               | 1         | 0.6%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.6%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.6%    |
| AuthenTec AES1600                                                          | 1         | 0.6%    |
| Unknown                                                                    | 1         | 0.6%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 44        | 51.16%  |
| Alcor Micro           | 23        | 26.74%  |
| O2 Micro              | 6         | 6.98%   |
| Lenovo                | 6         | 6.98%   |
| Upek                  | 5         | 5.81%   |
| Gemalto (was Gemplus) | 1         | 1.16%   |
| Clay Logic            | 1         | 1.16%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 26.74%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 19.77%  |
| Broadcom 5880                                                                | 12        | 13.95%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 10.47%  |
| Lenovo Integrated Smart Card Reader                                          | 6         | 6.98%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 5.81%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 5.81%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 4         | 4.65%   |
| Broadcom 58200                                                               | 2         | 2.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.16%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.16%   |
| Clay Logic Nitrokey Start                                                    | 1         | 1.16%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 493       | 54.84%  |
| 1     | 298       | 33.15%  |
| 2     | 90        | 10.01%  |
| 3     | 14        | 1.56%   |
| 4     | 4         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 165       | 31.79%  |
| Graphics card            | 131       | 25.24%  |
| Chipcard                 | 80        | 15.41%  |
| Net/wireless             | 49        | 9.44%   |
| Multimedia controller    | 20        | 3.85%   |
| Bluetooth                | 20        | 3.85%   |
| Storage                  | 14        | 2.7%    |
| Camera                   | 13        | 2.5%    |
| Card reader              | 9         | 1.73%   |
| Sound                    | 5         | 0.96%   |
| Net/ethernet             | 4         | 0.77%   |
| Communication controller | 4         | 0.77%   |
| Modem                    | 2         | 0.39%   |
| Network                  | 1         | 0.19%   |
| Flash memory             | 1         | 0.19%   |
| Firewire controller      | 1         | 0.19%   |

