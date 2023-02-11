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

Total: 135

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 16        | 17.78%  |
| Ubuntu 18.04        | 7         | 7.78%   |
| Ubuntu 22.04        | 4         | 4.44%   |
| Fedora 36           | 4         | 4.44%   |
| OpenMandriva 4.3    | 3         | 3.33%   |
| Fedora 37           | 3         | 3.33%   |
| Debian 11           | 3         | 3.33%   |
| Zorin 16            | 2         | 2.22%   |
| Ubuntu 21.10        | 2         | 2.22%   |
| Pop!_OS 20.10       | 2         | 2.22%   |
| OpenMandriva 4.2    | 2         | 2.22%   |
| Linux Mint 20.3     | 2         | 2.22%   |
| Linux Mint 20.1     | 2         | 2.22%   |
| ArcoLinux Rolling   | 2         | 2.22%   |
| Xubuntu 19.10       | 1         | 1.11%   |
| Xubuntu 18.04       | 1         | 1.11%   |
| Void Linux Rolling  | 1         | 1.11%   |
| Ubuntu Budgie 22.04 | 1         | 1.11%   |
| Ubuntu Budgie 21.10 | 1         | 1.11%   |
| Ubuntu Budgie 20.04 | 1         | 1.11%   |
| Ubuntu 21.04        | 1         | 1.11%   |
| Ubuntu 19.04        | 1         | 1.11%   |
| Solus 4.1           | 1         | 1.11%   |
| Pop!_OS 21.04       | 1         | 1.11%   |
| Pop!_OS 20.04       | 1         | 1.11%   |
| OpenMandriva 23.01  | 1         | 1.11%   |
| Manjaro 22.0.0      | 1         | 1.11%   |
| Manjaro 21.1.2      | 1         | 1.11%   |
| Manjaro 20.1        | 1         | 1.11%   |
| Lubuntu 21.04       | 1         | 1.11%   |
| LMDE 4              | 1         | 1.11%   |
| Linux Mint 21       | 1         | 1.11%   |
| Linux Mint 20.2     | 1         | 1.11%   |
| Linux Mint 20       | 1         | 1.11%   |
| Linux Mint 19.3     | 1         | 1.11%   |
| Kubuntu 20.04       | 1         | 1.11%   |
| KDE neon 22.04      | 1         | 1.11%   |
| KDE neon 20.04      | 1         | 1.11%   |
| Fedora 34           | 1         | 1.11%   |
| Fedora 33           | 1         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 30        | 33.71%  |
| Fedora        | 12        | 13.48%  |
| Linux Mint    | 8         | 8.99%   |
| OpenMandriva  | 6         | 6.74%   |
| Pop!_OS       | 4         | 4.49%   |
| Debian        | 4         | 4.49%   |
| Ubuntu Budgie | 3         | 3.37%   |
| Manjaro       | 3         | 3.37%   |
| Zorin         | 2         | 2.25%   |
| Xubuntu       | 2         | 2.25%   |
| KDE neon      | 2         | 2.25%   |
| Clear Linux   | 2         | 2.25%   |
| ArcoLinux     | 2         | 2.25%   |
| Arch          | 2         | 2.25%   |
| Void Linux    | 1         | 1.12%   |
| Solus         | 1         | 1.12%   |
| Lubuntu       | 1         | 1.12%   |
| LMDE          | 1         | 1.12%   |
| Kubuntu       | 1         | 1.12%   |
| Elementary    | 1         | 1.12%   |
| Archcraft     | 1         | 1.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-48-generic        | 4         | 3.92%   |
| 5.4.0-42-generic        | 3         | 2.94%   |
| 5.16.7-desktop-1omv4003 | 3         | 2.94%   |
| 5.13.0-22-generic       | 3         | 2.94%   |
| 5.4.0-77-generic        | 2         | 1.96%   |
| 5.4.0-52-generic        | 2         | 1.96%   |
| 5.4.0-33-generic        | 2         | 1.96%   |
| 5.3.0-51-generic        | 2         | 1.96%   |
| 5.15.0-58-generic       | 2         | 1.96%   |
| 5.15.0-53-generic       | 2         | 1.96%   |
| 5.15.0-41-generic       | 2         | 1.96%   |
| 6.1.5-200.fc37.x86_64   | 1         | 0.98%   |
| 6.1.1-desktop-1omv2290  | 1         | 0.98%   |
| 6.0.6-300.fc37.x86_64   | 1         | 0.98%   |
| 6.0.14-300.fc37.x86_64  | 1         | 0.98%   |
| 5.9.12-xanmod1          | 1         | 0.98%   |
| 5.9.11-arch2-1          | 1         | 0.98%   |
| 5.9.1-arch1-1           | 1         | 0.98%   |
| 5.8.8-arch1-1           | 1         | 0.98%   |
| 5.8.15-301.fc33.x86_64  | 1         | 0.98%   |
| 5.8.12_1                | 1         | 0.98%   |
| 5.8.0-38-generic        | 1         | 0.98%   |
| 5.7.10-201.fc32.x86_64  | 1         | 0.98%   |
| 5.6.19-158.current      | 1         | 0.98%   |
| 5.4.60-2-MANJARO        | 1         | 0.98%   |
| 5.4.15-200.fc31.x86_64  | 1         | 0.98%   |
| 5.4.0-7642-generic      | 1         | 0.98%   |
| 5.4.0-74-generic        | 1         | 0.98%   |
| 5.4.0-72-generic        | 1         | 0.98%   |
| 5.4.0-39-generic        | 1         | 0.98%   |
| 5.4.0-29-generic        | 1         | 0.98%   |
| 5.4.0-28-generic        | 1         | 0.98%   |
| 5.4.0-26-generic        | 1         | 0.98%   |
| 5.4.0-109-generic       | 1         | 0.98%   |
| 5.4.0-105-generic       | 1         | 0.98%   |
| 5.3.0-61-generic        | 1         | 0.98%   |
| 5.3.0-46-generic        | 1         | 0.98%   |
| 5.3.0-42-generic        | 1         | 0.98%   |
| 5.3.0-28-generic        | 1         | 0.98%   |
| 5.3.0-19-generic        | 1         | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 22.34%  |
| 5.15.0  | 8         | 8.51%   |
| 5.13.0  | 8         | 8.51%   |
| 5.3.0   | 6         | 6.38%   |
| 5.11.0  | 6         | 6.38%   |
| 5.16.7  | 3         | 3.19%   |
| 5.10.0  | 3         | 3.19%   |
| 5.0.0   | 3         | 3.19%   |
| 4.19.0  | 2         | 2.13%   |
| 6.1.5   | 1         | 1.06%   |
| 6.1.1   | 1         | 1.06%   |
| 6.0.6   | 1         | 1.06%   |
| 6.0.14  | 1         | 1.06%   |
| 5.9.12  | 1         | 1.06%   |
| 5.9.11  | 1         | 1.06%   |
| 5.9.1   | 1         | 1.06%   |
| 5.8.8   | 1         | 1.06%   |
| 5.8.15  | 1         | 1.06%   |
| 5.8.12  | 1         | 1.06%   |
| 5.8.0   | 1         | 1.06%   |
| 5.7.10  | 1         | 1.06%   |
| 5.6.19  | 1         | 1.06%   |
| 5.4.60  | 1         | 1.06%   |
| 5.4.15  | 1         | 1.06%   |
| 5.19.7  | 1         | 1.06%   |
| 5.19.14 | 1         | 1.06%   |
| 5.19.12 | 1         | 1.06%   |
| 5.18.17 | 1         | 1.06%   |
| 5.18.13 | 1         | 1.06%   |
| 5.18.11 | 1         | 1.06%   |
| 5.17.4  | 1         | 1.06%   |
| 5.15.76 | 1         | 1.06%   |
| 5.13.13 | 1         | 1.06%   |
| 5.12.9  | 1         | 1.06%   |
| 5.12.14 | 1         | 1.06%   |
| 5.11.15 | 1         | 1.06%   |
| 5.11.12 | 1         | 1.06%   |
| 5.10.19 | 1         | 1.06%   |
| 5.10.14 | 1         | 1.06%   |
| 5.0.10  | 1         | 1.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 24.73%  |
| 5.15    | 9         | 9.68%   |
| 5.13    | 9         | 9.68%   |
| 5.11    | 8         | 8.6%    |
| 5.3     | 6         | 6.45%   |
| 5.10    | 5         | 5.38%   |
| 5.8     | 4         | 4.3%    |
| 5.0     | 4         | 4.3%    |
| 5.9     | 3         | 3.23%   |
| 5.19    | 3         | 3.23%   |
| 5.16    | 3         | 3.23%   |
| 4.19    | 3         | 3.23%   |
| 6.1     | 2         | 2.15%   |
| 6.0     | 2         | 2.15%   |
| 5.18    | 2         | 2.15%   |
| 5.12    | 2         | 2.15%   |
| 5.7     | 1         | 1.08%   |
| 5.6     | 1         | 1.08%   |
| 5.17    | 1         | 1.08%   |
| 4.18    | 1         | 1.08%   |
| 4.15    | 1         | 1.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 86        | 96.63%  |
| i686   | 3         | 3.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 42        | 46.67%  |
| KDE5       | 13        | 14.44%  |
| XFCE       | 8         | 8.89%   |
| Unknown    | 8         | 8.89%   |
| X-Cinnamon | 7         | 7.78%   |
| Budgie     | 4         | 4.44%   |
| KDE        | 3         | 3.33%   |
| sway       | 1         | 1.11%   |
| MATE       | 1         | 1.11%   |
| LXQt       | 1         | 1.11%   |
| LXDE       | 1         | 1.11%   |
| DWM        | 1         | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 73        | 80.22%  |
| Wayland | 14        | 15.38%  |
| Unknown | 4         | 4.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 48        | 53.93%  |
| SDDM    | 12        | 13.48%  |
| GDM     | 11        | 12.36%  |
| GDM3    | 8         | 8.99%   |
| LightDM | 6         | 6.74%   |
| TDM     | 4         | 4.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 52        | 57.14%  |
| es_DO   | 21        | 23.08%  |
| Unknown | 7         | 7.69%   |
| es_ES   | 4         | 4.4%    |
| es_MX   | 2         | 2.2%    |
| en_CA   | 2         | 2.2%    |
| ru_RU   | 1         | 1.1%    |
| fr_FR   | 1         | 1.1%    |
| C       | 1         | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 49        | 55.06%  |
| EFI  | 40        | 44.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 70        | 78.65%  |
| Btrfs   | 9         | 10.11%  |
| Overlay | 6         | 6.74%   |
| Xfs     | 2         | 2.25%   |
| F2fs    | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 49        | 55.06%  |
| GPT     | 32        | 35.96%  |
| MBR     | 8         | 8.99%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 83.33%  |
| Yes       | 15        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 70.79%  |
| Yes       | 26        | 29.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 30        | 33.71%  |
| Lenovo              | 16        | 17.98%  |
| Hewlett-Packard     | 12        | 13.48%  |
| ASUSTek Computer    | 7         | 7.87%   |
| Acer                | 5         | 5.62%   |
| Apple               | 4         | 4.49%   |
| Samsung Electronics | 2         | 2.25%   |
| MSI                 | 2         | 2.25%   |
| Google              | 2         | 2.25%   |
| EVOO                | 2         | 2.25%   |
| Toshiba             | 1         | 1.12%   |
| TODOS INDUSTRIAL    | 1         | 1.12%   |
| SAELITE             | 1         | 1.12%   |
| Nuvision            | 1         | 1.12%   |
| Fujitsu             | 1         | 1.12%   |
| Eluktronics         | 1         | 1.12%   |
| ECS                 | 1         | 1.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| EVOO EV-C-116-7                                   | 2         | 2.25%   |
| Dell Latitude E6540                               | 2         | 2.25%   |
| Dell Latitude E6430                               | 2         | 2.25%   |
| Dell Latitude E6420                               | 2         | 2.25%   |
| Dell Latitude E6410                               | 2         | 2.25%   |
| Dell Inspiron 5570                                | 2         | 2.25%   |
| Apple MacBookPro8,1                               | 2         | 2.25%   |
| Toshiba Satellite C55-A                           | 1         | 1.12%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 1.12%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 1.12%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 1.12%   |
| SAELITE ES1AU11                                   | 1         | 1.12%   |
| Nuvision NES11                                    | 1         | 1.12%   |
| MSI GE62 6QC                                      | 1         | 1.12%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 1.12%   |
| Lenovo Z50-75 80EC                                | 1         | 1.12%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 1.12%   |
| Lenovo ThinkPad T490 20N3S7BC02                   | 1         | 1.12%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 1.12%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 1.12%   |
| Lenovo ThinkPad T420s 41732BU                     | 1         | 1.12%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 1.12%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 1.12%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 1.12%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 1.12%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 1.12%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 1         | 1.12%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 1.12%   |
| Lenovo IdeaPad 3 15ALC6 82KU                      | 1         | 1.12%   |
| Lenovo G505s 20255                                | 1         | 1.12%   |
| Lenovo G40-70 20369                               | 1         | 1.12%   |
| HP ProBook 6470b                                  | 1         | 1.12%   |
| HP Pavilion ze2000 (EC201UA#ABA)                  | 1         | 1.12%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 1         | 1.12%   |
| HP Pavilion dv6                                   | 1         | 1.12%   |
| HP Notebook                                       | 1         | 1.12%   |
| HP Laptop 15-bw0xx                                | 1         | 1.12%   |
| HP G60                                            | 1         | 1.12%   |
| HP ENVY Laptop 13-ad0xx                           | 1         | 1.12%   |
| HP EliteBook 8540w                                | 1         | 1.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 18        | 20.22%  |
| Dell Inspiron              | 9         | 10.11%  |
| Lenovo ThinkPad            | 8         | 8.99%   |
| Acer Aspire                | 5         | 5.62%   |
| Lenovo IdeaPad             | 3         | 3.37%   |
| HP Pavilion                | 3         | 3.37%   |
| HP EliteBook               | 2         | 2.25%   |
| EVOO EV-C-116-7            | 2         | 2.25%   |
| Dell Vostro                | 2         | 2.25%   |
| ASUS VivoBook              | 2         | 2.25%   |
| Apple MacBookPro8          | 2         | 2.25%   |
| Toshiba Satellite          | 1         | 1.12%   |
| TODOS INDUSTRIAL Easytouch | 1         | 1.12%   |
| Samsung RV420              | 1         | 1.12%   |
| Samsung 905S3G             | 1         | 1.12%   |
| SAELITE ES1AU11            | 1         | 1.12%   |
| Nuvision NES11             | 1         | 1.12%   |
| MSI GE62                   | 1         | 1.12%   |
| MSI CR70                   | 1         | 1.12%   |
| Lenovo Z50-75              | 1         | 1.12%   |
| Lenovo ThinkBook           | 1         | 1.12%   |
| Lenovo Legion              | 1         | 1.12%   |
| Lenovo G505s               | 1         | 1.12%   |
| Lenovo G40-70              | 1         | 1.12%   |
| HP ProBook                 | 1         | 1.12%   |
| HP Notebook                | 1         | 1.12%   |
| HP Laptop                  | 1         | 1.12%   |
| HP G60                     | 1         | 1.12%   |
| HP ENVY                    | 1         | 1.12%   |
| HP 255                     | 1         | 1.12%   |
| HP 250                     | 1         | 1.12%   |
| Google Winky               | 1         | 1.12%   |
| Google Kip                 | 1         | 1.12%   |
| Fujitsu LIFEBOOK           | 1         | 1.12%   |
| Eluktronics P670RE3        | 1         | 1.12%   |
| ECS ClassMate              | 1         | 1.12%   |
| Dell XPS                   | 1         | 1.12%   |
| ASUS ZenBook               | 1         | 1.12%   |
| ASUS X553MA                | 1         | 1.12%   |
| ASUS TUF                   | 1         | 1.12%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 10        | 11.24%  |
| 2011 | 10        | 11.24%  |
| 2014 | 9         | 10.11%  |
| 2013 | 9         | 10.11%  |
| 2019 | 8         | 8.99%   |
| 2012 | 8         | 8.99%   |
| 2020 | 5         | 5.62%   |
| 2008 | 5         | 5.62%   |
| 2021 | 4         | 4.49%   |
| 2018 | 4         | 4.49%   |
| 2010 | 4         | 4.49%   |
| 2015 | 3         | 3.37%   |
| 2009 | 3         | 3.37%   |
| 2016 | 2         | 2.25%   |
| 2007 | 2         | 2.25%   |
| 2022 | 1         | 1.12%   |
| 2006 | 1         | 1.12%   |
| 2005 | 1         | 1.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 89        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 85        | 95.51%  |
| Enabled  | 4         | 4.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 87        | 97.75%  |
| Yes  | 2         | 2.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 28        | 31.46%  |
| 4.01-8.0   | 23        | 25.84%  |
| 8.01-16.0  | 15        | 16.85%  |
| 16.01-24.0 | 11        | 12.36%  |
| 2.01-3.0   | 4         | 4.49%   |
| 1.01-2.0   | 4         | 4.49%   |
| 32.01-64.0 | 3         | 3.37%   |
| 24.01-32.0 | 1         | 1.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 36        | 37.11%  |
| 2.01-3.0  | 27        | 27.84%  |
| 3.01-4.0  | 18        | 18.56%  |
| 4.01-8.0  | 9         | 9.28%   |
| 0.51-1.0  | 6         | 6.19%   |
| 8.01-16.0 | 1         | 1.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 75.28%  |
| 2      | 22        | 24.72%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 53.93%  |
| Yes       | 41        | 46.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 84.27%  |
| No        | 14        | 15.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 97.75%  |
| No        | 2         | 2.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 70%     |
| No        | 27        | 30%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 89        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 58        | 63.74%  |
| Santiago de los Caballeros | 9         | 9.89%   |
| La Romana                  | 4         | 4.4%    |
| Santo Domingo              | 3         | 3.3%    |
| Santa Cruz de Barahona     | 2         | 2.2%    |
| Alejandro Bass             | 2         | 2.2%    |
| Sosua, Cabarete            | 1         | 1.1%    |
| Santo Domingo Oeste        | 1         | 1.1%    |
| San Pedro de Macorís      | 1         | 1.1%    |
| San Cristobal              | 1         | 1.1%    |
| Punta Cana                 | 1         | 1.1%    |
| Los Hidalgos               | 1         | 1.1%    |
| Guaymate                   | 1         | 1.1%    |
| Constanza                  | 1         | 1.1%    |
| Concepción de la Vega     | 1         | 1.1%    |
| Cancino                    | 1         | 1.1%    |
| Boca Chica                 | 1         | 1.1%    |
| Baní                      | 1         | 1.1%    |
| Bajos de Haina             | 1         | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 20        | 25     | 19.05%  |
| Samsung Electronics       | 12        | 13     | 11.43%  |
| WDC                       | 10        | 13     | 9.52%   |
| Toshiba                   | 10        | 12     | 9.52%   |
| SanDisk                   | 8         | 11     | 7.62%   |
| Hitachi                   | 8         | 9      | 7.62%   |
| Kingston                  | 6         | 6      | 5.71%   |
| Unknown                   | 5         | 6      | 4.76%   |
| SK hynix                  | 5         | 6      | 4.76%   |
| Unknown                   | 3         | 3      | 2.86%   |
| Transcend                 | 2         | 2      | 1.9%    |
| Micron Technology         | 2         | 2      | 1.9%    |
| FORESEE                   | 2         | 2      | 1.9%    |
| UMIS                      | 1         | 1      | 0.95%   |
| SPCC                      | 1         | 1      | 0.95%   |
| PNY                       | 1         | 1      | 0.95%   |
| OCZ                       | 1         | 1      | 0.95%   |
| Micron/Crucial Technology | 1         | 1      | 0.95%   |
| LITEONIT                  | 1         | 2      | 0.95%   |
| Intel                     | 1         | 1      | 0.95%   |
| Indilinx                  | 1         | 1      | 0.95%   |
| Hewlett-Packard           | 1         | 1      | 0.95%   |
| Eluktro                   | 1         | 1      | 0.95%   |
| China                     | 1         | 2      | 0.95%   |
| A-DATA Technology         | 1         | 1      | 0.95%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Seagate ST500LM000-1EJ162 500GB | 3         | 2.8%    |
| Unknown                         | 3         | 2.8%    |
| Unknown MMC Card  32GB          | 2         | 1.87%   |
| Unknown MMC Card  16GB          | 2         | 1.87%   |
| Toshiba MQ01ACF050 500GB        | 2         | 1.87%   |
| Toshiba MK3275GSX 320GB         | 2         | 1.87%   |
| Seagate ST9250315AS 250GB       | 2         | 1.87%   |
| Seagate ST1000LM049-2GH172 1TB  | 2         | 1.87%   |
| Seagate ST1000LM035-1RK172 1TB  | 2         | 1.87%   |
| SanDisk NVMe SSD Drive 256GB    | 2         | 1.87%   |
| Samsung SSD 860 EVO 500GB       | 2         | 1.87%   |
| Kingston SA400S37240G 240GB SSD | 2         | 1.87%   |
| FORESEE 128GB SSD               | 2         | 1.87%   |
| WDC WDS100T2G0A-00JH30 1TB SSD  | 1         | 0.93%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1         | 0.93%   |
| WDC WD3200LPVX-75V0TT0 320GB    | 1         | 0.93%   |
| WDC WD3200BEVT-75A23T0 320GB    | 1         | 0.93%   |
| WDC WD2500BEVT-75A23T0 250GB    | 1         | 0.93%   |
| WDC WD2500BEVS-22UST0 250GB     | 1         | 0.93%   |
| WDC WD1600BEVT-75ZCT1 160GB     | 1         | 0.93%   |
| WDC WD10SPZX-24Z10T0 1TB        | 1         | 0.93%   |
| WDC WD10JPVX-60JC3T1 1TB        | 1         | 0.93%   |
| WDC WD10JPCX-24UE4T0 1TB        | 1         | 0.93%   |
| Unknown MMC Card  64GB          | 1         | 0.93%   |
| Unknown MMC Card  128GB         | 1         | 0.93%   |
| UMIS RPJTJ256MEE1OWX 256GB      | 1         | 0.93%   |
| Transcend TS256GSSD340 256GB    | 1         | 0.93%   |
| Transcend TS128GSSD370S 128GB   | 1         | 0.93%   |
| Toshiba NVMe SSD Drive 1024GB   | 1         | 0.93%   |
| Toshiba MQ01ABF050 500GB        | 1         | 0.93%   |
| Toshiba MQ01ABD100 1TB          | 1         | 0.93%   |
| Toshiba MK6475GSX 640GB         | 1         | 0.93%   |
| Toshiba MK3276GSX 320GB         | 1         | 0.93%   |
| Toshiba MK2556GSY 250GB         | 1         | 0.93%   |
| SPCC Solid State Disk 512GB     | 1         | 0.93%   |
| SK hynix SC311 SATA 256GB SSD   | 1         | 0.93%   |
| SK hynix NVMe SSD Drive 256GB   | 1         | 0.93%   |
| SK hynix HCG8e  64GB            | 1         | 0.93%   |
| SK hynix C2S3T/240G 240GB SSD   | 1         | 0.93%   |
| SK hynix BC711 NVMe 512GB       | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 25     | 42.55%  |
| WDC                 | 9         | 12     | 19.15%  |
| Toshiba             | 9         | 11     | 19.15%  |
| Hitachi             | 8         | 9      | 17.02%  |
| Samsung Electronics | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 20.59%  |
| SanDisk             | 6         | 9      | 17.65%  |
| Kingston            | 5         | 5      | 14.71%  |
| Transcend           | 2         | 2      | 5.88%   |
| SK hynix            | 2         | 2      | 5.88%   |
| FORESEE             | 2         | 2      | 5.88%   |
| WDC                 | 1         | 1      | 2.94%   |
| SPCC                | 1         | 1      | 2.94%   |
| PNY                 | 1         | 1      | 2.94%   |
| OCZ                 | 1         | 1      | 2.94%   |
| LITEONIT            | 1         | 2      | 2.94%   |
| Hewlett-Packard     | 1         | 1      | 2.94%   |
| Eluktro             | 1         | 1      | 2.94%   |
| China               | 1         | 2      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |
| Unknown             | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 45        | 58     | 45%     |
| SSD     | 31        | 40     | 31%     |
| NVMe    | 15        | 16     | 15%     |
| MMC     | 8         | 9      | 8%      |
| Unknown | 1         | 1      | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 70        | 95     | 72.92%  |
| NVMe | 15        | 16     | 15.63%  |
| MMC  | 8         | 9      | 8.33%   |
| SAS  | 3         | 4      | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 55        | 74     | 74.32%  |
| 0.51-1.0   | 17        | 21     | 22.97%  |
| 3.01-4.0   | 1         | 2      | 1.35%   |
| 1.01-2.0   | 1         | 1      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 33.7%   |
| 251-500        | 18        | 19.57%  |
| 501-1000       | 16        | 17.39%  |
| 1-20           | 8         | 8.7%    |
| 51-100         | 7         | 7.61%   |
| 21-50          | 4         | 4.35%   |
| 1001-2000      | 4         | 4.35%   |
| Unknown        | 2         | 2.17%   |
| More than 3000 | 1         | 1.09%   |
| 2001-3000      | 1         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 39        | 39%     |
| 21-50     | 21        | 21%     |
| 51-100    | 16        | 16%     |
| 101-250   | 12        | 12%     |
| 251-500   | 4         | 4%      |
| 501-1000  | 3         | 3%      |
| 1001-2000 | 2         | 2%      |
| Unknown   | 2         | 2%      |
| 2001-3000 | 1         | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba MK3276GSX 320GB           | 1         | 1      | 11.11%  |
| Toshiba MK3275GSX 320GB           | 1         | 1      | 11.11%  |
| Seagate ST9750420AS 752GB         | 1         | 1      | 11.11%  |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 11.11%  |
| Seagate ST2000LM007-1R8174 2TB    | 1         | 1      | 11.11%  |
| Samsung Electronics HM500LI 500GB | 1         | 1      | 11.11%  |
| Hitachi HTS727550A9E364 500GB     | 1         | 1      | 11.11%  |
| Hitachi HTS725032A9A364 320GB     | 1         | 1      | 11.11%  |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 33.33%  |
| Hitachi             | 3         | 3      | 33.33%  |
| Toshiba             | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 33.33%  |
| Hitachi             | 3         | 3      | 33.33%  |
| Toshiba             | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 100%    |

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
| Detected | 56        | 84     | 60.87%  |
| Works    | 27        | 31     | 29.35%  |
| Malfunc  | 9         | 9      | 9.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 65        | 69.15%  |
| AMD                          | 14        | 14.89%  |
| Samsung Electronics          | 4         | 4.26%   |
| SK hynix                     | 2         | 2.13%   |
| SanDisk                      | 2         | 2.13%   |
| Micron Technology            | 2         | 2.13%   |
| Union Memory (Shenzhen)      | 1         | 1.06%   |
| Toshiba America Info Systems | 1         | 1.06%   |
| Nvidia                       | 1         | 1.06%   |
| Micron/Crucial Technology    | 1         | 1.06%   |
| Kingston Technology Company  | 1         | 1.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 13        | 13%     |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 9%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 8         | 8%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 7         | 7%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 7%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 4         | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 4%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 3%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 3%      |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 2         | 2%      |
| Micron Non-Volatile memory controller                                                  | 2         | 2%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 2%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 2%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 2         | 2%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 2%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 2%      |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1%      |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1%      |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 1%      |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1%      |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 1%      |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1%      |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 1%      |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 1%      |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1%      |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 1%      |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 1%      |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 1%      |
| AMD FCH IDE Controller                                                                 | 1         | 1%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 61        | 63.54%  |
| NVMe | 15        | 15.63%  |
| RAID | 10        | 10.42%  |
| IDE  | 10        | 10.42%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 74        | 83.15%  |
| AMD    | 15        | 16.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 4.49%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 4.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 3.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.25%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 2.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 2.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.25%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 2.25%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 2.25%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 2.25%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 2         | 2.25%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 2.25%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 2.25%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 2.25%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.12%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.12%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.12%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 1.12%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 1.12%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.12%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.12%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 1.12%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.12%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.12%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.12%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.12%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.12%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.12%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 1.12%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 1.12%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.12%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.12%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.12%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.12%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 1         | 1.12%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 28        | 31.46%  |
| Intel Core i7           | 13        | 14.61%  |
| Intel Celeron           | 12        | 13.48%  |
| Intel Core i3           | 7         | 7.87%   |
| Intel Core 2 Duo        | 4         | 4.49%   |
| AMD Ryzen 5             | 3         | 3.37%   |
| Intel Core 2            | 2         | 2.25%   |
| Intel Atom              | 2         | 2.25%   |
| AMD Ryzen 7             | 2         | 2.25%   |
| AMD A8                  | 2         | 2.25%   |
| AMD A6                  | 2         | 2.25%   |
| AMD A10                 | 2         | 2.25%   |
| Other                   | 1         | 1.12%   |
| Intel Pentium Dual-Core | 1         | 1.12%   |
| Intel Pentium Dual      | 1         | 1.12%   |
| Intel Pentium           | 1         | 1.12%   |
| Intel Genuine           | 1         | 1.12%   |
| Intel Core i9           | 1         | 1.12%   |
| AMD Quad-Core           | 1         | 1.12%   |
| AMD Mobile Sempron      | 1         | 1.12%   |
| AMD A4                  | 1         | 1.12%   |
| AMD A12                 | 1         | 1.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 61        | 68.54%  |
| 4      | 22        | 24.72%  |
| 8      | 2         | 2.25%   |
| 6      | 2         | 2.25%   |
| 1      | 2         | 2.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 89        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 57        | 64.04%  |
| 1      | 32        | 35.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 87        | 97.75%  |
| 32-bit         | 1         | 1.12%   |
| Unknown        | 1         | 1.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 17.78%  |
| 0x206a7    | 10        | 11.11%  |
| 0x306a9    | 7         | 7.78%   |
| 0x806e9    | 5         | 5.56%   |
| 0x40651    | 5         | 5.56%   |
| 0x806ea    | 4         | 4.44%   |
| 0x706a1    | 4         | 4.44%   |
| 0x1067a    | 4         | 4.44%   |
| 0x306c3    | 3         | 3.33%   |
| 0x30678    | 3         | 3.33%   |
| 0x07030105 | 3         | 3.33%   |
| 0x806ec    | 2         | 2.22%   |
| 0x6f6      | 2         | 2.22%   |
| 0x506e3    | 2         | 2.22%   |
| 0x20652    | 2         | 2.22%   |
| 0x10676    | 2         | 2.22%   |
| 0x806c1    | 1         | 1.11%   |
| 0x6fd      | 1         | 1.11%   |
| 0x506c9    | 1         | 1.11%   |
| 0x406c3    | 1         | 1.11%   |
| 0x20655    | 1         | 1.11%   |
| 0x106ca    | 1         | 1.11%   |
| 0x08608103 | 1         | 1.11%   |
| 0x08608102 | 1         | 1.11%   |
| 0x08600103 | 1         | 1.11%   |
| 0x08108109 | 1         | 1.11%   |
| 0x08108102 | 1         | 1.11%   |
| 0x0700010f | 1         | 1.11%   |
| 0x06006705 | 1         | 1.11%   |
| 0x0600611a | 1         | 1.11%   |
| 0x06003106 | 1         | 1.11%   |
| 0x06001119 | 1         | 1.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 17.98%  |
| SandyBridge   | 10        | 11.24%  |
| IvyBridge     | 9         | 10.11%  |
| Haswell       | 9         | 10.11%  |
| Silvermont    | 6         | 6.74%   |
| Penryn        | 6         | 6.74%   |
| Westmere      | 5         | 5.62%   |
| Goldmont plus | 5         | 5.62%   |
| Puma          | 3         | 3.37%   |
| Core          | 3         | 3.37%   |
| Zen+          | 2         | 2.25%   |
| Skylake       | 2         | 2.25%   |
| Excavator     | 2         | 2.25%   |
| Unknown       | 2         | 2.25%   |
| Zen 2         | 1         | 1.12%   |
| TigerLake     | 1         | 1.12%   |
| Steamroller   | 1         | 1.12%   |
| Piledriver    | 1         | 1.12%   |
| K8 Hammer     | 1         | 1.12%   |
| K10 Llano     | 1         | 1.12%   |
| Jaguar        | 1         | 1.12%   |
| Goldmont      | 1         | 1.12%   |
| Bonnell       | 1         | 1.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 67.65%  |
| AMD    | 20        | 19.61%  |
| Nvidia | 13        | 12.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 8.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 8.41%   |
| Intel UHD Graphics 620                                                                   | 6         | 5.61%   |
| Intel HD Graphics 620                                                                    | 5         | 4.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 4.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 4.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 4.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.8%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.87%   |
| Intel HD Graphics 530                                                                    | 2         | 1.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.87%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.87%   |
| AMD Lucienne                                                                             | 2         | 1.87%   |
| Nvidia TU117M                                                                            | 1         | 0.93%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.93%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.93%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 1         | 0.93%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.93%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.93%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.93%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 0.93%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 0.93%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.93%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.93%   |
| Intel HD Graphics 500                                                                    | 1         | 0.93%   |
| Intel Haswell Integrated Graphics Controller                                             | 1         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.93%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.93%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.93%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.93%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 58        | 65.17%  |
| 1 x AMD        | 12        | 13.48%  |
| Intel + Nvidia | 7         | 7.87%   |
| 1 x Nvidia     | 4         | 4.49%   |
| Intel + AMD    | 4         | 4.49%   |
| 2 x AMD        | 2         | 2.25%   |
| AMD + Nvidia   | 2         | 2.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 82        | 92.13%  |
| Proprietary | 6         | 6.74%   |
| Unknown     | 1         | 1.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 71.91%  |
| 0.01-0.5   | 9         | 10.11%  |
| 1.01-2.0   | 7         | 7.87%   |
| 0.51-1.0   | 6         | 6.74%   |
| 3.01-4.0   | 2         | 2.25%   |
| 2.01-3.0   | 1         | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 18.63%  |
| LG Display              | 15        | 14.71%  |
| BOE                     | 15        | 14.71%  |
| Chimei Innolux          | 13        | 12.75%  |
| Samsung Electronics     | 11        | 10.78%  |
| Dell                    | 6         | 5.88%   |
| Chi Mei Optoelectronics | 5         | 4.9%    |
| Apple                   | 4         | 3.92%   |
| Hewlett-Packard         | 2         | 1.96%   |
| ZTR                     | 1         | 0.98%   |
| Westinghouse            | 1         | 0.98%   |
| Vizio                   | 1         | 0.98%   |
| Unknown (XXX)           | 1         | 0.98%   |
| Sony                    | 1         | 0.98%   |
| Philips                 | 1         | 0.98%   |
| PANDA                   | 1         | 0.98%   |
| LG Philips              | 1         | 0.98%   |
| Lenovo                  | 1         | 0.98%   |
| KDC                     | 1         | 0.98%   |
| InnoLux Display         | 1         | 0.98%   |
| Goldstar                | 1         | 0.98%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 2.94%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 1.96%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 2         | 1.96%   |
| ZTR LCD Monitor ZTR0001 1366x768 309x173mm 13.9-inch                  | 1         | 0.98%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch          | 1         | 0.98%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1         | 0.98%   |
| Unknown (XXX) Philco XXX0030 1600x1200 708x398mm 32.0-inch            | 1         | 0.98%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                         | 1         | 0.98%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch  | 1         | 0.98%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch             | 1         | 0.98%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch               | 1         | 0.98%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD0357 1600x900 382x215mm 17.3-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 0.98%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch               | 1         | 0.98%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 1         | 0.98%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch      | 1         | 0.98%   |
| Hewlett-Packard E221c HWP3093 1920x1080 497x292mm 22.7-inch           | 1         | 0.98%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch             | 1         | 0.98%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                 | 1         | 0.98%   |
| Dell P2212H DELA07E 1920x1080 531x299mm 24.0-inch                     | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 43        | 45.26%  |
| 1920x1080 (FHD)    | 29        | 30.53%  |
| 1280x800 (WXGA)    | 7         | 7.37%   |
| 1600x900 (HD+)     | 6         | 6.32%   |
| 3840x2160 (4K)     | 2         | 2.11%   |
| 1280x1024 (SXGA)   | 2         | 2.11%   |
| 3840x1100          | 1         | 1.05%   |
| 1680x1050 (WSXGA+) | 1         | 1.05%   |
| 1360x768           | 1         | 1.05%   |
| 1280x768           | 1         | 1.05%   |
| 1024x768 (XGA)     | 1         | 1.05%   |
| 1024x600           | 1         | 1.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 44        | 43.56%  |
| 13      | 17        | 16.83%  |
| 14      | 13        | 12.87%  |
| 11      | 7         | 6.93%   |
| 17      | 4         | 3.96%   |
| 24      | 2         | 1.98%   |
| 22      | 2         | 1.98%   |
| 21      | 2         | 1.98%   |
| 72      | 1         | 0.99%   |
| 40      | 1         | 0.99%   |
| 34      | 1         | 0.99%   |
| 32      | 1         | 0.99%   |
| 31      | 1         | 0.99%   |
| 23      | 1         | 0.99%   |
| 20      | 1         | 0.99%   |
| 19      | 1         | 0.99%   |
| 10      | 1         | 0.99%   |
| Unknown | 1         | 0.99%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 62        | 62.63%  |
| 201-300     | 16        | 16.16%  |
| 351-400     | 7         | 7.07%   |
| 401-500     | 5         | 5.05%   |
| 501-600     | 3         | 3.03%   |
| 701-800     | 2         | 2.02%   |
| 801-900     | 1         | 1.01%   |
| 601-700     | 1         | 1.01%   |
| 1501-2000   | 1         | 1.01%   |
| Unknown     | 1         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 76        | 85.39%  |
| 16/10   | 8         | 8.99%   |
| 5/4     | 2         | 2.25%   |
| 4/3     | 1         | 1.12%   |
| 3.40    | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 44        | 43.56%  |
| 81-90          | 24        | 23.76%  |
| 51-60          | 8         | 7.92%   |
| 201-250        | 7         | 6.93%   |
| 71-80          | 5         | 4.95%   |
| 121-130        | 3         | 2.97%   |
| 351-500        | 2         | 1.98%   |
| 151-200        | 2         | 1.98%   |
| 501-1000       | 2         | 1.98%   |
| More than 1000 | 1         | 0.99%   |
| 41-50          | 1         | 0.99%   |
| 141-150        | 1         | 0.99%   |
| Unknown        | 1         | 0.99%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 45        | 45.92%  |
| 121-160       | 31        | 31.63%  |
| 51-100        | 15        | 15.31%  |
| 1-50          | 3         | 3.06%   |
| 161-240       | 2         | 2.04%   |
| More than 240 | 1         | 1.02%   |
| Unknown       | 1         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 72        | 80%     |
| 2     | 15        | 16.67%  |
| 0     | 2         | 2.22%   |
| 3     | 1         | 1.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 33.09%  |
| Realtek Semiconductor           | 42        | 30.22%  |
| Qualcomm Atheros                | 22        | 15.83%  |
| Broadcom                        | 13        | 9.35%   |
| Broadcom Limited                | 3         | 2.16%   |
| Ralink Technology               | 2         | 1.44%   |
| Qualcomm Atheros Communications | 2         | 1.44%   |
| Marvell Technology Group        | 2         | 1.44%   |
| Lenovo                          | 2         | 1.44%   |
| Nvidia                          | 1         | 0.72%   |
| MediaTek                        | 1         | 0.72%   |
| JCM                             | 1         | 0.72%   |
| Dell                            | 1         | 0.72%   |
| AMD                             | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 11.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 7.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 4.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 4.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 2.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.91%   |
| Intel Wireless 7260                                               | 5         | 2.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 2.33%   |
| Intel Wireless 3165                                               | 4         | 2.33%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.74%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.74%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.74%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.16%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 1.16%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 1.16%   |
| Lenovo Thinkpad LAN                                               | 2         | 1.16%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.16%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.16%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.16%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.16%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.16%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.58%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.58%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.58%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.58%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 47.83%  |
| Qualcomm Atheros                | 19        | 20.65%  |
| Realtek Semiconductor           | 12        | 13.04%  |
| Broadcom                        | 10        | 10.87%  |
| Ralink Technology               | 2         | 2.17%   |
| Qualcomm Atheros Communications | 2         | 2.17%   |
| MediaTek                        | 1         | 1.09%   |
| Dell                            | 1         | 1.09%   |
| Broadcom Limited                | 1         | 1.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 7         | 7.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 5.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 5         | 5.38%   |
| Intel Wireless 7260                                                                   | 5         | 5.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 4.3%    |
| Intel Wireless 3165                                                                   | 4         | 4.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 3.23%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 3.23%   |
| Intel Centrino Advanced-N 6235                                                        | 3         | 3.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 3.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 2.15%   |
| Realtek 802.11n WLAN Adapter                                                          | 2         | 2.15%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 2.15%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 2.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 2.15%   |
| Intel Centrino Wireless-N 2230                                                        | 2         | 2.15%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.15%   |
| Intel Centrino Advanced-N 6200                                                        | 2         | 2.15%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 2.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.08%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.08%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 1.08%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.08%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 1.08%   |
| Intel Wireless 8260                                                                   | 1         | 1.08%   |
| Intel Wireless 7265                                                                   | 1         | 1.08%   |
| Intel Wireless 3160                                                                   | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.08%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.08%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 1.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 35        | 45.45%  |
| Intel                    | 24        | 31.17%  |
| Broadcom                 | 6         | 7.79%   |
| Qualcomm Atheros         | 5         | 6.49%   |
| Marvell Technology Group | 2         | 2.6%    |
| Lenovo                   | 2         | 2.6%    |
| Broadcom Limited         | 2         | 2.6%    |
| Nvidia                   | 1         | 1.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 24.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 16.88%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 10.39%  |
| Intel 82577LM Gigabit Network Connection                          | 4         | 5.19%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.6%    |
| Lenovo Thinkpad LAN                                               | 2         | 2.6%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.3%    |
| Nvidia MCP79 Ethernet                                             | 1         | 1.3%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.3%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.3%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.3%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.3%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.3%    |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.3%    |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 1.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.3%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.3%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.3%    |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 1.3%    |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 1.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 87        | 53.05%  |
| Ethernet | 75        | 45.73%  |
| Modem    | 2         | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 70        | 76.09%  |
| Ethernet | 22        | 23.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 72        | 80.9%   |
| 1     | 14        | 15.73%  |
| 0     | 3         | 3.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 87        | 96.67%  |
| Yes  | 3         | 3.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 44.44%  |
| Qualcomm Atheros Communications | 10        | 15.87%  |
| Dell                            | 6         | 9.52%   |
| IMC Networks                    | 5         | 7.94%   |
| Realtek Semiconductor           | 4         | 6.35%   |
| Apple                           | 4         | 6.35%   |
| Broadcom                        | 3         | 4.76%   |
| Lite-On Technology              | 2         | 3.17%   |
| Hewlett-Packard                 | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 15        | 23.81%  |
| Qualcomm Atheros  Bluetooth Device             | 5         | 7.94%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 5         | 7.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 3         | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 4.76%   |
| IMC Networks Bluetooth Radio                   | 3         | 4.76%   |
| Dell BCM20702A0 Bluetooth Module               | 3         | 4.76%   |
| Apple Bluetooth Host Controller                | 3         | 4.76%   |
| Realtek Bluetooth Radio                        | 2         | 3.17%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 3.17%   |
| Intel AX200 Bluetooth                          | 2         | 3.17%   |
| Realtek RTL8723B Bluetooth                     | 1         | 1.59%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 1.59%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 1.59%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 1.59%   |
| Lite-On Wireless_Device                        | 1         | 1.59%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 1.59%   |
| Intel Bluetooth Device                         | 1         | 1.59%   |
| IMC Networks Bluetooth Device                  | 1         | 1.59%   |
| IMC Networks Bluetooth                         | 1         | 1.59%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 1.59%   |
| Dell Wireless 360 Bluetooth                    | 1         | 1.59%   |
| Dell Wireless 355 Bluetooth                    | 1         | 1.59%   |
| Dell Wireless 350 Bluetooth                    | 1         | 1.59%   |
| Broadcom HP Portable SoftSailing               | 1         | 1.59%   |
| Broadcom BCM43142 Bluetooth 4.0                | 1         | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 1.59%   |
| Apple Bluetooth HCI                            | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 72        | 72%     |
| AMD                 | 16        | 16%     |
| Nvidia              | 8         | 8%      |
| Logitech            | 2         | 2%      |
| Sony                | 1         | 1%      |
| C-Media Electronics | 1         | 1%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 9.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 8.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 7.44%   |
| AMD FCH Azalia Controller                                                                         | 7         | 5.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 4.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 4.13%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 4.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 4.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 4.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 3.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 3.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 2.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.48%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 2.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.65%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.83%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.83%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.83%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.83%   |
| Logitech Logi USB Headset                                                                         | 1         | 0.83%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.83%   |
| C-Media Electronics USB PnP Sound Device                                                          | 1         | 0.83%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.83%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.83%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 1         | 0.83%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 19        | 33.93%  |
| Samsung Electronics | 14        | 25%     |
| Micron Technology   | 7         | 12.5%   |
| Crucial             | 3         | 5.36%   |
| Unknown (ABCD)      | 2         | 3.57%   |
| Unknown             | 2         | 3.57%   |
| Ramaxel Technology  | 2         | 3.57%   |
| Nanya Technology    | 2         | 3.57%   |
| Kingston            | 2         | 3.57%   |
| Sesame              | 1         | 1.79%   |
| A-DATA Technology   | 1         | 1.79%   |
| Unknown             | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.39%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 3.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.39%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 3.39%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 3.39%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.69%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.69%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.69%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.69%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 1.69%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.69%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.69%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.69%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 1         | 1.69%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.69%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.69%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 2667MT/s                | 1         | 1.69%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.69%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.69%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 1.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.69%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.69%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.69%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.69%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.69%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.69%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.69%   |
| Ramaxel RAM RMT3010EC58E8F1333 2048MB SODIMM DDR3 1600MT/s       | 1         | 1.69%   |
| Ramaxel RAM RMT1970ED48E8F1066 2048MB SODIMM DDR3 1067MT/s       | 1         | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 18        | 40.91%  |
| DDR4   | 16        | 36.36%  |
| LPDDR4 | 4         | 9.09%   |
| SDRAM  | 3         | 6.82%   |
| DDR2   | 2         | 4.55%   |
| LPDDR3 | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 93.18%  |
| Row Of Chips | 2         | 4.55%   |
| DIMM         | 1         | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 19        | 39.58%  |
| 8192  | 14        | 29.17%  |
| 2048  | 9         | 18.75%  |
| 16384 | 6         | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 15        | 30%     |
| 2667  | 9         | 18%     |
| 2400  | 7         | 14%     |
| 1333  | 4         | 8%      |
| 3200  | 3         | 6%      |
| 4199  | 2         | 4%      |
| 2133  | 2         | 4%      |
| 1334  | 2         | 4%      |
| 3266  | 1         | 2%      |
| 2048  | 1         | 2%      |
| 1867  | 1         | 2%      |
| 1067  | 1         | 2%      |
| 975   | 1         | 2%      |
| 667   | 1         | 2%      |

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
| Chicony Electronics                    | 13        | 17.33%  |
| Microdia                               | 10        | 13.33%  |
| Sunplus Innovation Technology          | 8         | 10.67%  |
| IMC Networks                           | 7         | 9.33%   |
| Suyin                                  | 6         | 8%      |
| Realtek Semiconductor                  | 6         | 8%      |
| Syntek                                 | 4         | 5.33%   |
| Apple                                  | 4         | 5.33%   |
| Silicon Motion                         | 3         | 4%      |
| Ricoh                                  | 3         | 4%      |
| Quanta                                 | 2         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.67%   |
| Sonix Technology                       | 1         | 1.33%   |
| Primax Electronics                     | 1         | 1.33%   |
| OmniVision Technologies                | 1         | 1.33%   |
| Logitech                               | 1         | 1.33%   |
| globaloptics                           | 1         | 1.33%   |
| Alcor Micro                            | 1         | 1.33%   |
| Acer                                   | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD               | 5         | 6.67%   |
| Chicony integrated camera                  | 4         | 5.33%   |
| IMC Networks Integrated Camera             | 3         | 4%      |
| Syntek Lenovo EasyCamera                   | 2         | 2.67%   |
| Microdia Sonix USB 2.0 Camera              | 2         | 2.67%   |
| Microdia Integrated_Webcam_HD              | 2         | 2.67%   |
| Microdia Integrated Webcam                 | 2         | 2.67%   |
| Microdia Dell Integrated HD Webcam         | 2         | 2.67%   |
| IMC Networks USB2.0 HD UVC WebCam          | 2         | 2.67%   |
| Apple FaceTime HD Camera                   | 2         | 2.67%   |
| Syntek Integrated Camera                   | 1         | 1.33%   |
| Syntek EasyCamera                          | 1         | 1.33%   |
| Suyin VGA Webcam                           | 1         | 1.33%   |
| Suyin TOSHIBA Web Camera - HD              | 1         | 1.33%   |
| Suyin Laptop_Integrated_Webcam_HD          | 1         | 1.33%   |
| Suyin HP TrueVision HD                     | 1         | 1.33%   |
| Suyin Acer/Lenovo Webcam [CN0316]          | 1         | 1.33%   |
| Suyin 1.3M HD WebCam                       | 1         | 1.33%   |
| Sunplus Laptop_Integrated_Webcam_HD        | 1         | 1.33%   |
| Sunplus Laptop_Integrated_Webcam_FHD       | 1         | 1.33%   |
| Sunplus Integrated_Webcam_FHD              | 1         | 1.33%   |
| Sonix HP Webcam-101                        | 1         | 1.33%   |
| Silicon Motion WebCam SCB-0385N            | 1         | 1.33%   |
| Silicon Motion WebCam SC-10HDD13335N       | 1         | 1.33%   |
| Silicon Motion Real HD WebCam              | 1         | 1.33%   |
| Ricoh Laptop_Integrated_Webcam_FHD         | 1         | 1.33%   |
| Ricoh Integrated Webcam                    | 1         | 1.33%   |
| Ricoh HD Webcam                            | 1         | 1.33%   |
| Realtek MTD camera                         | 1         | 1.33%   |
| Realtek Integrated Webcam HD               | 1         | 1.33%   |
| Realtek Integrated Webcam                  | 1         | 1.33%   |
| Realtek Integrated Camera                  | 1         | 1.33%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.33%   |
| Realtek HP Truevision HD integrated webcam | 1         | 1.33%   |
| Quanta HP Webcam                           | 1         | 1.33%   |
| Quanta HP TrueVision HD Webcam             | 1         | 1.33%   |
| Primax HP HD Webcam [Fixed]                | 1         | 1.33%   |
| OmniVision OV2640 Webcam                   | 1         | 1.33%   |
| Microdia Laptop_Integrated_Webcam_E4HD     | 1         | 1.33%   |
| Microdia Laptop_Integrated_Webcam_2M       | 1         | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 50%     |
| Synaptics                  | 3         | 25%     |
| STMicroelectronics         | 1         | 8.33%   |
| Shenzhen Goodix Technology | 1         | 8.33%   |
| LighTuning Technology      | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 8.33%   |
| Validity Sensors VFS491                           | 1         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                   | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner              | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 8.33%   |
| STMicroelectronics Fingerprint Reader             | 1         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 8.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 70%     |
| O2 Micro    | 2         | 20%     |
| Alcor Micro | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 20%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom 58200                                                               | 1         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 61        | 68.54%  |
| 1     | 24        | 26.97%  |
| 2     | 4         | 4.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 12        | 37.5%   |
| Chipcard              | 8         | 25%     |
| Graphics card         | 5         | 15.63%  |
| Storage               | 2         | 6.25%   |
| Multimedia controller | 2         | 6.25%   |
| Net/wireless          | 1         | 3.13%   |
| Card reader           | 1         | 3.13%   |
| Bluetooth             | 1         | 3.13%   |

