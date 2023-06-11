Linux in Dominican Republic - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Dominican Republic.

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

Total: 152

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6540              | [85520c9a0b](https://linux-hardware.org/?probe=85520c9a0b) | Jun 08, 2023 |
| Dell          | Latitude E6540              | [30f20f78ac](https://linux-hardware.org/?probe=30f20f78ac) | Jun 08, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [f9103674dc](https://linux-hardware.org/?probe=f9103674dc) | May 22, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [19416d3973](https://linux-hardware.org/?probe=19416d3973) | May 21, 2023 |
| Dell          | Inspiron 5555               | [378acd7874](https://linux-hardware.org/?probe=378acd7874) | May 09, 2023 |
| Dell          | Inspiron 5555               | [534af3636c](https://linux-hardware.org/?probe=534af3636c) | May 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [dd238f7e60](https://linux-hardware.org/?probe=dd238f7e60) | May 04, 2023 |
| HP            | EliteBook 8460p             | [ea7f9b7eef](https://linux-hardware.org/?probe=ea7f9b7eef) | Apr 20, 2023 |
| HP            | EliteBook 8460p             | [d3526466e8](https://linux-hardware.org/?probe=d3526466e8) | Apr 20, 2023 |
| HP            | Laptop 14-dk1xxx            | [b7e04c4c41](https://linux-hardware.org/?probe=b7e04c4c41) | Apr 12, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [4b7801e829](https://linux-hardware.org/?probe=4b7801e829) | Mar 22, 2023 |
| Unknown       | Unknown                     | [7a44108d05](https://linux-hardware.org/?probe=7a44108d05) | Mar 16, 2023 |
| VTEX          | NOTEBOOK                    | [0b91c54846](https://linux-hardware.org/?probe=0b91c54846) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | [4687219ca3](https://linux-hardware.org/?probe=4687219ca3) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | [687328ccb0](https://linux-hardware.org/?probe=687328ccb0) | Mar 06, 2023 |
| VTEX          | NOTEBOOK                    | [b12a53ec1e](https://linux-hardware.org/?probe=b12a53ec1e) | Mar 06, 2023 |
| HP            | ProBook 4520s               | [8192287499](https://linux-hardware.org/?probe=8192287499) | Feb 19, 2023 |
| Dell          | Inspiron 5520               | [6de5bc549f](https://linux-hardware.org/?probe=6de5bc549f) | Jan 29, 2023 |
| Google        | Kip                         | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| Lenovo        | ThinkPad T420s 41732BU      | [fb42067a32](https://linux-hardware.org/?probe=fb42067a32) | Jan 20, 2023 |
| Google        | Kip                         | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | 255 G6 Notebook PC          | [4d2e9f3ee4](https://linux-hardware.org/?probe=4d2e9f3ee4) | Jan 16, 2023 |
| Dell          | XPS M1330                   | [e3d66114f6](https://linux-hardware.org/?probe=e3d66114f6) | Jan 10, 2023 |
| Dell          | Latitude 5420               | [9fd9875465](https://linux-hardware.org/?probe=9fd9875465) | Dec 23, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T420s 41732BU      | [ac7791c167](https://linux-hardware.org/?probe=ac7791c167) | Nov 24, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [1a1f5f8d90](https://linux-hardware.org/?probe=1a1f5f8d90) | Nov 22, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [b2772ed1b3](https://linux-hardware.org/?probe=b2772ed1b3) | Nov 22, 2022 |
| Lenovo        | ThinkPad T490 20N3S7BC02    | [76a37f4e66](https://linux-hardware.org/?probe=76a37f4e66) | Nov 19, 2022 |
| Dell          | Latitude 5590               | [bbb332cf90](https://linux-hardware.org/?probe=bbb332cf90) | Nov 11, 2022 |
| Eluktronic... | P670RE3                     | [d96ecdf7ab](https://linux-hardware.org/?probe=d96ecdf7ab) | Nov 08, 2022 |
| MSI           | GE62 6QC                    | [92ac4fbaa6](https://linux-hardware.org/?probe=92ac4fbaa6) | Oct 19, 2022 |
| EVOO          | EV-C-116-7                  | [ff4216edcd](https://linux-hardware.org/?probe=ff4216edcd) | Oct 18, 2022 |
| Dell          | Inspiron 5570               | [cab829a52b](https://linux-hardware.org/?probe=cab829a52b) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [923a579655](https://linux-hardware.org/?probe=923a579655) | Oct 03, 2022 |
| Dell          | Latitude 2110               | [3fbbac2c8a](https://linux-hardware.org/?probe=3fbbac2c8a) | Oct 03, 2022 |
| Dell          | Latitude E6540              | [08bd609dbe](https://linux-hardware.org/?probe=08bd609dbe) | Sep 20, 2022 |
| Dell          | Latitude E6420              | [3ea84baba3](https://linux-hardware.org/?probe=3ea84baba3) | Sep 09, 2022 |
| Dell          | Latitude E6420              | [78fd24b713](https://linux-hardware.org/?probe=78fd24b713) | Sep 09, 2022 |
| Acer          | Aspire A515-45              | [9e48793165](https://linux-hardware.org/?probe=9e48793165) | Aug 18, 2022 |
| Acer          | Aspire A515-45              | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| Dell          | Latitude E5440              | [c8e68471c1](https://linux-hardware.org/?probe=c8e68471c1) | Jul 16, 2022 |
| Acer          | Aspire E5-571               | [9cd0caeff2](https://linux-hardware.org/?probe=9cd0caeff2) | Jul 14, 2022 |
| ECS           | ClassMate                   | [c86fa72fe1](https://linux-hardware.org/?probe=c86fa72fe1) | Jun 13, 2022 |
| Lenovo        | G505s 20255                 | [578aee86ed](https://linux-hardware.org/?probe=578aee86ed) | May 27, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [c72447a3ea](https://linux-hardware.org/?probe=c72447a3ea) | May 03, 2022 |
| TODOS INDU... | Easytouch_2022_V1           | [efc26220c4](https://linux-hardware.org/?probe=efc26220c4) | May 01, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [454226474b](https://linux-hardware.org/?probe=454226474b) | Apr 29, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | [9d5011b41d](https://linux-hardware.org/?probe=9d5011b41d) | Mar 23, 2022 |
| ASUSTek       | K53E                        | [3a0af085ae](https://linux-hardware.org/?probe=3a0af085ae) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [507f27294e](https://linux-hardware.org/?probe=507f27294e) | Feb 15, 2022 |
| EVOO          | EV-C-116-7                  | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [563f0e150e](https://linux-hardware.org/?probe=563f0e150e) | Dec 31, 2021 |
| Apple         | MacBookPro8,1               | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| Apple         | MacBookPro8,1               | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire 5733Z                | [ea7511ce8d](https://linux-hardware.org/?probe=ea7511ce8d) | Dec 24, 2021 |
| Apple         | MacBookPro8,1               | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9b89720cb4](https://linux-hardware.org/?probe=9b89720cb4) | Dec 14, 2021 |
| Lenovo        | G505s 20255                 | [b32fd5f07f](https://linux-hardware.org/?probe=b32fd5f07f) | Dec 07, 2021 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [d1843d03ba](https://linux-hardware.org/?probe=d1843d03ba) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | [a77255409f](https://linux-hardware.org/?probe=a77255409f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | [ef02c2fb6c](https://linux-hardware.org/?probe=ef02c2fb6c) | Dec 02, 2021 |
| Lenovo        | G505s 20255                 | [8d3228452b](https://linux-hardware.org/?probe=8d3228452b) | Nov 20, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| Dell          | Latitude E6410              | [bd65cdda08](https://linux-hardware.org/?probe=bd65cdda08) | Oct 08, 2021 |
| Apple         | MacBook2,1                  | [7b2dcf44d9](https://linux-hardware.org/?probe=7b2dcf44d9) | Sep 08, 2021 |
| HP            | Pavilion dv6                | [5038083b91](https://linux-hardware.org/?probe=5038083b91) | Sep 07, 2021 |
| Apple         | MacBook2,1                  | [e402a0b407](https://linux-hardware.org/?probe=e402a0b407) | Aug 31, 2021 |
| Dell          | Inspiron 5521               | [24bfc2b04a](https://linux-hardware.org/?probe=24bfc2b04a) | Aug 26, 2021 |
| Dell          | Inspiron 5521               | [8242b46551](https://linux-hardware.org/?probe=8242b46551) | Jul 29, 2021 |
| Google        | Winky                       | [696230b066](https://linux-hardware.org/?probe=696230b066) | Jul 14, 2021 |
| Google        | Winky                       | [6048ac2ff9](https://linux-hardware.org/?probe=6048ac2ff9) | Jul 14, 2021 |
| Acer          | Aspire 1810TZ               | [3ed828bab0](https://linux-hardware.org/?probe=3ed828bab0) | Jul 11, 2021 |
| Acer          | Aspire 1810TZ               | [9b650cfab3](https://linux-hardware.org/?probe=9b650cfab3) | Jul 11, 2021 |
| Dell          | Latitude E6420              | [fe42f53d85](https://linux-hardware.org/?probe=fe42f53d85) | Jul 11, 2021 |
| Dell          | Inspiron N5050              | [772842d291](https://linux-hardware.org/?probe=772842d291) | Jul 06, 2021 |
| HP            | EliteBook 8460p             | [cc6035ae99](https://linux-hardware.org/?probe=cc6035ae99) | Jun 28, 2021 |
| SAELITE       | ES1AU11                     | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| SAELITE       | ES1AU11                     | [25dc027ef1](https://linux-hardware.org/?probe=25dc027ef1) | Jun 26, 2021 |
| Dell          | Latitude E6530              | [fda4879b12](https://linux-hardware.org/?probe=fda4879b12) | Jun 19, 2021 |
| Dell          | Latitude E6530              | [40566262f5](https://linux-hardware.org/?probe=40566262f5) | Jun 11, 2021 |
| Dell          | Latitude E6430              | [9ec2685f9d](https://linux-hardware.org/?probe=9ec2685f9d) | Jun 04, 2021 |
| Dell          | Latitude E6430              | [6098210314](https://linux-hardware.org/?probe=6098210314) | Jun 04, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [5343885c32](https://linux-hardware.org/?probe=5343885c32) | May 17, 2021 |
| Dell          | Inspiron 3541               | [2170036527](https://linux-hardware.org/?probe=2170036527) | May 17, 2021 |
| Dell          | Inspiron 5570               | [d310246b09](https://linux-hardware.org/?probe=d310246b09) | Apr 30, 2021 |
| Dell          | Latitude D830               | [f6f0884fca](https://linux-hardware.org/?probe=f6f0884fca) | Apr 28, 2021 |
| Dell          | Latitude E6540              | [522d36a07e](https://linux-hardware.org/?probe=522d36a07e) | Apr 21, 2021 |
| Dell          | Latitude E6540              | [3c76496221](https://linux-hardware.org/?probe=3c76496221) | Apr 21, 2021 |
| Dell          | Inspiron 3521               | [96d33743db](https://linux-hardware.org/?probe=96d33743db) | Jan 24, 2021 |
| Lenovo        | ThinkPad E470 20H1006DUS    | [3c51b58a24](https://linux-hardware.org/?probe=3c51b58a24) | Dec 14, 2020 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [f18b7b439b](https://linux-hardware.org/?probe=f18b7b439b) | Dec 05, 2020 |
| Fujitsu       | LIFEBOOK AH562              | [68c670f9e0](https://linux-hardware.org/?probe=68c670f9e0) | Dec 01, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | [012580c2a7](https://linux-hardware.org/?probe=012580c2a7) | Nov 10, 2020 |
| HP            | Notebook                    | [5176e73c5a](https://linux-hardware.org/?probe=5176e73c5a) | Oct 27, 2020 |
| ASUSTek       | X553MA                      | [d6729d6c6a](https://linux-hardware.org/?probe=d6729d6c6a) | Oct 17, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | [907bc464e9](https://linux-hardware.org/?probe=907bc464e9) | Oct 13, 2020 |
| HP            | EliteBook 8540w             | [03c52e4d49](https://linux-hardware.org/?probe=03c52e4d49) | Oct 10, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Dell          | Latitude E5530 non-vPro     | [fd73b699f6](https://linux-hardware.org/?probe=fd73b699f6) | Oct 05, 2020 |
| Dell          | Latitude D620               | [3832d0c33e](https://linux-hardware.org/?probe=3832d0c33e) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| HP            | Laptop 15-bw0xx             | [80611690cf](https://linux-hardware.org/?probe=80611690cf) | Sep 13, 2020 |
| Dell          | Latitude D620               | [d14cb277b7](https://linux-hardware.org/?probe=d14cb277b7) | Sep 12, 2020 |
| HP            | ProBook 6470b               | [c622e7298d](https://linux-hardware.org/?probe=c622e7298d) | Sep 07, 2020 |
| Dell          | Vostro 5471                 | [6d24c75bcf](https://linux-hardware.org/?probe=6d24c75bcf) | Sep 03, 2020 |
| Nuvision      | L1W6_I1101_G Reserved       | [b3e73aa9ba](https://linux-hardware.org/?probe=b3e73aa9ba) | Aug 29, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [d7d672869f](https://linux-hardware.org/?probe=d7d672869f) | Aug 16, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8eb28a49c4](https://linux-hardware.org/?probe=8eb28a49c4) | Aug 03, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [fcbd102a50](https://linux-hardware.org/?probe=fcbd102a50) | Jul 30, 2020 |
| Dell          | Vostro A860                 | [16ded4e283](https://linux-hardware.org/?probe=16ded4e283) | Jun 28, 2020 |
| Dell          | Inspiron 1545               | [093c4d226c](https://linux-hardware.org/?probe=093c4d226c) | Jun 28, 2020 |
| HP            | 250 G3                      | [1862b881c0](https://linux-hardware.org/?probe=1862b881c0) | Jun 23, 2020 |
| Acer          | Aspire one 1-431            | [80f65d1ab4](https://linux-hardware.org/?probe=80f65d1ab4) | Jun 23, 2020 |
| Acer          | Aspire one 1-431            | [5994ea3a38](https://linux-hardware.org/?probe=5994ea3a38) | Jun 09, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [4003a55819](https://linux-hardware.org/?probe=4003a55819) | Jun 03, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [131d3a17f3](https://linux-hardware.org/?probe=131d3a17f3) | May 30, 2020 |
| Dell          | Vostro A860                 | [35d08abb65](https://linux-hardware.org/?probe=35d08abb65) | May 20, 2020 |
| Dell          | Latitude E6410              | [4e98eb67c5](https://linux-hardware.org/?probe=4e98eb67c5) | May 19, 2020 |
| Dell          | Latitude 3340               | [a8795064a1](https://linux-hardware.org/?probe=a8795064a1) | May 18, 2020 |
| Dell          | Latitude 3340               | [a07d882043](https://linux-hardware.org/?probe=a07d882043) | May 18, 2020 |
| Dell          | Latitude E6430              | [4316261d97](https://linux-hardware.org/?probe=4316261d97) | May 15, 2020 |
| Dell          | Latitude E6430              | [eef205a77d](https://linux-hardware.org/?probe=eef205a77d) | May 14, 2020 |
| HP            | G60                         | [90ec25f151](https://linux-hardware.org/?probe=90ec25f151) | May 13, 2020 |
| HP            | G60                         | [0b84216baf](https://linux-hardware.org/?probe=0b84216baf) | May 13, 2020 |
| Dell          | Inspiron 3521               | [1b33a3d155](https://linux-hardware.org/?probe=1b33a3d155) | May 03, 2020 |
| Dell          | Latitude E6430              | [5a74b9f950](https://linux-hardware.org/?probe=5a74b9f950) | May 03, 2020 |
| Dell          | Latitude E6430              | [31e36437f4](https://linux-hardware.org/?probe=31e36437f4) | May 03, 2020 |
| Dell          | Latitude E6410              | [125cc5d7fd](https://linux-hardware.org/?probe=125cc5d7fd) | Apr 26, 2020 |
| Dell          | Latitude 3330               | [4033fca5eb](https://linux-hardware.org/?probe=4033fca5eb) | Mar 22, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | [185bf79f49](https://linux-hardware.org/?probe=185bf79f49) | Feb 08, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | [cb7950841c](https://linux-hardware.org/?probe=cb7950841c) | Feb 07, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | [3212549df1](https://linux-hardware.org/?probe=3212549df1) | Feb 05, 2020 |
| Lenovo        | Z50-75 80EC                 | [661a8243a3](https://linux-hardware.org/?probe=661a8243a3) | Feb 01, 2020 |
| Lenovo        | Z50-75 80EC                 | [ee353d9346](https://linux-hardware.org/?probe=ee353d9346) | Feb 01, 2020 |
| Apple         | MacBookPro8,1               | [51c3c0bb31](https://linux-hardware.org/?probe=51c3c0bb31) | Jan 07, 2020 |
| Apple         | MacBookPro8,1               | [4df330ed80](https://linux-hardware.org/?probe=4df330ed80) | Jan 07, 2020 |
| Apple         | MacBookPro5,5               | [e4a03527b5](https://linux-hardware.org/?probe=e4a03527b5) | Dec 11, 2019 |
| Toshiba       | Satellite C55-A             | [a760ea9cb2](https://linux-hardware.org/?probe=a760ea9cb2) | Nov 14, 2019 |
| Toshiba       | Satellite C55-A             | [b2477d7154](https://linux-hardware.org/?probe=b2477d7154) | Nov 07, 2019 |
| Apple         | MacBookPro5,5               | [cb7b5a4d2e](https://linux-hardware.org/?probe=cb7b5a4d2e) | Oct 13, 2019 |
| Dell          | Latitude E6430              | [49d71b26e7](https://linux-hardware.org/?probe=49d71b26e7) | Oct 08, 2019 |
| Dell          | Latitude E6430              | [b3ef7b4357](https://linux-hardware.org/?probe=b3ef7b4357) | Oct 06, 2019 |
| Apple         | MacBookPro5,5               | [9a7d44bf28](https://linux-hardware.org/?probe=9a7d44bf28) | Aug 15, 2019 |
| HP            | Pavilion ze2000 (EC201UA... | [572baa05f4](https://linux-hardware.org/?probe=572baa05f4) | Jun 15, 2019 |
| ASUSTek       | T100TA                      | [412e4da0ce](https://linux-hardware.org/?probe=412e4da0ce) | May 21, 2019 |
| Lenovo        | G40-70 20369                | [1f456620db](https://linux-hardware.org/?probe=1f456620db) | May 05, 2019 |
| HP            | Laptop 15-bw0xx             | [0b9c00412b](https://linux-hardware.org/?probe=0b9c00412b) | Dec 14, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 16        | 16%     |
| Ubuntu 18.04        | 7         | 7%      |
| Ubuntu 22.04        | 5         | 5%      |
| OpenMandriva 4.3    | 4         | 4%      |
| Fedora 36           | 4         | 4%      |
| Fedora 37           | 3         | 3%      |
| Debian 11           | 3         | 3%      |
| Zorin 16            | 2         | 2%      |
| Ubuntu 21.10        | 2         | 2%      |
| Pop!_OS 20.10       | 2         | 2%      |
| OpenMandriva 4.2    | 2         | 2%      |
| Manjaro             | 2         | 2%      |
| Linux Mint 20.3     | 2         | 2%      |
| Linux Mint 20.1     | 2         | 2%      |
| ArcoLinux Rolling   | 2         | 2%      |
| Arch Rolling        | 2         | 2%      |
| Xubuntu 19.10       | 1         | 1%      |
| Xubuntu 18.04       | 1         | 1%      |
| Void Linux Rolling  | 1         | 1%      |
| Ubuntu Budgie 22.04 | 1         | 1%      |
| Ubuntu Budgie 21.10 | 1         | 1%      |
| Ubuntu Budgie 20.04 | 1         | 1%      |
| Ubuntu 22.10        | 1         | 1%      |
| Ubuntu 21.04        | 1         | 1%      |
| Ubuntu 19.04        | 1         | 1%      |
| Solus 4.1           | 1         | 1%      |
| Pop!_OS 21.04       | 1         | 1%      |
| Pop!_OS 20.04       | 1         | 1%      |
| OpenMandriva 23.01  | 1         | 1%      |
| MX 21               | 1         | 1%      |
| Manjaro 22.0.0      | 1         | 1%      |
| Manjaro 21.1.2      | 1         | 1%      |
| Manjaro 20.1        | 1         | 1%      |
| Lubuntu 21.04       | 1         | 1%      |
| LMDE 4              | 1         | 1%      |
| Linux Mint 21.1     | 1         | 1%      |
| Linux Mint 21       | 1         | 1%      |
| Linux Mint 20.2     | 1         | 1%      |
| Linux Mint 20       | 1         | 1%      |
| Linux Mint 19.3     | 1         | 1%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 32        | 32.32%  |
| Fedora        | 13        | 13.13%  |
| Linux Mint    | 9         | 9.09%   |
| OpenMandriva  | 7         | 7.07%   |
| Manjaro       | 5         | 5.05%   |
| Pop!_OS       | 4         | 4.04%   |
| Debian        | 4         | 4.04%   |
| Ubuntu Budgie | 3         | 3.03%   |
| Arch          | 3         | 3.03%   |
| Zorin         | 2         | 2.02%   |
| Xubuntu       | 2         | 2.02%   |
| KDE neon      | 2         | 2.02%   |
| Clear Linux   | 2         | 2.02%   |
| ArcoLinux     | 2         | 2.02%   |
| Void Linux    | 1         | 1.01%   |
| Solus         | 1         | 1.01%   |
| MX            | 1         | 1.01%   |
| Lubuntu       | 1         | 1.01%   |
| LMDE          | 1         | 1.01%   |
| Kubuntu       | 1         | 1.01%   |
| Endless       | 1         | 1.01%   |
| Elementary    | 1         | 1.01%   |
| Archcraft     | 1         | 1.01%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-48-generic        | 4         | 3.57%   |
| 5.16.7-desktop-1omv4003 | 4         | 3.57%   |
| 5.4.0-42-generic        | 3         | 2.68%   |
| 5.13.0-22-generic       | 3         | 2.68%   |
| 5.4.0-77-generic        | 2         | 1.79%   |
| 5.4.0-52-generic        | 2         | 1.79%   |
| 5.4.0-33-generic        | 2         | 1.79%   |
| 5.3.0-51-generic        | 2         | 1.79%   |
| 5.15.0-58-generic       | 2         | 1.79%   |
| 5.15.0-53-generic       | 2         | 1.79%   |
| 5.15.0-41-generic       | 2         | 1.79%   |
| 6.2.7-arch1-1           | 1         | 0.89%   |
| 6.2.14-300.fc38.x86_64  | 1         | 0.89%   |
| 6.2.12-1-MANJARO        | 1         | 0.89%   |
| 6.1.5-200.fc37.x86_64   | 1         | 0.89%   |
| 6.1.1-desktop-1omv2290  | 1         | 0.89%   |
| 6.0.6-300.fc37.x86_64   | 1         | 0.89%   |
| 6.0.14-300.fc37.x86_64  | 1         | 0.89%   |
| 5.9.12-xanmod1          | 1         | 0.89%   |
| 5.9.11-arch2-1          | 1         | 0.89%   |
| 5.9.1-arch1-1           | 1         | 0.89%   |
| 5.8.8-arch1-1           | 1         | 0.89%   |
| 5.8.15-301.fc33.x86_64  | 1         | 0.89%   |
| 5.8.12_1                | 1         | 0.89%   |
| 5.8.0-38-generic        | 1         | 0.89%   |
| 5.7.10-201.fc32.x86_64  | 1         | 0.89%   |
| 5.6.19-158.current      | 1         | 0.89%   |
| 5.4.60-2-MANJARO        | 1         | 0.89%   |
| 5.4.15-200.fc31.x86_64  | 1         | 0.89%   |
| 5.4.0-7642-generic      | 1         | 0.89%   |
| 5.4.0-74-generic        | 1         | 0.89%   |
| 5.4.0-72-generic        | 1         | 0.89%   |
| 5.4.0-39-generic        | 1         | 0.89%   |
| 5.4.0-29-generic        | 1         | 0.89%   |
| 5.4.0-28-generic        | 1         | 0.89%   |
| 5.4.0-26-generic        | 1         | 0.89%   |
| 5.4.0-109-generic       | 1         | 0.89%   |
| 5.4.0-105-generic       | 1         | 0.89%   |
| 5.3.0-61-generic        | 1         | 0.89%   |
| 5.3.0-46-generic        | 1         | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 20.19%  |
| 5.15.0  | 10        | 9.62%   |
| 5.13.0  | 8         | 7.69%   |
| 5.3.0   | 6         | 5.77%   |
| 5.11.0  | 6         | 5.77%   |
| 5.16.7  | 4         | 3.85%   |
| 5.10.0  | 4         | 3.85%   |
| 5.0.0   | 3         | 2.88%   |
| 5.19.0  | 2         | 1.92%   |
| 4.19.0  | 2         | 1.92%   |
| 6.2.7   | 1         | 0.96%   |
| 6.2.14  | 1         | 0.96%   |
| 6.2.12  | 1         | 0.96%   |
| 6.1.5   | 1         | 0.96%   |
| 6.1.1   | 1         | 0.96%   |
| 6.0.6   | 1         | 0.96%   |
| 6.0.14  | 1         | 0.96%   |
| 5.9.12  | 1         | 0.96%   |
| 5.9.11  | 1         | 0.96%   |
| 5.9.1   | 1         | 0.96%   |
| 5.8.8   | 1         | 0.96%   |
| 5.8.15  | 1         | 0.96%   |
| 5.8.12  | 1         | 0.96%   |
| 5.8.0   | 1         | 0.96%   |
| 5.7.10  | 1         | 0.96%   |
| 5.6.19  | 1         | 0.96%   |
| 5.4.60  | 1         | 0.96%   |
| 5.4.15  | 1         | 0.96%   |
| 5.19.7  | 1         | 0.96%   |
| 5.19.14 | 1         | 0.96%   |
| 5.19.12 | 1         | 0.96%   |
| 5.18.17 | 1         | 0.96%   |
| 5.18.13 | 1         | 0.96%   |
| 5.18.11 | 1         | 0.96%   |
| 5.17.4  | 1         | 0.96%   |
| 5.15.94 | 1         | 0.96%   |
| 5.15.76 | 1         | 0.96%   |
| 5.13.13 | 1         | 0.96%   |
| 5.12.9  | 1         | 0.96%   |
| 5.12.14 | 1         | 0.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 22.33%  |
| 5.15    | 12        | 11.65%  |
| 5.13    | 9         | 8.74%   |
| 5.11    | 8         | 7.77%   |
| 5.3     | 6         | 5.83%   |
| 5.10    | 6         | 5.83%   |
| 5.19    | 5         | 4.85%   |
| 5.8     | 4         | 3.88%   |
| 5.16    | 4         | 3.88%   |
| 5.0     | 4         | 3.88%   |
| 6.2     | 3         | 2.91%   |
| 5.9     | 3         | 2.91%   |
| 4.19    | 3         | 2.91%   |
| 6.1     | 2         | 1.94%   |
| 6.0     | 2         | 1.94%   |
| 5.18    | 2         | 1.94%   |
| 5.12    | 2         | 1.94%   |
| 5.7     | 1         | 0.97%   |
| 5.6     | 1         | 0.97%   |
| 5.17    | 1         | 0.97%   |
| 4.18    | 1         | 0.97%   |
| 4.15    | 1         | 0.97%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 95        | 96.94%  |
| i686   | 3         | 3.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 45        | 45%     |
| KDE5       | 18        | 18%     |
| XFCE       | 9         | 9%      |
| X-Cinnamon | 8         | 8%      |
| Unknown    | 8         | 8%      |
| Budgie     | 4         | 4%      |
| KDE        | 3         | 3%      |
| sway       | 1         | 1%      |
| MATE       | 1         | 1%      |
| LXQt       | 1         | 1%      |
| LXDE       | 1         | 1%      |
| DWM        | 1         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 78        | 78%     |
| Wayland | 18        | 18%     |
| Unknown | 4         | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 51.52%  |
| SDDM    | 14        | 14.14%  |
| GDM     | 11        | 11.11%  |
| GDM3    | 10        | 10.1%   |
| LightDM | 9         | 9.09%   |
| TDM     | 4         | 4.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 57        | 56.44%  |
| es_DO   | 25        | 24.75%  |
| Unknown | 7         | 6.93%   |
| es_ES   | 4         | 3.96%   |
| es_MX   | 3         | 2.97%   |
| en_CA   | 2         | 1.98%   |
| ru_RU   | 1         | 0.99%   |
| fr_FR   | 1         | 0.99%   |
| C       | 1         | 0.99%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 51        | 52.04%  |
| EFI  | 47        | 47.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 75        | 76.53%  |
| Btrfs   | 12        | 12.24%  |
| Overlay | 7         | 7.14%   |
| Xfs     | 2         | 2.04%   |
| F2fs    | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 52        | 52.53%  |
| GPT     | 39        | 39.39%  |
| MBR     | 8         | 8.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 83.84%  |
| Yes       | 16        | 16.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 71        | 72.45%  |
| Yes       | 27        | 27.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 31        | 31.63%  |
| Lenovo              | 17        | 17.35%  |
| Hewlett-Packard     | 17        | 17.35%  |
| ASUSTek Computer    | 7         | 7.14%   |
| Acer                | 5         | 5.1%    |
| Apple               | 4         | 4.08%   |
| Samsung Electronics | 2         | 2.04%   |
| MSI                 | 2         | 2.04%   |
| Google              | 2         | 2.04%   |
| EVOO                | 2         | 2.04%   |
| VTEX                | 1         | 1.02%   |
| Toshiba             | 1         | 1.02%   |
| TODOS INDUSTRIAL    | 1         | 1.02%   |
| SAELITE             | 1         | 1.02%   |
| Nuvision            | 1         | 1.02%   |
| Fujitsu             | 1         | 1.02%   |
| Eluktronics         | 1         | 1.02%   |
| ECS                 | 1         | 1.02%   |
| Unknown             | 1         | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Lenovo IdeaPad 330S-15IKB 81F5                    | 2         | 2.04%   |
| HP EliteBook 8460p                                | 2         | 2.04%   |
| EVOO EV-C-116-7                                   | 2         | 2.04%   |
| Dell Latitude E6540                               | 2         | 2.04%   |
| Dell Latitude E6430                               | 2         | 2.04%   |
| Dell Latitude E6420                               | 2         | 2.04%   |
| Dell Latitude E6410                               | 2         | 2.04%   |
| Dell Inspiron 5570                                | 2         | 2.04%   |
| Dell Inspiron 5555                                | 2         | 2.04%   |
| Apple MacBookPro8,1                               | 2         | 2.04%   |
| VTEX NOTEBOOK                                     | 1         | 1.02%   |
| Toshiba Satellite C55-A                           | 1         | 1.02%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 1.02%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 1.02%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 1.02%   |
| SAELITE ES1AU11                                   | 1         | 1.02%   |
| Nuvision NES11                                    | 1         | 1.02%   |
| MSI GE62 6QC                                      | 1         | 1.02%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 1.02%   |
| Lenovo Z50-75 80EC                                | 1         | 1.02%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 1.02%   |
| Lenovo ThinkPad T490 20N3S7BC02                   | 1         | 1.02%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 1.02%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 1.02%   |
| Lenovo ThinkPad T420s 41732BU                     | 1         | 1.02%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 1.02%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 1.02%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 1.02%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 1.02%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 1.02%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 1.02%   |
| Lenovo IdeaPad 3 15ALC6 82KU                      | 1         | 1.02%   |
| Lenovo G505s 20255                                | 1         | 1.02%   |
| Lenovo G40-70 20369                               | 1         | 1.02%   |
| HP ProBook 6470b                                  | 1         | 1.02%   |
| HP ProBook 4520s                                  | 1         | 1.02%   |
| HP Pavilion ze2000 (EC201UA#ABA)                  | 1         | 1.02%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 1         | 1.02%   |
| HP Pavilion dv6                                   | 1         | 1.02%   |
| HP OMEN Laptop 15-en1xxx                          | 1         | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 18        | 18.37%  |
| Dell Inspiron              | 10        | 10.2%   |
| Lenovo ThinkPad            | 8         | 8.16%   |
| Acer Aspire                | 5         | 5.1%    |
| Lenovo IdeaPad             | 4         | 4.08%   |
| HP Pavilion                | 3         | 3.06%   |
| HP Laptop                  | 3         | 3.06%   |
| HP EliteBook               | 3         | 3.06%   |
| HP ProBook                 | 2         | 2.04%   |
| EVOO EV-C-116-7            | 2         | 2.04%   |
| Dell Vostro                | 2         | 2.04%   |
| ASUS VivoBook              | 2         | 2.04%   |
| Apple MacBookPro8          | 2         | 2.04%   |
| VTEX NOTEBOOK              | 1         | 1.02%   |
| Toshiba Satellite          | 1         | 1.02%   |
| TODOS INDUSTRIAL Easytouch | 1         | 1.02%   |
| Samsung RV420              | 1         | 1.02%   |
| Samsung 905S3G             | 1         | 1.02%   |
| SAELITE ES1AU11            | 1         | 1.02%   |
| Nuvision NES11             | 1         | 1.02%   |
| MSI GE62                   | 1         | 1.02%   |
| MSI CR70                   | 1         | 1.02%   |
| Lenovo Z50-75              | 1         | 1.02%   |
| Lenovo ThinkBook           | 1         | 1.02%   |
| Lenovo Legion              | 1         | 1.02%   |
| Lenovo G505s               | 1         | 1.02%   |
| Lenovo G40-70              | 1         | 1.02%   |
| HP OMEN                    | 1         | 1.02%   |
| HP Notebook                | 1         | 1.02%   |
| HP G60                     | 1         | 1.02%   |
| HP ENVY                    | 1         | 1.02%   |
| HP 255                     | 1         | 1.02%   |
| HP 250                     | 1         | 1.02%   |
| Google Winky               | 1         | 1.02%   |
| Google Kip                 | 1         | 1.02%   |
| Fujitsu LIFEBOOK           | 1         | 1.02%   |
| Eluktronics P670RE3        | 1         | 1.02%   |
| ECS ClassMate              | 1         | 1.02%   |
| Dell XPS                   | 1         | 1.02%   |
| ASUS ZenBook               | 1         | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 11        | 11.22%  |
| 2019 | 10        | 10.2%   |
| 2017 | 10        | 10.2%   |
| 2014 | 9         | 9.18%   |
| 2013 | 9         | 9.18%   |
| 2012 | 8         | 8.16%   |
| 2021 | 7         | 7.14%   |
| 2020 | 5         | 5.1%    |
| 2018 | 5         | 5.1%    |
| 2010 | 5         | 5.1%    |
| 2008 | 5         | 5.1%    |
| 2015 | 4         | 4.08%   |
| 2009 | 3         | 3.06%   |
| 2016 | 2         | 2.04%   |
| 2007 | 2         | 2.04%   |
| 2022 | 1         | 1.02%   |
| 2006 | 1         | 1.02%   |
| 2005 | 1         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 98        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 94        | 95.92%  |
| Enabled  | 4         | 4.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 96        | 97.96%  |
| Yes  | 2         | 2.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 31        | 31.63%  |
| 4.01-8.0   | 26        | 26.53%  |
| 8.01-16.0  | 18        | 18.37%  |
| 16.01-24.0 | 11        | 11.22%  |
| 2.01-3.0   | 4         | 4.08%   |
| 1.01-2.0   | 4         | 4.08%   |
| 32.01-64.0 | 3         | 3.06%   |
| 24.01-32.0 | 1         | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 40        | 37.38%  |
| 2.01-3.0  | 29        | 27.1%   |
| 3.01-4.0  | 19        | 17.76%  |
| 4.01-8.0  | 12        | 11.21%  |
| 0.51-1.0  | 6         | 5.61%   |
| 8.01-16.0 | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 75        | 75.76%  |
| 2      | 24        | 24.24%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 54.55%  |
| Yes       | 45        | 45.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 81.63%  |
| No        | 18        | 18.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 97.96%  |
| No        | 2         | 2.04%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 70.71%  |
| No        | 29        | 29.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 98        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 63        | 62.38%  |
| Santiago de los Caballeros | 9         | 8.91%   |
| Santo Domingo              | 5         | 4.95%   |
| La Romana                  | 5         | 4.95%   |
| Santa Cruz de Barahona     | 2         | 1.98%   |
| Concepción de la Vega     | 2         | 1.98%   |
| Alejandro Bass             | 2         | 1.98%   |
| Sosua, Cabarete            | 1         | 0.99%   |
| Santo Domingo Oeste        | 1         | 0.99%   |
| San Pedro de Macorís      | 1         | 0.99%   |
| San Cristobal              | 1         | 0.99%   |
| Punta Cana                 | 1         | 0.99%   |
| Los Hidalgos               | 1         | 0.99%   |
| Guaymate                   | 1         | 0.99%   |
| Constanza                  | 1         | 0.99%   |
| Cancino                    | 1         | 0.99%   |
| Cabarete                   | 1         | 0.99%   |
| Boca Chica                 | 1         | 0.99%   |
| Baní                      | 1         | 0.99%   |
| Bajos de Haina             | 1         | 0.99%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 20        | 26     | 17.39%  |
| Samsung Electronics       | 14        | 15     | 12.17%  |
| Toshiba                   | 12        | 14     | 10.43%  |
| WDC                       | 11        | 14     | 9.57%   |
| SanDisk                   | 8         | 11     | 6.96%   |
| Hitachi                   | 8         | 9      | 6.96%   |
| Kingston                  | 6         | 6      | 5.22%   |
| Unknown                   | 5         | 6      | 4.35%   |
| SK hynix                  | 5         | 6      | 4.35%   |
| Unknown                   | 3         | 3      | 2.61%   |
| Transcend                 | 2         | 2      | 1.74%   |
| SPCC                      | 2         | 2      | 1.74%   |
| Micron/Crucial Technology | 2         | 2      | 1.74%   |
| Micron Technology         | 2         | 2      | 1.74%   |
| Intel                     | 2         | 3      | 1.74%   |
| FORESEE                   | 2         | 2      | 1.74%   |
| China                     | 2         | 3      | 1.74%   |
| UMIS                      | 1         | 1      | 0.87%   |
| PNY                       | 1         | 1      | 0.87%   |
| OCZ                       | 1         | 1      | 0.87%   |
| LITEONIT                  | 1         | 2      | 0.87%   |
| Indilinx                  | 1         | 1      | 0.87%   |
| Hewlett-Packard           | 1         | 1      | 0.87%   |
| Eluktro                   | 1         | 1      | 0.87%   |
| AirDisk                   | 1         | 1      | 0.87%   |
| A-DATA Technology         | 1         | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LM000-1EJ162 500GB                     | 3         | 2.54%   |
| Unknown                                             | 3         | 2.54%   |
| Unknown MMC Card  32GB                              | 2         | 1.69%   |
| Unknown MMC Card  16GB                              | 2         | 1.69%   |
| Toshiba MQ01ACF050 500GB                            | 2         | 1.69%   |
| Toshiba MK3275GSX 320GB                             | 2         | 1.69%   |
| Seagate ST9250315AS 250GB                           | 2         | 1.69%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 1.69%   |
| SanDisk NVMe SSD Drive 256GB                        | 2         | 1.69%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 1.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 1.69%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.69%   |
| FORESEE 128GB SSD                                   | 2         | 1.69%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                      | 1         | 0.85%   |
| WDC WD5000LPLX-08ZNTT0 500GB                        | 1         | 0.85%   |
| WDC WD3200LPVX-75V0TT0 320GB                        | 1         | 0.85%   |
| WDC WD3200BEVT-75A23T0 320GB                        | 1         | 0.85%   |
| WDC WD2500BEVT-75A23T0 250GB                        | 1         | 0.85%   |
| WDC WD2500BEVS-22UST0 250GB                         | 1         | 0.85%   |
| WDC WD2500BEKT-60A25T1 250GB                        | 1         | 0.85%   |
| WDC WD1600BEVT-75ZCT1 160GB                         | 1         | 0.85%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 0.85%   |
| WDC WD10JPVX-60JC3T1 1TB                            | 1         | 0.85%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 0.85%   |
| Unknown MMC Card  64GB                              | 1         | 0.85%   |
| Unknown MMC Card  128GB                             | 1         | 0.85%   |
| UMIS RPJTJ256MEE1OWX 256GB                          | 1         | 0.85%   |
| Transcend TS256GSSD340 256GB                        | 1         | 0.85%   |
| Transcend TS128GSSD370S 128GB                       | 1         | 0.85%   |
| Toshiba NVMe SSD Drive 1024GB                       | 1         | 0.85%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 0.85%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 0.85%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.85%   |
| Toshiba MK6475GSX 640GB                             | 1         | 0.85%   |
| Toshiba MK6465GSXN 640GB                            | 1         | 0.85%   |
| Toshiba MK3276GSX 320GB                             | 1         | 0.85%   |
| Toshiba MK2556GSY 250GB                             | 1         | 0.85%   |
| SPCC Solid State Disk 512GB                         | 1         | 0.85%   |
| SPCC Solid State Disk 1024GB                        | 1         | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 26     | 40%     |
| Toshiba             | 11        | 13     | 22%     |
| WDC                 | 10        | 13     | 20%     |
| Hitachi             | 8         | 9      | 16%     |
| Samsung Electronics | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 21.05%  |
| SanDisk             | 6         | 9      | 15.79%  |
| Kingston            | 5         | 5      | 13.16%  |
| Transcend           | 2         | 2      | 5.26%   |
| SPCC                | 2         | 2      | 5.26%   |
| SK hynix            | 2         | 2      | 5.26%   |
| FORESEE             | 2         | 2      | 5.26%   |
| China               | 2         | 3      | 5.26%   |
| WDC                 | 1         | 1      | 2.63%   |
| PNY                 | 1         | 1      | 2.63%   |
| OCZ                 | 1         | 1      | 2.63%   |
| LITEONIT            | 1         | 2      | 2.63%   |
| Hewlett-Packard     | 1         | 1      | 2.63%   |
| Eluktro             | 1         | 1      | 2.63%   |
| AirDisk             | 1         | 1      | 2.63%   |
| A-DATA Technology   | 1         | 1      | 2.63%   |
| Unknown             | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 48        | 62     | 44.04%  |
| SSD     | 35        | 44     | 32.11%  |
| NVMe    | 17        | 20     | 15.6%   |
| MMC     | 8         | 9      | 7.34%   |
| Unknown | 1         | 1      | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 77        | 103    | 73.33%  |
| NVMe | 17        | 20     | 16.19%  |
| MMC  | 8         | 9      | 7.62%   |
| SAS  | 3         | 4      | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 78     | 71.6%   |
| 0.51-1.0   | 19        | 23     | 23.46%  |
| 1.01-2.0   | 3         | 3      | 3.7%    |
| 4.01-10.0  | 1         | 2      | 1.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 33.33%  |
| 251-500        | 19        | 18.63%  |
| 501-1000       | 17        | 16.67%  |
| 1-20           | 9         | 8.82%   |
| 51-100         | 8         | 7.84%   |
| 1001-2000      | 5         | 4.9%    |
| 21-50          | 4         | 3.92%   |
| 2001-3000      | 3         | 2.94%   |
| Unknown        | 2         | 1.96%   |
| More than 3000 | 1         | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 43        | 39.09%  |
| 21-50     | 22        | 20%     |
| 51-100    | 17        | 15.45%  |
| 101-250   | 13        | 11.82%  |
| 251-500   | 4         | 3.64%   |
| 501-1000  | 4         | 3.64%   |
| 1001-2000 | 3         | 2.73%   |
| 2001-3000 | 2         | 1.82%   |
| Unknown   | 2         | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEKT-60A25T1 250GB      | 1         | 1      | 8.33%   |
| Toshiba MK6465GSXN 640GB          | 1         | 1      | 8.33%   |
| Toshiba MK3276GSX 320GB           | 1         | 1      | 8.33%   |
| Toshiba MK3275GSX 320GB           | 1         | 1      | 8.33%   |
| Seagate ST9750420AS 752GB         | 1         | 1      | 8.33%   |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 8.33%   |
| Seagate ST500LM000-1EJ162 500GB   | 1         | 1      | 8.33%   |
| Seagate ST2000LM007-1R8174 2TB    | 1         | 1      | 8.33%   |
| Samsung Electronics HM500LI 500GB | 1         | 1      | 8.33%   |
| Hitachi HTS727550A9E364 500GB     | 1         | 1      | 8.33%   |
| Hitachi HTS725032A9A364 320GB     | 1         | 1      | 8.33%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 33.33%  |
| Toshiba             | 3         | 3      | 25%     |
| Hitachi             | 3         | 3      | 25%     |
| WDC                 | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 33.33%  |
| Toshiba             | 3         | 3      | 25%     |
| Hitachi             | 3         | 3      | 25%     |
| WDC                 | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 100%    |

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
| Detected | 61        | 91     | 59.8%   |
| Works    | 29        | 33     | 28.43%  |
| Malfunc  | 12        | 12     | 11.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 71        | 68.27%  |
| AMD                          | 16        | 15.38%  |
| Samsung Electronics          | 5         | 4.81%   |
| SK hynix                     | 2         | 1.92%   |
| SanDisk                      | 2         | 1.92%   |
| Micron/Crucial Technology    | 2         | 1.92%   |
| Micron Technology            | 2         | 1.92%   |
| Union Memory (Shenzhen)      | 1         | 0.96%   |
| Toshiba America Info Systems | 1         | 0.96%   |
| Nvidia                       | 1         | 0.96%   |
| Kingston Technology Company  | 1         | 0.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 15        | 13.51%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 11        | 9.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 9         | 8.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 7         | 6.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 7         | 6.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 6.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 5         | 4.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 3.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 4         | 3.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 2.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 2.7%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 2         | 1.8%    |
| Micron NVMe Storage Controller                                                         | 2         | 1.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 2         | 1.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 1.8%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.9%    |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 0.9%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.9%    |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.9%    |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 0.9%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.9%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 0.9%    |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 0.9%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.9%    |
| Intel NVMe Controller                                                                  | 1         | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.9%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.9%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 0.9%    |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 0.9%    |
| AMD FCH IDE Controller                                                                 | 1         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 67        | 63.21%  |
| NVMe | 17        | 16.04%  |
| RAID | 12        | 11.32%  |
| IDE  | 10        | 9.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 80        | 81.63%  |
| AMD    | 18        | 18.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 4.08%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 4.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 3.06%   |
| Intel Celeron N4120 CPU @ 1.10GHz           | 3         | 3.06%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.04%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 2.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 2.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.04%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 2.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 2.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 2.04%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 2.04%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 2         | 2.04%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 2         | 2.04%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 2.04%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 2.04%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 2.04%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.02%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.02%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.02%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 1.02%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.02%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.02%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 1.02%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.02%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.02%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 1.02%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.02%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.02%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.02%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.02%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.02%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 1.02%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.02%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 1.02%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.02%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.02%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.02%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 29.59%  |
| Intel Core i7           | 14        | 14.29%  |
| Intel Celeron           | 14        | 14.29%  |
| Intel Core i3           | 9         | 9.18%   |
| Intel Core 2 Duo        | 4         | 4.08%   |
| AMD Ryzen 7             | 3         | 3.06%   |
| AMD Ryzen 5             | 3         | 3.06%   |
| AMD A10                 | 3         | 3.06%   |
| Intel Core 2            | 2         | 2.04%   |
| Intel Atom              | 2         | 2.04%   |
| AMD A8                  | 2         | 2.04%   |
| AMD A6                  | 2         | 2.04%   |
| Other                   | 1         | 1.02%   |
| Intel Pentium Dual-Core | 1         | 1.02%   |
| Intel Pentium Dual      | 1         | 1.02%   |
| Intel Pentium           | 1         | 1.02%   |
| Intel Genuine           | 1         | 1.02%   |
| Intel Core i9           | 1         | 1.02%   |
| AMD Ryzen 3             | 1         | 1.02%   |
| AMD Quad-Core           | 1         | 1.02%   |
| AMD Mobile Sempron      | 1         | 1.02%   |
| AMD A4                  | 1         | 1.02%   |
| AMD A12                 | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 66        | 67.35%  |
| 4      | 25        | 25.51%  |
| 8      | 3         | 3.06%   |
| 6      | 2         | 2.04%   |
| 1      | 2         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 98        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 64        | 65.31%  |
| 1      | 34        | 34.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 96        | 97.96%  |
| 32-bit         | 1         | 1.02%   |
| Unknown        | 1         | 1.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 20.2%   |
| 0x206a7    | 11        | 11.11%  |
| 0x306a9    | 7         | 7.07%   |
| 0x806e9    | 5         | 5.05%   |
| 0x40651    | 5         | 5.05%   |
| 0x806ea    | 4         | 4.04%   |
| 0x706a1    | 4         | 4.04%   |
| 0x1067a    | 4         | 4.04%   |
| 0x306c3    | 3         | 3.03%   |
| 0x30678    | 3         | 3.03%   |
| 0x07030105 | 3         | 3.03%   |
| 0x806ec    | 2         | 2.02%   |
| 0x706a8    | 2         | 2.02%   |
| 0x6f6      | 2         | 2.02%   |
| 0x506e3    | 2         | 2.02%   |
| 0x20655    | 2         | 2.02%   |
| 0x20652    | 2         | 2.02%   |
| 0x10676    | 2         | 2.02%   |
| 0x806c1    | 1         | 1.01%   |
| 0x6fd      | 1         | 1.01%   |
| 0x506c9    | 1         | 1.01%   |
| 0x406c3    | 1         | 1.01%   |
| 0x106ca    | 1         | 1.01%   |
| 0x08608103 | 1         | 1.01%   |
| 0x08608102 | 1         | 1.01%   |
| 0x08600103 | 1         | 1.01%   |
| 0x08108109 | 1         | 1.01%   |
| 0x08108102 | 1         | 1.01%   |
| 0x0700010f | 1         | 1.01%   |
| 0x06006705 | 1         | 1.01%   |
| 0x0600611a | 1         | 1.01%   |
| 0x06006110 | 1         | 1.01%   |
| 0x06003106 | 1         | 1.01%   |
| 0x06001119 | 1         | 1.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 17.35%  |
| SandyBridge   | 11        | 11.22%  |
| IvyBridge     | 9         | 9.18%   |
| Haswell       | 9         | 9.18%   |
| Goldmont plus | 7         | 7.14%   |
| Westmere      | 6         | 6.12%   |
| Silvermont    | 6         | 6.12%   |
| Penryn        | 6         | 6.12%   |
| Zen+          | 3         | 3.06%   |
| Puma          | 3         | 3.06%   |
| Excavator     | 3         | 3.06%   |
| Core          | 3         | 3.06%   |
| Skylake       | 2         | 2.04%   |
| Unknown       | 2         | 2.04%   |
| Zen 3         | 1         | 1.02%   |
| Zen 2         | 1         | 1.02%   |
| TigerLake     | 1         | 1.02%   |
| Steamroller   | 1         | 1.02%   |
| Piledriver    | 1         | 1.02%   |
| K8 Hammer     | 1         | 1.02%   |
| K10 Llano     | 1         | 1.02%   |
| Jaguar        | 1         | 1.02%   |
| IceLake       | 1         | 1.02%   |
| Goldmont      | 1         | 1.02%   |
| Bonnell       | 1         | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 75        | 66.96%  |
| AMD    | 23        | 20.54%  |
| Nvidia | 14        | 12.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 8.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 7.69%   |
| Intel UHD Graphics 620                                                                   | 7         | 5.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 5.98%   |
| Intel HD Graphics 620                                                                    | 5         | 4.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 4.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 4.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 4.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.56%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.71%   |
| Intel HD Graphics 530                                                                    | 2         | 1.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.71%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.71%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.71%   |
| AMD Lucienne                                                                             | 2         | 1.71%   |
| Nvidia TU117M                                                                            | 1         | 0.85%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.85%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.85%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                               | 1         | 0.85%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.85%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.85%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.85%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 0.85%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 0.85%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.85%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.85%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.85%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.85%   |
| Intel HD Graphics 500                                                                    | 1         | 0.85%   |
| Intel Haswell Integrated Graphics Controller                                             | 1         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 64        | 65.31%  |
| 1 x AMD        | 14        | 14.29%  |
| Intel + Nvidia | 7         | 7.14%   |
| 1 x Nvidia     | 4         | 4.08%   |
| Intel + AMD    | 4         | 4.08%   |
| AMD + Nvidia   | 3         | 3.06%   |
| 2 x AMD        | 2         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 91        | 92.86%  |
| Proprietary | 6         | 6.12%   |
| Unknown     | 1         | 1.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 73.74%  |
| 0.01-0.5   | 9         | 9.09%   |
| 1.01-2.0   | 7         | 7.07%   |
| 0.51-1.0   | 7         | 7.07%   |
| 3.01-4.0   | 2         | 2.02%   |
| 2.01-3.0   | 1         | 1.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 21        | 18.92%  |
| BOE                     | 17        | 15.32%  |
| LG Display              | 16        | 14.41%  |
| Chimei Innolux          | 14        | 12.61%  |
| Samsung Electronics     | 13        | 11.71%  |
| Dell                    | 6         | 5.41%   |
| Chi Mei Optoelectronics | 5         | 4.5%    |
| Apple                   | 4         | 3.6%    |
| Hewlett-Packard         | 2         | 1.8%    |
| ZTR                     | 1         | 0.9%    |
| Westinghouse            | 1         | 0.9%    |
| Vizio                   | 1         | 0.9%    |
| Unknown (XXX)           | 1         | 0.9%    |
| Sony                    | 1         | 0.9%    |
| Philips                 | 1         | 0.9%    |
| PANDA                   | 1         | 0.9%    |
| LG Philips              | 1         | 0.9%    |
| Lenovo                  | 1         | 0.9%    |
| KDC                     | 1         | 0.9%    |
| InnoLux Display         | 1         | 0.9%    |
| InfoVision              | 1         | 0.9%    |
| Goldstar                | 1         | 0.9%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 3         | 2.7%    |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 1.8%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.8%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 2         | 1.8%    |
| ZTR LCD Monitor ZTR0001 1366x768 309x173mm 13.9-inch                  | 1         | 0.9%    |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch          | 1         | 0.9%    |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 0.9%    |
| Unknown (XXX) Philco XXX0030 1600x1200 708x398mm 32.0-inch            | 1         | 0.9%    |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                         | 1         | 0.9%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4642 1366x768 309x174mm 14.0-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch  | 1         | 0.9%    |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch              | 1         | 0.9%    |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch               | 1         | 0.9%    |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0357 1600x900 382x215mm 17.3-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 0.9%    |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 0.9%    |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 1         | 0.9%    |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch      | 1         | 0.9%    |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 1         | 0.9%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 49        | 47.12%  |
| 1920x1080 (FHD)    | 32        | 30.77%  |
| 1280x800 (WXGA)    | 7         | 6.73%   |
| 1600x900 (HD+)     | 6         | 5.77%   |
| 3840x2160 (4K)     | 2         | 1.92%   |
| 1280x1024 (SXGA)   | 2         | 1.92%   |
| 3840x1100          | 1         | 0.96%   |
| 1680x1050 (WSXGA+) | 1         | 0.96%   |
| 1360x768           | 1         | 0.96%   |
| 1280x768           | 1         | 0.96%   |
| 1024x768 (XGA)     | 1         | 0.96%   |
| 1024x600           | 1         | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 50        | 45.45%  |
| 13      | 18        | 16.36%  |
| 14      | 14        | 12.73%  |
| 11      | 8         | 7.27%   |
| 17      | 4         | 3.64%   |
| 24      | 2         | 1.82%   |
| 22      | 2         | 1.82%   |
| 21      | 2         | 1.82%   |
| 72      | 1         | 0.91%   |
| 40      | 1         | 0.91%   |
| 34      | 1         | 0.91%   |
| 32      | 1         | 0.91%   |
| 31      | 1         | 0.91%   |
| 23      | 1         | 0.91%   |
| 20      | 1         | 0.91%   |
| 19      | 1         | 0.91%   |
| 10      | 1         | 0.91%   |
| Unknown | 1         | 0.91%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 70        | 64.81%  |
| 201-300     | 17        | 15.74%  |
| 351-400     | 7         | 6.48%   |
| 401-500     | 5         | 4.63%   |
| 501-600     | 3         | 2.78%   |
| 701-800     | 2         | 1.85%   |
| 801-900     | 1         | 0.93%   |
| 601-700     | 1         | 0.93%   |
| 1501-2000   | 1         | 0.93%   |
| Unknown     | 1         | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 85        | 86.73%  |
| 16/10   | 8         | 8.16%   |
| 5/4     | 2         | 2.04%   |
| 4/3     | 1         | 1.02%   |
| 3.40    | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 50        | 45.45%  |
| 81-90          | 26        | 23.64%  |
| 51-60          | 9         | 8.18%   |
| 201-250        | 7         | 6.36%   |
| 71-80          | 5         | 4.55%   |
| 121-130        | 3         | 2.73%   |
| 351-500        | 2         | 1.82%   |
| 151-200        | 2         | 1.82%   |
| 501-1000       | 2         | 1.82%   |
| More than 1000 | 1         | 0.91%   |
| 41-50          | 1         | 0.91%   |
| 141-150        | 1         | 0.91%   |
| Unknown        | 1         | 0.91%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 50        | 46.73%  |
| 121-160       | 35        | 32.71%  |
| 51-100        | 15        | 14.02%  |
| 1-50          | 3         | 2.8%    |
| 161-240       | 2         | 1.87%   |
| More than 240 | 1         | 0.93%   |
| Unknown       | 1         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 81        | 81.82%  |
| 2     | 15        | 15.15%  |
| 0     | 2         | 2.02%   |
| 3     | 1         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 32.24%  |
| Realtek Semiconductor           | 48        | 31.58%  |
| Qualcomm Atheros                | 24        | 15.79%  |
| Broadcom                        | 14        | 9.21%   |
| Ralink Technology               | 3         | 1.97%   |
| Broadcom Limited                | 3         | 1.97%   |
| Qualcomm Atheros Communications | 2         | 1.32%   |
| Marvell Technology Group        | 2         | 1.32%   |
| Lenovo                          | 2         | 1.32%   |
| Nvidia                          | 1         | 0.66%   |
| MediaTek                        | 1         | 0.66%   |
| JCM                             | 1         | 0.66%   |
| Dell                            | 1         | 0.66%   |
| AMD                             | 1         | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 11.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 7.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 4.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 4.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 3.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 3.21%   |
| Intel Wireless 7260                                               | 5         | 2.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 2.14%   |
| Intel Wireless 3165                                               | 4         | 2.14%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.6%    |
| Intel Wireless 8265 / 8275                                        | 3         | 1.6%    |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.6%    |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.07%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 1.07%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 1.07%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 1.07%   |
| Lenovo Thinkpad LAN                                               | 2         | 1.07%   |
| Intel Wireless 7265                                               | 2         | 1.07%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.07%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 1.07%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.07%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.07%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.07%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.53%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 46.08%  |
| Qualcomm Atheros                | 21        | 20.59%  |
| Realtek Semiconductor           | 15        | 14.71%  |
| Broadcom                        | 11        | 10.78%  |
| Ralink Technology               | 3         | 2.94%   |
| Qualcomm Atheros Communications | 2         | 1.96%   |
| MediaTek                        | 1         | 0.98%   |
| Dell                            | 1         | 0.98%   |
| Broadcom Limited                | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 8         | 7.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 6         | 5.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 6         | 5.83%   |
| Intel Wireless 7260                                                                   | 5         | 4.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 3.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 3.88%   |
| Intel Wireless 3165                                                                   | 4         | 3.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 2.91%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 2.91%   |
| Intel Wi-Fi 6 AX200                                                                   | 3         | 2.91%   |
| Intel Centrino Advanced-N 6235                                                        | 3         | 2.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 2.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 2.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.94%   |
| Realtek 802.11n WLAN Adapter                                                          | 2         | 1.94%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 1.94%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 1.94%   |
| Intel Wireless 7265                                                                   | 2         | 1.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.94%   |
| Intel Centrino Wireless-N 2230                                                        | 2         | 1.94%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.94%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 1.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.94%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.97%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.97%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.97%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.97%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 0.97%   |
| Intel Wireless 8260                                                                   | 1         | 0.97%   |
| Intel Wireless 3160                                                                   | 1         | 0.97%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 0.97%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 0.97%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 39        | 47.56%  |
| Intel                    | 25        | 30.49%  |
| Broadcom                 | 6         | 7.32%   |
| Qualcomm Atheros         | 5         | 6.1%    |
| Marvell Technology Group | 2         | 2.44%   |
| Lenovo                   | 2         | 2.44%   |
| Broadcom Limited         | 2         | 2.44%   |
| Nvidia                   | 1         | 1.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 26.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 17.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 10.98%  |
| Intel 82577LM Gigabit Network Connection                          | 4         | 4.88%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.44%   |
| Lenovo Thinkpad LAN                                               | 2         | 2.44%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.22%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.22%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.22%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.22%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.22%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.22%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.22%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.22%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.22%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.22%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 1.22%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.22%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.22%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 1.22%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 1.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 96        | 53.93%  |
| Ethernet | 80        | 44.94%  |
| Modem    | 2         | 1.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 77.45%  |
| Ethernet | 23        | 22.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 77        | 78.57%  |
| 1     | 18        | 18.37%  |
| 0     | 3         | 3.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 95        | 95.96%  |
| Yes  | 4         | 4.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 42.86%  |
| Qualcomm Atheros Communications | 12        | 17.14%  |
| Realtek Semiconductor           | 6         | 8.57%   |
| IMC Networks                    | 6         | 8.57%   |
| Dell                            | 6         | 8.57%   |
| Apple                           | 4         | 5.71%   |
| Broadcom                        | 3         | 4.29%   |
| Lite-On Technology              | 2         | 2.86%   |
| Hewlett-Packard                 | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 16        | 22.86%  |
| Qualcomm Atheros  Bluetooth Device             | 7         | 10%     |
| Intel Centrino Bluetooth Wireless Transceiver  | 5         | 7.14%   |
| IMC Networks Bluetooth Radio                   | 4         | 5.71%   |
| Realtek  Bluetooth 4.2 Adapter                 | 3         | 4.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 3         | 4.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 4.29%   |
| Intel AX200 Bluetooth                          | 3         | 4.29%   |
| Dell BCM20702A0 Bluetooth Module               | 3         | 4.29%   |
| Apple Bluetooth Host Controller                | 3         | 4.29%   |
| Realtek Bluetooth Radio                        | 2         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 2.86%   |
| Realtek RTL8723B Bluetooth                     | 1         | 1.43%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 1.43%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 1.43%   |
| Lite-On Wireless_Device                        | 1         | 1.43%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 1.43%   |
| Intel AX201 Bluetooth                          | 1         | 1.43%   |
| IMC Networks Bluetooth Device                  | 1         | 1.43%   |
| IMC Networks Bluetooth                         | 1         | 1.43%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 1.43%   |
| Dell Wireless 360 Bluetooth                    | 1         | 1.43%   |
| Dell Wireless 355 Bluetooth                    | 1         | 1.43%   |
| Dell Wireless 350 Bluetooth                    | 1         | 1.43%   |
| Broadcom HP Portable SoftSailing               | 1         | 1.43%   |
| Broadcom BCM43142 Bluetooth 4.0                | 1         | 1.43%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 1.43%   |
| Apple Bluetooth HCI                            | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 78        | 70.91%  |
| AMD                 | 19        | 17.27%  |
| Nvidia              | 9         | 8.18%   |
| Logitech            | 2         | 1.82%   |
| Sony                | 1         | 0.91%   |
| C-Media Electronics | 1         | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 9.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 7.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 7.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 5.26%   |
| AMD FCH Azalia Controller                                                                         | 7         | 5.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 5.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 4.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 4.51%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.76%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 3.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 3.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 2.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 2.26%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 2.26%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.5%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.5%    |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.75%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.75%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.75%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Logitech Logi USB Headset                                                                         | 1         | 0.75%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.75%   |
| C-Media Electronics USB PnP Sound Device                                                          | 1         | 0.75%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.75%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 20        | 30.77%  |
| Samsung Electronics | 16        | 24.62%  |
| Micron Technology   | 8         | 12.31%  |
| Kingston            | 4         | 6.15%   |
| Crucial             | 4         | 6.15%   |
| Unknown (ABCD)      | 3         | 4.62%   |
| Unknown             | 2         | 3.08%   |
| Ramaxel Technology  | 2         | 3.08%   |
| Nanya Technology    | 2         | 3.08%   |
| A-DATA Technology   | 2         | 3.08%   |
| Sesame              | 1         | 1.54%   |
| Unknown             | 1         | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 4.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.94%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.94%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 2.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.94%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 2.94%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 2.94%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 2.94%   |
| A-DATA RAM AD73I1B1674EU 2GB SODIMM DDR3 1334MT/s                | 2         | 2.94%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.47%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.47%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.47%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.47%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.47%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 2667MT/s                | 1         | 1.47%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 1.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.47%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.47%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 21        | 42.86%  |
| DDR4   | 17        | 34.69%  |
| LPDDR4 | 5         | 10.2%   |
| SDRAM  | 3         | 6.12%   |
| DDR2   | 2         | 4.08%   |
| LPDDR3 | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 93.88%  |
| Row Of Chips | 2         | 4.08%   |
| DIMM         | 1         | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 22        | 40%     |
| 8192  | 15        | 27.27%  |
| 2048  | 11        | 20%     |
| 16384 | 7         | 12.73%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 17        | 29.31%  |
| 2667  | 9         | 15.52%  |
| 2400  | 9         | 15.52%  |
| 1333  | 6         | 10.34%  |
| 3200  | 3         | 5.17%   |
| 1334  | 3         | 5.17%   |
| 4199  | 2         | 3.45%   |
| 3266  | 2         | 3.45%   |
| 2133  | 2         | 3.45%   |
| 2048  | 1         | 1.72%   |
| 1867  | 1         | 1.72%   |
| 1067  | 1         | 1.72%   |
| 975   | 1         | 1.72%   |
| 667   | 1         | 1.72%   |

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
| Chicony Electronics                    | 15        | 17.65%  |
| Microdia                               | 12        | 14.12%  |
| Sunplus Innovation Technology          | 8         | 9.41%   |
| IMC Networks                           | 8         | 9.41%   |
| Suyin                                  | 7         | 8.24%   |
| Realtek Semiconductor                  | 6         | 7.06%   |
| Syntek                                 | 4         | 4.71%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.71%   |
| Apple                                  | 4         | 4.71%   |
| Silicon Motion                         | 3         | 3.53%   |
| Ricoh                                  | 3         | 3.53%   |
| Quanta                                 | 2         | 2.35%   |
| Primax Electronics                     | 2         | 2.35%   |
| Sonix Technology                       | 1         | 1.18%   |
| OmniVision Technologies                | 1         | 1.18%   |
| MacroSilicon                           | 1         | 1.18%   |
| Logitech                               | 1         | 1.18%   |
| globaloptics                           | 1         | 1.18%   |
| Bison Electronics                      | 1         | 1.18%   |
| Alcor Micro                            | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                    | 5         | 5.88%   |
| Chicony Integrated Camera                                       | 5         | 5.88%   |
| IMC Networks Integrated Camera                                  | 3         | 3.53%   |
| Syntek Lenovo EasyCamera                                        | 2         | 2.35%   |
| Microdia Sonix USB 2.0 Camera                                   | 2         | 2.35%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 2.35%   |
| Microdia Integrated Webcam                                      | 2         | 2.35%   |
| Microdia HP Integrated Webcam                                   | 2         | 2.35%   |
| Microdia Dell Integrated HD Webcam                              | 2         | 2.35%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 2         | 2.35%   |
| Chicony Integrated HP HD Webcam                                 | 2         | 2.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 2.35%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 2         | 2.35%   |
| Apple FaceTime HD Camera                                        | 2         | 2.35%   |
| Syntek Integrated Camera                                        | 1         | 1.18%   |
| Syntek EasyCamera                                               | 1         | 1.18%   |
| Suyin VGA Webcam                                                | 1         | 1.18%   |
| Suyin TOSHIBA Web Camera - HD                                   | 1         | 1.18%   |
| Suyin Laptop_Integrated_Webcam_HD                               | 1         | 1.18%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 1.18%   |
| Suyin HP TrueVision HD                                          | 1         | 1.18%   |
| Suyin Acer/Lenovo Webcam [CN0316]                               | 1         | 1.18%   |
| Suyin 1.3M HD WebCam                                            | 1         | 1.18%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 1.18%   |
| Sunplus Laptop_Integrated_Webcam_FHD                            | 1         | 1.18%   |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 1.18%   |
| Sonix HP Webcam-101                                             | 1         | 1.18%   |
| Silicon Motion WebCam SCB-0385N                                 | 1         | 1.18%   |
| Silicon Motion WebCam SC-10HDD13335N                            | 1         | 1.18%   |
| Silicon Motion Real HD WebCam                                   | 1         | 1.18%   |
| Ricoh Laptop_Integrated_Webcam_FHD                              | 1         | 1.18%   |
| Ricoh Integrated Webcam                                         | 1         | 1.18%   |
| Ricoh HD Webcam                                                 | 1         | 1.18%   |
| Realtek USB Camera                                              | 1         | 1.18%   |
| Realtek Integrated Webcam HD                                    | 1         | 1.18%   |
| Realtek Integrated Webcam                                       | 1         | 1.18%   |
| Realtek Integrated Camera                                       | 1         | 1.18%   |
| Realtek HP Wide Vision HD Camera                                | 1         | 1.18%   |
| Realtek HP Truevision HD integrated webcam                      | 1         | 1.18%   |
| Quanta HP Webcam                                                | 1         | 1.18%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 50%     |
| Synaptics                  | 3         | 21.43%  |
| STMicroelectronics         | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |
| LighTuning Technology      | 1         | 7.14%   |
| Elan Microelectronics      | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader        | 2         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 14.29%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 7.14%   |
| Validity Sensors VFS491                           | 1         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                   | 1         | 7.14%   |
| Validity Sensors Fingerprint scanner              | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader             | 1         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 7.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 7.14%   |
| Elan ELAN:ARM-M4                                  | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 63.64%  |
| O2 Micro    | 2         | 18.18%  |
| Alcor Micro | 2         | 18.18%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 18.18%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 18.18%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom 58200                                                               | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 69        | 69.7%   |
| 1     | 24        | 24.24%  |
| 2     | 6         | 6.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 14        | 38.89%  |
| Chipcard              | 9         | 25%     |
| Graphics card         | 5         | 13.89%  |
| Storage               | 2         | 5.56%   |
| Net/wireless          | 2         | 5.56%   |
| Multimedia controller | 2         | 5.56%   |
| Card reader           | 1         | 2.78%   |
| Bluetooth             | 1         | 2.78%   |

