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

Total: 126

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 16        | 18.82%  |
| Ubuntu 18.04        | 7         | 8.24%   |
| Ubuntu 22.04        | 4         | 4.71%   |
| Fedora 36           | 4         | 4.71%   |
| Debian 11           | 3         | 3.53%   |
| Ubuntu 21.10        | 2         | 2.35%   |
| Pop!_OS 20.10       | 2         | 2.35%   |
| OpenMandriva 4.3    | 2         | 2.35%   |
| OpenMandriva 4.2    | 2         | 2.35%   |
| Linux Mint 20.3     | 2         | 2.35%   |
| Linux Mint 20.1     | 2         | 2.35%   |
| ArcoLinux Rolling   | 2         | 2.35%   |
| Zorin 16            | 1         | 1.18%   |
| Xubuntu 19.10       | 1         | 1.18%   |
| Xubuntu 18.04       | 1         | 1.18%   |
| Void Linux Rolling  | 1         | 1.18%   |
| Ubuntu Budgie 22.04 | 1         | 1.18%   |
| Ubuntu Budgie 21.10 | 1         | 1.18%   |
| Ubuntu Budgie 20.04 | 1         | 1.18%   |
| Ubuntu 21.04        | 1         | 1.18%   |
| Ubuntu 19.04        | 1         | 1.18%   |
| Solus 4.1           | 1         | 1.18%   |
| Pop!_OS 21.04       | 1         | 1.18%   |
| Pop!_OS 20.04       | 1         | 1.18%   |
| Manjaro 22.0.0      | 1         | 1.18%   |
| Manjaro 21.1.2      | 1         | 1.18%   |
| Manjaro 20.1        | 1         | 1.18%   |
| Lubuntu 21.04       | 1         | 1.18%   |
| LMDE 4              | 1         | 1.18%   |
| Linux Mint 21       | 1         | 1.18%   |
| Linux Mint 20.2     | 1         | 1.18%   |
| Linux Mint 20       | 1         | 1.18%   |
| Linux Mint 19.3     | 1         | 1.18%   |
| Kubuntu 20.04       | 1         | 1.18%   |
| KDE neon 22.04      | 1         | 1.18%   |
| KDE neon 20.04      | 1         | 1.18%   |
| Fedora 37           | 1         | 1.18%   |
| Fedora 34           | 1         | 1.18%   |
| Fedora 33           | 1         | 1.18%   |
| Fedora 32           | 1         | 1.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 30        | 35.71%  |
| Fedora        | 10        | 11.9%   |
| Linux Mint    | 8         | 9.52%   |
| Pop!_OS       | 4         | 4.76%   |
| OpenMandriva  | 4         | 4.76%   |
| Debian        | 4         | 4.76%   |
| Ubuntu Budgie | 3         | 3.57%   |
| Manjaro       | 3         | 3.57%   |
| Xubuntu       | 2         | 2.38%   |
| KDE neon      | 2         | 2.38%   |
| Clear Linux   | 2         | 2.38%   |
| ArcoLinux     | 2         | 2.38%   |
| Arch          | 2         | 2.38%   |
| Zorin         | 1         | 1.19%   |
| Void Linux    | 1         | 1.19%   |
| Solus         | 1         | 1.19%   |
| Lubuntu       | 1         | 1.19%   |
| LMDE          | 1         | 1.19%   |
| Kubuntu       | 1         | 1.19%   |
| Elementary    | 1         | 1.19%   |
| Archcraft     | 1         | 1.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-48-generic        | 4         | 4.17%   |
| 5.4.0-42-generic        | 3         | 3.13%   |
| 5.13.0-22-generic       | 3         | 3.13%   |
| 5.4.0-77-generic        | 2         | 2.08%   |
| 5.4.0-52-generic        | 2         | 2.08%   |
| 5.4.0-33-generic        | 2         | 2.08%   |
| 5.3.0-51-generic        | 2         | 2.08%   |
| 5.16.7-desktop-1omv4003 | 2         | 2.08%   |
| 5.15.0-53-generic       | 2         | 2.08%   |
| 5.15.0-41-generic       | 2         | 2.08%   |
| 6.0.6-300.fc37.x86_64   | 1         | 1.04%   |
| 5.9.12-xanmod1          | 1         | 1.04%   |
| 5.9.11-arch2-1          | 1         | 1.04%   |
| 5.9.1-arch1-1           | 1         | 1.04%   |
| 5.8.8-arch1-1           | 1         | 1.04%   |
| 5.8.15-301.fc33.x86_64  | 1         | 1.04%   |
| 5.8.12_1                | 1         | 1.04%   |
| 5.8.0-38-generic        | 1         | 1.04%   |
| 5.7.10-201.fc32.x86_64  | 1         | 1.04%   |
| 5.6.19-158.current      | 1         | 1.04%   |
| 5.4.60-2-MANJARO        | 1         | 1.04%   |
| 5.4.15-200.fc31.x86_64  | 1         | 1.04%   |
| 5.4.0-7642-generic      | 1         | 1.04%   |
| 5.4.0-74-generic        | 1         | 1.04%   |
| 5.4.0-72-generic        | 1         | 1.04%   |
| 5.4.0-39-generic        | 1         | 1.04%   |
| 5.4.0-29-generic        | 1         | 1.04%   |
| 5.4.0-28-generic        | 1         | 1.04%   |
| 5.4.0-26-generic        | 1         | 1.04%   |
| 5.4.0-109-generic       | 1         | 1.04%   |
| 5.4.0-105-generic       | 1         | 1.04%   |
| 5.3.0-61-generic        | 1         | 1.04%   |
| 5.3.0-46-generic        | 1         | 1.04%   |
| 5.3.0-42-generic        | 1         | 1.04%   |
| 5.3.0-28-generic        | 1         | 1.04%   |
| 5.3.0-19-generic        | 1         | 1.04%   |
| 5.19.7-arch1-1          | 1         | 1.04%   |
| 5.19.14-200.fc36.x86_64 | 1         | 1.04%   |
| 5.19.12-200.fc36.x86_64 | 1         | 1.04%   |
| 5.18.17-200.fc36.x86_64 | 1         | 1.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 23.6%   |
| 5.13.0  | 8         | 8.99%   |
| 5.15.0  | 7         | 7.87%   |
| 5.3.0   | 6         | 6.74%   |
| 5.11.0  | 6         | 6.74%   |
| 5.10.0  | 3         | 3.37%   |
| 5.0.0   | 3         | 3.37%   |
| 5.16.7  | 2         | 2.25%   |
| 4.19.0  | 2         | 2.25%   |
| 6.0.6   | 1         | 1.12%   |
| 5.9.12  | 1         | 1.12%   |
| 5.9.11  | 1         | 1.12%   |
| 5.9.1   | 1         | 1.12%   |
| 5.8.8   | 1         | 1.12%   |
| 5.8.15  | 1         | 1.12%   |
| 5.8.12  | 1         | 1.12%   |
| 5.8.0   | 1         | 1.12%   |
| 5.7.10  | 1         | 1.12%   |
| 5.6.19  | 1         | 1.12%   |
| 5.4.60  | 1         | 1.12%   |
| 5.4.15  | 1         | 1.12%   |
| 5.19.7  | 1         | 1.12%   |
| 5.19.14 | 1         | 1.12%   |
| 5.19.12 | 1         | 1.12%   |
| 5.18.17 | 1         | 1.12%   |
| 5.18.13 | 1         | 1.12%   |
| 5.18.11 | 1         | 1.12%   |
| 5.17.4  | 1         | 1.12%   |
| 5.15.76 | 1         | 1.12%   |
| 5.13.13 | 1         | 1.12%   |
| 5.12.9  | 1         | 1.12%   |
| 5.12.14 | 1         | 1.12%   |
| 5.11.15 | 1         | 1.12%   |
| 5.11.12 | 1         | 1.12%   |
| 5.10.19 | 1         | 1.12%   |
| 5.10.14 | 1         | 1.12%   |
| 5.0.10  | 1         | 1.12%   |
| 4.19.8  | 1         | 1.12%   |
| 4.18.0  | 1         | 1.12%   |
| 4.15.0  | 1         | 1.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 26.14%  |
| 5.13    | 9         | 10.23%  |
| 5.15    | 8         | 9.09%   |
| 5.11    | 8         | 9.09%   |
| 5.3     | 6         | 6.82%   |
| 5.10    | 5         | 5.68%   |
| 5.8     | 4         | 4.55%   |
| 5.0     | 4         | 4.55%   |
| 5.9     | 3         | 3.41%   |
| 5.19    | 3         | 3.41%   |
| 4.19    | 3         | 3.41%   |
| 5.18    | 2         | 2.27%   |
| 5.16    | 2         | 2.27%   |
| 5.12    | 2         | 2.27%   |
| 6.0     | 1         | 1.14%   |
| 5.7     | 1         | 1.14%   |
| 5.6     | 1         | 1.14%   |
| 5.17    | 1         | 1.14%   |
| 4.18    | 1         | 1.14%   |
| 4.15    | 1         | 1.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 81        | 96.43%  |
| i686   | 3         | 3.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 40        | 47.06%  |
| KDE5       | 11        | 12.94%  |
| XFCE       | 8         | 9.41%   |
| X-Cinnamon | 7         | 8.24%   |
| Unknown    | 7         | 8.24%   |
| Budgie     | 4         | 4.71%   |
| KDE        | 3         | 3.53%   |
| sway       | 1         | 1.18%   |
| MATE       | 1         | 1.18%   |
| LXQt       | 1         | 1.18%   |
| LXDE       | 1         | 1.18%   |
| DWM        | 1         | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 69        | 81.18%  |
| Wayland | 12        | 14.12%  |
| Unknown | 4         | 4.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 47        | 55.95%  |
| SDDM    | 10        | 11.9%   |
| GDM     | 10        | 11.9%   |
| GDM3    | 7         | 8.33%   |
| LightDM | 6         | 7.14%   |
| TDM     | 4         | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 49        | 57.65%  |
| es_DO   | 19        | 22.35%  |
| Unknown | 7         | 8.24%   |
| es_ES   | 3         | 3.53%   |
| es_MX   | 2         | 2.35%   |
| en_CA   | 2         | 2.35%   |
| ru_RU   | 1         | 1.18%   |
| fr_FR   | 1         | 1.18%   |
| C       | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 47        | 55.95%  |
| EFI  | 37        | 44.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 68        | 80.95%  |
| Btrfs   | 7         | 8.33%   |
| Overlay | 5         | 5.95%   |
| Xfs     | 2         | 2.38%   |
| F2fs    | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 49        | 58.33%  |
| GPT     | 27        | 32.14%  |
| MBR     | 8         | 9.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 85.88%  |
| Yes       | 12        | 14.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 71.43%  |
| Yes       | 24        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 27        | 32.14%  |
| Lenovo              | 16        | 19.05%  |
| Hewlett-Packard     | 11        | 13.1%   |
| ASUSTek Computer    | 7         | 8.33%   |
| Acer                | 5         | 5.95%   |
| Apple               | 4         | 4.76%   |
| Samsung Electronics | 2         | 2.38%   |
| MSI                 | 2         | 2.38%   |
| EVOO                | 2         | 2.38%   |
| Toshiba             | 1         | 1.19%   |
| TODOS INDUSTRIAL    | 1         | 1.19%   |
| SAELITE             | 1         | 1.19%   |
| Nuvision            | 1         | 1.19%   |
| Google              | 1         | 1.19%   |
| Fujitsu             | 1         | 1.19%   |
| Eluktronics         | 1         | 1.19%   |
| ECS                 | 1         | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| EVOO EV-C-116-7                                   | 2         | 2.38%   |
| Dell Latitude E6540                               | 2         | 2.38%   |
| Dell Latitude E6430                               | 2         | 2.38%   |
| Dell Latitude E6420                               | 2         | 2.38%   |
| Dell Latitude E6410                               | 2         | 2.38%   |
| Dell Inspiron 5570                                | 2         | 2.38%   |
| Apple MacBookPro8,1                               | 2         | 2.38%   |
| Toshiba Satellite C55-A                           | 1         | 1.19%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 1.19%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 1.19%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 1.19%   |
| SAELITE ES1AU11                                   | 1         | 1.19%   |
| Nuvision NES11                                    | 1         | 1.19%   |
| MSI GE62 6QC                                      | 1         | 1.19%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 1.19%   |
| Lenovo Z50-75 80EC                                | 1         | 1.19%   |
| Lenovo ThinkPad W540 20BHS0GB06                   | 1         | 1.19%   |
| Lenovo ThinkPad T490 20N3S7BC02                   | 1         | 1.19%   |
| Lenovo ThinkPad T480s 20L7CTO1WW                  | 1         | 1.19%   |
| Lenovo ThinkPad T470 20HD004AUS                   | 1         | 1.19%   |
| Lenovo ThinkPad T420s 41732BU                     | 1         | 1.19%   |
| Lenovo ThinkPad T410 2537N99                      | 1         | 1.19%   |
| Lenovo ThinkPad P43s 20RH0013US                   | 1         | 1.19%   |
| Lenovo ThinkPad E470 20H1006DUS                   | 1         | 1.19%   |
| Lenovo ThinkBook 14s-IWL 20RM                     | 1         | 1.19%   |
| Lenovo Legion 5 15ARH05 82B5                      | 1         | 1.19%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 1         | 1.19%   |
| Lenovo IdeaPad 320-15IKB 80XL                     | 1         | 1.19%   |
| Lenovo IdeaPad 3 15ALC6 82KU                      | 1         | 1.19%   |
| Lenovo G505s 20255                                | 1         | 1.19%   |
| Lenovo G40-70 20369                               | 1         | 1.19%   |
| HP ProBook 6470b                                  | 1         | 1.19%   |
| HP Pavilion ze2000 (EC201UA#ABA)                  | 1         | 1.19%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 1         | 1.19%   |
| HP Pavilion dv6                                   | 1         | 1.19%   |
| HP Notebook                                       | 1         | 1.19%   |
| HP Laptop 15-bw0xx                                | 1         | 1.19%   |
| HP G60                                            | 1         | 1.19%   |
| HP ENVY Laptop 13-ad0xx                           | 1         | 1.19%   |
| HP EliteBook 8540w                                | 1         | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 17        | 20.24%  |
| Lenovo ThinkPad            | 8         | 9.52%   |
| Dell Inspiron              | 8         | 9.52%   |
| Acer Aspire                | 5         | 5.95%   |
| Lenovo IdeaPad             | 3         | 3.57%   |
| HP Pavilion                | 3         | 3.57%   |
| HP EliteBook               | 2         | 2.38%   |
| EVOO EV-C-116-7            | 2         | 2.38%   |
| Dell Vostro                | 2         | 2.38%   |
| ASUS VivoBook              | 2         | 2.38%   |
| Apple MacBookPro8          | 2         | 2.38%   |
| Toshiba Satellite          | 1         | 1.19%   |
| TODOS INDUSTRIAL Easytouch | 1         | 1.19%   |
| Samsung RV420              | 1         | 1.19%   |
| Samsung 905S3G             | 1         | 1.19%   |
| SAELITE ES1AU11            | 1         | 1.19%   |
| Nuvision NES11             | 1         | 1.19%   |
| MSI GE62                   | 1         | 1.19%   |
| MSI CR70                   | 1         | 1.19%   |
| Lenovo Z50-75              | 1         | 1.19%   |
| Lenovo ThinkBook           | 1         | 1.19%   |
| Lenovo Legion              | 1         | 1.19%   |
| Lenovo G505s               | 1         | 1.19%   |
| Lenovo G40-70              | 1         | 1.19%   |
| HP ProBook                 | 1         | 1.19%   |
| HP Notebook                | 1         | 1.19%   |
| HP Laptop                  | 1         | 1.19%   |
| HP G60                     | 1         | 1.19%   |
| HP ENVY                    | 1         | 1.19%   |
| HP 250                     | 1         | 1.19%   |
| Google Winky               | 1         | 1.19%   |
| Fujitsu LIFEBOOK           | 1         | 1.19%   |
| Eluktronics P670RE3        | 1         | 1.19%   |
| ECS ClassMate              | 1         | 1.19%   |
| ASUS ZenBook               | 1         | 1.19%   |
| ASUS X553MA                | 1         | 1.19%   |
| ASUS TUF                   | 1         | 1.19%   |
| ASUS T100TA                | 1         | 1.19%   |
| ASUS K53E                  | 1         | 1.19%   |
| Apple MacBookPro5          | 1         | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 10        | 11.9%   |
| 2017 | 9         | 10.71%  |
| 2014 | 9         | 10.71%  |
| 2013 | 9         | 10.71%  |
| 2019 | 8         | 9.52%   |
| 2012 | 7         | 8.33%   |
| 2020 | 4         | 4.76%   |
| 2018 | 4         | 4.76%   |
| 2010 | 4         | 4.76%   |
| 2008 | 4         | 4.76%   |
| 2021 | 3         | 3.57%   |
| 2015 | 3         | 3.57%   |
| 2009 | 3         | 3.57%   |
| 2016 | 2         | 2.38%   |
| 2007 | 2         | 2.38%   |
| 2022 | 1         | 1.19%   |
| 2006 | 1         | 1.19%   |
| 2005 | 1         | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 84        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 80        | 95.24%  |
| Enabled  | 4         | 4.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 98.81%  |
| Yes  | 1         | 1.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 26        | 30.95%  |
| 4.01-8.0   | 23        | 27.38%  |
| 8.01-16.0  | 12        | 14.29%  |
| 16.01-24.0 | 11        | 13.1%   |
| 2.01-3.0   | 4         | 4.76%   |
| 1.01-2.0   | 4         | 4.76%   |
| 32.01-64.0 | 3         | 3.57%   |
| 24.01-32.0 | 1         | 1.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 34        | 36.96%  |
| 2.01-3.0 | 26        | 28.26%  |
| 3.01-4.0 | 18        | 19.57%  |
| 4.01-8.0 | 9         | 9.78%   |
| 0.51-1.0 | 5         | 5.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 62        | 73.81%  |
| 2      | 22        | 26.19%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 54.76%  |
| Yes       | 38        | 45.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 84.52%  |
| No        | 13        | 15.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 97.62%  |
| No        | 2         | 2.38%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 67.86%  |
| No        | 27        | 32.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 84        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 54        | 62.79%  |
| Santiago de los Caballeros | 9         | 10.47%  |
| La Romana                  | 4         | 4.65%   |
| Santo Domingo              | 3         | 3.49%   |
| Santa Cruz de Barahona     | 2         | 2.33%   |
| Alejandro Bass             | 2         | 2.33%   |
| Sosua, Cabarete            | 1         | 1.16%   |
| Santo Domingo Oeste        | 1         | 1.16%   |
| San Pedro de Macorís      | 1         | 1.16%   |
| San Cristobal              | 1         | 1.16%   |
| Punta Cana                 | 1         | 1.16%   |
| Los Hidalgos               | 1         | 1.16%   |
| Guaymate                   | 1         | 1.16%   |
| Constanza                  | 1         | 1.16%   |
| Concepción de la Vega     | 1         | 1.16%   |
| Boca Chica                 | 1         | 1.16%   |
| Baní                      | 1         | 1.16%   |
| Bajos de Haina             | 1         | 1.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 20        | 25     | 20%     |
| WDC                       | 10        | 13     | 10%     |
| Toshiba                   | 10        | 12     | 10%     |
| Samsung Electronics       | 10        | 11     | 10%     |
| SanDisk                   | 8         | 11     | 8%      |
| Hitachi                   | 8         | 9      | 8%      |
| Kingston                  | 5         | 5      | 5%      |
| Unknown                   | 4         | 5      | 4%      |
| SK hynix                  | 4         | 5      | 4%      |
| Unknown                   | 3         | 3      | 3%      |
| Transcend                 | 2         | 2      | 2%      |
| Micron Technology         | 2         | 2      | 2%      |
| FORESEE                   | 2         | 2      | 2%      |
| UMIS                      | 1         | 1      | 1%      |
| SPCC                      | 1         | 1      | 1%      |
| PNY                       | 1         | 1      | 1%      |
| OCZ                       | 1         | 1      | 1%      |
| Micron/Crucial Technology | 1         | 1      | 1%      |
| LITEONIT                  | 1         | 2      | 1%      |
| Intel                     | 1         | 1      | 1%      |
| Indilinx                  | 1         | 1      | 1%      |
| Hewlett-Packard           | 1         | 1      | 1%      |
| Eluktro                   | 1         | 1      | 1%      |
| China                     | 1         | 1      | 1%      |
| A-DATA Technology         | 1         | 1      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Seagate ST500LM000-1EJ162 500GB | 3         | 2.94%   |
| Unknown                         | 3         | 2.94%   |
| Unknown MMC Card  32GB          | 2         | 1.96%   |
| Toshiba MQ01ACF050 500GB        | 2         | 1.96%   |
| Toshiba MK3275GSX 320GB         | 2         | 1.96%   |
| Seagate ST9250315AS 250GB       | 2         | 1.96%   |
| Seagate ST1000LM049-2GH172 1TB  | 2         | 1.96%   |
| Seagate ST1000LM035-1RK172 1TB  | 2         | 1.96%   |
| SanDisk NVMe SSD Drive 256GB    | 2         | 1.96%   |
| Samsung SSD 860 EVO 500GB       | 2         | 1.96%   |
| FORESEE 128GB SSD               | 2         | 1.96%   |
| WDC WDS100T2G0A-00JH30 1TB SSD  | 1         | 0.98%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1         | 0.98%   |
| WDC WD3200LPVX-75V0TT0 320GB    | 1         | 0.98%   |
| WDC WD3200BEVT-75A23T0 320GB    | 1         | 0.98%   |
| WDC WD2500BEVT-75A23T0 250GB    | 1         | 0.98%   |
| WDC WD2500BEVS-22UST0 250GB     | 1         | 0.98%   |
| WDC WD1600BEVT-75ZCT1 160GB     | 1         | 0.98%   |
| WDC WD10SPZX-24Z10T0 1TB        | 1         | 0.98%   |
| WDC WD10JPVX-60JC3T1 1TB        | 1         | 0.98%   |
| WDC WD10JPCX-24UE4T0 1TB        | 1         | 0.98%   |
| Unknown MMC Card  64GB          | 1         | 0.98%   |
| Unknown MMC Card  16GB          | 1         | 0.98%   |
| Unknown MMC Card  128GB         | 1         | 0.98%   |
| UMIS RPJTJ256MEE1OWX 256GB      | 1         | 0.98%   |
| Transcend TS256GSSD340 256GB    | 1         | 0.98%   |
| Transcend TS128GSSD370S 128GB   | 1         | 0.98%   |
| Toshiba NVMe SSD Drive 1024GB   | 1         | 0.98%   |
| Toshiba MQ01ABF050 500GB        | 1         | 0.98%   |
| Toshiba MQ01ABD100 1TB          | 1         | 0.98%   |
| Toshiba MK6475GSX 640GB         | 1         | 0.98%   |
| Toshiba MK3276GSX 320GB         | 1         | 0.98%   |
| Toshiba MK2556GSY 250GB         | 1         | 0.98%   |
| SPCC Solid State Disk 512GB     | 1         | 0.98%   |
| SK hynix SC311 SATA 256GB SSD   | 1         | 0.98%   |
| SK hynix NVMe SSD Drive 256GB   | 1         | 0.98%   |
| SK hynix HCG8e  64GB            | 1         | 0.98%   |
| SK hynix C2S3T/240G 240GB SSD   | 1         | 0.98%   |
| Seagate ST9750420AS 752GB       | 1         | 0.98%   |
| Seagate ST9500325AS 500GB       | 1         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 20        | 25     | 43.48%  |
| WDC     | 9         | 12     | 19.57%  |
| Toshiba | 9         | 11     | 19.57%  |
| Hitachi | 8         | 9      | 17.39%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 6         | 9      | 18.75%  |
| Samsung Electronics | 6         | 7      | 18.75%  |
| Kingston            | 4         | 4      | 12.5%   |
| Transcend           | 2         | 2      | 6.25%   |
| SK hynix            | 2         | 2      | 6.25%   |
| FORESEE             | 2         | 2      | 6.25%   |
| WDC                 | 1         | 1      | 3.13%   |
| SPCC                | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| LITEONIT            | 1         | 2      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |
| Eluktro             | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |
| Unknown             | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 44        | 57     | 46.32%  |
| SSD     | 29        | 37     | 30.53%  |
| NVMe    | 14        | 15     | 14.74%  |
| MMC     | 7         | 8      | 7.37%   |
| Unknown | 1         | 1      | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 67        | 91     | 73.63%  |
| NVMe | 14        | 15     | 15.38%  |
| MMC  | 7         | 8      | 7.69%   |
| SAS  | 3         | 4      | 3.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 69     | 71.83%  |
| 0.51-1.0   | 17        | 21     | 23.94%  |
| 1.01-2.0   | 2         | 2      | 2.82%   |
| 3.01-4.0   | 1         | 2      | 1.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 35.63%  |
| 251-500        | 17        | 19.54%  |
| 501-1000       | 15        | 17.24%  |
| 1-20           | 6         | 6.9%    |
| 51-100         | 6         | 6.9%    |
| 21-50          | 4         | 4.6%    |
| 1001-2000      | 4         | 4.6%    |
| Unknown        | 2         | 2.3%    |
| More than 3000 | 1         | 1.15%   |
| 2001-3000      | 1         | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 36        | 38.3%   |
| 21-50     | 20        | 21.28%  |
| 51-100    | 16        | 17.02%  |
| 101-250   | 10        | 10.64%  |
| 251-500   | 4         | 4.26%   |
| 501-1000  | 3         | 3.19%   |
| 1001-2000 | 2         | 2.13%   |
| Unknown   | 2         | 2.13%   |
| 2001-3000 | 1         | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MK3276GSX 320GB         | 1         | 1      | 12.5%   |
| Toshiba MK3275GSX 320GB         | 1         | 1      | 12.5%   |
| Seagate ST9750420AS 752GB       | 1         | 1      | 12.5%   |
| Seagate ST500LM021-1KJ152 500GB | 1         | 1      | 12.5%   |
| Seagate ST2000LM007-1R8174 2TB  | 1         | 1      | 12.5%   |
| Hitachi HTS727550A9E364 500GB   | 1         | 1      | 12.5%   |
| Hitachi HTS725032A9A364 320GB   | 1         | 1      | 12.5%   |
| Hitachi HTS547575A9E384 752GB   | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 37.5%   |
| Hitachi | 3         | 3      | 37.5%   |
| Toshiba | 2         | 2      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 37.5%   |
| Hitachi | 3         | 3      | 37.5%   |
| Toshiba | 2         | 2      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 100%    |

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
| Detected | 55        | 82     | 63.22%  |
| Works    | 24        | 28     | 27.59%  |
| Malfunc  | 8         | 8      | 9.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 62        | 69.66%  |
| AMD                          | 13        | 14.61%  |
| Samsung Electronics          | 4         | 4.49%   |
| SanDisk                      | 2         | 2.25%   |
| Micron Technology            | 2         | 2.25%   |
| Union Memory (Shenzhen)      | 1         | 1.12%   |
| Toshiba America Info Systems | 1         | 1.12%   |
| SK hynix                     | 1         | 1.12%   |
| Nvidia                       | 1         | 1.12%   |
| Micron/Crucial Technology    | 1         | 1.12%   |
| Kingston Technology Company  | 1         | 1.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 12        | 12.77%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 9         | 9.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 8         | 8.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 7.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 6.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 5.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 4         | 4.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 4.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 3.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 3.19%   |
| Micron Non-Volatile memory controller                                                  | 2         | 2.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 2.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 2         | 2.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 2.13%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 1.06%   |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 1.06%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 1         | 1.06%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.06%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 1.06%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.06%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 1.06%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 1.06%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.06%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 1.06%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 1         | 1.06%   |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 1.06%   |
| AMD FCH IDE Controller                                                                 | 1         | 1.06%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 58        | 64.44%  |
| NVMe | 14        | 15.56%  |
| RAID | 9         | 10%     |
| IDE  | 9         | 10%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 70        | 83.33%  |
| AMD    | 14        | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 4.76%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 4.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 3.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.38%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 2.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 2.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 2.38%   |
| Intel Core i5-2415M CPU @ 2.30GHz           | 2         | 2.38%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 2.38%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 2.38%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.19%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.19%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.19%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 1.19%   |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 1.19%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.19%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.19%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 1.19%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.19%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.19%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.19%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.19%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.19%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.19%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 1.19%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 1.19%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.19%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.19%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.19%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.19%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.19%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 1         | 1.19%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.19%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 27        | 32.14%  |
| Intel Core i7           | 13        | 15.48%  |
| Intel Celeron           | 11        | 13.1%   |
| Intel Core i3           | 7         | 8.33%   |
| Intel Core 2 Duo        | 3         | 3.57%   |
| AMD Ryzen 5             | 3         | 3.57%   |
| Intel Core 2            | 2         | 2.38%   |
| Intel Atom              | 2         | 2.38%   |
| AMD Ryzen 7             | 2         | 2.38%   |
| AMD A8                  | 2         | 2.38%   |
| AMD A10                 | 2         | 2.38%   |
| Intel Pentium Dual-Core | 1         | 1.19%   |
| Intel Pentium Dual      | 1         | 1.19%   |
| Intel Pentium           | 1         | 1.19%   |
| Intel Genuine           | 1         | 1.19%   |
| Intel Core i9           | 1         | 1.19%   |
| AMD Quad-Core           | 1         | 1.19%   |
| AMD Mobile Sempron      | 1         | 1.19%   |
| AMD A6                  | 1         | 1.19%   |
| AMD A4                  | 1         | 1.19%   |
| AMD A12                 | 1         | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 57        | 67.86%  |
| 4      | 21        | 25%     |
| 8      | 2         | 2.38%   |
| 6      | 2         | 2.38%   |
| 1      | 2         | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 84        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 55        | 65.48%  |
| 1      | 29        | 34.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 82        | 97.62%  |
| 32-bit         | 1         | 1.19%   |
| Unknown        | 1         | 1.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 17.86%  |
| 0x206a7    | 10        | 11.9%   |
| 0x306a9    | 6         | 7.14%   |
| 0x806e9    | 5         | 5.95%   |
| 0x40651    | 5         | 5.95%   |
| 0x806ea    | 4         | 4.76%   |
| 0x706a1    | 4         | 4.76%   |
| 0x1067a    | 4         | 4.76%   |
| 0x306c3    | 3         | 3.57%   |
| 0x07030105 | 3         | 3.57%   |
| 0x806ec    | 2         | 2.38%   |
| 0x6f6      | 2         | 2.38%   |
| 0x506e3    | 2         | 2.38%   |
| 0x30678    | 2         | 2.38%   |
| 0x20652    | 2         | 2.38%   |
| 0x6fd      | 1         | 1.19%   |
| 0x506c9    | 1         | 1.19%   |
| 0x406c3    | 1         | 1.19%   |
| 0x20655    | 1         | 1.19%   |
| 0x106ca    | 1         | 1.19%   |
| 0x10676    | 1         | 1.19%   |
| 0x08608103 | 1         | 1.19%   |
| 0x08608102 | 1         | 1.19%   |
| 0x08600103 | 1         | 1.19%   |
| 0x08108109 | 1         | 1.19%   |
| 0x08108102 | 1         | 1.19%   |
| 0x0700010f | 1         | 1.19%   |
| 0x0600611a | 1         | 1.19%   |
| 0x06003106 | 1         | 1.19%   |
| 0x06001119 | 1         | 1.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 19.05%  |
| SandyBridge   | 10        | 11.9%   |
| Haswell       | 9         | 10.71%  |
| IvyBridge     | 8         | 9.52%   |
| Westmere      | 5         | 5.95%   |
| Silvermont    | 5         | 5.95%   |
| Penryn        | 5         | 5.95%   |
| Goldmont plus | 5         | 5.95%   |
| Puma          | 3         | 3.57%   |
| Core          | 3         | 3.57%   |
| Zen+          | 2         | 2.38%   |
| Skylake       | 2         | 2.38%   |
| Unknown       | 2         | 2.38%   |
| Zen 2         | 1         | 1.19%   |
| Steamroller   | 1         | 1.19%   |
| Piledriver    | 1         | 1.19%   |
| K8 Hammer     | 1         | 1.19%   |
| K10 Llano     | 1         | 1.19%   |
| Jaguar        | 1         | 1.19%   |
| Goldmont      | 1         | 1.19%   |
| Excavator     | 1         | 1.19%   |
| Bonnell       | 1         | 1.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 66        | 68.04%  |
| AMD    | 19        | 19.59%  |
| Nvidia | 12        | 12.37%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 8.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 7.84%   |
| Intel UHD Graphics 620                                                                   | 6         | 5.88%   |
| Intel HD Graphics 620                                                                    | 5         | 4.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 4.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 4.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 3.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.94%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.96%   |
| Intel HD Graphics 530                                                                    | 2         | 1.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.96%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.96%   |
| AMD Lucienne                                                                             | 2         | 1.96%   |
| Nvidia TU117M                                                                            | 1         | 0.98%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.98%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.98%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 1         | 0.98%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.98%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.98%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.98%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 0.98%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.98%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.98%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.98%   |
| Intel HD Graphics 500                                                                    | 1         | 0.98%   |
| Intel Haswell Integrated Graphics Controller                                             | 1         | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.98%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.98%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.98%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.98%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.98%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 0.98%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.98%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 65.48%  |
| 1 x AMD        | 11        | 13.1%   |
| Intel + Nvidia | 7         | 8.33%   |
| Intel + AMD    | 4         | 4.76%   |
| 1 x Nvidia     | 3         | 3.57%   |
| 2 x AMD        | 2         | 2.38%   |
| AMD + Nvidia   | 2         | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 77        | 91.67%  |
| Proprietary | 6         | 7.14%   |
| Unknown     | 1         | 1.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 72.62%  |
| 1.01-2.0   | 7         | 8.33%   |
| 0.01-0.5   | 7         | 8.33%   |
| 0.51-1.0   | 6         | 7.14%   |
| 3.01-4.0   | 2         | 2.38%   |
| 2.01-3.0   | 1         | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 19.59%  |
| LG Display              | 15        | 15.46%  |
| BOE                     | 14        | 14.43%  |
| Chimei Innolux          | 11        | 11.34%  |
| Samsung Electronics     | 10        | 10.31%  |
| Dell                    | 5         | 5.15%   |
| Chi Mei Optoelectronics | 5         | 5.15%   |
| Apple                   | 4         | 4.12%   |
| Hewlett-Packard         | 2         | 2.06%   |
| ZTR                     | 1         | 1.03%   |
| Westinghouse            | 1         | 1.03%   |
| Vizio                   | 1         | 1.03%   |
| Unknown (XXX)           | 1         | 1.03%   |
| Sony                    | 1         | 1.03%   |
| Philips                 | 1         | 1.03%   |
| PANDA                   | 1         | 1.03%   |
| LG Philips              | 1         | 1.03%   |
| Lenovo                  | 1         | 1.03%   |
| KDC                     | 1         | 1.03%   |
| InnoLux Display         | 1         | 1.03%   |
| Goldstar                | 1         | 1.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 2.06%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 2.06%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 2.06%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 2.06%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 2.06%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 2         | 2.06%   |
| ZTR LCD Monitor ZTR0001 1366x768 256x144mm 11.6-inch                  | 1         | 1.03%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch          | 1         | 1.03%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1         | 1.03%   |
| Unknown (XXX) V56 XXX0030 1920x1080 708x398mm 32.0-inch               | 1         | 1.03%   |
| Sony TV SNY1703 1360x768 1600x900mm 72.3-inch                         | 1         | 1.03%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 610x350mm 27.7-inch  | 1         | 1.03%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch             | 1         | 1.03%   |
| PANDA LC116LF1L02 NCP000F 1920x1080 256x144mm 11.6-inch               | 1         | 1.03%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD03AE 1366x768 345x194mm 15.6-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD0357 1600x900 382x215mm 17.3-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 1.03%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch               | 1         | 1.03%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 1         | 1.03%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch      | 1         | 1.03%   |
| Hewlett-Packard E221c HWP3093 1920x1080 497x292mm 22.7-inch           | 1         | 1.03%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch             | 1         | 1.03%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                 | 1         | 1.03%   |
| Dell P2212H DELA07E 1920x1080 531x299mm 24.0-inch                     | 1         | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 40        | 43.96%  |
| 1920x1080 (FHD)    | 28        | 30.77%  |
| 1280x800 (WXGA)    | 7         | 7.69%   |
| 1600x900 (HD+)     | 6         | 6.59%   |
| 3840x2160 (4K)     | 2         | 2.2%    |
| 1280x1024 (SXGA)   | 2         | 2.2%    |
| 3840x1100          | 1         | 1.1%    |
| 1680x1050 (WSXGA+) | 1         | 1.1%    |
| 1360x768           | 1         | 1.1%    |
| 1280x768           | 1         | 1.1%    |
| 1024x768 (XGA)     | 1         | 1.1%    |
| 1024x600           | 1         | 1.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 42        | 43.75%  |
| 13      | 15        | 15.63%  |
| 14      | 12        | 12.5%   |
| 11      | 8         | 8.33%   |
| 17      | 4         | 4.17%   |
| 24      | 2         | 2.08%   |
| 22      | 2         | 2.08%   |
| 72      | 1         | 1.04%   |
| 40      | 1         | 1.04%   |
| 34      | 1         | 1.04%   |
| 32      | 1         | 1.04%   |
| 31      | 1         | 1.04%   |
| 23      | 1         | 1.04%   |
| 21      | 1         | 1.04%   |
| 20      | 1         | 1.04%   |
| 19      | 1         | 1.04%   |
| 10      | 1         | 1.04%   |
| Unknown | 1         | 1.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 61.7%   |
| 201-300     | 17        | 18.09%  |
| 351-400     | 6         | 6.38%   |
| 401-500     | 4         | 4.26%   |
| 501-600     | 3         | 3.19%   |
| 701-800     | 2         | 2.13%   |
| 801-900     | 1         | 1.06%   |
| 601-700     | 1         | 1.06%   |
| 1501-2000   | 1         | 1.06%   |
| Unknown     | 1         | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 72        | 84.71%  |
| 16/10   | 8         | 9.41%   |
| 5/4     | 2         | 2.35%   |
| 4/3     | 1         | 1.18%   |
| 3.40    | 1         | 1.18%   |
| Unknown | 1         | 1.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 42        | 43.75%  |
| 81-90          | 21        | 21.88%  |
| 51-60          | 9         | 9.38%   |
| 201-250        | 6         | 6.25%   |
| 71-80          | 5         | 5.21%   |
| 121-130        | 3         | 3.13%   |
| 351-500        | 2         | 2.08%   |
| 151-200        | 2         | 2.08%   |
| 501-1000       | 2         | 2.08%   |
| More than 1000 | 1         | 1.04%   |
| 41-50          | 1         | 1.04%   |
| 141-150        | 1         | 1.04%   |
| Unknown        | 1         | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 41        | 44.09%  |
| 121-160       | 31        | 33.33%  |
| 51-100        | 14        | 15.05%  |
| 1-50          | 3         | 3.23%   |
| 161-240       | 2         | 2.15%   |
| More than 240 | 1         | 1.08%   |
| Unknown       | 1         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 69        | 81.18%  |
| 2     | 13        | 15.29%  |
| 0     | 2         | 2.35%   |
| 3     | 1         | 1.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 32.56%  |
| Realtek Semiconductor           | 39        | 30.23%  |
| Qualcomm Atheros                | 22        | 17.05%  |
| Broadcom                        | 12        | 9.3%    |
| Qualcomm Atheros Communications | 2         | 1.55%   |
| Marvell Technology Group        | 2         | 1.55%   |
| Lenovo                          | 2         | 1.55%   |
| Broadcom Limited                | 2         | 1.55%   |
| Ralink Technology               | 1         | 0.78%   |
| Nvidia                          | 1         | 0.78%   |
| MediaTek                        | 1         | 0.78%   |
| JCM                             | 1         | 0.78%   |
| Dell                            | 1         | 0.78%   |
| AMD                             | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 11.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 7.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 4.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 4.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 3.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 3.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 2.48%   |
| Intel Wireless 7260                                               | 4         | 2.48%   |
| Intel Wireless 3165                                               | 4         | 2.48%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.86%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.86%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.86%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.24%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 1.24%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 1.24%   |
| Lenovo Thinkpad LAN                                               | 2         | 1.24%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.24%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.24%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.24%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.24%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.24%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.24%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.62%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.62%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 46.51%  |
| Qualcomm Atheros                | 19        | 22.09%  |
| Realtek Semiconductor           | 12        | 13.95%  |
| Broadcom                        | 9         | 10.47%  |
| Qualcomm Atheros Communications | 2         | 2.33%   |
| Ralink Technology               | 1         | 1.16%   |
| MediaTek                        | 1         | 1.16%   |
| Dell                            | 1         | 1.16%   |
| Broadcom Limited                | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 7         | 8.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 5.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 5         | 5.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 4.6%    |
| Intel Wireless 7260                                                                   | 4         | 4.6%    |
| Intel Wireless 3165                                                                   | 4         | 4.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 3.45%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 3.45%   |
| Intel Centrino Advanced-N 6235                                                        | 3         | 3.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 3         | 3.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2         | 2.3%    |
| Realtek 802.11n WLAN Adapter                                                          | 2         | 2.3%    |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 2.3%    |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 2.3%    |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 2.3%    |
| Intel Centrino Advanced-N 6200                                                        | 2         | 2.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 2.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 2.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.15%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.15%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 1.15%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 1.15%   |
| Intel Wireless 8260                                                                   | 1         | 1.15%   |
| Intel Wireless 7265                                                                   | 1         | 1.15%   |
| Intel Wireless 3160                                                                   | 1         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.15%   |
| Intel Centrino Wireless-N 6150                                                        | 1         | 1.15%   |
| Intel Centrino Wireless-N 2230                                                        | 1         | 1.15%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 1.15%   |
| Intel Centrino Wireless-N + WiMAX 6150                                                | 1         | 1.15%   |
| Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card                             | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 32        | 44.44%  |
| Intel                    | 23        | 31.94%  |
| Broadcom                 | 6         | 8.33%   |
| Qualcomm Atheros         | 5         | 6.94%   |
| Marvell Technology Group | 2         | 2.78%   |
| Lenovo                   | 2         | 2.78%   |
| Nvidia                   | 1         | 1.39%   |
| Broadcom Limited         | 1         | 1.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 25%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 16.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 11.11%  |
| Intel 82577LM Gigabit Network Connection                          | 4         | 5.56%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 4.17%   |
| Lenovo Thinkpad LAN                                               | 2         | 2.78%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.39%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.39%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.39%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.39%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.39%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.39%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.39%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 1.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.39%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.39%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 52.9%   |
| Ethernet | 71        | 45.81%  |
| Modem    | 2         | 1.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 67        | 77.01%  |
| Ethernet | 20        | 22.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 68        | 80.95%  |
| 1     | 13        | 15.48%  |
| 0     | 3         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 98.81%  |
| Yes  | 1         | 1.19%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 42.11%  |
| Qualcomm Atheros Communications | 10        | 17.54%  |
| IMC Networks                    | 5         | 8.77%   |
| Dell                            | 5         | 8.77%   |
| Realtek Semiconductor           | 4         | 7.02%   |
| Apple                           | 4         | 7.02%   |
| Lite-On Technology              | 2         | 3.51%   |
| Broadcom                        | 2         | 3.51%   |
| Hewlett-Packard                 | 1         | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 14        | 24.56%  |
| Qualcomm Atheros  Bluetooth Device             | 5         | 8.77%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 4         | 7.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 3         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 5.26%   |
| IMC Networks Bluetooth Radio                   | 3         | 5.26%   |
| Dell BCM20702A0 Bluetooth Module               | 3         | 5.26%   |
| Apple Bluetooth Host Controller                | 3         | 5.26%   |
| Realtek Bluetooth Radio                        | 2         | 3.51%   |
| Intel AX200 Bluetooth                          | 2         | 3.51%   |
| Realtek RTL8723B Bluetooth                     | 1         | 1.75%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 1.75%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 1.75%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 1.75%   |
| Lite-On Wireless_Device                        | 1         | 1.75%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 1.75%   |
| IMC Networks Bluetooth Device                  | 1         | 1.75%   |
| IMC Networks Bluetooth                         | 1         | 1.75%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 1.75%   |
| Dell Wireless 360 Bluetooth                    | 1         | 1.75%   |
| Dell Wireless 350 Bluetooth                    | 1         | 1.75%   |
| Broadcom HP Portable SoftSailing               | 1         | 1.75%   |
| Broadcom BCM43142 Bluetooth 4.0                | 1         | 1.75%   |
| Apple Bluetooth HCI                            | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 68        | 72.34%  |
| AMD                 | 15        | 15.96%  |
| Nvidia              | 8         | 8.51%   |
| Sony                | 1         | 1.06%   |
| Logitech            | 1         | 1.06%   |
| C-Media Electronics | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 9.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 7.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 7.89%   |
| AMD FCH Azalia Controller                                                                         | 7         | 6.14%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 4.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 4.39%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 4.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 4.39%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 4.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 3.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 2.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.63%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.75%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.88%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.88%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.88%   |
| Logitech Logi USB Headset                                                                         | 1         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.88%   |
| C-Media Electronics USB PnP Sound Device                                                          | 1         | 0.88%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.88%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.88%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 1         | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.88%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.88%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 17        | 34%     |
| Samsung Electronics | 12        | 24%     |
| Micron Technology   | 7         | 14%     |
| Unknown (ABCD)      | 2         | 4%      |
| Ramaxel Technology  | 2         | 4%      |
| Nanya Technology    | 2         | 4%      |
| Kingston            | 2         | 4%      |
| Crucial             | 2         | 4%      |
| Unknown             | 1         | 2%      |
| Sesame              | 1         | 2%      |
| A-DATA Technology   | 1         | 2%      |
| Unknown             | 1         | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.77%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.77%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 3.77%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 3.77%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 3.77%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.89%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.89%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 1.89%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.89%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.89%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.89%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.89%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.89%   |
| SK hynix RAM HMA851S6DJR6N-XN 4096MB Row Of Chips DDR4 3200MT/s  | 1         | 1.89%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.89%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 1         | 1.89%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.89%   |
| Sesame RAM S939A2SGS-ITR 8192MB SODIMM DDR4 2667MT/s             | 1         | 1.89%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 1         | 1.89%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 1         | 1.89%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.89%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 1         | 1.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.89%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.89%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.89%   |
| Ramaxel RAM RMT3010EC58E8F1333 2048MB SODIMM DDR3 1600MT/s       | 1         | 1.89%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s          | 1         | 1.89%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.89%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR2 2048MT/s             | 1         | 1.89%   |
| Micron RAM H6451U67F1600G 4GB SODIMM DDR3 1333MT/s               | 1         | 1.89%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 16        | 41.03%  |
| DDR4   | 14        | 35.9%   |
| LPDDR4 | 4         | 10.26%  |
| SDRAM  | 3         | 7.69%   |
| LPDDR3 | 1         | 2.56%   |
| DDR2   | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 92.31%  |
| Row Of Chips | 2         | 5.13%   |
| DIMM         | 1         | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 18        | 42.86%  |
| 8192  | 12        | 28.57%  |
| 2048  | 7         | 16.67%  |
| 16384 | 5         | 11.9%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 13        | 29.55%  |
| 2667  | 9         | 20.45%  |
| 2400  | 6         | 13.64%  |
| 1333  | 3         | 6.82%   |
| 4199  | 2         | 4.55%   |
| 3200  | 2         | 4.55%   |
| 2133  | 2         | 4.55%   |
| 1334  | 2         | 4.55%   |
| 3266  | 1         | 2.27%   |
| 2048  | 1         | 2.27%   |
| 1867  | 1         | 2.27%   |
| 1067  | 1         | 2.27%   |
| 667   | 1         | 2.27%   |

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
| Chicony Electronics                    | 13        | 18.57%  |
| Microdia                               | 10        | 14.29%  |
| Sunplus Innovation Technology          | 7         | 10%     |
| IMC Networks                           | 7         | 10%     |
| Realtek Semiconductor                  | 6         | 8.57%   |
| Suyin                                  | 5         | 7.14%   |
| Syntek                                 | 4         | 5.71%   |
| Apple                                  | 4         | 5.71%   |
| Silicon Motion                         | 3         | 4.29%   |
| Ricoh                                  | 3         | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.86%   |
| Sonix Technology                       | 1         | 1.43%   |
| Primax Electronics                     | 1         | 1.43%   |
| Logitech                               | 1         | 1.43%   |
| globaloptics                           | 1         | 1.43%   |
| Alcor Micro                            | 1         | 1.43%   |
| Acer                                   | 1         | 1.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD               | 5         | 7.14%   |
| Chicony integrated camera                  | 4         | 5.71%   |
| IMC Networks Integrated Camera             | 3         | 4.29%   |
| Syntek Lenovo EasyCamera                   | 2         | 2.86%   |
| Microdia Sonix USB 2.0 Camera              | 2         | 2.86%   |
| Microdia Integrated_Webcam_HD              | 2         | 2.86%   |
| Microdia Integrated Webcam                 | 2         | 2.86%   |
| Microdia Dell Integrated HD Webcam         | 2         | 2.86%   |
| IMC Networks USB2.0 HD UVC WebCam          | 2         | 2.86%   |
| Apple FaceTime HD Camera                   | 2         | 2.86%   |
| Syntek Integrated Camera                   | 1         | 1.43%   |
| Syntek EasyCamera                          | 1         | 1.43%   |
| Suyin VGA Webcam                           | 1         | 1.43%   |
| Suyin TOSHIBA Web Camera - HD              | 1         | 1.43%   |
| Suyin HP TrueVision HD                     | 1         | 1.43%   |
| Suyin Acer/Lenovo Webcam [CN0316]          | 1         | 1.43%   |
| Suyin 1.3M HD WebCam                       | 1         | 1.43%   |
| Sunplus Laptop_Integrated_Webcam_HD        | 1         | 1.43%   |
| Sunplus Laptop_Integrated_Webcam_FHD       | 1         | 1.43%   |
| Sonix HP Webcam-101                        | 1         | 1.43%   |
| Silicon Motion WebCam SCB-0385N            | 1         | 1.43%   |
| Silicon Motion WebCam SC-10HDD13335N       | 1         | 1.43%   |
| Silicon Motion Real HD WebCam              | 1         | 1.43%   |
| Ricoh Laptop_Integrated_Webcam_FHD         | 1         | 1.43%   |
| Ricoh Integrated Webcam                    | 1         | 1.43%   |
| Ricoh HD Webcam                            | 1         | 1.43%   |
| Realtek USB Camera                         | 1         | 1.43%   |
| Realtek Integrated Webcam HD               | 1         | 1.43%   |
| Realtek Integrated Webcam                  | 1         | 1.43%   |
| Realtek Integrated Camera                  | 1         | 1.43%   |
| Realtek HP Wide Vision HD Camera           | 1         | 1.43%   |
| Realtek HP Truevision HD integrated webcam | 1         | 1.43%   |
| Primax HP HD Webcam [Fixed]                | 1         | 1.43%   |
| Microdia Laptop_Integrated_Webcam_E4HD     | 1         | 1.43%   |
| Microdia Laptop_Integrated_Webcam_2M       | 1         | 1.43%   |
| Logitech QuickCam Pro 4000                 | 1         | 1.43%   |
| IMC Networks UVC VGA Webcam                | 1         | 1.43%   |
| IMC Networks USB2.0 HD IR UVC WebCam       | 1         | 1.43%   |
| globaloptics Integrated Camera 2M          | 1         | 1.43%   |
| Chicony USB2.0 HD UVC WebCam               | 1         | 1.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 54.55%  |
| Synaptics                  | 3         | 27.27%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| LighTuning Technology      | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 18.18%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 9.09%   |
| Validity Sensors VFS491                           | 1         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors Synaptics WBDI                   | 1         | 9.09%   |
| Validity Sensors Fingerprint scanner              | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device               | 1         | 9.09%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 66.67%  |
| O2 Micro    | 2         | 22.22%  |
| Alcor Micro | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 22.22%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 59        | 70.24%  |
| 1     | 21        | 25%     |
| 2     | 4         | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 37.93%  |
| Chipcard              | 8         | 27.59%  |
| Graphics card         | 3         | 10.34%  |
| Storage               | 2         | 6.9%    |
| Multimedia controller | 2         | 6.9%    |
| Net/wireless          | 1         | 3.45%   |
| Card reader           | 1         | 3.45%   |
| Bluetooth             | 1         | 3.45%   |

